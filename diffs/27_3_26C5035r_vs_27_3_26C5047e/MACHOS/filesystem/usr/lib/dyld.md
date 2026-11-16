## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__AUTH_CONST.__const`

```diff
Functions:
~ _sandbox_check : 116 -> 120
~ _ccsha384_vng_arm_hw_compress : 8 -> 4
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Mon Nov  9 22:37:02 PST 2026; root:libignition-64~30610/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Mon Nov  9 22:37:02 PST 2026; root:libignition-64~30610/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Oct 28 21:34:12 PDT 2026; root:libignition-64~30353/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Wed Oct 28 21:34:12 PDT 2026; root:libignition-64~30353/libignition_core/RELEASE_ARM64E"
```
