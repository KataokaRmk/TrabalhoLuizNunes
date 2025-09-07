# TrabalhoLuizNunes

# Gerenciador de Tarefas em Java (Web Local)

Aplicação Java minimalista que implementa um **servidor HTTP** com interface web para criar, listar, atualizar e excluir tarefas.  
A persistência é feita em um arquivo CSV simples (`data_tasks.csv`) e o frontend em HTML/JS já vem embutido no código.

## Funcionalidades
- Criar tarefas com título e descrição.
- Visualizar tarefas agrupadas por status: **pendente**, **em andamento** e **concluída**.
- Atualizar o status de uma tarefa (avanço ou retrocesso).
- Excluir tarefas.
- Armazenamento automático em arquivo CSV para manter os dados entre execuções.

## Como executar
1. Tenha o **JDK 11+** instalado.
2. Compile e rode:
```bash
javac App.java
java App
