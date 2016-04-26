# firestone
Firestone Initiative : Guacamole as a service

To deploy guac-server :
docker build --build-arg http_proxy="http://proxy.xxx.xxx:yyyy" --rm=true -t path&tag -f ./Dockerfile_guacd .

To run guac-server :
docker run -d -p 4822:4822 path&tag
