# ideation-notes
## Concept
 - Organize pools with certain `breakLimits`
 - People can invest their ERC20{in the backend we put all this ERC20 into AAVE Lending pool}
 - Using the **chainlink-alarm-clock**, the pool will break when the **exchange rate**(from chainlink price feed) reaches the `breakLimit`
   - Users get back their ERC20 {with some `interest`}
 - One person at random/highest staker will be awarded an **NFT**

## Work required
 - Depoying on Moonbeam
 - Using Chainlink price feeds, VRF, alarm clock
 - Shifting funds from Moonbeam to AAVE


## Structure
<img src="./assets/image.png" width="600">