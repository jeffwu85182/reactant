[reactant-di](../README.md) › [Globals](../globals.md) › ["util"](_util_.md)

# External module: "util"

## Index

### Functions

* [getMetadata](_util_.md#const-getmetadata)
* [setMetadata](_util_.md#const-setmetadata)

## Functions

### `Const` getMetadata

▸ **getMetadata**(`metaKey`: [MetaDataKey](_interfaces_.md#metadatakey)): *[MetadataMap](_interfaces_.md#metadatamap)*

*Defined in [packages/reactant-di/src/util.ts:8](https://github.com/unadlib/reactant/blob/222a645/packages/reactant-di/src/util.ts#L8)*

**Parameters:**

Name | Type |
------ | ------ |
`metaKey` | [MetaDataKey](_interfaces_.md#metadatakey) |

**Returns:** *[MetadataMap](_interfaces_.md#metadatamap)*

___

### `Const` setMetadata

▸ **setMetadata**(`metaKey`: [MetaDataKey](_interfaces_.md#metadatakey), `target`: [Module](../interfaces/_interfaces_.module.md)‹any›, `serviceIdentifier`: [ServiceIdentifier](_interfaces_.md#serviceidentifier)‹any›): *void*

*Defined in [packages/reactant-di/src/util.ts:11](https://github.com/unadlib/reactant/blob/222a645/packages/reactant-di/src/util.ts#L11)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`metaKey` | [MetaDataKey](_interfaces_.md#metadatakey) | - |
`target` | [Module](../interfaces/_interfaces_.module.md)‹any› | - |
`serviceIdentifier` | [ServiceIdentifier](_interfaces_.md#serviceidentifier)‹any› | target |

**Returns:** *void*
