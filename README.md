

## หนุกกันนิ



List of commands:

 Local:

-git init
-git add .
-git remote add production https//githubcom/XXX/XXXX.git
-git remote -v
-git commit -m "first commit"
-git push production master

Production:

-git init
-git remote add production https//githubcom/XXX/XXXX.git
-git pull production master
-composer install --optimize-autoloader --no-dev
-mv .env.example .env
-vim .env
-php artisan key:generate
-php artisan migrate
-php artisan config:cache
-php artisan route:cache
-php artisan view:cache
-php artisan storage:link
-cd ..
-ln -s larasocketdemo/public chatapp
