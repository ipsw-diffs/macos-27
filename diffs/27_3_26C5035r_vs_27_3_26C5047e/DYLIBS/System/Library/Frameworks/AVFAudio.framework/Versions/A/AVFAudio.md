## AVFAudio

> `/System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio`

```diff

-794.303.0.0.0
-  __TEXT.__text: 0xecaf0
+794.305.1.0.0
+  __TEXT.__text: 0xecb74
   __TEXT.__realtime: 0x1d64
   __TEXT.__objc_methlist: 0x4eb4
   __TEXT.__const: 0xd20

   __TEXT.__swift5_assocty: 0x78
   __TEXT.__swift5_proto: 0x14
   __TEXT.__gcc_except_tab: 0xd7c8
-  __TEXT.__oslogstring: 0x144a9
+  __TEXT.__oslogstring: 0x144b4
   __TEXT.__unwind_info: 0x59c0
   __TEXT.__eh_frame: 0x2a8
   __TEXT.__objc_stubs: 0x0

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3765
-  Symbols:   7992
+  Symbols:   7993
   CStrings:  2877
 
Symbols:
+ _AVAudioSessionInterruptionEndLikelyToBeResumableKey
Functions:
~ -[AVAudioIONode setVoiceProcessingEnabled:error:] : 2744 -> 2748
~ -[AVAudioEngine mainMixerNode] : 384 -> 488
~ sub_1b3f89b5c -> sub_1b4229bc8 : 128 -> 152
CStrings:
+ "%25s:%-5d Engine#%p: error: couldn't connect mixer to output node, format: %s"
- "%25s:%-5d Engine#%p: error: couldn't connect mixer to output node!"
```
