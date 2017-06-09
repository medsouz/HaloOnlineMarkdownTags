# [0x1DFF] 0x00001DFF

**Name:** ```0x00001DFF```

**Index:** ```0x1DFF```

**Tag Group:** ```ChudAnimationDefinition (chad)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|UInt16	|0
Unknown	|Int16	|0
Position	|TagBlock (Position)	|0
Rotation	|TagBlock (Rotation)	|0
Size	|TagBlock (Size)	|0
Color	|TagBlock (Color)	|0
Alpha	|TagBlock (Alpha)	|[1](#alpha)
AlphaUnknown	|TagBlock (AlphaUnknown)	|0
Bitmap	|TagBlock (Bitmap)	|0
NumberOfFrames	|Int32	|10


## Tag Blocks

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
Alpha	|Single	|1.5


**1:**

Name	| Type	| Value
---	|---	|---	|
FrameNumber	|Int32	|10
Alpha	|Single	|0.2


