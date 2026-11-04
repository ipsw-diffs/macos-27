## txm.macosx.release.im4p

> `Firmware/txm.macosx.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__TEXT_BOOT_EXEC.__text`
- `__DATA.__data`

```diff

-217.0.2.0.0
+217.60.2.0.0
   __TEXT.__cstring: 0x793e
   __TEXT.__const: 0x121c8
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x10148
   __DATA_CONST.__auth_ptr: 0x80
-  __TEXT_EXEC.__text: 0x4fb14
+  __TEXT_EXEC.__text: 0x4fb34
   __TEXT_EXEC.__exc: 0x8a0
   __TEXT_BOOT_EXEC.__text: 0x4060
   __TEXT_BOOT_EXEC.__bootcode: 0x278
Functions:
~ sub_fffffff01705d1e4 : 296 -> 328
CStrings:
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Wed Oct 28 21:09:02 PDT 2026; root:AppleImage4_txm-374~9143/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Wed Oct 28 21:09:02 PDT 2026; root:AppleImage4_txm-374~9143/libimage4_TXM/RELEASE_ARM64E"
+ "txm.macosx.release.TrustedExecutionMonitor_Guarded-217.60.2"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Sat Oct  3 13:22:28 PDT 2026; root:AppleImage4_txm-374~8631/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Sat Oct  3 13:22:28 PDT 2026; root:AppleImage4_txm-374~8631/libimage4_TXM/RELEASE_ARM64E"
- "txm.macosx.release.TrustedExecutionMonitor_Guarded-217.0.2"
```
