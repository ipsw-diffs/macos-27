## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sun Sep 13 18:59:23 PDT 2026; root:libignition-64~27372/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Sun Sep 13 18:59:23 PDT 2026; root:libignition-64~27372/libignition_core/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Fri Sep  4 22:55:32 PDT 2026; root:libignition-64~25449/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Fri Sep  4 22:55:32 PDT 2026; root:libignition-64~25449/libignition_core/RELEASE_ARM64E"
```
