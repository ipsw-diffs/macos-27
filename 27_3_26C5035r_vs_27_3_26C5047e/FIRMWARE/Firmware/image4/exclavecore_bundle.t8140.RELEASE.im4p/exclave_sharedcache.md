## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__shared_cache`

```diff

-1777.60.14.0.1
-  __TEXT.__text: 0xdc0f5c
+1777.60.18.0.1
+  __TEXT.__text: 0xddbf08
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa7ec1
-  __TEXT.__const: 0x1d1934
-  __TEXT.__swift5_typeref: 0x2aad6
-  __TEXT.__swift5_reflstr: 0x45398
-  __TEXT.__swift5_assocty: 0xe848
-  __TEXT.__swift5_fieldmd: 0x6ed2c
-  __TEXT.__constg_swiftt: 0x663a0
-  __TEXT.__swift5_protos: 0x11bc
-  __TEXT.__swift5_proto: 0xa71c
-  __TEXT.__swift5_types: 0x6894
+  __TEXT.__cstring: 0xa8771
+  __TEXT.__const: 0x1d1cd4
+  __TEXT.__swift5_typeref: 0x2ad4e
+  __TEXT.__swift5_reflstr: 0x45778
+  __TEXT.__swift5_assocty: 0xe860
+  __TEXT.__swift5_fieldmd: 0x6efbc
+  __TEXT.__constg_swiftt: 0x66680
+  __TEXT.__swift5_protos: 0x11c4
+  __TEXT.__swift5_proto: 0xa730
+  __TEXT.__swift5_types: 0x68b8
   __TEXT.__swift5_types2: 0xbc
-  __TEXT.__swift5_builtin: 0x27b0
+  __TEXT.__swift5_builtin: 0x27ec
   __TEXT.__swift5_capture: 0x36b0
   __TEXT.__objc_methtype: 0x2f6
   __TEXT.__swift5_mpenum: 0xe54
-  __TEXT.__swift_as_entry: 0x1744
-  __TEXT.__swift_as_ret: 0x1ab4
-  __TEXT.__swift_as_cont: 0x3388
-  __TEXT.__oslogstring: 0x70e7
+  __TEXT.__swift_as_entry: 0x1760
+  __TEXT.__swift_as_ret: 0x1adc
+  __TEXT.__swift_as_cont: 0x33e8
+  __TEXT.__oslogstring: 0x70c7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x148
-  __TEXT.__eh_frame: 0x7844c
+  __TEXT.__eh_frame: 0x78bc4
   __DATA.__TIGHTBEAM_VT: 0x1080
   __DATA.__TIGHTBEAM: 0x448
-  __DATA.__const: 0x11e820
-  __DATA.__data: 0x51b88
+  __DATA.__const: 0x11eb58
+  __DATA.__data: 0x51f48
   __DATA.__mod_init_func: 0x48
   __DATA.__ENDPOINTS: 0x1bee5
-  __DATA.__auth_ptr: 0x63b0
+  __DATA.__auth_ptr: 0x6410
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0x248b0
-  __DATA.__common: 0x3d59
+  __DATA.__bss: 0x248c0
+  __DATA.__common: 0x3d79
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6910
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 50241
+  Functions: 50418
   Symbols:   1
-  CStrings:  15457
+  CStrings:  15500
 
CStrings:
+ " has a session hint transition in flight -- leaving for later"
+ " ignored: perf control upcalls not wired"
+ " minModeledLatencyUs "
+ " no sample from this sensor, still within first integration period, skipping..."
+ "); kext has no handler, disabling perf control upcalls"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Tue Nov 10 00:53:24 PST 2026; root:AppleImage4_exclavecore-374~20317/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.205"
+ "BUG IN XNU: concurrent calls to LogServer.getLogs()"
+ "BUG IN XNU: concurrent calls to RedactedLogServer.getLogs()"
+ "Build Date: Mon Nov  9 23:00:53 PST 2026"
+ "Builtin.FixedArray of %zd elements with stride %zu is too large to be representable\n"
+ "Cached procedure refused: shutdown in progress"
+ "Error getting voice trigger event: "
+ "ExclaveIndicatorControllerComponent/ExclavesPlatform.swift"
+ "ExclaveOS Image4 Framework Version 7.0.0: Tue Nov 10 00:53:24 PST 2026; root:AppleImage4_exclavecore-374~20317/ExclaveImage4/RELEASE_ARM64E"
+ "ExclaveSISP-6.203"
+ "Failed to read GLTB"
+ "MNISTDynamicPower"
+ "Model load refused: shutdown in progress"
+ "OSLogServerComponent/RedactedLogServer.swift"
+ "Perf control policy 0x"
+ "Perf control policy: report "
+ "Request refused: shutdown in progress"
+ "SILManager: enabled region with no indicator resolved"
+ "Shutdown reset: accepting new work again"
+ "Siri activated mic: microphone allowed for longer than "
+ "Siri activated mic: no voice trigger service, microphone not allowed"
+ "Siri activated mic: recent voice trigger event detected"
+ "SiriActivatedMic = "
+ "Tried to build a Builtin.FixedArray without metadata for the element type"
+ "Tue Nov 10 01:32:55 PST 2026"
+ "[B] Start Siri dark wake policy"
+ "[B] Stop Siri dark wake policy"
+ "[ERROR] %s: %s: No valid procedure variant info for procId %llu (single and bonded both absent)\n"
+ "[EXDisplayPipeDriver] setSILHealth(region:indicator:status:healthValidForDuration:) not supported"
+ "[StrictMode] .rampUp -> .steady"
+ "[StrictMode] Can't use pre-wake MIB. Reporting failure."
+ "[StrictMode] Disabling (enabledTs="
+ "[StrictMode] Enabling (ts="
+ "[StrictMode] Healthy. Disabling. MIB="
+ "_decNumAllocated()"
+ "failed to shrink max mapped to minimum = "
+ "getProcedureLatencyStats"
+ "octopus_siri_activated_mic"
+ "policy-siri-activated-mic"
+ "reset max mapped to minimum = "
+ "sessionHint Start: releasing the re-registration EC assertion failed: "
+ "sessionHint: refused, shutdown in progress"
+ "startShutdown: shutdown downcall completed"
+ "type bound to a value generic parameter"
+ "type where a Builtin.FixedArray count is required"
+ "unresolved Builtin.FixedArray element type"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Thu Oct 29 00:01:52 PDT 2026; root:AppleImage4_exclavecore-374~20051/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.203.1"
- "Build Date: Wed Oct 28 21:52:48 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Thu Oct 29 00:01:52 PDT 2026; root:AppleImage4_exclavecore-374~20051/ExclaveImage4/RELEASE_ARM64E"
- "ExclaveSISP-6.201"
- "MMIO read: addr=%p value=0x%llx"
- "Thu Oct 29 00:33:51 PDT 2026"
- "[EIC] MMIO read: addr=%p value=0x%llx\n"
- "[EXDisplayPipeDriver] setSILHealth(region:status:healthValidForDuration:) not supported"
```
