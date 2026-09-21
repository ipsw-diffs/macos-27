## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2260.9.1.0.0
-  __TEXT.__text: 0x7befc8
+2260.11.1.0.0
+  __TEXT.__text: 0x7bff34
   __TEXT.__realtime: 0xea4
-  __TEXT.__objc_methlist: 0x39e30
+  __TEXT.__objc_methlist: 0x39f30
   __TEXT.__const: 0x184a8
-  __TEXT.__cstring: 0x9b6cf
-  __TEXT.__oslogstring: 0x14240c
-  __TEXT.__gcc_except_tab: 0x324c
+  __TEXT.__cstring: 0x9b6ec
+  __TEXT.__oslogstring: 0x142815
+  __TEXT.__gcc_except_tab: 0x3258
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x1b4a8
+  __TEXT.__unwind_info: 0x1b4e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x508
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x18530
+  __DATA_CONST.__objc_selrefs: 0x185a0
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x1240
   __DATA_CONST.__objc_arraydata: 0x2790
-  __DATA_CONST.__got: 0x1b70
+  __DATA_CONST.__got: 0x1b00
   __AUTH_CONST.__const: 0x8a08
-  __AUTH_CONST.__cfstring: 0x29200
-  __AUTH_CONST.__objc_const: 0x6c678
+  __AUTH_CONST.__cfstring: 0x29220
+  __AUTH_CONST.__objc_const: 0x6c768
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x4e00
   __AUTH_CONST.__objc_arrayobj: 0x1d58
   __AUTH_CONST.__objc_doubleobj: 0x210
   __AUTH_CONST.__objc_floatobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x2d0
-  __AUTH_CONST.__auth_got: 0x2ba0
+  __AUTH_CONST.__auth_got: 0x2ba8
   __AUTH.__objc_data: 0x140
-  __AUTH.__data: 0xc8
-  __DATA.__objc_ivar: 0x7698
-  __DATA.__data: 0x7df0
-  __DATA.__bss: 0x998
+  __AUTH.__data: 0x8
+  __DATA.__objc_ivar: 0x76b4
+  __DATA.__data: 0x1e20
+  __DATA.__bss: 0xad8
   __DATA.__common: 0x9
   __DATA_DIRTY.__objc_data: 0xcd00
-  __DATA_DIRTY.__data: 0x428
-  __DATA_DIRTY.__bss: 0x938
+  __DATA_DIRTY.__data: 0x6420
+  __DATA_DIRTY.__bss: 0x7e8
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35313
-  Symbols:   54508
-  CStrings:  33368
+  Functions: 35338
+  Symbols:   54543
+  CStrings:  33380
 
