## spctl

> `/usr/sbin/spctl`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_dupclass`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 823.1.1.0.0
-  __TEXT.__text: 0xc64c
+  __TEXT.__text: 0xc350
   __TEXT.__auth_stubs: 0xa40
   __TEXT.__objc_stubs: 0x10a0
   __TEXT.__init_offsets: 0x4

   __TEXT.__gcc_except_tab: 0x5fc
   __TEXT.__dlopen_cstrs: 0x62
   __TEXT.__dof_security_: 0x28e
-  __TEXT.__unwind_info: 0x518
+  __TEXT.__unwind_info: 0x678
   __DATA_CONST.__const: 0xc88
   __DATA_CONST.__cfstring: 0xda0
   __DATA_CONST.__objc_classlist: 0x68
```
