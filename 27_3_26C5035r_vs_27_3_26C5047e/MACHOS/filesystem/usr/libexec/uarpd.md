## uarpd

> `/usr/libexec/uarpd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1587.60.11.0.0
-  __TEXT.__text: 0xadc4c
+1587.60.14.0.0
+  __TEXT.__text: 0xadedc
   __TEXT.__auth_stubs: 0x960
-  __TEXT.__objc_stubs: 0xada0
-  __TEXT.__objc_methlist: 0x8a40
-  __TEXT.__objc_methname: 0xfb62
+  __TEXT.__objc_stubs: 0xadc0
+  __TEXT.__objc_methlist: 0x8a48
+  __TEXT.__objc_methname: 0xfb70
   __TEXT.__objc_classname: 0x1d25
-  __TEXT.__cstring: 0xb800
+  __TEXT.__cstring: 0xb801
   __TEXT.__objc_methtype: 0x2b3a
   __TEXT.__const: 0x140
-  __TEXT.__gcc_except_tab: 0x1ec
-  __TEXT.__oslogstring: 0x9a5e
-  __TEXT.__unwind_info: 0x3358
-  __DATA_CONST.__const: 0x11b0
+  __TEXT.__gcc_except_tab: 0x208
+  __TEXT.__oslogstring: 0x9a2b
+  __TEXT.__unwind_info: 0x3368
+  __DATA_CONST.__const: 0x11e0
   __DATA_CONST.__cfstring: 0x5780
   __DATA_CONST.__objc_classlist: 0x610
   __DATA_CONST.__objc_catlist: 0x18

   __DATA_CONST.__auth_got: 0x4c0
   __DATA_CONST.__got: 0x670
   __DATA.__objc_const: 0x10ab0
-  __DATA.__objc_selrefs: 0x33a0
+  __DATA.__objc_selrefs: 0x33a8
   __DATA.__objc_ivar: 0xb90
   __DATA.__objc_data: 0x3ca0
   __DATA.__data: 0x548

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 4070
+  Functions: 4073
   Symbols:   223
   CStrings:  5141
 
CStrings:
+ "%s: Endpoint has no config %@, use database entry"
+ "-[UARPHostEndpoint hostEndpointAcceptsAssetManagerNotification:]_block_invoke"
+ "createConfig"
+ "hostEndpointAcceptsAssetManagerNotification:"
- "%s: Endpoint has no config %@ "
- "%s: database entry %@ not updated for greater available version of %@"
- "-[UARPHostEndpoint hostEndpointAcceptsAssetManagerNotification]_block_invoke"
- "hostEndpointAcceptsAssetManagerNotification"
```
