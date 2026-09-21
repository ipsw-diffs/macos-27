## netstat

> `/usr/sbin/netstat`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 757.0.0.0.0
-  __TEXT.__text: 0x1b72c
+  __TEXT.__text: 0x1b7ac
   __TEXT.__auth_stubs: 0x4e0
-  __TEXT.__cstring: 0xf8c1
+  __TEXT.__cstring: 0xf9da
   __TEXT.__const: 0x3d8
   __TEXT.__unwind_info: 0x268
   __DATA_CONST.__const: 0x14b8

   - /usr/lib/libpcap.A.dylib
   Functions: 125
   Symbols:   88
-  CStrings:  2434
+  CStrings:  2442
 
Functions:
~ sub_100018be4 : 4600 -> 4648
~ sub_100019ddc -> sub_100019e0c : 88 -> 104
~ sub_10001a204 -> sub_10001a244 : 5496 -> 5544
~ sub_10001b77c -> sub_10001b7ec : 88 -> 104
CStrings:
+ "DROP_REASON_FSW_TX_FLOW_AOP_OFFLOAD"
+ "DROP_REASON_FSW_TX_FLOW_BAD_ID"
+ "DROP_REASON_FSW_TX_FLOW_TORN_DOWN"
+ "DROP_REASON_FSW_TX_FLOW_WRONG_PORT"
+ "Flowswitch Tx flow id mismatch"
+ "Flowswitch Tx flow torn down"
+ "Flowswitch Tx not allowed on offload flow"
+ "Flowswitch flow not owned by Tx nexus port"
```
