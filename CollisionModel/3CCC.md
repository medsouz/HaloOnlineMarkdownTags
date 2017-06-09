# [0x3CCC] 0x00003CCC

**Name:** ```0x00003CCC```

**Index:** ```0x3CCC```

**Tag Group:** ```CollisionModel (coll)```

## Fields

Name	| Type	| Value
---	|---	|---	|
CollisionModelChecksum	|Int32	|454430232
Errors	|TagBlock (Errors)	|0
Flags	|UInt32	|0
Materials	|TagBlock (Materials)	|[1](#materials)
Regions	|TagBlock (Regions)	|[2](#regions)
PathfindingSpheres	|TagBlock (PathfindingSpheres)	|0
Nodes	|TagBlock (Nodes)	|[3](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick_hum


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
Bsps	|TagBlock (Regions_Permutations_Bsps)	|[2](#regions_permutations_bsps)
BspPhysics	|TagBlock (Regions_Permutations_BspPhysics)	|0
BspMoppCodes	|TagBlock (Regions_Permutations_BspMoppCodes)	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|standard
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


**1:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|1
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**0:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|2
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|legs
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hinge_base
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|2


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|gun
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


