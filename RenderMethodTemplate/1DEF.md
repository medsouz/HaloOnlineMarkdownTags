# [0x1DEF] 0x00001DEF

**Name:** ```0x00001DEF```

**Index:** ```0x1DEF```

**Tag Group:** ```RenderMethodTemplate (rmt2)```

## Fields

Name	| Type	| Value
---	|---	|---	|
VertexShader	|CachedTagInstance (VertexShader)	|[[0x1DF1] 0x00001DF1](../VertexShader/1DF1.md)
PixelShader	|CachedTagInstance (PixelShader)	|[[0x1DF2] 0x00001DF2](../PixelShader/1DF2.md)
DrawModeBitmask	|UInt32	|1
DrawModes	|TagBlock (DrawModes)	|[1](#drawmodes)
Unknown3	|TagBlock (Unknown3)	|[1](#unknown3)
ArgumentMappings	|TagBlock (ArgumentMappings)	|[5](#argumentmappings)
Arguments	|TagBlock (Arguments)	|[4](#arguments)
Unknown5	|TagBlock (Unknown5)	|0
Unknown6	|TagBlock (Unknown6)	|0
ShaderMaps	|TagBlock (ShaderMaps)	|[1](#shadermaps)
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
Unknown	|UInt32	|134415360
Unknown2	|UInt32	|0
Unknown3	|UInt32	|2049
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0


### ArgumentMappings

**0:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|2
ArgumentIndex	|Byte	|0
Unknown	|Byte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|58
ArgumentIndex	|Byte	|0
Unknown	|Byte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|59
ArgumentIndex	|Byte	|1
Unknown	|Byte	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|229
ArgumentIndex	|Byte	|2
Unknown	|Byte	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
RegisterIndex	|UInt16	|230
ArgumentIndex	|Byte	|3
Unknown	|Byte	|0


### Arguments

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|tint_color


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|intensity


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|u_tiles


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|v_tiles


### ShaderMaps

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base_map


