## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/Versions/A/LocalSpeechRecognitionBridge`

```diff

-3605.31.3.0.0
-  __TEXT.__text: 0x1f3e4
-  __TEXT.__objc_methlist: 0x2524
+3605.32.1.14.1
+  __TEXT.__text: 0x1f9c0
+  __TEXT.__objc_methlist: 0x25a4
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__const: 0xb0
   __TEXT.__gcc_except_tab: 0x230
-  __TEXT.__cstring: 0x4bc0
-  __TEXT.__oslogstring: 0x2d3e
-  __TEXT.__unwind_info: 0x960
+  __TEXT.__cstring: 0x4d13
+  __TEXT.__oslogstring: 0x2eb9
+  __TEXT.__unwind_info: 0x968
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0xb8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1368
+  __DATA_CONST.__objc_selrefs: 0x13b0
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0xc8
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x1e8
   __AUTH_CONST.__const: 0x810
-  __AUTH_CONST.__cfstring: 0x1b80
-  __AUTH_CONST.__objc_const: 0x3d88
+  __AUTH_CONST.__cfstring: 0x1bc0
+  __AUTH_CONST.__objc_const: 0x3e28
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x4b0
-  __DATA.__objc_ivar: 0x2d0
+  __DATA.__objc_ivar: 0x2dc
   __DATA.__data: 0x8b0
   __DATA_DIRTY.__objc_data: 0x410
   __DATA_DIRTY.__bss: 0x58

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 777
-  Symbols:   1890
-  CStrings:  619
+  Functions: 786
+  Symbols:   1904
+  CStrings:  628
 
Symbols:
+ -[LBAudioStreamProvider _anchorHostTimeForPacketIndex:inHostTimes:baseIndex:]
+ -[LBAudioStreamProvider _forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]
+ -[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]
+ -[LBAudioStreamProvider previousPacketHostTimesBaseIndex]
+ -[LBAudioStreamProvider previousPacketHostTimes]
+ -[LBAudioStreamProvider previousStreamId]
+ -[LBAudioStreamProvider setPreviousPacketHostTimes:]
+ -[LBAudioStreamProvider setPreviousPacketHostTimesBaseIndex:]
+ -[LBAudioStreamProvider setPreviousStreamId:]
+ GCC_except_table338
+ GCC_except_table355
+ GCC_except_table480
+ GCC_except_table493
+ GCC_except_table503
+ GCC_except_table587
+ GCC_except_table709
+ GCC_except_table744
+ GCC_except_table749
+ GCC_except_table754
+ OBJC_IVAR_$_LBAudioStreamProvider._previousPacketHostTimes
+ OBJC_IVAR_$_LBAudioStreamProvider._previousPacketHostTimesBaseIndex
+ OBJC_IVAR_$_LBAudioStreamProvider._previousStreamId
+ ___94-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]_block_invoke
+ _objc_msgSend$_anchorHostTimeForPacketIndex:inHostTimes:baseIndex:
+ _objc_msgSend$_forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:
+ _objc_msgSend$forwardUserSpeakingEndAtHostTime:forStreamId:
+ _objc_msgSend$isEqual:
- -[LBAudioStreamProvider _anchorHostTimeForPacketIndex:]
- GCC_except_table332
- GCC_except_table346
- GCC_except_table471
- GCC_except_table475
- GCC_except_table494
- GCC_except_table578
- GCC_except_table700
- GCC_except_table735
- GCC_except_table740
- GCC_except_table745
- _objc_msgSend$_anchorHostTimeForPacketIndex:
- _objc_msgSend$forwardUserSpeakingEndAtHostTime:
CStrings:
+ "%s #stream LBAudioStreamProvider DROP legacy USE, no live stream to attribute it to"
+ "%s #stream LBAudioStreamProvider DROP nil streamId"
+ "%s #stream LBAudioStreamProvider DROP no packet hostTimes tracked for streamId=%@ (stream may not have produced packets yet)"
+ "%s #stream LBAudioStreamProvider DROP unknown streamId=%@ (current=%@, previous=%@)"
+ "%s #stream LBAudioStreamProvider ENTRY (legacy, no streamId) secondsFromEnd=%f lastPacketIndex=%llu"
+ "%s #stream LBAudioStreamProvider ENTRY secondsFromEnd=%f lastPacketIndex=%llu streamId=%@"
+ "%s #stream LBAudioStreamProvider XPC SEND useHostTime=%llu (anchorHostTime=%llu, secondsFromEnd=%f, streamId=%@, stream=%{public}@)"
+ "-[LBAudioStreamProvider _anchorHostTimeForPacketIndex:inHostTimes:baseIndex:]"
+ "-[LBAudioStreamProvider _forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]"
+ "-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]"
+ "-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]_block_invoke"
+ "current"
+ "previous"
- "%s #stream LBAudioStreamProvider DROP no packet hostTimes tracked (stream may not have produced packets yet)"
- "%s #stream LBAudioStreamProvider ENTRY secondsFromEnd=%f lastPacketIndex=%llu"
- "%s #stream LBAudioStreamProvider XPC SEND useHostTime=%llu (anchorHostTime=%llu, secondsFromEnd=%f)"
- "-[LBAudioStreamProvider _anchorHostTimeForPacketIndex:]"
```
