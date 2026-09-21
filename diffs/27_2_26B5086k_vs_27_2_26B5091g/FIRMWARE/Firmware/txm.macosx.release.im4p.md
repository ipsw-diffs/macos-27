## txm.macosx.release.im4p

> `Firmware/txm.macosx.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__TEXT_BOOT_EXEC.__text`
- `__DATA.__data`

```diff

   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x10148
   __DATA_CONST.__auth_ptr: 0x80
-  __TEXT_EXEC.__text: 0x4fb14
+  __TEXT_EXEC.__text: 0x4fb24
   __TEXT_EXEC.__exc: 0x8a0
   __TEXT_BOOT_EXEC.__text: 0x4060
   __TEXT_BOOT_EXEC.__bootcode: 0x278
Functions:
~ sub_fffffff017066498 : 200 -> 204
~ sub_fffffff0170681c0 -> sub_fffffff0170681c4 : 488 -> 500
CStrings:
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Fri Sep 11 20:15:43 PDT 2026; root:AppleImage4_txm-374~8076/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Fri Sep 11 20:15:43 PDT 2026; root:AppleImage4_txm-374~8076/libimage4_TXM/RELEASE_ARM64E"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Wed Sep  2 23:26:50 PDT 2026; root:AppleImage4_txm-374~7870/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Wed Sep  2 23:26:50 PDT 2026; root:AppleImage4_txm-374~7870/libimage4_TXM/RELEASE_ARM64E"
```
