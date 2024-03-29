# Git Aliases
    alias ga='git add'
    alias gaa='git add .'
    alias gaaa='git add --all'
    alias gau='git add --update'
    alias gb='git branch'
    alias gbd='git branch --delete '
    alias gc='git commit'
    alias gcm='git commit --message'
    alias gcf='git commit --fixup'
    alias gco='git checkout'
    alias gcob='git checkout -b'
    alias gcom='git checkout master'
    alias gcos='git checkout staging'
    alias gcod='git checkout develop'
    alias gd='git diff'
    alias gda='git diff HEAD'
    alias gi='git init'
    alias glg='git log --graph --oneline --decorate --all'
    alias gld='git log --pretty=format:"%h %ad %s" --date=short --all'
    alias gm='git merge --no-ff'
    alias gma='git merge --abort'
    alias gmc='git merge --continue'
    alias gpl='git pull'
    alias gplo='git pull origin'
    alias gplr='git pull --rebase'
    alias gps='git push'
    alias gpso='git push origin'
    alias gr='git rebase'
    alias gs='git status'
    alias gss='git status --short'
    alias gst='git stash'
    alias gsta='git stash apply'
    alias gstd='git stash drop'
    alias gstl='git stash list'
    alias gstp='git stash pop'
    alias gsts='git stash save'

    function push() {
        git add .
        git commit -a -m "$1"
        git push
    }
 
# Artisan Aliases
    alias art='php artisan'
    
# Terminal Aliases
    alias c='clear'
    
# Docker Aliases
    alias d-c='docker-compose'
    alias de='winpty docker exec'
    alias d='winpty docker'
