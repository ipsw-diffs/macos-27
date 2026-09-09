## CopyHFSMeta

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/CopyHFSMeta`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 751.0.0.0.0
-  __TEXT.__text: 0x38ac
+  __TEXT.__text: 0x3874
   __TEXT.__auth_stubs: 0x3b0
   __TEXT.__const: 0x50
   __TEXT.__cstring: 0x139a
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0x108
   __DATA_CONST.__const: 0x80
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__auth_got: 0x1d8
Functions:
~ sub_100001360 : 212 -> 200
~ sub_100001468 -> sub_10000145c : 1144 -> 1136
~ sub_100001fec -> sub_100001fd8 : 836 -> 832
~ sub_100002330 -> sub_100002318 : 416 -> 412
~ sub_100002e30 -> sub_100002e14 : 1256 -> 1244
~ sub_10000367c -> sub_100003654 : 256 -> 240
```
