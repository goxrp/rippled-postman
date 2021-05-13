# Rippled Postman Collection

This package provides a Postman Collection to be used with the `rippled` XRP Ledger server.

## API Support

- [ ] Public rippled Methods
  - [ ] Account Methods
    - [x] `account_channels` - Get a list of payment channels where the account is the source of the channel.
    - [x] `account_currencies` - Get a list of currencies an account can send or receive.
    - [x] `account_info` - Get basic data about an account.
    - [x] `account_lines` - Get info about an account's trust lines.
    - [ ] `account_objects` - Get all ledger objects owned by an account.
    - [x] `account_offers` - Get info about an account's currency exchange offers.
    - [x] `account_tx` - Get info about an account's transactions.
    - [x] `gateway_balances` - Calculate total amounts issued by an account.
    - [x] `noripple_check` - Get recommended changes to an account's Default Ripple and No Ripple settings.
  - [ ] Ledger Methods
    - [x] `ledger` - Get info about a ledger version.
    - [x] `ledger_closed` - Get the latest closed ledger version.
    - [x] `ledger_current` - Get the current working ledger version.
    - [x] `ledger_data` - Get the raw contents of a ledger version.
    - [ ] `ledger_entry` - Get one element from a ledger version.
  - [ ] Transaction Methods
    - [ ] `sign` - Cryptographically sign a transaction.
    - [ ] `sign_for` - Contribute to a multi-signature.
    - [ ] `submit` - Send a transaction to the network.
    - [ ] `submit_multisigned` - Send a multi-signed transaction to the network.
    - [ ] `transaction_entry` - Retrieve info about a transaction from a particular ledger version.
    - [ ] `tx` - Retrieve info about a transaction from all the ledgers on hand.
    - [ ] `tx_history` - Retrieve info about all recent transactions.
  - [x] Path and Order Book Methods
    - [x] `book_offers` - Get info about offers to exchange two currencies.
    - [x] `deposit_authorized` - Check whether an account is authorized to send money directly to another.
    - [ ] ~`path_find` - Find a path for a payment between two accounts and receive updates. (websocket only)~
    - [x] `ripple_path_find` - Find a path for payment between two accounts, once.
  - [ ] Payment Channel Methods
    - [ ] `channel_authorize` - Sign a claim for money from a payment channel.
    - [ ] `channel_verify` - Check a payment channel claim's signature.
  - [x] Server Info Methods
    - [x] `fee` - Get information about transaction cost.
    - [x] `manifest` - Look up the public information about a known validator.
    - [x] `server_info` - Retrieve status of the server in human-readable format.
    - [x] `server_state` - Retrieve status of the server in machine-readable format.
  - [x] utility Methods
    - [ ] ~`json` - Pass JSON through the commandline.~ (commandline only)
	- [x] `ping` - Confirm connectivity with the server.
    - [x] `random` - Generate a random number.