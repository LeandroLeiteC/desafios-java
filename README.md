## Desafio Criando um Banco

Neste desafio você criará um software que simulará um Banco.

#### Requisitos do projeto

##### Requisitos funcionais
- O software deve ser interativo pelo console
- Deve ser feito em Java
- Deve-se utilizar Orientação a Objeto

##### Regras de negócio
- Deve ser possível abrir contas do tipo _corrente_ e do tipo _poupança_
- Para se cadastrar no Banco é preciso informar:
    - CPF (Não precisa ser válidado por enquanto)
    - Nome Completo
    - Data de Nascimento
    - Senha
- Não deve permitir menores de idade criar conta
- Não deve permitir que um mesmo CPF tenha mais de 1 conta.
- Deve permitir fazer login na conta informando _CPF_ e _Senha_
- Deve permitir fazer depósitos
- Deve permitir fazer saques
    - Contas corrente devem possuir cheque especial no valor de R$ 100.00
    - Contas poupança devem possuir cheque especial no valor de R$ 250.00
    - Contas corrente não possuem taxa de saque 
    - Contas poupança possuem uma taxa de R$ 2.50 por saque
    - Não deve permitir fazer um saque se todo o cheque especial foi utilizado
- Deve permitir fechar uma conta somente se seu saldo estiver zerado

##### Desafio Bônus
- Deve permitir fazer transferência para outra conta do banco
- Uma vez logado deve permitir alterar a senha
- Deve ter a função _esqueci minha senha_ permitindo alterar a senha da conta se:
    - O usuário informar a _Data de Nascimento_ correta
    - O usuário informar seu _Nome Completo_ corretamente
