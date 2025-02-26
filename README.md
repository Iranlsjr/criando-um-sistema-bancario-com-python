# Desafio - Sistema Bancário (Versão 1)

## Descrição

Fomos contratados por um grande banco para desenvolver a primeira versão do seu novo sistema bancário. O objetivo dessa versão inicial é implementar três operações principais:

1. **Depósito**
2. **Saque**
3. **Extrato**

A primeira versão (v1) do sistema será simples e trabalhará com apenas **1 usuário**, sem a necessidade de identificar o número da agência ou conta bancária.

---

## Funcionalidades

### 1. Operação de Depósito

- **Objetivo**: Permitir que o usuário deposite valores positivos em sua conta bancária.
- **Detalhes**:
  - O sistema deve aceitar **apenas valores positivos**.
  - Todos os depósitos realizados devem ser armazenados em uma variável.
  - A operação de extrato deve listar todos os depósitos realizados.
  - Os valores devem ser exibidos no formato **R$ xxx.xx**, exemplo: **R$ 1500.45**.

---

### 2. Operação de Saque

- **Objetivo**: Permitir que o usuário realize saques de sua conta.
- **Detalhes**:
  - O sistema deve permitir até **3 saques diários**, com um **limite máximo de R$ 500,00 por saque**.
  - Caso o usuário não tenha saldo suficiente, o sistema deve exibir uma mensagem informando a impossibilidade de realizar o saque devido à **falta de saldo**.
  - Todos os saques realizados devem ser armazenados em uma variável.
  - Os valores dos saques devem ser exibidos no formato **R$ xxx.xx**, exemplo: **R$ 300.00**.

---

### 3. Operação de Extrato

- **Objetivo**: Exibir o histórico de depósitos e saques realizados, bem como o saldo atual.
- **Detalhes**:
  - O extrato deve listar **todos os depósitos** e **todos os saques** realizados na conta.
  - No final da listagem, o **saldo atual** deve ser exibido.
  - O saldo deve ser calculado como a diferença entre os **depósitos** e os **saques**.
  - O valor do saldo deve ser exibido no formato **R$ xxx.xx**, exemplo: **R$ 1200.50**.

---

## Requisitos

- **Depósitos**: Devem ser armazenados em uma lista e exibidos no extrato.
- **Saques**: Devem ser armazenados em uma lista e exibidos no extrato.
- **Saldo**: Calculado dinamicamente a partir dos depósitos e saques, e exibido no final do extrato.

---

## Exemplos de Exibição

- **Depósito**: `R$ 500.00`
- **Saque**: `R$ 300.00`
- **Extrato**:
