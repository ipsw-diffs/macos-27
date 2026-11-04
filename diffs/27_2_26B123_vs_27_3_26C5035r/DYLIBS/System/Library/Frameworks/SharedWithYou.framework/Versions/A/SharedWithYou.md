## SharedWithYou

> `/System/Library/Frameworks/SharedWithYou.framework/Versions/A/SharedWithYou`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-217.200.51.0.0
-  __TEXT.__text: 0x3d5ac
-  __TEXT.__objc_methlist: 0x1fb4
-  __TEXT.__const: 0x1cb0
+217.300.22.0.0
+  __TEXT.__text: 0x3e5f0
+  __TEXT.__objc_methlist: 0x20ec
+  __TEXT.__const: 0x1ca8
   __TEXT.__cstring: 0x18f8
-  __TEXT.__oslogstring: 0x2697
+  __TEXT.__oslogstring: 0x26d7
   __TEXT.__gcc_except_tab: 0x41c
   __TEXT.__dlopen_cstrs: 0x54
   __TEXT.__constg_swiftt: 0x748

   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x14
-  __TEXT.__unwind_info: 0x1500
+  __TEXT.__unwind_info: 0x15c0
   __TEXT.__eh_frame: 0x318
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x340
-  __DATA_CONST.__objc_classlist: 0x120
+  __DATA_CONST.__const: 0x380
+  __DATA_CONST.__objc_classlist: 0x128
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x108
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1538
+  __DATA_CONST.__objc_selrefs: 0x1558
   __DATA_CONST.__objc_protorefs: 0x58
-  __DATA_CONST.__objc_superrefs: 0xa8
+  __DATA_CONST.__objc_superrefs: 0xb0
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x6f8
   __AUTH_CONST.__const: 0x1570
   __AUTH_CONST.__cfstring: 0x900
-  __AUTH_CONST.__objc_const: 0x3a60
+  __AUTH_CONST.__objc_const: 0x3c50
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0xbe0
-  __AUTH.__objc_data: 0xce8
+  __AUTH.__objc_data: 0xd38
   __AUTH.__data: 0x2b0
-  __DATA.__objc_ivar: 0x140
+  __DATA.__objc_ivar: 0x148
   __DATA.__data: 0x13d8
   __DATA.__bss: 0x1110
   __DATA.__common: 0x58

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1566
-  Symbols:   2184
-  CStrings:  318
+  Functions: 1618
+  Symbols:   2221
+  CStrings:  319
 
Symbols:
+ -[SWCollaborationToolbarItem .cxx_destruct]
+ -[SWCollaborationToolbarItem activeParticipantCount]
+ -[SWCollaborationToolbarItem collaborationButtonView]
+ -[SWCollaborationToolbarItem detailViewListContent]
+ -[SWCollaborationToolbarItem dismissPopoverAnimated:completion:]
+ -[SWCollaborationToolbarItem initWithCollaborationButtonView:]
+ -[SWCollaborationToolbarItem initWithItemProvider:]
+ -[SWCollaborationToolbarItem manageButtonTitle]
+ -[SWCollaborationToolbarItem pendingAccessRequestsCount]
+ -[SWCollaborationToolbarItem setActiveParticipantCount:]
+ -[SWCollaborationToolbarItem setCollaborationButtonView:]
+ -[SWCollaborationToolbarItem setDetailViewListContent:]
+ -[SWCollaborationToolbarItem setManageButtonTitle:]
+ -[SWCollaborationToolbarItem setPendingAccessRequestsCount:]
+ -[SWCollaborationToolbarItem setShowManageButton:]
+ -[SWCollaborationToolbarItem setShowsParticipantCount:]
+ -[SWCollaborationToolbarItem showManageButton]
+ -[SWCollaborationToolbarItem showsParticipantCount]
+ -[_SWCollaborationDetailViewController manageButtonTitle]
+ -[_SWCollaborationDetailViewController setTypeErasedListContentView:]
+ -[_SWCollaborationDetailViewController showManageButton]
+ -[_SWCollaborationDetailViewController typeErasedListContentView]
+ _OBJC_CLASS_$_SWCollaborationToolbarItem
+ _OBJC_IVAR_$_SWCollaborationToolbarItem._collaborationButtonView
+ _OBJC_IVAR_$__SWCollaborationDetailViewController._typeErasedListContentView
+ _OBJC_METACLASS_$_SWCollaborationToolbarItem
+ __OBJC_$_INSTANCE_METHODS_SWCollaborationToolbarItem
+ __OBJC_$_INSTANCE_VARIABLES_SWCollaborationToolbarItem
+ __OBJC_$_PROP_LIST_SWCollaborationToolbarItem
+ __OBJC_CLASS_RO_$_SWCollaborationToolbarItem
+ __OBJC_METACLASS_RO_$_SWCollaborationToolbarItem
+ _keypath_get.26Tm
+ _keypath_get.32Tm
+ _keypath_get.38Tm
+ _keypath_get_selector_listContentView
+ _keypath_set.33Tm
+ _keypath_set.39Tm
+ _objc_msgSend$detailViewListContent
+ _objc_msgSend$listContentView
+ _objc_msgSend$setTypeErasedListContentView:
+ _objc_msgSend$showManageButton
+ _objc_msgSend$typeErasedListContentView
- _keypath_get.22Tm
- _keypath_get.30Tm
- _keypath_get.36Tm
- _keypath_set.31Tm
- _keypath_set.37Tm
CStrings:
+ "[SWCollaboration] toolbarItem API pendingAccessRequestsCount=%ld"
```
