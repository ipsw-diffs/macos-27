## MobileDevice

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/MobileDevice.framework/Versions/A/MobileDevice`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_MobileDev`
- `__TEXT.__dof_afc`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-1860.40.9.0.0
-  __TEXT.__text: 0x2b0f98
+1860.40.12.0.0
+  __TEXT.__text: 0x2b1018
   __TEXT.__objc_methlist: 0x3fbc
   __TEXT.__const: 0x10e9d0
-  __TEXT.__cstring: 0x7ad97
+  __TEXT.__cstring: 0x7ae0a
   __TEXT.__gcc_except_tab: 0x53a4
   __TEXT.__oslogstring: 0xf37
   __TEXT.__ustring: 0xb0

   __DATA_CONST.__objc_selrefs: 0x1d20
   __DATA_CONST.__got: 0x3a8
   __AUTH_CONST.__const: 0x90f8
-  __AUTH_CONST.__cfstring: 0x404e0
+  __AUTH_CONST.__cfstring: 0x40520
   __AUTH_CONST.__objc_const: 0x74e0
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__auth_got: 0x20d0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libssl.35.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 10416
-  Symbols:   14695
-  CStrings:  16953
+  Functions: 10417
+  Symbols:   14696
+  CStrings:  16955
 
Symbols:
+ GCC_except_table1106
+ GCC_except_table1292
+ GCC_except_table1295
+ GCC_except_table1412
+ _AMAuthInstallCopyDebugPath
+ _AMAuthInstallSetDebugPath
- GCC_except_table1107
- GCC_except_table1293
- GCC_except_table1296
- GCC_except_table1413
- __ZL48_thr_AMRestorableDeviceHandleMDRSDeviceConnectedP20__AMRestorableDeviceP23__MDRemoteServiceDevice
CStrings:
+ "1860.40.12"
+ "Found new non-USB RSD device, ignoring."
+ "Found non-USB RSD device which isn't restoring, ignoring."
+ "RSD callback triggered: ProductID=0x%04x LocationID=0x%08x IsRestorable=%d IsRestoreEnd=%d SupportsLockdown=%d IOKitFallback=%d"
+ "libauthinstall-1155.40.7"
+ "restore library built Sep 13 2026 at 18:52:14"
- "1860.40.9"
- "RSD callback triggered: ProductID=0x%04x LocationID=0x%08x IsRestorable=%d SupportsLockdown=%d IOKitFallback=%d"
- "libauthinstall-1155.40.6"
- "restore library built Sep  5 2026 at 03:58:03"
```
