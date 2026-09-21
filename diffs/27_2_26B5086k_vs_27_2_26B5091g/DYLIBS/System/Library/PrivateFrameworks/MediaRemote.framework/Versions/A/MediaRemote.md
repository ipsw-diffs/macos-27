## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote`

```diff

-4026.200.11.0.0
-  __TEXT.__text: 0x30eeb4
-  __TEXT.__objc_methlist: 0x2b92c
+4026.200.15.0.0
+  __TEXT.__text: 0x30eeb0
+  __TEXT.__objc_methlist: 0x2b934
   __TEXT.__const: 0x5d8
-  __TEXT.__cstring: 0x2c532
-  __TEXT.__oslogstring: 0xd3b8
+  __TEXT.__cstring: 0x2c525
+  __TEXT.__oslogstring: 0xd42d
   __TEXT.__gcc_except_tab: 0x58c0
   __TEXT.__dlopen_cstrs: 0x40b
   __TEXT.__ustring: 0x7b8
-  __TEXT.__unwind_info: 0xe2f8
+  __TEXT.__unwind_info: 0xe300
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf158
+  __DATA_CONST.__objc_selrefs: 0xf160
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0xff0
   __DATA_CONST.__objc_arraydata: 0x260
   __DATA_CONST.__got: 0x1428
-  __AUTH_CONST.__const: 0xa420
+  __AUTH_CONST.__const: 0xa440
   __AUTH_CONST.__cfstring: 0x23e00
   __AUTH_CONST.__objc_const: 0x466c0
   __AUTH_CONST.__objc_intobj: 0x4f8

   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0xa90
-  __AUTH.__objc_data: 0x8430
+  __AUTH.__objc_data: 0x5d20
   __DATA.__objc_ivar: 0x32f4
   __DATA.__data: 0x1a08
   __DATA.__bss: 0x8a8
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x2d50
+  __DATA_DIRTY.__objc_data: 0x5460
   __DATA_DIRTY.__data: 0x88
   __DATA_DIRTY.__bss: 0x5a0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 20607
-  Symbols:   35174
-  CStrings:  6511
+  Functions: 20610
+  Symbols:   35178
+  CStrings:  6512
 
Symbols:
+ -[MRMediaRemoteService requestPushToStartTokenWithCompletion:]
+ -[MRNowPlayingPushTokenManager requestStartToken]
+ -[MRUserSettings remoteSessionStalenessGraceInterval]
+ __49-[MRNowPlayingPushTokenManager requestStartToken]_block_invoke
+ ___49-[MRNowPlayingPushTokenManager requestStartToken]_block_invoke
+ ___53-[MRUserSettings remoteSessionStalenessGraceInterval]_block_invoke
+ ___62-[MRMediaRemoteService requestPushToStartTokenWithCompletion:]_block_invoke
+ _objc_msgSend$requestPushToStartTokenWithCompletion:
+ remoteSessionStalenessGraceInterval.__interval
+ remoteSessionStalenessGraceInterval.__once
- -[MRMediaRemoteService remoteSessionAssertionsWithCompletion:]
- -[MRUserSettings remoteSessionDefaultAssertionInterval]
- ___55-[MRUserSettings remoteSessionDefaultAssertionInterval]_block_invoke
- ___62-[MRMediaRemoteService remoteSessionAssertionsWithCompletion:]_block_invoke
- remoteSessionDefaultAssertionInterval.__interval
- remoteSessionDefaultAssertionInterval.__once
CStrings:
+ "[MRNowPlayingPushTokenManager] requestStartToken"
+ "[MRNowPlayingPushTokenManager] requestStartToken failed: %{public}@"
+ "remoteSessionStalenessGraceInterval"
- "assertions"
- "remoteSessionDefaultAssertionInterval"
```
