# [0x1CEB] 0x00001CEB

**Name:** ```0x00001CEB```

**Index:** ```0x1CEB```

**Tag Group:** ```Bitmap (bitm)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Usage	|Int32	|19
Flags	|Enum (BitmapRuntimeFlags)	|null
SpriteSpacing	|Int16	|-1
UnknownC	|Single	|5
Unknown10	|Single	|0.5
CurveMode	|Enum (BitmapCurveMode)	|null
MaxMipMapLevel	|SByte	|0
MaxResolution	|Int16	|0
AtlasIndex	|Int16	|0
ForceBitmapFormatEnum	|Int16	|23
TightBounds	|TagBlock (TightBounds)	|0
UsageOverrides	|TagBlock (UsageOverrides)	|0
ManualSequences	|TagBlock (ManualSequences)	|0
SourceData	|Byte[]	|System.Byte[]
ProcessedPixelData	|Byte[]	|System.Byte[]
Sequences	|TagBlock (Sequences)	|[1](#sequences)
Images	|TagBlock (Images)	|[1](#images)
XenonProcessedPixelData	|Byte[]	|System.Byte[]
XenonImages	|TagBlock (XenonImages)	|0
Resources	|TagBlock (Resources)	|[1](#resources)
InterleavedResources	|TagBlock (InterleavedResources)	|0
UnknownB4	|Int32	|0


## Tag Blocks

### Sequences

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|String	|
FirstBitmapIndex	|Int16	|0
BitmapCount	|Int16	|0
Sprites	|TagBlock (Sequences_Sprites)	|[4](#sequences_sprites)


### Sequences_Sprites

**0:**

Name	| Type	| Value
---	|---	|---	|
BitmapIndex	|Int16	|0
Left	|Single	|0.75
Right	|Single	|1
Top	|Single	|0
Bottom	|Single	|1
RegistrationPoint	|RealPoint2d	|{ X: 0.125, Y: 0.5 }


**1:**

Name	| Type	| Value
---	|---	|---	|
BitmapIndex	|Int16	|0
Left	|Single	|0
Right	|Single	|0.25
Top	|Single	|0
Bottom	|Single	|1
RegistrationPoint	|RealPoint2d	|{ X: 0.125, Y: 0.5 }


**2:**

Name	| Type	| Value
---	|---	|---	|
BitmapIndex	|Int16	|0
Left	|Single	|0.25
Right	|Single	|0.5
Top	|Single	|0
Bottom	|Single	|1
RegistrationPoint	|RealPoint2d	|{ X: 0.125, Y: 0.5 }


**3:**

Name	| Type	| Value
---	|---	|---	|
BitmapIndex	|Int16	|0
Left	|Single	|0.5
Right	|Single	|0.75
Top	|Single	|0
Bottom	|Single	|1
RegistrationPoint	|RealPoint2d	|{ X: 0.125, Y: 0.5 }


### Images

**0:**

Name	| Type	| Value
---	|---	|---	|
Signature	|Tag	|bitm
Width	|Int16	|512
Height	|Int16	|256
Depth	|SByte	|1
XboxFlags	|Enum (BitmapFlagsXbox)	|null
Type	|Enum (BitmapType)	|null
FourTimesLog2Size	|Byte	|0
Format	|Enum (BitmapFormat)	|null
Flags	|Enum (BitmapFlags)	|null
RegistrationPoint	|Point2d	|{ X: 0, Y: 0 }
MipmapCount	|SByte	|9
Curve	|Enum (BitmapImageCurve)	|null
InterleavedTextureIndex	|Byte	|255
InterleavedTextureIndex2	|Byte	|0
DataOffset	|Int32	|0
DataSize	|Int32	|349526
Unknown20	|Single	|0
Unknown24	|SByte	|0
Unknown25	|SByte	|0
Unknown26	|SByte	|0
Unknown27	|SByte	|0
Unknown28	|Int32	|-1
Unknown2C	|Int32	|0


### Resources

**0:**

Name	| Type	| Value
---	|---	|---	|
Resource	|ResourceReference	|BlamCore.Cache.ResourceReference
Unknown4	|Int32	|0

