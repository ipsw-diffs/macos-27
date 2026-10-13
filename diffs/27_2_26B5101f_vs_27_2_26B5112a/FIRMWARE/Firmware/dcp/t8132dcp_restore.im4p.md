## t8132dcp_restore.im4p

> `Firmware/dcp/t8132dcp_restore.im4p`

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

-  __TEXT.__text: 0x383c38
+  __TEXT.__text: 0x384254
   __TEXT.__const: 0x47c718
   __TEXT.__chain_starts: 0x3c
-  __TEXT.__cstring: 0x3dac0
+  __TEXT.__cstring: 0x3dd71
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
   __DATA.__const: 0x5af90

   __DATA._rtk_mtab: 0x828
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x25655
-  Functions: 8159
+  __OS_LOG.__string: 0x256bf
+  Functions: 8161
   Symbols:   0
-  CStrings:  9560
+  CStrings:  9571
 
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
