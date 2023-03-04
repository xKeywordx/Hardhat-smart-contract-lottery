# hardhat-smart-contract-lottery
Sample lottery smart contract in Hardhat

The contract allows users to enter a raffle after they pay a 0.01 ETH entrance fee.
Using Chainlink's VRF, the contract will pick a random address that will win the raffle and give all users to the winning address.
While the raffle is ongoing, the state of the raffle changes from "open" to "ongoing", meaning that new users can not join at this time and they need to wait for the current raffle to finish in order to join the next one.
