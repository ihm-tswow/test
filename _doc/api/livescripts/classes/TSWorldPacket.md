---
title: TSWorldPacket
---


## Methods

{: .api-section }
### GetOpcode

{: .code-example }
`GetOpcode(): uint16`

Returns the opcode of the [WorldPacket].

**Returns:** 
`uint16`

uint16 opcode

___

{: .api-section }
### GetSize

{: .code-example }
`GetSize(): uint32`

Returns the size of the [WorldPacket].

**Returns:** 
`uint32`

uint32 size

___

{: .api-section }
### IsNull

{: .code-example }
`IsNull(): boolean`

**Returns:** 
`boolean`

___

{: .api-section }
### ReadDouble

{: .code-example }
`ReadDouble(): double`

**Returns:** 
`double`

___

{: .api-section }
### ReadFloat

{: .code-example }
`ReadFloat(): float`

**Returns:** 
`float`

___

{: .api-section }
### ReadInt16

{: .code-example }
`ReadInt16(): int16`

**Returns:** 
`int16`

___

{: .api-section }
### ReadInt32

{: .code-example }
`ReadInt32(): int32`

**Returns:** 
`int32`

___

{: .api-section }
### ReadInt64

{: .code-example }
`ReadInt64(): int64`

**Returns:** 
`int64`

___

{: .api-section }
### ReadInt8

{: .code-example }
`ReadInt8(): int8`

**Returns:** 
`int8`

___

{: .api-section }
### ReadString

{: .code-example }
`ReadString(): string`

**Returns:** 
`string`

___

{: .api-section }
### ReadUInt16

{: .code-example }
`ReadUInt16(): uint16`

**Returns:** 
`uint16`

___

{: .api-section }
### ReadUInt32

{: .code-example }
`ReadUInt32(): uint32`

**Returns:** 
`uint32`

___

{: .api-section }
### ReadUInt64

{: .code-example }
`ReadUInt64(): uint64`

**Returns:** 
`uint64`

___

{: .api-section }
### ReadUInt8

{: .code-example }
`ReadUInt8(): uint8`

**Returns:** 
`uint8`

___

{: .api-section }
### SetOpcode

{: .code-example }
`SetOpcode(opcode): void`

Sets the opcode of the [WorldPacket] to the specified opcode.

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type | Description |
|-
| `opcode` | `uint32` | : see Opcodes.h for all known opcodes |

**Returns:** 
`void`

___

{: .api-section }
### WriteDouble

{: .code-example }
`WriteDouble(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `double` |

**Returns:** 
`void`

___

{: .api-section }
### WriteFloat

{: .code-example }
`WriteFloat(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `float` |

**Returns:** 
`void`

___

{: .api-section }
### WriteInt16

{: .code-example }
`WriteInt16(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `int16` |

**Returns:** 
`void`

___

{: .api-section }
### WriteInt8

{: .code-example }
`WriteInt8(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `int8` |

**Returns:** 
`void`

___

{: .api-section }
### WriteString

{: .code-example }
`WriteString(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `string` |

**Returns:** 
`void`

___

{: .api-section }
### WriteUInt16

{: .code-example }
`WriteUInt16(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `uint16` |

**Returns:** 
`void`

___

{: .api-section }
### WriteUInt32

{: .code-example }
`WriteUInt32(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `uint32` |

**Returns:** 
`void`

___

{: .api-section }
### WriteUInt64

{: .code-example }
`WriteUInt64(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `uint64` |

**Returns:** 
`void`

___

{: .api-section }
### WriteUInt8

{: .code-example }
`WriteUInt8(value): void`

#### Parameters

{: .table .api-table .table-bordered}
| Name | Type |
|-
| `value` | `uint8` |

**Returns:** 
`void`

