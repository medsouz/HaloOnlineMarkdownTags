# [0x1AFB] 0x00001AFB

**Name:** ```0x00001AFB```

**Index:** ```0x1AFB```

**Tag Group:** ```Shader (rmsh)```

## Fields

Name	| Type	| Value
---	|---	|---	|
BaseRenderMethod	|CachedTagInstance (RenderMethodDefinition)	|[[0x033F] shaders\shader](../RenderMethodDefinition/033F.md)
Unknown	|TagBlock (Unknown)	|[11](#unknown)
ImportData	|TagBlock (ImportData)	|[22](#importdata)
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
Unknown	|Int16	|3


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|2


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|2


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|2


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


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
MaterialType	|StringId	|base_map
Unknown	|Int32	|0
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFC] 0x00001AFC](../Bitmap/1AFC.md)
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|1
Unknown5	|Int16	|4
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|detail_map
Unknown	|Int32	|0
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFD] 0x00001AFD](../Bitmap/1AFD.md)
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
MaterialType	|StringId	|bump_map
Unknown	|Int32	|0
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFE] 0x00001AFE](../Bitmap/1AFE.md)
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|1
Unknown5	|Int16	|4
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|specular_coefficient
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


**4:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|diffuse_coefficient
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


**5:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|albedo_specular_tint_blend
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


**6:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|normal_specular_tint
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


**7:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|glancing_specular_tint
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


**8:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|area_specular_contribution
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


**9:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|analytical_specular_contribution
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


**10:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|self_illum_map
Unknown	|Int32	|0
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFF] 0x00001AFF](../Bitmap/1AFF.md)
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|0
Unknown5	|Int16	|0
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|0


