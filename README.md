# profile
My linux profile

# Git aliases
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.l "log --oneline --graph"

# Docker aliases
##delete all stopped containers
docker rm $(docker ps -a -q)
