**[Polkadot JS API](../README.md)**

> [Globals](../globals.md) / ["packages/metadata/src/Metadata/MetadataVersioned"](../modules/_packages_metadata_src_metadata_metadataversioned_.md) / MetadataVersioned

# Class: MetadataVersioned

**`name`** MetadataVersioned

**`description`** 
The versioned runtime metadata as a decoded structure

## Hierarchy

* Struct

  ↳ **MetadataVersioned**

  ↳↳ [Metadata](_packages_metadata_src_metadata_metadata_.metadata.md)

## Implements

* Codec

## Index

### Constructors

* [constructor](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#constructor)

### Properties

* [registry](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#registry)
* [size](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#size)

### Accessors

* [Type](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#type)
* [asCallsOnly](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#ascallsonly)
* [asLatest](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#aslatest)
* [asV10](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv10)
* [asV11](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv11)
* [asV12](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv12)
* [asV9](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv9)
* [defKeys](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#defkeys)
* [encodedLength](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#encodedlength)
* [hash](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#hash)
* [isEmpty](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#isempty)
* [magicNumber](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#magicnumber)
* [version](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#version)

### Methods

* [clear](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#clear)
* [delete](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#delete)
* [eq](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#eq)
* [forEach](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#foreach)
* [get](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#get)
* [getAtIndex](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#getatindex)
* [getUniqTypes](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#getuniqtypes)
* [has](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#has)
* [set](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#set)
* [toArray](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#toarray)
* [toHex](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tohex)
* [toHuman](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tohuman)
* [toJSON](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tojson)
* [toRawType](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#torawtype)
* [toString](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tostring)
* [toU8a](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tou8a)
* [typesToMap](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#typestomap)
* [with](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#with)

## Constructors

### constructor

\+ **new MetadataVersioned**(`registry`: Registry, `value?`: unknown): [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)

*Overrides void*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:27](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L27)*

#### Parameters:

Name | Type |
------ | ------ |
`registry` | Registry |
`value?` | unknown |

**Returns:** [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)

## Properties

### registry

• `Readonly` **registry**: Registry

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[registry](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#registry)*

*Defined in [packages/types/src/codec/Struct.ts:108](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L108)*

___

### size

• `Readonly` **size**: number

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[size](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#size)*

*Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:28*

## Accessors

### Type

• get **Type**(): object

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[Type](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#type)*

*Defined in [packages/types/src/codec/Struct.ts:171](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L171)*

**`description`** Returns the Type description to sthe structure

**Returns:** object

___

### asCallsOnly

• get **asCallsOnly**(): [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:60](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L60)*

**`description`** Returns the wrapped metadata as a limited calls-only (latest) version

**Returns:** [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)

___

### asLatest

• get **asLatest**(): MetadataLatest

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:100](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L100)*

**`description`** Returns the wrapped values as a latest version object

**Returns:** MetadataLatest

___

### asV10

• get **asV10**(): MetadataV10

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:79](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L79)*

**`description`** Returns the wrapped values as a V10 object

**Returns:** MetadataV10

___

### asV11

• get **asV11**(): MetadataV11

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:86](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L86)*

**`description`** Returns the wrapped values as a V10 object

**Returns:** MetadataV11

___

### asV12

• get **asV12**(): MetadataV11

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:93](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L93)*

**`description`** Returns the wrapped values as a V10 object

**Returns:** MetadataV11

___

### asV9

• get **asV9**(): MetadataV9

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:70](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L70)*

**`description`** Returns the wrapped metadata as a V1 object

**Returns:** MetadataV9

___

### defKeys

• get **defKeys**(): string[]

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[defKeys](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#defkeys)*

*Defined in [packages/types/src/codec/Struct.ts:149](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L149)*

**`description`** The available keys for this enum

**Returns:** string[]

___

### encodedLength

• get **encodedLength**(): number

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[encodedLength](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#encodedlength)*

*Defined in [packages/types/src/codec/Struct.ts:185](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L185)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** number

___

### hash

• get **hash**(): H256

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[hash](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#hash)*

*Defined in [packages/types/src/codec/Struct.ts:196](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L196)*

**`description`** returns a hash of the contents

**Returns:** H256

___

### isEmpty

• get **isEmpty**(): boolean

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[isEmpty](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#isempty)*

*Defined in [packages/types/src/codec/Struct.ts:156](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L156)*

**`description`** Checks if the value is an empty value

**Returns:** boolean

___

### magicNumber

• get **magicNumber**(): [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:108](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L108)*

**`description`** 

**Returns:** [MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)

___

### version

• get **version**(): number

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:122](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L122)*

**`description`** the metadata version this structure represents

**Returns:** number

## Methods

### clear

▸ **clear**(): void

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[clear](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#clear)*

*Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:22*

**Returns:** void

___

### delete

▸ **delete**(`key`: keyof TypesDef): boolean

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[delete](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#delete)*

*Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:23*

#### Parameters:

Name | Type |
------ | ------ |
`key` | keyof TypesDef |

**Returns:** boolean

___

### eq

▸ **eq**(`other?`: unknown): boolean

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[eq](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#eq)*

*Defined in [packages/types/src/codec/Struct.ts:203](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L203)*

**`description`** Compares the value of the input to see if there is a match

#### Parameters:

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** boolean

___

### forEach

▸ **forEach**(`callbackfn`: (value: Codec,key: keyof TypesDef,map: Map\<keyof TypesDef, Codec>) => void, `thisArg?`: any): void

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[forEach](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#foreach)*

*Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:24*

#### Parameters:

Name | Type |
------ | ------ |
`callbackfn` | (value: Codec,key: keyof TypesDef,map: Map\<keyof TypesDef, Codec>) => void |
`thisArg?` | any |

**Returns:** void

___

### get

▸ **get**(`name`: keyof TypesDef): Codec \| undefined

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[get](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#get)*

*Overrides void*

*Defined in [packages/types/src/codec/Struct.ts:211](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L211)*

**`description`** Returns a specific names entry in the structure

#### Parameters:

Name | Type | Description |
------ | ------ | ------ |
`name` | keyof TypesDef | The name of the entry to retrieve  |

**Returns:** Codec \| undefined

___

### getAtIndex

▸ **getAtIndex**(`index`: number): Codec

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[getAtIndex](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#getatindex)*

*Defined in [packages/types/src/codec/Struct.ts:218](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L218)*

**`description`** Returns the values of a member at a specific index (Rather use get(name) for performance)

#### Parameters:

Name | Type |
------ | ------ |
`index` | number |

**Returns:** Codec

___

### getUniqTypes

▸ **getUniqTypes**(`throwError`: boolean): string[]

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:126](https://github.com/polkadot-js/api/blob/014fa123b/packages/metadata/src/Metadata/MetadataVersioned.ts#L126)*

#### Parameters:

Name | Type |
------ | ------ |
`throwError` | boolean |

**Returns:** string[]

___

### has

▸ **has**(`key`: keyof TypesDef): boolean

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[has](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#has)*

*Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:26*

#### Parameters:

Name | Type |
------ | ------ |
`key` | keyof TypesDef |

**Returns:** boolean

___

### set

▸ **set**(`key`: keyof TypesDef, `value`: Codec): this

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[set](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#set)*

*Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:27*

#### Parameters:

Name | Type |
------ | ------ |
`key` | keyof TypesDef |
`value` | Codec |

**Returns:** this

___

### toArray

▸ **toArray**(): Codec[]

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toArray](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#toarray)*

*Defined in [packages/types/src/codec/Struct.ts:225](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L225)*

**`description`** Converts the Object to an standard JavaScript Array

**Returns:** Codec[]

___

### toHex

▸ **toHex**(): string

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toHex](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tohex)*

*Defined in [packages/types/src/codec/Struct.ts:232](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L232)*

**`description`** Returns a hex string representation of the value

**Returns:** string

___

### toHuman

▸ **toHuman**(`isExtended?`: undefined \| false \| true): AnyJson

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toHuman](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tohuman)*

*Defined in [packages/types/src/codec/Struct.ts:239](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L239)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

#### Parameters:

Name | Type |
------ | ------ |
`isExtended?` | undefined \| false \| true |

**Returns:** AnyJson

___

### toJSON

▸ **toJSON**(): AnyJson

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toJSON](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tojson)*

*Defined in [packages/types/src/codec/Struct.ts:252](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L252)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** AnyJson

___

### toRawType

▸ **toRawType**(): string

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toRawType](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#torawtype)*

*Defined in [packages/types/src/codec/Struct.ts:276](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L276)*

**`description`** Returns the base runtime type name for this instance

**Returns:** string

___

### toString

▸ **toString**(): string

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toString](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tostring)*

*Defined in [packages/types/src/codec/Struct.ts:285](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L285)*

**`description`** Returns the string representation of the value

**Returns:** string

___

### toU8a

▸ **toU8a**(`isBare?`: BareOpts): Uint8Array

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toU8a](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tou8a)*

*Defined in [packages/types/src/codec/Struct.ts:293](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L293)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

#### Parameters:

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | BareOpts | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** Uint8Array

___

### typesToMap

▸ `Static`**typesToMap**(`registry`: Registry, `Types`: Record\<string, Constructor>): Record\<string, string>

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[typesToMap](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#typestomap)*

*Defined in [packages/types/src/codec/Struct.ts:265](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L265)*

#### Parameters:

Name | Type |
------ | ------ |
`registry` | Registry |
`Types` | Record\<string, Constructor> |

**Returns:** Record\<string, string>

___

### with

▸ `Static`**with**\<S>(`Types`: S, `jsonMap?`: Map\<keyof S, string>): Constructor\<Struct\<S>>

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[with](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#with)*

*Defined in [packages/types/src/codec/Struct.ts:125](https://github.com/polkadot-js/api/blob/014fa123b/packages/types/src/codec/Struct.ts#L125)*

#### Type parameters:

Name | Type |
------ | ------ |
`S` | TypesDef |

#### Parameters:

Name | Type |
------ | ------ |
`Types` | S |
`jsonMap?` | Map\<keyof S, string> |

**Returns:** Constructor\<Struct\<S>>
