# Voting Smart Contract

This repository contains a Solidity smart contract for conducting voting processes, along with a React front-end application to interact with the contract.

## Smart Contract Details

### Prerequisites

- Solidity compiler version: ^0.8.0
- SPDX-License-Identifier: MIT

### Features

- **Voter Management:** Admin can add voters to the system.
- **Ballot Creation:** Admin can create new ballots with specified choices and duration.
- **Voting:** Voters can cast their votes on available ballots.
- **Vote Monitoring:** Ballots display current votes, and voters can see if they have already voted.

### Contract Structure

- **Voting.sol:** Main contract file containing the implementation of the voting system.
- **Mappings:** Utilizes mappings to track voters, ballots, and votes.
- **Modifiers:** Includes a custom modifier for admin-only functions.
- **Functions:** Provides methods for adding voters, creating ballots, and casting votes.

## Front-End Application

### Prerequisites

- React version: ^17.0.2

### Features

- **Admin Interface:** Admin can create new ballots and add voters.
- **Voter Interface:** Voters can view available ballots and cast their votes.
- **Real-Time Updates:** Automatically fetches ballot data and updates voting status.

### Application Structure

- **App.js:** Main component handling the application logic and interaction with the smart contract.
- **Components:** Contains reusable UI components for ballot creation, voter management, and voting.
- **Web3 Integration:** Utilizes Web3.js to interact with the Ethereum blockchain.

## How to Use

1. Clone the repository.
2. Install dependencies for both the smart contract and the front-end application.
3. Deploy the smart contract to an Ethereum network.
4. Configure the front-end application to connect to the deployed contract.
5. Run the application and start voting!

## License

This project is licensed under the MIT License - 
