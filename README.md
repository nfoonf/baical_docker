# baical_docker

basic baical setup with SSL-Offloading via haproxy and valid on the fly generated ssl-certs:

1. edit docker compose file according to your mail address and domain
2. excute 'docker-compose -f docker-compose.yml up --build' 
3. connect to $YOUR_DOMAIN:8080/admin and configure
