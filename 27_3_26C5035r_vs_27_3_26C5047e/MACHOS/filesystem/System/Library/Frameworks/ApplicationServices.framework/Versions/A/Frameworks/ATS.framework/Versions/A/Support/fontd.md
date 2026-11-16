## fontd

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/ATS.framework/Versions/A/Support/fontd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-425.0.0.0.0
-  __TEXT.__text: 0x37a40
-  __TEXT.__auth_stubs: 0x14b0
-  __TEXT.__objc_stubs: 0xe60
+426.0.0.0.0
+  __TEXT.__text: 0x386fc
+  __TEXT.__auth_stubs: 0x14d0
+  __TEXT.__objc_stubs: 0xea0
   __TEXT.__objc_methlist: 0x608
-  __TEXT.__gcc_except_tab: 0x59cc
-  __TEXT.__const: 0x7d0
-  __TEXT.__cstring: 0x7f78
+  __TEXT.__gcc_except_tab: 0x5b24
+  __TEXT.__const: 0x7c8
+  __TEXT.__cstring: 0x8074
   __TEXT.__objc_classname: 0xac
-  __TEXT.__objc_methname: 0x10b9
+  __TEXT.__objc_methname: 0x10c0
   __TEXT.__objc_methtype: 0x8af
   __TEXT.__oslogstring: 0x3
-  __TEXT.__unwind_info: 0x1ca8
-  __DATA_CONST.__const: 0x4460
-  __DATA_CONST.__cfstring: 0x26e0
+  __TEXT.__unwind_info: 0x1cf8
+  __DATA_CONST.__const: 0x44e0
+  __DATA_CONST.__cfstring: 0x2760
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x18
-  __DATA_CONST.__auth_got: 0xa70
-  __DATA_CONST.__got: 0x250
+  __DATA_CONST.__auth_got: 0xa80
+  __DATA_CONST.__got: 0x270
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x5f8
-  __DATA.__objc_selrefs: 0x568
+  __DATA.__objc_selrefs: 0x578
   __DATA.__objc_ivar: 0x18
   __DATA.__objc_data: 0x140
   __DATA.__data: 0x738

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1007
-  Symbols:   419
-  CStrings:  821
+  Functions: 1015
+  Symbols:   425
+  CStrings:  828
 
Symbols:
+ _CFNullGetTypeID
+ _FSGetMaxSupportedFontAssetCompatibilityVersion
+ _OBJC_CLASS_$_NSPredicate
+ _kFSFontAssetFontInfoKey
+ _kFSFontAssetMockFutureVersion
+ _kFSFontAssetPostScriptFontNameKey
CStrings:
+ "B24@?0@\"MAAsset\"8@\"NSDictionary\"16"
+ "Downloading font \"%@\" (assetId: \"%@\") failed (%d)."
+ "MaxFontCompatibilityVersion"
+ "XType - deleting duplicated FontAsset for %@ failed (%d)."
+ "XType - downloading FontAsset for %@."
+ "XType - purging unsupported FontAsset %@ failed (%d)."
+ "XType - purging unsupported FontAsset for %@ (assetId: \"%@\")."
+ "allKeys"
+ "assetId"
+ "filteredArrayUsingPredicate:"
+ "firstObject"
+ "predicateWithBlock:"
+ "purge:"
- "Downloading newer font \"%@\" failed."
- "XType - found newer FontAsset for %@."
- "intValue"
- "intersectsSet:"
- "numberWithInteger:"
- "sortedArrayUsingFunction:context:"
```
