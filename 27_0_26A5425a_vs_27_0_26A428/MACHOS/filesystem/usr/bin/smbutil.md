## smbutil

> `/usr/bin/smbutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 579.0.11.0.0
-  __TEXT.__text: 0xd668
+  __TEXT.__text: 0xd5c4
   __TEXT.__auth_stubs: 0x960
   __TEXT.__objc_stubs: 0x180
   __TEXT.__cstring: 0x3c17

   __TEXT.__oslogstring: 0x39e
   __TEXT.__gcc_except_tab: 0xfc
   __TEXT.__objc_methname: 0xf5
-  __TEXT.__unwind_info: 0x268
+  __TEXT.__unwind_info: 0x338
   __DATA_CONST.__const: 0x158
   __DATA_CONST.__cfstring: 0xb80
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _main : 304 -> 292
~ _print_header : 92 -> 80
~ __ZL20addShareToDictionaryP17smb_server_handleP14__CFDictionaryPK10__CFStringS5_tP6statfsi : 700 -> 688
~ _print_header : 204 -> 192
~ _print_footer : 100 -> 88
~ _print_header : 204 -> 192
~ _add_str : 92 -> 80
~ _NetApiBufferFree : 52 -> 40
~ __ZN8platform18invoke_new_handlerEv : 76 -> 64
~ __ZN11rpc_mempool7destroyEPS_ : 40 -> 28
~ __ZNSt3__16vectorIPvNS_9allocatorIS1_EEE6resizeEm : 284 -> 268
~ __ZN11rpc_mempool4freeEPv : 156 -> 144
~ __ZZNSt3__16vectorIPvNS_9allocatorIS1_EEE12emplace_backIJRKS1_EEEvDpOT_ENKUlvE0_clEv : 204 -> 200
~ _OUTLINED_FUNCTION_1 : 28 -> 16
```
