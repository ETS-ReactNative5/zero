<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [StabilityDeposit](./lib-base.stabilitydeposit.md)

## StabilityDeposit class

A Stability Deposit and its accrued gains.

<b>Signature:</b>

```typescript
export declare class StabilityDeposit 
```

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `StabilityDeposit` class.

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [collateralGain](./lib-base.stabilitydeposit.collateralgain.md) |  | [Decimal](./lib-base.decimal.md) | Amount of native currency (e.g. Ether) received in exchange for the used-up ZUSD. |
|  [currentZUSD](./lib-base.stabilitydeposit.currentzusd.md) |  | [Decimal](./lib-base.decimal.md) | Amount of ZUSD left in the Stability Deposit. |
|  [frontendTag](./lib-base.stabilitydeposit.frontendtag.md) |  | string | Address of frontend through which this Stability Deposit was made. |
|  [initialZUSD](./lib-base.stabilitydeposit.initialzusd.md) |  | [Decimal](./lib-base.decimal.md) | Amount of ZUSD in the Stability Deposit at the time of the last direct modification. |
|  [isEmpty](./lib-base.stabilitydeposit.isempty.md) |  | boolean |  |
|  [zeroReward](./lib-base.stabilitydeposit.zeroreward.md) |  | [Decimal](./lib-base.decimal.md) | Amount of ZERO rewarded since the last modification of the Stability Deposit. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [apply(change)](./lib-base.stabilitydeposit.apply.md) |  | Apply a [StabilityDepositChange](./lib-base.stabilitydepositchange.md) to this Stability Deposit. |
|  [equals(that)](./lib-base.stabilitydeposit.equals.md) |  | Compare to another instance of <code>StabilityDeposit</code>. |
|  [whatChanged(thatZUSD)](./lib-base.stabilitydeposit.whatchanged.md) |  | Calculate the difference between the <code>currentZUSD</code> in this Stability Deposit and <code>thatZUSD</code>. |

