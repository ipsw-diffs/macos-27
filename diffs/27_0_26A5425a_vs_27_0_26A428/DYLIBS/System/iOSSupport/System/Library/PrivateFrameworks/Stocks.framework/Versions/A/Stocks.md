## Stocks

> `/System/iOSSupport/System/Library/PrivateFrameworks/Stocks.framework/Versions/A/Stocks`

```diff

 1555.1.0.0.0
-  __TEXT.__text: 0x46348
+  __TEXT.__text: 0x46334
   __TEXT.__objc_methlist: 0x54a8
   __TEXT.__const: 0x2f8
   __TEXT.__cstring: 0x242d

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1830
+  Functions: 1831
   Symbols:   5026
   CStrings:  686
 
Functions:
+ _OUTLINED_FUNCTION_2
~ -[StockPlatterViewController updateChartForInterval:completion:].cold.1 : 60 -> 52
~ __64-[StockPlatterViewController updateChartForInterval:completion:]_block_invoke.cold.1 : 72 -> 64
~ __64-[StockPlatterViewController updateChartForInterval:completion:]_block_invoke.101.cold.1 : 64 -> 56
~ __64-[StockPlatterViewController updateChartForInterval:completion:]_block_invoke.103.cold.1 : 64 -> 56
~ -[YQLRequest loadRequest:].cold.1 : 108 -> 100
~ -[YQLRequest loadRequest:].cold.2 : 72 -> 64
~ -[YQLRequest failWithError:].cold.1 : 152 -> 156
~ -[YQLRequest URLSession:task:didCompleteWithError:].cold.1 : 160 -> 164
```
