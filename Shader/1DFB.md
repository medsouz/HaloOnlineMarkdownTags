# [0x1DFB] 0x00001DFB

**Name:** ```0x00001DFB```

**Index:** ```0x1DFB```

**Tag Group:** ```Shader (rmsh)```

## Fields

Name	| Type	| Value
---	|---	|---	|
BaseRenderMethod	|CachedTagInstance (RenderMethodDefinition)	|[[0x033F] shaders\shader](../RenderMethodDefinition/033F.md)
Unknown	|TagBlock (Unknown)	|[11](#unknown)
ImportData	|TagBlock (ImportData)	|[4](#importdata)
ShaderProperties	|TagBlock (ShaderProperties)	|[1](#shaderproperties)
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|2
Unknown5	|SByte	|0
Unknown6	|UInt32	|0
Unknown7	|Int32	|-1
Material	|StringId	|


## Tag Blocks

### Unknown

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|2


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


### ImportData

**0:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|self_illum_map
Unknown	|Int32	|0
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1084] 0x00001084](../Bitmap/1084.md)
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|1
Unknown5	|Int16	|6
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|self_illum_color
Unknown	|Int32	|1
Bitmap	|CachedTagInstance	|null
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|0
Unknown5	|Int16	|0
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|[1](#importdata_functions)


**2:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|self_illum_intensity
Unknown	|Int32	|2
Bitmap	|CachedTagInstance	|null
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|0
Unknown5	|Int16	|0
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|[1](#importdata_functions)


**3:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|albedo_color
Unknown	|Int32	|5
Bitmap	|CachedTagInstance	|null
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|0
Unknown5	|Int16	|0
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|[1](#importdata_functions)


### ImportData_Functions

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|1
Name	|StringId	|
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Function2	|Byte[]	|System.Byte[]


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Name	|StringId	|
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Function2	|Byte[]	|System.Byte[]


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|1
Name	|StringId	|
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Function2	|Byte[]	|System.Byte[]


### ShaderProperties

**0:**

Name	| Type	| Value
---	|---	|---	|
Template	|CachedTagInstance (RenderMethodTemplate)	|[[0x0EFC] 0x00000EFC](../RenderMethodTemplate/0EFC.md)
ShaderMaps	|TagBlock (ShaderProperties_ShaderMaps)	|[1](#shaderproperties_shadermaps)
Arguments	|TagBlock (ShaderProperties_Arguments)	|[4](#shaderproperties_arguments)
Unknown	|TagBlock (ShaderProperties_Unknown)	|0
Unknown2	|UInt32	|0
DrawModes	|TagBlock (ShaderProperties_DrawModes)	|0
Unknown4	|TagBlock (ShaderProperties_Unknown4)	|0
Unknown5	|TagBlock (ShaderProperties_Unknown5)	|0
Functions	|TagBlock (ShaderProperties_Functions)	|0
BitmapTransparency	|Int32	|1
Unknown7	|Int32	|1
Unknown8	|UInt32	|0
Unknown9	|Int16	|-1
Unknown10	|Int16	|-1
Unknown11	|Int16	|-1
Unknown12	|Int16	|-1
Unknown13	|Int16	|0
Unknown14	|Int16	|-1
Unknown15	|Int16	|-1
Unknown16	|Int16	|-1


### ShaderProperties_ShaderMaps

**0:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1084] 0x00001084](../Bitmap/1084.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|6
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|1
Unknown3	|SByte	|0
Unknown4	|SByte	|0


### ShaderProperties_Arguments

**0:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0
Arg2	|Single	|0
Arg3	|Single	|0
Arg4	|Single	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|0
Arg4	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.3098039
Arg2	|Single	|1
Arg3	|Single	|0.145098
Arg4	|Single	|1


**3:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|1
Arg4	|Single	|1


