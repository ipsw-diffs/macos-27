## com.apple.fskit.exfat

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.exfat.appex/Contents/MacOS/com.apple.fskit.exfat`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 561.0.3.0.0
-  __TEXT.__text: 0x12bfc
+  __TEXT.__text: 0x12a50
   __TEXT.__auth_stubs: 0x8b0
   __TEXT.__objc_stubs: 0x800
   __TEXT.__objc_methlist: 0x204

   __TEXT.__objc_methname: 0x741
   __TEXT.__objc_classname: 0x5f
   __TEXT.__objc_methtype: 0x233
-  __TEXT.__unwind_info: 0x320
+  __TEXT.__unwind_info: 0x478
   __DATA_CONST.__const: 0x450
   __DATA_CONST.__cfstring: 0x3e0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ _CONV_UTF8ToUnistr255 : 1368 -> 1372
~ sub_1000014a0 -> sub_1000014a4 : 148 -> 156
~ _CONV_DuplicateName : 128 -> 116
~ _fsck_exfat_cache_dispose : 200 -> 188
~ _fsck_exfat_cache_get_cluster : 80 -> 68
~ _fsck_exfat_upcase_replace : 696 -> 692
~ _fsck_exfat_dir_cluster_cache_dispose_thread : 188 -> 176
~ _fsck_exfat_bitmap_allocate : 764 -> 760
~ sub_100004874 -> sub_100004848 : 524 -> 516
~ _fsck_exfat_bitmap_free : 740 -> 736
~ _fsck_exfat_bitmap_verify : 2296 -> 2292
~ _fsck_exfat_resize_chain : 168 -> 156
~ _fsck_exfat_iter_dir_entries : 740 -> 736
~ _CFStringCopyFilenameExtension : 192 -> 168
~ sub_100009818 -> sub_1000097b4 : 188 -> 176
~ sub_1000098d4 -> sub_100009864 : 96 -> 84
~ sub_100009934 -> sub_1000098b8 : 80 -> 68
~ sub_1000099a4 -> sub_10000991c : 80 -> 68
~ sub_1000099f4 -> sub_100009960 : 68 -> 56
~ _format_buf_zero : 200 -> 196
~ _format_buf_write : 240 -> 236
~ _exfat_format_defaults : 496 -> 488
~ _upcase_write : 100 -> 88
~ _root_write : 304 -> 292
~ _localizeFSCKMessage : 376 -> 364
~ sub_10000eb10 -> sub_10000ea3c : 72 -> 60
~ sub_10000eb58 -> sub_10000ea78 : 64 -> 52
~ _localizeNewFSMessage : 432 -> 420
~ sub_10000f030 -> sub_10000ef38 : 116 -> 104
~ sub_10000f0a4 -> sub_10000efa0 : 252 -> 240
~ sub_1000100ac -> sub_10000ff9c : 192 -> 180
~ sub_10001016c -> sub_100010050 : 96 -> 84
~ sub_1000101cc -> sub_1000100a4 : 80 -> 68
~ sub_10001021c -> sub_1000100e8 : 192 -> 180
~ sub_1000102dc -> sub_10001019c : 1412 -> 1400
~ sub_100010d84 -> sub_100010c38 : 80 -> 68
~ sub_100010dd4 -> sub_100010c7c : 72 -> 60
~ sub_100010e1c -> sub_100010cb8 : 2756 -> 2744
~ sub_100011f4c -> sub_100011ddc : 88 -> 76
~ sub_100011fa4 -> sub_100011e28 : 76 -> 64
~ sub_100012730 -> sub_1000125a8 : 132 -> 120
~ sub_1000127b4 -> sub_100012620 : 80 -> 68
~ sub_100012804 -> sub_100012664 : 68 -> 56
```
