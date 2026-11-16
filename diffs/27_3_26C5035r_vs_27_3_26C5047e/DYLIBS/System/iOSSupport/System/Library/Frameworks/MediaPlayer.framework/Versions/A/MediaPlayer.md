## MediaPlayer

> `/System/iOSSupport/System/Library/Frameworks/MediaPlayer.framework/Versions/A/MediaPlayer`

```diff

-4026.300.13.0.0
-  __TEXT.__text: 0x20e09c
-  __TEXT.__objc_methlist: 0x217cc
+4026.300.20.0.0
+  __TEXT.__text: 0x20e970
+  __TEXT.__objc_methlist: 0x21804
   __TEXT.__const: 0x4da0
-  __TEXT.__cstring: 0x29e35
-  __TEXT.__oslogstring: 0xfef0
-  __TEXT.__gcc_except_tab: 0xa490
+  __TEXT.__cstring: 0x29ea5
+  __TEXT.__oslogstring: 0x10070
+  __TEXT.__gcc_except_tab: 0xa4c8
   __TEXT.__dlopen_cstrs: 0x25c
   __TEXT.__ustring: 0x1dc
   __TEXT.__constg_swiftt: 0x32c

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xc220
+  __TEXT.__unwind_info: 0xc240
   __TEXT.__eh_frame: 0x4a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xae28
+  __DATA_CONST.__const: 0xae68
   __DATA_CONST.__objc_classlist: 0x1110
   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x368
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x103c8
+  __DATA_CONST.__objc_selrefs: 0x103e8
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0xbb0
   __DATA_CONST.__objc_arraydata: 0x830
-  __DATA_CONST.__got: 0x1ee8
-  __AUTH_CONST.__const: 0x4bc0
-  __AUTH_CONST.__cfstring: 0x20740
-  __AUTH_CONST.__objc_const: 0x382a0
+  __DATA_CONST.__got: 0x1ef0
+  __AUTH_CONST.__const: 0x4c00
+  __AUTH_CONST.__cfstring: 0x20780
+  __AUTH_CONST.__objc_const: 0x382b8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0xeb8
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x1c70
+  __AUTH_CONST.__auth_got: 0x1c88
   __AUTH.__objc_data: 0x6ff0
   __AUTH.__data: 0x100
   __DATA.__objc_ivar: 0x2228
   __DATA.__data: 0x2c30
-  __DATA.__bss: 0x1bf0
+  __DATA.__bss: 0x1c00
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x3b10
   __DATA_DIRTY.__data: 0x100

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13711
-  Symbols:   29768
-  CStrings:  5962
+  Functions: 13719
+  Symbols:   29786
+  CStrings:  5972
 
Symbols:
+ +[MPHomeUserMonitor fallbackIsExplicitAllowed]
+ -[MPModelLibraryPlaylistEditController currentPlaylist]
+ -[MPRequestResponseController setDemandsReload]
+ GCC_except_table142
+ GCC_except_table69
+ GCC_except_table73
+ _SANDBOX_CHECK_NO_REPORT
+ ___46+[MPHomeUserMonitor fallbackIsExplicitAllowed]_block_invoke
+ ___47-[MPRequestResponseController setDemandsReload]_block_invoke
+ ___74-[MPModelLibraryPlaylistEditPlaylistDataSource loadEntriesWithCompletion:]_block_invoke_2
+ ___74-[MPModelLibraryPlaylistEditPlaylistDataSource loadEntriesWithCompletion:]_block_invoke_3
+ ___block_descriptor_32_e30_16?0"MPModelPlaylistEntry"8l
+ ___block_descriptor_34_e30_v16?0"MPModelPlaylistEntry"8l
+ ___block_descriptor_57_e8_32s40bs48w_e45_v24?0"MPArtworkRepresentation"8"NSError"16lw48l8s32l8s40l8
+ _fallbackIsExplicitAllowed.homeDefaults
+ _fallbackIsExplicitAllowed.onceToken
+ _getpid
+ _objc_msgSend$fallbackIsExplicitAllowed
+ _objc_msgSend$setDemandsReload
+ _os_unfair_recursive_lock_lock
+ _sandbox_check
- GCC_except_table141
- GCC_except_table95
- ___block_descriptor_56_e8_32s40bs48w_e45_v24?0"MPArtworkRepresentation"8"NSError"16lw48l8s32l8s40l8
CStrings:
+ "@16@?0@\"MPModelPlaylistEntry\"8"
+ "GuestExplicitContentIsAllowed"
+ "MPHomeUserMonitor.fallbackIsExplicitAllowed: cannot read com.apple.home, using MPHomeUserPreferenceAllowExplicitFallbackValue=%{BOOL}u"
+ "RRC %{public}@: Canceling request [demanded by client]"
+ "RRC %{public}@: Demands reload [request by client]"
+ "RRC %{public}@: Reloading [automatic, demanded by client]"
+ "RRCDemandsReload"
+ "[RCE:%{public}@] timeout | finishing [default timeout] status=%{public}@"
+ "com.apple.home"
+ "user-preference-read"
```
