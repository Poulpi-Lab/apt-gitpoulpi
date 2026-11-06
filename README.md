# GitPoulpi APT repository

Signed APT repository for [GitPoulpi](https://github.com/Poulpi-Lab/GitPoulpi), a lightweight cross-platform terminal Git client (Debian and Ubuntu, amd64 and arm64).

```sh
sudo install -d -m 0755 /etc/apt/keyrings
curl -fsSL https://poulpi-lab.github.io/apt-gitpoulpi/gitpoulpi-archive-keyring.gpg | sudo tee /etc/apt/keyrings/gitpoulpi.gpg >/dev/null
sudo curl -fsSL -o /etc/apt/sources.list.d/gitpoulpi.sources https://poulpi-lab.github.io/apt-gitpoulpi/gitpoulpi.sources
sudo apt update && sudo apt install gitpoulpi
```

The repository itself is published on the `gh-pages` branch by the GitPoulpi release workflow; do not edit it by hand.
