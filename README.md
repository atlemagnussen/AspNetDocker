# aspnet docker

testing

## docker build
```sh
 docker build -t web-app-docker .

 docker run -p 4000:80 web-app-docker
 # or with more options
 docker run -d --rm -p 5000:80 -p 5001:443 -e ASPNETCORE_HTTPS_PORT=https://+:5001 -e ASPNETCORE_URLS=http://+:5000  web-app-docker
```