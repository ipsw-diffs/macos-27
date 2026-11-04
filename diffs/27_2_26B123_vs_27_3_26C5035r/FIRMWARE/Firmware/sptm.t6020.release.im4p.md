## sptm.t6020.release.im4p

> `Firmware/sptm.t6020.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`
- `__DATA.__auth_ptr`

```diff

-820.40.24.0.0
-  __TEXT.__cstring: 0x153d0
+820.60.12.0.0
+  __TEXT.__cstring: 0x154ba
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7b68
   __LATE_CONST.__late_const: 0x8ca50
-  __TEXT_EXEC.__text: 0x5c7c8
+  __TEXT_EXEC.__text: 0x5cc44
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __DATA.__bss: 0x6128
   __DATA.__common: 0x21c88
   __BOOTDATA.__data: 0x18000
-  Functions: 394
+  Functions: 396
   Symbols:   1
-  CStrings:  2484
+  CStrings:  2491
 
CStrings:
+ "%s(%s:%d) - papt_start(%#llx), num_mappings(%u), flags(%#x)\n"
+ "%s: (range %s): no primary range found for requested alias at phys %p, size %u"
+ "%s: (range %s): reserved VA range must not have a physical address"
+ "SPTM-820.60.12|2026-10-30:01:13:02.026540|"
+ "SPTM_FUNCTIONID_REMAP_REGION_RNX"
+ "sptm_prepare_region_for_remapping"
+ "sptm_remap_region_rnx"
+ "target_papt.num_mappings"
+ "target_papt.start"
- "%s: dart %p (%s:%u): SID %u leaf page table flags present in level %hhu page table entry %#zx: 0x%016llx"
- "SPTM-820.40.24|2026-10-07:21:08:19.808229|"
```
