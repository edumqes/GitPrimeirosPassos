# Treinamento Básico em Git

Este repositório foi criado com o objetivo de servir como material de apoio para capacitação Minsait - Git na Prática: Primeiros Passos

## Objetivos

- Entender os conceitos básicos de controle de versão
- Aprender os principais comandos do Git
- Praticar o fluxo de trabalho com repositórios locais e remotos (GitHub)

## Pré-requisitos

Antes de começar, é recomendável ter:

- Git instalado ([Instruções de instalação](https://git-scm.com/book/pt-br/v2/Instalação-Do-Git))
- Uma conta no GitHub

## Tópicos abordados

1. O que é sistema de controle de versão?
2. O que é o git?
3. Preparando o ambiente de trabalho
4. Primeiros passos: Você no controle!
5. Repositório remoto: Github
6. Histórico de atualizações
7. Ramificações: entendendo as branchs
8. 1° Up: Ignorando arquivos


## Comandos básicos:

   - `git init`
   - `git status`
   - `git add`
   - `git commit`
   - `git log`
   - `git diff`

## Trabalhando com repositórios remotos:
   - `git remote`
   - `git push`
   - `git pull`
   - `git clone`

## Criando e manipulando branches (branch criado Change_ReadMe):
   - `git branch`
   - `git checkout`
   - `git merge`

## Resolvendo conflitos

- Antes de efetuar merge na `main`, teste as alterações e resolva conflitos com atenção.

## Boas práticas

- Faça commits pequenos e frequentes, com mensagens claras e objetivas.
- Sempre atualize a branch local com `git pull` antes de iniciar o trabalho.
- Use `.gitignore` para evitar o versionamento de arquivos desnecessários (como logs e binários).
- Nunca faça commit de senhas, tokens ou dados sensíveis.
- Escreva mensagens de commit no imperativo, por exemplo: `Adiciona validação de formulário`.
- Revise o histórico de commits com `git log` antes de enviar alterações.

## Como usar este repositório

Link do repositório para avaliação utilizando chave SSH:

```bash
git clone git@github.com:edumqes/GitPrimeirosPassos.git
cd GitPrimeirosPassos

