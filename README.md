### islide相关模板 
```javascript
4
wget https://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm
5
rpm -Uvh mysql57-community-release-el7-11.noarch.rpm
6
yum repolist enabled | grep mysql
7
yum install java-1.8.0-openjdk* mysql-community-server -y
8
systemctl start mysqld && systemctl enable mysqld
9
mysql -uroot -p
10
​```
