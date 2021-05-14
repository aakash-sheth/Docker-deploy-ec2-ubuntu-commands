# Deploy-Docker-Container-on-AWS


## Commands on Ubuntu Server  

```bash
sudo apt-get update
```

```bash
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
```

```bash
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

```bash
curl -fsSL https://get.docker.com -o get-docker.sh
```

````bash
sudo sh get-docker.sh
````

```bash
apt-cache madison docker-ce
```


```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io
```


```bash
sudo apt install docker.io
```


```bash
sudo apt install docker-compose
```

