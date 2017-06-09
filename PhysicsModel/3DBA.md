# [0x3DBA] 0x00003DBA

**Name:** ```0x00003DBA```

**Index:** ```0x3DBA```

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
PhantomTypes	|TagBlock (PhantomTypes)	|[4](#phantomtypes)
PoweredChains	|TagBlock (PoweredChains)	|0
NodeEdges	|TagBlock (NodeEdges)	|0
RigidBodies	|TagBlock (RigidBodies)	|[1](#rigidbodies)
Materials	|TagBlock (Materials)	|[4](#materials)
Spheres	|TagBlock (Spheres)	|0
MultiSpheres	|TagBlock (MultiSpheres)	|0
Pills	|TagBlock (Pills)	|0
Boxes	|TagBlock (Boxes)	|0
Triangles	|TagBlock (Triangles)	|0
Polyhedra	|TagBlock (Polyhedra)	|[4](#polyhedra)
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[31](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[103](#polyhedronplaneequations)
MassDistributions	|TagBlock (MassDistributions)	|0
Lists	|TagBlock (Lists)	|[1](#lists)
ListShapes	|TagBlock (ListShapes)	|[4](#listshapes)
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
Phantoms	|TagBlock (Phantoms)	|[4](#phantoms)


## Tag Blocks

### PhantomTypes

**0:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhantomTypeFlags)	|null
MinimumSize	|Enum (SizeValue)	|null
MaximumSize	|Enum (SizeValue)	|null
MarkerName	|StringId	|
AlignmentMarkerName	|StringId	|
HookesLawE	|Single	|0
LinearDeadRadius	|Single	|0
CenterAcceleration	|Single	|0
CenterMaxLevel	|Single	|0
AxisAcceleration	|Single	|0
AxisMaxVelocity	|Single	|0
DirectionAcceleration	|Single	|0
DirectionMaxVelocity	|Single	|0
AlignmentHookesLawE	|Single	|0
AlignmentAcceleration	|Single	|0
AlignmentMaxVelocity	|Single	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhantomTypeFlags)	|null
MinimumSize	|Enum (SizeValue)	|null
MaximumSize	|Enum (SizeValue)	|null
MarkerName	|StringId	|
AlignmentMarkerName	|StringId	|
HookesLawE	|Single	|0
LinearDeadRadius	|Single	|0
CenterAcceleration	|Single	|0
CenterMaxLevel	|Single	|0
AxisAcceleration	|Single	|0
AxisMaxVelocity	|Single	|0
DirectionAcceleration	|Single	|25
DirectionMaxVelocity	|Single	|25
AlignmentHookesLawE	|Single	|0
AlignmentAcceleration	|Single	|0
AlignmentMaxVelocity	|Single	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhantomTypeFlags)	|null
MinimumSize	|Enum (SizeValue)	|null
MaximumSize	|Enum (SizeValue)	|null
MarkerName	|StringId	|foreground_74
AlignmentMarkerName	|StringId	|
HookesLawE	|Single	|0
LinearDeadRadius	|Single	|0
CenterAcceleration	|Single	|0
CenterMaxLevel	|Single	|0
AxisAcceleration	|Single	|0
AxisMaxVelocity	|Single	|0
DirectionAcceleration	|Single	|0
DirectionMaxVelocity	|Single	|25
AlignmentHookesLawE	|Single	|0
AlignmentAcceleration	|Single	|0
AlignmentMaxVelocity	|Single	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (PhantomTypeFlags)	|null
MinimumSize	|Enum (SizeValue)	|null
MaximumSize	|Enum (SizeValue)	|null
MarkerName	|StringId	|
AlignmentMarkerName	|StringId	|map_default
HookesLawE	|Single	|3.926018E-41
LinearDeadRadius	|Single	|0
CenterAcceleration	|Single	|0
CenterMaxLevel	|Single	|0
AxisAcceleration	|Single	|0
AxisMaxVelocity	|Single	|0
DirectionAcceleration	|Single	|0
DirectionMaxVelocity	|Single	|0
AlignmentHookesLawE	|Single	|0
AlignmentAcceleration	|Single	|0
AlignmentMaxVelocity	|Single	|0


### RigidBodies

**0:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|0
Region	|Int16	|0
Permutations	|Int16	|0
Unknown	|Int16	|0
BoundingSphereOffset	|RealPoint3d	|{ X: 0, Y: 0, Z: 0 }
BoundingSphereRadius	|Single	|9.47675
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
Mass	|Single	|0
CenterOfMassI	|Single	|0
CenterOfMassJ	|Single	|0
CenterOfMassK	|Single	|0
CenterOfMassRadius	|Single	|0
InertiaTensorXI	|Single	|0
InertiaTensorXJ	|Single	|0
InertiaTensorXK	|Single	|0
InertiaTensorXRadius	|Single	|0
InertiaTensorYI	|Single	|0
InertiaTensorYJ	|Single	|0
InertiaTensorYK	|Single	|0
InertiaTensorYRadius	|Single	|0
InertiaTensorZI	|Single	|0
InertiaTensorZJ	|Single	|0
InertiaTensorZK	|Single	|0
InertiaTensorZRadius	|Single	|0
BoundingSpherePad	|Single	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|65536


### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phantom0
MaterialName	|StringId	|energy
PhantomType	|Int16	|0
Flags	|Enum (MaterialFlags)	|null


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phantom1
MaterialName	|StringId	|energy
PhantomType	|Int16	|1
Flags	|Enum (MaterialFlags)	|null


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phantom2
MaterialName	|StringId	|energy
PhantomType	|Int16	|2
Flags	|Enum (MaterialFlags)	|null


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phantom3
MaterialName	|StringId	|energy
PhantomType	|Int16	|3
Flags	|Enum (MaterialFlags)	|null


### Polyhedra

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|launch_volume01
MaterialIndex	|SByte	|0
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|144
RelativeMassScale	|Single	|1
Friction	|Single	|0.2
Restitution	|Single	|0.7
Volume	|Single	|16.0497
Mass	|Single	|16.0497
OverallShapeIndex	|Int16	|0
PhantomIndex	|SByte	|0
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
AabbHalfExtentsI	|Single	|0.98441
AabbHalfExtentsJ	|Single	|2.34082
AabbHalfExtentsK	|Single	|2.24159
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.00208366
AabbCenterJ	|Single	|-1.54112
AabbCenterK	|Single	|1.69251
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|7
FourVectorsCapacity	|UInt32	|2147483655
Unknown8	|Int32	|28
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|31
PlaneEquationsCapacity	|UInt32	|2147483679
Unknown10	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|launch_volume02
MaterialIndex	|SByte	|1
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|144
RelativeMassScale	|Single	|1
Friction	|Single	|0.2
Restitution	|Single	|0.7
Volume	|Single	|31.22403
Mass	|Single	|31.22403
OverallShapeIndex	|Int16	|1
PhantomIndex	|SByte	|1
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
AabbHalfExtentsI	|Single	|0.9844095
AabbHalfExtentsJ	|Single	|4.574812
AabbHalfExtentsK	|Single	|3.28303
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.00208354
AabbCenterJ	|Single	|2.581937
AabbCenterK	|Single	|2.733945
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|8
FourVectorsCapacity	|UInt32	|2147483656
Unknown8	|Int32	|32
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|18
PlaneEquationsCapacity	|UInt32	|2147483666
Unknown10	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|launch_volume03
MaterialIndex	|SByte	|2
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|144
RelativeMassScale	|Single	|1
Friction	|Single	|0.2
Restitution	|Single	|0.7
Volume	|Single	|30.97067
Mass	|Single	|30.97067
OverallShapeIndex	|Int16	|2
PhantomIndex	|SByte	|2
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|288
Unknown3	|Int32	|8
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
AabbHalfExtentsI	|Single	|0.9844095
AabbHalfExtentsJ	|Single	|4.542274
AabbHalfExtentsK	|Single	|3.264244
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.00208354
AabbCenterJ	|Single	|2.549399
AabbCenterK	|Single	|2.715159
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|8
FourVectorsCapacity	|UInt32	|2147483656
Unknown8	|Int32	|32
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|18
PlaneEquationsCapacity	|UInt32	|2147483666
Unknown10	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|launch_volume04
MaterialIndex	|SByte	|3
Unknown	|SByte	|0
GlobalMaterialIndex	|Int16	|144
RelativeMassScale	|Single	|1
Friction	|Single	|0.2
Restitution	|Single	|0.7
Volume	|Single	|12.60894
Mass	|Single	|12.60894
OverallShapeIndex	|Int16	|3
PhantomIndex	|SByte	|3
InteractionUnknown	|SByte	|-1
Unknown2	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|416
Unknown3	|Int32	|8
Radius	|Single	|0.0164
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
AabbHalfExtentsI	|Single	|0.9844095
AabbHalfExtentsJ	|Single	|1.867807
AabbHalfExtentsK	|Single	|1.981163
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.002083361
AabbCenterJ	|Single	|-0.5771727
AabbCenterK	|Single	|1.432077
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|8
FourVectorsCapacity	|UInt32	|2147483656
Unknown8	|Int32	|32
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|36
PlaneEquationsCapacity	|UInt32	|2147483684
Unknown10	|UInt32	|0


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.982326
FourVectorsXJ	|Single	|-0.982326
FourVectorsXK	|Single	|-0.906144
FourVectorsXRadius	|Single	|-0.9061438
FourVectorsYI	|Single	|-1.46389
FourVectorsYJ	|Single	|0.237913
FourVectorsYK	|Single	|-1.24891
FourVectorsYRadius	|Single	|0.4528986
FourVectorsZI	|Single	|0.423952
FourVectorsZJ	|Single	|1.40649
FourVectorsZK	|Single	|0.0515869
FourVectorsZRadius	|Single	|1.034125


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061437
FourVectorsXJ	|Single	|-0.9061436
FourVectorsXK	|Single	|-0.9061432
FourVectorsXRadius	|Single	|-0.6891958
FourVectorsYI	|Single	|-1.646077
FourVectorsYJ	|Single	|-2.618679
FourVectorsYK	|Single	|0.02292752
FourVectorsYRadius	|Single	|-1.066651
FourVectorsZI	|Single	|0.7963172
FourVectorsZJ	|Single	|0.2187676
FourVectorsZK	|Single	|1.746055
FourVectorsZRadius	|Single	|-0.2640893


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891954
FourVectorsXJ	|Single	|-0.3645099
FourVectorsXK	|Single	|-0.3645095
FourVectorsXRadius	|Single	|-0.3645093
FourVectorsYI	|Single	|0.6351542
FourVectorsYJ	|Single	|-0.9448708
FourVectorsYK	|Single	|0.7569332
FourVectorsYRadius	|Single	|-1.240338
FourVectorsZI	|Single	|0.7184481
FourVectorsZJ	|Single	|-0.4750175
FourVectorsZK	|Single	|0.5075203
FourVectorsZRadius	|Single	|3.934095


**3:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.364509
FourVectorsXJ	|Single	|0.002083659
FourVectorsXK	|Single	|0.002083659
FourVectorsXRadius	|Single	|0.3686762
FourVectorsYI	|Single	|-3.881944
FourVectorsYJ	|Single	|-0.9021077
FourVectorsYK	|Single	|0.7996969
FourVectorsYRadius	|Single	|-0.9448708
FourVectorsZI	|Single	|2.374009
FourVectorsZJ	|Single	|-0.5490851
FourVectorsZK	|Single	|0.4334522
FourVectorsZRadius	|Single	|-0.4750175


**4:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686768
FourVectorsXJ	|Single	|0.3686769
FourVectorsXK	|Single	|0.3686771
FourVectorsXRadius	|Single	|0.693362
FourVectorsYI	|Single	|0.7569332
FourVectorsYJ	|Single	|-1.240338
FourVectorsYK	|Single	|-3.881944
FourVectorsYRadius	|Single	|-1.06665
FourVectorsZI	|Single	|0.5075203
FourVectorsZJ	|Single	|3.934095
FourVectorsZK	|Single	|2.374008
FourVectorsZRadius	|Single	|-0.2640902


**5:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933625
FourVectorsXJ	|Single	|0.9103105
FourVectorsXK	|Single	|0.9103105
FourVectorsXRadius	|Single	|0.9103106
FourVectorsYI	|Single	|0.6351547
FourVectorsYJ	|Single	|-1.646076
FourVectorsYK	|Single	|-1.248906
FourVectorsYRadius	|Single	|-2.618678
FourVectorsZI	|Single	|0.7184477
FourVectorsZJ	|Single	|0.7963172
FourVectorsZK	|Single	|0.05158639
FourVectorsZRadius	|Single	|0.2187676


**6:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103107
FourVectorsXJ	|Single	|0.910311
FourVectorsXK	|Single	|0.9864928
FourVectorsXRadius	|Single	|0.9864932
FourVectorsYI	|Single	|0.4528984
FourVectorsYJ	|Single	|0.02292812
FourVectorsYK	|Single	|-1.463891
FourVectorsYRadius	|Single	|0.237913
FourVectorsZI	|Single	|1.034124
FourVectorsZJ	|Single	|1.746054
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|1.40649


**7:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9823259
FourVectorsXJ	|Single	|-0.9823259
FourVectorsXK	|Single	|-0.906144
FourVectorsXRadius	|Single	|-0.906144
FourVectorsYI	|Single	|-1.431092
FourVectorsYJ	|Single	|6.594965
FourVectorsYK	|Single	|6.809951
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|0.4239523
FourVectorsZJ	|Single	|5.043937
FourVectorsZK	|Single	|4.671572
FourVectorsZRadius	|Single	|0.05158687


**8:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061437
FourVectorsXJ	|Single	|-0.9061435
FourVectorsXK	|Single	|-0.6891958
FourVectorsXRadius	|Single	|-0.6891956
FourVectorsYI	|Single	|-1.646077
FourVectorsYJ	|Single	|6.379979
FourVectorsYK	|Single	|-1.033851
FourVectorsYRadius	|Single	|6.992208
FourVectorsZI	|Single	|0.7963172
FourVectorsZJ	|Single	|5.416303
FourVectorsZK	|Single	|-0.2640893
FourVectorsZRadius	|Single	|4.355896


**9:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891955
FourVectorsXJ	|Single	|-0.6891953
FourVectorsXK	|Single	|-0.3645099
FourVectorsXRadius	|Single	|-0.3645097
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.197724
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.113986
FourVectorsZI	|Single	|1.111994
FourVectorsZJ	|Single	|5.731978
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.144968


**10:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.3645095
FourVectorsXJ	|Single	|-0.3645092
FourVectorsXK	|Single	|0.00208354
FourVectorsXRadius	|Single	|0.00208354
FourVectorsYI	|Single	|-1.950113
FourVectorsYJ	|Single	|6.075945
FourVectorsYK	|Single	|-1.992875
FourVectorsYRadius	|Single	|-0.8693075
FourVectorsZI	|Single	|1.322922
FourVectorsZJ	|Single	|5.942907
FourVectorsZK	|Single	|1.39699
FourVectorsZRadius	|Single	|-0.5490851


**11:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.00208354
FourVectorsXJ	|Single	|0.00208354
FourVectorsXK	|Single	|0.3686762
FourVectorsXRadius	|Single	|0.3686765
FourVectorsYI	|Single	|6.033181
FourVectorsYJ	|Single	|7.15675
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.113986
FourVectorsZI	|Single	|6.016974
FourVectorsZJ	|Single	|4.070899
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.144968


**12:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686767
FourVectorsXJ	|Single	|0.3686769
FourVectorsXK	|Single	|0.693362
FourVectorsXRadius	|Single	|0.6933622
FourVectorsYI	|Single	|-1.950112
FourVectorsYJ	|Single	|6.075944
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|6.992208
FourVectorsZI	|Single	|1.322921
FourVectorsZJ	|Single	|5.942906
FourVectorsZK	|Single	|-0.2640901
FourVectorsZRadius	|Single	|4.355895


**13:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933625
FourVectorsXJ	|Single	|0.6933627
FourVectorsXK	|Single	|0.9103105
FourVectorsXRadius	|Single	|0.9103105
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.197724
FourVectorsYK	|Single	|-1.646076
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.111993
FourVectorsZJ	|Single	|5.731978
FourVectorsZK	|Single	|0.7963173
FourVectorsZRadius	|Single	|0.05158639


**14:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103105
FourVectorsXJ	|Single	|0.9103108
FourVectorsXK	|Single	|0.9864928
FourVectorsXRadius	|Single	|0.986493
FourVectorsYI	|Single	|6.809951
FourVectorsYJ	|Single	|6.37998
FourVectorsYK	|Single	|-1.431092
FourVectorsYRadius	|Single	|6.594965
FourVectorsZI	|Single	|4.671572
FourVectorsZJ	|Single	|5.416302
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|5.043937


**15:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9823259
FourVectorsXJ	|Single	|-0.9823259
FourVectorsXK	|Single	|-0.906144
FourVectorsXRadius	|Single	|-0.906144
FourVectorsYI	|Single	|-1.431092
FourVectorsYJ	|Single	|6.52989
FourVectorsYK	|Single	|6.744876
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|0.4239523
FourVectorsZJ	|Single	|5.006366
FourVectorsZK	|Single	|4.634001
FourVectorsZRadius	|Single	|0.05158687


**16:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061437
FourVectorsXJ	|Single	|-0.9061435
FourVectorsXK	|Single	|-0.6891958
FourVectorsXRadius	|Single	|-0.6891956
FourVectorsYI	|Single	|-1.646077
FourVectorsYJ	|Single	|6.314904
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|6.927133
FourVectorsZI	|Single	|0.7963172
FourVectorsZJ	|Single	|5.378732
FourVectorsZK	|Single	|-0.2640893
FourVectorsZRadius	|Single	|4.318325


**17:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891955
FourVectorsXJ	|Single	|-0.6891953
FourVectorsXK	|Single	|-0.3645099
FourVectorsXRadius	|Single	|-0.3645098
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.132649
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.04891
FourVectorsZI	|Single	|1.111994
FourVectorsZJ	|Single	|5.694407
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.107397


**18:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.3645095
FourVectorsXJ	|Single	|-0.3645093
FourVectorsXK	|Single	|0.00208354
FourVectorsXRadius	|Single	|0.00208354
FourVectorsYI	|Single	|-1.950112
FourVectorsYJ	|Single	|6.01087
FourVectorsYK	|Single	|-1.992875
FourVectorsYRadius	|Single	|-0.8693078
FourVectorsZI	|Single	|1.322922
FourVectorsZJ	|Single	|5.905336
FourVectorsZK	|Single	|1.39699
FourVectorsZRadius	|Single	|-0.5490851


**19:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.00208354
FourVectorsXJ	|Single	|0.00208354
FourVectorsXK	|Single	|0.3686762
FourVectorsXRadius	|Single	|0.3686765
FourVectorsYI	|Single	|5.968106
FourVectorsYJ	|Single	|7.091674
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.04891
FourVectorsZI	|Single	|5.979403
FourVectorsZJ	|Single	|4.033329
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.107397


**20:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686767
FourVectorsXJ	|Single	|0.3686769
FourVectorsXK	|Single	|0.693362
FourVectorsXRadius	|Single	|0.6933622
FourVectorsYI	|Single	|-1.950112
FourVectorsYJ	|Single	|6.010869
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|6.927133
FourVectorsZI	|Single	|1.322921
FourVectorsZJ	|Single	|5.905335
FourVectorsZK	|Single	|-0.2640901
FourVectorsZRadius	|Single	|4.318324


**21:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933625
FourVectorsXJ	|Single	|0.6933627
FourVectorsXK	|Single	|0.9103105
FourVectorsXRadius	|Single	|0.9103105
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.132649
FourVectorsYK	|Single	|-1.646077
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.111993
FourVectorsZJ	|Single	|5.694407
FourVectorsZK	|Single	|0.7963173
FourVectorsZRadius	|Single	|0.05158639


**22:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103105
FourVectorsXJ	|Single	|0.9103108
FourVectorsXK	|Single	|0.9864928
FourVectorsXRadius	|Single	|0.986493
FourVectorsYI	|Single	|6.744875
FourVectorsYJ	|Single	|6.314905
FourVectorsYK	|Single	|-1.431091
FourVectorsYRadius	|Single	|6.52989
FourVectorsZI	|Single	|4.634
FourVectorsZJ	|Single	|5.378731
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|5.006366


**23:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9823261
FourVectorsXJ	|Single	|-0.9823259
FourVectorsXK	|Single	|-0.9061443
FourVectorsXRadius	|Single	|-0.906144
FourVectorsYI	|Single	|0.7288506
FourVectorsYJ	|Single	|-1.431092
FourVectorsYK	|Single	|0.9438365
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.657133
FourVectorsZJ	|Single	|0.4239522
FourVectorsZK	|Single	|1.317569
FourVectorsZRadius	|Single	|0.05158675


**24:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061437
FourVectorsXJ	|Single	|-0.9061436
FourVectorsXK	|Single	|-0.6891959
FourVectorsXRadius	|Single	|-0.6891958
FourVectorsYI	|Single	|0.06175971
FourVectorsYJ	|Single	|-2.098182
FourVectorsYK	|Single	|1.126093
FourVectorsYRadius	|Single	|-1.033851
FourVectorsZI	|Single	|2.812568
FourVectorsZJ	|Single	|1.546586
FourVectorsZK	|Single	|1.001892
FourVectorsZRadius	|Single	|-0.2640895


**25:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891956
FourVectorsXJ	|Single	|-0.6891955
FourVectorsXK	|Single	|-0.3645099
FourVectorsXRadius	|Single	|-0.3645099
FourVectorsYI	|Single	|-0.1204948
FourVectorsYJ	|Single	|-2.280437
FourVectorsYK	|Single	|-0.9120709
FourVectorsYRadius	|Single	|1.24787
FourVectorsZI	|Single	|3.128244
FourVectorsZJ	|Single	|1.862262
FourVectorsZK	|Single	|-0.4750177
FourVectorsZRadius	|Single	|0.7909642


**26:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.3645094
FourVectorsXJ	|Single	|-0.3645093
FourVectorsXK	|Single	|0.002083361
FourVectorsXRadius	|Single	|0.002083361
FourVectorsYI	|Single	|-2.402217
FourVectorsYJ	|Single	|-0.2422741
FourVectorsYK	|Single	|-2.44498
FourVectorsYRadius	|Single	|-0.8693078
FourVectorsZI	|Single	|2.073191
FourVectorsZJ	|Single	|3.339172
FourVectorsZK	|Single	|2.147258
FourVectorsZRadius	|Single	|-0.5490854


**27:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.002083361
FourVectorsXJ	|Single	|0.002083361
FourVectorsXK	|Single	|0.3686762
FourVectorsXRadius	|Single	|0.3686763
FourVectorsYI	|Single	|-0.2850383
FourVectorsYJ	|Single	|1.290635
FourVectorsYK	|Single	|-0.9120709
FourVectorsYRadius	|Single	|1.24787
FourVectorsZI	|Single	|3.41324
FourVectorsZJ	|Single	|0.7168962
FourVectorsZK	|Single	|-0.4750177
FourVectorsZRadius	|Single	|0.7909642


**28:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686768
FourVectorsXJ	|Single	|0.3686768
FourVectorsXK	|Single	|0.693362
FourVectorsXRadius	|Single	|0.693362
FourVectorsYI	|Single	|-2.402217
FourVectorsYJ	|Single	|-0.2422752
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|1.126093
FourVectorsZI	|Single	|2.07319
FourVectorsZJ	|Single	|3.339172
FourVectorsZK	|Single	|-0.2640902
FourVectorsZRadius	|Single	|1.001892


**29:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933625
FourVectorsXJ	|Single	|0.6933625
FourVectorsXK	|Single	|0.9103103
FourVectorsXRadius	|Single	|0.9103105
FourVectorsYI	|Single	|-2.280437
FourVectorsYJ	|Single	|-0.1204942
FourVectorsYK	|Single	|0.9438353
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.862262
FourVectorsZJ	|Single	|3.128244
FourVectorsZK	|Single	|1.317568
FourVectorsZRadius	|Single	|0.05158627


**30:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103106
FourVectorsXJ	|Single	|0.9103106
FourVectorsXK	|Single	|0.9864928
FourVectorsXRadius	|Single	|0.9864928
FourVectorsYI	|Single	|-2.098181
FourVectorsYJ	|Single	|0.06176102
FourVectorsYK	|Single	|-1.431091
FourVectorsYRadius	|Single	|0.72885
FourVectorsZI	|Single	|1.546586
FourVectorsZJ	|Single	|2.812567
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|1.657134


### PolyhedronPlaneEquations

*Excluded due to >100 entries.*### Lists

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
ChildShapesSize	|Int32	|4
ChildShapesCapacity	|UInt32	|2147483652
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065360011
Unknown10	|UInt32	|1085351122
Unknown11	|UInt32	|1079192029
Unknown12	|UInt32	|1015437643
Unknown13	|UInt32	|990416384
Unknown14	|UInt32	|1070700154
Unknown15	|UInt32	|1076820211
Unknown16	|UInt32	|0


### ListShapes

**0:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown	|UInt32	|0
Unknown2	|UInt32	|3419130827
Unknown3	|Int32	|4


**1:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|1
Unknown	|UInt32	|0
Unknown2	|UInt32	|3419130827
Unknown3	|Int32	|4


**2:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|2
Unknown	|UInt32	|0
Unknown2	|UInt32	|3419130827
Unknown3	|Int32	|4


**3:**

Name	| Type	| Value
---	|---	|---	|
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|3
Unknown	|UInt32	|0
Unknown2	|UInt32	|3419130827
Unknown3	|Int32	|4


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
Name	|StringId	|lift
Flags	|UInt16	|0
Parent	|Int16	|-1
Sibling	|Int16	|-1
Child	|Int16	|-1


### Phantoms

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown2	|Int32	|25
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|0
Unknown6	|Int32	|29


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown2	|Int32	|25
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|1
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|1
Unknown6	|Int32	|29


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown2	|Int32	|25
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|2
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|2
Unknown6	|Int32	|29


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Int32	|0
Size	|Int16	|0
Count	|Int16	|128
Offset	|Int32	|0
Unknown2	|Int32	|25
ShapeType	|Enum (ShapeTypeValue)	|null
ShapeIndex	|Int16	|3
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int32	|0
Size2	|Int16	|0
Count2	|Int16	|128
Offset2	|Int32	|3
Unknown6	|Int32	|29


