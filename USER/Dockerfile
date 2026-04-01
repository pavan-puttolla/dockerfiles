FROM almalinux:9
RUN dnf install nginx -y
#To create a user and switch to that user
RUN useradd  roboshop

USER roboshop
CMD ["sleep", "100"]
CMD ["nginx", "-g", "daemon off;"]
