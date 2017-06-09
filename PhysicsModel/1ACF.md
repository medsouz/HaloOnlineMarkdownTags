# [0x1ACF] 0x00001ACF

**Name:** ```0x00001ACF```

**Index:** ```0x1ACF```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|0.1
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
Boxes	|TagBlock (Boxes)	|[1](#boxes)
Triangles	|TagBlock (Triangles)	|0
Polyhedra	|TagBlock (Polyhedra)	|[1](#polyhedra)
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[3](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[12](#polyhedronplaneequations)
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|[1](#lists)
ListShapes	|TagBlock (ListShapes)	|[2](#listshapes)
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
BoundingSphereRadius	|Single	|0.04985474
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
Mass	|Single	|0.1
CenterOfMassI	|Single	|0.000346054
CenterOfMassJ	|Single	|0.0005673375
CenterOfMassK	|Single	|0.01977853
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|2.087492E-05
InertiaTensorXJ	|Single	|-1.390877E-09
InertiaTensorXK	|Single	|-7.641046E-08
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|-1.390877E-09
InertiaTensorYJ	|Single	|2.087578E-05
InertiaTensorYK	|Single	|-5.619239E-08
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|-7.641046E-08
InertiaTensorZJ	|Single	|-5.619239E-08
InertiaTensorZK	|Single	|1.656042E-05
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thin
MaterialName	|StringId	|
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Boxes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|_invincibility
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|54
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|3.528755E-05
Mass	|Single	|0.09181568
Index	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown3	|Int32	|6
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
HalfExtentsI	|Single	|0.0164
HalfExtentsJ	|Single	|0.0164
HalfExtentsK	|Single	|0.0164
HalfExtentsRadius	|Single	|0.0164
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|32
Unknown8	|Int32	|13
Radius2	|Single	|0.0164
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
RotationII	|Single	|0.7071068
RotationIJ	|Single	|0.7071068
RotationIK	|Single	|0
RotationIRadius	|Single	|0
RotationJI	|Single	|-0.7071068
RotationJJ	|Single	|0.7071068
RotationJK	|Single	|0
RotationJRadius	|Single	|0
RotationKI	|Single	|0
RotationKJ	|Single	|0
RotationKK	|Single	|1
RotationKRadius	|Single	|0
TranslationI	|Single	|0.0003871155
TranslationJ	|Single	|0.0005975342
TranslationK	|Single	|0.02143729
TranslationRadius	|Single	|0


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|_invincibility
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|54
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|3.145484E-06
Mass	|Single	|0.008184322
OverallShapeIndex	|Int16	|1
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
AabbHalfExtentsI	|Single	|0.006099999
AabbHalfExtentsJ	|Single	|0.006099999
AabbHalfExtentsK	|Single	|0.0286
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|-0.0001145937
AabbCenterJ	|Single	|0.0002285764
AabbCenterK	|Single	|0.001169737
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|3
FourVectorsCapacity	|UInt32	|2147483651
Unknown8	|Int32	|10
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|12
PlaneEquationsCapacity	|UInt32	|2147483660
Unknown10	|UInt32	|0


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.006214593
FourVectorsXJ	|Single	|-0.006214593
FourVectorsXK	|Single	|-0.0001145937
FourVectorsXRadius	|Single	|-0.0001145937
FourVectorsYI	|Single	|0.0002285764
FourVectorsYJ	|Single	|0.0002285764
FourVectorsYK	|Single	|-0.005871423
FourVectorsYRadius	|Single	|-0.005871423
FourVectorsZI	|Single	|-0.01623026
FourVectorsZJ	|Single	|0.01856974
FourVectorsZK	|Single	|-0.01623026
FourVectorsZRadius	|Single	|0.01856974


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.0001145937
FourVectorsXJ	|Single	|-0.0001145937
FourVectorsXK	|Single	|-0.0001145937
FourVectorsXRadius	|Single	|-0.0001145937
FourVectorsYI	|Single	|0.0002285764
FourVectorsYJ	|Single	|0.0002285764
FourVectorsYK	|Single	|0.006328575
FourVectorsYRadius	|Single	|0.006328575
FourVectorsZI	|Single	|-0.02743026
FourVectorsZJ	|Single	|0.02976974
FourVectorsZK	|Single	|-0.01623026
FourVectorsZRadius	|Single	|0.01856974


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.005985405
FourVectorsXJ	|Single	|0.005985405
FourVectorsXK	|Single	|0.005985405
FourVectorsXRadius	|Single	|0.005985405
FourVectorsYI	|Single	|0.0002285764
FourVectorsYJ	|Single	|0.0002285764
FourVectorsYK	|Single	|0.0002285764
FourVectorsYRadius	|Single	|0.0002285764
FourVectorsZI	|Single	|-0.01623026
FourVectorsZJ	|Single	|0.01856974
FourVectorsZK	|Single	|0.01856974
FourVectorsZRadius	|Single	|0.01856974


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.7071068
Unknown2	|Single	|-0.7071068
Unknown3	|Single	|0
Unknown4	|Single	|-0.004232753


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.7071068
Unknown2	|Single	|0.7071068
Unknown3	|Single	|0
Unknown4	|Single	|-0.004556009


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6598632
Unknown2	|Single	|-0.6598632
Unknown3	|Single	|0.3593898
Unknown4	|Single	|-0.01062373


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6598632
Unknown2	|Single	|0.6598632
Unknown3	|Single	|0.3593898
Unknown4	|Single	|-0.01092539


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6598632
Unknown2	|Single	|-0.6598632
Unknown3	|Single	|-0.3593898
Unknown4	|Single	|-0.009782941


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6598632
Unknown2	|Single	|0.6598632
Unknown3	|Single	|-0.3593898
Unknown4	|Single	|-0.0100846


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6598632
Unknown2	|Single	|0.6598632
Unknown3	|Single	|0.3593898
Unknown4	|Single	|-0.01077415


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6598632
Unknown2	|Single	|-0.6598632
Unknown3	|Single	|-0.3593898
Unknown4	|Single	|-0.009631709


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6598632
Unknown2	|Single	|-0.6598632
Unknown3	|Single	|0.3593898
Unknown4	|Single	|-0.0104725


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6598632
Unknown2	|Single	|0.6598632
Unknown3	|Single	|-0.3593898
Unknown4	|Single	|-0.009933367


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.7071068
Unknown2	|Single	|-0.7071068
Unknown3	|Single	|0
Unknown4	|Single	|-0.004070693


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.7071068
Unknown2	|Single	|0.7071068
Unknown3	|Single	|0
Unknown4	|Single	|-0.004393949


### Lists

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown2	|Int32	|10
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
ChildShapesSize	|Int32	|2
ChildShapesCapacity	|UInt32	|2147483650
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1025649760
Unknown10	|UInt32	|1025649760
Unknown11	|UInt32	|1028183972
Unknown12	|UInt32	|1057239754
Unknown13	|UInt32	|969602560
Unknown14	|UInt32	|974955456
Unknown15	|UInt32	|1001030208
Unknown16	|UInt32	|1056964608


### ListShapes

**0:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|2147483648
Unknown3	|Int32	|2


**1:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|1229448
Unknown3	|Int32	|2


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
Name	|StringId	|invincibility_equipment
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|-1


