# Solana Smart Contract (Program) in Rust 🚀

This project contains a simple smart contract (also known as a *program*) built on the [Solana blockchain](https://solana.com/) using the [Rust programming language](https://www.rust-lang.org/).

## 📌 Overview

This is a beginner-friendly project created to understand the fundamentals of Solana smart contract development using Rust. It includes:

- Writing a basic smart contract in Rust
- Compiling and deploying the contract to the local Solana cluster
- Interacting with the contract using the Solana CLI or a client script

## 📦 Tech Stack

- **Blockchain**: Solana
- **Language**: Rust
- **Tools**: Solana CLI, Anchor (optional), Cargo
- **Local Testing**: Solana Test Validator

## 🛠️ Prerequisites

Make sure you have the following installed:

- [Rust](https://www.rust-lang.org/tools/install)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Node.js & npm](https://nodejs.org/) (if using Anchor or frontend tools)
- [Anchor Framework](https://www.anchor-lang.com/docs/installation) *(optional)*

## 📁 Project Structure

simple-solana-smart-contract/ ├── programs/ │ └── my_contract/ # Main smart contract code (Rust) │ └── src/lib.rs # Rust entry point ├── tests/ # Integration tests ├── target/ # Build output ├── Anchor.toml # Anchor config (if using Anchor) ├── Cargo.toml # Rust dependencies └── README.md # Project documentation
