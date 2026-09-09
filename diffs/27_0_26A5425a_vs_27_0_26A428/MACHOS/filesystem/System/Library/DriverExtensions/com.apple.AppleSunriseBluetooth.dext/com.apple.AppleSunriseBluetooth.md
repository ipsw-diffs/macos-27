## com.apple.AppleSunriseBluetooth

> `/System/Library/DriverExtensions/com.apple.AppleSunriseBluetooth.dext/com.apple.AppleSunriseBluetooth`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

 112.0.0.0.0
-  __TEXT.__text: 0x2ef68
-  __TEXT.__auth_stubs: 0x920
+  __TEXT.__text: 0x2e9e8
+  __TEXT.__auth_stubs: 0x930
   __TEXT.__cstring: 0xb3e9
   __TEXT.__const: 0x15b0
-  __TEXT.__unwind_info: 0x870
+  __TEXT.__unwind_info: 0xd68
   __TEXT.__oslogstring: 0x251d
   __DATA_CONST.__const: 0x15f8
   __DATA_CONST.__osclassinfo: 0x60
-  __DATA_CONST.__auth_got: 0x490
+  __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x78
   __DATA.__data: 0x1bcfd
   __DATA.__bss: 0xb2e0

   - /System/DriverKit/System/Library/PrivateFrameworks/CoreCaptureDriverKit.framework/CoreCaptureDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
   Functions: 941
-  Symbols:   1191
+  Symbols:   1192
   CStrings:  1659
 
