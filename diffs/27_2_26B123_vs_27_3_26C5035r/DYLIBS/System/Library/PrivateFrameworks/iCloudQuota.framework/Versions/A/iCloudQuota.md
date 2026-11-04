## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/Versions/A/iCloudQuota`

```diff

-301.24.1.5.0
-  __TEXT.__text: 0x75e84
-  __TEXT.__objc_methlist: 0x5394
+301.24.2.4.0
+  __TEXT.__text: 0x772a8
+  __TEXT.__objc_methlist: 0x53ec
   __TEXT.__const: 0x1370
-  __TEXT.__cstring: 0x4d81
+  __TEXT.__cstring: 0x4dd1
   __TEXT.__gcc_except_tab: 0x578
-  __TEXT.__oslogstring: 0x77be
+  __TEXT.__oslogstring: 0x79ae
   __TEXT.__dlopen_cstrs: 0x35b
-  __TEXT.__ustring: 0x4
+  __TEXT.__ustring: 0xe
   __TEXT.__swift5_typeref: 0x7f8
   __TEXT.__swift5_capture: 0x39c
   __TEXT.__swift5_reflstr: 0x2f8

   __TEXT.__swift_as_cont: 0xe0
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_protos: 0x1c
-  __TEXT.__unwind_info: 0x24c0
+  __TEXT.__unwind_info: 0x24e8
   __TEXT.__eh_frame: 0x1500
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xa20
+  __DATA_CONST.__const: 0xa48
   __DATA_CONST.__objc_classlist: 0x358
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2c50
+  __DATA_CONST.__objc_selrefs: 0x2cb8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x268
   __DATA_CONST.__objc_arraydata: 0x728
   __DATA_CONST.__got: 0x718
-  __AUTH_CONST.__const: 0x2660
-  __AUTH_CONST.__cfstring: 0x6160
+  __AUTH_CONST.__const: 0x2680
+  __AUTH_CONST.__cfstring: 0x61c0
   __AUTH_CONST.__objc_const: 0xa790
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_arrayobj: 0x90

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2923
-  Symbols:   5071
-  CStrings:  1512
+  Functions: 2932
+  Symbols:   5092
+  CStrings:  1521
 
Symbols:
+ +[_ICQDeviceInfo _canFillTemplate:words:]
+ +[_ICQDeviceInfo filledTemplate:itemCount:albumName:]
+ +[_ICQDeviceInfo filledTemplateForItemCount:albumName:lookup:]
+ +[_ICQDeviceInfo normalizedAlbumName:]
+ +[_ICQDeviceInfo wordsToReplaceForItemCount:albumName:]
+ +[_ICQHelperFunctions fillTemplate:words:]
+ -[ICQOffer exactMessageSpecificationForReason:bundleId:]
+ -[ICQOffer inAppAlertKeyForReason:placement:]
+ GCC_except_table14
+ _ICQBannerSourceAppFeatureMessagingInfo
+ ___42+[_ICQHelperFunctions fillTemplate:words:]_block_invoke
+ ___block_descriptor_32_e31_q24?0"NSString"8"NSString"16l
+ _objc_msgSend$_canFillTemplate:words:
+ _objc_msgSend$compare:options:range:
+ _objc_msgSend$fillTemplate:words:
+ _objc_msgSend$filledTemplate:itemCount:albumName:
+ _objc_msgSend$sortedArrayUsingComparator:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$stringWithCapacity:
+ _objc_msgSend$templateKeyForItemCount:
+ _objc_msgSend$whitespaceAndNewlineCharacterSet
+ _objc_msgSend$wordsToReplaceForItemCount:albumName:
- GCC_except_table37
CStrings:
+ "%$AlbumName"
+ "%{public}@ has no value, skipping the template"
+ "ICQBannerSourceAppFeatureMessagingInfo"
+ "No appFeatureMessagingInfo entry for reason: %{public}@, placement: %{public}@, bundleId: %{public}@ in offer %{public}@"
+ "albumName is empty or whitespace, treating as nil"
+ "appFeatureMessagingInfo entry for reason: %{public}@, placement: %{public}@ in offer %{public}@ has an alertKey of unexpected type %{public}@"
+ "appFeatureMessagingInfo entry for reason: %{public}@, placement: %{public}@ in offer %{public}@ has no SHOW_INLINE_ALERT link with an alertKey"
+ "q24@?0@\"NSString\"8@\"NSString\"16"
+ "\u2068%@\u2069"
```
