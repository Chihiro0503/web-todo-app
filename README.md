web-todo-app

This app allows you to record and save what you do. In addition, a record is stored for each email address.

**important information**
Commercial use,Modification,Distribution,Patent use are not allowed.

# Requirement
PHP 8.1.2 or higher
Laravel
Docker Desktop

#How to start

Set permissions.
docker compose run --rm app chmod 707 -R storage

Up the docker container to touchdown the website.
docker compose up

then your site is now running at http://localhost:8000


# Check the DB Connections
go to http://localhost:8888/ .
Type in the form as follows:
- Email Address / Username：user@example.com
- Password：passw@rd
and then you can check the Database.
 
# License
Copyright Chihiro Takahashi

This repository was created based on the TechSelect Curriculum,operated by Local-innovation.Co. Ltd.
Commercial use,Modification,Distribution,Patent use are not allowed.
This repository is provided without WARRANTY and Liability.
