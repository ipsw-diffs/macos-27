## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Versions/A/Transparency`

```diff

-1766.40.56.0.0
-  __TEXT.__text: 0x82108
-  __TEXT.__objc_methlist: 0x4ad0
-  __TEXT.__cstring: 0x315c
-  __TEXT.__const: 0x4ed0
-  __TEXT.__gcc_except_tab: 0x4fc
-  __TEXT.__oslogstring: 0x20db
+1766.40.58.0.0
+  __TEXT.__text: 0x82a38
+  __TEXT.__objc_methlist: 0x4b70
+  __TEXT.__cstring: 0x318c
+  __TEXT.__const: 0x4ee0
+  __TEXT.__gcc_except_tab: 0x528
+  __TEXT.__oslogstring: 0x229b
   __TEXT.__swift5_typeref: 0x10e4
   __TEXT.__swift5_reflstr: 0x9ca
   __TEXT.__swift5_assocty: 0x260

   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_acfuncs: 0x1b8
   __TEXT.__swift5_capture: 0x2c4
-  __TEXT.__unwind_info: 0x3450
+  __TEXT.__unwind_info: 0x3490
   __TEXT.__eh_frame: 0x38e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2058
+  __DATA_CONST.__objc_selrefs: 0x20b8
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x180
-  __DATA_CONST.__got: 0x660
-  __AUTH_CONST.__const: 0x50c8
-  __AUTH_CONST.__cfstring: 0x3ac0
-  __AUTH_CONST.__objc_const: 0x8050
+  __DATA_CONST.__got: 0x668
+  __AUTH_CONST.__const: 0x5228
+  __AUTH_CONST.__cfstring: 0x3ae0
+  __AUTH_CONST.__objc_const: 0x8140
   __AUTH_CONST.__objc_intobj: 0x1e0
-  __AUTH_CONST.__auth_got: 0xb60
+  __AUTH_CONST.__auth_got: 0xb78
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0x3b4
+  __DATA.__objc_ivar: 0x3c8
   __DATA.__data: 0x928
   __DATA.__bss: 0x6d10
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x1dd0
   __DATA_DIRTY.__data: 0xf20
-  __DATA_DIRTY.__bss: 0x11e0
+  __DATA_DIRTY.__bss: 0x11f0
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3930
-  Symbols:   4516
-  CStrings:  788
+  Functions: 3961
+  Symbols:   4562
+  CStrings:  797
 
Symbols:
+ +[TransparencyXPCConnection nowNs]
+ -[TransparencyXPCConnection dropConnectionForGeneration:]
+ -[TransparencyXPCConnection firstSuppressedNs]
+ -[TransparencyXPCConnection flushSuppressedPeerExits:]
+ -[TransparencyXPCConnection generation]
+ -[TransparencyXPCConnection lastPeerExitLogNs]
+ -[TransparencyXPCConnection lastSuppressedNs]
+ -[TransparencyXPCConnection logPeerExit:]
+ -[TransparencyXPCConnection setFirstSuppressedNs:]
+ -[TransparencyXPCConnection setGeneration:]
+ -[TransparencyXPCConnection setLastPeerExitLogNs:]
+ -[TransparencyXPCConnection setLastSuppressedNs:]
+ -[TransparencyXPCConnection setSuppressedPeerExits:]
+ -[TransparencyXPCConnection suppressedPeerExits]
+ GCC_except_table12
+ GCC_except_table25
+ GCC_except_table36
+ GCC_except_table9
+ OBJC_IVAR_$_TransparencyXPCConnection._firstSuppressedNs
+ OBJC_IVAR_$_TransparencyXPCConnection._generation
+ OBJC_IVAR_$_TransparencyXPCConnection._lastPeerExitLogNs
+ OBJC_IVAR_$_TransparencyXPCConnection._lastSuppressedNs
+ OBJC_IVAR_$_TransparencyXPCConnection._suppressedPeerExits
+ _NSDebugDescriptionErrorKey
+ __41-[TransparencyXPCConnection logPeerExit:]_block_invoke
+ __51-[SoftwareTransparency sysdiagnoseInfo:completion:]_block_invoke
+ __54-[TransparencyXPCConnection flushSuppressedPeerExits:]_block_invoke
+ __88-[SoftwareTransparency verifyExpiringProofs:forDigest:configuration:counter:completion:]_block_invoke
+ ___41-[TransparencyXPCConnection logPeerExit:]_block_invoke
+ ___51-[SoftwareTransparency sysdiagnoseInfo:completion:]_block_invoke_2
+ ___54-[TransparencyXPCConnection flushSuppressedPeerExits:]_block_invoke
+ ___88-[SoftwareTransparency verifyExpiringProofs:forDigest:configuration:counter:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e5_v8?0l
+ ___block_descriptor_56_e8_32s40w_e5_v8?0l
+ ___copy_helper_block_e8_32s40w
+ ___destroy_helper_block_e8_32s40w
+ _clock_gettime_nsec_np
+ _dispatch_after
+ _dispatch_time
+ _objc_msgSend$dropConnectionForGeneration:
+ _objc_msgSend$firstSuppressedNs
+ _objc_msgSend$flushSuppressedPeerExits:
+ _objc_msgSend$generation
+ _objc_msgSend$lastPeerExitLogNs
+ _objc_msgSend$lastSuppressedNs
+ _objc_msgSend$logPeerExit:
+ _objc_msgSend$nowNs
+ _objc_msgSend$setFirstSuppressedNs:
+ _objc_msgSend$setGeneration:
+ _objc_msgSend$setLastPeerExitLogNs:
+ _objc_msgSend$setLastSuppressedNs:
+ _objc_msgSend$setSuppressedPeerExits:
+ _objc_msgSend$suppressedPeerExits
- -[SoftwareTransparency verifyExpiringProofs:for:counter:completion:]
- GCC_except_table29
- GCC_except_table3
- GCC_except_table8
- __45-[TransparencyXPCConnection createConnection]_block_invoke_2
- ___68-[SoftwareTransparency verifyExpiringProofs:for:counter:completion:]_block_invoke
- _objc_msgSend$initWithDomain:code:userInfo:
CStrings:
+ "swtransparencyd did not answer after %d attempts"
+ "sysdiagnoseInfo attempt %d hit %{public}@ %ld, retrying"
+ "sysdiagnoseInfo failed on attempt %d: %{public}@"
+ "sysdiagnoseInfo giving up after %d attempts"
+ "verifyExpiringProofs attempt %d hit %{public}@ %ld, retrying"
+ "verifyExpiringProofs failed on attempt %d: %{public}@"
+ "verifyExpiringProofs giving up after %d attempts"
+ "xpc connection invalidated, it will not reconnect: %{public}@"
+ "xpc peer exited, next call reopens: %{public}@"
+ "xpc peer exited: %{public}@ (%lu more suppressed at once)"
+ "xpc peer exited: %{public}@ (%lu more suppressed over %llums)"
- "server connection exited or crashed: %@"
- "xpc connection cannot be formed or has been terminated: %@"
```
