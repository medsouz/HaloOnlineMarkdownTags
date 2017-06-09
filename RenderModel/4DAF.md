# 0x4DAF

**Index:** ```0x4DAF```

**Tag Group:** ```RenderModel (mode)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|switch_monitor
Flags	|Enum (FlagsValue)	|null
Unknown6	|Int16	|0
Checksum	|Int32	|268699673
Regions	|TagBlock (Regions)	|[1](#regions)
Unknown18	|Int32	|0
InstanceStartingMeshIndex	|Int32	|-1
Instances	|TagBlock (Instances)	|0
Unknown2C	|Int32	|0
Nodes	|TagBlock (Nodes)	|[1](#nodes)
MarkerGroups	|TagBlock (MarkerGroups)	|[1](#markergroups)
Materials	|TagBlock (Materials)	|[2](#materials)
Unknown54	|Int32	|0
Unknown58	|Int32	|0
Unknown5C	|Int32	|0
Unknown60	|Int32	|0
Geometry	|RenderGeometry	|BlamCore.Geometry.RenderGeometry
UnknownE8	|TagBlock (UnknownE8)	|0
UnknownF4	|Int32	|1063594103
UnknownF8	|Int32	|-1081415403
UnknownFC	|Int32	|0
Unknown100	|Int32	|-1081415403
Unknown104	|Int32	|1071069669
Unknown108	|Int32	|-2147483648
Unknown10C	|Int32	|-1082615608
Unknown110	|Int32	|-2147483648
Unknown114	|Int32	|0
Unknown118	|Int32	|0
Unknown11C	|Int32	|0
Unknown120	|Int32	|0
Unknown124	|Int32	|0
Unknown128	|Int32	|0
Unknown12C	|Int32	|0
Unknown130	|Int32	|0
Unknown134	|Int32	|1063594103
Unknown138	|Int32	|-1081415403
Unknown13C	|Int32	|0
Unknown140	|Int32	|-1081415403
Unknown144	|Int32	|1071069669
Unknown148	|Int32	|-2147483648
Unknown14C	|Int32	|-1082615608
Unknown150	|Int32	|-2147483648
Unknown154	|Int32	|0
Unknown158	|Int32	|0
Unknown15C	|Int32	|0
Unknown160	|Int32	|0
Unknown164	|Int32	|0
Unknown168	|Int32	|0
Unknown16C	|Int32	|0
Unknown170	|Int32	|0
Unknown174	|Int32	|1063594103
Unknown178	|Int32	|-1081415403
Unknown17C	|Int32	|0
Unknown180	|Int32	|-1081415403
Unknown184	|Int32	|1071069669
Unknown188	|Int32	|-2147483648
Unknown18C	|Int32	|-1082615608
Unknown190	|Int32	|-2147483648
Unknown194	|Int32	|0
Unknown198	|Int32	|0
Unknown19C	|Int32	|0
Unknown1A0	|Int32	|0
Unknown1A4	|Int32	|0
Unknown1A8	|Int32	|0
Unknown1AC	|Int32	|0
Unknown1B0	|Int32	|0
Unknown1B4	|TagBlock (Unknown1B4)	|0
RuntimeNodes	|TagBlock (RuntimeNodes)	|[1](#runtimenodes)
Unknown1CC	|Int32	|0


## Tag Blocks

### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
MeshIndex	|Int16	|0
MeshCount	|UInt16	|1
Unknown8	|Int32	|0
UnknownC	|Int32	|0
Unknown10	|Int32	|0
Unknown14	|Int32	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|monitor_node
ParentNode	|Int16	|-1
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
ImportNode	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, -1 }
DefaultScale	|Single	|1
InverseForward	|RealVector3d	|{ I: 1, J: 0, K: 0 }
InverseLeft	|RealVector3d	|{ I: 0, J: 1, K: 0 }
InverseUp	|RealVector3d	|{ I: 0, J: 0, K: 1 }
InversePosition	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
DistanceFromParent	|Single	|0


### MarkerGroups

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|front
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


### MarkerGroups_Markers

**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.2410686, Y: 0.002055298, Z: 0.4854707 }
Rotation	|RealQuaternion	|{ -0.2705983, 0.6532816, 0.2705978, -0.6532813 }
Scale	|Single	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
RenderMethod	|CachedTagInstance (Shader)	|[0x4DB0](../Shader/4DB0.md)
Properties	|TagBlock (Materials_Properties)	|0
Unknown	|Int32	|0
BreakableSurfaceIndex	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RenderMethod	|CachedTagInstance (Shader)	|[0x4DB3](../Shader/4DB3.md)
Properties	|TagBlock (Materials_Properties)	|0
Unknown	|Int32	|0
BreakableSurfaceIndex	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0


### RuntimeNodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Rotation	|RealQuaternion	|{ 0, 0, 0, -1 }
Translation	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
Scale	|Single	|1


