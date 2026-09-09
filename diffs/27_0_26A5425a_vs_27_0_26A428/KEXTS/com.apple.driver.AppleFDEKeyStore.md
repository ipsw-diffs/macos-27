## com.apple.driver.AppleFDEKeyStore

> `com.apple.driver.AppleFDEKeyStore`

```diff

 60.0.1.0.0
   __TEXT.__const: 0x20
   __TEXT.__cstring: 0x3be
-  __TEXT_EXEC.__text: 0x53a4
+  __TEXT_EXEC.__text: 0x54d8
   __TEXT_EXEC.__auth_stubs: 0x490
   __DATA.__data: 0x188
   __DATA.__common: 0xb8
Functions:
~ __ZN16AppleFDEKeyStore9MetaClassC1Ev : 72 -> 76
~ __ZN16AppleFDEKeyStoreC2EPK11OSMetaClass : 52 -> 56
~ __ZN16AppleFDEKeyStoreC1EPK11OSMetaClass : 52 -> 56
~ __ZN16AppleFDEKeyStoreD0Ev : 68 -> 72
~ __ZN16AppleFDEKeyStore9MetaClassC2Ev : 72 -> 76
~ __ZNK16AppleFDEKeyStore9MetaClass5allocEv : 104 -> 108
~ __ZN16AppleFDEKeyStoreC1Ev : 88 -> 92
~ __ZN16AppleFDEKeyStoreC2Ev : 88 -> 92
~ __ZN16AppleFDEKeyStore4initEP12OSDictionary : 332 -> 336
~ __ZN16AppleFDEKeyStore4freeEv : 88 -> 92
~ __ZN16AppleFDEKeyStore5startEP9IOService : 536 -> 540
~ __ZN16AppleFDEKeyStore4stopEP9IOService : 120 -> 124
~ __ZN16AppleFDEKeyStore10handleOpenEP9IOServicejPv : 164 -> 168
~ __ZN16AppleFDEKeyStore11handleCloseEP9IOServicej : 208 -> 212
~ __ZNK16AppleFDEKeyStore12handleIsOpenEPK9IOService : 68 -> 72
~ __ZN16AppleFDEKeyStore23setPassphraseWithUserIDEPhPKvjb : 316 -> 320
~ __ZN16AppleFDEKeyStore13getPassphraseEPhPvjPjb : 224 -> 228
~ __ZN16AppleFDEKeyStore16deletePassphraseEPhb : 256 -> 260
~ __ZN16AppleFDEKeyStore13unwrapDiskKEKEPhP14wrappedDiskKEKS0_ : 388 -> 392
~ __ZN16AppleFDEKeyStore18unwrapDiskKEKToSMCEPhP14wrappedDiskKEK : 432 -> 436
~ __ZN16AppleFDEKeyStore11commitStashEv : 1660 -> 1664
~ __ZN16AppleFDEKeyStore6getKeyEPhP9volumeKey : 192 -> 196
~ __ZN16AppleFDEKeyStore11wrapDiskKEKEPhS0_P14wrappedDiskKEK : 328 -> 332
~ __ZN16AppleFDEKeyStore8setPBKDFEP14PBKDF_InStructP14uuid_OutStruct : 404 -> 408
~ __ZN16AppleFDEKeyStore8getPBKDFEP14PBKDF_InStructP18getPBKDF_OutStruct : 256 -> 260
~ __ZN16AppleFDEKeyStore9createKeyEPhjj : 208 -> 212
~ __ZN16AppleFDEKeyStore16setKeyWithUserIDEPhP9volumeKeyb : 300 -> 304
~ __ZN16AppleFDEKeyStore6hasKeyEPh : 124 -> 128
~ __ZN16AppleFDEKeyStore9deleteKeyEPhb : 260 -> 264
~ __ZN16AppleFDEKeyStore15getStashKeyUUIDE16aks_stash_type_tPh : 120 -> 124
~ __ZN16AppleFDEKeyStore16userClientEnryptEP19xtsEncrypt_InStruct : 656 -> 660
~ __ZN16AppleFDEKeyStore8selfTestEPv : 1808 -> 1812
~ __ZN26AppleFDEKeyStoreUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN26AppleFDEKeyStoreUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleFDEKeyStoreUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN26AppleFDEKeyStoreUserClientD0Ev : 68 -> 72
~ __ZN26AppleFDEKeyStoreUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK26AppleFDEKeyStoreUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN26AppleFDEKeyStoreUserClientC1Ev : 88 -> 92
~ __ZN26AppleFDEKeyStoreUserClientC2Ev : 88 -> 92
~ __ZN26AppleFDEKeyStoreUserClient5startEP9IOService : 120 -> 124
~ __ZN26AppleFDEKeyStoreUserClient12initWithTaskEP4taskPvj : 84 -> 88
~ __ZN26AppleFDEKeyStoreUserClient11clientCloseEv : 84 -> 88
~ __ZN26AppleFDEKeyStoreUserClient15userClientCloseEv : 156 -> 160
~ __ZN26AppleFDEKeyStoreUserClient25currentProcHasEntitlementEPKc : 108 -> 112
~ __ZN26AppleFDEKeyStoreUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 2164 -> 2168
~ _GLOBAL__sub_I_AppleFDEKeyStore.cpp : 140 -> 144
~ __GLOBAL__D_a : 56 -> 60
~ _rfc3394_unwrap : 604 -> 608
~ _UnwrapVolumeKEK : 284 -> 288
~ _validateKeyCheck : 280 -> 284
~ _UnwrapVolumeKey : 168 -> 172
~ _assembleKeyCheck : 144 -> 148
~ _getRandomBytes : 40 -> 44
~ _makeKeyCheck : 308 -> 312
~ _CreateKEK : 44 -> 48
~ _CreateVEK : 56 -> 60
~ _WrapVolumeKEK : 356 -> 360
~ _WrapVolumeKey : 164 -> 168
~ _CCKeyDerivationPBKDF : 244 -> 248
~ __ZN16AppleFDEKeyStore20setPassphraseGetUUIDEP29setPassphraseGetUUID_InStructP14uuid_OutStruct : 128 -> 132
~ __ZN16AppleFDEKeyStore19getPassphraseNoCopyEP28getPassphraseNoCopy_InStructP29getPassphraseNoCopy_OutStruct : 360 -> 364
~ __ZN16AppleFDEKeyStore20unwrapDiskKEKGetUUIDEP22unwrapDiskKEK_InStructP14uuid_OutStruct : 124 -> 128
~ __ZN16AppleFDEKeyStore11setStashKeyEPh16aks_stash_type_t : 140 -> 144
~ __ZN16AppleFDEKeyStore22unwrapVolumeKeyGetUUIDEPhP16wrappedVolumeKeyS0_ : 148 -> 152
~ __ZN16AppleFDEKeyStore15unwrapVolumeKeyEPhP16wrappedVolumeKeyS0_ : 252 -> 256
~ __ZN16AppleFDEKeyStore13wrapVolumeKeyEPhS0_P16wrappedVolumeKey : 224 -> 228
~ __ZN16AppleFDEKeyStore16createKeyGetUUIDEP25createKeyGetUUID_InStructP14uuid_OutStruct : 132 -> 136
~ __ZN16AppleFDEKeyStore13setKeyGetUUIDEP22setKeyGetUUID_InStructP14uuid_OutStruct : 124 -> 128
~ __ZN16AppleFDEKeyStore21lookupLocalEffaceableEv : 388 -> 392
~ __ZN16AppleFDEKeyStore11getStashKeyE16aks_stash_type_tP9volumeKey : 96 -> 100
~ __ZN16AppleFDEKeyStore8wrapTestEv : 688 -> 692
~ _ZN16AppleFDEKeyStore5startEP9IOService.cold.1 : 44 -> 48
~ _ZN16AppleFDEKeyStore5startEP9IOService.cold.2 : 80 -> 84
~ _rfc3394_wrap : 524 -> 528
~ _aes_operation : 196 -> 200
~ _CCCalibratePBKDF : 392 -> 396
```
