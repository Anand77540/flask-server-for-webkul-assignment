# flask-server-for-webkul-assignment
for creating python virtual environment
    python -m venv venv_name

for installing dependencies if requirements.txt file exists 
   "pip install -r requirements.txt"


/----------------------------------The command you have to follow for easily setup and run this server----------------------------/
1. make and open folder (after that use cmd or vs code)

2. make virtual environment by typing following command
python -m venv venv_name

3. now, activate virtual environment by typing following command
.\venv\Scripts\activate

4. install all requirred packages
pip install flask
pip install Werkzeug
pip install os

5. run server by typing following command
python app.py



/--------------------------------now test all the requirements------------------------------------------------------/
1. default get request 
method : get
server url : http://127.0.0.1:5000/


2. sigup request
method : post
server url : http://127.0.0.1:5000/api/v1/signup
json : 
{
    "name":"Satish Tiwari",
    "email":"tiwarisatish989@gmail.com",
    "password":"admin123"
}


3. login request
method : post 
server url :  http://127.0.0.1:5000/api/v1/login
json:
{
    "email":"tiwarisatish989@gmail.com",
    "password":"admin123"
}


4. get all user details
method: get
server url :  http://127.0.0.1:5000/api/v1/users


// hosted server url
https://flask-server-for-webkul-assignment.onrender.com
