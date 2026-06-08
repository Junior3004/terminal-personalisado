# Contexto do Projeto: Terminal Personalizado

Este diretório é um repositório de configurações e automações para o terminal Windows (CMD), focado em aumentar a produtividade no uso do Git e outras ferramentas de linha de comando.

## 📂 Visão Geral do Diretório

O projeto não contém código-fonte de aplicação, mas sim scripts de automação global e documentação de suporte para o ambiente de desenvolvimento local do usuário.

### Arquivos Principais

- **`GIT_AUTOMATIONS.md`**: Guia detalhado de uso para o comando personalizado `up` e aliases globais do Git (`git s`, `git a`, `git c`, `git p`).
- **`GEMINI.md`**: Este arquivo de instruções para o agente Gemini.

## 🛠️ Configurações do Sistema

As automações configuradas através deste projeto dependem de elementos externos ao diretório:

1.  **Pasta de Scripts Globais**: Localizada em `C:\scripts\`.
2.  **Scripts Batch**:
    - `up.bat`: Automatiza o fluxo `git add .` + `git commit` + `git push`.
3.  **PATH do Windows**: A pasta `C:\scripts` deve estar no PATH do usuário para que os comandos funcionem em qualquer local.
4.  **Git Config**: Aliases globais configurados no arquivo `.gitconfig` do usuário.

## 📖 Instruções de Uso para o Agente

Ao atuar neste diretório ou em projetos relacionados para este usuário:

- **Preferência de Terminal**: O usuário utiliza predominantemente o **CMD** (Command Prompt).
- **Fluxo de Trabalho Git**: Priorize o uso do comando `up "mensagem"` para salvar progresso, a menos que uma operação granular seja necessária.
- **Linguagem**: Todas as interações e documentações devem ser em **Português do Brasil**.
- **Novas Automações**: Sempre que criar novos scripts `.bat` em `C:\scripts`, atualize o `GIT_AUTOMATIONS.md` e verifique se o comando está acessível via PATH.
