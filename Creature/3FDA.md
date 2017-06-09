# [0x3FDA] objects\characters\ambient_life\lod_hornet\lod_hornet

**Name:** ```objects\characters\ambient_life\lod_hornet\lod_hornet```

**Index:** ```0x3FDA```

**Tag Group:** ```Creature (crea)```

## Fields

Name	| Type	| Value
---	|---	|---	|
ObjectTypeHaloOnline	|Enum (GameObjectTypeHalo3ODST)	|null
Unused1	|SByte	|0
ObjectFlags	|Enum (GameObjectFlags)	|null
BoundingRadius	|Single	|0.2
BoundingOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
AccelerationScale	|Single	|1
LightmapShadowMode	|Enum (LightmapShadowModeValue)	|null
SweetenerSize	|Enum (SweetenerSizeValue)	|null
WaterDensity	|Enum (WaterDensityValue)	|null
DynamicLightSphereRadius	|Single	|0
DynamicLightSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultModelVariant	|StringId	|
Model	|CachedTagInstance (Model)	|[[0x41D1] objects\vehicles\lod\lod_hornet\lod_hornet](../Model/41D1.md)
CrateObject	|CachedTagInstance	|null
CollisionDamage	|CachedTagInstance (CollisionDamage)	|[[0x2E57] globals\collision_damage\biped_small](../CollisionDamage/2E57.md)
EarlyMoverProperties	|TagBlock (EarlyMoverProperties)	|0
CreationEffect	|CachedTagInstance	|null
MaterialEffects	|CachedTagInstance	|null
ArmorSounds	|CachedTagInstance	|null
MeleeImpact	|CachedTagInstance	|null
AiProperties	|TagBlock (AiProperties)	|[1](#aiproperties)
Functions	|TagBlock (Functions)	|[1](#functions)
HudTextMessageIndex	|Int16	|0
Attachments	|TagBlock (Attachments)	|[2](#attachments)
Widgets	|TagBlock (Widgets)	|0
ChangeColors	|TagBlock (ChangeColors)	|0
NodeMaps	|TagBlock (NodeMaps)	|0
MultiplayerObjectProperties	|TagBlock (MultiplayerObjectProperties)	|0
RevivingEquipment	|TagBlock (RevivingEquipment)	|0
ModelObjectData	|TagBlock (ModelObjectData)	|0
Flags2	|UInt32	|76
DefaultTeam	|Enum (DefaultTeamValue)	|null
MotionSensorBlipSize	|Enum (MotionSensorBlipSizeValue)	|null
TurningVelocityMaximum	|Angle	|{ Degrees: 720, Radians: 12.56637 }
TurningAccelerationMaximum	|Angle	|{ Degrees: 1440, Radians: 25.13274 }
CasualTuringModifer	|Single	|0.5
AutoaimWidth	|Single	|0.03
Flags3	|UInt32	|99
HeightStanding	|Single	|0.551
HeightCrouching	|Single	|0.551
Radius	|Single	|0.275
Mass	|Single	|30
LivingMaterialName	|StringId	|hard_metal_thin_for_sentinel
DeadMaterialName	|StringId	|hard_metal_thin_for_sentinel
LivingGlobalMaterialIndex	|Int16	|67
DeadGlobalMaterialIndex	|Int16	|67
DeadSphereShapes	|TagBlock (DeadSphereShapes)	|[3](#deadsphereshapes)
PillShapes	|TagBlock (PillShapes)	|0
SphereShapes	|TagBlock (SphereShapes)	|[2](#sphereshapes)
MaximumSlopeAngle	|Angle	|{ Degrees: 45, Radians: 0.7853982 }
DownhillFalloffAngle	|Angle	|{ Degrees: 20, Radians: 0.3490658 }
DownhillCutoffAngle	|Angle	|{ Degrees: 45, Radians: 0.7853982 }
UphillFalloffAngle	|Angle	|{ Degrees: 20, Radians: 0.3490658 }
UphillCutoffAngle	|Angle	|{ Degrees: 45, Radians: 0.7853982 }
DownhillVelocityScale	|Single	|1.25
UphillVelocityScale	|Single	|0.65
Unknown6	|UInt32	|1060439283
Unknown7	|UInt32	|3199147331
Unknown8	|UInt32	|3207922931
Unknown9	|UInt32	|1051663683
Unknown10	|UInt32	|1060439283
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
FallingVelocityScale	|Single	|0
Unknown13	|UInt32	|0
BankAngle	|Angle	|{ Degrees: 35, Radians: 0.6108652 }
BankApplyTime	|Single	|4
BankDecayTime	|Single	|0.5
PitchRatio	|Single	|0.5
MaximumVelocity	|Single	|12
MaximumSidestepVelocity	|Single	|0.01
Acceleration	|Single	|12
Deceleration	|Single	|3.6
AngularVelocityMaximum	|Angle	|{ Degrees: 90, Radians: 1.570796 }
AngularAccelerationMaximum	|Angle	|{ Degrees: 90, Radians: 1.570796 }
CrouchVelocityModifier	|Single	|1
Unknown14	|UInt32	|0
ImpactDamage	|CachedTagInstance	|null
ImpactShieldDamage	|CachedTagInstance	|null
MetagameProperties	|TagBlock (MetagameProperties)	|0
DestroyAfterDeathTimeMin	|Single	|1
DestroyAfterDeathTimeMax	|Single	|3


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
ImportName	|StringId	|current_shield_damage
ExportName	|StringId	|shield_glow_source
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|


### Attachments

**0:**

Name	| Type	| Value
---	|---	|---	|
AtlasFlags	|Enum (AtlasFlagsValue)	|null
Attachment2	|CachedTagInstance (Effect)	|[[0x41D2] 0x000041D2](../Effect/41D2.md)
Marker	|StringId	|
ChangeColor	|Enum (ChangeColorValue)	|null
Unknown	|Int16	|0
PrimaryScale	|StringId	|shooting
SecondaryScale	|StringId	|


**1:**

Name	| Type	| Value
---	|---	|---	|
AtlasFlags	|Enum (AtlasFlagsValue)	|null
Attachment2	|CachedTagInstance (SoundLooping)	|[[0x41D3] 0x000041D3](../SoundLooping/41D3.md)
Marker	|StringId	|
ChangeColor	|Enum (ChangeColorValue)	|null
Unknown	|Int16	|0
PrimaryScale	|StringId	|
SecondaryScale	|StringId	|


### DeadSphereShapes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|
MaterialIndex	|SByte	|-1
Unknown	|SByte	|-1
GlobalMaterialIndex	|Int16	|0
RelativeMassScale	|Single	|0
Friction	|Single	|0
Restitution	|Single	|0
Volume	|Single	|0
Mass	|Single	|0
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|0
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown3	|Int32	|3
Radius	|Single	|0.275
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|32
Unknown8	|Int32	|12
Radius2	|Single	|0.275
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
TranslationI	|Single	|0
TranslationJ	|Single	|0
TranslationK	|Single	|0
TranslationRadius	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|
MaterialIndex	|SByte	|-1
Unknown	|SByte	|-1
GlobalMaterialIndex	|Int16	|0
RelativeMassScale	|Single	|0
Friction	|Single	|0
Restitution	|Single	|0
Volume	|Single	|0
Mass	|Single	|0
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|0
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|112
Unknown3	|Int32	|3
Radius	|Single	|0.37125
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|144
Unknown8	|Int32	|12
Radius2	|Single	|0.37125
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
TranslationI	|Single	|0
TranslationJ	|Single	|0
TranslationK	|Single	|0
TranslationRadius	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|
MaterialIndex	|SByte	|-1
Unknown	|SByte	|-1
GlobalMaterialIndex	|Int16	|0
RelativeMassScale	|Single	|0
Friction	|Single	|0
Restitution	|Single	|0
Volume	|Single	|0
Mass	|Single	|0
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|0
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|224
Unknown3	|Int32	|3
Radius	|Single	|0.4675
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|256
Unknown8	|Int32	|12
Radius2	|Single	|0.4675
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
TranslationI	|Single	|0
TranslationJ	|Single	|0
TranslationK	|Single	|0
TranslationRadius	|Single	|0


### SphereShapes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|
MaterialIndex	|SByte	|-1
Unknown	|SByte	|-1
GlobalMaterialIndex	|Int16	|0
RelativeMassScale	|Single	|0
Friction	|Single	|0
Restitution	|Single	|0
Volume	|Single	|0
Mass	|Single	|0
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|0
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown3	|Int32	|3
Radius	|Single	|0.275
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|32
Unknown8	|Int32	|12
Radius2	|Single	|0.275
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
TranslationI	|Single	|0
TranslationJ	|Single	|0
TranslationK	|Single	|0
TranslationRadius	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|
MaterialIndex	|SByte	|-1
Unknown	|SByte	|-1
GlobalMaterialIndex	|Int16	|0
RelativeMassScale	|Single	|0
Friction	|Single	|0
Restitution	|Single	|0
Volume	|Single	|0
Mass	|Single	|0
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|0
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|112
Unknown3	|Int32	|3
Radius	|Single	|0.275
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|144
Unknown8	|Int32	|12
Radius2	|Single	|0.275
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
TranslationI	|Single	|0
TranslationJ	|Single	|0
TranslationK	|Single	|0
TranslationRadius	|Single	|0


