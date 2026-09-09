## com.apple.kec.Compression

> `com.apple.kec.Compression`

```diff

 212.0.1.0.0
   __TEXT.__const: 0x8
-  __TEXT_EXEC.__text: 0x3d78
+  __TEXT_EXEC.__text: 0x3dc4
   __TEXT_EXEC.__auth_stubs: 0x60
   __DATA.__data: 0xdc
   __DATA_CONST.__const: 0x48
Functions:
~ _lz4raw_encode_buffer : 324 -> 328
~ _lz4raw_decode_buffer : 268 -> 272
~ _lz4_encode_buffer : 544 -> 552
~ _lz4_stream_init : 204 -> 208
~ _lz4_stream_process : 1804 -> 1808
~ _smb_lz77_encode_buffer : 1028 -> 1032
~ _smb_lz77h_decode_buffer : 1576 -> 1580
~ _smb_lz77h_encode_buffer : 3000 -> 3016
~ _smb_lznt1_decode_buffer : 760 -> 764
~ _smb_lznt1_encode_buffer : 964 -> 968
~ _realloc_stream_state : 152 -> 156
~ _compression_stream_destroy : 80 -> 84
~ _compression_stream_identify_algorithm : 36 -> 40
~ _compression_kext_start : 216 -> 220
~ _lz4_decode : 612 -> 616
```
