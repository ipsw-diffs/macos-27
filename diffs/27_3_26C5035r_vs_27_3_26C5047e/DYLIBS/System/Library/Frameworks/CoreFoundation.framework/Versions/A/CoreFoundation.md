## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation`

```diff

-5027.2.4.0.0
-  __TEXT.__text: 0x202bdc
+5027.2.9.0.0
+  __TEXT.__text: 0x202f28
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x846c
   __TEXT.__const: 0x1a8114
   __TEXT.__oslogstring: 0xb46d
-  __TEXT.__cstring: 0xbbc83
+  __TEXT.__cstring: 0xbbcc3
   __TEXT.__gcc_except_tab: 0x68ac
   __TEXT.__ustring: 0x1446
   __TEXT.__dlopen_cstrs: 0xcc
   __TEXT.__dof_NSAppNap: 0x4cf
   __TEXT.__dof_CFRunLoop: 0x964
   __TEXT.__dof_Cocoa_Aut: 0x486
-  __TEXT.__unwind_info: 0x8b98
+  __TEXT.__unwind_info: 0x8ba0
   __TEXT.__eh_frame: 0x450
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3ac768
+  __DATA_CONST.__const: 0x3ac770
   __DATA_CONST.__objc_classlist: 0x4c0
   __DATA_CONST.__objc_nlclslist: 0x58
   __DATA_CONST.__objc_catlist: 0x18

   __DATA_CONST.__objc_arraydata: 0x1760
   __DATA_CONST.__got: 0x540
   __AUTH_CONST.__const: 0x93c8
-  __AUTH_CONST.__cfstring: 0xd55e0
+  __AUTH_CONST.__cfstring: 0xd5600
   __AUTH_CONST.__objc_const: 0xb208
   __AUTH_CONST.__const_cfobj2: 0x40
   __AUTH_CONST.__objc_dictobj: 0x848
   __AUTH_CONST.__objc_arrayobj: 0x48
-  __AUTH_CONST.__auth_got: 0x19e8
+  __AUTH_CONST.__auth_got: 0x19f0
   __AUTH.__objc_data: 0xcd0
   __AUTH.__data: 0x120
   __DATA.__objc_ivar: 0x670

   __DATA.__cf_except_bt: 0x2000
   __DATA.__cf_except_pack: 0x410
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1050
+  __DATA.__bss: 0x1060
   __DATA.__common: 0xc0
   __DATA_DIRTY.__objc_data: 0x22b0
   __DATA_DIRTY.__data: 0x198

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/liboah.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9464
-  Symbols:   14164
-  CStrings:  31443
+  Functions: 9465
+  Symbols:   14167
+  CStrings:  31445
 
Symbols:
+ ___CFStackBufferHandleOutOfMemory
+ ___CFUserNotificationMachPortLock
+ _os_unfair_recursive_lock_lock
Functions:
~ ___writeObject15 : 3220 -> 3340
~ ___NSMakeSpecialForwardingCaptureBlock : 300 -> 292
~ _CFPlugInInstanceCreate : 1032 -> 1028
~ ____InitializeDiskArbitrationKeys_block_invoke : 140 -> 148
~ _findCFBurstTrieMappedLevel : 360 -> 332
~ _findCFBurstTrieCompactMappedLevel : 456 -> 504
~ _findCFBurstTrieMappedPage : 608 -> 708
~ ___CFUserNotificationDeallocate : 132 -> 156
~ __CFUserNotificationMachPortCallBack : 204 -> 316
~ _traverseCFBurstTrieMappedLevel : 408 -> 464
~ _traverseCFBurstTrieCompactMappedLevel : 444 -> 572
~ -[CFPDSource acceptMessage:populatingReply:] : 3736 -> 3828
~ _OUTLINED_FUNCTION_6 : 24 -> 20
+ ___CFStackBufferHandleOutOfMemory
~ -[CFPDSource openActualPath] : 308 -> 408
~ -[CFPDSource shouldStayDirtyAfterOpenForWritingFailureWithErrno:] : 220 -> 224
~ -[CFPDSource cleanUpIfNecessaryAfterCreatingPlist] : 348 -> 356
~ -[CFPDSource cacheFileInfoForWriting:euid:egid:didCreate:].cold.6 : 92 -> 96
~ -[CFPDSource cleanUpAfterAcceptingMessage:].cold.1 : 128 -> 120
CStrings:
+ "/usr/libexec/secd"
+ "Attempt to temporarily allocate memory failed"
```
