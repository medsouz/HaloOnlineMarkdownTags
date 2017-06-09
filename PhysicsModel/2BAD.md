# [0x2BAD] 0x00002BAD

**Name:** ```0x00002BAD```

**Index:** ```0x2BAD```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|1954.593
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
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[6](#polyhedronplaneequations)
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
BoundingSphereRadius	|Single	|1.087607
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
Mass	|Single	|1954.593
CenterOfMassI	|Single	|-3.099997E-10
CenterOfMassJ	|Single	|-7.726758E-09
CenterOfMassK	|Single	|0.4330554
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|157.6301
InertiaTensorXJ	|Single	|6.075638E-08
InertiaTensorXK	|Single	|8.849644E-09
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|6.075638E-08
InertiaTensorYJ	|Single	|212.7187
InertiaTensorYK	|Single	|5.35277E-07
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|8.849644E-09
InertiaTensorZJ	|Single	|5.35277E-07
InertiaTensorZK	|Single	|126.1953
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|default
MaterialName	|StringId	|hard_metal_thick_cov
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|physics_model
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|76
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.3007067
Mass	|Single	|1954.593
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
AabbHalfExtentsI	|Single	|0.4086
AabbHalfExtentsJ	|Single	|0.2336
AabbHalfExtentsK	|Single	|0.4336
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0
AabbCenterJ	|Single	|0
AabbCenterK	|Single	|0.4476606
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|2
FourVectorsCapacity	|UInt32	|2147483650
Unknown8	|Int32	|8
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|6
PlaneEquationsCapacity	|UInt32	|2147483654
Unknown10	|UInt32	|0


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.4086
FourVectorsXJ	|Single	|-0.4086
FourVectorsXK	|Single	|-0.3336
FourVectorsXRadius	|Single	|-0.3336
FourVectorsYI	|Single	|-0.2336
FourVectorsYJ	|Single	|0.2336
FourVectorsYK	|Single	|-0.2336
FourVectorsYRadius	|Single	|0.2336
FourVectorsZI	|Single	|0.01406065
FourVectorsZJ	|Single	|0.01406065
FourVectorsZK	|Single	|0.8812606
FourVectorsZRadius	|Single	|0.8812606


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3336
FourVectorsXJ	|Single	|0.3336
FourVectorsXK	|Single	|0.4086
FourVectorsXRadius	|Single	|0.4086
FourVectorsYI	|Single	|-0.2336
FourVectorsYJ	|Single	|0.2336
FourVectorsYK	|Single	|-0.2336
FourVectorsYRadius	|Single	|0.2336
FourVectorsZI	|Single	|0.8812606
FourVectorsZJ	|Single	|0.8812606
FourVectorsZK	|Single	|0.01406065
FourVectorsZRadius	|Single	|0.01406065


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.996281
Unknown2	|Single	|0
Unknown3	|Single	|0.08616359
Unknown4	|Single	|-0.4082919


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-1
Unknown3	|Single	|0
Unknown4	|Single	|-0.2336


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|-1
Unknown4	|Single	|0.01406065


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|0.9999999
Unknown4	|Single	|-0.8812606


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0.9999999
Unknown3	|Single	|0
Unknown4	|Single	|-0.2336


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.996281
Unknown2	|Single	|0
Unknown3	|Single	|0.08616359
Unknown4	|Single	|-0.4082919


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
Name	|StringId	|node
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|-1


