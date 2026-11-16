## RemoteHID

> `/System/Library/PrivateFrameworks/RemoteHID.framework/Versions/A/RemoteHID`

```diff

 224.40.2.0.0
-  __TEXT.__text: 0xac84
+  __TEXT.__text: 0xac4c
   __TEXT.__objc_methlist: 0x540
   __TEXT.__const: 0x260
   __TEXT.__gcc_except_tab: 0x588
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[HIDRemoteEndpoint getDevice:] : 128 -> 124
~ -[HIDRemoteEndpoint addDevice:] : 220 -> 216
~ -[HIDRemoteEndpoint _removeDeviceID:] : 368 -> 364
~ -[HIDRemoteEndpoint removeAllDevices] : 284 -> 280
~ -[HIDRemoteEndpoint logRemovedDevice:] : 148 -> 144
~ -[HIDRemoteEndpoint copyState] : 344 -> 340
~ -[HIDRemoteEndpoint devices] : 76 -> 72
~ -[HIDRemoteDeviceServer endpoints] : 76 -> 72
~ -[HIDRemoteDeviceServer getEndpoint:] : 128 -> 124
~ -[HIDRemoteDeviceServer connectEndpoint:] : 200 -> 196
~ -[HIDRemoteDeviceServer _disconnectEndpointID:] : 228 -> 224
~ -[HIDRemoteDeviceServer disconnectAll] : 152 -> 148
~ -[HIDRemoteDeviceServer getRefreshCountForEndpoint:deviceID:] : 380 -> 376
~ -[HIDRemoteDeviceServer setRefreshCountForEndpoint:deviceID:count:] : 408 -> 404
```
