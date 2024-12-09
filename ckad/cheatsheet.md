# ETCD
```bash
# TODO: Populate commands as you use them in labs here
etcdctl # include the flags for specifying api version and note the differences
```

# Systemd and Journalctl
```bash
systemctl status docker
systemctl list-units
systemctl cat docker

journalctl -u docker
journalctl -u docker -f
```

# Kubectl
> Create a pod yaml definition
```bash
kubectl run nginx --image=nginx --dry-run=client -o yaml > pod.yaml
```
> Create a deployment yaml definition
```bash
kubectl create deployment nginx --image=nginx       # start a single instance of nginx
```