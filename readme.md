## USANDO GIT BASH

- git init
- git clone _No local da pasta_
- cd _Sua pasta_
- Main (Principal)
- git status

-Untracked (U)
 - Está na pasta versionada mas o git ainda não o conhece.

-Index Added (A)
 - Arquivo reconhecido pelo git

-Modified (M)
 - Modificado
### GIT ADD
- git add "Nome1" "Nome2" _Com aspas_
- git add . _Adiciona todos arquivos da pasta_
- git add * _Adiciona tudo menos itens em subpastas_

### Atalhos
- clear _Limpa o terminal_

### GITIGNORE E OUTROS

- Node modules é para ser ignorado

- git rm --cached _rm=remover_
 - (use "git rm --cached <file>..." to unstage)
  - unstage : retirar do estágio de controle

  - rm --cached -r _Recursively_
-git commit -m"Comentário"
 - Confirmar as alterações no pc local
 - O trabalho está pronto _Localmente_
 -git push
 -git push origin main _Vão ser empurrados pro servidor, subir para o github_

 -incremental 
  - Toda vez que eu faço um add, o trabalho é adicionado na linha do tempo por seu artefato


**Tech4me 2022**