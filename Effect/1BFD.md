# [0x1BFD] 0x00001BFD

**Name:** ```0x00001BFD```

**Index:** ```0x1BFD```

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
Unknown12	|Single	|0.4
Unknown13	|Single	|0.1
Unknown14	|TagBlock (Unknown14)	|0


## Tag Blocks

### Locations

**0:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|forward
Unknown	|Int32	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Unknown5	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
MarkerName	|StringId	|reflection
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
Name	|StringId	|hard_metal
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
ParticleSystems	|TagBlock (Events_ParticleSystems)	|[2](#events_particlesystems)


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
SpawnedTag	|CachedTagInstance (DecalSystem)	|[[0x1C38] 0x00001C38](../DecalSystem/1C38.md)
VelocityBoundsMin	|Single	|0.5
VelocityBoundsMax	|Single	|0.5
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
VelocityConeAngle	|Angle	|{ Degrees: 0, Radians: 0 }
AngularVelocityBoundsMin	|Angle	|{ Degrees: 0, Radians: 0 }
AngularVelocityBoundsMax	|Angle	|{ Degrees: 0, Radians: 0 }
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
Particle	|CachedTagInstance (Particle)	|[[0x03FF] 0x000003FF](../Particle/03FF.md)
Unknown5	|Int16	|2
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|-1
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|1.787364
Unknown8	|Single	|0.198424
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|20
LodInDistance	|Single	|5
LodFeatherInDelta	|Single	|0.2
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1053609165


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0
Particle	|CachedTagInstance (Particle)	|[[0x03DA] 0x000003DA](../Particle/03DA.md)
Unknown5	|Int16	|1
LocationIndex	|Int16	|0
CoordinateSystem	|Enum (CoordinateSystemValue)	|null
Environment	|Enum (EnvironmentValue)	|null
Disposition	|Enum (DispositionValue)	|null
CameraMode	|Enum (CameraModeValue)	|null
SortBias	|Int16	|0
Flags	|UInt16	|16384
Unknown6	|Single	|1
Unknown7	|Single	|204.4706
Unknown8	|Single	|0.00978137
Unknown9	|Single	|0
Unknown10	|UInt32	|2147483648
Unknown11	|Single	|1
AmountSize	|Single	|1
Unknown12	|Single	|45
LodInDistance	|Single	|5
LodFeatherInDelta	|Single	|0.2
Emitters	|TagBlock (Events_ParticleSystems_Emitters)	|[1](#events_particlesystems_emitters)
Unknown13	|UInt32	|1055286886


### Events_ParticleSystems_Emitters

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|7424
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1064362872
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
Unknown62	|UInt32	|232
Input13	|SByte	|1
InputRange13	|SByte	|6
OutputKind13	|Enum (OutputKindValue13)	|null
Output13	|SByte	|0
Unknown63	|Byte[]	|System.Byte[]
Unknown64	|UInt32	|0
Unknown65	|UInt32	|64
Input14	|SByte	|0
InputRange14	|SByte	|4
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
InputRange16	|SByte	|7
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
Input18	|SByte	|1
InputRange18	|SByte	|21
OutputKind18	|Enum (OutputKindValue18)	|null
Output18	|SByte	|2
ParticleAlphaBlackPoint	|Byte[]	|System.Byte[]
Unknown75	|UInt32	|0
Unknown76	|UInt32	|64
Unknown77	|Int32	|137983
Unknown78	|Int32	|2647
Unknown79	|Int32	|2099697
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[12](#events_particlesystems_emitters_compiledfunctions)
CompiledColorValues	|TagBlock (Events_ParticleSystems_Emitters_CompiledColorValues)	|[6](#events_particlesystems_emitters_compiledcolorvalues)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|emitter_0
Unknown	|UInt16	|3328
Unknown2	|Int16	|0
CustomEmitterPoints	|CachedTagInstance	|null
Unknown3	|UInt32	|1070385428
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
InputRange4	|SByte	|4
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
Input8	|SByte	|0
InputRange8	|SByte	|3
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
ParticlePhysics	|CachedTagInstance (ParticlePhysics)	|[[0x03DB] 0x000003DB](../ParticlePhysics/03DB.md)
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
Input11	|SByte	|13
InputRange11	|SByte	|4
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
InputRange15	|SByte	|4
OutputKind15	|Enum (OutputKindValue15)	|null
Output15	|SByte	|0
ParticleScale	|Byte[]	|System.Byte[]
Unknown69	|UInt32	|0
Unknown70	|UInt32	|0
Input16	|SByte	|4
InputRange16	|SByte	|5
OutputKind16	|Enum (OutputKindValue16)	|null
Output16	|SByte	|0
ParticleTint	|Byte[]	|System.Byte[]
Unknown71	|UInt32	|0
Unknown72	|UInt32	|128
Input17	|SByte	|0
InputRange17	|SByte	|4
OutputKind17	|Enum (OutputKindValue17)	|null
Output17	|SByte	|0
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
Unknown77	|Int32	|137975
Unknown78	|Int32	|170583
Unknown79	|Int32	|2353
Unknown80	|TagBlock (Events_ParticleSystems_Emitters_Unknown80)	|[13](#events_particlesystems_emitters_unknown80)
CompiledFunctions	|TagBlock (Events_ParticleSystems_Emitters_CompiledFunctions)	|[10](#events_particlesystems_emitters_compiledfunctions)
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
Unknown3	|UInt32	|3189348762
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
Unknown3	|UInt32	|0
Unknown4	|UInt32	|232


### Events_ParticleSystems_Emitters_Unknown80

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1130430464
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
Unknown2	|UInt32	|1124335616
Unknown3	|UInt32	|1220542464
Unknown4	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1124466688
Unknown3	|UInt32	|1226833920
Unknown4	|UInt32	|1104150528


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|1090519040
Unknown3	|UInt32	|1231028224
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
Unknown3	|UInt32	|1234173952
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
Unknown2	|UInt32	|1143652352
Unknown3	|UInt32	|1235222592
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
Unknown2	|UInt32	|1126236160
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1224736896


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
Unknown2	|UInt32	|1124335616
Unknown3	|UInt32	|1220542464
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
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1226833920
Unknown4	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1231028224
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
Unknown2	|UInt32	|1241513984
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|1233125440
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
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1061158912
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3185021984
Unknown10	|UInt32	|1067119236
Unknown11	|UInt32	|3221666977
Unknown12	|UInt32	|1065353216
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1041865114
Unknown4	|UInt32	|1048576000
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
Unknown3	|UInt32	|1041865114
Unknown4	|UInt32	|1048576000
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
Unknown3	|UInt32	|1067450368
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


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1067450368
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


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1048576000
Unknown4	|UInt32	|1067450368
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3211949432
Unknown10	|UInt32	|1054906184
Unknown11	|UInt32	|1068779549
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1065353216
Unknown2	|UInt32	|1065353216
Unknown3	|UInt32	|1036831949
Unknown4	|UInt32	|1051931443
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
Unknown3	|UInt32	|1036831949
Unknown4	|UInt32	|1051931443
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
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1089276286
Unknown10	|UInt32	|3246935003
Unknown11	|UInt32	|1092227831
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
Unknown3	|UInt32	|985963430
Unknown4	|UInt32	|992204554
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
Unknown3	|UInt32	|985963430
Unknown4	|UInt32	|992204554
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
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1037167493
Unknown3	|UInt32	|0
Unknown4	|UInt32	|1065353216
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1092360442
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
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|3185290420
Unknown10	|UInt32	|3212912666
Unknown11	|UInt32	|1039199644
Unknown12	|UInt32	|1065330711
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1088421888
Unknown2	|UInt32	|2139095039
Unknown3	|UInt32	|1068289229
Unknown4	|UInt32	|1056964608
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|1056964608
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065819250
Unknown10	|UInt32	|3225885810
Unknown11	|UInt32	|1078169145
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|UInt32	|1082130432
Unknown2	|UInt32	|1036496404
Unknown3	|UInt32	|1048576000
Unknown4	|UInt32	|1106247680
Unknown5	|UInt32	|1112539136
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1092885058
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
Unknown9	|UInt32	|1025333168
Unknown10	|UInt32	|1064281335
Unknown11	|UInt32	|3221971803
Unknown12	|UInt32	|1067059581
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0


### Events_ParticleSystems_Emitters_CompiledColorValues

**0:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.5490196
Green	|Single	|0.5803922
Blue	|Single	|0.6156863
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.1568628
Green	|Single	|0.1686275
Blue	|Single	|0.1843137
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.7137255
Green	|Single	|0.7333333
Blue	|Single	|0.7843137
Magnitude	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.4588235
Green	|Single	|0.5176471
Blue	|Single	|0.5490196
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
Green	|Single	|0.9568627
Blue	|Single	|0.9019608
Magnitude	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|0.1921569
Green	|Single	|0.3137255
Blue	|Single	|0.9960784
Magnitude	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Red	|Single	|1
Green	|Single	|0.6784314
Blue	|Single	|0.3568628
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


