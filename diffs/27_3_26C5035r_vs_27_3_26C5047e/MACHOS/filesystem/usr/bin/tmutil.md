## tmutil

> `/usr/bin/tmutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
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

-2616.0.0.0.0
-  __TEXT.__text: 0x23ca4
+2616.3.1.0.0
+  __TEXT.__text: 0x23dcc
   __TEXT.__auth_stubs: 0x1070
   __TEXT.__objc_stubs: 0x3540
   __TEXT.__objc_methlist: 0xc64
Functions:
~ sub_100017c58 : 132 -> 156
~ sub_100018a04 -> sub_100018a1c : 216 -> 240
~ sub_1000236e8 -> sub_100023718 : 432 -> 460
~ sub_100023898 -> sub_1000238e4 : 316 -> 352
~ sub_1000239d4 -> sub_100023a44 : 316 -> 352
~ sub_100023b10 -> sub_100023ba4 : 316 -> 352
~ sub_100024620 -> sub_1000246d8 : 252 -> 276
~ sub_100024730 -> sub_100024800 : 456 -> 484
~ sub_1000248f8 -> sub_1000249e4 : 260 -> 284
~ sub_100024abc -> sub_100024bc0 : 984 -> 1020
CStrings:
+ "Nov 10 2026"
- "Oct 30 2026"
```
