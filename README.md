<img width="1269" alt="Screen Shot 2021-11-26 at 9 04 28 AM" src="https://user-images.githubusercontent.com/25509797/143540525-851c5955-3e40-438b-87b4-2bd896cbd659.png">
# Assignment-Webshop

Use command => git clone git@github.com:Samyaryal/Assignment-Webshop.git 

Cd Webshop  

In terminal create a Virtual env => python3 -m venv myvenv 

Activate virtual env => source myvenv/bin/activate 

pip3 install -r requirements.txt 

create a mysql db and add credentials to settings.py 
pip3 install mysqlclient (if not installed mysqlclient) 

python3 manage.py makemigrations followed by python3 manage.py migrate and python3 manage.py runserver to run the server

App runs on port http://127.0.0.1:8000/api/products. 

 

Now for Frontend 

In new Terminal 

Cd client 

npm install 

Npm start 

Page can be vieweed in port http://localhost:3000/ 
 
