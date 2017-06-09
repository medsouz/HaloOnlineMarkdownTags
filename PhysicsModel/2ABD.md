# [0x2ABD] sailpanel)

**Name:** ```sailpanel)```

**Index:** ```0x2ABD```

**Tag Group:** ```PhysicsModel (phmo)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhysicsModelFlags)	|null
Mass	|Single	|2.196231
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
Node	|Int16	|0
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
BoundingSphereRadius	|Single	|0.2255513
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
Mass	|Single	|2.196231
CenterOfMassI	|Single	|-0.001733113
CenterOfMassJ	|Single	|-0.01040894
CenterOfMassK	|Single	|-0.01537831
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0.009498203
InertiaTensorXJ	|Single	|0.004280696
InertiaTensorXK	|Single	|-0.005073358
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0.004280696
InertiaTensorYJ	|Single	|0.01332071
InertiaTensorYK	|Single	|0.003253055
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|-0.005073358
InertiaTensorZJ	|Single	|0.003253055
InertiaTensorZK	|Single	|0.01042692
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick_hum_warthog
MaterialName	|StringId	|hard_metal_thin_hum
PhantomType	|Int16	|-1
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|p_phy_sailpanel
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|55
RelativeMassScale	|Single	|1
Friction	|Single	|0.85
Restitution	|Single	|0.3
Volume	|Single	|0.001464154
Mass	|Single	|2.196231
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
AabbHalfExtentsI	|Single	|0.1335772
AabbHalfExtentsJ	|Single	|0.09980027
AabbHalfExtentsK	|Single	|0.1224948
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|-0.001733109
AabbCenterJ	|Single	|-0.01040893
AabbCenterK	|Single	|-0.0153783
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
FourVectorsXI	|Single	|-0.1353103
FourVectorsXJ	|Single	|-0.1045796
FourVectorsXK	|Single	|-0.08793746
FourVectorsXRadius	|Single	|-0.05720679
FourVectorsYI	|Single	|0.04550342
FourVectorsYJ	|Single	|0.08939134
FourVectorsYK	|Single	|0.0123326
FourVectorsYRadius	|Single	|0.05622052
FourVectorsZI	|Single	|-0.05922139
FourVectorsZJ	|Single	|-0.05922136
FourVectorsZK	|Single	|-0.1378731
FourVectorsZRadius	|Single	|-0.137873


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.05374059
FourVectorsXJ	|Single	|0.08447126
FourVectorsXK	|Single	|0.1011134
FourVectorsXRadius	|Single	|0.1318441
FourVectorsYI	|Single	|-0.07703839
FourVectorsYJ	|Single	|-0.03315048
FourVectorsYK	|Single	|-0.1102092
FourVectorsYRadius	|Single	|-0.06632128
FourVectorsZI	|Single	|0.1071164
FourVectorsZJ	|Single	|0.1071165
FourVectorsZK	|Single	|0.02846476
FourVectorsZRadius	|Single	|0.02846478


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6599526
Unknown2	|Single	|0.4621043
Unknown3	|Single	|-0.5923869
Unknown4	|Single	|-0.1454077


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.5543572
Unknown2	|Single	|-0.8321044
Unknown3	|Single	|0.01703851
Unknown4	|Single	|-0.0361376


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.4867524
Unknown2	|Single	|0.3408273
Unknown3	|Single	|0.8043064
Unknown4	|Single	|-0.03373928


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.4867524
Unknown2	|Single	|-0.3408273
Unknown3	|Single	|-0.8043064
Unknown4	|Single	|-0.06388513


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.5543572
Unknown2	|Single	|0.8321044
Unknown3	|Single	|-0.01703844
Unknown4	|Single	|-0.01741749


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6599526
Unknown2	|Single	|-0.4621044
Unknown3	|Single	|0.5923868
Unknown4	|Single	|-0.1345204


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hull
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
Name	|StringId	|sailpanel
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|-1


