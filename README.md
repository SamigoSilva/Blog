# Para deploy no Heroku

## Fazer login
heroku login -i

## cria app
heroku create nome_do_app

## cria Banco
heroku addons:create heroku-postgresql:hobby-dev --app nome_do_app

## ve config do app
heroku config --app nome_do_app

## para atualizar
git push heroku main
