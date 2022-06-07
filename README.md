<p align="center">
<a href="http://sendinair.com/"><img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/w_400/v1654403006/SendInAir%20design/SendInAir_logo2_vzge5u.png" /></a>
</p>

# SendInAir NFT Server

SendInAir NFT Server. It can be used to mint and transfer NFTs, and check balance with wallet addresses.

## Supported blockchain
- Klaytn
- Ethereum (Work in progress)

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
- Start with `docker-compose -f production.yml up --build -d`
- Stop with `docker-compose -f production.yml down`

## How to test API
1. [Download Insomnia (API testing tool)](https://insomnia.rest/download)
2. [![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=SendInAir%20NFT%20Server&uri=https%3A%2F%2Fsendinair-doc-test.s3.ap-northeast-2.amazonaws.com%2Fdoc%2Btest%2Fsendinair_nft_server.json)

## How to change PORT
- Change PORT in .env file

## Usage

<p align="center">
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_500/v1654583596/sendinair_project/sendinair_nft_wallet_create_xlvdrl.jpg" />
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_500/v1654583596/sendinair_project/sendinair_nft_wallet_create_result_gsnprc.jpg" />
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_300/v1654583596/sendinair_project/sendinair_nft_wallet_list_fophgo.jpg" />
</p>
