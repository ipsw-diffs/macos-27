## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t6050.RELEASE.im4p/exclave_sharedcache`

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
-  __TEXT.__text: 0xdaa30c
+1777.60.18.0.1
+  __TEXT.__text: 0xdc5308
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa8c21
-  __TEXT.__const: 0x19e904
-  __TEXT.__swift5_typeref: 0x2ab2a
-  __TEXT.__swift5_reflstr: 0x3db38
-  __TEXT.__swift5_assocty: 0xec48
-  __TEXT.__swift5_fieldmd: 0x5dfe4
-  __TEXT.__constg_swiftt: 0x63ac4
-  __TEXT.__swift5_protos: 0x1244
-  __TEXT.__swift5_proto: 0x9d74
-  __TEXT.__swift5_types: 0x6054
+  __TEXT.__cstring: 0xa94d1
+  __TEXT.__const: 0x19ecb4
+  __TEXT.__swift5_typeref: 0x2ada2
+  __TEXT.__swift5_reflstr: 0x3df18
+  __TEXT.__swift5_assocty: 0xec60
+  __TEXT.__swift5_fieldmd: 0x5e274
+  __TEXT.__constg_swiftt: 0x63da4
+  __TEXT.__swift5_protos: 0x124c
+  __TEXT.__swift5_proto: 0x9d88
+  __TEXT.__swift5_types: 0x6078
   __TEXT.__swift5_types2: 0xc0
-  __TEXT.__swift5_builtin: 0x27d8
+  __TEXT.__swift5_builtin: 0x2814
   __TEXT.__swift5_capture: 0x35d0
   __TEXT.__objc_methtype: 0x2f6
   __TEXT.__swift5_mpenum: 0xeac
-  __TEXT.__swift_as_entry: 0x17ac
-  __TEXT.__swift_as_ret: 0x1ae0
-  __TEXT.__swift_as_cont: 0x3418
-  __TEXT.__oslogstring: 0x71f7
+  __TEXT.__swift_as_entry: 0x17c8
+  __TEXT.__swift_as_ret: 0x1b08
+  __TEXT.__swift_as_cont: 0x3478
+  __TEXT.__oslogstring: 0x71d7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x128
-  __TEXT.__eh_frame: 0x7a078
+  __TEXT.__eh_frame: 0x7a7f8
   __DATA.__TIGHTBEAM_VT: 0x1200
   __DATA.__TIGHTBEAM: 0x4a8
-  __DATA.__const: 0xe2a98
-  __DATA.__data: 0x50ab0
+  __DATA.__const: 0xe2dd0
+  __DATA.__data: 0x50e70
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1bee5
-  __DATA.__auth_ptr: 0x75c0
+  __DATA.__auth_ptr: 0x7620
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0x24be0
-  __DATA.__common: 0x2839
+  __DATA.__bss: 0x24bf0
+  __DATA.__common: 0x2859
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6910
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 48505
+  Functions: 48682
   Symbols:   1
-  CStrings:  15490
+  CStrings:  15533
 
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
+ "Tue Nov 10 01:32:31 PST 2026"
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
- "Thu Oct 29 00:33:21 PDT 2026"
- "[EIC] MMIO read: addr=%p value=0x%llx\n"
- "[EXDisplayPipeDriver] setSILHealth(region:status:healthValidForDuration:) not supported"
```
