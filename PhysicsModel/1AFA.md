# [0x1AFA] 0x00001AFA

**Name:** ```0x00001AFA```

**Index:** ```0x1AFA```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|8.212845
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
Polyhedra	|TagBlock (Polyhedra)	|[2](#polyhedra)
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[4](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[12](#polyhedronplaneequations)
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|[1](#lists)
ListShapes	|TagBlock (ListShapes)	|[2](#listshapes)
Mopps	|TagBlock (Mopps)	|0
MoppCodes	|Byte[]	|System.Byte[]
HingeConstraints	|TagBlock (HingeConstraints)	|0
RagdollConstraints	|TagBlock (RagdollConstraints)	|0
Regions	|TagBlock (Regions)	|[1](#regions)
Nodes	|TagBlock (Nodes)	|[2](#nodes)
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
BoundingSphereRadius	|Single	|0.2001453
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
Mass	|Single	|8.212845
CenterOfMassI	|Single	|0.020424
CenterOfMassJ	|Single	|0
CenterOfMassK	|Single	|0.0193313
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0.008051798
InertiaTensorXJ	|Single	|0
InertiaTensorXK	|Single	|0.004473146
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0
InertiaTensorYJ	|Single	|0.06219059
InertiaTensorYK	|Single	|-2.309264E-11
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0.004473146
InertiaTensorZJ	|Single	|-2.309264E-11
InertiaTensorZK	|Single	|0.05702343
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick_for
MaterialName	|StringId	|
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phy_auto_turret
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|86
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.0004248902
Mass	|Single	|2.761786
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
AabbHalfExtentsI	|Single	|0.07633688
AabbHalfExtentsJ	|Single	|0.01177176
AabbHalfExtentsK	|Single	|0.04242369
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|-0.01551939
AabbCenterJ	|Single	|0
AabbCenterK	|Single	|0.04923957
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|2
FourVectorsCapacity	|UInt32	|2147483650
Unknown8	|Int32	|8
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|6
PlaneEquationsCapacity	|UInt32	|2147483654
Unknown10	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phy_auto_turret
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|86
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.0008386244
Mass	|Single	|5.451058
OverallShapeIndex	|Int16	|1
PhantomIndex	|SByte	|-1
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|160
Unknown3	|Int32	|8
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
AabbHalfExtentsI	|Single	|0.1570929
AabbHalfExtentsJ	|Single	|0.02564201
AabbHalfExtentsK	|Single	|0.02602369
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.03863476
AabbCenterJ	|Single	|0
AabbCenterK	|Single	|0.004178233
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
FourVectorsXI	|Single	|-0.09185626
FourVectorsXJ	|Single	|-0.09185626
FourVectorsXK	|Single	|-0.09185626
FourVectorsXRadius	|Single	|-0.09185626
FourVectorsYI	|Single	|-0.01177176
FourVectorsYJ	|Single	|-0.01177176
FourVectorsYK	|Single	|0.01177176
FourVectorsYRadius	|Single	|0.01177176
FourVectorsZI	|Single	|0.006815881
FourVectorsZJ	|Single	|0.09166326
FourVectorsZK	|Single	|0.006815881
FourVectorsZRadius	|Single	|0.09166326


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.06081749
FourVectorsXJ	|Single	|0.06081749
FourVectorsXK	|Single	|0.06081749
FourVectorsXRadius	|Single	|0.06081749
FourVectorsYI	|Single	|-0.01177176
FourVectorsYJ	|Single	|-0.01177176
FourVectorsYK	|Single	|0.01177176
FourVectorsYRadius	|Single	|0.01177176
FourVectorsZI	|Single	|0.006815881
FourVectorsZJ	|Single	|0.09166326
FourVectorsZK	|Single	|0.006815881
FourVectorsZRadius	|Single	|0.09166326


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.1184582
FourVectorsXJ	|Single	|-0.1184582
FourVectorsXK	|Single	|-0.1184582
FourVectorsXRadius	|Single	|-0.1184582
FourVectorsYI	|Single	|-0.02564201
FourVectorsYJ	|Single	|-0.02564201
FourVectorsYK	|Single	|0.02564201
FourVectorsYRadius	|Single	|0.02564201
FourVectorsZI	|Single	|-0.02184546
FourVectorsZJ	|Single	|0.03020192
FourVectorsZK	|Single	|-0.02184546
FourVectorsZRadius	|Single	|0.03020192


**3:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.1957277
FourVectorsXJ	|Single	|0.1957277
FourVectorsXK	|Single	|0.1957277
FourVectorsXRadius	|Single	|0.1957277
FourVectorsYI	|Single	|-0.02564201
FourVectorsYJ	|Single	|-0.02564201
FourVectorsYK	|Single	|0.02564201
FourVectorsYRadius	|Single	|0.02564201
FourVectorsZI	|Single	|-0.02184546
FourVectorsZJ	|Single	|0.03020192
FourVectorsZK	|Single	|-0.02184546
FourVectorsZRadius	|Single	|0.03020192


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1
Unknown2	|Single	|0
Unknown3	|Single	|0
Unknown4	|Single	|-0.09185626


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-1
Unknown3	|Single	|0
Unknown4	|Single	|-0.01177176


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|-1
Unknown4	|Single	|0.006815881


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|1
Unknown4	|Single	|-0.09166326


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|1
Unknown3	|Single	|0
Unknown4	|Single	|-0.01177176


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|1
Unknown2	|Single	|0
Unknown3	|Single	|0
Unknown4	|Single	|-0.06081749


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1
Unknown2	|Single	|0
Unknown3	|Single	|0
Unknown4	|Single	|-0.1184582


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-1
Unknown3	|Single	|0
Unknown4	|Single	|-0.02564201


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|-1
Unknown4	|Single	|-0.02184546


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|0
Unknown3	|Single	|1
Unknown4	|Single	|-0.03020192


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|1
Unknown3	|Single	|0
Unknown4	|Single	|-0.02564201


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9999999
Unknown2	|Single	|0
Unknown3	|Single	|0
Unknown4	|Single	|-0.1957277


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
Unknown9	|UInt32	|1043441696
Unknown10	|UInt32	|1026307133
Unknown11	|UInt32	|1033228788
Unknown12	|UInt32	|1015437643
Unknown13	|UInt32	|1025392508
Unknown14	|UInt32	|0
Unknown15	|UInt32	|1024392356
Unknown16	|UInt32	|0


### ListShapes

**0:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|Int32	|2


**1:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|1
Unknown	|UInt32	|0
Unknown2	|UInt32	|1229360
Unknown3	|Int32	|2


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
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
Name	|StringId	|turret
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gun
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|-1
Child	|Int16	|-1


