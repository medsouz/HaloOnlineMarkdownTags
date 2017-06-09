# [0x1ADA] 0x00001ADA

**Name:** ```0x00001ADA```

**Index:** ```0x1ADA```

**Tag Group:** ```DamageEffect (jpt!)```

## Fields

Name	| Type	| Value
---	|---	|---	|
RadiusMin	|Single	|0.5
RadiusMax	|Single	|1.75
CutoffScale	|Single	|0
Flags	|UInt32	|0
SideEffect	|Enum (SideEffectValue)	|null
Category	|Enum (CategoryValue)	|null
Flags2	|UInt32	|0
AreaOfEffectCoreRadius	|Single	|0.75
DamageLowerBound	|Single	|0
DamageUpperBoundMin	|Single	|0
DamageUpperBoundMax	|Single	|0
DamageInnerConeAngle	|Angle	|{ Degrees: 0, Radians: 0 }
DamageOuterConeAngle	|Angle	|{ Degrees: 0, Radians: 0 }
ActiveCamoflageDamage	|Single	|0.1
Stun	|Single	|0
MaxStun	|Single	|0
StunTime	|Single	|0
InstantaneousAcceleration	|Single	|2
RiderDirectDamageScale	|Single	|0
RiderMaxTransferDamageScale	|Single	|0
RiderMinTransferDamageScale	|Single	|1
GeneralDamage	|StringId	|explosion_small
SpecificDamage	|StringId	|
SpecialDamage	|StringId	|
AiStunRadius	|Single	|3.5
AiStunBoundsMin	|Single	|0.85
AiStunBoundsMax	|Single	|0.5
ShakeRadius	|Single	|8
EmpRadius	|Single	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1065353216
PlayerResponses	|TagBlock (PlayerResponses)	|[1](#playerresponses)
DamageResponse	|CachedTagInstance (DamageResponseDefinition)	|[[0x04BB] 0x000004BB](../DamageResponseDefinition/04BB.md)
Duration	|Single	|0.5
FadeFunction	|Enum (FadeFunctionValue)	|null
Unknown4	|Int16	|0
Rotation	|Angle	|{ Degrees: 0.7, Radians: 0.0122173 }
Pushback	|Single	|0.3
JitterMin	|Single	|0
JitterMax	|Single	|0
Duration2	|Single	|0.8
FalloffFunction	|Enum (FalloffFunctionValue)	|null
Unknown5	|Int16	|0
RandomTranslation	|Single	|0.04
RandomRotation	|Angle	|{ Degrees: 0, Radians: 0 }
WobbleFunction	|Enum (WobbleFunctionValue)	|null
Unknown6	|Int16	|0
WobbleFunctionPeriod	|Single	|1
WobbleWeight	|Single	|0
Sound	|CachedTagInstance	|null
ForwardVelocity	|Single	|30
ForwardRadius	|Single	|2
ForwardExponent	|Single	|0
OutwardVelocity	|Single	|15
OutwardRadius	|Single	|1
OutwardExponent	|Single	|0


## Tag Blocks

### PlayerResponses

**0:**

Name	| Type	| Value
---	|---	|---	|
ResponseType	|Enum (ResponseTypeValue)	|null
Unknown	|Int16	|0
Type	|Enum (TypeValue)	|null
Priority	|Enum (PriorityValue)	|null
Duration	|Single	|1
FadeFunction	|Enum (FadeFunctionValue)	|null
Unknown2	|Int16	|0
MaximumIntensity	|Single	|0.5
ColorAlpha	|Single	|0.25
ColorRed	|Single	|1
ColorGreen	|Single	|0.933333
ColorBlue	|Single	|0.756863
LowFrequencyVibrationDuration	|Single	|1
LowFrequencyVibrationFunction	|Byte[]	|System.Byte[]
HighFrequencyVibrationDuration	|Single	|0.14
HighFrequencyVibrationFunction	|Byte[]	|System.Byte[]
EffectName	|StringId	|
Duration2	|Single	|0
EffectScaleFunction	|Byte[]	|System.Byte[]


