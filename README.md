# sistema-bancario-python


## Requisitos do sistema:

A seguir a lista de requisitos do sistema divididos por suas funcionalidades.

### Operação de depósito

- Deve ser possível depositar valores positivos.
- Não é necessário número de agência nem número da conta bancária.
- Todos os depósitos devem ser exibidos no extrato.

### Operação de saque

- O sistema deve permitir 3 saques diários com limite máximo de 500 reais por saque.
- Caso não exista saldo, o sistema deve exibir uma mensagem informando.
- Todos os saques devem ser exibidos no extrato.

### Operação de extrato

- Essa operação deve listar todos os depósitos e saques em conta.
- Ao final deve ser exibido o saldo atual em conta.
- Caso o extrato esteja em branco, exiba: "não foram realizadas movimentações".
- Formatação padrão: R$ xxx.xx