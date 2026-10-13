## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/Versions/A/APTransport`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1005.12.1.0.0
-  __TEXT.__text: 0x8cb88
-  __TEXT.__objc_methlist: 0x1aa4
+1005.13.1.0.0
+  __TEXT.__text: 0x8cbbc
+  __TEXT.__objc_methlist: 0x1adc
   __TEXT.__const: 0x64c
   __TEXT.__gcc_except_tab: 0x844
   __TEXT.__cstring: 0x251bd

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1738
+  __DATA_CONST.__objc_selrefs: 0x1758
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x360
   __AUTH_CONST.__const: 0x38b0
   __AUTH_CONST.__cfstring: 0x5840
-  __AUTH_CONST.__objc_const: 0x2128
+  __AUTH_CONST.__objc_const: 0x2148
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__auth_got: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 4231
-  Symbols:   4682
+  Symbols:   4683
   CStrings:  3645
 
Symbols:
+ _APSIsHomeAccessory
Functions:
~ -[APBrowserBTLEManager update] : 340 -> 348
~ +[APBonjourCacheHomeKit isDeviceCacheable:] : 212 -> 228
~ __APBonjourBrowserTickleDetailedMode : 744 -> 752
~ __APBonjourBrowserSetModeInternal : 2068 -> 2088
CStrings:
+ "1005.13.1"
- "1005.12.1"
```
