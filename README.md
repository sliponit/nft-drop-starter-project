# Solana NFT Drop Project
### Welcome 👋

1. cd into the `app` folder
2. Run `npm install` at the root of your directory
3. Run `npm run start` to start the project
4. Start coding!

### To deploy on metaplex
```sh
ts-node ~/install/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload -e devnet -k ~/.config/solana/devnet.json -cp config.json ./assets
```

verify
```sh
ts-node ~/install/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts verify_upload -e devnet -k ~/.config/solana/devnet.json
```

arweave
https://explorer.solana.com/address/7CWJarE446nZieLMYHBDC2dn6G93bTdA7Y2s1MqRsoMJ?cluster=devnet


pinata
https://explorer.solana.com/address/51DB6CJfKFU3dEjNVQBi3JYs4jDUhd5G1uxSMRntzrvb?cluster=devnet