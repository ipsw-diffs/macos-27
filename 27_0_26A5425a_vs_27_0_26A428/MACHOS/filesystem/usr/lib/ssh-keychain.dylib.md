## ssh-keychain.dylib

> `/usr/lib/ssh-keychain.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__data`

```diff

 878.0.13.0.0
-  __TEXT.__text: 0x44f8
+  __TEXT.__text: 0x4410
   __TEXT.__objc_methlist: 0x1fc
   __TEXT.__const: 0x60
   __TEXT.__oslogstring: 0x636
   __TEXT.__cstring: 0x10a
   __TEXT.__gcc_except_tab: 0x48
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__unwind_info: 0x188
   __TEXT.__objc_stubs: 0x9c0
   __TEXT.__auth_stubs: 0x350
   __TEXT.__objc_classname: 0x29
Functions:
~ -[NSMutableData(BIGENDIAN) appendUInt32:] : 92 -> 80
~ _TK_LOG_sshkeychain : 68 -> 56
~ ___TK_LOG_sshkeychain_block_invoke : 72 -> 60
~ _C_GetSlotList : 268 -> 264
~ -[KPSlot .cxx_destruct] : 92 -> 80
~ -[KPCertificate .cxx_destruct] : 140 -> 128
~ _getSession : 108 -> 96
~ _dataToHex : 164 -> 152
~ _dataFromHex : 228 -> 216
~ _stringCpyPaddedWithSpaces : 112 -> 100
~ _getCertificateFilter : 740 -> 728
~ _processIdentity : 1640 -> 1628
~ _TK_LOG_sshkeychain : 68 -> 56
~ _getSlot : 448 -> 436
~ _getAvailableSlots : 1440 -> 1428
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___TK_LOG_sshkeychain_block_invoke : 72 -> 60
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ _OUTLINED_FUNCTION_7 : 32 -> 20
```
