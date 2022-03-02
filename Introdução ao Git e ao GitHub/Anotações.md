# :notebook: Anotaces - Introducao ao Git e GitHub

##### Beneficios das tecnologias:

:one: - Controle de versao

:two: - Armazenamento em nuvem

:three: - Trabalho em equipe

:four: - Melhoria do codigo

:five: - Reconhecimento



## Introducao ao Git

> Link de download do Git: https://git-scm.com/downloads
>
> Git Bash - terminal extendido para otimizar o uso do Git.

##### Formas de interacao (comandos)

- dir - lista pastas do diretorio onde esta situado (Windows)

- ls -  lista pastas do diretorio onde esta situado (Linux)

- cd - mostra base do diretorio (Windows/Linux)

- cd .. - retrocede um nivel na navegacao (Windows)

- cls/clear - limpa tela (Windows) 

- clear - limpa tela (Linux)

- mkdir - criar diretorio/pasta (Windows)

- echo hello > nome.txt - cria arquivo de texto (Windows) 

- del nomedapasta - deleta pasta ou arquivos (Windows)

- dir + seta pra cima - encontra os diretorios (Windows)

- rmdir nomedapasta /S /Q - remover repositorios (Windows)

- rm - rf nomedapasta - deletar diretorios (Linux) 

- TAB - completar (Windows/Linux)

##### Funcionamento do Git

- SHA1 (Secure Hash Algoritgm) - conjunto de funcoes hash criptograficas projetadas pela Agencia de Seguranca Nacional dos EUA. A encriptacao gera um conjunto de caracteres identificadores de 40 digitos.
- Objetos fundamentais
  - Bloobs - primeiro item da estrutura
  - Trees - agrupamento de bloobs
  - Commits - agrupamento de trees
- Sistema distribuido
  - Quando qualquer alteracao e realizada em qualquer arquivo, uma nova chave e gerada, no intuito de "amarrar" todos os arquivos e pastas e garantir a seguranca.
- Seguranca
  - Chave SSH - chave de seguranca definida ao conectar repositorio local ao repositorio no servidor
  - Tokens - e possivel disponibilizar token para acessar a plataforma pelo navegador (so aparece uma unica vez)
- Alguns comandos com o Git
  - git init - inicia o Git
  - git add - adiciona versionamento
  - git commit -  cria um commit
  - git push - empurra commit para servidor do GitHub
  - git add . - adiciona todas as alteraçoes para realizar o commit
  - git status - verifica status das alteraçoes
  - git commit -m "mensagem" - coloca uma mensagem na nova versão, para identificá-la (muito importante)
  - git push origin main - envia todas atualizações commit para nuvem
- Ciclo de vida dos arquivos
  - Untracked - nao temos ciencia
  - Tracked - temos ciencia
  - Staged - arquivo que est?o se preparando pra fazer parte de outro levantamento
- Resolvendo conflitos
  - Quando um repositorio e "clonado", a data do repositorio do usuario que clonou e mais recente, entao se voce realizar um commit depois disso, e sua data for alterada para a data do commit, sera considerado como primeiro o repositorio da outra pessoa, devido a data. Isso e um "conflito". Para resolver, voce deve fazer isso manualmente no seu repositorio ou em contato com o usuario que clonou.

