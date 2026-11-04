## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Versions/A/Frameworks/SymptomEvaluator.framework/Versions/A/SymptomEvaluator`

```diff

-2394.40.17.0.0
-  __TEXT.__text: 0x1f263c
-  __TEXT.__objc_methlist: 0x12554
-  __TEXT.__cstring: 0x1ba6f
+2394.60.10.0.0
+  __TEXT.__text: 0x1f3990
+  __TEXT.__objc_methlist: 0x125dc
+  __TEXT.__cstring: 0x1baff
   __TEXT.__const: 0xf10
-  __TEXT.__oslogstring: 0x2ac75
-  __TEXT.__gcc_except_tab: 0x315c
+  __TEXT.__oslogstring: 0x2ad55
+  __TEXT.__gcc_except_tab: 0x31f8
   __TEXT.__dlopen_cstrs: 0x56
   __TEXT.__swift5_typeref: 0x38d
   __TEXT.__swift5_capture: 0x518

   __TEXT.__swift_as_entry: 0x4c
   __TEXT.__swift_as_ret: 0x68
   __TEXT.__swift_as_cont: 0x78
-  __TEXT.evaluator_cfg: 0x6649
-  __TEXT.__unwind_info: 0x6dd0
+  __TEXT.evaluator_cfg: 0x664b
+  __TEXT.__unwind_info: 0x6e48
   __TEXT.__eh_frame: 0x7d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2c88
+  __DATA_CONST.__const: 0x2ca8
   __DATA_CONST.__objc_classlist: 0x6e0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa090
+  __DATA_CONST.__objc_selrefs: 0xa0e0
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x480
   __DATA_CONST.__objc_arraydata: 0xc8
   __DATA_CONST.__got: 0xd30
-  __AUTH_CONST.__const: 0x54c0
-  __AUTH_CONST.__cfstring: 0x166e0
-  __AUTH_CONST.__objc_const: 0x2e218
-  __AUTH_CONST.__objc_intobj: 0x600
+  __AUTH_CONST.__const: 0x54f0
+  __AUTH_CONST.__cfstring: 0x16780
+  __AUTH_CONST.__objc_const: 0x2e248
+  __AUTH_CONST.__objc_intobj: 0x630
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__auth_got: 0x1420
   __AUTH.__objc_data: 0xbd8
   __AUTH.__data: 0xc8
-  __DATA.__objc_ivar: 0x1f40
-  __DATA.__data: 0x18a0
+  __DATA.__objc_ivar: 0x1f44
+  __DATA.__data: 0x18b0
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0xda8
+  __DATA.__bss: 0xdb8
   __DATA.__common: 0xa0
   __DATA_DIRTY.__objc_data: 0x3908
   __DATA_DIRTY.__data: 0x1b0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9503
-  Symbols:   18497
-  CStrings:  8482
+  Functions: 9532
+  Symbols:   18535
+  CStrings:  8494
 
Symbols:
+ +[NetworkAnalyticsEngine _armSustainedTimer:forValue:delaySecs:label:readUnderlying:setSustained:readSustained:]
+ +[NetworkAnalyticsEngine _clearSharedInstanceForTesting]
+ +[NetworkAnalyticsEngine _onDnsOutChangedTo:forRelay:]
+ +[NetworkAnalyticsEngine _onInternetDnsOutChangedTo:forRelay:]
+ +[NetworkAnalyticsEngine _sustainedDnsOutDelaySecsForTesting]
+ +[NetworkAnalyticsEngine _testDriveDnsOutForRelay:on:]
+ +[NetworkAnalyticsEngine _testDriveInternetDnsOutForRelay:on:]
+ +[NetworkAnalyticsEngine _testResetNetworkTunablesState]
+ +[NetworkAnalyticsEngine _testSetSustainedDnsOutDelaySecs:]
+ -[ConfigurationParams initWithUnderlyingDictionary:logHandle:]
+ -[NetworkAnalyticsEngine _configureNetworkParamsFromPrefs:]
+ -[NetworkAnalyticsEngine initTestInstanceWithQueue:]
+ -[NetworkStateRelay setSustainedInternetDnsOut:]
+ -[NetworkStateRelay sustainedInternetDnsOut]
+ GCC_except_table106
+ GCC_except_table110
+ GCC_except_table114
+ GCC_except_table138
+ GCC_except_table146
+ GCC_except_table162
+ GCC_except_table166
+ GCC_except_table171
+ GCC_except_table175
+ GCC_except_table182
+ GCC_except_table190
+ GCC_except_table193
+ GCC_except_table194
+ GCC_except_table198
+ GCC_except_table201
+ GCC_except_table202
+ GCC_except_table206
+ GCC_except_table209
+ GCC_except_table210
+ GCC_except_table214
+ GCC_except_table218
+ GCC_except_table222
+ GCC_except_table226
+ GCC_except_table230
+ GCC_except_table234
+ GCC_except_table238
+ GCC_except_table242
+ GCC_except_table246
+ GCC_except_table250
+ GCC_except_table254
+ GCC_except_table258
+ GCC_except_table262
+ GCC_except_table266
+ GCC_except_table274
+ GCC_except_table280
+ GCC_except_table281
+ GCC_except_table282
+ GCC_except_table294
+ GCC_except_table304
+ GCC_except_table305
+ GCC_except_table387
+ GCC_except_table391
+ GCC_except_table78
+ GCC_except_table90
+ _OBJC_IVAR_$_NetworkStateRelay._sustainedInternetDnsOut
+ ___112+[NetworkAnalyticsEngine _armSustainedTimer:forValue:delaySecs:label:readUnderlying:setSustained:readSustained:]_block_invoke
+ ___28-[NetworkStateRelay primary]_block_invoke
+ ___32-[NetworkStateRelay setPrimary:]_block_invoke
+ ___36-[NetworkStateRelay madePrimaryDate]_block_invoke
+ ___40-[NetworkStateRelay setMadePrimaryDate:]_block_invoke
+ ___44-[NetworkStateRelay sustainedInternetDnsOut]_block_invoke
+ ___48-[NetworkStateRelay setSustainedInternetDnsOut:]_block_invoke
+ ___54+[NetworkAnalyticsEngine _onDnsOutChangedTo:forRelay:]_block_invoke
+ ___62+[NetworkAnalyticsEngine _onInternetDnsOutChangedTo:forRelay:]_block_invoke
+ ___62+[NetworkAnalyticsEngine _onInternetDnsOutChangedTo:forRelay:]_block_invoke_2
+ ___62+[NetworkAnalyticsEngine _onInternetDnsOutChangedTo:forRelay:]_block_invoke_3
+ ___block_descriptor_72_e8_32bs40bs_e5_v8?0l
+ _kNetworkParamsName
+ _kNotificationBundleAdded
+ _kNotificationBundleIDAdded
+ _kSustainedDnsOutDelaySecs
+ _objc_msgSend$_configureNetworkParamsFromPrefs:
+ _objc_msgSend$initWithUnderlyingDictionary:logHandle:
+ _objc_msgSend$setSustainedDnsOut:
+ _objc_msgSend$setSustainedInternetDnsOut:
+ _objc_msgSend$sustainedDnsOut
+ _objc_msgSend$sustainedInternetDnsOut
+ _sustainedDnsOutDelaySecs
+ _sustainedDnsOutTimer
+ _sustainedInternetDnsOutTimer
- GCC_except_table104
- GCC_except_table108
- GCC_except_table116
- GCC_except_table120
- GCC_except_table124
- GCC_except_table128
- GCC_except_table132
- GCC_except_table136
- GCC_except_table144
- GCC_except_table148
- GCC_except_table156
- GCC_except_table159
- GCC_except_table160
- GCC_except_table168
- GCC_except_table172
- GCC_except_table176
- GCC_except_table181
- GCC_except_table184
- GCC_except_table188
- GCC_except_table189
- GCC_except_table192
- GCC_except_table196
- GCC_except_table204
- GCC_except_table208
- GCC_except_table212
- GCC_except_table216
- GCC_except_table220
- GCC_except_table224
- GCC_except_table228
- GCC_except_table232
- GCC_except_table236
- GCC_except_table240
- GCC_except_table243
- GCC_except_table244
- GCC_except_table248
- GCC_except_table252
- GCC_except_table256
- GCC_except_table260
- GCC_except_table271
- GCC_except_table272
- GCC_except_table273
- GCC_except_table284
- GCC_except_table296
- GCC_except_table351
- GCC_except_table355
- GCC_except_table92
CStrings:
+ "%s (active%s/primary%s/constrained%s/expensive%s/rssifull%s/rssithresh%s/txthresh%s/arp%s/dns%s/sust-dns%s/i-dns%s/sust-i-dns%s/i-stuck%s/rssiexempt:%d/rnfPoll:%d/rnfFrict%s/rnfDStall%s/rnfFback%s/apsd%s/1ppservconnfric%s/tcphints:%ld/lqm:%ld/assess:%ld/advisory:%d/pwrDL:%ld/pwrUL:%ld/ic:%ld%s/txRate:%.1f/rxRate:%.1f/wfrict:%lu/wfft%s/bbh:%d)"
+ "(active == NO) OR (primary == NO) OR ((sustainedDnsOut == NO) AND (tcpProgressHintsScore <= 10))"
+ "(active == YES) AND (primary == YES) AND ((sustainedDnsOut == YES) OR (tcpProgressHintsScore > 10))"
+ "(active == YES) AND (primary == YES) AND ((sustainedInternetDnsOut == YES) OR (tcpProgressHintsScore >= %lu))"
+ "2\x81\""
+ "BundleIDAdded"
+ "config %s restored to defaults, sustainedDnsOutDelaySecs: %.1f"
+ "config %s, sustainedDnsOutDelaySecs: %.1f"
+ "kNotificationBundleAdded"
+ "network_params"
+ "queue"
+ "relay %s: armed (%.1fs)"
+ "relay %s: cancelled (recovered before %.1fs)"
+ "relay %s: cleared"
+ "relay %s: fired (sustained for %.1fs)"
+ "sustainedDnsOutDelaySecs"
+ "sustainedInternetDnsOut"
- "%s (active%s/primary%s/constrained%s/expensive%s/rssifull%s/rssithresh%s/txthresh%s/arp%s/dns%s/sust-dns%s/i-dns%s/i-stuck%s/rssiexempt:%d/rnfPoll:%d/rnfFrict%s/rnfDStall%s/rnfFback%s/apsd%s/1ppservconnfric%s/tcphints:%ld/lqm:%ld/assess:%ld/advisory:%d/pwrDL:%ld/pwrUL:%ld/ic:%ld%s/txRate:%.1f/rxRate:%.1f/wfrict:%lu/wfft%s/bbh:%d)"
- "(active == NO) OR (primary == NO) OR ((dnsOut == NO) AND (tcpProgressHintsScore <= 10))"
- "(active == YES) AND (primary == YES) AND ((dnsOut == YES) OR (tcpProgressHintsScore > 10))"
- "(active == YES) AND (primary == YES) AND ((internetDnsOut == YES) OR (tcpProgressHintsScore >= %lu))"
- "2\x81!\xd1"
```
