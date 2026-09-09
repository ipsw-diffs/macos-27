## kextlibs

> `/usr/sbin/kextlibs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 784.0.0.0.0
-  __TEXT.__text: 0x1ab8
+  __TEXT.__text: 0x1a80
   __TEXT.__auth_stubs: 0x380
   __TEXT.__cstring: 0x933
-  __TEXT.__unwind_info: 0x88
+  __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x1c0
Functions:
~ sub_100000828 : 1440 -> 1444
~ sub_10000165c -> sub_100001660 : 728 -> 716
~ sub_1000019e4 -> sub_1000019dc : 364 -> 352
~ sub_100001b50 -> sub_100001b3c : 112 -> 100
~ sub_100001de0 -> sub_100001dc0 : 104 -> 92
~ sub_1000021c4 -> sub_100002198 : 104 -> 92
```
