## Apply ColorSync Profile to Images

> `/System/Library/Automator/Apply ColorSync Profile to Images.action/Contents/MacOS/Apply ColorSync Profile to Images`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x25c8
+  __TEXT.__text: 0x24fc
   __TEXT.__auth_stubs: 0x500
   __TEXT.__objc_stubs: 0xc60
   __TEXT.__objc_methlist: 0x1c0

   __TEXT.__objc_classname: 0x3f
   __TEXT.__objc_methtype: 0x365
   __TEXT.__const: 0x40
-  __TEXT.__unwind_info: 0xf0
+  __TEXT.__unwind_info: 0x108
   __DATA_CONST.__cfstring: 0x220
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ -[CSProfile initWithCFPath:] : 228 -> 216
~ _profileFilter : 544 -> 532
~ -[ColorSyncProfiles awakeFromNib] : 292 -> 268
~ -[ColorSyncProfiles ConversionTypeCheckBoxAction:] : 180 -> 168
~ -[ColorSyncProfiles ProfileMenuAction:] : 316 -> 304
~ -[ColorSyncProfiles loadProfiles:] : 884 -> 860
~ _compareProfileNames : 72 -> 60
~ -[ColorSyncProfiles updateState] : 264 -> 252
~ -[ColorSyncProfiles updateProfileUI:] : 464 -> 440
~ -[ColorSyncProfiles parametersUpdated] : 736 -> 724
~ -[CSBeforeViewClass drawRect:] : 340 -> 328
~ -[CSBeforeViewClass drawBackground] : 256 -> 244
~ -[CSBeforeViewClass createCacheContext:withAlpha:] : 196 -> 184
~ -[CSBeforeViewClass drawImageToCache:displayColorSpace:filter:] : 528 -> 516
```
