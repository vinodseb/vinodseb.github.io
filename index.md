# Hello World

### Purge Residual Configurations
```sh
dpkg -l | grep '^rc' | awk '{print $2}' | xargs sudo apt-get -y purge
```
