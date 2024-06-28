FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
RUN rm -rf /user/share/nginx/html/index.html
COPY C:\terraform-course\Dockerfiles\projectcopy\opportunity /usr/share/nginx/html/
CMD [ "nginx" , "-g" , "daemon off;" ]