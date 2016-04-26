# firestone
Firestone Initiative : Guacamole as a service

To deploy guac-server :
docker build --build-arg http_proxy="http://proxy.xxx.xxx:yyyy" --rm=true -t path&tag -f ./Dockerfile_guacd .
