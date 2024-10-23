# Polkadot Transaction Sender

This repository provides a simple Rust example for interacting with the Polkadot network using the [Substrate API Client](https://github.com/scs/substrate-api-client). It demonstrates how to sign and send transactions, specifically how to transfer funds between accounts.

## Features

- Connects to a Polkadot node via WebSocket.
- Signs and sends a transaction using test accounts (Alice -> Bob).
- Waits for the transaction to be included in a block.

## Prerequisites

To build and run this project, you'll need the following:

- **Rust**: Ensure you have the Rust toolchain installed. You can install it by following the instructions at [rustup.rs](https://rustup.rs).
- **WebSocket connection**: You will be connecting to the Polkadot node via WebSocket. Make sure you have access to the RPC endpoint (e.g., `wss://rpc.polkadot.io`).

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/polkadot-transaction-sender.git
   cd polkadot-transaction-sender
