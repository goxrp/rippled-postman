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