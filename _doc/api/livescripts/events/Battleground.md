---
title: Battleground
---






{: .api-section }
### OnAchievementCriteria




{: .code-example }
`OnAchievementCriteria((bg,criteria,player,target,miscValueA,handled) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `criteria` | `uint32` |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `target` | [`TSUnit`](../classes/TSUnit) |
| `miscValueA` | `uint32` |
| `handled` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnAddCreature




{: .code-example }
`OnAddCreature((bg,type,entry,x,y,z,o,respawnTime) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `type` | `uint32` |
| `entry` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `x` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `y` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `z` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `o` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `respawnTime` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |

{: .api-section }
### OnAddGameObject




{: .code-example }
`OnAddGameObject((bg,type,entry,goState,x,y,z,o,rot0,rot1,rot2,rot3) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `type` | `uint32` |
| `entry` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `goState` | [`TSMutable`](../classes/TSMutable)<`uint8`\> |
| `x` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `y` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `z` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `o` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `rot0` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `rot1` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `rot2` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `rot3` | [`TSMutable`](../classes/TSMutable)<`float`\> |

{: .api-section }
### OnAddPlayer




{: .code-example }
`OnAddPlayer((bg,player) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |

{: .api-section }
### OnAddSpiritGuide




{: .code-example }
`OnAddSpiritGuide((bg,type,entry,teamId,x,y,z,o) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `type` | `uint32` |
| `entry` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |
| `teamId` | [`TSMutable`](../classes/TSMutable)<`uint8`\> |
| `x` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `y` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `z` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `o` | [`TSMutable`](../classes/TSMutable)<`float`\> |

{: .api-section }
### OnAreaTrigger




{: .code-example }
`OnAreaTrigger((bg,player,trigger,handled) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `trigger` | `uint32` |
| `handled` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnCanCreate




{: .code-example }
`OnCanCreate((bg,success) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `success` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnClickFlag




{: .code-example }
`OnClickFlag((bg,player,flagObj) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `flagObj` | [`TSGameObject`](../classes/TSGameObject) |

{: .api-section }
### OnCloseDoors




{: .code-example }
`OnCloseDoors((bg) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |

{: .api-section }
### OnCreate




{: .code-example }
`OnCreate((bg) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |

{: .api-section }
### OnDestroyGate




{: .code-example }
`OnDestroyGate((bg,player,target) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `target` | [`TSGameObject`](../classes/TSGameObject) |

{: .api-section }
### OnDropFlag




{: .code-example }
`OnDropFlag((bg,player) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |

{: .api-section }
### OnEndEarly




{: .code-example }
`OnEndEarly((bg,winner) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `winner` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |

{: .api-section }
### OnEndLate



Note that "winner" can no longer be changed at this stage,
for that, use "OnEndEarly"


{: .code-example }
`OnEndLate((bg,winner) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `winner` | `uint32` |

{: .api-section }
### OnGenericEvent




{: .code-example }
`OnGenericEvent((bg,obj,eventId,invoker) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `obj` | [`TSWorldObject`](../classes/TSWorldObject) |
| `eventId` | `uint32` |
| `invoker` | [`TSWorldObject`](../classes/TSWorldObject) |

{: .api-section }
### OnKillCreature




{: .code-example }
`OnKillCreature((bg,victim,killer,player) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `victim` | [`TSCreature`](../classes/TSCreature) |
| `killer` | `any` |
| `player` | [`TSPlayer`](../classes/TSPlayer) |

{: .api-section }
### OnKillPlayer




{: .code-example }
`OnKillPlayer((bg,victim,killer) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `victim` | [`TSPlayer`](../classes/TSPlayer) |
| `killer` | [`TSPlayer`](../classes/TSPlayer) |

{: .api-section }
### OnOpenDoors




{: .code-example }
`OnOpenDoors((bg) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |

{: .api-section }
### OnPlayerLogin




{: .code-example }
`OnPlayerLogin((bg,player) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |

{: .api-section }
### OnPlayerLogout




{: .code-example }
`OnPlayerLogout((bg,player) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |

{: .api-section }
### OnPlayerUnderMap




{: .code-example }
`OnPlayerUnderMap((bg,player,handled) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `handled` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnReload




{: .code-example }
`OnReload((bg) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |

{: .api-section }
### OnRemovePlayer




{: .code-example }
`OnRemovePlayer((bg,guid,player,teamId) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `guid` | `uint64` |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `teamId` | `uint32` |

{: .api-section }
### OnReset




{: .code-example }
`OnReset((bg) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |

{: .api-section }
### OnSelect




{: .code-example }
`OnSelect((bgType) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bgType` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |

{: .api-section }
### OnUpdateEarly




{: .code-example }
`OnUpdateEarly((bg,diff) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `diff` | `uint32` |

{: .api-section }
### OnUpdateLate




{: .code-example }
`OnUpdateLate((bg,diff) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `diff` | `uint32` |

{: .api-section }
### OnUpdateScore




{: .code-example }
`OnUpdateScore((bg,player,type,isAddHonor,value) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bg` | [`TSBattleground`](../classes/TSBattleground) |
| `player` | [`TSPlayer`](../classes/TSPlayer) |
| `type` | `uint32` |
| `isAddHonor` | `boolean` |
| `value` | [`TSMutable`](../classes/TSMutable)<`uint32`\> |

{: .api-section }
### OnWeight




{: .code-example }
`OnWeight((bgType,weight,origType) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `bgType` | `uint32` |
| `weight` | [`TSMutable`](../classes/TSMutable)<`float`\> |
| `origType` | `uint32` |
