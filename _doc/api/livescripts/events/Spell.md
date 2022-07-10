---
title: Spell
---






{: .api-section }
### OnAfterCast




{: .code-example }
`OnAfterCast((spell,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAfterDispel




{: .code-example }
`OnAfterDispel((aura,dispel,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `aura` | [`TSAura`](../classes/TSAura) |
| `dispel` | [`TSDispelInfo`](../classes/TSDispelInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAfterEffectApply




{: .code-example }
`OnAfterEffectApply((effect,application,modes,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `modes` | [`AuraEffectHandleMode`](../enums/AuraEffectHandleMode) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAfterEffectProc




{: .code-example }
`OnAfterEffectProc((effect,application,proc,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `proc` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAfterEffectRemove




{: .code-example }
`OnAfterEffectRemove((effect,application,modes,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `modes` | [`AuraEffectHandleMode`](../enums/AuraEffectHandleMode) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAfterHit




{: .code-example }
`OnAfterHit((spell,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAfterProc




{: .code-example }
`OnAfterProc((application,proc,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `proc` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnApply




{: .code-example }
`OnApply((effect,application,type) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `type` | `uint32` |

{: .api-section }
### OnBeforeCast




{: .code-example }
`OnBeforeCast((spell,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnBeforeHit




{: .code-example }
`OnBeforeHit((spell,miss,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `miss` | [`SpellMissInfo`](../enums/SpellMissInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnCalcAuraCrit



critChance should be between 0 and 1


{: .code-example }
`OnCalcAuraCrit((aura,chance) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `aura` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `chance` | [`TSMutable`](../classes/TSMutable)<`float`\> |

{: .api-section }
### OnCalcCrit



critChance should be between 0 and 1


{: .code-example }
`OnCalcCrit((spelL,chance) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spelL` | [`TSSpell`](../classes/TSSpell) |
| `chance` | [`TSMutable`](../classes/TSMutable)<`float`\> |

{: .api-section }
### OnCalcHit



hitChance should be an integer between 0 and 10000


{: .code-example }
`OnCalcHit((spell,hitChance,attacker,defender) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpellInfo`](../classes/TSSpellInfo) |
| `hitChance` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `attacker` | [`TSWorldObject`](../classes/TSWorldObject) |
| `defender` | [`TSUnit`](../classes/TSUnit) |

{: .api-section }
### OnCalcMeleeMiss




{: .code-example }
`OnCalcMeleeMiss((spell,miss,attacker,victim,attackType,skillDiff) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpellInfo`](../classes/TSSpellInfo) |
| `miss` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `attacker` | [`TSUnit`](../classes/TSUnit) |
| `victim` | [`TSUnit`](../classes/TSUnit) |
| `attackType` | [`WeaponAttackType`](../enums/WeaponAttackType) |
| `skillDiff` | `int32` |

{: .api-section }
### OnCalcMiss




{: .code-example }
`OnCalcMiss((spell,target,missCondition,effectMask) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `target` | [`TSUnit`](../classes/TSUnit) |
| `missCondition` | [`TSMutable`](../classes/TSMutable)<[`SpellMissInfo`](../enums/SpellMissInfo)\> |
| `effectMask` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |

{: .api-section }
### OnCalcReflect



reflectCHance should be an integer between 0 and 10000


{: .code-example }
`OnCalcReflect((spell,reflectChance,attacker,victim) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpellInfo`](../classes/TSSpellInfo) |
| `reflectChance` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `attacker` | [`TSWorldObject`](../classes/TSWorldObject) |
| `victim` | [`TSUnit`](../classes/TSUnit) |

{: .api-section }
### OnCalcResist



resistChance should be an integer between 0 and 10000


{: .code-example }
`OnCalcResist((spell,resistChance,attacker,defender) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpellInfo`](../classes/TSSpellInfo) |
| `resistChance` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `attacker` | [`TSWorldObject`](../classes/TSWorldObject) |
| `defender` | [`TSUnit`](../classes/TSUnit) |

{: .api-section }
### OnCalcSpellPowerLevelPenalty




{: .code-example }
`OnCalcSpellPowerLevelPenalty((spell,penalty,caster) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpellInfo`](../classes/TSSpellInfo) |
| `penalty` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `caster` | [`TSUnit`](../classes/TSUnit) |

{: .api-section }
### OnCast




{: .code-example }
`OnCast((spell) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |

{: .api-section }
### OnCheckAreaTarget




{: .code-example }
`OnCheckAreaTarget((aura,unit,result,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `aura` | [`TSAura`](../classes/TSAura) |
| `unit` | [`TSUnit`](../classes/TSUnit) |
| `result` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnCheckCast




{: .code-example }
`OnCheckCast((spell,result) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `result` | [`TSMutable`](../classes/TSMutable)<[`SpellCastResult`](../enums/SpellCastResult)\> |

{: .api-section }
### OnCheckEffectProc




{: .code-example }
`OnCheckEffectProc((effect,application,procEvent,result,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `procEvent` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `result` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnCheckProc




{: .code-example }
`OnCheckProc((application,procEvent,result,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `procEvent` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `result` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnDamageEarly




{: .code-example }
`OnDamageEarly((spell,damage,info,type,isCrit,effectMask) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `damage` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `info` | [`TSSpellDamageInfo`](../classes/TSSpellDamageInfo) |
| `type` | `uint32` |
| `isCrit` | `boolean` |
| `effectMask` | `uint32` |

{: .api-section }
### OnDamageLate




{: .code-example }
`OnDamageLate((spell,damage,info,type,isCrit,effectMask) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `damage` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `info` | [`TSSpellDamageInfo`](../classes/TSSpellDamageInfo) |
| `type` | `uint32` |
| `isCrit` | `boolean` |
| `effectMask` | `uint32` |

{: .api-section }
### OnDestinationTargetSelect




{: .code-example }
`OnDestinationTargetSelect((spell,dest,index,target,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `dest` | [`TSSpellDestination`](../classes/TSSpellDestination) |
| `index` | [`SpellEffIndex`](../enums/SpellEffIndex) |
| `target` | [`TSSpellImplicitTargetInfo`](../classes/TSSpellImplicitTargetInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnDispel




{: .code-example }
`OnDispel((aura,dispel,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `aura` | [`TSAura`](../classes/TSAura) |
| `dispel` | [`TSDispelInfo`](../classes/TSDispelInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffect




{: .code-example }
`OnEffect((spell,cancel,info,mode,unitTarget,item,obj,corpse) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `info` | [`TSSpellEffectInfo`](../classes/TSSpellEffectInfo) |
| `mode` | [`SpellEffectHandleMode`](../enums/SpellEffectHandleMode) |
| `unitTarget` | [`TSUnit`](../classes/TSUnit) |
| `item` | [`TSItem`](../classes/TSItem) |
| `obj` | [`TSGameObject`](../classes/TSGameObject) |
| `corpse` | [`TSCorpse`](../classes/TSCorpse) |

{: .api-section }
### OnEffectAbsorb




{: .code-example }
`OnEffectAbsorb((effect,application,damage,absorbAmount,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `damage` | [`TSDamageInfo`](../classes/TSDamageInfo) |
| `absorbAmount` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectAfterAbsorb




{: .code-example }
`OnEffectAfterAbsorb((effect,application,damage,absorbAmount,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `damage` | [`TSDamageInfo`](../classes/TSDamageInfo) |
| `absorbAmount` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectAfterManaShield




{: .code-example }
`OnEffectAfterManaShield((effect,application,damage,absorbAmount,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `damage` | [`TSDamageInfo`](../classes/TSDamageInfo) |
| `absorbAmount` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectApplyGlyph



**`note`** Use with Player.OnGlyphInitForLevel


{: .code-example }
`OnEffectApplyGlyph((spell,locked) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `locked` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectCalcAmount




{: .code-example }
`OnEffectCalcAmount((effect,amount,canBeReclalculated,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `amount` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `canBeReclalculated` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectCalcPeriodic




{: .code-example }
`OnEffectCalcPeriodic((effect,isPeriodic,amplitude,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `isPeriodic` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `amplitude` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectCalcSpellMod




{: .code-example }
`OnEffectCalcSpellMod((effect,modifier,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `modifier` | [`TSSpellModifier`](../classes/TSSpellModifier) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectManaShield




{: .code-example }
`OnEffectManaShield((effect,application,damage,absorbAmount,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `damage` | [`TSDamageInfo`](../classes/TSDamageInfo) |
| `absorbAmount` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectPeriodic




{: .code-example }
`OnEffectPeriodic((effect,application,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectProc




{: .code-example }
`OnEffectProc((effect,application,eventInfo,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `eventInfo` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnEffectSplit




{: .code-example }
`OnEffectSplit((effect,application,damage,splitAmount,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `damage` | [`TSDamageInfo`](../classes/TSDamageInfo) |
| `splitAmount` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnHit




{: .code-example }
`OnHit((spell) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |

{: .api-section }
### OnObjectAreaTargetSelect




{: .code-example }
`OnObjectAreaTargetSelect((spell,objects,index,target,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `objects` | [`TSWorldObjectCollection`](../classes/TSWorldObjectCollection) |
| `index` | [`SpellEffIndex`](../enums/SpellEffIndex) |
| `target` | [`TSSpellImplicitTargetInfo`](../classes/TSSpellImplicitTargetInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnObjectTargetSelect




{: .code-example }
`OnObjectTargetSelect((spell,object,index,target,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `object` | [`TSMutableWorldObject`](../classes/TSMutableWorldObject) |
| `index` | [`SpellEffIndex`](../enums/SpellEffIndex) |
| `target` | [`TSSpellImplicitTargetInfo`](../classes/TSSpellImplicitTargetInfo) |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnPeriodicDamage




{: .code-example }
`OnPeriodicDamage((aura,damage) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `aura` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `damage` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |

{: .api-section }
### OnPrepareProc




{: .code-example }
`OnPrepareProc((application,procEvent,prepare,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `procEvent` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `prepare` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnProc




{: .code-example }
`OnProc((application,proc,handled,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `proc` | [`TSProcEventInfo`](../classes/TSProcEventInfo) |
| `handled` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnRemove




{: .code-example }
`OnRemove((effect,application,type) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |
| `application` | [`TSAuraApplication`](../classes/TSAuraApplication) |
| `type` | `uint32` |

{: .api-section }
### OnResistAbsorbCalculate




{: .code-example }
`OnResistAbsorbCalculate((spelL,damage,resistAmount,absorbAmount,cancel) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spelL` | [`TSSpell`](../classes/TSSpell) |
| `damage` | [`TSDamageInfo`](../classes/TSDamageInfo) |
| `resistAmount` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `absorbAmount` | [`TSMutable`](../classes/TSMutable)<`int32`\> |
| `cancel` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnSuccessfulDispel




{: .code-example }
`OnSuccessfulDispel((spell,dispelType) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpell`](../classes/TSSpell) |
| `dispelType` | `uint32` |

{: .api-section }
### OnTick




{: .code-example }
`OnTick((effect) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `effect` | [`TSAuraEffect`](../classes/TSAuraEffect) |

{: .api-section }
### OnTrainerSend




{: .code-example }
`OnTrainerSend((spell,trainerId,receiver,allow) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `spell` | [`TSSpellInfo`](../classes/TSSpellInfo) |
| `trainerId` | `uint32` |
| `receiver` | [`TSPlayer`](../classes/TSPlayer) |
| `allow` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
