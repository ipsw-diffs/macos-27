## DeviceInterfaceClient

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterfaceClient.framework/Versions/A/DeviceInterfaceClient`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`

```diff

 294.0.0.0.0
-  __TEXT.__text: 0xabd0
+  __TEXT.__text: 0xab70
   __TEXT.__objc_methlist: 0x848
   __TEXT.__const: 0x48
   __TEXT.__cstring: 0xccf
   __TEXT.__gcc_except_tab: 0x50
   __TEXT.__oslogstring: 0xe
-  __TEXT.__unwind_info: 0x218
-  __TEXT.__eh_frame: 0xd4
+  __TEXT.__unwind_info: 0x4a0
+  __TEXT.__eh_frame: 0xdc
   __TEXT.__objc_stubs: 0xa80
   __TEXT.__auth_stubs: 0x410
   __TEXT.__objc_classname: 0xdc
Functions:
~ -[DeviceInterfaceClientTransportXPCClient createRequestType:] : 288 -> 276
~ -[DeviceInterfaceClientTransportXPCClient sendRequestAndGetResponse:] : 408 -> 396
~ +[DeviceInterfaceClientServerXPCClient sharedInstance] : 220 -> 208
~ +[DeviceInterfaceClientServerXPCClient extractPropertiesFromDictionary:] : 356 -> 344
~ -[DeviceInterfaceClientServerXPCClient createTransportConnection:] : 616 -> 604
~ -[DeviceInterfaceClientServerXPCClient createRequestType:] : 288 -> 276
~ -[DeviceInterfaceClientServerXPCClient sendRequestAndGetResponse:] : 408 -> 396
~ _device_interface_client_server_xpc_client_create_transport_connection : 156 -> 144
```
