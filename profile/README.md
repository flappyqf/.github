# FlappyQF - Flappy Bird Quadratic Funding
## 👀What is FlappyQF?
FlappyQF is a platform that employes a Defi approach that ensures fair competition between projects while allowing users to interact with the iconic flappy birds as part of experience.

## Product Description
### ‼️Problem Statement
This innovative projects aims to tackle a few major problems that are being faced in the Defi space
- Complicated contribution process
- Unfair competition among projects due to unbalanced project's followers

### 🎯Vision
FlappyQF envisions a fair and engaging platform that democratizes project funding through gamified contributions, ensuring a level playing field for all projects while fostering community participation and transparency.

### 🚨Unique Value Proposition
What sets FlappyQF apart is its combination of fairness, ease of use, and engaging gamification, making project funding more accessible and enjoyable.

## ⚒️How it's Made?
Users can contribute to projects while playing a flappy bird-inspired game, where their contributions help boost the project's visibility. The more they contribute, the higher the project soars, powered up by their support.

## The Stack
1. Frontend - Next.JS, TailwindCSS, React, Javascript, Typescript
2. UI Library - DaisyUI, Aceternity UI
3. Web3 Development - Solidity, Foundry, ThirdWeb


## Track We're Applying For
### Robust Democracy
The FlappyQF platform is aimed at making something that is already innovative even better. Quadratic Funding is a novel concept that we feel many can easily get onboarded to if being presented in a gamified format while also helping amplify more contribution impact of smaller organizations, this helps tackle centralization risks and ensures that power is distributed fairly and by merit.

## Sponsor Prizes
### Scroll
#### Deploy on Scroll
1. [Mock USDC](https://sepolia.scrollscan.com/address/0xcf6bc8d4d55b4baba1e7783400f3bf7fbd55cf5b#code)
2. [⁠FlappyQF Factory Contract](https://sepolia.scrollscan.com/address/0x5922F957C2DF08FE3dD5f6Dd8f2f7FE14fF9c43f#code)
3. [FlappyQF Implementation Contract](https://sepolia.scrollscan.com/address/0xb72cB3Cac841CeafCE22422179442Bd200C24417#code)
4. [⁠Game Verifier Contract](https://sepolia.scrollscan.com/address/0x54D161e5f34Ea7b975BFc036a280290239fa6d12#code)
5. [Game Proving Contract](https://sepolia.scrollscan.com/address/0x1FFFd4b3051E2e9884627083a9daE472c7D04521#code)

#### Best Game on Scroll
We are aiming for a world where the traditional flappy bird concept can be used to introduce verifiable multipliers that can be used to amplify contributions made by anyone, anywhere to their favourite projects participating in the FlappyQF round. Three.js was used to render the graphics, and the graphics reflect the cyberpunk vibes of Tokyo. The goal was for this score to be used as private inputs where a proof can be produced after and that proof is used to verify if the project is eligible for a multiplier or not.

### Cabinet
#### DApps that require high scalability
We used Cabinet RPC nodes here to deploy our smart contracts on Scroll and Ethereum Sepolia => https://github.com/flappyqf/contracts/blob/main/.env.template#L6-L10

### API3
#### DeFI and oracle extractable value Best implementation of an API3 oracle
#### API3 OEV/Price Feeds
We utilised Price Feed protected by OEV on most chains that we deployed on (Ethereum Sepolia, Scroll Sepolia, and Linea Sepolia), the code integrating it is here => https://github.com/flappyqf/contracts/blob/main/src/FlappyQFFactory.sol#L108-L234. These price feeds facilitate the process of allowing for round contributions to be made in ETH therefore facilitating better user experience, this is then used to convert to USDC reflecting each round's matching pool. A sample transaction showing how we utilised this to convert ETH to USDC with as less slippage as possible => https://sepolia.etherscan.io/tx/0x84edbb2bd3ac96215ff24fddfc923dfefccbdbded435c96fe9cd62b8a773a6f3#eventlog

#### API3 QRNG
On the Ethereum Sepolia network, we utilised API3 Quantum Random Number Generator (QRNG) to capture a random number which is crucial for us to perform randomization of projects that are competing with each other. The code is here => https://github.com/flappyqf/contracts/blob/main/src/FlappyQFFactory.sol#L15-L170. The transaction hash for the number being called for is here => https://sepolia.etherscan.io/tx/0xe18335bd903ed6d2d565e144ed7d5634432117af9a17dbd941abb0dc5180aed9#eventlog. It being retrieved is here => https://sepolia.etherscan.io/tx/0x22095bc7319b6c9f49d4a038e856cec778ffddefd84ad3208146cd987af95a88#eventlog. The random number is used to assign teams as shown here => https://sepolia.etherscan.io/tx/0xf39135a1612dc9d41ae811cf076a370d25c2209f5d1e1b7d8a6b07cd04a6256a#eventlog

### NERO
#### Build dApps or tools using NERO Chain (testnet)
We deployed all our smart contracts to the NERO testnet as we believe in the real-world integration of NERO alongside its partner technologies. We loved the experience of seamlessly deploying it to an EVM-compatible chain.

1. [Mock USDC](https://testnetscan.nerochain.io/address/0xc33c0203a9F4eA06e2627Fc6635518D6C2993ddF/transactions#address-tabs)
2. [⁠FlappyQF Factory Contract](https://testnetscan.nerochain.io/address/0x460c44641673b2fB1d7D769f01B309EAA5eAc533)
3. [FlappyQF Implementation Contract](https://testnetscan.nerochain.io/address/0xA419a7a700dE519C95CF012767F78f90E115A8EC)
4. [⁠Game Verifier Contract](https://testnetscan.nerochain.io/address/0xe9E4af72b567a9CBD6460CDA0466D071934e890d)
5. [Game Proving Contract](https://testnetscan.nerochain.io/address/0xe4e52354d9625CCa463B071dAc1Af27533cbEc00)
   
### Metamask/ Linea
1. [Mock USDC](https://sepolia.lineascan.build/address/0x460c44641673b2fB1d7D769f01B309EAA5eAc533)
2. [⁠FlappyQF Factory Contract](https://sepolia.lineascan.build/address/0xe9E4af72b567a9CBD6460CDA0466D071934e890d)
3. [FlappyQF Implementation Contract](https://sepolia.lineascan.build/address/0xe4e52354d9625CCa463B071dAc1Af27533cbEc00)
4. [⁠Game Verifier Contract](https://sepolia.lineascan.build/address/0xeA9c9a0e5E6493F2BD8a1E81e68a52b63D315819)
5. [Game Proving Contract](https://sepolia.lineascan.build/address/0xCB8Eb5882FBDf0a746aec8857a36132B2aE42714)
   

### API3
1. [Mock USDC]()
2. [⁠FlappyQF Factory Contract]()
3. [FlappyQF Implementation Contract]()
4. [⁠Game Verifier Contract]()
5. [Game Proving Contract]()

### ENS
1. [Mock USDC]()
2. [⁠FlappyQF Factory Contract]()
3. [FlappyQF Implementation Contract]()
4. [⁠Game Verifier Contract]()
5. [Game Proving Contract]()



   



