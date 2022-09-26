---
slug: /solana.userwallet.getsigner
title: UserWallet.getSigner() method
hide_title: true
displayed_sidebar: solana
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## UserWallet.getSigner() method

Get the connected signer

**Signature:**

```typescript
getSigner(): import("@metaplex-foundation/js/dist/types/plugins/identityModule").IdentityClient;
```

**Returns:**

import("@metaplex-foundation/js/dist/types/plugins/identityModule").IdentityClient

the signer

## Example

```jsx
const signer = sdk.wallet.getSigner();
```