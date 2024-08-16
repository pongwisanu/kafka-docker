# Kafka on docker with sample

## Detail


## Installation

### Local install

Skip if want to use docker

install openjkd-11
```
sudo apt-get install openjdk-11-jre-headless
```
download kafka
```
tar -xzf kafka_2.13-3.5.0.tgz
cd kafka_2.13-3.5.0
```
### prometheus (optional)

build for running on docker need to change some config for local installation 

download jmx
```
https://github.com/prometheus/jmx_exporter/releases
```


## Running
```
docker compose up -d --build
```

## Testing
