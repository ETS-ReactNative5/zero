<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [SendableLiquity](./lib-base.sendableliquity.md) &gt; [stakeZERO](./lib-base.sendableliquity.stakezero.md)

## SendableLiquity.stakeZERO() method

Stake ZERO to start earning fee revenue or increase existing stake.

<b>Signature:</b>

```typescript
stakeZERO(amount: Decimalish): Promise<SentLiquityTransaction<S, LiquityReceipt<R, void>>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./lib-base.decimalish.md) | Amount of ZERO to add to new or existing stake. |

<b>Returns:</b>

Promise&lt;[SentLiquityTransaction](./lib-base.sentliquitytransaction.md)<!-- -->&lt;S, [LiquityReceipt](./lib-base.liquityreceipt.md)<!-- -->&lt;R, void&gt;&gt;&gt;

## Remarks

As a side-effect, the transaction will also pay out an existing ZERO stake's [collateral gain](./lib-base.zerostake.collateralgain.md) and [ZUSD gain](./lib-base.zerostake.zusdgain.md)<!-- -->.

