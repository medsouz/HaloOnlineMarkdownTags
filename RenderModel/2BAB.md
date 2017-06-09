# [0x2BAB] 0x00002BAB

**Name:** ```0x00002BAB```

**Index:** ```0x2BAB```

**Tag Group:** ```RenderModel (mode)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|crate_space
Flags	|Enum (FlagsValue)	|null
Unknown6	|Int16	|0
Checksum	|Int32	|386273036
Regions	|TagBlock (Regions)	|[1](#regions)
Unknown18	|Int32	|0
InstanceStartingMeshIndex	|Int32	|-1
Instances	|TagBlock (Instances)	|0
Unknown2C	|Int32	|0
Nodes	|TagBlock (Nodes)	|[1](#nodes)
MarkerGroups	|TagBlock (MarkerGroups)	|[7](#markergroups)
Materials	|TagBlock (Materials)	|[2](#materials)
Unknown54	|Int32	|0
Unknown58	|Int32	|0
Unknown5C	|Int32	|0
Unknown60	|Int32	|0
Geometry	|RenderGeometry	|BlamCore.Geometry.RenderGeometry
UnknownE8	|TagBlock (UnknownE8)	|0
UnknownF4	|Int32	|1063594078
UnknownF8	|Int32	|-1081415402
UnknownFC	|Int32	|0
Unknown100	|Int32	|-1081415402
Unknown104	|Int32	|1071069661
Unknown108	|Int32	|-2147483648
Unknown10C	|Int32	|-1082615617
Unknown110	|Int32	|-2147483648
Unknown114	|Int32	|0
Unknown118	|Int32	|0
Unknown11C	|Int32	|0
Unknown120	|Int32	|0
Unknown124	|Int32	|0
Unknown128	|Int32	|0
Unknown12C	|Int32	|0
Unknown130	|Int32	|0
Unknown134	|Int32	|1063594078
Unknown138	|Int32	|-1081415402
Unknown13C	|Int32	|0
Unknown140	|Int32	|-1081415402
Unknown144	|Int32	|1071069661
Unknown148	|Int32	|-2147483648
Unknown14C	|Int32	|-1082615617
Unknown150	|Int32	|-2147483648
Unknown154	|Int32	|0
Unknown158	|Int32	|0
Unknown15C	|Int32	|0
Unknown160	|Int32	|0
Unknown164	|Int32	|0
Unknown168	|Int32	|0
Unknown16C	|Int32	|0
Unknown170	|Int32	|0
Unknown174	|Int32	|1063594078
Unknown178	|Int32	|-1081415402
Unknown17C	|Int32	|0
Unknown180	|Int32	|-1081415402
Unknown184	|Int32	|1071069661
Unknown188	|Int32	|-2147483648
Unknown18C	|Int32	|-1082615617
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
Name	|StringId	|object
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
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
Name	|StringId	|node
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
Name	|StringId	|hint_bunker
Markers	|TagBlock (MarkerGroups_Markers)	|[8](#markergroups_markers)


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hint_corner_left
Markers	|TagBlock (MarkerGroups_Markers)	|[2](#markergroups_markers)


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hint_corner_right
Markers	|TagBlock (MarkerGroups_Markers)	|[2](#markergroups_markers)


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hint_hoist_crouch
Markers	|TagBlock (MarkerGroups_Markers)	|[4](#markergroups_markers)


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hint_hoist_stand
Markers	|TagBlock (MarkerGroups_Markers)	|[4](#markergroups_markers)


**5:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hint_mount_crouch
Markers	|TagBlock (MarkerGroups_Markers)	|[8](#markergroups_markers)


**6:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hint_vault_crouch
Markers	|TagBlock (MarkerGroups_Markers)	|[4](#markergroups_markers)


### MarkerGroups_Markers

**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.430788, Y: 0.2520621, Z: 0.4526123 }
Rotation	|RealQuaternion	|{ 0.5000003, -0.4999999, 0.4999997, -0.5000001 }
Scale	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.00130249, Y: 0.2680261, Z: 0.002612305 }
Rotation	|RealQuaternion	|{ -0.7071069, 0.7071068, 4.225001E-07, 4.150001E-08 }
Scale	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.4251202, Y: 0.2569916, Z: 0.4526123 }
Rotation	|RealQuaternion	|{ 0.4999997, -0.5, -0.5000003, 0.5 }
Scale	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.00130249, Y: 0.2680261, Z: 0.9026122 }
Rotation	|RealQuaternion	|{ 4.125E-07, 4.76E-08, 0.7071068, -0.7071068 }
Scale	|Single	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.00130249, Y: -0.2695761, Z: 0.9026122 }
Rotation	|RealQuaternion	|{ -2.37E-08, 4.194001E-07, -0.7071068, -0.7071068 }
Scale	|Single	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.4309882, Y: -0.2569682, Z: 0.4526123 }
Rotation	|RealQuaternion	|{ -0.4999999, -0.5000003, 0.5, 0.4999998 }
Scale	|Single	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.00130249, Y: -0.224398, Z: 0.002612305 }
Rotation	|RealQuaternion	|{ -0.7071068, -0.7071068, 2.37E-08, -4.194001E-07 }
Scale	|Single	|0


**7:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.4322595, Y: -0.2601148, Z: 0.4526123 }
Rotation	|RealQuaternion	|{ -0.5000001, -0.4999997, -0.5, -0.5000002 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.3068487, Y: -0.2330794, Z: 0.002612305 }
Rotation	|RealQuaternion	|{ 0.5000001, -0.5000004, 0.4999996, 0.4999999 }
Scale	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.3266779, Y: 0.2487934, Z: 0.002612305 }
Rotation	|RealQuaternion	|{ -0.5000004, -0.5, -0.5, 0.4999996 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.3317633, Y: 0.2525735, Z: 0.002612305 }
Rotation	|RealQuaternion	|{ -0.5000004, -0.5, -0.5, 0.4999996 }
Scale	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.4486267, Y: -0.1629344, Z: 0.002612305 }
Rotation	|RealQuaternion	|{ 0.5000001, -0.5000002, 0.4999997, 0.4999999 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.3858679, Y: -0.213569, Z: 0.1453436 }
Rotation	|RealQuaternion	|{ -0.04362048, 1.558E-07, -0.9990482, 4.251E-07 }
Scale	|Single	|0.4999999


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.3423492, Y: 0.213569, Z: 0.6427499 }
Rotation	|RealQuaternion	|{ 4.18E-07, -0.9990482, -3.186E-07, 0.0436189 }
Scale	|Single	|0.5


**2:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.3490252, Y: -0.213569, Z: 0.6474572 }
Rotation	|RealQuaternion	|{ -0.9990483, 5.277E-07, -0.04361835, -1.974E-07 }
Scale	|Single	|0.5


**3:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.3923309, Y: 0.2135691, Z: 0.1524766 }
Rotation	|RealQuaternion	|{ 3.46E-08, 0.04362097, 5.206E-07, -0.9990482 }
Scale	|Single	|0.5


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.325, Y: -0.1770954, Z: 0.893231 }
Rotation	|RealQuaternion	|{ -0.7071068, -5.606E-07, -0.7071068, 9.130002E-08 }
Scale	|Single	|0.65


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.325, Y: 0.1770952, Z: 0.8932311 }
Rotation	|RealQuaternion	|{ -2.711E-07, 0.7071068, -2.796E-07, -0.7071068 }
Scale	|Single	|0.65


**2:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.224613, Y: 0.2029359, Z: -3.42914E-07 }
Rotation	|RealQuaternion	|{ 1.0438E-06, -0.7071068, -1.0185E-06, -0.7071068 }
Scale	|Single	|0.45


**3:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.2256384, Y: -0.2029369, Z: -1.84328E-07 }
Rotation	|RealQuaternion	|{ 0.7071068, -2.67E-08, -0.7071068, 5.493001E-07 }
Scale	|Single	|0.45


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.225, Y: -0.245, Z: 0.8 }
Rotation	|RealQuaternion	|{ 0.7071064, -0.7071072, -1.02E-06, 1.02E-06 }
Scale	|Single	|0.7


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.225, Y: -0.245, Z: 0.09999999 }
Rotation	|RealQuaternion	|{ 5.058E-07, -6.294E-07, 0.7071071, -0.7071065 }
Scale	|Single	|0.7


**2:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.225, Y: 0.245, Z: 0.8 }
Rotation	|RealQuaternion	|{ -0.5, -0.5, -0.5000004, -0.4999996 }
Scale	|Single	|0.45


**3:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.225, Y: 0.245, Z: 0.8 }
Rotation	|RealQuaternion	|{ -0.7071071, -0.7071066, -4.299001E-07, -7.053001E-07 }
Scale	|Single	|0.7


**4:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.225, Y: 0.245, Z: 0.1 }
Rotation	|RealQuaternion	|{ -2.135E-07, 3.372E-07, -0.7071071, -0.7071065 }
Scale	|Single	|0.7


**5:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.225, Y: -0.245, Z: 0.8 }
Rotation	|RealQuaternion	|{ -0.4999996, 0.4999999, 0.5000004, -0.5000001 }
Scale	|Single	|0.45


**6:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.225, Y: 0.245, Z: 0.09999999 }
Rotation	|RealQuaternion	|{ -0.5000005, -0.5000002, 0.4999996, 0.4999997 }
Scale	|Single	|0.45


**7:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.225, Y: -0.245, Z: 0.09999999 }
Rotation	|RealQuaternion	|{ -0.5000004, 0.5000002, -0.4999994, 0.5 }
Scale	|Single	|0.45


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.4666174, Y: -8.107E-09, Z: 0.1499999 }
Rotation	|RealQuaternion	|{ -0.04361905, 9.06E-08, -0.9990482, -7.92E-08 }
Scale	|Single	|0.5


**1:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.4752447, Y: 1.88745E-07, Z: 0.1519025 }
Rotation	|RealQuaternion	|{ -1.509E-07, 0.04361905, -6.6E-09, -0.9990482 }
Scale	|Single	|0.5


**2:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0, Y: 0.2813388, Z: 0 }
Rotation	|RealQuaternion	|{ -4.500001E-08, -1.686E-07, -0.7071067, -0.7071069 }
Scale	|Single	|0.9


**3:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -6.10352E-07, Y: -0.2822815, Z: 0 }
Rotation	|RealQuaternion	|{ 1.068E-07, -2.304E-07, 0.7071067, -0.7071069 }
Scale	|Single	|0.9


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
RenderMethod	|CachedTagInstance (Shader)	|[[0x2BAE] 0x00002BAE](../Shader/2BAE.md)
Properties	|TagBlock (Materials_Properties)	|0
Unknown	|Int32	|0
BreakableSurfaceIndex	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RenderMethod	|CachedTagInstance (Shader)	|[[0x2BAF] 0x00002BAF](../Shader/2BAF.md)
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


