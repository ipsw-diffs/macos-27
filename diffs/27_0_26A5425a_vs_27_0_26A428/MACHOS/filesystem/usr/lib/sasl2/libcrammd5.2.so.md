## libcrammd5.2.so

> `/usr/lib/sasl2/libcrammd5.2.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x1fb8
+  __TEXT.__text: 0x1f94
   __TEXT.__auth_stubs: 0x110
   __TEXT.__cstring: 0x5ae
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__const: 0x18
   __DATA_CONST.__auth_got: 0x88
   __DATA_CONST.__got: 0x8
Functions:
~ _crammd5_server_mech_dispose : 88 -> 76
~ _crammd5_client_mech_dispose : 84 -> 72
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
```
