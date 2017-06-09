# 0x4DCF

**Index:** ```0x4DCF```

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
PermutationCount	|Byte	|6
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[6](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|loop1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|386078
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|loop2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|211917
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|loop3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|276829
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**3:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|loop4
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|137951
PermutationNumber	|UInt32	|3
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**4:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|loop5
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|174382
PermutationNumber	|UInt32	|4
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


**5:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|loop6
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|135298
PermutationNumber	|UInt32	|5
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|1
Unknown2	|UInt32	|680


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|44320
Unknown2	|Byte	|2
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|175392
Size	|UInt16	|31034
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|271962
Size	|UInt16	|60788
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|398286
Size	|UInt16	|63162
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|461448
Size	|UInt16	|14330
Unknown2	|Byte	|1
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|541314
Size	|UInt16	|62118
Unknown2	|Byte	|0
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


### ExtraInfo

**0:**

Name	| Type	| Value
---	|---	|---	|
LanguagePermutations	|TagBlock (ExtraInfo_LanguagePermutations)	|[6](#extrainfo_languagepermutations)
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[8](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|386078
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|175392
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[4](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|211917
ResourceSampleOffset	|UInt32	|175392
ResourceSampleSize	|UInt32	|96570
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[6](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|276829
ResourceSampleOffset	|UInt32	|271962
ResourceSampleSize	|UInt32	|126324
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[3](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|137951
ResourceSampleOffset	|UInt32	|398286
ResourceSampleSize	|UInt32	|63162
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[4](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|174382
ResourceSampleOffset	|UInt32	|461448
ResourceSampleSize	|UInt32	|79866
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[3](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|135298
ResourceSampleOffset	|UInt32	|541314
ResourceSampleSize	|UInt32	|62118
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
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|0
Unknown4	|UInt32	|54400
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|55296
Unknown3	|UInt32	|54400
Unknown4	|UInt32	|109696
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|53248
Unknown3	|UInt32	|109696
Unknown4	|UInt32	|162944
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|55296
Unknown3	|UInt32	|162944
Unknown4	|UInt32	|218240
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|55296
Unknown3	|UInt32	|218240
Unknown4	|UInt32	|273536
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|273536
Unknown4	|UInt32	|328320
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|328320
Unknown4	|UInt32	|383104
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|2944
Unknown3	|UInt32	|383104
Unknown4	|UInt32	|386048
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|116736


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|55808
Unknown3	|UInt32	|0
Unknown4	|UInt32	|55424
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54272
Unknown3	|UInt32	|55424
Unknown4	|UInt32	|109696
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|109696
Unknown4	|UInt32	|164480
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|47360
Unknown3	|UInt32	|164480
Unknown4	|UInt32	|211840
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|63488


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|0
Unknown4	|UInt32	|54400
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|54400
Unknown4	|UInt32	|109184
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|55296
Unknown3	|UInt32	|109184
Unknown4	|UInt32	|164480
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|51200
Unknown3	|UInt32	|164480
Unknown4	|UInt32	|215680
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|215680
Unknown4	|UInt32	|270464
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|6272
Unknown3	|UInt32	|270464
Unknown4	|UInt32	|276736
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|83968


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|0
Unknown4	|UInt32	|54400
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|54400
Unknown4	|UInt32	|109184
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28672
Unknown3	|UInt32	|109184
Unknown4	|UInt32	|137856
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|43008


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|54784
Unknown3	|UInt32	|0
Unknown4	|UInt32	|54400
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|55808
Unknown3	|UInt32	|54400
Unknown4	|UInt32	|110208
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|53248
Unknown3	|UInt32	|110208
Unknown4	|UInt32	|163456
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|10880
Unknown3	|UInt32	|163456
Unknown4	|UInt32	|174336
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|53248


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|53760
Unknown3	|UInt32	|0
Unknown4	|UInt32	|53376
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|55808
Unknown3	|UInt32	|53376
Unknown4	|UInt32	|109184
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|109184
Unknown4	|UInt32	|135296
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|40960


