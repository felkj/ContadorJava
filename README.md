# Contador Java 🚀

Este é um projeto simples em Java que recebe dois números do usuário e realiza uma contagem entre eles. Se o primeiro número for maior ou igual ao segundo, uma exceção personalizada é lançada.

## 📋 Funcionalidades

- Lê dois parâmetros inteiros via terminal.
- Verifica se o segundo número é maior que o primeiro.
- Realiza uma contagem do 1 até a diferença entre os dois números.
- Lança uma exceção personalizada (`ParametrosInvalidosException`) se a ordem dos parâmetros estiver incorreta.

## 💻 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
2. Compile o código:
   ```bash
   javac Contador.java ParametrosInvalidosException.java
3. Execute:
  ``` bash
   java Contador
```
📄 Exemplo de uso
 ```bash
   Digite o primeiro parâmetro.
   2
   Digite o segundo parâmetro.
   5
   Imprimindo o número 0
   Imprimindo o número 1
   Imprimindo o número 2
   Imprimindo o número 3.
```
⚠️ Tratamento de erros
Se o primeiro número for maior ou igual ao segundo, será exibida a mensagem:
   ```bash
   O segundo parâmetro deve ser maior que o primeiro.
```
🛠️ Tecnologias
Java 17+ (mas funciona em versões anteriores também)

Feito por Felipe Silva
