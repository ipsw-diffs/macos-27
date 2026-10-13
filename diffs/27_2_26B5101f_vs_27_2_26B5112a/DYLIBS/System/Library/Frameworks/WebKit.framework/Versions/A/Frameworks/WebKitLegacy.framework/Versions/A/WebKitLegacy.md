## WebKitLegacy

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-625.2.7.1.0
-  __TEXT.__text: 0x19c0f8
+625.2.8.11.6
+  __TEXT.__text: 0x19c194
   __TEXT.__objc_methlist: 0x10250
   __TEXT.__const: 0x67a
   __TEXT.__getClass_cstr: 0x30
-  __TEXT.__gcc_except_tab: 0x14958
-  __TEXT.__cstring: 0x1eb25
+  __TEXT.__gcc_except_tab: 0x1495c
+  __TEXT.__cstring: 0x1ec4a
   __TEXT.__oslogstring: 0x14a
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0xa4f0

   __DATA_CONST.__objc_arraydata: 0x38
   __DATA_CONST.__got: 0x1420
   __AUTH_CONST.__const: 0x5390
-  __AUTH_CONST.__cfstring: 0xffe0
+  __AUTH_CONST.__cfstring: 0x10060
   __AUTH_CONST.__objc_const: 0x11490
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x3d8
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x4758
+  __AUTH_CONST.__auth_got: 0x4760
   __AUTH.__objc_data: 0x2a30
   __AUTH.__data: 0x40
   __DATA.__objc_ivar: 0x508

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 7529
-  Symbols:   15915
-  CStrings:  2533
+  Symbols:   15916
+  CStrings:  2537
 
Symbols:
+ __ZN7WebCore24DeprecatedGlobalSettings37setMediaResourceLoadTimeoutForTestingEj
Functions:
~ +[WebPreferences initialize] : 13124 -> 13140
~ -[WebFrame(WebInternal) _dragSourceEndedAt:operation:] : 396 -> 392
~ +[WebPreferences(WebPrivateInternalFeatures) _internalFeatures] : 14256 -> 14380
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 23952 -> 23972
CStrings:
+ "AppKit gestures for pointer events"
+ "Media Resource Load Timeout For Testing"
+ "MediaResourceLoadTimeoutForTesting"
+ "Test override for the timeout applied to each media resource load serviced by WebKit, in milliseconds (0 means use production default)"
+ "Use AppKit gestures to drive DOM pointer events directly, rather than deriving them from synthesized mouse events"
+ "UseAppKitGesturesForPointerEvents"
+ "WebKitMediaResourceLoadTimeoutForTesting"
+ "WebKitUseAppKitGesturesForPointerEvents"
- "AppKit gestures for manipulation surfaces"
- "Use AppKit gestures to drive manipulation surfaces"
- "UseAppKitGesturesForManipulationSurfaces"
- "WebKitUseAppKitGesturesForManipulationSurfaces"
```
