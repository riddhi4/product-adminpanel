# product with adminpanel
laravel project
1. composer install

2. npm install

3. npm run dev

4. npm run watch

5. composer require laravel/passport (using only api) and php artisan passport:install 

6. php artisan key:generate

7. php artisan migrate --seed / php artisan db:seed

8. php artisan storage:link  (using only file upload public-path)

9.  php artisan serve

Note :: database for check test1.sql 

		==================== LOGIN =======================
					USER:: email->     user@user.com
						   password -> password
					Admin:: email->    admin@admin.com
						   password -> password
					EndUser::email-> rp1@gmail.com
							 password -> 123456789


Sample path ::
http://127.0.0.1:8000/user/login  -> end user 

http://127.0.0.1:8000/user/register -> end user

http://127.0.0.1:8000/user -> end user

http://127.0.0.1:8000/user/productshow -> end user product show

http://127.0.0.1:8000/user/productshow/1 -> end user product details show

http://127.0.0.1:8000/login -> admin

http://127.0.0.1:8000/register -> admin

http://127.0.0.1:8000/admin -> admin

