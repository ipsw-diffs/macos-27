## BoardServices

> `/System/Library/PrivateFrameworks/BoardServices.framework/Versions/A/BoardServices`

```diff

 827.2.3.0.0
-  __TEXT.__text: 0x85068
+  __TEXT.__text: 0x85088
   __TEXT.__objc_methlist: 0x255c
   __TEXT.__const: 0x1b00
   __TEXT.__constg_swiftt: 0x94c
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[BSXPCServiceConnection _lock_disconnect] : 480 -> 476
~ -[BSXPCServiceConnection sendBarrierBlock:] : 876 -> 872
~ -[BSXPCServiceConnection activeMessageBatch] : 84 -> 80
~ -[BSXPCServiceConnection shouldSendMessage:] : 1228 -> 1224
~ sub_18cbaa8b4 -> sub_18cc198a4 : 316 -> 352
~ sub_18cbbc99c -> sub_18cc2b9b0 : 112 -> 124
```
