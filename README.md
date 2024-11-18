# install docker
- https://docs.docker.com/engine/install/ubuntu/

# install harbor
`wget https://github.com/goharbor/harbor/releases/download/v2.9.0/harbor-online-installer-v2.9.0.tgz`

`tar -xzvf harbor-online-installer-v2.9.0.tgz`

`cd harbor`

### change public ip or domain in the harbor.yml.tmpl

`cp harbor.yml.tmpl harbor.yml`

`sudo ./install.sh`

`http://<public-ip>:80`

default username and password 
username - admin
password - Harbor12345
