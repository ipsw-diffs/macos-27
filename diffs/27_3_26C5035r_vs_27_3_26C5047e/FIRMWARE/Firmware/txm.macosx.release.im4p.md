## txm.macosx.release.im4p

> `Firmware/txm.macosx.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__TEXT_BOOT_EXEC.__text`
- `__DATA.__data`

```diff

-217.60.2.0.0
-  __TEXT.__cstring: 0x793e
+217.60.3.0.0
+  __TEXT.__cstring: 0x7a4e
   __TEXT.__const: 0x121c8
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x10148
   __DATA_CONST.__auth_ptr: 0x80
-  __TEXT_EXEC.__text: 0x4fb34
+  __TEXT_EXEC.__text: 0x4fc74
   __TEXT_EXEC.__exc: 0x8a0
   __TEXT_BOOT_EXEC.__text: 0x4060
   __TEXT_BOOT_EXEC.__bootcode: 0x278
   __DATA.__data: 0x350
   __DATA.__common: 0xf80
   __DATA.__bss: 0xe28
-  Functions: 1219
+  Functions: 1220
   Symbols:   1
-  CStrings:  881
+  CStrings:  887
 
CStrings:
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Mon Nov  9 22:04:47 PST 2026; root:AppleImage4_txm-374~9335/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Mon Nov  9 22:04:47 PST 2026; root:AppleImage4_txm-374~9335/libimage4_TXM/RELEASE_ARM64E"
+ "developer mode enabled due to QA automation"
+ "enqa"
+ "invalid length for QA automation property: %u"
+ "system manifest is configured with QA automation"
+ "txm.macosx.release.TrustedExecutionMonitor_Guarded-217.60.3"
+ "unable to find /chosen/manifest-properties in device tree"
+ "unable to find QA automation property in /chosen/manifest-properties"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Wed Oct 28 21:09:02 PDT 2026; root:AppleImage4_txm-374~9143/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Wed Oct 28 21:09:02 PDT 2026; root:AppleImage4_txm-374~9143/libimage4_TXM/RELEASE_ARM64E"
- "txm.macosx.release.TrustedExecutionMonitor_Guarded-217.60.2"
```
