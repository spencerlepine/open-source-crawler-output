## Detected Typos Diff
```diff
--- ./packages/flutter/test/material/range_slider_test.dart	original
+++ ./packages/flutter/test/material/range_slider_test.dart	fixed
@@ -1461 +1461 @@
-      // Represents the raised button wth next text.
+      // Represents the raised button with next text.
--- ./packages/flutter/test/widgets/table_test.dart	original
+++ ./packages/flutter/test/widgets/table_test.dart	fixed
@@ -1003 +1003 @@
-  testWidgets('Do not crash if a child that has not been layed out in a previous build is removed', (WidgetTester tester) async {
+  testWidgets('Do not crash if a child that has not been laid out in a previous build is removed', (WidgetTester tester) async {
@@ -1025 +1025 @@
-      null, EnginePhase.build, // Children are not layed out!
+      null, EnginePhase.build, // Children are not laid out!
--- ./packages/flutter/test/widgets/lookup_boundary_test.dart	original
+++ ./packages/flutter/test/widgets/lookup_boundary_test.dart	fixed
@@ -176 +176 @@
-    testWidgets('causes didChangeDependencies to be called on move even if dependency was non-existant', (WidgetTester tester) async {
+    testWidgets('causes didChangeDependencies to be called on move even if dependency was non-existent', (WidgetTester tester) async {
--- ./packages/flutter/test/material/text_field_test.dart	original
+++ ./packages/flutter/test/material/text_field_test.dart	fixed
@@ -6870 +6870 @@
-  testWidgets('TextField semantics alway include label and not hint when input value is not empty', (WidgetTester tester) async {
+  testWidgets('TextField semantics always include label and not hint when input value is not empty', (WidgetTester tester) async {
--- ./packages/flutter/test/widgets/draggable_test.dart	original
+++ ./packages/flutter/test/widgets/draggable_test.dart	fixed
@@ -1976,3 +1976,3 @@
-    final List<DragTargetData> acceptedDragTargetDatas = <DragTargetData>[];
-    final List<DragTargetDetails<DragTargetData>> acceptedDragTargetDataDetails = <DragTargetDetails<DragTargetData>>[];
-    final List<ExtendedDragTargetData> acceptedExtendedDragTargetDatas = <ExtendedDragTargetData>[];
+    final List<DragTargetData> acceptedDragTargetData = <DragTargetData>[];
+    final List<DragTargetDetails<DragTargetData>> acceptedDragTargetDataDetails = <DragTargetDetails<DragTargetData>>[];
+    final List<ExtendedDragTargetData> acceptedExtendedDragTargetData = <ExtendedDragTargetData>[];
@@ -1999,13 +1999,13 @@
-                }, onAccept: acceptedDragTargetDatas.add,
-                onAcceptWithDetails: acceptedDragTargetDataDetails.add,
-              ),
-              DragTarget<ExtendedDragTargetData>(
-                builder: (BuildContext context, List<ExtendedDragTargetData?> data, List<dynamic> rejects) {
-                  return const IgnorePointer(
-                    child: SizedBox(
-                      height: 100.0,
-                      child: Text('Target2'),
-                    ),
-                  );
-                },
-                onAccept: acceptedExtendedDragTargetDatas.add,
+                }, onAccept: acceptedDragTargetData.add,
+                onAcceptWithDetails: acceptedDragTargetDataDetails.add,
+              ),
+              DragTarget<ExtendedDragTargetData>(
+                builder: (BuildContext context, List<ExtendedDragTargetData?> data, List<dynamic> rejects) {
+                  return const IgnorePointer(
+                    child: SizedBox(
+                      height: 100.0,
+                      child: Text('Target2'),
+                    ),
+                  );
+                },
+                onAccept: acceptedExtendedDragTargetData.add,
@@ -2031,4 +2031,4 @@
-      expect(acceptedDragTargetDatas, equals(<DragTargetData>[dragTargetData]));
-      expect(acceptedDragTargetDataDetails, hasLength(1));
-      expect(acceptedDragTargetDataDetails.first.offset, const Offset(256.0, 74.0));
-      expect(acceptedExtendedDragTargetDatas, isEmpty);
+      expect(acceptedDragTargetData, equals(<DragTargetData>[dragTargetData]));
+      expect(acceptedDragTargetDataDetails, hasLength(1));
+      expect(acceptedDragTargetDataDetails.first.offset, const Offset(256.0, 74.0));
+      expect(acceptedExtendedDragTargetData, isEmpty);
@@ -2037 +2037 @@
-      acceptedDragTargetDatas.clear();
+      acceptedDragTargetData.clear();
--- ./packages/flutter/test/widgets/slivers_test.dart	original
+++ ./packages/flutter/test/widgets/slivers_test.dart	fixed
@@ -62,9 +62,9 @@
-void verify(WidgetTester tester, List<Offset> idealPositions, List<bool> idealVisibles) {
-  final List<Offset> actualPositions = tester.renderObjectList<RenderBox>(find.byType(SizedBox, skipOffstage: false)).map<Offset>(
-    (RenderBox target) => target.localToGlobal(Offset.zero),
-  ).toList();
-  final List<bool> actualVisibles = tester.renderObjectList<RenderSliverToBoxAdapter>(find.byType(SliverToBoxAdapter, skipOffstage: false)).map<bool>(
-    (RenderSliverToBoxAdapter target) => target.geometry!.visible,
-  ).toList();
-  expect(actualPositions, equals(idealPositions));
-  expect(actualVisibles, equals(idealVisibles));
+void verify(WidgetTester tester, List<Offset> idealPositions, List<bool> idealVisible) {
+  final List<Offset> actualPositions = tester.renderObjectList<RenderBox>(find.byType(SizedBox, skipOffstage: false)).map<Offset>(
+    (RenderBox target) => target.localToGlobal(Offset.zero),
+  ).toList();
+  final List<bool> actualVisible = tester.renderObjectList<RenderSliverToBoxAdapter>(find.byType(SliverToBoxAdapter, skipOffstage: false)).map<bool>(
+    (RenderSliverToBoxAdapter target) => target.geometry!.visible,
+  ).toList();
+  expect(actualPositions, equals(idealPositions));
+  expect(actualVisible, equals(idealVisible));
--- ./packages/flutter/test/widgets/text_test.dart	original
+++ ./packages/flutter/test/widgets/text_test.dart	fixed
@@ -772 +772 @@
-    //   hello world RIS OD you OD WOH YOB good bye
+    //   hello world RIS OD you OD WHO YOB good bye
--- ./packages/flutter/test/widgets/widget_inspector_test.dart	original
+++ ./packages/flutter/test/widgets/widget_inspector_test.dart	fixed
@@ -1381 +1381 @@
-    // TODO(CoderDake): Clean up pubRootDirectory tests https://github.com/flutter/flutter/issues/107186
+    // TODO(CoderTake): Clean up pubRootDirectory tests https://github.com/flutter/flutter/issues/107186
--- ./packages/flutter/test/widgets/editable_text_test.dart	original
+++ ./packages/flutter/test/widgets/editable_text_test.dart	fixed
@@ -5663 +5663 @@
-    // Everything's just formated the same way now.
+    // Everything's just formatted the same way now.
--- ./packages/flutter/lib/src/material/refresh_indicator.dart	original
+++ ./packages/flutter/lib/src/material/refresh_indicator.dart	fixed
@@ -159 +159 @@
-  /// Noteably the scrollable widget itself will have slightly different behavior
+  /// Notably the scrollable widget itself will have slightly different behavior
--- ./packages/flutter/lib/src/material/segmented_button.dart	original
+++ ./packages/flutter/lib/src/material/segmented_button.dart	fixed
@@ -160 +160 @@
-  /// The default is false, so only a single segement may be selected at one
+  /// The default is false, so only a single segment may be selected at one
--- ./packages/flutter/lib/src/material/action_buttons.dart	original
+++ ./packages/flutter/lib/src/material/action_buttons.dart	fixed
@@ -328 +328 @@
-/// The default behaviour on press can be overriden with [onPressed].
+/// The default behaviour on press can be overridden with [onPressed].
@@ -393 +393 @@
-/// The default behaviour on press can be overriden with [onPressed].
+/// The default behaviour on press can be overridden with [onPressed].
--- ./packages/flutter/lib/src/material/tab_indicator.dart	original
+++ ./packages/flutter/lib/src/material/tab_indicator.dart	fixed
@@ -31 +31 @@
-  /// drawn, otherwise rectangular tab indictor is drawn.
+  /// drawn, otherwise rectangular tab indicator is drawn.
--- ./packages/flutter/lib/src/material/text_selection.dart	original
+++ ./packages/flutter/lib/src/material/text_selection.dart	fixed
@@ -246 +246 @@
-    final List<_TextSelectionToolbarItemData> itemDatas = <_TextSelectionToolbarItemData>[
+    final List<_TextSelectionToolbarItemData> itemData = <_TextSelectionToolbarItemData>[
@@ -271 +271 @@
-    if (itemDatas.isEmpty) {
+    if (itemData.isEmpty) {
@@ -278,3 +278,3 @@
-      children: itemDatas.asMap().entries.map((MapEntry<int, _TextSelectionToolbarItemData> entry) {
-        return TextSelectionToolbarTextButton(
-          padding: TextSelectionToolbarTextButton.getPadding(entry.key, itemDatas.length),
+      children: itemData.asMap().entries.map((MapEntry<int, _TextSelectionToolbarItemData> entry) {
+        return TextSelectionToolbarTextButton(
+          padding: TextSelectionToolbarTextButton.getPadding(entry.key, itemData.length),
--- ./packages/flutter/lib/src/services/dom.dart	original
+++ ./packages/flutter/lib/src/services/dom.dart	fixed
@@ -29 +29 @@
-/// The underyling window.
+/// The underlying window.
@@ -51 +51 @@
-  /// The underyling platform string.
+  /// The underlying platform string.
--- ./packages/flutter/lib/src/cupertino/nav_bar.dart	original
+++ ./packages/flutter/lib/src/cupertino/nav_bar.dart	fixed
@@ -190 +190 @@
-bool _isTransitionable(BuildContext context) {
+bool _isTransitional(BuildContext context) {
@@ -485 +485 @@
-    if (!widget.transitionBetweenRoutes || !_isTransitionable(context)) {
+    if (!widget.transitionBetweenRoutes || !_isTransitional(context)) {
@@ -501 +501 @@
-          child: _TransitionableNavigationBar(
+          child: _TransitionalNavigationBar(
@@ -878 +878 @@
-    if (!transitionBetweenRoutes || !_isTransitionable(context)) {
+    if (!transitionBetweenRoutes || !_isTransitional(context)) {
@@ -893 +893 @@
-      child: _TransitionableNavigationBar(
+      child: _TransitionalNavigationBar(
@@ -1618,2 +1618,2 @@
-class _TransitionableNavigationBar extends StatelessWidget {
-  _TransitionableNavigationBar({
+class _TransitionalNavigationBar extends StatelessWidget {
+  _TransitionalNavigationBar({
@@ -1646 +1646 @@
-      '_TransitionableNavigationBar.renderBox should be called when building '
+      '_TransitionalNavigationBar.renderBox should be called when building '
@@ -1661,14 +1661,14 @@
-            '_TransitionableNavigationBar should never re-appear inside '
-            '_NavigationBarTransition. Keyed _TransitionableNavigationBar should '
-            'only serve as anchor points in routes rather than appearing inside '
-            'Hero flights themselves.',
-          );
-          if (ancestor.widget.runtimeType == Hero) {
-            inHero = true;
-          }
-        }
-        return true;
-      });
-      assert(
-        inHero,
-        '_TransitionableNavigationBar should only be added as the immediate '
+            '_TransitionalNavigationBar should never re-appear inside '
+            '_NavigationBarTransition. Keyed _TransitionalNavigationBar should '
+            'only serve as anchor points in routes rather than appearing inside '
+            'Hero flights themselves.',
+          );
+          if (ancestor.widget.runtimeType == Hero) {
+            inHero = true;
+          }
+        }
+        return true;
+      });
+      assert(
+        inHero,
+        '_TransitionalNavigationBar should only be added as the immediate '
@@ -1717,2 +1717,2 @@
-  final _TransitionableNavigationBar topNavBar;
-  final _TransitionableNavigationBar bottomNavBar;
+  final _TransitionalNavigationBar topNavBar;
+  final _TransitionalNavigationBar bottomNavBar;
@@ -1811,2 +1811,2 @@
-    required _TransitionableNavigationBar bottomNavBar,
-    required _TransitionableNavigationBar topNavBar,
+    required _TransitionalNavigationBar bottomNavBar,
+    required _TransitionalNavigationBar topNavBar,
@@ -2423,3 +2423,3 @@
-  assert(child is _TransitionableNavigationBar);
-  // Tree reshaping is fine here because the Heroes' child is always a
-  // _TransitionableNavigationBar which has a GlobalKey.
+  assert(child is _TransitionalNavigationBar);
+  // Tree reshaping is fine here because the Heroes' child is always a
+  // _TransitionalNavigationBar which has a GlobalKey.
@@ -2458,2 +2458,2 @@
-  assert(fromHeroWidget.child is _TransitionableNavigationBar);
-  assert(toHeroWidget.child is _TransitionableNavigationBar);
+  assert(fromHeroWidget.child is _TransitionalNavigationBar);
+  assert(toHeroWidget.child is _TransitionalNavigationBar);
@@ -2461,2 +2461,2 @@
-  final _TransitionableNavigationBar fromNavBar = fromHeroWidget.child as _TransitionableNavigationBar;
-  final _TransitionableNavigationBar toNavBar = toHeroWidget.child as _TransitionableNavigationBar;
+  final _TransitionalNavigationBar fromNavBar = fromHeroWidget.child as _TransitionalNavigationBar;
+  final _TransitionalNavigationBar toNavBar = toHeroWidget.child as _TransitionalNavigationBar;
--- ./packages/flutter/lib/src/rendering/paragraph.dart	original
+++ ./packages/flutter/lib/src/rendering/paragraph.dart	fixed
@@ -1041 +1041 @@
-    bool needsChildConfigrationsDelegate = false;
+    bool needsChildConfigurationsDelegate = false;
@@ -1047 +1047 @@
-      needsChildConfigrationsDelegate = needsChildConfigrationsDelegate || info.isPlaceholder;
+      needsChildConfigurationsDelegate = needsChildConfigurationsDelegate || info.isPlaceholder;
@@ -1053 +1053 @@
-    } else if (needsChildConfigrationsDelegate) {
+    } else if (needsChildConfigurationsDelegate) {
--- ./packages/flutter_localizations/lib/src/l10n/material_es_PY.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_PY.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_fr.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_fr.arb	fixed
@@ -42 +42 @@
-  "popupMenuLabel": "Menu contextuel",
+  "popupMenuLabel": "Menu contextual",
@@ -69,2 +69,2 @@
-  "invalidDateFormatLabel": "Format non valide.",
-  "invalidDateRangeLabel": "Plage non valide.",
+  "invalidDateFormatLabel": "Format non valid.",
+  "invalidDateRangeLabel": "Plage non valid.",
@@ -81 +81 @@
-  "invalidTimeLabel": "Veuillez indiquer une heure valide",
+  "invalidTimeLabel": "Veuillez indiquer une heure valid",
@@ -130 +130 @@
-  "keyboardKeySpace": "Espace",
+  "keyboardKeySpace": "Escape",
--- ./packages/flutter_localizations/lib/src/l10n/generated_cupertino_localizations.dart	original
+++ ./packages/flutter_localizations/lib/src/l10n/generated_cupertino_localizations.dart	fixed
@@ -1406 +1406 @@
-  String? get datePickerMinuteSemanticsLabelOne => '1 minut';
+  String? get datePickerMinuteSemanticsLabelOne => '1 minute';
@@ -1409 +1409 @@
-  String get datePickerMinuteSemanticsLabelOther => r'$minute minuts';
+  String get datePickerMinuteSemanticsLabelOther => r'$minute minutes';
@@ -1418 +1418 @@
-  String get modalBarrierDismissLabel => 'Ignora';
+  String get modalBarrierDismissLabel => 'Ignore';
@@ -1556 +1556 @@
-  String get datePickerMinuteSemanticsLabelOther => r'$minute minut';
+  String get datePickerMinuteSemanticsLabelOther => r'$minute minute';
@@ -1700 +1700 @@
-  String? get datePickerMinuteSemanticsLabelOne => '1 minut';
+  String? get datePickerMinuteSemanticsLabelOne => '1 minute';
@@ -3308 +3308 @@
-  String? get datePickerMinuteSemanticsLabelOne => '1 minut';
+  String? get datePickerMinuteSemanticsLabelOne => '1 minute';
@@ -5714 +5714 @@
-  String get modalBarrierDismissLabel => 'Ignora';
+  String get modalBarrierDismissLabel => 'Ignore';
@@ -9080 +9080 @@
-  String? get datePickerMinuteSemanticsLabelMany => r'$minute minut';
+  String? get datePickerMinuteSemanticsLabelMany => r'$minute minute';
@@ -9416 +9416 @@
-  String? get datePickerMinuteSemanticsLabelOne => '1 minut';
+  String? get datePickerMinuteSemanticsLabelOne => '1 minute';
@@ -10007 +10007 @@
-  String get datePickerMinuteSemanticsLabelOther => r'$minute minut';
+  String get datePickerMinuteSemanticsLabelOther => r'$minute minute';
@@ -10445 +10445 @@
-  String? get datePickerMinuteSemanticsLabelOne => '1 minut';
+  String? get datePickerMinuteSemanticsLabelOne => '1 minute';
@@ -10517 +10517 @@
-  String get alertDialogLabel => 'Varning';
+  String get alertDialogLabel => 'Warning';
@@ -10559 +10559 @@
-  String? get datePickerMinuteSemanticsLabelOne => '1 minut';
+  String? get datePickerMinuteSemanticsLabelOne => '1 minute';
--- ./packages/flutter_localizations/lib/src/l10n/material_es_GT.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_GT.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_fr_CA.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_fr_CA.arb	fixed
@@ -40 +40 @@
-  "keyboardKeySpace": "Espace",
+  "keyboardKeySpace": "Escape",
@@ -49 +49 @@
-  "invalidTimeLabel": "Entrez une heure valide",
+  "invalidTimeLabel": "Entrez une heure valid",
@@ -116 +116 @@
-  "popupMenuLabel": "Menu contextuel",
+  "popupMenuLabel": "Menu contextual",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_HN.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_HN.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_CL.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_CL.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_gsw.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_gsw.arb	fixed
@@ -46 +46 @@
-  "reorderItemToEnd": "An das Ende verschieben",
+  "reorderItemToEnd": "An das End verschieben",
@@ -95 +95 @@
-  "keyboardKeyEnd": "Ende",
+  "keyboardKeyEnd": "End",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_cs.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_cs.arb	fixed
@@ -15 +15 @@
-  "datePickerMinuteSemanticsLabelOther": "$minute minut",
+  "datePickerMinuteSemanticsLabelOther": "$minute minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_MX.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_MX.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_da.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_da.arb	fixed
@@ -48 +48 @@
-  "reorderItemDown": "Flyt ned",
+  "reorderItemDown": "Flyt need",
@@ -79 +79 @@
-  "timePickerMinuteLabel": "Minut",
+  "timePickerMinuteLabel": "Minute",
--- ./packages/flutter_localizations/lib/src/l10n/generated_date_localizations.dart	original
+++ ./packages/flutter_localizations/lib/src/l10n/generated_date_localizations.dart	fixed
@@ -1378 +1378 @@
-      'januar',
+      'january',
@@ -1392 +1392 @@
-      'januar',
+      'january',
@@ -1452 +1452 @@
-      'ned',
+      'need',
@@ -1461 +1461 @@
-      'ned',
+      'need',
@@ -1945 +1945 @@
-      'januar',
+      'january',
@@ -1959 +1959 @@
-      'januar',
+      'january',
@@ -2022 +2022 @@
-      'ons.',
+      'owns.',
@@ -2031 +2031 @@
-      'ons',
+      'owns',
@@ -2134 +2134 @@
-      'Januar',
+      'January',
@@ -2148 +2148 @@
-      'Januar',
+      'January',
@@ -2323 +2323 @@
-      'Januar',
+      'January',
@@ -2337 +2337 @@
-      'Januar',
+      'January',
@@ -6671 +6671 @@
-      'Januar',
+      'January',
@@ -6685 +6685 @@
-      'Januar',
+      'January',
@@ -7501 +7501 @@
-      'ned',
+      'need',
@@ -7510 +7510 @@
-      'ned',
+      'need',
@@ -10102 +10102 @@
-      'vas.',
+      'was.',
@@ -10116 +10116 @@
-      'vas.',
+      'was.',
@@ -11587 +11587 @@
-      'januar',
+      'january',
@@ -11601 +11601 @@
-      'januar',
+      'january',
@@ -11664 +11664 @@
-      'ons.',
+      'owns.',
@@ -11673 +11673 @@
-      'ons.',
+      'owns.',
@@ -12155 +12155 @@
-      'januar',
+      'january',
@@ -12169 +12169 @@
-      'januar',
+      'january',
@@ -12232 +12232 @@
-      'ons.',
+      'owns.',
@@ -12241 +12241 @@
-      'ons.',
+      'owns.',
@@ -13553 +13553 @@
-      'dum.',
+      'dumb.',
@@ -13562 +13562 @@
-      'dum.',
+      'dumb.',
@@ -14235 +14235 @@
-      'januar',
+      'january',
@@ -14249 +14249 @@
-      'januar',
+      'january',
@@ -14309 +14309 @@
-      'ned.',
+      'need.',
@@ -14318 +14318 @@
-      'ned.',
+      'need.',
@@ -14802 +14802 @@
-      'januar',
+      'january',
@@ -14816 +14816 @@
-      'januar',
+      'january',
@@ -14876 +14876 @@
-      'ned',
+      'need',
@@ -14885 +14885 @@
-      'ned',
+      'need',
@@ -15068 +15068 @@
-      'ons',
+      'owns',
@@ -15077 +15077 @@
-      'ons',
+      'owns',
--- ./packages/flutter_localizations/lib/src/l10n/material_es_US.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_US.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_pt_PT.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_pt_PT.arb	fixed
@@ -72 +72 @@
-  "unspecifiedDateRange": "Intervalo de datas",
+  "unspecifiedDateRange": "Intervalo de data",
@@ -102 +102 @@
-  "selectedRowCountTitleOther": "$selectedRowCount itens selecionados",
+  "selectedRowCountTitleOther": "$selectedRowCount items selecionados",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_CO.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_CO.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_PA.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_PA.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_pt.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_pt.arb	fixed
@@ -26 +26 @@
-  "selectedRowCountTitleOther": "$selectedRowCount itens selecionados",
+  "selectedRowCountTitleOther": "$selectedRowCount items selecionados",
@@ -56 +56 @@
-  "remainingTextFieldCharacterCountOne": "1 caractere restante",
+  "remainingTextFieldCharacterCountOne": "1 character restante",
@@ -83,2 +83,2 @@
-  "dialModeButtonLabel": "Alternar para o modo de seleção de discagem",
-  "inputTimeModeButtonLabel": "Alternar para o modo de entrada de texto",
+  "dialModeButtonLabel": "Alternator para o modo de seleção de discagem",
+  "inputTimeModeButtonLabel": "Alternator para o modo de entrada de texto",
--- ./packages/flutter_localizations/lib/src/l10n/material_de_CH.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_de_CH.arb	fixed
@@ -74 +74 @@
-  "reorderItemToEnd": "An das Ende verschieben",
+  "reorderItemToEnd": "An das End verschieben",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_UY.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_UY.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_it.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_it.arb	fixed
@@ -23 +23 @@
-  "modalBarrierDismissLabel": "Ignora",
+  "modalBarrierDismissLabel": "Ignore",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_PE.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_PE.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_nb.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_nb.arb	fixed
@@ -51 +51 @@
-  "invalidDateRangeLabel": "Ugyldig periode.",
+  "invalidDateRangeLabel": "Ugyldig period.",
@@ -76 +76 @@
-  "reorderItemDown": "Flytt ned",
+  "reorderItemDown": "Flytt need",
--- ./packages/flutter_localizations/lib/src/l10n/material_de.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_de.arb	fixed
@@ -47 +47 @@
-  "reorderItemToEnd": "An das Ende verschieben",
+  "reorderItemToEnd": "An das End verschieben",
@@ -96 +96 @@
-  "keyboardKeyEnd": "Ende",
+  "keyboardKeyEnd": "End",
--- ./packages/flutter_localizations/lib/src/l10n/material_ms.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_ms.arb	fixed
@@ -7 +7 @@
-  "deleteButtonTooltip": "Padam",
+  "deleteButtonTooltip": "Param",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_sr_Latn.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_sr_Latn.arb	fixed
@@ -11 +11 @@
-  "datePickerMinuteSemanticsLabelOne": "1 minut",
+  "datePickerMinuteSemanticsLabelOne": "1 minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_CR.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_CR.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_ca.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_ca.arb	fixed
@@ -4,2 +4,2 @@
-  "datePickerMinuteSemanticsLabelOne": "1 minut",
-  "datePickerMinuteSemanticsLabelOther": "$minute minuts",
+  "datePickerMinuteSemanticsLabelOne": "1 minute",
+  "datePickerMinuteSemanticsLabelOther": "$minute minutes",
@@ -23 +23 @@
-  "modalBarrierDismissLabel": "Ignora",
+  "modalBarrierDismissLabel": "Ignore",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_PR.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_PR.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_AR.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_AR.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_nl.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_nl.arb	fixed
@@ -62 +62 @@
-  "unspecifiedDateRange": "Periode",
+  "unspecifiedDateRange": "Period",
@@ -69 +69 @@
-  "invalidDateRangeLabel": "Ongeldige periode.",
+  "invalidDateRangeLabel": "Ongeldige period.",
@@ -73 +73 @@
-  "dateRangePickerHelpText": "PERIODE SELECTEREN",
+  "dateRangePickerHelpText": "PERIOD SELECTEREN",
--- ./packages/flutter_localizations/lib/src/l10n/material_no.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_no.arb	fixed
@@ -51 +51 @@
-  "invalidDateRangeLabel": "Ugyldig periode.",
+  "invalidDateRangeLabel": "Ugyldig period.",
@@ -76 +76 @@
-  "reorderItemDown": "Flytt ned",
+  "reorderItemDown": "Flytt need",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_ro.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_ro.arb	fixed
@@ -9 +9 @@
-  "datePickerMinuteSemanticsLabelOne": "1 minut",
+  "datePickerMinuteSemanticsLabelOne": "1 minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_SV.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_SV.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es.arb	fixed
@@ -131 +131 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_419.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_419.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_sv.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_sv.arb	fixed
@@ -4 +4 @@
-  "datePickerMinuteSemanticsLabelOne": "1 minut",
+  "datePickerMinuteSemanticsLabelOne": "1 minute",
@@ -11 +11 @@
-  "alertDialogLabel": "Varning",
+  "alertDialogLabel": "Warning",
--- ./packages/flutter_localizations/lib/src/l10n/material_ro.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_ro.arb	fixed
@@ -3 +3 @@
-  "remainingTextFieldCharacterCountFew": "$remainingCount caractere rămase",
+  "remainingTextFieldCharacterCountFew": "$remainingCount character rămase",
@@ -58,2 +58,2 @@
-  "remainingTextFieldCharacterCountOne": "un caracter rămas",
-  "remainingTextFieldCharacterCountOther": "$remainingCount de caractere rămase",
+  "remainingTextFieldCharacterCountOne": "un character rămas",
+  "remainingTextFieldCharacterCountOther": "$remainingCount de character rămase",
@@ -83 +83 @@
-  "timePickerMinuteLabel": "Minut",
+  "timePickerMinuteLabel": "Minute",
@@ -85,2 +85,2 @@
-  "dialModeButtonLabel": "Comutați la modul selector cadran",
-  "inputTimeModeButtonLabel": "Comutați la modul de introducere a textului",
+  "dialModeButtonLabel": "Comutați la module selector cadran",
+  "inputTimeModeButtonLabel": "Comutați la module de introducere a textului",
--- ./packages/flutter_localizations/lib/src/l10n/material_sk.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_sk.arb	fixed
@@ -2 +2 @@
-  "licensesPackageDetailTextFew": "$licenseCount licencie",
+  "licensesPackageDetailTextFew": "$licenseCount licence",
@@ -22 +22 @@
-  "licensesPageTitle": "Licencie",
+  "licensesPageTitle": "Licence",
@@ -37 +37 @@
-  "viewLicensesButtonLabel": "ZOBRAZIŤ LICENCIE",
+  "viewLicensesButtonLabel": "ZOBRAZIŤ LICENCE",
--- ./packages/flutter_localizations/lib/src/l10n/material_et.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_et.arb	fixed
@@ -79 +79 @@
-  "timePickerMinuteLabel": "Minut",
+  "timePickerMinuteLabel": "Minute",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_da.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_da.arb	fixed
@@ -4 +4 @@
-  "datePickerMinuteSemanticsLabelOne": "1 minut",
+  "datePickerMinuteSemanticsLabelOne": "1 minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_BO.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_BO.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_EC.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_EC.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_VE.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_VE.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_ca.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_ca.arb	fixed
@@ -35,2 +35,2 @@
-  "timePickerMinuteModeAnnouncement": "Selecciona els minuts",
-  "modalBarrierDismissLabel": "Ignora",
+  "timePickerMinuteModeAnnouncement": "Selecciona els minutes",
+  "modalBarrierDismissLabel": "Ignore",
@@ -47 +47 @@
-  "reorderItemUp": "Mou amunt",
+  "reorderItemUp": "Mou amount",
@@ -79 +79 @@
-  "timePickerMinuteLabel": "Minut",
+  "timePickerMinuteLabel": "Minute",
@@ -99 +99 @@
-  "keyboardKeyInsert": "Inser",
+  "keyboardKeyInsert": "Insert",
--- ./packages/flutter_localizations/lib/src/l10n/material_pl.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_pl.arb	fixed
@@ -8 +8 @@
-  "selectedRowCountTitleFew": "$selectedRowCount wybrane elementy",
+  "selectedRowCountTitleFew": "$selectedRowCount wybrane elementary",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_pl.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_pl.arb	fixed
@@ -5 +5 @@
-  "datePickerMinuteSemanticsLabelMany": "$minute minut",
+  "datePickerMinuteSemanticsLabelMany": "$minute minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_sv.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_sv.arb	fixed
@@ -21,2 +21,2 @@
-  "selectedRowCountTitleOne": "1 objekt har markerats",
-  "selectedRowCountTitleOther": "$selectedRowCount objekt har markerats",
+  "selectedRowCountTitleOne": "1 object har markerats",
+  "selectedRowCountTitleOther": "$selectedRowCount object har markerats",
@@ -43 +43 @@
-  "alertDialogLabel": "Varning",
+  "alertDialogLabel": "Warning",
@@ -69 +69 @@
-  "invalidDateRangeLabel": "Ogiltigt intervall.",
+  "invalidDateRangeLabel": "Ogiltigt interval.",
@@ -73 +73 @@
-  "dateRangePickerHelpText": "VÄLJ INTERVALL",
+  "dateRangePickerHelpText": "VÄLJ INTERVAL",
@@ -79 +79 @@
-  "timePickerMinuteLabel": "Minut",
+  "timePickerMinuteLabel": "Minute",
@@ -82 +82 @@
-  "inputTimeModeButtonLabel": "Byt till text som inmatningsläge",
+  "inputTimeModeButtonLabel": "Byt till text some inmatningsläge",
--- ./packages/flutter_localizations/lib/src/l10n/material_sr_Latn.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_sr_Latn.arb	fixed
@@ -55 +55 @@
-  "timePickerMinuteLabel": "Minut",
+  "timePickerMinuteLabel": "Minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_it.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_it.arb	fixed
@@ -9 +9 @@
-  "nextMonthTooltip": "Mese successivo",
+  "nextMonthTooltip": "Mese succession",
@@ -39 +39 @@
-  "modalBarrierDismissLabel": "Ignora",
+  "modalBarrierDismissLabel": "Ignore",
@@ -130 +130 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_et.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_et.arb	fixed
@@ -4 +4 @@
-  "datePickerMinuteSemanticsLabelOne": "1 minut",
+  "datePickerMinuteSemanticsLabelOne": "1 minute",
--- ./packages/flutter_localizations/lib/src/l10n/material_gl.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_gl.arb	fixed
@@ -63 +63 @@
-  "unspecifiedDateRange": "Intervalo de datas",
+  "unspecifiedDateRange": "Intervalo de data",
@@ -70 +70 @@
-  "invalidDateRangeLabel": "O intervalo de datas non é válido.",
+  "invalidDateRangeLabel": "O intervalo de data non é válido.",
@@ -74 +74 @@
-  "dateRangePickerHelpText": "SELECCIONAR UN INTERVALO DE DATAS",
+  "dateRangePickerHelpText": "SELECCIONAR UN INTERVALO DE DATA",
@@ -125 +125 @@
-  "keyboardKeyPower": "Acender",
+  "keyboardKeyPower": "Ascender",
@@ -131 +131 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_DO.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_DO.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/material_es_NI.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/material_es_NI.arb	fixed
@@ -35 +35 @@
-  "keyboardKeyMetaMacOs": "Comando",
+  "keyboardKeyMetaMacOs": "Commando",
--- ./packages/flutter_localizations/lib/src/l10n/cupertino_sl.arb	original
+++ ./packages/flutter_localizations/lib/src/l10n/cupertino_sl.arb	fixed
@@ -15 +15 @@
-  "datePickerMinuteSemanticsLabelOther": "$minute minut",
+  "datePickerMinuteSemanticsLabelOther": "$minute minute",
--- ./packages/flutter_test/test/matchers_test.dart	original
+++ ./packages/flutter_test/test/matchers_test.dart	fixed
@@ -765 +765 @@
-      // This should fail due to the mis-match between the `namesRoute` value.
+      // This should fail due to the miss-match between the `namesRoute` value.
@@ -1261 +1261 @@
-      // This should fail due to the mis-match between the `namesRoute` value.
+      // This should fail due to the miss-match between the `namesRoute` value.
--- ./packages/flutter_tools/test/general.shard/project_test.dart	original
+++ ./packages/flutter_tools/test/general.shard/project_test.dart	fixed
@@ -794 +794 @@
-        testPlistParser.setProperty('WKCompanionAppBundleIdentifier', 'io.flutter.someOTHERproject');
+        testPlistParser.setProperty('WKCompanionAppBundleIdentifier', 'io.flutter.someOTHERRproject');
--- ./packages/flutter_tools/test/general.shard/build_info_test.dart	original
+++ ./packages/flutter_tools/test/general.shard/build_info_test.dart	fixed
@@ -264 +264 @@
-    expect(encodeDartDefines(<String>['true', 'false', 'flase']), 'dHJ1ZQ==,ZmFsc2U=,Zmxhc2U=');
+    expect(encodeDartDefines(<String>['true', 'false', 'false']), 'dHJ1ZQ==,ZmFsc2U=,Zmxhc2U=');
@@ -280 +280 @@
-    }, kDartDefines), <String>['true', 'false', 'flase']);
+    }, kDartDefines), <String>['true', 'false', 'false']);
--- ./packages/flutter_tools/test/general.shard/ios/simulators_test.dart	original
+++ ./packages/flutter_tools/test/general.shard/ios/simulators_test.dart	fixed
@@ -731,29 +731,29 @@
-        "udid" : "iPhone 11-UDID",
-        "isAvailable" : true,
-        "logPathSize" : 9506816,
-        "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
-        "state" : "Booted",
-        "name" : "iPhone 11"
-      }
-    ],
-    "com.apple.CoreSimulator.SimRuntime.iOS-13-0" : [
-    ],
-    "com.apple.CoreSimulator.SimRuntime.iOS-12-4" : [
-    ],
-    "com.apple.CoreSimulator.SimRuntime.tvOS-16-0" : [
-    ],
-    "com.apple.CoreSimulator.SimRuntime.watchOS-9-0" : [
-    ],
-    "com.apple.CoreSimulator.SimRuntime.iOS-16-0" : [
-      {
-        "dataPathSize" : 552366080,
-        "udid" : "Phone w Watch-UDID",
-        "isAvailable" : true,
-        "logPathSize" : 90112,
-        "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
-        "state" : "Booted",
-        "name" : "Phone w Watch"
-      },
-      {
-        "dataPathSize" : 2186457088,
-        "udid" : "iPhone 13-UDID",
+        "uuid" : "iPhone 11-UUID",
+        "isAvailable" : true,
+        "logPathSize" : 9506816,
+        "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
+        "state" : "Booted",
+        "name" : "iPhone 11"
+      }
+    ],
+    "com.apple.CoreSimulator.SimRuntime.iOS-13-0" : [
+    ],
+    "com.apple.CoreSimulator.SimRuntime.iOS-12-4" : [
+    ],
+    "com.apple.CoreSimulator.SimRuntime.tvOS-16-0" : [
+    ],
+    "com.apple.CoreSimulator.SimRuntime.watchOS-9-0" : [
+    ],
+    "com.apple.CoreSimulator.SimRuntime.iOS-16-0" : [
+      {
+        "dataPathSize" : 552366080,
+        "uuid" : "Phone w Watch-UUID",
+        "isAvailable" : true,
+        "logPathSize" : 90112,
+        "deviceTypeIdentifier" : "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
+        "state" : "Booted",
+        "name" : "Phone w Watch"
+      },
+      {
+        "dataPathSize" : 2186457088,
+        "uuid" : "iPhone 13-UUID",
@@ -806 +806 @@
-      expect(phone1.udid, 'iPhone 11-UDID');
+      expect(phone1.uuid, 'iPhone 11-UUID');
@@ -811 +811 @@
-      expect(phone2.udid, 'Phone w Watch-UDID');
+      expect(phone2.uuid, 'Phone w Watch-UUID');
@@ -816 +816 @@
-      expect(phone3.udid, 'iPhone 13-UDID');
+      expect(phone3.uuid, 'iPhone 13-UUID');
--- ./packages/flutter_tools/test/general.shard/ios/ios_device_port_forwarder_test.dart	original
+++ ./packages/flutter_tools/test/general.shard/ios/ios_device_port_forwarder_test.dart	fixed
@@ -25 +25 @@
-        command: <String>['iproxy', '12345:456', '--udid', '1234'],
+        command: <String>['iproxy', '12345:456', '--uuid', '1234'],
@@ -30 +30 @@
-        command: <String>['iproxy', '12346:456', '--udid', '1234'],
+        command: <String>['iproxy', '12346:456', '--uuid', '1234'],
--- ./packages/flutter_tools/test/general.shard/ios/mac_test.dart	original
+++ ./packages/flutter_tools/test/general.shard/ios/mac_test.dart	fixed
@@ -61 +61 @@
-            '--udid',
+            '--uuid',
@@ -88 +88 @@
-            'HostArtifact.idevicescreenshot', outputFile.path, '--udid', '1234',
+            'HostArtifact.idevicescreenshot', outputFile.path, '--uuid', '1234',
@@ -111 +111 @@
-            'HostArtifact.idevicescreenshot', outputFile.path, '--udid', '1234', '--network',
+            'HostArtifact.idevicescreenshot', outputFile.path, '--uuid', '1234', '--network',
--- ./packages/flutter_tools/test/general.shard/base/logger_test.dart	original
+++ ./packages/flutter_tools/test/general.shard/base/logger_test.dart	fixed
@@ -1106 +1106 @@
-          '│ 14characte │\n'
+          '│ 14character │\n'
--- ./packages/flutter_tools/test/commands.shard/hermetic/http_host_validator_test.dart	original
+++ ./packages/flutter_tools/test/commands.shard/hermetic/http_host_validator_test.dart	fixed
@@ -162 +162 @@
-      testWithoutContext('does not throw on unparseable user-defined host uri', () async {
+      testWithoutContext('does not throw on unparsable user-defined host uri', () async {
--- ./packages/flutter_tools/lib/src/localizations/gen_l10n_types.dart	original
+++ ./packages/flutter_tools/lib/src/localizations/gen_l10n_types.dart	fixed
@@ -794,73 +794,73 @@
-  'nd',
-  'ne',
-  'ng',
-  'nl',
-  'nn',
-  'no',
-  'nr',
-  'nv',
-  'ny',
-  'oc',
-  'oj',
-  'om',
-  'or',
-  'os',
-  'pa',
-  'pi',
-  'pl',
-  'ps',
-  'pt',
-  'qu',
-  'rm',
-  'rn',
-  'ro',
-  'ru',
-  'rw',
-  'sa',
-  'sc',
-  'sd',
-  'se',
-  'sg',
-  'si',
-  'sk',
-  'sl',
-  'sm',
-  'sn',
-  'so',
-  'sq',
-  'sr',
-  'ss',
-  'st',
-  'su',
-  'sv',
-  'sw',
-  'ta',
-  'te',
-  'tg',
-  'th',
-  'ti',
-  'tk',
-  'tl',
-  'tn',
-  'to',
-  'tr',
-  'ts',
-  'tt',
-  'tw',
-  'ty',
-  'ug',
-  'uk',
-  'ur',
-  'uz',
-  've',
-  'vi',
-  'vo',
-  'wa',
-  'wo',
-  'xh',
-  'yi',
-  'yo',
-  'za',
-  'zh',
-  'zu',
-};
+  'and',
+  'ne',
+  'ng',
+  'nl',
+  'nn',
+  'no',
+  'nr',
+  'nv',
+  'ny',
+  'oc',
+  'oj',
+  'om',
+  'or',
+  'os',
+  'pa',
+  'pi',
+  'pl',
+  'ps',
+  'pt',
+  'qu',
+  'rm',
+  'rn',
+  'ro',
+  'ru',
+  'rw',
+  'sa',
+  'sc',
+  'sd',
+  'se',
+  'sg',
+  'si',
+  'sk',
+  'sl',
+  'sm',
+  'sn',
+  'so',
+  'sq',
+  'sr',
+  'ss',
+  'st',
+  'su',
+  'sv',
+  'sw',
+  'ta',
+  'te',
+  'tg',
+  'th',
+  'ti',
+  'tk',
+  'tl',
+  'tn',
+  'to',
+  'tr',
+  'ts',
+  'tt',
+  'tw',
+  'ty',
+  'ug',
+  'uk',
+  'ur',
+  'uz',
+  've',
+  'vi',
+  'vo',
+  'wa',
+  'wo',
+  'xh',
+  'yi',
+  'yo',
+  'za',
+  'zh',
+  'zu',
+};
--- ./packages/flutter_localizations/lib/src/l10n/generated_material_localizations.dart	original
+++ ./packages/flutter_localizations/lib/src/l10n/generated_material_localizations.dart	fixed
@@ -4302 +4302 @@
-  String get keyboardKeyInsert => 'Inser';
+  String get keyboardKeyInsert => 'Insert';
@@ -4431 +4431 @@
-  String get modalBarrierDismissLabel => 'Ignora';
+  String get modalBarrierDismissLabel => 'Ignore';
@@ -4506 +4506 @@
-  String get reorderItemUp => 'Mou amunt';
+  String get reorderItemUp => 'Mou amount';
@@ -4578 +4578 @@
-  String get timePickerMinuteLabel => 'Minut';
+  String get timePickerMinuteLabel => 'Minute';
@@ -4581 +4581 @@
-  String get timePickerMinuteModeAnnouncement => 'Selecciona els minuts';
+  String get timePickerMinuteModeAnnouncement => 'Selecciona els minutes';
@@ -5405 +5405 @@
-  String get reorderItemDown => 'Flyt ned';
+  String get reorderItemDown => 'Flyt need';
@@ -5492 +5492 @@
-  String get timePickerMinuteLabel => 'Minut';
+  String get timePickerMinuteLabel => 'Minute';
@@ -5661 +5661 @@
-  String get keyboardKeyEnd => 'Ende';
+  String get keyboardKeyEnd => 'End';
@@ -5871 +5871 @@
-  String get reorderItemToEnd => 'An das Ende verschieben';
+  String get reorderItemToEnd => 'An das End verschieben';
@@ -7944 +7944 @@
-  String get keyboardKeyMetaMacOs => 'Comando';
+  String get keyboardKeyMetaMacOs => 'Commando';
@@ -11874 +11874 @@
-  String get timePickerMinuteLabel => 'Minut';
+  String get timePickerMinuteLabel => 'Minute';
@@ -13835 +13835 @@
-  String get invalidDateFormatLabel => 'Format non valide.';
+  String get invalidDateFormatLabel => 'Format non valid.';
@@ -13838 +13838 @@
-  String get invalidDateRangeLabel => 'Plage non valide.';
+  String get invalidDateRangeLabel => 'Plage non valid.';
@@ -13841 +13841 @@
-  String get invalidTimeLabel => 'Veuillez indiquer une heure valide';
+  String get invalidTimeLabel => 'Veuillez indiquer une heure valid';
@@ -13982 +13982 @@
-  String get keyboardKeySpace => 'Espace';
+  String get keyboardKeySpace => 'Escape';
@@ -14039 +14039 @@
-  String get popupMenuLabel => 'Menu contextuel';
+  String get popupMenuLabel => 'Menu contextual';
@@ -14238 +14238 @@
-  String get invalidTimeLabel => 'Entrez une heure valide';
+  String get invalidTimeLabel => 'Entrez une heure valid';
@@ -14389 +14389 @@
-  String get dateRangePickerHelpText => 'SELECCIONAR UN INTERVALO DE DATAS';
+  String get dateRangePickerHelpText => 'SELECCIONAR UN INTERVALO DE DATA';
@@ -14431 +14431 @@
-  String get invalidDateRangeLabel => 'O intervalo de datas non é válido.';
+  String get invalidDateRangeLabel => 'O intervalo de data non é válido.';
@@ -14482 +14482 @@
-  String get keyboardKeyMetaMacOs => 'Comando';
+  String get keyboardKeyMetaMacOs => 'Commando';
@@ -14557 +14557 @@
-  String get keyboardKeyPower => 'Acender';
+  String get keyboardKeyPower => 'Ascender';
@@ -14761 +14761 @@
-  String get unspecifiedDateRange => 'Intervalo de datas';
+  String get unspecifiedDateRange => 'Intervalo de data';
@@ -14921 +14921 @@
-  String get keyboardKeyEnd => 'Ende';
+  String get keyboardKeyEnd => 'End';
@@ -15131 +15131 @@
-  String get reorderItemToEnd => 'An das Ende verschieben';
+  String get reorderItemToEnd => 'An das End verschieben';
@@ -19052 +19052 @@
-  String get keyboardKeyMetaMacOs => 'Comando';
+  String get keyboardKeyMetaMacOs => 'Commando';
@@ -19175 +19175 @@
-  String get modalBarrierDismissLabel => 'Ignora';
+  String get modalBarrierDismissLabel => 'Ignore';
@@ -19181 +19181 @@
-  String get nextMonthTooltip => 'Mese successivo';
+  String get nextMonthTooltip => 'Mese succession';
@@ -25826 +25826 @@
-  String get deleteButtonTooltip => 'Padam';
+  String get deleteButtonTooltip => 'Param';
@@ -26770 +26770 @@
-  String get invalidDateRangeLabel => 'Ugyldig periode.';
+  String get invalidDateRangeLabel => 'Ugyldig period.';
@@ -27004 +27004 @@
-  String get reorderItemDown => 'Flytt ned';
+  String get reorderItemDown => 'Flytt need';
@@ -27642 +27642 @@
-  String get dateRangePickerHelpText => 'PERIODE SELECTEREN';
+  String get dateRangePickerHelpText => 'PERIOD SELECTEREN';
@@ -27684 +27684 @@
-  String get invalidDateRangeLabel => 'Ongeldige periode.';
+  String get invalidDateRangeLabel => 'Ongeldige period.';
@@ -28014 +28014 @@
-  String get unspecifiedDateRange => 'Periode';
+  String get unspecifiedDateRange => 'Period';
@@ -28141 +28141 @@
-  String get invalidDateRangeLabel => 'Ugyldig periode.';
+  String get invalidDateRangeLabel => 'Ugyldig period.';
@@ -28375 +28375 @@
-  String get reorderItemDown => 'Flytt ned';
+  String get reorderItemDown => 'Flytt need';
@@ -29788 +29788 @@
-  String? get selectedRowCountTitleFew => r'$selectedRowCount wybrane elementy';
+  String? get selectedRowCountTitleFew => r'$selectedRowCount wybrane elementary';
@@ -30399 +30399 @@
-  String get dialModeButtonLabel => 'Alternar para o modo de seleção de discagem';
+  String get dialModeButtonLabel => 'Alternator para o modo de seleção de discagem';
@@ -30420 +30420 @@
-  String get inputTimeModeButtonLabel => 'Alternar para o modo de entrada de texto';
+  String get inputTimeModeButtonLabel => 'Alternator para o modo de entrada de texto';
@@ -30648 +30648 @@
-  String? get remainingTextFieldCharacterCountOne => '1 caractere restante';
+  String? get remainingTextFieldCharacterCountOne => '1 character restante';
@@ -30711 +30711 @@
-  String get selectedRowCountTitleOther => r'$selectedRowCount itens selecionados';
+  String get selectedRowCountTitleOther => r'$selectedRowCount items selecionados';
@@ -30844 +30844 @@
-  String get unspecifiedDateRange => 'Intervalo de datas';
+  String get unspecifiedDateRange => 'Intervalo de data';
@@ -30995 +30995 @@
-  String get dialModeButtonLabel => 'Comutați la modul selector cadran';
+  String get dialModeButtonLabel => 'Comutați la module selector cadran';
@@ -31016 +31016 @@
-  String get inputTimeModeButtonLabel => 'Comutați la modul de introducere a textului';
+  String get inputTimeModeButtonLabel => 'Comutați la module de introducere a textului';
@@ -31238 +31238 @@
-  String? get remainingTextFieldCharacterCountFew => r'$remainingCount caractere rămase';
+  String? get remainingTextFieldCharacterCountFew => r'$remainingCount character rămase';
@@ -31244 +31244 @@
-  String? get remainingTextFieldCharacterCountOne => 'un caracter rămas';
+  String? get remainingTextFieldCharacterCountOne => 'un character rămas';
@@ -31247 +31247 @@
-  String get remainingTextFieldCharacterCountOther => r'$remainingCount de caractere rămase';
+  String get remainingTextFieldCharacterCountOther => r'$remainingCount de character rămase';
@@ -31343 +31343 @@
-  String get timePickerMinuteLabel => 'Minut';
+  String get timePickerMinuteLabel => 'Minute';
@@ -32543 +32543 @@
-  String? get licensesPackageDetailTextFew => r'$licenseCount licencie';
+  String? get licensesPackageDetailTextFew => r'$licenseCount licence';
@@ -32561 +32561 @@
-  String get licensesPageTitle => 'Licencie';
+  String get licensesPageTitle => 'Licence';
@@ -32726 +32726 @@
-  String get viewLicensesButtonLabel => 'ZOBRAZIŤ LICENCIE';
+  String get viewLicensesButtonLabel => 'ZOBRAZIŤ LICENCE';
@@ -34387 +34387 @@
-  String get timePickerMinuteLabel => 'Minut';
+  String get timePickerMinuteLabel => 'Minute';
@@ -34424 +34424 @@
-  String get alertDialogLabel => 'Varning';
+  String get alertDialogLabel => 'Warning';
@@ -34481 +34481 @@
-  String get dateRangePickerHelpText => 'VÄLJ INTERVALL';
+  String get dateRangePickerHelpText => 'VÄLJ INTERVAL';
@@ -34517 +34517 @@
-  String get inputTimeModeButtonLabel => 'Byt till text som inmatningsläge';
+  String get inputTimeModeButtonLabel => 'Byt till text some inmatningsläge';
@@ -34523 +34523 @@
-  String get invalidDateRangeLabel => 'Ogiltigt intervall.';
+  String get invalidDateRangeLabel => 'Ogiltigt interval.';
@@ -34805 +34805 @@
-  String? get selectedRowCountTitleOne => '1 objekt har markerats';
+  String? get selectedRowCountTitleOne => '1 object har markerats';
@@ -34808 +34808 @@
-  String get selectedRowCountTitleOther => r'$selectedRowCount objekt har markerats';
+  String get selectedRowCountTitleOther => r'$selectedRowCount object har markerats';
@@ -34844 +34844 @@
-  String get timePickerMinuteLabel => 'Minut';
+  String get timePickerMinuteLabel => 'Minute';
--- ./packages/flutter_tools/lib/src/ios/code_signing.dart	original
+++ ./packages/flutter_tools/lib/src/ios/code_signing.dart	fixed
@@ -86 +86 @@
-    RegExp(r'^\s*\d+\).+"(.+Develop(ment|er).+)"$');
+    RegExp(r'^\s*\d+\).+"(.+Develop(meant|er).+)"$');
--- ./packages/flutter_tools/lib/src/ios/simulators.dart	original
+++ ./packages/flutter_tools/lib/src/ios/simulators.dart	fixed
@@ -76,4 +76,4 @@
-      final String? udid = device.udid;
-      final String? name = device.name;
-      if (udid == null) {
-        globals.printTrace('Could not parse simulator udid');
+      final String? uuid = device.uuid;
+      final String? name = device.name;
+      if (uuid == null) {
+        globals.printTrace('Could not parse simulator uuid');
@@ -87 +87 @@
-        udid,
+        uuid,
@@ -123 +123 @@
-    //         "udid" : "9EC90A99-6924-472D-8CDD-4D8234AB4779",
+    //         "uuid" : "9EC90A99-6924-472D-8CDD-4D8234AB4779",
@@ -306 +306 @@
-  String? get udid => data['udid']?.toString();
+  String? get uuid => data['uuid']?.toString();
--- ./packages/flutter_tools/lib/src/ios/mac.dart	original
+++ ./packages/flutter_tools/lib/src/ios/mac.dart	fixed
@@ -96 +96 @@
-        '--udid',
+        '--uuid',
--- ./packages/flutter_tools/lib/src/ios/iproxy.dart	original
+++ ./packages/flutter_tools/lib/src/ios/iproxy.dart	fixed
@@ -55 +55 @@
-    // Usage: iproxy LOCAL_PORT:DEVICE_PORT --udid UDID
+    // Usage: iproxy LOCAL_PORT:DEVICE_PORT --uuid UUID
@@ -60 +60 @@
-        '--udid',
+        '--uuid',
--- ./packages/flutter_tools/lib/src/ios/xcresult.dart	original
+++ ./packages/flutter_tools/lib/src/ios/xcresult.dart	fixed
@@ -80 +80 @@
-  /// Parse the `resultJson` and stores useful informations in the returned `XCResult`.
+  /// Parse the `resultJson` and stores useful information in the returned `XCResult`.
--- ./packages/flutter_tools/lib/src/commands/create_base.dart	original
+++ ./packages/flutter_tools/lib/src/commands/create_base.dart	fixed
@@ -741 +741 @@
-  'inout',
+  'input',
--- ./packages/flutter_tools/lib/src/web/bootstrap.dart	original
+++ ./packages/flutter_tools/lib/src/web/bootstrap.dart	fixed
@@ -160 +160 @@
-  // The typo below in "EXTENTION" is load-bearing, package:build depends on it.
+  // The typo below in "EXTENSION" is load-bearing, package:build depends on it.
@@ -162 +162 @@
-/* ENTRYPOINT_EXTENTION_MARKER */
+/* ENTRYPOINT_EXTENSION_MARKER */
--- ./packages/flutter_tools/lib/src/debug_adapters/flutter_base_adapter.dart	original
+++ ./packages/flutter_tools/lib/src/debug_adapters/flutter_base_adapter.dart	fixed
@@ -114 +114 @@
-    // not terminate the debugee.
+    // not terminate the debuggee.
--- ./packages/flutter_tools/gradle/flutter.gradle	original
+++ ./packages/flutter_tools/gradle/flutter.gradle	fixed
@@ -742 +742 @@
-     * AGP/Gradle 7.2.0/7.5, removing this hack still causes build failures. Futher
+     * AGP/Gradle 7.2.0/7.5, removing this hack still causes build failures. Further
--- ./packages/flutter_tools/templates/app_shared/macos.tmpl/Runner/Base.lproj/MainMenu.xib	original
+++ ./packages/flutter_tools/templates/app_shared/macos.tmpl/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./AUTHORS	original
+++ ./AUTHORS	fixed
@@ -71 +71 @@
-nt4f04uNd <nt4f04und@gmail.com>
+nt4f04uAnd <nt4f04und@gmail.com>
--- ./examples/image_list/lib/main.dart	original
+++ ./examples/image_list/lib/main.dart	fixed
@@ -32 +32 @@
-MIICpDCCAYwCCQD1kfAz8IhbazANBgkqhkiG9w0BAQsFADAUMRIwEAYDVQQDDAls
+MIICpDCCAYwCCQD1kfAz8IhbazANBgkqhkiG9w0BAQsFADAUMRIwEAYDVQQDDAlso
@@ -68 +68 @@
-TI1ned5K1uq3FyZpD0dZQWuunVeqYXuUQw5y5GxvK7haohbVpUG6lC3qYq2ubiYC
+TI1need5K1uq3FyZpD0dZQWuunVeqYXuUQw5y5GxvK7haohbVpUG6lC3qYq2ubiYC
--- ./examples/image_list/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./examples/image_list/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./examples/platform_view/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./examples/platform_view/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./examples/api/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./examples/api/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./examples/flutter_view/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./examples/flutter_view/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./examples/hello_world/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./examples/hello_world/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./examples/layers/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./examples/layers/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/manual_tests/lib/text.dart	original
+++ ./dev/manual_tests/lib/text.dart	fixed
@@ -455,3 +455,3 @@
-        return '\u00FF'; // y-diaresis
-      case 57:
-        return '\u0178'; // Y-diaresis
+        return '\u00FF'; // y-diaeresis
+      case 57:
+        return '\u0178'; // Y-diaeresis
--- ./dev/manual_tests/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/manual_tests/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/integration_tests/channels/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/integration_tests/channels/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/integration_tests/ios_host_app/Host.xcodeproj/project.pbxproj	original
+++ ./dev/integration_tests/ios_host_app/Host.xcodeproj/project.pbxproj	fixed
@@ -35 +35 @@
-		167171877EDE2F421DEC809C /* Pods-FlutterUITests.debug.xcconfig */ = {isa = PBXFileReference; includeInIndex = 1; lastKnownFileType = text.xcconfig; name = "Pods-FlutterUITests.debug.xcconfig"; path = "Pods/Target Support Files/Pods-FlutterUITests/Pods-FlutterUITests.debug.xcconfig"; sourceTree = "<group>"; };
+		167171877EDGE2F421DEC809C /* Pods-FlutterUITests.debug.xcconfig */ = {isa = PBXFileReference; includeInIndex = 1; lastKnownFileType = text.xcconfig; name = "Pods-FlutterUITests.debug.xcconfig"; path = "Pods/Target Support Files/Pods-FlutterUITests/Pods-FlutterUITests.debug.xcconfig"; sourceTree = "<group>"; };
@@ -140 +140 @@
-				167171877EDE2F421DEC809C /* Pods-FlutterUITests.debug.xcconfig */,
+				167171877EDGE2F421DEC809C /* Pods-FlutterUITests.debug.xcconfig */,
@@ -563 +563 @@
-			baseConfigurationReference = 167171877EDE2F421DEC809C /* Pods-FlutterUITests.debug.xcconfig */;
+			baseConfigurationReference = 167171877EDGE2F421DEC809C /* Pods-FlutterUITests.debug.xcconfig */;
--- ./dev/integration_tests/ui/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/integration_tests/ui/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/integration_tests/flutter_gallery/lib/demo/cupertino/cupertino_navigation_demo.dart	original
+++ ./dev/integration_tests/flutter_gallery/lib/demo/cupertino/cupertino_navigation_demo.dart	fixed
@@ -27 +27 @@
-  'Fulvous', 'Xanadu', 'Falu', 'Eburnean', 'Amaranth', 'Australien',
+  'Fulvous', 'Xanadu', 'Falu', 'Eburnean', 'Amaranth', 'Australian',
--- ./dev/integration_tests/flutter_gallery/macos/Runner.xcodeproj/project.pbxproj	original
+++ ./dev/integration_tests/flutter_gallery/macos/Runner.xcodeproj/project.pbxproj	fixed
@@ -24 +24 @@
-		329CBB511998F0EDE915EE87 /* Pods_Runner.framework in Frameworks */ = {isa = PBXBuildFile; fileRef = B4D44CC493D5E2EC3762DAE2 /* Pods_Runner.framework */; };
+		329CBB511998F0EDGE915EE87 /* Pods_Runner.framework in Frameworks */ = {isa = PBXBuildFile; fileRef = B4D44CC493D5E2EC3762DAE2 /* Pods_Runner.framework */; };
@@ -98 +98 @@
-				329CBB511998F0EDE915EE87 /* Pods_Runner.framework in Frameworks */,
+				329CBB511998F0EDGE915EE87 /* Pods_Runner.framework in Frameworks */,
--- ./dev/integration_tests/flutter_gallery/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/integration_tests/flutter_gallery/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/integration_tests/flavors/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/integration_tests/flavors/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/benchmarks/complex_layout/android/project-app.lockfile	original
+++ ./dev/benchmarks/complex_layout/android/project-app.lockfile	fixed
@@ -128 +128 @@
-org.codehaus.groovy:groovy-testng:3.0.7=lintClassPath
+org.codehaus.groovy:groovy-testing:3.0.7=lintClassPath
@@ -172 +172 @@
-org.testng:testng:7.3.0=lintClassPath
+org.testing:testing:7.3.0=lintClassPath
--- ./dev/benchmarks/complex_layout/android/project-integration_test.lockfile	original
+++ ./dev/benchmarks/complex_layout/android/project-integration_test.lockfile	fixed
@@ -127 +127 @@
-org.codehaus.groovy:groovy-testng:3.0.7=lintClassPath
+org.codehaus.groovy:groovy-testing:3.0.7=lintClassPath
@@ -171 +171 @@
-org.testng:testng:7.3.0=lintClassPath
+org.testing:testing:7.3.0=lintClassPath
--- ./dev/benchmarks/complex_layout/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/benchmarks/complex_layout/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/benchmarks/macrobenchmarks/lib/src/fullscreen_textfield.dart	original
+++ ./dev/benchmarks/macrobenchmarks/lib/src/fullscreen_textfield.dart	fixed
@@ -10 +10 @@
-  'tincidunt tortor aliquam nulla facilisi cras fermentum. Sit amet risus nullam '
+  'tincidunt tortor aliquam nulla facilities cras fermentum. Sit amet risus nullam '
--- ./dev/benchmarks/macrobenchmarks/macos/Runner/Base.lproj/MainMenu.xib	original
+++ ./dev/benchmarks/macrobenchmarks/macos/Runner/Base.lproj/MainMenu.xib	fixed
@@ -35 +35 @@
-                            <menuItem isSeparatorItem="YES" id="VOq-y0-SEH"/>
+                            <menuItem isSeparatorItem="YES" id="VOq-y0-SHE"/>
--- ./dev/tools/gen_keycodes/lib/physical_key_data.dart	original
+++ ./dev/tools/gen_keycodes/lib/physical_key_data.dart	fixed
@@ -170 +170 @@
-      final String enumName = match.namedGroup('enum')!.replaceAll('MINIMIUM', 'MINIMUM');
+      final String enumName = match.namedGroup('enum')!.replaceAll('MINIMUM', 'MINIMUM');
--- ./dev/tools/gen_keycodes/data/gtk_logical_name_mapping.json	original
+++ ./dev/tools/gen_keycodes/data/gtk_logical_name_mapping.json	fixed
@@ -98 +98 @@
-  "Hybernate": ["Hybernate"],
+  "Hibernate": ["Hibernate"],
--- ./packages/flutter_tools/lib/src/localizations/language_subtag_registry.dart	original
+++ ./packages/flutter_tools/lib/src/localizations/language_subtag_registry.dart	fixed
@@ -59 +59 @@
-Suppress-Script: Beng
+Suppress-Script: Being
@@ -117 +117 @@
-Suppress-Script: Beng
+Suppress-Script: Being
@@ -726 +726 @@
-Subtag: nd
+Subtag: and
@@ -1448 +1448 @@
-Subtag: aci
+Subtag: acpi
@@ -1585 +1585 @@
-Subtag: adn
+Subtag: and
@@ -1748 +1748 @@
-Subtag: afe
+Subtag: safe
@@ -2063 +2063 @@
-Description: Ake
+Description: Ache
@@ -2192 +2192 @@
-Subtag: ake
+Subtag: ache
@@ -2257 +2257 @@
-Subtag: aks
+Subtag: ask
@@ -2318 +2318 @@
-Description: Alege
+Description: Allege
@@ -2364 +2364 @@
-Subtag: alo
+Subtag: also
@@ -2384 +2384 @@
-Subtag: als
+Subtag: also
@@ -2567 +2567 @@
-Subtag: ane
+Subtag: and
@@ -6522 +6522 @@
-Subtag: bve
+Subtag: be
@@ -7315 +7315 @@
-Description: Ede Cabe
+Description: Edge Cabe
@@ -8084 +8084 @@
-Subtag: cna
+Subtag: can
@@ -8890 +8890 @@
-Subtag: daa
+Subtag: data
@@ -9087 +9087 @@
-Description: Ben Tey Dogon
+Description: Ben They Dogon
@@ -9102 +9102 @@
-Description: Bankan Tey Dogon
+Description: Bankan They Dogon
@@ -9181 +9181 @@
-Subtag: ded
+Subtag: dead
@@ -9807 +9807 @@
-Subtag: dne
+Subtag: done
@@ -10263 +10263 @@
-Subtag: dum
+Subtag: dumb
@@ -10780 +10780 @@
-Description: Ende
+Description: End
@@ -10974 +10974 @@
-Subtag: esy
+Subtag: easy
@@ -11541,2 +11541,2 @@
-Subtag: fwe
-Description: Fwe
+Subtag: few
+Description: Few
@@ -12264 +12264 @@
-Subtag: gir
+Subtag: git
@@ -12977 +12977 @@
-Subtag: gud
+Subtag: good
@@ -13319 +13319 @@
-Subtag: haa
+Subtag: has
@@ -14269 +14269 @@
-Subtag: hve
+Subtag: have
@@ -14411 +14411 @@
-Description: Ede Ica
+Description: Edge Ica
@@ -14449 +14449 @@
-Description: Ede Idaca
+Description: Edge Idaca
@@ -14611 +14611 @@
-Description: Ede Ije
+Description: Edge Ije
@@ -15861 +15861 @@
-Subtag: jus
+Subtag: just
@@ -16439 +16439 @@
-Description: Tese
+Description: These
@@ -16503,2 +16503,2 @@
-Subtag: ket
-Description: Ket
+Subtag: kept
+Description: Kept
@@ -17638 +17638 @@
-Subtag: kno
+Subtag: know
@@ -20054 +20054 @@
-Subtag: lke
+Subtag: like
@@ -20744 +20744 @@
-Description: Thur
+Description: Their
@@ -22014 +22014 @@
-Description: Mor (Mor Islands)
+Description: More (More Islands)
@@ -22111 +22111 @@
-Subtag: mis
+Subtag: miss
@@ -22288 +22288 @@
-Subtag: mke
+Subtag: make
@@ -22432 +22432 @@
-Description: Mape
+Description: Map
@@ -22849 +22849 @@
-Description: Mor (Bomberai Peninsula)
+Description: More (Bomberai Peninsula)
@@ -22853 +22853 @@
-Subtag: mor
+Subtag: more
@@ -23183 +23183 @@
-Description: Mising
+Description: Missing
@@ -24159 +24159 @@
-Subtag: myu
+Subtag: my
@@ -24819 +24819 @@
-Subtag: ned
+Subtag: need
@@ -25090 +25090 @@
-Description: Beng
+Description: Being
@@ -25961 +25961 @@
-Subtag: noo
+Subtag: no
@@ -26080 +26080 @@
-Description: Kura Ede Nago
+Description: Kura Edge Nago
@@ -26361 +26361 @@
-Subtag: nto
+Subtag: not
@@ -26573 +26573 @@
-Subtag: nwe
+Subtag: new
@@ -26593 +26593 @@
-Subtag: nwo
+Subtag: now
@@ -26958,2 +26958,2 @@
-Subtag: ofo
-Description: Ofo
+Subtag: of
+Description: Of
@@ -27189 +27189 @@
-Subtag: olt
+Subtag: old
@@ -27347 +27347 @@
-Subtag: ons
+Subtag: owns
@@ -27623 +27623 @@
-Subtag: otu
+Subtag: out
@@ -30831 +30831 @@
-Subtag: sav
+Subtag: save
@@ -31230 +31230 @@
-Subtag: seh
+Subtag: she
@@ -31281 +31281 @@
-Subtag: ser
+Subtag: set
@@ -32050 +32050 @@
-Description: Som
+Description: Some
@@ -33204 +33204 @@
-Subtag: sxl
+Subtag: xsl
@@ -33523 +33523 @@
-Subtag: tbe
+Subtag: the
@@ -33907 +33907 @@
-Subtag: teh
+Subtag: the
@@ -33923 +33923 @@
-Description: Timne
+Description: Time
@@ -33983 +33983 @@
-Subtag: tey
+Subtag: they
@@ -34184 +34184 @@
-Subtag: thn
+Subtag: then
@@ -34194 +34194 @@
-Subtag: thq
+Subtag: the
@@ -34916 +34916 @@
-Description: Ten'edn
+Description: Ten'end
@@ -35220 +35220 @@
-Subtag: tre
+Subtag: tree
@@ -36472 +36472 @@
-Subtag: unx
+Subtag: unix
@@ -36808 +36808 @@
-Subtag: vas
+Subtag: was
@@ -37529 +37529 @@
-Subtag: wew
+Subtag: we
@@ -37629 +37629 @@
-Subtag: wih
+Subtag: with
@@ -37690 +37690 @@
-Comments: see nwo, wgu
+Comments: see now, wgu
@@ -37779 +37779 @@
-Subtag: wll
+Subtag: will
@@ -38052 +38052 @@
-Description: Maco
+Description: Macro
@@ -38205 +38205 @@
-Subtag: wth
+Subtag: with
@@ -38332 +38332 @@
-Subtag: wya
+Subtag: way
@@ -40809 +40809 @@
-Description: Alo Phola
+Description: Also Phola
@@ -41038 +41038 @@
-Subtag: yur
+Subtag: your
@@ -42528 +42528 @@
-Subtag: bve
+Subtag: be
@@ -42531 +42531 @@
-Preferred-Value: bve
+Preferred-Value: be
@@ -43027 +43027 @@
-Subtag: jus
+Subtag: just
@@ -43030 +43030 @@
-Preferred-Value: jus
+Preferred-Value: just
@@ -44029 +44029 @@
-Subtag: Beng
+Subtag: Being
@@ -44483 +44483 @@
-Subtag: Maka
+Subtag: Make
@@ -46632 +46632 @@
-  (Formulário Ortográfico de 1943 - Oficial no Brasil)
+  (Formulário Ortográfico de 1943 - Official no Brasil)
@@ -47310 +47310 @@
-Prefix: yur
+Prefix: your
--- ./dev/tools/localization/language_subtag_registry.dart	original
+++ ./dev/tools/localization/language_subtag_registry.dart	fixed
@@ -59 +59 @@
-Suppress-Script: Beng
+Suppress-Script: Being
@@ -117 +117 @@
-Suppress-Script: Beng
+Suppress-Script: Being
@@ -726 +726 @@
-Subtag: nd
+Subtag: and
@@ -1448 +1448 @@
-Subtag: aci
+Subtag: acpi
@@ -1585 +1585 @@
-Subtag: adn
+Subtag: and
@@ -1748 +1748 @@
-Subtag: afe
+Subtag: safe
@@ -2063 +2063 @@
-Description: Ake
+Description: Ache
@@ -2192 +2192 @@
-Subtag: ake
+Subtag: ache
@@ -2257 +2257 @@
-Subtag: aks
+Subtag: ask
@@ -2318 +2318 @@
-Description: Alege
+Description: Allege
@@ -2364 +2364 @@
-Subtag: alo
+Subtag: also
@@ -2384 +2384 @@
-Subtag: als
+Subtag: also
@@ -2567 +2567 @@
-Subtag: ane
+Subtag: and
@@ -6522 +6522 @@
-Subtag: bve
+Subtag: be
@@ -7315 +7315 @@
-Description: Ede Cabe
+Description: Edge Cabe
@@ -8084 +8084 @@
-Subtag: cna
+Subtag: can
@@ -8890 +8890 @@
-Subtag: daa
+Subtag: data
@@ -9087 +9087 @@
-Description: Ben Tey Dogon
+Description: Ben They Dogon
@@ -9102 +9102 @@
-Description: Bankan Tey Dogon
+Description: Bankan They Dogon
@@ -9181 +9181 @@
-Subtag: ded
+Subtag: dead
@@ -9807 +9807 @@
-Subtag: dne
+Subtag: done
@@ -10263 +10263 @@
-Subtag: dum
+Subtag: dumb
@@ -10780 +10780 @@
-Description: Ende
+Description: End
@@ -10974 +10974 @@
-Subtag: esy
+Subtag: easy
@@ -11541,2 +11541,2 @@
-Subtag: fwe
-Description: Fwe
+Subtag: few
+Description: Few
@@ -12264 +12264 @@
-Subtag: gir
+Subtag: git
@@ -12977 +12977 @@
-Subtag: gud
+Subtag: good
@@ -13319 +13319 @@
-Subtag: haa
+Subtag: has
@@ -14269 +14269 @@
-Subtag: hve
+Subtag: have
@@ -14411 +14411 @@
-Description: Ede Ica
+Description: Edge Ica
@@ -14449 +14449 @@
-Description: Ede Idaca
+Description: Edge Idaca
@@ -14611 +14611 @@
-Description: Ede Ije
+Description: Edge Ije
@@ -15861 +15861 @@
-Subtag: jus
+Subtag: just
@@ -16439 +16439 @@
-Description: Tese
+Description: These
@@ -16503,2 +16503,2 @@
-Subtag: ket
-Description: Ket
+Subtag: kept
+Description: Kept
@@ -17638 +17638 @@
-Subtag: kno
+Subtag: know
@@ -20054 +20054 @@
-Subtag: lke
+Subtag: like
@@ -20744 +20744 @@
-Description: Thur
+Description: Their
@@ -22014 +22014 @@
-Description: Mor (Mor Islands)
+Description: More (More Islands)
@@ -22111 +22111 @@
-Subtag: mis
+Subtag: miss
@@ -22288 +22288 @@
-Subtag: mke
+Subtag: make
@@ -22432 +22432 @@
-Description: Mape
+Description: Map
@@ -22849 +22849 @@
-Description: Mor (Bomberai Peninsula)
+Description: More (Bomberai Peninsula)
@@ -22853 +22853 @@
-Subtag: mor
+Subtag: more
@@ -23183 +23183 @@
-Description: Mising
+Description: Missing
@@ -24159 +24159 @@
-Subtag: myu
+Subtag: my
@@ -24819 +24819 @@
-Subtag: ned
+Subtag: need
@@ -25090 +25090 @@
-Description: Beng
+Description: Being
@@ -25961 +25961 @@
-Subtag: noo
+Subtag: no
@@ -26080 +26080 @@
-Description: Kura Ede Nago
+Description: Kura Edge Nago
@@ -26361 +26361 @@
-Subtag: nto
+Subtag: not
@@ -26573 +26573 @@
-Subtag: nwe
+Subtag: new
@@ -26593 +26593 @@
-Subtag: nwo
+Subtag: now
@@ -26958,2 +26958,2 @@
-Subtag: ofo
-Description: Ofo
+Subtag: of
+Description: Of
@@ -27189 +27189 @@
-Subtag: olt
+Subtag: old
@@ -27347 +27347 @@
-Subtag: ons
+Subtag: owns
@@ -27623 +27623 @@
-Subtag: otu
+Subtag: out
@@ -30831 +30831 @@
-Subtag: sav
+Subtag: save
@@ -31230 +31230 @@
-Subtag: seh
+Subtag: she
@@ -31281 +31281 @@
-Subtag: ser
+Subtag: set
@@ -32050 +32050 @@
-Description: Som
+Description: Some
@@ -33204 +33204 @@
-Subtag: sxl
+Subtag: xsl
@@ -33523 +33523 @@
-Subtag: tbe
+Subtag: the
@@ -33907 +33907 @@
-Subtag: teh
+Subtag: the
@@ -33923 +33923 @@
-Description: Timne
+Description: Time
@@ -33983 +33983 @@
-Subtag: tey
+Subtag: they
@@ -34184 +34184 @@
-Subtag: thn
+Subtag: then
@@ -34194 +34194 @@
-Subtag: thq
+Subtag: the
@@ -34916 +34916 @@
-Description: Ten'edn
+Description: Ten'end
@@ -35220 +35220 @@
-Subtag: tre
+Subtag: tree
@@ -36472 +36472 @@
-Subtag: unx
+Subtag: unix
@@ -36808 +36808 @@
-Subtag: vas
+Subtag: was
@@ -37529 +37529 @@
-Subtag: wew
+Subtag: we
@@ -37629 +37629 @@
-Subtag: wih
+Subtag: with
@@ -37690 +37690 @@
-Comments: see nwo, wgu
+Comments: see now, wgu
@@ -37779 +37779 @@
-Subtag: wll
+Subtag: will
@@ -38052 +38052 @@
-Description: Maco
+Description: Macro
@@ -38205 +38205 @@
-Subtag: wth
+Subtag: with
@@ -38332 +38332 @@
-Subtag: wya
+Subtag: way
@@ -40809 +40809 @@
-Description: Alo Phola
+Description: Also Phola
@@ -41038 +41038 @@
-Subtag: yur
+Subtag: your
@@ -42528 +42528 @@
-Subtag: bve
+Subtag: be
@@ -42531 +42531 @@
-Preferred-Value: bve
+Preferred-Value: be
@@ -43027 +43027 @@
-Subtag: jus
+Subtag: just
@@ -43030 +43030 @@
-Preferred-Value: jus
+Preferred-Value: just
@@ -44029 +44029 @@
-Subtag: Beng
+Subtag: Being
@@ -44483 +44483 @@
-Subtag: Maka
+Subtag: Make
@@ -46632 +46632 @@
-  (Formulário Ortográfico de 1943 - Oficial no Brasil)
+  (Formulário Ortográfico de 1943 - Official no Brasil)
@@ -47310 +47310 @@
-Prefix: yur
+Prefix: your
