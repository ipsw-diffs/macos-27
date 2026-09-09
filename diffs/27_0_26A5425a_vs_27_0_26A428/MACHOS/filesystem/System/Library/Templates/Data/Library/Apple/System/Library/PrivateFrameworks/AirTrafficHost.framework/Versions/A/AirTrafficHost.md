## AirTrafficHost

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/AirTrafficHost.framework/Versions/A/AirTrafficHost`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 4026.140.1.0.0
-  __TEXT.__text: 0x33270
+  __TEXT.__text: 0x330c4
   __TEXT.__auth_stubs: 0x770
   __TEXT.__cstring: 0x23df
   __TEXT.__const: 0x67a0
-  __TEXT.__unwind_info: 0x2a0
+  __TEXT.__unwind_info: 0x390
   __DATA_CONST.__const: 0xdf8
   __DATA_CONST.__cfstring: 0x740
   __DATA_CONST.__auth_got: 0x3b8
Functions:
~ _ATHostConnectionDestroy : 64 -> 52
~ __ATHostConnectionDestroy : 164 -> 152
~ _ATHostConnectionRetain : 68 -> 56
~ _ATHostConnectionRelease : 120 -> 108
~ _ATHostConnectionInvalidate : 84 -> 72
~ _ATHostConnectionSendConnectionInvalid : 92 -> 80
~ _ATHostConnectionSendPing : 92 -> 80
~ __On_Queue_ATHostMessageLinkObserverInvokeMessageReceivedCallback : 92 -> 80
~ __ATHostMessageLinkDeviceObserverCallback : 204 -> 192
~ _ATHostMessageLinkDestroy : 252 -> 240
~ __ATHostMessageLinkSendMessage : 108 -> 96
~ __ATHostMessageLinkHandleDeviceObserverNotification : 360 -> 348
~ __ATHostMessageLinkReconnect : 108 -> 96
~ __ATHostMessageLinkDeviceNotificationObserverCallback : 108 -> 96
~ __ATHostMessageLinkConnect : 256 -> 244
~ __ATHostMessageLinkDeviceSocketObserverCallback : 156 -> 144
~ __ATHostMessageLinkHandleSocketNotification : 936 -> 916
~ __ATHostMessageLinkInvokeObserverCallback : 80 -> 68
~ _ATHostDeviceObserverDestroy : 264 -> 252
~ __ATHostDeviceObserverHandleDeviceNotification : 624 -> 612
~ _ATCFMessageGetParam : 80 -> 68
~ __ATHostMDSocketStartReading : 420 -> 396
~ _ATHostAMDeviceSocketDestroy : 168 -> 156
~ _ATHostAMDeviceSocketWrite : 192 -> 180
~ __ATHostAMDeviceEnqueueDataForWriting : 300 -> 288
~ __ATHostMDSocketHandleClose : 128 -> 116
~ __ATHostAMDeviceSocketProcessIncomingData : 84 -> 72
~ _ATProcessLinkSendMessage : 412 -> 388
~ __closeReadWriteFds : 100 -> 88
~ _ATProcessLinkRelease : 208 -> 196
~ __ATHostDeviceNotificationObserverSecureListenCallback : 392 -> 380
~ _ATHostDeviceNotificationObserverDestroy : 204 -> 192
~ __ATHostDeviceNotificationObserverHandleDeviceNotification : 80 -> 68
```
