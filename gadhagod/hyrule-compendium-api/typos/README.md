## Detected Typos Diff
```diff
--- ./docs/_sidebar.md	original
+++ ./docs/_sidebar.md	fixed
@@ -4 +4 @@
-    * [API Reference](?id=api-refrence)
+    * [API Reference](?id=api-reference)
--- ./docs/client-libraries/ruby.md	original
+++ ./docs/client-libraries/ruby.md	fixed
@@ -18 +18 @@
-compendium.get_all  # get everthing
+compendium.get_all  # get everything
@@ -94 +94 @@
-* `target_entry`: Non-existant input entry that causes error.
+* `target_entry`: Non-existent input entry that causes error.
@@ -100 +100 @@
-* `target_category`: Non-existant input category that causes error.
+* `target_category`: Non-existent input category that causes error.
--- ./db/mappings/compendium.sql	original
+++ ./db/mappings/compendium.sql	fixed
@@ -1 +1 @@
--- tranformation for compendium collections
+-- transformation for compendium collections
--- ./local/README.md	original
+++ ./local/README.md	fixed
@@ -15,2 +15,2 @@
-Now to authorize access to your Rockset account retrive your api key from the rockset console and set an enviroment variable called `RS2_TOKEN` for it.
-To set a permanant enviroment variable on mac and linux:
+Now to authorize access to your Rockset account retrieve your api key from the rockset console and set an environment variable called `RS2_TOKEN` for it.
+To set a permanent environment variable on mac and linux:
@@ -25 +25 @@
-To set a session-long enviroment variable, use `export`.
+To set a session-long environment variable, use `export`.
--- ./db/data/regions.json	original
+++ ./db/data/regions.json	fixed
@@ -264 +264 @@
-                    "name": "mirro shaz",
+                    "name": "mirror shaz",
@@ -480 +480 @@
-                    "name": "maka rah",
+                    "name": "make rah",
--- ./tests/dictionary.txt	original
+++ ./tests/dictionary.txt	fixed
@@ -8 +8 @@
-Non-existant
+Non-existent
--- ./tests/test/v3.ts	original
+++ ./tests/test/v3.ts	fixed
@@ -258,4 +258,4 @@
-                    assert.equal(data.length, expectedReigonNames.length, `STATUS CODE: 200; Expected regions do not match recieved regions`);
-                    for (let i = 0; i < expectedReigonNames.length; i++) {
-                        if (!data.map((regionData => regionData.name)).includes(expectedReigonNames[i])) {
-                            assert.fail(`STATUS CODE: 200; Expected regions do not match recieved regions`);
+                    assert.equal(data.length, expectedReigonNames.length, `STATUS CODE: 200; Expected regions do not match received regions`);
+                    for (let i = 0; i < expectedReigonNames.length; i++) {
+                        if (!data.map((regionData => regionData.name)).includes(expectedReigonNames[i])) {
+                            assert.fail(`STATUS CODE: 200; Expected regions do not match received regions`);
--- ./tests/test/v2.ts	original
+++ ./tests/test/v2.ts	fixed
@@ -244 +244 @@
-                                    assert.fail("Subcategories non-existant")
+                                    assert.fail("Subcategories non-existent")
