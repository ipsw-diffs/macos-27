## trustd

> `/usr/libexec/trustd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-62460.60.42.501.1
-  __TEXT.__text: 0x60174
-  __TEXT.__auth_stubs: 0x2450
-  __TEXT.__objc_stubs: 0x36c0
+62460.60.60.0.1
+  __TEXT.__text: 0x60f3c
+  __TEXT.__auth_stubs: 0x2460
+  __TEXT.__objc_stubs: 0x36e0
   __TEXT.__objc_methlist: 0xe2c
   __TEXT.__const: 0xdce0
   __TEXT.__dlopen_cstrs: 0x54
   __TEXT.__objc_classname: 0x1b4
-  __TEXT.__objc_methname: 0x3251
+  __TEXT.__objc_methname: 0x327b
   __TEXT.__objc_methtype: 0xc6b
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_typeref: 0x17
   __TEXT.__swift5_reflstr: 0x4
   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__gcc_except_tab: 0xc98
-  __TEXT.__cstring: 0x6502
-  __TEXT.__oslogstring: 0x621b
-  __TEXT.__unwind_info: 0x14e8
-  __DATA_CONST.__const: 0x44c8
-  __DATA_CONST.__cfstring: 0x68e0
+  __TEXT.__gcc_except_tab: 0xdac
+  __TEXT.__cstring: 0x67da
+  __TEXT.__oslogstring: 0x6224
+  __TEXT.__unwind_info: 0x1518
+  __DATA_CONST.__const: 0x4558
+  __DATA_CONST.__cfstring: 0x6ac0
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__objc_arraydata: 0x110
   __DATA_CONST.__objc_arrayobj: 0x78
   __DATA_CONST.__objc_dictobj: 0x190
-  __DATA_CONST.__auth_got: 0x1238
+  __DATA_CONST.__auth_got: 0x1240
   __DATA_CONST.__got: 0x928
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x1780
-  __DATA.__objc_selrefs: 0xf38
+  __DATA.__objc_selrefs: 0xf40
   __DATA.__objc_ivar: 0xd4
   __DATA.__objc_data: 0x5b8
   __DATA.__data: 0x430
-  __DATA.__bss: 0xc80
+  __DATA.__bss: 0xcb8
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 1290
-  Symbols:   897
-  CStrings:  2370
+  Functions: 1300
+  Symbols:   898
+  CStrings:  2389
 
Symbols:
+ _access
CStrings:
+ "B32@?0@\"NSNumber\"8Q16^B24"
+ "CallerID"
+ "HasQCStatements"
+ "IsOneQWAC"
+ "KeySizeSkippedUserTrust"
+ "KeySizeSkippedUserTrustAdminSettingsCount"
+ "KeySizeSkippedUserTrustStoreCount"
+ "KeySizeSkippedUserTrustUserSettingsCount"
+ "WeakHashSkippedNonSystemAnchor"
+ "WeakHashSkippedNonSystemAnchorCount"
+ "WeakKeySkippedAnchor"
+ "WeakKeySkippedAnchorNonSystemCount"
+ "WeakKeySkippedAnchorSystemCount"
+ "WeakKeySkippedNonSystemAnchor"
+ "WeakKeySkippedNonSystemAnchorCount"
+ "^{OpaqueSecPVC=^{_SecPathBuilder}^{__CFArray}^{__CFDictionary}qB^iq^{__CFArray}I^{__CFArray}I}16@?0q8"
+ "fsType"
+ "ignoring asset path (not on an AuthAPFS volume): %s"
+ "inputPath"
+ "invalid asset path: %{public}@ (%s)"
+ "isReportableAppIdentifier:platformBinary:"
+ "mountPoint"
+ "realPath"
+ "v24@?0^{OpaqueSecPVC=^{_SecPathBuilder}^{__CFArray}^{__CFDictionary}qB^iq^{__CFArray}I^{__CFArray}I}8^B16"
+ "v32@?0^{OpaqueSecPVC=^{_SecPathBuilder}^{__CFArray}^{__CFDictionary}qB^iq^{__CFArray}I^{__CFArray}I}8^{__SecPolicy={__CFRuntimeBase=QAQ}^{__CFString}^{__CFString}^{__CFDictionary}}16q24"
+ "versionPlistExists"
- "MissingEKU"
- "OCSPWeakHash"
- "WeakHash"
- "WeakKey"
- "ignoring asset path (not on an AuthAPFS volume)"
- "invalid asset path: %{public}@"
- "v24@?0^{OpaqueSecPVC=^{_SecPathBuilder}^{__CFArray}^{__CFDictionary}qB^{__CFArray}I^{__CFArray}I}8^B16"
```
