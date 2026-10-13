## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/Versions/A/TextToSpeech`

```diff

-727.3.2.0.0
-  __TEXT.__text: 0x32b018
+727.3.3.0.0
+  __TEXT.__text: 0x3313f8
   __TEXT.__objc_methlist: 0x4550
-  __TEXT.__const: 0x3f391
+  __TEXT.__const: 0x3f511
   __TEXT.__dlopen_cstrs: 0x2af
-  __TEXT.__constg_swiftt: 0x8208
-  __TEXT.__swift5_typeref: 0x7912
-  __TEXT.__swift5_fieldmd: 0x6250
-  __TEXT.__cstring: 0x8cd1
-  __TEXT.__swift5_types: 0x7a4
-  __TEXT.__swift5_capture: 0x31d0
-  __TEXT.__swift5_reflstr: 0x4cf0
+  __TEXT.__constg_swiftt: 0x83b4
+  __TEXT.__swift5_typeref: 0x793a
+  __TEXT.__swift5_fieldmd: 0x637c
+  __TEXT.__cstring: 0x8ce1
+  __TEXT.__swift5_types: 0x7b0
+  __TEXT.__swift5_capture: 0x31d4
+  __TEXT.__swift5_reflstr: 0x4e70
   __TEXT.__swift5_assocty: 0x1600
-  __TEXT.__swift5_proto: 0x1320
+  __TEXT.__swift5_proto: 0x132c
   __TEXT.__swift_as_entry: 0xc88
   __TEXT.__swift_as_ret: 0xdb0
   __TEXT.__swift_as_cont: 0x1234
   __TEXT.__swift5_builtin: 0x474
-  __TEXT.__oslogstring: 0x2fa0
+  __TEXT.__oslogstring: 0x3230
   __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_mpenum: 0x144
   __TEXT.__gcc_except_tab: 0x2ba8
   __TEXT.__ustring: 0x2c6
-  __TEXT.__unwind_info: 0xf150
-  __TEXT.__eh_frame: 0x17148
+  __TEXT.__unwind_info: 0xf1c8
+  __TEXT.__eh_frame: 0x17270
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1340
-  __DATA_CONST.__objc_classlist: 0x3d0
+  __DATA_CONST.__objc_classlist: 0x3d8
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_superrefs: 0x108
   __DATA_CONST.__objc_arraydata: 0x1398
   __DATA_CONST.__got: 0xdb8
-  __AUTH_CONST.__const: 0x17f38
+  __AUTH_CONST.__const: 0x18158
   __AUTH_CONST.__cfstring: 0x6340
-  __AUTH_CONST.__objc_const: 0xbca0
+  __AUTH_CONST.__objc_const: 0xbef8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_arrayobj: 0xee8
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_floatobj: 0x40
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x2968
-  __AUTH.__objc_data: 0x2410
-  __AUTH.__data: 0x2810
+  __AUTH_CONST.__auth_got: 0x2998
+  __AUTH.__objc_data: 0x2590
+  __AUTH.__data: 0x28d0
   __DATA.__objc_ivar: 0x428
-  __DATA.__data: 0x2ff8
-  __DATA.__bss: 0x1e800
-  __DATA.__common: 0x228
+  __DATA.__data: 0x3000
+  __DATA.__bss: 0x1e9c0
+  __DATA.__common: 0x238
   __DATA_DIRTY.__objc_data: 0x12b8
   __DATA_DIRTY.__data: 0x3a20
   __DATA_DIRTY.__bss: 0x89c0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 16109
-  Symbols:   1356
-  CStrings:  1733
+  Functions: 16150
+  Symbols:   1358
+  CStrings:  1744
 
Symbols:
+ _AudioObjectHasProperty
+ _uscript_getScript
CStrings:
+ "(?<![\\d(])\\+?\\(?\\d{1,4}\\)?(?:[-. ]?\\(?\\d{1,5}\\)?){0,5}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?(?!\\d)"
+ "AudioQueue session timings (%{public}s): ioBufferDuration=%.*fms (requested %.*fms), outputLatency=%.*fms, wirelessTransport=%{bool}d, headroom=%.*fms, bufferDuration=%.*fms, buffersPerIOCycle=%.*f, stagedTarget=%ld, ioCycleFloor=%.*fms, effectivePriming=%.*fms, effectiveMaxBuffered=%.*fms"
+ "Failed to enqueue silence buffer: %d"
+ "PRAGMA journal_mode=TRUNCATE"
+ "Ranged event spans elements with distinct source text; dropped %ld range(s) from consolidation"
+ "Regex cache left in journal mode '%{public}s'; discarding the database file"
+ "Stop wind-down: hardwareDepth=%ld, repaying %ld of %ld deferred enqueue(s) with silence"
+ "Top-up enqueue failed"
+ "com.apple.Accessibility.TextToSpeech.AudioQueueSessionConfig"
+ "priming"
+ "queue build"
+ "queue start"
+ "test"
- "(?:\\(\\d{3}\\)\\s?|\\d{3}[-. ])\\d{3}[-. ]?\\d{4}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{10}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{3}[-. ]\\d{4}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{7}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?"
- "PRAGMA journal_mode=WAL"
```
