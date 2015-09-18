# nginx 1.9 alpine
nginx 1.9 alpine
reverse proxy (SSL offload) 
size 25MB !!!


On CoreOS save nginx.service to /etc/systemd/system/ and 

To start a new unit, we need to tell systemd to create the symlink and then start the file:

$ sudo systemctl enable /etc/systemd/system/nginx.service
$ sudo systemctl start nginx.service


