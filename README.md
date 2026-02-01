# avairis_ppa
Avairis Debian Package Repository

## Packages currently available

avairis-ca-certificate

## Install packages from this repository

First, you have to install the avairis_ppa.gpg file so that the package signatures can be verified.

```
sudo -i
curl https://avairis.github.io/avairis_ppa/pubkey.asc | gpg --dearmor -o /etc/apt/trusted.gpg.d/avairis_ppa.gpg
echo "deb [signed-by=/etc/apt/trusted.gpg.d/avairis_ppa.gpg] https://avairis.github.io/avairis_ppa/ ./" > /etc/apt/sources.list.d/avairis_ppa.list
apt-get update
```

