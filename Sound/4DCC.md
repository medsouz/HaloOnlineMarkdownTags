# 0x4DCC

**Index:** ```0x4DCC```

**Tag Group:** ```Sound (snd!)```

## Fields

Name	| Type	| Value
---	|---	|---	|
Flags	|Enum (FlagsValue)	|null
Unknown1	|Int16	|0
Unknown2	|UInt32	|0
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
PermutationCount	|Byte	|7
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[7](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|608152
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|348888
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|240060
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**3:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves4
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|339284
PermutationNumber	|UInt32	|3
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**4:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves5
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|422506
PermutationNumber	|UInt32	|4
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**5:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves6
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|326481
PermutationNumber	|UInt32	|5
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**6:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|stereo_leaves7
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|396899
PermutationNumber	|UInt32	|6
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|13472
Unknown2	|Byte	|4
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|275616
Size	|UInt16	|27094
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|433782
Size	|UInt16	|43562
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|542880
Size	|UInt16	|22918
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|696870
Size	|UInt16	|60502
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|888444
Size	|UInt16	|17176
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|1036692
Size	|UInt16	|49018
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


### ExtraInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
LanguagePermutations	|TagBlock (ExtraInfo_LanguagePermutations)	|[7](#extrainfo_languagepermutations)
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


**3:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**4:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**5:**

Name	| Type	| Value
---	|---	|---	|
RawInfo	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo)	|[1](#extrainfo_languagepermutations_rawinfo)


**6:**

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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[26](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|608152
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|275616
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[15](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|348888
ResourceSampleOffset	|UInt32	|275616
ResourceSampleSize	|UInt32	|158166
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[10](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|240060
ResourceSampleOffset	|UInt32	|433782
ResourceSampleSize	|UInt32	|109098
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[15](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|339284
ResourceSampleOffset	|UInt32	|542880
ResourceSampleSize	|UInt32	|153990
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[17](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|422506
ResourceSampleOffset	|UInt32	|696870
ResourceSampleSize	|UInt32	|191574
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
SampleCount	|UInt32	|326481
ResourceSampleOffset	|UInt32	|888444
ResourceSampleSize	|UInt32	|148248
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[17](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|396899
ResourceSampleOffset	|UInt32	|1036692
ResourceSampleSize	|UInt32	|180090
Unknown20	|UInt32	|0
Unknown21	|UInt32	|0
Unknown22	|UInt32	|0
Unknown23	|UInt32	|0
Unknown24	|Int32	|480


### ExtraInfo_LanguagePermutations_RawInfo_UnknownList

**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|47616
Unknown3	|UInt32	|0
Unknown4	|UInt32	|47232
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|47232
Unknown4	|UInt32	|68736
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|68736
Unknown4	|UInt32	|89728
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|89728
Unknown4	|UInt32	|110208
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|110208
Unknown4	|UInt32	|130688
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|130688
Unknown4	|UInt32	|151168
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|151168
Unknown4	|UInt32	|171648
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|171648
Unknown4	|UInt32	|192128
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|192128
Unknown4	|UInt32	|212608
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|212608
Unknown4	|UInt32	|232576
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|232576
Unknown4	|UInt32	|252544
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|252544
Unknown4	|UInt32	|273024
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|273024
Unknown4	|UInt32	|293504
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|293504
Unknown4	|UInt32	|313472
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|313472
Unknown4	|UInt32	|333440
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|245760


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|333440
Unknown4	|UInt32	|353408
Unknown5	|UInt32	|245760
Unknown6	|UInt32	|262144


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19456
Unknown3	|UInt32	|353408
Unknown4	|UInt32	|372864
Unknown5	|UInt32	|262144
Unknown6	|UInt32	|278528


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|372864
Unknown4	|UInt32	|392832
Unknown5	|UInt32	|278528
Unknown6	|UInt32	|294912


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19456
Unknown3	|UInt32	|392832
Unknown4	|UInt32	|412288
Unknown5	|UInt32	|294912
Unknown6	|UInt32	|311296


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|412288
Unknown4	|UInt32	|432256
Unknown5	|UInt32	|311296
Unknown6	|UInt32	|327680


**20:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|432256
Unknown4	|UInt32	|452736
Unknown5	|UInt32	|327680
Unknown6	|UInt32	|344064


**21:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|452736
Unknown4	|UInt32	|473728
Unknown5	|UInt32	|344064
Unknown6	|UInt32	|360448


**22:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|473728
Unknown4	|UInt32	|495232
Unknown5	|UInt32	|360448
Unknown6	|UInt32	|376832


**23:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22528
Unknown3	|UInt32	|495232
Unknown4	|UInt32	|517760
Unknown5	|UInt32	|376832
Unknown6	|UInt32	|393216


**24:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|25600
Unknown3	|UInt32	|517760
Unknown4	|UInt32	|543360
Unknown5	|UInt32	|393216
Unknown6	|UInt32	|409600


**25:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|64896
Unknown3	|UInt32	|543360
Unknown4	|UInt32	|608256
Unknown5	|UInt32	|409600
Unknown6	|UInt32	|425984


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|32768
Unknown3	|UInt32	|0
Unknown4	|UInt32	|32384
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|32384
Unknown4	|UInt32	|52864
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|52864
Unknown4	|UInt32	|72832
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|19968
Unknown3	|UInt32	|72832
Unknown4	|UInt32	|92800
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|92800
Unknown4	|UInt32	|113280
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|113280
Unknown4	|UInt32	|134272
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|134272
Unknown4	|UInt32	|154752
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|154752
Unknown4	|UInt32	|175744
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|175744
Unknown4	|UInt32	|196224
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|196224
Unknown4	|UInt32	|217216
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|217216
Unknown4	|UInt32	|238720
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|238720
Unknown4	|UInt32	|260224
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22528
Unknown3	|UInt32	|260224
Unknown4	|UInt32	|282752
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|282752
Unknown4	|UInt32	|308864
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|40064
Unknown3	|UInt32	|308864
Unknown4	|UInt32	|348928
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|237568


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|31232
Unknown3	|UInt32	|0
Unknown4	|UInt32	|30848
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|30848
Unknown4	|UInt32	|52352
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|52352
Unknown4	|UInt32	|73856
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|73856
Unknown4	|UInt32	|95360
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|95360
Unknown4	|UInt32	|116352
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|116352
Unknown4	|UInt32	|137344
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|137344
Unknown4	|UInt32	|157824
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|157824
Unknown4	|UInt32	|178816
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22528
Unknown3	|UInt32	|178816
Unknown4	|UInt32	|201344
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|38784
Unknown3	|UInt32	|201344
Unknown4	|UInt32	|240128
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|161792


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|37888
Unknown3	|UInt32	|0
Unknown4	|UInt32	|37504
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|37504
Unknown4	|UInt32	|59008
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|59008
Unknown4	|UInt32	|79488
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|79488
Unknown4	|UInt32	|99968
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|99968
Unknown4	|UInt32	|120448
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|120448
Unknown4	|UInt32	|141440
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|141440
Unknown4	|UInt32	|162432
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|162432
Unknown4	|UInt32	|182912
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|182912
Unknown4	|UInt32	|203392
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|203392
Unknown4	|UInt32	|223872
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|223872
Unknown4	|UInt32	|244864
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|244864
Unknown4	|UInt32	|265856
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|23040
Unknown3	|UInt32	|265856
Unknown4	|UInt32	|288896
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|32768
Unknown3	|UInt32	|288896
Unknown4	|UInt32	|321664
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|17664
Unknown3	|UInt32	|321664
Unknown4	|UInt32	|339328
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|231424


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|49152
Unknown3	|UInt32	|0
Unknown4	|UInt32	|48768
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22528
Unknown3	|UInt32	|48768
Unknown4	|UInt32	|71296
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|71296
Unknown4	|UInt32	|92288
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|92288
Unknown4	|UInt32	|112768
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|112768
Unknown4	|UInt32	|133248
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|133248
Unknown4	|UInt32	|153728
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|153728
Unknown4	|UInt32	|174720
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|174720
Unknown4	|UInt32	|195712
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|195712
Unknown4	|UInt32	|216704
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|216704
Unknown4	|UInt32	|237184
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|237184
Unknown4	|UInt32	|257664
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|257664
Unknown4	|UInt32	|278656
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|278656
Unknown4	|UInt32	|299648
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|299648
Unknown4	|UInt32	|321152
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|23552
Unknown3	|UInt32	|321152
Unknown4	|UInt32	|344704
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|245760


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|344704
Unknown4	|UInt32	|373888
Unknown5	|UInt32	|245760
Unknown6	|UInt32	|262144


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|48640
Unknown3	|UInt32	|373888
Unknown4	|UInt32	|422528
Unknown5	|UInt32	|262144
Unknown6	|UInt32	|270336


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|48128
Unknown3	|UInt32	|0
Unknown4	|UInt32	|47744
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|23040
Unknown3	|UInt32	|47744
Unknown4	|UInt32	|70784
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|70784
Unknown4	|UInt32	|92288
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|92288
Unknown4	|UInt32	|113280
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|113280
Unknown4	|UInt32	|134272
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|134272
Unknown4	|UInt32	|154752
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|154752
Unknown4	|UInt32	|175232
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|175232
Unknown4	|UInt32	|196224
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|196224
Unknown4	|UInt32	|217216
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|217216
Unknown4	|UInt32	|238208
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|238208
Unknown4	|UInt32	|259200
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|259200
Unknown4	|UInt32	|280192
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|23040
Unknown3	|UInt32	|280192
Unknown4	|UInt32	|303232
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|23296
Unknown3	|UInt32	|303232
Unknown4	|UInt32	|326528
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|221184


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|41472
Unknown3	|UInt32	|0
Unknown4	|UInt32	|41088
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|41088
Unknown4	|UInt32	|62592
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|62592
Unknown4	|UInt32	|84096
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|84096
Unknown4	|UInt32	|105088
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|21504
Unknown3	|UInt32	|105088
Unknown4	|UInt32	|126592
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22528
Unknown3	|UInt32	|126592
Unknown4	|UInt32	|149120
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22016
Unknown3	|UInt32	|149120
Unknown4	|UInt32	|171136
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22016
Unknown3	|UInt32	|171136
Unknown4	|UInt32	|193152
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|193152
Unknown4	|UInt32	|214144
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|214144
Unknown4	|UInt32	|235136
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|235136
Unknown4	|UInt32	|255616
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|255616
Unknown4	|UInt32	|276096
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20480
Unknown3	|UInt32	|276096
Unknown4	|UInt32	|296576
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|296576
Unknown4	|UInt32	|317568
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|20992
Unknown3	|UInt32	|317568
Unknown4	|UInt32	|338560
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|245760


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22528
Unknown3	|UInt32	|338560
Unknown4	|UInt32	|361088
Unknown5	|UInt32	|245760
Unknown6	|UInt32	|262144


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|35840
Unknown3	|UInt32	|361088
Unknown4	|UInt32	|396928
Unknown5	|UInt32	|262144
Unknown6	|UInt32	|278528


