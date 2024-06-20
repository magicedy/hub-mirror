# hub-mirror

> 国内 Docker Hub 无法正常访问
> 
> 利用 Github Action 将 Docker Hub 上的镜像推送到 Github 镜像仓库

### eg.

|docker.io|ghcr.io(Platforms: arm64,amd64)|
|:---:|:---:|
|traefik:v3.0.2|ghcr.io/droplet-js/traefik:v3.0.2|
|portainer/portainer-ce:2.16.2-alpine|ghcr.io/droplet-js/portainer/portainer-ce:2.16.2-alpine|
|gitea/gitea:1.17.3|ghcr.io/droplet-js/gitea/gitea:1.17.3|
|drone/drone:2.16.0|ghcr.io/droplet-js/drone/drone:2.16.0|
|filebrowser/filebrowser:v2.23.0|ghcr.io/droplet-js/filebrowser/filebrowser:v2.23.0|
|nginx:1.23.3-alpine|ghcr.io/droplet-js/nginx:1.23.3-alpine|

[docker-compose.yml](./docker-compose.yml)
