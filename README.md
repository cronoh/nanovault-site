# NanoVault

NanoVault is a fully client-side signing wallet for sending and receiving [Nano](https://github.com/nanocurrency/raiblocks) 
on your [desktop](https://github.com/cronoh/nanovault/releases) or [in your browser](https://nanovault.io)

![NanoVault Screenshot](https://s3-us-west-2.amazonaws.com/nanovault.io/NanoVault-Preview.png)

# What is NanoVault?

NanoVault is an open source wallet application for interacting with [Nano](https://github.com/nanocurrency/raiblocks), which makes it dead-simple to use, and as secure as possible.  It is fully client side which means your seed and private keys are generated in your browser and transactions are signed locally.  None of your  wallet data is ever stored on any server in any format (Encrypted or otherwise), so there is no need for server-based authentication measures such as 2FA.

## How does it work?

NanoVault performs the standard hashing operations called for by the Nano protocol in your browser using Javascript, and then uses the publically-safe output of that to send to our hosted Nano nodes to perform transactions and receive updates from the network.


## How is data stored?

By default, your wallet data is stored in your browsers local storage, encrypted by the password you set on your wallet (If desired, you can change the application settings to never store any wallet data). Other data related to the application, such as your settings and address book are also stored in your local storage.  They can be cleared completely using the application settings page if needed.

**No data at all is ever stored on a server, and only public Nano network transaction information is ever sent across the network.**

# NanoVault Guide

Use the guide below to figure out in detail how to use any piece of the application.

- Create/Import Wallet
- Your Accounts
- Sending A Transaction
- Receiving A Transaction
- The Address Book
- Configuring Your Wallet
- Configuring NanoVault
