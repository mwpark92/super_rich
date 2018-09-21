python 3.5 or later
Django 2.1.1
Postgresql 10 


설치 command
pip install Django==2.1.1
pip install psycopg2 


실행 command
테스트 shell 실행: python manage.py shell
개발서버 실행: python manage.py runserver 8080 (호스트 네임이 한글이여야 함)
마이그레이션 diff 생성: python manage.py makemigrations analysis
마이그레이션 diff 실행: python manage.py migrate

tutorial
https://docs.djangoproject.com/ko/2.1/intro/tutorial01/

