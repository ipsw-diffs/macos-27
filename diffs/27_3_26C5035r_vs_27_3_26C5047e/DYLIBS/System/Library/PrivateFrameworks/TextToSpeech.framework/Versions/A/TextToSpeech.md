## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/Versions/A/TextToSpeech`

```diff

-727.3.12.0.0
-  __TEXT.__text: 0x332cf0
-  __TEXT.__objc_methlist: 0x4550
-  __TEXT.__const: 0x3f531
+727.3.22.0.0
+  __TEXT.__text: 0x348660
+  __TEXT.__objc_methlist: 0x4588
+  __TEXT.__const: 0x3f971
   __TEXT.__dlopen_cstrs: 0x2af
-  __TEXT.__constg_swiftt: 0x83b4
-  __TEXT.__swift5_typeref: 0x795c
-  __TEXT.__swift5_fieldmd: 0x637c
-  __TEXT.__cstring: 0x8d21
-  __TEXT.__swift5_types: 0x7b0
-  __TEXT.__swift5_capture: 0x31d4
-  __TEXT.__swift5_reflstr: 0x4e70
-  __TEXT.__swift5_assocty: 0x1600
-  __TEXT.__swift5_proto: 0x132c
-  __TEXT.__swift_as_entry: 0xc88
-  __TEXT.__swift_as_ret: 0xdb0
-  __TEXT.__swift_as_cont: 0x1234
+  __TEXT.__constg_swiftt: 0x8694
+  __TEXT.__swift5_typeref: 0x7b22
+  __TEXT.__swift5_fieldmd: 0x65b0
+  __TEXT.__cstring: 0x8ea1
+  __TEXT.__swift5_types: 0x7d4
+  __TEXT.__swift5_capture: 0x32c8
+  __TEXT.__swift5_reflstr: 0x51a0
+  __TEXT.__swift5_assocty: 0x1660
+  __TEXT.__swift5_proto: 0x1344
+  __TEXT.__swift_as_entry: 0xc9c
+  __TEXT.__swift_as_ret: 0xdc0
+  __TEXT.__swift_as_cont: 0x1258
   __TEXT.__swift5_builtin: 0x474
-  __TEXT.__oslogstring: 0x3230
+  __TEXT.__oslogstring: 0x3550
   __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_mpenum: 0x144
   __TEXT.__gcc_except_tab: 0x2ba8
   __TEXT.__ustring: 0x2c6
-  __TEXT.__unwind_info: 0xf200
-  __TEXT.__eh_frame: 0x17358
+  __TEXT.__unwind_info: 0xf4d0
+  __TEXT.__eh_frame: 0x17908
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1340
+  __DATA_CONST.__const: 0x1350
   __DATA_CONST.__objc_classlist: 0x3d8
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x2e20
+  __DATA_CONST.__objc_selrefs: 0x2e48
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x108
   __DATA_CONST.__objc_arraydata: 0x1398
-  __DATA_CONST.__got: 0xdc8
-  __AUTH_CONST.__const: 0x18168
+  __DATA_CONST.__got: 0xe78
+  __AUTH_CONST.__const: 0x18988
   __AUTH_CONST.__cfstring: 0x6340
-  __AUTH_CONST.__objc_const: 0xbef8
+  __AUTH_CONST.__objc_const: 0xc170
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_arrayobj: 0xee8
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_floatobj: 0x40
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x29b8
-  __AUTH.__objc_data: 0x2590
-  __AUTH.__data: 0x28d0
+  __AUTH_CONST.__auth_got: 0x2ae0
+  __AUTH.__objc_data: 0x27c8
+  __AUTH.__data: 0x28e0
   __DATA.__objc_ivar: 0x428
-  __DATA.__data: 0x3040
-  __DATA.__bss: 0x1e9c0
-  __DATA.__common: 0x238
-  __DATA_DIRTY.__objc_data: 0x12b8
+  __DATA.__data: 0x30d8
+  __DATA.__bss: 0x1ee10
+  __DATA.__common: 0x2a8
+  __DATA_DIRTY.__objc_data: 0x12e0
   __DATA_DIRTY.__data: 0x3a20
   __DATA_DIRTY.__bss: 0x89c0
   __DATA_DIRTY.__common: 0x2f0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 16159
-  Symbols:   1358
-  CStrings:  1746
+  Functions: 16342
+  Symbols:   1359
+  CStrings:  1765
 
Symbols:
+ _AudioQueueEnqueueBufferWithParameters
+ _dladdr
- _AudioQueueEnqueueBuffer
CStrings:
+ "(?<![\\p{L}\\p{N}])\\((US\\$|CA\\$|A\\$|HK\\$|NZ\\$|S\\$|NT\\$|R\\$|Mex\\$|JP¥|[$€£¥₹₩₽₺₪₫฿₦₨₴₡₱])\\s?((?:\\d{1,3}(?:[,. \u202f ]\\d{3})+|\\d+)(?:[.,]\\d+)?|\\.\\d+)\\)(?![\\p{L}\\p{N}])"
+ "Audio unit did not report end of request %{public}s within %{public}s; trailing markers may be dropped"
+ "AudioQueue %{public}s again within %.*fs of the last recycle (late by %.*fms); not recycling"
+ "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, deadlineMisses=%ld, genSkips=%ld, lateEnqueues=%ld maxLate=%.*fms staleRecycles=%ld hintRecycles=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld, ioCycle=%.*fms bufDur=%.*fms buffersPerIOCycle=%.*f"
+ "AudioQueue dispose: %.*fms"
+ "AudioQueue recycling (%{public}s): late by %.*fms, state=%{public}s, keeping %ld record(s) (%.*fms), cachedIOCycle=%.*fms"
+ "AudioQueue start: prime=%.*fms status=%d frames=%u/%u, start=%.*fms status=%d, ioBufferDuration=%.*fms, cancelled=%{bool}d"
+ "AudioQueue stop (%{public}s): %.*fms status=%d, ioBufferDuration=%.*fms"
+ "AudioQueueStop failed: %d; invalidating"
+ "CoreSynthesizerAudio"
+ "Failed to %{public}s audio queue (prime=%d, start=%d); invalidating"
+ "Instantiated audio unit for %{public}s, inProcess: %{bool}d"
+ "Not starting cancelled utterance with id %s"
+ "Stopping audio queue (%{public}s)"
+ "US\\$|CA\\$|A\\$|HK\\$|NZ\\$|S\\$|NT\\$|R\\$|Mex\\$|JP¥|[$€£¥₹₩₽₺₪₫฿₦₨₴₡₱]"
+ "UnspeakableCharacters"
+ "XCTestConfigurationFilePath"
+ "com.apple.Accessibility.TextToSpeech.AudioQueueControl"
+ "com.apple.TextToSpeech.diagnostics"
+ "com.apple.TextToSpeech.endOfRequest"
+ "loadedFromSharedCache"
+ "secondary audio hint"
+ "stale timeline"
+ "stop timeout"
+ "textToSpeechPath"
- "(?<![\\p{L}\\p{N}])\\((US\\$|CA\\$|A\\$|HK\\$|NZ\\$|S\\$|NT\\$|R\\$|Mex\\$|[$€£¥₹₩₽₺₪₫฿₦₨₴₡₱])\\s?((?:\\d{1,3}(?:[,. \u202f ]\\d{3})+|\\d+)(?:[.,]\\d+)?|\\.\\d+)\\)(?![\\p{L}\\p{N}])"
- "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, deadlineMisses=%ld, genSkips=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld, ioCycle=%.*fms bufDur=%.*fms buffersPerIOCycle=%.*f"
- "Failed to prime audio queue: %d"
- "Failed to start audio queue: %d"
- "Stop timeout reached, stopping queue"
- "US\\$|CA\\$|A\\$|HK\\$|NZ\\$|S\\$|NT\\$|R\\$|Mex\\$|[$€£¥₹₩₽₺₪₫฿₦₨₴₡₱]"
```
