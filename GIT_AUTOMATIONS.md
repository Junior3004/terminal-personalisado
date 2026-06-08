# 🚀 Guia de Automações Git (Windows CMD)

Este guia contém as instruções para as personalizações e comandos rápidos configurados para otimizar seu fluxo de trabalho com Git.

---

## ⚡ Comando Combinado: `up`

O comando `up` automatiza o fluxo de adicionar, commitar e enviar alterações com um único comando.

**Uso:**
```cmd
up "sua mensagem de commit"
```

**O que ele faz por baixo dos panos:**
1. `git add .` (Adiciona todas as modificações)
2. `git commit -m "sua mensagem"` (Cria o commit com a mensagem passada)
3. `git push` (Envia para o repositório remoto)

---

## ⌨️ Atalhos Individuais (Git Aliases)

Se você preferir executar os comandos um por um, pode usar estes atalhos curtos:

| Comando Original | Atalho Curto | Descrição |
| :--- | :--- | :--- |
| `git status` | `git s` | Verifica o status dos arquivos |
| `git add .` | `git a` | Adiciona todas as mudanças |
| `git commit -m "msg"`| `git c "msg"`| Cria um commit com mensagem |
| `git push` | `git p` | Envia as alterações |

---

## 🛠️ Detalhes Técnicos (Onde está instalado?)

Para que esses comandos funcionem globalmente no seu Windows:

1.  **Script Batch:** O comando `up` está localizado em `C:\scripts\up.bat`.
2.  **Variável de Ambiente:** A pasta `C:\scripts` foi adicionada ao seu **PATH** de usuário.
3.  **Aliases:** Os atalhos curtos (`s`, `a`, `c`, `p`) estão salvos na sua configuração global do Git (`~/.gitconfig`).

> **Nota:** Se o comando `up` não for reconhecido, feche e abra o seu terminal CMD para que o Windows atualize as variáveis de ambiente.

---
*Configuração realizada em 08 de Junho de 2026.*
