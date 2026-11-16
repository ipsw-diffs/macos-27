## agx_a010

> `Firmware/agx/armfw_g17x.im4p/agx_a010`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3ce28
-  __TEXT.__gxf_code: 0x50a0
+  __TEXT.__text: 0x3e5d0
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
-  __DATA.__zerofill: 0x58018
+  __DATA.__zerofill: 0x59058
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
-  Functions: 414
+  Functions: 416
   Symbols:   175
-  CStrings:  232
+  CStrings:  235
 
CStrings:
+ "Nov 10 2026 03:23:31"
+ "QOS BACKOFF @t=%u held=%p_%p relPhase=%u relIdle=%u relUnbind=%u relNoWork=%u relGPUIdle=%u holdTicks=%u avgHoldx100=%u holdSkipNoCtn=%u"
+ "QOS TABLE @t=%u demoted=%p_%p promoted=%p_%p"
+ "QOS TABLE @t=%u qid=%u pid=%u pri=%u role=%u pending=%u target=%u cur=%u demotes=%u halts=%u holds=%u heldnow=%u"
- "Oct 30 2026 01:13:01"
```
