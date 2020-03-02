# Docker Environment Aliases
Very handy aliases for common docker commands
Drop the following into your /home/<username>/.bashrc file
  
alias dps="sudo docker ps"
alias dcd="sudo docker-compose down"
alias dcu="sudo docker-compose up -d"
alias dcr="sudo docker-compose restart"
alias di="sudo docker inspect -f '{{ .Mounts }}'"
alias dl="sudo docker logs"

function de { sudo docker exec -it "$1" /bin/bash; }
