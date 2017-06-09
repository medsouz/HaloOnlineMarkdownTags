# [0x0CEE] 0x00000CEE

**Name:** ```0x00000CEE```

**Index:** ```0x0CEE```

**Tag Group:** ```Effect (effe)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt32	|66560
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
Locations	|TagBlock (Locations)	|[3](#locations)
Events	|TagBlock (Events)	|[1](#events)
LoopingSound	|CachedTagInstance	|null
LocationIndex	|SByte	|0
EventIndex	|SByte	|-1
Unknown11	|Int16	|0
AlwaysPlayDistance	|Single	|0
NeverPlayDistance	|Single	|0
Unknown12	|Single	|4
Unknown13	|Single	|0.1
Unknown14	|TagBlock (Unknown14)	|0


## Tag Blocks

### Locations

**0:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|gravity
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|up
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|normal
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


### Events

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|soft_terrain_snow
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0
SkipFraction	|Single	|0
DelayBoundsMin	|Single	|0
DelayBoundsMax	|Single	|0
DurationBoundsMin	|Single	|0.4
DurationBoundsMax	|Single	|0.4
Parts	|TagBlock (Events_Parts)	|[1](#events_parts)
Accelerations	|TagBlock (Events_Accelerations)	|0
ParticleSystems	|TagBlock (Events_ParticleSystems)	|[3](#events_particlesystems)


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
AnticipatedTagClass	|Int32	|1684366195
SpawnedTag	|CachedTagInstance (DecalSystem)	|[[0x0D51] 0x00000D51](../DecalSystem/0D51.md)
VelocityBoundsMin	|Single	|0.75
VelocityBoundsMax	|Single	|0.75
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
VelocityConeAngle	|Angle	|{ Degrees: 0, Radians: 0 }
AngularVelocityBoundsMin	|Angle	|{ Degrees: 35, Radians: 0.6108652 }
AngularVelocityBoundsMax	|Angle	|{ Degrees: 35, Radians: 0.6108652 }
RadiusModifierBoundsMin	|Single	|0.65
RadiusModifierBoundsMax	|Single	|0.65
OriginOffsetX	|Single	|0
OriginOffsetY	|Single	|0
OriginOffsetZ	|Single	|0
OriginRotationI	|Angle	|{ Degrees: 0, Radians: 0 }
OriginRotationJ	|Angle	|{ Degrees: 0, Radians: 0 }
AScalesValues	|UInt32	|0
BScalesValues	|UInt32	|0


### Events_ParticleSystems

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x0D52] 0x00000D52](../Particle/0D52.md)
Unknown5	|Int16	|1
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|-5
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|3.682129
Unknown8	|Single	|0.285641
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|50
LodInDistance	|Single	|15
LodFeatherInDelta	|Single	|0.06666667
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1061158912


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x041F] 0x0000041F](../Particle/041F.md)
Unknown5	|Int16	|1
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|3
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|2
Unknown8	|Single	|0.622839
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|20
LodInDistance	|Single	|5
LodFeatherInDelta	|Single	|0.2
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1067450368


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x0D54] 0x00000D54](../Particle/0D54.md)
Unknown5	|Int16	|2
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|5
Flags	|UInt16	|16400
Unknown6	|Single	|1
Unknown7	|Single	|3.682129
Unknown8	|Single	|0.0155663
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|50
LodInDistance	|Single	|15
LodFeatherInDelta	|Single	|0.06666667
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1082130432


### Events_ParticleSystems_Emitters

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|7428
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1051657111
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Input	|SByte	|1
InputRange	|SByte	|1
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown7	|Byte[]	|System.Byte[]
Unknown8	|UInt32	|0
Unknown9	|UInt32	|234
Unknown10	|UInt32	|1028443341
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Input2	|SByte	|1
InputRange2	|SByte	|3
OutputKind2	|Enum (OutputKindValue2)	|null
Output2	|SByte	|0
Unknown16	|Byte[]	|System.Byte[]
Unknown17	|UInt32	|0
Unknown18	|UInt32	|236
Unknown19	|UInt32	|0
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|UInt32	|0
Input3	|SByte	|1
InputRange3	|SByte	|8
OutputKind3	|Enum (OutputKindValue3)	|null
Output3	|SByte	|0
Unknown25	|Byte[]	|System.Byte[]
Unknown26	|UInt32	|1024416809
Unknown27	|UInt32	|224
Input4	|SByte	|0
InputRange4	|SByte	|4
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|0
Input5	|SByte	|1
InputRange5	|SByte	|5
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|64
Input6	|SByte	|1
InputRange6	|SByte	|3
OutputKind6	|Enum (OutputKindValue6)	|null
Output6	|SByte	|2
Unknown34	|Byte[]	|System.Byte[]
Unknown35	|UInt32	|1097859072
Unknown36	|UInt32	|224
Input7	|SByte	|1
InputRange7	|SByte	|8
OutputKind7	|Enum (OutputKindValue7)	|null
Output7	|SByte	|2
Unknown37	|Byte[]	|System.Byte[]
Unknown38	|UInt32	|0
Unknown39	|UInt32	|232
Input8	|SByte	|1
InputRange8	|SByte	|8
OutputKind8	|Enum (OutputKindValue8)	|null
Output8	|SByte	|0
Unknown40	|Byte[]	|System.Byte[]
Unknown41	|UInt32	|0
Unknown42	|UInt32	|232
Input9	|SByte	|0
InputRange9	|SByte	|6
OutputKind9	|Enum (OutputKindValue9)	|null
Output9	|SByte	|0
Unknown43	|Byte[]	|System.Byte[]
Unknown44	|UInt32	|0
Unknown45	|UInt32	|0
ParticlePhysics	|CachedTagInstance (ParticlePhysics)	|[[0x0441] 0x00000441](../ParticlePhysics/0441.md)
Unknown46	|UInt32	|257
Unknown47	|TagBlock (Events_ParticleSystems_Emitters_Unknown47)	|[1](#events_particlesystems_emitters_unknown47)
Input10	|SByte	|1
InputRange10	|SByte	|8
OutputKind10	|Enum (OutputKindValue10)	|null
Output10	|SByte	|0
Unknown48	|Byte[]	|System.Byte[]
Unknown49	|UInt32	|0
Unknown50	|UInt32	|236
Unknown51	|UInt32	|0
Unknown52	|UInt32	|0
Unknown53	|UInt32	|0
Unknown54	|UInt32	|0
Unknown55	|UInt32	|0
Unknown56	|UInt32	|0
Input11	|SByte	|0
InputRange11	|SByte	|7
OutputKind11	|Enum (OutputKindValue11)	|null
Output11	|SByte	|0
Unknown57	|Byte[]	|System.Byte[]
Unknown58	|UInt32	|0
Unknown59	|UInt32	|0
Input12	|SByte	|15
InputRange12	|SByte	|4
OutputKind12	|Enum (OutputKindValue12)	|null
Output12	|SByte	|0
Unknown60	|Byte[]	|System.Byte[]
Unknown61	|UInt32	|0
Unknown62	|UInt32	|232
Input13	|SByte	|0
InputRange13	|SByte	|21
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|0
Input14	|SByte	|0
InputRange14	|SByte	|22
OutputKind14	|Enum (OutputKindValue14)	|null
Output14	|SByte	|0
Unknown66	|Byte[]	|System.Byte[]
Unknown67	|UInt32	|0
Unknown68	|UInt32	|0
Input15	|SByte	|0
InputRange15	|SByte	|0
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|0
Unknown70	|UInt32	|0
Input16	|SByte	|0
InputRange16	|SByte	|23
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|0
Input17	|SByte	|0
InputRange17	|SByte	|8
OutputKind17	|Enum (OutputKindValue17)	|null
Output17	|SByte	|0
ParticleAlpha	|Byte[]	|System.Byte[]
Unknown73	|UInt32	|0
Unknown74	|UInt32	|0
Input18	|SByte	|0
InputRange18	|SByte	|0
OutputKind18	|Enum (OutputKindValue18)	|null
Output18	|SByte	|2
ParticleAlphaBlackPoint	|Byte[]	|System.Byte[]
Unknown75	|UInt32	|0
Unknown76	|UInt32	|0
Unknown77	|Int32	|2807
Unknown78	|Int32	|2791
Unknown79	|Int32	|14680305
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[8](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[5](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|3332
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1047746169
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Input	|SByte	|1
InputRange	|SByte	|1
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown7	|Byte[]	|System.Byte[]
Unknown8	|UInt32	|0
Unknown9	|UInt32	|234
Unknown10	|UInt32	|1028443341
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Input2	|SByte	|1
InputRange2	|SByte	|3
OutputKind2	|Enum (OutputKindValue2)	|null
Output2	|SByte	|0
Unknown16	|Byte[]	|System.Byte[]
Unknown17	|UInt32	|0
Unknown18	|UInt32	|236
Unknown19	|UInt32	|0
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|UInt32	|0
Input3	|SByte	|1
InputRange3	|SByte	|8
OutputKind3	|Enum (OutputKindValue3)	|null
Output3	|SByte	|0
Unknown25	|Byte[]	|System.Byte[]
Unknown26	|UInt32	|1033476506
Unknown27	|UInt32	|224
Input4	|SByte	|1
InputRange4	|SByte	|5
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|64
Input5	|SByte	|1
InputRange5	|SByte	|6
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|64
Input6	|SByte	|1
InputRange6	|SByte	|8
OutputKind6	|Enum (OutputKindValue6)	|null
Output6	|SByte	|2
Unknown34	|Byte[]	|System.Byte[]
Unknown35	|UInt32	|0
Unknown36	|UInt32	|64
Input7	|SByte	|1
InputRange7	|SByte	|8
OutputKind7	|Enum (OutputKindValue7)	|null
Output7	|SByte	|2
Unknown37	|Byte[]	|System.Byte[]
Unknown38	|UInt32	|0
Unknown39	|UInt32	|232
Input8	|SByte	|1
InputRange8	|SByte	|8
OutputKind8	|Enum (OutputKindValue8)	|null
Output8	|SByte	|11
Unknown40	|Byte[]	|System.Byte[]
Unknown41	|UInt32	|0
Unknown42	|UInt32	|64
Input9	|SByte	|0
InputRange9	|SByte	|4
OutputKind9	|Enum (OutputKindValue9)	|null
Output9	|SByte	|0
Unknown43	|Byte[]	|System.Byte[]
Unknown44	|UInt32	|0
Unknown45	|UInt32	|0
ParticlePhysics	|CachedTagInstance (ParticlePhysics)	|[[0x0498] 0x00000498](../ParticlePhysics/0498.md)
Unknown46	|UInt32	|257
Unknown47	|TagBlock (Events_ParticleSystems_Emitters_Unknown47)	|[1](#events_particlesystems_emitters_unknown47)
Input10	|SByte	|1
InputRange10	|SByte	|8
OutputKind10	|Enum (OutputKindValue10)	|null
Output10	|SByte	|0
Unknown48	|Byte[]	|System.Byte[]
Unknown49	|UInt32	|0
Unknown50	|UInt32	|236
Unknown51	|UInt32	|0
Unknown52	|UInt32	|0
Unknown53	|UInt32	|0
Unknown54	|UInt32	|0
Unknown55	|UInt32	|0
Unknown56	|UInt32	|0
Input11	|SByte	|0
InputRange11	|SByte	|4
OutputKind11	|Enum (OutputKindValue11)	|null
Output11	|SByte	|0
Unknown57	|Byte[]	|System.Byte[]
Unknown58	|UInt32	|0
Unknown59	|UInt32	|0
Input12	|SByte	|15
InputRange12	|SByte	|4
OutputKind12	|Enum (OutputKindValue12)	|null
Output12	|SByte	|4
Unknown60	|Byte[]	|System.Byte[]
Unknown61	|UInt32	|0
Unknown62	|UInt32	|128
Input13	|SByte	|1
InputRange13	|SByte	|7
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|64
Input14	|SByte	|0
InputRange14	|SByte	|21
OutputKind14	|Enum (OutputKindValue14)	|null
Output14	|SByte	|0
Unknown66	|Byte[]	|System.Byte[]
Unknown67	|UInt32	|0
Unknown68	|UInt32	|0
Input15	|SByte	|0
InputRange15	|SByte	|0
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|0
Unknown70	|UInt32	|0
Input16	|SByte	|0
InputRange16	|SByte	|2
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|232
Input17	|SByte	|0
InputRange17	|SByte	|8
OutputKind17	|Enum (OutputKindValue17)	|null
Output17	|SByte	|0
ParticleAlpha	|Byte[]	|System.Byte[]
Unknown73	|UInt32	|0
Unknown74	|UInt32	|0
Input18	|SByte	|1
InputRange18	|SByte	|0
OutputKind18	|Enum (OutputKindValue18)	|null
Output18	|SByte	|2
ParticleAlphaBlackPoint	|Byte[]	|System.Byte[]
Unknown75	|UInt32	|0
Unknown76	|UInt32	|232
Unknown77	|Int32	|168703
Unknown78	|Int32	|166471
Unknown79	|Int32	|2099697
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[6](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[4](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|2820
Unknown2	|Int16	|3
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1040846812
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Input	|SByte	|1
InputRange	|SByte	|2
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown7	|Byte[]	|System.Byte[]
Unknown8	|UInt32	|0
Unknown9	|UInt32	|234
Unknown10	|UInt32	|1033476506
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Input2	|SByte	|1
InputRange2	|SByte	|3
OutputKind2	|Enum (OutputKindValue2)	|null
Output2	|SByte	|0
Unknown16	|Byte[]	|System.Byte[]
Unknown17	|UInt32	|0
Unknown18	|UInt32	|236
Unknown19	|UInt32	|0
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|UInt32	|0
Input3	|SByte	|1
InputRange3	|SByte	|6
OutputKind3	|Enum (OutputKindValue3)	|null
Output3	|SByte	|0
Unknown25	|Byte[]	|System.Byte[]
Unknown26	|UInt32	|0
Unknown27	|UInt32	|64
Input4	|SByte	|0
InputRange4	|SByte	|2
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|232
Input5	|SByte	|1
InputRange5	|SByte	|2
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|232
Input6	|SByte	|1
InputRange6	|SByte	|3
OutputKind6	|Enum (OutputKindValue6)	|null
Output6	|SByte	|2
Unknown34	|Byte[]	|System.Byte[]
Unknown35	|UInt32	|1094713344
Unknown36	|UInt32	|224
Input7	|SByte	|1
InputRange7	|SByte	|8
OutputKind7	|Enum (OutputKindValue7)	|null
Output7	|SByte	|2
Unknown37	|Byte[]	|System.Byte[]
Unknown38	|UInt32	|0
Unknown39	|UInt32	|232
Input8	|SByte	|1
InputRange8	|SByte	|8
OutputKind8	|Enum (OutputKindValue8)	|null
Output8	|SByte	|0
Unknown40	|Byte[]	|System.Byte[]
Unknown41	|UInt32	|0
Unknown42	|UInt32	|232
Input9	|SByte	|0
InputRange9	|SByte	|7
OutputKind9	|Enum (OutputKindValue9)	|null
Output9	|SByte	|0
Unknown43	|Byte[]	|System.Byte[]
Unknown44	|UInt32	|0
Unknown45	|UInt32	|0
ParticlePhysics	|CachedTagInstance (ParticlePhysics)	|[[0x029F] fx\physics_templates\_default](../ParticlePhysics/029F.md)
Unknown46	|UInt32	|3
Unknown47	|TagBlock (Events_ParticleSystems_Emitters_Unknown47)	|[2](#events_particlesystems_emitters_unknown47)
Input10	|SByte	|1
InputRange10	|SByte	|8
OutputKind10	|Enum (OutputKindValue10)	|null
Output10	|SByte	|0
Unknown48	|Byte[]	|System.Byte[]
Unknown49	|UInt32	|0
Unknown50	|UInt32	|236
Unknown51	|UInt32	|0
Unknown52	|UInt32	|0
Unknown53	|UInt32	|0
Unknown54	|UInt32	|0
Unknown55	|UInt32	|0
Unknown56	|UInt32	|0
Input11	|SByte	|0
InputRange11	|SByte	|2
OutputKind11	|Enum (OutputKindValue11)	|null
Output11	|SByte	|0
Unknown57	|Byte[]	|System.Byte[]
Unknown58	|UInt32	|0
Unknown59	|UInt32	|232
Input12	|SByte	|15
InputRange12	|SByte	|4
OutputKind12	|Enum (OutputKindValue12)	|null
Output12	|SByte	|0
Unknown60	|Byte[]	|System.Byte[]
Unknown61	|UInt32	|0
Unknown62	|UInt32	|232
Input13	|SByte	|0
InputRange13	|SByte	|2
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|232
Input14	|SByte	|0
InputRange14	|SByte	|21
OutputKind14	|Enum (OutputKindValue14)	|null
Output14	|SByte	|0
Unknown66	|Byte[]	|System.Byte[]
Unknown67	|UInt32	|0
Unknown68	|UInt32	|0
Input15	|SByte	|0
InputRange15	|SByte	|0
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|1065353216
Unknown70	|UInt32	|240
Input16	|SByte	|0
InputRange16	|SByte	|2
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|232
Input17	|SByte	|0
InputRange17	|SByte	|8
OutputKind17	|Enum (OutputKindValue17)	|null
Output17	|SByte	|0
ParticleAlpha	|Byte[]	|System.Byte[]
Unknown73	|UInt32	|0
Unknown74	|UInt32	|0
Input18	|SByte	|0
InputRange18	|SByte	|0
OutputKind18	|Enum (OutputKindValue18)	|null
Output18	|SByte	|2
ParticleAlphaBlackPoint	|Byte[]	|System.Byte[]
Unknown75	|UInt32	|0
Unknown76	|UInt32	|232
Unknown77	|Int32	|188159
Unknown78	|Int32	|188155
Unknown79	|Int32	|2097393
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[9](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[5](#events_particlesystems_emitters_compiledcolorvalues)


### Events_ParticleSystems_Emitters_Unknown47

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|TagBlock (Events_ParticleSystems_Emitters_Unknown47_Unknown2)	|[3](#events_particlesystems_emitters_unknown47_unknown2)
Unknown3	|UInt32	|7
Unknown4	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|TagBlock (Events_ParticleSystems_Emitters_Unknown47_Unknown2)	|[3](#events_particlesystems_emitters_unknown47_unknown2)
Unknown3	|UInt32	|7
Unknown4	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|TagBlock (Events_ParticleSystems_Emitters_Unknown47_Unknown2)	|[3](#events_particlesystems_emitters_unknown47_unknown2)
Unknown3	|UInt32	|7
Unknown4	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1
Unknown2	|TagBlock (Events_ParticleSystems_Emitters_Unknown47_Unknown2)	|[2](#events_particlesystems_emitters_unknown47_unknown2)
Unknown3	|UInt32	|3
Unknown4	|UInt32	|0


### Events_ParticleSystems_Emitters_Unknown47_Unknown2

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1061158912
Unknown4	|UInt32	|224


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1065353216
Unknown4	|UInt32	|240


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|0
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1069547520
Unknown4	|UInt32	|224


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Input	|SByte	|0
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1041865114
Unknown4	|UInt32	|224


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1065353216
Unknown4	|UInt32	|240


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1065353216
Unknown4	|UInt32	|240


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1062836634
Unknown4	|UInt32	|224


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|224


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|0
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|224


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|224


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1036831949
Unknown4	|UInt32	|224


### Events_ParticleSystems_Emitters_Unknown80

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1144537088
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1090519040


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1216348160
Unknown4	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1144078336
Unknown3	|UInt32	|1224736768
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1099956224


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1071644672
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1228931072
Unknown4	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1231028352
Unknown4	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1108082688


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1143521280
Unknown3	|UInt32	|1216348160
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1091567616


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1069547520
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1224736768
Unknown4	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1226834192
Unknown4	|UInt32	|1240465408


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1104150528


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1143537664
Unknown3	|UInt32	|1220542464
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1124466688
Unknown3	|UInt32	|1226833920
Unknown4	|UInt32	|1099431936


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1071644672
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1126694912
Unknown3	|UInt32	|1231028224
Unknown4	|UInt32	|0


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1108082688


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


### Events_ParticleSystems_Emitters_CompiledFunctions

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1065353216
Unknown7	|UInt32	|1065353216
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1065353216
Unknown7	|UInt32	|1065353216
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065353216
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1050421494
Unknown3	|UInt32	|1065353216
Unknown4	|UInt32	|0
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1075741830
Unknown10	|UInt32	|3220532772
Unknown11	|UInt32	|1056239991
Unknown12	|UInt32	|3172657315
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1033476506
Unknown4	|UInt32	|1040187392
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1033476506
Unknown4	|UInt32	|1040187392
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065353216
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1061158912
Unknown4	|UInt32	|1068289229
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1068193049
Unknown10	|UInt32	|3228843639
Unknown11	|UInt32	|1079334230
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1036831949
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1053379728
Unknown10	|UInt32	|1058757048
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|1055454659
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3232274867
Unknown10	|UInt32	|1070546346
Unknown11	|UInt32	|0
Unknown12	|UInt32	|1065353216
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1082776095
Unknown10	|UInt32	|3237481611
Unknown11	|UInt32	|1076172149
Unknown12	|UInt32	|1063075217
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1045220557
Unknown4	|UInt32	|1036831949
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1045220557
Unknown4	|UInt32	|1036831949
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065353216
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1092616192
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|1066611507
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3221225472
Unknown10	|UInt32	|1077936128
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|1065353216
Unknown15	|UInt32	|1051858497
Unknown16	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|1044381696
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1118421880
Unknown10	|UInt32	|3262192042
Unknown11	|UInt32	|1096444327
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1056545178
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|1065353216
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1097709745
Unknown10	|UInt32	|3255081632
Unknown11	|UInt32	|1101911413
Unknown12	|UInt32	|3227247730
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1068289229
Unknown4	|UInt32	|1061158912
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1068289229
Unknown4	|UInt32	|1061158912
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065353216
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1065353216
Unknown7	|UInt32	|1065353216
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1065353216
Unknown7	|UInt32	|1065353216
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065353216
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065353216
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


### Events_ParticleSystems_Emitters_CompiledColorValues

**0:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.7921569
Green	|Single	|0.7921569
Blue	|Single	|0.7921569
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|1
Blue	|Single	|1
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|1
Blue	|Single	|1
Magnitude	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|1
Blue	|Single	|1
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|1
Blue	|Single	|1
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|1
Blue	|Single	|1
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|1
Blue	|Single	|1
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.7882353
Green	|Single	|0.9137255
Blue	|Single	|0.9490196
Magnitude	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


