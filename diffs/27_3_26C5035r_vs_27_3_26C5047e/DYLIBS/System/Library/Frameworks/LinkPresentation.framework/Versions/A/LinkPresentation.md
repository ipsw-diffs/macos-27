## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/Versions/A/LinkPresentation`

```diff

-319.1.0.0.0
-  __TEXT.__text: 0xf53cc
-  __TEXT.__objc_methlist: 0x103fc
-  __TEXT.__cstring: 0x7c8b
-  __TEXT.__gcc_except_tab: 0x20568
+319.2.0.0.0
+  __TEXT.__text: 0xf5d80
+  __TEXT.__objc_methlist: 0x1044c
+  __TEXT.__cstring: 0x7c7b
+  __TEXT.__gcc_except_tab: 0x20688
   __TEXT.__const: 0x1cf4
   __TEXT.__ustring: 0x3f6
-  __TEXT.__oslogstring: 0x3564
+  __TEXT.__oslogstring: 0x3704
   __TEXT.__dlopen_cstrs: 0x5ac
   __TEXT.__swift5_typeref: 0x61e
   __TEXT.__constg_swiftt: 0x58c

   __TEXT.__swift_as_entry: 0x28
   __TEXT.__swift_as_ret: 0x20
   __TEXT.__swift_as_cont: 0x44
-  __TEXT.__unwind_info: 0x7d38
+  __TEXT.__unwind_info: 0x7d60
   __TEXT.__eh_frame: 0xa58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x1d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6ec0
+  __DATA_CONST.__objc_selrefs: 0x6ef8
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x598
   __DATA_CONST.__objc_arraydata: 0x1638
-  __DATA_CONST.__got: 0xd88
+  __DATA_CONST.__got: 0xd90
   __AUTH_CONST.__const: 0x3358
   __AUTH_CONST.__cfstring: 0xd5c0
-  __AUTH_CONST.__objc_const: 0x2ae80
+  __AUTH_CONST.__objc_const: 0x2af30
   __AUTH_CONST.__objc_intobj: 0x2a0
   __AUTH_CONST.__objc_arrayobj: 0x630
   __AUTH_CONST.__objc_dictobj: 0xc8

   __AUTH_CONST.__auth_got: 0xcb0
   __AUTH.__objc_data: 0x2930
   __AUTH.__data: 0x160
-  __DATA.__objc_ivar: 0x1734
+  __DATA.__objc_ivar: 0x1744
   __DATA.__data: 0x18a0
   __DATA.__bss: 0x1f58
   __DATA.__common: 0x1c8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6366
-  Symbols:   13926
-  CStrings:  2156
+  Functions: 6374
+  Symbols:   13948
+  CStrings:  2162
 
Symbols:
+ +[LPMetadataProvider _copyWebViewConfigurationWithNetworkAttributionSourceApplicationBundleIdentifier:sourceApplicationSecondaryIdentifier:]
+ -[LPFetcherConfiguration networkAttributionSourceApplicationBundleIdentifier]
+ -[LPFetcherConfiguration setNetworkAttributionSourceApplicationBundleIdentifier:]
+ -[LPMediaAssetFetcher _streamingVideo]
+ -[LPMetadataProviderSpecializationContext initWithOriginalURL:postRedirectURL:MIMEType:webView:hasLoadedResource:shouldFetchSubresources:allowedSpecializations:fetchIsNotUserInitiated:networkAttributionSourceApplicationBundleIdentifier:]
+ -[LPMetadataProviderSpecializationContext networkAttributionSourceApplicationBundleIdentifier]
+ -[LPVideo _networkAttributionSourceApplicationBundleIdentifier]
+ -[LPVideo set_networkAttributionSourceApplicationBundleIdentifier:]
+ GCC_except_table125
+ GCC_except_table141
+ GCC_except_table91
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
