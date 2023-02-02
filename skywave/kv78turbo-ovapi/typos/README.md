## Detected Typos Diff
```diff
--- ./wordforms.txt	original
+++ ./wordforms.txt	fixed
@@ -15 +15 @@
-Adm. > admiraal
+Adm. > admiral
--- ./sphinx.conf	original
+++ ./sphinx.conf	fixed
@@ -294 +294 @@
-	# requires searchd to be run from root
+	# requires searched to be run from root
@@ -437 +437 @@
-	# optional, default is 0 (do not preopen), searchd-only
+	# optional, default is 0 (do not preopen), searched-only
@@ -443 +443 @@
-	# optional, default is 0 (cache in RAM), searchd-only
+	# optional, default is 0 (cache in RAM), searched-only
@@ -497,58 +497,58 @@
-    U+013A->l, U+013B->l, U+013C->l, U+013D->l, U+013E->l, U+013F->l, U+0140->l, U+0141->l, U+0142->l, U+019A->l, U+01C8->l, U+0234->l, U+023D->l, U+026B->l, U+026C->l, U+026D->l, U+029F->l, U+02E1->l, U+1D0C->l, U+1D38->l, U+1D85->l, U+1DA9->l, U+1DAA->l,  \
-    U+1DAB->l, U+1E36->l, U+1E37->l, U+1E38->l, U+1E39->l, U+1E3A->l, U+1E3B->l, U+1E3C->l, U+1E3D->l, U+2C60->l, U+2C61->l, U+2C62->l, U+019C->m, U+026F->m, U+0270->m, U+0271->m, U+1D0D->m, U+1D1F->m, U+1D39->m, U+1D50->m, U+1D5A->m, U+1D6F->m, U+1D86->m,  \
-    U+1DAC->m, U+1DAD->m, U+1E3E->m, U+1E3F->m, U+1E40->m, U+1E41->m, U+1E42->m, U+1E43->m, U+00D1->n, U+00F1->n, U+0143->n, U+0144->n, U+0145->n, U+0146->n, U+0147->n, U+0148->n, U+0149->n, U+019D->n, U+019E->n, U+01CB->n, U+01F8->n, U+01F9->n, U+0220->n,  \
-    U+0235->n, U+0272->n, U+0273->n, U+0274->n, U+1D0E->n, U+1D3A->n, U+1D3B->n, U+1D70->n, U+1D87->n, U+1DAE->n, U+1DAF->n, U+1DB0->n, U+1E44->n, U+1E45->n, U+1E46->n, U+1E47->n, U+1E48->n, U+1E49->n, U+1E4A->n, U+1E4B->n, U+207F->n, U+00D2->o, U+00D3->o,  \
-    U+00D4->o, U+00D5->o, U+00D6->o, U+00D8->o, U+00F2->o, U+00F3->o, U+00F4->o, U+00F5->o, U+00F6->o, U+00F8->o, U+01030F->o, U+014C->o, U+014D->o, U+014E->o, U+014F->o, U+0150->o, U+0151->o, U+0186->o, U+019F->o, U+01A0->o, U+01A1->o, U+01D1->o, U+01D2->o,  \
-    U+01EA->o, U+01EB->o, U+01EC->o, U+01ED->o, U+01FE->o, U+01FF->o, U+020C->o, U+020D->o, U+020E->o, U+020F->o, U+022A->o, U+022B->o, U+022C->o, U+022D->o, U+022E->o, U+022F->o, U+0230->o, U+0231->o, U+0254->o, U+0275->o, U+043E->o, U+04E6->o, U+04E7->o,  \
-    U+04E8->o, U+04E9->o, U+04EA->o, U+04EB->o, U+1D0F->o, U+1D10->o, U+1D11->o, U+1D12->o, U+1D13->o, U+1D16->o, U+1D17->o, U+1D3C->o, U+1D52->o, U+1D53->o, U+1D54->o, U+1D55->o, U+1D97->o, U+1DB1->o, U+1E4C->o, U+1E4D->o, U+1E4E->o, U+1E4F->o, U+1E50->o,  \
-    U+1E51->o, U+1E52->o, U+1E53->o, U+1ECC->o, U+1ECD->o, U+1ECE->o, U+1ECF->o, U+1ED0->o, U+1ED1->o, U+1ED2->o, U+1ED3->o, U+1ED4->o, U+1ED5->o, U+1ED6->o, U+1ED7->o, U+1ED8->o, U+1ED9->o, U+1EDA->o, U+1EDB->o, U+1EDC->o, U+1EDD->o, U+1EDE->o, U+1EDF->o,  \
-    U+1EE0->o, U+1EE1->o, U+1EE2->o, U+1EE3->o, U+2092->o, U+2C9E->o, U+2C9F->o, U+01A4->p, U+01A5->p, U+1D18->p, U+1D3E->p, U+1D56->p, U+1D71->p, U+1D7D->p, U+1D88->p, U+1E54->p, U+1E55->p, U+1E56->p, U+1E57->p, U+2C63->p, U+024A->q, U+024B->q, U+02A0->q,  \
-    U+0154->r, U+0155->r, U+0156->r, U+0157->r, U+0158->r, U+0159->r, U+0210->r, U+0211->r, U+0212->r, U+0213->r, U+024C->r, U+024D->r, U+0279->r, U+027A->r, U+027B->r, U+027C->r, U+027D->r, U+027E->r, U+027F->r, U+0280->r, U+0281->r, U+02B3->r, U+02B4->r,  \
-    U+02B5->r, U+02B6->r, U+1D19->r, U+1D1A->r, U+1D3F->r, U+1D63->r, U+1D72->r, U+1D73->r, U+1D89->r, U+1DCA->r, U+1E58->r, U+1E59->r, U+1E5A->r, U+1E5B->r, U+1E5C->r, U+1E5D->r, U+1E5E->r, U+1E5F->r, U+211C->r, U+2C64->r, U+00DF->s, U+015A->s, U+015B->s,  \
-    U+015C->s, U+015D->s, U+015E->s, U+015F->s, U+0160->s, U+0161->s, U+017F->s, U+0218->s, U+0219->s, U+023F->s, U+0282->s, U+02E2->s, U+1D74->s, U+1D8A->s, U+1DB3->s, U+1E60->s, U+1E61->s, U+1E62->s, U+1E63->s, U+1E64->s, U+1E65->s, U+1E66->s, U+1E67->s,  \
-    U+1E68->s, U+1E69->s, U+1E9B->s, U+0162->t, U+0163->t, U+0164->t, U+0165->t, U+0166->t, U+0167->t, U+01AB->t, U+01AC->t, U+01AD->t, U+01AE->t, U+021A->t, U+021B->t, U+0236->t, U+023E->t, U+0287->t, U+0288->t, U+1D1B->t, U+1D40->t, U+1D57->t, U+1D75->t,  \
-    U+1DB5->t, U+1E6A->t, U+1E6B->t, U+1E6C->t, U+1E6D->t, U+1E6E->t, U+1E6F->t, U+1E70->t, U+1E71->t, U+1E97->t, U+2C66->t, U+00D9->u, U+00DA->u, U+00DB->u, U+00DC->u, U+00F9->u, U+00FA->u, U+00FB->u, U+00FC->u, U+010316->u, U+0168->u, U+0169->u, U+016A->u,  \
-    U+016B->u, U+016C->u, U+016D->u, U+016E->u, U+016F->u, U+0170->u, U+0171->u, U+0172->u, U+0173->u, U+01AF->u, U+01B0->u, U+01D3->u, U+01D4->u, U+01D5->u, U+01D6->u, U+01D7->u, U+01D8->u, U+01D9->u, U+01DA->u, U+01DB->u, U+01DC->u, U+0214->u, U+0215->u,  \
-    U+0216->u, U+0217->u, U+0244->u, U+0289->u, U+1D1C->u, U+1D1D->u, U+1D1E->u, U+1D41->u, U+1D58->u, U+1D59->u, U+1D64->u, U+1D7E->u, U+1D99->u, U+1DB6->u, U+1DB8->u, U+1E72->u, U+1E73->u, U+1E74->u, U+1E75->u, U+1E76->u, U+1E77->u, U+1E78->u, U+1E79->u,  \
-    U+1E7A->u, U+1E7B->u, U+1EE4->u, U+1EE5->u, U+1EE6->u, U+1EE7->u, U+1EE8->u, U+1EE9->u, U+1EEA->u, U+1EEB->u, U+1EEC->u, U+1EED->u, U+1EEE->u, U+1EEF->u, U+1EF0->u, U+1EF1->u, U+01B2->v, U+0245->v, U+028B->v, U+028C->v, U+1D20->v, U+1D5B->v, U+1D65->v,  \
-    U+1D8C->v, U+1DB9->v, U+1DBA->v, U+1E7C->v, U+1E7D->v, U+1E7E->v, U+1E7F->v, U+2C74->v, U+0174->w, U+0175->w, U+028D->w, U+02B7->w, U+1D21->w, U+1D42->w, U+1E80->w, U+1E81->w, U+1E82->w, U+1E83->w, U+1E84->w, U+1E85->w, U+1E86->w, U+1E87->w, U+1E88->w,  \
-    U+1E89->w, U+1E98->w, U+02E3->x, U+1D8D->x, U+1E8A->x, U+1E8B->x, U+1E8C->x, U+1E8D->x, U+2093->x, U+00DD->y, U+00FD->y, U+00FF->y, U+0176->y, U+0177->y, U+0178->y, U+01B3->y, U+01B4->y, U+0232->y, U+0233->y, U+024E->y, U+024F->y, U+028E->y, U+028F->y,  \
-    U+02B8->y, U+1E8E->y, U+1E8F->y, U+1E99->y, U+1EF2->y, U+1EF3->y, U+1EF4->y, U+1EF5->y, U+1EF6->y, U+1EF7->y, U+1EF8->y, U+1EF9->y, U+0179->z, U+017A->z, U+017B->z, U+017C->z, U+017D->z, U+017E->z, U+01B5->z, U+01B6->z, U+0224->z, U+0225->z, U+0240->z,  \
-    U+0290->z, U+0291->z, U+1D22->z, U+1D76->z, U+1D8E->z, U+1DBB->z, U+1DBC->z, U+1DBD->z, U+1E90->z, U+1E91->z, U+1E92->z, U+1E93->z, U+1E94->z, U+1E95->z, U+2128->z, U+2C6B->z, U+2C6C->z, U+00C6->U+00E6, U+01E2->U+00E6, U+01E3->U+00E6, U+01FC->U+00E6,  \
-    U+01FD->U+00E6, U+1D01->U+00E6, U+1D02->U+00E6, U+1D2D->U+00E6, U+1D46->U+00E6, U+00E6, U+0622->U+0627, U+0623->U+0627, U+0624->U+0648, U+0625->U+0627, U+0626->U+064A, U+06C0->U+06D5, U+06C2->U+06C1, U+06D3->U+06D2, U+FB50->U+0671, U+FB51->U+0671, U+FB52->U+067B,  \
-    U+FB53->U+067B, U+FB54->U+067B, U+FB56->U+067E, U+FB57->U+067E, U+FB58->U+067E, U+FB5A->U+0680, U+FB5B->U+0680, U+FB5C->U+0680, U+FB5E->U+067A, U+FB5F->U+067A, U+FB60->U+067A, U+FB62->U+067F, U+FB63->U+067F, U+FB64->U+067F, U+FB66->U+0679, U+FB67->U+0679,  \
-    U+FB68->U+0679, U+FB6A->U+06A4, U+FB6B->U+06A4, U+FB6C->U+06A4, U+FB6E->U+06A6, U+FB6F->U+06A6, U+FB70->U+06A6, U+FB72->U+0684, U+FB73->U+0684, U+FB74->U+0684, U+FB76->U+0683, U+FB77->U+0683, U+FB78->U+0683, U+FB7A->U+0686, U+FB7B->U+0686, U+FB7C->U+0686,  \
-    U+FB7E->U+0687, U+FB7F->U+0687, U+FB80->U+0687, U+FB82->U+068D, U+FB83->U+068D, U+FB84->U+068C, U+FB85->U+068C, U+FB86->U+068E, U+FB87->U+068E, U+FB88->U+0688, U+FB89->U+0688, U+FB8A->U+0698, U+FB8B->U+0698, U+FB8C->U+0691, U+FB8D->U+0691, U+FB8E->U+06A9,  \
-    U+FB8F->U+06A9, U+FB90->U+06A9, U+FB92->U+06AF, U+FB93->U+06AF, U+FB94->U+06AF, U+FB96->U+06B3, U+FB97->U+06B3, U+FB98->U+06B3, U+FB9A->U+06B1, U+FB9B->U+06B1, U+FB9C->U+06B1, U+FB9E->U+06BA, U+FB9F->U+06BA, U+FBA0->U+06BB, U+FBA1->U+06BB, U+FBA2->U+06BB,  \
-    U+FBA4->U+06C0, U+FBA5->U+06C0, U+FBA6->U+06C1, U+FBA7->U+06C1, U+FBA8->U+06C1, U+FBAA->U+06BE, U+FBAB->U+06BE, U+FBAC->U+06BE, U+FBAE->U+06D2, U+FBAF->U+06D2, U+FBB0->U+06D3, U+FBB1->U+06D3, U+FBD3->U+06AD, U+FBD4->U+06AD, U+FBD5->U+06AD, U+FBD7->U+06C7,  \
-    U+FBD8->U+06C7, U+FBD9->U+06C6, U+FBDA->U+06C6, U+FBDB->U+06C8, U+FBDC->U+06C8, U+FBDD->U+0677, U+FBDE->U+06CB, U+FBDF->U+06CB, U+FBE0->U+06C5, U+FBE1->U+06C5, U+FBE2->U+06C9, U+FBE3->U+06C9, U+FBE4->U+06D0, U+FBE5->U+06D0, U+FBE6->U+06D0, U+FBE8->U+0649,  \
-    U+FBFC->U+06CC, U+FBFD->U+06CC, U+FBFE->U+06CC, U+0621, U+0627..U+063A, U+0641..U+064A, U+0660..U+0669, U+066E, U+066F, U+0671..U+06BF, U+06C1, U+06C3..U+06D2, U+06D5, U+06EE..U+06FC, U+06FF, U+0750..U+076D, U+FB55, U+FB59, U+FB5D, U+FB61, U+FB65, U+FB69,  \
-    U+FB6D, U+FB71, U+FB75, U+FB79, U+FB7D, U+FB81, U+FB91, U+FB95, U+FB99, U+FB9D, U+FBA3, U+FBA9, U+FBAD, U+FBD6, U+FBE7, U+FBE9, U+FBFF, U+0531..U+0556->U+0561..U+0586, U+0561..U+0586, U+0587, U+09DC->U+09A1, U+09DD->U+09A2, U+09DF->U+09AF, U+09F0->U+09AC,  \
-    U+09F1->U+09AC, U+0985..U+0990, U+0993..U+09B0, U+09B2, U+09B6..U+09B9, U+09CE, U+09E0, U+09E1, U+09E6..U+09EF, U+F900->U+8C48, U+F901->U+66F4, U+F902->U+8ECA, U+F903->U+8CC8, U+F904->U+6ED1, U+F905->U+4E32, U+F906->U+53E5, U+F907->U+9F9C, U+F908->U+9F9C,  \
-    U+F909->U+5951, U+F90A->U+91D1, U+F90B->U+5587, U+F90C->U+5948, U+F90D->U+61F6, U+F90E->U+7669, U+F90F->U+7F85, U+F910->U+863F, U+F911->U+87BA, U+F912->U+88F8, U+F913->U+908F, U+F914->U+6A02, U+F915->U+6D1B, U+F916->U+70D9, U+F917->U+73DE, U+F918->U+843D,  \
-    U+F919->U+916A, U+F91A->U+99F1, U+F91B->U+4E82, U+F91C->U+5375, U+F91D->U+6B04, U+F91E->U+721B, U+F91F->U+862D, U+F920->U+9E1E, U+F921->U+5D50, U+F922->U+6FEB, U+F923->U+85CD, U+F924->U+8964, U+F925->U+62C9, U+F926->U+81D8, U+F927->U+881F, U+F928->U+5ECA,  \
-    U+F929->U+6717, U+F92A->U+6D6A, U+F92B->U+72FC, U+F92C->U+90CE, U+F92D->U+4F86, U+F92E->U+51B7, U+F92F->U+52DE, U+F930->U+64C4, U+F931->U+6AD3, U+F932->U+7210, U+F933->U+76E7, U+F934->U+8001, U+F935->U+8606, U+F936->U+865C, U+F937->U+8DEF, U+F938->U+9732,  \
-    U+F939->U+9B6F, U+F93A->U+9DFA, U+F93B->U+788C, U+F93C->U+797F, U+F93D->U+7DA0, U+F93E->U+83C9, U+F93F->U+9304, U+F940->U+9E7F, U+F941->U+8AD6, U+F942->U+58DF, U+F943->U+5F04, U+F944->U+7C60, U+F945->U+807E, U+F946->U+7262, U+F947->U+78CA, U+F948->U+8CC2,  \
-    U+F949->U+96F7, U+F94A->U+58D8, U+F94B->U+5C62, U+F94C->U+6A13, U+F94D->U+6DDA, U+F94E->U+6F0F, U+F94F->U+7D2F, U+F950->U+7E37, U+F951->U+964B, U+F952->U+52D2, U+F953->U+808B, U+F954->U+51DC, U+F955->U+51CC, U+F956->U+7A1C, U+F957->U+7DBE, U+F958->U+83F1,  \
-    U+F959->U+9675, U+F95A->U+8B80, U+F95B->U+62CF, U+F95C->U+6A02, U+F95D->U+8AFE, U+F95E->U+4E39, U+F95F->U+5BE7, U+F960->U+6012, U+F961->U+7387, U+F962->U+7570, U+F963->U+5317, U+F964->U+78FB, U+F965->U+4FBF, U+F966->U+5FA9, U+F967->U+4E0D, U+F968->U+6CCC,  \
-    U+F969->U+6578, U+F96A->U+7D22, U+F96B->U+53C3, U+F96C->U+585E, U+F96D->U+7701, U+F96E->U+8449, U+F96F->U+8AAA, U+F970->U+6BBA, U+F971->U+8FB0, U+F972->U+6C88, U+F973->U+62FE, U+F974->U+82E5, U+F975->U+63A0, U+F976->U+7565, U+F977->U+4EAE, U+F978->U+5169,  \
-    U+F979->U+51C9, U+F97A->U+6881, U+F97B->U+7CE7, U+F97C->U+826F, U+F97D->U+8AD2, U+F97E->U+91CF, U+F97F->U+52F5, U+F980->U+5442, U+F981->U+5973, U+F982->U+5EEC, U+F983->U+65C5, U+F984->U+6FFE, U+F985->U+792A, U+F986->U+95AD, U+F987->U+9A6A, U+F988->U+9E97,  \
-    U+F989->U+9ECE, U+F98A->U+529B, U+F98B->U+66C6, U+F98C->U+6B77, U+F98D->U+8F62, U+F98E->U+5E74, U+F98F->U+6190, U+F990->U+6200, U+F991->U+649A, U+F992->U+6F23, U+F993->U+7149, U+F994->U+7489, U+F995->U+79CA, U+F996->U+7DF4, U+F997->U+806F, U+F998->U+8F26,  \
-    U+F999->U+84EE, U+F99A->U+9023, U+F99B->U+934A, U+F99C->U+5217, U+F99D->U+52A3, U+F99E->U+54BD, U+F99F->U+70C8, U+F9A0->U+88C2, U+F9A1->U+8AAA, U+F9A2->U+5EC9, U+F9A3->U+5FF5, U+F9A4->U+637B, U+F9A5->U+6BAE, U+F9A6->U+7C3E, U+F9A7->U+7375, U+F9A8->U+4EE4,  \
-    U+F9A9->U+56F9, U+F9AA->U+5BE7, U+F9AB->U+5DBA, U+F9AC->U+601C, U+F9AD->U+73B2, U+F9AE->U+7469, U+F9AF->U+7F9A, U+F9B0->U+8046, U+F9B1->U+9234, U+F9B2->U+96F6, U+F9B3->U+9748, U+F9B4->U+9818, U+F9B5->U+4F8B, U+F9B6->U+79AE, U+F9B7->U+91B4, U+F9B8->U+96B8,  \
-    U+F9B9->U+60E1, U+F9BA->U+4E86, U+F9BB->U+50DA, U+F9BC->U+5BEE, U+F9BD->U+5C3F, U+F9BE->U+6599, U+F9BF->U+6A02, U+F9C0->U+71CE, U+F9C1->U+7642, U+F9C2->U+84FC, U+F9C3->U+907C, U+F9C4->U+9F8D, U+F9C5->U+6688, U+F9C6->U+962E, U+F9C7->U+5289, U+F9C8->U+677B,  \
-    U+F9C9->U+67F3, U+F9CA->U+6D41, U+F9CB->U+6E9C, U+F9CC->U+7409, U+F9CD->U+7559, U+F9CE->U+786B, U+F9CF->U+7D10, U+F9D0->U+985E, U+F9D1->U+516D, U+F9D2->U+622E, U+F9D3->U+9678, U+F9D4->U+502B, U+F9D5->U+5D19, U+F9D6->U+6DEA, U+F9D7->U+8F2A, U+F9D8->U+5F8B,  \
-    U+F9D9->U+6144, U+F9DA->U+6817, U+F9DB->U+7387, U+F9DC->U+9686, U+F9DD->U+5229, U+F9DE->U+540F, U+F9DF->U+5C65, U+F9E0->U+6613, U+F9E1->U+674E, U+F9E2->U+68A8, U+F9E3->U+6CE5, U+F9E4->U+7406, U+F9E5->U+75E2, U+F9E6->U+7F79, U+F9E7->U+88CF, U+F9E8->U+88E1,  \
-    U+F9E9->U+91CC, U+F9EA->U+96E2, U+F9EB->U+533F, U+F9EC->U+6EBA, U+F9ED->U+541D, U+F9EE->U+71D0, U+F9EF->U+7498, U+F9F0->U+85FA, U+F9F1->U+96A3, U+F9F2->U+9C57, U+F9F3->U+9E9F, U+F9F4->U+6797, U+F9F5->U+6DCB, U+F9F6->U+81E8, U+F9F7->U+7ACB, U+F9F8->U+7B20,  \
-    U+F9F9->U+7C92, U+F9FA->U+72C0, U+F9FB->U+7099, U+F9FC->U+8B58, U+F9FD->U+4EC0, U+F9FE->U+8336, U+F9FF->U+523A, U+FA00->U+5207, U+FA01->U+5EA6, U+FA02->U+62D3, U+FA03->U+7CD6, U+FA04->U+5B85, U+FA05->U+6D1E, U+FA06->U+66B4, U+FA07->U+8F3B, U+FA08->U+884C,  \
-    U+FA09->U+964D, U+FA0A->U+898B, U+FA0B->U+5ED3, U+FA0C->U+5140, U+FA0D->U+55C0, U+FA10->U+585A, U+FA12->U+6674, U+FA15->U+51DE, U+FA16->U+732A, U+FA17->U+76CA, U+FA18->U+793C, U+FA19->U+795E, U+FA1A->U+7965, U+FA1B->U+798F, U+FA1C->U+9756, U+FA1D->U+7CBE,  \
-    U+FA1E->U+7FBD, U+FA20->U+8612, U+FA22->U+8AF8, U+FA25->U+9038, U+FA26->U+90FD, U+FA2A->U+98EF, U+FA2B->U+98FC, U+FA2C->U+9928, U+FA2D->U+9DB4, U+FA30->U+4FAE, U+FA31->U+50E7, U+FA32->U+514D, U+FA33->U+52C9, U+FA34->U+52E4, U+FA35->U+5351, U+FA36->U+559D,  \
-    U+FA37->U+5606, U+FA38->U+5668, U+FA39->U+5840, U+FA3A->U+58A8, U+FA3B->U+5C64, U+FA3C->U+5C6E, U+FA3D->U+6094, U+FA3E->U+6168, U+FA3F->U+618E, U+FA40->U+61F2, U+FA41->U+654F, U+FA42->U+65E2, U+FA43->U+6691, U+FA44->U+6885, U+FA45->U+6D77, U+FA46->U+6E1A,  \
-    U+FA47->U+6F22, U+FA48->U+716E, U+FA49->U+722B, U+FA4A->U+7422, U+FA4B->U+7891, U+FA4C->U+793E, U+FA4D->U+7949, U+FA4E->U+7948, U+FA4F->U+7950, U+FA50->U+7956, U+FA51->U+795D, U+FA52->U+798D, U+FA53->U+798E, U+FA54->U+7A40, U+FA55->U+7A81, U+FA56->U+7BC0,  \
-    U+FA57->U+7DF4, U+FA58->U+7E09, U+FA59->U+7E41, U+FA5A->U+7F72, U+FA5B->U+8005, U+FA5C->U+81ED, U+FA5D->U+8279, U+FA5E->U+8279, U+FA5F->U+8457, U+FA60->U+8910, U+FA61->U+8996, U+FA62->U+8B01, U+FA63->U+8B39, U+FA64->U+8CD3, U+FA65->U+8D08, U+FA66->U+8FB6,  \
-    U+FA67->U+9038, U+FA68->U+96E3, U+FA69->U+97FF, U+FA6A->U+983B, U+FA70->U+4E26, U+FA71->U+51B5, U+FA72->U+5168, U+FA73->U+4F80, U+FA74->U+5145, U+FA75->U+5180, U+FA76->U+52C7, U+FA77->U+52FA, U+FA78->U+559D, U+FA79->U+5555, U+FA7A->U+5599, U+FA7B->U+55E2,  \
-    U+FA7C->U+585A, U+FA7D->U+58B3, U+FA7E->U+5944, U+FA7F->U+5954, U+FA80->U+5A62, U+FA81->U+5B28, U+FA82->U+5ED2, U+FA83->U+5ED9, U+FA84->U+5F69, U+FA85->U+5FAD, U+FA86->U+60D8, U+FA87->U+614E, U+FA88->U+6108, U+FA89->U+618E, U+FA8A->U+6160, U+FA8B->U+61F2,  \
-    U+FA8C->U+6234, U+FA8D->U+63C4, U+FA8E->U+641C, U+FA8F->U+6452, U+FA90->U+6556, U+FA91->U+6674, U+FA92->U+6717, U+FA93->U+671B, U+FA94->U+6756, U+FA95->U+6B79, U+FA96->U+6BBA, U+FA97->U+6D41, U+FA98->U+6EDB, U+FA99->U+6ECB, U+FA9A->U+6F22, U+FA9B->U+701E,  \
-    U+FA9C->U+716E, U+FA9D->U+77A7, U+FA9E->U+7235, U+FA9F->U+72AF, U+FAA0->U+732A, U+FAA1->U+7471, U+FAA2->U+7506, U+FAA3->U+753B, U+FAA4->U+761D, U+FAA5->U+761F, U+FAA6->U+76CA, U+FAA7->U+76DB, U+FAA8->U+76F4, U+FAA9->U+774A, U+FAAA->U+7740, U+FAAB->U+78CC,  \
-    U+FAAC->U+7AB1, U+FAAD->U+7BC0, U+FAAE->U+7C7B, U+FAAF->U+7D5B, U+FAB0->U+7DF4, U+FAB1->U+7F3E, U+FAB2->U+8005, U+FAB3->U+8352, U+FAB4->U+83EF, U+FAB5->U+8779, U+FAB6->U+8941, U+FAB7->U+8986, U+FAB8->U+8996, U+FAB9->U+8ABF, U+FABA->U+8AF8, U+FABB->U+8ACB,  \
-    U+FABC->U+8B01, U+FABD->U+8AFE, U+FABE->U+8AED, U+FABF->U+8B39, U+FAC0->U+8B8A, U+FAC1->U+8D08, U+FAC2->U+8F38, U+FAC3->U+9072, U+FAC4->U+9199, U+FAC5->U+9276, U+FAC6->U+967C, U+FAC7->U+96E3, U+FAC8->U+9756, U+FAC9->U+97DB, U+FACA->U+97FF, U+FACB->U+980B,  \
+    U+013A->l, U+013B->l, U+013C->l, U+013D->l, U+013E->l, U+013F->l, U+0140->l, U+0141->l, U+0142->l, U+019A->l, U+01C8->l, U+0234->l, U+023D->l, U+026B->l, U+026C->l, U+026D->l, U+029F->l, U+02E1->l, U+1D0C->l, U+1D38->l, U+1D85->l, U+1DA9->l, U+1DATA->l,  \
+    U+1DAB->l, U+1E36->l, U+1E37->l, U+1E38->l, U+1E39->l, U+1E3A->l, U+1E3B->l, U+1E3C->l, U+1E3D->l, U+2C60->l, U+2C61->l, U+2C62->l, U+019C->m, U+026F->m, U+0270->m, U+0271->m, U+1D0D->m, U+1D1F->m, U+1D39->m, U+1D50->m, U+1D5A->m, U+1D6F->m, U+1D86->m,  \
+    U+1DAC->m, U+1DAD->m, U+1E3E->m, U+1E3F->m, U+1E40->m, U+1E41->m, U+1E42->m, U+1E43->m, U+00D1->n, U+00F1->n, U+0143->n, U+0144->n, U+0145->n, U+0146->n, U+0147->n, U+0148->n, U+0149->n, U+019D->n, U+019E->n, U+01CB->n, U+01F8->n, U+01F9->n, U+0220->n,  \
+    U+0235->n, U+0272->n, U+0273->n, U+0274->n, U+1D0E->n, U+1D3A->n, U+1D3B->n, U+1D70->n, U+1D87->n, U+1DAE->n, U+1DAF->n, U+1DB0->n, U+1E44->n, U+1E45->n, U+1E46->n, U+1E47->n, U+1E48->n, U+1E49->n, U+1E4A->n, U+1E4B->n, U+207F->n, U+00D2->o, U+00D3->o,  \
+    U+00D4->o, U+00D5->o, U+00D6->o, U+00D8->o, U+00F2->o, U+00F3->o, U+00F4->o, U+00F5->o, U+00F6->o, U+00F8->o, U+01030F->o, U+014C->o, U+014D->o, U+014E->o, U+014F->o, U+0150->o, U+0151->o, U+0186->o, U+019F->o, U+01A0->o, U+01A1->o, U+01D1->o, U+01D2->o,  \
+    U+01EA->o, U+01EB->o, U+01EC->o, U+01ED->o, U+01FE->o, U+01FF->o, U+020C->o, U+020D->o, U+020E->o, U+020F->o, U+022A->o, U+022B->o, U+022C->o, U+022D->o, U+022E->o, U+022F->o, U+0230->o, U+0231->o, U+0254->o, U+0275->o, U+043E->o, U+04E6->o, U+04E7->o,  \
+    U+04E8->o, U+04E9->o, U+04EA->o, U+04EB->o, U+1D0F->o, U+1D10->o, U+1D11->o, U+1D12->o, U+1D13->o, U+1D16->o, U+1D17->o, U+1D3C->o, U+1D52->o, U+1D53->o, U+1D54->o, U+1D55->o, U+1D97->o, U+1DB1->o, U+1E4C->o, U+1E4D->o, U+1E4E->o, U+1E4F->o, U+1E50->o,  \
+    U+1E51->o, U+1E52->o, U+1E53->o, U+1ECC->o, U+1ECD->o, U+1ECE->o, U+1ECF->o, U+1ED0->o, U+1ED1->o, U+1ED2->o, U+1ED3->o, U+1ED4->o, U+1ED5->o, U+1ED6->o, U+1ED7->o, U+1ED8->o, U+1ED9->o, U+1EDA->o, U+1EDB->o, U+1EDC->o, U+1EDD->o, U+1EDGE->o, U+1EDF->o,  \
+    U+1EE0->o, U+1EE1->o, U+1EE2->o, U+1EE3->o, U+2092->o, U+2C9E->o, U+2C9F->o, U+01A4->p, U+01A5->p, U+1D18->p, U+1D3E->p, U+1D56->p, U+1D71->p, U+1D7D->p, U+1D88->p, U+1E54->p, U+1E55->p, U+1E56->p, U+1E57->p, U+2C63->p, U+024A->q, U+024B->q, U+02A0->q,  \
+    U+0154->r, U+0155->r, U+0156->r, U+0157->r, U+0158->r, U+0159->r, U+0210->r, U+0211->r, U+0212->r, U+0213->r, U+024C->r, U+024D->r, U+0279->r, U+027A->r, U+027B->r, U+027C->r, U+027D->r, U+027E->r, U+027F->r, U+0280->r, U+0281->r, U+02B3->r, U+02B4->r,  \
+    U+02B5->r, U+02B6->r, U+1D19->r, U+1D1A->r, U+1D3F->r, U+1D63->r, U+1D72->r, U+1D73->r, U+1D89->r, U+1DCA->r, U+1E58->r, U+1E59->r, U+1E5A->r, U+1E5B->r, U+1E5C->r, U+1E5D->r, U+1E5E->r, U+1E5F->r, U+211C->r, U+2C64->r, U+00DF->s, U+015A->s, U+015B->s,  \
+    U+015C->s, U+015D->s, U+015E->s, U+015F->s, U+0160->s, U+0161->s, U+017F->s, U+0218->s, U+0219->s, U+023F->s, U+0282->s, U+02E2->s, U+1D74->s, U+1D8A->s, U+1DB3->s, U+1E60->s, U+1E61->s, U+1E62->s, U+1E63->s, U+1E64->s, U+1E65->s, U+1E66->s, U+1E67->s,  \
+    U+1E68->s, U+1E69->s, U+1E9B->s, U+0162->t, U+0163->t, U+0164->t, U+0165->t, U+0166->t, U+0167->t, U+01AB->t, U+01AC->t, U+01AD->t, U+01AE->t, U+021A->t, U+021B->t, U+0236->t, U+023E->t, U+0287->t, U+0288->t, U+1D1B->t, U+1D40->t, U+1D57->t, U+1D75->t,  \
+    U+1DB5->t, U+1E6A->t, U+1E6B->t, U+1E6C->t, U+1E6D->t, U+1E6E->t, U+1E6F->t, U+1E70->t, U+1E71->t, U+1E97->t, U+2C66->t, U+00D9->u, U+00DA->u, U+00DB->u, U+00DC->u, U+00F9->u, U+00FA->u, U+00FB->u, U+00FC->u, U+010316->u, U+0168->u, U+0169->u, U+016A->u,  \
+    U+016B->u, U+016C->u, U+016D->u, U+016E->u, U+016F->u, U+0170->u, U+0171->u, U+0172->u, U+0173->u, U+01AF->u, U+01B0->u, U+01D3->u, U+01D4->u, U+01D5->u, U+01D6->u, U+01D7->u, U+01D8->u, U+01D9->u, U+01DA->u, U+01DB->u, U+01DC->u, U+0214->u, U+0215->u,  \
+    U+0216->u, U+0217->u, U+0244->u, U+0289->u, U+1D1C->u, U+1D1D->u, U+1D1E->u, U+1D41->u, U+1D58->u, U+1D59->u, U+1D64->u, U+1D7E->u, U+1D99->u, U+1DB6->u, U+1DB8->u, U+1E72->u, U+1E73->u, U+1E74->u, U+1E75->u, U+1E76->u, U+1E77->u, U+1E78->u, U+1E79->u,  \
+    U+1E7A->u, U+1E7B->u, U+1EE4->u, U+1EE5->u, U+1EE6->u, U+1EE7->u, U+1EE8->u, U+1EE9->u, U+1EEA->u, U+1EEB->u, U+1EEC->u, U+1EED->u, U+1EEE->u, U+1EEF->u, U+1EF0->u, U+1EF1->u, U+01B2->v, U+0245->v, U+028B->v, U+028C->v, U+1D20->v, U+1D5B->v, U+1D65->v,  \
+    U+1D8C->v, U+1DB9->v, U+1DBA->v, U+1E7C->v, U+1E7D->v, U+1E7E->v, U+1E7F->v, U+2C74->v, U+0174->w, U+0175->w, U+028D->w, U+02B7->w, U+1D21->w, U+1D42->w, U+1E80->w, U+1E81->w, U+1E82->w, U+1E83->w, U+1E84->w, U+1E85->w, U+1E86->w, U+1E87->w, U+1E88->w,  \
+    U+1E89->w, U+1E98->w, U+02E3->x, U+1D8D->x, U+1E8A->x, U+1E8B->x, U+1E8C->x, U+1E8D->x, U+2093->x, U+00DD->y, U+00FD->y, U+00FF->y, U+0176->y, U+0177->y, U+0178->y, U+01B3->y, U+01B4->y, U+0232->y, U+0233->y, U+024E->y, U+024F->y, U+028E->y, U+028F->y,  \
+    U+02B8->y, U+1E8E->y, U+1E8F->y, U+1E99->y, U+1EF2->y, U+1EF3->y, U+1EF4->y, U+1EF5->y, U+1EF6->y, U+1EF7->y, U+1EF8->y, U+1EF9->y, U+0179->z, U+017A->z, U+017B->z, U+017C->z, U+017D->z, U+017E->z, U+01B5->z, U+01B6->z, U+0224->z, U+0225->z, U+0240->z,  \
+    U+0290->z, U+0291->z, U+1D22->z, U+1D76->z, U+1D8E->z, U+1DBB->z, U+1DBC->z, U+1DBD->z, U+1E90->z, U+1E91->z, U+1E92->z, U+1E93->z, U+1E94->z, U+1E95->z, U+2128->z, U+2C6B->z, U+2C6C->z, U+00C6->U+00E6, U+01E2->U+00E6, U+01E3->U+00E6, U+01FC->U+00E6,  \
+    U+01FD->U+00E6, U+1D01->U+00E6, U+1D02->U+00E6, U+1D2D->U+00E6, U+1D46->U+00E6, U+00E6, U+0622->U+0627, U+0623->U+0627, U+0624->U+0648, U+0625->U+0627, U+0626->U+064A, U+06C0->U+06D5, U+06C2->U+06C1, U+06D3->U+06D2, U+FB50->U+0671, U+FB51->U+0671, U+FB52->U+067B,  \
+    U+FB53->U+067B, U+FB54->U+067B, U+FB56->U+067E, U+FB57->U+067E, U+FB58->U+067E, U+FB5A->U+0680, U+FB5B->U+0680, U+FB5C->U+0680, U+FB5E->U+067A, U+FB5F->U+067A, U+FB60->U+067A, U+FB62->U+067F, U+FB63->U+067F, U+FB64->U+067F, U+FB66->U+0679, U+FB67->U+0679,  \
+    U+FB68->U+0679, U+FB6A->U+06A4, U+FB6B->U+06A4, U+FB6C->U+06A4, U+FB6E->U+06A6, U+FB6F->U+06A6, U+FB70->U+06A6, U+FB72->U+0684, U+FB73->U+0684, U+FB74->U+0684, U+FB76->U+0683, U+FB77->U+0683, U+FB78->U+0683, U+FB7A->U+0686, U+FB7B->U+0686, U+FB7C->U+0686,  \
+    U+FB7E->U+0687, U+FB7F->U+0687, U+FB80->U+0687, U+FB82->U+068D, U+FB83->U+068D, U+FB84->U+068C, U+FB85->U+068C, U+FB86->U+068E, U+FB87->U+068E, U+FB88->U+0688, U+FB89->U+0688, U+FB8A->U+0698, U+FB8B->U+0698, U+FB8C->U+0691, U+FB8D->U+0691, U+FB8E->U+06A9,  \
+    U+FB8F->U+06A9, U+FB90->U+06A9, U+FB92->U+06AF, U+FB93->U+06AF, U+FB94->U+06AF, U+FB96->U+06B3, U+FB97->U+06B3, U+FB98->U+06B3, U+FB9A->U+06B1, U+FB9B->U+06B1, U+FB9C->U+06B1, U+FB9E->U+06BA, U+FB9F->U+06BA, U+FBA0->U+06BB, U+FBA1->U+06BB, U+FBA2->U+06BB,  \
+    U+FBA4->U+06C0, U+FBA5->U+06C0, U+FBA6->U+06C1, U+FBA7->U+06C1, U+FBA8->U+06C1, U+FBAA->U+06BE, U+FBAB->U+06BE, U+FBAC->U+06BE, U+FBAE->U+06D2, U+FBAF->U+06D2, U+FBB0->U+06D3, U+FBB1->U+06D3, U+FBD3->U+06AD, U+FBD4->U+06AD, U+FBD5->U+06AD, U+FBD7->U+06C7,  \
+    U+FBD8->U+06C7, U+FBD9->U+06C6, U+FBDA->U+06C6, U+FBDB->U+06C8, U+FBDC->U+06C8, U+FBDD->U+0677, U+FBDE->U+06CB, U+FBDF->U+06CB, U+FBE0->U+06C5, U+FBE1->U+06C5, U+FBE2->U+06C9, U+FBE3->U+06C9, U+FBE4->U+06D0, U+FBE5->U+06D0, U+FBE6->U+06D0, U+FBE8->U+0649,  \
+    U+FBFC->U+06CC, U+FBFD->U+06CC, U+FBFE->U+06CC, U+0621, U+0627..U+063A, U+0641..U+064A, U+0660..U+0669, U+066E, U+066F, U+0671..U+06BF, U+06C1, U+06C3..U+06D2, U+06D5, U+06EE..U+06FC, U+06FF, U+0750..U+076D, U+FB55, U+FB59, U+FB5D, U+FB61, U+FB65, U+FB69,  \
+    U+FB6D, U+FB71, U+FB75, U+FB79, U+FB7D, U+FB81, U+FB91, U+FB95, U+FB99, U+FB9D, U+FBA3, U+FBA9, U+FBAD, U+FBD6, U+FBE7, U+FBE9, U+FBFF, U+0531..U+0556->U+0561..U+0586, U+0561..U+0586, U+0587, U+09DC->U+09A1, U+09DD->U+09A2, U+09DF->U+09AF, U+09F0->U+09AC,  \
+    U+09F1->U+09AC, U+0985..U+0990, U+0993..U+09B0, U+09B2, U+09B6..U+09B9, U+09CE, U+09E0, U+09E1, U+09E6..U+09EF, U+F900->U+8C48, U+F901->U+66F4, U+F902->U+8ECA, U+F903->U+8CC8, U+F904->U+6ED1, U+F905->U+4E32, U+F906->U+53E5, U+F907->U+9F9C, U+F908->U+9F9C,  \
+    U+F909->U+5951, U+F90A->U+91D1, U+F90B->U+5587, U+F90C->U+5948, U+F90D->U+61F6, U+F90E->U+7669, U+F90F->U+7F85, U+F910->U+863F, U+F911->U+87BA, U+F912->U+88F8, U+F913->U+908F, U+F914->U+6A02, U+F915->U+6D1B, U+F916->U+70D9, U+F917->U+73DE, U+F918->U+843D,  \
+    U+F919->U+916A, U+F91A->U+99F1, U+F91B->U+4E82, U+F91C->U+5375, U+F91D->U+6B04, U+F91E->U+721B, U+F91F->U+862D, U+F920->U+9E1E, U+F921->U+5D50, U+F922->U+6FEB, U+F923->U+85CD, U+F924->U+8964, U+F925->U+62C9, U+F926->U+81D8, U+F927->U+881F, U+F928->U+5ECA,  \
+    U+F929->U+6717, U+F92A->U+6D6A, U+F92B->U+72FC, U+F92C->U+90CE, U+F92D->U+4F86, U+F92E->U+51B7, U+F92F->U+52DE, U+F930->U+64C4, U+F931->U+6AD3, U+F932->U+7210, U+F933->U+76E7, U+F934->U+8001, U+F935->U+8606, U+F936->U+865C, U+F937->U+8DEF, U+F938->U+9732,  \
+    U+F939->U+9B6F, U+F93A->U+9DFA, U+F93B->U+788C, U+F93C->U+797F, U+F93D->U+7DA0, U+F93E->U+83C9, U+F93F->U+9304, U+F940->U+9E7F, U+F941->U+8AD6, U+F942->U+58DF, U+F943->U+5F04, U+F944->U+7C60, U+F945->U+807E, U+F946->U+7262, U+F947->U+78CA, U+F948->U+8CC2,  \
+    U+F949->U+96F7, U+F94A->U+58D8, U+F94B->U+5C62, U+F94C->U+6A13, U+F94D->U+6DDA, U+F94E->U+6F0F, U+F94F->U+7D2F, U+F950->U+7E37, U+F951->U+964B, U+F952->U+52D2, U+F953->U+808B, U+F954->U+51DC, U+F955->U+51CC, U+F956->U+7A1C, U+F957->U+7DBE, U+F958->U+83F1,  \
+    U+F959->U+9675, U+F95A->U+8B80, U+F95B->U+62CF, U+F95C->U+6A02, U+F95D->U+8SAFE, U+F95E->U+4E39, U+F95F->U+5BE7, U+F960->U+6012, U+F961->U+7387, U+F962->U+7570, U+F963->U+5317, U+F964->U+78FB, U+F965->U+4FBF, U+F966->U+5FA9, U+F967->U+4E0D, U+F968->U+6CCC,  \
+    U+F969->U+6578, U+F96A->U+7D22, U+F96B->U+53C3, U+F96C->U+585E, U+F96D->U+7701, U+F96E->U+8449, U+F96F->U+8AAA, U+F970->U+6BBA, U+F971->U+8FB0, U+F972->U+6C88, U+F973->U+62FE, U+F974->U+82E5, U+F975->U+63A0, U+F976->U+7565, U+F977->U+4EAE, U+F978->U+5169,  \
+    U+F979->U+51C9, U+F97A->U+6881, U+F97B->U+7CE7, U+F97C->U+826F, U+F97D->U+8AD2, U+F97E->U+91CF, U+F97F->U+52F5, U+F980->U+5442, U+F981->U+5973, U+F982->U+5EEC, U+F983->U+65C5, U+F984->U+6FFE, U+F985->U+792A, U+F986->U+95AD, U+F987->U+9A6A, U+F988->U+9E97,  \
+    U+F989->U+9ECE, U+F98A->U+529B, U+F98B->U+66C6, U+F98C->U+6B77, U+F98D->U+8F62, U+F98E->U+5E74, U+F98F->U+6190, U+F990->U+6200, U+F991->U+649A, U+F992->U+6F23, U+F993->U+7149, U+F994->U+7489, U+F995->U+79CA, U+F996->U+7DF4, U+F997->U+806F, U+F998->U+8F26,  \
+    U+F999->U+84EE, U+F99A->U+9023, U+F99B->U+934A, U+F99C->U+5217, U+F99D->U+52A3, U+F99E->U+54BD, U+F99F->U+70C8, U+F9A0->U+88C2, U+F9A1->U+8AAA, U+F9A2->U+5EC9, U+F9A3->U+5FF5, U+F9A4->U+637B, U+F9A5->U+6BAE, U+F9A6->U+7C3E, U+F9A7->U+7375, U+F9A8->U+4EE4,  \
+    U+F9A9->U+56F9, U+F9AA->U+5BE7, U+F9AB->U+5DBA, U+F9AC->U+601C, U+F9AD->U+73B2, U+F9AE->U+7469, U+F9AF->U+7F9A, U+F9B0->U+8046, U+F9B1->U+9234, U+F9B2->U+96F6, U+F9B3->U+9748, U+F9B4->U+9818, U+F9B5->U+4F8B, U+F9B6->U+79AE, U+F9B7->U+91B4, U+F9B8->U+96B8,  \
+    U+F9B9->U+60E1, U+F9BA->U+4E86, U+F9BB->U+50DA, U+F9BC->U+5BEE, U+F9BD->U+5C3F, U+F9BE->U+6599, U+F9BF->U+6A02, U+F9C0->U+71CE, U+F9C1->U+7642, U+F9C2->U+84FC, U+F9C3->U+907C, U+F9C4->U+9F8D, U+F9C5->U+6688, U+F9C6->U+962E, U+F9C7->U+5289, U+F9C8->U+677B,  \
+    U+F9C9->U+67F3, U+F9CA->U+6D41, U+F9CB->U+6E9C, U+F9CC->U+7409, U+F9CD->U+7559, U+F9CE->U+786B, U+F9CF->U+7D10, U+F9D0->U+985E, U+F9D1->U+516D, U+F9D2->U+622E, U+F9D3->U+9678, U+F9D4->U+502B, U+F9D5->U+5D19, U+F9D6->U+6DEA, U+F9D7->U+8F2A, U+F9D8->U+5F8B,  \
+    U+F9D9->U+6144, U+F9DA->U+6817, U+F9DB->U+7387, U+F9DC->U+9686, U+F9DD->U+5229, U+F9DE->U+540F, U+F9DF->U+5C65, U+F9E0->U+6613, U+F9E1->U+674E, U+F9E2->U+68A8, U+F9E3->U+6CE5, U+F9E4->U+7406, U+F9E5->U+75E2, U+F9E6->U+7F79, U+F9E7->U+88CF, U+F9E8->U+88E1,  \
+    U+F9E9->U+91CC, U+F9EA->U+96E2, U+F9EB->U+533F, U+F9EC->U+6EBA, U+F9ED->U+541D, U+F9EE->U+71D0, U+F9EF->U+7498, U+F9F0->U+85FA, U+F9F1->U+96A3, U+F9F2->U+9C57, U+F9F3->U+9E9F, U+F9F4->U+6797, U+F9F5->U+6DCB, U+F9F6->U+81E8, U+F9F7->U+7ACB, U+F9F8->U+7B20,  \
+    U+F9F9->U+7C92, U+F9FA->U+72C0, U+F9FB->U+7099, U+F9FC->U+8B58, U+F9FD->U+4EC0, U+F9FE->U+8336, U+F9FF->U+523A, U+FA00->U+5207, U+FA01->U+5EA6, U+FA02->U+62D3, U+FA03->U+7CD6, U+FA04->U+5B85, U+FA05->U+6D1E, U+FA06->U+66B4, U+FA07->U+8F3B, U+FA08->U+884C,  \
+    U+FA09->U+964D, U+FA0A->U+898B, U+FA0B->U+5ED3, U+FA0C->U+5140, U+FA0D->U+55C0, U+FA10->U+585A, U+FA12->U+6674, U+FA15->U+51DE, U+FA16->U+732A, U+FA17->U+76CA, U+FA18->U+793C, U+FA19->U+795E, U+FA1A->U+7965, U+FA1B->U+798F, U+FA1C->U+9756, U+FA1D->U+7CBE,  \
+    U+FA1E->U+7FBD, U+FA20->U+8612, U+FA22->U+8AF8, U+FA25->U+9038, U+FA26->U+90FD, U+FA2A->U+98EF, U+FA2B->U+98FC, U+FA2C->U+9928, U+FA2D->U+9DB4, U+FA30->U+4FAE, U+FA31->U+50E7, U+FA32->U+514D, U+FA33->U+52C9, U+FA34->U+52E4, U+FA35->U+5351, U+FA36->U+559D,  \
+    U+FA37->U+5606, U+FA38->U+5668, U+FA39->U+5840, U+FA3A->U+58A8, U+FA3B->U+5C64, U+FA3C->U+5C6E, U+FA3D->U+6094, U+FA3E->U+6168, U+FA3F->U+618E, U+FA40->U+61F2, U+FA41->U+654F, U+FA42->U+65E2, U+FA43->U+6691, U+FA44->U+6885, U+FA45->U+6D77, U+FA46->U+6E1A,  \
+    U+FA47->U+6F22, U+FA48->U+716E, U+FA49->U+722B, U+FA4A->U+7422, U+FA4B->U+7891, U+FA4C->U+793E, U+FA4D->U+7949, U+FA4E->U+7948, U+FA4F->U+7950, U+FA50->U+7956, U+FA51->U+795D, U+FA52->U+798D, U+FA53->U+798E, U+FA54->U+7A40, U+FA55->U+7A81, U+FA56->U+7BC0,  \
+    U+FA57->U+7DF4, U+FA58->U+7E09, U+FA59->U+7E41, U+FA5A->U+7F72, U+FA5B->U+8005, U+FA5C->U+81ED, U+FA5D->U+8279, U+FA5E->U+8279, U+FA5F->U+8457, U+FA60->U+8910, U+FA61->U+8996, U+FA62->U+8B01, U+FA63->U+8B39, U+FA64->U+8CD3, U+FA65->U+8D08, U+FA66->U+8FB6,  \
+    U+FA67->U+9038, U+FA68->U+96E3, U+FA69->U+97FF, U+FA6A->U+983B, U+FA70->U+4E26, U+FA71->U+51B5, U+FA72->U+5168, U+FA73->U+4F80, U+FA74->U+5145, U+FA75->U+5180, U+FA76->U+52C7, U+FA77->U+52FA, U+FA78->U+559D, U+FA79->U+5555, U+FA7A->U+5599, U+FA7B->U+55E2,  \
+    U+FA7C->U+585A, U+FA7D->U+58B3, U+FA7E->U+5944, U+FA7F->U+5954, U+FA80->U+5A62, U+FA81->U+5B28, U+FA82->U+5ED2, U+FA83->U+5ED9, U+FA84->U+5F69, U+FA85->U+5FAD, U+FA86->U+60D8, U+FA87->U+614E, U+FA88->U+6108, U+FA89->U+618E, U+FA8A->U+6160, U+FA8B->U+61F2,  \
+    U+FA8C->U+6234, U+FA8D->U+63C4, U+FA8E->U+641C, U+FA8F->U+6452, U+FA90->U+6556, U+FA91->U+6674, U+FA92->U+6717, U+FA93->U+671B, U+FA94->U+6756, U+FA95->U+6B79, U+FA96->U+6BBA, U+FA97->U+6D41, U+FA98->U+6EDB, U+FA99->U+6ECB, U+FA9A->U+6F22, U+FA9B->U+701E,  \
+    U+FA9C->U+716E, U+FA9D->U+77A7, U+FA9E->U+7235, U+FA9F->U+72AF, U+FAA0->U+732A, U+FAA1->U+7471, U+FAA2->U+7506, U+FAA3->U+753B, U+FAA4->U+761D, U+FAA5->U+761F, U+FAA6->U+76CA, U+FAA7->U+76DB, U+FAA8->U+76F4, U+FAA9->U+774A, U+FAAA->U+7740, U+FAAB->U+78CC,  \
+    U+FAAC->U+7AB1, U+FAAD->U+7BC0, U+FAAE->U+7C7B, U+FAAF->U+7D5B, U+FAB0->U+7DF4, U+FAB1->U+7F3E, U+FAB2->U+8005, U+FAB3->U+8352, U+FAB4->U+83EF, U+FAB5->U+8779, U+FAB6->U+8941, U+FAB7->U+8986, U+FAB8->U+8996, U+FAB9->U+8ABF, U+FABA->U+8AF8, U+FABB->U+8ACB,  \
+    U+FABC->U+8B01, U+FABD->U+8SAFE, U+FABE->U+8AED, U+FABF->U+8B39, U+FAC0->U+8B8A, U+FAC1->U+8D08, U+FAC2->U+8F38, U+FAC3->U+9072, U+FAC4->U+9199, U+FAC5->U+9276, U+FAC6->U+967C, U+FAC7->U+96E3, U+FAC8->U+9756, U+FAC9->U+97DB, U+FACA->U+97FF, U+FACB->U+980B,  \
@@ -767 +767 @@
-## searchd settings
+## searched settings
@@ -770 +770 @@
-searchd
+searched
@@ -782,2 +782,2 @@
-	# log file, searchd run info is logged here
-	# optional, default is 'searchd.log'
+	# log file, searched run info is logged here
+	# optional, default is 'searched.log'
@@ -802 +802 @@
-	# PID file, searchd process ID file name
+	# PID file, searched process ID file name
@@ -819 +819 @@
-	# whether to unlink .old index copies on succesful rotation.
+	# whether to unlink .old index copies on successful rotation.
@@ -837 +837 @@
-	# shared between all instances of searchd, disables attr flushes!
+	# shared between all instances of searched, disables attr flushes!
@@ -847 +847 @@
-	# searchd will (try to) log crashed query to 'crash_log_path.PID' file
+	# searched will (try to) log crashed query to 'crash_log_path.PID' file
--- ./sphinxapi.py	original
+++ ./sphinxapi.py	fixed
@@ -4 +4 @@
-# Python version of Sphinx searchd client (Python API)
+# Python version of Sphinx searched client (Python API)
@@ -24,8 +24,8 @@
-# known searchd commands
-SEARCHD_COMMAND_SEARCH		= 0
-SEARCHD_COMMAND_EXCERPT		= 1
-SEARCHD_COMMAND_UPDATE		= 2
-SEARCHD_COMMAND_KEYWORDS	= 3
-SEARCHD_COMMAND_PERSIST		= 4
-SEARCHD_COMMAND_STATUS		= 5
-SEARCHD_COMMAND_FLUSHATTRS	= 7
+# known searched commands
+SEARCHED_COMMAND_SEARCH		= 0
+SEARCHED_COMMAND_EXCERPT		= 1
+SEARCHED_COMMAND_UPDATE		= 2
+SEARCHED_COMMAND_KEYWORDS	= 3
+SEARCHED_COMMAND_PERSIST		= 4
+SEARCHED_COMMAND_STATUS		= 5
+SEARCHED_COMMAND_FLUSHATTRS	= 7
@@ -41,5 +41,5 @@
-# known searchd status codes
-SEARCHD_OK				= 0
-SEARCHD_ERROR			= 1
-SEARCHD_RETRY			= 2
-SEARCHD_WARNING			= 3
+# known searched status codes
+SEARCHED_OK				= 0
+SEARCHED_ERROR			= 1
+SEARCHED_RETRY			= 2
+SEARCHED_WARNING			= 3
@@ -60 +60 @@
-SPH_RANK_WORDCOUNT		= 3 # simple word-count weighting, rank is a weighted sum of per-field keyword occurence counts
+SPH_RANK_WORDCOUNT		= 3 # simple word-count weighting, rank is a weighted sum of per-field keyword occurrence counts
@@ -118,10 +118,10 @@
-		self._host			= 'localhost'					# searchd host (default is "localhost")
-		self._port			= 9312							# searchd port (default is 9312)
-		self._path			= None							# searchd unix-domain socket path
-		self._socket		= None
-		self._offset		= 0								# how much records to seek from result-set start (default is 0)
-		self._limit			= 20							# how much records to return from result-set starting at offset (default is 20)
-		self._mode			= SPH_MATCH_ALL					# query matching mode (default is SPH_MATCH_ALL)
-		self._weights		= []							# per-field weights (default is 1 for all fields)
-		self._sort			= SPH_SORT_RELEVANCE			# match sorting mode (default is SPH_SORT_RELEVANCE)
-		self._sortby		= ''							# attribute to sort by (defualt is "")
+		self._host			= 'localhost'					# searched host (default is "localhost")
+		self._port			= 9312							# searched port (default is 9312)
+		self._path			= None							# searched unix-domain socket path
+		self._socket		= None
+		self._offset		= 0								# how much records to seek from result-set start (default is 0)
+		self._limit			= 20							# how much records to return from result-set starting at offset (default is 20)
+		self._mode			= SPH_MATCH_ALL					# query matching mode (default is SPH_MATCH_ALL)
+		self._weights		= []							# per-field weights (default is 1 for all fields)
+		self._sort			= SPH_SORT_RELEVANCE			# match sorting mode (default is SPH_SORT_RELEVANCE)
+		self._sortby		= ''							# attribute to sort by (default is "")
@@ -174 +174 @@
-		Set searchd server host and port.
+		Set searched server host and port.
@@ -198 +198 @@
-		INTERNAL METHOD, DO NOT CALL. Connects to searchd server.
+		INTERNAL METHOD, DO NOT CALL. Connects to searched server.
@@ -233 +233 @@
-			self._error = 'expected searchd protocol version, got %s' % v
+			self._error = 'expected searched protocol version, got %s' % v
@@ -243 +243 @@
-		INTERNAL METHOD, DO NOT CALL. Gets and checks response packet from searchd server.
+		INTERNAL METHOD, DO NOT CALL. Gets and checks response packet from searched server.
@@ -263,4 +263,4 @@
-				self._error = 'failed to read searchd response (status=%s, ver=%s, len=%s, read=%s)' \
-					% (status, ver, length, read)
-			else:
-				self._error = 'received zero-sized searchd response'
+				self._error = 'failed to read searched response (status=%s, ver=%s, len=%s, read=%s)' \
+					% (status, ver, length, read)
+			else:
+				self._error = 'received zero-sized searched response'
@@ -270 +270 @@
-		if status==SEARCHD_WARNING:
+		if status==SEARCHED_WARNING:
@@ -275,2 +275,2 @@
-		if status==SEARCHD_ERROR:
-			self._error = 'searchd error: '+response[4:]
+		if status==SEARCHED_ERROR:
+			self._error = 'searched error: '+response[4:]
@@ -279,2 +279,2 @@
-		if status==SEARCHD_RETRY:
-			self._error = 'temporary searchd error: '+response[4:]
+		if status==SEARCHED_RETRY:
+			self._error = 'temporary searched error: '+response[4:]
@@ -283 +283 @@
-		if status!=SEARCHD_OK:
+		if status!=SEARCHED_OK:
@@ -289 +289 @@
-			self._warning = 'searchd command v.%d.%d older than client\'s v.%d.%d, some options might not work' \
+			self._warning = 'searched command v.%d.%d older than client\'s v.%d.%d, some options might not work' \
@@ -381 +381 @@
-		Only match records if document ID is beetwen $min and $max (inclusive).
+		Only match records if document ID is between $min and $max (inclusive).
@@ -407 +407 @@
-		Only match records if 'attribute' value is beetwen 'min_' and 'max_' (inclusive).
+		Only match records if 'attribute' value is between 'min_' and 'max_' (inclusive).
@@ -497 +497 @@
-		Connect to searchd server and run given search query.
+		Connect to searched server and run given search query.
@@ -509 +509 @@
-		if results[0]['status'] == SEARCHD_ERROR:
+		if results[0]['status'] == SEARCHED_ERROR:
@@ -636 +636 @@
-		req = pack('>HHLLL', SEARCHD_COMMAND_SEARCH, VER_COMMAND_SEARCH, length, 0, len(self._reqs))+req
+		req = pack('>HHLLL', SEARCHED_COMMAND_SEARCH, VER_COMMAND_SEARCH, length, 0, len(self._reqs))+req
@@ -659 +659 @@
-			if status != SEARCHD_OK:
+			if status != SEARCHED_OK:
@@ -665 +665 @@
-				if status == SEARCHD_WARNING:
+				if status == SEARCHED_WARNING:
@@ -777 +777 @@
-		Connect to searchd server and generate exceprts from given documents.
+		Connect to searched server and generate exceprts from given documents.
@@ -868 +868 @@
-		req = pack('>2HL', SEARCHD_COMMAND_EXCERPT, VER_COMMAND_EXCERPT, length)+req
+		req = pack('>2HL', SEARCHED_COMMAND_EXCERPT, VER_COMMAND_EXCERPT, length)+req
@@ -953 +953 @@
-		req = pack ( '>2HL', SEARCHD_COMMAND_UPDATE, VER_COMMAND_UPDATE, length ) + req
+		req = pack ( '>2HL', SEARCHED_COMMAND_UPDATE, VER_COMMAND_UPDATE, length ) + req
@@ -967 +967 @@
-		Connect to searchd server, and generate keywords list for a given query.
+		Connect to searched server, and generate keywords list for a given query.
@@ -986 +986 @@
-		req = pack ( '>2HL', SEARCHD_COMMAND_KEYWORDS, VER_COMMAND_KEYWORDS, length ) + req
+		req = pack ( '>2HL', SEARCHED_COMMAND_KEYWORDS, VER_COMMAND_KEYWORDS, length ) + req
@@ -1036 +1036 @@
-		req = pack ( '>2HLL', SEARCHD_COMMAND_STATUS, VER_COMMAND_STATUS, 4, 1 )
+		req = pack ( '>2HLL', SEARCHED_COMMAND_STATUS, VER_COMMAND_STATUS, 4, 1 )
@@ -1072 +1072 @@
-		request = pack ( '>hhII', SEARCHD_COMMAND_PERSIST, 0, 4, 1 )
+		request = pack ( '>hhII', SEARCHED_COMMAND_PERSIST, 0, 4, 1 )
@@ -1094 +1094 @@
-		request = pack ( '>hhI', SEARCHD_COMMAND_FLUSHATTRS, VER_COMMAND_FLUSHATTRS, 0 ) # cmd, ver, bodylen
+		request = pack ( '>hhI', SEARCHED_COMMAND_FLUSHATTRS, VER_COMMAND_FLUSHATTRS, 0 ) # cmd, ver, bodylen
--- ./kv78turbo-api.py	original
+++ ./kv78turbo-api.py	fixed
@@ -186 +186 @@
-	    newrow['WheelChairAccessible'] = row['WheelChairAccessible'] # Because of agencies not implementing the accessiblity tag in KV6, we're better off ignoring UKNOWNS unfortunately
+	    newrow['WheelChairAccessible'] = row['WheelChairAccessible'] # Because of agencies not implementing the accessibility tag in KV6, we're better off ignoring UNKNOWNS unfortunately
@@ -237 +237 @@
-    if row['TripStopStatus'] in set(['ARRIVED', 'PASSED']): # , 'DRIVING']): Driving alleen nemen als kleinste waarde uit lijn, gegeven dat er geen ARRIVED/PASSED is
+    if row['TripStopStatus'] in set(['ARRIVED', 'PASSED']): # , 'DRIVING']): Driving alleen nemen also kleinste waarde uit lijn, gegeven dat er geen ARRIVED/PASSED is
--- ./accessibility.tsv	original
+++ ./accessibility.tsv	fixed
@@ -68,2809 +68,2809 @@
-42055302|Wassenaar, Admiraal Helfrichlaan|ACCESSIBLE|NOTACCESSIBLE
-42056802|Wassenaar, Papegaaienlaan|ACCESSIBLE|NOTACCESSIBLE
-42061301|Zoetermeer, Gouderakstraat|ACCESSIBLE|NOTACCESSIBLE
-42061701|Zoetermeer, Houtsingel|ACCESSIBLE|NOTACCESSIBLE
-42067702|Den Haag, Prinses Marijkestraat|ACCESSIBLE|NOTACCESSIBLE
-32003602|Loevesteinlaan|ACCESSIBLE|NOTACCESSIBLE
-42015701|Den Haag, Lozerlaan|ACCESSIBLE|NOTACCESSIBLE
-42015702|Den Haag, Lozerlaan|ACCESSIBLE|NOTACCESSIBLE
-54142030|Den Haag, Waalsdorperlaan|ACCESSIBLE|NOTACCESSIBLE
-42064201|Zoetermeer, Regenboogsingel|ACCESSIBLE|NOTACCESSIBLE
-32002724|Station Hollands Spoor|ACCESSIBLE|NOTACCESSIBLE
-32003708|Melis Stokelaan|ACCESSIBLE|NOTACCESSIBLE
-42055602|Wassenaar, Burchtlaan|ACCESSIBLE|NOTACCESSIBLE
-32002926|Jacob Catsstraat|ACCESSIBLE|NOTACCESSIBLE
-32003916|Regulusweg|ACCESSIBLE|NOTACCESSIBLE
-42017801|Den Haag, Parnassia|ACCESSIBLE|NOTACCESSIBLE
-32003327|De Dreef|ACCESSIBLE|NOTACCESSIBLE
-32003339|Lozerlaan|ACCESSIBLE|NOTACCESSIBLE
-42056202|Wassenaar, de Kieviet|ACCESSIBLE|NOTACCESSIBLE
-32001913|Thorbeckelaan|ACCESSIBLE|NOTACCESSIBLE
-32003211|Castricumplein|ACCESSIBLE|NOTACCESSIBLE
-42000602|Den Hoorn, RK Kerk|ACCESSIBLE|NOTACCESSIBLE
-42024602|Honselersdijk, Strijplaan|ACCESSIBLE|NOTACCESSIBLE
-42035001|Maasland, Viaduct|ACCESSIBLE|NOTACCESSIBLE
-42067001|Delfgauw, Hoefsmidstraat|ACCESSIBLE|NOTACCESSIBLE
-074203|Van Boshuizenstraat|ACCESSIBLE|UNKNOWN
-42004201|Delft, Brahmslaan|ACCESSIBLE|ACCESSIBLE
-42017501|Den Haag, Ockenrode|ACCESSIBLE|ACCESSIBLE
-42007802|Delft, Zuidpoort|ACCESSIBLE|NOTACCESSIBLE
-50003320|Utrecht, Juliusstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000402|Bronovo Ziekenhuis|NOTACCESSIBLE|NOTACCESSIBLE
-32002908|Delftselaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000201|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
-32000214|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
-32000312|Plesmanweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000735|Rusthoekstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001915|Perenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001872|Westduin|NOTACCESSIBLE|NOTACCESSIBLE
-32000218|Harstenhoekplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000204|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
-32000604|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
-32002508|Saffierhorst|NOTACCESSIBLE|NOTACCESSIBLE
-32005212|Paulus Potterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42000201|Den Hoorn, Hof van Delftstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42000301|Schipluiden, Manege|NOTACCESSIBLE|NOTACCESSIBLE
-42003902|Delft, Krakeelpolderweg|NOTACCESSIBLE|NOTACCESSIBLE
-42005308|Delft, Station Delft|NOTACCESSIBLE|NOTACCESSIBLE
-51380090|Schalkwijk, Spoorlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51280940|Houten, De Muren|NOTACCESSIBLE|NOTACCESSIBLE
-51380290|'t Goy, Wickenburghseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000980|Utrecht, Anne Frankplein|NOTACCESSIBLE|NOTACCESSIBLE
-59151380|Utrecht, Berezinadreef|ACCESSIBLE|ACCESSIBLE
-50002370|Utrecht, Karperstraat|ACCESSIBLE|ACCESSIBLE
-50006830|Utrecht, Maliebaan|NOTACCESSIBLE|ACCESSIBLE
-50000320|Utrecht, Kleine Singel|NOTACCESSIBLE|ACCESSIBLE
-50200110|Zeist, De Dreef/Panweg|NOTACCESSIBLE|ACCESSIBLE
-59230030|Haarzuilens, Joostenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51200500|Vleuten, Station|NOTACCESSIBLE|NOTACCESSIBLE
-50005000|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50001270|Utrecht, Socrateslaan|NOTACCESSIBLE|ACCESSIBLE
-59330110|Kockengen, Dreef|NOTACCESSIBLE|NOTACCESSIBLE
-50001690|Utrecht, Kemal Ataturkstraat|NOTACCESSIBLE|ACCESSIBLE
-50001150|Utrecht, Diakonessenhuis|NOTACCESSIBLE|ACCESSIBLE
-50006730|Utrecht, Tolsteegbrug|NOTACCESSIBLE|ACCESSIBLE
-50006452|Utrecht, Linschotensingel|NOTACCESSIBLE|ACCESSIBLE
-50001282|Utrecht, Socrateslaan|NOTACCESSIBLE|ACCESSIBLE
-50006870|Utrecht, Oudwijkerdwarsstraat|NOTACCESSIBLE|ACCESSIBLE
-50000240|Utrecht, Winklerlaan|NOTACCESSIBLE|ACCESSIBLE
-50200891|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|ACCESSIBLE
-50007420|Utrecht, Prinsesselaan|NOTACCESSIBLE|ACCESSIBLE
-59151330|Utrecht, Atlasdreef|ACCESSIBLE|ACCESSIBLE
-59150770|Utrecht, Nijldreef|ACCESSIBLE|ACCESSIBLE
-50100540|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
-59150620|Utrecht, Pionstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50001330|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
-51280690|Houten, Oude Dorp|ACCESSIBLE|ACCESSIBLE
-50100560|Utrecht-De Uithof, WKZ|ACCESSIBLE|NOTACCESSIBLE
-50007080|Utrecht, Nijverheidsweg|ACCESSIBLE|NOTACCESSIBLE
-50200570|Zeist, Godfried van Seystln|ACCESSIBLE|NOTACCESSIBLE
-59250610|Maarssenbroek, Antilopespoor|ACCESSIBLE|NOTACCESSIBLE
-51200010|De Meern, Europaweg|ACCESSIBLE|NOTACCESSIBLE
-50008080|Utrecht, Beethovenlaan|ACCESSIBLE|NOTACCESSIBLE
-51111280|De Meern, De Balije|ACCESSIBLE|NOTACCESSIBLE
-51110100|De Meern, Meernbrug|ACCESSIBLE|NOTACCESSIBLE
-59390150|Den Dolder, Pleineslaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200180|Maartensdijk, Koningin Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000841|Utrecht, Majellapark|ACCESSIBLE|NOTACCESSIBLE
-51200122|De Meern, Veldhuizen|ACCESSIBLE|NOTACCESSIBLE
-59250840|Maarssenbroek, Het Kwadrant|ACCESSIBLE|NOTACCESSIBLE
-51200140|De Meern, Europaweg|ACCESSIBLE|NOTACCESSIBLE
-59250170|Maarssen, Kaatsbaan|ACCESSIBLE|NOTACCESSIBLE
-51200120|De Meern, Veldhuizen|ACCESSIBLE|NOTACCESSIBLE
-50100410|Utrecht, Rijnsweerd Noord|ACCESSIBLE|NOTACCESSIBLE
-59250820|Maarssenbroek, Antilopespoor|ACCESSIBLE|NOTACCESSIBLE
-51110110|De Meern, Meernbrug|ACCESSIBLE|NOTACCESSIBLE
-50000050|Utrecht, 24 Oktoberplein|ACCESSIBLE|NOTACCESSIBLE
-50005210|Utrecht, Beethovenlaan|ACCESSIBLE|NOTACCESSIBLE
-59150280|Utrecht, Carnegiedreef|ACCESSIBLE|ACCESSIBLE
-59150011|Maarssen, Rekreatieoord|ACCESSIBLE|NOTACCESSIBLE
-59250160|Maarssen, Kaatsbaan|ACCESSIBLE|NOTACCESSIBLE
-51280500|Houten, Koedijk|ACCESSIBLE|ACCESSIBLE
-59150070|Utrecht, Oud Zuilen|ACCESSIBLE|ACCESSIBLE
-51200320|Vleuten, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100680|Bilthoven,  RIVM|NOTACCESSIBLE|NOTACCESSIBLE
-59140091|Utrecht, Mesonweg|NOTACCESSIBLE|NOTACCESSIBLE
-51110520|De Meern, Zuiderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
-50001010|Utrecht, Sterrenwijk|NOTACCESSIBLE|NOTACCESSIBLE
-51220950|Nieuwegein, Berkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50200700|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50002230|Utrecht, Nicolaas Beetsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59140041|Utrecht, Thoriumweg|NOTACCESSIBLE|NOTACCESSIBLE
-51320062|IJsselstein, Mandenmaker|NOTACCESSIBLE|NOTACCESSIBLE
-50310110|Austerlitz, Waterlooweg|NOTACCESSIBLE|NOTACCESSIBLE
-50001840|Utrecht, Willem van Noortstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220132|Nieuwegein, De Kempenaerpark|NOTACCESSIBLE|NOTACCESSIBLE
-51380340|Houten, Poeldijk|NOTACCESSIBLE|NOTACCESSIBLE
-50001450|Utrecht, Sint Jacobsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50005505|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51280580|Houten, Molenzoom|ACCESSIBLE|ACCESSIBLE
-022943|Station Sloterdijk|ACCESSIBLE|UNKNOWN
-51180060|Nieuwegein, Ravenswade|NOTACCESSIBLE|NOTACCESSIBLE
-59151750|Utrecht, J.M.de Muinck Keizerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50001411|Utrecht, Vondellaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200060|Hollandsche Rading, Plantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-51221000|Nieuwegein, Waterbies|NOTACCESSIBLE|NOTACCESSIBLE
-50220185|Bilthoven, Kwikstaartlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220160|Nieuwegein, Landmansweide|NOTACCESSIBLE|NOTACCESSIBLE
-50000970|Utrecht, Anne Frankplein|NOTACCESSIBLE|NOTACCESSIBLE
-50201080|Zeist, Verzetslaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220760|Nieuwegein, Constructieweg|NOTACCESSIBLE|NOTACCESSIBLE
-51380150|Schalkwijk, Van Gaalen|NOTACCESSIBLE|NOTACCESSIBLE
-51200230|Vleuten, Bottensteinweg|NOTACCESSIBLE|NOTACCESSIBLE
-50190060|Bunnik, Rhijnauwenselaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200770|Zeist, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
-50002110|Utrecht, 5 Mei Plein|NOTACCESSIBLE|NOTACCESSIBLE
-51220360|Nieuwegein, Blauwe Brug|NOTACCESSIBLE|NOTACCESSIBLE
-50001480|Utrecht, Oudenoord|NOTACCESSIBLE|NOTACCESSIBLE
-50000441|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
-50001430|Utrecht, Rozenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59230110|Haarzuilens, Gieltjesdorp|NOTACCESSIBLE|NOTACCESSIBLE
-50490130|Werkhoven, Provincialeweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220791|Nieuwegein, Rembrandthage|NOTACCESSIBLE|NOTACCESSIBLE
-50201070|Zeist, Handelscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-51200360|Vleuten, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50490060|Werkhoven, Sportpark|NOTACCESSIBLE|NOTACCESSIBLE
-59390080|Den Dolder, Hertenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51221010|Nieuwegein, Raalterveste|NOTACCESSIBLE|NOTACCESSIBLE
-50310020|Austerlitz, KNVB-Sportcentrum|NOTACCESSIBLE|NOTACCESSIBLE
-59150480|Utrecht, De Bazelstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50200920|Zeist, Griftlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50003310|Utrecht, Juliusstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59330100|Kockengen, Dreef|NOTACCESSIBLE|NOTACCESSIBLE
-50001232|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
-50002260|Utrecht, Hoogh Boulandt|NOTACCESSIBLE|NOTACCESSIBLE
-50005510|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-59250850|Maarssenbroek, Het Kwadrant|ACCESSIBLE|NOTACCESSIBLE
-59151850|Utrecht, Arizonadreef|NOTACCESSIBLE|NOTACCESSIBLE
-50007040|Utrecht, Vlampijpstraat|NOTACCESSIBLE|NOTACCESSIBLE
-095243|Bullewijk|ACCESSIBLE|UNKNOWN
-59140100|Utrecht, Mesonweg|NOTACCESSIBLE|NOTACCESSIBLE
-59151320|Utrecht, Oderdreef|NOTACCESSIBLE|ACCESSIBLE
-50200140|Zeist, Nepveulaan|NOTACCESSIBLE|NOTACCESSIBLE
-50003130|Utrecht, De Koppel|NOTACCESSIBLE|NOTACCESSIBLE
-50000430|Utrecht, Viaduct|NOTACCESSIBLE|NOTACCESSIBLE
-32008104|Centrum-West|NOTACCESSIBLE|ACCESSIBLE
-32002501|Overbosch|ACCESSIBLE|ACCESSIBLE
-42019701|Den Haag, De Uithof|NOTACCESSIBLE|NOTACCESSIBLE
-42019801|Den Haag, Veenweg|NOTACCESSIBLE|NOTACCESSIBLE
-42019802|Den Haag, Veenweg|NOTACCESSIBLE|NOTACCESSIBLE
-42019901|Den Haag, Veluweplein|NOTACCESSIBLE|NOTACCESSIBLE
-42019902|Den Haag, Veluweplein|NOTACCESSIBLE|NOTACCESSIBLE
-42020001|Den Haag, van Essendijk|NOTACCESSIBLE|NOTACCESSIBLE
-42020002|Den Haag, van Essendijk|NOTACCESSIBLE|NOTACCESSIBLE
-42020301|Den Haag, Wellant College Madestein|NOTACCESSIBLE|NOTACCESSIBLE
-42020302|Den Haag, Wellant College Madestein|NOTACCESSIBLE|NOTACCESSIBLE
-51280650|Houten, De Meren|ACCESSIBLE|ACCESSIBLE
-50000420|Utrecht, Herenweg|NOTACCESSIBLE|NOTACCESSIBLE
-50006890|Utrecht, Oosterstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51280960|Houten, Weteringshoek|NOTACCESSIBLE|NOTACCESSIBLE
-59100080|Groenekan, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-51220011|Nieuwegein, Sporttunnel|NOTACCESSIBLE|NOTACCESSIBLE
-51221040|Nieuwegein, Fokkesteeg|NOTACCESSIBLE|NOTACCESSIBLE
-50220040|Bilthoven, Station|NOTACCESSIBLE|NOTACCESSIBLE
-50310140|Austerlitz, De Pyramide|NOTACCESSIBLE|NOTACCESSIBLE
-50005508|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51111250|Utrecht, Utrechtseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50390060|Odijk, Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
-59250650|Utrecht, Computerweg|NOTACCESSIBLE|NOTACCESSIBLE
-50006390|Utrecht, Waalstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50005516|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50390140|Odijk, Eikelaar|NOTACCESSIBLE|NOTACCESSIBLE
-50201310|Zeist, Kritzingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200421|Zeist, Kromme-Rijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250360|Maarssenbroek, Bloem-Boomstede|NOTACCESSIBLE|NOTACCESSIBLE
-50002400|Utrecht, Kastelenplantsoen|ACCESSIBLE|ACCESSIBLE
-59250480|Maarssenbroek, Kamelenspoor|NOTACCESSIBLE|NOTACCESSIBLE
-50200560|Zeist, Couwenhoven|NOTACCESSIBLE|NOTACCESSIBLE
-59140051|Utrecht, Kernweg|NOTACCESSIBLE|NOTACCESSIBLE
-51110230|Vleuten, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000540|Utrecht, Nijenoord|NOTACCESSIBLE|NOTACCESSIBLE
-51340551|Vianen, Marconiweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220872|Nieuwegein, Doorslag|NOTACCESSIBLE|NOTACCESSIBLE
-51220541|Nieuwegein, De Bongenaar|NOTACCESSIBLE|NOTACCESSIBLE
-50002150|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-51220711|Nieuwegein, Graaf Florisweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220851|Nieuwegein, IJsselsteinseweg|NOTACCESSIBLE|NOTACCESSIBLE
-51380060|Schalkwijk, Jhr. Ramweg|NOTACCESSIBLE|NOTACCESSIBLE
-59200120|Maartensdijk, Groenhorst|ACCESSIBLE|ACCESSIBLE
-51111160|Utrecht, Klifrakplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-59152000|Utrecht, Paranadreef|NOTACCESSIBLE|NOTACCESSIBLE
-51220012|Nieuwegein, Galvanibaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340070|Vianen, Rietkamp|NOTACCESSIBLE|NOTACCESSIBLE
-50291010|Bunnik, Station|NOTACCESSIBLE|NOTACCESSIBLE
-50002140|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50190070|Bunnik, Rhijnauwenselaan|NOTACCESSIBLE|NOTACCESSIBLE
-50390160|Odijk, Gaspeldoorn|NOTACCESSIBLE|NOTACCESSIBLE
-59390110|Huis ter Heide, Van Ostadelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220240|Nieuwegein, Koetsdrift|NOTACCESSIBLE|NOTACCESSIBLE
-59250240|Maarssen, Station/Bisonspoor|NOTACCESSIBLE|NOTACCESSIBLE
-50200520|Zeist, Nijenheim|NOTACCESSIBLE|NOTACCESSIBLE
-50100150|De Bilt, Hessenweg|ACCESSIBLE|ACCESSIBLE
-50220050|Bilthoven, Station|NOTACCESSIBLE|NOTACCESSIBLE
-59250180|Maarssen, Thorbeckelaan|NOTACCESSIBLE|NOTACCESSIBLE
-50001050|Utrecht, Stadionlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50201230|Zeist, Grote Koppel|NOTACCESSIBLE|NOTACCESSIBLE
-50000310|Utrecht, Kleine Singel|NOTACCESSIBLE|ACCESSIBLE
-50007200|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003412|Zweeloostraat|ACCESSIBLE|ACCESSIBLE
-32002858|Nieuwe Haven|NOTACCESSIBLE|NOTACCESSIBLE
-42011801|Den Haag, Eendenplein|NOTACCESSIBLE|NOTACCESSIBLE
-42019702|Den Haag, De Uithof|NOTACCESSIBLE|NOTACCESSIBLE
-32001917|Laan van Eik en Duinen|NOTACCESSIBLE|NOTACCESSIBLE
-32005102|Herenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42005304|Delft, Station Delft (Perron F)|NOTACCESSIBLE|NOTACCESSIBLE
-42012701|Den Haag, Guntersteinweg|NOTACCESSIBLE|NOTACCESSIBLE
-42059701|Zoetermeer, Centrum West (Perron A)|NOTACCESSIBLE|NOTACCESSIBLE
-022953|Station Sloterdijk|ACCESSIBLE|UNKNOWN
-022963|Isolatorweg|ACCESSIBLE|UNKNOWN
-022973|Isolatorweg|ACCESSIBLE|UNKNOWN
-032023|Jan v.Galenstraat|ACCESSIBLE|UNKNOWN
-032033|Jan v.Galenstraat|ACCESSIBLE|UNKNOWN
-032043|Burg.de Vlugtlaan|ACCESSIBLE|UNKNOWN
-032053|Burg.de Vlugtlaan|ACCESSIBLE|UNKNOWN
-043183|Henk Sneevlietweg|ACCESSIBLE|UNKNOWN
-043193|Henk Sneevlietweg|ACCESSIBLE|UNKNOWN
-043203|Heemstedestraat|ACCESSIBLE|UNKNOWN
-043213|Heemstedestraat|ACCESSIBLE|UNKNOWN
-043223|Station Lelylaan|ACCESSIBLE|UNKNOWN
-043233|Station Lelylaan|ACCESSIBLE|UNKNOWN
-043243|Postjesweg|ACCESSIBLE|UNKNOWN
-043253|Postjesweg|ACCESSIBLE|UNKNOWN
-071922|Station Zuid|ACCESSIBLE|UNKNOWN
-073423|Amstelveenseweg|ACCESSIBLE|UNKNOWN
-073433|Amstelveenseweg|ACCESSIBLE|UNKNOWN
-074003|Overamstel|ACCESSIBLE|UNKNOWN
-074013|Overamstel|ACCESSIBLE|UNKNOWN
-074043|Station RAI|ACCESSIBLE|UNKNOWN
-074053|Station RAI|ACCESSIBLE|UNKNOWN
-074083|Station Zuid|ACCESSIBLE|UNKNOWN
-074093|Station Zuid|ACCESSIBLE|UNKNOWN
-074123|De Boelelaan/VU|ACCESSIBLE|UNKNOWN
-074133|De Boelelaan/VU|ACCESSIBLE|UNKNOWN
-074163|A.J. Ernststraat|ACCESSIBLE|UNKNOWN
-074173|A.J. Ernststraat|ACCESSIBLE|UNKNOWN
-074213|Van Boshuizenstraat|ACCESSIBLE|UNKNOWN
-074243|Uilenstede|ACCESSIBLE|UNKNOWN
-074253|Uilenstede|ACCESSIBLE|UNKNOWN
-074283|Kronenburg|ACCESSIBLE|UNKNOWN
-074293|Kronenburg|ACCESSIBLE|UNKNOWN
-074323|Zonnestein|ACCESSIBLE|UNKNOWN
-074333|Zonnestein|ACCESSIBLE|UNKNOWN
-074363|Onderuit|ACCESSIBLE|UNKNOWN
-074373|Onderuit|ACCESSIBLE|UNKNOWN
-074403|Oranjebaan|ACCESSIBLE|UNKNOWN
-074413|Oranjebaan|ACCESSIBLE|UNKNOWN
-074503|Amstelveen Centrum|ACCESSIBLE|UNKNOWN
-074513|Amstelveen Centrum|ACCESSIBLE|UNKNOWN
-074543|Ouderkerkerlaan|ACCESSIBLE|UNKNOWN
-074553|Ouderkerkerlaan|ACCESSIBLE|UNKNOWN
-074583|Sportlaan|ACCESSIBLE|UNKNOWN
-074593|Sportlaan|ACCESSIBLE|UNKNOWN
-074623|Marne|ACCESSIBLE|UNKNOWN
-074633|Marne|ACCESSIBLE|UNKNOWN
-074663|Gondel|ACCESSIBLE|UNKNOWN
-074673|Gondel|ACCESSIBLE|UNKNOWN
-074703|Meent|ACCESSIBLE|UNKNOWN
-074713|Meent|ACCESSIBLE|UNKNOWN
-074743|Brink|ACCESSIBLE|UNKNOWN
-074753|Brink|ACCESSIBLE|UNKNOWN
-074783|Poortwachter|ACCESSIBLE|UNKNOWN
-074793|Poortwachter|ACCESSIBLE|UNKNOWN
-074963|Spinnerij|ACCESSIBLE|UNKNOWN
-074973|Spinnerij|ACCESSIBLE|UNKNOWN
-074983|Sacharovlaan|ACCESSIBLE|UNKNOWN
-074993|Sacharovlaan|ACCESSIBLE|UNKNOWN
-075003|Westwijk|ACCESSIBLE|UNKNOWN
-075013|Westwijk|ACCESSIBLE|UNKNOWN
-095003|Centraal Station|ACCESSIBLE|UNKNOWN
-095023|Nieuwmarkt|ACCESSIBLE|UNKNOWN
-095033|Nieuwmarkt|ACCESSIBLE|UNKNOWN
-095083|Waterlooplein|ACCESSIBLE|UNKNOWN
-095093|Waterlooplein|ACCESSIBLE|UNKNOWN
-095103|Weesperplein|ACCESSIBLE|UNKNOWN
-095113|Weesperplein|ACCESSIBLE|UNKNOWN
-095123|Wibautstraat|ACCESSIBLE|UNKNOWN
-095133|Wibautstraat|ACCESSIBLE|UNKNOWN
-095143|Amstelstation|ACCESSIBLE|UNKNOWN
-095153|Amstelstation|ACCESSIBLE|UNKNOWN
-095163|Van der Madeweg|ACCESSIBLE|UNKNOWN
-095173|Van der Madeweg|ACCESSIBLE|UNKNOWN
-095193|Spaklerweg|ACCESSIBLE|UNKNOWN
-095203|Strandvliet|ACCESSIBLE|UNKNOWN
-095213|Strandvliet|ACCESSIBLE|UNKNOWN
-095223|Station Bijlmer ArenA|ACCESSIBLE|UNKNOWN
-095233|Station Bijlmer ArenA|ACCESSIBLE|UNKNOWN
-095253|Bullewijk|ACCESSIBLE|UNKNOWN
-095263|Station Holendrecht |ACCESSIBLE|UNKNOWN
-095273|Station Holendrecht |ACCESSIBLE|UNKNOWN
-095283|Reigersbos|ACCESSIBLE|UNKNOWN
-095293|Reigersbos|ACCESSIBLE|UNKNOWN
-095303|Gein|ACCESSIBLE|UNKNOWN
-095313|Gein|ACCESSIBLE|UNKNOWN
-095403|Venserpolder|ACCESSIBLE|UNKNOWN
-095413|Venserpolder|ACCESSIBLE|UNKNOWN
-095423|Station Diemen-Zuid|ACCESSIBLE|UNKNOWN
-095433|Station Diemen-Zuid|ACCESSIBLE|UNKNOWN
-095443|Verrijn Stuartweg|ACCESSIBLE|UNKNOWN
-095453|Verrijn Stuartweg|ACCESSIBLE|UNKNOWN
-095463|Station Ganzenhoef|ACCESSIBLE|UNKNOWN
-095473|Station Ganzenhoef|ACCESSIBLE|UNKNOWN
-095483|Kraaienneststation|ACCESSIBLE|UNKNOWN
-095493|Kraaienneststation|ACCESSIBLE|UNKNOWN
-095503|Gaasperplas|ACCESSIBLE|UNKNOWN
-095513|Station Duivendrecht|ACCESSIBLE|UNKNOWN
-095523|Station Duivendrecht|ACCESSIBLE|UNKNOWN
-095553|Gaasperplas|ACCESSIBLE|UNKNOWN
-095623|Station Zuid|ACCESSIBLE|UNKNOWN
-095633|Overamstel|ACCESSIBLE|UNKNOWN
-095643|Van der Madeweg|ACCESSIBLE|UNKNOWN
-095653|Van der Madeweg|ACCESSIBLE|UNKNOWN
-095663|Spaklerweg|ACCESSIBLE|UNKNOWN
-095673|Spaklerweg|ACCESSIBLE|UNKNOWN
-2903|Monstersestraat|ACCESSIBLE|UNKNOWN
-2904|Monstersestraat|ACCESSIBLE|UNKNOWN
-3003|De La Reyweg|ACCESSIBLE|UNKNOWN
-3004|De La Reyweg|ACCESSIBLE|UNKNOWN
-32001601|Kraayensteinlaan|ACCESSIBLE|UNKNOWN
-32001602|Kraayensteinlaan|ACCESSIBLE|UNKNOWN
-32001711|Kapelaan Meereboerweg|ACCESSIBLE|UNKNOWN
-32001712|Kapelaan Meereboerweg|ACCESSIBLE|UNKNOWN
-32001810|Buitentuinen|ACCESSIBLE|UNKNOWN
-32001811|Buitentuinen|ACCESSIBLE|UNKNOWN
-32001919|Walnootstraat|ACCESSIBLE|UNKNOWN
-32001920|Walnootstraat|ACCESSIBLE|UNKNOWN
-32001921|Thorbeckelaan|ACCESSIBLE|UNKNOWN
-32001922|Thorbeckelaan|ACCESSIBLE|UNKNOWN
-32002606|Centraal Station|ACCESSIBLE|UNKNOWN
-32002607|Centraal Station|ACCESSIBLE|UNKNOWN
-32002820|MCH Westeinde|ACCESSIBLE|UNKNOWN
-32002822|MCH Westeinde|ACCESSIBLE|UNKNOWN
-32002824|Brouwersgracht|ACCESSIBLE|UNKNOWN
-32003101|Kamperfoeliestraat|ACCESSIBLE|UNKNOWN
-32003102|Kamperfoeliestraat|ACCESSIBLE|UNKNOWN
-32003103|Valkenboslaan|ACCESSIBLE|UNKNOWN
-32003104|Valkenboslaan|ACCESSIBLE|UNKNOWN
-32003107|Fahrenheitstraat|ACCESSIBLE|UNKNOWN
-32003108|Fahrenheitstraat|ACCESSIBLE|UNKNOWN
-32003203|Nieuwendamlaan|ACCESSIBLE|UNKNOWN
-32003204|Nieuwendamlaan|ACCESSIBLE|UNKNOWN
-32003205|Laan van Eik en Duinen|ACCESSIBLE|UNKNOWN
-32007601|Voorburg 't Loo|ACCESSIBLE|UNKNOWN
-32007602|Voorburg 't Loo|ACCESSIBLE|UNKNOWN
-32007603|Prinses Beatrixlaan|ACCESSIBLE|UNKNOWN
-32007604|Prinses Beatrixlaan|ACCESSIBLE|UNKNOWN
-32007703|Essesteijn|ACCESSIBLE|UNKNOWN
-32007704|Essesteijn|ACCESSIBLE|UNKNOWN
-32007705|Elzendreef|ACCESSIBLE|UNKNOWN
-32007706|Elzendreef|ACCESSIBLE|UNKNOWN
-32009501|Leidsenhage|ACCESSIBLE|UNKNOWN
-32009502|Leidsenhage|ACCESSIBLE|UNKNOWN
-32009503|Burgemeester Kolfschotenlaan|ACCESSIBLE|UNKNOWN
-32009506|Kastelenring|ACCESSIBLE|UNKNOWN
-42002801|Delft, Fuutlaan|ACCESSIBLE|ACCESSIBLE
-49000101|Lelystad, Lelycentre|ACCESSIBLE|UNKNOWN
-57142235|Amsterdam, Station Zuid|ACCESSIBLE|UNKNOWN
-57142260|Amsterdam, De Boelelaan/VU|ACCESSIBLE|UNKNOWN
-1707|Loosduinse Hoofdstraat|NOTACCESSIBLE|UNKNOWN
-1708|Loosduinse Hoofdstraat|NOTACCESSIBLE|UNKNOWN
-32001709|Burgemeester Hovylaan|NOTACCESSIBLE|UNKNOWN
-32001710|Burgemeester Hovylaan|NOTACCESSIBLE|UNKNOWN
-32002647|Oostinje|NOTACCESSIBLE|UNKNOWN
-32002648|Oostinje|NOTACCESSIBLE|UNKNOWN
-32003206|Laan van Eik en Duinen|NOTACCESSIBLE|UNKNOWN
-32009504|Burgemeester Kolfschotenlaan|NOTACCESSIBLE|UNKNOWN
-32009505|Kastelenring|NOTACCESSIBLE|UNKNOWN
-32009507|Dillenburgsingel|NOTACCESSIBLE|UNKNOWN
-32009508|Dillenburgsingel|NOTACCESSIBLE|UNKNOWN
-32007611|Voorburg 't Loo|NOTACCESSIBLE|ACCESSIBLE
-42044902|Rijswijk, 't Haantje|NOTACCESSIBLE|NOTACCESSIBLE
-32000228|Pompstationsweg|NOTACCESSIBLE|ACCESSIBLE
-32000309|Maurits de Brauwweg|ACCESSIBLE|ACCESSIBLE
-32000404|Bronovo Ziekenhuis|ACCESSIBLE|ACCESSIBLE
-32000406|Waalsdorperweg|ACCESSIBLE|ACCESSIBLE
-32000409|Theo Mann Bouwmeesterlaan|ACCESSIBLE|ACCESSIBLE
-32000411|Oostduinlaan|ACCESSIBLE|ACCESSIBLE
-32000417|Groenhovenstraat|ACCESSIBLE|ACCESSIBLE
-32000426|Jozef Israëlsplein|ACCESSIBLE|ACCESSIBLE
-32000427|Jozef Israëlsplein|ACCESSIBLE|ACCESSIBLE
-32000432|Van Alkemadelaan|ACCESSIBLE|ACCESSIBLE
-32000433|Van Alkemadelaan|ACCESSIBLE|ACCESSIBLE
-32000436|Weissenbruchstraat|ACCESSIBLE|ACCESSIBLE
-32000440|Breitnerlaan|ACCESSIBLE|ACCESSIBLE
-32000442|Laan van Clingendael|ACCESSIBLE|ACCESSIBLE
-32000447|Wassenaarseweg|ACCESSIBLE|ACCESSIBLE
-32000448|Wassenaarseweg|ACCESSIBLE|ACCESSIBLE
-32000717|Duinstraat|ACCESSIBLE|ACCESSIBLE
-32001103|Cornelis de Wittlaan|ACCESSIBLE|ACCESSIBLE
-32001106|Gemeentemuseum/Museon|ACCESSIBLE|ACCESSIBLE
-32001107|Gemeentemuseum/Museon|ACCESSIBLE|ACCESSIBLE
-32001112|Valeriusstraat|ACCESSIBLE|ACCESSIBLE
-32001113|Valeriusstraat|ACCESSIBLE|ACCESSIBLE
-32001125|Cornelis de Wittlaan|ACCESSIBLE|ACCESSIBLE
-32001201|Kwartellaan|ACCESSIBLE|ACCESSIBLE
-32001202|Kwartellaan|ACCESSIBLE|ACCESSIBLE
-32001203|Nieboerweg|ACCESSIBLE|ACCESSIBLE
-32001207|Haga Ziekenhuis|ACCESSIBLE|ACCESSIBLE
-32001208|Haga Ziekenhuis|ACCESSIBLE|ACCESSIBLE
-32001209|Houtrustweg|ACCESSIBLE|ACCESSIBLE
-32001210|Houtrustweg|ACCESSIBLE|ACCESSIBLE
-32001304|Kruisbeklaan|ACCESSIBLE|ACCESSIBLE
-32001307|Vliegenvangerlaan|ACCESSIBLE|ACCESSIBLE
-32001308|Vliegenvangerlaan|ACCESSIBLE|ACCESSIBLE
-32001403|Muurbloemweg|ACCESSIBLE|ACCESSIBLE
-32001404|Muurbloemweg|ACCESSIBLE|ACCESSIBLE
-32001406|Arabislaan|ACCESSIBLE|ACCESSIBLE
-32001408|de Savornin Lohmanlaan|ACCESSIBLE|ACCESSIBLE
-32001411|Aronskelkweg|ACCESSIBLE|ACCESSIBLE
-32001412|Aronskelkweg|ACCESSIBLE|ACCESSIBLE
-32001417|Lobelialaan|ACCESSIBLE|ACCESSIBLE
-32001418|Lobelialaan|ACCESSIBLE|ACCESSIBLE
-32001423|Hoefbladlaan|ACCESSIBLE|ACCESSIBLE
-32001424|Hoefbladlaan|ACCESSIBLE|ACCESSIBLE
-32001425|Teunisbloemplein|ACCESSIBLE|ACCESSIBLE
-32001429|De Savornin Lohmanplein|ACCESSIBLE|ACCESSIBLE
-32001514|Kijkduinsestraat|ACCESSIBLE|ACCESSIBLE
-32001516|Kijkduinsestraat|ACCESSIBLE|ACCESSIBLE
-32001914|Thorbeckelaan|ACCESSIBLE|ACCESSIBLE
-32002401|Malieveld|ACCESSIBLE|ACCESSIBLE
-32002503|Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
-32002504|Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
-32002506|Barnsteenhorst|ACCESSIBLE|ACCESSIBLE
-32002602|Centraal Station|NOTACCESSIBLE|ACCESSIBLE
-32002603|Centraal Station|NOTACCESSIBLE|ACCESSIBLE
-32002637|Theresiastraat|ACCESSIBLE|ACCESSIBLE
-32002638|Theresiastraat|ACCESSIBLE|ACCESSIBLE
-32002649|Juliana van Stolberglaan|ACCESSIBLE|ACCESSIBLE
-32002703|Huijgenspark|ACCESSIBLE|ACCESSIBLE
-32002825|Brouwersgracht|ACCESSIBLE|ACCESSIBLE
-32002849|Bierkade|ACCESSIBLE|ACCESSIBLE
-32002850|Bierkade|ACCESSIBLE|ACCESSIBLE
-32002880|Spui|ACCESSIBLE|ACCESSIBLE
-32002881|Spui|ACCESSIBLE|ACCESSIBLE
-32002882|Grote Markt|ACCESSIBLE|ACCESSIBLE
-32002883|Grote Markt|ACCESSIBLE|ACCESSIBLE
-32002925|Jacob Catsstraat|ACCESSIBLE|ACCESSIBLE
-32003119|Soestdijkseplein|ACCESSIBLE|ACCESSIBLE
-32003120|Soestdijkseplein|ACCESSIBLE|ACCESSIBLE
-32003121|De La Reyweg|ACCESSIBLE|ACCESSIBLE
-32003122|De La Reyweg|ACCESSIBLE|ACCESSIBLE
-32003129|Dierenselaan|ACCESSIBLE|ACCESSIBLE
-32003212|Castricumplein|ACCESSIBLE|ACCESSIBLE
-32003213|Monnickendamplein|ACCESSIBLE|ACCESSIBLE
-32003214|Monnickendamplein|ACCESSIBLE|ACCESSIBLE
-32003217|Leyenburg|ACCESSIBLE|ACCESSIBLE
-32003309|Bouwlustlaan|ACCESSIBLE|ACCESSIBLE
-32003323|Hertenrade|ACCESSIBLE|ACCESSIBLE
-32003341|Ambachtsweg|ACCESSIBLE|ACCESSIBLE
-32003361|Randveen|ACCESSIBLE|ACCESSIBLE
-32003372|Revalidatiecentrum|ACCESSIBLE|ACCESSIBLE
-32003411|Zweeloostraat|ACCESSIBLE|ACCESSIBLE
-32003831|Ledeganckplein|ACCESSIBLE|ACCESSIBLE
-32005209|Hendrik Ravesteijnplein|ACCESSIBLE|ACCESSIBLE
-32005210|Hendrik Ravesteijnplein|ACCESSIBLE|ACCESSIBLE
-32005301|Van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
-32005302|Van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
-32005303|Generaal Spoorlaan|ACCESSIBLE|ACCESSIBLE
-32005305|Huis te Landelaan|ACCESSIBLE|ACCESSIBLE
-32005306|Huis te Landelaan|ACCESSIBLE|ACCESSIBLE
-32005307|Rijswijkse Schouwburg|ACCESSIBLE|ACCESSIBLE
-32005308|Rijswijkse Schouwburg|ACCESSIBLE|ACCESSIBLE
-32005309|Dr. H. Colijnlaan|ACCESSIBLE|ACCESSIBLE
-32005310|Dr. H. Colijnlaan|ACCESSIBLE|ACCESSIBLE
-32005409|Prinses Beatrixlaan|ACCESSIBLE|ACCESSIBLE
-32005410|Prinses Beatrixlaan|ACCESSIBLE|ACCESSIBLE
-32005411|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
-32005412|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
-32005421|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
-32005422|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
-32005501|Sammersweg|ACCESSIBLE|ACCESSIBLE
-32005502|Sammersweg|ACCESSIBLE|ACCESSIBLE
-32005503|De Schilp|ACCESSIBLE|ACCESSIBLE
-32005504|De Schilp|ACCESSIBLE|ACCESSIBLE
-32005510|Minister van den Tempellaan|ACCESSIBLE|ACCESSIBLE
-32005514|Sir Winston Churchilllaan|ACCESSIBLE|ACCESSIBLE
-32005515|Sir Winston Churchilllaan|ACCESSIBLE|ACCESSIBLE
-32005519|Prinses Marijkesingel|ACCESSIBLE|ACCESSIBLE
-32005520|Prinses Marijkesingel|ACCESSIBLE|ACCESSIBLE
-32005601|Wethouder Brederodelaan|ACCESSIBLE|ACCESSIBLE
-32005602|Wethouder Brederodelaan|ACCESSIBLE|ACCESSIBLE
-32005603|Albert Schweitzerlaan|ACCESSIBLE|ACCESSIBLE
-32005604|Albert Schweitzerlaan|ACCESSIBLE|ACCESSIBLE
-32005605|Aletta Jacobsstraat|ACCESSIBLE|ACCESSIBLE
-32005623|Pater Doumenstraat|ACCESSIBLE|ACCESSIBLE
-32005624|Pater Doumenstraat|ACCESSIBLE|ACCESSIBLE
-32005701|Admiraal Helfrichsingel|ACCESSIBLE|ACCESSIBLE
-32005702|Admiraal Helfrichsingel|ACCESSIBLE|ACCESSIBLE
-32005944|Ypenburg Centrum|ACCESSIBLE|ACCESSIBLE
-32005945|Ypenburg Centrum|ACCESSIBLE|ACCESSIBLE
-32005946|Anthony Fokkersingel|NOTACCESSIBLE|ACCESSIBLE
-32005947|Anthony Fokkersingel|ACCESSIBLE|ACCESSIBLE
-32007211|Leidschendam-Voorburg|ACCESSIBLE|ACCESSIBLE
-32007212|Leidschendam-Voorburg|NOTACCESSIBLE|ACCESSIBLE
-32007507|Spinozalaan|ACCESSIBLE|ACCESSIBLE
-32007508|Spinozalaan|ACCESSIBLE|ACCESSIBLE
-32007509|Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
-32007510|Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
-32007612|Voorburg 't Loo|ACCESSIBLE|ACCESSIBLE
-32008101|Voorweg Laag|NOTACCESSIBLE|ACCESSIBLE
-32008102|Voorweg Laag|NOTACCESSIBLE|ACCESSIBLE
-32008103|Centrum-West|ACCESSIBLE|ACCESSIBLE
-32008106|Stadhuis|NOTACCESSIBLE|ACCESSIBLE
-32008107|Palenstein|ACCESSIBLE|ACCESSIBLE
-32008108|Palenstein|NOTACCESSIBLE|ACCESSIBLE
-32008109|Seghwaert|NOTACCESSIBLE|ACCESSIBLE
-32008110|Seghwaert|ACCESSIBLE|ACCESSIBLE
-32008111|Leidsewallen|ACCESSIBLE|ACCESSIBLE
-32008112|Leidsewallen|NOTACCESSIBLE|ACCESSIBLE
-32008113|De Leyens|NOTACCESSIBLE|ACCESSIBLE
-32008114|De Leyens|ACCESSIBLE|ACCESSIBLE
-32008115|Buytenwegh|ACCESSIBLE|ACCESSIBLE
-32008116|Buytenwegh|ACCESSIBLE|ACCESSIBLE
-32008117|Voorweg Hoog|ACCESSIBLE|ACCESSIBLE
-32008118|Voorweg Hoog|ACCESSIBLE|ACCESSIBLE
-32008119|Meerzicht|NOTACCESSIBLE|ACCESSIBLE
-32008120|Meerzicht|ACCESSIBLE|ACCESSIBLE
-32008121|Driemanspolder|ACCESSIBLE|ACCESSIBLE
-32008122|Driemanspolder|ACCESSIBLE|ACCESSIBLE
-32008123|Delftsewallen|NOTACCESSIBLE|ACCESSIBLE
-32008126|Dorp|ACCESSIBLE|ACCESSIBLE
-32008130|Oosterheem|ACCESSIBLE|ACCESSIBLE
-32008132|Javalaan|ACCESSIBLE|ACCESSIBLE
-32009589|Leidschenveen Centrum|ACCESSIBLE|ACCESSIBLE
-32009594|Forepark|ACCESSIBLE|ACCESSIBLE
-32009595|Forepark|ACCESSIBLE|ACCESSIBLE
-32009596|Leidschenveen|ACCESSIBLE|ACCESSIBLE
-32009597|Leidschenveen|ACCESSIBLE|ACCESSIBLE
-42000402|Den Hoorn, Hoornseweg|NOTACCESSIBLE|ACCESSIBLE
-42000701|Delft, Abtswoudsepark|ACCESSIBLE|ACCESSIBLE
-42000801|Delft, Abtswoude|ACCESSIBLE|ACCESSIBLE
-42000802|Delft, Abtswoude|ACCESSIBLE|ACCESSIBLE
-42001002|Delft, Arubastraat|ACCESSIBLE|ACCESSIBLE
-42001201|Delft, Bankastraat|NOTACCESSIBLE|ACCESSIBLE
-42001202|Delft, Bankastraat|ACCESSIBLE|ACCESSIBLE
-42001302|Delft, Buitenhofdreef|ACCESSIBLE|ACCESSIBLE
-42001501|Delft, Bieslandsekade|ACCESSIBLE|ACCESSIBLE
-42001502|Delft, Bieslandsekade|ACCESSIBLE|ACCESSIBLE
-42001801|Delft, Brasserskade|ACCESSIBLE|ACCESSIBLE
-42001802|Delft, Brasserskade|ACCESSIBLE|ACCESSIBLE
-42001901|Delft, Botanische Tuin|ACCESSIBLE|ACCESSIBLE
-42002001|Delft, Burgwal|ACCESSIBLE|ACCESSIBLE
-42002002|Delft, Burgwal|ACCESSIBLE|ACCESSIBLE
-42002201|Delft, Wateringseweg|ACCESSIBLE|ACCESSIBLE
-42002202|Delft, Wateringseweg|ACCESSIBLE|ACCESSIBLE
-42002301|Delft, Chopinlaan|ACCESSIBLE|ACCESSIBLE
-42002302|Delft, Chopinlaan|ACCESSIBLE|ACCESSIBLE
-42002401|Delft, Componistenpad|ACCESSIBLE|ACCESSIBLE
-42002402|Delft, Componistenpad|ACCESSIBLE|ACCESSIBLE
-42002501|Delft, Delftse Hout|ACCESSIBLE|ACCESSIBLE
-42002502|Delft, Delftse Hout|ACCESSIBLE|ACCESSIBLE
-42002601|Delft, Edelhertlaan|ACCESSIBLE|ACCESSIBLE
-42002602|Delft, Edelhertlaan|ACCESSIBLE|ACCESSIBLE
-42002802|Delft, Fuutlaan|ACCESSIBLE|ACCESSIBLE
-42003001|Delft, G.G.Z. Delfland|ACCESSIBLE|ACCESSIBLE
-42003002|Delft, G.G.Z. Delfland|ACCESSIBLE|ACCESSIBLE
-42003101|Delft, Hugo de Grootstraat|ACCESSIBLE|ACCESSIBLE
-42003102|Delft, Hugo de Grootstraat|ACCESSIBLE|ACCESSIBLE
-42003201|Delft, De Hoven Passage|ACCESSIBLE|ACCESSIBLE
-42003202|Delft, De Hoven Passage|ACCESSIBLE|ACCESSIBLE
-42003401|Delft, IKEA|ACCESSIBLE|ACCESSIBLE
-42003402|Delft, IKEA|ACCESSIBLE|ACCESSIBLE
-42003501|Delft, Jan Campertlaan|ACCESSIBLE|ACCESSIBLE
-42003502|Delft, Jan Campertlaan|ACCESSIBLE|ACCESSIBLE
-42003801|Delft, Kalfjeslaan|ACCESSIBLE|ACCESSIBLE
-42003802|Delft, Kalfjeslaan|ACCESSIBLE|ACCESSIBLE
-42004001|Delft, Latijns Amerikalaan|ACCESSIBLE|ACCESSIBLE
-42004002|Delft, Latijns Amerikalaan|ACCESSIBLE|ACCESSIBLE
-42004101|Delft, Lindenhof/Kuyperweg|ACCESSIBLE|ACCESSIBLE
-42004102|Delft, Lindenhof/Kuyperweg|ACCESSIBLE|ACCESSIBLE
-42004202|Delft, Brahmslaan|ACCESSIBLE|ACCESSIBLE
-42004301|Delft, Marlotlaan|ACCESSIBLE|ACCESSIBLE
-42004302|Delft, Marlotlaan|ACCESSIBLE|ACCESSIBLE
-42004402|Delft, Markt|ACCESSIBLE|ACCESSIBLE
-42004701|Delft, Twee Molentjeskade|ACCESSIBLE|ACCESSIBLE
-42004702|Delft, Twee Molentjeskade|ACCESSIBLE|ACCESSIBLE
-42004801|Delft, Mozartlaan|ACCESSIBLE|ACCESSIBLE
-42004802|Delft, Mozartlaan|ACCESSIBLE|ACCESSIBLE
-42004901|Delft, Menno ter Braaklaan|ACCESSIBLE|ACCESSIBLE
-42004902|Delft, Menno ter Braaklaan|ACCESSIBLE|ACCESSIBLE
-42005001|Delft, Nassauplein|ACCESSIBLE|ACCESSIBLE
-42005002|Delft, Nassauplein|ACCESSIBLE|ACCESSIBLE
-42005101|Delft, Nieuwe Langendijk|ACCESSIBLE|ACCESSIBLE
-42005102|Delft, Nieuwe Langendijk|ACCESSIBLE|ACCESSIBLE
-42005401|Delft, TNO Zuidpolder|ACCESSIBLE|ACCESSIBLE
-42005402|Delft, TNO Zuidpolder|ACCESSIBLE|ACCESSIBLE
-42005501|Delft, Parkzoom|ACCESSIBLE|ACCESSIBLE
-42005502|Delft, Parkzoom|ACCESSIBLE|ACCESSIBLE
-42005601|Delft, Poortcenter|ACCESSIBLE|ACCESSIBLE
-42005602|Delft, Poortcenter|NOTACCESSIBLE|ACCESSIBLE
-42005901|Delft, Poortlandplein|ACCESSIBLE|ACCESSIBLE
-42005902|Delft, Poortlandplein|ACCESSIBLE|ACCESSIBLE
-42006101|Delft, Revalidatiecentrum|ACCESSIBLE|ACCESSIBLE
-42006102|Delft, Revalidatiecentrum|ACCESSIBLE|ACCESSIBLE
-42006201|Delft, Reinier de Graaf Gasthuis|ACCESSIBLE|ACCESSIBLE
-42006202|Delft, Reinier de Graaf Gasthuis|ACCESSIBLE|ACCESSIBLE
-42006301|Delft, Rietzangerstraat|ACCESSIBLE|ACCESSIBLE
-42006302|Delft, Rietzangerstraat|ACCESSIBLE|ACCESSIBLE
-42006401|Delft, Schoolstraat|ACCESSIBLE|ACCESSIBLE
-42006402|Delft, Schoolstraat|ACCESSIBLE|ACCESSIBLE
-42006601|Delft, Stefanna|ACCESSIBLE|ACCESSIBLE
-42006602|Delft, Stefanna|ACCESSIBLE|ACCESSIBLE
-42006701|Delft, Stieltjesweg|NOTACCESSIBLE|ACCESSIBLE
-42006702|Delft, Stieltjesweg|ACCESSIBLE|ACCESSIBLE
-42006801|Delft, van der Lelijstraat|ACCESSIBLE|ACCESSIBLE
-42006802|Delft, van der Lelijstraat|ACCESSIBLE|ACCESSIBLE
-42006901|Delft, van der Slootsingel|ACCESSIBLE|ACCESSIBLE
-42006902|Delft, van der Slootsingel|ACCESSIBLE|ACCESSIBLE
-42007001|Delft, Voorhofdreef|NOTACCESSIBLE|ACCESSIBLE
-42007002|Delft, Voorhofdreef|ACCESSIBLE|ACCESSIBLE
-42007101|Delft, Vrijheidslaan|ACCESSIBLE|ACCESSIBLE
-42007301|Delft, Weteringlaan|ACCESSIBLE|ACCESSIBLE
-42007302|Delft, Weteringlaan|ACCESSIBLE|ACCESSIBLE
-42007401|Delft, Westlandhof|ACCESSIBLE|ACCESSIBLE
-42007402|Delft, Westlandhof|ACCESSIBLE|ACCESSIBLE
-42007701|Delft, Westlandseweg|ACCESSIBLE|ACCESSIBLE
-42007702|Delft, Westlandseweg|ACCESSIBLE|ACCESSIBLE
-42007901|Delfgauw, Delfgauwseplein|ACCESSIBLE|ACCESSIBLE
-42007902|Delfgauw, Delfgauwseplein|ACCESSIBLE|ACCESSIBLE
-42008001|Delfgauw, Gouden Rijderplein|ACCESSIBLE|ACCESSIBLE
-42008002|Delfgauw, Gouden Rijderplein|ACCESSIBLE|ACCESSIBLE
-42008301|Delfgauw, Laan van Ruyven|ACCESSIBLE|ACCESSIBLE
-42008401|Delft, Laan der Zeven Linden|ACCESSIBLE|ACCESSIBLE
-42008402|Delft, Laan der Zeven Linden|NOTACCESSIBLE|ACCESSIBLE
-42008501|Delfgauw, Overslagweg|ACCESSIBLE|ACCESSIBLE
-42008801|De Lier, Hoofdstraat|ACCESSIBLE|ACCESSIBLE
-42008802|De Lier, Hoofdstraat|ACCESSIBLE|ACCESSIBLE
-42009401|De Lier, Sportlaan|ACCESSIBLE|ACCESSIBLE
-42009402|De Lier, Sportlaan|ACCESSIBLE|ACCESSIBLE
-42009501|De Lier, Zwetburgh|ACCESSIBLE|ACCESSIBLE
-42009502|De Lier, Zwetburgh|ACCESSIBLE|ACCESSIBLE
-42010901|Den Haag, Carel Reinierszkade|ACCESSIBLE|ACCESSIBLE
-42010902|Den Haag, Carel Reinierszkade|ACCESSIBLE|ACCESSIBLE
-42011101|Den Haag, Dedemsvaartweg|ACCESSIBLE|ACCESSIBLE
-42013001|Den Haag, Haagse Markt|ACCESSIBLE|ACCESSIBLE
-42013002|Den Haag, Haagse Markt|ACCESSIBLE|ACCESSIBLE
-42014202|Den Haag, Kaapseplein|NOTACCESSIBLE|ACCESSIBLE
-42014501|Den Haag, Lanen|ACCESSIBLE|ACCESSIBLE
-42014502|Den Haag, Lanen|ACCESSIBLE|ACCESSIBLE
-42016102|Den Haag, Laan van Wateringseveld|ACCESSIBLE|ACCESSIBLE
-42017001|Den Haag, Laan van Nieuw Oost-Indie|ACCESSIBLE|ACCESSIBLE
-42017301|Den Haag, Station Ypenburg|ACCESSIBLE|ACCESSIBLE
-42017304|Den Haag, Station Ypenburg|ACCESSIBLE|ACCESSIBLE
-42017401|Den Haag, Ockenburgh|ACCESSIBLE|ACCESSIBLE
-42017402|Den Haag, Ockenburgh|ACCESSIBLE|ACCESSIBLE
-42018501|Den Haag, Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
-42018502|Den Haag, Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
-42018901|Den Haag, Schalk Burgerstraat|ACCESSIBLE|ACCESSIBLE
-42018902|Den Haag, Schalk Burgerstraat|NOTACCESSIBLE|ACCESSIBLE
-42019202|Den Haag, Steenhouwersgaarde|ACCESSIBLE|ACCESSIBLE
-42019301|Den Haag, Strijpkade|ACCESSIBLE|ACCESSIBLE
-42019302|Den Haag, Strijpkade|ACCESSIBLE|ACCESSIBLE
-42021201|'s-Gravenzande, De Brug|ACCESSIBLE|ACCESSIBLE
-42021202|'s-Gravenzande, De Brug|ACCESSIBLE|ACCESSIBLE
-42021301|'s-Gravenzande, Edisonstraat|ACCESSIBLE|ACCESSIBLE
-42021302|'s-Gravenzande, Edisonstraat|ACCESSIBLE|ACCESSIBLE
-42021601|'s-Gravenzande, Heliotroop|ACCESSIBLE|ACCESSIBLE
-42021701|'s-Gravenzande, Hoflaan|ACCESSIBLE|ACCESSIBLE
-42021904|Den Haag, Leyenburg Perron H|NOTACCESSIBLE|ACCESSIBLE
-42022001|'s-Gravenzande, Langestraat|ACCESSIBLE|ACCESSIBLE
-42022002|'s-Gravenzande, Langestraat|ACCESSIBLE|ACCESSIBLE
-42022301|'s-Gravenzande, Naaldwijkseweg|ACCESSIBLE|ACCESSIBLE
-42022302|'s-Gravenzande, Naaldwijkseweg|ACCESSIBLE|ACCESSIBLE
-42022501|'s-Gravenzande, Strandweg|ACCESSIBLE|ACCESSIBLE
-42023301|'s-Gravenzande, Zandeveltplein|ACCESSIBLE|ACCESSIBLE
-42023302|'s-Gravenzande, Zandeveltplein|ACCESSIBLE|ACCESSIBLE
-42024101|Honselersdijk, Nederhof|ACCESSIBLE|ACCESSIBLE
-42024102|Honselersdijk, Nederhof|ACCESSIBLE|ACCESSIBLE
-42024202|Honselersdijk, Nieuweweg|ACCESSIBLE|ACCESSIBLE
-42024601|Honselersdijk, Strijplaan|ACCESSIBLE|ACCESSIBLE
-42026501|Kwintsheul, Raaphorstbrug|ACCESSIBLE|ACCESSIBLE
-42026502|Kwintsheul, Raaphorstbrug|ACCESSIBLE|ACCESSIBLE
-42026601|Kwintsheul, RK Kerk|ACCESSIBLE|ACCESSIBLE
-42026602|Kwintsheul, RK Kerk|ACCESSIBLE|ACCESSIBLE
-42026703|Leidschendam, St. Antoniushove|ACCESSIBLE|ACCESSIBLE
-42026704|Leidschendam, MCH Antoniushove|ACCESSIBLE|ACCESSIBLE
-42027101|Leidschendam, Dillenburgsingel|ACCESSIBLE|ACCESSIBLE
-42027102|Leidschendam, Dillenburgsingel|ACCESSIBLE|ACCESSIBLE
-42027501|Leidschendam, Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
-42027503|Leidschendam, Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
-42027601|Leidschendam, Leidsenhage/Banninglaan|ACCESSIBLE|ACCESSIBLE
-42027602|Leidschendam, Leidsenhage/Banninglaan|ACCESSIBLE|ACCESSIBLE
-42027801|Leidschendam, Vlindertuin|ACCESSIBLE|ACCESSIBLE
-42027802|Leidschendam, Vlindertuin|ACCESSIBLE|ACCESSIBLE
-42028501|Leidschendam, Rozenrust|ACCESSIBLE|ACCESSIBLE
-42028502|Leidschendam, Rozenrust|ACCESSIBLE|ACCESSIBLE
-42028701|Voorburg, Sijtwendetunnel|ACCESSIBLE|ACCESSIBLE
-42029001|Leidschendam, Weikamp|ACCESSIBLE|ACCESSIBLE
-42029002|Leidschendam, Weikamp|ACCESSIBLE|ACCESSIBLE
-42034001|Maasland, Commandeurskade|ACCESSIBLE|ACCESSIBLE
-42034002|Maasland, Commandeurskade|NOTACCESSIBLE|ACCESSIBLE
-42034101|Maasland, Doelstraat|ACCESSIBLE|ACCESSIBLE
-42034102|Maasland, Doelstraat|ACCESSIBLE|ACCESSIBLE
-42034401|Maasland, Kluisweer|ACCESSIBLE|ACCESSIBLE
-42034402|Maasland, Kluisweer|ACCESSIBLE|ACCESSIBLE
-42034901|Maasland, Nieuw Huis Ter Lucht|ACCESSIBLE|ACCESSIBLE
-42034902|Maasland, Nieuw Huis Ter Lucht|ACCESSIBLE|ACCESSIBLE
-42035002|Maasland, Viaduct|ACCESSIBLE|ACCESSIBLE
-42035003|Maasland, Viaduct|ACCESSIBLE|ACCESSIBLE
-42035101|Monster, Acaciastraat|ACCESSIBLE|ACCESSIBLE
-42035102|Monster, Acaciastraat|ACCESSIBLE|ACCESSIBLE
-42035201|Monster, Duinstraat|ACCESSIBLE|ACCESSIBLE
-42035202|Monster, Duinstraat|ACCESSIBLE|ACCESSIBLE
-42035301|Monster, Emmaplein|ACCESSIBLE|ACCESSIBLE
-42035302|Monster, Emmaplein|ACCESSIBLE|ACCESSIBLE
-42035601|Monster, Plaats Langeveld|ACCESSIBLE|ACCESSIBLE
-42035602|Monster, Plaats Langeveld|ACCESSIBLE|ACCESSIBLE
-42035701|Monster, Schelppad|ACCESSIBLE|ACCESSIBLE
-42035702|Monster, Schelppad|ACCESSIBLE|ACCESSIBLE
-42035801|Monster, De Tol|ACCESSIBLE|ACCESSIBLE
-42035901|Monster, Taets van Amerongenstraat|ACCESSIBLE|ACCESSIBLE
-42035902|Monster, Taets van Amerongenstraat|ACCESSIBLE|ACCESSIBLE
-42036002|Monster, Verdilaan|ACCESSIBLE|ACCESSIBLE
-42036201|Monster, Watergat|ACCESSIBLE|ACCESSIBLE
-42036202|Monster, Watergat|ACCESSIBLE|ACCESSIBLE
-42036302|Monster, Stichting Westerhonk|ACCESSIBLE|ACCESSIBLE
-42036701|Maasdijk, Verkadestraat|ACCESSIBLE|ACCESSIBLE
-42036702|Maasdijk, Verkadestraat|ACCESSIBLE|ACCESSIBLE
-42039001|Nootdorp, Begraafplaats St. Janshof|ACCESSIBLE|ACCESSIBLE
-42039002|Nootdorp, Begraafplaats St. Janshof|ACCESSIBLE|ACCESSIBLE
-42039201|Nootdorp, Duizendschoon|ACCESSIBLE|ACCESSIBLE
-42039202|Nootdorp, Duizendschoon|ACCESSIBLE|ACCESSIBLE
-42039501|Nootdorp, Larixlaan|ACCESSIBLE|ACCESSIBLE
-42039502|Nootdorp, Larixlaan|ACCESSIBLE|ACCESSIBLE
-42039801|Nootdorp, Rotonde Randstadrail|ACCESSIBLE|ACCESSIBLE
-42040101|Naaldwijk, Ambachtstraat|ACCESSIBLE|ACCESSIBLE
-42040102|Naaldwijk, Ambachtstraat|ACCESSIBLE|ACCESSIBLE
-42040401|Naaldwijk, Hoge Woerd|ACCESSIBLE|ACCESSIBLE
-42040501|Naaldwijk, Industriestraat|ACCESSIBLE|ACCESSIBLE
-42040502|Naaldwijk, Industriestraat|ACCESSIBLE|ACCESSIBLE
-42040601|Naaldwijk, Linde|ACCESSIBLE|ACCESSIBLE
-42040602|Naaldwijk, Linde|ACCESSIBLE|ACCESSIBLE
-42040701|Naaldwijk, Lage Woerd|ACCESSIBLE|ACCESSIBLE
-42040702|Naaldwijk, Lage Woerd|ACCESSIBLE|ACCESSIBLE
-42040901|Naaldwijk, Perzikenstraat/Rozenhof|ACCESSIBLE|ACCESSIBLE
-42040902|Naaldwijk, Perzikenstraat/Rozenhof|ACCESSIBLE|ACCESSIBLE
-42041001|Naaldwijk, Pijle Tuinen|ACCESSIBLE|ACCESSIBLE
-42041002|Naaldwijk, Pijle Tuinen|ACCESSIBLE|ACCESSIBLE
-42041301|Naaldwijk, Zuidweg|ACCESSIBLE|ACCESSIBLE
-42041302|Naaldwijk, Zuidweg|ACCESSIBLE|ACCESSIBLE
-42042001|Pijnacker, Ade|ACCESSIBLE|ACCESSIBLE
-42042002|Pijnacker, Ade|ACCESSIBLE|ACCESSIBLE
-42044001|Pijnacker, Rijskade|ACCESSIBLE|ACCESSIBLE
-42044002|Pijnacker, Rijskade|ACCESSIBLE|ACCESSIBLE
-42044401|Rijswijk, In de Bogaard|ACCESSIBLE|ACCESSIBLE
-42044402|Rijswijk, In de Bogaard|ACCESSIBLE|ACCESSIBLE
-42044701|Rijswijk, Darling Markt|ACCESSIBLE|ACCESSIBLE
-42044702|Rijswijk, Darling Markt|ACCESSIBLE|ACCESSIBLE
-42045204|Rijswijk, Dr. H.J. van Mooklaan|ACCESSIBLE|ACCESSIBLE
-42045406|Rijswijk, Station Rijswijk|NOTACCESSIBLE|ACCESSIBLE
-42045407|Rijswijk, Station Rijswijk|NOTACCESSIBLE|ACCESSIBLE
-42046401|Rijswijk, TNO / Lange Kleiweg|ACCESSIBLE|ACCESSIBLE
-42046402|Rijswijk, TNO / Lange Kleiweg|ACCESSIBLE|ACCESSIBLE
-42046701|Rijswijk, van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
-42046702|Rijswijk, van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
-42050101|Voorburg, Sijtwendetunnel|ACCESSIBLE|ACCESSIBLE
-42050301|Voorburg, Hoeckvlietstraat|ACCESSIBLE|ACCESSIBLE
-42050302|Voorburg, Hoeckvlietstraat|ACCESSIBLE|ACCESSIBLE
-42051001|Voorburg, Station Leidschendam/Voorburg|ACCESSIBLE|ACCESSIBLE
-42051501|Voorburg, Rembrandtlaan|ACCESSIBLE|ACCESSIBLE
-42051502|Voorburg, Rembrandtlaan|ACCESSIBLE|ACCESSIBLE
-42052001|Voorburg, van Halewijnlaan|ACCESSIBLE|ACCESSIBLE
-42052002|Voorburg, van Halewijnlaan|ACCESSIBLE|ACCESSIBLE
-42052101|Voorburg, van Heurnstraat|ACCESSIBLE|ACCESSIBLE
-42052102|Voorburg, van Heurnstraat|ACCESSIBLE|ACCESSIBLE
-42055401|Wassenaar, Ammonslaantje|ACCESSIBLE|ACCESSIBLE
-42055402|Wassenaar, Ammonslaantje|ACCESSIBLE|ACCESSIBLE
-42055501|Wassenaar, Beukenhorstlaan|ACCESSIBLE|ACCESSIBLE
-42055502|Wassenaar, Beukenhorstlaan|ACCESSIBLE|ACCESSIBLE
-42055601|Wassenaar, Burchtlaan|ACCESSIBLE|ACCESSIBLE
-42055801|Wassenaar, van Duivenvoordelaan|ACCESSIBLE|ACCESSIBLE
-42055802|Wassenaar, van Duivenvoordelaan|ACCESSIBLE|ACCESSIBLE
-42056001|Wassenaar, Jonkerlaan|ACCESSIBLE|ACCESSIBLE
-42056002|Wassenaar, Jonkerlaan|ACCESSIBLE|ACCESSIBLE
-42056401|Wassenaar, Maaldrift|ACCESSIBLE|ACCESSIBLE
-42056402|Wassenaar, Maaldrift|ACCESSIBLE|ACCESSIBLE
-42056501|Wassenaar, Nachtegaallaan|ACCESSIBLE|ACCESSIBLE
-42056502|Wassenaar, Nachtegaallaan|ACCESSIBLE|ACCESSIBLE
-42056901|Wassenaar, Park Duinrell|ACCESSIBLE|ACCESSIBLE
-42056902|Wassenaar, Park Duinrell|ACCESSIBLE|ACCESSIBLE
-42057101|Wassenaar, Rozenplein|ACCESSIBLE|ACCESSIBLE
-42057102|Wassenaar, Rozenplein|ACCESSIBLE|ACCESSIBLE
-42057301|Wassenaar, Stadhoudersplein|ACCESSIBLE|ACCESSIBLE
-42057302|Wassenaar, Stadhoudersplein|ACCESSIBLE|ACCESSIBLE
-42057501|Wassenaar, Stoeplaan|ACCESSIBLE|ACCESSIBLE
-42057502|Wassenaar, Stoeplaan|ACCESSIBLE|ACCESSIBLE
-42057601|Wassenaar, Strandwal|ACCESSIBLE|ACCESSIBLE
-42057602|Wassenaar, Strandwal|ACCESSIBLE|ACCESSIBLE
-42057701|Wassenaar, Ter Weerlaan|ACCESSIBLE|ACCESSIBLE
-42057702|Wassenaar, Ter Weerlaan|ACCESSIBLE|ACCESSIBLE
-42057901|Wassenaar, Weyermanstraat|ACCESSIBLE|ACCESSIBLE
-42057902|Wassenaar, Weyermanstraat|ACCESSIBLE|ACCESSIBLE
-42058001|Wassenaar, Wittenburgerweg|ACCESSIBLE|ACCESSIBLE
-42058101|Wassenaar, Wildrust|ACCESSIBLE|ACCESSIBLE
-42058102|Wassenaar, Wildrust|ACCESSIBLE|ACCESSIBLE
-42058201|Wateringen, De Ark|ACCESSIBLE|ACCESSIBLE
-42058202|Wateringen, De Ark|ACCESSIBLE|ACCESSIBLE
-42058301|Wateringen, Gemeentehuis / Plein|ACCESSIBLE|ACCESSIBLE
-42058401|Wateringen, Harry Hoekstraat|ACCESSIBLE|ACCESSIBLE
-42058402|Wateringen, Harry Hoekstraat|ACCESSIBLE|ACCESSIBLE
-42058501|Wateringen, Plein|ACCESSIBLE|ACCESSIBLE
-42058503|Wateringen, Plein|ACCESSIBLE|ACCESSIBLE
-42058601|Zoetermeer, Acaciazoom|ACCESSIBLE|ACCESSIBLE
-42058602|Zoetermeer, Acaciazoom|ACCESSIBLE|ACCESSIBLE
-42058701|Zoetermeer, Alkmenehof|ACCESSIBLE|ACCESSIBLE
-42059101|Zoetermeer, Berglaan|ACCESSIBLE|ACCESSIBLE
-42059102|Zoetermeer, Berglaan|ACCESSIBLE|ACCESSIBLE
-42059201|Zoetermeer, Beryl|ACCESSIBLE|ACCESSIBLE
-42059202|Zoetermeer, Beryl|ACCESSIBLE|ACCESSIBLE
-42059501|Zoetermeer, Brinkmanplan|ACCESSIBLE|ACCESSIBLE
-42059702|Zoetermeer, Centrum West (Perron B)|ACCESSIBLE|ACCESSIBLE
-42059703|Zoetermeer, Centrum West (Perron F)|ACCESSIBLE|ACCESSIBLE
-42059705|Zoetermeer, Centrum West (Perron H)|ACCESSIBLE|ACCESSIBLE
-42059801|Zoetermeer, De Louvrierruimte|ACCESSIBLE|ACCESSIBLE
-42060101|Zoetermeer, Driesprong|ACCESSIBLE|ACCESSIBLE
-42060102|Zoetermeer, Driesprong|ACCESSIBLE|ACCESSIBLE
-42060301|Zoetermeer, Dijkmanschans|ACCESSIBLE|ACCESSIBLE
-42060601|Zoetermeer, Electrablauw|ACCESSIBLE|ACCESSIBLE
-42060602|Zoetermeer, Electrablauw|ACCESSIBLE|ACCESSIBLE
-42060701|Zoetermeer, Elzehout|ACCESSIBLE|ACCESSIBLE
-42060702|Zoetermeer, Elzehout|ACCESSIBLE|ACCESSIBLE
-42061101|Zoetermeer, Florazoom|ACCESSIBLE|ACCESSIBLE
-42061102|Zoetermeer, Florazoom|ACCESSIBLE|ACCESSIBLE
-42061202|Zoetermeer, Fonteinbos|ACCESSIBLE|ACCESSIBLE
-42061601|Zoetermeer, Hoflaan|ACCESSIBLE|ACCESSIBLE
-42061702|Zoetermeer, Houtsingel|ACCESSIBLE|ACCESSIBLE
-42061901|Zoetermeer, Kahnlijn|ACCESSIBLE|ACCESSIBLE
-42062001|Zoetermeer, Kerkenbos|ACCESSIBLE|ACCESSIBLE
-42062002|Zoetermeer, Kerkenbos|ACCESSIBLE|ACCESSIBLE
-42062101|Zoetermeer, Kleurlaan|ACCESSIBLE|ACCESSIBLE
-42062501|Zoetermeer, Lommerbaan|ACCESSIBLE|ACCESSIBLE
-42062902|Zoetermeer, Meerzichtlaan|ACCESSIBLE|ACCESSIBLE
-42063101|Zoetermeer, Nathaliegang|ACCESSIBLE|ACCESSIBLE
-42063102|Zoetermeer, Nathaliegang|ACCESSIBLE|ACCESSIBLE
-42063301|Zoetermeer, Noordhove/Winkelcentrum|ACCESSIBLE|ACCESSIBLE
-42063401|Zoetermeer, Station Oost|ACCESSIBLE|ACCESSIBLE
-42063601|Zoetermeer, Ogeahout|NOTACCESSIBLE|ACCESSIBLE
-42063602|Zoetermeer, Ogeahout|ACCESSIBLE|ACCESSIBLE
-42063801|Zoetermeer, Pelschans|NOTACCESSIBLE|ACCESSIBLE
-42064101|Zoetermeer, Redelaan|ACCESSIBLE|ACCESSIBLE
-42064302|Zoetermeer, Robijn|ACCESSIBLE|ACCESSIBLE
-42064601|Zoetermeer, Salomeschouw|ACCESSIBLE|ACCESSIBLE
-42064602|Zoetermeer, Salomeschouw|ACCESSIBLE|ACCESSIBLE
-42064801|Zoetermeer, Sportctr. De Driesprong|ACCESSIBLE|ACCESSIBLE
-42064802|Zoetermeer, Sportctr. De Driesprong|ACCESSIBLE|ACCESSIBLE
-42064902|Zoetermeer, Sportcentrum De Veur|ACCESSIBLE|ACCESSIBLE
-42065001|Zoetermeer, Stadhoudersring|ACCESSIBLE|ACCESSIBLE
-42065002|Zoetermeer, Stadhoudersring|ACCESSIBLE|ACCESSIBLE
-42065101|Zoetermeer, Station Driemanspolder|ACCESSIBLE|ACCESSIBLE
-42065102|Zoetermeer, Station Driemanspolder|ACCESSIBLE|ACCESSIBLE
-42065201|Zoetermeer, Station Meerzicht|ACCESSIBLE|ACCESSIBLE
-42065202|Zoetermeer, Station Meerzicht|ACCESSIBLE|ACCESSIBLE
-42065401|Zoetermeer, Surfpad|ACCESSIBLE|ACCESSIBLE
-42065402|Zoetermeer, Surfpad|ACCESSIBLE|ACCESSIBLE
-42065601|Zoetermeer, Viaduct Afrikaweg|ACCESSIBLE|ACCESSIBLE
-42065602|Zoetermeer, Viaduct Afrikaweg|ACCESSIBLE|ACCESSIBLE
-42066101|Zoetermeer, Winkelcentrum De Vlieger|ACCESSIBLE|ACCESSIBLE
-42066102|Zoetermeer, Winkelcentrum De Vlieger|ACCESSIBLE|ACCESSIBLE
-42066301|Zoetermeer, Maria Montessorilaan|ACCESSIBLE|ACCESSIBLE
-42066302|Zoetermeer, Maria Montessorilaan|ACCESSIBLE|ACCESSIBLE
-42066401|Zoetermeer, Winkelcentrum Rokkeveen|ACCESSIBLE|ACCESSIBLE
-42066402|Zoetermeer, Winkelcentrum Rokkeveen|ACCESSIBLE|ACCESSIBLE
-42066501|Zoetermeer, Zalkerbos|ACCESSIBLE|ACCESSIBLE
-42066502|Zoetermeer, Zalkerbos|ACCESSIBLE|ACCESSIBLE
-42066701|Zoetermeer, Zwaardslootseweg|ACCESSIBLE|ACCESSIBLE
-42066702|Zoetermeer, Zwaardslootseweg|ACCESSIBLE|ACCESSIBLE
-42066801|Zoetermeer, Planbaan|ACCESSIBLE|ACCESSIBLE
-42066901|Zoetermeer, Groen-blauwlaan|ACCESSIBLE|ACCESSIBLE
-42067002|Delfgauw, Hoefsmidstraat|ACCESSIBLE|ACCESSIBLE
-42067101|Delfgauw, Achtmanstraat|ACCESSIBLE|ACCESSIBLE
-42067102|Delfgauw, Achtmanstraat|ACCESSIBLE|ACCESSIBLE
-42067201|Delfgauw, Laan van Ruyven|ACCESSIBLE|ACCESSIBLE
-42068301|Nootdorp, De Poort|ACCESSIBLE|ACCESSIBLE
-42069502|Delft, Olof Palmestraat|ACCESSIBLE|ACCESSIBLE
-42070601|Wateringen, Vlasser|NOTACCESSIBLE|ACCESSIBLE
-42070602|Wateringen, Vlasser|ACCESSIBLE|ACCESSIBLE
-42070701|Wateringen, Guldeland|ACCESSIBLE|ACCESSIBLE
-42070702|Wateringen, Guldeland|ACCESSIBLE|ACCESSIBLE
-42070801|Wateringen, Willem 3 straat|ACCESSIBLE|ACCESSIBLE
-42070802|Wateringen, Willem 3 straat|ACCESSIBLE|ACCESSIBLE
-42071301|Den Haag, Melis Stokelaan|NOTACCESSIBLE|ACCESSIBLE
-42071302|Den Haag, Melis Stokelaan|ACCESSIBLE|ACCESSIBLE
-42071401|Den Haag, Dalerveenstraat|ACCESSIBLE|ACCESSIBLE
-42071402|Den Haag, Dalerveenstraat|ACCESSIBLE|ACCESSIBLE
-42071501|Den Haag, Gramsbergenlaan|ACCESSIBLE|ACCESSIBLE
-42071502|Den Haag, Gramsbergenlaan|ACCESSIBLE|ACCESSIBLE
-42071901|Delft, Pootstraat|ACCESSIBLE|ACCESSIBLE
-42072001|Delft, Frank van Borselenstraat|ACCESSIBLE|ACCESSIBLE
-42072601|Delft, Station Zuid|ACCESSIBLE|ACCESSIBLE
-42072602|Delft, Station Zuid|ACCESSIBLE|ACCESSIBLE
-49000040|Lelystad, Ziekenhuis|ACCESSIBLE|ACCESSIBLE
-49001650|Lelystad, Agora|ACCESSIBLE|ACCESSIBLE
-49001700|Lelystad, Agora|ACCESSIBLE|ACCESSIBLE
-49003250|Lelystad, Ziekenhuis|ACCESSIBLE|ACCESSIBLE
-49003300|Lelystad, De Hoven|ACCESSIBLE|ACCESSIBLE
-49003320|Lelystad, De Hoven|ACCESSIBLE|ACCESSIBLE
-49003370|Lelystad, 't Laar|ACCESSIBLE|ACCESSIBLE
-49004500|Lelystad, De Rietlanden|ACCESSIBLE|ACCESSIBLE
-49005550|Lelystad, Karveelbrug|ACCESSIBLE|ACCESSIBLE
-49005600|Lelystad, Karveelbrug|ACCESSIBLE|ACCESSIBLE
-49005650|Lelystad, Kempenaarbrug|ACCESSIBLE|ACCESSIBLE
-49005700|Lelystad, Kempenaarbrug|ACCESSIBLE|ACCESSIBLE
-49005850|Lelystad, Batavia Stad|ACCESSIBLE|ACCESSIBLE
-49005920|Lelystad, Batavia Stad|ACCESSIBLE|ACCESSIBLE
-49005921|Lelystad, Batavia Stad|ACCESSIBLE|ACCESSIBLE
-49007000|Lelystad, Houtribsluis|ACCESSIBLE|ACCESSIBLE
-49007010|Lelystad, Houtribsluis|ACCESSIBLE|ACCESSIBLE
-49120010|Lelystad, Bataviastad|ACCESSIBLE|ACCESSIBLE
-53491302|Maasland, Viaduct|ACCESSIBLE|ACCESSIBLE
-54000720|Dr. Kuyperstraat|ACCESSIBLE|ACCESSIBLE
-54240130|Wassenaar, Rijksdorp|ACCESSIBLE|ACCESSIBLE
-54240140|Wassenaar, Bronckhorstlaan|ACCESSIBLE|ACCESSIBLE
-54240390|Wassenaar, Lange Kerkdam|NOTACCESSIBLE|ACCESSIBLE
-54240400|Wassenaar, Lange Kerkdam|ACCESSIBLE|ACCESSIBLE
-54240440|Wassenaar, Johan de Wittstraat|ACCESSIBLE|ACCESSIBLE
-54241020|Wassenaar, Rijksdorp|ACCESSIBLE|ACCESSIBLE
-54360030|Wassenaar, Bronckhorstlaan|ACCESSIBLE|ACCESSIBLE
-54360070|Katwijk a/d Rijn, Hotel Wassenaar|ACCESSIBLE|ACCESSIBLE
-54360100|Wassenaar, Hotel Wassenaar|ACCESSIBLE|ACCESSIBLE
-54410066|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
-54410067|Zoetermeer, Centrum West (G)|ACCESSIBLE|ACCESSIBLE
-54410510|Zoetermeer, Wengehout|ACCESSIBLE|ACCESSIBLE
-54410520|Zoetermeer, Wengehout|ACCESSIBLE|ACCESSIBLE
-54410730|Zoetermeer, Pruimengaarde|ACCESSIBLE|ACCESSIBLE
-54410740|Zoetermeer, Pruimengaarde|ACCESSIBLE|ACCESSIBLE
-54411040|Zoetermeer, Ambachtsherenlaan|ACCESSIBLE|ACCESSIBLE
-54414032|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
-54414165|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
-54414206|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
-6013|Kruidenlaan|ACCESSIBLE|ACCESSIBLE
-6014|Kruidenlaan|ACCESSIBLE|ACCESSIBLE
-90000007|Lelystad, Agora|ACCESSIBLE|ACCESSIBLE
-90000009|Lelystad, 't Laar|ACCESSIBLE|ACCESSIBLE
-90000011|Lelystad, De Rietlanden|ACCESSIBLE|ACCESSIBLE
-90000012|Lelystad, Bataviahaven|ACCESSIBLE|ACCESSIBLE
-32000101|Oude Waalsdorperweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000102|Oude Waalsdorperweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000202|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
-32000205|Kurhausweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000206|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
-32000207|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
-32000208|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
-32000209|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
-32000217|Harstenhoekplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000219|Stevinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000220|Stevinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000221|Gentsestraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000311|Plesmanweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000401|Bronovo Ziekenhuis|NOTACCESSIBLE|NOTACCESSIBLE
-32000412|Oostduinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000413|Van der Woertstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000414|Van der Woertstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000415|Ruychrocklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000416|Ruychrocklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000428|Van Hoytemastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000435|Dr. Kuyperstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000437|Weissenbruchstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000438|Willem Witsenplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000439|Willem Witsenplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000503|Bankaplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000504|Bankaplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000507|Vredespaleis|NOTACCESSIBLE|NOTACCESSIBLE
-32000508|Vredespaleis|NOTACCESSIBLE|NOTACCESSIBLE
-32000509|Vredespaleis|NOTACCESSIBLE|NOTACCESSIBLE
-32000510|Nassauplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000511|Nassauplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000515|Alexanderplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000516|Alexanderplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000601|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
-32000603|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
-32000605|Kerkhoflaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000608|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
-32000702|Badhuiskade|NOTACCESSIBLE|NOTACCESSIBLE
-32000703|Badhuiskade|NOTACCESSIBLE|NOTACCESSIBLE
-32000706|Schev.slag/Beelden aan Zee|NOTACCESSIBLE|NOTACCESSIBLE
-32000707|Schev.slag/Beelden aan Zee|NOTACCESSIBLE|NOTACCESSIBLE
-32000714|Keizerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000715|Keizerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000716|Duinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000718|Duinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000719|Duinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000720|Prins Willemstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000721|Prins Willemstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000724|Haringkade|NOTACCESSIBLE|NOTACCESSIBLE
-32000725|Haringkade|NOTACCESSIBLE|NOTACCESSIBLE
-32000726|Nieuwe Parklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000727|Nieuwe Parklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000730|Douzastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000731|Douzastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000732|Statenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000733|Statenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000734|Rusthoekstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000737|Statenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000802|Markenseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000803|Tesselseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000804|Tesselseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000807|Nieboerweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000808|Nieboerweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000809|Markenseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000904|Scheveningseweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000905|Scheveningseweg|NOTACCESSIBLE|NOTACCESSIBLE
-32000917|Willem de Zwijgerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000918|Willem de Zwijgerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32000919|World Forum|NOTACCESSIBLE|NOTACCESSIBLE
-32000920|World Forum|NOTACCESSIBLE|NOTACCESSIBLE
-32000927|Statenplein|NOTACCESSIBLE|NOTACCESSIBLE
-32000930|Aert van der Goesstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32000932|Van Boetzelaerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001110|Conradkade|NOTACCESSIBLE|NOTACCESSIBLE
-32001111|Conradkade|NOTACCESSIBLE|NOTACCESSIBLE
-32001114|Groot Hertoginnelaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001115|Groot Hertoginnelaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001117|Banstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001118|Banstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001119|Conradkade|NOTACCESSIBLE|NOTACCESSIBLE
-32001123|Laan van Meerdervoort|NOTACCESSIBLE|NOTACCESSIBLE
-32001124|Laan van Meerdervoort|NOTACCESSIBLE|NOTACCESSIBLE
-32001204|Nieboerweg|NOTACCESSIBLE|NOTACCESSIBLE
-32001303|Kruisbeklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001305|Oude Buizerdlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001306|Oude Buizerdlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001419|De Savornin Lohmanplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001420|De Savornin Lohmanplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001426|Teunisbloemplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001427|de Savornin Lohmanplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001502|Kijkduin|NOTACCESSIBLE|NOTACCESSIBLE
-32001504|Kijkduin Strand|NOTACCESSIBLE|NOTACCESSIBLE
-32001506|Kijkduin Strand|NOTACCESSIBLE|NOTACCESSIBLE
-32001715|Houtwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001716|Houtwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001719|Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001721|Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001805|Pisuissestraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001806|Pisuissestraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001808|Groen van Prinstererlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32001818|Arnold Spoelplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001822|Louis Armstrongplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001823|Louis Armstrongplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001824|Buitentuinen|NOTACCESSIBLE|NOTACCESSIBLE
-32001825|Buitentuinen|NOTACCESSIBLE|NOTACCESSIBLE
-32001828|Binnentuinen|NOTACCESSIBLE|NOTACCESSIBLE
-32001829|Binnentuinen|NOTACCESSIBLE|NOTACCESSIBLE
-32001873|Westduin|NOTACCESSIBLE|NOTACCESSIBLE
-32001907|Colijnplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001908|Colijnplein|NOTACCESSIBLE|NOTACCESSIBLE
-32001911|Appelstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001912|Appelstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001916|Perenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001918|Laan van Eik en Duinen|NOTACCESSIBLE|NOTACCESSIBLE
-32001923|Okkernootstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32001924|Okkernootstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002002|Goudenregenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002008|Fahrenheitstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002012|Valkenbosplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002013|Valkenbosplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002017|Copernicusplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002018|Copernicusplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002019|Kamperfoeliestraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002020|Kamperfoeliestraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002021|Weimarstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002022|Weimarstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002301|Javastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002306|Javastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002307|Mauritskade|NOTACCESSIBLE|NOTACCESSIBLE
-32002308|Mauritskade|NOTACCESSIBLE|NOTACCESSIBLE
-32002309|Dr. Kuyperstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002310|Dr. Kuyperstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002313|Mauritskade|NOTACCESSIBLE|NOTACCESSIBLE
-32002403|Malieveld|NOTACCESSIBLE|NOTACCESSIBLE
-32002505|Barnsteenhorst|NOTACCESSIBLE|NOTACCESSIBLE
-32002507|Saffierhorst|NOTACCESSIBLE|NOTACCESSIBLE
-32002519|Het Kleine Loo|NOTACCESSIBLE|NOTACCESSIBLE
-32002520|Het Kleine Loo|NOTACCESSIBLE|NOTACCESSIBLE
-32002521|Margarethaland|NOTACCESSIBLE|NOTACCESSIBLE
-32002522|Margarethaland|NOTACCESSIBLE|NOTACCESSIBLE
-32002526|Station Mariahoeve|NOTACCESSIBLE|NOTACCESSIBLE
-32002631|Prins Clauslaan|NOTACCESSIBLE|NOTACCESSIBLE
-32002632|Prins Clauslaan|NOTACCESSIBLE|NOTACCESSIBLE
-32002633|Koningin Marialaan|NOTACCESSIBLE|NOTACCESSIBLE
-32002634|Koningin Marialaan|NOTACCESSIBLE|NOTACCESSIBLE
-32002635|Laan van Nieuw Oost Indië|NOTACCESSIBLE|NOTACCESSIBLE
-32002636|Laan van Nieuw Oost Indië|NOTACCESSIBLE|NOTACCESSIBLE
-32002639|Spaarwaterstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002640|Spaarwaterstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002641|De Eerensplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002642|De Eerensplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002645|Ternoot|NOTACCESSIBLE|NOTACCESSIBLE
-32002646|Ternoot|NOTACCESSIBLE|NOTACCESSIBLE
-32002655|Stuyvesantstraat|ACCESSIBLE|NOTACCESSIBLE
-32002656|Stuyvesantstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32002658|Station Laan van NOI|ACCESSIBLE|NOTACCESSIBLE
-32002659|Station Laan van NOI|ACCESSIBLE|NOTACCESSIBLE
-32002707|Rijswijkseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002708|Rijswijkseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002711|Weteringplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002712|Weteringplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002715|Rijswijkseplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002719|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32002720|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32002721|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32002730|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32002731|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32002803|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
-32002804|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
-32002821|Brouwersgracht|NOTACCESSIBLE|NOTACCESSIBLE
-32002828|Den Haag, Grote Markt|NOTACCESSIBLE|NOTACCESSIBLE
-32002845|Amsterdamse Veerkade|NOTACCESSIBLE|NOTACCESSIBLE
-32002846|Amsterdamse Veerkade|NOTACCESSIBLE|NOTACCESSIBLE
-32002857|Nieuwe Haven|NOTACCESSIBLE|NOTACCESSIBLE
-32002864|Buitenhof|NOTACCESSIBLE|NOTACCESSIBLE
-32002865|Buitenhof|NOTACCESSIBLE|NOTACCESSIBLE
-32002873|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
-32002874|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
-32002909|Vaillantplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002913|Hobbemaplein|NOTACCESSIBLE|NOTACCESSIBLE
-32002914|Hobbemaplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003001|Loosduinseweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003009|Schalk Burgerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003010|Schalk Burgerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003113|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003123|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003125|Barneveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003126|Barneveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003130|Dierenselaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003201|Volendamlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003202|Volendamlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003209|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003210|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003218|Leyenburg|NOTACCESSIBLE|NOTACCESSIBLE
-32003219|Zuiderpark|NOTACCESSIBLE|NOTACCESSIBLE
-32003220|Zuiderpark|NOTACCESSIBLE|NOTACCESSIBLE
-32003223|Monnickendamplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003224|Monnickendamplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003302|Drapeniersgaarde|NOTACCESSIBLE|NOTACCESSIBLE
-32003303|Drapeniersgaarde|NOTACCESSIBLE|NOTACCESSIBLE
-32003306|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003318|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003319|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003320|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003321|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003322|Hertenrade|NOTACCESSIBLE|NOTACCESSIBLE
-32003330|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003331|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003342|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003343|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003358|Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003359|Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003363|Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003364|Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003405|Meppelweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003406|Meppelweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003407|Almeloplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003408|Almeloplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003413|Leyweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003414|Leyweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003424|Loevesteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003425|Loevesteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003438|Fluitenbergstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003439|Fluitenbergstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003442|Steenwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003443|Steenwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003601|Loevesteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003612|Cannenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003613|Cannenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003624|Moerweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003625|Moerweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003626|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
-32003627|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
-32003628|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
-32003629|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
-32003709|Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
-32003801|Goudriaankade|NOTACCESSIBLE|NOTACCESSIBLE
-32003802|Goudriaankade|NOTACCESSIBLE|NOTACCESSIBLE
-32003803|Calandplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003804|Calandplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003807|Neherkade|NOTACCESSIBLE|NOTACCESSIBLE
-32003808|Neherkade|NOTACCESSIBLE|NOTACCESSIBLE
-32003819|Jonckbloetplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003820|Jonckbloetplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003829|Alberdingk Thijmstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003830|Alberdingk Thijmstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003832|Ledeganckplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003833|Jan van Beersstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003834|Jan van Beersstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003843|Stieltjesstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003844|Stieltjesstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003845|Jonckbloetplein|NOTACCESSIBLE|NOTACCESSIBLE
-32003846|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32003847|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
-32003857|Megastores|NOTACCESSIBLE|NOTACCESSIBLE
-32003858|Megastores|NOTACCESSIBLE|NOTACCESSIBLE
-32003859|Megastores hoofdingang|NOTACCESSIBLE|NOTACCESSIBLE
-32003903|Poolsterstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003904|Poolsterstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003905|Wegastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003906|Wegastraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003907|Zonweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003908|Zonweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003909|Melkwegstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003910|Melkwegstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003911|Saturnusstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32003917|Regulusweg|NOTACCESSIBLE|NOTACCESSIBLE
-32003919|Saturnusstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32004009|Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
-32004010|Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
-32004011|Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
-32004012|Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
-32005101|Herenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32005105|Bilderdijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-32005106|Geestbrug|NOTACCESSIBLE|NOTACCESSIBLE
-32005205|Esdoornstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32005206|Esdoornstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32005211|Paulus Potterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32005606|Aletta Jacobsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32005705|Klaroenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32005706|Klaroenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32005940|Plesmanlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32005941|Plesmanlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32006020|Dorpskade|NOTACCESSIBLE|NOTACCESSIBLE
-32007101|Binckhorstlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32007102|Binckhorstlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32007103|Diaconessenhuis|NOTACCESSIBLE|NOTACCESSIBLE
-32007104|Diaconessenhuis|NOTACCESSIBLE|NOTACCESSIBLE
-32007105|Redenburgstraat|NOTACCESSIBLE|NOTACCESSIBLE
-32007110|Voorburg Station|NOTACCESSIBLE|NOTACCESSIBLE
-32007111|Voorburg Station|NOTACCESSIBLE|NOTACCESSIBLE
-32007112|Sonnenburghlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32007202|Rozenboomlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32007411|Bruijnings Ingenhoeslaan|ACCESSIBLE|NOTACCESSIBLE
-32007412|Bruijnings Ingenhoeslaan|ACCESSIBLE|NOTACCESSIBLE
-32007505|Mgr. van Steelaan|ACCESSIBLE|NOTACCESSIBLE
-32007506|Mgr. van Steelaan|ACCESSIBLE|NOTACCESSIBLE
-32008125|Dorp|NOTACCESSIBLE|NOTACCESSIBLE
-32008128|Willem Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
-32008129|Willem Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
-32008131|Oosterheem|NOTACCESSIBLE|NOTACCESSIBLE
-32009115|Abtswoudsepark|NOTACCESSIBLE|NOTACCESSIBLE
-32009509|MCH Antoniushove|NOTACCESSIBLE|NOTACCESSIBLE
-32009515|Prins Bernhardlaan|NOTACCESSIBLE|NOTACCESSIBLE
-32009521|MCH Antoniushove|NOTACCESSIBLE|NOTACCESSIBLE
-32009568|Spieringdam|NOTACCESSIBLE|NOTACCESSIBLE
-32009574|Houtkade|NOTACCESSIBLE|NOTACCESSIBLE
-32009807|Laan van Nootdorp|NOTACCESSIBLE|NOTACCESSIBLE
-32009810|Scholekstersingel|NOTACCESSIBLE|NOTACCESSIBLE
-32009811|Scholekstersingel|NOTACCESSIBLE|NOTACCESSIBLE
-32009812|Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
-32009813|Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
-32009815|Nootdorp Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-42000101|Den Hoorn, Houtzagerij|NOTACCESSIBLE|NOTACCESSIBLE
-42000102|Den Hoorn, Houtzagerij|NOTACCESSIBLE|NOTACCESSIBLE
-42000202|Den Hoorn, Hof van Delftstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42000302|Schipluiden, Manege|NOTACCESSIBLE|NOTACCESSIBLE
-42000501|Den Hoorn, My home is my castle|NOTACCESSIBLE|NOTACCESSIBLE
-42000502|Den Hoorn, My home is my castle|NOTACCESSIBLE|NOTACCESSIBLE
-42001101|Delft, Aula - TU|NOTACCESSIBLE|NOTACCESSIBLE
-42001401|Delft, De Bieslandhof|NOTACCESSIBLE|NOTACCESSIBLE
-42001402|Delft, De Bieslandhof|NOTACCESSIBLE|NOTACCESSIBLE
-42002701|Delft, Koningin Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
-42002702|Delft, Koningin Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
-42003601|Delft, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
-42003602|Delft, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
-42003901|Delft, Krakeelpolderweg|NOTACCESSIBLE|NOTACCESSIBLE
-42004401|Delft, Markt|NOTACCESSIBLE|NOTACCESSIBLE
-42004501|Delft, Michiel de Ruyterweg|NOTACCESSIBLE|NOTACCESSIBLE
-42004502|Delft, Michiel de Ruyterweg|NOTACCESSIBLE|NOTACCESSIBLE
-42005302|Delft, Station Delft (Perron D)|NOTACCESSIBLE|NOTACCESSIBLE
-42005303|Delft, Station Delft (Perron E)|NOTACCESSIBLE|NOTACCESSIBLE
-42005305|Delft, Station Delft (Perron G)|NOTACCESSIBLE|NOTACCESSIBLE
-42005306|Delft, Station Delft (Perron J)|NOTACCESSIBLE|NOTACCESSIBLE
-42005307|Delft, Station Delft (Perron H)|NOTACCESSIBLE|NOTACCESSIBLE
-42005801|Delft, Prof. Krausstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42005802|Delft, Prof. Krausstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42006001|Delft, Prinsenhof|NOTACCESSIBLE|NOTACCESSIBLE
-42006002|Delft, Prinsenhof|NOTACCESSIBLE|NOTACCESSIBLE
-42006501|Delft, Schoemakerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42006502|Delft, Schoemakerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42007102|Delft, Vrijheidslaan|NOTACCESSIBLE|NOTACCESSIBLE
-42007201|Delft, Watermanweg|NOTACCESSIBLE|NOTACCESSIBLE
-42007202|Delft, Watermanweg|NOTACCESSIBLE|NOTACCESSIBLE
-42007601|Delft, Wateringsevest|NOTACCESSIBLE|NOTACCESSIBLE
-42007602|Delft, Wateringsevest|NOTACCESSIBLE|NOTACCESSIBLE
-42008903|De Lier, Jogchem van der Houtweg|NOTACCESSIBLE|NOTACCESSIBLE
-42009101|De Lier, Leeweg|NOTACCESSIBLE|NOTACCESSIBLE
-42009102|De Lier, Leeweg|NOTACCESSIBLE|NOTACCESSIBLE
-42009201|De Lier, Lierweg|NOTACCESSIBLE|NOTACCESSIBLE
-42009202|De Lier, Lierweg|NOTACCESSIBLE|NOTACCESSIBLE
-42009602|Den Haag, Arnold Spoelplein|NOTACCESSIBLE|NOTACCESSIBLE
-42009603|Den Haag, Arnold Spoelplein|NOTACCESSIBLE|NOTACCESSIBLE
-42009901|Den Haag, Boslaan|NOTACCESSIBLE|NOTACCESSIBLE
-42009902|Den Haag, Boslaan|NOTACCESSIBLE|NOTACCESSIBLE
-42010101|Den Haag, Bottgerwater|NOTACCESSIBLE|NOTACCESSIBLE
-42010102|Den Haag, Bottgerwater|NOTACCESSIBLE|NOTACCESSIBLE
-42010302|Den Haag, Brouwersgracht|NOTACCESSIBLE|NOTACCESSIBLE
-42010701|Den Haag, Castellum|NOTACCESSIBLE|NOTACCESSIBLE
-42010702|Den Haag, Castellum|NOTACCESSIBLE|NOTACCESSIBLE
-42011102|Den Haag, Dedemsvaartweg|NOTACCESSIBLE|NOTACCESSIBLE
-42011201|Den Haag, Defensie|NOTACCESSIBLE|NOTACCESSIBLE
-42011202|Den Haag, Defensie|NOTACCESSIBLE|NOTACCESSIBLE
-42011401|Den Haag, Dinkel|NOTACCESSIBLE|NOTACCESSIBLE
-42011501|Den Haag, Donau|NOTACCESSIBLE|NOTACCESSIBLE
-42011502|Den Haag, Donau|NOTACCESSIBLE|NOTACCESSIBLE
-42011802|Den Haag, Eendenplein|NOTACCESSIBLE|NOTACCESSIBLE
-42011901|Den Haag, Erasmusplein|NOTACCESSIBLE|NOTACCESSIBLE
-42011902|Den Haag, Erasmusplein|NOTACCESSIBLE|NOTACCESSIBLE
-42012101|Den Haag, Dr. H.E. van Gelderlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42012102|Den Haag, Dr. H.E. van Gelderlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42012301|Den Haag, Gouverneurplein|NOTACCESSIBLE|NOTACCESSIBLE
-42012501|Den Haag, Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
-42012502|Den Haag, Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
-42012601|Den Haag, Guirlande|NOTACCESSIBLE|NOTACCESSIBLE
-42012602|Den Haag, Guirlande|NOTACCESSIBLE|NOTACCESSIBLE
-42012702|Den Haag, Guntersteinweg|NOTACCESSIBLE|NOTACCESSIBLE
-42012801|Den Haag, Haeghe Flor|NOTACCESSIBLE|NOTACCESSIBLE
-42012802|Den Haag, Haeghe Flor|NOTACCESSIBLE|NOTACCESSIBLE
-42013101|Den Haag, Haagse Poort|NOTACCESSIBLE|NOTACCESSIBLE
-42013102|Den Haag, Haagse Poort|NOTACCESSIBLE|NOTACCESSIBLE
-42013201|Den Haag, Hoefkade|NOTACCESSIBLE|NOTACCESSIBLE
-42013202|Den Haag, Hoefkade|NOTACCESSIBLE|NOTACCESSIBLE
-42013301|Den Haag, Hofzichtlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42013302|Den Haag, Hofzichtlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42013501|Den Haag, Hobbemastraat|NOTACCESSIBLE|NOTACCESSIBLE
-42013502|Den Haag, Hobbemastraat|NOTACCESSIBLE|NOTACCESSIBLE
-42013801|Den Haag, Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
-42013802|Den Haag, Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
-42014101|Den Haag, Juliana van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
-42014102|Den Haag, Juliana van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
-42014601|Den Haag, Lage Veld|NOTACCESSIBLE|NOTACCESSIBLE
-42014602|Den Haag, Lage Veld|NOTACCESSIBLE|NOTACCESSIBLE
-42015001|Den Haag, Leliekeverstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42015002|Den Haag, Leliekeverstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42015601|Den Haag, Loire|NOTACCESSIBLE|NOTACCESSIBLE
-42015602|Den Haag, Loire|NOTACCESSIBLE|NOTACCESSIBLE
-42015801|Den Haag, Laan van 's-Gravenmade|NOTACCESSIBLE|NOTACCESSIBLE
-42015802|Den Haag, Laan van 's-Gravenmade|NOTACCESSIBLE|NOTACCESSIBLE
-42015901|Den Haag, Laan van Hoornwijck|NOTACCESSIBLE|NOTACCESSIBLE
-42015902|Den Haag, Laan van Hoornwijck|NOTACCESSIBLE|NOTACCESSIBLE
-42016101|Den Haag, Laan van Wateringseveld|NOTACCESSIBLE|NOTACCESSIBLE
-42016201|Den Haag, Laan van Ypenburg|NOTACCESSIBLE|NOTACCESSIBLE
-42016202|Den Haag, Laan van Ypenburg|NOTACCESSIBLE|NOTACCESSIBLE
-42016701|Den Haag, Moerweg/Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
-42016702|Den Haag, Moerweg/Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
-42017002|Den Haag, Laan van Nieuw Oost-Indie|NOTACCESSIBLE|NOTACCESSIBLE
-42017601|Den Haag, Ockenburghstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42017602|Den Haag, Ockenburghstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42017701|Den Haag, Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
-42017702|Den Haag, Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
-42017901|Den Haag, Parijsplein|NOTACCESSIBLE|NOTACCESSIBLE
-42017902|Den Haag, Parijsplein|NOTACCESSIBLE|NOTACCESSIBLE
-42018201|Den Haag, Paul Steenbergenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42018202|Den Haag, Paul Steenbergenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42018301|Den Haag, Q.A. Nederpelstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42018701|Den Haag, Rotonde Houtkade|NOTACCESSIBLE|NOTACCESSIBLE
-42018702|Den Haag, Rotonde Houtkade|NOTACCESSIBLE|NOTACCESSIBLE
-42019201|Den Haag, Steenhouwersgaarde|NOTACCESSIBLE|NOTACCESSIBLE
-42019401|Poeldijk, Teylingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42019402|Poeldijk, Teylingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42019501|Den Haag, Theems|NOTACCESSIBLE|NOTACCESSIBLE
-42019502|Den Haag, Theems|NOTACCESSIBLE|NOTACCESSIBLE
-42019601|Den Haag, Tiber|NOTACCESSIBLE|NOTACCESSIBLE
-42019602|Den Haag, Tiber|NOTACCESSIBLE|NOTACCESSIBLE
-42020501|Den Haag, Weidevogellaan|NOTACCESSIBLE|NOTACCESSIBLE
-42020502|Den Haag, Weidevogellaan|NOTACCESSIBLE|NOTACCESSIBLE
-42021001|'s-Gravenzande, Aaksterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42021002|'s-Gravenzande, Aaksterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42021101|'s-Gravenzande, Arco|NOTACCESSIBLE|NOTACCESSIBLE
-42021102|'s-Gravenzande, Arco|NOTACCESSIBLE|NOTACCESSIBLE
-42021401|Naaldwijk, Galgeweg|NOTACCESSIBLE|NOTACCESSIBLE
-42021402|Naaldwijk, Galgeweg|NOTACCESSIBLE|NOTACCESSIBLE
-42021501|'s-Gravenzande, Heenweg|NOTACCESSIBLE|NOTACCESSIBLE
-42021502|'s-Gravenzande, Heenweg|NOTACCESSIBLE|NOTACCESSIBLE
-42021602|'s-Gravenzande, Heliotroop|NOTACCESSIBLE|NOTACCESSIBLE
-42021702|'s-Gravenzande, Hoflaan|NOTACCESSIBLE|NOTACCESSIBLE
-42021801|Den Haag, Zichtenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
-42021802|Den Haag, Zichtenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
-42022101|'s-Gravenzande, Maasdijk|NOTACCESSIBLE|NOTACCESSIBLE
-42022102|'s-Gravenzande, Maasdijk|NOTACCESSIBLE|NOTACCESSIBLE
-42022201|'s-Gravenzande, Monsterseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42022202|'s-Gravenzande, Monsterseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42022502|'s-Gravenzande, Strandweg|NOTACCESSIBLE|NOTACCESSIBLE
-42022701|Den Haag, Zuidwerflaan|NOTACCESSIBLE|NOTACCESSIBLE
-42022702|Den Haag, Zuidwerflaan|NOTACCESSIBLE|NOTACCESSIBLE
-42023001|'s-Gravenzande, Vlugtenburg|NOTACCESSIBLE|NOTACCESSIBLE
-42023002|'s-Gravenzande, Vlugtenburg|NOTACCESSIBLE|NOTACCESSIBLE
-42023101|'s-Gravenzande, Villa Ouwendijk|NOTACCESSIBLE|NOTACCESSIBLE
-42023102|'s-Gravenzande, Villa Ouwendijk|NOTACCESSIBLE|NOTACCESSIBLE
-42023202|'s-Gravenzande, Vreeburghlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42023501|Honselersdijk, FloraHolland|NOTACCESSIBLE|NOTACCESSIBLE
-42023502|Honselersdijk, FloraHolland|NOTACCESSIBLE|NOTACCESSIBLE
-42023901|Honselersdijk, Middel Broekweg|NOTACCESSIBLE|NOTACCESSIBLE
-42023902|Honselersdijk, Middel Broekweg|NOTACCESSIBLE|NOTACCESSIBLE
-42024201|Honselersdijk, Nieuweweg|NOTACCESSIBLE|NOTACCESSIBLE
-42024301|Honselersdijk, Oostheullaan|NOTACCESSIBLE|NOTACCESSIBLE
-42024302|Honselersdijk, Oostheullaan|NOTACCESSIBLE|NOTACCESSIBLE
-42024701|Honselersdijk, Westlands Museum|NOTACCESSIBLE|NOTACCESSIBLE
-42024702|Honselersdijk, Westlands Museum|NOTACCESSIBLE|NOTACCESSIBLE
-42026903|Leidschendam, Damlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42027201|Leidschendam, GGZ Haagstreek|NOTACCESSIBLE|NOTACCESSIBLE
-42033901|Maasdijk, Coldenhovelaan|NOTACCESSIBLE|NOTACCESSIBLE
-42033902|Maasdijk, Coldenhovelaan|NOTACCESSIBLE|NOTACCESSIBLE
-42034201|Maasland, Duivenvlugt|NOTACCESSIBLE|NOTACCESSIBLE
-42034202|Maasland, Duivenvlugt|NOTACCESSIBLE|NOTACCESSIBLE
-42034301|Maasland, Hammerdreef|NOTACCESSIBLE|NOTACCESSIBLE
-42034302|Maasland, Hammerdreef|NOTACCESSIBLE|NOTACCESSIBLE
-42034501|Maasland, Kwakelweg|NOTACCESSIBLE|NOTACCESSIBLE
-42034502|Maasland, Kwakelweg|NOTACCESSIBLE|NOTACCESSIBLE
-42034601|Maasland, Lickebaertshoeve|NOTACCESSIBLE|NOTACCESSIBLE
-42034602|Maasland, Lickebaertshoeve|NOTACCESSIBLE|NOTACCESSIBLE
-42034701|Maasland, Maaslandsedam|NOTACCESSIBLE|NOTACCESSIBLE
-42034702|Maasland, Maaslandsedam|NOTACCESSIBLE|NOTACCESSIBLE
-42034801|Maasland, Twee Molens|NOTACCESSIBLE|NOTACCESSIBLE
-42034802|Maasland, Twee Molens|NOTACCESSIBLE|NOTACCESSIBLE
-42035005|Maasland, Viaduct|NOTACCESSIBLE|NOTACCESSIBLE
-42035401|Monster, Burg. Kampschoerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42035402|Monster, Burg. Kampschoerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42035501|Monster, Papelaan|NOTACCESSIBLE|NOTACCESSIBLE
-42035502|Monster, Papelaan|NOTACCESSIBLE|NOTACCESSIBLE
-42035802|Monster, De Tol|NOTACCESSIBLE|NOTACCESSIBLE
-42036101|Monster, Vlotlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42036102|Monster, Vlotlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42036501|Maasdijk, Groeneweg|NOTACCESSIBLE|NOTACCESSIBLE
-42036502|Maasdijk, Groeneweg|NOTACCESSIBLE|NOTACCESSIBLE
-42036601|Maasdijk, Nollaantje|NOTACCESSIBLE|NOTACCESSIBLE
-42036801|Maasdijk, Westerlee|NOTACCESSIBLE|NOTACCESSIBLE
-42036802|Maasdijk, Westerlee|NOTACCESSIBLE|NOTACCESSIBLE
-42039101|Nootdorp, Centrum/Parade|NOTACCESSIBLE|NOTACCESSIBLE
-42039102|Nootdorp, Centrum/Parade|NOTACCESSIBLE|NOTACCESSIBLE
-42039901|Nootdorp, Veenhage|NOTACCESSIBLE|NOTACCESSIBLE
-42039903|Nootdorp, Veenhage|NOTACCESSIBLE|NOTACCESSIBLE
-42040201|Naaldwijk, Grote Achterweg|NOTACCESSIBLE|NOTACCESSIBLE
-42040202|Naaldwijk, Grote Achterweg|NOTACCESSIBLE|NOTACCESSIBLE
-42040301|Naaldwijk, 's-Gravenzandseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42040302|Naaldwijk, 's-Gravenzandseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42040402|Naaldwijk, Hoge Woerd|NOTACCESSIBLE|NOTACCESSIBLE
-42040801|Naaldwijk, Monnikenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42040802|Naaldwijk, Monnikenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041101|Maasdijk, Sint Jorispad|NOTACCESSIBLE|NOTACCESSIBLE
-42041102|Maasdijk, Sint Jorispad|NOTACCESSIBLE|NOTACCESSIBLE
-42041201|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041202|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041203|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041204|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041206|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041207|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041208|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041209|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041401|Poeldijk, Paul Captijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041402|Poeldijk, Paul Captijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041801|Poeldijk, Dr. Weitjenslaan|NOTACCESSIBLE|NOTACCESSIBLE
-42041802|Poeldijk, Dr. Weitjenslaan|NOTACCESSIBLE|NOTACCESSIBLE
-42042101|Pijnacker, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-42042102|Pijnacker, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-42042201|Pijnacker, Bremlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42042202|Pijnacker, Bremlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42042301|Pijnacker, Burg|NOTACCESSIBLE|NOTACCESSIBLE
-42042302|Pijnacker, Burg|NOTACCESSIBLE|NOTACCESSIBLE
-42042401|Pijnacker, B.V. Mol|NOTACCESSIBLE|NOTACCESSIBLE
-42042402|Pijnacker, B.V. Mol|NOTACCESSIBLE|NOTACCESSIBLE
-42042801|Pijnacker, Groen van Prinstererlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42042802|Pijnacker, Groen van Prinstererlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42043001|Pijnacker, Klein Vlieland|NOTACCESSIBLE|NOTACCESSIBLE
-42043002|Pijnacker, Klein Vlieland|NOTACCESSIBLE|NOTACCESSIBLE
-42043101|Pijnacker, Meersma|NOTACCESSIBLE|NOTACCESSIBLE
-42043102|Pijnacker, Meersma|NOTACCESSIBLE|NOTACCESSIBLE
-42043201|Pijnacker, Molenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42043202|Pijnacker, Molenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42043301|Pijnacker, Mophuis|NOTACCESSIBLE|NOTACCESSIBLE
-42043302|Pijnacker, Mophuis|NOTACCESSIBLE|NOTACCESSIBLE
-42043401|Pijnacker, Nootdorpseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42043701|Pijnacker, Pasteurlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42043702|Pijnacker, Pasteurlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42043801|Pijnacker, Raadhuisplein|NOTACCESSIBLE|NOTACCESSIBLE
-42043802|Pijnacker, Raadhuisplein|NOTACCESSIBLE|NOTACCESSIBLE
-42043901|Pijnacker, Station|NOTACCESSIBLE|NOTACCESSIBLE
-42043902|Pijnacker, Station|NOTACCESSIBLE|NOTACCESSIBLE
-42044101|Pijnacker, van Vuren|NOTACCESSIBLE|NOTACCESSIBLE
-42044102|Pijnacker, van Vuren|NOTACCESSIBLE|NOTACCESSIBLE
-42044303|Rijswijk, Bogaard/Churchilllaan|NOTACCESSIBLE|NOTACCESSIBLE
-42044304|Rijswijk, Bogaard/Churchilllaan|NOTACCESSIBLE|NOTACCESSIBLE
-42044503|Rijswijk, De Bruyn Kopsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42044504|Rijswijk, De Bruyn Kopsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42044901|Rijswijk, 't Haantje|NOTACCESSIBLE|NOTACCESSIBLE
-42045203|Rijswijk, Dr. H.J. van Mooklaan|NOTACCESSIBLE|NOTACCESSIBLE
-42045403|Rijswijk, Station Rijswijk|NOTACCESSIBLE|NOTACCESSIBLE
-42045405|Rijswijk, Station Rijswijk|NOTACCESSIBLE|NOTACCESSIBLE
-42045501|Rijswijk, Laan van Oversteen|NOTACCESSIBLE|NOTACCESSIBLE
-42045502|Rijswijk, Laan van Oversteen|NOTACCESSIBLE|NOTACCESSIBLE
-42045601|Rijswijk, Patentlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42045602|Rijswijk, Patentlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42045901|Rijswijk, Polakweg|NOTACCESSIBLE|NOTACCESSIBLE
-42045902|Rijswijk, Polakweg|NOTACCESSIBLE|NOTACCESSIBLE
-42046101|Rijswijk, Schaapweg|NOTACCESSIBLE|NOTACCESSIBLE
-42046102|Rijswijk, Schaapweg|NOTACCESSIBLE|NOTACCESSIBLE
-42046503|Rijswijk, Treubstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42046603|Rijswijk, Volmerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42046604|Rijswijk, Volmerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42046803|Rijswijk, Verrijn Stuartlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42046804|Rijswijk, Verrijn Stuartlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42047601|Schipluiden, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-42047602|Schipluiden, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-42047701|Schipluiden, Groot Genoeg|NOTACCESSIBLE|NOTACCESSIBLE
-42047702|Schipluiden, Groot Genoeg|NOTACCESSIBLE|NOTACCESSIBLE
-42047801|Schipluiden, Hodenpijl|NOTACCESSIBLE|NOTACCESSIBLE
-42047802|Schipluiden, Hodenpijl|NOTACCESSIBLE|NOTACCESSIBLE
-42047901|Schipluiden, Kolkbrug|NOTACCESSIBLE|NOTACCESSIBLE
-42047902|Schipluiden, Kolkbrug|NOTACCESSIBLE|NOTACCESSIBLE
-42048001|Schipluiden, Lierhand|NOTACCESSIBLE|NOTACCESSIBLE
-42048002|Schipluiden, Lierhand|NOTACCESSIBLE|NOTACCESSIBLE
-42048101|Schipluiden, Molen|NOTACCESSIBLE|NOTACCESSIBLE
-42048102|Schipluiden, Molen|NOTACCESSIBLE|NOTACCESSIBLE
-42048201|Schipluiden, Op Hoop van Zegen|NOTACCESSIBLE|NOTACCESSIBLE
-42048202|Schipluiden, Op Hoop van Zegen|NOTACCESSIBLE|NOTACCESSIBLE
-42048301|Schipluiden, Opslagpl. Rijkswaterstaat|NOTACCESSIBLE|NOTACCESSIBLE
-42048302|Schipluiden, Opslagpl. Rijkswaterstaat|NOTACCESSIBLE|NOTACCESSIBLE
-42048401|Schipluiden, Schouwse Heul|NOTACCESSIBLE|NOTACCESSIBLE
-42048402|Schipluiden, Schouwse Heul|NOTACCESSIBLE|NOTACCESSIBLE
-42048501|Schipluiden, 't Woudt|NOTACCESSIBLE|NOTACCESSIBLE
-42048502|Schipluiden, 't Woudt|NOTACCESSIBLE|NOTACCESSIBLE
-42050402|Voorburg, Heer Hubrechtstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42050701|Voorburg, Laan van Heldenburg|NOTACCESSIBLE|NOTACCESSIBLE
-42050702|Voorburg, Laan van Heldenburg|NOTACCESSIBLE|NOTACCESSIBLE
-42051002|Voorburg, Station Leidschendam/Voorburg|NOTACCESSIBLE|NOTACCESSIBLE
-42051302|Voorburg, Potgieterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42051602|Voorburg, Rozenboomlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42052201|Voorburg, Zwartelaan/Station|NOTACCESSIBLE|NOTACCESSIBLE
-42052202|Voorburg, Zwartelaan/Station|NOTACCESSIBLE|NOTACCESSIBLE
-42055301|Wassenaar, Admiraal Helfrichlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42056602|Wassenaar, van Oldenbarneveltweg|NOTACCESSIBLE|NOTACCESSIBLE
-42056604|Wassenaar, van Oldenbarneveltweg|NOTACCESSIBLE|NOTACCESSIBLE
-42056801|Wassenaar, Papegaaienlaan|NOTACCESSIBLE|NOTACCESSIBLE
-42058002|Wassenaar, Wittenburgerweg|NOTACCESSIBLE|NOTACCESSIBLE
-42058801|Zoetermeer, Aluminiumstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42059001|Zoetermeer, Bastionhotel|NOTACCESSIBLE|NOTACCESSIBLE
-42059002|Zoetermeer, Bastionhotel|NOTACCESSIBLE|NOTACCESSIBLE
-42059301|Zoetermeer, Binnenwater|NOTACCESSIBLE|NOTACCESSIBLE
-42059302|Zoetermeer, Binnenwater|NOTACCESSIBLE|NOTACCESSIBLE
-42059401|Zoetermeer, Bordeauxstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42059402|Zoetermeer, Bordeauxstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42059601|Zoetermeer, Cobaltstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42059602|Zoetermeer, Cobaltstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060201|Zoetermeer, Dunantstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060202|Zoetermeer, Dunantstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060401|Zoetermeer, Edelgasstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060402|Zoetermeer, Edelgasstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060501|Zoetermeer, Edisonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060502|Zoetermeer, Edisonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060801|Zoetermeer, Miss Etam|NOTACCESSIBLE|NOTACCESSIBLE
-42060901|Zoetermeer, Frans Halsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42060902|Zoetermeer, Frans Halsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42061201|Zoetermeer, Fonteinbos|NOTACCESSIBLE|NOTACCESSIBLE
-42061401|Zoetermeer, Groenewater|NOTACCESSIBLE|NOTACCESSIBLE
-42061402|Zoetermeer, Groenewater|NOTACCESSIBLE|NOTACCESSIBLE
-42061501|Zoetermeer, van der Hagenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42061502|Zoetermeer, van der Hagenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42061801|Zoetermeer, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
-42061802|Zoetermeer, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
-42062201|Zoetermeer, Koperstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42062202|Zoetermeer, Koperstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42062401|Zoetermeer, Lansinghageweg|NOTACCESSIBLE|NOTACCESSIBLE
-42062601|Zoetermeer, 't Lange Land Ziekenhuis|NOTACCESSIBLE|NOTACCESSIBLE
-42062801|Zoetermeer, Marconistraat|NOTACCESSIBLE|NOTACCESSIBLE
-42062802|Zoetermeer, Marconistraat|NOTACCESSIBLE|NOTACCESSIBLE
-42063001|Zoetermeer, Metaalstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42063002|Zoetermeer, Metaalstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42063201|Zoetermeer, Newtonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42063202|Zoetermeer, Newtonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42063402|Zoetermeer, Station Oost|NOTACCESSIBLE|NOTACCESSIBLE
-42063403|Zoetermeer, Station Oost|NOTACCESSIBLE|NOTACCESSIBLE
-42063501|Zoetermeer, Station|NOTACCESSIBLE|NOTACCESSIBLE
-42063502|Zoetermeer, Station|NOTACCESSIBLE|NOTACCESSIBLE
-42063701|Zoetermeer, Oostwaarts|NOTACCESSIBLE|NOTACCESSIBLE
-42063702|Zoetermeer, Oostwaarts|NOTACCESSIBLE|NOTACCESSIBLE
-42063901|Zoetermeer, Philipsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42063902|Zoetermeer, Philipsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42064002|Zoetermeer, Poortugaalstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42064301|Zoetermeer, Robijn|NOTACCESSIBLE|NOTACCESSIBLE
-42064401|Zoetermeer, Rokkeveenseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42064402|Zoetermeer, Rokkeveenseweg|NOTACCESSIBLE|NOTACCESSIBLE
-42064501|Zoetermeer, Rokkeveenseweg-zuid|NOTACCESSIBLE|NOTACCESSIBLE
-42064502|Zoetermeer, Rokkeveenseweg-zuid|NOTACCESSIBLE|NOTACCESSIBLE
-42065501|Zoetermeer, Theaterplein|NOTACCESSIBLE|NOTACCESSIBLE
-42065502|Zoetermeer, Theaterplein|NOTACCESSIBLE|NOTACCESSIBLE
-42065801|Zoetermeer, van Galenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42065802|Zoetermeer, van Galenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42066001|Zoetermeer, Vijverhoek|NOTACCESSIBLE|NOTACCESSIBLE
-42066002|Zoetermeer, Vijverhoek|NOTACCESSIBLE|NOTACCESSIBLE
-42066601|Zoetermeer, Zilverstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42066602|Zoetermeer, Zilverstraat|NOTACCESSIBLE|NOTACCESSIBLE
-42068201|Nootdorp, Poort van Nootdorp|NOTACCESSIBLE|NOTACCESSIBLE
-42068202|Nootdorp, Poort van Nootdorp|NOTACCESSIBLE|NOTACCESSIBLE
-42070501|Wateringen, Hoefsmid|NOTACCESSIBLE|NOTACCESSIBLE
-42070901|Den Haag, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-42071101|Den Haag, Dedemvaartweg/Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
-42071102|Den Haag, Dedemvaartweg/Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
-42073201|Nootdorp, Kievitsbloem|NOTACCESSIBLE|NOTACCESSIBLE
-42073202|Nootdorp, Kievitsbloem|NOTACCESSIBLE|NOTACCESSIBLE
-54000730|Den Haag, Laan van Clingendael|NOTACCESSIBLE|NOTACCESSIBLE
-54142010|Den Haag, Laan van Clingendael|NOTACCESSIBLE|NOTACCESSIBLE
-54142020|Wassenaar, Rust en Vreugdlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54142050|Wassenaar, Kerkehout|NOTACCESSIBLE|NOTACCESSIBLE
-54142060|Wassenaar, Kerkehout|NOTACCESSIBLE|NOTACCESSIBLE
-54142090|Wassenaar, Houtlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54142100|Wassenaar, Houtlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54240150|Wassenaar, American School|NOTACCESSIBLE|NOTACCESSIBLE
-54240370|Wassenaar, Dr Mansveltkade/Duinrell|NOTACCESSIBLE|NOTACCESSIBLE
-54240380|Wassenaar, Dr Mansveltkade/Duinrell|NOTACCESSIBLE|NOTACCESSIBLE
-54240430|Wassenaar, Johan de Wittstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54240520|Wassenaar, Deijleroord|NOTACCESSIBLE|NOTACCESSIBLE
-54243010|Wassenaar, Rust en Vreugdlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54341010|Wassenaar, Deijleroord|NOTACCESSIBLE|NOTACCESSIBLE
-54410210|Zoetermeer, Boerhaavelaan|NOTACCESSIBLE|NOTACCESSIBLE
-54410220|Zoetermeer, Boerhaavelaan|NOTACCESSIBLE|NOTACCESSIBLE
-54410350|Zoetermeer, Raminhout|NOTACCESSIBLE|NOTACCESSIBLE
-54410360|Zoetermeer, Raminhout|NOTACCESSIBLE|NOTACCESSIBLE
-54410750|Zoetermeer, Osylaan|NOTACCESSIBLE|NOTACCESSIBLE
-54410760|Zoetermeer, Osylaan|NOTACCESSIBLE|NOTACCESSIBLE
-54410830|Zoetermeer, Radonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54410840|Zoetermeer, Radonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54411030|Zoetermeer, Ambachtsherenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411060|Zoetermeer, Station Palenstein|NOTACCESSIBLE|NOTACCESSIBLE
-54411070|Zoetermeer, Van Aalstlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411080|Zoetermeer, Van Aalstlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411270|Zoetermeer, Fokkerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54411280|Zoetermeer, Fokkerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54411290|Zoetermeer, Oostweg|NOTACCESSIBLE|NOTACCESSIBLE
-54411300|Zoetermeer, Oostweg|NOTACCESSIBLE|NOTACCESSIBLE
-54411310|Zoetermeer, Werner von Siemensstr.|NOTACCESSIBLE|NOTACCESSIBLE
-54411390|Zoetermeer, van Diestlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411400|Zoetermeer, van Diestlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411410|Zoetermeer, Vaartdreef|NOTACCESSIBLE|NOTACCESSIBLE
-54411420|Zoetermeer, Vaartdreef|NOTACCESSIBLE|NOTACCESSIBLE
-54411530|Zoetermeer, Meidoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411540|Zoetermeer, Meidoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
-54411560|Zoetermeer, Van Wijngaardenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54412230|Zoetermeer, Franklinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54412240|Zoetermeer, Franklinstraat|NOTACCESSIBLE|NOTACCESSIBLE
-54412260|Zoetermeer, Miss Etam|NOTACCESSIBLE|NOTACCESSIBLE
-54412270|Zoetermeer, Miss Etam|NOTACCESSIBLE|NOTACCESSIBLE
-54413010|Zoetermeer, Muzieklaan|NOTACCESSIBLE|NOTACCESSIBLE
-54413110|Zoetermeer, Marsmanhove|NOTACCESSIBLE|NOTACCESSIBLE
-54413120|Zoetermeer, Marsmanhove|NOTACCESSIBLE|NOTACCESSIBLE
-54413130|Zoetermeer, Aidaschouw|NOTACCESSIBLE|NOTACCESSIBLE
-54413140|Zoetermeer, Aidaschouw|NOTACCESSIBLE|NOTACCESSIBLE
-54415050|Zoetermeer, Mandelabrug/A12/Station|NOTACCESSIBLE|NOTACCESSIBLE
-54415060|Zoetermeer, Mandelabrug/A12/Station|NOTACCESSIBLE|NOTACCESSIBLE
-54415320|Zoetermeer, Werner von Siemensstr.|NOTACCESSIBLE|NOTACCESSIBLE
-54420130|Stompwijk, Meer- en Geerweg|NOTACCESSIBLE|NOTACCESSIBLE
-54420140|Stompwijk, Meer- en Geerweg|NOTACCESSIBLE|NOTACCESSIBLE
-54420160|Zoetermeer, Muzieklaan|NOTACCESSIBLE|NOTACCESSIBLE
-54421030|Stompwijk, Weltevreden|NOTACCESSIBLE|NOTACCESSIBLE
-54421040|Stompwijk, Weltevreden|NOTACCESSIBLE|NOTACCESSIBLE
-54510140|Zoetermeer, W. Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
-54510150|Zoetermeer, W. Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
-54510180|Zoetermeer, Benthuizenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50101100|Utrecht-De Uithof, Padualaan|NOTACCESSIBLE|ACCESSIBLE
-50006880|Utrecht, Oudwijkerdwarsstraat|NOTACCESSIBLE|ACCESSIBLE
-50002800|Utrecht, Hijmans v.d Berghlaan|NOTACCESSIBLE|ACCESSIBLE
-59140151|Utrecht, Savannahweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200911|Zeist, Sanatoriumlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59230060|Haarzuilens, Brink|NOTACCESSIBLE|NOTACCESSIBLE
-50000173|Utrecht, Rijnkade|NOTACCESSIBLE|NOTACCESSIBLE
-59152150|Utrecht, Rubicondreef|NOTACCESSIBLE|NOTACCESSIBLE
-59150820|Utrecht, Humberdreef|NOTACCESSIBLE|NOTACCESSIBLE
-51220432|Nieuwegein, Noorderveld|NOTACCESSIBLE|NOTACCESSIBLE
-51220581|Nieuwegein, Groningenhaven|NOTACCESSIBLE|NOTACCESSIBLE
-59490030|Den Dolder, Ernst Sillem Hoeve|NOTACCESSIBLE|NOTACCESSIBLE
-50000650|Utrecht, Oorsprongpark|NOTACCESSIBLE|NOTACCESSIBLE
-59150581|Utrecht, Burg. Van Tuyllkade|NOTACCESSIBLE|NOTACCESSIBLE
-51112000|Utrecht, Vredenburg Leidsche Rijn|NOTACCESSIBLE|NOTACCESSIBLE
-51320320|IJsselstein, Ewoud/Boerhaaveweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220420|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
-51111150|Utrecht, Klifrakplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-51225080|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-50002100|Utrecht, 24 Oktoberplein-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-59250342|Maarssenbroek, Zonnebaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340411|Vianen, Hagenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51380200|Schalkwijk, Ramselaar|NOTACCESSIBLE|NOTACCESSIBLE
-50390130|Odijk, Eikelaar|NOTACCESSIBLE|NOTACCESSIBLE
-50005504|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51111600|Utrecht, Meijewetering|NOTACCESSIBLE|NOTACCESSIBLE
-51320092|IJsselstein, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200510|Zeist, Nijenheim|NOTACCESSIBLE|NOTACCESSIBLE
-50202010|Zeist,  Soc. Werkvoorz. Zeist|NOTACCESSIBLE|NOTACCESSIBLE
-50006522|Utrecht, Texel|NOTACCESSIBLE|NOTACCESSIBLE
-50190120|Utrecht, Ln v Maarschalkerwd|NOTACCESSIBLE|NOTACCESSIBLE
-50003790|Utrecht, Kanaleneiland|NOTACCESSIBLE|NOTACCESSIBLE
-50000830|Utrecht, Majellapark|ACCESSIBLE|NOTACCESSIBLE
-51220920|Nieuwegein, Bernhardstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51110340|De Meern, Esdoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50003100|Utrecht, Dolomieten|ACCESSIBLE|ACCESSIBLE
-50007470|Utrecht, De Hoogstraat|ACCESSIBLE|ACCESSIBLE
-51200130|De Meern, De Balije|ACCESSIBLE|NOTACCESSIBLE
-50000400|Utrecht, Draaiweg|ACCESSIBLE|ACCESSIBLE
-50003040|Utrecht, Robijnlaan|ACCESSIBLE|ACCESSIBLE
-59150250|Utrecht, Klopvaart|ACCESSIBLE|ACCESSIBLE
-50001720|Utrecht, Kapteynlaan|ACCESSIBLE|ACCESSIBLE
-50001650|Utrecht, Pedro Luis Brionstraat|ACCESSIBLE|ACCESSIBLE
-50001670|Utrecht, Simon Bolivarstraat|ACCESSIBLE|ACCESSIBLE
-59150610|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
-51280850|Houten, Rondeel/De Veste|ACCESSIBLE|ACCESSIBLE
-50101090|Utrecht-De Uithof, Padualaan|ACCESSIBLE|ACCESSIBLE
-50003180|Utrecht, Betuwe|ACCESSIBLE|ACCESSIBLE
-51280820|Houten, De Gaarden|ACCESSIBLE|ACCESSIBLE
-50008150|Utrecht, Van Heuven Goedhartlaan|ACCESSIBLE|ACCESSIBLE
-50220170|Bilthoven, Berg en Bosch|ACCESSIBLE|ACCESSIBLE
-59151310|Utrecht, Oderdreef|ACCESSIBLE|ACCESSIBLE
-59200010|Maartensdijk, Groenhorst|ACCESSIBLE|ACCESSIBLE
-50100423|Utrecht, Rijnsweerd Noord|ACCESSIBLE|ACCESSIBLE
-59152100|Utrecht, Loevenhoutsedijk|ACCESSIBLE|ACCESSIBLE
-50001950|Utrecht, Racinelaan|ACCESSIBLE|ACCESSIBLE
-59151250|Utrecht, Theemsdreef|ACCESSIBLE|ACCESSIBLE
-51200410|Vleuten, Rivierkom Noord|NOTACCESSIBLE|NOTACCESSIBLE
-50100140|De Bilt, Alfred Nobellaan|ACCESSIBLE|ACCESSIBLE
-59152030|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
-50001390|Utrecht, Constant Erzeijstraat|ACCESSIBLE|ACCESSIBLE
-51280320|Houten, Bedr. Terr. Meidoornk.|ACCESSIBLE|ACCESSIBLE
-50007440|Utrecht, Rosarium|ACCESSIBLE|ACCESSIBLE
-50000511|Utrecht, Struyckenlaan|ACCESSIBLE|ACCESSIBLE
-59151340|Utrecht, Atlasdreef|ACCESSIBLE|ACCESSIBLE
-59250380|Maarssenbroek, Duiven-Fazantenkamp|ACCESSIBLE|ACCESSIBLE
-50001750|Utrecht, W. de Zwijgerplantsoen|ACCESSIBLE|ACCESSIBLE
-59151970|Utrecht, Amazonedreef|ACCESSIBLE|ACCESSIBLE
-50002840|Utrecht, Alexander Numankade|ACCESSIBLE|ACCESSIBLE
-50006510|Utrecht, Brennerbaan|ACCESSIBLE|ACCESSIBLE
-59152710|Maarssen, Rekreatieoord|ACCESSIBLE|NOTACCESSIBLE
-51280310|Houten, Bedr. Terr. Meidoornk.|ACCESSIBLE|ACCESSIBLE
-50100821|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
-50002590|Utrecht, Marco Pololaan|ACCESSIBLE|ACCESSIBLE
-50220030|Bilthoven, Leijenseweg|ACCESSIBLE|ACCESSIBLE
-50001810|Utrecht, Willem van Noortplein|ACCESSIBLE|ACCESSIBLE
-50002650|Utrecht, Aziëlaan|ACCESSIBLE|ACCESSIBLE
-50006170|Utrecht, Willem Dreeslaan|ACCESSIBLE|ACCESSIBLE
-50220130|Bilthoven, Hobbemalaan|ACCESSIBLE|ACCESSIBLE
-59100070|Groenekan, Centrum|ACCESSIBLE|ACCESSIBLE
-51340242|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
-59250620|Maarssenbroek, Planetenbaan|ACCESSIBLE|ACCESSIBLE
-50003120|Utrecht, Simplonbaan|ACCESSIBLE|ACCESSIBLE
-59150270|Utrecht, Carnegiedreef|ACCESSIBLE|ACCESSIBLE
-50008180|Utrecht, Marshalllaan|ACCESSIBLE|ACCESSIBLE
-50100130|De Bilt, Alfred Nobellaan|ACCESSIBLE|ACCESSIBLE
-59150611|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
-51340234|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
-50002380|Utrecht, Karperstraat|ACCESSIBLE|ACCESSIBLE
-50001700|Utrecht, Kemal Ataturkstraat|ACCESSIBLE|ACCESSIBLE
-59150481|Utrecht, Klopvaart|ACCESSIBLE|ACCESSIBLE
-50003030|Utrecht, Robijnlaan|ACCESSIBLE|ACCESSIBLE
-50002620|Utrecht, Columbuslaan/Afrikalaan|ACCESSIBLE|ACCESSIBLE
-59250391|Maarssenbroek, Duiven-Fazantenkamp|ACCESSIBLE|ACCESSIBLE
-59150210|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
-50220220|Bilthoven, Jan Provostlaan|ACCESSIBLE|ACCESSIBLE
-50006500|Utrecht, Stelviobaan|ACCESSIBLE|ACCESSIBLE
-59150780|Utrecht, Nijldreef|ACCESSIBLE|ACCESSIBLE
-51280680|Houten, Oude Dorp|ACCESSIBLE|ACCESSIBLE
-50200900|Zeist, Sanatoriumlaan|ACCESSIBLE|ACCESSIBLE
-50002810|Utrecht, Jan van Galenstraat|ACCESSIBLE|ACCESSIBLE
-50003150|Utrecht, Sleeswijk|ACCESSIBLE|ACCESSIBLE
-50001550|Utrecht, Koningin Wilhelminalaan|ACCESSIBLE|ACCESSIBLE
-50002032|Utrecht, Ziekenhuis Oudenrijn|ACCESSIBLE|ACCESSIBLE
-51280810|Houten, De Erven/De Schaft|ACCESSIBLE|ACCESSIBLE
-51280790|Houten, De Grassen|ACCESSIBLE|ACCESSIBLE
-59150840|Utrecht, Medusadreef|ACCESSIBLE|ACCESSIBLE
-50100200|De Bilt, Dr. Letteplein|ACCESSIBLE|ACCESSIBLE
-51281020|Houten, Odijkseweg|ACCESSIBLE|ACCESSIBLE
-51280430|Houten, De Molen|ACCESSIBLE|ACCESSIBLE
-50201000|Zeist, Heideweg|ACCESSIBLE|ACCESSIBLE
-51280840|Houten, Rondeel/Veste|ACCESSIBLE|ACCESSIBLE
-51110460|De Meern, Boekbinderslaan|ACCESSIBLE|NOTACCESSIBLE
-50001310|Utrecht, Rijnhuizenlaan|ACCESSIBLE|ACCESSIBLE
-50220480|Bilthoven, Berg en Bosch|ACCESSIBLE|ACCESSIBLE
-50200290|Zeist, Hogeweg|ACCESSIBLE|ACCESSIBLE
-50100550|Utrecht-De Uithof, WKZ|ACCESSIBLE|ACCESSIBLE
-50002000|Utrecht, Den Hommel|ACCESSIBLE|ACCESSIBLE
-50008100|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
-50003170|Utrecht, Betuwe|ACCESSIBLE|ACCESSIBLE
-50200090|Zeist, L. Flat|ACCESSIBLE|ACCESSIBLE
-51340244|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
-50008090|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
-51280770|Houten, Elzenkade|ACCESSIBLE|ACCESSIBLE
-59150220|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
-50100660|Bilthoven, Leeuwenhoekln/RIVM|ACCESSIBLE|NOTACCESSIBLE
-50002193|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
-59150710|Utrecht, Ammandreef|ACCESSIBLE|ACCESSIBLE
-59150740|Utrecht, Pekingdreef|ACCESSIBLE|ACCESSIBLE
-50001300|Utrecht, 't Goylaan|ACCESSIBLE|ACCESSIBLE
-50000390|Utrecht, Draaiweg|ACCESSIBLE|ACCESSIBLE
-59150760|Utrecht, Maniladreef|ACCESSIBLE|ACCESSIBLE
-50220240|Bilthoven, Rubenslaan|ACCESSIBLE|ACCESSIBLE
-50000410|Utrecht, Herenweg|ACCESSIBLE|ACCESSIBLE
-50001340|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
-50001660|Utrecht, Pedro Luis Brionstraat|ACCESSIBLE|ACCESSIBLE
-59151220|Utrecht, Ziekenhuis Overvecht|ACCESSIBLE|ACCESSIBLE
-50200040|Zeist, Winkelc. Vollenhove|ACCESSIBLE|ACCESSIBLE
-50003050|Utrecht, Slotlaan|ACCESSIBLE|ACCESSIBLE
-50200060|Zeist, Gunninglaan|ACCESSIBLE|ACCESSIBLE
-59200220|Maartensdijk, Fazantlaan|ACCESSIBLE|ACCESSIBLE
-50100810|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
-50000230|Utrecht, Winklerlaan|ACCESSIBLE|ACCESSIBLE
-50100240|Bilthoven, Zonneplein|ACCESSIBLE|ACCESSIBLE
-50001240|Utrecht, Europaplein|ACCESSIBLE|ACCESSIBLE
-50001710|Utrecht, Kapteynlaan|ACCESSIBLE|ACCESSIBLE
-59151370|Utrecht, Berezinadreef|ACCESSIBLE|ACCESSIBLE
-50003090|Utrecht, Dolomieten|ACCESSIBLE|ACCESSIBLE
-50002670|Utrecht, Australiëlaan|ACCESSIBLE|ACCESSIBLE
-51280740|Houten, De Borchen/Doornkade|ACCESSIBLE|ACCESSIBLE
-50006470|Utrecht, Lunettenbaan|ACCESSIBLE|ACCESSIBLE
-51281010|Houten, Kooikerspad|ACCESSIBLE|ACCESSIBLE
-59250411|Maarssenbroek, Pauwen-Reigerskamp|ACCESSIBLE|ACCESSIBLE
-50003110|Utrecht, Simplonbaan|ACCESSIBLE|ACCESSIBLE
-51281030|Houten, Odijkseweg|ACCESSIBLE|ACCESSIBLE
-59150750|Utrecht, Maniladreef|ACCESSIBLE|ACCESSIBLE
-50001680|Utrecht, Simon Bolivarstraat|ACCESSIBLE|ACCESSIBLE
-50007410|Utrecht, Prinsesselaan|ACCESSIBLE|ACCESSIBLE
-50220260|Bilthoven, Rubenslaan|ACCESSIBLE|ACCESSIBLE
-51280640|Houten, De Meren|ACCESSIBLE|NOTACCESSIBLE
-50006910|Utrecht, Homeruslaan|ACCESSIBLE|ACCESSIBLE
-51114350|Utrecht, Station Terwijde|ACCESSIBLE|NOTACCESSIBLE
-51280730|Houten, De Veste/De Slagen|ACCESSIBLE|ACCESSIBLE
-50007430|Utrecht, Rosarium|ACCESSIBLE|ACCESSIBLE
-50000250|Utrecht, De Lichtkring|ACCESSIBLE|ACCESSIBLE
-59151210|Utrecht, Ziekenhuis Overvecht|ACCESSIBLE|ACCESSIBLE
-50008170|Utrecht, Marshalllaan|ACCESSIBLE|ACCESSIBLE
-50002610|Utrecht, Columbuslaan/Afrikalaan|ACCESSIBLE|ACCESSIBLE
-50006480|Utrecht, Lunettenbaan|ACCESSIBLE|ACCESSIBLE
-50008160|Utrecht, Van Heuven Goedhartlaan|ACCESSIBLE|ACCESSIBLE
-51280590|Houten, Molenzoom|ACCESSIBLE|ACCESSIBLE
-59155000|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
-59150190|Utrecht, Sint Maartendreef|ACCESSIBLE|ACCESSIBLE
-51281000|Houten, Kooikerspad|ACCESSIBLE|ACCESSIBLE
-50001360|Utrecht, Tolsteegplantsoen|ACCESSIBLE|ACCESSIBLE
-51340231|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
-50006150|Utrecht, Kardinaal de Jongweg|ACCESSIBLE|ACCESSIBLE
-50100440|Utrecht, Rijnsweerd Zuid|ACCESSIBLE|NOTACCESSIBLE
-50001160|Utrecht, Diakonessenhuis|ACCESSIBLE|ACCESSIBLE
-59150410|Utrecht, Einsteindreef|ACCESSIBLE|ACCESSIBLE
-50008070|Utrecht, Vrieslantlaan|ACCESSIBLE|ACCESSIBLE
-50000220|Utrecht, Willem Dreeslaan|ACCESSIBLE|ACCESSIBLE
-59250630|Maarssenbroek, Planetenbaan|ACCESSIBLE|ACCESSIBLE
-50000330|Utrecht, Wittevrouwenbrug|ACCESSIBLE|ACCESSIBLE
-50007070|Utrecht, Nijverheidsweg|ACCESSIBLE|ACCESSIBLE
-59151290|Utrecht, Neckardreef|ACCESSIBLE|ACCESSIBLE
-50001960|Utrecht, Racinelaan|ACCESSIBLE|ACCESSIBLE
-50002570|Utrecht, Rooseveltlaan|ACCESSIBLE|ACCESSIBLE
-59151260|Utrecht, Theemsdreef|ACCESSIBLE|ACCESSIBLE
-50001980|Utrecht, Everard Meysterlaan|ACCESSIBLE|NOTACCESSIBLE
-50002111|Utrecht, Loevenhoutsedijk|ACCESSIBLE|ACCESSIBLE
-59150790|Utrecht, Oranjerivierdreef|ACCESSIBLE|ACCESSIBLE
-50007480|Utrecht, De Hoogstraat|ACCESSIBLE|ACCESSIBLE
-50100290|Bilthoven, Konijnenlaan|ACCESSIBLE|ACCESSIBLE
-59150260|Utrecht, Klopvaart|ACCESSIBLE|ACCESSIBLE
-59100210|Utrecht, Vulcanusdreef|ACCESSIBLE|ACCESSIBLE
-59150200|Utrecht, Sint Maartendreef|ACCESSIBLE|ACCESSIBLE
-59252031|Maarssenbroek, Pauwen-Reigerskamp|ACCESSIBLE|ACCESSIBLE
-59252005|Maarssenbroek, Spechten-Valkenkamp|ACCESSIBLE|ACCESSIBLE
-50200070|Zeist, Gunninglaan|ACCESSIBLE|ACCESSIBLE
-50002600|Utrecht, Marco Pololaan|ACCESSIBLE|ACCESSIBLE
-50100300|Bilthoven, Konijnenlaan|ACCESSIBLE|ACCESSIBLE
-59150730|Utrecht, Pekingdreef|ACCESSIBLE|ACCESSIBLE
-50006490|Utrecht, Stelviobaan|ACCESSIBLE|ACCESSIBLE
-50001530|Utrecht, Europaplein|ACCESSIBLE|ACCESSIBLE
-50001820|Utrecht, Willem van Noortplein|ACCESSIBLE|ACCESSIBLE
-50001400|Utrecht, Constant Erzeijstraat|ACCESSIBLE|ACCESSIBLE
-59250120|Maarssen, Dr. Plesmanlaan|ACCESSIBLE|ACCESSIBLE
-51280720|Houten, De Veste/De Slagen|ACCESSIBLE|ACCESSIBLE
-59151300|Utrecht, Neckardreef|ACCESSIBLE|ACCESSIBLE
-51340243|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
-50000200|Utrecht, Vulcanusdreef|ACCESSIBLE|ACCESSIBLE
-59250752|Maarssenbroek, Verbindingsweg|ACCESSIBLE|NOTACCESSIBLE
-50002710|Utrecht, Medusadreef|ACCESSIBLE|ACCESSIBLE
-59151980|Utrecht, Amazonedreef|ACCESSIBLE|ACCESSIBLE
-59250150|Maarssen, Maria Dommerstichting|ACCESSIBLE|ACCESSIBLE
-50220120|Bilthoven, Hobbemalaan|ACCESSIBLE|ACCESSIBLE
-59150720|Utrecht, Ammandreef|ACCESSIBLE|ACCESSIBLE
-50002820|Utrecht, Jan van Galenstraat|ACCESSIBLE|ACCESSIBLE
-50007120|Utrecht, Spinozaweg|ACCESSIBLE|ACCESSIBLE
-50200360|Zeist, Heerewegen|ACCESSIBLE|NOTACCESSIBLE
-50100811|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
-50002660|Utrecht, Aziëlaan|ACCESSIBLE|ACCESSIBLE
-51280630|Houten, De Mossen|ACCESSIBLE|ACCESSIBLE
-50003160|Utrecht, Sleeswijk|ACCESSIBLE|ACCESSIBLE
-50006860|Utrecht, Burg. Reigerstraat|ACCESSIBLE|ACCESSIBLE
-51280710|Houten, De Staart|ACCESSIBLE|ACCESSIBLE
-51280530|Houten, Koedijk|ACCESSIBLE|ACCESSIBLE
-51280700|Houten, De Staart|ACCESSIBLE|ACCESSIBLE
-50008030|Utrecht, David Ben Goerionstraat|ACCESSIBLE|ACCESSIBLE
-50001560|Utrecht, Koningin Wilhelminalaan|ACCESSIBLE|ACCESSIBLE
-50001770|Utrecht, Prof. Leonard Fuchslaan|ACCESSIBLE|ACCESSIBLE
-50002830|Utrecht, Alexander Numankade|ACCESSIBLE|ACCESSIBLE
-51280670|Houten, De Tuinen/Kruisboog|ACCESSIBLE|ACCESSIBLE
-59150221|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
-50006850|Utrecht, Burg. Reigerstraat|ACCESSIBLE|ACCESSIBLE
-50007090|Utrecht, Schepenbuurt|ACCESSIBLE|ACCESSIBLE
-50220150|Bilthoven, Albert Cuyplaan|ACCESSIBLE|ACCESSIBLE
-50000260|Utrecht, De Lichtkring|ACCESSIBLE|ACCESSIBLE
-59250130|Maarssen, Dr. Plesmanlaan|ACCESSIBLE|ACCESSIBLE
-51340233|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
-59250140|Maarssen, Maria Dommerstichting|ACCESSIBLE|ACCESSIBLE
-50008130|Utrecht, Ziekenhuis Oudenrijn|ACCESSIBLE|ACCESSIBLE
-50002042|Utrecht, Ziekenhuis Oudenrijn|ACCESSIBLE|ACCESSIBLE
-59200230|Maartensdijk, Fazantlaan|ACCESSIBLE|ACCESSIBLE
-50002790|Utrecht, Hijmans v.d. Berghlaan|ACCESSIBLE|ACCESSIBLE
-50220200|Bilthoven, Jan Provostlaan|ACCESSIBLE|ACCESSIBLE
-50002560|Utrecht, Van Bijnkershoeklaan|ACCESSIBLE|ACCESSIBLE
-50100230|Bilthoven, Zonneplein|ACCESSIBLE|ACCESSIBLE
-50000280|Utrecht, Prof. Dieperinklaan|ACCESSIBLE|ACCESSIBLE
-50001970|Utrecht, Everard Meysterlaan|ACCESSIBLE|NOTACCESSIBLE
-50002390|Utrecht, Kastelenplantsoen|ACCESSIBLE|ACCESSIBLE
-50001350|Utrecht, Tolsteegplantsoen|ACCESSIBLE|ACCESSIBLE
-50008050|Utrecht, IJsselsteinlaan|ACCESSIBLE|ACCESSIBLE
-51110450|De Meern, Boekbinderslaan|ACCESSIBLE|NOTACCESSIBLE
-50006920|Utrecht, Homeruslaan|ACCESSIBLE|ACCESSIBLE
-59250740|Maarssenbroek, Verbindingsweg|ACCESSIBLE|NOTACCESSIBLE
-50200050|Zeist, Winkelc. Vollenhove|ACCESSIBLE|ACCESSIBLE
-51280750|Houten, De Borchen/Doornkade|ACCESSIBLE|ACCESSIBLE
-51280431|Houten, De Molen|ACCESSIBLE|ACCESSIBLE
-50000270|Utrecht, Prof. Dieperinklaan|ACCESSIBLE|ACCESSIBLE
-50002550|Utrecht, Van Bijnkershoeklaan|ACCESSIBLE|ACCESSIBLE
-59252029|Maarssenbroek, Spechten-Valkenkamp|ACCESSIBLE|ACCESSIBLE
-50220140|Bilthoven, Albert Cuyplaan|ACCESSIBLE|ACCESSIBLE
-50007500|Utrecht, Hobbemastraat|ACCESSIBLE|ACCESSIBLE
-50220285|Bilthoven, Sperwerlaan|ACCESSIBLE|ACCESSIBLE
-51220720|Nieuwegein, Postkantoor|ACCESSIBLE|ACCESSIBLE
-50200080|Zeist, L. Flat|ACCESSIBLE|ACCESSIBLE
-50006520|Utrecht, Brennerbaan|ACCESSIBLE|ACCESSIBLE
-50100820|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
-50006160|Utrecht, Kardinaal de Jongweg|ACCESSIBLE|ACCESSIBLE
-59150800|Utrecht, Oranjerivierdreef|ACCESSIBLE|ACCESSIBLE
-50001320|Utrecht, Rijnhuizenlaan|ACCESSIBLE|ACCESSIBLE
-50100670|Bilthoven, Leeuwenhoekln/RIVM|ACCESSIBLE|NOTACCESSIBLE
-50007510|Utrecht, Hobbemastraat|ACCESSIBLE|ACCESSIBLE
-50220020|Bilthoven, Leijenseweg|ACCESSIBLE|ACCESSIBLE
-51280830|Houten, De Gaarden|ACCESSIBLE|ACCESSIBLE
-51280800|Houten, De Erven/De Schaft|ACCESSIBLE|ACCESSIBLE
-50003060|Utrecht, Slotlaan|ACCESSIBLE|ACCESSIBLE
-50002680|Utrecht, Zeelantlaan|ACCESSIBLE|ACCESSIBLE
-50100160|De Bilt, Hessenweg|ACCESSIBLE|ACCESSIBLE
-59152130|Utrecht, Korfoedreef|NOTACCESSIBLE|NOTACCESSIBLE
-51340120|Vianen, Marienhof|NOTACCESSIBLE|NOTACCESSIBLE
-50200870|Zeist, Van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
-50006670|Utrecht, Catharijneconvent|NOTACCESSIBLE|NOTACCESSIBLE
-50201050|Zeist, Verzetslaan|NOTACCESSIBLE|NOTACCESSIBLE
-51110190|Vleuten, Dorpsplein|NOTACCESSIBLE|NOTACCESSIBLE
-51200400|Haarzuilens, Thematerweg|NOTACCESSIBLE|NOTACCESSIBLE
-51340431|Vianen, Lange Dreef|NOTACCESSIBLE|NOTACCESSIBLE
-59250491|Maarssenbroek, Kamelenspoor|NOTACCESSIBLE|NOTACCESSIBLE
-50002080|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000581|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200040|Hollandsche Rading, Tolakkerweg 57|NOTACCESSIBLE|NOTACCESSIBLE
-51220890|Nieuwegein, B.J.Buurmanstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220871|Nieuwegein, Doorslag|NOTACCESSIBLE|NOTACCESSIBLE
-59390100|Huis ter Heide, Van Ostadelaan|NOTACCESSIBLE|NOTACCESSIBLE
-59230100|Haarzuilens, Gieltjesdorp|NOTACCESSIBLE|NOTACCESSIBLE
-50001111|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-59150500|Utrecht, Cornelis Smeenkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51380320|'t Goy, Wickenburghseweg|NOTACCESSIBLE|NOTACCESSIBLE
-51111590|Utrecht, Meijewetering|NOTACCESSIBLE|NOTACCESSIBLE
-50200011|Zeist, Jordanlaan/Kroostweg|NOTACCESSIBLE|NOTACCESSIBLE
-51180031|Nieuwegein, De Liesbosch|NOTACCESSIBLE|NOTACCESSIBLE
-59151280|Utrecht, Landskroondreef|NOTACCESSIBLE|NOTACCESSIBLE
-51220170|Nieuwegein, Landmansweide|NOTACCESSIBLE|NOTACCESSIBLE
-50220340|Bilthoven, Winkelc. Kwinkelier|NOTACCESSIBLE|NOTACCESSIBLE
-51380240|Schalkwijk, De Heul|NOTACCESSIBLE|NOTACCESSIBLE
-51380170|Schalkwijk, Ramselaar|NOTACCESSIBLE|NOTACCESSIBLE
-50006340|Utrecht, Van der Goesstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220031|Nieuwegein, Postkantoor|NOTACCESSIBLE|NOTACCESSIBLE
-51110510|De Meern, Zuiderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
-50005514|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51341210|Vianen, Hoeufftlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50001290|Utrecht, 't Goylaan|NOTACCESSIBLE|NOTACCESSIBLE
-50001020|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
-50005300|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
-59140040|Utrecht, Thoriumweg|NOTACCESSIBLE|NOTACCESSIBLE
-51200212|Vleuten, Sparrendaal|NOTACCESSIBLE|NOTACCESSIBLE
-50001230|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
-50200230|Zeist, Steynlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200330|Zeist, Louise de Colignypl.|NOTACCESSIBLE|NOTACCESSIBLE
-51380040|Schalkwijk, Korte Uitweg|NOTACCESSIBLE|NOTACCESSIBLE
-50006710|Utrecht, Centraal Museum|NOTACCESSIBLE|NOTACCESSIBLE
-59150501|Utrecht, Cornelis Smeenkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50001540|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
-51320100|IJsselstein, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
-51320130|IJsselstein, Binnenstad|NOTACCESSIBLE|NOTACCESSIBLE
-50100531|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
-51380100|Schalkwijk, Wickenburghselaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100210|Bilthoven, Groenekanseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200370|Zeist, Heerewegen|NOTACCESSIBLE|NOTACCESSIBLE
-51220800|Nieuwegein, Randijk|NOTACCESSIBLE|NOTACCESSIBLE
-50003610|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59250100|Maarssen, Winkelcentrum|NOTACCESSIBLE|NOTACCESSIBLE
-51111140|Utrecht, Archeologiepark|NOTACCESSIBLE|NOTACCESSIBLE
-50290130|Bunnik, Van Zijldreef|NOTACCESSIBLE|NOTACCESSIBLE
-50002131|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50390150|Odijk, Gaspeldoorn|NOTACCESSIBLE|NOTACCESSIBLE
-59150290|Utrecht, Daelwijck|NOTACCESSIBLE|NOTACCESSIBLE
-51220601|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
-50220080|Bilthoven, Soestdijkseweg-Noord|NOTACCESSIBLE|NOTACCESSIBLE
-59140120|Utrecht, Hyperonenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220071|Nieuwegein, Zorgcentrum Zuilenstein|NOTACCESSIBLE|NOTACCESSIBLE
-51220460|Nieuwegein, Buys Ballotbaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220621|Nieuwegein, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
-50390200|Odijk, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
-51220440|Nieuwegein, Noorderveld|NOTACCESSIBLE|NOTACCESSIBLE
-50201370|Zeist, Dijnselburg|NOTACCESSIBLE|NOTACCESSIBLE
-59200210|Maartensdijk, Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
-59330080|Kockengen, Wethouder Van Doornweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000920|Utrecht, Station Zuilen|NOTACCESSIBLE|NOTACCESSIBLE
-50000152|Utrecht, Voorstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51221031|Nieuwegein, Fokkesteeg|NOTACCESSIBLE|NOTACCESSIBLE
-51220650|Nieuwegein, Binnenwal|NOTACCESSIBLE|NOTACCESSIBLE
-59250550|Maarssenbroek, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200660|Zeist, Weeshuislaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100350|De Bilt, Burg. de Withstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50201100|Zeist, Handelscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-51340080|Vianen, Augustinushof|NOTACCESSIBLE|NOTACCESSIBLE
-50320010|Huis ter Heide, Prins Alexanderweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200310|Zeist, Amandelhof|NOTACCESSIBLE|NOTACCESSIBLE
-50205010|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
-51222210|Nieuwegein, Blokhoeve Noord|NOTACCESSIBLE|NOTACCESSIBLE
-50006540|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
-50100070|De Bilt, Tunneltje de Bilt|NOTACCESSIBLE|NOTACCESSIBLE
-50100430|Utrecht, Rijnsweerd Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-51285010|Houten, Station|NOTACCESSIBLE|NOTACCESSIBLE
-59150310|Maarssen, De Malle Jan|NOTACCESSIBLE|NOTACCESSIBLE
-51380080|Schalkwijk, Kloostergaarde|NOTACCESSIBLE|NOTACCESSIBLE
-51220910|Nieuwegein, Bernhardstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50006130|Utrecht, Mr. Tripkade|NOTACCESSIBLE|NOTACCESSIBLE
-50000860|Utrecht, Bleekstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59250810|Maarssen, Sportpark Oostwaard|NOTACCESSIBLE|NOTACCESSIBLE
-50290060|Bunnik, Kosterijland|NOTACCESSIBLE|NOTACCESSIBLE
-50100280|Bilthoven, Duivenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50003333|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50001000|Utrecht, Sterrenwijk|NOTACCESSIBLE|NOTACCESSIBLE
-50200720|Zeist, Prof.Lorentzln.-Zkh.|NOTACCESSIBLE|NOTACCESSIBLE
-50006410|Utrecht, Maasplein|NOTACCESSIBLE|NOTACCESSIBLE
-50001830|Utrecht, Willem van Noortstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50003070|Utrecht, Brennerbrug|NOTACCESSIBLE|NOTACCESSIBLE
-50200460|Zeist, Brugakker|NOTACCESSIBLE|NOTACCESSIBLE
-51340091|Vianen, Augustinushof|NOTACCESSIBLE|NOTACCESSIBLE
-59151960|Utrecht, Bogotadreef|NOTACCESSIBLE|NOTACCESSIBLE
-59151590|Utrecht, Prins Bernhardlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111560|Utrecht, Musicalkade|NOTACCESSIBLE|NOTACCESSIBLE
-51340051|Vianen, Clarissenhof|NOTACCESSIBLE|NOTACCESSIBLE
-59200160|Maartensdijk, Tuinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59152700|Maarssen, Herenweg|NOTACCESSIBLE|NOTACCESSIBLE
-59150180|Utrecht, Gageldijk 97|NOTACCESSIBLE|NOTACCESSIBLE
-50100590|De Bilt,  Grontmij Houdringe|NOTACCESSIBLE|NOTACCESSIBLE
-50100120|Zeist, Jordanlaan/Kroostweg|NOTACCESSIBLE|NOTACCESSIBLE
-51340092|Vianen, Augustinushof|NOTACCESSIBLE|NOTACCESSIBLE
-51220212|Nieuwegein, De Baten|NOTACCESSIBLE|NOTACCESSIBLE
-50007170|Utrecht, Jan Pietersz. Coenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51320050|IJsselstein, Mandenmaker|NOTACCESSIBLE|NOTACCESSIBLE
-51220572|Nieuwegein, Groningenhaven|NOTACCESSIBLE|NOTACCESSIBLE
-59150590|Utrecht, Jan van Zutphenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200300|Maartensdijk, Rotonde-Noord|NOTACCESSIBLE|NOTACCESSIBLE
-50200951|Zeist, Van Renesselaan|NOTACCESSIBLE|NOTACCESSIBLE
-50003370|Utrecht, Janskerkhof|NOTACCESSIBLE|NOTACCESSIBLE
-51345550|Vianen, Eendrachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000520|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200170|Maartensdijk, Tuinlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111190|Utrecht, De Woerd|NOTACCESSIBLE|NOTACCESSIBLE
-51200330|Vleuten, Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59100020|Maartensdijk, Achterwetering|NOTACCESSIBLE|NOTACCESSIBLE
-50003260|Utrecht, Afrikalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200840|Zeist, Graaf Adolflaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250231|Maarssen, Raadhuisstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50001790|Utrecht, Ingenhouszstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59200130|Maartensdijk, Mauritshoeve|NOTACCESSIBLE|NOTACCESSIBLE
-51380230|Schalkwijk, Viadukt|NOTACCESSIBLE|NOTACCESSIBLE
-59151350|Utrecht, Donaudreef|NOTACCESSIBLE|NOTACCESSIBLE
-51320040|IJsselstein, Europalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50003190|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
-51110370|De Meern, Sligro|NOTACCESSIBLE|NOTACCESSIBLE
-50200030|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|NOTACCESSIBLE
-50000190|Utrecht, Vredenburgviaduct|NOTACCESSIBLE|NOTACCESSIBLE
-50002510|Utrecht, Ravellaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340290|Vianen, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-59390040|Huis ter Heide, Park  Rodichem|NOTACCESSIBLE|NOTACCESSIBLE
-51325500|IJsselstein, Binnenstad|NOTACCESSIBLE|NOTACCESSIBLE
-50000570|Utrecht, David van Mollemstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50000850|Utrecht, Bleekstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50320040|Huis ter Heide, Sterrenberg|NOTACCESSIBLE|NOTACCESSIBLE
-50003540|Utrecht, Ina Boudier Bakkerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340010|Vianen, Hotel Vianen|NOTACCESSIBLE|NOTACCESSIBLE
-50003660|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
-50000002|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51200420|Vleuten, Rivierkom Noord|NOTACCESSIBLE|NOTACCESSIBLE
-51200290|Vleuten, Vrijthof|NOTACCESSIBLE|NOTACCESSIBLE
-51110210|Vleuten, Henri Dunantlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51380360|'t Goy, Oostrumsdijkje|NOTACCESSIBLE|NOTACCESSIBLE
-50002040|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-59151810|Utrecht, Oregondreef|NOTACCESSIBLE|NOTACCESSIBLE
-50001470|Utrecht, Oudenoord|NOTACCESSIBLE|NOTACCESSIBLE
-50002160|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-50000682|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
-51110350|De Meern, Esdoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200710|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000440|Utrecht, Viaduct|NOTACCESSIBLE|NOTACCESSIBLE
-51380050|Schalkwijk, Jhr. Ramweg|NOTACCESSIBLE|NOTACCESSIBLE
-59200050|Hollandsche Rading, Plantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-50002120|Utrecht, 5 Mei Plein|NOTACCESSIBLE|NOTACCESSIBLE
-59250730|Maarssen, Cramerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250190|Maarssen, Thorbeckelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220692|Nieuwegein, Herman Heijermanshove|NOTACCESSIBLE|NOTACCESSIBLE
-51320061|IJsselstein, Mandenmaker|NOTACCESSIBLE|NOTACCESSIBLE
-59200190|Maartensdijk, Koningin Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220111|Nieuwegein, Galecopperdijk|NOTACCESSIBLE|NOTACCESSIBLE
-50201340|Zeist, Schaerweydelaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200380|Zeist, Prinses Margrietlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200250|Maartensdijk, Valklaan|NOTACCESSIBLE|NOTACCESSIBLE
-59140220|Utrecht, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-51110050|De Meern, Strijkviertel|NOTACCESSIBLE|NOTACCESSIBLE
-50200740|Zeist, Jagersingel|NOTACCESSIBLE|NOTACCESSIBLE
-59250670|Maarssenbroek, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220100|Nieuwegein, Galecopperdijk|NOTACCESSIBLE|NOTACCESSIBLE
-50003630|Utrecht, Ondiep|NOTACCESSIBLE|NOTACCESSIBLE
-59230140|Haarzuilens, Ockhuizerweg|NOTACCESSIBLE|NOTACCESSIBLE
-59200100|Maartensdijk, Rotonde-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-50002240|Utrecht, Nicolaas Beetsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50007160|Utrecht, Billitonkade|NOTACCESSIBLE|NOTACCESSIBLE
-50000070|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
-50220165|Bilthoven, Boslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50320030|Huis ter Heide, Dolderseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100260|Bilthoven, Poolsterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000720|Utrecht, P+R Veemarkt|NOTACCESSIBLE|NOTACCESSIBLE
-59150340|Utrecht, Muyskenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51280030|Houten, Prov.weg/Doornkade|NOTACCESSIBLE|NOTACCESSIBLE
-50100420|Utrecht, Rijnsweerd Noord|NOTACCESSIBLE|NOTACCESSIBLE
-50001440|Utrecht, Rozenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59152060|Utrecht, Taagdreef|NOTACCESSIBLE|NOTACCESSIBLE
-51200340|Vleuten, Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000341|Utrecht, Wittevrouwenbrug|NOTACCESSIBLE|NOTACCESSIBLE
-51221080|Nieuwegein, Rembrandthage|NOTACCESSIBLE|NOTACCESSIBLE
-59100040|Maartensdijk, Nieuwe-Wetering|NOTACCESSIBLE|NOTACCESSIBLE
-59250211|Maarssen, Parkweg|NOTACCESSIBLE|NOTACCESSIBLE
-51221420|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
-59152140|Utrecht, Korfoedreef|NOTACCESSIBLE|NOTACCESSIBLE
-50001460|Utrecht, Sint Jacobsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59150530|Utrecht, Prins Bernhardplein|NOTACCESSIBLE|NOTACCESSIBLE
-50101040|Utrecht, De Kromme Rijn|NOTACCESSIBLE|NOTACCESSIBLE
-50007111|Utrecht, Spinozaweg|NOTACCESSIBLE|NOTACCESSIBLE
-59390140|Den Dolder, Pleineslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50201460|Zeist, Geroplein|NOTACCESSIBLE|NOTACCESSIBLE
-50190090|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
-51380260|Schalkwijk, Viadukt|NOTACCESSIBLE|NOTACCESSIBLE
-59150450|Utrecht, De Bazelstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51180020|Nieuwegein, De Liesbosch|NOTACCESSIBLE|NOTACCESSIBLE
-51320410|IJsselstein, Lagebiezen|NOTACCESSIBLE|NOTACCESSIBLE
-50101030|Utrecht, De Kromme Rijn|NOTACCESSIBLE|NOTACCESSIBLE
-50200750|Zeist, Jagersingel|NOTACCESSIBLE|NOTACCESSIBLE
-50001220|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-59200240|Maartensdijk, Valklaan|NOTACCESSIBLE|NOTACCESSIBLE
-59150910|Utrecht, Station Zuilen|NOTACCESSIBLE|NOTACCESSIBLE
-51340350|Vianen, v.Duvenvoordestraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220280|Nieuwegein, Calscollege|NOTACCESSIBLE|NOTACCESSIBLE
-51220260|Nieuwegein, Noordstedeweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000480|Utrecht, Watertoren|NOTACCESSIBLE|NOTACCESSIBLE
-51380140|Schalkwijk, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
-59151302|Utrecht, Tamarinde|NOTACCESSIBLE|NOTACCESSIBLE
-50201240|Zeist,  Woudschoten|NOTACCESSIBLE|NOTACCESSIBLE
-51120010|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
-51220561|Nieuwegein, Brabanthaven|NOTACCESSIBLE|NOTACCESSIBLE
-50007050|Utrecht, Gietijzerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50008020|Utrecht, Schaverijstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59151770|Utrecht, Franciscusdreef|NOTACCESSIBLE|NOTACCESSIBLE
-51340330|Vianen, Brugstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220340|Nieuwegein, H.Heijermanshove|NOTACCESSIBLE|NOTACCESSIBLE
-50200830|Zeist, Pr. Margrietlaan 235|NOTACCESSIBLE|NOTACCESSIBLE
-50310120|Austerlitz, Traayweg|NOTACCESSIBLE|NOTACCESSIBLE
-50001860|Utrecht, Adelaarstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51111310|Utrecht, Korianderstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50001370|Utrecht, Vondellaan|NOTACCESSIBLE|NOTACCESSIBLE
-51320080|IJsselstein, Televisiebaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340420|Vianen, Hagenweg|NOTACCESSIBLE|NOTACCESSIBLE
-59140210|Utrecht, Niels Bohrweg|NOTACCESSIBLE|NOTACCESSIBLE
-50002250|Utrecht, Hoogh Boulandt|NOTACCESSIBLE|NOTACCESSIBLE
-50006650|Utrecht, Hamburgerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51340150|Vianen, Weidekamp|NOTACCESSIBLE|NOTACCESSIBLE
-50201520|Zeist, Lageweg/Waterigeweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000350|Utrecht, Stadsschouwburg|NOTACCESSIBLE|NOTACCESSIBLE
-51220591|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
-50220110|Bilthoven, Van der Helstlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100532|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
-59152160|Utrecht, Rubicondreef|NOTACCESSIBLE|NOTACCESSIBLE
-50201220|Zeist, Alg. Begraafplaats|NOTACCESSIBLE|NOTACCESSIBLE
-59252023|Maarssenbroek, Zebraspoor|NOTACCESSIBLE|NOTACCESSIBLE
-51340340|Vianen, Brugstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51340130|Vianen, 't Zand|NOTACCESSIBLE|NOTACCESSIBLE
-51220900|Nieuwegein, B.J.Buurmanstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59250770|Maarssenbroek, Niels Bohrweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000001|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50290070|Bunnik, Kosterijland|NOTACCESSIBLE|NOTACCESSIBLE
-51220051|Nieuwegein, Wenckebachplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-51280760|Houten, Elzenkade|NOTACCESSIBLE|NOTACCESSIBLE
-50000370|Utrecht, Janskerkhof|NOTACCESSIBLE|NOTACCESSIBLE
-59150170|Utrecht, Gageldijk 97|NOTACCESSIBLE|NOTACCESSIBLE
-51221050|Nieuwegein, Gerbrandypark|NOTACCESSIBLE|NOTACCESSIBLE
-51111010|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
-50005503|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51320091|IJsselstein, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000300|Utrecht, Eykmanplein|NOTACCESSIBLE|NOTACCESSIBLE
-59150130|Maarssen, Gageldijk 41|NOTACCESSIBLE|NOTACCESSIBLE
-50007100|Utrecht, Schepenbuurt|NOTACCESSIBLE|NOTACCESSIBLE
-51280190|Houten, Poeldijk|NOTACCESSIBLE|NOTACCESSIBLE
-59151950|Utrecht, Bogotadreef|NOTACCESSIBLE|NOTACCESSIBLE
-59250091|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
-59490020|Den Dolder, Ernst Sillem Hoeve|NOTACCESSIBLE|NOTACCESSIBLE
-59150320|Maarssen, De Malle Jan|NOTACCESSIBLE|NOTACCESSIBLE
-59150460|Utrecht, Prins Bernhardplein|NOTACCESSIBLE|NOTACCESSIBLE
-51220831|Nieuwegein, Waterlelie|NOTACCESSIBLE|NOTACCESSIBLE
-59250212|Maarssen, Parkweg|NOTACCESSIBLE|NOTACCESSIBLE
-51340451|Vianen, Sportlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51320032|IJsselstein, Europalaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220991|Nieuwegein, Waterbies|NOTACCESSIBLE|NOTACCESSIBLE
-50005502|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51111200|Utrecht, De Woerd|NOTACCESSIBLE|NOTACCESSIBLE
-50003800|Utrecht, Kanaleneiland|NOTACCESSIBLE|NOTACCESSIBLE
-50200820|Zeist, Pr. Margrietlaan 235|NOTACCESSIBLE|NOTACCESSIBLE
-50005055|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51110140|De Meern, Noorderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
-50310030|Austerlitz, KNVB-Sportcentrum|NOTACCESSIBLE|NOTACCESSIBLE
-50006370|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220411|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
-59250093|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
-59100100|Groenekan, Zwembad  Blauwkapel|NOTACCESSIBLE|NOTACCESSIBLE
-59250081|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
-59150390|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
-51220271|Nieuwegein, Noordstedeweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220300|Nieuwegein, Merwesteintunnel|NOTACCESSIBLE|NOTACCESSIBLE
-51200450|Vleuten, Stroomrugbaan|NOTACCESSIBLE|NOTACCESSIBLE
-50001241|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
-51380020|'t Goy, Odijk|NOTACCESSIBLE|NOTACCESSIBLE
-50002210|Utrecht, Willemsviaduct|NOTACCESSIBLE|NOTACCESSIBLE
-50006690|Utrecht, Universiteitsmuseum|NOTACCESSIBLE|NOTACCESSIBLE
-51200210|De Meern, Esdoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50002142|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59200200|Maartensdijk, Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000030|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51221032|Nieuwegein, Fokkesteeg|NOTACCESSIBLE|NOTACCESSIBLE
-51320071|IJsselstein, Televisiebaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220080|Nieuwegein, Orpheuslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100530|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
-59390070|Bosch en Duin, Vossenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100400|Utrecht, Archimedeslaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250720|Maarssen, Cramerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200760|Zeist, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000060|Utrecht, 24 Oktoberplein|NOTACCESSIBLE|NOTACCESSIBLE
-50003640|Utrecht, Ondiep|NOTACCESSIBLE|NOTACCESSIBLE
-50200810|Zeist, Pr. Margrietlaan 405|NOTACCESSIBLE|NOTACCESSIBLE
-51280020|Houten, Koppeldijk|NOTACCESSIBLE|NOTACCESSIBLE
-59151620|Utrecht, Minister Talmastraat|NOTACCESSIBLE|NOTACCESSIBLE
-59150431|Utrecht, Burg. Van Tuyllkade|NOTACCESSIBLE|NOTACCESSIBLE
-59250030|Maarssen, Herenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51111240|Utrecht, Het Zand|NOTACCESSIBLE|NOTACCESSIBLE
-51340400|Vianen, Verz C. Batenstein|NOTACCESSIBLE|NOTACCESSIBLE
-51111170|Utrecht, Kreekraklaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200490|Zeist, Koppelweg|NOTACCESSIBLE|NOTACCESSIBLE
-51200240|Vleuten, Bottensteinweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220452|Nieuwegein, Buys Ballotbaan|NOTACCESSIBLE|NOTACCESSIBLE
-51112500|Utrecht, Vredenburg Leidsche Rijn|NOTACCESSIBLE|NOTACCESSIBLE
-59140160|Utrecht, Savannahweg|NOTACCESSIBLE|NOTACCESSIBLE
-50003350|Utrecht, Stadsschouwburg|NOTACCESSIBLE|NOTACCESSIBLE
-50100020|De Bilt, Steinenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
-59140080|Utrecht, Uraniumweg|NOTACCESSIBLE|NOTACCESSIBLE
-59151760|Utrecht, J.M.de Muinck Keizerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220641|Nieuwegein, Binnenwal|NOTACCESSIBLE|NOTACCESSIBLE
-50200340|Zeist, De Oldenborgh|NOTACCESSIBLE|NOTACCESSIBLE
-51111420|Utrecht, Mercatorlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000512|Utrecht, Struyckenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220972|Nieuwegein, 't Veerhuis|NOTACCESSIBLE|NOTACCESSIBLE
-50007490|Utrecht, Prins Hendriklaan|NOTACCESSIBLE|NOTACCESSIBLE
-50007140|Utrecht, Laan van Nieuw Guinea|NOTACCESSIBLE|NOTACCESSIBLE
-50101060|Utrecht, Wim Sonneveldlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50006630|Utrecht, Domplein|NOTACCESSIBLE|NOTACCESSIBLE
-59151820|Utrecht, Oregondreef|NOTACCESSIBLE|NOTACCESSIBLE
-50100520|Utrecht-De Uithof, Heidelberglaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250200|Maarssen, Parkweg|NOTACCESSIBLE|NOTACCESSIBLE
-59152050|Utrecht, Taagdreef|NOTACCESSIBLE|NOTACCESSIBLE
-59250700|Maarssen, Ranstplein|NOTACCESSIBLE|NOTACCESSIBLE
-51320421|IJsselstein, Lagebiezen|NOTACCESSIBLE|NOTACCESSIBLE
-50006350|Utrecht, Brederoplein|NOTACCESSIBLE|NOTACCESSIBLE
-51220712|Nieuwegein, Graaf Florisweg|NOTACCESSIBLE|NOTACCESSIBLE
-59250060|Maarssen, Zwembad|NOTACCESSIBLE|NOTACCESSIBLE
-51111210|Utrecht, Tweede Westerparklaan|NOTACCESSIBLE|NOTACCESSIBLE
-51320031|IJsselstein, Europalaan|NOTACCESSIBLE|NOTACCESSIBLE
-51280260|Houten, Prov.weg/Doornkade|NOTACCESSIBLE|NOTACCESSIBLE
-51285000|Houten, Station|NOTACCESSIBLE|NOTACCESSIBLE
-50200160|Zeist, Burg. Patijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59151600|Utrecht, Prins Bernhardlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59150240|Utrecht, Daelwijck|NOTACCESSIBLE|NOTACCESSIBLE
-51114360|Utrecht, Station Terwijde|NOTACCESSIBLE|NOTACCESSIBLE
-50390170|Odijk, Rijnseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50390180|Odijk, Rijnseweg|NOTACCESSIBLE|NOTACCESSIBLE
-51221020|Nieuwegein, Raalterveste|NOTACCESSIBLE|NOTACCESSIBLE
-50310050|Austerlitz, Austerlitzseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50201060|Zeist, Vrijheidsplein|NOTACCESSIBLE|NOTACCESSIBLE
-51220220|Nieuwegein, Barnsteendrift|NOTACCESSIBLE|NOTACCESSIBLE
-50002190|Utrecht, Station Overvecht|NOTACCESSIBLE|NOTACCESSIBLE
-51320390|IJsselstein, Achtersloot|NOTACCESSIBLE|NOTACCESSIBLE
-51380070|Schalkwijk, Wickenburghselaan|NOTACCESSIBLE|NOTACCESSIBLE
-59150150|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51320710|IJsselstein, Goudplevier|NOTACCESSIBLE|NOTACCESSIBLE
-59230010|Haarzuilens, Thematerweg|NOTACCESSIBLE|NOTACCESSIBLE
-50390050|Odijk, De Vork|NOTACCESSIBLE|NOTACCESSIBLE
-51200213|Vleuten, Sparrendaal|NOTACCESSIBLE|NOTACCESSIBLE
-51111110|Utrecht, Burgemeester Verderlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59390090|Den Dolder, Hertenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340140|Vianen, 't Zand|NOTACCESSIBLE|NOTACCESSIBLE
-59390050|Huis ter Heide, Park  Rodichem|NOTACCESSIBLE|NOTACCESSIBLE
-50200500|Zeist, Koppelweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100610|De Bilt,  Grontmij Houdringe|NOTACCESSIBLE|NOTACCESSIBLE
-50190080|Bunnik, Van Zijldreef|NOTACCESSIBLE|NOTACCESSIBLE
-59390020|Huis ter Heide, Frans van Mierislaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111470|Utrecht, Papendorp Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-59150550|Utrecht, Sweder van Zuylenweg|NOTACCESSIBLE|NOTACCESSIBLE
-50002030|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51111180|Utrecht, Kreekraklaan|NOTACCESSIBLE|NOTACCESSIBLE
-59151180|Utrecht, Niftarlakeplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-50001380|Utrecht, Vondellaan|NOTACCESSIBLE|NOTACCESSIBLE
-59140071|Utrecht, Uraniumweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000530|Utrecht, Nijenoord|NOTACCESSIBLE|NOTACCESSIBLE
-50201110|Zeist, Vrijheidsplein|NOTACCESSIBLE|NOTACCESSIBLE
-51111260|Utrecht, Utrechtseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50310090|Austerlitz, Dorpsplein|NOTACCESSIBLE|NOTACCESSIBLE
-59150401|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
-50310040|Austerlitz, Austerlitzseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50003140|Utrecht, De Koppel|NOTACCESSIBLE|NOTACCESSIBLE
-51110150|De Meern, Noorderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
-59230070|Haarzuilens, Brink|NOTACCESSIBLE|NOTACCESSIBLE
-50006310|Utrecht, Van Zijstweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100170|De Bilt, Looijdijk|NOTACCESSIBLE|NOTACCESSIBLE
-59250560|Maarssenbroek, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-59151240|Utrecht, Kaap Hoorndreef|NOTACCESSIBLE|NOTACCESSIBLE
-50007450|Utrecht, Dillenburgstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50001800|Utrecht, Ingenhouszstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220700|Nieuwegein, Graaf Florisweg|NOTACCESSIBLE|NOTACCESSIBLE
-59100050|Groenekan, Buitenlust|NOTACCESSIBLE|NOTACCESSIBLE
-59250531|Maarssenbroek, Vogelweg-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
-50200800|Zeist, Pr. Margrietlaan 405|NOTACCESSIBLE|NOTACCESSIBLE
-50002070|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200480|Zeist, De Sluis|NOTACCESSIBLE|NOTACCESSIBLE
-50000640|Utrecht, Wittevrouwen|NOTACCESSIBLE|NOTACCESSIBLE
-50100050|De Bilt, Kerklaan|NOTACCESSIBLE|NOTACCESSIBLE
-51320422|IJsselstein, Lagebiezen|NOTACCESSIBLE|NOTACCESSIBLE
-51380350|Schalkwijk, Trip|NOTACCESSIBLE|NOTACCESSIBLE
-59250110|Maarssen, Winkelcentrum|NOTACCESSIBLE|NOTACCESSIBLE
-50200411|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|NOTACCESSIBLE
-50201480|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200170|Zeist, Burg. Patijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59150600|Utrecht, Professor Bavinckstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59200070|Maartensdijk, Industrieterrein|NOTACCESSIBLE|NOTACCESSIBLE
-50001080|Utrecht, Stadionlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000470|Utrecht, Watertoren|NOTACCESSIBLE|NOTACCESSIBLE
-51280950|Houten, De Muren|NOTACCESSIBLE|NOTACCESSIBLE
-50005501|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51180070|Nieuwegein, Ravenswade|NOTACCESSIBLE|NOTACCESSIBLE
-50007110|Utrecht, Spinozaweg|NOTACCESSIBLE|NOTACCESSIBLE
-59230150|Haarzuilens, Polderweg|NOTACCESSIBLE|NOTACCESSIBLE
-51380130|Schalkwijk, Rozenhoeve|NOTACCESSIBLE|NOTACCESSIBLE
-50290050|Bunnik, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-50001760|Utrecht, W. de Zwijgerplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-51110770|De Meern, Proost en Brandt|NOTACCESSIBLE|NOTACCESSIBLE
-51220140|Nieuwegein, Middenweide|NOTACCESSIBLE|NOTACCESSIBLE
-50310010|Zeist, Woudschoten|NOTACCESSIBLE|NOTACCESSIBLE
-50000630|Utrecht, Wittevrouwen|NOTACCESSIBLE|NOTACCESSIBLE
-51220992|Nieuwegein, Waterbies|NOTACCESSIBLE|NOTACCESSIBLE
-50100250|Bilthoven, Poolsterlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200020|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|NOTACCESSIBLE
-50002022|Utrecht, Welgelegen|NOTACCESSIBLE|NOTACCESSIBLE
-51114600|Utrecht, Parkzichtlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200960|Zeist, Het Rond|NOTACCESSIBLE|NOTACCESSIBLE
-51340522|Vianen, De Limiet-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-51200200|Vleuten, Rivierkom Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-59250361|Maarssenbroek, Bloem-Boomstede|NOTACCESSIBLE|NOTACCESSIBLE
-50205022|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
-50100110|Utrecht, P+R Veemarkt|NOTACCESSIBLE|NOTACCESSIBLE
-59150810|Utrecht, Humberdreef|NOTACCESSIBLE|NOTACCESSIBLE
-59230020|Haarzuilens, Joostenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59300070|Hollandsche Rading, Vuurse Dreef|NOTACCESSIBLE|NOTACCESSIBLE
-50200100|Zeist, De Dreef/Panweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000040|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51340170|Vianen, Pr.Julianastraat|NOTACCESSIBLE|NOTACCESSIBLE
-50006810|Utrecht, Stadsschouwburg|NOTACCESSIBLE|NOTACCESSIBLE
-50007190|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
-50220060|Bilthoven, Bilderdijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-59150090|Utrecht, Fort De Gagel|NOTACCESSIBLE|NOTACCESSIBLE
-51225030|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-50201010|Zeist, Heideweg|NOTACCESSIBLE|NOTACCESSIBLE
-50205000|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
-51225082|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-50100030|De Bilt, Steinenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220512|Nieuwegein, Oosterlichtcollege|NOTACCESSIBLE|NOTACCESSIBLE
-50200780|Zeist, Prinses Irenelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220290|Nieuwegein, Calscollege|NOTACCESSIBLE|NOTACCESSIBLE
-50005507|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50201390|Zeist, Johannes Postlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50201030|Zeist, Nieuw Beerschoten|NOTACCESSIBLE|NOTACCESSIBLE
-59140230|Utrecht, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
-59200090|Maartensdijk, Rotonde-Noord|NOTACCESSIBLE|NOTACCESSIBLE
-50000781|Utrecht, Kanonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220231|Nieuwegein, Barnsteendrift|NOTACCESSIBLE|NOTACCESSIBLE
-50390100|Odijk, N229-Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
-59150100|Utrecht, Fort De Gagel|NOTACCESSIBLE|NOTACCESSIBLE
-59330040|Kockengen, Kockengensebrug|NOTACCESSIBLE|NOTACCESSIBLE
-51200190|Vleuten, Rivierkom Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-51111320|Utrecht, Korianderstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51111220|Utrecht, Tweede Westerparklaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250220|Maarssen, Raadhuisstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51341220|Vianen, Hoeufftlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200790|Zeist, Prinses Irenelaan|NOTACCESSIBLE|NOTACCESSIBLE
-50101010|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
-50002129|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
-59140060|Utrecht, Kernweg|NOTACCESSIBLE|NOTACCESSIBLE
-50002191|Utrecht, Station Overvecht|NOTACCESSIBLE|NOTACCESSIBLE
-50200970|Zeist, Het Rond|NOTACCESSIBLE|NOTACCESSIBLE
-51220751|Nieuwegein, Guido Gezellehove|NOTACCESSIBLE|NOTACCESSIBLE
-51380250|'t Goy, Odijk|NOTACCESSIBLE|NOTACCESSIBLE
-50000660|Utrecht, Oorsprongpark|NOTACCESSIBLE|NOTACCESSIBLE
-59390170|Den Dolder,  Willem Arntszhoeve|NOTACCESSIBLE|NOTACCESSIBLE
-50190030|Utrecht, Koningsweg 175|NOTACCESSIBLE|NOTACCESSIBLE
-50190050|Bunnik,  Oud Amelisweerd|NOTACCESSIBLE|NOTACCESSIBLE
-50200940|Zeist, Van Renesselaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220552|Nieuwegein, Brabanthaven|NOTACCESSIBLE|NOTACCESSIBLE
-50000100|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
-50100700|Utrecht, Cambridgelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220390|Nieuwegein, Huis de Geer|NOTACCESSIBLE|NOTACCESSIBLE
-59200310|Maartensdijk, Rotonde-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-50320020|Huis ter Heide, Dolderseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50007460|Utrecht, Dillenburgstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220971|Nieuwegein, 't Veerhuis|NOTACCESSIBLE|NOTACCESSIBLE
-50100100|De Bilt, Amersfoortseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50002128|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50410010|Austerlitz, De Pyramide|NOTACCESSIBLE|NOTACCESSIBLE
-50200670|Zeist, Weeshuislaan|NOTACCESSIBLE|NOTACCESSIBLE
-50001780|Utrecht, Prof. Leonard Fuchslaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200110|Maartensdijk, Achterwetering|NOTACCESSIBLE|NOTACCESSIBLE
-50100080|De Bilt, Biltse Hoek|NOTACCESSIBLE|NOTACCESSIBLE
-50201320|Zeist, Berkenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59200150|Maartensdijk, Rustenhoven|NOTACCESSIBLE|NOTACCESSIBLE
-59230130|Haarzuilens, Ockhuizerweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100360|De Bilt, Burg. de Withstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50007150|Utrecht, Billitonkade|NOTACCESSIBLE|NOTACCESSIBLE
-51280050|Houten, Koppeldijk|NOTACCESSIBLE|NOTACCESSIBLE
-50190010|Utrecht, Koningsweg / A 27|NOTACCESSIBLE|NOTACCESSIBLE
-59150060|Utrecht, Oud Zuilen|NOTACCESSIBLE|NOTACCESSIBLE
-51320342|IJsselstein, Goudplevier|NOTACCESSIBLE|NOTACCESSIBLE
-59200030|Hollandsche Rading, Tolakkerweg 57|NOTACCESSIBLE|NOTACCESSIBLE
-50200180|Zeist, Van der Merschlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200260|Zeist, Schaerweydelaan|NOTACCESSIBLE|NOTACCESSIBLE
-59230040|Haarzuilens, Kasteel|NOTACCESSIBLE|NOTACCESSIBLE
-51320072|IJsselstein, Televisiebaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100650|De Bilt, De Holle Bilt|NOTACCESSIBLE|NOTACCESSIBLE
-51220272|Nieuwegein, Noordstedeweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100450|Utrecht-De Uithof, Botanische Tuinen|NOTACCESSIBLE|NOTACCESSIBLE
-50190100|Utrecht, Koningsweg / A 27|NOTACCESSIBLE|NOTACCESSIBLE
-51320402|IJsselstein, Achtersloot|NOTACCESSIBLE|NOTACCESSIBLE
-50000140|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
-50003360|Utrecht, Neude|NOTACCESSIBLE|NOTACCESSIBLE
-50001490|Utrecht, David van Mollemstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51380120|Schalkwijk, Spoorlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111130|Utrecht, Archeologiepark|NOTACCESSIBLE|NOTACCESSIBLE
-51200250|Vleuten, Alenveltpark|NOTACCESSIBLE|NOTACCESSIBLE
-59151200|Utrecht, J.M.de Muinck Keizerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50006420|Utrecht, Maasplein|NOTACCESSIBLE|NOTACCESSIBLE
-50220090|Bilthoven, Soestdijkseweg-Noord|NOTACCESSIBLE|NOTACCESSIBLE
-51180080|Nieuwegein, Penitentiaire Inr.|NOTACCESSIBLE|NOTACCESSIBLE
-51220410|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220211|Nieuwegein, De Baten|NOTACCESSIBLE|NOTACCESSIBLE
-51111060|Nieuwegein, Remiseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000360|Utrecht, Neude|NOTACCESSIBLE|NOTACCESSIBLE
-50220100|Bilthoven, Van der Helstlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000460|Utrecht, Concordiastraat|NOTACCESSIBLE|NOTACCESSIBLE
-59330060|Kockengen, Kerkweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220610|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
-50200190|Zeist, Van der Merschlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51380380|Schalkwijk, Trip|NOTACCESSIBLE|NOTACCESSIBLE
-50000182|Utrecht, Zkh. Oudenrijn/Beneluxlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50220440|Maartensdijk, Mauritshoeve|NOTACCESSIBLE|NOTACCESSIBLE
-50001850|Utrecht, Adelaarstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50000880|Utrecht, Van Koetsveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50007130|Utrecht, Laan van Nieuw Guinea|NOTACCESSIBLE|NOTACCESSIBLE
-50390010|Bunnik, Uitgaansc. Brothers|NOTACCESSIBLE|NOTACCESSIBLE
-51220691|Nieuwegein, H.Heijermanshove|NOTACCESSIBLE|NOTACCESSIBLE
-50201380|Zeist, Johannes Postlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220820|Nieuwegein, Waterlelie|NOTACCESSIBLE|NOTACCESSIBLE
-51200270|Vleuten, De Reit|NOTACCESSIBLE|NOTACCESSIBLE
-51200218|Vleuten, Wilhelminalaan|NOTACCESSIBLE|NOTACCESSIBLE
-51325501|IJsselstein, Binnenstad|NOTACCESSIBLE|NOTACCESSIBLE
-50200440|Zeist, Noordweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200390|Zeist, Prinses Margrietlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250050|Maarssen, De Wilgenplas|NOTACCESSIBLE|NOTACCESSIBLE
-51225040|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-59140140|Utrecht, Otto Hahnweg|NOTACCESSIBLE|NOTACCESSIBLE
-51320401|IJsselstein, Achtersloot|NOTACCESSIBLE|NOTACCESSIBLE
-50008040|Utrecht, Burg. Fockema Andreaelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51110791|De Meern, Oracle|NOTACCESSIBLE|NOTACCESSIBLE
-50291000|Bunnik, Station|NOTACCESSIBLE|NOTACCESSIBLE
-59152070|Utrecht, Brailledreef|NOTACCESSIBLE|NOTACCESSIBLE
-59250232|Maarssen, Raadhuisstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51340491|Vianen, Edisonweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100040|De Bilt, Kerklaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220740|Nieuwegein, Guido Gezellehove|NOTACCESSIBLE|NOTACCESSIBLE
-50200300|Zeist, Amandelhof|NOTACCESSIBLE|NOTACCESSIBLE
-51200310|Vleuten, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50490010|Odijk, Fruittuin|NOTACCESSIBLE|NOTACCESSIBLE
-51380270|t Goy, Café  De Eng|NOTACCESSIBLE|NOTACCESSIBLE
-50100510|Utrecht-De Uithof, Heidelberglaan|NOTACCESSIBLE|NOTACCESSIBLE
-50201090|Huis ter Heide, P.Alexanderstichting|NOTACCESSIBLE|NOTACCESSIBLE
-50002180|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
-59200080|Maartensdijk, Industrieterrein|NOTACCESSIBLE|NOTACCESSIBLE
-59151930|Utrecht, Orinocodreef|NOTACCESSIBLE|NOTACCESSIBLE
-51320360|IJsselstein, Overwaard|NOTACCESSIBLE|NOTACCESSIBLE
-59140131|Utrecht, Otto Hahnweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200280|Zeist, Hogeweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100630|De Bilt, De Holle Bilt|NOTACCESSIBLE|NOTACCESSIBLE
-51380310|'t Goy, Oostrumsdijkje|NOTACCESSIBLE|NOTACCESSIBLE
-50200220|Zeist, Steynlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50220190|Bilthoven, Walnootlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51200370|Vleuten, Henri Dunantlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59100090|Groenekan, Zwembad  Blauwkapel|NOTACCESSIBLE|NOTACCESSIBLE
-51220501|Nieuwegein, Wattbaan|NOTACCESSIBLE|NOTACCESSIBLE
-59230160|Haarzuilens, Polderweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200150|Zeist, Nepveulaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200210|Zeist, J.van Lennepplein|NOTACCESSIBLE|NOTACCESSIBLE
-50220290|Bilthoven, Walnootlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200990|Zeist, Molenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51111230|Utrecht, Het Zand|NOTACCESSIBLE|NOTACCESSIBLE
-50310100|Austerlitz, Waterlooweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200730|Zeist, Prof.Lorentzln.-Zkh.|NOTACCESSIBLE|NOTACCESSIBLE
-51380190|Schalkwijk, De Heul|NOTACCESSIBLE|NOTACCESSIBLE
-59252009|Maarssenbroek, Vogelweg-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
-51220930|Nieuwegein, Koninginnenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340180|Vianen, Pr.Julianastraat|NOTACCESSIBLE|NOTACCESSIBLE
-51200280|Vleuten, De Reit|NOTACCESSIBLE|NOTACCESSIBLE
-50200430|Zeist, Noordweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100091|De Bilt, Amersfoortseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000960|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51110380|De Meern, Sligro|NOTACCESSIBLE|NOTACCESSIBLE
-51200260|Vleuten, Alenveltpark|NOTACCESSIBLE|NOTACCESSIBLE
-50390240|Odijk, Jodichemdreef|NOTACCESSIBLE|NOTACCESSIBLE
-51220151|Nieuwegein, Middenweide|NOTACCESSIBLE|NOTACCESSIBLE
-59151870|Utrecht, Nebraskadreef|NOTACCESSIBLE|NOTACCESSIBLE
-50100190|De Bilt, Dr. Letteplein|NOTACCESSIBLE|NOTACCESSIBLE
-51220730|Nieuwegein, Leusderschans|NOTACCESSIBLE|NOTACCESSIBLE
-51220532|Nieuwegein, De Bongenaar|NOTACCESSIBLE|NOTACCESSIBLE
-50003080|Utrecht, Brennerbrug|NOTACCESSIBLE|NOTACCESSIBLE
-50200931|Zeist, Griftlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50201470|Zeist, Geroplein|NOTACCESSIBLE|NOTACCESSIBLE
-50003400|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
-50390070|Odijk, Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
-59250660|Maarssenbroek, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
-50205020|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
-50201360|Zeist, Dijnselburg|NOTACCESSIBLE|NOTACCESSIBLE
-50200320|Zeist, Louise de Colignypl.|NOTACCESSIBLE|NOTACCESSIBLE
-51200350|Vleuten, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220880|Nieuwegein, Leusderschans|NOTACCESSIBLE|NOTACCESSIBLE
-50000671|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000610|Utrecht, Afrikalaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220960|Nieuwegein, Berkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220370|Nieuwegein, Blauwe Brug|NOTACCESSIBLE|NOTACCESSIBLE
-51220330|Nieuwegein, Martinbaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100220|De Bilt, Groenekanseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50290040|Bunnik, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-50200980|Zeist, Molenweg|NOTACCESSIBLE|NOTACCESSIBLE
-50100060|De Bilt, Tunneltje de Bilt|NOTACCESSIBLE|NOTACCESSIBLE
-51380110|Schalkwijk, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
-59330090|Kockengen, Wethouder Van Doornweg|NOTACCESSIBLE|NOTACCESSIBLE
-50201510|Zeist, Lageweg|NOTACCESSIBLE|NOTACCESSIBLE
-59140111|Utrecht, Hyperonenweg|NOTACCESSIBLE|NOTACCESSIBLE
-50391110|Bunnik, Uitgaansc. Brothers|NOTACCESSIBLE|NOTACCESSIBLE
-59151270|Utrecht, Landskroondreef|NOTACCESSIBLE|NOTACCESSIBLE
-51220770|Nieuwegein, Constructieweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220602|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
-59330020|Kockengen, Portengen|NOTACCESSIBLE|NOTACCESSIBLE
-50000172|Utrecht, Rijnkade|NOTACCESSIBLE|NOTACCESSIBLE
-50390080|Odijk, Fruittuin|NOTACCESSIBLE|NOTACCESSIBLE
-50310130|Austerlitz, Traayweg|NOTACCESSIBLE|NOTACCESSIBLE
-50006330|Utrecht, Van der Goesstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59230090|Haarzuilens, De Bom|NOTACCESSIBLE|NOTACCESSIBLE
-50200580|Zeist, Godfried van Seystln|NOTACCESSIBLE|NOTACCESSIBLE
-50000771|Utrecht, Kanonstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50002860|Utrecht, Griftstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51200380|Vleuten, Henri Dunantlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111550|Utrecht, Musicalkade|NOTACCESSIBLE|NOTACCESSIBLE
-51220380|Nieuwegein, 't Veerhuis|NOTACCESSIBLE|NOTACCESSIBLE
-51220940|Nieuwegein, Koninginnenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59151880|Utrecht, Nebraskadreef|NOTACCESSIBLE|NOTACCESSIBLE
-50002540|Utrecht, Overste den Oudenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111120|Utrecht, Burgemeester Verderlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250800|Maarssen, Sportpark Oostwaard|NOTACCESSIBLE|NOTACCESSIBLE
-51220091|Nieuwegein, Orpheuslaan|NOTACCESSIBLE|NOTACCESSIBLE
-50007060|Utrecht, Gietijzerstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50007030|Utrecht, Walserijstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59250440|Maarssenbroek, Spechten-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
-50000870|Utrecht, Van Koetsveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50000950|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
-51380300|t Goy, Café  De Eng|NOTACCESSIBLE|NOTACCESSIBLE
-50006300|Utrecht, Jaarbeursplein|NOTACCESSIBLE|NOTACCESSIBLE
-50201260|Zeist, Grote Koppel|NOTACCESSIBLE|NOTACCESSIBLE
-51280660|Houten, De Tuinen/Kruisboog|NOTACCESSIBLE|NOTACCESSIBLE
-51111100|Nieuwegein, Blokhoeve Noord|NOTACCESSIBLE|NOTACCESSIBLE
-51320341|IJsselstein, Goudplevier|NOTACCESSIBLE|NOTACCESSIBLE
-59150990|Utrecht, Kaap Hoorndreef|NOTACCESSIBLE|NOTACCESSIBLE
-59150370|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250350|Maarssenbroek, Zonnebaan|NOTACCESSIBLE|NOTACCESSIBLE
-59390180|Den Dolder, Soestdijkerweg|NOTACCESSIBLE|NOTACCESSIBLE
-59150140|Maarssen, Gageldijk 41|NOTACCESSIBLE|NOTACCESSIBLE
-51220492|Nieuwegein, Wattbaan|NOTACCESSIBLE|NOTACCESSIBLE
-50490040|Werkhoven, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
-59490010|Den Dolder, Soestdijkerweg|NOTACCESSIBLE|NOTACCESSIBLE
-51200217|Vleuten, Wilhelminalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50006380|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
-59151860|Utrecht, Arizonadreef|NOTACCESSIBLE|NOTACCESSIBLE
-51111050|Nieuwegein, Remiseweg|NOTACCESSIBLE|NOTACCESSIBLE
-50201120|Huis ter Heide, P.Alexanderstichting|NOTACCESSIBLE|NOTACCESSIBLE
-50006900|Utrecht, Oosterstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50006400|Utrecht, Waalstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50320050|Huis ter Heide, Sterrenberg|NOTACCESSIBLE|NOTACCESSIBLE
-50100330|De Bilt, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51340440|Vianen, Lange Dreef|NOTACCESSIBLE|NOTACCESSIBLE
-50005536|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51340161|Vianen, Weidekamp|NOTACCESSIBLE|NOTACCESSIBLE
-51220200|Nieuwegein, De Baten|NOTACCESSIBLE|NOTACCESSIBLE
-50000800|Utrecht, Hasebroekstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220521|Nieuwegein, Oosterlichtcollege|NOTACCESSIBLE|NOTACCESSIBLE
-50003620|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59151990|Utrecht, Paranadreef|NOTACCESSIBLE|NOTACCESSIBLE
-59330070|Kockengen, Kerkweg|NOTACCESSIBLE|NOTACCESSIBLE
-59390060|Bosch en Duin, Vossenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51221060|Nieuwegein, Gerbrandypark|NOTACCESSIBLE|NOTACCESSIBLE
-50200850|Zeist, Graaf Adolflaan|NOTACCESSIBLE|NOTACCESSIBLE
-51111450|Utrecht, Orteliuslaan|NOTACCESSIBLE|NOTACCESSIBLE
-51380030|Schalkwijk, Kloostergaarde|NOTACCESSIBLE|NOTACCESSIBLE
-51340542|Vianen, Laanakkerweg|NOTACCESSIBLE|NOTACCESSIBLE
-50201300|Zeist, Kritzingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
-51110801|De Meern, Oracle|NOTACCESSIBLE|NOTACCESSIBLE
-59255000|Maarssen, Station/Bisonspoor|NOTACCESSIBLE|NOTACCESSIBLE
-50590010|Werkhoven, Hardenbroek|NOTACCESSIBLE|NOTACCESSIBLE
-50201330|Zeist, Berkenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000710|Utrecht, Sartreweg|NOTACCESSIBLE|NOTACCESSIBLE
-50000340|Utrecht, Wittevrouwenbrug|NOTACCESSIBLE|NOTACCESSIBLE
-51180090|Nieuwegein, Penitentiaire Inr.|NOTACCESSIBLE|NOTACCESSIBLE
-50100710|Utrecht, Bolognalaan|NOTACCESSIBLE|NOTACCESSIBLE
-50105500|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
-59250040|Maarssen, De Wilgenplas|NOTACCESSIBLE|NOTACCESSIBLE
-59252011|Maarssenbroek, Zebraspoor|NOTACCESSIBLE|NOTACCESSIBLE
-59390120|Den Dolder, Station|NOTACCESSIBLE|NOTACCESSIBLE
-50201140|Huis ter Heide, Prins Alexanderweg|NOTACCESSIBLE|NOTACCESSIBLE
-51220120|Nieuwegein, De Kempenaerpark|NOTACCESSIBLE|NOTACCESSIBLE
-51220021|Nieuwegein, Postkantoor|NOTACCESSIBLE|NOTACCESSIBLE
-50002010|Utrecht, Den Hommel|NOTACCESSIBLE|NOTACCESSIBLE
-50001021|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
-50002200|Utrecht, Moreelsepark/HC|NOTACCESSIBLE|NOTACCESSIBLE
-59200140|Maartensdijk, Rustenhoven|NOTACCESSIBLE|NOTACCESSIBLE
-51340360|Vianen, v. Duvenvoordestraat|NOTACCESSIBLE|NOTACCESSIBLE
-50002220|Utrecht, Willemsviaduct|NOTACCESSIBLE|NOTACCESSIBLE
-50190020|Utrecht, Koningsweg 175|NOTACCESSIBLE|NOTACCESSIBLE
-51220680|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
-50000700|Utrecht, Sartreweg|NOTACCESSIBLE|NOTACCESSIBLE
-50190110|Utrecht, Ln v Maarschalkerwd|NOTACCESSIBLE|NOTACCESSIBLE
-59150330|Utrecht, Muyskenweg|NOTACCESSIBLE|NOTACCESSIBLE
-51110780|De Meern, Proost en Brandt|NOTACCESSIBLE|NOTACCESSIBLE
-59200020|Hollandsche Rading, Vuurse Dreef|NOTACCESSIBLE|NOTACCESSIBLE
-59100030|Maartensdijk, Nieuwe-Wetering|NOTACCESSIBLE|NOTACCESSIBLE
-51220252|Nieuwegein, Koetsdrift|NOTACCESSIBLE|NOTACCESSIBLE
-59150300|Utrecht, Sweder van Zuylenweg|NOTACCESSIBLE|NOTACCESSIBLE
-59330030|Kockengen, Portengen|NOTACCESSIBLE|NOTACCESSIBLE
-59152080|Utrecht, Brailledreef|NOTACCESSIBLE|NOTACCESSIBLE
-50200450|Zeist, Brugakker|NOTACCESSIBLE|NOTACCESSIBLE
-59330120|Kockengen, Roerdomp|NOTACCESSIBLE|NOTACCESSIBLE
-51340390|Vianen, Verz C. Batenstein|NOTACCESSIBLE|NOTACCESSIBLE
-50002060|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
-50001090|Utrecht, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
-51340040|Vianen, Clarissenhof|NOTACCESSIBLE|NOTACCESSIBLE
-50007520|Utrecht, Pieter Breughelstraat|NOTACCESSIBLE|NOTACCESSIBLE
-59330130|Kockengen, Roerdomp|NOTACCESSIBLE|NOTACCESSIBLE
-51220321|Nieuwegein, Martinbaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000160|Utrecht, Vredenburgviaduct|NOTACCESSIBLE|NOTACCESSIBLE
-59151360|Utrecht, Donaudreef|NOTACCESSIBLE|NOTACCESSIBLE
-59140200|Utrecht, Niels Bohrweg|NOTACCESSIBLE|NOTACCESSIBLE
-50001210|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-51111080|Nieuwegein, Huis de Geer|NOTACCESSIBLE|NOTACCESSIBLE
-59151840|Utrecht, Hudsondreef|NOTACCESSIBLE|NOTACCESSIBLE
-51220152|Nieuwegein, Middenweide|NOTACCESSIBLE|NOTACCESSIBLE
-50007180|Utrecht, Jan Pietersz. Coenstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50190040|Bunnik,  Oud Amelisweerd|NOTACCESSIBLE|NOTACCESSIBLE
-50310060|Austerlitz, Oude Postweg|NOTACCESSIBLE|NOTACCESSIBLE
-59230050|Haarzuilens, Kasteel|NOTACCESSIBLE|NOTACCESSIBLE
-50310070|Austerlitz, Oude Postweg|NOTACCESSIBLE|NOTACCESSIBLE
-50200350|Zeist, De Oldenborgh|NOTACCESSIBLE|NOTACCESSIBLE
-50390210|Odijk, Jodichemdreef|NOTACCESSIBLE|NOTACCESSIBLE
-50390040|Odijk, De Vork|NOTACCESSIBLE|NOTACCESSIBLE
-50490120|Werkhoven, Hardenbroek|NOTACCESSIBLE|NOTACCESSIBLE
-51200300|Vleuten, Vrijthof|NOTACCESSIBLE|NOTACCESSIBLE
-59151170|Utrecht, Niftarlakeplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-59390010|Huis ter Heide, Prins Alexanderweg|NOTACCESSIBLE|NOTACCESSIBLE
-50008060|Utrecht, Churchilllaan|NOTACCESSIBLE|NOTACCESSIBLE
-59150630|Utrecht, Pionstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50200470|Zeist, De Sluis|NOTACCESSIBLE|NOTACCESSIBLE
-50310080|Austerlitz, Dorpsplein|NOTACCESSIBLE|NOTACCESSIBLE
-51220060|Nieuwegein, Zorgcentrum Zuilenstein|NOTACCESSIBLE|NOTACCESSIBLE
-50001180|Utrecht, Bosboomstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51220032|Nieuwegein, Postkantoor|NOTACCESSIBLE|NOTACCESSIBLE
-50390190|Odijk, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
-50201490|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100390|Utrecht, Archimedeslaan|NOTACCESSIBLE|NOTACCESSIBLE
-59250711|Maarssen, Ranstplein|NOTACCESSIBLE|NOTACCESSIBLE
-51340501|Vianen, K. Onnesweg|NOTACCESSIBLE|NOTACCESSIBLE
-59390030|Huis ter Heide, Frans van Mierislaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220040|Nieuwegein, Wenckebachplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
-50200550|Zeist, Couwenhoven|NOTACCESSIBLE|NOTACCESSIBLE
-50320060|Huis ter Heide, RK Kerk|NOTACCESSIBLE|NOTACCESSIBLE
-50000790|Utrecht, Hasebroekstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51225070|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-51110040|De Meern, Strijkviertel|NOTACCESSIBLE|NOTACCESSIBLE
-50006290|Utrecht, Jaarbeursplein|NOTACCESSIBLE|NOTACCESSIBLE
-51221100|Nieuwegein, Marconi|NOTACCESSIBLE|NOTACCESSIBLE
-59140240|Utrecht, Computerweg|NOTACCESSIBLE|NOTACCESSIBLE
-59151940|Utrecht, Orinocodreef|NOTACCESSIBLE|NOTACCESSIBLE
-50105510|Bilthoven,  RIVM|NOTACCESSIBLE|NOTACCESSIBLE
-50201210|Zeist, Alg. Begraafplaats|NOTACCESSIBLE|NOTACCESSIBLE
-50001500|Utrecht, David van Mollemstraat|NOTACCESSIBLE|NOTACCESSIBLE
-50390090|Odijk, N229-Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
-59330050|Kockengen, Kockengensebrug|NOTACCESSIBLE|NOTACCESSIBLE
-59230080|Haarzuilens, De Bom|NOTACCESSIBLE|NOTACCESSIBLE
-50002530|Utrecht, Overste den Oudenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-59100060|Groenekan, Buitenlust|NOTACCESSIBLE|NOTACCESSIBLE
-59252007|Maarssenbroek, Spechten-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
-51380370|Schalkwijk, Korte Uitweg|NOTACCESSIBLE|NOTACCESSIBLE
-51340061|Vianen, Rietkamp|NOTACCESSIBLE|NOTACCESSIBLE
-51340110|Vianen, Marienhof|NOTACCESSIBLE|NOTACCESSIBLE
-50200530|Zeist, De Boerderij|NOTACCESSIBLE|NOTACCESSIBLE
-50490070|Werkhoven, Sportpark|NOTACCESSIBLE|NOTACCESSIBLE
-59390130|Den Dolder, Station|NOTACCESSIBLE|NOTACCESSIBLE
-51200160|De Meern, Wiericke|NOTACCESSIBLE|NOTACCESSIBLE
-50201500|Zeist, Griffensteijnselaan|NOTACCESSIBLE|NOTACCESSIBLE
-50201530|Zeist, Griffensteijnselaan|NOTACCESSIBLE|NOTACCESSIBLE
-50100460|Utrecht-De Uithof, Botanische Tuinen|NOTACCESSIBLE|NOTACCESSIBLE
-50100180|De Bilt, Looijdijk|NOTACCESSIBLE|NOTACCESSIBLE
-51380160|Schalkwijk, Rozenhoeve|NOTACCESSIBLE|NOTACCESSIBLE
-50101050|Utrecht, Wim Sonneveldlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50220070|Bilthoven, Bilderdijklaan|NOTACCESSIBLE|NOTACCESSIBLE
-59151830|Utrecht, Hudsondreef|NOTACCESSIBLE|NOTACCESSIBLE
-50100270|Bilthoven, Duivenlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50000290|Utrecht, Eykmanplein|NOTACCESSIBLE|NOTACCESSIBLE
-51221090|Nieuwegein, Marconi|NOTACCESSIBLE|NOTACCESSIBLE
-51220190|Nieuwegein, Antilopeweide|NOTACCESSIBLE|NOTACCESSIBLE
-51220232|Nieuwegein, Barnsteendrift|NOTACCESSIBLE|NOTACCESSIBLE
-50005001|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50201020|Zeist, Nieuw Beerschoten|NOTACCESSIBLE|NOTACCESSIBLE
-50005506|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-50490050|Werkhoven, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
-50490140|Werkhoven, Provincialeweg|NOTACCESSIBLE|NOTACCESSIBLE
-50005416|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
-51285020|Houten, Station|NOTACCESSIBLE|NOTACCESSIBLE
-50006360|Utrecht, Brederoplein|NOTACCESSIBLE|NOTACCESSIBLE
-50006840|Utrecht, Maliebaan|NOTACCESSIBLE|NOTACCESSIBLE
-50202020|Zeist, Soc. Werkvoorz. Zeist|NOTACCESSIBLE|NOTACCESSIBLE
-51220632|Nieuwegein, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
-50002850|Utrecht, Griftstraat|NOTACCESSIBLE|NOTACCESSIBLE
-51340300|Vianen, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
-51220180|Nieuwegein, Antilopeweide|NOTACCESSIBLE|NOTACCESSIBLE
-51220811|Nieuwegein, Randijk|NOTACCESSIBLE|NOTACCESSIBLE
-50100533|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
-50200200|Zeist, J.van Lennepplein|NOTACCESSIBLE|NOTACCESSIBLE
-51220401|Nieuwegein, Galvanibaan|NOTACCESSIBLE|NOTACCESSIBLE
-50002050|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
-51340052|Vianen, Clarissenhof|NOTACCESSIBLE|NOTACCESSIBLE
-51380180|Schalkwijk, Van Gaalen|NOTACCESSIBLE|NOTACCESSIBLE
-50002090|Utrecht, 24 Oktoberplein-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
-59390160|Den Dolder,  Willem Arntszhoeve|NOTACCESSIBLE|NOTACCESSIBLE
-50200860|Zeist, Van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
-51220840|Nieuwegein, IJsselsteinseweg|NOTACCESSIBLE|NOTACCESSIBLE
-59250080|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
-50220455|Bilthoven, Leeuweriklaan|NOTACCESSIBLE|NOTACCESSIBLE
-51280970|Houten, Weteringshoek|NOTACCESSIBLE|NOTACCESSIBLE
-51340460|Vianen, Sportlaan|NOTACCESSIBLE|NOTACCESSIBLE
-50200540|Zeist, De Boerderij|NOTACCESSIBLE|NOTACCESSIBLE
-50100340|De Bilt, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
-095183|Spaklerweg|ACCESSIBLE|UNKNOWN
-51225000|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
-50006140|Utrecht, Mr. Tripkade|NOTACCESSIBLE|NOTACCESSIBLE
-50000450|Utrecht, Concordiastraat|NOTACCESSIBLE|NOTACCESSIBLE
-59250070|Maarssen, Zwembad|NOTACCESSIBLE|NOTACCESSIBLE
+42055302|Wassenaar, Admiral Helfrichlaan|ACCESSIBLE|NOTACCESSIBLE
+42056802|Wassenaar, Papegaaienlaan|ACCESSIBLE|NOTACCESSIBLE
+42061301|Zoetermeer, Gouderakstraat|ACCESSIBLE|NOTACCESSIBLE
+42061701|Zoetermeer, Houtsingel|ACCESSIBLE|NOTACCESSIBLE
+42067702|Den Haag, Prinses Marijkestraat|ACCESSIBLE|NOTACCESSIBLE
+32003602|Loevesteinlaan|ACCESSIBLE|NOTACCESSIBLE
+42015701|Den Haag, Lozerlaan|ACCESSIBLE|NOTACCESSIBLE
+42015702|Den Haag, Lozerlaan|ACCESSIBLE|NOTACCESSIBLE
+54142030|Den Haag, Waalsdorperlaan|ACCESSIBLE|NOTACCESSIBLE
+42064201|Zoetermeer, Regenboogsingel|ACCESSIBLE|NOTACCESSIBLE
+32002724|Station Hollands Spoor|ACCESSIBLE|NOTACCESSIBLE
+32003708|Melis Stokelaan|ACCESSIBLE|NOTACCESSIBLE
+42055602|Wassenaar, Burchtlaan|ACCESSIBLE|NOTACCESSIBLE
+32002926|Jacob Catsstraat|ACCESSIBLE|NOTACCESSIBLE
+32003916|Regulusweg|ACCESSIBLE|NOTACCESSIBLE
+42017801|Den Haag, Parnassia|ACCESSIBLE|NOTACCESSIBLE
+32003327|De Dreef|ACCESSIBLE|NOTACCESSIBLE
+32003339|Lozerlaan|ACCESSIBLE|NOTACCESSIBLE
+42056202|Wassenaar, de Kieviet|ACCESSIBLE|NOTACCESSIBLE
+32001913|Thorbeckelaan|ACCESSIBLE|NOTACCESSIBLE
+32003211|Castricumplein|ACCESSIBLE|NOTACCESSIBLE
+42000602|Den Hoorn, RK Kerk|ACCESSIBLE|NOTACCESSIBLE
+42024602|Honselersdijk, Strijplaan|ACCESSIBLE|NOTACCESSIBLE
+42035001|Maasland, Viaduct|ACCESSIBLE|NOTACCESSIBLE
+42067001|Delfgauw, Hoefsmidstraat|ACCESSIBLE|NOTACCESSIBLE
+074203|Van Boshuizenstraat|ACCESSIBLE|UNKNOWN
+42004201|Delft, Brahmslaan|ACCESSIBLE|ACCESSIBLE
+42017501|Den Haag, Ockenrode|ACCESSIBLE|ACCESSIBLE
+42007802|Delft, Zuidpoort|ACCESSIBLE|NOTACCESSIBLE
+50003320|Utrecht, Juliusstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000402|Bronovo Ziekenhuis|NOTACCESSIBLE|NOTACCESSIBLE
+32002908|Delftselaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000201|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
+32000214|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
+32000312|Plesmanweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000735|Rusthoekstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001915|Perenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001872|Westduin|NOTACCESSIBLE|NOTACCESSIBLE
+32000218|Harstenhoekplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000204|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
+32000604|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
+32002508|Saffierhorst|NOTACCESSIBLE|NOTACCESSIBLE
+32005212|Paulus Potterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42000201|Den Hoorn, Hof van Delftstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42000301|Schipluiden, Manege|NOTACCESSIBLE|NOTACCESSIBLE
+42003902|Delft, Krakeelpolderweg|NOTACCESSIBLE|NOTACCESSIBLE
+42005308|Delft, Station Delft|NOTACCESSIBLE|NOTACCESSIBLE
+51380090|Schalkwijk, Spoorlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51280940|Houten, De Muren|NOTACCESSIBLE|NOTACCESSIBLE
+51380290|'t Goy, Wickenburghseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000980|Utrecht, Anne Frankplein|NOTACCESSIBLE|NOTACCESSIBLE
+59151380|Utrecht, Berezinadreef|ACCESSIBLE|ACCESSIBLE
+50002370|Utrecht, Karperstraat|ACCESSIBLE|ACCESSIBLE
+50006830|Utrecht, Maliebaan|NOTACCESSIBLE|ACCESSIBLE
+50000320|Utrecht, Kleine Singel|NOTACCESSIBLE|ACCESSIBLE
+50200110|Zeist, De Dreef/Panweg|NOTACCESSIBLE|ACCESSIBLE
+59230030|Haarzuilens, Joostenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51200500|Vleuten, Station|NOTACCESSIBLE|NOTACCESSIBLE
+50005000|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50001270|Utrecht, Socrateslaan|NOTACCESSIBLE|ACCESSIBLE
+59330110|Kockengen, Dreef|NOTACCESSIBLE|NOTACCESSIBLE
+50001690|Utrecht, Kemal Ataturkstraat|NOTACCESSIBLE|ACCESSIBLE
+50001150|Utrecht, Diakonessenhuis|NOTACCESSIBLE|ACCESSIBLE
+50006730|Utrecht, Tolsteegbrug|NOTACCESSIBLE|ACCESSIBLE
+50006452|Utrecht, Linschotensingel|NOTACCESSIBLE|ACCESSIBLE
+50001282|Utrecht, Socrateslaan|NOTACCESSIBLE|ACCESSIBLE
+50006870|Utrecht, Oudwijkerdwarsstraat|NOTACCESSIBLE|ACCESSIBLE
+50000240|Utrecht, Winklerlaan|NOTACCESSIBLE|ACCESSIBLE
+50200891|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|ACCESSIBLE
+50007420|Utrecht, Prinsesselaan|NOTACCESSIBLE|ACCESSIBLE
+59151330|Utrecht, Atlasdreef|ACCESSIBLE|ACCESSIBLE
+59150770|Utrecht, Nijldreef|ACCESSIBLE|ACCESSIBLE
+50100540|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
+59150620|Utrecht, Pionstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50001330|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
+51280690|Houten, Oude Drop|ACCESSIBLE|ACCESSIBLE
+50100560|Utrecht-De Uithof, WKZ|ACCESSIBLE|NOTACCESSIBLE
+50007080|Utrecht, Nijverheidsweg|ACCESSIBLE|NOTACCESSIBLE
+50200570|Zeist, Godfried van Seystln|ACCESSIBLE|NOTACCESSIBLE
+59250610|Maarssenbroek, Antilopespoor|ACCESSIBLE|NOTACCESSIBLE
+51200010|De Meern, Europaweg|ACCESSIBLE|NOTACCESSIBLE
+50008080|Utrecht, Beethovenlaan|ACCESSIBLE|NOTACCESSIBLE
+51111280|De Meern, De Balije|ACCESSIBLE|NOTACCESSIBLE
+51110100|De Meern, Meernbrug|ACCESSIBLE|NOTACCESSIBLE
+59390150|Den Dolder, Pleineslaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200180|Maartensdijk, Koningin Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000841|Utrecht, Majellapark|ACCESSIBLE|NOTACCESSIBLE
+51200122|De Meern, Veldhuizen|ACCESSIBLE|NOTACCESSIBLE
+59250840|Maarssenbroek, Het Kwadrant|ACCESSIBLE|NOTACCESSIBLE
+51200140|De Meern, Europaweg|ACCESSIBLE|NOTACCESSIBLE
+59250170|Maarssen, Kaatsbaan|ACCESSIBLE|NOTACCESSIBLE
+51200120|De Meern, Veldhuizen|ACCESSIBLE|NOTACCESSIBLE
+50100410|Utrecht, Rijnsweerd Noord|ACCESSIBLE|NOTACCESSIBLE
+59250820|Maarssenbroek, Antilopespoor|ACCESSIBLE|NOTACCESSIBLE
+51110110|De Meern, Meernbrug|ACCESSIBLE|NOTACCESSIBLE
+50000050|Utrecht, 24 Oktoberplein|ACCESSIBLE|NOTACCESSIBLE
+50005210|Utrecht, Beethovenlaan|ACCESSIBLE|NOTACCESSIBLE
+59150280|Utrecht, Carnegiedreef|ACCESSIBLE|ACCESSIBLE
+59150011|Maarssen, Rekreatieoord|ACCESSIBLE|NOTACCESSIBLE
+59250160|Maarssen, Kaatsbaan|ACCESSIBLE|NOTACCESSIBLE
+51280500|Houten, Koedijk|ACCESSIBLE|ACCESSIBLE
+59150070|Utrecht, Oud Zuilen|ACCESSIBLE|ACCESSIBLE
+51200320|Vleuten, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100680|Bilthoven,  RIVM|NOTACCESSIBLE|NOTACCESSIBLE
+59140091|Utrecht, Mesonweg|NOTACCESSIBLE|NOTACCESSIBLE
+51110520|De Meern, Zuiderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
+50001010|Utrecht, Sterrenwijk|NOTACCESSIBLE|NOTACCESSIBLE
+51220950|Nieuwegein, Berkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50200700|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50002230|Utrecht, Nicolaas Beetsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59140041|Utrecht, Thoriumweg|NOTACCESSIBLE|NOTACCESSIBLE
+51320062|IJsselstein, Mandenmaker|NOTACCESSIBLE|NOTACCESSIBLE
+50310110|Austerlitz, Waterlooweg|NOTACCESSIBLE|NOTACCESSIBLE
+50001840|Utrecht, Willem van Noortstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220132|Nieuwegein, De Kempenaerpark|NOTACCESSIBLE|NOTACCESSIBLE
+51380340|Houten, Poeldijk|NOTACCESSIBLE|NOTACCESSIBLE
+50001450|Utrecht, Sint Jacobsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50005505|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51280580|Houten, Molenzoom|ACCESSIBLE|ACCESSIBLE
+022943|Station Sloterdijk|ACCESSIBLE|UNKNOWN
+51180060|Nieuwegein, Ravenswade|NOTACCESSIBLE|NOTACCESSIBLE
+59151750|Utrecht, J.M.de Muinck Keizerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50001411|Utrecht, Vondellaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200060|Hollandsche Rading, Plantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+51221000|Nieuwegein, Waterbies|NOTACCESSIBLE|NOTACCESSIBLE
+50220185|Bilthoven, Kwikstaartlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220160|Nieuwegein, Landmansweide|NOTACCESSIBLE|NOTACCESSIBLE
+50000970|Utrecht, Anne Frankplein|NOTACCESSIBLE|NOTACCESSIBLE
+50201080|Zeist, Verzetslaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220760|Nieuwegein, Constructieweg|NOTACCESSIBLE|NOTACCESSIBLE
+51380150|Schalkwijk, Van Gaalen|NOTACCESSIBLE|NOTACCESSIBLE
+51200230|Vleuten, Bottensteinweg|NOTACCESSIBLE|NOTACCESSIBLE
+50190060|Bunnik, Rhijnauwenselaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200770|Zeist, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
+50002110|Utrecht, 5 Mei Plein|NOTACCESSIBLE|NOTACCESSIBLE
+51220360|Nieuwegein, Blauwe Brug|NOTACCESSIBLE|NOTACCESSIBLE
+50001480|Utrecht, Oudenoord|NOTACCESSIBLE|NOTACCESSIBLE
+50000441|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
+50001430|Utrecht, Rozenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59230110|Haarzuilens, Gieltjesdorp|NOTACCESSIBLE|NOTACCESSIBLE
+50490130|Werkhoven, Provincialeweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220791|Nieuwegein, Rembrandthage|NOTACCESSIBLE|NOTACCESSIBLE
+50201070|Zeist, Handelscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+51200360|Vleuten, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50490060|Werkhoven, Sportpark|NOTACCESSIBLE|NOTACCESSIBLE
+59390080|Den Dolder, Hertenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51221010|Nieuwegein, Raalterveste|NOTACCESSIBLE|NOTACCESSIBLE
+50310020|Austerlitz, KNVB-Sportcentrum|NOTACCESSIBLE|NOTACCESSIBLE
+59150480|Utrecht, De Bazelstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50200920|Zeist, Griftlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50003310|Utrecht, Juliusstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59330100|Kockengen, Dreef|NOTACCESSIBLE|NOTACCESSIBLE
+50001232|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
+50002260|Utrecht, Hoogh Boulandt|NOTACCESSIBLE|NOTACCESSIBLE
+50005510|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+59250850|Maarssenbroek, Het Kwadrant|ACCESSIBLE|NOTACCESSIBLE
+59151850|Utrecht, Arizonadreef|NOTACCESSIBLE|NOTACCESSIBLE
+50007040|Utrecht, Vlampijpstraat|NOTACCESSIBLE|NOTACCESSIBLE
+095243|Bullewijk|ACCESSIBLE|UNKNOWN
+59140100|Utrecht, Mesonweg|NOTACCESSIBLE|NOTACCESSIBLE
+59151320|Utrecht, Oderdreef|NOTACCESSIBLE|ACCESSIBLE
+50200140|Zeist, Nepveulaan|NOTACCESSIBLE|NOTACCESSIBLE
+50003130|Utrecht, De Koppel|NOTACCESSIBLE|NOTACCESSIBLE
+50000430|Utrecht, Viaduct|NOTACCESSIBLE|NOTACCESSIBLE
+32008104|Centrum-West|NOTACCESSIBLE|ACCESSIBLE
+32002501|Overbosch|ACCESSIBLE|ACCESSIBLE
+42019701|Den Haag, De Uithof|NOTACCESSIBLE|NOTACCESSIBLE
+42019801|Den Haag, Veenweg|NOTACCESSIBLE|NOTACCESSIBLE
+42019802|Den Haag, Veenweg|NOTACCESSIBLE|NOTACCESSIBLE
+42019901|Den Haag, Veluweplein|NOTACCESSIBLE|NOTACCESSIBLE
+42019902|Den Haag, Veluweplein|NOTACCESSIBLE|NOTACCESSIBLE
+42020001|Den Haag, van Essendijk|NOTACCESSIBLE|NOTACCESSIBLE
+42020002|Den Haag, van Essendijk|NOTACCESSIBLE|NOTACCESSIBLE
+42020301|Den Haag, Wellant College Madestein|NOTACCESSIBLE|NOTACCESSIBLE
+42020302|Den Haag, Wellant College Madestein|NOTACCESSIBLE|NOTACCESSIBLE
+51280650|Houten, De Meren|ACCESSIBLE|ACCESSIBLE
+50000420|Utrecht, Herenweg|NOTACCESSIBLE|NOTACCESSIBLE
+50006890|Utrecht, Oosterstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51280960|Houten, Weteringshoek|NOTACCESSIBLE|NOTACCESSIBLE
+59100080|Groenekan, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+51220011|Nieuwegein, Sporttunnel|NOTACCESSIBLE|NOTACCESSIBLE
+51221040|Nieuwegein, Fokkesteeg|NOTACCESSIBLE|NOTACCESSIBLE
+50220040|Bilthoven, Station|NOTACCESSIBLE|NOTACCESSIBLE
+50310140|Austerlitz, De Pyramid|NOTACCESSIBLE|NOTACCESSIBLE
+50005508|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51111250|Utrecht, Utrechtseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50390060|Odijk, Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
+59250650|Utrecht, Computerweg|NOTACCESSIBLE|NOTACCESSIBLE
+50006390|Utrecht, Waalstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50005516|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50390140|Odijk, Eikelaar|NOTACCESSIBLE|NOTACCESSIBLE
+50201310|Zeist, Kritzingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200421|Zeist, Kromme-Rijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250360|Maarssenbroek, Bloem-Boomstede|NOTACCESSIBLE|NOTACCESSIBLE
+50002400|Utrecht, Kastelenplantsoen|ACCESSIBLE|ACCESSIBLE
+59250480|Maarssenbroek, Kamelenspoor|NOTACCESSIBLE|NOTACCESSIBLE
+50200560|Zeist, Couwenhoven|NOTACCESSIBLE|NOTACCESSIBLE
+59140051|Utrecht, Kernweg|NOTACCESSIBLE|NOTACCESSIBLE
+51110230|Vleuten, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000540|Utrecht, Nijenoord|NOTACCESSIBLE|NOTACCESSIBLE
+51340551|Vianen, Marconiweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220872|Nieuwegein, Doorslag|NOTACCESSIBLE|NOTACCESSIBLE
+51220541|Nieuwegein, De Bongenaar|NOTACCESSIBLE|NOTACCESSIBLE
+50002150|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+51220711|Nieuwegein, Graaf Florisweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220851|Nieuwegein, IJsselsteinseweg|NOTACCESSIBLE|NOTACCESSIBLE
+51380060|Schalkwijk, Jhr. Ramweg|NOTACCESSIBLE|NOTACCESSIBLE
+59200120|Maartensdijk, Groenhorst|ACCESSIBLE|ACCESSIBLE
+51111160|Utrecht, Klifrakplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+59152000|Utrecht, Paranadreef|NOTACCESSIBLE|NOTACCESSIBLE
+51220012|Nieuwegein, Galvanibaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340070|Vianen, Rietkamp|NOTACCESSIBLE|NOTACCESSIBLE
+50291010|Bunnik, Station|NOTACCESSIBLE|NOTACCESSIBLE
+50002140|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50190070|Bunnik, Rhijnauwenselaan|NOTACCESSIBLE|NOTACCESSIBLE
+50390160|Odijk, Gaspeldoorn|NOTACCESSIBLE|NOTACCESSIBLE
+59390110|Huis ter Heide, Van Ostadelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220240|Nieuwegein, Koetsdrift|NOTACCESSIBLE|NOTACCESSIBLE
+59250240|Maarssen, Station/Bisonspoor|NOTACCESSIBLE|NOTACCESSIBLE
+50200520|Zeist, Nijenheim|NOTACCESSIBLE|NOTACCESSIBLE
+50100150|De Bilt, Hessenweg|ACCESSIBLE|ACCESSIBLE
+50220050|Bilthoven, Station|NOTACCESSIBLE|NOTACCESSIBLE
+59250180|Maarssen, Thorbeckelaan|NOTACCESSIBLE|NOTACCESSIBLE
+50001050|Utrecht, Stadionlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50201230|Zeist, Grote Koppel|NOTACCESSIBLE|NOTACCESSIBLE
+50000310|Utrecht, Kleine Singel|NOTACCESSIBLE|ACCESSIBLE
+50007200|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003412|Zweeloostraat|ACCESSIBLE|ACCESSIBLE
+32002858|Nieuwe Haven|NOTACCESSIBLE|NOTACCESSIBLE
+42011801|Den Haag, Eendenplein|NOTACCESSIBLE|NOTACCESSIBLE
+42019702|Den Haag, De Uithof|NOTACCESSIBLE|NOTACCESSIBLE
+32001917|Laan van Eik en Duinen|NOTACCESSIBLE|NOTACCESSIBLE
+32005102|Herenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42005304|Delft, Station Delft (Perron F)|NOTACCESSIBLE|NOTACCESSIBLE
+42012701|Den Haag, Guntersteinweg|NOTACCESSIBLE|NOTACCESSIBLE
+42059701|Zoetermeer, Centrum West (Perron A)|NOTACCESSIBLE|NOTACCESSIBLE
+022953|Station Sloterdijk|ACCESSIBLE|UNKNOWN
+022963|Isolatorweg|ACCESSIBLE|UNKNOWN
+022973|Isolatorweg|ACCESSIBLE|UNKNOWN
+032023|Jan v.Galenstraat|ACCESSIBLE|UNKNOWN
+032033|Jan v.Galenstraat|ACCESSIBLE|UNKNOWN
+032043|Burg.de Vlugtlaan|ACCESSIBLE|UNKNOWN
+032053|Burg.de Vlugtlaan|ACCESSIBLE|UNKNOWN
+043183|Henk Sneevlietweg|ACCESSIBLE|UNKNOWN
+043193|Henk Sneevlietweg|ACCESSIBLE|UNKNOWN
+043203|Heemstedestraat|ACCESSIBLE|UNKNOWN
+043213|Heemstedestraat|ACCESSIBLE|UNKNOWN
+043223|Station Lelylaan|ACCESSIBLE|UNKNOWN
+043233|Station Lelylaan|ACCESSIBLE|UNKNOWN
+043243|Postjesweg|ACCESSIBLE|UNKNOWN
+043253|Postjesweg|ACCESSIBLE|UNKNOWN
+071922|Station Zuid|ACCESSIBLE|UNKNOWN
+073423|Amstelveenseweg|ACCESSIBLE|UNKNOWN
+073433|Amstelveenseweg|ACCESSIBLE|UNKNOWN
+074003|Overamstel|ACCESSIBLE|UNKNOWN
+074013|Overamstel|ACCESSIBLE|UNKNOWN
+074043|Station RAI|ACCESSIBLE|UNKNOWN
+074053|Station RAI|ACCESSIBLE|UNKNOWN
+074083|Station Zuid|ACCESSIBLE|UNKNOWN
+074093|Station Zuid|ACCESSIBLE|UNKNOWN
+074123|De Boelelaan/VU|ACCESSIBLE|UNKNOWN
+074133|De Boelelaan/VU|ACCESSIBLE|UNKNOWN
+074163|A.J. Ernststraat|ACCESSIBLE|UNKNOWN
+074173|A.J. Ernststraat|ACCESSIBLE|UNKNOWN
+074213|Van Boshuizenstraat|ACCESSIBLE|UNKNOWN
+074243|Uilenstede|ACCESSIBLE|UNKNOWN
+074253|Uilenstede|ACCESSIBLE|UNKNOWN
+074283|Kronenburg|ACCESSIBLE|UNKNOWN
+074293|Kronenburg|ACCESSIBLE|UNKNOWN
+074323|Zonnestein|ACCESSIBLE|UNKNOWN
+074333|Zonnestein|ACCESSIBLE|UNKNOWN
+074363|Onderuit|ACCESSIBLE|UNKNOWN
+074373|Onderuit|ACCESSIBLE|UNKNOWN
+074403|Oranjebaan|ACCESSIBLE|UNKNOWN
+074413|Oranjebaan|ACCESSIBLE|UNKNOWN
+074503|Amstelveen Centrum|ACCESSIBLE|UNKNOWN
+074513|Amstelveen Centrum|ACCESSIBLE|UNKNOWN
+074543|Ouderkerkerlaan|ACCESSIBLE|UNKNOWN
+074553|Ouderkerkerlaan|ACCESSIBLE|UNKNOWN
+074583|Sportlaan|ACCESSIBLE|UNKNOWN
+074593|Sportlaan|ACCESSIBLE|UNKNOWN
+074623|Marne|ACCESSIBLE|UNKNOWN
+074633|Marne|ACCESSIBLE|UNKNOWN
+074663|Gondel|ACCESSIBLE|UNKNOWN
+074673|Gondel|ACCESSIBLE|UNKNOWN
+074703|Meent|ACCESSIBLE|UNKNOWN
+074713|Meent|ACCESSIBLE|UNKNOWN
+074743|Brink|ACCESSIBLE|UNKNOWN
+074753|Brink|ACCESSIBLE|UNKNOWN
+074783|Poortwachter|ACCESSIBLE|UNKNOWN
+074793|Poortwachter|ACCESSIBLE|UNKNOWN
+074963|Spinnerij|ACCESSIBLE|UNKNOWN
+074973|Spinnerij|ACCESSIBLE|UNKNOWN
+074983|Sacharovlaan|ACCESSIBLE|UNKNOWN
+074993|Sacharovlaan|ACCESSIBLE|UNKNOWN
+075003|Westwijk|ACCESSIBLE|UNKNOWN
+075013|Westwijk|ACCESSIBLE|UNKNOWN
+095003|Centraal Station|ACCESSIBLE|UNKNOWN
+095023|Nieuwmarkt|ACCESSIBLE|UNKNOWN
+095033|Nieuwmarkt|ACCESSIBLE|UNKNOWN
+095083|Waterlooplein|ACCESSIBLE|UNKNOWN
+095093|Waterlooplein|ACCESSIBLE|UNKNOWN
+095103|Weesperplein|ACCESSIBLE|UNKNOWN
+095113|Weesperplein|ACCESSIBLE|UNKNOWN
+095123|Wibautstraat|ACCESSIBLE|UNKNOWN
+095133|Wibautstraat|ACCESSIBLE|UNKNOWN
+095143|Amstelstation|ACCESSIBLE|UNKNOWN
+095153|Amstelstation|ACCESSIBLE|UNKNOWN
+095163|Van der Madeweg|ACCESSIBLE|UNKNOWN
+095173|Van der Madeweg|ACCESSIBLE|UNKNOWN
+095193|Spaklerweg|ACCESSIBLE|UNKNOWN
+095203|Strandvliet|ACCESSIBLE|UNKNOWN
+095213|Strandvliet|ACCESSIBLE|UNKNOWN
+095223|Station Bijlmer ArenA|ACCESSIBLE|UNKNOWN
+095233|Station Bijlmer ArenA|ACCESSIBLE|UNKNOWN
+095253|Bullewijk|ACCESSIBLE|UNKNOWN
+095263|Station Holendrecht |ACCESSIBLE|UNKNOWN
+095273|Station Holendrecht |ACCESSIBLE|UNKNOWN
+095283|Reigersbos|ACCESSIBLE|UNKNOWN
+095293|Reigersbos|ACCESSIBLE|UNKNOWN
+095303|Gein|ACCESSIBLE|UNKNOWN
+095313|Gein|ACCESSIBLE|UNKNOWN
+095403|Venserpolder|ACCESSIBLE|UNKNOWN
+095413|Venserpolder|ACCESSIBLE|UNKNOWN
+095423|Station Diemen-Zuid|ACCESSIBLE|UNKNOWN
+095433|Station Diemen-Zuid|ACCESSIBLE|UNKNOWN
+095443|Verrijn Stuartweg|ACCESSIBLE|UNKNOWN
+095453|Verrijn Stuartweg|ACCESSIBLE|UNKNOWN
+095463|Station Ganzenhoef|ACCESSIBLE|UNKNOWN
+095473|Station Ganzenhoef|ACCESSIBLE|UNKNOWN
+095483|Kraaienneststation|ACCESSIBLE|UNKNOWN
+095493|Kraaienneststation|ACCESSIBLE|UNKNOWN
+095503|Gaasperplas|ACCESSIBLE|UNKNOWN
+095513|Station Duivendrecht|ACCESSIBLE|UNKNOWN
+095523|Station Duivendrecht|ACCESSIBLE|UNKNOWN
+095553|Gaasperplas|ACCESSIBLE|UNKNOWN
+095623|Station Zuid|ACCESSIBLE|UNKNOWN
+095633|Overamstel|ACCESSIBLE|UNKNOWN
+095643|Van der Madeweg|ACCESSIBLE|UNKNOWN
+095653|Van der Madeweg|ACCESSIBLE|UNKNOWN
+095663|Spaklerweg|ACCESSIBLE|UNKNOWN
+095673|Spaklerweg|ACCESSIBLE|UNKNOWN
+2903|Monstersestraat|ACCESSIBLE|UNKNOWN
+2904|Monstersestraat|ACCESSIBLE|UNKNOWN
+3003|De La Reyweg|ACCESSIBLE|UNKNOWN
+3004|De La Reyweg|ACCESSIBLE|UNKNOWN
+32001601|Kraayensteinlaan|ACCESSIBLE|UNKNOWN
+32001602|Kraayensteinlaan|ACCESSIBLE|UNKNOWN
+32001711|Kapelaan Meereboerweg|ACCESSIBLE|UNKNOWN
+32001712|Kapelaan Meereboerweg|ACCESSIBLE|UNKNOWN
+32001810|Buitentuinen|ACCESSIBLE|UNKNOWN
+32001811|Buitentuinen|ACCESSIBLE|UNKNOWN
+32001919|Walnootstraat|ACCESSIBLE|UNKNOWN
+32001920|Walnootstraat|ACCESSIBLE|UNKNOWN
+32001921|Thorbeckelaan|ACCESSIBLE|UNKNOWN
+32001922|Thorbeckelaan|ACCESSIBLE|UNKNOWN
+32002606|Centraal Station|ACCESSIBLE|UNKNOWN
+32002607|Centraal Station|ACCESSIBLE|UNKNOWN
+32002820|MCH Westeinde|ACCESSIBLE|UNKNOWN
+32002822|MCH Westeinde|ACCESSIBLE|UNKNOWN
+32002824|Brouwersgracht|ACCESSIBLE|UNKNOWN
+32003101|Kamperfoeliestraat|ACCESSIBLE|UNKNOWN
+32003102|Kamperfoeliestraat|ACCESSIBLE|UNKNOWN
+32003103|Valkenboslaan|ACCESSIBLE|UNKNOWN
+32003104|Valkenboslaan|ACCESSIBLE|UNKNOWN
+32003107|Fahrenheitstraat|ACCESSIBLE|UNKNOWN
+32003108|Fahrenheitstraat|ACCESSIBLE|UNKNOWN
+32003203|Nieuwendamlaan|ACCESSIBLE|UNKNOWN
+32003204|Nieuwendamlaan|ACCESSIBLE|UNKNOWN
+32003205|Laan van Eik en Duinen|ACCESSIBLE|UNKNOWN
+32007601|Voorburg 't Loo|ACCESSIBLE|UNKNOWN
+32007602|Voorburg 't Loo|ACCESSIBLE|UNKNOWN
+32007603|Prinses Beatrixlaan|ACCESSIBLE|UNKNOWN
+32007604|Prinses Beatrixlaan|ACCESSIBLE|UNKNOWN
+32007703|Essesteijn|ACCESSIBLE|UNKNOWN
+32007704|Essesteijn|ACCESSIBLE|UNKNOWN
+32007705|Elzendreef|ACCESSIBLE|UNKNOWN
+32007706|Elzendreef|ACCESSIBLE|UNKNOWN
+32009501|Leidsenhage|ACCESSIBLE|UNKNOWN
+32009502|Leidsenhage|ACCESSIBLE|UNKNOWN
+32009503|Burgemeester Kolfschotenlaan|ACCESSIBLE|UNKNOWN
+32009506|Kastelenring|ACCESSIBLE|UNKNOWN
+42002801|Delft, Fuutlaan|ACCESSIBLE|ACCESSIBLE
+49000101|Lelystad, Lelycentre|ACCESSIBLE|UNKNOWN
+57142235|Amsterdam, Station Zuid|ACCESSIBLE|UNKNOWN
+57142260|Amsterdam, De Boelelaan/VU|ACCESSIBLE|UNKNOWN
+1707|Loosduinse Hoofdstraat|NOTACCESSIBLE|UNKNOWN
+1708|Loosduinse Hoofdstraat|NOTACCESSIBLE|UNKNOWN
+32001709|Burgemeester Hovylaan|NOTACCESSIBLE|UNKNOWN
+32001710|Burgemeester Hovylaan|NOTACCESSIBLE|UNKNOWN
+32002647|Oostinje|NOTACCESSIBLE|UNKNOWN
+32002648|Oostinje|NOTACCESSIBLE|UNKNOWN
+32003206|Laan van Eik en Duinen|NOTACCESSIBLE|UNKNOWN
+32009504|Burgemeester Kolfschotenlaan|NOTACCESSIBLE|UNKNOWN
+32009505|Kastelenring|NOTACCESSIBLE|UNKNOWN
+32009507|Dillenburgsingel|NOTACCESSIBLE|UNKNOWN
+32009508|Dillenburgsingel|NOTACCESSIBLE|UNKNOWN
+32007611|Voorburg 't Loo|NOTACCESSIBLE|ACCESSIBLE
+42044902|Rijswijk, 't Haantje|NOTACCESSIBLE|NOTACCESSIBLE
+32000228|Pompstationsweg|NOTACCESSIBLE|ACCESSIBLE
+32000309|Maurits de Brauwweg|ACCESSIBLE|ACCESSIBLE
+32000404|Bronovo Ziekenhuis|ACCESSIBLE|ACCESSIBLE
+32000406|Waalsdorperweg|ACCESSIBLE|ACCESSIBLE
+32000409|Theo Mann Bouwmeesterlaan|ACCESSIBLE|ACCESSIBLE
+32000411|Oostduinlaan|ACCESSIBLE|ACCESSIBLE
+32000417|Groenhovenstraat|ACCESSIBLE|ACCESSIBLE
+32000426|Jozef Israëlsplein|ACCESSIBLE|ACCESSIBLE
+32000427|Jozef Israëlsplein|ACCESSIBLE|ACCESSIBLE
+32000432|Van Alkemadelaan|ACCESSIBLE|ACCESSIBLE
+32000433|Van Alkemadelaan|ACCESSIBLE|ACCESSIBLE
+32000436|Weissenbruchstraat|ACCESSIBLE|ACCESSIBLE
+32000440|Breitnerlaan|ACCESSIBLE|ACCESSIBLE
+32000442|Laan van Clingendael|ACCESSIBLE|ACCESSIBLE
+32000447|Wassenaarseweg|ACCESSIBLE|ACCESSIBLE
+32000448|Wassenaarseweg|ACCESSIBLE|ACCESSIBLE
+32000717|Duinstraat|ACCESSIBLE|ACCESSIBLE
+32001103|Cornelis de Wittlaan|ACCESSIBLE|ACCESSIBLE
+32001106|Gemeentemuseum/Museon|ACCESSIBLE|ACCESSIBLE
+32001107|Gemeentemuseum/Museon|ACCESSIBLE|ACCESSIBLE
+32001112|Valeriusstraat|ACCESSIBLE|ACCESSIBLE
+32001113|Valeriusstraat|ACCESSIBLE|ACCESSIBLE
+32001125|Cornelis de Wittlaan|ACCESSIBLE|ACCESSIBLE
+32001201|Kwartellaan|ACCESSIBLE|ACCESSIBLE
+32001202|Kwartellaan|ACCESSIBLE|ACCESSIBLE
+32001203|Nieboerweg|ACCESSIBLE|ACCESSIBLE
+32001207|Haga Ziekenhuis|ACCESSIBLE|ACCESSIBLE
+32001208|Haga Ziekenhuis|ACCESSIBLE|ACCESSIBLE
+32001209|Houtrustweg|ACCESSIBLE|ACCESSIBLE
+32001210|Houtrustweg|ACCESSIBLE|ACCESSIBLE
+32001304|Kruisbeklaan|ACCESSIBLE|ACCESSIBLE
+32001307|Vliegenvangerlaan|ACCESSIBLE|ACCESSIBLE
+32001308|Vliegenvangerlaan|ACCESSIBLE|ACCESSIBLE
+32001403|Muurbloemweg|ACCESSIBLE|ACCESSIBLE
+32001404|Muurbloemweg|ACCESSIBLE|ACCESSIBLE
+32001406|Arabislaan|ACCESSIBLE|ACCESSIBLE
+32001408|de Savornin Lohmanlaan|ACCESSIBLE|ACCESSIBLE
+32001411|Aronskelkweg|ACCESSIBLE|ACCESSIBLE
+32001412|Aronskelkweg|ACCESSIBLE|ACCESSIBLE
+32001417|Lobelialaan|ACCESSIBLE|ACCESSIBLE
+32001418|Lobelialaan|ACCESSIBLE|ACCESSIBLE
+32001423|Hoefbladlaan|ACCESSIBLE|ACCESSIBLE
+32001424|Hoefbladlaan|ACCESSIBLE|ACCESSIBLE
+32001425|Teunisbloemplein|ACCESSIBLE|ACCESSIBLE
+32001429|De Savornin Lohmanplein|ACCESSIBLE|ACCESSIBLE
+32001514|Kijkduinsestraat|ACCESSIBLE|ACCESSIBLE
+32001516|Kijkduinsestraat|ACCESSIBLE|ACCESSIBLE
+32001914|Thorbeckelaan|ACCESSIBLE|ACCESSIBLE
+32002401|Malieveld|ACCESSIBLE|ACCESSIBLE
+32002503|Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
+32002504|Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
+32002506|Barnsteenhorst|ACCESSIBLE|ACCESSIBLE
+32002602|Centraal Station|NOTACCESSIBLE|ACCESSIBLE
+32002603|Centraal Station|NOTACCESSIBLE|ACCESSIBLE
+32002637|Theresiastraat|ACCESSIBLE|ACCESSIBLE
+32002638|Theresiastraat|ACCESSIBLE|ACCESSIBLE
+32002649|Juliana van Stolberglaan|ACCESSIBLE|ACCESSIBLE
+32002703|Huijgenspark|ACCESSIBLE|ACCESSIBLE
+32002825|Brouwersgracht|ACCESSIBLE|ACCESSIBLE
+32002849|Bierkade|ACCESSIBLE|ACCESSIBLE
+32002850|Bierkade|ACCESSIBLE|ACCESSIBLE
+32002880|Spui|ACCESSIBLE|ACCESSIBLE
+32002881|Spui|ACCESSIBLE|ACCESSIBLE
+32002882|Grote Markt|ACCESSIBLE|ACCESSIBLE
+32002883|Grote Markt|ACCESSIBLE|ACCESSIBLE
+32002925|Jacob Catsstraat|ACCESSIBLE|ACCESSIBLE
+32003119|Soestdijkseplein|ACCESSIBLE|ACCESSIBLE
+32003120|Soestdijkseplein|ACCESSIBLE|ACCESSIBLE
+32003121|De La Reyweg|ACCESSIBLE|ACCESSIBLE
+32003122|De La Reyweg|ACCESSIBLE|ACCESSIBLE
+32003129|Dierenselaan|ACCESSIBLE|ACCESSIBLE
+32003212|Castricumplein|ACCESSIBLE|ACCESSIBLE
+32003213|Monnickendamplein|ACCESSIBLE|ACCESSIBLE
+32003214|Monnickendamplein|ACCESSIBLE|ACCESSIBLE
+32003217|Leyenburg|ACCESSIBLE|ACCESSIBLE
+32003309|Bouwlustlaan|ACCESSIBLE|ACCESSIBLE
+32003323|Hertenrade|ACCESSIBLE|ACCESSIBLE
+32003341|Ambachtsweg|ACCESSIBLE|ACCESSIBLE
+32003361|Randveen|ACCESSIBLE|ACCESSIBLE
+32003372|Revalidatiecentrum|ACCESSIBLE|ACCESSIBLE
+32003411|Zweeloostraat|ACCESSIBLE|ACCESSIBLE
+32003831|Ledeganckplein|ACCESSIBLE|ACCESSIBLE
+32005209|Hendrik Ravesteijnplein|ACCESSIBLE|ACCESSIBLE
+32005210|Hendrik Ravesteijnplein|ACCESSIBLE|ACCESSIBLE
+32005301|Van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
+32005302|Van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
+32005303|Generaal Spoorlaan|ACCESSIBLE|ACCESSIBLE
+32005305|Huis te Landelaan|ACCESSIBLE|ACCESSIBLE
+32005306|Huis te Landelaan|ACCESSIBLE|ACCESSIBLE
+32005307|Rijswijkse Schouwburg|ACCESSIBLE|ACCESSIBLE
+32005308|Rijswijkse Schouwburg|ACCESSIBLE|ACCESSIBLE
+32005309|Dr. H. Colijnlaan|ACCESSIBLE|ACCESSIBLE
+32005310|Dr. H. Colijnlaan|ACCESSIBLE|ACCESSIBLE
+32005409|Prinses Beatrixlaan|ACCESSIBLE|ACCESSIBLE
+32005410|Prinses Beatrixlaan|ACCESSIBLE|ACCESSIBLE
+32005411|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
+32005412|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
+32005421|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
+32005422|Rijswijk Station|NOTACCESSIBLE|ACCESSIBLE
+32005501|Sammersweg|ACCESSIBLE|ACCESSIBLE
+32005502|Sammersweg|ACCESSIBLE|ACCESSIBLE
+32005503|De Schilp|ACCESSIBLE|ACCESSIBLE
+32005504|De Schilp|ACCESSIBLE|ACCESSIBLE
+32005510|Minister van den Tempellaan|ACCESSIBLE|ACCESSIBLE
+32005514|Sir Winston Churchilllaan|ACCESSIBLE|ACCESSIBLE
+32005515|Sir Winston Churchilllaan|ACCESSIBLE|ACCESSIBLE
+32005519|Prinses Marijkesingel|ACCESSIBLE|ACCESSIBLE
+32005520|Prinses Marijkesingel|ACCESSIBLE|ACCESSIBLE
+32005601|Wethouder Brederodelaan|ACCESSIBLE|ACCESSIBLE
+32005602|Wethouder Brederodelaan|ACCESSIBLE|ACCESSIBLE
+32005603|Albert Schweitzerlaan|ACCESSIBLE|ACCESSIBLE
+32005604|Albert Schweitzerlaan|ACCESSIBLE|ACCESSIBLE
+32005605|Aletta Jacobsstraat|ACCESSIBLE|ACCESSIBLE
+32005623|Pater Doumenstraat|ACCESSIBLE|ACCESSIBLE
+32005624|Pater Doumenstraat|ACCESSIBLE|ACCESSIBLE
+32005701|Admiral Helfrichsingel|ACCESSIBLE|ACCESSIBLE
+32005702|Admiral Helfrichsingel|ACCESSIBLE|ACCESSIBLE
+32005944|Ypenburg Centrum|ACCESSIBLE|ACCESSIBLE
+32005945|Ypenburg Centrum|ACCESSIBLE|ACCESSIBLE
+32005946|Anthony Fokkersingel|NOTACCESSIBLE|ACCESSIBLE
+32005947|Anthony Fokkersingel|ACCESSIBLE|ACCESSIBLE
+32007211|Leidschendam-Voorburg|ACCESSIBLE|ACCESSIBLE
+32007212|Leidschendam-Voorburg|NOTACCESSIBLE|ACCESSIBLE
+32007507|Spinozalaan|ACCESSIBLE|ACCESSIBLE
+32007508|Spinozalaan|ACCESSIBLE|ACCESSIBLE
+32007509|Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
+32007510|Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
+32007612|Voorburg 't Loo|ACCESSIBLE|ACCESSIBLE
+32008101|Voorweg Laag|NOTACCESSIBLE|ACCESSIBLE
+32008102|Voorweg Laag|NOTACCESSIBLE|ACCESSIBLE
+32008103|Centrum-West|ACCESSIBLE|ACCESSIBLE
+32008106|Stadhuis|NOTACCESSIBLE|ACCESSIBLE
+32008107|Palenstein|ACCESSIBLE|ACCESSIBLE
+32008108|Palenstein|NOTACCESSIBLE|ACCESSIBLE
+32008109|Seghwaert|NOTACCESSIBLE|ACCESSIBLE
+32008110|Seghwaert|ACCESSIBLE|ACCESSIBLE
+32008111|Leidsewallen|ACCESSIBLE|ACCESSIBLE
+32008112|Leidsewallen|NOTACCESSIBLE|ACCESSIBLE
+32008113|De Leyens|NOTACCESSIBLE|ACCESSIBLE
+32008114|De Leyens|ACCESSIBLE|ACCESSIBLE
+32008115|Buytenwegh|ACCESSIBLE|ACCESSIBLE
+32008116|Buytenwegh|ACCESSIBLE|ACCESSIBLE
+32008117|Voorweg Hoog|ACCESSIBLE|ACCESSIBLE
+32008118|Voorweg Hoog|ACCESSIBLE|ACCESSIBLE
+32008119|Meerzicht|NOTACCESSIBLE|ACCESSIBLE
+32008120|Meerzicht|ACCESSIBLE|ACCESSIBLE
+32008121|Driemanspolder|ACCESSIBLE|ACCESSIBLE
+32008122|Driemanspolder|ACCESSIBLE|ACCESSIBLE
+32008123|Delftsewallen|NOTACCESSIBLE|ACCESSIBLE
+32008126|Drop|ACCESSIBLE|ACCESSIBLE
+32008130|Oosterheem|ACCESSIBLE|ACCESSIBLE
+32008132|Javalaan|ACCESSIBLE|ACCESSIBLE
+32009589|Leidschenveen Centrum|ACCESSIBLE|ACCESSIBLE
+32009594|Forepark|ACCESSIBLE|ACCESSIBLE
+32009595|Forepark|ACCESSIBLE|ACCESSIBLE
+32009596|Leidschenveen|ACCESSIBLE|ACCESSIBLE
+32009597|Leidschenveen|ACCESSIBLE|ACCESSIBLE
+42000402|Den Hoorn, Hoornseweg|NOTACCESSIBLE|ACCESSIBLE
+42000701|Delft, Abtswoudsepark|ACCESSIBLE|ACCESSIBLE
+42000801|Delft, Abtswoude|ACCESSIBLE|ACCESSIBLE
+42000802|Delft, Abtswoude|ACCESSIBLE|ACCESSIBLE
+42001002|Delft, Arubastraat|ACCESSIBLE|ACCESSIBLE
+42001201|Delft, Bankastraat|NOTACCESSIBLE|ACCESSIBLE
+42001202|Delft, Bankastraat|ACCESSIBLE|ACCESSIBLE
+42001302|Delft, Buitenhofdreef|ACCESSIBLE|ACCESSIBLE
+42001501|Delft, Bieslandsekade|ACCESSIBLE|ACCESSIBLE
+42001502|Delft, Bieslandsekade|ACCESSIBLE|ACCESSIBLE
+42001801|Delft, Brasserskade|ACCESSIBLE|ACCESSIBLE
+42001802|Delft, Brasserskade|ACCESSIBLE|ACCESSIBLE
+42001901|Delft, Botanische Tuin|ACCESSIBLE|ACCESSIBLE
+42002001|Delft, Burgwal|ACCESSIBLE|ACCESSIBLE
+42002002|Delft, Burgwal|ACCESSIBLE|ACCESSIBLE
+42002201|Delft, Wateringseweg|ACCESSIBLE|ACCESSIBLE
+42002202|Delft, Wateringseweg|ACCESSIBLE|ACCESSIBLE
+42002301|Delft, Chopinlaan|ACCESSIBLE|ACCESSIBLE
+42002302|Delft, Chopinlaan|ACCESSIBLE|ACCESSIBLE
+42002401|Delft, Componistenpad|ACCESSIBLE|ACCESSIBLE
+42002402|Delft, Componistenpad|ACCESSIBLE|ACCESSIBLE
+42002501|Delft, Delftse Hout|ACCESSIBLE|ACCESSIBLE
+42002502|Delft, Delftse Hout|ACCESSIBLE|ACCESSIBLE
+42002601|Delft, Edelhertlaan|ACCESSIBLE|ACCESSIBLE
+42002602|Delft, Edelhertlaan|ACCESSIBLE|ACCESSIBLE
+42002802|Delft, Fuutlaan|ACCESSIBLE|ACCESSIBLE
+42003001|Delft, G.G.Z. Delfland|ACCESSIBLE|ACCESSIBLE
+42003002|Delft, G.G.Z. Delfland|ACCESSIBLE|ACCESSIBLE
+42003101|Delft, Hugo de Grootstraat|ACCESSIBLE|ACCESSIBLE
+42003102|Delft, Hugo de Grootstraat|ACCESSIBLE|ACCESSIBLE
+42003201|Delft, De Hoven Passage|ACCESSIBLE|ACCESSIBLE
+42003202|Delft, De Hoven Passage|ACCESSIBLE|ACCESSIBLE
+42003401|Delft, IKEA|ACCESSIBLE|ACCESSIBLE
+42003402|Delft, IKEA|ACCESSIBLE|ACCESSIBLE
+42003501|Delft, Jan Campertlaan|ACCESSIBLE|ACCESSIBLE
+42003502|Delft, Jan Campertlaan|ACCESSIBLE|ACCESSIBLE
+42003801|Delft, Kalfjeslaan|ACCESSIBLE|ACCESSIBLE
+42003802|Delft, Kalfjeslaan|ACCESSIBLE|ACCESSIBLE
+42004001|Delft, Latijns Amerikalaan|ACCESSIBLE|ACCESSIBLE
+42004002|Delft, Latijns Amerikalaan|ACCESSIBLE|ACCESSIBLE
+42004101|Delft, Lindenhof/Kuyperweg|ACCESSIBLE|ACCESSIBLE
+42004102|Delft, Lindenhof/Kuyperweg|ACCESSIBLE|ACCESSIBLE
+42004202|Delft, Brahmslaan|ACCESSIBLE|ACCESSIBLE
+42004301|Delft, Marlotlaan|ACCESSIBLE|ACCESSIBLE
+42004302|Delft, Marlotlaan|ACCESSIBLE|ACCESSIBLE
+42004402|Delft, Markt|ACCESSIBLE|ACCESSIBLE
+42004701|Delft, Twee Molentjeskade|ACCESSIBLE|ACCESSIBLE
+42004702|Delft, Twee Molentjeskade|ACCESSIBLE|ACCESSIBLE
+42004801|Delft, Mozartlaan|ACCESSIBLE|ACCESSIBLE
+42004802|Delft, Mozartlaan|ACCESSIBLE|ACCESSIBLE
+42004901|Delft, Menno ter Braaklaan|ACCESSIBLE|ACCESSIBLE
+42004902|Delft, Menno ter Braaklaan|ACCESSIBLE|ACCESSIBLE
+42005001|Delft, Nassauplein|ACCESSIBLE|ACCESSIBLE
+42005002|Delft, Nassauplein|ACCESSIBLE|ACCESSIBLE
+42005101|Delft, Nieuwe Langendijk|ACCESSIBLE|ACCESSIBLE
+42005102|Delft, Nieuwe Langendijk|ACCESSIBLE|ACCESSIBLE
+42005401|Delft, TNO Zuidpolder|ACCESSIBLE|ACCESSIBLE
+42005402|Delft, TNO Zuidpolder|ACCESSIBLE|ACCESSIBLE
+42005501|Delft, Parkzoom|ACCESSIBLE|ACCESSIBLE
+42005502|Delft, Parkzoom|ACCESSIBLE|ACCESSIBLE
+42005601|Delft, Poortcenter|ACCESSIBLE|ACCESSIBLE
+42005602|Delft, Poortcenter|NOTACCESSIBLE|ACCESSIBLE
+42005901|Delft, Poortlandplein|ACCESSIBLE|ACCESSIBLE
+42005902|Delft, Poortlandplein|ACCESSIBLE|ACCESSIBLE
+42006101|Delft, Revalidatiecentrum|ACCESSIBLE|ACCESSIBLE
+42006102|Delft, Revalidatiecentrum|ACCESSIBLE|ACCESSIBLE
+42006201|Delft, Reinier de Graaf Gasthuis|ACCESSIBLE|ACCESSIBLE
+42006202|Delft, Reinier de Graaf Gasthuis|ACCESSIBLE|ACCESSIBLE
+42006301|Delft, Rietzangerstraat|ACCESSIBLE|ACCESSIBLE
+42006302|Delft, Rietzangerstraat|ACCESSIBLE|ACCESSIBLE
+42006401|Delft, Schoolstraat|ACCESSIBLE|ACCESSIBLE
+42006402|Delft, Schoolstraat|ACCESSIBLE|ACCESSIBLE
+42006601|Delft, Stefanna|ACCESSIBLE|ACCESSIBLE
+42006602|Delft, Stefanna|ACCESSIBLE|ACCESSIBLE
+42006701|Delft, Stieltjesweg|NOTACCESSIBLE|ACCESSIBLE
+42006702|Delft, Stieltjesweg|ACCESSIBLE|ACCESSIBLE
+42006801|Delft, van der Lelijstraat|ACCESSIBLE|ACCESSIBLE
+42006802|Delft, van der Lelijstraat|ACCESSIBLE|ACCESSIBLE
+42006901|Delft, van der Slootsingel|ACCESSIBLE|ACCESSIBLE
+42006902|Delft, van der Slootsingel|ACCESSIBLE|ACCESSIBLE
+42007001|Delft, Voorhofdreef|NOTACCESSIBLE|ACCESSIBLE
+42007002|Delft, Voorhofdreef|ACCESSIBLE|ACCESSIBLE
+42007101|Delft, Vrijheidslaan|ACCESSIBLE|ACCESSIBLE
+42007301|Delft, Weteringlaan|ACCESSIBLE|ACCESSIBLE
+42007302|Delft, Weteringlaan|ACCESSIBLE|ACCESSIBLE
+42007401|Delft, Westlandhof|ACCESSIBLE|ACCESSIBLE
+42007402|Delft, Westlandhof|ACCESSIBLE|ACCESSIBLE
+42007701|Delft, Westlandseweg|ACCESSIBLE|ACCESSIBLE
+42007702|Delft, Westlandseweg|ACCESSIBLE|ACCESSIBLE
+42007901|Delfgauw, Delfgauwseplein|ACCESSIBLE|ACCESSIBLE
+42007902|Delfgauw, Delfgauwseplein|ACCESSIBLE|ACCESSIBLE
+42008001|Delfgauw, Gouden Rijderplein|ACCESSIBLE|ACCESSIBLE
+42008002|Delfgauw, Gouden Rijderplein|ACCESSIBLE|ACCESSIBLE
+42008301|Delfgauw, Laan van Ruyven|ACCESSIBLE|ACCESSIBLE
+42008401|Delft, Laan der Zeven Linden|ACCESSIBLE|ACCESSIBLE
+42008402|Delft, Laan der Zeven Linden|NOTACCESSIBLE|ACCESSIBLE
+42008501|Delfgauw, Overslagweg|ACCESSIBLE|ACCESSIBLE
+42008801|De Lier, Hoofdstraat|ACCESSIBLE|ACCESSIBLE
+42008802|De Lier, Hoofdstraat|ACCESSIBLE|ACCESSIBLE
+42009401|De Lier, Sportlaan|ACCESSIBLE|ACCESSIBLE
+42009402|De Lier, Sportlaan|ACCESSIBLE|ACCESSIBLE
+42009501|De Lier, Zwetburgh|ACCESSIBLE|ACCESSIBLE
+42009502|De Lier, Zwetburgh|ACCESSIBLE|ACCESSIBLE
+42010901|Den Haag, Carel Reinierszkade|ACCESSIBLE|ACCESSIBLE
+42010902|Den Haag, Carel Reinierszkade|ACCESSIBLE|ACCESSIBLE
+42011101|Den Haag, Dedemsvaartweg|ACCESSIBLE|ACCESSIBLE
+42013001|Den Haag, Haagse Markt|ACCESSIBLE|ACCESSIBLE
+42013002|Den Haag, Haagse Markt|ACCESSIBLE|ACCESSIBLE
+42014202|Den Haag, Kaapseplein|NOTACCESSIBLE|ACCESSIBLE
+42014501|Den Haag, Lanen|ACCESSIBLE|ACCESSIBLE
+42014502|Den Haag, Lanen|ACCESSIBLE|ACCESSIBLE
+42016102|Den Haag, Laan van Wateringseveld|ACCESSIBLE|ACCESSIBLE
+42017001|Den Haag, Laan van Nieuw Oost-Indie|ACCESSIBLE|ACCESSIBLE
+42017301|Den Haag, Station Ypenburg|ACCESSIBLE|ACCESSIBLE
+42017304|Den Haag, Station Ypenburg|ACCESSIBLE|ACCESSIBLE
+42017401|Den Haag, Ockenburgh|ACCESSIBLE|ACCESSIBLE
+42017402|Den Haag, Ockenburgh|ACCESSIBLE|ACCESSIBLE
+42018501|Den Haag, Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
+42018502|Den Haag, Reigersbergenweg|ACCESSIBLE|ACCESSIBLE
+42018901|Den Haag, Schalk Burgerstraat|ACCESSIBLE|ACCESSIBLE
+42018902|Den Haag, Schalk Burgerstraat|NOTACCESSIBLE|ACCESSIBLE
+42019202|Den Haag, Steenhouwersgaarde|ACCESSIBLE|ACCESSIBLE
+42019301|Den Haag, Strijpkade|ACCESSIBLE|ACCESSIBLE
+42019302|Den Haag, Strijpkade|ACCESSIBLE|ACCESSIBLE
+42021201|'s-Gravenzande, De Brug|ACCESSIBLE|ACCESSIBLE
+42021202|'s-Gravenzande, De Brug|ACCESSIBLE|ACCESSIBLE
+42021301|'s-Gravenzande, Edisonstraat|ACCESSIBLE|ACCESSIBLE
+42021302|'s-Gravenzande, Edisonstraat|ACCESSIBLE|ACCESSIBLE
+42021601|'s-Gravenzande, Heliotroop|ACCESSIBLE|ACCESSIBLE
+42021701|'s-Gravenzande, Hoflaan|ACCESSIBLE|ACCESSIBLE
+42021904|Den Haag, Leyenburg Perron H|NOTACCESSIBLE|ACCESSIBLE
+42022001|'s-Gravenzande, Langestraat|ACCESSIBLE|ACCESSIBLE
+42022002|'s-Gravenzande, Langestraat|ACCESSIBLE|ACCESSIBLE
+42022301|'s-Gravenzande, Naaldwijkseweg|ACCESSIBLE|ACCESSIBLE
+42022302|'s-Gravenzande, Naaldwijkseweg|ACCESSIBLE|ACCESSIBLE
+42022501|'s-Gravenzande, Strandweg|ACCESSIBLE|ACCESSIBLE
+42023301|'s-Gravenzande, Zandeveltplein|ACCESSIBLE|ACCESSIBLE
+42023302|'s-Gravenzande, Zandeveltplein|ACCESSIBLE|ACCESSIBLE
+42024101|Honselersdijk, Nederhof|ACCESSIBLE|ACCESSIBLE
+42024102|Honselersdijk, Nederhof|ACCESSIBLE|ACCESSIBLE
+42024202|Honselersdijk, Nieuweweg|ACCESSIBLE|ACCESSIBLE
+42024601|Honselersdijk, Strijplaan|ACCESSIBLE|ACCESSIBLE
+42026501|Kwintsheul, Raaphorstbrug|ACCESSIBLE|ACCESSIBLE
+42026502|Kwintsheul, Raaphorstbrug|ACCESSIBLE|ACCESSIBLE
+42026601|Kwintsheul, RK Kerk|ACCESSIBLE|ACCESSIBLE
+42026602|Kwintsheul, RK Kerk|ACCESSIBLE|ACCESSIBLE
+42026703|Leidschendam, St. Antoniushove|ACCESSIBLE|ACCESSIBLE
+42026704|Leidschendam, MCH Antoniushove|ACCESSIBLE|ACCESSIBLE
+42027101|Leidschendam, Dillenburgsingel|ACCESSIBLE|ACCESSIBLE
+42027102|Leidschendam, Dillenburgsingel|ACCESSIBLE|ACCESSIBLE
+42027501|Leidschendam, Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
+42027503|Leidschendam, Koningin Julianaplein|ACCESSIBLE|ACCESSIBLE
+42027601|Leidschendam, Leidsenhage/Banninglaan|ACCESSIBLE|ACCESSIBLE
+42027602|Leidschendam, Leidsenhage/Banninglaan|ACCESSIBLE|ACCESSIBLE
+42027801|Leidschendam, Vlindertuin|ACCESSIBLE|ACCESSIBLE
+42027802|Leidschendam, Vlindertuin|ACCESSIBLE|ACCESSIBLE
+42028501|Leidschendam, Rozenrust|ACCESSIBLE|ACCESSIBLE
+42028502|Leidschendam, Rozenrust|ACCESSIBLE|ACCESSIBLE
+42028701|Voorburg, Sijtwendetunnel|ACCESSIBLE|ACCESSIBLE
+42029001|Leidschendam, Weikamp|ACCESSIBLE|ACCESSIBLE
+42029002|Leidschendam, Weikamp|ACCESSIBLE|ACCESSIBLE
+42034001|Maasland, Commandeurskade|ACCESSIBLE|ACCESSIBLE
+42034002|Maasland, Commandeurskade|NOTACCESSIBLE|ACCESSIBLE
+42034101|Maasland, Doelstraat|ACCESSIBLE|ACCESSIBLE
+42034102|Maasland, Doelstraat|ACCESSIBLE|ACCESSIBLE
+42034401|Maasland, Kluisweer|ACCESSIBLE|ACCESSIBLE
+42034402|Maasland, Kluisweer|ACCESSIBLE|ACCESSIBLE
+42034901|Maasland, Nieuw Huis Ter Lucht|ACCESSIBLE|ACCESSIBLE
+42034902|Maasland, Nieuw Huis Ter Lucht|ACCESSIBLE|ACCESSIBLE
+42035002|Maasland, Viaduct|ACCESSIBLE|ACCESSIBLE
+42035003|Maasland, Viaduct|ACCESSIBLE|ACCESSIBLE
+42035101|Monster, Acaciastraat|ACCESSIBLE|ACCESSIBLE
+42035102|Monster, Acaciastraat|ACCESSIBLE|ACCESSIBLE
+42035201|Monster, Duinstraat|ACCESSIBLE|ACCESSIBLE
+42035202|Monster, Duinstraat|ACCESSIBLE|ACCESSIBLE
+42035301|Monster, Emmaplein|ACCESSIBLE|ACCESSIBLE
+42035302|Monster, Emmaplein|ACCESSIBLE|ACCESSIBLE
+42035601|Monster, Plaats Langeveld|ACCESSIBLE|ACCESSIBLE
+42035602|Monster, Plaats Langeveld|ACCESSIBLE|ACCESSIBLE
+42035701|Monster, Schelppad|ACCESSIBLE|ACCESSIBLE
+42035702|Monster, Schelppad|ACCESSIBLE|ACCESSIBLE
+42035801|Monster, De Tol|ACCESSIBLE|ACCESSIBLE
+42035901|Monster, Taets van Amerongenstraat|ACCESSIBLE|ACCESSIBLE
+42035902|Monster, Taets van Amerongenstraat|ACCESSIBLE|ACCESSIBLE
+42036002|Monster, Verdilaan|ACCESSIBLE|ACCESSIBLE
+42036201|Monster, Watergat|ACCESSIBLE|ACCESSIBLE
+42036202|Monster, Watergat|ACCESSIBLE|ACCESSIBLE
+42036302|Monster, Stitching Westerhonk|ACCESSIBLE|ACCESSIBLE
+42036701|Maasdijk, Verkadestraat|ACCESSIBLE|ACCESSIBLE
+42036702|Maasdijk, Verkadestraat|ACCESSIBLE|ACCESSIBLE
+42039001|Nootdorp, Begraafplaats St. Janshof|ACCESSIBLE|ACCESSIBLE
+42039002|Nootdorp, Begraafplaats St. Janshof|ACCESSIBLE|ACCESSIBLE
+42039201|Nootdorp, Duizendschoon|ACCESSIBLE|ACCESSIBLE
+42039202|Nootdorp, Duizendschoon|ACCESSIBLE|ACCESSIBLE
+42039501|Nootdorp, Larixlaan|ACCESSIBLE|ACCESSIBLE
+42039502|Nootdorp, Larixlaan|ACCESSIBLE|ACCESSIBLE
+42039801|Nootdorp, Rotonde Randstadrail|ACCESSIBLE|ACCESSIBLE
+42040101|Naaldwijk, Ambachtstraat|ACCESSIBLE|ACCESSIBLE
+42040102|Naaldwijk, Ambachtstraat|ACCESSIBLE|ACCESSIBLE
+42040401|Naaldwijk, Hoge Woerd|ACCESSIBLE|ACCESSIBLE
+42040501|Naaldwijk, Industriestraat|ACCESSIBLE|ACCESSIBLE
+42040502|Naaldwijk, Industriestraat|ACCESSIBLE|ACCESSIBLE
+42040601|Naaldwijk, Linde|ACCESSIBLE|ACCESSIBLE
+42040602|Naaldwijk, Linde|ACCESSIBLE|ACCESSIBLE
+42040701|Naaldwijk, Lage Woerd|ACCESSIBLE|ACCESSIBLE
+42040702|Naaldwijk, Lage Woerd|ACCESSIBLE|ACCESSIBLE
+42040901|Naaldwijk, Perzikenstraat/Rozenhof|ACCESSIBLE|ACCESSIBLE
+42040902|Naaldwijk, Perzikenstraat/Rozenhof|ACCESSIBLE|ACCESSIBLE
+42041001|Naaldwijk, Pijle Tuinen|ACCESSIBLE|ACCESSIBLE
+42041002|Naaldwijk, Pijle Tuinen|ACCESSIBLE|ACCESSIBLE
+42041301|Naaldwijk, Zuidweg|ACCESSIBLE|ACCESSIBLE
+42041302|Naaldwijk, Zuidweg|ACCESSIBLE|ACCESSIBLE
+42042001|Pijnacker, Ade|ACCESSIBLE|ACCESSIBLE
+42042002|Pijnacker, Ade|ACCESSIBLE|ACCESSIBLE
+42044001|Pijnacker, Rijskade|ACCESSIBLE|ACCESSIBLE
+42044002|Pijnacker, Rijskade|ACCESSIBLE|ACCESSIBLE
+42044401|Rijswijk, In de Bogaard|ACCESSIBLE|ACCESSIBLE
+42044402|Rijswijk, In de Bogaard|ACCESSIBLE|ACCESSIBLE
+42044701|Rijswijk, Darling Markt|ACCESSIBLE|ACCESSIBLE
+42044702|Rijswijk, Darling Markt|ACCESSIBLE|ACCESSIBLE
+42045204|Rijswijk, Dr. H.J. van Mooklaan|ACCESSIBLE|ACCESSIBLE
+42045406|Rijswijk, Station Rijswijk|NOTACCESSIBLE|ACCESSIBLE
+42045407|Rijswijk, Station Rijswijk|NOTACCESSIBLE|ACCESSIBLE
+42046401|Rijswijk, TNO / Lange Kleiweg|ACCESSIBLE|ACCESSIBLE
+42046402|Rijswijk, TNO / Lange Kleiweg|ACCESSIBLE|ACCESSIBLE
+42046701|Rijswijk, van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
+42046702|Rijswijk, van Vredenburchweg|ACCESSIBLE|ACCESSIBLE
+42050101|Voorburg, Sijtwendetunnel|ACCESSIBLE|ACCESSIBLE
+42050301|Voorburg, Hoeckvlietstraat|ACCESSIBLE|ACCESSIBLE
+42050302|Voorburg, Hoeckvlietstraat|ACCESSIBLE|ACCESSIBLE
+42051001|Voorburg, Station Leidschendam/Voorburg|ACCESSIBLE|ACCESSIBLE
+42051501|Voorburg, Rembrandtlaan|ACCESSIBLE|ACCESSIBLE
+42051502|Voorburg, Rembrandtlaan|ACCESSIBLE|ACCESSIBLE
+42052001|Voorburg, van Halewijnlaan|ACCESSIBLE|ACCESSIBLE
+42052002|Voorburg, van Halewijnlaan|ACCESSIBLE|ACCESSIBLE
+42052101|Voorburg, van Heurnstraat|ACCESSIBLE|ACCESSIBLE
+42052102|Voorburg, van Heurnstraat|ACCESSIBLE|ACCESSIBLE
+42055401|Wassenaar, Ammonslaantje|ACCESSIBLE|ACCESSIBLE
+42055402|Wassenaar, Ammonslaantje|ACCESSIBLE|ACCESSIBLE
+42055501|Wassenaar, Beukenhorstlaan|ACCESSIBLE|ACCESSIBLE
+42055502|Wassenaar, Beukenhorstlaan|ACCESSIBLE|ACCESSIBLE
+42055601|Wassenaar, Burchtlaan|ACCESSIBLE|ACCESSIBLE
+42055801|Wassenaar, van Duivenvoordelaan|ACCESSIBLE|ACCESSIBLE
+42055802|Wassenaar, van Duivenvoordelaan|ACCESSIBLE|ACCESSIBLE
+42056001|Wassenaar, Jonkerlaan|ACCESSIBLE|ACCESSIBLE
+42056002|Wassenaar, Jonkerlaan|ACCESSIBLE|ACCESSIBLE
+42056401|Wassenaar, Maaldrift|ACCESSIBLE|ACCESSIBLE
+42056402|Wassenaar, Maaldrift|ACCESSIBLE|ACCESSIBLE
+42056501|Wassenaar, Nachtegaallaan|ACCESSIBLE|ACCESSIBLE
+42056502|Wassenaar, Nachtegaallaan|ACCESSIBLE|ACCESSIBLE
+42056901|Wassenaar, Park Duinrell|ACCESSIBLE|ACCESSIBLE
+42056902|Wassenaar, Park Duinrell|ACCESSIBLE|ACCESSIBLE
+42057101|Wassenaar, Rozenplein|ACCESSIBLE|ACCESSIBLE
+42057102|Wassenaar, Rozenplein|ACCESSIBLE|ACCESSIBLE
+42057301|Wassenaar, Stadhoudersplein|ACCESSIBLE|ACCESSIBLE
+42057302|Wassenaar, Stadhoudersplein|ACCESSIBLE|ACCESSIBLE
+42057501|Wassenaar, Stoeplaan|ACCESSIBLE|ACCESSIBLE
+42057502|Wassenaar, Stoeplaan|ACCESSIBLE|ACCESSIBLE
+42057601|Wassenaar, Strandwal|ACCESSIBLE|ACCESSIBLE
+42057602|Wassenaar, Strandwal|ACCESSIBLE|ACCESSIBLE
+42057701|Wassenaar, Ter Weerlaan|ACCESSIBLE|ACCESSIBLE
+42057702|Wassenaar, Ter Weerlaan|ACCESSIBLE|ACCESSIBLE
+42057901|Wassenaar, Weyermanstraat|ACCESSIBLE|ACCESSIBLE
+42057902|Wassenaar, Weyermanstraat|ACCESSIBLE|ACCESSIBLE
+42058001|Wassenaar, Wittenburgerweg|ACCESSIBLE|ACCESSIBLE
+42058101|Wassenaar, Wildrust|ACCESSIBLE|ACCESSIBLE
+42058102|Wassenaar, Wildrust|ACCESSIBLE|ACCESSIBLE
+42058201|Wateringen, De Ark|ACCESSIBLE|ACCESSIBLE
+42058202|Wateringen, De Ark|ACCESSIBLE|ACCESSIBLE
+42058301|Wateringen, Gemeentehuis / Plein|ACCESSIBLE|ACCESSIBLE
+42058401|Wateringen, Harry Hoekstraat|ACCESSIBLE|ACCESSIBLE
+42058402|Wateringen, Harry Hoekstraat|ACCESSIBLE|ACCESSIBLE
+42058501|Wateringen, Plein|ACCESSIBLE|ACCESSIBLE
+42058503|Wateringen, Plein|ACCESSIBLE|ACCESSIBLE
+42058601|Zoetermeer, Acaciazoom|ACCESSIBLE|ACCESSIBLE
+42058602|Zoetermeer, Acaciazoom|ACCESSIBLE|ACCESSIBLE
+42058701|Zoetermeer, Alkmenehof|ACCESSIBLE|ACCESSIBLE
+42059101|Zoetermeer, Berglaan|ACCESSIBLE|ACCESSIBLE
+42059102|Zoetermeer, Berglaan|ACCESSIBLE|ACCESSIBLE
+42059201|Zoetermeer, Beryl|ACCESSIBLE|ACCESSIBLE
+42059202|Zoetermeer, Beryl|ACCESSIBLE|ACCESSIBLE
+42059501|Zoetermeer, Brinkmanplan|ACCESSIBLE|ACCESSIBLE
+42059702|Zoetermeer, Centrum West (Perron B)|ACCESSIBLE|ACCESSIBLE
+42059703|Zoetermeer, Centrum West (Perron F)|ACCESSIBLE|ACCESSIBLE
+42059705|Zoetermeer, Centrum West (Perron H)|ACCESSIBLE|ACCESSIBLE
+42059801|Zoetermeer, De Louvrierruimte|ACCESSIBLE|ACCESSIBLE
+42060101|Zoetermeer, Driesprong|ACCESSIBLE|ACCESSIBLE
+42060102|Zoetermeer, Driesprong|ACCESSIBLE|ACCESSIBLE
+42060301|Zoetermeer, Dijkmanschans|ACCESSIBLE|ACCESSIBLE
+42060601|Zoetermeer, Electrablauw|ACCESSIBLE|ACCESSIBLE
+42060602|Zoetermeer, Electrablauw|ACCESSIBLE|ACCESSIBLE
+42060701|Zoetermeer, Elzehout|ACCESSIBLE|ACCESSIBLE
+42060702|Zoetermeer, Elzehout|ACCESSIBLE|ACCESSIBLE
+42061101|Zoetermeer, Florazoom|ACCESSIBLE|ACCESSIBLE
+42061102|Zoetermeer, Florazoom|ACCESSIBLE|ACCESSIBLE
+42061202|Zoetermeer, Fonteinbos|ACCESSIBLE|ACCESSIBLE
+42061601|Zoetermeer, Hoflaan|ACCESSIBLE|ACCESSIBLE
+42061702|Zoetermeer, Houtsingel|ACCESSIBLE|ACCESSIBLE
+42061901|Zoetermeer, Kahnlijn|ACCESSIBLE|ACCESSIBLE
+42062001|Zoetermeer, Kerkenbos|ACCESSIBLE|ACCESSIBLE
+42062002|Zoetermeer, Kerkenbos|ACCESSIBLE|ACCESSIBLE
+42062101|Zoetermeer, Kleurlaan|ACCESSIBLE|ACCESSIBLE
+42062501|Zoetermeer, Lommerbaan|ACCESSIBLE|ACCESSIBLE
+42062902|Zoetermeer, Meerzichtlaan|ACCESSIBLE|ACCESSIBLE
+42063101|Zoetermeer, Nathaliegang|ACCESSIBLE|ACCESSIBLE
+42063102|Zoetermeer, Nathaliegang|ACCESSIBLE|ACCESSIBLE
+42063301|Zoetermeer, Noordhove/Winkelcentrum|ACCESSIBLE|ACCESSIBLE
+42063401|Zoetermeer, Station Oost|ACCESSIBLE|ACCESSIBLE
+42063601|Zoetermeer, Ogeahout|NOTACCESSIBLE|ACCESSIBLE
+42063602|Zoetermeer, Ogeahout|ACCESSIBLE|ACCESSIBLE
+42063801|Zoetermeer, Pelschans|NOTACCESSIBLE|ACCESSIBLE
+42064101|Zoetermeer, Redelaan|ACCESSIBLE|ACCESSIBLE
+42064302|Zoetermeer, Robijn|ACCESSIBLE|ACCESSIBLE
+42064601|Zoetermeer, Salomeschouw|ACCESSIBLE|ACCESSIBLE
+42064602|Zoetermeer, Salomeschouw|ACCESSIBLE|ACCESSIBLE
+42064801|Zoetermeer, Sportctr. De Driesprong|ACCESSIBLE|ACCESSIBLE
+42064802|Zoetermeer, Sportctr. De Driesprong|ACCESSIBLE|ACCESSIBLE
+42064902|Zoetermeer, Sportcentrum De Veur|ACCESSIBLE|ACCESSIBLE
+42065001|Zoetermeer, Stadhoudersring|ACCESSIBLE|ACCESSIBLE
+42065002|Zoetermeer, Stadhoudersring|ACCESSIBLE|ACCESSIBLE
+42065101|Zoetermeer, Station Driemanspolder|ACCESSIBLE|ACCESSIBLE
+42065102|Zoetermeer, Station Driemanspolder|ACCESSIBLE|ACCESSIBLE
+42065201|Zoetermeer, Station Meerzicht|ACCESSIBLE|ACCESSIBLE
+42065202|Zoetermeer, Station Meerzicht|ACCESSIBLE|ACCESSIBLE
+42065401|Zoetermeer, Surfpad|ACCESSIBLE|ACCESSIBLE
+42065402|Zoetermeer, Surfpad|ACCESSIBLE|ACCESSIBLE
+42065601|Zoetermeer, Viaduct Afrikaweg|ACCESSIBLE|ACCESSIBLE
+42065602|Zoetermeer, Viaduct Afrikaweg|ACCESSIBLE|ACCESSIBLE
+42066101|Zoetermeer, Winkelcentrum De Vlieger|ACCESSIBLE|ACCESSIBLE
+42066102|Zoetermeer, Winkelcentrum De Vlieger|ACCESSIBLE|ACCESSIBLE
+42066301|Zoetermeer, Maria Montessorilaan|ACCESSIBLE|ACCESSIBLE
+42066302|Zoetermeer, Maria Montessorilaan|ACCESSIBLE|ACCESSIBLE
+42066401|Zoetermeer, Winkelcentrum Rokkeveen|ACCESSIBLE|ACCESSIBLE
+42066402|Zoetermeer, Winkelcentrum Rokkeveen|ACCESSIBLE|ACCESSIBLE
+42066501|Zoetermeer, Zalkerbos|ACCESSIBLE|ACCESSIBLE
+42066502|Zoetermeer, Zalkerbos|ACCESSIBLE|ACCESSIBLE
+42066701|Zoetermeer, Zwaardslootseweg|ACCESSIBLE|ACCESSIBLE
+42066702|Zoetermeer, Zwaardslootseweg|ACCESSIBLE|ACCESSIBLE
+42066801|Zoetermeer, Planbaan|ACCESSIBLE|ACCESSIBLE
+42066901|Zoetermeer, Groen-blauwlaan|ACCESSIBLE|ACCESSIBLE
+42067002|Delfgauw, Hoefsmidstraat|ACCESSIBLE|ACCESSIBLE
+42067101|Delfgauw, Achtmanstraat|ACCESSIBLE|ACCESSIBLE
+42067102|Delfgauw, Achtmanstraat|ACCESSIBLE|ACCESSIBLE
+42067201|Delfgauw, Laan van Ruyven|ACCESSIBLE|ACCESSIBLE
+42068301|Nootdorp, De Poort|ACCESSIBLE|ACCESSIBLE
+42069502|Delft, Olof Palmestraat|ACCESSIBLE|ACCESSIBLE
+42070601|Wateringen, Vlasser|NOTACCESSIBLE|ACCESSIBLE
+42070602|Wateringen, Vlasser|ACCESSIBLE|ACCESSIBLE
+42070701|Wateringen, Guldeland|ACCESSIBLE|ACCESSIBLE
+42070702|Wateringen, Guldeland|ACCESSIBLE|ACCESSIBLE
+42070801|Wateringen, Willem 3 straat|ACCESSIBLE|ACCESSIBLE
+42070802|Wateringen, Willem 3 straat|ACCESSIBLE|ACCESSIBLE
+42071301|Den Haag, Melis Stokelaan|NOTACCESSIBLE|ACCESSIBLE
+42071302|Den Haag, Melis Stokelaan|ACCESSIBLE|ACCESSIBLE
+42071401|Den Haag, Dalerveenstraat|ACCESSIBLE|ACCESSIBLE
+42071402|Den Haag, Dalerveenstraat|ACCESSIBLE|ACCESSIBLE
+42071501|Den Haag, Gramsbergenlaan|ACCESSIBLE|ACCESSIBLE
+42071502|Den Haag, Gramsbergenlaan|ACCESSIBLE|ACCESSIBLE
+42071901|Delft, Pootstraat|ACCESSIBLE|ACCESSIBLE
+42072001|Delft, Frank van Borselenstraat|ACCESSIBLE|ACCESSIBLE
+42072601|Delft, Station Zuid|ACCESSIBLE|ACCESSIBLE
+42072602|Delft, Station Zuid|ACCESSIBLE|ACCESSIBLE
+49000040|Lelystad, Ziekenhuis|ACCESSIBLE|ACCESSIBLE
+49001650|Lelystad, Agora|ACCESSIBLE|ACCESSIBLE
+49001700|Lelystad, Agora|ACCESSIBLE|ACCESSIBLE
+49003250|Lelystad, Ziekenhuis|ACCESSIBLE|ACCESSIBLE
+49003300|Lelystad, De Hoven|ACCESSIBLE|ACCESSIBLE
+49003320|Lelystad, De Hoven|ACCESSIBLE|ACCESSIBLE
+49003370|Lelystad, 't Laar|ACCESSIBLE|ACCESSIBLE
+49004500|Lelystad, De Rietlanden|ACCESSIBLE|ACCESSIBLE
+49005550|Lelystad, Karveelbrug|ACCESSIBLE|ACCESSIBLE
+49005600|Lelystad, Karveelbrug|ACCESSIBLE|ACCESSIBLE
+49005650|Lelystad, Kempenaarbrug|ACCESSIBLE|ACCESSIBLE
+49005700|Lelystad, Kempenaarbrug|ACCESSIBLE|ACCESSIBLE
+49005850|Lelystad, Batavia Stad|ACCESSIBLE|ACCESSIBLE
+49005920|Lelystad, Batavia Stad|ACCESSIBLE|ACCESSIBLE
+49005921|Lelystad, Batavia Stad|ACCESSIBLE|ACCESSIBLE
+49007000|Lelystad, Houtribsluis|ACCESSIBLE|ACCESSIBLE
+49007010|Lelystad, Houtribsluis|ACCESSIBLE|ACCESSIBLE
+49120010|Lelystad, Bataviastad|ACCESSIBLE|ACCESSIBLE
+53491302|Maasland, Viaduct|ACCESSIBLE|ACCESSIBLE
+54000720|Dr. Kuyperstraat|ACCESSIBLE|ACCESSIBLE
+54240130|Wassenaar, Rijksdorp|ACCESSIBLE|ACCESSIBLE
+54240140|Wassenaar, Bronckhorstlaan|ACCESSIBLE|ACCESSIBLE
+54240390|Wassenaar, Lange Kerkdam|NOTACCESSIBLE|ACCESSIBLE
+54240400|Wassenaar, Lange Kerkdam|ACCESSIBLE|ACCESSIBLE
+54240440|Wassenaar, Johan de Wittstraat|ACCESSIBLE|ACCESSIBLE
+54241020|Wassenaar, Rijksdorp|ACCESSIBLE|ACCESSIBLE
+54360030|Wassenaar, Bronckhorstlaan|ACCESSIBLE|ACCESSIBLE
+54360070|Katwijk a/d Rijn, Hotel Wassenaar|ACCESSIBLE|ACCESSIBLE
+54360100|Wassenaar, Hotel Wassenaar|ACCESSIBLE|ACCESSIBLE
+54410066|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
+54410067|Zoetermeer, Centrum West (G)|ACCESSIBLE|ACCESSIBLE
+54410510|Zoetermeer, Wengehout|ACCESSIBLE|ACCESSIBLE
+54410520|Zoetermeer, Wengehout|ACCESSIBLE|ACCESSIBLE
+54410730|Zoetermeer, Pruimengaarde|ACCESSIBLE|ACCESSIBLE
+54410740|Zoetermeer, Pruimengaarde|ACCESSIBLE|ACCESSIBLE
+54411040|Zoetermeer, Ambachtsherenlaan|ACCESSIBLE|ACCESSIBLE
+54414032|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
+54414165|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
+54414206|Zoetermeer, Centrum West|ACCESSIBLE|ACCESSIBLE
+6013|Kruidenlaan|ACCESSIBLE|ACCESSIBLE
+6014|Kruidenlaan|ACCESSIBLE|ACCESSIBLE
+90000007|Lelystad, Agora|ACCESSIBLE|ACCESSIBLE
+90000009|Lelystad, 't Laar|ACCESSIBLE|ACCESSIBLE
+90000011|Lelystad, De Rietlanden|ACCESSIBLE|ACCESSIBLE
+90000012|Lelystad, Bataviahaven|ACCESSIBLE|ACCESSIBLE
+32000101|Oude Waalsdorperweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000102|Oude Waalsdorperweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000202|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
+32000205|Kurhausweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000206|Kurhaus|NOTACCESSIBLE|NOTACCESSIBLE
+32000207|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
+32000208|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
+32000209|Zwarte Pad|NOTACCESSIBLE|NOTACCESSIBLE
+32000217|Harstenhoekplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000219|Stevinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000220|Stevinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000221|Gentsestraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000311|Plesmanweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000401|Bronovo Ziekenhuis|NOTACCESSIBLE|NOTACCESSIBLE
+32000412|Oostduinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000413|Van der Woertstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000414|Van der Woertstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000415|Ruychrocklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000416|Ruychrocklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000428|Van Hoytemastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000435|Dr. Kuyperstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000437|Weissenbruchstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000438|Willem Witsenplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000439|Willem Witsenplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000503|Bankaplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000504|Bankaplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000507|Vredespaleis|NOTACCESSIBLE|NOTACCESSIBLE
+32000508|Vredespaleis|NOTACCESSIBLE|NOTACCESSIBLE
+32000509|Vredespaleis|NOTACCESSIBLE|NOTACCESSIBLE
+32000510|Nassauplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000511|Nassauplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000515|Alexanderplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000516|Alexanderplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000601|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
+32000603|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
+32000605|Kerkhoflaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000608|Madurodam|NOTACCESSIBLE|NOTACCESSIBLE
+32000702|Badhuiskade|NOTACCESSIBLE|NOTACCESSIBLE
+32000703|Badhuiskade|NOTACCESSIBLE|NOTACCESSIBLE
+32000706|Schev.slag/Beelden aan Zee|NOTACCESSIBLE|NOTACCESSIBLE
+32000707|Schev.slag/Beelden aan Zee|NOTACCESSIBLE|NOTACCESSIBLE
+32000714|Keizerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000715|Keizerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000716|Duinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000718|Duinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000719|Duinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000720|Prins Willemstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000721|Prins Willemstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000724|Haringkade|NOTACCESSIBLE|NOTACCESSIBLE
+32000725|Haringkade|NOTACCESSIBLE|NOTACCESSIBLE
+32000726|Nieuwe Parklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000727|Nieuwe Parklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000730|Douzastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000731|Douzastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000732|Statenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000733|Statenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000734|Rusthoekstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000737|Statenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000802|Markenseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000803|Tesselseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000804|Tesselseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000807|Nieboerweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000808|Nieboerweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000809|Markenseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000904|Scheveningseweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000905|Scheveningseweg|NOTACCESSIBLE|NOTACCESSIBLE
+32000917|Willem de Zwijgerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000918|Willem de Zwijgerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32000919|World Forum|NOTACCESSIBLE|NOTACCESSIBLE
+32000920|World Forum|NOTACCESSIBLE|NOTACCESSIBLE
+32000927|Statenplein|NOTACCESSIBLE|NOTACCESSIBLE
+32000930|Aert van der Goesstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32000932|Van Boetzelaerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001110|Conradkade|NOTACCESSIBLE|NOTACCESSIBLE
+32001111|Conradkade|NOTACCESSIBLE|NOTACCESSIBLE
+32001114|Groot Hertoginnelaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001115|Groot Hertoginnelaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001117|Banstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001118|Banstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001119|Conradkade|NOTACCESSIBLE|NOTACCESSIBLE
+32001123|Laan van Meerdervoort|NOTACCESSIBLE|NOTACCESSIBLE
+32001124|Laan van Meerdervoort|NOTACCESSIBLE|NOTACCESSIBLE
+32001204|Nieboerweg|NOTACCESSIBLE|NOTACCESSIBLE
+32001303|Kruisbeklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001305|Oude Buizerdlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001306|Oude Buizerdlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001419|De Savornin Lohmanplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001420|De Savornin Lohmanplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001426|Teunisbloemplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001427|de Savornin Lohmanplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001502|Kijkduin|NOTACCESSIBLE|NOTACCESSIBLE
+32001504|Kijkduin Strand|NOTACCESSIBLE|NOTACCESSIBLE
+32001506|Kijkduin Strand|NOTACCESSIBLE|NOTACCESSIBLE
+32001715|Houtwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001716|Houtwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001719|Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001721|Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001805|Pisuissestraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001806|Pisuissestraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001808|Groen van Prinstererlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32001818|Arnold Spoelplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001822|Louis Armstrongplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001823|Louis Armstrongplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001824|Buitentuinen|NOTACCESSIBLE|NOTACCESSIBLE
+32001825|Buitentuinen|NOTACCESSIBLE|NOTACCESSIBLE
+32001828|Binnentuinen|NOTACCESSIBLE|NOTACCESSIBLE
+32001829|Binnentuinen|NOTACCESSIBLE|NOTACCESSIBLE
+32001873|Westduin|NOTACCESSIBLE|NOTACCESSIBLE
+32001907|Colijnplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001908|Colijnplein|NOTACCESSIBLE|NOTACCESSIBLE
+32001911|Appelstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001912|Appelstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001916|Perenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001918|Laan van Eik en Duinen|NOTACCESSIBLE|NOTACCESSIBLE
+32001923|Okkernootstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32001924|Okkernootstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002002|Goudenregenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002008|Fahrenheitstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002012|Valkenbosplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002013|Valkenbosplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002017|Copernicusplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002018|Copernicusplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002019|Kamperfoeliestraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002020|Kamperfoeliestraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002021|Weimarstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002022|Weimarstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002301|Javastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002306|Javastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002307|Mauritskade|NOTACCESSIBLE|NOTACCESSIBLE
+32002308|Mauritskade|NOTACCESSIBLE|NOTACCESSIBLE
+32002309|Dr. Kuyperstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002310|Dr. Kuyperstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002313|Mauritskade|NOTACCESSIBLE|NOTACCESSIBLE
+32002403|Malieveld|NOTACCESSIBLE|NOTACCESSIBLE
+32002505|Barnsteenhorst|NOTACCESSIBLE|NOTACCESSIBLE
+32002507|Saffierhorst|NOTACCESSIBLE|NOTACCESSIBLE
+32002519|Het Kleine Loo|NOTACCESSIBLE|NOTACCESSIBLE
+32002520|Het Kleine Loo|NOTACCESSIBLE|NOTACCESSIBLE
+32002521|Margarethaland|NOTACCESSIBLE|NOTACCESSIBLE
+32002522|Margarethaland|NOTACCESSIBLE|NOTACCESSIBLE
+32002526|Station Mariahoeve|NOTACCESSIBLE|NOTACCESSIBLE
+32002631|Prins Clauslaan|NOTACCESSIBLE|NOTACCESSIBLE
+32002632|Prins Clauslaan|NOTACCESSIBLE|NOTACCESSIBLE
+32002633|Koningin Marialaan|NOTACCESSIBLE|NOTACCESSIBLE
+32002634|Koningin Marialaan|NOTACCESSIBLE|NOTACCESSIBLE
+32002635|Laan van Nieuw Oost Indië|NOTACCESSIBLE|NOTACCESSIBLE
+32002636|Laan van Nieuw Oost Indië|NOTACCESSIBLE|NOTACCESSIBLE
+32002639|Spaarwaterstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002640|Spaarwaterstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002641|De Eerensplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002642|De Eerensplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002645|Ternoot|NOTACCESSIBLE|NOTACCESSIBLE
+32002646|Ternoot|NOTACCESSIBLE|NOTACCESSIBLE
+32002655|Stuyvesantstraat|ACCESSIBLE|NOTACCESSIBLE
+32002656|Stuyvesantstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32002658|Station Laan van NOI|ACCESSIBLE|NOTACCESSIBLE
+32002659|Station Laan van NOI|ACCESSIBLE|NOTACCESSIBLE
+32002707|Rijswijkseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002708|Rijswijkseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002711|Weteringplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002712|Weteringplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002715|Rijswijkseplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002719|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32002720|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32002721|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32002730|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32002731|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32002803|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
+32002804|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
+32002821|Brouwersgracht|NOTACCESSIBLE|NOTACCESSIBLE
+32002828|Den Haag, Grote Markt|NOTACCESSIBLE|NOTACCESSIBLE
+32002845|Amsterdamse Veerkade|NOTACCESSIBLE|NOTACCESSIBLE
+32002846|Amsterdamse Veerkade|NOTACCESSIBLE|NOTACCESSIBLE
+32002857|Nieuwe Haven|NOTACCESSIBLE|NOTACCESSIBLE
+32002864|Buitenhof|NOTACCESSIBLE|NOTACCESSIBLE
+32002865|Buitenhof|NOTACCESSIBLE|NOTACCESSIBLE
+32002873|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
+32002874|Kneuterdijk|NOTACCESSIBLE|NOTACCESSIBLE
+32002909|Vaillantplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002913|Hobbemaplein|NOTACCESSIBLE|NOTACCESSIBLE
+32002914|Hobbemaplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003001|Loosduinseweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003009|Schalk Burgerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003010|Schalk Burgerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003113|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003123|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003125|Barneveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003126|Barneveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003130|Dierenselaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003201|Volendamlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003202|Volendamlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003209|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003210|Escamplaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003218|Leyenburg|NOTACCESSIBLE|NOTACCESSIBLE
+32003219|Zuiderpark|NOTACCESSIBLE|NOTACCESSIBLE
+32003220|Zuiderpark|NOTACCESSIBLE|NOTACCESSIBLE
+32003223|Monnickendamplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003224|Monnickendamplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003302|Drapeniersgaarde|NOTACCESSIBLE|NOTACCESSIBLE
+32003303|Drapeniersgaarde|NOTACCESSIBLE|NOTACCESSIBLE
+32003306|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003318|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003319|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003320|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003321|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003322|Hertenrade|NOTACCESSIBLE|NOTACCESSIBLE
+32003330|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003331|Beresteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003342|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003343|Vrederustlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003358|Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003359|Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003363|Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003364|Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003405|Meppelweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003406|Meppelweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003407|Almeloplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003408|Almeloplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003413|Leyweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003414|Leyweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003424|Loevesteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003425|Loevesteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003438|Fluitenbergstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003439|Fluitenbergstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003442|Steenwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003443|Steenwijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003601|Loevesteinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003612|Cannenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003613|Cannenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003624|Moerweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003625|Moerweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003626|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
+32003627|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
+32003628|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
+32003629|Station Moerwijk|NOTACCESSIBLE|NOTACCESSIBLE
+32003709|Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
+32003801|Goudriaankade|NOTACCESSIBLE|NOTACCESSIBLE
+32003802|Goudriaankade|NOTACCESSIBLE|NOTACCESSIBLE
+32003803|Calandplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003804|Calandplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003807|Neherkade|NOTACCESSIBLE|NOTACCESSIBLE
+32003808|Neherkade|NOTACCESSIBLE|NOTACCESSIBLE
+32003819|Jonckbloetplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003820|Jonckbloetplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003829|Alberdingk Thijmstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003830|Alberdingk Thijmstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003832|Ledeganckplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003833|Jan van Beersstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003834|Jan van Beersstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003843|Stieltjesstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003844|Stieltjesstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003845|Jonckbloetplein|NOTACCESSIBLE|NOTACCESSIBLE
+32003846|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32003847|Station Hollands Spoor|NOTACCESSIBLE|NOTACCESSIBLE
+32003857|Megastores|NOTACCESSIBLE|NOTACCESSIBLE
+32003858|Megastores|NOTACCESSIBLE|NOTACCESSIBLE
+32003859|Megastores hoofdingang|NOTACCESSIBLE|NOTACCESSIBLE
+32003903|Poolsterstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003904|Poolsterstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003905|Wegastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003906|Wegastraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003907|Zonweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003908|Zonweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003909|Melkwegstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003910|Melkwegstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003911|Saturnusstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32003917|Regulusweg|NOTACCESSIBLE|NOTACCESSIBLE
+32003919|Saturnusstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32004009|Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
+32004010|Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
+32004011|Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
+32004012|Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
+32005101|Herenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32005105|Bilderdijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+32005106|Geestbrug|NOTACCESSIBLE|NOTACCESSIBLE
+32005205|Esdoornstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32005206|Esdoornstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32005211|Paulus Potterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32005606|Aletta Jacobsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32005705|Klaroenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32005706|Klaroenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32005940|Plesmanlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32005941|Plesmanlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32006020|Dorpskade|NOTACCESSIBLE|NOTACCESSIBLE
+32007101|Binckhorstlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32007102|Binckhorstlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32007103|Diaconessenhuis|NOTACCESSIBLE|NOTACCESSIBLE
+32007104|Diaconessenhuis|NOTACCESSIBLE|NOTACCESSIBLE
+32007105|Redenburgstraat|NOTACCESSIBLE|NOTACCESSIBLE
+32007110|Voorburg Station|NOTACCESSIBLE|NOTACCESSIBLE
+32007111|Voorburg Station|NOTACCESSIBLE|NOTACCESSIBLE
+32007112|Sonnenburghlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32007202|Rozenboomlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32007411|Bruijnings Ingenhoeslaan|ACCESSIBLE|NOTACCESSIBLE
+32007412|Bruijnings Ingenhoeslaan|ACCESSIBLE|NOTACCESSIBLE
+32007505|Mgr. van Steelaan|ACCESSIBLE|NOTACCESSIBLE
+32007506|Mgr. van Steelaan|ACCESSIBLE|NOTACCESSIBLE
+32008125|Drop|NOTACCESSIBLE|NOTACCESSIBLE
+32008128|Willem Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
+32008129|Willem Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
+32008131|Oosterheem|NOTACCESSIBLE|NOTACCESSIBLE
+32009115|Abtswoudsepark|NOTACCESSIBLE|NOTACCESSIBLE
+32009509|MCH Antoniushove|NOTACCESSIBLE|NOTACCESSIBLE
+32009515|Prins Bernhardlaan|NOTACCESSIBLE|NOTACCESSIBLE
+32009521|MCH Antoniushove|NOTACCESSIBLE|NOTACCESSIBLE
+32009568|Spieringdam|NOTACCESSIBLE|NOTACCESSIBLE
+32009574|Houtkade|NOTACCESSIBLE|NOTACCESSIBLE
+32009807|Laan van Nootdorp|NOTACCESSIBLE|NOTACCESSIBLE
+32009810|Scholekstersingel|NOTACCESSIBLE|NOTACCESSIBLE
+32009811|Scholekstersingel|NOTACCESSIBLE|NOTACCESSIBLE
+32009812|Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
+32009813|Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
+32009815|Nootdorp Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+42000101|Den Hoorn, Houtzagerij|NOTACCESSIBLE|NOTACCESSIBLE
+42000102|Den Hoorn, Houtzagerij|NOTACCESSIBLE|NOTACCESSIBLE
+42000202|Den Hoorn, Hof van Delftstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42000302|Schipluiden, Manege|NOTACCESSIBLE|NOTACCESSIBLE
+42000501|Den Hoorn, My home is my castle|NOTACCESSIBLE|NOTACCESSIBLE
+42000502|Den Hoorn, My home is my castle|NOTACCESSIBLE|NOTACCESSIBLE
+42001101|Delft, Aula - TU|NOTACCESSIBLE|NOTACCESSIBLE
+42001401|Delft, De Bieslandhof|NOTACCESSIBLE|NOTACCESSIBLE
+42001402|Delft, De Bieslandhof|NOTACCESSIBLE|NOTACCESSIBLE
+42002701|Delft, Koningin Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
+42002702|Delft, Koningin Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
+42003601|Delft, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
+42003602|Delft, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
+42003901|Delft, Krakeelpolderweg|NOTACCESSIBLE|NOTACCESSIBLE
+42004401|Delft, Markt|NOTACCESSIBLE|NOTACCESSIBLE
+42004501|Delft, Michiel de Ruyterweg|NOTACCESSIBLE|NOTACCESSIBLE
+42004502|Delft, Michiel de Ruyterweg|NOTACCESSIBLE|NOTACCESSIBLE
+42005302|Delft, Station Delft (Perron D)|NOTACCESSIBLE|NOTACCESSIBLE
+42005303|Delft, Station Delft (Perron E)|NOTACCESSIBLE|NOTACCESSIBLE
+42005305|Delft, Station Delft (Perron G)|NOTACCESSIBLE|NOTACCESSIBLE
+42005306|Delft, Station Delft (Perron J)|NOTACCESSIBLE|NOTACCESSIBLE
+42005307|Delft, Station Delft (Perron H)|NOTACCESSIBLE|NOTACCESSIBLE
+42005801|Delft, Prof. Krausstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42005802|Delft, Prof. Krausstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42006001|Delft, Prinsenhof|NOTACCESSIBLE|NOTACCESSIBLE
+42006002|Delft, Prinsenhof|NOTACCESSIBLE|NOTACCESSIBLE
+42006501|Delft, Schoemakerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42006502|Delft, Schoemakerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42007102|Delft, Vrijheidslaan|NOTACCESSIBLE|NOTACCESSIBLE
+42007201|Delft, Watermanweg|NOTACCESSIBLE|NOTACCESSIBLE
+42007202|Delft, Watermanweg|NOTACCESSIBLE|NOTACCESSIBLE
+42007601|Delft, Wateringsevest|NOTACCESSIBLE|NOTACCESSIBLE
+42007602|Delft, Wateringsevest|NOTACCESSIBLE|NOTACCESSIBLE
+42008903|De Lier, Jogchem van der Houtweg|NOTACCESSIBLE|NOTACCESSIBLE
+42009101|De Lier, Leeweg|NOTACCESSIBLE|NOTACCESSIBLE
+42009102|De Lier, Leeweg|NOTACCESSIBLE|NOTACCESSIBLE
+42009201|De Lier, Lierweg|NOTACCESSIBLE|NOTACCESSIBLE
+42009202|De Lier, Lierweg|NOTACCESSIBLE|NOTACCESSIBLE
+42009602|Den Haag, Arnold Spoelplein|NOTACCESSIBLE|NOTACCESSIBLE
+42009603|Den Haag, Arnold Spoelplein|NOTACCESSIBLE|NOTACCESSIBLE
+42009901|Den Haag, Boslaan|NOTACCESSIBLE|NOTACCESSIBLE
+42009902|Den Haag, Boslaan|NOTACCESSIBLE|NOTACCESSIBLE
+42010101|Den Haag, Bottgerwater|NOTACCESSIBLE|NOTACCESSIBLE
+42010102|Den Haag, Bottgerwater|NOTACCESSIBLE|NOTACCESSIBLE
+42010302|Den Haag, Brouwersgracht|NOTACCESSIBLE|NOTACCESSIBLE
+42010701|Den Haag, Castellum|NOTACCESSIBLE|NOTACCESSIBLE
+42010702|Den Haag, Castellum|NOTACCESSIBLE|NOTACCESSIBLE
+42011102|Den Haag, Dedemsvaartweg|NOTACCESSIBLE|NOTACCESSIBLE
+42011201|Den Haag, Defensive|NOTACCESSIBLE|NOTACCESSIBLE
+42011202|Den Haag, Defensive|NOTACCESSIBLE|NOTACCESSIBLE
+42011401|Den Haag, Dinkel|NOTACCESSIBLE|NOTACCESSIBLE
+42011501|Den Haag, Donau|NOTACCESSIBLE|NOTACCESSIBLE
+42011502|Den Haag, Donau|NOTACCESSIBLE|NOTACCESSIBLE
+42011802|Den Haag, Eendenplein|NOTACCESSIBLE|NOTACCESSIBLE
+42011901|Den Haag, Erasmusplein|NOTACCESSIBLE|NOTACCESSIBLE
+42011902|Den Haag, Erasmusplein|NOTACCESSIBLE|NOTACCESSIBLE
+42012101|Den Haag, Dr. H.E. van Gelderlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42012102|Den Haag, Dr. H.E. van Gelderlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42012301|Den Haag, Gouverneurplein|NOTACCESSIBLE|NOTACCESSIBLE
+42012501|Den Haag, Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
+42012502|Den Haag, Gruttosingel|NOTACCESSIBLE|NOTACCESSIBLE
+42012601|Den Haag, Guirlande|NOTACCESSIBLE|NOTACCESSIBLE
+42012602|Den Haag, Guirlande|NOTACCESSIBLE|NOTACCESSIBLE
+42012702|Den Haag, Guntersteinweg|NOTACCESSIBLE|NOTACCESSIBLE
+42012801|Den Haag, Haeghe Flor|NOTACCESSIBLE|NOTACCESSIBLE
+42012802|Den Haag, Haeghe Flor|NOTACCESSIBLE|NOTACCESSIBLE
+42013101|Den Haag, Haagse Poort|NOTACCESSIBLE|NOTACCESSIBLE
+42013102|Den Haag, Haagse Poort|NOTACCESSIBLE|NOTACCESSIBLE
+42013201|Den Haag, Hoefkade|NOTACCESSIBLE|NOTACCESSIBLE
+42013202|Den Haag, Hoefkade|NOTACCESSIBLE|NOTACCESSIBLE
+42013301|Den Haag, Hofzichtlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42013302|Den Haag, Hofzichtlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42013501|Den Haag, Hobbemastraat|NOTACCESSIBLE|NOTACCESSIBLE
+42013502|Den Haag, Hobbemastraat|NOTACCESSIBLE|NOTACCESSIBLE
+42013801|Den Haag, Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
+42013802|Den Haag, Hoge Veld|NOTACCESSIBLE|NOTACCESSIBLE
+42014101|Den Haag, Juliana van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
+42014102|Den Haag, Juliana van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
+42014601|Den Haag, Lage Veld|NOTACCESSIBLE|NOTACCESSIBLE
+42014602|Den Haag, Lage Veld|NOTACCESSIBLE|NOTACCESSIBLE
+42015001|Den Haag, Leliekeverstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42015002|Den Haag, Leliekeverstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42015601|Den Haag, Loire|NOTACCESSIBLE|NOTACCESSIBLE
+42015602|Den Haag, Loire|NOTACCESSIBLE|NOTACCESSIBLE
+42015801|Den Haag, Laan van 's-Gravenmade|NOTACCESSIBLE|NOTACCESSIBLE
+42015802|Den Haag, Laan van 's-Gravenmade|NOTACCESSIBLE|NOTACCESSIBLE
+42015901|Den Haag, Laan van Hoornwijck|NOTACCESSIBLE|NOTACCESSIBLE
+42015902|Den Haag, Laan van Hoornwijck|NOTACCESSIBLE|NOTACCESSIBLE
+42016101|Den Haag, Laan van Wateringseveld|NOTACCESSIBLE|NOTACCESSIBLE
+42016201|Den Haag, Laan van Ypenburg|NOTACCESSIBLE|NOTACCESSIBLE
+42016202|Den Haag, Laan van Ypenburg|NOTACCESSIBLE|NOTACCESSIBLE
+42016701|Den Haag, Moerweg/Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
+42016702|Den Haag, Moerweg/Melis Stokelaan|NOTACCESSIBLE|NOTACCESSIBLE
+42017002|Den Haag, Laan van Nieuw Oost-Indie|NOTACCESSIBLE|NOTACCESSIBLE
+42017601|Den Haag, Ockenburghstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42017602|Den Haag, Ockenburghstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42017701|Den Haag, Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
+42017702|Den Haag, Oosteinde|NOTACCESSIBLE|NOTACCESSIBLE
+42017901|Den Haag, Parijsplein|NOTACCESSIBLE|NOTACCESSIBLE
+42017902|Den Haag, Parijsplein|NOTACCESSIBLE|NOTACCESSIBLE
+42018201|Den Haag, Paul Steenbergenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42018202|Den Haag, Paul Steenbergenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42018301|Den Haag, Q.A. Nederpelstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42018701|Den Haag, Rotonde Houtkade|NOTACCESSIBLE|NOTACCESSIBLE
+42018702|Den Haag, Rotonde Houtkade|NOTACCESSIBLE|NOTACCESSIBLE
+42019201|Den Haag, Steenhouwersgaarde|NOTACCESSIBLE|NOTACCESSIBLE
+42019401|Poeldijk, Teylingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42019402|Poeldijk, Teylingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42019501|Den Haag, Theems|NOTACCESSIBLE|NOTACCESSIBLE
+42019502|Den Haag, Theems|NOTACCESSIBLE|NOTACCESSIBLE
+42019601|Den Haag, Tiber|NOTACCESSIBLE|NOTACCESSIBLE
+42019602|Den Haag, Tiber|NOTACCESSIBLE|NOTACCESSIBLE
+42020501|Den Haag, Weidevogellaan|NOTACCESSIBLE|NOTACCESSIBLE
+42020502|Den Haag, Weidevogellaan|NOTACCESSIBLE|NOTACCESSIBLE
+42021001|'s-Gravenzande, Aaksterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42021002|'s-Gravenzande, Aaksterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42021101|'s-Gravenzande, Arco|NOTACCESSIBLE|NOTACCESSIBLE
+42021102|'s-Gravenzande, Arco|NOTACCESSIBLE|NOTACCESSIBLE
+42021401|Naaldwijk, Galgeweg|NOTACCESSIBLE|NOTACCESSIBLE
+42021402|Naaldwijk, Galgeweg|NOTACCESSIBLE|NOTACCESSIBLE
+42021501|'s-Gravenzande, Heenweg|NOTACCESSIBLE|NOTACCESSIBLE
+42021502|'s-Gravenzande, Heenweg|NOTACCESSIBLE|NOTACCESSIBLE
+42021602|'s-Gravenzande, Heliotroop|NOTACCESSIBLE|NOTACCESSIBLE
+42021702|'s-Gravenzande, Hoflaan|NOTACCESSIBLE|NOTACCESSIBLE
+42021801|Den Haag, Zichtenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
+42021802|Den Haag, Zichtenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
+42022101|'s-Gravenzande, Maasdijk|NOTACCESSIBLE|NOTACCESSIBLE
+42022102|'s-Gravenzande, Maasdijk|NOTACCESSIBLE|NOTACCESSIBLE
+42022201|'s-Gravenzande, Monsterseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42022202|'s-Gravenzande, Monsterseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42022502|'s-Gravenzande, Strandweg|NOTACCESSIBLE|NOTACCESSIBLE
+42022701|Den Haag, Zuidwerflaan|NOTACCESSIBLE|NOTACCESSIBLE
+42022702|Den Haag, Zuidwerflaan|NOTACCESSIBLE|NOTACCESSIBLE
+42023001|'s-Gravenzande, Vlugtenburg|NOTACCESSIBLE|NOTACCESSIBLE
+42023002|'s-Gravenzande, Vlugtenburg|NOTACCESSIBLE|NOTACCESSIBLE
+42023101|'s-Gravenzande, Villa Ouwendijk|NOTACCESSIBLE|NOTACCESSIBLE
+42023102|'s-Gravenzande, Villa Ouwendijk|NOTACCESSIBLE|NOTACCESSIBLE
+42023202|'s-Gravenzande, Vreeburghlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42023501|Honselersdijk, FloraHolland|NOTACCESSIBLE|NOTACCESSIBLE
+42023502|Honselersdijk, FloraHolland|NOTACCESSIBLE|NOTACCESSIBLE
+42023901|Honselersdijk, Middel Broekweg|NOTACCESSIBLE|NOTACCESSIBLE
+42023902|Honselersdijk, Middel Broekweg|NOTACCESSIBLE|NOTACCESSIBLE
+42024201|Honselersdijk, Nieuweweg|NOTACCESSIBLE|NOTACCESSIBLE
+42024301|Honselersdijk, Oostheullaan|NOTACCESSIBLE|NOTACCESSIBLE
+42024302|Honselersdijk, Oostheullaan|NOTACCESSIBLE|NOTACCESSIBLE
+42024701|Honselersdijk, Westlands Museum|NOTACCESSIBLE|NOTACCESSIBLE
+42024702|Honselersdijk, Westlands Museum|NOTACCESSIBLE|NOTACCESSIBLE
+42026903|Leidschendam, Damlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42027201|Leidschendam, GGZ Haagstreek|NOTACCESSIBLE|NOTACCESSIBLE
+42033901|Maasdijk, Coldenhovelaan|NOTACCESSIBLE|NOTACCESSIBLE
+42033902|Maasdijk, Coldenhovelaan|NOTACCESSIBLE|NOTACCESSIBLE
+42034201|Maasland, Duivenvlugt|NOTACCESSIBLE|NOTACCESSIBLE
+42034202|Maasland, Duivenvlugt|NOTACCESSIBLE|NOTACCESSIBLE
+42034301|Maasland, Hammerdreef|NOTACCESSIBLE|NOTACCESSIBLE
+42034302|Maasland, Hammerdreef|NOTACCESSIBLE|NOTACCESSIBLE
+42034501|Maasland, Kwakelweg|NOTACCESSIBLE|NOTACCESSIBLE
+42034502|Maasland, Kwakelweg|NOTACCESSIBLE|NOTACCESSIBLE
+42034601|Maasland, Lickebaertshoeve|NOTACCESSIBLE|NOTACCESSIBLE
+42034602|Maasland, Lickebaertshoeve|NOTACCESSIBLE|NOTACCESSIBLE
+42034701|Maasland, Maaslandsedam|NOTACCESSIBLE|NOTACCESSIBLE
+42034702|Maasland, Maaslandsedam|NOTACCESSIBLE|NOTACCESSIBLE
+42034801|Maasland, Twee Molens|NOTACCESSIBLE|NOTACCESSIBLE
+42034802|Maasland, Twee Molens|NOTACCESSIBLE|NOTACCESSIBLE
+42035005|Maasland, Viaduct|NOTACCESSIBLE|NOTACCESSIBLE
+42035401|Monster, Burg. Kampschoerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42035402|Monster, Burg. Kampschoerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42035501|Monster, Papelaan|NOTACCESSIBLE|NOTACCESSIBLE
+42035502|Monster, Papelaan|NOTACCESSIBLE|NOTACCESSIBLE
+42035802|Monster, De Tol|NOTACCESSIBLE|NOTACCESSIBLE
+42036101|Monster, Vlotlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42036102|Monster, Vlotlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42036501|Maasdijk, Groeneweg|NOTACCESSIBLE|NOTACCESSIBLE
+42036502|Maasdijk, Groeneweg|NOTACCESSIBLE|NOTACCESSIBLE
+42036601|Maasdijk, Nollaantje|NOTACCESSIBLE|NOTACCESSIBLE
+42036801|Maasdijk, Westerlee|NOTACCESSIBLE|NOTACCESSIBLE
+42036802|Maasdijk, Westerlee|NOTACCESSIBLE|NOTACCESSIBLE
+42039101|Nootdorp, Centrum/Parade|NOTACCESSIBLE|NOTACCESSIBLE
+42039102|Nootdorp, Centrum/Parade|NOTACCESSIBLE|NOTACCESSIBLE
+42039901|Nootdorp, Veenhage|NOTACCESSIBLE|NOTACCESSIBLE
+42039903|Nootdorp, Veenhage|NOTACCESSIBLE|NOTACCESSIBLE
+42040201|Naaldwijk, Grote Achterweg|NOTACCESSIBLE|NOTACCESSIBLE
+42040202|Naaldwijk, Grote Achterweg|NOTACCESSIBLE|NOTACCESSIBLE
+42040301|Naaldwijk, 's-Gravenzandseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42040302|Naaldwijk, 's-Gravenzandseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42040402|Naaldwijk, Hoge Woerd|NOTACCESSIBLE|NOTACCESSIBLE
+42040801|Naaldwijk, Monnikenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42040802|Naaldwijk, Monnikenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041101|Maasdijk, Sint Jorispad|NOTACCESSIBLE|NOTACCESSIBLE
+42041102|Maasdijk, Sint Jorispad|NOTACCESSIBLE|NOTACCESSIBLE
+42041201|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041202|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041203|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041204|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041206|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041207|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041208|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041209|Naaldwijk, Verdilaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041401|Poeldijk, Paul Captijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041402|Poeldijk, Paul Captijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041801|Poeldijk, Dr. Weitjenslaan|NOTACCESSIBLE|NOTACCESSIBLE
+42041802|Poeldijk, Dr. Weitjenslaan|NOTACCESSIBLE|NOTACCESSIBLE
+42042101|Pijnacker, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+42042102|Pijnacker, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+42042201|Pijnacker, Bremlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42042202|Pijnacker, Bremlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42042301|Pijnacker, Burg|NOTACCESSIBLE|NOTACCESSIBLE
+42042302|Pijnacker, Burg|NOTACCESSIBLE|NOTACCESSIBLE
+42042401|Pijnacker, B.V. Mol|NOTACCESSIBLE|NOTACCESSIBLE
+42042402|Pijnacker, B.V. Mol|NOTACCESSIBLE|NOTACCESSIBLE
+42042801|Pijnacker, Groen van Prinstererlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42042802|Pijnacker, Groen van Prinstererlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42043001|Pijnacker, Klein Vlieland|NOTACCESSIBLE|NOTACCESSIBLE
+42043002|Pijnacker, Klein Vlieland|NOTACCESSIBLE|NOTACCESSIBLE
+42043101|Pijnacker, Meersma|NOTACCESSIBLE|NOTACCESSIBLE
+42043102|Pijnacker, Meersma|NOTACCESSIBLE|NOTACCESSIBLE
+42043201|Pijnacker, Molenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42043202|Pijnacker, Molenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42043301|Pijnacker, Mophuis|NOTACCESSIBLE|NOTACCESSIBLE
+42043302|Pijnacker, Mophuis|NOTACCESSIBLE|NOTACCESSIBLE
+42043401|Pijnacker, Nootdorpseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42043701|Pijnacker, Pasteurlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42043702|Pijnacker, Pasteurlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42043801|Pijnacker, Raadhuisplein|NOTACCESSIBLE|NOTACCESSIBLE
+42043802|Pijnacker, Raadhuisplein|NOTACCESSIBLE|NOTACCESSIBLE
+42043901|Pijnacker, Station|NOTACCESSIBLE|NOTACCESSIBLE
+42043902|Pijnacker, Station|NOTACCESSIBLE|NOTACCESSIBLE
+42044101|Pijnacker, van Vuren|NOTACCESSIBLE|NOTACCESSIBLE
+42044102|Pijnacker, van Vuren|NOTACCESSIBLE|NOTACCESSIBLE
+42044303|Rijswijk, Bogaard/Churchilllaan|NOTACCESSIBLE|NOTACCESSIBLE
+42044304|Rijswijk, Bogaard/Churchilllaan|NOTACCESSIBLE|NOTACCESSIBLE
+42044503|Rijswijk, De Bruyn Kopsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42044504|Rijswijk, De Bruyn Kopsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42044901|Rijswijk, 't Haantje|NOTACCESSIBLE|NOTACCESSIBLE
+42045203|Rijswijk, Dr. H.J. van Mooklaan|NOTACCESSIBLE|NOTACCESSIBLE
+42045403|Rijswijk, Station Rijswijk|NOTACCESSIBLE|NOTACCESSIBLE
+42045405|Rijswijk, Station Rijswijk|NOTACCESSIBLE|NOTACCESSIBLE
+42045501|Rijswijk, Laan van Oversteen|NOTACCESSIBLE|NOTACCESSIBLE
+42045502|Rijswijk, Laan van Oversteen|NOTACCESSIBLE|NOTACCESSIBLE
+42045601|Rijswijk, Patentlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42045602|Rijswijk, Patentlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42045901|Rijswijk, Polakweg|NOTACCESSIBLE|NOTACCESSIBLE
+42045902|Rijswijk, Polakweg|NOTACCESSIBLE|NOTACCESSIBLE
+42046101|Rijswijk, Schaapweg|NOTACCESSIBLE|NOTACCESSIBLE
+42046102|Rijswijk, Schaapweg|NOTACCESSIBLE|NOTACCESSIBLE
+42046503|Rijswijk, Treubstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42046603|Rijswijk, Volmerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42046604|Rijswijk, Volmerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42046803|Rijswijk, Verrijn Stuartlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42046804|Rijswijk, Verrijn Stuartlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42047601|Schipluiden, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+42047602|Schipluiden, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+42047701|Schipluiden, Groot Genoeg|NOTACCESSIBLE|NOTACCESSIBLE
+42047702|Schipluiden, Groot Genoeg|NOTACCESSIBLE|NOTACCESSIBLE
+42047801|Schipluiden, Hodenpijl|NOTACCESSIBLE|NOTACCESSIBLE
+42047802|Schipluiden, Hodenpijl|NOTACCESSIBLE|NOTACCESSIBLE
+42047901|Schipluiden, Kolkbrug|NOTACCESSIBLE|NOTACCESSIBLE
+42047902|Schipluiden, Kolkbrug|NOTACCESSIBLE|NOTACCESSIBLE
+42048001|Schipluiden, Lierhand|NOTACCESSIBLE|NOTACCESSIBLE
+42048002|Schipluiden, Lierhand|NOTACCESSIBLE|NOTACCESSIBLE
+42048101|Schipluiden, Molen|NOTACCESSIBLE|NOTACCESSIBLE
+42048102|Schipluiden, Molen|NOTACCESSIBLE|NOTACCESSIBLE
+42048201|Schipluiden, Op Hoop van Zegen|NOTACCESSIBLE|NOTACCESSIBLE
+42048202|Schipluiden, Op Hoop van Zegen|NOTACCESSIBLE|NOTACCESSIBLE
+42048301|Schipluiden, Opslagpl. Rijkswaterstaat|NOTACCESSIBLE|NOTACCESSIBLE
+42048302|Schipluiden, Opslagpl. Rijkswaterstaat|NOTACCESSIBLE|NOTACCESSIBLE
+42048401|Schipluiden, Schouwse Heul|NOTACCESSIBLE|NOTACCESSIBLE
+42048402|Schipluiden, Schouwse Heul|NOTACCESSIBLE|NOTACCESSIBLE
+42048501|Schipluiden, 't Woudt|NOTACCESSIBLE|NOTACCESSIBLE
+42048502|Schipluiden, 't Woudt|NOTACCESSIBLE|NOTACCESSIBLE
+42050402|Voorburg, Heer Hubrechtstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42050701|Voorburg, Laan van Heldenburg|NOTACCESSIBLE|NOTACCESSIBLE
+42050702|Voorburg, Laan van Heldenburg|NOTACCESSIBLE|NOTACCESSIBLE
+42051002|Voorburg, Station Leidschendam/Voorburg|NOTACCESSIBLE|NOTACCESSIBLE
+42051302|Voorburg, Potgieterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42051602|Voorburg, Rozenboomlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42052201|Voorburg, Zwartelaan/Station|NOTACCESSIBLE|NOTACCESSIBLE
+42052202|Voorburg, Zwartelaan/Station|NOTACCESSIBLE|NOTACCESSIBLE
+42055301|Wassenaar, Admiral Helfrichlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42056602|Wassenaar, van Oldenbarneveltweg|NOTACCESSIBLE|NOTACCESSIBLE
+42056604|Wassenaar, van Oldenbarneveltweg|NOTACCESSIBLE|NOTACCESSIBLE
+42056801|Wassenaar, Papegaaienlaan|NOTACCESSIBLE|NOTACCESSIBLE
+42058002|Wassenaar, Wittenburgerweg|NOTACCESSIBLE|NOTACCESSIBLE
+42058801|Zoetermeer, Aluminiumstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42059001|Zoetermeer, Bastionhotel|NOTACCESSIBLE|NOTACCESSIBLE
+42059002|Zoetermeer, Bastionhotel|NOTACCESSIBLE|NOTACCESSIBLE
+42059301|Zoetermeer, Binnenwater|NOTACCESSIBLE|NOTACCESSIBLE
+42059302|Zoetermeer, Binnenwater|NOTACCESSIBLE|NOTACCESSIBLE
+42059401|Zoetermeer, Bordeauxstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42059402|Zoetermeer, Bordeauxstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42059601|Zoetermeer, Cobaltstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42059602|Zoetermeer, Cobaltstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060201|Zoetermeer, Dunantstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060202|Zoetermeer, Dunantstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060401|Zoetermeer, Edelgasstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060402|Zoetermeer, Edelgasstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060501|Zoetermeer, Edisonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060502|Zoetermeer, Edisonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060801|Zoetermeer, Miss Etam|NOTACCESSIBLE|NOTACCESSIBLE
+42060901|Zoetermeer, Frans Halsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42060902|Zoetermeer, Frans Halsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42061201|Zoetermeer, Fonteinbos|NOTACCESSIBLE|NOTACCESSIBLE
+42061401|Zoetermeer, Groenewater|NOTACCESSIBLE|NOTACCESSIBLE
+42061402|Zoetermeer, Groenewater|NOTACCESSIBLE|NOTACCESSIBLE
+42061501|Zoetermeer, van der Hagenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42061502|Zoetermeer, van der Hagenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42061801|Zoetermeer, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
+42061802|Zoetermeer, Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
+42062201|Zoetermeer, Koperstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42062202|Zoetermeer, Koperstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42062401|Zoetermeer, Lansinghageweg|NOTACCESSIBLE|NOTACCESSIBLE
+42062601|Zoetermeer, 't Lange Land Ziekenhuis|NOTACCESSIBLE|NOTACCESSIBLE
+42062801|Zoetermeer, Marconistraat|NOTACCESSIBLE|NOTACCESSIBLE
+42062802|Zoetermeer, Marconistraat|NOTACCESSIBLE|NOTACCESSIBLE
+42063001|Zoetermeer, Metaalstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42063002|Zoetermeer, Metaalstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42063201|Zoetermeer, Newtonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42063202|Zoetermeer, Newtonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42063402|Zoetermeer, Station Oost|NOTACCESSIBLE|NOTACCESSIBLE
+42063403|Zoetermeer, Station Oost|NOTACCESSIBLE|NOTACCESSIBLE
+42063501|Zoetermeer, Station|NOTACCESSIBLE|NOTACCESSIBLE
+42063502|Zoetermeer, Station|NOTACCESSIBLE|NOTACCESSIBLE
+42063701|Zoetermeer, Oostwaarts|NOTACCESSIBLE|NOTACCESSIBLE
+42063702|Zoetermeer, Oostwaarts|NOTACCESSIBLE|NOTACCESSIBLE
+42063901|Zoetermeer, Philipsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42063902|Zoetermeer, Philipsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42064002|Zoetermeer, Poortugaalstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42064301|Zoetermeer, Robijn|NOTACCESSIBLE|NOTACCESSIBLE
+42064401|Zoetermeer, Rokkeveenseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42064402|Zoetermeer, Rokkeveenseweg|NOTACCESSIBLE|NOTACCESSIBLE
+42064501|Zoetermeer, Rokkeveenseweg-zuid|NOTACCESSIBLE|NOTACCESSIBLE
+42064502|Zoetermeer, Rokkeveenseweg-zuid|NOTACCESSIBLE|NOTACCESSIBLE
+42065501|Zoetermeer, Theaterplein|NOTACCESSIBLE|NOTACCESSIBLE
+42065502|Zoetermeer, Theaterplein|NOTACCESSIBLE|NOTACCESSIBLE
+42065801|Zoetermeer, van Galenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42065802|Zoetermeer, van Galenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42066001|Zoetermeer, Vijverhoek|NOTACCESSIBLE|NOTACCESSIBLE
+42066002|Zoetermeer, Vijverhoek|NOTACCESSIBLE|NOTACCESSIBLE
+42066601|Zoetermeer, Zilverstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42066602|Zoetermeer, Zilverstraat|NOTACCESSIBLE|NOTACCESSIBLE
+42068201|Nootdorp, Poort van Nootdorp|NOTACCESSIBLE|NOTACCESSIBLE
+42068202|Nootdorp, Poort van Nootdorp|NOTACCESSIBLE|NOTACCESSIBLE
+42070501|Wateringen, Hoefsmid|NOTACCESSIBLE|NOTACCESSIBLE
+42070901|Den Haag, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+42071101|Den Haag, Dedemvaartweg/Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
+42071102|Den Haag, Dedemvaartweg/Erasmusweg|NOTACCESSIBLE|NOTACCESSIBLE
+42073201|Nootdorp, Kievitsbloem|NOTACCESSIBLE|NOTACCESSIBLE
+42073202|Nootdorp, Kievitsbloem|NOTACCESSIBLE|NOTACCESSIBLE
+54000730|Den Haag, Laan van Clingendael|NOTACCESSIBLE|NOTACCESSIBLE
+54142010|Den Haag, Laan van Clingendael|NOTACCESSIBLE|NOTACCESSIBLE
+54142020|Wassenaar, Rust en Vreugdlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54142050|Wassenaar, Kerkehout|NOTACCESSIBLE|NOTACCESSIBLE
+54142060|Wassenaar, Kerkehout|NOTACCESSIBLE|NOTACCESSIBLE
+54142090|Wassenaar, Houtlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54142100|Wassenaar, Houtlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54240150|Wassenaar, American School|NOTACCESSIBLE|NOTACCESSIBLE
+54240370|Wassenaar, Dr Mansveltkade/Duinrell|NOTACCESSIBLE|NOTACCESSIBLE
+54240380|Wassenaar, Dr Mansveltkade/Duinrell|NOTACCESSIBLE|NOTACCESSIBLE
+54240430|Wassenaar, Johan de Wittstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54240520|Wassenaar, Deijleroord|NOTACCESSIBLE|NOTACCESSIBLE
+54243010|Wassenaar, Rust en Vreugdlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54341010|Wassenaar, Deijleroord|NOTACCESSIBLE|NOTACCESSIBLE
+54410210|Zoetermeer, Boerhaavelaan|NOTACCESSIBLE|NOTACCESSIBLE
+54410220|Zoetermeer, Boerhaavelaan|NOTACCESSIBLE|NOTACCESSIBLE
+54410350|Zoetermeer, Raminhout|NOTACCESSIBLE|NOTACCESSIBLE
+54410360|Zoetermeer, Raminhout|NOTACCESSIBLE|NOTACCESSIBLE
+54410750|Zoetermeer, Osylaan|NOTACCESSIBLE|NOTACCESSIBLE
+54410760|Zoetermeer, Osylaan|NOTACCESSIBLE|NOTACCESSIBLE
+54410830|Zoetermeer, Radonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54410840|Zoetermeer, Radonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54411030|Zoetermeer, Ambachtsherenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411060|Zoetermeer, Station Palenstein|NOTACCESSIBLE|NOTACCESSIBLE
+54411070|Zoetermeer, Van Aalstlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411080|Zoetermeer, Van Aalstlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411270|Zoetermeer, Fokkerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54411280|Zoetermeer, Fokkerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54411290|Zoetermeer, Oostweg|NOTACCESSIBLE|NOTACCESSIBLE
+54411300|Zoetermeer, Oostweg|NOTACCESSIBLE|NOTACCESSIBLE
+54411310|Zoetermeer, Werner von Siemensstr.|NOTACCESSIBLE|NOTACCESSIBLE
+54411390|Zoetermeer, van Diestlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411400|Zoetermeer, van Diestlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411410|Zoetermeer, Vaartdreef|NOTACCESSIBLE|NOTACCESSIBLE
+54411420|Zoetermeer, Vaartdreef|NOTACCESSIBLE|NOTACCESSIBLE
+54411530|Zoetermeer, Meidoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411540|Zoetermeer, Meidoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
+54411560|Zoetermeer, Van Wijngaardenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54412230|Zoetermeer, Franklinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54412240|Zoetermeer, Franklinstraat|NOTACCESSIBLE|NOTACCESSIBLE
+54412260|Zoetermeer, Miss Etam|NOTACCESSIBLE|NOTACCESSIBLE
+54412270|Zoetermeer, Miss Etam|NOTACCESSIBLE|NOTACCESSIBLE
+54413010|Zoetermeer, Muzieklaan|NOTACCESSIBLE|NOTACCESSIBLE
+54413110|Zoetermeer, Marsmanhove|NOTACCESSIBLE|NOTACCESSIBLE
+54413120|Zoetermeer, Marsmanhove|NOTACCESSIBLE|NOTACCESSIBLE
+54413130|Zoetermeer, Aidaschouw|NOTACCESSIBLE|NOTACCESSIBLE
+54413140|Zoetermeer, Aidaschouw|NOTACCESSIBLE|NOTACCESSIBLE
+54415050|Zoetermeer, Mandelabrug/A12/Station|NOTACCESSIBLE|NOTACCESSIBLE
+54415060|Zoetermeer, Mandelabrug/A12/Station|NOTACCESSIBLE|NOTACCESSIBLE
+54415320|Zoetermeer, Werner von Siemensstr.|NOTACCESSIBLE|NOTACCESSIBLE
+54420130|Stompwijk, Meer- en Geerweg|NOTACCESSIBLE|NOTACCESSIBLE
+54420140|Stompwijk, Meer- en Geerweg|NOTACCESSIBLE|NOTACCESSIBLE
+54420160|Zoetermeer, Muzieklaan|NOTACCESSIBLE|NOTACCESSIBLE
+54421030|Stompwijk, Weltevreden|NOTACCESSIBLE|NOTACCESSIBLE
+54421040|Stompwijk, Weltevreden|NOTACCESSIBLE|NOTACCESSIBLE
+54510140|Zoetermeer, W. Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
+54510150|Zoetermeer, W. Dreeslaan|NOTACCESSIBLE|NOTACCESSIBLE
+54510180|Zoetermeer, Benthuizenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50101100|Utrecht-De Uithof, Padualaan|NOTACCESSIBLE|ACCESSIBLE
+50006880|Utrecht, Oudwijkerdwarsstraat|NOTACCESSIBLE|ACCESSIBLE
+50002800|Utrecht, Hijmans v.d Berghlaan|NOTACCESSIBLE|ACCESSIBLE
+59140151|Utrecht, Savannahweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200911|Zeist, Sanatoriumlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59230060|Haarzuilens, Brink|NOTACCESSIBLE|NOTACCESSIBLE
+50000173|Utrecht, Rijnkade|NOTACCESSIBLE|NOTACCESSIBLE
+59152150|Utrecht, Rubicondreef|NOTACCESSIBLE|NOTACCESSIBLE
+59150820|Utrecht, Humberdreef|NOTACCESSIBLE|NOTACCESSIBLE
+51220432|Nieuwegein, Noorderveld|NOTACCESSIBLE|NOTACCESSIBLE
+51220581|Nieuwegein, Groningenhaven|NOTACCESSIBLE|NOTACCESSIBLE
+59490030|Den Dolder, Ernst Sillem Hoeve|NOTACCESSIBLE|NOTACCESSIBLE
+50000650|Utrecht, Oorsprongpark|NOTACCESSIBLE|NOTACCESSIBLE
+59150581|Utrecht, Burg. Van Tuyllkade|NOTACCESSIBLE|NOTACCESSIBLE
+51112000|Utrecht, Vredenburg Leidsche Rijn|NOTACCESSIBLE|NOTACCESSIBLE
+51320320|IJsselstein, Ewoud/Boerhaaveweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220420|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
+51111150|Utrecht, Klifrakplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+51225080|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+50002100|Utrecht, 24 Oktoberplein-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+59250342|Maarssenbroek, Zonnebaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340411|Vianen, Hagenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51380200|Schalkwijk, Ramselaar|NOTACCESSIBLE|NOTACCESSIBLE
+50390130|Odijk, Eikelaar|NOTACCESSIBLE|NOTACCESSIBLE
+50005504|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51111600|Utrecht, Meijewetering|NOTACCESSIBLE|NOTACCESSIBLE
+51320092|IJsselstein, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200510|Zeist, Nijenheim|NOTACCESSIBLE|NOTACCESSIBLE
+50202010|Zeist,  Soc. Werkvoorz. Zeist|NOTACCESSIBLE|NOTACCESSIBLE
+50006522|Utrecht, Texel|NOTACCESSIBLE|NOTACCESSIBLE
+50190120|Utrecht, Ln v Maarschalkerwd|NOTACCESSIBLE|NOTACCESSIBLE
+50003790|Utrecht, Kanaleneiland|NOTACCESSIBLE|NOTACCESSIBLE
+50000830|Utrecht, Majellapark|ACCESSIBLE|NOTACCESSIBLE
+51220920|Nieuwegein, Bernhardstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51110340|De Meern, Esdoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50003100|Utrecht, Dolomieten|ACCESSIBLE|ACCESSIBLE
+50007470|Utrecht, De Hoogstraat|ACCESSIBLE|ACCESSIBLE
+51200130|De Meern, De Balije|ACCESSIBLE|NOTACCESSIBLE
+50000400|Utrecht, Draaiweg|ACCESSIBLE|ACCESSIBLE
+50003040|Utrecht, Robijnlaan|ACCESSIBLE|ACCESSIBLE
+59150250|Utrecht, Klopvaart|ACCESSIBLE|ACCESSIBLE
+50001720|Utrecht, Kapteynlaan|ACCESSIBLE|ACCESSIBLE
+50001650|Utrecht, Pedro Luis Brionstraat|ACCESSIBLE|ACCESSIBLE
+50001670|Utrecht, Simon Bolivarstraat|ACCESSIBLE|ACCESSIBLE
+59150610|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
+51280850|Houten, Rondeel/De Veste|ACCESSIBLE|ACCESSIBLE
+50101090|Utrecht-De Uithof, Padualaan|ACCESSIBLE|ACCESSIBLE
+50003180|Utrecht, Betuwe|ACCESSIBLE|ACCESSIBLE
+51280820|Houten, De Gaarden|ACCESSIBLE|ACCESSIBLE
+50008150|Utrecht, Van Heuven Goedhartlaan|ACCESSIBLE|ACCESSIBLE
+50220170|Bilthoven, Berg en Bosch|ACCESSIBLE|ACCESSIBLE
+59151310|Utrecht, Oderdreef|ACCESSIBLE|ACCESSIBLE
+59200010|Maartensdijk, Groenhorst|ACCESSIBLE|ACCESSIBLE
+50100423|Utrecht, Rijnsweerd Noord|ACCESSIBLE|ACCESSIBLE
+59152100|Utrecht, Loevenhoutsedijk|ACCESSIBLE|ACCESSIBLE
+50001950|Utrecht, Racinelaan|ACCESSIBLE|ACCESSIBLE
+59151250|Utrecht, Theemsdreef|ACCESSIBLE|ACCESSIBLE
+51200410|Vleuten, Rivierkom Noord|NOTACCESSIBLE|NOTACCESSIBLE
+50100140|De Bilt, Alfred Nobellaan|ACCESSIBLE|ACCESSIBLE
+59152030|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
+50001390|Utrecht, Constant Erzeijstraat|ACCESSIBLE|ACCESSIBLE
+51280320|Houten, Bedr. Terr. Meidoornk.|ACCESSIBLE|ACCESSIBLE
+50007440|Utrecht, Rosarium|ACCESSIBLE|ACCESSIBLE
+50000511|Utrecht, Struyckenlaan|ACCESSIBLE|ACCESSIBLE
+59151340|Utrecht, Atlasdreef|ACCESSIBLE|ACCESSIBLE
+59250380|Maarssenbroek, Duiven-Fazantenkamp|ACCESSIBLE|ACCESSIBLE
+50001750|Utrecht, W. de Zwijgerplantsoen|ACCESSIBLE|ACCESSIBLE
+59151970|Utrecht, Amazonedreef|ACCESSIBLE|ACCESSIBLE
+50002840|Utrecht, Alexander Numankade|ACCESSIBLE|ACCESSIBLE
+50006510|Utrecht, Brennerbaan|ACCESSIBLE|ACCESSIBLE
+59152710|Maarssen, Rekreatieoord|ACCESSIBLE|NOTACCESSIBLE
+51280310|Houten, Bedr. Terr. Meidoornk.|ACCESSIBLE|ACCESSIBLE
+50100821|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
+50002590|Utrecht, Marco Pololaan|ACCESSIBLE|ACCESSIBLE
+50220030|Bilthoven, Leijenseweg|ACCESSIBLE|ACCESSIBLE
+50001810|Utrecht, Willem van Noortplein|ACCESSIBLE|ACCESSIBLE
+50002650|Utrecht, Aziëlaan|ACCESSIBLE|ACCESSIBLE
+50006170|Utrecht, Willem Dreeslaan|ACCESSIBLE|ACCESSIBLE
+50220130|Bilthoven, Hobbemalaan|ACCESSIBLE|ACCESSIBLE
+59100070|Groenekan, Centrum|ACCESSIBLE|ACCESSIBLE
+51340242|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
+59250620|Maarssenbroek, Planetenbaan|ACCESSIBLE|ACCESSIBLE
+50003120|Utrecht, Simplonbaan|ACCESSIBLE|ACCESSIBLE
+59150270|Utrecht, Carnegiedreef|ACCESSIBLE|ACCESSIBLE
+50008180|Utrecht, Marshalllaan|ACCESSIBLE|ACCESSIBLE
+50100130|De Bilt, Alfred Nobellaan|ACCESSIBLE|ACCESSIBLE
+59150611|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
+51340234|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
+50002380|Utrecht, Karperstraat|ACCESSIBLE|ACCESSIBLE
+50001700|Utrecht, Kemal Ataturkstraat|ACCESSIBLE|ACCESSIBLE
+59150481|Utrecht, Klopvaart|ACCESSIBLE|ACCESSIBLE
+50003030|Utrecht, Robijnlaan|ACCESSIBLE|ACCESSIBLE
+50002620|Utrecht, Columbuslaan/Afrikalaan|ACCESSIBLE|ACCESSIBLE
+59250391|Maarssenbroek, Duiven-Fazantenkamp|ACCESSIBLE|ACCESSIBLE
+59150210|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
+50220220|Bilthoven, Jan Provostlaan|ACCESSIBLE|ACCESSIBLE
+50006500|Utrecht, Stelviobaan|ACCESSIBLE|ACCESSIBLE
+59150780|Utrecht, Nijldreef|ACCESSIBLE|ACCESSIBLE
+51280680|Houten, Oude Drop|ACCESSIBLE|ACCESSIBLE
+50200900|Zeist, Sanatoriumlaan|ACCESSIBLE|ACCESSIBLE
+50002810|Utrecht, Jan van Galenstraat|ACCESSIBLE|ACCESSIBLE
+50003150|Utrecht, Sleeswijk|ACCESSIBLE|ACCESSIBLE
+50001550|Utrecht, Koningin Wilhelminalaan|ACCESSIBLE|ACCESSIBLE
+50002032|Utrecht, Ziekenhuis Oudenrijn|ACCESSIBLE|ACCESSIBLE
+51280810|Houten, De Erven/De Schaft|ACCESSIBLE|ACCESSIBLE
+51280790|Houten, De Grassen|ACCESSIBLE|ACCESSIBLE
+59150840|Utrecht, Medusadreef|ACCESSIBLE|ACCESSIBLE
+50100200|De Bilt, Dr. Letteplein|ACCESSIBLE|ACCESSIBLE
+51281020|Houten, Odijkseweg|ACCESSIBLE|ACCESSIBLE
+51280430|Houten, De Molen|ACCESSIBLE|ACCESSIBLE
+50201000|Zeist, Heideweg|ACCESSIBLE|ACCESSIBLE
+51280840|Houten, Rondeel/Veste|ACCESSIBLE|ACCESSIBLE
+51110460|De Meern, Boekbinderslaan|ACCESSIBLE|NOTACCESSIBLE
+50001310|Utrecht, Rijnhuizenlaan|ACCESSIBLE|ACCESSIBLE
+50220480|Bilthoven, Berg en Bosch|ACCESSIBLE|ACCESSIBLE
+50200290|Zeist, Hogeweg|ACCESSIBLE|ACCESSIBLE
+50100550|Utrecht-De Uithof, WKZ|ACCESSIBLE|ACCESSIBLE
+50002000|Utrecht, Den Hommel|ACCESSIBLE|ACCESSIBLE
+50008100|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
+50003170|Utrecht, Betuwe|ACCESSIBLE|ACCESSIBLE
+50200090|Zeist, L. Flat|ACCESSIBLE|ACCESSIBLE
+51340244|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
+50008090|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
+51280770|Houten, Elzenkade|ACCESSIBLE|ACCESSIBLE
+59150220|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
+50100660|Bilthoven, Leeuwenhoekln/RIVM|ACCESSIBLE|NOTACCESSIBLE
+50002193|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
+59150710|Utrecht, Ammandreef|ACCESSIBLE|ACCESSIBLE
+59150740|Utrecht, Pekingdreef|ACCESSIBLE|ACCESSIBLE
+50001300|Utrecht, 't Goylaan|ACCESSIBLE|ACCESSIBLE
+50000390|Utrecht, Draaiweg|ACCESSIBLE|ACCESSIBLE
+59150760|Utrecht, Maniladreef|ACCESSIBLE|ACCESSIBLE
+50220240|Bilthoven, Rubenslaan|ACCESSIBLE|ACCESSIBLE
+50000410|Utrecht, Herenweg|ACCESSIBLE|ACCESSIBLE
+50001340|Utrecht, Smaragdplein|ACCESSIBLE|ACCESSIBLE
+50001660|Utrecht, Pedro Luis Brionstraat|ACCESSIBLE|ACCESSIBLE
+59151220|Utrecht, Ziekenhuis Overvecht|ACCESSIBLE|ACCESSIBLE
+50200040|Zeist, Winkelc. Vollenhove|ACCESSIBLE|ACCESSIBLE
+50003050|Utrecht, Slotlaan|ACCESSIBLE|ACCESSIBLE
+50200060|Zeist, Gunninglaan|ACCESSIBLE|ACCESSIBLE
+59200220|Maartensdijk, Fazantlaan|ACCESSIBLE|ACCESSIBLE
+50100810|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
+50000230|Utrecht, Winklerlaan|ACCESSIBLE|ACCESSIBLE
+50100240|Bilthoven, Zonneplein|ACCESSIBLE|ACCESSIBLE
+50001240|Utrecht, Europaplein|ACCESSIBLE|ACCESSIBLE
+50001710|Utrecht, Kapteynlaan|ACCESSIBLE|ACCESSIBLE
+59151370|Utrecht, Berezinadreef|ACCESSIBLE|ACCESSIBLE
+50003090|Utrecht, Dolomieten|ACCESSIBLE|ACCESSIBLE
+50002670|Utrecht, Australiëlaan|ACCESSIBLE|ACCESSIBLE
+51280740|Houten, De Borchen/Doornkade|ACCESSIBLE|ACCESSIBLE
+50006470|Utrecht, Lunettenbaan|ACCESSIBLE|ACCESSIBLE
+51281010|Houten, Kooikerspad|ACCESSIBLE|ACCESSIBLE
+59250411|Maarssenbroek, Pauwen-Reigerskamp|ACCESSIBLE|ACCESSIBLE
+50003110|Utrecht, Simplonbaan|ACCESSIBLE|ACCESSIBLE
+51281030|Houten, Odijkseweg|ACCESSIBLE|ACCESSIBLE
+59150750|Utrecht, Maniladreef|ACCESSIBLE|ACCESSIBLE
+50001680|Utrecht, Simon Bolivarstraat|ACCESSIBLE|ACCESSIBLE
+50007410|Utrecht, Prinsesselaan|ACCESSIBLE|ACCESSIBLE
+50220260|Bilthoven, Rubenslaan|ACCESSIBLE|ACCESSIBLE
+51280640|Houten, De Meren|ACCESSIBLE|NOTACCESSIBLE
+50006910|Utrecht, Homeruslaan|ACCESSIBLE|ACCESSIBLE
+51114350|Utrecht, Station Terwijde|ACCESSIBLE|NOTACCESSIBLE
+51280730|Houten, De Veste/De Slagen|ACCESSIBLE|ACCESSIBLE
+50007430|Utrecht, Rosarium|ACCESSIBLE|ACCESSIBLE
+50000250|Utrecht, De Lichtkring|ACCESSIBLE|ACCESSIBLE
+59151210|Utrecht, Ziekenhuis Overvecht|ACCESSIBLE|ACCESSIBLE
+50008170|Utrecht, Marshalllaan|ACCESSIBLE|ACCESSIBLE
+50002610|Utrecht, Columbuslaan/Afrikalaan|ACCESSIBLE|ACCESSIBLE
+50006480|Utrecht, Lunettenbaan|ACCESSIBLE|ACCESSIBLE
+50008160|Utrecht, Van Heuven Goedhartlaan|ACCESSIBLE|ACCESSIBLE
+51280590|Houten, Molenzoom|ACCESSIBLE|ACCESSIBLE
+59155000|Utrecht, Station Overvecht|ACCESSIBLE|ACCESSIBLE
+59150190|Utrecht, Sint Maartendreef|ACCESSIBLE|ACCESSIBLE
+51281000|Houten, Kooikerspad|ACCESSIBLE|ACCESSIBLE
+50001360|Utrecht, Tolsteegplantsoen|ACCESSIBLE|ACCESSIBLE
+51340231|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
+50006150|Utrecht, Kardinaal de Jongweg|ACCESSIBLE|ACCESSIBLE
+50100440|Utrecht, Rijnsweerd Zuid|ACCESSIBLE|NOTACCESSIBLE
+50001160|Utrecht, Diakonessenhuis|ACCESSIBLE|ACCESSIBLE
+59150410|Utrecht, Einsteindreef|ACCESSIBLE|ACCESSIBLE
+50008070|Utrecht, Vrieslantlaan|ACCESSIBLE|ACCESSIBLE
+50000220|Utrecht, Willem Dreeslaan|ACCESSIBLE|ACCESSIBLE
+59250630|Maarssenbroek, Planetenbaan|ACCESSIBLE|ACCESSIBLE
+50000330|Utrecht, Wittevrouwenbrug|ACCESSIBLE|ACCESSIBLE
+50007070|Utrecht, Nijverheidsweg|ACCESSIBLE|ACCESSIBLE
+59151290|Utrecht, Neckardreef|ACCESSIBLE|ACCESSIBLE
+50001960|Utrecht, Racinelaan|ACCESSIBLE|ACCESSIBLE
+50002570|Utrecht, Rooseveltlaan|ACCESSIBLE|ACCESSIBLE
+59151260|Utrecht, Theemsdreef|ACCESSIBLE|ACCESSIBLE
+50001980|Utrecht, Everard Meysterlaan|ACCESSIBLE|NOTACCESSIBLE
+50002111|Utrecht, Loevenhoutsedijk|ACCESSIBLE|ACCESSIBLE
+59150790|Utrecht, Oranjerivierdreef|ACCESSIBLE|ACCESSIBLE
+50007480|Utrecht, De Hoogstraat|ACCESSIBLE|ACCESSIBLE
+50100290|Bilthoven, Konijnenlaan|ACCESSIBLE|ACCESSIBLE
+59150260|Utrecht, Klopvaart|ACCESSIBLE|ACCESSIBLE
+59100210|Utrecht, Vulcanusdreef|ACCESSIBLE|ACCESSIBLE
+59150200|Utrecht, Sint Maartendreef|ACCESSIBLE|ACCESSIBLE
+59252031|Maarssenbroek, Pauwen-Reigerskamp|ACCESSIBLE|ACCESSIBLE
+59252005|Maarssenbroek, Spechten-Valkenkamp|ACCESSIBLE|ACCESSIBLE
+50200070|Zeist, Gunninglaan|ACCESSIBLE|ACCESSIBLE
+50002600|Utrecht, Marco Pololaan|ACCESSIBLE|ACCESSIBLE
+50100300|Bilthoven, Konijnenlaan|ACCESSIBLE|ACCESSIBLE
+59150730|Utrecht, Pekingdreef|ACCESSIBLE|ACCESSIBLE
+50006490|Utrecht, Stelviobaan|ACCESSIBLE|ACCESSIBLE
+50001530|Utrecht, Europaplein|ACCESSIBLE|ACCESSIBLE
+50001820|Utrecht, Willem van Noortplein|ACCESSIBLE|ACCESSIBLE
+50001400|Utrecht, Constant Erzeijstraat|ACCESSIBLE|ACCESSIBLE
+59250120|Maarssen, Dr. Plesmanlaan|ACCESSIBLE|ACCESSIBLE
+51280720|Houten, De Veste/De Slagen|ACCESSIBLE|ACCESSIBLE
+59151300|Utrecht, Neckardreef|ACCESSIBLE|ACCESSIBLE
+51340243|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
+50000200|Utrecht, Vulcanusdreef|ACCESSIBLE|ACCESSIBLE
+59250752|Maarssenbroek, Verbindingsweg|ACCESSIBLE|NOTACCESSIBLE
+50002710|Utrecht, Medusadreef|ACCESSIBLE|ACCESSIBLE
+59151980|Utrecht, Amazonedreef|ACCESSIBLE|ACCESSIBLE
+59250150|Maarssen, Maria Dommerstichting|ACCESSIBLE|ACCESSIBLE
+50220120|Bilthoven, Hobbemalaan|ACCESSIBLE|ACCESSIBLE
+59150720|Utrecht, Ammandreef|ACCESSIBLE|ACCESSIBLE
+50002820|Utrecht, Jan van Galenstraat|ACCESSIBLE|ACCESSIBLE
+50007120|Utrecht, Spinozaweg|ACCESSIBLE|ACCESSIBLE
+50200360|Zeist, Heerewegen|ACCESSIBLE|NOTACCESSIBLE
+50100811|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
+50002660|Utrecht, Aziëlaan|ACCESSIBLE|ACCESSIBLE
+51280630|Houten, De Mossen|ACCESSIBLE|ACCESSIBLE
+50003160|Utrecht, Sleeswijk|ACCESSIBLE|ACCESSIBLE
+50006860|Utrecht, Burg. Reigerstraat|ACCESSIBLE|ACCESSIBLE
+51280710|Houten, De Staart|ACCESSIBLE|ACCESSIBLE
+51280530|Houten, Koedijk|ACCESSIBLE|ACCESSIBLE
+51280700|Houten, De Staart|ACCESSIBLE|ACCESSIBLE
+50008030|Utrecht, David Ben Goerionstraat|ACCESSIBLE|ACCESSIBLE
+50001560|Utrecht, Koningin Wilhelminalaan|ACCESSIBLE|ACCESSIBLE
+50001770|Utrecht, Prof. Leonard Fuchslaan|ACCESSIBLE|ACCESSIBLE
+50002830|Utrecht, Alexander Numankade|ACCESSIBLE|ACCESSIBLE
+51280670|Houten, De Tuinen/Kruisboog|ACCESSIBLE|ACCESSIBLE
+59150221|Utrecht, Zamenhofdreef|ACCESSIBLE|ACCESSIBLE
+50006850|Utrecht, Burg. Reigerstraat|ACCESSIBLE|ACCESSIBLE
+50007090|Utrecht, Schepenbuurt|ACCESSIBLE|ACCESSIBLE
+50220150|Bilthoven, Albert Cuyplaan|ACCESSIBLE|ACCESSIBLE
+50000260|Utrecht, De Lichtkring|ACCESSIBLE|ACCESSIBLE
+59250130|Maarssen, Dr. Plesmanlaan|ACCESSIBLE|ACCESSIBLE
+51340233|Vianen, Busstation Lekbrug|ACCESSIBLE|ACCESSIBLE
+59250140|Maarssen, Maria Dommerstichting|ACCESSIBLE|ACCESSIBLE
+50008130|Utrecht, Ziekenhuis Oudenrijn|ACCESSIBLE|ACCESSIBLE
+50002042|Utrecht, Ziekenhuis Oudenrijn|ACCESSIBLE|ACCESSIBLE
+59200230|Maartensdijk, Fazantlaan|ACCESSIBLE|ACCESSIBLE
+50002790|Utrecht, Hijmans v.d. Berghlaan|ACCESSIBLE|ACCESSIBLE
+50220200|Bilthoven, Jan Provostlaan|ACCESSIBLE|ACCESSIBLE
+50002560|Utrecht, Van Bijnkershoeklaan|ACCESSIBLE|ACCESSIBLE
+50100230|Bilthoven, Zonneplein|ACCESSIBLE|ACCESSIBLE
+50000280|Utrecht, Prof. Dieperinklaan|ACCESSIBLE|ACCESSIBLE
+50001970|Utrecht, Everard Meysterlaan|ACCESSIBLE|NOTACCESSIBLE
+50002390|Utrecht, Kastelenplantsoen|ACCESSIBLE|ACCESSIBLE
+50001350|Utrecht, Tolsteegplantsoen|ACCESSIBLE|ACCESSIBLE
+50008050|Utrecht, IJsselsteinlaan|ACCESSIBLE|ACCESSIBLE
+51110450|De Meern, Boekbinderslaan|ACCESSIBLE|NOTACCESSIBLE
+50006920|Utrecht, Homeruslaan|ACCESSIBLE|ACCESSIBLE
+59250740|Maarssenbroek, Verbindingsweg|ACCESSIBLE|NOTACCESSIBLE
+50200050|Zeist, Winkelc. Vollenhove|ACCESSIBLE|ACCESSIBLE
+51280750|Houten, De Borchen/Doornkade|ACCESSIBLE|ACCESSIBLE
+51280431|Houten, De Molen|ACCESSIBLE|ACCESSIBLE
+50000270|Utrecht, Prof. Dieperinklaan|ACCESSIBLE|ACCESSIBLE
+50002550|Utrecht, Van Bijnkershoeklaan|ACCESSIBLE|ACCESSIBLE
+59252029|Maarssenbroek, Spechten-Valkenkamp|ACCESSIBLE|ACCESSIBLE
+50220140|Bilthoven, Albert Cuyplaan|ACCESSIBLE|ACCESSIBLE
+50007500|Utrecht, Hobbemastraat|ACCESSIBLE|ACCESSIBLE
+50220285|Bilthoven, Sperwerlaan|ACCESSIBLE|ACCESSIBLE
+51220720|Nieuwegein, Postkantoor|ACCESSIBLE|ACCESSIBLE
+50200080|Zeist, L. Flat|ACCESSIBLE|ACCESSIBLE
+50006520|Utrecht, Brennerbaan|ACCESSIBLE|ACCESSIBLE
+50100820|Utrecht-De Uithof, Heidelberglaan|ACCESSIBLE|ACCESSIBLE
+50006160|Utrecht, Kardinaal de Jongweg|ACCESSIBLE|ACCESSIBLE
+59150800|Utrecht, Oranjerivierdreef|ACCESSIBLE|ACCESSIBLE
+50001320|Utrecht, Rijnhuizenlaan|ACCESSIBLE|ACCESSIBLE
+50100670|Bilthoven, Leeuwenhoekln/RIVM|ACCESSIBLE|NOTACCESSIBLE
+50007510|Utrecht, Hobbemastraat|ACCESSIBLE|ACCESSIBLE
+50220020|Bilthoven, Leijenseweg|ACCESSIBLE|ACCESSIBLE
+51280830|Houten, De Gaarden|ACCESSIBLE|ACCESSIBLE
+51280800|Houten, De Erven/De Schaft|ACCESSIBLE|ACCESSIBLE
+50003060|Utrecht, Slotlaan|ACCESSIBLE|ACCESSIBLE
+50002680|Utrecht, Zeelantlaan|ACCESSIBLE|ACCESSIBLE
+50100160|De Bilt, Hessenweg|ACCESSIBLE|ACCESSIBLE
+59152130|Utrecht, Korfoedreef|NOTACCESSIBLE|NOTACCESSIBLE
+51340120|Vianen, Marienhof|NOTACCESSIBLE|NOTACCESSIBLE
+50200870|Zeist, Van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
+50006670|Utrecht, Catharijneconvent|NOTACCESSIBLE|NOTACCESSIBLE
+50201050|Zeist, Verzetslaan|NOTACCESSIBLE|NOTACCESSIBLE
+51110190|Vleuten, Dorpsplein|NOTACCESSIBLE|NOTACCESSIBLE
+51200400|Haarzuilens, Thematerweg|NOTACCESSIBLE|NOTACCESSIBLE
+51340431|Vianen, Lange Dreef|NOTACCESSIBLE|NOTACCESSIBLE
+59250491|Maarssenbroek, Kamelenspoor|NOTACCESSIBLE|NOTACCESSIBLE
+50002080|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000581|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200040|Hollandsche Rading, Tolakkerweg 57|NOTACCESSIBLE|NOTACCESSIBLE
+51220890|Nieuwegein, B.J.Buurmanstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220871|Nieuwegein, Doorslag|NOTACCESSIBLE|NOTACCESSIBLE
+59390100|Huis ter Heide, Van Ostadelaan|NOTACCESSIBLE|NOTACCESSIBLE
+59230100|Haarzuilens, Gieltjesdorp|NOTACCESSIBLE|NOTACCESSIBLE
+50001111|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+59150500|Utrecht, Cornelis Smeenkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51380320|'t Goy, Wickenburghseweg|NOTACCESSIBLE|NOTACCESSIBLE
+51111590|Utrecht, Meijewetering|NOTACCESSIBLE|NOTACCESSIBLE
+50200011|Zeist, Jordanlaan/Kroostweg|NOTACCESSIBLE|NOTACCESSIBLE
+51180031|Nieuwegein, De Liesbosch|NOTACCESSIBLE|NOTACCESSIBLE
+59151280|Utrecht, Landskroondreef|NOTACCESSIBLE|NOTACCESSIBLE
+51220170|Nieuwegein, Landmansweide|NOTACCESSIBLE|NOTACCESSIBLE
+50220340|Bilthoven, Winkelc. Kwinkelier|NOTACCESSIBLE|NOTACCESSIBLE
+51380240|Schalkwijk, De Heul|NOTACCESSIBLE|NOTACCESSIBLE
+51380170|Schalkwijk, Ramselaar|NOTACCESSIBLE|NOTACCESSIBLE
+50006340|Utrecht, Van der Goesstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220031|Nieuwegein, Postkantoor|NOTACCESSIBLE|NOTACCESSIBLE
+51110510|De Meern, Zuiderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
+50005514|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51341210|Vianen, Hoeufftlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50001290|Utrecht, 't Goylaan|NOTACCESSIBLE|NOTACCESSIBLE
+50001020|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
+50005300|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
+59140040|Utrecht, Thoriumweg|NOTACCESSIBLE|NOTACCESSIBLE
+51200212|Vleuten, Sparrendaal|NOTACCESSIBLE|NOTACCESSIBLE
+50001230|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
+50200230|Zeist, Steynlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200330|Zeist, Louise de Colignypl.|NOTACCESSIBLE|NOTACCESSIBLE
+51380040|Schalkwijk, Korte Uitweg|NOTACCESSIBLE|NOTACCESSIBLE
+50006710|Utrecht, Centraal Museum|NOTACCESSIBLE|NOTACCESSIBLE
+59150501|Utrecht, Cornelis Smeenkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50001540|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
+51320100|IJsselstein, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
+51320130|IJsselstein, Binnenstad|NOTACCESSIBLE|NOTACCESSIBLE
+50100531|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
+51380100|Schalkwijk, Wickenburghselaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100210|Bilthoven, Groenekanseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200370|Zeist, Heerewegen|NOTACCESSIBLE|NOTACCESSIBLE
+51220800|Nieuwegein, Randijk|NOTACCESSIBLE|NOTACCESSIBLE
+50003610|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59250100|Maarssen, Winkelcentrum|NOTACCESSIBLE|NOTACCESSIBLE
+51111140|Utrecht, Archeologiepark|NOTACCESSIBLE|NOTACCESSIBLE
+50290130|Bunnik, Van Zijldreef|NOTACCESSIBLE|NOTACCESSIBLE
+50002131|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50390150|Odijk, Gaspeldoorn|NOTACCESSIBLE|NOTACCESSIBLE
+59150290|Utrecht, Daelwijck|NOTACCESSIBLE|NOTACCESSIBLE
+51220601|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
+50220080|Bilthoven, Soestdijkseweg-Noord|NOTACCESSIBLE|NOTACCESSIBLE
+59140120|Utrecht, Hyperonenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220071|Nieuwegein, Zorgcentrum Zuilenstein|NOTACCESSIBLE|NOTACCESSIBLE
+51220460|Nieuwegein, Buys Ballotbaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220621|Nieuwegein, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
+50390200|Odijk, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
+51220440|Nieuwegein, Noorderveld|NOTACCESSIBLE|NOTACCESSIBLE
+50201370|Zeist, Dijnselburg|NOTACCESSIBLE|NOTACCESSIBLE
+59200210|Maartensdijk, Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
+59330080|Kockengen, Wethouder Van Doornweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000920|Utrecht, Station Zuilen|NOTACCESSIBLE|NOTACCESSIBLE
+50000152|Utrecht, Voorstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51221031|Nieuwegein, Fokkesteeg|NOTACCESSIBLE|NOTACCESSIBLE
+51220650|Nieuwegein, Binnenwal|NOTACCESSIBLE|NOTACCESSIBLE
+59250550|Maarssenbroek, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200660|Zeist, Weeshuislaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100350|De Bilt, Burg. de Withstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50201100|Zeist, Handelscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+51340080|Vianen, Augustinushof|NOTACCESSIBLE|NOTACCESSIBLE
+50320010|Huis ter Heide, Prins Alexanderweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200310|Zeist, Amandelhof|NOTACCESSIBLE|NOTACCESSIBLE
+50205010|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
+51222210|Nieuwegein, Blokhoeve Noord|NOTACCESSIBLE|NOTACCESSIBLE
+50006540|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
+50100070|De Bilt, Tunneltje de Bilt|NOTACCESSIBLE|NOTACCESSIBLE
+50100430|Utrecht, Rijnsweerd Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+51285010|Houten, Station|NOTACCESSIBLE|NOTACCESSIBLE
+59150310|Maarssen, De Malle Jan|NOTACCESSIBLE|NOTACCESSIBLE
+51380080|Schalkwijk, Kloostergaarde|NOTACCESSIBLE|NOTACCESSIBLE
+51220910|Nieuwegein, Bernhardstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50006130|Utrecht, Mr. Tripkade|NOTACCESSIBLE|NOTACCESSIBLE
+50000860|Utrecht, Bleekstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59250810|Maarssen, Sportpark Oostwaard|NOTACCESSIBLE|NOTACCESSIBLE
+50290060|Bunnik, Kosterijland|NOTACCESSIBLE|NOTACCESSIBLE
+50100280|Bilthoven, Duivenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50003333|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50001000|Utrecht, Sterrenwijk|NOTACCESSIBLE|NOTACCESSIBLE
+50200720|Zeist, Prof.Lorentzln.-Zkh.|NOTACCESSIBLE|NOTACCESSIBLE
+50006410|Utrecht, Maasplein|NOTACCESSIBLE|NOTACCESSIBLE
+50001830|Utrecht, Willem van Noortstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50003070|Utrecht, Brennerbrug|NOTACCESSIBLE|NOTACCESSIBLE
+50200460|Zeist, Brugakker|NOTACCESSIBLE|NOTACCESSIBLE
+51340091|Vianen, Augustinushof|NOTACCESSIBLE|NOTACCESSIBLE
+59151960|Utrecht, Bogotadreef|NOTACCESSIBLE|NOTACCESSIBLE
+59151590|Utrecht, Prins Bernhardlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111560|Utrecht, Musicalkade|NOTACCESSIBLE|NOTACCESSIBLE
+51340051|Vianen, Clarissenhof|NOTACCESSIBLE|NOTACCESSIBLE
+59200160|Maartensdijk, Tuinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59152700|Maarssen, Herenweg|NOTACCESSIBLE|NOTACCESSIBLE
+59150180|Utrecht, Gageldijk 97|NOTACCESSIBLE|NOTACCESSIBLE
+50100590|De Bilt,  Grontmij Houdringe|NOTACCESSIBLE|NOTACCESSIBLE
+50100120|Zeist, Jordanlaan/Kroostweg|NOTACCESSIBLE|NOTACCESSIBLE
+51340092|Vianen, Augustinushof|NOTACCESSIBLE|NOTACCESSIBLE
+51220212|Nieuwegein, De Baten|NOTACCESSIBLE|NOTACCESSIBLE
+50007170|Utrecht, Jan Pietersz. Coenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51320050|IJsselstein, Mandenmaker|NOTACCESSIBLE|NOTACCESSIBLE
+51220572|Nieuwegein, Groningenhaven|NOTACCESSIBLE|NOTACCESSIBLE
+59150590|Utrecht, Jan van Zutphenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200300|Maartensdijk, Rotonde-Noord|NOTACCESSIBLE|NOTACCESSIBLE
+50200951|Zeist, Van Renesselaan|NOTACCESSIBLE|NOTACCESSIBLE
+50003370|Utrecht, Janskerkhof|NOTACCESSIBLE|NOTACCESSIBLE
+51345550|Vianen, Eendrachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000520|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200170|Maartensdijk, Tuinlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111190|Utrecht, De Woerd|NOTACCESSIBLE|NOTACCESSIBLE
+51200330|Vleuten, Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59100020|Maartensdijk, Achterwetering|NOTACCESSIBLE|NOTACCESSIBLE
+50003260|Utrecht, Afrikalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200840|Zeist, Graaf Adolflaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250231|Maarssen, Raadhuisstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50001790|Utrecht, Ingenhouszstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59200130|Maartensdijk, Mauritshoeve|NOTACCESSIBLE|NOTACCESSIBLE
+51380230|Schalkwijk, Viadukt|NOTACCESSIBLE|NOTACCESSIBLE
+59151350|Utrecht, Donaudreef|NOTACCESSIBLE|NOTACCESSIBLE
+51320040|IJsselstein, Europalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50003190|Utrecht, Station Lunetten|NOTACCESSIBLE|NOTACCESSIBLE
+51110370|De Meern, Sligro|NOTACCESSIBLE|NOTACCESSIBLE
+50200030|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|NOTACCESSIBLE
+50000190|Utrecht, Vredenburgviaduct|NOTACCESSIBLE|NOTACCESSIBLE
+50002510|Utrecht, Ravellaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340290|Vianen, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+59390040|Huis ter Heide, Park  Rodichem|NOTACCESSIBLE|NOTACCESSIBLE
+51325500|IJsselstein, Binnenstad|NOTACCESSIBLE|NOTACCESSIBLE
+50000570|Utrecht, David van Mollemstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50000850|Utrecht, Bleekstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50320040|Huis ter Heide, Sterrenberg|NOTACCESSIBLE|NOTACCESSIBLE
+50003540|Utrecht, Ina Boudier Bakkerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340010|Vianen, Hotel Vianen|NOTACCESSIBLE|NOTACCESSIBLE
+50003660|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
+50000002|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51200420|Vleuten, Rivierkom Noord|NOTACCESSIBLE|NOTACCESSIBLE
+51200290|Vleuten, Vrijthof|NOTACCESSIBLE|NOTACCESSIBLE
+51110210|Vleuten, Henri Dunantlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51380360|'t Goy, Oostrumsdijkje|NOTACCESSIBLE|NOTACCESSIBLE
+50002040|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+59151810|Utrecht, Oregondreef|NOTACCESSIBLE|NOTACCESSIBLE
+50001470|Utrecht, Oudenoord|NOTACCESSIBLE|NOTACCESSIBLE
+50002160|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+50000682|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
+51110350|De Meern, Esdoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200710|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000440|Utrecht, Viaduct|NOTACCESSIBLE|NOTACCESSIBLE
+51380050|Schalkwijk, Jhr. Ramweg|NOTACCESSIBLE|NOTACCESSIBLE
+59200050|Hollandsche Rading, Plantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+50002120|Utrecht, 5 Mei Plein|NOTACCESSIBLE|NOTACCESSIBLE
+59250730|Maarssen, Cramerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250190|Maarssen, Thorbeckelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220692|Nieuwegein, Herman Heijermanshove|NOTACCESSIBLE|NOTACCESSIBLE
+51320061|IJsselstein, Mandenmaker|NOTACCESSIBLE|NOTACCESSIBLE
+59200190|Maartensdijk, Koningin Julianalaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220111|Nieuwegein, Galecopperdijk|NOTACCESSIBLE|NOTACCESSIBLE
+50201340|Zeist, Schaerweydelaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200380|Zeist, Prinses Margrietlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200250|Maartensdijk, Valklaan|NOTACCESSIBLE|NOTACCESSIBLE
+59140220|Utrecht, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+51110050|De Meern, Strijkviertel|NOTACCESSIBLE|NOTACCESSIBLE
+50200740|Zeist, Jagersingel|NOTACCESSIBLE|NOTACCESSIBLE
+59250670|Maarssenbroek, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220100|Nieuwegein, Galecopperdijk|NOTACCESSIBLE|NOTACCESSIBLE
+50003630|Utrecht, Ondiep|NOTACCESSIBLE|NOTACCESSIBLE
+59230140|Haarzuilens, Ockhuizerweg|NOTACCESSIBLE|NOTACCESSIBLE
+59200100|Maartensdijk, Rotonde-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+50002240|Utrecht, Nicolaas Beetsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50007160|Utrecht, Billitonkade|NOTACCESSIBLE|NOTACCESSIBLE
+50000070|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
+50220165|Bilthoven, Boslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50320030|Huis ter Heide, Dolderseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100260|Bilthoven, Poolsterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000720|Utrecht, P+R Veemarkt|NOTACCESSIBLE|NOTACCESSIBLE
+59150340|Utrecht, Muyskenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51280030|Houten, Prov.weg/Doornkade|NOTACCESSIBLE|NOTACCESSIBLE
+50100420|Utrecht, Rijnsweerd Noord|NOTACCESSIBLE|NOTACCESSIBLE
+50001440|Utrecht, Rozenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59152060|Utrecht, Taagdreef|NOTACCESSIBLE|NOTACCESSIBLE
+51200340|Vleuten, Albert Schweitzerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000341|Utrecht, Wittevrouwenbrug|NOTACCESSIBLE|NOTACCESSIBLE
+51221080|Nieuwegein, Rembrandthage|NOTACCESSIBLE|NOTACCESSIBLE
+59100040|Maartensdijk, Nieuwe-Wetering|NOTACCESSIBLE|NOTACCESSIBLE
+59250211|Maarssen, Parkweg|NOTACCESSIBLE|NOTACCESSIBLE
+51221420|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
+59152140|Utrecht, Korfoedreef|NOTACCESSIBLE|NOTACCESSIBLE
+50001460|Utrecht, Sint Jacobsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59150530|Utrecht, Prins Bernhardplein|NOTACCESSIBLE|NOTACCESSIBLE
+50101040|Utrecht, De Kromme Rijn|NOTACCESSIBLE|NOTACCESSIBLE
+50007111|Utrecht, Spinozaweg|NOTACCESSIBLE|NOTACCESSIBLE
+59390140|Den Dolder, Pleineslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50201460|Zeist, Geroplein|NOTACCESSIBLE|NOTACCESSIBLE
+50190090|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
+51380260|Schalkwijk, Viadukt|NOTACCESSIBLE|NOTACCESSIBLE
+59150450|Utrecht, De Bazelstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51180020|Nieuwegein, De Liesbosch|NOTACCESSIBLE|NOTACCESSIBLE
+51320410|IJsselstein, Lagebiezen|NOTACCESSIBLE|NOTACCESSIBLE
+50101030|Utrecht, De Kromme Rijn|NOTACCESSIBLE|NOTACCESSIBLE
+50200750|Zeist, Jagersingel|NOTACCESSIBLE|NOTACCESSIBLE
+50001220|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+59200240|Maartensdijk, Valklaan|NOTACCESSIBLE|NOTACCESSIBLE
+59150910|Utrecht, Station Zuilen|NOTACCESSIBLE|NOTACCESSIBLE
+51340350|Vianen, v.Duvenvoordestraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220280|Nieuwegein, Calscollege|NOTACCESSIBLE|NOTACCESSIBLE
+51220260|Nieuwegein, Noordstedeweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000480|Utrecht, Watertoren|NOTACCESSIBLE|NOTACCESSIBLE
+51380140|Schalkwijk, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
+59151302|Utrecht, Tamarinde|NOTACCESSIBLE|NOTACCESSIBLE
+50201240|Zeist,  Woudschoten|NOTACCESSIBLE|NOTACCESSIBLE
+51120010|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
+51220561|Nieuwegein, Brabanthaven|NOTACCESSIBLE|NOTACCESSIBLE
+50007050|Utrecht, Gietijzerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50008020|Utrecht, Schaverijstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59151770|Utrecht, Franciscusdreef|NOTACCESSIBLE|NOTACCESSIBLE
+51340330|Vianen, Brugstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220340|Nieuwegein, H.Heijermanshove|NOTACCESSIBLE|NOTACCESSIBLE
+50200830|Zeist, Pr. Margrietlaan 235|NOTACCESSIBLE|NOTACCESSIBLE
+50310120|Austerlitz, Traayweg|NOTACCESSIBLE|NOTACCESSIBLE
+50001860|Utrecht, Adelaarstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51111310|Utrecht, Korianderstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50001370|Utrecht, Vondellaan|NOTACCESSIBLE|NOTACCESSIBLE
+51320080|IJsselstein, Televisiebaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340420|Vianen, Hagenweg|NOTACCESSIBLE|NOTACCESSIBLE
+59140210|Utrecht, Niels Bohrweg|NOTACCESSIBLE|NOTACCESSIBLE
+50002250|Utrecht, Hoogh Boulandt|NOTACCESSIBLE|NOTACCESSIBLE
+50006650|Utrecht, Hamburgerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51340150|Vianen, Weidekamp|NOTACCESSIBLE|NOTACCESSIBLE
+50201520|Zeist, Lageweg/Waterigeweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000350|Utrecht, Stadsschouwburg|NOTACCESSIBLE|NOTACCESSIBLE
+51220591|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
+50220110|Bilthoven, Van der Helstlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100532|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
+59152160|Utrecht, Rubicondreef|NOTACCESSIBLE|NOTACCESSIBLE
+50201220|Zeist, Alg. Begraafplaats|NOTACCESSIBLE|NOTACCESSIBLE
+59252023|Maarssenbroek, Zebraspoor|NOTACCESSIBLE|NOTACCESSIBLE
+51340340|Vianen, Brugstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51340130|Vianen, 't Zand|NOTACCESSIBLE|NOTACCESSIBLE
+51220900|Nieuwegein, B.J.Buurmanstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59250770|Maarssenbroek, Niels Bohrweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000001|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50290070|Bunnik, Kosterijland|NOTACCESSIBLE|NOTACCESSIBLE
+51220051|Nieuwegein, Wenckebachplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+51280760|Houten, Elzenkade|NOTACCESSIBLE|NOTACCESSIBLE
+50000370|Utrecht, Janskerkhof|NOTACCESSIBLE|NOTACCESSIBLE
+59150170|Utrecht, Gageldijk 97|NOTACCESSIBLE|NOTACCESSIBLE
+51221050|Nieuwegein, Gerbrandypark|NOTACCESSIBLE|NOTACCESSIBLE
+51111010|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
+50005503|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51320091|IJsselstein, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000300|Utrecht, Eykmanplein|NOTACCESSIBLE|NOTACCESSIBLE
+59150130|Maarssen, Gageldijk 41|NOTACCESSIBLE|NOTACCESSIBLE
+50007100|Utrecht, Schepenbuurt|NOTACCESSIBLE|NOTACCESSIBLE
+51280190|Houten, Poeldijk|NOTACCESSIBLE|NOTACCESSIBLE
+59151950|Utrecht, Bogotadreef|NOTACCESSIBLE|NOTACCESSIBLE
+59250091|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
+59490020|Den Dolder, Ernst Sillem Hoeve|NOTACCESSIBLE|NOTACCESSIBLE
+59150320|Maarssen, De Malle Jan|NOTACCESSIBLE|NOTACCESSIBLE
+59150460|Utrecht, Prins Bernhardplein|NOTACCESSIBLE|NOTACCESSIBLE
+51220831|Nieuwegein, Waterlelie|NOTACCESSIBLE|NOTACCESSIBLE
+59250212|Maarssen, Parkweg|NOTACCESSIBLE|NOTACCESSIBLE
+51340451|Vianen, Sportlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51320032|IJsselstein, Europalaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220991|Nieuwegein, Waterbies|NOTACCESSIBLE|NOTACCESSIBLE
+50005502|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51111200|Utrecht, De Woerd|NOTACCESSIBLE|NOTACCESSIBLE
+50003800|Utrecht, Kanaleneiland|NOTACCESSIBLE|NOTACCESSIBLE
+50200820|Zeist, Pr. Margrietlaan 235|NOTACCESSIBLE|NOTACCESSIBLE
+50005055|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51110140|De Meern, Noorderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
+50310030|Austerlitz, KNVB-Sportcentrum|NOTACCESSIBLE|NOTACCESSIBLE
+50006370|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220411|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
+59250093|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
+59100100|Groenekan, Zwembad  Blauwkapel|NOTACCESSIBLE|NOTACCESSIBLE
+59250081|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
+59150390|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
+51220271|Nieuwegein, Noordstedeweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220300|Nieuwegein, Merwesteintunnel|NOTACCESSIBLE|NOTACCESSIBLE
+51200450|Vleuten, Stroomrugbaan|NOTACCESSIBLE|NOTACCESSIBLE
+50001241|Utrecht, Europaplein|NOTACCESSIBLE|NOTACCESSIBLE
+51380020|'t Goy, Odijk|NOTACCESSIBLE|NOTACCESSIBLE
+50002210|Utrecht, Willemsviaduct|NOTACCESSIBLE|NOTACCESSIBLE
+50006690|Utrecht, Universiteitsmuseum|NOTACCESSIBLE|NOTACCESSIBLE
+51200210|De Meern, Esdoornlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50002142|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59200200|Maartensdijk, Emmalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000030|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51221032|Nieuwegein, Fokkesteeg|NOTACCESSIBLE|NOTACCESSIBLE
+51320071|IJsselstein, Televisiebaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220080|Nieuwegein, Orpheuslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100530|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
+59390070|Bosch en Duin, Vossenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100400|Utrecht, Archimedeslaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250720|Maarssen, Cramerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200760|Zeist, Oranje Nassaulaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000060|Utrecht, 24 Oktoberplein|NOTACCESSIBLE|NOTACCESSIBLE
+50003640|Utrecht, Ondiep|NOTACCESSIBLE|NOTACCESSIBLE
+50200810|Zeist, Pr. Margrietlaan 405|NOTACCESSIBLE|NOTACCESSIBLE
+51280020|Houten, Koppeldijk|NOTACCESSIBLE|NOTACCESSIBLE
+59151620|Utrecht, Minister Talmastraat|NOTACCESSIBLE|NOTACCESSIBLE
+59150431|Utrecht, Burg. Van Tuyllkade|NOTACCESSIBLE|NOTACCESSIBLE
+59250030|Maarssen, Herenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51111240|Utrecht, Het Zand|NOTACCESSIBLE|NOTACCESSIBLE
+51340400|Vianen, Verz C. Batenstein|NOTACCESSIBLE|NOTACCESSIBLE
+51111170|Utrecht, Kreekraklaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200490|Zeist, Koppelweg|NOTACCESSIBLE|NOTACCESSIBLE
+51200240|Vleuten, Bottensteinweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220452|Nieuwegein, Buys Ballotbaan|NOTACCESSIBLE|NOTACCESSIBLE
+51112500|Utrecht, Vredenburg Leidsche Rijn|NOTACCESSIBLE|NOTACCESSIBLE
+59140160|Utrecht, Savannahweg|NOTACCESSIBLE|NOTACCESSIBLE
+50003350|Utrecht, Stadsschouwburg|NOTACCESSIBLE|NOTACCESSIBLE
+50100020|De Bilt, Steinenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
+59140080|Utrecht, Uraniumweg|NOTACCESSIBLE|NOTACCESSIBLE
+59151760|Utrecht, J.M.de Muinck Keizerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220641|Nieuwegein, Binnenwal|NOTACCESSIBLE|NOTACCESSIBLE
+50200340|Zeist, De Oldenborgh|NOTACCESSIBLE|NOTACCESSIBLE
+51111420|Utrecht, Mercatorlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000512|Utrecht, Struyckenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220972|Nieuwegein, 't Veerhuis|NOTACCESSIBLE|NOTACCESSIBLE
+50007490|Utrecht, Prins Hendriklaan|NOTACCESSIBLE|NOTACCESSIBLE
+50007140|Utrecht, Laan van Nieuw Guinea|NOTACCESSIBLE|NOTACCESSIBLE
+50101060|Utrecht, Wim Sonneveldlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50006630|Utrecht, Domplein|NOTACCESSIBLE|NOTACCESSIBLE
+59151820|Utrecht, Oregondreef|NOTACCESSIBLE|NOTACCESSIBLE
+50100520|Utrecht-De Uithof, Heidelberglaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250200|Maarssen, Parkweg|NOTACCESSIBLE|NOTACCESSIBLE
+59152050|Utrecht, Taagdreef|NOTACCESSIBLE|NOTACCESSIBLE
+59250700|Maarssen, Ranstplein|NOTACCESSIBLE|NOTACCESSIBLE
+51320421|IJsselstein, Lagebiezen|NOTACCESSIBLE|NOTACCESSIBLE
+50006350|Utrecht, Brederoplein|NOTACCESSIBLE|NOTACCESSIBLE
+51220712|Nieuwegein, Graaf Florisweg|NOTACCESSIBLE|NOTACCESSIBLE
+59250060|Maarssen, Zwembad|NOTACCESSIBLE|NOTACCESSIBLE
+51111210|Utrecht, Tweede Westerparklaan|NOTACCESSIBLE|NOTACCESSIBLE
+51320031|IJsselstein, Europalaan|NOTACCESSIBLE|NOTACCESSIBLE
+51280260|Houten, Prov.weg/Doornkade|NOTACCESSIBLE|NOTACCESSIBLE
+51285000|Houten, Station|NOTACCESSIBLE|NOTACCESSIBLE
+50200160|Zeist, Burg. Patijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59151600|Utrecht, Prins Bernhardlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59150240|Utrecht, Daelwijck|NOTACCESSIBLE|NOTACCESSIBLE
+51114360|Utrecht, Station Terwijde|NOTACCESSIBLE|NOTACCESSIBLE
+50390170|Odijk, Rijnseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50390180|Odijk, Rijnseweg|NOTACCESSIBLE|NOTACCESSIBLE
+51221020|Nieuwegein, Raalterveste|NOTACCESSIBLE|NOTACCESSIBLE
+50310050|Austerlitz, Austerlitzseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50201060|Zeist, Vrijheidsplein|NOTACCESSIBLE|NOTACCESSIBLE
+51220220|Nieuwegein, Barnsteendrift|NOTACCESSIBLE|NOTACCESSIBLE
+50002190|Utrecht, Station Overvecht|NOTACCESSIBLE|NOTACCESSIBLE
+51320390|IJsselstein, Achtersloot|NOTACCESSIBLE|NOTACCESSIBLE
+51380070|Schalkwijk, Wickenburghselaan|NOTACCESSIBLE|NOTACCESSIBLE
+59150150|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51320710|IJsselstein, Goudplevier|NOTACCESSIBLE|NOTACCESSIBLE
+59230010|Haarzuilens, Thematerweg|NOTACCESSIBLE|NOTACCESSIBLE
+50390050|Odijk, De Vork|NOTACCESSIBLE|NOTACCESSIBLE
+51200213|Vleuten, Sparrendaal|NOTACCESSIBLE|NOTACCESSIBLE
+51111110|Utrecht, Burgemeester Verderlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59390090|Den Dolder, Hertenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340140|Vianen, 't Zand|NOTACCESSIBLE|NOTACCESSIBLE
+59390050|Huis ter Heide, Park  Rodichem|NOTACCESSIBLE|NOTACCESSIBLE
+50200500|Zeist, Koppelweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100610|De Bilt,  Grontmij Houdringe|NOTACCESSIBLE|NOTACCESSIBLE
+50190080|Bunnik, Van Zijldreef|NOTACCESSIBLE|NOTACCESSIBLE
+59390020|Huis ter Heide, Frans van Mierislaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111470|Utrecht, Papendorp Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+59150550|Utrecht, Sweder van Zuylenweg|NOTACCESSIBLE|NOTACCESSIBLE
+50002030|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51111180|Utrecht, Kreekraklaan|NOTACCESSIBLE|NOTACCESSIBLE
+59151180|Utrecht, Niftarlakeplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+50001380|Utrecht, Vondellaan|NOTACCESSIBLE|NOTACCESSIBLE
+59140071|Utrecht, Uraniumweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000530|Utrecht, Nijenoord|NOTACCESSIBLE|NOTACCESSIBLE
+50201110|Zeist, Vrijheidsplein|NOTACCESSIBLE|NOTACCESSIBLE
+51111260|Utrecht, Utrechtseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50310090|Austerlitz, Dorpsplein|NOTACCESSIBLE|NOTACCESSIBLE
+59150401|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
+50310040|Austerlitz, Austerlitzseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50003140|Utrecht, De Koppel|NOTACCESSIBLE|NOTACCESSIBLE
+51110150|De Meern, Noorderbreedte|NOTACCESSIBLE|NOTACCESSIBLE
+59230070|Haarzuilens, Brink|NOTACCESSIBLE|NOTACCESSIBLE
+50006310|Utrecht, Van Zijstweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100170|De Bilt, Looijdijk|NOTACCESSIBLE|NOTACCESSIBLE
+59250560|Maarssenbroek, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+59151240|Utrecht, Kaap Hoorndreef|NOTACCESSIBLE|NOTACCESSIBLE
+50007450|Utrecht, Dillenburgstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50001800|Utrecht, Ingenhouszstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220700|Nieuwegein, Graaf Florisweg|NOTACCESSIBLE|NOTACCESSIBLE
+59100050|Groenekan, Buitenlust|NOTACCESSIBLE|NOTACCESSIBLE
+59250531|Maarssenbroek, Vogelweg-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
+50200800|Zeist, Pr. Margrietlaan 405|NOTACCESSIBLE|NOTACCESSIBLE
+50002070|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200480|Zeist, De Sluis|NOTACCESSIBLE|NOTACCESSIBLE
+50000640|Utrecht, Wittevrouwen|NOTACCESSIBLE|NOTACCESSIBLE
+50100050|De Bilt, Kerklaan|NOTACCESSIBLE|NOTACCESSIBLE
+51320422|IJsselstein, Lagebiezen|NOTACCESSIBLE|NOTACCESSIBLE
+51380350|Schalkwijk, Trip|NOTACCESSIBLE|NOTACCESSIBLE
+59250110|Maarssen, Winkelcentrum|NOTACCESSIBLE|NOTACCESSIBLE
+50200411|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|NOTACCESSIBLE
+50201480|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200170|Zeist, Burg. Patijnlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59150600|Utrecht, Professor Bavinckstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59200070|Maartensdijk, Industrieterrein|NOTACCESSIBLE|NOTACCESSIBLE
+50001080|Utrecht, Stadionlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000470|Utrecht, Watertoren|NOTACCESSIBLE|NOTACCESSIBLE
+51280950|Houten, De Muren|NOTACCESSIBLE|NOTACCESSIBLE
+50005501|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51180070|Nieuwegein, Ravenswade|NOTACCESSIBLE|NOTACCESSIBLE
+50007110|Utrecht, Spinozaweg|NOTACCESSIBLE|NOTACCESSIBLE
+59230150|Haarzuilens, Polderweg|NOTACCESSIBLE|NOTACCESSIBLE
+51380130|Schalkwijk, Rozenhoeve|NOTACCESSIBLE|NOTACCESSIBLE
+50290050|Bunnik, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+50001760|Utrecht, W. de Zwijgerplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+51110770|De Meern, Proost en Brandt|NOTACCESSIBLE|NOTACCESSIBLE
+51220140|Nieuwegein, Middenweide|NOTACCESSIBLE|NOTACCESSIBLE
+50310010|Zeist, Woudschoten|NOTACCESSIBLE|NOTACCESSIBLE
+50000630|Utrecht, Wittevrouwen|NOTACCESSIBLE|NOTACCESSIBLE
+51220992|Nieuwegein, Waterbies|NOTACCESSIBLE|NOTACCESSIBLE
+50100250|Bilthoven, Poolsterlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200020|Zeist, Dreef/Kromme-Rijnln.|NOTACCESSIBLE|NOTACCESSIBLE
+50002022|Utrecht, Welgelegen|NOTACCESSIBLE|NOTACCESSIBLE
+51114600|Utrecht, Parkzichtlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200960|Zeist, Het Rond|NOTACCESSIBLE|NOTACCESSIBLE
+51340522|Vianen, De Limiet-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+51200200|Vleuten, Rivierkom Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+59250361|Maarssenbroek, Bloem-Boomstede|NOTACCESSIBLE|NOTACCESSIBLE
+50205022|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
+50100110|Utrecht, P+R Veemarkt|NOTACCESSIBLE|NOTACCESSIBLE
+59150810|Utrecht, Humberdreef|NOTACCESSIBLE|NOTACCESSIBLE
+59230020|Haarzuilens, Joostenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59300070|Hollandsche Rading, Vuurse Dreef|NOTACCESSIBLE|NOTACCESSIBLE
+50200100|Zeist, De Dreef/Panweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000040|Utrecht, Graadt van Roggenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51340170|Vianen, Pr.Julianastraat|NOTACCESSIBLE|NOTACCESSIBLE
+50006810|Utrecht, Stadsschouwburg|NOTACCESSIBLE|NOTACCESSIBLE
+50007190|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
+50220060|Bilthoven, Bilderdijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+59150090|Utrecht, Fort De Gagel|NOTACCESSIBLE|NOTACCESSIBLE
+51225030|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+50201010|Zeist, Heideweg|NOTACCESSIBLE|NOTACCESSIBLE
+50205000|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
+51225082|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+50100030|De Bilt, Steinenburglaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220512|Nieuwegein, Oosterlichtcollege|NOTACCESSIBLE|NOTACCESSIBLE
+50200780|Zeist, Prinses Irenelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220290|Nieuwegein, Calscollege|NOTACCESSIBLE|NOTACCESSIBLE
+50005507|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50201390|Zeist, Johannes Postlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50201030|Zeist, Nieuw Beerschoten|NOTACCESSIBLE|NOTACCESSIBLE
+59140230|Utrecht, Ambachtsweg|NOTACCESSIBLE|NOTACCESSIBLE
+59200090|Maartensdijk, Rotonde-Noord|NOTACCESSIBLE|NOTACCESSIBLE
+50000781|Utrecht, Kanonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220231|Nieuwegein, Barnsteendrift|NOTACCESSIBLE|NOTACCESSIBLE
+50390100|Odijk, N229-Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
+59150100|Utrecht, Fort De Gagel|NOTACCESSIBLE|NOTACCESSIBLE
+59330040|Kockengen, Kockengensebrug|NOTACCESSIBLE|NOTACCESSIBLE
+51200190|Vleuten, Rivierkom Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+51111320|Utrecht, Korianderstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51111220|Utrecht, Tweede Westerparklaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250220|Maarssen, Raadhuisstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51341220|Vianen, Hoeufftlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200790|Zeist, Prinses Irenelaan|NOTACCESSIBLE|NOTACCESSIBLE
+50101010|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
+50002129|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
+59140060|Utrecht, Kernweg|NOTACCESSIBLE|NOTACCESSIBLE
+50002191|Utrecht, Station Overvecht|NOTACCESSIBLE|NOTACCESSIBLE
+50200970|Zeist, Het Rond|NOTACCESSIBLE|NOTACCESSIBLE
+51220751|Nieuwegein, Guido Gezellehove|NOTACCESSIBLE|NOTACCESSIBLE
+51380250|'t Goy, Odijk|NOTACCESSIBLE|NOTACCESSIBLE
+50000660|Utrecht, Oorsprongpark|NOTACCESSIBLE|NOTACCESSIBLE
+59390170|Den Dolder,  Willem Arntszhoeve|NOTACCESSIBLE|NOTACCESSIBLE
+50190030|Utrecht, Koningsweg 175|NOTACCESSIBLE|NOTACCESSIBLE
+50190050|Bunnik,  Oud Amelisweerd|NOTACCESSIBLE|NOTACCESSIBLE
+50200940|Zeist, Van Renesselaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220552|Nieuwegein, Brabanthaven|NOTACCESSIBLE|NOTACCESSIBLE
+50000100|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
+50100700|Utrecht, Cambridgelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220390|Nieuwegein, Huis de Geer|NOTACCESSIBLE|NOTACCESSIBLE
+59200310|Maartensdijk, Rotonde-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+50320020|Huis ter Heide, Dolderseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50007460|Utrecht, Dillenburgstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220971|Nieuwegein, 't Veerhuis|NOTACCESSIBLE|NOTACCESSIBLE
+50100100|De Bilt, Amersfoortseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50002128|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50410010|Austerlitz, De Pyramid|NOTACCESSIBLE|NOTACCESSIBLE
+50200670|Zeist, Weeshuislaan|NOTACCESSIBLE|NOTACCESSIBLE
+50001780|Utrecht, Prof. Leonard Fuchslaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200110|Maartensdijk, Achterwetering|NOTACCESSIBLE|NOTACCESSIBLE
+50100080|De Bilt, Biltse Hoek|NOTACCESSIBLE|NOTACCESSIBLE
+50201320|Zeist, Berkenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59200150|Maartensdijk, Rustenhoven|NOTACCESSIBLE|NOTACCESSIBLE
+59230130|Haarzuilens, Ockhuizerweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100360|De Bilt, Burg. de Withstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50007150|Utrecht, Billitonkade|NOTACCESSIBLE|NOTACCESSIBLE
+51280050|Houten, Koppeldijk|NOTACCESSIBLE|NOTACCESSIBLE
+50190010|Utrecht, Koningsweg / A 27|NOTACCESSIBLE|NOTACCESSIBLE
+59150060|Utrecht, Oud Zuilen|NOTACCESSIBLE|NOTACCESSIBLE
+51320342|IJsselstein, Goudplevier|NOTACCESSIBLE|NOTACCESSIBLE
+59200030|Hollandsche Rading, Tolakkerweg 57|NOTACCESSIBLE|NOTACCESSIBLE
+50200180|Zeist, Van der Merschlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200260|Zeist, Schaerweydelaan|NOTACCESSIBLE|NOTACCESSIBLE
+59230040|Haarzuilens, Kasteel|NOTACCESSIBLE|NOTACCESSIBLE
+51320072|IJsselstein, Televisiebaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100650|De Bilt, De Holle Bilt|NOTACCESSIBLE|NOTACCESSIBLE
+51220272|Nieuwegein, Noordstedeweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100450|Utrecht-De Uithof, Botanische Tuinen|NOTACCESSIBLE|NOTACCESSIBLE
+50190100|Utrecht, Koningsweg / A 27|NOTACCESSIBLE|NOTACCESSIBLE
+51320402|IJsselstein, Achtersloot|NOTACCESSIBLE|NOTACCESSIBLE
+50000140|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
+50003360|Utrecht, Neude|NOTACCESSIBLE|NOTACCESSIBLE
+50001490|Utrecht, David van Mollemstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51380120|Schalkwijk, Spoorlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111130|Utrecht, Archeologiepark|NOTACCESSIBLE|NOTACCESSIBLE
+51200250|Vleuten, Alenveltpark|NOTACCESSIBLE|NOTACCESSIBLE
+59151200|Utrecht, J.M.de Muinck Keizerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50006420|Utrecht, Maasplein|NOTACCESSIBLE|NOTACCESSIBLE
+50220090|Bilthoven, Soestdijkseweg-Noord|NOTACCESSIBLE|NOTACCESSIBLE
+51180080|Nieuwegein, Penitentiaire Inr.|NOTACCESSIBLE|NOTACCESSIBLE
+51220410|Nieuwegein, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220211|Nieuwegein, De Baten|NOTACCESSIBLE|NOTACCESSIBLE
+51111060|Nieuwegein, Remiseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000360|Utrecht, Neude|NOTACCESSIBLE|NOTACCESSIBLE
+50220100|Bilthoven, Van der Helstlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000460|Utrecht, Concordiastraat|NOTACCESSIBLE|NOTACCESSIBLE
+59330060|Kockengen, Kerkweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220610|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
+50200190|Zeist, Van der Merschlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51380380|Schalkwijk, Trip|NOTACCESSIBLE|NOTACCESSIBLE
+50000182|Utrecht, Zkh. Oudenrijn/Beneluxlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50220440|Maartensdijk, Mauritshoeve|NOTACCESSIBLE|NOTACCESSIBLE
+50001850|Utrecht, Adelaarstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50000880|Utrecht, Van Koetsveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50007130|Utrecht, Laan van Nieuw Guinea|NOTACCESSIBLE|NOTACCESSIBLE
+50390010|Bunnik, Uitgaansc. Brothers|NOTACCESSIBLE|NOTACCESSIBLE
+51220691|Nieuwegein, H.Heijermanshove|NOTACCESSIBLE|NOTACCESSIBLE
+50201380|Zeist, Johannes Postlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220820|Nieuwegein, Waterlelie|NOTACCESSIBLE|NOTACCESSIBLE
+51200270|Vleuten, De Reit|NOTACCESSIBLE|NOTACCESSIBLE
+51200218|Vleuten, Wilhelminalaan|NOTACCESSIBLE|NOTACCESSIBLE
+51325501|IJsselstein, Binnenstad|NOTACCESSIBLE|NOTACCESSIBLE
+50200440|Zeist, Noordweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200390|Zeist, Prinses Margrietlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250050|Maarssen, De Wilgenplas|NOTACCESSIBLE|NOTACCESSIBLE
+51225040|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+59140140|Utrecht, Otto Hahnweg|NOTACCESSIBLE|NOTACCESSIBLE
+51320401|IJsselstein, Achtersloot|NOTACCESSIBLE|NOTACCESSIBLE
+50008040|Utrecht, Burg. Fockema Andreaelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51110791|De Meern, Oracle|NOTACCESSIBLE|NOTACCESSIBLE
+50291000|Bunnik, Station|NOTACCESSIBLE|NOTACCESSIBLE
+59152070|Utrecht, Brailledreef|NOTACCESSIBLE|NOTACCESSIBLE
+59250232|Maarssen, Raadhuisstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51340491|Vianen, Edisonweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100040|De Bilt, Kerklaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220740|Nieuwegein, Guido Gezellehove|NOTACCESSIBLE|NOTACCESSIBLE
+50200300|Zeist, Amandelhof|NOTACCESSIBLE|NOTACCESSIBLE
+51200310|Vleuten, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50490010|Odijk, Fruittuin|NOTACCESSIBLE|NOTACCESSIBLE
+51380270|t Goy, Café  De Eng|NOTACCESSIBLE|NOTACCESSIBLE
+50100510|Utrecht-De Uithof, Heidelberglaan|NOTACCESSIBLE|NOTACCESSIBLE
+50201090|Huis ter Heide, P.Alexanderstichting|NOTACCESSIBLE|NOTACCESSIBLE
+50002180|Utrecht, P+R Westraven|NOTACCESSIBLE|NOTACCESSIBLE
+59200080|Maartensdijk, Industrieterrein|NOTACCESSIBLE|NOTACCESSIBLE
+59151930|Utrecht, Orinocodreef|NOTACCESSIBLE|NOTACCESSIBLE
+51320360|IJsselstein, Overwaard|NOTACCESSIBLE|NOTACCESSIBLE
+59140131|Utrecht, Otto Hahnweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200280|Zeist, Hogeweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100630|De Bilt, De Holle Bilt|NOTACCESSIBLE|NOTACCESSIBLE
+51380310|'t Goy, Oostrumsdijkje|NOTACCESSIBLE|NOTACCESSIBLE
+50200220|Zeist, Steynlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50220190|Bilthoven, Walnootlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51200370|Vleuten, Henri Dunantlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59100090|Groenekan, Zwembad  Blauwkapel|NOTACCESSIBLE|NOTACCESSIBLE
+51220501|Nieuwegein, Wattbaan|NOTACCESSIBLE|NOTACCESSIBLE
+59230160|Haarzuilens, Polderweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200150|Zeist, Nepveulaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200210|Zeist, J.van Lennepplein|NOTACCESSIBLE|NOTACCESSIBLE
+50220290|Bilthoven, Walnootlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200990|Zeist, Molenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51111230|Utrecht, Het Zand|NOTACCESSIBLE|NOTACCESSIBLE
+50310100|Austerlitz, Waterlooweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200730|Zeist, Prof.Lorentzln.-Zkh.|NOTACCESSIBLE|NOTACCESSIBLE
+51380190|Schalkwijk, De Heul|NOTACCESSIBLE|NOTACCESSIBLE
+59252009|Maarssenbroek, Vogelweg-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
+51220930|Nieuwegein, Koninginnenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340180|Vianen, Pr.Julianastraat|NOTACCESSIBLE|NOTACCESSIBLE
+51200280|Vleuten, De Reit|NOTACCESSIBLE|NOTACCESSIBLE
+50200430|Zeist, Noordweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100091|De Bilt, Amersfoortseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000960|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51110380|De Meern, Sligro|NOTACCESSIBLE|NOTACCESSIBLE
+51200260|Vleuten, Alenveltpark|NOTACCESSIBLE|NOTACCESSIBLE
+50390240|Odijk, Jodichemdreef|NOTACCESSIBLE|NOTACCESSIBLE
+51220151|Nieuwegein, Middenweide|NOTACCESSIBLE|NOTACCESSIBLE
+59151870|Utrecht, Nebraskadreef|NOTACCESSIBLE|NOTACCESSIBLE
+50100190|De Bilt, Dr. Letteplein|NOTACCESSIBLE|NOTACCESSIBLE
+51220730|Nieuwegein, Leusderschans|NOTACCESSIBLE|NOTACCESSIBLE
+51220532|Nieuwegein, De Bongenaar|NOTACCESSIBLE|NOTACCESSIBLE
+50003080|Utrecht, Brennerbrug|NOTACCESSIBLE|NOTACCESSIBLE
+50200931|Zeist, Griftlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50201470|Zeist, Geroplein|NOTACCESSIBLE|NOTACCESSIBLE
+50003400|Utrecht, Van Hoornekade|NOTACCESSIBLE|NOTACCESSIBLE
+50390070|Odijk, Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
+59250660|Maarssenbroek, Nijverheidsweg|NOTACCESSIBLE|NOTACCESSIBLE
+50205020|Zeist, Busstation|NOTACCESSIBLE|NOTACCESSIBLE
+50201360|Zeist, Dijnselburg|NOTACCESSIBLE|NOTACCESSIBLE
+50200320|Zeist, Louise de Colignypl.|NOTACCESSIBLE|NOTACCESSIBLE
+51200350|Vleuten, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220880|Nieuwegein, Leusderschans|NOTACCESSIBLE|NOTACCESSIBLE
+50000671|Utrecht, Vasco da Gamalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000610|Utrecht, Afrikalaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220960|Nieuwegein, Berkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220370|Nieuwegein, Blauwe Brug|NOTACCESSIBLE|NOTACCESSIBLE
+51220330|Nieuwegein, Martinbaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100220|De Bilt, Groenekanseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50290040|Bunnik, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+50200980|Zeist, Molenweg|NOTACCESSIBLE|NOTACCESSIBLE
+50100060|De Bilt, Tunneltje de Bilt|NOTACCESSIBLE|NOTACCESSIBLE
+51380110|Schalkwijk, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
+59330090|Kockengen, Wethouder Van Doornweg|NOTACCESSIBLE|NOTACCESSIBLE
+50201510|Zeist, Lageweg|NOTACCESSIBLE|NOTACCESSIBLE
+59140111|Utrecht, Hyperonenweg|NOTACCESSIBLE|NOTACCESSIBLE
+50391110|Bunnik, Uitgaansc. Brothers|NOTACCESSIBLE|NOTACCESSIBLE
+59151270|Utrecht, Landskroondreef|NOTACCESSIBLE|NOTACCESSIBLE
+51220770|Nieuwegein, Constructieweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220602|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
+59330020|Kockengen, Portengen|NOTACCESSIBLE|NOTACCESSIBLE
+50000172|Utrecht, Rijnkade|NOTACCESSIBLE|NOTACCESSIBLE
+50390080|Odijk, Fruittuin|NOTACCESSIBLE|NOTACCESSIBLE
+50310130|Austerlitz, Traayweg|NOTACCESSIBLE|NOTACCESSIBLE
+50006330|Utrecht, Van der Goesstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59230090|Haarzuilens, De Bom|NOTACCESSIBLE|NOTACCESSIBLE
+50200580|Zeist, Godfried van Seystln|NOTACCESSIBLE|NOTACCESSIBLE
+50000771|Utrecht, Kanonstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50002860|Utrecht, Griftstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51200380|Vleuten, Henri Dunantlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111550|Utrecht, Musicalkade|NOTACCESSIBLE|NOTACCESSIBLE
+51220380|Nieuwegein, 't Veerhuis|NOTACCESSIBLE|NOTACCESSIBLE
+51220940|Nieuwegein, Koninginnenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59151880|Utrecht, Nebraskadreef|NOTACCESSIBLE|NOTACCESSIBLE
+50002540|Utrecht, Overste den Oudenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111120|Utrecht, Burgemeester Verderlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250800|Maarssen, Sportpark Oostwaard|NOTACCESSIBLE|NOTACCESSIBLE
+51220091|Nieuwegein, Orpheuslaan|NOTACCESSIBLE|NOTACCESSIBLE
+50007060|Utrecht, Gietijzerstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50007030|Utrecht, Walserijstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59250440|Maarssenbroek, Spechten-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
+50000870|Utrecht, Van Koetsveldstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50000950|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
+51380300|t Goy, Café  De Eng|NOTACCESSIBLE|NOTACCESSIBLE
+50006300|Utrecht, Jaarbeursplein|NOTACCESSIBLE|NOTACCESSIBLE
+50201260|Zeist, Grote Koppel|NOTACCESSIBLE|NOTACCESSIBLE
+51280660|Houten, De Tuinen/Kruisboog|NOTACCESSIBLE|NOTACCESSIBLE
+51111100|Nieuwegein, Blokhoeve Noord|NOTACCESSIBLE|NOTACCESSIBLE
+51320341|IJsselstein, Goudplevier|NOTACCESSIBLE|NOTACCESSIBLE
+59150990|Utrecht, Kaap Hoorndreef|NOTACCESSIBLE|NOTACCESSIBLE
+59150370|Utrecht, Marnixlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250350|Maarssenbroek, Zonnebaan|NOTACCESSIBLE|NOTACCESSIBLE
+59390180|Den Dolder, Soestdijkerweg|NOTACCESSIBLE|NOTACCESSIBLE
+59150140|Maarssen, Gageldijk 41|NOTACCESSIBLE|NOTACCESSIBLE
+51220492|Nieuwegein, Wattbaan|NOTACCESSIBLE|NOTACCESSIBLE
+50490040|Werkhoven, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
+59490010|Den Dolder, Soestdijkerweg|NOTACCESSIBLE|NOTACCESSIBLE
+51200217|Vleuten, Wilhelminalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50006380|Utrecht, Balijelaan|NOTACCESSIBLE|NOTACCESSIBLE
+59151860|Utrecht, Arizonadreef|NOTACCESSIBLE|NOTACCESSIBLE
+51111050|Nieuwegein, Remiseweg|NOTACCESSIBLE|NOTACCESSIBLE
+50201120|Huis ter Heide, P.Alexanderstichting|NOTACCESSIBLE|NOTACCESSIBLE
+50006900|Utrecht, Oosterstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50006400|Utrecht, Waalstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50320050|Huis ter Heide, Sterrenberg|NOTACCESSIBLE|NOTACCESSIBLE
+50100330|De Bilt, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51340440|Vianen, Lange Dreef|NOTACCESSIBLE|NOTACCESSIBLE
+50005536|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51340161|Vianen, Weidekamp|NOTACCESSIBLE|NOTACCESSIBLE
+51220200|Nieuwegein, De Baten|NOTACCESSIBLE|NOTACCESSIBLE
+50000800|Utrecht, Hasebroekstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220521|Nieuwegein, Oosterlichtcollege|NOTACCESSIBLE|NOTACCESSIBLE
+50003620|Utrecht, Anton Geesinkstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59151990|Utrecht, Paranadreef|NOTACCESSIBLE|NOTACCESSIBLE
+59330070|Kockengen, Kerkweg|NOTACCESSIBLE|NOTACCESSIBLE
+59390060|Bosch en Duin, Vossenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51221060|Nieuwegein, Gerbrandypark|NOTACCESSIBLE|NOTACCESSIBLE
+50200850|Zeist, Graaf Adolflaan|NOTACCESSIBLE|NOTACCESSIBLE
+51111450|Utrecht, Orteliuslaan|NOTACCESSIBLE|NOTACCESSIBLE
+51380030|Schalkwijk, Kloostergaarde|NOTACCESSIBLE|NOTACCESSIBLE
+51340542|Vianen, Laanakkerweg|NOTACCESSIBLE|NOTACCESSIBLE
+50201300|Zeist, Kritzingerlaan|NOTACCESSIBLE|NOTACCESSIBLE
+51110801|De Meern, Oracle|NOTACCESSIBLE|NOTACCESSIBLE
+59255000|Maarssen, Station/Bisonspoor|NOTACCESSIBLE|NOTACCESSIBLE
+50590010|Werkhoven, Hardenbroek|NOTACCESSIBLE|NOTACCESSIBLE
+50201330|Zeist, Berkenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000710|Utrecht, Sartreweg|NOTACCESSIBLE|NOTACCESSIBLE
+50000340|Utrecht, Wittevrouwenbrug|NOTACCESSIBLE|NOTACCESSIBLE
+51180090|Nieuwegein, Penitentiaire Inr.|NOTACCESSIBLE|NOTACCESSIBLE
+50100710|Utrecht, Bolognalaan|NOTACCESSIBLE|NOTACCESSIBLE
+50105500|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
+59250040|Maarssen, De Wilgenplas|NOTACCESSIBLE|NOTACCESSIBLE
+59252011|Maarssenbroek, Zebraspoor|NOTACCESSIBLE|NOTACCESSIBLE
+59390120|Den Dolder, Station|NOTACCESSIBLE|NOTACCESSIBLE
+50201140|Huis ter Heide, Prins Alexanderweg|NOTACCESSIBLE|NOTACCESSIBLE
+51220120|Nieuwegein, De Kempenaerpark|NOTACCESSIBLE|NOTACCESSIBLE
+51220021|Nieuwegein, Postkantoor|NOTACCESSIBLE|NOTACCESSIBLE
+50002010|Utrecht, Den Hommel|NOTACCESSIBLE|NOTACCESSIBLE
+50001021|Utrecht, Stadion Galgenwaard|NOTACCESSIBLE|NOTACCESSIBLE
+50002200|Utrecht, Moreelsepark/HC|NOTACCESSIBLE|NOTACCESSIBLE
+59200140|Maartensdijk, Rustenhoven|NOTACCESSIBLE|NOTACCESSIBLE
+51340360|Vianen, v. Duvenvoordestraat|NOTACCESSIBLE|NOTACCESSIBLE
+50002220|Utrecht, Willemsviaduct|NOTACCESSIBLE|NOTACCESSIBLE
+50190020|Utrecht, Koningsweg 175|NOTACCESSIBLE|NOTACCESSIBLE
+51220680|Nieuwegein, Poort van Nieuwegein|NOTACCESSIBLE|NOTACCESSIBLE
+50000700|Utrecht, Sartreweg|NOTACCESSIBLE|NOTACCESSIBLE
+50190110|Utrecht, Ln v Maarschalkerwd|NOTACCESSIBLE|NOTACCESSIBLE
+59150330|Utrecht, Muyskenweg|NOTACCESSIBLE|NOTACCESSIBLE
+51110780|De Meern, Proost en Brandt|NOTACCESSIBLE|NOTACCESSIBLE
+59200020|Hollandsche Rading, Vuurse Dreef|NOTACCESSIBLE|NOTACCESSIBLE
+59100030|Maartensdijk, Nieuwe-Wetering|NOTACCESSIBLE|NOTACCESSIBLE
+51220252|Nieuwegein, Koetsdrift|NOTACCESSIBLE|NOTACCESSIBLE
+59150300|Utrecht, Sweder van Zuylenweg|NOTACCESSIBLE|NOTACCESSIBLE
+59330030|Kockengen, Portengen|NOTACCESSIBLE|NOTACCESSIBLE
+59152080|Utrecht, Brailledreef|NOTACCESSIBLE|NOTACCESSIBLE
+50200450|Zeist, Brugakker|NOTACCESSIBLE|NOTACCESSIBLE
+59330120|Kockengen, Roerdomp|NOTACCESSIBLE|NOTACCESSIBLE
+51340390|Vianen, Verz C. Batenstein|NOTACCESSIBLE|NOTACCESSIBLE
+50002060|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
+50001090|Utrecht, Rubenslaan|NOTACCESSIBLE|NOTACCESSIBLE
+51340040|Vianen, Clarissenhof|NOTACCESSIBLE|NOTACCESSIBLE
+50007520|Utrecht, Pieter Breughelstraat|NOTACCESSIBLE|NOTACCESSIBLE
+59330130|Kockengen, Roerdomp|NOTACCESSIBLE|NOTACCESSIBLE
+51220321|Nieuwegein, Martinbaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000160|Utrecht, Vredenburgviaduct|NOTACCESSIBLE|NOTACCESSIBLE
+59151360|Utrecht, Donaudreef|NOTACCESSIBLE|NOTACCESSIBLE
+59140200|Utrecht, Niels Bohrweg|NOTACCESSIBLE|NOTACCESSIBLE
+50001210|Utrecht, Kanaleneiland Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+51111080|Nieuwegein, Huis de Geer|NOTACCESSIBLE|NOTACCESSIBLE
+59151840|Utrecht, Hudsondreef|NOTACCESSIBLE|NOTACCESSIBLE
+51220152|Nieuwegein, Middenweide|NOTACCESSIBLE|NOTACCESSIBLE
+50007180|Utrecht, Jan Pietersz. Coenstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50190040|Bunnik,  Oud Amelisweerd|NOTACCESSIBLE|NOTACCESSIBLE
+50310060|Austerlitz, Oude Postweg|NOTACCESSIBLE|NOTACCESSIBLE
+59230050|Haarzuilens, Kasteel|NOTACCESSIBLE|NOTACCESSIBLE
+50310070|Austerlitz, Oude Postweg|NOTACCESSIBLE|NOTACCESSIBLE
+50200350|Zeist, De Oldenborgh|NOTACCESSIBLE|NOTACCESSIBLE
+50390210|Odijk, Jodichemdreef|NOTACCESSIBLE|NOTACCESSIBLE
+50390040|Odijk, De Vork|NOTACCESSIBLE|NOTACCESSIBLE
+50490120|Werkhoven, Hardenbroek|NOTACCESSIBLE|NOTACCESSIBLE
+51200300|Vleuten, Vrijthof|NOTACCESSIBLE|NOTACCESSIBLE
+59151170|Utrecht, Niftarlakeplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+59390010|Huis ter Heide, Prins Alexanderweg|NOTACCESSIBLE|NOTACCESSIBLE
+50008060|Utrecht, Churchilllaan|NOTACCESSIBLE|NOTACCESSIBLE
+59150630|Utrecht, Pionstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50200470|Zeist, De Sluis|NOTACCESSIBLE|NOTACCESSIBLE
+50310080|Austerlitz, Dorpsplein|NOTACCESSIBLE|NOTACCESSIBLE
+51220060|Nieuwegein, Zorgcentrum Zuilenstein|NOTACCESSIBLE|NOTACCESSIBLE
+50001180|Utrecht, Bosboomstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51220032|Nieuwegein, Postkantoor|NOTACCESSIBLE|NOTACCESSIBLE
+50390190|Odijk, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
+50201490|Zeist, Lindenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100390|Utrecht, Archimedeslaan|NOTACCESSIBLE|NOTACCESSIBLE
+59250711|Maarssen, Ranstplein|NOTACCESSIBLE|NOTACCESSIBLE
+51340501|Vianen, K. Onnesweg|NOTACCESSIBLE|NOTACCESSIBLE
+59390030|Huis ter Heide, Frans van Mierislaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220040|Nieuwegein, Wenckebachplantsoen|NOTACCESSIBLE|NOTACCESSIBLE
+50200550|Zeist, Couwenhoven|NOTACCESSIBLE|NOTACCESSIBLE
+50320060|Huis ter Heide, RK Kerk|NOTACCESSIBLE|NOTACCESSIBLE
+50000790|Utrecht, Hasebroekstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51225070|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+51110040|De Meern, Strijkviertel|NOTACCESSIBLE|NOTACCESSIBLE
+50006290|Utrecht, Jaarbeursplein|NOTACCESSIBLE|NOTACCESSIBLE
+51221100|Nieuwegein, Marconi|NOTACCESSIBLE|NOTACCESSIBLE
+59140240|Utrecht, Computerweg|NOTACCESSIBLE|NOTACCESSIBLE
+59151940|Utrecht, Orinocodreef|NOTACCESSIBLE|NOTACCESSIBLE
+50105510|Bilthoven,  RIVM|NOTACCESSIBLE|NOTACCESSIBLE
+50201210|Zeist, Alg. Begraafplaats|NOTACCESSIBLE|NOTACCESSIBLE
+50001500|Utrecht, David van Mollemstraat|NOTACCESSIBLE|NOTACCESSIBLE
+50390090|Odijk, N229-Zeisterweg|NOTACCESSIBLE|NOTACCESSIBLE
+59330050|Kockengen, Kockengensebrug|NOTACCESSIBLE|NOTACCESSIBLE
+59230080|Haarzuilens, De Bom|NOTACCESSIBLE|NOTACCESSIBLE
+50002530|Utrecht, Overste den Oudenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+59100060|Groenekan, Buitenlust|NOTACCESSIBLE|NOTACCESSIBLE
+59252007|Maarssenbroek, Spechten-Zwanenkamp|NOTACCESSIBLE|NOTACCESSIBLE
+51380370|Schalkwijk, Korte Uitweg|NOTACCESSIBLE|NOTACCESSIBLE
+51340061|Vianen, Rietkamp|NOTACCESSIBLE|NOTACCESSIBLE
+51340110|Vianen, Marienhof|NOTACCESSIBLE|NOTACCESSIBLE
+50200530|Zeist, De Boerderij|NOTACCESSIBLE|NOTACCESSIBLE
+50490070|Werkhoven, Sportpark|NOTACCESSIBLE|NOTACCESSIBLE
+59390130|Den Dolder, Station|NOTACCESSIBLE|NOTACCESSIBLE
+51200160|De Meern, Wiericke|NOTACCESSIBLE|NOTACCESSIBLE
+50201500|Zeist, Griffensteijnselaan|NOTACCESSIBLE|NOTACCESSIBLE
+50201530|Zeist, Griffensteijnselaan|NOTACCESSIBLE|NOTACCESSIBLE
+50100460|Utrecht-De Uithof, Botanische Tuinen|NOTACCESSIBLE|NOTACCESSIBLE
+50100180|De Bilt, Looijdijk|NOTACCESSIBLE|NOTACCESSIBLE
+51380160|Schalkwijk, Rozenhoeve|NOTACCESSIBLE|NOTACCESSIBLE
+50101050|Utrecht, Wim Sonneveldlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50220070|Bilthoven, Bilderdijklaan|NOTACCESSIBLE|NOTACCESSIBLE
+59151830|Utrecht, Hudsondreef|NOTACCESSIBLE|NOTACCESSIBLE
+50100270|Bilthoven, Duivenlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50000290|Utrecht, Eykmanplein|NOTACCESSIBLE|NOTACCESSIBLE
+51221090|Nieuwegein, Marconi|NOTACCESSIBLE|NOTACCESSIBLE
+51220190|Nieuwegein, Antilopeweide|NOTACCESSIBLE|NOTACCESSIBLE
+51220232|Nieuwegein, Barnsteendrift|NOTACCESSIBLE|NOTACCESSIBLE
+50005001|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50201020|Zeist, Nieuw Beerschoten|NOTACCESSIBLE|NOTACCESSIBLE
+50005506|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+50490050|Werkhoven, De Brink|NOTACCESSIBLE|NOTACCESSIBLE
+50490140|Werkhoven, Provincialeweg|NOTACCESSIBLE|NOTACCESSIBLE
+50005416|Utrecht, Centraal Station|NOTACCESSIBLE|NOTACCESSIBLE
+51285020|Houten, Station|NOTACCESSIBLE|NOTACCESSIBLE
+50006360|Utrecht, Brederoplein|NOTACCESSIBLE|NOTACCESSIBLE
+50006840|Utrecht, Maliebaan|NOTACCESSIBLE|NOTACCESSIBLE
+50202020|Zeist, Soc. Werkvoorz. Zeist|NOTACCESSIBLE|NOTACCESSIBLE
+51220632|Nieuwegein, Gemeentehuis|NOTACCESSIBLE|NOTACCESSIBLE
+50002850|Utrecht, Griftstraat|NOTACCESSIBLE|NOTACCESSIBLE
+51340300|Vianen, Centrum|NOTACCESSIBLE|NOTACCESSIBLE
+51220180|Nieuwegein, Antilopeweide|NOTACCESSIBLE|NOTACCESSIBLE
+51220811|Nieuwegein, Randijk|NOTACCESSIBLE|NOTACCESSIBLE
+50100533|Utrecht-De Uithof, AZU|NOTACCESSIBLE|NOTACCESSIBLE
+50200200|Zeist, J.van Lennepplein|NOTACCESSIBLE|NOTACCESSIBLE
+51220401|Nieuwegein, Galvanibaan|NOTACCESSIBLE|NOTACCESSIBLE
+50002050|Utrecht, Westplein|NOTACCESSIBLE|NOTACCESSIBLE
+51340052|Vianen, Clarissenhof|NOTACCESSIBLE|NOTACCESSIBLE
+51380180|Schalkwijk, Van Gaalen|NOTACCESSIBLE|NOTACCESSIBLE
+50002090|Utrecht, 24 Oktoberplein-Zuid|NOTACCESSIBLE|NOTACCESSIBLE
+59390160|Den Dolder,  Willem Arntszhoeve|NOTACCESSIBLE|NOTACCESSIBLE
+50200860|Zeist, Van Stolberglaan|NOTACCESSIBLE|NOTACCESSIBLE
+51220840|Nieuwegein, IJsselsteinseweg|NOTACCESSIBLE|NOTACCESSIBLE
+59250080|Maarssen, Maarsseveensevaart|NOTACCESSIBLE|NOTACCESSIBLE
+50220455|Bilthoven, Leeuweriklaan|NOTACCESSIBLE|NOTACCESSIBLE
+51280970|Houten, Weteringshoek|NOTACCESSIBLE|NOTACCESSIBLE
+51340460|Vianen, Sportlaan|NOTACCESSIBLE|NOTACCESSIBLE
+50200540|Zeist, De Boerderij|NOTACCESSIBLE|NOTACCESSIBLE
+50100340|De Bilt, Dorpsstraat|NOTACCESSIBLE|NOTACCESSIBLE
+095183|Spaklerweg|ACCESSIBLE|UNKNOWN
+51225000|Nieuwegein, Stadscentrum|NOTACCESSIBLE|NOTACCESSIBLE
+50006140|Utrecht, Mr. Tripkade|NOTACCESSIBLE|NOTACCESSIBLE
+50000450|Utrecht, Concordiastraat|NOTACCESSIBLE|NOTACCESSIBLE
+59250070|Maarssen, Zwembad|NOTACCESSIBLE|NOTACCESSIBLE
