## AppleODClientLDAP

> `/System/Library/OpenDirectory/Modules/AppleODClientLDAP.bundle/Contents/MacOS/AppleODClientLDAP`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 164.0.0.0.0
-  __TEXT.__text: 0x166c4
+  __TEXT.__text: 0x16454
   __TEXT.__auth_stubs: 0x1250
   __TEXT.__const: 0x68
   __TEXT.__cstring: 0x5db3
-  __TEXT.__unwind_info: 0x438
+  __TEXT.__unwind_info: 0x528
   __DATA_CONST.__const: 0x14f0
   __DATA_CONST.__cfstring: 0x3e20
   __DATA_CONST.__auth_got: 0x928
Functions:
~ ___ldap_publish_scep_entry_block_invoke : 208 -> 196
~ __ldap_add_certs_to_keychain_block_invoke.141 : 988 -> 976
~ ___copy_helper_block_8_32r40r : 80 -> 68
~ ___destroy_helper_block_8_32r40r : 68 -> 56
~ __ldap_cert_cfstring_compare : 144 -> 132
~ ____ldap_remove_certs_from_keychain_internal_block_invoke : 468 -> 456
~ _ldap_conn_close_connection : 124 -> 112
~ _ldap_odconn_is_encrypted : 40 -> 28
~ _ldap_odconn_is_ldapi : 40 -> 28
~ ___copy_helper_block_8_32b40r48r : 96 -> 84
~ ___destroy_helper_block_8_32b40r48r : 80 -> 68
~ ___copy_helper_block_8_32b40r : 80 -> 68
~ ___destroy_helper_block_8_32b40r : 68 -> 56
~ _ldap_odconn_copy_url : 48 -> 36
~ ____ldap_conn_ctx_update_with_rootDSE_block_invoke : 200 -> 188
~ ____ldap_conn_set_supported_sasl_mechs_block_invoke : 96 -> 84
~ ____ldap_conn_set_naming_contexts_block_invoke : 96 -> 84
~ ____ldap_conn_auth_on_connection_block_invoke : 1016 -> 1004
~ ____ldap_conn_create_list_of_mechs_to_try_block_invoke_2 : 88 -> 76
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _odm_create_connection_with_options : 212 -> 200
~ ___GetAuthenticationData_block_invoke : 148 -> 136
~ ____ldap_create_service_principal_aliases_block_invoke : 136 -> 124
~ ____ldap_make_trust_account_session_key_agent_if_applicable_block_invoke : 280 -> 268
~ ___copy_helper_block_8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_8_32r40r48r : 80 -> 68
~ ___copy_helper_block_8_32r40r48r56r64r : 128 -> 116
~ ___destroy_helper_block_8_32r40r48r56r64r : 104 -> 92
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _ldap_read_server_mappings : 220 -> 196
~ _ldap_write_server_mappings : 1176 -> 1164
~ _ldap_modcfg_init : 980 -> 968
~ ___ldap_modcfg_init_block_invoke_2 : 68 -> 56
~ ___ldap_modcfg_init_block_invoke_4 : 60 -> 48
~ ___ldap_modcfg_init_block_invoke_5 : 68 -> 56
~ ___ldap_modcfg_init_block_invoke_7 : 76 -> 64
~ __ldap_modcfg_publish_info : 216 -> 204
~ ___ldap_modcfg_init_block_invoke_9 : 88 -> 76
~ ___ldap_modcfg_init_block_invoke_11 : 124 -> 112
~ ____ldap_modcfg_set_kerberos_realm_block_invoke : 96 -> 84
~ ____ldap_modcfg_set_kerberos_domain_mappings_block_invoke : 96 -> 84
~ _aodc_unicode_array_from_cfstr : 144 -> 132
~ _aodc_error_create_with_args : 272 -> 260
~ _aodc_error_create : 96 -> 84
~ _aodc_create_string_from_error : 308 -> 296
~ _aodc_log_cfdict_contents : 456 -> 444
~ _aodc_create_url_with_destination : 476 -> 464
~ ___aodc_copy_services_from_localhost_block_invoke : 100 -> 88
~ __ldap_policy_create_dn_prefix_str : 220 -> 196
~ ___ldap_remove_all_real_policies_block_invoke_2 : 88 -> 76
```
