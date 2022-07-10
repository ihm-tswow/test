---
title: SmartAction
---






{: .api-section }
### OnActivateEarly




{: .code-example }
`OnActivateEarly((script,cancelAction,cancelLink) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `script` | [`TSSmartScriptValues`](../classes/TSSmartScriptValues) |
| `cancelAction` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
| `cancelLink` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |

{: .api-section }
### OnActivateLate




{: .code-example }
`OnActivateLate((script,cancelLink) => void`
#### Event Parameters

{: .table .table-bordered .event-table .api-table}
| Name | Type |
|-
| `script` | [`TSSmartScriptValues`](../classes/TSSmartScriptValues) |
| `cancelLink` | [`TSMutable`](../classes/TSMutable)<`boolean`\> |
