# Sistema Bancário em Python

Este projeto é um sistema bancário simples desenvolvido em Python, executado no terminal. Ele permite ao usuário realizar operações básicas como depósito, saque e exibir extrato, simulando o funcionamento de uma conta bancária.

## Funcionalidades

- **Depósito**: Permite ao usuário depositar valores positivos em sua conta. O valor é somado ao saldo e registrado no extrato.
- **Saque**: Permite ao usuário sacar valores, respeitando o saldo disponível, um limite máximo por saque (R$ 500) e um limite diário de saques (3 saques por execução). Todas as validações são feitas para garantir a segurança da operação.
- **Extrato**: Exibe todas as movimentações realizadas (depósitos e saques) e o saldo atual da conta.
- **Menu interativo**: O usuário navega pelas opções através de um menu simples, digitando a letra correspondente à operação desejada.
- **Limpeza do console**: A cada exibição do menu, o console é limpo para melhor visualização.

## Como funciona o código

- O código está todo no arquivo `desafio.py`.
- As funções principais são:
  - `limpar_console()`: Limpa a tela do terminal.
  - `exibir_menu()`: Mostra o menu de opções e lê a escolha do usuário.
  - `depositar(saldo, extrato)`: Realiza depósitos, valida o valor e atualiza saldo e extrato.
  - `sacar(saldo, limite, numero_saques, extrato, limite_saques)`: Realiza saques, valida limites e atualiza saldo, extrato e número de saques.
  - `exibir_extrato(saldo, extrato)`: Mostra todas as movimentações e o saldo atual.
  - `main()`: Função principal que controla o fluxo do programa e gerencia o estado da conta.
- Todas as mensagens e variáveis estão em português para facilitar o entendimento.
- Não há armazenamento permanente: ao encerrar o programa, todas as informações são perdidas.

## Como executar

1. Certifique-se de ter o Python instalado.
2. No terminal, navegue até a pasta do projeto.
3. Execute o comando:
   ```
   python desafio.py
   ```
4. Siga as instruções exibidas no menu.

## Observações

- O sistema não utiliza bibliotecas externas, apenas módulos padrão do Python (`os` e `textwrap`).
- O código é didático, ideal para quem está aprendendo lógica de programação e manipulação de dados em Python.

---

Desenvolvido por Kevin.
