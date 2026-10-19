## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 3111.40.45.0.0
-  __TEXT.__text: 0x106894
+  __TEXT.__text: 0x106c6c
   __TEXT.__auth_stubs: 0x3000
   __TEXT.__objc_stubs: 0xf00
   __TEXT.__objc_methlist: 0x2a4
   __TEXT.__const: 0x15dc
   __TEXT.__cstring: 0x18b17
   __TEXT.__gcc_except_tab: 0x3fc
-  __TEXT.__oslogstring: 0x2001b
+  __TEXT.__oslogstring: 0x200d8
   __TEXT.__objc_classname: 0x5fe
   __TEXT.__objc_methname: 0xe47
   __TEXT.__objc_methtype: 0x4ea
-  __TEXT.__unwind_info: 0x1d20
+  __TEXT.__unwind_info: 0x1d28
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x62d0
   __DATA_CONST.__cfstring: 0x1260

   - /usr/lib/libnetworkextension.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 1804
-  Symbols:   3854
-  CStrings:  4576
+  Functions: 1806
+  Symbols:   3856
+  CStrings:  4578
 
Symbols:
+ GCC_except_table1154
+ GCC_except_table1233
+ GCC_except_table1242
+ GCC_except_table1370
+ GCC_except_table1766
+ GCC_except_table502
+ _CacheRecordDecrementIneligibleForRecycling
+ _CacheRecordIncrementIneligibleForRecycling
- GCC_except_table1152
- GCC_except_table1231
- GCC_except_table1240
- GCC_except_table1368
- GCC_except_table1764
- GCC_except_table500
CStrings:
+ "ineligibleForRecycling overflow - %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
+ "ineligibleForRecycling underflow - %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
```
