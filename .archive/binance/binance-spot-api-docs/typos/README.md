## Detected Typos Diff
```diff
--- ./CHANGELOG_CN.md	original
+++ ./CHANGELOG_CN.md	fixed
@@ -370,9 +370,9 @@
-  *  POST api/v3/order `RESULT` 与 `FULL` 响应中增加 `cummulativeQuoteQty`
-  *  GET api/v3/openOrders 无symbol调用权重下降为 40.
-  *  GET api/v3/ticker/24hr 无symbol调用权重下降为 40.
-  *  GET /api/v1/trades amount最大可取到1000.
-  *  GET /api/v1/historicalTrades amount最大可取到1000.
-  *  GET /api/v1/aggTrades amount最大可取到1000.
-  *  GET /api/v1/klines amount最大可取到1000.
-  *  订单查询结果返回中增加 `updateTime` 字段，代表该订单末次更新(创建、成交、过期、取消、拒绝等等)时间; `time` 仅表示创建时间.
-  *  订单查询结果中增加 `cummulativeQuoteQty`字段. 负值表示尚无任何成交，该字段不可用.
+  *  POST api/v3/order `RESULT` 与 `FULL` 响应中增加 `cumulativeQuoteQty`
+  *  GET api/v3/openOrders 无symbol调用权重下降为 40.
+  *  GET api/v3/ticker/24hr 无symbol调用权重下降为 40.
+  *  GET /api/v1/trades amount最大可取到1000.
+  *  GET /api/v1/historicalTrades amount最大可取到1000.
+  *  GET /api/v1/aggTrades amount最大可取到1000.
+  *  GET /api/v1/klines amount最大可取到1000.
+  *  订单查询结果返回中增加 `updateTime` 字段，代表该订单末次更新(创建、成交、过期、取消、拒绝等等)时间; `time` 仅表示创建时间.
+  *  订单查询结果中增加 `cumulativeQuoteQty`字段. 负值表示尚无任何成交，该字段不可用.
@@ -382,2 +382,2 @@
-  *  订单报告与成交报告中增加`cummulativeQuoteQty` 字段 (`Z`). 表示已经成交的金额， 即已经花费的金额(买入订单)或已经收到的金额(卖出订单)，均未计算手续费. 此功能增加之前成交的订单在历史订单接口中查询到的该字段可能小于零. 
-  *  `cummulativeQuoteQty`/`cummulativeQty` 可以用来计算该订单已经成交部分的平均价格。
+  *  订单报告与成交报告中增加`cumulativeQuoteQty` 字段 (`Z`). 表示已经成交的金额， 即已经花费的金额(买入订单)或已经收到的金额(卖出订单)，均未计算手续费. 此功能增加之前成交的订单在历史订单接口中查询到的该字段可能小于零. 
+  *  `cumulativeQuoteQty`/`cumulativeQty` 可以用来计算该订单已经成交部分的平均价格。
--- ./CHANGELOG.md	original
+++ ./CHANGELOG.md	fixed
@@ -601,9 +601,9 @@
-*  POST api/v3/order `RESULT` and `FULL` responses now have `cummulativeQuoteQty`
-*  GET api/v3/openOrders with no symbol weight reduced to 40.
-*  GET api/v3/ticker/24hr with no symbol weight reduced to 40.
-*  Max amount of trades from GET /api/v1/trades increased to 1000.
-*  Max amount of trades from GET /api/v1/historicalTrades increased to 1000.
-*  Max amount of aggregate trades from GET /api/v1/aggTrades increased to 1000.
-*  Max amount of aggregate trades from GET /api/v1/klines increased to 1000.
-*  Rest API Order lookups now return `updateTime` which represents the last time the order was updated; `time` is the order creation time.
-*  Order lookup endpoints will now return `cummulativeQuoteQty`. If `cummulativeQuoteQty` is < 0, it means the data isn't available for this order at this time.
+*  POST api/v3/order `RESULT` and `FULL` responses now have `cumulativeQuoteQty`
+*  GET api/v3/openOrders with no symbol weight reduced to 40.
+*  GET api/v3/ticker/24hr with no symbol weight reduced to 40.
+*  Max amount of trades from GET /api/v1/trades increased to 1000.
+*  Max amount of trades from GET /api/v1/historicalTrades increased to 1000.
+*  Max amount of aggregate trades from GET /api/v1/aggTrades increased to 1000.
+*  Max amount of aggregate trades from GET /api/v1/klines increased to 1000.
+*  Rest API Order lookups now return `updateTime` which represents the last time the order was updated; `time` is the order creation time.
+*  Order lookup endpoints will now return `cumulativeQuoteQty`. If `cumulativeQuoteQty` is < 0, it means the data isn't available for this order at this time.
@@ -613 +613 @@
-*  `cummulativeQuoteQty` field added to order responses and execution reports (as variable `Z`). Represents the cummulative amount of the `quote` that has been spent (with a `BUY` order) or received (with a `SELL` order). Historical orders will have a value < 0 in this field indicating the data is not available at this time. `cummulativeQuoteQty` divided by `cummulativeQty` will give the average price for an order.
+*  `cumulativeQuoteQty` field added to order responses and execution reports (as variable `Z`). Represents the cumulative amount of the `quote` that has been spent (with a `BUY` order) or received (with a `SELL` order). Historical orders will have a value < 0 in this field indicating the data is not available at this time. `cumulativeQuoteQty` divided by `cumulativeQty` will give the average price for an order.
--- ./errors.md	original
+++ ./errors.md	fixed
@@ -14 +14 @@
- * An unknown error occured while processing the request.
+ * An unknown error occurred while processing the request.
--- ./faqs/spot_glossary_cn.md	original
+++ ./faqs/spot_glossary_cn.md	fixed
@@ -60 +60 @@
-`cummulativeQuoteQty`
+`cumulativeQuoteQty`
--- ./rest-api_CN.md	original
+++ ./rest-api_CN.md	fixed
@@ -1418 +1418 @@
-  "cummulativeQuoteQty": "10.00000000",
+  "cumulativeQuoteQty": "10.00000000",
@@ -1439 +1439 @@
-  "cummulativeQuoteQty": "10.00000000",
+  "cumulativeQuoteQty": "10.00000000",
@@ -1569,16 +1569,16 @@
-    "cummulativeQuoteQty": "0.00000000",
-    "status": "CANCELED",
-    "timeInForce": "GTC",
-    "type": "LIMIT",
-    "side": "SELL"
-  },
-  "newOrderResponse": {
-    "symbol": "BTCUSDT",
-    "orderId": 10,
-    "orderListId": -1,
-    "clientOrderId": "wOceeeOzNORyLiQfw7jd8S",
-    "transactTime": 1652928801803,
-    "price": "0.02000000",
-    "origQty": "0.040000",
-    "executedQty": "0.00000000",
-    "cummulativeQuoteQty": "0.00000000",
+    "cumulativeQuoteQty": "0.00000000",
+    "status": "CANCELED",
+    "timeInForce": "GTC",
+    "type": "LIMIT",
+    "side": "SELL"
+  },
+  "newOrderResponse": {
+    "symbol": "BTCUSDT",
+    "orderId": 10,
+    "orderListId": -1,
+    "clientOrderId": "wOceeeOzNORyLiQfw7jd8S",
+    "transactTime": 1652928801803,
+    "price": "0.02000000",
+    "origQty": "0.040000",
+    "executedQty": "0.00000000",
+    "cumulativeQuoteQty": "0.00000000",
@@ -1628 +1628 @@
-      "cummulativeQuoteQty": "0.000000",
+      "cumulativeQuoteQty": "0.000000",
@@ -1706 +1706 @@
-* 某些订单中`cummulativeQuoteQty`<0，是由于这些订单是cummulativeQuoteQty功能上线之前的订单。
+* 某些订单中`cumulativeQuoteQty`<0，是由于这些订单是cumulativeQuoteQty功能上线之前的订单。
@@ -1720 +1720 @@
-  "cummulativeQuoteQty": "0.0",
+  "cumulativeQuoteQty": "0.0",
@@ -1769 +1769 @@
-  "cummulativeQuoteQty": "8.00000000",
+  "cumulativeQuoteQty": "8.00000000",
@@ -1811 +1811 @@
-  "cummulativeQuoteQty": "0.0", // 累计交易的金额
+  "cumulativeQuoteQty": "0.0", // 累计交易的金额
@@ -1859 +1859 @@
-    "cummulativeQuoteQty": "0.0",
+    "cumulativeQuoteQty": "0.0",
@@ -1895 +1895 @@
-* 一些历史订单 `cummulativeQuoteQty`  < 0, 是指数据此时不存在。
+* 一些历史订单 `cumulativeQuoteQty`  < 0, 是指数据此时不存在。
@@ -1911 +1911 @@
-    "cummulativeQuoteQty": "0.0",
+    "cumulativeQuoteQty": "0.0",
@@ -2037,17 +2037,17 @@
-      "cummulativeQuoteQty": "0.00000000",
-      "status": "CANCELED",
-      "timeInForce": "GTC",
-      "type": "STOP_LOSS_LIMIT",
-      "side": "SELL",
-      "stopPrice": "1.00000000"
-    },
-    {
-      "symbol": "LTCBTC",
-      "origClientOrderId": "TXOvglzXuaubXAaENpaRCB",
-      "orderId": 3,
-      "orderListId": 0,
-      "clientOrderId": "unfWT8ig8i0uj6lPuYLez6",
-      "price": "3.00000000",
-      "origQty": "10.00000000",
-      "executedQty": "0.00000000",
-      "cummulativeQuoteQty": "0.00000000",
+      "cumulativeQuoteQty": "0.00000000",
+      "status": "CANCELED",
+      "timeInForce": "GTC",
+      "type": "STOP_LOSS_LIMIT",
+      "side": "SELL",
+      "stopPrice": "1.00000000"
+    },
+    {
+      "symbol": "LTCBTC",
+      "origClientOrderId": "TXOvglzXuaubXAaENpaRCB",
+      "orderId": 3,
+      "orderListId": 0,
+      "clientOrderId": "unfWT8ig8i0uj6lPuYLez6",
+      "price": "3.00000000",
+      "origQty": "10.00000000",
+      "executedQty": "0.00000000",
+      "cumulativeQuoteQty": "0.00000000",
--- ./faqs/spot_glossary.md	original
+++ ./faqs/spot_glossary.md	fixed
@@ -60 +60 @@
-`cummulativeQuoteQty`
+`cumulativeQuoteQty`
--- ./rest-api.md	original
+++ ./rest-api.md	fixed
@@ -1481 +1481 @@
-  "cummulativeQuoteQty": "10.00000000",
+  "cumulativeQuoteQty": "10.00000000",
@@ -1502 +1502 @@
-  "cummulativeQuoteQty": "10.00000000",
+  "cumulativeQuoteQty": "10.00000000",
@@ -1592 +1592 @@
-* For some historical orders `cummulativeQuoteQty` will be < 0, meaning the data is not available at this time.
+* For some historical orders `cumulativeQuoteQty` will be < 0, meaning the data is not available at this time.
@@ -1607 +1607 @@
-  "cummulativeQuoteQty": "0.0",
+  "cumulativeQuoteQty": "0.0",
@@ -1658 +1658 @@
-  "cummulativeQuoteQty": "0.00000000",
+  "cumulativeQuoteQty": "0.00000000",
@@ -1697,69 +1697,69 @@
-    "cummulativeQuoteQty": "0.000000",
-    "status": "CANCELED",
-    "timeInForce": "GTC",
-    "type": "LIMIT",
-    "side": "BUY"
-  },
-  {
-    "symbol": "BTCUSDT",
-    "origClientOrderId": "A3EF2HCwxgZPFMrfwbgrhv",
-    "orderId": 13,
-    "orderListId": -1,
-    "clientOrderId": "pXLV6Hz6mprAcVYpVMTGgx",
-    "price": "0.090430",
-    "origQty": "0.178622",
-    "executedQty": "0.000000",
-    "cummulativeQuoteQty": "0.000000",
-    "status": "CANCELED",
-    "timeInForce": "GTC",
-    "type": "LIMIT",
-    "side": "BUY"
-  },
-  {
-    "orderListId": 1929,
-    "contingencyType": "OCO",
-    "listStatusType": "ALL_DONE",
-    "listOrderStatus": "ALL_DONE",
-    "listClientOrderId": "2inzWQdDvZLHbbAmAozX2N",
-    "transactionTime": 1585230948299,
-    "symbol": "BTCUSDT",
-    "orders": [
-      {
-        "symbol": "BTCUSDT",
-        "orderId": 20,
-        "clientOrderId": "CwOOIPHSmYywx6jZX77TdL"
-      },
-      {
-        "symbol": "BTCUSDT",
-        "orderId": 21,
-        "clientOrderId": "461cPg51vQjV3zIMOXNz39"
-      }
-    ],
-    "orderReports": [
-      {
-        "symbol": "BTCUSDT",
-        "origClientOrderId": "CwOOIPHSmYywx6jZX77TdL",
-        "orderId": 20,
-        "orderListId": 1929,
-        "clientOrderId": "pXLV6Hz6mprAcVYpVMTGgx",
-        "price": "0.668611",
-        "origQty": "0.690354",
-        "executedQty": "0.000000",
-        "cummulativeQuoteQty": "0.000000",
-        "status": "CANCELED",
-        "timeInForce": "GTC",
-        "type": "STOP_LOSS_LIMIT",
-        "side": "BUY",
-        "stopPrice": "0.378131",
-        "icebergQty": "0.017083"
-      },
-      {
-        "symbol": "BTCUSDT",
-        "origClientOrderId": "461cPg51vQjV3zIMOXNz39",
-        "orderId": 21,
-        "orderListId": 1929,
-        "clientOrderId": "pXLV6Hz6mprAcVYpVMTGgx",
-        "price": "0.008791",
-        "origQty": "0.690354",
-        "executedQty": "0.000000",
-        "cummulativeQuoteQty": "0.000000",
+    "cumulativeQuoteQty": "0.000000",
+    "status": "CANCELED",
+    "timeInForce": "GTC",
+    "type": "LIMIT",
+    "side": "BUY"
+  },
+  {
+    "symbol": "BTCUSDT",
+    "origClientOrderId": "A3EF2HCwxgZPFMrfwbgrhv",
+    "orderId": 13,
+    "orderListId": -1,
+    "clientOrderId": "pXLV6Hz6mprAcVYpVMTGgx",
+    "price": "0.090430",
+    "origQty": "0.178622",
+    "executedQty": "0.000000",
+    "cumulativeQuoteQty": "0.000000",
+    "status": "CANCELED",
+    "timeInForce": "GTC",
+    "type": "LIMIT",
+    "side": "BUY"
+  },
+  {
+    "orderListId": 1929,
+    "contingencyType": "OCO",
+    "listStatusType": "ALL_DONE",
+    "listOrderStatus": "ALL_DONE",
+    "listClientOrderId": "2inzWQdDvZLHbbAmAozX2N",
+    "transactionTime": 1585230948299,
+    "symbol": "BTCUSDT",
+    "orders": [
+      {
+        "symbol": "BTCUSDT",
+        "orderId": 20,
+        "clientOrderId": "CwOOIPHSmYywx6jZX77TdL"
+      },
+      {
+        "symbol": "BTCUSDT",
+        "orderId": 21,
+        "clientOrderId": "461cPg51vQjV3zIMOXNz39"
+      }
+    ],
+    "orderReports": [
+      {
+        "symbol": "BTCUSDT",
+        "origClientOrderId": "CwOOIPHSmYywx6jZX77TdL",
+        "orderId": 20,
+        "orderListId": 1929,
+        "clientOrderId": "pXLV6Hz6mprAcVYpVMTGgx",
+        "price": "0.668611",
+        "origQty": "0.690354",
+        "executedQty": "0.000000",
+        "cumulativeQuoteQty": "0.000000",
+        "status": "CANCELED",
+        "timeInForce": "GTC",
+        "type": "STOP_LOSS_LIMIT",
+        "side": "BUY",
+        "stopPrice": "0.378131",
+        "icebergQty": "0.017083"
+      },
+      {
+        "symbol": "BTCUSDT",
+        "origClientOrderId": "461cPg51vQjV3zIMOXNz39",
+        "orderId": 21,
+        "orderListId": 1929,
+        "clientOrderId": "pXLV6Hz6mprAcVYpVMTGgx",
+        "price": "0.008791",
+        "origQty": "0.690354",
+        "executedQty": "0.000000",
+        "cumulativeQuoteQty": "0.000000",
@@ -1839,16 +1839,16 @@
-    "cummulativeQuoteQty": "0.00000000",
-    "status": "CANCELED",
-    "timeInForce": "GTC",
-    "type": "LIMIT",
-    "side": "SELL"
-  },
-  "newOrderResponse": {
-    "symbol": "BTCUSDT",
-    "orderId": 10,
-    "orderListId": -1,
-    "clientOrderId": "wOceeeOzNORyLiQfw7jd8S",
-    "transactTime": 1652928801803,
-    "price": "0.02000000",
-    "origQty": "0.040000",
-    "executedQty": "0.00000000",
-    "cummulativeQuoteQty": "0.00000000",
+    "cumulativeQuoteQty": "0.00000000",
+    "status": "CANCELED",
+    "timeInForce": "GTC",
+    "type": "LIMIT",
+    "side": "SELL"
+  },
+  "newOrderResponse": {
+    "symbol": "BTCUSDT",
+    "orderId": 10,
+    "orderListId": -1,
+    "clientOrderId": "wOceeeOzNORyLiQfw7jd8S",
+    "transactTime": 1652928801803,
+    "price": "0.02000000",
+    "origQty": "0.040000",
+    "executedQty": "0.00000000",
+    "cumulativeQuoteQty": "0.00000000",
@@ -1898 +1898 @@
-      "cummulativeQuoteQty": "0.000000",
+      "cumulativeQuoteQty": "0.000000",
@@ -1991 +1991 @@
-    "cummulativeQuoteQty": "0.0",
+    "cumulativeQuoteQty": "0.0",
@@ -2032 +2032 @@
-* For some historical orders `cummulativeQuoteQty` will be < 0, meaning the data is not available at this time.
+* For some historical orders `cumulativeQuoteQty` will be < 0, meaning the data is not available at this time.
@@ -2046 +2046 @@
-    "cummulativeQuoteQty": "0.0",
+    "cumulativeQuoteQty": "0.0",
@@ -2143,17 +2143,17 @@
-      "cummulativeQuoteQty": "0.000000",
-      "status": "NEW",
-      "timeInForce": "GTC",
-      "type": "STOP_LOSS",
-      "side": "BUY",
-      "stopPrice": "0.960664"
-    },
-    {
-      "symbol": "LTCBTC",
-      "orderId": 3,
-      "orderListId": 0,
-      "clientOrderId": "xTXKaGYd4bluPVp78IVRvl",
-      "transactTime": 1563417480525,
-      "price": "0.036435",
-      "origQty": "0.624363",
-      "executedQty": "0.000000",
-      "cummulativeQuoteQty": "0.000000",
+      "cumulativeQuoteQty": "0.000000",
+      "status": "NEW",
+      "timeInForce": "GTC",
+      "type": "STOP_LOSS",
+      "side": "BUY",
+      "stopPrice": "0.960664"
+    },
+    {
+      "symbol": "LTCBTC",
+      "orderId": 3,
+      "orderListId": 0,
+      "clientOrderId": "xTXKaGYd4bluPVp78IVRvl",
+      "transactTime": 1563417480525,
+      "price": "0.036435",
+      "origQty": "0.624363",
+      "executedQty": "0.000000",
+      "cumulativeQuoteQty": "0.000000",
@@ -2231,17 +2231,17 @@
-      "cummulativeQuoteQty": "0.00000000",
-      "status": "CANCELED",
-      "timeInForce": "GTC",
-      "type": "STOP_LOSS_LIMIT",
-      "side": "SELL",
-      "stopPrice": "1.00000000"
-    },
-    {
-      "symbol": "LTCBTC",
-      "origClientOrderId": "TXOvglzXuaubXAaENpaRCB",
-      "orderId": 3,
-      "orderListId": 0,
-      "clientOrderId": "unfWT8ig8i0uj6lPuYLez6",
-      "price": "3.00000000",
-      "origQty": "10.00000000",
-      "executedQty": "0.00000000",
-      "cummulativeQuoteQty": "0.00000000",
+      "cumulativeQuoteQty": "0.00000000",
+      "status": "CANCELED",
+      "timeInForce": "GTC",
+      "type": "STOP_LOSS_LIMIT",
+      "side": "SELL",
+      "stopPrice": "1.00000000"
+    },
+    {
+      "symbol": "LTCBTC",
+      "origClientOrderId": "TXOvglzXuaubXAaENpaRCB",
+      "orderId": 3,
+      "orderListId": 0,
+      "clientOrderId": "unfWT8ig8i0uj6lPuYLez6",
+      "price": "3.00000000",
+      "origQty": "10.00000000",
+      "executedQty": "0.00000000",
+      "cumulativeQuoteQty": "0.00000000",
