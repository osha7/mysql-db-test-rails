# BUILD AN APP WITH MYSQL:

rails new demo-app -d=mysql
cd demo-app
code .

webpack/database.yml file:  and  Gemfile
check for:  'mysql2'

terminal commands:
rake db:create

for this example: command:
rails g model employee name:string email:string
rake db:migrate

