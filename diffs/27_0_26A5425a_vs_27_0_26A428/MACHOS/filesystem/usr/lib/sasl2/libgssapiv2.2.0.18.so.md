## libgssapiv2.2.0.18.so

> `/usr/lib/sasl2/libgssapiv2.2.0.18.so`

### Sections with Same Size but Changed Content

- `__AUTH.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x3a74
+  __TEXT.__text: 0x3a50
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x792
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0x108
   __TEXT.__auth_stubs: 0x290
   __DATA_CONST.__got: 0x28
   __AUTH_CONST.__auth_got: 0x148
Functions:
~ _gssapi_server_mech_step : 3236 -> 3228
~ _gssapi_common_mech_dispose : 64 -> 52
~ _gssapi_client_mech_step : 3792 -> 3788
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
```
