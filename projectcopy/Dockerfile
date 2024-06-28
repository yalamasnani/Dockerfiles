FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
COPY C:\terraform-course\Dockerfiles\projectcopy\opportunity /usr/share/nginx/html/
CMD ["nginx," "-g" "daemon off;"]