# JamesExchange Exchange Server

It can be used for fungible asset like crypto currencies and security tokens.

<br/>

## System requirements

Your system must have the following requirements to install exchange engine.
- Git
- Docker
- Docker-compose

<br/>

## Install Docker & Docker-compose
*For Linux and Mac
> Installation
- [Run](https://github.com/docker/docker-install) `curl -fsSL https://get.docker.com -o get-docker.sh`
- Then `sh get-docker.sh` to install Docker
- `sudo apt  install docker-compose` to install Docker-compose
> Post Installation [(permission setting)](https://docs.docker.com/engine/install/linux-postinstall/)
- `sudo groupadd docker` (move on to the next step if it already exists)
- `sudo usermod -aG docker $USER`
- `newgrp docker`

*For Windows
> [Download and install git](https://github.com/git-guides/install-git/)

> Download Docker
> [Docker Homepage](https://www.docker.com/get-started/)

> Download docker-compose
> [docker-compose](https://docs.docker.com/compose/install/)

<br/>

## Instructions
Download codes and run with following command
- Clone this repository `git clone https://github.com/jamesexchange/exchange-api.git`
- Start with `docker-compose -f production.yml up --build -d`
- Stop with `docker-compose -f production.yml down`

## How to receive the updates
- Stop the server first before recieving the updates
- Run `docker pull jamesexchange/exchange-server`

## How to change PORT
- Stop the server if it's already running
- Change PORT in the .env file
- Start the server


License
=======

    Copyright 2022 JamesExchange,Inc

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

