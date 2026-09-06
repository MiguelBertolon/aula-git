# 📚 Tabela de Estudos Detalhada — Git & GitHub

## Comandos Básicos de Git

| Comando | Função |
|---|---|
| `git init` | Cria um novo repositório Git |
| `git status` | Mostra o estado dos arquivos (staged, modified, untracked) |
| `git add <arquivo>` | Move arquivo para a área de staging |
| `git commit -m "mensagem"` | Salva as alterações no histórico |

## Comandos de Repositório Remoto

| Comando | Função |
|---|---|
| `git clone <url>` | Clona um repositório remoto |
| `git push origin main` | Envia commits para o repositório remoto |
| `git pull origin main` | Baixa e mescla alterações do remoto |
| `git remote -v` | Lista os repositórios remotos configurados |

## Branches e Merge

| Comando | Função |
|---|---|
| `git branch <nome>` | Cria uma nova branch |
| `git checkout <branch>` | Muda para outra branch |
| `git merge <branch>` | Mescla alterações de uma branch na atual |
| `git branch -d <nome>` | Deleta uma branch local |

## Conventional Commits

| Prefixo | Uso |
|---|---|
| `feat:` | Nova funcionalidade ou conteúdo |
| `fix:` | Correção de erro |
| `docs:` | Alterações em documentação |
| `chore:` | Tarefas de manutenção/organização |


## Fluxo de Trabalho Colaborativo (Resumo)

1. `git pull` para atualizar antes de trabalhar
2. Editar arquivos
3. `git add` + `git commit -m "mensagem clara"`
4. `git pull` novamente (garantir sincronização)
5. `git push` para enviar ao repositório remoto