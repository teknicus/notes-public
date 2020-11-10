Install K3d - `curl -s https://raw.githubusercontent.com/rancher/k3d/main/install.sh | bash`

```
k3d cluster create hudson
    --api-port 6443
    --servers 1
    --agents 1
    -p 30000-32767:30000-32767@server[0]


```

k3d cluster create portainer --api-port 6443 --servers 1 --agents 1 -p 30000-32767:30000-32767@server[0]