## agx_a000

> `Firmware/agx/armfw_g17p.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c16c
-  __TEXT.__gxf_code: 0x5150
+  __TEXT.__text: 0x3d91c
+  __TEXT.__gxf_code: 0x5180
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1d44
   __TEXT._rtk_patchbay: 0x231
   __TEXT._rtk_tunables: 0x6a0
-  __TEXT.__cstring: 0x234d
+  __TEXT.__cstring: 0x2474
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x24
   __DATA.__gxf_data: 0x8168
-  __DATA.__data: 0x17c98
+  __DATA.__data: 0x17cd8
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x830
   __DATA._rtk_irq_stack: 0x4000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x5b1d8
+  __DATA.__zerofill: 0x5c218
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
-  Functions: 434
+  Functions: 436
   Symbols:   191
-  CStrings:  236
+  CStrings:  239
 
CStrings:
+ "Nov 10 2026 03:21:50"
+ "QOS BACKOFF @t=%u held=%p_%p relPhase=%u relIdle=%u relUnbind=%u relNoWork=%u relGPUIdle=%u holdTicks=%u avgHoldx100=%u holdSkipNoCtn=%u"
+ "QOS TABLE @t=%u demoted=%p_%p promoted=%p_%p"
+ "QOS TABLE @t=%u qid=%u pid=%u pri=%u role=%u pending=%u target=%u cur=%u demotes=%u halts=%u holds=%u heldnow=%u"
- "Oct 30 2026 01:11:13"
```
