FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello, Welcom to Dockerfile. a Way of creating own images" > /usr/share/nginx/hello.html
# deamon off command makes our container running and attached to screen.
CMD ["nginx", "-g", "daemon off"]