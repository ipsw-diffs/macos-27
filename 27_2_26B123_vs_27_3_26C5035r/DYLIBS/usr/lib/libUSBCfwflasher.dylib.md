## libUSBCfwflasher.dylib

> `/usr/lib/libUSBCfwflasher.dylib`

```diff

 40.0.0.0.0
-  __TEXT.__text: 0x24f04
+  __TEXT.__text: 0x2505c
   __TEXT.__init_offsets: 0x18
   __TEXT.__objc_methlist: 0x4fc
-  __TEXT.__cstring: 0x9130
-  __TEXT.__const: 0x1680
+  __TEXT.__cstring: 0x8fbb
   __TEXT.__gcc_except_tab: 0x6e0
-  __TEXT.__oslogstring: 0x270f
-  __TEXT.__unwind_info: 0xa20
+  __TEXT.__const: 0x1670
+  __TEXT.__oslogstring: 0x27bb
+  __TEXT.__unwind_info: 0xa28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__got: 0x108
   __AUTH_CONST.__const: 0x238
-  __AUTH_CONST.__cfstring: 0x3160
+  __AUTH_CONST.__cfstring: 0x3020
   __AUTH_CONST.__objc_const: 0x720
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0x30

   __AUTH.__objc_data: 0x190
   __DATA.__objc_ivar: 0x6c
   __DATA.__data: 0x420
-  __DATA.__bss: 0x768
+  __DATA.__bss: 0x770
   __DATA.__common: 0xac
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 482
-  Symbols:   1075
-  CStrings:  1223
+  Functions: 483
+  Symbols:   1076
+  CStrings:  1216
 
Symbols:
+ GCC_except_table101
+ GCC_except_table108
+ _drain_responses
- GCC_except_table106
- GCC_except_table93
CStrings:
+ "3679.60.14b97"
+ "AstrisArmProbeServer-3679.60.14~97 (FizzSeedUpdate tools)"
+ "[AstrisAsync] collect_responses - response read timed out, failing %zu remaining command(s) without waiting"
+ "drain_responses"
+ "{%s} discarded %d abandoned response(s), %d still to drain [%s]"
- "3679.40.30b163"
- "AstrisArmProbeServer-3679.40.30~163 (FizzB tools)"
- "Attempting to un-bork firmware... status = 0x%X"
- "Command set required to update this HW is not available.  Update process is forced to abort."
- "Failed to write \"MAGIC\" data or send memory modify command. status=0x%02x"
- "Firmware appears to be within the range known to have a broken update path.  Attempting to fix"
- "MEMm response: %02X %02X %02X %02X"
- "Memory modify failed and out of retries.  Aborting as retries were exhausted"
- "Modifying memory..."
- "Retrying memory modify command as it looks like it didn't execute..."
- "Should think SFWu now usable"
- "useBorkedSFWWorkarounds: %s"
```
