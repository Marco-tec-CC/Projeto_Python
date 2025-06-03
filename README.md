# 🏥 Sistema de Fila de Espera Hospitalar

## Grupo

- Marco Aurélio de Araújo Fernandes  
- Ysaac William Barbosa Viana Colaço 

---

## 📝 Descrição do Projeto

Este projeto é uma aplicação em Python com interface gráfica feita em **Tkinter**, que simula a triagem de pacientes em uma fila de espera hospitalar.  
A lógica de prioridade segue os **níveis de gravidade usados pelo SUS**, organizando os pacientes de forma automática conforme o risco.

---

## 🎯 Objetivo

O sistema tem como finalidade aplicar conceitos de **programação orientada a objetos**, **interfaces gráficas com Tkinter** e **manipulação de arquivos com `pickle`**, simulando uma situação real de atendimento hospitalar.

---

## ✅ Funcionalidades

- 👤 Adicionar pacientes com nome, idade e gravidade.
- 📋 Visualizar lista de espera ordenada por prioridade.
- 🔔 Chamar o próximo paciente da fila.
- ❌ Remover paciente da fila pelo nome.
- 💾 Salvar e carregar a lista automaticamente de um arquivo `.pkl`.

---

## 🚦 Níveis de Gravidade (Triagem do SUS)

| Cor      | Gravidade     | Prioridade |
|----------|---------------|------------|
| 🔴 Vermelho | Emergência     | 1 (mais urgente) |
| 🟡 Amarelo  | Urgente        | 2 |
| 🟢 Verde    | Pouco urgente  | 3 |
| 🔵 Azul     | Não urgente    | 4 (menos urgente) |

---

## 💻 Tecnologias Utilizadas

- Python 3.6+
- Tkinter (interface gráfica)
- Pickle (salvamento de dados)
- Git & GitHub
