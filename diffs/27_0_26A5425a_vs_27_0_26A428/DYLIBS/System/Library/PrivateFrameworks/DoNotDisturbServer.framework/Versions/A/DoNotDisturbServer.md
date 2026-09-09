## DoNotDisturbServer

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/Versions/A/DoNotDisturbServer`

```diff

 511.0.0.0.0
-  __TEXT.__text: 0xc6e98
+  __TEXT.__text: 0xc6f04
   __TEXT.__objc_methlist: 0xa774
   __TEXT.__const: 0x688
   __TEXT.__cstring: 0x8784

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3873
+  Functions: 3874
   Symbols:   9195
   CStrings:  2127
 
Functions:
~ _DNDSRedactSysdiagnose : 92 -> 96
~ -[DNDSSyncEngineMetadataStore recordWithID:].cold.1 : 156 -> 152
~ -[DNDSSyncEngineMetadataStore purge].cold.1 : 64 -> 72
~ -[DNDSSyncEngineMetadataStore _read].cold.1 : 96 -> 92
~ -[DNDSSyncEngineMetadataStore _write].cold.1 : 64 -> 72
+ -[DNDSIDSSyncEngineMetadataStore _read].cold.1
```
