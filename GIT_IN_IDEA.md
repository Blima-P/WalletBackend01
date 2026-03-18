# Guia: Como usar o Git no IntelliJ IDEA

Este projeto foi inicializado com uma estrutura básica Spring Boot.

## 1. Abrir o Projeto
1. Abra o IntelliJ IDEA.
2. Clique em **File** > **Open**.
3. Selecione a pasta `WalletBackend01`.
4. O IntelliJ detectará o `pom.xml` e configurará o projeto automaticamente.

## 2. Commit (Salvar Alterações)
Quando você faz alterações no código e quer salvá-las no histórico:
1. Pressione `Ctrl + K` (ou clique no ícone de "Check" verde na barra superior à esquerda, ou aba "Commit" na esquerda).
2. Selecione os arquivos que deseja commitar.
3. Escreva uma mensagem descrevendo o que você fez (ex: "Criando entidade Usuario").
4. Clique em **Commit**.

## 3. Push (Enviar para o GitHub)
Para enviar seus commits para o servidor (GitHub):
1. Pressione `Ctrl + Shift + K` (ou vá em **Git** > **Push** no menu superior).
2. Verifique os commits que serão enviados.
3. Clique em **Push**.
   *Nota: Se for a primeira vez, ele pode pedir suas credenciais do GitHub.*

## 4. Pull (Atualizar o Projeto)
Se houver alterações no GitHub que você não tem localmente:
1. Pressione `Ctrl + T` (ou vá em **Git** > **Update Project**).
2. Selecione "Merge" ou "Rebase" e clique em **OK**.

## Dica Rápida
A maioria das ações do Git pode ser encontrada no menu superior "Git".

---
**Estrutura do Projeto:**
- `src/main/java`: Seu código Java fica aqui.
- `src/main/resources/application.properties`: Configuração do banco de dados.
- `pom.xml`: Dependências do projeto (Spring Boot, MySQL, etc).
