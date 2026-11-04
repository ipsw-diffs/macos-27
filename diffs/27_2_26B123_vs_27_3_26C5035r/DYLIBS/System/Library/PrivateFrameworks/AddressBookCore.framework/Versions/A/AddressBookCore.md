## AddressBookCore

> `/System/Library/PrivateFrameworks/AddressBookCore.framework/Versions/A/AddressBookCore`

```diff

-2768.200.91.0.0
-  __TEXT.__text: 0xe22fc
-  __TEXT.__objc_methlist: 0x12bf4
+2768.300.31.0.0
+  __TEXT.__text: 0xe2804
+  __TEXT.__objc_methlist: 0x12c24
   __TEXT.__const: 0x1e4
   __TEXT.__cstring: 0xcd74
-  __TEXT.__gcc_except_tab: 0x4010
-  __TEXT.__oslogstring: 0x5dd4
+  __TEXT.__gcc_except_tab: 0x4000
+  __TEXT.__oslogstring: 0x5e72
   __TEXT.__dlopen_cstrs: 0x239
-  __TEXT.__unwind_info: 0x6d40
+  __TEXT.__unwind_info: 0x6d60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x1f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9320
+  __DATA_CONST.__objc_selrefs: 0x9348
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x698
   __DATA_CONST.__objc_arraydata: 0x148
   __DATA_CONST.__got: 0x1828
   __AUTH_CONST.__const: 0x5c10
   __AUTH_CONST.__cfstring: 0xe400
-  __AUTH_CONST.__objc_const: 0x1a008
+  __AUTH_CONST.__objc_const: 0x1a028
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x868
   __AUTH.__objc_data: 0x59b0
   __AUTH.__data: 0x20
-  __DATA.__objc_ivar: 0xb88
+  __DATA.__objc_ivar: 0xb8c
   __DATA.__data: 0x1b00
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xc78

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7344
-  Symbols:   16726
-  CStrings:  2623
+  Functions: 7352
+  Symbols:   16737
+  CStrings:  2624
 
Symbols:
+ -[ABPersistentStoreCoordinatorCache cachedAccountStackDidChange:]
+ -[ABPersistentStoreCoordinatorCache cachedStackForCurrentUser]
+ -[ABPersistentStoreCoordinatorCache refreshPersistentStoresFromCachedAccountStackDescription]
+ -[ABPersistentStoreCoordinatorCache shouldSkipEmptyCachedAccountStack:]
+ _OBJC_IVAR_$_ABPersistentStoreCoordinatorCache._isObserving
+ ___65-[ABPersistentStoreCoordinatorCache cachedAccountStackDidChange:]_block_invoke
+ ___65-[ABPersistentStoreCoordinatorCache cachedAccountStackDidChange:]_block_invoke_2
+ _objc_msgSend$accountsDidChangeNotificationName
+ _objc_msgSend$cachedStackForCurrentUser
+ _objc_msgSend$refreshPersistentStoresFromCachedAccountStackDescription
+ _objc_msgSend$shouldSkipEmptyCachedAccountStack:
CStrings:
+ "%p: Ignoring cached account stack that's unexpectedly empty while %lu persistent account(s) exist; keeping existing persistent stores attached"
+ "Exception while replacing account with identifier %{public}@ (config changed): %{public}@"
+ "replacing account in ABAccountRepository and forwarding ABDistributedAccountConfigurationDidChangeNotification: %{public}@ in-process as ABAccountConfigurationDidChangeNotification"
- "Exception while invalidating accounts (configs changed): %{public}@"
- "invalidating all sources in ABAccountRepository and forwarding ABDistributedAccountConfigurationDidChangeNotification: %{public}@ in-process as ABAccountConfigurationDidChangeNotification"
```
