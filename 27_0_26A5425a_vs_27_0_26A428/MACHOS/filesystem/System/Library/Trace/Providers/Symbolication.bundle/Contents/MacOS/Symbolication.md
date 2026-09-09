## Symbolication

> `/System/Library/Trace/Providers/Symbolication.bundle/Contents/MacOS/Symbolication`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 206.0.0.0.0
-  __TEXT.__text: 0xe50
+  __TEXT.__text: 0xe14
   __TEXT.__auth_stubs: 0x1b0
   __TEXT.__objc_stubs: 0x180
   __TEXT.__objc_methlist: 0x13c
Functions:
~ sub_d5c : 100 -> 88
~ sub_fac -> sub_fa0 : 124 -> 112
~ sub_1044 -> sub_102c : 264 -> 252
~ sub_1948 -> sub_1924 : 144 -> 132
~ sub_1a48 -> sub_1a18 : 68 -> 56
```
