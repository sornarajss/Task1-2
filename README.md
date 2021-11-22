sudo apt-get install
sudo apt install nginx -y
systemctl status nginx
sudo apt install python3 -y
systemctl status python
whereis python
sudo apt install python3-pip
whereis pip3
sudo apt install gunicorn3
sudo pip3 install flask
 mkdir flaskapplication
 ls
 cd flaskapplication
 python3 app.py
 cd /etc/nginx
 ls
 cd  sites-enabled
 sudo vi flaskapp
 sudo service nginx restart
 cd ~
 cd flaskapplication
 gusudo gunicorn3 app:app
 history
