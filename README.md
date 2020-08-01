# Arquivo para listar alguns comandos de configuração do git.

-git init
-git config --global code.editor=code 
-git config --global --edit
    [alias]
        c = !git add --all && git commit -m 
        s = !git status -s
        l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
        amend = !git add --all && git commit --amend --no-edit
        count = !git shortlog -s --grep


# Projeto utilizando o conventional commits
    https://www.conventionalcommits.org/pt-br/