## IOMFBDiagnose

> `/usr/bin/IOMFBDiagnose`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 700.50.97.9.0
-  __TEXT.__text: 0x1001c
+  __TEXT.__text: 0x10860
   __TEXT.__auth_stubs: 0x2b0
   __TEXT.__objc_stubs: 0xe0
-  __TEXT.__const: 0xab4
-  __TEXT.__cstring: 0x7eb3
+  __TEXT.__const: 0xb74
+  __TEXT.__cstring: 0x837b
   __TEXT.__objc_methname: 0x62
-  __TEXT.__unwind_info: 0x1d8
-  __DATA_CONST.__const: 0xd20
+  __TEXT.__unwind_info: 0x250
+  __DATA_CONST.__const: 0xd50
   __DATA_CONST.__cfstring: 0xc00
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x160

   - /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/Versions/A/IOMobileFramebuffer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 118
+  Functions: 121
   Symbols:   56
-  CStrings:  1289
+  CStrings:  1346
 
CStrings:
+ "\t\t%03.2f/%03.2f %.2f ms\n"
+ "\t\t%s 0x%016llx %10.2fms\n"
+ "\t\t0x%016llx %15s(%02d) %.2f ms %s\n"
+ "\t\tTotal latency %.2fms\n"
+ "\t\tcurrent angle: %.2f\n"
+ "\t\tselected heatmap XD angle: %d\n\n"
+ "\t\tselected heatmap XD index: %d\n"
+ "\t0x%016llx %03.2f %.2f ms\n"
+ "\tAverage Adjustment(last 25 frames): %d\n"
+ "\tAverage Drift(last 25 frames): %d\n"
+ "\tCurrent Frame Number: %u\n"
+ "\tDrift Exceeded Count: %u\n"
+ "\tEnabled                : %d\n"
+ "\tFirst MSG Sync Miss Frame: %u\n"
+ "\tGenLock Frequency: %f\n"
+ "\tGenLock Mode: %s\n"
+ "\tGenLock: %s\n"
+ "\tLast %d adjustment values\n"
+ "\tLast %d drift values\n"
+ "\tLast Angle Update:"
+ "\tLast MSG Sync Miss Frame: %u\n"
+ "\tLatency traces:"
+ "\tLut Angles = { "
+ "\tMSG Sync Miss Count: %u\n"
+ "\tPipe Mode: %s\n"
+ "\tRamp %s\n"
+ "\tUnknown genlock mode: %u\n"
+ "\tUnsupported genlock data version"
+ "\tVersion                : %d\n"
+ "\tcurrent_angle          : %f\n"
+ "\tindex                  : %d\n"
+ "\tlut_size               : %d\n"
+ "\tweight                 : %f\n"
+ "\n\tHinge-angle info:"
+ " %f "
+ " } \n "
+ "%d, "
+ "%s hinge angle traces:\n"
+ ">> RDLC info version %d unsupported <<"
+ ">> failed to read RDLC info. Returned %x <<\n"
+ "ACSS2"
+ "Awake"
+ "Cold Boot"
+ "Consumed  "
+ "Error: lut_size exceeds maximum"
+ "GenLock"
+ "HW Follower mode"
+ "HingeAngleUpdate"
+ "HingeAngleUpdateAOD"
+ "LTA"
+ "Multi-pipe"
+ "Pending   "
+ "Programmed"
+ "RDLC"
+ "RDLC info : "
+ "Received  "
+ "Single Pipe"
```
