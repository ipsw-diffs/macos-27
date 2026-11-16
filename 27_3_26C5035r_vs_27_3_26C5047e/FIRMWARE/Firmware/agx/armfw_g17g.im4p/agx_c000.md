## agx_c000

> `Firmware/agx/armfw_g17g.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d54c
-  __TEXT.__gxf_code: 0x5130
+  __TEXT.__text: 0x3ecec
+  __TEXT.__gxf_code: 0x5160
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x10bc
+  __TEXT.__const: 0x10cc
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
-  __TEXT.__cstring: 0x2470
+  __TEXT.__cstring: 0x2597
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8160
-  __DATA.__data: 0x17d40
+  __DATA.__data: 0x17d80
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x7c8
   __DATA._rtk_irq_stack: 0x4000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x5a778
+  __DATA.__zerofill: 0x5b7b8
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
-  Functions: 416
+  Functions: 418
   Symbols:   173
-  CStrings:  239
+  CStrings:  242
 
CStrings:
+ "Nov 10 2026 03:36:03"
+ "QOS BACKOFF @t=%u held=%p_%p relPhase=%u relIdle=%u relUnbind=%u relNoWork=%u relGPUIdle=%u holdTicks=%u avgHoldx100=%u holdSkipNoCtn=%u"
+ "QOS TABLE @t=%u demoted=%p_%p promoted=%p_%p"
+ "QOS TABLE @t=%u qid=%u pid=%u pri=%u role=%u pending=%u target=%u cur=%u demotes=%u halts=%u holds=%u heldnow=%u"
- "Oct 30 2026 01:26:22"
```
