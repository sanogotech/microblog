# Welcome to Microblog!

This is an example application featured in my [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world). See the tutorial for instructions on how to work with it.

0*. https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xvii-deployment-on-linux
- https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xxii-background-jobs  (Redis Queue)
- https://github.com/MicrosoftArchive/redis/releases  (redis server)

*1  Clone

$ git clone https://github.com/miguelgrinberg/microblog
$ cd microblog
$ git checkout v0.17

*2  Install requirements

$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ pip install -r requirements.txt

3*  For production only
In addition to the common requirements in requirements.txt, I'm going to use two packages that are specific to this production deployment, so they are not included in the requirements file. The gunicorn package is a production web server for Python applications. The pymysql package contains the MySQL driver that enables SQLAlchemy to work with MySQL databases:

(venv) $ pip install gunicorn pymysql

*4.  Run
- flak db init or flask db upgrade
- flask run

*5.  localhost:5000



