# Assignment-Webshop

Use command => git clone git@github.com:Samyaryal/Assignment-Webshop.git 

Cd Webshop  

In terminal create a Virtual env => python3 -m venv myvenv 

Activate virtual env => source myvenv/bin/activate 

pip3 install -r requirements.txt 

create a mysql db and add credentials to settings.py OR use the same in settings.py DATABASES =  { 'default': { 'ENGINE': 'django.db.backends.mysql', 'NAME': 'shop', HOST: 'localhost', 'USER': 'root', 'PASSWORD': 'rootuser', 'PORT': '3306' } } 

pip3 install mysqlclient (if not installed mysqlclient) 

python3 manage.py makemigrations  then python3 manage.py migrate then python3 manage.py runserver 

open http://127.0.0.1:8000/api/products  on your browser to view the server app. 

 

Now for Frontend 

In new Terminal 

Cd client 

npm install 

Npm start 

Browser can be viewed in http://localhost:3000/ 
 
