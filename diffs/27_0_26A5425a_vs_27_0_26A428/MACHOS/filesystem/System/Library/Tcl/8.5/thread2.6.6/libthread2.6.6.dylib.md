## libthread2.6.6.dylib

> `/System/Library/Tcl/8.5/thread2.6.6/libthread2.6.6.dylib`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 154.0.0.0.0
-  __TEXT.__text: 0xe168
+  __TEXT.__text: 0xe010
   __TEXT.__auth_stubs: 0xf0
   __TEXT.__cstring: 0xefa
-  __TEXT.__unwind_info: 0x220
+  __TEXT.__unwind_info: 0x2d8
   __DATA_CONST.__auth_got: 0x78
   __DATA_CONST.__got: 0x10
   __DATA.__data: 0x118
Functions:
~ _ThreadUnwindObjCmd : 152 -> 140
~ _Init : 244 -> 232
~ _ThreadExitProc : 584 -> 572
~ _ThreadFreeProc : 92 -> 80
~ _ThreadSetResult : 412 -> 400
~ _ThreadSend : 1224 -> 1212
~ _ThreadIdleProc : 96 -> 84
~ _NewThread : 488 -> 476
~ _ThreadCutChannel : 196 -> 184
~ _Sv_RegisterCommand : 208 -> 196
~ _Sv_RegisterObjType : 144 -> 132
~ _Sv_RegisterPsStore : 160 -> 148
~ _SvObjDispatchObjCmd : 288 -> 276
~ _ThreadEvalObjCmd : 720 -> 724
~ _Sp_ExclusiveMutexFinalize : 148 -> 136
~ _Sp_RecursiveMutexFinalize : 148 -> 136
~ _Sp_ReadWriteMutexFinalize : 172 -> 160
~ _PutAnyItem : 116 -> 104
~ _SpMutexLock : 84 -> 72
~ _RemoveAnyItem : 256 -> 244
~ _TpoolCreateObjCmd : 1076 -> 1072
~ _AppExitHandler : 108 -> 96
~ _SignalWaiter : 184 -> 172
~ _InitWaiter : 172 -> 160
~ _Sv_RegisterListCommands : 528 -> 516
~ _SvLpushObjCmd : 424 -> 420
~ _SvLreplaceObjCmd : 696 -> 692
~ _SvLinsertObjCmd : 524 -> 520
~ _SvLrangeObjCmd : 468 -> 464
~ _SvGetIntForIndex : 544 -> 536
~ _Sv_RegisterKeylistCommands : 300 -> 288
~ _DupKeyedListInternalRep : 244 -> 248
~ _TclX_KeyedListGet : 216 -> 204
~ _TclX_KeyedListGetKeys : 428 -> 416
~ _FreeKeyedListData : 192 -> 180
```
