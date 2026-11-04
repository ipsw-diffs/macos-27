## scodec_host_v1.im4p

> `Firmware/scodec/scodec_host_v1.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._afk_sys_objt`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4cd90
+  __TEXT.__text: 0x4ce88
   __TEXT.__const: 0x3938
   __TEXT.__cstring: 0x2a21
   __TEXT.__init_offsets: 0x0

   __DATA.__constructor: 0x0
   __DATA.__zerofill: 0x89530
   __OS_LOG.__string: 0x2dab
-  Functions: 1066
+  Functions: 1067
   Symbols:   3738
   CStrings:  733
 
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(bzero.S~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(memcmp.S~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(memmove.S~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(stack_protector.c~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(hibernate.S~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(start_anywhere_4k_link16m.S~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(vectors.S~armv8_chinook_Oz_flto_pac.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.3.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(wfi_workarounds.S~armv8_chinook_Oz_flto_pac.o)
+ __ZN18AFKEPCommandRemote7releaseEv
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(bzero.S~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(memcmp.S~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(memmove.S~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libc11.a(stack_protector.c~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(hibernate.S~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(start_anywhere_4k_link16m.S~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(vectors.S~armv8_chinook_Oz_flto_pac.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX27.2.Internal.sdk/usr/local/standalone/RTKit/usr/lib/Debug/armv8_chinook_Oz_flto_pac/libplatform~asc_v7_no_lib.a(wfi_workarounds.S~armv8_chinook_Oz_flto_pac.o)
- _OUTLINED_FUNCTION_633
Functions:
~ _afk_msgr_handle_q_reg : 216 -> 344
+ __ZN18AFKEPCommandRemote7releaseEv
~ __ZN16AFKEPInterfaceV213handleMessageEPKN5AFKEP11MessageInfoE8afk_spanI12AFKEPMessageE : 1248 -> 1304
~ __ZN16AFKEPInterfaceV215enqueueResponseEP18AFKEPCommandRemoteiy8afk_spanI12AFKEPMessageEPK16AFKEPSendOptions : 812 -> 764
~ ____ZN16AFKEPInterfaceV211handleCloseEv_block_invoke : 180 -> 160
~ ____ZN18AFKEPInterfaceFWV213enqueueReportEh8afk_spanI12AFKEPMessageEy18AFKEPReportOptions_block_invoke : 176 -> 184
~ __ZN18AFKEPInterfaceFWV218_sendPublishReportEP13AFKDictionary : 968 -> 992
~ __ZN25AFKEPInterfaceServiceFWV213handleMessageEPKN5AFKEP11MessageInfoE8afk_spanI12AFKEPMessageE : 1320 -> 1324
~ _OUTLINED_FUNCTION_388 : 3896 -> 3884
~ __rtk_lock_lock : 368 -> 376
```
