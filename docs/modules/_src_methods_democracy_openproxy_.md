[@substrate/txwrapper](../README.md) › [Globals](../globals.md) › ["src/methods/democracy/openProxy"](_src_methods_democracy_openproxy_.md)

# Module: "src/methods/democracy/openProxy"

## Index

### Interfaces

* [DemocracyOpenProxyArgs](../interfaces/_src_methods_democracy_openproxy_.democracyopenproxyargs.md)

### Functions

* [openProxy](_src_methods_democracy_openproxy_.md#openproxy)

## Functions

###  openProxy

▸ **openProxy**(`args`: [DemocracyOpenProxyArgs](../interfaces/_src_methods_democracy_openproxy_.democracyopenproxyargs.md), `info`: [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md), `options?`: Partial‹[Options](../interfaces/_src_util_options_.options.md)›): *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*

*Defined in [src/methods/democracy/openProxy.ts:21](https://github.com/paritytech/txwrapper/blob/d1bfb8b/src/methods/democracy/openProxy.ts#L21)*

Become a proxy. This must be called prior to a later `activateProxy`.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`args` | [DemocracyOpenProxyArgs](../interfaces/_src_methods_democracy_openproxy_.democracyopenproxyargs.md) | - |
`info` | [BaseTxInfo](../interfaces/_src_util_types_.basetxinfo.md) | Information required to construct the transaction.  |
`options?` | Partial‹[Options](../interfaces/_src_util_options_.options.md)› | - |

**Returns:** *[UnsignedTransaction](../interfaces/_src_util_types_.unsignedtransaction.md)*