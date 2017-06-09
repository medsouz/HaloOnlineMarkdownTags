# [0x3DBD] 0x00003DBD

**Name:** ```0x00003DBD```

**Index:** ```0x3DBD```

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
PolyhedronFourVectors	|TagBlock (PolyhedronFourVectors)	|[28](#polyhedronfourvectors)
PolyhedronPlaneEquations	|TagBlock (PolyhedronPlaneEquations)	|[98](#polyhedronplaneequations)
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
BoundingSphereRadius	|Single	|9.476748
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
Name	|StringId	|phantom3
MaterialName	|StringId	|energy
PhantomType	|Int16	|3
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
Name	|StringId	|phantom0
MaterialName	|StringId	|energy
PhantomType	|Int16	|0
Flags	|Enum (MaterialFlags)	|null


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|phantom2
MaterialName	|StringId	|energy
PhantomType	|Int16	|2
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
Volume	|Single	|9.42631
Mass	|Single	|9.42631
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
AabbHalfExtentsI	|Single	|0.9844093
AabbHalfExtentsJ	|Single	|1.699352
AabbHalfExtentsK	|Single	|1.689389
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.002083302
AabbCenterJ	|Single	|-0.4087171
AabbCenterK	|Single	|1.140304
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|8
FourVectorsCapacity	|UInt32	|2147483656
Unknown8	|Int32	|32
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|42
PlaneEquationsCapacity	|UInt32	|2147483690
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
AabbCenterI	|Single	|0.002083421
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
Volume	|Single	|4.199681
Mass	|Single	|4.199681
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
AabbHalfExtentsI	|Single	|0.9082274
AabbHalfExtentsJ	|Single	|0.9159945
AabbHalfExtentsK	|Single	|1.075056
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.002083659
AabbCenterJ	|Single	|-1.309965
AabbCenterK	|Single	|1.499007
AabbCenterRadius	|Single	|0
Unknown7	|UInt32	|0
FourVectorsSize	|Int32	|4
FourVectorsCapacity	|UInt32	|2147483652
Unknown8	|Int32	|16
Unknown9	|UInt32	|0
PlaneEquationsSize	|Int32	|20
PlaneEquationsCapacity	|UInt32	|2147483668
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
Volume	|Single	|30.97067
Mass	|Single	|30.97067
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
AabbHalfExtentsJ	|Single	|4.542274
AabbHalfExtentsK	|Single	|3.264244
AabbHalfExtentsRadius	|Single	|0
AabbCenterI	|Single	|0.002083421
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


### PolyhedronFourVectors

**0:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.982326
FourVectorsXJ	|Single	|-0.9823259
FourVectorsXK	|Single	|-0.9061443
FourVectorsXRadius	|Single	|-0.906144
FourVectorsYI	|Single	|0.7288506
FourVectorsYJ	|Single	|-1.431092
FourVectorsYK	|Single	|0.9438365
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.657133
FourVectorsZJ	|Single	|0.4239522
FourVectorsZK	|Single	|1.284769
FourVectorsZRadius	|Single	|0.05158675


**1:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061438
FourVectorsXJ	|Single	|-0.9061437
FourVectorsXK	|Single	|-0.6891959
FourVectorsXRadius	|Single	|-0.6891959
FourVectorsYI	|Single	|0.3986706
FourVectorsYJ	|Single	|-1.761271
FourVectorsYK	|Single	|-1.033851
FourVectorsYRadius	|Single	|1.126093
FourVectorsZI	|Single	|2.229022
FourVectorsZJ	|Single	|0.9958391
FourVectorsZK	|Single	|-0.2640895
FourVectorsZRadius	|Single	|1.001892


**2:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891956
FourVectorsXJ	|Single	|-0.6891955
FourVectorsXK	|Single	|-0.36451
FourVectorsXRadius	|Single	|-0.36451
FourVectorsYI	|Single	|0.2164161
FourVectorsYJ	|Single	|-1.943527
FourVectorsYK	|Single	|-0.9120709
FourVectorsYRadius	|Single	|1.24787
FourVectorsZI	|Single	|2.544697
FourVectorsZJ	|Single	|1.278716
FourVectorsZK	|Single	|-0.4750177
FourVectorsZRadius	|Single	|0.7909642


**3:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.3645095
FourVectorsXJ	|Single	|-0.3645094
FourVectorsXK	|Single	|0.002083272
FourVectorsXRadius	|Single	|0.002083272
FourVectorsYI	|Single	|-2.065307
FourVectorsYJ	|Single	|0.0946368
FourVectorsYK	|Single	|-2.108069
FourVectorsYRadius	|Single	|-0.8693078
FourVectorsZI	|Single	|1.489644
FourVectorsZJ	|Single	|2.755626
FourVectorsZK	|Single	|1.563712
FourVectorsZRadius	|Single	|-0.5490854


**4:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.002083272
FourVectorsXJ	|Single	|0.002083272
FourVectorsXK	|Single	|0.3686762
FourVectorsXRadius	|Single	|0.3686762
FourVectorsYI	|Single	|0.05187255
FourVectorsYJ	|Single	|1.290635
FourVectorsYK	|Single	|-0.9120709
FourVectorsYRadius	|Single	|1.24787
FourVectorsZI	|Single	|2.829693
FourVectorsZJ	|Single	|0.7168962
FourVectorsZK	|Single	|-0.4750177
FourVectorsZRadius	|Single	|0.7909642


**5:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686766
FourVectorsXJ	|Single	|0.3686767
FourVectorsXK	|Single	|0.693362
FourVectorsXRadius	|Single	|0.693362
FourVectorsYI	|Single	|-2.065306
FourVectorsYJ	|Single	|0.09463561
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|1.126093
FourVectorsZI	|Single	|1.489643
FourVectorsZJ	|Single	|2.755625
FourVectorsZK	|Single	|-0.2640902
FourVectorsZRadius	|Single	|1.001892


**6:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933625
FourVectorsXJ	|Single	|0.6933625
FourVectorsXK	|Single	|0.9103103
FourVectorsXRadius	|Single	|0.9103105
FourVectorsYI	|Single	|-1.943526
FourVectorsYJ	|Single	|0.2164166
FourVectorsYK	|Single	|0.9438353
FourVectorsYRadius	|Single	|-1.761271
FourVectorsZI	|Single	|1.278715
FourVectorsZJ	|Single	|2.544698
FourVectorsZK	|Single	|1.284768
FourVectorsZRadius	|Single	|0.9958391


**7:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103105
FourVectorsXJ	|Single	|0.9103105
FourVectorsXK	|Single	|0.9864926
FourVectorsXRadius	|Single	|0.9864926
FourVectorsYI	|Single	|-1.216106
FourVectorsYJ	|Single	|0.3986719
FourVectorsYK	|Single	|-1.431091
FourVectorsYRadius	|Single	|0.72885
FourVectorsZI	|Single	|0.05158627
FourVectorsZJ	|Single	|2.229021
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|1.657134


**8:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.982326
FourVectorsXJ	|Single	|-0.9823259
FourVectorsXK	|Single	|-0.9061441
FourVectorsXRadius	|Single	|-0.906144
FourVectorsYI	|Single	|-1.431092
FourVectorsYJ	|Single	|6.594965
FourVectorsYK	|Single	|6.809951
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|0.4239523
FourVectorsZJ	|Single	|5.043937
FourVectorsZK	|Single	|4.671572
FourVectorsZRadius	|Single	|0.05158687


**9:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061438
FourVectorsXJ	|Single	|-0.9061435
FourVectorsXK	|Single	|-0.6891959
FourVectorsXRadius	|Single	|-0.6891958
FourVectorsYI	|Single	|-1.646077
FourVectorsYJ	|Single	|6.379979
FourVectorsYK	|Single	|-1.033851
FourVectorsYRadius	|Single	|6.992208
FourVectorsZI	|Single	|0.7963172
FourVectorsZJ	|Single	|5.416303
FourVectorsZK	|Single	|-0.2640893
FourVectorsZRadius	|Single	|4.355896


**10:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891956
FourVectorsXJ	|Single	|-0.6891954
FourVectorsXK	|Single	|-0.36451
FourVectorsXRadius	|Single	|-0.3645098
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.197724
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.113986
FourVectorsZI	|Single	|1.111994
FourVectorsZJ	|Single	|5.731978
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.144968


**11:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.3645096
FourVectorsXJ	|Single	|-0.3645093
FourVectorsXK	|Single	|0.002083451
FourVectorsXRadius	|Single	|0.002083451
FourVectorsYI	|Single	|-1.950113
FourVectorsYJ	|Single	|6.075945
FourVectorsYK	|Single	|-1.992875
FourVectorsYRadius	|Single	|-0.8693075
FourVectorsZI	|Single	|1.322922
FourVectorsZJ	|Single	|5.942907
FourVectorsZK	|Single	|1.39699
FourVectorsZRadius	|Single	|-0.5490851


**12:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.002083451
FourVectorsXJ	|Single	|0.002083451
FourVectorsXK	|Single	|0.3686762
FourVectorsXRadius	|Single	|0.3686764
FourVectorsYI	|Single	|6.033181
FourVectorsYJ	|Single	|7.15675
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.113986
FourVectorsZI	|Single	|6.016974
FourVectorsZJ	|Single	|4.070899
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.144968


**13:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686766
FourVectorsXJ	|Single	|0.3686768
FourVectorsXK	|Single	|0.6933619
FourVectorsXRadius	|Single	|0.6933621
FourVectorsYI	|Single	|-1.950112
FourVectorsYJ	|Single	|6.075944
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|6.992208
FourVectorsZI	|Single	|1.322921
FourVectorsZJ	|Single	|5.942906
FourVectorsZK	|Single	|-0.2640901
FourVectorsZRadius	|Single	|4.355895


**14:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933624
FourVectorsXJ	|Single	|0.6933626
FourVectorsXK	|Single	|0.9103104
FourVectorsXRadius	|Single	|0.9103104
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.197724
FourVectorsYK	|Single	|-1.646076
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.111993
FourVectorsZJ	|Single	|5.731978
FourVectorsZK	|Single	|0.7963173
FourVectorsZRadius	|Single	|0.05158639


**15:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103104
FourVectorsXJ	|Single	|0.9103107
FourVectorsXK	|Single	|0.9864926
FourVectorsXRadius	|Single	|0.9864929
FourVectorsYI	|Single	|6.809951
FourVectorsYJ	|Single	|6.37998
FourVectorsYK	|Single	|-1.431092
FourVectorsYRadius	|Single	|6.594965
FourVectorsZI	|Single	|4.671572
FourVectorsZJ	|Single	|5.416302
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|5.043937


**16:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061437
FourVectorsXJ	|Single	|-0.9061432
FourVectorsXK	|Single	|-0.7827143
FourVectorsXRadius	|Single	|-0.782714
FourVectorsYI	|Single	|-1.989382
FourVectorsYJ	|Single	|-0.6089558
FourVectorsYK	|Single	|-1.431092
FourVectorsYRadius	|Single	|-0.3939703
FourVectorsZI	|Single	|0.5820925
FourVectorsZJ	|Single	|1.414037
FourVectorsZK	|Single	|0.4239522
FourVectorsZRadius	|Single	|1.041671


**17:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.7006913
FourVectorsXJ	|Single	|-0.7006909
FourVectorsXK	|Single	|-0.6891956
FourVectorsXRadius	|Single	|-0.689195
FourVectorsYI	|Single	|-1.449989
FourVectorsYJ	|Single	|-2.225959
FourVectorsYK	|Single	|-2.171637
FourVectorsYRadius	|Single	|-0.791211
FourVectorsZI	|Single	|2.574063
FourVectorsZJ	|Single	|2.217901
FourVectorsZK	|Single	|0.8977688
FourVectorsZRadius	|Single	|1.696913


**18:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933624
FourVectorsXJ	|Single	|0.693363
FourVectorsXK	|Single	|0.704859
FourVectorsXRadius	|Single	|0.7048594
FourVectorsYI	|Single	|-2.171637
FourVectorsYJ	|Single	|-0.7912104
FourVectorsYK	|Single	|-1.449989
FourVectorsYRadius	|Single	|-2.225959
FourVectorsZI	|Single	|0.8977685
FourVectorsZJ	|Single	|1.696913
FourVectorsZK	|Single	|2.574062
FourVectorsZRadius	|Single	|2.217901


**19:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.7868811
FourVectorsXJ	|Single	|0.7868815
FourVectorsXK	|Single	|0.9103104
FourVectorsXRadius	|Single	|0.910311
FourVectorsYI	|Single	|-1.431091
FourVectorsYJ	|Single	|-0.3939703
FourVectorsYK	|Single	|-1.989381
FourVectorsYRadius	|Single	|-0.6089555
FourVectorsZI	|Single	|0.4239516
FourVectorsZJ	|Single	|1.041672
FourVectorsZK	|Single	|0.5820925
FourVectorsZRadius	|Single	|1.414036


**20:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.982326
FourVectorsXJ	|Single	|-0.9823259
FourVectorsXK	|Single	|-0.9061441
FourVectorsXRadius	|Single	|-0.906144
FourVectorsYI	|Single	|-1.431092
FourVectorsYJ	|Single	|6.52989
FourVectorsYK	|Single	|6.744876
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|0.4239523
FourVectorsZJ	|Single	|5.006366
FourVectorsZK	|Single	|4.634001
FourVectorsZRadius	|Single	|0.05158687


**21:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.9061438
FourVectorsXJ	|Single	|-0.9061435
FourVectorsXK	|Single	|-0.6891959
FourVectorsXRadius	|Single	|-0.6891958
FourVectorsYI	|Single	|-1.646077
FourVectorsYJ	|Single	|6.314904
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|6.927133
FourVectorsZI	|Single	|0.7963172
FourVectorsZJ	|Single	|5.378732
FourVectorsZK	|Single	|-0.2640893
FourVectorsZRadius	|Single	|4.318325


**22:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.6891956
FourVectorsXJ	|Single	|-0.6891954
FourVectorsXK	|Single	|-0.36451
FourVectorsXRadius	|Single	|-0.3645099
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.132649
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.04891
FourVectorsZI	|Single	|1.111994
FourVectorsZJ	|Single	|5.694407
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.107397


**23:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|-0.3645096
FourVectorsXJ	|Single	|-0.3645093
FourVectorsXK	|Single	|0.002083451
FourVectorsXRadius	|Single	|0.002083451
FourVectorsYI	|Single	|-1.950112
FourVectorsYJ	|Single	|6.01087
FourVectorsYK	|Single	|-1.992875
FourVectorsYRadius	|Single	|-0.8693078
FourVectorsZI	|Single	|1.322922
FourVectorsZJ	|Single	|5.905336
FourVectorsZK	|Single	|1.39699
FourVectorsZRadius	|Single	|-0.5490851


**24:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.002083451
FourVectorsXJ	|Single	|0.002083451
FourVectorsXK	|Single	|0.3686762
FourVectorsXRadius	|Single	|0.3686764
FourVectorsYI	|Single	|5.968106
FourVectorsYJ	|Single	|7.091674
FourVectorsYK	|Single	|-0.9120708
FourVectorsYRadius	|Single	|7.04891
FourVectorsZI	|Single	|5.979403
FourVectorsZJ	|Single	|4.033329
FourVectorsZK	|Single	|-0.4750175
FourVectorsZRadius	|Single	|4.107397


**25:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.3686766
FourVectorsXJ	|Single	|0.3686768
FourVectorsXK	|Single	|0.6933619
FourVectorsXRadius	|Single	|0.6933621
FourVectorsYI	|Single	|-1.950112
FourVectorsYJ	|Single	|6.010869
FourVectorsYK	|Single	|-1.03385
FourVectorsYRadius	|Single	|6.927133
FourVectorsZI	|Single	|1.322921
FourVectorsZJ	|Single	|5.905335
FourVectorsZK	|Single	|-0.2640901
FourVectorsZRadius	|Single	|4.318324


**26:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.6933624
FourVectorsXJ	|Single	|0.6933626
FourVectorsXK	|Single	|0.9103104
FourVectorsXRadius	|Single	|0.9103104
FourVectorsYI	|Single	|-1.828332
FourVectorsYJ	|Single	|6.132649
FourVectorsYK	|Single	|-1.646077
FourVectorsYRadius	|Single	|-1.216106
FourVectorsZI	|Single	|1.111993
FourVectorsZJ	|Single	|5.694407
FourVectorsZK	|Single	|0.7963173
FourVectorsZRadius	|Single	|0.05158639


**27:**

Name	| Type	| Value
---	|---	|---	|
FourVectorsXI	|Single	|0.9103104
FourVectorsXJ	|Single	|0.9103107
FourVectorsXK	|Single	|0.9864926
FourVectorsXRadius	|Single	|0.9864929
FourVectorsYI	|Single	|6.744875
FourVectorsYJ	|Single	|6.314905
FourVectorsYK	|Single	|-1.431091
FourVectorsYRadius	|Single	|6.52989
FourVectorsZI	|Single	|4.634
FourVectorsZJ	|Single	|5.378731
FourVectorsZK	|Single	|0.4239516
FourVectorsZRadius	|Single	|5.006366


### PolyhedronPlaneEquations

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9934111
Unknown2	|Single	|-0.05682349
Unknown3	|Single	|0.0995273
Unknown4	|Single	|-1.099368


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9846636
Unknown2	|Single	|0.08650167
Unknown3	|Single	|-0.1515095
Unknown4	|Single	|-0.779236


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.859314
Unknown2	|Single	|0.2535834
Unknown3	|Single	|-0.4441564
Unknown4	|Single	|-0.4473653


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8593134
Unknown2	|Single	|-0.2535841
Unknown3	|Single	|0.4441572
Unknown4	|Single	|-1.667601


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8402501
Unknown2	|Single	|0.2741696
Unknown3	|Single	|-0.467772
Unknown4	|Single	|-0.4191801


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8402501
Unknown2	|Single	|-0.2741697
Unknown3	|Single	|0.4677721
Unknown4	|Single	|-1.7101


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6000624
Unknown2	|Single	|-0.4045064
Unknown3	|Single	|0.6901448
Unknown4	|Single	|-2.082228


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6000621
Unknown2	|Single	|0.4045064
Unknown3	|Single	|-0.690145
Unknown4	|Single	|-0.1776212


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2271962
Unknown2	|Single	|0.4924393
Unknown3	|Single	|-0.8401699
Unknown4	|Single	|-0.03277137


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2271944
Unknown2	|Single	|-0.4924392
Unknown3	|Single	|0.8401704
Unknown4	|Single	|-2.351407


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.1036122
Unknown2	|Single	|0.8703955
Unknown3	|Single	|0.4813277
Unknown4	|Single	|-1.533793


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.09164853
Unknown2	|Single	|-0.8676184
Unknown3	|Single	|-0.4887114
Unknown4	|Single	|-1.12448


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.04294886
Unknown2	|Single	|0.8627381
Unknown3	|Single	|0.5038239
Unknown4	|Single	|-1.5059


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.03489234
Unknown2	|Single	|-0.86239
Unknown3	|Single	|-0.5050406
Unknown4	|Single	|-1.054322


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.0153876
Unknown2	|Single	|0.8613086
Unknown3	|Single	|0.507849
Unknown4	|Single	|-1.489328


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.01538348
Unknown2	|Single	|-0.8613089
Unknown3	|Single	|-0.5078488
Unknown4	|Single	|-1.035185


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.006870179
Unknown2	|Single	|0.8613904
Unknown3	|Single	|0.5078973
Unknown4	|Single	|-1.483598


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.006867681
Unknown2	|Single	|-0.8613905
Unknown3	|Single	|-0.507897
Unknown4	|Single	|-1.029413


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.001953022
Unknown2	|Single	|-0.8618072
Unknown3	|Single	|-0.5072322
Unknown4	|Single	|-1.027685


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.001949391
Unknown2	|Single	|0.8618075
Unknown3	|Single	|0.5072317
Unknown4	|Single	|-1.48001


**20:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-5.448855E-06
Unknown2	|Single	|0.8660316
Unknown3	|Single	|0.4999894
Unknown4	|Single	|-1.476171


**21:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-2.822883E-06
Unknown2	|Single	|-0.8660225
Unknown3	|Single	|-0.5000052
Unknown4	|Single	|-1.043771


**22:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.001953029
Unknown2	|Single	|-0.8618072
Unknown3	|Single	|-0.5072321
Unknown4	|Single	|-1.027694


**23:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.001953891
Unknown2	|Single	|0.8618068
Unknown3	|Single	|0.5072331
Unknown4	|Single	|-1.480022


**24:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.006863515
Unknown2	|Single	|0.8613904
Unknown3	|Single	|0.5078971
Unknown4	|Single	|-1.483623


**25:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.006867802
Unknown2	|Single	|-0.8613905
Unknown3	|Single	|-0.507897
Unknown4	|Single	|-1.029441


**26:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.01538296
Unknown2	|Single	|-0.8613089
Unknown3	|Single	|-0.5078488
Unknown4	|Single	|-1.035248


**27:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.01538769
Unknown2	|Single	|0.8613087
Unknown3	|Single	|0.5078489
Unknown4	|Single	|-1.489393


**28:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.0348939
Unknown2	|Single	|-0.86239
Unknown3	|Single	|-0.5050403
Unknown4	|Single	|-1.054469


**29:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.04295338
Unknown2	|Single	|0.8627384
Unknown3	|Single	|0.503823
Unknown4	|Single	|-1.506082


**30:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.09165116
Unknown2	|Single	|-0.8676185
Unknown3	|Single	|-0.4887106
Unknown4	|Single	|-1.124865


**31:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.103629
Unknown2	|Single	|0.8703967
Unknown3	|Single	|0.4813219
Unknown4	|Single	|-1.534233


**32:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2271941
Unknown2	|Single	|0.4924392
Unknown3	|Single	|-0.8401706
Unknown4	|Single	|-0.03371744


**33:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2271945
Unknown2	|Single	|-0.4924394
Unknown3	|Single	|0.8401703
Unknown4	|Single	|-2.352353


**34:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6000597
Unknown2	|Single	|0.4045077
Unknown3	|Single	|-0.6901464
Unknown4	|Single	|-0.1801198


**35:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6000623
Unknown2	|Single	|-0.4045066
Unknown3	|Single	|0.6901447
Unknown4	|Single	|-2.084728


**36:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8402498
Unknown2	|Single	|-0.2741701
Unknown3	|Single	|0.4677724
Unknown4	|Single	|-1.713602


**37:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8402507
Unknown2	|Single	|0.2741693
Unknown3	|Single	|-0.4677714
Unknown4	|Single	|-0.4226817


**38:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8593139
Unknown2	|Single	|0.2535837
Unknown3	|Single	|-0.4441565
Unknown4	|Single	|-0.4509453


**39:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8593146
Unknown2	|Single	|-0.2535829
Unknown3	|Single	|0.4441557
Unknown4	|Single	|-1.671179


**40:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9846634
Unknown2	|Single	|0.08650216
Unknown3	|Single	|-0.15151
Unknown4	|Single	|-0.7833378


**41:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9934109
Unknown2	|Single	|-0.05682336
Unknown3	|Single	|0.09952729
Unknown4	|Single	|-1.103507


**42:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9846639
Unknown2	|Single	|0.08703516
Unknown3	|Single	|-0.1512016
Unknown4	|Single	|-0.7786033


**43:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9846637
Unknown2	|Single	|-0.08703566
Unknown3	|Single	|0.1512025
Unknown4	|Single	|-1.15592


**44:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8593168
Unknown2	|Single	|0.2551475
Unknown3	|Single	|-0.4432543
Unknown4	|Single	|-0.4455122


**45:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8593164
Unknown2	|Single	|-0.2551479
Unknown3	|Single	|0.443255
Unknown4	|Single	|-1.551629


**46:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6000707
Unknown2	|Single	|0.3990751
Unknown3	|Single	|-0.6932923
Unknown4	|Single	|-0.1840731


**47:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6000706
Unknown2	|Single	|-0.3990752
Unknown3	|Single	|0.6932924
Unknown4	|Single	|-1.914145


**48:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2271999
Unknown2	|Single	|0.4858305
Unknown3	|Single	|-0.8440077
Unknown4	|Single	|-0.04062363


**49:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2271985
Unknown2	|Single	|-0.4858306
Unknown3	|Single	|0.844008
Unknown4	|Single	|-2.146797


**50:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-2.715615E-06
Unknown2	|Single	|0.8660287
Unknown3	|Single	|0.4999943
Unknown4	|Single	|-8.233377


**51:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1.616436E-06
Unknown2	|Single	|-0.866025
Unknown3	|Single	|-0.5000008
Unknown4	|Single	|-1.027385


**52:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2271984
Unknown2	|Single	|-0.4858307
Unknown3	|Single	|0.844008
Unknown4	|Single	|-2.147744


**53:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2271986
Unknown2	|Single	|0.4858306
Unknown3	|Single	|-0.844008
Unknown4	|Single	|-0.04156977


**54:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6000683
Unknown2	|Single	|0.3990761
Unknown3	|Single	|-0.6932939
Unknown4	|Single	|-0.186572


**55:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6000701
Unknown2	|Single	|-0.3990754
Unknown3	|Single	|0.6932926
Unknown4	|Single	|-1.916645


**56:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8593162
Unknown2	|Single	|0.255148
Unknown3	|Single	|-0.4432551
Unknown4	|Single	|-0.4490918


**57:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8593165
Unknown2	|Single	|-0.2551478
Unknown3	|Single	|0.4432547
Unknown4	|Single	|-1.555209


**58:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9846637
Unknown2	|Single	|0.08703591
Unknown3	|Single	|-0.1512029
Unknown4	|Single	|-0.7827047


**59:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9846638
Unknown2	|Single	|-0.08703563
Unknown3	|Single	|0.1512023
Unknown4	|Single	|-1.160022


**60:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9910251
Unknown2	|Single	|-0.0690001
Unknown3	|Single	|0.1144908
Unknown4	|Single	|-1.101923


**61:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9894787
Unknown2	|Single	|-0.06035292
Unknown3	|Single	|0.1314897
Unknown4	|Single	|-1.119293


**62:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9611675
Unknown2	|Single	|0.1424474
Unknown3	|Single	|-0.2363592
Unknown4	|Single	|-0.4499907


**63:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9597082
Unknown2	|Single	|0.1437926
Unknown3	|Single	|-0.2414206
Unknown4	|Single	|-0.4430462


**64:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6098781
Unknown2	|Single	|-0.7915893
Unknown3	|Single	|-0.03788409
Unknown4	|Single	|-2.105358


**65:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.1088697
Unknown2	|Single	|0.7955311
Unknown3	|Single	|0.5960518
Unknown4	|Single	|-0.4570475


**66:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-5.959096E-07
Unknown2	|Single	|0.8406285
Unknown3	|Single	|0.541612
Unknown4	|Single	|-0.2539543


**67:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-5.93423E-07
Unknown2	|Single	|0.7995992
Unknown3	|Single	|0.6005341
Unknown4	|Single	|-0.3864028


**68:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-5.53166E-07
Unknown2	|Single	|0.5117192
Unknown3	|Single	|-0.8591528
Unknown4	|Single	|1.096556


**69:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-2.411773E-07
Unknown2	|Single	|-0.2725357
Unknown3	|Single	|-0.9621456
Unknown4	|Single	|0.01787989


**70:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1.515529E-07
Unknown2	|Single	|0.8660253
Unknown3	|Single	|0.5
Unknown4	|Single	|-0.1796474


**71:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1.134217E-07
Unknown2	|Single	|-0.8660266
Unknown3	|Single	|-0.4999981
Unknown4	|Single	|-1.431812


**72:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1.394827E-08
Unknown2	|Single	|-0.9991544
Unknown3	|Single	|-0.04111465
Unknown4	|Single	|-2.132889


**73:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|3.083263E-07
Unknown2	|Single	|-0.4171475
Unknown3	|Single	|0.9088388
Unknown4	|Single	|-2.944268


**74:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.1088763
Unknown2	|Single	|0.7955296
Unknown3	|Single	|0.5960525
Unknown4	|Single	|-0.4575091


**75:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6098787
Unknown2	|Single	|-0.7915888
Unknown3	|Single	|-0.03788488
Unknown4	|Single	|-2.107898


**76:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9597083
Unknown2	|Single	|0.1437922
Unknown3	|Single	|-0.2414205
Unknown4	|Single	|-0.447046


**77:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9611672
Unknown2	|Single	|0.1424475
Unknown3	|Single	|-0.2363606
Unknown4	|Single	|-0.4539945


**78:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9894785
Unknown2	|Single	|-0.06035204
Unknown3	|Single	|0.1314904
Unknown4	|Single	|-1.123417


**79:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9910253
Unknown2	|Single	|-0.06900015
Unknown3	|Single	|0.1144897
Unknown4	|Single	|-1.106052


**80:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.984664
Unknown2	|Single	|0.08703355
Unknown3	|Single	|-0.1512025
Unknown4	|Single	|-0.7786053


**81:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.9846637
Unknown2	|Single	|-0.08703407
Unknown3	|Single	|0.1512035
Unknown4	|Single	|-1.155918


**82:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8593169
Unknown2	|Single	|0.2551428
Unknown3	|Single	|-0.4432571
Unknown4	|Single	|-0.4455177


**83:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.8593165
Unknown2	|Single	|-0.2551431
Unknown3	|Single	|0.4432575
Unknown4	|Single	|-1.551623


**84:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6000707
Unknown2	|Single	|-0.3990679
Unknown3	|Single	|0.6932966
Unknown4	|Single	|-1.914136


**85:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.6000705
Unknown2	|Single	|0.3990678
Unknown3	|Single	|-0.6932967
Unknown4	|Single	|-0.1840817


**86:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2271999
Unknown2	|Single	|0.4858216
Unknown3	|Single	|-0.8440129
Unknown4	|Single	|-0.04063385


**87:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-0.2271981
Unknown2	|Single	|-0.4858217
Unknown3	|Single	|0.8440132
Unknown4	|Single	|-2.146786


**88:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-3.837332E-06
Unknown2	|Single	|0.8660311
Unknown3	|Single	|0.49999
Unknown4	|Single	|-8.158235


**89:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|-1.550035E-06
Unknown2	|Single	|-0.8660234
Unknown3	|Single	|-0.5000035
Unknown4	|Single	|-1.027377


**90:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2271982
Unknown2	|Single	|0.4858217
Unknown3	|Single	|-0.8440132
Unknown4	|Single	|-0.04157978


**91:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.2271988
Unknown2	|Single	|-0.4858216
Unknown3	|Single	|0.8440131
Unknown4	|Single	|-2.147733


**92:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6000675
Unknown2	|Single	|0.399069
Unknown3	|Single	|-0.6932986
Unknown4	|Single	|-0.1865803


**93:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.6000701
Unknown2	|Single	|-0.3990681
Unknown3	|Single	|0.6932968
Unknown4	|Single	|-1.916636


**94:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8593163
Unknown2	|Single	|0.2551432
Unknown3	|Single	|-0.4432577
Unknown4	|Single	|-0.4490973


**95:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.8593165
Unknown2	|Single	|-0.2551431
Unknown3	|Single	|0.4432575
Unknown4	|Single	|-1.555203


**96:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9846637
Unknown2	|Single	|0.08703423
Unknown3	|Single	|-0.1512037
Unknown4	|Single	|-0.7827066


**97:**

Name	| Type	| Value
---	|---	|---	|
Unknown	|Single	|0.9846637
Unknown2	|Single	|-0.08703399
Unknown3	|Single	|0.1512032
Unknown4	|Single	|-1.16002


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
ChildShapesSize	|Int32	|4
ChildShapesCapacity	|UInt32	|2147483652
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|1065360006
Unknown10	|UInt32	|1083614700
Unknown11	|UInt32	|1079192029
Unknown12	|UInt32	|1015437643
Unknown13	|UInt32	|990415360
Unknown14	|UInt32	|1075693833
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


