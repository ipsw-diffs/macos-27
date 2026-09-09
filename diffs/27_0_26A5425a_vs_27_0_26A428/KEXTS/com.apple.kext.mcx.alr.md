## com.apple.kext.mcx.alr

> `com.apple.kext.mcx.alr`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

   __TEXT.__cstring: 0xe4d
   __TEXT.__os_log: 0xc
   __TEXT.__const: 0x28
-  __TEXT_EXEC.__text: 0x448c
+  __TEXT_EXEC.__text: 0x45e4
   __TEXT_EXEC.__auth_stubs: 0x390
   __DATA.__data: 0x340
   __DATA.__bss: 0xb31
Functions:
~ _mystrprefix : 32 -> 36
~ __Z12InitKernUtilPKc : 72 -> 76
~ __Z12TermKernUtilv : 48 -> 52
~ __ZN10TMutexLockC2Ev : 60 -> 64
~ __ZN10TMutexLockD2Ev : 56 -> 60
~ _MyLog : 52 -> 56
~ __ZL6vMyLog13os_log_type_tPKcPc : 228 -> 232
~ _dbgAssert : 44 -> 48
~ _dbgAssertPrint : 92 -> 96
~ __ZN13TManagedUsersC2Ev : 76 -> 80
~ __ZN13TManagedUsersD2Ev : 80 -> 84
~ __ZN13TManagedUsers15CreateObjForUIDEj : 84 -> 88
~ __ZN13TManagedUsers9IsManagedEj : 200 -> 204
~ __ZN13TManagedUsers10SetManagedEjb : 508 -> 512
~ __ZL15InstallListenerv : 296 -> 300
~ __ZN13TManagedUsers10GetManagedER8TCString : 436 -> 440
~ __ZN17MCX_ALR_KeepAlive9MetaClassC1Ev : 72 -> 76
~ __ZN17MCX_ALR_KeepAliveC2EPK11OSMetaClass : 52 -> 56
~ __ZN17MCX_ALR_KeepAliveD0Ev : 68 -> 72
~ __ZNK17MCX_ALR_KeepAlive9MetaClass5allocEv : 104 -> 108
~ __ZN17MCX_ALR_KeepAliveC1Ev : 88 -> 92
~ __ZN19TMCX_ALR_Connection9MetaClassC1Ev : 72 -> 76
~ __ZN19TMCX_ALR_ConnectionC2EPK11OSMetaClass : 72 -> 76
~ __ZN19TMCX_ALR_ConnectionD2Ev : 84 -> 88
~ __ZN19TMCX_ALR_ConnectionD1Ev : 84 -> 88
~ __ZN19TMCX_ALR_ConnectionD0Ev : 104 -> 108
~ __ZNK19TMCX_ALR_Connection9MetaClass5allocEv : 52 -> 56
~ __ZN19TMCX_ALR_ConnectionC2Ev : 92 -> 96
~ __ZN19TMCX_ALR_Connection4initEv : 112 -> 116
~ __ZN19TMCX_ALR_Connection4freeEv : 264 -> 268
~ __ZN11AuthRequestD1Ev : 56 -> 60
~ __ZN12UConnections4InitEv : 72 -> 76
~ __ZN12UConnections4FreeEv : 88 -> 92
~ __ZN12UConnections3AddEP19TMCX_ALR_Connection : 148 -> 152
~ __ZN12UConnections6RemoveEP19TMCX_ALR_Connection : 192 -> 196
~ __ZN12UConnections4FindEjPv : 196 -> 200
~ __ZN12UConnections16FindAuthProviderEj : 264 -> 268
~ __ZN12UConnections9GetStatusER8TCString : 476 -> 480
~ __ZL12SysctlUnloadP10sysctl_oidPviP10sysctl_req : 208 -> 212
~ __ZL14SysctlLogExecsP10sysctl_oidPviP10sysctl_req : 144 -> 148
~ _com_apple_kext_mcx_alr_start : 480 -> 484
~ __ZL6DoStopb : 372 -> 376
~ __ZL17MACCheckVNodeExecP5ucredP5vnodeS2_P5labelS4_S4_P13componentnamePjPvm : 2152 -> 2156
~ __ZL13SendTokenListPvjR15TTokenGenerator : 196 -> 200
~ __ZL11ctl_connectPvP12sockaddr_ctlPS_ : 232 -> 236
~ __ZL14ctl_disconnectPvjS_ : 324 -> 328
~ __ZL8ctl_sendPvjS_P6__mbufi : 1704 -> 1708
~ __ZL20SetAuthRequestResultP11AuthRequestij : 104 -> 108
~ __ZL16ProcessAuthReplyP19TMCX_ALR_Connectioniij : 316 -> 320
~ __ZL22DisconnectAuthProviderjPKc : 140 -> 144
~ __ZL9ShowStatsv : 364 -> 368
~ __ZL14SendDisconnectP19TMCX_ALR_ConnectionPKc : 160 -> 164
~ _GLOBAL__sub_I_mcxalrkext.cp : 148 -> 152
~ __GLOBAL__D_a : 56 -> 60
~ __Z5streqPKcS0_ : 84 -> 88
~ __ZN8TCStringC2ERKS_ : 60 -> 64
~ __ZN8TCString6AssignEPKc : 84 -> 88
~ __ZN8TCStringC2EPKc : 56 -> 60
~ __ZN9TvCStringC2EPKcz : 76 -> 80
~ __ZN8TCString8_vAssignEPKcPPc : 232 -> 236
~ __ZN8TCStringD2Ev : 72 -> 76
~ __ZN8TCString5ClearEv : 68 -> 72
~ __ZN8TCString6AssignEPKS_ : 124 -> 128
~ __ZN8TCString13AssignFromPtrEPKvj : 148 -> 152
~ __ZN8TCString7vAssignEPKcz : 44 -> 48
~ __ZN8TCString6AppendEPKc : 240 -> 244
~ __ZN8TCString6AppendEc : 44 -> 48
~ __ZN8TCString7vAppendEPKcz : 116 -> 120
~ __ZN8TCString6InsertEPKcj : 348 -> 352
~ __ZN8TCString4TrimEv : 216 -> 220
~ __ZN12TTokenParserC2EPKcm : 72 -> 76
~ __ZN12TTokenParser13SetFromBufferEPKvm : 236 -> 240
~ __ZN12TTokenParserD2Ev : 76 -> 80
~ __ZN12TTokenParser7DisposeEv : 84 -> 88
~ __ZN12TTokenParser14GetDescriptionEv : 60 -> 64
~ __ZL16BuildDescriptionR8TCStringPKcj : 116 -> 120
~ __ZN12TTokenParser4NextER8TCString : 516 -> 520
~ __ZN12TTokenParser8NextLongEv : 120 -> 124
~ __ZN12TTokenParser12NextLongLongEv : 120 -> 124
~ __ZN15TTokenGeneratorD2Ev : 112 -> 116
~ __ZN15TTokenGenerator3AddEPKc : 340 -> 344
~ __ZN15TTokenGenerator6AddIntEi : 136 -> 140
~ __ZN15TTokenGenerator11AddLongLongEx : 136 -> 140
~ __ZN15TTokenGenerator9AddBinaryEPKvj : 116 -> 120
~ __ZN15TTokenGenerator14GetDescriptionEv : 60 -> 64
~ __ZN15TTokenGenerator8GenerateERj : 224 -> 228
CStrings:
+ "20:38:23"
- "21:38:25"
```
