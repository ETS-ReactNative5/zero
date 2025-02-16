<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [TransactableLiquity](./lib-base.transactableliquity.md)

## TransactableLiquity interface

Send Liquity transactions and wait for them to succeed.

<b>Signature:</b>

```typescript
export interface TransactableLiquity 
```

## Remarks

The functions return the details of the transaction (if any), or throw an implementation-specific subclass of [TransactionFailedError](./lib-base.transactionfailederror.md) in case of transaction failure.

Implemented by [EthersLiquity](./lib-ethers.ethersliquity.md)<!-- -->.

## Methods

|  Method | Description |
|  --- | --- |
|  [adjustTrove(params, maxBorrowingRate)](./lib-base.transactableliquity.adjusttrove.md) | Adjust existing Trove by changing its collateral, debt, or both. |
|  [borrowZUSD(amount, maxBorrowingRate)](./lib-base.transactableliquity.borrowzusd.md) | Adjust existing Trove by borrowing more ZUSD. |
|  [claimCollateralSurplus()](./lib-base.transactableliquity.claimcollateralsurplus.md) | Claim leftover collateral after a liquidation or redemption. |
|  [closeTrove()](./lib-base.transactableliquity.closetrove.md) | Close existing Trove by repaying all debt and withdrawing all collateral. |
|  [depositCollateral(amount)](./lib-base.transactableliquity.depositcollateral.md) | Adjust existing Trove by depositing more collateral. |
|  [depositZUSDInStabilityPool(amount, frontendTag)](./lib-base.transactableliquity.depositzusdinstabilitypool.md) | Make a new Stability Deposit, or top up existing one. |
|  [liquidate(address)](./lib-base.transactableliquity.liquidate.md) | Liquidate one or more undercollateralized Troves. |
|  [liquidateUpTo(maximumNumberOfTrovesToLiquidate)](./lib-base.transactableliquity.liquidateupto.md) | Liquidate the least collateralized Troves up to a maximum number. |
|  [openTrove(params, maxBorrowingRate)](./lib-base.transactableliquity.opentrove.md) | Open a new Trove by depositing collateral and borrowing ZUSD. |
|  [redeemZUSD(amount, maxRedemptionRate)](./lib-base.transactableliquity.redeemzusd.md) | Redeem ZUSD to native currency (e.g. Ether) at face value. |
|  [registerFrontend(kickbackRate)](./lib-base.transactableliquity.registerfrontend.md) | Register current wallet address as a Liquity frontend. |
|  [repayZUSD(amount)](./lib-base.transactableliquity.repayzusd.md) | Adjust existing Trove by repaying some of its debt. |
|  [sendZERO(toAddress, amount)](./lib-base.transactableliquity.sendzero.md) | Send ZERO tokens to an address. |
|  [sendZUSD(toAddress, amount)](./lib-base.transactableliquity.sendzusd.md) | Send ZUSD tokens to an address. |
|  [stakeZERO(amount)](./lib-base.transactableliquity.stakezero.md) | Stake ZERO to start earning fee revenue or increase existing stake. |
|  [transferCollateralGainToTrove()](./lib-base.transactableliquity.transfercollateralgaintotrove.md) | Transfer [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) from Stability Deposit to Trove. |
|  [unstakeZERO(amount)](./lib-base.transactableliquity.unstakezero.md) | Withdraw ZERO from staking. |
|  [withdrawCollateral(amount)](./lib-base.transactableliquity.withdrawcollateral.md) | Adjust existing Trove by withdrawing some of its collateral. |
|  [withdrawGainsFromStabilityPool()](./lib-base.transactableliquity.withdrawgainsfromstabilitypool.md) | Withdraw [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) and [ZERO reward](./lib-base.stabilitydeposit.zeroreward.md) from Stability Deposit. |
|  [withdrawGainsFromStaking()](./lib-base.transactableliquity.withdrawgainsfromstaking.md) | Withdraw [collateral gain](./lib-base.zerostake.collateralgain.md) and [ZUSD gain](./lib-base.zerostake.zusdgain.md) from ZERO stake. |
|  [withdrawZUSDFromStabilityPool(amount)](./lib-base.transactableliquity.withdrawzusdfromstabilitypool.md) | Withdraw ZUSD from Stability Deposit. |

