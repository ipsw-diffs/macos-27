## ScreenReaderBrailleDriver

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/ScreenReaderBrailleDriver.framework/Versions/A/ScreenReaderBrailleDriver`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`

```diff

 1048.3.0.0.0
-  __TEXT.__text: 0xc594
+  __TEXT.__text: 0xc360
   __TEXT.__objc_methlist: 0x274
   __TEXT.__const: 0x34c
   __TEXT.__gcc_except_tab: 0x28
   __TEXT.__cstring: 0x569
   __TEXT.__oslogstring: 0x2db
-  __TEXT.__unwind_info: 0x2b8
+  __TEXT.__unwind_info: 0x3b0
   __TEXT.__objc_stubs: 0x800
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__objc_classname: 0x48
Functions:
~ _SCRDAlva6SeriesAppendKeyEvent : 656 -> 644
~ _SCRDBrailleNoteExtractEventsFromBuffer : 772 -> 760
~ _SCRDAdvanceBufferToPacketStart : 140 -> 128
~ _SCRDAppendFullKeystrokeFromEvent : 176 -> 164
~ _SCRDPostSleepNotification : 212 -> 200
~ _SCRDEasyLinkExtractEventsFromBuffer : 944 -> 932
~ _SCRDEasyLinkExtractKeyboardEventsFromBuffer : 508 -> 496
~ _SCRDEurobrailleExtractEventsFromBuffer : 984 -> 972
~ __appendSwitchKeyboardEvent : 708 -> 696
~ __appendJoystickCommandKeyboardEvent : 320 -> 308
~ __appendFunctionKeyboardEvent : 224 -> 212
~ -[SCRDFileReader invalidateWithWait:] : 148 -> 136
~ -[SCRDFileReader .cxx_destruct] : 76 -> 64
~ _SCRDFreedomScientificExtractEventsFromBuffer : 1760 -> 1748
~ __SCRDHIMSExtractEventsFromBuffer : 512 -> 500
~ __SCRDHIMSSyncBrailleAppendEventsFromKeyPacket : 152 -> 140
~ __SCRDHIMSBrailleEDGEAppendEventsFromKeyPacket : 400 -> 388
~ _SCRDHandyTechExtractEventsFromBuffer : 588 -> 576
~ __appendEventForKeyCode : 1216 -> 1204
~ _SCRDHumanwareExtractEventsFromBuffer : 476 -> 464
~ _SCRDMDVAppendKeyPressEvent : 916 -> 904
~ __appendShiftKeyEvent : 132 -> 120
~ _SCRDMDVSerialCreatePacketsFromBuffer : 392 -> 380
~ _SCRDMDVSerialExtractEventsFromBuffer : 536 -> 524
~ _SCRDMDVSerialAppendRouterPressEvent : 268 -> 256
~ _SCRDMDVSerialAppendBrailleKeyPressEvent : 188 -> 176
~ _SCRDMDVHIDAppendRouterPressEvent : 144 -> 132
~ _SCRDNinepointSystemsCebraExtractKeyboardEventsFromBuffer : 548 -> 536
~ _SCRDNinepointSystemsNinepointExtractKeyboardEventsFromBuffer : 344 -> 332
~ _SCRDNinepointSystemsNinepointCreateWriteBuffer : 280 -> 272
~ _SCRDPapenmeierReleasePacket : 72 -> 60
~ _SCRDPapenmeierCreatePacketFromBuffer : 744 -> 736
~ _SCRDPapenmeierExtractEventsFromBuffer : 1636 -> 1620
~ __appendProtocolBFrontAndRearEvents : 400 -> 388
~ _SCRDSeikaExtractEventsFromBuffer : 1488 -> 1472
~ __notetakerAppendButtonEventFromBuffer : 372 -> 360
~ _SCRDSerialDeviceCalloutDevicePath : 128 -> 116
~ __notificationHandler : 108 -> 96
~ +[SCRDUSBDeviceCallbackManager sharedManager] : 84 -> 72
~ ___45+[SCRDUSBDeviceCallbackManager sharedManager]_block_invoke : 64 -> 52
~ ___46-[SCRDUSBDeviceCallbackManager addCompletion:]_block_invoke : 144 -> 132
~ ___49-[SCRDUSBDeviceCallbackManager removeCompletion:]_block_invoke : 92 -> 80
~ ___56-[SCRDUSBDeviceCallbackManager completionWithReference:]_block_invoke : 132 -> 120
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[SCRDUSBDeviceCallbackManager .cxx_destruct] : 68 -> 56
~ _SCRDKGSExtractEventsFromBuffer : 2896 -> 2884
```
