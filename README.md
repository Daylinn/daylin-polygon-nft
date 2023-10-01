# NFT Polygon Marketplace

## Overview

Welcome to the NFT Polygon Marketplace, a decentralized marketplace built on the Polygon (formerly Matic) network. This project was developed as part of an internship at The Walt Disney Company. The marketplace enables users to create, buy, sell, and trade non-fungible tokens (NFTs) with ease. Take a look at what our marketplace has to offer!

## Table of Contents

1. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Configuration](#configuration)
2. [Project Structure](#project-structure)
3. [Smart Contracts](#smart-contracts)
4. [Frontend](#frontend)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Getting Started

### Prerequisites

- Node.js and npm installed on your development machine.
- Polygon (Matic) wallet for testing on the Polygon network.
- PostgreSQL or another suitable database for storing user and NFT data.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/nft-polygon-marketplace.git
Install dependencies:
cd nft-polygon-marketplace
npm install


Configuration
Create a .env file in the project root and configure it with your environment-specific variables. Here are some common variables you might need:
DATABASE_URL=postgres://username:password@localhost:5432/database_name
POLYGON_NETWORK_ENDPOINT=https://matic-mainnet.chainstacklabs.com/
POLYGON_MNEMONIC=your-mnemonic-phrase

Set up your database schema by running the migration scripts:
npm run db:migrate

Project Structure
contracts/: Smart contract code for the NFT marketplace.
pages/: Next.js pages for the frontend.
public/: Static assets and images.
scripts/: Scripts for deployment or other automation.
styles/: CSS or styling files.
test/: Test scripts and test data.
Smart Contracts
The heart of our NFT Polygon Marketplace is the Ethereum smart contract. It manages NFT creation, listing, purchasing, and reselling. You can find the smart contract code in the contracts/ directory.

Frontend
Our frontend is built using Next.js, a React framework. It provides a user-friendly interface for interacting with the marketplace. Here are some of the key frontend pages:

/ (Home): The main landing page where users can browse featured NFTs.
/dashboard: User dashboard for managing listings and transactions.
/create-nft: Create and mint new NFTs to list on the marketplace.
/my-nfts: View and manage the NFTs you own.
/resell-nft: List NFTs for resale or modify existing listings.
Usage
Access the marketplace through your web browser at http://localhost:3000.
Create an account or log in if you already have one.
Browse, list, and purchase NFTs on the marketplace.
Use the dashboard to manage your listings and transactions.
Contributing
We welcome contributions to our NFT Polygon Marketplace project! If you'd like to contribute, please follow the standard GitHub Fork and Pull Request workflow. Be sure to review the CONTRIBUTING.md for more details.

License
This project is licensed under the MIT License. See the LICENSE.md file for details.
