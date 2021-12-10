# Introdução ao Git

- link para download
  - [git](https://git-scm.com/downloads)
  - debian/ubuntu - `sudo apt install git`

### Comandos básicos

Iniciar um repositório no [^1]CLI

- `git init`

Definir nome e e-mail

- `git config --global user.name {nome}` nome preferencialmente igual ao do github
- `git config --global user.email {email}` email preferencialmente igual do github

Obter ajuda

- `git help {comando}`
- `git {comando} --help`

Verificar o branch

- `git status`

Adicionando arquivos/pastas novos ou editados

- `git add {* / . incluir todos arquivos ou pastas / {nome do arquivo/pasta} incluir somente o arquivo ou pasta definido}`

Envelopando os arquivos/pastas novos ou editados

- `git commit -m "{mensagem}"`  *mensagem deve ser curta, simples e de fácil entendimento*

Ciclos git

- Tracked
  - Conhecido do git (todos os arquivos/pastas do repositorio que são conhecidos pelo git)
- Untracked
  - Não conhecido do git (existe arquivos/pastas no repositorio que não são conhecidos pelo git)
- Modified
  - Modificado (arquivos/pastas conhecidas pelo git que foram alterados)
- Unmodified
  - Não Modificado (arquivos/pastas conhecidas pelo git que não foram modificados)
- Staged
  - Local onde os arquivos/pastas estão preparados para serem agrupadas no git











[^1]: CLI - Command Line Interface ou Interface de linha de comando