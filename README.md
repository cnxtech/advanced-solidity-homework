# Puppercoin Crowdsale

The following code creates an ERC20 token that will be minted through a Crowdsale contract which is leveraged from the OpenZeppelin Solidity library.  This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin).  This contract will mint the tokens automatically and distribute them to buyers in one transaction.  The Crowdsale is required to enable refunds if successful and the goal is met, which is a maximum of 300 Ether.  The crowdsale will run for 24 weeks.  The Crowdsale will function over three smart contracts: PupperCoinSaleDeployer, PupperCoinSale and PupperCoin.

---

## Technologies

Language: Solidity

Developed with [Remix](https://remix.ethereum.org/) and [MetaMask](https://metamask.io/)

---

## Instructions
*For the purpose of this demonstration, the goal has been set to 3 Ether and the length of the Crowdsale has been shortened*

1. Compile PupperCoinSaleDeployer, PupperCoinSale and PupperCoin contracts
![compiler](Resources/compiler.png)

2. Deploy PupperCoinSaleDeployer contract
![deployer_contract](Resources/deployer_contract.gif)

3. Deploy PupperCoin and PupperCoinSale contracts
![coin_sale_contracts](Resources/coin_sale_contracts.gif)

4. Buy PupperCoin tokens and check out Crowdsale functionality
![buy_tokens](Resources/buy_tokens.gif)

5. Reach PupperCoin Crowdsale goal
![reach_goal](Resources/reach_goal.gif)

6. Close and finalize Puppercoin Crowdsale
![close_finalize](Resources/close.gif)


---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell

