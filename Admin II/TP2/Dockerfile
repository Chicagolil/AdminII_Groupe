FROM nginx:latest
RUN apt update && apt install -y nano iproute2 iputils-ping net-tools && rm -rf /var/lib/apt/lists/*
COPY index.html /usr/share/nginx/html