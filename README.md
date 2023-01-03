# Simple Faucet for ChainLink

* Deployed contract at: 0xcF1496e4667F89dE10824176EbF70397Da68cc48

Allows user to get ChainLink Tokens:
1. Visit live URL: http://152.67.71.249:9988/
2. Add the following token address to your Metmask wallet: 0x48120Eb14AB6EBe2C4F937c3c4915ae1DaF96736
3. Click Connect Wallet and get Tokens -> You should receive 1 LINK
4. After 1 Minute another Link token can be asked for

## Run locally with docker:
* docker build -t faucet-dapp-starter-code-connect-wallet .
* docker run -p 9999:3000 faucet-dapp-starter-code-connect-wallet
