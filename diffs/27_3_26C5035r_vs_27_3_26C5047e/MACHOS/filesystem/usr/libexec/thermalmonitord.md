## thermalmonitord

> `/usr/libexec/thermalmonitord`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2087.60.5.0.0
-  __TEXT.__text: 0x10fa0
-  __TEXT.__auth_stubs: 0xc70
-  __TEXT.__objc_stubs: 0x1c20
-  __TEXT.__objc_methlist: 0xe74
+2087.60.6.0.0
+  __TEXT.__text: 0x1159c
+  __TEXT.__auth_stubs: 0xcd0
+  __TEXT.__objc_stubs: 0x1c80
+  __TEXT.__objc_methlist: 0xea4
   __TEXT.__const: 0x17e
   __TEXT.__gcc_except_tab: 0x50
-  __TEXT.__objc_methname: 0x2b3a
-  __TEXT.__cstring: 0x52f5
+  __TEXT.__objc_methname: 0x2bdb
+  __TEXT.__cstring: 0x558e
   __TEXT.__objc_classname: 0x1a0
-  __TEXT.__objc_methtype: 0xf62
+  __TEXT.__objc_methtype: 0xf9b
   __TEXT.__oslogstring: 0x6f
-  __TEXT.__unwind_info: 0x558
+  __TEXT.__unwind_info: 0x578
   __DATA_CONST.__const: 0x8d8
-  __DATA_CONST.__cfstring: 0x5600
+  __DATA_CONST.__cfstring: 0x5780
   __DATA_CONST.__objc_classlist: 0x90
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_dictobj: 0x2c718
   __DATA_CONST.__objc_arrayobj: 0x31f8
   __DATA_CONST.__objc_doubleobj: 0xa2a0
-  __DATA_CONST.__auth_got: 0x648
+  __DATA_CONST.__auth_got: 0x678
   __DATA_CONST.__got: 0x130
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x2890
-  __DATA.__objc_selrefs: 0x920
-  __DATA.__objc_ivar: 0x354
+  __DATA.__objc_const: 0x2910
+  __DATA.__objc_selrefs: 0x938
+  __DATA.__objc_ivar: 0x364
   __DATA.__objc_data: 0x5a0
   __DATA.__data: 0x84
-  __DATA.__bss: 0x1c0
+  __DATA.__bss: 0x1b8
   __DATA.__common: 0x939
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 376
-  Symbols:   245
-  CStrings:  1412
+  Functions: 382
+  Symbols:   251
+  CStrings:  1436
 
Symbols:
+ _CFDataGetBytes
+ _IOIteratorNext
+ _IOObjectRetain
+ _IORegistryEntryGetName
+ _IORegistryEntryGetParentEntry
+ _IOServiceGetMatchingServices
CStrings:
+ "%@: dieCount*loopCount %u exceeds the %d-bit TDDB cluster mask capacity"
+ "B36@0:8^{__CFData=}16^{__CFString=}24I32"
+ "Failed to find %s service for die %u in the registry"
+ "Failed to find %s service(s) in the registry"
+ "Failed to read valid die/loop count for PMP index %u (die %u loop %u)"
+ "I20@0:8I16"
+ "IOService"
+ "LTS invariant: PMP for die %u does not expose key %@ (die-namespace mismatch)"
+ "LTS invariant: PMP instance %u per-die loop-count %u != %u"
+ "LTS invariant: multi-PMP instance %u reports die-count %u (expected 1)"
+ "LTS: duplicate PMP index %d, ignoring"
+ "LTS: failed to find %s service(s) in the registry"
+ "LTS: no usable ApplePMPv2 instances found"
+ "LTS: skipping ApplePMPv2 with unusable pmpN index %d"
+ "LTS: unexpected type/size for PMP property"
+ "Unexpected aggregated die count %u (max %d)"
+ "[2I]"
+ "^{__CFData=}32@0:8^{__CFString=}16B24I28"
+ "^{__CFString=}20@0:8I16"
+ "_pmpKeyNamespaceVerified"
+ "_pmpServiceCount"
+ "_pmpServices"
+ "_pmpServicesScouted"
+ "copyKeyFromPMP:is_64:forDie:"
+ "copyPmpDieProbeKeyForDie:"
+ "dieCount:%u loopCount:%u pmpServices:%u"
+ "ensurePmpServices"
+ "lts-ctrl-%u-0-cores"
+ "lts-ctrl-%u-0-is-inuse"
+ "sendDataToPMP:forKey:forDie:"
+ "serviceForDie:"
+ "v20@0:8I16"
+ "verifyPmpKeyNamespace:"
- "B32@0:8^{__CFData=}16^{__CFString=}24"
- "Failed to find %s service in the registry"
- "Failed to read die count for registry\n"
- "Failed to read loop count for registry\n"
- "^{__CFData=}28@0:8^{__CFString=}16B24"
- "copyKeyFromPMP:is_64:"
- "dieCount:%u loopCount:%u"
- "getPMPSvc"
- "sendDataToPMP:forKey:"
```
