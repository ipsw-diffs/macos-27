## wifip2pd

> `/usr/libexec/wifip2pd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__auth_got`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-890.1.0.0.0
-  __TEXT.__text: 0x5eb954
+890.5.0.0.0
+  __TEXT.__text: 0x5ef144
   __TEXT.__auth_stubs: 0x4f30
   __TEXT.__objc_stubs: 0x4800
   __TEXT.__objc_methlist: 0x1c34
-  __TEXT.__const: 0x40a40
+  __TEXT.__const: 0x40a10
   __TEXT.__cstring: 0xfb5a
-  __TEXT.__swift5_typeref: 0xd5f9
+  __TEXT.__swift5_typeref: 0xd5dd
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__oslogstring: 0x2390c
-  __TEXT.__constg_swiftt: 0x106b0
-  __TEXT.__swift5_fieldmd: 0x16bfc
+  __TEXT.__oslogstring: 0x23b8c
+  __TEXT.__constg_swiftt: 0x106d8
+  __TEXT.__swift5_fieldmd: 0x16c14
   __TEXT.__swift5_types: 0x130c
   __TEXT.__swift5_builtin: 0x175c
-  __TEXT.__swift5_reflstr: 0x14eb9
+  __TEXT.__swift5_reflstr: 0x14f19
   __TEXT.__swift5_assocty: 0x2d78
   __TEXT.__swift5_proto: 0x3094
   __TEXT.__objc_methtype: 0x2367
   __TEXT.__swift5_protos: 0x108
-  __TEXT.__swift5_capture: 0x848c
-  __TEXT.__objc_methname: 0xa5a5
+  __TEXT.__swift5_capture: 0x85a4
+  __TEXT.__objc_methname: 0xa5c5
   __TEXT.__objc_classname: 0x11f7
   __TEXT.__swift5_mpenum: 0x1b8
   __TEXT.__swift_as_entry: 0x24c
   __TEXT.__swift_as_ret: 0x1a0
   __TEXT.__swift_as_cont: 0x67c
-  __TEXT.__unwind_info: 0x14bf8
-  __TEXT.__eh_frame: 0x1f154
-  __DATA_CONST.__const: 0x3aa68
+  __TEXT.__unwind_info: 0x14c40
+  __TEXT.__eh_frame: 0x1f184
+  __DATA_CONST.__const: 0x3ace8
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x208
   __DATA_CONST.__objc_protolist: 0x2f0

   __DATA_CONST.__objc_protorefs: 0x178
   __DATA_CONST.__auth_got: 0x27a0
   __DATA_CONST.__got: 0x1078
-  __DATA_CONST.__auth_ptr: 0x7a20
-  __DATA.__objc_const: 0xb128
+  __DATA_CONST.__auth_ptr: 0x7a18
+  __DATA.__objc_const: 0xb168
   __DATA.__objc_selrefs: 0x1700
   __DATA.__objc_data: 0x1a70
-  __DATA.__data: 0x155d0
+  __DATA.__data: 0x15628
   __DATA.__bss: 0x5e4d0
-  __DATA.__common: 0xbd0
+  __DATA.__common: 0xbe0
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 25302
+  Functions: 25349
   Symbols:   2277
-  CStrings:  5626
+  CStrings:  5635
 
