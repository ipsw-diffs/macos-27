## SiriObservation

> `/System/Library/PrivateFrameworks/SiriObservation.framework/Versions/A/SiriObservation`

```diff

-3605.31.1.14.2
-  __TEXT.__text: 0x10334
-  __TEXT.__objc_methlist: 0x1310
+3610.11.2.4.1
+  __TEXT.__text: 0x10900
+  __TEXT.__objc_methlist: 0x1320
   __TEXT.__const: 0x88
-  __TEXT.__gcc_except_tab: 0xfc
-  __TEXT.__oslogstring: 0x5d6
-  __TEXT.__cstring: 0x1b61
-  __TEXT.__unwind_info: 0x6d8
+  __TEXT.__gcc_except_tab: 0x124
+  __TEXT.__oslogstring: 0x62d
+  __TEXT.__cstring: 0x1bfe
+  __TEXT.__unwind_info: 0x700
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x80
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8e0
+  __DATA_CONST.__objc_selrefs: 0x8f0
   __DATA_CONST.__objc_superrefs: 0x80
   __DATA_CONST.__objc_arraydata: 0xc0
   __DATA_CONST.__got: 0x180
-  __AUTH_CONST.__const: 0x7f0
+  __AUTH_CONST.__const: 0x850
   __AUTH_CONST.__cfstring: 0xa20
-  __AUTH_CONST.__objc_const: 0x1fd0
+  __AUTH_CONST.__objc_const: 0x2030
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x1ac
+  __DATA.__objc_ivar: 0x1b8
   __DATA.__data: 0x420
   __DATA.__bss: 0x30
   __DATA_DIRTY.__objc_data: 0x500

   - /System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 475
-  Symbols:   1130
-  CStrings:  236
+  Functions: 480
+  Symbols:   1143
+  CStrings:  241
 
Symbols:
+ -[SOMediaNowPlayingObserver _fetchIsProxyGroupPlayerWithCompletion:]
+ -[SOMediaNowPlayingObserver _setProxyGroupPlayer:]
+ -[SOMediaNowPlayingObserver _updateProxyGroupPlayerStateWithCompletion:]
+ GCC_except_table150
+ GCC_except_table154
+ GCC_except_table248
+ _MRMediaRemoteGetDeviceInfo
+ _OBJC_IVAR_$_SOClockTimerManager._isTimerAlarmCoordinationEnabled
+ _OBJC_IVAR_$_SOMediaNowPlayingObserver._proxyGroupPlayerStateGeneration
+ _OBJC_IVAR_$_SOMediaNowPlayingObserver._proxyGroupPlayerStateGroup
+ ___66-[SOMediaNowPlayingObserver mediaRemoteActiveDeviceInfoDidChange:]_block_invoke_2
+ ___68-[SOMediaNowPlayingObserver _fetchIsProxyGroupPlayerWithCompletion:]_block_invoke
+ ___68-[SOMediaNowPlayingObserver getProxyGroupPlayerStateWithCompletion:]_block_invoke_2
+ ___72-[SOMediaNowPlayingObserver _updateProxyGroupPlayerStateWithCompletion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e24_v24?0^v8^{__CFError=}16l
+ ___block_descriptor_56_e8_32bs40w_e8_v12?0B8l
+ _objc_msgSend$_fetchIsProxyGroupPlayerWithCompletion:
+ _objc_msgSend$_setProxyGroupPlayer:
+ _objc_msgSend$_updateProxyGroupPlayerStateWithCompletion:
+ _objc_msgSend$compare:
- -[SOMediaNowPlayingObserver _isProxyGroupPlayer]
- -[SOMediaNowPlayingObserver _updateProxyGroupPlayerState]
- GCC_except_table243
- _CFRelease
- _MRMediaRemoteCopyDeviceInfo
- _objc_msgSend$_isProxyGroupPlayer
- _objc_msgSend$_updateProxyGroupPlayerState
CStrings:
+ "%s %p Ignored a stale isProxyGroupPlayer = %d"
+ "%s Unable to fetch local device info: %@"
+ "-[SOMediaNowPlayingObserver _fetchIsProxyGroupPlayerWithCompletion:]_block_invoke"
+ "-[SOMediaNowPlayingObserver _updateProxyGroupPlayerStateWithCompletion:]_block_invoke"
+ "v12@?0B8"
+ "v24@?0^v8^{__CFError=}16"
- "-[SOMediaNowPlayingObserver _isProxyGroupPlayer]"
```
