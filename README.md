## Sample Hardhat Project

- This repository contains a decentralized voting application, often referred to as a Voting Dapp, built on the Ethereum blockchain. This application leverages blockchain technology to create a secure, transparent, and tamper-proof voting system. Users can cast their votes, and the results are recorded on the Ethereum blockchain, ensuring the integrity of the voting process. This type of application has the potential to enhance trust in elections and voting procedures by providing a verifiable and immutable record of the votes.

## Project Setup
```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

```
//install the docker
sudo apt  install docker.io
//show all container
sudo docker ps -a
//show all images
sudo docker image ls
//to build the image
sudo docker build -t jitendra/voting-dapp .
//to run the image
sudo docker run -p 3000:3000 jitendra/voting-dapp
```
