## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferAgent.framework/Versions/A/IMTransferAgent`

```diff

-1491.200.101.1.3
-  __TEXT.__text: 0x19608
-  __TEXT.__objc_methlist: 0xa84
+1491.300.43.0.0
+  __TEXT.__text: 0x1a280
+  __TEXT.__objc_methlist: 0xa9c
   __TEXT.__const: 0x118
-  __TEXT.__gcc_except_tab: 0x1754
+  __TEXT.__gcc_except_tab: 0x17d4
   __TEXT.__cstring: 0xc0a
-  __TEXT.__oslogstring: 0x2ab5
-  __TEXT.__unwind_info: 0x6b8
+  __TEXT.__oslogstring: 0x2e4b
+  __TEXT.__unwind_info: 0x6f0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd78
+  __DATA_CONST.__objc_selrefs: 0xd90
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x378
-  __AUTH_CONST.__const: 0xa60
+  __DATA_CONST.__got: 0x380
+  __AUTH_CONST.__const: 0xb20
   __AUTH_CONST.__cfstring: 0xe00
   __AUTH_CONST.__objc_const: 0xdb0
   __AUTH_CONST.__objc_intobj: 0x48

   - /System/Library/PrivateFrameworks/Marco.framework/Versions/A/Marco
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 302
-  Symbols:   232
-  CStrings:  356
+  Functions: 310
+  Symbols:   237
+  CStrings:  364
 
Symbols:
+ _IMIsCommSafetySensitiveFromSCSensitivityAnalysis
+ _IMMMCSForceFallbackPathForTesting
+ _IMMMCSRegionStoreFeatureEnabled
+ _IMMMCSResponseRequiresFailure
+ _IMShouldDisableMMCSFallbackForRegion
+ _OBJC_CLASS_$_IMRegionConnectionPolicy
- _IMCommSafetyStateFromSCSensitivityAnalysis
CStrings:
+ "Avatar image was checked for sensitive content. Is sensitive: %{BOOL}d, error: %@"
+ "Failing download for transfer %@ rather than falling back to the unoptimized MMCS path in a region that disallows it."
+ "Failing upload for transfer %@ rather than falling back to the unoptimized MMCS path in a region that disallows it."
+ "Ignoring the AuthGet opt-out for download with GUID %@: region disallows the MMCS fallback."
+ "Ignoring the AuthPut opt-out for upload with GUID %@: region disallows the MMCS fallback."
+ "Madrid did not preauthorize ('cV': %tu); failing download rather than falling back to the unoptimized MMCS path in a region that disallows it (transfer: %@)"
+ "Madrid did not preauthorize ('cV': %tu); failing upload rather than falling back to the unoptimized MMCS path in a region that disallows it (transfer: %@)"
+ "Region disallows the MMCS fallback; refusing the unoptimized MMCS path for this transfer."
+ "Wallpaper image was checked for sensitive content. Is sensitive: %{BOOL}d, error: %@"
+ "Withholding Madrid content headers to force the MMCS fallback path due to user default."
- "Avatar image was checked for sensitive content. Is sensitive: %d, error: %@"
- "Wallpaper image was checked for sensitive content. Is sensitive: %d, error: %@"
```
