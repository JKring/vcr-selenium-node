# Selenium Grid Node - Chrome

Selenium Node configured to run Google Chrome.

## Dockerfile

[`selenium/node-chrome` Dockerfile](https://github.com/SeleniumHQ/docker-selenium/blob/master/NodeChrome/Dockerfile)

## How to use this image

```
./generate.sh 3.0.1-fermium
docker build -t vcr-selenium-node .
docker run --rm -i -t -d --link vcr-selenium:hub vcr-selenium-node
```