## appleh16camerad

> `/usr/sbin/appleh16camerad`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-6.201.0.0.0
-  __TEXT.__text: 0x88460
-  __TEXT.__auth_stubs: 0x1740
+6.203.0.0.0
+  __TEXT.__text: 0x89014
+  __TEXT.__auth_stubs: 0x17a0
   __TEXT.__objc_stubs: 0xac0
   __TEXT.__init_offsets: 0x1c
   __TEXT.__objc_methlist: 0x334
-  __TEXT.__cstring: 0x6624
+  __TEXT.__cstring: 0x6677
   __TEXT.__const: 0x19be0
-  __TEXT.__gcc_except_tab: 0x10c0
-  __TEXT.__oslogstring: 0x4713
+  __TEXT.__gcc_except_tab: 0x10bc
+  __TEXT.__oslogstring: 0x488f
   __TEXT.__objc_methname: 0xad2
   __TEXT.__objc_classname: 0xa9
   __TEXT.__objc_methtype: 0x63d
-  __TEXT.__unwind_info: 0x17c0
-  __DATA_CONST.__const: 0xa3d0
+  __TEXT.__unwind_info: 0x1808
+  __DATA_CONST.__const: 0xa3f0
   __DATA_CONST.__cfstring: 0x23c0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_protolist: 0x20

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA_CONST.__auth_got: 0xbb0
+  __DATA_CONST.__auth_got: 0xbe0
   __DATA_CONST.__got: 0x1280
   __DATA_CONST.__auth_ptr: 0x38
   __DATA.__objc_const: 0x5c8
   __DATA.__objc_selrefs: 0x3e0
   __DATA.__objc_ivar: 0x14
   __DATA.__objc_data: 0xf0
-  __DATA.__data: 0x3812b0
+  __DATA.__data: 0x3812b8
   __DATA.__bss: 0x2580
   __DATA.__common: 0x18
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1364
-  Symbols:   985
-  CStrings:  1528
+  Functions: 1384
+  Symbols:   991
+  CStrings:  1541
 
Symbols:
+ _xpc_connection_send_message_with_reply
+ _xpc_connection_send_message_with_reply_sync
+ _xpc_copy_description
+ _xpc_dictionary_create
+ _xpc_dictionary_get_int64
+ _xpc_dictionary_set_uint64
CStrings:
+ "%s - assistant failed to load setfiles: 0x%08x\n"
+ "%s - received async error reply: %s\n"
+ "%s - received error reply: %s\n"
+ "%s - received invalid reply\n"
+ "%s - received reply\n"
+ "%s: CloseInterfaceToSavageCam without a matching open\n"
+ "6.203"
+ "H16ISPServicesRemote: SetProperty %d (reply=0x%08X)\n"
+ "H16ISPServicesRemote: SetProperty %d (sent)\n"
+ "H16ISPServicesRemote: SetProperty (async) %d (reply=0x%08X)\n"
+ "ISP_BuildAndLoadSetfile"
+ "LoadSetfiles"
+ "sendMessageAsync_block_invoke"
+ "sendMessageSync"
- "6.201"
```
