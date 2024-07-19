# airchain-testnet

```
# start rollups
git clone https://github.com/sarox0987/airchain-testnet.git
cd airchain-testnet

#replace `<eigen-wallet-address>` `<tracker-wallet-address>` `<your-mnemonic-phrase>` for all services

docker-compose up -d evmos-0 evmos-1
# wait for containers health status
docker ps

# then start trackers
docker-compose up -d tracker-0 tracker-1

# get evmos station private key 
cat rollups/evmos-0/evmos.key
cat rollups/evmos-1/evmos.key
```


