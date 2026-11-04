## AirPlayReceiverKit

> `/System/Library/PrivateFrameworks/AirPlayReceiverKit.framework/Versions/A/AirPlayReceiverKit`

```diff

-1005.13.1.0.0
-  __TEXT.__text: 0x266fc
+1015.5.1.0.0
+  __TEXT.__text: 0x26ab0
   __TEXT.__objc_methlist: 0x1404
-  __TEXT.__cstring: 0x8a1b
+  __TEXT.__cstring: 0x8afb
   __TEXT.__const: 0x92
   __TEXT.__oslogstring: 0x424
-  __TEXT.__gcc_except_tab: 0x744
+  __TEXT.__gcc_except_tab: 0x7bc
   __TEXT.__unwind_info: 0xe80
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1308
+  __DATA_CONST.__objc_selrefs: 0x1318
   __DATA_CONST.__objc_superrefs: 0x48
-  __DATA_CONST.__got: 0x870
+  __DATA_CONST.__got: 0x888
   __AUTH_CONST.__const: 0xcc0
   __AUTH_CONST.__cfstring: 0x1840
-  __AUTH_CONST.__objc_const: 0x2250
+  __AUTH_CONST.__objc_const: 0x2270
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x2d0
-  __DATA.__objc_ivar: 0x298
+  __DATA.__objc_ivar: 0x29c
   __DATA.__data: 0x490
   __DATA.__bss: 0x2c
   __DATA_DIRTY.__objc_data: 0xa0

   - /System/Library/PrivateFrameworks/CoreUtils.framework/Versions/A/CoreUtils
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 963
-  Symbols:   1986
-  CStrings:  836
+  Functions: 964
+  Symbols:   1992
+  CStrings:  841
 
Symbols:
+ _OBJC_IVAR_$_APRKMediaPlayer._isCurrentInterstitialEventIDAwaitingEvents
+ _kFigEndPointPlaybackSessionKey_LoudnessInfo
+ _kFigEndpointPlaybackSessionProxiedProperty_LoudnessInfo
+ _kFigEndpointPlaybackSessionProxiedProperty_PrefersAudioVideoVariants
+ _objc_msgSend$setLoudnessInfo:
+ _objc_msgSend$setPrefersAudioVideoVariants:
Functions:
~ -[APRKMediaPlayer _insertPlayQueueItemWithDictionary:] : 2276 -> 2472
~ -[APRKMediaPlayer _setPropertyWithDictionary:] : 4140 -> 4788
~ -[APRKStreamRenderer videoFrameSize] : 252 -> 300
~ -[APRKMediaPlayer _insertPlayQueueItemWithDictionary:].cold.6 : 40 -> 56
+ -[APRKMediaPlayer _insertPlayQueueItemWithDictionary:].cold.8
CStrings:
+ "1015.5.1"
+ "Applying deferred current interstitial event %@"
+ "Current interstitial event %@ arrived before interstitialEvents; deferring"
+ "LoudnessInfo property set to %@"
+ "LoudnessInfo set to %@"
+ "PrefersAudioVideoVariants property set to %d."
+ "Q\xf0\xb1"
- "1005.13.1"
- "Q\xf0\xa1"
```
