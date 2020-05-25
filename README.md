# Server
How to configure the server and useful scripts.

## 1. Install Ubuntu

With "terrahost" this is easy. Should not take long.

## 2. Installing basic programs

## 2.1 NeoVIM

```bash
apt update
apt install neovim 
```

### 2.2 Setting up GitHub SSH keys



## 3. Configure SSH 

### 3.1 Create a user

The first step to setting up SSH is making it safe, so that you don't loose access to your server. To do this the first step is setting up a user that is not root. 

### 3.2 Sharing keys between your local machine and the server

First you need to generate some.

```bash
ssh-keygen -t rsa -b 4096 -C "hfb@complex.codes"
```

The best way is probably using ssh-copy-id. Will try using this link.

[Link to Digital Oceans article](https://www.digitalocean.com/docs/droplets/how-to/add-ssh-keys/to-existing-droplet/#with-ssh-copy-id)

````
usermod -aG sudo 
```

