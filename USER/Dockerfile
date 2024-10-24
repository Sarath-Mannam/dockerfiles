FROM almalinux:8
# First create the user
RUN useradd sarath
USER sarath
# From here onwards everything will run on sarath user and not on root access
RUN echo "Hello Docker" > /tmp/hello.txt
# now let's see with which user this file will be created inside the image