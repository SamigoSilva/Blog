# Para deploy no Heroku

## Fazer login
heroku login -i

## cria app
heroku create <nome do app>

## cria Banco
heroku addons:create heroku-postgresql:hobby-dev --app <nome do app>

## ve config do app
heroku config --app <nome do app>

## para atualizar
git push heroku main
