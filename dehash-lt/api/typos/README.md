## Detected Typos Diff
```diff
--- ./passwordChecker/README.md	original
+++ ./passwordChecker/README.md	fixed
@@ -17 +17 @@
-All these hashes are succesfully cracked and stored in our database
+All these hashes are successfully cracked and stored in our database
@@ -24 +24 @@
-## STEP 3: Write your own script or use one of our examples writen in:
+## STEP 3: Write your own script or use one of our examples written in:
--- ./api.php	original
+++ ./api.php	fixed
@@ -199,2 +199,2 @@
-			$submitedEmail = strtolower(explode(":", $line, 2)[0]);
-			$submitedHash = explode(":", $line, 2)[1];
+			$submittedEmail = strtolower(explode(":", $line, 2)[0]);
+			$submittedHash = explode(":", $line, 2)[1];
@@ -202 +202 @@
-			$emailsPasswords = search("EMAIL", $submitedEmail);
+			$emailsPasswords = search("EMAIL", $submittedEmail);
@@ -211,4 +211,4 @@
-				$verifiedPassword = crack($submitedHash, $passwords);
-				if($verifiedPassword){
-					$result = new \stdClass();
-					$result->_id = $submitedHash;
+				$verifiedPassword = crack($submittedHash, $passwords);
+				if($verifiedPassword){
+					$result = new \stdClass();
+					$result->_id = $submittedHash;
