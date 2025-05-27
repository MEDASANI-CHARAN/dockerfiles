FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
# ADD https://raw.githubusercontent.com/MEDASANI-CHARAN/terraform-aws-vpc/refs/heads/main/vpc.tf /tmp/session-vpc.tf
# ADD sample-1 /tmp/
ADD https://raw.githubusercontent.com/MEDASANI-CHARAN/dockerfiles/refs/heads/main/COPY/Dockerfile /usr/share/nginx/html/Dockerfile
CMD ["nginx","-g","daemon off;"]
# CMD ["sleep", "100"]