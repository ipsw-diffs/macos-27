## SiriUI

> `/System/Library/PrivateFrameworks/SiriUI.framework/Versions/A/SiriUI`

```diff

-3610.6.1.4.1
-  __TEXT.__text: 0xcc8a8
-  __TEXT.__objc_methlist: 0x10ce0
-  __TEXT.__const: 0x25d4
-  __TEXT.__cstring: 0xc54b
+3610.8.2.0.0
+  __TEXT.__text: 0xcd4b4
+  __TEXT.__objc_methlist: 0x10d38
+  __TEXT.__const: 0x2604
+  __TEXT.__cstring: 0xc65b
   __TEXT.__gcc_except_tab: 0x1234
-  __TEXT.__oslogstring: 0x65d3
+  __TEXT.__oslogstring: 0x66cc
   __TEXT.__ustring: 0x2a
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__swift5_typeref: 0x1700
+  __TEXT.__swift5_typeref: 0x170e
   __TEXT.__swift5_capture: 0x1d0
   __TEXT.__swift5_reflstr: 0x5df
   __TEXT.__swift5_assocty: 0x260
-  __TEXT.__constg_swiftt: 0x10b4
-  __TEXT.__swift5_fieldmd: 0x724
+  __TEXT.__constg_swiftt: 0x10e0
+  __TEXT.__swift5_fieldmd: 0x734
   __TEXT.__swift5_proto: 0xc0
-  __TEXT.__swift5_types: 0xb0
+  __TEXT.__swift5_types: 0xb4
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift_as_entry: 0x8
   __TEXT.__swift_as_ret: 0x8
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__unwind_info: 0x4f48
+  __TEXT.__unwind_info: 0x4f80
   __TEXT.__eh_frame: 0x56c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x7a8
-  __DATA_CONST.__objc_classlist: 0x5f0
+  __DATA_CONST.__objc_classlist: 0x5f8
   __DATA_CONST.__objc_catlist: 0x180
   __DATA_CONST.__objc_protolist: 0x400
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa640
+  __DATA_CONST.__objc_selrefs: 0xa660
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x3e0
   __DATA_CONST.__objc_arraydata: 0x180
-  __DATA_CONST.__got: 0x1828
+  __DATA_CONST.__got: 0x1840
   __AUTH_CONST.__const: 0x36f0
   __AUTH_CONST.__cfstring: 0x5540
-  __AUTH_CONST.__objc_const: 0x22350
+  __AUTH_CONST.__objc_const: 0x22400
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_doubleobj: 0xe0
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x10e0
-  __AUTH.__objc_data: 0x2d90
-  __AUTH.__data: 0x4d8
-  __DATA.__objc_ivar: 0xdcc
-  __DATA.__data: 0x3250
+  __AUTH_CONST.__auth_got: 0x1100
+  __AUTH.__objc_data: 0x2e40
+  __AUTH.__data: 0x508
+  __DATA.__objc_ivar: 0xdd4
+  __DATA.__data: 0x3260
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0x14c8
-  __DATA.__common: 0x4e0
+  __DATA.__common: 0x4e8
   __DATA_DIRTY.__objc_data: 0x1a38
   __DATA_DIRTY.__data: 0x788
   __DATA_DIRTY.__bss: 0x878

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6178
-  Symbols:   13087
-  CStrings:  1768
+  Functions: 6193
+  Symbols:   13099
+  CStrings:  1774
 
Symbols:
+ GCC_except_table236
+ GCC_except_table276
+ GCC_except_table293
+ _OBJC_CLASS_$__TtC6SiriUI20GMAvailabilityRegion
+ _OBJC_IVAR_$_SiriUISystemAssistantExperienceViewController._starterFetchGeneration
+ _OBJC_IVAR_$_SiriUISystemAssistantExperienceViewController._starterRefreshRequestCount
+ _OBJC_METACLASS_$__TtC6SiriUI20GMAvailabilityRegion
+ __CLASS_METHODS__TtC6SiriUI20GMAvailabilityRegion
+ __CLASS_PROPERTIES__TtC6SiriUI20GMAvailabilityRegion
+ __DATA__TtC6SiriUI20GMAvailabilityRegion
+ __INSTANCE_METHODS__TtC6SiriUI20GMAvailabilityRegion
+ __METACLASS_DATA__TtC6SiriUI20GMAvailabilityRegion
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PHPickerViewControllerDelegate
+ ___block_descriptor_57_e8_32s40w_e17_v16?0"NSArray"8l
+ _objc_msgSend$finderActivity:
+ _symbolic _____ 6SiriUI20GMAvailabilityRegionC
+ _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV6PolicyV
- GCC_except_table235
- GCC_except_table275
- GCC_except_table292
- ___101-[SiriUISystemAssistantExperienceViewController setupConversationStarterSuggestionViewsForAppSwitch:]_block_invoke_2
- ___block_descriptor_49_e8_32s40w_e17_v16?0"NSArray"8l
CStrings:
+ "%s #suggestions: discarding stale starter suggestions (%lu views)"
+ "%s #suggestions: skipping starter refresh for app switch, a newer activation arrived"
+ "%s #suggestions: skipping starter refresh for app switch, starters were disabled during the delay"
+ "-[SiriUISystemAssistantExperienceViewController finderActivity:]_block_invoke"
+ "-[SiriUISystemAssistantExperienceViewController setupConversationStarterSuggestionViewsForAppSwitch:]_block_invoke_2"
+ "ModelCatalog.UseCaseIdentifier.settingsAppleIntelligence.id"
+ "\xf0\xd11"
- "\xf0\xb11"
```
