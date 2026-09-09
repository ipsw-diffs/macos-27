## mschapv2.so

> `/usr/lib/sasl2/mschapv2.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 195.0.0.0.0
-  __TEXT.__text: 0x24fc
+  __TEXT.__text: 0x24dc
   __TEXT.__auth_stubs: 0x1b0
   __TEXT.__const: 0xb0
   __TEXT.__cstring: 0x6b6
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x18
   __DATA_CONST.__auth_got: 0xd8
   __DATA_CONST.__got: 0x10
Functions:
~ _chap_both_mech_dispose : 112 -> 100
~ __plug_ipfromstring : 568 -> 572
~ __plug_parseuser : 372 -> 360
~ _CStringToUnicode : 148 -> 136
```
