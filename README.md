EVERYTHING ABOUT Local Server.
====

Steps
---
1: Install MAMP server
2: Go to Php my admin page , create a new database name should be in small letter.
3: go to priviliage part , set new password as "root" save this.
4: Drag and drop the php file folder in Htdocs folder. 
5: you can take refrence from : https://www.positronx.io/create-simple-php-crud-rest-api-with-mysql-php-pdo/

---

PHP files
---
Please drop DBCode folder in Htdocs folder of MAMP & open config folder & edit database.php with new
db name & password 

---

Access on Other System
---
Start your MAMP server , open you mac setting , click on network where you get your ip address
you can use this to access on other system if all are connected to same network.

ex: Wi-Fi is connected to Kunal’s iPhone and has the IP address 172.20.10.2
use :  172.20.10.2:8888

PDO("mysql:host=localhost;port=8889;dbname=phpapidb", "root", "root");

port=8889 : it is your SQL Port number.


---



