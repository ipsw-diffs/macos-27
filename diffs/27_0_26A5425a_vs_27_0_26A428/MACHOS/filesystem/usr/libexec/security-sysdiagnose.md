## security-sysdiagnose

> `/usr/libexec/security-sysdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-62460.1.2.0.0
-  __TEXT.__text: 0x40fc
+62460.1.3.0.0
+  __TEXT.__text: 0x406c
   __TEXT.__auth_stubs: 0x6d0
   __TEXT.__objc_stubs: 0x520
   __TEXT.__objc_methlist: 0xdc

   __TEXT.__objc_methtype: 0x1a7
   __TEXT.__cstring: 0xe28
   __TEXT.__oslogstring: 0xa8
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x118
   __DATA_CONST.__const: 0x358
   __DATA_CONST.__cfstring: 0xc60
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_100000dc0 : 56 -> 44
~ sub_100000df8 -> sub_100000dec : 56 -> 44
~ sub_100000e30 -> sub_100000e18 : 280 -> 268
~ sub_100000f48 -> sub_100000f24 : 472 -> 460
~ sub_100001120 -> sub_1000010f0 : 764 -> 752
~ sub_100003060 -> sub_100003024 : 176 -> 164
~ sub_100003404 -> sub_1000033bc : 104 -> 92
~ sub_10000347c -> sub_100003428 : 108 -> 96
~ sub_100004198 -> sub_100004138 : 80 -> 68
~ sub_1000041e8 -> sub_10000417c : 72 -> 60
~ sub_100004c0c -> sub_100004b94 : 392 -> 368
```
