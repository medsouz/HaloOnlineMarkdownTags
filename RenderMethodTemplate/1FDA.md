# [0x1FDA] 0x00001FDA

**Name:** ```0x00001FDA```

**Index:** ```0x1FDA```

**Tag Group:** ```RenderMethodTemplate (rmt2)```

## Fields

Name	| Type	| Value
---	|---	|---	|
VertexShader	|CachedTagInstance (VertexShader)	|[[0x1FDB] 0x00001FDB](../VertexShader/1FDB.md)
PixelShader	|CachedTagInstance (PixelShader)	|[[0x1FDC] 0x00001FDC](../PixelShader/1FDC.md)
DrawModeBitmask	|UInt32	|1
DrawModes	|TagBlock (DrawModes)	|[1](#drawmodes)
Unknown3	|TagBlock (Unknown3)	|[1](#unknown3)
ArgumentMappings	|TagBlock (ArgumentMappings)	|[5](#argumentmappings)
Arguments	|TagBlock (Arguments)	|[2](#arguments)
Unknown5	|TagBlock (Unknown5)	|0
Unknown6	|TagBlock (Unknown6)	|0
ShaderMaps	|TagBlock (ShaderMaps)	|[3](#shadermaps)
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0


## Tag Blocks

### DrawModes

**0:**

Name	| Type	| Value
---	|---	|---	|
UnknownBlock2Pointer	|UInt16	|1024


### Unknown3

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|134417408
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0


### ArgumentMappings

**0:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|0
ArgumentIndex	|Byte	|0
Unknown	|Byte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|1
ArgumentIndex	|Byte	|1
Unknown	|Byte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|2
ArgumentIndex	|Byte	|2
Unknown	|Byte	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|12
ArgumentIndex	|Byte	|0
Unknown	|Byte	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|13
ArgumentIndex	|Byte	|1
Unknown	|Byte	|0


### Arguments

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|blend_mode


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|fog


### ShaderMaps

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base_map


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|palette


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|alpha_map

