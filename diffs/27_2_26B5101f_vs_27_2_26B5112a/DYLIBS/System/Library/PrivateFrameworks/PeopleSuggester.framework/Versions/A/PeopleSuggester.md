## PeopleSuggester

> `/System/Library/PrivateFrameworks/PeopleSuggester.framework/Versions/A/PeopleSuggester`

```diff

-1976.0.0.0.0
-  __TEXT.__text: 0x124570
+1977.0.0.0.0
+  __TEXT.__text: 0x12455c
   __TEXT.__objc_methlist: 0xaca4
   __TEXT.__const: 0x978
   __TEXT.__gcc_except_tab: 0x42b4
   __TEXT.__cstring: 0x31454
-  __TEXT.__oslogstring: 0xfcd3
+  __TEXT.__oslogstring: 0xfcb3
   __TEXT.__dlopen_cstrs: 0x160f
   __TEXT.__ustring: 0x7e4
   __TEXT.__unwind_info: 0x4280

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6d60
+  __DATA_CONST.__objc_selrefs: 0x6d58
   __DATA_CONST.__objc_superrefs: 0x400
   __DATA_CONST.__objc_arraydata: 0x39d78
-  __DATA_CONST.__got: 0x930
+  __DATA_CONST.__got: 0x928
   __AUTH_CONST.__const: 0x4310
   __AUTH_CONST.__cfstring: 0x7f020
   __AUTH_CONST.__objc_const: 0x155e8

   - /System/Library/PrivateFrameworks/CoreDuetContext.framework/Versions/A/CoreDuetContext
   - /System/Library/PrivateFrameworks/CoreEmoji.framework/Versions/A/CoreEmoji
   - /System/Library/PrivateFrameworks/IntelligencePlatformLibrary.framework/Versions/A/IntelligencePlatformLibrary
-  - /System/Library/PrivateFrameworks/ProactiveEventTracker.framework/Versions/A/ProactiveEventTracker
   - /System/Library/PrivateFrameworks/ProactiveSupport.framework/Versions/A/ProactiveSupport
   - /System/Library/PrivateFrameworks/ProtocolBuffer.framework/Versions/A/ProtocolBuffer
   - /System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5237
-  Symbols:   10540
+  Symbols:   10538
   CStrings:  17732
 
Symbols:
- _OBJC_CLASS_$_PETEventTracker2
- _objc_msgSend$logMessage:
Functions:
~ -[_PSInteractionsStatistics(StaticFeatures) computeTimeSinceLastPhoneCallWithConversationId:interactionRecord:] : 380 -> 400
~ -[_PSInteractionsStatistics(StaticFeatures) computeTimeSinceLastIncomingInteractionForConversationId:interactionRecord:] : 248 -> 268
~ -[_PSInteractionsStatistics loadFeaturesAndPropertiesFromContactCatalog] : 4428 -> 4420
~ ___61-[_PSEnsembleModel sendDataToPETAsync:withConfig:andContext:]_block_invoke : 192 -> 140
CStrings:
+ "Loaded contact catalog: %lu conversations, %lu features, %lu properties, %lu personId sets, %lu bundleId counts, %lu visual identifiers, latencyMs=%.2f"
+ "_PSEnsemble: sent data to Biome"
- "Loaded contact catalog: %lu conversations, %lu features, %lu properties, %lu personId sets, %lu bundleId counts, %lu visual identifiers (skipped %lu timeSince* features), latencyMs=%.2f"
- "_PSEnsemble: sent data to PET"
```
