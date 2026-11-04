## AVFAudio

> `/System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio`

```diff

-794.210.0.0.0
-  __TEXT.__text: 0xeca78
+794.303.0.0.0
+  __TEXT.__text: 0xecaf0
   __TEXT.__realtime: 0x1d64
   __TEXT.__objc_methlist: 0x4eb4
   __TEXT.__const: 0xd20

   __DATA_CONST.__got: 0x590
   __AUTH_CONST.__const: 0x7848
   __AUTH_CONST.__cfstring: 0x2ea0
-  __AUTH_CONST.__objc_const: 0x7990
+  __AUTH_CONST.__objc_const: 0x79b0
   __AUTH_CONST.__weak_auth_got: 0x38
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x258
   __AUTH_CONST.__auth_got: 0x1188
   __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x348
+  __DATA.__objc_ivar: 0x34c
   __DATA.__data: 0x710
   __DATA.__bss: 0x6e0
   __DATA_DIRTY.__objc_data: 0x1e00

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3765
-  Symbols:   7991
+  Symbols:   7992
   CStrings:  2877
 
Symbols:
+ _OBJC_IVAR_$_AudioPlayerImpl._weakSelf
+ __ZL25LocalPlayerHandleCallbackP15AudioPlayerImpljmPKv
- __ZL25LocalPlayerHandleCallbackP13AVAudioPlayerjmPKv
Functions:
~ -[AudioPlayerImpl dealloc] : 340 -> 352
~ -[AVAudioPlayer(AVAudioPlayerPriv) initBase] : 1080 -> 1092
~ __ZL25LocalPlayerHandleCallbackP13AVAudioPlayerjmPKv -> __ZL25LocalPlayerHandleCallbackP15AudioPlayerImpljmPKv : 196 -> 276
~ sub_1b3b1a6b8 -> sub_1b3f89720 : 56 -> 64
~ sub_1b3b1a6f0 -> sub_1b3f89760 : 92 -> 100
```
