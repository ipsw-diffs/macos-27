## ipad13dcp.im4p

> `Firmware/dcp/ipad13dcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x2eca98
+  __TEXT.__text: 0x2ed0dc
   __TEXT.__const: 0x3ca7e0
   __TEXT.__chain_starts: 0x2c
-  __TEXT.__cstring: 0x37f3b
+  __TEXT.__cstring: 0x381ec
   __TEXT.__padding1: 0x1
   __TEXT.__padding2: 0x1
   __TEXT.__lcxx_override: 0x24

   __DATA._rtk_mtab: 0x570
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x235d0
-  Functions: 7263
+  __OS_LOG.__string: 0x2363a
+  Functions: 7266
   Symbols:   0
-  CStrings:  8728
+  CStrings:  8739
 
CStrings:
+ " Dont load UPCL in Default Preset with Optimal Observer matrix present"
+ " UPCL not loaded as primary matrix . Saved to calcache"
+ "EAN mode info: accepted blob from iBoot, validMask 0x%llx"
+ "EAN mode info: blob rejected, size %u bytes, external pipe %d, nothing will be restored from EAN"
+ "EAN mode info: curve slot %u (ICC curve loc %u) is table type, discarding the whole blob so mode, preset and user adjustment are lost with it"
+ "EAN mode info: no saved blob, preset and ICC left at their defaults"
+ "EAN mode info: restoring reference preset as %s, validMask 0x%llx"
+ "[AFK]Failed to set initial vsyncRate, 0x%08x is not a supported timing"
+ "[AFK]Set initial vsync rate 0x%08x"
+ "initial vsync rate set to 0x%x (16.16 Hz) from saved EAN mode info"
+ "initial vsync rate: setInitialVSyncRate( 0x%x ) failed with 0x%x"
```
