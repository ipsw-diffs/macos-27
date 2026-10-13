## WebKitLegacy

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-625.2.7.1.0
-  __TEXT.__text: 0x15c9d4
+625.2.8.11.6
+  __TEXT.__text: 0x15ca74
   __TEXT.__objc_methlist: 0xf4b8
   __TEXT.__const: 0x234
   __TEXT.__getClass_cstr: 0x12
   __TEXT.__dlsym_cstr: 0x39
-  __TEXT.__gcc_except_tab: 0x12dac
-  __TEXT.__cstring: 0x1b7bf
+  __TEXT.__gcc_except_tab: 0x12db4
+  __TEXT.__cstring: 0x1b8ba
   __TEXT.__oslogstring: 0x14a
   __TEXT.__unwind_info: 0x9b60
   __TEXT.__eh_frame: 0x88

   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x1008
   __AUTH_CONST.__const: 0x50c0
-  __AUTH_CONST.__cfstring: 0xe460
+  __AUTH_CONST.__cfstring: 0xe4e0
   __AUTH_CONST.__objc_const: 0xfc50
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x2d0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x4610
+  __AUTH_CONST.__auth_got: 0x4618
   __AUTH.__objc_data: 0x2440
   __AUTH.__data: 0x38
   __DATA.__objc_ivar: 0x488

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 7223
-  Symbols:   14323
-  CStrings:  2160
+  Symbols:   14324
+  CStrings:  2164
 
Symbols:
+ __ZN7WebCore24DeprecatedGlobalSettings37setMediaResourceLoadTimeoutForTestingEj
Functions:
~ +[WebPreferences initialize] : 11700 -> 11716
~ +[WebPreferences(WebPrivateInternalFeatures) _internalFeatures] : 12560 -> 12684
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 21316 -> 21336
CStrings:
+ "Media Resource Load Timeout For Testing"
+ "MediaResourceLoadTimeoutForTesting"
+ "Test override for the timeout applied to each media resource load serviced by WebKit, in milliseconds (0 means use production default)"
+ "WebKitMediaResourceLoadTimeoutForTesting"
```
