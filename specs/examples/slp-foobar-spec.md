![Simple Ledger Protocol](../../images/SLP-logo-solid-200.png)

## FooBar Protocol Spec

| Properties           | Value            |
| -------------------- | ---------------- |
| Protocol Name        | FooBar           |
| Specification Status | Provisional      |
| Date First Drafted   | mm/dd/yyyy       |
| Date Last Updated    | mm/dd/yyyy       |
| D-App Identifier     | DAPP:FOOBAR-PROV |
| Implementations      | None             |

## Purpose

FooBar provides a trustless way to do Foo and Bar using SLP tokens.  The FooBar d-app works with any SLP token id that follows the specification requirements provided herein.



## Requirements

### <u>General Description of Usage</u> 

Using a FooBar d-app involves creating your own NFT Group token FooBar token and using the NFT children to track the status of Foo and Bar.

### <u>Transactions</u>

#### Genesis

* **NFT Group**
  * <u>Token Type</u>: 0x81 (Must be NFT Group)
  * <u>Name</u>: Any value by token creator
  * <u>Ticker</u>: D-App Identifier
  * <u>Document URI</u>: Location of the token document following token document d-app specification
  * <u>Document Hash</u>: sha256 hash value of the token document
* **NFT Children**
  * <u>Token Type</u>: 0x41 (Must be NFT Child)
  * <u>Name</u>: Any value by FooBar NFT token creator
  * <u>Ticker</u>: D-App Identifier
  * <u>Document URI</u>: Location of FooBar NFT characteristics
  * <u>Document Hash</u>: Specific to FooBar NFT characteristics

#### Minting

FooBar Group token minting is governed by a custom mint baton emission script with an initial redeem script template provided below.  Alternatively, FooBar NFT Group minting can be performed at the discretion of FooBar Group creator the current holder of the token.

#### Send

There are no special restrictions or requirements for sending transactions.

### <u>Actions</u>

Anyone holding a Foo token can reliably go to a Bar by holding the token in a SLP wallet.



## Change Log

* mm/dd/yyyy - Addressed Provisional peer-review comments by xyz.
* mm/dd/yyyy - initial draft

