# SimpleAspNetCoreApi
Uma API simples em dotnet core para testes diversos

## Para executar
heroku create simple-aspnetcore-api --buildpack https://github.com/heroku-softtrends/heroku-buildpack-dotnetcore.git
heroku git:remote -a simple-aspnetcore-api
heroku buildpacks:set https://github.com/jincod/dotnetcore-buildpack.git
git push heroku main

## Para visualizar o buildpack usado
no diretório do repositório -> heroku buildpacks

heroku create station-agent-api --buildpack https://github.com/jincod/dotnetcore-buildpack.git
heroku git:remote -a station-agent-api
git push heroku main