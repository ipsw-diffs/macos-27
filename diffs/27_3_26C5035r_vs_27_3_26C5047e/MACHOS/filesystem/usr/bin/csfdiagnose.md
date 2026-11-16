## csfdiagnose

> `/usr/bin/csfdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 301.24.2.1.0
-  __TEXT.__text: 0x15028
+  __TEXT.__text: 0x150b0
   __TEXT.__auth_stubs: 0xb20
   __TEXT.__objc_stubs: 0x180
   __TEXT.__const: 0x15a2
Functions:
~ sub_100009810 : 1060 -> 1076
~ sub_100010784 -> sub_100010794 : 276 -> 312
~ sub_100010898 -> sub_1000108cc : 276 -> 312
~ sub_1000109ac -> sub_100010a04 : 260 -> 284
~ sub_100010c3c -> sub_100010cac : 260 -> 284
```
