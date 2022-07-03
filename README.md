# smarthome-control-node-red

Start a Node-Red instance.

## Usage

Start the container with

```shell
docker compose up -d --build nginx
```

## Live usage

If you want to use node-red on a live server, use the file `docker-compose.traefik.live.deploy.yml`

You must have a traefik proxy running for this.

### Usage

Adjust the env-file:

- VIRTUAL_HOST
  - Set the Domainname of your node-red instance
- TRAEFIK_HOSTS_RULE
  - Domainname for traefik