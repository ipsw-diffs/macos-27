## libanonymous.2.so

> `/usr/lib/sasl2/libanonymous.2.so`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x1910
+  __TEXT.__text: 0x18f0
   __TEXT.__auth_stubs: 0xf0
   __TEXT.__cstring: 0x4dd
   __TEXT.__const: 0x18
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__auth_got: 0x78
   __DATA_CONST.__got: 0x8
   __DATA.__data: 0xc8
Functions:
~ _anonymous_server_mech_step : 360 -> 352
~ _anonymous_client_dispose : 84 -> 72
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
```