Symbols:
+ _PE_i_can_has_debugger
Functions:
~ __ZN26AppleSunriseFirmwareLoader4freeEv : 72 -> 60
~ _kalMemFreeHW : 392 -> 380
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ __ZL18kalMemTrackerAllocPKc : 92 -> 80
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ __ZN30AppleSunriseBluetoothIPCClient4freeEv : 184 -> 172
~ __ZN30AppleSunriseBluetoothIPCClient14ExternalMethodEyP27IOUserClientMethodArgumentsPK26IOUserClientMethodDispatchP8OSObjectPv : 184 -> 172
~ __ZN30AppleSunriseBluetoothIPCClient26ReadCompletionNotificationEPhm : 1828 -> 1812
~ _OUTLINED_FUNCTION_3 : 48 -> 36
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ _rx_list_initialize : 120 -> 108
~ _rx_list_append : 120 -> 108
~ _rx_list_destory : 192 -> 180
~ _OUTLINED_FUNCTION_3 : 32 -> 20
~ _btmtk_recv_error_handler_common : 124 -> 112
~ _btmtk_cif_rx_packet_handler_common : 108 -> 96
~ __ZN21AppleSunriseBluetooth22reportCurrentDextStageEi : 268 -> 256
~ ____ZN21AppleSunriseBluetooth9Stop_ImplEP9IOService_block_invoke : 64 -> 52
~ ____ZN21AppleSunriseBluetooth18SetPowerState_ImplEj_block_invoke : 84 -> 72
~ __ZN21AppleSunriseBluetooth12clientHalFLREv : 608 -> 596
~ __ZN21AppleSunriseBluetooth17clientHalSoCResetEv : 640 -> 628
~ __ZN21AppleSunriseBluetooth22setFunctionCrashActionE34AppleSunriseHALFunctionCrashAction : 268 -> 256
~ _OUTLINED_FUNCTION_4 : 28 -> 16
~ _OUTLINED_FUNCTION_11 : 24 -> 12
~ _OUTLINED_FUNCTION_12 : 24 -> 12
~ _pci_restore_state : 92 -> 80
~ _pci_reset_function : 148 -> 136
~ _pci_resource_free : 128 -> 116
~ _pci_free_consistent : 92 -> 80
~ _OUTLINED_FUNCTION_1 : 36 -> 24
~ ___wait_event_interruptible : 260 -> 248
~ ___wait_event_interruptible_timeout : 284 -> 272
~ ___wake_up_interruptible : 200 -> 188
~ ___wake_up_all : 204 -> 192
~ _kfree_skb : 76 -> 64
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ __ZN23AppleSunriseTimerAction4freeEv : 128 -> 116
~ _btmtk_pci_ipc_sleep_state_machine : 1016 -> 1004
~ _btmtk_pcie_coredump_trigger : 560 -> 548
~ _btmtk_pci_dirver_apply_tx : 992 -> 996
~ _PCIe_HOST_Packet_RX_Handler : 1168 -> 1148
~ _btmtk_pcie_reg_write_halt : 96 -> 84
~ _btmtk_check_d3_conninfra_before_flr : 148 -> 136
~ _btmtk_pcie_doorbell_moderation : 340 -> 328
~ _btmtk_pci_ring_db : 472 -> 460
~ _btmtk_pci_set_sleep_state : 248 -> 236
~ _btmtk_pcie_check_fabric_11_12 : 3768 -> 3772
~ _btmtk_pcie_add_coredump_timer : 164 -> 152
~ _btmtk_pci_ipc_free_coredump_dma : 100 -> 88
~ _btmtk_pcie_driver_recv_coredump : 512 -> 500
~ _btmtk_pcie_del_coredump_timer : 136 -> 124
~ _btmtk_get_debug_SOP_data : 5168 -> 5160
~ _btmtk_pcie_dump_debug_sop : 84 -> 72
~ _btmtk_pcie_coredump_timer_cback : 224 -> 212
~ _btmtk_pci_ipc_free_image_addr_dma : 100 -> 88
~ _btmtk_pcie_add_patch_dl_timer : 168 -> 156
~ _btmtk_pci_set_ipc_control_state : 248 -> 236
~ _btmtk_pcie_chip_reset_notify : 88 -> 76
~ _btmtk_pcie_mtcmos_hw_mode_sol : 204 -> 192
~ _btmtk_pcie_del_patch_dl_timer : 136 -> 124
~ _btmtk_pcie_del_ipc_status_timer : 136 -> 124
~ _btmtk_pci_free_tx_cell_dma_buffer : 320 -> 304
~ _btmtk_pci_free_rx_cell_dma_buffer : 272 -> 268
~ _btmtk_reset_notify : 184 -> 160
~ _btmtk_pcie_handle_dma_hang : 84 -> 72
~ _btmtk_pcie_patch_dl_timer_cback : 108 -> 96
~ _btmtk_pci_trigger_L05 : 100 -> 88
~ _btmtk_pci_sys_restart_cb : 72 -> 60
~ _btmtk_pcie_ipc_status_timer_cback : 272 -> 260
~ _btmtk_pcie_add_ipc_status_timer : 164 -> 152
~ _btmtk_pci_ipc_state_machine : 796 -> 760
~ _btmtk_cif_disconnect : 1132 -> 1120
~ _tlsf_check : 328 -> 332
~ __ZL12block_insertP9control_tP14block_header_t : 188 -> 192
~ _tlsf_remove_pool : 152 -> 140
~ _tlsf_create : 376 -> 380
~ _tlsf_malloc : 108 -> 88
~ __ZL19adjust_request_sizemm : 76 -> 68
~ __ZL17block_locate_freeP9control_tm : 268 -> 264
~ _tlsf_memalign : 320 -> 296
~ _tlsf_free : 208 -> 196
~ _tlsf_realloc : 432 -> 408
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _btmtk_reset_timer_add : 112 -> 100
~ _btmtk_reset_timer : 92 -> 80
~ _btmtk_reset_timer_update : 72 -> 60
~ _btmtk_reset_trigger : 148 -> 136
~ __ZN27AppleSunriseInterruptAction4freeEv : 128 -> 116
~ _hci_ipc_close : 52 -> 40
~ _hci_ipc_handle_power_state : 356 -> 332
~ _add_timer : 96 -> 84
~ ___wake_up_process_block_invoke : 116 -> 104
~ __Z16get_current_taskv : 60 -> 48
~ _OUTLINED_FUNCTION_6 : 32 -> 20
~ ___free_irq_block_invoke : 76 -> 64
~ _enable_irq : 68 -> 56
~ __Z11disable_irqj : 68 -> 56
~ _disable_irq_nosync : 68 -> 56
~ _fw_log : 112 -> 100
~ _driver_log_raw_dump : 356 -> 348
~ _report_fault : 240 -> 228
~ _btmtk_exit_from_host_sleep : 168 -> 156
~ _btmtk_set_chip_state : 212 -> 200
~ _btmtk_load_all_register : 2572 -> 2544
~ _btmtk_print_bt_patch_info : 512 -> 500
~ _btmtk_free_dev_memory : 116 -> 104
~ _btmtk_hci_ipc_trigger_core_dump : 48 -> 36
~ _btmtk_initiate_fw_download : 176 -> 164
~ _btmtk_fops_set_state : 148 -> 136
~ _btmtk_main_cif_uninitialize : 136 -> 124
~ _main_exit : 248 -> 236
~ _main_driver_exit : 96 -> 84
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _OUTLINED_FUNCTION_5 : 28 -> 16
```
