# [0x2ECA] objects\multi\territories\territory_static

**Name:** ```objects\multi\territories\territory_static```

**Index:** ```0x2ECA```

**Tag Group:** ```Crate (bloc)```

## Fields

Name	| Type	| Value
---	|---	|---	|
ObjectTypeHaloOnline	|Enum (GameObjectTypeHalo3ODST)	|null
Unused1	|SByte	|0
ObjectFlags	|Enum (GameObjectFlags)	|null
BoundingRadius	|Single	|1.1
BoundingOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
AccelerationScale	|Single	|0
LightmapShadowMode	|Enum (LightmapShadowModeValue)	|null
SweetenerSize	|Enum (SweetenerSizeValue)	|null
WaterDensity	|Enum (WaterDensityValue)	|null
DynamicLightSphereRadius	|Single	|0
DynamicLightSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultModelVariant	|StringId	|
Model	|CachedTagInstance (Model)	|[[0x33B2] objects\multi\models\mp_flag_base\mp_flag_base](../Model/33B2.md)
CrateObject	|CachedTagInstance	|null
CollisionDamage	|CachedTagInstance	|null
EarlyMoverProperties	|TagBlock (EarlyMoverProperties)	|0
CreationEffect	|CachedTagInstance	|null
MaterialEffects	|CachedTagInstance	|null
ArmorSounds	|CachedTagInstance	|null
MeleeImpact	|CachedTagInstance	|null
AiProperties	|TagBlock (AiProperties)	|0
Functions	|TagBlock (Functions)	|0
HudTextMessageIndex	|Int16	|0
Attachments	|TagBlock (Attachments)	|0
Widgets	|TagBlock (Widgets)	|0
ChangeColors	|TagBlock (ChangeColors)	|0
NodeMaps	|TagBlock (NodeMaps)	|0
MultiplayerObjectProperties	|TagBlock (MultiplayerObjectProperties)	|[1](#multiplayerobjectproperties)
RevivingEquipment	|TagBlock (RevivingEquipment)	|0
ModelObjectData	|TagBlock (ModelObjectData)	|[1](#modelobjectdata)
Flags2	|UInt16	|0
Unknown6	|Int16	|0
MetagameProperties	|TagBlock (MetagameProperties)	|0
Unknown7	|SByte	|0
Unknown8	|SByte	|0
Unknown9	|SByte	|0
Unknown10	|SByte	|0


## Tag Blocks

### MultiplayerObjectProperties

**0:**

Name	| Type	| Value
---	|---	|---	|
EngineFlags	|Enum (EngineFlagsValue)	|null
ObjectType	|Enum (ObjectTypeValue)	|null
TeleporterFlags	|Byte	|0
Unknown	|SByte	|8
Flags	|Byte	|0
Shape	|Enum (ObjectShapeValue)	|null
SpawnTimerMode	|Enum (SpawnTimerModeValue)	|null
SpawnTime	|Int16	|0
UnknownSpawnTime	|Int16	|0
RadiusWidth	|Single	|2
Length	|Single	|0
Top	|Single	|1
Bottom	|Single	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int32	|0
Unknown6	|Int32	|0
ChildObject	|CachedTagInstance (Scenery)	|[[0x33C3] 0x000033C3](../Scenery/33C3.md)
Unknown7	|Int32	|0
ShapeShader	|CachedTagInstance (ShaderHalogram)	|[[0x15DA] objects\multi\shaders\koth_shield](../ShaderHalogram/15DA.md)
UnknownShader	|CachedTagInstance (ShaderHalogram)	|[[0x15DA] objects\multi\shaders\koth_shield](../ShaderHalogram/15DA.md)
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
Offset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
Radius	|Single	|1.1


