---
title: TSAura
---


## Methods

{: .api-section }
### GetApplications

{: .code-example }
`GetApplications(): TSArray<TSAuraApplication>`

Returns all active applications of this aura.

**Returns:** 
`TSArray`<[`TSAuraApplication`](TSAuraApplication)\>

applications

___

{: .api-section }
### GetAuraID

{: .code-example }
`GetAuraID(): TSNumber<uint32>`

Returns the ID of the [Spell] that caused this [Aura] to be applied.

**Returns:** 
`TSNumber`<`uint32`\>

uint32 aura_id

___

{: .api-section }
### GetCaster

{: .code-example }
`GetCaster(): TSWorldObject`

Returns the [Unit] that casted the [Spell] that caused this [Aura] to be applied.

**Returns:** 
[`TSWorldObject`](TSWorldObject)

caster

___

{: .api-section }
### GetCasterGUID

{: .code-example }
`GetCasterGUID(): TSNumber<uint64>`

Returns the GUID of the [Unit] that casted the [Spell] that caused this [Aura] to be applied.

**Returns:** 
`TSNumber`<`uint64`\>

string caster_guid : the GUID of the Unit as a decimal string

___

{: .api-section }
### GetCasterLevel

{: .code-example }
`GetCasterLevel(): TSNumber<uint32>`

Returns the level of the [Unit] that casted the [Spell] that caused this [Aura] to be applied.

**Returns:** 
`TSNumber`<`uint32`\>

uint32 caster_level

___

{: .api-section }
### GetDuration

{: .code-example }
`GetDuration(): TSNumber<int32>`

Returns the amount of time left until the [Aura] expires.

**Returns:** 
`TSNumber`<`int32`\>

int32 duration : amount of time left in milliseconds

___

{: .api-section }
### GetEffect

{: .code-example }
`GetEffect(index): TSAuraEffect`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `index` | `uint8` |

**Returns:** 
[`TSAuraEffect`](TSAuraEffect)

___

{: .api-section }
### GetMaxDuration

{: .code-example }
`GetMaxDuration(): TSNumber<int32>`

Returns the amount of time this [Aura] lasts when applied.

To determine how much time has passed since this Aura was applied,
  subtract the result of [Aura]:GetDuration from the result of this method.

**Returns:** 
`TSNumber`<`int32`\>

int32 max_duration : the maximum duration of the Aura, in milliseconds

___

{: .api-section }
### GetOwner

{: .code-example }
`GetOwner(): TSWorldObject`

Returns the [Unit] that the [Aura] has been applied to.

**Returns:** 
[`TSWorldObject`](TSWorldObject)

owner

___

{: .api-section }
### GetStackAmount

{: .code-example }
`GetStackAmount(): TSNumber<uint32>`

Returns the number of times the [Aura] has "stacked".

This is the same as the number displayed on the [Aura]'s icon in-game.

**Returns:** 
`TSNumber`<`uint32`\>

uint32 stack_amount

___

{: .api-section }
### IsNull

{: .code-example }
`IsNull(): boolean`

**Returns:** 
`boolean`

___

{: .api-section }
### Remove

{: .code-example }
`Remove(): void`

Remove this [Aura] from the [Unit] it is applied to.

**Returns:** 
`void`

___

{: .api-section }
### SetDuration

{: .code-example }
`SetDuration(duration): void`

Change the amount of time before the [Aura] expires.

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `duration` | `int32` |

**Returns:** 
`void`

___

{: .api-section }
### SetMaxDuration

{: .code-example }
`SetMaxDuration(duration): void`

Change the maximum amount of time before the [Aura] expires.

This does not affect the current duration of the [Aura], but if the [Aura]
  is reset to the maximum duration, it will instead change to `duration`.

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `duration` | `int32` |

**Returns:** 
`void`

___

{: .api-section }
### SetStackAmount

{: .code-example }
`SetStackAmount(amount): void`

Change the amount of times the [Aura] has "stacked" on the [Unit].

If `amount` is greater than or equal to the current number of stacks,
  then the [Aura] has its duration reset to the maximum duration.

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `amount` | `uint8` |

**Returns:** 
`void`

