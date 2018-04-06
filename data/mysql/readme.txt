docker run --name=mysql1 \
--mount type=bind,src=/Sites/gsuite/mysqlServer/my.cnf,dst=/etc/my.cnf \
--mount type=bind,src=/Sites/gsuite/mysqlServer/data,dst=/var/lib/mysql \
-d mysql/mysql-server

docker logs [containerID]
GENERATED ROOT PASSWORD: ^3jIpP0SetozIwOwOB(oJTulvyx

docker exec -it [containerID] mysql -uroot -p

ALTER USER 'root'@'localhost' IDENTIFIED BY '[newpassword]';