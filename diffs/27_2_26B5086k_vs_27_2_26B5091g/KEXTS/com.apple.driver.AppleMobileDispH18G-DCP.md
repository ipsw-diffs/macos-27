## com.apple.driver.AppleMobileDispH18G-DCP

> `com.apple.driver.AppleMobileDispH18G-DCP`

```diff

-700.50.103.0.0
+700.50.104.0.0
   __TEXT.__const: 0x1920
-  __TEXT.__cstring: 0x73d9
-  __TEXT_EXEC.__text: 0x27194
+  __TEXT.__cstring: 0x7377
+  __TEXT_EXEC.__text: 0x271a4
   __TEXT_EXEC.__auth_stubs: 0xe40
   __DATA.__data: 0x393b8
   __DATA.__common: 0x120
   __DATA.__bss: 0x16d
   __DATA_CONST.__mod_init_func: 0x18
   __DATA_CONST.__mod_term_func: 0x18
-  __DATA_CONST.__const: 0x60c8
+  __DATA_CONST.__const: 0x60e0
   __DATA_CONST.__kalloc_type: 0x6c0
   __DATA_CONST.__kalloc_var: 0xf0
   __DATA_CONST.__auth_got: 0x720
   __DATA_CONST.__got: 0xd0
-  Functions: 1491
-  Symbols:   1918
+  Functions: 1495
+  Symbols:   1920
   CStrings:  599
 
Symbols:
+ __ZN16UnifiedPipeline217is_mode_set_dirtyEv
+ __ZNK5IOMFB15UPPipeInterface28get_ext_disp_hw_lead_time_usEv
Functions:
+ __ZN5IOMFB15UPPipeInterface28skip_abg_program_black_frameEv
+ __ZN16UnifiedPipeline217is_mode_set_dirtyEv
+ __ZNK5IOMFB15UPPipeInterface22replay_uses_pdc_bufferEv
~ __ZN23IOMobileFramebufferShim20set_digital_out_modeEjj : 7428 -> 7324
+ __ZNK5IOMFB15UPPipeInterface22replay_uses_pdc_bufferEv
CStrings:
+ "%s: Skipping redundant modeset (timing=%u, color=%u)\n"
+ "Skipping redundant modeset (timing=%u, color=%u)\n"
- "%s: AED: Skipping spurious modeset (timing=%u, color=%u, is_dual=%d unchanged, intent toggled %d->%d)\n"
- "AED: Skipping spurious modeset (timing=%u, color=%u, is_dual=%d unchanged, intent toggled %d->%d)\n"
```
