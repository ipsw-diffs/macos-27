## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

 2260.15.1.0.0
-  __TEXT.__text: 0x7c3f34
+  __TEXT.__text: 0x7c3f28
   __TEXT.__realtime: 0xea4
   __TEXT.__objc_methlist: 0x3a090
   __TEXT.__const: 0x184a8
   __TEXT.__cstring: 0x9bd3c
-  __TEXT.__oslogstring: 0x143df1
+  __TEXT.__oslogstring: 0x143de9
   __TEXT.__gcc_except_tab: 0x326c
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56

   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
   Functions: 35384
-  Symbols:   54614
+  Symbols:   54612
   CStrings:  33447
 
Symbols:
- _objc_msgSend$setupLocalABTestSwitches
- _objc_msgSend$setupLocalOnOffSwitches
Functions:
~ __48-[VCMediaStreamManager registerBlocksForService]_block_invoke.295 : 524 -> 548
~ -[VCSwitchManager initializeLocalSwitches] : 704 -> 668
CStrings:
+ " [%s] %s:%d SwitchManager: Non-seed build - using master local switch: %08X"
- " [%s] %s:%d SwitchManager: A/B testing turned off - using master local switch: %08X"
```
