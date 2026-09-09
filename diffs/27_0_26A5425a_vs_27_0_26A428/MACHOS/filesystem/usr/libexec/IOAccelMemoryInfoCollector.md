## IOAccelMemoryInfoCollector

> `/usr/libexec/IOAccelMemoryInfoCollector`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 491.0.0.0.0
-  __TEXT.__text: 0x1730
+  __TEXT.__text: 0x16f4
   __TEXT.__auth_stubs: 0x2d0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x10
   __TEXT.__cstring: 0x645
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x120
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x170
Functions:
~ sub_100000ae0 : 92 -> 80
~ sub_100000d38 -> sub_100000d2c : 596 -> 584
~ sub_100001294 -> sub_10000127c : 112 -> 100
~ sub_100001538 -> sub_100001514 : 220 -> 208
~ sub_100001e30 -> sub_100001e00 : 136 -> 124
```
