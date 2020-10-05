**[Polkadot JS API](../README.md)**

> [Globals](../globals.md) / "packages/types/src/create/createType"

# Module: "packages/types/src/create/createType"

## Index

### Functions

* [createType](_packages_types_src_create_createtype_.md#createtype)
* [createTypeUnsafe](_packages_types_src_create_createtype_.md#createtypeunsafe)

## Functions

### createType

▸ **createType**\<K>(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `type`: K, ...`params`: any[]): InterfaceTypes[K]

*Defined in [packages/types/src/create/createType.ts:76](https://github.com/polkadot-js/api/blob/acb565d46/packages/types/src/create/createType.ts#L76)*

Create an instance of a `type` with a given `params`.

#### Type parameters:

Name | Type |
------ | ------ |
`K` | keyof [InterfaceTypes](../interfaces/_packages_types_src_types_registry_.interfacetypes.md) |

#### Parameters:

Name | Type | Description |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) | - |
`type` | K | A recognizable string representing the type to create an instance from |
`...params` | any[] | The value to instantiate the type with  |

**Returns:** InterfaceTypes[K]

___

### createTypeUnsafe

▸ **createTypeUnsafe**\<T, K>(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `type`: K, `params`: any[], `isPedantic?`: undefined \| false \| true): T

*Defined in [packages/types/src/create/createType.ts:60](https://github.com/polkadot-js/api/blob/acb565d46/packages/types/src/create/createType.ts#L60)*

#### Type parameters:

Name | Type | Default |
------ | ------ | ------ |
`T` | [Codec](../interfaces/_packages_types_src_types_codec_.codec.md) | Codec |
`K` | string | string |

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) | - |
`type` | K | - |
`params` | any[] | [] |
`isPedantic?` | undefined \| false \| true | - |

**Returns:** T
