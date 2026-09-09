## com.apple.DriverKit-AppleEthernetE1000

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetE1000.dext/com.apple.DriverKit-AppleEthernetE1000`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 171.0.0.0.0
-  __TEXT.__text: 0x30a70
+  __TEXT.__text: 0x30814
   __TEXT.__auth_stubs: 0x4f0
   __TEXT.__const: 0xb78
   __TEXT.__cstring: 0x1c71
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetE1000.build/Objects-normal/arm64e/DriverKit_AppleEthernetE1000-4f3fe0d53204cf7a7eb5cd9b7a7e8a8f.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/ApplePCINetworking_driverkit/install/TempContent/Objects/ApplePCINetworking.build/AppleEthernetE1000.build/Objects-normal/arm64e/DriverKit_AppleEthernetE1000-1e8d3c7db0c9b94d0047e653311c98a1.o
Functions:
~ __Z27e1000_init_nvm_params_82575P8e1000_hw : 504 -> 496
~ __ZL23e1000_release_nvm_82575P8e1000_hw : 60 -> 48
~ __Z18e1000_read_emi_regP8e1000_hwtPt : 108 -> 96
~ __ZL26e1000_check_for_link_82575P8e1000_hw : 136 -> 112
~ __ZL25e1000_read_mac_addr_82575P8e1000_hw : 72 -> 60
~ __ZL28e1000_get_link_up_info_82575P8e1000_hwPtS1_ : 56 -> 44
~ __ZL30e1000_phy_hw_reset_sgmii_82575P8e1000_hw : 136 -> 124
~ __Z24e1000_read_nvm_srrd_i210P8e1000_hwttPt : 184 -> 188
~ __Z25e1000_write_nvm_srwr_i210P8e1000_hwttPt : 200 -> 204
~ __ZN34DriverKit_AppleEthernetE1000_IVars22getSupportedMediaArrayEPjS0_ : 164 -> 160
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ __Z18e1000_read_pba_rawP8e1000_hwPtjtP9e1000_pba : 276 -> 280
~ __Z32e1000_power_down_phy_copper_baseP8e1000_hw : 100 -> 88
~ __ZL22e1000_write_vfta_82543P8e1000_hwjj : 1200 -> 1188
~ __ZL34e1000_phy_force_speed_duplex_82543P8e1000_hw : 96 -> 84
~ __Z14e1000_read_mbxP8e1000_hwPjtt : 36 -> 32
~ __Z21e1000_read_posted_mbxP8e1000_hwPjtt : 196 -> 184
~ __Z27e1000_phy_reset_dsp_genericP8e1000_hw : 112 -> 100
~ __Z31e1000_setup_copper_link_genericP8e1000_hw : 184 -> 172
~ __Z37e1000_enable_phy_wakeup_reg_access_bmP8e1000_hwPt : 164 -> 152
~ __Z38e1000_disable_phy_wakeup_reg_access_bmP8e1000_hwPt : 108 -> 96
~ __Z22e1000_read_phy_reg_gpyP8e1000_hwjPt : 164 -> 152
~ __ZL24__e1000_access_xmdio_regP8e1000_hwthPtb : 256 -> 244
~ __ZL30e1000_access_phy_debug_regs_hvP8e1000_hwjPtb : 184 -> 160
~ __Z25e1000_read_emi_reg_lockedP8e1000_hwtPt : 108 -> 96
~ __Z26e1000_write_emi_reg_lockedP8e1000_hwtt : 108 -> 96
~ __ZL24e1000_setup_link_ich8lanP8e1000_hw : 220 -> 208
~ __ZL25e1000_cleanup_led_ich8lanP8e1000_hw : 96 -> 84
~ __ZL20e1000_led_on_ich8lanP8e1000_hw : 96 -> 84
~ __ZL21e1000_led_off_ich8lanP8e1000_hw : 96 -> 84
~ __ZL39e1000_phy_timing_recovery_workaround_lvP8e1000_hw : 748 -> 736
~ __ZL35e1000_power_down_phy_copper_ich8lanP8e1000_hw : 100 -> 88
~ __ZL31e1000_read_mac_addr_80003es2lanP8e1000_hw : 72 -> 60
~ __ZL34e1000_get_link_up_info_80003es2lanP8e1000_hwPtS1_ : 108 -> 96
~ __ZL29e1000_release_nvm_80003es2lanP8e1000_hw : 60 -> 48
~ __ZL39e1000_power_down_phy_copper_80003es2lanP8e1000_hw : 100 -> 88
~ _OUTLINED_FUNCTION_12 : 32 -> 20
~ _OUTLINED_FUNCTION_14 : 36 -> 24
~ __ZN28DriverKit_AppleEthernetE10004freeEv : 72 -> 60
~ ____ZN28DriverKit_AppleEthernetE10009Stop_ImplEP9IOService_block_invoke : 256 -> 244
~ __ZN28DriverKit_AppleEthernetE100013TxSubmit_ImplEP8OSAction : 56 -> 44
~ __ZN28DriverKit_AppleEthernetE100013RxSubmit_ImplEP8OSAction : 148 -> 136
~ __Z22e1000_setup_init_funcsP8e1000_hwb : 380 -> 368
~ __Z18e1000_power_up_phyP8e1000_hw : 96 -> 84
~ __Z24e1000_read_nvm_srrd_i225P8e1000_hwttPt : 184 -> 188
~ __Z25e1000_write_nvm_srwr_i225P8e1000_hwttPt : 200 -> 204
~ __ZL26e1000_init_nvm_params_i225P8e1000_hw : 412 -> 404
~ __ZN34DriverKit_AppleEthernetE1000_IVars7disableEv : 152 -> 140
~ _OUTLINED_FUNCTION_6 : 28 -> 16
~ __ZNK34DriverKit_AppleEthernetE1000_IVars16queueIntrHandlerEv : 188 -> 176
~ __ZL22e1000_setup_link_82542P8e1000_hw : 292 -> 280
~ __ZL35e1000_setup_fiber_serdes_link_82571P8e1000_hw : 92 -> 80
~ __ZL25e1000_read_mac_addr_82571P8e1000_hw : 88 -> 76
~ __ZL23e1000_release_nvm_82571P8e1000_hw : 56 -> 44
~ __ZL21e1000_write_nvm_82571P8e1000_hwttPt : 256 -> 244
~ __ZL33e1000_power_down_phy_copper_82571P8e1000_hw : 108 -> 96
~ __ZL29e1000_set_d3_lplu_state_82541P8e1000_hwb : 380 -> 368
```
