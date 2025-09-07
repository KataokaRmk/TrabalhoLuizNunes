# TrabalhoLuizNunes

# Gerenciador de Tarefas em Java (Web Local)

Este projeto é uma aplicação simples feita em **Java**, que cria um servidor web local para gerenciar tarefas.  
A ideia é permitir que o usuário cadastre atividades, acompanhe o andamento e organize melhor o que precisa ser feito — tudo direto no navegador, sem precisar de frameworks pesados.

---

## O que o sistema faz
- Permite **criar tarefas**, com título e descrição.
- Organiza as tarefas em três estágios: **pendente**, **em andamento** e **concluída**.
- Dá a opção de **mudar o status** de cada tarefa (avançar ou voltar).
- Permite **excluir tarefas** quando não forem mais necessárias.
- Salva tudo em um arquivo CSV, para não perder os dados ao fechar o programa.

---

## Como executar
1. Tenha o **JDK 11+** instalado na sua máquina.
2. Compile e rode o programa:
   ```bash
   javac App.java
   java App.
   
---
##  Avaliação do Projeto

Este projeto funciona muito bem como exercício de aprendizado. Ele mostra de forma prática como criar um servidor HTTP em Java, responder a requisições, trabalhar com arquivos e ainda integrar um frontend básico em HTML/JS. Outro ponto positivo é que ele não exige bibliotecas externas — basta o Java para rodar.

Porém, como é uma versão simplificada, também tem suas limitações. O uso de arrays fixos para armazenar as tarefas deixa o código engessado, o parser manual de JSON pode dar problema em casos mais complexos, e o uso de CSV não é ideal para vários usuários acessando ao mesmo tempo. Além disso, não há nenhum tipo de autenticação, o que seria importante em cenários reais.

---
## Proposta de Substituição
Esse projeto funciona bem como protótipo, mas pode ser melhorado.
Um próximo passo seria organizar melhor o código (criando uma classe Task e usando coleções), adotar uma biblioteca de JSON (como Gson) e trocar o CSV por um banco simples como SQLite.

Se a ideia for algo mais completo, dá para evoluir para uma aplicação profissional com Spring Boot, banco de dados robusto (PostgreSQL/MySQL) e um frontend moderno (React ou Vue).
