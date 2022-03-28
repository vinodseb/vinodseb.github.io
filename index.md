# Random Linux Commands

### Purge Residual Configurations
```sh
dpkg -l | grep '^rc' | awk '{print $2}' | xargs sudo apt-get -y purge
```

### Start Dummy HTTP Server
```sh
python3 -m http.server
```
