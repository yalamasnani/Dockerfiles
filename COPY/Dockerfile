FROM almalinux:8
RUN yum update -y
RUN yum install nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY C:\terraform-course\Dockerfiles\COPY /usr/share/nginx/html/
CMD [" nginx", "-g" ,"daemon off;"] 