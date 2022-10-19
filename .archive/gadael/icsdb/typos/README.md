## Detected Typos Diff
```diff
--- ./i18n/fr/nonworkingdays.json	original
+++ ./i18n/fr/nonworkingdays.json	fixed
@@ -32 +32 @@
-    "Assumption": "Assomption",
+    "Assumption": "Assumption",
@@ -55 +55 @@
-    "Saint-Pierre-Chanel": "Saint-Pierre-Chanel",
+    "Saint-Pierre-Channel": "Saint-Pierre-Channel",
@@ -65 +65 @@
-    "Saint-Pierre-Chanel": "Saint-Pierre-Chanel",
+    "Saint-Pierre-Channel": "Saint-Pierre-Channel",
@@ -98 +98 @@
-    "Patriots' Day": "Journée nationale des patriotes",
+    "Patriots' Day": "Journée nationale des patriots",
--- ./src/specialevents.js	original
+++ ./src/specialevents.js	fixed
@@ -282 +282 @@
-    let serie = [];
+    let series = [];
@@ -285 +285 @@
-        serie.push(new Date(y, 10, 1+ getThanksGiving(y)));
+        series.push(new Date(y, 10, 1+ getThanksGiving(y)));
@@ -288 +288 @@
-    afterThanksgiving.setProperty('RDATE', serie, { VALUE: 'DATE' });
+    afterThanksgiving.setProperty('RDATE', series, { VALUE: 'DATE' });
--- ./README.md	original
+++ ./README.md	fixed
@@ -26 +26 @@
-Warning, this set of ICS files is suject to move to his own domain in the near future. The github url will probably remain but offical permalinks will be modified
+Warning, this set of ICS files is suject to move to his own domain in the near future. The github url will probably remain but official permalinks will be modified
@@ -39 +39 @@
-More generally, all recuring dates start from 1970 or more to prevent some bugs while decoding the events with various icalendar libraries.
+More generally, all recurring dates start from 1970 or more to prevent some bugs while decoding the events with various icalendar libraries.
--- ./data/france-wallis-futuna-nonworkingdays.ics	original
+++ ./data/france-wallis-futuna-nonworkingdays.ics	fixed
@@ -54 +54 @@
-SUMMARY:Saint-Pierre-Chanel
+SUMMARY:Saint-Pierre-Channel
--- ./build/en-US/france-wallis-futuna-nonworkingdays.ics	original
+++ ./build/en-US/france-wallis-futuna-nonworkingdays.ics	fixed
@@ -65 +65 @@
-SUMMARY:Saint-Pierre-Chanel
+SUMMARY:Saint-Pierre-Channel
--- ./build/fr-FR/germany-saarland-nonworkingdays.ics	original
+++ ./build/fr-FR/germany-saarland-nonworkingdays.ics	fixed
@@ -205 +205 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-appenzell innerrhoden-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-appenzell innerrhoden-nonworkingdays.ics	fixed
@@ -284 +284 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-wallis-futuna-nonworkingdays.ics	original
+++ ./build/fr-FR/france-wallis-futuna-nonworkingdays.ics	fixed
@@ -65 +65 @@
-SUMMARY:Saint-Pierre-Chanel
+SUMMARY:Saint-Pierre-Channel
@@ -202 +202 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-martinique-nonworkingdays.ics	original
+++ ./build/fr-FR/france-martinique-nonworkingdays.ics	fixed
@@ -233 +233 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-schwyz-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-schwyz-nonworkingdays.ics	fixed
@@ -316 +316 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-polynesia-nonworkingdays.ics	original
+++ ./build/fr-FR/france-polynesia-nonworkingdays.ics	fixed
@@ -218 +218 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-guyane-nonworkingdays.ics	original
+++ ./build/fr-FR/france-guyane-nonworkingdays.ics	fixed
@@ -187 +187 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-moselle-rhin-nonworkingdays.ics	original
+++ ./build/fr-FR/france-moselle-rhin-nonworkingdays.ics	fixed
@@ -203 +203 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/us-all-nonworkingdays.ics	original
+++ ./build/fr-FR/us-all-nonworkingdays.ics	fixed
@@ -275 +275 @@
-SUMMARY:Journée nationale des patriotes
+SUMMARY:Journée nationale des patriots
--- ./build/fr-FR/switzerland-solothurn-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-solothurn-nonworkingdays.ics	fixed
@@ -317 +317 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-obwalden-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-obwalden-nonworkingdays.ics	fixed
@@ -301 +301 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-jura-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-jura-nonworkingdays.ics	fixed
@@ -317 +317 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-zug-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-zug-nonworkingdays.ics	fixed
@@ -301 +301 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/germany-all-nonworkingdays.ics	original
+++ ./build/fr-FR/germany-all-nonworkingdays.ics	fixed
@@ -239 +239 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-all-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-all-nonworkingdays.ics	fixed
@@ -399 +399 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-reunion-nonworkingdays.ics	original
+++ ./build/fr-FR/france-reunion-nonworkingdays.ics	fixed
@@ -172 +172 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-newcaledonia-nonworkingdays.ics	original
+++ ./build/fr-FR/france-newcaledonia-nonworkingdays.ics	fixed
@@ -172 +172 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/us-maine-nonworkingdays.ics	original
+++ ./build/fr-FR/us-maine-nonworkingdays.ics	fixed
@@ -64 +64 @@
-SUMMARY:Journée nationale des patriotes
+SUMMARY:Journée nationale des patriots
--- ./build/fr-FR/us-wisconsin-nonworkingdays.ics	original
+++ ./build/fr-FR/us-wisconsin-nonworkingdays.ics	fixed
@@ -64 +64 @@
-SUMMARY:Journée nationale des patriotes
+SUMMARY:Journée nationale des patriots
--- ./build/fr-FR/switzerland-aargau-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-aargau-nonworkingdays.ics	fixed
@@ -301 +301 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-valais-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-valais-nonworkingdays.ics	fixed
@@ -268 +268 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-guadeloupe-nonworkingdays.ics	original
+++ ./build/fr-FR/france-guadeloupe-nonworkingdays.ics	fixed
@@ -233 +233 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-nidwalden-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-nidwalden-nonworkingdays.ics	fixed
@@ -300 +300 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/us-massachusetts-nonworkingdays.ics	original
+++ ./build/fr-FR/us-massachusetts-nonworkingdays.ics	fixed
@@ -80 +80 @@
-SUMMARY:Journée nationale des patriotes
+SUMMARY:Journée nationale des patriots
--- ./build/fr-FR/switzerland-ticino-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-ticino-nonworkingdays.ics	fixed
@@ -332 +332 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/belgium-nonworkingdays.ics	original
+++ ./build/fr-FR/belgium-nonworkingdays.ics	fixed
@@ -157 +157 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-uri-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-uri-nonworkingdays.ics	fixed
@@ -316 +316 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/france-nonworkingdays.ics	original
+++ ./build/fr-FR/france-nonworkingdays.ics	fixed
@@ -172 +172 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
--- ./build/fr-FR/switzerland-fribourg-nonworkingdays.ics	original
+++ ./build/fr-FR/switzerland-fribourg-nonworkingdays.ics	fixed
@@ -301 +301 @@
-SUMMARY:Assomption
+SUMMARY:Assumption
