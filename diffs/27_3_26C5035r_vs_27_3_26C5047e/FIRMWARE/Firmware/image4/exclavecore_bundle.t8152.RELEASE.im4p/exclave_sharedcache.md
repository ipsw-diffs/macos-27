## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8152.RELEASE.im4p/exclave_sharedcache`

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
-  __TEXT.__text: 0xdb5144
+1777.60.18.0.1
+  __TEXT.__text: 0xdd0044
   __TEXT.__lcxx_override: 0xd0
-  __TEXT.__cstring: 0xa9fe1
-  __TEXT.__const: 0x1a44e4
-  __TEXT.__swift5_typeref: 0x2b316
-  __TEXT.__swift5_reflstr: 0x40108
-  __TEXT.__swift5_assocty: 0xefa0
-  __TEXT.__swift5_fieldmd: 0x61588
-  __TEXT.__constg_swiftt: 0x6503c
-  __TEXT.__swift5_protos: 0x1288
-  __TEXT.__swift5_proto: 0xa034
-  __TEXT.__swift5_types: 0x6268
+  __TEXT.__cstring: 0xaa891
+  __TEXT.__const: 0x1a4884
+  __TEXT.__swift5_typeref: 0x2b59e
+  __TEXT.__swift5_reflstr: 0x404e8
+  __TEXT.__swift5_assocty: 0xefb8
+  __TEXT.__swift5_fieldmd: 0x61818
+  __TEXT.__constg_swiftt: 0x6531c
+  __TEXT.__swift5_protos: 0x1290
+  __TEXT.__swift5_proto: 0xa048
+  __TEXT.__swift5_types: 0x628c
   __TEXT.__swift5_types2: 0xc4
-  __TEXT.__swift5_builtin: 0x27ec
+  __TEXT.__swift5_builtin: 0x2828
   __TEXT.__swift5_capture: 0x3690
   __TEXT.__objc_methtype: 0x2f6
   __TEXT.__swift5_mpenum: 0xefc
-  __TEXT.__swift_as_entry: 0x17b0
-  __TEXT.__swift_as_ret: 0x1ae4
-  __TEXT.__swift_as_cont: 0x3424
-  __TEXT.__oslogstring: 0x71f7
+  __TEXT.__swift_as_entry: 0x17cc
+  __TEXT.__swift_as_ret: 0x1b0c
+  __TEXT.__swift_as_cont: 0x3484
+  __TEXT.__oslogstring: 0x71d7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x130
-  __TEXT.__eh_frame: 0x7a808
+  __TEXT.__eh_frame: 0x7af90
   __DATA.__TIGHTBEAM_VT: 0x1200
   __DATA.__TIGHTBEAM: 0x4b0
-  __DATA.__const: 0xeded8
-  __DATA.__data: 0x51528
+  __DATA.__const: 0xee210
+  __DATA.__data: 0x518e8
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1bee5
-  __DATA.__auth_ptr: 0x64a8
+  __DATA.__auth_ptr: 0x6508
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0x24fc0
-  __DATA.__common: 0x26d1
+  __DATA.__bss: 0x24fd0
+  __DATA.__common: 0x26f1
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6910
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 1363
+  Functions: 1362
   Symbols:   1
-  CStrings:  15618
+  CStrings:  15661
 
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
+ "Tue Nov 10 01:32:52 PST 2026"
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
- "Thu Oct 29 00:33:49 PDT 2026"
- "[EIC] MMIO read: addr=%p value=0x%llx\n"
- "[EXDisplayPipeDriver] setSILHealth(region:status:healthValidForDuration:) not supported"
```
