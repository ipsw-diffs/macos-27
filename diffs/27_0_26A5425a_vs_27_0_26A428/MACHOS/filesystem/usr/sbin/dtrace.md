## dtrace

> `/usr/sbin/dtrace`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 416.0.3.0.0
-  __TEXT.__text: 0x3884
+  __TEXT.__text: 0x3858
   __TEXT.__auth_stubs: 0x520
   __TEXT.__const: 0x4d
   __TEXT.__cstring: 0x16cc
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__const: 0x120
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__auth_got: 0x290
Functions:
~ _main : 7240 -> 7236
~ _usage : 164 -> 152
~ _bufhandler : 2024 -> 2020
~ _dof_prune_all : 188 -> 176
~ _anon_prog : 256 -> 244
```
