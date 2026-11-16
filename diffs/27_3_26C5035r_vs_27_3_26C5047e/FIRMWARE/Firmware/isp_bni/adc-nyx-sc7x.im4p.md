## adc-nyx-sc7x.im4p

> `Firmware/isp_bni/adc-nyx-sc7x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8f3758
+  __TEXT.__text: 0x8f4308
   __TEXT.__const: 0x24030c
   __TEXT.text_env: 0x8e0
-  __TEXT.__cstring: 0xe58e6
+  __TEXT.__cstring: 0xe5d52
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3b748
+  __DATA.__const: 0x3b770
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xd9040
   __DATA._rtk_power: 0x3b8

   __DATA.__zerofill: 0xe25af8
   Functions: 8337
   Symbols:   0
-  CStrings:  25355
+  CStrings:  25379
 
CStrings:
+ "20:26:48"
+ "CISP_CMD_APPLE_MULTI_CHS_COMBINED_AF_WINDOW_PARAM_SET: Invalid chBitMask 0x%x, chTot %zu\n"
+ "CISP_CMD_APPLE_MULTI_CHS_COMBINED_AF_WINDOW_PARAM_SET: Invalid totalNumAFParamWin %u, max allowed %d\n"
+ "CISP_CMD_CH_MULTICAM_AE_WINDOW_PARAM_SET: Invalid chId %u at %u, chTot %zu\n"
+ "CISP_CMD_CH_MULTICAM_CAMERA_CONTROL_ROI_SET: Invalid chId %u at %u, chTot %zu\n"
+ "CISP_CMD_CH_MULTICAM_COMBINED_AF_WINDOW_PARAM_SET: Invalid chId %u numWin %u at %u, chTot %zu\n"
+ "Quark isn't ready for start %llu, %u, pending %u, waited %llu us, serviced %u"
+ "Quark ready after %llu us (serviced %u projector cmds)"
+ "StatsMasterSet: chId %d out of range (0..%d)"
+ "[%s] CMD = %#04x [%s]: chId %u mode %d out of range\n"
+ "bvc8"
+ "byc8"
+ "ch %zu: DUAL_PRIME pool drain timeout (%zu/%zu)"
+ "ch %zu: DUAL_PRIME_STILL pool drain timeout (%zu/%zu)"
+ "ch %zu: SLAVE_SHARE pool drain timeout (%zu/%zu)"
+ "ch %zu: raw pool drain timeout (%zu/%zu)"
+ "ch %zu: still raw pool drain timeout (%zu/%zu)"
+ "chEntry->pool[FILTER_IC][CIC_POOL_RAW_1]"
+ "chEntry->pool[FILTER_IC][CIC_POOL_RAW_3]"
+ "checking quark readiness... %llu %u pending %u"
+ "craw"
+ "pAWBHistogramWeight->numEntries <= CISP_AWB_HISTOGRAM_MAX_WEIGHT_LUXNODES"
+ "pPostTintParamSet->numEntries <= CISP_AWB_MAX_POST_TINT_PARAM_MASK"
+ "pProjectionPoint->numPoints <= CISP_AWB_MAX_PROJECTION_POINTS"
+ "pWinSet->winID >= CISP_APPLE_AE_WIN_0"
+ "pXToCCTLut->numPoints <= CISP_AWB_MAX_HISTOGRAM_X_TO_CCT_LUT_ENTRIES"
+ "raw10"
+ "raw12"
+ "raw14"
+ "raw16"
+ "raw8"
+ "rgp0"
- "02:03:04"
- "Quark isn't ready for start %llu, %u"
- "Quark ready after %u * 2 ms"
- "bus < ISP_SPMI_CONTROLLER_TOT"
- "checking quark readiness... %llu %u"
- "numElements <= STF_MAXTABLEENTRIES"
- "pParams->mode < CISP_CAMERA_CONFIG_MODE_TOTAL"
- "pSensorNoiseModel->mode < CISP_CAMERA_CONFIG_MODE_TOTAL"
```
