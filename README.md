### Comandos

`docker build -t heroku-docker-dotnet -f Dockerfile .`

`docker run -d -p 5025:80 --name heroku-dotnet heroku-docker-dotnet`