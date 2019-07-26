myproject = django_jwt
myprojectdir = mots_jwt_token
myprojectenv = myprojectenv
sudo python3 manage.py runserver 0.0.0.0:80









--------------------------create deploy server--------------------------
1.click navigation menu
2.click compute engine
3.click vm instances
4.click create instance
5.edit name
6.edit book disk click change
7.change to ubuntu 18.04 LTS click select
8.click allow http traffic
9.click allow https traffic
10.click create and wait for minute
11.click ssh to run cmd google
--------------------------create deploy server--------------------------


-------------------deploy server ubuntu django---------------------------
0.click ssh to run cmd google
1.sudo apt-get update
2.git clone https://github.com/MickeyProject/google-cloud-platform-django.git
3.sudo apt-get install python3-pip
4.y
5.ls <- find file where
6.cd <- file
6.sudo pip3 install -r requirements.txt
7.ls
8.go to django_jwt
9.nano settings.py
10.add in ALLOWED_HOST = ["35.239.61.173"] <-external ip
11.ctrl+x
12.y
13.enter
14.sudo python3 manage.py runserver 0.0.0.0:80
15.screen
16.Kill all node
17.sudo python3 manage.py runserver 0.0.0.0:80
18.ctrl+a
19.alt+a
20.altd
21.search 35.239.61.173

if edit a file
22.edit file
23.git pull origin master and go to point 1.
-------------------deploy server ubuntu django---------------------------