## Intents

> `/System/Library/Frameworks/Intents.framework/Versions/A/Intents`

```diff

-4016.1.16.0.0
-  __TEXT.__text: 0x48f4c4
-  __TEXT.__objc_methlist: 0x7ab5c
+4016.2.7.0.0
+  __TEXT.__text: 0x491d00
+  __TEXT.__objc_methlist: 0x7ad3c
   __TEXT.__const: 0x1d90
-  __TEXT.__dlopen_cstrs: 0xb0a
-  __TEXT.__gcc_except_tab: 0x1f88
-  __TEXT.__cstring: 0x4c376
-  __TEXT.__oslogstring: 0x613d
+  __TEXT.__dlopen_cstrs: 0xb62
+  __TEXT.__gcc_except_tab: 0x1ff0
+  __TEXT.__cstring: 0x4c7cc
+  __TEXT.__oslogstring: 0x6535
   __TEXT.__ustring: 0x512
-  __TEXT.__unwind_info: 0x15298
+  __TEXT.__unwind_info: 0x15360
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9a68
-  __DATA_CONST.__objc_classlist: 0x29e0
+  __DATA_CONST.__const: 0x9a90
+  __DATA_CONST.__objc_classlist: 0x29f8
   __DATA_CONST.__objc_catlist: 0xf8
-  __DATA_CONST.__objc_protolist: 0x19b0
+  __DATA_CONST.__objc_protolist: 0x19c0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x15588
-  __DATA_CONST.__objc_protorefs: 0x90
-  __DATA_CONST.__objc_superrefs: 0x1438
+  __DATA_CONST.__objc_selrefs: 0x156b0
+  __DATA_CONST.__objc_protorefs: 0x98
+  __DATA_CONST.__objc_superrefs: 0x1448
   __DATA_CONST.__objc_arraydata: 0xd128
-  __DATA_CONST.__got: 0x2918
-  __AUTH_CONST.__const: 0x3e60
-  __AUTH_CONST.__cfstring: 0x45640
-  __AUTH_CONST.__objc_const: 0xb6878
+  __DATA_CONST.__got: 0x2960
+  __AUTH_CONST.__const: 0x3f70
+  __AUTH_CONST.__cfstring: 0x457a0
+  __AUTH_CONST.__objc_const: 0xb6cb8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x798
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x53e8
   __AUTH_CONST.__objc_dictobj: 0x3b38
-  __AUTH_CONST.__auth_got: 0x760
-  __AUTH.__objc_data: 0x15428
-  __DATA.__objc_ivar: 0x3d34
-  __DATA.__data: 0x134d8
-  __DATA.__bss: 0xc60
+  __AUTH_CONST.__auth_got: 0x768
+  __AUTH.__objc_data: 0x15518
+  __DATA.__objc_ivar: 0x3d48
+  __DATA.__data: 0x13598
+  __DATA.__bss: 0xc90
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x4e98
   __DATA_DIRTY.__bss: 0x1d0

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 31232
-  Symbols:   59124
-  CStrings:  10055
+  Functions: 31288
+  Symbols:   59274
+  CStrings:  10095
 
Symbols:
+ +[INIntentDeliveryEnvelope supportsBSXPCSecureCoding]
+ +[INIntentDeliveryListener sharedListener]
+ +[INIntentDeliveryRequest supportsBSXPCSecureCoding]
+ -[INAppIntentDeliverer _completeWithArchivedResponse:error:]
+ -[INAppIntentDeliverer _handleLaunchActionResponse:archivedForwardingAction:]
+ -[INAppIntentDeliverer _handshakeLaunchAction]
+ -[INAppIntentDeliverer _launchAction]
+ -[INAppIntentDeliverer deliveryConnection]
+ -[INAppIntentDeliverer setDeliveryConnection:]
+ -[INAppIntentDispatcher _dispatchIntentForwardingAction:auditToken:completionHandler:]
+ -[INAppIntentDispatcher dispatchIntentForwardingAction:verifiedPeerAuditToken:completionHandler:]
+ -[INAppResolver _resolvedAppMatchingDescriptor:options:]
+ -[INAppResolver cachedStrictMatchingResults]
+ -[INAppResolver resolvedAppMatchingDescriptor:options:]
+ -[INAppResolverOptions requireStrictMatching]
+ -[INIntentDeliveryEnvelope .cxx_destruct]
+ -[INIntentDeliveryEnvelope encodeWithBSXPCCoder:]
+ -[INIntentDeliveryEnvelope initWithBSXPCCoder:]
+ -[INIntentDeliveryEnvelope initWithListenerEndpoint:]
+ -[INIntentDeliveryEnvelope listenerEndpoint]
+ -[INIntentDeliveryListener .cxx_destruct]
+ -[INIntentDeliveryListener _init]
+ -[INIntentDeliveryListener deliverArchivedForwardingAction:endpoint:reply:]
+ -[INIntentDeliveryListener envelope]
+ -[INIntentDeliveryListener executionHandler]
+ -[INIntentDeliveryListener listener:shouldAcceptNewConnection:]
+ -[INIntentDeliveryListener listener]
+ -[INIntentDeliveryListener setExecutionHandler:]
+ -[INIntentDeliveryRequest encodeWithBSXPCCoder:]
+ -[INIntentDeliveryRequest initWithBSXPCCoder:]
+ -[INStartSendingUpdatesForwardingAction _updateObserverEndpoint:]
+ -[INStartSendingUpdatesForwardingAction setEndpoint:]
+ GCC_except_table10005
+ GCC_except_table10192
+ GCC_except_table10204
+ GCC_except_table10206
+ GCC_except_table10211
+ GCC_except_table10276
+ GCC_except_table10837
+ GCC_except_table10962
+ GCC_except_table10966
+ GCC_except_table11079
+ GCC_except_table11192
+ GCC_except_table11219
+ GCC_except_table11220
+ GCC_except_table11443
+ GCC_except_table11885
+ GCC_except_table12614
+ GCC_except_table12625
+ GCC_except_table12628
+ GCC_except_table12636
+ GCC_except_table12657
+ GCC_except_table13262
+ GCC_except_table13837
+ GCC_except_table13841
+ GCC_except_table14086
+ GCC_except_table14613
+ GCC_except_table15293
+ GCC_except_table15297
+ GCC_except_table16428
+ GCC_except_table16531
+ GCC_except_table16539
+ GCC_except_table16540
+ GCC_except_table16843
+ GCC_except_table18489
+ GCC_except_table19145
+ GCC_except_table19302
+ GCC_except_table19330
+ GCC_except_table20335
+ GCC_except_table20337
+ GCC_except_table20340
+ GCC_except_table20495
+ GCC_except_table21523
+ GCC_except_table21825
+ GCC_except_table22895
+ GCC_except_table22898
+ GCC_except_table22901
+ GCC_except_table23516
+ GCC_except_table23946
+ GCC_except_table24257
+ GCC_except_table25734
+ GCC_except_table25746
+ GCC_except_table27617
+ GCC_except_table27620
+ GCC_except_table27621
+ GCC_except_table27622
+ GCC_except_table27623
+ GCC_except_table29315
+ GCC_except_table29317
+ GCC_except_table29319
+ GCC_except_table29327
+ GCC_except_table29329
+ GCC_except_table29338
+ GCC_except_table30386
+ GCC_except_table30394
+ GCC_except_table30395
+ GCC_except_table30399
+ GCC_except_table30400
+ GCC_except_table30401
+ GCC_except_table30402
+ GCC_except_table30404
+ GCC_except_table30408
+ GCC_except_table30410
+ GCC_except_table30411
+ GCC_except_table30412
+ GCC_except_table30413
+ GCC_except_table30415
+ GCC_except_table30604
+ GCC_except_table5418
+ GCC_except_table5419
+ GCC_except_table5626
+ GCC_except_table5629
+ GCC_except_table5635
+ GCC_except_table5875
+ GCC_except_table5884
+ GCC_except_table6424
+ GCC_except_table6427
+ GCC_except_table6461
+ GCC_except_table6462
+ GCC_except_table6496
+ GCC_except_table7059
+ GCC_except_table7144
+ GCC_except_table7145
+ GCC_except_table7868
+ GCC_except_table8134
+ GCC_except_table8485
+ GCC_except_table8738
+ GCC_except_table9416
+ GCC_except_table9617
+ GCC_except_table9628
+ GCC_except_table9629
+ _BSActionErrorDomain
+ _INAppResolverOptionsRequireStrictMatchingKey
+ _INBundleIdentifiersAreLikelyVariants
+ _INIntentDeliveryEntitlement
+ _INIntentDeliveryEnvelopeInActionInfo
+ _INIntentDeliveryGetMode
+ _INIntentDeliveryModeForFlags
+ _INIntentDeliveryModeOverrideForTesting
+ _INIntentDeliveryObjectOfClassInActionInfo
+ _INIntentDeliveryPeerEntitlementOverrideForTesting
+ _INIntentDeliveryPeerIsEntitled
+ _INIntentDeliveryProcessDescription
+ _INIntentDeliveryReceivingXPCInterface
+ _INIntentDeliveryRequestInActionInfo
+ _INNamesAreEquivalent
+ _OBJC_CLASS_$_BSActionResponder
+ _OBJC_CLASS_$_BSMutableSettings
+ _OBJC_CLASS_$_BSSettings
+ _OBJC_CLASS_$_INIntentDeliveryEnvelope
+ _OBJC_CLASS_$_INIntentDeliveryListener
+ _OBJC_CLASS_$_INIntentDeliveryRequest
+ _OBJC_CLASS_$_NSXPCListener
+ _OBJC_IVAR_$_INAppIntentDeliverer._deliveryConnection
+ _OBJC_IVAR_$_INAppResolver._cachedStrictMatchingResults
+ _OBJC_IVAR_$_INIntentDeliveryEnvelope._listenerEndpoint
+ _OBJC_IVAR_$_INIntentDeliveryListener._executionHandler
+ _OBJC_IVAR_$_INIntentDeliveryListener._listener
+ _OBJC_METACLASS_$_INIntentDeliveryEnvelope
+ _OBJC_METACLASS_$_INIntentDeliveryListener
+ _OBJC_METACLASS_$_INIntentDeliveryRequest
+ _SecTaskCopySigningIdentifier
+ _UIKitServicesLibraryCore.frameworkLibrary
+ __INIntentDeliverySetModeOverrideForTesting
+ __INIntentDeliverySetPeerEntitlementOverrideForTesting
+ __OBJC_$_CLASS_METHODS_INIntentDeliveryEnvelope
+ __OBJC_$_CLASS_METHODS_INIntentDeliveryListener
+ __OBJC_$_CLASS_METHODS_INIntentDeliveryRequest
+ __OBJC_$_CLASS_PROP_LIST_INIntentDeliveryListener
+ __OBJC_$_INSTANCE_METHODS_INIntentDeliveryEnvelope
+ __OBJC_$_INSTANCE_METHODS_INIntentDeliveryListener
+ __OBJC_$_INSTANCE_METHODS_INIntentDeliveryRequest
+ __OBJC_$_INSTANCE_VARIABLES_INIntentDeliveryEnvelope
+ __OBJC_$_INSTANCE_VARIABLES_INIntentDeliveryListener
+ __OBJC_$_PROP_LIST_INIntentDeliveryEnvelope
+ __OBJC_$_PROP_LIST_INIntentDeliveryListener
+ __OBJC_$_PROP_LIST_INIntentDeliveryRequest
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_INIntentDeliveryReceiving
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_INIntentDeliveryReceiving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_REFS_INIntentDeliveryReceiving
+ __OBJC_$_PROTOCOL_REFS_NSXPCListenerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_INIntentDeliveryEnvelope
+ __OBJC_CLASS_PROTOCOLS_$_INIntentDeliveryListener
+ __OBJC_CLASS_PROTOCOLS_$_INIntentDeliveryRequest
+ __OBJC_CLASS_RO_$_INIntentDeliveryEnvelope
+ __OBJC_CLASS_RO_$_INIntentDeliveryListener
+ __OBJC_CLASS_RO_$_INIntentDeliveryRequest
+ __OBJC_LABEL_PROTOCOL_$_INIntentDeliveryReceiving
+ __OBJC_LABEL_PROTOCOL_$_NSXPCListenerDelegate
+ __OBJC_METACLASS_RO_$_INIntentDeliveryEnvelope
+ __OBJC_METACLASS_RO_$_INIntentDeliveryListener
+ __OBJC_METACLASS_RO_$_INIntentDeliveryRequest
+ __OBJC_PROTOCOL_$_INIntentDeliveryReceiving
+ __OBJC_PROTOCOL_$_NSXPCListenerDelegate
+ __OBJC_PROTOCOL_REFERENCE_$_INIntentDeliveryReceiving
+ ___37-[INAppIntentDeliverer _launchAction]_block_invoke
+ ___42+[INIntentDeliveryListener sharedListener]_block_invoke
+ ___46-[INAppIntentDeliverer _handshakeLaunchAction]_block_invoke
+ ___56-[INAppResolver _resolvedAppMatchingDescriptor:options:]_block_invoke
+ ___75-[INIntentDeliveryListener deliverArchivedForwardingAction:endpoint:reply:]_block_invoke
+ ___77-[INAppIntentDeliverer _handleLaunchActionResponse:archivedForwardingAction:]_block_invoke
+ ___86-[INAppIntentDispatcher _dispatchIntentForwardingAction:auditToken:completionHandler:]_block_invoke
+ ___INIntentDeliveryObjectOfClassInActionInfo_block_invoke
+ ___UIKitServicesLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32bs_e42_v16?0"INIntentForwardingActionResponse"8l
+ ___block_descriptor_40_e8_32s_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_40_e8_32s_e42_v16?0"INIntentForwardingActionResponse"8l
+ ___block_descriptor_48_e8_32s40s_e26_v16?0"BSActionResponse"8l
+ ___block_descriptor_56_e8_32s40r_e12_v24?0q8^B16lu48l8
+ ___block_descriptor_64_e8_32s40s48bs56r_e42_v16?0"INIntentForwardingActionResponse"8l
+ ___getUISIntentForwardingActionClass_block_invoke
+ _audit_stringUIKitServices
+ _getUISIntentForwardingActionClass
+ _getUISIntentForwardingActionClass.softClass
+ _objc_msgSend$_completeWithArchivedResponse:error:
+ _objc_msgSend$_dispatchIntentForwardingAction:auditToken:completionHandler:
+ _objc_msgSend$_handleLaunchActionResponse:archivedForwardingAction:
+ _objc_msgSend$_handshakeLaunchAction
+ _objc_msgSend$_resolvedAppMatchingDescriptor:options:
+ _objc_msgSend$_updateObserverEndpoint:
+ _objc_msgSend$allSettings
+ _objc_msgSend$anonymousListener
+ _objc_msgSend$cachedStrictMatchingResults
+ _objc_msgSend$compare:options:
+ _objc_msgSend$completeWithIntentForwardingActionResponse:
+ _objc_msgSend$deliverArchivedForwardingAction:endpoint:reply:
+ _objc_msgSend$deliveryConnection
+ _objc_msgSend$enumerateWithBlock:
+ _objc_msgSend$executionHandler
+ _objc_msgSend$info
+ _objc_msgSend$initWithInfo:responder:
+ _objc_msgSend$initWithIntentForwardingAction:responseHandler:
+ _objc_msgSend$initWithIntentForwardingAction:responseQueue:responseHandler:
+ _objc_msgSend$instancesRespondToSelector:
+ _objc_msgSend$listener
+ _objc_msgSend$listenerEndpoint
+ _objc_msgSend$objectForSetting:
+ _objc_msgSend$requireStrictMatching
+ _objc_msgSend$resolvedAppMatchingDescriptor:options:
+ _objc_msgSend$responderWithHandler:
+ _objc_msgSend$setDeliveryConnection:
+ _objc_msgSend$setExportedInterface:
+ _objc_msgSend$setExportedObject:
+ _objc_msgSend$setObject:forSetting:
+ _objc_msgSend$setQueue:
+ _objc_msgSend$setTimeout:
+ _sharedListener.onceToken
+ _sharedListener.sharedListener
- -[INAppResolver _resolvedAppMatchingDescriptor:]
- GCC_except_table10141
- GCC_except_table10153
- GCC_except_table10155
- GCC_except_table10160
- GCC_except_table10225
- GCC_except_table10786
- GCC_except_table10911
- GCC_except_table10915
- GCC_except_table11028
- GCC_except_table11141
- GCC_except_table11168
- GCC_except_table11169
- GCC_except_table11392
- GCC_except_table11834
- GCC_except_table12563
- GCC_except_table12574
- GCC_except_table12577
- GCC_except_table12585
- GCC_except_table12606
- GCC_except_table13211
- GCC_except_table13786
- GCC_except_table13790
- GCC_except_table14035
- GCC_except_table14562
- GCC_except_table15242
- GCC_except_table15246
- GCC_except_table16377
- GCC_except_table16480
- GCC_except_table16488
- GCC_except_table16489
- GCC_except_table16791
- GCC_except_table18437
- GCC_except_table19093
- GCC_except_table19250
- GCC_except_table19278
- GCC_except_table20283
- GCC_except_table20285
- GCC_except_table20288
- GCC_except_table20442
- GCC_except_table21469
- GCC_except_table21771
- GCC_except_table22839
- GCC_except_table22842
- GCC_except_table22845
- GCC_except_table23460
- GCC_except_table23890
- GCC_except_table24201
- GCC_except_table25678
- GCC_except_table25690
- GCC_except_table27561
- GCC_except_table27564
- GCC_except_table27565
- GCC_except_table27566
- GCC_except_table27567
- GCC_except_table29259
- GCC_except_table29261
- GCC_except_table29263
- GCC_except_table29271
- GCC_except_table29273
- GCC_except_table29282
- GCC_except_table30330
- GCC_except_table30338
- GCC_except_table30339
- GCC_except_table30343
- GCC_except_table30344
- GCC_except_table30345
- GCC_except_table30346
- GCC_except_table30348
- GCC_except_table30352
- GCC_except_table30354
- GCC_except_table30355
- GCC_except_table30356
- GCC_except_table30357
- GCC_except_table30359
- GCC_except_table30548
- GCC_except_table5416
- GCC_except_table5417
- GCC_except_table5624
- GCC_except_table5627
- GCC_except_table5631
- GCC_except_table5873
- GCC_except_table5882
- GCC_except_table6422
- GCC_except_table6425
- GCC_except_table6457
- GCC_except_table6458
- GCC_except_table6494
- GCC_except_table7057
- GCC_except_table7142
- GCC_except_table7143
- GCC_except_table7866
- GCC_except_table8132
- GCC_except_table8477
- GCC_except_table9398
- GCC_except_table9954
- ___48-[INAppResolver _resolvedAppMatchingDescriptor:]_block_invoke
- ___74-[INAppIntentDispatcher dispatchIntentForwardingAction:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e48_v16?0"INHandleIntentForwardingActionResponse"8l
- _objc_msgSend$_resolvedAppMatchingDescriptor:
CStrings:
+ "%@ (pid %d)"
+ "%s Failed to archive intent forwarding action response: %{public}@"
+ "%s Failed to unarchive intent delivery from pid %d: %{public}@"
+ "%s Failed to unarchive intent forwarding action response from %{public}@: %{public}@"
+ "%s Falling back to unverified intent delivery: UISIntentForwardingAction has no -initWithInfo:responder:"
+ "%s Falling back to unverified intent delivery: failed to archive the action: %{public}@"
+ "%s Ignoring a late handshake answer from %{public}@"
+ "%s Ignoring a second completion for intent delivery from pid %d"
+ "%s Intent delivery connection to %{public}@ failed: %{public}@"
+ "%s Intent delivery for %{public}@ got no handshake envelope back: %{public}@"
+ "%s Refusing intent delivery from pid %d: no execution handler is installed"
+ "%s Rejecting intent delivery connection: verified delivery is off"
+ "%s Rejecting intent delivery from %{public}@: missing %{public}@"
+ "%s Replacing unexpected %{public}@ from %{public}@ with an error"
+ "%s Would reject intent delivery from %{public}@: missing %{public}@ (audit mode)"
+ "-[INAppIntentDeliverer _completeWithArchivedResponse:error:]"
+ "-[INAppIntentDeliverer _handleLaunchActionResponse:archivedForwardingAction:]"
+ "-[INAppIntentDeliverer _handleLaunchActionResponse:archivedForwardingAction:]_block_invoke"
+ "-[INAppIntentDeliverer _handshakeLaunchAction]"
+ "-[INAppIntentDeliverer completeWithIntentForwardingActionResponse:]"
+ "-[INIntentDeliveryListener deliverArchivedForwardingAction:endpoint:reply:]"
+ "-[INIntentDeliveryListener deliverArchivedForwardingAction:endpoint:reply:]_block_invoke"
+ "-[INIntentDeliveryListener listener:shouldAcceptNewConnection:]"
+ "/System/Library/PrivateFrameworks/UIKitServices.framework/Contents/MacOS/UIKitServices"
+ "0@`"
+ "<unknown>"
+ "Application answered with an unexpected response"
+ "Application answered with an unreadable response"
+ "Application did not answer the delivery handshake"
+ "Application did not answer the delivery handshake in time"
+ "No intent delivery handler is installed"
+ "RequireStrictMatching"
+ "UISIntentForwardingAction"
+ "Unreadable intent forwarding action"
+ "com.apple.private.intents.delivery"
+ "intent_delivery_enforce"
+ "intent_delivery_handshake"
+ "listenerEndpoint"
+ "softlink:r:path:/System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices"
+ "v16@?0@\"BSActionResponse\"8"
+ "v24@?0q8^B16"
- "v16@?0@\"INHandleIntentForwardingActionResponse\"8"
```
