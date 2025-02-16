<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [PopulatableEthersLiquity](./lib-ethers.populatableethersliquity.md) &gt; [unstakeZERO](./lib-ethers.populatableethersliquity.unstakezero.md)

## PopulatableEthersLiquity.unstakeZERO() method

Withdraw ZERO from staking.

<b>Signature:</b>

```typescript
unstakeZERO(amount: Decimalish, overrides?: EthersTransactionOverrides): Promise<PopulatedEthersLiquityTransaction<void>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  amount | [Decimalish](./lib-base.decimalish.md) | Amount of ZERO to withdraw. |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;[PopulatedEthersLiquityTransaction](./lib-ethers.populatedethersliquitytransaction.md)<!-- -->&lt;void&gt;&gt;

## Remarks

As a side-effect, the transaction will also pay out the ZERO stake's [collateral gain](./lib-base.zerostake.collateralgain.md) and [ZUSD gain](./lib-base.zerostake.zusdgain.md)<!-- -->.

