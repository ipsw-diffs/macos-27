## GameCenterUI

> `/System/Library/PrivateFrameworks/GameCenterUI.framework/Versions/A/GameCenterUI`

```diff

-821.1.8.0.0
-  __TEXT.__text: 0x407914
-  __TEXT.__objc_methlist: 0x19a78
+821.1.11.0.0
+  __TEXT.__text: 0x407c28
+  __TEXT.__objc_methlist: 0x19a98
   __TEXT.__const: 0x24894
   __TEXT.__cstring: 0x14fd0
   __TEXT.__gcc_except_tab: 0x1570
-  __TEXT.__oslogstring: 0x73c7
+  __TEXT.__oslogstring: 0x74e7
   __TEXT.__ustring: 0xa
   __TEXT.__constg_swiftt: 0xe938
   __TEXT.__swift5_typeref: 0x24506

   __TEXT.__swift_as_ret: 0x214
   __TEXT.__swift_as_cont: 0x580
   __TEXT.__swift5_mpenum: 0xe0
-  __TEXT.__unwind_info: 0x153d8
+  __TEXT.__unwind_info: 0x153e8
   __TEXT.__eh_frame: 0x7f3c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist2: 0x18
   __DATA_CONST.__objc_protolist: 0x370
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xcaa0
+  __DATA_CONST.__objc_selrefs: 0xcac0
   __DATA_CONST.__objc_protorefs: 0x130
   __DATA_CONST.__objc_superrefs: 0x618
   __DATA_CONST.__objc_arraydata: 0x388
   __DATA_CONST.__got: 0x28b8
   __AUTH_CONST.__const: 0x1e490
   __AUTH_CONST.__cfstring: 0x9180
-  __AUTH_CONST.__objc_const: 0x42fe0
+  __AUTH_CONST.__objc_const: 0x42ff0
   __AUTH_CONST.__objc_intobj: 0x810
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_dictobj: 0x78

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 30039
-  Symbols:   22713
-  CStrings:  2711
+  Functions: 30042
+  Symbols:   22721
+  CStrings:  2713
 
Symbols:
+ -[GKComposeRecipientView setShowsAddRecipientButton:]
+ -[GKComposeRecipientView showsAddRecipientButton]
+ -[GKDashboardMultiplayerPickerViewController updateAddRecipientButtonVisibility:]
+ -[GKLeaderboardScoreDataSource hasMoreEntriesToLoad]
+ GCC_except_table66
+ GCC_except_table70
+ GCC_except_table82
+ OBJC_IVAR_$_GKComposeRecipientView._showsAddRecipientButton
+ _objc_msgSend$hasMoreEntriesToLoad
+ _objc_msgSend$setShowsAddRecipientButton:
+ _objc_msgSend$showsAddRecipientButton
+ _objc_msgSend$updateAddRecipientButtonVisibility:
- -[GKDashboardMultiplayerPickerViewController setExcludesContacts:]
- GCC_except_table65
- GCC_except_table81
- OBJC_IVAR_$_GKDashboardMultiplayerPickerViewController._excludesContacts
CStrings:
+ "Not forming contact from picked contact, since contacts are excluded. GKPreferences.shared.multiplayerAllowedPlayerType is set to: %@, pickerOrigin: %@"
+ "Not presenting contact picker, since contacts are excluded. GKPreferences.shared.multiplayerAllowedPlayerType is set to: %@, pickerOrigin: %@"
```
