# Docker git client

Usage:

alias git='docker run -it --rm -u 0:0 -v ~/.ssh:/root/.ssh -v $(pwd):/root/git naturlich/git-client'

git config --local user.name "Derek Su" <br>
git config --local user.email "naturlich1986@gmail.com" <br>
git config --local core.editor vim <br>
