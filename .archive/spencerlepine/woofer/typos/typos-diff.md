## Detected Typos Diff
```diff
--- ./resources/REPOSITORY_SECRETS.md	original
+++ ./resources/REPOSITORY_SECRETS.md	fixed
@@ -3 +3 @@
-## Create `CI` enviroment with test coverage uploads
+## Create `CI` environment with test coverage uploads
@@ -6 +6 @@
-enviroment:
+environment:
@@ -12 +12 @@
-## Create `development` enviroment with development ENV vars
+## Create `development` environment with development ENV vars
@@ -15 +15 @@
-enviroment: development
+environment: development
@@ -31 +31 @@
-## Create `staging` enviroment with pre-production info
+## Create `staging` environment with pre-production info
@@ -34 +34 @@
-enviroment:
+environment:
@@ -45 +45 @@
-## Create `production` enviroment with production ENV vars
+## Create `production` environment with production ENV vars
@@ -48 +48 @@
-enviroment: production
+environment: production
--- ./resources/WOOFER_API.md	original
+++ ./resources/WOOFER_API.md	fixed
@@ -356 +356 @@
-## Verify Server Statuss
+## Verify Server Status
--- ./resources/challenges.txt	original
+++ ./resources/challenges.txt	fixed
@@ -14 +14 @@
-        - Seperate database for chats?
+        - Separate database for chats?
@@ -44 +44 @@
-Context: Need enviroment variables for tokens and config.
+Context: Need environment variables for tokens and config.
@@ -53 +53 @@
-Problem: SLOW GitHub Actions => Installing packages and setting up enviroments OVER and OVER
+Problem: SLOW GitHub Actions => Installing packages and setting up environments OVER and OVER
@@ -73 +73 @@
-Challenge: Deployment Stragety, Continuous Delivery with GitHub Actions to EC2 Instance
+Challenge: Deployment Strategy, Continuous Delivery with GitHub Actions to EC2 Instance
@@ -115,3 +115,3 @@
-Docker Image and Enviroment Variables
-Context: docker image unable to access enviroment variables
-Problem: have file for enviroment variables, it is pushing env files into images to DockerHub
+Docker Image and Environment Variables
+Context: docker image unable to access environment variables
+Problem: have file for environment variables, it is pushing env files into images to DockerHub
@@ -153 +153 @@
-# Docker + Webpack Enviroment Variables Challenge
+# Docker + Webpack Environment Variables Challenge
@@ -161 +161 @@
-My setup for this project is to read directly from a `.env` file. When building Docker images, this cuases problems, since different libaries handle `process.env` differently.
+My setup for this project is to read directly from a `.env` file. When building Docker images, this causes problems, since different libraries handle `process.env` differently.
@@ -170,5 +170,5 @@
-- [x] Refactored the Docker file for the client to refrence build ARGS and set ENV varaibles.
-- [x] Updated the Docker-compose file to pass build-args when building client image
-- [x] Updated the GitHub Action workfows to pass build-args when building the client image
-- [x] Updated the GitHub Action workfows to pass env variables when running the client container
-- [x] Removed broken refrences to .env file on the EC2 server. Only use ENV variables in the Node.js runtime, not storing a `.env` file on the EC2.
+- [x] Refactored the Docker file for the client to reference build ARGS and set ENV variables.
+- [x] Updated the Docker-compose file to pass build-args when building client image
+- [x] Updated the GitHub Action workflows to pass build-args when building the client image
+- [x] Updated the GitHub Action workflows to pass env variables when running the client container
+- [x] Removed broken references to .env file on the EC2 server. Only use ENV variables in the Node.js runtime, not storing a `.env` file on the EC2.
@@ -184 +184 @@
-Now, the GitHub enviroment will store the secrets, and the GitHub Action will set the ENV vars during the deployment.
+Now, the GitHub environment will store the secrets, and the GitHub Action will set the ENV vars during the deployment.
--- ./resources/development/resources.md	original
+++ ./resources/development/resources.md	fixed
@@ -150 +150 @@
-> TOCHECKOUT: Project Vulnerabilites Check w/ Synk - [GitHub Action](https://github.com/snyk/actions)
+> TOCHECKOUT: Project Vulnerabilities Check w/ Synk - [GitHub Action](https://github.com/snyk/actions)
@@ -153 +153 @@
-> Accessing Enviroments in workflows: - [Stack Overflow](https://stackoverflow.com/questions/66521958/how-to-access-environment-secrets-from-a-github-workflow)
+> Accessing Environments in workflows: - [Stack Overflow](https://stackoverflow.com/questions/66521958/how-to-access-environment-secrets-from-a-github-workflow)
--- ./resources/development/other/PORTFOLIO_SITE/projects/woofer/woofer.md	original
+++ ./resources/development/other/PORTFOLIO_SITE/projects/woofer/woofer.md	fixed
@@ -76 +76 @@
-- [React Testing Libary](https://testing-library.com/)
+- [React Testing Library](https://testing-library.com/)
--- ./client/src/components/pages/ChatListPage/ChatList/ChatList.test.js	original
+++ ./client/src/components/pages/ChatListPage/ChatList/ChatList.test.js	fixed
@@ -5 +5 @@
-import ChatListCompnent from "./ChatList"
+import ChatListComponent from "./ChatList"
@@ -9 +9 @@
-    <ChatListCompnent {...props} />
+    <ChatListComponent {...props} />
--- ./client/src/components/pages/ProfilePage/Profile/ImagesTab/ImagesTab.js	original
+++ ./client/src/components/pages/ProfilePage/Profile/ImagesTab/ImagesTab.js	fixed
@@ -28 +28 @@
-    // on reader load somthing...
+    // on reader load something...
--- ./client/src/components/ui/StatusChecker/StatusChecker.js	original
+++ ./client/src/components/ui/StatusChecker/StatusChecker.js	fixed
@@ -17 +17 @@
-  const [apiErorr, setApiError] = useState("")
+  const [apiError, setApiError] = useState("")
@@ -136 +136 @@
-                      {console.log(apiErorr)}
+                      {console.log(apiError)}
@@ -138 +138 @@
-                        <p>{apiErorr}</p>
+                        <p>{apiError}</p>
--- ./client/src/context/AuthContext/AuthContext.js	original
+++ ./client/src/context/AuthContext/AuthContext.js	fixed
@@ -34,3 +34,3 @@
-    authUser.checkLoginStatus((authenicatedUser) => {
-      if (authenicatedUser) {
-        setCurrentUser(authenicatedUser)
+    authUser.checkLoginStatus((authenticatedUser) => {
+      if (authenticatedUser) {
+        setCurrentUser(authenticatedUser)
--- ./client/src/utils/helpers.test.js	original
+++ ./client/src/utils/helpers.test.js	fixed
@@ -16 +16 @@
-      expect(formatAgeStr("inavlid date")).toBe("? y/o")
+      expect(formatAgeStr("invalid date")).toBe("? y/o")
--- ./client/src/utils/test-utils.js	original
+++ ./client/src/utils/test-utils.js	fixed
@@ -35 +35 @@
-// Replace the defualt render function
+// Replace the default render function
@@ -61 +61 @@
-  it('expectedExports should contain "targetInstance" key with contructor value', () => {
+  it('expectedExports should contain "targetInstance" key with constructor value', () => {
--- ./client/src/hooks/useAuthRedirect/useAuthRedirect.test.js	original
+++ ./client/src/hooks/useAuthRedirect/useAuthRedirect.test.js	fixed
@@ -8 +8 @@
-  const defualtValues = {}
+  const defaultValues = {}
@@ -10 +10 @@
-    <AuthContext.Provider value={{ ...defualtValues, ...contextValue }}>
+    <AuthContext.Provider value={{ ...defaultValues, ...contextValue }}>
--- ./client/webpack.ci.config.js	original
+++ ./client/webpack.ci.config.js	fixed
@@ -112 +112 @@
-    // Calculates sizes of gziped bundles.
+    // Calculates sizes of gzipped bundles.
--- ./client/webpack.prod.config.js	original
+++ ./client/webpack.prod.config.js	fixed
@@ -118 +118 @@
-    // Calculates sizes of gziped bundles.
+    // Calculates sizes of gzipped bundles.
--- ./server/src/database.test.js	original
+++ ./server/src/database.test.js	fixed
@@ -4 +4 @@
-  test("should be connected to a databse", (done) => {
+  test("should be connected to a database", (done) => {
--- ./server/src/app.js	original
+++ ./server/src/app.js	fixed
@@ -56 +56 @@
-    "Content-Type, Content-Length, Authorization, Accept, X-Requested-With , yourHeaderFeild"
+    "Content-Type, Content-Length, Authorization, Accept, X-Requested-With , yourHeaderField"
--- ./server/src/controllers/chats/deleteChatRoom/index.js	original
+++ ./server/src/controllers/chats/deleteChatRoom/index.js	fixed
@@ -11 +11 @@
-        message: "Successfuly delete chat room",
+        message: "Successfully delete chat room",
--- ./server/src/controllers/chats/createNewChat/createNewChat.test.js	original
+++ ./server/src/controllers/chats/createNewChat/createNewChat.test.js	fixed
@@ -56 +56 @@
-    test("should resolve and aadd chatIds to user profiles", (done) => {
+    test("should resolve and add chatIds to user profiles", (done) => {
--- ./server/src/controllers/matches/generateMoreQueueMatches/index.js	original
+++ ./server/src/controllers/matches/generateMoreQueueMatches/index.js	fixed
@@ -69 +69 @@
-              let validPrefenceStatus = false
+              let validPreferenceStatus = false
@@ -76 +76 @@
-                  validPrefenceStatus = true
+                  validPreferenceStatus = true
@@ -80 +80 @@
-                validPrefenceStatus,
+                validPreferenceStatus,
@@ -98,2 +98,2 @@
-        genderCheckObjects.forEach(({ validPrefenceStatus, userId }) => {
-          if (validPrefenceStatus) {
+        genderCheckObjects.forEach(({ validPreferenceStatus, userId }) => {
+          if (validPreferenceStatus) {
--- ./server/src/controllers/zipcodes/addUserZipCode/addUserZipCode.test.js	original
+++ ./server/src/controllers/zipcodes/addUserZipCode/addUserZipCode.test.js	fixed
@@ -57 +57 @@
-    test("should udpate user profile", (done) => {
+    test("should update user profile", (done) => {
--- ./server/config/config.js	original
+++ ./server/config/config.js	fixed
@@ -3 +3 @@
- * enviroment variables exists
+ * environment variables exists
