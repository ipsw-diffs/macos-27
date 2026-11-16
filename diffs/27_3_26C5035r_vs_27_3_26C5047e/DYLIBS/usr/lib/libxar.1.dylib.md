## libxar.1.dylib

> `/usr/lib/libxar.1.dylib`

```diff

-516.40.4.0.0
-  __TEXT.__text: 0xc8d8
-  __TEXT.__const: 0x168
+516.60.2.0.0
+  __TEXT.__text: 0xcda4
+  __TEXT.__const: 0x170
   __TEXT.__cstring: 0xc25
   __TEXT.__unwind_info: 0x398
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libbz2.1.0.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 224
-  Symbols:   374
+  Functions: 225
+  Symbols:   375
   CStrings:  198
 
Symbols:
+ _xar_io_get_decompress_chunk_size
Functions:
~ _xar_darwinattr_archive : 1872 -> 1876
~ _xar_bzip_fromheap_done : 80 -> 92
~ _xar_bzip_fromheap_in : 480 -> 816
~ _xar_darwinattr_extract : 1520 -> 1640
~ _xar_ea_write : 144 -> 260
~ _xar_data_extract : 424 -> 428
~ _xar_data_verify : 164 -> 180
+ _xar_io_get_decompress_chunk_size
~ _xar_attrcopy_from_heap : 744 -> 844
~ _xar_attrcopy_from_heap_to_stream_init : 260 -> 268
~ _xar_attrcopy_from_heap_to_stream : 596 -> 764
~ _xar_attrcopy_from_heap_to_stream_end : 152 -> 200
~ _xar_gzip_fromheap_done : 80 -> 92
~ _xar_gzip_fromheap_in : 588 -> 836
```
