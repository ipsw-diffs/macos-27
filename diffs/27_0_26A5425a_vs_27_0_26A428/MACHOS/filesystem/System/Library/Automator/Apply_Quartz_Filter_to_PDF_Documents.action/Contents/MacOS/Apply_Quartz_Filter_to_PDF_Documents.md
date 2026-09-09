## Apply Quartz Filter to PDF Documents

> `/System/Library/Automator/Apply Quartz Filter to PDF Documents.action/Contents/MacOS/Apply Quartz Filter to PDF Documents`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x2740
+  __TEXT.__text: 0x265c
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__objc_stubs: 0xea0
   __TEXT.__objc_methlist: 0x1b4

   __TEXT.__objc_classname: 0x3c
   __TEXT.__objc_methtype: 0x2d7
   __TEXT.__const: 0x10
-  __TEXT.__unwind_info: 0xf0
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__cfstring: 0x2a0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ -[PDF_Quartz_Filters awakeFromNib] : 496 -> 484
~ -[PDF_Quartz_Filters opened] : 100 -> 88
~ -[PDF_Quartz_Filters FilterMenuAction:] : 184 -> 172
~ -[PDF_Quartz_Filters loadFilters:] : 604 -> 580
~ _compareFilterNames : 76 -> 64
~ -[PDF_Quartz_Filters updateState] : 168 -> 156
~ -[PDF_Quartz_Filters updateFilterUI] : 240 -> 228
~ -[PDF_Quartz_Filters updateFilterMenuFromFilterView] : 236 -> 224
~ -[PDF_Quartz_Filters parametersUpdated] : 716 -> 704
~ -[PDF_Quartz_Filters quartzFilterManager:didSelectFilter:] : 96 -> 84
~ -[PDF_Quartz_Filters filterAddNotification:] : 236 -> 224
~ -[PDF_Quartz_Filters filterRemoveNotification:] : 356 -> 344
~ -[PDF_Quartz_Filters setCollapsed:] : 140 -> 128
~ -[PDF_Quartz_Filters help:] : 68 -> 56
~ -[PDFQFBeforeViewClass drawRect:] : 332 -> 320
~ -[PDFQFBeforeViewClass drawBackground] : 256 -> 244
~ -[PDFQFBeforeViewClass createCacheContext:] : 184 -> 172
~ -[PDFQFBeforeViewClass drawPDFPageToCache:displayColorSpace:filter:] : 504 -> 492
```
