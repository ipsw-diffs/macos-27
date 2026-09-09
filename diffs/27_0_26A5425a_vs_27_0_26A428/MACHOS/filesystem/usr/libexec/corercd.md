## corercd

> `/usr/libexec/corercd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`

```diff

 277.0.0.0.0
-  __TEXT.__text: 0x260
+  __TEXT.__text: 0x23c
   __TEXT.__auth_stubs: 0xd0
   __TEXT.__objc_stubs: 0x40
   __TEXT.__const: 0x38
Functions:
~ sub_10000099c : 80 -> 68
~ sub_1000009ec -> sub_1000009e0 : 68 -> 56
~ sub_100000a50 -> sub_100000a38 : 152 -> 140
```
