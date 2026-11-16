## com.apple.filesystems.udf

> `com.apple.filesystems.udf`

```diff

-331.60.2.0.0
+331.60.4.0.0
   __TEXT.__const: 0x1b08
-  __TEXT.__cstring: 0x3193
-  __TEXT_EXEC.__text: 0x2fbd4
-  __TEXT_EXEC.__auth_stubs: 0xa50
+  __TEXT.__cstring: 0x33bc
+  __TEXT_EXEC.__text: 0x2ffc8
+  __TEXT_EXEC.__auth_stubs: 0xa70
   __DATA.__data: 0x4f8
-  __DATA.__common: 0x4d8
+  __DATA.__common: 0x4d0
   __DATA.__bss: 0x1425
   __DATA_CONST.__const: 0x1140
-  __DATA_CONST.__kalloc_var: 0xa0
-  __DATA_CONST.__auth_got: 0x528
+  __DATA_CONST.__kalloc_var: 0x460
+  __DATA_CONST.__kalloc_type: 0x100
+  __DATA_CONST.__auth_got: 0x538
   __DATA_CONST.__got: 0x20
-  Functions: 859
-  Symbols:   1175
-  CStrings:  353
+  Functions: 858
+  Symbols:   1190
+  CStrings:  368
 
Symbols:
+ _IOFreeTypeImpl
+ _IOMallocTypeImpl
+ __ZN11UDFDirCacheC1Em
+ __ZN11UDFDirCacheC2Em
+ __ZZN11UDFDirCache17RemoveAndFreeNodeEPKhijE20kalloc_type_view_147
+ __ZZN11UDFDirCache23FindAndRemoveSpareEntryEjjjPxPjE20kalloc_type_view_170
+ __ZZN11UDFDirCache6ExpandEvE20kalloc_type_view_199
+ __ZZN11UDFDirCache6ExpandEvE20kalloc_type_view_208
+ __ZZN11UDFDirCache6InsertEPKhijjE19kalloc_type_view_95
+ __ZZN11UDFDirCacheC1EmE19kalloc_type_view_55
+ __ZZN11UDFDirCacheD1EvE19kalloc_type_view_66
+ __ZZN11UDFDirCacheD1EvE19kalloc_type_view_69
+ __ZZN12UDFAllocZone8GrowZoneEmE20kalloc_type_view_119
+ __ZZN12UDFAllocZone8GrowZoneEmE20kalloc_type_view_125
+ __ZZN12UDFAllocZone8GrowZoneEmE20kalloc_type_view_134
+ __ZZN12UDFAllocZone8GrowZoneEmE20kalloc_type_view_142
+ __ZZN12UDFAllocZone8GrowZoneEmE20kalloc_type_view_166
+ __ZZN12UDFAllocZone8GrowZoneEmE20kalloc_type_view_167
+ __ZZN12UDFAllocZoneD1EvE19kalloc_type_view_67
+ __ZZN12UDFAllocZoneD1EvE19kalloc_type_view_68
- __ZN11UDFDirCacheC1EmP12UDFAllocZone
- __ZN11UDFDirCacheC2EmP12UDFAllocZone
- __ZN12UDFAllocZone14GuaranteeSpaceEm
- __ZN12UDFAllocZone18AddChunkToFreeListERK12UDFChunkInfo
- _udfDirCachePageableZone
CStrings:
+ "\"UDFAllocZone::Free: free stack overflow (double free or foreign pointer)\" @%s:%d"
+ "12"
+ "21"
+ "File times EA backup time offset %lld out of bounds, ignoring"
+ "File times EA creation time offset %lld out of bounds, ignoring"
+ "File times EA length %lld too short for %u timestamp(s), ignoring"
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
+ "UDFAllocZone.cpp"
+ "site.UDFDirHashBucket"
+ "site.UDFDirHashEntry"
+ "site.struct UDFChunkInfo"
+ "site.void*"
```
