## sha1sum

> `/sbin/sha1sum`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 199.0.0.0.0
-  __TEXT.__text: 0x1628
+  __TEXT.__text: 0x1604
   __TEXT.__auth_stubs: 0x200
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0x125e
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0x90
   __DATA_CONST.__const: 0x680
   __DATA_CONST.__auth_got: 0x100
   __DATA_CONST.__got: 0x30
Functions:
~ sub_100001968 : 596 -> 584
~ sub_100001bc0 -> sub_100001bb4 : 36 -> 24
~ sub_100001be4 -> sub_100001bcc : 28 -> 16
```
