## mtree

> `/usr/sbin/mtree`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 487.0.1.0.0
-  __TEXT.__text: 0x8e80
+  __TEXT.__text: 0x8de4
   __TEXT.__auth_stubs: 0x7a0
   __TEXT.__const: 0x6f7
   __TEXT.__cstring: 0x15bf
-  __TEXT.__unwind_info: 0x198
+  __TEXT.__unwind_info: 0x2a8
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0x3d0
Functions:
~ sub_100000c58 : 96 -> 84
~ sub_100000dc0 -> sub_100000db4 : 80 -> 68
~ sub_100000e10 -> sub_100000df8 : 68 -> 56
~ sub_100001820 -> sub_1000017fc : 36 -> 24
~ sub_100001844 -> sub_100001814 : 36 -> 24
~ sub_100003bfc -> sub_100003bc0 : 208 -> 196
~ sub_10000510c -> sub_1000050c4 : 40 -> 28
~ sub_1000060e0 -> sub_10000608c : 80 -> 68
~ sub_100006d60 -> sub_100006d00 : 44 -> 32
~ sub_100006d8c -> sub_100006d20 : 28 -> 16
~ sub_100006dbc -> sub_100006d44 : 32 -> 20
~ sub_100007648 -> sub_1000075c4 : 156 -> 144
~ sub_1000076e4 -> sub_100007654 : 908 -> 896
```
