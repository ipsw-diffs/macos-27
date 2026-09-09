## com.apple.CharacterPicker.FileService

> `/System/Library/PrivateFrameworks/CharacterPicker.framework/Versions/Current/XPCServices/com.apple.CharacterPicker.FileService.xpc/Contents/MacOS/com.apple.CharacterPicker.FileService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 323.500.0.0.0
-  __TEXT.__text: 0x6860
+  __TEXT.__text: 0x65ec
   __TEXT.__auth_stubs: 0x6a0
   __TEXT.__objc_stubs: 0x14e0
   __TEXT.__objc_methlist: 0x45c

   __TEXT.__objc_classname: 0x6c
   __TEXT.__objc_methname: 0x1187
   __TEXT.__objc_methtype: 0x287
-  __TEXT.__unwind_info: 0x240
+  __TEXT.__unwind_info: 0x2e0
   __DATA_CONST.__const: 0x430
   __DATA_CONST.__cfstring: 0xec0
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ ___fileservice_event_handler_block_invoke : 2040 -> 2028
~ +[NSUserDefaults(EmojiUserDefaults) emojiUserDefaults] : 68 -> 56
~ ___54+[NSUserDefaults(EmojiUserDefaults) emojiUserDefaults]_block_invoke : 76 -> 64
~ -[NSUserDefaults(EmojiUserDefaults) setHasAcceptedSuggestedGenmojiOnboarding:] : 84 -> 72
~ +[NSUserDefaults(GPUserDefaults) gpUserDefaults] : 68 -> 56
~ ___48+[NSUserDefaults(GPUserDefaults) gpUserDefaults]_block_invoke : 76 -> 64
~ -[NSUserDefaults(GPUserDefaults) didShowPreReleaseWarning] : 92 -> 80
~ _SetRecentString : 120 -> 108
~ _ClearRecentStrings : 112 -> 100
~ _SetFavoritesIDArray : 124 -> 112
~ _SetLastState : 168 -> 156
~ _CreateXPCArrayFromStringArray : 364 -> 352
~ _PrepareOpeningLargeCharacterViewer : 76 -> 64
~ _EntityIDFromCharacterInfo : 308 -> 296
~ _EntityIDFromCharacterViewerItem : 244 -> 232
~ _StringFromUnicodeCodeString : 964 -> 968
~ _NormalizedSkinToneString : 336 -> 324
~ _LastUsedSkinToneString : 156 -> 144
~ _IsEmojiCategoryName : 92 -> 80
~ _IsStickersCategoryName : 112 -> 100
~ _MyFrameworkLocalizedString : 64 -> 52
~ _PreferredLocalizationOfBundle : 124 -> 112
~ _GetCategoryDataForLanguage : 224 -> 212
~ _ImageNamedInFramework : 56 -> 44
~ _ConvertPointBetweenViews : 368 -> 356
~ _LogCurrentTime : 52 -> 40
~ __LogCurrentTimeWithType_block_invoke.160 : 148 -> 136
~ ___LogCurrentTimeWithType_block_invoke_2 : 172 -> 160
~ ___copy_helper_block_e8_32o40r : 80 -> 68
~ ___destroy_helper_block_e8_32o40r : 68 -> 56
~ ___copy_helper_block_e8_32o40o : 80 -> 68
~ ___destroy_helper_block_e8_32o40o : 68 -> 56
~ _ShouldDrawPreReleaseStamp : 140 -> 128
~ +[CPKStandardCharacterEntity characterEntity] : 40 -> 28
~ +[CPKStandardCharacterEntity characterEntityWithIdentifier:] : 60 -> 48
~ -[CPKStandardCharacterEntity imageURL] : 76 -> 64
~ -[CPKStandardCharacterEntity image] : 88 -> 76
~ -[CPKStandardCharacterEntity setCharacterString:] : 124 -> 112
~ -[CPKStandardCharacterEntity setFontName:] : 72 -> 60
~ -[CPKStandardCharacterEntity setImageURL:] : 72 -> 60
~ -[CPKStandardCharacterEntity setGlyph:] : 120 -> 96
~ -[CPKStandardCharacterEntity glyphID] : 52 -> 40
~ -[CPKStandardCharacterEntity setCachedGlyph:] : 120 -> 96
~ -[CPKStandardCharacterEntity cachedGlyphID] : 52 -> 40
~ -[CPKStandardCharacterEntity setNumberOfSectionedCharacters:] : 80 -> 68
~ -[CPKStandardCharacterEntity numberOfSectionedCharacters] : 52 -> 40
~ -[CPKStandardCharacterEntity description] : 88 -> 76
~ -[CPKStandardCharacterEntity setInlineAttachmentImage:] : 88 -> 76
~ -[CPCharacterDatabase createXPCArrayForSearchString:maxCount:] : 1836 -> 1820
~ -[CPCharacterDatabase createXPCArrayForRelatedCharacters:maxCount:] : 716 -> 712
~ -[CPCharacterDatabase languageForFieldTag:] : 68 -> 56
~ -[CPCharacterDatabase tagsForLanguage:] : 68 -> 56
```
