## CoreJapaneseEngine

> `/System/Library/PrivateFrameworks/CoreJapaneseEngine.framework/Versions/A/CoreJapaneseEngine`

```diff

-275.208.0.0.0
-  __TEXT.__text: 0x3d494
-  __TEXT.__objc_methlist: 0x2fc4
+276.2.2.0.0
+  __TEXT.__text: 0x3d5d4
+  __TEXT.__objc_methlist: 0x2fe4
   __TEXT.__const: 0x1e8
   __TEXT.__gcc_except_tab: 0x634
-  __TEXT.__cstring: 0x2cca
+  __TEXT.__cstring: 0x2d12
   __TEXT.__oslogstring: 0x1475
   __TEXT.__ustring: 0x57a
-  __TEXT.__unwind_info: 0xd90
+  __TEXT.__unwind_info: 0xda0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2808
+  __DATA_CONST.__objc_selrefs: 0x2820
   __DATA_CONST.__objc_superrefs: 0x88
   __DATA_CONST.__objc_arraydata: 0x7b8
   __DATA_CONST.__got: 0x428
   __AUTH_CONST.__const: 0xd40
-  __AUTH_CONST.__cfstring: 0x3fc0
+  __AUTH_CONST.__cfstring: 0x4020
   __AUTH_CONST.__objc_const: 0x4998
   __AUTH_CONST.__objc_intobj: 0xaf8
   __AUTH_CONST.__objc_dictobj: 0x280
   __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH_CONST.__auth_got: 0xa00
+  __AUTH_CONST.__auth_got: 0xa10
   __AUTH.__objc_data: 0x820
   __DATA.__objc_ivar: 0x3e4
   __DATA.__data: 0x248

   - /usr/lib/libmecabra.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1239
-  Symbols:   3206
-  CStrings:  667
+  Functions: 1243
+  Symbols:   3215
+  CStrings:  670
 
Symbols:
+ +[JIMPreferences shouldSuppressEnglishCandidates]
+ +[JIMPreferences shouldSuppressPredictionCandidates]
+ -[JIMSession _effectiveMaxPredictionCount]
+ GCC_except_table307
+ GCC_except_table309
+ GCC_except_table69
+ GCC_except_table96
+ _CFPreferencesAppValueIsForced
+ _CFPreferencesGetAppBooleanValue
+ _JIMManagedPreferenceDisallows
+ _objc_msgSend$_effectiveMaxPredictionCount
+ _objc_msgSend$shouldSuppressEnglishCandidates
+ _objc_msgSend$shouldSuppressPredictionCandidates
- GCC_except_table306
- GCC_except_table308
- GCC_except_table68
- GCC_except_table95
CStrings:
+ "allowAutoCorrection"
+ "allowPredictiveKeyboard"
+ "com.apple.applicationaccess"
```
