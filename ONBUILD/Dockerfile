FROM almalinux:8                  
# almalinux is exactly same as centos 
RUN yum install nginx -y
# When we install the nginx we use to remove the default index.html page of nginx
RUN rmI -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]
# daemon off command makes our container running in the foreground for infinite time until we stop