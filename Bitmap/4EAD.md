# 0x4EAD

**Index:** ```0x4EAD```

**Tag Group:** ```Bitmap (bitm)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Usage	|Int32	|0
Flags	|Enum (BitmapRuntimeFlags)	|null
SpriteSpacing	|Int16	|4
UnknownC	|Single	|5
Unknown10	|Single	|0.5
CurveMode	|Enum (BitmapCurveMode)	|null
MaxMipMapLevel	|SByte	|0
MaxResolution	|Int16	|0
AtlasIndex	|Int16	|0
ForceBitmapFormatEnum	|Int16	|0
TightBounds	|TagBlock (TightBounds)	|0
UsageOverrides	|TagBlock (UsageOverrides)	|[1](#usageoverrides)
ManualSequences	|TagBlock (ManualSequences)	|0
SourceData	|Byte[]	|System.Byte[]
ProcessedPixelData	|Byte[]	|System.Byte[]
Sequences	|TagBlock (Sequences)	|0
Images	|TagBlock (Images)	|[1](#images)
XenonProcessedPixelData	|Byte[]	|System.Byte[]
XenonImages	|TagBlock (XenonImages)	|0
Resources	|TagBlock (Resources)	|[1](#resources)
InterleavedResources	|TagBlock (InterleavedResources)	|0
UnknownB4	|Int32	|0


## Tag Blocks

### UsageOverrides

**0:**

Name	| Type	| Value
---	|---	|---	|
SourceGamma	|Single	|0
BitmapCurveEnum	|Int32	|1
Unknown8	|Int32	|2
UnknownC	|Int32	|0
Unknown10	|Int32	|0
Unknown14	|Int32	|0
Unknown18	|Int32	|0
Unknown1C	|Int32	|0
Unknown20	|Int32	|0
Unknown24	|Int32	|0


### Images

**0:**

Name	| Type	| Value
---	|---	|---	|
Signature	|Tag	|bitm
Width	|Int16	|32
Height	|Int16	|8
Depth	|SByte	|1
XboxFlags	|Enum (BitmapFlagsXbox)	|null
Type	|Enum (BitmapType)	|null
FourTimesLog2Size	|Byte	|0
Format	|Enum (BitmapFormat)	|null
Flags	|Enum (BitmapFlags)	|null
RegistrationPoint	|Point2d	|{ X: 0, Y: 0 }
MipmapCount	|SByte	|5
Curve	|Enum (BitmapImageCurve)	|null
InterleavedTextureIndex	|Byte	|0
InterleavedTextureIndex2	|Byte	|0
DataOffset	|Int32	|0
DataSize	|Int32	|400
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

