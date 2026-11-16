## WebKitLegacy

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-626.1.12.11.4
-  __TEXT.__text: 0x197cb8
+626.1.17.0.0
+  __TEXT.__text: 0x197d5c
   __TEXT.__objc_methlist: 0x10250
   __TEXT.__const: 0x6c0
   __TEXT.__getClass_cstr: 0x23
-  __TEXT.__gcc_except_tab: 0x14ac4
-  __TEXT.__cstring: 0x16813
+  __TEXT.__gcc_except_tab: 0x14ad8
+  __TEXT.__cstring: 0x168ba
   __TEXT.__oslogstring: 0x14a
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0xa4e0

   __DATA_CONST.__objc_superrefs: 0x368
   __DATA_CONST.__objc_arraydata: 0x38
   __DATA_CONST.__got: 0x1428
-  __AUTH_CONST.__const: 0x53a0
-  __AUTH_CONST.__cfstring: 0x10ee0
+  __AUTH_CONST.__const: 0x53b0
+  __AUTH_CONST.__cfstring: 0x10f80
   __AUTH_CONST.__objc_const: 0x11490
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x408
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0x4840
+  __AUTH_CONST.__auth_got: 0x4848
   __AUTH.__objc_data: 0x2a30
   __AUTH.__data: 0x38
   __DATA.__objc_ivar: 0x508

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 7515
-  Symbols:   15925
-  CStrings:  2610
+  Functions: 7517
+  Symbols:   15928
+  CStrings:  2615
 
Symbols:
+ GCC_except_table204
+ GCC_except_table259
+ GCC_except_table262
+ GCC_except_table457
+ GCC_except_table545
+ GCC_except_table552
+ __ZN7WebCore17FrameLoaderClient23didNotifyUserActivationEN3WTF13MonotonicTimeENSt3__18optionalINS_16ProcessQualifiedINS1_23ObjectIdentifierGenericINS_30UserGestureTokenIdentifierTypeENS1_38ObjectIdentifierMainThreadAccessTraitsEEEEEEE
+ __ZN7WebCore17FrameLoaderClient29didRevokeForcedUserActivationENS_16ProcessQualifiedIN3WTF23ObjectIdentifierGenericINS_30UserGestureTokenIdentifierTypeENS2_38ObjectIdentifierMainThreadAccessTraitsEEEEE
+ __ZN7WebCore24DeprecatedGlobalSettings37setMediaResourceLoadTimeoutForTestingEj
+ __ZNK7WebCore12ChromeClient17devicePostureTypeEv
- GCC_except_table239
- GCC_except_table255
- GCC_except_table261
- GCC_except_table456
- GCC_except_table463
- GCC_except_table551
- __ZN7WebCore17FrameLoaderClient23didNotifyUserActivationEN3WTF13MonotonicTimeE
Functions:
~ +[WebPreferences initialize] : 13864 -> 13880
+ __ZN7WebCore17FrameLoaderClient25didHandleFirstUserGestureEN3WTF13MonotonicTimeE
~ -[WebView(WebViewEditing) setSmartInsertDeleteEnabled:] : 184 -> 176
+ __ZNK15WebChromeClient31canShowDataListSuggestionLabelsEv
~ +[WebPreferences(WebPrivateExperimentalFeatures) _experimentalFeatures] : 27876 -> 28000
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 25312 -> 25332
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
