---
title: Vehicle
---






{: .api-section }
### OnAddPassenger




{: .code-example }
`OnAddPassenger((veh,passenger,seatId) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `veh` | [`TSVehicle`](../classes/TSVehicle) |
| `passenger` | [`TSUnit`](../classes/TSUnit) |
| `seatId` | `int8` |

{: .api-section }
### OnInstall




{: .code-example }
`OnInstall((veh) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `veh` | [`TSVehicle`](../classes/TSVehicle) |

{: .api-section }
### OnInstallAccessory




{: .code-example }
`OnInstallAccessory((veh,accessory) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `veh` | [`TSVehicle`](../classes/TSVehicle) |
| `accessory` | [`TSCreature`](../classes/TSCreature) |

{: .api-section }
### OnRemovePassenger




{: .code-example }
`OnRemovePassenger((veh,passenger) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `veh` | [`TSVehicle`](../classes/TSVehicle) |
| `passenger` | [`TSUnit`](../classes/TSUnit) |

{: .api-section }
### OnReset




{: .code-example }
`OnReset((veh) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `veh` | [`TSVehicle`](../classes/TSVehicle) |

{: .api-section }
### OnUninstall




{: .code-example }
`OnUninstall((veh) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `veh` | [`TSVehicle`](../classes/TSVehicle) |
