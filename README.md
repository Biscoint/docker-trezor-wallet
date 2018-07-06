# docker-trezor-wallet

## Overview
This is a Dockerfile to build an image for a local Trezor Wallet (instead of http://wallet.trezor.io/)
It was created based on blog post by Bach N. [Run a local instance of Trezor Wallet](https://medium.com/@xbach/run-a-local-instance-of-trezor-wallet-442febc4ac81)

If you have improvements or suggestions please open an issue or pull request on the GitHub project page.

### Links
- [Run a local instance of Trezor Wallet](https://medium.com/@xbach/run-a-local-instance-of-trezor-wallet-442febc4ac81)

## Quick Start

### Build
To build the image:
```
sudo docker build . -t bit4/trezor-wallet

```
### Running
To simply run the container:
```
sudo docker run -d -p 80:8080 bit4/trezor-wallet:latest
```
