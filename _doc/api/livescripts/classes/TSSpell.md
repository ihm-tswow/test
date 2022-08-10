---
title: TSSpell
---


## Methods

{: .api-section }
### Cancel

{: .code-example }
`Cancel(): void`

Cancels the [Spell].

**Returns:** 
`void`

___

{: .api-section }
### Cast

{: .code-example }
`Cast(skipCheck): void`

Casts the [Spell].

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `skipCheck` | `boolean` |

**Returns:** 
`void`

___

{: .api-section }
### Finish

{: .code-example }
`Finish(): void`

Finishes the [Spell].

**Returns:** 
`void`

___

{: .api-section }
### GetCastTime

{: .code-example }
`GetCastTime(): TSNumber<int32>`

Returns the cast time of the [Spell].

**Returns:** 
`TSNumber`<`int32`\>

int32 castTime

___

{: .api-section }
### GetCaster

{: .code-example }
`GetCaster(): TSWorldObject`

Returns the [Unit] that casted the [Spell].

**Returns:** 
[`TSWorldObject`](TSWorldObject)

caster

___

{: .api-section }
### GetDuration

{: .code-example }
`GetDuration(): TSNumber<int32>`

Returns the spell duration of the [Spell].

**Returns:** 
`TSNumber`<`int32`\>

int32 duration

___

{: .api-section }
### GetEntry

{: .code-example }
`GetEntry(): TSNumber<uint32>`

Returns the entry ID of the [Spell].

**Returns:** 
`TSNumber`<`uint32`\>

uint32 entryId

___

{: .api-section }
### GetGlyphSlot

{: .code-example }
`GetGlyphSlot(): TSNumber<uint32>`

**Returns:** 
`TSNumber`<`uint32`\>

___

{: .api-section }
### GetOriginalCaster

{: .code-example }
`GetOriginalCaster(): TSWorldObject`

Returns the [WorldObject] that originally casted the [Spell].

**Returns:** 
[`TSWorldObject`](TSWorldObject)

original caster

___

{: .api-section }
### GetOriginalOrCurrentCaster

{: .code-example }
`GetOriginalOrCurrentCaster(): TSWorldObject`

Returns the [WorldObject] that originally casted the [Spell], or the current caster.

**Returns:** 
[`TSWorldObject`](TSWorldObject)

original or current caster

___

{: .api-section }
### GetPowerCost

{: .code-example }
`GetPowerCost(): TSNumber<uint32>`

Returns the power cost of the [Spell].

**Returns:** 
`TSNumber`<`uint32`\>

uint32 powerCost

___

{: .api-section }
### GetSpellInfo

{: .code-example }
`GetSpellInfo(): TSSpellInfo`

**Returns:** 
[`TSSpellInfo`](TSSpellInfo)

___

{: .api-section }
### GetTarget

{: .code-example }
`GetTarget(): TSObject`

Returns the target [Object] of the [Spell].

The target can be any of the following [Object] types:
- [Player]
- [Creature]
- [GameObject]
- [Item]
- [Corpse]

**Returns:** 
[`TSObject`](TSObject)

target

___

{: .api-section }
### GetTargetDest

{: .code-example }
`GetTargetDest(): TSPosition`

Returns the target destination coordinates of the [Spell].

**Returns:** 
[`TSPosition`](TSPosition)

float x : x coordinate of the [Spell]

___

{: .api-section }
### IsAutoRepeat

{: .code-example }
`IsAutoRepeat(): boolean`

Returns `true` if the [Spell] is automatically repeating, `false` otherwise.

**Returns:** 
`boolean`

bool isAutoRepeating

___

{: .api-section }
### IsNull

{: .code-example }
`IsNull(): boolean`

**Returns:** 
`boolean`

___

{: .api-section }
### SetAutoRepeat

{: .code-example }
`SetAutoRepeat(repeat): void`

Sets the [Spell] to automatically repeat.

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `repeat` | `boolean` |

**Returns:** 
`void`

