## agx_a000

> `Firmware/agx/armfw_g17x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d1a4
-  __TEXT.__gxf_code: 0x50a0
+  __TEXT.__text: 0x3e94c
+  __TEXT.__gxf_code: 0x50d0
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x120c
+  __TEXT.__const: 0x121c
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
-  __TEXT.__cstring: 0x2249
+  __TEXT.__cstring: 0x2370
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8130
-  __DATA.__data: 0x17da0
+  __DATA.__data: 0x17de0
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x7d8
   __DATA._rtk_irq_stack: 0x4000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x58118
+  __DATA.__zerofill: 0x59158
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
-  Functions: 415
+  Functions: 417
   Symbols:   175
-  CStrings:  232
+  CStrings:  235
 
CStrings:
+ "Nov 10 2026 03:32:23"
+ "QOS BACKOFF @t=%u held=%p_%p relPhase=%u relIdle=%u relUnbind=%u relNoWork=%u relGPUIdle=%u holdTicks=%u avgHoldx100=%u holdSkipNoCtn=%u"
+ "QOS TABLE @t=%u demoted=%p_%p promoted=%p_%p"
+ "QOS TABLE @t=%u qid=%u pid=%u pri=%u role=%u pending=%u target=%u cur=%u demotes=%u halts=%u holds=%u heldnow=%u"
- "Oct 30 2026 01:22:15"
```
