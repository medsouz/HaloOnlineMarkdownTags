# [0x3DCD] 0x00003DCD

**Name:** ```0x00003DCD```

**Index:** ```0x3DCD```

**Tag Group:** ```CollisionModel (coll)```

## Fields

Name	| Type	| Value
---	|---	|---	|
CollisionModelChecksum	|Int32	|0
Errors	|TagBlock (Errors)	|0
Flags	|UInt32	|0
Materials	|TagBlock (Materials)	|[1](#materials)
Regions	|TagBlock (Regions)	|[1](#regions)
PathfindingSpheres	|TagBlock (PathfindingSpheres)	|0
Nodes	|TagBlock (Nodes)	|[6](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|soft_organic_flesh


### Regions

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|seagull
Permutations	|TagBlock (Regions_Permutations)	|[1](#regions_permutations)


### Regions_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|base
Bsps	|TagBlock (Regions_Permutations_Bsps)	|[3](#regions_permutations_bsps)
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
NodeIndex	|Int16	|2
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


**2:**

Name	| Type	| Value
---	|---	|---	|
NodeIndex	|Int16	|3
Padding	|Int16	|0
Geometry	|CollisionGeometry	|BlamCore.Geometry.CollisionGeometry


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|body
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|feet
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|2
FirstChildNode	|Int16	|-1


**2:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_left
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|3
FirstChildNode	|Int16	|4


**3:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_right
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|0
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|5


**4:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_left_tip
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|2
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


**5:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|wing_right_tip
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|3
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


