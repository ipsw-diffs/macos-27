## binhex

> `/usr/bin/binhex`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA.__data`

```diff

-187.0.0.0.0
-  __TEXT.__text: 0x3cb4
+188.0.0.0.0
+  __TEXT.__text: 0x3cf4
   __TEXT.__auth_stubs: 0x350
   __TEXT.__const: 0x358
   __TEXT.__cstring: 0x10a8
Functions:
~ sub_1000006b0 : 9396 -> 9440
~ sub_100003858 -> sub_100003884 : 672 -> 692
CStrings:
+ "02:34:03"
+ "Nov 10 2026"
- "01:39:08"
- "Oct 29 2026"
```
