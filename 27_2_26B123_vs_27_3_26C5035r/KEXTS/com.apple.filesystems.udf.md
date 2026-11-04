## com.apple.filesystems.udf

> `com.apple.filesystems.udf`

```diff

-331.40.5.0.0
+331.60.2.0.0
   __TEXT.__const: 0x1b08
-  __TEXT.__cstring: 0x307c
-  __TEXT_EXEC.__text: 0x2fa04
+  __TEXT.__cstring: 0x3193
+  __TEXT_EXEC.__text: 0x2fbd4
   __TEXT_EXEC.__auth_stubs: 0xa50
   __DATA.__data: 0x4f8
   __DATA.__common: 0x4d8

   __DATA_CONST.__kalloc_var: 0xa0
   __DATA_CONST.__auth_got: 0x528
   __DATA_CONST.__got: 0x20
-  Functions: 860
+  Functions: 859
   Symbols:   1175
-  CStrings:  348
+  CStrings:  353
 
Symbols:
+ __ZN15UDFDeviceBufferC2EP8UDFMountj
+ __ZN18UDFDeviceBufferLRUC1EP8UDFMountj
+ __ZN18UDFDeviceBufferLRUC2EP8UDFMountj
- __ZN15UDFDeviceBufferC2EP8UDFMountm
- __ZN18UDFDeviceBufferLRUC1EP8UDFMountm
- __ZN18UDFDeviceBufferLRUC2EP8UDFMountm
CStrings:
+ "Device buffer hash too large: %zu entries"
+ "Device buffer too large: %u packets of %zu bytes"
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "embedded data end exceeds sector size"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "\"non-memory resident sparing table is not implemented yet\" @%s:%d"
- "UDFPartition.cpp"
```
