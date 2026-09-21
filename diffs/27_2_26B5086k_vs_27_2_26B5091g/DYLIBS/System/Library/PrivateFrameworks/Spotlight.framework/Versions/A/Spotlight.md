## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Versions/A/Spotlight`

```diff

-2465.1.2.0.0
-  __TEXT.__text: 0xe26a8
-  __TEXT.__objc_methlist: 0x5444
-  __TEXT.__const: 0x2620
-  __TEXT.__gcc_except_tab: 0x4160
-  __TEXT.__cstring: 0x6dd1
-  __TEXT.__oslogstring: 0x5bbf
+2465.1.3.0.0
+  __TEXT.__text: 0xe3f3c
+  __TEXT.__objc_methlist: 0x545c
+  __TEXT.__const: 0x2630
+  __TEXT.__gcc_except_tab: 0x417c
+  __TEXT.__cstring: 0x6e01
+  __TEXT.__oslogstring: 0x5d5f
   __TEXT.__ustring: 0x32
-  __TEXT.__swift5_typeref: 0xe5f
-  __TEXT.__swift5_fieldmd: 0x834
-  __TEXT.__constg_swiftt: 0xa2c
-  __TEXT.__swift5_reflstr: 0x7d7
+  __TEXT.__swift5_typeref: 0xe89
+  __TEXT.__swift5_fieldmd: 0x84c
+  __TEXT.__constg_swiftt: 0xa3c
+  __TEXT.__swift5_reflstr: 0x7f7
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_proto: 0x14c
   __TEXT.__swift5_types: 0x9c
   __TEXT.__swift_as_entry: 0xd4
   __TEXT.__swift_as_ret: 0xc0
   __TEXT.__swift_as_cont: 0x168
-  __TEXT.__swift5_capture: 0x680
+  __TEXT.__swift5_capture: 0x6ac
   __TEXT.__swift5_assocty: 0x168
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__unwind_info: 0x3028
+  __TEXT.__unwind_info: 0x3050
   __TEXT.__eh_frame: 0x1ce8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4630
+  __DATA_CONST.__objc_selrefs: 0x4648
   __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0xa18
   __DATA_CONST.__got: 0x15b0
-  __AUTH_CONST.__const: 0x4828
-  __AUTH_CONST.__cfstring: 0x6f40
-  __AUTH_CONST.__objc_const: 0x7d58
+  __AUTH_CONST.__const: 0x4928
+  __AUTH_CONST.__cfstring: 0x6f60
+  __AUTH_CONST.__objc_const: 0x7db0
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x8d0
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1870
-  __AUTH.__objc_data: 0x580
-  __AUTH.__data: 0x60
+  __AUTH_CONST.__auth_got: 0x18b0
+  __AUTH.__objc_data: 0x810
+  __AUTH.__data: 0x88
   __DATA.__objc_ivar: 0x58c
-  __DATA.__data: 0xcd0
-  __DATA.__bss: 0x2550
+  __DATA.__data: 0xc80
+  __DATA.__bss: 0x25f0
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x1a48
-  __DATA_DIRTY.__data: 0x8e8
-  __DATA_DIRTY.__bss: 0xc10
+  __DATA_DIRTY.__objc_data: 0x17f0
+  __DATA_DIRTY.__data: 0x918
+  __DATA_DIRTY.__bss: 0xb80
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3410
-  Symbols:   6755
-  CStrings:  1520
+  Functions: 3431
+  Symbols:   6770
+  CStrings:  1526
 
Symbols:
+ +[SPAppDefaults userDefaults]
+ -[SPAppDefaults reloadFilterPrefs:]
+ GCC_except_table9
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _SSSantizedBundleIDList
+ __PROPERTIES_SPPreferenceManager
+ ___29+[SPAppDefaults userDefaults]_block_invoke
+ ___35-[SPAppDefaults reloadFilterPrefs:]_block_invoke
+ ____tccDisabledBundlesChanged_block_invoke
+ __swift_closure_destructor.218Tm
+ __swift_closure_destructor.273Tm
+ __tccDisabledBundlesChanged
+ _objc_msgSend$federationDisabledBundles
+ _objc_msgSend$isServiceMode
+ _objc_msgSend$reloadFilterPrefs:
+ _objc_msgSend$userDefaults
+ _symbolic SiSg
+ _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 3XPC10XPCSessionC
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 3XPC10XPCSessionC So16os_unfair_lock_sV
+ userDefaults.onceToken
+ userDefaults.userDefaults
- -[SPAppDefaults reloadFilterPrefs]
- GCC_except_table7
- ___34-[SPAppDefaults reloadFilterPrefs]_block_invoke
- __swift_closure_destructor.224Tm
- __swift_closure_destructor.264Tm
- _objc_msgSend$reloadFilterPrefs
CStrings:
+ "[migrateLegacyIfNeeded] Migrating from version %ld"
+ "[migrateLegacyIfNeeded] the ruleset is empty, trying to migrate an older set"
+ "[migrateLegacyIfNeeded] the ruleset isn't empty, keep the newer version"
+ "[qid=%lu][SearchToolFederation] CoreSpotlight federationDisabledBundles: %@"
+ "com.apple.spotlight.tcc.siriAccessChanged"
+ "reloadFromCFPreferences: cache unreadable (mode=%s) after %ld retries — preserving existing set"
+ "reloadFromCFPreferences: cache unreadable (mode=%s, attempt=%ld) — retrying in %fs"
+ "reloadFromCFPreferences: read %ld disabled bundle(s) (mode=%s)"
- "[SPQueryTask] disabledBundleIdentifiers returned nil — preferences may not be loaded"
- "[qid=%lu][SearchToolFederation] CoreSpotlight disabledBundles: %@"
```
