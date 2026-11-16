## sirittsd

> `/System/Library/PrivateFrameworks/SiriTTSService.framework/sirittsd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_capture`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3610.9.1.0.0
-  __TEXT.__text: 0x5db28
-  __TEXT.__auth_stubs: 0x2d80
+3610.14.2.0.0
+  __TEXT.__text: 0x5dfc8
+  __TEXT.__auth_stubs: 0x2dc0
   __TEXT.__objc_stubs: 0xe60
   __TEXT.__objc_methlist: 0x660
   __TEXT.__const: 0x1288
   __TEXT.__swift5_typeref: 0xba2
   __TEXT.__cstring: 0x9e2
-  __TEXT.__oslogstring: 0x27d2
+  __TEXT.__oslogstring: 0x2812
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_capture: 0xb5c
   __TEXT.__objc_methtype: 0xa4d

   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x58
-  __DATA_CONST.__auth_got: 0x16c8
+  __DATA_CONST.__auth_got: 0x16e8
   __DATA_CONST.__got: 0x908
   __DATA_CONST.__auth_ptr: 0x4e0
   __DATA.__objc_const: 0x19b8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 1121
-  Symbols:   1124
-  CStrings:  616
+  Symbols:   1128
+  CStrings:  617
 
Symbols:
+ _$s14SiriTTSService13MobileGestaltV9isHomePodSbvgZ
+ _$s14SiriTTSService24TTSFeatureFlagsContainerC6sharedACvgZ
+ _$s14SiriTTSService24TTSFeatureFlagsContainerCMa
+ _$s14SiriTTSService27SynthesizingRequestProtocolPAAE19containsAudioPromptSbvg
+ _$s14SiriTTSService9PCCClientC14isPCCSupported12featureFlagsSbAA010TTSFeatureG9ContainerC_tFZ
- _$s14SiriTTSService9PCCClientC14isPCCSupportedSbvgZ
Functions:
~ sub_100003398 : 264 -> 288
~ sub_100003bb4 -> sub_100003bcc : 112 -> 124
~ sub_100006984 -> sub_1000069a8 : 120 -> 144
~ sub_10000f524 -> sub_10000f560 : 1988 -> 2004
~ sub_100010b70 -> sub_100010bbc : 836 -> 876
~ sub_100010eb4 -> sub_100010f28 : 776 -> 800
~ sub_100011a00 -> sub_100011a8c : 3820 -> 3848
~ sub_100012a24 -> sub_100012acc : 1544 -> 1820
~ sub_1000152a8 -> sub_100015464 : 3408 -> 3620
~ sub_100015ff8 -> sub_100016288 : 3292 -> 3296
~ sub_100028f6c -> sub_100029200 : 4448 -> 4616
~ sub_10002a0cc -> sub_10002a408 : 4300 -> 4552
~ sub_100038f00 -> sub_100039338 : 1000 -> 996
~ sub_1000392e8 -> sub_10003971c : 828 -> 848
~ sub_10003964c -> sub_100039a94 : 872 -> 876
~ sub_100058894 -> sub_100058ce0 : 260 -> 284
~ sub_100058998 -> sub_100058dfc : 316 -> 352
~ sub_10005a634 -> sub_10005aabc : 3024 -> 3036
~ sub_10005b2cc -> sub_10005b760 : 1140 -> 1152
CStrings:
+ "#PrewarmRequest %llu skipping device engine prewarm since %s is preferred."
+ "PCC voice is not enabled due to audio prompt in text."
+ "PCC voice is not enabled since PCC is not supported on this platform."
- "#PrewarmRequest %llu skipping device engine prewarm since PCC is preferred."
- "PCC voice is not enabled due to disabled SiriTTSService/pcc feature."
```
