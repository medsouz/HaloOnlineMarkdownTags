# [0x2EAC] objects\multi\powerups\powerup_yellow\powerup_yellow

**Name:** ```objects\multi\powerups\powerup_yellow\powerup_yellow```

**Index:** ```0x2EAC```

**Tag Group:** ```Equipment (eqip)```

## Fields

Name	| Type	| Value
---	|---	|---	|
ObjectTypeHaloOnline	|Enum (GameObjectTypeHalo3ODST)	|null
Unused1	|SByte	|0
ObjectFlags	|Enum (GameObjectFlags)	|null
BoundingRadius	|Single	|0.3
BoundingOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0.35 }
AccelerationScale	|Single	|0.5
LightmapShadowMode	|Enum (LightmapShadowModeValue)	|null
SweetenerSize	|Enum (SweetenerSizeValue)	|null
WaterDensity	|Enum (WaterDensityValue)	|null
DynamicLightSphereRadius	|Single	|0
DynamicLightSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultModelVariant	|StringId	|
Model	|CachedTagInstance (Model)	|[[0x31B6] 0x000031B6](../Model/31B6.md)
CrateObject	|CachedTagInstance	|null
CollisionDamage	|CachedTagInstance	|null
EarlyMoverProperties	|TagBlock (EarlyMoverProperties)	|0
CreationEffect	|CachedTagInstance	|null
MaterialEffects	|CachedTagInstance	|null
ArmorSounds	|CachedTagInstance	|null
MeleeImpact	|CachedTagInstance	|null
AiProperties	|TagBlock (AiProperties)	|0
Functions	|TagBlock (Functions)	|[1](#functions)
HudTextMessageIndex	|Int16	|0
Attachments	|TagBlock (Attachments)	|[2](#attachments)
Widgets	|TagBlock (Widgets)	|0
ChangeColors	|TagBlock (ChangeColors)	|0
NodeMaps	|TagBlock (NodeMaps)	|0
MultiplayerObjectProperties	|TagBlock (MultiplayerObjectProperties)	|[1](#multiplayerobjectproperties)
RevivingEquipment	|TagBlock (RevivingEquipment)	|0
ModelObjectData	|TagBlock (ModelObjectData)	|[1](#modelobjectdata)
Flags2	|UInt32	|0
OldMessageIndex	|Int16	|30
SortOrder	|Int16	|0
OldMultiplayerOnGroundScale	|Single	|0
OldCampaignOnGroundScale	|Single	|0
PickupMessage	|StringId	|
SwapMessage	|StringId	|
PickupOrDualWieldMessage	|StringId	|
SwapOrDualWieldMessage	|StringId	|
PickedUpMessage	|StringId	|powerup_pickup_yellow
SwitchToMessage	|StringId	|
SwitchToFromAiMessage	|StringId	|
AllWeaponsEmptyMessage	|StringId	|
CollisionSound	|CachedTagInstance	|null
PredictedBitmaps	|TagBlock (PredictedBitmaps)	|0
DetonationDamageEffect	|CachedTagInstance	|null
DetonationDelayMin	|Single	|0
DetonationDelayMax	|Single	|0
DetonatingEffect	|CachedTagInstance	|null
DetonationEffect	|CachedTagInstance	|null
CampaignGroundScale	|Single	|0
MultiplayerGroundScale	|Single	|0
SmallHoldScale	|Single	|0
SmallHolsterScale	|Single	|0
MediumHoldScale	|Single	|0
MediumHolsterScale	|Single	|0
LargeHoldScale	|Single	|0
LargeHolsterScale	|Single	|0
HugeHoldScale	|Single	|0
HugeHolsterScale	|Single	|0
GroundedFrictionLength	|Single	|5
GroundedFrictionUnknown	|Single	|2
UseDuration	|Single	|0
Unknown8	|UInt32	|0
NumberOfUses	|Int16	|1
Flags3	|UInt16	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
EquipmentCamera	|TagBlock (EquipmentCamera)	|0
HealthPack	|TagBlock (HealthPack)	|0
Powerup	|TagBlock (Powerup)	|[1](#powerup)
ObjectCreation	|TagBlock (ObjectCreation)	|0
Destruction	|TagBlock (Destruction)	|0
RadarManipulation	|TagBlock (RadarManipulation)	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Invisibility	|TagBlock (Invisibility)	|0
Invincibility	|TagBlock (Invincibility)	|0
Regenerator	|TagBlock (Regenerator)	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
ForcedReload	|TagBlock (ForcedReload)	|0
ConcussiveBlast	|TagBlock (ConcussiveBlast)	|0
TankMode	|TagBlock (TankMode)	|0
MagPulse	|TagBlock (MagPulse)	|0
Hologram	|TagBlock (Hologram)	|0
ReactiveArmor	|TagBlock (ReactiveArmor)	|0
BombRun	|TagBlock (BombRun)	|0
ArmorLock	|TagBlock (ArmorLock)	|0
Adrenaline	|TagBlock (Adrenaline)	|0
LightningStrike	|TagBlock (LightningStrike)	|0
Scrambler	|TagBlock (Scrambler)	|0
WeaponJammer	|TagBlock (WeaponJammer)	|0
AmmoPack	|TagBlock (AmmoPack)	|0
Vision	|TagBlock (Vision)	|0
HudInterface	|CachedTagInstance	|null
PickupSound	|CachedTagInstance (Sound)	|[[0x31B8] 0x000031B8](../Sound/31B8.md)
EmptySound	|CachedTagInstance	|null
ActivationEffect	|CachedTagInstance	|null
ActiveEffect	|CachedTagInstance	|null
DeactivationEffect	|CachedTagInstance	|null
EnterAnimation	|StringId	|
IdleAnimation	|StringId	|
ExitAnimation	|StringId	|


## Tag Blocks

### Functions

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
ImportName	|StringId	|one
ExportName	|StringId	|one
TurnOffWith	|StringId	|
MinimumValue	|Single	|0
DefaultFunction	|Byte[]	|System.Byte[]
ScaleBy	|StringId	|


### Attachments

**0:**

Name	| Type	| Value
---	|---	|---	|
AtlasFlags	|Enum (AtlasFlagsValue)	|null
Attachment2	|CachedTagInstance (Effect)	|[[0x31B7] 0x000031B7](../Effect/31B7.md)
Marker	|StringId	|
ChangeColor	|Enum (ChangeColorValue)	|null
Unknown	|Int16	|0
PrimaryScale	|StringId	|
SecondaryScale	|StringId	|


**1:**

Name	| Type	| Value
---	|---	|---	|
AtlasFlags	|Enum (AtlasFlagsValue)	|null
Attachment2	|CachedTagInstance (SoundLooping)	|[[0x1B51] 0x00001B51](../SoundLooping/1B51.md)
Marker	|StringId	|
ChangeColor	|Enum (ChangeColorValue)	|null
Unknown	|Int16	|0
PrimaryScale	|StringId	|one
SecondaryScale	|StringId	|


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
SpawnTime	|Int16	|30
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
Offset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0.35 }
Radius	|Single	|0.3


### Powerup

**0:**

Name	| Type	| Value
---	|---	|---	|
PowerupTraitSet	|Enum (PowerupTraitSetValue)	|null


