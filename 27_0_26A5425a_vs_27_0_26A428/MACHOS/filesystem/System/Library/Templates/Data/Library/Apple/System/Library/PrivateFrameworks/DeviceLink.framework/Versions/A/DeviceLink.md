## DeviceLink

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceLink.framework/Versions/A/DeviceLink`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 307.0.0.0.0
-  __TEXT.__text: 0xeca8
+  __TEXT.__text: 0xe948
   __TEXT.__auth_stubs: 0xcb0
   __TEXT.__cstring: 0x5389
   __TEXT.__const: 0x48
-  __TEXT.__unwind_info: 0x358
+  __TEXT.__unwind_info: 0x4d0
   __DATA_CONST.__const: 0x220
   __DATA_CONST.__cfstring: 0x3600
   __DATA_CONST.__auth_got: 0x658
Functions:
~ _genericConnectionMadeCallback : 84 -> 72
~ _genericConnectionFailedCallback : 136 -> 124
~ _genericAcceptFailedCallback : 136 -> 124
~ _genericConnectionLostCallback : 112 -> 100
~ _genericProcessMessageCallback : 160 -> 148
~ _genericSendFileCallback : 176 -> 164
~ __DLHandlerThreadMessagePortCallback : 6272 -> 6252
~ __DLRequestRead : 140 -> 116
~ __DLCallHistoryMain : 156 -> 132
~ __DLRequestWriteV : 168 -> 156
~ __SendMessage : 140 -> 116
~ __DLHandlerThreadWriteMessage : 104 -> 80
~ __DLSendDataAndDisconnectOnError : 124 -> 100
~ __DLCreateDeviceLinkConnectionForDevice : 208 -> 196
~ __DLCreateDeviceLinkConnectionForComputer : 228 -> 216
~ _DLCreateDeviceLinkConnectionForDevice : 188 -> 176
~ _DLCreateDeviceLinkConnectionForComputer : 208 -> 196
~ _DLWaitForConnection : 420 -> 408
~ _DLConnect : 404 -> 392
~ _DLDeviceReady : 104 -> 92
~ __DLOperationProgressContextUpdate : 168 -> 164
~ __DLBulkOperationContextMergeResults : 172 -> 160
~ __DLBulkOperationContextUpdate : 192 -> 180
~ __DLRemoveItemOnComputerCallback : 68 -> 56
~ __DLCallHistoryAddEntry : 136 -> 124
~ __DLSendData : 160 -> 148
~ __DLUpdateProgress : 128 -> 116
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ _OUTLINED_FUNCTION_0 : 52 -> 40
~ _OUTLINED_FUNCTION_1 : 36 -> 24
~ _SocketStreamHandlerCreator : 204 -> 192
~ _SocketStreamHandlerAccept : 516 -> 504
~ _SocketStreamHandlerConnect : 668 -> 656
~ __SocketLogCallback : 108 -> 96
~ _StreamHandlerRegisterCreatorForType : 136 -> 124
~ _StreamHandlerForType : 280 -> 256
~ _StreamHandlerSend : 312 -> 300
~ _StreamHandlerReceive : 308 -> 296
~ _SocketLog : 96 -> 84
~ _SocketDelete : 100 -> 88
~ _DLThreadDeleteSendPort : 64 -> 52
~ _DLThreadSendMessage : 56 -> 44
~ _DLShouldLog : 76 -> 64
~ __DLWarnAboutUsingCopyHomeDirPathAndCallDLCopyHomeDirPath : 112 -> 100
~ _DLStringByAppendingPathComponent : 268 -> 256
~ _DLEnsureDirectoryExists : 672 -> 648
~ _DLSetProcessName : 92 -> 80
~ _DLRegenerateUniqueProcessName : 232 -> 220
~ _DLSetLogDirectoryName : 100 -> 88
~ _DLCreateStringFromData : 88 -> 76
~ _copyKeysAndValuesFromDictionaryNoRetain : 116 -> 104
~ _copyKeysAndValuesFromDictionary : 132 -> 120
~ _DLReleaseFlockForFile : 308 -> 296
~ _initializeLogging : 108 -> 96
~ __DLAddNumberToDict : 204 -> 180
~ __DLAddDateToDict : 208 -> 184
~ __gatherDictionaryKeysAndValues : 116 -> 104
~ __DLDeviceRelease : 216 -> 204
~ __DLDeviceGetDeviceIdentifier : 80 -> 68
~ __AMDeviceNotification : 1240 -> 1216
~ _DLDeviceListenerDestroy : 96 -> 84
```
