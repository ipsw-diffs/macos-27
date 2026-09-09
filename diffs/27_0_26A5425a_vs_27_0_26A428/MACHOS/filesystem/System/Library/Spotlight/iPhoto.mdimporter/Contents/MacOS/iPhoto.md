## iPhoto

> `/System/Library/Spotlight/iPhoto.mdimporter/Contents/MacOS/iPhoto`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 240.0.0.0.0
-  __TEXT.__text: 0x52f4
+  __TEXT.__text: 0x525c
   __TEXT.__auth_stubs: 0x2f0
   __TEXT.__objc_stubs: 0x500
   __TEXT.__cstring: 0xb80
   __TEXT.__const: 0x737e
   __TEXT.__objc_methname: 0x32e
-  __TEXT.__unwind_info: 0x108
+  __TEXT.__unwind_info: 0x168
   __DATA_CONST.__const: 0x398
   __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _parseFile : 88 -> 76
~ _ipiAddKeyword : 252 -> 240
~ _ipiIndexSetAddInt : 72 -> 60
~ _updateImageMetaData : 912 -> 900
~ _ipiProcessImage : 128 -> 116
~ _ipiDictionaryAddInt : 116 -> 104
~ _ipiDictionaryAddDouble : 112 -> 100
~ _ipiDictionaryAddString : 108 -> 96
~ _DeallocMetadataImporterPluginType : 92 -> 80
~ _yyparse : 3452 -> 3476
~ sub_26b4 -> sub_2660 : 124 -> 112
~ sub_2730 -> sub_26d0 : 152 -> 140
~ sub_27c8 -> sub_275c : 620 -> 612
~ sub_2a70 -> sub_29fc : 136 -> 124
~ _yy_delete_buffer : 112 -> 100
~ _yy_scan_string : 60 -> 48
```
