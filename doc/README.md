```shell
sudo docker volume create redis-data

sudo docker-compose up -d
sudo docker-compose down

sudo docker pull diygod/rsshub

sudo docker pull diygod/rsshub:2021-06-18
sudo docker diygod/rsshub:chromium-bundled
sudo docker pull diygod/rsshub:chromium-bundled-2021-06-18
sudo docker run -d --name rsshub -p 1200:1200 diygod/rsshub
sudo docker stop rsshub
```