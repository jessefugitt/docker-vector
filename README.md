# docker-vector

###Background
See http://techblog.netflix.com/2015/04/introducing-vector-netflixs-on-host.html for more information about Vector.
This docker image allows you to run the Netflix Vector web-based monitoring GUI inside docker using nginx.

###To run
```
docker run -d -p 8080:80 --name vector jessefugitt/vector
```
###To access the web-based monitoring GUI
```
http://docker-host-ip:8080
```
###To modify vector
```
git clone https://github.com/jessefugitt/docker-vector.git
edit Dockerfile
docker build -t jessefugitt/vector .
```
