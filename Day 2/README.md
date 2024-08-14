### Run
```
docker run --name docker-nginx_overwrite_headers -p 1080:80 -v ./html:/usr/share/nginx/html -v ./nginx.conf:/etc/nginx/nginx.conf -d nginx
```
