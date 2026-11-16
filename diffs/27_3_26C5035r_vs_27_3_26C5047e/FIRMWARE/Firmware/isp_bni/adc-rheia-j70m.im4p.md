## adc-rheia-j70m.im4p

> `Firmware/isp_bni/adc-rheia-j70m.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._fwinfo`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x96acd0
+  __TEXT.__text: 0x96b988
   __TEXT.__const: 0x3146a0
-  __TEXT.__cstring: 0xf1a19
+  __TEXT.__cstring: 0xf1f4e
   __TEXT.text_env: 0x4f1a4
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x390c8
+  __DATA.__const: 0x390f0
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xd94d8
   __DATA._rtk_power: 0x3f8

   __DATA.__chain_starts: 0x24
   __DATA.__mod_init_func: 0x8
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0xd7fdf8
-  Functions: 8594
+  __DATA.__zerofill: 0xd7bdf8
+  Functions: 8593
   Symbols:   0
-  CStrings:  26432
+  CStrings:  26458
 
CStrings:
+ "20:26:43"
+ "CISP_CMD_APPLE_MULTI_CHS_COMBINED_AF_WINDOW_PARAM_SET: Invalid chBitMask 0x%x, chTot %zu\n"
+ "CISP_CMD_APPLE_MULTI_CHS_COMBINED_AF_WINDOW_PARAM_SET: Invalid totalNumAFParamWin %u, max allowed %d\n"
+ "CISP_CMD_CH_MULTICAM_AE_WINDOW_PARAM_SET: Invalid chId %u at %u, chTot %zu\n"
+ "CISP_CMD_CH_MULTICAM_CAMERA_CONTROL_ROI_SET: Invalid chId %u at %u, chTot %zu\n"
+ "CISP_CMD_CH_MULTICAM_COMBINED_AF_WINDOW_PARAM_SET: Invalid chId %u numWin %u at %u, chTot %zu\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves %u exceeds MAX_CH_PER_SYNCGROUP %d, rejecting\n"
+ "Quark isn't ready for start %llu, %u, pending %u, waited %llu us, serviced %u"
+ "Quark ready after %llu us (serviced %u projector cmds)"
+ "StatsMasterSet: chId %d out of range (0..%d)"
+ "[%lu]: VIO LACC-match config alloc failed (%u)"
+ "[%lu]: VIO action config alloc failed (%u)"
+ "[%lu]: VIO config channel out of range"
+ "[%lu]: VIO operation config alloc failed (%u)"
+ "[%s] CH = 0x%zx VIO config size %u inconsistent with insize %u, rejecting"
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
- "02:03:12"
- "NULL != pActionListHdr[pCmd->ch]"
- "NULL != pOpListHdr[pCmd->ch]"
- "Quark isn't ready for start %llu, %u"
- "Quark ready after %u * 2 ms"
- "bus < ISP_SPMI_CONTROLLER_TOT"
- "checking quark readiness... %llu %u"
- "laccMatchInputBuf[pCmd->ch].inputBuf != nullptr"
- "numElements <= STF_MAXTABLEENTRIES"
- "pCmd->ch < CVDDP_MAX_CH_NUMBER"
- "pParams->mode < CISP_CAMERA_CONFIG_MODE_TOTAL"
- "pSensorNoiseModel->mode < CISP_CAMERA_CONFIG_MODE_TOTAL"
```
