# Person-Finder
missing person finder with react-native, machine learning and django server.


Steps to set-up:
clone the kodona server https://github.com/narayanansampath/person-finder-server.git
#1  install dependancies
pip3 install -r requirments.txt

 install postgres database 
   #2.1 create a database named kodona_db
   #2.2 create a user named kodona_user password as 'password'

#3 create the database tables
python3 manage.py migrate

#4 run the server
python3 manage.py runserver

#5 hit the server at
localhost:8000/
