# [0x3DAB] 0x00003DAB

**Name:** ```0x00003DAB```

**Index:** ```0x3DAB```

**Tag Group:** ```CollisionModel (coll)```

## Fields

Name	| Type	| Value
---	|---	|---	|
CollisionModelChecksum	|Int32	|320801566
Errors	|TagBlock (Errors)	|0
Flags	|UInt32	|0
Materials	|TagBlock (Materials)	|[1](#materials)
Regions	|TagBlock (Regions)	|[2](#regions)
PathfindingSpheres	|TagBlock (PathfindingSpheres)	|[2](#pathfindingspheres)
Nodes	|TagBlock (Nodes)	|[1](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thin


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|box
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|light
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Bsps	|TagBlock (Regions_Permutations_Bsps)	|[1](#regions_permutations_bsps)
BspPhysics	|TagBlock (Regions_Permutations_BspPhysics)	|0
BspMoppCodes	|TagBlock (Regions_Permutations_BspMoppCodes)	|0


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
Center	|RealPoint3d	|{ X: 0.04563477, Y: -0.0261149, Z: 0.7900645 }
Radius	|Single	|0.25


**1:**

Name	| Type	| Value
---	|---	|---	|
Node	|Int16	|0
Flags	|Enum (PathfindingSphereFlags)	|null
Center	|RealPoint3d	|{ X: -0.05543945, Y: -0.02611488, Z: 0.2454812 }
Radius	|Single	|0.34


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|node
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


