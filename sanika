FROM ubuntu:20.04

LABEL devops_engg="dipak"

RUN apt update && apt install -y nginx

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80
