# Forum dApp: A Decentralized Forum Application

Welcome to the **Forum dApp**! This decentralized application (dApp) allows users to create posts, add comments, participate in polls, and engage with the content through upvotes and downvotes. The dApp runs on a smart contract that ensures all interactions are securely and transparently managed on the blockchain.

## Features
- **Create Posts:** Users can publish posts to the forum on specific topics.
- **Add Comments:** Users can comment on posts to foster discussion.
- **Create Polls:** Users can initiate polls within posts, enabling community voting.
- **Upvote/Downvote:** Users can engage with posts and comments by upvoting or downvoting them.
- **List User Posts and Comments:** View all posts and comments made by specific users.

## Quest Details

### By the end of this quest, you will be able to:
1. Describe the functionalities of the Forum smart contract.
2. Write the Forum smart contract.
3. Deploy the Forum smart contract.
4. Verify and publish the Forum smart contract on Arbiscan.

## Setup Instructions

### 1. Prerequisites
To get started, you will need:
- **Node.js** (v14.x or higher)
- **npm** or **yarn**
- **Hardhat** (for compiling and deploying smart contracts)
- **MetaMask** (or any other web3 wallet)
- **Arbitrum Network** for deploying the contract.

### 2. Smart Contract
The Forum smart contract is written in Solidity and provides the following core functionalities:
- **Post Creation**
- **Comment Creation**
- **Poll Creation**
- **Post/Comment Voting**

To write and deploy the smart contract, follow the steps outlined below.

#### a) Write the Forum Smart Contract
- Open your Solidity environment (e.g., Remix or Hardhat).
- Implement the core functionalities (post, comment, vote, poll).

#### b) Deploy the Forum Smart Contract
- Use Hardhat or Remix to deploy your contract to the Arbitrum testnet or mainnet.

#### c) Verify and Publish on Arbiscan
- Once deployed, verify your contract on Arbiscan using the contract address and source code.

### 3. Frontend Development
The frontend will allow users to interact with the smart contract. You will implement the following UI components:
- **Post Creation Form**: Allows users to create posts.
- **Poll Creation Form**: Lets users create polls within posts.
- **Comment Section**: Enables users to comment on posts.
- **Upvote/Downvote Buttons**: Users can upvote or downvote posts and comments.
- **User Post/Comment List**: Displays all posts and comments made by a user.

### 4. Interacting with the Smart Contract
After deploying the smart contract, connect it with the frontend using **ethers.js** or **web3.js**. You can create transactions to interact with the contract functions like creating posts, comments, polls, and voting.

### 5. Running the Project Locally
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd forum-dapp
    npm install
    npx hardhat compile
    npx hardhat run scripts/deploy.js --network arbitrum
    npm start