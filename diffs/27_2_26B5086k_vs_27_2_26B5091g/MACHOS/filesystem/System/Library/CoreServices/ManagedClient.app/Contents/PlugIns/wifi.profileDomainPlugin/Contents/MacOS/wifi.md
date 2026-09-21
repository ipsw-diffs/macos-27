## wifi

> `/System/Library/CoreServices/ManagedClient.app/Contents/PlugIns/wifi.profileDomainPlugin/Contents/MacOS/wifi`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-1847.40.3.0.0
-  __TEXT.__text: 0x11860
-  __TEXT.__auth_stubs: 0xa30
+1847.40.4.0.0
+  __TEXT.__text: 0x11a34
+  __TEXT.__auth_stubs: 0xa40
   __TEXT.__objc_stubs: 0x1200
   __TEXT.__objc_methlist: 0x1ac
-  __TEXT.__cstring: 0x5688
+  __TEXT.__cstring: 0x57b0
   __TEXT.__const: 0x118
-  __TEXT.__oslogstring: 0x3b9c
+  __TEXT.__oslogstring: 0x3ca3
   __TEXT.__gcc_except_tab: 0x12c
   __TEXT.__objc_methname: 0x10e7
   __TEXT.__objc_classname: 0x39
   __TEXT.__objc_methtype: 0x26c
   __TEXT.__unwind_info: 0x4b8
   __DATA_CONST.__const: 0x150
-  __DATA_CONST.__cfstring: 0x19a0
+  __DATA_CONST.__cfstring: 0x19c0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__auth_got: 0x528
+  __DATA_CONST.__auth_got: 0x530
   __DATA_CONST.__got: 0x1a0
   __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x90

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 262
-  Symbols:   224
-  CStrings:  695
+  Symbols:   225
+  CStrings:  699
 
Symbols:
+ _object_getClassName
Functions:
~ sub_2ae8 : 808 -> 1276
CStrings:
+ "EAPClientConfiguration is present but is not a dictionary; rejecting payload."
+ "TLSRequiresNIAPTLSPackageVersion"
+ "TLSRequiresNIAPTLSPackageVersion present in EAPClientConfiguration but is not a string (got %s); rejecting payload."
+ "TLSRequiresNIAPTLSPackageVersion string is empty; rejecting payload."
```
