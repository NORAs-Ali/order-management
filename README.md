To create image in docker :
1.docker images
2.docker run -p 3306:3306 --name mysql-container -e MYSQL_ROOT_PASSWORD=  -e MYSQL_DATABASE=userdb -e MYSQL_PASSWOED=  -d mysql
3. docker build -t connect-to-mysql .
4. docker run -p 7002:7002 connect-to-mysql
