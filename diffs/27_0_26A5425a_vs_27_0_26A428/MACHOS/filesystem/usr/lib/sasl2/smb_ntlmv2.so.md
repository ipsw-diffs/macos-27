## smb_ntlmv2.so

> `/usr/lib/sasl2/smb_ntlmv2.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 195.0.0.0.0
-  __TEXT.__text: 0x20ac
+  __TEXT.__text: 0x2080
   __TEXT.__auth_stubs: 0x190
   __TEXT.__cstring: 0x6fb
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__const: 0x20
   __DATA_CONST.__auth_got: 0xc8
   __DATA_CONST.__got: 0x10
Functions:
~ _CStringToUnicode : 148 -> 136
~ _ntlmv2_server_mech_step : 1768 -> 1756
~ _ntlmv2_both_mech_dispose : 112 -> 100
~ __plug_ipfromstring : 568 -> 572
~ __plug_parseuser : 372 -> 360
```
