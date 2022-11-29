## Detected Typos Diff
```diff
--- ./lib/orm/associations/association.js	original
+++ ./lib/orm/associations/association.js	fixed
@@ -117 +117 @@
-     A setter for schema, since we don't have a reference at constuction time.
+     A setter for schema, since we don't have a reference at construction time.
--- ./lib/orm/model.js	original
+++ ./lib/orm/model.js	fixed
@@ -21 +21 @@
-  You can access properites (fields) and relationships directly off of models.
+  You can access properties (fields) and relationships directly off of models.
@@ -399 +399 @@
-    Finds the inverse for an association that explicity defines it's inverse
+    Finds the inverse for an association that explicitly defines it's inverse
--- ./lib/serializer.js	original
+++ ./lib/serializer.js	fixed
@@ -374 +374 @@
-    This method is used by the POST and PUT shorthands. These shorthands expect a valid JSON:API document as part of the request, so that they know how to create or update the appropriate resouce. The *normalize* method allows you to transform your request body into a JSON:API document, which lets you take advantage of the shorthands when you otherwise may not be able to.
+    This method is used by the POST and PUT shorthands. These shorthands expect a valid JSON:API document as part of the request, so that they know how to create or update the appropriate resource. The *normalize* method allows you to transform your request body into a JSON:API document, which lets you take advantage of the shorthands when you otherwise may not be able to.
--- ./__tests__/external/shared/serializers/base/override-serialize-test.js	original
+++ ./__tests__/external/shared/serializers/base/override-serialize-test.js	fixed
@@ -64 +64 @@
-  test(`it can access the databse while in a serializer method`, () => {
+  test(`it can access the database while in a serializer method`, () => {
--- ./__tests__/external/shared/serializers/base/associations/polymorphic/has-many-test.js	original
+++ ./__tests__/external/shared/serializers/base/associations/polymorphic/has-many-test.js	fixed
@@ -17 +17 @@
-    server.schema.users.create({ things: [post], name: "Ned" });
+    server.schema.users.create({ things: [post], name: "Need" });
@@ -45 +45 @@
-        name: "Ned",
+        name: "Need",
@@ -70 +70 @@
-        name: "Ned",
+        name: "Need",
@@ -96 +96 @@
-        name: "Ned",
+        name: "Need",
--- ./__tests__/internal/unit/factory-test.js	original
+++ ./__tests__/internal/unit/factory-test.js	fixed
@@ -221 +221 @@
-  test("throws meaningfull exception on circular reference", () => {
+  test("throws meaningful exception on circular reference", () => {
--- ./__tests__/internal/unit/db-test.js	original
+++ ./__tests__/internal/unit/db-test.js	fixed
@@ -402 +402 @@
-  test("returns a copy, not a referecne", () => {
+  test("returns a copy, not a reference", () => {
--- ./__tests__/internal/move-after-handle-request/route-handlers/function-handler/normalize-request-attrs-test.js	original
+++ ./__tests__/internal/move-after-handle-request/route-handlers/function-handler/normalize-request-attrs-test.js	fixed
@@ -126 +126 @@
-  test(`it errors if the optional parameter is camelized for a model with a compount name`, async () => {
+  test(`it errors if the optional parameter is camelized for a model with a compound name`, async () => {
--- ./__tests__/internal/move-after-handle-request/shorthands/post-shorthand-with-relationships-test.js	original
+++ ./__tests__/internal/move-after-handle-request/shorthands/post-shorthand-with-relationships-test.js	fixed
@@ -12 +12 @@
-          appliction: JSONAPISerializer,
+          application: JSONAPISerializer,
