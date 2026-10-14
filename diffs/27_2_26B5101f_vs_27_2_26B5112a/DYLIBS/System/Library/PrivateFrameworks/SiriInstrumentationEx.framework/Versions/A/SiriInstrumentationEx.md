## SiriInstrumentationEx

> `/System/Library/PrivateFrameworks/SiriInstrumentationEx.framework/Versions/A/SiriInstrumentationEx`

```diff

 3605.33.1.0.0
-  __TEXT.__text: 0x28b5cc
-  __TEXT.__objc_methlist: 0x2054c
-  __TEXT.__const: 0x5a164
+  __TEXT.__text: 0x291108
+  __TEXT.__objc_methlist: 0x20a5c
+  __TEXT.__const: 0x5ac64
   __TEXT.__constg_swiftt: 0xc
-  __TEXT.__swift5_proto: 0x34dc
+  __TEXT.__swift5_proto: 0x3548
   __TEXT.__swift5_typeref: 0xa
-  __TEXT.__cstring: 0x8913
-  __TEXT.__unwind_info: 0xdf80
+  __TEXT.__cstring: 0x89d0
+  __TEXT.__unwind_info: 0xe180
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1078
-  __DATA_CONST.__objc_classlist: 0x1038
+  __DATA_CONST.__objc_classlist: 0x1060
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1e090
-  __DATA_CONST.__objc_superrefs: 0x1038
-  __DATA_CONST.__got: 0x1620
-  __AUTH_CONST.__cfstring: 0x98a0
-  __AUTH_CONST.__objc_const: 0x2fbd0
+  __DATA_CONST.__objc_selrefs: 0x1e198
+  __DATA_CONST.__objc_superrefs: 0x1060
+  __DATA_CONST.__got: 0x1648
+  __AUTH_CONST.__cfstring: 0x9940
+  __AUTH_CONST.__objc_const: 0x302f0
   __AUTH_CONST.__auth_got: 0x1a8
-  __AUTH.__objc_data: 0xa230
-  __DATA.__objc_ivar: 0x20b8
+  __AUTH.__objc_data: 0xa3c0
+  __DATA.__objc_ivar: 0x2104
   __DATA.__data: 0xb28
-  __DATA.__bss: 0x69b80
+  __DATA.__bss: 0x6a900
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/ProtocolBuffer.framework/Versions/A/ProtocolBuffer

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 17894
-  Symbols:   30402
-  CStrings:  1226
+  Functions: 18053
+  Symbols:   30585
+  CStrings:  1232
 
Symbols:
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived .cxx_destruct]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived addIdentityAggressors:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived clearIdentityAggressors]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteIdentityAggressors]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived deleteIsRecentlySeen]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived hasIsRecentlySeen]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived identityAggressorsAtIndex:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived identityAggressorsCount]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived identityAggressors]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived isRecentlySeen]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setHasIsRecentlySeen:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setIdentityAggressors:]
+ -[ORCHSchemaORCHSpeakerIdentificationResultReceived setIsRecentlySeen:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked deleteIsRecentlySeen]
+ -[PLANNERSchemaPLANNERUserIdentityChecked hasIsRecentlySeen]
+ -[PLANNERSchemaPLANNERUserIdentityChecked isRecentlySeen]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setHasIsRecentlySeen:]
+ -[PLANNERSchemaPLANNERUserIdentityChecked setIsRecentlySeen:]
+ -[SISchemaUEIResponseAppLaunchCanceled deleteExists]
+ -[SISchemaUEIResponseAppLaunchCanceled dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchCanceled exists]
+ -[SISchemaUEIResponseAppLaunchCanceled hasExists]
+ -[SISchemaUEIResponseAppLaunchCanceled hash]
+ -[SISchemaUEIResponseAppLaunchCanceled initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchCanceled initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchCanceled isEqual:]
+ -[SISchemaUEIResponseAppLaunchCanceled jsonData]
+ -[SISchemaUEIResponseAppLaunchCanceled readFrom:]
+ -[SISchemaUEIResponseAppLaunchCanceled setExists:]
+ -[SISchemaUEIResponseAppLaunchCanceled setHasExists:]
+ -[SISchemaUEIResponseAppLaunchCanceled writeTo:]
+ -[SISchemaUEIResponseAppLaunchContext .cxx_destruct]
+ -[SISchemaUEIResponseAppLaunchContext canceled]
+ -[SISchemaUEIResponseAppLaunchContext deleteCanceled]
+ -[SISchemaUEIResponseAppLaunchContext deleteEnded]
+ -[SISchemaUEIResponseAppLaunchContext deleteFailed]
+ -[SISchemaUEIResponseAppLaunchContext deleteStartedOrChanged]
+ -[SISchemaUEIResponseAppLaunchContext dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchContext ended]
+ -[SISchemaUEIResponseAppLaunchContext failed]
+ -[SISchemaUEIResponseAppLaunchContext hasCanceled]
+ -[SISchemaUEIResponseAppLaunchContext hasEnded]
+ -[SISchemaUEIResponseAppLaunchContext hasFailed]
+ -[SISchemaUEIResponseAppLaunchContext hasStartedOrChanged]
+ -[SISchemaUEIResponseAppLaunchContext hash]
+ -[SISchemaUEIResponseAppLaunchContext initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchContext initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchContext isEqual:]
+ -[SISchemaUEIResponseAppLaunchContext jsonData]
+ -[SISchemaUEIResponseAppLaunchContext readFrom:]
+ -[SISchemaUEIResponseAppLaunchContext setCanceled:]
+ -[SISchemaUEIResponseAppLaunchContext setEnded:]
+ -[SISchemaUEIResponseAppLaunchContext setFailed:]
+ -[SISchemaUEIResponseAppLaunchContext setHasCanceled:]
+ -[SISchemaUEIResponseAppLaunchContext setHasEnded:]
+ -[SISchemaUEIResponseAppLaunchContext setHasFailed:]
+ -[SISchemaUEIResponseAppLaunchContext setHasStartedOrChanged:]
+ -[SISchemaUEIResponseAppLaunchContext setStartedOrChanged:]
+ -[SISchemaUEIResponseAppLaunchContext startedOrChanged]
+ -[SISchemaUEIResponseAppLaunchContext whichContextevent]
+ -[SISchemaUEIResponseAppLaunchContext writeTo:]
+ -[SISchemaUEIResponseAppLaunchEnded .cxx_destruct]
+ -[SISchemaUEIResponseAppLaunchEnded deleteExecutorAppIntentMetrics]
+ -[SISchemaUEIResponseAppLaunchEnded dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchEnded executorAppIntentMetrics]
+ -[SISchemaUEIResponseAppLaunchEnded hasExecutorAppIntentMetrics]
+ -[SISchemaUEIResponseAppLaunchEnded hash]
+ -[SISchemaUEIResponseAppLaunchEnded initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchEnded initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchEnded isEqual:]
+ -[SISchemaUEIResponseAppLaunchEnded jsonData]
+ -[SISchemaUEIResponseAppLaunchEnded readFrom:]
+ -[SISchemaUEIResponseAppLaunchEnded setExecutorAppIntentMetrics:]
+ -[SISchemaUEIResponseAppLaunchEnded setHasExecutorAppIntentMetrics:]
+ -[SISchemaUEIResponseAppLaunchEnded writeTo:]
+ -[SISchemaUEIResponseAppLaunchFailed .cxx_destruct]
+ -[SISchemaUEIResponseAppLaunchFailed addErrors:]
+ -[SISchemaUEIResponseAppLaunchFailed clearErrors]
+ -[SISchemaUEIResponseAppLaunchFailed deleteErrors]
+ -[SISchemaUEIResponseAppLaunchFailed dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchFailed errorsAtIndex:]
+ -[SISchemaUEIResponseAppLaunchFailed errorsCount]
+ -[SISchemaUEIResponseAppLaunchFailed errors]
+ -[SISchemaUEIResponseAppLaunchFailed hash]
+ -[SISchemaUEIResponseAppLaunchFailed initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchFailed initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchFailed isEqual:]
+ -[SISchemaUEIResponseAppLaunchFailed jsonData]
+ -[SISchemaUEIResponseAppLaunchFailed readFrom:]
+ -[SISchemaUEIResponseAppLaunchFailed setErrors:]
+ -[SISchemaUEIResponseAppLaunchFailed writeTo:]
+ -[SISchemaUEIResponseAppLaunchStarted deleteExists]
+ -[SISchemaUEIResponseAppLaunchStarted dictionaryRepresentation]
+ -[SISchemaUEIResponseAppLaunchStarted exists]
+ -[SISchemaUEIResponseAppLaunchStarted hasExists]
+ -[SISchemaUEIResponseAppLaunchStarted hash]
+ -[SISchemaUEIResponseAppLaunchStarted initWithDictionary:]
+ -[SISchemaUEIResponseAppLaunchStarted initWithJSON:]
+ -[SISchemaUEIResponseAppLaunchStarted isEqual:]
+ -[SISchemaUEIResponseAppLaunchStarted jsonData]
+ -[SISchemaUEIResponseAppLaunchStarted readFrom:]
+ -[SISchemaUEIResponseAppLaunchStarted setExists:]
+ -[SISchemaUEIResponseAppLaunchStarted setHasExists:]
+ -[SISchemaUEIResponseAppLaunchStarted writeTo:]
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._identityAggressors
+ OBJC_IVAR_$_ORCHSchemaORCHSpeakerIdentificationResultReceived._isRecentlySeen
+ OBJC_IVAR_$_PLANNERSchemaPLANNERUserIdentityChecked._isRecentlySeen
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchCanceled._exists
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchCanceled._has
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._canceled
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._ended
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._failed
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasCanceled
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasEnded
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasFailed
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._hasStartedOrChanged
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._startedOrChanged
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchContext._whichContextevent
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchEnded._executorAppIntentMetrics
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchEnded._hasExecutorAppIntentMetrics
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchFailed._errors
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchStarted._exists
+ OBJC_IVAR_$_SISchemaUEIResponseAppLaunchStarted._has
+ _OBJC_CLASS_$_ExecutorSiriSchemaExecutorAppIntentMetrics
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchCanceled
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchContext
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchEnded
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchFailed
+ _OBJC_CLASS_$_SISchemaUEIResponseAppLaunchStarted
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchCanceled
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchContext
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchEnded
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchFailed
+ _OBJC_METACLASS_$_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchContext
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_$_INSTANCE_METHODS_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchContext
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_$_INSTANCE_VARIABLES_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchContext
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_$_PROP_LIST_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchContext
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_CLASS_RO_$_SISchemaUEIResponseAppLaunchStarted
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchCanceled
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchContext
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchEnded
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchFailed
+ __OBJC_METACLASS_RO_$_SISchemaUEIResponseAppLaunchStarted
+ _objc_msgSend$addIdentityAggressors:
+ _objc_msgSend$clearIdentityAggressors
+ _objc_msgSend$identityAggressors
+ _objc_msgSend$isRecentlySeen
+ _objc_msgSend$remoteContext
+ _objc_msgSend$remoteSessionContext
+ _objc_msgSend$remoteTimeInMs
+ _objc_msgSend$riId
+ _objc_msgSend$riSessionId
+ _objc_msgSend$roundTripCount
+ _objc_msgSend$setIdentityAggressors:
+ _objc_msgSend$setIsRecentlySeen:
+ _objc_msgSend$setRemoteContext:
+ _objc_msgSend$setRemoteSessionContext:
+ _objc_msgSend$setRemoteTimeInMs:
+ _objc_msgSend$setRiId:
+ _objc_msgSend$setRiSessionId:
+ _objc_msgSend$setRoundTripCount:
+ _objc_msgSend$setSourceContext:
+ _objc_msgSend$setSourceSessionContext:
+ _objc_msgSend$setUeiResponseAppLaunchContext:
+ _objc_msgSend$sourceContext
+ _objc_msgSend$sourceSessionContext
+ _objc_msgSend$ueiResponseAppLaunchContext
CStrings:
+ "PLANNERUSERIDENTITYCHECKOUTCOME_UNRECOGNIZED_SPEAKER_ON_HOME_ACCESSORY"
+ "PLANNERUSERIDENTITYCHECKOUTCOME_VISUAL_IDENTITY_REQUIRED"
+ "Q"
+ "executorAppIntentMetrics"
+ "identityAggressors"
+ "isRecentlySeen"
```
