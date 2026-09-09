## libdigestmd5.2.so

> `/usr/lib/sasl2/libdigestmd5.2.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x7078
+  __TEXT.__text: 0x7018
   __TEXT.__auth_stubs: 0x190
   __TEXT.__const: 0xf8
   __TEXT.__cstring: 0x138f
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x150
   __DATA_CONST.__const: 0x18
   __DATA_CONST.__auth_got: 0xc8
   __DATA_CONST.__got: 0x10
Functions:
~ _free_rc4 : 96 -> 84
~ _digestmd5_server_mech_step : 1884 -> 1872
~ _digestmd5_common_mech_free : 212 -> 200
~ _MD5_UTF8_8859_1 : 276 -> 264
~ _digestmd5_common_mech_dispose : 368 -> 356
~ _digestmd5_client_mech_step : 4020 -> 4008
~ _digestmd5_client_mech_dispose : 124 -> 112
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
```
