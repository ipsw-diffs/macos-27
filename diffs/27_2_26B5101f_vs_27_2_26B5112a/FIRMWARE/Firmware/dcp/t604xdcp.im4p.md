## t604xdcp.im4p

> `Firmware/dcp/t604xdcp.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__chain_starts`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._afk_sys_objt`
- `__DATA._rtk_data_uuid`

```diff

-  __TEXT.__text: 0x30bd6c
+  __TEXT.__text: 0x30c388
   __TEXT.__const: 0x3b3c10
   __TEXT.__chain_starts: 0x34
-  __TEXT.__cstring: 0x3a2a6
+  __TEXT.__cstring: 0x3a557
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
   __DATA.__const: 0x3b128

   __DATA._rtk_mtab: 0x5a0
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x242ec
-  Functions: 7442
+  __OS_LOG.__string: 0x24356
+  Functions: 7444
   Symbols:   0
-  CStrings:  9041
+  CStrings:  9052
 
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
