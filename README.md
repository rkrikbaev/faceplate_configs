# faceplate_configs
Optimal faceplate configs


# docker

Run container with faceplate enviroment:

`
sudo docker run -p 9022:9000 -p 8022:8000 --restart always -d --name fp-js_api_test4 -v /home/user/faceplate/faceplate_v3.2.2.0/DB:/opt/ext/faceplate/DB fpcloud/fp:v3.2.2
`
