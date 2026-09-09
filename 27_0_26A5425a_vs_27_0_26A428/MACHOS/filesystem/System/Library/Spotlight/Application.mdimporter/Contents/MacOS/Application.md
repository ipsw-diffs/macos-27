## Application

> `/System/Library/Spotlight/Application.mdimporter/Contents/MacOS/Application`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`

```diff

 2459.405.0.0.0
-  __TEXT.__text: 0x3ab0
+  __TEXT.__text: 0x3a40
   __TEXT.__auth_stubs: 0x860
   __TEXT.__objc_stubs: 0x600
   __TEXT.__const: 0x58
   __TEXT.__cstring: 0x8fa
   __TEXT.__ustring: 0x1f0
   __TEXT.__objc_methname: 0x3e0
-  __TEXT.__unwind_info: 0x198
+  __TEXT.__unwind_info: 0x1f8
   __DATA_CONST.__const: 0x1d8
   __DATA_CONST.__cfstring: 0x1320
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _XPCUtil_PackCFIntoArray : 160 -> 148
~ _XPCUtil_PackCFIntoDictionary : 160 -> 148
~ sub_1150 -> sub_1138 : 104 -> 92
~ _CF_RangeUnion : 32 -> 24
~ _CF_RangeIntersection : 36 -> 28
~ _MDArrayIterate : 88 -> 76
~ sub_3fe0 -> sub_3fa0 : 236 -> 224
~ sub_40cc -> sub_4080 : 96 -> 84
~ sub_412c -> sub_40d4 : 80 -> 68
~ _DeallocMetadataImporterPluginType : 92 -> 80
```
