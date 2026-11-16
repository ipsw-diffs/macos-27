## FrontBoard

> `/System/Library/PrivateFrameworks/FrontBoard.framework/Versions/A/FrontBoard`

```diff

 1153.3.2.0.0
-  __TEXT.__text: 0x80bbc
+  __TEXT.__text: 0x80b20
   __TEXT.__objc_methlist: 0x5500
   __TEXT.__const: 0x2ac
   __TEXT.__cstring: 0xabdd
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[FBProcess isFinishedLaunching] : 60 -> 56
~ -[FBProcess isForeground] : 68 -> 64
~ -[FBProcess isRunning] : 68 -> 64
~ -[FBProcess isBeingDebugged] : 92 -> 88
~ -[FBProcess isPendingExit] : 60 -> 56
~ -[FBProcess state] : 72 -> 68
~ -[FBProcess applicationInfo] : 284 -> 276
~ -[FBProcess exitContext] : 72 -> 68
~ -[FBProcess bootstrapWithDelegate:] : 160 -> 156
~ -[FBProcess invalidate] : 160 -> 156
~ -[FBProcess taskState] : 68 -> 64
~ -[FBProcess visibility] : 68 -> 64
~ -[FBProcess delegate] : 72 -> 68
~ -[FBProcess executableLivesOnSystemPartition] : 108 -> 104
~ -[FBProcess isPlatformBinary] : 188 -> 184
~ -[FBProcess _executeBlockAfterBootstrap:] : 288 -> 284
~ -[FBProcess _executeBlockAfterLaunchCompletes:] : 240 -> 236
~ -[FBProcess _notePendingExitForReason:] : 672 -> 668
~ -[FBProcess _updateStateWithBlock:] : 640 -> 636
~ ___30-[FBProcess _bootstrapAndExec]_block_invoke.121 : 248 -> 244
~ -[FBProcess _setSceneLifecycleState:] : 184 -> 180
~ -[FBProcess _processDidExitWithContext:] : 656 -> 652
~ ___40-[FBProcess _processDidExitWithContext:]_block_invoke_2 : 328 -> 324
~ -[FBProcess _rebuildState] : 68 -> 64
~ -[FBProcess _rebuildState:] : 280 -> 276
~ -[FBProcess _launchDidComplete:finalizeBlock:] : 1160 -> 1156
~ ___46-[FBProcess _launchDidComplete:finalizeBlock:]_block_invoke_2 : 116 -> 112
~ -[FBProcess _newWatchdogForContext:completion:] : 548 -> 544
~ ___47-[FBProcess _newWatchdogForContext:completion:]_block_invoke : 544 -> 540
~ -[FBProcess _startWatchdogTimerForContext:] : 232 -> 228
~ -[FBProcess _shouldWatchdogWithDeclineReason:] : 252 -> 248
~ -[FBProcess _terminateWithRequest:completion:] : 776 -> 772
~ -[FBProcess _lock_consumeLock_performGracefulKill] : 1840 -> 1836
~ ___50-[FBProcess _lock_consumeLock_performGracefulKill]_block_invoke.296 : 116 -> 112
~ -[FBProcess _terminateWithRequest:forWatchdog:] : 220 -> 216
~ -[FBProcess _watchdog:shouldTerminateWithDeclineReason:] : 320 -> 316
~ -[FBProcess descriptionBuilderWithMultilinePrefix:] : 200 -> 196
~ ___50-[FBProcess _lock_consumeLock_performGracefulKill]_block_invoke.cold.1 : 412 -> 408
```
