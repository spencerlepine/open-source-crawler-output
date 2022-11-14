## Detected Typos Diff
```diff
--- ./packages/react-dom/src/__tests__/ReactDOMInput-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMInput-test.js	fixed
@@ -2148 +2148 @@
-    // value in order to "dettach" it from defaultValue. This had the unfortunate
+    // value in order to "detach" it from defaultValue. This had the unfortunate
--- ./packages/react-dom/src/__tests__/ReactDOMServerIntegrationInput-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMServerIntegrationInput-test.js	fixed
@@ -40 +40 @@
-const desc = disableInputAttributeSyncing ? xdescribe : describe;
+const desc = disableInputAttributeSyncing ? describe : describe;
--- ./packages/react-dom/src/__tests__/ReactDOMOption-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMOption-test.js	fixed
@@ -201 +201 @@
-        <option>gir{a}ffe</option>
+        <option>git{a}ffe</option>
--- ./packages/react-dom/src/__tests__/ReactDOMEventPropagation-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMEventPropagation-test.js	fixed
@@ -1114,6 +1114,6 @@
-    it('onSeeked', () => {
-      testEmulatedBubblingEvent({
-        type: 'video',
-        reactEvent: 'onSeeked',
-        reactEventType: 'seeked',
-        nativeEvent: 'seeked',
+    it('onSought', () => {
+      testEmulatedBubblingEvent({
+        type: 'video',
+        reactEvent: 'onSought',
+        reactEventType: 'sought',
+        nativeEvent: 'sought',
@@ -1121 +1121 @@
-          const e = new Event('seeked', {
+          const e = new Event('sought', {
--- ./packages/react-dom/src/__tests__/ReactDOMSingletonComponents-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMSingletonComponents-test.js	fixed
@@ -628 +628 @@
-    // We construct and insert some artificial stylesheets mimicing what a 3rd party script might do
+    // We construct and insert some artificial stylesheets mimicking what a 3rd party script might do
--- ./packages/react-dom/src/__tests__/ReactDOMServerPartialHydration-test.internal.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMServerPartialHydration-test.internal.js	fixed
@@ -804,2 +804,2 @@
-      const [visible, setVisibilty] = React.useState(false);
-      showSibling = () => setVisibilty(true);
+      const [visible, setVisibility] = React.useState(false);
+      showSibling = () => setVisibility(true);
@@ -866,2 +866,2 @@
-      const [visible, setVisibilty] = React.useState(true);
-      hideMiddle = () => setVisibilty(false);
+      const [visible, setVisibility] = React.useState(true);
+      hideMiddle = () => setVisibility(false);
--- ./packages/react-dom/src/__tests__/__snapshots__/ReactTestUtils-test.js.snap	original
+++ ./packages/react-dom/src/__tests__/__snapshots__/ReactTestUtils-test.js.snap	fixed
@@ -74 +74 @@
-  "seeked",
+  "sought",
--- ./packages/react-dom/src/__tests__/ReactDOMFizzServer-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMFizzServer-test.js	fixed
@@ -426 +426 @@
-    CSPnonce = 'R4nd0m';
+    CSPnonce = 'R4and0m';
@@ -442 +442 @@
-          {nonce: 'R4nd0m'},
+          {nonce: 'R4and0m'},
@@ -3516 +3516 @@
-      // these characters valid javascript and may be necessary in scripts and won't be interpretted properly
+      // these characters valid javascript and may be necessary in scripts and won't be interpreted properly
@@ -3802 +3802 @@
-  it('supresses hydration warnings when an error occurs within a Suspense boundary', async () => {
+  it('suppresses hydration warnings when an error occurs within a Suspense boundary', async () => {
--- ./packages/react-dom/src/__tests__/ReactDOMEventListener-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMEventListener-test.js	fixed
@@ -392 +392 @@
-      onSeeked() {},
+      onSought() {},
@@ -435 +435 @@
-        case 'seeked':
+        case 'sought':
--- ./packages/react-dom/src/__tests__/ReactDOMFloat-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMFloat-test.js	fixed
@@ -4043,9 +4043,9 @@
-            ' anonymouse CORS mode. To fix add an empty string, "anonymous", or any other string' +
-            ' value except "use-credentials" for the crossOrigin prop of all font preloads.%s',
-          'preload Resource (as "font")',
-          'foo',
-          componentStack(['link', 'body', 'html']),
-        );
-        expect(mockError).toHaveBeenCalledWith(
-          'Warning: A %s with href "%s" specified a crossOrigin value of "use-credentials". Font preloads must always use' +
-            ' anonymouse CORS mode. To fix use an empty string, "anonymous", or any other string' +
+            ' anonymous CORS mode. To fix add an empty string, "anonymous", or any other string' +
+            ' value except "use-credentials" for the crossOrigin prop of all font preloads.%s',
+          'preload Resource (as "font")',
+          'foo',
+          componentStack(['link', 'body', 'html']),
+        );
+        expect(mockError).toHaveBeenCalledWith(
+          'Warning: A %s with href "%s" specified a crossOrigin value of "use-credentials". Font preloads must always use' +
+            ' anonymous CORS mode. To fix use an empty string, "anonymous", or any other string' +
@@ -4661,10 +4661,10 @@
-        'Warning: A style Resource with href "foo" recieved new props with different values from the props used' +
-          ' when this Resource was first rendered. React will only use the props provided when' +
-          ' this resource was first rendered until a new href is provided. Unlike conventional' +
-          ' DOM elements, Resources instances do not have a one to one correspondence with Elements' +
-          ' in the DOM and as such, every instance of a Resource for a single Resource identifier' +
-          ' (href) must have props that agree with each other. The differences are described below.' +
-          '\n  data-something-extra: missing or null in latest props, "extra" in original props' +
-          '\n  data-something-new: "new" in latest props, missing or null in original props' +
-          '\n  precedence: "fu" in latest props, "foo" in original props',
-        'Warning: A script Resource with src "sfoo" recieved new props with different values from the props used' +
+        'Warning: A style Resource with href "foo" received new props with different values from the props used' +
+          ' when this Resource was first rendered. React will only use the props provided when' +
+          ' this resource was first rendered until a new href is provided. Unlike conventional' +
+          ' DOM elements, Resources instances do not have a one to one correspondence with Elements' +
+          ' in the DOM and as such, every instance of a Resource for a single Resource identifier' +
+          ' (href) must have props that agree with each other. The differences are described below.' +
+          '\n  data-something-extra: missing or null in latest props, "extra" in original props' +
+          '\n  data-something-new: "new" in latest props, missing or null in original props' +
+          '\n  precedence: "fu" in latest props, "foo" in original props',
+        'Warning: A script Resource with src "sfoo" received new props with different values from the props used' +
--- ./packages/react-dom/src/__tests__/ReactDOMFizzServerBrowser-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMFizzServerBrowser-test.js	fixed
@@ -367 +367 @@
-  it('should stream large contents that might overlow individual buffers', async () => {
+  it('should stream large contents that might overflow individual buffers', async () => {
@@ -375 +375 @@
-    // the view sizes change or become dynamic becasue of the use of byobRequest
+    // the view sizes change or become dynamic because of the use of byobRequest
--- ./packages/react-dom/src/__tests__/ReactDOMServerIntegrationCheckbox-test.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMServerIntegrationCheckbox-test.js	fixed
@@ -40 +40 @@
-const desc = disableInputAttributeSyncing ? xdescribe : describe;
+const desc = disableInputAttributeSyncing ? describe : describe;
--- ./packages/react-dom/src/__tests__/ReactDOMImageLoad-test.internal.js	original
+++ ./packages/react-dom/src/__tests__/ReactDOMImageLoad-test.internal.js	fixed
@@ -306 +306 @@
-      // yield is ignored becasue we are sync rendering
+      // yield is ignored because we are sync rendering
--- ./packages/react-dom/src/test-utils/ReactTestUtils.js	original
+++ ./packages/react-dom/src/test-utils/ReactTestUtils.js	fixed
@@ -659 +659 @@
-  'seeked',
+  'sought',
--- ./packages/react-devtools-extensions/README.md	original
+++ ./packages/react-devtools-extensions/README.md	fixed
@@ -7,2 +7,2 @@
-* [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/react-devtools/)
-* [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/react-developer-tools/gpphkfbcpidddadnkolkpfckpihlkkil)
+* [Firefox Add-owns](https://addons.mozilla.org/en-US/firefox/addon/react-devtools/)
+* [Edge Add-owns](https://microsoftedge.microsoft.com/addons/detail/react-developer-tools/gpphkfbcpidddadnkolkpfckpihlkkil)
--- ./packages/react-devtools-extensions/flow-typed/jest.js	original
+++ ./packages/react-devtools-extensions/flow-typed/jest.js	fixed
@@ -1075 +1075 @@
-declare var xdescribe: typeof describe;
+declare var describe: typeof describe;
--- ./packages/react-devtools-core/src/standalone.js	original
+++ ./packages/react-devtools-core/src/standalone.js	fixed
@@ -347 +347 @@
-    // Because of this it relies on the extension to pass filters, so include them wth the response here.
+    // Because of this it relies on the extension to pass filters, so include them with the response here.
--- ./packages/react-reconciler/src/ReactFiberBeginWork.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberBeginWork.old.js	fixed
@@ -1568 +1568 @@
-  // should be implemented to warn when children are passsed when otherwise not
+  // should be implemented to warn when children are passed when otherwise not
@@ -3924 +3924 @@
-      // Check if this child belongs to a list of muliple children in
+      // Check if this child belongs to a list of multiple children in
--- ./packages/react-reconciler/src/ReactFiberHooks.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberHooks.new.js	fixed
@@ -1637 +1637 @@
-    // Check if the susbcribe function changed. We can save some memory by
+    // Check if the subscribe function changed. We can save some memory by
@@ -2396 +2396 @@
-    // Use a captial R prefix for server-generated ids.
+    // Use a capital R prefix for server-generated ids.
--- ./packages/react-reconciler/src/__tests__/useSyncExternalStore-test.js	original
+++ ./packages/react-reconciler/src/__tests__/useSyncExternalStore-test.js	fixed
@@ -100 +100 @@
-          // This demostrates whether the children are consistent when the
+          // This demonstrates whether the children are consistent when the
--- ./packages/react-reconciler/src/__tests__/ReactOffscreen-test.js	original
+++ ./packages/react-reconciler/src/__tests__/ReactOffscreen-test.js	fixed
@@ -1525 +1525 @@
-      // Offscreen is attached by default. State updates from offscreen are **not defered**.
+      // Offscreen is attached by default. State updates from offscreen are **not deferred**.
@@ -1544 +1544 @@
-      // Offscreen is detached. State updates from offscreen are **defered**.
+      // Offscreen is detached. State updates from offscreen are **deferred**.
@@ -1623 +1623 @@
-      // Offscreen is attached. State updates from offscreen are **not defered**.
+      // Offscreen is attached. State updates from offscreen are **not deferred**.
@@ -1642 +1642 @@
-      // Offscreen is detached. State updates from offscreen are **defered**.
+      // Offscreen is detached. State updates from offscreen are **deferred**.
--- ./packages/react-reconciler/src/ReactFiberTreeContext.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberTreeContext.new.js	fixed
@@ -112 +112 @@
-  // the whole set without doing extra work later, or storing addtional
+  // the whole set without doing extra work later, or storing additional
--- ./packages/react-reconciler/src/ReactFiberWorkLoop.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberWorkLoop.new.js	fixed
@@ -2263 +2263 @@
-  // This is a fork of performUnitOfWork specifcally for replaying a fiber that
+  // This is a fork of performUnitOfWork specifically for replaying a fiber that
@@ -2301 +2301 @@
-  // This is a fork of performUnitOfWork specifcally for unwinding a fiber
+  // This is a fork of performUnitOfWork specifically for unwinding a fiber
--- ./packages/react-reconciler/src/ReactFiberHydrationContext.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberHydrationContext.new.js	fixed
@@ -94 +94 @@
-// This flag allows for warning supression when we expect there to be mismatches
+// This flag allows for warning suppression when we expect there to be mismatches
--- ./packages/react-reconciler/src/ReactFiberHydrationContext.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberHydrationContext.old.js	fixed
@@ -94 +94 @@
-// This flag allows for warning supression when we expect there to be mismatches
+// This flag allows for warning suppression when we expect there to be mismatches
--- ./packages/react-reconciler/src/ReactFiberBeginWork.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberBeginWork.new.js	fixed
@@ -1568 +1568 @@
-  // should be implemented to warn when children are passsed when otherwise not
+  // should be implemented to warn when children are passed when otherwise not
@@ -3924 +3924 @@
-      // Check if this child belongs to a list of muliple children in
+      // Check if this child belongs to a list of multiple children in
--- ./packages/react-reconciler/src/ReactFiberTreeContext.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberTreeContext.old.js	fixed
@@ -112 +112 @@
-  // the whole set without doing extra work later, or storing addtional
+  // the whole set without doing extra work later, or storing additional
--- ./packages/react-reconciler/src/ReactFiberHooks.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberHooks.old.js	fixed
@@ -1637 +1637 @@
-    // Check if the susbcribe function changed. We can save some memory by
+    // Check if the subscribe function changed. We can save some memory by
@@ -2396 +2396 @@
-    // Use a captial R prefix for server-generated ids.
+    // Use a capital R prefix for server-generated ids.
--- ./packages/react-reconciler/src/ReactFiberCommitWork.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberCommitWork.new.js	fixed
@@ -2885 +2885 @@
-          // Only trigger disapper layout effects if:
+          // Only trigger disappear layout effects if:
@@ -4143 +4143 @@
-      // order as during a deletiong: parent before child
+      // order as during a deletion: parent before child
--- ./packages/react-reconciler/src/ReactFiberWorkLoop.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberWorkLoop.old.js	fixed
@@ -2263 +2263 @@
-  // This is a fork of performUnitOfWork specifcally for replaying a fiber that
+  // This is a fork of performUnitOfWork specifically for replaying a fiber that
@@ -2301 +2301 @@
-  // This is a fork of performUnitOfWork specifcally for unwinding a fiber
+  // This is a fork of performUnitOfWork specifically for unwinding a fiber
--- ./packages/react-reconciler/src/ReactFiberClassComponent.new.js	original
+++ ./packages/react-reconciler/src/ReactFiberClassComponent.new.js	fixed
@@ -499 +499 @@
-    if (typeof instance.componentWillRecieveProps === 'function') {
+    if (typeof instance.componentWillReceiveProps === 'function') {
@@ -502 +502 @@
-          'componentWillRecieveProps(). Did you mean componentWillReceiveProps()?',
+          'componentWillReceiveProps(). Did you mean componentWillReceiveProps()?',
@@ -506 +506 @@
-    if (typeof instance.UNSAFE_componentWillRecieveProps === 'function') {
+    if (typeof instance.UNSAFE_componentWillReceiveProps === 'function') {
@@ -509 +509 @@
-          'UNSAFE_componentWillRecieveProps(). Did you mean UNSAFE_componentWillReceiveProps()?',
+          'UNSAFE_componentWillReceiveProps(). Did you mean UNSAFE_componentWillReceiveProps()?',
--- ./packages/react-reconciler/src/ReactFiberCommitWork.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberCommitWork.old.js	fixed
@@ -2885 +2885 @@
-          // Only trigger disapper layout effects if:
+          // Only trigger disappear layout effects if:
@@ -4143 +4143 @@
-      // order as during a deletiong: parent before child
+      // order as during a deletion: parent before child
--- ./packages/react-reconciler/src/ReactFiberClassComponent.old.js	original
+++ ./packages/react-reconciler/src/ReactFiberClassComponent.old.js	fixed
@@ -499 +499 @@
-    if (typeof instance.componentWillRecieveProps === 'function') {
+    if (typeof instance.componentWillReceiveProps === 'function') {
@@ -502 +502 @@
-          'componentWillRecieveProps(). Did you mean componentWillReceiveProps()?',
+          'componentWillReceiveProps(). Did you mean componentWillReceiveProps()?',
@@ -506 +506 @@
-    if (typeof instance.UNSAFE_componentWillRecieveProps === 'function') {
+    if (typeof instance.UNSAFE_componentWillReceiveProps === 'function') {
@@ -509 +509 @@
-          'UNSAFE_componentWillRecieveProps(). Did you mean UNSAFE_componentWillReceiveProps()?',
+          'UNSAFE_componentWillReceiveProps(). Did you mean UNSAFE_componentWillReceiveProps()?',
--- ./packages/react-devtools-shell/src/e2e/devtools.js	original
+++ ./packages/react-devtools-shell/src/e2e/devtools.js	fixed
@@ -11 +11 @@
-// TODO (Webpack 5) Hoepfully we can remove this once we upgrade to Webpack 5.
+// TODO (Webpack 5) Hopefully we can remove this once we upgrade to Webpack 5.
--- ./packages/react-devtools-shell/src/e2e-regression/devtools.js	original
+++ ./packages/react-devtools-shell/src/e2e-regression/devtools.js	fixed
@@ -11 +11 @@
-// TODO (Webpack 5) Hoepfully we can remove this once we upgrade to Webpack 5.
+// TODO (Webpack 5) Hopefully we can remove this once we upgrade to Webpack 5.
--- ./packages/react-devtools-shell/src/app/devtools.js	original
+++ ./packages/react-devtools-shell/src/app/devtools.js	fixed
@@ -13 +13 @@
-// TODO (Webpack 5) Hoepfully we can remove this once we upgrade to Webpack 5.
+// TODO (Webpack 5) Hopefully we can remove this once we upgrade to Webpack 5.
--- ./packages/react-devtools-shared/src/__tests__/profilingHostRoot-test.js	original
+++ ./packages/react-devtools-shared/src/__tests__/profilingHostRoot-test.js	fixed
@@ -38 +38 @@
-    // This is the DevTools hook installed by the env.beforEach()
+    // This is the DevTools hook installed by the env.beforeEach()
--- ./packages/react-devtools-shared/src/__tests__/TimelineProfiler-test.js	original
+++ ./packages/react-devtools-shared/src/__tests__/TimelineProfiler-test.js	fixed
@@ -1410 +1410 @@
-        // There should be two batches of renders: Suspeneded and resolved.
+        // There should be two batches of renders: Suspended and resolved.
@@ -1468 +1468 @@
-        // There should be two batches of renders: Suspeneded and resolved.
+        // There should be two batches of renders: Suspended and resolved.
@@ -1526 +1526 @@
-        // There should be two batches of renders: Suspeneded and resolved.
+        // There should be two batches of renders: Suspended and resolved.
@@ -1584 +1584 @@
-        // There should be two batches of renders: Suspeneded and resolved.
+        // There should be two batches of renders: Suspended and resolved.
@@ -2482 +2482 @@
-        function CommponentWithChildren({initialRender}) {
+        function ComponentWithChildren({initialRender}) {
@@ -2496 +2496 @@
-        renderRootHelper(<CommponentWithChildren initialRender={false} />);
+        renderRootHelper(<ComponentWithChildren initialRender={false} />);
@@ -2517 +2517 @@
-              in CommponentWithChildren (at **)",
+              in ComponentWithChildren (at **)",
--- ./packages/react-devtools-shared/src/__tests__/utils-test.js	original
+++ ./packages/react-devtools-shared/src/__tests__/utils-test.js	fixed
@@ -186 +186 @@
-    it('should format string substituions', () => {
+    it('should format string substitutions', () => {
@@ -192 +192 @@
-      // deal, since there is a string substituion but it's incorrect
+      // deal, since there is a string substitution but it's incorrect
@@ -219 +219 @@
-    it('should properly format escaped string substituions', () => {
+    it('should properly format escaped string substitutions', () => {
--- ./packages/react-devtools-shared/src/__tests__/inspectedElement-test.js	original
+++ ./packages/react-devtools-shared/src/__tests__/inspectedElement-test.js	fixed
@@ -2881 +2881 @@
-      // Inpsect <ErrorBoundary /> to toggle off the error state
+      // Inspect <ErrorBoundary /> to toggle off the error state
--- ./packages/react-devtools-shared/src/devtools/utils.js	original
+++ ./packages/react-devtools-shared/src/devtools/utils.js	fixed
@@ -195 +195 @@
-const STACK_DELIMETER = /\n\s+at /;
+const STACK_DELIMITER = /\n\s+at /;
@@ -203 +203 @@
-    .split(STACK_DELIMETER)
+    .split(STACK_DELIMITER)
--- ./packages/react-devtools-shared/src/__tests__/preprocessData-test.js	original
+++ ./packages/react-devtools-shared/src/__tests__/preprocessData-test.js	fixed
@@ -1757 +1757 @@
-          it('shoult parse Errors thrown during render', async () => {
+          it('should parse Errors thrown during render', async () => {
@@ -1805 +1805 @@
-          it('should warn about suspending during an udpate', async () => {
+          it('should warn about suspending during an update', async () => {
--- ./packages/react-devtools-shared/src/devtools/store.js	original
+++ ./packages/react-devtools-shared/src/devtools/store.js	fixed
@@ -449 +449 @@
-  // This is a static flag, controled by the Store config.
+  // This is a static flag, controlled by the Store config.
@@ -466 +466 @@
-  // This is a static flag, controled by the Store config.
+  // This is a static flag, controlled by the Store config.
--- ./packages/react-devtools-shared/src/devtools/views/Settings/GeneralSettings.js	original
+++ ./packages/react-devtools-shared/src/devtools/views/Settings/GeneralSettings.js	fixed
@@ -26 +26 @@
-  // but the "." are stripped from anchor tags, becomming: <major><minor><patch>
+  // but the "." are stripped from anchor tags, becoming: <major><minor><patch>
--- ./packages/react-devtools-shared/src/devtools/views/Profiler/WhatChanged.js	original
+++ ./packages/react-devtools-shared/src/devtools/views/Profiler/WhatChanged.js	fixed
@@ -19 +19 @@
-  // This is debatable but I think 1-based might ake for a nicer UX.
+  // This is debatable but I think 1-based might ache for a nicer UX.
--- ./packages/react-devtools-shared/src/devtools/views/ErrorBoundary/ErrorBoundary.js	original
+++ ./packages/react-devtools-shared/src/devtools/views/ErrorBoundary/ErrorBoundary.js	fixed
@@ -164 +164 @@
-            errorMessage={errorMessage || 'Error occured in inspected element'}
+            errorMessage={errorMessage || 'Error occurred in inspected element'}
--- ./packages/react-devtools-shared/src/hook.js	original
+++ ./packages/react-devtools-shared/src/hook.js	fixed
@@ -223 +223 @@
-  // React and DevTools are connecting and the renderer interface isn't avaiable
+  // React and DevTools are connecting and the renderer interface isn't available
--- ./packages/react-devtools-shared/src/backend/StyleX/utils.js	original
+++ ./packages/react-devtools-shared/src/backend/StyleX/utils.js	fixed
@@ -93 +93 @@
-    // $FlowFixMe Flow doesn't konw about these properties
+    // $FlowFixMe Flow doesn't know about these properties
@@ -99 +99 @@
-      // $FlowFixMe Flow doesn't konw about these properties
+      // $FlowFixMe Flow doesn't know about these properties
--- ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/react-sources-extended/ToDoList.js.map	original
+++ ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/react-sources-extended/ToDoList.js.map	fixed
@@ -1 +1 @@
-{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_react_sources":[[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]}+{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_react_sources":[[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]}--- ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/react-sources-extended/index-map/ToDoList.js.map	original
+++ ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/react-sources-extended/index-map/ToDoList.js.map	fixed
@@ -1 +1 @@
-{"version":3,"sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_react_sources":[[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]}}]}+{"version":3,"sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_react_sources":[[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]}}]}--- ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/ToDoList.js.map	original
+++ ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/ToDoList.js.map	fixed
@@ -1 +1 @@
-{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"]}+{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"]}--- ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/fb-sources-extended/ToDoList.js.map	original
+++ ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/fb-sources-extended/ToDoList.js.map	fixed
@@ -1 +1 @@
-{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_facebook_sources":[[null,[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]]}+{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_facebook_sources":[[null,[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]]}--- ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/fb-sources-extended/index-map/ToDoList.js.map	original
+++ ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/fb-sources-extended/index-map/ToDoList.js.map	fixed
@@ -1 +1 @@
-{"version":3,"sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_facebook_sources":[[null,[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]]}}]}+{"version":3,"sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"],"x_facebook_sources":[[null,[{"names":["<no-hook>","handleDelete","handleToggle","newItemText","items","uid","handleClick","handleKeyPress","handleChange","removeItem","toggleItem"],"mappings":"CAAD;cuBCA;gBCDA;kBDEA;oBCFA;sCgBGA,AYHA;uCxBIA;2CxBJA;4CoBKA,AWLA;8CbMA;2DSNA;6DNOA;oEtBPA;sEoBQA;2EpBRA;6EkBSA;gFlBTA;kFkBUA;mGlBVA"}]]]}}]}--- ./packages/react-devtools-shared/src/backend/renderer.js	original
+++ ./packages/react-devtools-shared/src/backend/renderer.js	fixed
@@ -646 +646 @@
-    // This is less effecient since it means the front-end will need to purge the entire cache,
+    // This is less efficient since it means the front-end will need to purge the entire cache,
--- ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/index-map/ToDoList.js.map	original
+++ ./packages/react-devtools-shared/src/hooks/__tests__/__source__/__compiled__/external/index-map/ToDoList.js.map	fixed
@@ -1 +1 @@
-{"version":3,"sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"]}}]}+{"version":3,"sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"sources":["ToDoList.js"],"names":["ListItem","item","removeItem","toggleItem","handleDelete","handleToggle","isComplete","text","List","props","newItemText","setNewItemText","items","setItems","id","uid","setUID","handleClick","handleKeyPress","event","key","handleChange","currentTarget","value","itemToRemove","filter","itemToToggle","index","findIndex","slice","concat","map"],"mappings":"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","sourcesContent":["/**\n * Copyright (c) Meta Platforms, Inc. and affiliates.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n *\n * @flow\n */\n\nimport * as React from 'react';\nimport {Fragment, useCallback, useState} from 'react';\n\nexport function ListItem({item, removeItem, toggleItem}) {\n  const handleDelete = useCallback(() => {\n    removeItem(item);\n  }, [item, removeItem]);\n\n  const handleToggle = useCallback(() => {\n    toggleItem(item);\n  }, [item, toggleItem]);\n\n  return (\n    <li>\n      <button onClick={handleDelete}>Delete</button>\n      <label>\n        <input\n          checked={item.isComplete}\n          onChange={handleToggle}\n          type=\"checkbox\"\n        />{' '}\n        {item.text}\n      </label>\n    </li>\n  );\n}\n\nexport function List(props) {\n  const [newItemText, setNewItemText] = useState('');\n  const [items, setItems] = useState([\n    {id: 1, isComplete: true, text: 'First'},\n    {id: 2, isComplete: true, text: 'Second'},\n    {id: 3, isComplete: false, text: 'Third'},\n  ]);\n  const [uid, setUID] = useState(4);\n\n  const handleClick = useCallback(() => {\n    if (newItemText !== '') {\n      setItems([\n        ...items,\n        {\n          id: uid,\n          isComplete: false,\n          text: newItemText,\n        },\n      ]);\n      setUID(uid + 1);\n      setNewItemText('');\n    }\n  }, [newItemText, items, uid]);\n\n  const handleKeyPress = useCallback(\n    event => {\n      if (event.key === 'Enter') {\n        handleClick();\n      }\n    },\n    [handleClick],\n  );\n\n  const handleChange = useCallback(\n    event => {\n      setNewItemText(event.currentTarget.value);\n    },\n    [setNewItemText],\n  );\n\n  const removeItem = useCallback(\n    itemToRemove => setItems(items.filter(item => item !== itemToRemove)),\n    [items],\n  );\n\n  const toggleItem = useCallback(\n    itemToToggle => {\n      // Dont use indexOf()\n      // because editing props in DevTools creates a new Object.\n      const index = items.findIndex(item => item.id === itemToToggle.id);\n\n      setItems(\n        items\n          .slice(0, index)\n          .concat({\n            ...itemToToggle,\n            isComplete: !itemToToggle.isComplete,\n          })\n          .concat(items.slice(index + 1)),\n      );\n    },\n    [items],\n  );\n\n  return (\n    <Fragment>\n      <h1>List</h1>\n      <input\n        type=\"text\"\n        placeholder=\"New list item...\"\n        value={newItemText}\n        onChange={handleChange}\n        onKeyPress={handleKeyPress}\n      />\n      <button disabled={newItemText === ''} onClick={handleClick}>\n        <span role=\"img\" aria-label=\"Add item\">\n          Add\n        </span>\n      </button>\n      <ul>\n        {items.map(item => (\n          <ListItem\n            key={item.id}\n            item={item}\n            removeItem={removeItem}\n            toggleItem={toggleItem}\n          />\n        ))}\n      </ul>\n    </Fragment>\n  );\n}\n"]}}]}--- ./packages/react-devtools-shared/src/hooks/parseHookNames/parseSourceAndMetadata.js	original
+++ ./packages/react-devtools-shared/src/hooks/parseHookNames/parseSourceAndMetadata.js	fixed
@@ -345 +345 @@
-          // rather than in loadSourceAndMetatada -> loadSourceFiles().
+          // rather than in loadSourceAndMetadata -> loadSourceFiles().
--- ./packages/shared/CheckStringCoercion.js	original
+++ ./packages/shared/CheckStringCoercion.js	fixed
@@ -65 +65 @@
-  // problem and how that type was used: key, atrribute, input value prop, etc.
+  // problem and how that type was used: key, attribute, input value prop, etc.
--- ./packages/react-devtools/CHANGELOG.md	original
+++ ./packages/react-devtools/CHANGELOG.md	fixed
@@ -59 +59 @@
-* Fix regex for `formateWithStyles` function ([lunaruan](https://github.com/lunaruan) in [#24486](https://github.com/facebook/react/pull/24486))
+* Fix regex for `formatWithStyles` function ([lunaruan](https://github.com/lunaruan) in [#24486](https://github.com/facebook/react/pull/24486))
--- ./packages/react/src/__tests__/ReactES6Class-test.js	original
+++ ./packages/react/src/__tests__/ReactES6Class-test.js	fixed
@@ -503 +503 @@
-      componentWillRecieveProps() {
+      componentWillReceiveProps() {
@@ -513 +513 @@
-        'NamedComponent has a method called componentWillRecieveProps(). Did ' +
+        'NamedComponent has a method called componentWillReceiveProps(). Did ' +
@@ -520 +520 @@
-      UNSAFE_componentWillRecieveProps() {
+      UNSAFE_componentWillReceiveProps() {
@@ -530 +530 @@
-        'NamedComponent has a method called UNSAFE_componentWillRecieveProps(). ' +
+        'NamedComponent has a method called UNSAFE_componentWillReceiveProps(). ' +
--- ./packages/react/src/__tests__/ReactProfiler-test.internal.js	original
+++ ./packages/react/src/__tests__/ReactProfiler-test.internal.js	fixed
@@ -2736,8 +2736,8 @@
-        nestedUpdateSheduled: false,
-      };
-      componentDidUpdate(prevProps, prevState) {
-        if (
-          this.props.scheduleNestedUpdate &&
-          !this.state.nestedUpdateSheduled
-        ) {
-          this.setState({nestedUpdateSheduled: true});
+        nestedUpdateScheduled: false,
+      };
+      componentDidUpdate(prevProps, prevState) {
+        if (
+          this.props.scheduleNestedUpdate &&
+          !this.state.nestedUpdateScheduled
+        ) {
+          this.setState({nestedUpdateScheduled: true});
@@ -2748,5 +2748,5 @@
-        const {nestedUpdateSheduled} = this.state;
-        Scheduler.unstable_yieldValue(
-          `Component:${scheduleNestedUpdate}:${nestedUpdateSheduled}`,
-        );
-        return nestedUpdateSheduled;
+        const {nestedUpdateScheduled} = this.state;
+        Scheduler.unstable_yieldValue(
+          `Component:${scheduleNestedUpdate}:${nestedUpdateScheduled}`,
+        );
+        return nestedUpdateScheduled;
--- ./packages/react/src/__tests__/ReactCoffeeScriptClass-test.coffee	original
+++ ./packages/react/src/__tests__/ReactCoffeeScriptClass-test.coffee	fixed
@@ -466 +466 @@
-      componentWillRecieveProps: ->
+      componentWillReceiveProps: ->
@@ -477 +477 @@
-      'Warning: NamedComponent has a method called componentWillRecieveProps().
+      'Warning: NamedComponent has a method called componentWillReceiveProps().
@@ -483 +483 @@
-      UNSAFE_componentWillRecieveProps: ->
+      UNSAFE_componentWillReceiveProps: ->
@@ -494 +494 @@
-      'Warning: NamedComponent has a method called UNSAFE_componentWillRecieveProps().
+      'Warning: NamedComponent has a method called UNSAFE_componentWillReceiveProps().
--- ./packages/react/src/__tests__/createReactClassIntegration-test.js	original
+++ ./packages/react/src/__tests__/createReactClassIntegration-test.js	fixed
@@ -147 +147 @@
-        componentWillRecieveProps: function() {
+        componentWillReceiveProps: function() {
@@ -155 +155 @@
-      'Warning: A component has a method called componentWillRecieveProps(). Did you ' +
+      'Warning: A component has a method called componentWillReceiveProps(). Did you ' +
@@ -164 +164 @@
-        UNSAFE_componentWillRecieveProps: function() {
+        UNSAFE_componentWillReceiveProps: function() {
@@ -172 +172 @@
-      'Warning: A component has a method called UNSAFE_componentWillRecieveProps(). ' +
+      'Warning: A component has a method called UNSAFE_componentWillReceiveProps(). ' +
--- ./packages/react/src/__tests__/ReactTypeScriptClass-test.ts	original
+++ ./packages/react/src/__tests__/ReactTypeScriptClass-test.ts	fixed
@@ -275 +275 @@
-  componentWillRecieveProps() {
+  componentWillReceiveProps() {
@@ -285 +285 @@
-  UNSAFE_componentWillRecieveProps() {
+  UNSAFE_componentWillReceiveProps() {
@@ -653 +653 @@
-        'MisspelledComponent2 has a method called componentWillRecieveProps(). ' +
+        'MisspelledComponent2 has a method called componentWillReceiveProps(). ' +
@@ -663 +663 @@
-        'MisspelledComponent3 has a method called UNSAFE_componentWillRecieveProps(). ' +
+        'MisspelledComponent3 has a method called UNSAFE_componentWillReceiveProps(). ' +
--- ./packages/react-refresh/src/__tests__/ReactFreshBabelPlugin-test.js	original
+++ ./packages/react-refresh/src/__tests__/ReactFreshBabelPlugin-test.js	fixed
@@ -528 +528 @@
-  it('does not get tripped by IIFEs', () => {
+  it('does not get tripped by IFEs', () => {
--- ./packages/react-refresh/src/__tests__/__snapshots__/ReactFreshBabelPlugin-test.js.snap	original
+++ ./packages/react-refresh/src/__tests__/__snapshots__/ReactFreshBabelPlugin-test.js.snap	fixed
@@ -89 +89 @@
-exports[`ReactFreshBabelPlugin does not get tripped by IIFEs 1`] = `
+exports[`ReactFreshBabelPlugin does not get tripped by IFEs 1`] = `
--- ./packages/react-refresh/src/__tests__/ReactFresh-test.js	original
+++ ./packages/react-refresh/src/__tests__/ReactFresh-test.js	fixed
@@ -2304 +2304 @@
-          const tranformed = React.useMemo(() => val * 2, [val]);
+          const transformed = React.useMemo(() => val * 2, [val]);
@@ -2313 +2313 @@
-              {tranformed}
+              {transformed}
@@ -2337 +2337 @@
-            const tranformed = React.useMemo(() => val * 10, [val]);
+            const transformed = React.useMemo(() => val * 10, [val]);
@@ -2346 +2346 @@
-                {tranformed}
+                {transformed}
--- ./packages/react-devtools-timeline/src/view-base/Surface.js	original
+++ ./packages/react-devtools-timeline/src/view-base/Surface.js	fixed
@@ -53,2 +53,2 @@
- * Represents the canvas surface and a view heirarchy. A surface is also the
- * place where all interactions enter the view heirarchy.
+ * Represents the canvas surface and a view hierarchy. A surface is also the
+ * place where all interactions enter the view hierarchy.
--- ./packages/react-devtools-timeline/src/import-worker/index.js	original
+++ ./packages/react-devtools-timeline/src/import-worker/index.js	fixed
@@ -10 +10 @@
-// This file uses workerize to load ./importFile.worker as a webworker and instanciates it,
+// This file uses workerize to load ./importFile.worker as a webworker and instantiates it,
--- ./packages/react-devtools-timeline/src/import-worker/preprocessData.js	original
+++ ./packages/react-devtools-timeline/src/import-worker/preprocessData.js	fixed
@@ -112 +112 @@
-  // We only need to extact them once.
+  // We only need to extract them once.
@@ -286 +286 @@
-    // Keep track of curent event in case future ones overlap.
+    // Keep track of current event in case future ones overlap.
@@ -1043 +1043 @@
-  // flame chart events, we can futher deduce that the data is invalid and we
+  // flame chart events, we can further deduce that the data is invalid and we
--- ./packages/react-devtools-timeline/src/content-views/ReactMeasuresView.js	original
+++ ./packages/react-devtools-timeline/src/content-views/ReactMeasuresView.js	fixed
@@ -135 +135 @@
-        // and it looks bad if text flows underneath/behind these overlayed rects.
+        // and it looks bad if text flows underneath/behind these overlaid rects.
--- ./packages/react-devtools-timeline/src/content-views/utils/colors.js	original
+++ ./packages/react-devtools-timeline/src/content-views/utils/colors.js	fixed
@@ -37 +37 @@
-  // Hash algorithm for substrings is described in "Über die Komplexität der Multiplikation in
+  // Hash algorithm for substrings is described in "Über die Komplexität der Multiplication in
--- ./packages/react-dom-bindings/src/client/ReactDOMFloatClient.js	original
+++ ./packages/react-dom-bindings/src/client/ReactDOMFloatClient.js	fixed
@@ -211 +211 @@
-  // during commit after we have rendered. Instead we detatch any instances from
+  // during commit after we have rendered. Instead we detach any instances from
@@ -939 +939 @@
-      // the preload pathways. For instance if you have diffreent crossOrigin attributes for a preload
+      // the preload pathways. For instance if you have different crossOrigin attributes for a preload
@@ -1025 +1025 @@
-      // the preload pathways. For instance if you have diffreent crossOrigin attributes for a preload
+      // the preload pathways. For instance if you have different crossOrigin attributes for a preload
@@ -1115 +1115 @@
-          // This resoruce is a structured meta type with a parent.
+          // This resource is a structured meta type with a parent.
--- ./packages/react-dom-bindings/src/client/ReactDOMHostConfig.js	original
+++ ./packages/react-dom-bindings/src/client/ReactDOMHostConfig.js	fixed
@@ -773 +773 @@
-        // may still hold on to references to the previous fiber tree. We detatch them
+        // may still hold on to references to the previous fiber tree. We detach them
--- ./packages/react-dom-bindings/src/server/ReactDOMFloatServer.js	original
+++ ./packages/react-dom-bindings/src/server/ReactDOMFloatServer.js	fixed
@@ -491 +491 @@
-    // the preload pathways. For instance if you have diffreent crossOrigin attributes for a preload
+    // the preload pathways. For instance if you have different crossOrigin attributes for a preload
@@ -578 +578 @@
-    // the preload pathways. For instance if you have diffreent crossOrigin attributes for a preload
+    // the preload pathways. For instance if you have different crossOrigin attributes for a preload
--- ./packages/react-dom-bindings/src/server/fizz-instruction-set/ReactDOMFizzInstructionSet.js	original
+++ ./packages/react-dom-bindings/src/server/fizz-instruction-set/ReactDOMFizzInstructionSet.js	fixed
@@ -79 +79 @@
-    // If it is already loaded we don't return it as a depenendency since there is nothing
+    // If it is already loaded we don't return it as a dependency since there is nothing
--- ./packages/react-dom-bindings/src/shared/ReactDOMResourceValidation.js	original
+++ ./packages/react-dom-bindings/src/shared/ReactDOMResourceValidation.js	fixed
@@ -280 +280 @@
-          ' "as" prop must be of type "style". This most likely ocurred by rendering a preload link with an incorrect' +
+          ' "as" prop must be of type "style". This most likely occurred by rendering a preload link with an incorrect' +
@@ -360 +360 @@
-          ' "as" prop must be of type "script". This most likely ocurred by rendering a preload link with an incorrect' +
+          ' "as" prop must be of type "script". This most likely occurred by rendering a preload link with an incorrect' +
@@ -551 +551 @@
-          'A %s with %s "%s" recieved new props with different values from the props used' +
+          'A %s with %s "%s" received new props with different values from the props used' +
@@ -631 +631 @@
-            ' anonymouse CORS mode. To fix add an empty string, "anonymous", or any other string' +
+            ' anonymous CORS mode. To fix add an empty string, "anonymous", or any other string' +
@@ -639 +639 @@
-            ' anonymouse CORS mode. To fix use an empty string, "anonymous", or any other string' +
+            ' anonymous CORS mode. To fix use an empty string, "anonymous", or any other string' +
--- ./packages/react-dom-bindings/src/server/ReactDOMServerFormatConfig.js	original
+++ ./packages/react-dom-bindings/src/server/ReactDOMServerFormatConfig.js	fixed
@@ -128 +128 @@
-const scriptIntegirty = stringToPrecomputedChunk('" integrity="');
+const scriptIntegrity = stringToPrecomputedChunk('" integrity="');
@@ -195 +195 @@
-          scriptIntegirty,
+          scriptIntegrity,
@@ -215 +215 @@
-          scriptIntegirty,
+          scriptIntegrity,
@@ -235 +235 @@
-          scriptIntegirty,
+          scriptIntegrity,
@@ -2187 +2187 @@
-  errorMesssage: ?string,
+  errorMessage: ?string,
@@ -2205,5 +2205,5 @@
-    if (errorMesssage) {
-      writeChunk(destination, clientRenderedSuspenseBoundaryError1B);
-      writeChunk(
-        destination,
-        stringToChunk(escapeTextForBrowser(errorMesssage)),
+    if (errorMessage) {
+      writeChunk(destination, clientRenderedSuspenseBoundaryError1B);
+      writeChunk(
+        destination,
+        stringToChunk(escapeTextForBrowser(errorMessage)),
@@ -2545 +2545 @@
-      // santizing breaking out of strings and script tags
+      // sanitizing breaking out of strings and script tags
@@ -2567 +2567 @@
-      // santizing breaking out of strings and script tags
+      // sanitizing breaking out of strings and script tags
@@ -2979 +2979 @@
-    // Santized URLs
+    // Sanitized URLs
--- ./packages/react-dom-bindings/src/events/DOMEventProperties.js	original
+++ ./packages/react-dom-bindings/src/events/DOMEventProperties.js	fixed
@@ -90 +90 @@
-  'seeked',
+  'sought',
--- ./packages/react-dom-bindings/src/events/TopLevelEventTypes.js	original
+++ ./packages/react-dom-bindings/src/events/TopLevelEventTypes.js	fixed
@@ -76 +76 @@
-  | 'seeked'
+  | 'sought'
--- ./packages/react-dom-bindings/src/events/DOMEventNames.js	original
+++ ./packages/react-dom-bindings/src/events/DOMEventNames.js	fixed
@@ -91 +91 @@
-  | 'seeked'
+  | 'sought'
--- ./packages/react-dom-bindings/src/events/ReactDOMEventListener.js	original
+++ ./packages/react-dom-bindings/src/events/ReactDOMEventListener.js	fixed
@@ -443 +443 @@
-    case 'seeked':
+    case 'sought':
--- ./packages/react-dom-bindings/src/events/DOMPluginEventSystem.js	original
+++ ./packages/react-dom-bindings/src/events/DOMPluginEventSystem.js	fixed
@@ -198 +198 @@
-  'seeked',
+  'sought',
--- ./packages/react-server/src/ReactFizzClassComponent.js	original
+++ ./packages/react-server/src/ReactFizzClassComponent.js	fixed
@@ -452 +452 @@
-    if (typeof instance.componentWillRecieveProps === 'function') {
+    if (typeof instance.componentWillReceiveProps === 'function') {
@@ -455 +455 @@
-          'componentWillRecieveProps(). Did you mean componentWillReceiveProps()?',
+          'componentWillReceiveProps(). Did you mean componentWillReceiveProps()?',
@@ -459 +459 @@
-    if (typeof instance.UNSAFE_componentWillRecieveProps === 'function') {
+    if (typeof instance.UNSAFE_componentWillReceiveProps === 'function') {
@@ -462 +462 @@
-          'UNSAFE_componentWillRecieveProps(). Did you mean UNSAFE_componentWillReceiveProps()?',
+          'UNSAFE_componentWillReceiveProps(). Did you mean UNSAFE_componentWillReceiveProps()?',
--- ./packages/react-server/src/ReactServerStreamConfigBrowser.js	original
+++ ./packages/react-server/src/ReactServerStreamConfigBrowser.js	fixed
@@ -98 +98 @@
-  // in web streams there is no backpressure so we can alwas write more
+  // in web streams there is no backpressure so we can always write more
--- ./packages/react-server/src/ReactFizzServer.js	original
+++ ./packages/react-server/src/ReactFizzServer.js	fixed
@@ -229 +229 @@
-  // Returning null/undefined will cause a defualt error message in production
+  // Returning null/undefined will cause a default error message in production
@@ -1442 +1442 @@
-        // can allocate enough id slots to acommodate them. So we must exhaust
+        // can allocate enough id slots to accommodate them. So we must exhaust
--- ./scripts/shared/inlinedHostConfigs.js	original
+++ ./scripts/shared/inlinedHostConfigs.js	fixed
@@ -93 +93 @@
-      'react-dom/src/server/ReactDOMLegacyServerImpl.js', // not an entrypoint, but only usable in *Brower and *Node files
+      'react-dom/src/server/ReactDOMLegacyServerImpl.js', // not an entrypoint, but only usable in *Browser and *Node files
--- ./scripts/jest/typescript/jest.d.ts	original
+++ ./scripts/jest/typescript/jest.d.ts	fixed
@@ -19 +19 @@
-declare function xdescribe(name: string, fn: any): void;
+declare function describe(name: string, fn: any): void;
--- ./scripts/release/snapshot-test.snapshot	original
+++ ./scripts/release/snapshot-test.snapshot	fixed
@@ -220 +220 @@
- nextExpirationTimeToWorkOn:0,expirationTime:0,firstBatch:null,nextScheduledRoot:null};this._mountNode=a.stateNode=b;Nd(this.props.children,this._mountNode,this)};a.prototype.componentDidUpdate=function(a){var b=this.props;b.height===a.height&&b.width===a.width||this._surface.resize(+b.width,+b.height);Nd(this.props.children,this._mountNode,this);this._surface.render&&this._surface.render()};a.prototype.componentWillUnmount=function(){Nd(null,this._mountNode,this)};a.prototype.render=function(){var a=
+ nextExpirationTimeToWorkOn:0,expirationTime:0,firstBatch:null,nextScheduledRoot:null};this._mountNode=a.stateNode=b;And(this.props.children,this._mountNode,this)};a.prototype.componentDidUpdate=function(a){var b=this.props;b.height===a.height&&b.width===a.width||this._surface.resize(+b.width,+b.height);And(this.props.children,this._mountNode,this);this._surface.render&&this._surface.render()};a.prototype.componentWillUnmount=function(){And(null,this._mountNode,this)};a.prototype.render=function(){var a=
@@ -433,4 +433,4 @@
- var ci={createPortal:bi,findDOMNode:function(a){if(null==a)return null;if(1===a.nodeType)return a;var b=a._reactInternalFiber;void 0===b&&("function"===typeof a.render?t("188"):t("268",Object.keys(a)));a=nd(b);a=null===a?null:a.stateNode;return a},hydrate:function(a,b,c){return ai(null,a,b,!0,c)},render:function(a,b,c){return ai(null,a,b,!1,c)},unstable_renderSubtreeIntoContainer:function(a,b,c,d){null==a||void 0===a._reactInternalFiber?t("38"):void 0;return ai(a,b,c,!1,d)},unmountComponentAtNode:function(a){Zh(a)?
- void 0:t("40");return a._reactRootContainer?(Ph(function(){ai(null,null,a,!1,function(){a._reactRootContainer=null})}),!0):!1},unstable_createPortal:function(){return bi.apply(void 0,arguments)},unstable_batchedUpdates:Oh,unstable_interactiveUpdates:Qh,flushSync:function(a,b){X?t("187"):void 0;var c=Z;Z=!0;try{return rh(a,b)}finally{Z=c,Lh(1073741823,!1)}},unstable_flushControlled:function(a){var b=Z;Z=!0;try{rh(a)}finally{(Z=b)||X||Lh(1073741823,!1)}},__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED:{Events:[Ja,
--Ka,La,Ca.injectEventPluginsByName,qa,Ra,function(a){za(a,Qa)},Ib,Jb,Jd,Ea]},unstable_createRoot:function(a,b){Zh(a)?void 0:t("299","unstable_createRoot");return new Yh(a,!0,null!=b&&!0===b.hydrate)}};(function(a){var b=a.findFiberByHostInstance;return Ve(n({},a,{findHostInstanceByFiber:function(a){a=nd(a);return null===a?null:a.stateNode},findFiberByHostInstance:function(a){return b?b(a):null}}))})({findFiberByHostInstance:Ia,bundleType:0,version:"16.6.1-canary-b3d1a81a9",rendererPackageName:"react-dom"});
-+Ka,La,Ca.injectEventPluginsByName,qa,Ra,function(a){za(a,Qa)},Ib,Jb,Jd,Ea]},unstable_createRoot:function(a,b){Zh(a)?void 0:t("299","unstable_createRoot");return new Yh(a,!0,null!=b&&!0===b.hydrate)}};(function(a){var b=a.findFiberByHostInstance;return Ve(n({},a,{findHostInstanceByFiber:function(a){a=nd(a);return null===a?null:a.stateNode},findFiberByHostInstance:function(a){return b?b(a):null}}))})({findFiberByHostInstance:Ia,bundleType:0,version:"1.2.3",rendererPackageName:"react-dom"});
+ var ci={createPortal:bi,findDOMNode:function(a){if(null==a)return null;if(1===a.nodeType)return a;var b=a._reactInternalFiber;void 0===b&&("function"===typeof a.render?t("188"):t("268",Object.keys(a)));a=and(b);a=null===a?null:a.stateNode;return a},hydrate:function(a,b,c){return ai(null,a,b,!0,c)},render:function(a,b,c){return ai(null,a,b,!1,c)},unstable_renderSubtreeIntoContainer:function(a,b,c,d){null==a||void 0===a._reactInternalFiber?t("38"):void 0;return ai(a,b,c,!1,d)},unmountComponentAtNode:function(a){Zh(a)?
+ void 0:t("40");return a._reactRootContainer?(Ph(function(){ai(null,null,a,!1,function(){a._reactRootContainer=null})}),!0):!1},unstable_createPortal:function(){return bi.apply(void 0,arguments)},unstable_batchedUpdates:Oh,unstable_interactiveUpdates:Qh,flushSync:function(a,b){X?t("187"):void 0;var c=Z;Z=!0;try{return rh(a,b)}finally{Z=c,Lh(1073741823,!1)}},unstable_flushControlled:function(a){var b=Z;Z=!0;try{rh(a)}finally{(Z=b)||X||Lh(1073741823,!1)}},__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED:{Events:[Ja,
+-Ka,La,Ca.injectEventPluginsByName,qa,Ra,function(a){za(a,Qa)},Ib,Jb,Jd,Ea]},unstable_createRoot:function(a,b){Zh(a)?void 0:t("299","unstable_createRoot");return new Yh(a,!0,null!=b&&!0===b.hydrate)}};(function(a){var b=a.findFiberByHostInstance;return Ve(n({},a,{findHostInstanceByFiber:function(a){a=and(a);return null===a?null:a.stateNode},findFiberByHostInstance:function(a){return b?b(a):null}}))})({findFiberByHostInstance:Ia,bundleType:0,version:"16.6.1-canary-b3d1a81a9",rendererPackageName:"react-dom"});
++Ka,La,Ca.injectEventPluginsByName,qa,Ra,function(a){za(a,Qa)},Ib,Jb,Jd,Ea]},unstable_createRoot:function(a,b){Zh(a)?void 0:t("299","unstable_createRoot");return new Yh(a,!0,null!=b&&!0===b.hydrate)}};(function(a){var b=a.findFiberByHostInstance;return Ve(n({},a,{findHostInstanceByFiber:function(a){a=and(a);return null===a?null:a.stateNode},findFiberByHostInstance:function(a){return b?b(a):null}}))})({findFiberByHostInstance:Ia,bundleType:0,version:"1.2.3",rendererPackageName:"react-dom"});
@@ -780 +780 @@
- var $d={create:function(a,b){var c=Nd.createNodeMock,d=!1;"object"===typeof b&&null!==b&&("function"===typeof b.createNodeMock&&(c=b.createNodeMock),!0===b.unstable_isConcurrent&&(d=!0));var e={children:[],createNodeMock:c,tag:"CONTAINER"},g=eb(e,d,!1);null==g?n("215"):void 0;Hd(a,g,null,null);a={root:void 0,toJSON:function(){if(null==g||null==g.current||null==e||0===e.children.length)return null;if(1===e.children.length)return Od(e.children[0]);var a=null;if(e.children&&e.children.length)for(var b=
+ var $d={create:function(a,b){var c=And.createNodeMock,d=!1;"object"===typeof b&&null!==b&&("function"===typeof b.createNodeMock&&(c=b.createNodeMock),!0===b.unstable_isConcurrent&&(d=!0));var e={children:[],createNodeMock:c,tag:"CONTAINER"},g=eb(e,d,!1);null==g?n("215"):void 0;Hd(a,g,null,null);a={root:void 0,toJSON:function(){if(null==g||null==g.current||null==e||0===e.children.length)return null;if(1===e.children.length)return Od(e.children[0]);var a=null;if(e.children&&e.children.length)for(var b=
--- ./fixtures/nesting/src/legacy/createLegacyRoot.js	original
+++ ./fixtures/nesting/src/legacy/createLegacyRoot.js	fixed
@@ -20 +20 @@
-          we woud instead import {ReactReduxContext} from 'react-redux'
+          we would instead import {ReactReduxContext} from 'react-redux'
--- ./fixtures/nesting/README.md	original
+++ ./fixtures/nesting/README.md	fixed
@@ -71 +71 @@
-The `scripts` in the root `package.json` are set up so that when you run `npm install` in it, it also runs `npm intall` in both `src/legacy` and `src/modern` folders.
+The `scripts` in the root `package.json` are set up so that when you run `npm install` in it, it also runs `npm install` in both `src/legacy` and `src/modern` folders.
--- ./CHANGELOG.md	original
+++ ./CHANGELOG.md	fixed
@@ -1499 +1499 @@
-- Add-Ons: `TestUtils.Simulate()` now prints a helpful message if you attempt to use it with shallow rendering. ([@conorhastings](https://github.com/conorhastings) in [#5358](https://github.com/facebook/react/pull/5358))
+- Add-Owns: `TestUtils.Simulate()` now prints a helpful message if you attempt to use it with shallow rendering. ([@conorhastings](https://github.com/conorhastings) in [#5358](https://github.com/facebook/react/pull/5358))
@@ -1520 +1520 @@
-- Add-Ons: ReactPerf no longer instruments adding or removing an event listener because they don’t really touch the DOM due to event delegation. ([@antoaravinth](https://github.com/antoaravinth) in [#5209](https://github.com/facebook/react/pull/5209))
+- Add-Owns: ReactPerf no longer instruments adding or removing an event listener because they don’t really touch the DOM due to event delegation. ([@antoaravinth](https://github.com/antoaravinth) in [#5209](https://github.com/facebook/react/pull/5209))
@@ -1636,4 +1636,4 @@
-- Add-Ons: Due to the DOM node refs change mentioned above, `TestUtils.findAllInRenderedTree` and related helpers are no longer able to take a DOM component, only a custom component.
-- The `props` object is now frozen, so mutating props after creating a component element is no longer supported. In most cases, [`React.cloneElement`](https://reactjs.org/docs/react-api.html#cloneelement) should be used instead. This change makes your components easier to reason about and enables the compiler optimizations mentioned above.
-- Plain objects are no longer supported as React children; arrays should be used instead. You can use the [`createFragment`](https://reactjs.org/docs/create-fragment.html) helper to migrate, which now returns an array.
-- Add-Ons: `classSet` has been removed. Use [classnames](https://github.com/JedWatson/classnames) instead.
+- Add-Owns: Due to the DOM node refs change mentioned above, `TestUtils.findAllInRenderedTree` and related helpers are no longer able to take a DOM component, only a custom component.
+- The `props` object is now frozen, so mutating props after creating a component element is no longer supported. In most cases, [`React.cloneElement`](https://reactjs.org/docs/react-api.html#cloneelement) should be used instead. This change makes your components easier to reason about and enables the compiler optimizations mentioned above.
+- Plain objects are no longer supported as React children; arrays should be used instead. You can use the [`createFragment`](https://reactjs.org/docs/create-fragment.html) helper to migrate, which now returns an array.
+- Add-Owns: `classSet` has been removed. Use [classnames](https://github.com/JedWatson/classnames) instead.
@@ -1648,2 +1648,2 @@
-- Add-Ons: `cloneWithProps` is now deprecated. Use [`React.cloneElement`](https://reactjs.org/docs/react-api.html#cloneelement) instead (unlike `cloneWithProps`, `cloneElement` does not merge `className` or `style` automatically; you can merge them manually if needed).
-- Add-Ons: To improve reliability, `CSSTransitionGroup` will no longer listen to transition events. Instead, you should specify transition durations manually using props such as `transitionEnterTimeout={500}`.
+- Add-Owns: `cloneWithProps` is now deprecated. Use [`React.cloneElement`](https://reactjs.org/docs/react-api.html#cloneelement) instead (unlike `cloneWithProps`, `cloneElement` does not merge `className` or `style` automatically; you can merge them manually if needed).
+- Add-Owns: To improve reliability, `CSSTransitionGroup` will no longer listen to transition events. Instead, you should specify transition durations manually using props such as `transitionEnterTimeout={500}`.
@@ -1661,5 +1661,5 @@
-- React DOM now supports these media events on `audio` and `video` tags: `onAbort`, `onCanPlay`, `onCanPlayThrough`, `onDurationChange`, `onEmptied`, `onEncrypted`, `onEnded`, `onError`, `onLoadedData`, `onLoadedMetadata`, `onLoadStart`, `onPause`, `onPlay`, `onPlaying`, `onProgress`, `onRateChange`, `onSeeked`, `onSeeking`, `onStalled`, `onSuspend`, `onTimeUpdate`, `onVolumeChange`, `onWaiting`.
-- Many small performance improvements have been made.
-- Many warnings show more context than before.
-- Add-Ons: A [`shallowCompare`](https://github.com/facebook/react/pull/3355) add-on has been added as a migration path for `PureRenderMixin` in ES6 classes.
-- Add-Ons: `CSSTransitionGroup` can now use [custom class names](https://github.com/facebook/react/blob/48942b85/docs/docs/10.1-animation.md#custom-classes) instead of appending `-enter-active` or similar to the transition name.
+- React DOM now supports these media events on `audio` and `video` tags: `onAbort`, `onCanPlay`, `onCanPlayThrough`, `onDurationChange`, `onEmptied`, `onEncrypted`, `onEnded`, `onError`, `onLoadedData`, `onLoadedMetadata`, `onLoadStart`, `onPause`, `onPlay`, `onPlaying`, `onProgress`, `onRateChange`, `onSought`, `onSeeking`, `onStalled`, `onSuspend`, `onTimeUpdate`, `onVolumeChange`, `onWaiting`.
+- Many small performance improvements have been made.
+- Many warnings show more context than before.
+- Add-Owns: A [`shallowCompare`](https://github.com/facebook/react/pull/3355) add-on has been added as a migration path for `PureRenderMixin` in ES6 classes.
+- Add-Owns: `CSSTransitionGroup` can now use [custom class names](https://github.com/facebook/react/blob/48942b85/docs/docs/10.1-animation.md#custom-classes) instead of appending `-enter-active` or similar to the transition name.
@@ -1681,2 +1681,2 @@
-- Add-Ons: When using the test utils, `Simulate.mouseEnter` and `Simulate.mouseLeave` now work.
-- Add-Ons: ReactTransitionGroup now correctly handles multiple nodes being removed simultaneously.
+- Add-Owns: When using the test utils, `Simulate.mouseEnter` and `Simulate.mouseLeave` now work.
+- Add-Owns: ReactTransitionGroup now correctly handles multiple nodes being removed simultaneously.
@@ -1712 +1712 @@
-### React with Add-ons
+### React with Add-owns
@@ -1738 +1738 @@
-### React with Add-Ons
+### React with Add-Owns
@@ -1758 +1758 @@
-### React with Add-Ons
+### React with Add-Owns
@@ -1801 +1801 @@
-### React with Add-Ons
+### React with Add-Owns
--- ./fixtures/attribute-behavior/src/attributes.js	original
+++ ./fixtures/attribute-behavior/src/attributes.js	fixed
@@ -428 +428 @@
-  {name: 'defaultValuE', tagName: 'input', read: getAttribute('defaultValuE')},
+  {name: 'defaultValueE', tagName: 'input', read: getAttribute('defaultValueE')},
--- ./fixtures/attribute-behavior/README.md	original
+++ ./fixtures/attribute-behavior/README.md	fixed
@@ -16 +16 @@
-them are invalid or mis-capitalized or mixed up versions of real ones.
+them are invalid or miss-capitalized or mixed up versions of real ones.
--- ./fixtures/dom/src/components/fixtures/media-events/index.js	original
+++ ./fixtures/dom/src/components/fixtures/media-events/index.js	fixed
@@ -25 +25 @@
-      onSeeked: false,
+      onSought: false,
--- ./AUTHORS	original
+++ ./AUTHORS	fixed
@@ -653,478 +653,478 @@
-Mathieu Savy <savy.mathieu@gmail.com>
-Matias Singers <mail@matiassingers.com>
-Matsunoki <himkt@klis.tsukuba.ac.jp>
-Matt Brookes <matt@brookes.net>
-Matt Dunn-Rankin <mdunnrankin@gmail.com>
-Matt Harrison <mt.harrison86@gmail.com>
-Matt Huggins <matt.huggins@gmail.com>
-Matt Stow <matt.stow@foxsports.com.au>
-Matt Zabriskie <mzabriskie@gmail.com>
-Matthew Dapena-Tretter <m@tthewwithanm.com>
-Matthew Herbst <mherbst@chegg.com>
-Matthew Hodgson <matthew@matrix.org>
-Matthew Johnston <matthewjohnston4@outlook.com>
-Matthew King <mking@users.noreply.github.com>
-Matthew Looi <looi.matthew@gmail.com>
-Matthew Miner <matthew@matthewminer.com>
-Matthew Shotton <matthew.shotton@bbc.co.uk>
-Matthias Le Brun <mlbli@me.com>
-Matti Nelimarkka <matti.nelimarkka@hiit.fi>
-Mattijs Kneppers <mattijs@arttech.nl>
-Max Donchenko <maxx.donchenko@gmail.com>
-Max F. Albrecht <1@178.is>
-Max Heiber <max.heiber@gmail.com>
-Max Stoiber <contact@mstoiber.com>
-Maxi Ferreira <charca@gmail.com>
-Maxim Abramchuk <MaximAbramchuck@gmail.com>
-Maxwel D'souza <maxellusionist@gmail.com>
-Merrick Christensen <merrick.christensen@gmail.com>
-Mert Kahyaoğlu <mertkahyaoglu93@gmail.com>
-Michael Chan <mijoch@gmail.com>
-Michael Jackson <mjijackson@gmail.com>
-Michael McDermott <michael@mgmcdermott.com>
-Michael O'Brien <mcobrien@users.noreply.github.com>
-Michael Randers-Pehrson <michael.rp@gmail.com>
-Michael Ridgway <mridgway@yahoo-inc.com>
-Michael Sinov <sihaelov@gmail.com>
-Michael Terry <michael@michaelterry.org>
-Michael Warner <MichaelJWarner@hotmail.com>
-Michael Wiencek <mwtuea@gmail.com>
-Michael Ziwisky <mikezx@gmail.com>
-Michal Srb <xixixao@seznam.cz>
-Michał Ordon <designorant@users.noreply.github.com>
-Michał Pierzchała <thymikee@gmail.com>
-Michele Bertoli <MicheleBertoli@users.noreply.github.com>
-Michelle Todd <himichelletodd@gmail.com>
-Michiya <mhibino@users.noreply.github.com>
-Mihai Parparita <mihai.parparita@gmail.com>
-Mike D Pilsbury <mike.pilsbury@gmail.com>
-Mike Groseclose <mike.groseclose@gmail.com>
-Mike Nordick <mnordick>
-Mikhail Osher <yo@miraage.io>
-Mikolaj Dadela <mikolaj.dadela@hgv-online.de>
-Miles Johnson <mileswjohnson@gmail.com>
-Miller Medeiros <miller@millermedeiros.com>
-Minwe LUO <minwe@yunshipei.com>
-Minwei Xu <faceswilliam@gmail.com>
-Miorel Palii <miorel@fb.com>
-Mitchel Humpherys <mitch.special@gmail.com>
-Mitermayer Reis <mitermayer.reis@gmail.com>
-Moacir Rosa <paulomoacir.junior@gmail.com>
-Mojtaba Dashtinejad <mojtaba@gmail.com>
-Morhaus <alexandre.kirszenberg@gmail.com>
-Moshe Kolodny <kolodny.github@gmail.com>
-Mouad Debbar <mdebbar@fb.com>
-Murad <rogozhnikoff@users.noreply.github.com>
-Murray M. Moss <murray@mmoss.name>
-Murtaza Haveliwala <murtaza.sh@gmail.com>
-NE-SmallTown <ne_smalltown@163.com>
-Nadeesha Cabral <nadeesha.cabral@gmail.com>
-Naman Goel <naman34@gmail.com>
-Nate <nchristensen@deseretdigital.com>
-Nate Hunzaker <nate.hunzaker@gmail.com>
-Nate Lee <nathaniel.jy.lee88@gmail.com>
-Nate Norberg <natenorberg@gmail.com>
-Nathan Hardy <nhardy@users.noreply.github.com>
-Nathan Smith <NogsMPLS@users.noreply.github.com>
-Nathan White <nw@nwhite.net>
-Nee <944316342@qq.com>
-Neo <nihgwu@live.com>
-Neri Marschik <marschik_neri@cyberagent.co.jp>
-NestorTejero <webeafix@gmail.com>
-Nguyen Truong Duy <truongduy134@yahoo.com>
-Nicholas Bergson-Shilcock <me@nicholasbs.net>
-Nicholas Clawson <nickclaw@users.noreply.github.com>
-Nick Balestra <nickbalestra@users.noreply.github.com>
-Nick Fitzgerald <fitzgen@gmail.com>
-Nick Gavalas <njg57@cornell.edu>
-Nick Kasten <kastencode@gmail.com>
-Nick Merwin <nick@lemurheavy.com>
-Nick Presta <nick@nickpresta.ca>
-Nick Raienko <enaqxx@gmail.com>
-Nick Thompson <ncthom91@gmail.com>
-Nick Williams <WickyNilliams@users.noreply.github.com>
-Nik Nyby <nnyby@columbia.edu>
-Nikita Lebedev <bloomber111@gmail.com>
-Niklas Boström <nbostrom@gmail.com>
-Nikoloz Buligini <nbuligini11@gmail.com>
-Nima Jahanshahi <nbjahan@gmail.com>
-Ning Xia <ning-github@users.noreply.github.com>
-Niole Nelson <niolenelson@gmail.com>
-Nolan Lawson <nolan@nolanlawson.com>
-Nuno Campos <nuno@crowdprocess.com>
-OJ Kwon <kwon.ohjoong@gmail.com>
-Oiva Eskola <oiva.eskola@gmail.com>
-Oleg <o.yanchinskiy@gmail.com>
-Oleksii Markhovskyi <olexiy.markhovsky@gmail.com>
-Oliver Zeigermann <oliver.zeigermann@gmail.com>
-Olivier Tassinari <Olivier.tassinari@gmail.com>
-Omid Hezaveh <omidfi@users.noreply.github.com>
-Oscar Bolmsten <oscar-b@users.noreply.github.com>
-Oskari Mantere <osku.mantere@gmail.com>
-Owen Coutts <owenc@fb.com>
-Pablo Lacerda de Miranda <pablolm@yahoo-inc.com>
-Paolo Moretti <moretti@users.noreply.github.com>
-Pascal Hartig <passy@twitter.com>
-Patrick <info@telepark.de>
-Patrick Finnigan <patrick.k.finnigan@gmail.com>
-Patrick Laughlin <patrick@laughl.info>
-Patrick Stapleton <github@gdi2290.com>
-Paul Benigeri <me@benigeri.com>
-Paul Harper <benekastah@gmail.com>
-Paul Kehrer <paul.l.kehrer@gmail.com>
-Paul Manta <paulmanta@users.noreply.github.com>
-Paul O’Shannessy <paul@oshannessy.com>
-Paul Seiffert <paul.seiffert@gmail.com>
-Paul Shen <paul@mnml0.com>
-Pedro Nauck <pedronauck@gmail.com>
-Pete Hunt <floydophone@gmail.com>
-Peter Blazejewicz <peter.blazejewicz@gmail.com>
-Peter Cottle <pcottle@fb.com>
-Peter Jaros <peter.a.jaros@gmail.com>
-Peter Newnham <peter.newnham@appsbroker.com>
-Peter Ruibal <ruibalp@gmail.com>
-Petri Lehtinen <petri@digip.org>
-Petri Lievonen <plievone@cc.hut.fi>
-Phil Quinn <philquinn90@gmail.com>
-Phil Rajchgot <tophil@outlook.com>
-Philip Jackson <p-jackson@live.com>
-Philipp Spieß <hello@philippspiess.com>
-Pieter De Baets <pieter.debaets@gmail.com>
-Pieter Vanderwerff <me@pieter.io>
-Piotr Czajkowski <czajkowski.piotr@gmail.com>
-Piper Chester <piperchester@gmail.com>
-Pontus Abrahamsson <info@wdlinkoping.se>
-Pouja Nikray <poujanik@gmail.com>
-Prathamesh Sonpatki <csonpatki@gmail.com>
-Prayag Verma <prayag.verma@gmail.com>
-Preston Parry <ClimbsRocks@users.noreply.github.com>
-Qin Junwen <kjj10@163.com>
-RSG <Radi123@users.noreply.github.com>
-Rachel D. Cartwright <stormchica@gmail.com>
-Rafael <rafael.garcia@clever.com>
-Rafael Angeline <me@rafaelangeline.com>
-Rafal Dittwald <rafal.dittwald@gmail.com>
-Ragnar Þór Valgeirsson <ragnar.valgeirsson@gmail.com>
-Rahul Gupta <rahulgupta4@practo.com>
-Rainer Oviir <roviir@gmail.com>
-Raito Bezarius <masterancpp@gmail.com>
-Rajat Sehgal <rajatsehgal1988@gmail.com>
-Rajiv Tirumalareddy <rajivtreddy@gmail.com>
-Ram Kaniyur <quadrupleslap@users.noreply.github.com>
-Randall Randall <randall@randallsquared.com>
-Ray <ray@tomo.im>
-Ray Dai <exiadbq@gmail.com>
-Raymond Ha <raymond@shraymonks.com>
-Reed Loden <reed@reedloden.com>
-Remko Tronçon <git@el-tramo.be>
-Ricardo <ddrjm@users.noreply.github.com>
-Rich Harris <richard.a.harris@gmail.com>
-Richard <riscarrott@googlemail.com>
-Richard D. Worth <rdworth@gmail.com>
-Richard Feldman <richard.t.feldman@gmail.com>
-Richard Kho <hello@richardkho.com>
-Richard Littauer <richard.littauer@gmail.com>
-Richard Livesey <Livesey7@hotmail.co.uk>
-Richard Maisano <rickmaisano@gmail.com>
-Richard Roncancio <batusai513@msn.com>
-Richard Wood <rwoodnz@gmail.com>
-Richie Thomas <rickthomas1980@gmail.com>
-Rick Beerendonk <rick@beerendonk.com>
-Rick Ford <rickfordrick@gmail.com>
-Riley Tomasek <riley.tomasek@gmail.com>
-Rob Arnold <robarnold@cs.cmu.edu>
-Robert Binna <rbinna@gmail.com>
-Robert Chang <cht8687@gmail.com>
-Robert Haritonov <r@rhr.me>
-Robert Kielty <rob.kielty@gmail.com>
-Robert Knight <robert.knight@mendeley.com>
-Robert Martin <rmartin@rmart.in>
-Robert Sedovsek <robert.sedovsek@gmail.com>
-Robin Berjon <robin@berjon.com>
-Robin Frischmann <robin@rofrischmann.de>
-Robin Ricard <ricard.robin@gmail.com>
-Roderick Hsiao <roderickhsiao@users.noreply.github.com>
-Rodrigo Pombo <pombopombopombo@gmail.com>
-Rohan Nair <rohan@objectiveiq.com>
-Roman Liutikov <roman01la@romanliutikov.com>
-Roman Matusevich <roma.matusevich@gmail.com>
-Roman Pominov <rpominov+github@gmail.com>
-Roman Vanesyan <roman.vanesyan@gmail.com>
-Rui Araújo <ruka.araujo@gmail.com>
-Russ <russwirtz@gmail.com>
-Ryan Lahfa <masterancpp@gmail.com>
-Ryan Seddon <seddon.ryan@gmail.com>
-Ryo Shibayama <j02521@gmail.com>
-Sahat Yalkabov <sakhat@gmail.com>
-Saif Hakim <saif@benchling.com>
-Saiichi Hashimoto <saiichihashimoto@gmail.com>
-Sakina Crocker <sakinac@gmail.com>
-Sam Balana <sam.balana@ardentacademy.com>
-Sam Beveridge <sbeveridge@saltstack.com>
-Sam Saccone <samccone@gmail.com>
-Sam Selikoff <sam.selikoff@gmail.com>
-Samer Buna <samerbuna@users.noreply.github.com>
-Samuel <savepointsam@gmail.com>
-Samuel Hapák <samuel.hapak@gmail.com>
-Samuel Reed <samuel.trace.reed@gmail.com>
-Samuel Scheiderich <samsch@users.noreply.github.com>
-Samy Al Zahrani <samy@sadeem.net>
-Sander Spies <sandermail@gmail.com>
-Sasha Aickin <xander76@yahoo.com>
-Sassan Haradji <sassanh@gmail.com>
-Satoshi Nakajima <satoshi.nakajima@gmail.com>
-Scott <scottdomes@gmail.com>
-Scott Burch <scott@bulldoginfo.com>
-Scott Feeney <scott@oceanbase.org>
-Sean Gransee <sean.gransee@gmail.com>
-Sean Kinsey <oyvind@fb.com>
-Sean Smith <sean.smith.2009@gmail.com>
-Seba <sebaest77@gmail.com>
-Sebastian Markbåge <sebastian@calyptus.eu>
-Sebastian McKenzie <sebmck@gmail.com>
-Senin Roman <Rastopyr@gmail.com>
-Seoh Char <devthewild@gmail.com>
-Sercan Eraslan <sercan.eraslan@sahibinden.com>
-Serg <undrdog@yandex.ru>
-Sergey Generalov <sergey@genbit.ru>
-Sergey Rubanov <chi187@gmail.com>
-Seyi Adebajo <hello@seyinanigans.com>
-Shane O'Sullivan <shaneosullivan1@gmail.com>
-Shaun Trennery <shaun.trennery@gmail.com>
-ShihChi Huang <hhuang@netflix.com>
-Shim Won <marocchino@gmail.com>
-Shinnosuke Watanabe <snnskwtnb@gmail.com>
-Shogun Sea <shogunsea08@gmail.com>
-Shota Kubota <kubosho@users.noreply.github.com>
-Shripad K <assortmentofsorts@gmail.com>
-Shubheksha Jalan <jshubheksha@gmail.com>
-Shuhei Kagawa <shuhei.kagawa@gmail.com>
-Sibi <psibi2000@gmail.com>
-Simen Bekkhus <sbekkhus91@gmail.com>
-Simon Højberg <r.hackr@gmail.com>
-Simon Welsh <simon@simon.geek.nz>
-Simone Vittori <hello@simonewebdesign.it>
-Skasi <skasski@gmx.at>
-Snowmanzzz(Zhengzhong Zhao) <zhengzhongzhao@gmail.com>
-Soichiro Kawamura <mail@w-st.com>
-Soo Jae Hwang <misoguy1985@gmail.com>
-Sophia <szensius@gmail.com>
-Sophia Westwood <sophia@quip.com>
-Sophie Alpert <git@sophiebits.com>
-Sota Ohara <ohrst.18@gmail.com>
-Spen Taylor <spen_@hotmail.co.uk>
-Spencer Ahrens <sahrens@users.noreply.github.com>
-Spencer Handley <spencerhandley@gmail.com>
-Sriram Thiagarajan <sri.sjc@gmail.com>
-Stefan Dombrowski <sdo451@gmail.com>
-Stephen John Sorensen <spudly@users.noreply.github.com>
-Stephen Murphy <smurphy3@apple.com>
-Stephie <Stephie@users.noreply.github.com>
-Sterling Cobb <sterlingcobb@gmail.com>
-Steve Baker <_steve_@outlook.com>
-Steve Mao <maochenyan@gmail.com>
-Steven Luscher <react@steveluscher.com>
-Steven Syrek <sjsyrek@users.noreply.github.com>
-Steven Vachon <contact@svachon.com>
-Stolenkid <stolen.kid7@gmail.com>
-Stoyan Stefanov <ssttoo@ymail.com>
-Stuart Harris <stuart.harris@red-badger.com>
-SunHuawei <stonesun@aliyun.com>
-Sundeep Malladi <sundeep.malladi@gmail.com>
-Sung Won Cho <mikeswcho@gmail.com>
-Sunny Juneja <me@sunnyjuneja.com>
-Sunny Ripert <sunny@sunfox.org>
-Superlaziness <shemyakin@me.com>
-Sven Helmberger <fforw@gmx.de>
-Sverre Johansen <sverre.johansen@gmail.com>
-Swaroop SM <swaroop.striker@gmail.com>
-Sébastien Lorber <lorber.sebastien@gmail.com>
-Sławomir Laskowski <laskowski.box@gmail.com>
-Taegon Kim <gonom9@gmail.com>
-Taeho Kim <dittos@gmail.com>
-Taehwan, No <taehwanno.dev@gmail.com>
-Tanase Hagi <TanaseHagi@users.noreply.github.com>
-Tanner <devtanc@gmail.com>
-Tay Yang Shun <tay.yang.shun@gmail.com>
-Ted Kim <ted@vcnc.co.kr>
-TedPowers <TedPowers@users.noreply.github.com>
-Tengfei Guo <terryr3rd@yeah.net>
-Teodor Szente <teodor98sz@gmail.com>
-Tetsuharu OHZEKI <saneyuki.s.snyk@gmail.com>
-Tetsuya Hasegawa <tetsuya.chicago@gmail.com>
-Thibaut Rizzi <zoom@rhizom.fr>
-Thomas Aylott <oblivious@subtlegradient.com>
-Thomas Boyt <thomas.boyt@venmo.com>
-Thomas Broadley <buriedunderbooks@hotmail.com>
-Thomas Reggi <socialtr@gmail.com>
-Thomas Röggla <t.roggla@cwi.nl>
-Thomas Shaddox <thomas@heyzap.com>
-Thomas Shafer <thomasjshafer@gmail.com>
-ThomasCrvsr <crevoisier.thomas@gmail.com>
-Tiago Fernandez <tiago.fernandez@gmail.com>
-Tienchai Wirojsaksaree <tienchai@fb.com>
-Tim Routowicz <troutowicz@gmail.com>
-Tim Schaub <tschaub@users.noreply.github.com>
-Timothy Yung <yungsters@gmail.com>
-Timur Carpeev <timuric@users.noreply.github.com>
-Tobias Reiss <tag+github@basecode.de>
-Tom Duncalf <tom@tomduncalf.com>
-Tom Gasson <tom.gasson@arup.com>
-Tom Haggie <thaggie@gmail.com>
-Tom Hauburger <thauburger@gmail.com>
-Tom MacWright <tom@macwright.org>
-Tom Occhino <tomocchino@gmail.com>
-Tomasz Kołodziejski <tkolodziejski@gmail.com>
-Tomoya Suzuki <tmysz.dev@gmail.com>
-Tomáš Hromada <Gyfis@seznam.cz>
-Tony Rossi <tony@iamrossi.com>
-Tony Spiro <tspiro@tonyspiro.com>
-Toru Kobayashi <koba0004@gmail.com>
-Trevor Smith <trevorlynnsmith@gmail.com>
-Trinh Hoang Nhu <trinhhoangnhu@gmail.com>
-Troy DeMonbreun <github@troyd.net>
-Tsung Hung <thung@me.com>
-Tyler Brock <tyler.brock@gmail.com>
-Tyler Buchea <tyler@buchea.com>
-Tyler Deitz <tylerdeitz@gmail.com>
-Ujjwal Ojha <ojhaujjwal@users.noreply.github.com>
-Uladzimir Havenchyk <uladzimir@toptal.com>
-Usman <syedusmanajmal@gmail.com>
-Ustin Zarubin <ustin.zarubin@campusbellhops.com>
-Vadim Chernysh <chernysh.vadim@gmail.com>
-Valentin Shergin <valentin@shergin.com>
-Van der Auwermeulen Grégoire <gregoirevandera@gmail.com>
-Varayut Lerdkanlayanawat <l.varayut@gmail.com>
-Varun Bhuvanendran <varunbhuvanendran@users.noreply.github.com>
-Varun Rau <varunrau@gmail.com>
-Vasiliy Loginevskiy <Yeti.or@gmail.com>
-Vedat Mahir YILMAZ <mahir@vedatmahir.com>
-Veljko Tornjanski <tornjanski.veljko@gmail.com>
-Vesa Laakso <laakso.vesa@gmail.com>
-Victor Alvarez <v.alvarez312@gmail.com>
-Victor Homyakov <vkhomyackov@gmail.com>
-Victor Koenders <victor.koenders@gmail.com>
-Victoria Quirante <victoria.quirante@gmail.com>
-Vikash Agrawal <vikashagrawal1990@gmail.com>
-Ville Immonen <ville.immonen@iki.fi>
-Vincent Riemer <vincentriemer@gmail.com>
-Vincent Siao <vincent@asana.com>
-Vincent Taing <taing.vincent@gmail.com>
-Vipul A M <vipulnsward@gmail.com>
-Vitaliy Potapov <noginsk@rambler.ru>
-Vitaly Kramskikh <vkramskikh@gmail.com>
-Vitor Balocco <vitorbal@gmail.com>
-Vjeux <vjeuxx@gmail.com>
-Vladimir Kovpak <cn007b@gmail.com>
-Vladimir Tikunov <vtikunov@yandex.ru>
-Volkan Unsal <spocksplanet@gmail.com>
-Wander Wang <wander.wang@ismole.com>
-Wayne Larsen <wayne@larsen.st>
-Weizenlol <winliveweiz@gmail.com>
-Whien <sal95610@gmail.com>
-WickyNilliams <WickyNilliams@MBA>
-Will Myers <will@usebutton.com>
-William Hoffmann <whoffpen@gmail.com>
-Wincent Colaiuta <win@wincent.com>
-Wout Mertens <Wout.Mertens@gmail.com>
-Xavier Morel <xmo-odoo@users.noreply.github.com>
-XuefengWu <benewu@gmail.com>
-Yakov Dalinchuk <murashki@users.noreply.github.com>
-Yan Li <mangakjd@gmail.com>
-Yasar icli <hello@yasaricli.com>
-Yaxian <yaxian.gu@gmail.com>
-YouBao Nong <noyobo@gmail.com>
-Yuichi Hagio <yhagio87@gmail.com>
-Yura Chuchola <smhfanda@gmail.com>
-Yuriy Dybskiy <yuriy@dybskiy.com>
-Yusong Liu <lysnku@gmail.com>
-Yutaka Nakajima <nakazye@gmail.com>
-Yuval Dekel <thedekel@fb.com>
-Zac Braddy <zacharybraddy@gmail.com>
-Zac Smith <billyzacsmith@gmail.com>
-Zach Bruggeman <mail@bruggie.com>
-Zach Ramaekers <zramaekers@gmail.com>
-Zacharias <zachasme@users.noreply.github.com>
-Zeke Sikelianos <zeke@sikelianos.com>
-Zhangjd <zhang.jd@qq.com>
-adraeth <jerzy.mirecki@gmail.com>
-ankitml <ankitml@gmail.com>
-arush <arush@ilovebrands.net>
-bel3atar <bel3atar@aol.com>
-brafdlog <brafdlog@gmail.com>
-brillout <brillout@users.noreply.github.com>
-chen <kikyous@163.com>
-chocolateboy <chocolate@cpan.org>
-cjshawMIT <cjshaw@mit.edu>
-clariroid <clarinette.uranus@gmail.com>
-claudiopro <claudio.procida@gmail.com>
-cloudy1 <mohaned@cloudypedia.com>
-comerc <comerc@users.noreply.github.com>
-cutbko <kutsenko.eugene@hotmail.com>
-davidxi <davidgraycn@gmail.com>
-dfrownfelter <davidrfrownfelter@gmail.com>
-djskinner <skinner@destiny-denied.co.uk>
-dongmeng.ldm <dongmeng.ldm@alibaba-inc.com>
-everdimension <everdimension@gmail.com>
-gillchristian <gillchristiang@gmail.com>
-gitanupam <anupamjain@gmail.com>
-guoyong yi <451417726@qq.com>
-hanumanthan <hanu.sas@gmail.com>
-hao.huang <hao.huang@aliyun.com>
-hjmoss <hjmoss@users.noreply.github.com>
-hkal <hkal@users.noreply.github.com>
-iamchenxin <iamchenxin@gmail.com>
-iamdoron <doronpagot@gmail.com>
-iawia002 <z2d@jifangcheng.com>
-imagentleman <imagentlemail@gmail.com>
-imjanghyuk <im.janghyuk@gmail.com>
-inkinworld <inkinworld@live.com>
-jaaberg <aaberg89@gmail.com>
-jddxf <740531372@qq.com>
-jinmmd <jinmmd@gmail.com>
-koh-taka <koh-taka@users.noreply.github.com>
-kohashi85 <hako584@gmail.com>
-ksvitkovsky <ksvitkovsky@yandex.ru>
-laiso <laiso@lai.so>
-lamo2k123 <lamo2k123@gmail.com>
-leeyoungalias <leeyoungalias@qq.com>
-li.li <li.li@ele.me>
-lucas <lucas.aragno157@gmail.com>
-maxprafferty <maxprafferty@gmail.com>
-mdogadailo <m.dogadailo@gmail.com>
-mfijas <michal.fijas@gmail.com>
-mguidotto <j8.matteo@gmail.com>
-mondaychen <monday.chen@gmail.com>
-najisawas <naji_sawas@gmx.com>
-neeldeep <neeldeep@users.noreply.github.com>
-newvlad <vladdr@live.com>
-nhducit <nhducit@users.noreply.github.com>
-ogom <ogom@outlook.com>
-pingan1927 <pengsencai1986@gmail.com>
-rgarifullin <ringarifullin@gmail.com>
-saiyagg <saiyagg@gmail.com>
-scloudyy <onecloud.shen@gmail.com>
-segmentationfaulter <segmentationfaulter@users.noreply.github.com>
-shifengchen <shifengchen10@gmail.com>
-songawee <dennis@songawee.com>
-starkch <chp.sitark@autodesk.com>
-sugarshin <shinsugar@gmail.com>
-tokikuch <msmania@users.noreply.github.com>
-ventuno <ventuno@users.noreply.github.com>
-wacii <w.a.cunningham.ii@gmail.com>
-wali-s <ahmad3y2k@hotmail.com>
-walrusfruitcake <walrusfruitcake@users.noreply.github.com>
-yiminghe <yiminghe@gmail.com>
-youmoo <youmoolee@gmail.com>
-yuntao.qyt <yuntao.qyt@alibaba-inc.com>
-z.ky <zky829@users.noreply.github.com>
-zhangjg <jinguozhang@qq.com>
-zhangs <zhangtreefish@yahoo.com>
-zombieJ <smith3816@gmail.com>
-zwhitchcox <zwhitchcox@gmail.com>
-Árni Hermann Reynisson <arnihr@gmail.com>
-元彦 <yuanyan@users.noreply.github.com>
-凌恒 <jiakun.dujk@alibaba-inc.com>
-张敏 <cookfront@gmail.com>
-王晓勇 <Plortinus@gmail.com>
-龙海燕 <1250766229@qq.com>
+Mathieu Savvy <savy.mathieu@gmail.com>
+Matias Singers <mail@matiassingers.com>
+Matsunoki <himkt@klis.tsukuba.ac.jp>
+Matt Brookes <matt@brookes.net>
+Matt Dunn-Rankin <mdunnrankin@gmail.com>
+Matt Harrison <mt.harrison86@gmail.com>
+Matt Huggins <matt.huggins@gmail.com>
+Matt Stow <matt.stow@foxsports.com.au>
+Matt Zabriskie <mzabriskie@gmail.com>
+Matthew Dapena-Tretter <m@tthewwithanm.com>
+Matthew Herbst <mherbst@chegg.com>
+Matthew Hodgson <matthew@matrix.org>
+Matthew Johnston <matthewjohnston4@outlook.com>
+Matthew King <mking@users.noreply.github.com>
+Matthew Looi <looi.matthew@gmail.com>
+Matthew Miner <matthew@matthewminer.com>
+Matthew Shotton <matthew.shotton@bbc.co.uk>
+Matthias Le Brun <mlbli@me.com>
+Matti Nelimarkka <matti.nelimarkka@hiit.fi>
+Mattijs Kneppers <mattijs@arttech.nl>
+Max Donchenko <maxx.donchenko@gmail.com>
+Max F. Albrecht <1@178.is>
+Max Heiber <max.heiber@gmail.com>
+Max Stoiber <contact@mstoiber.com>
+Maxi Ferreira <charca@gmail.com>
+Maxim Abramchuk <MaximAbramchuck@gmail.com>
+Maxwel D'souza <maxellusionist@gmail.com>
+Merrick Christensen <merrick.christensen@gmail.com>
+Mert Kahyaoğlu <mertkahyaoglu93@gmail.com>
+Michael Chan <mijoch@gmail.com>
+Michael Jackson <mjijackson@gmail.com>
+Michael McDermott <michael@mgmcdermott.com>
+Michael O'Brien <mcobrien@users.noreply.github.com>
+Michael Randers-Pehrson <michael.rp@gmail.com>
+Michael Ridgway <mridgway@yahoo-inc.com>
+Michael Sinov <sihaelov@gmail.com>
+Michael Terry <michael@michaelterry.org>
+Michael Warner <MichaelJWarner@hotmail.com>
+Michael Wiencek <mwtuea@gmail.com>
+Michael Ziwisky <mikezx@gmail.com>
+Michal Srb <xixixao@seznam.cz>
+Michał Ordon <designorant@users.noreply.github.com>
+Michał Pierzchała <thymikee@gmail.com>
+Michele Bertoli <MicheleBertoli@users.noreply.github.com>
+Michelle Todd <himichelletodd@gmail.com>
+Michiya <mhibino@users.noreply.github.com>
+Mihai Parparita <mihai.parparita@gmail.com>
+Mike D Pilsbury <mike.pilsbury@gmail.com>
+Mike Groseclose <mike.groseclose@gmail.com>
+Mike Nordick <mnordick>
+Mikhail Osher <yo@miraage.io>
+Mikolaj Dadela <mikolaj.dadela@hgv-online.de>
+Miles Johnson <mileswjohnson@gmail.com>
+Miller Medeiros <miller@millermedeiros.com>
+Minwe LUO <minwe@yunshipei.com>
+Minwei Xu <faceswilliam@gmail.com>
+Miorel Palii <miorel@fb.com>
+Mitchel Humpherys <mitch.special@gmail.com>
+Mitermayer Reis <mitermayer.reis@gmail.com>
+Moacir Rosa <paulomoacir.junior@gmail.com>
+Mojtaba Dashtinejad <mojtaba@gmail.com>
+Morhaus <alexandre.kirszenberg@gmail.com>
+Moshe Kolodny <kolodny.github@gmail.com>
+Mouad Debbar <mdebbar@fb.com>
+Murad <rogozhnikoff@users.noreply.github.com>
+Murray M. Moss <murray@mmoss.name>
+Murtaza Haveliwala <murtaza.sh@gmail.com>
+NE-SmallTown <ne_smalltown@163.com>
+Nadeesha Cabral <nadeesha.cabral@gmail.com>
+Naman Goel <naman34@gmail.com>
+Nate <nchristensen@deseretdigital.com>
+Nate Hunzaker <nate.hunzaker@gmail.com>
+Nate Lee <nathaniel.jy.lee88@gmail.com>
+Nate Norberg <natenorberg@gmail.com>
+Nathan Hardy <nhardy@users.noreply.github.com>
+Nathan Smith <NogsMPLS@users.noreply.github.com>
+Nathan White <nw@nwhite.net>
+Nee <944316342@qq.com>
+Neo <nihgwu@live.com>
+Neri Marschik <marschik_neri@cyberagent.co.jp>
+NestorTejero <webeafix@gmail.com>
+Nguyen Truong Duy <truongduy134@yahoo.com>
+Nicholas Bergson-Shilcock <me@nicholasbs.net>
+Nicholas Clawson <nickclaw@users.noreply.github.com>
+Nick Balestra <nickbalestra@users.noreply.github.com>
+Nick Fitzgerald <fitzgen@gmail.com>
+Nick Gavalas <njg57@cornell.edu>
+Nick Kasten <kastencode@gmail.com>
+Nick Merwin <nick@lemurheavy.com>
+Nick Presta <nick@nickpresta.ca>
+Nick Raienko <enaqxx@gmail.com>
+Nick Thompson <ncthom91@gmail.com>
+Nick Williams <WickyNilliams@users.noreply.github.com>
+Nik Nyby <nnyby@columbia.edu>
+Nikita Lebedev <bloomber111@gmail.com>
+Niklas Boström <nbostrom@gmail.com>
+Nikoloz Buligini <nbuligini11@gmail.com>
+Nima Jahanshahi <nbjahan@gmail.com>
+Ning Xia <ning-github@users.noreply.github.com>
+Niole Nelson <niolenelson@gmail.com>
+Nolan Lawson <nolan@nolanlawson.com>
+Nuno Campos <nuno@crowdprocess.com>
+OJ Kwon <kwon.ohjoong@gmail.com>
+Oiva Eskola <oiva.eskola@gmail.com>
+Oleg <o.yanchinskiy@gmail.com>
+Oleksii Markhovskyi <olexiy.markhovsky@gmail.com>
+Oliver Zeigermann <oliver.zeigermann@gmail.com>
+Olivier Tassinari <Olivier.tassinari@gmail.com>
+Omid Hezaveh <omidfi@users.noreply.github.com>
+Oscar Bolmsten <oscar-b@users.noreply.github.com>
+Oskari Mantere <osku.mantere@gmail.com>
+Owen Coutts <owenc@fb.com>
+Pablo Lacerda de Miranda <pablolm@yahoo-inc.com>
+Paolo Moretti <moretti@users.noreply.github.com>
+Pascal Hartig <passy@twitter.com>
+Patrick <info@telepark.de>
+Patrick Finnigan <patrick.k.finnigan@gmail.com>
+Patrick Laughlin <patrick@laughl.info>
+Patrick Stapleton <github@gdi2290.com>
+Paul Benigeri <me@benigeri.com>
+Paul Harper <benekastah@gmail.com>
+Paul Kehrer <paul.l.kehrer@gmail.com>
+Paul Manta <paulmanta@users.noreply.github.com>
+Paul O’Shannessy <paul@oshannessy.com>
+Paul Seiffert <paul.seiffert@gmail.com>
+Paul Shen <paul@mnml0.com>
+Pedro Nauck <pedronauck@gmail.com>
+Pete Hunt <floydophone@gmail.com>
+Peter Blazejewicz <peter.blazejewicz@gmail.com>
+Peter Cottle <pcottle@fb.com>
+Peter Jaros <peter.a.jaros@gmail.com>
+Peter Newnham <peter.newnham@appsbroker.com>
+Peter Ruibal <ruibalp@gmail.com>
+Petri Lehtinen <petri@digip.org>
+Petri Lievonen <plievone@cc.hut.fi>
+Phil Quinn <philquinn90@gmail.com>
+Phil Rajchgot <tophil@outlook.com>
+Philip Jackson <p-jackson@live.com>
+Philipp Spieß <hello@philippspiess.com>
+Pieter De Baets <pieter.debaets@gmail.com>
+Pieter Vanderwerff <me@pieter.io>
+Piotr Czajkowski <czajkowski.piotr@gmail.com>
+Piper Chester <piperchester@gmail.com>
+Pontus Abrahamsson <info@wdlinkoping.se>
+Pouja Nikray <poujanik@gmail.com>
+Prathamesh Sonpatki <csonpatki@gmail.com>
+Prayag Verma <prayag.verma@gmail.com>
+Preston Parry <ClimbsRocks@users.noreply.github.com>
+Qin Junwen <kjj10@163.com>
+RSG <Radi123@users.noreply.github.com>
+Rachel D. Cartwright <stormchica@gmail.com>
+Rafael <rafael.garcia@clever.com>
+Rafael Angeline <me@rafaelangeline.com>
+Rafal Dittwald <rafal.dittwald@gmail.com>
+Ragnar Þór Valgeirsson <ragnar.valgeirsson@gmail.com>
+Rahul Gupta <rahulgupta4@practo.com>
+Rainer Oviir <roviir@gmail.com>
+Raito Bezarius <masterancpp@gmail.com>
+Rajat Sehgal <rajatsehgal1988@gmail.com>
+Rajiv Tirumalareddy <rajivtreddy@gmail.com>
+Ram Kaniyur <quadrupleslap@users.noreply.github.com>
+Randall Randall <randall@randallsquared.com>
+Ray <ray@tomo.im>
+Ray Dai <exiadbq@gmail.com>
+Raymond Ha <raymond@shraymonks.com>
+Reed Loden <reed@reedloden.com>
+Remko Tronçon <git@el-tramo.be>
+Ricardo <ddrjm@users.noreply.github.com>
+Rich Harris <richard.a.harris@gmail.com>
+Richard <riscarrott@googlemail.com>
+Richard D. Worth <rdworth@gmail.com>
+Richard Feldman <richard.t.feldman@gmail.com>
+Richard Kho <hello@richardkho.com>
+Richard Littauer <richard.littauer@gmail.com>
+Richard Livesey <Livesey7@hotmail.co.uk>
+Richard Maisano <rickmaisano@gmail.com>
+Richard Roncancio <batusai513@msn.com>
+Richard Wood <rwoodnz@gmail.com>
+Richie Thomas <rickthomas1980@gmail.com>
+Rick Beerendonk <rick@beerendonk.com>
+Rick Ford <rickfordrick@gmail.com>
+Riley Tomasek <riley.tomasek@gmail.com>
+Rob Arnold <robarnold@cs.cmu.edu>
+Robert Binna <rbinna@gmail.com>
+Robert Chang <cht8687@gmail.com>
+Robert Haritonov <r@rhr.me>
+Robert Kielty <rob.kielty@gmail.com>
+Robert Knight <robert.knight@mendeley.com>
+Robert Martin <rmartin@rmart.in>
+Robert Sedovsek <robert.sedovsek@gmail.com>
+Robin Berjon <robin@berjon.com>
+Robin Frischmann <robin@rofrischmann.de>
+Robin Ricard <ricard.robin@gmail.com>
+Roderick Hsiao <roderickhsiao@users.noreply.github.com>
+Rodrigo Pombo <pombopombopombo@gmail.com>
+Rohan Nair <rohan@objectiveiq.com>
+Roman Liutikov <roman01la@romanliutikov.com>
+Roman Matusevich <roma.matusevich@gmail.com>
+Roman Pominov <rpominov+github@gmail.com>
+Roman Vanesyan <roman.vanesyan@gmail.com>
+Rui Araújo <ruka.araujo@gmail.com>
+Russ <russwirtz@gmail.com>
+Ryan Lahfa <masterancpp@gmail.com>
+Ryan Seddon <seddon.ryan@gmail.com>
+Ryo Shibayama <j02521@gmail.com>
+Sahat Yalkabov <sakhat@gmail.com>
+Saif Hakim <saif@benchling.com>
+Saiichi Hashimoto <saiichihashimoto@gmail.com>
+Sakina Crocker <sakinac@gmail.com>
+Sam Balana <sam.balana@ardentacademy.com>
+Sam Beveridge <sbeveridge@saltstack.com>
+Sam Saccone <samccone@gmail.com>
+Sam Selikoff <sam.selikoff@gmail.com>
+Samer Buna <samerbuna@users.noreply.github.com>
+Samuel <savepointsam@gmail.com>
+Samuel Hapák <samuel.hapak@gmail.com>
+Samuel Reed <samuel.trace.reed@gmail.com>
+Samuel Scheiderich <samsch@users.noreply.github.com>
+Samy Al Zahrani <samy@sadeem.net>
+Sander Spies <sandermail@gmail.com>
+Sasha Aickin <xander76@yahoo.com>
+Sassan Haradji <sassanh@gmail.com>
+Satoshi Nakajima <satoshi.nakajima@gmail.com>
+Scott <scottdomes@gmail.com>
+Scott Burch <scott@bulldoginfo.com>
+Scott Feeney <scott@oceanbase.org>
+Sean Gransee <sean.gransee@gmail.com>
+Sean Kinsey <oyvind@fb.com>
+Sean Smith <sean.smith.2009@gmail.com>
+Seba <sebaest77@gmail.com>
+Sebastian Markbåge <sebastian@calyptus.eu>
+Sebastian McKenzie <sebmck@gmail.com>
+Senin Roman <Rastopyr@gmail.com>
+Seoh Char <devthewild@gmail.com>
+Sercan Eraslan <sercan.eraslan@sahibinden.com>
+Serg <undrdog@yandex.ru>
+Sergey Generalov <sergey@genbit.ru>
+Sergey Rubanov <chi187@gmail.com>
+Seyi Adebajo <hello@seyinanigans.com>
+Shane O'Sullivan <shaneosullivan1@gmail.com>
+Shaun Trennery <shaun.trennery@gmail.com>
+ShihChi Huang <hhuang@netflix.com>
+Shim Won <marocchino@gmail.com>
+Shinnosuke Watanabe <snnskwtnb@gmail.com>
+Shogun Sea <shogunsea08@gmail.com>
+Shota Kubota <kubosho@users.noreply.github.com>
+Shripad K <assortmentofsorts@gmail.com>
+Shubheksha Jalan <jshubheksha@gmail.com>
+Shuhei Kagawa <shuhei.kagawa@gmail.com>
+Sibi <psibi2000@gmail.com>
+Simen Bekkhus <sbekkhus91@gmail.com>
+Simon Højberg <r.hackr@gmail.com>
+Simon Welsh <simon@simon.geek.nz>
+Simone Vittori <hello@simonewebdesign.it>
+Skasi <skasski@gmx.at>
+Snowmanzzz(Zhengzhong Zhao) <zhengzhongzhao@gmail.com>
+Soichiro Kawamura <mail@w-st.com>
+Soo Jae Hwang <misoguy1985@gmail.com>
+Sophia <szensius@gmail.com>
+Sophia Westwood <sophia@quip.com>
+Sophie Alpert <git@sophiebits.com>
+Sota Ohara <ohrst.18@gmail.com>
+Spen Taylor <spen_@hotmail.co.uk>
+Spencer Ahrens <sahrens@users.noreply.github.com>
+Spencer Handley <spencerhandley@gmail.com>
+Sriram Thiagarajan <sri.sjc@gmail.com>
+Stefan Dombrowski <sdo451@gmail.com>
+Stephen John Sorensen <spudly@users.noreply.github.com>
+Stephen Murphy <smurphy3@apple.com>
+Stephie <Stephie@users.noreply.github.com>
+Sterling Cobb <sterlingcobb@gmail.com>
+Steve Baker <_steve_@outlook.com>
+Steve Mao <maochenyan@gmail.com>
+Steven Luscher <react@steveluscher.com>
+Steven Syrek <sjsyrek@users.noreply.github.com>
+Steven Vachon <contact@svachon.com>
+Stolenkid <stolen.kid7@gmail.com>
+Stoyan Stefanov <ssttoo@ymail.com>
+Stuart Harris <stuart.harris@red-badger.com>
+SunHuawei <stonesun@aliyun.com>
+Sundeep Malladi <sundeep.malladi@gmail.com>
+Sung Won Cho <mikeswcho@gmail.com>
+Sunny Juneja <me@sunnyjuneja.com>
+Sunny Ripert <sunny@sunfox.org>
+Superlaziness <shemyakin@me.com>
+Sven Helmberger <fforw@gmx.de>
+Sverre Johansen <sverre.johansen@gmail.com>
+Swaroop SM <swaroop.striker@gmail.com>
+Sébastien Lorber <lorber.sebastien@gmail.com>
+Sławomir Laskowski <laskowski.box@gmail.com>
+Taegon Kim <gonom9@gmail.com>
+Taeho Kim <dittos@gmail.com>
+Taehwan, No <taehwanno.dev@gmail.com>
+Tanase Hagi <TanaseHagi@users.noreply.github.com>
+Tanner <devtanc@gmail.com>
+Tay Yang Shun <tay.yang.shun@gmail.com>
+Ted Kim <ted@vcnc.co.kr>
+TedPowers <TedPowers@users.noreply.github.com>
+Tengfei Guo <terryr3rd@yeah.net>
+Teodor Szente <teodor98sz@gmail.com>
+Tetsuharu OHZEKI <saneyuki.s.snyk@gmail.com>
+Tetsuya Hasegawa <tetsuya.chicago@gmail.com>
+Thibaut Rizzi <zoom@rhizom.fr>
+Thomas Aylott <oblivious@subtlegradient.com>
+Thomas Boyt <thomas.boyt@venmo.com>
+Thomas Broadly <buriedunderbooks@hotmail.com>
+Thomas Reggi <socialtr@gmail.com>
+Thomas Röggla <t.roggla@cwi.nl>
+Thomas Shaddox <thomas@heyzap.com>
+Thomas Shafer <thomasjshafer@gmail.com>
+ThomasCrvsr <crevoisier.thomas@gmail.com>
+Tiago Fernandez <tiago.fernandez@gmail.com>
+Tienchai Wirojsaksaree <tienchai@fb.com>
+Tim Routowicz <troutowicz@gmail.com>
+Tim Schaub <tschaub@users.noreply.github.com>
+Timothy Yung <yungsters@gmail.com>
+Timur Carpeev <timuric@users.noreply.github.com>
+Tobias Reiss <tag+github@basecode.de>
+Tom Duncalf <tom@tomduncalf.com>
+Tom Gasson <tom.gasson@arup.com>
+Tom Haggie <thaggie@gmail.com>
+Tom Hauburger <thauburger@gmail.com>
+Tom MacWright <tom@macwright.org>
+Tom Occhino <tomocchino@gmail.com>
+Tomasz Kołodziejski <tkolodziejski@gmail.com>
+Tomoya Suzuki <tmysz.dev@gmail.com>
+Tomáš Hromada <Gyfis@seznam.cz>
+Tony Rossi <tony@iamrossi.com>
+Tony Spiro <tspiro@tonyspiro.com>
+Toru Kobayashi <koba0004@gmail.com>
+Trevor Smith <trevorlynnsmith@gmail.com>
+Trinh Hoang Nhu <trinhhoangnhu@gmail.com>
+Troy DeMonbreun <github@troyd.net>
+Tsung Hung <thung@me.com>
+Tyler Brock <tyler.brock@gmail.com>
+Tyler Buchea <tyler@buchea.com>
+Tyler Deitz <tylerdeitz@gmail.com>
+Ujjwal Ojha <ojhaujjwal@users.noreply.github.com>
+Uladzimir Havenchyk <uladzimir@toptal.com>
+Usman <syedusmanajmal@gmail.com>
+Ustin Zarubin <ustin.zarubin@campusbellhops.com>
+Vadim Chernysh <chernysh.vadim@gmail.com>
+Valentin Shergin <valentin@shergin.com>
+Van der Auwermeulen Grégoire <gregoirevandera@gmail.com>
+Varayut Lerdkanlayanawat <l.varayut@gmail.com>
+Varun Bhuvanendran <varunbhuvanendran@users.noreply.github.com>
+Varun Rau <varunrau@gmail.com>
+Vasiliy Loginevskiy <Yeti.or@gmail.com>
+Vedat Mahir YILMAZ <mahir@vedatmahir.com>
+Veljko Tornjanski <tornjanski.veljko@gmail.com>
+Vesa Laakso <laakso.vesa@gmail.com>
+Victor Alvarez <v.alvarez312@gmail.com>
+Victor Homyakov <vkhomyackov@gmail.com>
+Victor Koenders <victor.koenders@gmail.com>
+Victoria Quirante <victoria.quirante@gmail.com>
+Vikash Agrawal <vikashagrawal1990@gmail.com>
+Ville Immonen <ville.immonen@iki.fi>
+Vincent Riemer <vincentriemer@gmail.com>
+Vincent Siao <vincent@asana.com>
+Vincent Taing <taing.vincent@gmail.com>
+Vipul A M <vipulnsward@gmail.com>
+Vitality Potapov <noginsk@rambler.ru>
+Vitaly Kramskikh <vkramskikh@gmail.com>
+Vitor Balocco <vitorbal@gmail.com>
+Vjeux <vjeuxx@gmail.com>
+Vladimir Kovpak <cn007b@gmail.com>
+Vladimir Tikunov <vtikunov@yandex.ru>
+Volkan Unsal <spocksplanet@gmail.com>
+Wander Wang <wander.wang@ismole.com>
+Wayne Larsen <wayne@larsen.st>
+Weizenlol <winliveweiz@gmail.com>
+Whien <sal95610@gmail.com>
+WickyNilliams <WickyNilliams@MBA>
+Will Myers <will@usebutton.com>
+William Hoffmann <whoffpen@gmail.com>
+Wincent Colaiuta <win@wincent.com>
+Wout Mertens <Wout.Mertens@gmail.com>
+Xavier Morel <xmo-odoo@users.noreply.github.com>
+XuefengWu <benewu@gmail.com>
+Yakov Dalinchuk <murashki@users.noreply.github.com>
+Yan Li <mangakjd@gmail.com>
+Yasar icli <hello@yasaricli.com>
+Yaxian <yaxian.gu@gmail.com>
+YouBao Nong <noyobo@gmail.com>
+Yuichi Hagio <yhagio87@gmail.com>
+Yura Chuchola <smhfanda@gmail.com>
+Yuriy Dybskiy <yuriy@dybskiy.com>
+Yusong Liu <lysnku@gmail.com>
+Yutaka Nakajima <nakazye@gmail.com>
+Yuval Dekel <thedekel@fb.com>
+Zac Braddy <zacharybraddy@gmail.com>
+Zac Smith <billyzacsmith@gmail.com>
+Zach Bruggeman <mail@bruggie.com>
+Zach Ramaekers <zramaekers@gmail.com>
+Zacharias <zachasme@users.noreply.github.com>
+Zeke Sikelianos <zeke@sikelianos.com>
+Zhangjd <zhang.jd@qq.com>
+adraeth <jerzy.mirecki@gmail.com>
+ankitml <ankitml@gmail.com>
+arush <arush@ilovebrands.net>
+bel3atar <bel3atar@aol.com>
+brafdlog <brafdlog@gmail.com>
+brillout <brillout@users.noreply.github.com>
+chen <kikyous@163.com>
+chocolateboy <chocolate@cpan.org>
+cjshawMIT <cjshaw@mit.edu>
+clariroid <clarinette.uranus@gmail.com>
+claudiopro <claudio.procida@gmail.com>
+cloudy1 <mohaned@cloudypedia.com>
+comerc <comerc@users.noreply.github.com>
+cutbko <kutsenko.eugene@hotmail.com>
+davidxi <davidgraycn@gmail.com>
+dfrownfelter <davidrfrownfelter@gmail.com>
+djskinner <skinner@destiny-denied.co.uk>
+dongmeng.ldm <dongmeng.ldm@alibaba-inc.com>
+everdimension <everdimension@gmail.com>
+gillchristian <gillchristiang@gmail.com>
+gitanupam <anupamjain@gmail.com>
+guoyong yi <451417726@qq.com>
+hanumanthan <hanu.sas@gmail.com>
+hao.huang <hao.huang@aliyun.com>
+hjmoss <hjmoss@users.noreply.github.com>
+hkal <hkal@users.noreply.github.com>
+iamchenxin <iamchenxin@gmail.com>
+iamdoron <doronpagot@gmail.com>
+iawia002 <z2d@jifangcheng.com>
+imagentleman <imagentlemail@gmail.com>
+imjanghyuk <im.janghyuk@gmail.com>
+inkinworld <inkinworld@live.com>
+jaaberg <aaberg89@gmail.com>
+jddxf <740531372@qq.com>
+jinmmd <jinmmd@gmail.com>
+koh-taka <koh-taka@users.noreply.github.com>
+kohashi85 <hako584@gmail.com>
+ksvitkovsky <ksvitkovsky@yandex.ru>
+laiso <laiso@lai.so>
+lamo2k123 <lamo2k123@gmail.com>
+leeyoungalias <leeyoungalias@qq.com>
+li.li <li.li@ele.me>
+lucas <lucas.aragno157@gmail.com>
+maxprafferty <maxprafferty@gmail.com>
+mdogadailo <m.dogadailo@gmail.com>
+mfijas <michal.fijas@gmail.com>
+mguidotto <j8.matteo@gmail.com>
+mondaychen <monday.chen@gmail.com>
+najisawas <naji_sawas@gmx.com>
+neeldeep <neeldeep@users.noreply.github.com>
+newvlad <vladdr@live.com>
+nhducit <nhducit@users.noreply.github.com>
+ogom <ogom@outlook.com>
+pingan1927 <pengsencai1986@gmail.com>
+rgarifullin <ringarifullin@gmail.com>
+saiyagg <saiyagg@gmail.com>
+scloudyy <onecloud.shen@gmail.com>
+segmentationfaulter <segmentationfaulter@users.noreply.github.com>
+shifengchen <shifengchen10@gmail.com>
+songawee <dennis@songawee.com>
+starkch <chp.sitark@autodesk.com>
+sugarshin <shinsugar@gmail.com>
+tokikuch <msmania@users.noreply.github.com>
+ventuno <ventuno@users.noreply.github.com>
+wacii <w.a.cunningham.ii@gmail.com>
+wali-s <ahmad3y2k@hotmail.com>
+walrusfruitcake <walrusfruitcake@users.noreply.github.com>
+yiminghe <yiminghe@gmail.com>
+youmoo <youmoolee@gmail.com>
+yuntao.qyt <yuntao.qyt@alibaba-inc.com>
+z.ky <zky829@users.noreply.github.com>
+zhangjg <jinguozhang@qq.com>
+zhangs <zhangtreefish@yahoo.com>
+zombieJ <smith3816@gmail.com>
+zwhitchcox <zwhitchcox@gmail.com>
+Árni Hermann Reynisson <arnihr@gmail.com>
+元彦 <yuanyan@users.noreply.github.com>
+凌恒 <jiakun.dujk@alibaba-inc.com>
+张敏 <cookfront@gmail.com>
+王晓勇 <Plortinus@gmail.com>
+龙海燕 <1250766229@qq.com>
--- ./fixtures/attribute-behavior/AttributeTableSnapshot.md	original
+++ ./fixtures/attribute-behavior/AttributeTableSnapshot.md	fixed
@@ -2601 +2601 @@
-## `defaultValuE` (on `<input>` inside `<div>`)
+## `defaultValueE` (on `<input>` inside `<div>`)
@@ -2604,21 +2604,21 @@
-| `defaultValuE=(string)`| (changed, warning)| `"a string"` |
-| `defaultValuE=(empty string)`| (changed, warning)| `<empty string>` |
-| `defaultValuE=(array with string)`| (changed, warning)| `"string"` |
-| `defaultValuE=(empty array)`| (changed, warning)| `<empty string>` |
-| `defaultValuE=(object)`| (changed, warning)| `"result of toString()"` |
-| `defaultValuE=(numeric string)`| (changed, warning)| `"42"` |
-| `defaultValuE=(-1)`| (changed, warning)| `"-1"` |
-| `defaultValuE=(0)`| (changed, warning)| `"0"` |
-| `defaultValuE=(integer)`| (changed, warning)| `"1"` |
-| `defaultValuE=(NaN)`| (changed, warning)| `"NaN"` |
-| `defaultValuE=(float)`| (changed, warning)| `"99.99"` |
-| `defaultValuE=(true)`| (initial, warning)| `<null>` |
-| `defaultValuE=(false)`| (initial, warning)| `<null>` |
-| `defaultValuE=(string 'true')`| (changed, warning)| `"true"` |
-| `defaultValuE=(string 'false')`| (changed, warning)| `"false"` |
-| `defaultValuE=(string 'on')`| (changed, warning)| `"on"` |
-| `defaultValuE=(string 'off')`| (changed, warning)| `"off"` |
-| `defaultValuE=(symbol)`| (initial, warning)| `<null>` |
-| `defaultValuE=(function)`| (initial, warning)| `<null>` |
-| `defaultValuE=(null)`| (initial, warning)| `<null>` |
-| `defaultValuE=(undefined)`| (initial, warning)| `<null>` |
+| `defaultValueE=(string)`| (changed, warning)| `"a string"` |
+| `defaultValueE=(empty string)`| (changed, warning)| `<empty string>` |
+| `defaultValueE=(array with string)`| (changed, warning)| `"string"` |
+| `defaultValueE=(empty array)`| (changed, warning)| `<empty string>` |
+| `defaultValueE=(object)`| (changed, warning)| `"result of toString()"` |
+| `defaultValueE=(numeric string)`| (changed, warning)| `"42"` |
+| `defaultValueE=(-1)`| (changed, warning)| `"-1"` |
+| `defaultValueE=(0)`| (changed, warning)| `"0"` |
+| `defaultValueE=(integer)`| (changed, warning)| `"1"` |
+| `defaultValueE=(NaN)`| (changed, warning)| `"NaN"` |
+| `defaultValueE=(float)`| (changed, warning)| `"99.99"` |
+| `defaultValueE=(true)`| (initial, warning)| `<null>` |
+| `defaultValueE=(false)`| (initial, warning)| `<null>` |
+| `defaultValueE=(string 'true')`| (changed, warning)| `"true"` |
+| `defaultValueE=(string 'false')`| (changed, warning)| `"false"` |
+| `defaultValueE=(string 'on')`| (changed, warning)| `"on"` |
+| `defaultValueE=(string 'off')`| (changed, warning)| `"off"` |
+| `defaultValueE=(symbol)`| (initial, warning)| `<null>` |
+| `defaultValueE=(function)`| (initial, warning)| `<null>` |
+| `defaultValueE=(null)`| (initial, warning)| `<null>` |
+| `defaultValueE=(undefined)`| (initial, warning)| `<null>` |
