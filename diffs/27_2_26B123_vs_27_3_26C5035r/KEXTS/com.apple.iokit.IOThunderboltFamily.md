## com.apple.iokit.IOThunderboltFamily

> `com.apple.iokit.IOThunderboltFamily`

```diff

-6834.40.2.0.0
-  __TEXT.__cstring: 0x4ada2
-  __TEXT.__os_log: 0x3bd4b
+6834.60.3.0.0
+  __TEXT.__cstring: 0x4ae4f
+  __TEXT.__os_log: 0x3bdf8
   __TEXT.__const: 0xb54
-  __TEXT_EXEC.__text: 0x1d1e44
+  __TEXT_EXEC.__text: 0x1d2000
   __TEXT_EXEC.__auth_stubs: 0xab0
   __DATA.__data: 0xc42
   __DATA.__common: 0x1600

   __DATA_CONST.__kalloc_var: 0xcd0
   __DATA_CONST.__auth_got: 0x558
   __DATA_CONST.__got: 0x168
-  Functions: 7380
-  Symbols:   11590
-  CStrings:  3742
+  Functions: 7381
+  Symbols:   11592
+  CStrings:  3743
 
Symbols:
+ __ZN26IOThunderboltConfigCommand24isTopologyDiscoveryProbeEv
+ __ZN30IOThunderboltConfigReadCommand24isTopologyDiscoveryProbeEv
+ __ZZN26IOThunderboltConfigCommand15processResponseEP27IOThunderboltReceiveCommandE11_os_log_fmt__10_
- __ZN26IOThunderboltConfigCommand36_RESERVEDIOThunderboltConfigCommand0Ev
Functions:
+ __ZN30IOThunderboltConfigReadCommand24isTopologyDiscoveryProbeEv
- __ZN26IOThunderboltConfigCommand37_RESERVEDIOThunderboltConfigCommand31Ev
~ __ZN26IOThunderboltConfigCommand15processResponseEP27IOThunderboltReceiveCommand : 3692 -> 4096
+ __ZN26IOThunderboltConfigCommand24isTopologyDiscoveryProbeEv
CStrings:
+ "%lldus IOThunderboltConfigCommand - error_code = %d exact_match = %d not_exact_match = %d error_port_in_route = %d foreign_topology_id = %d command_status = %d\n"
+ "%lldus IOThunderboltConfigCommand - route mismatch on foreign topology ID for a topology discovery probe - treating as inconclusive, not rejecting\n"
+ "01:13:29"
+ "Oct 30 2026"
- "%lldus IOThunderboltConfigCommand - error_code = %d exact_match = %d not_exact_match = %d error_port_in_route = %d command_status = %d\n"
- "23:04:59"
- "Oct 14 2026"
```
