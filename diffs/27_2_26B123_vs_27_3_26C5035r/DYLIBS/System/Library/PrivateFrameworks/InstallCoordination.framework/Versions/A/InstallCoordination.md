## InstallCoordination

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Versions/A/InstallCoordination`

```diff

-849.40.7.0.2
-  __TEXT.__text: 0x65d78
-  __TEXT.__objc_methlist: 0x4a38
+849.60.8.0.0
+  __TEXT.__text: 0x65f00
+  __TEXT.__objc_methlist: 0x4a78
   __TEXT.__const: 0xc8
-  __TEXT.__cstring: 0x18b86
+  __TEXT.__cstring: 0x18b9f
   __TEXT.__gcc_except_tab: 0x1c10
   __TEXT.__oslogstring: 0x195
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x1dd0
+  __TEXT.__unwind_info: 0x1df0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x9d0
-  __DATA_CONST.__objc_classlist: 0x220
+  __DATA_CONST.__objc_classlist: 0x228
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22e8
+  __DATA_CONST.__objc_selrefs: 0x22f8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x19d0
+  __AUTH_CONST.__const: 0x19f0
   __AUTH_CONST.__cfstring: 0x6060
-  __AUTH_CONST.__objc_const: 0xd7c0
+  __AUTH_CONST.__objc_const: 0xd868
   __AUTH_CONST.__auth_got: 0x4b0
-  __AUTH.__objc_data: 0xa0
+  __AUTH.__objc_data: 0xf0
   __DATA.__objc_protorefs: 0x20
-  __DATA.__objc_classrefs: 0x350
-  __DATA.__objc_superrefs: 0x190
+  __DATA.__objc_classrefs: 0x358
+  __DATA.__objc_superrefs: 0x198
   __DATA.__objc_ivar: 0x260
   __DATA.__data: 0x1e0
-  __DATA.__bss: 0x90
+  __DATA.__bss: 0xa0
   __DATA_DIRTY.__objc_data: 0x14a0
   __DATA_DIRTY.__data: 0xaf0
   __DATA_DIRTY.__bss: 0x60

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1837
-  Symbols:   4018
-  CStrings:  1916
+  Functions: 1842
+  Symbols:   4031
+  CStrings:  1917
 
Symbols:
+ +[IXManagedAppTracker sharedTracker]
+ -[IXManagedAppTracker init]
+ -[IXManagedAppTracker managedAppBundleIdentifiersWithError:]
+ -[IXManagedAppTracker startTrackingWithError:]
+ _OBJC_CLASS_$_IXManagedAppTracker
+ _OBJC_METACLASS_$_IXManagedAppTracker
+ __OBJC_$_CLASS_METHODS_IXManagedAppTracker
+ __OBJC_$_CLASS_PROP_LIST_IXManagedAppTracker
+ __OBJC_$_INSTANCE_METHODS_IXManagedAppTracker
+ __OBJC_CLASS_RO_$_IXManagedAppTracker
+ __OBJC_METACLASS_RO_$_IXManagedAppTracker
+ ___36+[IXManagedAppTracker sharedTracker]_block_invoke
+ _sharedTracker.onceToken
+ _sharedTracker.sharedTracker
- +[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]
CStrings:
+ "-[IXManagedAppTracker managedAppBundleIdentifiersWithError:]"
+ "-[IXManagedAppTracker startTrackingWithError:]"
- "+[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]"
```
