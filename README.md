docker build -t nomHyperCool .
docker run -d -p 90:80 nomHyperCool
docker exec -it shaDocker sh