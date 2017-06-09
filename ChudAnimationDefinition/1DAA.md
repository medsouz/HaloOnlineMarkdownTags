# [0x1DAA] 0x00001DAA

**Name:** ```0x00001DAA```

**Index:** ```0x1DAA```

**Tag Group:** ```ChudAnimationDefinition (chad)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt16	|0
Unknown	|Int16	|0
Position	|TagBlock (Position)	|0
Rotation	|TagBlock (Rotation)	|0
Size	|TagBlock (Size)	|[1](#size)
Color	|TagBlock (Color)	|0
Alpha	|TagBlock (Alpha)	|[1](#alpha)
AlphaUnknown	|TagBlock (AlphaUnknown)	|0
Bitmap	|TagBlock (Bitmap)	|0
NumberOfFrames	|Int32	|40


## Tag Blocks

### Size

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Size_Animation)	|[2](#size_animation)
Unknown	|Byte[]	|System.Byte[]


### Size_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|0
StretchX	|Single	|0.2
StretchY	|Single	|0.2


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|40
StretchX	|Single	|1.4
StretchY	|Single	|1.4


### Alpha

**0:**

Name	| Type	| Value
---	|---	|---	|
Animation	|TagBlock (Alpha_Animation)	|[2](#alpha_animation)
Function	|Byte[]	|System.Byte[]


### Alpha_Animation

**0:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|0
Alpha	|Single	|1


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|40
Alpha	|Single	|1


