## VTL

> `/System/Library/Extensions/VTLAdapter.kext/Contents/PlugIns/VTL.plugin/Contents/MacOS/VTL`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 15.0.0.0.0
-  __TEXT.__text: 0x74f8
+  __TEXT.__text: 0x7460
   __TEXT.__auth_stubs: 0x4a0
   __TEXT.__const: 0xce
   __TEXT.__oslogstring: 0x4a3
   __TEXT.__cstring: 0xb34
   __TEXT.__gcc_except_tab: 0xba0
-  __TEXT.__unwind_info: 0x398
+  __TEXT.__unwind_info: 0x498
   __DATA_CONST.__const: 0x1f0
   __DATA_CONST.__auth_got: 0x258
   __DATA_CONST.__got: 0x80
Functions:
~ sub_a30 : 28 -> 16
~ __ZN3VTL10IOCFPlugIn14QueryInterfaceE11CFUUIDBytesPPv : 252 -> 240
~ sub_18f0 -> sub_18d8 : 144 -> 132
~ sub_2424 -> sub_2400 : 432 -> 428
~ sub_25d4 -> sub_25ac : 164 -> 152
~ sub_26d8 -> sub_26a4 : 196 -> 192
~ sub_2cfc -> sub_2cc4 : 284 -> 268
~ sub_2e18 -> sub_2dd0 : 284 -> 268
~ sub_4534 -> sub_44dc : 164 -> 152
~ sub_4620 -> sub_45bc : 196 -> 192
~ sub_66b0 -> sub_6648 : 260 -> 248
~ sub_6b04 -> sub_6a90 : 28 -> 16
~ sub_6b44 -> sub_6ac4 : 32 -> 20
~ sub_6b64 -> sub_6ad8 : 32 -> 20
```
