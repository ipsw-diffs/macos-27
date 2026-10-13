## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sat Oct 10 01:01:19 PDT 2026; root:libignition-64~29905/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Sat Oct 10 01:01:19 PDT 2026; root:libignition-64~29905/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sun Sep 27 19:54:55 PDT 2026; root:libignition-64~29475/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Sun Sep 27 19:54:55 PDT 2026; root:libignition-64~29475/libignition_core/RELEASE_ARM64E"
```
