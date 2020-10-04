**[Polkadot JS API](../README.md)**

> [Globals](../globals.md) / "packages/api-derive/src/accounts/indexToId"

# Module: "packages/api-derive/src/accounts/indexToId"

## Index

### Functions

* [indexToId](_packages_api_derive_src_accounts_indextoid_.md#indextoid)

## Functions

### indexToId

▸ **indexToId**(`instanceId`: string, `api`: ApiInterfaceRx): function

*Defined in [packages/api-derive/src/accounts/indexToId.ts:51](https://github.com/polkadot-js/api/blob/d3703c072/packages/api-derive/src/accounts/indexToId.ts#L51)*

**`name`** indexToId

**`example`** 
<BR>

```javascript
api.derive.accounts.indexToId('F7Hs', (accountId) => {
  console.log(`The AccountId of F7Hs is ${accountId}`);
});
```

#### Parameters:

Name | Type |
------ | ------ |
`instanceId` | string |
`api` | ApiInterfaceRx |

**Returns:** function

Returns the corresponding AccountId.
