# Facial-Recognition-Capstone
<h2>This project compose of 2 systems:</h2>

<h3>1. A facial-recognition Surveillance  System. </h3>
This is a face recognition system, with the function of automatically creating database
tables and saving face features into the database. The face_recognition model utilized in this
project has an accuracy rate of 99.38%. The python opencv model is able to capture 30
frames every second. This facial recognition processing speed reaches 6 frames every
second.
<h3> 2. A 2 Way Authentication System.</h3>
For the 2 way authentication system, the input is properly sanitized and tested SQL
injection proof. Passwords are properly hashed by sha512.
<hr>
<h3>Environment Setup:</h3>
<h4>
Mysql database install and setup:</h4>

<p>sudo apt-get install mysql-server -y</p>
<p>sudo service mysql start</p>
<p>sudo mysql -u root -p</p>
<p>mysql> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'mplftw20';</p>
<p>create database iss;</p>
<p>use  iss;</p>
<br>
<h4>
install python3 modules:</h4>
<br>
<p>sudo apt-get -y install python3-pip python3-dev -y</p>
<p>sudo apt-get -y install cmake</p>
<p>sudo apt-get -y install python3-tk</p>
<p>sudo apt-get install python3-pil python3-pil.imagetk</p>
<p>
<p>pip3 install --upgrade pip</p>
<p>pip3 install opencv-contrib-python</p>
<p>pip3 install face_recognition</p>
<p>pip3 install mysql.connector</p>
<p>pip3 install playsound</p>
