## osacompile

> `/usr/bin/osacompile`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`

```diff

 410.1.0.0.0
-  __TEXT.__text: 0x27f8
+  __TEXT.__text: 0x27c0
   __TEXT.__auth_stubs: 0x6a0
   __TEXT.__init_offsets: 0x4
   __TEXT.__gcc_except_tab: 0x30c
   __TEXT.__cstring: 0x3f9
   __TEXT.__const: 0x1a
-  __TEXT.__unwind_info: 0x190
+  __TEXT.__unwind_info: 0x1a8
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__auth_got: 0x358
   __DATA_CONST.__got: 0x48
Functions:
~ sub_100000848 : 120 -> 108
~ sub_1000008c0 -> sub_1000008b4 : 120 -> 108
~ sub_1000019b8 -> sub_1000019a0 : 820 -> 816
~ sub_100002344 -> sub_100002328 : 196 -> 192
~ sub_100002548 -> sub_100002528 : 356 -> 344
~ sub_100002aa4 -> sub_100002a78 : 120 -> 108
```
