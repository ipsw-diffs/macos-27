## LinkPresentation

> `/System/iOSSupport/System/Library/Frameworks/LinkPresentation.framework/Versions/A/LinkPresentation`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-319.1.0.0.0
-  __TEXT.__text: 0xfb130
-  __TEXT.__objc_methlist: 0x103e4
+319.2.0.0.0
+  __TEXT.__text: 0xfbab8
+  __TEXT.__objc_methlist: 0x10434
   __TEXT.__cstring: 0x8151
-  __TEXT.__gcc_except_tab: 0x21298
+  __TEXT.__gcc_except_tab: 0x213bc
   __TEXT.__const: 0x24a4
   __TEXT.__ustring: 0x46a
-  __TEXT.__oslogstring: 0x377b
+  __TEXT.__oslogstring: 0x392b
   __TEXT.__dlopen_cstrs: 0x8bf
   __TEXT.__swift5_typeref: 0xaf6
   __TEXT.__constg_swiftt: 0x864

   __TEXT.__swift_as_ret: 0x28
   __TEXT.__swift_as_cont: 0x4c
   __TEXT.__swift5_assocty: 0x108
-  __TEXT.__unwind_info: 0x8260
+  __TEXT.__unwind_info: 0x8288
   __TEXT.__eh_frame: 0xdc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7480
+  __DATA_CONST.__objc_selrefs: 0x74b8
   __DATA_CONST.__objc_protorefs: 0xb8
   __DATA_CONST.__objc_superrefs: 0x540
   __DATA_CONST.__objc_arraydata: 0x1638
-  __DATA_CONST.__got: 0xe60
+  __DATA_CONST.__got: 0xe68
   __AUTH_CONST.__const: 0x1f98
   __AUTH_CONST.__cfstring: 0xcb00
-  __AUTH_CONST.__objc_const: 0x2bdc8
+  __AUTH_CONST.__objc_const: 0x2be78
   __AUTH_CONST.__objc_intobj: 0x390
   __AUTH_CONST.__objc_arrayobj: 0x630
   __AUTH_CONST.__objc_dictobj: 0xc8

   __AUTH_CONST.__auth_got: 0x10a8
   __AUTH.__objc_data: 0x28e0
   __AUTH.__data: 0x2f8
-  __DATA.__objc_ivar: 0x1708
+  __DATA.__objc_ivar: 0x1718
   __DATA.__data: 0x1ac8
   __DATA.__bss: 0x1e00
   __DATA.__common: 0x1d8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6672
-  Symbols:   14413
-  CStrings:  2148
+  Functions: 6680
+  Symbols:   14433
+  CStrings:  2154
 
Symbols:
+ +[LPMetadataProvider _copyWebViewConfigurationWithNetworkAttributionSourceApplicationBundleIdentifier:sourceApplicationSecondaryIdentifier:]
+ -[LPFetcherConfiguration networkAttributionSourceApplicationBundleIdentifier]
+ -[LPFetcherConfiguration setNetworkAttributionSourceApplicationBundleIdentifier:]
+ -[LPMediaAssetFetcher _streamingVideo]
+ -[LPMetadataProviderSpecializationContext initWithOriginalURL:postRedirectURL:MIMEType:webView:hasLoadedResource:shouldFetchSubresources:allowedSpecializations:fetchIsNotUserInitiated:networkAttributionSourceApplicationBundleIdentifier:]
+ -[LPMetadataProviderSpecializationContext networkAttributionSourceApplicationBundleIdentifier]
+ -[LPVideo _networkAttributionSourceApplicationBundleIdentifier]
+ -[LPVideo set_networkAttributionSourceApplicationBundleIdentifier:]
+ GCC_except_table150
+ _AVURLAssetClientBundleIdentifierKey
+ _OBJC_IVAR_$_LPFetcherConfiguration._networkAttributionSourceApplicationBundleIdentifier
+ _OBJC_IVAR_$_LPMediaAssetFetcher._networkAttributionSourceApplicationBundleIdentifier
+ _OBJC_IVAR_$_LPMetadataProviderSpecializationContext._networkAttributionSourceApplicationBundleIdentifier
+ _OBJC_IVAR_$_LPVideo._networkAttributionSourceApplicationBundleIdentifier
+ _objc_msgSend$_copyWebViewConfigurationWithNetworkAttributionSourceApplicationBundleIdentifier:sourceApplicationSecondaryIdentifier:
+ _objc_msgSend$_streamingVideo
+ _objc_msgSend$initWithOriginalURL:postRedirectURL:MIMEType:webView:hasLoadedResource:shouldFetchSubresources:allowedSpecializations:fetchIsNotUserInitiated:networkAttributionSourceApplicationBundleIdentifier:
+ _objc_msgSend$networkAttributionSourceApplicationBundleIdentifier
+ _objc_msgSend$setNetworkAttributionSourceApplicationBundleIdentifier:
+ _objc_msgSend$setSourceApplicationBundleIdentifier:
+ _objc_msgSend$set_networkAttributionSourceApplicationBundleIdentifier:
+ _objc_msgSend$set_sourceApplicationBundleIdentifier:
- -[LPMetadataProviderSpecializationContext initWithOriginalURL:postRedirectURL:MIMEType:webView:hasLoadedResource:shouldFetchSubresources:allowedSpecializations:fetchIsNotUserInitiated:]
- _objc_msgSend$initWithOriginalURL:postRedirectURL:MIMEType:webView:hasLoadedResource:shouldFetchSubresources:allowedSpecializations:fetchIsNotUserInitiated:
CStrings:
+ "From %@"
+ "Invitation to Join Subscription"
+ "LPFetcherGroup<%d>: allocating web view for %@ (attributed=%d)"
+ "LPImageFetcher<%d>: allocating fallback web view, did not have webViewForProcessSharing (attributed=%d)"
+ "LPMediaAssetFetcher<%d>: creating asset (attributed=%d)"
+ "LPMetadataProvider<%d>: attributing network activity to %{public}@"
+ "LPMetadataProvider<%d>: creating web view (attributed=%d)"
+ "LPMetadataProvider<%d>: ignoring network attribution set after fetching started"
+ "LPMetadataProvider<%d>: not reusing client-provided WKWebView for fetching"
+ "LPRawURLContentsFetcher<%d>: allocating fallback web view, did not have webViewForProcessSharing (attributed=%d)"
- "Invitation from %@"
- "LPImageFetcher<%d>: allocating fallback web view, did not have webViewForProcessSharing"
- "LPRawURLContentsFetcher<%d>: allocating fallback web view, did not have webViewForProcessSharing"
- "Subscription Invitation"
```
