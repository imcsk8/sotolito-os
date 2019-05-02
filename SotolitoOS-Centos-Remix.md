# SotolitoOS CentOS Based Appliance

## Install Required Software

```
# yum install -y cockpit podman
```

## Configure SotolitoLabs Registry

```
# sed -i "s/registries = \[/registries = \[\'hub.sotolitolabs.com\', / " /etc/containers/registries.conf
```
