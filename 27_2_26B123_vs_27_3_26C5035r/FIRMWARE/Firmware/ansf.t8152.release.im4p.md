## ansf.t8152.release.im4p

> `Firmware/ansf.t8152.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x45a0
-  __TEXT.__text: 0x210f2c
-  __TEXT.shared: 0xee40
+  __TEXT.__text: 0x2136a0
+  __TEXT.shared: 0xf3fc
   __TEXT.read: 0x7214
-  __TEXT.__const: 0x63e0
-  __TEXT.__cstring: 0x277dc
+  __TEXT.__const: 0x64f0
+  __TEXT.__cstring: 0x27877
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x1c
   __DATA._rtk_boot: 0x4000

   __DATA._rtk_patchbay: 0x4b9
   __DATA._rtk_tunables: 0xa10
   __DATA._rtk_mtab: 0x330
-  __DATA.__data: 0x8530
+  __DATA.__data: 0x8528
   __DATA.__const: 0x1cc8
   __DATA.__gxf_data: 0x10
-  __DATA.core_globals: 0x17b
+  __DATA.core_globals: 0x17c
   __DATA._rtk_init_stack: 0x1000
   __DATA._rtk_irq_stack: 0x1000
   __DATA._rtk_exc_stack: 0x1000

   __DATA._rtk_heap: 0x0
   __DATA._rtk_threads: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x3f34c8
-  Functions: 2170
+  __DATA.__zerofill: 0x3f46e8
+  Functions: 2176
   Symbols:   0
-  CStrings:  4258
+  CStrings:  4261
 
CStrings:
+ "3975.60.4"
+ "3975.60.4~272"
+ "AppleStorageFirmware-3975.60.4~272"
+ "HotPages BootInit: status=%d needBytes=%u KB init=%d"
+ "HotPages: reserve %u KB out of %lld KB leftover"
+ "HotPages: reserve SKIPPED (need %u KB, leftover %lld KB)"
- "3975.40.15"
- "3975.40.15~298"
- "AppleStorageFirmware-3975.40.15~298"
```
