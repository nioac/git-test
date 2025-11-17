# Projeto de Exemplos de Arquivos e Comandos (branch descrição)

Este repositório contém arquivos de exemplo, comandos básicos de Bash, comandos Git e uma breve explicação de fluxo de trabalho para quem está começando a utilizar terminal e versionamento de código.

## Estrutura dos arquivos

- **arquivo_01.txt**:  
  Informações do curso e anotações adicionais.

- **arquivo_02.txt**:  
  Informações e exemplos variados de texto, incluindo linhas fora do contexto de nuvem.

- **comandos_bash.txt**:  
  Lista de comandos básicos do Bash para gerenciamento de diretórios e arquivos.

- **comandos_git.txt**:  
  Comandos Git essenciais para controlar o versionamento, histórico e branches, além do fluxo de trabalho sugerido.

- **comandos_sec.txt**:  
  Informações adicionais e exemplos de alterações e enumeração.

---

## Exemplos de Comandos Bash

```
ls       # Lista arquivos/diretórios na pasta atual
cd       # Troca o diretório de trabalho
pwd      # Mostra o diretório atual
cat      # Exibe o conteúdo de um arquivo
rm       # Remove arquivo
rm -rf   # Remove diretórios e arquivos de forma recursiva
```

## Exemplos de Comandos Git

```
git init                     # Inicializa repositório Git na pasta atual
git status                   # Exibe o status dos arquivos no repositorio
git add <nome_arquivo>       # Adiciona arquivo para ser commitado
git commit -m "mensagem"     # Realiza o commit
git log                      # Exibe o histórico de commits
git diff <arquivo>           # Mostra diferenças no arquivo especificado
git checkout -b <nova_branch># Cria uma nova branch
git branch                   # Lista todas as branches existentes
git checkout <branch>        # Troca para a branch escolhida
git merge <outra_branch>     # Mescla branch escolhida com sua branch atual
git show                     # Mostra objetos do Git
```

### Fluxo de Trabalho

1. Criar o diretório do projeto
2. Iniciar o Git no diretório (`git init .`)
3. Editar ou criar arquivos necessários
4. Verificar status dos arquivos (`git status`)
5. Adicionar arquivos com `git add <nome_arquivo>`
6. Verificar novamente com `git status`
7. Realizar o commit (`git commit -m "mensagem"`)
8. Repetir a partir do passo 3 conforme a necessidade

---

## Observações

- Este repositório serve de apoio para quem está começando e deseja visualizar exemplos práticos de arquivos, comandos Bash e comandos Git.
- Sinta-se livre para consultar os arquivos, fazer alterações e praticar os comandos descritos!
