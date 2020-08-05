# Chainpoint Drand

## Required
- Go 1.14 +
- Docker 
- Docker-compose
- DNS name

## Steps
1. go get -u github.com/drand/drand
2. drand generate-keypair <address>
3. mkdir -p ~/data && chmod 777 ~/data
4. mv ~/.drand/key data
5. touch ~/data/acme.json && chmod 600 ~/data/acme.json
6. docker-compose up -d




