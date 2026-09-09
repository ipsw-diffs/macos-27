## login.so

> `/usr/lib/sasl2/login.so`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x1aa4
+  __TEXT.__text: 0x1a80
   __TEXT.__auth_stubs: 0xe0
   __TEXT.__cstring: 0x5b4
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__auth_got: 0x70
   __DATA_CONST.__got: 0x8
   __DATA.__data: 0xc8
Functions:
~ _login_server_mech_dispose : 84 -> 72
~ _login_client_mech_dispose : 88 -> 76
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
```
