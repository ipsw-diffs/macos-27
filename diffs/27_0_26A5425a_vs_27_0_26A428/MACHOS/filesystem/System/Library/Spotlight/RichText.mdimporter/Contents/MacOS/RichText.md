## RichText

> `/System/Library/Spotlight/RichText.mdimporter/Contents/MacOS/RichText`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 365.0.0.0.0
-  __TEXT.__text: 0xf58
+  __TEXT.__text: 0xf38
   __TEXT.__auth_stubs: 0x1d0
   __TEXT.__objc_stubs: 0x460
   __TEXT.__const: 0x38
   __TEXT.__gcc_except_tab: 0x60
   __TEXT.__cstring: 0x214
   __TEXT.__objc_methname: 0x279
-  __TEXT.__unwind_info: 0x90
+  __TEXT.__unwind_info: 0x98
   __DATA_CONST.__const: 0x28
   __DATA_CONST.__cfstring: 0x4a0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _GetMetadataForURL : 2552 -> 2544
~ _DeallocRichTextSnifferPluginType : 92 -> 80
~ _RichTextSnifferPluginFactory : 180 -> 168
```
