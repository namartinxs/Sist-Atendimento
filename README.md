# 🧍 Sistema de Gerenciamento de Senhas de Atendimento

Trabalho desenvolvido para a disciplina **Estrutura de Dados Lineares**, com o objetivo de aplicar conceitos de **filas**, **pilhas** e **simulação dinâmica** em um sistema que gerencia o fluxo de clientes em um ambiente de atendimento.

--- 

## 🎯 Objetivo

O sistema simula de forma dinâmica a geração e o atendimento de senhas em um ambiente com múltiplos postos de atendimento, considerando:
- Senhas **normais (N)** e **prioritárias (P)**;
- **Regras de prioridade e alternância (2N : 1P)**;
- **Ativação e desativação dinâmica** de postos;
- **Desistência aleatória** de clientes;
- Armazenamento em **pilha** das senhas atendidas.

---

## 🧰 Tecnologias utilizadas

- Python


---

## 🗂️ Estrutura do Projeto


---

## 📌 Funcionalidades

### ✅Tipos de Senha:
- Senhas Normais (N): Prioridade padrão.
- Senhas Prioritárias (P): Prioridade elevada.
### ✅Postos de Atendimento:
- O sistema deve suportar até 5 postos de atendimento.
- No mínimo 3 postos devem estar sempre disponíveis (ativos). Os demais podem ser ativados/desativados dinamicamente.
- Cada posto pode estar em dois estados: ocupado ou livre.
### ✅Lógica de Chamada de Senhas:
- A cada 2 senhas normais chamadas, 1 senha prioritária deve ser chamada.
- A prioridade das senhas é estrita: senhas prioritárias têm precedência, respeitando a regra de alternância (2N:1P).
### ✅Armazenamento de Senhas Atendidas:
- As senhas atendidas devem ser empilhadas em um mesmo local, mantendo o registro da ordem de atendimento.
### ✅Desistência de Clientes:
- O sistema deve simular a desistência aleatória de clientes que retiraram senhas, mas não aguardaram o atendimento.
### ✅Simulação Dinâmica:
- O programa deve simular continuamente a chegada de pessoas retirando senhas (normais e prioritárias, de forma aleatória).
- A simulação deve incluir o atendimento de senhas e a desistência de clientes, de forma dinâmica e aleatória.
### ✅Encerramento do Atendimento:
- Ao encerrarem os atendimentos (por exemplo, quando a fila de espera e os postos de atendimento estiverem vazios, ou por uma condição de encerramento definida), o sistema deverá mostrar todas as senhas atendidas, da última para a primeira.


---

## 🧪 Como rodar o projeto

---
## 📄 Documentação:

http://localhost:3000/api-docs

