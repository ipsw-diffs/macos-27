## unzipsfx

> `/usr/bin/unzipsfx`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0xbcd4
+  __TEXT.__text: 0xbc5c
   __TEXT.__auth_stubs: 0x450
   __TEXT.__const: 0x12bb
   __TEXT.__cstring: 0x427
-  __TEXT.__unwind_info: 0x148
+  __TEXT.__unwind_info: 0x188
   __DATA_CONST.__auth_got: 0x228
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x30
Functions:
~ _main : 64 -> 52
~ _unzip : 808 -> 796
~ _uz_opts : 1884 -> 1872
~ _extract_or_test_files : 9952 -> 9920
~ _memflush : 156 -> 160
~ _open_outfile : 408 -> 396
~ _readbuf : 368 -> 364
~ _UzpMessagePrnt : 756 -> 760
~ _inflate_codes : 1556 -> 1552
~ _inflate : 3996 -> 3976
~ _huft_build : 1500 -> 1496
~ _process_zipfiles : 4196 -> 4188
~ _process_cdir_file_hdr : 772 -> 764
```
