# Front-run-pancakeswap-bot
The front run bot for Pancakeswap (BSC)

Pancakeswap frontrun bot that purchases the specified token when liquidity is added.
Bot is following the “target” address and trades tokens on PancakeSwap.
Bot can front run by setting higher gas fee and using direct node for transaction

## Prerequisities
- Node and NPM 
- Wallet with BNB for gas and token swap

## Steps to Run BOT
- Update env.js and provide private key to wallet and token address you want to target
- Bot is preconfigured for Pancakeswap on BSC. Review configuration in constants.js. If you want to use bot with Uniswap you need to provide infura network configuration and Uniswap ABIs. Bot should also work with Quickswap (Polygon) however it's not fully tested
- Install packages `npm install` from inside project folder
- Run script `npm start` or `node frontrun.js`

## Team Members
Cassandra Rodrigues - https://www.linkedin.com/in/cassandra-rodrigues-a712b0202
Kate Rebello - https://www.linkedin.com/in/kate-rebello-a38235194
Aaron Rodrigues - https://www.linkedin.com/in/aaron-rodrigues-12b3071bb
Vatsal Mehta - https://www.linkedin.com/in/vatsal-mehta-270556200
