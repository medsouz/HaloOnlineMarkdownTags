# 0x4EEE

**Index:** ```0x4EEE```

**Tag Group:** ```CollisionModel (coll)```

## Fields

Name	| Type	| Value
---	|---	|---	|
CollisionModelChecksum	|Int32	|319819549
Errors	|TagBlock (Errors)	|0
Flags	|UInt32	|0
Materials	|TagBlock (Materials)	|[2](#materials)
Regions	|TagBlock (Regions)	|[1](#regions)
PathfindingSpheres	|TagBlock (PathfindingSpheres)	|[2](#pathfindingspheres)
Nodes	|TagBlock (Nodes)	|[1](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thin


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|soft_inorganic_vinyl


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
Bsps	|TagBlock (Regions_Permutations_Bsps)	|[1](#regions_permutations_bsps)
BspPhysics	|TagBlock (Regions_Permutations_BspPhysics)	|0
BspMoppCodes	|TagBlock (Regions_Permutations_BspMoppCodes)	|0


### Regions_Permutations_Bsps

**0:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|0
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


### PathfindingSpheres

**0:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|0
Flags	|Enum (PathfindingSphereFlags)	|null
Center	|RealPoint3d	|{ X: -0.2524377, Y: 0, Z: 0.157548 }
Radius	|Single	|0.35


**1:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|0
Flags	|Enum (PathfindingSphereFlags)	|null
Center	|RealPoint3d	|{ X: 0.2575622, Y: 0, Z: 0.157548 }
Radius	|Single	|0.35


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|node02
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


