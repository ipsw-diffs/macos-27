## com.apple.DriverKit-AppleEthernetIXGBE

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetIXGBE.dext/com.apple.DriverKit-AppleEthernetIXGBE`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 171.0.0.0.0
-  __TEXT.__text: 0x2df44
+  __TEXT.__text: 0x2dd20
   __TEXT.__auth_stubs: 0x580
   __TEXT.__const: 0xd38
   __TEXT.__cstring: 0x4871
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetIXGBE.build/Objects-normal/arm64e/DriverKit_AppleEthernetIXGBE-93e23d1c018d79edeec20f986c1e5b5c.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetIXGBE.build/Objects-normal/arm64e/DriverKit_AppleEthernetIXGBE-ee1129426f0de3bb6a00027eb6899446.o
Functions:
~ __ZN28DriverKit_AppleEthernetIXGBE4freeEv : 72 -> 60
~ ____ZN28DriverKit_AppleEthernetIXGBE9Stop_ImplEP9IOService_block_invoke : 280 -> 268
~ __ZN28DriverKit_AppleEthernetIXGBE13TxSubmit_ImplEP8OSAction : 48 -> 36
~ __ZN28DriverKit_AppleEthernetIXGBE13RxSubmit_ImplEP8OSAction : 116 -> 104
~ __ZN28DriverKit_AppleEthernetIXGBE11SetMTU_ImplEj : 100 -> 88
~ _OUTLINED_FUNCTION_9 : 28 -> 16
~ __Z26ixgbe_dmac_config_tcs_X550P8ixgbe_hw : 344 -> 340
~ __Z33ixgbe_update_eeprom_checksum_X550P8ixgbe_hw : 264 -> 252
~ __ZL25ixgbe_identify_phy_x550emP8ixgbe_hw : 1352 -> 1328
~ __ZL29ixgbe_release_swfw_sync_X550aP8ixgbe_hwj : 172 -> 160
~ __Z30ixgbe_release_swfw_sync_X550emP8ixgbe_hwj : 136 -> 124
~ __Z31ixgbe_setup_mac_link_sfp_x550emP8ixgbe_hwjb : 168 -> 156
~ __Z29ixgbe_setup_mac_link_t_X550emP8ixgbe_hwjb : 216 -> 204
~ __Z21ixgbe_setup_kr_x550emP8ixgbe_hw : 88 -> 76
~ __Z33ixgbe_setup_internal_phy_t_x550emP8ixgbe_hw : 292 -> 280
~ __Z30ixgbe_handle_lasi_ext_t_x550emP8ixgbe_hw : 104 -> 92
~ __ZL18ixgbe_reset_phy_fwP8ixgbe_hw : 144 -> 132
~ __Z15ixgbe_reset_phyP8ixgbe_hw : 120 -> 108
~ __Z18ixgbe_read_phy_regP8ixgbe_hwjjPt : 152 -> 140
~ __Z19ixgbe_write_phy_regP8ixgbe_hwjjt : 152 -> 140
~ __ZL22ixgbe_out_i2c_byte_ackP8ixgbe_hwh : 72 -> 60
~ __Z38ixgbe_get_phy_firmware_version_genericP8ixgbe_hwPt : 132 -> 120
~ __Z29ixgbe_read_i2c_eeprom_genericP8ixgbe_hwhPh : 144 -> 132
~ __Z30ixgbe_write_i2c_eeprom_genericP8ixgbe_hwhh : 144 -> 132
~ __Z29ixgbe_identify_module_genericP8ixgbe_hw : 204 -> 180
~ __Z34ixgbe_get_phy_firmware_version_tnxP8ixgbe_hwPt : 132 -> 120
~ __ZNK34DriverKit_AppleEthernetIXGBE_IVars16queueIntrHandlerEv : 152 -> 140
~ _OUTLINED_FUNCTION_4 : 28 -> 16
~ __Z28ixgbe_update_mc_addr_list_vfP8ixgbe_hwPhjPFS1_S0_PS1_PjEb : 420 -> 412
~ __Z19ixgbe_start_hw_X540P8ixgbe_hw : 136 -> 124
~ __Z25ixgbe_init_swfw_sync_X540P8ixgbe_hw : 80 -> 68
~ __Z25ixgbe_setup_mac_link_X540P8ixgbe_hwjb : 140 -> 128
~ __ZNK34DriverKit_AppleEthernetIXGBE_IVars12enableQueuesEy : 180 -> 168
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars10configLinkEv : 332 -> 320
~ __ZN34DriverKit_AppleEthernetIXGBE_IVars7disableEv : 144 -> 132
~ _OUTLINED_FUNCTION_5 : 36 -> 24
~ _OUTLINED_FUNCTION_15 : 28 -> 16
~ __Z34ixgbe_read_eeprom_bit_bang_genericP8ixgbe_hwtPt : 188 -> 176
~ __Z41ixgbe_read_eeprom_buffer_bit_bang_genericP8ixgbe_hwttPt : 232 -> 236
~ __Z42ixgbe_write_eeprom_buffer_bit_bang_genericP8ixgbe_hwttPt : 464 -> 468
~ __ZL23ixgbe_read_eeprom_82599P8ixgbe_hwtPt : 200 -> 176
~ __ZL30ixgbe_read_eeprom_buffer_82599P8ixgbe_hwttPt : 220 -> 196
~ __Z35ixgbe_fdir_add_perfect_filter_82599P8ixgbe_hwP15ixgbe_atr_inputS2_thb : 452 -> 440
~ __Z30ixgbe_dcb_calculate_tc_creditsPhPtS0_i : 156 -> 148
~ __Z34ixgbe_dcb_calculate_tc_credits_ceeP8ixgbe_hwP16ixgbe_dcb_configjh : 320 -> 316
~ __Z26ixgbe_dcb_check_config_ceeP16ixgbe_dcb_config : 352 -> 360
~ __Z24ixgbe_dcb_config_pfc_ceeP8ixgbe_hwP16ixgbe_dcb_config : 296 -> 284
~ __ZL21ixgbe_read_posted_mbxP8ixgbe_hwPjtt : 332 -> 320
```
