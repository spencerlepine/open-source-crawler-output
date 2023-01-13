## Detected Typos Diff
```diff
--- ./docs/server_api.md	original
+++ ./docs/server_api.md	fixed
@@ -9 +9 @@
-| Emulator                | Running in emulated environent: popular emulators such as Nox, Bluestacks etc. | `true` or `false` |
+| Emulator                | Running in emulated environment: popular emulators such as Nox, Bluestacks etc. | `true` or `false` |
--- ./app/src/main/java/com/fingerprintjs/android/aev/demo/demo_screen/api/VerifyRequest.kt	original
+++ ./app/src/main/java/com/fingerprintjs/android/aev/demo/demo_screen/api/VerifyRequest.kt	fixed
@@ -55 +55 @@
-    private val autorizationToken: String,
+    private val authorizationToken: String,
@@ -67 +67 @@
-        resultMap[PRIVATE_API_KEY] = autorizationToken
+        resultMap[PRIVATE_API_KEY] = authorizationToken
