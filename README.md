# SendInAir NFT API

<p>
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/v1659149392/SendInAir%20design/BAYC_nft_list_sxn5po.png" />
</p>

SendInAir solves the hardest part of making NFT service and provides APIs for integrating into your Web3 service.

<br/>

## Supported blockchain
- Ethereum
- Klaytn

<br/>

## Features
- Minting
- Transfer
- Transfer (Fee delegated to master)
- Get balance
- Get token info
- Get token uri

<br/>

## System requirements

Your system must have the following requirements to install Sendinair NFT Server.
- Git
- Docker
- Docker-compose

<br/>

## Install Docker & Docker-compose in 1 min
*For Linux
> Installation
- [Run](https://github.com/docker/docker-install) `curl -fsSL https://get.docker.com -o get-docker.sh`
- Then `sh get-docker.sh` to install Docker
- `sudo apt install docker-compose` to install Docker-compose
> Post Installation [(permission setting)](https://docs.docker.com/engine/install/linux-postinstall/)
- `sudo groupadd docker` (move on to the next step if it already exists)
- `sudo usermod -aG docker $USER`
- `newgrp docker`

*For Mac
- [Download and install Docker](https://docs.docker.com/desktop/install/mac-install/)

*For Windows
- [Download and install git](https://gitforwindows.org/)
- [Download and install Docker](https://docs.docker.com/desktop/install/windows-install/)

**You're all ready to use our product! 🎉**

<br/>

## How to create & deploy NFT smart contract
You need an ***already deployed smart contract address*** (ETH / KLAY) to use this in ***production***.
If you are not sure on how to do this, we've created a easy-to-follow wiki for you.

Check it out [here](https://woojae-jun.gitbook.io/sendinair-nft-server/).

***🚗 Or you can skip this part and simply test our API with default environment file***
- We've set all the variables so you can test immediately!

<br/>

## Instructions
Download the product
- Clone this repository `git clone https://github.com/sendinair/sendinair-nft-server.git`
- Go into the ***sendinair-nft-server*** directory

Add necessary information
> Make sure you are in the ***sendinair-nft-server*** directory

> You should enter your information on the ***right*** side of the equal symbol(=)
- Open ***docker-compose.env*** file
- Enter the api key you got from SendInAir in `API_KEY`
  - You can use the tester key that's already included in the file
- Enter your deployed ETH / KLAY contract address in `NFT_CONTRACT_ADDRESS_ETH` or `NFT_CONTRACT_ADDRESS_KLAY`
- Enter your contract owner private key for ETH / KLAY in `NFT_CONTRACT_OWNER_PRIVATE_KEY_ETH` or `NFT_CONTRACT_OWNER_PRIVATE_KEY_KLAY`
- Save and close ***docker-compose.env*** file

Start / Stop the server
- Start the server with `docker-compose -f production.yml up --build -d`
- Stop the server with `docker-compose -f production.yml down`

<br/>

## How to test the APIs
1. [Download Insomnia (API testing tool)](https://insomnia.rest/download)
2. [![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Sendinair%20NFT%20Server&uri=https%3A%2F%2Fsendinair-doc-test.s3.ap-northeast-2.amazonaws.com%2Fdoc%2Btest%2Fsendinair-nft-server-insomnia_2022-07-30.json)

<br/>

## How to receive updates
- Stop the server first before recieving the updates
- Run `docker pull sendinair/nft-server`

<br/>

## How to change the PORT
- Stop the server if it's already running
- Change `PORT` in the ***.env*** file
- Start the server

<br/>

<p align="center">
<a href="http://sendinair.com/"><img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/w_400/v1655263343/SendInAir%20design/sendinair_logo_dgzmyv.png" /></a>
</p>

<br/>

License
=======

    Copyright 2022 SendInAir,Inc

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


