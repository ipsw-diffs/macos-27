## srp.so

> `/usr/lib/sasl2/srp.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x4a90
+  __TEXT.__text: 0x4a48
   __TEXT.__auth_stubs: 0x4d0
   __TEXT.__cstring: 0x12d8
   __TEXT.__const: 0x602
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x130
   __DATA_CONST.__const: 0x18
   __DATA_CONST.__cfstring: 0x60
   __DATA_CONST.__auth_got: 0x268
Functions:
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
~ _cc_get_digestbyname : 224 -> 176
~ _srp_common_mech_dispose : 348 -> 336
```
