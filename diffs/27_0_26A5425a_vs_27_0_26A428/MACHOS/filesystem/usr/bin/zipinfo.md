## zipinfo

> `/usr/bin/zipinfo`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x17114
+  __TEXT.__text: 0x17144
   __TEXT.__auth_stubs: 0x4d0
   __TEXT.__const: 0x4a99
   __TEXT.__cstring: 0x2fb4
-  __TEXT.__unwind_info: 0x1b0
+  __TEXT.__unwind_info: 0x208
   __DATA_CONST.__const: 0x9e0
   __DATA_CONST.__auth_got: 0x268
   __DATA_CONST.__got: 0x28
Functions:
~ _main : 64 -> 52
~ _uz_opts : 2116 -> 2104
~ _show_version_info : 1492 -> 1480
~ _testkey : 380 -> 376
~ _explode_lit : 1928 -> 1920
~ _explode_nolit : 1720 -> 1712
~ _extract_or_test_files : 14932 -> 15220
~ _memflush : 156 -> 160
~ _extract_izvms_block : 400 -> 384
~ _open_outfile : 408 -> 396
~ _readbuf : 368 -> 364
~ _UzpMessagePrnt : 756 -> 760
~ _inflate_codes : 1556 -> 1552
~ _inflate : 4372 -> 4312
~ _huft_build : 1500 -> 1496
~ _list_files : 2520 -> 2516
~ _fnprint : 148 -> 136
~ _process_zipfiles : 1648 -> 1644
~ _do_seekable : 5640 -> 5632
~ _process_cdir_file_hdr : 772 -> 764
~ _zi_opts : 1064 -> 1052
~ _zi_end_central : 1300 -> 1288
~ _zipinfo : 14760 -> 14752
~ _zi_showMacTypeCreator : 632 -> 620
~ _version : 196 -> 184
```
