## tcpdump

> `/usr/sbin/tcpdump`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 161.0.0.0.0
-  __TEXT.__text: 0x960bc
+  __TEXT.__text: 0x9613c
   __TEXT.__auth_stubs: 0xce0
   __TEXT.__const: 0xc75
-  __TEXT.__cstring: 0x387a7
+  __TEXT.__cstring: 0x3882f
   __TEXT.__oslogstring: 0xb0
   __TEXT.__unwind_info: 0xee0
   __DATA_CONST.__const: 0x22910

   - /usr/lib/libssl.48.dylib
   Functions: 909
   Symbols:   2261
-  CStrings:  12428
+  CStrings:  12432
 
Functions:
~ _print_pktap_header : 5224 -> 5272
~ sub_10008b270 -> sub_10008b2a0 : 88 -> 104
~ _print_pcap_ng_block : 8764 -> 8812
~ sub_10009457c -> sub_1000945ec : 88 -> 104
CStrings:
+ "DROP_REASON_FSW_TX_FLOW_AOP_OFFLOAD"
+ "DROP_REASON_FSW_TX_FLOW_BAD_ID"
+ "DROP_REASON_FSW_TX_FLOW_TORN_DOWN"
+ "DROP_REASON_FSW_TX_FLOW_WRONG_PORT"
```
