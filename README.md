```
source env/bin/activate
pip install -r requirements.txt
mv .env-sample .env
fill .env
cd LoginGmail
./manage.py createsuperuser
./manage.py runserver
```
