<p align="center">
<a href="http://sendinair.com/"><img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/w_400/v1655263343/SendInAir%20design/sendinair_logo_dgzmyv.png" /></a>
</p>

# SendInAir NFT Server

SendInAir NFT Server. It can be used to mint and transfer NFTs, and check balance with wallet addresses.

## Supported blockchain
- Ethereum
- Klaytn

## Features
- Minting
- Transfer
- Transfer (Fee delegated to master)
- Get balance
- Get token info
- Get token uri

## System requirements

Your system must have the following requirements to install exchange engine.

> Download Docker
> [Docker Homepage](https://www.docker.com/get-started/)

> Download docker-compose
> [docker-compose](https://docs.docker.com/compose/install/)


## Instructions
Download codes and run with following command
- Clone this repogitory `git clone https://github.com/sendinair/sendinair-nft-server.git`
- Enter your API key in the .env file
- Start with `docker-compose -f production.yml up --build -d`
- Stop with `docker-compose -f production.yml down`

## How to test the APIs
1. [Download Insomnia (API testing tool)](https://insomnia.rest/download)
2. [![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=sendinair-nft-server&uri=https%3A%2F%2Fsendinair-doc-test.s3.ap-northeast-2.amazonaws.com%2Fdoc%2Btest%2Fsendinair-nft-server.json)

## How to receive updates
- Stop the server first before recieving the updates
- Run `docker pull sendinair/crypto-wallet-server`

## How to change PORT or API_KEY
- Stop the server if it's already running
- Change PORT or API_KEY in the .env file
- Start the server

## Usage

<p align="center">
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_500/v1654583596/sendinair_project/sendinair_nft_wallet_create_xlvdrl.jpg" />
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_500/v1654583596/sendinair_project/sendinair_nft_wallet_create_result_gsnprc.jpg" />
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_300/v1654583596/sendinair_project/sendinair_nft_wallet_list_fophgo.jpg" />
</p>
