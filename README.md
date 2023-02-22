# learn-btc-wallet
The wallet that helps you understand

**NOTE** This wallet is not meant to be used with real bitcoin. Run your node in regtest mode!

### Requirements:
- [Client](https://github.com/facebook/learn-btc-wallet-client)
- [Server](https://github.com/facebook/learn-btc-wallt-server)
- Bitcoin node running in regtest mode (see bitcoin.conf)
- Docker?
- MongoDB

Checkout [this repo](https://github.com/daGoodenough/docker-bitcoin) forked from @chanhosuh

You can run the node with Docker and the rest of the app on your local machine, or use Docker compose.

### Get started
1. Create root dir:

```git clone https://github.com/daGoodenough/learn-btc-wallet.git```

2. From cloned repo

```git clone https://github.com/daGoodenough/docker-bitcoin```

3. Build docker-bitcoin

4. From here you can use the compose file in the docker-bitcoin folder to run BTC Core alone.\n
Or user the compose file in the root dir to orchestrate the whole app.

### Notes:
- Uses MongoDB Atlas for hosting the db. You will need to create your own account and auth [here](https://www.mongodb.com/atlas/database) or configure to run locally.
- Requires Docker Compose.

### Contribution:
I'd love the help to make this app the learning resource I know it can be.
Feel free to make pull requests as you see fit, or reach out to me for more collaboration.

