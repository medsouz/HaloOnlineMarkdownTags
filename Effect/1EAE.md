# [0x1EAE] 0x00001EAE

**Name:** ```0x00001EAE```

**Index:** ```0x1EAE```

**Tag Group:** ```Effect (effe)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt32	|1280
Unknown	|Int32	|0
Unknown2	|Single	|3
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
LocationIndex	|SByte	|-1
EventIndex	|SByte	|-1
Unknown11	|Int16	|0
AlwaysPlayDistance	|Single	|10
NeverPlayDistance	|Single	|50
Unknown12	|Single	|2
Unknown13	|Single	|0.1
Unknown14	|TagBlock (Unknown14)	|0


## Tag Blocks

### Locations

**0:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|normal
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|forward
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|up
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


### Events

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|plasma_dirt_medium
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
ParticleSystems	|TagBlock (Events_ParticleSystems)	|[5](#events_particlesystems)


### Events_Parts

**0:**

Name	| Type	| Value
---	|---	|---	|
CreateInEnvironment	|Enum (CreateInEnvironmentValue)	|null
CreateInDisposition	|Enum (CreateInDispositionValue)	|null
LocationIndex	|Int16	|1
Unknown	|Int16	|-1
Unknown2	|Int16	|0
Unknown3	|SByte	|0
CameraMode	|Enum (CameraModeValue)	|null
AnticipatedTagClass	|Int32	|1684366195
SpawnedTag	|CachedTagInstance (DecalSystem)	|[[0x0493] 0x00000493](../DecalSystem/0493.md)
VelocityBoundsMin	|Single	|0.5
VelocityBoundsMax	|Single	|0.5
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
VelocityConeAngle	|Angle	|{ Degrees: 0, Radians: 0 }
AngularVelocityBoundsMin	|Angle	|{ Degrees: 0.3, Radians: 0.005235988 }
AngularVelocityBoundsMax	|Angle	|{ Degrees: 0.3, Radians: 0.005235988 }
RadiusModifierBoundsMin	|Single	|0
RadiusModifierBoundsMax	|Single	|0
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
Particle	|CachedTagInstance (Particle)	|[[0x0688] 0x00000688](../Particle/0688.md)
Unknown5	|Int16	|2
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|3
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|4.724536
Unknown8	|Single	|0.423323
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|20
LodInDistance	|Single	|5
LodFeatherInDelta	|Single	|0.2
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1067450368


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x066F] 0x0000066F](../Particle/066F.md)
Unknown5	|Int16	|2
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|4
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|8.700645
Unknown8	|Single	|0.229868
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|20
LodInDistance	|Single	|5
LodFeatherInDelta	|Single	|0.2
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1053609165


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x0670] 0x00000670](../Particle/0670.md)
Unknown5	|Int16	|2
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|-4
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|7.5989
Unknown8	|Single	|0.263196
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|8
LodInDistance	|Single	|3
LodFeatherInDelta	|Single	|0.3333333
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1067450368


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x057F] 0x0000057F](../Particle/057F.md)
Unknown5	|Int16	|0
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|2
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|2.181544
Unknown8	|Single	|0.916782
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|20
LodInDistance	|Single	|5
LodFeatherInDelta	|Single	|0.2
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1062836634


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x057B] 0x0000057B](../Particle/057B.md)
Unknown5	|Int16	|0
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|-7
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|35.71926
Unknown8	|Single	|0.0559922
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|6
LodInDistance	|Single	|3
LodFeatherInDelta	|Single	|0.3333333
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1073741824


### Events_ParticleSystems_Emitters

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|7428
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1045617763
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
Unknown10	|UInt32	|0
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
Unknown26	|UInt32	|1014350479
Unknown27	|UInt32	|224
Input4	|SByte	|1
InputRange4	|SByte	|4
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|4
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|0
Input5	|SByte	|1
InputRange5	|SByte	|2
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|232
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
ParticlePhysics	|CachedTagInstance (ParticlePhysics)	|[[0x029F] fx\physics_templates\_default](../ParticlePhysics/029F.md)
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
Input11	|SByte	|1
InputRange11	|SByte	|4
OutputKind11	|Enum (OutputKindValue11)	|null
Output11	|SByte	|0
Unknown57	|Byte[]	|System.Byte[]
Unknown58	|UInt32	|0
Unknown59	|UInt32	|0
Input12	|SByte	|7
InputRange12	|SByte	|2
OutputKind12	|Enum (OutputKindValue12)	|null
Output12	|SByte	|0
Unknown60	|Byte[]	|System.Byte[]
Unknown61	|UInt32	|0
Unknown62	|UInt32	|192
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
InputRange16	|SByte	|5
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|232
Input17	|SByte	|0
InputRange17	|SByte	|0
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
Unknown77	|Int32	|35575
Unknown78	|Int32	|35543
Unknown79	|Int32	|6291953
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[12](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[5](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|7424
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1042502583
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
Unknown10	|UInt32	|0
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
Unknown26	|UInt32	|0
Unknown27	|UInt32	|232
Input4	|SByte	|1
InputRange4	|SByte	|21
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|64
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
Unknown35	|UInt32	|1077936128
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
InputRange9	|SByte	|4
OutputKind9	|Enum (OutputKindValue9)	|null
Output9	|SByte	|0
Unknown43	|Byte[]	|System.Byte[]
Unknown44	|UInt32	|0
Unknown45	|UInt32	|0
ParticlePhysics	|CachedTagInstance	|null
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
Input11	|SByte	|1
InputRange11	|SByte	|8
OutputKind11	|Enum (OutputKindValue11)	|null
Output11	|SByte	|0
Unknown57	|Byte[]	|System.Byte[]
Unknown58	|UInt32	|981668463
Unknown59	|UInt32	|224
Input12	|SByte	|15
InputRange12	|SByte	|4
OutputKind12	|Enum (OutputKindValue12)	|null
Output12	|SByte	|0
Unknown60	|Byte[]	|System.Byte[]
Unknown61	|UInt32	|0
Unknown62	|UInt32	|232
Input13	|SByte	|0
InputRange13	|SByte	|4
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|232
Input14	|SByte	|0
InputRange14	|SByte	|4
OutputKind14	|Enum (OutputKindValue14)	|null
Output14	|SByte	|0
Unknown66	|Byte[]	|System.Byte[]
Unknown67	|UInt32	|0
Unknown68	|UInt32	|0
Input15	|SByte	|0
InputRange15	|SByte	|5
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|0
Unknown70	|UInt32	|0
Input16	|SByte	|0
InputRange16	|SByte	|5
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
Unknown76	|UInt32	|0
Unknown77	|Int32	|40703
Unknown78	|Int32	|40695
Unknown79	|Int32	|2097393
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[12](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[5](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|7424
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1051658496
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
Unknown10	|UInt32	|0
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
Input3	|SByte	|0
InputRange3	|SByte	|4
OutputKind3	|Enum (OutputKindValue3)	|null
Output3	|SByte	|0
Unknown25	|Byte[]	|System.Byte[]
Unknown26	|UInt32	|0
Unknown27	|UInt32	|232
Input4	|SByte	|0
InputRange4	|SByte	|6
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|0
Input5	|SByte	|1
InputRange5	|SByte	|2
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|232
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
Input8	|SByte	|8
InputRange8	|SByte	|9
OutputKind8	|Enum (OutputKindValue8)	|null
Output8	|SByte	|11
Unknown40	|Byte[]	|System.Byte[]
Unknown41	|UInt32	|0
Unknown42	|UInt32	|64
Input9	|SByte	|0
InputRange9	|SByte	|7
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
InputRange11	|SByte	|21
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
Input13	|SByte	|0
InputRange13	|SByte	|22
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|0
Input14	|SByte	|23
InputRange14	|SByte	|24
OutputKind14	|Enum (OutputKindValue14)	|null
Output14	|SByte	|0
Unknown66	|Byte[]	|System.Byte[]
Unknown67	|UInt32	|0
Unknown68	|UInt32	|192
Input15	|SByte	|0
InputRange15	|SByte	|0
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|0
Unknown70	|UInt32	|0
Input16	|SByte	|0
InputRange16	|SByte	|6
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|232
Input17	|SByte	|0
InputRange17	|SByte	|4
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
Unknown77	|Int32	|41719
Unknown78	|Int32	|43607
Unknown79	|Int32	|31459825
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[11](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[5](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|7428
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1051703208
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
Unknown10	|UInt32	|0
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
Unknown26	|UInt32	|1020054733
Unknown27	|UInt32	|224
Input4	|SByte	|1
InputRange4	|SByte	|5
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|64
Input5	|SByte	|1
InputRange5	|SByte	|2
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|232
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
Output9	|SByte	|4
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
Output11	|SByte	|5
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
InputRange13	|SByte	|6
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|64
Input14	|SByte	|0
InputRange14	|SByte	|7
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
InputRange16	|SByte	|0
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|232
Input17	|SByte	|0
InputRange17	|SByte	|21
OutputKind17	|Enum (OutputKindValue17)	|null
Output17	|SByte	|0
ParticleAlpha	|Byte[]	|System.Byte[]
Unknown73	|UInt32	|0
Unknown74	|UInt32	|0
Input18	|SByte	|1
InputRange18	|SByte	|22
OutputKind18	|Enum (OutputKindValue18)	|null
Output18	|SByte	|2
ParticleAlphaBlackPoint	|Byte[]	|System.Byte[]
Unknown75	|UInt32	|0
Unknown76	|UInt32	|64
Unknown77	|Int32	|168703
Unknown78	|Int32	|35415
Unknown79	|Int32	|6294001
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[9](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[6](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|773
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1081550796
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
Unknown10	|UInt32	|0
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
Unknown26	|UInt32	|1028443341
Unknown27	|UInt32	|224
Input4	|SByte	|1
InputRange4	|SByte	|21
OutputKind4	|Enum (OutputKindValue4)	|null
Output4	|SByte	|0
Unknown28	|Byte[]	|System.Byte[]
Unknown29	|UInt32	|0
Unknown30	|UInt32	|64
Input5	|SByte	|1
InputRange5	|SByte	|22
OutputKind5	|Enum (OutputKindValue5)	|null
Output5	|SByte	|0
Unknown31	|Byte[]	|System.Byte[]
Unknown32	|UInt32	|0
Unknown33	|UInt32	|64
Input6	|SByte	|1
InputRange6	|SByte	|8
OutputKind6	|Enum (OutputKindValue6)	|null
Output6	|SByte	|11
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
ParticlePhysics	|CachedTagInstance (ParticlePhysics)	|[[0x0441] 0x00000441](../ParticlePhysics/0441.md)
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
InputRange11	|SByte	|23
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
Input13	|SByte	|0
InputRange13	|SByte	|24
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|0
Input14	|SByte	|0
InputRange14	|SByte	|4
OutputKind14	|Enum (OutputKindValue14)	|null
Output14	|SByte	|0
Unknown66	|Byte[]	|System.Byte[]
Unknown67	|UInt32	|0
Unknown68	|UInt32	|0
Input15	|SByte	|0
InputRange15	|SByte	|4
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|1065353216
Unknown70	|UInt32	|240
Input16	|SByte	|1
InputRange16	|SByte	|2
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|232
Input17	|SByte	|0
InputRange17	|SByte	|8
OutputKind17	|Enum (OutputKindValue17)	|null
Output17	|SByte	|11
ParticleAlpha	|Byte[]	|System.Byte[]
Unknown73	|UInt32	|0
Unknown74	|UInt32	|0
Input18	|SByte	|1
InputRange18	|SByte	|8
OutputKind18	|Enum (OutputKindValue18)	|null
Output18	|SByte	|2
ParticleAlphaBlackPoint	|Byte[]	|System.Byte[]
Unknown75	|UInt32	|0
Unknown76	|UInt32	|232
Unknown77	|Int32	|180991
Unknown78	|Int32	|182855
Unknown79	|Int32	|31459793
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[8](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[6](#events_particlesystems_emitters_compiledcolorvalues)


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
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1065353216
Unknown4	|UInt32	|240


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
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|0
Unknown4	|UInt32	|232


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|0
Unknown4	|UInt32	|232


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|0
Unknown4	|UInt32	|232


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Input	|SByte	|0
InputRange	|SByte	|5
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
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|5
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1069547520
Unknown4	|UInt32	|224


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|0
Unknown4	|UInt32	|232


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
Unknown3	|UInt32	|1077936128
Unknown4	|UInt32	|224


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|5
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1084227584
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
Unknown3	|UInt32	|1065337844
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
Unknown3	|UInt32	|1028600249
Unknown4	|UInt32	|224


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|2
Input	|SByte	|0
InputRange	|SByte	|4
OutputKind	|Enum (OutputKindValue)	|null
Output	|SByte	|0
Unknown2	|Byte[]	|System.Byte[]
Unknown3	|UInt32	|1023508243
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
Unknown3	|UInt32	|1048576000
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
Unknown3	|UInt32	|1048576000
Unknown4	|UInt32	|224


### Events_ParticleSystems_Emitters_Unknown80

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
Unknown2	|UInt32	|1144045568
Unknown3	|UInt32	|1216348160
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1126498304
Unknown3	|UInt32	|1224736768
Unknown4	|UInt32	|1099431936


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
Unknown3	|UInt32	|1228931072
Unknown4	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1231028224
Unknown4	|UInt32	|1231028224


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
Unknown3	|UInt32	|1233125440
Unknown4	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1093664768
Unknown3	|UInt32	|1235222592
Unknown4	|UInt32	|1224736768


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
Unknown2	|UInt32	|1124204544
Unknown3	|UInt32	|1207959552
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1128529920
Unknown3	|UInt32	|1220542464
Unknown4	|UInt32	|1226834192


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1067450368
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
Unknown3	|UInt32	|1226833920
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
Unknown2	|UInt32	|1130823680
Unknown3	|UInt32	|1228931072
Unknown4	|UInt32	|0


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1233125440
Unknown4	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1093664768
Unknown3	|UInt32	|1235222592
Unknown4	|UInt32	|1224736768


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
Unknown2	|UInt32	|1145094144
Unknown3	|UInt32	|1216348160
Unknown4	|UInt32	|1245184000


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1126498304
Unknown3	|UInt32	|1224736768
Unknown4	|UInt32	|1224737040


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1067450368
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
Unknown2	|UInt32	|1088421888
Unknown3	|UInt32	|1228931072
Unknown4	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1233125512
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
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1234174016
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
Unknown2	|UInt32	|1143488512
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1130561536
Unknown3	|UInt32	|1216348160
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1224736768
Unknown4	|UInt32	|1224737168


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1067450368
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
Unknown3	|UInt32	|1226833920
Unknown4	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1228931344
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
Unknown2	|UInt32	|1144127488
Unknown3	|UInt32	|1231028352
Unknown4	|UInt32	|1207959552


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
Unknown4	|UInt32	|1110441984


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
Unknown3	|UInt32	|1110966272
Unknown4	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1124270080
Unknown3	|UInt32	|1216348160
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1224736768
Unknown4	|UInt32	|1231028624


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
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
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
Unknown2	|UInt32	|1128726528
Unknown3	|UInt32	|1228931072
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
Unknown4	|UInt32	|1110441984


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
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1042032886
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1062836634
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
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
Unknown9	|UInt32	|3215817336
Unknown10	|UInt32	|1082779592
Unknown11	|UInt32	|3230774199
Unknown12	|UInt32	|1070377522
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
Unknown4	|UInt32	|1041865114
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
Unknown4	|UInt32	|1041865114
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
Unknown3	|UInt32	|1041865114
Unknown4	|UInt32	|1068289229
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3175078968
Unknown10	|UInt32	|3215007119
Unknown11	|UInt32	|1074673891
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
Unknown3	|UInt32	|3175926989
Unknown4	|UInt32	|1028443341
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1077470092
Unknown10	|UInt32	|3230779163
Unknown11	|UInt32	|1076538026
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1040522936
Unknown3	|UInt32	|1065353216
Unknown4	|UInt32	|0
Unknown5	|UInt32	|1112539136
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


**9:**

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
Unknown9	|UInt32	|3217965638
Unknown10	|UInt32	|1083710542
Unknown11	|UInt32	|3231024872
Unknown12	|UInt32	|1069804717
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1061158912
Unknown4	|UInt32	|1069547520
Unknown5	|UInt32	|1111752704
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


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1061158912
Unknown4	|UInt32	|1069547520
Unknown5	|UInt32	|1111752704
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


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1056964608
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3213606832
Unknown10	|UInt32	|1035729664
Unknown11	|UInt32	|0
Unknown12	|UInt32	|1065353216
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1041865114
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


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1041865114
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


**3:**

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


**4:**

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


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1048576000
Unknown4	|UInt32	|1069547520
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3206304886
Unknown10	|UInt32	|3204887909
Unknown11	|UInt32	|1073826558
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
Unknown9	|UInt32	|1065353216
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
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1050337608
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111490560
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


**9:**

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
Unknown9	|UInt32	|3204784580
Unknown10	|UInt32	|1077475370
Unknown11	|UInt32	|3217918484
Unknown12	|UInt32	|1047614737
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|1069547520
Unknown5	|UInt32	|1111752704
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


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|1069547520
Unknown5	|UInt32	|1111752704
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


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1053693051
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
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
Unknown9	|UInt32	|3224032727
Unknown10	|UInt32	|1073746322
Unknown11	|UInt32	|3197871752
Unknown12	|UInt32	|1064887384
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1043542835
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


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1043542835
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


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111752704
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


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111752704
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


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|1069547520
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


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|1069547520
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


**8:**

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


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1050505380
Unknown3	|UInt32	|1041865114
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111490560
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


**10:**

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
Unknown9	|UInt32	|3233855392
Unknown10	|UInt32	|1094515647
Unknown11	|UInt32	|3232876573
Unknown12	|UInt32	|1061437942
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1062836634
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1056784204
Unknown10	|UInt32	|1009790208
Unknown11	|UInt32	|3217076269
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
Unknown4	|UInt32	|1062836634
Unknown5	|UInt32	|1112801280
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3196352596
Unknown10	|UInt32	|1065546294
Unknown11	|UInt32	|3215100460
Unknown12	|UInt32	|1057057815
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1050253722
Unknown4	|UInt32	|1045220557
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
Unknown3	|UInt32	|1050253722
Unknown4	|UInt32	|1045220557
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
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
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


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1056964608
Unknown4	|UInt32	|1069547520
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1046432264
Unknown10	|UInt32	|3221143919
Unknown11	|UInt32	|1076538027
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


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1048576000
Unknown5	|UInt32	|1111752704
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
Unknown4	|UInt32	|1048576000
Unknown5	|UInt32	|1111752704
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


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1061788058
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
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


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3231094424
Unknown10	|UInt32	|1083610776
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1008981770
Unknown4	|UInt32	|1017370378
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
Unknown3	|UInt32	|1008981770
Unknown4	|UInt32	|1017370378
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
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111490560
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


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111752704
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


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1111752704
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
Red	|Single	|0.9607843
Green	|Single	|0.9764706
Blue	|Single	|0.9960784
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.427451
Green	|Single	|0.3490196
Blue	|Single	|0.2392157
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.227451
Green	|Single	|0.1372549
Blue	|Single	|0.1019608
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
Red	|Single	|0.9607843
Green	|Single	|0.9764706
Blue	|Single	|0.9960784
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.1137255
Green	|Single	|0.09019608
Blue	|Single	|0.08235294
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.282353
Green	|Single	|0.2196078
Blue	|Single	|0.1333333
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
Red	|Single	|0.2745098
Green	|Single	|0.2313726
Blue	|Single	|0.1921569
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.1254902
Green	|Single	|0.08627451
Blue	|Single	|0.06666667
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
Red	|Single	|0.5019608
Green	|Single	|0.4666667
Blue	|Single	|0.4078431
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.5176471
Green	|Single	|0.3647059
Blue	|Single	|0.2078431
Magnitude	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.1372549
Green	|Single	|0.09411765
Blue	|Single	|0.07450981
Magnitude	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**5:**

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
Red	|Single	|0.4588235
Green	|Single	|0.4431373
Blue	|Single	|0.4156863
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.372549
Green	|Single	|0.2117647
Blue	|Single	|0.1058824
Magnitude	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.1058824
Green	|Single	|0.07450981
Blue	|Single	|0.0627451
Magnitude	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0
Green	|Single	|0
Blue	|Single	|0
Magnitude	|Single	|0


