## Detected Typos Diff
```diff
--- ./test/data/v1/npm.json	original
+++ ./test/data/v1/npm.json	fixed
@@ -4011 +4011 @@
-					"markerPattern": "^((clos|fix|resolv)(e[sd]|ing))|(refs?)",
+					"markerPattern": "^((close|fix|resolv)(e[sd]|ing))|(refs?)",
@@ -4145 +4145 @@
-					"markerPattern": "^((clos|fix|resolv)(e[sd]|ing))|^(refs?)",
+					"markerPattern": "^((close|fix|resolv)(e[sd]|ing))|^(refs?)",
@@ -4279 +4279 @@
-					"markerPattern": "^((clos|fix|resolv)(e[sd]|ing))|^(refs?)",
+					"markerPattern": "^((close|fix|resolv)(e[sd]|ing))|^(refs?)",
@@ -4413 +4413 @@
-					"markerPattern": "^((clos|fix|resolv)(e[sd]|ing))|^(refs?)",
+					"markerPattern": "^((close|fix|resolv)(e[sd]|ing))|^(refs?)",
@@ -4824 +4824 @@
-		"readme": "# jQuery\n\n> jQuery is a fast, small, and feature-rich JavaScript library.\n\nFor information on how to get started and how to use jQuery, please see [jQuery's documentation](http://api.jquery.com/).\nFor source files and issues, please visit the [jQuery repo](https://github.com/jquery/jquery).\n\nIf upgrading, please see the [blog post for 3.2.1](https://blog.jquery.com/2017/03/20/jquery-3-2-1-now-available/). This includes notable differences from the previous version and a more readable changelog.\n\n## Including jQuery\n\nBelow are some of the most common ways to include jQuery.\n\n### Browser\n\n#### Script tag\n\n```html\n<script src=\"https://code.jquery.com/jquery-3.2.1.min.js\"></script>\n```\n\n#### Babel\n\n[Babel](http://babeljs.io/) is a next generation JavaScript compiler. One of the features is the ability to use ES6/ES2015 modules now, even though browsers do not yet support this feature natively.\n\n```js\nimport $ from \"jquery\";\n```\n\n#### Browserify/Webpack\n\nThere are several ways to use [Browserify](http://browserify.org/) and [Webpack](https://webpack.github.io/). For more information on using these tools, please refer to the corresponding project's documention. In the script, including jQuery will usually look like this...\n\n```js\nvar $ = require(\"jquery\");\n```\n\n#### AMD (Asynchronous Module Definition)\n\nAMD is a module format built for the browser. For more information, we recommend [require.js' documentation](http://requirejs.org/docs/whyamd.html).\n\n```js\ndefine([\"jquery\"], function($) {\n\n});\n```\n\n### Node\n\nTo include jQuery in [Node](nodejs.org), first install with npm.\n\n```sh\nnpm install jquery\n```\n\nFor jQuery to work in Node, a window with a document is required. Since no such window exists natively in Node, one can be mocked by tools such as [jsdom](https://github.com/tmpvar/jsdom). This can be useful for testing purposes.\n\n```js\nrequire(\"jsdom\").env(\"\", function(err, window) {\n\tif (err) {\n\t\tconsole.error(err);\n\t\treturn;\n\t}\n\n\tvar $ = require(\"jquery\")(window);\n});\n```\n",
+		"readme": "# jQuery\n\n> jQuery is a fast, small, and feature-rich JavaScript library.\n\nFor information on how to get started and how to use jQuery, please see [jQuery's documentation](http://api.jquery.com/).\nFor source files and issues, please visit the [jQuery repo](https://github.com/jquery/jquery).\n\nIf upgrading, please see the [blog post for 3.2.1](https://blog.jquery.com/2017/03/20/jquery-3-2-1-now-available/). This includes notable differences from the previous version and a more readable changelog.\n\n## Including jQuery\n\nBelow are some of the most common ways to include jQuery.\n\n### Browser\n\n#### Script tag\n\n```html\n<script src=\"https://code.jquery.com/jquery-3.2.1.min.js\"></script>\n```\n\n#### Babel\n\n[Babel](http://babeljs.io/) is a next generation JavaScript compiler. One of the features is the ability to use ES6/ES2015 modules now, even though browsers do not yet support this feature natively.\n\n```js\nimport $ from \"jquery\";\n```\n\n#### Browserify/Webpack\n\nThere are several ways to use [Browserify](http://browserify.org/) and [Webpack](https://webpack.github.io/). For more information on using these tools, please refer to the corresponding project's documentation. In the script, including jQuery will usually look like this...\n\n```js\nvar $ = require(\"jquery\");\n```\n\n#### AMD (Asynchronous Module Definition)\n\nAMD is a module format built for the browser. For more information, we recommend [require.js' documentation](http://requirejs.org/docs/whyamd.html).\n\n```js\ndefine([\"jquery\"], function($) {\n\n});\n```\n\n### Node\n\nTo include jQuery in [Node](nodejs.org), first install with npm.\n\n```sh\nnpm install jquery\n```\n\nFor jQuery to work in Node, a window with a document is required. Since no such window exists natively in Node, one can be mocked by tools such as [jsdom](https://github.com/tmpvar/jsdom). This can be useful for testing purposes.\n\n```js\nrequire(\"jsdom\").env(\"\", function(err, window) {\n\tif (err) {\n\t\tconsole.error(err);\n\t\treturn;\n\t}\n\n\tvar $ = require(\"jquery\")(window);\n});\n```\n",
--- ./test/data/v1/cdn.json	original
+++ ./test/data/v1/cdn.json	fixed
@@ -632 +632 @@
-				"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+				"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
@@ -1568 +1568 @@
-				"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+				"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
@@ -3782 +3782 @@
-				"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+				"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
--- ./test/expected/v1/package.json	original
+++ ./test/expected/v1/package.json	fixed
@@ -749 +749 @@
-								"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+								"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
@@ -1668 +1668 @@
-				"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+				"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
@@ -2730 +2730 @@
-								"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+								"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
@@ -5675 +5675 @@
-								"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+								"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
@@ -7807 +7807 @@
-				"hash": "+gND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
+				"hash": "+gAND7PEyGjy4zMBPzDjNx5L80bv+rMbglBOyjehkLEc=",
