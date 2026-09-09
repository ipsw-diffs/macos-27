## DumpPanicRecoveryOS

> `/usr/libexec/DumpPanicRecoveryOS`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 37.0.1.0.0
-  __TEXT.__text: 0x28410
+  __TEXT.__text: 0x28050
   __TEXT.__auth_stubs: 0xbb0
   __TEXT.__objc_stubs: 0x20c0
   __TEXT.__objc_methlist: 0x76c

   __TEXT.__objc_classname: 0xe9
   __TEXT.__objc_methtype: 0x540
   __TEXT.__gcc_except_tab: 0xb38
-  __TEXT.__unwind_info: 0x850
+  __TEXT.__unwind_info: 0xce8
   __DATA_CONST.__const: 0x690
   __DATA_CONST.__cfstring: 0x2140
   __DATA_CONST.__objc_classlist: 0x60

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 829
+  Functions: 830
   Symbols:   266
   CStrings:  1244
 
```
