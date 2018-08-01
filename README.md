# Lottery Pool

Lottery pool is a simple web based game where you can enter to compete with other players
to win money

you can play [here](https://aklssl.now.sh)

The game works as follows:

1. A manager starts the game
2. Players has to pay a least 0.1 ether to enter the game
3. The game prize is created by collecting all the ether paid by players
4. The smart contract behind the game pick randomly a winner and sends the money to its account


## For devs

This game is interacting with a tested and deployed smart contract placed in this repo,
where you can find the smart contract solidity code, a **compile** and a **deploy** script,
together with lots of **test cases**.

[lottery](https://github.com/Rafaell416/lottery)

The contract was deployed to Rinkeby Test Network using [infura](https://infura.io/)


### Running the app locally

`
git clone git@github.com:Rafaell416/lottery-pool.git

cd lottery-pool

yarn install
`
