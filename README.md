### Comandos

`docker build -t heroku-docker-dotnet -f Dockerfile .`

`docker run -d -p 5025:80 --name heroku-dotnet heroku-docker-dotnet`

Reference: [How to Deploy a Dockerized Web App to Heroku using the GitHub Actions by Yohan Malshika (Medium)](https://enlear.academy/how-to-deploy-a-dockerized-web-app-to-heroku-using-the-github-actions-f16c00b19621)