**11:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|bump_detail_map
Unknown	|Int32	|0
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1B00] 0x00001B00](../Bitmap/1B00.md)
Unknown2	|UInt32	|0
Unknown3	|Int32	|0
Unknown4	|Int16	|1
Unknown5	|Int16	|4
Unknown6	|Int16	|0
Unknown7	|Int16	|0
Unknown8	|Int16	|0
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Functions	|TagBlock (ImportData_Functions)	|[1](#importdata_functions)


**12:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|environment_map_specular_contribution
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


**13:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|fresnel_curve_steepness
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


**14:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|albedo_blend
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


**15:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|roughness
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


**16:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|env_roughness_scale
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


**17:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|environment_map
Unknown	|Int32	|0
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
Functions	|TagBlock (ImportData_Functions)	|0


**18:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|normal_specular_power
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


**19:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|change_color_map
Unknown	|Int32	|0
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
Functions	|TagBlock (ImportData_Functions)	|0


**20:**

Name	| Type	| Value
---	|---	|---	|
MaterialType	|StringId	|glancing_specular_power
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


**21:**

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


### ImportData_Functions

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|2
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
Unknown	|Int32	|0
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
Name	|StringId	|variant
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Function2	|Byte[]	|System.Byte[]


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|1
Name	|StringId	|variant
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
Unknown	|Int32	|0
Name	|StringId	|
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Function2	|Byte[]	|System.Byte[]


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|2
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
Unknown	|Int32	|0
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
Unknown	|Int32	|0
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
Unknown	|Int32	|0
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
Unknown	|Int32	|0
Name	|StringId	|
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1090519040
Function2	|Byte[]	|System.Byte[]


### ShaderProperties

**0:**

Name	| Type	| Value
---	|---	|---	|
Template	|CachedTagInstance (RenderMethodTemplate)	|[[0x1B01] 0x00001B01](../RenderMethodTemplate/1B01.md)
ShaderMaps	|TagBlock (ShaderProperties_ShaderMaps)	|[6](#shaderproperties_shadermaps)
Arguments	|TagBlock (ShaderProperties_Arguments)	|[24](#shaderproperties_arguments)
Unknown	|TagBlock (ShaderProperties_Unknown)	|0
Unknown2	|UInt32	|0
DrawModes	|TagBlock (ShaderProperties_DrawModes)	|[20](#shaderproperties_drawmodes)
Unknown4	|TagBlock (ShaderProperties_Unknown4)	|[14](#shaderproperties_unknown4)
Unknown5	|TagBlock (ShaderProperties_Unknown5)	|[23](#shaderproperties_unknown5)
Functions	|TagBlock (ShaderProperties_Functions)	|[3](#shaderproperties_functions)
BitmapTransparency	|Int32	|0
Unknown7	|Int32	|1
Unknown8	|UInt32	|0
Unknown9	|Int16	|-1
Unknown10	|Int16	|0
Unknown11	|Int16	|-1
Unknown12	|Int16	|-1
Unknown13	|Int16	|-1
Unknown14	|Int16	|-1
Unknown15	|Int16	|-1
Unknown16	|Int16	|-1


### ShaderProperties_ShaderMaps

**0:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFC] 0x00001AFC](../Bitmap/1AFC.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|4
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFD] 0x00001AFD](../Bitmap/1AFD.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|0
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|1
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x02B7] shaders\default_bitmaps\bitmaps\gray_50_percent](../Bitmap/02B7.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|0
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|2
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFE] 0x00001AFE](../Bitmap/1AFE.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|4
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|3
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1B00] 0x00001B00](../Bitmap/1B00.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|4
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|4
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Bitmap	|CachedTagInstance (Bitmap)	|[[0x1AFF] 0x00001AFF](../Bitmap/1AFF.md)
Unknown	|SByte	|0
BitmapIndex	|SByte	|0
Unknown2	|SByte	|0
BitmapFlags	|Byte	|0
UnknownBitmapIndexEnable	|SByte	|0
UvArgumentIndex	|SByte	|20
Unknown3	|SByte	|0
Unknown4	|SByte	|0


### ShaderProperties_Arguments

**0:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|0
Arg4	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|15
Arg2	|Single	|15
Arg3	|Single	|0
Arg4	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|0
Arg4	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|0
Arg4	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|15
Arg2	|Single	|15
Arg3	|Single	|0
Arg4	|Single	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|1
Arg4	|Single	|1


**6:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|1
Arg4	|Single	|1


**7:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1.5
Arg2	|Single	|1.5
Arg3	|Single	|1.5
Arg4	|Single	|1.5


**8:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1.5
Arg2	|Single	|1.5
Arg3	|Single	|1.5
Arg4	|Single	|1.5


**9:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.8000001
Arg2	|Single	|0.8392158
Arg3	|Single	|0.8862746
Arg4	|Single	|1


**10:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1.5
Arg2	|Single	|1.5
Arg3	|Single	|1.5
Arg4	|Single	|1.5


**11:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.3529412
Arg2	|Single	|0.627451
Arg3	|Single	|0.7098039
Arg4	|Single	|1


**12:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|1
Arg4	|Single	|1


**13:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.2
Arg2	|Single	|0.2
Arg3	|Single	|0.2
Arg4	|Single	|0.2


**14:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.8
Arg2	|Single	|0.8
Arg3	|Single	|0.8
Arg4	|Single	|0.8


**15:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.4
Arg2	|Single	|0.4
Arg3	|Single	|0.4
Arg4	|Single	|0.4


**16:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.8
Arg2	|Single	|0.8
Arg3	|Single	|0.8
Arg4	|Single	|0.8


**17:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0
Arg2	|Single	|0
Arg3	|Single	|0
Arg4	|Single	|0


**18:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|1
Arg4	|Single	|1


**19:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0.2
Arg2	|Single	|0.2
Arg3	|Single	|0.2
Arg4	|Single	|0.2


**20:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|0
Arg4	|Single	|0


**21:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1
Arg2	|Single	|1
Arg3	|Single	|1
Arg4	|Single	|1


**22:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|1.705882
Arg2	|Single	|1.705882
Arg3	|Single	|1.705882
Arg4	|Single	|1.705882


**23:**

Name	| Type	| Value
---	|---	|---	|
Arg1	|Single	|0
Arg2	|Single	|0
Arg3	|Single	|0
Arg4	|Single	|0


### ShaderProperties_DrawModes

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1024


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1025


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1027


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1026


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1030


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1031


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1032


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1028


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1029


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1033


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1035


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1034


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1036


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|0


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|1037


### ShaderProperties_Unknown4

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|12


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|6
Unknown3	|SByte	|12


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|3
Unknown3	|SByte	|12


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|18
Unknown3	|SByte	|8


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|9
Unknown3	|SByte	|12


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|12
Unknown3	|SByte	|12


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|15
Unknown3	|SByte	|12


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|20
Unknown3	|SByte	|4


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|21
Unknown3	|SByte	|8


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0


### ShaderProperties_Unknown5

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|76
Unknown2	|Int16	|2304


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|78
Unknown2	|Int16	|2817


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|67
Unknown2	|Int16	|5634


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|76
Unknown2	|Int16	|2304


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|78
Unknown2	|Int16	|2817


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|67
Unknown2	|Int16	|5634


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|77
Unknown2	|Int16	|2304


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|79
Unknown2	|Int16	|2817


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|67
Unknown2	|Int16	|5634


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|77
Unknown2	|Int16	|2304


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|79
Unknown2	|Int16	|2817


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|67
Unknown2	|Int16	|5634


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|77
Unknown2	|Int16	|2304


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|79
Unknown2	|Int16	|2817


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|67
Unknown2	|Int16	|5634


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|77
Unknown2	|Int16	|2304


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|79
Unknown2	|Int16	|2817


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|67
Unknown2	|Int16	|5634


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|71
Unknown2	|Int16	|2304


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|73
Unknown2	|Int16	|2817


**20:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|64
Unknown2	|Int16	|5634


**21:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|71
Unknown2	|Int16	|2304


**22:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|73
Unknown2	|Int16	|2817


### ShaderProperties_Functions

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|1
Name	|StringId	|variant
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1065353216
Function2	|Byte[]	|System.Byte[]


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|1
Name	|StringId	|variant
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1065353216
Function2	|Byte[]	|System.Byte[]


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Name	|StringId	|
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1090519040
Function2	|Byte[]	|System.Byte[]


