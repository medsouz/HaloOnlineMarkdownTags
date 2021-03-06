# 0x4DAC

**Index:** ```0x4DAC```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|94.828
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
NodeEdges	|TagBlock (NodeEdges)	|[1](#nodeedges)
RigidBodies	|TagBlock (RigidBodies)	|[2](#rigidbodies)
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

### NodeEdges

**0:**

Name	| Type	| Value
---	|---	|---	|
NodeAGlobalMaterialIndex	|Int16	|0
NodeBGlobalMaterialIndex	|Int16	|0
NodeA	|Int16	|2
NodeB	|Int16	|1
Constraints	|TagBlock (NodeEdges_Constraints)	|0
NodeAMaterial	|StringId	|
NodeBMaterial	|StringId	|


### RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|1
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0.01360733, Y: 0.0002075195, Z: 0.2388794 }
BoundingSphereRadius	|Single	|1.098629
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
Mass	|Single	|61.10121
CenterOfMassI	|Single	|-0.0008597863
CenterOfMassJ	|Single	|0
CenterOfMassK	|Single	|0.2341865
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|15.21549
InertiaTensorXJ	|Single	|1.281045E-09
InertiaTensorXK	|Single	|-0.01213629
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|1.281045E-09
InertiaTensorYJ	|Single	|1.007179
InertiaTensorYK	|Single	|-9.458746E-08
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|-0.01213629
InertiaTensorZJ	|Single	|-9.458746E-08
InertiaTensorZK	|Single	|14.21024
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|2
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0.6956189, Y: -1.984856, Z: 0.2597797 }
BoundingSphereRadius	|Single	|0.7512222
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
Mass	|Single	|33.72678
CenterOfMassI	|Single	|-2.664262E-05
CenterOfMassJ	|Single	|0.002958413
CenterOfMassK	|Single	|0.2392048
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|2.945992
InertiaTensorXJ	|Single	|-2.241471E-08
InertiaTensorXK	|Single	|0.002530342
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|-2.241471E-08
InertiaTensorYJ	|Single	|0.5559394
InertiaTensorYK	|Single	|-1.182344E-08
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0.002530342
InertiaTensorZJ	|Single	|-1.182344E-08
InertiaTensorZK	|Single	|2.390976
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick
MaterialName	|StringId	|
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|door_large01
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|69
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.009400186
Mass	|Single	|61.10121
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
AabbHalfExtentsI	|Single	|0.009014187
AabbHalfExtentsJ	|Single	|0.8352599
AabbHalfExtentsK	|Single	|0.2225261
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|-0.0008597849
AabbCenterJ	|Single	|0
AabbCenterK	|Single	|0.2341865
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
Name	|StringId	|door_small01
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|69
RelativeMassScale	|Single	|1
Friction	|Single	|0.8
Restitution	|Single	|0.35
Volume	|Single	|0.005188736
Mass	|Single	|33.72678
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
AabbHalfExtentsI	|Single	|0.007342579
AabbHalfExtentsJ	|Single	|0.4611252
AabbHalfExtentsK	|Single	|0.2223798
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|-2.664514E-05
AabbCenterJ	|Single	|0.002958447
AabbCenterK	|Single	|0.2392048
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
FourVectorsXI	|Single	|-0.009873972
FourVectorsXJ	|Single	|-0.009873972
FourVectorsXK	|Single	|-0.004497663
FourVectorsXRadius	|Single	|-0.004497663
FourVectorsYI	|Single	|-0.8352599
FourVectorsYJ	|Single	|0.8352599
FourVectorsYK	|Single	|-0.8352599
FourVectorsYRadius	|Single	|0.8352599
FourVectorsZI	|Single	|0.01217231
FourVectorsZJ	|Single	|0.01217231
FourVectorsZK	|Single	|0.4567125
FourVectorsZRadius	|Single	|0.4567125


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.002778086
FourVectorsXJ	|Single	|0.002778086
FourVectorsXK	|Single	|0.008154402
FourVectorsXRadius	|Single	|0.008154402
FourVectorsYI	|Single	|-0.8352599
FourVectorsYJ	|Single	|0.8352599
FourVectorsYK	|Single	|-0.8352599
FourVectorsYRadius	|Single	|0.8352599
FourVectorsZI	|Single	|0.01166043
FourVectorsZJ	|Single	|0.01166043
FourVectorsZK	|Single	|0.4562007
FourVectorsZRadius	|Single	|0.4562007


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.007369224
FourVectorsXJ	|Single	|-0.007369213
FourVectorsXK	|Single	|-0.005338602
FourVectorsXRadius	|Single	|-0.005338594
FourVectorsYI	|Single	|-0.4581667
FourVectorsYJ	|Single	|0.4640836
FourVectorsYK	|Single	|-0.4581667
FourVectorsYRadius	|Single	|0.4640836
FourVectorsZI	|Single	|0.4613912
FourVectorsZJ	|Single	|0.4613912
FourVectorsZK	|Single	|0.01682498
FourVectorsZRadius	|Single	|0.01682496


