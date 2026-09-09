## com.apple.driver.AppleEffaceableStorage

> `com.apple.driver.AppleEffaceableStorage`

```diff

 92.0.0.0.0
   __TEXT.__cstring: 0x148b
   __TEXT.__const: 0x44
-  __TEXT_EXEC.__text: 0x4e3c
+  __TEXT_EXEC.__text: 0x4f58
   __TEXT_EXEC.__auth_stubs: 0x240
   __DATA.__data: 0xc8
   __DATA.__common: 0x60
Functions:
~ _startEffaceableNOR : 284 -> 288
~ _getUnitsPerGroup : 84 -> 88
~ _eraseGroup : 96 -> 100
~ _writeUnit : 144 -> 148
~ _readUnit : 132 -> 136
~ _startEffaceableStorage : 1792 -> 1796
~ _logf : 60 -> 64
~ _getCapacity : 44 -> 48
~ _getCopiesPerUnit : 80 -> 84
~ _revealCopy : 284 -> 288
~ _effaceGroup : 580 -> 584
~ _cleanBuffers : 236 -> 240
~ _checksumCopy : 224 -> 228
~ _updateDynamicProperties : 168 -> 172
~ _setLockerWithIDExternal : 564 -> 568
~ _spaceForLocker : 308 -> 312
~ _generateNonce : 288 -> 292
~ _consumeNonce : 184 -> 188
~ _formatStorage : 400 -> 404
~ _getBytes : 320 -> 324
~ _setBytes : 756 -> 760
~ _wipeStorage : 444 -> 448
~ _getLockerInternal : 272 -> 276
~ _findLockerForRequest : 100 -> 104
~ _discardLockers : 132 -> 136
~ _getLockersFromStorage : 624 -> 628
~ _setLockerInternal : 552 -> 556
~ _putLockersInStorage : 404 -> 412
~ _effaceLockerInternal : 400 -> 404
~ _writeClone : 1104 -> 1108
~ __ZN22AppleEffaceableStorage9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleEffaceableStorageC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleEffaceableStorage9MetaClassC2Ev : 72 -> 76
~ __ZN22AppleEffaceableStorage5startEP9IOService : 968 -> 972
~ __ZN22AppleEffaceableStorage4logkEPvPKcz : 52 -> 56
~ __ZN22AppleEffaceableStorage4logfEPvPKcz : 52 -> 56
~ __ZN22AppleEffaceableStorage14setLockerGatedEjPKvyb : 56 -> 60
~ __ZN22AppleEffaceableStorage20setLockerWithIDGatedEP16_setLockerWithID : 84 -> 88
~ __ZN22AppleEffaceableStorage19spaceForLockerGatedEjPy : 84 -> 88
~ __ZN22AppleEffaceableStorage17effaceLockerGatedEjb : 56 -> 60
~ __ZN22AppleEffaceableStorage18generateNonceGatedEPv : 56 -> 60
~ __ZN22AppleEffaceableStorage18formatStorageGatedEv : 56 -> 60
~ __ZN22AppleEffaceableStorage13getBytesGatedEPvyy : 56 -> 60
~ __ZN22AppleEffaceableStorage13setBytesGatedEPvyy : 56 -> 60
~ __ZN22AppleEffaceableStorage16wipeStorageGatedEPv : 56 -> 60
~ __ZN22AppleEffaceableStorage15registerServiceEj : 216 -> 220
~ __ZN22AppleEffaceableStorage11getCapacityEv : 40 -> 44
~ __ZN22AppleEffaceableStorage8getBytesEPvyy : 172 -> 176
~ __ZN22AppleEffaceableStorage8setBytesEPKvyy : 172 -> 176
~ __ZN22AppleEffaceableStorage11wipeStorageEv : 148 -> 152
~ __ZN22AppleEffaceableStorage15setLockerWithIDEjPKvyjb : 116 -> 120
~ __ZN22AppleEffaceableStorage8vlogfSysEPKcPc : 36 -> 40
~ __ZN22AppleEffaceableStorage11calcSHA1SysEPKvjPv : 112 -> 116
~ __Z9vlogfHookP18_effaceable_systemPKcPc : 48 -> 52
~ _GLOBAL__sub_I_AppleEffaceableStorage.cpp : 80 -> 84
~ __ZN32AppleEffaceableStorageUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN32AppleEffaceableStorageUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN32AppleEffaceableStorageUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN32AppleEffaceableStorageUserClientD0Ev : 68 -> 72
~ __ZN32AppleEffaceableStorageUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK32AppleEffaceableStorageUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN32AppleEffaceableStorageUserClientC1Ev : 88 -> 92
~ __ZN32AppleEffaceableStorageUserClientC2Ev : 88 -> 92
~ __ZN32AppleEffaceableStorageUserClient5startEP9IOService : 168 -> 172
~ __ZN32AppleEffaceableStorageUserClient11clientCloseEv : 64 -> 68
~ __ZN32AppleEffaceableStorageUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 1772 -> 1776
~ _GLOBAL__sub_I_AppleEffaceableStorageUserClient.cpp : 80 -> 84
~ __Z9panicHookP18_effaceable_systemPKc : 32 -> 36
~ __ZN22AppleEffaceableStorage8panicSysEPKc : 20 -> 24
~ _Z7contextP18_effaceable_system.cold.1 : 20 -> 24
```
