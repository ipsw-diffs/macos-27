## AMPLibraryAgent

> `/System/Library/PrivateFrameworks/AMPLibrary.framework/Versions/A/Support/AMPLibraryAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1.7.3.10.0
-  __TEXT.__text: 0x5edbe0
-  __TEXT.__auth_stubs: 0x3910
+1.7.3.21.0
+  __TEXT.__text: 0x5ee560
+  __TEXT.__auth_stubs: 0x3920
   __TEXT.__objc_stubs: 0x55c0
   __TEXT.__init_offsets: 0xcc
   __TEXT.__objc_methlist: 0x1494
-  __TEXT.__cstring: 0x44c43
+  __TEXT.__cstring: 0x44c6e
   __TEXT.__const: 0x76d10
   __TEXT.__objc_classname: 0x3ef
   __TEXT.__objc_methtype: 0x18d9

   __TEXT.__swift5_typeref: 0x3a
   __TEXT.__swift5_fieldmd: 0x20
   __TEXT.__swift5_types: 0x8
-  __TEXT.__gcc_except_tab: 0x30d70
-  __TEXT.__oslogstring: 0x2b847
+  __TEXT.__gcc_except_tab: 0x30df4
+  __TEXT.__oslogstring: 0x2bac1
   __TEXT.__objc_methname: 0x59b0
-  __TEXT.__unwind_info: 0x16910
+  __TEXT.__unwind_info: 0x16928
   __TEXT.__eh_frame: 0xf0
   __DATA_CONST.__const: 0x43058
-  __DATA_CONST.__cfstring: 0x116a0
+  __DATA_CONST.__cfstring: 0x116c0
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x78

   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_intobj: 0x90
-  __DATA_CONST.__auth_got: 0x1c98
+  __DATA_CONST.__auth_got: 0x1ca0
   __DATA_CONST.__got: 0xac0
   __DATA_CONST.__auth_ptr: 0x150
   __DATA.__objc_const: 0x1fb8

   __DATA.__objc_ivar: 0xe8
   __DATA.__objc_data: 0x7a0
   __DATA.__data: 0x15c8
-  __DATA.__bss: 0x33a48
+  __DATA.__bss: 0x33a58
   __DATA.__common: 0x3270
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 17921
-  Symbols:   1304
-  CStrings:  13485
+  Functions: 17927
+  Symbols:   1305
+  CStrings:  13496
 
Symbols:
+ _CFDateGetTimeIntervalSinceDate
CStrings:
+ "%s/AMPLibraryAgent-1.7.3.21"
+ "(outChangeDataVar->mValidFields & kAMPLPlaylistChangeDataValidField_Var_CloudArtworkVariantsInfo) != kAMPLPlaylistChangeDataValidFields_Var_None"
+ "**ERROR**: SendCloudDAAPStoreRequest - WaitForLockedCompletion() failed! status:%d client:%{public}s request:%{public}s"
+ "1.7.3.21"
+ "13.7.3.21"
+ "AMPLibraryAgent version: 1.7.3.21"
+ "Detected expired or expiring JWT token for client id %{public}s."
+ "Received new JWT token for client id %{public}s. Expiration %{public}@."
+ "Requesting new JWT token for client id %{public}s."
+ "album-group-query-request"
+ "channel-client> Shutting down. TurnOff:%c"
+ "channel-client> Starting up. PushAvailability:%c"
+ "cloud> Canceling CloudDaapStoreRequest..."
+ "cloud> CloudDAAPStoreRequest completed."
+ "cloudArtworkVariantsInfo"
+ "codecList->numCodecs < 30"
+ "icml> Processing AlbumAPNSChannelIDWillChange message. newChannelID:%{public}s existingChannelID:%{public}s cid:%{public}s album:%{public}s"
+ "icml> Unregistered channel name for album that was removed from library! cid:%{public}s album:%{public}s"
+ "jwt_service"
- "%s/AMPLibraryAgent-1.7.3.10"
- "(outChangeDataVar->mValidFields & kAMPLPlaylistChangeDataValidField_Var_ArtworkVariantsInfo) != kAMPLPlaylistChangeDataValidFields_Var_None"
- "**ERROR**: WaitForLockedCompletion() failed! status:%d client:%{public}s request:%{public}s"
- "1.7.3.10"
- "13.7.3.10"
- "AMPLibraryAgent version: 1.7.3.10"
- "artworkVariantsInfo"
- "info.mExpectedReleaseDate != 0"
```
