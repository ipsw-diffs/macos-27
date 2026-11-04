## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-655.1.14.1.0
-  __TEXT.__text: 0x1024f0
-  __TEXT.__objc_methlist: 0xa438
-  __TEXT.__const: 0x3558
+655.2.7.0.0
+  __TEXT.__text: 0x103648
+  __TEXT.__objc_methlist: 0xa468
+  __TEXT.__const: 0x3568
   __TEXT.__cstring: 0xa82c
-  __TEXT.__oslogstring: 0xc29a
-  __TEXT.__gcc_except_tab: 0x1b44
-  __TEXT.__constg_swiftt: 0xe1c
+  __TEXT.__oslogstring: 0xc3ea
+  __TEXT.__gcc_except_tab: 0x1b8c
+  __TEXT.__constg_swiftt: 0xe24
   __TEXT.__swift5_typeref: 0x1606
   __TEXT.__swift5_builtin: 0xf0
   __TEXT.__swift5_reflstr: 0x7fe

   __TEXT.__swift5_types: 0xf8
   __TEXT.__swift5_capture: 0xc0c
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__swift_as_entry: 0x194
-  __TEXT.__swift_as_ret: 0x1d4
-  __TEXT.__swift_as_cont: 0x274
+  __TEXT.__swift_as_entry: 0x198
+  __TEXT.__swift_as_ret: 0x1dc
+  __TEXT.__swift_as_cont: 0x27c
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0x55b8
-  __TEXT.__eh_frame: 0x4704
+  __TEXT.__unwind_info: 0x5600
+  __TEXT.__eh_frame: 0x4804
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x240
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5450
+  __DATA_CONST.__objc_selrefs: 0x5478
   __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x4d8
   __DATA_CONST.__objc_arraydata: 0x250
-  __DATA_CONST.__got: 0xe40
-  __AUTH_CONST.__const: 0x5088
+  __DATA_CONST.__got: 0xe60
+  __AUTH_CONST.__const: 0x5090
   __AUTH_CONST.__cfstring: 0x99e0
-  __AUTH_CONST.__objc_const: 0x13500
+  __AUTH_CONST.__objc_const: 0x13570
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __AUTH_CONST.__auth_got: 0x11a8
+  __AUTH_CONST.__auth_got: 0x11b0
   __AUTH.__objc_data: 0x3248
   __AUTH.__data: 0x4f8
-  __DATA.__objc_ivar: 0x7c8
-  __DATA.__data: 0x2190
+  __DATA.__objc_ivar: 0x7d4
+  __DATA.__data: 0x21a0
   __DATA.__bss: 0x3f00
   __DATA.__common: 0xd0
   __DATA_DIRTY.__objc_data: 0x1f40

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6121
-  Symbols:   8731
-  CStrings:  2283
+  Functions: 6134
+  Symbols:   8746
+  CStrings:  2288
 
Symbols:
+ -[STConversation _applyManagingGuardianAppleIDs:generation:]
+ -[STConversation _managingGuardiansMayHaveChanged]
+ -[STConversation _nextManagingGuardiansFetchGeneration]
+ -[STConversation familyNotifyToken]
+ GCC_except_table54
+ GCC_except_table63
+ GCC_except_table77
+ _FAFamilyUpdateNotification
+ _OBJC_IVAR_$_STConversation._appliedManagingGuardiansFetchGeneration
+ _OBJC_IVAR_$_STConversation._familyNotifyToken
+ _OBJC_IVAR_$_STConversation._managingGuardiansFetchGeneration
+ ___50-[STConversation _managingGuardiansMayHaveChanged]_block_invoke
+ ___73-[STConversation _stConversationCommonInitSetupObservationOfStateChanges]_block_invoke_2
+ ___block_descriptor_48_e8_32s_e29_v24?0"NSArray"8"NSError"16l
+ ___swift_closure_destructor.24Tm
+ _objc_msgSend$_applyManagingGuardianAppleIDs:generation:
+ _objc_msgSend$_managingGuardiansMayHaveChanged
+ _objc_msgSend$_nextManagingGuardiansFetchGeneration
+ _objc_msgSend$isEqualToArray:
- GCC_except_table56
- GCC_except_table73
- ___block_descriptor_40_e8_32s_e29_v24?0"NSArray"8"NSError"16l
- ___swift_closure_destructor.23Tm
CStrings:
+ "Could not get groupEntryContent for webDomain %{private}s, error: %{public}@"
+ "Failed to fetch managing guardian Apple IDs again. Error: %{public}@"
+ "Ignored managing guardian Apple IDs, a newer reply was applied"
+ "Managing guardian Apple IDs changed to: %{private}@"
+ "No applicator, defaulting content to webDomain %{private}s"
```
