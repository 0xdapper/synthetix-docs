# IFuturesMarketManager

## Description

**Source:** [contracts/interfaces/IFuturesMarketManager.sol](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol)

## Views

### `allMarkets`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol#L8)</sub>

??? example "Details"

    **Signature**

    `allMarkets() view returns (address[])`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `marketForKey`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol#L10)</sub>

??? example "Details"

    **Signature**

    `marketForKey(bytes32 marketKey) view returns (address)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `markets`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol#L4)</sub>

??? example "Details"

    **Signature**

    `markets(uint256 index, uint256 pageSize) view returns (address[])`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `marketsForKeys`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol#L12)</sub>

??? example "Details"

    **Signature**

    `marketsForKeys(bytes32[] marketKeys) view returns (address[])`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `numMarkets`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol#L6)</sub>

??? example "Details"

    **Signature**

    `numMarkets() view returns (uint256)`

    **Visibility**

    `external`

    **State Mutability**

    `view`

### `totalDebt`

<sub>[Source](https://github.com/Synthetixio/synthetix/tree/v2.74.1/contracts/interfaces/IFuturesMarketManager.sol#L14)</sub>

??? example "Details"

    **Signature**

    `totalDebt() view returns (uint256 debt, bool isInvalid)`

    **Visibility**

    `external`

    **State Mutability**

    `view`
