## gunzip

> `/usr/bin/gunzip`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x588c
+  __TEXT.__text: 0x5850
   __TEXT.__auth_stubs: 0x5e0
   __TEXT.__const: 0x67d
   __TEXT.__cstring: 0x1058
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x180
   __DATA_CONST.__const: 0x2a0
   __DATA_CONST.__auth_got: 0x2f0
   __DATA_CONST.__got: 0x30
Functions:
~ _handle_stdout : 348 -> 336
~ _got_sigint : 80 -> 68
~ _zdopen : 232 -> 220
~ _unlz : 3072 -> 3084
~ _print_verbage : 204 -> 192
~ _print_test : 188 -> 176
~ _write_retry : 124 -> 120
~ _zread : 1344 -> 1336
```
