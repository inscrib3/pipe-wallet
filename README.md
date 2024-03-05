# XPIPE Protocol
The XPIPE Protocol expands what the PIPE protocol can do, opening the door for new things we can create.

We're starting with something called the XID indexer.

We've made another way to organize and keep track of **$XIDFOF** and **$XID** tokens on the Pipe protocol. It's like a special filing system just for these tokens.

Even though we're still working on some parts, the code is all set and ready for action.

With this code, you can easily organize and manage XID tokens.

## Token Details:

XIDFOF: There are 4.4 million of these tokens, all split up into 404 chunks.

XID: There are 21k of these tokens. You can find more details about them in `config/default.json`.

These tokens will be super useful for our upcoming plans.

## What's New?
**OP_RETURN XP S**: This lets us do special things related to staking.

**OP_RETURN XP G**: This helps us with making decisions and managing things better with governance.

## For Other Projects
Other projects can use this code too. They just need to tweak the `config/default.json` to fit their needs. It'll help them keep things organized and running smoothly. It will also allow you to use the same features we have.

## Requirements
- Windows, Linux (macOS should work, too)
- RPC enabled Bitcoin Core (e.g. QuickNode)[https://www.quicknode.com/] or fully indexed Bitcoin Core 24.0.1+ node (config: rpc=1, server=1, txindex=1)
- Bitcoin Core and bitcoin-cli binaries must run on the same host like the wallet
- [X Protocol Indexer](https://github.com/inscrib3/xpipe-protocol/archive/refs/heads/master.zip)
- Node >= 18.13.0 & NPM

## Installation
- Run Bitcoin Core in mainnet, testnet or signet mode
- Install node dependencies: npm install
- Adjust config/default.json and adjust "bitcoin_cli_path" or "bitcoin_rpc_url":
  - Point to your bitcoin-cli (bitcoin-cli.exe) or RPC URL
  - Full path required
  - Quote backslashes if you are using them on Windows
- (MongoDB)[https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/#procedure] installed
- (MongoDB Compass)[https://www.mongodb.com/try/download/compass] (optional for viewing data)
