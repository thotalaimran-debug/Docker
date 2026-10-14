FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
LABEL course="docker"
      trainer="imran"  
      author="imran"
EXPOSE 80/tcp
COPY index.html /usr/share/nginx/html/index.html

