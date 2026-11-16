## agx_a000

> `Firmware/agx/armfw_g16s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x51d90
-  __TEXT.__gxf_code: 0x50c0
+  __TEXT.__text: 0x534f4
+  __TEXT.__gxf_code: 0x50f0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x132c
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x2fdb
+  __TEXT.__cstring: 0x3102
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA.__gxf_data: 0x8130
-  __DATA.__data: 0x179b8
+  __DATA.__data: 0x179f8
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0xbb0
   __DATA._rtk_irq_stack: 0x4000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x5ea78
+  __DATA.__zerofill: 0x5fa98
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
-  Functions: 498
+  Functions: 500
   Symbols:   173
-  CStrings:  308
+  CStrings:  311
 
CStrings:
+ "Nov 10 2026 03:22:18"
+ "QOS BACKOFF @t=%u held=%p_%p relPhase=%u relIdle=%u relUnbind=%u relNoWork=%u relGPUIdle=%u holdTicks=%u avgHoldx100=%u holdSkipNoCtn=%u"
+ "QOS TABLE @t=%u demoted=%p_%p promoted=%p_%p"
+ "QOS TABLE @t=%u qid=%u pid=%u pri=%u role=%u pending=%u target=%u cur=%u demotes=%u halts=%u holds=%u heldnow=%u"
- "Oct 30 2026 01:11:42"
```
