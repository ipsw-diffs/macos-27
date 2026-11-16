## agx_b000

> `Firmware/agx/armfw_g18g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c964
-  __TEXT.__gxf_code: 0x4f60
+  __TEXT.__text: 0x3e0d0
+  __TEXT.__gxf_code: 0x4f90
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x2118
+  __TEXT.__const: 0x2128
   __TEXT._rtk_patchbay: 0x23a
   __TEXT._rtk_tunables: 0x7e0
-  __TEXT.__cstring: 0x24c7
+  __TEXT.__cstring: 0x25ee
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x20
   __DATA.__gxf_data: 0x80b8
-  __DATA.__data: 0x189c8
+  __DATA.__data: 0x18a08
   __DATA._rtk_init_stack: 0x4000
   __DATA.__const: 0x7c0
   __DATA._rtk_irq_stack: 0x4000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x57c38
+  __DATA.__zerofill: 0x58c98
   __DATA_SHARED_RO._RTK_EXT_SHD_DTA: 0x8000
-  Functions: 404
+  Functions: 406
   Symbols:   169
-  CStrings:  238
+  CStrings:  241
 
CStrings:
+ "Nov 10 2026 03:32:14"
+ "QOS BACKOFF @t=%u held=%p_%p relPhase=%u relIdle=%u relUnbind=%u relNoWork=%u relGPUIdle=%u holdTicks=%u avgHoldx100=%u holdSkipNoCtn=%u"
+ "QOS TABLE @t=%u demoted=%p_%p promoted=%p_%p"
+ "QOS TABLE @t=%u qid=%u pid=%u pri=%u role=%u pending=%u target=%u cur=%u demotes=%u halts=%u holds=%u heldnow=%u"
- "Oct 30 2026 01:22:05"
```
