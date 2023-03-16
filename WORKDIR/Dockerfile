FROM almalinux
#RUN cd /tmp  ---> this is not correct way to give default directory
RUN adduser nginx
USER nginx
WORKDIR /tmp
RUN touch hello.txt