## spindump

> `/usr/sbin/spindump`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-454.2.0.0.0
-  __TEXT.__text: 0x10e8fc
+454.4.0.0.0
+  __TEXT.__text: 0x10e9a0
   __TEXT.__auth_stubs: 0x15b0
   __TEXT.__objc_stubs: 0x4bc0
   __TEXT.__objc_methlist: 0xce0
   __TEXT.__const: 0x2e0
-  __TEXT.__oslogstring: 0x358fa
-  __TEXT.__cstring: 0x1bcc8
+  __TEXT.__oslogstring: 0x35abf
+  __TEXT.__cstring: 0x1bd12
   __TEXT.__objc_classname: 0x143
   __TEXT.__objc_methtype: 0x596
   __TEXT.__gcc_except_tab: 0x47cc
   __TEXT.__objc_methname: 0x4a11
   __TEXT.__unwind_info: 0x2648
-  __DATA_CONST.__const: 0x2190
+  __DATA_CONST.__const: 0x21b0
   __DATA_CONST.__cfstring: 0xdc20
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libz.1.dylib
   Functions: 2779
   Symbols:   462
-  CStrings:  5205
+  CStrings:  5208
 
Functions:
~ sub_1000957dc : 15772 -> 15832
~ sub_1000b02a8 -> sub_1000b02e4 : 23864 -> 23876
~ sub_1000b5fe0 -> sub_1000b6028 : 112 -> 128
~ sub_1000b6460 -> sub_1000b64b8 : 1440 -> 1452
~ sub_1000b6a00 -> sub_1000b6a64 : 1384 -> 1400
~ sub_1000b6f68 -> sub_1000b6fdc : 6852 -> 6860
~ sub_1000dfd88 -> sub_1000dfe04 : 144 -> 156
~ sub_1000dfe18 -> sub_1000dfea0 : 484 -> 512
CStrings:
+ "BundleIdOverride=%{public, signpost.description:attribute}@ %{public, signpost.description:begin_time}llu cid=%{public,name=cid}llu pid=%{public,name=pid}u conditionsPreventingSubmission=%{public,name=conditionsPreventingSubmission}#llx otherConditions=%{public,name=otherConditions}#llx hidEventCountSinceLastSignpost=%{signpost.telemetry:number1,public}llu userActionCountSinceLastSignpost=%{signpost.telemetry:number2,public}llu enableTelemetry=YES "
+ "hid_event_count_since_last_signpost"
+ "user_action_count_since_last_signpost"
```
