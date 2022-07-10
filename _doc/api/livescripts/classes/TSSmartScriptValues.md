---
title: TSSmartScriptValues
---


## Methods

{: .api-section }
### GetActionArgument1

{: .code-example }
`GetActionArgument1(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetActionArgument2

{: .code-example }
`GetActionArgument2(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetActionArgument3

{: .code-example }
`GetActionArgument3(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetActionArgument4

{: .code-example }
`GetActionArgument4(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetActionArgument5

{: .code-example }
`GetActionArgument5(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetActionArgument6

{: .code-example }
`GetActionArgument6(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetBoolArg

{: .code-example }
`GetBoolArg(): boolean`

**Returns:** 
`boolean`

___

{: .api-section }
### GetCounterValue

{: .code-example }
`GetCounterValue(id): uint32`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `id` | `uint32` |

**Returns:** 
`uint32`

___

{: .api-section }
### GetEntryOrGUID

{: .code-example }
`GetEntryOrGUID(): int32`

**Returns:** 
`int32`

___

{: .api-section }
### GetEventArgument1

{: .code-example }
`GetEventArgument1(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventArgument2

{: .code-example }
`GetEventArgument2(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventArgument3

{: .code-example }
`GetEventArgument3(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventArgument4

{: .code-example }
`GetEventArgument4(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventArgument5

{: .code-example }
`GetEventArgument5(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventChance

{: .code-example }
`GetEventChance(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventFlags

{: .code-example }
`GetEventFlags(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventID

{: .code-example }
`GetEventID(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetEventPhaseMask

{: .code-example }
`GetEventPhaseMask(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetGameObjectArg

{: .code-example }
`GetGameObjectArg(): TSGameObject`

**Returns:** 
[`TSGameObject`](TSGameObject)

___

{: .api-section }
### GetLastInvoker

{: .code-example }
`GetLastInvoker(): TSUnit`

**Returns:** 
[`TSUnit`](TSUnit)

___

{: .api-section }
### GetLink

{: .code-example }
`GetLink(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetPriority

{: .code-example }
`GetPriority(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetSelf

{: .code-example }
`GetSelf(): TSWorldObject`

**Returns:** 
[`TSWorldObject`](TSWorldObject)

___

{: .api-section }
### GetSourceType

{: .code-example }
`GetSourceType(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetSpellArg

{: .code-example }
`GetSpellArg(): TSSpellInfo`

**Returns:** 
[`TSSpellInfo`](TSSpellInfo)

___

{: .api-section }
### GetTargetList

{: .code-example }
`GetTargetList(id, ref): TSArray<TSWorldObject>`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `id` | `uint32` |
| `ref` | [`TSWorldObject`](TSWorldObject) |

**Returns:** 
`TSArray`<[`TSWorldObject`](TSWorldObject)\>

___

{: .api-section }
### GetTargetParam1

{: .code-example }
`GetTargetParam1(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetTargetParam2

{: .code-example }
`GetTargetParam2(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetTargetParam3

{: .code-example }
`GetTargetParam3(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetTargetParam4

{: .code-example }
`GetTargetParam4(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetTargetX

{: .code-example }
`GetTargetX(): float`

**Returns:** 
`float`

___

{: .api-section }
### GetTargetY

{: .code-example }
`GetTargetY(): float`

**Returns:** 
`float`

___

{: .api-section }
### GetTargetZ

{: .code-example }
`GetTargetZ(): float`

**Returns:** 
`float`

___

{: .api-section }
### GetTargets

{: .code-example }
`GetTargets(): TSArray<TSWorldObject>`

**Returns:** 
`TSArray`<[`TSWorldObject`](TSWorldObject)\>

___

{: .api-section }
### GetTimer

{: .code-example }
`GetTimer(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetUIntArg1

{: .code-example }
`GetUIntArg1(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetUIntArg2

{: .code-example }
`GetUIntArg2(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### GetUnitArg

{: .code-example }
`GetUnitArg(): TSUnit`

**Returns:** 
[`TSUnit`](TSUnit)

___

{: .api-section }
### StoreCounter

{: .code-example }
`StoreCounter(id, value, reset): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `id` | `uint32` |
| `value` | `uint32` |
| `reset` | `uint32` |

**Returns:** 
`void`

___

{: .api-section }
### StoreTargetList

{: .code-example }
`StoreTargetList(objects, id): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `objects` | `TSArray`<[`TSWorldObject`](TSWorldObject)\> |
| `id` | `uint32` |

**Returns:** 
`void`

