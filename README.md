# Docker git client

Usage:

alias git='docker run -it --rm -u 0:0 -v ~/.ssh:/root/.ssh -v $(pwd):/root/git naturlich/git-client'

git config --local user.name "Derek Su"
git config --local user.email "naturlich1986@gmail.com"
git config --local core.editor vim
