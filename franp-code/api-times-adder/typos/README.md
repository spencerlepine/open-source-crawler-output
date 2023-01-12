## Detected Typos Diff
```diff
--- ./routes/mainRouter.js	original
+++ ./routes/mainRouter.js	fixed
@@ -8 +8 @@
-        "message": "Please, use the method POST for comunicate with this API."
+        "message": "Please, use the method POST for communicate with this API."
@@ -17 +17 @@
-    const comunicateErrors = (message) => {
+    const communicateErrors = (message) => {
@@ -27 +27 @@
-        comunicateErrors(`Array of times don't sended, you sended a ${typeof(data)}`)
+        communicateErrors(`Array of times don't sended, you sended a ${typeof(data)}`)
@@ -33 +33 @@
-        comunicateErrors(`Array of times are empty`)
+        communicateErrors(`Array of times are empty`)
@@ -39 +39 @@
-        comunicateErrors(`You sended ${data.length} times, but 200 are the limit`)
+        communicateErrors(`You sended ${data.length} times, but 200 are the limit`)
@@ -54 +54 @@
-                comunicateErrors(`The value Nº ${separatedTime.indexOf(str) + 1} in the array Nº ${data.indexOf(time) + 1} are not valid`)
+                communicateErrors(`The value Nº ${separatedTime.indexOf(str) + 1} in the array Nº ${data.indexOf(time) + 1} are not valid`)
@@ -96 +96 @@
-                comunicateErrors(`Sended ${quantityColons} colons in your time Nº ${data.indexOf(time) + 1}`)
+                communicateErrors(`Sended ${quantityColons} colons in your time Nº ${data.indexOf(time) + 1}`)
@@ -125 +125 @@
-            'standarTime': `${globalHours}:${globalMinutes}:${globalSeconds}`,
+            'standardTime': `${globalHours}:${globalMinutes}:${globalSeconds}`,
