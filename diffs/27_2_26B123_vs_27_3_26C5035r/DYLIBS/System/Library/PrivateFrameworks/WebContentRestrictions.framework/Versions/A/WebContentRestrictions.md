## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/Versions/A/WebContentRestrictions`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-75.0.0.0.0
-  __TEXT.__text: 0x11088
-  __TEXT.__objc_methlist: 0xc60
+79.0.0.0.0
+  __TEXT.__text: 0x110a8
+  __TEXT.__objc_methlist: 0xc90
   __TEXT.__const: 0x670
   __TEXT.__cstring: 0x15d1
   __TEXT.__gcc_except_tab: 0x1cc

   __DATA_CONST.__objc_classlist: 0x78
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8c8
+  __DATA_CONST.__objc_selrefs: 0x8e8
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__objc_arraydata: 0x78
   __DATA_CONST.__got: 0x1b0
   __AUTH_CONST.__const: 0x669
   __AUTH_CONST.__cfstring: 0x1920
-  __AUTH_CONST.__objc_const: 0x1570
+  __AUTH_CONST.__objc_const: 0x15d0
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__auth_got: 0x4e8
   __AUTH.__objc_data: 0x4a0
   __AUTH.__data: 0x168
-  __DATA.__objc_ivar: 0xd0
+  __DATA.__objc_ivar: 0xd8
   __DATA.__data: 0x2a8
   __DATA.__bss: 0x690
   __DATA_DIRTY.__objc_data: 0x50

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 441
-  Symbols:   1282
+  Functions: 445
+  Symbols:   1288
   CStrings:  266
 
Symbols:
+ -[WCRBrowserEngineClient allowListAuthenticationInFlight]
+ -[WCRBrowserEngineClient allowListPINEntryPresented]
+ -[WCRBrowserEngineClient setAllowListAuthenticationInFlight:]
+ -[WCRBrowserEngineClient setAllowListPINEntryPresented:]
+ _OBJC_IVAR_$_WCRBrowserEngineClient._allowListAuthenticationInFlight
+ _OBJC_IVAR_$_WCRBrowserEngineClient._allowListPINEntryPresented
CStrings:
+ "WCRAuthenticationSites-2026-09-25.plist"
- "WCRAuthenticationSites-2026-07-19.plist"
```
