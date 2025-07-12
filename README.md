# Dio-Sistema-Bancário
Projeto Sistema Bancário Simples em Python

## Desafio - Criar Sistema Bancário em Python ##

O Sistema Bancário deverá conter entre suas atribuições:

1. Implementar três operações essenciais:
   - [ ] depósito,
   - [ ] saque,
   - [ ] extrato.
3. O sistema será desenvolvido para um banco que busca monetizar suas operações - terá regras.

### Operação de DEPÓSITO ###

Deve ser possível depositar valores positivos para a conta bancária. A AV1 do projeto trabalha apenas com 1 usuário, então nesse momento não haverá identificação de conta e agência.
Todos os depósitos devem ser armazenados em uma variável e exibidos na operação EXTRATO.

### Operação de SAQUE ###

O sistema deve permitir realizar **3 SAQUES diários com limite máximo de R$ 500,00 por saque**. Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de saldo. _Todos os saques devem ser armazenados em uma variável e exibidos na operação de **EXTRATO**_.

### Operação de EXTRATO ###

Essa operação deve listar **todos** os depósitos e saques realizados na conta. No fim da listagem deve ser exibido o saldo atual da conta. Se o EXTRATO estiver em branco, exibir a mensagem: _Não foram realizadas movimentações_.
Os valores devem ser exibidos utilizando o formato moeda BR **R$ xxx.xx, - ex: 1500.45 = R$ 1500.45**
