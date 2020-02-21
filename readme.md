# Installation

## Install jdk

```bash
sudo apt-get install default-jdk
```

## Install the server

```bash
git clone https://github.com/nealarec/selenium-server.git
sudo mv selenium-server /opt/selenium/
sudo ln -s /opt/selenium/selenium-server.service /lib/systemd/system
```

# To start the server

```bash
sudo systemctl start selenium-server.service
```
