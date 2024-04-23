# Zero Involvement and Pairing Authentication (ZIPA) Cluster Device Setup (zcds)

> Code to setup a device within the SSL ZIPA cluster

## Table of Contents

- [Zero Involvement and Pairing Authentication (ZIPA) Cluster Device Setup (zcds)](#zero-involvement-and-pairing-authentication-zipa-cluster-device-setup-zcds)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [How to Install](#how-to-install)
    - [Installation steps](#installation-steps)

## About

Ansible code to setup and install software on devices within the Software and
Systems Laboratory (SSL) ZIPA cluster.

## How to Install

This code has been tested on Raspberry Pi 3s and 4s running Debian.

### Installation steps

1. Clone this repository onto the client device
1. `make build`
1. `make run`
