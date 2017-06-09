# [0x3CCE] 0x00003CCE

**Name:** ```0x00003CCE```

**Index:** ```0x3CCE```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|453.8857
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
NodeEdges	|TagBlock (NodeEdges)	|[2](#nodeedges)
RigidBodies	|TagBlock (RigidBodies)	|[3](#rigidbodies)
Materials	|TagBlock (Materials)	|[1](#materials)
Spheres	|TagBlock (Spheres)	|0
MultiSpheres	|TagBlock (MultiSpheres)	|0
Pills	|TagBlock (Pills)	|0
Boxes	|TagBlock (Boxes)	|[3](#boxes)
Triangles	|TagBlock (Triangles)	|0
Polyhedra	|TagBlock (Polyhedra)	|0
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|0
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|0
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|0
ListShapes	|TagBlock (ListShapes)	|0
Mopps	|TagBlock (Mopps)	|0
MoppCodes	|Byte[]	|System.Byte[]
HingeConstraints	|TagBlock (HingeConstraints)	|0
RagdollConstraints	|TagBlock (RagdollConstraints)	|0
Regions	|TagBlock (Regions)	|[2](#regions)
Nodes	|TagBlock (Nodes)	|[3](#nodes)
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

### NodeEdges

**0:**

Name	| Type	| Value
---	|---	|---	|
NodeAGlobalMaterialIndex	|Int16	|0
NodeBGlobalMaterialIndex	|Int16	|0
NodeA	|Int16	|1
NodeB	|Int16	|0
Constraints	|TagBlock (NodeEdges_Constraints)	|0
NodeAMaterial	|StringId	|
NodeBMaterial	|StringId	|


**1:**

Name	| Type	| Value
---	|---	|---	|
NodeAGlobalMaterialIndex	|Int16	|0
NodeBGlobalMaterialIndex	|Int16	|0
NodeA	|Int16	|2
NodeB	|Int16	|0
Constraints	|TagBlock (NodeEdges_Constraints)	|0
NodeAMaterial	|StringId	|
NodeBMaterial	|StringId	|


### RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|2
Region	|Int16	|1
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: -0.01794712, Y: 7.629399E-08, Z: 0.2145425 }
BoundingSphereRadius	|Single	|0.3949081
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
Mass	|Single	|379.1015
CenterOfMassI	|Single	|0.03637282
CenterOfMassJ	|Single	|-8.2997E-08
CenterOfMassK	|Single	|0.01278962
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|9.151246
InertiaTensorXJ	|Single	|1.015266E-07
InertiaTensorXK	|Single	|-3.291219E-08
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|1.015266E-07
InertiaTensorYJ	|Single	|13.79145
InertiaTensorYK	|Single	|3.948151E-08
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|-3.291219E-08
InertiaTensorZJ	|Single	|3.948151E-08
InertiaTensorZK	|Single	|9.151246
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|1
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0.00661737, Y: 1.677123E-06, Z: 0.1550844 }
BoundingSphereRadius	|Single	|0.4406157
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
ShapeIndex	|Int16	|1
Mass	|Single	|22.09937
CenterOfMassI	|Single	|0.1199122
CenterOfMassJ	|Single	|-1.676621E-06
CenterOfMassK	|Single	|0.1716741
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0.2303538
InertiaTensorXJ	|Single	|0
InertiaTensorXK	|Single	|-0.1661582
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0
InertiaTensorYJ	|Single	|0.3854783
InertiaTensorYK	|Single	|0
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|-0.1661582
InertiaTensorZJ	|Single	|0
InertiaTensorZK	|Single	|0.1717574
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|0
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0.009698913, Y: 0, Z: 4.999161E-05 }
BoundingSphereRadius	|Single	|0.2911506
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
ShapeIndex	|Int16	|2
Mass	|Single	|52.68482
CenterOfMassI	|Single	|0
CenterOfMassJ	|Single	|0
CenterOfMassK	|Single	|0.05314843
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0.4655246
InertiaTensorXJ	|Single	|0
InertiaTensorXK	|Single	|0
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0
InertiaTensorYJ	|Single	|0.5530341
InertiaTensorYK	|Single	|0
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0
InertiaTensorZJ	|Single	|0
InertiaTensorZK	|Single	|0.9709975
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick_hum
MaterialName	|StringId	|
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Boxes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phy_pod
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|70
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.05832331
Mass	|Single	|379.1015
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
HalfExtentsI	|Single	|0.2336
HalfExtentsJ	|Single	|0.1336
HalfExtentsK	|Single	|0.2336
HalfExtentsRadius	|Single	|0.1336
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|32
Unknown8	|Int32	|13
Radius2	|Single	|0.0164
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
RotationII	|Single	|0.6755901
RotationIJ	|Single	|-8.508573E-09
RotationIK	|Single	|-0.7372774
RotationIRadius	|Single	|0
RotationJI	|Single	|2.187977E-08
RotationJJ	|Single	|1
RotationJK	|Single	|8.508573E-09
RotationJRadius	|Single	|0
RotationKI	|Single	|0.7372774
RotationKJ	|Single	|-2.187977E-08
RotationKK	|Single	|0.6755901
RotationKRadius	|Single	|0
TranslationI	|Single	|0.03637281
TranslationJ	|Single	|-8.2997E-08
TranslationK	|Single	|0.01278962
TranslationRadius	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phy_base
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|70
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.003399903
Mass	|Single	|22.09937
Index	|Int16	|1
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
HalfExtentsI	|Single	|0.0571
HalfExtentsJ	|Single	|0.0336
HalfExtentsK	|Single	|0.221514
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
RotationII	|Single	|0.7660444
RotationIJ	|Single	|0
RotationIK	|Single	|-0.6427876
RotationIRadius	|Single	|0
RotationJI	|Single	|0
RotationJJ	|Single	|1
RotationJK	|Single	|0
RotationJRadius	|Single	|0
RotationKI	|Single	|0.6427876
RotationKJ	|Single	|0
RotationKK	|Single	|0.7660444
RotationKRadius	|Single	|0
TranslationI	|Single	|0.1199122
TranslationJ	|Single	|-1.676621E-06
TranslationK	|Single	|0.1716741
TranslationRadius	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phy_legs
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|70
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.008105357
Mass	|Single	|52.68482
Index	|Int16	|2
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|352
Unknown3	|Int32	|6
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
HalfExtentsI	|Single	|0.1736
HalfExtentsJ	|Single	|0.1586
HalfExtentsK	|Single	|0.03679843
HalfExtentsRadius	|Single	|0.03679843
Unknown7	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|384
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
RotationJJ	|Single	|1
RotationJK	|Single	|0
RotationJRadius	|Single	|0
RotationKI	|Single	|0
RotationKJ	|Single	|0
RotationKK	|Single	|1
RotationKRadius	|Single	|0
TranslationI	|Single	|0
TranslationJ	|Single	|0
TranslationK	|Single	|0.05314843
TranslationRadius	|Single	|0


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
RigidBodies	|TagBlock (Regions_Permutations_RigidBodies)	|[2](#regions_permutations_rigidbodies)


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
RigidBodies	|TagBlock (Regions_Permutations_RigidBodies)	|[1](#regions_permutations_rigidbodies)


### Regions_Permutations_RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
RigidBodyIndex	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
RigidBodyIndex	|Int16	|2


**0:**

Name	| Type	| Value
---	|---	|---	|
RigidBodyIndex	|Int16	|0


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|legs
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hinge_base
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|-1
Child	|Int16	|2


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gun
Flags	|UInt16	|0
Parent	|Int16	|1
Sibling	|Int16	|-1
Child	|Int16	|-1


