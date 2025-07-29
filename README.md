# Dio-Sistema-Bancário
V1 - Projeto Sistema Bancário Simples em Python
V2 - Projeto Modularizado do Sistema Bancário

## V1 Desafio - Criar Sistema Bancário em Python ##

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

## V2 Desafio - Modularizar Sistema Bancário em Python ##

Vamos otimizar nosso Sistema Bancário, modularizando com funções Python. O objetivo é aprimorar a estrutura e a eficiência do sistema, implementando as operações de depósito, saque e extrato em funções específicas. Refatoramos o código existente, dividindo em funções reutilizáveis, facilitando a manutenção e o entendimento do sistema como um todo.

1. Criar funções para operações existentes:
   - [ ] depósito,
   - [ ] saque, e
   - [ ] extrato
  
2. Criar duas novas funções:
   - [ ] criar usuário, e
   - [ ] criar conta corrente

A função Saque deve receber os argumentos por nome (keyword only).
A função Depósito deve receber os argumentos apenas por posição (positional only).
A função Extrato deve receber os argumentos por posição e nome.
A função Criar usuário (cliente) deve armazenar os usuários em uma lista: nome, data de nascimento, cpf e endereço. Endereço é uma String com formato: logradouro, número - bairro - cidade/sigla estado. CPF deve ser apenas números e não pode haver dois clientes com mesmo CPF.
A função Criar conta corrente é composta por: agência, número da conta e usuário. o número da conta é sequencial, inciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

