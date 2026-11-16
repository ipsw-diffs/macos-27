## libcurl.4.dylib

> `/usr/lib/libcurl.4.dylib`

```diff

-168.40.2.0.0
-  __TEXT.__text: 0x6b948
-  __TEXT.__const: 0xee4
-  __TEXT.__cstring: 0x10aa5
-  __TEXT.__unwind_info: 0x1550
+168.60.2.0.0
+  __TEXT.__text: 0x7d3c4
+  __TEXT.__const: 0x19d0
+  __TEXT.__cstring: 0x120d2
+  __TEXT.__unwind_info: 0x1938
   __TEXT.__auth_stubs: 0x0
-  __DATA_CONST.__const: 0x2040
+  __DATA_CONST.__const: 0x35c0
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x1800
+  __AUTH_CONST.__const: 0x1b50
   __AUTH_CONST.__cfstring: 0x60
-  __AUTH_CONST.__auth_got: 0xe80
-  __AUTH.__data: 0x6e8
-  __DATA.__data: 0x1f38
-  __DATA.__bss: 0x380
+  __AUTH_CONST.__auth_got: 0xef0
+  __AUTH.__data: 0x730
+  __DATA.__data: 0x198
+  __DATA.__common: 0x20
+  __DATA.__bss: 0x378
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Kerberos.framework/Versions/A/Kerberos
   - /System/Library/Frameworks/LDAP.framework/Versions/A/LDAP

   - /usr/lib/libcrypto.46.dylib
   - /usr/lib/libssl.48.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1440
-  Symbols:   2092
-  CStrings:  2861
+  Functions: 1719
+  Symbols:   2393
+  CStrings:  3039
 
Symbols:
+ _ALPN_SPEC_H2
+ _Curl_alpn2alpnid
+ _Curl_alpn_contains_proto
+ _Curl_alpn_copy
+ _Curl_alpn_restrict_to
+ _Curl_async_await
+ _Curl_async_destroy
+ _Curl_async_get_impl
+ _Curl_async_getaddrinfo
+ _Curl_async_getsock
+ _Curl_async_global_cleanup
+ _Curl_async_global_init
+ _Curl_async_is_resolved
+ _Curl_async_shutdown
+ _Curl_async_thrdd_destroy
+ _Curl_async_thrdd_shutdown
+ _Curl_auth_create_ntlm_type3_message.host
+ _Curl_base64encdec
+ _Curl_bufq_unwrite
+ _Curl_cf_def_shutdown
+ _Curl_cipher_suite_get_str
+ _Curl_cipher_suite_lookup_id
+ _Curl_cipher_suite_walk_str
+ _Curl_conn_cf_get_ip_info
+ _Curl_conn_cf_needs_flush
+ _Curl_conn_cf_poll
+ _Curl_conn_flush
+ _Curl_conn_free
+ _Curl_conn_get_stream_error
+ _Curl_conn_http_version
+ _Curl_conn_is_setup
+ _Curl_conn_is_tcp_listen
+ _Curl_conn_meta_get
+ _Curl_conn_meta_remove
+ _Curl_conn_meta_set
+ _Curl_conn_needs_flush
+ _Curl_conn_seems_dead
+ _Curl_conn_shutdown
+ _Curl_conn_shutdown_timeleft
+ _Curl_conn_terminate
+ _Curl_conn_upkeep
+ _Curl_connect_only_attach
+ _Curl_cpool_add
+ _Curl_cpool_check_limits
+ _Curl_cpool_conn_now_idle
+ _Curl_cpool_destroy
+ _Curl_cpool_do_by_id
+ _Curl_cpool_do_locked
+ _Curl_cpool_find
+ _Curl_cpool_get_conn
+ _Curl_cpool_init
+ _Curl_cpool_prune_dead
+ _Curl_cpool_upkeep
+ _Curl_cpool_xfer_init
+ _Curl_creader_def_is_paused
+ _Curl_creader_is_paused
+ _Curl_cshutdn_add
+ _Curl_cshutdn_add_pollfds
+ _Curl_cshutdn_add_waitfds
+ _Curl_cshutdn_close_oldest
+ _Curl_cshutdn_count
+ _Curl_cshutdn_dest_count
+ _Curl_cshutdn_destroy
+ _Curl_cshutdn_init
+ _Curl_cshutdn_perform
+ _Curl_cshutdn_run_once
+ _Curl_cshutdn_setfds
+ _Curl_cshutdn_terminate
+ _Curl_cw_out_unpause
+ _Curl_cw_pause_flush
+ _Curl_cwriter_is_content_decoding
+ _Curl_cwriter_is_paused
+ _Curl_cwriter_unpause
+ _Curl_cwt_pause
+ _Curl_dnscache_add
+ _Curl_dnscache_destroy
+ _Curl_dnscache_get
+ _Curl_dnscache_init
+ _Curl_dnscache_mk_entry
+ _Curl_dnscache_prune
+ _Curl_expire_ex
+ _Curl_handler_ws
+ _Curl_handler_wss
+ _Curl_hash_add2
+ _Curl_hash_count
+ _Curl_hexasciitable
+ _Curl_hexbyte
+ _Curl_http_follow
+ _Curl_http_neg_init
+ _Curl_http_write_resp_hd
+ _Curl_junkscan
+ _Curl_ldigits
+ _Curl_llist_append
+ _Curl_llist_head
+ _Curl_meta_get
+ _Curl_meta_remove
+ _Curl_meta_reset
+ _Curl_meta_set
+ _Curl_multi_ev_assess_conn
+ _Curl_multi_ev_assess_xfer
+ _Curl_multi_ev_assess_xfer_bset
+ _Curl_multi_ev_assign
+ _Curl_multi_ev_cleanup
+ _Curl_multi_ev_conn_done
+ _Curl_multi_ev_expire_xfers
+ _Curl_multi_ev_init
+ _Curl_multi_ev_socket_done
+ _Curl_multi_ev_xfer_done
+ _Curl_multi_get_easy
+ _Curl_multi_getsock
+ _Curl_multi_will_close
+ _Curl_multi_xfer_sockbuf_borrow
+ _Curl_multi_xfer_sockbuf_release
+ _Curl_multi_xfers_running
+ _Curl_netrc_cleanup
+ _Curl_netrc_init
+ _Curl_netrc_strerror
+ _Curl_nghttp2_calloc
+ _Curl_nghttp2_free
+ _Curl_nghttp2_malloc
+ _Curl_nghttp2_realloc
+ _Curl_node_elem
+ _Curl_node_llist
+ _Curl_node_next
+ _Curl_node_remove
+ _Curl_node_take_elem
+ _Curl_node_uremove
+ _Curl_oss_check_peer_cert
+ _Curl_ossl_add_session
+ _Curl_ossl_ctx_init
+ _Curl_ossl_version
+ _Curl_parse_interface
+ _Curl_parse_interface.host_prefix
+ _Curl_parse_interface.if_host_prefix
+ _Curl_pgrsEarlyData
+ _Curl_pgrsUpdate_nometer
+ _Curl_pipe
+ _Curl_pollfds_add_ps
+ _Curl_pollfds_add_sock
+ _Curl_pollfds_cleanup
+ _Curl_pollfds_init
+ _Curl_pollfds_reset
+ _Curl_pp_needs_flush
+ _Curl_rand_bytes
+ _Curl_req_sendbuf_empty
+ _Curl_req_stop_send_recv
+ _Curl_resolv_blocking
+ _Curl_resolv_unlink
+ _Curl_sasl_is_blocked
+ _Curl_sec_conn_destroy
+ _Curl_sec_conn_init
+ _Curl_sendrecv
+ _Curl_sha512_256_finish
+ _Curl_sha512_256_init
+ _Curl_sha512_256_transform
+ _Curl_sha512_256_transform.K
+ _Curl_sha512_256_update
+ _Curl_shutdown_clear
+ _Curl_shutdown_start
+ _Curl_shutdown_started
+ _Curl_shutdown_timeleft
+ _Curl_socketpair
+ _Curl_splayget
+ _Curl_splayset
+ _Curl_ssl_get_channel_binding
+ _Curl_ssl_peer_key_make
+ _Curl_ssl_scache_add_obj
+ _Curl_ssl_scache_create
+ _Curl_ssl_scache_destroy
+ _Curl_ssl_scache_get_obj
+ _Curl_ssl_scache_lock
+ _Curl_ssl_scache_put
+ _Curl_ssl_scache_remove_all
+ _Curl_ssl_scache_return
+ _Curl_ssl_scache_take
+ _Curl_ssl_scache_unlock
+ _Curl_ssl_session_create
+ _Curl_ssl_session_create2
+ _Curl_ssl_session_destroy
+ _Curl_trc_dns
+ _Curl_trc_feat_dns
+ _Curl_trc_feat_ftp
+ _Curl_trc_feat_ids
+ _Curl_trc_feat_multi
+ _Curl_trc_feat_read
+ _Curl_trc_feat_smtp
+ _Curl_trc_feat_ssls
+ _Curl_trc_feat_write
+ _Curl_trc_feat_ws
+ _Curl_trc_ftp
+ _Curl_trc_mstate_name
+ _Curl_trc_mstate_names
+ _Curl_trc_multi
+ _Curl_trc_read
+ _Curl_trc_smtp
+ _Curl_trc_ssls
+ _Curl_trc_write
+ _Curl_trc_ws
+ _Curl_udigits
+ _Curl_uint_bset_add
+ _Curl_uint_bset_capacity
+ _Curl_uint_bset_clear
+ _Curl_uint_bset_contains
+ _Curl_uint_bset_count
+ _Curl_uint_bset_destroy
+ _Curl_uint_bset_empty
+ _Curl_uint_bset_first
+ _Curl_uint_bset_init
+ _Curl_uint_bset_next
+ _Curl_uint_bset_remove
+ _Curl_uint_bset_resize
+ _Curl_uint_hash_clear
+ _Curl_uint_hash_count
+ _Curl_uint_hash_destroy
+ _Curl_uint_hash_get
+ _Curl_uint_hash_init
+ _Curl_uint_hash_remove
+ _Curl_uint_hash_set
+ _Curl_uint_hash_visit
+ _Curl_uint_spbset_add
+ _Curl_uint_spbset_clear
+ _Curl_uint_spbset_contains
+ _Curl_uint_spbset_count
+ _Curl_uint_spbset_destroy
+ _Curl_uint_spbset_empty
+ _Curl_uint_spbset_first
+ _Curl_uint_spbset_init
+ _Curl_uint_spbset_next
+ _Curl_uint_spbset_remove
+ _Curl_uint_tbl_add
+ _Curl_uint_tbl_capacity
+ _Curl_uint_tbl_clear
+ _Curl_uint_tbl_contains
+ _Curl_uint_tbl_count
+ _Curl_uint_tbl_destroy
+ _Curl_uint_tbl_first
+ _Curl_uint_tbl_get
+ _Curl_uint_tbl_init
+ _Curl_uint_tbl_next
+ _Curl_uint_tbl_remove
+ _Curl_uint_tbl_resize
+ _Curl_waitfds_add_ps
+ _Curl_waitfds_init
+ _Curl_ws_accept
+ _Curl_ws_request
+ _Curl_xfer_flush
+ _Curl_xfer_is_blocked
+ _Curl_xfer_needs_flush
+ _Curl_xfer_send_shutdown
+ _Curl_xfer_setup1
+ _Curl_xfer_setup2
+ _Curl_xfer_setup_nop
+ _Curl_xfer_write_is_paused
+ _Curl_xfer_write_resp_hd
+ _EVP_get_digestbyname
+ _OBJ_find_sigid_algs
+ _SSL_SESSION_get_timeout
+ _SSL_set_alpn_protos
+ _SSL_version
+ _TLS_method
+ _X509_digest
+ _X509_get_signature_nid
+ __ftp_state
+ _addr_ctx_destroy
+ _altsvc_create
+ _asyn_thrdd_await
+ _async_thrdd_destroy
+ _authcmp
+ _buffer_read
+ _calc_s3_payload_hash
+ _canon_path
+ _cf_ctx_free
+ _cf_h2_body_send
+ _cf_h2_ctx_free
+ _cf_h2_header_error
+ _cf_h2_on_invalid_frame_recv
+ _cf_h2_proxy_cntrl
+ _cf_h2_proxy_query
+ _cf_h2_proxy_shutdown
+ _cf_h2_shutdown
+ _cf_h2_update_local_win
+ _cf_hc_cntrl
+ _cf_hc_shutdown
+ _cf_he_shutdown
+ _cf_scache_peer_remove_expired
+ _cf_socket_shutdown
+ _cf_ssl_add_peer
+ _cf_ssl_cache_peer_update
+ _cf_ssl_find_peer_by_key
+ _cf_ssl_peer_key_add_hash
+ _cf_ssl_peer_key_add_path
+ _cf_ssl_scache_clear_peer
+ _cf_ssl_scache_get
+ _cf_ssl_scache_session_ldestroy
+ _close_secondarysocket
+ _closedir
+ _compare_header_names
+ _conn_meta_freeentry
+ _cpfds_add_sock
+ _cpool_bundle_free_entry
+ _cpool_discard_conn
+ _cpool_do_conn
+ _cpool_find_conn
+ _cpool_foreach
+ _cpool_get_first
+ _cpool_get_oldest_idle
+ _cpool_reap_dead_cb
+ _cpool_remove_conn
+ _cr_buf_rewind
+ _cr_in_is_paused
+ _cr_in_unpause
+ _cr_mime_close
+ _cr_mime_is_paused
+ _create_dnscache_id
+ _cs_list
+ _cshutdn_destroy_oldest
+ _cshutdn_perform
+ _cshutdn_run_conn_handler
+ _cshutdn_run_once
+ _cshutdn_update_ev
+ _curl_easy_ssls_export
+ _curl_easy_ssls_import
+ _curl_multi_waitfds
+ _curlx_base64_decode
+ _curlx_base64_encode
+ _curlx_base64url_encode
+ _curlx_dyn_add
+ _curlx_dyn_addf
+ _curlx_dyn_addn
+ _curlx_dyn_free
+ _curlx_dyn_init
+ _curlx_dyn_len
+ _curlx_dyn_ptr
+ _curlx_dyn_reset
+ _curlx_dyn_setlen
+ _curlx_dyn_tail
+ _curlx_dyn_take
+ _curlx_dyn_uptr
+ _curlx_dyn_vaddf
+ _curlx_dyn_vprintf
+ _curlx_now
+ _curlx_str_assign
+ _curlx_str_casecompare
+ _curlx_str_cmp
+ _curlx_str_cspn
+ _curlx_str_hex
+ _curlx_str_init
+ _curlx_str_key_compare
+ _curlx_str_newline
+ _curlx_str_nudge
+ _curlx_str_number
+ _curlx_str_numblanks
+ _curlx_str_octal
+ _curlx_str_passblanks
+ _curlx_str_quotedword
+ _curlx_str_single
+ _curlx_str_singlespace
+ _curlx_str_trimblanks
+ _curlx_str_until
+ _curlx_str_untilnl
+ _curlx_str_word
+ _curlx_timediff
+ _curlx_timediff_ceil
+ _curlx_timediff_us
+ _cw_out_bufs_free
+ _cw_pause_close
+ _cw_pause_flush
+ _cw_pause_init
+ _cw_pause_write
+ _d2i_SSL_SESSION
+ _default_ciphers
+ _dnscache_entry_dtor
+ _dnscache_entry_is_stale
+ _doh_probe_done
+ _doh_probe_dtor
+ _doh_probe_run
+ _doh_probe_write_cb
+ _doh_rdata
+ _doh_show
+ _doh_skipqname
+ _dupeasy_meta_freeentry
+ _easy_meta_freeentry
+ _file_do.accept_ranges
+ _file_easy_dtor
+ _free_chain
+ _free_primary_ssl_config
+ _ftp_check_ctrl_on_data_wait
+ _ftp_conn_dtor
+ _ftp_conns_match
+ _ftp_easy_dtor
+ _ftp_initiate_transfer
+ _ftp_pp_statemachine
+ _ftp_pp_statemachine.ftpauth
+ _ftp_state_names
+ _ftp_state_pwd
+ _getASN1Element_
+ _h2_stream_ctx_free
+ _h2_stream_hash_free
+ _h2_xfer_write_resp_hd
+ _hash_elem_destroy
+ _http_aws_decode_encode
+ _http_cookies
+ _http_firstwrite
+ _http_range
+ _http_req_complete
+ _http_req_set_reader
+ _http_request_version
+ _http_rw_hd
+ _http_size
+ _http_switch_to_get
+ _http_target
+ _http_write_header
+ _httpauth
+ _i2d_SSL_SESSION
+ _imap_conn_dtor
+ _imap_easy_dtor
+ _imap_easy_reset
+ _imap_pp_statemachine
+ _inflateReset2
+ _is_reserved_char
+ _make_headers
+ _mev_assess
+ _mev_forget_socket
+ _mev_pollset_dtor
+ _mev_sh_entry_compare
+ _mev_sh_entry_dtor
+ _mev_sh_entry_hash
+ _mev_sh_entry_update
+ _move_pending_to_connect
+ _mqtt_conn_dtor
+ _mqtt_easy_dtor
+ _mqtt_verify_connack
+ _multi_done_locked
+ _multi_run_expired
+ _multi_xfer_bufs_free
+ _multi_xfers_add
+ _nghttp2_session_callbacks_set_on_invalid_frame_recv_callback
+ _nghttp2_session_client_new3
+ _nghttp2_submit_goaway
+ _nghttp2_submit_window_update
+ _nilstr
+ _nw_in_recv
+ _opendir
+ _oss_x509_share_free
+ _ossl_do_file_type
+ _ossl_get_channel_binding
+ _ossl_init_ssl
+ _out_number
+ _ph_freeentry
+ _pipe2
+ _pkp_pin_peer_pubkey
+ _poll
+ _pop3_conn_dtor
+ _pop3_easy_dtor
+ _pop3_write
+ _pop3cmds
+ _progress_calc
+ _push_certinfo
+ _readdir
+ _realpath$DARWIN_EXTSN
+ _rtsp_conn_dtor
+ _rtsp_easy_dtor
+ _sasl_unchosen
+ _sectransp_cipher_suite_get_str
+ _sectransp_get_supported_ciphers
+ _set_url
+ _set_url_port
+ _set_url_scheme
+ _setopt_RTSP_REQUEST
+ _setopt_cptr
+ _setstropt_interface
+ _setup_connection_internals
+ _should_urlencode
+ _sigpipe_apply
+ _smb_conn_dtor
+ _smb_easy_dtor
+ _smb_send_close
+ _smb_send_open
+ _smb_send_read
+ _smb_send_write
+ _smtp_conn_dtor
+ _smtp_easy_dtor
+ _smtp_perform_starttls
+ _smtp_pp_statemachine
+ _smtp_state
+ _smtp_state.names
+ _socketpair
+ _ssl_cf_connect_deferred
+ _ssl_cf_shutdown
+ _str_num_base
+ _telnet_easy_dtor
+ _telnet_negotiate
+ _tftp_conn_dtor
+ _trc_apply_level_by_category
+ _trc_apply_level_by_name
+ _trc_cfts
+ _trc_feats
+ _trc_infof
+ _trc_print_ids
+ _trc_write
+ _trc_write.s_infotype
+ _uint_hash_clear
+ _uint_spbset_get_chunk
+ _uint_tbl_clear_rows
+ _url_match_auth
+ _url_match_auth_nego
+ _url_match_auth_ntlm
+ _url_match_conn
+ _url_match_http_multiplex
+ _url_match_multiplex_limits
+ _url_match_proto_config
+ _url_match_result
+ _url_match_ssl_config
+ _ws_client_collect
+ _ws_conn_dtor
+ _ws_cw_close
+ _ws_cw_dec_next
+ _ws_cw_decode
+ _ws_cw_init
+ _ws_cw_write
+ _ws_dec_info
+ _ws_dec_pass
+ _ws_enc_info
+ _ws_enc_write_head
+ _ws_flush
+ _ws_frame_name_of_op
+ _ws_send_raw_blocking
+ _ws_setup_conn
+ _xfer_setup
- _AcceptServerConnect
- _AllowServerConnect
- _CRYPTO_malloc
- _Curl_addrinfo_callback
- _Curl_base64_decode
- _Curl_base64_encode
- _Curl_base64url_encode
- _Curl_bufq_space
- _Curl_cache_addr
- _Curl_conn_ev_data_attach
- _Curl_conn_ev_data_detach
- _Curl_conn_ev_update_info
- _Curl_conn_is_http2
- _Curl_conn_tcp_accepted_set
- _Curl_conncache_add_conn
- _Curl_conncache_close_all_connections
- _Curl_conncache_destroy
- _Curl_conncache_extract_bundle
- _Curl_conncache_extract_oldest
- _Curl_conncache_find_bundle
- _Curl_conncache_foreach
- _Curl_conncache_init
- _Curl_conncache_remove_conn
- _Curl_conncache_return_conn
- _Curl_conncache_size
- _Curl_cookie_freelist
- _Curl_cw_out_flush
- _Curl_cwriter_remove_by_name
- _Curl_disconnect
- _Curl_doh_trc
- _Curl_dyn_add
- _Curl_dyn_addf
- _Curl_dyn_addn
- _Curl_dyn_free
- _Curl_dyn_init
- _Curl_dyn_len
- _Curl_dyn_ptr
- _Curl_dyn_reset
- _Curl_dyn_setlen
- _Curl_dyn_tail
- _Curl_dyn_uptr
- _Curl_dyn_vaddf
- _Curl_dyn_vprintf
- _Curl_dynhds_add_custom
- _Curl_fetch_addr
- _Curl_follow
- _Curl_free_multi_ssl_backend_data
- _Curl_free_primary_ssl_config
- _Curl_getaddrinfo
- _Curl_he2ai
- _Curl_hostcache_clean
- _Curl_hostcache_prune
- _Curl_http_cookies
- _Curl_http_exp100_got100
- _Curl_http_exp100_is_selected
- _Curl_http_firstwrite
- _Curl_http_header
- _Curl_http_host
- _Curl_http_range
- _Curl_http_req_complete
- _Curl_http_req_set_reader
- _Curl_http_size
- _Curl_http_statusline
- _Curl_http_target
- _Curl_http_useragent
- _Curl_init_dnscache
- _Curl_ipvalid
- _Curl_llist_remove
- _Curl_multi_closed
- _Curl_multi_max_host_connections
- _Curl_multi_max_total_connections
- _Curl_multiuse_state
- _Curl_none_cert_status_request
- _Curl_none_check_cxn
- _Curl_none_cleanup
- _Curl_none_close_all
- _Curl_none_data_pending
- _Curl_none_engines_list
- _Curl_none_false_start
- _Curl_none_init
- _Curl_none_random
- _Curl_none_session_free
- _Curl_none_set_engine
- _Curl_none_set_engine_default
- _Curl_none_shutdown
- _Curl_now
- _Curl_ossl_certchain
- _Curl_ossl_set_client_cert
- _Curl_ossl_verifyhost
- _Curl_persistconninfo
- _Curl_pop3_write
- _Curl_posttransfer
- _Curl_preconnect
- _Curl_rand
- _Curl_readwrite
- _Curl_resolv_unlock
- _Curl_resolver_cancel
- _Curl_resolver_cleanup
- _Curl_resolver_duphandle
- _Curl_resolver_getaddrinfo
- _Curl_resolver_getsock
- _Curl_resolver_global_cleanup
- _Curl_resolver_global_init
- _Curl_resolver_init
- _Curl_resolver_is_resolved
- _Curl_resolver_kill
- _Curl_resolver_wait_resolv
- _Curl_sec_end
- _Curl_set_dns_interface
- _Curl_set_dns_local_ip4
- _Curl_set_dns_local_ip6
- _Curl_set_dns_servers
- _Curl_ssl_addsessionid
- _Curl_ssl_delsessionid
- _Curl_ssl_getsessionid
- _Curl_ssl_initsessions
- _Curl_ssl_kill_session
- _Curl_ssl_sessionid_lock
- _Curl_ssl_sessionid_unlock
- _Curl_str_key_compare
- _Curl_timediff
- _Curl_timediff_ceil
- _Curl_timediff_us
- _Curl_transferencode
- _Curl_updatesocket
- _Curl_use_http_1_1plus
- _Curl_xfer_setup
- _InitiateTransfer
- _MHDx_sha512_256_finish
- _MHDx_sha512_256_init
- _MHDx_sha512_256_transform
- _MHDx_sha512_256_transform.K
- _MHDx_sha512_256_update
- _ReceivedServerConnect
- _SSL_CTX_set_alpn_protos
- _access
- _alpn2alpnid
- _base64enc
- _base64encdec
- _bundle_remove_conn
- _call_extract_if_dead
- _cf_h2_ctx_clear
- _cf_types
- _check_gzip_header
- _ciphertable
- _cnOID
- _concat_url
- _conn_free
- _conn_is_conn
- _conncache_find_first_connection
- _create_hostcache_id
- _curlx_strtoofft
- _curlx_ultous
- _curlx_uztoso
- _destroy_async_data
- _destroy_thread_sync_data
- _do_connect
- _do_file_type
- _doh_done
- _doh_write_cb
- _dohprobe
- _extract_if_dead
- _fd_key_compare
- _formatf.nilstr
- _free_bundle_hash_entry
- _freednsentry
- _ftp_dophase_done
- _ftp_statemachine
- _ftp_statemachine.ftpauth
- _ftp_timeleft_accept
- _getASN1Element
- _get_http_string
- _getalnum
- _getpid
- _hash_element_dtor
- _hash_fd
- _hashkey
- _have_openssl
- _hexdigits
- _hextable
- _hostcache_timestamp_remove
- _imap_perform_upgrade_tls
- _imap_statemachine
- _invalid_octets.badoctets
- _junkscan.badbytes
- _lower_digits
- _mqtt_disconnect
- _multi_getsock
- _multissl_connect_nonblocking
- _negotiate
- _nghttp2_session_client_new2
- _nw_in_read
- _ossl_bio_cf_method_create
- _ossl_connect_common
- _ossl_connect_nonblocking
- _ossl_free_multi_ssl_backend_data
- _ossl_session_free
- _ossl_version
- _pipe
- _pop3_perform_upgrade_tls
- _prune_dead_connections
- _randit
- _randit.randseed
- _randit.seeded
- _rdata
- _resolve_server
- _rtsp_disconnect
- _sanOID
- _sectransp_connect_common
- _sectransp_connect_nonblocking
- _sh_freeentry
- _showdoh
- _singlesocket
- _skipqname
- _smb_disconnect
- _smtp_perform_upgrade_tls
- _smtp_statemachine
- _sockhash_destroy
- _sscanf
- _ssl_cf_cntrl
- _ssl_prefs_check
- _strtok_r
- _strtoul
- _tftp_disconnect
- _trhash
- _trhash_compare
- _trhash_dtor
- _upper_digits
CStrings:
+ "\t\r\n"
+ " \t\r;,"
+ " ("
+ " (upgraded to SSL)"
+ " NON-FIN"
+ " NON-FINAL"
+ " secondary"
+ "%%%02X"
+ "%.*s4%s"
+ "%.*s4-HMAC-SHA256\n%s\n%s\n%s"
+ "%.*s4_request"
+ "%.*s:\r\n"
+ "%s %s%s%s %u %s %s%s%s %u \"%d%02d%02d %02d:%02d:%02d\" %u %u\n"
+ "%s cached session for '%s'"
+ "%s connection #%ld"
+ "%s pollset[], timeouts=%zu, paused %d/%d (r/w)"
+ "%s pollset[fd=%d %s%s, fd=%d %s%s], timeouts=%zu"
+ "%s pollset[fd=%d %s%s], timeouts=%zu"
+ "%s pollset[fds=%u], timeouts=%zu"
+ "%s%c%s%c%s%c%s"
+ "%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s"
+ "%s/%.*s/%.*s/%s"
+ "%s://"
+ "%s="
+ "%s=%s"
+ "%s[CPOOL] destroy, %zu connections"
+ "%s_proxy"
+ "%u/%d/%s"
+ "%zu bytes payload"
+ "(null)"
+ "-> [%s]"
+ ".localhost."
+ ".netrc error: %s"
+ "1.2.840.10045.4.3.1"
+ "1.2.840.10045.4.3.2"
+ "1.2.840.10045.4.3.3"
+ "1.2.840.10045.4.3.4"
+ "1.2.840.113549.1.9.2"
+ "13"
+ "2.5.29.17"
+ "2.5.4.3"
+ "3"
+ "8.14.1"
+ ":%s-"
+ ":%s-%s"
+ ":CCERT"
+ ":CHOST-%s"
+ ":CIPHER-%s"
+ ":CIPHER13-%s"
+ ":CPORT-%d"
+ ":CURVES-%s"
+ ":G"
+ ":IMPL-%s"
+ ":L"
+ ":NO-VRFY-HOST"
+ ":NO-VRFY-PEER"
+ ":Pinned-%s"
+ ":QUIC"
+ ":TLSOPT-%x"
+ ":TLSVER-%d-%d"
+ ":TRNSPRT-%d"
+ ":UDP"
+ ":UNIX"
+ ":VRFY-STATUS"
+ ";:"
+ "???"
+ "A Transfer-Encoding (%.*s) was listed after chunked"
+ "ACCT"
+ "ALPN: asked for '%s' from previous session, but server did not confirm it. Refusing to continue."
+ "ALPN: asked for '%s' from previous session, but server selected '%.*s'. Refusing to continue."
+ "ALPN: deferred handshake for early data using '%.*s'."
+ "ALPN: deferred handshake for early data without specific protocol."
+ "ALPN: server confirmed to use '%s'"
+ "ALPN: server selected protocol contains NUL. Refusing to continue."
+ "APOP"
+ "APPEND %s%s {%ld}"
+ "AUTH"
+ "Added %.*s:%ld:%s to DNS cache%s"
+ "Added alt-svc: %.*s:%d over %s"
+ "Allowing sub-requests (like DoH) to override max connection limit"
+ "Answered"
+ "Authorization: %.*s4-HMAC-SHA256 Credential=%s/%s, SignedHeaders=%s, Signature=%s\r\n%s%s"
+ "BIN"
+ "Bad alt-svc IPv6 hostname, ignoring."
+ "Bad alt-svc hostname, ignoring."
+ "Basic authentication problem, ignoring."
+ "Bearer authentication problem, ignoring."
+ "CA"
+ "CAInfoBlob"
+ "CApath"
+ "CLIENT libcurl 8.14.1\r\n%s\r\nQUIT\r\n"
+ "CLIENT libcurl 8.14.1\r\nDEFINE %s %s\r\nQUIT\r\n"
+ "CLIENT libcurl 8.14.1\r\nMATCH %s %s %s\r\nQUIT\r\n"
+ "CLOSE"
+ "COMMAND"
+ "COMPLETED"
+ "CONNECTING"
+ "CONT"
+ "CRL"
+ "CURLOPT_XOAUTH2_BEARER"
+ "CWD"
+ "Cannot use sigv4 authentication with path-as-is flag"
+ "CertBlob"
+ "Checking for incoming on fd=%d ip=%s:%d"
+ "Connection #%ld is not open enough, cannot reuse"
+ "Connection pool is full, closing the oldest of %zu/%u"
+ "Connection still in use %u, no more multi_done now!"
+ "Could not connect to server"
+ "Could not find digest algorithm %s (NID %d)"
+ "Could not read a file:// file"
+ "Could not resolve hostname"
+ "Could not resolve proxy name"
+ "Could not resume download"
+ "Could not use specified SSL cipher"
+ "Couldn't bind to '%s' with errno %d: %s"
+ "Couldn't bind to interface '%s' with errno %d: %s"
+ "Curl_conn_connect(), filter returned %d"
+ "Curl_conn_connect(block=%d) -> %d, done=%d"
+ "Curl_conn_connect(block=1), Curl_poll() -> %d"
+ "Curl_conn_connect(block=1), do poll"
+ "Curl_multi_will_close fd=%d"
+ "Curl_resolv_check() -> %d, %s"
+ "DELE"
+ "DID"
+ "DNS"
+ "DOING"
+ "DOING_MORE"
+ "DONE"
+ "Deleted"
+ "Digest authentication problem, ignoring."
+ "Discarding connection #%ld from %zu to reach destination limit of %zu"
+ "Discarding connection #%ld from %zu to reach total limit of %zu"
+ "Draft"
+ "Drop custom request method for next request"
+ "EAGAIN flushing sendbuf, payload_encoded: %zu/%zu"
+ "ECH"
+ "ECH attempted but failed"
+ "EHLO"
+ "Error determining ALPN"
+ "Error receiving HTTP2 header: %d(%s)"
+ "Excessive username length for proxy auth"
+ "Expire cleared"
+ "FTP: cannot figure out the host in the PASV response"
+ "FTP: could not retrieve (RETR failed) the specified file"
+ "FTP: could not set file type"
+ "Failed extracting certificate chain"
+ "Failed to determine username."
+ "Failed to find the SSL filter"
+ "Failed to resolve %s '%s' with timeout after %ld ms"
+ "Failed to set TCP_KEEPCNT on fd %d: errno %d"
+ "Flagged"
+ "Found"
+ "HELO"
+ "HTTP server does not seem to support byte ranges. Cannot resume."
+ "HTTPS_PROXY"
+ "Hostname in DNS cache does not have needed family, zapped"
+ "INIT"
+ "Invalid response header"
+ "IssuerBlob"
+ "LIB-IDS"
+ "LIST_TYPE"
+ "MAIL"
+ "MAX_CONCURRENT_STREAMS reached, skip (%u)"
+ "MDTM"
+ "MKD"
+ "MSG"
+ "MSGSENT"
+ "MULTI"
+ "NAMEFMT"
+ "NTLM authentication problem, ignoring."
+ "No"
+ "No connections available, total of %ld reached."
+ "No more connections allowed to host"
+ "OpenSSL engine not found"
+ "PASS"
+ "PBSZ"
+ "PENDING"
+ "PENDING handle timeout"
+ "PERFORMING"
+ "PING"
+ "PONG"
+ "POSTDATA"
+ "PRET"
+ "PROT"
+ "PROTOCONNECT"
+ "PROTOCONNECTING"
+ "PROV"
+ "Password too long: [%zu]"
+ "QUIC needs at least TLS version 1.3"
+ "RATELIMITING"
+ "RCPT"
+ "READ"
+ "RESOLVE %.*s:%ld - old addresses discarded"
+ "RESOLVE *:%ld using wildcard"
+ "RESOLVING"
+ "REST"
+ "RETR_PREQUOTE"
+ "RETR_REST"
+ "RETR_SIZE"
+ "RETR_TYPE"
+ "RSET"
+ "RTSP/1.0"
+ "Re-using existing %s: connection%s with %s %s"
+ "Received ping response."
+ "Refused WebSockets upgrade: %d"
+ "Reject response due to 'chunked' not being the last Transfer-Encoding"
+ "SASL: %s is missing %s"
+ "SASL: %s is missing username"
+ "SASL: %s not builtin"
+ "SASL: %s not supported by the platform/libraries"
+ "SASL: auth EXTERNAL not chosen with password"
+ "SASL: no auth mechanism offered could be selected"
+ "SASL: no auth mechanism was offered or recognized"
+ "SASL: no overlap between offered and configured auth mechanisms"
+ "SERVERGREET"
+ "SOCKS4: too long hostname"
+ "SSL reusing session with ALPN '%s'"
+ "SSL session not accepted by OpenSSL, continuing without"
+ "SSL shutdown not received, but closed"
+ "SSL shutdown not sent, read -> %d"
+ "SSL shutdown read -> %d"
+ "SSL shutdown received, not sending"
+ "SSL shutdown sent, want receive"
+ "SSL shutdown still wants to send"
+ "SSL shutdown, ignore recv error: '%s', errno %d"
+ "SSL: Failed to allocate memory"
+ "SSL: Failed to get supported ciphers"
+ "SSL: SSL_set_session not accepted, continuing without: %s"
+ "SSL: cannot find the certificate \"%s\" and its private key in the Keychain."
+ "SSL: cannot load CA certificate file %s"
+ "SSL: cannot load the certificate \"%s\" and its private key: OSStatus %d"
+ "SSL: certificate subject name '%s' does not match target hostname '%s'"
+ "SSL: could not allocate %zu bytes of memory"
+ "SSL: could not create a context"
+ "SSL: could not create a context (handle)"
+ "SSL: could not create a context: %s"
+ "SSL: could not get X509-issuer name"
+ "SSL: could not get peer certificate"
+ "SSL: duplicate cipher in list: \"%.*s\""
+ "SSL: failed to set maximum TLS version"
+ "SSL: failed to set minimum TLS version"
+ "SSL: no supported cipher in list"
+ "SSL: no supported default ciphers"
+ "SSL: unknown cipher in list: \"%.*s\""
+ "SSL: unsupported maximum TLS version value"
+ "SSL: unsupported minimum TLS version value"
+ "SSLS"
+ "SSL_SIGNATURE_ALGORITHMS"
+ "SSL_connect() -> err=%d, detail=%d"
+ "SSL_connect() -> want recv"
+ "SSL_connect() -> want send"
+ "STAT"
+ "STOP"
+ "STOR"
+ "STOR_PREQUOTE"
+ "STOR_SIZE"
+ "STOR_TYPE"
+ "Sec-WebSocket-Key"
+ "Sec-WebSocket-Version"
+ "Seen"
+ "Server accepted %zu bytes of TLS early data."
+ "Server did not accept auth data"
+ "Server prematurely closed the RTSP connection."
+ "Server rejected TLS early data."
+ "Server upgrade does not support multiplex yet, wait"
+ "Shutdown send direction error: %d. Broken server? Proceeding as if everything is ok."
+ "Stick to %s instead of GET"
+ "Switch to GET because of %d response"
+ "TCP_KEEPCNT"
+ "TEXT"
+ "TFTP filename too long"
+ "TLS connect error: %s"
+ "TLS_UNKNOWN_0x%04x"
+ "TOP"
+ "TUNNELING"
+ "TYPE"
+ "Timeout waiting for block %d ACK. Retries = %d"
+ "Too long SOCKS proxy username"
+ "Too long hostname (maximum is %d)"
+ "Too many response headers, %d is max"
+ "Trailer:"
+ "UIDL"
+ "UPGRADETLS"
+ "UPLOAD_FLAGS"
+ "UTF8"
+ "Unable to find digest NID for certificate signature algorithm"
+ "Unsolicited Transfer-Encoding (%.*s) found"
+ "Unsupported Content-Length value"
+ "Uploading to a URL without a filename"
+ "Username too long: [%zu]"
+ "Version mismatch (from HTTP/%u to HTTP/%u)"
+ "WAIT220"
+ "WARNING: no socket in pollset or timer, transfer may stall!"
+ "WRITE"
+ "WS, using chunk size %zu"
+ "WS-ENC: %s [%s%s payload=%ld/%ld]"
+ "WSS"
+ "Waiting on connection to negotiate possible multiplexing."
+ "X-%.*s-Date"
+ "X509_digest() failed"
+ "XTND"
+ "[%d] EOS frame with unfinished upload and HTTP status %d, abort upload by RST"
+ "[%d] PUSH_PROMISE, denied by application -> %d"
+ "[%d] PUSH_PROMISE, failed to set url -> %d"
+ "[%d] cf_body_send last CHUNK -> %zd, %d, eos=%d"
+ "[%d] cf_body_send(len=%zu) -> %zd, %d, eos=%d"
+ "[%d] cf_send(len=%zu) -> %zd, %d, eos=%d, h2 windows %d-%d (stream-conn), buffers %zu-%zu (stream-conn)"
+ "[%d] error %d writing %zu bytes of data, RST-ing stream"
+ "[%d] error %d writing %zu bytes of headers"
+ "[%d] error after response headers, but we did not want a body anyway, ignore: %s (err %u)"
+ "[%d] flush -> %d, h2 windows %d-%d (stream-conn), buffers %zu-%zu (stream-conn)"
+ "[%d] local window size now %d"
+ "[%d] local window update by %d"
+ "[%d] nghttp2 set_local_window_size(%d) failed: %s(%d)"
+ "[%d] nghttp2_session_set_local_window_size() failed: %s(%d)"
+ "[%d] nghttp2_submit_window_update() failed: %s(%d)"
+ "[%d] req_body_read(len=%zu) eos=%d -> %zd, %d"
+ "[%d] stream now %spaused"
+ "[%d] stream output paused"
+ "[%d] stream output unpaused"
+ "[%d] xfer write failed"
+ "[%ld-%ld] "
+ "[%ld-x] "
+ "[%s] -> [%s]"
+ "[%s] DO phase failed"
+ "[%s] DO phase is complete1"
+ "[%s] DO phase is complete2"
+ "[%s] DO phase starts"
+ "[%s] DO-MORE phase ends with %d"
+ "[%s] closing DATA connection"
+ "[%s] done, result=%d"
+ "[%s] ftp_domore_getsock()"
+ "[%s] ftp_state_retr()"
+ "[%s] ftp_state_use_port(), listening on %d"
+ "[%s] ftp_state_use_port(), opened socket"
+ "[%s] ftp_state_use_port(), socket bound to port %d"
+ "[%s] perform, awaiting DATA connect"
+ "[%s] protocol connect phase DONE"
+ "[%s] setup connection -> %d"
+ "[0] progress ingress: done"
+ "[0] progress ingress: inbufg=%zu"
+ "[CPOOL] added connection %ld. The cache now contains %zu members"
+ "[CPOOL] not discarding #%ld still in use by %u transfers"
+ "[FTP] [%s] perform, DATA connection established"
+ "[HTTP2] [%d] received invalid frame: %s, error %d: %s"
+ "[OUT] PAUSE requested by client"
+ "[OUT] done"
+ "[OUT] paused, buffering %zu more bytes (%zu/%d)"
+ "[OUT] unpause"
+ "[OUT] wrote %zu %s bytes -> %zu"
+ "[PAUSE] buffer %zu more bytes of type %x, total=%zu -> %d"
+ "[PAUSE] flushed %zu/%zu bytes, type=%x -> %d"
+ "[PAUSE] flushed 0/%zu bytes, type=%x -> %d"
+ "[PAUSE] writing %zu/%zu bytes of type %x -> %d"
+ "[SCACHE] failed to add session for %s, error=%d"
+ "[SHARE] "
+ "[SHUTDOWN] %sclosing connection #%ld"
+ "[SHUTDOWN] added #%ld to shutdowns, now %zu conns in shutdown"
+ "[SHUTDOWN] destroy, %zu connections, timeout=%dms"
+ "[SHUTDOWN] discarding oldest shutdown connection due to connection limit of %zu"
+ "[SHUTDOWN] perform on %zu connections"
+ "[SHUTDOWN] shutdown all"
+ "[SHUTDOWN] shutdown finished cleanly"
+ "[SHUTDOWN] shutdown finished, %s"
+ "[SHUTDOWN] shutdown finished, aborted"
+ "[SHUTDOWN] shutdown, done=%d"
+ "[SHUTDOWN] trigger multi connchanged"
+ "[SHUTDOWN] update events failed, discarding #%ld"
+ "[WS] CLOSE frame must not be fragmented"
+ "[WS] CONNECT_ONLY is required"
+ "[WS] Error while waiting for socket becoming writable"
+ "[WS] No associated connection"
+ "[WS] No ongoing fragmented message to continue"
+ "[WS] Not a websocket transfer"
+ "[WS] PING frame must not be fragmented"
+ "[WS] PONG frame must not be fragmented"
+ "[WS] Received 101, switch to WebSocket; mask %02x%02x%02x%02x"
+ "[WS] Timeout waiting for socket becoming writable"
+ "[WS] auto-respond to PING with a PONG"
+ "[WS] connection expectedly closed?"
+ "[WS] connection is not setup for websocket"
+ "[WS] connection not found"
+ "[WS] curl_ws_send() called with smaller 'buflen' than bytes already buffered in previous call, %zu vs %zu"
+ "[WS] decode ending with %zd frame bytes remaining"
+ "[WS] decode error %d"
+ "[WS] error adding data to buffer %d"
+ "[WS] flush, write error %d"
+ "[WS] fragmented message interrupted by new BINARY msg"
+ "[WS] fragmented message interrupted by new TEXT msg"
+ "[WS] fragsize and flags must be zero in raw mode"
+ "[WS] frame length longer than 64 signed not supported"
+ "[WS] given CLOSE frame is too big"
+ "[WS] given PING frame is too big"
+ "[WS] given PONG frame is too big"
+ "[WS] invalid fragmented CLOSE frame"
+ "[WS] invalid fragmented PING frame"
+ "[WS] invalid fragmented PONG frame"
+ "[WS] invalid opcode: %02x"
+ "[WS] invalid reserved bits: %02x"
+ "[WS] masked input frame"
+ "[WS] no flags given"
+ "[WS] no flags given; interpreting as continuation fragment for compatibility"
+ "[WS] no ongoing fragmented message to resume"
+ "[WS] not a websocket transfer"
+ "[WS] received CLOSE frame is too big"
+ "[WS] received PING frame is too big"
+ "[WS] received PONG frame is too big"
+ "[WS] setting CURLWS_CONT flag without message type is supported for compatibility but highly discouraged"
+ "[WS] starting new frame with %zd bytes from last one remaining to be sent"
+ "[WS] starting new frame with negative payload length %ld"
+ "[WS] unaligned frame size (sending %zu instead of %ld)"
+ "[WS] unexpected frame header length"
+ "[WS] unknown flags: %x"
+ "[x-%ld] "
+ "[x-x] "
+ "\\\\%s\\%s%c%s"
+ "add buf reader, len=%zu -> %d"
+ "add fread reader, len=%ld -> %d"
+ "add, session already expired"
+ "added %s decoder %s -> %d"
+ "added session for %s [proto=0x%x, valid_secs=%ld, alpn=%s, earlydata=%zu, quic_tp=%s], peer has %zu sessions now"
+ "added to multi, mid=%u, running=%u, total=%u"
+ "adding wanted h1"
+ "adding wanted h2"
+ "adding wanted h3"
+ "adjust_pollset, listening, POLLIN fd=%d"
+ "adjust_pollset, want_recv=%d want_send=%d"
+ "all previous attempts failed, starting %s"
+ "attempt to borrow xfer_sockbuf when already borrowed"
+ "aws_sigv4: Canonical request (enclosed in []) - [%s]"
+ "aws_sigv4: Signature - %s"
+ "aws_sigv4: String to sign (enclosed in []) - [%s]"
+ "aws_sigv4: picked region %.*s from host"
+ "aws_sigv4: picked service %.*s from host"
+ "best effort done"
+ "blksize parsed from OACK (%d) requested (%d)"
+ "body"
+ "buffered"
+ "buffered incomplete frame head"
+ "cannot complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), Unknown."
+ "cannot complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), request rejected because SOCKS server cannot connect to identd on the client."
+ "cannot complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), request rejected because the client program and identd report different user-ids."
+ "cannot complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), request rejected or failed."
+ "cannot complete SOCKS5 connection to %s. (%d)"
+ "cannot get the size of %s"
+ "cannot get the size of file."
+ "cannot open %s for writing"
+ "cannot read input"
+ "cannot resolve new host %s:%hu"
+ "cannot resolve proxy host %s:%hu"
+ "cf_shutdown -> %d, done=%d"
+ "cf_socket_close, fd=%d"
+ "cf_socket_shutdown, fd=%d"
+ "client mime read EOF fail, only %ld/%ld of needed bytes read"
+ "client read function EOF fail, only %ld/%ld of needed bytes read"
+ "client reader needs rewind before next request"
+ "client returned ERROR on write of %zu bytes"
+ "client side MAX_CONCURRENT_STREAMS reached, skip (%u)"
+ "client start, rewind readers"
+ "client_read(len=%zu) -> %d, nread=%zu, eos=%d"
+ "client_reset, clear readers"
+ "client_reset, will rewind reader"
+ "client_write(type=%x, len=%zu) -> %d"
+ "closing"
+ "closing connection #%ld"
+ "connect timeout"
+ "connect, all attempts failed"
+ "connect, check %s"
+ "connection"
+ "content"
+ "control code detected in .netrc credentials"
+ "could not allocate xfer_sockbuf of %zu bytes"
+ "cr_buf_read(len=%zu) -> 0, nread=%zu, eos=%d"
+ "cr_in, rewind via fseek -> %d(%d)"
+ "cr_in, rewind via set.ioctl_func -> %d"
+ "cr_in, rewind via set.seek_func -> %d"
+ "cr_in_read(len=%zu, total=%ld, read=%ld) -> %d, nread=%zu, eos=%d"
+ "cr_in_read, callback returned CURL_READFUNC_PAUSE"
+ "cr_lc_read(len=%zu) -> %d, nread=%zu, eos=%d"
+ "cr_mime_read(len=%zu) is errored -> %d, eos=0"
+ "cr_mime_read(len=%zu) seen eos -> 0, eos=1"
+ "cr_mime_read(len=%zu), mime_read() -> %zd"
+ "cr_mime_read(len=%zu), paused by callback"
+ "cr_mime_read(len=%zu), small read, using tmp"
+ "cr_mime_read(len=%zu, total=%ld, read=%ld) -> %d, %zu, %d"
+ "crypto engine not set, cannot load certificate"
+ "crypto engine not set, cannot load private key"
+ "curl_multi_fdset"
+ "curl_multi_waitfds"
+ "curl_sa_addr inet_ntop() failed with errno %d: %s"
+ "curl_ws_recv(len=%zu) -> %zu bytes (frame at %ld, %ld left)"
+ "curl_ws_recv, added %zu bytes from network"
+ "curl_ws_send(len=%zu, fragsize=%ld, flags=%x), raw=%d"
+ "curl_ws_send(len=%zu, fragsize=%ld, flags=%x, raw=%d) -> %d, %zu"
+ "cw-pause"
+ "decoded"
+ "decoded %s [%s%s payload=%ld/%ld]"
+ "decoded %s [%s%s]"
+ "decoded %s [%s%s](%d/%d)"
+ "decoder not requested, ignored: %.*s"
+ "deferred handshake %s: %dms"
+ "dns"
+ "doh"
+ "download_write body(type=%x, blen=%zu) -> %d"
+ "download_write body(type=%x, blen=%zu), did not want a BODY"
+ "download_write header(type=%x, blen=%zu) -> %d"
+ "ecdsa-with-SHA224"
+ "ecdsa-with-SHA256"
+ "ecdsa-with-SHA384"
+ "ecdsa-with-SHA512"
+ "end of response with %ld bytes missing"
+ "ev %s, call(fd=%d, ev=REMOVE)"
+ "ev assess"
+ "ev entry fd=%d, added %s #%ld, total=%u/%d (xfer/conn)"
+ "ev entry fd=%d, conn lost interest but is not registered"
+ "ev entry fd=%d, removed transfer, total=%u/%d (xfer/conn)"
+ "ev entry fd=%d, transfer lost interest but is not registered"
+ "ev new entry fd=%d"
+ "ev update call(fd=%d, ev=%s%s)"
+ "ev update fd=%d, action '%s%s' -> '%s%s' (%d/%d r/w)"
+ "ezm:doh-p"
+ "file://%s%s%s%s%s"
+ "find peer slot for %s among %zu slots"
+ "first aws-sigv4 provider cannot be empty"
+ "flush -> %d, connection-window=%d, nw_send_buffer(%zu)"
+ "flush EAGAIN, %zu bytes remain in buffer"
+ "flushed %zu bytes"
+ "force "
+ "found"
+ "ftp server does not support SIZE"
+ "ftp_initiate_transfer()"
+ "getFTPResponse -> result=%d, nread=%zd, ftpcode=%d"
+ "getFTPResponse start"
+ "hard timeout of %dms reached, starting %s"
+ "header"
+ "header_collect pushed(type=%x, len=%zu) -> %d"
+ "hostname"
+ "hostname: %s"
+ "http/2 recv on a transfer never opened or already cleared, mid=%u"
+ "http_chunk error, expected 0x0a, seeing 0x%ux"
+ "http_chunk, added last chunk with trailers from client -> %d"
+ "http_chunk, added last, empty chunk"
+ "http_chunk, made chunk of %zu bytes -> %d"
+ "http_chunk, response complete"
+ "http_chunked, chunk start of %ld bytes"
+ "http_chunked, write %zu body bytes, %ld bytes in chunk remain"
+ "https_proxy"
+ "ignoring duplicate 'chunked' decoder"
+ "in shutdown, waiting for server response"
+ "increased xfer table size to %u"
+ "init threaded resolve of %s:%d"
+ "invalid chunk size: '%s'"
+ "invalid easy handle in xfer table for mid=%u"
+ "is_resolved() result=%d, dns=%sfound"
+ "last user gone"
+ "libcurl/8.14.1"
+ "localhost."
+ "looking for %s decoder: %.*s"
+ "master easy %u already gone."
+ "master easy %u without sub_xfer_done callback."
+ "meta:mev:ps"
+ "meta:proto:file:easy"
+ "meta:proto:ftp:conn"
+ "meta:proto:ftp:easy"
+ "meta:proto:imap:conn"
+ "meta:proto:imap:easy"
+ "meta:proto:mqtt:conn"
+ "meta:proto:mqtt:easy"
+ "meta:proto:pop3:conn"
+ "meta:proto:pop3:easy"
+ "meta:proto:rtsp:conn"
+ "meta:proto:rtsp:easy"
+ "meta:proto:smb:conn"
+ "meta:proto:smb:easy"
+ "meta:proto:smtp:conn"
+ "meta:proto:smtp:easy"
+ "meta:proto:telnet:easy"
+ "meta:proto:tftp:conn"
+ "meta:proto:ws:conn"
+ "missing"
+ "mqtt_ping: sent ping request."
+ "multi changed, check CONNECT_PEND queue"
+ "multi_cleanup, closing admin handle, done"
+ "multi_done, not reusing connection=%ld, forbid=%d, close=%d, premature=%d, conn_multiplex=%d"
+ "multi_done: status: %d prem: %d done: %d"
+ "multi_done_locked, in use=%u"
+ "multi_perform(running=%u)"
+ "multi_wait"
+ "necessary data rewind was not possible"
+ "need more input"
+ "needs flush"
+ "network"
+ "nghttp2 recv error %zd: %s"
+ "nghttp2 shuts down connection with error %d: %s"
+ "nghttp2_submit_goaway() failed: %s(%d)"
+ "no cached session for %s"
+ "no matching entry"
+ "no such file"
+ "not "
+ "nothing heard from the server yet"
+ "ossl_connect, done"
+ "ossl_connect, step1"
+ "ossl_connect, step2"
+ "ossl_connect, step3"
+ "ossl_populate_x509_store, path=%s, blob=%d"
+ "out of memory"
+ "passed %zd bytes payload, %ld remain"
+ "passing"
+ "pause buffer not large enough -> CURLE_TOO_LARGE"
+ "peer entry %zu key recovered: %s"
+ "peer not found for %s"
+ "progress ingress, session is closed"
+ "promise easy handle added to multi, mid=%u"
+ "protocol"
+ "read error getting mime data"
+ "received GOAWAY, error=%u, last_stream=%u"
+ "removed from multi, mid=%u, running=%u, total=%u"
+ "resolve thread failed init: %d"
+ "resolve thread started for of %s:%d"
+ "resolve, destroy async data, shared ref=%d"
+ "resolve, wait for thread to finish"
+ "s3-express"
+ "s3-outposts"
+ "send SSL close notify"
+ "sending"
+ "sending QUIT to close session"
+ "server requested blksize larger than allocated (%ld)"
+ "set filter for listen socket fd=%d ip=%s:%d"
+ "set next attempt to start in %ums"
+ "setopt 0x%x got bad argument"
+ "setting size while ignoring"
+ "shut down failed with %d"
+ "shut down not done yet"
+ "shut down successfully"
+ "shutdown -> %d, done=%d"
+ "shutdown and remove SSL, done -> %d"
+ "shutdown and remove SSL, start"
+ "shutdown done"
+ "shutdown read -> %zd, %d"
+ "shutdown start on%s connection"
+ "shutdown timeout"
+ "shutdown, error: %d"
+ "shutdown, send close notify"
+ "shutting down"
+ "smtp_disconnect(), finished"
+ "smtp_do() -> %d, done=%d"
+ "smtp_doing() -> %d, done=%d"
+ "smtp_done(status=%d, premature=%d) -> %d"
+ "smtp_perform() -> %d, connected=%d, done=%d"
+ "smtp_perform(), start"
+ "smtp_regular_transfer() -> %d, done=%d"
+ "smtp_setup_connection() -> %d"
+ "socket done"
+ "socket_check -> %x"
+ "soft timeout of %dms reached, %s has not seen any data, starting %s"
+ "ssl engine did not initialized the certificate properly."
+ "ssl_cf_set_earlydata(len=%zu) -> %zd"
+ "starting new resolve, with previous not cleaned up"
+ "state change from %s to %s"
+ "sub xfer done for master %u"
+ "suppressing chunked transfer encoding on connection using HTTP version 2 or higher"
+ "switching connection to HTTP/2"
+ "syntax error"
+ "threaded: is_resolved(), already done, dns=%sfound"
+ "tls-server-end-point:"
+ "tls:ossl:x509:share"
+ "too many IP, cannot show"
+ "took session for %s [proto=0x%x, alpn=%s, earlydata=%zu, quic_tp=%s], %zu sessions remain"
+ "trailers"
+ "transfer"
+ "transfer would use an invalid scache at %p, denied"
+ "tsize parsed from OACK (%ld)"
+ "un"
+ "unable to add scache peer: %d"
+ "unknown sub request done"
+ "unstructuredName"
+ "unsupported transport %d in SSL init"
+ "upgrading connection to HTTP/2"
+ "user + domain + hostname too big"
+ "websocket"
+ "ws"
+ "ws-decode"
+ "ws_proxy"
+ "ws_send_raw(len=%zu) -> %d, %zu"
+ "ws_send_raw_blocking() partial, %zu left to send"
+ "wss"
+ "wss_proxy"
+ "x-%.*s-content-sha256"
+ "x-%.*s-content-sha256: %s"
+ "x-%.*s-date:%s"
+ "xfer_write_resp(len=%zu, eos=%d) -> %d"
+ "yes"
- "%10s %512s %u %10s %512s %u \"%64[^\"]\" %u %u"
- "%25"
- "%256s \"%64[^\"]\""
- "%64[^:]:%64[^:]:%64[^:]:%64s"
- "%s %s%s%s %u %s %s%s%s %u \"%d%02d%02d %02d:%02d:%02d\" %u %d\n"
- "%s (%d) %s (%d)"
- "%s (%ld)"
- "%s/%s/%s/%s"
- "%s4%s"
- "%s4-HMAC-SHA256\n%s\n%s\n%s"
- "%s4_request"
- "%s://%s%s%s%s%s%s%s%s%s%s%s%s%s%s"
- "%u/%ld/%s"
- ".netrc parser error"
- "/.."
- "/../"
- "/..?"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/curl/curl/lib/vtls/openssl.c"
- "/dev/urandom"
- "0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ"
- "0123456789abcdef"
- "0123456789abcdefghijklmnopqrstuvwxyz"
- "1.2.0.4"
- "8.7.1"
- "A required function in the library was not found"
- "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/"
- "ADH-AES128-GCM-SHA256"
- "ADH-AES128-SHA"
- "ADH-AES128-SHA256"
- "ADH-AES256-GCM-SHA384"
- "ADH-AES256-SHA"
- "ADH-AES256-SHA256"
- "ADH-DES-CBC-SHA"
- "ADH-DES-CBC3-SHA"
- "ADH-RC4-MD5"
- "AECDH-AES128-SHA"
- "AECDH-AES256-SHA"
- "AECDH-DES-CBC3-SHA"
- "AECDH-NULL-SHA"
- "AECDH-RC4-SHA"
- "AES128-GCM-SHA256"
- "AES128-SHA"
- "AES128-SHA256"
- "AES256-GCM-SHA384"
- "AES256-SHA"
- "AES256-SHA256"
- "APPEND %s (\\Seen) {%ld}"
- "Added %.*s:%d:%s to DNS cache%s"
- "Added alt-svc: %s:%d over %s"
- "Authentication problem. Ignoring this."
- "Authorization: %s4-HMAC-SHA256 Credential=%s/%s, SignedHeaders=%s, Signature=%s\r\n%s%s"
- "Bad syntax CURLOPT_RESOLVE removal entry '%s'"
- "CLIENT libcurl 8.7.1\r\n%s\r\nQUIT\r\n"
- "CLIENT libcurl 8.7.1\r\nDEFINE %s %s\r\nQUIT\r\n"
- "CLIENT libcurl 8.7.1\r\nMATCH %s %s %s\r\nQUIT\r\n"
- "Can not multiplex, even if we wanted to"
- "Can't complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), Unknown."
- "Can't complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), request rejected because SOCKS server cannot connect to identd on the client."
- "Can't complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), request rejected because the client program and identd report different user-ids."
- "Can't complete SOCKS4 connection to %d.%d.%d.%d:%d. (%d), request rejected or failed."
- "Can't complete SOCKS5 connection to %s. (%d)"
- "Can't get the size of %s"
- "Can't get the size of file."
- "Can't open %s for writing"
- "Can't resolve new host %s:%hu"
- "Can't resolve proxy host %s:%hu"
- "Checking for server connect"
- "Closing connection"
- "Connection #%ld isn't open enough, can't reuse"
- "Connection cache is full, closing the oldest one"
- "Could multiplex, but not asked to"
- "Could not resolve host: %s"
- "Couldn't bind to '%s'"
- "Couldn't bind to interface '%s'"
- "Couldn't connect to server"
- "Couldn't read a file:// file"
- "Couldn't resolve host name"
- "Couldn't resolve proxy '%s'"
- "Couldn't resolve proxy name"
- "Couldn't resume download"
- "Couldn't use specified SSL cipher"
- "Curl_conn_tcp_listen_set(%d)"
- "DES-CBC-SHA"
- "DES-CBC3-SHA"
- "DH-DSS-AES128-GCM-SHA256"
- "DH-DSS-AES128-SHA"
- "DH-DSS-AES128-SHA256"
- "DH-DSS-AES256-GCM-SHA384"
- "DH-DSS-AES256-SHA"
- "DH-DSS-AES256-SHA256"
- "DH-DSS-DES-CBC-SHA"
- "DH-DSS-DES-CBC3-SHA"
- "DH-RSA-AES128-GCM-SHA256"
- "DH-RSA-AES128-SHA"
- "DH-RSA-AES128-SHA256"
- "DH-RSA-AES256-GCM-SHA384"
- "DH-RSA-AES256-SHA"
- "DH-RSA-AES256-SHA256"
- "DH-RSA-DES-CBC-SHA"
- "DH-RSA-DES-CBC3-SHA"
- "DHE-DSS-AES128-GCM-SHA256"
- "DHE-DSS-AES128-SHA"
- "DHE-DSS-AES128-SHA256"
- "DHE-DSS-AES256-GCM-SHA384"
- "DHE-DSS-AES256-SHA"
- "DHE-DSS-AES256-SHA256"
- "DHE-DSS-DES-CBC3-SHA"
- "DHE-PSK-3DES-EDE-CBC-SHA"
- "DHE-PSK-AES128-CBC-SHA"
- "DHE-PSK-AES128-CBC-SHA256"
- "DHE-PSK-AES128-GCM-SHA256"
- "DHE-PSK-AES256-CBC-SHA"
- "DHE-PSK-AES256-CBC-SHA384"
- "DHE-PSK-AES256-GCM-SHA384"
- "DHE-PSK-NULL-SHA"
- "DHE-PSK-NULL-SHA256"
- "DHE-PSK-NULL-SHA384"
- "DHE-PSK-RC4-SHA"
- "DHE-RSA-AES128-GCM-SHA256"
- "DHE-RSA-AES128-SHA"
- "DHE-RSA-AES128-SHA256"
- "DHE-RSA-AES256-GCM-SHA384"
- "DHE-RSA-AES256-SHA"
- "DHE-RSA-AES256-SHA256"
- "DHE-RSA-DES-CBC3-SHA"
- "DICT"
- "DoH"
- "ECDH-ECDSA-AES128-GCM-SHA256"
- "ECDH-ECDSA-AES128-SHA"
- "ECDH-ECDSA-AES128-SHA256"
- "ECDH-ECDSA-AES256-GCM-SHA384"
- "ECDH-ECDSA-AES256-SHA"
- "ECDH-ECDSA-AES256-SHA384"
- "ECDH-ECDSA-DES-CBC3-SHA"
- "ECDH-ECDSA-NULL-SHA"
- "ECDH-ECDSA-RC4-SHA"
- "ECDH-RSA-AES128-GCM-SHA256"
- "ECDH-RSA-AES128-SHA"
- "ECDH-RSA-AES128-SHA256"
- "ECDH-RSA-AES256-GCM-SHA384"
- "ECDH-RSA-AES256-SHA"
- "ECDH-RSA-AES256-SHA384"
- "ECDH-RSA-DES-CBC3-SHA"
- "ECDH-RSA-NULL-SHA"
- "ECDH-RSA-RC4-SHA"
- "ECDHE-ECDSA-AES128-GCM-SHA256"
- "ECDHE-ECDSA-AES128-SHA"
- "ECDHE-ECDSA-AES128-SHA256"
- "ECDHE-ECDSA-AES256-GCM-SHA384"
- "ECDHE-ECDSA-AES256-SHA"
- "ECDHE-ECDSA-AES256-SHA384"
- "ECDHE-ECDSA-CHACHA20-POLY1305"
- "ECDHE-ECDSA-DES-CBC3-SHA"
- "ECDHE-ECDSA-NULL-SHA"
- "ECDHE-ECDSA-RC4-SHA"
- "ECDHE-PSK-AES128-CBC-SHA"
- "ECDHE-PSK-AES256-CBC-SHA"
- "ECDHE-RSA-AES128-GCM-SHA256"
- "ECDHE-RSA-AES128-SHA"
- "ECDHE-RSA-AES128-SHA256"
- "ECDHE-RSA-AES256-GCM-SHA384"
- "ECDHE-RSA-AES256-SHA"
- "ECDHE-RSA-AES256-SHA384"
- "ECDHE-RSA-CHACHA20-POLY1305"
- "ECDHE-RSA-DES-CBC3-SHA"
- "ECDHE-RSA-NULL-SHA"
- "ECDHE-RSA-RC4-SHA"
- "EDH-DSS-CBC-SHA"
- "EDH-RSA-DES-CBC-SHA"
- "EXP-ADH-DES-CBC-SHA"
- "EXP-ADH-RC4-MD5"
- "EXP-DES-CBC-SHA"
- "EXP-DH-DSS-DES-CBC-SHA"
- "EXP-DH-RSA-DES-CBC-SHA"
- "EXP-EDH-DSS-DES-CBC-SHA"
- "EXP-EDH-RSA-DES-CBC-SHA"
- "EXP-RC2-CBC-MD5"
- "EXP-RC4-MD5"
- "Excessive alt-svc header, ignoring."
- "Excessive alt-svc host name, ignoring."
- "Excessive user name length for proxy auth"
- "FTP: can't figure out the host in the PASV response"
- "FTP: couldn't retrieve (RETR failed) the specified file"
- "FTP: couldn't set file type"
- "FTPS"
- "Failed to determine user name."
- "Failed to resolve host '%s' with timeout after %ld ms"
- "Found bundle for host: %p [%s]"
- "GOPHER"
- "GOPHERS"
- "Got PUSH_PROMISE, ask application"
- "HTTP server doesn't seem to support byte ranges. Cannot resume."
- "HTTP/2 proxy, send again with decreased length"
- "HTTP/2 send again with decreased length (%zd vs %zd)"
- "HTTPS"
- "Hostname '%s' was found"
- "Hostname in DNS cache doesn't have needed family, zapped"
- "IDEA-CBC-SHA"
- "IMAP"
- "IMAPS"
- "Internal problem setting up the POST"
- "LDAP"
- "LDAPS"
- "Last-Modified: %s, %02d %s %4d %02d:%02d:%02d GMT\r\n%s"
- "LibreSSL SSL_read on shutdown: %s, errno %d"
- "MAX_CONCURRENT_STREAMS reached, skip (%zu)"
- "MQTT"
- "NTML"
- "NULL-MD5"
- "NULL-SHA"
- "NULL-SHA256"
- "No connections available in cache"
- "No connections available."
- "No known authentication mechanisms supported"
- "No more connections allowed to host: %zu"
- "POP3"
- "POP3S"
- "PSK-3DES-EDE-CBC-SHA"
- "PSK-AES128-CBC-SHA"
- "PSK-AES128-CBC-SHA256"
- "PSK-AES128-GCM-SHA256"
- "PSK-AES256-CBC-SHA"
- "PSK-AES256-CBC-SHA384"
- "PSK-AES256-GCM-SHA384"
- "PSK-CHACHA20-POLY1305"
- "PSK-NULL-SHA"
- "PSK-NULL-SHA256"
- "PSK-NULL-SHA384"
- "PSK-RC4-SHA"
- "Password is too large: [%zu]"
- "Preparing for accepting server on data port"
- "RC4-MD5"
- "RC4-SHA"
- "RESOLVE %.*s:%d - old addresses discarded"
- "RESOLVE *:%d using wildcard"
- "RSA-PSK-3DES-EDE-CBC-SHA"
- "RSA-PSK-AES128-CBC-SHA"
- "RSA-PSK-AES128-CBC-SHA256"
- "RSA-PSK-AES128-GCM-SHA256"
- "RSA-PSK-AES256-CBC-SHA"
- "RSA-PSK-AES256-CBC-SHA384"
- "RSA-PSK-AES256-GCM-SHA384"
- "RSA-PSK-NULL-SHA"
- "RSA-PSK-NULL-SHA256"
- "RSA-PSK-NULL-SHA384"
- "RSA-PSK-RC4-SHA"
- "RTSP"
- "Re-using existing connection with %s %s"
- "Remove session ID again from cache"
- "SMB"
- "SMBS"
- "SMTPS"
- "SOCKS4: too long host name"
- "SOCKS5: hostname '%s' found"
- "SSL Engine '%s' not found"
- "SSL connection timeout"
- "SSL shutdown sent"
- "SSL shutdown, EOF from server"
- "SSL shutdown, error: '%s', errno %d"
- "SSL versions not supported"
- "SSL: Can't find the certificate \"%s\" and its private key in the Keychain."
- "SSL: Can't load the certificate \"%s\" and its private key: OSStatus %d"
- "SSL: Failed to allocate memory for all ciphers"
- "SSL: Failed to allocate memory for allowed ciphers"
- "SSL: SSLGetNumberSupportedCiphers() failed: OSStatus %d"
- "SSL: SSL_set_session failed: %s"
- "SSL: Setting cipher suites list \"%s\""
- "SSL: can't load CA certificate file %s"
- "SSL: certificate subject name '%s' does not match target host name '%s'"
- "SSL: cipher string \"%s\" contains unsupported cipher name starting position %zd and ending position %zd"
- "SSL: couldn't allocate %zu bytes of memory"
- "SSL: couldn't create a context"
- "SSL: couldn't create a context (handle)"
- "SSL: couldn't create a context: %s"
- "SSL: couldn't get X509-issuer name"
- "SSL: couldn't get peer certificate"
- "SSL_get_shutdown() returned SSL_RECEIVED_SHUTDOWN"
- "SSL_get_shutdown() returned SSL_SENT_SHUTDOWN"
- "SSL_get_shutdown() returned SSL_SENT_SHUTDOWN|SSL_RECEIVED__SHUTDOWN"
- "Server didn't accept auth data"
- "Server doesn't support multiplex (yet)"
- "Server doesn't support multiplex yet, wait"
- "Server upgrade doesn't support multiplex yet, wait"
- "Switch from POST to GET"
- "Switch to %s"
- "TELNET"
- "TFTP"
- "TFTP file name too long"
- "TLS_AES_128_CCM_8_SHA256"
- "TLS_AES_128_CCM_SHA256"
- "TLS_AES_128_GCM_SHA256"
- "TLS_AES_256_GCM_SHA384"
- "TLS_CHACHA20_POLY1305_SHA256"
- "TLS_DHE_DSS_EXPORT_WITH_DES40_CBC_SHA"
- "TLS_DHE_DSS_WITH_3DES_EDE_CBC_SHA"
- "TLS_DHE_DSS_WITH_AES_128_CBC_SHA"
- "TLS_DHE_DSS_WITH_AES_128_CBC_SHA256"
- "TLS_DHE_DSS_WITH_AES_128_GCM_SHA256"
- "TLS_DHE_DSS_WITH_AES_256_CBC_SHA"
- "TLS_DHE_DSS_WITH_AES_256_CBC_SHA256"
- "TLS_DHE_DSS_WITH_AES_256_GCM_SHA384"
- "TLS_DHE_DSS_WITH_DES_CBC_SHA"
- "TLS_DHE_PSK_WITH_3DES_EDE_CBC_SHA"
- "TLS_DHE_PSK_WITH_AES_128_CBC_SHA"
- "TLS_DHE_PSK_WITH_AES_128_CBC_SHA256"
- "TLS_DHE_PSK_WITH_AES_128_GCM_SHA256"
- "TLS_DHE_PSK_WITH_AES_256_CBC_SHA"
- "TLS_DHE_PSK_WITH_AES_256_CBC_SHA384"
- "TLS_DHE_PSK_WITH_AES_256_GCM_SHA384"
- "TLS_DHE_PSK_WITH_NULL_SHA"
- "TLS_DHE_PSK_WITH_NULL_SHA256"
- "TLS_DHE_PSK_WITH_NULL_SHA384"
- "TLS_DHE_PSK_WITH_RC4_128_SHA"
- "TLS_DHE_RSA_EXPORT_WITH_DES40_CBC_SHA"
- "TLS_DHE_RSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_DHE_RSA_WITH_AES_128_CBC_SHA"
- "TLS_DHE_RSA_WITH_AES_128_CBC_SHA256"
- "TLS_DHE_RSA_WITH_AES_128_GCM_SHA256"
- "TLS_DHE_RSA_WITH_AES_256_CBC_SHA"
- "TLS_DHE_RSA_WITH_AES_256_CBC_SHA256"
- "TLS_DHE_RSA_WITH_AES_256_GCM_SHA384"
- "TLS_DHE_RSA_WITH_DES_CBC_SHA"
- "TLS_DH_DSS_EXPORT_WITH_DES40_CBC_SHA"
- "TLS_DH_DSS_WITH_3DES_EDE_CBC_SHA"
- "TLS_DH_DSS_WITH_AES_128_CBC_SHA"
- "TLS_DH_DSS_WITH_AES_128_CBC_SHA256"
- "TLS_DH_DSS_WITH_AES_128_GCM_SHA256"
- "TLS_DH_DSS_WITH_AES_256_CBC_SHA"
- "TLS_DH_DSS_WITH_AES_256_CBC_SHA256"
- "TLS_DH_DSS_WITH_AES_256_GCM_SHA384"
- "TLS_DH_DSS_WITH_DES_CBC_SHA"
- "TLS_DH_RSA_EXPORT_WITH_DES40_CBC_SHA"
- "TLS_DH_RSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_DH_RSA_WITH_AES_128_CBC_SHA"
- "TLS_DH_RSA_WITH_AES_128_CBC_SHA256"
- "TLS_DH_RSA_WITH_AES_128_GCM_SHA256"
- "TLS_DH_RSA_WITH_AES_256_CBC_SHA"
- "TLS_DH_RSA_WITH_AES_256_CBC_SHA256"
- "TLS_DH_RSA_WITH_AES_256_GCM_SHA384"
- "TLS_DH_RSA_WITH_DES_CBC_SHA"
- "TLS_DH_anon_EXPORT_WITH_DES40_CBC_SHA"
- "TLS_DH_anon_EXPORT_WITH_RC4_40_MD5"
- "TLS_DH_anon_WITH_3DES_EDE_CBC_SHA"
- "TLS_DH_anon_WITH_AES_128_CBC_SHA"
- "TLS_DH_anon_WITH_AES_128_CBC_SHA256"
- "TLS_DH_anon_WITH_AES_128_GCM_SHA256"
- "TLS_DH_anon_WITH_AES_256_CBC_SHA"
- "TLS_DH_anon_WITH_AES_256_CBC_SHA256"
- "TLS_DH_anon_WITH_AES_256_GCM_SHA384"
- "TLS_DH_anon_WITH_DES_CBC_SHA"
- "TLS_DH_anon_WITH_RC4_128_MD5"
- "TLS_ECDHE_ECDSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_ECDHE_ECDSA_WITH_AES_128_CBC_SHA"
- "TLS_ECDHE_ECDSA_WITH_AES_128_CBC_SHA256"
- "TLS_ECDHE_ECDSA_WITH_AES_128_GCM_SHA256"
- "TLS_ECDHE_ECDSA_WITH_AES_256_CBC_SHA"
- "TLS_ECDHE_ECDSA_WITH_AES_256_CBC_SHA384"
- "TLS_ECDHE_ECDSA_WITH_AES_256_GCM_SHA384"
- "TLS_ECDHE_ECDSA_WITH_CHACHA20_POLY1305_SHA256"
- "TLS_ECDHE_ECDSA_WITH_NULL_SHA"
- "TLS_ECDHE_ECDSA_WITH_RC4_128_SHA"
- "TLS_ECDHE_PSK_WITH_AES_128_CBC_SHA"
- "TLS_ECDHE_PSK_WITH_AES_256_CBC_SHA"
- "TLS_ECDHE_RSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_ECDHE_RSA_WITH_AES_128_CBC_SHA"
- "TLS_ECDHE_RSA_WITH_AES_128_CBC_SHA256"
- "TLS_ECDHE_RSA_WITH_AES_128_GCM_SHA256"
- "TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA"
- "TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384"
- "TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384"
- "TLS_ECDHE_RSA_WITH_CHACHA20_POLY1305_SHA256"
- "TLS_ECDHE_RSA_WITH_NULL_SHA"
- "TLS_ECDHE_RSA_WITH_RC4_128_SHA"
- "TLS_ECDH_ECDSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_ECDH_ECDSA_WITH_AES_128_CBC_SHA"
- "TLS_ECDH_ECDSA_WITH_AES_128_CBC_SHA256"
- "TLS_ECDH_ECDSA_WITH_AES_128_GCM_SHA256"
- "TLS_ECDH_ECDSA_WITH_AES_256_CBC_SHA"
- "TLS_ECDH_ECDSA_WITH_AES_256_CBC_SHA384"
- "TLS_ECDH_ECDSA_WITH_AES_256_GCM_SHA384"
- "TLS_ECDH_ECDSA_WITH_NULL_SHA"
- "TLS_ECDH_ECDSA_WITH_RC4_128_SHA"
- "TLS_ECDH_RSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_ECDH_RSA_WITH_AES_128_CBC_SHA"
- "TLS_ECDH_RSA_WITH_AES_128_CBC_SHA256"
- "TLS_ECDH_RSA_WITH_AES_128_GCM_SHA256"
- "TLS_ECDH_RSA_WITH_AES_256_CBC_SHA"
- "TLS_ECDH_RSA_WITH_AES_256_CBC_SHA384"
- "TLS_ECDH_RSA_WITH_AES_256_GCM_SHA384"
- "TLS_ECDH_RSA_WITH_NULL_SHA"
- "TLS_ECDH_RSA_WITH_RC4_128_SHA"
- "TLS_ECDH_anon_WITH_3DES_EDE_CBC_SHA"
- "TLS_ECDH_anon_WITH_AES_128_CBC_SHA"
- "TLS_ECDH_anon_WITH_AES_256_CBC_SHA"
- "TLS_ECDH_anon_WITH_NULL_SHA"
- "TLS_ECDH_anon_WITH_RC4_128_SHA"
- "TLS_NULL_WITH_NULL_NULL"
- "TLS_PSK_WITH_3DES_EDE_CBC_SHA"
- "TLS_PSK_WITH_AES_128_CBC_SHA"
- "TLS_PSK_WITH_AES_128_CBC_SHA256"
- "TLS_PSK_WITH_AES_128_GCM_SHA256"
- "TLS_PSK_WITH_AES_256_CBC_SHA"
- "TLS_PSK_WITH_AES_256_CBC_SHA384"
- "TLS_PSK_WITH_AES_256_GCM_SHA384"
- "TLS_PSK_WITH_CHACHA20_POLY1305_SHA256"
- "TLS_PSK_WITH_NULL_SHA"
- "TLS_PSK_WITH_NULL_SHA256"
- "TLS_PSK_WITH_NULL_SHA384"
- "TLS_PSK_WITH_RC4_128_SHA"
- "TLS_RSA_EXPORT_WITH_DES40_CBC_SHA"
- "TLS_RSA_EXPORT_WITH_RC2_CBC_40_MD5"
- "TLS_RSA_EXPORT_WITH_RC4_40_MD5"
- "TLS_RSA_PSK_WITH_3DES_EDE_CBC_SHA"
- "TLS_RSA_PSK_WITH_AES_128_CBC_SHA"
- "TLS_RSA_PSK_WITH_AES_128_CBC_SHA256"
- "TLS_RSA_PSK_WITH_AES_128_GCM_SHA256"
- "TLS_RSA_PSK_WITH_AES_256_CBC_SHA"
- "TLS_RSA_PSK_WITH_AES_256_CBC_SHA384"
- "TLS_RSA_PSK_WITH_AES_256_GCM_SHA384"
- "TLS_RSA_PSK_WITH_NULL_SHA"
- "TLS_RSA_PSK_WITH_NULL_SHA256"
- "TLS_RSA_PSK_WITH_NULL_SHA384"
- "TLS_RSA_PSK_WITH_RC4_128_SHA"
- "TLS_RSA_WITH_3DES_EDE_CBC_SHA"
- "TLS_RSA_WITH_AES_128_CBC_SHA"
- "TLS_RSA_WITH_AES_128_CBC_SHA256"
- "TLS_RSA_WITH_AES_128_GCM_SHA256"
- "TLS_RSA_WITH_AES_256_CBC_SHA"
- "TLS_RSA_WITH_AES_256_CBC_SHA256"
- "TLS_RSA_WITH_AES_256_GCM_SHA384"
- "TLS_RSA_WITH_DES_CBC_SHA"
- "TLS_RSA_WITH_IDEA_CBC_SHA"
- "TLS_RSA_WITH_NULL_MD5"
- "TLS_RSA_WITH_NULL_SHA"
- "TLS_RSA_WITH_NULL_SHA256"
- "TLS_RSA_WITH_RC4_128_MD5"
- "TLS_RSA_WITH_RC4_128_SHA"
- "Too long SOCKS proxy user name"
- "Too long host name (maximum is %d)"
- "Transfer was pending, now try another"
- "Uploading to a URL without a file name"
- "Username is too large: [%zu]"
- "WARNING: using weak random seed"
- "WORKSTATION"
- "X-%s-Date"
- "[%d] cf_send(len=%zu) -> %zd, %d, upload_left=%ld, h2 windows %d-%d (stream-conn), buffers %zu-%zu (stream-conn)"
- "[%d] cf_send(len=%zu) BLOCK: win %u/%zu blocked_len=%zu"
- "[%d] cf_send(len=%zu) BLOCK: win %u/%zu hds_len=%zu blocked_len=%zu"
- "[%d] data done send"
- "[%d] egress blocked, DRAIN"
- "[%d] remote flow window is exhausted"
- "[%d] req_body_read(len=%zu) left=%ld -> %zd, %d"
- "[%zd-%zd], http/2 recv on a transfer never opened or already cleared"
- "[DoH] AAAA: "
- "[DoH] Host name: %s"
- "\\\\"
- "_proxy"
- "aws-sigv4: region too long in hostname"
- "aws-sigv4: service too long in hostname"
- "aws-sigv4: too many query pairs in URL"
- "aws_sigv4: picked region %s from host"
- "aws_sigv4: picked service %s from host"
- "blksize parsed from OACK"
- "buffered %zd additional bytes"
- "can multiplex"
- "cf_socket_close(%d)"
- "chunk hex-length not valid: '%s'"
- "client mime read EOF fail, only only %ld/%ld of needed bytes read"
- "client read function EOF fail, only only %ld/%ld of needed bytes read"
- "client side MAX_CONCURRENT_STREAMS reached, skip (%zu)"
- "connect, all failed"
- "connect, check h21"
- "crypto engine not set, can't load certificate"
- "crypto engine not set, can't load private key"
- "download"
- "failed to store ssl session"
- "file://%s%s%s"
- "first aws-sigv4 provider can't be empty"
- "ftp server doesn't support SIZE"
- "ftp_perform ends with SECONDARY: %d"
- "h21"
- "hard timeout of %dms reached, starting h21"
- "host name"
- "host!"
- "initialization failure, transfer not http initialized"
- "libcurl/8.7.1"
- "max-age="
- "necessary data rewind wasn't possible"
- "not from sending TLS shutdown on connection closed by peer"
- "nw_in_read(len=%zu, fd=%d) -> %d, err=%d"
- "old SSL session ID is stale, removing"
- "partial read: empty buffer first"
- "peer has shutdown TLS"
- "populate_x509_store, path=%s, blob=%d"
- "read: %s"
- "received GOAWAY, error=%d, last_stream=%u"
- "recv from buffer"
- "requested"
- "sa_addr inet_ntop() failed with errno %d: %s"
- "select/poll returned error"
- "serially"
- "server requested blksize larger than allocated"
- "soft timeout of %dms reached, h3 has not seen any data, starting h21"
- "space-separated NOPROXY patterns are deprecated"
- "ssl engine didn't initialized the certificate properly."
- "too many IP, can't show"
- "tsize parsed from OACK"
- "unsupported max version passed via CURLOPT_SSLVERSION"
- "unsupported min version passed via CURLOPT_SSLVERSION"
- "user + domain + host name too big"
- "x-%s-content-sha256"
- "x-%s-content-sha256: %s"
- "x-%s-date:%s"
- "xn--"
```
