**[Polkadot JS API](../README.md)**

> [Globals](../globals.md) / ["packages/api/src/types/storage"](../modules/_packages_api_src_types_storage_.md) / QueryableStorageMultiBase

# Interface: QueryableStorageMultiBase\<**ApiType**>

## Type parameters

Name | Type |
------ | ------ |
`ApiType` | [ApiTypes](../modules/_packages_api_src_types_base_.md#apitypes) |

## Hierarchy

* **QueryableStorageMultiBase**

## Callable

▸ \<T>(`calls`: [QueryableStorageMultiArg](../modules/_packages_api_src_types_storage_.md#queryablestoragemultiarg)\<ApiType>[]): Observable\<T>

*Defined in [packages/api/src/types/storage.ts:62](https://github.com/polkadot-js/api/blob/95c4f03bc/packages/api/src/types/storage.ts#L62)*

#### Type parameters:

Name | Type |
------ | ------ |
`T` | Codec[] |

#### Parameters:

Name | Type |
------ | ------ |
`calls` | [QueryableStorageMultiArg](../modules/_packages_api_src_types_storage_.md#queryablestoragemultiarg)\<ApiType>[] |

**Returns:** Observable\<T>
