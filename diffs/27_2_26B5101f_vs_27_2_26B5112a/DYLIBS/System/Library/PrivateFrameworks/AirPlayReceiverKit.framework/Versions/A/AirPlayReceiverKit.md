## AirPlayReceiverKit

> `/System/Library/PrivateFrameworks/AirPlayReceiverKit.framework/Versions/A/AirPlayReceiverKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1005.12.1.0.0
-  __TEXT.__text: 0x266e0
+1005.13.1.0.0
+  __TEXT.__text: 0x266fc
   __TEXT.__objc_methlist: 0x1404
   __TEXT.__cstring: 0x8a1b
   __TEXT.__const: 0x92

   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1300
+  __DATA_CONST.__objc_selrefs: 0x1308
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__got: 0x870
   __AUTH_CONST.__const: 0xcc0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 963
-  Symbols:   2067
+  Symbols:   2069
   CStrings:  836
 
Symbols:
+ _APSIsHomeAccessory
+ _objc_msgSend$setAudiovisualBackgroundPlaybackPolicy:
Functions:
~ -[APRKMediaPlayer initWithP2PWiFiSupport:isInterstitialPlayer:playerSessionID:] : 988 -> 1008
~ -[APRKMediaPlayer _insertPlayQueueItemWithDictionary:] : 2268 -> 2276
CStrings:
+ "1005.13.1"
- "1005.12.1"
```
