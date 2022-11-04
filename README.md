# network-performance-tester-server


GitHub repo: https://github.com/jrcamenzuli/network-performance-tester-server
Docker repo: https://hub.docker.com/repository/docker/jrcamenzuli/network-performance-tester-server

The easiest way to start using this server is to use Docker:
1.  pull the latest image
```
docker pull jrcamenzuli/network-performance-tester-server
```
2. run a container
```
docker run --rm -p9001:9001/udp -p9000:9000/udp -p53:53/udp -p53:53/tcp -p80:80/tcp -p443:443/tcp --name network-performance-tester-server -d jrcamenzuli/network-performance-tester-server
```

# network-performance-tester-client

This server complements https://github.com/jrcamenzuli/network-performance-tester-client

