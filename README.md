## Getting started

1. git clone https://github.com/ChristopherLonk/env.git [your-project-folder]
2. cd [your-project-folder]
3. vagrant up --provision
4. ... please wait ...
5. mkdir web
6. git clone https://github.com/ChristopherLonk/laravel.git web
7. vagrant ssh -c "bash /vagrant/web/product/bin/deploy/local.sh"
8. go to http://lemp.test
9. login with
   - user: agent@agent.com 
   - password: agentagent

## Default access
- Default project: http://lemp.test
- Database: 192.168.56.111:3306
  - user: admin
  - password: 5dsa4d65a4s54grfzh41fgz5kij4ghj15gh684hf5d4b6f54685drf454650
