## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/Versions/A/SiriUIFoundation`

```diff

-3610.10.1.0.0
-  __TEXT.__text: 0x7b8a4
-  __TEXT.__objc_methlist: 0x43d8
+3610.17.1.0.0
+  __TEXT.__text: 0x7c30c
+  __TEXT.__objc_methlist: 0x44c8
   __TEXT.__const: 0x32ec
-  __TEXT.__cstring: 0x6196
-  __TEXT.__oslogstring: 0x5c79
+  __TEXT.__cstring: 0x6296
+  __TEXT.__oslogstring: 0x5d17
   __TEXT.__gcc_except_tab: 0xa00
   __TEXT.__ustring: 0x22
   __TEXT.__dlopen_cstrs: 0x58
   __TEXT.__swift5_typeref: 0x119e
   __TEXT.__swift5_capture: 0x534
   __TEXT.__constg_swiftt: 0x13f0
-  __TEXT.__swift5_reflstr: 0x100a
-  __TEXT.__swift5_fieldmd: 0xe8c
+  __TEXT.__swift5_reflstr: 0x102a
+  __TEXT.__swift5_fieldmd: 0xe98
   __TEXT.__swift5_builtin: 0x64
   __TEXT.__swift5_proto: 0x228
   __TEXT.__swift5_types: 0x118

   __TEXT.__swift_as_ret: 0xc0
   __TEXT.__swift_as_cont: 0x110
   __TEXT.__swift5_protos: 0x28
-  __TEXT.__swift5_assocty: 0x228
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x2a58
+  __TEXT.__swift5_assocty: 0x228
+  __TEXT.__unwind_info: 0x2a98
   __TEXT.__eh_frame: 0x1950
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x570
-  __DATA_CONST.__objc_classlist: 0x300
+  __DATA_CONST.__objc_classlist: 0x310
   __DATA_CONST.__objc_catlist: 0x158
   __DATA_CONST.__objc_protolist: 0x158
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2cc8
+  __DATA_CONST.__objc_selrefs: 0x2d80
   __DATA_CONST.__objc_protorefs: 0x78
-  __DATA_CONST.__objc_superrefs: 0x160
+  __DATA_CONST.__objc_superrefs: 0x170
   __DATA_CONST.__objc_arraydata: 0x20
-  __DATA_CONST.__got: 0x938
+  __DATA_CONST.__got: 0x948
   __AUTH_CONST.__const: 0x4b39
-  __AUTH_CONST.__cfstring: 0x2200
-  __AUTH_CONST.__objc_const: 0x8958
+  __AUTH_CONST.__cfstring: 0x2260
+  __AUTH_CONST.__objc_const: 0x8b98
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0xbb8
-  __AUTH.__objc_data: 0xff0
+  __AUTH.__objc_data: 0x1090
   __AUTH.__data: 0xb98
-  __DATA.__objc_ivar: 0x414
-  __DATA.__data: 0x14f8
+  __DATA.__objc_ivar: 0x42c
+  __DATA.__data: 0x1500
   __DATA.__bss: 0x40f0
   __DATA.__common: 0x48
   __DATA_DIRTY.__objc_data: 0xef8

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3131
-  Symbols:   4581
-  CStrings:  1040
+  Functions: 3149
+  Symbols:   4639
+  CStrings:  1053
 
Symbols:
+ +[SRUIFIntelligenceFlowFeatureFlag(SWEFeatureFlags) isIntercomPlannerToolsEnabled]
+ -[SRUIFInstrumentationManager _isLoggableLinkTappedURL:]
+ -[SRUIFInstrumentationManager _weblinkMetadataForDetails:]
+ -[SRUIFInstrumentationManager emitLinkTappedWithType:isPersonalEntity:opensExternally:URL:]
+ -[SRUIFInstrumentationManager emitLinkTappedWithType:isPersonalEntity:opensExternally:details:]
+ -[SRUIFLinkTapDetails .cxx_destruct]
+ -[SRUIFLinkTapDetails URL]
+ -[SRUIFLinkTapDetails initWithURL:weblink:]
+ -[SRUIFLinkTapDetails weblink]
+ -[SRUIFUIBridgeClient _considerTTSPrewarmForProgressUpdate:]
+ -[SRUIFUIBridgeClient _discardPendingTTSPrewarmWithReason:]
+ -[SRUIFUIBridgeClient _firePendingTTSPrewarmIfThinking:]
+ -[SRUIFUIBridgeClient discardPendingTTSPrewarm]
+ -[SRUIFUIBridgeClient scheduleTTSPrewarm:]
+ -[SRUIFWeblinkTapDetails .cxx_destruct]
+ -[SRUIFWeblinkTapDetails initWithPosition:openSource:]
+ -[SRUIFWeblinkTapDetails openSource]
+ -[SRUIFWeblinkTapDetails position]
+ GCC_except_table122
+ GCC_except_table124
+ GCC_except_table135
+ _OBJC_CLASS_$_SISchemaUEIWeblinkMetadata
+ _OBJC_CLASS_$_SRUIFLinkTapDetails
+ _OBJC_CLASS_$_SRUIFWeblinkTapDetails
+ _OBJC_IVAR_$_SRUIFLinkTapDetails._URL
+ _OBJC_IVAR_$_SRUIFLinkTapDetails._weblink
+ _OBJC_IVAR_$_SRUIFUIBridgeClient._pendingTTSPrewarm
+ _OBJC_IVAR_$_SRUIFUIBridgeClient._ttsPrewarmLock
+ _OBJC_IVAR_$_SRUIFWeblinkTapDetails._openSource
+ _OBJC_IVAR_$_SRUIFWeblinkTapDetails._position
+ _OBJC_METACLASS_$_SRUIFLinkTapDetails
+ _OBJC_METACLASS_$_SRUIFWeblinkTapDetails
+ __OBJC_$_INSTANCE_METHODS_SRUIFLinkTapDetails
+ __OBJC_$_INSTANCE_METHODS_SRUIFWeblinkTapDetails
+ __OBJC_$_INSTANCE_VARIABLES_SRUIFLinkTapDetails
+ __OBJC_$_INSTANCE_VARIABLES_SRUIFWeblinkTapDetails
+ __OBJC_$_PROP_LIST_SRUIFLinkTapDetails
+ __OBJC_$_PROP_LIST_SRUIFWeblinkTapDetails
+ __OBJC_CLASS_RO_$_SRUIFLinkTapDetails
+ __OBJC_CLASS_RO_$_SRUIFWeblinkTapDetails
+ __OBJC_METACLASS_RO_$_SRUIFLinkTapDetails
+ __OBJC_METACLASS_RO_$_SRUIFWeblinkTapDetails
+ ___95-[SRUIFInstrumentationManager emitLinkTappedWithType:isPersonalEntity:opensExternally:details:]_block_invoke
+ ___block_descriptor_70_e8_32s40s48w_e5_v8?0l
+ _objc_msgSend$URL
+ _objc_msgSend$_considerTTSPrewarmForProgressUpdate:
+ _objc_msgSend$_discardPendingTTSPrewarmWithReason:
+ _objc_msgSend$_firePendingTTSPrewarmIfThinking:
+ _objc_msgSend$_isLoggableLinkTappedURL:
+ _objc_msgSend$_weblinkMetadataForDetails:
+ _objc_msgSend$activities
+ _objc_msgSend$activityType
+ _objc_msgSend$emitLinkTappedWithType:isPersonalEntity:opensExternally:URL:
+ _objc_msgSend$emitLinkTappedWithType:isPersonalEntity:opensExternally:details:
+ _objc_msgSend$initWithURL:weblink:
+ _objc_msgSend$openSource
+ _objc_msgSend$position
+ _objc_msgSend$setOpenSource:
+ _objc_msgSend$setPosition:
+ _objc_msgSend$setUrl:
+ _objc_msgSend$setWeblinkMetadata:
+ _objc_msgSend$standardUserDefaults
+ _objc_msgSend$weblink
- GCC_except_table114
- GCC_except_table120
- GCC_except_table131
- ___87-[SRUIFInstrumentationManager emitLinkTappedWithType:isPersonalEntity:opensExternally:]_block_invoke
- ___block_descriptor_61_e8_32s40w_e5_v8?0l
CStrings:
+ "%s #ttsprewarm deferral disabled, prewarming now"
+ "%s #ttsprewarm dropped: %s"
+ "%s #ttsprewarm fired at thinking"
+ "%s #ttsprewarm scheduled (replaced pending: %d)"
+ "-[SRUIFUIBridgeClient _discardPendingTTSPrewarmWithReason:]"
+ "-[SRUIFUIBridgeClient _firePendingTTSPrewarmIfThinking:]"
+ "-[SRUIFUIBridgeClient scheduleTTSPrewarm:]"
+ "IntercomPlannerTools"
+ "Siri ended"
+ "SiriTTSPrewarmDeferralDisabled"
+ "http"
+ "https"
+ "request ended"
```
