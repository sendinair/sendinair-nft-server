<br/>
<p align="center">
<a href="http://sendinair.com/"><img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/w_400/v1655263343/SendInAir%20design/sendinair_logo_dgzmyv.png" /></a>
</p>
<br/>

# SendInAir NFT Server

SendInAir NFT Server. It can be used to mint and transfer NFTs, and check balance with wallet addresses.

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

> [Download and install git](https://github.com/git-guides/install-git/)

> Download Docker
> [Docker Homepage](https://www.docker.com/get-started/)

> Download docker-compose
> [docker-compose](https://docs.docker.com/compose/install/)

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
- Enter your deployed ETH / KLAY contract address in `NFT_CONTRACT_ADDRESS_ETH` or `NFT_CONTRACT_ADDRESS_KLAY`
- Enter your contract owner private key for ETH / KLAY in `NFT_CONTRACT_OWNER_PRIVATE_KEY_ETH` or `NFT_CONTRACT_OWNER_PRIVATE_KEY_KLAY`
- Save and close ***docker-compose.env*** file

Start / Stop the server
- Start the server with `docker-compose -f production.yml up --build -d`
- Stop the server with `docker-compose -f production.yml down`

<br/>

## How to test the APIs
1. [Download Insomnia (API testing tool)](https://insomnia.rest/download)
2. [![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=sendinair-nft-server&uri=https%3A%2F%2Fsendinair-doc-test.s3.ap-northeast-2.amazonaws.com%2Fdoc%2Btest%2Fsendinair-nft-server.json)

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

## Usage

<p align="center">
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_500/v1654583596/sendinair_project/sendinair_nft_wallet_create_xlvdrl.jpg" />
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_500/v1654583596/sendinair_project/sendinair_nft_wallet_create_result_gsnprc.jpg" />
  <img src="https://res.cloudinary.com/dqvwj4pl2/image/upload/h_300/v1654583596/sendinair_project/sendinair_nft_wallet_list_fophgo.jpg" />
</p>
