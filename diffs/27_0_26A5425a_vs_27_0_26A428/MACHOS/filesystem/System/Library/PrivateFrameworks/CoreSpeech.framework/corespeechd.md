## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

 3600.70.47.0.0
-  __TEXT.__text: 0x17c338
+  __TEXT.__text: 0x178a4c
   __TEXT.__auth_stubs: 0x1400
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_stubs: 0x20a00
-  __TEXT.__objc_methlist: 0x1ae30
+  __TEXT.__objc_stubs: 0x20b20
+  __TEXT.__objc_methlist: 0x1afd0
   __TEXT.__const: 0x378
   __TEXT.__dlopen_cstrs: 0x126
-  __TEXT.__gcc_except_tab: 0x2cf0
-  __TEXT.__cstring: 0x2e09e
-  __TEXT.__objc_methname: 0x45105
-  __TEXT.__oslogstring: 0x26048
-  __TEXT.__objc_classname: 0x3729
-  __TEXT.__objc_methtype: 0x8ccc
-  __TEXT.__unwind_info: 0x5a08
-  __DATA_CONST.__const: 0x62f0
-  __DATA_CONST.__cfstring: 0x87c0
-  __DATA_CONST.__objc_classlist: 0x968
+  __TEXT.__gcc_except_tab: 0x2d38
+  __TEXT.__cstring: 0x2e324
+  __TEXT.__objc_methname: 0x4527a
+  __TEXT.__oslogstring: 0x263dd
+  __TEXT.__objc_classname: 0x37cb
+  __TEXT.__objc_methtype: 0x8d0f
+  __TEXT.__unwind_info: 0x7000
+  __DATA_CONST.__const: 0x6410
+  __DATA_CONST.__cfstring: 0x8800
+  __DATA_CONST.__objc_classlist: 0x988
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x590
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xc8
-  __DATA_CONST.__objc_superrefs: 0x7b0
+  __DATA_CONST.__objc_superrefs: 0x7d0
   __DATA_CONST.__objc_arraydata: 0x240
   __DATA_CONST.__objc_dictobj: 0x2a8
   __DATA_CONST.__objc_floatobj: 0x590

   __DATA_CONST.__objc_arrayobj: 0x150
   __DATA_CONST.__objc_doubleobj: 0x60
   __DATA_CONST.__auth_got: 0xa18
-  __DATA_CONST.__got: 0x1378
+  __DATA_CONST.__got: 0x1380
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x2a0d0
-  __DATA.__objc_selrefs: 0xc720
-  __DATA.__objc_ivar: 0x20e8
-  __DATA.__objc_data: 0x5e10
+  __DATA.__objc_const: 0x2a458
+  __DATA.__objc_selrefs: 0xc770
+  __DATA.__objc_ivar: 0x20f8
+  __DATA.__objc_data: 0x5f50
   __DATA.__lazy_load_got: 0x8
   __DATA.__data: 0x42c4
   __DATA.__bss: 0x628

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 10205
-  Symbols:   939
-  CStrings:  16456
+  Functions: 10252
+  Symbols:   940
+  CStrings:  16496
 
Symbols:
+ _NSProcessInfoPowerStateDidChangeNotification
CStrings:
+ "%s Disabling VoiceTrigger on AOP as since LowPowerMode is enabled"
+ "%s Disabling VoiceTrigger on AOP as since SleepMode is enabled"
+ "%s Disabling VoiceTrigger on AOP as the watch is off wrist"
+ "%s External phrase spotter running, ignore AOP trigger notification"
+ "%s ForceAPModeNonExclaveWatch=YES, forcing listening enabled (AP mode always on)"
+ "%s Phrase spotter is disabled, ignore Siri AP/AOP activation"
+ "%s RTS on watch cannot be turned on since there is another non eligible app recording and we are not in a connected or outgoing call"
+ "%s Received Hearst event %{public}ld"
+ "%s VoiceTrigger on watch cannot be turned on since HS is disabled"
+ "%s VoiceTrigger on watch cannot be turned on since system shell is not started"
+ "%s VoiceTrigger on watch cannot be turned on since there is another non eligible app recording and we are not in a connected or outgoing call"
+ "%s phraseSpotter bypassed, ignore AOP/AP trigger notification"
+ "-[CSAlwaysOnProcessorEnabledWatchExclave _addConditons]_block_invoke"
+ "-[CSRaiseToSpeakEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch CSAudioRouteChangeMonitor:didReceiveAudioRouteChangeEvent:]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch _addConditons]_block_invoke"
+ "-[CSVoiceTriggerActivationPolicyExclaveWatch _isExternalPhraseSpotterRunning:]"
+ "-[CSVoiceTriggerEnabledPolicyWatchExclave _addListeningEnabledConditions]_block_invoke"
+ "@\"<CSSleepModeMonitorProviding>\""
+ "@\"<CSWristStateMonitorProviding>\""
+ "CSAlwaysOnProcessorEnabledWatchExclave"
+ "CSRaiseToSpeakEnabledPolicyWatchExclave"
+ "CSVoiceTriggerActivationPolicyExclaveWatch"
+ "CSVoiceTriggerEnabledPolicyWatchExclave"
+ "T@\"<CSSleepModeMonitorProviding>\",&,N,V_sleepModeMonitor"
+ "T@\"<CSWristStateMonitorProviding>\",&,N,V_wristStateMonitor"
+ "_addConditons"
+ "_handlePowerStateChange:"
+ "_isExternalPhraseSpotterRunning:"
+ "_sleepModeMonitor"
+ "_subscribeToMonitors"
+ "_wristStateMonitor"
+ "com.apple.corespeech.CSAOPActivationEventHandlingPolicyWatch.queue"
+ "com.apple.corespeech.CSAlwaysOnProcessorEnabledExcalveWatch.queue"
+ "forceAPModeNonExclaveWatch"
+ "isLowPowerModeEnabled"
+ "setSleepModeMonitor:"
+ "setWristStateMonitor:"
+ "sleepModeMonitor"
+ "wristStateMonitor"
```
