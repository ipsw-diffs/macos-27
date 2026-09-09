## smb

> `/System/Library/Templates/Data/usr/libexec/cups/apple/smb`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 676.0.0.0.0
-  __TEXT.__text: 0x5c48
+  __TEXT.__text: 0x5b8c
   __TEXT.__auth_stubs: 0x670
   __TEXT.__const: 0x218
   __TEXT.__gcc_except_tab: 0x27c
   __TEXT.__cstring: 0xdd51
   __TEXT.__oslogstring: 0x106
-  __TEXT.__unwind_info: 0x1b0
+  __TEXT.__unwind_info: 0x1d8
   __DATA_CONST.__const: 0x7370
   __DATA_CONST.__auth_got: 0x340
   __DATA_CONST.__got: 0x70
Functions:
~ __ZN7spoolss7extractERPhRKS0_RNS_10JOB_INFO_1ES3_ : 588 -> 576
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN8platform15utf16_converter4initEPKh : 84 -> 72
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ __Z16make_rpc_bindingPKcS0_ : 1144 -> 1104
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqe220106Ev : 360 -> 320
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED2Ev : 284 -> 232
~ __ZN3smb20extract_utf16_stringERPhS0_R10oem_string : 128 -> 132
```
