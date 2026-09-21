## AudioCodecs

> `/System/Library/Components/AudioCodecs.component/Contents/MacOS/AudioCodecs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-818.203.0.0.0
-  __TEXT.__text: 0x61a728
+818.204.1.0.0
+  __TEXT.__text: 0x61a93c
   __TEXT.__realtime: 0x3b4
   __TEXT.__auth_stubs: 0x1910
   __TEXT.__const: 0x334b98
-  __TEXT.__cstring: 0xc7da
+  __TEXT.__cstring: 0xc7e2
   __TEXT.__gcc_except_tab: 0x134c8
-  __TEXT.__oslogstring: 0x1bb7b
+  __TEXT.__oslogstring: 0x1bc3c
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0xb1a8
   __TEXT.__eh_frame: 0x6a8

   - /usr/lib/libc++.1.dylib
   Functions: 9878
   Symbols:   17833
-  CStrings:  3532
+  CStrings:  3536
 
Functions:
~ __ZN17ACDDPAtmosDecoder35SoundCheckDictionaryPropertyHandlerEPK14__CFDictionary : 324 -> 348
~ __ZN6mpddrc15UniDrcSelection18getSignalPeakLevelERKNS_12UniDrcHeaderEjjhjPfPb : 1768 -> 1916
~ __ZN6mpddrc15UniDrcSelection19selectDownmixMatrixERKNS_12UniDrcHeaderE : 532 -> 768
~ __ZN6mpddrc15UniDrcSelection7ProcessERKNS_15UniDrcInterfaceERKNS_12UniDrcHeaderENS_12UniDrcDomainEPNS_19UniDrcSelProcOutputE : 15252 -> 15416
~ __ZN12ACLC3Decoder15AppendInputDataEPKvRjS2_PK28AudioStreamPacketDescription : 192 -> 204
~ _ddp_udc_int_dlb_bitbuf_read : 420 -> 332
~ _ddp_udc_int_dlb_bitbuf_read_long : 524 -> 452
~ _ddp_udc_int_exmd_unpblkaht : 2588 -> 2544
~ _ddp_udc_int_exmd_skipahtmants : 792 -> 772
~ _ddp_udc_int_jocd_process_one_frame : 29784 -> 29888
~ __ZL29aacDecoder_SignalInterruptionP20AAC_DECODER_INSTANCE : 264 -> 288
~ __ZN7lpd_dec10lpdDecoder4ReadER16TBitstreamReaderIjEiPfbP8ArithDecjb : 6836 -> 6868
~ __ZNSt3__116allocator_traitsINS_9allocatorIN7lpd_dec10lpdDecoderEEEE9constructB9nqe220106IS3_JELi0EEEvRS4_PT_DpOT0_ : 472 -> 476
~ __Z23CAacDecoder_DecodeFrameP20AAC_DECODER_INSTANCEjPfii : 20100 -> 20108
CStrings:
+ "%25s:%-5d ERROR: desired effect type count (%d) exceeds request list size (%d)\n"
+ "%25s:%-5d ERROR: downmix coefficient count mismatch\n"
+ "%25s:%-5d ERROR: invalid downmix matrix dimensions %d x %d\n"
+ "23:09:02"
+ "LoudnessManagerV3"
+ "Sep 11 2026"
- "01:36:42"
- "Sep  1 2026"
```
