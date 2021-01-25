

## List of commands:

 ###  Local:

- git init
- git add .
- git remote add production https//githubcom/XXX/XXXX.git
- git remote -v
- git commit -m "first commit"
- git push production master

###  Production:

- git init
- git remote add production https://github.com/Horizen23/laravel-maleeta.git
- git pull production master
- composer install --optimize-autoloader --no-dev
- mv .env.example .env
- vim .env
- php artisan key:generate
- php artisan migrate
- php artisan config:cache
- php artisan route:cache
- php artisan view:cache
- php artisan storage:link
- cd ..
- ln -s larasocketdemo/public chatapp

###  commands in two line in CMD:
  ######1
     set _line=DB_CONNECTION=mysql DB_HOST=127.0.0.1 DB_PORT=3306 DB_DATABASE=login_api DB_USERNAME=root DB_PASSWORD=   MEMCACHED_HOST=127.0.0.1 REDIS_HOST=127.0.0.1   private_key_maleeta="maleetatoei"
  ######2
    git init &git remote add production https://github.com/Horizen23/laravel-maleeta.git&git pull production master& composer install --optimize-autoloader --no-dev & move .env.example .env &echo %_line: = >>.env &echo;%>>.env& php artisan key:generate & php artisan migrate & php artisan config:cache & php artisan route:cache & php artisan view:cache & php artisan storage:link & start "google" "c:\program files (x86)\Google\Chrome\Application\chrome.exe" "http://127.0.0.1:8000/" & php artisan serv 




###  commands in one line in CMD:
    git init &&git remote add production https://github.com/Horizen23/laravel-maleeta.git&git pull production master&& composer install --optimize-autoloader --no-dev && move .env.example .env &&echo DB_CONNECTION=mysql  >>.env &&echo DB_HOST=127.0.0.1  >>.env &&echo DB_PORT=3306  >>.env &&echo DB_DATABASE=login_api >>.env &&echo DB_USERNAME=root >>.env &&echo DB_PASSWORD= >>.env &echo private_key_maleeta = "maleetatoei" >>.env &&php artisan key:generate & php artisan migrate & php artisan config:cache & php artisan route:cache & php artisan view:cache & php artisan storage:link & start "google" "c:\program files (x86)\Google\Chrome\Application\chrome.exe" "http://127.0.0.1:8000/" & php artisan serv 
  
  
  
  
  
  
  
  
  
