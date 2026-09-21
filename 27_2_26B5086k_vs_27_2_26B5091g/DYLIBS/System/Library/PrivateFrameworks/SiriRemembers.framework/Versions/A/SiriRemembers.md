## SiriRemembers

> `/System/Library/PrivateFrameworks/SiriRemembers.framework/Versions/A/SiriRemembers`

```diff

-3605.12.1.0.0
-  __TEXT.__text: 0xab380
+3605.13.1.0.0
+  __TEXT.__text: 0xacda0
   __TEXT.__objc_methlist: 0x224
-  __TEXT.__const: 0x9964
-  __TEXT.__cstring: 0x30bf
-  __TEXT.__oslogstring: 0x3b55
-  __TEXT.__constg_swiftt: 0x2008
-  __TEXT.__swift5_typeref: 0x2825
-  __TEXT.__swift5_reflstr: 0x12a2
-  __TEXT.__swift5_fieldmd: 0x2598
+  __TEXT.__const: 0x99d4
+  __TEXT.__cstring: 0x314f
+  __TEXT.__oslogstring: 0x3d95
+  __TEXT.__constg_swiftt: 0x2068
+  __TEXT.__swift5_typeref: 0x285d
+  __TEXT.__swift5_reflstr: 0x12b2
+  __TEXT.__swift5_fieldmd: 0x25d0
   __TEXT.__swift5_builtin: 0x8c
   __TEXT.__swift5_proto: 0x854
-  __TEXT.__swift5_types: 0x2b0
+  __TEXT.__swift5_types: 0x2b8
   __TEXT.__swift5_assocty: 0x2d0
-  __TEXT.__swift5_capture: 0xadc
+  __TEXT.__swift5_capture: 0xb48
   __TEXT.__swift5_mpenum: 0x30
   __TEXT.__swift5_protos: 0x44
-  __TEXT.__unwind_info: 0x3468
-  __TEXT.__eh_frame: 0x4c18
+  __TEXT.__unwind_info: 0x34e8
+  __TEXT.__eh_frame: 0x4c40
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xe8
-  __DATA_CONST.__objc_classlist: 0xa8
+  __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x700
+  __DATA_CONST.__objc_selrefs: 0x730
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x6d50
-  __AUTH_CONST.__objc_const: 0x1448
-  __AUTH_CONST.__auth_got: 0x15d8
-  __AUTH.__data: 0x4c8
-  __DATA.__data: 0x1508
-  __DATA.__bss: 0xaea0
+  __AUTH_CONST.__const: 0x6f70
+  __AUTH_CONST.__objc_const: 0x1520
+  __AUTH_CONST.__auth_got: 0x1600
+  __AUTH.__data: 0x570
+  __DATA.__data: 0x1528
+  __DATA.__bss: 0xada0
   __DATA.__common: 0xb0
   __DATA_DIRTY.__objc_data: 0x118
-  __DATA_DIRTY.__data: 0x2ba8
-  __DATA_DIRTY.__bss: 0x4200
+  __DATA_DIRTY.__data: 0x2bc8
+  __DATA_DIRTY.__bss: 0x4300
   __DATA_DIRTY.__common: 0x1b0
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Intents.framework/Versions/A/Intents
   - /System/Library/PrivateFrameworks/ArgumentParserInternal.framework/Versions/A/ArgumentParserInternal
+  - /System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices
   - /System/Library/PrivateFrameworks/BiomeLibrary.framework/Versions/A/BiomeLibrary
   - /System/Library/PrivateFrameworks/BiomeStorage.framework/Versions/A/BiomeStorage
   - /System/Library/PrivateFrameworks/BiomeStreams.framework/Versions/A/BiomeStreams

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4991
-  Symbols:   1750
-  CStrings:  504
+  Functions: 5055
+  Symbols:   1770
+  CStrings:  511
 
Symbols:
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _NSStringFromAFSiriOrchestrationMode
+ _NSStringFromAFSiriUnavailabilityReasons
+ _OBJC_CLASS_$_AFSiriAvailability
+ __DATA__TtC13SiriRemembersP33_9FF6230672138D50B412B1ABD10EC6DE20CapabilitiesObserver
+ __IVARS__TtC13SiriRemembersP33_9FF6230672138D50B412B1ABD10EC6DE20CapabilitiesObserver
+ __METACLASS_DATA__TtC13SiriRemembersP33_9FF6230672138D50B412B1ABD10EC6DE20CapabilitiesObserver
+ _objc_msgSend$desiredOrchestrationMode
+ _objc_msgSend$fromPreferences
+ _objc_msgSend$isAvailable
+ _objc_msgSend$missingDesiredCapabilitiesFor:
+ _objc_msgSend$siriLocale
+ _objc_msgSend$unavailabilityReasons
+ _symbolic SbSgIgl_
+ _symbolic _____ 13SiriRemembers0aB20TranscriptForwardingO
+ _symbolic _____ 13SiriRemembers20CapabilitiesObserver33_9FF6230672138D50B412B1ABD10EC6DELLC
+ _symbolic _____XDXMT 13SiriRemembers20CapabilitiesObserver33_9FF6230672138D50B412B1ABD10EC6DELLC
+ _symbolic _____ySbSgG 13SiriRemembers6AtomicC
CStrings:
+ "SiriRemembersDonationFromAppIntentsListener: ignored event since Siri is not orchestrating on Linwood"
+ "TranscriptForwarding: AFSiriAvailability.fromPreferences() is nil, reading from app.intents (context=%{public}s)"
+ "TranscriptForwarding: allowTranscriptDonationForward is off, reading from app.intents (context=%{public}s)"
+ "TranscriptForwarding: isEnabled=%{bool}d, context=%{public}s, desiredOrchestrationMode=%{public}s, isAvailable=%{bool}d, siriLocale=%{public}s, unavailabilityReasons=%{public}s, missingLinwoodCapabilities=%{public}s"
+ "capabilitiesDidChange"
+ "com.apple.SiriRemembers.TranscriptForwarding"
+ "com.apple.siri.orchestration.capabilities.didChange"
```
