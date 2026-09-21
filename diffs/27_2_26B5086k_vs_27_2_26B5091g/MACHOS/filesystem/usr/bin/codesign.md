## codesign

> `/usr/bin/codesign`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__dof_security_`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

 135.40.5.0.0
-  __TEXT.__text: 0x23720
+  __TEXT.__text: 0x2371c
   __TEXT.__auth_stubs: 0x1680
   __TEXT.__objc_stubs: 0xcc0
   __TEXT.__init_offsets: 0xc
Functions:
~ sub_100019ab0 : 208 -> 204
```
