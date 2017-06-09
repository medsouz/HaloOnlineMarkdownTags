# 0x4CBE

**Index:** ```0x4CBE```

**Tag Group:** ```Sound (snd!)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
Unknown1	|Int16	|0
Unknown2	|UInt32	|14
Unknown3	|UInt32	|0
SoundClass	|Enum (SoundClassValue)	|null
SampleRate	|Enum (SampleRateValue)	|null
Unknown6	|SByte	|0
ImportType	|Enum (ImportTypeValue)	|null
PlaybackParameters	|PlaybackParameter	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PlaybackParameter
Scale	|Scale	|BlamCore.TagDefinitions.SoundCacheFileGestalt+Scale
PlatformCodec	|PlatformCodecBlock	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PlatformCodecBlock
Promotion	|Promotion	|BlamCore.TagDefinitions.SoundCacheFileGestalt+Promotion
PitchRanges	|TagBlock (PitchRanges)	|[1](#pitchranges)
CustomPlayBacks	|TagBlock (CustomPlayBacks)	|0
ExtraInfo	|TagBlock (ExtraInfo)	|[1](#extrainfo)
Languages	|TagBlock (Languages)	|0
Resource	|ResourceReference	|BlamCore.Cache.ResourceReference


## Tag Blocks

### PitchRanges

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	||default|
PitchRangeParameters	|PitchRangeParametersBlock	|BlamCore.TagDefinitions.SoundCacheFileGestalt+PitchRangeParametersBlock
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|Int16	|-1
Unknown6	|Int16	|-1
PermutationCount	|Byte	|3
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[3](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|hallway1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|168820
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|hallway2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|372310
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|hallway3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|333121
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|11720
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|77256
Size	|UInt16	|38056
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|246384
Size	|UInt16	|20308
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


### ExtraInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
LanguagePermutations	|TagBlock (ExtraInfo_LanguagePermutations)	|[3](#extrainfo_languagepermutations)
EncodedPermutationSections	|TagBlock (ExtraInfo_EncodedPermutationSections)	|0
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0


### ExtraInfo_LanguagePermutations

**0:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**1:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**2:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


### ExtraInfo_LanguagePermutations_RawInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
SkipFractionName	|StringId	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[7](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|168820
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|77256
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|1
Unknown24	|Int32	|680


**0:**

Name	| Type	| Value
---	|---	|---	|
SkipFractionName	|StringId	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[14](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|372310
ResourceSampleOffset	|UInt32	|77256
ResourceSampleSize	|UInt32	|169128
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|1
Unknown24	|Int32	|680


**0:**

Name	| Type	| Value
---	|---	|---	|
SkipFractionName	|StringId	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0
Unknown3	|UInt32	|0
Unknown4	|UInt32	|0
Unknown5	|UInt32	|0
Unknown6	|UInt32	|0
Unknown7	|UInt32	|0
Unknown8	|UInt32	|0
Unknown9	|UInt32	|0
Unknown10	|UInt32	|0
Unknown11	|UInt32	|0
Unknown12	|UInt32	|0
Unknown13	|UInt32	|0
Unknown14	|UInt32	|0
Unknown15	|UInt32	|0
Unknown16	|UInt32	|0
Unknown17	|UInt32	|0
Unknown18	|UInt32	|0
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[13](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|333121
ResourceSampleOffset	|UInt32	|246384
ResourceSampleSize	|UInt32	|151380
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|1
Unknown24	|Int32	|680


### ExtraInfo_LanguagePermutations_RawInfo_UnknownList

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|0
Unknown4	|UInt32	|27264
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|27264
Unknown4	|UInt32	|54912
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|54912
Unknown4	|UInt32	|82048
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|82048
Unknown4	|UInt32	|110208
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|110208
Unknown4	|UInt32	|137856
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|137856
Unknown4	|UInt32	|164992
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|3712
Unknown3	|UInt32	|164992
Unknown4	|UInt32	|168704
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|102400


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|0
Unknown4	|UInt32	|27264
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|27264
Unknown4	|UInt32	|54400
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|54400
Unknown4	|UInt32	|81536
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26624
Unknown3	|UInt32	|81536
Unknown4	|UInt32	|108160
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26624
Unknown3	|UInt32	|108160
Unknown4	|UInt32	|134784
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26624
Unknown3	|UInt32	|134784
Unknown4	|UInt32	|161408
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|161408
Unknown4	|UInt32	|188544
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|188544
Unknown4	|UInt32	|216192
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|216192
Unknown4	|UInt32	|243328
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|243328
Unknown4	|UInt32	|270976
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|270976
Unknown4	|UInt32	|298624
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|298624
Unknown4	|UInt32	|326272
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|326272
Unknown4	|UInt32	|353920
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|18304
Unknown3	|UInt32	|353920
Unknown4	|UInt32	|372224
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|225280


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|0
Unknown4	|UInt32	|27264
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|27264
Unknown4	|UInt32	|54400
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|54400
Unknown4	|UInt32	|82048
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|82048
Unknown4	|UInt32	|109696
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|109696
Unknown4	|UInt32	|137344
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|137344
Unknown4	|UInt32	|164992
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|164992
Unknown4	|UInt32	|192640
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|192640
Unknown4	|UInt32	|220288
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|220288
Unknown4	|UInt32	|247936
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|247936
Unknown4	|UInt32	|275584
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|275584
Unknown4	|UInt32	|303232
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|303232
Unknown4	|UInt32	|330880
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|2176
Unknown3	|UInt32	|330880
Unknown4	|UInt32	|333056
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|198656


