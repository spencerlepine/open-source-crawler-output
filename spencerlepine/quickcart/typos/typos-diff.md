## Detected Typos Diff
```diff
--- ./README.md	original
+++ ./README.md	fixed
@@ -26 +26 @@
-- [React Testing Libary](https://testing-library.com/)
+- [React Testing Library](https://testing-library.com/)
@@ -40 +40 @@
-- Save product images with a convient image searching pop-up connected to Google CSE
+- Save product images with a convenient image searching pop-up connected to Google CSE
--- ./whitepaper/TODO	original
+++ ./whitepaper/TODO	fixed
@@ -14 +14 @@
- - Implement product reccomendations widget
+ - Implement product recommendations widget
--- ./client/src/components/FormContainer/ProductInfoEntry/ServingsPerInput/styles.js	original
+++ ./client/src/components/FormContainer/ProductInfoEntry/ServingsPerInput/styles.js	fixed
@@ -18 +18 @@
-      lineHeigt: '26px',
+      lineHeight: '26px',
--- ./client/src/components/FormContainer/FormContainer.test.js	original
+++ ./client/src/components/FormContainer/FormContainer.test.js	fixed
@@ -38 +38 @@
-  test('should update a product when editing an exisiting item', () => {
+  test('should update a product when editing an existing item', () => {
--- ./client/src/components/settings/ViewCartLogsButton/ViewCartLogsButton.js	original
+++ ./client/src/components/settings/ViewCartLogsButton/ViewCartLogsButton.js	fixed
@@ -10 +10 @@
-    <div className={`viewCartLogsButton ${classes.logContianer}`}>
+    <div className={`viewCartLogsButton ${classes.logContainer}`}>
--- ./client/src/components/settings/ViewCartLogsButton/styles.js	original
+++ ./client/src/components/settings/ViewCartLogsButton/styles.js	fixed
@@ -4 +4 @@
-  logContianer: {
+  logContainer: {
--- ./client/src/components/settings/AccountDetails/AccountDetails.js	original
+++ ./client/src/components/settings/AccountDetails/AccountDetails.js	fixed
@@ -23 +23 @@
-          <p><b>Acount Created:</b> {accountDetails['joinDate'].toString()}</p>
+          <p><b>Account Created:</b> {accountDetails['joinDate'].toString()}</p>
--- ./client/src/components/ui/Popup/styles.js	original
+++ ./client/src/components/ui/Popup/styles.js	fixed
@@ -20 +20 @@
-    width: 'fit-conent',
+    width: 'fit-content',
--- ./client/src/components/ProductDetails/styles.js	original
+++ ./client/src/components/ProductDetails/styles.js	fixed
@@ -152 +152 @@
-  nutritionDetials: {
+  nutritionDetails: {
@@ -160 +160 @@
-  extraDetials: {
+  extraDetails: {
--- ./client/src/components/ProductDetails/ProductDetails.js	original
+++ ./client/src/components/ProductDetails/ProductDetails.js	fixed
@@ -44 +44 @@
-            <div className={classes.extraDetials}>
+            <div className={classes.extraDetails}>
@@ -60 +60 @@
-        <div className={classes.nutritionDetials}>
+        <div className={classes.nutritionDetails}>
--- ./client/src/components/cart/CartViewer/CartViewer.test.js	original
+++ ./client/src/components/cart/CartViewer/CartViewer.test.js	fixed
@@ -49 +49 @@
-  test('clicking the "Analyze Cart" button changes text to "Veiw List"', done => {
+  test('clicking the "Analyze Cart" button changes text to "View List"', done => {
--- ./client/src/test-utils/testContextExports.js	original
+++ ./client/src/test-utils/testContextExports.js	fixed
@@ -22 +22 @@
-  it('expectedExports should contain "targetInstance" key with contructor value', () => {
+  it('expectedExports should contain "targetInstance" key with constructor value', () => {
--- ./client/src/context/AuthContext/AuthContext.js	original
+++ ./client/src/context/AuthContext/AuthContext.js	fixed
@@ -13,3 +13,3 @@
-    authUser.checkLoginStatus(authenicatedUser => {
-      if (authenicatedUser) {
-        setCurrentUser(authenicatedUser);
+    authUser.checkLoginStatus(authenticatedUser => {
+      if (authenticatedUser) {
+        setCurrentUser(authenticatedUser);
--- ./client/src/hooks/useAuthRedirect/useAuthRedirect.test.js	original
+++ ./client/src/hooks/useAuthRedirect/useAuthRedirect.test.js	fixed
@@ -8 +8 @@
-  const defualtValues = {};
+  const defaultValues = {};
@@ -10 +10 @@
-    <AuthContext.Provider value={{ ...defualtValues, ...contextValue }}>
+    <AuthContext.Provider value={{ ...defaultValues, ...contextValue }}>
--- ./webpack.prod.config.js	original
+++ ./webpack.prod.config.js	fixed
@@ -83 +83 @@
-    // Calculates sizes of gziped bundles.
+    // Calculates sizes of gzipped bundles.
