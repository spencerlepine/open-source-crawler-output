## Detected Typos Diff
```diff
--- ./docs/migrating_v0_v1.md	original
+++ ./docs/migrating_v0_v1.md	fixed
@@ -48 +48 @@
-The new response is now an object containing property "bot" indicating whether the user is a bot or not. And if "bot" is `true`, then we additionaly provide a property "botKind" as described in our [API docs](docs/api.md).
+The new response is now an object containing property "bot" indicating whether the user is a bot or not. And if "bot" is `true`, then we additionally provide a property "botKind" as described in our [API docs](docs/api.md).
--- ./playground/index.ts	original
+++ ./playground/index.ts	fixed
@@ -79 +79 @@
-    resultTextEl.innerHTML = 'An error occured'
+    resultTextEl.innerHTML = 'An error occurred'
