## uarpd

> `/usr/libexec/uarpd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1587.40.26.0.0
-  __TEXT.__text: 0xacbe4
+1587.40.28.0.0
+  __TEXT.__text: 0xad510
   __TEXT.__auth_stubs: 0x940
-  __TEXT.__objc_stubs: 0xabc0
-  __TEXT.__objc_methlist: 0x8980
-  __TEXT.__objc_methname: 0xf964
+  __TEXT.__objc_stubs: 0xac80
+  __TEXT.__objc_methlist: 0x89c0
+  __TEXT.__objc_methname: 0xfa16
   __TEXT.__objc_classname: 0x1d25
-  __TEXT.__cstring: 0xb5df
-  __TEXT.__objc_methtype: 0x2b2b
-  __TEXT.__const: 0x148
+  __TEXT.__cstring: 0xb788
+  __TEXT.__objc_methtype: 0x2b3a
+  __TEXT.__const: 0x140
   __TEXT.__gcc_except_tab: 0x1ec
-  __TEXT.__oslogstring: 0x9936
-  __TEXT.__unwind_info: 0x3318
+  __TEXT.__oslogstring: 0x99c1
+  __TEXT.__unwind_info: 0x3340
   __DATA_CONST.__const: 0x11b0
   __DATA_CONST.__cfstring: 0x5720
   __DATA_CONST.__objc_classlist: 0x610

   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__auth_got: 0x4b0
-  __DATA_CONST.__got: 0x668
-  __DATA.__objc_const: 0x109b8
-  __DATA.__objc_selrefs: 0x3320
-  __DATA.__objc_ivar: 0xb78
+  __DATA_CONST.__got: 0x670
+  __DATA.__objc_const: 0x10a18
+  __DATA.__objc_selrefs: 0x3350
+  __DATA.__objc_ivar: 0xb84
   __DATA.__objc_data: 0x3ca0
   __DATA.__data: 0x548
   __DATA.__bss: 0x1178

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 4048
-  Symbols:   220
-  CStrings:  5099
+  Functions: 4059
+  Symbols:   221
+  CStrings:  5119
 
Symbols:
+ _OBJC_CLASS_$_NSHashTable
CStrings:
+ "%s: %@, %lu endpoint(s) with transport plumbed"
+ "%s: Not starting pruning timer, paused"
+ "%s: Pausing pruning timer"
+ "%s: Resuming pruning timer"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportPlumbed:]"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportPlumbed:]_block_invoke"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportUnplumbed:]"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportUnplumbed:]_block_invoke"
+ "-[UARPPrunerManager pausePruning]_block_invoke"
+ "-[UARPPrunerManager resumePruning]_block_invoke"
+ "-[UARPPrunerManager startPruningInternal]"
+ "@\"NSHashTable\""
+ "_kQueueKey"
+ "_paused"
+ "_transportPlumbedEndpoints"
+ "hashTableWithOptions:"
+ "hostEndpointTransportPlumbed:"
+ "hostEndpointTransportUnplumbed:"
+ "pausePruning"
+ "resumePruning"
+ "startPruningInternal"
- "-[UARPPrunerManager startPruning]_block_invoke"
```
