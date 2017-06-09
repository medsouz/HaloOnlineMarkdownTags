# [0x3CDB] 0x00003CDB

**Name:** ```0x00003CDB```

**Index:** ```0x3CDB```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|54989.07
LowFrequencyDeactivationScale	|Single	|1
HighFrequencyDeactivationScale	|Single	|1
CustomShapeRadius	|Single	|0
MaximumPenetrationDepthScale	|Single	|0
ImportVersion	|SByte	|1
Unused1	|Byte	|0
Unused2	|Byte	|0
Unused3	|Byte	|0
DampedSpringMotors	|TagBlock (DampedSpringMotors)	|0
PositionMotors	|TagBlock (PositionMotors)	|0
PhantomTypes	|TagBlock (PhantomTypes)	|0
PoweredChains	|TagBlock (PoweredChains)	|0
NodeEdges	|TagBlock (NodeEdges)	|0
RigidBodies	|TagBlock (RigidBodies)	|[1](#rigidbodies)
Materials	|TagBlock (Materials)	|[1](#materials)
Spheres	|TagBlock (Spheres)	|0
MultiSpheres	|TagBlock (MultiSpheres)	|0
Pills	|TagBlock (Pills)	|0
Boxes	|TagBlock (Boxes)	|0
Triangles	|TagBlock (Triangles)	|0
Polyhedra	|TagBlock (Polyhedra)	|[1](#polyhedra)
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[10](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[58](#polyhedronplaneequations)
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|0
ListShapes	|TagBlock (ListShapes)	|0
Mopps	|TagBlock (Mopps)	|0
MoppCodes	|Byte[]	|System.Byte[]
HingeConstraints	|TagBlock (HingeConstraints)	|0
RagdollConstraints	|TagBlock (RagdollConstraints)	|0
Regions	|TagBlock (Regions)	|[1](#regions)
Nodes	|TagBlock (Nodes)	|[5](#nodes)
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
LimitedHingeConstraints	|TagBlock (LimitedHingeConstraints)	|0
BallAndSocketConstraintBlock	|Single	|0
BallAndSocketConstraintBlock2	|Single	|0
BallAndSocketConstraintBlock3	|Single	|0
StiffSpringConstraintBlock	|Single	|0
StiffSpringConstraintBlock2	|Single	|0
StiffSpringConstraintBlock3	|Single	|0
PrismaticConstraintBlock	|Single	|0
PrismaticConstraintBlock2	|Single	|0
PrismaticConstraintBlock3	|Single	|0
Phantoms	|TagBlock (Phantoms)	|0


## Tag Blocks

### RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|0
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
BoundingSphereRadius	|Single	|6.560152
Flags	|UInt16	|0
MotionType	|Enum (MotionTypeValue)	|null
NoPhantomPowerAltRigidBody	|Int16	|-1
Size	|Enum (SizeValue)	|null
InertiaTensorScale	|Single	|1
LinearDampening	|Single	|0
AngularDampening	|Single	|0.05
CenterOfMassOffsetX	|Single	|0
CenterOfMassOffsetY	|Single	|0
CenterOfMassOffsetZ	|Single	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Mass	|Single	|54989.07
CenterOfMassI	|Single	|8.737301E-08
CenterOfMassJ	|Single	|-2.329505
CenterOfMassK	|Single	|-1.469414
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|151168.3
InertiaTensorXJ	|Single	|0.005929219
InertiaTensorXK	|Single	|0.0002695963
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0.005929219
InertiaTensorYJ	|Single	|66720.06
InertiaTensorYK	|Single	|4486.301
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0.0002695963
InertiaTensorZJ	|Single	|4486.301
InertiaTensorZK	|Single	|135726.3
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thin_hum
MaterialName	|StringId	|
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|p_man_cannon
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|55
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|36.65938
Mass	|Single	|54989.07
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|32
Unknown3	|Int32	|8
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
AabbHalfExtentsI	|Single	|1.385664
AabbHalfExtentsJ	|Single	|2.596806
AabbHalfExtentsK	|Single	|1.864592
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|1.192093E-07
AabbCenterJ	|Single	|-2.520013
AabbCenterK	|Single	|-1.763678
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|10
FourVectorsCapacity	|UInt32	|2147483658
Unknown8	|Int32	|37
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|58
PlaneEquationsCapacity	|UInt32	|2147483706
Unknown10	|UInt32	|0


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-1.385664
FourVectorsXJ	|Single	|-1.34696
FourVectorsXK	|Single	|-1.319775
FourVectorsXRadius	|Single	|-1.319775
FourVectorsYI	|Single	|-2.658807
FourVectorsYJ	|Single	|0.07679248
FourVectorsYK	|Single	|-2.134397
FourVectorsYRadius	|Single	|0.07679248
FourVectorsZI	|Single	|-1.187577
FourVectorsZJ	|Single	|-0.3356819
FourVectorsZK	|Single	|-2.037892
FourVectorsZRadius	|Single	|-2.037892


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-1.249689
FourVectorsXJ	|Single	|-1.145348
FourVectorsXK	|Single	|-1.135427
FourVectorsXRadius	|Single	|-0.9500456
FourVectorsYI	|Single	|-2.968717
FourVectorsYJ	|Single	|-4.833598
FourVectorsYK	|Single	|-4.748622
FourVectorsYRadius	|Single	|-4.876507
FourVectorsZI	|Single	|-0.3044611
FourVectorsZJ	|Single	|-0.6491941
FourVectorsZK	|Single	|-1.957503
FourVectorsZRadius	|Single	|-0.371297


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.8958473
FourVectorsXJ	|Single	|-0.8958473
FourVectorsXK	|Single	|-0.8320206
FourVectorsXRadius	|Single	|-0.5343375
FourVectorsYI	|Single	|-2.134397
FourVectorsYJ	|Single	|-0.2522891
FourVectorsYK	|Single	|-3.432667
FourVectorsYRadius	|Single	|-5.064867
FourVectorsZI	|Single	|-2.932071
FourVectorsZJ	|Single	|-2.932071
FourVectorsZK	|Single	|-2.738862
FourVectorsZRadius	|Single	|-2.549231


**3:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.5157908
FourVectorsXJ	|Single	|-0.5157908
FourVectorsXK	|Single	|-0.5042119
FourVectorsXRadius	|Single	|-0.5025645
FourVectorsYI	|Single	|-2.924506
FourVectorsYJ	|Single	|0.07679248
FourVectorsYK	|Single	|-5.116818
FourVectorsYRadius	|Single	|-4.626792
FourVectorsZI	|Single	|0.1009145
FourVectorsZJ	|Single	|0.1009145
FourVectorsZK	|Single	|-0.02615333
FourVectorsZRadius	|Single	|0.04369509


**4:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.1785168
FourVectorsXJ	|Single	|-0.1785168
FourVectorsXK	|Single	|5.960464E-08
FourVectorsXRadius	|Single	|0.1785168
FourVectorsYI	|Single	|-1.742641
FourVectorsYJ	|Single	|-0.2522891
FourVectorsYK	|Single	|0.07679248
FourVectorsYRadius	|Single	|-1.742641
FourVectorsZI	|Single	|-3.62827
FourVectorsZJ	|Single	|-3.338756
FourVectorsZK	|Single	|-2.23823
FourVectorsZRadius	|Single	|-3.62827


**5:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.1785168
FourVectorsXJ	|Single	|0.5025646
FourVectorsXK	|Single	|0.504212
FourVectorsXRadius	|Single	|0.5157908
FourVectorsYI	|Single	|-0.2522891
FourVectorsYJ	|Single	|-4.626792
FourVectorsYK	|Single	|-5.116818
FourVectorsYRadius	|Single	|-2.924506
FourVectorsZI	|Single	|-3.338756
FourVectorsZJ	|Single	|0.04369509
FourVectorsZK	|Single	|-0.02615333
FourVectorsZRadius	|Single	|0.1009145


**6:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.5157908
FourVectorsXJ	|Single	|0.5343375
FourVectorsXK	|Single	|0.8320206
FourVectorsXRadius	|Single	|0.8958473
FourVectorsYI	|Single	|0.07679248
FourVectorsYJ	|Single	|-5.064868
FourVectorsYK	|Single	|-3.432668
FourVectorsYRadius	|Single	|-2.134397
FourVectorsZI	|Single	|0.1009145
FourVectorsZJ	|Single	|-2.549231
FourVectorsZK	|Single	|-2.738862
FourVectorsZRadius	|Single	|-2.932071


**7:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.8958473
FourVectorsXJ	|Single	|0.9500456
FourVectorsXK	|Single	|1.135427
FourVectorsXRadius	|Single	|1.145348
FourVectorsYI	|Single	|-0.2522891
FourVectorsYJ	|Single	|-4.876507
FourVectorsYK	|Single	|-4.748622
FourVectorsYRadius	|Single	|-4.833598
FourVectorsZI	|Single	|-2.932071
FourVectorsZJ	|Single	|-0.371297
FourVectorsZK	|Single	|-1.957503
FourVectorsZRadius	|Single	|-0.6491941


**8:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|1.24969
FourVectorsXJ	|Single	|1.319775
FourVectorsXK	|Single	|1.319775
FourVectorsXRadius	|Single	|1.34696
FourVectorsYI	|Single	|-2.968717
FourVectorsYJ	|Single	|-2.134397
FourVectorsYK	|Single	|0.07679248
FourVectorsYRadius	|Single	|0.07679248
FourVectorsZI	|Single	|-0.3044611
FourVectorsZJ	|Single	|-2.037892
FourVectorsZK	|Single	|-2.037892
FourVectorsZRadius	|Single	|-0.3356819


**9:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|1.385664
FourVectorsXJ	|Single	|1.385664
FourVectorsXK	|Single	|1.385664
FourVectorsXRadius	|Single	|1.385664
FourVectorsYI	|Single	|-2.658807
FourVectorsYJ	|Single	|-2.658807
FourVectorsYK	|Single	|-2.658807
FourVectorsYRadius	|Single	|-2.658807
FourVectorsZI	|Single	|-1.187577
FourVectorsZJ	|Single	|-1.187577
FourVectorsZK	|Single	|-1.187577
FourVectorsZRadius	|Single	|-1.187577


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9996898
Unknown2	|Single	|0.01911562
Unknown3	|Single	|-0.01596557
Unknown4	|Single	|-1.353369


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9970112
Unknown2	|Single	|0
Unknown3	|Single	|-0.07725598
Unknown4	|Single	|-1.473269


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9934303
Unknown2	|Single	|-0.1134638
Unknown3	|Single	|-0.01490255
Unknown4	|Single	|-1.695936


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9897941
Unknown2	|Single	|-0.07355068
Unknown3	|Single	|-0.1220572
Unknown4	|Single	|-1.712031


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9894411
Unknown2	|Single	|-0.03014846
Unknown3	|Single	|0.1417653
Unknown4	|Single	|-1.282834


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9890822
Unknown2	|Single	|-0.07840526
Unknown3	|Single	|0.1247753
Unknown4	|Single	|-1.430819


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9035936
Unknown2	|Single	|-6.13681E-09
Unknown3	|Single	|-0.4283909
Unknown4	|Single	|-2.065554


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9009342
Unknown2	|Single	|-0.07666571
Unknown3	|Single	|-0.42713
Unknown4	|Single	|-2.22311


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8404819
Unknown2	|Single	|-0.1199565
Unknown3	|Single	|-0.5283942
Unknown4	|Single	|-2.558268


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8197483
Unknown2	|Single	|-0.1481339
Unknown3	|Single	|0.553235
Unknown4	|Single	|-1.29576


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.7396995
Unknown2	|Single	|-0.2092155
Unknown3	|Single	|-0.6395887
Unknown4	|Single	|-3.085357


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.696458
Unknown2	|Single	|0
Unknown3	|Single	|-0.7175975
Unknown4	|Single	|-2.727967


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6494008
Unknown2	|Single	|-0.1282562
Unknown3	|Single	|0.7495526
Unknown4	|Single	|-0.9640958


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6479025
Unknown2	|Single	|-0.143192
Unknown3	|Single	|-0.7481433
Unknown4	|Single	|-3.07966


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6366024
Unknown2	|Single	|-0.6919226
Unknown3	|Single	|0.340559
Unknown4	|Single	|-3.852518


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6096179
Unknown2	|Single	|-0.1098513
Unknown3	|Single	|0.7850469
Unknown4	|Single	|-0.848934


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.5731934
Unknown2	|Single	|-0.1969501
Unknown3	|Single	|-0.7953993
Unknown4	|Single	|-3.331461


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.5101049
Unknown2	|Single	|-0.8580447
Unknown3	|Single	|-0.059599
Unknown4	|Single	|-4.770382


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4862991
Unknown2	|Single	|0.1666271
Unknown3	|Single	|-0.8577579
Unknown4	|Single	|-2.908619


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4831952
Unknown2	|Single	|-0.006457765
Unknown3	|Single	|0.8754888
Unknown4	|Single	|-0.3564629


**20:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4817051
Unknown2	|Single	|-0.03317799
Unknown3	|Single	|0.8757051
Unknown4	|Single	|-0.4338596


**21:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4650281
Unknown2	|Single	|1.179647E-09
Unknown3	|Single	|0.8852959
Unknown4	|Single	|-0.3291964


**22:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.3924164
Unknown2	|Single	|-0.9196773
Unknown3	|Single	|-0.01425114
Unknown4	|Single	|-4.904056


**23:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2469872
Unknown2	|Single	|0.8655682
Unknown3	|Single	|-0.4356479
Unknown4	|Single	|-1.28024


**24:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.04248748
Unknown2	|Single	|0.9590894
Unknown3	|Single	|-0.2798969
Unknown4	|Single	|-0.7001246


**25:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-8.922004E-07
Unknown2	|Single	|-0.9997882
Unknown3	|Single	|-0.02058612
Unknown4	|Single	|-5.116273


**26:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-3.659281E-07
Unknown2	|Single	|-0.3089088
Unknown3	|Single	|-0.9510917
Unknown4	|Single	|-3.989135


**27:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-0.1411138
Unknown3	|Single	|0.9899934
Unknown4	|Single	|-0.6961619


**28:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-0.03359429
Unknown3	|Single	|0.9994357
Unknown4	|Single	|-0.1991042


**29:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|1
Unknown4	|Single	|-0.1009145


**30:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0.1906941
Unknown3	|Single	|-0.9816495
Unknown4	|Single	|-3.229378


**31:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0.9580838
Unknown3	|Single	|-0.2864881
Unknown4	|Single	|-0.7148


**32:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0.9999999
Unknown3	|Single	|0
Unknown4	|Single	|-0.07679247


**33:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.04248747
Unknown2	|Single	|0.9590895
Unknown3	|Single	|-0.2798969
Unknown4	|Single	|-0.7001246


**34:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2469872
Unknown2	|Single	|0.8655682
Unknown3	|Single	|-0.4356479
Unknown4	|Single	|-1.28024


**35:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.3924166
Unknown2	|Single	|-0.9196772
Unknown3	|Single	|-0.0142508
Unknown4	|Single	|-4.904055


**36:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4650281
Unknown2	|Single	|0
Unknown3	|Single	|0.8852959
Unknown4	|Single	|-0.3291964


**37:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4817049
Unknown2	|Single	|-0.03317798
Unknown3	|Single	|0.8757051
Unknown4	|Single	|-0.4338595


**38:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4831951
Unknown2	|Single	|-0.006457719
Unknown3	|Single	|0.8754889
Unknown4	|Single	|-0.3564627


**39:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4862991
Unknown2	|Single	|0.1666271
Unknown3	|Single	|-0.8577579
Unknown4	|Single	|-2.908619


**40:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.5101058
Unknown2	|Single	|-0.8580443
Unknown3	|Single	|-0.05959897
Unknown4	|Single	|-4.770381


**41:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.5731934
Unknown2	|Single	|-0.1969501
Unknown3	|Single	|-0.7953992
Unknown4	|Single	|-3.331461


**42:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6096178
Unknown2	|Single	|-0.1098513
Unknown3	|Single	|0.785047
Unknown4	|Single	|-0.848934


**43:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6366028
Unknown2	|Single	|-0.6919218
Unknown3	|Single	|0.34056
Unknown4	|Single	|-3.852514


**44:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6479025
Unknown2	|Single	|-0.143192
Unknown3	|Single	|-0.7481433
Unknown4	|Single	|-3.07966


**45:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6494008
Unknown2	|Single	|-0.1282562
Unknown3	|Single	|0.7495525
Unknown4	|Single	|-0.9640963


**46:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6964581
Unknown2	|Single	|4.198222E-09
Unknown3	|Single	|-0.7175975
Unknown4	|Single	|-2.727967


**47:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.7396994
Unknown2	|Single	|-0.2092155
Unknown3	|Single	|-0.6395888
Unknown4	|Single	|-3.085357


**48:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.819748
Unknown2	|Single	|-0.148134
Unknown3	|Single	|0.5532355
Unknown4	|Single	|-1.29576


**49:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8404818
Unknown2	|Single	|-0.1199565
Unknown3	|Single	|-0.5283945
Unknown4	|Single	|-2.558268


**50:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.900934
Unknown2	|Single	|-0.07666568
Unknown3	|Single	|-0.4271302
Unknown4	|Single	|-2.22311


**51:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9035934
Unknown2	|Single	|0
Unknown3	|Single	|-0.428391
Unknown4	|Single	|-2.065555


**52:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9890822
Unknown2	|Single	|-0.07840526
Unknown3	|Single	|0.1247754
Unknown4	|Single	|-1.43082


**53:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9894411
Unknown2	|Single	|-0.03014838
Unknown3	|Single	|0.1417653
Unknown4	|Single	|-1.282834


**54:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9897941
Unknown2	|Single	|-0.07355067
Unknown3	|Single	|-0.1220572
Unknown4	|Single	|-1.712031


**55:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9934304
Unknown2	|Single	|-0.1134638
Unknown3	|Single	|-0.01490255
Unknown4	|Single	|-1.695937


**56:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9970113
Unknown2	|Single	|0
Unknown3	|Single	|-0.07725598
Unknown4	|Single	|-1.47327


**57:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9996899
Unknown2	|Single	|0.01911566
Unknown3	|Single	|-0.01596544
Unknown4	|Single	|-1.353369


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
RigidBodies	|TagBlock (Regions_Permutations_RigidBodies)	|[1](#regions_permutations_rigidbodies)


### Regions_Permutations_RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
RigidBodyIndex	|Int16	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|man_cannon
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|flap_1
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|2
Child	|Int16	|-1


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|flap_2
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|3
Child	|Int16	|-1


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|turbine
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|-1
Child	|Int16	|4


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|fan
Flags	|UInt16	|0
Parent	|Int16	|3
Sibling	|Int16	|-1
Child	|Int16	|-1


