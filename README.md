# Candy Machine User Interface Configuration Guide

## Introduction
This guide offers a detailed walkthrough for setting up the user interface (UI) of your Candy Machine. The UI is designed to streamline the NFT minting process using the SPL token you've generated. Users can leverage their Phantom wallets for the minting procedure.

## Prerequisites
Make sure you have the following prerequisites in place before proceeding:

- A configured Candy Machine with specific details outlined in its config.json file, including price, quantity, symbol, seller fee basis points, SPL token account, SPL token, go-live date, and creator details.
- A designated Phantom wallet for minting.
- A newly created SPL token.

## Steps

### 1. SPL Token Configuration
If not already done, follow Lesson Three guidelines to create the SPL token and note down its address.

### 2. Update Candy Machine Config
Edit the config.json file of your Candy Machine and update the following fields:

- `splTokenAccount`: Replace it with the address of the created SPL token account.
- `splToken`: Replace it with the SPL token address.

### 3. UI Customization
Consult the "Quick Node: Set Up a Minting Site" tutorial for instructions on creating a UI for your Candy Machine. This UI empowers users to connect their Phantom wallets and mint NFTs using the SPL token as payment.

### 4. Adapt Minting Logic
Within your SPL project's minting logic (as per Lesson Three), make necessary adjustments to mint NFTs to the Phantom wallet address or modify the transfer function to deliver minted NFTs to your Phantom wallet.

### 5. Testing
Thoroughly test the entire setup by transferring or minting your SPL token to a Phantom account. Use the UI to mint NFTs, ensuring a seamless process for users paying with the designated SPL token.