CStrings:
+ "#### Not Terminating datapath %hhu with %s. Referenced by other endpoint."
+ "#### Terminating datapath session %hhu with %s for Responder"
+ "%@: [BLOOM FILTER] FW Config: %s (WatchdogReset)"
+ "%s Terminated. It released its count when the pairing session for: %s was replaced"
+ "%s Terminated. It uses no pairing keys, so leaving the pairing session for: %s"
+ "%s is stopping. Pairing session for: %s is still held by another datapath"
+ "%s was set up with the replaced pairing session for: %s. Terminating it"
+ "5847298215aa4c496349d419114565ede536b076e8e34688ef2504fdaf52519b"
+ "9105287f0003abe9b7d3272855d4b43cf4b3f61d59126dcf009b20dc0b8e53f5"
+ "Cannot create new datapath for %@ to %s[%hhu] because connection mode is %s but no DCEA"
+ "Failed to clear the peer presence table after interface re-creation because %@"
+ "Retaining pairing session to: %s, UsageCount: %ld"
+ "WiFiP2P-890.5 Nov 10 2026 02:11:40"
+ "hasPairingSession"
+ "releasedPairingSession"
+ "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"33edcace6e42e7bf0a6fd73d3b209a2b496f98b5e1f3ecc1f96a079dbedd1583\": {\n      \"WiFiAwareServices\": {\n        \"2c785e3dee84cac7486b77412356f77571ccf334864b4992c417254a1ab29944\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"a8cd6b783fd23557b60fe766b6a8ad15098bb98713e57b8168e1edb069f8ad07\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e78efbf254ee0c26b695cc2c7bb531dca3c8b86b9b669df2ca0f05bcd0019c82\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"886162ceaf3ffb2aeb21878649c8ad6976506f8da0852521f72796c2a29ff083\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"fb596edf042d7ded66d1d83a28d6f4dd3021336de2670d9211fe805c469fb61f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"a916d4a926cb860bf4dc7147cee2779b0901db26a2be56eae994f37135c8594b\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"f5a0259fae4d0916e2f195129a6bbf4946a4892f047d87b55b062e672bad9c1e\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"6238544d0a4be0074335b953f3b3d5e3c418e54ddb8ba444ded7f6db1e597747\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"9b689859e0712e72565c533dbf99e41bef513499d482683eea5418fd6faab66e\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"09835287ab4a0f9b229a7c5ccc0d02b6a33823309750ea2188e3236993d235ed\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"c63d9cd0eae133f02d92a5d981fba74e74ed058de8cb4f92062e577c1ce26bde\": {\n      \"WiFiAwareServices\": {\n        \"8db85fc009a971ad299be822b388fc3773421b941c2f4a97b350ba358562bb11\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"07e72018e8147a4dd82a8b5b6c936fca05a34a6add805f3da8143c7a89841c5a\": {\n      \"WiFiAwareServices\": {\n        \"183e78bcee1a86c6e5b70840285317815204a34c508ac41760c3bf9780b7010a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"fa0cc9e4da64c9c764a24d93b20cbec3dadbe187b88ce9904b30311a81378f18\": {\n      \"WiFiAwareServices\": {\n        \"686a47790c2eaccfb020862b23f33d54d166dc31c2c4e9aa93f252522e8eaa76\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"5095a77b7edf534f9bf65389fe984ff76672425785f4a1250fa6c714a70561d8\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"c68588635ff839ed273178024ff9556ded919a17dc157c3b575a8a0cfe77fc0d\": {\n      \"WiFiAwareServices\": {\n        \"8db85fc009a971ad299be822b388fc3773421b941c2f4a97b350ba358562bb11\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"adf4329264c0a5404f8eff0c7a7bdaedb94f859e5edf599346874d2127f4478e\": {\n      \"WiFiAwareServices\": {\n        \"183e78bcee1a86c6e5b70840285317815204a34c508ac41760c3bf9780b7010a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
+ "{\n  \"c281f50e31f64afb3d059bc41a209eddf46153634ed44242cf76189a7da52875\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"546f1618aaac85710cfe0b8bda6c703194125a3436d262f1f1a1ac4a62924728\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"0ba069d287264992c53363abb93847b511d47240582da1d5474f327e8200d9a0\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"8a5facd7fb20422102ade60be6c72497338b14b690b385308261f72b086ae1e4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"05c9b2e6ed59b8f06a21c0cba0bc94a9042a03947faf00e6d7cf1e5e6cd92e30\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Timeout\": 120,\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"bdc065138de99c418b0a7bb030addb625174d89bd5cb2e62660cd37c63ff2709\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"150fd0a734a9192d08ab559af5b5707e85d770dda287a249ca427183856ef447\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"ac593b852d1fe13bb8c5182c7a7a155676ee04061a4fac2cf36902c080ef4e66\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"805c287e6b9470e1143d14f312fd612c20fca1a219f1a4b09b1f9f1308d8903d\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"Timeout\": 120\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"9f6e03746168a17a3ce8805bc545c26b52b7032ad3bf70d2e3e7ee9d99517e34\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"15dac950112b2ca98f28f2d2389de3a87696c55cc283f7766d8e6e897a18ae6d\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"4cc1dde21a0c38ca9dd728b26c559c02ddc8210ebe002437c309034cfe77bab1\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"2005e83bb2216ca80980532f4a68a0036ec43946d4cdebe4b15d900019c224fc\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
- "#### Not Terminating datapath %hhu. Referenced by other endpoint."
- "#### Terminating datapath session %hhu for Responder"
- "8e36d7ead8e67df7975423873012f4f88a1049396f5794ed88eb2454b44b713a"
- "WiFiP2P-890.1 Oct 29 2026 01:10:57"
- "c9ced9aa2adcb2592ed8475e4a8cab9490817cb3e6ee43c68694d27df7bcd786"
- "datapathType"
- "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"f09659885985096fa028a731901f9adb5f6a90d1044fdca7ff83c9edccfd3921\": {\n      \"WiFiAwareServices\": {\n        \"5a2c89b277c89fe2ce144e7fca5d36816862e5e5e28d3cad6e6a13b4bbdd6227\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"f86e971e96df17a43fa0504d93500d7d77b6fa650f8169494ed49468c8873bba\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"f5bdd329580646deb6370e017e1df3aab3a351a2dd3bce3dd81b2e6903b33b2b\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"72def5a4a4736a4a3a399b66999b90966cf8906a988da64877ea0b113e14fc48\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"23842ed98278c90d6ae281aab3e66b2d4ea3964394e15a9611fff80cc809e574\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"138e376824315344a28d62cffbfcb55f2555200af6a9743ae7fdf4de37a0b530\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"a02228095f8e90f11942ff3f8b8a6b828c3978171c58353cccf61c0934c12613\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"b57b46342e82c7cb59b6e3f4dbf25ad89a76d418486b72dea3c2137f9dc68dc4\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"3b424bb48a7672392eac4375061a0ec3d2617195116f4fe5bd0d4cf8585d85f2\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"94025f4a60a900cdd3861bad30de9e20adaca73bc355ad2dd93c946f94996315\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"2aec150f9fae49c886b12dd1512ff80939dfd27c29fdc84c8c147d173ae4505b\": {\n      \"WiFiAwareServices\": {\n        \"aee78977a845edc7319d463adc481dc9875d02447159273123dabb2040f64f44\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"cedab3b73f475aeb2554c6e49de8419cfbaf11e069e620439d21b48bf8599a6b\": {\n      \"WiFiAwareServices\": {\n        \"42272f25510fa40a7060699e0c8c3da205d4882b835074b5be67321049b0ed81\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"c5881602b0ef8b02862a2d0ac6b7cc5296eaf78a036f10696fb4e2b42c31bb55\": {\n      \"WiFiAwareServices\": {\n        \"a7728e075f874dbd36599f5094da775101941a8b0c2e1f07cf9477137ed2e0ef\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"d16e965a17a950dbb09d0c2fec0080e90269f15d44b12831421f3bc8c30b72c2\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"935e0e58f199d0eb67276578f173f4a19a3deea5f5bbe1d11e90349a3b004724\": {\n      \"WiFiAwareServices\": {\n        \"aee78977a845edc7319d463adc481dc9875d02447159273123dabb2040f64f44\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"27d49143049923a512885cf11875b7fdb97e58dc64b9a8b7a7fb793849fb5590\": {\n      \"WiFiAwareServices\": {\n        \"42272f25510fa40a7060699e0c8c3da205d4882b835074b5be67321049b0ed81\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
- "{\n  \"aaabee233f2a6d972d989ff260193bb190a11242410e7e82beb1f4eedd01adc3\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"f0ec9a30f69e66434556b4bf8af37072a8effbc14064c177a26a9fac4c6d6960\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"ceae227db95eadc547cbd17b3003c94e569e006acc967633d467eec4a10e1f40\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"831329f4c66e345c03377983859e20468ec98462b5ff473a35f0b192e49b7c96\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"2f8273c49651bcb2264fdeaed3529081c818c366bcac45cfc8efe3d5b67f9682\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Timeout\": 120,\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"8ad9a3057e725fb206c1a2f7dbcc2fa9d3a587c6d02bb94edc98b319c0b94d64\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"9b60cfd1cc48e8cee3409bdd12e2f21df7368f7c7828ba9a30a569e4c546a809\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"8c422c5ef776dafffda9f3fc29deee1961bdb75908ea7d55be8a8e42e78ca602\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"7b65a1aac19571f3444a4208b79ecfb1bbf71a9146159cca712b3c9ee4e0408d\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"Timeout\": 120\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"e7741fbc5cafb0068e6a04e420ef0bf7bfa920152931f7f7385174508b12bbe4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"7f5455b28ad6a734aefaf5673cb06c77c76116a77597e3d0d9ac2259164de7b9\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"58c077106c289858d48691190ac879bf2ba56840198fb2cba6bbbb3f22a3bd2b\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"77058283fd27b6c8ced1d15a298ca981d85f175124141e45a716cd155760646c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
```
