# [0x3DCA] objects\characters\ambient_life\bird_quadwing2\bird_quadwing2

**Name:** ```objects\characters\ambient_life\bird_quadwing2\bird_quadwing2```

**Index:** ```0x3DCA```

**Tag Group:** ```Model (hlmt)```

## Fields

Name	| Type	| Value
---	|---	|---	|
RenderModel	|CachedTagInstance (RenderModel)	|[[0x3455] objects\characters\ambient_life\bird_quadwing\bird_quadwing](../RenderModel/3455.md)
CollisionModel	|CachedTagInstance (CollisionModel)	|[[0x3456] objects\characters\ambient_life\bird_quadwing\bird_quadwing](../CollisionModel/3456.md)
Animation	|CachedTagInstance (ModelAnimationGraph)	|[[0x3457] objects\characters\ambient_life\bird_quadwing\bird_quadwing](../ModelAnimationGraph/3457.md)
PhysicsModel	|CachedTagInstance	|null
ReduceToL1SuperLow	|Single	|100
ReduceToL2Low	|Single	|90
ReduceToL3Medium	|Single	|60
ReduceToL4High	|Single	|0
ReduceToL5SuperHigh	|Single	|0
LodModel	|CachedTagInstance	|null
Variants	|TagBlock (Variants)	|[1](#variants)
Unknown	|TagBlock (Unknown)	|0
InstanceGroups	|TagBlock (InstanceGroups)	|0
Materials	|TagBlock (Materials)	|[1](#materials)
NewDamageInfo	|TagBlock (NewDamageInfo)	|[1](#newdamageinfo)
Targets	|TagBlock (Targets)	|0
CollisionRegions	|TagBlock (CollisionRegions)	|[1](#collisionregions)
Nodes	|TagBlock (Nodes)	|[8](#nodes)
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

### Variants

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
VariantDialogue	|CachedTagInstance	|null
DefaultDialogEffect	|StringId	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
ModelRegion0Index	|SByte	|0
ModelRegion1Index	|SByte	|-1
ModelRegion2Index	|SByte	|-1
ModelRegion3Index	|SByte	|-1
ModelRegion4Index	|SByte	|-1
ModelRegion5Index	|SByte	|-1
ModelRegion6Index	|SByte	|-1
ModelRegion7Index	|SByte	|-1
ModelRegion8Index	|SByte	|-1
ModelRegion9Index	|SByte	|-1
ModelRegion10Index	|SByte	|-1
ModelRegion11Index	|SByte	|-1
ModelRegion12Index	|SByte	|-1
ModelRegion13Index	|SByte	|-1
ModelRegion14Index	|SByte	|-1
ModelRegion15Index	|SByte	|-1
Regions	|TagBlock (Variants_Regions)	|[1](#variants_regions)
Objects	|TagBlock (Variants_Objects)	|0
Unknown5	|Int32	|-1
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0


### Variants_Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|bird
RenderModelRegionIndex	|SByte	|0
Unknown	|SByte	|0
Unknown2	|SByte	|-1
Unknown3	|SByte	|-1
Permutations	|TagBlock (Variants_Regions_Permutations)	|[1](#variants_regions_permutations)
SortOrder	|Enum (SortOrderValue)	|null


### Variants_Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
RenderModelPermutationIndex	|SByte	|0
Unknown	|SByte	|0
Unknown2	|SByte	|0
Flags	|Enum (FlagsValue)	|null
Probability	|Single	|1
States	|TagBlock (Variants_Regions_Permutations_States)	|[1](#variants_regions_permutations_states)
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


### Variants_Regions_Permutations_States

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|
Unknown	|SByte	|-1
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|bird_quadwing
Unknown	|Int16	|0
DamageSectionIndex	|Int16	|0
Unknown2	|Int16	|0
Unknown3	|Int16	|-1
MaterialName	|StringId	|soft_organic_flesh
GlobalMaterialIndex	|Int16	|8
Unknown4	|Int16	|0


### NewDamageInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
GlobalIndirectMaterialName	|StringId	|soft_organic_flesh
IndirectDamageSection	|Int16	|0
Unknown	|Int16	|0
Unknown2	|UInt32	|0
CollisionDamageReportingType	|Enum (DamageReportingTypeValue)	|null
ResponseDamageReportingType	|Enum (DamageReportingTypeValue)	|null
Unknown3	|Int16	|3
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
MaxVitality	|Single	|10
MinStunDamage	|Single	|0
StunTime	|Single	|0
RechargeTime	|Single	|0
RechargeFraction	|Single	|1
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
Unknown19	|UInt32	|0
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|UInt32	|0
MaxShieldVitality	|Single	|0
GlobalShieldMaterialName	|StringId	|
MinStunDamage2	|Single	|0
StunTime2	|Single	|0
ShieldRechargeTime	|Single	|0
ShieldDamagedThreshold	|Single	|0
ShieldDamagedEffect	|CachedTagInstance	|null
ShieldDepletedEffect	|CachedTagInstance	|null
ShieldRechargingEffect	|CachedTagInstance	|null
DamageSections	|TagBlock (NewDamageInfo_DamageSections)	|[1](#newdamageinfo_damagesections)
Nodes	|TagBlock (NewDamageInfo_Nodes)	|[8](#newdamageinfo_nodes)
GlobalShieldMaterialIndex	|Int16	|-1
GlobalIndirectMaterialIndex	|Int16	|8
Unknown25	|UInt32	|1148846080
Unknown26	|UInt32	|0
DamageSeats	|TagBlock (NewDamageInfo_DamageSeats)	|0
DamageConstraints	|TagBlock (NewDamageInfo_DamageConstraints)	|0


### NewDamageInfo_DamageSections

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|bird
Flags	|Enum (FlagsValue)	|null
VitalityPercentage	|Single	|1
InstantResponses	|TagBlock (NewDamageInfo_DamageSections_InstantResponses)	|[1](#newdamageinfo_damagesections_instantresponses)
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
StunTime	|Single	|0
RechargeTime	|Single	|0
Unknown7	|UInt32	|0
ResurrectionRegionName	|StringId	|
RessurectionRegionRuntimeIndex	|Int16	|-1
Unknown8	|Int16	|0


### NewDamageInfo_DamageSections_InstantResponses

**0:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[[0x3458] objects\characters\ambient_life\bird_quadwing\bird_quadwing](../Effect/3458.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[[0x3459] objects\characters\ambient_life\bird_quadwing\bird_quadwing](../Effect/3459.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|bird
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|0
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|body
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


### NewDamageInfo_Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|2
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


### CollisionRegions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|bird
CollisionRegionIndex	|SByte	|0
PhysicsRegionIndex	|SByte	|0
Unknown	|SByte	|0
Unknown2	|SByte	|0
Permutations	|TagBlock (CollisionRegions_Permutations)	|[1](#collisionregions_permutations)


### CollisionRegions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|0
PhysicsPermutationIndex	|SByte	|0
Unknown	|SByte	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|body
ParentNode	|Int16	|-1
FirstChildNode	|Int16	|1
NextSiblingNode	|Int16	|-1
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|head
ParentNode	|Int16	|0
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|2
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0.2544834, Y: 0.0001406282, Z: -0.005047073 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lb_wing
ParentNode	|Int16	|0
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|3
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: -0.07763682, Y: 0.06880937, Z: 0.03315056 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lf_wing_base
ParentNode	|Int16	|0
FirstChildNode	|Int16	|6
NextSiblingNode	|Int16	|4
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0.0007931161, Y: 0.04829251, Z: 0.03376804 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|rb_wing
ParentNode	|Int16	|0
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|5
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: -0.09540945, Y: -0.06674572, Z: 0.02147358 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**5:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|rf_wing_base
ParentNode	|Int16	|0
FirstChildNode	|Int16	|7
NextSiblingNode	|Int16	|-1
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: -0.0006451154, Y: -0.04410723, Z: 0.03376804 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**6:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lf_wing_tip
ParentNode	|Int16	|3
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0.01004502, Y: 0.1822739, Z: 0.003130417 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


**7:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|rf_wing_tip
ParentNode	|Int16	|5
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0.01442535, Y: -0.1881468, Z: 0.00313038 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


### ModelObjectData

**0:**

Name	| Type	| Value
---	|---	|---	|
Type	|Enum (TypeValue)	|null
Unknown	|Int16	|0
Offset	|RealPoint3d	|{ X: -0.162875, Y: 0.001185, Z: -0.0105428 }
Radius	|Single	|1.05001


