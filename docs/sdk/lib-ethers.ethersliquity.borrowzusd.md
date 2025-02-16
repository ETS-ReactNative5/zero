<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [EthersLiquity](./lib-ethers.ethersliquity.md) &gt; [borrowZUSD](./lib-ethers.ethersliquity.borrowzusd.md)

## EthersLiquity.borrowZUSD() method

Adjust existing Trove by borrowing more ZUSD.

<b>Signature:</b>

```typescript
borrowZUSD(amount: Decimalish, maxBorrowingRate?: Decimalish, overrides?: EthersTransactionOverrides): Promise<TroveAdjustmentDetails>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./lib-base.decimalish.md) | The amount of ZUSD to borrow. |
|  maxBorrowingRate | [Decimalish](./lib-base.decimalish.md) | Maximum acceptable [borrowing rate](./lib-base.fees.borrowingrate.md)<!-- -->. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[TroveAdjustmentDetails](./lib-base.troveadjustmentdetails.md)<!-- -->&gt;

## Exceptions

Throws [EthersTransactionFailedError](./lib-ethers.etherstransactionfailederror.md) in case of transaction failure.

## Remarks

Equivalent to:

```typescript
adjustTrove({ borrowZUSD: amount }, maxBorrowingRate)

```

