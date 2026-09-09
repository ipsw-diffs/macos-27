## com.apple.kec.AppleEncryptedArchive

> `com.apple.kec.AppleEncryptedArchive`

```diff

 469.0.0.0.0
   __TEXT.__const: 0x10
   __TEXT.__cstring: 0x27
-  __TEXT_EXEC.__text: 0x1a64
+  __TEXT_EXEC.__text: 0x1a9c
   __TEXT_EXEC.__auth_stubs: 0x160
   __DATA.__data: 0xdc
   __DATA_CONST.__const: 0x28
Functions:
~ _AEAKernelEncryptGetStateSize : 48 -> 52
~ _AEAKernelEncryptInitializeState : 656 -> 660
~ _AEAKernelEncryptOpen : 840 -> 844
~ _HKDF : 136 -> 140
~ _writeBytes : 268 -> 272
~ _AEAKernelEncryptWrite : 1128 -> 1132
~ _updateSegment : 240 -> 244
~ _endSegment : 504 -> 508
~ _AEAKernelEncryptClose : 1620 -> 1624
~ _aeadInit : 176 -> 180
~ _aeadUpdateAux : 104 -> 108
~ _aeadUpdateData : 196 -> 200
~ _aeadFinish : 184 -> 188
~ _AppleEncryptedArchive_start : 136 -> 140
```
