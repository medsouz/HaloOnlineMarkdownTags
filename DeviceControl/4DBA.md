# 0x4DBA

**Index:** ```0x4DBA```

**Tag Group:** ```DeviceControl (ctrl)```

## Fields

Name	| Type	| Value
---	|---	|---	|
ObjectTypeHaloOnline	|Enum (GameObjectTypeHalo3ODST)	|null
Unused1	|SByte	|0
ObjectFlags	|Enum (GameObjectFlags)	|null
BoundingRadius	|Single	|0.35
BoundingOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0.365 }
AccelerationScale	|Single	|0
LightmapShadowMode	|Enum (LightmapShadowModeValue)	|null
SweetenerSize	|Enum (SweetenerSizeValue)	|null
WaterDensity	|Enum (WaterDensityValue)	|null
DynamicLightSphereRadius	|Single	|0
DynamicLightSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultModelVariant	|StringId	|
Model	|CachedTagInstance (Model)	|[0x4DBB](../Model/4DBB.md)
CrateObject	|CachedTagInstance	|null
CollisionDamage	|CachedTagInstance	|null
EarlyMoverProperties	|TagBlock (EarlyMoverProperties)	|0
CreationEffect	|CachedTagInstance	|null
MaterialEffects	|CachedTagInstance	|null
ArmorSounds	|CachedTagInstance	|null
MeleeImpact	|CachedTagInstance	|null
AiProperties	|TagBlock (AiProperties)	|0
Functions	|TagBlock (Functions)	|[3](#functions)
HudTextMessageIndex	|Int16	|0
Attachments	|TagBlock (Attachments)	|0
Widgets	|TagBlock (Widgets)	|0
ChangeColors	|TagBlock (ChangeColors)	|0
NodeMaps	|TagBlock (NodeMaps)	|0
MultiplayerObjectProperties	|TagBlock (MultiplayerObjectProperties)	|0
RevivingEquipment	|TagBlock (RevivingEquipment)	|0
ModelObjectData	|TagBlock (ModelObjectData)	|0
Flags2	|UInt32	|0
PowerTransitionTime	|Single	|0
PowerAccelerationTime	|Single	|900
PositionTransitionTime	|Single	|0.2
PositionAccelerationTime	|Single	|900
DepoweredPositionTransitionTime	|Single	|0
DepoweredPositionAccelerationTime	|Single	|900
LightmapFlags	|UInt32	|0
OpenUp	|CachedTagInstance	|null
CloseDown	|CachedTagInstance	|null
Opened	|CachedTagInstance	|null
Closed	|CachedTagInstance	|null
Depowered	|CachedTagInstance	|null
Repowered	|CachedTagInstance	|null
DelayTime	|Single	|0
DelayEffect	|CachedTagInstance	|null
AutomaticActivationRadius	|Single	|0
Type	|Enum (TypeValue)	|null
TriggersWhen	|Enum (TriggersWhenValue)	|null
CallValue	|Single	|0
ActionString	|StringId	|zanzibar_gate_action
On	|CachedTagInstance	|null
Off	|CachedTagInstance	|null
Deny	|CachedTagInstance	|null
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0


## Tag Blocks

### Functions

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|one
ExportName	|StringId	|flash
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|change_in_position


**1:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|one
ExportName	|StringId	|index_flash
TurnOffWith	|StringId	|position
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|scalar


**2:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|position
ExportName	|StringId	|scalar
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|


