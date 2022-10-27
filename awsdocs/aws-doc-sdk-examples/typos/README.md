## Detected Typos Diff
```diff
--- ./kotlin/services/codepipeline/src/main/kotlin/com/kotlin/pipeline/CreatePipeline.kt	original
+++ ./kotlin/services/codepipeline/src/main/kotlin/com/kotlin/pipeline/CreatePipeline.kt	fixed
@@ -32 +32 @@
-            <name> <roleArn> <s3Bucket> <s3OuputBucket>
+            <name> <roleArn> <s3Bucket> <s3OutputBucket>
@@ -38 +38 @@
-            s3OuputBucket - the name of the Amazon S3 bucket where the code is deployed.  
+            s3OutputBucket - the name of the Amazon S3 bucket where the code is deployed.  
@@ -49,2 +49,2 @@
-    val s3OuputBucket = args[3]
-    createNewPipeline(name, roleArn, s3Bucket, s3OuputBucket)
+    val s3OutputBucket = args[3]
+    createNewPipeline(name, roleArn, s3Bucket, s3OutputBucket)
@@ -58 +58 @@
-    s3OuputBucket: String
+    s3OutputBucket: String
@@ -89 +89 @@
-    mapConfig1["BucketName"] = s3OuputBucket
+    mapConfig1["BucketName"] = s3OutputBucket
--- ./kotlin/services/stepfunctions/src/main/kotlin/com/kotlin/stepfunctions/ListActivities.kt	original
+++ ./kotlin/services/stepfunctions/src/main/kotlin/com/kotlin/stepfunctions/ListActivities.kt	fixed
@@ -26 +26 @@
-    listAllActivites()
+    listAllActivities()
@@ -30 +30 @@
-suspend fun listAllActivites() {
+suspend fun listAllActivities() {
--- ./kotlin/services/kms/src/main/kotlin/com/kotlin/kms/DescribeKey.kt	original
+++ ./kotlin/services/kms/src/main/kotlin/com/kotlin/kms/DescribeKey.kt	fixed
@@ -41 +41 @@
-    describeSpecifcKey(keyId)
+    describeSpecificKey(keyId)
@@ -45 +45 @@
-suspend fun describeSpecifcKey(keyIdVal: String?) {
+suspend fun describeSpecificKey(keyIdVal: String?) {
--- ./kotlin/services/lex/src/main/kotlin/com/kotlin/lex/PostText.kt	original
+++ ./kotlin/services/lex/src/main/kotlin/com/kotlin/lex/PostText.kt	fixed
@@ -49,2 +49,2 @@
-    val textReponse = getText(inputText, botName, botAlias)
-    println(textReponse)
+    val textResponse = getText(inputText, botName, botAlias)
+    println(textResponse)
--- ./kotlin/services/pinpoint/src/main/kotlin/com/kotlin/pinpoint/ListSegments.kt	original
+++ ./kotlin/services/pinpoint/src/main/kotlin/com/kotlin/pinpoint/ListSegments.kt	fixed
@@ -55 +55 @@
-            println("Segement id is ${segment.id}")
+            println("Segment id is ${segment.id}")
--- ./kotlin/services/autoscale/src/main/kotlin/com/example/autoscaling/AutoScalingScenario.kt	original
+++ ./kotlin/services/autoscale/src/main/kotlin/com/example/autoscaling/AutoScalingScenario.kt	fixed
@@ -127,3 +127,3 @@
-// snippet-start:[autoscale.kotlin.describe_scaling_activites.main]
-suspend fun describeAutoScalingGroups(groupName: String) {
-    val groupsReques = DescribeAutoScalingGroupsRequest {
+// snippet-start:[autoscale.kotlin.describe_scaling_activities.main]
+suspend fun describeAutoScalingGroups(groupName: String) {
+    val groupsRequest = DescribeAutoScalingGroupsRequest {
@@ -135 +135 @@
-        val response = autoScalingClient.describeAutoScalingGroups(groupsReques)
+        val response = autoScalingClient.describeAutoScalingGroups(groupsRequest)
@@ -141 +141 @@
-// snippet-end:[autoscale.kotlin.describe_scaling_activites.main]
+// snippet-end:[autoscale.kotlin.describe_scaling_activities.main]
--- ./kotlin/services/dynamodb/src/main/kotlin/com/kotlin/dynamodb/Scenario.kt	original
+++ ./kotlin/services/dynamodb/src/main/kotlin/com/kotlin/dynamodb/Scenario.kt	fixed
@@ -71 +71 @@
-    deletIssuesTable(tableName)
+    deleteIssuesTable(tableName)
@@ -192 +192 @@
-suspend fun deletIssuesTable(tableNameVal: String) {
+suspend fun deleteIssuesTable(tableNameVal: String) {
--- ./kotlin/usecases/creating_workflows_stepfunctions/src/main/kotlin/example2/PersistCase.kt	original
+++ ./kotlin/usecases/creating_workflows_stepfunctions/src/main/kotlin/example2/PersistCase.kt	fixed
@@ -23 +23 @@
-        val formatedDate = formatter.format(date)
+        val formattedDate = formatter.format(date)
@@ -31 +31 @@
-        itemValues["registrationDate"] = AttributeValue.S(formatedDate)
+        itemValues["registrationDate"] = AttributeValue.S(formattedDate)
--- ./kotlin/usecases/creating_workflows_stepfunctions/Readme.md	original
+++ ./kotlin/usecases/creating_workflows_stepfunctions/Readme.md	fixed
@@ -364 +364 @@
-This Kotlin code represents the **Handler** class that creates a Lamdba function that reads the ticket ID value that is passed to the workflow. Notice that you can log messages to Amazon CloudWatch logs by using a **LambdaLogger** object. The **handleRequest** method returns the ticket ID value that is passed to the second step in the workflow. Notice that the **handleRequest** method uses **runBlocking** and the return vlaue uses **return@runBlocking**. These are required when creating a Lambda function by using the AWS SDK for Kotlin. 
+This Kotlin code represents the **Handler** class that creates a Lamdba function that reads the ticket ID value that is passed to the workflow. Notice that you can log messages to Amazon CloudWatch logs by using a **LambdaLogger** object. The **handleRequest** method returns the ticket ID value that is passed to the second step in the workflow. Notice that the **handleRequest** method uses **runBlocking** and the return value uses **return@runBlocking**. These are required when creating a Lambda function by using the AWS SDK for Kotlin. 
@@ -494 +494 @@
-        val formatedDate = formatter.format(date)
+        val formattedDate = formatter.format(date)
@@ -502 +502 @@
-        itemValues["registrationDate"] = AttributeValue.S(formatedDate)
+        itemValues["registrationDate"] = AttributeValue.S(formattedDate)
--- ./kotlin/usecases/first_android_app/Readme.md	original
+++ ./kotlin/usecases/first_android_app/Readme.md	fixed
@@ -31 +31 @@
-+ Add the dependencies to your Andorid project
++ Add the dependencies to your Android project
--- ./kotlin/usecases/subpub_app_android/Readme.md	original
+++ ./kotlin/usecases/subpub_app_android/Readme.md	fixed
@@ -24 +24 @@
-+ Add the dependencies to your Andorid project
++ Add the dependencies to your Android project
@@ -62 +62 @@
-The specified email address recieves an email message that lets the recipient confirm the subscription. 
+The specified email address receives an email message that lets the recipient confirm the subscription. 
@@ -66 +66 @@
-Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and recieves published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
+Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and receives published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
--- ./kotlin/usecases/itemtracker_dynamodb/src/main/kotlin/com/aws/rest/DynamoDBService.kt	original
+++ ./kotlin/usecases/itemtracker_dynamodb/src/main/kotlin/com/aws/rest/DynamoDBService.kt	fixed
@@ -192 +192 @@
-        val formatedDate = formatter.format(date)
+        val formattedDate = formatter.format(date)
@@ -199 +199 @@
-        itemValues["date"] = AttributeValue.S(formatedDate)
+        itemValues["date"] = AttributeValue.S(formattedDate)
--- ./kotlin/usecases/itemtracker_dynamodb/Readme.md	original
+++ ./kotlin/usecases/itemtracker_dynamodb/Readme.md	fixed
@@ -481 +481 @@
-        val formatedDate = formatter.format(date)
+        val formattedDate = formatter.format(date)
@@ -490 +490 @@
-        itemValues["date"] = AttributeValue.S(formatedDate)
+        itemValues["date"] = AttributeValue.S(formattedDate)
--- ./kotlin/usecases/subpub_app/Readme.md	original
+++ ./kotlin/usecases/subpub_app/Readme.md	fixed
@@ -47 +47 @@
-The specified email address recieves an email message that lets the recipient confirm the subscription. 
+The specified email address receives an email message that lets the recipient confirm the subscription. 
@@ -51 +51 @@
-Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and recieves published messages. To publish a message, a user enters the message into the web applicaiton and then chooses the **Publish** button. 
+Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and receives published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
--- ./resources/cfn/go_example_lambda/GoCdkStack.template.json	original
+++ ./resources/cfn/go_example_lambda/GoCdkStack.template.json	fixed
@@ -606 +606 @@
-          "ZipFile": "exports.handler = (event, context) => {\n    // eslint-disable-next-line @typescript-eslint/no-require-imports, import/no-extraneous-dependencies\n    const s3 = new (require('aws-sdk').S3)();\n    // eslint-disable-next-line @typescript-eslint/no-require-imports\n    const https = require('https');\n    // eslint-disable-next-line @typescript-eslint/no-require-imports\n    const url = require('url');\n    log(JSON.stringify(event, undefined, 2));\n    const props = event.ResourceProperties;\n    if (event.RequestType === 'Delete') {\n        props.NotificationConfiguration = {}; // this is how you clean out notifications\n    }\n    const req = {\n        Bucket: props.BucketName,\n        NotificationConfiguration: props.NotificationConfiguration,\n    };\n    return s3.putBucketNotificationConfiguration(req, (err, data) => {\n        log({ err, data });\n        if (err) {\n            return submitResponse('FAILED', err.message + `\\nMore information in CloudWatch Log Stream: ${context.logStreamName}`);\n        }\n        else {\n            return submitResponse('SUCCESS');\n        }\n    });\n    function log(obj) {\n        console.error(event.RequestId, event.StackId, event.LogicalResourceId, obj);\n    }\n    // eslint-disable-next-line max-len\n    // adapted from https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-lambda-function-code.html#cfn-lambda-function-code-cfnresponsemodule\n    // to allow sending an error messge as a reason.\n    function submitResponse(responseStatus, reason) {\n        const responseBody = JSON.stringify({\n            Status: responseStatus,\n            Reason: reason || 'See the details in CloudWatch Log Stream: ' + context.logStreamName,\n            PhysicalResourceId: event.PhysicalResourceId || event.LogicalResourceId,\n            StackId: event.StackId,\n            RequestId: event.RequestId,\n            LogicalResourceId: event.LogicalResourceId,\n            NoEcho: false,\n        });\n        log({ responseBody });\n        const parsedUrl = url.parse(event.ResponseURL);\n        const options = {\n            hostname: parsedUrl.hostname,\n            port: 443,\n            path: parsedUrl.path,\n            method: 'PUT',\n            headers: {\n                'content-type': '',\n                'content-length': responseBody.length,\n            },\n        };\n        const request = https.request(options, (r) => {\n            log({ statusCode: r.statusCode, statusMessage: r.statusMessage });\n            context.done();\n        });\n        request.on('error', (error) => {\n            log({ sendError: error });\n            context.done();\n        });\n        request.write(responseBody);\n        request.end();\n    }\n};"
+          "ZipFile": "exports.handler = (event, context) => {\n    // eslint-disable-next-line @typescript-eslint/no-require-imports, import/no-extraneous-dependencies\n    const s3 = new (require('aws-sdk').S3)();\n    // eslint-disable-next-line @typescript-eslint/no-require-imports\n    const https = require('https');\n    // eslint-disable-next-line @typescript-eslint/no-require-imports\n    const url = require('url');\n    log(JSON.stringify(event, undefined, 2));\n    const props = event.ResourceProperties;\n    if (event.RequestType === 'Delete') {\n        props.NotificationConfiguration = {}; // this is how you clean out notifications\n    }\n    const req = {\n        Bucket: props.BucketName,\n        NotificationConfiguration: props.NotificationConfiguration,\n    };\n    return s3.putBucketNotificationConfiguration(req, (err, data) => {\n        log({ err, data });\n        if (err) {\n            return submitResponse('FAILED', err.message + `\\nMore information in CloudWatch Log Stream: ${context.logStreamName}`);\n        }\n        else {\n            return submitResponse('SUCCESS');\n        }\n    });\n    function log(obj) {\n        console.error(event.RequestId, event.StackId, event.LogicalResourceId, obj);\n    }\n    // eslint-disable-next-line max-len\n    // adapted from https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-lambda-function-code.html#cfn-lambda-function-code-cfnresponsemodule\n    // to allow sending an error message as a reason.\n    function submitResponse(responseStatus, reason) {\n        const responseBody = JSON.stringify({\n            Status: responseStatus,\n            Reason: reason || 'See the details in CloudWatch Log Stream: ' + context.logStreamName,\n            PhysicalResourceId: event.PhysicalResourceId || event.LogicalResourceId,\n            StackId: event.StackId,\n            RequestId: event.RequestId,\n            LogicalResourceId: event.LogicalResourceId,\n            NoEcho: false,\n        });\n        log({ responseBody });\n        const parsedUrl = url.parse(event.ResponseURL);\n        const options = {\n            hostname: parsedUrl.hostname,\n            port: 443,\n            path: parsedUrl.path,\n            method: 'PUT',\n            headers: {\n                'content-type': '',\n                'content-length': responseBody.length,\n            },\n        };\n        const request = https.request(options, (r) => {\n            log({ statusCode: r.statusCode, statusMessage: r.statusMessage });\n            context.done();\n        });\n        request.on('error', (error) => {\n            log({ sendError: error });\n            context.done();\n        });\n        request.write(responseBody);\n        request.end();\n    }\n};"
--- ./resources/cdk/go-apprunner/app/Dockerfile	original
+++ ./resources/cdk/go-apprunner/app/Dockerfile	fixed
@@ -13 +13 @@
-# In a production envrionment, these are generally not useful to have.
+# In a production environment, these are generally not useful to have.
--- ./resources/cdk/go_example_lambda/src/dynamodb/main.go	original
+++ ./resources/cdk/go_example_lambda/src/dynamodb/main.go	fixed
@@ -18 +18 @@
-		//   for information on AttibuteValue.
+		//   for information on AttributeValue.
--- ./python/cross_service/aurora_rest_lending_library/library_api/chalicelib/library_data.py	original
+++ ./python/cross_service/aurora_rest_lending_library/library_api/chalicelib/library_data.py	fixed
@@ -290 +290 @@
-                "Transaction %s commited with status %s.", transaction_id,
+                "Transaction %s committed with status %s.", transaction_id,
--- ./python/example_code/comprehend/README.md	original
+++ ./python/example_code/comprehend/README.md	fixed
@@ -11 +11 @@
-new issues to the classifer for labeling.
+new issues to the classifier for labeling.
--- ./python/example_code/secretsmanager/setup.yaml	original
+++ ./python/example_code/secretsmanager/setup.yaml	fixed
@@ -231 +231 @@
-  docexamplevpcforsecretsPrivateSubnet2RouteTable5053DAA3:
+  docexamplevpcforsecretsPrivateSubnet2RouteTable5053DATA3:
@@ -245 +245 @@
-        Ref: docexamplevpcforsecretsPrivateSubnet2RouteTable5053DAA3
+        Ref: docexamplevpcforsecretsPrivateSubnet2RouteTable5053DATA3
@@ -254 +254 @@
-        Ref: docexamplevpcforsecretsPrivateSubnet2RouteTable5053DAA3
+        Ref: docexamplevpcforsecretsPrivateSubnet2RouteTable5053DATA3
--- ./python/example_code/deeplens/deeplens_frameworks_mxnet.py	original
+++ ./python/example_code/deeplens/deeplens_frameworks_mxnet.py	fixed
@@ -23 +23 @@
-fake_image = mx.nd.random.uniform(shape=(1,3,224,224), ctx=mx.cpu())
+fake_image = mx.and.random.uniform(shape=(1,3,224,224), ctx=mx.cpu())
--- ./python/example_code/rekognition/custom_labels_csv_to_manifest.py	original
+++ ./python/example_code/rekognition/custom_labels_csv_to_manifest.py	fixed
@@ -30 +30 @@
-    occurence of a duplicate is recorded. Other duplicates are recorded in duplicates_file.
+    occurrence of a duplicate is recorded. Other duplicates are recorded in duplicates_file.
@@ -180 +180 @@
-            print(f"{deduplicated_file} contains the first occurence of a duplicate. "
+            print(f"{deduplicated_file} contains the first occurrence of a duplicate. "
--- ./ruby/helpers/disclaimers.rb	original
+++ ./ruby/helpers/disclaimers.rb	fixed
@@ -30 +30 @@
-  puts "For more information on the Shared Repsonsibility Model, please see:      "
+  puts "For more information on the Shared Responsibility Model, please see:      "
--- ./ruby/example_code/ec2/ec2-ruby-example-elastic-ips.rb	original
+++ ./ruby/example_code/ec2/ec2-ruby-example-elastic-ips.rb	fixed
@@ -73 +73 @@
-# @return [String] The assocation ID corresponding to the association of the
+# @return [String] The association ID corresponding to the association of the
--- ./ruby/example_code/ec2/ec2-ruby-example-get-instance-info-by-tag.rb	original
+++ ./ruby/example_code/ec2/ec2-ruby-example-get-instance-info-by-tag.rb	fixed
@@ -10 +10 @@
-# snippet-start:[ec2.Ruby.getInstanceInforByTag]
+# snippet-start:[ec2.Ruby.getInstanceInfoByTag]
@@ -78 +78 @@
-# snippet-end:[ec2.Ruby.getInstanceInforByTag]
+# snippet-end:[ec2.Ruby.getInstanceInfoByTag]
--- ./ruby/example_code/cloudwatch/cw-ruby-example-alarm-actions.rb	original
+++ ./ruby/example_code/cloudwatch/cw-ruby-example-alarm-actions.rb	fixed
@@ -29 +29 @@
-# @param theshold [Float] The value against which the specified statistic is compared.
+# @param threshold [Float] The value against which the specified statistic is compared.
--- ./ruby/example_code/cloudwatch/cw-ruby-example-create-alarm.rb	original
+++ ./ruby/example_code/cloudwatch/cw-ruby-example-create-alarm.rb	fixed
@@ -26 +26 @@
-# @param theshold [Float] The value against which the specified statistic is compared.
+# @param threshold [Float] The value against which the specified statistic is compared.
--- ./ruby/example_code/cloudwatch/cw-ruby-example-alarm-basics.rb	original
+++ ./ruby/example_code/cloudwatch/cw-ruby-example-alarm-basics.rb	fixed
@@ -49 +49 @@
-# @param theshold [Float] The value against which the specified statistic is compared.
+# @param threshold [Float] The value against which the specified statistic is compared.
--- ./ruby/example_code/dynamodb/GettingStarted/MoviesScan.rb	original
+++ ./ruby/example_code/dynamodb/GettingStarted/MoviesScan.rb	fixed
@@ -6 +6 @@
-# If an item matches the specified search condition, then informaton about
+# If an item matches the specified search condition, then information about
--- ./ruby/example_code/dynamodb/GettingStarted/MoviesQuery02.rb	original
+++ ./ruby/example_code/dynamodb/GettingStarted/MoviesQuery02.rb	fixed
@@ -6 +6 @@
-# If an item matches the specified search condition, then informaton about
+# If an item matches the specified search condition, then information about
--- ./ruby/example_code/dynamodb/GettingStarted/MoviesQuery01.rb	original
+++ ./ruby/example_code/dynamodb/GettingStarted/MoviesQuery01.rb	fixed
@@ -6 +6 @@
-# If an item matches the specified search condition, then informaton about
+# If an item matches the specified search condition, then information about
--- ./ruby/example_code/dynamodb/GettingStarted/README.md	original
+++ ./ruby/example_code/dynamodb/GettingStarted/README.md	fixed
@@ -45 +45 @@
-  [Download Ruby](https://www.ruby-lang.org/en/downloads/) on the Ruby Progamming Language website.
+  [Download Ruby](https://www.ruby-lang.org/en/downloads/) on the Ruby Programming Language website.
--- ./ruby/example_code/dynamodb/GettingStarted/MoviesCreateTable.rb	original
+++ ./ruby/example_code/dynamodb/GettingStarted/MoviesCreateTable.rb	fixed
@@ -7 +7 @@
-# consisting of a 'year' hash/partition key attrribute and a
+# consisting of a 'year' hash/partition key attribute and a
--- ./php/example_code/s3/s3_basics/testfile.txt	original
+++ ./php/example_code/s3/s3_basics/testfile.txt	fixed
@@ -1 +1 @@
-Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla dolor, varius vel vehicula vitae, dapibus id tellus. Vivamus nisl risus, pretium in nisi non, venenatis rhoncus ligula. Sed pharetra nibh nulla. Integer vitae mollis nisi. Nunc ante nulla, cursus id dolor sit amet, suscipit molestie est. Vestibulum sollicitudin fermentum arcu ut dictum. Sed finibus feugiat libero, sit amet fermentum ex consequat auctor. Donec varius fringilla sagittis. Sed gravida efficitur erat et viverra. Nulla malesuada metus vitae lacus malesuada, at faucibus velit tincidunt. Cras fermentum blandit purus. Integer rutrum semper lorem, rutrum aliquet elit egestas ac. Integer tincidunt sem nec turpis aliquet consectetur. Nunc accumsan est leo, ut tincidunt turpis interdum in. Ut finibus nibh et ullamcorper pharetra.
+Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla dolor, various vel vehicula vitae, dapibus id tellus. Vivamus nisl risus, pretium in nisi non, venenatis rhoncus ligula. Sed pharetra nibh nulla. Integer vitae mollis nisi. Nunc ante nulla, cursus id dolor sit amet, suscipit molestie est. Vestibulum sollicitudin fermentum arcu ut dictum. Sed finibus feugiat libero, sit amet fermentum ex consequat auctor. Donec various fringilla sagittis. Sed gravida efficitur erat et viverra. Nulla malesuada metus vitae lacus malesuada, at faucibus velit tincidunt. Cras fermentum blandit purus. Integer rutrum semper lorem, rutrum aliquet elit egestas ac. Integer tincidunt sem nec turpis aliquet consectetur. Nunc accumsan est leo, ut tincidunt turpis interdum in. Ut finibus nibh et ullamcorper pharetra.
@@ -3 +3 @@
-Duis sodales odio velit, nec ornare leo venenatis ut. Pellentesque in libero sit amet libero vestibulum lobortis. Vivamus laoreet ex eget mi suscipit, vitae volutpat felis iaculis. Etiam rhoncus ac arcu nec commodo. Phasellus posuere, mi eget egestas tincidunt, orci tellus placerat turpis, sit amet blandit nibh magna eu est. Nunc ultrices tincidunt rhoncus. Praesent faucibus id augue quis laoreet. Maecenas ac pellentesque eros, id pellentesque magna. Integer faucibus auctor ante. Mauris vitae pharetra erat. Nulla facilisi. Fusce ac ex libero. Duis posuere lacus lectus, ut varius sapien efficitur eget. Nunc enim urna, congue non tristique id, consequat eget nisi. Nulla in massa sit amet nisi rhoncus tempor sagittis id erat.
+Duis sodales odio velit, nec ornare leo venenatis ut. Pellentesque in libero sit amet libero vestibulum lobortis. Vivamus laoreet ex eget mi suscipit, vitae volutpat felis iaculis. Etiam rhoncus ac arcu nec commodo. Phasellus posuere, mi eget egestas tincidunt, orci tellus placerat turpis, sit amet blandit nibh magna eu est. Nunc ultrices tincidunt rhoncus. Praesent faucibus id augue quis laoreet. Maecenas ac pellentesque eros, id pellentesque magna. Integer faucibus auctor ante. Mauris vitae pharetra erat. Nulla facilities. Fusce ac ex libero. Duis posuere lacus lectus, ut various sapien efficitur eget. Nunc enim urna, congue non tristique id, consequat eget nisi. Nulla in massa sit amet nisi rhoncus tempor sagittis id erat.
--- ./php/example_code/s3/s3_basics/Readme.md	original
+++ ./php/example_code/s3/s3_basics/Readme.md	fixed
@@ -50 +50 @@
-Once your composer depencies are successfully installed, you can run the getting started file directly with:
+Once your composer dependencies are successfully installed, you can run the getting started file directly with:
--- ./php/example_code/s3/MultipartUploadErrorHandeling.php	original
+++ ./php/example_code/s3/MultipartUploadErrorHandling.php	fixed
@@ -64 +64 @@
-// snippet-sourcedescription:[MultipartUploadErrorHandeling.php demonstrates how to use UploadState  to resume an upload that failed to complete.]
+// snippet-sourcedescription:[MultipartUploadErrorHandling.php demonstrates how to use UploadState  to resume an upload that failed to complete.]
--- ./php/example_code/s3/MultipartUploadCustimized.php	original
+++ ./php/example_code/s3/MultipartUploadCustomized.php	fixed
@@ -59 +59 @@
-// snippet-sourcedescription:[MultipartUploadCustimized.php demonstrates how to set custom options on the CreateMultipartUpload, UploadPart, and CompleteMultipartUpload operations executed by the multipart uploader via callbacks passed to its constructor.]
+// snippet-sourcedescription:[MultipartUploadCustomized.php demonstrates how to set custom options on the CreateMultipartUpload, UploadPart, and CompleteMultipartUpload operations executed by the multipart uploader via callbacks passed to its constructor.]
--- ./php/example_code/translate/TranslateText.php	original
+++ ./php/example_code/translate/TranslateText.php	fixed
@@ -20,2 +20,2 @@
-// snippet-start:[translate.php.traslate_text.complete]
-// snippet-start:[translate.php.traslate_text.import]
+// snippet-start:[translate.php.translate_text.complete]
+// snippet-start:[translate.php.translate_text.import]
@@ -27 +27 @@
-// snippet-end:[translate.php.traslate_text.import]
+// snippet-end:[translate.php.translate_text.import]
@@ -37 +37 @@
-// snippet-start:[translate.php.traslate_text.main]
+// snippet-start:[translate.php.translate_text.main]
@@ -72,2 +72,2 @@
-// snippet-end:[translate.php.traslate_text.main]
-// snippet-end:[translate.php.traslate_text.complete]
+// snippet-end:[translate.php.translate_text.main]
+// snippet-end:[translate.php.translate_text.complete]
--- ./php/example_code/sqs/ReceiveMessage.php	original
+++ ./php/example_code/sqs/ReceiveMessage.php	fixed
@@ -19,2 +19,2 @@
-// snippet-start:[sqs.php.recieve_message.complete]
-// snippet-start:[sqs.php.recieve_message.import]
+// snippet-start:[sqs.php.receive_message.complete]
+// snippet-start:[sqs.php.receive_message.import]
@@ -25 +25 @@
-// snippet-end:[sqs.php.recieve_message.import]
+// snippet-end:[sqs.php.receive_message.import]
@@ -33 +33 @@
-// snippet-start:[sqs.php.recieve_message.main]
+// snippet-start:[sqs.php.receive_message.main]
@@ -66,2 +66,2 @@
-// snippet-end:[sqs.php.recieve_message.main]
-// snippet-end:[sqs.php.recieve_message.complete]
+// snippet-end:[sqs.php.receive_message.main]
+// snippet-end:[sqs.php.receive_message.complete]
--- ./php/example_code/sqs/LongPollingReceiveMessage.php	original
+++ ./php/example_code/sqs/LongPollingReceiveMessage.php	fixed
@@ -19,2 +19,2 @@
-// snippet-start:[sqs.php.long_polling_recieve_message.complete]
-// snippet-start:[sqs.php.long_polling_recieve_message.import]
+// snippet-start:[sqs.php.long_polling_receive_message.complete]
+// snippet-start:[sqs.php.long_polling_receive_message.import]
@@ -25 +25 @@
-// snippet-end:[sqs.php.long_polling_recieve_message.import]
+// snippet-end:[sqs.php.long_polling_receive_message.import]
@@ -33 +33 @@
-// snippet-start:[sqs.php.long_polling_recieve_message.main]
+// snippet-start:[sqs.php.long_polling_receive_message.main]
@@ -58,2 +58,2 @@
-// snippet-end:[sqs.php.long_polling_recieve_message.main]
-// snippet-end:[sqs.php.long_polling_recieve_message.complete]
+// snippet-end:[sqs.php.long_polling_receive_message.main]
+// snippet-end:[sqs.php.long_polling_receive_message.complete]
--- ./php/example_code/securityhub/InviteMembers.php	original
+++ ./php/example_code/securityhub/InviteMembers.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./php/example_code/securityhub/GetFindings.php	original
+++ ./php/example_code/securityhub/GetFindings.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./php/example_code/securityhub/EnableSecurityHub.php	original
+++ ./php/example_code/securityhub/EnableSecurityHub.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./php/example_code/securityhub/ListInvitations.php	original
+++ ./php/example_code/securityhub/ListInvitations.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./php/example_code/securityhub/DeleteMembers.php	original
+++ ./php/example_code/securityhub/DeleteMembers.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./php/example_code/securityhub/DisableSecurityHub.php	original
+++ ./php/example_code/securityhub/DisableSecurityHub.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./php/example_code/securityhub/GetInsights.php	original
+++ ./php/example_code/securityhub/GetInsights.php	fixed
@@ -30 +30 @@
-// Create a Securty Hub Client
+// Create a Security Hub Client
--- ./dotnetv3/Rekognition/FaceRekognitionExample/FaceRekognitionExample/FaceRekognition.cs	original
+++ ./dotnetv3/Rekognition/FaceRekognitionExample/FaceRekognitionExample/FaceRekognition.cs	fixed
@@ -56 +56 @@
-        /// contins images of celebrities.</param>
+        /// contains images of celebrities.</param>
@@ -118 +118 @@
-        /// contins faces.</param>
+        /// contains faces.</param>
--- ./dotnetv3/SecretsManager/GetSecretValue/GetSecretValueExample/GetSecretValue.cs	original
+++ ./dotnetv3/SecretsManager/GetSecretValue/GetSecretValueExample/GetSecretValue.cs	fixed
@@ -56 +56 @@
-        /// <returns>The GetSecretValueReponse object returned by
+        /// <returns>The GetSecretValueResponse object returned by
--- ./dotnetv3/cross-service/DynamodbWebApp/WebApplicationDynamoDB/Controllers/DynamoDBService.cs	original
+++ ./dotnetv3/cross-service/DynamodbWebApp/WebApplicationDynamoDB/Controllers/DynamoDBService.cs	fixed
@@ -52 +52 @@
-            return "Item " + id + " was succefully updated";
+            return "Item " + id + " was successfully updated";
--- ./dotnetv3/cross-service/DynamodbWebApp/Readme.md	original
+++ ./dotnetv3/cross-service/DynamodbWebApp/Readme.md	fixed
@@ -319 +319 @@
-            return "Item " + id + " was succefully updated";
+            return "Item " + id + " was successfully updated";
--- ./dotnetv3/cross-service/DynamodbWebApp/images/Example.txt	original
+++ ./dotnetv3/cross-service/DynamodbWebApp/images/Example.txt	fixed
@@ -324 +324 @@
-            return "Item "+ id + " was succefully updated";
+            return "Item "+ id + " was successfully updated";
--- ./dotnetv3/cross-service/react_dotnet/ItemTrackerRDSRest/RDSService.cs	original
+++ ./dotnetv3/cross-service/react_dotnet/ItemTrackerRDSRest/RDSService.cs	fixed
@@ -188 +188 @@
-        // Modfies a record in the Work table.
+        // Modifies a record in the Work table.
--- ./dotnetv3/cross-service/react_dotnet/Readme.md	original
+++ ./dotnetv3/cross-service/react_dotnet/Readme.md	fixed
@@ -442 +442 @@
-        // Modfies a record in the Work table.
+        // Modifies a record in the Work table.
--- ./dotnetv3/cross-service/SubscribePublishTranslate/Readme.md	original
+++ ./dotnetv3/cross-service/SubscribePublishTranslate/Readme.md	fixed
@@ -52 +52 @@
-The specified email address recieves an email message that asks the recipient to confirm the subscription. 
+The specified email address receives an email message that asks the recipient to confirm the subscription. 
@@ -56 +56 @@
-Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and recieves published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
+Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and receives published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
@@ -132 +132 @@
-The following C# code represents the **HomeController** class. Becasue the Async version of the AWS SDK for .NET is used, notice that the controller methods have to use **async** keywords and the return values are defined using **Task**. 
+The following C# code represents the **HomeController** class. Because the Async version of the AWS SDK for .NET is used, notice that the controller methods have to use **async** keywords and the return values are defined using **Task**. 
@@ -207 +207 @@
-In the code for the SnsService controller, be sure to change the AWS Region in the constructor call for the client object to the region where your rescources are defined. For example, in the first l ine of the UnSubEmail method, change:
+In the code for the SnsService controller, be sure to change the AWS Region in the constructor call for the client object to the region where your resources are defined. For example, in the first l ine of the UnSubEmail method, change:
--- ./dotnetv3/Glue/scenarios/Glue_Basics_Scenario/Glue_Basics/GlueMethods.cs	original
+++ ./dotnetv3/Glue/scenarios/Glue_Basics_Scenario/Glue_Basics/GlueMethods.cs	fixed
@@ -427 +427 @@
-            Console.WriteLine($"No informaton about {databaseName}.");
+            Console.WriteLine($"No information about {databaseName}.");
--- ./dotnetv3/Glue/scenarios/Glue_Basics_Scenario/Glue_Basics/GlueBasics.cs	original
+++ ./dotnetv3/Glue/scenarios/Glue_Basics_Scenario/Glue_Basics/GlueBasics.cs	fixed
@@ -74 +74 @@
-Console.WriteLine("Deleting the AWS Glue job used by the exmple.");
+Console.WriteLine("Deleting the AWS Glue job used by the example.");
--- ./dotnetv3/IAM/ListSAMLProvidersExample/ListSAMLProviders.cs	original
+++ ./dotnetv3/IAM/ListSAMLProvidersExample/ListSAMLProviders.cs	fixed
@@ -4 +4 @@
-// Lists the avaiable SAML providers defined using the Amazon Identity
+// Lists the available SAML providers defined using the Amazon Identity
--- ./dotnetv3/IAM/IAM_Basics_Scenario/IAM_Basics_Scenario/IAM_Basics.cs	original
+++ ./dotnetv3/IAM/IAM_Basics_Scenario/IAM_Basics_Scenario/IAM_Basics.cs	fixed
@@ -181 +181 @@
-        /// <param name="policyName">The name of the poicy to create.</param>
+        /// <param name="policyName">The name of the policy to create.</param>
--- ./dotnetv3/IAM/README.md	original
+++ ./dotnetv3/IAM/README.md	fixed
@@ -28 +28 @@
-- [Detach a policy from a role](DetachRolePolicyExample/DetachRolePolicyExample/DetachRolePolicy.cs) (`DetatchRolePolicyAsync`)
+- [Detach a policy from a role](DetachRolePolicyExample/DetachRolePolicyExample/DetachRolePolicy.cs) (`DetachRolePolicyAsync`)
--- ./dotnetv3/S3/UploadFileMPULowLevelAPIExample/UploadFileMPULowLevelAPI.cs	original
+++ ./dotnetv3/S3/UploadFileMPULowLevelAPIExample/UploadFileMPULowLevelAPI.cs	fixed
@@ -7 +7 @@
-/// example was created using the AWS SDK for .NET verion 3.7 and
+/// example was created using the AWS SDK for .NET version 3.7 and
--- ./dotnetv3/S3/versioned-examples/ListObjectVersionsExample/ListObjectVersions.cs	original
+++ ./dotnetv3/S3/versioned-examples/ListObjectVersionsExample/ListObjectVersions.cs	fixed
@@ -7 +7 @@
-/// the AWS SDK for .NET verion 3.7 and .NET Core 5.0.
+/// the AWS SDK for .NET version 3.7 and .NET Core 5.0.
--- ./dotnetv3/S3/GenPresignedURLExample/GenPresignedUrl.cs	original
+++ ./dotnetv3/S3/GenPresignedURLExample/GenPresignedUrl.cs	fixed
@@ -41 +41 @@
-        /// in the ojbectKey parameter for the amount of time specified in the
+        /// in the objectKey parameter for the amount of time specified in the
--- ./dotnetv3/S3/TransferAccelerationExample/TransferAcceleration.cs	original
+++ ./dotnetv3/S3/TransferAccelerationExample/TransferAcceleration.cs	fixed
@@ -22 +22 @@
-        /// The main method initalizes the client object and sets the
+        /// The main method initializes the client object and sets the
--- ./dotnetv3/S3/ServerAccessLoggingExample/ServerAccessLogging.cs	original
+++ ./dotnetv3/S3/ServerAccessLoggingExample/ServerAccessLogging.cs	fixed
@@ -75 +75 @@
-        /// will be prepended to each log oject.
+        /// will be prepended to each log object.
--- ./dotnetv3/S3/README.md	original
+++ ./dotnetv3/S3/README.md	fixed
@@ -54 +54 @@
-- [Tag an object in a bucket](ObjectTagExample/ObjectTag.cs) (`PutOjectAsync`, `PutObjectTaggingAsync`)
+- [Tag an object in a bucket](ObjectTagExample/ObjectTag.cs) (`PutObjectAsync`, `PutObjectTaggingAsync`)
--- ./dotnetv3/S3/DualStackEndpointExample/DualStackEndpoint.cs	original
+++ ./dotnetv3/S3/DualStackEndpointExample/DualStackEndpoint.cs	fixed
@@ -7 +7 @@
-/// The example was created using the AWS SDK for .NET verion 3.7 and .NET
+/// The example was created using the AWS SDK for .NET version 3.7 and .NET
--- ./dotnetv3/S3/scenarios/TransferUtilityBasics/TransferUtilityBasics/TransferBasics.cs	original
+++ ./dotnetv3/S3/scenarios/TransferUtilityBasics/TransferUtilityBasics/TransferBasics.cs	fixed
@@ -80 +80 @@
-    Console.WriteLine($"{downloadPath} now contains the fillowing files:");
+    Console.WriteLine($"{downloadPath} now contains the following files:");
--- ./dotnetv3/Comprehend/DetectingSyntaxExample/DetectingSyntaxExample/DetectingSyntax.cs	original
+++ ./dotnetv3/Comprehend/DetectingSyntaxExample/DetectingSyntaxExample/DetectingSyntax.cs	fixed
@@ -20 +20 @@
-        /// This method calls DetectSynaxAsync to identify the syntax elements
+        /// This method calls DetectSyntaxAsync to identify the syntax elements
--- ./dotnetv3/Comprehend/DetectSentimentExample/DetectSentimentExample/DetectSentiment.cs	original
+++ ./dotnetv3/Comprehend/DetectSentimentExample/DetectSentimentExample/DetectSentiment.cs	fixed
@@ -21 +21 @@
-        /// supplied text and determine the overal sentiment.
+        /// supplied text and determine the overall sentiment.
--- ./dotnetv3/Organizations/CreateAccountExample/CreateAccountExample/CreateAccount.cs	original
+++ ./dotnetv3/Organizations/CreateAccountExample/CreateAccountExample/CreateAccount.cs	fixed
@@ -37 +37 @@
-            Console.WriteLine($"The staus of {status.AccountName} is {status.State}.");
+            Console.WriteLine($"The status of {status.AccountName} is {status.State}.");
--- ./dotnetv3/Lambda/ListFunctionsExample/ListFunctionsExample/ListFunctions.cs	original
+++ ./dotnetv3/Lambda/ListFunctionsExample/ListFunctionsExample/ListFunctions.cs	fixed
@@ -35 +35 @@
-            // Get the list again useing a Lambda client paginator.
+            // Get the list again using a Lambda client paginator.
--- ./dotnetv3/Lambda/scenarios/Lambda_Basics/Lambda_Basics/LambdaMethods.cs	original
+++ ./dotnetv3/Lambda/scenarios/Lambda_Basics/Lambda_Basics/LambdaMethods.cs	fixed
@@ -108,2 +108,2 @@
-            var reponse = await client.ListFunctionsAsync();
-            var functionList = reponse.Functions;
+            var response = await client.ListFunctionsAsync();
+            var functionList = response.Functions;
@@ -176,2 +176,2 @@
-            var reponse = await client.CreateFunctionAsync(createFunctionRequest);
-            return reponse.FunctionArn;
+            var response = await client.CreateFunctionAsync(createFunctionRequest);
+            return response.FunctionArn;
--- ./dotnetv3/dynamodb/FromSQL/UpdateItemExample/UpdateItemExample/UpdateItem.cs	original
+++ ./dotnetv3/dynamodb/FromSQL/UpdateItemExample/UpdateItemExample/UpdateItem.cs	fixed
@@ -87 +87 @@
-            // Silenty ignores issue if id does not identify an order
+            // Silently ignores issue if id does not identify an order
@@ -105 +105 @@
-        /// <param name="id">The Id of the item to be udpated.</param>
+        /// <param name="id">The Id of the item to be updated.</param>
--- ./dotnetv3/dynamodb/high-level-api/HighLevelBatchWriteItemExample/HighLevelBatchWriteItemExample/HighLevelBatchWriteItem.cs	original
+++ ./dotnetv3/dynamodb/high-level-api/HighLevelBatchWriteItemExample/HighLevelBatchWriteItemExample/HighLevelBatchWriteItem.cs	fixed
@@ -16 +16 @@
-    /// This example was written using the AWS SDK for .NET verion 3.7 and .NET
+    /// This example was written using the AWS SDK for .NET version 3.7 and .NET
--- ./javascript/example_code/mediaconvert/emc_getendpoint.js	original
+++ ./javascript/example_code/mediaconvert/emc_getendpoint.js	fixed
@@ -28 +28 @@
-// snippet-start:[mediaconvert.JavaScript.endoint.describeEndpoints]
+// snippet-start:[mediaconvert.JavaScript.endpoint.describeEndpoints]
@@ -51 +51 @@
-// snippet-end:[mediaconvert.JavaScript.endoint.describeEndpoints]
+// snippet-end:[mediaconvert.JavaScript.endpoint.describeEndpoints]
--- ./javascript/example_code/kinesis/blog_page.html	original
+++ ./javascript/example_code/kinesis/blog_page.html	fixed
@@ -18 +18 @@
- snippet-sourcedescription:[blog_page.html contains the HTML for the scroll-progress exmaple]
+ snippet-sourcedescription:[blog_page.html contains the HTML for the scroll-progress example]
--- ./javav2/README.rst	original
+++ ./javav2/README.rst	fixed
@@ -27 +27 @@
-  After you set your AWS credentails in the credentials file located in the .aws folder, you can create a service client like this.
+  After you set your AWS credentials in the credentials file located in the .aws folder, you can create a service client like this.
@@ -74 +74 @@
-+ `Creating a dynamic web application that analyzes photos using the AWS SDK for Java <https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/javav2/usecases/creating_photo_analyzer_app>`_ - Discusses using the AWS SDK for Java and various AWS services, such as Amazon Rekognition, to analyze images. This web MVC applicatio analyzes many images and generate a report that breaks down each image into a series of labels.
++ `Creating a dynamic web application that analyzes photos using the AWS SDK for Java <https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/javav2/usecases/creating_photo_analyzer_app>`_ - Discusses using the AWS SDK for Java and various AWS services, such as Amazon Rekognition, to analyze images. This web MVC application analyzes many images and generate a report that breaks down each image into a series of labels.
--- ./javav2/usecases/Creating_Spring_RDS_ Rest/src/main/java/com/aws/rest/WorkItemRepository.java	original
+++ ./javav2/usecases/Creating_Spring_RDS_ Rest/src/main/java/com/aws/rest/WorkItemRepository.java	fixed
@@ -79 +79 @@
-        List<SqlParameter> paremeters = List.of(
+        List<SqlParameter> parameters = List.of(
@@ -89 +89 @@
-        ExecuteStatementResponse result = execute(sql, paremeters);
+        ExecuteStatementResponse result = execute(sql, parameters);
--- ./javav2/usecases/Creating_Spring_RDS_ Rest/Readme.md	original
+++ ./javav2/usecases/Creating_Spring_RDS_ Rest/Readme.md	fixed
@@ -534 +534 @@
-        List<SqlParameter> paremeters = List.of(
+        List<SqlParameter> parameters = List.of(
@@ -544 +544 @@
-        ExecuteStatementResponse result = execute(sql, paremeters);
+        ExecuteStatementResponse result = execute(sql, parameters);
--- ./javav2/usecases/CreatingSpringRedshiftRest/src/main/java/com/aws/rest/WorkItemRepository.java	original
+++ ./javav2/usecases/CreatingSpringRedshiftRest/src/main/java/com/aws/rest/WorkItemRepository.java	fixed
@@ -196 +196 @@
-            List<SqlParameter> paremeters = List.of(
+            List<SqlParameter> parameters = List.of(
@@ -206 +206 @@
-            ExecuteStatementResponse result = execute(sql, paremeters);
+            ExecuteStatementResponse result = execute(sql, parameters);
--- ./javav2/usecases/CreatingSpringRedshiftRest/Readme.md	original
+++ ./javav2/usecases/CreatingSpringRedshiftRest/Readme.md	fixed
@@ -629 +629 @@
-            List<SqlParameter> paremeters = List.of(
+            List<SqlParameter> parameters = List.of(
@@ -639 +639 @@
-            ExecuteStatementResponse result = execute(sql, paremeters);
+            ExecuteStatementResponse result = execute(sql, parameters);
--- ./javav2/usecases/creating_message_application/src/main/java/com/example/sqs/SendReceiveMessages.java	original
+++ ./javav2/usecases/creating_message_application/src/main/java/com/example/sqs/SendReceiveMessages.java	fixed
@@ -122 +122 @@
-            // Specify the Langauge code of the incoming message.
+            // Specify the Language code of the incoming message.
--- ./javav2/usecases/creating_message_application/Readme.md	original
+++ ./javav2/usecases/creating_message_application/Readme.md	fixed
@@ -474 +474 @@
-            // Specify the Langauge code of the incoming message.
+            // Specify the Language code of the incoming message.
--- ./javav2/usecases/creating_photo_analyzer_async/Readme.md	original
+++ ./javav2/usecases/creating_photo_analyzer_async/Readme.md	fixed
@@ -30 +30 @@
-**Note** To read a similiar use case that uses the AWS SDK for Java V2 synchronous clients, see [Creating a dynamic web application that analyzes photos using the AWS SDK for Java](https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/javav2/usecases/creating_photo_analyzer_app).
+**Note** To read a similar use case that uses the AWS SDK for Java V2 synchronous clients, see [Creating a dynamic web application that analyzes photos using the AWS SDK for Java](https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/javav2/usecases/creating_photo_analyzer_app).
--- ./javav2/usecases/video_analyzer_application/Readme.md	original
+++ ./javav2/usecases/video_analyzer_application/Readme.md	fixed
@@ -4 +4 @@
-You can create a Java web application that analyzes videos for label detection by using the Java SDK for Java version 2. The application created in this AWS tutorial lets you upload a video (MP4 file) to an Amazon Simple Storage Service (Amazon S3) bucket. Then the appliction uses the Amazon Rekognition service to analyze the video. The results are used to populate a data model and then a report is generated and emailed to a specific user by using the Amazon Simple Email Service (SES).
+You can create a Java web application that analyzes videos for label detection by using the Java SDK for Java version 2. The application created in this AWS tutorial lets you upload a video (MP4 file) to an Amazon Simple Storage Service (Amazon S3) bucket. Then the application uses the Amazon Rekognition service to analyze the video. The results are used to populate a data model and then a report is generated and emailed to a specific user by using the Amazon Simple Email Service (SES).
@@ -978 +978 @@
-**Note**: Specifiy valid **topicArn** and **roleArn** values. See the **Prerequisites** section at the start of this tutorial. 
+**Note**: Specify valid **topicArn** and **roleArn** values. See the **Prerequisites** section at the start of this tutorial. 
--- ./javav2/usecases/creating_dynamodb_web_app/src/main/resources/public/js/items.js	original
+++ ./javav2/usecases/creating_dynamodb_web_app/src/main/resources/public/js/items.js	fixed
@@ -64 +64 @@
-            alert("You have successfully modfied item "+msg)
+            alert("You have successfully modified item "+msg)
--- ./javav2/usecases/creating_lambda_ppe/src/main/java/com/example/ppe/SendEmail.java	original
+++ ./javav2/usecases/creating_lambda_ppe/src/main/java/com/example/ppe/SendEmail.java	fixed
@@ -20 +20 @@
-    public void sendMsg(Set<String> unqiueKeys) {
+    public void sendMsg(Set<String> uniqueKeys) {
@@ -35 +35 @@
-        for (String myKey : unqiueKeys) {
+        for (String myKey : uniqueKeys) {
--- ./javav2/usecases/creating_lambda_ppe/src/main/java/com/example/ppe/PPEHandler.java	original
+++ ./javav2/usecases/creating_lambda_ppe/src/main/java/com/example/ppe/PPEHandler.java	fixed
@@ -47,2 +47,2 @@
-        Set<String> unqiueKeys = createUniqueList(myList);
-        email.sendMsg(unqiueKeys);
+        Set<String> uniqueKeys = createUniqueList(myList);
+        email.sendMsg(uniqueKeys);
--- ./javav2/usecases/creating_lambda_ppe/Readme.md	original
+++ ./javav2/usecases/creating_lambda_ppe/Readme.md	fixed
@@ -559 +559 @@
-The **GearIten** class represents the model in this use case. Its stores data retrieved from the Amazon Rekognition service. 
+The **GearItem** class represents the model in this use case. Its stores data retrieved from the Amazon Rekognition service. 
@@ -665,2 +665,2 @@
-        Set<String> unqiueKeys = createUniqueList(myList);
-        email.sendMsg(unqiueKeys);
+        Set<String> uniqueKeys = createUniqueList(myList);
+        email.sendMsg(uniqueKeys);
@@ -795 +795 @@
-    public void sendMsg(Set<String> unqiueKeys) {
+    public void sendMsg(Set<String> uniqueKeys) {
@@ -810 +810 @@
-        for (String myKey : unqiueKeys) {
+        for (String myKey : uniqueKeys) {
--- ./javav2/usecases/creating_lambda_tag_assets/Readme.md	original
+++ ./javav2/usecases/creating_lambda_tag_assets/Readme.md	fixed
@@ -17 +17 @@
-The Lambda function reads this image in a given S3 bucket and passes it to the Amazon Rekognition service to geneate a series of labels. Each label is used to create a tag that is applied to the image. After you execute the Lambda function, each image has multiple tags, as shown in the following illustration.
+The Lambda function reads this image in a given S3 bucket and passes it to the Amazon Rekognition service to generate a series of labels. Each label is used to create a tag that is applied to the image. After you execute the Lambda function, each image has multiple tags, as shown in the following illustration.
--- ./javav2/usecases/creating_sns_sample_app/Readme.md	original
+++ ./javav2/usecases/creating_sns_sample_app/Readme.md	fixed
@@ -56 +56 @@
-The specified email address recieves an email message that lets the recipient confirm the subscription. 
+The specified email address receives an email message that lets the recipient confirm the subscription. 
@@ -60 +60 @@
-After the email recipient accepts the confirmation, their email address is subscribed to the specific SNS topic and recieves published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
+After the email recipient accepts the confirmation, their email address is subscribed to the specific SNS topic and receives published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
--- ./javav2/usecases/creating_workflows_stepfunctions/Readme.md	original
+++ ./javav2/usecases/creating_workflows_stepfunctions/Readme.md	fixed
@@ -599 +599 @@
-        String sender = "SPECIFY an email address" ; // REPLACE WITH AN EMAIL ADDRESSS
+        String sender = "SPECIFY an email address" ; // REPLACE WITH AN EMAIL ADDRESS
--- ./javav2/usecases/create_amazon_personalize_app/src/main/java/com/amazonaws/personalize/client/resource/AbstractResourceManager.java	original
+++ ./javav2/usecases/create_amazon_personalize_app/src/main/java/com/amazonaws/personalize/client/resource/AbstractResourceManager.java	fixed
@@ -77 +77 @@
-                deleteResouce(name);
+                deleteResource(name);
@@ -86 +86 @@
-    public void deleteResouce(String name) throws IOException, ResourceException {
+    public void deleteResource(String name) throws IOException, ResourceException {
--- ./javav2/usecases/create_amazon_personalize_app/src/main/java/com/amazonaws/personalize/client/resource/ResourceManager.java	original
+++ ./javav2/usecases/create_amazon_personalize_app/src/main/java/com/amazonaws/personalize/client/resource/ResourceManager.java	fixed
@@ -13 +13 @@
-    void deleteResouce(String name) throws IOException, ResourceException;
+    void deleteResource(String name) throws IOException, ResourceException;
--- ./javav2/usecases/create_amazon_personalize_app/static/web/assets/owl.carousel.min.js	original
+++ ./javav2/usecases/create_amazon_personalize_app/static/web/assets/owl.carousel.min.js	fixed
@@ -6,2 +6,2 @@
-!function(a,b,c,d){function e(b,c){this.settings=null,this.options=a.extend({},e.Defaults,c),this.$element=a(b),this._handlers={},this._plugins={},this._supress={},this._current=null,this._speed=null,this._coordinates=[],this._breakpoint=null,this._width=null,this._items=[],this._clones=[],this._mergers=[],this._widths=[],this._invalidated={},this._pipe=[],this._drag={time:null,target:null,pointer:null,stage:{start:null,current:null},direction:null},this._states={current:{},tags:{initializing:["busy"],animating:["busy"],dragging:["interacting"]}},a.each(["onResize","onThrottledResize"],a.proxy(function(b,c){this._handlers[c]=a.proxy(this[c],this)},this)),a.each(e.Plugins,a.proxy(function(a,b){this._plugins[a.charAt(0).toLowerCase()+a.slice(1)]=new b(this)},this)),a.each(e.Workers,a.proxy(function(b,c){this._pipe.push({filter:c.filter,run:a.proxy(c.run,this)})},this)),this.setup(),this.initialize()}e.Defaults={items:3,loop:!1,center:!1,rewind:!1,checkVisibility:!0,mouseDrag:!0,touchDrag:!0,pullDrag:!0,freeDrag:!1,margin:0,stagePadding:0,merge:!1,mergeFit:!0,autoWidth:!1,startPosition:0,rtl:!1,smartSpeed:250,fluidSpeed:!1,dragEndSpeed:!1,responsive:{},responsiveRefreshRate:200,responsiveBaseElement:b,fallbackEasing:"swing",slideTransition:"",info:!1,nestedItemSelector:!1,itemElement:"div",stageElement:"div",refreshClass:"owl-refresh",loadedClass:"owl-loaded",loadingClass:"owl-loading",rtlClass:"owl-rtl",responsiveClass:"owl-responsive",dragClass:"owl-drag",itemClass:"owl-item",stageClass:"owl-stage",stageOuterClass:"owl-stage-outer",grabClass:"owl-grab"},e.Width={Default:"default",Inner:"inner",Outer:"outer"},e.Type={Event:"event",State:"state"},e.Plugins={},e.Workers=[{filter:["width","settings"],run:function(){this._width=this.$element.width()}},{filter:["width","items","settings"],run:function(a){a.current=this._items&&this._items[this.relative(this._current)]}},{filter:["items","settings"],run:function(){this.$stage.children(".cloned").remove()}},{filter:["width","items","settings"],run:function(a){var b=this.settings.margin||"",c=!this.settings.autoWidth,d=this.settings.rtl,e={width:"auto","margin-left":d?b:"","margin-right":d?"":b};!c&&this.$stage.children().css(e),a.css=e}},{filter:["width","items","settings"],run:function(a){var b=(this.width()/this.settings.items).toFixed(3)-this.settings.margin,c=null,d=this._items.length,e=!this.settings.autoWidth,f=[];for(a.items={merge:!1,width:b};d--;)c=this._mergers[d],c=this.settings.mergeFit&&Math.min(c,this.settings.items)||c,a.items.merge=c>1||a.items.merge,f[d]=e?b*c:this._items[d].width();this._widths=f}},{filter:["items","settings"],run:function(){var b=[],c=this._items,d=this.settings,e=Math.max(2*d.items,4),f=2*Math.ceil(c.length/2),g=d.loop&&c.length?d.rewind?e:Math.max(e,f):0,h="",i="";for(g/=2;g>0;)b.push(this.normalize(b.length/2,!0)),h+=c[b[b.length-1]][0].outerHTML,b.push(this.normalize(c.length-1-(b.length-1)/2,!0)),i=c[b[b.length-1]][0].outerHTML+i,g-=1;this._clones=b,a(h).addClass("cloned").appendTo(this.$stage),a(i).addClass("cloned").prependTo(this.$stage)}},{filter:["width","items","settings"],run:function(){for(var a=this.settings.rtl?1:-1,b=this._clones.length+this._items.length,c=-1,d=0,e=0,f=[];++c<b;)d=f[c-1]||0,e=this._widths[this.relative(c)]+this.settings.margin,f.push(d+e*a);this._coordinates=f}},{filter:["width","items","settings"],run:function(){var a=this.settings.stagePadding,b=this._coordinates,c={width:Math.ceil(Math.abs(b[b.length-1]))+2*a,"padding-left":a||"","padding-right":a||""};this.$stage.css(c)}},{filter:["width","items","settings"],run:function(a){var b=this._coordinates.length,c=!this.settings.autoWidth,d=this.$stage.children();if(c&&a.items.merge)for(;b--;)a.css.width=this._widths[this.relative(b)],d.eq(b).css(a.css);else c&&(a.css.width=a.items.width,d.css(a.css))}},{filter:["items"],run:function(){this._coordinates.length<1&&this.$stage.removeAttr("style")}},{filter:["width","items","settings"],run:function(a){a.current=a.current?this.$stage.children().index(a.current):0,a.current=Math.max(this.minimum(),Math.min(this.maximum(),a.current)),this.reset(a.current)}},{filter:["position"],run:function(){this.animate(this.coordinates(this._current))}},{filter:["width","position","items","settings"],run:function(){var a,b,c,d,e=this.settings.rtl?1:-1,f=2*this.settings.stagePadding,g=this.coordinates(this.current())+f,h=g+this.width()*e,i=[];for(c=0,d=this._coordinates.length;c<d;c++)a=this._coordinates[c-1]||0,b=Math.abs(this._coordinates[c])+f*e,(this.op(a,"<=",g)&&this.op(a,">",h)||this.op(b,"<",g)&&this.op(b,">",h))&&i.push(c);this.$stage.children(".active").removeClass("active"),this.$stage.children(":eq("+i.join("), :eq(")+")").addClass("active"),this.$stage.children(".center").removeClass("center"),this.settings.center&&this.$stage.children().eq(this.current()).addClass("center")}}],e.prototype.initializeStage=function(){this.$stage=this.$element.find("."+this.settings.stageClass),this.$stage.length||(this.$element.addClass(this.options.loadingClass),this.$stage=a("<"+this.settings.stageElement+">",{class:this.settings.stageClass}).wrap(a("<div/>",{class:this.settings.stageOuterClass})),this.$element.append(this.$stage.parent()))},e.prototype.initializeItems=function(){var b=this.$element.find(".owl-item");if(b.length)return this._items=b.get().map(function(b){return a(b)}),this._mergers=this._items.map(function(){return 1}),void this.refresh();this.replace(this.$element.children().not(this.$stage.parent())),this.isVisible()?this.refresh():this.invalidate("width"),this.$element.removeClass(this.options.loadingClass).addClass(this.options.loadedClass)},e.prototype.initialize=function(){if(this.enter("initializing"),this.trigger("initialize"),this.$element.toggleClass(this.settings.rtlClass,this.settings.rtl),this.settings.autoWidth&&!this.is("pre-loading")){var a,b,c;a=this.$element.find("img"),b=this.settings.nestedItemSelector?"."+this.settings.nestedItemSelector:d,c=this.$element.children(b).width(),a.length&&c<=0&&this.preloadAutoWidthImages(a)}this.initializeStage(),this.initializeItems(),this.registerEventHandlers(),this.leave("initializing"),this.trigger("initialized")},e.prototype.isVisible=function(){return!this.settings.checkVisibility||this.$element.is(":visible")},e.prototype.setup=function(){var b=this.viewport(),c=this.options.responsive,d=-1,e=null;c?(a.each(c,function(a){a<=b&&a>d&&(d=Number(a))}),e=a.extend({},this.options,c[d]),"function"==typeof e.stagePadding&&(e.stagePadding=e.stagePadding()),delete e.responsive,e.responsiveClass&&this.$element.attr("class",this.$element.attr("class").replace(new RegExp("("+this.options.responsiveClass+"-)\\S+\\s","g"),"$1"+d))):e=a.extend({},this.options),this.trigger("change",{property:{name:"settings",value:e}}),this._breakpoint=d,this.settings=e,this.invalidate("settings"),this.trigger("changed",{property:{name:"settings",value:this.settings}})},e.prototype.optionsLogic=function(){this.settings.autoWidth&&(this.settings.stagePadding=!1,this.settings.merge=!1)},e.prototype.prepare=function(b){var c=this.trigger("prepare",{content:b});return c.data||(c.data=a("<"+this.settings.itemElement+"/>").addClass(this.options.itemClass).append(b)),this.trigger("prepared",{content:c.data}),c.data},e.prototype.update=function(){for(var b=0,c=this._pipe.length,d=a.proxy(function(a){return this[a]},this._invalidated),e={};b<c;)(this._invalidated.all||a.grep(this._pipe[b].filter,d).length>0)&&this._pipe[b].run(e),b++;this._invalidated={},!this.is("valid")&&this.enter("valid")},e.prototype.width=function(a){switch(a=a||e.Width.Default){case e.Width.Inner:case e.Width.Outer:return this._width;default:return this._width-2*this.settings.stagePadding+this.settings.margin}},e.prototype.refresh=function(){this.enter("refreshing"),this.trigger("refresh"),this.setup(),this.optionsLogic(),this.$element.addClass(this.options.refreshClass),this.update(),this.$element.removeClass(this.options.refreshClass),this.leave("refreshing"),this.trigger("refreshed")},e.prototype.onThrottledResize=function(){b.clearTimeout(this.resizeTimer),this.resizeTimer=b.setTimeout(this._handlers.onResize,this.settings.responsiveRefreshRate)},e.prototype.onResize=function(){return!!this._items.length&&(this._width!==this.$element.width()&&(!!this.isVisible()&&(this.enter("resizing"),this.trigger("resize").isDefaultPrevented()?(this.leave("resizing"),!1):(this.invalidate("width"),this.refresh(),this.leave("resizing"),void this.trigger("resized")))))},e.prototype.registerEventHandlers=function(){a.support.transition&&this.$stage.on(a.support.transition.end+".owl.core",a.proxy(this.onTransitionEnd,this)),!1!==this.settings.responsive&&this.on(b,"resize",this._handlers.onThrottledResize),this.settings.mouseDrag&&(this.$element.addClass(this.options.dragClass),this.$stage.on("mousedown.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("dragstart.owl.core selectstart.owl.core",function(){return!1})),this.settings.touchDrag&&(this.$stage.on("touchstart.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("touchcancel.owl.core",a.proxy(this.onDragEnd,this)))},e.prototype.onDragStart=function(b){var d=null;3!==b.which&&(a.support.transform?(d=this.$stage.css("transform").replace(/.*\(|\)| /g,"").split(","),d={x:d[16===d.length?12:4],y:d[16===d.length?13:5]}):(d=this.$stage.position(),d={x:this.settings.rtl?d.left+this.$stage.width()-this.width()+this.settings.margin:d.left,y:d.top}),this.is("animating")&&(a.support.transform?this.animate(d.x):this.$stage.stop(),this.invalidate("position")),this.$element.toggleClass(this.options.grabClass,"mousedown"===b.type),this.speed(0),this._drag.time=(new Date).getTime(),this._drag.target=a(b.target),this._drag.stage.start=d,this._drag.stage.current=d,this._drag.pointer=this.pointer(b),a(c).on("mouseup.owl.core touchend.owl.core",a.proxy(this.onDragEnd,this)),a(c).one("mousemove.owl.core touchmove.owl.core",a.proxy(function(b){var d=this.difference(this._drag.pointer,this.pointer(b));a(c).on("mousemove.owl.core touchmove.owl.core",a.proxy(this.onDragMove,this)),Math.abs(d.x)<Math.abs(d.y)&&this.is("valid")||(b.preventDefault(),this.enter("dragging"),this.trigger("drag"))},this)))},e.prototype.onDragMove=function(a){var b=null,c=null,d=null,e=this.difference(this._drag.pointer,this.pointer(a)),f=this.difference(this._drag.stage.start,e);this.is("dragging")&&(a.preventDefault(),this.settings.loop?(b=this.coordinates(this.minimum()),c=this.coordinates(this.maximum()+1)-b,f.x=((f.x-b)%c+c)%c+b):(b=this.settings.rtl?this.coordinates(this.maximum()):this.coordinates(this.minimum()),c=this.settings.rtl?this.coordinates(this.minimum()):this.coordinates(this.maximum()),d=this.settings.pullDrag?-1*e.x/5:0,f.x=Math.max(Math.min(f.x,b+d),c+d)),this._drag.stage.current=f,this.animate(f.x))},e.prototype.onDragEnd=function(b){var d=this.difference(this._drag.pointer,this.pointer(b)),e=this._drag.stage.current,f=d.x>0^this.settings.rtl?"left":"right";a(c).off(".owl.core"),this.$element.removeClass(this.options.grabClass),(0!==d.x&&this.is("dragging")||!this.is("valid"))&&(this.speed(this.settings.dragEndSpeed||this.settings.smartSpeed),this.current(this.closest(e.x,0!==d.x?f:this._drag.direction)),this.invalidate("position"),this.update(),this._drag.direction=f,(Math.abs(d.x)>3||(new Date).getTime()-this._drag.time>300)&&this._drag.target.one("click.owl.core",function(){return!1})),this.is("dragging")&&(this.leave("dragging"),this.trigger("dragged"))},e.prototype.closest=function(b,c){var e=-1,f=30,g=this.width(),h=this.coordinates();return this.settings.freeDrag||a.each(h,a.proxy(function(a,i){return"left"===c&&b>i-f&&b<i+f?e=a:"right"===c&&b>i-g-f&&b<i-g+f?e=a+1:this.op(b,"<",i)&&this.op(b,">",h[a+1]!==d?h[a+1]:i-g)&&(e="left"===c?a+1:a),-1===e},this)),this.settings.loop||(this.op(b,">",h[this.minimum()])?e=b=this.minimum():this.op(b,"<",h[this.maximum()])&&(e=b=this.maximum())),e},e.prototype.animate=function(b){var c=this.speed()>0;this.is("animating")&&this.onTransitionEnd(),c&&(this.enter("animating"),this.trigger("translate")),a.support.transform3d&&a.support.transition?this.$stage.css({transform:"translate3d("+b+"px,0px,0px)",transition:this.speed()/1e3+"s"+(this.settings.slideTransition?" "+this.settings.slideTransition:"")}):c?this.$stage.animate({left:b+"px"},this.speed(),this.settings.fallbackEasing,a.proxy(this.onTransitionEnd,this)):this.$stage.css({left:b+"px"})},e.prototype.is=function(a){return this._states.current[a]&&this._states.current[a]>0},e.prototype.current=function(a){if(a===d)return this._current;if(0===this._items.length)return d;if(a=this.normalize(a),this._current!==a){var b=this.trigger("change",{property:{name:"position",value:a}});b.data!==d&&(a=this.normalize(b.data)),this._current=a,this.invalidate("position"),this.trigger("changed",{property:{name:"position",value:this._current}})}return this._current},e.prototype.invalidate=function(b){return"string"===a.type(b)&&(this._invalidated[b]=!0,this.is("valid")&&this.leave("valid")),a.map(this._invalidated,function(a,b){return b})},e.prototype.reset=function(a){(a=this.normalize(a))!==d&&(this._speed=0,this._current=a,this.suppress(["translate","translated"]),this.animate(this.coordinates(a)),this.release(["translate","translated"]))},e.prototype.normalize=function(a,b){var c=this._items.length,e=b?0:this._clones.length;return!this.isNumeric(a)||c<1?a=d:(a<0||a>=c+e)&&(a=((a-e/2)%c+c)%c+e/2),a},e.prototype.relative=function(a){return a-=this._clones.length/2,this.normalize(a,!0)},e.prototype.maximum=function(a){var b,c,d,e=this.settings,f=this._coordinates.length;if(e.loop)f=this._clones.length/2+this._items.length-1;else if(e.autoWidth||e.merge){if(b=this._items.length)for(c=this._items[--b].width(),d=this.$element.width();b--&&!((c+=this._items[b].width()+this.settings.margin)>d););f=b+1}else f=e.center?this._items.length-1:this._items.length-e.items;return a&&(f-=this._clones.length/2),Math.max(f,0)},e.prototype.minimum=function(a){return a?0:this._clones.length/2},e.prototype.items=function(a){return a===d?this._items.slice():(a=this.normalize(a,!0),this._items[a])},e.prototype.mergers=function(a){return a===d?this._mergers.slice():(a=this.normalize(a,!0),this._mergers[a])},e.prototype.clones=function(b){var c=this._clones.length/2,e=c+this._items.length,f=function(a){return a%2==0?e+a/2:c-(a+1)/2};return b===d?a.map(this._clones,function(a,b){return f(b)}):a.map(this._clones,function(a,c){return a===b?f(c):null})},e.prototype.speed=function(a){return a!==d&&(this._speed=a),this._speed},e.prototype.coordinates=function(b){var c,e=1,f=b-1;return b===d?a.map(this._coordinates,a.proxy(function(a,b){return this.coordinates(b)},this)):(this.settings.center?(this.settings.rtl&&(e=-1,f=b+1),c=this._coordinates[b],c+=(this.width()-c+(this._coordinates[f]||0))/2*e):c=this._coordinates[f]||0,c=Math.ceil(c))},e.prototype.duration=function(a,b,c){return 0===c?0:Math.min(Math.max(Math.abs(b-a),1),6)*Math.abs(c||this.settings.smartSpeed)},e.prototype.to=function(a,b){var c=this.current(),d=null,e=a-this.relative(c),f=(e>0)-(e<0),g=this._items.length,h=this.minimum(),i=this.maximum();this.settings.loop?(!this.settings.rewind&&Math.abs(e)>g/2&&(e+=-1*f*g),a=c+e,(d=((a-h)%g+g)%g+h)!==a&&d-e<=i&&d-e>0&&(c=d-e,a=d,this.reset(c))):this.settings.rewind?(i+=1,a=(a%i+i)%i):a=Math.max(h,Math.min(i,a)),this.speed(this.duration(c,a,b)),this.current(a),this.isVisible()&&this.update()},e.prototype.next=function(a){a=a||!1,this.to(this.relative(this.current())+1,a)},e.prototype.prev=function(a){a=a||!1,this.to(this.relative(this.current())-1,a)},e.prototype.onTransitionEnd=function(a){if(a!==d&&(a.stopPropagation(),(a.target||a.srcElement||a.originalTarget)!==this.$stage.get(0)))return!1;this.leave("animating"),this.trigger("translated")},e.prototype.viewport=function(){var d;return this.options.responsiveBaseElement!==b?d=a(this.options.responsiveBaseElement).width():b.innerWidth?d=b.innerWidth:c.documentElement&&c.documentElement.clientWidth?d=c.documentElement.clientWidth:console.warn("Can not detect viewport width."),d},e.prototype.replace=function(b){this.$stage.empty(),this._items=[],b&&(b=b instanceof jQuery?b:a(b)),this.settings.nestedItemSelector&&(b=b.find("."+this.settings.nestedItemSelector)),b.filter(function(){return 1===this.nodeType}).each(a.proxy(function(a,b){b=this.prepare(b),this.$stage.append(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)},this)),this.reset(this.isNumeric(this.settings.startPosition)?this.settings.startPosition:0),this.invalidate("items")},e.prototype.add=function(b,c){var e=this.relative(this._current);c=c===d?this._items.length:this.normalize(c,!0),b=b instanceof jQuery?b:a(b),this.trigger("add",{content:b,position:c}),b=this.prepare(b),0===this._items.length||c===this._items.length?(0===this._items.length&&this.$stage.append(b),0!==this._items.length&&this._items[c-1].after(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)):(this._items[c].before(b),this._items.splice(c,0,b),this._mergers.splice(c,0,1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)),this._items[e]&&this.reset(this._items[e].index()),this.invalidate("items"),this.trigger("added",{content:b,position:c})},e.prototype.remove=function(a){(a=this.normalize(a,!0))!==d&&(this.trigger("remove",{content:this._items[a],position:a}),this._items[a].remove(),this._items.splice(a,1),this._mergers.splice(a,1),this.invalidate("items"),this.trigger("removed",{content:null,position:a}))},e.prototype.preloadAutoWidthImages=function(b){b.each(a.proxy(function(b,c){this.enter("pre-loading"),c=a(c),a(new Image).one("load",a.proxy(function(a){c.attr("src",a.target.src),c.css("opacity",1),this.leave("pre-loading"),!this.is("pre-loading")&&!this.is("initializing")&&this.refresh()},this)).attr("src",c.attr("src")||c.attr("data-src")||c.attr("data-src-retina"))},this))},e.prototype.destroy=function(){this.$element.off(".owl.core"),this.$stage.off(".owl.core"),a(c).off(".owl.core"),!1!==this.settings.responsive&&(b.clearTimeout(this.resizeTimer),this.off(b,"resize",this._handlers.onThrottledResize));for(var d in this._plugins)this._plugins[d].destroy();this.$stage.children(".cloned").remove(),this.$stage.unwrap(),this.$stage.children().contents().unwrap(),this.$stage.children().unwrap(),this.$stage.remove(),this.$element.removeClass(this.options.refreshClass).removeClass(this.options.loadingClass).removeClass(this.options.loadedClass).removeClass(this.options.rtlClass).removeClass(this.options.dragClass).removeClass(this.options.grabClass).attr("class",this.$element.attr("class").replace(new RegExp(this.options.responsiveClass+"-\\S+\\s","g"),"")).removeData("owl.carousel")},e.prototype.op=function(a,b,c){var d=this.settings.rtl;switch(b){case"<":return d?a>c:a<c;case">":return d?a<c:a>c;case">=":return d?a<=c:a>=c;case"<=":return d?a>=c:a<=c}},e.prototype.on=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,d):a.attachEvent&&a.attachEvent("on"+b,c)},e.prototype.off=function(a,b,c,d){a.removeEventListener?a.removeEventListener(b,c,d):a.detachEvent&&a.detachEvent("on"+b,c)},e.prototype.trigger=function(b,c,d,f,g){var h={item:{count:this._items.length,index:this.current()}},i=a.camelCase(a.grep(["on",b,d],function(a){return a}).join("-").toLowerCase()),j=a.Event([b,"owl",d||"carousel"].join(".").toLowerCase(),a.extend({relatedTarget:this},h,c));return this._supress[b]||(a.each(this._plugins,function(a,b){b.onTrigger&&b.onTrigger(j)}),this.register({type:e.Type.Event,name:b}),this.$element.trigger(j),this.settings&&"function"==typeof this.settings[i]&&this.settings[i].call(this,j)),j},e.prototype.enter=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]===d&&(this._states.current[b]=0),this._states.current[b]++},this))},e.prototype.leave=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]--},this))},e.prototype.register=function(b){if(b.type===e.Type.Event){if(a.event.special[b.name]||(a.event.special[b.name]={}),!a.event.special[b.name].owl){var c=a.event.special[b.name]._default;a.event.special[b.name]._default=function(a){return!c||!c.apply||a.namespace&&-1!==a.namespace.indexOf("owl")?a.namespace&&a.namespace.indexOf("owl")>-1:c.apply(this,arguments)},a.event.special[b.name].owl=!0}}else b.type===e.Type.State&&(this._states.tags[b.name]?this._states.tags[b.name]=this._states.tags[b.name].concat(b.tags):this._states.tags[b.name]=b.tags,this._states.tags[b.name]=a.grep(this._states.tags[b.name],a.proxy(function(c,d){return a.inArray(c,this._states.tags[b.name])===d},this)))},e.prototype.suppress=function(b){a.each(b,a.proxy(function(a,b){this._supress[b]=!0},this))},e.prototype.release=function(b){a.each(b,a.proxy(function(a,b){delete this._supress[b]},this))},e.prototype.pointer=function(a){var c={x:null,y:null};return a=a.originalEvent||a||b.event,a=a.touches&&a.touches.length?a.touches[0]:a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:a,a.pageX?(c.x=a.pageX,c.y=a.pageY):(c.x=a.clientX,c.y=a.clientY),c},e.prototype.isNumeric=function(a){return!isNaN(parseFloat(a))},e.prototype.difference=function(a,b){return{x:a.x-b.x,y:a.y-b.y}},a.fn.owlCarousel=function(b){var c=Array.prototype.slice.call(arguments,1);return this.each(function(){var d=a(this),f=d.data("owl.carousel");f||(f=new e(this,"object"==typeof b&&b),d.data("owl.carousel",f),a.each(["next","prev","to","destroy","refresh","replace","add","remove"],function(b,c){f.register({type:e.Type.Event,name:c}),f.$element.on(c+".owl.carousel.core",a.proxy(function(a){a.namespace&&a.relatedTarget!==this&&(this.suppress([c]),f[c].apply(this,[].slice.call(arguments,1)),this.release([c]))},f))})),"string"==typeof b&&"_"!==b.charAt(0)&&f[b].apply(f,c)})},a.fn.owlCarousel.Constructor=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._interval=null,this._visible=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoRefresh&&this.watch()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={autoRefresh:!0,autoRefreshInterval:500},e.prototype.watch=function(){this._interval||(this._visible=this._core.isVisible(),this._interval=b.setInterval(a.proxy(this.refresh,this),this._core.settings.autoRefreshInterval))},e.prototype.refresh=function(){this._core.isVisible()!==this._visible&&(this._visible=!this._visible,this._core.$element.toggleClass("owl-hidden",!this._visible),this._visible&&this._core.invalidate("width")&&this._core.refresh())},e.prototype.destroy=function(){var a,c;b.clearInterval(this._interval);for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoRefresh=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._loaded=[],this._handlers={"initialized.owl.carousel change.owl.carousel resized.owl.carousel":a.proxy(function(b){if(b.namespace&&this._core.settings&&this._core.settings.lazyLoad&&(b.property&&"position"==b.property.name||"initialized"==b.type)){var c=this._core.settings,e=c.center&&Math.ceil(c.items/2)||c.items,f=c.center&&-1*e||0,g=(b.property&&b.property.value!==d?b.property.value:this._core.current())+f,h=this._core.clones().length,i=a.proxy(function(a,b){this.load(b)},this);for(c.lazyLoadEager>0&&(e+=c.lazyLoadEager,c.loop&&(g-=c.lazyLoadEager,e++));f++<e;)this.load(h/2+this._core.relative(g)),h&&a.each(this._core.clones(this._core.relative(g)),i),g++}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={lazyLoad:!1,lazyLoadEager:0},e.prototype.load=function(c){var d=this._core.$stage.children().eq(c),e=d&&d.find(".owl-lazy");!e||a.inArray(d.get(0),this._loaded)>-1||(e.each(a.proxy(function(c,d){var e,f=a(d),g=b.devicePixelRatio>1&&f.attr("data-src-retina")||f.attr("data-src")||f.attr("data-srcset");this._core.trigger("load",{element:f,url:g},"lazy"),f.is("img")?f.one("load.owl.lazy",a.proxy(function(){f.css("opacity",1),this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("src",g):f.is("source")?f.one("load.owl.lazy",a.proxy(function(){this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("srcset",g):(e=new Image,e.onload=a.proxy(function(){f.css({"background-image":'url("'+g+'")',opacity:"1"}),this._core.trigger("loaded",{element:f,url:g},"lazy")},this),e.src=g)},this)),this._loaded.push(d.get(0)))},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this._core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Lazy=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(c){this._core=c,this._previousHeight=null,this._handlers={"initialized.owl.carousel refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&this.update()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&"position"===a.property.name&&this.update()},this),"loaded.owl.lazy":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&a.element.closest("."+this._core.settings.itemClass).index()===this._core.current()&&this.update()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers),this._intervalId=null;var d=this;a(b).on("load",function(){d._core.settings.autoHeight&&d.update()}),a(b).resize(function(){d._core.settings.autoHeight&&(null!=d._intervalId&&clearTimeout(d._intervalId),d._intervalId=setTimeout(function(){d.update()},250))})};e.Defaults={autoHeight:!1,autoHeightClass:"owl-height"},e.prototype.update=function(){var b=this._core._current,c=b+this._core.settings.items,d=this._core.settings.lazyLoad,e=this._core.$stage.children().toArray().slice(b,c),f=[],g=0;a.each(e,function(b,c){f.push(a(c).height())}),g=Math.max.apply(null,f),g<=1&&d&&this._previousHeight&&(g=this._previousHeight),this._previousHeight=g,this._core.$stage.parent().height(g).addClass(this._core.settings.autoHeightClass)},e.prototype.destroy=function(){var a,b;for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoHeight=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._videos={},this._playing=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.register({type:"state",name:"playing",tags:["interacting"]})},this),"resize.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.video&&this.isInFullScreen()&&a.preventDefault()},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.is("resizing")&&this._core.$stage.find(".cloned .owl-video-frame").remove()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"===a.property.name&&this._playing&&this.stop()},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find(".owl-video");c.length&&(c.css("display","none"),this.fetch(c,a(b.content)))}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers),this._core.$element.on("click.owl.video",".owl-video-play-icon",a.proxy(function(a){this.play(a)},this))};e.Defaults={video:!1,videoHeight:!1,videoWidth:!1},e.prototype.fetch=function(a,b){var c=function(){return a.attr("data-vimeo-id")?"vimeo":a.attr("data-vzaar-id")?"vzaar":"youtube"}(),d=a.attr("data-vimeo-id")||a.attr("data-youtube-id")||a.attr("data-vzaar-id"),e=a.attr("data-width")||this._core.settings.videoWidth,f=a.attr("data-height")||this._core.settings.videoHeight,g=a.attr("href");if(!g)throw new Error("Missing video URL.");if(d=g.match(/(http:|https:|)\/\/(player.|www.|app.)?(vimeo\.com|youtu(be\.com|\.be|be\.googleapis\.com|be\-nocookie\.com)|vzaar\.com)\/(video\/|videos\/|embed\/|channels\/.+\/|groups\/.+\/|watch\?v=|v\/)?([A-Za-z0-9._%-]*)(\&\S+)?/),d[3].indexOf("youtu")>-1)c="youtube";else if(d[3].indexOf("vimeo")>-1)c="vimeo";else{if(!(d[3].indexOf("vzaar")>-1))throw new Error("Video URL not supported.");c="vzaar"}d=d[6],this._videos[g]={type:c,id:d,width:e,height:f},b.attr("data-video",g),this.thumbnail(a,this._videos[g])},e.prototype.thumbnail=function(b,c){var d,e,f,g=c.width&&c.height?"width:"+c.width+"px;height:"+c.height+"px;":"",h=b.find("img"),i="src",j="",k=this._core.settings,l=function(c){e='<div class="owl-video-play-icon"></div>',d=k.lazyLoad?a("<div/>",{class:"owl-video-tn "+j,srcType:c}):a("<div/>",{class:"owl-video-tn",style:"opacity:1;background-image:url("+c+")"}),b.after(d),b.after(e)};if(b.wrap(a("<div/>",{class:"owl-video-wrapper",style:g})),this._core.settings.lazyLoad&&(i="data-src",j="owl-lazy"),h.length)return l(h.attr(i)),h.remove(),!1;"youtube"===c.type?(f="//img.youtube.com/vi/"+c.id+"/hqdefault.jpg",l(f)):"vimeo"===c.type?a.ajax({type:"GET",url:"//vimeo.com/api/v2/video/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a[0].thumbnail_large,l(f)}}):"vzaar"===c.type&&a.ajax({type:"GET",url:"//vzaar.com/api/videos/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a.framegrab_url,l(f)}})},e.prototype.stop=function(){this._core.trigger("stop",null,"video"),this._playing.find(".owl-video-frame").remove(),this._playing.removeClass("owl-video-playing"),this._playing=null,this._core.leave("playing"),this._core.trigger("stopped",null,"video")},e.prototype.play=function(b){var c,d=a(b.target),e=d.closest("."+this._core.settings.itemClass),f=this._videos[e.attr("data-video")],g=f.width||"100%",h=f.height||this._core.$stage.height();this._playing||(this._core.enter("playing"),this._core.trigger("play",null,"video"),e=this._core.items(this._core.relative(e.index())),this._core.reset(e.index()),c=a('<iframe frameborder="0" allowfullscreen mozallowfullscreen webkitAllowFullScreen ></iframe>'),c.attr("height",h),c.attr("width",g),"youtube"===f.type?c.attr("src","//www.youtube.com/embed/"+f.id+"?autoplay=1&rel=0&v="+f.id):"vimeo"===f.type?c.attr("src","//player.vimeo.com/video/"+f.id+"?autoplay=1"):"vzaar"===f.type&&c.attr("src","//view.vzaar.com/"+f.id+"/player?autoplay=true"),a(c).wrap('<div class="owl-video-frame" />').insertAfter(e.find(".owl-video")),this._playing=e.addClass("owl-video-playing"))},e.prototype.isInFullScreen=function(){var b=c.fullscreenElement||c.mozFullScreenElement||c.webkitFullscreenElement;return b&&a(b).parent().hasClass("owl-video-frame")},e.prototype.destroy=function(){var a,b;this._core.$element.off("click.owl.video");for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Video=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this.core=b,this.core.options=a.extend({},e.Defaults,this.core.options),this.swapping=!0,this.previous=d,this.next=d,this.handlers={"change.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&(this.previous=this.core.current(),this.next=a.property.value)},this),"drag.owl.carousel dragged.owl.carousel translated.owl.carousel":a.proxy(function(a){a.namespace&&(this.swapping="translated"==a.type)},this),"translate.owl.carousel":a.proxy(function(a){a.namespace&&this.swapping&&(this.core.options.animateOut||this.core.options.animateIn)&&this.swap()},this)},this.core.$element.on(this.handlers)};e.Defaults={animateOut:!1,
-animateIn:!1},e.prototype.swap=function(){if(1===this.core.settings.items&&a.support.animation&&a.support.transition){this.core.speed(0);var b,c=a.proxy(this.clear,this),d=this.core.$stage.children().eq(this.previous),e=this.core.$stage.children().eq(this.next),f=this.core.settings.animateIn,g=this.core.settings.animateOut;this.core.current()!==this.previous&&(g&&(b=this.core.coordinates(this.previous)-this.core.coordinates(this.next),d.one(a.support.animation.end,c).css({left:b+"px"}).addClass("animated owl-animated-out").addClass(g)),f&&e.one(a.support.animation.end,c).addClass("animated owl-animated-in").addClass(f))}},e.prototype.clear=function(b){a(b.target).css({left:""}).removeClass("animated owl-animated-out owl-animated-in").removeClass(this.core.settings.animateIn).removeClass(this.core.settings.animateOut),this.core.onTransitionEnd()},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Animate=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._call=null,this._time=0,this._timeout=0,this._paused=!0,this._handlers={"changed.owl.carousel":a.proxy(function(a){a.namespace&&"settings"===a.property.name?this._core.settings.autoplay?this.play():this.stop():a.namespace&&"position"===a.property.name&&this._paused&&(this._time=0)},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoplay&&this.play()},this),"play.owl.autoplay":a.proxy(function(a,b,c){a.namespace&&this.play(b,c)},this),"stop.owl.autoplay":a.proxy(function(a){a.namespace&&this.stop()},this),"mouseover.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"mouseleave.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.play()},this),"touchstart.owl.core":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"touchend.owl.core":a.proxy(function(){this._core.settings.autoplayHoverPause&&this.play()},this)},this._core.$element.on(this._handlers),this._core.options=a.extend({},e.Defaults,this._core.options)};e.Defaults={autoplay:!1,autoplayTimeout:5e3,autoplayHoverPause:!1,autoplaySpeed:!1},e.prototype._next=function(d){this._call=b.setTimeout(a.proxy(this._next,this,d),this._timeout*(Math.round(this.read()/this._timeout)+1)-this.read()),this._core.is("interacting")||c.hidden||this._core.next(d||this._core.settings.autoplaySpeed)},e.prototype.read=function(){return(new Date).getTime()-this._time},e.prototype.play=function(c,d){var e;this._core.is("rotating")||this._core.enter("rotating"),c=c||this._core.settings.autoplayTimeout,e=Math.min(this._time%(this._timeout||c),c),this._paused?(this._time=this.read(),this._paused=!1):b.clearTimeout(this._call),this._time+=this.read()%c-e,this._timeout=c,this._call=b.setTimeout(a.proxy(this._next,this,d),c-e)},e.prototype.stop=function(){this._core.is("rotating")&&(this._time=0,this._paused=!0,b.clearTimeout(this._call),this._core.leave("rotating"))},e.prototype.pause=function(){this._core.is("rotating")&&!this._paused&&(this._time=this.read(),this._paused=!0,b.clearTimeout(this._call))},e.prototype.destroy=function(){var a,b;this.stop();for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.autoplay=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(b){this._core=b,this._initialized=!1,this._pages=[],this._controls={},this._templates=[],this.$element=this._core.$element,this._overrides={next:this._core.next,prev:this._core.prev,to:this._core.to},this._handlers={"prepared.owl.carousel":a.proxy(function(b){b.namespace&&this._core.settings.dotsData&&this._templates.push('<div class="'+this._core.settings.dotClass+'">'+a(b.content).find("[data-dot]").addBack("[data-dot]").attr("data-dot")+"</div>")},this),"added.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,0,this._templates.pop())},this),"remove.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,1)},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&this.draw()},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&!this._initialized&&(this._core.trigger("initialize",null,"navigation"),this.initialize(),this.update(),this.draw(),this._initialized=!0,this._core.trigger("initialized",null,"navigation"))},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._initialized&&(this._core.trigger("refresh",null,"navigation"),this.update(),this.draw(),this._core.trigger("refreshed",null,"navigation"))},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers)};e.Defaults={nav:!1,navText:['<span aria-label="Previous">&#x2039;</span>','<span aria-label="Next">&#x203a;</span>'],navSpeed:!1,navElement:'button type="button" role="presentation"',navContainer:!1,navContainerClass:"owl-nav",navClass:["owl-prev","owl-next"],slideBy:1,dotClass:"owl-dot",dotsClass:"owl-dots",dots:!0,dotsEach:!1,dotsData:!1,dotsSpeed:!1,dotsContainer:!1},e.prototype.initialize=function(){var b,c=this._core.settings;this._controls.$relative=(c.navContainer?a(c.navContainer):a("<div>").addClass(c.navContainerClass).appendTo(this.$element)).addClass("disabled"),this._controls.$previous=a("<"+c.navElement+">").addClass(c.navClass[0]).html(c.navText[0]).prependTo(this._controls.$relative).on("click",a.proxy(function(a){this.prev(c.navSpeed)},this)),this._controls.$next=a("<"+c.navElement+">").addClass(c.navClass[1]).html(c.navText[1]).appendTo(this._controls.$relative).on("click",a.proxy(function(a){this.next(c.navSpeed)},this)),c.dotsData||(this._templates=[a('<button role="button">').addClass(c.dotClass).append(a("<span>")).prop("outerHTML")]),this._controls.$absolute=(c.dotsContainer?a(c.dotsContainer):a("<div>").addClass(c.dotsClass).appendTo(this.$element)).addClass("disabled"),this._controls.$absolute.on("click","button",a.proxy(function(b){var d=a(b.target).parent().is(this._controls.$absolute)?a(b.target).index():a(b.target).parent().index();b.preventDefault(),this.to(d,c.dotsSpeed)},this));for(b in this._overrides)this._core[b]=a.proxy(this[b],this)},e.prototype.destroy=function(){var a,b,c,d,e;e=this._core.settings;for(a in this._handlers)this.$element.off(a,this._handlers[a]);for(b in this._controls)"$relative"===b&&e.navContainer?this._controls[b].html(""):this._controls[b].remove();for(d in this.overides)this._core[d]=this._overrides[d];for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},e.prototype.update=function(){var a,b,c,d=this._core.clones().length/2,e=d+this._core.items().length,f=this._core.maximum(!0),g=this._core.settings,h=g.center||g.autoWidth||g.dotsData?1:g.dotsEach||g.items;if("page"!==g.slideBy&&(g.slideBy=Math.min(g.slideBy,g.items)),g.dots||"page"==g.slideBy)for(this._pages=[],a=d,b=0,c=0;a<e;a++){if(b>=h||0===b){if(this._pages.push({start:Math.min(f,a-d),end:a-d+h-1}),Math.min(f,a-d)===f)break;b=0,++c}b+=this._core.mergers(this._core.relative(a))}},e.prototype.draw=function(){var b,c=this._core.settings,d=this._core.items().length<=c.items,e=this._core.relative(this._core.current()),f=c.loop||c.rewind;this._controls.$relative.toggleClass("disabled",!c.nav||d),c.nav&&(this._controls.$previous.toggleClass("disabled",!f&&e<=this._core.minimum(!0)),this._controls.$next.toggleClass("disabled",!f&&e>=this._core.maximum(!0))),this._controls.$absolute.toggleClass("disabled",!c.dots||d),c.dots&&(b=this._pages.length-this._controls.$absolute.children().length,c.dotsData&&0!==b?this._controls.$absolute.html(this._templates.join("")):b>0?this._controls.$absolute.append(new Array(b+1).join(this._templates[0])):b<0&&this._controls.$absolute.children().slice(b).remove(),this._controls.$absolute.find(".active").removeClass("active"),this._controls.$absolute.children().eq(a.inArray(this.current(),this._pages)).addClass("active"))},e.prototype.onTrigger=function(b){var c=this._core.settings;b.page={index:a.inArray(this.current(),this._pages),count:this._pages.length,size:c&&(c.center||c.autoWidth||c.dotsData?1:c.dotsEach||c.items)}},e.prototype.current=function(){var b=this._core.relative(this._core.current());return a.grep(this._pages,a.proxy(function(a,c){return a.start<=b&&a.end>=b},this)).pop()},e.prototype.getPosition=function(b){var c,d,e=this._core.settings;return"page"==e.slideBy?(c=a.inArray(this.current(),this._pages),d=this._pages.length,b?++c:--c,c=this._pages[(c%d+d)%d].start):(c=this._core.relative(this._core.current()),d=this._core.items().length,b?c+=e.slideBy:c-=e.slideBy),c},e.prototype.next=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!0),b)},e.prototype.prev=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!1),b)},e.prototype.to=function(b,c,d){var e;!d&&this._pages.length?(e=this._pages.length,a.proxy(this._overrides.to,this._core)(this._pages[(b%e+e)%e].start,c)):a.proxy(this._overrides.to,this._core)(b,c)},a.fn.owlCarousel.Constructor.Plugins.Navigation=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(c){this._core=c,this._hashes={},this.$element=this._core.$element,this._handlers={"initialized.owl.carousel":a.proxy(function(c){c.namespace&&"URLHash"===this._core.settings.startPosition&&a(b).trigger("hashchange.owl.navigation")},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find("[data-hash]").addBack("[data-hash]").attr("data-hash");if(!c)return;this._hashes[c]=b.content}},this),"changed.owl.carousel":a.proxy(function(c){if(c.namespace&&"position"===c.property.name){var d=this._core.items(this._core.relative(this._core.current())),e=a.map(this._hashes,function(a,b){return a===d?b:null}).join();if(!e||b.location.hash.slice(1)===e)return;b.location.hash=e}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers),a(b).on("hashchange.owl.navigation",a.proxy(function(a){var c=b.location.hash.substring(1),e=this._core.$stage.children(),f=this._hashes[c]&&e.index(this._hashes[c]);f!==d&&f!==this._core.current()&&this._core.to(this._core.relative(f),!1,!0)},this))};e.Defaults={URLhashListener:!1},e.prototype.destroy=function(){var c,d;a(b).off("hashchange.owl.navigation");for(c in this._handlers)this._core.$element.off(c,this._handlers[c]);for(d in Object.getOwnPropertyNames(this))"function"!=typeof this[d]&&(this[d]=null)},a.fn.owlCarousel.Constructor.Plugins.Hash=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){function e(b,c){var e=!1,f=b.charAt(0).toUpperCase()+b.slice(1);return a.each((b+" "+h.join(f+" ")+f).split(" "),function(a,b){if(g[b]!==d)return e=!c||b,!1}),e}function f(a){return e(a,!0)}var g=a("<support>").get(0).style,h="Webkit Moz O ms".split(" "),i={transition:{end:{WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd",transition:"transitionend"}},animation:{end:{WebkitAnimation:"webkitAnimationEnd",MozAnimation:"animationend",OAnimation:"oAnimationEnd",animation:"animationend"}}},j={csstransforms:function(){return!!e("transform")},csstransforms3d:function(){return!!e("perspective")},csstransitions:function(){return!!e("transition")},cssanimations:function(){return!!e("animation")}};j.csstransitions()&&(a.support.transition=new String(f("transition")),a.support.transition.end=i.transition.end[a.support.transition]),j.cssanimations()&&(a.support.animation=new String(f("animation")),a.support.animation.end=i.animation.end[a.support.animation]),j.csstransforms()&&(a.support.transform=new String(f("transform")),a.support.transform3d=j.csstransforms3d())}(window.Zepto||window.jQuery,window,document);+!function(a,b,c,d){function e(b,c){this.settings=null,this.options=a.extend({},e.Defaults,c),this.$element=a(b),this._handlers={},this._plugins={},this._suppress={},this._current=null,this._speed=null,this._coordinates=[],this._breakpoint=null,this._width=null,this._items=[],this._clones=[],this._mergers=[],this._widths=[],this._invalidated={},this._pipe=[],this._drag={time:null,target:null,pointer:null,stage:{start:null,current:null},direction:null},this._states={current:{},tags:{initializing:["busy"],animating:["busy"],dragging:["interacting"]}},a.each(["onResize","onThrottledResize"],a.proxy(function(b,c){this._handlers[c]=a.proxy(this[c],this)},this)),a.each(e.Plugins,a.proxy(function(a,b){this._plugins[a.charAt(0).toLowerCase()+a.slice(1)]=new b(this)},this)),a.each(e.Workers,a.proxy(function(b,c){this._pipe.push({filter:c.filter,run:a.proxy(c.run,this)})},this)),this.setup(),this.initialize()}e.Defaults={items:3,loop:!1,center:!1,rewind:!1,checkVisibility:!0,mouseDrag:!0,touchDrag:!0,pullDrag:!0,freeDrag:!1,margin:0,stagePadding:0,merge:!1,mergeFit:!0,autoWidth:!1,startPosition:0,rtl:!1,smartSpeed:250,fluidSpeed:!1,dragEndSpeed:!1,responsive:{},responsiveRefreshRate:200,responsiveBaseElement:b,fallbackEasing:"swing",slideTransition:"",info:!1,nestedItemSelector:!1,itemElement:"div",stageElement:"div",refreshClass:"owl-refresh",loadedClass:"owl-loaded",loadingClass:"owl-loading",rtlClass:"owl-rtl",responsiveClass:"owl-responsive",dragClass:"owl-drag",itemClass:"owl-item",stageClass:"owl-stage",stageOuterClass:"owl-stage-outer",grabClass:"owl-grab"},e.Width={Default:"default",Inner:"inner",Outer:"outer"},e.Type={Event:"event",State:"state"},e.Plugins={},e.Workers=[{filter:["width","settings"],run:function(){this._width=this.$element.width()}},{filter:["width","items","settings"],run:function(a){a.current=this._items&&this._items[this.relative(this._current)]}},{filter:["items","settings"],run:function(){this.$stage.children(".cloned").remove()}},{filter:["width","items","settings"],run:function(a){var b=this.settings.margin||"",c=!this.settings.autoWidth,d=this.settings.rtl,e={width:"auto","margin-left":d?b:"","margin-right":d?"":b};!c&&this.$stage.children().css(e),a.css=e}},{filter:["width","items","settings"],run:function(a){var b=(this.width()/this.settings.items).toFixed(3)-this.settings.margin,c=null,d=this._items.length,e=!this.settings.autoWidth,f=[];for(a.items={merge:!1,width:b};d--;)c=this._mergers[d],c=this.settings.mergeFit&&Math.min(c,this.settings.items)||c,a.items.merge=c>1||a.items.merge,f[d]=e?b*c:this._items[d].width();this._widths=f}},{filter:["items","settings"],run:function(){var b=[],c=this._items,d=this.settings,e=Math.max(2*d.items,4),f=2*Math.ceil(c.length/2),g=d.loop&&c.length?d.rewind?e:Math.max(e,f):0,h="",i="";for(g/=2;g>0;)b.push(this.normalize(b.length/2,!0)),h+=c[b[b.length-1]][0].outerHTML,b.push(this.normalize(c.length-1-(b.length-1)/2,!0)),i=c[b[b.length-1]][0].outerHTML+i,g-=1;this._clones=b,a(h).addClass("cloned").appendTo(this.$stage),a(i).addClass("cloned").prependTo(this.$stage)}},{filter:["width","items","settings"],run:function(){for(var a=this.settings.rtl?1:-1,b=this._clones.length+this._items.length,c=-1,d=0,e=0,f=[];++c<b;)d=f[c-1]||0,e=this._widths[this.relative(c)]+this.settings.margin,f.push(d+e*a);this._coordinates=f}},{filter:["width","items","settings"],run:function(){var a=this.settings.stagePadding,b=this._coordinates,c={width:Math.ceil(Math.abs(b[b.length-1]))+2*a,"padding-left":a||"","padding-right":a||""};this.$stage.css(c)}},{filter:["width","items","settings"],run:function(a){var b=this._coordinates.length,c=!this.settings.autoWidth,d=this.$stage.children();if(c&&a.items.merge)for(;b--;)a.css.width=this._widths[this.relative(b)],d.eq(b).css(a.css);else c&&(a.css.width=a.items.width,d.css(a.css))}},{filter:["items"],run:function(){this._coordinates.length<1&&this.$stage.removeAttr("style")}},{filter:["width","items","settings"],run:function(a){a.current=a.current?this.$stage.children().index(a.current):0,a.current=Math.max(this.minimum(),Math.min(this.maximum(),a.current)),this.reset(a.current)}},{filter:["position"],run:function(){this.animate(this.coordinates(this._current))}},{filter:["width","position","items","settings"],run:function(){var a,b,c,d,e=this.settings.rtl?1:-1,f=2*this.settings.stagePadding,g=this.coordinates(this.current())+f,h=g+this.width()*e,i=[];for(c=0,d=this._coordinates.length;c<d;c++)a=this._coordinates[c-1]||0,b=Math.abs(this._coordinates[c])+f*e,(this.op(a,"<=",g)&&this.op(a,">",h)||this.op(b,"<",g)&&this.op(b,">",h))&&i.push(c);this.$stage.children(".active").removeClass("active"),this.$stage.children(":eq("+i.join("), :eq(")+")").addClass("active"),this.$stage.children(".center").removeClass("center"),this.settings.center&&this.$stage.children().eq(this.current()).addClass("center")}}],e.prototype.initializeStage=function(){this.$stage=this.$element.find("."+this.settings.stageClass),this.$stage.length||(this.$element.addClass(this.options.loadingClass),this.$stage=a("<"+this.settings.stageElement+">",{class:this.settings.stageClass}).wrap(a("<div/>",{class:this.settings.stageOuterClass})),this.$element.append(this.$stage.parent()))},e.prototype.initializeItems=function(){var b=this.$element.find(".owl-item");if(b.length)return this._items=b.get().map(function(b){return a(b)}),this._mergers=this._items.map(function(){return 1}),void this.refresh();this.replace(this.$element.children().not(this.$stage.parent())),this.isVisible()?this.refresh():this.invalidate("width"),this.$element.removeClass(this.options.loadingClass).addClass(this.options.loadedClass)},e.prototype.initialize=function(){if(this.enter("initializing"),this.trigger("initialize"),this.$element.toggleClass(this.settings.rtlClass,this.settings.rtl),this.settings.autoWidth&&!this.is("pre-loading")){var a,b,c;a=this.$element.find("img"),b=this.settings.nestedItemSelector?"."+this.settings.nestedItemSelector:d,c=this.$element.children(b).width(),a.length&&c<=0&&this.preloadAutoWidthImages(a)}this.initializeStage(),this.initializeItems(),this.registerEventHandlers(),this.leave("initializing"),this.trigger("initialized")},e.prototype.isVisible=function(){return!this.settings.checkVisibility||this.$element.is(":visible")},e.prototype.setup=function(){var b=this.viewport(),c=this.options.responsive,d=-1,e=null;c?(a.each(c,function(a){a<=b&&a>d&&(d=Number(a))}),e=a.extend({},this.options,c[d]),"function"==typeof e.stagePadding&&(e.stagePadding=e.stagePadding()),delete e.responsive,e.responsiveClass&&this.$element.attr("class",this.$element.attr("class").replace(new RegExp("("+this.options.responsiveClass+"-)\\S+\\s","g"),"$1"+d))):e=a.extend({},this.options),this.trigger("change",{property:{name:"settings",value:e}}),this._breakpoint=d,this.settings=e,this.invalidate("settings"),this.trigger("changed",{property:{name:"settings",value:this.settings}})},e.prototype.optionsLogic=function(){this.settings.autoWidth&&(this.settings.stagePadding=!1,this.settings.merge=!1)},e.prototype.prepare=function(b){var c=this.trigger("prepare",{content:b});return c.data||(c.data=a("<"+this.settings.itemElement+"/>").addClass(this.options.itemClass).append(b)),this.trigger("prepared",{content:c.data}),c.data},e.prototype.update=function(){for(var b=0,c=this._pipe.length,d=a.proxy(function(a){return this[a]},this._invalidated),e={};b<c;)(this._invalidated.all||a.grep(this._pipe[b].filter,d).length>0)&&this._pipe[b].run(e),b++;this._invalidated={},!this.is("valid")&&this.enter("valid")},e.prototype.width=function(a){switch(a=a||e.Width.Default){case e.Width.Inner:case e.Width.Outer:return this._width;default:return this._width-2*this.settings.stagePadding+this.settings.margin}},e.prototype.refresh=function(){this.enter("refreshing"),this.trigger("refresh"),this.setup(),this.optionsLogic(),this.$element.addClass(this.options.refreshClass),this.update(),this.$element.removeClass(this.options.refreshClass),this.leave("refreshing"),this.trigger("refreshed")},e.prototype.onThrottledResize=function(){b.clearTimeout(this.resizeTimer),this.resizeTimer=b.setTimeout(this._handlers.onResize,this.settings.responsiveRefreshRate)},e.prototype.onResize=function(){return!!this._items.length&&(this._width!==this.$element.width()&&(!!this.isVisible()&&(this.enter("resizing"),this.trigger("resize").isDefaultPrevented()?(this.leave("resizing"),!1):(this.invalidate("width"),this.refresh(),this.leave("resizing"),void this.trigger("resized")))))},e.prototype.registerEventHandlers=function(){a.support.transition&&this.$stage.on(a.support.transition.end+".owl.core",a.proxy(this.onTransitionEnd,this)),!1!==this.settings.responsive&&this.on(b,"resize",this._handlers.onThrottledResize),this.settings.mouseDrag&&(this.$element.addClass(this.options.dragClass),this.$stage.on("mousedown.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("dragstart.owl.core selectstart.owl.core",function(){return!1})),this.settings.touchDrag&&(this.$stage.on("touchstart.owl.core",a.proxy(this.onDragStart,this)),this.$stage.on("touchcancel.owl.core",a.proxy(this.onDragEnd,this)))},e.prototype.onDragStart=function(b){var d=null;3!==b.which&&(a.support.transform?(d=this.$stage.css("transform").replace(/.*\(|\)| /g,"").split(","),d={x:d[16===d.length?12:4],y:d[16===d.length?13:5]}):(d=this.$stage.position(),d={x:this.settings.rtl?d.left+this.$stage.width()-this.width()+this.settings.margin:d.left,y:d.top}),this.is("animating")&&(a.support.transform?this.animate(d.x):this.$stage.stop(),this.invalidate("position")),this.$element.toggleClass(this.options.grabClass,"mousedown"===b.type),this.speed(0),this._drag.time=(new Date).getTime(),this._drag.target=a(b.target),this._drag.stage.start=d,this._drag.stage.current=d,this._drag.pointer=this.pointer(b),a(c).on("mouseup.owl.core touchend.owl.core",a.proxy(this.onDragEnd,this)),a(c).one("mousemove.owl.core touchmove.owl.core",a.proxy(function(b){var d=this.difference(this._drag.pointer,this.pointer(b));a(c).on("mousemove.owl.core touchmove.owl.core",a.proxy(this.onDragMove,this)),Math.abs(d.x)<Math.abs(d.y)&&this.is("valid")||(b.preventDefault(),this.enter("dragging"),this.trigger("drag"))},this)))},e.prototype.onDragMove=function(a){var b=null,c=null,d=null,e=this.difference(this._drag.pointer,this.pointer(a)),f=this.difference(this._drag.stage.start,e);this.is("dragging")&&(a.preventDefault(),this.settings.loop?(b=this.coordinates(this.minimum()),c=this.coordinates(this.maximum()+1)-b,f.x=((f.x-b)%c+c)%c+b):(b=this.settings.rtl?this.coordinates(this.maximum()):this.coordinates(this.minimum()),c=this.settings.rtl?this.coordinates(this.minimum()):this.coordinates(this.maximum()),d=this.settings.pullDrag?-1*e.x/5:0,f.x=Math.max(Math.min(f.x,b+d),c+d)),this._drag.stage.current=f,this.animate(f.x))},e.prototype.onDragEnd=function(b){var d=this.difference(this._drag.pointer,this.pointer(b)),e=this._drag.stage.current,f=d.x>0^this.settings.rtl?"left":"right";a(c).off(".owl.core"),this.$element.removeClass(this.options.grabClass),(0!==d.x&&this.is("dragging")||!this.is("valid"))&&(this.speed(this.settings.dragEndSpeed||this.settings.smartSpeed),this.current(this.closest(e.x,0!==d.x?f:this._drag.direction)),this.invalidate("position"),this.update(),this._drag.direction=f,(Math.abs(d.x)>3||(new Date).getTime()-this._drag.time>300)&&this._drag.target.one("click.owl.core",function(){return!1})),this.is("dragging")&&(this.leave("dragging"),this.trigger("dragged"))},e.prototype.closest=function(b,c){var e=-1,f=30,g=this.width(),h=this.coordinates();return this.settings.freeDrag||a.each(h,a.proxy(function(a,i){return"left"===c&&b>i-f&&b<i+f?e=a:"right"===c&&b>i-g-f&&b<i-g+f?e=a+1:this.op(b,"<",i)&&this.op(b,">",h[a+1]!==d?h[a+1]:i-g)&&(e="left"===c?a+1:a),-1===e},this)),this.settings.loop||(this.op(b,">",h[this.minimum()])?e=b=this.minimum():this.op(b,"<",h[this.maximum()])&&(e=b=this.maximum())),e},e.prototype.animate=function(b){var c=this.speed()>0;this.is("animating")&&this.onTransitionEnd(),c&&(this.enter("animating"),this.trigger("translate")),a.support.transform3d&&a.support.transition?this.$stage.css({transform:"translate3d("+b+"px,0px,0px)",transition:this.speed()/1e3+"s"+(this.settings.slideTransition?" "+this.settings.slideTransition:"")}):c?this.$stage.animate({left:b+"px"},this.speed(),this.settings.fallbackEasing,a.proxy(this.onTransitionEnd,this)):this.$stage.css({left:b+"px"})},e.prototype.is=function(a){return this._states.current[a]&&this._states.current[a]>0},e.prototype.current=function(a){if(a===d)return this._current;if(0===this._items.length)return d;if(a=this.normalize(a),this._current!==a){var b=this.trigger("change",{property:{name:"position",value:a}});b.data!==d&&(a=this.normalize(b.data)),this._current=a,this.invalidate("position"),this.trigger("changed",{property:{name:"position",value:this._current}})}return this._current},e.prototype.invalidate=function(b){return"string"===a.type(b)&&(this._invalidated[b]=!0,this.is("valid")&&this.leave("valid")),a.map(this._invalidated,function(a,b){return b})},e.prototype.reset=function(a){(a=this.normalize(a))!==d&&(this._speed=0,this._current=a,this.suppress(["translate","translated"]),this.animate(this.coordinates(a)),this.release(["translate","translated"]))},e.prototype.normalize=function(a,b){var c=this._items.length,e=b?0:this._clones.length;return!this.isNumeric(a)||c<1?a=d:(a<0||a>=c+e)&&(a=((a-e/2)%c+c)%c+e/2),a},e.prototype.relative=function(a){return a-=this._clones.length/2,this.normalize(a,!0)},e.prototype.maximum=function(a){var b,c,d,e=this.settings,f=this._coordinates.length;if(e.loop)f=this._clones.length/2+this._items.length-1;else if(e.autoWidth||e.merge){if(b=this._items.length)for(c=this._items[--b].width(),d=this.$element.width();b--&&!((c+=this._items[b].width()+this.settings.margin)>d););f=b+1}else f=e.center?this._items.length-1:this._items.length-e.items;return a&&(f-=this._clones.length/2),Math.max(f,0)},e.prototype.minimum=function(a){return a?0:this._clones.length/2},e.prototype.items=function(a){return a===d?this._items.slice():(a=this.normalize(a,!0),this._items[a])},e.prototype.mergers=function(a){return a===d?this._mergers.slice():(a=this.normalize(a,!0),this._mergers[a])},e.prototype.clones=function(b){var c=this._clones.length/2,e=c+this._items.length,f=function(a){return a%2==0?e+a/2:c-(a+1)/2};return b===d?a.map(this._clones,function(a,b){return f(b)}):a.map(this._clones,function(a,c){return a===b?f(c):null})},e.prototype.speed=function(a){return a!==d&&(this._speed=a),this._speed},e.prototype.coordinates=function(b){var c,e=1,f=b-1;return b===d?a.map(this._coordinates,a.proxy(function(a,b){return this.coordinates(b)},this)):(this.settings.center?(this.settings.rtl&&(e=-1,f=b+1),c=this._coordinates[b],c+=(this.width()-c+(this._coordinates[f]||0))/2*e):c=this._coordinates[f]||0,c=Math.ceil(c))},e.prototype.duration=function(a,b,c){return 0===c?0:Math.min(Math.max(Math.abs(b-a),1),6)*Math.abs(c||this.settings.smartSpeed)},e.prototype.to=function(a,b){var c=this.current(),d=null,e=a-this.relative(c),f=(e>0)-(e<0),g=this._items.length,h=this.minimum(),i=this.maximum();this.settings.loop?(!this.settings.rewind&&Math.abs(e)>g/2&&(e+=-1*f*g),a=c+e,(d=((a-h)%g+g)%g+h)!==a&&d-e<=i&&d-e>0&&(c=d-e,a=d,this.reset(c))):this.settings.rewind?(i+=1,a=(a%i+i)%i):a=Math.max(h,Math.min(i,a)),this.speed(this.duration(c,a,b)),this.current(a),this.isVisible()&&this.update()},e.prototype.next=function(a){a=a||!1,this.to(this.relative(this.current())+1,a)},e.prototype.prev=function(a){a=a||!1,this.to(this.relative(this.current())-1,a)},e.prototype.onTransitionEnd=function(a){if(a!==d&&(a.stopPropagation(),(a.target||a.srcElement||a.originalTarget)!==this.$stage.get(0)))return!1;this.leave("animating"),this.trigger("translated")},e.prototype.viewport=function(){var d;return this.options.responsiveBaseElement!==b?d=a(this.options.responsiveBaseElement).width():b.innerWidth?d=b.innerWidth:c.documentElement&&c.documentElement.clientWidth?d=c.documentElement.clientWidth:console.warn("Can not detect viewport width."),d},e.prototype.replace=function(b){this.$stage.empty(),this._items=[],b&&(b=b instanceof jQuery?b:a(b)),this.settings.nestedItemSelector&&(b=b.find("."+this.settings.nestedItemSelector)),b.filter(function(){return 1===this.nodeType}).each(a.proxy(function(a,b){b=this.prepare(b),this.$stage.append(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)},this)),this.reset(this.isNumeric(this.settings.startPosition)?this.settings.startPosition:0),this.invalidate("items")},e.prototype.add=function(b,c){var e=this.relative(this._current);c=c===d?this._items.length:this.normalize(c,!0),b=b instanceof jQuery?b:a(b),this.trigger("add",{content:b,position:c}),b=this.prepare(b),0===this._items.length||c===this._items.length?(0===this._items.length&&this.$stage.append(b),0!==this._items.length&&this._items[c-1].after(b),this._items.push(b),this._mergers.push(1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)):(this._items[c].before(b),this._items.splice(c,0,b),this._mergers.splice(c,0,1*b.find("[data-merge]").addBack("[data-merge]").attr("data-merge")||1)),this._items[e]&&this.reset(this._items[e].index()),this.invalidate("items"),this.trigger("added",{content:b,position:c})},e.prototype.remove=function(a){(a=this.normalize(a,!0))!==d&&(this.trigger("remove",{content:this._items[a],position:a}),this._items[a].remove(),this._items.splice(a,1),this._mergers.splice(a,1),this.invalidate("items"),this.trigger("removed",{content:null,position:a}))},e.prototype.preloadAutoWidthImages=function(b){b.each(a.proxy(function(b,c){this.enter("pre-loading"),c=a(c),a(new Image).one("load",a.proxy(function(a){c.attr("src",a.target.src),c.css("opacity",1),this.leave("pre-loading"),!this.is("pre-loading")&&!this.is("initializing")&&this.refresh()},this)).attr("src",c.attr("src")||c.attr("data-src")||c.attr("data-src-retina"))},this))},e.prototype.destroy=function(){this.$element.off(".owl.core"),this.$stage.off(".owl.core"),a(c).off(".owl.core"),!1!==this.settings.responsive&&(b.clearTimeout(this.resizeTimer),this.off(b,"resize",this._handlers.onThrottledResize));for(var d in this._plugins)this._plugins[d].destroy();this.$stage.children(".cloned").remove(),this.$stage.unwrap(),this.$stage.children().contents().unwrap(),this.$stage.children().unwrap(),this.$stage.remove(),this.$element.removeClass(this.options.refreshClass).removeClass(this.options.loadingClass).removeClass(this.options.loadedClass).removeClass(this.options.rtlClass).removeClass(this.options.dragClass).removeClass(this.options.grabClass).attr("class",this.$element.attr("class").replace(new RegExp(this.options.responsiveClass+"-\\S+\\s","g"),"")).removeData("owl.carousel")},e.prototype.op=function(a,b,c){var d=this.settings.rtl;switch(b){case"<":return d?a>c:a<c;case">":return d?a<c:a>c;case">=":return d?a<=c:a>=c;case"<=":return d?a>=c:a<=c}},e.prototype.on=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,d):a.attachEvent&&a.attachEvent("on"+b,c)},e.prototype.off=function(a,b,c,d){a.removeEventListener?a.removeEventListener(b,c,d):a.detachEvent&&a.detachEvent("on"+b,c)},e.prototype.trigger=function(b,c,d,f,g){var h={item:{count:this._items.length,index:this.current()}},i=a.camelCase(a.grep(["on",b,d],function(a){return a}).join("-").toLowerCase()),j=a.Event([b,"owl",d||"carousel"].join(".").toLowerCase(),a.extend({relatedTarget:this},h,c));return this._suppress[b]||(a.each(this._plugins,function(a,b){b.onTrigger&&b.onTrigger(j)}),this.register({type:e.Type.Event,name:b}),this.$element.trigger(j),this.settings&&"function"==typeof this.settings[i]&&this.settings[i].call(this,j)),j},e.prototype.enter=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]===d&&(this._states.current[b]=0),this._states.current[b]++},this))},e.prototype.leave=function(b){a.each([b].concat(this._states.tags[b]||[]),a.proxy(function(a,b){this._states.current[b]--},this))},e.prototype.register=function(b){if(b.type===e.Type.Event){if(a.event.special[b.name]||(a.event.special[b.name]={}),!a.event.special[b.name].owl){var c=a.event.special[b.name]._default;a.event.special[b.name]._default=function(a){return!c||!c.apply||a.namespace&&-1!==a.namespace.indexOf("owl")?a.namespace&&a.namespace.indexOf("owl")>-1:c.apply(this,arguments)},a.event.special[b.name].owl=!0}}else b.type===e.Type.State&&(this._states.tags[b.name]?this._states.tags[b.name]=this._states.tags[b.name].concat(b.tags):this._states.tags[b.name]=b.tags,this._states.tags[b.name]=a.grep(this._states.tags[b.name],a.proxy(function(c,d){return a.inArray(c,this._states.tags[b.name])===d},this)))},e.prototype.suppress=function(b){a.each(b,a.proxy(function(a,b){this._suppress[b]=!0},this))},e.prototype.release=function(b){a.each(b,a.proxy(function(a,b){delete this._suppress[b]},this))},e.prototype.pointer=function(a){var c={x:null,y:null};return a=a.originalEvent||a||b.event,a=a.touches&&a.touches.length?a.touches[0]:a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:a,a.pageX?(c.x=a.pageX,c.y=a.pageY):(c.x=a.clientX,c.y=a.clientY),c},e.prototype.isNumeric=function(a){return!isNaN(parseFloat(a))},e.prototype.difference=function(a,b){return{x:a.x-b.x,y:a.y-b.y}},a.fn.owlCarousel=function(b){var c=Array.prototype.slice.call(arguments,1);return this.each(function(){var d=a(this),f=d.data("owl.carousel");f||(f=new e(this,"object"==typeof b&&b),d.data("owl.carousel",f),a.each(["next","prev","to","destroy","refresh","replace","add","remove"],function(b,c){f.register({type:e.Type.Event,name:c}),f.$element.on(c+".owl.carousel.core",a.proxy(function(a){a.namespace&&a.relatedTarget!==this&&(this.suppress([c]),f[c].apply(this,[].slice.call(arguments,1)),this.release([c]))},f))})),"string"==typeof b&&"_"!==b.charAt(0)&&f[b].apply(f,c)})},a.fn.owlCarousel.Constructor=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._interval=null,this._visible=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoRefresh&&this.watch()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={autoRefresh:!0,autoRefreshInterval:500},e.prototype.watch=function(){this._interval||(this._visible=this._core.isVisible(),this._interval=b.setInterval(a.proxy(this.refresh,this),this._core.settings.autoRefreshInterval))},e.prototype.refresh=function(){this._core.isVisible()!==this._visible&&(this._visible=!this._visible,this._core.$element.toggleClass("owl-hidden",!this._visible),this._visible&&this._core.invalidate("width")&&this._core.refresh())},e.prototype.destroy=function(){var a,c;b.clearInterval(this._interval);for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoRefresh=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._loaded=[],this._handlers={"initialized.owl.carousel change.owl.carousel resized.owl.carousel":a.proxy(function(b){if(b.namespace&&this._core.settings&&this._core.settings.lazyLoad&&(b.property&&"position"==b.property.name||"initialized"==b.type)){var c=this._core.settings,e=c.center&&Math.ceil(c.items/2)||c.items,f=c.center&&-1*e||0,g=(b.property&&b.property.value!==d?b.property.value:this._core.current())+f,h=this._core.clones().length,i=a.proxy(function(a,b){this.load(b)},this);for(c.lazyLoadEager>0&&(e+=c.lazyLoadEager,c.loop&&(g-=c.lazyLoadEager,e++));f++<e;)this.load(h/2+this._core.relative(g)),h&&a.each(this._core.clones(this._core.relative(g)),i),g++}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers)};e.Defaults={lazyLoad:!1,lazyLoadEager:0},e.prototype.load=function(c){var d=this._core.$stage.children().eq(c),e=d&&d.find(".owl-lazy");!e||a.inArray(d.get(0),this._loaded)>-1||(e.each(a.proxy(function(c,d){var e,f=a(d),g=b.devicePixelRatio>1&&f.attr("data-src-retina")||f.attr("data-src")||f.attr("data-srcset");this._core.trigger("load",{element:f,url:g},"lazy"),f.is("img")?f.one("load.owl.lazy",a.proxy(function(){f.css("opacity",1),this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("src",g):f.is("source")?f.one("load.owl.lazy",a.proxy(function(){this._core.trigger("loaded",{element:f,url:g},"lazy")},this)).attr("srcset",g):(e=new Image,e.onload=a.proxy(function(){f.css({"background-image":'url("'+g+'")',opacity:"1"}),this._core.trigger("loaded",{element:f,url:g},"lazy")},this),e.src=g)},this)),this._loaded.push(d.get(0)))},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this._core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Lazy=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(c){this._core=c,this._previousHeight=null,this._handlers={"initialized.owl.carousel refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&this.update()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&"position"===a.property.name&&this.update()},this),"loaded.owl.lazy":a.proxy(function(a){a.namespace&&this._core.settings.autoHeight&&a.element.closest("."+this._core.settings.itemClass).index()===this._core.current()&&this.update()},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers),this._intervalId=null;var d=this;a(b).on("load",function(){d._core.settings.autoHeight&&d.update()}),a(b).resize(function(){d._core.settings.autoHeight&&(null!=d._intervalId&&clearTimeout(d._intervalId),d._intervalId=setTimeout(function(){d.update()},250))})};e.Defaults={autoHeight:!1,autoHeightClass:"owl-height"},e.prototype.update=function(){var b=this._core._current,c=b+this._core.settings.items,d=this._core.settings.lazyLoad,e=this._core.$stage.children().toArray().slice(b,c),f=[],g=0;a.each(e,function(b,c){f.push(a(c).height())}),g=Math.max.apply(null,f),g<=1&&d&&this._previousHeight&&(g=this._previousHeight),this._previousHeight=g,this._core.$stage.parent().height(g).addClass(this._core.settings.autoHeightClass)},e.prototype.destroy=function(){var a,b;for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.AutoHeight=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._videos={},this._playing=null,this._handlers={"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.register({type:"state",name:"playing",tags:["interacting"]})},this),"resize.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.video&&this.isInFullScreen()&&a.preventDefault()},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._core.is("resizing")&&this._core.$stage.find(".cloned .owl-video-frame").remove()},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"===a.property.name&&this._playing&&this.stop()},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find(".owl-video");c.length&&(c.css("display","none"),this.fetch(c,a(b.content)))}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this._core.$element.on(this._handlers),this._core.$element.on("click.owl.video",".owl-video-play-icon",a.proxy(function(a){this.play(a)},this))};e.Defaults={video:!1,videoHeight:!1,videoWidth:!1},e.prototype.fetch=function(a,b){var c=function(){return a.attr("data-vimeo-id")?"vimeo":a.attr("data-vzaar-id")?"vzaar":"youtube"}(),d=a.attr("data-vimeo-id")||a.attr("data-youtube-id")||a.attr("data-vzaar-id"),e=a.attr("data-width")||this._core.settings.videoWidth,f=a.attr("data-height")||this._core.settings.videoHeight,g=a.attr("href");if(!g)throw new Error("Missing video URL.");if(d=g.match(/(http:|https:|)\/\/(player.|www.|app.)?(vimeo\.com|youtu(be\.com|\.be|be\.googleapis\.com|be\-nocookie\.com)|vzaar\.com)\/(video\/|videos\/|embed\/|channels\/.+\/|groups\/.+\/|watch\?v=|v\/)?([A-Za-z0-9._%-]*)(\&\S+)?/),d[3].indexOf("youtu")>-1)c="youtube";else if(d[3].indexOf("vimeo")>-1)c="vimeo";else{if(!(d[3].indexOf("vzaar")>-1))throw new Error("Video URL not supported.");c="vzaar"}d=d[6],this._videos[g]={type:c,id:d,width:e,height:f},b.attr("data-video",g),this.thumbnail(a,this._videos[g])},e.prototype.thumbnail=function(b,c){var d,e,f,g=c.width&&c.height?"width:"+c.width+"px;height:"+c.height+"px;":"",h=b.find("img"),i="src",j="",k=this._core.settings,l=function(c){e='<div class="owl-video-play-icon"></div>',d=k.lazyLoad?a("<div/>",{class:"owl-video-tn "+j,srcType:c}):a("<div/>",{class:"owl-video-tn",style:"opacity:1;background-image:url("+c+")"}),b.after(d),b.after(e)};if(b.wrap(a("<div/>",{class:"owl-video-wrapper",style:g})),this._core.settings.lazyLoad&&(i="data-src",j="owl-lazy"),h.length)return l(h.attr(i)),h.remove(),!1;"youtube"===c.type?(f="//img.youtube.com/vi/"+c.id+"/hqdefault.jpg",l(f)):"vimeo"===c.type?a.ajax({type:"GET",url:"//vimeo.com/api/v2/video/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a[0].thumbnail_large,l(f)}}):"vzaar"===c.type&&a.ajax({type:"GET",url:"//vzaar.com/api/videos/"+c.id+".json",jsonp:"callback",dataType:"jsonp",success:function(a){f=a.framegrab_url,l(f)}})},e.prototype.stop=function(){this._core.trigger("stop",null,"video"),this._playing.find(".owl-video-frame").remove(),this._playing.removeClass("owl-video-playing"),this._playing=null,this._core.leave("playing"),this._core.trigger("stopped",null,"video")},e.prototype.play=function(b){var c,d=a(b.target),e=d.closest("."+this._core.settings.itemClass),f=this._videos[e.attr("data-video")],g=f.width||"100%",h=f.height||this._core.$stage.height();this._playing||(this._core.enter("playing"),this._core.trigger("play",null,"video"),e=this._core.items(this._core.relative(e.index())),this._core.reset(e.index()),c=a('<iframe frameborder="0" allowfullscreen mozallowfullscreen webkitAllowFullScreen ></iframe>'),c.attr("height",h),c.attr("width",g),"youtube"===f.type?c.attr("src","//www.youtube.com/embed/"+f.id+"?autoplay=1&rel=0&v="+f.id):"vimeo"===f.type?c.attr("src","//player.vimeo.com/video/"+f.id+"?autoplay=1"):"vzaar"===f.type&&c.attr("src","//view.vzaar.com/"+f.id+"/player?autoplay=true"),a(c).wrap('<div class="owl-video-frame" />').insertAfter(e.find(".owl-video")),this._playing=e.addClass("owl-video-playing"))},e.prototype.isInFullScreen=function(){var b=c.fullscreenElement||c.mozFullScreenElement||c.webkitFullscreenElement;return b&&a(b).parent().hasClass("owl-video-frame")},e.prototype.destroy=function(){var a,b;this._core.$element.off("click.owl.video");for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Video=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this.core=b,this.core.options=a.extend({},e.Defaults,this.core.options),this.swapping=!0,this.previous=d,this.next=d,this.handlers={"change.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&(this.previous=this.core.current(),this.next=a.property.value)},this),"drag.owl.carousel dragged.owl.carousel translated.owl.carousel":a.proxy(function(a){a.namespace&&(this.swapping="translated"==a.type)},this),"translate.owl.carousel":a.proxy(function(a){a.namespace&&this.swapping&&(this.core.options.animateOut||this.core.options.animateIn)&&this.swap()},this)},this.core.$element.on(this.handlers)};e.Defaults={animateOut:!1,
+animateIn:!1},e.prototype.swap=function(){if(1===this.core.settings.items&&a.support.animation&&a.support.transition){this.core.speed(0);var b,c=a.proxy(this.clear,this),d=this.core.$stage.children().eq(this.previous),e=this.core.$stage.children().eq(this.next),f=this.core.settings.animateIn,g=this.core.settings.animateOut;this.core.current()!==this.previous&&(g&&(b=this.core.coordinates(this.previous)-this.core.coordinates(this.next),d.one(a.support.animation.end,c).css({left:b+"px"}).addClass("animated owl-animated-out").addClass(g)),f&&e.one(a.support.animation.end,c).addClass("animated owl-animated-in").addClass(f))}},e.prototype.clear=function(b){a(b.target).css({left:""}).removeClass("animated owl-animated-out owl-animated-in").removeClass(this.core.settings.animateIn).removeClass(this.core.settings.animateOut),this.core.onTransitionEnd()},e.prototype.destroy=function(){var a,b;for(a in this.handlers)this.core.$element.off(a,this.handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.Animate=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){var e=function(b){this._core=b,this._call=null,this._time=0,this._timeout=0,this._paused=!0,this._handlers={"changed.owl.carousel":a.proxy(function(a){a.namespace&&"settings"===a.property.name?this._core.settings.autoplay?this.play():this.stop():a.namespace&&"position"===a.property.name&&this._paused&&(this._time=0)},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.autoplay&&this.play()},this),"play.owl.autoplay":a.proxy(function(a,b,c){a.namespace&&this.play(b,c)},this),"stop.owl.autoplay":a.proxy(function(a){a.namespace&&this.stop()},this),"mouseover.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"mouseleave.owl.autoplay":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.play()},this),"touchstart.owl.core":a.proxy(function(){this._core.settings.autoplayHoverPause&&this._core.is("rotating")&&this.pause()},this),"touchend.owl.core":a.proxy(function(){this._core.settings.autoplayHoverPause&&this.play()},this)},this._core.$element.on(this._handlers),this._core.options=a.extend({},e.Defaults,this._core.options)};e.Defaults={autoplay:!1,autoplayTimeout:5e3,autoplayHoverPause:!1,autoplaySpeed:!1},e.prototype._next=function(d){this._call=b.setTimeout(a.proxy(this._next,this,d),this._timeout*(Math.round(this.read()/this._timeout)+1)-this.read()),this._core.is("interacting")||c.hidden||this._core.next(d||this._core.settings.autoplaySpeed)},e.prototype.read=function(){return(new Date).getTime()-this._time},e.prototype.play=function(c,d){var e;this._core.is("rotating")||this._core.enter("rotating"),c=c||this._core.settings.autoplayTimeout,e=Math.min(this._time%(this._timeout||c),c),this._paused?(this._time=this.read(),this._paused=!1):b.clearTimeout(this._call),this._time+=this.read()%c-e,this._timeout=c,this._call=b.setTimeout(a.proxy(this._next,this,d),c-e)},e.prototype.stop=function(){this._core.is("rotating")&&(this._time=0,this._paused=!0,b.clearTimeout(this._call),this._core.leave("rotating"))},e.prototype.pause=function(){this._core.is("rotating")&&!this._paused&&(this._time=this.read(),this._paused=!0,b.clearTimeout(this._call))},e.prototype.destroy=function(){var a,b;this.stop();for(a in this._handlers)this._core.$element.off(a,this._handlers[a]);for(b in Object.getOwnPropertyNames(this))"function"!=typeof this[b]&&(this[b]=null)},a.fn.owlCarousel.Constructor.Plugins.autoplay=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(b){this._core=b,this._initialized=!1,this._pages=[],this._controls={},this._templates=[],this.$element=this._core.$element,this._overrides={next:this._core.next,prev:this._core.prev,to:this._core.to},this._handlers={"prepared.owl.carousel":a.proxy(function(b){b.namespace&&this._core.settings.dotsData&&this._templates.push('<div class="'+this._core.settings.dotClass+'">'+a(b.content).find("[data-dot]").addBack("[data-dot]").attr("data-dot")+"</div>")},this),"added.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,0,this._templates.pop())},this),"remove.owl.carousel":a.proxy(function(a){a.namespace&&this._core.settings.dotsData&&this._templates.splice(a.position,1)},this),"changed.owl.carousel":a.proxy(function(a){a.namespace&&"position"==a.property.name&&this.draw()},this),"initialized.owl.carousel":a.proxy(function(a){a.namespace&&!this._initialized&&(this._core.trigger("initialize",null,"navigation"),this.initialize(),this.update(),this.draw(),this._initialized=!0,this._core.trigger("initialized",null,"navigation"))},this),"refreshed.owl.carousel":a.proxy(function(a){a.namespace&&this._initialized&&(this._core.trigger("refresh",null,"navigation"),this.update(),this.draw(),this._core.trigger("refreshed",null,"navigation"))},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers)};e.Defaults={nav:!1,navText:['<span aria-label="Previous">&#x2039;</span>','<span aria-label="Next">&#x203a;</span>'],navSpeed:!1,navElement:'button type="button" role="presentation"',navContainer:!1,navContainerClass:"owl-nav",navClass:["owl-prev","owl-next"],slideBy:1,dotClass:"owl-dot",dotsClass:"owl-dots",dots:!0,dotsEach:!1,dotsData:!1,dotsSpeed:!1,dotsContainer:!1},e.prototype.initialize=function(){var b,c=this._core.settings;this._controls.$relative=(c.navContainer?a(c.navContainer):a("<div>").addClass(c.navContainerClass).appendTo(this.$element)).addClass("disabled"),this._controls.$previous=a("<"+c.navElement+">").addClass(c.navClass[0]).html(c.navText[0]).prependTo(this._controls.$relative).on("click",a.proxy(function(a){this.prev(c.navSpeed)},this)),this._controls.$next=a("<"+c.navElement+">").addClass(c.navClass[1]).html(c.navText[1]).appendTo(this._controls.$relative).on("click",a.proxy(function(a){this.next(c.navSpeed)},this)),c.dotsData||(this._templates=[a('<button role="button">').addClass(c.dotClass).append(a("<span>")).prop("outerHTML")]),this._controls.$absolute=(c.dotsContainer?a(c.dotsContainer):a("<div>").addClass(c.dotsClass).appendTo(this.$element)).addClass("disabled"),this._controls.$absolute.on("click","button",a.proxy(function(b){var d=a(b.target).parent().is(this._controls.$absolute)?a(b.target).index():a(b.target).parent().index();b.preventDefault(),this.to(d,c.dotsSpeed)},this));for(b in this._overrides)this._core[b]=a.proxy(this[b],this)},e.prototype.destroy=function(){var a,b,c,d,e;e=this._core.settings;for(a in this._handlers)this.$element.off(a,this._handlers[a]);for(b in this._controls)"$relative"===b&&e.navContainer?this._controls[b].html(""):this._controls[b].remove();for(d in this.overrides)this._core[d]=this._overrides[d];for(c in Object.getOwnPropertyNames(this))"function"!=typeof this[c]&&(this[c]=null)},e.prototype.update=function(){var a,b,c,d=this._core.clones().length/2,e=d+this._core.items().length,f=this._core.maximum(!0),g=this._core.settings,h=g.center||g.autoWidth||g.dotsData?1:g.dotsEach||g.items;if("page"!==g.slideBy&&(g.slideBy=Math.min(g.slideBy,g.items)),g.dots||"page"==g.slideBy)for(this._pages=[],a=d,b=0,c=0;a<e;a++){if(b>=h||0===b){if(this._pages.push({start:Math.min(f,a-d),end:a-d+h-1}),Math.min(f,a-d)===f)break;b=0,++c}b+=this._core.mergers(this._core.relative(a))}},e.prototype.draw=function(){var b,c=this._core.settings,d=this._core.items().length<=c.items,e=this._core.relative(this._core.current()),f=c.loop||c.rewind;this._controls.$relative.toggleClass("disabled",!c.nav||d),c.nav&&(this._controls.$previous.toggleClass("disabled",!f&&e<=this._core.minimum(!0)),this._controls.$next.toggleClass("disabled",!f&&e>=this._core.maximum(!0))),this._controls.$absolute.toggleClass("disabled",!c.dots||d),c.dots&&(b=this._pages.length-this._controls.$absolute.children().length,c.dotsData&&0!==b?this._controls.$absolute.html(this._templates.join("")):b>0?this._controls.$absolute.append(new Array(b+1).join(this._templates[0])):b<0&&this._controls.$absolute.children().slice(b).remove(),this._controls.$absolute.find(".active").removeClass("active"),this._controls.$absolute.children().eq(a.inArray(this.current(),this._pages)).addClass("active"))},e.prototype.onTrigger=function(b){var c=this._core.settings;b.page={index:a.inArray(this.current(),this._pages),count:this._pages.length,size:c&&(c.center||c.autoWidth||c.dotsData?1:c.dotsEach||c.items)}},e.prototype.current=function(){var b=this._core.relative(this._core.current());return a.grep(this._pages,a.proxy(function(a,c){return a.start<=b&&a.end>=b},this)).pop()},e.prototype.getPosition=function(b){var c,d,e=this._core.settings;return"page"==e.slideBy?(c=a.inArray(this.current(),this._pages),d=this._pages.length,b?++c:--c,c=this._pages[(c%d+d)%d].start):(c=this._core.relative(this._core.current()),d=this._core.items().length,b?c+=e.slideBy:c-=e.slideBy),c},e.prototype.next=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!0),b)},e.prototype.prev=function(b){a.proxy(this._overrides.to,this._core)(this.getPosition(!1),b)},e.prototype.to=function(b,c,d){var e;!d&&this._pages.length?(e=this._pages.length,a.proxy(this._overrides.to,this._core)(this._pages[(b%e+e)%e].start,c)):a.proxy(this._overrides.to,this._core)(b,c)},a.fn.owlCarousel.Constructor.Plugins.Navigation=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){"use strict";var e=function(c){this._core=c,this._hashes={},this.$element=this._core.$element,this._handlers={"initialized.owl.carousel":a.proxy(function(c){c.namespace&&"URLHash"===this._core.settings.startPosition&&a(b).trigger("hashchange.owl.navigation")},this),"prepared.owl.carousel":a.proxy(function(b){if(b.namespace){var c=a(b.content).find("[data-hash]").addBack("[data-hash]").attr("data-hash");if(!c)return;this._hashes[c]=b.content}},this),"changed.owl.carousel":a.proxy(function(c){if(c.namespace&&"position"===c.property.name){var d=this._core.items(this._core.relative(this._core.current())),e=a.map(this._hashes,function(a,b){return a===d?b:null}).join();if(!e||b.location.hash.slice(1)===e)return;b.location.hash=e}},this)},this._core.options=a.extend({},e.Defaults,this._core.options),this.$element.on(this._handlers),a(b).on("hashchange.owl.navigation",a.proxy(function(a){var c=b.location.hash.substring(1),e=this._core.$stage.children(),f=this._hashes[c]&&e.index(this._hashes[c]);f!==d&&f!==this._core.current()&&this._core.to(this._core.relative(f),!1,!0)},this))};e.Defaults={URLhashListener:!1},e.prototype.destroy=function(){var c,d;a(b).off("hashchange.owl.navigation");for(c in this._handlers)this._core.$element.off(c,this._handlers[c]);for(d in Object.getOwnPropertyNames(this))"function"!=typeof this[d]&&(this[d]=null)},a.fn.owlCarousel.Constructor.Plugins.Hash=e}(window.Zepto||window.jQuery,window,document),function(a,b,c,d){function e(b,c){var e=!1,f=b.charAt(0).toUpperCase()+b.slice(1);return a.each((b+" "+h.join(f+" ")+f).split(" "),function(a,b){if(g[b]!==d)return e=!c||b,!1}),e}function f(a){return e(a,!0)}var g=a("<support>").get(0).style,h="Webkit Moz O ms".split(" "),i={transition:{end:{WebkitTransition:"webkitTransitionEnd",MozTransition:"transitionend",OTransition:"oTransitionEnd",transition:"transitionend"}},animation:{end:{WebkitAnimation:"webkitAnimationEnd",MozAnimation:"animationend",OAnimation:"oAnimationEnd",animation:"animationend"}}},j={csstransforms:function(){return!!e("transform")},csstransforms3d:function(){return!!e("perspective")},csstransitions:function(){return!!e("transition")},cssanimations:function(){return!!e("animation")}};j.csstransitions()&&(a.support.transition=new String(f("transition")),a.support.transition.end=i.transition.end[a.support.transition]),j.cssanimations()&&(a.support.animation=new String(f("animation")),a.support.animation.end=i.animation.end[a.support.animation]),j.csstransforms()&&(a.support.transform=new String(f("transform")),a.support.transform3d=j.csstransforms3d())}(window.Zepto||window.jQuery,window,document);--- ./javav2/usecases/workflow_multiple_channels/src/main/java/com/example/messages/SendNotifications.java	original
+++ ./javav2/usecases/workflow_multiple_channels/src/main/java/com/example/messages/SendNotifications.java	fixed
@@ -187 +187 @@
-            String subject = "School Attendence";
+            String subject = "School Attendance";
--- ./javav2/usecases/workflow_multiple_channels/src/main/java/com/example/messages/Student.java	original
+++ ./javav2/usecases/workflow_multiple_channels/src/main/java/com/example/messages/Student.java	fixed
@@ -13 +13 @@
-    private String phoneNunber;
+    private String phoneNumber;
@@ -15,2 +15,2 @@
-    public void setPhoneNunber(String phoneNunber) {
-        this.phoneNunber = phoneNunber;
+    public void setPhoneNumber(String phoneNumber) {
+        this.phoneNumber = phoneNumber;
@@ -19,2 +19,2 @@
-    public String getPhoneNunber() {
-        return this.phoneNunber;
+    public String getPhoneNumber() {
+        return this.phoneNumber;
--- ./javav2/usecases/workflow_multiple_channels/src/main/java/com/example/messages/RDSGetStudents.java	original
+++ ./javav2/usecases/workflow_multiple_channels/src/main/java/com/example/messages/RDSGetStudents.java	fixed
@@ -56 +56 @@
-                student.setPhoneNunber(phone);
+                student.setPhoneNumber(phone);
@@ -118 +118 @@
-                phone.appendChild( doc.createTextNode(myStudent.getPhoneNunber() ) );
+                phone.appendChild( doc.createTextNode(myStudent.getPhoneNumber() ) );
--- ./javav2/usecases/workflow_multiple_channels/Readme.md	original
+++ ./javav2/usecases/workflow_multiple_channels/Readme.md	fixed
@@ -561 +561 @@
-                student.setPhoneNunber(phone);
+                student.setPhoneNumber(phone);
@@ -623 +623 @@
-                phone.appendChild( doc.createTextNode(myStudent.getPhoneNunber() ) );
+                phone.appendChild( doc.createTextNode(myStudent.getPhoneNumber() ) );
@@ -873 +873 @@
-      private String phoneNunber;
+      private String phoneNumber;
@@ -875,2 +875,2 @@
-      public void setPhoneNunber(String phoneNunber) {
-        this.phoneNunber = phoneNunber;
+      public void setPhoneNumber(String phoneNumber) {
+        this.phoneNumber = phoneNumber;
@@ -879,2 +879,2 @@
-      public String getPhoneNunber() {
-        return this.phoneNunber;
+      public String getPhoneNumber() {
+        return this.phoneNumber;
--- ./javav2/usecases/creating_sns_async/Readme.md	original
+++ ./javav2/usecases/creating_sns_async/Readme.md	fixed
@@ -49 +49 @@
-The specified email address recieves an email message that lets the recipient confirm the subscription. 
+The specified email address receives an email message that lets the recipient confirm the subscription. 
@@ -53 +53 @@
-Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and recieves published messages. To publish a message, a user enters the message into the web applicaiton and then chooses the **Publish** button. 
+Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and receives published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
--- ./javav2/usecases/Creating_etl_workflow/Readme.md	original
+++ ./javav2/usecases/Creating_etl_workflow/Readme.md	fixed
@@ -63 +63 @@
-+ An Amazon S3 bucket that contains a Microsoft Excel document that contains poplation data. Create a Microsoft Excel document similiar to the previous illustration and put in example numbers for population data.  For information about creating an Amazon S3 bucket, see [Creating a bucket](https://docs.aws.amazon.com/AmazonS3/latest/userguide/create-bucket-overview.html).
++ An Amazon S3 bucket that contains a Microsoft Excel document that contains poplation data. Create a Microsoft Excel document similar to the previous illustration and put in example numbers for population data.  For information about creating an Amazon S3 bucket, see [Creating a bucket](https://docs.aws.amazon.com/AmazonS3/latest/userguide/create-bucket-overview.html).
@@ -345 +345 @@
-+ **Population** - Used as the data mapping class for the Amazon DynamoDB Java API (V2) Enchanced Client. 
++ **Population** - Used as the data mapping class for the Amazon DynamoDB Java API (V2) Enhanced Client. 
--- ./javav2/example_code/lookoutvision/src/main/java/com/example/lookoutvision/ShowAnomalies.java	original
+++ ./javav2/example_code/lookoutvision/src/main/java/com/example/lookoutvision/ShowAnomalies.java	fixed
@@ -170 +170 @@
-        //Calculate font size based on arbitary 32 pixel image width.
+        //Calculate font size based on arbitrary 32 pixel image width.
--- ./javav2/example_code/codepipeline/src/main/java/com/example/pipeline/CreatePipeline.java	original
+++ ./javav2/example_code/codepipeline/src/main/java/com/example/pipeline/CreatePipeline.java	fixed
@@ -46 +46 @@
-            "   <name> <roleArn> <s3Bucket> <s3OuputBucket>\n\n" +
+            "   <name> <roleArn> <s3Bucket> <s3OutputBucket>\n\n" +
@@ -51 +51 @@
-            "   s3OuputBucket - The name of the Amazon S3 bucket where the code is deployed.  \n\n";
+            "   s3OutputBucket - The name of the Amazon S3 bucket where the code is deployed.  \n\n";
@@ -61 +61 @@
-        String s3OuputBucket = args[3] ;
+        String s3OutputBucket = args[3] ;
@@ -68 +68 @@
-        createNewPipeline(pipelineClient, name, roleArn, s3Bucket, s3OuputBucket);
+        createNewPipeline(pipelineClient, name, roleArn, s3Bucket, s3OutputBucket);
@@ -73 +73 @@
-    public static void createNewPipeline(CodePipelineClient pipelineClient, String name, String roleArn, String s3Bucket, String s3OuputBucket) {
+    public static void createNewPipeline(CodePipelineClient pipelineClient, String name, String roleArn, String s3Bucket, String s3OutputBucket) {
@@ -104 +104 @@
-            mapConfig1.put("BucketName",s3OuputBucket);
+            mapConfig1.put("BucketName",s3OutputBucket);
--- ./javav2/example_code/stepfunctions/src/test/java/StepFunctionsTest.java	original
+++ ./javav2/example_code/stepfunctions/src/test/java/StepFunctionsTest.java	fixed
@@ -94 +94 @@
-        ListActivities.listAllActivites(sfnClient);
+        ListActivities.listAllActivities(sfnClient);
--- ./javav2/example_code/stepfunctions/src/main/java/com/example/stepfunctions/ListActivities.java	original
+++ ./javav2/example_code/stepfunctions/src/main/java/com/example/stepfunctions/ListActivities.java	fixed
@@ -40 +40 @@
-        listAllActivites(sfnClient);
+        listAllActivities(sfnClient);
@@ -45 +45 @@
-    public static void listAllActivites(SfnClient sfnClient) {
+    public static void listAllActivities(SfnClient sfnClient) {
--- ./javav2/example_code/stepfunctions/Readme.md	original
+++ ./javav2/example_code/stepfunctions/Readme.md	fixed
@@ -32 +32 @@
-- **jsonFile** - A JSON file that contains the values to pass to the worflow and used in the **StartExecution** test.
+- **jsonFile** - A JSON file that contains the values to pass to the workflow and used in the **StartExecution** test.
--- ./javav2/example_code/transcribe/src/main/java/com/amazonaws/transcribestreaming/TranscribeStreamingRetryClient.java	original
+++ ./javav2/example_code/transcribe/src/main/java/com/amazonaws/transcribestreaming/TranscribeStreamingRetryClient.java	fixed
@@ -129 +129 @@
-                log.debug("Error occured:", e);
+                log.debug("Error occurred:", e);
--- ./javav2/example_code/kms/src/test/java/AmazonKMSTest.java	original
+++ ./javav2/example_code/kms/src/test/java/AmazonKMSTest.java	fixed
@@ -131 +131 @@
-        DescribeKey.describeSpecifcKey(kmsClient, keyId);
+        DescribeKey.describeSpecificKey(kmsClient, keyId);
--- ./javav2/example_code/kms/src/main/java/com/example/kms/DescribeKey.java	original
+++ ./javav2/example_code/kms/src/main/java/com/example/kms/DescribeKey.java	fixed
@@ -51 +51 @@
-        describeSpecifcKey(kmsClient, keyId );
+        describeSpecificKey(kmsClient, keyId );
@@ -56 +56 @@
-    public static void describeSpecifcKey(KmsClient kmsClient,String keyId ){
+    public static void describeSpecificKey(KmsClient kmsClient,String keyId ){
--- ./javav2/example_code/s3/src/main/java/com/example/s3/DeleteMultiObjects.java	original
+++ ./javav2/example_code/s3/src/main/java/com/example/s3/DeleteMultiObjects.java	fixed
@@ -62 +62 @@
-        // Upload three sample objects to the specfied Amazon S3 bucket.
+        // Upload three sample objects to the specified Amazon S3 bucket.
--- ./javav2/example_code/personalize/src/main/resources/domain-dsg-config.properties	original
+++ ./javav2/example_code/personalize/src/main/resources/domain-dsg-config.properties	fixed
@@ -10 +10 @@
-newDatasetType = <Specify Interactions or Items or Users. You must at minium create an Interactions dataset>
+newDatasetType = <Specify Interactions or Items or Users. You must at minimum create an Interactions dataset>
--- ./javav2/example_code/sqs/src/main/java/com/example/sqs/SendReceiveMessages.java	original
+++ ./javav2/example_code/sqs/src/main/java/com/example/sqs/SendReceiveMessages.java	fixed
@@ -8 +8 @@
-// snippet-start:[sqs.java2.send_recieve_messages.complete]
+// snippet-start:[sqs.java2.send_receive_messages.complete]
@@ -23 +23 @@
-// snippet-start:[sqs.java2.send_recieve_messages.import]
+// snippet-start:[sqs.java2.send_receive_messages.import]
@@ -39 +39 @@
-// snippet-end:[sqs.java2.send_recieve_messages.import]
+// snippet-end:[sqs.java2.send_receive_messages.import]
@@ -41 +41 @@
-// snippet-start:[sqs.java2.send_recieve_messages.main]
+// snippet-start:[sqs.java2.send_receive_messages.main]
@@ -102,2 +102,2 @@
-// snippet-end:[sqs.java2.send_recieve_messages.main]
-// snippet-end:[sqs.java2.send_recieve_messages.complete]
+// snippet-end:[sqs.java2.send_receive_messages.main]
+// snippet-end:[sqs.java2.send_receive_messages.complete]
--- ./javav2/example_code/sqs/src/main/java/com/example/sqs/SendMessages.java	original
+++ ./javav2/example_code/sqs/src/main/java/com/example/sqs/SendMessages.java	fixed
@@ -12 +12 @@
-// snippet-start:[sqs.java2.send_recieve_messages.import]
+// snippet-start:[sqs.java2.send_receive_messages.import]
@@ -20 +20 @@
-// snippet-end:[sqs.java2.send_recieve_messages.import]
+// snippet-end:[sqs.java2.send_receive_messages.import]
@@ -55 +55 @@
-    // snippet-start:[sqs.java2.send_recieve_messages.main]
+    // snippet-start:[sqs.java2.send_receive_messages.main]
@@ -82 +82 @@
-    // snippet-end:[sqs.java2.send_recieve_messages.main]
+    // snippet-end:[sqs.java2.send_receive_messages.main]
--- ./javav2/example_code/guardduty/src/main/java/com/example/guardduty/ListDetectors.java	original
+++ ./javav2/example_code/guardduty/src/main/java/com/example/guardduty/ListDetectors.java	fixed
@@ -2 +2 @@
-// snippet-sourcedescription:[ListDetectors.java demonstrates how to List detector id valuess of all the existing Amazon GuardDuty detector resources.]
+// snippet-sourcedescription:[ListDetectors.java demonstrates how to List detector id values of all the existing Amazon GuardDuty detector resources.]
--- ./javav2/example_code/mediastore/src/main/java/com/example/mediastore/CreateContainer.java	original
+++ ./javav2/example_code/mediastore/src/main/java/com/example/mediastore/CreateContainer.java	fixed
@@ -66 +66 @@
-            // Wait unitl the container is in an active state.
+            // Wait until the container is in an active state.
--- ./javav2/example_code/pinpoint/src/main/java/com/example/pinpoint/ListSegments.java	original
+++ ./javav2/example_code/pinpoint/src/main/java/com/example/pinpoint/ListSegments.java	fixed
@@ -1 +1 @@
-//snippet-sourcedescription:[ListSegements.java demonstrates how to list segments in an application.]
+//snippet-sourcedescription:[ListSegments.java demonstrates how to list segments in an application.]
@@ -66 +66 @@
-                System.out.println("Segement " + segment.id() + " " + segment.name() + " " + segment.lastModifiedDate());
+                System.out.println("Segment " + segment.id() + " " + segment.name() + " " + segment.lastModifiedDate());
--- ./javav2/example_code/pinpoint/src/main/java/com/example/pinpoint/GetTemplateByName	original
+++ ./javav2/example_code/pinpoint/src/main/java/com/example/pinpoint/GetTemplateByName	fixed
@@ -14 +14 @@
-                .credentialsProvider(CredentialUtility.getCredentails())
+                .credentialsProvider(CredentialUtility.getCredentials())
--- ./javav2/example_code/pinpoint/src/main/java/com/example/pinpoint/ImportSegment.java	original
+++ ./javav2/example_code/pinpoint/src/main/java/com/example/pinpoint/ImportSegment.java	fixed
@@ -38 +38 @@
-            "  bucket - The name of the Amazon S3 bucket that contains the segment definitons.\n\n" +
+            "  bucket - The name of the Amazon S3 bucket that contains the segment definitions.\n\n" +
--- ./javav2/example_code/mq/src/test/java/AmazonMQTest.java	original
+++ ./javav2/example_code/mq/src/test/java/AmazonMQTest.java	fixed
@@ -79 +79 @@
-        String result = CreateConfiguration.createNewConfigutation(mqClient, configurationName);
+        String result = CreateConfiguration.createNewConfiguration(mqClient, configurationName);
--- ./javav2/example_code/mq/src/main/java/com/example/mq/CreateConfiguration.java	original
+++ ./javav2/example_code/mq/src/main/java/com/example/mq/CreateConfiguration.java	fixed
@@ -51 +51 @@
-        String result = createNewConfigutation(mqClient, configurationName);
+        String result = createNewConfiguration(mqClient, configurationName);
@@ -56 +56 @@
-    public static String createNewConfigutation(MqClient mqClient, String configurationName) {
+    public static String createNewConfiguration(MqClient mqClient, String configurationName) {
--- ./javav2/example_code/cloudfront/src/test/java/CloudFrontTest.java	original
+++ ./javav2/example_code/cloudfront/src/test/java/CloudFrontTest.java	fixed
@@ -87,2 +87,2 @@
-   public void GetDistrubutions() {
-        GetDistrubutions.getCFDistrubutions(cloudFrontClient);
+   public void GetDistributions() {
+        GetDistributions.getCFDistributions(cloudFrontClient);
--- ./javav2/example_code/cloudfront/src/main/java/com/example/cloudfront/GetDistrubutions.java	original
+++ ./javav2/example_code/cloudfront/src/main/java/com/example/cloudfront/GetDistributions.java	fixed
@@ -1 +1 @@
-//snippet-sourcedescription:[GetDistrubutions.java demonstrates how to get information about a distribution.]
+//snippet-sourcedescription:[GetDistributions.java demonstrates how to get information about a distribution.]
@@ -29 +29 @@
-public class GetDistrubutions {
+public class GetDistributions {
@@ -38 +38 @@
-        getCFDistrubutions(cloudFrontClient);
+        getCFDistributions(cloudFrontClient);
@@ -43 +43 @@
-     public static void getCFDistrubutions(CloudFrontClient cloudFrontClient) {
+     public static void getCFDistributions(CloudFrontClient cloudFrontClient) {
--- ./javav2/example_code/iam/Readme.md	original
+++ ./javav2/example_code/iam/Readme.md	fixed
@@ -36 +36 @@
-- [Performing various IAM operations](https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/javav2/example_code/iam/src/main/java/com/example/iam/IAMScenario.java) (Mulitple commands)
+- [Performing various IAM operations](https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/javav2/example_code/iam/src/main/java/com/example/iam/IAMScenario.java) (Multiple commands)
--- ./javav2/example_code/kinesis/src/test/java/KinesisServiceTest.java	original
+++ ./javav2/example_code/kinesis/src/test/java/KinesisServiceTest.java	fixed
@@ -107 +107 @@
-    public void DeleteDataStreem() {
+    public void DeleteDataStream() {
--- ./javav2/example_code/kinesis/src/main/java/com/example/kinesis/KinesisStreamEx.java	original
+++ ./javav2/example_code/kinesis/src/main/java/com/example/kinesis/KinesisStreamEx.java	fixed
@@ -153 +153 @@
-                System.out.println("Receieved initial response");
+                System.out.println("Received initial response");
--- ./javav2/example_code/sagemaker/src/main/java/com/example/sage/InvokeEndpoint.java	original
+++ ./javav2/example_code/sagemaker/src/main/java/com/example/sage/InvokeEndpoint.java	fixed
@@ -48 +48 @@
-        invokeSpecficEndpoint(runtimeClient, endpointName, payload, contentType) ;
+        invokeSpecificEndpoint(runtimeClient, endpointName, payload, contentType) ;
@@ -52 +52 @@
-    public static void invokeSpecficEndpoint(SageMakerRuntimeClient runtimeClient, String endpointName, String payload, String contentType) {
+    public static void invokeSpecificEndpoint(SageMakerRuntimeClient runtimeClient, String endpointName, String payload, String contentType) {
--- ./javav2/example_code/sns/src/main/java/com/example/sns/GetSMSAtrributes.java	original
+++ ./javav2/example_code/sns/src/main/java/com/example/sns/GetSMSAttributes.java	fixed
@@ -1 +1 @@
-//snippet-sourcedescription:[GetSMSAtrributes.java demonstrates how to retrieve the default SMS type for Amazon Simple Notification Service (Amazon SNS).]
+//snippet-sourcedescription:[GetSMSAttributes.java demonstrates how to retrieve the default SMS type for Amazon Simple Notification Service (Amazon SNS).]
@@ -12 +12 @@
-//snippet-start:[sns.java2.GetSMSAtrributes.import]
+//snippet-start:[sns.java2.GetSMSAttributes.import]
@@ -21 +21 @@
-//snippet-end:[sns.java2.GetSMSAtrributes.import]
+//snippet-end:[sns.java2.GetSMSAttributes.import]
@@ -30 +30 @@
-public class GetSMSAtrributes {
+public class GetSMSAttributes {
@@ -54 +54 @@
-    //snippet-start:[sns.java2.GetSMSAtrributes.main]
+    //snippet-start:[sns.java2.GetSMSAttributes.main]
@@ -80 +80 @@
-    //snippet-end:[sns.java2.GetSMSAtrributes.main]
+    //snippet-end:[sns.java2.GetSMSAttributes.main]
--- ./javav2/example_code/autoscale/src/main/java/com/example/autoscaling/AutoScalingScenario.java	original
+++ ./javav2/example_code/autoscale/src/main/java/com/example/autoscaling/AutoScalingScenario.java	fixed
@@ -148 +148 @@
-    // snippet-start:[autoscale.java2.describe_scaling_activites.main]
+    // snippet-start:[autoscale.java2.describe_scaling_activities.main]
@@ -168 +168 @@
-    // snippet-end:[autoscale.java2.describe_scaling_activites.main]
+    // snippet-end:[autoscale.java2.describe_scaling_activities.main]
--- ./javav2/example_code/cloudtrail/src/main/java/com/example/cloudtrail/GetTrailLoggingTime.java	original
+++ ./javav2/example_code/cloudtrail/src/main/java/com/example/cloudtrail/GetTrailLoggingTime.java	fixed
@@ -70 +70 @@
-            Instant lastestNotication = trailStatusResponse.startLoggingTime();
+            Instant latestNotification = trailStatusResponse.startLoggingTime();
@@ -72 +72 @@
-            if (lastestNotication != null) {
+            if (latestNotification != null) {
@@ -79,2 +79,2 @@
-                formatter.format(lastestNotication);
-                System.out.println("The date of the logging time is " + lastestNotication);
+                formatter.format(latestNotification);
+                System.out.println("The date of the logging time is " + latestNotification);
--- ./javav2/example_code/dynamodb/src/test/java/DynamoDBTest.java	original
+++ ./javav2/example_code/dynamodb/src/test/java/DynamoDBTest.java	fixed
@@ -182 +182 @@
-   public void SycnPagination(){
+   public void SyncPagination(){
--- ./javav2/example_code/dynamodb/src/main/java/com/example/dynamodb/PutItemEncrypt.java	original
+++ ./javav2/example_code/dynamodb/src/main/java/com/example/dynamodb/PutItemEncrypt.java	fixed
@@ -76 +76 @@
-        // Create a KmsClient object to use to encrpt data.
+        // Create a KmsClient object to use to encrypt data.
--- ./javav2/example_code/dynamodb/Readme.md	original
+++ ./javav2/example_code/dynamodb/Readme.md	fixed
@@ -41,2 +41,2 @@
-- [Quering items from an Amazon DynamoDB table by using the enhanced client](https://github.com/awsdocs/aws-doc-sdk-examples/blob/main/javav2/example_code/dynamodb/src/main/java/com/example/dynamodb/EnhancedQueryRecords.java) (Query command)
-- [Quering items from an Amazon DynamoDB table by using the enhanced client and a secondary index](https://github.com/awsdocs/aws-doc-sdk-examples/blob/main/javav2/example_code/dynamodb/src/main/java/com/example/dynamodb/EnhancedGetItemUsingIndex.java) (Query command)
+- [Querying items from an Amazon DynamoDB table by using the enhanced client](https://github.com/awsdocs/aws-doc-sdk-examples/blob/main/javav2/example_code/dynamodb/src/main/java/com/example/dynamodb/EnhancedQueryRecords.java) (Query command)
+- [Querying items from an Amazon DynamoDB table by using the enhanced client and a secondary index](https://github.com/awsdocs/aws-doc-sdk-examples/blob/main/javav2/example_code/dynamodb/src/main/java/com/example/dynamodb/EnhancedGetItemUsingIndex.java) (Query command)
--- ./go/s3/README.md	original
+++ ./go/s3/README.md	fixed
@@ -70 +70 @@
-- **-t** gets the object using a custom timout; otherwise, it uses a custom HTTP client.
+- **-t** gets the object using a custom timeout; otherwise, it uses a custom HTTP client.
--- ./go/sqs/README.md	original
+++ ./go/sqs/README.md	fixed
@@ -80 +80 @@
-### ChangeMsgVisibilty
+### ChangeMsgVisibility
--- ./go/iam/README.md	original
+++ ./go/iam/README.md	fixed
@@ -104 +104 @@
-- _CERT-NAME_ is the name of the cerificate.
+- _CERT-NAME_ is the name of the certificate.
@@ -160 +160 @@
-This example lists the accesss keys for a specific user.
+This example lists the access keys for a specific user.
--- ./go/rds/CopySnapshotToS3/CopySnapshotToS3.go	original
+++ ./go/rds/CopySnapshotToS3/CopySnapshotToS3.go	fixed
@@ -43,2 +43,2 @@
-    IndentifierSnapshotTime := currentTime.Format("20060102")
-    exportIdentifier := *exportRDSSnapshotName + IndentifierSnapshotTime
+    IdentifierSnapshotTime := currentTime.Format("20060102")
+    exportIdentifier := *exportRDSSnapshotName + IdentifierSnapshotTime
--- ./go/example_code/ec2/ec2_create_security_group.go	original
+++ ./go/example_code/ec2/ec2_create_security_group.go	fixed
@@ -117 +117 @@
-            // Can use setters to simplify seting multiple values without the
+            // Can use setters to simplify setting multiple values without the
--- ./go/example_code/iam/IamListAdmins.go	original
+++ ./go/example_code/iam/IamListAdmins.go	fixed
@@ -3 +3 @@
-// snippet-sourcedescription:[Lists the IAM users that have adminstrator privileges.]
+// snippet-sourcedescription:[Lists the IAM users that have administrator privileges.]
--- ./go/example_code/rds/rds_copy_snapshot_to_s3.go	original
+++ ./go/example_code/rds/rds_copy_snapshot_to_s3.go	fixed
@@ -6 +6 @@
-// snippet-keyword:[CopyDBSnaphotToS3 function]
+// snippet-keyword:[CopyDBSnapshotToS3 function]
@@ -65,2 +65,2 @@
-	IndentifierSanpshotTime := currentTime.Format("20060102")
-	exportIdentifier := exportRDSSnapshotName + IndentifierSanpshotTime
+	IdentifierSanpshotTime := currentTime.Format("20060102")
+	exportIdentifier := exportRDSSnapshotName + IdentifierSanpshotTime
--- ./rust_dev_preview/ses/src/bin/send-email.rs	original
+++ ./rust_dev_preview/ses/src/bin/send-email.rs	fixed
@@ -93 +93 @@
-/// * `-c CONTACT-LIST` - The contact list with the email addresses of the recepients.
+/// * `-c CONTACT-LIST` - The contact list with the email addresses of the recipients.
--- ./rust_dev_preview/s3/testfile.txt	original
+++ ./rust_dev_preview/s3/testfile.txt	fixed
@@ -1 +1 @@
-Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla dolor, varius vel vehicula vitae, dapibus id tellus. Vivamus nisl risus, pretium in nisi non, venenatis rhoncus ligula. Sed pharetra nibh nulla. Integer vitae mollis nisi. Nunc ante nulla, cursus id dolor sit amet, suscipit molestie est. Vestibulum sollicitudin fermentum arcu ut dictum. Sed finibus feugiat libero, sit amet fermentum ex consequat auctor. Donec varius fringilla sagittis. Sed gravida efficitur erat et viverra. Nulla malesuada metus vitae lacus malesuada, at faucibus velit tincidunt. Cras fermentum blandit purus. Integer rutrum semper lorem, rutrum aliquet elit egestas ac. Integer tincidunt sem nec turpis aliquet consectetur. Nunc accumsan est leo, ut tincidunt turpis interdum in. Ut finibus nibh et ullamcorper pharetra.
+Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla dolor, various vel vehicula vitae, dapibus id tellus. Vivamus nisl risus, pretium in nisi non, venenatis rhoncus ligula. Sed pharetra nibh nulla. Integer vitae mollis nisi. Nunc ante nulla, cursus id dolor sit amet, suscipit molestie est. Vestibulum sollicitudin fermentum arcu ut dictum. Sed finibus feugiat libero, sit amet fermentum ex consequat auctor. Donec various fringilla sagittis. Sed gravida efficitur erat et viverra. Nulla malesuada metus vitae lacus malesuada, at faucibus velit tincidunt. Cras fermentum blandit purus. Integer rutrum semper lorem, rutrum aliquet elit egestas ac. Integer tincidunt sem nec turpis aliquet consectetur. Nunc accumsan est leo, ut tincidunt turpis interdum in. Ut finibus nibh et ullamcorper pharetra.
@@ -3 +3 @@
-Duis sodales odio velit, nec ornare leo venenatis ut. Pellentesque in libero sit amet libero vestibulum lobortis. Vivamus laoreet ex eget mi suscipit, vitae volutpat felis iaculis. Etiam rhoncus ac arcu nec commodo. Phasellus posuere, mi eget egestas tincidunt, orci tellus placerat turpis, sit amet blandit nibh magna eu est. Nunc ultrices tincidunt rhoncus. Praesent faucibus id augue quis laoreet. Maecenas ac pellentesque eros, id pellentesque magna. Integer faucibus auctor ante. Mauris vitae pharetra erat. Nulla facilisi. Fusce ac ex libero. Duis posuere lacus lectus, ut varius sapien efficitur eget. Nunc enim urna, congue non tristique id, consequat eget nisi. Nulla in massa sit amet nisi rhoncus tempor sagittis id erat.
+Duis sodales odio velit, nec ornare leo venenatis ut. Pellentesque in libero sit amet libero vestibulum lobortis. Vivamus laoreet ex eget mi suscipit, vitae volutpat felis iaculis. Etiam rhoncus ac arcu nec commodo. Phasellus posuere, mi eget egestas tincidunt, orci tellus placerat turpis, sit amet blandit nibh magna eu est. Nunc ultrices tincidunt rhoncus. Praesent faucibus id augue quis laoreet. Maecenas ac pellentesque eros, id pellentesque magna. Integer faucibus auctor ante. Mauris vitae pharetra erat. Nulla facilities. Fusce ac ex libero. Duis posuere lacus lectus, ut various sapien efficitur eget. Nunc enim urna, congue non tristique id, consequat eget nisi. Nulla in massa sit amet nisi rhoncus tempor sagittis id erat.
--- ./rust_dev_preview/ca-certs/src/main.rs	original
+++ ./rust_dev_preview/ca-certs/src/main.rs	fixed
@@ -33 +33 @@
-    // however, for generated clients, they are constructred from a Hyper adapter directly:
+    // however, for generated clients, they are constructed from a Hyper adapter directly:
--- ./rust_dev_preview/cognitoidentity/src/bin/describe-identity-pool.rs	original
+++ ./rust_dev_preview/cognitoidentity/src/bin/describe-identity-pool.rs	fixed
@@ -97 +97 @@
-/// Displays some information about an Amazon Cognito identitiy pool.
+/// Displays some information about an Amazon Cognito identity pool.
--- ./rust_dev_preview/eks/README.md	original
+++ ./rust_dev_preview/eks/README.md	fixed
@@ -43 +43 @@
-  There must be at least two subnet IDs, and each must be in a separate Availabiliy Zone (AZ).
+  There must be at least two subnet IDs, and each must be in a separate Availability Zone (AZ).
--- ./rust_dev_preview/ssm/src/bin/create-parameter.rs	original
+++ ./rust_dev_preview/ssm/src/bin/create-parameter.rs	fixed
@@ -92,2 +92,2 @@
-        println!("Paramter value:       {}", &parameter_value);
-        println!("Paramter description: {}", &title);
+        println!("Parameter value:       {}", &parameter_value);
+        println!("Parameter description: {}", &title);
--- ./rust_dev_preview/polly/src/bin/describe-voices.rs	original
+++ ./rust_dev_preview/polly/src/bin/describe-voices.rs	fixed
@@ -16 +16 @@
-    /// Whether to isplay additional information.
+    /// Whether to display additional information.
--- ./java/example_code/s3/src/main/java/aws/example/s3/S3Encrypt.java	original
+++ ./java/example_code/s3/src/main/java/aws/example/s3/S3Encrypt.java	fixed
@@ -230,3 +230,3 @@
-    // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymetric_key]
-    public void encryptionOnly_CustomerManagedAsymetricKey() throws NoSuchAlgorithmException {
-        // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymetric_key_build]
+    // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymmetric_key]
+    public void encryptionOnly_CustomerManagedAsymmetricKey() throws NoSuchAlgorithmException {
+        // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymmetric_key_build]
@@ -242 +242 @@
-        // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymetric_key_build]
+        // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymmetric_key_build]
@@ -244 +244 @@
-        // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymetric_key_put_object]
+        // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymmetric_key_put_object]
@@ -247,2 +247,2 @@
-        // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymetric_key_put_object]
-        // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymetric_key_retrieve]
+        // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymmetric_key_put_object]
+        // snippet-start:[s3.java1.s3_encrypt.encryption_only_asymmetric_key_retrieve]
@@ -251 +251 @@
-        // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymetric_key_retrieve]
+        // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymmetric_key_retrieve]
@@ -253 +253 @@
-    // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymetric_key]
+    // snippet-end:[s3.java1.s3_encrypt.encryption_only_asymmetric_key]
--- ./java/example_code/polly/SpeechMarks.java	original
+++ ./java/example_code/polly/SpeechMarks.java	fixed
@@ -15 +15 @@
-// snippet-sourcedescription:[SpeechMarks demonstrates how to synthesize speech marks for inputed text.]
+// snippet-sourcedescription:[SpeechMarks demonstrates how to synthesize speech marks for inputted text.]
--- ./gov2/cross_service/wordfreq/example_content/gutenberg2.txt	original
+++ ./gov2/cross_service/wordfreq/example_content/gutenberg2.txt	fixed
@@ -111 +111 @@
-drawing upon metalic plates is concerned--to the methods practised by
+drawing upon metallic plates is concerned--to the methods practised by
@@ -347 +347 @@
-negociations with the French government which were concluded most
+negotiations with the French government which were concluded most
@@ -376 +376 @@
-doubt of the Calotype, in their hands, entirely superceding the
+doubt of the Calotype, in their hands, entirely superseding the
@@ -393,12 +393,12 @@
-"The process was a secret, and negociations were then in progress, for
-the disclosure of it to the public between the French government and
-the distinguished discoverer.  M. Daguerre had shown his results to the
-king, and to a few only of the distinguished savans, and by the advice
-of M. Arago, had determined to wait the action of the French Chambers,
-before showing them to any other persons.  I was exceedingly desirous
-of seeing them, but knew not how to approach M. Daguerre who was a
-stranger to me.  On mentioning my desire to Robert Walsh, Esq., our
-worthy Consul, he said to me; 'state that you are an American, the
-inventor of the Telegraph, request to see them, and invite him in turn
-to see the Telegraph, and I know enough of the urbanity and liberal
-feelings of the French, to insure you an invitation.' I was successfull
+"The process was a secret, and negotiations were then in progress, for
+the disclosure of it to the public between the French government and
+the distinguished discoverer.  M. Daguerre had shown his results to the
+king, and to a few only of the distinguished savans, and by the advice
+of M. Arago, had determined to wait the action of the French Chambers,
+before showing them to any other persons.  I was exceedingly desirous
+of seeing them, but knew not how to approach M. Daguerre who was a
+stranger to me.  On mentioning my desire to Robert Walsh, Esq., our
+worthy Consul, he said to me; 'state that you are an American, the
+inventor of the Telegraph, request to see them, and invite him in turn
+to see the Telegraph, and I know enough of the urbanity and liberal
+feelings of the French, to insure you an invitation.' I was successful
@@ -520 +520 @@
-percieved the effect, in the gradual darkening of various parts of the
+perceived the effect, in the gradual darkening of various parts of the
@@ -646 +646 @@
-manner hide the light from d--Now, if b recieve as much light as would
+manner hide the light from d--Now, if b receive as much light as would
@@ -683 +683 @@
-mirror, were it not first coated on one side with a metalic amalgam,
+mirror, were it not first coated on one side with a metallic amalgam,
@@ -858 +858 @@
-summer, with the most sensative process, it not unfrequently happens
+summer, with the most sensitive process, it not unfrequently happens
@@ -895 +895 @@
-of platinum, which readily recieves a photogenic image by darkening
+of platinum, which readily receives a photogenic image by darkening
@@ -1029 +1029 @@
-metalic silver is seen to be revived on the surface of the salt.  Great
+metallic silver is seen to be revived on the surface of the salt.  Great
@@ -1106 +1106 @@
-very loose state of chemical agregation; the attractive forces increase
+very loose state of chemical aggregation; the attractive forces increase
@@ -1181 +1181 @@
-this stage, will gradually darken and eventually develope the picture.
+this stage, will gradually darken and eventually develop the picture.
@@ -1194 +1194 @@
-Here I must leave the subject of the action of light upon metalic
+Here I must leave the subject of the action of light upon metallic
@@ -1221 +1221 @@
-brown impression begins to be percieved in the midst of the white
+brown impression begins to be perceived in the midst of the white
@@ -1229 +1229 @@
-photographs.--  Future experiments will undoubtedly more fully develope
+photographs.--  Future experiments will undoubtedly more fully develop
@@ -1267 +1267 @@
-Photographic art, either on paper, or metalic plates--but, like all
+Photographic art, either on paper, or metallic plates--but, like all
@@ -1297 +1297 @@
-is to be prefered; but if you must cover it use matting.  There is no
+is to be preferred; but if you must cover it use matting.  There is no
@@ -1354 +1354 @@
-employed.  Any metalic mounting on the brushes should be avoided, as
+employed.  Any metallic mounting on the brushes should be avoided, as
@@ -1448 +1448 @@
-alway come with Voitlander instruments and should be secured by the
+always come with Voitlander instruments and should be secured by the
@@ -1461 +1461 @@
-Son of Germany.  Their small size consists of two seperate acromatic
+Son of Germany.  Their small size consists of two separate acromatic
@@ -1553 +1553 @@
-one side to receive the thermometre tube and scale by which the proper
+one side to receive the thermometer tube and scale by which the proper
@@ -1599,8 +1599,8 @@
-embeded within it a stout glass jar (c), the edges of which are ground.
-Over this is placed the sliding cover b, double the length of the box,
-one half occupied by a piece of ground glass (e), tightly pressed upon
-the glass pot by a spring (i) beneath the cross bar g, and fits the pot
-so accurately that it effectually prevents the escape of the vapor of
-the iodine, bromine or other accelerating liquid contained therein.
-The other half of the lid is cut through, shoulders being left at the
-four angles for the different sizes of frames, designed to recieve the
+embedded within it a stout glass jar (c), the edges of which are ground.
+Over this is placed the sliding cover b, double the length of the box,
+one half occupied by a piece of ground glass (e), tightly pressed upon
+the glass pot by a spring (i) beneath the cross bar g, and fits the pot
+so accurately that it effectually prevents the escape of the vapor of
+the iodine, bromine or other accelerating liquid contained therein.
+The other half of the lid is cut through, shoulders being left at the
+four angles for the different sizes of frames, designed to receive the
@@ -1673 +1673 @@
-It consists of two thermometre tubes placed, side by side, on a metalic
+It consists of two thermometer tubes placed, side by side, on a metallic
@@ -1737,2 +1737,2 @@
-should be no action percieved upon them when the poles F, G, are not in
-contact.  Should any action be percieved, it indicates imperfect
+should be no action perceived upon them when the poles F, G, are not in
+contact.  Should any action be perceived, it indicates imperfect
@@ -1749 +1749 @@
-half an inch from it.  A slight effervescence will now be percieved
+half an inch from it.  A slight effervescence will now be perceived
@@ -1868 +1868 @@
-the plate.  Even the back should not be neglected, but throughly
+the plate.  Even the back should not be neglected, but thoroughly
@@ -1890 +1890 @@
-plate recieves its final polish; the circular motion is changed for a
+plate receives its final polish; the circular motion is changed for a
@@ -1909 +1909 @@
-SECOND OPERATION.--Applying the sensative coating.--The apparatus and
+SECOND OPERATION.--Applying the sensitive coating.--The apparatus and
@@ -2013 +2013 @@
-Roach's Tripple Compound.--This is one of the very best sensitive
+Roach's Triple Compound.--This is one of the very best sensitive
@@ -2437,7 +2437,7 @@
-moment the mercury vaporizes, the picture will begin to develope
-itself.  The spirit lamp must now be removed for a short time, and when
-the action of the mercury appears to cease, it is to be very carefully
-applied again, until a well defined picture is visible.  The
-vaporization must then be suddenly stopped, and the photograph removed
-from the box.  The drawing will then be very beautiful and distinct;
-but much detail is still clouded, for the developement of which it is
+moment the mercury vaporizes, the picture will begin to develop
+itself.  The spirit lamp must now be removed for a short time, and when
+the action of the mercury appears to cease, it is to be very carefully
+applied again, until a well defined picture is visible.  The
+vaporization must then be suddenly stopped, and the photograph removed
+from the box.  The drawing will then be very beautiful and distinct;
+but much detail is still clouded, for the development of which it is
@@ -2592,5 +2592,5 @@
-paper must be used.  If these be kept seperate and marked, they can be
-again employed for the same stage; but it would not do, for example, to
-dry the finished picture in the same folds in which the sensitive paper
-had been pressed.  A very convenient method is to have two or three
-quarto size books of bibulous paper, one for each seperate process.
+paper must be used.  If these be kept separate and marked, they can be
+again employed for the same stage; but it would not do, for example, to
+dry the finished picture in the same folds in which the sensitive paper
+had been pressed.  A very convenient method is to have two or three
+quarto size books of bibulous paper, one for each separate process.
@@ -2832 +2832 @@
-Camels' or Badgers' hair Brushes:--A seperate one being kept for each
+Camels' or Badgers' hair Brushes:--A separate one being kept for each
@@ -3088 +3088 @@
-paper, and the words are formed by fixing the seperate letters in their
+paper, and the words are formed by fixing the separate letters in their
@@ -3161 +3161 @@
-pictures are produced capable of developement by the breath, or by
+pictures are produced capable of development by the breath, or by
@@ -3183 +3183 @@
-comes on, an invisible impression is the result, to develope which all
+comes on, an invisible impression is the result, to develop which all
@@ -3986 +3986 @@
-     Roach's Tripple Compound of  67
+     Roach's Triple Compound of  67
@@ -4121 +4121 @@
-  Roach's Tripple Compound of Bromine.  67
+  Roach's Triple Compound of Bromine.  67
@@ -4393 +4393 @@
-WARRANTIES OF MERCHANTIBILITY OR FITNESS FOR ANY PURPOSE.
+WARRANTIES OF MERCHANTABILITY OR FITNESS FOR ANY PURPOSE.
--- ./gov2/cross_service/wordfreq/wordfreq/cmd/worker/main.go	original
+++ ./gov2/cross_service/wordfreq/wordfreq/cmd/worker/main.go	fixed
@@ -209 +209 @@
-				result.StatusMessage = "Failed to retreive bucket data"
+				result.StatusMessage = "Failed to retrieve bucket data"
--- ./gov2/cross_service/wordfreq/README.md	original
+++ ./gov2/cross_service/wordfreq/README.md	fixed
@@ -28 +28 @@
-* Push the locally built Docker container to a private Amazon Elastic COntainer Registry (AWS ECR) registry
+* Push the locally built Docker container to a private Amazon Elastic CContainer Registry (AWS ECR) registry
--- ./gov2/testtools/awsm_stubber.go	original
+++ ./gov2/testtools/awsm_stubber.go	fixed
@@ -134 +134 @@
-	serOut := middleware.SerializeOutput{}
+	setOut := middleware.SerializeOutput{}
@@ -152 +152 @@
-			serOut.Result = stub.Output
+			setOut.Result = stub.Output
@@ -155 +155 @@
-	return serOut, metadata, err
+	return setOut, metadata, err
--- ./cpp/example_code/s3/gtests/gtest_list_buckets_disabling_dns_cache.cpp	original
+++ ./cpp/example_code/s3/gtests/gtest_list_buckets_disabling_dns_cache.cpp	fixed
@@ -14 +14 @@
-    TEST_F(S3_GTests, list_buckets_diabling_dns_cache) {
+    TEST_F(S3_GTests, list_buckets_disabling_dns_cache) {
--- ./cpp/example_code/acm/acm_basic_operations.cpp	original
+++ ./cpp/example_code/acm/acm_basic_operations.cpp	fixed
@@ -530,2 +530,2 @@
-            case Aws::ACM::Model::RevocationReason::SUPERCEDED:
-                reason = "Superceded";
+            case Aws::ACM::Model::RevocationReason::SUPERSEDED:
+                reason = "Superseded";
--- ./cpp/example_code/lambda/lambda_example.cpp	original
+++ ./cpp/example_code/lambda/lambda_example.cpp	fixed
@@ -1 +1 @@
-//snippet-sourcedescription:[lambda_example.cpp demonstrates how to programatically create, invoke, and manage an AWS Lambda function.]
+//snippet-sourcedescription:[lambda_example.cpp demonstrates how to programmatically create, invoke, and manage an AWS Lambda function.]
--- ./cpp/example_code/dynamodb/query_items.cpp	original
+++ ./cpp/example_code/dynamodb/query_items.cpp	fixed
@@ -1 +1 @@
-//snippet-sourcedescription:[query_items.cpp demonstrates how to perfrom Query operation and retrieve items from an Amazon DynamoDB table.]
+//snippet-sourcedescription:[query_items.cpp demonstrates how to perform Query operation and retrieve items from an Amazon DynamoDB table.]
--- ./cpp/example_code/dynamodb/create_table.cpp	original
+++ ./cpp/example_code/dynamodb/create_table.cpp	fixed
@@ -68,4 +68,4 @@
-        Aws::DynamoDB::Model::AttributeDefinition haskKey;
-        haskKey.SetAttributeName("Name");
-        haskKey.SetAttributeType(Aws::DynamoDB::Model::ScalarAttributeType::S);
-        req.AddAttributeDefinitions(haskKey);
+        Aws::DynamoDB::Model::AttributeDefinition hashKey;
+        hashKey.SetAttributeName("Name");
+        hashKey.SetAttributeType(Aws::DynamoDB::Model::ScalarAttributeType::S);
+        req.AddAttributeDefinitions(hashKey);
--- ./cpp/example_code/dynamodb/dynamodb_getting_started_scenario.cpp	original
+++ ./cpp/example_code/dynamodb/dynamodb_getting_started_scenario.cpp	fixed
@@ -273,4 +273,4 @@
-        std::shared_ptr<Aws::DynamoDB::Model::AttributeValue> plotAttibute = Aws::MakeShared<Aws::DynamoDB::Model::AttributeValue>(
-                ALLOCATION_TAG.c_str());
-        plotAttibute->SetS(plot);
-        infoMapAttribute.AddMEntry(PLOT_KEY, plotAttibute);
+        std::shared_ptr<Aws::DynamoDB::Model::AttributeValue> plotAttribute = Aws::MakeShared<Aws::DynamoDB::Model::AttributeValue>(
+                ALLOCATION_TAG.c_str());
+        plotAttribute->SetS(plot);
+        infoMapAttribute.AddMEntry(PLOT_KEY, plotAttribute);
--- ./cpp/example_code/dynamodb/describe_table.cpp	original
+++ ./cpp/example_code/dynamodb/describe_table.cpp	fixed
@@ -72 +72 @@
-            const Aws::DynamoDB::Model::ProvisionedThroughputDescription& ptd = td.GetProvisionedThroughput();
+            const Aws::DynamoDB::Model::ProvisionedThroughputDescription& pdf = td.GetProvisionedThroughput();
@@ -74,2 +74,2 @@
-            std::cout << "  Read Capacity : " << ptd.GetReadCapacityUnits() << std::endl;
-            std::cout << "  Write Capacity: " << ptd.GetWriteCapacityUnits() << std::endl;
+            std::cout << "  Read Capacity : " << pdf.GetReadCapacityUnits() << std::endl;
+            std::cout << "  Write Capacity: " << pdf.GetWriteCapacityUnits() << std::endl;
--- ./tools/cdk_app_template/setup.ts	original
+++ ./tools/cdk_app_template/setup.ts	fixed
@@ -89 +89 @@
-    //    This diplays:
+    //    This displays:
--- ./javascriptv3/example_code/ses/src/ses_listidentities.js	original
+++ ./javascriptv3/example_code/ses/src/ses_listidentities.js	fixed
@@ -22 +22 @@
-  const listIdentitiesCommmand = createListIdentitiesCommand();
+  const listIdentitiesCommand = createListIdentitiesCommand();
@@ -25 +25 @@
-    return await sesClient.send(listIdentitiesCommmand);
+    return await sesClient.send(listIdentitiesCommand);
--- ./javascriptv3/example_code/mediaconvert/src/emc_getendpoint.js	original
+++ ./javascriptv3/example_code/mediaconvert/src/emc_getendpoint.js	fixed
@@ -17 +17 @@
-// snippet-start:[mediaconvert.JavaScript.endoint.describeEndpointsV3]
+// snippet-start:[mediaconvert.JavaScript.endpoint.describeEndpointsV3]
@@ -36 +36 @@
-// snippet-end:[mediaconvert.JavaScript.endoint.describeEndpointsV3]
+// snippet-end:[mediaconvert.JavaScript.endpoint.describeEndpointsV3]
--- ./javascriptv3/example_code/s3/src/s3_multipartupload.js	original
+++ ./javascriptv3/example_code/s3/src/s3_multipartupload.js	fixed
@@ -41 +41 @@
-    // Create the mutlipart upload.
+    // Create the multipart upload.
@@ -81 +81 @@
-    // Complete the mutlipart upload.
+    // Complete the multipart upload.
--- ./javascriptv3/example_code/codecommit/README.md	original
+++ ./javascriptv3/example_code/codecommit/README.md	fixed
@@ -14,2 +14,2 @@
-- [Get informtion about a pull request](src/getPullRequest.js)
-- [Get informatino about a repository](src/getRepository.js)
+- [Get information about a pull request](src/getPullRequest.js)
+- [Get information about a repository](src/getRepository.js)
--- ./javascriptv3/example_code/personalize/src/personalize_createDomainSchema.js	original
+++ ./javascriptv3/example_code/personalize/src/personalize_createDomainSchema.js	fixed
@@ -17 +17 @@
-node createDomanSchema.js
+node createDomainSchema.js
--- ./javascriptv3/example_code/cross-services/sns-sample-app/Readme.md	original
+++ ./javascriptv3/example_code/cross-services/sns-sample-app/Readme.md	fixed
@@ -13 +13 @@
-The specified email address recieves an email message that lets the recipient confirm the subscription. 
+The specified email address receives an email message that lets the recipient confirm the subscription. 
@@ -17 +17 @@
-Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and recieves published messages. To publish a message, a user enters the message into the web applicaiton and then chooses the **Publish** button. 
+Once the email recipient accepts the confirmation, that email is subscribed to the specific SNS topic and receives published messages. To publish a message, a user enters the message into the web application and then chooses the **Publish** button. 
@@ -147 +147 @@
-It also loads **stlyes.css**, which applies styles to the HTML,
+It also loads **styles.css**, which applies styles to the HTML,
--- ./javascriptv3/example_code/cross-services/photo_analyzer/js/index.js	original
+++ ./javascriptv3/example_code/cross-services/photo_analyzer/js/index.js	fixed
@@ -109 +109 @@
-    // Loop through images. For each image, retreive the image name,
+    // Loop through images. For each image, retrieve the image name,
@@ -153 +153 @@
-  var csv = "Object, Confidance \n";
+  var csv = "Object, Confidence \n";
--- ./javascriptv3/example_code/cross-services/photo_analyzer/Readme.md	original
+++ ./javascriptv3/example_code/cross-services/photo_analyzer/Readme.md	fixed
@@ -20 +20 @@
-seperate Amazon S3 bucket, breaking the image down into a series of labels. In addition, this application uses Amazon Simple Email Service (Amazon SES)
+separate Amazon S3 bucket, breaking the image down into a series of labels. In addition, this application uses Amazon Simple Email Service (Amazon SES)
@@ -165 +165 @@
-It also loads **stlyes.css**, which applies styles to the HTML,
+It also loads **styles.css**, which applies styles to the HTML,
@@ -341 +341 @@
-uploading the report to the Amazon S3 bucket (*uploadFile*), and sending the specified recepient email notification about each image (*sendEmail*).
+uploading the report to the Amazon S3 bucket (*uploadFile*), and sending the specified recipient email notification about each image (*sendEmail*).
@@ -374 +374 @@
-    // Loop through images. For each image, retreive the image name,
+    // Loop through images. For each image, retrieve the image name,
@@ -419 +419 @@
-  var csv = "Object, Confidance \n";
+  var csv = "Object, Confidence \n";
--- ./javascriptv3/example_code/cross-services/video-analyzer/src/js/index.js	original
+++ ./javascriptv3/example_code/cross-services/video-analyzer/src/js/index.js	fixed
@@ -175 +175 @@
-  var csv = "Bounding Box, , , , Confidance, Pose, , ,  Quality, ,\n";
+  var csv = "Bounding Box, , , , Confidence, Pose, , ,  Quality, ,\n";
--- ./javascriptv3/example_code/cross-services/video-analyzer/README.md	original
+++ ./javascriptv3/example_code/cross-services/video-analyzer/README.md	fixed
@@ -422 +422 @@
-  var csv = "Bounding Box, , , , Confidance, Pose, , ,  Quality, ,\n";
+  var csv = "Bounding Box, , , , Confidence, Pose, , ,  Quality, ,\n";
--- ./javascriptv3/example_code/cross-services/lex-bot/src/index.html	original
+++ ./javascriptv3/example_code/cross-services/lex-bot/src/index.html	fixed
@@ -27 +27 @@
-<input type="text" id="wisdom" size="80" value="" placeholder="J'ai besoin d'une chambre d'hôtel">
+<input type="text" id="wisdom" size="80" value="" placeholder="J'ai besoin d'une chamber d'hôtel">
--- ./javascriptv3/example_code/cross-services/transcribe-streaming-app/src/index.html	original
+++ ./javascriptv3/example_code/cross-services/transcribe-streaming-app/src/index.html	fixed
@@ -36 +36 @@
-        <option value = "pt-BR">Portugese (Brazilian)</option>
+        <option value = "pt-BR">Portuguese (Brazilian)</option>
--- ./javascriptv3/example_code/cross-services/lambda-step-functions/src/lambda3/sendemail.js	original
+++ ./javascriptv3/example_code/cross-services/lambda-step-functions/src/lambda3/sendemail.js	fixed
@@ -26 +26 @@
-  const recepient = event.S;
+  const recipient = event.S;
@@ -43 +43 @@
-      ToAddresses: [recepient],
+      ToAddresses: [recipient],
--- ./javascriptv3/example_code/cross-services/ddb-item-tracker/README.md	original
+++ ./javascriptv3/example_code/cross-services/ddb-item-tracker/README.md	fixed
@@ -510,3 +510,3 @@
-  AWS Region, and **IDENTITY_POOL_ID** with the Amazon Cognito Idenfity Pool Id you created in [Create the resources](#create-the-resources).
-- **sesClient.js** - creates a client for Amazon SES. Update **REGION** to your
-  AWS Region, and **IDENTITY_POOL_ID** with the Amazon Cognito Idenfity Pool Id you created in [Create the resources](#create-the-resources).
+  AWS Region, and **IDENTITY_POOL_ID** with the Amazon Cognito Identify Pool Id you created in [Create the resources](#create-the-resources).
+- **sesClient.js** - creates a client for Amazon SES. Update **REGION** to your
+  AWS Region, and **IDENTITY_POOL_ID** with the Amazon Cognito Identify Pool Id you created in [Create the resources](#create-the-resources).
--- ./javascriptv3/example_code/codebuild/src/createProject.js	original
+++ ./javascriptv3/example_code/codebuild/src/createProject.js	fixed
@@ -19 +19 @@
-Note: This sample specifies the mimimum parameters required, and depending on your choices, alternative parameters may be required.
+Note: This sample specifies the minimum parameters required, and depending on your choices, alternative parameters may be required.
--- ./javascriptv3/example_code/reactnative/test.js	original
+++ ./javascriptv3/example_code/reactnative/test.js	fixed
@@ -67 +67 @@
-          backroundColor="#68a0cf"
+          backgroundColor="#68a0cf"
@@ -72 +72 @@
-          backroundColor="#68a0cf"
+          backgroundColor="#68a0cf"
--- ./javascriptv3/example_code/reactnative/README.rst	original
+++ ./javascriptv3/example_code/reactnative/README.rst	fixed
@@ -4 +4 @@
-1. Make sure npm and node is intalled.
+1. Make sure npm and node is installed.
@@ -11 +11 @@
-2. Change :code:`region` and :code:`indentityPoolId` in :code:`App.js` according to comment.
+2. Change :code:`region` and :code:`identityPoolId` in :code:`App.js` according to comment.
@@ -30 +30 @@
-1. Actually we can install all packages of lastest version except for :code:`react-native-get-random-values`. Version :code:`@1.7.0` have issues when connecting with Native Modules so I change it to :code:`@1.6.0`. 
+1. Actually we can install all packages of latest version except for :code:`react-native-get-random-values`. Version :code:`@1.7.0` have issues when connecting with Native Modules so I change it to :code:`@1.6.0`. 
--- ./javascriptv3/example_code/reactnative/App.js	original
+++ ./javascriptv3/example_code/reactnative/App.js	fixed
@@ -88 +88 @@
-          backroundColor="#68a0cf"
+          backgroundColor="#68a0cf"
@@ -93 +93 @@
-          backroundColor="#68a0cf"
+          backgroundColor="#68a0cf"
--- ./javascriptv3/example_code/polly/src/polly.html	original
+++ ./javascriptv3/example_code/polly/src/polly.html	fixed
@@ -4 +4 @@
-polly.html is the front-end code for an exmaple demonstrating how to get started using the AWS SDK for
+polly.html is the front-end code for an example demonstrating how to get started using the AWS SDK for
--- ./resources/sample_files/movies.json	original
+++ ./resources/sample_files/movies.json	fixed
@@ -1766 +1766 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -5514 +5514 @@
-                "JJ Feild",
+                "JJ Field",
@@ -5959 +5959 @@
-        "title": "Jack Reacher",
+        "title": "Jack Richer",
@@ -7544 +7544 @@
-        "title": "Lo imposible",
+        "title": "Lo impossible",
@@ -8487 +8487 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -8592 +8592 @@
-            "plot": "A newly engaged couple have a breakdown in an isolated area and must pay a call to the bizarre residence of Dr. Frank-N-Furter.",
+            "plot": "A newly engaged couple have a breakdown in an isolated area and must pay a call to the bizarre residence of Dr. Frank-N-Further.",
@@ -8955 +8955 @@
-            "plot": "The story of Olympic Wrestling Champion Mark Schultz and how paranoid schizophrenic John duPont killed his brother, Olympic Champion Dave Schultz.",
+            "plot": "The story of Olympic Wrestling Champion Mark Schultz and how paranoid schizophrenic John duPoint killed his brother, Olympic Champion Dave Schultz.",
@@ -10791 +10791 @@
-                "Sylvia Hoeks"
+                "Sylvia Hoax"
@@ -11445 +11445 @@
-                "Denis Leary",
+                "Denis Leery",
@@ -12777 +12777 @@
-                "John Doman"
+                "John Domain"
@@ -15365 +15365 @@
-                "Joseph Cotten",
+                "Joseph Cotton",
@@ -16430 +16430 @@
-                "Liana Liberato"
+                "Liana Liberation"
@@ -16917 +16917 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -19234 +19234 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -21296 +21296 @@
-        "title": "Man som hatar kvinnor",
+        "title": "Man some hatar kvinnor",
@@ -23027 +23027 @@
-                "Clea DuVall"
+                "Clean DuVall"
@@ -24293 +24293 @@
-            "plot": "Frank Martin puts the driving gloves on to deliver Valentina, the kidnapped daughter of a Ukranian government official, from Marseilles to Odessa on the Black Sea. En route, he has to contend with thugs who want to intercept Valentina's safe delivery and not let his personal feelings get in the way of his dangerous objective.",
+            "plot": "Frank Martin puts the driving gloves on to deliver Valentina, the kidnapped daughter of a Ukrainian government official, from Marseilles to Odessa on the Black Sea. En route, he has to contend with thugs who want to intercept Valentina's safe delivery and not let his personal feelings get in the way of his dangerous objective.",
@@ -26878 +26878 @@
-                "Denis Leary",
+                "Denis Leery",
@@ -27100 +27100 @@
-                "Ned Beatty"
+                "Need Beatty"
@@ -28441 +28441 @@
-            "plot": "Students suspect that their teachers are aliens after bizarre occurances.",
+            "plot": "Students suspect that their teachers are aliens after bizarre occurrences.",
@@ -28446 +28446 @@
-                "Clea DuVall",
+                "Clean DuVall",
@@ -28854 +28854 @@
-            "plot": "The Turtles and the Shredder battle once again, this time for the last cannister of the ooze that created the Turtles, which Shredder wants to create an army of new mutants.",
+            "plot": "The Turtles and the Shredder battle once again, this time for the last canister of the ooze that created the Turtles, which Shredder wants to create an army of new mutants.",
@@ -29960 +29960 @@
-            "plot": "A boy inadvertantly breaks 3 important rules concerning his new pet and unleashes a horde of malevolently mischievous monsters on a small town.",
+            "plot": "A boy inadvertently breaks 3 important rules concerning his new pet and unleashes a horde of malevolently mischievous monsters on a small town.",
@@ -31642 +31642 @@
-                "Ben Nott",
+                "Ben Not",
@@ -32603 +32603 @@
-                "Clea DuVall"
+                "Clean DuVall"
@@ -33602 +33602 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -33919 +33919 @@
-            "plot": "A French intelligence agent becomes embroiled in the Cold War politics first with uncovering the events leading up to the 1962 Cuban Missle Crisis, and then back to France to break up an international Russian spy ring.",
+            "plot": "A French intelligence agent becomes embroiled in the Cold War politics first with uncovering the events leading up to the 1962 Cuban Missile Crisis, and then back to France to break up an international Russian spy ring.",
@@ -36280 +36280 @@
-            "plot": "High school student Nick O'Leary, member of the Queercore band The Jerk Offs, meets college-bound Norah Silverberg when she asks him to be her boyfriend for five minutes.",
+            "plot": "High school student Nick O'Leery, member of the Queercore band The Jerk Offs, meets college-bound Norah Silverberg when she asks him to be her boyfriend for five minutes.",
@@ -40735 +40735 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -40964 +40964 @@
-                "Liev Schreiber"
+                "Live Schreiber"
@@ -43452 +43452 @@
-                "Chris Noth",
+                "Chris North",
@@ -46665 +46665 @@
-                "Kelsey Grammer"
+                "Kelsey Grammar"
@@ -46981 +46981 @@
-                "Joseph Cotten",
+                "Joseph Cotton",
@@ -47803 +47803 @@
-        "title": "Un monstre a Paris",
+        "title": "Un monster a Paris",
@@ -48599 +48599 @@
-                "Ned Beatty"
+                "Need Beatty"
@@ -48956 +48956 @@
-                "John McEnery"
+                "John McEnergy"
@@ -50807 +50807 @@
-                "Denis Leary"
+                "Denis Leery"
@@ -51122 +51122 @@
-                "Alex D. Linz",
+                "Alex D. Lines",
@@ -52979 +52979 @@
-                "Denis Leary"
+                "Denis Leery"
@@ -55410 +55410 @@
-            "plot": "In a Napoleonic era insane asylum, an inmate, the irrepressible Marquis De Sade, fights a battle of wills against a tyrannically prudish doctor.",
+            "plot": "In a Napoleonic era insane asylum, an inmate, the irrepressible Marquis De Sad, fights a battle of wills against a tyrannically prudish doctor.",
@@ -55651 +55651 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -56747 +56747 @@
-                "Steve Bacic",
+                "Steve Basic",
@@ -56836 +56836 @@
-            "plot": "On Christmas Eve, a doubting boy boards a magical train that's headed to the North Pole and Santa Claus's home.",
+            "plot": "On Christmas Eve, a doubting boy boards a magical train that's headed to the North Pole and Santa Clause's home.",
@@ -58768 +58768 @@
-        "title": "Because of Winn-Dixie",
+        "title": "Because of Win-Dixie",
@@ -59360 +59360 @@
-        "title": "Forces speciales",
+        "title": "Forces specials",
@@ -60724 +60724 @@
-            "directors": ["Stewart Hendler"],
+            "directors": ["Stewart Handler"],
@@ -62057 +62057 @@
-                "Liev Schreiber"
+                "Live Schreiber"
@@ -65418 +65418 @@
-            "plot": "Tells the story of a young woman's relentless search for her fiance, who has disappeared from the trenches of the Somme during World War One.",
+            "plot": "Tells the story of a young woman's relentless search for her fiance, who has disappeared from the trenches of the Some during World War One.",
@@ -66767 +66767 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -72412 +72412 @@
-            "plot": "When a man inadvertantly kills Santa on Christmas Eve, he finds himself magically recruited to take his place.",
+            "plot": "When a man inadvertently kills Santa on Christmas Eve, he finds himself magically recruited to take his place.",
@@ -72905 +72905 @@
-                "Liev Schreiber"
+                "Live Schreiber"
@@ -73800 +73800 @@
-                "Jack Sholder"
+                "Jack Shoulder"
@@ -75136 +75136 @@
-            "directors": ["Ned Benson"],
+            "directors": ["Need Benson"],
@@ -75392 +75392 @@
-        "title": "Luftslottet som sprangdes",
+        "title": "Luftslottet some sprangdes",
@@ -75426 +75426 @@
-                "Sean McClory",
+                "Sean McGlory",
@@ -76071 +76071 @@
-                "Erica Linz",
+                "Erica Lines",
@@ -76309 +76309 @@
-                "Ned Dowd"
+                "Need Dowd"
@@ -77888 +77888 @@
-        "title": "Coco avant Chanel",
+        "title": "Coco avant Channel",
@@ -77898 +77898 @@
-            "plot": "The story of Coco Chanel's rise from obscure beginnings to the heights of the fashion world.",
+            "plot": "The story of Coco Channel's rise from obscure beginnings to the heights of the fashion world.",
@@ -79500 +79500 @@
-                "Clea DuVall",
+                "Clean DuVall",
@@ -80963 +80963 @@
-                "Joseph Cotten",
+                "Joseph Cotton",
@@ -82091 +82091 @@
-            "directors": ["Liev Schreiber"],
+            "directors": ["Live Schreiber"],
@@ -82201 +82201 @@
-                "Kelsey Grammer",
+                "Kelsey Grammar",
@@ -83299 +83299 @@
-                "Kelsey Grammer"
+                "Kelsey Grammar"
@@ -83772 +83772 @@
-            "directors": ["Jack Sholder"],
+            "directors": ["Jack Shoulder"],
@@ -91381 +91381 @@
-                "Emily Atack",
+                "Emily Attack",
@@ -96130 +96130 @@
-                "Denis Leary",
+                "Denis Leery",
@@ -96330 +96330 @@
-                "Charles Durning"
+                "Charles During"
@@ -96561 +96561 @@
-                "Liev Schreiber",
+                "Live Schreiber",
@@ -97260 +97260 @@
-                "Joseph Cotten",
+                "Joseph Cotton",
@@ -99371 +99371 @@
-        "title": "Ned Kelly",
+        "title": "Need Kelly",
@@ -100094 +100094 @@
-        "title": "Paradies: Glaube",
+        "title": "Paradise: Glaube",
@@ -100545 +100545 @@
-            "plot": "At the opening party of a collosal, but poorly constructed, office building, a massive fire breaks out that threatens to destroy the tower and everyone in it.",
+            "plot": "At the opening party of a colossal, but poorly constructed, office building, a massive fire breaks out that threatens to destroy the tower and everyone in it.",
@@ -103451 +103451 @@
-            "directors": ["James Rabbitts"],
+            "directors": ["James Rabbits"],
