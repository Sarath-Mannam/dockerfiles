FROM almalinux:8                  
# almalinux is exactly same as centos 
# RUN yum install epel-release -y
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# Removing default index.html file
RUN echo "Hello, Welcome to Dockerfile" > /usr/share/nginx/html/index.html
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]
# daemon off command makes our container running in the foreground for infinite time until we stop