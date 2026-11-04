## com.apple.SafariPlatformSupport.Helper

> `/System/Library/PrivateFrameworks/SafariPlatformSupport.framework/Versions/Current/XPCServices/com.apple.SafariPlatformSupport.Helper.xpc/Contents/MacOS/com.apple.SafariPlatformSupport.Helper`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-7625.2.8.11.9
-  __TEXT.__text: 0xbb7c
-  __TEXT.__auth_stubs: 0x300
-  __TEXT.__objc_stubs: 0x2400
-  __TEXT.__objc_methlist: 0xfac
+7626.1.12.11.4
+  __TEXT.__text: 0xbf00
+  __TEXT.__auth_stubs: 0x320
+  __TEXT.__objc_stubs: 0x2520
+  __TEXT.__objc_methlist: 0xfcc
   __TEXT.__objc_classname: 0x5c7
-  __TEXT.__objc_methname: 0x3a91
-  __TEXT.__objc_methtype: 0x1522
-  __TEXT.__cstring: 0x51e
+  __TEXT.__objc_methname: 0x3bee
+  __TEXT.__objc_methtype: 0x1583
+  __TEXT.__cstring: 0x586
   __TEXT.__const: 0x50
-  __TEXT.__gcc_except_tab: 0xcfc
+  __TEXT.__gcc_except_tab: 0xd2c
   __TEXT.__oslogstring: 0x45a
-  __TEXT.__ustring: 0xd0
-  __TEXT.__unwind_info: 0x638
-  __DATA_CONST.__const: 0xa50
-  __DATA_CONST.__cfstring: 0x320
+  __TEXT.__ustring: 0x6c
+  __TEXT.__unwind_info: 0x658
+  __DATA_CONST.__const: 0xb20
+  __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_intobj: 0x18
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x198
-  __DATA_CONST.__got: 0x200
+  __DATA_CONST.__auth_got: 0x1a8
+  __DATA_CONST.__got: 0x218
   __DATA.__objc_const: 0x17f8
-  __DATA.__objc_selrefs: 0xd40
-  __DATA.__objc_ivar: 0xe0
+  __DATA.__objc_selrefs: 0xd78
+  __DATA.__objc_ivar: 0xe4
   __DATA.__objc_data: 0x3c0
-  __DATA.__data: 0xa40
+  __DATA.__data: 0xa48
   __DATA.__bss: 0xa0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices

   - /System/Library/Frameworks/JavaScriptCore.framework/Versions/A/JavaScriptCore
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
+  - /System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/Versions/A/AuthenticationServicesCore
   - /System/Library/PrivateFrameworks/PasswordManagerUI.framework/Versions/A/PasswordManagerUI
   - /System/Library/PrivateFrameworks/Safari.framework/Versions/A/Safari
   - /System/Library/PrivateFrameworks/SafariCore.framework/Versions/A/SafariCore

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 283
-  Symbols:   155
-  CStrings:  763
+  Functions: 293
+  Symbols:   160
+  CStrings:  774
 
Symbols:
+ _AutoFillFromICloudKeychainPreferenceKey
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_NSUserDefaults
+ __ZSt9terminatev
+ ___cxa_begin_catch
CStrings:
+ "@\"NSString\"16@?0@\"ASCredentialProvider\"8"
+ "@\"NSUserDefaults\""
+ "@24@0:8q16"
+ "B16@?0@\"ASCredentialProvider\"8"
+ "_credentialProviderForRow:"
+ "_credentialProviders"
+ "_enabledCredentialProvidersMayHaveChanged"
+ "_expandCredentialsString"
+ "_fetchCredentialsAndReloadUIWithEnabledCredentialProviders:"
+ "_firstCredentialProviderRow"
+ "_hasThirdPartyCredentialProviders"
+ "_isShowingCredentialProviders:"
+ "_observedSystemSafariDefaults"
+ "_reloadAndResizeForPasswordAutoFill"
+ "_shouldShowExpandCredentialsRow"
+ "_titleForCredentialProvider:"
+ "arrayWithCapacity:"
+ "displayName"
+ "extensionBundleID"
+ "externalExtension"
+ "getEnabledProvidersSortedForDisplaySynchronously"
+ "getEnabledProvidersSortedForDisplayWithCompletion:"
+ "isEqualToArray:"
+ "passwordsViewController:fillText:"
+ "passwordsViewController:selectedWiFiNetworkWithSSID:password:"
+ "presentAsChildOfView:completionHandler:didSelectWiFiNetworkHandler:"
+ "safari_browserDefaultsForcingSystemSafari:"
+ "safari_mapAndFilterObjectsUsingBlock:"
+ "v24@?0@\"NSString\"8@\"NSString\"16"
+ "v40@0:8@\"PMMiniPasswordsViewController\"16@\"NSString\"24@\"NSString\"32"
- "Other Passwords…"
- "Passwords…"
- "Passwords… (App Name)"
- "_additionalPasswordsString"
- "_credentialProviderExtensions"
- "_extensionPasswordsString:"
- "_fetchCredentialsAndReloadUIWithEnabledExtensionProviders:"
- "_firstOtherPasswordsRow"
- "displayNameForExtension:"
- "enabledExtensions"
- "fillPassword:"
- "fillUsername:"
- "fillVerificationCode:"
- "getEnabledExtensionsWithCompletion:"
- "passwordsViewController:fillPassword:"
- "passwordsViewController:fillUsername:"
- "passwordsViewController:fillVerificationCode:"
- "presentAsChildOfView:completionHandler:"
- "removeObserver:"
```
