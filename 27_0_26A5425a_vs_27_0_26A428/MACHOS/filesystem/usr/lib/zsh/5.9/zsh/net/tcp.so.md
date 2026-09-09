## tcp.so

> `/usr/lib/zsh/5.9/zsh/net/tcp.so`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0xc04
+  __TEXT.__text: 0xbe0
   __TEXT.__auth_stubs: 0x2a0
   __TEXT.__cstring: 0x351
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__auth_got: 0x150
   __DATA_CONST.__got: 0x10
   __DATA.__data: 0x80
Functions:
~ sub_6ec : 100 -> 88
~ _tcp_connect : 140 -> 128
~ _cleanup_ : 132 -> 120
```
