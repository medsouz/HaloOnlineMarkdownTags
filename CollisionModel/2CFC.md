# [0x2CFC] objects\vehicles\hornet\garbage\flap\flap_snow

**Name:** ```objects\vehicles\hornet\garbage\flap\flap_snow```

**Index:** ```0x2CFC```

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
Nodes	|TagBlock (Nodes)	|[1](#nodes)


## Tag Blocks

### Materials

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|hard_metal_thick_hum_hornet


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


### Nodes

**0:**

Name	| Type	| Value
---	|---	|---	|
Name	|StringId	|flap
Flags	|Enum (NodeFlags)	|null
ParentNode	|Int16	|-1
NextSiblingNode	|Int16	|-1
FirstChildNode	|Int16	|-1


