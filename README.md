# DigiCare
Environment Setup and and install - (on vs code terminal)

pip install py
pip install virtualenv
virtualenv env
.\env\Scripts\activate.ps1  
pip install py
pip install flask   
pip install db       
pip install pymysql  
pip install flask_sqlalchemy  
pip install flask_migrate
pip install flask_login
pip install werkzeug==2.3.0
pip install pytz 

*Create username and password in phpAdmin according to app file

For DB migration -

flask --app digicare.py db init
flask --app digicare.py db migrate
flask --app digicare.py db upgrade

* This should create tables in your DB
