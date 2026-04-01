# FROM almalinux:9
# RUN useradd expense
# USER expense
# CMD ["sleep", "100"]
FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]