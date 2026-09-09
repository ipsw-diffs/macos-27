## com.apple.driver.AppleUSBDeviceMux

> `com.apple.driver.AppleUSBDeviceMux`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 571.0.0.0.1
   __TEXT.__const: 0x34
   __TEXT.__cstring: 0x1359
-  __TEXT_EXEC.__text: 0x5a14
+  __TEXT_EXEC.__text: 0x5b24
   __TEXT_EXEC.__auth_stubs: 0x4c0
   __DATA.__data: 0xc8
   __DATA.__common: 0x68
Functions:
~ __ZN17AppleUSBDeviceMux10bmsReleaseEP17BulkUSBMuxSessionPKc : 136 -> 140
~ __ZN17AppleUSBDeviceMux9bmsRetainEP17BulkUSBMuxSessionPKc : 92 -> 96
~ __ZN17AppleUSBDeviceMux13bubSetSessionEP14USBWriteBufferP17BulkUSBMuxSession : 84 -> 88
~ __ZN17AppleUSBDeviceMux9MetaClassC1Ev : 72 -> 76
~ __ZN17AppleUSBDeviceMuxC2EPK11OSMetaClass : 68 -> 72
~ __ZN17AppleUSBDeviceMuxC1EPK11OSMetaClass : 68 -> 72
~ __ZN17AppleUSBDeviceMuxD0Ev : 68 -> 72
~ __ZN17AppleUSBDeviceMux9MetaClassC2Ev : 72 -> 76
~ __ZNK17AppleUSBDeviceMux9MetaClass5allocEv : 120 -> 124
~ __ZN17AppleUSBDeviceMuxC1Ev : 104 -> 108
~ __ZN17AppleUSBDeviceMuxC2Ev : 104 -> 108
~ __ZN17AppleUSBDeviceMux5startEP9IOService : 1016 -> 1020
~ __ZN17AppleUSBDeviceMux17asyncReadCompleteEP6__mbufij : 1024 -> 1028
~ __ZN17AppleUSBDeviceMux18asyncWriteCompleteEP14USBWriteBufferij : 1096 -> 1100
~ __ZN17AppleUSBDeviceMux22asyncMbufWriteCompleteEP6__mbufij : 604 -> 608
~ __ZN17AppleUSBDeviceMux13sessionUpcallEP19IOSocketEventSourceP8__socketP17BulkUSBMuxSession : 460 -> 464
~ __ZN17AppleUSBDeviceMux12startUSBReadEv : 644 -> 648
~ __ZN17AppleUSBDeviceMux14resyncWithHostEv : 472 -> 476
~ __ZN17AppleUSBDeviceMux23allocateUSBWriteBuffersEv : 280 -> 284
~ __ZN17AppleUSBDeviceMux14freeUSBBuffersEv : 208 -> 212
~ __ZN17AppleUSBDeviceMux22allocateUSBReadBuffersEv : 204 -> 208
~ __ZN17AppleUSBDeviceMux10timerFiredEP8OSObjectP18IOTimerEventSource : 144 -> 148
~ __ZN17AppleUSBDeviceMux4freeEv : 360 -> 364
~ __ZN17AppleUSBDeviceMux14cleanupSessionEP17BulkUSBMuxSession : 340 -> 344
~ __ZN17AppleUSBDeviceMux16getUSBReadBufferEPP6__mbufi : 288 -> 292
~ __ZN17AppleUSBDeviceMux20recoverUSBReadBufferEPcjS0_ : 64 -> 68
~ __ZN17AppleUSBDeviceMux18setPropertiesGatedEP8OSObject : 244 -> 248
~ __ZN17AppleUSBDeviceMux7messageEjP9IOServicePv : 948 -> 952
~ __ZN17AppleUSBDeviceMux12setTimeoutMSEj : 172 -> 176
~ __ZN17AppleUSBDeviceMux11reportStatsEb : 184 -> 188
~ __ZN17AppleUSBDeviceMux14freeBufferListEP14USBWriteBuffer : 260 -> 264
~ __ZN17AppleUSBDeviceMux14sendMuxSegmentEP17BulkUSBMuxSession : 964 -> 968
~ __ZN17AppleUSBDeviceMux19handleConnectResultEP17BulkUSBMuxSessioni : 660 -> 664
~ __ZN17AppleUSBDeviceMux6muxLogEhbPKcz : 44 -> 48
~ __ZN17AppleUSBDeviceMux10sendMuxRSTEP17BulkUSBMuxSessionbPKcz : 92 -> 96
~ __ZN17AppleUSBDeviceMux14writeMbufToUSBEP6__mbufj : 652 -> 656
~ __ZN17AppleUSBDeviceMux10newSessionEP6tcphdr : 968 -> 972
~ __ZN17AppleUSBDeviceMux10sendMuxRSTEP6tcphdrbPKcz : 44 -> 48
~ __ZN17AppleUSBDeviceMux17handleMuxTCPInputEP6__mbuf : 1608 -> 1612
~ __ZN17AppleUSBDeviceMux26handleMuxHostLogLevelInputEP6__mbuf : 188 -> 192
~ __ZN17AppleUSBDeviceMux21handleMuxVersionInputEP6__mbuf : 384 -> 388
~ __ZN17AppleUSBDeviceMux14writeMbufToUSBEP6__mbuf : 316 -> 320
~ __ZN17AppleUSBDeviceMux14handleMuxInputEP6__mbuf : 1944 -> 1948
~ __ZN17AppleUSBDeviceMux11dumpUSBLogsEv : 336 -> 340
~ __ZN17AppleUSBDeviceMux13muxLogLimitedEhbPKcz : 180 -> 184
~ __ZN17AppleUSBDeviceMux8writeZLPEv : 72 -> 76
~ __ZN17AppleUSBDeviceMux14writeToUSBPipeEP14USBWriteBuffer : 584 -> 588
~ __ZN17AppleUSBDeviceMux13startUSBWriteEP14USBWriteBufferjb : 360 -> 364
~ __ZN17AppleUSBDeviceMux7vmuxLogEhbPKcPc : 360 -> 364
~ __ZN17AppleUSBDeviceMux11vsendMuxRSTEP6tcphdrbPKcPc : 440 -> 444
~ __ZN17AppleUSBDeviceMux14socketIsClosedEP8__socket : 196 -> 200
~ _GLOBAL__sub_I_AppleUSBDeviceMux.cpp : 80 -> 84
~ __ZN19IOSocketEventSource9MetaClassC1Ev : 72 -> 76
~ __ZN19IOSocketEventSourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN19IOSocketEventSourceC1EPK11OSMetaClass : 52 -> 56
~ __ZN19IOSocketEventSourceD0Ev : 68 -> 72
~ __ZN19IOSocketEventSource9MetaClassC2Ev : 72 -> 76
~ __ZNK19IOSocketEventSource9MetaClass5allocEv : 104 -> 108
~ __ZN19IOSocketEventSourceC1Ev : 88 -> 92
~ __ZN19IOSocketEventSourceC2Ev : 88 -> 92
~ __ZN19IOSocketEventSource4initEP8OSObjectP8__socketPvPFvS1_PS_S3_S4_E : 200 -> 204
~ __ZN19IOSocketEventSource17socketEventSourceEP8OSObjectP8__socketPvPFvS1_PS_S3_S4_E : 252 -> 256
~ __ZN19IOSocketEventSource12handleUpcallEv : 124 -> 128
~ __ZN19IOSocketEventSource12checkForWorkEv : 76 -> 80
~ _GLOBAL__sub_I_IOSocketEventSource.cpp : 80 -> 84
~ _ZN17AppleUSBDeviceMux10bmsReleaseEP17BulkUSBMuxSessionPKc.cold.1 : 56 -> 60
~ _ZN17AppleUSBDeviceMux9bmsRetainEP17BulkUSBMuxSessionPKc.cold.1 : 56 -> 60
~ _ZN17AppleUSBDeviceMux14freeBufferListEP14USBWriteBuffer.cold.1 : 56 -> 60
CStrings:
+ "18:51:22"
+ "Aug 30 2026"
- "21:49:08"
- "Aug 11 2026"
```
