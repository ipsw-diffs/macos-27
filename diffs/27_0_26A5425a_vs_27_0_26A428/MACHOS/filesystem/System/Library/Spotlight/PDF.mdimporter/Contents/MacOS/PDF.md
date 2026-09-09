## PDF

> `/System/Library/Spotlight/PDF.mdimporter/Contents/MacOS/PDF`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 240.0.0.0.0
-  __TEXT.__text: 0x1030
+  __TEXT.__text: 0xffc
   __TEXT.__auth_stubs: 0x1e0
   __TEXT.__objc_stubs: 0x400
   __TEXT.__objc_methlist: 0x2c

   __TEXT.__objc_classname: 0x13
   __TEXT.__objc_methtype: 0x2e
   __TEXT.__objc_methname: 0x2b7
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xb0
   __DATA_CONST.__const: 0x58
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ _DeallocMetadataImporterPluginType : 92 -> 80
~ -[PDFImportExtension performOCRWithPDFDocument:existingAttributes:options:] : 1072 -> 1056
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
```
