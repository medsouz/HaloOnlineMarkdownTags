# [0x3DBB] 0x00003DBB

**Name:** ```0x00003DBB```

**Index:** ```0x3DBB```

**Tag Group:** ```Model (hlmt)```

## Fields

Name	| Type	| Value
---	|---	|---	|
RenderModel	|CachedTagInstance (RenderModel)	|[[0x3DBC] 0x00003DBC](../RenderModel/3DBC.md)
CollisionModel	|CachedTagInstance	|null
Animation	|CachedTagInstance	|null
PhysicsModel	|CachedTagInstance (PhysicsModel)	|[[0x3DBD] 0x00003DBD](../PhysicsModel/3DBD.md)
ReduceToL1SuperLow	|Single	|298.4272
ReduceToL2Low	|Single	|223.8204
ReduceToL3Medium	|Single	|0
ReduceToL4High	|Single	|0
ReduceToL5SuperHigh	|Single	|0
LodModel	|CachedTagInstance	|null
Variants	|TagBlock (Variants)	|0
Unknown	|TagBlock (Unknown)	|0
InstanceGroups	|TagBlock (InstanceGroups)	|0
Materials	|TagBlock (Materials)	|0
NewDamageInfo	|TagBlock (NewDamageInfo)	|0
Targets	|TagBlock (Targets)	|0
CollisionRegions	|TagBlock (CollisionRegions)	|[1](#collisionregions)
Nodes	|TagBlock (Nodes)	|[1](#nodes)
Unknown2	|UInt32	|0
ModelObjectData	|TagBlock (ModelObjectData)	|[1](#modelobjectdata)
PrimaryDialogue	|CachedTagInstance	|null
SecondaryDialogue	|CachedTagInstance	|null
Flags	|Enum (FlagsValue)	|null
DefaultDialogueEffect	|StringId	|
RenderOnlyNodeFlags1	|Enum (RenderOnlyNodeFlags1Value)	|null
RenderOnlyNodeFlags2	|Enum (RenderOnlyNodeFlags2Value)	|null
RenderOnlyNodeFlags3	|Enum (RenderOnlyNodeFlags3Value)	|null
RenderOnlyNodeFlags4	|Enum (RenderOnlyNodeFlags4Value)	|null
RenderOnlyNodeFlags5	|Enum (RenderOnlyNodeFlags5Value)	|null
RenderOnlyNodeFlags6	|Enum (RenderOnlyNodeFlags6Value)	|null
RenderOnlyNodeFlags7	|Enum (RenderOnlyNodeFlags7Value)	|null
RenderOnlyNodeFlags8	|Enum (RenderOnlyNodeFlags8Value)	|null
RenderOnlySectionFlags1	|Enum (RenderOnlySectionFlags1Value)	|null
RenderOnlySectionFlags2	|Enum (RenderOnlySectionFlags2Value)	|null
RenderOnlySectionFlags3	|Enum (RenderOnlySectionFlags3Value)	|null
RenderOnlySectionFlags4	|Enum (RenderOnlySectionFlags4Value)	|null
RenderOnlySectionFlags5	|Enum (RenderOnlySectionFlags5Value)	|null
RenderOnlySectionFlags6	|Enum (RenderOnlySectionFlags6Value)	|null
RenderOnlySectionFlags7	|Enum (RenderOnlySectionFlags7Value)	|null
RenderOnlySectionFlags8	|Enum (RenderOnlySectionFlags8Value)	|null
RuntimeFlags	|Enum (RuntimeFlagsValue)	|null
ScenarioLoadParametersBlock	|Single	|0
ScenarioLoadParametersBlock2	|Single	|0
ScenarioLoadParametersBlock3	|Single	|0
Unknown4	|Int16	|0
Unknown5	|Int16	|0
Unknown6	|TagBlock (Unknown6)	|0
Unknown7	|TagBlock (Unknown7)	|0
Unknown8	|TagBlock (Unknown8)	|0
ShieldImpactThirdPerson	|CachedTagInstance	|null
ShieldImpactFirstPerson	|CachedTagInstance	|null
OvershieldThirdPerson	|CachedTagInstance	|null
OvershieldFirstPerson	|CachedTagInstance	|null


## Tag Blocks

### CollisionRegions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
CollisionRegionIndex	|SByte	|-1
PhysicsRegionIndex	|SByte	|0
Unknown	|SByte	|0
Unknown2	|SByte	|0
Permutations	|TagBlock (CollisionRegions_Permutations)	|[1](#collisionregions_permutations)


### CollisionRegions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|-1
PhysicsPermutationIndex	|SByte	|0
Unknown	|SByte	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lift
ParentNode	|Int16	|-1
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


### ModelObjectData

**0:**

Name	| Type	| Value
---	|---	|---	|
Type	|Enum (TypeValue)	|null
Unknown	|Int16	|0
Offset	|RealPoint3d	|{ X: 0.00760373, Y: 1.21272, Z: 2.28738 }
Radius	|Single	|3.73034


