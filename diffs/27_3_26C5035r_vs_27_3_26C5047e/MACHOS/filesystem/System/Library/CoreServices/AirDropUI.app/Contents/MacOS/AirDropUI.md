## AirDropUI

> `/System/Library/CoreServices/AirDropUI.app/Contents/MacOS/AirDropUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2131.30.43.1.1
-  __TEXT.__text: 0x9dbd4
-  __TEXT.__auth_stubs: 0x2740
+2131.30.65.0.0
+  __TEXT.__text: 0x9e0d0
+  __TEXT.__auth_stubs: 0x2750
   __TEXT.__objc_stubs: 0xa20
   __TEXT.__objc_methlist: 0x394
   __TEXT.__const: 0x6014

   __TEXT.__objc_methtype: 0x608
   __TEXT.__cstring: 0x875
   __TEXT.__swift5_mpenum: 0x2c
-  __TEXT.__oslogstring: 0x1bd7
+  __TEXT.__oslogstring: 0x1c37
   __TEXT.__swift5_capture: 0xbcc
   __TEXT.__swift_as_entry: 0x8c
   __TEXT.__swift_as_ret: 0x7c

   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x40
-  __DATA_CONST.__auth_got: 0x13a8
+  __DATA_CONST.__auth_got: 0x13b0
   __DATA_CONST.__got: 0xaf8
   __DATA_CONST.__auth_ptr: 0xb20
   __DATA.__objc_const: 0x13e8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 2028
-  Symbols:   1215
-  CStrings:  427
+  Symbols:   1216
+  CStrings:  428
 
Symbols:
+ _$s7Sharing16SFAirDropReceiveO8TransferV5StateO9invisibleSbvg
Functions:
~ sub_10000d99c : 18596 -> 19488
~ sub_100028460 -> sub_1000287dc : 260 -> 284
~ sub_100028a3c -> sub_100028dd0 : 112 -> 124
~ sub_10002d9c4 -> sub_10002dd64 : 228 -> 252
~ sub_10003c484 -> sub_10003c83c : 2128 -> 2136
~ sub_10003faac -> sub_10003fe6c : 3120 -> 3188
~ sub_100066d38 -> sub_10006713c : 2588 -> 2712
~ sub_100087dcc -> sub_10008824c : 132 -> 156
~ sub_100088b80 -> sub_100089018 : 252 -> 276
~ sub_100093964 -> sub_100093e14 : 260 -> 284
~ sub_100093a68 -> sub_100093f30 : 300 -> 324
~ sub_100093b94 -> sub_100094074 : 456 -> 484
CStrings:
+ "AirDropTransferSessionController transfer update for %s skipped for invisible state: %s"
```
