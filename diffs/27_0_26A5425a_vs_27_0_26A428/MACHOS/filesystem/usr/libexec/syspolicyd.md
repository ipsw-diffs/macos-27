## syspolicyd

> `/usr/libexec/syspolicyd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_security_`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 823.1.1.0.0
-  __TEXT.__text: 0xb3220
+  __TEXT.__text: 0xb0590
   __TEXT.__auth_stubs: 0x2c50
   __TEXT.__objc_stubs: 0xa5e0
   __TEXT.__init_offsets: 0x4

   __TEXT.__swift5_proto: 0x40
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x2528
+  __TEXT.__unwind_info: 0x33d0
   __TEXT.__eh_frame: 0x1b8
   __DATA_CONST.__const: 0x3c98
   __DATA_CONST.__cfstring: 0x8d00

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3594
+  Functions: 3593
   Symbols:   1065
   CStrings:  5570
 
```
