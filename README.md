# example_webserver
simple example of web server that listens on port :8080

1) create directory /usr/bin/webapi

mkdir -p /usr/bin/webapi

2) compile webapi.go file 

go build webapi.go

3) copy binary file webapi to application directory /usr/bin/webapi

cp ./webapi /usr/bin/webapi/

4) create systemd service configuration file webapi.service in directory /etc/systemd/system/

5) start your brand new web-service

systemctl start webapi.service

6)  check out how the service works

http://[Server's IP addr]:8080/
