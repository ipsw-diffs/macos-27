## IOMFBDiagnose

> `/usr/bin/IOMFBDiagnose`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

-700.51.10.0.0
-  __TEXT.__text: 0x109c8
+700.51.12.0.0
+  __TEXT.__text: 0x10ab8
   __TEXT.__auth_stubs: 0x2b0
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__const: 0xb74
-  __TEXT.__cstring: 0x850d
+  __TEXT.__cstring: 0x8600
   __TEXT.__objc_methname: 0x62
-  __TEXT.__unwind_info: 0x250
-  __DATA_CONST.__const: 0xd60
+  __TEXT.__unwind_info: 0x258
+  __DATA_CONST.__const: 0xd90
   __DATA_CONST.__cfstring: 0xbe0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x160

   - /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/Versions/A/IOMobileFramebuffer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 122
+  Functions: 123
   Symbols:   56
-  CStrings:  1361
+  CStrings:  1372
 
Functions:
~ sub_100010520 : 472 -> 488
+ sub_100010708
CStrings:
+ "  Current preset: %s\n"
+ "  Currently active: %s (active table: %s)\n"
+ "  Currently active: unknown (KSF table state unavailable, error: 0x%x)\n"
+ "DBCL (factory)"
+ "EDT (factory)"
+ "Non-reference"
+ "None"
+ "PBLSCLRegion"
+ "Reference"
+ "Test gains"
+ "UBCL (user calibration)"
```
