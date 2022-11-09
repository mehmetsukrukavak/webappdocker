# webappdocker
Image Create
docker build --no-cache -t aspcoremvc:v1 . 

Volume Create
docker volume create images 

Container Create
docker run -d  -p 58104:4500 --name con67 --env MySqlCon='Uzak Sunucu VT' -v images:/app/wwwroot/images 212

Service Create
docker swarm init
<img width="621" alt="image" src="https://user-images.githubusercontent.com/18085037/200789502-291b9894-6201-417e-83bd-2ac2f000686a.png">
docker tag 2a6 msukrukavak/webappdocker:v5  
docker image push msukrukavak/webappdocker:aspcoremvc:v5 
