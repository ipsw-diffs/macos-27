## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-3298.60.14.0.0
-  __TEXT.__text: 0x10404
+3298.60.20.0.0
+  __TEXT.__text: 0x106c8
   __TEXT.__auth_stubs: 0xc80
   __TEXT.__objc_stubs: 0x1500
   __TEXT.__objc_methlist: 0x9f0
   __TEXT.__const: 0x2a0
-  __TEXT.__oslogstring: 0x192f
+  __TEXT.__cstring: 0x1b66
+  __TEXT.__oslogstring: 0x1948
   __TEXT.__objc_classname: 0x1b1
   __TEXT.__objc_methtype: 0xa85
   __TEXT.__objc_methname: 0x14d1
-  __TEXT.__cstring: 0x1351
   __TEXT.__gcc_except_tab: 0x2dc
-  __TEXT.__unwind_info: 0x4a8
-  __DATA_CONST.__const: 0x518
+  __TEXT.__unwind_info: 0x4b8
+  __DATA_CONST.__const: 0x6a8
   __DATA_CONST.__cfstring: 0x1c0
   __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_catlist: 0x10

   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 281
+  Functions: 284
   Symbols:   246
-  CStrings:  700
+  CStrings:  746
 
CStrings:
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Nov 10 01:36:12 PST 2026; root:libxpc_executables-3298.60.20~43/smd/RELEASE_ARM64E"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Nov 10 01:36:12 PST 2026; root:libxpc_executables-3298.60.20~43/smd/RELEASE_ARM64E"
+ "Rejecting plist name: %s"
+ "com.apple.private.domain-extension"
+ "com.apple.private.spawn-driver"
+ "com.apple.private.xpc.allowed-get-service-name"
+ "com.apple.private.xpc.allowed-launch-types"
+ "com.apple.private.xpc.conclave.submit"
+ "com.apple.private.xpc.cryptex.submit"
+ "com.apple.private.xpc.cryptex.terminate"
+ "com.apple.private.xpc.domain-extension"
+ "com.apple.private.xpc.domain-extension.proxy"
+ "com.apple.private.xpc.launchd.allow-posixspawn-telemetry"
+ "com.apple.private.xpc.launchd.allow-set-bundle-path"
+ "com.apple.private.xpc.launchd.allow-submit-launch-angels"
+ "com.apple.private.xpc.launchd.allowed-coalition-quiesce"
+ "com.apple.private.xpc.launchd.allowed-complete-urgent-log-submission"
+ "com.apple.private.xpc.launchd.allowed-manage-trial-factors"
+ "com.apple.private.xpc.launchd.app-server"
+ "com.apple.private.xpc.launchd.app-state-manager"
+ "com.apple.private.xpc.launchd.enable-disable-system-services"
+ "com.apple.private.xpc.launchd.event-monitor"
+ "com.apple.private.xpc.launchd.job-manager"
+ "com.apple.private.xpc.launchd.job-manager-remove-any"
+ "com.apple.private.xpc.launchd.job-query"
+ "com.apple.private.xpc.launchd.load-jetsam-properties-path"
+ "com.apple.private.xpc.launchd.loginitem-bootstrapper"
+ "com.apple.private.xpc.launchd.loginitem-outside-bundle"
+ "com.apple.private.xpc.launchd.obliterator"
+ "com.apple.private.xpc.launchd.per-user-create.mbsetupuser"
+ "com.apple.private.xpc.launchd.per-user-lookup"
+ "com.apple.private.xpc.launchd.persist-to-boot-mode"
+ "com.apple.private.xpc.launchd.reboot"
+ "com.apple.private.xpc.launchd.reboot-pivot-root"
+ "com.apple.private.xpc.launchd.service-hold"
+ "com.apple.private.xpc.launchd.service-stats"
+ "com.apple.private.xpc.launchd.setenv-pid-domain"
+ "com.apple.private.xpc.launchd.storage-mounter"
+ "com.apple.private.xpc.launchd.system-job-bootstrap"
+ "com.apple.private.xpc.launchd.userspace-reboot"
+ "com.apple.private.xpc.persona-creator"
+ "com.apple.private.xpc.persona-manager"
+ "com.apple.private.xpc.service-attach"
+ "com.apple.private.xpc.service-configure"
+ "com.apple.private.xpc.service-instance-manager"
+ "com.apple.private.xpc.smd-job-submit"
+ "com.apple.rootless.xpc.bootstrap"
+ "com.apple.rootless.xpc.effective-root"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Thu Oct 29 00:45:18 PDT 2026; root:libxpc_executables-3298.60.14~78/smd/RELEASE_ARM64E"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Thu Oct 29 00:45:18 PDT 2026; root:libxpc_executables-3298.60.14~78/smd/RELEASE_ARM64E"
```
