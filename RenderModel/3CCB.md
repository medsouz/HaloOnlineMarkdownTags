# [0x3CCB] objects\weapons\turret\missile_pod\missile_pod_vehicle\missile_pod_vehicle

**Name:** ```objects\weapons\turret\missile_pod\missile_pod_vehicle\missile_pod_vehicle```

**Index:** ```0x3CCB```

**Tag Group:** ```RenderModel (mode)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|missile_pod_vehicle
Flags	|Enum (FlagsValue)	|null
Unknown6	|Int16	|0
Checksum	|Int32	|454168088
Regions	|TagBlock (Regions)	|[2](#regions)
Unknown18	|Int32	|0
InstanceStartingMeshIndex	|Int32	|-1
Instances	|TagBlock (Instances)	|0
Unknown2C	|Int32	|0
Nodes	|TagBlock (Nodes)	|[3](#nodes)
MarkerGroups	|TagBlock (MarkerGroups)	|[20](#markergroups)
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
RuntimeNodes	|TagBlock (RuntimeNodes)	|[3](#runtimenodes)
Unknown1CC	|Int32	|0


## Tag Blocks

### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hull
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|pod
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
MeshIndex	|Int16	|0
MeshCount	|UInt16	|1
Unknown8	|Int32	|0
UnknownC	|Int32	|0
Unknown10	|Int32	|0
Unknown14	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
MeshIndex	|Int16	|1
MeshCount	|UInt16	|1
Unknown8	|Int32	|0
UnknownC	|Int32	|0
Unknown10	|Int32	|0
Unknown14	|Int32	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|legs
ParentNode	|Int16	|-1
FirstChildNode	|Int16	|1
NextSiblingNode	|Int16	|-1
ImportNode	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: 0.009698913, Y: 0, Z: 4.999161E-05 }
DefaultRotation	|RealQuaternion	|{ 0, 0, 0, 1 }
DefaultScale	|Single	|1
InverseForward	|RealVector3d	|{ I: 1, J: 0, K: 0 }
InverseLeft	|RealVector3d	|{ I: 0, J: 1, K: 0 }
InverseUp	|RealVector3d	|{ I: 0, J: 0, K: 1 }
InversePosition	|RealPoint3d	|{ X: -0.009698913, Y: 0, Z: -4.999161E-05 }
DistanceFromParent	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hinge_base
ParentNode	|Int16	|0
FirstChildNode	|Int16	|2
NextSiblingNode	|Int16	|-1
ImportNode	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: -0.003081543, Y: 1.677123E-06, Z: 0.1550344 }
DefaultRotation	|RealQuaternion	|{ -1.59E-08, 0, -1.27E-08, -1 }
DefaultScale	|Single	|1
InverseForward	|RealVector3d	|{ I: 1, J: -2.54E-08, K: 4.0386E-16 }
InverseLeft	|RealVector3d	|{ I: 2.54E-08, J: 1, K: -3.18E-08 }
InverseUp	|RealVector3d	|{ I: 4.0386E-16, J: 3.18E-08, K: 1 }
InversePosition	|RealPoint3d	|{ X: -0.00661737, Y: -1.681886E-06, Z: -0.1550844 }
DistanceFromParent	|Single	|0.155065


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gun
ParentNode	|Int16	|1
FirstChildNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
ImportNode	|Int16	|0
DefaultTranslation	|RealPoint3d	|{ X: -0.02456449, Y: -1.598314E-06, Z: 0.05945812 }
DefaultRotation	|RealQuaternion	|{ 1.026834E-08, 0.4027468, -1.277922E-08, -0.9153115 }
DefaultScale	|Single	|1
InverseForward	|RealVector3d	|{ I: 0.6755901, J: -4.052285E-08, K: -0.7372774 }
InverseLeft	|RealVector3d	|{ I: 2.537957E-08, J: 1, K: -3.170674E-08 }
InverseUp	|RealVector3d	|{ I: 0.7372774, J: 2.708971E-09, K: 0.6755901 }
InversePosition	|RealPoint3d	|{ X: -0.1460525, Y: -7.760249E-08, Z: -0.1581748 }
DistanceFromParent	|Single	|0.06433259


### MarkerGroups

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|camera
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|foot_left
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|foot_right
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gunner_left_foot
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gunner_left_hand
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**5:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gunner_left_hand_chief
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**6:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gunner_right_foot
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**7:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gunner_right_hand
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**8:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gunner_right_hand_chief
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**9:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|indirect_barrel
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**10:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|indirect_barrel_f
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**11:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|primary_ejection
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**12:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|primary_trigger
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**13:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|right_hand
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**14:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|right_hand_elite
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**15:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|target_turret
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**16:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|tripod_spawn
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**17:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|turret_g
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**18:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|turret_g_enter
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


**19:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|weapon_spawn
Markers	|TagBlock (MarkerGroups_Markers)	|[1](#markergroups_markers)


### MarkerGroups_Markers

**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.2188438, Y: -9.091E-09, Z: 0.3507455 }
Rotation	|RealQuaternion	|{ 2.523E-07, -6.267E-07, 5.983E-07, 1 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.2634355, Y: 0.08932114, Z: 0.007312641 }
Rotation	|RealQuaternion	|{ -0.000633791, -2.592E-07, 0.3142323, 0.9493459 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.2036067, Y: -0.1241539, Z: 0.007312584 }
Rotation	|RealQuaternion	|{ 0.0002059017, -9.454E-07, -0.1022487, 0.9947588 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.2755585, Y: 0.09268505, Z: 0.005299094 }
Rotation	|RealQuaternion	|{ -7.4E-09, -1.128E-07, 0.0871558, 0.9961947 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.07646291, Y: 0.00111777, Z: 0.2396733 }
Rotation	|RealQuaternion	|{ 0.1695321, 0.2131513, -0.03758462, 0.9614639 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.0768431, Y: 0.00111777, Z: 0.2398506 }
Rotation	|RealQuaternion	|{ 0.1503097, 0.227116, -0.1212387, 0.9545296 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.2755585, Y: -0.101562, Z: 0.005299088 }
Rotation	|RealQuaternion	|{ 7.500001E-09, -9.580001E-08, -0.07845901, 0.9969174 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.1327906, Y: -0.002797358, Z: 0.1962027 }
Rotation	|RealQuaternion	|{ -0.1618415, 0.3569317, 0.06293646, 0.9178486 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.1330999, Y: -0.002797358, Z: 0.1964861 }
Rotation	|RealQuaternion	|{ -0.130117, 0.3696789, 0.1426928, 0.9088707 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|2
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.4904088, Y: -8.5339E-08, Z: 0.09109831 }
Rotation	|RealQuaternion	|{ 0.5, -0.5000001, -0.5, 0.4999999 }
Scale	|Single	|0.02500001


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|2
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.5107972, Y: -8.5339E-08, Z: 0.09109838 }
Rotation	|RealQuaternion	|{ 0.5, -0.5000001, -0.5, 0.4999999 }
Scale	|Single	|0.02500001


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.0400704, Y: -0.05105857, Z: 0.2765049 }
Rotation	|RealQuaternion	|{ -0.03084363, -0.03084369, -0.706434, 0.7064337 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.2375669, Y: -1.658199E-06, Z: 0.4801557 }
Rotation	|RealQuaternion	|{ 1.608E-07, -0.4027469, -9.55E-08, 0.9153115 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.1152675, Y: -0.003245043, Z: 0.3046697 }
Rotation	|RealQuaternion	|{ -0.004157446, 0.2715637, 0.001173746, 0.9624108 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.1253116, Y: -0.005075043, Z: 0.310884 }
Rotation	|RealQuaternion	|{ -0.004157446, 0.2715637, 0.001173746, 0.9624108 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -3.24845E-07, Y: 6.8284E-08, Z: 0.2511786 }
Rotation	|RealQuaternion	|{ 2.523E-07, -6.267E-07, 5.983E-07, 1 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.003081867, Y: 1.737432E-06, Z: 0.2727525 }
Rotation	|RealQuaternion	|{ 2.235E-07, -6.109E-07, 6.333E-07, 1 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|0
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.3118531, Y: 1.651344E-06, Z: 0.2494925 }
Rotation	|RealQuaternion	|{ 1.49E-07, -5.215E-07, 6.408E-07, 1 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: 0.1033982, Y: -0.03503817, Z: 0.1930214 }
Rotation	|RealQuaternion	|{ 0.2588196, 7.416E-07, 0.9659257, -9.505E-07 }
Scale	|Single	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
RegionIndex	|SByte	|-1
PermutationIndex	|SByte	|-1
NodeIndex	|SByte	|1
Unknown3	|SByte	|0
Translation	|RealPoint3d	|{ X: -0.1245474, Y: 0.007445264, Z: 0.1887042 }
Rotation	|RealQuaternion	|{ 3.216E-07, 0.0654029, 5.466E-07, 0.997859 }
Scale	|Single	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
RenderMethod	|CachedTagInstance (Shader)	|[[0x217D] 0x0000217D](../Shader/217D.md)
Properties	|TagBlock (Materials_Properties)	|0
Unknown	|Int32	|0
BreakableSurfaceIndex	|SByte	|0
Unknown2	|SByte	|0
Unknown3	|SByte	|0
Unknown4	|SByte	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RenderMethod	|CachedTagInstance (Shader)	|[[0x2190] 0x00002190](../Shader/2190.md)
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
Rotation	|RealQuaternion	|{ 0, 0, 0, 1 }
Translation	|RealPoint3d	|{ X: 0.009698913, Y: 0, Z: 4.999161E-05 }
Scale	|Single	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Rotation	|RealQuaternion	|{ -1.59E-08, 0, -1.27E-08, -1 }
Translation	|RealPoint3d	|{ X: -0.003081543, Y: 1.677123E-06, Z: 0.1550344 }
Scale	|Single	|1


**2:**

Name	| Type	| Value
---	|---	|---	|
Rotation	|RealQuaternion	|{ 1.026834E-08, 0.4027468, -1.277922E-08, -0.9153115 }
Translation	|RealPoint3d	|{ X: -0.02456449, Y: -1.598314E-06, Z: 0.05945812 }
Scale	|Single	|1


