# Criando um Banco Digital com Java e Orientação a Objetos

-- GFT Start #5 Java

### UML

- Uma pessoa no sistema deve conter seguintes características: nome, gênero, data de nascimento e CPF.
- Uma instituição bancária deverá ser criada assim que a aplicação inicia e ela deve possuir os seguintes dados: nome, data de criação e o código da agência bancária.
  -. requisitos:
  . Uma pessoa deve possuir apenas uma conta cadastrada
  . Uma conta deve ser definida da seguinte forma: agência, número, pessoa, ativa e saldo.
  -. Em uma conta digital deve ser possível ter ou fazer: transferência bancária para outra pessoa, solicitar cartão de crédito, sacar e depositar dinheiro.
  . Em uma transação bancária deve conter os dados da conta de quem está transferindo, quem está recebendo e data dessa operação e verificar se o saldo de quem está transferindo é menor ou igual ao saldo disponível dessa pessoa.
  . Para solicitação de cartão de crédito deverá ser analisado o saldo que essa pessoa possui, caso ela tenha a mais de R$ 50,00 a solicitação deverá ser aprovada e deve ser gerado automaticamente o número do cartão, data de expiração e o código de segurança.
  . No saque de dinheiro o sistema deverá verificar o saldo atual e ver se aquele valor é menor ou igual ao saldo da conta.
  . No depósito de dinheiro deve ser obrigatoriamente identificado para qual conta está sendo depositado e o valor do depósito.

### Requisitos para utilização

Deve-se ter instalado a versão do Java [1.7](https://docs.oracle.com/javase/7/docs/api/)

### Como compilar

Para compilar o projeto basta executar o comando abaixo:

```bash
cd local_projeto/wallet-java/src/br/esig/com/nujava/main/
```

```java
javac BancoDigital.java
```

- **Rodrigo Paim**
