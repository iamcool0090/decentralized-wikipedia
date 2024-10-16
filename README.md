# DecentraWiki

Welcome to DecentraWiki, a decentralized Wikipedia project aimed at combating bias in traditional Wikipedia. Developed during the Aventus Hackathons at Dayananda Sagar College of Engineering (DSCE), DecentraWiki leverages blockchain technology to ensure transparency, accountability, and neutrality in content creation and editing.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

DecentraWiki is a revolutionary platform that addresses the biases prevalent in traditional Wikipedia by decentralizing the content management process. Our goal is to create a more reliable and impartial information source, where every edit and contribution is transparent and verifiable on the blockchain.

## Features

- **Decentralized Content Management**: Uses blockchain technology to store and manage content, ensuring transparency and immutability.
- **Bias Mitigation**: Implemented mechanisms to reduce bias and provide a balanced perspective on various topics.
- **Community Governance**: Allows community members to propose, review, and approve changes to the content.
- **Immutable History**: Every edit is recorded on the blockchain, providing a complete and tamper-proof history of changes.
- **Incentivized Contributions**: Contributors are rewarded with tokens for valuable contributions to the platform.

## Technology Stack

- **Blockchain**: Ethereum or another suitable blockchain platform for decentralized storage and smart contracts.
- **Frontend**: React.js for a responsive and user-friendly interface.
- **Backend**: Node.js and Express.js for server-side logic.
- **Database**: IPFS (InterPlanetary File System) for decentralized storage of content.
- **Smart Contracts**: Solidity for implementing the logic of contributions, reviews, and rewards.

## Installation

To get started with DecentraWiki, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/decentrawiki.git
    cd decentrawiki
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up the environment variables**:
    Create a `.env` file in the root directory and add the necessary configuration settings. Example:
    ```env
    REACT_APP_BLOCKCHAIN_URL=https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID
    REACT_APP_CONTRACT_ADDRESS=YOUR_CONTRACT_ADDRESS
    REACT_APP_IPFS_API_URL=https://ipfs.infura.io:5001/api/v0
    ```

4. **Run the development server**:
    ```bash
    npm start
    ```

## Usage

1. **Access the Platform**:
    Open your browser and navigate to `http://localhost:3000` to access the DecentraWiki platform.

2. **Create an Account**:
    Sign up using your Ethereum wallet to start contributing to DecentraWiki.

3. **Contribute Content**:
    Submit new articles or edit existing ones. Your contributions will be reviewed by the community before being published.

4. **Review and Approve**:
    Participate in the review process by evaluating proposed changes and voting on them.

5. **Earn Rewards**:
    Receive tokens for valuable contributions and reviews.