Symbols:
+ +[VCAudioToolboxAudioComponentMock activeInstanceCount]
+ +[VCAudioToolboxAudioComponentMock isMockingSessionActive]
+ -[VCAVFoundationCapture secondaryCameraRequestSizeForAspectRatio:]
+ -[VCAudioToolboxAudioComponentMock autorelease]
+ -[VCAudioToolboxAudioComponentMock release]
+ -[VCAudioToolboxAudioComponentMock retainCount]
+ -[VCAudioToolboxAudioComponentMock retain]
+ -[VCAudioTransmitterConfig setShouldCapBitrateForWatchRelay:]
+ -[VCAudioTransmitterConfig shouldCapBitrateForWatchRelay]
+ -[VCCallSession isRemoteWatchRelayDeviceWithDeviceType:]
+ -[VCCoreAudio_AudioUnitMock autorelease]
+ -[VCCoreAudio_AudioUnitMock beginSession]
+ -[VCCoreAudio_AudioUnitMock endSession]
+ -[VCCoreAudio_AudioUnitMock isMockingEnabled]
+ -[VCCoreAudio_AudioUnitMock release]
+ -[VCCoreAudio_AudioUnitMock retainCount]
+ -[VCCoreAudio_AudioUnitMock retain]
+ -[VCRTPHistory dealloc]
+ -[VCVideoStream canReuseTransportsForStreamConfigs:]
+ -[VCVideoStream expectedTransportArrayCountForStreamConfigs:]
+ -[VCVideoStream transportArrayContainsRTXTransport]
+ -[VCVideoStream transportStreamCountForStreamConfig:]
+ -[VCVideoStream willCreateRTXTransportForStreamConfig:]
+ GCC_except_table145
+ GCC_except_table147
+ GCC_except_table149
+ GCC_except_table318
+ GCC_except_table374
+ GCC_except_table464
+ OBJC_IVAR_$_VCAVFoundationCapture._dualCaptureRear1440x1080
+ OBJC_IVAR_$_VCAudioToolboxAudioComponentMock._instancesLock
+ OBJC_IVAR_$_VCAudioTransmitter._shouldCapBitrateForWatchRelay
+ OBJC_IVAR_$_VCAudioTransmitterConfig._shouldCapBitrateForWatchRelay
+ OBJC_IVAR_$_VCMockIDSDatagramChannel._enqueueLock
+ OBJC_IVAR_$_VCMockIDSDatagramChannel._queueLock
+ OBJC_IVAR_$_VCSession._remoteParticipantsMapLock
+ _objc_getAssociatedObject
+ _objc_msgSend$activeInstanceCount
+ _objc_msgSend$canReuseTransportsForStreamConfigs:
+ _objc_msgSend$expectedTransportArrayCountForStreamConfigs:
+ _objc_msgSend$isMockingEnabled
+ _objc_msgSend$isMockingSessionActive
+ _objc_msgSend$isRemoteWatchRelayDeviceWithDeviceType:
+ _objc_msgSend$secondaryCameraRequestSizeForAspectRatio:
+ _objc_msgSend$setShouldCapBitrateForWatchRelay:
+ _objc_msgSend$shouldCapBitrateForWatchRelay
+ _objc_msgSend$transportArrayContainsRTXTransport
+ _objc_msgSend$transportStreamCountForStreamConfig:
+ _objc_msgSend$willCreateRTXTransportForStreamConfig:
+ _objc_setAssociatedObject
- -[VCAudioToolboxAudioComponentMock dealloc]
- -[VCCoreAudio_AudioUnitMock dealloc]
- GCC_except_table142
- GCC_except_table146
- GCC_except_table148
- GCC_except_table221
- GCC_except_table317
- GCC_except_table373
- GCC_except_table463
- ___30-[VCSession participantForID:]_block_invoke
- __audioComponentMockLock
- __audioUnitMockLock
- __weakAudioComponentMockInstance
- __weakAudioUnitMockInstance
- _objc_loadWeakRetained
CStrings:
+ " [%s] %s:%d %@(%p) Failed to allocate the active instances set"
+ " [%s] %s:%d %@(%p) Failed to init the instances lock"
+ " [%s] %s:%d %@(%p) [FTDC] No desired secondary capture formats: no video device format matches width=%d, height=%d, aspectRatio=%d among %lu multicam candidates of %lu total"
+ " [%s] %s:%d %@(%p) [FTDC] No exact %dx%d rear format (picker chose %dx%d); falling back to %dx%d"
+ " [%s] %s:%d Failed to allocate _enqueueLock"
+ " [%s] %s:%d Failed to allocate _queueLock"
+ " [%s] %s:%d Failed to allocate the active instances set"
+ " [%s] %s:%d Failed to init the instances lock"
+ " [%s] %s:%d [FTDC] No desired secondary capture formats: no video device format matches width=%d, height=%d, aspectRatio=%d among %lu multicam candidates of %lu total"
+ " [%s] %s:%d [FTDC] No exact %dx%d rear format (picker chose %dx%d); falling back to %dx%d"
+ " [%s] %s:%d beginSession: %lu audio unit mock instance(s) carried over from a previous session"
+ " [%s] %s:%d beginSession: %lu component mock instance(s) leaked from a previous session (never disposed)"
+ "-[VCAudioToolboxAudioComponentMock init]"
+ "-[VCCoreAudio_AudioUnitMock beginSession]"
+ "2260.11.1"
+ "VCVideoStream [%s] %s:%d %@(%p) Rebuilding transports for reconfigure. currentCount=%u expectedCount=%u localSSRCChanged=%d canReuse=%d"
+ "VCVideoStream [%s] %s:%d Rebuilding transports for reconfigure. currentCount=%u expectedCount=%u localSSRCChanged=%d canReuse=%d"
+ "dualCaptureRear1440x1080"
- " [%s] %s:%d %@(%p) no streams available"
- " [%s] %s:%d no streams available"
- "-[VCSessionUplinkVideoStreamController anchorStreamIDWithCappedVideoStreamIDs:]"
- "2260.9.1"
- "VCVideoStream [%s] %s:%d %@(%p) Reconfiguring VCVideoStream with a different number of transports."
- "VCVideoStream [%s] %s:%d Reconfiguring VCVideoStream with a different number of transports."
```
