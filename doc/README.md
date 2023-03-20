```shell
sudo docker volume create redis-data

sudo docker-compose up -d
sudo docker-compose down

docker-compose ps

http://82.157.54.206:8081/
http://82.157.54.206:8081/twitter/user/DIYgod
http://82.157.54.206:8081/bilibili/bangumi/media/9192
http://82.157.54.206:8081/baai/hub

https://rss.injahow.cn/bilibili/bangumi/media/9192
https://rss.injahow.cn/baai/hub
https://rss.itggg.cn/baai/hub

https://rsshub.rssforever.com
https://rss.qiuyuair.com
https://rss.injahow.cn
https://rss.feiyuyu.net
https://rss.shab.fun
https://rss.itggg.cn
https://rsshub.uneasy.win
https://rss.injahow.cn
https://rsshub.anyant.xyz

sudo docker pull diygod/rsshub

sudo docker pull diygod/rsshub:2021-06-18
sudo docker diygod/rsshub:chromium-bundled
sudo docker pull diygod/rsshub:chromium-bundled-2021-06-18
sudo docker run -d --name rsshub -p 1200:1200 diygod/rsshub
sudo docker stop rsshub

sudo docker run -d --name rsshub -p 1200:1200 -e CACHE_EXPIRE=3600 -e GITHUB_ACCESS_TOKEN=example diygod/rsshub
```