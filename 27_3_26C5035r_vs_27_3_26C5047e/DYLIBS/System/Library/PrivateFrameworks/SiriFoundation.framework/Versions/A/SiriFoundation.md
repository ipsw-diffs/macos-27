## SiriFoundation

> `/System/Library/PrivateFrameworks/SiriFoundation.framework/Versions/A/SiriFoundation`

```diff

-3610.6.1.4.1
-  __TEXT.__text: 0xed08
+3610.8.2.0.0
+  __TEXT.__text: 0xefa0
   __TEXT.__objc_methlist: 0x1264
   __TEXT.__const: 0x7c
-  __TEXT.__cstring: 0x2928
-  __TEXT.__oslogstring: 0x1afb
+  __TEXT.__cstring: 0x298a
+  __TEXT.__oslogstring: 0x1d1e
   __TEXT.__gcc_except_tab: 0x20
   __TEXT.__unwind_info: 0x668
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe98
+  __DATA_CONST.__objc_selrefs: 0xea8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0x30

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 436
-  Symbols:   1180
-  CStrings:  431
+  Symbols:   1182
+  CStrings:  441
 
Symbols:
+ -[SRFSetupAssistantPreferences siriAvailability]
+ -[SRFSetupAssistantPreferences wasLinwoodAutoOptInJustMitigated]
+ _OBJC_CLASS_$_AFSiriAvailability
+ _objc_msgSend$desiredOrchestrationMode
+ _objc_msgSend$fromPreferences
+ _objc_msgSend$isLinwoodCapableAndAccessRestricted
+ _objc_msgSend$wasLinwoodAutoOptInJustMitigated
- -[SRFSetupAssistantPreferences isSiriAICapable]
- -[SRFSetupAssistantPreferences wasSiriAIEverAvailable]
- _OBJC_CLASS_$_AFSystemAssistantExperienceStatusManager
- _objc_msgSend$isSiriAICapable
- _objc_msgSend$wasSiriAIEverAvailable
Functions:
~ +[SRFSetupAssistantPreferences shouldOfferSiriAIUpsellUsingSiriState:inputs:] : 104 -> 884
~ -[SRFSetupAssistantPreferences isSiriAICapable] -> -[SRFSetupAssistantPreferences siriAvailability] : 68 -> 12
~ -[SRFSetupAssistantPreferences wasSiriAIEverAvailable] -> -[SRFSetupAssistantPreferences wasLinwoodAutoOptInJustMitigated] : 68 -> 8
CStrings:
+ "%s Siri AI upsell %{public}s: Siri AI was available before, auto opt-in just mitigated=%{BOOL}d"
+ "%s Siri AI upsell not offered: Siri AI is already the orchestration mode"
+ "%s Siri AI upsell not offered: Siri is off"
+ "%s Siri AI upsell not offered: Siri preferences dictate Buddy should be skipped"
+ "%s Siri AI upsell not offered: not capable of Siri AI, past or behind the velvet rope"
+ "%s Siri AI upsell offered: Siri AI was never available"
+ "%s Siri availability: present=%{BOOL}d capable=%{BOOL}d accessRestricted=%{BOOL}d mode=%lu everAvailable=%{BOOL}d"
+ "+[SRFSetupAssistantPreferences shouldOfferSiriAIUpsellUsingSiriState:inputs:]"
+ "not offered"
+ "offered"
```
