# [0x2CFD] objects\vehicles\hornet\garbage\flap\flap_snow

**Name:** ```objects\vehicles\hornet\garbage\flap\flap_snow```

**Index:** ```0x2CFD```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|2.046774
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
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[2](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[12](#polyhedronplaneequations)
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
BoundingSphereRadius	|Single	|0.1705986
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
Mass	|Single	|2.046774
CenterOfMassI	|Single	|0.01242209
CenterOfMassJ	|Single	|0.002703803
CenterOfMassK	|Single	|0.001395969
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0.005884587
InertiaTensorXJ	|Single	|0.0002588862
InertiaTensorXK	|Single	|0.0004738052
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0.0002588862
InertiaTensorYJ	|Single	|0.006520117
InertiaTensorYK	|Single	|0.000325706
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0.0004738052
InertiaTensorZJ	|Single	|0.000325706
InertiaTensorZK	|Single	|0.0119621
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
Name	|StringId	|phy_flap
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|213
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.001023387
Mass	|Single	|2.046774
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
AabbHalfExtentsI	|Single	|0.1109272
AabbHalfExtentsJ	|Single	|0.1148577
AabbHalfExtentsK	|Single	|0.02832308
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|-0.007865876
AabbCenterJ	|Single	|0.0029094
AabbCenterK	|Single	|0.0008331314
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|2
FourVectorsCapacity	|UInt32	|2147483650
Unknown8	|Int32	|8
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|12
PlaneEquationsCapacity	|UInt32	|2147483660
Unknown10	|UInt32	|0


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.1187931
FourVectorsXJ	|Single	|-0.1163578
FourVectorsXK	|Single	|-0.115402
FourVectorsXRadius	|Single	|-0.09764092
FourVectorsYI	|Single	|-0.04118405
FourVectorsYJ	|Single	|0.06561778
FourVectorsYK	|Single	|0.07148695
FourVectorsYRadius	|Single	|-0.03351875
FourVectorsZI	|Single	|0.004231025
FourVectorsZJ	|Single	|0.0008331314
FourVectorsZK	|Single	|0.008432554
FourVectorsZRadius	|Single	|0.02915621


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.08256143
FourVectorsXJ	|Single	|0.08256146
FourVectorsXK	|Single	|0.1030613
FourVectorsXRadius	|Single	|0.1030613
FourVectorsYI	|Single	|0.1177671
FourVectorsYJ	|Single	|-0.1095233
FourVectorsYK	|Single	|0.1177671
FourVectorsYRadius	|Single	|-0.1119483
FourVectorsZI	|Single	|-0.02748995
FourVectorsZJ	|Single	|-0.01933716
FourVectorsZK	|Single	|0.001885112
FourVectorsZRadius	|Single	|0.01889401


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9941368
Unknown2	|Single	|0.02600721
Unknown3	|Single	|0.104956
Unknown4	|Single	|-0.1174696


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.7622743
Unknown2	|Single	|-0.001193654
Unknown3	|Single	|0.6472531
Unknown4	|Single	|-0.09334062


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.3085079
Unknown2	|Single	|-0.9453576
Unknown3	|Single	|0.105461
Unknown4	|Single	|-0.07602847


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2930579
Unknown2	|Single	|-0.8152872
Unknown3	|Single	|0.4994236
Unknown4	|Single	|-0.07050315


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2836431
Unknown2	|Single	|0.7758669
Unknown3	|Single	|-0.5635397
Unknown4	|Single	|-0.08344526


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2011638
Unknown2	|Single	|0.9694458
Unknown3	|Single	|0.140385
Unknown4	|Single	|-0.09370122


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.1335864
Unknown2	|Single	|-0.02847078
Unknown3	|Single	|-0.9906282
Unknown4	|Single	|-0.01285031


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.1280756
Unknown2	|Single	|-0.03555124
Unknown3	|Single	|-0.991127
Unknown4	|Single	|-0.01248516


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.0112161
Unknown2	|Single	|0.1917841
Unknown3	|Single	|0.981373
Unknown4	|Single	|-0.0232799


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.07959391
Unknown2	|Single	|0.07360699
Unknown3	|Single	|0.9941061
Unknown4	|Single	|-0.01874553


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8198808
Unknown2	|Single	|-0.02052324
Unknown3	|Single	|-0.5721663
Unknown4	|Single	|-0.08100239


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8798268
Unknown2	|Single	|-0.03509605
Unknown3	|Single	|-0.4739969
Unknown4	|Single	|-0.08564937


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
Name	|StringId	|flap
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|-1


