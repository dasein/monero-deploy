# monero-deploy

Bring up a monerod mining pool in docker

## Getting Started

1. Create a ./wallet directory and place your wallet and password in this
   directory (optionally update Dockerfile.monero-wallet-rpc as to your
   wallet location)

2. Bring up monerod and give it time to sync

   ```
   docker-compose up monerod
   ```

3. Bring up everything else

   ```
   docker-compose up
   ```

### Prerequisites

docker-ce >= 17.09.1-ce

docker-compose >= 1.17.1

## Built With

* [monerod](https://getmonero.org/) - XMR altcoin
* [cryptonote-xmr-pool](https://github.com/clintar/cryptonote-xmr-pool.git) - Cryptonote pool software

## License

This project is licensed under the MIT License
