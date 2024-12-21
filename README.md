# FortunEther

FortunEther is a decentralized sports betting application on the Ethereum blockchain, supporting **[moneyline betting](https://news.sportsinteraction.com/guide/moneyline-betting-explained)**.

## Features

1. **Add Bet**: Admin can add new bets and set odds.
2. **Bet**: Users can bet with Ether, recorded on the blockchain.
3. **My Bets**: Users can view all their bets and earnings/losses.
4. **Close Bet**: Admin closes bets before the game starts.
5. **Start Payout**: Admin selects winners and starts payouts after the game.
6. **Redeem**: Admin can redeem remaining Ether after payouts.

## Dependencies

- [Node.js](https://nodejs.org/en/download/)
- Truffle: `npm install -g truffle`
- [Ganache](https://www.trufflesuite.com/ganache)
- [Metamask](https://metamask.io/)

## Running the Code

1. Initialize Blockchain Ledger: `truffle migrate --reset`
2. Run DApp Server: `npm run dev`

## Demo

[Live Demo](https://fortunether.herokuapp.com/)

## Credits

Thanks to [goodvibration](https://ethereum.stackexchange.com/users/16043/goodvibration) and [Rob Hitchens](https://ethereum.stackexchange.com/users/5549/rob-hitchens-b9lab) for their answers on Stack Exchange.
