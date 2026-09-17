## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferAgent.framework/Versions/A/IMTransferAgent`

```diff

-1491.100.1.1.11
-  __TEXT.__text: 0x19984
+1491.200.63.0.0
+  __TEXT.__text: 0x19a98
   __TEXT.__objc_methlist: 0xa84
   __TEXT.__const: 0x118
-  __TEXT.__gcc_except_tab: 0x1734
+  __TEXT.__gcc_except_tab: 0x1754
   __TEXT.__cstring: 0xbd8
-  __TEXT.__oslogstring: 0x2a85
+  __TEXT.__oslogstring: 0x2ab5
   __TEXT.__unwind_info: 0x5c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd68
+  __DATA_CONST.__objc_selrefs: 0xd78
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x378

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 302
-  Symbols:   231
-  CStrings:  354
+  Symbols:   232
+  CStrings:  355
 
Symbols:
+ _IMStringFromCommSafetyEnablementGroup
Functions:
~ sub_200d2b36c -> sub_201b3036c : 2640 -> 2824
~ sub_200d2becc -> sub_201b30f84 : 1240 -> 1248
~ sub_200d2c3a4 -> sub_201b31464 : 540 -> 544
~ sub_200d2f104 -> sub_201b341c8 : 1168 -> 1176
~ sub_200d36cbc -> sub_201b3bd88 : 5876 -> 5948
CStrings:
+ "About to construct the nickname with contentSafetyEnablementGroup: %@"
+ "Avatar image safety check was skipped, comm safety check group setting: %@. Creating IMNicknameAvatarImage."
+ "Download %@ file size %llu -> request priority %ld"
+ "Wallpaper safety check was skipped, comm safety check group setting: %@. Creating IMWallpaper."
- "About to construct the nickname with contentSafetyEnablementGroup: %ld"
- "Avatar image safety check was skipped, comm safety check group setting: %ld. Creating IMNicknameAvatarImage."
- "Wallpaper safety check was skipped, comm safety check group setting: %ld. Creating IMWallpaper."
```
