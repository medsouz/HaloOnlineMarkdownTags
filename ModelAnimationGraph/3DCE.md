# [0x3DCE] 0x00003DCE

**Name:** ```0x00003DCE```

**Index:** ```0x3DCE```

**Tag Group:** ```ModelAnimationGraph (jmad)```

## Fields

Name	| Type	| Value
---	|---	|---	|
ParentAnimationGraph	|CachedTagInstance	|null
InheritanceFlags	|Enum (AnimationInheritanceFlags)	|null
PrivateFlags	|Enum (AnimationPrivateFlags)	|null
AnimationCodecPack	|Int16	|6
SkeletonNodes	|TagBlock (SkeletonNodes)	|[6](#skeletonnodes)
SoundReferences	|TagBlock (SoundReferences)	|0
EffectReferences	|TagBlock (EffectReferences)	|0
BlendScreens	|TagBlock (BlendScreens)	|0
Legs	|TagBlock (Legs)	|0
Animations	|TagBlock (Animations)	|[3](#animations)
Modes	|TagBlock (Modes)	|[1](#modes)
VehicleSuspension	|TagBlock (VehicleSuspension)	|0
ObjectOverlays	|TagBlock (ObjectOverlays)	|0
InheritanceList	|TagBlock (InheritanceList)	|0
WeaponList	|TagBlock (WeaponList)	|[1](#weaponlist)
LeftArmNodes	|UInt32[]	|System.UInt32[]
RightArmNodes	|UInt32[]	|System.UInt32[]
LastImportResults	|Byte[]	|System.Byte[]
AdditionalNodeData	|TagBlock (AdditionalNodeData)	|0
ResourceGroups	|TagBlock (ResourceGroups)	|[1](#resourcegroups)


## Tag Blocks

### SkeletonNodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|body
NextSiblingNodeIndex	|Int16	|-1
FirstChildNodeIndex	|Int16	|1
ParentNodeIndex	|Int16	|-1
ModelFlags	|Enum (SkeletonModelFlags)	|null
NodeJointFlags	|Enum (SkeletonNodeJointFlags)	|null
BaseVector	|RealVector3d	|{ I: 0, J: 0, K: 0 }
VectorRange	|Single	|0
ZPosition	|Single	|0.0416038


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|feet
NextSiblingNodeIndex	|Int16	|2
FirstChildNodeIndex	|Int16	|-1
ParentNodeIndex	|Int16	|0
ModelFlags	|Enum (SkeletonModelFlags)	|null
NodeJointFlags	|Enum (SkeletonNodeJointFlags)	|null
BaseVector	|RealVector3d	|{ I: 0, J: 0, K: 0 }
VectorRange	|Single	|0
ZPosition	|Single	|0.002901781


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_left
NextSiblingNodeIndex	|Int16	|3
FirstChildNodeIndex	|Int16	|4
ParentNodeIndex	|Int16	|0
ModelFlags	|Enum (SkeletonModelFlags)	|null
NodeJointFlags	|Enum (SkeletonNodeJointFlags)	|null
BaseVector	|RealVector3d	|{ I: 0, J: 0, K: 0 }
VectorRange	|Single	|0
ZPosition	|Single	|0.004085787


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_right
NextSiblingNodeIndex	|Int16	|-1
FirstChildNodeIndex	|Int16	|5
ParentNodeIndex	|Int16	|0
ModelFlags	|Enum (SkeletonModelFlags)	|null
NodeJointFlags	|Enum (SkeletonNodeJointFlags)	|null
BaseVector	|RealVector3d	|{ I: 0, J: 0, K: 0 }
VectorRange	|Single	|0
ZPosition	|Single	|0.003988549


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_left_tip
NextSiblingNodeIndex	|Int16	|-1
FirstChildNodeIndex	|Int16	|-1
ParentNodeIndex	|Int16	|2
ModelFlags	|Enum (SkeletonModelFlags)	|null
NodeJointFlags	|Enum (SkeletonNodeJointFlags)	|null
BaseVector	|RealVector3d	|{ I: 0, J: 0, K: 0 }
VectorRange	|Single	|0
ZPosition	|Single	|-0.0004455745


**5:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_right_tip
NextSiblingNodeIndex	|Int16	|-1
FirstChildNodeIndex	|Int16	|-1
ParentNodeIndex	|Int16	|3
ModelFlags	|Enum (SkeletonModelFlags)	|null
NodeJointFlags	|Enum (SkeletonNodeJointFlags)	|null
BaseVector	|RealVector3d	|{ I: 0, J: 0, K: 0 }
VectorRange	|Single	|0
ZPosition	|Single	|-0.0002712496


### Animations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|combat:unarmed:idle:var0
Weight	|Single	|0.5
LoopFrameIndex	|Int16	|0
PlaybackFlags	|UInt16	|0
BlendScreen	|SByte	|-1
DesiredCompression	|Enum (CompressionValue)	|null
CurrentCompression	|Enum (CompressionValue)	|null
NodeCount	|SByte	|6
FrameCount	|Int16	|30
Type	|Enum (FrameType)	|null
FrameInfoType	|Enum (FrameMovementDataType)	|null
ProductionFlags	|UInt16	|0
InternalFlags	|UInt16	|128
NodeListChecksum	|Int32	|537443583
ProductionChecksum	|Int32	|-443994834
Unknown	|Int16	|5
Unknown2	|Int16	|6
PreviousVariantSibling	|Int16	|-1
NextVariantSibling	|Int16	|1
ResourceGroupIndex	|Int16	|0
ResourceGroupMemberIndex	|Int16	|0
FrameEvents	|TagBlock (Animations_FrameEvents)	|0
SoundEvents	|TagBlock (Animations_SoundEvents)	|0
EffectEvents	|TagBlock (Animations_EffectEvents)	|0
DialogueEvents	|TagBlock (Animations_DialogueEvents)	|0
ObjectSpaceParentNodes	|TagBlock (Animations_ObjectSpaceParentNodes)	|0
LegAnchoring	|TagBlock (Animations_LegAnchoring)	|0
Unknown4	|Single	|1
Unknown5	|Single	|0
Unknown6	|Single	|0
Unknown7	|Single	|0
Unknown8	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|combat:unarmed:idle:var1
Weight	|Single	|1
LoopFrameIndex	|Int16	|0
PlaybackFlags	|UInt16	|0
BlendScreen	|SByte	|-1
DesiredCompression	|Enum (CompressionValue)	|null
CurrentCompression	|Enum (CompressionValue)	|null
NodeCount	|SByte	|6
FrameCount	|Int16	|80
Type	|Enum (FrameType)	|null
FrameInfoType	|Enum (FrameMovementDataType)	|null
ProductionFlags	|UInt16	|0
InternalFlags	|UInt16	|128
NodeListChecksum	|Int32	|537443583
ProductionChecksum	|Int32	|-1114638897
Unknown	|Int16	|5
Unknown2	|Int16	|6
PreviousVariantSibling	|Int16	|0
NextVariantSibling	|Int16	|-1
ResourceGroupIndex	|Int16	|0
ResourceGroupMemberIndex	|Int16	|1
FrameEvents	|TagBlock (Animations_FrameEvents)	|0
SoundEvents	|TagBlock (Animations_SoundEvents)	|0
EffectEvents	|TagBlock (Animations_EffectEvents)	|0
DialogueEvents	|TagBlock (Animations_DialogueEvents)	|0
ObjectSpaceParentNodes	|TagBlock (Animations_ObjectSpaceParentNodes)	|0
LegAnchoring	|TagBlock (Animations_LegAnchoring)	|0
Unknown4	|Single	|1
Unknown5	|Single	|0
Unknown6	|Single	|0
Unknown7	|Single	|0
Unknown8	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|combat:unarmed:perch
Weight	|Single	|0
LoopFrameIndex	|Int16	|0
PlaybackFlags	|UInt16	|0
BlendScreen	|SByte	|-1
DesiredCompression	|Enum (CompressionValue)	|null
CurrentCompression	|Enum (CompressionValue)	|null
NodeCount	|SByte	|6
FrameCount	|Int16	|80
Type	|Enum (FrameType)	|null
FrameInfoType	|Enum (FrameMovementDataType)	|null
ProductionFlags	|UInt16	|0
InternalFlags	|UInt16	|128
NodeListChecksum	|Int32	|537443583
ProductionChecksum	|Int32	|603827422
Unknown	|Int16	|5
Unknown2	|Int16	|6
PreviousVariantSibling	|Int16	|-1
NextVariantSibling	|Int16	|-1
ResourceGroupIndex	|Int16	|0
ResourceGroupMemberIndex	|Int16	|2
FrameEvents	|TagBlock (Animations_FrameEvents)	|0
SoundEvents	|TagBlock (Animations_SoundEvents)	|0
EffectEvents	|TagBlock (Animations_EffectEvents)	|0
DialogueEvents	|TagBlock (Animations_DialogueEvents)	|0
ObjectSpaceParentNodes	|TagBlock (Animations_ObjectSpaceParentNodes)	|0
LegAnchoring	|TagBlock (Animations_LegAnchoring)	|0
Unknown4	|Single	|1
Unknown5	|Single	|0
Unknown6	|Single	|0
Unknown7	|Single	|0
Unknown8	|Single	|0


### Modes

**0:**

Name	| Type	| Value
---	|---	|---	|
Label	|StringId	|combat
WeaponClass	|TagBlock (Modes_WeaponClass)	|[1](#modes_weaponclass)
ModeIk	|TagBlock (Modes_ModeIk)	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0


### Modes_WeaponClass

**0:**

Name	| Type	| Value
---	|---	|---	|
Label	|StringId	|unarmed
WeaponType	|TagBlock (Modes_WeaponClass_WeaponType)	|[1](#modes_weaponclass_weapontype)
WeaponIk	|TagBlock (Modes_WeaponClass_WeaponIk)	|0
SyncActionGroups	|TagBlock (Modes_WeaponClass_SyncActionGroups)	|0


### Modes_WeaponClass_WeaponType

**0:**

Name	| Type	| Value
---	|---	|---	|
Label	|StringId	|any
Actions	|TagBlock (Modes_WeaponClass_WeaponType_Actions)	|[2](#modes_weaponclass_weapontype_actions)
Overlays	|TagBlock (Modes_WeaponClass_WeaponType_Overlays)	|0
DeathAndDamage	|TagBlock (Modes_WeaponClass_WeaponType_DeathAndDamage)	|0
Transitions	|TagBlock (Modes_WeaponClass_WeaponType_Transitions)	|0


### Modes_WeaponClass_WeaponType_Actions

**0:**

Name	| Type	| Value
---	|---	|---	|
Label	|StringId	|idle
GraphIndex	|Int16	|-1
Animation	|Int16	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Label	|StringId	|perch
GraphIndex	|Int16	|-1
Animation	|Int16	|2


### WeaponList

**0:**

Name	| Type	| Value
---	|---	|---	|
WeaponName	|StringId	|any
WeaponClass	|StringId	|any


### ResourceGroups

**0:**

Name	| Type	| Value
---	|---	|---	|
MemberCount	|Int32	|3
Resource	|ResourceReference	|BlamCore.Cache.ResourceReference


