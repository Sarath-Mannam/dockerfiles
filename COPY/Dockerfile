FROM nginx
# Here first i will remove default index.html 
RUN rm -rf /usr/share/nginx/html/index.html
# Files should be available in the current directory where Dockerfile exists
#COPY index.html /usr/share/nginx/html/index.html
COPY qi/ /usr/share/nginx/html/