## librdma.dylib

> `/usr/lib/librdma.dylib`

```diff

-112.40.17.0.0
-  __TEXT.__text: 0x0
+112.60.8.0.0
+  __TEXT.__text: 0x22c0
+  __TEXT.__cstring: 0x751
+  __TEXT.__unwind_info: 0x100
+  __TEXT.__auth_stubs: 0x0
+  __DATA_CONST.__got: 0x0
+  __AUTH_CONST.__auth_got: 0xd0
+  __AUTH.__thread_vars: 0x18
+  __AUTH.__thread_data: 0x100
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/rdma/libibmad.dylib
   - /usr/lib/rdma/libibumad.dylib

   - /usr/lib/rdma/librdmacm.dylib
   - /usr/lib/rdma/librxe.dylib
   - /usr/lib/rdma/libthunderboltrdma.dylib
-  Functions: 0
-  Symbols:   0
-  CStrings:  0
+  Functions: 33
+  Symbols:   64
+  CStrings:  53
 
Symbols:
+ ___chkstk_darwin
+ ___error
+ ___stack_chk_fail
+ ___stack_chk_guard
+ ___strlcpy_chk
+ __tlv_bootstrap
+ _arc4random_buf
+ _bzero
+ _cfg_add_address
+ _cfg_add_ipsecif
+ _cfg_addr_to_string
+ _cfg_conn_check
+ _cfg_dump
+ _cfg_fail
+ _cfg_msg_append
+ _cfg_parse_addr
+ _cfg_pol_ext
+ _cfg_rekey
+ _cfg_sa_ext
+ _cfg_send
+ _close
+ _fcntl
+ _free
+ _getpid
+ _inet_ntop
+ _inet_pton
+ _ioctl
+ _ipsec_cfg_connect
+ _ipsec_cfg_disconnect
+ _ipsec_cfg_errbuf
+ _ipsec_cfg_errbuf$tlv$init
+ _ipsec_cfg_events_close
+ _ipsec_cfg_events_fd
+ _ipsec_cfg_events_open
+ _ipsec_cfg_events_read
+ _ipsec_cfg_flush
+ _ipsec_cfg_keygen
+ _ipsec_cfg_offload_generation
+ _ipsec_cfg_policy_add
+ _ipsec_cfg_policy_del
+ _ipsec_cfg_policy_list
+ _ipsec_cfg_policy_list_free
+ _ipsec_cfg_rekey_in
+ _ipsec_cfg_rekey_out
+ _ipsec_cfg_sa_add
+ _ipsec_cfg_sa_del
+ _ipsec_cfg_sa_list
+ _ipsec_cfg_sa_list_free
+ _ipsec_cfg_strerror
+ _ipsec_cfg_supported
+ _malloc_type_calloc
+ _malloc_type_realloc
+ _memcpy
+ _read
+ _setsockopt
+ _snprintf
+ _socket
+ _strchr
+ _strerror
+ _strlcpy
+ _strtol
+ _sysctlbyname
+ _vsnprintf
+ _write
CStrings:
+ "%s/%u"
+ "%s: cannot open PF_KEY socket: %s (are you root?)"
+ "%s: kernel refused: %s"
+ "%s: out of memory"
+ "%s: read from PF_KEY: %s"
+ "%s: write to PF_KEY: %s"
+ "PF_KEY message too large"
+ "SA add"
+ "SA delete"
+ "SA dump"
+ "SA flush"
+ "SIOCGIFCAP(%s): %s"
+ "SPI %u is reserved (must be > 255)"
+ "address is NULL"
+ "address too long: %s"
+ "bad prefix length: %s"
+ "buf is NULL"
+ "cannot allocate event handle"
+ "cannot open PF_KEY socket: %s (events require root)"
+ "cannot register for PF_KEY notifications: %s"
+ "cannot set O_NONBLOCK: %s"
+ "conn is NULL"
+ "direction must be OUT or IN"
+ "ev is NULL"
+ "ev or out is NULL"
+ "ifname is NULL"
+ "interface name too long: %s"
+ "key length %zu is not %d (GCM-128) or %d (GCM-256)"
+ "key_out and key_in are required"
+ "local_ip and remote_ip are required"
+ "net.key.offload_flush_generation"
+ "net.key.offload_flush_generation: %s (kernel may predate offload teardown notification)"
+ "new_key is NULL"
+ "not an IP address: %s"
+ "out and count are required"
+ "out is NULL"
+ "outbound and inbound reqid collide (%u); set reqid_out/reqid_in explicitly"
+ "policy add"
+ "policy delete"
+ "policy dump"
+ "policy flush"
+ "policy is NULL"
+ "read from PF_KEY: %s"
+ "replay_window %u does not fit in the 8-bit kernel field and would truncate to %u, silently disabling anti-replay; this is a size in BYTES (4/8/16/32), not a packet count"
+ "replay_window %u is not one of 4/8/16/32 bytes, which are the widths offload supports"
+ "replay_window requires esn when offloading (the hardware rejects non-ESN replay protection); either set esn, clear replay_window, or handle this SA in software"
+ "reqid %u exceeds the maximum userspace may set (%u); the kernel would discard it and the policy would not bind to this SA"
+ "reqid %u exceeds the maximum userspace may set (%u); the kernel would replace it and this policy would not bind to its SA"
+ "reqid must be nonzero (it is what binds this policy to its SA)"
+ "sa is NULL"
+ "sa->key is NULL"
+ "socket: %s"
+ "source and destination families differ"
```
