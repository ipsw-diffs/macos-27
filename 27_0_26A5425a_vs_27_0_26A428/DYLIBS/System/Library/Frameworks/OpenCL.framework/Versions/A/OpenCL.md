## OpenCL

> `/System/Library/Frameworks/OpenCL.framework/Versions/A/OpenCL`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 6.1.0.0.0
-  __TEXT.__text: 0x58e54
+  __TEXT.__text: 0x58e74
   __TEXT.__const: 0x1f7c
   __TEXT.__cstring: 0xc609
   __TEXT.__dof_opencl_ap: 0x4ee
Functions:
~ _clCreateContext : 2776 -> 2756
~ _clBuildProgram : 1996 -> 2036
~ sub_20e78334c -> sub_20e993360 : 340 -> 336
~ sub_20e789330 -> sub_20e999340 : 1152 -> 1156
~ sub_20e789e54 -> sub_20e999e68 : 372 -> 376
~ sub_20e789fc8 -> sub_20e999fe0 : 256 -> 260
~ sub_20e78a1d8 -> sub_20e99a1f4 : 256 -> 260
~ sub_20e78a4a4 -> sub_20e99a4c4 : 496 -> 500
~ sub_20e78a694 -> sub_20e99a6b8 : 340 -> 344
~ sub_20e790aa0 -> sub_20e9a0ac8 : 1040 -> 1032
~ sub_20e793254 -> sub_20e9a3274 : 452 -> 448
~ sub_20e793418 -> sub_20e9a3434 : 212 -> 208
~ sub_20e793a7c -> sub_20e9a3a94 : 20 -> 28
~ sub_20e79d700 -> sub_20e9ad720 : 344 -> 352
~ sub_20e7bcc30 -> sub_20e9ccc58 : 284 -> 280
~ sub_20e7bcd50 -> sub_20e9ccd74 : 212 -> 208
CStrings:
+ "OpenCL 1.2 (Aug  8 2026 15:27:26)"
- "OpenCL 1.2 (Aug  8 2026 17:42:34)"
```
