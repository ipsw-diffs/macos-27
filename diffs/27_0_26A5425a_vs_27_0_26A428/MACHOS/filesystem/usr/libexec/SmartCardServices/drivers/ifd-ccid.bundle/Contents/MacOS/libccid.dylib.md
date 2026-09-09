## libccid.dylib

> `/usr/libexec/SmartCardServices/drivers/ifd-ccid.bundle/Contents/MacOS/libccid.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`

```diff

 55039.0.0.0.0
-  __TEXT.__text: 0x1b4b0
+  __TEXT.__text: 0x1b178
   __TEXT.__const: 0x827
   __TEXT.__cstring: 0x6c33
-  __TEXT.__unwind_info: 0x428
+  __TEXT.__unwind_info: 0x5e8
   __TEXT.__auth_stubs: 0x6c0
   __DATA_CONST.__const: 0x370
   __DATA_CONST.__got: 0x50
Functions:
~ _CCID_Receive : 1628 -> 1624
~ _CmdXfrBlock : 2096 -> 2072
~ _CmdXfrBlockTPDU_T0 : 424 -> 412
~ _FreeChannel : 136 -> 124
~ _IFDHPolling : 208 -> 196
~ _T0_card_timeout : 160 -> 156
~ _IFDHPowerICC : 808 -> 800
~ _SYS_InitRandom : 84 -> 72
~ _get_data_rates : 672 -> 668
~ _InterruptStop : 348 -> 336
~ _yy_delete_buffer : 112 -> 100
~ _yy_scan_string : 60 -> 48
~ _bundleRelease : 184 -> 172
~ _list_destroy : 116 -> 104
~ _list_drop_elem : 200 -> 188
~ _list_delete : 80 -> 68
~ _list_delete_range : 588 -> 576
~ _discovered_devs_free : 100 -> 88
~ _usbi_connect_device : 172 -> 160
~ _usbi_disconnect_device : 184 -> 172
~ _libusb_free_device_list : 92 -> 80
~ _libusb_unref_device : 228 -> 216
~ _libusb_get_port_numbers : 152 -> 156
~ _libusb_close : 332 -> 308
~ _do_close : 464 -> 452
~ _libusb_set_configuration : 144 -> 132
~ _libusb_set_interface_alt_setting : 268 -> 256
~ _libusb_clear_halt : 144 -> 132
~ _libusb_reset_device : 132 -> 120
~ _libusb_alloc_streams : 204 -> 192
~ _libusb_free_streams : 192 -> 180
~ _libusb_kernel_driver_active : 172 -> 160
~ _libusb_detach_kernel_driver : 172 -> 160
~ _libusb_attach_kernel_driver : 172 -> 160
~ _libusb_set_debug : 52 -> 44
~ _get_env_debug_level : 56 -> 48
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _OUTLINED_FUNCTION_1 : 44 -> 32
~ _OUTLINED_FUNCTION_2 : 44 -> 32
~ _OUTLINED_FUNCTION_3 : 44 -> 32
~ _OUTLINED_FUNCTION_4 : 44 -> 32
~ _OUTLINED_FUNCTION_5 : 44 -> 32
~ _OUTLINED_FUNCTION_6 : 44 -> 32
~ _raw_desc_to_config : 2176 -> 2132
~ _libusb_free_config_descriptor : 64 -> 52
~ _clear_configuration : 108 -> 96
~ _libusb_free_bos_descriptor : 108 -> 96
~ _usbi_hotplug_notification : 224 -> 212
~ _usbi_io_exit : 176 -> 164
~ _usbi_remove_event_source : 316 -> 304
~ _libusb_free_transfer : 188 -> 176
~ _OUTLINED_FUNCTION_5 : 44 -> 32
~ _OUTLINED_FUNCTION_6 : 44 -> 32
~ _OUTLINED_FUNCTION_7 : 44 -> 32
~ _darwin_exit : 244 -> 232
~ _darwin_open : 392 -> 380
~ _darwin_close : 316 -> 304
~ _darwin_get_config_descriptor : 160 -> 156
~ _darwin_set_configuration : 232 -> 220
~ _darwin_claim_interface : 1120 -> 1108
~ _darwin_release_interface : 296 -> 284
~ _darwin_set_interface_altsetting : 208 -> 196
~ _darwin_clear_halt : 220 -> 208
~ _darwin_alloc_streams : 288 -> 284
~ _darwin_kernel_driver_active : 220 -> 208
~ _darwin_submit_transfer : 1912 -> 1900
~ _darwin_cancel_transfer : 472 -> 460
~ _darwin_handle_transfer_completion : 396 -> 388
~ _darwin_deref_cached_device : 108 -> 96
~ _darwin_async_io_callback : 200 -> 188
```
