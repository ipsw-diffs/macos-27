## AppleIDSettings

> `/System/Library/ExtensionKit/Extensions/AppleIDSettings.appex/Contents/MacOS/AppleIDSettings`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_selrefs`

```diff

-218.250.3.0.0
-  __TEXT.__text: 0x7e3c8
-  __TEXT.__auth_stubs: 0x24f0
+218.250.6.0.0
+  __TEXT.__text: 0x81a98
+  __TEXT.__auth_stubs: 0x2550
   __TEXT.__objc_stubs: 0x24c0
   __TEXT.__objc_methlist: 0x840
-  __TEXT.__const: 0x6174
-  __TEXT.__constg_swiftt: 0x1e6c
-  __TEXT.__swift5_typeref: 0xa1cc
+  __TEXT.__const: 0x6434
+  __TEXT.__constg_swiftt: 0x1f40
+  __TEXT.__swift5_typeref: 0xab2c
   __TEXT.__swift5_builtin: 0xc8
-  __TEXT.__swift5_reflstr: 0x122d
-  __TEXT.__swift5_fieldmd: 0x10f8
-  __TEXT.__swift5_assocty: 0x700
-  __TEXT.__swift5_proto: 0x28c
-  __TEXT.__swift5_types: 0x148
+  __TEXT.__swift5_reflstr: 0x12bd
+  __TEXT.__swift5_fieldmd: 0x115c
+  __TEXT.__swift5_assocty: 0x718
+  __TEXT.__swift5_proto: 0x290
+  __TEXT.__swift5_types: 0x14c
   __TEXT.__objc_classname: 0x6df
-  __TEXT.__objc_methname: 0x2e15
+  __TEXT.__objc_methname: 0x2e55
   __TEXT.__objc_methtype: 0xaf7
-  __TEXT.__oslogstring: 0x3fe3
-  __TEXT.__cstring: 0x1c3d
-  __TEXT.__swift5_capture: 0xb30
-  __TEXT.__swift_as_entry: 0x94
+  __TEXT.__oslogstring: 0x4173
+  __TEXT.__cstring: 0x1c9d
+  __TEXT.__swift5_capture: 0xb98
+  __TEXT.__swift_as_entry: 0x98
   __TEXT.__swift_as_ret: 0xac
-  __TEXT.__swift_as_cont: 0x12c
+  __TEXT.__swift_as_cont: 0x130
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x1ff8
-  __TEXT.__eh_frame: 0x1a88
-  __DATA_CONST.__const: 0x3e28
+  __TEXT.__unwind_info: 0x20a0
+  __TEXT.__eh_frame: 0x1b08
+  __DATA_CONST.__const: 0x3f80
   __DATA_CONST.__objc_classlist: 0x90
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xa8
-  __DATA_CONST.__auth_got: 0x1280
-  __DATA_CONST.__got: 0xb18
-  __DATA_CONST.__auth_ptr: 0xc90
-  __DATA.__objc_const: 0x33a8
+  __DATA_CONST.__auth_got: 0x12b0
+  __DATA_CONST.__got: 0xb20
+  __DATA_CONST.__auth_ptr: 0xcc8
+  __DATA.__objc_const: 0x33e8
   __DATA.__objc_selrefs: 0xbe8
-  __DATA.__objc_data: 0x1690
-  __DATA.__data: 0x33c0
-  __DATA.__bss: 0x5308
+  __DATA.__objc_data: 0x1730
+  __DATA.__data: 0x34b0
+  __DATA.__bss: 0x53c8
   __DATA.__common: 0xe8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2503
+  Functions: 2559
   Symbols:   340
-  CStrings:  1039
+  CStrings:  1050
 
CStrings:
+ "$__lazy_storage_$_refreshNavigationForTermsChange"
+ "Account is not the one the pane shows; leaving the terms banner unchanged."
+ "Shown account is not an Apple Account; clearing the terms banner."
+ "TERMS_BANNER_ACTION"
+ "TERMS_BANNER_LABEL"
+ "TERMS_BANNER_TITLE"
+ "Terms banner visibility already %{bool}d; skipping the refresh."
+ "Terms banner visibility changed to %{bool}d; refreshing the navigation."
+ "Unable to present terms without a shown account"
+ "Unable to resolve MMAccount to present terms"
+ "Unable to resolve an account from the terms follow-up arguments"
+ "_isTermsBannerVisible"
- "Trying to show terms when we do not have an accountIdentifier"
```
