## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/Versions/A/SpotlightDaemon`

```diff

-2465.1.2.0.0
-  __TEXT.__text: 0xc6904
-  __TEXT.__objc_methlist: 0x4bec
+2465.1.3.0.0
+  __TEXT.__text: 0xc6b0c
+  __TEXT.__objc_methlist: 0x4c04
   __TEXT.__const: 0x410
-  __TEXT.__cstring: 0x9ae6
+  __TEXT.__cstring: 0x9b3a
   __TEXT.__gcc_except_tab: 0x45bc
   __TEXT.__oslogstring: 0xc21f
-  __TEXT.__unwind_info: 0x3440
+  __TEXT.__unwind_info: 0x3448
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c40
+  __DATA_CONST.__objc_selrefs: 0x3c60
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x148
   __DATA_CONST.__objc_arraydata: 0x2f0
   __DATA_CONST.__got: 0xbc0
   __AUTH_CONST.__const: 0x5868
-  __AUTH_CONST.__cfstring: 0x7f60
+  __AUTH_CONST.__cfstring: 0x7fc0
   __AUTH_CONST.__objc_const: 0x6358
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x360

   __AUTH_CONST.__auth_got: 0x1060
   __AUTH.__objc_data: 0x280
   __DATA.__objc_ivar: 0x538
-  __DATA.__data: 0x3f8
-  __DATA.__bss: 0x208
+  __DATA.__data: 0x3f0
+  __DATA.__bss: 0x1c0
   __DATA.__common: 0x4
   __DATA_DIRTY.__objc_data: 0xfa0
-  __DATA_DIRTY.__data: 0x158
-  __DATA_DIRTY.__bss: 0x5b8
+  __DATA_DIRTY.__data: 0x160
+  __DATA_DIRTY.__bss: 0x600
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3425
-  Symbols:   6956
-  CStrings:  2610
+  Functions: 3427
+  Symbols:   6960
+  CStrings:  2613
 
Symbols:
+ -[SPCoreSpotlightTask _knownDisabledBundleIDsFromBundleIDs:excludingFPBundleIDs:]
+ -[SPCoreSpotlightTask _makeNotificationSourcesQueryStringWithBundleIDs:]
+ -[SPCoreSpotlightTask _makePrefsQueryStringWithPrefsDisabledBundles:]
+ GCC_except_table102
+ GCC_except_table105
+ GCC_except_table106
+ GCC_except_table82
+ GCC_except_table83
+ GCC_except_table87
+ GCC_except_table98
+ _objc_msgSend$_knownDisabledBundleIDsFromBundleIDs:excludingFPBundleIDs:
+ _objc_msgSend$_makeNotificationSourcesQueryStringWithBundleIDs:
+ _objc_msgSend$allDisabledBundlesSet
+ _objc_msgSend$federationDisabledBundles
- -[SPCoreSpotlightTask _makePrefsQueryStringWithBundleIDs:prefsDisabledBundles:]
- GCC_except_table100
- GCC_except_table104
- GCC_except_table80
- GCC_except_table81
- GCC_except_table85
- GCC_except_table91
- GCC_except_table96
- GCC_except_table97
- _objc_msgSend$_makePrefsQueryStringWithBundleIDs:prefsDisabledBundles:
CStrings:
+ " && _kMDItemBundleID!=\"com.apple.people.screenTimeRequest\""
+ "(!((%@) || (%@) || (%@) || (%@) || ((%@)%@)))"
+ "(_kMDItemBundleID = \"com.apple.usernotificationsd\" && %@)"
+ "kMDItemCreator"
- "(!((%@) || (%@) || (%@) || ((%@) && _kMDItemBundleID!=\"com.apple.people.screenTimeRequest\")))"
```
