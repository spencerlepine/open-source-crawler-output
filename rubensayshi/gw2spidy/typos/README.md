## Detected Typos Diff
```diff
--- ./vendor/twig/twig/CHANGELOG	original
+++ ./vendor/twig/twig/CHANGELOG	fixed
@@ -315 +315 @@
- * removed the newline after a comment (mimicks PHP behavior)
+ * removed the newline after a comment (mimics PHP behavior)
--- ./vendor/twig/twig/lib/Twig/TokenParser/AutoEscape.php	original
+++ ./vendor/twig/twig/lib/Twig/TokenParser/AutoEscape.php	fixed
@@ -21 +21 @@
- *   Everything will be outputed as is in this block
+ *   Everything will be outputted as is in this block
--- ./vendor/twig/twig/lib/Twig/TokenParser/Set.php	original
+++ ./vendor/twig/twig/lib/Twig/TokenParser/Set.php	fixed
@@ -52 +52 @@
-                throw new Twig_Error_Syntax("When using set, you must have the same number of variables and assignements.", $lineno);
+                throw new Twig_Error_Syntax("When using set, you must have the same number of variables and assignments.", $lineno);
--- ./vendor/simple_html_dom/simple_html_dom.php	original
+++ ./vendor/simple_html_dom/simple_html_dom.php	fixed
@@ -24 +24 @@
- *  NOTE:  If the user's system has a routine called get_last_retrieve_url_contents_content_type availalbe, we will assume it's returning the content-type header from the
+ *  NOTE:  If the user's system has a routine called get_last_retrieve_url_contents_content_type available, we will assume it's returning the content-type header from the
@@ -74 +74 @@
-    // For sourceforge users: uncomment the next line and comment the retreive_url_contents line 2 lines down if it is not already done.
+    // For sourceforge users: uncomment the next line and comment the retrieve_url_contents line 2 lines down if it is not already done.
@@ -512,2 +512,2 @@
-            // used to be: if (($levle=count($selectors[0]))===0) return array();
-            if (($levle=count($selectors[$c]))===0) return array();
+            // used to be: if (($level=count($selectors[0]))===0) return array();
+            if (($level=count($selectors[$c]))===0) return array();
@@ -519 +519 @@
-            for ($l=0; $l<$levle; ++$l)
+            for ($l=0; $l<$level; ++$l)
@@ -677 +677 @@
-        // Paperg: Add the colon to the attrbute, so that it properly finds <tag attr:ibute="something" > like google does.
+        // Paperg: Add the colon to the attribute, so that it properly finds <tag attr:ibute="something" > like google does.
--- ./vendor/simple_html_dom/manual/manual_api.htm	original
+++ ./vendor/simple_html_dom/manual/manual_api.htm	fixed
@@ -102 +102 @@
-        <td class="description">Read or write element's attribure value. </td>
+        <td class="description">Read or write element's attribute value. </td>
@@ -181,3 +181,3 @@
-  <h2>Camel naming convertions</h2>
-  <a class="top" href="#top">Top</a>
-  <div class="code">You can also call methods with W3C STANDARD camel naming convertions.<br>
+  <h2>Camel naming conversions</h2>
+  <a class="top" href="#top">Top</a>
+  <div class="code">You can also call methods with W3C STANDARD camel naming conversions.<br>
--- ./vendor/simple_html_dom/manual/manual.htm	original
+++ ./vendor/simple_html_dom/manual/manual.htm	fixed
@@ -152 +152 @@
-        <span class="comment">// Find <strong>lastest</strong> <strong>anchor</strong>, returns element object or <strong>null</strong> if not found</span> <span class="comment">(zero based)</span><br>
+        <span class="comment">// Find <strong>latest</strong> <strong>anchor</strong>, returns element object or <strong>null</strong> if not found</span> <span class="comment">(zero based)</span><br>
@@ -351 +351 @@
-      <div class="code">You can also call methods with <a href="manual_api.htm#camel"><span class="var">Camel naming convertions</span></a>.<br>
+      <div class="code">You can also call methods with <a href="manual_api.htm#camel"><span class="var">Camel naming conversions</span></a>.<br>
--- ./vendor/simple_html_dom/app/js/jquery.treeview.css	original
+++ ./vendor/simple_html_dom/app/js/jquery.treeview.css	fixed
@@ -40 +40 @@
-.treeview li.collapsable, .treeview li.expandable { background-position: 0 -176px; }
+.treeview li.collapsible, .treeview li.expandable { background-position: 0 -176px; }
@@ -45,2 +45,2 @@
-.treeview li.lastCollapsable, .treeview li.lastExpandable { background-image: url(images/treeview-default.gif); }  
-.treeview li.lastCollapsable { background-position: 0 -111px }
+.treeview li.lastCollapsible, .treeview li.lastExpandable { background-image: url(images/treeview-default.gif); }  
+.treeview li.lastCollapsible { background-position: 0 -111px }
@@ -49 +49 @@
-.treeview div.lastCollapsable-hitarea, .treeview div.lastExpandable-hitarea { background-position: 0; }
+.treeview div.lastCollapsible-hitarea, .treeview div.lastExpandable-hitarea { background-position: 0; }
@@ -52 +52 @@
-.treeview-red .hitarea, .treeview-red li.lastCollapsable, .treeview-red li.lastExpandable { background-image: url(images/treeview-red.gif); } 
+.treeview-red .hitarea, .treeview-red li.lastCollapsible, .treeview-red li.lastExpandable { background-image: url(images/treeview-red.gif); } 
@@ -55 +55 @@
-.treeview-black .hitarea, .treeview-black li.lastCollapsable, .treeview-black li.lastExpandable { background-image: url(images/treeview-black.gif); }  
+.treeview-black .hitarea, .treeview-black li.lastCollapsible, .treeview-black li.lastExpandable { background-image: url(images/treeview-black.gif); }  
@@ -58 +58 @@
-.treeview-gray .hitarea, .treeview-gray li.lastCollapsable, .treeview-gray li.lastExpandable { background-image: url(images/treeview-gray.gif); } 
+.treeview-gray .hitarea, .treeview-gray li.lastCollapsible, .treeview-gray li.lastExpandable { background-image: url(images/treeview-gray.gif); } 
@@ -61 +61 @@
-.treeview-famfamfam .hitarea, .treeview-famfamfam li.lastCollapsable, .treeview-famfamfam li.lastExpandable { background-image: url(images/treeview-famfamfam.gif); } 
+.treeview-famfamfam .hitarea, .treeview-famfamfam li.lastCollapsible, .treeview-famfamfam li.lastExpandable { background-image: url(images/treeview-famfamfam.gif); } 
--- ./vendor/simple_html_dom/app/js/jquery.treeview.js	original
+++ ./vendor/simple_html_dom/app/js/jquery.treeview.js	fixed
@@ -78,2 +78,2 @@
-						.addClass(CLASSES.collapsable)
-						.replaceClass(CLASSES.last, CLASSES.lastCollapsable);
+						.addClass(CLASSES.collapsible)
+						.replaceClass(CLASSES.last, CLASSES.lastCollapsible);
@@ -126 +126 @@
-				$("a:eq(0)", control).click( handler(CLASSES.collapsable) );
+				$("a:eq(0)", control).click( handler(CLASSES.collapsible) );
@@ -139,20 +139,20 @@
-						.swapClass( CLASSES.collapsableHitarea, CLASSES.expandableHitarea )
-						.swapClass( CLASSES.lastCollapsableHitarea, CLASSES.lastExpandableHitarea )
-					.end()
-					// swap classes for parent li
-					.swapClass( CLASSES.collapsable, CLASSES.expandable )
-					.swapClass( CLASSES.lastCollapsable, CLASSES.lastExpandable )
-					// find child lists
-					.find( ">ul" )
-					// toggle them
-					.heightToggle( settings.animated, settings.toggle );
-				if ( settings.unique ) {
-					$(this).parent()
-						.siblings()
-						// swap classes for hitarea
-						.find(">.hitarea")
-							.replaceClass( CLASSES.collapsableHitarea, CLASSES.expandableHitarea )
-							.replaceClass( CLASSES.lastCollapsableHitarea, CLASSES.lastExpandableHitarea )
-						.end()
-						.replaceClass( CLASSES.collapsable, CLASSES.expandable )
-						.replaceClass( CLASSES.lastCollapsable, CLASSES.lastExpandable )
+						.swapClass( CLASSES.collapsibleHitarea, CLASSES.expandableHitarea )
+						.swapClass( CLASSES.lastCollapsibleHitarea, CLASSES.lastExpandableHitarea )
+					.end()
+					// swap classes for parent li
+					.swapClass( CLASSES.collapsible, CLASSES.expandable )
+					.swapClass( CLASSES.lastCollapsible, CLASSES.lastExpandable )
+					// find child lists
+					.find( ">ul" )
+					// toggle them
+					.heightToggle( settings.animated, settings.toggle );
+				if ( settings.unique ) {
+					$(this).parent()
+						.siblings()
+						// swap classes for hitarea
+						.find(">.hitarea")
+							.replaceClass( CLASSES.collapsibleHitarea, CLASSES.expandableHitarea )
+							.replaceClass( CLASSES.lastCollapsibleHitarea, CLASSES.lastExpandableHitarea )
+						.end()
+						.replaceClass( CLASSES.collapsible, CLASSES.expandable )
+						.replaceClass( CLASSES.lastCollapsible, CLASSES.lastExpandable )
@@ -221,31 +221,31 @@
-					.removeClass(CLASSES.lastCollapsable)
-					.removeClass(CLASSES.lastExpandable)
-				.find(">.hitarea")
-					.removeClass(CLASSES.lastCollapsableHitarea)
-					.removeClass(CLASSES.lastExpandableHitarea);
-				$(branches).find("li").andSelf().prepareBranches(settings).applyClasses(settings, toggler);
-			});
-		}
-	});
-	
-	// classes used by the plugin
-	// need to be styled via external stylesheet, see first example
-	var CLASSES = $.fn.treeview.classes = {
-		open: "open",
-		closed: "closed",
-		expandable: "expandable",
-		expandableHitarea: "expandable-hitarea",
-		lastExpandableHitarea: "lastExpandable-hitarea",
-		collapsable: "collapsable",
-		collapsableHitarea: "collapsable-hitarea",
-		lastCollapsableHitarea: "lastCollapsable-hitarea",
-		lastCollapsable: "lastCollapsable",
-		lastExpandable: "lastExpandable",
-		last: "last",
-		hitarea: "hitarea"
-	};
-	
-	// provide backwards compability
-	$.fn.Treeview = $.fn.treeview;
-	
-})(jQuery);+					.removeClass(CLASSES.lastCollapsible)
+					.removeClass(CLASSES.lastExpandable)
+				.find(">.hitarea")
+					.removeClass(CLASSES.lastCollapsibleHitarea)
+					.removeClass(CLASSES.lastExpandableHitarea);
+				$(branches).find("li").andSelf().prepareBranches(settings).applyClasses(settings, toggler);
+			});
+		}
+	});
+	
+	// classes used by the plugin
+	// need to be styled via external stylesheet, see first example
+	var CLASSES = $.fn.treeview.classes = {
+		open: "open",
+		closed: "closed",
+		expandable: "expandable",
+		expandableHitarea: "expandable-hitarea",
+		lastExpandableHitarea: "lastExpandable-hitarea",
+		collapsible: "collapsible",
+		collapsibleHitarea: "collapsible-hitarea",
+		lastCollapsibleHitarea: "lastCollapsible-hitarea",
+		lastCollapsible: "lastCollapsible",
+		lastExpandable: "lastExpandable",
+		last: "last",
+		hitarea: "hitarea"
+	};
+	
+	// provide backwards compatibility
+	$.fn.Treeview = $.fn.treeview;
+	
+})(jQuery);--- ./vendor/simple_html_dom/app/google.htm	original
+++ ./vendor/simple_html_dom/app/google.htm	fixed
@@ -324 +324 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Replayed if draw.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Replayed if draw.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -326 +326 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>EDENBOROUGH</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">74<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">EDENBOROUGH</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>EDENBOROUGH</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">74<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">EDENBOROUGH</a>
@@ -369 +369 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>17</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>AMBROSINI</td></tr><tr><td>56</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>PATO</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>55</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ZACCARDO</td></tr><tr><td>81</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SAGLIK</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">81<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">SAGLIK</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>17</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>AMBROSINI</td></tr><tr><td>56</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>PATO</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>55</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ZACCARDO</td></tr><tr><td>81</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SAGLIK</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">81<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">SAGLIK</a>
@@ -389 +389 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>4</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>VERTONGHEN</td></tr><tr><td>90</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball-pen.gif\' alt=\'penalty\'></td><td nowrap=nowrap>SUAREZ</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>13</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>CERNY</td></tr><tr><td>41</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>JAROLIM</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">90<img align="top" width="17" height="16" border="0" src="images/ball-pen.gif" alt="penalty">SUAREZ</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>4</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>VERTONGHEN</td></tr><tr><td>90</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball-pen.gif\' alt=\'penalty\'></td><td nowrap=nowrap>SUAREZ</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>13</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>CERNY</td></tr><tr><td>41</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>JAROLIM</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">90<img align="top" width="17" height="16" border="0" src="images/ball-pen.gif" alt="penalty">SUAREZ</a>
@@ -409 +409 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>58</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SANTIN</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">58<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">SANTIN</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>58</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SANTIN</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">58<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">SANTIN</a>
@@ -429 +429 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BODIPO</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">74<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">BODIPO</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BODIPO</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">74<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">BODIPO</a>
@@ -449 +449 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>26</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>DJURDJEVIC</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">26<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">DJURDJEVIC</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>26</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>DJURDJEVIC</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">26<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">DJURDJEVIC</a>
@@ -469 +469 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>18</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>PETRIC</td></tr><tr><td>30</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>OLIC</td></tr><tr><td>57</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>OLIC</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>82</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>DELFOUNESO</td></tr><tr><td>84</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/redcard.gif\' alt=\'red card\'></td><td nowrap=nowrap>SIDWELL</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">84<img align="top" width="17" height="16" border="0" src="images/redcard.gif" alt="red card">SIDWELL</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>18</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>PETRIC</td></tr><tr><td>30</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>OLIC</td></tr><tr><td>57</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>OLIC</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>82</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>DELFOUNESO</td></tr><tr><td>84</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/redcard.gif\' alt=\'red card\'></td><td nowrap=nowrap>SIDWELL</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">84<img align="top" width="17" height="16" border="0" src="images/redcard.gif" alt="red card">SIDWELL</a>
@@ -489 +489 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>40</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>CROUCH</td></tr><tr><td>42</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>CROUCH</td></tr><tr><td>90</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>HREIDARSSON</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">90<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">HREIDARSSON</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>40</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>CROUCH</td></tr><tr><td>42</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>CROUCH</td></tr><tr><td>90</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>HREIDARSSON</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">90<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">HREIDARSSON</a>
@@ -509 +509 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>29</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ILAN</td></tr><tr><td>44</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ILAN</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>33</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>MORIENTES</td></tr><tr><td>72</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ZIGIC</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">72<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">ZIGIC</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>29</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ILAN</td></tr><tr><td>44</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ILAN</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>33</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>MORIENTES</td></tr><tr><td>72</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>ZIGIC</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">72<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">ZIGIC</a>
@@ -550 +550 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -552 +552 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>47</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BASHEER</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SALEH</td></tr><tr><td>84</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SALEH</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>53</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BO</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">84<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">SALEH</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>47</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BASHEER</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SALEH</td></tr><tr><td>84</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>SALEH</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>53</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BO</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">84<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">SALEH</a>
@@ -570 +570 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -572 +572 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>55</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>MARTINEZ</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>90</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/redcard.gif\' alt=\'red card\'></td><td nowrap=nowrap>NEJAD</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">90<img align="top" width="17" height="16" border="0" src="images/redcard.gif" alt="red card">NEJAD</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>55</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>MARTINEZ</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>90</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/redcard.gif\' alt=\'red card\'></td><td nowrap=nowrap>NEJAD</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">90<img align="top" width="17" height="16" border="0" src="images/redcard.gif" alt="red card">NEJAD</a>
@@ -613 +613 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -615 +615 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>19</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BIANCHI</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">19<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">BIANCHI</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>19</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BIANCHI</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">19<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">BIANCHI</a>
@@ -633 +633 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -635 +635 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>82</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>VUCINIC</td></tr><tr><td>86</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>VUCINIC</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">86<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">VUCINIC</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>82</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>VUCINIC</td></tr><tr><td>86</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>VUCINIC</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">86<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">VUCINIC</a>
@@ -652 +652 @@
-            <span id="ctl00_ContentPlaceHolder1_Repeater1_ctl05_CompGames1_lblCompName">&nbsp;ITALY - SERIE C1A</span></td>
+            <span id="ctl00_ContentPlaceHolder1_Repeater1_ctl05_CompGames1_lblCompName">&nbsp;ITALY - SERIES C1A</span></td>
@@ -695 +695 @@
-            <span id="ctl00_ContentPlaceHolder1_Repeater1_ctl06_CompGames1_lblCompName">&nbsp;ITALY - SERIE C2A</span></td>
+            <span id="ctl00_ContentPlaceHolder1_Repeater1_ctl06_CompGames1_lblCompName">&nbsp;ITALY - SERIES C2A</span></td>
@@ -721 +721 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>55</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>48</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr><tr><td>66</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">74<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">&nbsp;</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>55</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>48</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr><tr><td>66</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr><tr><td>74</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>&nbsp;</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">74<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">&nbsp;</a>
@@ -762 +762 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Replayed if draw.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Replayed if draw.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -764 +764 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>86</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>HAGAN</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>60</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>WILLIAMS</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">86<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">HAGAN</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>86</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>HAGAN</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>60</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>WILLIAMS</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">86<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">HAGAN</a>
@@ -805 +805 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Playing at Tokyo, Japan. Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return nd();"><img src="images/info.gif" border="0" /></a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table border=0 cellpadding=2 cellspacing=0 width=250><tr align=left bgcolor=#ffffff><td><img src=\'images/info.gif\' /><b>Match information</b></td></tr><tr><td>Playing at Tokyo, Japan. Knock out.</td></tr></table>',HAUTO,VAUTO,WIDTH,250);" onmouseout="return and();"><img src="images/info.gif" border="0" /></a>
@@ -807 +807 @@
-                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>4</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BIELER</td></tr><tr><td>26</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BOLANOS</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return nd();">26<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">BOLANOS</a>
+                <a class="poplink" href="javascript:void(0);" onmouseover="return overlib('<table><tr valign=top><td width=200><table border=1 cellspacing=0 cellpadding=2><tr valign=top><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr></table></td><td width=200><table border=1 cellspacing=0 cellpadding=2><tr><td width=20>Min</td><td width=20>&nbsp;</td><td width=120>Player</td></tr><tr><td>4</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BIELER</td></tr><tr><td>26</td><td><img align=\'top\' width=\'17\' height=\'16\' border=\'0\' src=\'images/ball.gif\' alt=\'goal\'></td><td nowrap=nowrap>BOLANOS</td></tr></table></td></tr></table>',HAUTO,VAUTO,WIDTH,400);" onmouseout="return and();">26<img align="top" width="17" height="16" border="0" src="images/ball.gif" alt="goal">BOLANOS</a>
--- ./vendor/simple_html_dom/app/js/jquery.js	original
+++ ./vendor/simple_html_dom/app/js/jquery.js	fixed
@@ -300 +300 @@
-				// clone will also remove the events from the orignal
+				// clone will also remove the events from the original
@@ -403 +403 @@
-							// Get the specifc value for the option
+							// Get the specific value for the option
@@ -614 +614 @@
-	// Evalulates a script in a global context
+	// Evaluates a script in a global context
@@ -1026 +1026 @@
-		// Safari mis-reports the default selected property of a hidden option
+		// Safari miss-reports the default selected property of a hidden option
@@ -1425 +1425 @@
-		// Match: :even, :last-chlid, #id, .class
+		// Match: :even, :last-child, #id, .class
@@ -1848 +1848 @@
-			// Handle multiple events seperated by a space
+			// Handle multiple events separated by a space
@@ -1906 +1906 @@
-				// Handle multiple events seperated by a space
+				// Handle multiple events separated by a space
@@ -2463 +2463 @@
-		// shift arguments if data argument was ommited
+		// shift arguments if data argument was omitted
--- ./vendor/simple_html_dom/testcase/slickspeed.htm	original
+++ ./vendor/simple_html_dom/testcase/slickspeed.htm	fixed
@@ -2828 +2828 @@
-McManus, Justin Baker, Joel Sklar, and Molly Ives Brower who perfermed
+McManus, Justin Baker, Joel Sklar, and Molly Ives Browser who perfermed
@@ -2844 +2844 @@
-  <dd><a name=refsCWWW></a> Martin J. D&uuml;rst, Fran&ccedil;ois Yergeau, Misha Wolf, Asmus Freytag, Tex Texin, editors; "<cite>Character Model for the World Wide Web</cite>", W3C Recommendation, 15 February 2005
+  <dd><a name=refsCWWW></a> Martin J. D&uuml;rst, Fran&ccedil;is Yergeau, Misha Wolf, Asmus Freytag, Tex Texin, editors; "<cite>Character Model for the World Wide Web</cite>", W3C Recommendation, 15 February 2005
@@ -2876 +2876 @@
-  <dd><a name="refsXML10"></a> Tim Bray, Jean Paoli, C. M. Sperberg-McQueen, Eve Maler, Fran&ccedil;ois Yergeau, editors; "<cite>Extensible Markup Language (XML) 1.0 (Third Edition)</cite>", W3C Recommendation, 4 February 2004
+  <dd><a name="refsXML10"></a> Tim Bray, Jean Paoli, C. M. Sperberg-McQueen, Eve Maler, Fran&ccedil;is Yergeau, editors; "<cite>Extensible Markup Language (XML) 1.0 (Third Edition)</cite>", W3C Recommendation, 4 February 2004
--- ./vendor/simple_html_dom/change_log.txt	original
+++ ./vendor/simple_html_dom/change_log.txt	fixed
@@ -106 +106 @@
-1. Stop infinity loop while tthe source content is BAD HTML.
+1. Stop infinity loop while the source content is BAD HTML.
--- ./vendor/nrk-predis/FAQ.md	original
+++ ./vendor/nrk-predis/FAQ.md	fixed
@@ -8 +8 @@
-extended by developers while still being reasonabily fast. With Predis you can swap almost any class
+extended by developers while still being reasonably fast. With Predis you can swap almost any class
--- ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersionNextTest.php	original
+++ ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersionNextTest.php	fixed
@@ -78 +78 @@
-            37 => 'smove',
+            37 => 'move',
--- ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion22Test.php	original
+++ ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion22Test.php	fixed
@@ -78 +78 @@
-            37 => 'smove',
+            37 => 'move',
--- ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion24Test.php	original
+++ ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion24Test.php	fixed
@@ -78 +78 @@
-            37 => 'smove',
+            37 => 'move',
--- ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion26Test.php	original
+++ ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion26Test.php	fixed
@@ -78 +78 @@
-            37 => 'smove',
+            37 => 'move',
--- ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion12Test.php	original
+++ ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion12Test.php	fixed
@@ -78 +78 @@
-            37 => 'smove',
+            37 => 'move',
--- ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion20Test.php	original
+++ ./vendor/nrk-predis/tests/Predis/Profiles/ServerVersion20Test.php	fixed
@@ -78 +78 @@
-            37 => 'smove',
+            37 => 'move',
--- ./vendor/nrk-predis/tests/Predis/ConnectionFactoryTest.php	original
+++ ./vendor/nrk-predis/tests/Predis/ConnectionFactoryTest.php	fixed
@@ -40 +40 @@
-            'host' => 'locahost',
+            'host' => 'localhost',
--- ./vendor/nrk-predis/tests/Predis/Commands/ListInsertTest.php	original
+++ ./vendor/nrk-predis/tests/Predis/Commands/ListInsertTest.php	fixed
@@ -77 +77 @@
-    public function testReturnsLengthOfListAfterInser()
+    public function testReturnsLengthOfListAfterInsert()
--- ./vendor/nrk-predis/tests/Predis/Commands/SetMoveTest.php	original
+++ ./vendor/nrk-predis/tests/Predis/Commands/SetMoveTest.php	fixed
@@ -35 +35 @@
-        return 'SMOVE';
+        return 'MOVE';
@@ -86,2 +86,2 @@
-        $this->assertTrue($redis->smove('letters:source', 'letters:destination', 'b'));
-        $this->assertFalse($redis->smove('letters:source', 'letters:destination', 'z'));
+        $this->assertTrue($redis->move('letters:source', 'letters:destination', 'b'));
+        $this->assertFalse($redis->move('letters:source', 'letters:destination', 'z'));
@@ -104 +104 @@
-        $redis->smove('set:destination', 'set:source', 'foo');
+        $redis->move('set:destination', 'set:source', 'foo');
@@ -118 +118 @@
-        $redis->smove('set:destination', 'set:source', 'foo');
+        $redis->move('set:destination', 'set:source', 'foo');
--- ./vendor/nrk-predis/tests/Predis/Commands/StringAppendTest.php	original
+++ ./vendor/nrk-predis/tests/Predis/Commands/StringAppendTest.php	fixed
@@ -88 +88 @@
-    public function testReturnsTheLenghtOfTheStringAfterAppend()
+    public function testReturnsTheLengthOfTheStringAfterAppend()
--- ./vendor/nrk-predis/tests/README.md	original
+++ ./vendor/nrk-predis/tests/README.md	fixed
@@ -6 +6 @@
-please read ahead to undestand how to disable integration tests.
+please read ahead to understand how to disable integration tests.
--- ./vendor/nrk-predis/bin/generate-command-test.php	original
+++ ./vendor/nrk-predis/bin/generate-command-test.php	fixed
@@ -114 +114 @@
-                throw new RuntimeException('Invalid value for realm has been sepcified (empty).');
+                throw new RuntimeException('Invalid value for realm has been specified (empty).');
--- ./vendor/nrk-predis/TODO	original
+++ ./vendor/nrk-predis/TODO	fixed
@@ -1 +1 @@
-* Documentation! The README is obviously not enought to show how to use Predis
+* Documentation! The README is obviously not enough to show how to use Predis
--- ./vendor/nrk-predis/CHANGELOG.md	original
+++ ./vendor/nrk-predis/CHANGELOG.md	fixed
@@ -127 +127 @@
-- The `Predis\IConnection` interface has been splitted into two new interfaces:
+- The `Predis\IConnection` interface has been split into two new interfaces:
@@ -191 +191 @@
-- Added inline (p)subscribtion via options when initializing an instance of
+- Added inline (p)subscription via options when initializing an instance of
@@ -337 +337 @@
-  - `connection_async` [default: `FALSE`]: estabilish connections to servers
+  - `connection_async` [default: `FALSE`]: establish connections to servers
@@ -397 +397 @@
-  override the server profile if you need the old (and uncorrect) behaviour
+  override the server profile if you need the old (and incorrect) behaviour
--- ./vendor/nrk-predis/lib/Predis/Network/MasterSlaveReplication.php	original
+++ ./vendor/nrk-predis/lib/Predis/Network/MasterSlaveReplication.php	fixed
@@ -285 +285 @@
-     * array of the specified commad instance.
+     * array of the specified command instance.
@@ -299 +299 @@
-     * a callable object can be provided to dinamically check if the passed
+     * a callable object can be provided to dynamically check if the passed
@@ -320 +320 @@
-     * its arguments, a callable object can be provided to dinamically check
+     * its arguments, a callable object can be provided to dynamically check
--- ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion20.php	original
+++ ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion20.php	fixed
@@ -81 +81 @@
-            'smove'                     => 'Predis\Commands\SetMove',
+            'move'                     => 'Predis\Commands\SetMove',
--- ./vendor/nrk-predis/lib/Predis/Distribution/HashRing.php	original
+++ ./vendor/nrk-predis/lib/Predis/Distribution/HashRing.php	fixed
@@ -187 +187 @@
-     * Calculates the corrisponding key of a node distributed in the hashring.
+     * Calculates the corresponding key of a node distributed in the hashring.
--- ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion24.php	original
+++ ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion24.php	fixed
@@ -81 +81 @@
-            'smove'                     => 'Predis\Commands\SetMove',
+            'move'                     => 'Predis\Commands\SetMove',
--- ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion26.php	original
+++ ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion26.php	fixed
@@ -81 +81 @@
-            'smove'                     => 'Predis\Commands\SetMove',
+            'move'                     => 'Predis\Commands\SetMove',
--- ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion12.php	original
+++ ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion12.php	fixed
@@ -81 +81 @@
-            'smove'                     => 'Predis\Commands\SetMove',
+            'move'                     => 'Predis\Commands\SetMove',
--- ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion22.php	original
+++ ./vendor/nrk-predis/lib/Predis/Profiles/ServerVersion22.php	fixed
@@ -81 +81 @@
-            'smove'                     => 'Predis\Commands\SetMove',
+            'move'                     => 'Predis\Commands\SetMove',
--- ./vendor/nrk-predis/lib/Predis/Options/CustomOption.php	original
+++ ./vendor/nrk-predis/lib/Predis/Options/CustomOption.php	fixed
@@ -15 +15 @@
- * Implements a generic class used to dinamically define a client option.
+ * Implements a generic class used to dynamically define a client option.
--- ./vendor/nrk-predis/lib/Predis/Client.php	original
+++ ./vendor/nrk-predis/lib/Predis/Client.php	fixed
@@ -210 +210 @@
-     * Dinamically invokes a Redis command with the specified arguments.
+     * Dynamically invokes a Redis command with the specified arguments.
--- ./vendor/nrk-predis/lib/Predis/Commands/SetMove.php	original
+++ ./vendor/nrk-predis/lib/Predis/Commands/SetMove.php	fixed
@@ -25 +25 @@
-        return 'SMOVE';
+        return 'MOVE';
--- ./vendor/nrk-predis/lib/Predis/Transaction/MultiExecContext.php	original
+++ ./vendor/nrk-predis/lib/Predis/Transaction/MultiExecContext.php	fixed
@@ -180 +180 @@
-     * Dinamically invokes a Redis command with the specified arguments.
+     * Dynamically invokes a Redis command with the specified arguments.
--- ./vendor/propel/CHANGELOG	original
+++ ./vendor/propel/CHANGELOG	fixed
@@ -119 +119 @@
-eb303e5 Fix: some isVersionningNecessary() calls can cause fatal errors
+eb303e5 Fix: some isVersioningNecessary() calls can cause fatal errors
@@ -267 +267 @@
-* [01b03f7] [turbo behavior] Use the correct binding code in accelerated findPk(). This is to accomodate cases where PK columns have special bindings (like timestamps... ot blobs, who knows). I took advantage of this to refactor the custom binding code in the adapters.
+* [01b03f7] [turbo behavior] Use the correct binding code in accelerated findPk(). This is to accommodate cases where PK columns have special bindings (like timestamps... ot blobs, who knows). I took advantage of this to refactor the custom binding code in the adapters.
@@ -357,61 +357,61 @@
-* [5d6e4b0] [archivable behavior] Added the ability to use a cutom archive class.
-* [5088e39] [archivable behavior] Added generated ActiveRecord::populateFromArchive() method
-* [182af0c] [archivable behavior] Initial commit
-* [ce59915] [Tests] More tests for MysqlSchemaParser
-* [20d407a] Changed visibility to be less 'open'. Related commit: 381e378cb17b388765dfbb5a3241dacbff449323
-* [dd10eec] [Tests] fixed script to handle reverse fixtures
-* [d64741a] Fixed the test file's syntax
-* [9584188] Fixed unit test
-* [8b20446] used 'SHOW FULL TABLES' instead of the previous one to handle multiple database
-* [acccc26] Excluded read only tables from being counted
-* [1cd82d6] handle views when using diff command
-* [7f89e83] Added unit test for MySQL schema parser
-* [8470dba] Added fixtures for MySQL reverse unit tests
-* [f75334c] Changed prototype to use the interface instead of an implementation class
-* [381e378] Changed visibility of simpleXmlToArray method in PropelConvertConfTask in order to use it in tests
-* [54ce432] Removed stray testing stuff that got left behind
-* [db4e041] FIX: Check that platform exists before using it
-* [be563e8] Fixed false positive in PostgreSQL migrations where generator would generate varchar-fields without explicit size as VARCHAR(255)
-* [7c84b79] Fixed postDelete hook in soft delete behavior
-* [39e3709] [SoftDeleteBehavior] Fixed missing post hook call
-* [8fc39e1] Added test to prove post hook is not fired on soft deleted objects.
-* [c5c30e0] set sequence name configurable
-* [082d27a] Added strict assertions
-* [1ad20fb] added unit-test for Table::appendXml (namespace & package attributes)
-* [3addf99] serialize namespace too
-* [76a3841] store table`s package name in Xml
-* [ff673c0] Added a tiny shell script to reset test fixtures
-* [3d6d4bd] fixed naming and default values in unit test
-* [67a77bf] Fixed bug in PhpNameGenerator. The default name convertor for table and column names is NameGenerator::CONV_METHOD_UNDERSCORE. This method has a slight bug resulting in an incorrect phpName for table using "_0" as a prefix:
-* [04fe003] fix usage of undefined variable
-* [ceb610f] `level` is reserved keywork in oracle
-* [57a0f2c] pass vendor`s type to VentorInfo::__construct in XMLElement::getVendorInfoForType()
-* [a3aaa76] detect autoincrement via sequences
-* [7c84546] [delegate behavior] Documented the fact that, finally, delegate behavior can handle inheritance over several levels
-* [8290ed5] [delegate behavior] Changed class table inheritance examples to show that the behavior is much more powerful than previously thought. Refs #40
-* [1f4ce85] Fixed MySQL type for a BOOLEAN
-* [5e7d765] [delegate behavior] Fixed typo in behavior documentation
-* [4ee22c0] [delegate behavior] Fixed coding standards
-* [4b327c6] [delegate behavior] Fixed wrong file permissions (old samba config)
-* [fe2ce45] [delegate behavior] Throwing exception at buildtime if the delegate table has a one-to-many relationship with the main table
-* [87ed930] [delegate behavior] provided support for delegation by way of a many-to-one relationship
-* [9583e6b] [delegate behavior] Refactoretests to leave less trace
-* [197b533] documented the delegate behavior
-* [ca09d1d] Introducing Delegate behavior, for class table inheritance fans
-* [a78212c] Fixed bad formatting in generated query classes
-* [184e63f] Removed __call() from generted ActiveRecord classes.
-* [0e454c5] Avoid getClassname() to trigger registered autoloaders for nothing.
-* [74cd5eb] Added the ability to define full qualified classnames in build properties.
-* [e1662d0] Reverted change on the TINYINT default size (MysqlSchemaParser)
-* [a2965d4] Fixed CS
-* [9521482] Fixed TINYINT interpretation in MysqlSchemaParser.
-* [e939c2e] Improved generated code for findOneOrCreate() method with ENUM and ARRAY types.
-* [594d44e] Added missing link to the StandardEnglishPluralizer class
-* [61deedb] Added more unit tests for the StandardEnglishPluralizer + Fixed special cases.
-* [5288e48] Improved the StandardEnglishPluralizer. Fixed issue #4
-* [22159b2] Fixed double left-join & "with" issue when a third table is joined and "withed"
-* [ec41624] Fixed phpdoc in parser/
-* [73a7d21] Fixed phpdoc in validator/
-* [10f5dd5] Added unit tests for issue #35 and PR #37
-* [9e62f3c] One-line fix for issue #35 (https://github.com/propelorm/Propel/issues/35)
-* [e84f5fa] Set limit parameter to 0 (like intially done) if clear() is called
+* [5d6e4b0] [archivable behavior] Added the ability to use a custom archive class.
+* [5088e39] [archivable behavior] Added generated ActiveRecord::populateFromArchive() method
+* [182af0c] [archivable behavior] Initial commit
+* [ce59915] [Tests] More tests for MysqlSchemaParser
+* [20d407a] Changed visibility to be less 'open'. Related commit: 381e378cb17b388765dfbb5a3241dacbff449323
+* [dd10eec] [Tests] fixed script to handle reverse fixtures
+* [d64741a] Fixed the test file's syntax
+* [9584188] Fixed unit test
+* [8b20446] used 'SHOW FULL TABLES' instead of the previous one to handle multiple database
+* [acccc26] Excluded read only tables from being counted
+* [1cd82d6] handle views when using diff command
+* [7f89e83] Added unit test for MySQL schema parser
+* [8470dba] Added fixtures for MySQL reverse unit tests
+* [f75334c] Changed prototype to use the interface instead of an implementation class
+* [381e378] Changed visibility of simpleXmlToArray method in PropelConvertConfTask in order to use it in tests
+* [54ce432] Removed stray testing stuff that got left behind
+* [db4e041] FIX: Check that platform exists before using it
+* [be563e8] Fixed false positive in PostgreSQL migrations where generator would generate varchar-fields without explicit size as VARCHAR(255)
+* [7c84b79] Fixed postDelete hook in soft delete behavior
+* [39e3709] [SoftDeleteBehavior] Fixed missing post hook call
+* [8fc39e1] Added test to prove post hook is not fired on soft deleted objects.
+* [c5c30e0] set sequence name configurable
+* [082d27a] Added strict assertions
+* [1ad20fb] added unit-test for Table::appendXml (namespace & package attributes)
+* [3addf99] serialize namespace too
+* [76a3841] store table`s package name in Xml
+* [ff673c0] Added a tiny shell script to reset test fixtures
+* [3d6d4bd] fixed naming and default values in unit test
+* [67a77bf] Fixed bug in PhpNameGenerator. The default name convertor for table and column names is NameGenerator::CONV_METHOD_UNDERSCORE. This method has a slight bug resulting in an incorrect phpName for table using "_0" as a prefix:
+* [04fe003] fix usage of undefined variable
+* [ceb610f] `level` is reserved keyword in oracle
+* [57a0f2c] pass vendor`s type to VentorInfo::__construct in XMLElement::getVendorInfoForType()
+* [a3aaa76] detect autoincrement via sequences
+* [7c84546] [delegate behavior] Documented the fact that, finally, delegate behavior can handle inheritance over several levels
+* [8290ed5] [delegate behavior] Changed class table inheritance examples to show that the behavior is much more powerful than previously thought. Refs #40
+* [1f4ce85] Fixed MySQL type for a BOOLEAN
+* [5e7d765] [delegate behavior] Fixed typo in behavior documentation
+* [4ee22c0] [delegate behavior] Fixed coding standards
+* [4b327c6] [delegate behavior] Fixed wrong file permissions (old samba config)
+* [fe2ce45] [delegate behavior] Throwing exception at buildtime if the delegate table has a one-to-many relationship with the main table
+* [87ed930] [delegate behavior] provided support for delegation by way of a many-to-one relationship
+* [9583e6b] [delegate behavior] Refactoretests to leave less trace
+* [197b533] documented the delegate behavior
+* [ca09d1d] Introducing Delegate behavior, for class table inheritance fans
+* [a78212c] Fixed bad formatting in generated query classes
+* [184e63f] Removed __call() from generated ActiveRecord classes.
+* [0e454c5] Avoid getClassname() to trigger registered autoloaders for nothing.
+* [74cd5eb] Added the ability to define full qualified classnames in build properties.
+* [e1662d0] Reverted change on the TINYINT default size (MysqlSchemaParser)
+* [a2965d4] Fixed CS
+* [9521482] Fixed TINYINT interpretation in MysqlSchemaParser.
+* [e939c2e] Improved generated code for findOneOrCreate() method with ENUM and ARRAY types.
+* [594d44e] Added missing link to the StandardEnglishPluralizer class
+* [61deedb] Added more unit tests for the StandardEnglishPluralizer + Fixed special cases.
+* [5288e48] Improved the StandardEnglishPluralizer. Fixed issue #4
+* [22159b2] Fixed double left-join & "with" issue when a third table is joined and "withed"
+* [ec41624] Fixed phpdoc in parser/
+* [73a7d21] Fixed phpdoc in validator/
+* [10f5dd5] Added unit tests for issue #35 and PR #37
+* [9e62f3c] One-line fix for issue #35 (https://github.com/propelorm/Propel/issues/35)
+* [e84f5fa] Set limit parameter to 0 (like initially done) if clear() is called
--- ./vendor/propel/generator/resources/dtd/database.dtd	original
+++ ./vendor/propel/generator/resources/dtd/database.dtd	fixed
@@ -28 +28 @@
-  defaultTranslateMethode CDATA #IMPLIED
+  defaultTranslateMethod CDATA #IMPLIED
--- ./vendor/propel/generator/resources/xsl/database.xsl	original
+++ ./vendor/propel/generator/resources/xsl/database.xsl	fixed
@@ -88 +88 @@
-	Tranlate IdMethod attribute to idMethod attribute
+	Translate IdMethod attribute to idMethod attribute
@@ -102 +102 @@
-	Normalize a table, add some attribute with default values if ommitted and normalize all attribute and childnodes
+	Normalize a table, add some attribute with default values if omitted and normalize all attribute and childnodes
@@ -125 +125 @@
-	Normalize a foreign-key, add some attribute with default values if ommitted and normalize all attribute and childnodes
+	Normalize a foreign-key, add some attribute with default values if omitted and normalize all attribute and childnodes
--- ./vendor/propel/generator/resources/xsd/database.xsd	original
+++ ./vendor/propel/generator/resources/xsd/database.xsd	fixed
@@ -188 +188 @@
-	<!-- Restrict php class name to letters (upper- and lowercase), numbers and the _. Dot seperated -->
+	<!-- Restrict php class name to letters (upper- and lowercase), numbers and the _. Dot separated -->
@@ -195 +195 @@
-	<!-- Restrict php namespaces name to letters (upper- and lowercase), numbers and the backslash Dot seperated -->
+	<!-- Restrict php namespaces name to letters (upper- and lowercase), numbers and the backslash Dot separated -->
--- ./vendor/propel/generator/bin/phing.php	original
+++ ./vendor/propel/generator/bin/phing.php	fixed
@@ -5 +5 @@
- * This is the Phing command line launcher. It starts up the system evironment
+ * This is the Phing command line launcher. It starts up the system environment
--- ./vendor/propel/generator/build.xml-local	original
+++ ./vendor/propel/generator/build.xml-local	fixed
@@ -2 +2 @@
-    Use this file to faciliate easy per-project building.
+    Use this file to facilitate easy per-project building.
@@ -27 +27 @@
-  <available file="./build.properties" property="projBuildPopertiesExists"/>
+  <available file="./build.properties" property="projBuildPropertiesExists"/>
--- ./vendor/propel/generator/pear/build.properties	original
+++ ./vendor/propel/generator/pear/build.properties	fixed
@@ -1 +1 @@
-# In this file you can define any properties taht you want to affect
+# In this file you can define any properties that you want to affect
--- ./vendor/propel/generator/build.xml	original
+++ ./vendor/propel/generator/build.xml	fixed
@@ -2 +2 @@
-    Use this file to faciliate easy per-project building.
+    Use this file to facilitate easy per-project building.
@@ -36 +36 @@
-  <available file="${propel.project.dir}/${build.properties}" property="projBuildPopertiesExists"/>
+  <available file="${propel.project.dir}/${build.properties}" property="projBuildPropertiesExists"/>
@@ -39 +39 @@
-<target name="check-buildprops" unless="projBuildPopertiesExists" depends="check-buildprops-exists">
+<target name="check-buildprops" unless="projBuildPropertiesExists" depends="check-buildprops-exists">
@@ -60 +60 @@
-<target name="check-buildprops-for-propel-gen" if="using.propel-gen" unless="projBuildPopertiesExists" depends="check-buildprops-exists">
+<target name="check-buildprops-for-propel-gen" if="using.propel-gen" unless="projBuildPropertiesExists" depends="check-buildprops-exists">
--- ./vendor/propel/generator/pear/pear-build.xml	original
+++ ./vendor/propel/generator/pear/pear-build.xml	fixed
@@ -2 +2 @@
-    Use this file to faciliate easy per-project building using
+    Use this file to facilitate easy per-project building using
--- ./vendor/propel/generator/build.properties-sample	original
+++ ./vendor/propel/generator/build.properties-sample	fixed
@@ -9 +9 @@
-# that you would like to use accross all of your Propel projects.
+# that you would like to use across all of your Propel projects.
@@ -30 +30 @@
-# You can set this here, but it's preferrable to set this in a
+# You can set this here, but it's preferable to set this in a
@@ -46 +46 @@
-# You can set this here, but it's preferrable to set this in a
+# You can set this here, but it's preferable to set this in a
@@ -76 +76 @@
-#   methods to easily retreive foreign key relationships.
+#   methods to easily retrieve foreign key relationships.
@@ -117 +117 @@
-# You can set them here, but it's preferrable to set these properties
+# You can set them here, but it's preferable to set these properties
@@ -127 +127 @@
-# are using multiple databses) you can use the @DB@ token which
+# are using multiple databases) you can use the @DB@ token which
@@ -139 +139 @@
-# (This does not apply to SQLite since the databse is automatically created
+# (This does not apply to SQLite since the database is automatically created
--- ./vendor/propel/generator/lib/reverse/oracle/OracleSchemaParser.php	original
+++ ./vendor/propel/generator/lib/reverse/oracle/OracleSchemaParser.php	fixed
@@ -35 +35 @@
-     * Supported but non existant as a specific type in Oracle:
+     * Supported but non existent as a specific type in Oracle:
--- ./vendor/propel/generator/lib/task/PropelDataDumpTask.php	original
+++ ./vendor/propel/generator/lib/task/PropelDataDumpTask.php	fixed
@@ -12 +12 @@
- * Dumps the contenst of selected databases to XML data dump file.
+ * Dumps the contents of selected databases to XML data dump file.
@@ -265 +265 @@
-        // 2) Now go create the XML files from teh database(s)
+        // 2) Now go create the XML files from the database(s)
--- ./vendor/propel/generator/lib/task/PropelSQLExec.php	original
+++ ./vendor/propel/generator/lib/task/PropelSQLExec.php	fixed
@@ -240,4 +240,4 @@
-        $successfullStatements = 0;
-        $this->log(sprintf('Executing SQL statements...'));
-        foreach ($statements as $database => $statementList) {
-            $successfullStatements += $this->insertDatabaseSqlFiles($database, $statementList);
+        $successfulStatements = 0;
+        $this->log(sprintf('Executing SQL statements...'));
+        foreach ($statements as $database => $statementList) {
+            $successfulStatements += $this->insertDatabaseSqlFiles($database, $statementList);
@@ -246 +246 @@
-        $this->log(sprintf('SQL execution complete. %d statements successfully executed.', $successfullStatements));
+        $this->log(sprintf('SQL execution complete. %d statements successfully executed.', $successfulStatements));
@@ -307 +307 @@
-                    $this->log("  Commiting transaction", Project::MSG_VERBOSE);
+                    $this->log("  Committing transaction", Project::MSG_VERBOSE);
--- ./vendor/propel/generator/lib/task/PropelConvertConfTask.php	original
+++ ./vendor/propel/generator/lib/task/PropelConvertConfTask.php	fixed
@@ -216 +216 @@
-            // add the childs attributes as if they where children
+            // add the children attributes as if they where children
@@ -310 +310 @@
-                        // for single tabel inheritance tables.
+                        // for single table inheritance tables.
--- ./vendor/propel/generator/lib/task/PropelSQLDiffTask.php	original
+++ ./vendor/propel/generator/lib/task/PropelSQLDiffTask.php	fixed
@@ -143,2 +143,2 @@
-        $appDatasFromXml = $this->getDataModels();
-        $appDataFromXml = array_pop($appDatasFromXml);
+        $appDataFromXml = $this->getDataModels();
+        $appDataFromXml = array_pop($appDataFromXml);
--- ./vendor/propel/generator/lib/task/AbstractPropelDataModelTask.php	original
+++ ./vendor/propel/generator/lib/task/AbstractPropelDataModelTask.php	fixed
@@ -271 +271 @@
-                    throw new IOException("Unable to create Ouptut directory: " . $outputDirectory->getAbsolutePath());
+                    throw new IOException("Unable to create Output directory: " . $outputDirectory->getAbsolutePath());
@@ -552 +552 @@
-        $mainAppData->joinAppDatas($ads);
+        $mainAppData->joinAppData($ads);
--- ./vendor/propel/generator/lib/task/BasePropelMigrationTask.php	original
+++ ./vendor/propel/generator/lib/task/BasePropelMigrationTask.php	fixed
@@ -73 +73 @@
-                    throw new IOException("Unable to create Ouptut directory: " . $outputDirectory->getAbsolutePath());
+                    throw new IOException("Unable to create Output directory: " . $outputDirectory->getAbsolutePath());
--- ./vendor/propel/generator/lib/model/Domain.php	original
+++ ./vendor/propel/generator/lib/model/Domain.php	fixed
@@ -246 +246 @@
-     * @param string $value The tyep to set.
+     * @param string $value The type to set.
@@ -302 +302 @@
-     * @param ColumnDefaultValue $value The defualt value object
+     * @param ColumnDefaultValue $value The default value object
--- ./vendor/propel/generator/lib/model/ConstraintNameGenerator.php	original
+++ ./vendor/propel/generator/lib/model/ConstraintNameGenerator.php	fixed
@@ -33 +33 @@
-     * of this contraint.
+     * of this constraint.
--- ./vendor/propel/generator/lib/model/Behavior.php	original
+++ ./vendor/propel/generator/lib/model/Behavior.php	fixed
@@ -196 +196 @@
-     * @param array  $vars        An associative array of argumens to be rendered
+     * @param array  $vars        An associative array of arguments to be rendered
--- ./vendor/propel/generator/lib/model/Column.php	original
+++ ./vendor/propel/generator/lib/model/Column.php	fixed
@@ -243 +243 @@
-            // use boleanValue()
+            // use booleanValue()
--- ./vendor/propel/generator/lib/model/VendorInfo.php	original
+++ ./vendor/propel/generator/lib/model/VendorInfo.php	fixed
@@ -102 +102 @@
-     * @return mixed  Paramter value.
+     * @return mixed  Parameter value.
@@ -128 +128 @@
-     * @param array $params Paramter data.
+     * @param array $params Parameter data.
--- ./vendor/propel/generator/lib/model/ColumnDefaultValue.php	original
+++ ./vendor/propel/generator/lib/model/ColumnDefaultValue.php	fixed
@@ -94 +94 @@
-     * @return boolean            Wheter this object represents same default value as $other
+     * @return boolean            Whether this object represents same default value as $other
--- ./vendor/propel/generator/lib/model/Table.php	original
+++ ./vendor/propel/generator/lib/model/Table.php	fixed
@@ -1349 +1349 @@
-     * @return boolan Value of readOnly.
+     * @return boolean Value of readOnly.
@@ -1620 +1620 @@
-     * Eg. Foreign key (a,b,c) refrences tbl(x,y,z) will be returned of col is either a,b or c.
+     * Eg. Foreign key (a,b,c) references tbl(x,y,z) will be returned of col is either a,b or c.
--- ./vendor/propel/generator/lib/model/ForeignKey.php	original
+++ ./vendor/propel/generator/lib/model/ForeignKey.php	fixed
@@ -602 +602 @@
-     * Whether this foreign key is matched by an invertes foreign key (on foreign table).
+     * Whether this foreign key is matched by an inverse foreign key (on foreign table).
--- ./vendor/propel/generator/lib/model/PhpNameGenerator.php	original
+++ ./vendor/propel/generator/lib/model/PhpNameGenerator.php	fixed
@@ -31 +31 @@
-     * stript from name prior to generate the resulting name.
+     * stripped from name prior to generate the resulting name.
@@ -82 +82 @@
-     * of name and each letter after the <code>STD_SEPERATOR</code>,
+     * of name and each letter after the <code>STD_SEPARATOR</code>,
--- ./vendor/propel/generator/lib/model/AppData.php	original
+++ ./vendor/propel/generator/lib/model/AppData.php	fixed
@@ -261 +261 @@
-    public function joinAppDatas($ads)
+    public function joinAppData($ads)
--- ./vendor/propel/generator/lib/model/PropelTypes.php	original
+++ ./vendor/propel/generator/lib/model/PropelTypes.php	fixed
@@ -247 +247 @@
-     * Resturns the PDO type (PDO::PARAM_* constant) value.
+     * Returns the PDO type (PDO::PARAM_* constant) value.
@@ -256 +256 @@
-     * Resturns the PDO type ('PDO::PARAM_*' constant) name.
+     * Returns the PDO type ('PDO::PARAM_*' constant) name.
--- ./vendor/propel/generator/lib/behavior/sluggable/SluggableBehavior.php	original
+++ ./vendor/propel/generator/lib/behavior/sluggable/SluggableBehavior.php	fixed
@@ -240 +240 @@
- * Make sure the slug is short enough to accomodate the column size
+ * Make sure the slug is short enough to accommodate the column size
@@ -268 +268 @@
- * @param	int    \$increment the count of occurences of the slug
+ * @param	int    \$increment the count of occurrences of the slug
--- ./vendor/propel/generator/lib/behavior/versionable/VersionableBehaviorObjectBuilderModifier.php	original
+++ ./vendor/propel/generator/lib/behavior/versionable/VersionableBehaviorObjectBuilderModifier.php	fixed
@@ -303,3 +303,3 @@
-    if (\$relateds = \$this->get{$fkGetter}(\$con)->toKeyValue('{$fk->getTable()->getFirstPrimaryKeyColumn()->getPhpName()}', 'Version')) {
-        \$version->set{$idsColumn->getPhpName()}(array_keys(\$relateds));
-        \$version->set{$versionsColumn->getPhpName()}(array_values(\$relateds));
+    if (\$relates = \$this->get{$fkGetter}(\$con)->toKeyValue('{$fk->getTable()->getFirstPrimaryKeyColumn()->getPhpName()}', 'Version')) {
+        \$version->set{$idsColumn->getPhpName()}(array_keys(\$relates));
+        \$version->set{$versionsColumn->getPhpName()}(array_values(\$relates));
@@ -321 +321 @@
- * Sets the properties of the curent object to the value they had at a specific version
+ * Sets the properties of the current object to the value they had at a specific version
@@ -353 +353 @@
- * Sets the properties of the curent object to the value they had at a specific version
+ * Sets the properties of the current object to the value they had at a specific version
--- ./vendor/propel/generator/lib/behavior/TimestampableBehavior.php	original
+++ ./vendor/propel/generator/lib/behavior/TimestampableBehavior.php	fixed
@@ -53 +53 @@
-     * @param  string $column One of the behavior colums, 'create_column' or 'update_column'
+     * @param  string $column One of the behavior columns, 'create_column' or 'update_column'
--- ./vendor/propel/generator/lib/builder/util/PropelTemplate.php	original
+++ ./vendor/propel/generator/lib/builder/util/PropelTemplate.php	fixed
@@ -61 +61 @@
-     * @param array $vars An associative array of argumens to be rendered
+     * @param array $vars An associative array of arguments to be rendered
--- ./vendor/propel/generator/lib/builder/util/XmlToDataSQL.php	original
+++ ./vendor/propel/generator/lib/builder/util/XmlToDataSQL.php	fixed
@@ -85 +85 @@
-     * Flag for enabing debug output to aid in parser tracing.
+     * Flag for enabling debug output to aid in parser tracing.
--- ./vendor/propel/generator/lib/builder/util/StandardEnglishPluralizer.php	original
+++ ./vendor/propel/generator/lib/builder/util/StandardEnglishPluralizer.php	fixed
@@ -59 +59 @@
-        'ois'  => 'ois',
+        'is'  => 'is',
--- ./vendor/propel/generator/lib/behavior/nestedset/NestedSetBehaviorObjectBuilderModifier.php	original
+++ ./vendor/propel/generator/lib/behavior/nestedset/NestedSetBehaviorObjectBuilderModifier.php	fixed
@@ -1523 +1523 @@
- * Alias for countDecendants(), for BC with Propel 1.4 nested sets
+ * Alias for countDescendants(), for BC with Propel 1.4 nested sets
--- ./vendor/propel/generator/lib/builder/sql/pgsql/PgsqlDataSQLBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/sql/pgsql/PgsqlDataSQLBuilder.php	fixed
@@ -40 +40 @@
-     * The main method in this class, returns the SQL for INSERTing data into a row.
+     * The main method in this class, returns the SQL for INSERTTing data into a row.
--- ./vendor/propel/generator/lib/builder/sql/DataSQLBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/sql/DataSQLBuilder.php	fixed
@@ -74 +74 @@
-     * The main method in this class, returns the SQL for INSERTing data into a row.
+     * The main method in this class, returns the SQL for INSERTTing data into a row.
--- ./vendor/propel/generator/lib/builder/om/QueryInheritanceBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/QueryInheritanceBuilder.php	fixed
@@ -62 +62 @@
-     * Set the child object that we're operating on currrently.
+     * Set the child object that we're operating on currently.
@@ -117 +117 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5NestedSetBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5NestedSetBuilder.php	fixed
@@ -55 +55 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5InterfaceBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5InterfaceBuilder.php	fixed
@@ -44 +44 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5NestedSetPeerBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5NestedSetPeerBuilder.php	fixed
@@ -55 +55 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
@@ -1042 +1042 @@
-     * @return array Array in order of heirarchy
+     * @return array Array in order of hierarchy
--- ./vendor/propel/generator/lib/builder/om/PHP5ExtensionNodePeerBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5ExtensionNodePeerBuilder.php	fixed
@@ -46 +46 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5NodePeerBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5NodePeerBuilder.php	fixed
@@ -52 +52 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
@@ -422 +422 @@
-        //the following dot isn`t mean`t a nodeKeySeperator
+        //the following dot isn`t mean`t a nodeKeySeparator
--- ./vendor/propel/generator/lib/builder/om/ObjectBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/ObjectBuilder.php	fixed
@@ -50 +50 @@
-     * in different langauges (e.g. PHP4 and PHP5).
+     * in different languages (e.g. PHP4 and PHP5).
@@ -84 +84 @@
-     * in different langauges (e.g. PHP4 and PHP5).
+     * in different languages (e.g. PHP4 and PHP5).
--- ./vendor/propel/generator/lib/builder/om/PHP5ExtensionPeerBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5ExtensionPeerBuilder.php	fixed
@@ -58 +58 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5PeerBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5PeerBuilder.php	fixed
@@ -93 +93 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
@@ -1766 +1766 @@
-        // it may make sense to refactor this, provided that thigns don't
+        // it may make sense to refactor this, provided that things don't
--- ./vendor/propel/generator/lib/builder/om/PHP5MultiExtendObjectBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5MultiExtendObjectBuilder.php	fixed
@@ -49 +49 @@
-     * Set the child object that we're operating on currrently.
+     * Set the child object that we're operating on currently.
@@ -111 +111 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5ExtensionNodeBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5ExtensionNodeBuilder.php	fixed
@@ -46 +46 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5TableMapBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5TableMapBuilder.php	fixed
@@ -60 +60 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/ExtensionQueryInheritanceBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/ExtensionQueryInheritanceBuilder.php	fixed
@@ -50 +50 @@
-     * Set the child object that we're operating on currrently.
+     * Set the child object that we're operating on currently.
@@ -86 +86 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/QueryBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/QueryBuilder.php	fixed
@@ -63 +63 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
@@ -248 +248 @@
-     * @param     string \$dbName The dabase name
+     * @param     string \$dbName The database name
@@ -416 +416 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./vendor/propel/generator/lib/builder/om/PHP5ObjectNoCollectionBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5ObjectNoCollectionBuilder.php	fixed
@@ -579 +579 @@
-            // it doesn't make sense to join in rows from the curent table, since we are fetching
+            // it doesn't make sense to join in rows from the current table, since we are fetching
@@ -694 +694 @@
-    } // addRefererInit()
+    } // addReferrerInit()
@@ -729 +729 @@
-    } // addRefererAdd
+    } // addReferrerAdd
@@ -827 +827 @@
-    } // addRefererCount
+    } // addReferrerCount
@@ -924 +924 @@
-    } // addRefererGet()
+    } // addReferrerGet()
--- ./vendor/propel/generator/lib/builder/om/PHP5ExtensionObjectBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5ExtensionObjectBuilder.php	fixed
@@ -58 +58 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/ExtensionQueryBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/ExtensionQueryBuilder.php	fixed
@@ -48 +48 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/builder/om/PHP5NodeBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5NodeBuilder.php	fixed
@@ -52 +52 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/generator/lib/config/GeneratorConfig.php	original
+++ ./vendor/propel/generator/lib/config/GeneratorConfig.php	fixed
@@ -170 +170 @@
-            throw new BuildException("Specified platform class ($clazz) does not implement teh PropelPlatformInterface interface.");
+            throw new BuildException("Specified platform class ($clazz) does not implement the PropelPlatformInterface interface.");
--- ./vendor/propel/generator/build-propel.xml	original
+++ ./vendor/propel/generator/build-propel.xml	fixed
@@ -17 +17 @@
-  <available file="${propel.home}/build.properties" property="globalBuildPopertiesExists"/>
+  <available file="${propel.home}/build.properties" property="globalBuildPropertiesExists"/>
@@ -21 +21 @@
-  		<isset property="globalBuildPopertiesExists"/>
+  		<isset property="globalBuildPropertiesExists"/>
@@ -30 +30 @@
-    with setting the corret defaults.
+    with setting the correct defaults.
@@ -136 +136 @@
-		If so, a warning is issued, since identifier quoting is only paritally implemented & this point.  -->
+		If so, a warning is issued, since identifier quoting is only partially implemented & this point.  -->
--- ./vendor/propel/runtime/lib/util/NodePeer.php	original
+++ ./vendor/propel/runtime/lib/util/NodePeer.php	fixed
@@ -271 +271 @@
-     * @return array     Array in order of heirarchy
+     * @return array     Array in order of hierarchy
--- ./vendor/propel/runtime/lib/util/PropelColumnTypes.php	original
+++ ./vendor/propel/runtime/lib/util/PropelColumnTypes.php	fixed
@@ -85 +85 @@
-     * Resturns the PDO type (PDO::PARAM_* constant) value for the Propel type provided.
+     * Returns the PDO type (PDO::PARAM_* constant) value for the Propel type provided.
--- ./vendor/propel/runtime/lib/util/PropelConditionalProxy.php	original
+++ ./vendor/propel/runtime/lib/util/PropelConditionalProxy.php	fixed
@@ -103 +103 @@
-     * return the current conditionnal status
+     * return the current conditional status
--- ./vendor/propel/runtime/lib/util/BasePeer.php	original
+++ ./vendor/propel/runtime/lib/util/BasePeer.php	fixed
@@ -802 +802 @@
-                    list($realtable, $tableName) = explode(' ', $ftable);
+                    list($relatable, $tableName) = explode(' ', $ftable);
--- ./vendor/propel/runtime/lib/validator/MatchValidator.php	original
+++ ./vendor/propel/runtime/lib/validator/MatchValidator.php	fixed
@@ -27 +27 @@
- *     <!-- allow strings that match the email adress pattern -->
+ *     <!-- allow strings that match the email address pattern -->
@@ -47 +47 @@
-     * @return string Prepared regular expession.
+     * @return string Prepared regular expression.
--- ./vendor/propel/runtime/lib/validator/TypeValidator.php	original
+++ ./vendor/propel/runtime/lib/validator/TypeValidator.php	fixed
@@ -74 +74 @@
-                throw new PropelException('Unkonwn type ' . $map->getValue());
+                throw new PropelException('Unknown type ' . $map->getValue());
--- ./vendor/propel/runtime/lib/validator/NotMatchValidator.php	original
+++ ./vendor/propel/runtime/lib/validator/NotMatchValidator.php	fixed
@@ -29 +29 @@
- *       message="Please enter a valid email adress." />
+ *       message="Please enter a valid email address." />
--- ./vendor/propel/runtime/lib/validator/ValidationFailed.php	original
+++ ./vendor/propel/runtime/lib/validator/ValidationFailed.php	fixed
@@ -111 +111 @@
-     * "magic" method to get string represenation of object.
+     * "magic" method to get string representation of object.
--- ./vendor/propel/runtime/lib/adapter/DBMSSQL.php	original
+++ ./vendor/propel/runtime/lib/adapter/DBMSSQL.php	fixed
@@ -223 +223 @@
-                //agregate columns must always have an alias clause
+                //aggregate columns must always have an alias clause
--- ./vendor/propel/runtime/lib/adapter/DBAdapter.php	original
+++ ./vendor/propel/runtime/lib/adapter/DBAdapter.php	fixed
@@ -145 +145 @@
-     * @return string The text delimeter.
+     * @return string The text delimiter.
@@ -204 +204 @@
-     * Quotes database objec identifiers (table names, col names, sequences, etc.).
+     * Quotes database object identifiers (table names, col names, sequences, etc.).
@@ -214 +214 @@
-     * Quotes a database table which could have space seperating it from an alias, both should be identified seperately
+     * Quotes a database table which could have space separating it from an alias, both should be identified separately
@@ -272 +272 @@
-     * Formats a temporal value brefore binding, given a ColumnMap object.
+     * Formats a temporal value before binding, given a ColumnMap object.
@@ -336 +336 @@
-     * By default false is returned -> backwards compability.
+     * By default false is returned -> backwards compatibility.
@@ -531 +531 @@
-     * $db->populateStmtValues($stmt, $params, Propel::getDatabaseMap($critera->getDbName()));
+     * $db->populateStmtValues($stmt, $params, Propel::getDatabaseMap($criteria->getDbName()));
--- ./vendor/propel/runtime/lib/collection/PropelOnDemandCollection.php	original
+++ ./vendor/propel/runtime/lib/collection/PropelOnDemandCollection.php	fixed
@@ -124 +124 @@
-        throw new PropelException('The On Demand Collection does not allow acces by offset');
+        throw new PropelException('The On Demand Collection does not allow access by offset');
@@ -138 +138 @@
-        throw new PropelException('The On Demand Collection does not allow acces by offset');
+        throw new PropelException('The On Demand Collection does not allow access by offset');
@@ -219 +219 @@
-        throw new PropelException('The On Demand Collection does not allow acces by offset');
+        throw new PropelException('The On Demand Collection does not allow access by offset');
@@ -224 +224 @@
-        throw new PropelException('The On Demand Collection does not allow acces by offset');
+        throw new PropelException('The On Demand Collection does not allow access by offset');
@@ -244 +244 @@
-        throw new PropelException('The On Demand Collection does not allow acces by offset');
+        throw new PropelException('The On Demand Collection does not allow access by offset');
--- ./vendor/propel/runtime/lib/collection/PropelArrayCollection.php	original
+++ ./vendor/propel/runtime/lib/collection/PropelArrayCollection.php	fixed
@@ -177 +177 @@
-     * And the seconf for the value.
+     * And the second for the value.
--- ./vendor/propel/runtime/lib/collection/PropelCollection.php	original
+++ ./vendor/propel/runtime/lib/collection/PropelCollection.php	fixed
@@ -519 +519 @@
-     * A PropelOnDemandCollection cannot be exported. Any attempt will result in a PropelExecption being thrown.
+     * A PropelOnDemandCollection cannot be exported. Any attempt will result in a PropelException being thrown.
--- ./vendor/propel/runtime/lib/collection/PropelObjectCollection.php	original
+++ ./vendor/propel/runtime/lib/collection/PropelObjectCollection.php	fixed
@@ -209 +209 @@
-     * And the seconf for the value.
+     * And the second for the value.
--- ./vendor/propel/runtime/lib/connection/PropelPDO.php	original
+++ ./vendor/propel/runtime/lib/connection/PropelPDO.php	fixed
@@ -216 +216 @@
-     * To be used in an evironment where Propelexceptions are caught.
+     * To be used in an environment where Propelexceptions are caught.
@@ -220 +220 @@
-    public function isCommitable()
+    public function isCommittable()
@@ -509 +509 @@
-            throw new PropelException('Extending PDOStatement is not supported with persistent connections. Count would be inaccurate, because we cannot count the PDOStatment::execute() calls. Either don\'t use persistent connections or don\'t call PropelPDO::getQueryCount()');
+            throw new PropelException('Extending PDOStatement is not supported with persistent connections. Count would be inaccurate, because we cannot count the PDOStatement::execute() calls. Either don\'t use persistent connections or don\'t call PropelPDO::getQueryCount()');
--- ./vendor/propel/runtime/lib/query/Criterion.php	original
+++ ./vendor/propel/runtime/lib/query/Criterion.php	fixed
@@ -38 +38 @@
-    protected $realtable;
+    protected $relatable;
@@ -108,3 +108,3 @@
-        // init $this->realtable
-        $realtable = $criteria->getTableForAlias($this->table);
-        $this->realtable = $realtable ? $realtable : $this->table;
+        // init $this->relatable
+        $relatable = $criteria->getTableForAlias($this->table);
+        $this->relatable = $relatable ? $relatable : $this->table;
@@ -359 +359 @@
-                $params[] = array('table' => $this->realtable, 'column' => $this->column, 'value' => $value);
+                $params[] = array('table' => $this->relatable, 'column' => $this->column, 'value' => $value);
@@ -397 +397 @@
-        $params[] = array('table' => $this->realtable, 'column' => $this->column, 'value' => $this->value);
+        $params[] = array('table' => $this->relatable, 'column' => $this->column, 'value' => $this->value);
@@ -431 +431 @@
-                $params[] = array('table' => $this->realtable, 'column' => $this->column, 'value' => $this->value);
+                $params[] = array('table' => $this->relatable, 'column' => $this->column, 'value' => $this->value);
--- ./vendor/propel/generator/lib/builder/om/PHP5ObjectBuilder.php	original
+++ ./vendor/propel/generator/lib/builder/om/PHP5ObjectBuilder.php	fixed
@@ -186 +186 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
@@ -370 +370 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -3358 +3358 @@
-            // it doesn't make sense to join in rows from the curent table, since we are fetching
+            // it doesn't make sense to join in rows from the current table, since we are fetching
@@ -3525 +3525 @@
-    } // addRefererClear()
+    } // addReferrerClear()
@@ -3581 +3581 @@
-    } // addRefererInit()
+    } // addReferrerInit()
@@ -3623 +3623 @@
-    } // addRefererAdd
+    } // addReferrerAdd
@@ -3677 +3677 @@
-    } // addRefererCount
+    } // addReferrerCount
@@ -3755 +3755 @@
-    } // addRefererGet()
+    } // addReferrerGet()
@@ -4100 +4100 @@
-    } // addRefererClear()
+    } // addReferrerClear()
@@ -4427 +4427 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -5075 +5075 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -5089 +5089 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -5289 +5289 @@
-                //		it seems to work as expected and is probably desireable to have those referrers from same table deep-copied.
+                //		it seems to work as expected and is probably desirable to have those referrers from same table deep-copied.
--- ./vendor/propel/runtime/lib/query/ModelCriteria.php	original
+++ ./vendor/propel/runtime/lib/query/ModelCriteria.php	fixed
@@ -59 +59 @@
-     * @param string $dbName     The dabase name
+     * @param string $dbName     The database name
@@ -953 +953 @@
-     *              Defaults to Criteria::LOGICAL_AND, also accapts Criteria::LOGICAL_OR
+     *              Defaults to Criteria::LOGICAL_AND, also accepts Criteria::LOGICAL_OR
@@ -2104 +2104 @@
-     *                  array('table' => $realtable, 'column' => $column, 'value' => $value)
+     *                  array('table' => $relatable, 'column' => $column, 'value' => $value)
@@ -2190 +2190 @@
-                // Test if first argument is suplied, else don't provide an alias to joinXXX (default value)
+                // Test if first argument is supplied, else don't provide an alias to joinXXX (default value)
--- ./vendor/propel/runtime/lib/query/ModelCriterion.php	original
+++ ./vendor/propel/runtime/lib/query/ModelCriterion.php	fixed
@@ -126 +126 @@
-            $params[] = array('table' => $this->realtable, 'column' => $this->column, 'value' => $this->value);
+            $params[] = array('table' => $this->relatable, 'column' => $this->column, 'value' => $this->value);
@@ -170 +170 @@
-            $params[] = array('table' => $this->realtable, 'column' => $this->column, 'value' => $value);
+            $params[] = array('table' => $this->relatable, 'column' => $this->column, 'value' => $value);
@@ -190 +190 @@
-            $params[] = array('table' => $this->realtable, 'column' => $this->column, 'value' => $value);
+            $params[] = array('table' => $this->relatable, 'column' => $this->column, 'value' => $value);
--- ./vendor/propel/runtime/lib/Propel.php	original
+++ ./vendor/propel/runtime/lib/Propel.php	fixed
@@ -41 +41 @@
-     * A constant defining 'System is unusuable' logging level
+     * A constant defining 'System is unusable' logging level
@@ -533 +533 @@
-     * @param string $name The datasource name that is used to look up the DSN from the runtime configuation file.
+     * @param string $name The datasource name that is used to look up the DSN from the runtime configuration file.
@@ -561 +561 @@
-     *                          from the runtime configuation file. Empty name not allowed.
+     *                          from the runtime configuration file. Empty name not allowed.
@@ -587 +587 @@
-     *                          from the runtime configuation file. Empty name not allowed.
+     *                          from the runtime configuration file. Empty name not allowed.
@@ -631 +631 @@
-     * @param array  $conparams    Connection paramters.
+     * @param array  $conparams    Connection parameters.
@@ -703 +703 @@
-     * Internal function to handle driver options or conneciton attributes in PDO.
+     * Internal function to handle driver options or connection attributes in PDO.
@@ -844 +844 @@
-     * @param  string $class dot-path to clas (e.g. path.to.my.ClassName).
+     * @param  string $class dot-path to class (e.g. path.to.my.ClassName).
--- ./vendor/propel/runtime/lib/query/Criteria.php	original
+++ ./vendor/propel/runtime/lib/query/Criteria.php	fixed
@@ -184 +184 @@
-     * Storage of join data. colleciton of Join objects.
+     * Storage of join data. collection of Join objects.
@@ -204 +204 @@
-    /** The name of the database as given in the contructor. */
+    /** The name of the database as given in the constructor. */
@@ -249 +249 @@
-     * @param string $dbName The dabase name.
+     * @param string $dbName The database name.
@@ -370 +370 @@
-     * Remove an alias for a table (useful when merging Criterias).
+     * Remove an alias for a table (useful when merging Criteria).
@@ -735 +735 @@
-     * This method adds a new criterion to the list of criterias.
+     * This method adds a new criterion to the list of criteria.
@@ -1515 +1515 @@
-     *            Defaults to Criteria::LOGICAL_AND, also accapts Criteria::LOGICAL_OR
+     *            Defaults to Criteria::LOGICAL_AND, also accepts Criteria::LOGICAL_OR
@@ -1627 +1627 @@
-     *  - If the first argument is a Criterion, it just resturns this Criterion.
+     *  - If the first argument is a Criterion, it just returns this Criterion.
--- ./vendor/propel/runtime/lib/map/ValidatorMap.php	original
+++ ./vendor/propel/runtime/lib/map/ValidatorMap.php	fixed
@@ -33 +33 @@
-    /** execption message thrown on invalid input */
+    /** exception message thrown on invalid input */
--- ./vendor/propel/runtime/lib/map/TableMap.php	original
+++ ./vendor/propel/runtime/lib/map/TableMap.php	fixed
@@ -681 +681 @@
-     * @deprecated Use ColumnMap::normalizeColumName() instead
+     * @deprecated Use ColumnMap::normalizeColumnName() instead
--- ./vendor/propel/test/fixtures/nestedset/build.properties	original
+++ ./vendor/propel/test/fixtures/nestedset/build.properties	fixed
@@ -21 +21 @@
-# are using multiple databses) you can use the @DB@ token which
+# are using multiple databases) you can use the @DB@ token which
--- ./vendor/propel/test/fixtures/bookstore/build.properties	original
+++ ./vendor/propel/test/fixtures/bookstore/build.properties	fixed
@@ -25 +25 @@
-# are using multiple databses) you can use the @DB@ token which
+# are using multiple databases) you can use the @DB@ token which
--- ./vendor/propel/test/fixtures/namespaced/build.properties	original
+++ ./vendor/propel/test/fixtures/namespaced/build.properties	fixed
@@ -24 +24 @@
-# are using multiple databses) you can use the @DB@ token which
+# are using multiple databases) you can use the @DB@ token which
--- ./vendor/propel/test/testsuite/generator/model/TableTest.php	original
+++ ./vendor/propel/test/testsuite/generator/model/TableTest.php	fixed
@@ -290 +290 @@
-        $appData1->joinAppDatas(array($appData2));
+        $appData1->joinAppData(array($appData2));
--- ./vendor/propel/test/testsuite/generator/behavior/i18n/I18nBehaviorObjectBuilderModifierTest.php	original
+++ ./vendor/propel/test/testsuite/generator/behavior/i18n/I18nBehaviorObjectBuilderModifierTest.php	fixed
@@ -307 +307 @@
-    public function testClearRemovesExistingTranlsations()
+    public function testClearRemovesExistingTranslations()
--- ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorQueryBuilderModifierWithScopeTest.php	original
+++ ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorQueryBuilderModifierWithScopeTest.php	fixed
@@ -100 +100 @@
-        $this->assertEquals($coll, $objs, 'decendantsOf() filters by descendants of the same scope');
+        $this->assertEquals($coll, $objs, 'descendantsOf() filters by descendants of the same scope');
--- ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorQueryBuilderModifierTest.php	original
+++ ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorQueryBuilderModifierTest.php	fixed
@@ -40 +40 @@
-        $this->assertEquals($coll, $objs, 'decendantsOf() filters by descendants');
+        $this->assertEquals($coll, $objs, 'descendantsOf() filters by descendants');
@@ -46 +46 @@
-        $this->assertEquals($coll, $objs, 'decendantsOf() filters by descendants');
+        $this->assertEquals($coll, $objs, 'descendantsOf() filters by descendants');
--- ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorPeerBuilderModifierWithScopeTest.php	original
+++ ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorPeerBuilderModifierWithScopeTest.php	fixed
@@ -208 +208 @@
-        $this->assertEquals($this->dumpTreeWithScope(1), $expected, 'shiftLevel can shift level whith a scope');
+        $this->assertEquals($this->dumpTreeWithScope(1), $expected, 'shiftLevel can shift level with a scope');
--- ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorObjectBuilderModifierTest.php	original
+++ ./vendor/propel/test/testsuite/generator/behavior/nestedset/NestedSetBehaviorObjectBuilderModifierTest.php	fixed
@@ -579 +579 @@
-        $this->assertEquals(0, count($t4->getSiblings()), 'getSiblings() returns an empty colleciton for lone children');
+        $this->assertEquals(0, count($t4->getSiblings()), 'getSiblings() returns an empty collection for lone children');
--- ./vendor/propel/test/testsuite/generator/builder/NamespaceTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/NamespaceTest.php	fixed
@@ -102,2 +102,2 @@
-        $noPublihser = \Baz\NamespacedPublisherQuery::create()->findOne();
-        $this->assertNull($noPublihser);
+        $noPublisher = \Baz\NamespacedPublisherQuery::create()->findOne();
+        $this->assertNull($noPublisher);
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectWithFixturesTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectWithFixturesTest.php	fixed
@@ -16 +16 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedNestedSetPeerTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedNestedSetPeerTest.php	fixed
@@ -20 +20 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/PHP5TableMapBuilderTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/PHP5TableMapBuilderTest.php	fixed
@@ -143 +143 @@
-        $this->assertFalse($bookTable->isSingleTableInheritance(), 'isSingleTabkeInheritance() returns false by default');
+        $this->assertFalse($bookTable->isSingleTableInheritance(), 'isSingleTableInheritance() returns false by default');
@@ -146 +146 @@
-        $this->assertTrue($empTable->isSingleTableInheritance(), 'isSingleTabkeInheritance() returns true for tables using single table inheritance');
+        $this->assertTrue($empTable->isSingleTableInheritance(), 'isSingleTableInheritance() returns true for tables using single table inheritance');
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectLobTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectLobTest.php	fixed
@@ -24 +24 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectRelTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectRelTest.php	fixed
@@ -20 +20 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
@@ -142,2 +142,2 @@
-        $this->assertTrue(method_exists('BookClubList', 'getBooks'), 'Object generator correcly adds getter for the crossRefFk');
-        $this->assertFalse(method_exists('BookClubList', 'getBookClubLists'), 'Object generator correcly adds getter for the crossRefFk');
+        $this->assertTrue(method_exists('BookClubList', 'getBooks'), 'Object generator correctly adds getter for the crossRefFk');
+        $this->assertFalse(method_exists('BookClubList', 'getBookClubLists'), 'Object generator correctly adds getter for the crossRefFk');
@@ -175,2 +175,2 @@
-        $this->assertTrue(method_exists('BookClubList', 'countBooks'), 'Object generator correcly adds counter for the crossRefFk');
-        $this->assertFalse(method_exists('BookClubList', 'countBookClubLists'), 'Object generator correcly adds counter for the crossRefFk');
+        $this->assertTrue(method_exists('BookClubList', 'countBooks'), 'Object generator correctly adds counter for the crossRefFk');
+        $this->assertFalse(method_exists('BookClubList', 'countBookClubLists'), 'Object generator correctly adds counter for the crossRefFk');
@@ -444 +444 @@
-        // Ths `$books` collection has ever been setted to the `$bookClubList1` object.
+        // Ths `$books` collection has ever been set to the `$bookClubList1` object.
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedNestedSetTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedNestedSetTest.php	fixed
@@ -20 +20 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedNestedSetObjectTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedNestedSetObjectTest.php	fixed
@@ -20 +20 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedPeerDoDeleteTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedPeerDoDeleteTest.php	fixed
@@ -19 +19 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedPeerTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedPeerTest.php	fixed
@@ -19 +19 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedPeerDoSelectTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedPeerDoSelectTest.php	fixed
@@ -19 +19 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/generator/config/GeneratorConfigTest.php	original
+++ ./vendor/propel/test/testsuite/generator/config/GeneratorConfigTest.php	fixed
@@ -63 +63 @@
-    public function testGetClassnameOnInexistantProperty()
+    public function testGetClassnameOnInexistentProperty()
--- ./vendor/propel/test/testsuite/misc/CharacterEncodingTest.php	original
+++ ./vendor/propel/test/testsuite/misc/CharacterEncodingTest.php	fixed
@@ -19 +19 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
--- ./vendor/propel/test/testsuite/runtime/util/PropelDateTimeTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/util/PropelDateTimeTest.php	fixed
@@ -92 +92 @@
-        $ser = serialize($pdt);
+        $set = serialize($pdt);
@@ -95 +95 @@
-        $pdt = unserialize($ser);
+        $pdt = unserialize($set);
@@ -111 +111 @@
-        $ser = serialize($pdt);
+        $set = serialize($pdt);
@@ -114 +114 @@
-        $pdt = unserialize($ser);
+        $pdt = unserialize($set);
@@ -130 +130 @@
-        $ser = serialize($pdt);
+        $set = serialize($pdt);
@@ -133 +133 @@
-        $pdt = unserialize($ser);
+        $pdt = unserialize($set);
--- ./vendor/propel/test/testsuite/runtime/util/BasePeerTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/util/BasePeerTest.php	fixed
@@ -46 +46 @@
-        $this->assertFalse(BasePeer::needsSelectAliases($c), 'Empty Criterias dont need aliases');
+        $this->assertFalse(BasePeer::needsSelectAliases($c), 'Empty Criteria dont need aliases');
@@ -51 +51 @@
-        $this->assertFalse(BasePeer::needsSelectAliases($c), 'Criterias with distinct column names dont need aliases');
+        $this->assertFalse(BasePeer::needsSelectAliases($c), 'Criteria with distinct column names dont need aliases');
@@ -55 +55 @@
-        $this->assertFalse(BasePeer::needsSelectAliases($c), 'Criterias with only the columns of a model dont need aliases');
+        $this->assertFalse(BasePeer::needsSelectAliases($c), 'Criteria with only the columns of a model dont need aliases');
@@ -60 +60 @@
-        $this->assertTrue(BasePeer::needsSelectAliases($c), 'Criterias with common column names do need aliases');
+        $this->assertTrue(BasePeer::needsSelectAliases($c), 'Criteria with common column names do need aliases');
@@ -264 +264 @@
-        $this->assertEquals($expectedSQL, $con->getLastExecutedQuery(), 'doDelete() combines conditions in WHERE whith an AND');
+        $this->assertEquals($expectedSQL, $con->getLastExecutedQuery(), 'doDelete() combines conditions in WHERE with an AND');
--- ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectTest.php	original
+++ ./vendor/propel/test/testsuite/generator/builder/om/GeneratedObjectTest.php	fixed
@@ -21 +21 @@
- * The database is relaoded before every test and flushed after every test.  This
+ * The database is reloaded before every test and flushed after every test.  This
@@ -684 +684 @@
-    public function testCopyConcretInheritance()
+    public function testCopyConcertInheritance()
@@ -695 +695 @@
-    public function testDeepCopyConcretInheritance()
+    public function testDeepCopyConcertInheritance()
--- ./vendor/propel/test/testsuite/runtime/validator/ValidatorTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/validator/ValidatorTest.php	fixed
@@ -20 +20 @@
- * The database is relaoded before every test and flushed after every test.	This
+ * The database is reloaded before every test and flushed after every test.	This
--- ./vendor/propel/test/testsuite/runtime/collection/PropelOnDemandCollectionTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/collection/PropelOnDemandCollectionTest.php	fixed
@@ -86 +86 @@
-        // since the code from toArray comes frmo PropelObjectCollection, we'll assume it's good
+        // since the code from toArray comes from PropelObjectCollection, we'll assume it's good
--- ./vendor/propel/test/testsuite/runtime/collection/PropelObjectCollectionWithFixturesTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/collection/PropelObjectCollectionWithFixturesTest.php	fixed
@@ -202 +202 @@
-        $this->assertEquals($count, $this->con->getQueryCount(), 'populateRelation() doesn\'t issue a new query on empy collections');
+        $this->assertEquals($count, $this->con->getQueryCount(), 'populateRelation() doesn\'t issue a new query on empty collections');
--- ./vendor/propel/test/testsuite/runtime/query/SubQueryTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/query/SubQueryTest.php	fixed
@@ -45 +45 @@
-        $this->assertCriteriaTranslation($c, $sql, $params, 'addSubQueryCriteriaInFrom() combines two queries succesfully');
+        $this->assertCriteriaTranslation($c, $sql, $params, 'addSubQueryCriteriaInFrom() combines two queries successfully');
@@ -172 +172 @@
-        $this->assertCriteriaTranslation($c, $sql, $params, 'addSubQueryCriteriaInFrom() combines two queries succesfully');
+        $this->assertCriteriaTranslation($c, $sql, $params, 'addSubQueryCriteriaInFrom() combines two queries successfully');
@@ -206 +206 @@
-        $this->assertCriteriaTranslation($c, $sql, $params, 'addSubQueryCriteriaInFrom() combines two queries succesfully');
+        $this->assertCriteriaTranslation($c, $sql, $params, 'addSubQueryCriteriaInFrom() combines two queries successfully');
--- ./vendor/propel/test/testsuite/runtime/query/CriteriaCombineTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/query/CriteriaCombineTest.php	fixed
@@ -366 +366 @@
-    $this->c->combine(array('cond3', 'cond4'), 'aNd', 'cond34');
+    $this->c->combine(array('cond3', 'cond4'), 'aAnd', 'cond34');
--- ./vendor/propel/test/testsuite/runtime/query/CriteriaTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/query/CriteriaTest.php	fixed
@@ -886 +886 @@
-        $this->assertEquals(1, count($c->getJoins()), "Expected not to have duplciate LJOIN added.");
+        $this->assertEquals(1, count($c->getJoins()), "Expected not to have duplicate LJOIN added.");
--- ./vendor/propel/test/testsuite/runtime/map/TableMapTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/map/TableMapTest.php	fixed
@@ -49,3 +49,3 @@
-      $this->assertTrue(true, 'A table map can be instanciated with no parameters');
-    } catch (Exception $e) {
-      $this->fail('A table map can be instanciated with no parameters');
+      $this->assertTrue(true, 'A table map can be instantiated with no parameters');
+    } catch (Exception $e) {
+      $this->fail('A table map can be instantiated with no parameters');
--- ./vendor/propel/test/testsuite/runtime/om/BaseObjectSerializeTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/om/BaseObjectSerializeTest.php	fixed
@@ -86 +86 @@
-        $author->setFirstName('JAne');
+        $author->setFirstName('JAnd');
--- ./vendor/propel/test/tools/helpers/bookstore/BookstoreTestBase.php	original
+++ ./vendor/propel/test/tools/helpers/bookstore/BookstoreTestBase.php	fixed
@@ -43 +43 @@
-        if ($this->con->isCommitable()) {
+        if ($this->con->isCommittable()) {
--- ./vendor/propel/test/tools/helpers/bookstore/behavior/AddClassBehaviorBuilder.php	original
+++ ./vendor/propel/test/tools/helpers/bookstore/behavior/AddClassBehaviorBuilder.php	fixed
@@ -22 +22 @@
-     * Adds class phpdoc comment and openning of class.
+     * Adds class phpdoc comment and opening of class.
--- ./vendor/propel/test/testsuite/runtime/query/ModelCriteriaTest.php	original
+++ ./vendor/propel/test/testsuite/runtime/query/ModelCriteriaTest.php	fixed
@@ -146 +146 @@
-        $this->assertCriteriaTranslation($c, $sql, $params, 'setModelAlias() allows the definition of the alias after constrution');
+        $this->assertCriteriaTranslation($c, $sql, $params, 'setModelAlias() allows the definition of the alias after construction');
@@ -171 +171 @@
-        $this->assertCriteriaTranslation($c, $sql, $params, 'setModelAlias() allows the definition of a true SQL alias after constrution');
+        $this->assertCriteriaTranslation($c, $sql, $params, 'setModelAlias() allows the definition of a true SQL alias after construction');
@@ -1340 +1340 @@
-        $this->assertCriteriaTranslation($c, $sql, $params, 'withColumn() called repeatedly adds several as colums');
+        $this->assertCriteriaTranslation($c, $sql, $params, 'withColumn() called repeatedly adds several as columns');
@@ -2446 +2446 @@
-            $this->fail('Unexpected exception catched: ' . $e->getMessage());
+            $this->fail('Unexpected exception caught: ' . $e->getMessage());
--- ./vendor/propel/test/etc/xsl/phpunit-noframes.xsl	original
+++ ./vendor/propel/test/etc/xsl/phpunit-noframes.xsl	fixed
@@ -396 +396 @@
-<!-- Style for the error and failure in the tescase template -->
+<!-- Style for the error and failure in the testcase template -->
--- ./vendor/symfony/security/Symfony/Component/Security/CHANGELOG.md	original
+++ ./vendor/symfony/security/Symfony/Component/Security/CHANGELOG.md	fixed
@@ -16 +16 @@
-   `use_referer` is true and the referrer is the `login_path`.
+   `use_referrer` is true and the referrer is the `login_path`.
--- ./vendor/symfony/security/Symfony/Component/Security/Acl/Model/ObjectIdentityInterface.php	original
+++ ./vendor/symfony/security/Symfony/Component/Security/Acl/Model/ObjectIdentityInterface.php	fixed
@@ -23 +23 @@
-     * explicitly, and do not have to rely on referencial equality instead.
+     * explicitly, and do not have to rely on referential equality instead.
--- ./vendor/symfony/security/Symfony/Component/Security/Http/Authentication/DefaultAuthenticationSuccessHandler.php	original
+++ ./vendor/symfony/security/Symfony/Component/Security/Http/Authentication/DefaultAuthenticationSuccessHandler.php	fixed
@@ -49 +49 @@
-            'use_referer'                    => false,
+            'use_referrer'                    => false,
@@ -105 +105 @@
-        if ($this->options['use_referer'] && ($targetUrl = $request->headers->get('Referer')) && $targetUrl !== $this->httpUtils->generateUri($request, $this->options['login_path'])) {
+        if ($this->options['use_referrer'] && ($targetUrl = $request->headers->get('Referrer')) && $targetUrl !== $this->httpUtils->generateUri($request, $this->options['login_path'])) {
--- ./vendor/symfony/http-kernel/Symfony/Component/HttpKernel/KernelEvents.php	original
+++ ./vendor/symfony/http-kernel/Symfony/Component/HttpKernel/KernelEvents.php	fixed
@@ -96 +96 @@
-     * The TERMINATE event occurs once a reponse was sent
+     * The TERMINATE event occurs once a response was sent
--- ./vendor/symfony/http-kernel/Symfony/Component/HttpKernel/Event/PostResponseEvent.php	original
+++ ./vendor/symfony/http-kernel/Symfony/Component/HttpKernel/Event/PostResponseEvent.php	fixed
@@ -64 +64 @@
-     * Returns the reponse for which this event was thrown.
+     * Returns the response for which this event was thrown.
--- ./vendor/symfony/http-kernel/Symfony/Component/HttpKernel/Debug/ContainerAwareTraceableEventDispatcher.php	original
+++ ./vendor/symfony/http-kernel/Symfony/Component/HttpKernel/Debug/ContainerAwareTraceableEventDispatcher.php	fixed
@@ -99 +99 @@
-                // timing informations.
+                // timing information.
@@ -212 +212 @@
-     * @return array Informations about the listener
+     * @return array Information about the listener
--- ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/File/MimeType/MimeTypeExtensionGuesser.php	original
+++ ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/File/MimeType/MimeTypeExtensionGuesser.php	fixed
@@ -53,688 +53,688 @@
-        'application/java-serialized-object' => 'ser',
-        'application/java-vm' => 'class',
-        'application/javascript' => 'js',
-        'application/json' => 'json',
-        'application/lost+xml' => 'lostxml',
-        'application/mac-binhex40' => 'hqx',
-        'application/mac-compactpro' => 'cpt',
-        'application/mads+xml' => 'mads',
-        'application/marc' => 'mrc',
-        'application/marcxml+xml' => 'mrcx',
-        'application/mathematica' => 'ma',
-        'application/mathml+xml' => 'mathml',
-        'application/mbox' => 'mbox',
-        'application/mediaservercontrol+xml' => 'mscml',
-        'application/metalink4+xml' => 'meta4',
-        'application/mets+xml' => 'mets',
-        'application/mods+xml' => 'mods',
-        'application/mp21' => 'm21',
-        'application/mp4' => 'mp4s',
-        'application/msword' => 'doc',
-        'application/mxf' => 'mxf',
-        'application/octet-stream' => 'bin',
-        'application/oda' => 'oda',
-        'application/oebps-package+xml' => 'opf',
-        'application/ogg' => 'ogx',
-        'application/onenote' => 'onetoc',
-        'application/oxps' => 'oxps',
-        'application/patch-ops-error+xml' => 'xer',
-        'application/pdf' => 'pdf',
-        'application/pgp-encrypted' => 'pgp',
-        'application/pgp-signature' => 'asc',
-        'application/pics-rules' => 'prf',
-        'application/pkcs10' => 'p10',
-        'application/pkcs7-mime' => 'p7m',
-        'application/pkcs7-signature' => 'p7s',
-        'application/pkcs8' => 'p8',
-        'application/pkix-attr-cert' => 'ac',
-        'application/pkix-cert' => 'cer',
-        'application/pkix-crl' => 'crl',
-        'application/pkix-pkipath' => 'pkipath',
-        'application/pkixcmp' => 'pki',
-        'application/pls+xml' => 'pls',
-        'application/postscript' => 'ai',
-        'application/prs.cww' => 'cww',
-        'application/pskc+xml' => 'pskcxml',
-        'application/rdf+xml' => 'rdf',
-        'application/reginfo+xml' => 'rif',
-        'application/relax-ng-compact-syntax' => 'rnc',
-        'application/resource-lists+xml' => 'rl',
-        'application/resource-lists-diff+xml' => 'rld',
-        'application/rls-services+xml' => 'rs',
-        'application/rpki-ghostbusters' => 'gbr',
-        'application/rpki-manifest' => 'mft',
-        'application/rpki-roa' => 'roa',
-        'application/rsd+xml' => 'rsd',
-        'application/rss+xml' => 'rss',
-        'application/rtf' => 'rtf',
-        'application/sbml+xml' => 'sbml',
-        'application/scvp-cv-request' => 'scq',
-        'application/scvp-cv-response' => 'scs',
-        'application/scvp-vp-request' => 'spq',
-        'application/scvp-vp-response' => 'spp',
-        'application/sdp' => 'sdp',
-        'application/set-payment-initiation' => 'setpay',
-        'application/set-registration-initiation' => 'setreg',
-        'application/shf+xml' => 'shf',
-        'application/smil+xml' => 'smi',
-        'application/sparql-query' => 'rq',
-        'application/sparql-results+xml' => 'srx',
-        'application/srgs' => 'gram',
-        'application/srgs+xml' => 'grxml',
-        'application/sru+xml' => 'sru',
-        'application/ssml+xml' => 'ssml',
-        'application/tei+xml' => 'tei',
-        'application/thraud+xml' => 'tfi',
-        'application/timestamped-data' => 'tsd',
-        'application/vnd.3gpp.pic-bw-large' => 'plb',
-        'application/vnd.3gpp.pic-bw-small' => 'psb',
-        'application/vnd.3gpp.pic-bw-var' => 'pvb',
-        'application/vnd.3gpp2.tcap' => 'tcap',
-        'application/vnd.3m.post-it-notes' => 'pwn',
-        'application/vnd.accpac.simply.aso' => 'aso',
-        'application/vnd.accpac.simply.imp' => 'imp',
-        'application/vnd.acucobol' => 'acu',
-        'application/vnd.acucorp' => 'atc',
-        'application/vnd.adobe.air-application-installer-package+zip' => 'air',
-        'application/vnd.adobe.fxp' => 'fxp',
-        'application/vnd.adobe.xdp+xml' => 'xdp',
-        'application/vnd.adobe.xfdf' => 'xfdf',
-        'application/vnd.ahead.space' => 'ahead',
-        'application/vnd.airzip.filesecure.azf' => 'azf',
-        'application/vnd.airzip.filesecure.azs' => 'azs',
-        'application/vnd.amazon.ebook' => 'azw',
-        'application/vnd.americandynamics.acc' => 'acc',
-        'application/vnd.amiga.ami' => 'ami',
-        'application/vnd.android.package-archive' => 'apk',
-        'application/vnd.anser-web-certificate-issue-initiation' => 'cii',
-        'application/vnd.anser-web-funds-transfer-initiation' => 'fti',
-        'application/vnd.antix.game-component' => 'atx',
-        'application/vnd.apple.installer+xml' => 'mpkg',
-        'application/vnd.apple.mpegurl' => 'm3u8',
-        'application/vnd.aristanetworks.swi' => 'swi',
-        'application/vnd.astraea-software.iota' => 'iota',
-        'application/vnd.audiograph' => 'aep',
-        'application/vnd.blueice.multipass' => 'mpm',
-        'application/vnd.bmi' => 'bmi',
-        'application/vnd.businessobjects' => 'rep',
-        'application/vnd.chemdraw+xml' => 'cdxml',
-        'application/vnd.chipnuts.karaoke-mmd' => 'mmd',
-        'application/vnd.cinderella' => 'cdy',
-        'application/vnd.claymore' => 'cla',
-        'application/vnd.cloanto.rp9' => 'rp9',
-        'application/vnd.clonk.c4group' => 'c4g',
-        'application/vnd.cluetrust.cartomobile-config' => 'c11amc',
-        'application/vnd.cluetrust.cartomobile-config-pkg' => 'c11amz',
-        'application/vnd.commonspace' => 'csp',
-        'application/vnd.contact.cmsg' => 'cdbcmsg',
-        'application/vnd.cosmocaller' => 'cmc',
-        'application/vnd.crick.clicker' => 'clkx',
-        'application/vnd.crick.clicker.keyboard' => 'clkk',
-        'application/vnd.crick.clicker.palette' => 'clkp',
-        'application/vnd.crick.clicker.template' => 'clkt',
-        'application/vnd.crick.clicker.wordbank' => 'clkw',
-        'application/vnd.criticaltools.wbs+xml' => 'wbs',
-        'application/vnd.ctc-posml' => 'pml',
-        'application/vnd.cups-ppd' => 'ppd',
-        'application/vnd.curl.car' => 'car',
-        'application/vnd.curl.pcurl' => 'pcurl',
-        'application/vnd.data-vision.rdz' => 'rdz',
-        'application/vnd.dece.data' => 'uvf',
-        'application/vnd.dece.ttml+xml' => 'uvt',
-        'application/vnd.dece.unspecified' => 'uvx',
-        'application/vnd.dece.zip' => 'uvz',
-        'application/vnd.denovo.fcselayout-link' => 'fe_launch',
-        'application/vnd.dna' => 'dna',
-        'application/vnd.dolby.mlp' => 'mlp',
-        'application/vnd.dpgraph' => 'dpg',
-        'application/vnd.dreamfactory' => 'dfac',
-        'application/vnd.dvb.ait' => 'ait',
-        'application/vnd.dvb.service' => 'svc',
-        'application/vnd.dynageo' => 'geo',
-        'application/vnd.ecowin.chart' => 'mag',
-        'application/vnd.enliven' => 'nml',
-        'application/vnd.epson.esf' => 'esf',
-        'application/vnd.epson.msf' => 'msf',
-        'application/vnd.epson.quickanime' => 'qam',
-        'application/vnd.epson.salt' => 'slt',
-        'application/vnd.epson.ssf' => 'ssf',
-        'application/vnd.eszigno3+xml' => 'es3',
-        'application/vnd.ezpix-album' => 'ez2',
-        'application/vnd.ezpix-package' => 'ez3',
-        'application/vnd.fdf' => 'fdf',
-        'application/vnd.fdsn.mseed' => 'mseed',
-        'application/vnd.fdsn.seed' => 'seed',
-        'application/vnd.flographit' => 'gph',
-        'application/vnd.fluxtime.clip' => 'ftc',
-        'application/vnd.framemaker' => 'fm',
-        'application/vnd.frogans.fnc' => 'fnc',
-        'application/vnd.frogans.ltf' => 'ltf',
-        'application/vnd.fsc.weblaunch' => 'fsc',
-        'application/vnd.fujitsu.oasys' => 'oas',
-        'application/vnd.fujitsu.oasys2' => 'oa2',
-        'application/vnd.fujitsu.oasys3' => 'oa3',
-        'application/vnd.fujitsu.oasysgp' => 'fg5',
-        'application/vnd.fujitsu.oasysprs' => 'bh2',
-        'application/vnd.fujixerox.ddd' => 'ddd',
-        'application/vnd.fujixerox.docuworks' => 'xdw',
-        'application/vnd.fujixerox.docuworks.binder' => 'xbd',
-        'application/vnd.fuzzysheet' => 'fzs',
-        'application/vnd.genomatix.tuxedo' => 'txd',
-        'application/vnd.geogebra.file' => 'ggb',
-        'application/vnd.geogebra.tool' => 'ggt',
-        'application/vnd.geometry-explorer' => 'gex',
-        'application/vnd.geonext' => 'gxt',
-        'application/vnd.geoplan' => 'g2w',
-        'application/vnd.geospace' => 'g3w',
-        'application/vnd.gmx' => 'gmx',
-        'application/vnd.google-earth.kml+xml' => 'kml',
-        'application/vnd.google-earth.kmz' => 'kmz',
-        'application/vnd.grafeq' => 'gqf',
-        'application/vnd.groove-account' => 'gac',
-        'application/vnd.groove-help' => 'ghf',
-        'application/vnd.groove-identity-message' => 'gim',
-        'application/vnd.groove-injector' => 'grv',
-        'application/vnd.groove-tool-message' => 'gtm',
-        'application/vnd.groove-tool-template' => 'tpl',
-        'application/vnd.groove-vcard' => 'vcg',
-        'application/vnd.hal+xml' => 'hal',
-        'application/vnd.handheld-entertainment+xml' => 'zmm',
-        'application/vnd.hbci' => 'hbci',
-        'application/vnd.hhe.lesson-player' => 'les',
-        'application/vnd.hp-hpgl' => 'hpgl',
-        'application/vnd.hp-hpid' => 'hpid',
-        'application/vnd.hp-hps' => 'hps',
-        'application/vnd.hp-jlyt' => 'jlt',
-        'application/vnd.hp-pcl' => 'pcl',
-        'application/vnd.hp-pclxl' => 'pclxl',
-        'application/vnd.hydrostatix.sof-data' => 'sfd-hdstx',
-        'application/vnd.hzn-3d-crossword' => 'x3d',
-        'application/vnd.ibm.minipay' => 'mpy',
-        'application/vnd.ibm.modcap' => 'afp',
-        'application/vnd.ibm.rights-management' => 'irm',
-        'application/vnd.ibm.secure-container' => 'sc',
-        'application/vnd.iccprofile' => 'icc',
-        'application/vnd.igloader' => 'igl',
-        'application/vnd.immervision-ivp' => 'ivp',
-        'application/vnd.immervision-ivu' => 'ivu',
-        'application/vnd.insors.igm' => 'igm',
-        'application/vnd.intercon.formnet' => 'xpw',
-        'application/vnd.intergeo' => 'i2g',
-        'application/vnd.intu.qbo' => 'qbo',
-        'application/vnd.intu.qfx' => 'qfx',
-        'application/vnd.ipunplugged.rcprofile' => 'rcprofile',
-        'application/vnd.irepository.package+xml' => 'irp',
-        'application/vnd.is-xpr' => 'xpr',
-        'application/vnd.isac.fcs' => 'fcs',
-        'application/vnd.jam' => 'jam',
-        'application/vnd.jcp.javame.midlet-rms' => 'rms',
-        'application/vnd.jisp' => 'jisp',
-        'application/vnd.joost.joda-archive' => 'joda',
-        'application/vnd.kahootz' => 'ktz',
-        'application/vnd.kde.karbon' => 'karbon',
-        'application/vnd.kde.kchart' => 'chrt',
-        'application/vnd.kde.kformula' => 'kfo',
-        'application/vnd.kde.kivio' => 'flw',
-        'application/vnd.kde.kontour' => 'kon',
-        'application/vnd.kde.kpresenter' => 'kpr',
-        'application/vnd.kde.kspread' => 'ksp',
-        'application/vnd.kde.kword' => 'kwd',
-        'application/vnd.kenameaapp' => 'htke',
-        'application/vnd.kidspiration' => 'kia',
-        'application/vnd.kinar' => 'kne',
-        'application/vnd.koan' => 'skp',
-        'application/vnd.kodak-descriptor' => 'sse',
-        'application/vnd.las.las+xml' => 'lasxml',
-        'application/vnd.llamagraphics.life-balance.desktop' => 'lbd',
-        'application/vnd.llamagraphics.life-balance.exchange+xml' => 'lbe',
-        'application/vnd.lotus-1-2-3' => '123',
-        'application/vnd.lotus-approach' => 'apr',
-        'application/vnd.lotus-freelance' => 'pre',
-        'application/vnd.lotus-notes' => 'nsf',
-        'application/vnd.lotus-organizer' => 'org',
-        'application/vnd.lotus-screencam' => 'scm',
-        'application/vnd.lotus-wordpro' => 'lwp',
-        'application/vnd.macports.portpkg' => 'portpkg',
-        'application/vnd.mcd' => 'mcd',
-        'application/vnd.medcalcdata' => 'mc1',
-        'application/vnd.mediastation.cdkey' => 'cdkey',
-        'application/vnd.mfer' => 'mwf',
-        'application/vnd.mfmp' => 'mfm',
-        'application/vnd.micrografx.flo' => 'flo',
-        'application/vnd.micrografx.igx' => 'igx',
-        'application/vnd.mif' => 'mif',
-        'application/vnd.mobius.daf' => 'daf',
-        'application/vnd.mobius.dis' => 'dis',
-        'application/vnd.mobius.mbk' => 'mbk',
-        'application/vnd.mobius.mqy' => 'mqy',
-        'application/vnd.mobius.msl' => 'msl',
-        'application/vnd.mobius.plc' => 'plc',
-        'application/vnd.mobius.txf' => 'txf',
-        'application/vnd.mophun.application' => 'mpn',
-        'application/vnd.mophun.certificate' => 'mpc',
-        'application/vnd.mozilla.xul+xml' => 'xul',
-        'application/vnd.ms-artgalry' => 'cil',
-        'application/vnd.ms-cab-compressed' => 'cab',
-        'application/vnd.ms-excel' => 'xls',
-        'application/vnd.ms-excel.addin.macroenabled.12' => 'xlam',
-        'application/vnd.ms-excel.sheet.binary.macroenabled.12' => 'xlsb',
-        'application/vnd.ms-excel.sheet.macroenabled.12' => 'xlsm',
-        'application/vnd.ms-excel.template.macroenabled.12' => 'xltm',
-        'application/vnd.ms-fontobject' => 'eot',
-        'application/vnd.ms-htmlhelp' => 'chm',
-        'application/vnd.ms-ims' => 'ims',
-        'application/vnd.ms-lrm' => 'lrm',
-        'application/vnd.ms-officetheme' => 'thmx',
-        'application/vnd.ms-pki.seccat' => 'cat',
-        'application/vnd.ms-pki.stl' => 'stl',
-        'application/vnd.ms-powerpoint' => 'ppt',
-        'application/vnd.ms-powerpoint.addin.macroenabled.12' => 'ppam',
-        'application/vnd.ms-powerpoint.presentation.macroenabled.12' => 'pptm',
-        'application/vnd.ms-powerpoint.slide.macroenabled.12' => 'sldm',
-        'application/vnd.ms-powerpoint.slideshow.macroenabled.12' => 'ppsm',
-        'application/vnd.ms-powerpoint.template.macroenabled.12' => 'potm',
-        'application/vnd.ms-project' => 'mpp',
-        'application/vnd.ms-word.document.macroenabled.12' => 'docm',
-        'application/vnd.ms-word.template.macroenabled.12' => 'dotm',
-        'application/vnd.ms-works' => 'wps',
-        'application/vnd.ms-wpl' => 'wpl',
-        'application/vnd.ms-xpsdocument' => 'xps',
-        'application/vnd.mseq' => 'mseq',
-        'application/vnd.musician' => 'mus',
-        'application/vnd.muvee.style' => 'msty',
-        'application/vnd.mynfc' => 'taglet',
-        'application/vnd.neurolanguage.nlu' => 'nlu',
-        'application/vnd.noblenet-directory' => 'nnd',
-        'application/vnd.noblenet-sealer' => 'nns',
-        'application/vnd.noblenet-web' => 'nnw',
-        'application/vnd.nokia.n-gage.data' => 'ngdat',
-        'application/vnd.nokia.n-gage.symbian.install' => 'n-gage',
-        'application/vnd.nokia.radio-preset' => 'rpst',
-        'application/vnd.nokia.radio-presets' => 'rpss',
-        'application/vnd.novadigm.edm' => 'edm',
-        'application/vnd.novadigm.edx' => 'edx',
-        'application/vnd.novadigm.ext' => 'ext',
-        'application/vnd.oasis.opendocument.chart' => 'odc',
-        'application/vnd.oasis.opendocument.chart-template' => 'otc',
-        'application/vnd.oasis.opendocument.database' => 'odb',
-        'application/vnd.oasis.opendocument.formula' => 'odf',
-        'application/vnd.oasis.opendocument.formula-template' => 'odft',
-        'application/vnd.oasis.opendocument.graphics' => 'odg',
-        'application/vnd.oasis.opendocument.graphics-template' => 'otg',
-        'application/vnd.oasis.opendocument.image' => 'odi',
-        'application/vnd.oasis.opendocument.image-template' => 'oti',
-        'application/vnd.oasis.opendocument.presentation' => 'odp',
-        'application/vnd.oasis.opendocument.presentation-template' => 'otp',
-        'application/vnd.oasis.opendocument.spreadsheet' => 'ods',
-        'application/vnd.oasis.opendocument.spreadsheet-template' => 'ots',
-        'application/vnd.oasis.opendocument.text' => 'odt',
-        'application/vnd.oasis.opendocument.text-master' => 'odm',
-        'application/vnd.oasis.opendocument.text-template' => 'ott',
-        'application/vnd.oasis.opendocument.text-web' => 'oth',
-        'application/vnd.olpc-sugar' => 'xo',
-        'application/vnd.oma.dd2+xml' => 'dd2',
-        'application/vnd.openofficeorg.extension' => 'oxt',
-        'application/vnd.openxmlformats-officedocument.presentationml.presentation' => 'pptx',
-        'application/vnd.openxmlformats-officedocument.presentationml.slide' => 'sldx',
-        'application/vnd.openxmlformats-officedocument.presentationml.slideshow' => 'ppsx',
-        'application/vnd.openxmlformats-officedocument.presentationml.template' => 'potx',
-        'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet' => 'xlsx',
-        'application/vnd.openxmlformats-officedocument.spreadsheetml.template' => 'xltx',
-        'application/vnd.openxmlformats-officedocument.wordprocessingml.document' => 'docx',
-        'application/vnd.openxmlformats-officedocument.wordprocessingml.template' => 'dotx',
-        'application/vnd.osgeo.mapguide.package' => 'mgp',
-        'application/vnd.osgi.dp' => 'dp',
-        'application/vnd.palm' => 'pdb',
-        'application/vnd.pawaafile' => 'paw',
-        'application/vnd.pg.format' => 'str',
-        'application/vnd.pg.osasli' => 'ei6',
-        'application/vnd.picsel' => 'efif',
-        'application/vnd.pmi.widget' => 'wg',
-        'application/vnd.pocketlearn' => 'plf',
-        'application/vnd.powerbuilder6' => 'pbd',
-        'application/vnd.previewsystems.box' => 'box',
-        'application/vnd.proteus.magazine' => 'mgz',
-        'application/vnd.publishare-delta-tree' => 'qps',
-        'application/vnd.pvi.ptid1' => 'ptid',
-        'application/vnd.quark.quarkxpress' => 'qxd',
-        'application/vnd.realvnc.bed' => 'bed',
-        'application/vnd.recordare.musicxml' => 'mxl',
-        'application/vnd.recordare.musicxml+xml' => 'musicxml',
-        'application/vnd.rig.cryptonote' => 'cryptonote',
-        'application/vnd.rim.cod' => 'cod',
-        'application/vnd.rn-realmedia' => 'rm',
-        'application/vnd.route66.link66+xml' => 'link66',
-        'application/vnd.sailingtracker.track' => 'st',
-        'application/vnd.seemail' => 'see',
-        'application/vnd.sema' => 'sema',
-        'application/vnd.semd' => 'semd',
-        'application/vnd.semf' => 'semf',
-        'application/vnd.shana.informed.formdata' => 'ifm',
-        'application/vnd.shana.informed.formtemplate' => 'itp',
-        'application/vnd.shana.informed.interchange' => 'iif',
-        'application/vnd.shana.informed.package' => 'ipk',
-        'application/vnd.simtech-mindmapper' => 'twd',
-        'application/vnd.smaf' => 'mmf',
-        'application/vnd.smart.teacher' => 'teacher',
-        'application/vnd.solent.sdkm+xml' => 'sdkm',
-        'application/vnd.spotfire.dxp' => 'dxp',
-        'application/vnd.spotfire.sfs' => 'sfs',
-        'application/vnd.stardivision.calc' => 'sdc',
-        'application/vnd.stardivision.draw' => 'sda',
-        'application/vnd.stardivision.impress' => 'sdd',
-        'application/vnd.stardivision.math' => 'smf',
-        'application/vnd.stardivision.writer' => 'sdw',
-        'application/vnd.stardivision.writer-global' => 'sgl',
-        'application/vnd.stepmania.package' => 'smzip',
-        'application/vnd.stepmania.stepchart' => 'sm',
-        'application/vnd.sun.xml.calc' => 'sxc',
-        'application/vnd.sun.xml.calc.template' => 'stc',
-        'application/vnd.sun.xml.draw' => 'sxd',
-        'application/vnd.sun.xml.draw.template' => 'std',
-        'application/vnd.sun.xml.impress' => 'sxi',
-        'application/vnd.sun.xml.impress.template' => 'sti',
-        'application/vnd.sun.xml.math' => 'sxm',
-        'application/vnd.sun.xml.writer' => 'sxw',
-        'application/vnd.sun.xml.writer.global' => 'sxg',
-        'application/vnd.sun.xml.writer.template' => 'stw',
-        'application/vnd.sus-calendar' => 'sus',
-        'application/vnd.svd' => 'svd',
-        'application/vnd.symbian.install' => 'sis',
-        'application/vnd.syncml+xml' => 'xsm',
-        'application/vnd.syncml.dm+wbxml' => 'bdm',
-        'application/vnd.syncml.dm+xml' => 'xdm',
-        'application/vnd.tao.intent-module-archive' => 'tao',
-        'application/vnd.tcpdump.pcap' => 'pcap',
-        'application/vnd.tmobile-livetv' => 'tmo',
-        'application/vnd.trid.tpt' => 'tpt',
-        'application/vnd.triscape.mxs' => 'mxs',
-        'application/vnd.trueapp' => 'tra',
-        'application/vnd.ufdl' => 'ufd',
-        'application/vnd.uiq.theme' => 'utz',
-        'application/vnd.umajin' => 'umj',
-        'application/vnd.unity' => 'unityweb',
-        'application/vnd.uoml+xml' => 'uoml',
-        'application/vnd.vcx' => 'vcx',
-        'application/vnd.visio' => 'vsd',
-        'application/vnd.visionary' => 'vis',
-        'application/vnd.vsf' => 'vsf',
-        'application/vnd.wap.wbxml' => 'wbxml',
-        'application/vnd.wap.wmlc' => 'wmlc',
-        'application/vnd.wap.wmlscriptc' => 'wmlsc',
-        'application/vnd.webturbo' => 'wtb',
-        'application/vnd.wolfram.player' => 'nbp',
-        'application/vnd.wordperfect' => 'wpd',
-        'application/vnd.wqd' => 'wqd',
-        'application/vnd.wt.stf' => 'stf',
-        'application/vnd.xara' => 'xar',
-        'application/vnd.xfdl' => 'xfdl',
-        'application/vnd.yamaha.hv-dic' => 'hvd',
-        'application/vnd.yamaha.hv-script' => 'hvs',
-        'application/vnd.yamaha.hv-voice' => 'hvp',
-        'application/vnd.yamaha.openscoreformat' => 'osf',
-        'application/vnd.yamaha.openscoreformat.osfpvg+xml' => 'osfpvg',
-        'application/vnd.yamaha.smaf-audio' => 'saf',
-        'application/vnd.yamaha.smaf-phrase' => 'spf',
-        'application/vnd.yellowriver-custom-menu' => 'cmp',
-        'application/vnd.zul' => 'zir',
-        'application/vnd.zzazz.deck+xml' => 'zaz',
-        'application/voicexml+xml' => 'vxml',
-        'application/widget' => 'wgt',
-        'application/winhlp' => 'hlp',
-        'application/wsdl+xml' => 'wsdl',
-        'application/wspolicy+xml' => 'wspolicy',
-        'application/x-7z-compressed' => '7z',
-        'application/x-abiword' => 'abw',
-        'application/x-ace-compressed' => 'ace',
-        'application/x-authorware-bin' => 'aab',
-        'application/x-authorware-map' => 'aam',
-        'application/x-authorware-seg' => 'aas',
-        'application/x-bcpio' => 'bcpio',
-        'application/x-bittorrent' => 'torrent',
-        'application/x-bzip' => 'bz',
-        'application/x-bzip2' => 'bz2',
-        'application/x-cdlink' => 'vcd',
-        'application/x-chat' => 'chat',
-        'application/x-chess-pgn' => 'pgn',
-        'application/x-cpio' => 'cpio',
-        'application/x-csh' => 'csh',
-        'application/x-debian-package' => 'deb',
-        'application/x-director' => 'dir',
-        'application/x-doom' => 'wad',
-        'application/x-dtbncx+xml' => 'ncx',
-        'application/x-dtbook+xml' => 'dtb',
-        'application/x-dtbresource+xml' => 'res',
-        'application/x-dvi' => 'dvi',
-        'application/x-font-bdf' => 'bdf',
-        'application/x-font-ghostscript' => 'gsf',
-        'application/x-font-linux-psf' => 'psf',
-        'application/x-font-otf' => 'otf',
-        'application/x-font-pcf' => 'pcf',
-        'application/x-font-snf' => 'snf',
-        'application/x-font-ttf' => 'ttf',
-        'application/x-font-type1' => 'pfa',
-        'application/x-font-woff' => 'woff',
-        'application/x-futuresplash' => 'spl',
-        'application/x-gnumeric' => 'gnumeric',
-        'application/x-gtar' => 'gtar',
-        'application/x-hdf' => 'hdf',
-        'application/x-java-jnlp-file' => 'jnlp',
-        'application/x-latex' => 'latex',
-        'application/x-mobipocket-ebook' => 'prc',
-        'application/x-ms-application' => 'application',
-        'application/x-ms-wmd' => 'wmd',
-        'application/x-ms-wmz' => 'wmz',
-        'application/x-ms-xbap' => 'xbap',
-        'application/x-msaccess' => 'mdb',
-        'application/x-msbinder' => 'obd',
-        'application/x-mscardfile' => 'crd',
-        'application/x-msclip' => 'clp',
-        'application/x-msdownload' => 'exe',
-        'application/x-msmediaview' => 'mvb',
-        'application/x-msmetafile' => 'wmf',
-        'application/x-msmoney' => 'mny',
-        'application/x-mspublisher' => 'pub',
-        'application/x-msschedule' => 'scd',
-        'application/x-msterminal' => 'trm',
-        'application/x-mswrite' => 'wri',
-        'application/x-netcdf' => 'nc',
-        'application/x-pkcs12' => 'p12',
-        'application/x-pkcs7-certificates' => 'p7b',
-        'application/x-pkcs7-certreqresp' => 'p7r',
-        'application/x-rar-compressed' => 'rar',
-        'application/x-rar' => 'rar',
-        'application/x-sh' => 'sh',
-        'application/x-shar' => 'shar',
-        'application/x-shockwave-flash' => 'swf',
-        'application/x-silverlight-app' => 'xap',
-        'application/x-stuffit' => 'sit',
-        'application/x-stuffitx' => 'sitx',
-        'application/x-sv4cpio' => 'sv4cpio',
-        'application/x-sv4crc' => 'sv4crc',
-        'application/x-tar' => 'tar',
-        'application/x-tcl' => 'tcl',
-        'application/x-tex' => 'tex',
-        'application/x-tex-tfm' => 'tfm',
-        'application/x-texinfo' => 'texinfo',
-        'application/x-ustar' => 'ustar',
-        'application/x-wais-source' => 'src',
-        'application/x-x509-ca-cert' => 'der',
-        'application/x-xfig' => 'fig',
-        'application/x-xpinstall' => 'xpi',
-        'application/xcap-diff+xml' => 'xdf',
-        'application/xenc+xml' => 'xenc',
-        'application/xhtml+xml' => 'xhtml',
-        'application/xml' => 'xml',
-        'application/xml-dtd' => 'dtd',
-        'application/xop+xml' => 'xop',
-        'application/xslt+xml' => 'xslt',
-        'application/xspf+xml' => 'xspf',
-        'application/xv+xml' => 'mxml',
-        'application/yang' => 'yang',
-        'application/yin+xml' => 'yin',
-        'application/zip' => 'zip',
-        'audio/adpcm' => 'adp',
-        'audio/basic' => 'au',
-        'audio/midi' => 'mid',
-        'audio/mp4' => 'mp4a',
-        'audio/mpeg' => 'mpga',
-        'audio/ogg' => 'oga',
-        'audio/vnd.dece.audio' => 'uva',
-        'audio/vnd.digital-winds' => 'eol',
-        'audio/vnd.dra' => 'dra',
-        'audio/vnd.dts' => 'dts',
-        'audio/vnd.dts.hd' => 'dtshd',
-        'audio/vnd.lucent.voice' => 'lvp',
-        'audio/vnd.ms-playready.media.pya' => 'pya',
-        'audio/vnd.nuera.ecelp4800' => 'ecelp4800',
-        'audio/vnd.nuera.ecelp7470' => 'ecelp7470',
-        'audio/vnd.nuera.ecelp9600' => 'ecelp9600',
-        'audio/vnd.rip' => 'rip',
-        'audio/webm' => 'weba',
-        'audio/x-aac' => 'aac',
-        'audio/x-aiff' => 'aif',
-        'audio/x-mpegurl' => 'm3u',
-        'audio/x-ms-wax' => 'wax',
-        'audio/x-ms-wma' => 'wma',
-        'audio/x-pn-realaudio' => 'ram',
-        'audio/x-pn-realaudio-plugin' => 'rmp',
-        'audio/x-wav' => 'wav',
-        'chemical/x-cdx' => 'cdx',
-        'chemical/x-cif' => 'cif',
-        'chemical/x-cmdf' => 'cmdf',
-        'chemical/x-cml' => 'cml',
-        'chemical/x-csml' => 'csml',
-        'chemical/x-xyz' => 'xyz',
-        'image/bmp' => 'bmp',
-        'image/cgm' => 'cgm',
-        'image/g3fax' => 'g3',
-        'image/gif' => 'gif',
-        'image/ief' => 'ief',
-        'image/jpeg' => 'jpeg',
-        'image/ktx' => 'ktx',
-        'image/png' => 'png',
-        'image/prs.btif' => 'btif',
-        'image/svg+xml' => 'svg',
-        'image/tiff' => 'tiff',
-        'image/vnd.adobe.photoshop' => 'psd',
-        'image/vnd.dece.graphic' => 'uvi',
-        'image/vnd.dvb.subtitle' => 'sub',
-        'image/vnd.djvu' => 'djvu',
-        'image/vnd.dwg' => 'dwg',
-        'image/vnd.dxf' => 'dxf',
-        'image/vnd.fastbidsheet' => 'fbs',
-        'image/vnd.fpx' => 'fpx',
-        'image/vnd.fst' => 'fst',
-        'image/vnd.fujixerox.edmics-mmr' => 'mmr',
-        'image/vnd.fujixerox.edmics-rlc' => 'rlc',
-        'image/vnd.ms-modi' => 'mdi',
-        'image/vnd.net-fpx' => 'npx',
-        'image/vnd.wap.wbmp' => 'wbmp',
-        'image/vnd.xiff' => 'xif',
-        'image/webp' => 'webp',
-        'image/x-cmu-raster' => 'ras',
-        'image/x-cmx' => 'cmx',
-        'image/x-freehand' => 'fh',
-        'image/x-icon' => 'ico',
-        'image/x-pcx' => 'pcx',
-        'image/x-pict' => 'pic',
-        'image/x-portable-anymap' => 'pnm',
-        'image/x-portable-bitmap' => 'pbm',
-        'image/x-portable-graymap' => 'pgm',
-        'image/x-portable-pixmap' => 'ppm',
-        'image/x-rgb' => 'rgb',
-        'image/x-xbitmap' => 'xbm',
-        'image/x-xpixmap' => 'xpm',
-        'image/x-xwindowdump' => 'xwd',
-        'message/rfc822' => 'eml',
-        'model/iges' => 'igs',
-        'model/mesh' => 'msh',
-        'model/vnd.collada+xml' => 'dae',
-        'model/vnd.dwf' => 'dwf',
-        'model/vnd.gdl' => 'gdl',
-        'model/vnd.gtw' => 'gtw',
-        'model/vnd.mts' => 'mts',
-        'model/vnd.vtu' => 'vtu',
-        'model/vrml' => 'wrl',
-        'text/calendar' => 'ics',
-        'text/css' => 'css',
-        'text/csv' => 'csv',
-        'text/html' => 'html',
-        'text/n3' => 'n3',
-        'text/plain' => 'txt',
-        'text/prs.lines.tag' => 'dsc',
-        'text/richtext' => 'rtx',
-        'text/sgml' => 'sgml',
-        'text/tab-separated-values' => 'tsv',
-        'text/troff' => 't',
-        'text/turtle' => 'ttl',
-        'text/uri-list' => 'uri',
-        'text/vcard' => 'vcard',
-        'text/vnd.curl' => 'curl',
-        'text/vnd.curl.dcurl' => 'dcurl',
-        'text/vnd.curl.scurl' => 'scurl',
-        'text/vnd.curl.mcurl' => 'mcurl',
-        'text/vnd.dvb.subtitle' => 'sub',
-        'text/vnd.fly' => 'fly',
-        'text/vnd.fmi.flexstor' => 'flx',
-        'text/vnd.graphviz' => 'gv',
-        'text/vnd.in3d.3dml' => '3dml',
-        'text/vnd.in3d.spot' => 'spot',
-        'text/vnd.sun.j2me.app-descriptor' => 'jad',
-        'text/vnd.wap.wml' => 'wml',
-        'text/vnd.wap.wmlscript' => 'wmls',
-        'text/x-asm' => 's',
-        'text/x-c' => 'c',
-        'text/x-fortran' => 'f',
-        'text/x-pascal' => 'p',
-        'text/x-java-source' => 'java',
-        'text/x-setext' => 'etx',
-        'text/x-uuencode' => 'uu',
-        'text/x-vcalendar' => 'vcs',
-        'text/x-vcard' => 'vcf',
-        'video/3gpp' => '3gp',
-        'video/3gpp2' => '3g2',
-        'video/h261' => 'h261',
-        'video/h263' => 'h263',
-        'video/h264' => 'h264',
-        'video/jpeg' => 'jpgv',
-        'video/jpm' => 'jpm',
-        'video/mj2' => 'mj2',
-        'video/mp4' => 'mp4',
-        'video/mpeg' => 'mpeg',
-        'video/ogg' => 'ogv',
-        'video/quicktime' => 'qt',
-        'video/vnd.dece.hd' => 'uvh',
-        'video/vnd.dece.mobile' => 'uvm',
-        'video/vnd.dece.pd' => 'uvp',
-        'video/vnd.dece.sd' => 'uvs',
-        'video/vnd.dece.video' => 'uvv',
-        'video/vnd.dvb.file' => 'dvb',
-        'video/vnd.fvt' => 'fvt',
-        'video/vnd.mpegurl' => 'mxu',
-        'video/vnd.ms-playready.media.pyv' => 'pyv',
-        'video/vnd.uvvu.mp4' => 'uvu',
-        'video/vnd.vivo' => 'viv',
-        'video/webm' => 'webm',
-        'video/x-f4v' => 'f4v',
-        'video/x-fli' => 'fli',
-        'video/x-flv' => 'flv',
-        'video/x-m4v' => 'm4v',
-        'video/x-ms-asf' => 'asf',
-        'video/x-ms-wm' => 'wm',
-        'video/x-ms-wmv' => 'wmv',
-        'video/x-ms-wmx' => 'wmx',
-        'video/x-ms-wvx' => 'wvx',
-        'video/x-msvideo' => 'avi',
-        'video/x-sgi-movie' => 'movie',
-        'x-conference/x-cooltalk' => 'ice',
-    );
-
-    /**
-     * {@inheritdoc}
-     */
-    public function guess($mimeType)
-    {
-        return isset($this->defaultExtensions[$mimeType]) ? $this->defaultExtensions[$mimeType] : null;
-    }
-}
+        'application/java-serialized-object' => 'set',
+        'application/java-vm' => 'class',
+        'application/javascript' => 'js',
+        'application/json' => 'json',
+        'application/lost+xml' => 'lostxml',
+        'application/mac-binhex40' => 'hqx',
+        'application/mac-compactpro' => 'cpt',
+        'application/mads+xml' => 'mads',
+        'application/marc' => 'mrc',
+        'application/marcxml+xml' => 'mrcx',
+        'application/mathematica' => 'ma',
+        'application/mathml+xml' => 'mathml',
+        'application/mbox' => 'mbox',
+        'application/mediaservercontrol+xml' => 'mscml',
+        'application/metalink4+xml' => 'meta4',
+        'application/mets+xml' => 'mets',
+        'application/mods+xml' => 'mods',
+        'application/mp21' => 'm21',
+        'application/mp4' => 'mp4s',
+        'application/msword' => 'doc',
+        'application/mxf' => 'mxf',
+        'application/octet-stream' => 'bin',
+        'application/oda' => 'oda',
+        'application/oebps-package+xml' => 'opf',
+        'application/ogg' => 'ogx',
+        'application/onenote' => 'onetoc',
+        'application/oxps' => 'oxps',
+        'application/patch-ops-error+xml' => 'xer',
+        'application/pdf' => 'pdf',
+        'application/pgp-encrypted' => 'pgp',
+        'application/pgp-signature' => 'asc',
+        'application/pics-rules' => 'prf',
+        'application/pkcs10' => 'p10',
+        'application/pkcs7-mime' => 'p7m',
+        'application/pkcs7-signature' => 'p7s',
+        'application/pkcs8' => 'p8',
+        'application/pkix-attr-cert' => 'ac',
+        'application/pkix-cert' => 'cer',
+        'application/pkix-crl' => 'crl',
+        'application/pkix-pkipath' => 'pkipath',
+        'application/pkixcmp' => 'pki',
+        'application/pls+xml' => 'pls',
+        'application/postscript' => 'ai',
+        'application/prs.cww' => 'cww',
+        'application/pskc+xml' => 'pskcxml',
+        'application/rdf+xml' => 'rdf',
+        'application/reginfo+xml' => 'rif',
+        'application/relax-ng-compact-syntax' => 'rnc',
+        'application/resource-lists+xml' => 'rl',
+        'application/resource-lists-diff+xml' => 'rld',
+        'application/rls-services+xml' => 'rs',
+        'application/rpki-ghostbusters' => 'gbr',
+        'application/rpki-manifest' => 'mft',
+        'application/rpki-roa' => 'roa',
+        'application/rsd+xml' => 'rsd',
+        'application/rss+xml' => 'rss',
+        'application/rtf' => 'rtf',
+        'application/sbml+xml' => 'sbml',
+        'application/scvp-cv-request' => 'scq',
+        'application/scvp-cv-response' => 'scs',
+        'application/scvp-vp-request' => 'spq',
+        'application/scvp-vp-response' => 'spp',
+        'application/sdp' => 'sdp',
+        'application/set-payment-initiation' => 'setpay',
+        'application/set-registration-initiation' => 'setreg',
+        'application/shf+xml' => 'shf',
+        'application/smil+xml' => 'smi',
+        'application/sparql-query' => 'rq',
+        'application/sparql-results+xml' => 'srx',
+        'application/srgs' => 'gram',
+        'application/srgs+xml' => 'grxml',
+        'application/sru+xml' => 'sru',
+        'application/ssml+xml' => 'ssml',
+        'application/tei+xml' => 'tei',
+        'application/thraud+xml' => 'tfi',
+        'application/timestamped-data' => 'tsd',
+        'application/vnd.3gpp.pic-bw-large' => 'plb',
+        'application/vnd.3gpp.pic-bw-small' => 'psb',
+        'application/vnd.3gpp.pic-bw-var' => 'pvb',
+        'application/vnd.3gpp2.tcap' => 'tcap',
+        'application/vnd.3m.post-it-notes' => 'pwn',
+        'application/vnd.accpac.simply.aso' => 'aso',
+        'application/vnd.accpac.simply.imp' => 'imp',
+        'application/vnd.acucobol' => 'acu',
+        'application/vnd.acucorp' => 'atc',
+        'application/vnd.adobe.air-application-installer-package+zip' => 'air',
+        'application/vnd.adobe.fxp' => 'fxp',
+        'application/vnd.adobe.xdp+xml' => 'xdp',
+        'application/vnd.adobe.xfdf' => 'xfdf',
+        'application/vnd.ahead.space' => 'ahead',
+        'application/vnd.airzip.filesecure.azf' => 'azf',
+        'application/vnd.airzip.filesecure.azs' => 'azs',
+        'application/vnd.amazon.ebook' => 'azw',
+        'application/vnd.americandynamics.acc' => 'acc',
+        'application/vnd.amiga.ami' => 'ami',
+        'application/vnd.android.package-archive' => 'apk',
+        'application/vnd.anser-web-certificate-issue-initiation' => 'cii',
+        'application/vnd.anser-web-funds-transfer-initiation' => 'fti',
+        'application/vnd.antix.game-component' => 'atx',
+        'application/vnd.apple.installer+xml' => 'mpkg',
+        'application/vnd.apple.mpegurl' => 'm3u8',
+        'application/vnd.aristanetworks.swi' => 'swi',
+        'application/vnd.astraea-software.iota' => 'iota',
+        'application/vnd.audiograph' => 'aep',
+        'application/vnd.blueice.multipass' => 'mpm',
+        'application/vnd.bmi' => 'bmi',
+        'application/vnd.businessobjects' => 'rep',
+        'application/vnd.chemdraw+xml' => 'cdxml',
+        'application/vnd.chipnuts.karaoke-mmd' => 'mmd',
+        'application/vnd.cinderella' => 'cdy',
+        'application/vnd.claymore' => 'cla',
+        'application/vnd.cloanto.rp9' => 'rp9',
+        'application/vnd.clonk.c4group' => 'c4g',
+        'application/vnd.cluetrust.cartomobile-config' => 'c11amc',
+        'application/vnd.cluetrust.cartomobile-config-pkg' => 'c11amz',
+        'application/vnd.commonspace' => 'csp',
+        'application/vnd.contact.cmsg' => 'cdbcmsg',
+        'application/vnd.cosmocaller' => 'cmc',
+        'application/vnd.crick.clicker' => 'clkx',
+        'application/vnd.crick.clicker.keyboard' => 'clkk',
+        'application/vnd.crick.clicker.palette' => 'clkp',
+        'application/vnd.crick.clicker.template' => 'clkt',
+        'application/vnd.crick.clicker.wordbank' => 'clkw',
+        'application/vnd.criticaltools.wbs+xml' => 'wbs',
+        'application/vnd.ctc-posml' => 'pml',
+        'application/vnd.cups-ppd' => 'ppd',
+        'application/vnd.curl.car' => 'car',
+        'application/vnd.curl.pcurl' => 'pcurl',
+        'application/vnd.data-vision.rdz' => 'rdz',
+        'application/vnd.dece.data' => 'uvf',
+        'application/vnd.dece.ttml+xml' => 'uvt',
+        'application/vnd.dece.unspecified' => 'uvx',
+        'application/vnd.dece.zip' => 'uvz',
+        'application/vnd.denovo.fcselayout-link' => 'fe_launch',
+        'application/vnd.dna' => 'dna',
+        'application/vnd.dolby.mlp' => 'mlp',
+        'application/vnd.dpgraph' => 'dpg',
+        'application/vnd.dreamfactory' => 'dfac',
+        'application/vnd.dvb.ait' => 'ait',
+        'application/vnd.dvb.service' => 'svc',
+        'application/vnd.dynageo' => 'geo',
+        'application/vnd.ecowin.chart' => 'mag',
+        'application/vnd.enliven' => 'nml',
+        'application/vnd.epson.esf' => 'esf',
+        'application/vnd.epson.msf' => 'msf',
+        'application/vnd.epson.quickanime' => 'qam',
+        'application/vnd.epson.salt' => 'slt',
+        'application/vnd.epson.ssf' => 'ssf',
+        'application/vnd.eszigno3+xml' => 'es3',
+        'application/vnd.ezpix-album' => 'ez2',
+        'application/vnd.ezpix-package' => 'ez3',
+        'application/vnd.fdf' => 'fdf',
+        'application/vnd.fdsn.mseed' => 'mseed',
+        'application/vnd.fdsn.seed' => 'seed',
+        'application/vnd.flographit' => 'gph',
+        'application/vnd.fluxtime.clip' => 'ftc',
+        'application/vnd.framemaker' => 'fm',
+        'application/vnd.frogans.fnc' => 'fnc',
+        'application/vnd.frogans.ltf' => 'ltf',
+        'application/vnd.fsc.weblaunch' => 'fsc',
+        'application/vnd.fujitsu.oasys' => 'oas',
+        'application/vnd.fujitsu.oasys2' => 'oa2',
+        'application/vnd.fujitsu.oasys3' => 'oa3',
+        'application/vnd.fujitsu.oasysgp' => 'fg5',
+        'application/vnd.fujitsu.oasysprs' => 'bh2',
+        'application/vnd.fujixerox.ddd' => 'ddd',
+        'application/vnd.fujixerox.docuworks' => 'xdw',
+        'application/vnd.fujixerox.docuworks.binder' => 'xbd',
+        'application/vnd.fuzzysheet' => 'fzs',
+        'application/vnd.genomatix.tuxedo' => 'txd',
+        'application/vnd.geogebra.file' => 'ggb',
+        'application/vnd.geogebra.tool' => 'ggt',
+        'application/vnd.geometry-explorer' => 'gex',
+        'application/vnd.geonext' => 'gxt',
+        'application/vnd.geoplan' => 'g2w',
+        'application/vnd.geospace' => 'g3w',
+        'application/vnd.gmx' => 'gmx',
+        'application/vnd.google-earth.kml+xml' => 'kml',
+        'application/vnd.google-earth.kmz' => 'kmz',
+        'application/vnd.grafeq' => 'gqf',
+        'application/vnd.groove-account' => 'gac',
+        'application/vnd.groove-help' => 'ghf',
+        'application/vnd.groove-identity-message' => 'gim',
+        'application/vnd.groove-injector' => 'grv',
+        'application/vnd.groove-tool-message' => 'gtm',
+        'application/vnd.groove-tool-template' => 'tpl',
+        'application/vnd.groove-vcard' => 'vcg',
+        'application/vnd.hal+xml' => 'hal',
+        'application/vnd.handheld-entertainment+xml' => 'zmm',
+        'application/vnd.hbci' => 'hbci',
+        'application/vnd.hhe.lesson-player' => 'les',
+        'application/vnd.hp-hpgl' => 'hpgl',
+        'application/vnd.hp-hpid' => 'hpid',
+        'application/vnd.hp-hps' => 'hps',
+        'application/vnd.hp-jlyt' => 'jlt',
+        'application/vnd.hp-pcl' => 'pcl',
+        'application/vnd.hp-pclxl' => 'pclxl',
+        'application/vnd.hydrostatix.sof-data' => 'sfd-hdstx',
+        'application/vnd.hzn-3d-crossword' => 'x3d',
+        'application/vnd.ibm.minipay' => 'mpy',
+        'application/vnd.ibm.modcap' => 'afp',
+        'application/vnd.ibm.rights-management' => 'irm',
+        'application/vnd.ibm.secure-container' => 'sc',
+        'application/vnd.iccprofile' => 'icc',
+        'application/vnd.igloader' => 'igl',
+        'application/vnd.immervision-ivp' => 'ivp',
+        'application/vnd.immervision-ivu' => 'ivu',
+        'application/vnd.insors.igm' => 'igm',
+        'application/vnd.intercon.formnet' => 'xpw',
+        'application/vnd.intergeo' => 'i2g',
+        'application/vnd.intu.qbo' => 'qbo',
+        'application/vnd.intu.qfx' => 'qfx',
+        'application/vnd.ipunplugged.rcprofile' => 'rcprofile',
+        'application/vnd.irepository.package+xml' => 'irp',
+        'application/vnd.is-xpr' => 'xpr',
+        'application/vnd.isac.fcs' => 'fcs',
+        'application/vnd.jam' => 'jam',
+        'application/vnd.jcp.javame.midlet-rms' => 'rms',
+        'application/vnd.jisp' => 'jisp',
+        'application/vnd.joost.joda-archive' => 'joda',
+        'application/vnd.kahootz' => 'ktz',
+        'application/vnd.kde.karbon' => 'karbon',
+        'application/vnd.kde.kchart' => 'chrt',
+        'application/vnd.kde.kformula' => 'kfo',
+        'application/vnd.kde.kivio' => 'flw',
+        'application/vnd.kde.kontour' => 'kon',
+        'application/vnd.kde.kpresenter' => 'kpr',
+        'application/vnd.kde.kspread' => 'ksp',
+        'application/vnd.kde.kword' => 'kwd',
+        'application/vnd.kenameaapp' => 'htke',
+        'application/vnd.kidspiration' => 'kia',
+        'application/vnd.kinar' => 'kne',
+        'application/vnd.koan' => 'skp',
+        'application/vnd.kodak-descriptor' => 'sse',
+        'application/vnd.las.las+xml' => 'lasxml',
+        'application/vnd.llamagraphics.life-balance.desktop' => 'lbd',
+        'application/vnd.llamagraphics.life-balance.exchange+xml' => 'lbe',
+        'application/vnd.lotus-1-2-3' => '123',
+        'application/vnd.lotus-approach' => 'apr',
+        'application/vnd.lotus-freelance' => 'pre',
+        'application/vnd.lotus-notes' => 'nsf',
+        'application/vnd.lotus-organizer' => 'org',
+        'application/vnd.lotus-screencam' => 'scm',
+        'application/vnd.lotus-wordpro' => 'lwp',
+        'application/vnd.macports.portpkg' => 'portpkg',
+        'application/vnd.mcd' => 'mcd',
+        'application/vnd.medcalcdata' => 'mc1',
+        'application/vnd.mediastation.cdkey' => 'cdkey',
+        'application/vnd.mfer' => 'mwf',
+        'application/vnd.mfmp' => 'mfm',
+        'application/vnd.micrografx.flo' => 'flo',
+        'application/vnd.micrografx.igx' => 'igx',
+        'application/vnd.mif' => 'mif',
+        'application/vnd.mobius.daf' => 'daf',
+        'application/vnd.mobius.dis' => 'dis',
+        'application/vnd.mobius.mbk' => 'mbk',
+        'application/vnd.mobius.mqy' => 'mqy',
+        'application/vnd.mobius.msl' => 'msl',
+        'application/vnd.mobius.plc' => 'plc',
+        'application/vnd.mobius.txf' => 'txf',
+        'application/vnd.mophun.application' => 'mpn',
+        'application/vnd.mophun.certificate' => 'mpc',
+        'application/vnd.mozilla.xul+xml' => 'xul',
+        'application/vnd.ms-artgalry' => 'cil',
+        'application/vnd.ms-cab-compressed' => 'cab',
+        'application/vnd.ms-excel' => 'xls',
+        'application/vnd.ms-excel.addin.macroenabled.12' => 'xlam',
+        'application/vnd.ms-excel.sheet.binary.macroenabled.12' => 'xlsb',
+        'application/vnd.ms-excel.sheet.macroenabled.12' => 'xlsm',
+        'application/vnd.ms-excel.template.macroenabled.12' => 'xltm',
+        'application/vnd.ms-fontobject' => 'eot',
+        'application/vnd.ms-htmlhelp' => 'chm',
+        'application/vnd.ms-ims' => 'ims',
+        'application/vnd.ms-lrm' => 'lrm',
+        'application/vnd.ms-officetheme' => 'thmx',
+        'application/vnd.ms-pki.seccat' => 'cat',
+        'application/vnd.ms-pki.stl' => 'stl',
+        'application/vnd.ms-powerpoint' => 'ppt',
+        'application/vnd.ms-powerpoint.addin.macroenabled.12' => 'ppam',
+        'application/vnd.ms-powerpoint.presentation.macroenabled.12' => 'pptm',
+        'application/vnd.ms-powerpoint.slide.macroenabled.12' => 'sldm',
+        'application/vnd.ms-powerpoint.slideshow.macroenabled.12' => 'ppsm',
+        'application/vnd.ms-powerpoint.template.macroenabled.12' => 'potm',
+        'application/vnd.ms-project' => 'mpp',
+        'application/vnd.ms-word.document.macroenabled.12' => 'docm',
+        'application/vnd.ms-word.template.macroenabled.12' => 'dotm',
+        'application/vnd.ms-works' => 'wps',
+        'application/vnd.ms-wpl' => 'wpl',
+        'application/vnd.ms-xpsdocument' => 'xps',
+        'application/vnd.mseq' => 'mseq',
+        'application/vnd.musician' => 'mus',
+        'application/vnd.muvee.style' => 'msty',
+        'application/vnd.mynfc' => 'taglet',
+        'application/vnd.neurolanguage.nlu' => 'nlu',
+        'application/vnd.noblenet-directory' => 'nnd',
+        'application/vnd.noblenet-sealer' => 'nns',
+        'application/vnd.noblenet-web' => 'nnw',
+        'application/vnd.nokia.n-gage.data' => 'ngdat',
+        'application/vnd.nokia.n-gage.symbian.install' => 'n-gage',
+        'application/vnd.nokia.radio-preset' => 'rpst',
+        'application/vnd.nokia.radio-presets' => 'rpss',
+        'application/vnd.novadigm.edm' => 'edm',
+        'application/vnd.novadigm.edx' => 'edx',
+        'application/vnd.novadigm.ext' => 'ext',
+        'application/vnd.oasis.opendocument.chart' => 'odc',
+        'application/vnd.oasis.opendocument.chart-template' => 'otc',
+        'application/vnd.oasis.opendocument.database' => 'odb',
+        'application/vnd.oasis.opendocument.formula' => 'odf',
+        'application/vnd.oasis.opendocument.formula-template' => 'odft',
+        'application/vnd.oasis.opendocument.graphics' => 'odg',
+        'application/vnd.oasis.opendocument.graphics-template' => 'otg',
+        'application/vnd.oasis.opendocument.image' => 'odi',
+        'application/vnd.oasis.opendocument.image-template' => 'oti',
+        'application/vnd.oasis.opendocument.presentation' => 'odp',
+        'application/vnd.oasis.opendocument.presentation-template' => 'otp',
+        'application/vnd.oasis.opendocument.spreadsheet' => 'ods',
+        'application/vnd.oasis.opendocument.spreadsheet-template' => 'ots',
+        'application/vnd.oasis.opendocument.text' => 'odt',
+        'application/vnd.oasis.opendocument.text-master' => 'odm',
+        'application/vnd.oasis.opendocument.text-template' => 'ott',
+        'application/vnd.oasis.opendocument.text-web' => 'oth',
+        'application/vnd.olpc-sugar' => 'xo',
+        'application/vnd.oma.dd2+xml' => 'dd2',
+        'application/vnd.openofficeorg.extension' => 'oxt',
+        'application/vnd.openxmlformats-officedocument.presentationml.presentation' => 'pptx',
+        'application/vnd.openxmlformats-officedocument.presentationml.slide' => 'sldx',
+        'application/vnd.openxmlformats-officedocument.presentationml.slideshow' => 'ppsx',
+        'application/vnd.openxmlformats-officedocument.presentationml.template' => 'potx',
+        'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet' => 'xlsx',
+        'application/vnd.openxmlformats-officedocument.spreadsheetml.template' => 'xltx',
+        'application/vnd.openxmlformats-officedocument.wordprocessingml.document' => 'docx',
+        'application/vnd.openxmlformats-officedocument.wordprocessingml.template' => 'dotx',
+        'application/vnd.osgeo.mapguide.package' => 'mgp',
+        'application/vnd.osgi.dp' => 'dp',
+        'application/vnd.palm' => 'pdb',
+        'application/vnd.pawaafile' => 'paw',
+        'application/vnd.pg.format' => 'str',
+        'application/vnd.pg.osasli' => 'ei6',
+        'application/vnd.picsel' => 'efif',
+        'application/vnd.pmi.widget' => 'wg',
+        'application/vnd.pocketlearn' => 'plf',
+        'application/vnd.powerbuilder6' => 'pbd',
+        'application/vnd.previewsystems.box' => 'box',
+        'application/vnd.proteus.magazine' => 'mgz',
+        'application/vnd.publishare-delta-tree' => 'qps',
+        'application/vnd.pvi.ptid1' => 'ptid',
+        'application/vnd.quark.quarkxpress' => 'qxd',
+        'application/vnd.realvnc.bed' => 'bed',
+        'application/vnd.recordare.musicxml' => 'mxl',
+        'application/vnd.recordare.musicxml+xml' => 'musicxml',
+        'application/vnd.rig.cryptonote' => 'cryptonote',
+        'application/vnd.rim.cod' => 'cod',
+        'application/vnd.rn-realmedia' => 'rm',
+        'application/vnd.route66.link66+xml' => 'link66',
+        'application/vnd.sailingtracker.track' => 'st',
+        'application/vnd.seemail' => 'see',
+        'application/vnd.sema' => 'sema',
+        'application/vnd.semd' => 'semd',
+        'application/vnd.semf' => 'semf',
+        'application/vnd.shana.informed.formdata' => 'ifm',
+        'application/vnd.shana.informed.formtemplate' => 'itp',
+        'application/vnd.shana.informed.interchange' => 'if',
+        'application/vnd.shana.informed.package' => 'ipk',
+        'application/vnd.simtech-mindmapper' => 'twd',
+        'application/vnd.smaf' => 'mmf',
+        'application/vnd.smart.teacher' => 'teacher',
+        'application/vnd.solent.sdkm+xml' => 'sdkm',
+        'application/vnd.spotfire.dxp' => 'dxp',
+        'application/vnd.spotfire.sfs' => 'sfs',
+        'application/vnd.stardivision.calc' => 'sdc',
+        'application/vnd.stardivision.draw' => 'sda',
+        'application/vnd.stardivision.impress' => 'sdd',
+        'application/vnd.stardivision.math' => 'smf',
+        'application/vnd.stardivision.writer' => 'sdw',
+        'application/vnd.stardivision.writer-global' => 'sgl',
+        'application/vnd.stepmania.package' => 'smzip',
+        'application/vnd.stepmania.stepchart' => 'sm',
+        'application/vnd.sun.xml.calc' => 'sxc',
+        'application/vnd.sun.xml.calc.template' => 'stc',
+        'application/vnd.sun.xml.draw' => 'sxd',
+        'application/vnd.sun.xml.draw.template' => 'std',
+        'application/vnd.sun.xml.impress' => 'sxi',
+        'application/vnd.sun.xml.impress.template' => 'sti',
+        'application/vnd.sun.xml.math' => 'sxm',
+        'application/vnd.sun.xml.writer' => 'sxw',
+        'application/vnd.sun.xml.writer.global' => 'sxg',
+        'application/vnd.sun.xml.writer.template' => 'stw',
+        'application/vnd.sus-calendar' => 'sus',
+        'application/vnd.svd' => 'svd',
+        'application/vnd.symbian.install' => 'sis',
+        'application/vnd.syncml+xml' => 'xsm',
+        'application/vnd.syncml.dm+wbxml' => 'bdm',
+        'application/vnd.syncml.dm+xml' => 'xdm',
+        'application/vnd.tao.intent-module-archive' => 'tao',
+        'application/vnd.tcpdump.pcap' => 'pcap',
+        'application/vnd.tmobile-livetv' => 'tmo',
+        'application/vnd.trid.tpt' => 'tpt',
+        'application/vnd.triscape.mxs' => 'mxs',
+        'application/vnd.trueapp' => 'tra',
+        'application/vnd.ufdl' => 'ufd',
+        'application/vnd.uiq.theme' => 'utz',
+        'application/vnd.umajin' => 'umj',
+        'application/vnd.unity' => 'unityweb',
+        'application/vnd.uoml+xml' => 'uoml',
+        'application/vnd.vcx' => 'vcx',
+        'application/vnd.visio' => 'vsd',
+        'application/vnd.visionary' => 'vis',
+        'application/vnd.vsf' => 'vsf',
+        'application/vnd.wap.wbxml' => 'wbxml',
+        'application/vnd.wap.wmlc' => 'wmlc',
+        'application/vnd.wap.wmlscriptc' => 'wmlsc',
+        'application/vnd.webturbo' => 'wtb',
+        'application/vnd.wolfram.player' => 'nbp',
+        'application/vnd.wordperfect' => 'wpd',
+        'application/vnd.wqd' => 'wqd',
+        'application/vnd.wt.stf' => 'stf',
+        'application/vnd.xara' => 'xar',
+        'application/vnd.xfdl' => 'xfdl',
+        'application/vnd.yamaha.hv-dic' => 'hvd',
+        'application/vnd.yamaha.hv-script' => 'hvs',
+        'application/vnd.yamaha.hv-voice' => 'hvp',
+        'application/vnd.yamaha.openscoreformat' => 'osf',
+        'application/vnd.yamaha.openscoreformat.osfpvg+xml' => 'osfpvg',
+        'application/vnd.yamaha.smaf-audio' => 'saf',
+        'application/vnd.yamaha.smaf-phrase' => 'spf',
+        'application/vnd.yellowriver-custom-menu' => 'cmp',
+        'application/vnd.zul' => 'zir',
+        'application/vnd.zzazz.deck+xml' => 'zaz',
+        'application/voicexml+xml' => 'vxml',
+        'application/widget' => 'wgt',
+        'application/winhlp' => 'hlp',
+        'application/wsdl+xml' => 'wsdl',
+        'application/wspolicy+xml' => 'wspolicy',
+        'application/x-7z-compressed' => '7z',
+        'application/x-abiword' => 'abw',
+        'application/x-ace-compressed' => 'ace',
+        'application/x-authorware-bin' => 'aab',
+        'application/x-authorware-map' => 'aam',
+        'application/x-authorware-seg' => 'aas',
+        'application/x-bcpio' => 'bcpio',
+        'application/x-bittorrent' => 'torrent',
+        'application/x-bzip' => 'bz',
+        'application/x-bzip2' => 'bz2',
+        'application/x-cdlink' => 'vcd',
+        'application/x-chat' => 'chat',
+        'application/x-chess-pgn' => 'pgn',
+        'application/x-cpio' => 'cpio',
+        'application/x-csh' => 'csh',
+        'application/x-debian-package' => 'deb',
+        'application/x-director' => 'dir',
+        'application/x-doom' => 'wad',
+        'application/x-dtbncx+xml' => 'ncx',
+        'application/x-dtbook+xml' => 'dtb',
+        'application/x-dtbresource+xml' => 'res',
+        'application/x-dvi' => 'dvi',
+        'application/x-font-bdf' => 'bdf',
+        'application/x-font-ghostscript' => 'gsf',
+        'application/x-font-linux-psf' => 'psf',
+        'application/x-font-otf' => 'otf',
+        'application/x-font-pcf' => 'pcf',
+        'application/x-font-snf' => 'snf',
+        'application/x-font-ttf' => 'ttf',
+        'application/x-font-type1' => 'pfa',
+        'application/x-font-woff' => 'woff',
+        'application/x-futuresplash' => 'spl',
+        'application/x-gnumeric' => 'gnumeric',
+        'application/x-gtar' => 'gtar',
+        'application/x-hdf' => 'hdf',
+        'application/x-java-jnlp-file' => 'jnlp',
+        'application/x-latex' => 'latex',
+        'application/x-mobipocket-ebook' => 'prc',
+        'application/x-ms-application' => 'application',
+        'application/x-ms-wmd' => 'wmd',
+        'application/x-ms-wmz' => 'wmz',
+        'application/x-ms-xbap' => 'xbap',
+        'application/x-msaccess' => 'mdb',
+        'application/x-msbinder' => 'obd',
+        'application/x-mscardfile' => 'crd',
+        'application/x-msclip' => 'clp',
+        'application/x-msdownload' => 'exe',
+        'application/x-msmediaview' => 'mvb',
+        'application/x-msmetafile' => 'wmf',
+        'application/x-msmoney' => 'mny',
+        'application/x-mspublisher' => 'pub',
+        'application/x-msschedule' => 'scd',
+        'application/x-msterminal' => 'trm',
+        'application/x-mswrite' => 'wri',
+        'application/x-netcdf' => 'nc',
+        'application/x-pkcs12' => 'p12',
+        'application/x-pkcs7-certificates' => 'p7b',
+        'application/x-pkcs7-certreqresp' => 'p7r',
+        'application/x-rar-compressed' => 'rar',
+        'application/x-rar' => 'rar',
+        'application/x-sh' => 'sh',
+        'application/x-shar' => 'shar',
+        'application/x-shockwave-flash' => 'swf',
+        'application/x-silverlight-app' => 'xap',
+        'application/x-stuffit' => 'sit',
+        'application/x-stuffitx' => 'sitx',
+        'application/x-sv4cpio' => 'sv4cpio',
+        'application/x-sv4crc' => 'sv4crc',
+        'application/x-tar' => 'tar',
+        'application/x-tcl' => 'tcl',
+        'application/x-tex' => 'tex',
+        'application/x-tex-tfm' => 'tfm',
+        'application/x-texinfo' => 'texinfo',
+        'application/x-ustar' => 'ustar',
+        'application/x-wais-source' => 'src',
+        'application/x-x509-ca-cert' => 'der',
+        'application/x-xfig' => 'fig',
+        'application/x-xpinstall' => 'xpi',
+        'application/xcap-diff+xml' => 'xdf',
+        'application/xenc+xml' => 'xenc',
+        'application/xhtml+xml' => 'xhtml',
+        'application/xml' => 'xml',
+        'application/xml-dtd' => 'dtd',
+        'application/xop+xml' => 'xop',
+        'application/xslt+xml' => 'xslt',
+        'application/xspf+xml' => 'xspf',
+        'application/xv+xml' => 'mxml',
+        'application/yang' => 'yang',
+        'application/yin+xml' => 'yin',
+        'application/zip' => 'zip',
+        'audio/adpcm' => 'adp',
+        'audio/basic' => 'au',
+        'audio/midi' => 'mid',
+        'audio/mp4' => 'mp4a',
+        'audio/mpeg' => 'mpga',
+        'audio/ogg' => 'oga',
+        'audio/vnd.dece.audio' => 'uva',
+        'audio/vnd.digital-winds' => 'eol',
+        'audio/vnd.dra' => 'dra',
+        'audio/vnd.dts' => 'dts',
+        'audio/vnd.dts.hd' => 'dtshd',
+        'audio/vnd.lucent.voice' => 'lvp',
+        'audio/vnd.ms-playready.media.pya' => 'pya',
+        'audio/vnd.nuera.ecelp4800' => 'ecelp4800',
+        'audio/vnd.nuera.ecelp7470' => 'ecelp7470',
+        'audio/vnd.nuera.ecelp9600' => 'ecelp9600',
+        'audio/vnd.rip' => 'rip',
+        'audio/webm' => 'weba',
+        'audio/x-aac' => 'aac',
+        'audio/x-aiff' => 'aif',
+        'audio/x-mpegurl' => 'm3u',
+        'audio/x-ms-wax' => 'wax',
+        'audio/x-ms-wma' => 'wma',
+        'audio/x-pn-realaudio' => 'ram',
+        'audio/x-pn-realaudio-plugin' => 'rmp',
+        'audio/x-wav' => 'wav',
+        'chemical/x-cdx' => 'cdx',
+        'chemical/x-cif' => 'cif',
+        'chemical/x-cmdf' => 'cmdf',
+        'chemical/x-cml' => 'cml',
+        'chemical/x-csml' => 'csml',
+        'chemical/x-xyz' => 'xyz',
+        'image/bmp' => 'bmp',
+        'image/cgm' => 'cgm',
+        'image/g3fax' => 'g3',
+        'image/gif' => 'gif',
+        'image/ief' => 'ief',
+        'image/jpeg' => 'jpeg',
+        'image/ktx' => 'ktx',
+        'image/png' => 'png',
+        'image/prs.btif' => 'btif',
+        'image/svg+xml' => 'svg',
+        'image/tiff' => 'tiff',
+        'image/vnd.adobe.photoshop' => 'psd',
+        'image/vnd.dece.graphic' => 'uvi',
+        'image/vnd.dvb.subtitle' => 'sub',
+        'image/vnd.djvu' => 'djvu',
+        'image/vnd.dwg' => 'dwg',
+        'image/vnd.dxf' => 'dxf',
+        'image/vnd.fastbidsheet' => 'fbs',
+        'image/vnd.fpx' => 'fpx',
+        'image/vnd.fst' => 'fst',
+        'image/vnd.fujixerox.edmics-mmr' => 'mmr',
+        'image/vnd.fujixerox.edmics-rlc' => 'rlc',
+        'image/vnd.ms-modi' => 'mdi',
+        'image/vnd.net-fpx' => 'npx',
+        'image/vnd.wap.wbmp' => 'wbmp',
+        'image/vnd.xiff' => 'xif',
+        'image/webp' => 'webp',
+        'image/x-cmu-raster' => 'ras',
+        'image/x-cmx' => 'cmx',
+        'image/x-freehand' => 'fh',
+        'image/x-icon' => 'ico',
+        'image/x-pcx' => 'pcx',
+        'image/x-pict' => 'pic',
+        'image/x-portable-anymap' => 'pnm',
+        'image/x-portable-bitmap' => 'pbm',
+        'image/x-portable-graymap' => 'pgm',
+        'image/x-portable-pixmap' => 'ppm',
+        'image/x-rgb' => 'rgb',
+        'image/x-xbitmap' => 'xbm',
+        'image/x-xpixmap' => 'xpm',
+        'image/x-xwindowdump' => 'xwd',
+        'message/rfc822' => 'eml',
+        'model/iges' => 'igs',
+        'model/mesh' => 'msh',
+        'model/vnd.collada+xml' => 'dae',
+        'model/vnd.dwf' => 'dwf',
+        'model/vnd.gdl' => 'gdl',
+        'model/vnd.gtw' => 'gtw',
+        'model/vnd.mts' => 'mts',
+        'model/vnd.vtu' => 'vtu',
+        'model/vrml' => 'wrl',
+        'text/calendar' => 'ics',
+        'text/css' => 'css',
+        'text/csv' => 'csv',
+        'text/html' => 'html',
+        'text/n3' => 'n3',
+        'text/plain' => 'txt',
+        'text/prs.lines.tag' => 'dsc',
+        'text/richtext' => 'rtx',
+        'text/sgml' => 'sgml',
+        'text/tab-separated-values' => 'tsv',
+        'text/troff' => 't',
+        'text/turtle' => 'ttl',
+        'text/uri-list' => 'uri',
+        'text/vcard' => 'vcard',
+        'text/vnd.curl' => 'curl',
+        'text/vnd.curl.dcurl' => 'dcurl',
+        'text/vnd.curl.scurl' => 'scurl',
+        'text/vnd.curl.mcurl' => 'mcurl',
+        'text/vnd.dvb.subtitle' => 'sub',
+        'text/vnd.fly' => 'fly',
+        'text/vnd.fmi.flexstor' => 'flx',
+        'text/vnd.graphviz' => 'gv',
+        'text/vnd.in3d.3dml' => '3dml',
+        'text/vnd.in3d.spot' => 'spot',
+        'text/vnd.sun.j2me.app-descriptor' => 'jad',
+        'text/vnd.wap.wml' => 'wml',
+        'text/vnd.wap.wmlscript' => 'wmls',
+        'text/x-asm' => 's',
+        'text/x-c' => 'c',
+        'text/x-fortran' => 'f',
+        'text/x-pascal' => 'p',
+        'text/x-java-source' => 'java',
+        'text/x-setext' => 'etx',
+        'text/x-uuencode' => 'uu',
+        'text/x-vcalendar' => 'vcs',
+        'text/x-vcard' => 'vcf',
+        'video/3gpp' => '3gp',
+        'video/3gpp2' => '3g2',
+        'video/h261' => 'h261',
+        'video/h263' => 'h263',
+        'video/h264' => 'h264',
+        'video/jpeg' => 'jpgv',
+        'video/jpm' => 'jpm',
+        'video/mj2' => 'mj2',
+        'video/mp4' => 'mp4',
+        'video/mpeg' => 'mpeg',
+        'video/ogg' => 'ogv',
+        'video/quicktime' => 'qt',
+        'video/vnd.dece.hd' => 'uvh',
+        'video/vnd.dece.mobile' => 'uvm',
+        'video/vnd.dece.pd' => 'uvp',
+        'video/vnd.dece.sd' => 'uvs',
+        'video/vnd.dece.video' => 'uvv',
+        'video/vnd.dvb.file' => 'dvb',
+        'video/vnd.fvt' => 'fvt',
+        'video/vnd.mpegurl' => 'mxu',
+        'video/vnd.ms-playready.media.pyv' => 'pyv',
+        'video/vnd.uvvu.mp4' => 'uvu',
+        'video/vnd.vivo' => 'viv',
+        'video/webm' => 'webm',
+        'video/x-f4v' => 'f4v',
+        'video/x-fli' => 'fli',
+        'video/x-flv' => 'flv',
+        'video/x-m4v' => 'm4v',
+        'video/x-ms-asf' => 'asf',
+        'video/x-ms-wm' => 'wm',
+        'video/x-ms-wmv' => 'wmv',
+        'video/x-ms-wmx' => 'wmx',
+        'video/x-ms-wvx' => 'wvx',
+        'video/x-msvideo' => 'avi',
+        'video/x-sgi-movie' => 'movie',
+        'x-conference/x-cooltalk' => 'ice',
+    );
+
+    /**
+     * {@inheritdoc}
+     */
+    public function guess($mimeType)
+    {
+        return isset($this->defaultExtensions[$mimeType]) ? $this->defaultExtensions[$mimeType] : null;
+    }
+}
--- ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/Response.php	original
+++ ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/Response.php	fixed
@@ -1100 +1100 @@
-     * Is the reponse forbidden?
+     * Is the response forbidden?
--- ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/JsonResponse.php	original
+++ ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/JsonResponse.php	fixed
@@ -57 +57 @@
-            $pattern = '/^[$_\p{L}][$_\p{L}\p{Mn}\p{Mc}\p{Nd}\p{Pc}\x{200C}\x{200D}]*+$/u';
+            $pattern = '/^[$_\p{L}][$_\p{L}\p{Mn}\p{Mc}\p{And}\p{Pc}\x{200C}\x{200D}]*+$/u';
--- ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/Session/Storage/NativeSessionStorage.php	original
+++ ./vendor/symfony/http-foundation/Symfony/Component/HttpFoundation/Session/Storage/NativeSessionStorage.php	fixed
@@ -81 +81 @@
-     * referer_check, ""
+     * referrer_check, ""
@@ -317 +317 @@
-            'hash_function', 'name', 'referer_check',
+            'hash_function', 'name', 'referrer_check',
--- ./vendor/hybridauth/CHANGELOG	original
+++ ./vendor/hybridauth/CHANGELOG	fixed
@@ -34 +34 @@
-	Another numbers of bug fixes and improvments
+	Another numbers of bug fixes and improvements
@@ -52 +52 @@
-	Hubrid_Auth_Activity::$date return now a timestamp across supproted social networks
+	Hubrid_Auth_Activity::$date return now a timestamp across supported social networks
--- ./vendor/hybridauth/Hybrid/User.php	original
+++ ./vendor/hybridauth/Hybrid/User.php	fixed
@@ -19 +19 @@
-	/* user profile, containts the list of fields available in the normalized user profile structure used by HybridAuth. */
+	/* user profile, contains the list of fields available in the normalized user profile structure used by HybridAuth. */
--- ./vendor/hybridauth/Hybrid/Provider_Model_OAuth1.php	original
+++ ./vendor/hybridauth/Hybrid/Provider_Model_OAuth1.php	fixed
@@ -22,2 +22,2 @@
-	public $request_tokens_raw = null; // request_tokens as recived from provider
-	public $access_tokens_raw  = null; // access_tokens as recived from provider
+	public $request_tokens_raw = null; // request_tokens as received from provider
+	public $access_tokens_raw  = null; // access_tokens as received from provider
@@ -81 +81 @@
-		// 3.3 - instanciate OAuth client with client credentials
+		// 3.3 - instantiate OAuth client with client credentials
@@ -101 +101 @@
-		// request tokens as recived from provider
+		// request tokens as received from provider
@@ -106 +106 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an error. " . $this->errorMessageByStatus( $this->api->http_code ), 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an error. " . $this->errorMessageByStatus( $this->api->http_code ), 5 );
@@ -110 +110 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid oauth token.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid oauth token.", 5 );
@@ -131 +131 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid oauth verifier.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid oauth verifier.", 5 );
@@ -137 +137 @@
-		// access tokens as recived from provider
+		// access tokens as received from provider
@@ -142 +142 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an error. " . $this->errorMessageByStatus( $this->api->http_code ), 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an error. " . $this->errorMessageByStatus( $this->api->http_code ), 5 );
@@ -147 +147 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid access token.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid access token.", 5 );
@@ -150 +150 @@
-		// we no more need to store requet tokens
+		// we no more need to store request tokens
--- ./vendor/hybridauth/Hybrid/User_Contact.php	original
+++ ./vendor/hybridauth/Hybrid/User_Contact.php	fixed
@@ -29 +29 @@
-	/* User dispalyName provided by the IDp or a concatenation of first and last name */
+	/* User displayName provided by the IDp or a concatenation of first and last name */
--- ./vendor/hybridauth/Hybrid/Provider_Adapter.php	original
+++ ./vendor/hybridauth/Hybrid/Provider_Adapter.php	fixed
@@ -93 +93 @@
-	* Hybrid_Provider_Adapter::login(), prepare the user session and the authentification request
+	* Hybrid_Provider_Adapter::login(), prepare the user session and the authentication request
--- ./vendor/hybridauth/Hybrid/thirdparty/Facebook/base_facebook.php	original
+++ ./vendor/hybridauth/Hybrid/thirdparty/Facebook/base_facebook.php	fixed
@@ -1189 +1189 @@
-          'API call before outputing anything'
+          'API call before outputting anything'
--- ./vendor/hybridauth/Hybrid/thirdparty/LinkedIn/LinkedIn.php	original
+++ ./vendor/hybridauth/Hybrid/thirdparty/LinkedIn/LinkedIn.php	fixed
@@ -4 +4 @@
-// hacked into the code to handel new scope (r_basicprofile+r_emailaddress) - until Paul update linkedinphp library!
+// hacked into the code to handle new scope (r_basicprofile+r_emailaddress) - until Paul update linkedinphp library!
--- ./vendor/hybridauth/Hybrid/thirdparty/OpenID/LightOpenID.php	original
+++ ./vendor/hybridauth/Hybrid/thirdparty/OpenID/LightOpenID.php	fixed
@@ -519 +519 @@
-        # That's because it's fully backwards compatibile with 1.0, and some providers
+        # That's because it's fully backwards compatible with 1.0, and some providers
@@ -569 +569 @@
-            # Don't send empty ax.requied and ax.if_available.
+            # Don't send empty ax.required and ax.if_available.
@@ -702 +702 @@
-            # AX namePerson, it might containg an apostrophe, which will be escaped.
+            # AX namePerson, it might containing an apostrophe, which will be escaped.
--- ./vendor/hybridauth/Hybrid/thirdparty/OAuth/OAuth2Client.php	original
+++ ./vendor/hybridauth/Hybrid/thirdparty/OAuth/OAuth2Client.php	fixed
@@ -234 +234 @@
-		parse_str( $result, $ouput ); 
+		parse_str( $result, $output ); 
@@ -238 +238 @@
-		foreach( $ouput as $k => $v )
+		foreach( $output as $k => $v )
--- ./vendor/hybridauth/Hybrid/Error.php	original
+++ ./vendor/hybridauth/Hybrid/Error.php	fixed
@@ -70 +70 @@
-	* return string detailled error backtrace as string.
+	* return string detailed error backtrace as string.
@@ -78 +78 @@
-	* @return string detailled error backtrace as string.
+	* @return string detailed error backtrace as string.
--- ./vendor/hybridauth/Hybrid/Auth.php	original
+++ ./vendor/hybridauth/Hybrid/Auth.php	fixed
@@ -13 +13 @@
- * Generally, Hybrid_Auth is the only class you should instanciate and use throughout your application.
+ * Generally, Hybrid_Auth is the only class you should instantiate and use throughout your application.
@@ -90 +90 @@
-		// instace of log mng
+		// instance of log mng
@@ -93 +93 @@
-		// instace of errors mng
+		// instance of errors mng
@@ -170 +170 @@
-	* Users sessions are stored using HybridAuth storage system ( HybridAuth 2.0 handle PHP Session only) and can be acessed directly by
+	* Users sessions are stored using HybridAuth storage system ( HybridAuth 2.0 handle PHP Session only) and can be accessed directly by
--- ./vendor/hybridauth/Hybrid/User_Profile.php	original
+++ ./vendor/hybridauth/Hybrid/User_Profile.php	fixed
@@ -31 +31 @@
-	/* User dispalyName provided by the IDp or a concatenation of first and last name. */
+	/* User displayName provided by the IDp or a concatenation of first and last name. */
--- ./vendor/hybridauth/Hybrid/thirdparty/OAuth/OAuth.php	original
+++ ./vendor/hybridauth/Hybrid/thirdparty/OAuth/OAuth.php	fixed
@@ -578 +578 @@
-      // Chapter 7.0 ("Accessing Protected Ressources")
+      // Chapter 7.0 ("Accessing Protected Resources")
@@ -596 +596 @@
-      // According to chapter 7 ("Accessing Protected Ressources") the signature-method
+      // According to chapter 7 ("Accessing Protected Resources") the signature-method
@@ -849 +849 @@
-        // We have already recieved parameter(s) with this name, so add to the list
+        // We have already received parameter(s) with this name, so add to the list
--- ./vendor/hybridauth/Hybrid/Providers/LinkedIn.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/LinkedIn.php	fixed
@@ -52 +52 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid Token.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid Token.", 5 );
@@ -65 +65 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid Token.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid Token.", 5 );
@@ -82 +82 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid Token.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid Token.", 5 );
@@ -103 +103 @@
-				throw new Exception( "User profile request failed! {$this->providerId} returned an invalide xml data.", 6 );
+				throw new Exception( "User profile request failed! {$this->providerId} returned an invalid xml data.", 6 );
--- ./vendor/hybridauth/Hybrid/Providers/Foursquare.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/Foursquare.php	fixed
@@ -38 +38 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
--- ./vendor/hybridauth/Hybrid/Providers/Yahoo.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/Yahoo.php	fixed
@@ -43 +43 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
@@ -232 +232 @@
-			throw new Exception( "User id request failed! {$this->providerId} returned an invalide response." );
+			throw new Exception( "User id request failed! {$this->providerId} returned an invalid response." );
--- ./vendor/hybridauth/Hybrid/Providers/Live.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/Live.php	fixed
@@ -49 +49 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
--- ./vendor/hybridauth/Hybrid/Providers/MySpace.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/MySpace.php	fixed
@@ -37 +37 @@
-			throw new Exception( "User id request failed! {$this->providerId} returned an invalide response." );
+			throw new Exception( "User id request failed! {$this->providerId} returned an invalid response." );
@@ -53 +53 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
@@ -81 +81 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
@@ -137 +137 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
--- ./vendor/hybridauth/Hybrid/Providers/Google.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/Google.php	fixed
@@ -60 +60 @@
-			throw new Exception( "User profile request failed! {$this->providerId} returned an invalide response.", 6 );
+			throw new Exception( "User profile request failed! {$this->providerId} returned an invalid response.", 6 );
--- ./vendor/hybridauth/Hybrid/Provider_Model_OpenID.php	original
+++ ./vendor/hybridauth/Hybrid/Provider_Model_OpenID.php	fixed
@@ -87 +87 @@
-		# if user don't garant acess of their data to your site, halt with an Exception
+		# if user don't garant access of their data to your site, halt with an Exception
@@ -89 +89 @@
-			throw new Exception( "Authentification failed! User has canceled authentication!", 5 );
+			throw new Exception( "Authentication failed! User has canceled authentication!", 5 );
@@ -94 +94 @@
-			throw new Exception( "Authentification failed. Invalid request recived!", 5 );
+			throw new Exception( "Authentication failed. Invalid request received!", 5 );
@@ -97 +97 @@
-		# fetch recived user data
+		# fetch received user data
--- ./vendor/hybridauth/Hybrid/Providers/Facebook.php	original
+++ ./vendor/hybridauth/Hybrid/Providers/Facebook.php	fixed
@@ -80 +80 @@
-			throw new Exception( "Authentification failed! The user denied your request.", 5 );
+			throw new Exception( "Authentication failed! The user denied your request.", 5 );
@@ -85 +85 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalide user id.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid user id.", 5 );
@@ -118 +118 @@
-		// if the provider identifier is not recived, we assume the auth has failed
+		// if the provider identifier is not received, we assume the auth has failed
--- ./vendor/hybridauth/Hybrid/Endpoint.php	original
+++ ./vendor/hybridauth/Hybrid/Endpoint.php	fixed
@@ -129,3 +129,3 @@
-		# if REQUESTed hauth_idprovider is wrong, session not created, etc.
-		if( ! $hauth ) {
-			Hybrid_Logger::error( "Endpoint: Invalide parameter on hauth_start!" );
+		# if REQUESTTed hauth_idprovider is wrong, session not created, etc.
+		if( ! $hauth ) {
+			Hybrid_Logger::error( "Endpoint: Invalid parameter on hauth_start!" );
@@ -134 +134 @@
-			die( "Invalide parameter! Please return to the login page and try again." );
+			die( "Invalid parameter! Please return to the login page and try again." );
@@ -164 +164 @@
-			Hybrid_Logger::error( "Endpoint: Invalide parameter on hauth_done!" );
+			Hybrid_Logger::error( "Endpoint: Invalid parameter on hauth_done!" );
@@ -169 +169 @@
-			die( "Invalide parameter! Please return to the login page and try again." );
+			die( "Invalid parameter! Please return to the login page and try again." );
@@ -184 +184 @@
-		Hybrid_Logger::info( "Endpoint: job done. retrun to callback url." );
+		Hybrid_Logger::info( "Endpoint: job done. return to callback url." );
--- ./vendor/hybridauth/Hybrid/Provider_Model_OAuth2.php	original
+++ ./vendor/hybridauth/Hybrid/Provider_Model_OAuth2.php	fixed
@@ -107 +107 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an error: $error", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an error: $error", 5 );
@@ -110 +110 @@
-		// try to authenicate user
+		// try to authenticate user
@@ -122 +122 @@
-			throw new Exception( "Authentification failed! {$this->providerId} returned an invalid access token.", 5 );
+			throw new Exception( "Authentication failed! {$this->providerId} returned an invalid access token.", 5 );
--- ./vendor/hybridauth/README.html	original
+++ ./vendor/hybridauth/README.html	fixed
@@ -72 +72 @@
-			<b>Hybridauth</b> HybridAuth enable developers to easily build social applications to engage websites vistors and customers on a social level by implementing social signin, social sharing, users profiles, friends list, activities stream, status updates and more.
+			<b>Hybridauth</b> HybridAuth enable developers to easily build social applications to engage websites visitors and customers on a social level by implementing social signin, social sharing, users profiles, friends list, activities stream, status updates and more.
--- ./vendor/hybridauth/Hybrid/Provider_Model.php	original
+++ ./vendor/hybridauth/Hybrid/Provider_Model.php	fixed
@@ -80 +80 @@
-	*     - include some libs nedded by this provider,
+	*     - include some libs needed by this provider,
--- ./vendor/silex/silex/src/Silex/HttpCache.php	original
+++ ./vendor/silex/silex/src/Silex/HttpCache.php	fixed
@@ -27 +27 @@
-     * @param Request $request The Request objet
+     * @param Request $request The Request object
--- ./vendor/igorw/src/Igorw/Silex/Env.php	original
+++ ./vendor/igorw/src/Igorw/Silex/Env.php	fixed
@@ -32 +32 @@
-                if ($envs = $this->atemptRetrieveFromCache()) {
+                if ($envs = $this->attemptRetrieveFromCache()) {
@@ -48 +48 @@
-                                $this->atemptStoreInCache($this->envs);
+                                $this->attemptStoreInCache($this->envs);
@@ -61 +61 @@
-    public function atemptRetrieveFromCache() {
+    public function attemptRetrieveFromCache() {
@@ -69 +69 @@
-    public function atemptStoreInCache($envs) {
+    public function attemptStoreInCache($envs) {
--- ./vendor/igorw/src/Igorw/Silex/Config.php	original
+++ ./vendor/igorw/src/Igorw/Silex/Config.php	fixed
@@ -124 +124 @@
-            // strip posible /**/ comments
+            // strip possible /**/ comments
--- ./webroot/assets/js/vendor/highstock/js/modules/data.src.js	original
+++ ./webroot/assets/js/vendor/highstock/js/modules/data.src.js	fixed
@@ -59 +59 @@
- * A callback function to access the parsed columns, the two-dimentional input data
+ * A callback function to access the parsed columns, the two-dimensional input data
@@ -67 +67 @@
- * The same as the columns input option, but defining rows intead of columns.
+ * The same as the columns input option, but defining rows instead of columns.
@@ -271 +271 @@
-				// Prepare the data from the spreadsheat
+				// Prepare the data from the spreadsheet
--- ./webroot/assets/js/vendor/highstock/js/modules/canvas-tools.js	original
+++ ./webroot/assets/js/vendor/highstock/js/modules/canvas-tools.js	fixed
@@ -23 +23 @@
-gainsboro:"dcdcdc",ghostwhite:"f8f8ff",gold:"ffd700",goldenrod:"daa520",gray:"808080",green:"008000",greenyellow:"adff2f",honeydew:"f0fff0",hotpink:"ff69b4",indianred:"cd5c5c",indigo:"4b0082",ivory:"fffff0",khaki:"f0e68c",lavender:"e6e6fa",lavenderblush:"fff0f5",lawngreen:"7cfc00",lemonchiffon:"fffacd",lightblue:"add8e6",lightcoral:"f08080",lightcyan:"e0ffff",lightgoldenrodyellow:"fafad2",lightgrey:"d3d3d3",lightgreen:"90ee90",lightpink:"ffb6c1",lightsalmon:"ffa07a",lightseagreen:"20b2aa",lightskyblue:"87cefa",
+gainsboro:"dcdcdc",ghostwhite:"f8f8ff",gold:"ffd700",goldenrod:"data520",gray:"808080",green:"008000",greenyellow:"adff2f",honeydew:"f0fff0",hotpink:"ff69b4",indianred:"cd5c5c",indigo:"4b0082",ivory:"fffff0",khaki:"f0e68c",lavender:"e6e6fa",lavenderblush:"fff0f5",lawngreen:"7cfc00",lemonchiffon:"fffacd",lightblue:"add8e6",lightcoral:"f08080",lightcyan:"e0ffff",lightgoldenrodyellow:"fafad2",lightgrey:"d3d3d3",lightgreen:"90ee90",lightpink:"ffb6c1",lightsalmon:"ffa07a",lightseagreen:"20b2aa",lightskyblue:"87cefa",
--- ./webroot/assets/js/vendor/highstock/js/modules/canvas-tools.src.js	original
+++ ./webroot/assets/js/vendor/highstock/js/modules/canvas-tools.src.js	fixed
@@ -73 +73 @@
-        goldenrod: 'daa520',
+        goldenrod: 'data520',
@@ -2972 +2972 @@
-			// the container (and as direct childs to the div specified in the html page)
+			// the container (and as direct children to the div specified in the html page)
@@ -3106 +3106 @@
-		 * Draws the SVG on the canvas or adds a draw invokation to the deferred list.
+		 * Draws the SVG on the canvas or adds a draw invocation to the deferred list.
--- ./webroot/assets/js/vendor/highstock/js/modules/map.src.js	original
+++ ./webroot/assets/js/vendor/highstock/js/modules/map.src.js	fixed
@@ -433 +433 @@
-		 * In choropleth maps, the color is a result of the value, so this needs translation tood
+		 * In choropleth maps, the color is a result of the value, so this needs translation todo
--- ./webroot/assets/js/vendor/highstock/js/modules/exporting.src.js	original
+++ ./webroot/assets/js/vendor/highstock/js/modules/exporting.src.js	fixed
@@ -249,5 +249,5 @@
-		each(chart.series, function (serie) {
-			seriesOptions = merge(serie.options, {
-				animation: false, // turn off animation
-				showCheckbox: false,
-				visible: serie.visible
+		each(chart.series, function (series) {
+			seriesOptions = merge(series.options, {
+				animation: false, // turn off animation
+				showCheckbox: false,
+				visible: series.visible
--- ./webroot/assets/js/vendor/highstock/js/adapters/mootools-adapter.src.js	original
+++ ./webroot/assets/js/vendor/highstock/js/adapters/mootools-adapter.src.js	fixed
@@ -240 +240 @@
-			// el.removeEvents below apperantly calls this method again. Do not quite understand why, so for now just bail out.
+			// el.removeEvents below apparently calls this method again. Do not quite understand why, so for now just bail out.
--- ./webroot/assets/js/vendor/highstock/exporting-server/phantomjs/highcharts-convert.js	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/phantomjs/highcharts-convert.js	fixed
@@ -26 +26 @@
-			TIMEOUT: 2000 /* 2 seconds timout for loading images */
+			TIMEOUT: 2000 /* 2 seconds timeout for loading images */
@@ -395 +395 @@
-			// check if witdh is set. Order of precedence:
+			// check if width is set. Order of precedence:
--- ./webroot/assets/js/vendor/highstock/exporting-server/phantomjs/readme.md	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/phantomjs/readme.md	fixed
@@ -34 +34 @@
-**-host** The hostname Phantomjs is listening to for POST-requests. If this parameter is specified, phantomjs startsup as Http-server.
+**-host** The hostname Phantomjs is listening to for POST-requests. If this parameter is specified, phantomjs startups as Http-server.
--- ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-web/target/highcharts-export-web/resources/lib/codemirror/util/javascript-hint.js	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-web/target/highcharts-export-web/resources/lib/codemirror/util/javascript-hint.js	fixed
@@ -63 +63 @@
-  // type and treat "." as indepenent token.
+  // type and treat "." as independent token.
--- ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-web/src/main/java/com/highcharts/export/controller/ExportController.java	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-web/src/main/java/com/highcharts/export/controller/ExportController.java	fixed
@@ -124 +124 @@
-		logger.debug(request.getHeader("referer") + " Total time: " + (System.currentTimeMillis() - start1));
+		logger.debug(request.getHeader("referrer") + " Total time: " + (System.currentTimeMillis() - start1));
--- ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-web/src/main/webapp/resources/lib/codemirror/util/javascript-hint.js	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-web/src/main/webapp/resources/lib/codemirror/util/javascript-hint.js	fixed
@@ -63 +63 @@
-  // type and treat "." as indepenent token.
+  // type and treat "." as independent token.
--- ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-convert/target/classes/phantomjs/highcharts-convert.js	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-convert/target/classes/phantomjs/highcharts-convert.js	fixed
@@ -26 +26 @@
-			TIMEOUT: 2000 /* 2 seconds timout for loading images */
+			TIMEOUT: 2000 /* 2 seconds timeout for loading images */
@@ -395 +395 @@
-			// check if witdh is set. Order of precedence:
+			// check if width is set. Order of precedence:
@@ -468 +468 @@
-			if (input === undefined || input.lenght === 0) {
+			if (input === undefined || input.length === 0) {
--- ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-convert/src/main/resources/phantomjs/highcharts-convert.js	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-convert/src/main/resources/phantomjs/highcharts-convert.js	fixed
@@ -26 +26 @@
-			TIMEOUT: 2000 /* 2 seconds timout for loading images */
+			TIMEOUT: 2000 /* 2 seconds timeout for loading images */
@@ -395 +395 @@
-			// check if witdh is set. Order of precedence:
+			// check if width is set. Order of precedence:
@@ -468 +468 @@
-			if (input === undefined || input.lenght === 0) {
+			if (input === undefined || input.length === 0) {
--- ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-convert/src/main/java/com/highcharts/export/server/Server.java	original
+++ ./webroot/assets/js/vendor/highstock/exporting-server/java/highcharts-export/highcharts-export-convert/src/main/java/com/highcharts/export/server/Server.java	fixed
@@ -60 +60 @@
-				throw new RuntimeException("Error, PhantomJS couldnot start");
+				throw new RuntimeException("Error, PhantomJS couldnt start");
--- ./webroot/assets/js/vendor/localforage.js	original
+++ ./webroot/assets/js/vendor/localforage.js	fixed
@@ -768 +768 @@
-            // Conver the blob to a binaryArray and then to a string.
+            // Convert the blob to a binaryArray and then to a string.
@@ -842 +842 @@
-                throw new Error('Unkown type: ' + type);
+                throw new Error('Unknown type: ' + type);
--- ./webroot/assets/js/chart.js	original
+++ ./webroot/assets/js/chart.js	fixed
@@ -107,3 +107,3 @@
-        $.each(data, function(k, serie) {
-            if (serie.type == 'column') {
-                $.extend(true, serie, {
+        $.each(data, function(k, series) {
+            if (series.type == 'column') {
+                $.extend(true, series, {
--- ./controllers/security.php	original
+++ ./controllers/security.php	fixed
@@ -35 +35 @@
- *  end point for the hybridauth lib to recieve callbacks on
+ *  end point for the hybridauth lib to receive callbacks on
--- ./controllers/watchlist.php	original
+++ ./controllers/watchlist.php	fixed
@@ -28 +28 @@
-    $uri = $request->headers->get('referer');
+    $uri = $request->headers->get('referrer');
--- ./src/GW2Spidy/Dataset/GemDatasetCleaner.php	original
+++ ./src/GW2Spidy/Dataset/GemDatasetCleaner.php	fixed
@@ -17 +17 @@
-     * different posible type of datasets we can have
+     * different possible type of datasets we can have
--- ./src/GW2Spidy/Dataset/BaseDataset.php	original
+++ ./src/GW2Spidy/Dataset/BaseDataset.php	fixed
@@ -29 +29 @@
-     * boolean to check weither or not the dataset is completely up-to-date
+     * boolean to check whether or not the dataset is completely up-to-date
@@ -81 +81 @@
-     *  if posible only with values since our lastUpdated moment
+     *  if possible only with values since our lastUpdated moment
--- ./src/GW2Spidy/Dataset/ItemDatasetCleaner.php	original
+++ ./src/GW2Spidy/Dataset/ItemDatasetCleaner.php	fixed
@@ -13 +13 @@
-     * different posible type of datasets we can have
+     * different possible type of datasets we can have
--- ./src/GW2Spidy/Dataset/ItemDataset.php	original
+++ ./src/GW2Spidy/Dataset/ItemDataset.php	fixed
@@ -11 +11 @@
-     * different posible type of datasets we can have
+     * different possible type of datasets we can have
@@ -38 +38 @@
-     *  if posible only with values since our lastUpdated moment
+     *  if possible only with values since our lastUpdated moment
--- ./src/GW2Spidy/Dataset/GemExchangeDataset.php	original
+++ ./src/GW2Spidy/Dataset/GemExchangeDataset.php	fixed
@@ -11 +11 @@
-     * different posible type of datasets we can have
+     * different possible type of datasets we can have
@@ -31 +31 @@
-     *  if posible only with values since our lastUpdated moment
+     *  if possible only with values since our lastUpdated moment
--- ./src/GW2Spidy/Dataset/ItemVolumeDataset.php	original
+++ ./src/GW2Spidy/Dataset/ItemVolumeDataset.php	fixed
@@ -12 +12 @@
-     *  if posible only with values since our lastUpdated moment
+     *  if possible only with values since our lastUpdated moment
--- ./src/GW2Spidy/DB/om/BaseBuyListingQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseBuyListingQuery.php	fixed
@@ -72 +72 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -125 +125 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseSellListing.php	original
+++ ./src/GW2Spidy/DB/om/BaseSellListing.php	fixed
@@ -49 +49 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -560 +560 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -738 +738 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -750 +750 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseWatchlistQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseWatchlistQuery.php	fixed
@@ -65 +65 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -118 +118 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseGW2SessionQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseGW2SessionQuery.php	fixed
@@ -58 +58 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -111 +111 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseDisciplineQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseDisciplineQuery.php	fixed
@@ -56 +56 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -109 +109 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseSellListingQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseSellListingQuery.php	fixed
@@ -72 +72 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -125 +125 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseGemToGoldRate.php	original
+++ ./src/GW2Spidy/DB/om/BaseGemToGoldRate.php	fixed
@@ -47 +47 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -565 +565 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
--- ./src/GW2Spidy/DB/om/BaseRecipe.php	original
+++ ./src/GW2Spidy/DB/om/BaseRecipe.php	fixed
@@ -53 +53 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -875 +875 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -1122 +1122 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -1134 +1134 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseGoldToGemRate.php	original
+++ ./src/GW2Spidy/DB/om/BaseGoldToGemRate.php	fixed
@@ -47 +47 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -565 +565 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
--- ./src/GW2Spidy/DB/om/BaseItem.php	original
+++ ./src/GW2Spidy/DB/om/BaseItem.php	fixed
@@ -63 +63 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -1548 +1548 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -1968 +1968 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -1980 +1980 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseItemQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseItemQuery.php	fixed
@@ -183 +183 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -236 +236 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseUser.php	original
+++ ./src/GW2Spidy/DB/om/BaseUser.php	fixed
@@ -48 +48 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -868 +868 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
--- ./src/GW2Spidy/DB/om/BaseItemTypeQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseItemTypeQuery.php	fixed
@@ -61 +61 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -114 +114 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseGoldToGemRateQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseGoldToGemRateQuery.php	fixed
@@ -54 +54 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -107 +107 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseBuyListing.php	original
+++ ./src/GW2Spidy/DB/om/BaseBuyListing.php	fixed
@@ -49 +49 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -560 +560 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -738 +738 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -750 +750 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseDiscipline.php	original
+++ ./src/GW2Spidy/DB/om/BaseDiscipline.php	fixed
@@ -46 +46 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -522 +522 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
--- ./src/GW2Spidy/DB/om/BaseItemSubType.php	original
+++ ./src/GW2Spidy/DB/om/BaseItemSubType.php	fixed
@@ -48 +48 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -427 +427 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -594 +594 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -606 +606 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseRecipeQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseRecipeQuery.php	fixed
@@ -106 +106 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -159 +159 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseWatchlist.php	original
+++ ./src/GW2Spidy/DB/om/BaseWatchlist.php	fixed
@@ -48 +48 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -426 +426 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -593 +593 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -605 +605 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseItemType.php	original
+++ ./src/GW2Spidy/DB/om/BaseItemType.php	fixed
@@ -48 +48 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -555 +555 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
--- ./src/GW2Spidy/DB/om/BaseGW2Session.php	original
+++ ./src/GW2Spidy/DB/om/BaseGW2Session.php	fixed
@@ -47 +47 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -618 +618 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
--- ./src/GW2Spidy/DB/om/BaseRecipeIngredient.php	original
+++ ./src/GW2Spidy/DB/om/BaseRecipeIngredient.php	fixed
@@ -48 +48 @@
-     * The flag var to prevent infinit loop in deep copy
+     * The flag var to prevent infinite loop in deep copy
@@ -452 +452 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
@@ -608 +608 @@
-     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objets otherwise.
+     * @return mixed <code>true</code> if all validations pass; array of <code>ValidationFailed</code> objects otherwise.
@@ -620 +620 @@
-            // were passed to this object by their coresponding set
+            // were passed to this object by their corresponding set
--- ./src/GW2Spidy/DB/om/BaseUserQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseUserQuery.php	fixed
@@ -81 +81 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -134 +134 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseGemToGoldRateQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseGemToGoldRateQuery.php	fixed
@@ -54 +54 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -107 +107 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseRecipeIngredientQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseRecipeIngredientQuery.php	fixed
@@ -65 +65 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -119 +119 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/DB/om/BaseItemSubTypeQuery.php	original
+++ ./src/GW2Spidy/DB/om/BaseItemSubTypeQuery.php	fixed
@@ -65 +65 @@
-     * @param     string $dbName The dabase name
+     * @param     string $dbName The database name
@@ -119 +119 @@
-            // the object is alredy in the instance pool
+            // the object is already in the instance pool
--- ./src/GW2Spidy/Util/CurlRequest.php	original
+++ ./src/GW2Spidy/Util/CurlRequest.php	fixed
@@ -12 +12 @@
-    protected $urlAsReferer = true;
+    protected $urlAsReferrer = true;
@@ -139,2 +139,2 @@
-        if ($this->urlAsReferer) {
-            $options[CURLOPT_REFERER] =  $this->url;
+        if ($this->urlAsReferrer) {
+            $options[CURLOPT_REFERRER] =  $this->url;
@@ -166 +166 @@
-            // retrieve body string based on reponse info
+            // retrieve body string based on response info
@@ -169 +169 @@
-            // retrieve header string based on reponse info
+            // retrieve header string based on response info
--- ./src/GW2Spidy/GW2API/APIItemV2.php	original
+++ ./src/GW2Spidy/GW2API/APIItemV2.php	fixed
@@ -80 +80 @@
-                    // - supress and short sleep
+                    // - suppress and short sleep
--- ./src/GW2Spidy/GW2API/APIItem.php	original
+++ ./src/GW2Spidy/GW2API/APIItem.php	fixed
@@ -99 +99 @@
-                    // - supress and short sleep
+                    // - suppress and short sleep
--- ./README.md	original
+++ ./README.md	fixed
@@ -113 +113 @@
-Install Node.js via the usual installation mechanism for your OS. Afterwards run `npm insall -g grunt` to globally install
+Install Node.js via the usual installation mechanism for your OS. Afterwards run `npm install -g grunt` to globally install
@@ -220 +220 @@
-The amount of requests we do are limited by our requestslot system, unfortunatly we're now bound by doing 1 item per request
+The amount of requests we do are limited by our requestslot system, unfortunately we're now bound by doing 1 item per request
@@ -240 +240 @@
-You can intercept the session_key by either using Fiddle2r to intercept the HTTPS trafic or using some custom tools to grab the URLs from share memory ...  
+You can intercept the session_key by either using Fiddle2r to intercept the HTTPS traffic or using some custom tools to grab the URLs from share memory ...  
@@ -246 +246 @@
-I do have a small tool (provided by someone else) that quickly grabs the session_key (by seaching for it in shared memory) without much hassle, I won't be sharing it publicly but you could consider joining the IRC channel and asking for it ;)
+I do have a small tool (provided by someone else) that quickly grabs the session_key (by searching for it in shared memory) without much hassle, I won't be sharing it publicly but you could consider joining the IRC channel and asking for it ;)
@@ -278,5 +278,5 @@
-Copyright and License - Apendix
-===============================
-The above BSD license will allow you to use this open source project for anything you like.  
-However, I would very much appreciate it when you decide to use the code if you could contribute your improvements back to this project
-and / or contact me so that I'm aware (and proud) of my project being used by other people too :-)
+Copyright and License - Appendix
+===============================
+The above BSD license will allow you to use this open source project for anything you like.  
+However, I would very much appreciate it when you decide to use the code if you could contribute your improvements back to this project
+and / or contact me so that I'm aware (and proud) of my project being used by other people too :-)
--- ./templates/item_list.html.twig	original
+++ ./templates/item_list.html.twig	fixed
@@ -21 +21 @@
-        calculate how many pages we can display before and after the curently active page
+        calculate how many pages we can display before and after the currently active page
--- ./templates/recipe_list.html.twig	original
+++ ./templates/recipe_list.html.twig	fixed
@@ -18 +18 @@
-        calculate how many pages we can display before and after the curently active page
+        calculate how many pages we can display before and after the currently active page
--- ./tools/redis-cache-benchmark.php	original
+++ ./tools/redis-cache-benchmark.php	fixed
@@ -15,2 +15,2 @@
-$oSerAndG = RedisCacheHandler::getInstance('ser_and_g', true,  0, true);
-$oSerNoG  = RedisCacheHandler::getInstance('ser_no_g',  true,  0, false);
+$oSetAndG = RedisCacheHandler::getInstance('set_and_g', true,  0, true);
+$oSetNoG  = RedisCacheHandler::getInstance('set_no_g',  true,  0, false);
@@ -19,2 +19,2 @@
-$sSerAndG = $oSerAndG->prepareValue($data);
-$sSerNoG = $oSerNoG->prepareValue($data);
+$sSetAndG = $oSetAndG->prepareValue($data);
+$sSetNoG = $oSetNoG->prepareValue($data);
@@ -23,2 +23,2 @@
-echo "with gzip length    [[ " . strlen($sSerAndG) . " ]] \n";
-echo "without gzip length [[ " .  strlen($sSerNoG) . " ]] \n";
+echo "with gzip length    [[ " . strlen($sSetAndG) . " ]] \n";
+echo "without gzip length [[ " .  strlen($sSetNoG) . " ]] \n";
@@ -29 +29 @@
-    $oSerAndG->prepareValue($data);
+    $oSetAndG->prepareValue($data);
@@ -31 +31 @@
-$iSerAndG = microtime(true) - $time;
+$iSetAndG = microtime(true) - $time;
@@ -35 +35 @@
-    $oSerNoG->prepareValue($data);
+    $oSetNoG->prepareValue($data);
@@ -37 +37 @@
-$iSerNoG = microtime(true) - $time;
+$iSetNoG = microtime(true) - $time;
@@ -46,2 +46,2 @@
-echo "with gzip time    [[ " .  $iSerAndG . " ]] avg [[ " .  $iSerAndG / $loops . " ]] \n";
-echo "without gzip time [[ " .  $iSerNoG .  " ]] avg [[ " .  $iSerNoG / $loops .  " ]] \n";
+echo "with gzip time    [[ " .  $iSetAndG . " ]] avg [[ " .  $iSetAndG / $loops . " ]] \n";
+echo "without gzip time [[ " .  $iSetNoG .  " ]] avg [[ " .  $iSetNoG / $loops .  " ]] \n";
@@ -52 +52 @@
-    $oSerAndG->returnValue($sSerAndG);
+    $oSetAndG->returnValue($sSetAndG);
@@ -54 +54 @@
-$iSerAndG = microtime(true) - $time;
+$iSetAndG = microtime(true) - $time;
@@ -58 +58 @@
-    $oSerAndG->returnValue($sSerNoG);
+    $oSetAndG->returnValue($sSetNoG);
@@ -60 +60 @@
-$iSerNoG = microtime(true) - $time;
+$iSetNoG = microtime(true) - $time;
@@ -69,2 +69,2 @@
-echo "with gzip time    [[ " .  $iSerAndG . " ]] avg [[ " .  $iSerAndG / $loops . " ]] \n";
-echo "without gzip time [[ " .  $iSerNoG .  " ]] avg [[ " .  $iSerNoG / $loops .  " ]] \n";
+echo "with gzip time    [[ " .  $iSetAndG . " ]] avg [[ " .  $iSetAndG / $loops . " ]] \n";
+echo "without gzip time [[ " .  $iSetNoG .  " ]] avg [[ " .  $iSetNoG / $loops .  " ]] \n";
--- ./tools/import-karma-from-wiki.php	original
+++ ./tools/import-karma-from-wiki.php	fixed
@@ -232 +232 @@
-    "Tomatoe"       => "Tomato",
+    "Tomato"       => "Tomato",
--- ./webroot/assets/js/vendor/highstock/js/highstock.src.js	original
+++ ./webroot/assets/js/vendor/highstock/js/highstock.src.js	fixed
@@ -248 +248 @@
- * Remove last occurence of an item from an array
+ * Remove last occurrence of an item from an array
@@ -444 +444 @@
-		key, // used in for constuct below
+		key, // used in for construct below
@@ -825 +825 @@
- * Helper class that contains variuos counters that are local to the chart.
+ * Helper class that contains various counters that are local to the chart.
@@ -2741 +2741 @@
-		// First call on instanciate
+		// First call on instantiate
@@ -3122 +3122 @@
-				.replace(/([\('\)])/g, '\\$1') // escape parantheses and quotes
+				.replace(/([\('\)])/g, '\\$1') // escape parentheses and quotes
@@ -3438 +3438 @@
-		// Add the events. IE9 and IE10 need mouseover and mouseout to funciton (#667).
+		// Add the events. IE9 and IE10 need mouseover and mouseout to function (#667).
@@ -3478 +3478 @@
-			// Substract due to #1129. Now bottom and left axis gridlines behave the same.
+			// Subtract due to #1129. Now bottom and left axis gridlines behave the same.
@@ -3647 +3647 @@
-			// using href throws "not supported" in ie7 and under, requries regex shim to fix later
+			// using href throws "not supported" in ie7 and under, requires regex shim to fix later
@@ -4273 +4273 @@
-			// determin y based on the baseline
+			// determine y based on the baseline
@@ -4358 +4358 @@
-		// change local variable and set attribue as well
+		// change local variable and set attribute as well
@@ -4669 +4669 @@
-							// Substracting half a pixel seems to make the coordinates
+							// Subtracting half a pixel seems to make the coordinates
@@ -4679 +4679 @@
-								// they are rounded to the same value above. In this case, substract 1 from the end X
+								// they are rounded to the same value above. In this case, subtract 1 from the end X
@@ -5654 +5654 @@
-		// List of renderering calls
+		// List of rendering calls
@@ -6317 +6317 @@
-	 * Sets the total of this stack. Should be called when a serie is hidden or shown
+	 * Sets the total of this stack. Should be called when a series is hidden or shown
@@ -6342 +6342 @@
-		// Change the text to reflect the new total and set visibility to hidden in case the serie is hidden
+		// Change the text to reflect the new total and set visibility to hidden in case the series is hidden
@@ -7015 +7015 @@
-	 * @param {Boolean} paneCoordiantes Whether the input pixel is relative to the chart or just the
+	 * @param {Boolean} paneCoordinates Whether the input pixel is relative to the chart or just the
@@ -7320 +7320 @@
-			if (spaceAvailable) { // if space is availabe, stay within the data range
+			if (spaceAvailable) { // if space is available, stay within the data range
@@ -7502 +7502 @@
-				categories ? // for categoried axis, 1 is default, for linear axis use tickPix
+				categories ? // for categorized axis, 1 is default, for linear axis use tickPix
@@ -10182,2 +10182,2 @@
-		each(chart.series, function (serie) {
-			var seriesOptions = serie.options;
+		each(chart.series, function (series) {
+			var seriesOptions = series.options;
@@ -10191,4 +10191,4 @@
-					serie.legendItems ||
-					(seriesOptions.legendType === 'point' ?
-							serie.data :
-							serie)
+					series.legendItems ||
+					(seriesOptions.legendType === 'point' ?
+							series.data :
+							series)
@@ -10670 +10670 @@
-			serie,
+			series,
@@ -10686 +10686 @@
-			serie = series[i];
+			series = series[i];
@@ -10688,4 +10688,4 @@
-			if (serie.options.stacking) {
-				hasStackedSeries = true;
-				
-				if (serie.isDirty) {
+			if (series.options.stacking) {
+				hasStackedSeries = true;
+				
+				if (series.isDirty) {
@@ -10700,3 +10700,3 @@
-				serie = series[i];
-				if (serie.options.stacking) {
-					serie.isDirty = true;
+				series = series[i];
+				if (series.options.stacking) {
+					series.isDirty = true;
@@ -10708,3 +10708,3 @@
-		each(series, function (serie) {
-			if (serie.isDirty) { // prepare the data so axis can read it
-				if (serie.options.legendType === 'point') {
+		each(series, function (series) {
+			if (series.isDirty) { // prepare the data so axis can read it
+				if (series.options.legendType === 'point') {
@@ -10771,4 +10771,4 @@
-		each(series, function (serie) {
-			if (serie.isDirty && serie.visible &&
-					(!serie.isCartesian || serie.xAxis)) { // issue #153
-				serie.redraw();
+		each(series, function (series) {
+			if (series.isDirty && series.visible &&
+					(!series.isCartesian || series.xAxis)) { // issue #153
+				series.redraw();
@@ -10948,2 +10948,2 @@
-		each(this.series, function (serie) {
-			points = points.concat(grep(serie.points || [], function (point) {
+		each(this.series, function (series) {
+			points = points.concat(grep(series.points || [], function (point) {
@@ -10960,2 +10960,2 @@
-		return grep(this.series, function (serie) {
-			return serie.selected;
+		return grep(this.series, function (series) {
+			return series.selected;
@@ -11509,2 +11509,2 @@
-		each(chart.series, function (serie) {
-			serie.isDirty = true;
+		each(chart.series, function (series) {
+			series.isDirty = true;
@@ -11821,4 +11821,4 @@
-		each(chart.series, function (serie) {
-			serie.translate();
-			serie.setTooltipPoints();
-			serie.render();
+		each(chart.series, function (series) {
+			series.translate();
+			series.setTooltipPoints();
+			series.render();
@@ -11997,2 +11997,2 @@
-		each(options.series || [], function (serieOptions) {
-			chart.initSeries(serieOptions);
+		each(options.series || [], function (seriesOptions) {
+			chart.initSeries(seriesOptions);
@@ -12227 +12227 @@
-		// fire the event with the defalut handler
+		// fire the event with the default handler
@@ -12796 +12796 @@
-		// Delte marker object if not allowed (#1125)
+		// Delete marker object if not allowed (#1125)
@@ -12853 +12853 @@
-		// don't substract radius in image symbols (#604)
+		// don't subtract radius in image symbols (#604)
@@ -13303 +13303 @@
-		// swithching view from non-grouped data to grouped data (#637)	
+		// switching view from non-grouped data to grouped data (#637)	
@@ -13977 +13977 @@
-		// options are given. If not, create a referance to the series wide point
+		// options are given. If not, create a reference to the series wide point
@@ -16190 +16190 @@
-			// if the point is sliced, use special translation, else use plot area traslation
+			// if the point is sliced, use special translation, else use plot area translation
@@ -16413 +16413 @@
-					// if the slot next to currrent slot is free, the y value is allowed
+					// if the slot next to current slot is free, the y value is allowed
@@ -18983 +18983 @@
-		if (!baseAxis) { // axis not yet instanciated
+		if (!baseAxis) { // axis not yet instantiated
@@ -20067 +20067 @@
-			 * In an ordinal axis, there might be areas with dense consentrations of points, then large
+			 * In an ordinal axis, there might be areas with dense concentrations of points, then large
@@ -20227 +20227 @@
-			 * Overrride the chart.pan method for ordinal axes. 
+			 * Override the chart.pan method for ordinal axes. 
