## Start Vagrant

```bash
vagrant up
vagrant ssh
sudo -i // Change to root admin
```

## Add Dockerfile

```bash
vim Dockerfile
:wq
```

## Build custom image

```bash
docker build -t tween-image .
```

## Run container from image

```bash
docker run -d -P tween-image
```

## Allow host access to machine

- Enable `private_network` on `Vagrantfile`

## Get current ip address

```bash
ip addr show
```
