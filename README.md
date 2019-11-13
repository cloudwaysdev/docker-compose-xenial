`docker-compose up -d`

OR

`docker-compose up`

``
```
docker network create --gateway 172.18.0.1 --subnet 172.18.0.0/16 --driver bridge ansible_nw

docker network inspect ansible_nw

docker network ls
```
``

`ln -s ~/.ssh/id_rsa.pub ssh_data/authorized_keys`

mkdir ssh_data && cp -f ~/.ssh/id_rsa.pub ssh_data/authorized_keys

rm ssh_data/authorized_keys