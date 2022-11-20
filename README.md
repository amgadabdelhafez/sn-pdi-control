# SN PDI Control
## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

Control your SN Dev PDIs using this CLI tool. it can wake your instances up, reset, upgrade, or release your instances, request a new instance with specific version.


## Usage <a name = "usage"></a>
```
--wake-up             wakes up all instances in config file
--reset-instance      resets an instance to its out-of-the-box settings
--release-instance    releases an instance back to pool
--upgrade-instance    upgrades an instance back to pool [TODO]
--add-account         add a new account credentials to config file
--config-file         use a specific config file instead of default config.json
--not-headless        show browser window (for debugging)
```

## Getting Started <a name = "getting_started"></a>


Install dependencies to run local, or use Dockerfile to run in a container.

```
# install local
pip install -r requirements.txt
```
```
# run local
python wake.py --wake-up
```


```
# install as docker container
docker compose build
```


```
# run as docker container
docker compose up
```
