---
slug: /sdk.editiondrop.claimto
title: EditionDrop.claimTo() method
hide_title: true
displayed_sidebar: typescript
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# EditionDrop.claimTo() method

Claim NFTs to a specific Wallet

## Example

```javascript
const address = "{{wallet_address}}"; // address of the wallet you want to claim the NFTs
const tokenId = 0; // the id of the NFT you want to claim
const quantity = 1; // how many NFTs you want to claim

const tx = await contract.claimTo(address, tokenId, quantity);
const receipt = tx.receipt; // the transaction receipt
```

**Signature:**

```typescript
claimTo(destinationAddress: string, tokenId: BigNumberish, quantity: BigNumberish, checkERC20Allowance?: boolean): Promise<TransactionResult>;
```

## Parameters

| Parameter           | Type         | Description                                                                                                                      |
| ------------------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| destinationAddress  | string       | Address you want to send the token to                                                                                            |
| tokenId             | BigNumberish | Id of the token you want to claim                                                                                                |
| quantity            | BigNumberish | Quantity of the tokens you want to claim                                                                                         |
| checkERC20Allowance | boolean      | <i>(Optional)</i> Optional, check if the wallet has enough ERC20 allowance to claim the tokens, and if not, approve the transfer |

**Returns:**

Promise&lt;[TransactionResult](./sdk.transactionresult.md)&gt;

- Receipt for the transaction

## Remarks

Let the specified wallet claim NFTs.
