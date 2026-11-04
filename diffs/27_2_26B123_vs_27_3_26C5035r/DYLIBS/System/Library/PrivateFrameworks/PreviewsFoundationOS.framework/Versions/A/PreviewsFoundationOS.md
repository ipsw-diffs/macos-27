## PreviewsFoundationOS

> `/System/Library/PrivateFrameworks/PreviewsFoundationOS.framework/Versions/A/PreviewsFoundationOS`

```diff

-24.20.10.0.0
-  __TEXT.__text: 0x137abc
+24.30.6.0.0
+  __TEXT.__text: 0x138ee0
   __TEXT.__objc_methlist: 0x274
-  __TEXT.__const: 0xfcdc
+  __TEXT.__const: 0xfdbc
   __TEXT.__gcc_except_tab: 0x24
-  __TEXT.__cstring: 0x5ee9
-  __TEXT.__swift5_typeref: 0x5511
+  __TEXT.__cstring: 0x5f59
+  __TEXT.__swift5_typeref: 0x5571
   __TEXT.__swift5_capture: 0x2f20
-  __TEXT.__constg_swiftt: 0x59fc
-  __TEXT.__swift5_reflstr: 0x226c
-  __TEXT.__swift5_fieldmd: 0x3e00
+  __TEXT.__constg_swiftt: 0x5a18
+  __TEXT.__swift5_reflstr: 0x227c
+  __TEXT.__swift5_fieldmd: 0x3e28
   __TEXT.__swift5_builtin: 0x154
   __TEXT.__swift5_assocty: 0x1298
   __TEXT.__swift5_proto: 0x8c8
-  __TEXT.__swift5_types: 0x598
+  __TEXT.__swift5_types: 0x59c
   __TEXT.__swift5_protos: 0xd0
   __TEXT.__swift5_mpenum: 0x80
-  __TEXT.__swift_as_entry: 0x1d0
-  __TEXT.__swift_as_ret: 0x1b8
-  __TEXT.__swift_as_cont: 0x2d8
+  __TEXT.__swift_as_entry: 0x1d4
+  __TEXT.__swift_as_ret: 0x1bc
+  __TEXT.__swift_as_cont: 0x2dc
   __TEXT.__oslogstring: 0x72c
-  __TEXT.__unwind_info: 0x6990
-  __TEXT.__eh_frame: 0x83d4
+  __TEXT.__unwind_info: 0x69e0
+  __TEXT.__eh_frame: 0x844c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4b0
+  __DATA_CONST.__objc_selrefs: 0x4c0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x10
-  __DATA_CONST.__got: 0x9a0
-  __AUTH_CONST.__const: 0xf510
+  __DATA_CONST.__got: 0x9b0
+  __AUTH_CONST.__const: 0xf580
   __AUTH_CONST.__cfstring: 0x80
   __AUTH_CONST.__objc_const: 0x25b8
-  __AUTH_CONST.__auth_got: 0x18a8
+  __AUTH_CONST.__auth_got: 0x18d8
   __AUTH.__objc_data: 0x1f8
   __AUTH.__data: 0x2728
   __DATA.__objc_ivar: 0x8
-  __DATA.__data: 0x69d0
-  __DATA.__bss: 0xdf90
+  __DATA.__data: 0x69f8
+  __DATA.__bss: 0xe010
   __DATA.__common: 0x18
   __DATA_DIRTY.__data: 0x38
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine

   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 7820
-  Symbols:   2377
-  CStrings:  432
+  Functions: 7839
+  Symbols:   2387
+  CStrings:  437
 
Symbols:
+ _objc_msgSend$pathWithComponents:
+ _objc_msgSend$stringByDeletingLastPathComponent
+ _symbolic SS4path_t
+ _symbolic Ss_Ss4patht
+ _symbolic _____ 20PreviewsFoundationOS16CrashReportErrorV015DyldLibraryLoaddF0V13FailureReasonO
+ _symbolic _____ySs_Ss4pathtG 17_StringProcessing5RegexV
+ _symbolic _____ySs_Ss4patht_G 17_StringProcessing5RegexV5MatchV
+ _symbolic _____ySs_Ss4patht_GSg 17_StringProcessing5RegexV5MatchV
+ _symbolic _____y_____G s16PartialRangeFromV SS5IndexV
+ _type_layout_string 20PreviewsFoundationOS16CrashReportErrorV015DyldLibraryLoaddF0V13FailureReasonO
CStrings:
+ " couldn't load `"
+ " crashed because the App Sandbox blocked loading "
+ "#/'(?<path>[^']+)' \\(file system sandbox blocked open\\(\\)\\)/#"
+ "#/Library not loaded: (?<path>[^\\n]+)/#"
+ "__PREVIEWS_SIMULATE_ASSISTIVE_TECHNOLOGY"
+ "` because the App Sandbox blocked access to it. Previews loads your app's code after the sandbox is applied, so libraries outside the app's container need explicit access.\n\nTo fix this, add `"
+ "` environment variable in your scheme's Run settings, or embed "
- "(dyld: launch, loading dependent libraries(.|\\n)*)?Library not loaded: @rpath/(?<library>.+?(?=/))"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Errors/CrashReportError+DyldLibraryLoadCrashError.swift"
```
