# 0x4CBA

**Index:** ```0x4CBA```

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
PermutationCount	|Byte	|3
Unknown7	|Byte	|0
Unknown8	|Int16	|-1
Permutations	|TagBlock (PitchRanges_Permutations)	|[3](#pitchranges_permutations)


### PitchRanges_Permutations

**0:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|day_cicada_detail1
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|497774
PermutationNumber	|UInt32	|0
IsNotFirstPermutation	|UInt32	|0
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**1:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|day_cicada_detail2
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|595168
PermutationNumber	|UInt32	|1
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


**2:**

Name	| Type	| Value
---	|---	|---	|
ImportName	|StringId	|day_cicada_detail3
SkipFraction	|Bounds`1	|{ Lower: 0, Upper: 0 }
SampleSize	|UInt32	|545026
PermutationNumber	|UInt32	|2
IsNotFirstPermutation	|UInt32	|1
PermutationChunks	|TagBlock (PitchRanges_Permutations_PermutationChunks)	|[1](#pitchranges_permutations_permutationchunks)
Unknown1	|UInt32	|0
Unknown2	|UInt32	|0


### PitchRanges_Permutations_PermutationChunks

**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|0
Size	|UInt16	|29418
Unknown2	|Byte	|3
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|226026
Size	|UInt16	|7730
Unknown2	|Byte	|4
Unknown3	|Byte	|4
RuntimeIndex	|Int32	|-1
UnknownA	|Int32	|0
UnknownSize	|Int32	|0


**0:**

Name	| Type	| Value
---	|---	|---	|
Offset	|UInt32	|495900
Size	|UInt16	|50820
Unknown2	|Byte	|3
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[17](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|497774
ResourceSampleOffset	|UInt32	|0
ResourceSampleSize	|UInt32	|226026
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[22](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|595168
ResourceSampleOffset	|UInt32	|226026
ResourceSampleSize	|UInt32	|269874
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
UnknownList	|TagBlock (ExtraInfo_LanguagePermutations_RawInfo_UnknownList)	|[19](#extrainfo_languagepermutations_rawinfo_unknownlist)
Compression	|Int16	|8
Language	|Byte	|0
Unknown19	|Byte	|0
SampleCount	|UInt32	|545026
ResourceSampleOffset	|UInt32	|495900
ResourceSampleSize	|UInt32	|247428
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
Unknown2	|UInt32	|31232
Unknown3	|UInt32	|0
Unknown4	|UInt32	|30848
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|30720
Unknown3	|UInt32	|30848
Unknown4	|UInt32	|61568
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|61568
Unknown4	|UInt32	|90752
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29696
Unknown3	|UInt32	|90752
Unknown4	|UInt32	|120448
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|30208
Unknown3	|UInt32	|120448
Unknown4	|UInt32	|150656
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|30208
Unknown3	|UInt32	|150656
Unknown4	|UInt32	|180864
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|30208
Unknown3	|UInt32	|180864
Unknown4	|UInt32	|211072
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|211072
Unknown4	|UInt32	|240256
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|240256
Unknown4	|UInt32	|267904
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|267904
Unknown4	|UInt32	|294016
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26624
Unknown3	|UInt32	|294016
Unknown4	|UInt32	|320640
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|320640
Unknown4	|UInt32	|348288
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|348288
Unknown4	|UInt32	|377472
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|377472
Unknown4	|UInt32	|406656
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|406656
Unknown4	|UInt32	|435840
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|245760


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29696
Unknown3	|UInt32	|435840
Unknown4	|UInt32	|465536
Unknown5	|UInt32	|245760
Unknown6	|UInt32	|262144


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|32256
Unknown3	|UInt32	|465536
Unknown4	|UInt32	|497792
Unknown5	|UInt32	|262144
Unknown6	|UInt32	|270336


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|30208
Unknown3	|UInt32	|0
Unknown4	|UInt32	|29824
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|29824
Unknown4	|UInt32	|59008
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28672
Unknown3	|UInt32	|59008
Unknown4	|UInt32	|87680
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|87680
Unknown4	|UInt32	|115328
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27136
Unknown3	|UInt32	|115328
Unknown4	|UInt32	|142464
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|142464
Unknown4	|UInt32	|170624
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|170624
Unknown4	|UInt32	|198272
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|198272
Unknown4	|UInt32	|225920
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|225920
Unknown4	|UInt32	|253568
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26624
Unknown3	|UInt32	|253568
Unknown4	|UInt32	|280192
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|280192
Unknown4	|UInt32	|306304
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|306304
Unknown4	|UInt32	|332416
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|332416
Unknown4	|UInt32	|358528
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|358528
Unknown4	|UInt32	|384640
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|384640
Unknown4	|UInt32	|410752
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|245760


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|410752
Unknown4	|UInt32	|436864
Unknown5	|UInt32	|245760
Unknown6	|UInt32	|262144


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|436864
Unknown4	|UInt32	|462976
Unknown5	|UInt32	|262144
Unknown6	|UInt32	|278528


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|462976
Unknown4	|UInt32	|489088
Unknown5	|UInt32	|278528
Unknown6	|UInt32	|294912


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|26112
Unknown3	|UInt32	|489088
Unknown4	|UInt32	|515200
Unknown5	|UInt32	|294912
Unknown6	|UInt32	|311296


**19:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|515200
Unknown4	|UInt32	|543360
Unknown5	|UInt32	|311296
Unknown6	|UInt32	|327680


**20:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|543360
Unknown4	|UInt32	|572544
Unknown5	|UInt32	|327680
Unknown6	|UInt32	|344064


**21:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|22656
Unknown3	|UInt32	|572544
Unknown4	|UInt32	|595200
Unknown5	|UInt32	|344064
Unknown6	|UInt32	|352256


**0:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|384
Unknown2	|UInt32	|35328
Unknown3	|UInt32	|0
Unknown4	|UInt32	|34944
Unknown5	|UInt32	|0
Unknown6	|UInt32	|16384


**1:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29696
Unknown3	|UInt32	|34944
Unknown4	|UInt32	|64640
Unknown5	|UInt32	|16384
Unknown6	|UInt32	|32768


**2:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29696
Unknown3	|UInt32	|64640
Unknown4	|UInt32	|94336
Unknown5	|UInt32	|32768
Unknown6	|UInt32	|49152


**3:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|94336
Unknown4	|UInt32	|121984
Unknown5	|UInt32	|49152
Unknown6	|UInt32	|65536


**4:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|121984
Unknown4	|UInt32	|150144
Unknown5	|UInt32	|65536
Unknown6	|UInt32	|81920


**5:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|150144
Unknown4	|UInt32	|178304
Unknown5	|UInt32	|81920
Unknown6	|UInt32	|98304


**6:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28672
Unknown3	|UInt32	|178304
Unknown4	|UInt32	|206976
Unknown5	|UInt32	|98304
Unknown6	|UInt32	|114688


**7:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|206976
Unknown4	|UInt32	|234624
Unknown5	|UInt32	|114688
Unknown6	|UInt32	|131072


**8:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|234624
Unknown4	|UInt32	|262272
Unknown5	|UInt32	|131072
Unknown6	|UInt32	|147456


**9:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|262272
Unknown4	|UInt32	|289920
Unknown5	|UInt32	|147456
Unknown6	|UInt32	|163840


**10:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|289920
Unknown4	|UInt32	|318080
Unknown5	|UInt32	|163840
Unknown6	|UInt32	|180224


**11:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28672
Unknown3	|UInt32	|318080
Unknown4	|UInt32	|346752
Unknown5	|UInt32	|180224
Unknown6	|UInt32	|196608


**12:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|346752
Unknown4	|UInt32	|375936
Unknown5	|UInt32	|196608
Unknown6	|UInt32	|212992


**13:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|29184
Unknown3	|UInt32	|375936
Unknown4	|UInt32	|405120
Unknown5	|UInt32	|212992
Unknown6	|UInt32	|229376


**14:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|405120
Unknown4	|UInt32	|433280
Unknown5	|UInt32	|229376
Unknown6	|UInt32	|245760


**15:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|27648
Unknown3	|UInt32	|433280
Unknown4	|UInt32	|460928
Unknown5	|UInt32	|245760
Unknown6	|UInt32	|262144


**16:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|28160
Unknown3	|UInt32	|460928
Unknown4	|UInt32	|489088
Unknown5	|UInt32	|262144
Unknown6	|UInt32	|278528


**17:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|31744
Unknown3	|UInt32	|489088
Unknown4	|UInt32	|520832
Unknown5	|UInt32	|278528
Unknown6	|UInt32	|294912


**18:**

Name	| Type	| Value
---	|---	|---	|
Unknown1	|UInt32	|0
Unknown2	|UInt32	|24320
Unknown3	|UInt32	|520832
Unknown4	|UInt32	|545152
Unknown5	|UInt32	|294912
Unknown6	|UInt32	|301056


