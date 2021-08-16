# aws_lightsail_rails
Projeto rails para testar deploy automático no aws lightsail

## Passos de deploy no lightsail
 - Instale rvm
 - Instale ruby
 - Instale rails
 - Instale nodejs
 - Instale yarn
 - Caso use Postgres, instale a gem `pg`
 - Instale a gem passenger
 - Para rodar a aplicação, execute `rvmsudo passenger start`
 - Utilize o comando `CREATE ROLE usuario WITH SUPERUSER CREATEDB CREATEROLE LOGIN ENCRYPTED PASSWORD 'senha';` para criar o usuário do database
