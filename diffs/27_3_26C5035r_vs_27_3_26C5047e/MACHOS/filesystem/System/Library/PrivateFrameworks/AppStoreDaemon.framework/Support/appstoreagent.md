## appstoreagent

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstoreagent`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-13.2.8.0.0
-  __TEXT.__text: 0x476110
-  __TEXT.__auth_stubs: 0x4690
+13.2.11.0.0
+  __TEXT.__text: 0x477440
+  __TEXT.__auth_stubs: 0x46c0
   __TEXT.__objc_stubs: 0x11aa0
-  __TEXT.__objc_methlist: 0xa1c4
+  __TEXT.__objc_methlist: 0xa1cc
   __TEXT.__dlopen_cstrs: 0x11a
-  __TEXT.__const: 0x2b564
-  __TEXT.__swift5_typeref: 0x3092
+  __TEXT.__const: 0x2b574
+  __TEXT.__swift5_typeref: 0x30a4
   __TEXT.__objc_classname: 0x3eb6
-  __TEXT.__objc_methname: 0x193a5
+  __TEXT.__objc_methname: 0x193b5
   __TEXT.__objc_methtype: 0x716f
   __TEXT.__constg_swiftt: 0x2ac8
-  __TEXT.__swift5_reflstr: 0x244a
-  __TEXT.__swift5_fieldmd: 0x2d40
+  __TEXT.__swift5_reflstr: 0x245a
+  __TEXT.__swift5_fieldmd: 0x2d4c
   __TEXT.__swift5_builtin: 0x2bc
   __TEXT.__swift5_assocty: 0x420
-  __TEXT.__oslogstring: 0x2e50c
-  __TEXT.__cstring: 0x19b91
+  __TEXT.__oslogstring: 0x2e7ca
+  __TEXT.__cstring: 0x19c73
   __TEXT.__swift5_proto: 0x400
   __TEXT.__swift5_types: 0x2e4
   __TEXT.__swift5_protos: 0x14

   __TEXT.__swift5_mpenum: 0x78
   __TEXT.__gcc_except_tab: 0x551c
   __TEXT.__ustring: 0x98
-  __TEXT.__unwind_info: 0xb120
+  __TEXT.__unwind_info: 0xb140
   __TEXT.__eh_frame: 0xac48
   __DATA_CONST.__const: 0x215b0
-  __DATA_CONST.__cfstring: 0x15320
+  __DATA_CONST.__cfstring: 0x153a0
   __DATA_CONST.__objc_classlist: 0x1088
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x420

   __DATA_CONST.__objc_arraydata: 0x748
   __DATA_CONST.__objc_dictobj: 0x258
   __DATA_CONST.__objc_arrayobj: 0x2a0
-  __DATA_CONST.__auth_got: 0x2358
+  __DATA_CONST.__auth_got: 0x2370
   __DATA_CONST.__got: 0x1a78
   __DATA_CONST.__auth_ptr: 0xa18
-  __DATA.__objc_const: 0x28e58
+  __DATA.__objc_const: 0x28e78
   __DATA.__objc_selrefs: 0x58e8
-  __DATA.__objc_ivar: 0x1c94
+  __DATA.__objc_ivar: 0x1c98
   __DATA.__objc_data: 0xc5b8
-  __DATA.__data: 0x7468
+  __DATA.__data: 0x7478
   __DATA.__bss: 0x8410
   __DATA.__common: 0xb8c
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10937
-  Symbols:   2097
-  CStrings:  11947
+  Functions: 10947
+  Symbols:   2100
+  CStrings:  11960
 
Symbols:
+ _inet_ntop
+ _inet_pton
+ _strcmp
CStrings:
+ "09:59:18"
+ "App Review download was redirected to a host outside the permitted plaintext scope."
+ "App Review package URL uses plaintext HTTP to an address that is not permitted under App Transport Security."
+ "Host %{private}@ failed inet_ntop (errno %d: %{public}s)"
+ "Host %{private}@ is not a canonical IPv4 literal"
+ "Host %{private}@ is not a valid IPv4 literal (inet_pton returned %d, errno %d: %{public}s)"
+ "Nov 10 2026"
+ "[%@] Failed to encode App Review ATS exception data error: %{public}@"
+ "[%@] Granting ATS plaintext bypass for App Review install from Magellan to host %{private}@"
+ "[%@] Rejecting App Review install: plaintext package URL host %{private}@ is neither an RFC 1918 nor a 17.0.0.0/8 address and will be blocked by ATS"
+ "[%@] Rejecting App Review redirect to %{private}@: outside the permitted http 17.0.0.0/8 scope for the ATS bypass session"
+ "[%@] Skipping App review for install as packageURL is not of type NSURL"
+ "_allowsAppReviewATSBypass"
+ "appreview-ats"
+ "com.apple.Magellan"
+ "initWithBundleID:bundleVersion:itemID:versionID:installDate:lastLaunchDate:wasFactoryInstall:"
- "03:51:30"
- "Oct 29 2026"
- "initWithBundleID:bundleVersion:itemID:versionID:installDate:lastLaunchDate:"
```
