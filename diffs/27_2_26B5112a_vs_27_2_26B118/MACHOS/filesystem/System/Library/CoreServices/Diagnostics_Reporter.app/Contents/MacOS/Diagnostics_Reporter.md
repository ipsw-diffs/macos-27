## Diagnostics Reporter

> `/System/Library/CoreServices/Diagnostics Reporter.app/Contents/MacOS/Diagnostics Reporter`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 1056.40.8.0.0
-  __TEXT.__text: 0x18ac8
-  __TEXT.__auth_stubs: 0x1040
+  __TEXT.__text: 0x18bf4
+  __TEXT.__auth_stubs: 0x1050
   __TEXT.__objc_stubs: 0x760
   __TEXT.__objc_methlist: 0x518
-  __TEXT.__cstring: 0x755
+  __TEXT.__cstring: 0x7a5
   __TEXT.__const: 0x1014
   __TEXT.__constg_swiftt: 0x60c
   __TEXT.__swift5_typeref: 0x986

   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__auth_got: 0x828
+  __DATA_CONST.__auth_got: 0x830
   __DATA_CONST.__got: 0x290
   __DATA_CONST.__auth_ptr: 0x368
   __DATA.__objc_const: 0x838

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 485
-  Symbols:   464
-  CStrings:  313
+  Functions: 486
+  Symbols:   465
+  CStrings:  316
 
Symbols:
+ __os_feature_enabled_impl
CStrings:
+ "OSAnalytics"
+ "com.apple.DiagnosticsReporter"
+ "forceSeedFeedbackPrompting"
```
