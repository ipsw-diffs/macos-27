## WebKitLegacy

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-626.1.12.11.4
-  __TEXT.__text: 0x157ee0
+626.1.17.0.0
+  __TEXT.__text: 0x157fb0
   __TEXT.__objc_methlist: 0xf4b8
   __TEXT.__const: 0x280
   __TEXT.__getClass_cstr: 0x12
   __TEXT.__dlsym_cstr: 0x39
-  __TEXT.__gcc_except_tab: 0x12e3c
-  __TEXT.__cstring: 0x135ba
+  __TEXT.__gcc_except_tab: 0x12e48
+  __TEXT.__cstring: 0x13661
   __TEXT.__oslogstring: 0x14a
   __TEXT.__unwind_info: 0x9b68
   __TEXT.__eh_frame: 0x88

   __DATA_CONST.__objc_superrefs: 0x350
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x1008
-  __AUTH_CONST.__const: 0x50f0
-  __AUTH_CONST.__cfstring: 0xf260
+  __AUTH_CONST.__const: 0x5118
+  __AUTH_CONST.__cfstring: 0xf300
   __AUTH_CONST.__objc_const: 0xfc50
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x300
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0x46d8
+  __AUTH_CONST.__auth_got: 0x46e0
   __AUTH.__objc_data: 0x2440
   __AUTH.__data: 0x38
   __DATA.__objc_ivar: 0x488

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 7212
-  Symbols:   14334
-  CStrings:  2223
+  Functions: 7215
+  Symbols:   14340
+  CStrings:  2228
 
Symbols:
+ GCC_except_table203
+ GCC_except_table226
+ GCC_except_table227
+ GCC_except_table236
+ GCC_except_table542
+ GCC_except_table545
+ GCC_except_table607
+ GCC_except_table618
+ __ZN7WebCore17FrameLoaderClient23didNotifyUserActivationEN3WTF13MonotonicTimeENSt3__18optionalINS_16ProcessQualifiedINS1_23ObjectIdentifierGenericINS_30UserGestureTokenIdentifierTypeENS1_38ObjectIdentifierMainThreadAccessTraitsEEEEEEE
+ __ZN7WebCore17FrameLoaderClient29didRevokeForcedUserActivationENS_16ProcessQualifiedIN3WTF23ObjectIdentifierGenericINS_30UserGestureTokenIdentifierTypeENS2_38ObjectIdentifierMainThreadAccessTraitsEEEEE
+ __ZN7WebCore24DeprecatedGlobalSettings37setMediaResourceLoadTimeoutForTestingEj
+ __ZNK7WebCore12ChromeClient17devicePostureTypeEv
+ __ZNK7WebCore12ChromeClient18didDisplayCaptionsEON3WTF6VectorINS1_6StringELm0ENS1_15CrashOnOverflowELm16ENS1_10FastMallocEEE
- GCC_except_table201
- GCC_except_table224
- GCC_except_table541
- GCC_except_table543
- GCC_except_table606
- GCC_except_table617
- __ZN7WebCore17FrameLoaderClient23didNotifyUserActivationEN3WTF13MonotonicTimeE
Functions:
+ __ZN7WebCore17FrameLoaderClient25didHandleFirstUserGestureEN3WTF13MonotonicTimeE
~ -[WebView(WebPrivate) initSimpleHTMLDocumentWithStyle:frame:preferences:groupName:] : 7676 -> 7672
~ -[WebView(WebViewEditing) setSmartInsertDeleteEnabled:] : 192 -> 184
~ -[WebView(WebViewEditing) smartInsertDeleteEnabled] : 36 -> 40
+ __ZNK7WebCore12ChromeClient18didDisplayCaptionsEON3WTF6VectorINS1_6StringELm0ENS1_15CrashOnOverflowELm16ENS1_10FastMallocEEE
+ __ZNK15WebChromeClient31canShowDataListSuggestionLabelsEv
~ __ZN15WebEditorClient24smartInsertDeleteEnabledEv : 76 -> 80
~ +[WebPreferences initialize] : 12432 -> 12452
~ +[WebPreferences(WebPrivateExperimentalFeatures) _experimentalFeatures] : 25596 -> 25848
~ +[WebPreferences(WebPrivateInternalFeatures) _internalFeatures] : 13052 -> 12928
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 22620 -> 22668
CStrings:
+ "Device Posture API"
+ "DevicePostureAPIEnabled"
+ "Enable the Device Posture API"
+ "Media Resource Load Timeout For Testing"
+ "MediaResourceLoadTimeoutForTesting"
+ "Test override for the timeout applied to each media resource load serviced by WebKit, in milliseconds (0 means use production default)"
+ "WebKitDevicePostureAPIEnabled"
+ "WebKitMediaResourceLoadTimeoutForTesting"
+ "WebKitRequiresUserGestureToStartAudiblePlaybackWhenHidden"
- "In two-up PDF display mode, align the trailing odd page to the same column as the first page instead of centering it"
- "Two-Up PDF Trailing Page Left Alignment"
- "TwoUpPDFTrailingPageLeftAlignmentEnabled"
- "WebKitTwoUpPDFTrailingPageLeftAlignmentEnabled"
```
