# **Gaming-Site: Langur Burja on Polygon**

## **Project Overview**
Gaming-Site brings the traditional Nepali game Langur Burja to the Polygon blockchain, combining classic gameplay with modern betting features. This decentralized application allows players to place bets, engage with various innovative betting strategies, and enjoy a secure and transparent gambling experience.

## **Features**
- **Traditional Langur Burja Gameplay**: Central betting area for classic bets on six symbols: Monkey, Flag, Fish, Prawn, King, and Tiger.
- **Innovative Betting Strategies**: Includes combination bets, pattern bets, sequence bets, streak betting, and multiplier dice to enhance gameplay.
- **Progressive Jackpot**: A growing jackpot pool that offers players the chance to win big.
- **Dynamic Odds and Risk Levels**: Real-time adjustments to odds and customizable risk levels for personalized betting experiences.
- **User-Friendly Interface**: Built with a modern UI/UX approach using React, making the game visually appealing and easy to navigate.
- **Secure Transactions**: Integration with MetaMask and Ethers.js for seamless and secure fund management.

## **Tech Stack**
- **Smart Contracts**: Solidity on Polygon
- **Front-end**: React with TypeScript
- **Back-end**: Node.js with Express
- **Blockchain Interaction**: Ethers.js
- **Wallet Integration**: MetaMask

## **Installation**
### **Prerequisites**
- Node.js
- Yarn or NPM
- MetaMask extension installed in your browser

### **Steps**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/PrashantGoit/Gaming-Site.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Gaming-Site
   ```

3. **Install dependencies:**
   ```bash
   yarn install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory and add your Polygon network settings, such as RPC URLs, private keys, and contract addresses.

5. **Compile and deploy smart contracts to Polygon:**
   ```bash
   yarn hardhat compile
   yarn hardhat run scripts/deploy.js --network mumbai
   ```

6. **Start the development server:**
   ```bash
   yarn start
   ```

7. **Open your browser and navigate to** `http://localhost:3000`.

## **Usage**
- Connect your MetaMask wallet to the Polygon network.
- Place bets on the Langur Burja board by selecting symbols and bet types.
- Monitor your bets, winnings, and account balance in real-time.
- Withdraw your winnings directly to your MetaMask wallet.

## **Future Plans**
### 1. **Cryptocurrency Integration**
- **Native Token Integration**: Develop a native token for in-game transactions, staking, and rewards.
- **Cross-Chain Compatibility**: Expand to other EVM-compatible chains like Ethereum and Binance Smart Chain.
- **DeFi Features**: Integrate staking, farming, and lending options for the native token.
- **NFTs**: Introduce NFTs as unique in-game assets that players can collect and trade.
- **Governance**: Implement a token-based governance model for community-driven decisions.

### 2. **Enhanced Gameplay Features**
- **Social Betting and Leaderboards**: Enable players to compete with friends and climb leaderboards.
- **AI-Based Betting Suggestions**: Use machine learning to offer personalized betting tips.
- **Mobile App**: Develop mobile apps for Android and iOS to reach a wider audience.

### 3. **Security and Compliance**
- **Security Audits**: Regular audits of smart contracts and security practices.
- **Regulatory Compliance**: Ensure adherence to relevant gambling laws and regulations.

## **Contributing**
We welcome contributions! Fork the repository, create a new branch, and submit a pull request. Make sure your code follows our guidelines and passes all tests.

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## **Contact**
For support or inquiries, contact Prashant Goit at [reach@prashantgoit.com.np](mailto:reach@prashantgoit.com.np).

---
