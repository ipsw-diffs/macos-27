## BackgroundTasks

> `/System/Library/Frameworks/BackgroundTasks.framework/Versions/A/BackgroundTasks`

```diff

-2467.60.9.0.0
-  __TEXT.__text: 0xa834
+2467.60.20.0.0
+  __TEXT.__text: 0xa814
   __TEXT.__objc_methlist: 0xe60
   __TEXT.__const: 0xe8
   __TEXT.__cstring: 0x6f4
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[BGTask _setTaskCompletedWithSuccess:actionsIfNotAlreadyCompleted:] : 184 -> 180
~ -[BGTask dealloc] : 220 -> 216
~ -[BGTask _callExpirationHandlerWithReason:] : 188 -> 184
~ -[BGContinuedProcessingTask setTaskPaused] : 412 -> 408
~ -[BGContinuedProcessingTask setExpirationHandler:] : 168 -> 164
~ -[BGContinuedProcessingTask expirationHandler] : 124 -> 120
~ -[BGContinuedProcessingTask setExpirationHandlerWithReason:] : 152 -> 148
~ -[BGContinuedProcessingTask expirationHandlerWithReason] : 92 -> 88
```
