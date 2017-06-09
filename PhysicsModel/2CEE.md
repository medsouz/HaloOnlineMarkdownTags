# [0x2CEE] 0x00002CEE

**Name:** ```0x00002CEE```

**Index:** ```0x2CEE```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|36.81903
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
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[5](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[36](#polyhedronplaneequations)
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|0
ListShapes	|TagBlock (ListShapes)	|0
Mopps	|TagBlock (Mopps)	|0
MoppCodes	|Byte[]	|System.Byte[]
HingeConstraints	|TagBlock (HingeConstraints)	|0
RagdollConstraints	|TagBlock (RagdollConstraints)	|0
Regions	|TagBlock (Regions)	|[1](#regions)
Nodes	|TagBlock (Nodes)	|[1](#nodes)
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
Node	|Int16	|-1
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
BoundingSphereRadius	|Single	|0.3983456
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
Mass	|Single	|36.81903
CenterOfMassI	|Single	|0.01003465
CenterOfMassJ	|Single	|-0.02019403
CenterOfMassK	|Single	|0.01228835
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0.225253
InertiaTensorXJ	|Single	|0.007319172
InertiaTensorXK	|Single	|0.01574243
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0.007319172
InertiaTensorYJ	|Single	|0.8515415
InertiaTensorYK	|Single	|0.003410916
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0.01574243
InertiaTensorZJ	|Single	|0.003410916
InertiaTensorZK	|Single	|0.8887737
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick_hum_hornet
MaterialName	|StringId	|
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phy_jet_l
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|213
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.01840951
Mass	|Single	|36.81903
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
AabbHalfExtentsI	|Single	|0.3305545
AabbHalfExtentsJ	|Single	|0.1382748
AabbHalfExtentsK	|Single	|0.1118716
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.005867511
AabbCenterJ	|Single	|0.004833654
AabbCenterK	|Single	|0.02168321
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|5
FourVectorsCapacity	|UInt32	|2147483653
Unknown8	|Int32	|20
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|36
PlaneEquationsCapacity	|UInt32	|2147483684
Unknown10	|UInt32	|0


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.324687
FourVectorsXJ	|Single	|-0.3175257
FourVectorsXK	|Single	|-0.2424055
FourVectorsXRadius	|Single	|-0.2316536
FourVectorsYI	|Single	|-0.05804222
FourVectorsYJ	|Single	|-0.08076799
FourVectorsYK	|Single	|-0.126675
FourVectorsYRadius	|Single	|0.01755781
FourVectorsZI	|Single	|0.08458954
FourVectorsZJ	|Single	|-0.0177624
FourVectorsZK	|Single	|-0.05461244
FourVectorsZRadius	|Single	|-0.04526044


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.2316536
FourVectorsXJ	|Single	|-0.1950387
FourVectorsXK	|Single	|-0.1183148
FourVectorsXRadius	|Single	|-0.08143771
FourVectorsYI	|Single	|0.03774853
FourVectorsYJ	|Single	|-0.09904145
FourVectorsYK	|Single	|0.004833654
FourVectorsYRadius	|Single	|0.004833654
FourVectorsZI	|Single	|0.04099529
FourVectorsZJ	|Single	|0.1019939
FourVectorsZK	|Single	|-0.0901884
FourVectorsZRadius	|Single	|0.1335548


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.04724223
FourVectorsXJ	|Single	|-0.02972907
FourVectorsXK	|Single	|0.08192267
FourVectorsXRadius	|Single	|0.08352088
FourVectorsYI	|Single	|0.1431084
FourVectorsYJ	|Single	|0.1269702
FourVectorsYK	|Single	|0.1243038
FourVectorsYRadius	|Single	|0.1372128
FourVectorsZI	|Single	|0.02168321
FourVectorsZJ	|Single	|-0.0427057
FourVectorsZK	|Single	|-0.06026223
FourVectorsZRadius	|Single	|0.01528955


**3:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.1174729
FourVectorsXJ	|Single	|0.14076
FourVectorsXK	|Single	|0.218927
FourVectorsXRadius	|Single	|0.2540986
FourVectorsYI	|Single	|0.004833654
FourVectorsYJ	|Single	|0.004833654
FourVectorsYK	|Single	|-0.09772778
FourVectorsYRadius	|Single	|0.03774838
FourVectorsZI	|Single	|0.1223266
FourVectorsZJ	|Single	|-0.08156209
FourVectorsZK	|Single	|0.1123968
FourVectorsZRadius	|Single	|0.04099533


**4:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.2540987
FourVectorsXJ	|Single	|0.2648504
FourVectorsXK	|Single	|0.3286242
FourVectorsXRadius	|Single	|0.336422
FourVectorsYI	|Single	|0.0175578
FourVectorsYJ	|Single	|-0.1334411
FourVectorsYK	|Single	|-0.09160089
FourVectorsYRadius	|Single	|-0.1138814
FourVectorsZI	|Single	|-0.04526049
FourVectorsZJ	|Single	|-0.07358749
FourVectorsZK	|Single	|0.05874068
FourVectorsZRadius	|Single	|-0.0333764


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.7651849
Unknown2	|Single	|0.615101
Unknown3	|Single	|-0.1901124
Unknown4	|Single	|-0.1966622


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.7427627
Unknown2	|Single	|0.6519322
Unknown3	|Single	|-0.1526041
Unknown4	|Single	|-0.1904171


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.5018228
Unknown2	|Single	|0.8422046
Unknown3	|Single	|-0.1971429
Unknown4	|Single	|-0.1399591


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4552502
Unknown2	|Single	|-0.8754057
Unknown3	|Single	|0.1625184
Unknown4	|Single	|-0.2123717


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4465037
Unknown2	|Single	|0.8317417
Unknown3	|Single	|-0.3299094
Unknown4	|Single	|-0.1329696


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.3944553
Unknown2	|Single	|0.08870853
Unknown3	|Single	|-0.9146234
Unknown4	|Single	|-0.1343308


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.3586538
Unknown2	|Single	|0.0869983
Unknown3	|Single	|-0.9294077
Unknown4	|Single	|-0.1266764


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.3226354
Unknown2	|Single	|-0.9106079
Unknown3	|Single	|0.2582625
Unknown4	|Single	|-0.1794555


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.3060526
Unknown2	|Single	|0.6243277
Unknown3	|Single	|0.7187119
Unknown4	|Single	|-0.1239294


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2940208
Unknown2	|Single	|0.6440693
Unknown3	|Single	|0.7062057
Unknown4	|Single	|-0.1213748


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2665631
Unknown2	|Single	|0.5110326
Unknown3	|Single	|-0.8171841
Unknown4	|Single	|-0.107709


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.1675819
Unknown2	|Single	|-0.1142474
Unknown3	|Single	|0.9792159
Unknown4	|Single	|-0.1438742


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.1292894
Unknown2	|Single	|0.4393697
Unknown3	|Single	|-0.8889536
Unknown4	|Single	|-0.09759391


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.03942457
Unknown2	|Single	|-0.2260997
Unknown3	|Single	|-0.9733061
Unknown4	|Single	|-0.09135254


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.02336141
Unknown2	|Single	|-0.2671568
Unknown3	|Single	|0.9633698
Unknown4	|Single	|-0.1292738


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.01571804
Unknown2	|Single	|0.9688607
Unknown3	|Single	|-0.2471068
Unknown4	|Single	|-0.1340366


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.006558828
Unknown2	|Single	|-0.984424
Unknown3	|Single	|0.1756879
Unknown4	|Single	|-0.1166971


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.001612599
Unknown2	|Single	|-0.9821305
Unknown3	|Single	|0.1881939
Unknown4	|Single	|-0.1167808


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.03266555
Unknown2	|Single	|0.1909944
Unknown3	|Single	|-0.9810475
Unknown4	|Single	|-0.08553748


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.03326533
Unknown2	|Single	|-0.02776499
Unknown3	|Single	|-0.9990608
Unknown4	|Single	|-0.0860337


**20:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.0361417
Unknown2	|Single	|0.9849439
Unknown3	|Single	|-0.1690546
Unknown4	|Single	|-0.1355807


**21:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.0441415
Unknown2	|Single	|0.6217436
Unknown3	|Single	|0.7819759
Unknown4	|Single	|-0.1038472


**22:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.05631184
Unknown2	|Single	|-0.04087973
Unknown3	|Single	|0.9975759
Unknown4	|Single	|-0.1284476


**23:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.06627451
Unknown2	|Single	|0.6375881
Unknown3	|Single	|0.7675214
Unknown4	|Single	|-0.1047556


**24:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.1402232
Unknown2	|Single	|-0.9653696
Unknown3	|Single	|0.2199977
Unknown4	|Single	|-0.1497691


**25:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.1732908
Unknown2	|Single	|-0.9538154
Unknown3	|Single	|0.2453703
Unknown4	|Single	|-0.1587311


**26:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2616839
Unknown2	|Single	|0.2928375
Unknown3	|Single	|-0.9196563
Unknown4	|Single	|-0.1132592


**27:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2692926
Unknown2	|Single	|0.6463413
Unknown3	|Single	|0.7139499
Unknown4	|Single	|-0.1220938


**28:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2790524
Unknown2	|Single	|0.1962143
Unknown3	|Single	|-0.9400157
Unknown4	|Single	|-0.1168975


**29:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4027269
Unknown2	|Single	|0.3151783
Unknown3	|Single	|0.859345
Unknown4	|Single	|-0.1539537


**30:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4140866
Unknown2	|Single	|0.3536441
Unknown3	|Single	|0.83873
Unknown4	|Single	|-0.1529523


**31:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4391337
Unknown2	|Single	|0.1957602
Unknown3	|Single	|-0.876835
Unknown4	|Single	|-0.1547064


**32:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.5149608
Unknown2	|Single	|0.8430938
Unknown3	|Single	|-0.1549466
Unknown4	|Single	|-0.1563242


**33:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.5290974
Unknown2	|Single	|0.8262275
Unknown3	|Single	|-0.1934012
Unknown4	|Single	|-0.1577031


**34:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8461218
Unknown2	|Single	|0.5189618
Unknown3	|Single	|-0.1214769
Unknown4	|Single	|-0.2296083


**35:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8682715
Unknown2	|Single	|0.4939545
Unknown3	|Single	|-0.04597384
Unknown4	|Single	|-0.2373879


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
Name	|StringId	|jet_l
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|-1


