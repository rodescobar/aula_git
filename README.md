## Criar o repositorio local
git init

##Linkar repositorio local com o github
git remote add origin https://github.com/rodescobar/aula_git.git

##Verificar alterações LOCAIS
git status

##Pegar arquivos alterados/novos e preparar para envio
git add .

##Fechar pacote para subir pro git
git commit -m "Primeiro UP"

##Despachar (PRIMEIRA VEZ)
git push --set-upstream origin master


##Configuracao de email e nome
git config --global user.email "rodescobar@gmail.com"
git config --global user.name "Rodrigo Escobar"