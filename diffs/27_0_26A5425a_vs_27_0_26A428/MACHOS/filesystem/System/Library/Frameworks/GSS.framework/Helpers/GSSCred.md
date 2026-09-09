## GSSCred

> `/System/Library/Frameworks/GSS.framework/Helpers/GSSCred`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 725.0.12.0.0
-  __TEXT.__text: 0x1d740
+  __TEXT.__text: 0x1d6ec
   __TEXT.__auth_stubs: 0x1190
   __TEXT.__objc_stubs: 0xac0
   __TEXT.__objc_methlist: 0x2a4

   __TEXT.__objc_methname: 0x84c
   __TEXT.__objc_methtype: 0x25c
   __TEXT.__dlopen_cstrs: 0x68
-  __TEXT.__unwind_info: 0x2d8
+  __TEXT.__unwind_info: 0x530
   __DATA_CONST.__const: 0xb90
   __DATA_CONST.__cfstring: 0x1080
   __DATA_CONST.__objc_classlist: 0x30
Functions:
~ _GSSOSLog : 136 -> 124
~ +[GSSCredXPCHelperClient createXPCConnection:] : 524 -> 512
~ _ksEncryptData : 1800 -> 1788
~ _ksDecryptData : 2588 -> 2576
~ +[HeimCredDecoder allowedClasses] : 144 -> 132
~ _GSSHelperOSLog : 136 -> 124
~ _OUTLINED_FUNCTION_43 : 24 -> 12
```
