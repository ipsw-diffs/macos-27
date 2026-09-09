## triald

> `/usr/libexec/triald`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 511.0.0.0.0
-  __TEXT.__text: 0xb84
+  __TEXT.__text: 0xb48
   __TEXT.__auth_stubs: 0x200
   __TEXT.__objc_stubs: 0x100
   __TEXT.__objc_methlist: 0x2c
Functions:
~ sub_100000d90 : 264 -> 252
~ sub_100000e98 -> sub_100000e8c : 468 -> 456
~ sub_10000106c -> sub_100001054 : 168 -> 156
~ sub_100001114 -> sub_1000010f0 : 60 -> 48
~ sub_100001150 -> sub_100001120 : 60 -> 48
```
