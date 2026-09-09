## AppleODClientPWS

> `/System/Library/OpenDirectory/Modules/AppleODClientPWS.bundle/Contents/MacOS/AppleODClientPWS`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 164.0.0.0.0
-  __TEXT.__text: 0x12e14
+  __TEXT.__text: 0x12c7c
   __TEXT.__auth_stubs: 0xda0
   __TEXT.__const: 0x2a0
   __TEXT.__cstring: 0x3ba6
-  __TEXT.__unwind_info: 0x328
+  __TEXT.__unwind_info: 0x408
   __DATA_CONST.__const: 0xf08
   __DATA_CONST.__cfstring: 0x2240
   __DATA_CONST.__auth_got: 0x6d0
Functions:
~ _pws_conn_set_cast_key : 428 -> 420
~ ___pws_conn_set_auth_context_block_invoke : 76 -> 64
~ ___pws_conn_send_cmd_read_resp_block_invoke : 1988 -> 1996
~ _pws_conn_get_odconnection : 532 -> 520
~ __pws_disconnect_cb : 108 -> 96
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ _pws_modcfg_init : 284 -> 272
~ _odm_copy_auth_information : 260 -> 248
~ _odm_create_connection_with_options : 160 -> 148
~ ___copy_helper_block_8_32r40r48r56r : 112 -> 100
~ ___destroy_helper_block_8_32r40r48r56r : 92 -> 80
~ ___copy_helper_block_8_32r40r48r56r64r72r80r88r96r : 192 -> 180
~ ___destroy_helper_block_8_32r40r48r56r64r72r80r88r96r : 152 -> 140
~ ___copy_helper_block_8_32b40r48r56r64r72r80r : 160 -> 148
~ ___destroy_helper_block_8_32b40r48r56r64r72r80r : 128 -> 116
~ __pws_sasl_hash_from_cfstr_or_cfdata : 348 -> 336
~ ___copy_helper_block_8_32r40r48r56r64r72r : 144 -> 132
~ ___destroy_helper_block_8_32r40r48r56r64r72r : 116 -> 104
~ ___pws_change_password_block_invoke.196 : 100 -> 88
~ ___pws_change_password_block_invoke.200 : 100 -> 88
~ ____pws_update_record_auth_data_block_invoke : 112 -> 100
~ ____pws_update_record_auth_data_block_invoke_2 : 112 -> 100
~ __pws_sasl_ctx_dealloc : 156 -> 144
~ _pws_sasl_auth_with_credentials : 536 -> 524
~ _aodc_unicode_array_from_cfstr : 144 -> 132
~ _aodc_error_create_with_args : 272 -> 260
~ _aodc_error_create : 96 -> 84
~ _aodc_create_string_from_error : 308 -> 296
~ _aodc_log_cfdict_contents : 456 -> 444
~ _aodc_create_url_with_destination : 476 -> 464
~ ___aodc_copy_services_from_localhost_block_invoke : 100 -> 88
~ ___pws_auth_ctx_release_block_invoke : 144 -> 132
~ ___pws_auth_ctx_set_connection_block_invoke : 68 -> 56
```
