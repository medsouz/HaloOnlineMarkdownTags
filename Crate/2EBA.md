# [0x2EBA] objects\gear\covenant\military\battery\battery

**Name:** ```objects\gear\covenant\military\battery\battery```

**Index:** ```0x2EBA```

**Tag Group:** ```Crate (bloc)```

## Fields

Name	| Type	| Value
---	|---	|---	|
ObjectTypeHaloOnline	|Enum (GameObjectTypeHalo3ODST)	|null
Unused1	|SByte	|0
ObjectFlags	|Enum (GameObjectFlags)	|null
BoundingRadius	|Single	|0.325
BoundingOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0.25 }
AccelerationScale	|Single	|1.1
LightmapShadowMode	|Enum (LightmapShadowModeValue)	|null
SweetenerSize	|Enum (SweetenerSizeValue)	|null
WaterDensity	|Enum (WaterDensityValue)	|null
DynamicLightSphereRadius	|Single	|0
DynamicLightSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultModelVariant	|StringId	|
Model	|CachedTagInstance (Model)	|[[0x3323] objects\gear\covenant\military\battery\battery](../Model/3323.md)
CrateObject	|CachedTagInstance	|null
CollisionDamage	|CachedTagInstance	|null
EarlyMoverProperties	|TagBlock (EarlyMoverProperties)	|0
CreationEffect	|CachedTagInstance	|null
MaterialEffects	|CachedTagInstance	|null
ArmorSounds	|CachedTagInstance	|null
MeleeImpact	|CachedTagInstance	|null
AiProperties	|TagBlock (AiProperties)	|[1](#aiproperties)
Functions	|TagBlock (Functions)	|[3](#functions)
HudTextMessageIndex	|Int16	|0
Attachments	|TagBlock (Attachments)	|[1](#attachments)
Widgets	|TagBlock (Widgets)	|0
ChangeColors	|TagBlock (ChangeColors)	|[1](#changecolors)
NodeMaps	|TagBlock (NodeMaps)	|0
MultiplayerObjectProperties	|TagBlock (MultiplayerObjectProperties)	|[1](#multiplayerobjectproperties)
RevivingEquipment	|TagBlock (RevivingEquipment)	|0
ModelObjectData	|TagBlock (ModelObjectData)	|[2](#modelobjectdata)
Flags2	|UInt16	|0
Unknown6	|Int16	|0
MetagameProperties	|TagBlock (MetagameProperties)	|0
Unknown7	|SByte	|0
Unknown8	|SByte	|0
Unknown9	|SByte	|0
Unknown10	|SByte	|0


## Tag Blocks

### AiProperties

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
AiTypeName	|StringId	|
Size	|Enum (ObjectSizeValue)	|null
LeapJumpSpeed	|Enum (AiDistanceValue)	|null


### Functions

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|one
ExportName	|StringId	|random_stream
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|


**1:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|
ExportName	|StringId	|random_glow
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|


**2:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|body_vitality
ExportName	|StringId	|health
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|


### Attachments

**0:**

Name	| Type	| Value
---	|---	|---	|
AtlasFlags	|Enum (AtlasFlagsValue)	|null
Attachment2	|CachedTagInstance (SoundLooping)	|[[0x3324] objects\gear\covenant\military\battery\battery](../SoundLooping/3324.md)
Marker	|StringId	|
ChangeColor	|Enum (ChangeColorValue)	|null
Unknown	|Int16	|0
PrimaryScale	|StringId	|
SecondaryScale	|StringId	|


### ChangeColors

**0:**

Name	| Type	| Value
---	|---	|---	|
InitialPermutations	|TagBlock (ChangeColors_InitialPermutations)	|0
Functions	|TagBlock (ChangeColors_Functions)	|0


### MultiplayerObjectProperties

**0:**

Name	| Type	| Value
---	|---	|---	|
EngineFlags	|Enum (EngineFlagsValue)	|null
ObjectType	|Enum (ObjectTypeValue)	|null
TeleporterFlags	|Byte	|0
Unknown	|SByte	|0
Flags	|Byte	|0
Shape	|Enum (ObjectShapeValue)	|null
SpawnTimerMode	|Enum (SpawnTimerModeValue)	|null
SpawnTime	|Int16	|60
UnknownSpawnTime	|Int16	|60
RadiusWidth	|Single	|0
Length	|Single	|0
Top	|Single	|0
Bottom	|Single	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int32	|0
Unknown6	|Int32	|0
ChildObject	|CachedTagInstance	|null
Unknown7	|Int32	|0
ShapeShader	|CachedTagInstance	|null
UnknownShader	|CachedTagInstance	|null
Unknown8	|CachedTagInstance	|null
Unknown9	|CachedTagInstance	|null
Unknown10	|CachedTagInstance	|null
Unknown11	|CachedTagInstance	|null
Unknown12	|CachedTagInstance	|null
Unknown13	|CachedTagInstance	|null


### ModelObjectData

**0:**

Name	| Type	| Value
---	|---	|---	|
Type	|Enum (TypeValue)	|null
Unknown	|Int16	|0
Offset	|RealPoint3d	|{ X: -1.098633E-05, Y: 0.0015, Z: 0.3 }
Radius	|Single	|0.25


**1:**

Name	| Type	| Value
---	|---	|---	|
Type	|Enum (TypeValue)	|null
Unknown	|Int16	|0
Offset	|RealPoint3d	|{ X: -1.098633E-05, Y: 0.0015, Z: 0.15 }
Radius	|Single	|0.25


