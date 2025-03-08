# Sistema Bancário Simples

Este projeto é uma atividade prática proposta pela **DIO (Digital Innovation One)** como parte do **Bootcamp** que estou realizando. O objetivo é criar um sistema bancário simples em Python, aplicando os conceitos que venho aprendendo durante o curso.

---

## 🚀 Funcionalidades

O sistema bancário possui as seguintes funcionalidades:

### Depósito:
- Permite ao usuário depositar valores positivos.
- Os valores são adicionados ao saldo da conta.
- Todos os depósitos são registrados no extrato.

### Saque:
- Permite ao usuário sacar valores positivos.
- O sistema verifica se o valor do saque não excede o saldo disponível.
- Limite de **3 saques diários**, com um valor máximo de **R$ 500,00 por saque**.
- Todos os saques são registrados no extrato.

### Extrato:
- Exibe todas as operações de depósito e saque realizadas.
- Mostra o saldo atual da conta.
- Os valores são exibidos no formato **R$ XXX.XX**.

### Sair:
- Encerra a execução do sistema.

---

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver o sistema.
- **Estruturas de Controle**: Uso de `if`, `elif`, `else` e `while` para controlar o fluxo do programa.
- **Variáveis e Listas**: Armazenamento de dados como saldo, extrato e número de saques.
