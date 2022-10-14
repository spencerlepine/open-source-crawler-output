## Detected Typos Diff
```diff
--- ./src/emoji/emoji.service.ts	original
+++ ./src/emoji/emoji.service.ts	fixed
@@ -30 +30 @@
-        const validGruop: string = group.replace(/_/g, " ");
+        const validGroup: string = group.replace(/_/g, " ");
@@ -32 +32 @@
-            .find({ group: validGruop }, { _id: 0 })
+            .find({ group: validGroup }, { _id: 0 })
