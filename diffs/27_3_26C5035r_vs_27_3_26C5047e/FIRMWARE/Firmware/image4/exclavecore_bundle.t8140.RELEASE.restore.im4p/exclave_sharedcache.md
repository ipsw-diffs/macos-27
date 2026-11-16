## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
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
-  __TEXT.__text: 0x5dde84
+1777.60.18.0.1
+  __TEXT.__text: 0x5e3bf8
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x50141
-  __TEXT.__const: 0x121564
-  __TEXT.__swift5_typeref: 0x13356
-  __TEXT.__swift5_reflstr: 0x124a8
-  __TEXT.__swift5_assocty: 0x7c20
-  __TEXT.__swift5_fieldmd: 0x1b428
-  __TEXT.__constg_swiftt: 0x26480
-  __TEXT.__swift5_protos: 0x8c0
-  __TEXT.__swift5_proto: 0x3b40
-  __TEXT.__swift5_types: 0x22b8
-  __TEXT.__swift5_types2: 0x64
-  __TEXT.__swift5_builtin: 0x1590
+  __TEXT.__cstring: 0x506e1
+  __TEXT.__const: 0x121c14
+  __TEXT.__swift5_typeref: 0x1354c
+  __TEXT.__swift5_reflstr: 0x125f8
+  __TEXT.__swift5_assocty: 0x7fb0
+  __TEXT.__swift5_fieldmd: 0x1b68c
+  __TEXT.__constg_swiftt: 0x267e8
+  __TEXT.__swift5_protos: 0x8c8
+  __TEXT.__swift5_proto: 0x3c10
+  __TEXT.__swift5_types: 0x22e8
+  __TEXT.__swift5_types2: 0x78
+  __TEXT.__swift5_builtin: 0x15f4
   __TEXT.__swift5_capture: 0xfec
   __TEXT.__objc_methtype: 0x111
   __TEXT.__swift5_mpenum: 0x3b8
   __TEXT.__swift_as_entry: 0x9bc
   __TEXT.__swift_as_ret: 0xb34
   __TEXT.__swift_as_cont: 0x1234
-  __TEXT.__oslogstring: 0xf0
+  __TEXT.__oslogstring: 0xd0
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xb0
-  __TEXT.__eh_frame: 0x33c14
+  __TEXT.__eh_frame: 0x33e54
   __DATA.__TIGHTBEAM_VT: 0x720
   __DATA.__TIGHTBEAM: 0x1d8
-  __DATA.__const: 0x3c1d0
-  __DATA.__data: 0x16e48
+  __DATA.__const: 0x3c958
+  __DATA.__data: 0x16f90
   __DATA.__mod_init_func: 0x40
   __DATA.__ENDPOINTS: 0x1aa59
-  __DATA.__auth_ptr: 0x2090
+  __DATA.__auth_ptr: 0x2150
   __DATA.__DEVICETREE: 0x18
   __DATA.__shared_cache: 0x380
   __DATA.__MMIOREGS: 0x795

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xe580
-  __DATA.__common: 0x6aa
+  __DATA.__bss: 0xe590
+  __DATA.__common: 0x6ca
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6910
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 22721
+  Functions: 22805
   Symbols:   1
-  CStrings:  7299
+  CStrings:  7328
 
CStrings:
+ " no sample from this sensor, still within first integration period, skipping..."
+ "AtomicLoadOrdering("
+ "AtomicStoreOrdering("
+ "AtomicUpdateOrdering("
+ "BUG IN XNU: concurrent calls to LogServer.getLogs()"
+ "BUG IN XNU: concurrent calls to RedactedLogServer.getLogs()"
+ "Builtin.FixedArray of %zd elements with stride %zu is too large to be representable\n"
+ "Error getting voice trigger event: "
+ "ExclaveIndicatorControllerComponent/ExclavesPlatform.swift"
+ "Failed to read GLTB"
+ "OSLogServerComponent/RedactedLogServer.swift"
+ "Siri activated mic: microphone allowed for longer than "
+ "Siri activated mic: no voice trigger service, microphone not allowed"
+ "Siri activated mic: recent voice trigger event detected"
+ "SiriActivatedMic = "
+ "Tried to build a Builtin.FixedArray without metadata for the element type"
+ "WordPair(first: "
+ "[B] Start Siri dark wake policy"
+ "[B] Stop Siri dark wake policy"
+ "[StrictMode] .rampUp -> .steady"
+ "[StrictMode] Can't use pre-wake MIB. Reporting failure."
+ "[StrictMode] Disabling (enabledTs="
+ "[StrictMode] Enabling (ts="
+ "[StrictMode] Healthy. Disabling. MIB="
+ "acquiringAndReleasing"
+ "octopus_siri_activated_mic"
+ "policy-siri-activated-mic"
+ "sequentiallyConsistent"
+ "type bound to a value generic parameter"
+ "type where a Builtin.FixedArray count is required"
+ "unresolved Builtin.FixedArray element type"
- "MMIO read: addr=%p value=0x%llx"
- "[EIC] MMIO read: addr=%p value=0x%llx\n"
```
