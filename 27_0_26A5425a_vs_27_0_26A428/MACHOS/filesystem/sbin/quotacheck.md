## quotacheck

> `/sbin/quotacheck`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 766.0.1.0.0
-  __TEXT.__text: 0x18c4
+  __TEXT.__text: 0x18a8
   __TEXT.__auth_stubs: 0x2b0
   __TEXT.__cstring: 0x2e5
   __TEXT.__const: 0x20
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__auth_got: 0x158
   __DATA_CONST.__got: 0x20
   __DATA.__data: 0x30
Functions:
~ sub_100000aa8 : 292 -> 280
~ sub_100000d10 -> sub_100000d04 : 1868 -> 1876
~ sub_10000186c -> sub_100001868 : 32 -> 20
~ sub_10000188c -> sub_10000187c : 132 -> 120
```
