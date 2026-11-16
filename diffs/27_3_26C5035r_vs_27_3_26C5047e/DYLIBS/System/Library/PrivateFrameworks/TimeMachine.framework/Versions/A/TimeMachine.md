## TimeMachine

> `/System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine`

```diff

-2616.0.0.0.0
-  __TEXT.__text: 0xb62ec
-  __TEXT.__objc_methlist: 0x5b00
+2616.3.1.0.0
+  __TEXT.__text: 0xb6b40
+  __TEXT.__objc_methlist: 0x5b10
   __TEXT.__const: 0x3cc6
   __TEXT.__gcc_except_tab: 0x1f88
-  __TEXT.__cstring: 0xcc8d
+  __TEXT.__cstring: 0xcd9d
   __TEXT.__ustring: 0xa4
   __TEXT.__oslogstring: 0xb
   __TEXT.__dlopen_cstrs: 0xb0

   __TEXT.__swift_as_ret: 0x168
   __TEXT.__swift_as_cont: 0x20c
   __TEXT.__swift5_protos: 0x10
-  __TEXT.__unwind_info: 0x3858
+  __TEXT.__unwind_info: 0x3860
   __TEXT.__eh_frame: 0x3594
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3440
+  __DATA_CONST.__objc_selrefs: 0x3450
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x230
   __DATA_CONST.__objc_arraydata: 0xf0
   __DATA_CONST.__got: 0xb10
-  __AUTH_CONST.__const: 0x5c08
-  __AUTH_CONST.__cfstring: 0x8860
+  __AUTH_CONST.__const: 0x5c58
+  __AUTH_CONST.__cfstring: 0x8960
   __AUTH_CONST.__objc_const: 0x8f28
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x258

   __AUTH.__data: 0x1f8
   __DATA.__objc_ivar: 0x4c0
   __DATA.__data: 0x9250
-  __DATA.__bss: 0x3ef0
+  __DATA.__bss: 0x3f00
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0xab0
   __DATA_DIRTY.__data: 0x2d0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3788
-  Symbols:   6000
-  CStrings:  1398
+  Functions: 3792
+  Symbols:   6007
+  CStrings:  1407
 
Symbols:
+ -[NSURL(TMAdditions) tm_FULLFSYNCItemsNamed:error:]
+ GCC_except_table72
+ ___42-[TMDiskImage writeTimeMachineInfo:error:]_block_invoke
+ ___42-[TMDiskImage writeTimeMachineInfo:error:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e15_v32?0816^B24l
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$tm_FULLFSYNCItemsNamed:error:
+ _writeTimeMachineInfo:error:.knownKeys
+ _writeTimeMachineInfo:error:.onceToken
- GCC_except_table44
- _objc_msgSend$tm_fsync:
CStrings:
+ "Dropping unrecognized key '%@' from the Time Machine info for '%@'"
+ "FULLFSYNC failed under '%@', error: %@"
+ "Refusing to use '%@' - it is a symbolic link"
+ "VerificationDate"
+ "VerificationExtendedSkip"
+ "VerificationID"
+ "VerificationSkeletonCaptureDate"
+ "VerificationState"
+ "v32@?0@8@16^B24"
```
