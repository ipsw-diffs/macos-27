## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/Versions/A/iCloudQuota`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-301.24.1.3.0
-  __TEXT.__text: 0x75bbc
-  __TEXT.__objc_methlist: 0x535c
+301.24.1.4.0
+  __TEXT.__text: 0x75f0c
+  __TEXT.__objc_methlist: 0x5394
   __TEXT.__const: 0x1370
   __TEXT.__cstring: 0x4d81
-  __TEXT.__gcc_except_tab: 0x560
+  __TEXT.__gcc_except_tab: 0x578
   __TEXT.__oslogstring: 0x77be
-  __TEXT.__dlopen_cstrs: 0x2f9
+  __TEXT.__dlopen_cstrs: 0x35b
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0x7f8
   __TEXT.__swift5_capture: 0x39c

   __TEXT.__swift_as_cont: 0xe0
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_protos: 0x1c
-  __TEXT.__unwind_info: 0x24a8
+  __TEXT.__unwind_info: 0x24c0
   __TEXT.__eh_frame: 0x1500
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xa08
-  __DATA_CONST.__objc_classlist: 0x350
+  __DATA_CONST.__const: 0xa20
+  __DATA_CONST.__objc_classlist: 0x358
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x48
+  __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x2c50
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x260
+  __DATA_CONST.__objc_superrefs: 0x268
   __DATA_CONST.__objc_arraydata: 0x728
   __DATA_CONST.__got: 0x720
   __AUTH_CONST.__const: 0x2660
   __AUTH_CONST.__cfstring: 0x6160
-  __AUTH_CONST.__objc_const: 0xa380
+  __AUTH_CONST.__objc_const: 0xa790
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x948
   __AUTH_CONST.__auth_got: 0xa90
-  __AUTH.__objc_data: 0x13f8
+  __AUTH.__objc_data: 0x1448
   __AUTH.__data: 0x5f0
-  __DATA.__objc_ivar: 0x634
-  __DATA.__data: 0x540
+  __DATA.__objc_ivar: 0x638
+  __DATA.__data: 0x5a0
   __DATA.__bss: 0x1150
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0xf40
   __DATA_DIRTY.__data: 0x278
-  __DATA_DIRTY.__bss: 0x240
+  __DATA_DIRTY.__bss: 0x250
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2918
-  Symbols:   5120
+  Functions: 2923
+  Symbols:   5136
   CStrings:  1512
 
Symbols:
+ -[ICQNotifyDeleteReporter .cxx_destruct]
+ -[ICQNotifyDeleteReporter initWithAccount:]
+ -[ICQNotifyDeleteReporter reportDeleteWithSuccess:bundleId:completion:]
+ OBJC_IVAR_$_ICQNotifyDeleteReporter._account
+ _OBJC_CLASS_$_ICQNotifyDeleteReporter
+ _OBJC_METACLASS_$_ICQNotifyDeleteReporter
+ __71-[ICQNotifyDeleteReporter reportDeleteWithSuccess:bundleId:completion:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_ICQNotifyDeleteReporter
+ __OBJC_$_INSTANCE_VARIABLES_ICQNotifyDeleteReporter
+ __OBJC_$_PROP_LIST_ICQNotifyDeleteReporter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ICQNotifyDeleteReporting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ICQNotifyDeleteReporting
+ __OBJC_$_PROTOCOL_REFS_ICQNotifyDeleteReporting
+ __OBJC_CLASS_PROTOCOLS_$_ICQNotifyDeleteReporter
+ __OBJC_CLASS_RO_$_ICQNotifyDeleteReporter
+ __OBJC_LABEL_PROTOCOL_$_ICQNotifyDeleteReporting
+ __OBJC_METACLASS_RO_$_ICQNotifyDeleteReporter
+ __OBJC_PROTOCOL_$_ICQNotifyDeleteReporting
+ ___71-[ICQNotifyDeleteReporter reportDeleteWithSuccess:bundleId:completion:]_block_invoke
- -[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]
- __77-[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]_block_invoke
- ___77-[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]_block_invoke
CStrings:
+ "XPC error connecting to ind daemon."
+ "reportDeleteWithSuccess:bundleId:completion: called by %{public}@ with success: %d."
- "Reaching out to daemon to report Manage Storage delete for %{public}@."
- "XPC Error while reaching out to daemon to report delete."
```