**3:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.005285311
FourVectorsXJ	|Single	|0.005285319
FourVectorsXK	|Single	|0.007315926
FourVectorsXRadius	|Single	|0.007315934
FourVectorsYI	|Single	|-0.4581667
FourVectorsYJ	|Single	|0.4640836
FourVectorsYK	|Single	|-0.4581667
FourVectorsYRadius	|Single	|0.4640836
FourVectorsZI	|Single	|0.4615846
FourVectorsZJ	|Single	|0.4615846
FourVectorsZK	|Single	|0.01701838
FourVectorsZRadius	|Single	|0.01701836


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9999269
Unknown2	|Single	|0
Unknown3	|Single	|0.01209321
Unknown4	|Single	|-0.01002045


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.04042554
Unknown2	|Single	|2.265995E-11
Unknown3	|Single	|-0.9991826
Unknown4	|Single	|0.0117632


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-1
Unknown3	|Single	|0
Unknown4	|Single	|-0.8352599


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|1
Unknown3	|Single	|0
Unknown4	|Single	|-0.8352599


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.04042082
Unknown2	|Single	|0
Unknown3	|Single	|0.9991828
Unknown4	|Single	|-0.4561575


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9999269
Unknown2	|Single	|0
Unknown3	|Single	|-0.01209322
Unknown4	|Single	|-0.002636871


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9999896
Unknown2	|Single	|8.004813E-09
Unknown3	|Single	|-0.004567593
Unknown4	|Single	|-0.005261693


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.01528263
Unknown2	|Single	|1.247148E-10
Unknown3	|Single	|0.9998832
Unknown4	|Single	|-0.4614499


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0
Unknown2	|Single	|-1
Unknown3	|Single	|0
Unknown4	|Single	|-0.4581667


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|2.048937E-09
Unknown2	|Single	|1
Unknown3	|Single	|-1.340644E-07
Unknown4	|Single	|-0.4640836


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.01528145
Unknown2	|Single	|-1.627896E-08
Unknown3	|Single	|-0.9998833
Unknown4	|Single	|0.01690459


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9999896
Unknown2	|Single	|-8.078613E-09
Unknown3	|Single	|0.004567584
Unknown4	|Single	|-0.007393587


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
RigidBodies	|TagBlock (Regions_Permutations_RigidBodies)	|[2](#regions_permutations_rigidbodies)


### Regions_Permutations_RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
RigidBodyIndex	|Int16	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
RigidBodyIndex	|Int16	|1


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|shutter_doors
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|door_anim_large
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|2
Child	|Int16	|-1


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|door_anim_small
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|3
Child	|Int16	|-1


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lock_large_anim
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|4
Child	|Int16	|-1


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|lock_small_anim
Flags	|UInt16	|0
Parent	|Int16	|0
Sibling	|Int16	|-1
Child	|Int16	|-1


