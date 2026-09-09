## slapd

> `/usr/libexec/slapd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__dof_ldap_rb_s`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 565.0.0.0.0
-  __TEXT.__text: 0x2152a0
+  __TEXT.__text: 0x212ecc
   __TEXT.__auth_stubs: 0x1ae0
   __TEXT.__init_offsets: 0x4
   __TEXT.__cstring: 0x52877
   __TEXT.__const: 0x2d1e8
   __TEXT.__dof_ldap_rb_s: 0x2ea
-  __TEXT.__unwind_info: 0x3670
+  __TEXT.__unwind_info: 0x5bc8
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0xa500
   __DATA_CONST.__cfstring: 0x1080

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libsasl2.2.dylib
-  Functions: 6066
+  Functions: 6067
   Symbols:   492
   CStrings:  10267
 
```
