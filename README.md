# Palinha
Teste para vaga de desenvolvedor Full Stack

Este é um projeto laravel em conjunto com vue. Meu plano era montar uma estrutura com docker
para rodar ambos os projetos em conjunto. mas devido a falta de tempo achei melhor descartar essa ideia.

Para rodar cada projeto, peço que abram suas respectivas pastas e

Para o projeto do FrontEnd utilize:
* npm install vite@latest axios bootstrap-vue vue-router
* npm run dev

Para o projeto do BackEnd utilize:
* copie o arquivo .env.example para um arquivo .env
* crie um banco de dados mysql chamado laravel, e um usuário laravel com a senha password
* composer install
* php artisan migrate
* php artisan db:seed
* php artisan serve
