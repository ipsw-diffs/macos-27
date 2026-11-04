## com.apple.driver.AppleMobileFileIntegrity

> `com.apple.driver.AppleMobileFileIntegrity`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1171.40.9.0.0
+1171.60.2.0.0
   __TEXT.__cstring: 0x1bbab
   __TEXT.__const: 0x1998
   __TEXT.__os_log: 0x47a
-  __TEXT_EXEC.__text: 0x354bc
+  __TEXT_EXEC.__text: 0x354e8
   __TEXT_EXEC.__auth_stubs: 0x1230
   __DATA.__data: 0xa42
   __DATA.__common: 0x100

   __DATA_CONST.__auth_got: 0x918
   __DATA_CONST.__got: 0xe0
   __DATA_CONST.__auth_ptr: 0x20
-  Functions: 1042
-  Symbols:   1978
+  Functions: 1043
+  Symbols:   1979
   CStrings:  3395
 
Symbols:
+ __Z25parentProcShouldBeTrustedR11LaunchFactsR15ProcessAccessorS2_
+ __ZN20LaunchTypeNonePolicy19launchTypeIsAllowedER11SystemFactsR11LaunchFactsR15ProcessAccessorS5_R23LaunchConstraintError_t
+ __ZN27LaunchTypeApplicationPolicy19launchTypeIsAllowedER11SystemFactsR11LaunchFactsR15ProcessAccessorS5_R23LaunchConstraintError_t
+ __ZN27LaunchTypeSysdiagnosePolicy19launchTypeIsAllowedER11SystemFactsR11LaunchFactsR15ProcessAccessorS5_R23LaunchConstraintError_t
+ __ZN29LaunchTypeSystemServicePolicy19launchTypeIsAllowedER11SystemFactsR11LaunchFactsR15ProcessAccessorS5_R23LaunchConstraintError_t
- __ZN20LaunchTypeNonePolicy19launchTypeIsAllowedER11SystemFactsR15ProcessAccessorS3_R23LaunchConstraintError_t
- __ZN27LaunchTypeApplicationPolicy19launchTypeIsAllowedER11SystemFactsR15ProcessAccessorS3_R23LaunchConstraintError_t
- __ZN27LaunchTypeSysdiagnosePolicy19launchTypeIsAllowedER11SystemFactsR15ProcessAccessorS3_R23LaunchConstraintError_t
- __ZN29LaunchTypeSystemServicePolicy19launchTypeIsAllowedER11SystemFactsR15ProcessAccessorS3_R23LaunchConstraintError_t
CStrings:
+ "01:18:20"
+ "AMFI: Only launchd can set the system service launch type (parent trusted? %d)\n"
+ "Oct 30 2026"
- "23:10:08"
- "AMFI: Only launchd can set the system service launch type (parent changed: %d)\n"
- "Oct 14 2026"
```
