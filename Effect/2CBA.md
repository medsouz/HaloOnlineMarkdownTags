# [0x2CBA] 0x00002CBA

**Name:** ```0x00002CBA```

**Index:** ```0x2CBA```

**Tag Group:** ```Effect (effe)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt32	|768
Unknown	|Int32	|0
Unknown2	|Single	|0
Unknown3	|UInt32	|0
Unknown4	|Single	|0.1
Unknown5	|SByte	|0
Unknown6	|SByte	|0
Unknown7	|SByte	|0
Unknown8	|SByte	|0
LoopStartEvent	|Int16	|-1
Unknown9	|Int16	|0
Unknown10	|UInt32	|0
Locations	|TagBlock (Locations)	|[1](#locations)
Events	|TagBlock (Events)	|[1](#events)
LoopingSound	|CachedTagInstance	|null
LocationIndex	|SByte	|0
EventIndex	|SByte	|-1
Unknown11	|Int16	|0
AlwaysPlayDistance	|Single	|0
NeverPlayDistance	|Single	|0
Unknown12	|Single	|0
Unknown13	|Single	|0.1
Unknown14	|TagBlock (Unknown14)	|0


## Tag Blocks

### Locations

**0:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|fx_jet_l_cover_crate
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


### Events

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|debris
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0
SkipFraction	|Single	|0
DelayBoundsMin	|Single	|0
DelayBoundsMax	|Single	|0
DurationBoundsMin	|Single	|0.03333334
DurationBoundsMax	|Single	|0.03333334
Parts	|TagBlock (Events_Parts)	|[1](#events_parts)
Accelerations	|TagBlock (Events_Accelerations)	|0
ParticleSystems	|TagBlock (Events_ParticleSystems)	|0


### Events_Parts

**0:**

Name	| Type	| Value
---	|---	|---	|
CreateInEnvironment	|Enum (CreateInEnvironmentValue)	|null
CreateInDisposition	|Enum (CreateInDispositionValue)	|null
LocationIndex	|Int16	|0
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|SByte	|0
CameraMode	|Enum (CameraModeValue)	|null
AnticipatedTagClass	|Int32	|1868720741
SpawnedTag	|CachedTagInstance (Crate)	|[[0x2D0D] objects\vehicles\hornet\garbage\cover_l\cover_l](../Crate/2D0D.md)
VelocityBoundsMin	|Single	|2
VelocityBoundsMax	|Single	|2
Unknown4	|UInt32	|0
Unknown5	|UInt32	|1070141403
VelocityConeAngle	|Angle	|{ Degrees: 60, Radians: 1.047198 }
AngularVelocityBoundsMin	|Angle	|{ Degrees: 200, Radians: 3.490659 }
AngularVelocityBoundsMax	|Angle	|{ Degrees: 500, Radians: 8.726646 }
RadiusModifierBoundsMin	|Single	|1
RadiusModifierBoundsMax	|Single	|1
OriginOffsetX	|Single	|0
OriginOffsetY	|Single	|0
OriginOffsetZ	|Single	|0
OriginRotationI	|Angle	|{ Degrees: 0, Radians: 0 }
OriginRotationJ	|Angle	|{ Degrees: 0, Radians: 0 }
AScalesValues	|UInt32	|0
BScalesValues	|UInt32	|0


