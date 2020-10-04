**[Polkadot JS API](../README.md)**

> [Globals](../globals.md) / "packages/api-derive/src/chain/subscribeNewHeads"

# Module: "packages/api-derive/src/chain/subscribeNewHeads"

## Index

### Functions

* [subscribeNewHeads](_packages_api_derive_src_chain_subscribenewheads_.md#subscribenewheads)

## Functions

### subscribeNewHeads

▸ **subscribeNewHeads**(`instanceId`: string, `api`: ApiInterfaceRx): function

*Defined in [packages/api-derive/src/chain/subscribeNewHeads.ts:25](https://github.com/polkadot-js/api/blob/d3703c072/packages/api-derive/src/chain/subscribeNewHeads.ts#L25)*

**`name`** subscribeNewHeads

**`description`** An observable of the current block header and it's author

**`example`** 
<BR>

```javascript
api.derive.chain.subscribeNewHeads((header) => {
  console.log(`block #${header.number} was authored by ${header.author}`);
});
```

#### Parameters:

Name | Type |
------ | ------ |
`instanceId` | string |
`api` | ApiInterfaceRx |

**Returns:** function

An array containing the block header and the block author
