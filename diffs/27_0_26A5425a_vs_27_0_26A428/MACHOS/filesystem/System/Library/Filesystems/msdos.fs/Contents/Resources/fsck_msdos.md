## fsck_msdos

> `/System/Library/Filesystems/msdos.fs/Contents/Resources/fsck_msdos`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 845.0.3.0.1
-  __TEXT.__text: 0x6f18
+  __TEXT.__text: 0x6eec
   __TEXT.__auth_stubs: 0x210
   __TEXT.__const: 0x20
   __TEXT.__cstring: 0x1312
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__auth_got: 0x108
   __DATA_CONST.__got: 0x40
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_100001cd4 : 32 -> 20
~ sub_100001cf4 -> sub_100001ce8 : 716 -> 712
~ sub_1000062b0 -> sub_1000062a0 : 208 -> 196
~ sub_100006984 -> sub_100006968 : 152 -> 140
~ sub_100006de8 -> sub_100006dc0 : 940 -> 936
```
