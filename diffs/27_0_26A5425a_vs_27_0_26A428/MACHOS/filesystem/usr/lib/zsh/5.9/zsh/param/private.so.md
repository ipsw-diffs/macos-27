## private.so

> `/usr/lib/zsh/5.9/zsh/param/private.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 118.0.0.0.0
-  __TEXT.__text: 0xfa0
+  __TEXT.__text: 0xf34
   __TEXT.__auth_stubs: 0x160
   __TEXT.__cstring: 0xba
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__const: 0x78
   __DATA_CONST.__auth_got: 0xb0
   __DATA_CONST.__got: 0x58
Functions:
~ _printprivatenode : 160 -> 148
~ _boot_ : 84 -> 72
~ _cleanup_ : 200 -> 188
~ _bin_private : 596 -> 584
~ _pps_setfn : 112 -> 100
~ _ppi_setfn : 112 -> 100
~ _ppf_setfn : 112 -> 100
~ _ppa_setfn : 112 -> 100
~ _pph_setfn : 112 -> 100
```
