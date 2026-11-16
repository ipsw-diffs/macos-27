## meminfo

> `/usr/bin/meminfo`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1071.40.9.0.0
-  __TEXT.__text: 0x136a8
+  __TEXT.__text: 0x137f4
   __TEXT.__auth_stubs: 0x9d0
   __TEXT.__objc_stubs: 0x100
   __TEXT.__const: 0x9b4
Functions:
~ sub_100004ca4 : 276 -> 312
~ sub_100004db8 -> sub_100004ddc : 284 -> 316
~ sub_10000792c -> sub_100007970 : 260 -> 284
~ sub_100007a30 -> sub_100007a8c : 276 -> 312
~ sub_100007b44 -> sub_100007bc4 : 260 -> 284
~ sub_100007c48 -> sub_100007ce0 : 260 -> 284
~ sub_100007d4c -> sub_100007dfc : 300 -> 324
~ sub_10000ef5c -> sub_10000f024 : 252 -> 276
~ sub_10000f990 -> sub_10000fa70 : 260 -> 284
~ sub_10000fa94 -> sub_10000fb8c : 276 -> 312
~ sub_10000fba8 -> sub_10000fcc4 : 300 -> 324
~ sub_10000fcd4 -> sub_10000fe08 : 260 -> 284
```
