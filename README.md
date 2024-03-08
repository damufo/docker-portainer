# Installation

Fork form atareao <a.k.a. Lorenzo>
```
git clone https://github.com/damufo/docker-portainer.git
cd docker-portainer
cp sample.env .env
sed -i "s/portainer.domain.com/your_fqdn/g" .env
mkdir data
```

To run:

```
docker-compose -f docker-compose.yml -f docker-compose.traefik.yml up -d
docker-compose logs -f
```

Local port is 3000

