# Example of FastCGI server written in Go

Run Nginx container:

```shell
docker run --name custom-nginx --network host -v /home/denis/Desktop/go_fastcgi/nginx.conf:/etc/nginx/nginx.conf:ro -d nginx
```
