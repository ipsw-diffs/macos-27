## ecosystemd

> `/System/Library/PrivateFrameworks/Ecosystem.framework/Support/ecosystemd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-60.3.0.0.0
-  __TEXT.__text: 0xbf53c
-  __TEXT.__auth_stubs: 0x1ff0
+60.4.0.0.0
+  __TEXT.__text: 0xc2fb0
+  __TEXT.__auth_stubs: 0x2030
   __TEXT.__objc_stubs: 0xae0
   __TEXT.__objc_methlist: 0x134
-  __TEXT.__const: 0x4bda
+  __TEXT.__const: 0x4c52
   __TEXT.__oslogstring: 0x6259
-  __TEXT.__cstring: 0x8f85
-  __TEXT.__swift5_typeref: 0x1be4
+  __TEXT.__cstring: 0x9205
+  __TEXT.__swift5_typeref: 0x1c44
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__objc_classname: 0x477
-  __TEXT.__objc_methname: 0x1365
-  __TEXT.__objc_methtype: 0x23f
-  __TEXT.__constg_swiftt: 0x1de4
-  __TEXT.__swift5_reflstr: 0x2027
-  __TEXT.__swift5_fieldmd: 0x1f00
+  __TEXT.__objc_classname: 0x497
+  __TEXT.__objc_methname: 0x13a5
+  __TEXT.__objc_methtype: 0x239
+  __TEXT.__constg_swiftt: 0x1eac
+  __TEXT.__swift5_reflstr: 0x2057
+  __TEXT.__swift5_fieldmd: 0x1f50
   __TEXT.__swift5_builtin: 0x12c
   __TEXT.__swift5_assocty: 0x1c8
-  __TEXT.__swift5_capture: 0x828
-  __TEXT.__swift5_proto: 0x2fc
-  __TEXT.__swift5_types: 0x198
-  __TEXT.__swift5_protos: 0x3c
+  __TEXT.__swift5_capture: 0x900
+  __TEXT.__swift5_proto: 0x300
+  __TEXT.__swift5_types: 0x19c
+  __TEXT.__swift5_protos: 0x40
   __TEXT.__swift5_mpenum: 0x48
   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0x8
   __TEXT.__swift_as_cont: 0x4
-  __TEXT.__unwind_info: 0x1ec0
-  __TEXT.__eh_frame: 0x201c
-  __DATA_CONST.__const: 0x52a8
-  __DATA_CONST.__objc_classlist: 0x98
+  __TEXT.__unwind_info: 0x1f08
+  __TEXT.__eh_frame: 0x1fe4
+  __DATA_CONST.__const: 0x5608
+  __DATA_CONST.__objc_classlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__auth_got: 0x1000
-  __DATA_CONST.__got: 0x490
-  __DATA_CONST.__auth_ptr: 0x5d0
-  __DATA.__objc_const: 0x1c98
+  __DATA_CONST.__auth_got: 0x1020
+  __DATA_CONST.__got: 0x4b0
+  __DATA_CONST.__auth_ptr: 0x5d8
+  __DATA.__objc_const: 0x1d90
   __DATA.__objc_selrefs: 0x358
   __DATA.__objc_data: 0x328
-  __DATA.__data: 0x35a0
+  __DATA.__data: 0x3688
   __DATA.__common: 0xa8
   __DATA.__bss: 0x5680
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2254
-  Symbols:   774
-  CStrings:  1383
+  Functions: 2297
+  Symbols:   779
+  CStrings:  1395
 
Symbols:
+ _$s10Foundation3URLV2eeoiySbAC_ACtFZ
+ _$s8Dispatch0A9PredicateO7onQueueyACSo17OS_dispatch_queueCcACmFWC
+ _$s8Dispatch0A9PredicateOMa
+ _$s8Dispatch25_dispatchPreconditionTestySbAA0A9PredicateOF
+ _swift_dynamicCastObjCProtocolConditional
CStrings:
+ "           Data in memory is still in use. The next reload falls back to bundled defaults.\n"
+ "           Run `ecosystemtool asset refresh` to reload now.\n"
+ "  File Size: missing (file not found on disk)\n"
+ "  Warning: cached asset file is missing. Trial may have deleted this factor pack.\n"
+ "<ecosystemd> [ASSET] cached file missing assetType=%{public}@ path=%{public}@"
+ "Note: the override is cleared when ecosystemd restarts (reboot, crash, or launchd exit)"
+ "[AssetManager] Refreshing Trial client"
+ "[AssetManager] Reopened unchanged asset: %{public}@"
+ "[AssetManager] Trial did not reload %{public}@, using bundled default instead of %{public}@"
+ "[AssetManager] Trial update pass already queued"
+ "_TtC10ecosystemd16TRIClientAdapter"
+ "com.apple.ecosystemd.trial.assetmanager.trial"
+ "isUpdatePassQueued"
+ "trialQueue"
- "[AssetManager] Refreshing client for: %{public}@"
- "[AssetManager] Trial update failed validation for %{public}@, keeping last known good version"
```
