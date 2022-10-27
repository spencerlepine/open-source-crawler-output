## Detected Typos Diff
```diff
--- ./doc_source/lambda-services.md	original
+++ ./doc_source/lambda-services.md	fixed
@@ -69 +69 @@
-For more information about how Lambda manages error handling for synchronously and asychronously invoked functions, see [Error handling and automatic retries in AWS Lambda](invocation-retries.md)\.
+For more information about how Lambda manages error handling for synchronously and asynchronously invoked functions, see [Error handling and automatic retries in AWS Lambda](invocation-retries.md)\.
--- ./doc_source/extensions-api-partners.md	original
+++ ./doc_source/extensions-api-partners.md	fixed
@@ -9 +9 @@
-+ [HashiCorp Vault](https://learn.hashicorp.com/tutorials/vault/aws-lambda) – Manages secrets and makes them available for developers to use within function code, without making functions Vault aware\.
++ [HashCorp Vault](https://learn.hashicorp.com/tutorials/vault/aws-lambda) – Manages secrets and makes them available for developers to use within function code, without making functions Vault aware\.
--- ./doc_source/ruby-logging.md	original
+++ ./doc_source/ruby-logging.md	fixed
@@ -129 +129 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/invocation-sync.md	original
+++ ./doc_source/invocation-sync.md	fixed
@@ -61 +61 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/golang-logging.md	original
+++ ./doc_source/golang-logging.md	fixed
@@ -114 +114 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/java-logging.md	original
+++ ./doc_source/java-logging.md	fixed
@@ -128 +128 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/gettingstarted-awscli.md	original
+++ ./doc_source/gettingstarted-awscli.md	fixed
@@ -158 +158 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/nodejs-logging.md	original
+++ ./doc_source/nodejs-logging.md	fixed
@@ -107 +107 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/runtimes-images.md	original
+++ ./doc_source/runtimes-images.md	fixed
@@ -6 +6 @@
-Each base image is compatible with one or more of the instruction set architectures that Lambda supports\. You need to build the function image for only one architcture\. Lambda does not support multi\-architecture images\.
+Each base image is compatible with one or more of the instruction set architectures that Lambda supports\. You need to build the function image for only one architecture\. Lambda does not support multi\-architecture images\.
--- ./doc_source/powershell-logging.md	original
+++ ./doc_source/powershell-logging.md	fixed
@@ -117 +117 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/foundation-console.md	original
+++ ./doc_source/foundation-console.md	fixed
@@ -32 +32 @@
-You can use the code editor in the AWS Lambda console to write, test, and view the execution results of your Lambda function code\. The code editor supports languages that do not require compiling, such as Node\.js and Python\. The code editor suppports only \.zip archive deployment packages, and the size of the deployment package must be less than 3 MB\. 
+You can use the code editor in the AWS Lambda console to write, test, and view the execution results of your Lambda function code\. The code editor supports languages that do not require compiling, such as Node\.js and Python\. The code editor supports only \.zip archive deployment packages, and the size of the deployment package must be less than 3 MB\. 
--- ./doc_source/configuration-envvars.md	original
+++ ./doc_source/configuration-envvars.md	fixed
@@ -265 +265 @@
-   If you're using a customer managed key with server\-side encryption, grant permissions to any AWS Identity and Access Management \(IAM\) users or roles that you want to be able to view or manange environment variables on the function\. For more information, see [Managing permissions to your server\-side encryption KMS key](#managing-permissions-to-your-server-side-encryption-key)\.
+   If you're using a customer managed key with server\-side encryption, grant permissions to any AWS Identity and Access Management \(IAM\) users or roles that you want to be able to view or manage environment variables on the function\. For more information, see [Managing permissions to your server\-side encryption KMS key](#managing-permissions-to-your-server-side-encryption-key)\.
--- ./doc_source/API_CodeSigningConfig.md	original
+++ ./doc_source/API_CodeSigningConfig.md	fixed
@@ -20 +20 @@
-Unique identifer for the Code signing configuration\.  
+Unique identifier for the Code signing configuration\.  
--- ./doc_source/csharp-logging.md	original
+++ ./doc_source/csharp-logging.md	fixed
@@ -148 +148 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/python-logging.md	original
+++ ./doc_source/python-logging.md	fixed
@@ -99 +99 @@
-    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwNDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
+    "LogResult": "U1RBUlQgUmVxdWVzdElkOiA4N2QwANDRiOC1mMTU0LTExZTgtOGNkYS0yOTc0YzVlNGZiMjEgVmVyc2lvb...",
--- ./doc_source/provisioned-concurrency.md	original
+++ ./doc_source/provisioned-concurrency.md	fixed
@@ -21 +21 @@
-+ [Managing provisioned concurrency with Application Auto Scaling](#managing-provisioned-concurency)
++ [Managing provisioned concurrency with Application Auto Scaling](#managing-provisioned-concurrency)
@@ -132 +132 @@
-## Managing provisioned concurrency with Application Auto Scaling<a name="managing-provisioned-concurency"></a>
+## Managing provisioned concurrency with Application Auto Scaling<a name="managing-provisioned-concurrency"></a>
