FROM almalinux:9
RUN mkdir /add
RUN adduser expense
 USER expense
#setup the pwd
WORKDIR /add
RUN pwd
CMD [ "sleep", "100" ]