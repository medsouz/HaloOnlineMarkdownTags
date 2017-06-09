# [0x3FCD] 0x00003FCD

**Name:** ```0x00003FCD```

**Index:** ```0x3FCD```

**Tag Group:** ```SoundLooping (lsnd)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt32	|0
MartySMusicTime	|Single	|0
Unknown1	|Single	|0
Unknown2	|Single	|0.9
Unknown3	|Single	|5
Unused	|CachedTagInstance	|null
SoundClass	|Enum (SoundClassValue)	|null
Unknown4	|Int16	|0
Tracks	|TagBlock (Tracks)	|[1](#tracks)
DetailSounds	|TagBlock (DetailSounds)	|[1](#detailsounds)


## Tag Blocks

### Tracks

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|amb_wind_mountains
Flags	|UInt32	|0
Gain	|Single	|-3
FadeInDuration	|Single	|0
Unknown1	|UInt32	|0
FadeOutDuration	|Single	|0
Unknown2	|Int16	|0
Unknown3	|Int16	|0
In	|CachedTagInstance	|null
Loop	|CachedTagInstance (Sound)	|[[0x40B9] 0x000040B9](../Sound/40B9.md)
Out	|CachedTagInstance	|null
AlternateLoop	|CachedTagInstance	|null
AlternateOut	|CachedTagInstance	|null
OutputEffect	|Enum (OutputEffectValue)	|null
Unknown4	|Int16	|0
AlternateTransitionIn	|CachedTagInstance	|null
AlternateTransitionOut	|CachedTagInstance	|null
AlternateCrossfadeDuration	|Single	|0
Unknown5	|Single	|0
AlternateFadeOutDuration	|Single	|0
Unknown6	|Single	|0


### DetailSounds

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|amb_wind_tree_gusts
Sound	|CachedTagInstance (Sound)	|[[0x40BA] 0x000040BA](../Sound/40BA.md)
RandomPeriodBounds	|Bounds`1	|{ Lower: 4, Upper: 11 }
Unknown	|Single	|0
Flags	|UInt32	|0
YawBounds	|Bounds`1	|{ Lower: { Degrees: -180, Radians: -3.141593 }, Upper: { Degrees: 180, Radians: 3.141593 } }
PitchBounds	|Bounds`1	|{ Lower: { Degrees: -90, Radians: -1.570796 }, Upper: { Degrees: 90, Radians: 1.570796 } }
DistanceBounds	|Bounds`1	|{ Lower: 0, Upper: 0 }


