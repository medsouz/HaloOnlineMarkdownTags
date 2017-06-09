# 0x4DFB

**Index:** ```0x4DFB```

**Tag Group:** ```Model (hlmt)```

## Fields

Name	| Type	| Value
---	|---	|---	|
RenderModel	|CachedTagInstance (RenderModel)	|[0x47F4](../RenderModel/47F4.md)
CollisionModel	|CachedTagInstance (CollisionModel)	|[0x47FA](../CollisionModel/47FA.md)
Animation	|CachedTagInstance	|null
PhysicsModel	|CachedTagInstance (PhysicsModel)	|[0x47FB](../PhysicsModel/47FB.md)
ReduceToL1SuperLow	|Single	|70
ReduceToL2Low	|Single	|64
ReduceToL3Medium	|Single	|0
ReduceToL4High	|Single	|0
ReduceToL5SuperHigh	|Single	|0
LodModel	|CachedTagInstance	|null
Variants	|TagBlock (Variants)	|[1](#variants)
Unknown	|TagBlock (Unknown)	|0
InstanceGroups	|TagBlock (InstanceGroups)	|0
Materials	|TagBlock (Materials)	|[4](#materials)
NewDamageInfo	|TagBlock (NewDamageInfo)	|[1](#newdamageinfo)
Targets	|TagBlock (Targets)	|0
CollisionRegions	|TagBlock (CollisionRegions)	|[4](#collisionregions)
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

### Variants

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
VariantDialogue	|CachedTagInstance	|null
DefaultDialogEffect	|StringId	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
ModelRegion0Index	|SByte	|3
ModelRegion1Index	|SByte	|2
ModelRegion2Index	|SByte	|0
ModelRegion3Index	|SByte	|1
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
Regions	|TagBlock (Variants_Regions)	|[4](#variants_regions)
Objects	|TagBlock (Variants_Objects)	|0
Unknown5	|Int32	|-1
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0


### Variants_Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|left
RenderModelRegionIndex	|SByte	|2
Unknown	|SByte	|0
Unknown2	|SByte	|-1
Unknown3	|SByte	|-1
Permutations	|TagBlock (Variants_Regions_Permutations)	|[1](#variants_regions_permutations)
SortOrder	|Enum (SortOrderValue)	|null


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|right
RenderModelRegionIndex	|SByte	|3
Unknown	|SByte	|0
Unknown2	|SByte	|-1
Unknown3	|SByte	|-1
Permutations	|TagBlock (Variants_Regions_Permutations)	|[1](#variants_regions_permutations)
SortOrder	|Enum (SortOrderValue)	|null


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|front
RenderModelRegionIndex	|SByte	|1
Unknown	|SByte	|0
Unknown2	|SByte	|-1
Unknown3	|SByte	|-1
Permutations	|TagBlock (Variants_Regions_Permutations)	|[1](#variants_regions_permutations)
SortOrder	|Enum (SortOrderValue)	|null


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|back
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
RenderModelPermutationIndex	|SByte	|1
Unknown	|SByte	|0
Unknown2	|SByte	|0
Flags	|Enum (FlagsValue)	|null
Probability	|Single	|1
States	|TagBlock (Variants_Regions_Permutations_States)	|[2](#variants_regions_permutations_states)
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
RenderModelPermutationIndex	|SByte	|1
Unknown	|SByte	|0
Unknown2	|SByte	|0
Flags	|Enum (FlagsValue)	|null
Probability	|Single	|1
States	|TagBlock (Variants_Regions_Permutations_States)	|[2](#variants_regions_permutations_states)
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
RenderModelPermutationIndex	|SByte	|1
Unknown	|SByte	|0
Unknown2	|SByte	|0
Flags	|Enum (FlagsValue)	|null
Probability	|Single	|1
States	|TagBlock (Variants_Regions_Permutations_States)	|[2](#variants_regions_permutations_states)
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
RenderModelPermutationIndex	|SByte	|1
Unknown	|SByte	|0
Unknown2	|SByte	|0
Flags	|Enum (FlagsValue)	|null
Probability	|Single	|1
States	|TagBlock (Variants_Regions_Permutations_States)	|[2](#variants_regions_permutations_states)
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0


### Variants_Regions_Permutations_States

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Unknown	|SByte	|0
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Unknown	|SByte	|2
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Unknown	|SByte	|0
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Unknown	|SByte	|2
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Unknown	|SByte	|0
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Unknown	|SByte	|2
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Unknown	|SByte	|0
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Unknown	|SByte	|2
PropertyFlags	|Enum (PropertyFlagsValue)	|null
State2	|Enum (StateValue)	|null
LoopingEffect	|CachedTagInstance	|null
LoopingEffectMarkerName	|StringId	|
InitialProbability	|Single	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|back
Unknown	|Int16	|0
DamageSectionIndex	|Int16	|3
Unknown2	|Int16	|0
Unknown3	|Int16	|-1
MaterialName	|StringId	|hard_terrain_concrete
GlobalMaterialIndex	|Int16	|104
Unknown4	|Int16	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|front
Unknown	|Int16	|0
DamageSectionIndex	|Int16	|2
Unknown2	|Int16	|1
Unknown3	|Int16	|-1
MaterialName	|StringId	|hard_terrain_concrete
GlobalMaterialIndex	|Int16	|104
Unknown4	|Int16	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|left
Unknown	|Int16	|0
DamageSectionIndex	|Int16	|0
Unknown2	|Int16	|2
Unknown3	|Int16	|-1
MaterialName	|StringId	|hard_terrain_concrete
GlobalMaterialIndex	|Int16	|104
Unknown4	|Int16	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|right
Unknown	|Int16	|0
DamageSectionIndex	|Int16	|1
Unknown2	|Int16	|3
Unknown3	|Int16	|-1
MaterialName	|StringId	|hard_terrain_concrete
GlobalMaterialIndex	|Int16	|104
Unknown4	|Int16	|0


### NewDamageInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
GlobalIndirectMaterialName	|StringId	|hard_terrain_concrete
IndirectDamageSection	|Int16	|4
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
MaxVitality	|Single	|500
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
MaxShieldVitality	|Single	|20
GlobalShieldMaterialName	|StringId	|
MinStunDamage2	|Single	|0
StunTime2	|Single	|0
ShieldRechargeTime	|Single	|10
ShieldDamagedThreshold	|Single	|0
ShieldDamagedEffect	|CachedTagInstance	|null
ShieldDepletedEffect	|CachedTagInstance	|null
ShieldRechargingEffect	|CachedTagInstance	|null
DamageSections	|TagBlock (NewDamageInfo_DamageSections)	|[5](#newdamageinfo_damagesections)
Nodes	|TagBlock (NewDamageInfo_Nodes)	|[1](#newdamageinfo_nodes)
GlobalShieldMaterialIndex	|Int16	|-1
GlobalIndirectMaterialIndex	|Int16	|104
Unknown25	|UInt32	|1036831949
Unknown26	|UInt32	|0
DamageSeats	|TagBlock (NewDamageInfo_DamageSeats)	|0
DamageConstraints	|TagBlock (NewDamageInfo_DamageConstraints)	|0


### NewDamageInfo_DamageSections

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|left
Flags	|Enum (FlagsValue)	|null
VitalityPercentage	|Single	|0.25
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


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|right
Flags	|Enum (FlagsValue)	|null
VitalityPercentage	|Single	|0.25
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


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|front
Flags	|Enum (FlagsValue)	|null
VitalityPercentage	|Single	|0.25
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


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|back
Flags	|Enum (FlagsValue)	|null
VitalityPercentage	|Single	|0.25
InstantResponses	|TagBlock (NewDamageInfo_DamageSections_InstantResponses)	|[2](#newdamageinfo_damagesections_instantresponses)
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


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|all
Flags	|Enum (FlagsValue)	|null
VitalityPercentage	|Single	|0.2
InstantResponses	|TagBlock (NewDamageInfo_DamageSections_InstantResponses)	|[5](#newdamageinfo_damagesections_instantresponses)
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
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x47FC](../Effect/47FC.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|left
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|2
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|left_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4808](../Effect/4808.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|right
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|3
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|right_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x480E](../Effect/480E.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|front
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|1
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|front_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4814](../Effect/4814.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|back
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|0
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|back_chunk_2
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4814](../Effect/4814.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|-1
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|back_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4814](../Effect/4814.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|back
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|0
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|back_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x480E](../Effect/480E.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|front
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|1
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|front_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4808](../Effect/4808.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|right
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|3
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|right_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x47FC](../Effect/47FC.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|left
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|2
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|left_chunk
DamageEffectMarkerName	|StringId	|
ResponseDelay	|Single	|0
DelayEffect	|CachedTagInstance	|null
DelayEffectMarkerName	|StringId	|
EjectingSeatLabel	|StringId	|
SkipFraction	|Single	|0
DestroyedChildObjectMarkerName	|StringId	|
TotalDamageThreshold	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
ConstraintDamageType	|Enum (ConstraintDamageTypeValue)	|null
Trigger	|StringId	|
Flags	|Enum (FlagsValue)	|null
DamageThreshold	|Single	|0.1
PrimaryTransitionEffect	|CachedTagInstance (Effect)	|[0x47FC](../Effect/47FC.md)
SecondaryTransitionEffect	|CachedTagInstance (Effect)	|[0x4802](../Effect/4802.md)
TransitionDamageEffect	|CachedTagInstance	|null
Region	|StringId	|left
NewState	|Enum (NewStateValue)	|null
RuntimeRegionIndex	|Int16	|2
SecondaryRegion	|StringId	|
SecondaryNewState	|Enum (SecondaryNewStateValue)	|null
SecondaryRuntimeRegionIndex	|Int16	|-1
Unknown	|Int16	|-1
UnknownSpecialDamage	|Enum (UnknownSpecialDamageValue)	|null
SpecialDamageCase	|StringId	|
EffectMarkerName	|StringId	|left_chunk
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


### CollisionRegions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|back
CollisionRegionIndex	|SByte	|0
PhysicsRegionIndex	|SByte	|-1
Unknown	|SByte	|0
Unknown2	|SByte	|0
Permutations	|TagBlock (CollisionRegions_Permutations)	|[3](#collisionregions_permutations)


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|front
CollisionRegionIndex	|SByte	|1
PhysicsRegionIndex	|SByte	|0
Unknown	|SByte	|0
Unknown2	|SByte	|0
Permutations	|TagBlock (CollisionRegions_Permutations)	|[3](#collisionregions_permutations)


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|left
CollisionRegionIndex	|SByte	|2
PhysicsRegionIndex	|SByte	|1
Unknown	|SByte	|0
Unknown2	|SByte	|0
Permutations	|TagBlock (CollisionRegions_Permutations)	|[3](#collisionregions_permutations)


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|right
CollisionRegionIndex	|SByte	|3
PhysicsRegionIndex	|SByte	|2
Unknown	|SByte	|0
Unknown2	|SByte	|0
Permutations	|TagBlock (CollisionRegions_Permutations)	|[3](#collisionregions_permutations)


### CollisionRegions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|1
PhysicsPermutationIndex	|SByte	|-1
Unknown	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|0
PhysicsPermutationIndex	|SByte	|-1
Unknown	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|2
PhysicsPermutationIndex	|SByte	|-1
Unknown	|SByte	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|1
PhysicsPermutationIndex	|SByte	|1
Unknown	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|0
PhysicsPermutationIndex	|SByte	|0
Unknown	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|2
PhysicsPermutationIndex	|SByte	|1
Unknown	|SByte	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|1
PhysicsPermutationIndex	|SByte	|1
Unknown	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|0
PhysicsPermutationIndex	|SByte	|0
Unknown	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|2
PhysicsPermutationIndex	|SByte	|2
Unknown	|SByte	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|minor
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|1
PhysicsPermutationIndex	|SByte	|1
Unknown	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|0
PhysicsPermutationIndex	|SByte	|0
Unknown	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|med
Flags	|Enum (FlagsValue)	|null
CollisionPermutationIndex	|SByte	|2
PhysicsPermutationIndex	|SByte	|2
Unknown	|SByte	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|jersey_barrier
ParentNode	|Int16	|-1
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
ImportNodeIndex	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0.0004057014, Y: -0.0001192403, Z: -5E-05 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
Inverse	|RealMatrix4x3	|BlamCore.Common.RealMatrix4x3


### ModelObjectData

**0:**

Name	| Type	| Value
---	|---	|---	|
Type	|Enum (TypeValue)	|null
Unknown	|Int16	|0
Offset	|RealPoint3d	|{ X: -0.00148086, Y: 0.00939041, Z: 0.328142 }
Radius	|Single	|0.821311


