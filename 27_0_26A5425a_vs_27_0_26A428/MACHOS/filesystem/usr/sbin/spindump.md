## spindump

> `/usr/sbin/spindump`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 448.0.0.0.0
-  __TEXT.__text: 0x10ee70
+  __TEXT.__text: 0x10e08c
   __TEXT.__auth_stubs: 0x1580
   __TEXT.__objc_stubs: 0x4bc0
   __TEXT.__objc_methlist: 0xce0

   __TEXT.__objc_methtype: 0x596
   __TEXT.__gcc_except_tab: 0x47cc
   __TEXT.__objc_methname: 0x4a11
-  __TEXT.__unwind_info: 0x1460
+  __TEXT.__unwind_info: 0x2620
   __DATA_CONST.__const: 0x2190
   __DATA_CONST.__cfstring: 0xdb80
   __DATA_CONST.__objc_classlist: 0x98

   - /usr/lib/libsystemstats.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2773
+  Functions: 2769
   Symbols:   458
   CStrings:  5195
 
```
