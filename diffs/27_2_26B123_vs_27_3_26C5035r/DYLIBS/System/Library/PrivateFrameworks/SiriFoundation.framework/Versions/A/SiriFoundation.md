## SiriFoundation

> `/System/Library/PrivateFrameworks/SiriFoundation.framework/Versions/A/SiriFoundation`

```diff

-3605.25.1.14.2
-  __TEXT.__text: 0xeb44
-  __TEXT.__objc_methlist: 0x11cc
+3610.6.1.4.1
+  __TEXT.__text: 0xed08
+  __TEXT.__objc_methlist: 0x1264
   __TEXT.__const: 0x7c
-  __TEXT.__cstring: 0x2921
-  __TEXT.__oslogstring: 0x1ac9
+  __TEXT.__cstring: 0x2928
+  __TEXT.__oslogstring: 0x1afb
   __TEXT.__gcc_except_tab: 0x20
-  __TEXT.__unwind_info: 0x658
+  __TEXT.__unwind_info: 0x668
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__const: 0x2c8
   __DATA_CONST.__objc_classlist: 0xa0
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x28
+  __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe58
+  __DATA_CONST.__objc_selrefs: 0xe98
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0x30
-  __DATA_CONST.__got: 0x1e0
+  __DATA_CONST.__got: 0x1e8
   __AUTH_CONST.__const: 0x3d0
   __AUTH_CONST.__cfstring: 0x1920
-  __AUTH_CONST.__objc_const: 0x1990
+  __AUTH_CONST.__objc_const: 0x1d10
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x360
   __AUTH.__objc_data: 0x280
   __DATA.__objc_ivar: 0x68
-  __DATA.__data: 0x288
+  __DATA.__data: 0x2e8
   __DATA.__bss: 0x48
   __DATA_DIRTY.__objc_data: 0x3c0
   __DATA_DIRTY.__bss: 0xb0

   - /System/Library/PrivateFrameworks/login.framework/Versions/A/login
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 430
-  Symbols:   1158
-  CStrings:  430
+  Functions: 436
+  Symbols:   1180
+  CStrings:  431
 
Symbols:
+ +[SRFSetupAssistantPreferences shouldOfferSiriAIUpsellUsingSiriState:inputs:]
+ +[SRFSetupAssistantPreferences shouldOfferSiriForSetupState:inputs:]
+ -[SRFSetupAssistantPreferences isSiriAICapable]
+ -[SRFSetupAssistantPreferences siriDataSharingOptInStatus]
+ -[SRFSetupAssistantPreferences siriIsEnabled]
+ -[SRFSetupAssistantPreferences wasSiriAIEverAvailable]
+ _OBJC_CLASS_$_AFSystemAssistantExperienceStatusManager
+ __OBJC_$_PROP_LIST_SRFSetupAssistantPreferences
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SRFSetupAssistantInputs
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SRFSetupAssistantInputs
+ __OBJC_$_PROTOCOL_REFS_SRFSetupAssistantInputs
+ __OBJC_CLASS_PROTOCOLS_$_SRFSetupAssistantPreferences
+ __OBJC_LABEL_PROTOCOL_$_SRFSetupAssistantInputs
+ __OBJC_PROTOCOL_$_SRFSetupAssistantInputs
+ _objc_msgSend$isLinwoodCapableIgnoringUserSetting
+ _objc_msgSend$isSiriAICapable
+ _objc_msgSend$linwoodEverAvailable
+ _objc_msgSend$shouldOfferSiriAIUpsellUsingSiriState:inputs:
+ _objc_msgSend$shouldOfferSiriForSetupState:inputs:
+ _objc_msgSend$siriAvailability
+ _objc_msgSend$siriIsEnabled
+ _objc_msgSend$wasSiriAIEverAvailable
CStrings:
+ "%s Siri UI should be shown for the Siri AI upsell"
+ "+[SRFSetupAssistantPreferences shouldOfferSiriForSetupState:inputs:]"
- "-[SRFSetupAssistantPreferences shouldOfferSiriForSetupState:]"
```
