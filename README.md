# docker-labs-proxy
* Scripts for use labs.play-with-docker.com as socks5 proxy
## Dependencies:
```
Chrome or Chromium
ssh
curl
python3
selenium
configparser
```
## To get started:
* **Download the latest revision**
```
git clone https://github.com/VHSgunzo/docker-labs-proxy.git && cd docker-labs-proxy
```
* **Install python dependencies for docker-labs-proxy**
```
pip install -r requirements.txt
```
* **Specify your username and password for docker.com in the .env file**
* **Execute docker-labs-proxy**
```
./docker-labs-proxy
```
* **Use local socks5://127.0.0.1:1080 proxy**
```
curl -x socks5://127.0.0.1:1080 ifconfig.io
```
