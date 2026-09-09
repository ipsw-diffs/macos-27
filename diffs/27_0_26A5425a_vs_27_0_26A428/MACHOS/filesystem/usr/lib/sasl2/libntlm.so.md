## libntlm.so

> `/usr/lib/sasl2/libntlm.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 219.0.0.0.0
-  __TEXT.__text: 0x3de8
+  __TEXT.__text: 0x3dbc
   __TEXT.__auth_stubs: 0x200
   __TEXT.__cstring: 0xc11
   __TEXT.__const: 0x8
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x120
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__auth_got: 0x100
   __DATA_CONST.__got: 0x10
Functions:
~ __plug_ipfromstring : 568 -> 572
~ __plug_decode : 524 -> 520
~ __plug_parseuser : 372 -> 360
~ _ntlm_server_mech_dispose : 100 -> 88
~ _make_netbios_name : 228 -> 220
~ _retry_writev : 288 -> 284
~ _smb_session_setup : 1124 -> 1128
~ _ntlm_client_mech_dispose : 84 -> 72
```
