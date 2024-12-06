docker build -t python-app .
docker ps
docker run python-app
docker ps
docker run -d --name python-container python-app
docker ps
docker attach python-container
docker run -d --name python-container python-app
docker rm 7e75fb69927b1bc8b25529afa658fcc649bcc1f7991e49e32cdb9b7412cd3a04 #IN CASE OF ERRORS
clear
git init
clear
docker build -t python-app .
docker images | grep python
docker run -d --name python-container python-app
docker ps
docker exec -it dca84c24f4e9 bash