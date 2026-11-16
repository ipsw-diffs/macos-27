## CoreServicesUIAgent

> `/System/Library/CoreServices/CoreServicesUIAgent.app/Contents/MacOS/CoreServicesUIAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_nlcatlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-469.2.2.0.0
-  __TEXT.__text: 0x2cea4
-  __TEXT.__auth_stubs: 0xed0
+469.2.3.0.0
+  __TEXT.__text: 0x2d620
+  __TEXT.__auth_stubs: 0xf30
   __TEXT.__objc_stubs: 0x4720
   __TEXT.__init_offsets: 0x8
   __TEXT.__objc_methlist: 0x17f4
-  __TEXT.__const: 0x128
+  __TEXT.__const: 0x140
   __TEXT.__cstring: 0x3f09
-  __TEXT.__objc_methname: 0x4e64
-  __TEXT.__oslogstring: 0x1b61
+  __TEXT.__objc_methname: 0x4e7d
+  __TEXT.__oslogstring: 0x1cb7
   __TEXT.__objc_classname: 0x442
   __TEXT.__objc_methtype: 0x110a
-  __TEXT.__gcc_except_tab: 0x2044
+  __TEXT.__gcc_except_tab: 0x211c
   __TEXT.__ustring: 0x16
-  __TEXT.__unwind_info: 0xfb8
-  __DATA_CONST.__const: 0xff0
+  __TEXT.__unwind_info: 0x1000
+  __DATA_CONST.__const: 0x1010
   __DATA_CONST.__cfstring: 0x4340
   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_catlist: 0x18

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x88
-  __DATA_CONST.__objc_intobj: 0xd8
+  __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__objc_arraydata: 0x308
   __DATA_CONST.__objc_arrayobj: 0x120
   __DATA_CONST.__objc_doubleobj: 0x30
-  __DATA_CONST.__auth_got: 0x780
-  __DATA_CONST.__got: 0x608
-  __DATA.__objc_const: 0x2a88
+  __DATA_CONST.__auth_got: 0x7b0
+  __DATA_CONST.__got: 0x610
+  __DATA.__objc_const: 0x2aa8
   __DATA.__objc_selrefs: 0x16b0
-  __DATA.__objc_ivar: 0x1fc
+  __DATA.__objc_ivar: 0x200
   __DATA.__objc_data: 0x780
   __DATA.__data: 0x480
   __DATA.__bss: 0x1d8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 776
-  Symbols:   446
-  CStrings:  1914
+  Functions: 785
+  Symbols:   453
+  CStrings:  1919
 
Symbols:
+ _UTTypeData
+ __qtn_error
+ __qtn_file_apply_to_fd
+ __qtn_file_init_with_fd
+ _fcntl
+ _fstat
+ _lstat
CStrings:
+ "_locatorFD"
+ "error %@/%lli while copying quarantine properties; treating as quarantined"
+ "error %i (%{public}s) reading quarantine of %{private}s; treating as quarantined"
+ "error %i (%{public}s) reading quarantine of fd %i; treating as quarantined"
+ "error %i (%{public}s) reading quarantine of mount point %{private}s; treating as quarantined"
+ "error %lli while setting quarantine data on fd %i"
+ "internet locator quarantine: %{private}@ was replaced while awaiting approval"
+ "internet locator quarantine: message does not name an Internet Locator file"
+ "typeWithFilenameExtension:conformingToType:"
- "error %@/%lli while copying quarantine properties"
- "internet locator quarantine: %{private}@ is not an Internet Locator file"
- "internet locator quarantine: no usable locator path in message"
- "locatorIsInternetLocationFile"
```
