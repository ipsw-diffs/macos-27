## WebDriver

> `/System/Library/PrivateFrameworks/WebDriver.framework/Versions/A/WebDriver`

```diff

-625.2.8.11.9
-  __TEXT.__text: 0x12437c
-  __TEXT.__objc_methlist: 0x6354
-  __TEXT.__gcc_except_tab: 0x84e4
-  __TEXT.__cstring: 0xe7ff
-  __TEXT.__oslogstring: 0x50ba
-  __TEXT.__const: 0xdb92
+626.1.12.11.4
+  __TEXT.__text: 0x127b84
+  __TEXT.__objc_methlist: 0x63ec
+  __TEXT.__gcc_except_tab: 0x863c
+  __TEXT.__cstring: 0xe9ef
+  __TEXT.__oslogstring: 0x51aa
+  __TEXT.__const: 0xdc22
   __TEXT.__ustring: 0x4
   __TEXT.__constg_swiftt: 0x187c
   __TEXT.__swift5_typeref: 0x1c61
-  __TEXT.__swift5_reflstr: 0x152e
+  __TEXT.__swift5_reflstr: 0x153e
   __TEXT.__swift5_fieldmd: 0x254c
   __TEXT.__swift5_assocty: 0x528
   __TEXT.__swift5_proto: 0x66c
   __TEXT.__swift5_types: 0x214
   __TEXT.__swift5_builtin: 0xa0
   __TEXT.__swift5_mpenum: 0x40
-  __TEXT.__swift5_capture: 0xb04
-  __TEXT.__swift_as_entry: 0x1ac
-  __TEXT.__swift_as_ret: 0x250
-  __TEXT.__swift_as_cont: 0x444
+  __TEXT.__swift5_capture: 0xb54
+  __TEXT.__swift_as_entry: 0x1b4
+  __TEXT.__swift_as_ret: 0x258
+  __TEXT.__swift_as_cont: 0x46c
   __TEXT.__swift5_protos: 0x8
   __TEXT.SandboxProfile: 0x0
-  __TEXT.__unwind_info: 0x6488
-  __TEXT.__eh_frame: 0x6f58
+  __TEXT.__unwind_info: 0x6580
+  __TEXT.__eh_frame: 0x7128
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1798
+  __DATA_CONST.__const: 0x1820
   __DATA_CONST.__objc_classlist: 0x3f8
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3828
+  __DATA_CONST.__objc_selrefs: 0x3880
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x2b8
   __DATA_CONST.__objc_arraydata: 0x2a0
   __DATA_CONST.__got: 0x8d8
-  __AUTH_CONST.__const: 0xc968
-  __AUTH_CONST.__cfstring: 0x9ea0
-  __AUTH_CONST.__objc_const: 0xb750
+  __AUTH_CONST.__const: 0xca98
+  __AUTH_CONST.__cfstring: 0xa280
+  __AUTH_CONST.__objc_const: 0xb838
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_dictobj: 0xa0
-  __AUTH_CONST.__objc_intobj: 0x498
+  __AUTH_CONST.__objc_intobj: 0x4b0
   __AUTH_CONST.__objc_arrayobj: 0x1b0
-  __AUTH_CONST.__auth_got: 0x1238
+  __AUTH_CONST.__auth_got: 0x1248
   __AUTH.__objc_data: 0x2680
   __AUTH.__data: 0x1370
-  __DATA.__objc_ivar: 0x720
+  __DATA.__objc_ivar: 0x734
   __DATA.__data: 0x1e80
   __DATA.__bss: 0xcd80
   __DATA.__common: 0x18

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5702
-  Symbols:   7012
-  CStrings:  2086
+  Functions: 5746
+  Symbols:   7051
+  CStrings:  2108
 
Symbols:
+ +[WDRemoteElement referenceIdentifierInClientPayload:]
+ +[WDRemoteElement referenceTypeOfClientPayload:]
+ -[RoutingConnection expectsRequestBodyFromMethod:atPath:]
+ -[WDMCPAutomationBridge isSessionValid]
+ -[WDProtocolBackendProxy invalidateWithErrorMessage:]
+ -[WDProtocolBackendProxy isValid]
+ -[WDRemoteSession consumeUserActivationWithCompletionHandler:]
+ -[WDRemoteSession setSiteIsolationEnabled:]
+ -[WDRemoteSession siteIsolationEnabled]
+ -[WDRemoteSessionHost bootstrapSessionIgnoringExistingRunningApplications:processIdentifier:environment:completionHandler:]
+ -[WDRemoteSessionHost processIdentifier]
+ -[WDW3CRouteHandler _evaluateInternalJavaScriptFunction:withArguments:sourceURL:forceUserGesture:inBrowsingContext:relatedSession:completionHandler:]
+ -[WDW3CRouteHandler _extractFunctionBody:andArguments:referencedShadowRoot:fromRequest:orSendResponse:relatedSession:]
+ -[WDW3CRouteHandler _handleConsumeUserActivation:response:relatedSession:]
+ -[WDW3CRouteHandler _translateClientPayload:toAutomationPayloadInSession:referencedShadowRoot:error:]
+ GCC_except_table115
+ GCC_except_table118
+ GCC_except_table127
+ GCC_except_table138
+ GCC_except_table162
+ GCC_except_table185
+ GCC_except_table197
+ GCC_except_table198
+ GCC_except_table377
+ GCC_except_table394
+ GCC_except_table398
+ GCC_except_table406
+ _OBJC_IVAR_$_WDProtocolBackendProxy._isInvalidated
+ _OBJC_IVAR_$_WDProtocolBackendProxy._sessionIdentifier
+ _OBJC_IVAR_$_WDProtocolBackendProxy._terminationErrorMessage
+ _OBJC_IVAR_$_WDRemoteSession._siteIsolationEnabled
+ _OBJC_IVAR_$_WDRemoteSessionHost._requestedProcessIdentifier
+ _WDVirtualAuthenticatorProtocolFromString
+ _WDVirtualAuthenticatorTransportFromString
+ __ZNSt3__123__lower_bound_bisectingB9sqn220106INS_17_ClassicAlgPolicyEPKNS_4pairIN3WTF28ComparableASCIISubsetLiteralILNS3_11ASCIISubsetE0EEE32WDProtocolAutomationErrorMessageEENS3_20ComparableStringViewENS_10__identityEZNKS3_14SortedArrayMapIS8_Lm25EE6tryGetINS3_6StringEEEPKS7_RKT_EUlRSJ_RT0_E_EESN_SN_RKT1_NS_15iterator_traitsISN_E15difference_typeERT3_RT2_
+ ___101-[WDW3CRouteHandler _translateClientPayload:toAutomationPayloadInSession:referencedShadowRoot:error:]_block_invoke
+ ___149-[WDW3CRouteHandler _evaluateInternalJavaScriptFunction:withArguments:sourceURL:forceUserGesture:inBrowsingContext:relatedSession:completionHandler:]_block_invoke
+ ___62-[WDRemoteSession consumeUserActivationWithCompletionHandler:]_block_invoke
+ ___74-[WDW3CRouteHandler _handleConsumeUserActivation:response:relatedSession:]_block_invoke
+ ___74-[WDW3CRouteHandler _handleConsumeUserActivation:response:relatedSession:]_block_invoke_2
+ ___74-[WDW3CRouteHandler _handleConsumeUserActivation:response:relatedSession:]_block_invoke_3
+ ___block_descriptor_56_e8_32s40r48r_e8_16?08l
+ ___block_descriptor_65_e8_32s40s48s56s_e20_v24?0"NSError"816l
+ ___block_descriptor_81_e8_32s40s48s56s64s72s_e20_v16?0"WDW3CError"8l
+ ___block_descriptor_81_e8_32s40s48s56s64s72s_e5_v8?0l
+ ___swift_closure_destructor.13Tm
+ ___swift_closure_destructor.31Tm
+ _objc_msgSend$_evaluateInternalJavaScriptFunction:withArguments:sourceURL:forceUserGesture:inBrowsingContext:relatedSession:completionHandler:
+ _objc_msgSend$_extractFunctionBody:andArguments:referencedShadowRoot:fromRequest:orSendResponse:relatedSession:
+ _objc_msgSend$_translateClientPayload:toAutomationPayloadInSession:referencedShadowRoot:error:
+ _objc_msgSend$bootstrapSessionIgnoringExistingRunningApplications:processIdentifier:environment:completionHandler:
+ _objc_msgSend$consumeUserActivationWithCompletionHandler:
+ _objc_msgSend$initWithProtocol:transport:
+ _objc_msgSend$invalidateWithErrorMessage:
+ _objc_msgSend$isSessionValid
+ _objc_msgSend$isValid
+ _objc_msgSend$longLongValue
+ _objc_msgSend$referenceIdentifierInClientPayload:
+ _objc_msgSend$referenceTypeOfClientPayload:
+ _objc_msgSend$setSiteIsolationEnabled:
+ _objc_msgSend$siteIsolationEnabled
+ _unresolvedScriptArgumentError
- -[WDRemoteSessionHost bootstrapSessionIgnoringExistingRunningApplications:environment:completionHandler:]
- -[WDW3CRouteHandler _extractFunctionBody:andArguments:fromRequest:orSendResponse:relatedSession:]
- -[WDW3CRouteHandler _translateClientPayload:toAutomationPayloadInSession:]
- GCC_except_table116
- GCC_except_table123
- GCC_except_table124
- GCC_except_table136
- GCC_except_table140
- GCC_except_table150
- GCC_except_table166
- GCC_except_table193
- GCC_except_table367
- GCC_except_table384
- GCC_except_table388
- GCC_except_table396
- __ZNSt3__123__lower_bound_bisectingB9sqn220106INS_17_ClassicAlgPolicyEPKNS_4pairIN3WTF28ComparableASCIISubsetLiteralILNS3_11ASCIISubsetE0EEE32WDProtocolAutomationErrorMessageEENS3_20ComparableStringViewENS_10__identityEZNKS3_14SortedArrayMapIS8_Lm24EE6tryGetINS3_6StringEEEPKS7_RKT_EUlRSJ_RT0_E_EESN_SN_RKT1_NS_15iterator_traitsISN_E15difference_typeERT3_RT2_
- ___132-[WDW3CRouteHandler _evaluateInternalJavaScriptFunction:withArguments:sourceURL:inBrowsingContext:relatedSession:completionHandler:]_block_invoke
- ___74-[WDW3CRouteHandler _translateClientPayload:toAutomationPayloadInSession:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56s_e20_v24?0"NSError"816l
- ___swift_closure_destructor.22Tm
- _objc_msgSend$_extractFunctionBody:andArguments:fromRequest:orSendResponse:relatedSession:
- _objc_msgSend$_translateClientPayload:toAutomationPayloadInSession:
- _objc_msgSend$bootstrapSessionIgnoringExistingRunningApplications:environment:completionHandler:
CStrings:
+ "\t-b, --bidi                Port number in the range 8080..8100 the driver should use to listen for incoming"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/include/wtf/HashTable.h"
+ "/session/:sessionId/window/consume-user-activation"
+ "22626.1.12.11.4"
+ "A reference identifier in the 'args' parameter is not a string."
+ "A shadow root reference could not be resolved in this browsing context"
+ "Capability 'safari:processID' must be a positive integer process identifier, but was '%@'."
+ "Execute a JavaScript function body within the page. The script may contain multiple statements; add an explicit `return` for any value you want back. Use `$uid(N)` to reference DOM elements by their UID from get_page_content output (e.g. `return $uid(42).href`). When `frameId` is set, runs inside the frame that UID belongs to. Prefer get_page_content for reading page text or structure — reach for it with `region: \"entire_page\"` or relaxed filters before scripting a DOM scrape here. Reserve this tool for actions or computations that text extraction can't express."
+ "Handle of the tab to navigate. If omitted, uses the active tab."
+ "No tab with handle "
+ "StaleNode"
+ "The 'safari:processID' and 'safari:ignoreExistingRunningApplications' capabilities cannot be combined."
+ "The 'safari:processID' capability is only supported for the 'macOS' platform."
+ "The browser session ended because Safari quit or crashed. All tabs, browsing context handles, console messages, and network records from that session are gone. The next tool call will start a new browser session with a fresh, empty state."
+ "UID of a node from get_page_content output, identifying a subframe to run in instead of the main frame: pass an iframe's UID to run inside that iframe, or the UID of a node inside a subframe to run in that subframe. Omit this to run in the main frame."
+ "Unable to find a running, automatable Safari instance with process identifier %d to attach to."
+ "Unreadable response from evaluate_javascript: "
+ "WDSessionHostProcessIdentifier"
+ "WDSessionSiteIsolationEnabled"
+ "WebDriver session (%{public}@) command '%{public}@' was sent after the remote session ended"
+ "WebDriver session (%{public}@) state (%{public}@) ignoring session host candidate (pid: %i) that does not match the requested process identifier (%i)"
+ "consume"
+ "consumeUserActivation"
+ "frame-075b-4da1-b6ba-e579c2d3230a"
+ "org.webkit.webdriver.controlled-by-external-agent"
+ "safari:processID"
+ "validateKey"
+ "webkit:siteIsolationEnabled"
+ "window-fcc6-11e5-b4f8-330a88ab9d7f"
- "\t-b, --bidi                Port number the driver should use to listen for incoming"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/include/wtf/HashTable.h"
- "22625.2.8.11.9"
- "Execute a JavaScript function body within the page. The script may contain multiple statements; add an explicit `return` for any value you want back. Use `$uid(N)` to reference DOM elements by their UID from get_page_content output (e.g. `return $uid(42).href`). When `frameId` is set, runs inside that iframe. Prefer get_page_content for reading page text or structure — reach for it with `region: \"entire_page\"` or relaxed filters before scripting a DOM scrape here. Reserve this tool for actions or computations that text extraction can't express."
- "UID of an iframe element from get_page_content output. When set, the expression runs inside that iframe instead of the main frame."
- "UUID of the tab to navigate. If omitted, uses the active tab."
- "void WTF::HashTable<WTF::String, WTF::KeyValuePair<WTF::String, WTF::Ref<WTF::JSONImpl::Value>>, WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<WTF::String, WTF::Ref<WTF::JSONImpl::Value>>>, WTF::DefaultHash<String>, WTF::HashMap<WTF::String, WTF::Ref<WTF::JSONImpl::Value>>::KeyValuePairTraits, WTF::HashTraits<String>>::validateKey(const ValueType &) [Key = WTF::String, Value = WTF::KeyValuePair<WTF::String, WTF::Ref<WTF::JSONImpl::Value>>, Extractor = WTF::KeyValuePairKeyExtractor<WTF::KeyValuePair<WTF::String, WTF::Ref<WTF::JSONImpl::Value>>>, HashFunctions = WTF::DefaultHash<String>, Traits = WTF::HashMap<WTF::String, WTF::Ref<WTF::JSONImpl::Value>>::KeyValuePairTraits, KeyTraits = WTF::HashTraits<String>, Malloc = WTF::FastMalloc, shouldValidateKey = WTF::ShouldValidateKey::Yes]"
```
