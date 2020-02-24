# Cards_sys


docker network create --driver bridge --subnet 172.18.0.0/16 --gateway 172.18.0.1 docker-network

docker run --name prometheus -d -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus --config.file="/etc/prometheus/prometheus.yml" 


