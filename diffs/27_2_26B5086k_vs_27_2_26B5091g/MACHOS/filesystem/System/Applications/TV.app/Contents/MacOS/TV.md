## TV

> `/System/Applications/TV.app/Contents/MacOS/TV`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__DATA.__thread_vars`

```diff

-1.7.1.18.1
-  __TEXT.__text: 0xde8780
-  __TEXT.__auth_stubs: 0x6e00
-  __TEXT.__objc_stubs: 0x26d40
+1.7.1.22.1
+  __TEXT.__text: 0xde8bd0
+  __TEXT.__auth_stubs: 0x6dd0
+  __TEXT.__objc_stubs: 0x26d00
   __TEXT.__init_offsets: 0x24c
-  __TEXT.__objc_methlist: 0x1b070
-  __TEXT.__const: 0xb99d9
-  __TEXT.__cstring: 0x76f3d
-  __TEXT.__objc_classname: 0x396e
-  __TEXT.__objc_methname: 0x39ceb
-  __TEXT.__objc_methtype: 0x12509
+  __TEXT.__objc_methlist: 0x1afe0
+  __TEXT.__const: 0xb9959
+  __TEXT.__cstring: 0x76f5b
+  __TEXT.__objc_classname: 0x3961
+  __TEXT.__objc_methname: 0x39c9b
+  __TEXT.__objc_methtype: 0x124d2
   __TEXT.__constg_swiftt: 0x1a54
   __TEXT.__swift5_typeref: 0xb44
   __TEXT.__swift5_reflstr: 0x1465

   __TEXT.__swift5_capture: 0x414
   __TEXT.__swift5_proto: 0xf0
   __TEXT.__swift5_types: 0xcc
-  __TEXT.__gcc_except_tab: 0xc0604
-  __TEXT.__oslogstring: 0x24595
+  __TEXT.__gcc_except_tab: 0xc06ac
+  __TEXT.__oslogstring: 0x245e9
   __TEXT.__ustring: 0x98
-  __TEXT.__unwind_info: 0x55e28
+  __TEXT.__unwind_info: 0x55e48
   __TEXT.__eh_frame: 0x120
-  __DATA_CONST.__const: 0x142fd0
-  __DATA_CONST.__cfstring: 0x26440
-  __DATA_CONST.__objc_classlist: 0xdb8
+  __DATA_CONST.__const: 0x142fe8
+  __DATA_CONST.__cfstring: 0x264e0
+  __DATA_CONST.__objc_classlist: 0xdb0
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x4e0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x140
-  __DATA_CONST.__objc_superrefs: 0x8c0
+  __DATA_CONST.__objc_superrefs: 0x8b8
   __DATA_CONST.__objc_intobj: 0x528
   __DATA_CONST.__objc_arraydata: 0x7c0
   __DATA_CONST.__objc_arrayobj: 0x450
   __DATA_CONST.__objc_doubleobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x3718
+  __DATA_CONST.__auth_got: 0x3700
   __DATA_CONST.__got: 0x2378
   __DATA_CONST.__auth_ptr: 0x408
-  __DATA.__objc_const: 0x2ad10
-  __DATA.__objc_selrefs: 0xe1a0
-  __DATA.__objc_ivar: 0x1340
-  __DATA.__objc_data: 0xab50
+  __DATA.__objc_const: 0x2ac00
+  __DATA.__objc_selrefs: 0xe188
+  __DATA.__objc_ivar: 0x1338
+  __DATA.__objc_data: 0xab00
   __DATA.__data: 0x5e7c
   __DATA.__thread_vars: 0x18
   __DATA.__thread_data: 0x10
-  __DATA.__common: 0xee80
-  __DATA.__bss: 0x19710
+  __DATA.__common: 0xee90
+  __DATA.__bss: 0x19720
   __RESTRICT.__restrict: 0x0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /System/Library/PrivateFrameworks/SkyLight.framework/Versions/A/SkyLight
   - /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/Versions/A/SymptomDiagnosticReporter
   - /System/Library/PrivateFrameworks/TVLibrary.framework/Versions/A/TVLibrary
+  - /System/Library/PrivateFrameworks/TVPlayback.framework/Versions/A/TVPlayback
   - /System/Library/PrivateFrameworks/VideosUI.framework/Versions/A/VideosUI
   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /System/Library/PrivateFrameworks/WatchListKit.framework/Versions/A/WatchListKit

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 65794
-  Symbols:   2891
-  CStrings:  31883
+  Functions: 65786
+  Symbols:   2889
+  CStrings:  31879
 
Symbols:
+ _OBJC_CLASS_$_TVPTimeRange
- _CMTimeMakeWithSeconds
- _CMTimeRangeGetIntersection
- _CMTimeRangeMake
CStrings:
+ "%s/AMPLibraryAgent-1.7.1.22"
+ "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 10581, true)) )"
+ "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 11401, true)) )"
+ "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 11594, true)) )"
+ "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 16405, true)) )"
+ "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 10548, true)) )"
+ "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 10633, true)) )"
+ "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15745, true)) )"
+ "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15784, true)) )"
+ "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15803, true)) )"
+ "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 18128, true)) )"
+ "( ((inItem->downloadManager) != __null) && (((inItem->downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inItem->downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15788, true)) )"
+ "( ((inWorkTaskInfo) != __null) && (((inWorkTaskInfo)->magic == 'dwti') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inWorkTaskInfo)->magic == 'dwti'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 8527, true)) )"
+ "1.7.1.22"
+ "13.7.1.22"
+ "Apple TV 1.7.1.22"
+ "GB"
+ "PreferredSignLanguage"
+ "SignLanguageEnabled"
+ "ase"
+ "bfi"
+ "down> Replacing default media selection with sign-language selection for %{public}@"
+ "hls-url"
+ "public.accessibility.sign-language-interpretation"
- "%s/AMPLibraryAgent-1.7.1.18"
- "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 10536, true)) )"
- "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 11356, true)) )"
- "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 11549, true)) )"
- "( ((downloadManager) != __null) && (((downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 16360, true)) )"
- "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 10503, true)) )"
- "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 10588, true)) )"
- "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15700, true)) )"
- "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15739, true)) )"
- "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15758, true)) )"
- "( ((inDM) != __null) && (((inDM)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inDM)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 18083, true)) )"
- "( ((inItem->downloadManager) != __null) && (((inItem->downloadManager)->magic == 'down') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inItem->downloadManager)->magic == 'down'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 15743, true)) )"
- "( ((inWorkTaskInfo) != __null) && (((inWorkTaskInfo)->magic == 'dwti') ? true : HandleAssert(AssertCategory::None, \"Assertion failure (expected to be true)\", \"(inWorkTaskInfo)->magic == 'dwti'\", \"/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/TVDesktop/iTunes/Application/DownloadManager.cpp\", 8482, true)) )"
- "1.7.1.18"
- "13.7.1.18"
- "@32@0:8d16d24"
- "@64@0:8{?={?=qiIq}{?=qiIq}}16"
- "Apple TV 1.7.1.18"
- "B24@0:8d16"
- "Start time: %f End time: %f Duration: %f"
- "TVPTimeRange"
- "Td,N,V_startTime"
- "_startTime"
- "inCloudArtistID.NotEmpty()"
- "initWithCMTimeRange:"
- "initWithStartTime:duration:"
- "intersectTimeRange:"
- "signLanguage"
```
