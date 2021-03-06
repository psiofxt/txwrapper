[@substrate/txwrapper](../README.md) › [Globals](../globals.md) › ["src/methods/democracy/vote"](_src_methods_democracy_vote_.md)

# Module: "src/methods/democracy/vote"

## Index

### Interfaces

* [DemocracyVoteArgs](../interfaces/_src_methods_democracy_vote_.democracyvoteargs.md)

### Functions

* [vote](_src_methods_democracy_vote_.md#vote)

## Functions

###  vote

▸ **vote**(`args`: [DemocracyVoteArgs](../interfaces/_src_methods_democracy_vote_.democracyvoteargs.md), `info`: [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md), `options`: [OptionsWithMeta](../interfaces/_src_util_types_.optionswithmeta.md)): *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*

*Defined in [src/methods/democracy/vote.ts:28](https://github.com/paritytech/txwrapper/blob/2e195b6/src/methods/democracy/vote.ts#L28)*

Vote in a referendum.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`args` | [DemocracyVoteArgs](../interfaces/_src_methods_democracy_vote_.democracyvoteargs.md) | Arguments specific to this method. |
`info` | [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md) | Information required to construct the transaction. |
`options` | [OptionsWithMeta](../interfaces/_src_util_types_.optionswithmeta.md) | Registry and metadata used for constructing the method.  |

**Returns:** *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*
