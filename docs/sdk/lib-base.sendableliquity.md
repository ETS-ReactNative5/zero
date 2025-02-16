<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [SendableLiquity](./lib-base.sendableliquity.md)

## SendableLiquity interface

Send Liquity transactions.

<b>Signature:</b>

```typescript
export interface SendableLiquity<R = unknown, S = unknown> extends _SendableFrom<TransactableLiquity, R, S> 
```
<b>Extends:</b> \_SendableFrom&lt;[TransactableLiquity](./lib-base.transactableliquity.md)<!-- -->, R, S&gt;

## Remarks

The functions return an object implementing [SentLiquityTransaction](./lib-base.sentliquitytransaction.md)<!-- -->, which can be used to monitor the transaction and get its details when it succeeds.

Implemented by [SendableEthersLiquity](./lib-ethers.sendableethersliquity.md)<!-- -->.

## Methods

|  Method | Description |
|  --- | --- |
|  [adjustTrove(params, maxBorrowingRate)](./lib-base.sendableliquity.adjusttrove.md) | Adjust existing Trove by changing its collateral, debt, or both. |
|  [borrowZUSD(amount, maxBorrowingRate)](./lib-base.sendableliquity.borrowzusd.md) | Adjust existing Trove by borrowing more ZUSD. |
|  [claimCollateralSurplus()](./lib-base.sendableliquity.claimcollateralsurplus.md) | Claim leftover collateral after a liquidation or redemption. |
|  [closeTrove()](./lib-base.sendableliquity.closetrove.md) | Close existing Trove by repaying all debt and withdrawing all collateral. |
|  [depositCollateral(amount)](./lib-base.sendableliquity.depositcollateral.md) | Adjust existing Trove by depositing more collateral. |
|  [depositZUSDInStabilityPool(amount, frontendTag)](./lib-base.sendableliquity.depositzusdinstabilitypool.md) | Make a new Stability Deposit, or top up existing one. |
|  [liquidate(address)](./lib-base.sendableliquity.liquidate.md) | Liquidate one or more undercollateralized Troves. |
|  [liquidateUpTo(maximumNumberOfTrovesToLiquidate)](./lib-base.sendableliquity.liquidateupto.md) | Liquidate the least collateralized Troves up to a maximum number. |
|  [openTrove(params, maxBorrowingRate)](./lib-base.sendableliquity.opentrove.md) | Open a new Trove by depositing collateral and borrowing ZUSD. |
|  [redeemZUSD(amount, maxRedemptionRate)](./lib-base.sendableliquity.redeemzusd.md) | Redeem ZUSD to native currency (e.g. Ether) at face value. |
|  [registerFrontend(kickbackRate)](./lib-base.sendableliquity.registerfrontend.md) | Register current wallet address as a Liquity frontend. |
|  [repayZUSD(amount)](./lib-base.sendableliquity.repayzusd.md) | Adjust existing Trove by repaying some of its debt. |
|  [sendZERO(toAddress, amount)](./lib-base.sendableliquity.sendzero.md) | Send ZERO tokens to an address. |
|  [sendZUSD(toAddress, amount)](./lib-base.sendableliquity.sendzusd.md) | Send ZUSD tokens to an address. |
|  [stakeZERO(amount)](./lib-base.sendableliquity.stakezero.md) | Stake ZERO to start earning fee revenue or increase existing stake. |
|  [transferCollateralGainToTrove()](./lib-base.sendableliquity.transfercollateralgaintotrove.md) | Transfer [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) from Stability Deposit to Trove. |
|  [unstakeZERO(amount)](./lib-base.sendableliquity.unstakezero.md) | Withdraw ZERO from staking. |
|  [withdrawCollateral(amount)](./lib-base.sendableliquity.withdrawcollateral.md) | Adjust existing Trove by withdrawing some of its collateral. |
|  [withdrawGainsFromStabilityPool()](./lib-base.sendableliquity.withdrawgainsfromstabilitypool.md) | Withdraw [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) and [ZERO reward](./lib-base.stabilitydeposit.zeroreward.md) from Stability Deposit. |
|  [withdrawGainsFromStaking()](./lib-base.sendableliquity.withdrawgainsfromstaking.md) | Withdraw [collateral gain](./lib-base.zerostake.collateralgain.md) and [ZUSD gain](./lib-base.zerostake.zusdgain.md) from ZERO stake. |
|  [withdrawZUSDFromStabilityPool(amount)](./lib-base.sendableliquity.withdrawzusdfromstabilitypool.md) | Withdraw ZUSD from Stability Deposit. |

