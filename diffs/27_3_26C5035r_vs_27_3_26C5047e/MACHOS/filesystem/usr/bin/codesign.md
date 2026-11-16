## codesign

> `/usr/bin/codesign`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__dof_security_`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_dupclass`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

 135.40.5.0.0
-  __TEXT.__text: 0x2371c
+  __TEXT.__text: 0x2374c
   __TEXT.__auth_stubs: 0x1680
   __TEXT.__objc_stubs: 0xcc0
   __TEXT.__init_offsets: 0xc
Functions:
~ sub_10000f0c8 : 260 -> 284
~ sub_100011834 -> sub_10001184c : 252 -> 276
```
