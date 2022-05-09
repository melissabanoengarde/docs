---
slug: /IPlatformFee
title: IPlatformFee
hide_title: true
---

# IPlatformFee

## Methods

### getPlatformFeeInfo

```solidity
function getPlatformFeeInfo() external view returns (address, uint16)
```

_Returns the platform fee bps and recipient._

#### Returns

| Name | Type    | Description |
| ---- | ------- | ----------- |
| \_0  | address | undefined   |
| \_1  | uint16  | undefined   |

### setPlatformFeeInfo

```solidity
function setPlatformFeeInfo(address _platformFeeRecipient, uint256 _platformFeeBps) external nonpayable
```

_Lets a module admin update the fees on primary sales._

#### Parameters

| Name                   | Type    | Description |
| ---------------------- | ------- | ----------- |
| \_platformFeeRecipient | address | undefined   |
| \_platformFeeBps       | uint256 | undefined   |

## Events

### PlatformFeeInfoUpdated

```solidity
event PlatformFeeInfoUpdated(address platformFeeRecipient, uint256 platformFeeBps)
```

_Emitted when fee on primary sales is updated._

#### Parameters

| Name                 | Type    | Description |
| -------------------- | ------- | ----------- |
| platformFeeRecipient | address | undefined   |
| platformFeeBps       | uint256 | undefined   |