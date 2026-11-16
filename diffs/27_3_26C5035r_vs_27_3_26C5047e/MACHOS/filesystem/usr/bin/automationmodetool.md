## automationmodetool

> `/usr/bin/automationmodetool`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA.__objc_selrefs`

```diff

-36.0.0.0.0
-  __TEXT.__text: 0x760
-  __TEXT.__auth_stubs: 0x190
+37.1.0.0.0
+  __TEXT.__text: 0x94c
+  __TEXT.__auth_stubs: 0x1b0
   __TEXT.__objc_stubs: 0x180
   __TEXT.__const: 0x10
-  __TEXT.__cstring: 0x2c7
+  __TEXT.__cstring: 0x50c
   __TEXT.__objc_methname: 0xac
-  __TEXT.__unwind_info: 0x80
-  __DATA_CONST.__const: 0xe0
-  __DATA_CONST.__cfstring: 0x80
+  __TEXT.__unwind_info: 0x88
+  __DATA_CONST.__const: 0xc0
+  __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0xd0
+  __DATA_CONST.__auth_got: 0xe0
   __DATA_CONST.__got: 0x28
   __DATA.__objc_selrefs: 0x60
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/AutomationMode.framework/Versions/A/AutomationMode
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9
-  Symbols:   35
-  CStrings:  36
+  Functions: 11
+  Symbols:   37
+  CStrings:  44
 
Symbols:
+ _geteuid
+ _os_variant_allows_internal_security_policies
CStrings:
+ "%s\n"
+ "Authentication failed or was cancelled."
+ "Unable to read password.\n"
+ "WARNING: Continuing grants Automation Mode unattended control of this device screen, keyboard, and pointer to all processes. Anyone who obtains this access can silently observe your screen, exfiltrate your files and credentials, and perform irreversible, destructive actions with no further prompts. Only continue on a dedicated CI device that doesn't contain any personal data."
+ "[Internal] Enter the password for user '%@': "
+ "authenticate-admin-nonshared"
+ "automationmodetool must not be run as root or via sudo.\n"
+ "com.apple.dt.automationmode"
+ "prompt"
- "Enter the password for user '%@': "
```
