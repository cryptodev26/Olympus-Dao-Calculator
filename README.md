# sohm-viewer

wsOHM is a wrapped version of sOHM such that:
• When you wrap your sOHM the amount of wsOHM you get is: sOHM / index.
• 50 sOHM at the index of 10 gets you 5 wsOHM.
• Upon unwrapping wsOHM the amount of OHM you get is: wsOHM x index.
• Example: 5 wsOHM with an index of 12, unwraps to 60 sOHM
• Price of 1 wsOHM is always approximately = price of 1 OHM x Current Index
• You can check current index and wsOHM price at https://app.olympusdao.finance/#/dashboard

You can currently obtain wsOHM by:
• Wrapping your sOHM at abracadabra.money on ETH Mainnet
• Buying it on sushiswap on Arbitrum L2
• Buying it on traderjoe.xyz on Avax Chain

wsOHM Contract on ETH Mainnet:
Ω •0xca76543cf381ebbb277be79574059e32108e3e65

wsOHM Contract on Arbitrum L2:
Ω •0x739ca6D71365a08f584c8FC4e1029045Fa8ABC4B
wsOHM-WETH | Analytics

wsOHM Contract on Avax Chain:
Ω •0x8CD309e14575203535EF120b5b0Ab4DDeD0C2073
MIM-wsOHM | Analytics

wsOHM markets are new and have thin liquidity. Expect slippage and price inefficiencies. Currently wsOHM will NOT show up on the main website's staking page.


0x383518188c0c6d7730d91b2c03a03c837814a899
User Avatar
Sohm contract:
0x04f2694c8fcee23e8fd0dfea1d4f5bb8c352111f

Usage
======================

1. first have to deploy smart contract (flashloan.sol) to mainnet(if deploy to test net  please check provider address and token address)
2. install Dapp's enviroments(node_module) 
```
$ npm install
```
3. run dapp
```
$ npm run start

```

This Dapp for mainnet, So if you want test on testnet please modifiy some variables.

