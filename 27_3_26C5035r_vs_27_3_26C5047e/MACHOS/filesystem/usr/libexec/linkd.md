## linkd

> `/usr/libexec/linkd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_ret`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-301.2.7.2.0
-  __TEXT.__text: 0xb979c
-  __TEXT.__auth_stubs: 0x25f0
+301.2.12.2.0
+  __TEXT.__text: 0xba854
+  __TEXT.__auth_stubs: 0x2600
   __TEXT.__objc_stubs: 0x2760
   __TEXT.__objc_methlist: 0xe74
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__const: 0x55dc
-  __TEXT.__constg_swiftt: 0x1c78
-  __TEXT.__swift5_typeref: 0x2c46
+  __TEXT.__const: 0x5622
+  __TEXT.__objc_classname: 0x8e6
+  __TEXT.__objc_methname: 0x3fcd
+  __TEXT.__objc_methtype: 0x195d
+  __TEXT.__constg_swiftt: 0x1cbc
+  __TEXT.__swift5_typeref: 0x2c7c
+  __TEXT.__swift5_reflstr: 0x1297
+  __TEXT.__swift5_fieldmd: 0x1650
   __TEXT.__swift5_builtin: 0x1cc
-  __TEXT.__swift5_reflstr: 0x1287
-  __TEXT.__swift5_fieldmd: 0x1628
   __TEXT.__swift5_assocty: 0x2d0
   __TEXT.__swift5_proto: 0x2d0
-  __TEXT.__swift5_types: 0x1b0
-  __TEXT.__objc_classname: 0x896
-  __TEXT.__objc_methname: 0x3f7d
-  __TEXT.__objc_methtype: 0x195d
+  __TEXT.__swift5_types: 0x1b4
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__cstring: 0x1df0
-  __TEXT.__swift5_capture: 0x2d60
-  __TEXT.__oslogstring: 0x5004
+  __TEXT.__cstring: 0x1e1b
+  __TEXT.__swift5_capture: 0x2d94
+  __TEXT.__oslogstring: 0x5094
   __TEXT.__swift5_protos: 0x68
   __TEXT.__swift_as_entry: 0x598
   __TEXT.__swift_as_cont: 0x724
   __TEXT.__swift_as_ret: 0x568
-  __TEXT.__unwind_info: 0x4158
-  __TEXT.__eh_frame: 0x9de8
-  __DATA_CONST.__const: 0x9230
-  __DATA_CONST.__objc_classlist: 0xe0
+  __TEXT.__unwind_info: 0x4198
+  __TEXT.__eh_frame: 0x9e38
+  __DATA_CONST.__const: 0x92d0
+  __DATA_CONST.__objc_classlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xc0
-  __DATA_CONST.__auth_got: 0x1300
+  __DATA_CONST.__auth_got: 0x1308
   __DATA_CONST.__got: 0xa30
-  __DATA_CONST.__auth_ptr: 0x12c8
-  __DATA.__objc_const: 0x2220
+  __DATA_CONST.__auth_ptr: 0x12e0
+  __DATA.__objc_const: 0x22d8
   __DATA.__objc_selrefs: 0xe30
   __DATA.__objc_data: 0xa48
-  __DATA.__data: 0x38b8
+  __DATA.__data: 0x3978
   __DATA.__bss: 0x3f80
   __DATA.__common: 0x308
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5296
-  Symbols:   1105
-  CStrings:  1225
+  Functions: 5313
+  Symbols:   1106
+  CStrings:  1230
 
Symbols:
+ _$s8Dispatch0A3QoSV10backgroundACvgZ
CStrings:
+ "%{public}s is not in the index and no audit is needed, unblocking"
+ "Failed to exclude %{public}s from backups: %{public}@"
+ "_TtC10LinkDaemon34AppNotificationEventListenerClient"
+ "com.apple.linkd.backup-exclusion"
+ "listenerBundleIdentifier"
```
