## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/Versions/A/IDSFoundation`

```diff

-2003.200.61.0.0
-  __TEXT.__text: 0x4e71b8
-  __TEXT.__objc_methlist: 0x1b054
-  __TEXT.__const: 0x406a0
-  __TEXT.__oslogstring: 0x2a16a
-  __TEXT.__cstring: 0x342bd
-  __TEXT.__gcc_except_tab: 0xb6a0
+2003.200.71.0.0
+  __TEXT.__text: 0x4f3f60
+  __TEXT.__objc_methlist: 0x1b0c4
+  __TEXT.__const: 0x40940
+  __TEXT.__oslogstring: 0x2a86a
+  __TEXT.__cstring: 0x3440d
+  __TEXT.__gcc_except_tab: 0xb6d8
   __TEXT.__dlopen_cstrs: 0xac
   __TEXT.__ustring: 0x188
-  __TEXT.__swift5_typeref: 0xb9a6
-  __TEXT.__constg_swiftt: 0xcb54
-  __TEXT.__swift5_reflstr: 0x6c76
-  __TEXT.__swift5_fieldmd: 0xb938
+  __TEXT.__swift5_typeref: 0xba36
+  __TEXT.__constg_swiftt: 0xcc3c
+  __TEXT.__swift5_reflstr: 0x6d66
+  __TEXT.__swift5_fieldmd: 0xba50
   __TEXT.__swift5_builtin: 0x3c0
   __TEXT.__swift5_assocty: 0x970
-  __TEXT.__swift5_proto: 0x34b0
-  __TEXT.__swift5_types: 0xef8
+  __TEXT.__swift5_proto: 0x34c8
+  __TEXT.__swift5_types: 0xf10
   __TEXT.__swift5_capture: 0x1668
-  __TEXT.__swift_as_entry: 0x3b8
-  __TEXT.__swift_as_ret: 0x33c
-  __TEXT.__swift_as_cont: 0x618
-  __TEXT.__swift5_protos: 0x9c
+  __TEXT.__swift_as_entry: 0x3c4
+  __TEXT.__swift_as_ret: 0x344
+  __TEXT.__swift_as_cont: 0x61c
+  __TEXT.__swift5_protos: 0xa0
   __TEXT.__swift5_acfuncs: 0x1cc
   __TEXT.__swift5_mpenum: 0x164
   __TEXT.__swift5_types2: 0x20
-  __TEXT.__unwind_info: 0x19958
-  __TEXT.__eh_frame: 0x1691c
+  __TEXT.__unwind_info: 0x19af8
+  __TEXT.__eh_frame: 0x1697c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x55f8
+  __DATA_CONST.__const: 0x5610
   __DATA_CONST.__objc_classlist: 0x12a0
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x1f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa9e0
+  __DATA_CONST.__objc_selrefs: 0xaa08
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0xb00
   __DATA_CONST.__objc_arraydata: 0x1558
-  __DATA_CONST.__got: 0x1410
-  __AUTH_CONST.__const: 0x1ca68
-  __AUTH_CONST.__cfstring: 0x2c2e0
-  __AUTH_CONST.__objc_const: 0x3d998
+  __DATA_CONST.__got: 0x1418
+  __AUTH_CONST.__const: 0x1cd20
+  __AUTH_CONST.__cfstring: 0x2c340
+  __AUTH_CONST.__objc_const: 0x3d9f8
   __AUTH_CONST.__objc_intobj: 0xbd0
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x1e90
-  __AUTH_CONST.__auth_got: 0x2720
+  __AUTH_CONST.__auth_got: 0x2748
   __AUTH.__objc_data: 0xa2d8
-  __AUTH.__data: 0xab00
+  __AUTH.__data: 0xac20
   __DATA.__objc_ivar: 0x2820
-  __DATA.__data: 0xf0b0
+  __DATA.__data: 0xf100
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x67a30
-  __DATA.__common: 0x1f0
+  __DATA.__bss: 0x67cb0
+  __DATA.__common: 0x1f8
   __DATA_DIRTY.__objc_data: 0x1540
-  __DATA_DIRTY.__data: 0x728
+  __DATA_DIRTY.__data: 0x738
   __DATA_DIRTY.__bss: 0x200
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 31828
-  Symbols:   4964
-  CStrings:  8186
+  Functions: 31924
+  Symbols:   4968
+  CStrings:  8203
 
Symbols:
+ _IDSGroupSessionClientParametersKey
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
CStrings:
+ "IDSGLLinkEngineCommon.linkConnectNotAttempted: %s: connect request was not attempted (%ld attempt(s) in a row came back with nothing); connectable again, but not before %s"
+ "IDSGLLinkEngineCommon.linkConnectNotAttempted: %s: no link"
+ "IDSGLLinkEngineCommon.linkConnectNotAttempted: %s: not awaiting a connect (%s); nothing to report"
+ "IDSGLLinkEngineCommon.linkDidDisconnect: %s (attempt ending: %s)"
+ "IDSGLLinkEngineCommon.linkDidDisconnect: %s: disconnected before the connect attempt got anywhere (%ld in a row); not offering it again before %s"
+ "IDSGLLinkEngineCommon.linkDidFail: %s: failed before the connect attempt got anywhere (%ld in a row); not offering it again before %s"
+ "LinkEngineConnectBestController.logIfOfferedInPlaceOfHeldLinks: %s: offered in place of higher-priority %s, held after connect attempts that achieved nothing. They are offered again when their hold ends, and take over from this link if they connect."
+ "LinkEngineConnectBestController.update: %s: %s wants a retry, but is held until %s"
+ "LinkEngineConnectBestController.update: %s: %s, but held until %s"
+ "LinkEngineConnectFirstController.logIfOfferedInPlaceOfHeldLinks: %s: offered in place of higher-priority %s, held after connect attempts that achieved nothing. If this link connects first it is kept, and %s will not be offered again until it fails."
+ "LinkEngineConnectFirstController.update: %s: %s wants a retry, but is held until %s"
+ "LinkEngineConnectFirstController.update: %s: %s, but held until %s"
+ "LinkEngine[%s].get: %ld there is another scheduled update. triggering... (%s)"
+ "_IDSGLLinkEngine.init: Connect bounce backoff: disabled=%{bool}d"
+ "_IDSGLLinkEngine.init: Pre-join connect hold: disabled=%{bool}d"
+ "_relayConnectionBehaviorForSession[%@]: shared session has not joined, but the pre-join hold is disabled (pjh); connecting, and the send path will refuse"
+ "_relayConnectionBehaviorForSession[%@]: shared session has not joined; holding off connecting new links"
+ "connect bounce backoff"
+ "gs-client-parameters-key"
+ "pre join connect hold"
+ "setSharedSessionHasJoined: %@; re-driving links"
- "IDSGLLinkEngineCommon.linkDidDisconnect: %s"
- "LinkEngineConnectBestController.update: %s: %s -> connecting (retry plugin)"
- "LinkEngine[%s].shouldContinueUpdating.get: %ld there is another scheduled update. triggering... (%s)"
- "setSharedSessionHasJoined: joined; re-driving links in case an allocbind was dropped pre-join"
```
