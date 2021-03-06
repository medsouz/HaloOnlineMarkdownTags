# [0x3DAC] 0x00003DAC

**Name:** ```0x00003DAC```

**Index:** ```0x3DAC```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|200
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
Pills	|TagBlock (Pills)	|[1](#pills)
Boxes	|TagBlock (Boxes)	|[2](#boxes)
Triangles	|TagBlock (Triangles)	|0
Polyhedra	|TagBlock (Polyhedra)	|0
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|0
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|0
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|[1](#lists)
ListShapes	|TagBlock (ListShapes)	|[3](#listshapes)
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
Node	|Int16	|0
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
BoundingSphereRadius	|Single	|1.054575
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
Mass	|Single	|200
CenterOfMassI	|Single	|-0.04977194
CenterOfMassJ	|Single	|-0.02699512
CenterOfMassK	|Single	|0.1941674
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|6.681559
InertiaTensorXJ	|Single	|-0.01086266
InertiaTensorXK	|Single	|-0.4980145
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|-0.01086266
InertiaTensorYJ	|Single	|8.573546
InertiaTensorYK	|Single	|-0.07043752
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|-0.4980145
InertiaTensorZJ	|Single	|-0.07043752
InertiaTensorZK	|Single	|5.18885
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
MaterialName	|StringId	|hard_metal_thin_hum_object_rattly
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Pills

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phys_model
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|201
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|0.0008105694
Mass	|Single	|3.618223
Index	|Int16	|0
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown3	|Int32	|7
Radius	|Single	|0.02013234
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
BottomI	|Single	|0.04999023
BottomJ	|Single	|-0.01597109
BottomK	|Single	|0.2037194
BottomRadius	|Single	|0.02013234
TopI	|Single	|0.04999023
TopJ	|Single	|-0.01597109
TopK	|Single	|0.8134547
TopRadius	|Single	|0.02013234


### Boxes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phys_model
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|201
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|0.04256185
Mass	|Single	|189.9877
Index	|Int16	|1
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
HalfExtentsI	|Single	|0.2336
HalfExtentsJ	|Single	|0.1436
HalfExtentsK	|Single	|0.1586
HalfExtentsRadius	|Single	|0.1436
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|32
Unknown8	|Int32	|13
Radius2	|Single	|0.0164
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
RotationII	|Single	|1
RotationIJ	|Single	|0
RotationIK	|Single	|0
RotationIRadius	|Single	|0
RotationJI	|Single	|0
RotationJJ	|Single	|0
RotationJK	|Single	|1
RotationJRadius	|Single	|0
RotationKI	|Single	|0
RotationKJ	|Single	|-1
RotationKK	|Single	|0
RotationKRadius	|Single	|0
TranslationI	|Single	|-0.05439209
TranslationJ	|Single	|-0.02761773
TranslationK	|Single	|0.1648168
TranslationRadius	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phys_model10
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|201
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|0.001432424
Mass	|Single	|6.39406
Index	|Int16	|2
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|176
Unknown3	|Int32	|6
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
HalfExtentsI	|Single	|0.0336
HalfExtentsJ	|Single	|0.0336
HalfExtentsK	|Single	|0.1586
HalfExtentsRadius	|Single	|0.0336
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|208
Unknown8	|Int32	|13
Radius2	|Single	|0.0164
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
RotationII	|Single	|1
RotationIJ	|Single	|2.291026E-08
RotationIK	|Single	|2.828457E-10
RotationIRadius	|Single	|0
RotationJI	|Single	|-2.828395E-10
RotationJJ	|Single	|-3.576279E-07
RotationJK	|Single	|1
RotationJRadius	|Single	|0
RotationKI	|Single	|2.291026E-08
RotationKJ	|Single	|-1
RotationKK	|Single	|-3.576279E-07
RotationKRadius	|Single	|0
TranslationI	|Single	|0.03105469
TranslationJ	|Single	|-0.01473356
TranslationK	|Single	|0.8883445
TranslationRadius	|Single	|0


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
ChildShapesSize	|Int32	|3
ChildShapesCapacity	|UInt32	|2147483651
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1048576000
Unknown10	|UInt32	|1043975157
Unknown11	|UInt32	|1055849390
Unknown12	|UInt32	|1057271063
Unknown13	|UInt32	|3177105982
Unknown14	|UInt32	|3165485192
Unknown15	|UInt32	|1056011014
Unknown16	|UInt32	|1056901989


### ListShapes

**0:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|6
Unknown3	|Int32	|3


**1:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|Int32	|3


**2:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|1
Unknown	|UInt32	|0
Unknown2	|UInt32	|3132
Unknown3	|Int32	|3


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|box
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


