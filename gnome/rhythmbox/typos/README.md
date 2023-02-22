## Detected Typos Diff
```diff
--- ./tests/test-rb-lib.c	original
+++ ./tests/test-rb-lib.c	fixed
@@ -70 +70 @@
-	ck_assert_msg (rb_string_value_map_get (map, "wombat", &val) == FALSE, "could retrieve non-existant entry");
+	ck_assert_msg (rb_string_value_map_get (map, "wombat", &val) == FALSE, "could retrieve non-existent entry");
--- ./tests/test-rhythmdb.c	original
+++ ./tests/test-rhythmdb.c	fixed
@@ -207 +207 @@
-	/* check folded and sort-key varients */
+	/* check folded and sort-key variants */
--- ./README.daap	original
+++ ./README.daap	fixed
@@ -70 +70 @@
-Resolving is done asychronously via rb_daap_mdns_resolve() and a callback which
+Resolving is done asynchronously via rb_daap_mdns_resolve() and a callback which
@@ -87 +87 @@
-source.  This reduces unneccessary computations and network traffic.
+source.  This reduces unnecessary computations and network traffic.
@@ -98 +98 @@
-recieving a list of the share's music & playlists.  The HTTP communication is
+receiving a list of the share's music & playlists.  The HTTP communication is
@@ -110 +110 @@
-	Here we request /login to recieve a session-id.  All subsequent requests
+	Here we request /login to receive a session-id.  All subsequent requests
@@ -132 +132 @@
-	We request /databases/ID/containers to recieve a list of playlists. Each
+	We request /databases/ID/containers to receive a list of playlists. Each
@@ -139 +139 @@
-After the connection is made and all the data transfered, a new 
+After the connection is made and all the data transferred, a new 
@@ -151 +151 @@
-recieved data through the pipeline.  The data recieved (the song) is in the
+received data through the pipeline.  The data received (the song) is in the
@@ -214 +214 @@
-rb-daap-structure.h.  They are defined in the RBDAAPContentCodeDefintion array 
+rb-daap-structure.h.  They are defined in the RBDAAPContentCodeDefinition array 
--- ./INTERNALS	original
+++ ./INTERNALS	fixed
@@ -155 +155 @@
-of the playback logic.  However, it delgates a fair amount of this to:
+of the playback logic.  However, it delegates a fair amount of this to:
--- ./help/pt/pt.po	original
+++ ./help/pt/pt.po	fixed
@@ -164 +164 @@
-msgstr "Projecto de Documentação do GNOME"
+msgstr "Projection de Documentação do GNOME"
@@ -204 +204 @@
-"documentação do GNOME, e os membros do Projecto de Documentação do GNOME "
+"documentação do GNOME, e os membros do Projection de Documentação do GNOME "
@@ -228,3 +228,3 @@
-"PROVAR-SE DEFEITUOSO EM QUALQUER ASPECTO, DEVE (NÃO O AUTOR INICIAL, AUTOR "
-"OU CONTRIBUINTE) ASSUMIR O CUSTO DE QUALQUER INTERVENÇÃO, REPARAÇÃO OU "
-"CORRECÇÃO. ESTA ?? DE GARANTIA CONSTITUI UMA PARTE ESSENCIAL DESTA LICENÇA. "
+"PROVAR-SE DEFEITUOSO EM QUALQUER ASPECTO, DEVE (NÃO O AUTHOR INICIAL, AUTHOR "
+"OU CONTRIBUINTE) ASSUMIR O CUSTO DE QUALQUER INTERVENÇÃO, REPARAÇÃO OU "
+"CORRECÇÃO. ESTA ?? DE GARANTIA CONSTITUI UMA PARTE ESSENTIAL DESTA LICENÇA. "
@@ -248,2 +248,2 @@
-"(INCLUINDO NEGLIGÊNCIA), CONTRACTO OU DE OUTRO TIPO, NEM O AUTOR, NEM O "
-"AUTOR INICIAL, QUALQUER CONTRIBUINTE, OU QUALQUER DISTRIBUÍDOR DO DOCUMENTO "
+"(INCLUINDO NEGLIGÊNCIA), CONTRACTION OU DE OUTRO TIPO, NEM O AUTHOR, NEM O "
+"AUTHOR INICIAL, QUALQUER CONTRIBUINTE, OU QUALQUER DISTRIBUÍDOR DO DOCUMENTO "
@@ -322 +322 @@
-msgstr "Projecto de Documentação do Ubuntu"
+msgstr "Projection de Documentação do Ubuntu"
@@ -387 +387 @@
-"Para comunicar um erro ou fazer uma sugestão em relação ao Reprodutor de "
+"Para comunicar um error ou fazer uma sugestão em relação ao Reprodutor de "
@@ -451 +451 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -478 +478 @@
-"Transfere música para dispositivos iPod, MTP e reprodutores de música USB de "
+"Transferred música para dispositivos iPod, MTP e reprodutores de música USB de "
@@ -499 +499 @@
-"Escolha <menuchoice><guisubmenu>Som&amp;Vídeo</"
+"Escolha <menuchoice><guisubmenu>Some&amp;Vídeo</"
@@ -505 +505 @@
-msgstr "Linha de Comando"
+msgstr "Linha de Commando"
@@ -555 +555 @@
-"Rhythmbox</application> com os seus componentes principais."
+"Rhythmbox</application> com os seus components principais."
@@ -576 +576 @@
-"A Tabela 1 descreve os componentes da janela do <application>Reprodutor de "
+"A Tabela 1 descreve os components da janela do <application>Reprodutor de "
@@ -582 +582 @@
-"Componentes da Janela do <application>Reprodutor de Música Rhythmbox</"
+"Components da Janela do <application>Reprodutor de Música Rhythmbox</"
@@ -695 +695 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -754 +754 @@
-"A apresentação do painel lateral pode ser alternada entre visível ou não, "
+"A apresentação do painel lateral pode set alternada entre visível ou não, "
@@ -770,2 +770,2 @@
-"reprodução. Quando nenhuma faixa está a ser reproduzida, esta área não "
-"apresenta nenhuma informação. Quando uma uma faixa está a ser reproduzida, o "
+"reprodução. Quando nenhuma faixa está a set reproduzida, esta área não "
+"apresenta nenhuma informação. Quando uma uma faixa está a set reproduzida, o "
@@ -780,2 +780,2 @@
-"Um marcador também é apresentado, mostrando o progresso da reprodução da "
-"faixa. Quando o marcador está focado, as teclas de setas podem ser "
+"Um marcador também é apresentado, mostrando o progression da reprodução da "
+"faixa. Quando o marcador está focado, as teclas de setas podem set "
@@ -809 +809 @@
-"duração da fonte seleccionada. A apresentação da barra de estado pode ser "
+"duração da fonte seleccionada. A apresentação da barra de estado pode set "
@@ -920 +920 @@
-"podem ser utilizador para saltar entre faixas durante a reprodução. "
+"podem set utilizador para saltar entre faixas durante a reprodução. "
@@ -1060 +1060 @@
-"As etiquetas podem ser alteradas escolhendo <menuchoice><guimenu> Música</"
+"As etiquetas podem set alteradas escolhendo <menuchoice><guimenu> Música</"
@@ -1075 +1075 @@
-"Rhythmbox</application> utiliza essas etiquetas para apresentar as faixas de "
+"Rhythmbox</application> utilize essas etiquetas para apresentar as faixas de "
@@ -1193 +1193 @@
-"etiquetas especificas <guilabel>Artistas</guilabel>, <guilabel>Álbuns</"
+"etiquetas especificas <guilabel>Artists</guilabel>, <guilabel>Álbuns</"
@@ -1206,3 +1206,3 @@
-"O Navegador é outra forma conveniente de encontrar faixas. O Navegador é uma "
-"vista de dois ou três painéis que permitem navegar por entre géneros de "
-"música, artistas e álbuns e apresentar faixas que correspondem a esses "
+"O Navegador é outra forma convenience de encontrar faixas. O Navegador é uma "
+"vista de dois ou três painéis que permitem navegar por entre géneros de "
+"música, artists e álbuns e apresentar faixas que correspondem a esses "
@@ -1255 +1255 @@
-"O sintonizador de Rádio na Internet pode ser utilizado para ouvir ficheiros "
+"O sintonizador de Rádio na Internet pode set utilizado para ouvir ficheiros "
@@ -1340 +1340 @@
-"autor publica um episódio, os subscritores do podcast são informados, "
+"author publica um episódio, os subscritores do podcast são informados, "
@@ -1471 +1471 @@
-"guilabel>, <guilabel>Autor </guilabel>, a data da <guilabel>Última "
+"guilabel>, <guilabel>Author </guilabel>, a data da <guilabel>Última "
@@ -1515 +1515 @@
-"progresso da transferência de um episódio na coluna <guilabel>Estado</"
+"progression da transferência de um episódio na coluna <guilabel>Estado</"
@@ -1630 +1630 @@
-"passará automaticamente para esta fonte, após a faixa ser reproduzida."
+"passará automaticamente para esta fonte, após a faixa set reproduzida."
@@ -1641 +1641 @@
-"fonte que estava a ser reproduzia anteriormente."
+"fonte que estava a set reproduzia anteriormente."
@@ -1699 +1699 @@
-"um grupo de artistas especifico ou mesmo faixas de um 'estilo' especifico ou "
+"um grupo de artists especifico ou mesmo faixas de um 'estilo' especifico ou "
@@ -1964 +1964 @@
-"faixas podem ser apresentadas na janela principal do <application>Reprodutor "
+"faixas podem set apresentadas na janela principal do <application>Reprodutor "
@@ -2078 +2078 @@
-"Rhythmbox</application> deveria ser capaz de lidar com a maioria dos "
+"Rhythmbox</application> deveria set capaz de lidar com a maioria dos "
@@ -2222 +2222 @@
-"A janela de notificação pode ser desactivada seleccionando a opção "
+"A janela de notificação pode set desactivada seleccionando a opção "
@@ -2236 +2236 @@
-"application> na área de notificação, os seguintes comandos podem ser enviado "
+"application> na área de notificação, os seguintes commandos podem set enviado "
@@ -2306 +2306 @@
-"Pode alternar rapidamente entre Reproduzir/Pausar pressionando o botão do "
+"Pode alternator rapidamente entre Reproduzir/Pausar pressionando o botão do "
@@ -2496 +2496 @@
-"consultar estatísticas, como as canções mais reproduzidas ou artistas mais "
+"consultar estatísticas, como as canções mais reproduzidas ou artists mais "
@@ -2501 +2501 @@
-msgstr "receba recomendações sobre artistas de que possa gostar."
+msgstr "receba recomendações sobre artists de que possa gostar."
@@ -2539 +2539 @@
-"perfil não está a ser actualizado, a informação aqui apresentada pode ajudá-"
+"perfil não está a set actualizado, a informação aqui apresentada pode ajudá-"
@@ -2776 +2776 @@
-msgstr "Alternar modo de Ecrã Completo"
+msgstr "Alternator modo de Ecrã Completo"
@@ -2823 +2823 @@
-"seguintes cadeias de comando são suportadas, utilizando o nome de programa "
+"seguintes cadeias de commando são suportadas, utilizando o nome de programa "
@@ -2828 +2828 @@
-msgstr "Texto de comando"
+msgstr "Texto de commando"
@@ -2856 +2856 @@
-msgstr "Alternar entre reprodução e pausa"
+msgstr "Alternator entre reprodução e pausa"
@@ -2864 +2864 @@
-msgstr "Alternar a mistura da ordem de reprodução"
+msgstr "Alternator a mistura da ordem de reprodução"
@@ -2872 +2872 @@
-msgstr "Alternar a repetição da ordem de reprodução"
+msgstr "Alternator a repetição da ordem de reprodução"
--- ./help/da/da.po	original
+++ ./help/da/da.po	fixed
@@ -92 +92 @@
-"finde en kopi af GFDL'en her: <ulink type=\"help\" url=\"help:fdl\">link</"
+"find en kopi af GFDL'en her: <ulink type=\"help\" url=\"help:fdl\">link</"
@@ -104,2 +104,2 @@
-"Hvis du vil distribuere denne manual separat fra denne samling, kan du gøre "
-"det ved at tilføje en kopi af licensen til manualen, som beskrevet i sektion "
+"Hvis du vil distribuere denne manual separate fra denne samling, kan du gøre "
+"det ved at tilføje en kopi af licensen til manualen, some beskrevet i sektion "
@@ -138,7 +138,7 @@
-"DETTE DOKUMENT GØRES TILGÆNGELIGT SÅDAN SOM DET ER, UDEN NOGEN FORM FOR "
-"GARANTI, HVERKEN UDTALT ELLER ANTYDET, DERIBLANDT, UDEN BEGRÆNSNINGER, "
-"GARANTIER OM AT DOKUMENTET ELLER ÆNDREDE VERSIONER AF DOKUMENTET ER FRIT FOR "
-"DEFEKTER, PASSENDE TIL ET BESTEMT FORMÅL ELLER IKKE-KRÆNKENDE. DU HÆFTER "
-"SELV FOR HELE RISIKOEN VEDRØRENDE KVALITET, KORREKTHED OG YDELSE FOR "
-"DOKUMENTET ELLER ÆNDREDE VERSIONER AF DOKUMENTET. SKULLE ET DOKUMENT, ELLER "
-"EN ÆNDRET VERSION AF ET DOKUMENT VISE SIG AT VÆRE DEFEKT PÅ EN HVILKEN SOM "
+"DETTE DOKUMENT GØRES TILGÆNGELIGT SÅDAN SOME DET ER, UDEN NOGEN FORM FOR "
+"GARANTI, HVERKEN UDTALT ELLER ANTYDET, DERIBLANDT, UDEN BEGRÆNSNINGER, "
+"GARANTIER OM AT DOKUMENTET ELLER ÆNDREDE VERSIONER AF DOKUMENTET ER FRIT FOR "
+"DEFEKTER, PASSENDE TIL ET BESTEMT FORMÅL ELLER IKKE-KRÆNKENDE. DU HÆFTER "
+"SELF FOR HELE RISIKOEN VEDRØRENDE KVALITET, KORREKTHED OG YDELSE FOR "
+"DOKUMENTET ELLER ÆNDREDE VERSIONER AF DOKUMENTET. SKULLE ET DOKUMENT, ELLER "
+"EN ÆNDRET VERSION AF ET DOKUMENT VISE SIG AT VÆRE DEFEKT PÅ EN HVILKEN SOME "
@@ -167,8 +167,8 @@
-"EN BEVIDST SKADENDE HANDLING (INKLUSIVE UFORSVARLIGHED) ELLER PÅ HVILKEN SOM "
-"HELST ANDEN MÅDE, KAN FORFATTEREN, SKRIBENT, BIDRAGYDERE, DISTRIBUTØRER "
-"ELLER FORSYNER AF DETTE DOKUMENT ELLER MODIFICEREDE VERSIONER GØRES "
-"ANSVARLIG OVERFOR NOGEN PERSON FOR NOGEN DIREKTE, INDIREKTE, SPECIEL, "
-"TILFÆLDIG ELLER FØLGENDE SKADE PÅFØRT NOGEN INKLUSIVE, UDEN BEGRÆNSNING, "
-"SKADE SOM FØLGE AF TAB AF RYGTE, ARBEJDSSTOP, COMPUTERFEJL ELLER -SVIGT, "
-"ELLER ENHVER ANDEN FORM FOR SKADE ELLER TAB SOM ER OPSTÅET I FORBINDELSE MED "
-"BRUG AF DETTE DOKUMENT ELLER MODIFICEREDE VERSIONER HERAF, SELV HVIS EN "
+"EN BEVIDST SKADENDE HANDLING (INKLUSIVE UFORSVARLIGHED) ELLER PÅ HVILKEN SOME "
+"HELST ANDEN MÅDE, KAN FORFATTEREN, SKRIBENT, BIDRAGYDERE, DISTRIBUTØRER "
+"ELLER FORSYNER AF DETTE DOKUMENT ELLER MODIFICEREDE VERSIONER GØRES "
+"ANSVARLIG OVERFOR NOGEN PERSON FOR NOGEN DIREKTE, INDIREKTE, SPECIEL, "
+"TILFÆLDIG ELLER FØLGENDE SKADE PÅFØRT NOGEN INKLUSIVE, UDEN BEGRÆNSNING, "
+"SKADE SOME FØLGE AF TAB AF RYGTE, ARBEJDSSTOP, COMPUTERFEJL ELLER -SVIGT, "
+"ELLER ENHVER ANDEN FORM FOR SKADE ELLER TAB SOME ER OPSTÅET I FORBINDELSE MED "
+"BRUG AF DETTE DOKUMENT ELLER MODIFICEREDE VERSIONER HERAF, SELF HVIS EN "
@@ -335 +335 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -339 +339 @@
-"<date>januar 2020</date> <_:revdescription-1/>"
+"<date>january 2020</date> <_:revdescription-1/>"
@@ -385 +385 @@
-msgstr "Introduktion"
+msgstr "Introduction"
@@ -408 +408 @@
-"Afspil forskellige formater af musikfiler fra din organiserede og mærkede "
+"Afspil forskellige formatter af musikfiler fra din organiserede og mærkede "
@@ -430 +430 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -493 +493 @@
-msgstr "Tast <command>rhythmbox</command>, og tryk <keycap>Retur</keycap>."
+msgstr "Taste <command>rhythmbox</command>, og tryk <keycap>Return</keycap>."
@@ -518 +518 @@
-"application>, vil en assistent hjælpe dig med at importere din musik. I den "
+"application>, vil en assistant hjælpe dig med at importere din musik. I den "
@@ -583 +583 @@
-"Tabel 1 beskriver komponenterne af <application>Musikafspilleren Rhythmbox</"
+"Table 1 beskriver komponenterne af <application>Musikafspilleren Rhythmbox</"
@@ -625,2 +625,2 @@
-"Giver adgang til afspillerfunktioner og detaljer om det spor, som afspilles i "
-"øjeblikket. Inkluderer tidsskyderen som viser sporets læseposition; "
+"Giver adgang til afspillerfunktioner og detaljer om det spor, some afspilles i "
+"øjeblikket. Inkluderer tidsskyderen some viser sporets læseposition; "
@@ -809 +809 @@
-"Der vises også en tracker med fremgangen af sporet som afspilles og en "
+"Der vises også en tracker med fremgangen af sporet some afspilles og en "
@@ -820,2 +820,2 @@
-"Hvis du bruger en mus med et hjul, kan du justere lydstyrken ved at rulle op "
-"eller ned mens musemarkøren er over lydstyrkeknappen i højre hjørne."
+"Hvis du bruger en mus med et hjul, kan du justere lydstyrken ved at rule op "
+"eller need mens musemarkøren er over lydstyrkeknappen i højre hjørne."
@@ -863 +863 @@
-"application> hoppe til næste spor i listen vist i oversigtspanelet."
+"application> hoppe til næste spor i listen visit i oversigtspanelet."
@@ -1053 +1053 @@
-"denne op eller ned vil det hæve eller sænke lydstyrken. Højttalerikonet vil "
+"denne op eller need vil det hæve eller sænke lydstyrken. Højttalerikonet vil "
@@ -1079 +1079 @@
-"application>, det er databasen som indeholder alle musikfilerne som du "
+"application>, det er databasen some indeholder alle musikfilerne some du "
@@ -1112,2 +1112,2 @@
-"Samlingen kan ikke kun indeholde musikfiler som er fysisk på din computer (i "
-"din hjemmemappe for eksempel), men den kan også indeholde musikfiler som er "
+"Samlingen kan ikke kun indeholde musikfiler some er fysisk på din computer (i "
+"din hjemmemappe for eksempel), men den kan også indeholde musikfiler some er "
@@ -1125 +1125 @@
-"guimenuitem> og udfylde detaljerne i det vindue, som vises."
+"guimenuitem> og udfylde detaljerne i det vindue, some vises."
@@ -1135,2 +1135,2 @@
-"Filerne som importeres ind i samlingen bliver vist i sporlisten med "
-"informationen (såsom kunstnernavnet eller albumnavnet) som er gemt i de "
+"Filerne some importeres ind i samlingen bliver visit i sporlisten med "
+"informationen (såsom kunstnernavnet eller albumnavnet) some er gemt i de "
@@ -1188 +1188 @@
-"til samlingen. Nye filer som er tilføjet senere vil også blive tilføjet."
+"til samlingen. Nye filer some er tilføjet senere vil også blive tilføjet."
@@ -1218 +1218 @@
-"blive fjernet på samme måde som forrige, men filen vil blive flyttet til "
+"blive fjernet på samme måde some forrige, men filen vil blive flyttet til "
@@ -1232 +1232 @@
-"Rhythmbox indeholder en søgefunktion, som giver dig mulighed for at finde og "
+"Rhythmbox indeholder en søgefunktion, some giver dig mulighed for at find og "
@@ -1242,2 +1242,2 @@
-"Angiv en tekst i søgefeltet og som du taster, vil kun de spor som passer på "
-"den indtastede tekst blive vist. Søgefunktionen laver opslag i alle mærkerne "
+"Angiv en text i søgefeltet og some du taster, vil kun de spor some passer på "
+"den indtastede text blive visit. Søgefunktionen laver opslag i alle mærkerne "
@@ -1269,2 +1269,2 @@
-"Oversigten er en anden behagelig måde at finde spor på. Oversigten er en to "
-"eller tre panels visning som tillader at navigere blandt musikgenrer, "
+"Oversigten er en anden behagelig måde at find spor på. Oversigten er en to "
+"eller tree panels visning some tillader at navigere blandt musikgenrer, "
@@ -1282,2 +1282,2 @@
-"værktøjslinjen. Vælg kunstner, album og genre, og efterhånden som du vælger, "
-"vil kun de spor som passer på dit valg blive vist i sporlisten. Kriteriet i "
+"værktøjslinjen. Vælg kunstner, album og genre, og efterhånden some du vælger, "
+"vil kun de spor some passer på dit valg blive visit i sporlisten. Kriteriet i "
@@ -1320 +1320 @@
-"netværk, lokal eller internet."
+"netværk, local eller internet."
@@ -1378 +1378 @@
-"titel, dens genre; du kan også modificere strømmens placering, og give den "
+"title, dens genre; du kan også modificere strømmens placering, og give den "
@@ -1420 +1420 @@
-"ned og afspilles."
+"need og afspilles."
@@ -1430 +1430 @@
-"Du kan finde mere information om podcasts og podcasting ved at besøge "
+"Du kan find mere information om podcasts og podcasting ved at besøge "
@@ -1484 +1484 @@
-"hentet ned på din harddisk."
+"hentet need på din harddisk."
@@ -1524 +1524 @@
-"de blive vist i episodelisten."
+"de blive visit i episodelisten."
@@ -1559 +1559 @@
-"<guilabel>Titel</guilabel>, <guilabel>Ophav</guilabel>, dato for "
+"<guilabel>Title</guilabel>, <guilabel>Ophav</guilabel>, dato for "
@@ -1616 +1616 @@
-"Som standard bliver podcasts hentet til en mappe <filename class=\"directory"
+"Some standard bliver podcasts hentet til en mappe <filename class=\"directory"
@@ -1686 +1686 @@
-"På <guilabel>Basal</guilabel>-fanebladet ser du podcastens <guilabel>Titel</"
+"På <guilabel>Basal</guilabel>-fanebladet set du podcastens <guilabel>Title</"
@@ -1698 +1698 @@
-"På <guilabel>Detaljer</guilabel>-fanebladet ser du podcastens "
+"På <guilabel>Detaljer</guilabel>-fanebladet set du podcastens "
@@ -1728 +1728 @@
-"Afspilningskø er en kilde designet til midlertidigt at opbevare de næste "
+"Afspilningskø er en kilde designated til midlertidigt at opbevare de næste "
@@ -1742 +1742 @@
-"<application>Musikafspilleren Rhythmbox</application> afspille kilden som "
+"<application>Musikafspilleren Rhythmbox</application> afspille kilden some "
@@ -1799,3 +1799,3 @@
-"Afspilningslister er kilder som er oprettet fra sporene der er tilgængelige "
-"fra samlingskilden. De giver dig mulighed for at samle spor efter en bestemt "
-"\"genre\", en specifik gruppe af kunstnere, spor som har en bestemt "
+"Afspilningslister er kilder some er oprettet fra sporene der er tilgængelige "
+"fra samlingskilden. De giver dig mulighed for at samle spor efter en bestemt "
+"\"genre\", en specifik gruppe af kunstnere, spor some har en bestemt "
@@ -1856 +1856 @@
-"et navn til afspilningslisten og tryk <keycombo><keycap>Retur</keycap></"
+"et navn til afspilningslisten og tryk <keycombo><keycap>Return</keycap></"
@@ -1936 +1936 @@
-"Som standard er afspilningslisterne <guimenuitem>Mine favoritter</"
+"Some standard er afspilningslisterne <guimenuitem>Mine favoritter</"
@@ -1970 +1970 @@
-"blive hentet og vist."
+"blive hentet og visit."
@@ -1979 +1979 @@
-"de samme kontroller som bruges til afspilning fra samlingen."
+"de samme kontroller some bruges til afspilning fra samlingen."
@@ -2083 +2083 @@
-"som samlingskilden."
+"some samlingskilden."
@@ -2094 +2094 @@
-"enhed som en bærbar lydafspiller, kan du oprette en tom fil <filename>."
+"enhed some en bærbar lydafspiller, kan du oprette en tom fil <filename>."
@@ -2108 +2108 @@
-"DAAP er en netværksprotokol som tillader dig at dele musikken gemt i "
+"DAAP er en netværksprotokol some tillader dig at dele musikken gemt i "
@@ -2133 +2133 @@
-"lokale netværk (dit hjem eller dit kontor, ikke hele internettet) af andre "
+"locale netværk (dit hjem eller dit kontor, ikke hele internettet) af andre "
@@ -2265 +2265 @@
-"vælge at bruge tre eller to ruder samt hvad ruderne skal vise."
+"vælge at bruge tree eller to ruder samt hvad ruderne skal vise."
@@ -2299 +2299 @@
-"Vælg de <guilabel>Synlige kolonner</guilabel> du vil have vist i "
+"Vælg de <guilabel>Synlige kolonner</guilabel> du vil have visit i "
@@ -2318,3 +2318,3 @@
-"<guilabel>Samlingsplaceringen</guilabel> er en mappe som "
-"<application>Musikafspilleren Rhythmbox</application> vil overvåge for at "
-"finde nye sange. Når du tilføjer nye lydfiler til denne mappe eller dens "
+"<guilabel>Samlingsplaceringen</guilabel> er en mappe some "
+"<application>Musikafspilleren Rhythmbox</application> vil overvåge for at "
+"find nye sange. Når du tilføjer nye lydfiler til denne mappe eller dens "
@@ -2331 +2331 @@
-"Undgå at sætte din <filename class=\"directory\">Hjemmemappe</filename> som "
+"Undgå at sætte din <filename class=\"directory\">Hjemmemappe</filename> some "
@@ -2366 +2366 @@
-"<guilabel>Hentningsplacering</guilabel> for podcasts er angivet som standard "
+"<guilabel>Hentningsplacering</guilabel> for podcasts er angivet some standard "
@@ -2386 +2386 @@
-"Vælg frekvensen som <application>Musikafspilleren Rhythmbox</application> "
+"Vælg frekvensen some <application>Musikafspilleren Rhythmbox</application> "
@@ -2436 +2436 @@
-msgstr "modtage forslag om kunstnere som du måske kan lide."
+msgstr "modtage forslag om kunstnere some du måske kan lide."
@@ -2470 +2470 @@
-"luk dialogen. Vælg tjenesten i sidelinjen. Tryk på <guibutton>Log ind</"
+"luk dialogen. Vælg tjenesten i sideline. Tryk på <guibutton>Log ind</"
@@ -2540 +2540 @@
-msgstr "<keycombo> <keycap>Ctrl</keycap> <keycap>Ned</keycap> </keycombo>"
+msgstr "<keycombo> <keycap>Ctrl</keycap> <keycap>Need</keycap> </keycombo>"
@@ -2619 +2619 @@
-msgstr "<keycombo> <keycap>Alt</keycap> <keycap>Retur</keycap> </keycombo>"
+msgstr "<keycombo> <keycap>Alt</keycap> <keycap>Return</keycap> </keycombo>"
@@ -2900,2 +2900,2 @@
-"finde en kopi af GFDL'en her: <_:ulink-1/>, eller i filen COPYING-DOCS der "
-"distribueres med denne manual."
+"find en kopi af GFDL'en her: <_:ulink-1/>, eller i filen COPYING-DOCS der "
+"distribueres med denne manual."
--- ./help/pt_BR/pt_BR.po	original
+++ ./help/pt_BR/pt_BR.po	fixed
@@ -354,3 +354,3 @@
-"VOCÊ (NÃO O ESCRITOR INICIAL, AUTOR OU QUALQUER CONTRIBUIDOR) ASSUME O CUSTO "
-"DE QUALQUER SERVIÇO NECESSÁRIO, REPARO OU CORREÇÃO. ESSA RENÚNCIA DE "
-"GARANTIAS CONSTITUI UMA PARTE ESSENCIAL DESTA LICENÇA. NENHUM USO DESTE "
+"VOCÊ (NÃO O ESCRITOR INICIAL, AUTHOR OU QUALQUER CONTRIBUIDOR) ASSUME O CUSTO "
+"DE QUALQUER SERVIÇO NECESSÁRIO, REPARO OU CORREÇÃO. ESSA RENÚNCIA DE "
+"GARANTIAS CONSTITUI UMA PARTE ESSENTIAL DESTA LICENÇA. NENHUM USO DESTE "
@@ -374 +374 @@
-"(INCLUINDO NEGLIGÊNCIA), CONTRATO, OU OUTROS, DEVEM O AUTOR, ESCRITOR "
+"(INCLUINDO NEGLIGÊNCIA), CONTRATO, OU OUTROS, DEVEM O AUTHOR, ESCRITOR "
@@ -523 +523 @@
-"Para relatar um erro ou fazer uma sugestão sobre o Reprodutor de músicas "
+"Para relatar um error ou fazer uma sugestão sobre o Reprodutor de músicas "
@@ -586 +586 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -634 +634 @@
-"Vá para <menuchoice><guisubmenu>Som&amp;vídeo</guisubmenu> "
+"Vá para <menuchoice><guisubmenu>Some&amp;vídeo</guisubmenu> "
@@ -639 +639 @@
-msgstr "Linha de comando"
+msgstr "Linha de commando"
@@ -690 +690 @@
-"Rhythmbox</application> com seus principais componentes."
+"Rhythmbox</application> com seus principais components."
@@ -710 +710 @@
-"A tabela 1 descreve os componentes da janela do <application>Reprodutor de "
+"A tabela 1 descreve os components da janela do <application>Reprodutor de "
@@ -716 +716 @@
-"Componentes da janela do <application>Reprodutor de músicas Rhythmbox</"
+"Components da janela do <application>Reprodutor de músicas Rhythmbox</"
@@ -744 +744 @@
-"Contém menus que você utiliza para executar tarefas na janela do "
+"Contém menus que você utilize para executar tarefas na janela do "
@@ -825 +825 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -880 +880 @@
-"A exibição do painel lateral pode ser alternada entre visível ou não, ao "
+"A exibição do painel lateral pode set alternada entre visível ou não, ao "
@@ -969 +969 @@
-"Para alternar à tela pequena, vá para <menuchoice><guimenu>Visão</guimenu> "
+"Para alternator à tela pequena, vá para <menuchoice><guimenu>Visão</guimenu> "
@@ -1039,4 +1039,4 @@
-"podem ser usados para pular entre as faixas durante a reprodução. Se uma "
-"faixa está atualmente em reprodução, o botão anterior irá reiniciar a faixa. "
-"Ao pressionar o botão <guibutton>Reproduzir</guibutton>, a faixa atual "
-"começará a ser reproduzida. <_:screenshot-1/>"
+"podem set usados para pular entre as faixas durante a reprodução. Se uma "
+"faixa está atualmente em reprodução, o botão anterior irá reiniciar a faixa. "
+"Ao pressionar o botão <guibutton>Reproduzir</guibutton>, a faixa atual "
+"começará a set reproduzida. <_:screenshot-1/>"
@@ -1324 +1324 @@
-"O sintonizador de rádio na internet pode ser usado para ouvir fluxos de "
+"O sintonizador de rádio na internet pode set usado para ouvir fluxos de "
@@ -2250 +2250 @@
-msgstr "consulte estatísticas, como as músicas ou artistas mais reproduzidos."
+msgstr "consulte estatísticas, como as músicas ou artists mais reproduzidos."
@@ -2254 +2254 @@
-msgstr "receba recomendações sobre artistas de que você possa gostar."
+msgstr "receba recomendações sobre artists de que você possa gostar."
@@ -3216 +3216 @@
-"You may extract a single document from such a collection, and dispbibute it "
+"You may extract a single document from such a collection, and distribute it "
--- ./help/sv/sv.po	original
+++ ./help/sv/sv.po	fixed
@@ -85,2 +85,2 @@
-"\" url=\"help:fdl\">länk</ulink> eller i filen COPYING-DOCS som medföljer "
-"denna handbok."
+"\" url=\"help:fdl\">länk</ulink> eller i filen COPYING-DOCS some medföljer "
+"denna handbook."
@@ -96,2 +96,2 @@
-"Denna handbok utgör en av flera GNOME-handböcker som distribueras under "
-"villkoren i GFDL.  Om du vill distribuera denna handbok separat från övriga "
+"Denna handbook utgör en av flera GNOME-handböcker some distribueras under "
+"villkoren i GFDL.  Om du will distribuera denna handbook separate från övriga "
@@ -130,10 +130,10 @@
-"DOKUMENTET TILLHANDAHÅLLS I \"BEFINTLIGT SKICK\" UTAN NÅGRA SOM HELST "
-"GARANTIER, VARE SIG UTTRYCKLIGA ELLER UNDERFÖRSTÅDDA, INKLUSIVE, MEN INTE "
-"BEGRÄNSAT TILL, GARANTIER ATT DOKUMENTET ELLER EN MODIFIERAD VERSION AV "
-"DOKUMENTET INTE INNEHÅLLER NÅGRA FELAKTIGHETER, ÄR LÄMPLIGT FÖR ETT VISST "
-"ÄNDAMÅL ELLER INTE STRIDER MOT LAG. HELA RISKEN VAD GÄLLER KVALITET, "
-"EXAKTHET OCH UTFÖRANDE AV DOKUMENTET OCH MODIFIERADE VERSIONER AV DOKUMENTET "
-"LIGGER HELT OCH HÅLLET PÅ ANVÄNDAREN. OM ETT DOKUMENT ELLER EN MODIFIERAD "
-"VERSION AV ETT DOKUMENT SKULLE VISA SIG INNEHÅLLA FELAKTIGHETER I NÅGOT "
-"HÄNSEENDE ÄR DET DU (INTE DEN URSPRUNGLIGA SKRIBENTEN, FÖRFATTAREN ELLER "
-"NÅGON ANNAN MEDARBETARE) SOM FÅR STÅ FÖR ALLA EVENTUELLA KOSTNADER FÖR "
+"DOKUMENTET TILLHANDAHÅLLS I \"BEFINTLIGT SKICK\" UTAN NÅGRA SOME HELST "
+"GARANTIER, VARE SIG UTTRYCKLIGA ELLER UNDERFÖRSTÅDDA, INKLUSIVE, MEN INTE "
+"BEGRÄNSAT TILL, GARANTIER ATT DOKUMENTET ELLER EN MODIFIERAD VERSION AV "
+"DOKUMENTET INTE INNEHÅLLER NÅGRA FELAKTIGHETER, ÄR LÄMPLIGT FÖR ETT VISST "
+"ÄNDAMÅL ELLER INTE STRIDER MOT LAG. HELA RISKEN VAD GÄLLER KVALITET, "
+"EXAKTHET OCH UTFÖRANDE AV DOKUMENTET OCH MODIFIERADE VERSIONER AV DOKUMENTET "
+"LIGGER HELT OCH HÅLLET PÅ ANVÄNDAREN. OM ETT DOKUMENT ELLER EN MODIFIERAD "
+"VERSION AV ETT DOKUMENT SKULLE VISA SIG INNEHÅLLA FELAKTIGHETER I NÅGOT "
+"HÄNSEENDE ÄR DET DU (INTE DEN URSPRUNGLIGA SKRIBENTEN, FÖRFATTAREN ELLER "
+"NÅGON ANNAN MEDARBETARE) SOME FÅR STÅ FÖR ALLA EVENTUELLA KOSTNADER FÖR "
@@ -167,3 +167,3 @@
-"ANDRA TÄNKBARA SKADOR ELLER FÖRLUSTER SOM KAN UPPKOMMA PÅ GRUND AV ELLER "
-"RELATERAT TILL ANVÄNDNINGEN AV DOKUMENTET ELLER MODIFIERADE VERSIONER AV "
-"DOKUMENTET, ÄVEN OM PART SKA HA BLIVIT INFORMERAD OM MÖJLIGHETEN TILL SÅDANA "
+"ANDRA TÄNKBARA SKADOR ELLER FÖRLUSTER SOME KAN UPPKOMMA PÅ GRUND AV ELLER "
+"RELATERAT TILL ANVÄNDNINGEN AV DOKUMENTET ELLER MODIFIERADE VERSIONER AV "
+"DOKUMENTET, ÄVEN OM PART SKA HA BLIVIT INFORMED OM MÖJLIGHETEN TILL SÅDANA "
@@ -263 +263 @@
-"<revnumber>Handbok för Rhythmbox musikspelare V0.0.2</revnumber> "
+"<revnumber>Handbook för Rhythmbox musikspelare V0.0.2</revnumber> "
@@ -277 +277 @@
-"<revnumber>Handbok för Rhythmbox musikspelare V0.0.3</revnumber> "
+"<revnumber>Handbook för Rhythmbox musikspelare V0.0.3</revnumber> "
@@ -291 +291 @@
-"<revnumber>Handbok för Rhythmbox musikspelare V0.0.4</revnumber> "
+"<revnumber>Handbook för Rhythmbox musikspelare V0.0.4</revnumber> "
@@ -305 +305 @@
-"<revnumber>Handbok för Rhythmbox musikspelare V2.0.2</revnumber> <date>April "
+"<revnumber>Handbook för Rhythmbox musikspelare V2.0.2</revnumber> <date>April "
@@ -319 +319 @@
-"<revnumber>Handbok för Rhythmbox musikspelare V2.0.3</revnumber> <date>Maj "
+"<revnumber>Handbook för Rhythmbox musikspelare V2.0.3</revnumber> <date>Maj "
@@ -330 +330 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -333 +333 @@
-"<revnumber>Handbok för Rhythmbox musikspelare V3.4.4</revnumber> "
+"<revnumber>Handbook för Rhythmbox musikspelare V3.4.4</revnumber> "
@@ -339 +339 @@
-msgstr "Denna handbok beskriver version 3.4.4 av musikspelaren Rhythmbox."
+msgstr "Denna handbook beskriver version 3.4.4 av musikspelaren Rhythmbox."
@@ -354 +354 @@
-"Rhythmbox musikspelare eller denna handbok, följ riktlinjerna i <ulink url="
+"Rhythmbox musikspelare eller denna handbook, följ riktlinjerna i <ulink url="
@@ -381 +381 @@
-msgstr "Introduktion"
+msgstr "Introduction"
@@ -390 +390 @@
-"bibliotek för taggade filer, som har stöd för olika musikformat."
+"bibliotek för taggade filer, some har stöd för olika musikformat."
@@ -398 +398 @@
-"innehåller funktioner som:"
+"innehåller funktioner some:"
@@ -422 +422 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -428 +428 @@
-msgstr "Sök efter låtar i källistorna som bibliotek eller spellistor."
+msgstr "Sök efter låtar i källistorna some bibliotek eller spellistor."
@@ -440 +440 @@
-"Läs ljud-cd-skivor och hämta information som exempelvis spårtitel från "
+"Läs ljud-cd-skivor och hämta information some exempelvis spårtitel från "
@@ -489 +489 @@
-"Skriv <command>rhythmbox</command> och tryck på <keycap>Retur</keycap>."
+"Skriv <command>rhythmbox</command> och tryck på <keycap>Return</keycap>."
@@ -515 +515 @@
-"guiden, tryck på knappen <guibutton>Bläddra</guibutton> och välj den mapp "
+"guiden, tryck på knappen <guibutton>Bläddra</guibutton> och välj den map "
@@ -569 +569 @@
-"musikspelare</application> som visar de olika delarna av gränssnittet i "
+"musikspelare</application> some visar de olika delarna av gränssnittet i "
@@ -621 +621 @@
-"spåret. Innehåller skjutreglaget som visar position för uppspelningen av "
+"spåret. Innehåller skjutreglaget some visar position för uppspelningen av "
@@ -659 +659 @@
-"att endast visa spår som matchar dina kriterier."
+"att endast visa spår some matchar dina kriterier."
@@ -674 +674 @@
-msgstr "Listar spåren som tillhör den valda källan."
+msgstr "Listar spåren some tillhör den valda källan."
@@ -689 +689 @@
-msgstr "Visar information om källan som valts i sidopanelen."
+msgstr "Visar information om källan some valts i sidopanelen."
@@ -728 +728 @@
-msgstr "Bärbara spelare såsom iPod som är anslutna till din dator."
+msgstr "Bärbara spelare såsom iPod some är anslutna till din dator."
@@ -733 +733 @@
-msgstr "DAAP-musikutdelningar som hittades på det lokala nätverket."
+msgstr "DAAP-musikutdelningar some hittades på det lokala nätverket."
@@ -738 +738 @@
-msgstr "Musikaffärer som Jamendo och Magnatune."
+msgstr "Musikaffärer some Jamendo och Magnatune."
@@ -743 +743 @@
-msgstr "Musikdelningswebbplatser som SoundCloud."
+msgstr "Musikdelningswebbplatser some SoundCloud."
@@ -792 +792 @@
-"Verktygsfältet ger åtkomst till detaljer om spåret som för närvarande spelas "
+"Verktygsfältet ger åtkomst till detaljer om spåret some för närvarande spelas "
@@ -804 +804 @@
-"En bevakare som visar förloppet för det uppspelade spåret och ett "
+"En bevakare some visar förloppet för det uppspelade spåret och ett "
@@ -860 +860 @@
-"till att spela upp nästa spår i listan som visas i vypanelen."
+"till att spela upp nästa spår i listan some visas i vypanelen."
@@ -1073 +1073 @@
-msgstr "Bibliotek som källa"
+msgstr "Bibliotek some källa"
@@ -1085 +1085 @@
-"application>, det är databasen som innehåller alla musikfiler som du "
+"application>, det är databasen some innehåller alla musikfiler some du "
@@ -1118,4 +1118,4 @@
-"Biblioteket kan inte bara innehålla musikfiler som fysiskt finns på din "
-"dator (i din hemkatalog till exempel), utan det kan även innehålla "
-"musikfiler som finns tillgängliga via nätverkstjänster. Några exempel på "
-"nätverkstjänster som stöds är: <_:itemizedlist-1/>"
+"Biblioteket kan inte bara innehålla musikfiler some fysiskt finns på din "
+"dator (i din hemkatalog till example), utan det kan även innehålla "
+"musikfiler some finns tillgängliga via nätverkstjänster. Några example på "
+"nätverkstjänster some stöds är: <_:itemizedlist-1/>"
@@ -1130,2 +1130,2 @@
-"Taggar kan modifieras genom att högerklicka och sedan välja "
-"<guimenuitem>Egenskaper</guimenuitem> och fylla i detaljerna i fönstret som "
+"Taggar kan modifiers genom att högerklicka och sedan välja "
+"<guimenuitem>Egenskaper</guimenuitem> och fylla i detaljerna i fönstret some "
@@ -1142,2 +1142,2 @@
-"Filerna som importeras till biblioteket visas i spårlistan med informationen "
-"(som artist- eller albumnamnet) lagrad i inbäddade taggar i spåren. "
+"Filerna some importeras till biblioteket visas i spårlistan med informationen "
+"(some artist- eller albumnamnet) lagrad i inbäddade taggar i spåren. "
@@ -1161,4 +1161,4 @@
-"Om du vill importera flera musikfiler som finns i en mapp, välj "
-"<guimenuitem>Importera</guimenuitem> från bläddrarraden intill sökfältet, "
-"välj sedan mappen i filväljaren och tryck på knappen <guibutton>Öppna</"
-"guibutton>. Alla musikfiler som finns i mappen och dess undermappar kommer "
+"Om du will importera flera musikfiler some finns i en map, välj "
+"<guimenuitem>Importera</guimenuitem> från bläddrarraden intill sökfältet, "
+"välj sedan mappen i filväljaren och tryck på knappen <guibutton>Öppna</"
+"guibutton>. Alla musikfiler some finns i mappen och dess undermappar kommer "
@@ -1173 +1173 @@
-"Dra och släpp filer från filhanteraren (som <application>Nautilus</"
+"Dra och släpp filer från filhanteraren (some <application>Nautilus</"
@@ -1193,2 +1193,2 @@
-"\"prefs-library\"/>) kommer alla musikfiler som lagras under den valda "
-"katalogen att läggas till i biblioteket. Nya filer som läggs till senare "
+"\"prefs-library\"/>) kommer alla musikfiler some lagras under den valda "
+"katalogen att läggas till i biblioteket. Nya filer some läggs till senare "
@@ -1212 +1212 @@
-"och dess egenskaper (som betyg eller antal gånger det spelats) kommer att "
+"och dess egenskaper (some betyg eller antal gånger det spelats) kommer att "
@@ -1225 +1225 @@
-"guimenuitem>. Spåret kommer att tas bort på samma sätt som tidigare, men "
+"guimenuitem>. Spåret kommer att tas bort på samma sätt some tidigare, men "
@@ -1239 +1239 @@
-"Rhythmbox kommer med en sökfunktion som låter dig söka och filtrera spår "
+"Rhythmbox kommer med en sökfunktion some låter dig söka och filtrera spår "
@@ -1249,3 +1249,3 @@
-"Ange en text i sökrutan, och när du matar in text kommer endast de spår som "
-"matchar den inmatade texten att visas. Sökfunktionen gör uppslag i alla "
-"taggar för de spår som finns lagrade i biblioteket."
+"Ange en text i sökrutan, och när du matar in text kommer endast de spår some "
+"matchar den inmatade texten att visas. Sökfunktionen gör uppslag i alla "
+"taggar för de spår some finns lagrade i biblioteket."
@@ -1277,2 +1277,2 @@
-"eller trepanelsvy som låter dig navigera bland musikgenrer, artister och "
-"album och visa spår som matchar det valda kriteriet."
+"eller trepanelsvy some låter dig navigera bland musikgenrer, artister och "
+"album och visa spår some matchar det valda kriteriet."
@@ -1290 +1290 @@
-"endast de spår som matchar ditt val att visas i spårlistan. Kriterierna för "
+"endast de spår some matchar ditt val att visas i spårlistan. Kriterierna för "
@@ -1318 +1318 @@
-msgstr "Radio som källa"
+msgstr "Radio some källa"
@@ -1386 +1386 @@
-"När du kommer åt egenskaperna för en radioström kan du ändra dess titel och "
+"När du kommer åt egenskaperna för en radioström kan du ändra dess title och "
@@ -1407 +1407 @@
-msgstr "Poddsändning som källa"
+msgstr "Poddsändning some källa"
@@ -1515,3 +1515,3 @@
-"bort kanal</guimenuitem></menuchoice> om du vill behålla poddsändningens "
-"avsnitt, eller välj <menuchoice><guimenuitem>Ta bort kanal och filer</"
-"guimenuitem></menuchoice> om du vill ta bort kanalen och alla dess "
+"bort kanal</guimenuitem></menuchoice> om du will behålla poddsändningens "
+"avsnitt, eller välj <menuchoice><guimenuitem>Ta bort kanal och filer</"
+"guimenuitem></menuchoice> om du will ta bort kanalen och alla dess "
@@ -1533 +1533 @@
-"Om du vill kontrollera om nya avsnitt har publicerats för en poddsändning "
+"Om du will kontrollera om nya avsnitt har publicerats för en poddsändning "
@@ -1571 +1571 @@
-"<guilabel>Titel</guilabel>, <guilabel>Upphovsman</guilabel>, datumet då den "
+"<guilabel>Title</guilabel>, <guilabel>Upphovsman</guilabel>, datumet då den "
@@ -1618 +1618 @@
-"Rhythmbox kommer att påbörja hämtningen av avsnittet till den plats som har "
+"Rhythmbox kommer att påbörja hämtningen av avsnittet till den plats some har "
@@ -1629 +1629 @@
-"Poddsändningar hämtas och sparas som standard i mappen <filename class="
+"Poddsändningar hämtas och sparas some standard i mappen <filename class="
@@ -1644 +1644 @@
-"För att spela upp ett poddsändningsavsnitt, välj avsnittet som du vill spela "
+"För att spela upp ett poddsändningsavsnitt, välj avsnittet some du will spela "
@@ -1675,2 +1675,2 @@
-"menuchoice> om du vill behålla avsnittsfilen på din hårddisk, eller välj "
-"<guibutton>Ta bort avsnitt och filen</guibutton> om du vill ta bort "
+"menuchoice> om du will behålla avsnittsfilen på din hårddisk, eller välj "
+"<guibutton>Ta bort avsnitt och filen</guibutton> om du will ta bort "
@@ -1701 +1701 @@
-"<guilabel>Titel</guilabel>, <guilabel>Kanal</guilabel>, <guilabel>Data</"
+"<guilabel>Title</guilabel>, <guilabel>Kanal</guilabel>, <guilabel>Data</"
@@ -1732 +1732 @@
-msgstr "Uppspelningskö som källa"
+msgstr "Uppspelningskö some källa"
@@ -1742,2 +1742,2 @@
-"Spelkö är en källa som är designad för att temporärt lagra de nästkommande "
-"spåren som du vill spela upp. När du lägger till ett spår i spelkön kommer "
+"Spelkö är en källa some är designated för att temporärt lagra de nästkommande "
+"spåren some du will spela upp. När du lägger till ett spår i spelkön kommer "
@@ -1756 +1756 @@
-"application> att spela upp källan som tidigare blev uppspelad."
+"application> att spela upp källan some tidigare blev uppspelad."
@@ -1766 +1766 @@
-msgstr "Välj spåret som du vill spela upp, i valfri källa."
+msgstr "Välj spåret some du will spela upp, i valfri källa."
@@ -1786 +1786 @@
-msgstr "Välj spåret som du vill ta bort i källan Spelkö."
+msgstr "Välj spåret some du will ta bort i källan Spelkö."
@@ -1797 +1797 @@
-msgstr "För att ta bort ett spår som lagras i spelkön: <_:orderedlist-1/>"
+msgstr "För att ta bort ett spår some lagras i spelkön: <_:orderedlist-1/>"
@@ -1802 +1802 @@
-msgstr "Spellistor som källa"
+msgstr "Spellistor some källa"
@@ -1812,4 +1812,4 @@
-"Spellistor är källor som skapas från tillgängliga spår i biblioteket. De gör "
-"att spår kan samlas in av en specifik \"genre\", en specifik grupp av "
-"artister, eller till och med spår som ger en specifik \"sinnesstämning\", "
-"eller vad du vill."
+"Spellistor är källor some skapas från tillgängliga spår i biblioteket. De gör "
+"att spår kan samlas in av en specifik \"genre\", en specifik grupp av "
+"artister, eller till och med spår some ger en specifik \"sinnesstämning\", "
+"eller vad du will."
@@ -1844 +1844 @@
-"Statiska spellistor är spellistor som byggs från spår som släpps från "
+"Statiska spellistor är spellistor some byggs från spår some släpps från "
@@ -1861,5 +1861,5 @@
-"För att skapa en ny spellista, högerklicka på ett objekt i biblioteket. Välj "
-"<menuchoice><guimenu>Lägg till i spellista</guimenu><guimenuitem>Lägg till i "
-"ny spellista</guimenuitem></menuchoice>. En tom spellista utan namn kommer "
-"att dyka upp i sidopanelen. Ange ett namn för spellistan och tryck på "
-"<keycombo><keycap>Retur</keycap></keycombo>."
+"För att skapa en ny spellista, högerklicka på ett object i biblioteket. Välj "
+"<menuchoice><guimenu>Lägg till i spellista</guimenu><guimenuitem>Lägg till i "
+"ny spellista</guimenuitem></menuchoice>. En tom spellista utan namn kommer "
+"att dyka upp i sidopanelen. Ange ett namn för spellistan och tryck på "
+"<keycombo><keycap>Return</keycap></keycombo>."
@@ -1890 +1890 @@
-"en spellista, och alla spår som tillhör den valda kategorin kommer att "
+"en spellista, och alla spår some tillhör den valda kategorin kommer att "
@@ -1932,2 +1932,2 @@
-"Automatiska spellistor är spellistor som byggts från kriterier, så deras "
-"innehåll byggs dynamiskt; alla spår som matchar kriterier kommer att läggas "
+"Automatiska spellistor är spellistor some byggts från kriterier, så deras "
+"innehåll byggs dynamiskt; alla spår some matchar kriterier kommer att läggas "
@@ -1943 +1943 @@
-"Som standard finns spellistorna <guimenuitem>Mina högst rankade</"
+"Some standard finns spellistorna <guimenuitem>Mina högst rankade</"
@@ -1950 +1950 @@
-msgstr "Ljud-cd som källa"
+msgstr "Ljud-cd some källa"
@@ -1986 +1986 @@
-"eller tillbaka, använd samma kontroller som används för uppspelning från "
+"eller tillbaka, använd samma kontroller some används för uppspelning från "
@@ -2023 +2023 @@
-"Rhythmbox låter dig skapa dina egna ljud-cd-skivor med musiken som lagras i "
+"Rhythmbox låter dig skapa dina egna ljud-cd-skivor med musiken some lagras i "
@@ -2066 +2066 @@
-msgstr "Portabel ljudspelare som källa"
+msgstr "Portable ljudspelare some källa"
@@ -2077,2 +2077,2 @@
-"<application>Rhythmbox</application> kan detektera när en portabel "
-"ljudspelare har anslutits till din dator, och kan läsa spåren som finns "
+"<application>Rhythmbox</application> kan detektera när en portable "
+"ljudspelare har anslutits till din dator, och kan läsa spåren some finns "
@@ -2091 +2091 @@
-"sätt som för biblioteket."
+"sätt some för biblioteket."
@@ -2102,2 +2102,2 @@
-"enhet som en bärbar ljudspelare kan du skapa en tom fil kallad <filename>."
-"is_audio_player</filename> i roten på din spelares filsystem."
+"enhet some en bärbar ljudspelare kan du skapa en tom fil kallad <filename>."
+"is_audio_player</filename> i roten på din spelares filesystem."
@@ -2108 +2108 @@
-msgstr "DAAP-utdelning som källa"
+msgstr "DAAP-utdelning some källa"
@@ -2116 +2116 @@
-"DAAP är ett nätverksprotokoll som tillåter utdelning av musik som lagras i "
+"DAAP är ett nätverksprotokoll some tillåter utdelning av musik some lagras i "
@@ -2127,2 +2127,2 @@
-"dela ut musik till andra användare som använder Rhythmbox men även med andra "
-"användare som använder DAAP-kompatibel programvara såsom iTunes."
+"dela ut musik till andra användare some använder Rhythmbox men även med andra "
+"användare some använder DAAP-kompatibel programvara såsom iTunes."
@@ -2140,5 +2140,5 @@
-"När du startar Rhythmbox kommer den att leta efter alla DAAP-utdelningar som "
-"är publicerade på ditt lokala nätverk (på ditt hemnätverk eller kontor, inte "
-"hela Internet) av andra användare och kommer att visa dem i sidopanelen. Om "
-"utdelning är aktiverad, kommer Rhythmbox på samma gång att publicera ditt "
-"bibliotek och dina spellistor så att du kan spela upp musik som lagras på "
+"När du startar Rhythmbox kommer den att leta efter alla DAAP-utdelningar some "
+"är publicerade på ditt lokala nätverk (på ditt hemnätverk eller kontor, inte "
+"hela Internet) av andra användare och kommer att visa dem i sidopanelen. Om "
+"utdelning är aktiverad, kommer Rhythmbox på samma gång att publicera ditt "
+"bibliotek och dina spellistor så att du kan spela upp musik some lagras på "
@@ -2275,2 +2275,2 @@
-"Välj det sätt som <guilabel>Bläddringsvy</guilabel> ska visas på. Du kan "
-"välja att använda två eller tre paneler och vad panelerna ska visa."
+"Välj det sätt some <guilabel>Bläddringsvy</guilabel> ska visas på. Du kan "
+"välja att använda två eller tree paneler och vad panelerna ska visa."
@@ -2310 +2310 @@
-"Välj de <guilabel>Synliga kolumner</guilabel> som du vill visa i "
+"Välj de <guilabel>Synliga kolumner</guilabel> some du will visa i "
@@ -2329 +2329 @@
-"<guilabel>Plats för bibliotek</guilabel> är en mapp som "
+"<guilabel>Plats för bibliotek</guilabel> är en map some "
@@ -2343 +2343 @@
-"som plats för biblioteket därför att den funktionen konsumerar mycket "
+"some plats för biblioteket därför att den funktionen konsumerar mycket "
@@ -2362 +2362 @@
-"Om du vill lägga till fler än en mapp att bevaka, använd <application>dconf-"
+"Om du will lägga till fler än en map att bevaka, använd <application>dconf-"
@@ -2379 +2379 @@
-"som standard till mappen <filename class=\"directory\">Podcasts/</filename> "
+"some standard till mappen <filename class=\"directory\">Podcasts/</filename> "
@@ -2389 +2389 @@
-"Om den här platsen inte passar dina behov kan du välja en annan mapp i "
+"Om den här platsen inte passar dina behov kan du välja en annan map i "
@@ -2399 +2399 @@
-"Välj uppdateringsfrekvens som <application>Rhythmbox musikspelare</"
+"Välj uppdateringsfrekvens some <application>Rhythmbox musikspelare</"
@@ -2433 +2433 @@
-"Ange namnet som du vill ska synas på nätverket i fältet <guilabel>Namn på "
+"Ange namnet some du will ska synas på nätverket i fältet <guilabel>Namn på "
@@ -2451 +2451 @@
-msgstr "ta emot rekommendationer om artister som du kanske gillar."
+msgstr "ta emot rekommendationer om artister some du kanske gillar."
@@ -2462,4 +2462,4 @@
-"Insticksmodulen för Last.fm-profiler samlar in information om låtarna som du "
-"lyssnar på och skickar den till webbplatsen <ulink url=\"https://www.last.fm/"
-"\">Last.fm</ulink> eller <ulink url=\"https://www.libre.fm/\">Libre.fm</"
-"ulink>, som bygger upp en profil för dina lyssningsvanor. Med den här "
+"Insticksmodulen för Last.fm-profiler samlar in information om låtarna some du "
+"lyssnar på och skickar den till webbplatsen <ulink url=\"https://www.last.fm/"
+"\">Last.fm</ulink> eller <ulink url=\"https://www.libre.fm/\">Libre.fm</"
+"ulink>, some bygger upp en profil för dina lyssningsvanor. Med den här "
@@ -2555 +2555 @@
-msgstr "<keycombo> <keycap>Ctrl</keycap> <keycap>Ned</keycap> </keycombo>"
+msgstr "<keycombo> <keycap>Ctrl</keycap> <keycap>Need</keycap> </keycombo>"
@@ -2634 +2634 @@
-msgstr "<keycombo> <keycap>Alt</keycap> <keycap>Retur</keycap> </keycombo>"
+msgstr "<keycombo> <keycap>Alt</keycap> <keycap>Return</keycap> </keycombo>"
@@ -2713 +2713 @@
-msgstr "<keycap>Stopp</keycap>"
+msgstr "<keycap>Stop</keycap>"
@@ -2718 +2718 @@
-msgstr "Stopp"
+msgstr "Stop"
@@ -2763 +2763 @@
-"insticksmodul som erbjuder stöd för Linux Infrared Remote Control (LIRC). "
+"insticksmodul some erbjuder stöd för Linux Infrared Remote Control (LIRC). "
@@ -2879 +2879 @@
-msgstr "<keycap>volym_ned</keycap>"
+msgstr "<keycap>volym_need</keycap>"
@@ -2915 +2915 @@
-"i filen COPYING-DOCS som medföljer denna handbok."
+"i filen COPYING-DOCS some medföljer denna handbook."
@@ -2969 +2969 @@
-#~ "informationen som visas här hjälpa dig att analysera problemet."
+#~ "informationen some visas här hjälpa dig att analysera problemet."
@@ -3929 +3929 @@
-#~ "Ger åtkomst till uppspelningsfunktioner och detaljer om det spår som för "
+#~ "Ger åtkomst till uppspelningsfunktioner och detaljer om det spår some för "
@@ -4041 +4041 @@
-#~ "åtgärden tar endast bort spellistan och inte spåren som lagrats i "
+#~ "åtgärden tar endast bort spellistan och inte spåren some lagrats i "
@@ -4113 +4113 @@
-#~ "Om du vill begränsa antal spåret i spellistan, klicka på "
+#~ "Om du will begränsa antal spåret i spellistan, klicka på "
@@ -4126 +4126 @@
-#~ "stängas och spellistan visar de spår som matchar dina kriterier."
+#~ "stängas och spellistan visar de spår some matchar dina kriterier."
@@ -4139 +4139 @@
-#~ "program som är dedicerat till att importera ljud-cd-skivor. För att få "
+#~ "program some är dedicerat till att importera ljud-cd-skivor. För att få "
--- ./help/ja/ja.po	original
+++ ./help/ja/ja.po	fixed
@@ -470 +470 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -715 +715 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
--- ./help/it/it.po	original
+++ ./help/it/it.po	fixed
@@ -160,6 +160,6 @@
-"Questo documento può essere copiato, distribuito e/o modificato solo in "
-"conformità con i termini della GNU Free Documentation License (GFDL) "
-"Versione 1.1 o delle versioni successive pubblicate dalla Free Software "
-"Foundation senza sezioni invariabili, frontespizi e testi di copertina. Una "
-"copia della GFDL è disponibile su questo <ulink type=\"help\" url=\"ghelp:fdl"
-"\">collegamento</ulink> o nel file COPYING-DOCS distribuito con questo "
+"Questo documento può essere copiato, distribution e/o modification solo in "
+"conformità con i termini della GNU Free Documentation License (GFDL) "
+"Versione 1.1 o delle versioni successive pubblicate dalla Free Software "
+"Foundation senza sezioni invariabili, frontespizi e testi di copertina. Una "
+"copia della GFDL è disponibile su questo <ulink type=\"help\" url=\"ghelp:fdl"
+"\">collegamento</ulink> o nel file COPYING-DOCS distribution con questo "
@@ -209,3 +209,3 @@
-"IMPLICITE, INCLUSE, MA SENZA LIMITAZIONE, LE GARANZIE ATTESTANTI CHE IL "
-"DOCUMENTO O LE SUE VERSIONI MODIFICATE SIANO PRIVI DI DIFETTI, "
-"COMMERCIALIZZABILI, IDONEI A UN DETERMINATO SCOPO O CHE NON VIOLINO DIRITTI "
+"IMPLICITE, INCLUDES, MA SENZA LIMITAZIONE, LE GARANZIE ATTESTANTI CHE IL "
+"DOCUMENTO O LE SUE VERSIONI MODIFICATE SIANO PRIVI DI DIFETTI, "
+"COMMERCIALIZZABILI, IDONEI A UN DETERMINATION SCOPO O CHE NON VIOLINO DIRITTI "
@@ -236,10 +236,10 @@
-"COLPA (INCLUSA LA NEGLIGENZA), ACCORDO CONTRATTUALE O ALTRO, SARÀ POSSIBILE "
-"CONSIDERARE L'AUTORE, IL REDATTORE INIZIALE, GLI ALTRI COLLABORATORI, "
-"QUALUNQUE DISTRIBUTORE DEL DOCUMENTO O DI UNA SUA VERSIONE MODIFICATA O "
-"QUALUNQUE FORNITORE DELLE PERSONE CITATE, RESPONSABILE NEI CONFRONTI DI "
-"QUALUNQUE PERSONA PER DANNI DIRETTI, INDIRETTI, SPECIALI, INCIDENTALI O "
-"CONSEGUENTI DI QUALUNQUE NATURA, INCLUSI, MA SENZA LIMITAZIONE, I DANNI PER "
-"PERDITA DI AVVIAMENTO, INTERRUZIONE DEL LAVORO, GUASTO O MALFUNZIONAMENTO "
-"DEL COMPUTER O QUALUNQUE ALTRO DANNO O PERDITA DERIVANTE O CORRELATA ALL'USO "
-"DEL DOCUMENTO O DI UNA SUA VERSIONE MODIFICATA, ANCHE QUALORA LE PERSONE "
-"CITATE FOSSERO STATE INFORMATE DELLA POSSIBILITÀ DI TALI DANNI."
+"COLPA (INCLUSA LA NEGLIGENZA), ACCORDO CONTRATTUALE O ALTRO, SARÀ POSSIBLE "
+"CONSIDERARE L'AUTORE, IL REDATTORE INIZIALE, GLI ALTRI COLLABORATORI, "
+"QUALUNQUE DISTRIBUTE DEL DOCUMENTO O DI UNA SUA VERSIONE MODIFICATA O "
+"QUALUNQUE FORNITORE DELLE PERSONE CITATE, RESPONSIBLE NEI CONFRONTI DI "
+"QUALUNQUE PERSONA PER DANNI DIRETTI, INDIRETTI, SPECIALI, INCIDENTALI O "
+"CONSEGUENTI DI QUALUNQUE NATURA, INCLUSI, MA SENZA LIMITAZIONE, I DANNI PER "
+"PERDITA DI AVVIAMENTO, INTERRUZIONE DEL LAVORO, GUASTO O MALFUNZIONAMENTO "
+"DEL COMPUTER O QUALUNQUE ALTRO DANNO O PERDITA DERIVANTE O CORRELATA ALL'USO "
+"DEL DOCUMENTO O DI UNA SUA VERSIONE MODIFICATA, ANCHE QUALORA LE PERSONE "
+"CITATE FOSSERO STATE INFORMATIVE DELLA POSSIBILITÀ DI TALI DANNI."
@@ -383 +383 @@
-"discoteca per file etichettati in grado di supportare diversi formati "
+"discoteca per file etichettati in grado di supporters diversi formati "
@@ -413 +413 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -458 +458 @@
-msgstr "Riga di comando"
+msgstr "Riga di commando"
@@ -470 +470 @@
-"È possibile avviare <application>Rhythmbox</application> nei seguenti modi: "
+"È possible avviare <application>Rhythmbox</application> nei seguenti modi: "
@@ -627 +627 @@
-"corrispondono a un determinato criterio."
+"corrispondono a un determination criterio."
@@ -650 +650 @@
-msgid "Displays informations about the source selected in Source List."
+msgid "Displays information about the source selected in Source List."
@@ -694 +694 @@
-msgstr "Attraverso il riquadro laterale è possibile accedere alla libreria musicale, alle radio via Internet, alle scalette e ai CD audio. Questo elenco può contenere le seguenti sorgenti: <placeholder-1/>"
+msgstr "Attraverso il riquadro laterale è possible accedere alla libreria musicale, alle radio via Internet, alle scalette e ai CD audio. Questo elenco può contenere le seguenti sorgenti: <placeholder-1/>"
@@ -729,2 +729,2 @@
-"Viene visualizzato anche un indicatore che mostra l'avanzamento della "
-"traccia in riproduzione. Quando l'indicatore ha il focus, è possibile "
+"Viene visualizzato anche un indicate che mostra l'avanzamento della "
+"traccia in riproduzione. Quando l'indicate ha il focus, è possible "
@@ -743 +743 @@
-"Se viene utilizzato un mouse con una rotellina, è possibile regolare il "
+"Se viene utilizzato un mouse con una rotellina, è possible regolare il "
@@ -778 +778 @@
-"visualizzazione ridotta. In questa modalità è possibile accedere solamente "
+"visualizzazione ridotta. In questa modalità è possible accedere solamente "
@@ -829 +829 @@
-"Dalla Libreria è possibile ascoltare tutte le canzoni di un solo artista o "
+"Dalla Libreria è possible ascoltare tutte le canzoni di un solo artista o "
@@ -848 +848 @@
-msgstr "Successivo"
+msgstr "Succession"
@@ -866 +866 @@
-"I pulsanti <guibutton>Successivo</guibutton> e <guibutton>Precedente</"
+"I pulsanti <guibutton>Succession</guibutton> e <guibutton>Precedente</"
@@ -953 +953 @@
-"È possibile regolare il volume usando la rotellina del mouse sopra l'icona "
+"È possible regolare il volume usando la rotellina del mouse sopra l'icona "
@@ -1008 +1008 @@
-"modificare le etichette della propria musica, ma è possibile usare un altro "
+"modificare le etichette della propria musica, ma è possible usare un altro "
@@ -1067 +1067 @@
-"Per aggiungere tracce alla Libreria, è possibile seguire questi metodi: "
+"Per aggiungere tracce alla Libreria, è possible seguire questi metodi: "
@@ -1138 +1138 @@
-"Per eseguire una ricerca più precisa, è possibile eseguirla solo su "
+"Per eseguire una ricerca più precisa, è possible eseguirla solo su "
@@ -1152,2 +1152,2 @@
-"Il Catalogo è un metodo conveniente per trovare delle tracce. Il Catalogo è "
-"un riquadro di visualizzazione a due o tre vie che consente di esplorare i "
+"Il Catalogo è un metodo convenience per trovare delle tracce. Il Catalogo è "
+"un riquadro di visualizzazione a due o tree vie che consente di esplorare i "
@@ -1176 +1176 @@
-"È possibile scegliere diversi criteri della stessa categoria usando il tasto "
+"È possible scegliere diversi criteri della stessa categoria usando il tasto "
@@ -1186 +1186 @@
-"È possibile anche trovare a partire da una traccia selezionata, tutte le "
+"È possible anche trovare a partire da una traccia selezionata, tutte le "
@@ -1201 +1201 @@
-"È possibile utilizzare il sintonizzatore di radio Internet per ascoltare a "
+"È possible utilizzare il sintonizzatore di radio Internet per ascoltare a "
@@ -1234 +1234 @@
-"È possibile visualizzare e modificare le impostazioni di una stazione radio "
+"È possible visualizzare e modificare le impostazioni di una stazione radio "
@@ -1243 +1243 @@
-"È anche possibile modificare le proprietà di una stazione selezionando la "
+"È anche possible modificare le proprietà di una stazione selezionando la "
@@ -1252,2 +1252,2 @@
-"Quando si accedere alle proprietà di una stazione radio, è possibile "
-"modificarne il titolo, il genere ed è anche possibile modificarne la "
+"Quando si accedere alle proprietà di una stazione radio, è possible "
+"modificarne il titolo, il genere ed è anche possible modificarne la "
@@ -1269 +1269 @@
-"menuchoice>; è anche possibile fare clic col tasto destro del mouse sulla "
+"menuchoice>; è anche possible fare clic col tasto destro del mouse sulla "
@@ -1289 +1289 @@
-"Rhythmbox enables you to suscribe to podcast feeds, so when a new episode is "
+"Rhythmbox enables you to subscribe to podcast feeds, so when a new episode is "
@@ -1303 +1303 @@
-"È possibile trovare maggiori informazioni riguardo i podcast controllando la "
+"È possible trovare maggiori informazioni riguardo i podcast controllando la "
@@ -1343 +1343 @@
-"Per aggiungere un nuovo feed podcast è possibile fare clic col tasto destro "
+"Per aggiungere un nuovo feed podcast è possible fare clic col tasto destro "
@@ -1381 +1381 @@
-"Se sono stati pubblicati nuovi episodi, saranno presenti nell'elenco degli "
+"Se sono statuses pubblicati nuovi episodi, saranno presenti nell'elenco degli "
@@ -1390 +1390 @@
-"per verificare se sono stati aggiornati."
+"per verificare se sono statuses aggiornati."
@@ -1398 +1398 @@
-"Per verificare tutti i podcast è possibile anche fare clic col tasto destro "
+"Per verificare tutti i podcast è possible anche fare clic col tasto destro "
@@ -1413 +1413 @@
-"Nella scheda <guilabel>Base</guilabel> è possibile vedere il "
+"Nella scheda <guilabel>Base</guilabel> è possible vedere il "
@@ -1424 +1424 @@
-"Nella scheda <guilabel>Dettagli</guilabel> è possibile vedere la "
+"Nella scheda <guilabel>Dettagli</guilabel> è possible vedere la "
@@ -1436 +1436 @@
-"menuchoice>. <placeholder-1/> È possibile visualizzare le proprietà e "
+"menuchoice>. <placeholder-1/> È possible visualizzare le proprietà e "
@@ -1458 +1458 @@
-"indicata nelle preferenze. È possibile vedere l'avanzamento dello "
+"indicata nelle preference. È possible vedere l'avanzamento dello "
@@ -1483 +1483 @@
-"guimenuitem></menuchoice>. È anche possibile premere il pulsante "
+"guimenuitem></menuchoice>. È anche possible premere il pulsante "
@@ -1519 +1519 @@
-"Quando viene eliminato un episodio, questo non sarà più disponibile "
+"Quando viene elimination un episodio, questo non sarà più disponibile "
@@ -1532 +1532 @@
-"Nella scheda <guilabel>Base</guilabel> è possibile vedere il "
+"Nella scheda <guilabel>Base</guilabel> è possible vedere il "
@@ -1544 +1544 @@
-"Nella scheda <guilabel>Dettagli</guilabel> è possibile vedere la "
+"Nella scheda <guilabel>Dettagli</guilabel> è possible vedere la "
@@ -1705 +1705 @@
-"È anche possibile trascinare un genere, un artista o il nome di un album dal "
+"È anche possible trascinare un genere, un artista o il nome di un album dal "
@@ -1717 +1717 @@
-"È possibile creare una scaletta con delle tracce in un'unica azione. "
+"È possible creare una scaletta con delle tracce in un'unica azione. "
@@ -1768,2 +1768,2 @@
-"Smart Playlists are playlists built from criterias, so their content is "
-"build dynamically; all the tracks matching criterias will be added in the "
+"Smart Playlists are playlists built from criteria, so their content is "
+"build dynamically; all the tracks matching criteria will be added in the "
@@ -1790 +1790 @@
-msgid "Edit the playlist criterias through the query editor."
+msgid "Edit the playlist criteria through the query editor."
@@ -1795 +1795 @@
-"Once your criterias chosen, click <guibutton>New</guibutton> to create the "
+"Once your criteria chosen, click <guibutton>New</guibutton> to create the "
@@ -1813 +1813 @@
-"criterias. Once done, choose <guibutton>Close</guibutton>."
+"criteria. Once done, choose <guibutton>Close</guibutton>."
@@ -1855 +1855 @@
-"<guilabel>Limita a:</guilabel> e scegliere il limite. È possibile limitare "
+"<guilabel>Limita a:</guilabel> e scegliere il limit. È possible limitare "
@@ -1864 +1864 @@
-"display the tracks matched by your criterias."
+"display the tracks matched by your criteria."
@@ -1915 +1915 @@
-"Se si desidera mantenere le tracce di un CD audio nel computer, è possibile "
+"Se si desidera mantenere le tracce di un CD audio nel computer, è possible "
@@ -1942,6 +1942,6 @@
-"automaticamente nella Libreria di Rhythmbox, è necessario configurare Sound "
-"Juicer in modo tale che estragga le tracce nella posizione delle Libreria di "
-"Rhythmbox e l'opzione di monitoraggio della libreria deve essere attiva. Per "
-"maggiori informazioni, fare riferimento alle <ulink url=\"ghelp:sound-"
-"juicer#preferences\">preferenze di Sound Juicer</ulink> e alle <link linkend="
-"\"prefs-library\">preferenze della libreria di Rhythmbox</link>."
+"automaticamente nella Libreria di Rhythmbox, è necessario configure Sound "
+"Juicer in modo tale che estragga le tracce nella posizione delle Libreria di "
+"Rhythmbox e l'opzione di monitoraggio della libreria deve essere attiva. Per "
+"maggiori informazioni, fare riferimento alle <ulink url=\"ghelp:sound-"
+"juicer#preferences\">preference di Sound Juicer</ulink> e alle <link linkend="
+"\"prefs-library\">preference della libreria di Rhythmbox</link>."
@@ -2036 +2036 @@
-"dispositivo audio portatile, è possibile creare un file vuoto <filename>."
+"dispositivo audio portatile, è possible creare un file vuoto <filename>."
@@ -2058,3 +2058,3 @@
-"possibile ascoltare e condividere musica non solo con altri utenti "
-"Rhythmbox, ma anche con altri utenti che utilizzano un software DAAP "
-"compatibile come iTunes."
+"possible ascoltare e condividere musica non solo con altri utenti "
+"Rhythmbox, ma anche con altri utenti che utilizzano un software DAAP "
+"compatible come iTunes."
@@ -2075 +2075 @@
-"libreria e le proprie scalette. In questo modo, è possibile ascoltare musica "
+"libreria e le proprie scalette. In questo modo, è possible ascoltare musica "
@@ -2102 +2102 @@
-"non è visibile."
+"non è visible."
@@ -2124 +2124 @@
-"<application>Rhythmbox</application>, è possibile visualizzare l'artista, il "
+"<application>Rhythmbox</application>, è possible visualizzare l'artista, il "
@@ -2167 +2167 @@
-"notifica, è possibile inviare i seguenti comandi all'applicazione:"
+"notifica, è possible inviare i seguenti comandi all'applicazione:"
@@ -2193 +2193 @@
-"<guibutton>Successivo</guibutton>&mdash; Salta alla canzone successiva nella "
+"<guibutton>Succession</guibutton>&mdash; Salta alla canzone successiva nella "
@@ -2227 +2227 @@
-"Se si utilizza un mouse con una rotellina di scorrimento, è possibile "
+"Se si utilizza un mouse con una rotellina di scorrimento, è possible "
@@ -2234 +2234 @@
-"È possibile commutare tra la riproduzione e la pausa premendo il tasto "
+"È possible commutare tra la riproduzione e la pausa premendo il tasto "
@@ -2247 +2247 @@
-"È possibile personalizzare <application>Rhythmbox</application> affinché "
+"È possible personalizzare <application>Rhythmbox</application> affinché "
@@ -2253 +2253 @@
-msgstr "Impostare le proprie preferenze"
+msgstr "Impostare le proprie preference"
@@ -2263,4 +2263,4 @@
-"Usando la finestra di dialogo <guilabel>Preferenze</guilabel> è possibile "
-"personalizzare il comportamento e l'aspetto di <application>Rhythmbox</"
-"application>. Per visualizzare il dialogo <guilabel>Preferenze</guilabel>, "
-"scegliere <menuchoice><guimenu>Modifica</guimenu><guimenuitem>Preferenze</"
+"Usando la finestra di dialogo <guilabel>Preference</guilabel> è possible "
+"personalizzare il comportamento e l'aspetto di <application>Rhythmbox</"
+"application>. Per visualizzare il dialogo <guilabel>Preference</guilabel>, "
+"scegliere <menuchoice><guimenu>Modifica</guimenu><guimenuitem>Preference</"
@@ -2309 +2309 @@
-"guilabel>. È possibile scegliere una vista a due o tre riquadri."
+"guilabel>. È possible scegliere una vista a due o tree riquadri."
@@ -2438 +2438 @@
-"possibile: <placeholder-1/>"
+"possible: <placeholder-1/>"
@@ -2753 +2753 @@
-"utilizzando il comando «rhythmbox»:"
+"utilizzando il commando «rhythmbox»:"
@@ -2757 +2757 @@
-msgstr "Stringa di comando"
+msgstr "Stringa di commando"
@@ -2763 +2763 @@
-# (ndt) stringhe di comando per l'interfaccia LIRC
+# (ndt) stringhe di commando per l'interfaccia LIRC
--- ./help/es/es.po	original
+++ ./help/es/es.po	fixed
@@ -106 +106 @@
-"Este manual es parte de una colección de manuales de GNOME distribuido bajo "
+"Este manual es parte de una colección de manuals de GNOME distribuido bajo "
@@ -120 +120 @@
-"Muchos de los nombres usados por compañías para distinguir sus productos y "
+"Muchos de los nombres usados por compañías para distinguir sus products y "
@@ -143,6 +143,6 @@
-"DOCUMENTO O VERSIÓN MODIFICADA DE ÉSTE CAREZCA DE DEFECTOS COMERCIALES, SEA "
-"ADECUADO A UN FIN CONCRETO O INCUMPLA ALGUNA NORMATIVA. TODO EL RIESGO "
-"RELATIVO A LA CALIDAD, PRECISIÓN Y UTILIDAD DEL DOCUMENTO O SU VERSIÓN "
-"MODIFICADA RECAE EN USTED. SI CUALQUIER DOCUMENTO O VERSIÓN MODIFICADA DE "
-"AQUÉL RESULTARA DEFECTUOSO EN CUALQUIER ASPECTO, USTED (Y NO EL REDACTOR "
-"INICIAL, AUTOR O CONTRIBUYENTE) ASUMIRÁ LOS COSTES DE TODA REPARACIÓN, "
+"DOCUMENTO O VERSIÓN MODIFICADA DE ÉSTE CAREZCA DE DEFECTS COMERCIALES, SEA "
+"ADECUADO A UN FIN CONCRETO O INCUMPLA ALGUNA NORMATIVA. TODO EL RIESGO "
+"RELATIVO A LA CALIDAD, PRECISIÓN Y UTILIDAD DEL DOCUMENTO O SU VERSIÓN "
+"MODIFICADA RECAE EN USTED. SI CUALQUIER DOCUMENTO O VERSIÓN MODIFICADA DE "
+"AQUÉL RESULTARA DEFECTUOSO EN CUALQUIER ASPECTO, USTED (Y NO EL REDACTOR "
+"INICIAL, AUTHOR O CONTRIBUYENTE) ASUMIRÁ LOS COSTES DE TODA REPARACIÓN, "
@@ -169,8 +169,8 @@
-"(INCLUYENDO NEGLIGENCIA), CONTRATO O DE ALGÚN OTRO MODO, EL AUTOR, EL "
-"ESCRITOR INICIAL, CUALQUIER CONTRIBUIDOR, O CUALQUIER DISTRIBUIDOR DEL "
-"DOCUMENTO O VERSIÓN MODIFICADA DEL DOCUMENTO, O CUALQUIER PROPORCIONADOR DE "
-"CUALQUIERA DE ESAS PARTES, SERÁ RESPONSABLE ANTE NINGUNA PERSONA POR NINGÚN "
-"DAÑO DIRECTO, INDIRECTO, ESPECIAL, INCIDENTAL O DERIVADO DE NINGÚN TIPO, "
-"INCLUYENDO, SIN LIMITACIÓN DAÑOS POR PÉRDIDA DE MERCANCÍAS, PARO TÉCNICO, "
-"FALLO INFORMÁTICO O MAL FUNCIONAMIENTO O CUALQUIER OTRO POSIBLE DAÑO O "
-"PÉRDIDAS DERIVADAS O RELACIONADAS CON EL USO DEL DOCUMENTO O SUS VERSIONES "
+"(INCLUYENDO NEGLIGENCIA), CONTRATO O DE ALGÚN OTRO MODO, EL AUTHOR, EL "
+"ESCRITOR INICIAL, CUALQUIER CONTRIBUIDOR, O CUALQUIER DISTRIBUIDOR DEL "
+"DOCUMENTO O VERSIÓN MODIFICADA DEL DOCUMENTO, O CUALQUIER PROPORCIONADOR DE "
+"CUALQUIERA DE ESAS PARTES, SERÁ RESPONSIBLE ANTE NINGUNA PERSONA POR NINGÚN "
+"DAÑO DIRECTO, INDIRECTO, ESPECIAL, INCIDENTAL O DERIVADO DE NINGÚN TIPO, "
+"INCLUYENDO, SIN LIMITACIÓN DAÑOS POR PÉRDIDA DE MERCANCÍAS, PARO TÉCNICO, "
+"FALLO INFORMÁTICO O MAL FUNCIONAMIENTO O CUALQUIER OTRO POSSIBLE DAÑO O "
+"PÉRDIDAS DERIVADAS O RELACIONADAS CON EL USO DEL DOCUMENTO O SUS VERSIONS "
@@ -187 +187 @@
-"ESTE DOCUMENTO Y LAS VERSIONES MODIFICADAS DEL MISMO SE PROPORCIONAN SEGÚN "
+"ESTE DOCUMENTO Y LAS VERSIONS MODIFICADAS DEL MISMO SE PROPORCIONAN SEGÚN "
@@ -338 +338 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -437 +437 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -500 +500 @@
-msgstr "Línea de comandos"
+msgstr "Línea de commandos"
@@ -555 +555 @@
-"Rhythmbox</application> con sus principales componentes."
+"Rhythmbox</application> con sus principles components."
@@ -597 +597 @@
-"La Tabla 1 describe los componentes de la ventana del "
+"La Tabla 1 describe los components de la ventana del "
@@ -604 +604 @@
-"Componentes de la ventana del <application>Reproductor de música Rhythmbox</"
+"Components de la ventana del <application>Reproductor de música Rhythmbox</"
@@ -742 +742 @@
-msgstr "Todas las listas de reproducción (normales e inteligentes)."
+msgstr "Todas las listas de reproducción (normals e inteligentes)."
@@ -778 +778 @@
-"reproducción. El panel lateral puede contener las siguientes fuentes: <_:"
+"reproducción. El panel lateral puede container las siguientes fuentes: <_:"
@@ -788 +788 @@
-"También puede contener la cola de reproducción si pulsa en el botón de menú "
+"También puede container la cola de reproducción si pulsa en el botón de menú "
@@ -948 +948 @@
-"reproduciendo una. Si se está reproduciendo una pista en ese momento, el "
+"reproduciendo una. Si se está reproduciendo una pista en ese memento, el "
@@ -965 +965 @@
-"La opción <guibutton>Repetir</guibutton> hace que el "
+"La opción <guibutton>Repetir</guibutton> have que el "
@@ -1015 +1015 @@
-"La opción <guibutton>Aleatorio</guibutton> hace que el "
+"La opción <guibutton>Aleatorio</guibutton> have que el "
@@ -1154,3 +1154,3 @@
-"La fonoteca no sólo puede contener archivos musicales que están físicamente "
-"en su equipo (por ejemplo en su carpeta personal), sino que también puede "
-"contener archivos musicales disponibles sobre los servicios de red remotos. "
+"La fonoteca no sólo puede container archivos musicales que están físicamente "
+"en su equipo (por ejemplo en su carpeta personal), sino que también puede "
+"container archivos musicales disponibles sobre los servicios de red remotos. "
@@ -1300 +1300 @@
-"etiquetas específicas <guilabel>Artistas</guilabel>, <guilabel>Álbumes</"
+"etiquetas específicas <guilabel>Artists</guilabel>, <guilabel>Álbumes</"
@@ -1315,3 +1315,3 @@
-"El examinador es otra forma conveniente de buscar pistas. El examinador es "
-"una ventana con dos o tres paneles que permite navegar entre géneros "
-"musicales, artistas y álbumes, y mostrar las pistas que coincidan con los "
+"El examinador es otra forma convenience de buscar pistas. El examinador es "
+"una ventana con dos o tres paneles que permite navegar entre géneros "
+"musicales, artists y álbumes, y mostrar las pistas que coincidan con los "
@@ -1331 +1331 @@
-"las que coincidan con su criterio. El criterio en las columnas se aplica de "
+"las que coincidan con su criterio. El criterio en las columns se aplica de "
@@ -1462 +1462 @@
-"la red; cuando un autor publica un episodio se informa a los suscriptores a "
+"la red; cuando un author publica un episodio se informa a los suscriptores a "
@@ -1617 +1617 @@
-"guilabel>, el <guilabel>Autor</guilabel>, la fecha de la <guilabel>Última "
+"guilabel>, el <guilabel>Author</guilabel>, la fecha de la <guilabel>Última "
@@ -1867 +1867 @@
-"particular, un grupo de artistas específico o incluso pistas de un "
+"particular, un grupo de artists específico o incluso pistas de un "
@@ -2004 +2004 @@
-"Las listas de reproduccion <guimenuitem>Mis mejores puntuados</guimenuitem>, "
+"Las listas de reproduction <guimenuitem>Miss mejores puntuados</guimenuitem>, "
@@ -2101 +2101 @@
-"Elija el botón <guibutton>Lista de reproduccion</guibutton> en la barra de "
+"Elija el botón <guibutton>Lista de reproduction</guibutton> en la barra de "
@@ -2144 +2144 @@
-"application> debería ser capaz de tratar con la mayoría de los reproductores "
+"application> debería set capaz de tratar con la mayoría de los reproductores "
@@ -2275 +2275 @@
-"comandos a la aplicación:"
+"commandos a la aplicación:"
@@ -2384 +2384 @@
-"Elija las <guilabel>Columnas visibles</guilabel> que desea que muestre el "
+"Elija las <guilabel>Columns visible</guilabel> que desea que muestre el "
@@ -2519 +2519 @@
-"consultar estadísticas, tales como las canciones o artistas más escuchados."
+"consultar estadísticas, tales como las canciones o artists más escuchados."
@@ -2524 +2524 @@
-msgstr "recibir recomendaciones sobre artistas que puede que le gusten."
+msgstr "recibir recomendaciones sobre artists que puede que le gusten."
@@ -2840 +2840 @@
-"Usando el nombre de programa «rhythmbox» se soportan los siguientes comandos:"
+"Usando el nombre de programa «rhythmbox» se soportan los siguientes commandos:"
@@ -2845 +2845 @@
-msgstr "Comando"
+msgstr "Commando"
@@ -2988,2 +2988,2 @@
-"las condiciones de la GNU Free Documentation License (GFDL), Versión 1.1 o "
-"cualquier versión posterior publicada por la Free Software Foundation sin "
+"las condiciones de la GNU Free Documentation License (GFDL), Versiońn 1.1 o "
+"cualquier versiońn posterior publicada por la Free Software Foundation sin "
@@ -3004 +3004 @@
-#~ "Ventana que contiene los menús que utiliza para realizar las tareas en "
+#~ "Ventana que contiene los menús que utilize para realizar las tareas en "
@@ -3012 +3012 @@
-#~ "También puede contener la cola de reproducción si se activa "
+#~ "También puede container la cola de reproducción si se activa "
@@ -3339 +3339 @@
-#~ "Para que las pistas importadas desde Sound-Juicer se importen "
+#~ "Para que las pistas importadas desde Sound-Juicer se importance "
@@ -3381 +3381 @@
-#~ "informarle de ello, mostrando una ventana de notificación en el "
+#~ "informal de ello, mostrando una ventana de notificación en el "
@@ -3502,3 +3502,3 @@
-#~ "segundo término, esta licencia proporciona al autor y al editor una "
-#~ "manera de obtener reconocimiento por su trabajo, sin que se le considere "
-#~ "responsable de las modificaciones realizadas por otros."
+#~ "segundo término, esta licencia proporciona al author y al editor una "
+#~ "manera de obtener reconocimiento por su trabajo, sin que se le considere "
+#~ "responsible de las modificaciones realizadas por otros."
@@ -3516 +3516 @@
-#~ "trabajos derivados del documento deben ser libres. Esto complementa a la "
+#~ "trabajos derivados del documento deben set libres. Esto complementa a la "
@@ -3529,7 +3529,7 @@
-#~ "Hemos diseñado esta Licencia para usarla en manuales de software libre, "
-#~ "ya que el software libre necesita documentación libre: un programa libre "
-#~ "debe venir con manuales que ofrezcan la mismas libertades que da el "
-#~ "software. Pero esta licencia no se limita a manuales de software, sino "
-#~ "que puede ser utilizado para cualquier trabajo textual, sin tener en "
-#~ "cuenta su temática o si se publica como libro impreso. Recomendamos esta "
-#~ "licencia principalmente para trabajos cuyo fin sea instructivo o de "
+#~ "Hemos diseñado esta Licencia para usarla en manuals de software libre, "
+#~ "ya que el software libre necesita documentación libre: un programa libre "
+#~ "debe venir con manuals que ofrezcan la mismas libertades que da el "
+#~ "software. Pero esta licencia no se limita a manuals de software, sino "
+#~ "que puede set utilizado para cualquier trabajo textual, sin tener en "
+#~ "cuenta su temática o si se publica como libro impreso. Recomendamos esta "
+#~ "licencia principalmente para trabajos cuyo fin sea instruction o de "
@@ -3555,3 +3555,3 @@
-#~ "una nota colocada por el dueño del copyright diciendo que puede ser "
-#~ "distribuido bajo los términos de esta licencia. El <_:quote-1/>, a "
-#~ "continuación, se refiere a cualquiera de dichos manuales o trabajos. "
+#~ "una nota colocada por el dueño del copyright diciendo que puede set "
+#~ "distribuido bajo los términos de esta licencia. El <_:quote-1/>, a "
+#~ "continuación, se refiere a cualquiera de dichos manuals o trabajos. "
@@ -3588,6 +3588,6 @@
-#~ "> que trata exclusivamente de lo relacionado con los editores o autores "
-#~ "del documento sobre el tema general del documento (o hace referencia a su "
-#~ "contenido principal) pero no contiene nada del contenido principal del "
-#~ "propio documento. (Por ejemplo, si un documento forma parte de un libro "
-#~ "de texto de matemáticas, una sección secundaria podría no explicar nada "
-#~ "de matemáticas.) La relación puede ser un asunto de conexión histórica "
+#~ "> que trata exclusivamente de lo relacionado con los editors o autores "
+#~ "del documento sobre el tema general del documento (o have referencia a su "
+#~ "contenido principal) pero no contiene nada del contenido principal del "
+#~ "propio documento. (Por ejemplo, si un documento forma parte de un libro "
+#~ "de texto de matemáticas, una sección secundaria podría no explicar nada "
+#~ "de matemáticas.) La relación puede set un asunto de conexión histórica "
@@ -3645,3 +3645,3 @@
-#~ "disponible al público en general, cuyo contenido puede ser visto y "
-#~ "editados directamente con editores de texto genéricos o (para imágenes "
-#~ "compuestas por píxeles) con programas genéricos de manipulación de "
+#~ "disponible al público en general, cuyo contenido puede set visto y "
+#~ "editados directamente con editors de texto genéricos o (para imágenes "
+#~ "compuestas por píxeles) con programs genéricos de manipulación de "
@@ -3671 +3671 @@
-#~ "que pueden ser leídos y editados únicamente en procesadores de textos "
+#~ "que pueden set leídos y editados únicamente en procesadores de textos "
@@ -3689 +3689 @@
-#~ "material que esta Licencia requiere en la portada. Para trabajos en "
+#~ "material que esta Licencia require en la portada. Para trabajos en "
@@ -3718 +3718 @@
-#~ "puede aceptar compensación a cambio de las copias. Si distribuye un "
+#~ "puede aceptar compensación a cambio de las copias. Si distribute un "
@@ -3752,4 +3752,4 @@
-#~ "igualmente prominentes y visibles. Además puede añadir otro material en "
-#~ "las cubiertas. Las copias con cambios limitados a las cubiertas, siempre "
-#~ "que conserven el título del <_:link-3/> y satisfagan estas condiciones, "
-#~ "pueden considerarse como copias literales en todos los aspectos."
+#~ "igualmente prominentes y visible. Además puede añadir otro material en "
+#~ "las cubiertas. Las copias con cambios limitados a las cubiertas, siempre "
+#~ "que conserven el título del <_:link-3/> y satisfagan estas condiciones, "
+#~ "pueden considerarse como copias literales en todos los aspects."
@@ -3782,9 +3782,9 @@
-#~ "Si Usted publica o distribuye copias <_:link-1/> del <_:link-2/> cuya "
-#~ "cantidad exceda las 100, debe incluir una copia <_:link-3/>, que pueda "
-#~ "ser leída por una máquina, con cada copia Opaca, o bien mostrar, en cada "
-#~ "copia Opaca, una dirección de red donde cualquier usuario de la misma "
-#~ "tenga acceso por medio de protocolos públicos y estandarizados a una "
-#~ "copia Transparente del Documento completa, sin material adicional. Si "
-#~ "usted hace uso de la última opción, deberá tomar las medidas necesarias, "
-#~ "cuando comience la distribución de las copias Opacas en cantidad, para "
-#~ "asegurar que esta copia Transparente permanecerá accesible en el sitio "
+#~ "Si Usted publica o distribute copias <_:link-1/> del <_:link-2/> cuya "
+#~ "cantidad exceda las 100, debe incluir una copia <_:link-3/>, que pueda "
+#~ "set leída por una máquina, con cada copia Opaca, o bien mostrar, en cada "
+#~ "copia Opaca, una dirección de red donde cualquier usuario de la misma "
+#~ "tenga acceso por medio de protocols públicos y estandarizados a una "
+#~ "copia Transparente del Documento completa, sin material adicional. Si "
+#~ "usted have uso de la última opción, deberá tomar las medidas necesarias, "
+#~ "cuando comience la distribución de las copias Opacas en cantidad, para "
+#~ "asegurar que esta copia Transparente permanecerá accessible en el sitio "
@@ -3836,3 +3836,3 @@
-#~ "distinto al del <_:link-2/> y de sus versiones anteriores (que deberían, "
-#~ "si hay alguna, estar listadas en la sección de Historia del Documento). "
-#~ "Puede usar el mismo título de versiones anteriores al original siempre y "
+#~ "distinto al del <_:link-2/> y de sus versions anteriores (que deberían, "
+#~ "si hay alguna, estar listadas en la sección de Historia del Documento). "
+#~ "Puede usar el mismo título de versions anteriores al original siempre y "
@@ -3852,2 +3852,2 @@
-#~ "con por lo menos cinco de los autores principales del <_:link-3/> (todos "
-#~ "sus autores principales, si hay menos de cinco), a menos que le eximan de "
+#~ "con por lo menos cinco de los autores principles del <_:link-3/> (todos "
+#~ "sus autores principles, si hay menos de cinco), a menos que le eximan de "
@@ -3952 +3952 @@
-#~ "direcciones de red dadas en el Documento para versiones anteriores en las "
+#~ "direcciones de red dadas en el Documento para versions anteriores en las "
@@ -4027 +4027 @@
-#~ "el aviso de licencia de la Versión Modificada. Tales títulos deben ser "
+#~ "el aviso de licencia de la Versión Modificada. Tales títulos deben set "
@@ -4039 +4039 @@
-#~ "una organización como definición oficial de un estándar."
+#~ "una organización como definición official de un estándar."
@@ -4073 +4073 @@
-#~ "Con esta Licencia ni los autores ni los editores del <_:link-1/> dan "
+#~ "Con esta Licencia ni los autores ni los editors del <_:link-1/> dan "
@@ -4092,2 +4092,2 @@
-#~ "arriba para versiones modificadas, siempre que incluya en la combinación "
-#~ "todas las <_:link-3/> de todos los documentos originales, sin "
+#~ "arriba para versions modificadas, siempre que incluya en la combinación "
+#~ "todas las <_:link-3/> de todos los documentos originals, sin "
@@ -4107,6 +4107,6 @@
-#~ "El trabajo combinado necesita contener solamente una copia de esta "
-#~ "Licencia, y múltiples <_:link-1/> idénticas pueden reemplazarse por una "
-#~ "sola copia. Si hay múltiples Secciones Invariantes con el mismo nombre "
-#~ "pero con contenidos diferentes, haga el título de cada una de estas "
-#~ "secciones único añadiéndolo al final de este, entre paréntesis, el nombre "
-#~ "del autor o de quien editó originalmente esa sección, si es conocido, o "
+#~ "El trabajo combinado necesita container solamente una copia de esta "
+#~ "Licencia, y múltiples <_:link-1/> idénticas pueden reemplazarse por una "
+#~ "sola copia. Si hay múltiples Secciones Invariantes con el mismo nombre "
+#~ "pero con contenidos diferentes, haga el título de cada una de estas "
+#~ "secciones único añadiéndolo al final de este, entre paréntesis, el nombre "
+#~ "del author o de quien editó originalmente esa sección, si es conocido, o "
@@ -4128 +4128 @@
-#~ "de los distintos documentos originales, formando una sección titulada <_:"
+#~ "de los distintos documentos originals, formando una sección titulada <_:"
@@ -4146,4 +4146,4 @@
-#~ "individuales de esta Licencia en todos los documentos por una sola copia "
-#~ "que esté incluida en la colección, siempre que siga las reglas de esta "
-#~ "Licencia para cada copia literal de cada uno de los documentos en "
-#~ "cualquiera de los demás aspectos."
+#~ "individuals de esta Licencia en todos los documentos por una sola copia "
+#~ "que esté incluida en la colección, siempre que siga las reglas de esta "
+#~ "Licencia para cada copia literal de cada uno de los documentos en "
+#~ "cualquiera de los demás aspects."
@@ -4152 +4152 @@
-#~| "You may extract a single document from such a collection, and dispbibute "
+#~| "You may extract a single document from such a collection, and distribute "
@@ -4165 +4165 @@
-#~ "todos los demás aspectos relativos a la copia literal de dicho documento."
+#~ "todos los demás aspects relativos a la copia literal de dicho documento."
@@ -4222 +4222 @@
-#~ ">. Reemplazar las <_:link-3/> con traducciones requiere permiso especial "
+#~ ">. Reemplazar las <_:link-3/> con traducciones require permiso especial "
@@ -4250 +4250 @@
-#~ msgstr "10. FUTURAS REVISIONES DE ESTA LICENCIA"
+#~ msgstr "10. FUTURAS REVISIONS DE ESTA LICENCIA"
@@ -4264,4 +4264,4 @@
-#~ "La <_:ulink-1/> puede publicar versiones nuevas y revisadas de la "
-#~ "Licencia de Documentación Libre GNU de vez en cuando. Dichas versiones "
-#~ "nuevas serán similares en espíritu a la presente versión, pero pueden "
-#~ "diferir en detalles para solucionar nuevos problemas o preocupaciones. "
+#~ "La <_:ulink-1/> puede publicar versions nuevas y revisadas de la "
+#~ "Licencia de Documentación Libre GNU de vez en cuando. Dichas versions "
+#~ "nuevas serán similares en espíritu a la presente versión, pero pueden "
+#~ "diferir en detalles para solucionar nuevos problems o preocupaciones. "
@@ -4286,2 +4286,2 @@
-#~ "condiciones de cualquiera de esas versiones especificadas o de cualquiera "
-#~ "de las versiones publicadas (no como borrador) por la Free Software "
+#~ "condiciones de cualquiera de esas versions especificadas o de cualquiera "
+#~ "de las versions publicadas (no como borrador) por la Free Software "
@@ -4324,2 +4324,2 @@
-#~ "bajo los términos de la Licencia de Documentación Libre de GNU, Versión "
-#~ "1.1 o cualquier otra versión posterior publicada por la Free Software "
+#~ "bajo los términos de la Licencia de Documentación Libre de GNU, Versiońn "
+#~ "1.1 o cualquier otra versiońn posterior publicada por la Free Software "
--- ./help/de/de.po	original
+++ ./help/de/de.po	fixed
@@ -93 +93 @@
-"und/oder modifiziert werden. Eine Kopie der GFDL finden Sie unter diesem "
+"und/oder modifiziert werden. Eine Kopie der GFDL finden Sie under diesem "
@@ -105 +105 @@
-"Dieses Handbuch ist Teil einer Sammlung von GNOME-Handbüchern, die unter der "
+"Dieses Handbuch ist Teil einer Sammlung von GNOME-Handbüchern, die under der "
@@ -143,12 +143,12 @@
-"ART, SOWOHL AUSDRÜCKLICH GENANNTE ALS AUCH ANGEDEUTETE. DIES BEZIEHT SICH "
-"AUCH OHNE EINSCHRÄNKUNG AUF GARANTIEN, DASS DIESES DOKUMENT ODER VERÄNDERTE "
-"FASSUNGEN DIESES DOKUMENTS FREI VON HANDELSDEFEKTEN, FÜR EINEN BESTIMMTEN "
-"ZWECK GEEIGNET IST ODER DASS ES KEINE RECHTE DRITTER VERLETZT. DAS VOLLE "
-"RISIKO WAS QUALITÄT, GENAUIGKEIT UND LEISTUNG DES DOKUMENTS ODER VERÄNDERTE "
-"FASSUNGEN DES DOKUMENTS LIEGT BEI IHNEN. SOLLTE EIN DOKUMENT ODER EINE "
-"VERÄNDERTE FASSUNG DAVON FEHLER IRGENDEINER ART BEINHALTEN, TRAGEN SIE "
-"(NICHT DER URSPRUNGSAUTOR, DER AUTOR ODER EIN MITWIRKENDER) DIE KOSTEN FÜR "
-"NOTWENDIGE DIENSTLEISTUNGEN, REPARATUREN ODER FEHLERKORREKTUREN. DIESER "
-"HAFTUNGSAUSSCHLUSS IST EIN ESSENZIELLER TEIL DIESER LIZENZ. DIE VERWENDUNG "
-"EINES DOKUMENTS ODER EINER VERÄNDERTEN VERSION DES DOKUMENTS IST NICHT "
-"GESTATTET AUßER UNTER BEACHTUNG DIESES HAFTUNGSAUSSCHLUSSES UND"
+"ART, SOWOHL AUSDRÜCKLICH GENANNTE ALSO AUCH ANGEDEUTETE. DIES BEZIEHT SICH "
+"AUCH OHNE EINSCHRÄNKUNG AUF GARANTIEN, DASS DIESES DOKUMENT ODER VERÄNDERTE "
+"FASSUNGEN DIESES DOKUMENTS FREI VON HANDELSDEFEKTEN, FÜR EINEN BESTIMMTEN "
+"ZWECK GEEIGNET IST ODER DASS ES KEINE RECHTE DRITTER VERLETZT. DAS VOLLE "
+"RISIKO WAS QUALITÄT, GENAUIGKEIT UND LEISTUNG DES DOKUMENTS ODER VERÄNDERTE "
+"FASSUNGEN DES DOKUMENTS LIEGT BEI IHNEN. SOLLTE EIN DOKUMENT ODER EINE "
+"VERÄNDERTE FASSUNG DAVON FEHLER IRGENDEINER ART BEINHALTEN, TRAGEN SIE "
+"(NICHT DER URSPRUNGSAUTOR, DER AUTHOR ODER EIN MITWIRKENDER) DIE KOSTEN FÜR "
+"NOTWENDIGE DIENSTLEISTUNGEN, REPARATUREN ODER FEHLERKORREKTUREN. DIESER "
+"HAFTUNGSAUSSCHLUSS IST EIN ESSENZIELLER TEIL DIESER LIZENZ. DIE VERWENDUNG "
+"EINES DOKUMENTS ODER EINER VERÄNDERTEN VERSION DES DOKUMENTS IST NICHT "
+"GESTATTET AUßER UNDER BEACHTUNG DIESES HAFTUNGSAUSSCHLUSSES UND"
@@ -170,3 +170,3 @@
-"UNTER KEINEN UMSTÄNDEN UND AUF BASIS KEINER RECHTSGRUNDLAGE, EGAL OB DURCH "
-"UNERLAUBTEN HANDLUNGEN (EINSCHLIEßLICH FAHRLÄSSIGKEIT), VERTRAG ODER "
-"ANDERWEITIG KANN DER AUTOR, URSPRUNGSAUTOR, EIN MITWIRKENDER ODER EIN "
+"UNDER KEINEN UMSTÄNDEN UND AUF BASIS KEINER RECHTSGRUNDLAGE, EGAL OB DURCH "
+"UNERLAUBTEN HANDLUNGEN (EINSCHLIEßLICH FAHRLÄSSIGKEIT), VERTRAG ODER "
+"ANDERWEITIG KANN DER AUTHOR, URSPRUNGSAUTOR, EIN MITWIRKENDER ODER EIN "
@@ -190 +190 @@
-"DAS DOKUMENT UND VERÄNDERTE FASSUNGEN DES DOKUMENTS WERDEN UNTER DEN "
+"DAS DOKUMENT UND VERÄNDERTE FASSUNGEN DES DOKUMENTS WERDEN UNDER DEN "
@@ -340 +340 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -344 +344 @@
-"<date>Januar 2020</date> <_:revdescription-1/>"
+"<date>January 2020</date> <_:revdescription-1/>"
@@ -419 +419 @@
-"Abspielen von Musikdateien zahlreicher Formate aus einer organisierten, mit "
+"Abspielen von Musikdateien zahlreicher Format aus einer organisierten, mit "
@@ -430 +430 @@
-msgstr "Anzeigen aller Titel in einer organisierten Ansicht."
+msgstr "Anzeigen aller Title in einer organisierten Ansicht."
@@ -441 +441 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -535,3 +535,3 @@
-"gestartet wird, wird Ihnen ein Assistent beim Importieren Ihrer "
-"Musiksammlung helfen. Klicken Sie auf der zweiten Seite des Assistenten auf "
-"<guibutton>Durchsuchen</guibutton> und wählen Sie den Ordner aus, in dem "
+"gestartet wird, wird Ihnen ein Assistant beim Importieren Ihrer "
+"Musiksammlung helfen. Klicken Sie auf der zweiten Seite des Assistenten auf "
+"<guibutton>Durchsuchen</guibutton> und wählen Sie den Order aus, in dem "
@@ -646,3 +646,3 @@
-"gegenwärtig abgespielten Titel. Enthält den Schieberegler, der die aktuelle "
-"Wiedergabeposition markiert und außerdem den Wechsel zu einer anderen Stelle "
-"des Titels ermöglicht. Enthält auch den Lautstärkeregler und den Knopf mit "
+"gegenwärtig abgespielten Title. Enthält den Schieberegler, der die aktuelle "
+"Wiedergabeposition markiert und außerdem den Wechsel zu einer anderen Stelle "
+"des Titles ermöglicht. Enthält auch den Lautstärkeregler und den Knopf mit "
@@ -685 +685 @@
-"Ermöglicht es, Titel aus der Bibliothek nach Musikrichtung, Künstler oder "
+"Ermöglicht es, Title aus der Bibliothek nach Musikrichtung, Künstler oder "
@@ -702 +702 @@
-msgstr "Listet die Titel auf, die zur ausgewählten Quelle gehören."
+msgstr "Listet die Title auf, die zur ausgewählten Quelle gehören."
@@ -732 +732 @@
-"der alle importierten Titel erscheinen."
+"der alle importierten Title erscheinen."
@@ -824,2 +824,2 @@
-"Titel. Wenn kein Titel angezeigt wird, zeigt sie keine Informationen an. "
-"Wenn ein Titel gespielt wird, wird der Titelname und darunter der Künstler- "
+"Title. Wenn kein Title angezeigt wird, zeigt sie keine Informationen an. "
+"Wenn ein Title gespielt wird, wird der Titelname und darunter der Künstler- "
@@ -835 +835 @@
-"Eine Fortschrittsleiste zeigt den Fortschritt des momentan gespielten Titels "
+"Eine Fortschrittsleiste zeigt den Fortschritt des momentan gespielten Titles "
@@ -862 +862 @@
-"Die Statusleiste enthält weitere Informationen über die Anzahl der Titel und "
+"Die Statusleiste enthält weitere Informationen über die Anzahl der Title und "
@@ -881,3 +881,3 @@
-"Um einen Titel abzuspielen, wählen Sie <guibutton>Wiedergabe</guibutton> in "
-"der Werkzeugleiste, oder klicken Sie einfach zweimal auf den zu spielenden "
-"Titel."
+"Um einen Title abzuspielen, wählen Sie <guibutton>Wiedergabe</guibutton> in "
+"der Werkzeugleiste, oder klicken Sie einfach zweimal auf den zu spielenden "
+"Title."
@@ -891,2 +891,2 @@
-"Wenn der Titel zu Ende ist, springt der <application>Rhythmbox "
-"Musikwiedergabe</application> zum nächsten Titel, der in der Titelliste in "
+"Wenn der Title zu End ist, springt der <application>Rhythmbox "
+"Musikwiedergabe</application> zum nächsten Title, der in der Titelliste in "
@@ -902 +902 @@
-"In der <xref linkend=\"library\"/> können Sie alle Titel eines Künstlers "
+"In der <xref linkend=\"library\"/> können Sie alle Title eines Künstlers "
@@ -948,3 +948,3 @@
-"Titeln hin und her zu springen. Wenn ein Titel gerade abgespielt wird, "
-"startet der Vorheriger-Knopf den Titel neu. Wenn der <guibutton>Wiedergabe</"
-"guibutton>-Knopf angeklickt wird, wird der momentane Titel abgespielt. <_:"
+"Titeln hin und her zu springen. Wenn ein Title gerade abgespielt wird, "
+"started der Vorheriger-Knopf den Title neu. Wenn der <guibutton>Wiedergabe</"
+"guibutton>-Knopf angeklickt wird, wird der momentane Title abgespielt. <_:"
@@ -966,2 +966,2 @@
-"<application>Rhythmbox Musikwiedergabe</application> nach dem Ende des "
-"letzten Titels der Liste beim ersten Titel von vorn beginnt."
+"<application>Rhythmbox Musikwiedergabe</application> nach dem End des "
+"letzten Titles der Liste beim ersten Title von vorn beginnt."
@@ -1014 +1014 @@
-"<application>Rhythmbox Music Player</application> die Titel in einer "
+"<application>Rhythmbox Music Player</application> die Title in einer "
@@ -1117 +1117 @@
-"auf die Titel, nicht die Dateien selbst gespeichert."
+"auf die Title, nicht die Dateien selbst gespeichert."
@@ -1148 +1148 @@
-"Ihrem Rechner gespeichert sind (in Ihrem persönlichen Ordner zum Beispiel), "
+"Ihrem Rechner gespeichert sind (in Ihrem persönlichen Order zum Beispiel), "
@@ -1171,5 +1171,5 @@
-"Die Titel, die in die Musiksammlung importiert wurden, werden in der "
-"Wiedergabeliste mit Informationen wie Künstlername oder dem Namen des Titels "
-"angezeigt. Diese Informationen sind in den Dateien selbst als sogenannte "
-"Tags eingebettet. Der <application>Rhythmbox Musikwiedergabe</application> "
-"verwendet diese Tags, um die Titel in einer übersichtlichen Anordnung "
+"Die Title, die in die Musiksammlung importiert wurden, werden in der "
+"Wiedergabeliste mit Informationen wie Künstlername oder dem Namen des Titles "
+"angezeigt. Diese Informationen sind in den Dateien selbst also sogenannte "
+"Tags eingebettet. Der <application>Rhythmbox Musikwiedergabe</application> "
+"verwendet diese Tags, um die Title in einer übersichtlichen Anordnung "
@@ -1181 +1181 @@
-msgstr "Titel zur Musiksammlung hinzufügen"
+msgstr "Title zur Musiksammlung hinzufügen"
@@ -1192,5 +1192,5 @@
-"Wenn Sie mehrere Musikdateien aus einem bestimmten Ordner importieren "
-"möchten, wählen Sie <guimenuitem>Importieren</guimenuitem> in der Leiste "
-"neben dem Suchfeld. Anschließend wählen Sie den Ordner im Dateiwähler aus "
-"und klicken auf den <guibutton>Öffnen</guibutton>-Knopf. Alle Musikdateien "
-"in diesem Ordner und dessen Unterordnern werden daraufhin importiert."
+"Wenn Sie mehrere Musikdateien aus einem bestimmten Order importieren "
+"möchten, wählen Sie <guimenuitem>Importieren</guimenuitem> in der Leiste "
+"neben dem Suchfeld. Anschließend wählen Sie den Order im Dateiwähler aus "
+"und klicken auf den <guibutton>Öffnen</guibutton>-Knopf. Alle Musikdateien "
+"in diesem Order und dessen Unterordnern werden daraufhin importiert."
@@ -1204 +1204 @@
-"Sie können Titel auch einfach aus einem Dateimanager (wie zum Beispiel "
+"Sie können Title auch einfach aus einem Dateimanager (wie zum Beispiel "
@@ -1213 +1213 @@
-"Um Titel der Musiksammlung hinzuzufügen, können Sie auf folgende Weisen "
+"Um Title der Musiksammlung hinzuzufügen, können Sie auf folgende Weisen "
@@ -1223,3 +1223,3 @@
-"Wenn Sie die Funktion »Die Musiksammlung auf neue Dateien hin überwachen« "
-"aktiviert haben (siehe <xref linkend=\"prefs-library\"/>), werden alle "
-"Musikdateien, die in dem gewählten Ordner gespeichert werden, zur "
+"Wenn Sie die Function »Die Musiksammlung auf neue Dateien hin überwachen« "
+"aktiviert haben (siehe <xref linkend=\"prefs-library\"/>), werden alle "
+"Musikdateien, die in dem gewählten Order gespeichert werden, zur "
@@ -1232 +1232 @@
-msgstr "Titel aus der Musiksammlung entfernen"
+msgstr "Title aus der Musiksammlung entfernen"
@@ -1242,3 +1242,3 @@
-"Um einen Titel aus der Musiksammlung zu entfernen, ihn aber trotzdem auf dem "
-"Datenträger gespeichert zu lassen, wählen Sie <guimenuitem>Entfernen</"
-"guimenuitem>. Der Titel und dessen Eigenschaften (wie die Bewertung oder wie "
+"Um einen Title aus der Musiksammlung zu entfernen, ihn aber trotzdem auf dem "
+"Datenträger gespeichert zu lassen, wählen Sie <guimenuitem>Entfernen</"
+"guimenuitem>. Der Title und dessen Eigenschaften (wie die Bewertung oder wie "
@@ -1255,5 +1255,5 @@
-"Um einen Titel aus der Musiksammlung und von Ihrer Festplatte zu entfernen, "
-"klicken Sie mit der rechten Maustaste auf den Titel und wählen Sie "
-"<guimenuitem>In den Papierkorb verschieben</guimenuitem>. Der Titel wird "
-"dann auf die gleiche Weise wie zuvor beschrieben aus der Musiksammlung "
-"entfernt, aber zusätzlich in den Papierkorb-Ordner der Dateiverwaltung "
+"Um einen Title aus der Musiksammlung und von Ihrer Festplatte zu entfernen, "
+"klicken Sie mit der rechten Maustaste auf den Title und wählen Sie "
+"<guimenuitem>In den Papierkorb verschieben</guimenuitem>. Der Title wird "
+"dann auf die gleiche Weise wie zuvor beschrieben aus der Musiksammlung "
+"entfernt, aber zusätzlich in den Papierkorb-Order der Dateiverwaltung "
@@ -1265 +1265 @@
-msgstr "Titel mit der Suchfunktion finden"
+msgstr "Title mit der Suchfunktion finden"
@@ -1273 +1273 @@
-"Rhythmbox besitzt eine Suchfunktion, mit der Sie alle Titel anhand von "
+"Rhythmbox besitzt eine Suchfunktion, mit der Sie alle Title anhand von "
@@ -1284,2 +1284,2 @@
-"Eingabe werden nur noch die Titel angezeigt, die zu Ihrer Eingabe passen. Es "
-"werden alle Tags der in der Musiksammlung enthaltenen Titel mit einbezogen."
+"Eingabe werden nur noch die Title angezeigt, die zu Ihrer Eingabe passen. Es "
+"werden alle Tags der in der Musiksammlung enthaltenen Title mit einbezogen."
@@ -1296 +1296 @@
-"<guilabel>Alben</guilabel> oder den <guilabel>Titel</guilabel> von Stücken."
+"<guilabel>Alben</guilabel> oder den <guilabel>Title</guilabel> von Stücken."
@@ -1301 +1301 @@
-msgstr "Titel mit Hilfe des Browsers finden"
+msgstr "Title mit Hilfe des Browsers finden"
@@ -1310,4 +1310,4 @@
-"Der Browser ist eine weitere komfortable Möglichkeit, bestimmte Titel zu "
-"finden. Der Browser ist ein dreigeteiltes Werkzeug, mit dem man durch "
-"Musikgenres, Künstler und Alben navigieren kann und der dann nur die zu den "
-"Suchbegriffen passenden Titel anzeigt."
+"Der Browser ist eine weitere komfortable Möglichkeit, bestimmte Title zu "
+"finden. Der Browser ist ein dreigeteiltes Werkzeug, mit dem man durch "
+"Musikgenres, Künstler und Alben navigieren kann und der dann nur die zu den "
+"Suchbegriffen passenden Title anzeigt."
@@ -1326 +1326 @@
-"Titel in der Titelliste angezeigt. Die Kriterien werden auf die Spalten von "
+"Title in der Titelliste angezeigt. Die Kriterien werden auf die Spalten von "
@@ -1347,7 +1347,7 @@
-"Sie können auch Titel finden, die dasselbe Genre, denselben Künstler oder "
-"Albumnamen wie der ausgewählte Titel haben, ausgehend von den Tags eines der "
-"Titel in der Titelliste. Wählen Sie einen Titel aus der Titelliste, klicken "
-"Sie mit der rechten Maustaste darauf, wählen Sie <guilabel>Dieses Genre "
-"durchsuchen</guilabel>, <guilabel>Nach diesem Künstler suchen</guilabel> "
-"oder <guilabel>Dieses Album durchsuchen</guilabel>. Der Browser wird die "
-"Titel dann nach den angegebenen Kriterien filtern."
+"Sie können auch Title finden, die dasselbe Genre, denselben Künstler oder "
+"Albumnamen wie der ausgewählte Title haben, ausgehend von den Tags eines der "
+"Title in der Titelliste. Wählen Sie einen Title aus der Titelliste, klicken "
+"Sie mit der rechten Maustaste darauf, wählen Sie <guilabel>Dieses Genre "
+"durchsuchen</guilabel>, <guilabel>Nach diesem Künstler suchen</guilabel> "
+"oder <guilabel>Dieses Album durchsuchen</guilabel>. Der Browser wird die "
+"Title dann nach den angegebenen Kriterien filtern."
@@ -1402 +1402 @@
-"Sie anschließend die Adresse des Internetradios ein und klicken auf den "
+"Sie anschließend die Address des Internetradios ein und klicken auf den "
@@ -1428 +1428 @@
-"Titel und sein Genre verändern; die Adresse des Datenstroms und die "
+"Title und sein Genre verändern; die Address des Datenstroms und die "
@@ -1459 +1459 @@
-"verteilen. Wenn ein Autor eine neue Folge veröffentlicht, werden die Podcast-"
+"verteilen. Wenn ein Author eine neue Folge veröffentlicht, werden die Podcast-"
@@ -1534 +1534 @@
-"daraufhin erscheinenden Fenster die Adresse des Podcasts an. Rhythmbox wird "
+"daraufhin erscheinenden Fenster die Address des Podcasts an. Rhythmbox wird "
@@ -1613,2 +1613,2 @@
-"Im Reiter <guilabel>Grundlegend</guilabel> können Sie den <guilabel>Titel</"
-"guilabel>, <guilabel>Autor</guilabel>, die <guilabel>Letzte Aktualisierung</"
+"Im Reiter <guilabel>Grundlegend</guilabel> können Sie den <guilabel>Title</"
+"guilabel>, <guilabel>Author</guilabel>, die <guilabel>Letzte Aktualisierung</"
@@ -1674 +1674 @@
-"Standardmäßig werden Podcasts in den Ordner <filename class=\"directory"
+"Standardmäßig werden Podcasts in den Order <filename class=\"directory"
@@ -1723 +1723 @@
-"löschen</guibutton>, falls die Folge sowohl aus der Liste als auch die Datei "
+"löschen</guibutton>, falls die Folge sowohl aus der Liste also auch die Datei "
@@ -1747 +1747 @@
-"Im Reiter <guilabel>Grundlegend</guilabel> sehen Sie den <guilabel>Titel</"
+"Im Reiter <guilabel>Grundlegend</guilabel> sehen Sie den <guilabel>Title</"
@@ -1792,3 +1792,3 @@
-"abzuspielenden Titel dient. Wenn Sie einen Titel zur Warteschlange "
-"hinzufügen, wechselt <application>Rhythmbox Musikwiedergabe</application> "
-"automatisch zu dieser Quelle, sobald die Titel abgespielt wurden."
+"abzuspielenden Title dient. Wenn Sie einen Title zur Warteschlange "
+"hinzufügen, wechselt <application>Rhythmbox Musikwiedergabe</application> "
+"automatisch zu dieser Quelle, sobald die Title abgespielt wurden."
@@ -1803 +1803 @@
-"Sobald ein Titel abgespielt wird, wird er automatisch aus der Warteschlange "
+"Sobald ein Title abgespielt wird, wird er automatisch aus der Warteschlange "
@@ -1810 +1810 @@
-msgstr "Einen Titel in die Warteschlange aufnehmen"
+msgstr "Einen Title in die Warteschlange aufnehmen"
@@ -1815 +1815 @@
-msgstr "Wählen Sie aus einer beliebigen Quelle den abzuspielenden Titel aus."
+msgstr "Wählen Sie aus einer beliebigen Quelle den abzuspielenden Title aus."
@@ -1821 +1821 @@
-"Führen Sie einen Klick mit der rechten Maustaste aus und wählen Sie "
+"Führen Sie einen Click mit der rechten Maustaste aus und wählen Sie "
@@ -1827 +1827 @@
-msgstr "So fügen Sie einen Titel hinzu: <_:orderedlist-1/>"
+msgstr "So fügen Sie einen Title hinzu: <_:orderedlist-1/>"
@@ -1832 +1832 @@
-msgstr "Einen Titel aus der Warteschlange entfernen"
+msgstr "Einen Title aus der Warteschlange entfernen"
@@ -1837 +1837 @@
-msgstr "Wählen Sie den zu löschenden Titel in der Warteschlange aus."
+msgstr "Wählen Sie den zu löschenden Title in der Warteschlange aus."
@@ -1844 +1844 @@
-"Führen Sie einen Klick mit der rechten Maustaste aus und wählen Sie "
+"Führen Sie einen Click mit der rechten Maustaste aus und wählen Sie "
@@ -1850 +1850 @@
-msgstr "So entfernen Sie einen Titel aus der Warteschlange: <_:orderedlist-1/>"
+msgstr "So entfernen Sie einen Title aus der Warteschlange: <_:orderedlist-1/>"
@@ -1866 +1866 @@
-"Titeln zusammengestellt werden. Sie ermöglichen die Anordnung der Titel "
+"Titeln zusammengestellt werden. Sie ermöglichen die Anordnung der Title "
@@ -1892 +1892 @@
-"Mit Rhythmbox können Sie die Titel einer Wiedergabeliste auf eine Audio-CD "
+"Mit Rhythmbox können Sie die Title einer Wiedergabeliste auf eine Audio-CD "
@@ -1918 +1918 @@
-"Maustaste auf ein Objekt in der Bibliothek. Wählen Sie anschließend "
+"Maustaste auf ein Object in der Bibliothek. Wählen Sie anschließend "
@@ -1937 +1937 @@
-"Um Titel zu einer Wiedergabeliste hinzuzufügen, wählen Sie Titel aus der "
+"Um Title zu einer Wiedergabeliste hinzuzufügen, wählen Sie Title aus der "
@@ -1949 +1949 @@
-"Albumnamen aus dem Browser zuweisen. Auf diese Weise werden alle Titel der "
+"Albumnamen aus dem Browser zuweisen. Auf diese Weise werden alle Title der "
@@ -1962 +1962 @@
-"erstellen. Wählen Sie Titel in der <guilabel>Titelliste</guilabel> aus, oder "
+"erstellen. Wählen Sie Title in der <guilabel>Titelliste</guilabel> aus, oder "
@@ -1980,4 +1980,4 @@
-"Um Titel aus der Wiedergabeliste zu entfernen, wählen Sie zunächst die zu "
-"entfernenden Titel aus. Danach klicken Sie mit der rechten Maustaste in die "
-"Auswahl und wählen Sie <guimenuitem>Löschen</guimenuitem>. Dieser Vorgang "
-"entfernt die Titel nur aus der Wiedergabeliste und nicht aus der Bibliothek."
+"Um Title aus der Wiedergabeliste zu entfernen, wählen Sie zunächst die zu "
+"entfernenden Title aus. Danach klicken Sie mit der rechten Maustaste in die "
+"Auswahl und wählen Sie <guimenuitem>Löschen</guimenuitem>. Dieser Vorgang "
+"entfernt die Title nur aus der Wiedergabeliste und nicht aus der Bibliothek."
@@ -1994 +1994 @@
-"Titel, die auf die Kriterien passen, werden zur Wiedergabeliste hinzugefügt."
+"Title, die auf die Kriterien passen, werden zur Wiedergabeliste hinzugefügt."
@@ -2035 +2035 @@
-"Quellenliste und die enthaltenen Titel können im Hauptfenster von "
+"Quellenliste und die enthaltenen Title können im Hauptfenster von "
@@ -2061 +2061 @@
-"Falls Sie die Titel Ihrer Audio-CDs auf Ihrem Rechner behalten wollen, "
+"Falls Sie die Title Ihrer Audio-CDs auf Ihrem Rechner behalten wollen, "
@@ -2094 +2094 @@
-"linkend=\"playlist\"/> und fügen Sie Titel hinzu."
+"linkend=\"playlist\"/> und fügen Sie Title hinzu."
@@ -2140 +2140 @@
-"eingesteckt wurde und ist in der Lage, die sich darauf befindenden Titel "
+"eingesteckt wurde und ist in der Lage, die sich darauf befindenden Title "
@@ -2165 +2165 @@
-"als tragbaren Musikplayer erkennt, können Sie von Hand eine leere Datei "
+"also tragbaren Musikplayer erkennt, können Sie von Hand eine leere Datei "
@@ -2209 +2209 @@
-"Verteilen Ihrer Titel aktiviert haben, verteilt Rhythmbox gleichzeitig Ihre "
+"Verteilen Ihrer Title aktiviert haben, verteilt Rhythmbox gleichzeitig Ihre "
@@ -2278 +2278 @@
-msgstr "<guibutton>Wiedergabe</guibutton> — Spielt den ausgewählten Titel ab."
+msgstr "<guibutton>Wiedergabe</guibutton> — Spielt den ausgewählten Title ab."
@@ -2286 +2286 @@
-"<guibutton>Zurück</guibutton> — Zum vorherigen Titel der ausgewählten Quelle "
+"<guibutton>Zurück</guibutton> — Zum vorherigen Title der ausgewählten Quelle "
@@ -2293 +2293 @@
-"<guibutton>Weiter</guibutton> — Zum nächsten Titel der ausgewählten Quelle "
+"<guibutton>Weiter</guibutton> — Zum nächsten Title der ausgewählten Quelle "
@@ -2396,3 +2396,3 @@
-"Der <guilabel>Ort der Musiksammlung</guilabel> ist ein Ordner, den "
-"<application>Rhythmbox Musikwiedergabe</application> nach Titeln durchsucht. "
-"Wenn Sie neue Audiodateien in diesen Ordner oder einen Unterordner mit einem "
+"Der <guilabel>Ort der Musiksammlung</guilabel> ist ein Order, den "
+"<application>Rhythmbox Musikwiedergabe</application> nach Titeln durchsucht. "
+"Wenn Sie neue Audiodateien in diesen Order oder einen Unterordner mit einem "
@@ -2409 +2409 @@
-"\">persönlichen Ordner</filename> als Ort der Musiksammlung anzugeben, da "
+"\">persönlichen Order</filename> also Ort der Musiksammlung anzugeben, da "
@@ -2428,3 +2428,3 @@
-"Falls Sie mehr als einen Ordner überwachen lassen wollen, verwenden Sie "
-"bitte den <application>Konfigurationseditor dconf-editor</application> und "
-"fügen den Ordner zur Liste /org/gnome/rhythmbox/rhythmboxdb/locations hinzu"
+"Falls Sie mehr also einen Order überwachen lassen wollen, verwenden Sie "
+"bitte den <application>Konfigurationseditor dconf-editor</application> und "
+"fügen den Order zur Liste /org/gnome/rhythmbox/rhythmboxdb/locations hinzu"
@@ -2445 +2445 @@
-"class=\"directory\">Podcasts/</filename> in Ihrem persönlichen Ordner."
+"class=\"directory\">Podcasts/</filename> in Ihrem persönlichen Order."
@@ -2455 +2455 @@
-"Ordner aus der Auswahlliste oder wählen Sie <guilabel>Andere</guilabel>, um "
+"Order aus der Auswahlliste oder wählen Sie <guilabel>Andere</guilabel>, um "
@@ -2490 +2490 @@
-"Netzwerks Zugriff auf Ihre Titel zu gestatten."
+"Netzwerks Zugriff auf Ihre Title zu gestatten."
@@ -2498 +2498 @@
-"Geben Sie im Feld <guilabel>Name des gemeinsamen Musikordners</guilabel> "
+"Geben Sie im Field <guilabel>Name des gemeinsamen Musikordners</guilabel> "
@@ -2526 +2526 @@
-"Die Last.fm-Profil-Erweiterung sammelt Informationen über die Titel, die Sie "
+"Die Last.fm-Profil-Erweiterung sammelt Informationen über die Title, die Sie "
@@ -2685 +2685 @@
-msgstr "Zum aktuellen Titel springen"
+msgstr "Zum aktuellen Title springen"
@@ -2781 +2781 @@
-msgstr "<keycap>Stopp</keycap>"
+msgstr "<keycap>Stop</keycap>"
@@ -2806 +2806 @@
-msgstr "Vorheriger Titel"
+msgstr "Vorheriger Title"
@@ -2816 +2816 @@
-msgstr "Nächster Titel"
+msgstr "Nächster Title"
@@ -2905 +2905 @@
-msgstr "Zum nächsten Titel springen"
+msgstr "Zum nächsten Title springen"
@@ -2915 +2915 @@
-msgstr "Zum vorherigen Titel springen"
+msgstr "Zum vorherigen Title springen"
@@ -2925 +2925 @@
-msgstr "Um 10 Sekunden im aktuellen Titel vorspringen"
+msgstr "Um 10 Sekunden im aktuellen Title vorspringen"
@@ -2935 +2935 @@
-msgstr "Um 10 Sekunden im aktuellen Titel zurückspringen"
+msgstr "Um 10 Sekunden im aktuellen Title zurückspringen"
@@ -2986 +2986 @@
-"und/oder modifiziert werden. Eine Kopie der GFDL finden Sie unter diesem <_:"
+"und/oder modifiziert werden. Eine Kopie der GFDL finden Sie under diesem <_:"
@@ -3105 +3105 @@
-#~ "kommerziell. Zweitens sichert diese Lizenz dem Autor und Veröffentlicher "
+#~ "kommerziell. Zweitens sichert diese Lizenz dem Author und Veröffentlicher "
@@ -3137 +3137 @@
-#~ "werden, unabhängig vom Thema, oder ob es als gedrucktes Buch "
+#~ "werden, unabhängig vom Thema, oder ob es also gedrucktes Buch "
@@ -3158 +3158 @@
-#~ "Hinweis des Copyright-Halters enthält, welcher besagt, dass sie unter den "
+#~ "Hinweis des Copyright-Halters enthält, welcher besagt, dass sie under den "
@@ -3193 +3193 @@
-#~ "nichts enthält, was direkt unter das Gesamtthema fällt. (Wenn zum "
+#~ "nichts enthält, was direkt under das Gesamtthema fällt. (Wenn zum "
@@ -3211,2 +3211,2 @@
-#~ "<_:quote-1/> sind spezielle <_:link-2/>, deren Titel in dem Hinweis, der "
-#~ "besagt, dass das <_:link-3/> unter dieser Lizenz veröffentlicht ist, "
+#~ "<_:quote-1/> sind spezielle <_:link-2/>, deren Title in dem Hinweis, der "
+#~ "besagt, dass das <_:link-3/> under dieser Lizenz veröffentlicht ist, "
@@ -3223,3 +3223,3 @@
-#~ "Die <_:quote-1/> sind spezielle kurze Textpassagen, die, als "
-#~ "Vorderseitentexte oder Rückseitentexte, in dem Hinweis aufgeführt sind, "
-#~ "der besagt, dass das <_:link-2/> unter dieser Lizenz veröffentlicht ist."
+#~ "Die <_:quote-1/> sind spezielle kurze Textpassagen, die, also "
+#~ "Vorderseitentexte oder Rückseitentexte, in dem Hinweis aufgeführt sind, "
+#~ "der besagt, dass das <_:link-2/> under dieser Lizenz veröffentlicht ist."
@@ -3274,2 +3274,2 @@
-#~ "gestaltet wurde. Undurchsichtige Formate enthalten PostScript, PDF, "
-#~ "proprietäre Formate die nur von proprietären Textverarbeitungen gelesen "
+#~ "gestaltet wurde. Undurchsichtige Format enthalten PostScript, PDF, "
+#~ "proprietäre Format die nur von proprietären Textverarbeitungen gelesen "
@@ -3295 +3295 @@
-#~ "erscheinen. Für Arbeiten, die als solche keine Titelseiten haben, meint "
+#~ "erscheinen. Für Arbeiten, die also solche keine Titelseiten haben, meint "
@@ -3320 +3320 @@
-#~ "und dass sie keine wie auch immer lautenden andere Bedingungen als die "
+#~ "und dass sie keine wie auch immer lautenden andere Bedingungen also die "
@@ -3332 +3332 @@
-#~ "Sie dürfen auch Kopien unter den oben genannten Bedingungen verleihen, "
+#~ "Sie dürfen auch Kopien under den oben genannten Bedingungen verleihen, "
@@ -3351,11 +3351,11 @@
-#~ "Wenn Sie mehr als 100 gedruckte Kopien des <_:link-1/> veröffentlichen, "
-#~ "und die Lizenz des Dokumentes <_:link-2/> verlangt, müssen Sie die Kopien "
-#~ "in Verpackungen einschließen, die sauber und leserlich all diese Cover-"
-#~ "Texte enthalten: Vorderseitentexte auf der Vorderseite, und "
-#~ "Rückseitentexte auf der Rückseite. Beide Seiten müssen auch sauber und "
-#~ "leserlich Sie als den Veröffentlicher dieser Kopien identifizieren. Die "
-#~ "Vorderseite muss den vollen Titel mit allen Wörtern des Titels gleich "
-#~ "auffällig und sichtbar darstellen. Sie dürfen andere Materialien "
-#~ "zusätzlich der Seite hinzufügen. Kopieren mit Veränderungen der Seiten, "
-#~ "solange diese den Titel des <_:link-3/> absichern und diese Bedingungen "
-#~ "erfüllen, können in anderer Hinsicht als wortwörtliche Kopien behandelt "
+#~ "Wenn Sie mehr also 100 gedruckte Kopien des <_:link-1/> veröffentlichen, "
+#~ "und die Lizenz des Dokumentes <_:link-2/> verlangt, müssen Sie die Kopien "
+#~ "in Verpackungen einschließen, die sauber und leserlich all diese Cover-"
+#~ "Texte enthalten: Vorderseitentexte auf der Vorderseite, und "
+#~ "Rückseitentexte auf der Rückseite. Beide Seiten müssen auch sauber und "
+#~ "leserlich Sie also den Veröffentlicher dieser Kopien identifizieren. Die "
+#~ "Vorderseite muss den vollen Title mit allen Wörtern des Titles gleich "
+#~ "auffällig und sichtbar darstellen. Sie dürfen andere Materialien "
+#~ "zusätzlich der Seite hinzufügen. Kopieren mit Veränderungen der Seiten, "
+#~ "solange diese den Title des <_:link-3/> absichern und diese Bedingungen "
+#~ "erfüllen, können in anderer Hinsicht also wortwörtliche Kopien behandelt "
@@ -3389,11 +3389,11 @@
-#~ "Wenn Sie mehr als 100 <_:link-1/> Kopien des <_:link-2/> veröffentlichen "
-#~ "oder verteilen, müssen Sie entweder zusammen mit jeder Undurchsichtigen "
-#~ "Kopie eine maschinenlesbare <_:link-3/> Kopie einfügen, oder in oder mit "
-#~ "jeder Undurchsichtigen Kopie eine öffentlich zugängliche Computer-"
-#~ "Netzwerk-Adresse angeben, die eine komplette Transparente Kopie des "
-#~ "Dokumentes enthält, die frei von hinzugefügtem Material ist und die sich "
-#~ "die allgemeine netzwerknutzende Öffentlichkeit mit Standard-"
-#~ "Netzwerkprotokollen unentgeltlich herunterladen kann. Wenn Sie die letzte "
-#~ "Option verwenden, müssen Sie, wenn Sie beginnen, Undurchsichtige Kopien "
-#~ "in Mengen zu verteilen, vernünftige umsichtige Schritte unternehmen, die "
-#~ "sicherstellen, dass die Transparente Kopie unter der genannten Adresse "
+#~ "Wenn Sie mehr also 100 <_:link-1/> Kopien des <_:link-2/> veröffentlichen "
+#~ "oder verteilen, müssen Sie entweder zusammen mit jeder Undurchsichtigen "
+#~ "Kopie eine maschinenlesbare <_:link-3/> Kopie einfügen, oder in oder mit "
+#~ "jeder Undurchsichtigen Kopie eine öffentlich zugängliche Computer-"
+#~ "Netzwerk-Address angeben, die eine komplette Transparente Kopie des "
+#~ "Dokumentes enthält, die frei von hinzugefügtem Material ist und die sich "
+#~ "die allgemeine netzwerknutzende Öffentlichkeit mit Standard-"
+#~ "Netzwerkprotokollen unentgeltlich herunterladen kann. Wenn Sie die letzte "
+#~ "Option verwenden, müssen Sie, wenn Sie beginnen, Undurchsichtige Kopien "
+#~ "in Mengen zu verteilen, vernünftige umsichtige Schritte unternehmen, die "
+#~ "sicherstellen, dass die Transparente Kopie under der genannten Address "
@@ -3426,6 +3426,6 @@
-#~ "Sie dürfen eine <_:link-1/> eines <_:link-2/> unter den in den "
-#~ "Abschnitten <_:link-3/> und <_:link-4/> oben stehenden Bedingungen "
-#~ "kopieren und verteilen, vorausgesetzt, Sie veröffentlichen die "
-#~ "Modifizierte Version unter genau dieser Lizenz, so dass die modifizierte "
-#~ "Version die Stelle des Dokumentes einnimmt, folglich auch das Lizenzieren "
-#~ "der Verteilung und Modifikation der Modifizierten Version an jeden, der "
+#~ "Sie dürfen eine <_:link-1/> eines <_:link-2/> under den in den "
+#~ "Abschnitten <_:link-3/> und <_:link-4/> oben stehenden Bedingungen "
+#~ "kopieren und verteilen, vorausgesetzt, Sie veröffentlichen die "
+#~ "Modifizierte Version under genau dieser Lizenz, so dass die modifizierte "
+#~ "Version die Stelle des Dokumentes einnimmt, folglich auch das Lizenzieren "
+#~ "der Verteilung und Modification der Modifizierten Version an jeden, der "
@@ -3445,4 +3445,4 @@
-#~ "Auf der <_:link-1/> (und auf den Covern, falls vorhanden) einen Titel "
-#~ "verwenden, der sich von dem des <_:link-2/> unterscheidet, und von denen "
-#~ "vorhergehender Versionen (die, falls vorhanden, in dem History-Abschnitt "
-#~ "des Dokumentes aufgeführt sein sollten). Sie dürfen denselben Titel wie "
+#~ "Auf der <_:link-1/> (und auf den Covern, falls vorhanden) einen Title "
+#~ "verwenden, der sich von dem des <_:link-2/> unterscheidet, und von denen "
+#~ "vorhergehender Versionen (die, falls vorhanden, in dem History-Abschnitt "
+#~ "des Dokumentes aufgeführt sein sollten). Sie dürfen denselben Title wie "
@@ -3461,4 +3461,4 @@
-#~ "Auf der <_:link-1/>, eine oder mehrere Personen als Autoren benennen, die "
-#~ "für das Einbringen von Veränderungen in die <_:link-2/> verantwortlich "
-#~ "sind, zusammen mit mindesten fünf eigentlichen Autoren des <_:link-3/> "
-#~ "(allen eigentlichen Autoren, wenn es weniger als fünf sind)."
+#~ "Auf der <_:link-1/>, eine oder mehrere Personen also Autoren benennen, die "
+#~ "für das Einbringen von Veränderungen in die <_:link-2/> verantwortlich "
+#~ "sind, zusammen mit mindesten fünf eigentlichen Autoren des <_:link-3/> "
+#~ "(allen eigentlichen Autoren, wenn es weniger also fünf sind)."
@@ -3473 +3473 @@
-#~ "Auf der <_:link-1/> den Namen des Veröffentlichers der <_:link-2/> als "
+#~ "Auf der <_:link-1/> den Namen des Veröffentlichers der <_:link-2/> also "
@@ -3501 +3501 @@
-#~ "öffentliche Erlaubnis gibt, die <_:link-1/> unter den Bedingungen dieser "
+#~ "öffentliche Erlaubnis gibt, die <_:link-1/> under den Bedingungen dieser "
@@ -3540,5 +3540,5 @@
-#~ "Den Abschnitt, der mit <_:quote-1/> betitelt ist, und seinen Titel "
-#~ "beibehalten und ihn zu einem Punkt hinzufügen, der mindestens Titel, "
-#~ "Jahr, neue Autoren, und Veröffentlicher der <_:link-2/> wie auf der <_:"
-#~ "link-3/> gegeben, benennt. Wenn es keinen mit <_:quote-4/> betitelten "
-#~ "Abschnitt gibt, erstellen Sie einen, der den Titel, Jahr, Autoren, und "
+#~ "Den Abschnitt, der mit <_:quote-1/> betitelt ist, und seinen Title "
+#~ "beibehalten und ihn zu einem Punkt hinzufügen, der mindestens Title, "
+#~ "Jahr, neue Autoren, und Veröffentlicher der <_:link-2/> wie auf der <_:"
+#~ "link-3/> gegeben, benennt. Wenn es keinen mit <_:quote-4/> betitelten "
+#~ "Abschnitt gibt, erstellen Sie einen, der den Title, Jahr, Autoren, und "
@@ -3561,8 +3561,8 @@
-#~ "Die Netzwerk-Adresse, falls aufgeführt, beibehalten, die im <_:link-1/> "
-#~ "aufgeführt ist, um öffentlichen Zugriff zu einer <_:link-2/> Kopie des "
-#~ "Dokumentes zu ermöglichen, und genauso die Netzwerk-Adressen, die im "
-#~ "Dokument für frühere Versionen, auf denen es basiert, aufgeführt sind. "
-#~ "Diese können in den <_:quote-3/>-Abschnitt gestellt werden. Sie können "
-#~ "eine Netzwerk-Adresse für ein Werk auslassen, das mindestens vier Jahre "
-#~ "vor dem Dokument selbst veröffentlicht wurde, oder wenn der ursprüngliche "
-#~ "Autor, auf den sich die jeweilige Version bezieht, es erlaubt."
+#~ "Die Netzwerk-Address, falls aufgeführt, beibehalten, die im <_:link-1/> "
+#~ "aufgeführt ist, um öffentlichen Zugriff zu einer <_:link-2/> Kopie des "
+#~ "Dokumentes zu ermöglichen, und genauso die Netzwerk-Adressen, die im "
+#~ "Dokument für frühere Versionen, auf denen es basiert, aufgeführt sind. "
+#~ "Diese können in den <_:quote-3/>-Abschnitt gestellt werden. Sie können "
+#~ "eine Netzwerk-Address für ein Werk auslassen, das mindestens vier Jahre "
+#~ "vor dem Dokument selbst veröffentlicht wurde, oder wenn der ursprüngliche "
+#~ "Author, auf den sich die jeweilige Version bezieht, es erlaubt."
@@ -3587 +3587 @@
-#~ "den Titel des Abschnittes beibehalten, und in dem Abschnitt allen Inhalt "
+#~ "den Title des Abschnittes beibehalten, und in dem Abschnitt allen Inhalt "
@@ -3600 +3600 @@
-#~ "und ihren Titeln. Abschnittsnummern oder ähnliches werden nicht als Teil "
+#~ "und ihren Titeln. Abschnittsnummern oder ähnliches werden nicht also Teil "
@@ -3640,3 +3640,3 @@
-#~ "Abschnitte als Unveränderlich bezeichnen. Um dies zu tun, fügen Sie ihre "
-#~ "Titel der Liste der <_:link-3/> in dem Lizenzhinweis der Modifizierten "
-#~ "Version hinzu. Diese Titel müssen sich von allen anderen Abschnittstiteln "
+#~ "Abschnitte also Unveränderlich bezeichnen. Um dies zu tun, fügen Sie ihre "
+#~ "Title der Liste der <_:link-3/> in dem Lizenzhinweis der Modifizierten "
+#~ "Version hinzu. Diese Title müssen sich von allen anderen Abschnittstiteln "
@@ -3654 +3654 @@
-#~ "einer Organisation als für die autoritäre Definition eines Standards "
+#~ "einer Organisation also für die autoritäre Definition eines Standards "
@@ -3674,10 +3674,10 @@
-#~ "Sie dürfen eine Passage aus bis zu fünf Wörtern als <_:link-1/> "
-#~ "hinzufügen, und eine Passage von bis zu 25 Wörtern als <_:link-2/>, ans "
-#~ "Ende der Liste von <_:link-3/> in der <_:link-4/>. Höchstens eine Passage "
-#~ "von Vorderseitentexten und eine von Rückseitentexten darf von (oder durch "
-#~ "Abmachungen von) irgendeinem Wesen hinzugefügt werden. Wenn das <_:link-5/"
-#~ "> für die entsprechende Seite schon einen Covertext hat, der vorher von "
-#~ "Ihnen oder durch Abmachungen von demselben Wesen, in dessen Namen Sie "
-#~ "handeln, hinzugefügt wurde, dürfen Sie keinen anderen hinzufügen; aber "
-#~ "Sie dürfen den alten, wenn es der ursprüngliche Veröffentlicher, der den "
-#~ "alten hinzugefügt hat, explizit erlaubt, ersetzen."
+#~ "Sie dürfen eine Passage aus bis zu fünf Wörtern also <_:link-1/> "
+#~ "hinzufügen, und eine Passage von bis zu 25 Wörtern also <_:link-2/>, ans "
+#~ "End der Liste von <_:link-3/> in der <_:link-4/>. Höchstens eine Passage "
+#~ "von Vorderseitentexten und eine von Rückseitentexten darf von (oder durch "
+#~ "Abmachungen von) irgendeinem Wesen hinzugefügt werden. Wenn das <_:link-5/"
+#~ "> für die entsprechende Seite schon einen Covertext hat, der vorher von "
+#~ "Ihnen oder durch Abmachungen von demselben Wesen, in dessen Namen Sie "
+#~ "handeln, hinzugefügt wurde, dürfen Sie keinen anderen hinzufügen; aber "
+#~ "Sie dürfen den alten, wenn es der ursprüngliche Veröffentlicher, der den "
+#~ "alten hinzugefügt hat, explicit erlaubt, ersetzen."
@@ -3690 +3690 @@
-#~ "Der/die Autor(en) und Veröffentlicher des <_:link-1/> erteilen durch "
+#~ "Der/die Author(en) und Veröffentlicher des <_:link-1/> erteilen durch "
@@ -3708,5 +3708,5 @@
-#~ "Sie dürfen das <_:link-1/> mit anderen Dokumenten, die unter dieser "
-#~ "Lizenz veröffentlicht wurden, unter den Bedingungen in <_:link-2/> für "
-#~ "Modifizierte Versionen kombinieren, vorausgesetzt, Sie beinhalten in der "
-#~ "Kombination alle <_:link-3/> aller ursprünglichen Dokumente unverändert, "
-#~ "und führen Sie alle als Unveränderliche Abschnitte Ihrer kombinierten "
+#~ "Sie dürfen das <_:link-1/> mit anderen Dokumenten, die under dieser "
+#~ "Lizenz veröffentlicht wurden, under den Bedingungen in <_:link-2/> für "
+#~ "Modifizierte Versionen kombinieren, vorausgesetzt, Sie beinhalten in der "
+#~ "Kombination alle <_:link-3/> aller ursprünglichen Dokumente unverändert, "
+#~ "und führen Sie alle also Unveränderliche Abschnitte Ihrer kombinierten "
@@ -3728,3 +3728,3 @@
-#~ "mit demselben Titel, aber unterschiedlichem Inhalt gibt, machen Sie den "
-#~ "Titel jedes Abschnittes durch Hinzufügen (in Klammern) des Namens des "
-#~ "ursprünglichen Autors oder Veröffentlichers dieses Abschnittes, falls "
+#~ "mit demselben Title, aber unterschiedlichem Inhalt gibt, machen Sie den "
+#~ "Title jedes Abschnittes durch Hinzufügen (in Klammern) des Namens des "
+#~ "ursprünglichen Authors oder Veröffentlichers dieses Abschnittes, falls "
@@ -3764 +3764 @@
-#~ "unter dieser Lizenz veröffentlichten Dokumenten besteht, und die "
+#~ "under dieser Lizenz veröffentlichten Dokumenten besteht, und die "
@@ -3777 +3777 @@
-#~ "heraustrennen und es individuell unter dieser Lizenz verteilen, "
+#~ "heraustrennen und es individuell under dieser Lizenz verteilen, "
@@ -3808,9 +3808,9 @@
-#~ "einem Teil eines Speicher- oder Verteilungsmediums, zählt nicht als "
-#~ "Ganzes als <_:link-2/> des Dokumentes, vorausgesetzt, kein Gesamt-"
-#~ "Copyright wurde für die Zusammenstellung festgelegt. Solch eine "
-#~ "Zusammenstellung wird <_:quote-3/> genannt, und diese Lizenz gilt nicht "
-#~ "für die anderen selbstenthaltenen Arbeiten, die mit dem Dokument "
-#~ "zusammengestellt wurden, im Falle, dass sie zusammengestellt wurden, wenn "
-#~ "sie nicht selbst abgeleitete Arbeiten des Dokumentes sind. Wenn die <_:"
-#~ "link-4/>-Bedingung von <_:link-5/> auf diese Kopien des Dokumentes "
-#~ "anwendbar ist, dann können, wenn das Dokument weniger als ein Viertel des "
+#~ "einem Teil eines Speicher- oder Verteilungsmediums, zählt nicht also "
+#~ "Ganzes also <_:link-2/> des Dokumentes, vorausgesetzt, kein Gesamt-"
+#~ "Copyright wurde für die Zusammenstellung festgelegt. Solch eine "
+#~ "Zusammenstellung wird <_:quote-3/> genannt, und diese Lizenz gilt nicht "
+#~ "für die anderen selbstenthaltenen Arbeiten, die mit dem Dokument "
+#~ "zusammengestellt wurden, im Falle, dass sie zusammengestellt wurden, wenn "
+#~ "sie nicht selbst abgeleitete Arbeiten des Dokumentes sind. Wenn die <_:"
+#~ "link-4/>-Bedingung von <_:link-5/> auf diese Kopien des Dokumentes "
+#~ "anwendbar ist, dann können, wenn das Dokument weniger also ein Viertel des "
@@ -3837,2 +3837,2 @@
-#~ "Übersetzung wird als eine Art Modifikation angesehen, also dürfen Sie "
-#~ "Übersetzungen des <_:link-1/> unter den Bedingungen von <_:link-2/> "
+#~ "Übersetzung wird also eine Art Modification angesehen, also dürfen Sie "
+#~ "Übersetzungen des <_:link-1/> under den Bedingungen von <_:link-2/> "
@@ -3865,2 +3865,2 @@
-#~ "Rechte unter dieser Lizenz. Wie auch immer, Parteien, die Kopien oder "
-#~ "Rechte von Ihnen unter dieser Lizenz bekommen haben, wird nicht die "
+#~ "Rechte under dieser Lizenz. Wie auch immer, Parteien, die Kopien oder "
+#~ "Rechte von Ihnen under dieser Lizenz bekommen haben, wird nicht die "
@@ -3887 +3887 @@
-#~ "im Detail unterscheiden, um neue Probleme oder Anliegen anzusprechen. "
+#~ "im Detail unterscheiden, um neue Problem oder Anliegen anzusprechen. "
@@ -3908,3 +3908,3 @@
-#~ "als Entwurf) veröffentlicht wurde, zu folgen. Wenn das Dokument keine "
-#~ "Versionsnummer angibt, können Sie irgendeine, jemals von der Free "
-#~ "Software Foundation (nicht als Entwurf) veröffentlichte Version wählen."
+#~ "also Entwurf) veröffentlicht wurde, zu folgen. Wenn das Dokument keine "
+#~ "Versionsnummer angibt, können Sie irgendeine, jemals von der Free "
+#~ "Software Foundation (nicht also Entwurf) veröffentlichte Version wählen."
@@ -3943,3 +3943,3 @@
-#~ "oder zu verändern unter den Bedingungen der GNU Free Documentation "
-#~ "License, Version 1.1 oder einer späteren, von der Free Software "
-#~ "Foundation veröffentlichten Version; mit den <_:link-1/>, DEREN TITEL "
+#~ "oder zu verändern under den Bedingungen der GNU Free Documentation "
+#~ "License, Version 1.1 oder einer späteren, von der Free Software "
+#~ "Foundation veröffentlichten Version; mit den <_:link-1/>, DEREN TITLE "
@@ -3979,3 +3979,3 @@
-#~ "empfehlen wir, diese Beispiele parallel unter einer freien Software-"
-#~ "Lizenz, wie der <_:ulink-1/>, zu veröffentlichen, um ihren Gebrauch in "
-#~ "freier Software zu erlauben."
+#~ "empfehlen wir, diese Beispiele parallel under einer freien Software-"
+#~ "Lizenz, wie der <_:ulink-1/>, zu veröffentlichen, um ihren Gebrauch in "
+#~ "freier Software zu erlauben."
--- ./help/id/id.po	original
+++ ./help/id/id.po	fixed
@@ -212 +212 @@
-# typo: Jaunary --> January
+# typo: January --> January
@@ -216 +216 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -316 +316 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -483 +483 @@
-"Tabel 1 menjelaskan komponen jendela <application>Rhythmbox Music Player</"
+"Table 1 menjelaskan komponen jendela <application>Rhythmbox Music Player</"
@@ -646 +646 @@
-msgstr "Pemutar portabel seperti iPod dicolokkan ke komputer Anda."
+msgstr "Pemutar portable seperti iPod dicolokkan ke komputer Anda."
@@ -652 +652 @@
-msgstr "Saham DAAP Music ditemukan di jaringan lokal."
+msgstr "Saham DAAP Music ditemukan di jaringan local."
@@ -1291 +1291 @@
-"dialirkan melalui jaringan, lokal atau Internet."
+"dialirkan melalui jaringan, local atau Internet."
@@ -2093 +2093 @@
-msgstr "Sumber Pemutar Audio Portabel"
+msgstr "Sumber Pemutar Audio Portable"
@@ -2106,3 +2106,3 @@
-"portabel dicolokkan ke komputer Anda, dan dapat membaca trek yang tersimpan "
-"di dalamnya. <application>Rhythmbox Music Player</application> harus dapat "
-"menangani sebagian besar pemutar audio portabel termasuk Apple iPod, pemutar "
+"portable dicolokkan ke komputer Anda, dan dapat membaca trek yang tersimpan "
+"di dalamnya. <application>Rhythmbox Music Player</application> harus dapat "
+"menangani sebagian besar pemutar audio portable termasuk Apple iPod, pemutar "
@@ -2119,2 +2119,2 @@
-"Saat Anda mencolokkan pemutar audio portabel, ikon untuk Pemutar Audio "
-"Portabel ditambahkan ke panel samping. Sumber ini bekerja dengan cara yang "
+"Saat Anda mencolokkan pemutar audio portable, ikon untuk Pemutar Audio "
+"Portable ditambahkan ke panel samping. Sumber ini bekerja dengan cara yang "
@@ -2133,3 +2133,3 @@
-"perangkat Anda sebagai pemutar audio portabel, Anda dapat membuat file "
-"kosong bernama <filename>.is_audio_player</filename> di hierarki tingkat "
-"atas sistem file pemutar Anda."
+"perangkat Anda sebagai pemutar audio portable, Anda dapat membuat file "
+"kosong bernama <filename>.is_audio_player</filename> di hierarki tingkat "
+"atas system file pemutar Anda."
@@ -2162 +2162 @@
-"Karena DAAP adalah protokol standar untuk berbagi musik, Anda dapat "
+"Karena DAAP adalah protokol standard untuk berbagi musik, Anda dapat "
@@ -2179 +2179 @@
-"diterbitkan di jaringan lokal Anda (rumah atau kantor Anda, bukan seluruh "
+"diterbitkan di jaringan local Anda (rumah atau kantor Anda, bukan seluruh "
@@ -2343 +2343 @@
-msgstr "Pemutar Portabel"
+msgstr "Pemutar Portable"
@@ -2476 +2476 @@
-"Jaringan Area Lokal Anda, ke <application>Pemutar Musik Rhythmbox</"
+"Jaringan Area Local Anda, ke <application>Pemutar Musik Rhythmbox</"
@@ -3089 +3089 @@
-"disadarkan atas merek dagang tersebut, maka nama-nama adalah dalam huruf "
+"disadarkan atas merek dagang tersebut, make nama-nama adalah dalam huruf "
--- ./help/oc/oc.po	original
+++ ./help/oc/oc.po	fixed
@@ -165 +165 @@
-msgstr "Projècte de documentacion de GNOME"
+msgstr "Projècte de documentation de GNOME"
@@ -339 +339 @@
-msgstr "Introduccion"
+msgstr "Introduction"
@@ -368 +368 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -483 +483 @@
-msgstr "Descripcion"
+msgstr "Description"
@@ -573 +573 @@
-msgid "Displays informations about the source selected in Source List."
+msgid "Displays information about the source selected in Source List."
@@ -1060 +1060 @@
-"Rhythmbox enables you to suscribe to podcast feeds, so when a new episode is "
+"Rhythmbox enables you to subscribe to podcast feeds, so when a new episode is "
@@ -1417,2 +1417,2 @@
-"Smart Playlists are playlists built from criterias, so their content is "
-"build dynamically; all the tracks matching criterias will be added in the "
+"Smart Playlists are playlists built from criteria, so their content is "
+"build dynamically; all the tracks matching criteria will be added in the "
@@ -1433 +1433 @@
-msgid "Edit the playlist criterias through the query editor."
+msgid "Edit the playlist criteria through the query editor."
@@ -1438 +1438 @@
-"Once your criterias chosen, click <guibutton>New</guibutton> to create the "
+"Once your criteria chosen, click <guibutton>New</guibutton> to create the "
@@ -1456 +1456 @@
-"criterias. Once done, choose <guibutton>Close</guibutton>."
+"criteria. Once done, choose <guibutton>Close</guibutton>."
@@ -1492 +1492 @@
-"display the tracks matched by your criterias."
+"display the tracks matched by your criteria."
@@ -1655 +1655 @@
-msgstr "Zòna de notificacion"
+msgstr "Zòna de notification"
@@ -1687 +1687 @@
-msgstr "Fenèstra de notificacion"
+msgstr "Fenèstra de notification"
--- ./help/ru/ru.po	original
+++ ./help/ru/ru.po	fixed
@@ -9 +9 @@
-"Last-Translator: Ser82-png <sw@atrus.ru>\n"
+"Last-Translator: Set82-png <sw@atrus.ru>\n"
@@ -23 +23 @@
-"Ser82-png <sw@atrus.ru>, 2022"
+"Set82-png <sw@atrus.ru>, 2022"
@@ -322 +322 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -422 +422 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -3325 +3325 @@
-#~ msgid "Edit the playlist criterias through the query editor."
+#~ msgid "Edit the playlist criteria through the query editor."
@@ -3329 +3329 @@
-#~ "Once your criterias chosen, click <guibutton>New</guibutton> to create "
+#~ "Once your criteria chosen, click <guibutton>New</guibutton> to create "
@@ -3346 +3346 @@
-#~ "criterias. Once done, choose <guibutton>Close</guibutton>."
+#~ "criteria. Once done, choose <guibutton>Close</guibutton>."
@@ -3394 +3394 @@
-#~ "display the tracks matched by your criterias."
+#~ "display the tracks matched by your criteria."
--- ./help/ro/ro.po	original
+++ ./help/ro/ro.po	fixed
@@ -66 +66 @@
-msgstr "Proiectul de documentare GNOME"
+msgstr "Proiectul de documentaries GNOME"
@@ -83 +83 @@
-"\">legătură</ulink> sau în fișierul COPYING-DOCS distribuit împreună cu "
+"\">legătură</ulink> sau în fișierul COPYING-DOCS distribute împreună cu "
@@ -94,2 +94,2 @@
-"Acest manual este parte dintr-o colecție de manuale GNOME distribuit sub "
-"GFDL. Dacă doriți să distribuiți acest manual separat de colecție, puteți "
+"Acest manual este parte dintr-o colecție de manuale GNOME distribute sub "
+"GFDL. Dacă doriți să distribuiți acest manual separate de colecție, puteți "
@@ -110 +110 @@
-"apar în orice documentație GNOME, și membrii proiectului de documentare "
+"apar în orice documentație GNOME, și membrii proiectului de documentaries "
@@ -136,2 +136,2 @@
-"ORICE ALT CONTRIBUITOR) ASUMĂ-ȚI COSTUL ORICĂRUI SERVICIU NECESAR, REPARAȚII "
-"SAU CORECTĂRI. ACEASTĂ RESPONSABILITATE DE GARANȚIE CONSTITUIE O PARTE "
+"ORICE ALT CONTRIBUTOR) ASUMĂ-ȚI COSTUL ORICĂRUI SERVICIU NECESAR, REPARAȚII "
+"SAU CORECTĂRI. ACEASTĂ RESPONSABILITATE DE GARANȚIE CONSTITUTE O PARTE "
@@ -158,9 +158,9 @@
-"SCRIITORUL INIȚIAL, ORICE CONTRIBUITOR SAU ORICE DISTRIBUITOR AL "
-"DOCUMENTULUI SAU VERSIUNEA MODIFICATĂ A ACESTUIA SAU ORICE FURNIZOR AL UNEIA "
-"DINTRE PĂRȚI, RĂSPUNZĂTOR PENTRU ORICE PERSOANĂ PENTRU ORICE DIRECTE, "
-"INDIRECTE, SPECIALE, INCIDENTALE SAU PAGUBE SUBSECVENȚE DE ORICE CARACTER "
-"INCLUSIV, FĂRĂ LIMITARE, DESPĂGUBIRI PENTRU PIERDERILE DE BUNĂVOINȚĂ, "
-"ÎNTRERUPERE A ACTIVITĂȚII, DEFECȚIUNE DE CALCULATOR, SAU ORICE ALTCEVA ȘI "
-"TOATE CELELALTE DAUNE SAU PIERDERI REZULTATE DIN SAU LEGATE DE UTILIZAREA "
-"DOCUMENTULUI ȘI VERSIUNILOR MODIFICATE ALE ACESTUIA, CHIAR DACĂ ACESTE PĂRȚI "
-"AU FOST INFORMATE DE POSIBILITATEA UNOR ASTFEL DE DAUNE."
+"SCRIITORUL INIȚIAL, ORICE CONTRIBUTOR SAU ORICE DISTRIBUTOR AL "
+"DOCUMENTULUI SAU VERSIUNEA MODIFICATĂ A ACESTUIA SAU ORICE FURNIZOR AL UNEIA "
+"DINTRE PĂRȚI, RĂSPUNZĂTOR PENTRU ORICE PERSOANĂ PENTRU ORICE DIRECTE, "
+"INDIRECTE, SPECIALE, INCIDENTALE SAU PAGUBE SUBSECVENȚE DE ORICE CHARACTER "
+"INCLUSIV, FĂRĂ LIMITARE, DESPĂGUBIRI PENTRU PIERDERILE DE BUNĂVOINȚĂ, "
+"ÎNTRERUPERE A ACTIVITĂȚII, DEFECȚIUNE DE CALCULATOR, SAU ORICE ALTCEVA ȘI "
+"TOATE CELELALTE DAUNE SAU PIERDERI REZULTATE DIN SAU LEGATE DE UTILIZAREA "
+"DOCUMENTULUI ȘI VERSIUNILOR MODIFICATE ALE ACESTUIA, CHIAR DACĂ ACESTE PĂRȚI "
+"AU FOST INFORMATIVE DE POSIBILITATEA UNOR ASTFEL DE DAUNE."
@@ -311 +311 @@
-"Acest manual descrie versiunea 0.11.5 a Playerului pentru muzică Rhythmbox."
+"Acest manual describe versiunea 0.11.5 a Playerului pentru muzică Rhythmbox."
@@ -363 +363 @@
-"și o bibliotecă pentru fișiere care suportă formate diverse de muzică."
+"și o bibliotecă pentru fișiere care suportă format diverse de muzică."
@@ -371 +371 @@
-"Rhythmbox</application> includ:"
+"Rhythmbox</application> include:"
@@ -377 +377 @@
-"Redarea diverselor formate de fișiere audio din biblioteca dumneavoastră "
+"Redarea diverselor format de fișiere audio din biblioteca dumneavoastră "
@@ -399 +399 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -556 +556 @@
-"Tabelul 1 descrie elementele din fereastra <application>Player pentru muzică "
+"Tabelul 1 describe elementele din fereastra <application>Player pentru muzică "
@@ -617 +617 @@
-"Oferă acces la funcțiile playerului și detalii despre piesa ce se redă."
+"Oferă access la funcțiile playerului și detalii despre piesa ce se redă."
@@ -702 +702 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -732 +732 @@
-msgstr "Toate listele de redare (normale și inteligente)."
+msgstr "Toate listele de redare (normal și inteligente)."
@@ -789 +789 @@
-"Zona barei de unelte oferă acces la detaliile despre piesa în curs de "
+"Zona barei de unelte oferă access la detaliile despre piesa în curs de "
@@ -928 +928 @@
-"muzică Rhythmbox</application> în modul ecran mic</phrase> </textobject>"
+"muzică Rhythmbox</application> în module ecran mic</phrase> </textobject>"
@@ -1166 +1166 @@
-"pentru a reflecta volumul relativ. <_:screenshot-1/>"
+"pentru a reflecta volumul relative. <_:screenshot-1/>"
@@ -1194 +1194 @@
-"Rhythmbox</application> (Biblioteca stochează calea de acces a fișierelor de "
+"Rhythmbox</application> (Biblioteca stochează calea de access a fișierelor de "
@@ -1228 +1228 @@
-"serviciilor de rețea. Unele exemple de servicii de rețea suportate sunt: <_:"
+"serviciilor de rețea. Unele example de servicii de rețea suportate sunt: <_:"
@@ -1373 +1373 @@
-"piesele care se potrivesc cu textul introdus vor fi afișate. Funcția de "
+"piesele care se potrivesc cu textul introduces vor fi afișate. Funcția de "
@@ -1383 +1383 @@
-"Pentru a efectua o căutare mai precisă, puteți alege să caute numai în "
+"Pentru a efectua o căutare mai precisă, puteți allege să caute numai în "
@@ -1426 +1426 @@
-"Puteți alege mai multe criterii de căutare din aceeași categorie folosind "
+"Puteți allege mai multe criterii de căutare din aceeași categorie folosind "
@@ -1745 +1745 @@
-"<guilabel>Drepturilor de autor</guilabel>."
+"<guilabel>Drepturilor de author</guilabel>."
@@ -2068 +2068 @@
-"din navigator, și toate piesele ce aparțin categoriei alese vor fi adăugate "
+"din navigator, și toate piesele ce aparțin categorize alese vor fi adăugate "
@@ -2153 +2153 @@
-"sunt adăugate listei în mod dinamic; toate piesele potrivite criteriilor "
+"sunt adăugate listei în mod dynamic; toate piesele potrivite criteriilor "
@@ -2296 +2296 @@
-"Când un CD Audio este introdus, va apărea în panoul lateral, și piesele de "
+"Când un CD Audio este introduces, va apărea în panoul lateral, și piesele de "
@@ -2465 +2465 @@
-"în Rhythmbox. DAAP este prescurtarea de la Digital Audio Acces Protocol."
+"în Rhythmbox. DAAP este prescurtarea de la Digital Audio Access Protocol."
@@ -2476 +2476 @@
-"cu alți utilizatori care folosesc programe compatibile cu DAAP, cum ar fi "
+"cu alți utilizatori care folosesc programe compatible cu DAAP, cum ar fi "
@@ -2733 +2733 @@
-"Această secțiune descrie cum să personalizați <application>Playerul pentru "
+"Această secțiune describe cum să personalizați <application>Playerul pentru "
@@ -2767,2 +2767,2 @@
-"Alegeți modul în care <guilabel>Vizualizarea navigatorului</guilabel> va fi "
-"afișată. Puteți alege utilizarea a două sau trei panouri și ce panouri ar "
+"Alegeți module în care <guilabel>Vizualizarea navigatorului</guilabel> va fi "
+"afișată. Puteți allege utilizarea a două sau trei panouri și ce panouri ar "
@@ -2971 +2971 @@
-"<guilabel>Parolă</guilabel> din fereastra de configurare a modulului profil "
+"<guilabel>Parolă</guilabel> din fereastra de configure a modulului profil "
@@ -2982 +2982 @@
-"Fereastra de configurare pentru modulul profil Last.fm afișează de asemenea "
+"Fereastra de configure pentru modulul profil Last.fm afișează de asemenea "
@@ -3196 +3196 @@
-msgstr "Comută / Ieși din modul pe tot ecranul"
+msgstr "Comută / Ieși din module pe tot ecranul"
@@ -3210 +3210 @@
-"tastaturile multimedia, dacă sunt configurate în mediul desktop."
+"tastaturile multimedia, dacă sunt configure în mediul desktop."
@@ -3264 +3264 @@
-"<application>Rhythmbox Music Player</application> include un modul pentru "
+"<application>Rhythmbox Music Player</application> include un module pentru "
@@ -3453 +3453 @@
-"<_:address-1/> Oricui îi este permis să copieze și să distribuie cópii "
+"<_:address-1/> Oricui îi este permis să copieze și să distribute cópii "
@@ -3486 +3486 @@
-"această Licență rezervă pentru autor și editor dreptul de a fi creditați "
+"această Licență rezervă pentru author și editor dreptul de a fi creditați "
@@ -3493 +3493 @@
-msgstr "stâng de autor („copyleft”)"
+msgstr "stâng de author („copyleft”)"
@@ -3504 +3504 @@
-"derivate trebuie să fie și ele libere în sensul de mai sus. Această Licență "
+"derivative trebuie să fie și ele libere în sensul de mai sus. Această Licență "
@@ -3525 +3525 @@
-"de modul de publicare. Această Licență este recomandată în principal pentru "
+"de module de publicare. Această Licență este recomandată în principal pentru "
@@ -3561 +3561 @@
-"inclusă de către deținătorul dreptului de autor ce permite distribuția sub "
+"inclusă de către deținătorul dreptului de author ce permite distribuția sub "
@@ -3606,3 +3606,3 @@
-"care are ca scop exclusiv descrierea relației editorilor sau a autorilor "
-"Documentului cu subiectul Documentului (sau cu subiecte legate de acesta) și "
-"care nu conține subiecte incluse în mod direct în subiectul Documentului. ("
+"care are ca scop exclusive descrierea relației editorilor sau a autorilor "
+"Documentului cu subiectul Documentului (sau cu subiecte legate de acesta) și "
+"care nu conține subiecte includes în mod direct în subiectul Documentului. ("
@@ -3688,6 +3688,6 @@
-"desene) un editor larg răspândit de grafică vectorială, și care poate fi "
-"folosit de către programe de formatare de text sau de către programe de "
-"conversie în alte formate care pot fi folosite ca intrare de către programe "
-"de formatare a textului. O copie făcută într-un format de fișier Transparent "
-"dar care prin prezența sau absența anumitor elemente specifice formatului "
-"descurajează sau împiedică modificările ulterioare nu este o copie "
+"desene) un editor large răspândit de grafică vectorială, și care poate fi "
+"folosit de către programe de formatare de text sau de către programe de "
+"converse în alte format care pot fi folosite ca intrare de către programe "
+"de formatare a textului. O copie făcută într-un format de fișier Transparent "
+"dar care prin prezența sau absența anumitor elemente specifice formatului "
+"descurajează sau împiedică modificările ulterior nu este o copie "
@@ -3710,7 +3710,7 @@
-"Exemple de formate compatibile cu copiile Transparente includ text ASCII "
-"fără marcare, format de intrare Texinfo, format de intrare LaTeX, SGML sau "
-"XML folosind un DTD public, HTML simplu și standard conceput pentru "
-"modificarea de către oameni. Formatele Opace includ formate de text ce pot "
-"fi citite și editate doar de procesoare de text proprietare, SGML și XML "
-"pentru care DTD-ul și/sau uneltele de procesare nu sunt disponibile public, "
-"HTML generat automat exclusiv în scopul printării/afișării."
+"Example de format compatible cu copiile Transparente include text ASCII "
+"fără marcare, format de intrare Texinfo, format de intrare LaTeX, SGML sau "
+"XML folosind un DTD public, HTML simplu și standard conceput pentru "
+"modificarea de către oameni. Formatele Opace include format de text ce pot "
+"fi citite și editate doar de procesoare de text proprietare, SGML și XML "
+"pentru care DTD-ul și/sau uneltele de procesare nu sunt disponibile public, "
+"HTML generat automat exclusive în scopul printării/afișării."
@@ -4329 +4329 @@
-"\">legătură</ulink> sau în fișierul COPYING-DOCS distribuit împreună cu "
+"\">legătură</ulink> sau în fișierul COPYING-DOCS distribute împreună cu "
@@ -4396 +4396 @@
-"\">legătură</ulink> sau în fișierul COPYING-DOCS distribuit împreună cu "
+"\">legătură</ulink> sau în fișierul COPYING-DOCS distribute împreună cu "
@@ -4520 +4520 @@
-#~ msgstr "Arată <placeholder-1/> în modul afișaj mic"
+#~ msgstr "Arată <placeholder-1/> în module afișaj mic"
@@ -4613 +4613 @@
-#~ msgstr "Comută / Ieși din modul ecran mic"
+#~ msgstr "Comută / Ieși din module ecran mic"
--- ./help/ca/ca.po	original
+++ ./help/ca/ca.po	fixed
@@ -69 +69 @@
-msgstr "Projecte de documentació del GNOME"
+msgstr "Projectile de documentació del GNOME"
@@ -112,2 +112,2 @@
-"productes i serveis es consideren marques comercials. Quan aquests noms "
-"apareguin en qualsevol documentació del GNOME, si els membres del Projecte "
+"productes i serveis es considered marques comercials. Quan aquests noms "
+"apareguin en qualsevol documentació del GNOME, si els membres del Projectile "
@@ -135,7 +135,7 @@
-"COMERCIALITZABLE, SIGUI ADEQUAT PER A UN ÚS CONCRET O NO INFRINGEIXI CAP "
-"LLEI. TOT EL RISC PEL QUE FA A LA QUALITAT, EXACTITUD I RENDIMENT DEL "
-"DOCUMENT O LA VERSIÓ MODIFICADA DEL DOCUMENT ÉS VOSTRE. EN CAS QUE EL "
-"DOCUMENT RESULTÉS DEFECTUÓS EN QUALSEVOL ASPECTE, VÓS (NO PAS L'ESCRIPTOR "
-"INICIAL, L'AUTOR O CAP ALTRE COL·LABORADOR) ASSUMIU TOT EL COST DE "
-"MANTENIMENT, REPARACIÓ O CORRECCIÓ. AQUESTA RENÚNCIA DE GARANTIA CONSTITUEIX "
-"UNA PART ESSENCIAL D'AQUESTA LLICÈNCIA. NO S'AUTORITZA L'ÚS DE CAP DOCUMENT "
+"COMERCIALITZABLE, SIGUI ADEQUAT PER A UN ÚS CONCERT O NO INFRINGEIXI CAP "
+"LLEI. TOT EL RISC PEL QUE FA A LA QUALITAT, EXACTITUD I RENDIMENT DEL "
+"DOCUMENT O LA VERSIÓ MODIFICADA DEL DOCUMENT ÉS VOSTRE. EN CAS QUE EL "
+"DOCUMENT RESULTÉS DEFECTUÓS EN QUALSEVOL ASPECTE, VÓS (NO PAS L'ESCRIPTOR "
+"INICIAL, L'AUTHOR O CAP ALTRE COL·LABORADOR) ASSUMIU TOT EL COST DE "
+"MANTENIMENT, REPARACIÓ O CORRECCIÓ. AQUESTA RENÚNCIA DE GARANTIA CONSTITUEIX "
+"UNA PART ESSENTIAL D'AQUESTA LLICÈNCIA. NO S'AUTORITZA L'ÚS DE CAP DOCUMENT "
@@ -159 +159 @@
-"(INCLOENT-HI LA NEGLIGÈNCIA), CONTRACTE O ALTRE CAS, L'AUTOR, L'ESCRIPTOR "
+"(INCLOENT-HI LA NEGLIGÈNCIA), CONTRACTE O ALTRE CAS, L'AUTHOR, L'ESCRIPTOR "
@@ -188 +188 @@
-"<orgname>Projecte de documentació del GNOME</orgname> "
+"<orgname>Projectile de documentació del GNOME</orgname> "
@@ -199 +199 @@
-"<orgname>Projecte de documentació del GNOME</orgname> "
+"<orgname>Projectile de documentació del GNOME</orgname> "
@@ -212 +212 @@
-"<affiliation> <orgname>Projecte de documentació del GNOME</orgname> "
+"<affiliation> <orgname>Projectile de documentació del GNOME</orgname> "
@@ -224 +224 @@
-"<orgname>Projecte de documentació del GNOME</orgname> <address><email>Victor."
+"<orgname>Projectile de documentació del GNOME</orgname> <address><email>Victor."
@@ -235 +235 @@
-"<orgname>Projecte de documentació d'Ubuntu</orgname> "
+"<orgname>Projectile de documentació d'Ubuntu</orgname> "
@@ -246 +246 @@
-"<orgname>Documentació del projecte GNOME </orgname> "
+"<orgname>Documentació del projectile GNOME </orgname> "
@@ -327 +327 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -426 +426 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -511 +511 @@
-msgstr "Executant l'Assistent"
+msgstr "Executant l'Assistant"
@@ -522,2 +522,2 @@
-"application>, un assistent us ajudarà a importar la vostra música. Al segon "
-"tauler de l'assistent, premeu el botó <guibutton>Navega</guibutton> i "
+"application>, un assistant us ajudarà a importar la vostra música. Al segon "
+"tauler de l'assistant, premeu el botó <guibutton>Navega</guibutton> i "
@@ -631 +631 @@
-"Dona accés a les funcions del reproductor i als detalls sobre la pista que "
+"Dona accés a les functions del reproductor i also detalls sobre la pista que "
@@ -809 +809 @@
-"L'àrea de la barra d'eines proporciona accés als detalls sobre la pista que "
+"L'àrea de la barra d'eines proporciona accés also detalls sobre la pista que "
@@ -834 +834 @@
-"amunt o cap avall mentre el punter del ratolí sigui a sobre el botó del "
+"amount o cap avall mentre el punter del ratolí sigui a sobre el botó del "
@@ -868 +868 @@
-"<guibutton>Reprodueix</guibutton> a la barra d'eines, o simplement feu doble "
+"<guibutton>Reprodueix</guibutton> a la barra d'eines, o simplement feu double "
@@ -1078 +1078 @@
-"amunt i avall s'apuja i s'abaixa el volum. La icona de l'altaveu canviarà "
+"amount i avall s'apuja i s'abaixa el volum. La icona de l'altaveu canviarà "
@@ -1106,2 +1106,2 @@
-"fitxers de música que importes al <application>Reproductor de música "
-"Rhythmbox</application> (la biblioteca emmagatzema el camí per a accedir als "
+"fitxers de música que imports al <application>Reproductor de música "
+"Rhythmbox</application> (la biblioteca emmagatzema el camí per a accedir also "
@@ -1139,3 +1139,3 @@
-"teu ordinador (al directori d'INICI per exemple), però també pot contenir "
-"fitxers de música disponibles a través de serveis de xarxa remots. Alguns "
-"exemples de serveis de xarxa compatibles són: <_:itemizedlist-1/>"
+"teu ordinador (al directori d'INICI per example), però també pot contenir "
+"fitxers de música disponibles a través de serveis de xarxa remots. Alguns "
+"examples de serveis de xarxa compatibles són: <_:itemizedlist-1/>"
@@ -1445 +1445 @@
-"un autor publica un episodi, se n'informa els subscriptors del podcast "
+"un author publica un episodi, se n'informa els subscriptors del podcast "
@@ -1455 +1455 @@
-"El Reproductor de música Rhythmbox us permet subscriure-us als canals de "
+"El Reproductor de música Rhythmbox us permet subscriure-us also canals de "
@@ -1601 +1601 @@
-"guilabel>, l'<guilabel>Autor</guilabel>, la data de l'<guilabel>Última "
+"guilabel>, l'<guilabel>Author</guilabel>, la data de l'<guilabel>Última "
@@ -1683 +1683 @@
-"Els episodis s'han de baixar abans de poder ser llegits. Consulteu<xref "
+"Els episodis s'han de baixar abans de poder set llegits. Consulteu<xref "
@@ -1853 +1853 @@
-"«gènere» concret, un grup d'artistes específic o fins i tot pistes que "
+"«gènere» concert, un grup d'artistes específic o fins i tot pistes que "
@@ -2098 +2098 @@
-msgstr "Inseriu un CD buit."
+msgstr "Inseriu un CD built."
@@ -2130 +2130 @@
-"Rhythmbox</application> hauria de ser compatible amb la majoria de "
+"Rhythmbox</application> hauria de set compatible amb la majoria de "
@@ -2141 +2141 @@
-"Quan connectes un reproductor d'àudio portàtil, s'afegeix una icona del "
+"Quan connects un reproductor d'àudio portàtil, s'afegeix una icona del "
@@ -2155 +2155 @@
-"buit anomenat <filename>.is_audio_player</filename> a la jerarquia superior "
+"built anomenat <filename>.is_audio_player</filename> a la jerarquia superior "
@@ -2200 +2200 @@
-"escoltar la música emmagatzemada als ordinadors dels vostres amics i ells "
+"escoltar la música emmagatzemada also ordinadors dels vostres amics i ells "
@@ -2301 +2301 @@
-"de música Rhythmbox</application> per a adaptar-lo als vostres requeriments "
+"de música Rhythmbox</application> per a adaptar-lo also vostres requirements "
@@ -2370 +2370 @@
-"Trieu les <guilabel>Columnes visibles</guilabel> que voleu que es mostrin al "
+"Trieu les <guilabel>Columnes visible</guilabel> que voleu que es mostrin al "
@@ -2607 +2607 @@
-msgstr "<keycombo> <keycap>Ctrl</keycap> <keycap>Fletxa amunt</keycap> </keycombo>"
+msgstr "<keycombo> <keycap>Ctrl</keycap> <keycap>Fletxa amount</keycap> </keycombo>"
--- ./help/zh_CN/zh_CN.po	original
+++ ./help/zh_CN/zh_CN.po	fixed
@@ -397 +397 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -618 +618 @@
-msgid "Displays informations about the source selected in Source List."
+msgid "Displays information about the source selected in Source List."
@@ -1202 +1202 @@
-"Rhythmbox enables you to suscribe to podcast feeds, so when a new episode is "
+"Rhythmbox enables you to subscribe to podcast feeds, so when a new episode is "
@@ -1638,2 +1638,2 @@
-"Smart Playlists are playlists built from criterias, so their content is "
-"build dynamically; all the tracks matching criterias will be added in the "
+"Smart Playlists are playlists built from criteria, so their content is "
+"build dynamically; all the tracks matching criteria will be added in the "
@@ -1658 +1658 @@
-msgid "Edit the playlist criterias through the query editor."
+msgid "Edit the playlist criteria through the query editor."
@@ -1663 +1663 @@
-"Once your criterias chosen, click <guibutton>New</guibutton> to create the "
+"Once your criteria chosen, click <guibutton>New</guibutton> to create the "
@@ -1681 +1681 @@
-"criterias. Once done, choose <guibutton>Close</guibutton>."
+"criteria. Once done, choose <guibutton>Close</guibutton>."
@@ -1728 +1728 @@
-"display the tracks matched by your criterias."
+"display the tracks matched by your criteria."
--- ./help/uk/uk.po	original
+++ ./help/uk/uk.po	fixed
@@ -220 +220 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -319 +319 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
--- ./help/gl/gl.po	original
+++ ./help/gl/gl.po	fixed
@@ -58 +58 @@
-"Para informar dun erro ou facer unha suxestión sobre o aplicativo Reprodutor "
+"Para informar dun error ou facer unha suxestión sobre o aplicativo Reprodutor "
--- ./help/el/el.po	original
+++ ./help/el/el.po	fixed
@@ -581 +581 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -881 +881 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -4406 +4406 @@
-"You may extract a single document from such a collection, and dispbibute it "
+"You may extract a single document from such a collection, and distribute it "
--- ./help/C/index.docbook	original
+++ ./help/C/index.docbook	fixed
@@ -184 +184 @@
-		<date>Jaunary 2020</date>
+		<date>January 2020</date>
@@ -244 +244 @@
-            <para>Create automatic playlists from criterias.</para>
+            <para>Create automatic playlists from criteria.</para>
@@ -1330 +1330 @@
-      <table frame="topbot" id="rb-shorcuts-1">
+      <table frame="topbot" id="rb-shortcuts-1">
@@ -1422 +1422 @@
-      <table frame="topbot" id="rb-shorcuts-2">
+      <table frame="topbot" id="rb-shortcuts-2">
@@ -1506 +1506 @@
-      <table frame="topbot" id="rb-shorcuts-3">
+      <table frame="topbot" id="rb-shortcuts-3">
--- ./help/sl/sl.po	original
+++ ./help/sl/sl.po	fixed
@@ -348 +348 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -529 +529 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -711 +711 @@
-msgstr "Nadzor glasnosti je na desni strani orodne vrstice. Pritisk na ikono zvočnika bo pokazal drsnik glasnosti. Drsanje tega navzgor in navzdol bo povečalo in zmanjšalo glasnost. Ikona zvočnika se bo spremenila in prikazala relativno glasnost. <placeholder-1/>"
+msgstr "Nadzor glasnosti je na desni strani orodne vrstice. Pritisk na ikono zvočnika bo pokazal drsnik glasnosti. Drsanje tega navzgor in navzdol bo povečalo in zmanjšalo glasnost. Ikona zvočnika se bo spremenila in prikazala relation glasnost. <placeholder-1/>"
@@ -1318 +1318 @@
-msgstr "Vsakič ko se je skladba spremenila, ali je bila epizoda podcasta prejeta vas lahko <application>Rhythmbox predvajalnik glasbe</application> obvesti. Na namizju prikaže obvestilno okno, ki vsebuje podatke."
+msgstr "Vsakič ko se je skladba spremenila, ali je bila epizoda podcasta prejeta was lahko <application>Rhythmbox predvajalnik glasbe</application> obvesti. Na namizju prikaže obvestilno okno, ki vsebuje podatke."
@@ -1358 +1358 @@
-msgstr "<guibutton>Pokaži obvestila</guibutton>&mdash; Določi ali naj vas <application>Rhythmbox predvajalnik glasbe</application> obvešča o spremembah skladb in različnih podrobnostih."
+msgstr "<guibutton>Pokaži obvestila</guibutton>&mdash; Določi ali naj was <application>Rhythmbox predvajalnik glasbe</application> obvešča o spremembah skladb in različnih podrobnostih."
@@ -1430 +1430 @@
-msgstr "Izognite se nastavitvi vaše mape <filename class=\"directory\">Doma</filename> kot mesto knjižnice, ker ta zmožnost zahteva veliko CPE."
+msgstr "Izognite se nastavitvi vaše map <filename class=\"directory\">Doma</filename> kot mesto knjižnice, ker ta zmožnost zahteva veliko CPE."
--- ./help/cs/cs.po	original
+++ ./help/cs/cs.po	fixed
@@ -139 +139 @@
-"JEHO UPRAVENÁ VERZE VADNÁ V JAKÉMKOLIV SMYSLU, VY (NIKOLIV PŮVODCE, AUTOR "
+"JEHO UPRAVENÁ VERZE VADNÁ V JAKÉMKOLIV SMYSLU, VY (NIKOLIV PŮVODCE, AUTHOR "
@@ -160 +160 @@
-"(VČETNĚ NEDBALOSTNÍCH), SMLOUVU NEBO JINÉ, NENÍ AUTOR, PŮVODNÍ PISATEL, "
+"(VČETNĚ NEDBALOSTNÍCH), SMLOUVU NEBO JINÉ, NENÍ AUTHOR, PŮVODNÍ PISATEL, "
@@ -326 +326 @@
-"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>Jaunary "
+"<revnumber>Rhythmbox Music Player Manual V3.4.4</revnumber> <date>January "
@@ -419 +419 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -1420 +1420 @@
-"Podcast je nový způsob vysílání zvukového obsahu po webu. Když autor "
+"Podcast je nový způsob vysílání zvukového obsahu po webu. Když author "
@@ -1575 +1575 @@
-"guilabel>, <guilabel>Autor</guilabel>, datum <guilabel>Poslední aktualizace</"
+"guilabel>, <guilabel>Author</guilabel>, datum <guilabel>Poslední aktualizace</"
@@ -2467 +2467 @@
-"Zásuvný modul profilu na Last.fm shromažďuje informace o skladbách, které "
+"Zásuvný module profilu na Last.fm shromažďuje informace o skladbách, které "
@@ -2485 +2485 @@
-"Abyste mohli používat tento zásuvný modul, musíte mít zřízený účet na jednom "
+"Abyste mohli používat tento zásuvný module, musíte mít zřízený účet na jednom "
@@ -2769 +2769 @@
-"modul pro podporu Linux Infrared Remote Control (LIRC). Následující řetězce "
+"module pro podporu Linux Infrared Remote Control (LIRC). Následující řetězce "
--- ./help/fr/fr.po	original
+++ ./help/fr/fr.po	fixed
@@ -310 +310 @@
-"Permission vous est donnée de copier, distribuer et/ou modifier ce document "
+"Permission vous est donnée de copier, distribute et/ou modifier ce document "
@@ -327 +327 @@
-"distribuer ce manuel indépendamment de la collection, vous devez joindre un "
+"distribute ce manuel indépendamment de la collection, vous devez joindre un "
@@ -359 +359 @@
-"LE PRÉSENT DOCUMENT EST FOURNI « TEL QUEL », SANS AUCUNE GARANTIE, EXPRESSE "
+"LE PRÉSENT DOCUMENT EST FOURNI « TEL QUEL », SANS AUCUNE GARANTIE, EXPRESSIVE "
@@ -389 +389 @@
-"PARTIES NE POURRA ÊTRE TENU RESPONSABLE À L'ÉGARD DE QUICONQUE POUR TOUT "
+"PARTIES NE POURRA ÊTRE TENU RESPONSIBLE À L'ÉGARD DE QUICONQUE POUR TOUT "
@@ -540 +540 @@
-"Rhythmbox est un lecteur de musique complet pour l'environnement de bureau "
+"Rhythmbox est un lecteur de musique complete pour l'environment de bureau "
@@ -584 +584 @@
-"Affiche des informations sur les chansons par la lecture de meta-données."
+"Affiche des information sur les chansons par la lecture de meta-données."
@@ -593 +593 @@
-"Crée des listes de lecture statiques par glisser-déposer à partir de la "
+"Crée des listed de lecture statiques par glisser-déposer à partir de la "
@@ -597,2 +597,2 @@
-msgid "Create automatic playlists from criterias."
-msgstr "Crée des listes de lecture intelligentes à partir de critères."
+msgid "Create automatic playlists from criteria."
+msgstr "Crée des listed de lecture intelligentes à partir de critères."
@@ -604 +604 @@
-"et les listes de lecture."
+"et les listed de lecture."
@@ -614 +614 @@
-"Lit les CD audio et télécharge sur Internet les informations telles que le "
+"Lit les CD audio et télécharge sur Internet les information telles que le "
@@ -619 +619 @@
-msgstr "Crée des CD audio à partir de listes de lecture."
+msgstr "Crée des CD audio à partir de listed de lecture."
@@ -774 +774 @@
-"Contient les principales fonctions du lecteur et fournit des détails au "
+"Contient les principles functions du lecteur et fournit des détails au "
@@ -820,2 +820,2 @@
-"Album. Le navigateur fournit en outre une fonction de recherche pour "
-"afficher uniquement les pistes correspondant à un critère donné."
+"Album. Le navigateur fournit en outre une function de recherche pour "
+"afficher uniquement les pistes correspondent à un critère donné."
@@ -844 +844 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -846 +846 @@
-"Affiche des informations à propos de la source sélectionnée dans le panneau "
+"Affiche des information à propos de la source sélectionnée dans le panneau "
@@ -871 +871 @@
-msgstr "Toutes les listes de lecture (normales et intelligentes)."
+msgstr "Toutes les listed de lecture (normals et intelligentes)."
@@ -875 +875 @@
-msgstr "Les CD audio insérés dans les lecteurs de CD de l'ordinateur."
+msgstr "Les CD audio insérés dans les lectures de CD de l'ordinateur."
@@ -879 +879 @@
-msgstr "Les lecteurs portables, comme l'iPod, connectés à l'ordinateur."
+msgstr "Les lectures portables, comme l'iPod, connectés à l'ordinateur."
@@ -896 +896 @@
-"vos radios Internet, vos listes de lecture et aux CD audio. Le panneau "
+"vos radios Internet, vos listed de lecture et aux CD audio. Le panneau "
@@ -964 +964 @@
-"La barre d'état contient des informations supplémentaires sur le nombre de "
+"La barre d'état contient des information supplémentaires sur le nombre de "
@@ -992 +992 @@
-"application> est disponible, permettant de minimiser l'espace utilisé et "
+"application> est disponible, permettant de minimiser l'escape utilisé et "
@@ -1187 +1187 @@
-"pointeur de la souris se trouve sur le bouton de contrôle du volume."
+"pointer de la souris se trouve sur le bouton de contrôle du volume."
@@ -1231 +1231 @@
-"sur votre ordinateur (dans votre dossier personnel, par exemple), mais aussi "
+"sur votre ordinateur (dans votre dossier personnel, par example), mais aussi "
@@ -1253 +1253 @@
-"pistes avec les informations stockées dans les balises des fichiers (comme "
+"pistes avec les information stockées dans les balises des fichiers (comme "
@@ -1355,2 +1355,2 @@
-"Rhythmbox propose une fonction de recherche qui permet de rechercher et de "
-"filtrer les pistes en fonction d'un terme."
+"Rhythmbox propose une function de recherche qui permet de rechercher et de "
+"filtrer les pistes en function d'un terme."
@@ -1365,3 +1365,3 @@
-"correspondant au texte saisi seront affichées et ce, mis à jour en "
-"permanence au fur et à mesure de vos frappes. La recherche pour "
-"correspondance est effectuée sur toutes les balises des pistes enregistrées "
+"correspondent au texte saisi seront affichées et ce, miss à jour en "
+"permanence au fur et à measure de vos frappes. La recherche pour "
+"correspondence est effectuée sur toutes les balises des pistes enregistrées "
@@ -1393 +1393 @@
-"pistes correspondant aux critères choisis."
+"pistes correspondent aux critères choisis."
@@ -1405,3 +1405,3 @@
-"des artistes, des albums et des genres, et seules les pistes correspondant à "
-"votre choix seront affichées dans la liste des pistes. Les critères "
-"s'appliquent au fur et à mesure des colonnes, de gauche à droite."
+"des artistes, des albums et des genres, et seules les pistes correspondent à "
+"votre choix seront affichées dans la liste des pistes. Les critères "
+"s'appliquent au fur et à measure des colonnes, de gauche à droite."
@@ -1428 +1428 @@
-"guilabel>. Le navigateur filtrera les pistes en fonction du critère choisi."
+"guilabel>. Le navigateur filtrera les pistes en function du critère choisi."
@@ -1461 +1461 @@
-"internet</guimenuitem></menuchoice>, entrez l'adresse de la radio station et "
+"internet</guimenuitem></menuchoice>, entrez l'address de la radio station et "
@@ -1493 +1493 @@
-"genre, mais aussi l'adresse du flux audio. Il est aussi possible de la noter."
+"genre, mais aussi l'address du flux audio. Il est aussi possible de la noter."
@@ -1541 +1541 @@
-"Pour plus d'informations sur les podcasts et le podcasting, vous pouvez "
+"Pour plus d'information sur les podcasts et le podcasting, vous pouvez "
@@ -1578 +1578 @@
-"l'adresse du flux podcast et appuyez sur le bouton <guibutton>Ajouter</"
+"l'address du flux podcast et appuyez sur le bouton <guibutton>Ajouter</"
@@ -1669 +1669 @@
-"du flux, la <guilabel>Langue</guilabel> ainsi que les informations de "
+"du flux, la <guilabel>Langue</guilabel> ainsi que les information de "
@@ -1874 +1874 @@
-msgstr "Source listes de lecture"
+msgstr "Source listed de lecture"
@@ -1883,3 +1883,3 @@
-"Les listes de lecture sont des sources créées à partir des pistes "
-"disponibles dans la bibliothèque. Elles permettent de regrouper des pistes "
-"selon des critères arbitraires, comme par exemple un groupe d'artistes ou "
+"Les listed de lecture sont des sources créées à partir des pistes "
+"disponibles dans la bibliothèque. Elles permettent de regrouper des pistes "
+"selon des critères arbitraires, comme par example un groupe d'artistes ou "
@@ -1890 +1890 @@
-msgstr "Listes de lecture statiques"
+msgstr "Listed de lecture statiques"
@@ -1894 +1894 @@
-msgstr "Listes de lecture intelligentes"
+msgstr "Listed de lecture intelligentes"
@@ -1899 +1899 @@
-"Rhythmbox propose deux types de listes de lecture : <_:itemizedlist-1/>"
+"Rhythmbox propose deux types de listed de lecture : <_:itemizedlist-1/>"
@@ -1904 +1904 @@
-"Rhythmbox vous permet de graver sur un CD audio les pistes de vos listes de "
+"Rhythmbox vous permet de graver sur un CD audio les pistes de vos listed de "
@@ -1911 +1911 @@
-"Les listes de lecture statiques sont des listes construites à partir de "
+"Les listed de lecture statiques sont des listed construites à partir de "
@@ -2031,3 +2031,3 @@
-"Les listes de lecture intelligentes sont des listes de lecture construites "
-"en fonction de critères, de telle sorte que leur contenu est généré "
-"dynamiquement. Toutes les pistes correspondant aux critères sont ajoutées à "
+"Les listed de lecture intelligentes sont des listed de lecture construites "
+"en function de critères, de telle sorte que leur contenu est généré "
+"dynamiquement. Toutes les pistes correspondent aux critères sont ajoutées à "
@@ -2038 +2038 @@
-msgstr "Création d'une liste de lecture intelligente"
+msgstr "Création d'une liste de lecture intelligence"
@@ -2046 +2046 @@
-"lecture</guisubmenu><guimenuitem>Nouvelle liste de lecture intelligente</"
+"lecture</guisubmenu><guimenuitem>Nouvelle liste de lecture intelligence</"
@@ -2068 +2068 @@
-msgstr "Édition d'une liste de lecture intelligente"
+msgstr "Édition d'une liste de lecture intelligence"
@@ -2078,3 +2078,3 @@
-"L'édition d'une liste de lecture intelligente vous permet de modifier les "
-"critères qui génèrent le contenu de la liste de lecture. Pour éditer une "
-"liste de lecture intelligente, sélectionnez-la puis choisissez "
+"L'édition d'une liste de lecture intelligence vous permet de modifier les "
+"critères qui génèrent le contenu de la liste de lecture. Pour éditer une "
+"liste de lecture intelligence, sélectionnez-la puis choisissez "
@@ -2088 +2088 @@
-msgstr "Suppression d'une liste de lecture intelligente"
+msgstr "Suppression d'une liste de lecture intelligence"
@@ -2095 +2095 @@
-"Pour supprimer une liste de lecture intelligente, sélectionnez la liste de "
+"Pour supprimer une liste de lecture intelligence, sélectionnez la liste de "
@@ -2121 +2121 @@
-"<guilabel>Limiter à</guilabel> et choisissez votre limite. Vous pouvez "
+"<guilabel>Limiter à</guilabel> et choisissez votre limit. Vous pouvez "
@@ -2134 +2134 @@
-"critères se ferme et la liste de lecture affiche les pistes correspondant à "
+"critères se ferme et la liste de lecture affiche les pistes correspondent à "
@@ -2164 +2164 @@
-"vous êtes connecté à Internet, les informations du CD sont recherchées et "
+"vous êtes connecté à Internet, les information du CD sont recherchées et "
@@ -2237 +2237 @@
-"Créez une liste de lecture, statique ou intelligente (voir <xref linkend="
+"Créez une liste de lecture, statique ou intelligence (voir <xref linkend="
@@ -2277,2 +2277,2 @@
-"capable de gérer la plupart des lecteurs audio portables, y compris l'iPod "
-"d'Apple, les baladeurs MTP et les lecteurs de stockage de masse."
+"capable de gérer la plupart des lectures audio portables, y compris l'iPod "
+"d'Apple, les baladeurs MTP et les lectures de stockage de masse."
@@ -2338 +2338 @@
-"partage aussi votre bibliothèque et vos listes de lecture. De cette manière, "
+"partage aussi votre bibliothèque et vos listed de lecture. De cette manière, "
@@ -2365 +2365 @@
-"de notification et d'obtenir des informations sans que l'interface "
+"de notification et d'obtenir des information sans que l'interface "
@@ -2378 +2378 @@
-msgstr "Obtention d'informations"
+msgstr "Obtention d'information"
@@ -2382 +2382 @@
-msgstr "Bulle d'aide"
+msgstr "Bullet d'aide"
@@ -2390 +2390 @@
-"Lorsque vous placez le pointeur de la souris au-dessus de l'icône du  "
+"Lorsque vous placez le pointer de la souris au-dessus de l'icône du  "
@@ -2407 +2407 @@
-"l'aide d'une fenêtre de notification affichant plusieurs informations à "
+"l'aide d'une fenêtre de notification affichant plusieurs information à "
@@ -2424 +2424 @@
-"<guilabel>Afficher les notifications</guilabel> du menu contextuel de "
+"<guilabel>Afficher les notifications</guilabel> du menu contextual de "
@@ -2438 +2438 @@
-"commandes suivantes à l'application :"
+"commands suivantes à l'application :"
@@ -2531 +2531 @@
-"Vous pouvez personnaliser l'apparence et le comportement du "
+"Vous pouvez personnaliser l'appearance et le comportement du "
@@ -2560 +2560 @@
-msgstr "Lecteurs portables"
+msgstr "Lectures portables"
@@ -2564 +2564 @@
-msgstr "Listes de lecture"
+msgstr "Listed de lecture"
@@ -2576 +2576 @@
-"Choisissez les <guilabel>Colonnes visibles</guilabel> à afficher dans le "
+"Choisissez les <guilabel>Colonnes visible</guilabel> à afficher dans le "
@@ -2606 +2606 @@
-"bibliothèque car cette fonctionnalité peut être coûteuse en ressources."
+"bibliothèque car cette fonctionnalité peut être coûteuse en resources."
@@ -2645 +2645 @@
-"Si cet emplacement ne vous convient pas, sélectionner un autre dossier dans "
+"Si cet emplacement ne vous convenient pas, sélectionner un autre dossier dans "
@@ -2701 +2701 @@
-"recevoir des recommandations à propos d'artistes que vous pourriez aimer."
+"recevoir des recommendations à propos d'artistes que vous pourriez aimer."
@@ -2710 +2710 @@
-"Le greffon de profil Last.fm collecte des informations sur les musiques que "
+"Le greffon de profil Last.fm collective des information sur les musiques que "
@@ -2738,2 +2738,2 @@
-"les informations d'état. Si votre page de profil Last.fm montre que votre "
-"profil n'est pas mis à jour, les informations affichées ici peuvent vous "
+"les information d'état. Si votre page de profil Last.fm montre que votre "
+"profil n'est pas miss à jour, les information affichées ici peuvent vous "
@@ -2855 +2855 @@
-msgstr "Se positionne dans le champ de recherche"
+msgstr "Se positioned dans le champ de recherche"
@@ -2921 +2921 @@
-"environnement de bureau."
+"environment de bureau."
@@ -3039 +3039 @@
-msgstr "Avance de 10 secondes sur la piste en cours"
+msgstr "Advance de 10 secondes sur la piste en cours"
@@ -3681 +3681 @@
-"You may extract a single document from such a collection, and dispbibute it "
+"You may extract a single document from such a collection, and distribute it "
@@ -3857,7 +3857,7 @@
-"Permission vous est donnée de copier, distribuer et/ou modifier ce document "
-"selon les termes de la Licence GNU Free Documentation License, Version 1.1 "
-"ou ultérieure publiée par la Free Software Foundation sans section "
-"inaltérable, sans texte de première page de couverture ni texte de dernière "
-"page de couverture. Vous trouverez un exemplaire de cette licence en suivant "
-"ce <_:ulink-1/> ou dans le fichier COPYING-DOCS fourni avec le présent "
-"manuel."
+"Permission vous est donnée de copier, distribute et/ou modifier ce document "
+"selon les termes de la Licence GNU Free Documentation License, Version 1.1 "
+"ou ultérieure publiée par la Free Software Foundation sans section "
+"inaltérable, sans texte de première page de couverture ni texte de dernière "
+"page de couverture. Vous trouverez un exemplaire de cette licence en suivant "
+"ce <_:ulink-1/> ou dans le fichier COPYING-DOCS fourni avec le présent "
+"manuel."
--- ./help/eu/eu.po	original
+++ ./help/eu/eu.po	fixed
@@ -480 +480 @@
-msgid "Create automatic playlists from criterias."
+msgid "Create automatic playlists from criteria."
@@ -722 +722 @@
-msgid "Displays informations about the source selected in the side pane."
+msgid "Displays information about the source selected in the side pane."
@@ -1288 +1288 @@
-"fitxategiak sare lokal batean nahiz Internenen entzuteko."
+"fitxategiak sare local batean nahiz Internenen entzuteko."
@@ -2156 +2156 @@
-"DAAPekin bateragarria den softwarea darabiltenekin, iTunes dutenekin, esate "
+"DATAPekin bateragarria den softwarea darabiltenekin, iTunes dutenekin, esate "
--- ./ChangeLog0.7.old	original
+++ ./ChangeLog0.7.old	fixed
@@ -918 +918 @@
-       don't depend on id3 pkgconfig file, add configury check for id3_frame_field
+       don't depend on id3 pkgconfig file, add configurable check for id3_frame_field
@@ -996 +996 @@
-      xine configury fixes, avoids crash (Bastien Nocera)
+      xine configurable fixes, avoids crash (Bastien Nocera)
@@ -1263 +1263 @@
-      remove refs to _AUDIO_QUALITY from monkey-meida
+      remove refs to _AUDIO_QUALITY from monkey-media
@@ -1545 +1545 @@
-       Add shuffle play order and modify RBHistory to accomodate it.
+       Add shuffle play order and modify RBHistory to accommodate it.
--- ./NEWS	original
+++ ./NEWS	fixed
@@ -50,16 +50,16 @@
-1634 - Opus files are encoded allways in hard-CBR
-1690 - Unhelpful error message for podcast feeds with no episodes
-1743 - Error transfering track: Target file already exists - while syncing with Android
-1744 - Transcoding WAV -> MP3 creates files outside "Music" dir during android sync
-1746 - Magnatune doesn't support buying individual albums
-1749 - Broken icon in 3.4.4 "About" dialog
-1750 - Remove reference to Miroguide search in code
-1751 - Replace www.rhythmbox.org with updated wiki.gnome.org links
-1758 - webremote plugin missing icons in 3.4.4
-1759 - webremote plugin not displaying icons / album art in Google chrome
-1760 - Rhythmbox crashed on plugging in iPhone 11 Pro with iOS 13.3
-1762 - RBAsyncCopy: Use G_FILE_COPY_OVERWRITE for g_file_copy_async()
-1763 - Magnatune: Rhythmbox crashes when download album is pressed more than once
-1764 - Magnatune: Albums download keeps repeating if album already exists
-1767 - Magnatune: Album art doesn't load properly
-1769 - Insufficent checking to determine whether files are under library directories
+1634 - Opus files are encoded always in hard-CBR
+1690 - Unhelpful error message for podcast feeds with no episodes
+1743 - Error transferring track: Target file already exists - while syncing with Android
+1744 - Transcoding WAV -> MP3 creates files outside "Music" dir during android sync
+1746 - Magnatune doesn't support buying individual albums
+1749 - Broken icon in 3.4.4 "About" dialog
+1750 - Remove reference to Miroguide search in code
+1751 - Replace www.rhythmbox.org with updated wiki.gnome.org links
+1758 - webremote plugin missing icons in 3.4.4
+1759 - webremote plugin not displaying icons / album art in Google chrome
+1760 - Rhythmbox crashed on plugging in iPhone 11 Pro with iOS 13.3
+1762 - RBAsyncCopy: Use G_FILE_COPY_OVERWRITE for g_file_copy_async()
+1763 - Magnatune: Rhythmbox crashes when download album is pressed more than once
+1764 - Magnatune: Albums download keeps repeating if album already exists
+1767 - Magnatune: Album art doesn't load properly
+1769 - Insufficient checking to determine whether files are under library directories
@@ -164 +164 @@
-- ru, courtesy of Ser82-png
+- ru, courtesy of Set82-png
@@ -395 +395 @@
-770262  Rhythmbox GIR Bindings Broken With 3.4 (rb_application_add_accelerator)
+770262  Rhythmbox GIT Bindings Broken With 3.4 (rb_application_add_accelerator)
@@ -627 +627 @@
-637747 - "Edit > Preferences > General > Visibile Columns > BPM" missing mnemonic
+637747 - "Edit > Preferences > General > Visible Columns > BPM" missing mnemonic
@@ -1743 +1743 @@
-584704 - External MP3 players should delete files rether than move to trash
+584704 - External MP3 players should delete files rather than move to trash
@@ -2023 +2023 @@
-584248 - "Always show notifications" doesn't work accross restarts
+584248 - "Always show notifications" doesn't work across restarts
@@ -2291 +2291 @@
-- William Jon McCann
+- William Jon McCan
@@ -2749 +2749 @@
-- William Jon McCann
+- William Jon McCan
@@ -2862,14 +2862,14 @@
-* use "friendly" date-time in track list (William Jon McCann)
-* add visualisation plugin (JOnathan Matthew)
-* support more lastfm:// URIs (Jonathan Matthew)
-* split code out into a library common to plugins and the binary (Jonathan Matthew)
-* display cover art in the tray icon tooltop and song-change notification (Ed Catmur)
-* Magnatune improvements (Adam Zimmerman)
-* core art improvements, support art for podcasts et al (Ed Catmur, Martin Szulecki)
-* Python plugin improvements (James Livingston, Jonathan Matthew)
-* add support for the Jamendo online catalogue (Guillaume Desmottes)
-* support new Gnome "media key" mechanism (James Livingston, Jonathan Matthew)
-* support track transfer for "generic" audio players, and improve iPod
-  track transfer support, including transcoding (James Livingston)
-* many build/run issues on Solaris (Irene Huang)
-* Nokia N800 support (William Jon McCann)
+* use "friendly" date-time in track list (William Jon McCan)
+* add visualisation plugin (JOnathan Matthew)
+* support more lastfm:// URIs (Jonathan Matthew)
+* split code out into a library common to plugins and the binary (Jonathan Matthew)
+* display cover art in the tray icon tooltop and song-change notification (Ed Catmur)
+* Magnatune improvements (Adam Zimmerman)
+* core art improvements, support art for podcasts et al (Ed Catmur, Martin Szulecki)
+* Python plugin improvements (James Livingston, Jonathan Matthew)
+* add support for the Jamendo online catalogue (Guillaume Desmottes)
+* support new Gnome "media key" mechanism (James Livingston, Jonathan Matthew)
+* support track transfer for "generic" audio players, and improve iPod
+  track transfer support, including transcoding (James Livingston)
+* many build/run issues on Solaris (Irene Huang)
+* Nokia N800 support (William Jon McCan)
@@ -2967,14 +2967,14 @@
-* turn CD burning into a plugin (William Jon McCann: #344300)
-* turn audio CD support into a plugin (James Livingston: #349415)
-* LIRC plugin fixes (Jonathan Matthew)
-* improve database thread usage
-* make DB handle unknown entry-types (Jonathan Matthew: #330226
-* improve plugin debug output, and bindings (James Livingston)
-* improve "import errors" and "missing files" source (William Jon McCann: #346800)
-* fix many memory leaks (William Jon McCann: #347446, #347446, #347446, #347446)
-* use GMapperFiles for DAAP transfers, fixing some iTunes clients (Jonathan Matthew: #330410)
-* add support for alternate playlists files (Alex Lancaster: #343659)
-* handle transparent panels correctly (DanWinship: #348208)
-* fix playlists subset searching (Jonathan Matthew: #348617)
-* make iradio playlists handling better (Jonathan Matthew: #347097)
-* use GOption instead og popt (William Jon McCann: #346930)
+* turn CD burning into a plugin (William Jon McCan: #344300)
+* turn audio CD support into a plugin (James Livingston: #349415)
+* LIRC plugin fixes (Jonathan Matthew)
+* improve database thread usage
+* make DB handle unknown entry-types (Jonathan Matthew: #330226
+* improve plugin debug output, and bindings (James Livingston)
+* improve "import errors" and "missing files" source (William Jon McCan: #346800)
+* fix many memory leaks (William Jon McCan: #347446, #347446, #347446, #347446)
+* use GMapperFiles for DAAP transfers, fixing some iTunes clients (Jonathan Matthew: #330410)
+* add support for alternate playlists files (Alex Lancaster: #343659)
+* handle transparent panels correctly (DanWinship: #348208)
+* fix playlists subset searching (Jonathan Matthew: #348617)
+* make iradio playlists handling better (Jonathan Matthew: #347097)
+* use GOption instead og popt (William Jon McCan: #346930)
@@ -3031,26 +3031,26 @@
-  Gareth Murphy, William Jon McCann, Martin Szulecki)
-* update the FSF's address (Gunnar Steinn Magnusson)
-* much improved Python bindings (James Livingston, Jonathan Matthew)
-* fix some translation issues (Nguyễn Thái Ngọc Duy, James Livingston: 339380, 343081)
-* improve startup time (James Livingston, Jonathan Matthew)
-* fix audioscrobbler submission, and allow viewing of info (Jonathan Matthew: 325848)
-* improve DBus interface (Jonathan Matthew, Tim Moloney)
-* allow transcoding during track transfer (Alessandro Decina: 322268)
-* cd burning fixes and improvements (William Jon McCann)
-* podcast feed parsing and download fixes (James Livingston: 339728)
-* turn the playback backend into a full GObject interface (James Livingston: 338667)
-* add more API documentation (Jonathan Mattjew)
-* add vorbis tag editing (James Livingston: 339878)
-* fix various threading insanities (Jonathan Matthew)
-* display "child libraries" with multiple library locations (James Livingston: 100552)
-* improve drag-and-drop from browsers (Jonathan Matthew: 327540)
-* support Motorola ROKR phones (Joe Barnett)
-* make query model limits saner (Janes Livingston)
-* source cleanup and API improvement (James Livingston, Jonathan Matthew)
-* improve status feedback for DAAP (Jonathan Matthew: 322020 and 338978)
-* memory improvement and leak fixed (James Livingston, Jonathan Matthew)
-* kill Bonobo support, require DBus, support DBus 0.3.0 (Jonathan Matthew: 339720)
-* add lyric download and view plugin (Jonathan Matthew: 319320)
-* add "add to playlist" menu (James Livingston: 323364)
-* allow changing of audio cd metadata (James Livingston)
-* improve DAAP handling (William Jon McCann: 342643)
+  Gareth Murphy, William Jon McCan, Martin Szulecki)
+* update the FSF's address (Gunnar Steinn Magnusson)
+* much improved Python bindings (James Livingston, Jonathan Matthew)
+* fix some translation issues (Nguyễn Thái Ngọc Duy, James Livingston: 339380, 343081)
+* improve startup time (James Livingston, Jonathan Matthew)
+* fix audioscrobbler submission, and allow viewing of info (Jonathan Matthew: 325848)
+* improve DBus interface (Jonathan Matthew, Tim Moloney)
+* allow transcoding during track transfer (Alessandro Decina: 322268)
+* cd burning fixes and improvements (William Jon McCan)
+* podcast feed parsing and download fixes (James Livingston: 339728)
+* turn the playback backend into a full GObject interface (James Livingston: 338667)
+* add more API documentation (Jonathan Mattjew)
+* add vorbis tag editing (James Livingston: 339878)
+* fix various threading insanities (Jonathan Matthew)
+* display "child libraries" with multiple library locations (James Livingston: 100552)
+* improve drag-and-drop from browsers (Jonathan Matthew: 327540)
+* support Motorola ROKR phones (Joe Barnett)
+* make query model limits saner (Janes Livingston)
+* source cleanup and API improvement (James Livingston, Jonathan Matthew)
+* improve status feedback for DAAP (Jonathan Matthew: 322020 and 338978)
+* memory improvement and leak fixed (James Livingston, Jonathan Matthew)
+* kill Bonobo support, require DBus, support DBus 0.3.0 (Jonathan Matthew: 339720)
+* add lyric download and view plugin (Jonathan Matthew: 319320)
+* add "add to playlist" menu (James Livingston: 323364)
+* allow changing of audio cd metadata (James Livingston)
+* improve DAAP handling (William Jon McCan: 342643)
@@ -3074,60 +3074,60 @@
-* break mDNS class into backend-specific classes (William Jon McCann)
-* add support for password-protected DAAP shares (William Jon McCann: 322966)
-* have per-client DAAP session (William Jon McCann: 329814)
-* make DAAP source icon show authentication status (William Jon McCann: 330291)
-* turn of paranoia when playing audio cds (James Livingston: 322270)
-* use network byte-order for DAAP, fixes some issues with Banshee (Jonathan Matthew)
-* fold RBSimpleView back into RBPropertyView (James Livingston: 327500)
-* store hidden state of entries in on-disk db (James Livingston: 325215)
-* add dbus methods for static playlist control (Jonathan Matthew: 329958)
-* force URI canonicalisation when first upgrading (James Livingston: 329988)
-* add browsers to playlists (James Livingston: 118862)
-* don't put drag-n-drop URIs in reverse order (Jonathan Matthew: 330283)
-* notification bubble fixed (Jonathan Matthew: 330876)
-* RhythmDB API cleanup (James Livingston, Jonathan Matthew: 330226)
-* add auto-completion to tag-editing (Sven Herzberg: )
-* add action to clear entire queue (Jonathan Matthew: 330014, 331392)
-* don't display entry notify bubble when containing "&" (Jonathan Matthew: 330784)
-* don't block UI when reading audio cd TOC (James Livingston: 329942)
-* stop polling cd drive when playing from it (James Livingston: 330716)
-* add Party Mode (William Jon McCann: 323933)
-* don't stop when playing track is deleted (James Livingston: 131150, 331712)
-* add quality column (James Livingston: 167659)
-* add "queue playlist" action (James Livingston: 330490, 330490)
-* update documentation to not be completely out-of-date (Baptiste Mille-Mathias: 314001)
-* add support for out-of-process metadata service (Jonathan Matthew: 329597)
-* port to using gnome-doc-utils (Luca Ferretti)
-* indicate pre-empted source when playing from queue (Jonathan Matthew: 330819)
-* add "starts with" and "ends with" string criteria (James Livingston)
-* don't choke on podcast feeds which use timezone names (Alex Lancaster: 331691)
-* make auto playlist editor non-modal (James Livingston: 320030)
-* add "missing files" and "import errors" sources (Jonathan Matthew: 167763, 142322)
-* use entry and button for Library Location preference (James Livingston: 328414)
-* remember window visibility between sessions (James Livingston: 127320)
-* don't import known non-audio files (James Livingston: 323179)
-* read more metadata from iPod dbs (Gunnar Steinn Magnusson: 324648)
-* support sources with no entry view (James Livingston: 331673, 331673)
-* add read-only PSP support (James Livingston, Bastien Nocera: 332337)
-* add read-only Nokia 770 support (James Livingston)
-* restore browser selections after browser change (James Livingston)
-* add "download location" to podcast info window (Jonathan Matthew: 330696)
-* fix issues with new totem-plparser recursion (James Livingston: 331508)
-* use drive rather than volume name for removable media (James Henstridge: 333080)
-* add gst 0.10 id3 tag editing (James Livingston: 309609)
-* add filtering support to debug output (Jonathan Matthew)
-* add plugin support (James Livingston: 330523)
-* add search bar (William Jon McCann: 328618, 334407)
-* filter browsers with search terms (Jonathan Matthew: 322787)
-* remove non-libnotify notifications (James Livingston: 331721)
-* update documentation (Baptiste Mille-Mathias)
-* add Increase and Decrease volume menu items (James Livingston: 123383)
-* add Python Console plugin (Steve Frécinaux)
-* add HTTP proxy support (Jonathan Matthew: 335091)
-* do all gnomevfs stats in one batch (Jonathan Matthew: 334106)
-* build properly on Solaris (Brian Cameron: 335318)
-* borrow Banshee's Eject icon, because g-i-t doesn't have one
-* have better "no GStreamer plugin found" messages (James Livingston: 128109)
-* add LIRC plugin (Jonathan Matthew)
-* use libsexy to add a clear button to the search box (James Livingston: 128109)
-* allow overriding of the toolbar button style (James Livingston: 336797)
-* add profiling hooks (William Jon McCann: 337387, 338114)
+* break mDNS class into backend-specific classes (William Jon McCan)
+* add support for password-protected DAAP shares (William Jon McCan: 322966)
+* have per-client DAAP session (William Jon McCan: 329814)
+* make DAAP source icon show authentication status (William Jon McCan: 330291)
+* turn of paranoia when playing audio cds (James Livingston: 322270)
+* use network byte-order for DAAP, fixes some issues with Banshee (Jonathan Matthew)
+* fold RBSimpleView back into RBPropertyView (James Livingston: 327500)
+* store hidden state of entries in on-disk db (James Livingston: 325215)
+* add dbus methods for static playlist control (Jonathan Matthew: 329958)
+* force URI canonicalisation when first upgrading (James Livingston: 329988)
+* add browsers to playlists (James Livingston: 118862)
+* don't put drag-n-drop URIs in reverse order (Jonathan Matthew: 330283)
+* notification bubble fixed (Jonathan Matthew: 330876)
+* RhythmDB API cleanup (James Livingston, Jonathan Matthew: 330226)
+* add auto-completion to tag-editing (Sven Herzberg: )
+* add action to clear entire queue (Jonathan Matthew: 330014, 331392)
+* don't display entry notify bubble when containing "&" (Jonathan Matthew: 330784)
+* don't block UI when reading audio cd TOC (James Livingston: 329942)
+* stop polling cd drive when playing from it (James Livingston: 330716)
+* add Party Mode (William Jon McCan: 323933)
+* don't stop when playing track is deleted (James Livingston: 131150, 331712)
+* add quality column (James Livingston: 167659)
+* add "queue playlist" action (James Livingston: 330490, 330490)
+* update documentation to not be completely out-of-date (Baptiste Mille-Mathias: 314001)
+* add support for out-of-process metadata service (Jonathan Matthew: 329597)
+* port to using gnome-doc-utils (Luca Ferretti)
+* indicate pre-empted source when playing from queue (Jonathan Matthew: 330819)
+* add "starts with" and "ends with" string criteria (James Livingston)
+* don't choke on podcast feeds which use timezone names (Alex Lancaster: 331691)
+* make auto playlist editor non-modal (James Livingston: 320030)
+* add "missing files" and "import errors" sources (Jonathan Matthew: 167763, 142322)
+* use entry and button for Library Location preference (James Livingston: 328414)
+* remember window visibility between sessions (James Livingston: 127320)
+* don't import known non-audio files (James Livingston: 323179)
+* read more metadata from iPod dbs (Gunnar Steinn Magnusson: 324648)
+* support sources with no entry view (James Livingston: 331673, 331673)
+* add read-only PSP support (James Livingston, Bastien Nocera: 332337)
+* add read-only Nokia 770 support (James Livingston)
+* restore browser selections after browser change (James Livingston)
+* add "download location" to podcast info window (Jonathan Matthew: 330696)
+* fix issues with new totem-plparser recursion (James Livingston: 331508)
+* use drive rather than volume name for removable media (James Henstridge: 333080)
+* add gst 0.10 id3 tag editing (James Livingston: 309609)
+* add filtering support to debug output (Jonathan Matthew)
+* add plugin support (James Livingston: 330523)
+* add search bar (William Jon McCan: 328618, 334407)
+* filter browsers with search terms (Jonathan Matthew: 322787)
+* remove non-libnotify notifications (James Livingston: 331721)
+* update documentation (Baptiste Mille-Mathias)
+* add Increase and Decrease volume menu items (James Livingston: 123383)
+* add Python Console plugin (Steve Frécinaux)
+* add HTTP proxy support (Jonathan Matthew: 335091)
+* do all gnomevfs stats in one batch (Jonathan Matthew: 334106)
+* build properly on Solaris (Brian Cameron: 335318)
+* borrow Banshee's Eject icon, because g-i-t doesn't have one
+* have better "no GStreamer plugin found" messages (James Livingston: 128109)
+* add LIRC plugin (Jonathan Matthew)
+* use libsexy to add a clear button to the search box (James Livingston: 128109)
+* allow overriding of the toolbar button style (James Livingston: 336797)
+* add profiling hooks (William Jon McCan: 337387, 338114)
@@ -3183,68 +3183,68 @@
-* don't try to burn long playlists [William Jon McCann: 321753]
-* other cd-burning fixes and HIG improvements [William Jon McCann: 321754]
-* fix "Post" and "Episode" wording [James Livingston: 321653]
-* display tag-writing errors to the user [James Livingston]
-* make the podcast dialog look like the song one [William Jon McCann]
-* use glib class private data everywhere [William Jon McCann: 313688]
-* add "Move to trash" command [Bastien Nocera: 315389]
-* support DBus 0.6 [William Jon McCann]
-* add support for "Watched Libraries] [James Livigston: 160159]
-* add support for remote gnome-vfs [James Livingston: 140355]
-* select source when hovering with drag [Thomas de Grenier de Latour: 323044]
-* fix parsing of some RSS feeds [Ryan P Skadberg: 323153]
-* use toolbar [William Jon McCann, James Livingston: 316238]
-* always hide rather than remove db entries until old [James Livingston]
-* ellipsise source names, instead of adding scroll bar [James Livingston]
-* allow year to be changed on multiple songs [Alex Lancaster]
-* refactor playlist classes [Jonathan Matthew]
-* add gstreamer 0.10 support [Jan Schmidt, James Livingston]
-* fix drag-and-drop of URLs [Jonathan Matthew:323610]
-* save metadata when forward/next are pressed [James Livingston: 320952]
-* fix complaints about deprecated libnautilusburn API in 2.13 [James Livingston]
-* make entry-views just a display, and fix play orders [Jonathan Matthew:323612]
-* remove distro-packaging stuff [James Livingston]
-* fix 5 sec pause when finding non-audio files with gst 0.10 [James Livingston]
-* fix playlist saving and shutdown [William Jon McCann: 322940]
-* submit songs longer than 30 mins to AudioScrobbler [Ståle Lyngaas: 323639]
-* make iradio dialog look like song one [William Jon McCann: 323306]
-* make genre tag-writing not use artist [Alex Lancaster: 323642]
-* more entry-view cleanup and refactoring [Jonathan Matthew: 323640]
-* fix problem with dropping artist/album into an entry view [James Livingston]
-* add play queue [Jonathan Matthew: 107787]
-* about dialog fixes and update AUTHORS and MAINTAINERS [William Jon McCann]
-* remove use of GMemChunks [James Livingston]
-* remove unused podcast feed column [William Jon McCann: 322961]
-* add support for the search box to playlists. [James Livingston]
-* add support for more date formats in podcast feeds [William Jon McCann]
-* use "friendly time" for properties display [William Jon McCann]
-* add fulscreen mode [William Jon McCann: 324075]
-* allow iradio stations to be stream URLs [Jonathan Matthew]
-* fix parsing of itunes:image element in podcasts [William Jon McCann]
-* allow podcasts with no pubication date [Jonathan Matthew]
-* add disc number to multiple-track properties window [Jonathan Matthew, 324777]
-* read playcount and year from ipod db [Gunnar Steinn Magnusson]
-* add 'last episode' field to the podcast feed dialog [Jonathan Matthew]
-* assorted DAAP fixes [James Livingston, Jonathan Matthew, William Jon McCann]
-* add libnotify support [Jonathan Matthew]
-* use G_DEFINE_TYPE [James Livingston, Lubomir Marinovm, William Jon McCann]
-* many play-order fixes [Jonathan Matthew]
-* add default playlists [William Jon McCann: 323004]
-* add support for Year criteria in auto playlists [Alex Lancaster: 321341]
-* give names to playlists created via drag-n-drop [William Jon McCann: 326116]
-* allow dbus to chaneg volume [Jonathan Matthew]
-* stop playback after a podcast finished [James Livingston: 322077]
-* fill in multi-track property window fields [James Livingston: 326054]
-* don't lose hidden entries from playlists [James Livingston: 319278]
-* add support for generic mass-storage audio players [James Livingston: 325602]
-* don't get stuck on recursive symlinks [James Livingston: 125452]
-* don't crash on hybrid audio+data cds [Jonathan Matthew]
-* make startup faster [James Livingston, Jonathan Matthew: 323348 and others]
-* display number of tracks in browsers [William Jon McCann: 327372]
-* add support for Year metadata from DAAP shares [Alex Lancaster: 327700]
-* support chunked-encoding for DAAP [Jonathan Matthew: 326738, 318852]
-* change default rating back to 0 [James Livingston]
-* sort URIs when artist/album is dragged [Jonathan Matthew: 327494]
-* remove items from browsers when tracks are hidden [James Livingston: 327061]
-* don't spin when all tracks are unplayable [Jnonathan Matthew: 329329]
-* minor UI and HIG fixes [Dennis Cranston, Jaap A. Haitsma, James Livingston,
-  Jonathan Matthew, William Jon McCann, Bastien Nocera]
+* don't try to burn long playlists [William Jon McCan: 321753]
+* other cd-burning fixes and HIG improvements [William Jon McCan: 321754]
+* fix "Post" and "Episode" wording [James Livingston: 321653]
+* display tag-writing errors to the user [James Livingston]
+* make the podcast dialog look like the song one [William Jon McCan]
+* use glib class private data everywhere [William Jon McCan: 313688]
+* add "Move to trash" command [Bastien Nocera: 315389]
+* support DBus 0.6 [William Jon McCan]
+* add support for "Watched Libraries] [James Livigston: 160159]
+* add support for remote gnome-vfs [James Livingston: 140355]
+* select source when hovering with drag [Thomas de Grenier de Latour: 323044]
+* fix parsing of some RSS feeds [Ryan P Skadberg: 323153]
+* use toolbar [William Jon McCan, James Livingston: 316238]
+* always hide rather than remove db entries until old [James Livingston]
+* ellipsise source names, instead of adding scroll bar [James Livingston]
+* allow year to be changed on multiple songs [Alex Lancaster]
+* refactor playlist classes [Jonathan Matthew]
+* add gstreamer 0.10 support [Jan Schmidt, James Livingston]
+* fix drag-and-drop of URLs [Jonathan Matthew:323610]
+* save metadata when forward/next are pressed [James Livingston: 320952]
+* fix complaints about deprecated libnautilusburn API in 2.13 [James Livingston]
+* make entry-views just a display, and fix play orders [Jonathan Matthew:323612]
+* remove distro-packaging stuff [James Livingston]
+* fix 5 sec pause when finding non-audio files with gst 0.10 [James Livingston]
+* fix playlist saving and shutdown [William Jon McCan: 322940]
+* submit songs longer than 30 mins to AudioScrobbler [Ståle Lyngaas: 323639]
+* make iradio dialog look like song one [William Jon McCan: 323306]
+* make genre tag-writing not use artist [Alex Lancaster: 323642]
+* more entry-view cleanup and refactoring [Jonathan Matthew: 323640]
+* fix problem with dropping artist/album into an entry view [James Livingston]
+* add play queue [Jonathan Matthew: 107787]
+* about dialog fixes and update AUTHORS and MAINTAINERS [William Jon McCan]
+* remove use of GMemChunks [James Livingston]
+* remove unused podcast feed column [William Jon McCan: 322961]
+* add support for the search box to playlists. [James Livingston]
+* add support for more date formats in podcast feeds [William Jon McCan]
+* use "friendly time" for properties display [William Jon McCan]
+* add fulscreen mode [William Jon McCan: 324075]
+* allow iradio stations to be stream URLs [Jonathan Matthew]
+* fix parsing of itunes:image element in podcasts [William Jon McCan]
+* allow podcasts with no pubication date [Jonathan Matthew]
+* add disc number to multiple-track properties window [Jonathan Matthew, 324777]
+* read playcount and year from ipod db [Gunnar Steinn Magnusson]
+* add 'last episode' field to the podcast feed dialog [Jonathan Matthew]
+* assorted DAAP fixes [James Livingston, Jonathan Matthew, William Jon McCan]
+* add libnotify support [Jonathan Matthew]
+* use G_DEFINE_TYPE [James Livingston, Lubomir Marinovm, William Jon McCan]
+* many play-order fixes [Jonathan Matthew]
+* add default playlists [William Jon McCan: 323004]
+* add support for Year criteria in auto playlists [Alex Lancaster: 321341]
+* give names to playlists created via drag-n-drop [William Jon McCan: 326116]
+* allow dbus to chaneg volume [Jonathan Matthew]
+* stop playback after a podcast finished [James Livingston: 322077]
+* fill in multi-track property window fields [James Livingston: 326054]
+* don't lose hidden entries from playlists [James Livingston: 319278]
+* add support for generic mass-storage audio players [James Livingston: 325602]
+* don't get stuck on recursive symlinks [James Livingston: 125452]
+* don't crash on hybrid audio+data cds [Jonathan Matthew]
+* make startup faster [James Livingston, Jonathan Matthew: 323348 and others]
+* display number of tracks in browsers [William Jon McCan: 327372]
+* add support for Year metadata from DAAP shares [Alex Lancaster: 327700]
+* support chunked-encoding for DAAP [Jonathan Matthew: 326738, 318852]
+* change default rating back to 0 [James Livingston]
+* sort URIs when artist/album is dragged [Jonathan Matthew: 327494]
+* remove items from browsers when tracks are hidden [James Livingston: 327061]
+* don't spin when all tracks are unplayable [Jnonathan Matthew: 329329]
+* minor UI and HIG fixes [Dennis Cranston, Jaap A. Haitsma, James Livingston,
+  Jonathan Matthew, William Jon McCan, Bastien Nocera]
@@ -3280 +3280 @@
-  James Livingston, Jonathan Matthew, William Jon McCann]
+  James Livingston, Jonathan Matthew, William Jon McCan]
@@ -3373 +3373 @@
-* Use a proper GTK status bar [William Jon McCann]
+* Use a proper GTK status bar [William Jon McCan]
@@ -3466 +3466 @@
-tr (Enver Altin)
+tr (Never Altin)
@@ -3494 +3494 @@
-* Fix flac configury [foser@gentoo.org]
+* Fix flac configurable [foser@gentoo.org]
@@ -3704 +3704 @@
-* UI improvments to playlist dialog and bugfixes [Yann Rouillard]
+* UI improvements to playlist dialog and bugfixes [Yann Rouillard]
@@ -3759 +3759 @@
-* Updated .spec file [William Jon McCann]
+* Updated .spec file [William Jon McCan]
--- ./sources/rb-display-page-group.h	original
+++ ./sources/rb-display-page-group.h	fixed
@@ -4 +4 @@
- *  Copyright (C) 2006  William Jon McCann <mccann@jhu.edu>
+ *  Copyright (C) 2006  William Jon McCan <mccann@jhu.edu>
--- ./sources/rb-library-source.c	original
+++ ./sources/rb-library-source.c	fixed
@@ -796 +796 @@
-	/* Replace path seperators with a hyphen */
+	/* Replace path separators with a hyphen */
--- ./sources/rb-display-page.c	original
+++ ./sources/rb-display-page.c	fixed
@@ -285,2 +285,2 @@
- * @text: (inout) (allow-none) (transfer full): holds the returned status text
- * @busy: (inout) (allow-none): holds the busy status
+ * @text: (input) (allow-none) (transfer full): holds the returned status text
+ * @busy: (input) (allow-none): holds the busy status
--- ./sources/rb-source.c	original
+++ ./sources/rb-source.c	fixed
@@ -1463,2 +1463,2 @@
- * @text: (inout) (allow-none) (transfer full): holds returned playback status text
- * @progress: (inout) (allow-none): holds returned playback status progress value
+ * @text: (input) (allow-none) (transfer full): holds returned playback status text
+ * @progress: (input) (allow-none): holds returned playback status progress value
--- ./sources/rb-display-page-group.c	original
+++ ./sources/rb-display-page-group.c	fixed
@@ -4 +4 @@
- *  Copyright (C) 2006  William Jon McCann <mccann@jhu.edu>
+ *  Copyright (C) 2006  William Jon McCan <mccann@jhu.edu>
--- ./lib/libmediaplayerid/meson.build	original
+++ ./lib/libmediaplayerid/meson.build	fixed
@@ -30 +30 @@
-mpid_gir = gnome.generate_gir(mediaplayerid_lib,
+mpid_git = gnome.generate_git(mediaplayerid_lib,
--- ./lib/libmediaplayerid/mpid-device.c	original
+++ ./lib/libmediaplayerid/mpid-device.c	fixed
@@ -516 +516 @@
-	 * A set of playlist format MIME types suppored by the device
+	 * A set of playlist format MIME types supported by the device
--- ./lib/rb-util.c	original
+++ ./lib/rb-util.c	fixed
@@ -1268,2 +1268,2 @@
-				/* set a nonexistant action name so it gets disabled */
-				g_menu_item_set_detailed_action (item, "nonexistant-action");
+				/* set a nonexistent action name so it gets disabled */
+				g_menu_item_set_detailed_action (item, "nonexistent-action");
--- ./lib/rb-cut-and-paste-code.c	original
+++ ./lib/rb-cut-and-paste-code.c	fixed
@@ -88 +88 @@
-	int nd, nm, ny;
+	int and, nm, ny;
@@ -101 +101 @@
-	g_date_time_get_ymd (now, &ny, &nm, &nd);
+	g_date_time_get_ymd (now, &ny, &nm, &and);
@@ -103 +103 @@
-	if (y == ny && m == nm && d == nd) {
+	if (y == ny && m == nm && d == and) {
--- ./ChangeLog0.8	original
+++ ./ChangeLog0.8	fixed
@@ -223 +223 @@
-	(rb_shell_load_uri_impl): Undo a patch that got accidently commited in
+	(rb_shell_load_uri_impl): Undo a patch that got accidently committed in
@@ -318 +318 @@
-2005-07-11  William Jon McCann  <mccann@jhu.edu>
+2005-07-11  William Jon McCan  <mccann@jhu.edu>
@@ -374 +374 @@
-2005-07-08  William Jon McCann  <mccann@jhu.edu>
+2005-07-08  William Jon McCan  <mccann@jhu.edu>
@@ -737 +737 @@
-	committ patch from  Gabriel de Perthuis to add a text/uri-list target
+	commit patch from  Gabriel de Perthuis to add a text/uri-list target
@@ -1200 +1200 @@
-2005-01-09 17:51:29 GMT	William Jon McCann <mccann@jhu.edu>	patch-159
+2005-01-09 17:51:29 GMT	William Jon McCan <mccann@jhu.edu>	patch-159
@@ -1417 +1417 @@
-2004-11-23 05:35:49 GMT	William Jon McCann <mccann@jhu.edu>	patch-150
+2004-11-23 05:35:49 GMT	William Jon McCan <mccann@jhu.edu>	patch-150
@@ -1439 +1439 @@
-2004-11-17 16:49:21 GMT	William Jon McCann <mccann@jhu.edu>	patch-149
+2004-11-17 16:49:21 GMT	William Jon McCan <mccann@jhu.edu>	patch-149
@@ -1908 +1908 @@
-2004-09-14 20:06:51 GMT	William Jon McCann <mccann@jhu.edu>	patch-123
+2004-09-14 20:06:51 GMT	William Jon McCan <mccann@jhu.edu>	patch-123
@@ -1936 +1936 @@
-2004-09-14 19:35:58 GMT	William Jon McCann <mccann@jhu.edu>	patch-122
+2004-09-14 19:35:58 GMT	William Jon McCan <mccann@jhu.edu>	patch-122
@@ -2155 +2155 @@
-       Propage a RBShell to rb-playlist-source through rb-playlist-manager
+       Propagate a RBShell to rb-playlist-source through rb-playlist-manager
@@ -2567 +2567 @@
-      fix aclocal build (William Jon McCann)
+      fix aclocal build (William Jon McCan)
@@ -2897 +2897 @@
-      Properly hide the unecessary browser panes at startup
+      Properly hide the unnecessary browser panes at startup
@@ -4439 +4439 @@
-      handle possibly uninitalized variable case
+      handle possibly uninitialized variable case
--- ./plugins/lyrics/lyrics.py	original
+++ ./plugins/lyrics/lyrics.py	fixed
@@ -85 +85 @@
-	# strip things like "(live at Somewhere)", "(accoustic)", etc
+	# strip things like "(live at Somewhere)", "(acoustic)", etc
--- ./plugins/audioscrobbler/rb-audioscrobbler-profile-page.c	original
+++ ./plugins/audioscrobbler/rb-audioscrobbler-profile-page.c	fixed
@@ -1092 +1092 @@
-	/* delete the entries which were transfered.
+	/* delete the entries which were transferred.
--- ./plugins/mpris/mpris-spec.h	original
+++ ./plugins/mpris/mpris-spec.h	fixed
@@ -39 +39 @@
-	"    <signal name='Seeked'>"
+	"    <signal name='Sought'>"
--- ./plugins/mpris/rb-mpris-plugin.c	original
+++ ./plugins/mpris/rb-mpris-plugin.c	fixed
@@ -77 +77 @@
-	gboolean emit_seeked;
+	gboolean emit_sought;
@@ -161,12 +161,12 @@
-	if (plugin->emit_seeked) {
-		GError *error = NULL;
-		rb_debug ("emitting Seeked; new time %" G_GINT64_FORMAT, plugin->last_elapsed/1000);
-		g_dbus_connection_emit_signal (plugin->connection,
-					       NULL,
-					       MPRIS_OBJECT_NAME,
-					       MPRIS_PLAYER_INTERFACE,
-					       "Seeked",
-					       g_variant_new ("(x)", plugin->last_elapsed / 1000),
-					       &error);
-		if (error != NULL) {
-			g_warning ("Unable to set MPRIS Seeked signal: %s", error->message);
+	if (plugin->emit_sought) {
+		GError *error = NULL;
+		rb_debug ("emitting Sought; new time %" G_GINT64_FORMAT, plugin->last_elapsed/1000);
+		g_dbus_connection_emit_signal (plugin->connection,
+					       NULL,
+					       MPRIS_OBJECT_NAME,
+					       MPRIS_PLAYER_INTERFACE,
+					       "Sought",
+					       g_variant_new ("(x)", plugin->last_elapsed / 1000),
+					       &error);
+		if (error != NULL) {
+			g_warning ("Unable to set MPRIS Sought signal: %s", error->message);
@@ -175 +175 @@
-		plugin->emit_seeked = 0;
+		plugin->emit_sought = 0;
@@ -1341 +1341 @@
-	plugin->emit_seeked = TRUE;
+	plugin->emit_sought = TRUE;
@@ -1425 +1425 @@
-		g_warning ("Unable to read MPRIS interface specificiation: %s", error->message);
+		g_warning ("Unable to read MPRIS interface specification: %s", error->message);
--- ./plugins/brasero-disc-recorder/rb-disc-recorder-plugin.c	original
+++ ./plugins/brasero-disc-recorder/rb-disc-recorder-plugin.c	fixed
@@ -3 +3 @@
- *  Copyright (C) 2006 William Jon McCann <mccann@jhu.edu>
+ *  Copyright (C) 2006 William Jon McCan <mccann@jhu.edu>
--- ./plugins/brasero-disc-recorder/cd-recorder.plugin.desktop.in	original
+++ ./plugins/brasero-disc-recorder/cd-recorder.plugin.desktop.in	fixed
@@ -6,2 +6,2 @@
-Authors=William Jon McCann, Rouquier Philippe
-Copyright=Copyright © 2006 William Jon McCann, © 2008-2009 Rouquier Philippe
+Authors=William Jon McCan, Rouquier Philippe
+Copyright=Copyright © 2006 William Jon McCan, © 2008-2009 Rouquier Philippe
--- ./plugins/pythonconsole/pythonconsole.py	original
+++ ./plugins/pythonconsole/pythonconsole.py	fixed
@@ -278 +278 @@
-			# Keep indentation of precendent line
+			# Keep indentation of precedent line
--- ./plugins/daap/rb-daap-sharing.c	original
+++ ./plugins/daap/rb-daap-sharing.c	fixed
@@ -3 +3 @@
- *  Implmentation of DAAP (iTunes Music Sharing) sharing
+ *  Implementation of DAAP (iTunes Music Sharing) sharing
--- ./plugins/ipod/rb-ipod-db.c	original
+++ ./plugins/ipod/rb-ipod-db.c	fixed
@@ -56 +56 @@
- * the iPod), RbIpodSource should update the GUI immediatly even if the IpodDB
+ * the iPod), RbIpodSource should update the GUI immediately even if the IpodDB
--- ./plugins/ipod/rb-ipod-source.c	original
+++ ./plugins/ipod/rb-ipod-source.c	fixed
@@ -1087 +1087 @@
-			rb_debug ("Failed to remove non-existant iPod Play Counts file");
+			rb_debug ("Failed to remove non-existent iPod Play Counts file");
--- ./backends/rb-player.c	original
+++ ./backends/rb-player.c	fixed
@@ -79 +79 @@
- * it opens (#rb_player_open), which is included in the paramters with each
+ * it opens (#rb_player_open), which is included in the parameters with each
@@ -415 +415 @@
- * the phenomemon known as 'gapless playback'.
+ * the phenomenon known as 'gapless playback'.
--- ./ChangeLog0.7	original
+++ ./ChangeLog0.7	fixed
@@ -1072 +1072 @@
-       massive overhaul of rhythmdb saving system. now saves periodically asynchronously when dirty, saves synchronously on exit if neded
+       massive overhaul of rhythmdb saving system. now saves periodically asynchronously when dirty, saves synchronously on exit if needed
@@ -1316 +1316 @@
-       changed the buffering progress to a seperate callback
+       changed the buffering progress to a separate callback
@@ -1845 +1845 @@
-      acutally put audioscale in pipeline (doh)
+      actually put audioscale in pipeline (doh)
@@ -1929 +1929 @@
-      merge from 0.6: flac configury fix
+      merge from 0.6: flac configurable fix
@@ -1936 +1936 @@
-       fix flac configury (foser@gentoo.org)
+       fix flac configurable (foser@gentoo.org)
@@ -2284 +2284 @@
-       explicity store active query rows in query creator
+       explicitly store active query rows in query creator
@@ -2783 +2783 @@
-      Conditionnaly defines the static mutex used as a fallback in rb-atomic since it's not always used
+      Conditionally defines the static mutex used as a fallback in rb-atomic since it's not always used
--- ./ChangeLog0.6	original
+++ ./ChangeLog0.6	fixed
@@ -1256 +1256 @@
-       Include config.h where neccessary, clarify a string in the song dialog, update German translation.
+       Include config.h where necessary, clarify a string in the song dialog, update German translation.
@@ -1770 +1770 @@
-      add configury to check for XFree86/XSun
+      add configurable to check for XFree86/XSun
@@ -4441 +4441 @@
-    With this commit, the first pass at RhythmDB is commited. 
+    With this commit, the first pass at RhythmDB is committed. 
--- ./podcast/rb-podcast-manager.h	original
+++ ./podcast/rb-podcast-manager.h	fixed
@@ -3 +3 @@
- *  Copyright (C) 2005 Renato Araujo Oliveira Filho - INdT <renato.filho@indt.org.br>
+ *  Copyright (C) 2005 Renato Araujo Oliveira Filho - IAndT <renato.filho@indt.org.br>
--- ./podcast/rb-podcast-parse.c	original
+++ ./podcast/rb-podcast-parse.c	fixed
@@ -3 +3 @@
- *  Copyright (C) 2005 Renato Araujo Oliveira Filho - INdT <renato.filho@indt.org.br>
+ *  Copyright (C) 2005 Renato Araujo Oliveira Filho - IAndT <renato.filho@indt.org.br>
--- ./podcast/rb-podcast-parse.h	original
+++ ./podcast/rb-podcast-parse.h	fixed
@@ -2 +2 @@
- *  Copyright (C) 2005 Renato Araujo Oliveira Filho - INdT <renato.filho@indt.org.br>
+ *  Copyright (C) 2005 Renato Araujo Oliveira Filho - IAndT <renato.filho@indt.org.br>
--- ./podcast/rb-podcast-manager.c	original
+++ ./podcast/rb-podcast-manager.c	fixed
@@ -3 +3 @@
- *  Copyright (C) 2005 Renato Araujo Oliveira Filho - INdT <renato.filho@indt.org.br>
+ *  Copyright (C) 2005 Renato Araujo Oliveira Filho - IAndT <renato.filho@indt.org.br>
--- ./AUTHORS	original
+++ ./AUTHORS	fixed
@@ -17 +17 @@
-William Jon McCann  <mccann@jhu.edu>
+William Jon McCan  <mccann@jhu.edu>
--- ./rhythmdb/rhythmdb.h	original
+++ ./rhythmdb/rhythmdb.h	fixed
@@ -406 +406 @@
- * implicitly ANDed. Here's an example:
+ * implicitly ANDead. Here's an example:
--- ./rhythmdb/rhythmdb-tree.c	original
+++ ./rhythmdb/rhythmdb-tree.c	fixed
@@ -2615 +2615 @@
-check_entry_existance (RBRefString *keyword,
+check_entry_existence (RBRefString *keyword,
@@ -2639 +2639 @@
-	g_hash_table_foreach (db->priv->keywords, (GHFunc)check_entry_existance, &data);
+	g_hash_table_foreach (db->priv->keywords, (GHFunc)check_entry_existence, &data);
--- ./rhythmdb/rhythmdb-query-model.c	original
+++ ./rhythmdb/rhythmdb-query-model.c	fixed
@@ -1975 +1975 @@
-	   occured in rhythmdb_query_model_drag_data_received */
+	   occurred in rhythmdb_query_model_drag_data_received */
--- ./rhythmdb/DESIGN	original
+++ ./rhythmdb/DESIGN	fixed
@@ -252 +252 @@
-smart playlist query requries it.
+smart playlist query requires it.
@@ -260 +260 @@
-** Morph RBIRadioBackend into the trival class RBIRadioLoader
+** Morph RBIRadioBackend into the trivial class RBIRadioLoader
--- ./rhythmdb/rhythmdb.c	original
+++ ./rhythmdb/rhythmdb.c	fixed
@@ -341 +341 @@
-	 * Database name.  Not sure whta this is used for.
+	 * Database name.  Not sure what this is used for.
@@ -495 +495 @@
-	 * entry independantly of an extra metadata request.
+	 * entry independently of an extra metadata request.
--- ./ChangeLog.pre-0.12	original
+++ ./ChangeLog.pre-0.12	fixed
@@ -1944 +1944 @@
-2008-10-01  William Jon McCann  <jmccann@redhat.com>
+2008-10-01  William Jon McCan  <jmccann@redhat.com>
@@ -1952 +1952 @@
-2008-10-01  William Jon McCann  <jmccann@redhat.com>
+2008-10-01  William Jon McCan  <jmccann@redhat.com>
@@ -1958 +1958 @@
-2008-10-01  William Jon McCann  <jmccann@redhat.com>
+2008-10-01  William Jon McCan  <jmccann@redhat.com>
@@ -2252 +2252 @@
-2008-10-01  William Jon McCann  <jmccann@redhat.com>
+2008-10-01  William Jon McCan  <jmccann@redhat.com>
@@ -2258 +2258 @@
-2008-10-01  William Jon McCann  <jmccann@redhat.com>
+2008-10-01  William Jon McCan  <jmccann@redhat.com>
@@ -2264 +2264 @@
-2008-10-01  William Jon McCann  <jmccann@redhat.com>
+2008-10-01  William Jon McCan  <jmccann@redhat.com>
@@ -2306 +2306 @@
-2008-09-30  William Jon McCann  <jmccann@redhat.com>
+2008-09-30  William Jon McCan  <jmccann@redhat.com>
@@ -2314 +2314 @@
-2008-09-30  William Jon McCann  <jmccann@redhat.com>
+2008-09-30  William Jon McCan  <jmccann@redhat.com>
@@ -2345 +2345 @@
-2008-09-26  William Jon McCann  <jmccann@redhat.com>
+2008-09-26  William Jon McCan  <jmccann@redhat.com>
@@ -2734 +2734 @@
-	callback being called simulatenously on multiple threads.
+	callback being called simultaneously on multiple threads.
@@ -2831 +2831 @@
-	Remove unneccessary imports.
+	Remove unnecessary imports.
@@ -3925 +3925 @@
-	soon during RbIpodSource instanciation since 
+	soon during RbIpodSource instantiation since 
@@ -5117 +5117 @@
-	iterface name, which I accidently committed
+	interface name, which I accidently committed
@@ -6692 +6692 @@
-	local files will be server. Need a propert http server that can read
+	local files will be server. Need a property http server that can read
@@ -7227 +7227 @@
-	types to have a name. Should catch any occurrances of 388783 if they
+	types to have a name. Should catch any occurrences of 388783 if they
@@ -7252 +7252 @@
-	attempt to disconnect if we aready are. Fixes #330201
+	attempt to disconnect if we already are. Fixes #330201
@@ -7464 +7464 @@
-	22x22 icon with diferent star emblem, matching other icons
+	22x22 icon with different star emblem, matching other icons
@@ -7692 +7692 @@
-	in tee branchs properly.
+	in tee branches properly.
@@ -7985 +7985 @@
-	configure.ac for easier maintainance (raise gnome-vfs version from
+	configure.ac for easier maintenance (raise gnome-vfs version from
@@ -8603 +8603 @@
-	(rhythmdb_tree_entry_keyword_has), (check_entry_existance): 64 bit
+	(rhythmdb_tree_entry_keyword_has), (check_entry_existence): 64 bit
@@ -8639 +8639 @@
-	(check_entry_existance), (rhythmdb_tree_entry_keywords_get): make
+	(check_entry_existence), (rhythmdb_tree_entry_keywords_get): make
@@ -8698 +8698 @@
-	GPL-licenced vesion by Jakub Steiner, since CC-BY-SA licencing
+	GPL-licenced version by Jakub Steiner, since CC-BY-SA licencing
@@ -8773 +8773 @@
-2007-03-03  William Jon McCann  <mccann@jhu.edu>
+2007-03-03  William Jon McCan  <mccann@jhu.edu>
@@ -8984 +8984 @@
-2007-03-01  William Jon McCann  <mccann@jhu.edu>
+2007-03-01  William Jon McCan  <mccann@jhu.edu>
@@ -8994 +8994 @@
-2007-02-27  William Jon McCann  <mccann@jhu.edu>
+2007-02-27  William Jon McCan  <mccann@jhu.edu>
@@ -9397 +9397 @@
-2007-02-09  William Jon McCann  <mccann@jhu.edu>
+2007-02-09  William Jon McCan  <mccann@jhu.edu>
@@ -9402 +9402 @@
-2007-02-09  William Jon McCann  <mccann@jhu.edu>
+2007-02-09  William Jon McCan  <mccann@jhu.edu>
@@ -9424 +9424 @@
-2007-02-08  William Jon McCann  <mccann@jhu.edu>
+2007-02-08  William Jon McCan  <mccann@jhu.edu>
@@ -9441 +9441 @@
-2007-02-07  William Jon McCann  <mccann@jhu.edu>
+2007-02-07  William Jon McCan  <mccann@jhu.edu>
@@ -9671 +9671 @@
-	patch partly by:  William Jon McCann  <mccann@jhu.edu>
+	patch partly by:  William Jon McCan  <mccann@jhu.edu>
@@ -9724 +9724 @@
-2007-01-23  William Jon McCann  <mccann@jhu.edu>
+2007-01-23  William Jon McCan  <mccann@jhu.edu>
@@ -9865 +9865 @@
-	patch by:  William Jon McCann  <mccann@jhu.edu>
+	patch by:  William Jon McCan  <mccann@jhu.edu>
@@ -9905 +9905 @@
-	patch by:  William Jon McCann  <mccann@jhu.edu>
+	patch by:  William Jon McCan  <mccann@jhu.edu>
@@ -10242 +10242 @@
-2006-12-19  William Jon McCann  <mccann@jhu.edu>
+2006-12-19  William Jon McCan  <mccann@jhu.edu>
@@ -10293 +10293 @@
-	(update_browser_property_visibilty):
+	(update_browser_property_visibility):
@@ -10443 +10443 @@
-	accidently comitted.
+	accidently committed.
@@ -11061 +11061 @@
-	(rb_podcast_source_feed_updates_avaliable_cb):
+	(rb_podcast_source_feed_updates_available_cb):
@@ -11282 +11282 @@
-2006-10-23  William Jon McCann  <mccann@jhu.edu>
+2006-10-23  William Jon McCan  <mccann@jhu.edu>
@@ -11314 +11314 @@
-	in and out of existance.
+	in and out of existence.
@@ -11461 +11461 @@
-	hypens in URI schemes.
+	hyphens in URI schemes.
@@ -11463 +11463 @@
-2006-10-06  William Jon McCann  <mccann@jhu.edu>
+2006-10-06  William Jon McCan  <mccann@jhu.edu>
@@ -11539 +11539 @@
-	patch by:  William Jon McCann  <mccann@jhu.edu>
+	patch by:  William Jon McCan  <mccann@jhu.edu>
@@ -11545 +11545 @@
-2006-10-02  William Jon McCann  <mccann@jhu.edu>
+2006-10-02  William Jon McCan  <mccann@jhu.edu>
@@ -11706 +11706 @@
-	* help/C/rhythmbox.xml: fix some mispellings and grammer.
+	* help/C/rhythmbox.xml: fix some mispellings and grammar.
@@ -11720 +11720 @@
-	patch by:  William Jon McCann  <mccann@jhu.edu>
+	patch by:  William Jon McCan  <mccann@jhu.edu>
@@ -11733 +11733 @@
-	patch by:  William Jon McCann  <mccann@jhu.edu>
+	patch by:  William Jon McCan  <mccann@jhu.edu>
@@ -11887 +11887 @@
-2006-09-02  William Jon McCann  <mccann@jhu.edu>
+2006-09-02  William Jon McCan  <mccann@jhu.edu>
@@ -12031 +12031 @@
-	than doign lots of strcmp()s.
+	than doing lots of strcmp()s.
@@ -12116 +12116 @@
-	update-inteval value from 0 to 1, which causes it to update on
+	update-interval value from 0 to 1, which causes it to update on
@@ -12124 +12124 @@
-	+ data/rhythmbox.desktop.in.in: add mroe indirection to the build, so
+	+ data/rhythmbox.desktop.in.in: add more indirection to the build, so
@@ -12128 +12128 @@
-2006-08-10  William Jon McCann  <mccann@jhu.edu>
+2006-08-10  William Jon McCan  <mccann@jhu.edu>
@@ -12328 +12328 @@
-	patch by: William Jon McCann  <mccann@jhu.edu>
+	patch by: William Jon McCan  <mccann@jhu.edu>
@@ -12340 +12340 @@
-	to seach for local art from http:// URIs, or those gnome-vfs doesn't
+	to search for local art from http:// URIs, or those gnome-vfs doesn't
@@ -12616 +12616 @@
-2006-07-25  William Jon McCann  <mccann@jhu.edu>
+2006-07-25  William Jon McCan  <mccann@jhu.edu>
@@ -12690 +12690 @@
-	(update_browser_property_visibilty), (view_selection_reset_cb),
+	(update_browser_property_visibility), (view_selection_reset_cb),
@@ -12705 +12705 @@
-2006-07-25  William Jon McCann  <mccann@jhu.edu>
+2006-07-25  William Jon McCan  <mccann@jhu.edu>
@@ -12778 +12778 @@
-2006-07-23  William Jon McCann  <mccann@jhu.edu>
+2006-07-23  William Jon McCan  <mccann@jhu.edu>
@@ -13202 +13202 @@
-2006-07-17  William Jon McCann  <mccann@jhu.edu>
+2006-07-17  William Jon McCan  <mccann@jhu.edu>
@@ -13337 +13337 @@
-	(rb_podcast_source_feed_updates_avaliable_cb),
+	(rb_podcast_source_feed_updates_available_cb),
@@ -13421 +13421 @@
-2006-07-14  William Jon McCann  <mccann@jhu.edu>
+2006-07-14  William Jon McCan  <mccann@jhu.edu>
@@ -13462 +13462 @@
-2006-07-14  William Jon McCann  <mccann@jhu.edu>
+2006-07-14  William Jon McCan  <mccann@jhu.edu>
@@ -13600,467 +13600,467 @@
-	(rb_validate_channel_propert), (rb_validate_item_propert),
-	(rb_podcast_parser_start_element), (rb_podcast_parser_end_element),
-	(rb_podcast_parser_characters), (rb_podcast_parse_load_feed),
-	(rb_podcast_parse_date), (rb_podcast_parse_time),
-	(rb_podcast_parse_channel_free), (rb_podcast_parse_item_free):
-	* podcast/rb-podcast-parse.h:
-	* podcast/rb-podcast-properties-dialog.c:
-	(rb_podcast_properties_dialog_init),
-	(rb_podcast_properties_dialog_get_current_entry),
-	(rb_podcast_properties_dialog_update_title),
-	(rb_podcast_properties_dialog_update_duration),
-	(rb_podcast_properties_dialog_update_date):
-	* podcast/rb-podcast-properties-dialog.h:
-	* rhythmdb/gsequence.c: (g_sequence_new), (g_sequence_prepend),
-	(g_sequence_insert), (g_sequence_remove), (g_sequence_concatenate),
-	(g_sequence_remove_range), (g_sequence_get_ptr_at_pos),
-	(g_sequence_ptr_move), (g_sequence_ptr_sort_changed),
-	(g_sequence_search), (g_sequence_set_aggregate_data),
-	(g_sequence_node_update_fields), (g_sequence_node_rotate),
-	(find_min), (g_sequence_node_find_by_pos),
-	(g_sequence_node_find_closest), (g_sequence_node_free),
-	(g_sequence_node_split), (g_sequence_node_insert_before),
-	(g_sequence_node_get_length), (g_sequence_node_remove),
-	(g_sequence_node_calc_height), (g_sequence_node_insert_sorted),
-	(g_sequence_calc_tree_height):
-	* rhythmdb/rb-refstring.c: (rb_refstring_system_shutdown),
-	(rb_refstring_get):
-	* rhythmdb/rb-refstring.h:
-	* rhythmdb/rhythmdb-gda.c: (rhythmdb_gda_class_init),
-	(rhythmdb_gda_init), (dump_model), (execute_query),
-	(execute_nonquery), (ensure_table_exists), (collect_value_for_sql),
-	(collect_value_from_sql), (_initialize), (rhythmdb_gda_new),
-	(rhythmdb_gda_load), (rhythmdb_gda_entry_new),
-	(rhythmdb_gda_entry_set), (rhythmdb_gda_entry_get),
-	(rhythmdb_gda_ref), (rhythmdb_gda_entry_lookup_by_location),
-	(translate_query), (do_query), (rhythmdb_gda_do_full_query):
-	* rhythmdb/rhythmdb-gda.h:
-	* rhythmdb/rhythmdb-monitor.c: (rhythmdb_init_monitoring),
-	(rhythmdb_finalize_monitoring), (monitor_entry_file),
-	(monitor_library_directory), (rhythmdb_check_changed_file),
-	(rhythmdb_start_monitoring), (rhythmdb_directory_change_cb),
-	(rhythmdb_monitor_uri_path), (entry_volume_mounted_or_unmounted),
-	(rhythmdb_volume_mounted_cb), (rhythmdb_volume_unmounted_cb):
-	* rhythmdb/rhythmdb-private.h:
-	* rhythmdb/rhythmdb-property-model.c:
-	(rhythmdb_property_model_set_property),
-	(rhythmdb_property_model_row_inserted_cb),
-	(rhythmdb_property_model_prop_changed_cb),
-	(rhythmdb_property_model_compare),
-	(rhythmdb_property_model_get_value),
-	(rhythmdb_property_model_iter_nth_child),
-	(rhythmdb_property_model_drag_data_delete), (query_model_cb),
-	(rhythmdb_property_model_drag_data_get),
-	(rhythmdb_property_model_enable_drag),
-	(rhythmdb_property_model_column_get_type):
-	* rhythmdb/rhythmdb-property-model.h:
-	* rhythmdb/rhythmdb-query-model.c:
-	(rhythmdb_query_model_class_init),
-	(rhythmdb_query_model_set_property),
-	(rhythmdb_query_model_dispose), (rhythmdb_query_model_chain),
-	(rhythmdb_query_model_has_pending_changes),
-	(rhythmdb_query_model_entry_changed_cb),
-	(rhythmdb_query_model_entry_deleted_cb), (idle_process_update),
-	(rhythmdb_query_model_add_entry),
-	(rhythmdb_query_model_remove_from_main_list),
-	(rhythmdb_query_model_remove_entry),
-	(rhythmdb_query_model_drag_data_received),
-	(rhythmdb_query_model_row_drop_possible),
-	(rhythmdb_query_model_compute_status_normal),
-	(rhythmdb_query_model_set_sort_order),
-	(rhythmdb_query_model_get_entry_index),
-	(rhythmdb_query_model_base_row_inserted),
-	(rhythmdb_query_model_base_row_deleted),
-	(rhythmdb_query_model_reapply_query), (_reverse_sorting_func),
-	(rhythmdb_query_model_date_sort_func),
-	(rhythmdb_query_model_within_limit):
-	* rhythmdb/rhythmdb-query-model.h:
-	* rhythmdb/rhythmdb-query-results.c:
-	(rhythmdb_query_results_query_complete):
-	* rhythmdb/rhythmdb-query-results.h:
-	* rhythmdb/rhythmdb-query.c: (rhythmdb_query_copy),
-	(rhythmdb_query_concatenate), (rhythmdb_query_parse_valist),
-	(rhythmdb_query_free), (rhythmdb_read_encoded_property),
-	(rhythmdb_query_serialize), (rhythmdb_query_deserialize),
-	(rhythmdb_query_preprocess), (rhythmdb_query_get_type):
-	* rhythmdb/rhythmdb-tree.c: (rhythmdb_tree_finalize),
-	(rhythmdb_tree_parser_start_element),
-	(rhythmdb_tree_parser_end_element), (rhythmdb_tree_load),
-	(save_entry), (save_entry_type), (save_unknown_entry_type),
-	(rhythmdb_tree_save), (rhythmdb_tree_entry_new),
-	(rhythmdb_tree_property_new), (get_genres_hash_for_type),
-	(get_or_create_genre), (remove_entry_from_album),
-	(rhythmdb_tree_entry_set), (rhythmdb_tree_entry_delete),
-	(remove_one_song), (rhythmdb_tree_entry_delete_by_type),
-	(search_match_properties), (evaluate_conjunctive_subquery),
-	(clone_remove_ptr_array_index), (conjunctive_query_albums),
-	(conjunctive_query_artists), (conjunctive_query_genre),
-	(conjunctive_query), (split_query_by_disjunctions),
-	(do_query_recurse), (rhythmdb_tree_entry_foreach),
-	(hash_tree_entries_foreach), (hash_tree_albums_foreach),
-	(hash_tree_artists_foreach), (hash_tree_genres_foreach),
-	(rhythmdb_hash_tree_foreach),
-	(rhythmdb_tree_entry_type_registered):
-	* rhythmdb/rhythmdb.c: (rhythmdb_class_init),
-	(metadata_field_from_prop), (extract_gtype_from_enum_entry),
-	(extract_nice_name_from_enum_entry), (rhythmdb_init),
-	(rhythmdb_execute_multi_stat_info_cb), (rhythmdb_event_free),
-	(rhythmdb_shutdown), (rhythmdb_finalize),
-	(rhythmdb_emit_entry_signals_idle), (process_added_entries_cb),
-	(rhythmdb_entry_insert), (rhythmdb_entry_new),
-	(rhythmdb_entry_example_new),
-	(set_metadata_string_default_unknown), (is_ghost_entry),
-	(rhythmdb_process_stat_event), (rhythmdb_add_import_error_entry),
-	(rhythmdb_process_metadata_load),
-	(rhythmdb_process_queued_entry_set_event),
-	(rhythmdb_process_events), (rhythmdb_execute_stat_info_cb),
-	(queue_stat_uri), (rhythmdb_entry_get), (entry_to_rb_metadata),
-	(rhythmdb_add_uri_with_type), (rhythmdb_load_thread_main),
-	(rhythmdb_load), (rhythmdb_save_thread_main), (rhythmdb_save),
-	(rhythmdb_entry_set), (rhythmdb_entry_set_internal),
-	(rhythmdb_entry_sync_mirrored), (rhythmdb_entry_delete),
-	(rhythmdb_entry_delete_by_type),
-	(rhythmdb_propid_from_nice_elt_name),
-	(rhythmdb_do_full_query_async_parsed), (rhythmdb_do_full_query),
-	(rhythmdb_compute_status_normal),
-	(rhythmdb_entry_register_type_alias),
-	(rhythmdb_entry_type_foreach), (song_can_sync_metadata),
-	(rhythmdb_entry_song_get_type), (rhythmdb_entry_ignore_get_type),
-	(rhythmdb_entry_import_error_get_type),
-	(rhythmdb_entry_podcast_post_get_type),
-	(rhythmdb_entry_podcast_feed_get_type),
-	(rhythmdb_entry_set_mount_point), (rhythmdb_entry_set_visibility),
-	(rhythmdb_sync_library_location), (rhythmdb_entry_get_string),
-	(rhythmdb_entry_get_ulong), (rhythmdb_entry_type_get_type):
-	* rhythmdb/rhythmdb.h:
-	* shell/main.c: (main), (load_uri_args), (handle_dbus_message):
-	* shell/rb-history.c: (rb_history_new), (rb_history_set_playing),
-	(rb_history_limit_size):
-	* shell/rb-history.h:
-	* shell/rb-play-order-linear-loop.c:
-	(rb_linear_play_order_loop_get_next):
-	* shell/rb-play-order-linear-loop.h:
-	* shell/rb-play-order-linear.c:
-	* shell/rb-play-order-linear.h:
-	* shell/rb-play-order-queue.c:
-	(rb_queue_play_order_playing_entry_removed):
-	* shell/rb-play-order-queue.h:
-	* shell/rb-play-order-random-by-age-and-rating.c:
-	* shell/rb-play-order-random-by-age-and-rating.h:
-	* shell/rb-play-order-random-by-age.c:
-	(rb_random_by_age_get_entry_weight):
-	* shell/rb-play-order-random-by-age.h:
-	* shell/rb-play-order-random-by-rating.c:
-	* shell/rb-play-order-random-by-rating.h:
-	* shell/rb-play-order-random-equal-weights.c:
-	* shell/rb-play-order-random-equal-weights.h:
-	* shell/rb-play-order-random.c: (rb_random_filter_history),
-	(rb_random_get_total_weight), (rb_random_play_order_get_next),
-	(rb_random_db_changed), (rb_random_playing_entry_changed),
-	(rb_random_db_entry_deleted):
-	* shell/rb-play-order-shuffle.c: (remove_from_history),
-	(add_randomly_to_history), (get_query_model_contents),
-	(rb_shuffle_playing_entry_changed):
-	* shell/rb-play-order-shuffle.h:
-	* shell/rb-play-order.c: (rb_play_order_class_init),
-	(rb_play_order_set_property),
-	(rb_play_order_playing_source_changed),
-	(rb_play_order_query_model_changed_cb),
-	(rb_play_order_query_model_changed),
-	(rb_play_order_entry_added_cb), (default_playing_entry_removed):
-	* shell/rb-play-order.h:
-	* shell/rb-playlist-manager.c: (rb_playlist_manager_class_init),
-	(rb_playlist_manager_init), (rb_playlist_manager_set_uimanager),
-	(rb_playlist_manager_set_property),
-	(rb_playlist_manager_parse_file),
-	(rb_playlist_manager_load_playlists),
-	(rb_playlist_manager_is_dirty), (rb_playlist_manager_save_data),
-	(rb_playlist_manager_save_playlists),
-	(rb_playlist_manager_new_playlist),
-	(rb_playlist_manager_new_playlist_from_selection_data),
-	(rb_playlist_manager_cmd_new_automatic_playlist),
-	(rb_playlist_manager_cmd_edit_automatic_playlist),
-	(_queue_track_cb), (rb_playlist_manager_cmd_delete_playlist),
-	(save_playlist_response_cb), (export_set_extension_cb),
-	(filter_get_export_filter_label), (setup_format_menu),
-	(rb_playlist_manager_cmd_save_playlist),
-	(rb_playlist_manager_get_playlists),
-	(rb_playlist_manager_get_playlist_names), (_get_playlist_by_name),
-	(rb_playlist_manager_delete_playlist),
-	(rb_playlist_manager_export_playlist):
-	* shell/rb-playlist-manager.h:
-	* shell/rb-removable-media-manager.c:
-	(rb_removable_media_manager_class_init),
-	(rb_removable_media_manager_dispose),
-	(rb_removable_media_manager_finalize),
-	(rb_removable_media_manager_set_property),
-	(split_drive_from_cdda_uri),
-	(rb_removable_media_manager_playing_uri_changed_cb),
-	(rb_removable_media_manager_load_media),
-	(rb_removable_media_manager_volume_mounted_cb),
-	(remove_volume_by_source),
-	(rb_removable_media_manager_source_deleted_cb),
-	(rb_removable_media_manager_volume_unmounted_cb),
-	(rb_removable_media_manager_mount_volume),
-	(rb_removable_media_manager_set_uimanager),
-	(rb_removable_media_manager_scan), (do_transfer),
-	(rb_removable_media_manager_cmd_copy_tracks):
-	* shell/rb-removable-media-manager.h:
-	* shell/rb-shell-clipboard.c: (rb_shell_clipboard_init),
-	(rb_shell_clipboard_finalize), (rb_shell_clipboard_constructor),
-	(rb_shell_clipboard_sync),
-	(rb_shell_clipboard_idle_poll_deletions),
-	(rb_shell_clipboard_cmd_add_to_playlist_new),
-	(rb_shell_clipboard_playlist_add_cb),
-	(rb_shell_clipboard_playlist_deleted_cb),
-	(rb_shell_clipboard_playlist_renamed_cb),
-	(rb_shell_clipboard_playlist_visible_cb),
-	(rb_shell_clipboard_playlist_added_cb):
-	* shell/rb-shell-player.c: (rb_shell_player_class_init),
-	(rb_shell_player_constructor), (volume_pre_unmount_cb),
-	(rb_shell_player_init), (rb_shell_player_set_property),
-	(rb_shell_player_new), (rb_shell_player_open_playlist_url),
-	(rb_shell_player_open_location),
-	(rb_shell_player_set_playing_entry),
-	(rb_shell_player_play_order_update_cb),
-	(rb_shell_player_jump_to_current), (rb_shell_player_do_previous),
-	(rb_shell_player_do_next), (rb_shell_player_do_previous_or_seek),
-	(rb_shell_player_cmd_previous), (rb_shell_player_cmd_next),
-	(rb_shell_player_cmd_play), (rb_shell_player_playpause),
-	(rb_shell_player_sync_volume), (rb_shell_player_sync_replaygain),
-	(gconf_song_position_slider_visibility_changed),
-	(rb_shell_player_entry_activated_cb),
-	(rb_shell_player_property_row_activated_cb),
-	(rb_shell_player_entry_changed_cb),
-	(rb_shell_player_sync_with_source), (rb_shell_player_sync_buttons),
-	(actually_set_playing_source),
-	(rb_shell_player_set_playing_source_internal),
-	(rb_shell_player_get_playing_song_duration), (eos_cb),
-	(rb_shell_player_error), (error_cb), (info_available_cb),
-	(grab_mmkey), (filter_mmkeys), (_idle_unblock_signal_cb),
-	(rb_shell_player_error_get_type):
-	* shell/rb-shell-player.h:
-	* shell/rb-shell-preferences.c: (rb_shell_preferences_init),
-	(rb_shell_preferences_append_page),
-	(share_check_button_toggled_cb),
-	(password_check_button_toggled_cb), (add_daap_preferences),
-	(rb_shell_preferences_column_check_changed_cb),
-	(rb_shell_preferences_sync_column_button),
-	(rb_shell_preferences_sync),
-	(rb_shell_preferences_browser_views_activated_cb):
-	* shell/rb-shell.c: (rb_shell_class_init), (rb_shell_init),
-	(rb_shell_set_property), (rb_shell_get_property),
-	(rb_shell_sync_state), (idle_save_rhythmdb), (rb_shell_finalize),
-	(construct_widgets), (construct_load_ui), (rb_shell_constructor),
-	(rb_shell_get_visibility), (rb_shell_set_visibility),
-	(rb_shell_sync_window_state), (rb_shell_db_entry_added_cb),
-	(rb_shell_register_entry_type_for_source),
-	(rb_shell_transfer_progress_cb), (rb_shell_playing_from_queue_cb),
-	(rb_shell_playing_entry_changed_cb), (rb_shell_select_source),
-	(rb_shell_player_stream_song_changed_cb),
-	(rb_shell_set_window_title),
-	(rb_shell_view_smalldisplay_changed_cb),
-	(rb_shell_view_queue_as_sidebar_changed_cb),
-	(rb_shell_cmd_plugins), (add_to_library_response_cb),
-	(rb_shell_cmd_add_folder_to_library),
-	(rb_shell_cmd_add_file_to_library),
-	(rb_shell_sync_pane_visibility), (rb_shell_sync_smalldisplay),
-	(sidepane_visibility_changed_cb), (toolbar_state_changed_cb),
-	(rb_shell_jump_to_entry_with_source), (tray_embedded_cb),
-	(session_die_cb), (save_yourself_cb), (rb_shell_session_init),
-	(handle_playlist_entry_cb), (rb_shell_load_uri),
-	(rb_shell_add_to_queue), (rb_shell_present),
-	(rb_shell_get_song_properties), (rb_shell_set_song_property),
-	(rb_shell_volume_widget_changed_cb),
-	(rb_shell_player_volume_changed_cb),
-	(rb_shell_ui_location_get_type):
-	* shell/rb-shell.h:
-	* shell/rb-source-header.c: (ui_manager_add_widget_cb),
-	(rb_source_header_init), (rb_source_header_set_source_internal),
-	(rb_source_state_sync), (rb_source_header_clear_search),
-	(rb_source_header_view_browser_changed_cb):
-	* shell/rb-source-header.h:
-	* shell/rb-statusbar.c: (rb_statusbar_construct),
-	(rb_statusbar_init), (rb_statusbar_finalize),
-	(rb_statusbar_set_property), (rb_statusbar_set_progress),
-	(rb_statusbar_source_status_changed_cb):
-	* shell/rb-statusbar.h:
-	* shell/rb-tray-icon.c: (rb_tray_icon_init),
-	(rb_tray_icon_constructor), (rb_tray_icon_finalize),
-	(rb_tray_icon_set_property), (rb_tray_icon_show_window_changed_cb),
-	(rb_tray_icon_get_geom), (rb_tray_icon_notify):
-	* sources/rb-audiocd-source.c: (rb_audiocd_source_constructor),
-	(rb_audiocd_create_track_entry):
-	* sources/rb-auto-playlist-source.c:
-	(rb_auto_playlist_source_class_init),
-	(rb_auto_playlist_source_constructor),
-	(rb_auto_playlist_source_new_from_xml), (impl_reset_filters),
-	(impl_search), (impl_receive_drag), (impl_save_contents_to_xml),
-	(rb_auto_playlist_source_query_complete_cb),
-	(rb_auto_playlist_source_do_query),
-	(rb_auto_playlist_source_set_query),
-	(rb_auto_playlist_source_browser_changed_cb),
-	(search_action_to_prop):
-	* sources/rb-auto-playlist-source.h:
-	* sources/rb-browser-source.c: (rb_browser_source_init),
-	(rb_browser_source_dispose), (search_action_to_prop),
-	(rb_browser_source_constructor),
-	(rb_browser_source_cmd_choose_genre),
-	(rb_browser_source_cmd_choose_artist),
-	(rb_browser_source_cmd_choose_album), (impl_search),
-	(rb_browser_source_browser_changed_cb),
-	(rb_browser_source_do_query):
-	* sources/rb-browser-source.h:
-	* sources/rb-daap-source.c: (rb_daap_source_class_init),
-	(rb_daap_source_init), (rb_daap_source_dispose),
-	(rb_daap_source_set_property), (start_browsing),
-	(rb_daap_sources_init), (rb_daap_sources_shutdown),
-	(rb_daap_source_connection_cb), (rb_daap_source_activate),
-	(rb_daap_source_cmd_disconnect), (rb_daap_source_find_for_uri),
-	(rb_daap_source_get_headers), (rb_daap_source_get_status):
-	* sources/rb-daap-source.h:
-	* sources/rb-import-errors-source.h:
-	* sources/rb-ipod-source.c: (rb_ipod_source_name_changed_cb),
-	(rb_ipod_source_init), (ipod_path_to_uri), (add_rb_playlist),
-	(add_ipod_song_to_db), (load_ipod_db_idle_cb),
-	(rb_ipod_load_songs), (rb_ipod_get_itunesdb_path),
-	(rb_ipod_is_volume_ipod), (hal_udi_is_ipod), (impl_get_ui_actions),
-	(impl_move_to_trash), (impl_receive_drag), (test_dir_on_ipod),
-	(ipod_mkdir_with_parents), (build_ipod_dir_name),
-	(generate_ipod_filename), (ipod_path_from_unix_path),
-	(impl_delete_thyself):
-	* sources/rb-iradio-source.c: (rb_iradio_source_class_init),
-	(rb_iradio_source_init), (rb_iradio_source_constructor),
-	(rb_iradio_source_new), (guess_uri_scheme),
-	(rb_iradio_source_add_station),
-	(rb_iradio_source_async_update_play_statistics),
-	(genre_selection_reset_cb), (rb_iradio_source_do_query),
-	(stations_view_drag_data_received_cb),
-	(rb_iradio_source_cmd_new_station):
-	* sources/rb-iradio-source.h:
-	* sources/rb-library-source.c: (rb_library_source_dispose),
-	(rb_library_source_constructor),
-	(rb_library_source_location_button_clicked_cb),
-	(impl_get_config_widget), (rb_library_source_library_location_cb),
-	(sanitize_path), (filepath_parse_pattern),
-	(layout_example_label_update),
-	(rb_library_source_layout_filename_changed), (build_filename),
-	(impl_can_paste), (impl_paste),
-	(rb_library_source_add_child_source),
-	(rb_library_source_sync_child_sources):
-	* sources/rb-library-source.h:
-	* sources/rb-missing-files-source.h:
-	* sources/rb-play-queue-source.c:
-	(rb_play_queue_source_constructor), (impl_show_entry_view_popup):
-	* sources/rb-play-queue-source.h:
-	* sources/rb-playlist-source-recorder.c:
-	(rb_playlist_source_recorder_class_init), (update_speed_combobox),
-	(_nautilus_burn_drive_eject), (burn_cd), (ask_rewrite_disc),
-	(rb_playlist_source_recorder_init),
-	(rb_playlist_source_recorder_new):
-	* sources/rb-playlist-source.c: (rb_playlist_source_constructor),
-	(rb_playlist_source_save_playlist),
-	(rb_playlist_source_entry_added_cb),
-	(rb_playlist_source_set_query_model),
-	(rb_playlist_source_add_to_map):
-	* sources/rb-podcast-source.c: (rb_podcast_source_class_init),
-	(rb_podcast_source_init), (rb_podcast_source_dispose),
-	(rb_podcast_source_finalize), (search_action_to_prop),
-	(rb_podcast_source_constructor), (rb_podcast_source_set_property),
-	(rb_podcast_source_get_property), (rb_podcast_source_new),
-	(impl_delete), (rb_podcast_source_songs_show_popup_cb),
-	(rb_podcast_source_feeds_show_popup_cb), (feed_select_change_cb),
-	(rb_podcast_source_show_browser), (construct_query_from_selection),
-	(rb_podcast_source_do_query), (impl_get_config_widget),
-	(rb_podcast_source_btn_file_change_cb),
-	(posts_view_drag_data_received_cb),
-	(rb_podcast_source_cmd_download_post),
-	(rb_podcast_source_cmd_cancel_download),
-	(rb_podcast_source_cmd_delete_feed),
-	(rb_podcast_source_cmd_properties_feed),
-	(rb_podcast_source_cmd_update_feed),
-	(rb_podcast_source_post_status_cell_data_func),
-	(rb_podcast_source_post_feed_cell_data_func),
-	(rb_podcast_source_post_date_cell_data_func),
-	(rb_podcast_source_load_finish_cb), (impl_receive_drag),
-	(rb_podcast_source_entry_activated_cb), (impl_can_add_to_queue),
-	(impl_add_to_queue), (rb_podcast_source_cmd_new_podcast),
-	(impl_get_status):
-	* sources/rb-podcast-source.h:
-	* sources/rb-removable-media-source.c:
-	(rb_removable_media_source_constructor):
-	* sources/rb-removable-media-source.h:
-	* sources/rb-source.h:
-	* sources/rb-sourcelist-model.c: (rb_sourcelist_model_class_init),
-	(rb_sourcelist_model_new), (rb_sourcelist_model_is_row_visible),
-	(rb_sourcelist_model_row_is_separator),
-	(rb_sourcelist_model_drag_data_received),
-	(rb_sourcelist_model_row_drop_possible), (path_is_droppable),
-	(rb_sourcelist_model_row_drop_position),
-	(rb_sourcelist_model_get_drag_target),
-	(rb_sourcelist_model_row_draggable),
-	(rb_sourcelist_model_drag_data_get),
-	(rb_sourcelist_model_row_inserted_cb),
-	(rb_sourcelist_model_get_group_path):
-	* sources/rb-sourcelist.c: (rb_sourcelist_append),
-	(match_source_to_iter), (rb_sourcelist_source_to_iter),
-	(rb_sourcelist_visible_source_to_iter),
-	(rb_sourcelist_edit_source_name),
-	(rb_sourcelist_selection_changed_cb), (button_press_cb),
-	(key_release_cb), (name_notify_cb), (icon_notify_cb),
-	(rb_sourcelist_title_cell_data_func), (source_name_edited_cb):
-	* sources/rb-static-playlist-source.c:
-	(rb_static_playlist_source_class_init),
-	(rb_static_playlist_source_constructor),
-	(rb_static_playlist_source_load_from_xml), (impl_reset_filters),
-	(impl_search), (rb_static_playlist_source_do_query),
-	(rb_static_playlist_source_browser_changed_cb),
-	(impl_receive_drag), (impl_save_contents_to_xml),
-	(rb_static_playlist_source_add_location_swapped),
-	(search_action_to_prop):
-	* sources/rb-static-playlist-source.h:
-	* widgets/bacon-volume.c: (bacon_volume_button_get_type):
-	* widgets/eggtrayicon.c: (egg_tray_icon_init),
-	(egg_tray_icon_get_orientation_property),
-	(egg_tray_icon_send_manager_message),
-	(egg_tray_icon_update_manager_window),
-	(egg_tray_icon_manager_window_destroyed), (egg_tray_icon_realize),
-	(egg_tray_icon_send_message), (egg_tray_icon_notify):
-	* widgets/eggtrayicon.h:
-	* widgets/rb-cell-renderer-pixbuf.c:
-	(rb_cell_renderer_pixbuf_get_property),
-	(rb_cell_renderer_pixbuf_set_property),
-	(rb_cell_renderer_pixbuf_get_size),
-	(rb_cell_renderer_pixbuf_render),
-	(rb_cell_renderer_pixbuf_activate):
-	* widgets/rb-cell-renderer-rating.c:
-	(rb_cell_renderer_rating_class_init),
-	(rb_cell_renderer_rating_get_property),
-	(rb_cell_renderer_rating_set_property),
-	(rb_cell_renderer_rating_get_size),
-	(rb_cell_renderer_rating_render),
-	(rb_cell_renderer_rating_activate):
-	* widgets/rb-dialog.c:
-	* widgets/rb-dialog.h:
-	* widgets/rb-druid.c: (rb_druid_init_widgets), (rb_druid_new),
-	(path_dialog_response_cb), (idle_set_sensitive), (do_response),
-	(rb_druid_page3_finish_cb):
-	* widgets/rb-entry-view.c: (rb_entry_view_class_init),
-	(rb_entry_view_init), (rb_entry_view_set_property),
-	(rb_entry_view_new), (rb_entry_view_play_count_cell_data_func),
-	(rb_entry_view_year_cell_data_func), (rb_entry_view_sync_sorting),
-	(rb_entry_view_get_sorting_type), (rb_entry_view_set_sorting_type),
-	(rb_entry_view_set_sorting_order),
-	(rb_entry_view_column_clicked_cb), (rb_entry_view_append_column),
-	(rb_entry_view_set_columns_clickable), (rb_entry_view_constructor),
-	(rb_entry_view_playing_song_changed),
-	(rb_entry_view_button_press_cb), (rb_entry_view_rows_reordered_cb),
-	(rb_entry_view_scroll_to_entry), (set_column_visibility),
-	(rb_entry_view_set_fixed_column_width),
-	(rb_entry_view_get_time_date_column_sample),
-	(rb_entry_view_state_get_type):
-	* widgets/rb-entry-view.h:
-	* widgets/rb-header.c: (rb_header_init), (rb_header_set_property),
-	(rb_header_sync), (slider_moved_timeout), (slider_moved_callback),
-	(changed_idle_callback), (rb_header_elapsed_changed_cb):
-	* widgets/rb-library-browser.c: (rb_library_browser_constructor),
-	(update_browser_property_visibilty),
+	(rb_validate_channel_property), (rb_validate_item_property),
+	(rb_podcast_parser_start_element), (rb_podcast_parser_end_element),
+	(rb_podcast_parser_characters), (rb_podcast_parse_load_feed),
+	(rb_podcast_parse_date), (rb_podcast_parse_time),
+	(rb_podcast_parse_channel_free), (rb_podcast_parse_item_free):
+	* podcast/rb-podcast-parse.h:
+	* podcast/rb-podcast-properties-dialog.c:
+	(rb_podcast_properties_dialog_init),
+	(rb_podcast_properties_dialog_get_current_entry),
+	(rb_podcast_properties_dialog_update_title),
+	(rb_podcast_properties_dialog_update_duration),
+	(rb_podcast_properties_dialog_update_date):
+	* podcast/rb-podcast-properties-dialog.h:
+	* rhythmdb/gsequence.c: (g_sequence_new), (g_sequence_prepend),
+	(g_sequence_insert), (g_sequence_remove), (g_sequence_concatenate),
+	(g_sequence_remove_range), (g_sequence_get_ptr_at_pos),
+	(g_sequence_ptr_move), (g_sequence_ptr_sort_changed),
+	(g_sequence_search), (g_sequence_set_aggregate_data),
+	(g_sequence_node_update_fields), (g_sequence_node_rotate),
+	(find_min), (g_sequence_node_find_by_pos),
+	(g_sequence_node_find_closest), (g_sequence_node_free),
+	(g_sequence_node_split), (g_sequence_node_insert_before),
+	(g_sequence_node_get_length), (g_sequence_node_remove),
+	(g_sequence_node_calc_height), (g_sequence_node_insert_sorted),
+	(g_sequence_calc_tree_height):
+	* rhythmdb/rb-refstring.c: (rb_refstring_system_shutdown),
+	(rb_refstring_get):
+	* rhythmdb/rb-refstring.h:
+	* rhythmdb/rhythmdb-gda.c: (rhythmdb_gda_class_init),
+	(rhythmdb_gda_init), (dump_model), (execute_query),
+	(execute_nonquery), (ensure_table_exists), (collect_value_for_sql),
+	(collect_value_from_sql), (_initialize), (rhythmdb_gda_new),
+	(rhythmdb_gda_load), (rhythmdb_gda_entry_new),
+	(rhythmdb_gda_entry_set), (rhythmdb_gda_entry_get),
+	(rhythmdb_gda_ref), (rhythmdb_gda_entry_lookup_by_location),
+	(translate_query), (do_query), (rhythmdb_gda_do_full_query):
+	* rhythmdb/rhythmdb-gda.h:
+	* rhythmdb/rhythmdb-monitor.c: (rhythmdb_init_monitoring),
+	(rhythmdb_finalize_monitoring), (monitor_entry_file),
+	(monitor_library_directory), (rhythmdb_check_changed_file),
+	(rhythmdb_start_monitoring), (rhythmdb_directory_change_cb),
+	(rhythmdb_monitor_uri_path), (entry_volume_mounted_or_unmounted),
+	(rhythmdb_volume_mounted_cb), (rhythmdb_volume_unmounted_cb):
+	* rhythmdb/rhythmdb-private.h:
+	* rhythmdb/rhythmdb-property-model.c:
+	(rhythmdb_property_model_set_property),
+	(rhythmdb_property_model_row_inserted_cb),
+	(rhythmdb_property_model_prop_changed_cb),
+	(rhythmdb_property_model_compare),
+	(rhythmdb_property_model_get_value),
+	(rhythmdb_property_model_iter_nth_child),
+	(rhythmdb_property_model_drag_data_delete), (query_model_cb),
+	(rhythmdb_property_model_drag_data_get),
+	(rhythmdb_property_model_enable_drag),
+	(rhythmdb_property_model_column_get_type):
+	* rhythmdb/rhythmdb-property-model.h:
+	* rhythmdb/rhythmdb-query-model.c:
+	(rhythmdb_query_model_class_init),
+	(rhythmdb_query_model_set_property),
+	(rhythmdb_query_model_dispose), (rhythmdb_query_model_chain),
+	(rhythmdb_query_model_has_pending_changes),
+	(rhythmdb_query_model_entry_changed_cb),
+	(rhythmdb_query_model_entry_deleted_cb), (idle_process_update),
+	(rhythmdb_query_model_add_entry),
+	(rhythmdb_query_model_remove_from_main_list),
+	(rhythmdb_query_model_remove_entry),
+	(rhythmdb_query_model_drag_data_received),
+	(rhythmdb_query_model_row_drop_possible),
+	(rhythmdb_query_model_compute_status_normal),
+	(rhythmdb_query_model_set_sort_order),
+	(rhythmdb_query_model_get_entry_index),
+	(rhythmdb_query_model_base_row_inserted),
+	(rhythmdb_query_model_base_row_deleted),
+	(rhythmdb_query_model_reapply_query), (_reverse_sorting_func),
+	(rhythmdb_query_model_date_sort_func),
+	(rhythmdb_query_model_within_limit):
+	* rhythmdb/rhythmdb-query-model.h:
+	* rhythmdb/rhythmdb-query-results.c:
+	(rhythmdb_query_results_query_complete):
+	* rhythmdb/rhythmdb-query-results.h:
+	* rhythmdb/rhythmdb-query.c: (rhythmdb_query_copy),
+	(rhythmdb_query_concatenate), (rhythmdb_query_parse_valist),
+	(rhythmdb_query_free), (rhythmdb_read_encoded_property),
+	(rhythmdb_query_serialize), (rhythmdb_query_deserialize),
+	(rhythmdb_query_preprocess), (rhythmdb_query_get_type):
+	* rhythmdb/rhythmdb-tree.c: (rhythmdb_tree_finalize),
+	(rhythmdb_tree_parser_start_element),
+	(rhythmdb_tree_parser_end_element), (rhythmdb_tree_load),
+	(save_entry), (save_entry_type), (save_unknown_entry_type),
+	(rhythmdb_tree_save), (rhythmdb_tree_entry_new),
+	(rhythmdb_tree_property_new), (get_genres_hash_for_type),
+	(get_or_create_genre), (remove_entry_from_album),
+	(rhythmdb_tree_entry_set), (rhythmdb_tree_entry_delete),
+	(remove_one_song), (rhythmdb_tree_entry_delete_by_type),
+	(search_match_properties), (evaluate_conjunctive_subquery),
+	(clone_remove_ptr_array_index), (conjunctive_query_albums),
+	(conjunctive_query_artists), (conjunctive_query_genre),
+	(conjunctive_query), (split_query_by_disjunctions),
+	(do_query_recurse), (rhythmdb_tree_entry_foreach),
+	(hash_tree_entries_foreach), (hash_tree_albums_foreach),
+	(hash_tree_artists_foreach), (hash_tree_genres_foreach),
+	(rhythmdb_hash_tree_foreach),
+	(rhythmdb_tree_entry_type_registered):
+	* rhythmdb/rhythmdb.c: (rhythmdb_class_init),
+	(metadata_field_from_prop), (extract_gtype_from_enum_entry),
+	(extract_nice_name_from_enum_entry), (rhythmdb_init),
+	(rhythmdb_execute_multi_stat_info_cb), (rhythmdb_event_free),
+	(rhythmdb_shutdown), (rhythmdb_finalize),
+	(rhythmdb_emit_entry_signals_idle), (process_added_entries_cb),
+	(rhythmdb_entry_insert), (rhythmdb_entry_new),
+	(rhythmdb_entry_example_new),
+	(set_metadata_string_default_unknown), (is_ghost_entry),
+	(rhythmdb_process_stat_event), (rhythmdb_add_import_error_entry),
+	(rhythmdb_process_metadata_load),
+	(rhythmdb_process_queued_entry_set_event),
+	(rhythmdb_process_events), (rhythmdb_execute_stat_info_cb),
+	(queue_stat_uri), (rhythmdb_entry_get), (entry_to_rb_metadata),
+	(rhythmdb_add_uri_with_type), (rhythmdb_load_thread_main),
+	(rhythmdb_load), (rhythmdb_save_thread_main), (rhythmdb_save),
+	(rhythmdb_entry_set), (rhythmdb_entry_set_internal),
+	(rhythmdb_entry_sync_mirrored), (rhythmdb_entry_delete),
+	(rhythmdb_entry_delete_by_type),
+	(rhythmdb_propid_from_nice_elt_name),
+	(rhythmdb_do_full_query_async_parsed), (rhythmdb_do_full_query),
+	(rhythmdb_compute_status_normal),
+	(rhythmdb_entry_register_type_alias),
+	(rhythmdb_entry_type_foreach), (song_can_sync_metadata),
+	(rhythmdb_entry_song_get_type), (rhythmdb_entry_ignore_get_type),
+	(rhythmdb_entry_import_error_get_type),
+	(rhythmdb_entry_podcast_post_get_type),
+	(rhythmdb_entry_podcast_feed_get_type),
+	(rhythmdb_entry_set_mount_point), (rhythmdb_entry_set_visibility),
+	(rhythmdb_sync_library_location), (rhythmdb_entry_get_string),
+	(rhythmdb_entry_get_ulong), (rhythmdb_entry_type_get_type):
+	* rhythmdb/rhythmdb.h:
+	* shell/main.c: (main), (load_uri_args), (handle_dbus_message):
+	* shell/rb-history.c: (rb_history_new), (rb_history_set_playing),
+	(rb_history_limit_size):
+	* shell/rb-history.h:
+	* shell/rb-play-order-linear-loop.c:
+	(rb_linear_play_order_loop_get_next):
+	* shell/rb-play-order-linear-loop.h:
+	* shell/rb-play-order-linear.c:
+	* shell/rb-play-order-linear.h:
+	* shell/rb-play-order-queue.c:
+	(rb_queue_play_order_playing_entry_removed):
+	* shell/rb-play-order-queue.h:
+	* shell/rb-play-order-random-by-age-and-rating.c:
+	* shell/rb-play-order-random-by-age-and-rating.h:
+	* shell/rb-play-order-random-by-age.c:
+	(rb_random_by_age_get_entry_weight):
+	* shell/rb-play-order-random-by-age.h:
+	* shell/rb-play-order-random-by-rating.c:
+	* shell/rb-play-order-random-by-rating.h:
+	* shell/rb-play-order-random-equal-weights.c:
+	* shell/rb-play-order-random-equal-weights.h:
+	* shell/rb-play-order-random.c: (rb_random_filter_history),
+	(rb_random_get_total_weight), (rb_random_play_order_get_next),
+	(rb_random_db_changed), (rb_random_playing_entry_changed),
+	(rb_random_db_entry_deleted):
+	* shell/rb-play-order-shuffle.c: (remove_from_history),
+	(add_randomly_to_history), (get_query_model_contents),
+	(rb_shuffle_playing_entry_changed):
+	* shell/rb-play-order-shuffle.h:
+	* shell/rb-play-order.c: (rb_play_order_class_init),
+	(rb_play_order_set_property),
+	(rb_play_order_playing_source_changed),
+	(rb_play_order_query_model_changed_cb),
+	(rb_play_order_query_model_changed),
+	(rb_play_order_entry_added_cb), (default_playing_entry_removed):
+	* shell/rb-play-order.h:
+	* shell/rb-playlist-manager.c: (rb_playlist_manager_class_init),
+	(rb_playlist_manager_init), (rb_playlist_manager_set_uimanager),
+	(rb_playlist_manager_set_property),
+	(rb_playlist_manager_parse_file),
+	(rb_playlist_manager_load_playlists),
+	(rb_playlist_manager_is_dirty), (rb_playlist_manager_save_data),
+	(rb_playlist_manager_save_playlists),
+	(rb_playlist_manager_new_playlist),
+	(rb_playlist_manager_new_playlist_from_selection_data),
+	(rb_playlist_manager_cmd_new_automatic_playlist),
+	(rb_playlist_manager_cmd_edit_automatic_playlist),
+	(_queue_track_cb), (rb_playlist_manager_cmd_delete_playlist),
+	(save_playlist_response_cb), (export_set_extension_cb),
+	(filter_get_export_filter_label), (setup_format_menu),
+	(rb_playlist_manager_cmd_save_playlist),
+	(rb_playlist_manager_get_playlists),
+	(rb_playlist_manager_get_playlist_names), (_get_playlist_by_name),
+	(rb_playlist_manager_delete_playlist),
+	(rb_playlist_manager_export_playlist):
+	* shell/rb-playlist-manager.h:
+	* shell/rb-removable-media-manager.c:
+	(rb_removable_media_manager_class_init),
+	(rb_removable_media_manager_dispose),
+	(rb_removable_media_manager_finalize),
+	(rb_removable_media_manager_set_property),
+	(split_drive_from_cdda_uri),
+	(rb_removable_media_manager_playing_uri_changed_cb),
+	(rb_removable_media_manager_load_media),
+	(rb_removable_media_manager_volume_mounted_cb),
+	(remove_volume_by_source),
+	(rb_removable_media_manager_source_deleted_cb),
+	(rb_removable_media_manager_volume_unmounted_cb),
+	(rb_removable_media_manager_mount_volume),
+	(rb_removable_media_manager_set_uimanager),
+	(rb_removable_media_manager_scan), (do_transfer),
+	(rb_removable_media_manager_cmd_copy_tracks):
+	* shell/rb-removable-media-manager.h:
+	* shell/rb-shell-clipboard.c: (rb_shell_clipboard_init),
+	(rb_shell_clipboard_finalize), (rb_shell_clipboard_constructor),
+	(rb_shell_clipboard_sync),
+	(rb_shell_clipboard_idle_poll_deletions),
+	(rb_shell_clipboard_cmd_add_to_playlist_new),
+	(rb_shell_clipboard_playlist_add_cb),
+	(rb_shell_clipboard_playlist_deleted_cb),
+	(rb_shell_clipboard_playlist_renamed_cb),
+	(rb_shell_clipboard_playlist_visible_cb),
+	(rb_shell_clipboard_playlist_added_cb):
+	* shell/rb-shell-player.c: (rb_shell_player_class_init),
+	(rb_shell_player_constructor), (volume_pre_unmount_cb),
+	(rb_shell_player_init), (rb_shell_player_set_property),
+	(rb_shell_player_new), (rb_shell_player_open_playlist_url),
+	(rb_shell_player_open_location),
+	(rb_shell_player_set_playing_entry),
+	(rb_shell_player_play_order_update_cb),
+	(rb_shell_player_jump_to_current), (rb_shell_player_do_previous),
+	(rb_shell_player_do_next), (rb_shell_player_do_previous_or_seek),
+	(rb_shell_player_cmd_previous), (rb_shell_player_cmd_next),
+	(rb_shell_player_cmd_play), (rb_shell_player_playpause),
+	(rb_shell_player_sync_volume), (rb_shell_player_sync_replaygain),
+	(gconf_song_position_slider_visibility_changed),
+	(rb_shell_player_entry_activated_cb),
+	(rb_shell_player_property_row_activated_cb),
+	(rb_shell_player_entry_changed_cb),
+	(rb_shell_player_sync_with_source), (rb_shell_player_sync_buttons),
+	(actually_set_playing_source),
+	(rb_shell_player_set_playing_source_internal),
+	(rb_shell_player_get_playing_song_duration), (eos_cb),
+	(rb_shell_player_error), (error_cb), (info_available_cb),
+	(grab_mmkey), (filter_mmkeys), (_idle_unblock_signal_cb),
+	(rb_shell_player_error_get_type):
+	* shell/rb-shell-player.h:
+	* shell/rb-shell-preferences.c: (rb_shell_preferences_init),
+	(rb_shell_preferences_append_page),
+	(share_check_button_toggled_cb),
+	(password_check_button_toggled_cb), (add_daap_preferences),
+	(rb_shell_preferences_column_check_changed_cb),
+	(rb_shell_preferences_sync_column_button),
+	(rb_shell_preferences_sync),
+	(rb_shell_preferences_browser_views_activated_cb):
+	* shell/rb-shell.c: (rb_shell_class_init), (rb_shell_init),
+	(rb_shell_set_property), (rb_shell_get_property),
+	(rb_shell_sync_state), (idle_save_rhythmdb), (rb_shell_finalize),
+	(construct_widgets), (construct_load_ui), (rb_shell_constructor),
+	(rb_shell_get_visibility), (rb_shell_set_visibility),
+	(rb_shell_sync_window_state), (rb_shell_db_entry_added_cb),
+	(rb_shell_register_entry_type_for_source),
+	(rb_shell_transfer_progress_cb), (rb_shell_playing_from_queue_cb),
+	(rb_shell_playing_entry_changed_cb), (rb_shell_select_source),
+	(rb_shell_player_stream_song_changed_cb),
+	(rb_shell_set_window_title),
+	(rb_shell_view_smalldisplay_changed_cb),
+	(rb_shell_view_queue_as_sidebar_changed_cb),
+	(rb_shell_cmd_plugins), (add_to_library_response_cb),
+	(rb_shell_cmd_add_folder_to_library),
+	(rb_shell_cmd_add_file_to_library),
+	(rb_shell_sync_pane_visibility), (rb_shell_sync_smalldisplay),
+	(sidepane_visibility_changed_cb), (toolbar_state_changed_cb),
+	(rb_shell_jump_to_entry_with_source), (tray_embedded_cb),
+	(session_die_cb), (save_yourself_cb), (rb_shell_session_init),
+	(handle_playlist_entry_cb), (rb_shell_load_uri),
+	(rb_shell_add_to_queue), (rb_shell_present),
+	(rb_shell_get_song_properties), (rb_shell_set_song_property),
+	(rb_shell_volume_widget_changed_cb),
+	(rb_shell_player_volume_changed_cb),
+	(rb_shell_ui_location_get_type):
+	* shell/rb-shell.h:
+	* shell/rb-source-header.c: (ui_manager_add_widget_cb),
+	(rb_source_header_init), (rb_source_header_set_source_internal),
+	(rb_source_state_sync), (rb_source_header_clear_search),
+	(rb_source_header_view_browser_changed_cb):
+	* shell/rb-source-header.h:
+	* shell/rb-statusbar.c: (rb_statusbar_construct),
+	(rb_statusbar_init), (rb_statusbar_finalize),
+	(rb_statusbar_set_property), (rb_statusbar_set_progress),
+	(rb_statusbar_source_status_changed_cb):
+	* shell/rb-statusbar.h:
+	* shell/rb-tray-icon.c: (rb_tray_icon_init),
+	(rb_tray_icon_constructor), (rb_tray_icon_finalize),
+	(rb_tray_icon_set_property), (rb_tray_icon_show_window_changed_cb),
+	(rb_tray_icon_get_geom), (rb_tray_icon_notify):
+	* sources/rb-audiocd-source.c: (rb_audiocd_source_constructor),
+	(rb_audiocd_create_track_entry):
+	* sources/rb-auto-playlist-source.c:
+	(rb_auto_playlist_source_class_init),
+	(rb_auto_playlist_source_constructor),
+	(rb_auto_playlist_source_new_from_xml), (impl_reset_filters),
+	(impl_search), (impl_receive_drag), (impl_save_contents_to_xml),
+	(rb_auto_playlist_source_query_complete_cb),
+	(rb_auto_playlist_source_do_query),
+	(rb_auto_playlist_source_set_query),
+	(rb_auto_playlist_source_browser_changed_cb),
+	(search_action_to_prop):
+	* sources/rb-auto-playlist-source.h:
+	* sources/rb-browser-source.c: (rb_browser_source_init),
+	(rb_browser_source_dispose), (search_action_to_prop),
+	(rb_browser_source_constructor),
+	(rb_browser_source_cmd_choose_genre),
+	(rb_browser_source_cmd_choose_artist),
+	(rb_browser_source_cmd_choose_album), (impl_search),
+	(rb_browser_source_browser_changed_cb),
+	(rb_browser_source_do_query):
+	* sources/rb-browser-source.h:
+	* sources/rb-daap-source.c: (rb_daap_source_class_init),
+	(rb_daap_source_init), (rb_daap_source_dispose),
+	(rb_daap_source_set_property), (start_browsing),
+	(rb_daap_sources_init), (rb_daap_sources_shutdown),
+	(rb_daap_source_connection_cb), (rb_daap_source_activate),
+	(rb_daap_source_cmd_disconnect), (rb_daap_source_find_for_uri),
+	(rb_daap_source_get_headers), (rb_daap_source_get_status):
+	* sources/rb-daap-source.h:
+	* sources/rb-import-errors-source.h:
+	* sources/rb-ipod-source.c: (rb_ipod_source_name_changed_cb),
+	(rb_ipod_source_init), (ipod_path_to_uri), (add_rb_playlist),
+	(add_ipod_song_to_db), (load_ipod_db_idle_cb),
+	(rb_ipod_load_songs), (rb_ipod_get_itunesdb_path),
+	(rb_ipod_is_volume_ipod), (hal_udi_is_ipod), (impl_get_ui_actions),
+	(impl_move_to_trash), (impl_receive_drag), (test_dir_on_ipod),
+	(ipod_mkdir_with_parents), (build_ipod_dir_name),
+	(generate_ipod_filename), (ipod_path_from_unix_path),
+	(impl_delete_thyself):
+	* sources/rb-iradio-source.c: (rb_iradio_source_class_init),
+	(rb_iradio_source_init), (rb_iradio_source_constructor),
+	(rb_iradio_source_new), (guess_uri_scheme),
+	(rb_iradio_source_add_station),
+	(rb_iradio_source_async_update_play_statistics),
+	(genre_selection_reset_cb), (rb_iradio_source_do_query),
+	(stations_view_drag_data_received_cb),
+	(rb_iradio_source_cmd_new_station):
+	* sources/rb-iradio-source.h:
+	* sources/rb-library-source.c: (rb_library_source_dispose),
+	(rb_library_source_constructor),
+	(rb_library_source_location_button_clicked_cb),
+	(impl_get_config_widget), (rb_library_source_library_location_cb),
+	(sanitize_path), (filepath_parse_pattern),
+	(layout_example_label_update),
+	(rb_library_source_layout_filename_changed), (build_filename),
+	(impl_can_paste), (impl_paste),
+	(rb_library_source_add_child_source),
+	(rb_library_source_sync_child_sources):
+	* sources/rb-library-source.h:
+	* sources/rb-missing-files-source.h:
+	* sources/rb-play-queue-source.c:
+	(rb_play_queue_source_constructor), (impl_show_entry_view_popup):
+	* sources/rb-play-queue-source.h:
+	* sources/rb-playlist-source-recorder.c:
+	(rb_playlist_source_recorder_class_init), (update_speed_combobox),
+	(_nautilus_burn_drive_eject), (burn_cd), (ask_rewrite_disc),
+	(rb_playlist_source_recorder_init),
+	(rb_playlist_source_recorder_new):
+	* sources/rb-playlist-source.c: (rb_playlist_source_constructor),
+	(rb_playlist_source_save_playlist),
+	(rb_playlist_source_entry_added_cb),
+	(rb_playlist_source_set_query_model),
+	(rb_playlist_source_add_to_map):
+	* sources/rb-podcast-source.c: (rb_podcast_source_class_init),
+	(rb_podcast_source_init), (rb_podcast_source_dispose),
+	(rb_podcast_source_finalize), (search_action_to_prop),
+	(rb_podcast_source_constructor), (rb_podcast_source_set_property),
+	(rb_podcast_source_get_property), (rb_podcast_source_new),
+	(impl_delete), (rb_podcast_source_songs_show_popup_cb),
+	(rb_podcast_source_feeds_show_popup_cb), (feed_select_change_cb),
+	(rb_podcast_source_show_browser), (construct_query_from_selection),
+	(rb_podcast_source_do_query), (impl_get_config_widget),
+	(rb_podcast_source_btn_file_change_cb),
+	(posts_view_drag_data_received_cb),
+	(rb_podcast_source_cmd_download_post),
+	(rb_podcast_source_cmd_cancel_download),
+	(rb_podcast_source_cmd_delete_feed),
+	(rb_podcast_source_cmd_properties_feed),
+	(rb_podcast_source_cmd_update_feed),
+	(rb_podcast_source_post_status_cell_data_func),
+	(rb_podcast_source_post_feed_cell_data_func),
+	(rb_podcast_source_post_date_cell_data_func),
+	(rb_podcast_source_load_finish_cb), (impl_receive_drag),
+	(rb_podcast_source_entry_activated_cb), (impl_can_add_to_queue),
+	(impl_add_to_queue), (rb_podcast_source_cmd_new_podcast),
+	(impl_get_status):
+	* sources/rb-podcast-source.h:
+	* sources/rb-removable-media-source.c:
+	(rb_removable_media_source_constructor):
+	* sources/rb-removable-media-source.h:
+	* sources/rb-source.h:
+	* sources/rb-sourcelist-model.c: (rb_sourcelist_model_class_init),
+	(rb_sourcelist_model_new), (rb_sourcelist_model_is_row_visible),
+	(rb_sourcelist_model_row_is_separator),
+	(rb_sourcelist_model_drag_data_received),
+	(rb_sourcelist_model_row_drop_possible), (path_is_droppable),
+	(rb_sourcelist_model_row_drop_position),
+	(rb_sourcelist_model_get_drag_target),
+	(rb_sourcelist_model_row_draggable),
+	(rb_sourcelist_model_drag_data_get),
+	(rb_sourcelist_model_row_inserted_cb),
+	(rb_sourcelist_model_get_group_path):
+	* sources/rb-sourcelist.c: (rb_sourcelist_append),
+	(match_source_to_iter), (rb_sourcelist_source_to_iter),
+	(rb_sourcelist_visible_source_to_iter),
+	(rb_sourcelist_edit_source_name),
+	(rb_sourcelist_selection_changed_cb), (button_press_cb),
+	(key_release_cb), (name_notify_cb), (icon_notify_cb),
+	(rb_sourcelist_title_cell_data_func), (source_name_edited_cb):
+	* sources/rb-static-playlist-source.c:
+	(rb_static_playlist_source_class_init),
+	(rb_static_playlist_source_constructor),
+	(rb_static_playlist_source_load_from_xml), (impl_reset_filters),
+	(impl_search), (rb_static_playlist_source_do_query),
+	(rb_static_playlist_source_browser_changed_cb),
+	(impl_receive_drag), (impl_save_contents_to_xml),
+	(rb_static_playlist_source_add_location_swapped),
+	(search_action_to_prop):
+	* sources/rb-static-playlist-source.h:
+	* widgets/bacon-volume.c: (bacon_volume_button_get_type):
+	* widgets/eggtrayicon.c: (egg_tray_icon_init),
+	(egg_tray_icon_get_orientation_property),
+	(egg_tray_icon_send_manager_message),
+	(egg_tray_icon_update_manager_window),
+	(egg_tray_icon_manager_window_destroyed), (egg_tray_icon_realize),
+	(egg_tray_icon_send_message), (egg_tray_icon_notify):
+	* widgets/eggtrayicon.h:
+	* widgets/rb-cell-renderer-pixbuf.c:
+	(rb_cell_renderer_pixbuf_get_property),
+	(rb_cell_renderer_pixbuf_set_property),
+	(rb_cell_renderer_pixbuf_get_size),
+	(rb_cell_renderer_pixbuf_render),
+	(rb_cell_renderer_pixbuf_activate):
+	* widgets/rb-cell-renderer-rating.c:
+	(rb_cell_renderer_rating_class_init),
+	(rb_cell_renderer_rating_get_property),
+	(rb_cell_renderer_rating_set_property),
+	(rb_cell_renderer_rating_get_size),
+	(rb_cell_renderer_rating_render),
+	(rb_cell_renderer_rating_activate):
+	* widgets/rb-dialog.c:
+	* widgets/rb-dialog.h:
+	* widgets/rb-druid.c: (rb_druid_init_widgets), (rb_druid_new),
+	(path_dialog_response_cb), (idle_set_sensitive), (do_response),
+	(rb_druid_page3_finish_cb):
+	* widgets/rb-entry-view.c: (rb_entry_view_class_init),
+	(rb_entry_view_init), (rb_entry_view_set_property),
+	(rb_entry_view_new), (rb_entry_view_play_count_cell_data_func),
+	(rb_entry_view_year_cell_data_func), (rb_entry_view_sync_sorting),
+	(rb_entry_view_get_sorting_type), (rb_entry_view_set_sorting_type),
+	(rb_entry_view_set_sorting_order),
+	(rb_entry_view_column_clicked_cb), (rb_entry_view_append_column),
+	(rb_entry_view_set_columns_clickable), (rb_entry_view_constructor),
+	(rb_entry_view_playing_song_changed),
+	(rb_entry_view_button_press_cb), (rb_entry_view_rows_reordered_cb),
+	(rb_entry_view_scroll_to_entry), (set_column_visibility),
+	(rb_entry_view_set_fixed_column_width),
+	(rb_entry_view_get_time_date_column_sample),
+	(rb_entry_view_state_get_type):
+	* widgets/rb-entry-view.h:
+	* widgets/rb-header.c: (rb_header_init), (rb_header_set_property),
+	(rb_header_sync), (slider_moved_timeout), (slider_moved_callback),
+	(changed_idle_callback), (rb_header_elapsed_changed_cb):
+	* widgets/rb-library-browser.c: (rb_library_browser_constructor),
+	(update_browser_property_visibility),
@@ -14125 +14125 @@
-2006-07-12  William Jon McCann  <mccann@jhu.edu>
+2006-07-12  William Jon McCan  <mccann@jhu.edu>
@@ -14262 +14262 @@
-2006-07-09  William Jon McCann  <mccann@jhu.edu>
+2006-07-09  William Jon McCan  <mccann@jhu.edu>
@@ -14293 +14293 @@
-	* shell/rb-shell.c: remove some ununsed gnomeui includes
+	* shell/rb-shell.c: remove some unused gnomeui includes
@@ -14298 +14298 @@
-	since it isn't acutally used anywhere. Fixes #346926
+	since it isn't actually used anywhere. Fixes #346926
@@ -14335 +14335 @@
-2006-07-08  William Jon McCann  <mccann@jhu.edu>
+2006-07-08  William Jon McCan  <mccann@jhu.edu>
@@ -14646 +14646 @@
-	(rhythmdb_query_model_drag_data_received): Make drag-and-drop withing
+	(rhythmdb_query_model_drag_data_received): Make drag-and-drop within
@@ -14685 +14685 @@
-	non-library tracks, as we don't supprot it yet. From #345248.
+	non-library tracks, as we don't support it yet. From #345248.
@@ -14980 +14980 @@
-2006-06-15  William Jon McCann  <mccann@jhu.edu>
+2006-06-15  William Jon McCan  <mccann@jhu.edu>
@@ -14992 +14992 @@
-2006-06-13  William Jon McCann  <mccann@jhu.edu>
+2006-06-13  William Jon McCan  <mccann@jhu.edu>
@@ -15188 +15188 @@
-	next visible row is a source.  Make persistant sources (playlists) and
+	next visible row is a source.  Make persistent sources (playlists) and
@@ -15304 +15304 @@
-2006-06-02  William Jon McCann  <mccann@jhu.edu>
+2006-06-02  William Jon McCan  <mccann@jhu.edu>
@@ -15319 +15319 @@
-2006-05-30  William Jon McCann  <mccann@jhu.edu>
+2006-05-30  William Jon McCan  <mccann@jhu.edu>
@@ -15353 +15353 @@
-	"suceeds" without transferring any data.
+	"succeeds" without transferring any data.
@@ -15554 +15554 @@
-2006-05-24  William Jon McCann  <mccann@jhu.edu>
+2006-05-24  William Jon McCan  <mccann@jhu.edu>
@@ -15573 +15573 @@
-2006-05-24  William Jon McCann  <mccann@jhu.edu>
+2006-05-24  William Jon McCan  <mccann@jhu.edu>
@@ -15581 +15581 @@
-2006-05-24  William Jon McCann  <mccann@jhu.edu>
+2006-05-24  William Jon McCan  <mccann@jhu.edu>
@@ -15588 +15588 @@
-2006-05-24  William Jon McCann  <mccann@jhu.edu>
+2006-05-24  William Jon McCan  <mccann@jhu.edu>
@@ -15754 +15754 @@
-2006-05-19  William Jon McCann  <mccann@jhu.edu>
+2006-05-19  William Jon McCan  <mccann@jhu.edu>
@@ -15766 +15766 @@
-2006-05-19  William Jon McCann  <mccann@jhu.edu>
+2006-05-19  William Jon McCan  <mccann@jhu.edu>
@@ -15809 +15809 @@
-2006-05-17  William Jon McCann  <mccann@jhu.edu>
+2006-05-17  William Jon McCan  <mccann@jhu.edu>
@@ -15930 +15930 @@
-2006-05-15  William Jon McCann  <mccann@jhu.edu>
+2006-05-15  William Jon McCan  <mccann@jhu.edu>
@@ -16069 +16069 @@
-2006-05-12  William Jon McCann  <mccann@jhu.edu>
+2006-05-12  William Jon McCan  <mccann@jhu.edu>
@@ -16080 +16080 @@
-2006-05-12  William Jon McCann  <mccann@jhu.edu>
+2006-05-12  William Jon McCan  <mccann@jhu.edu>
@@ -16143 +16143 @@
-	inital values, because some code paths may not set them before we use
+	initial values, because some code paths may not set them before we use
@@ -16149 +16149 @@
-2006-05-10  William Jon McCann  <mccann@jhu.edu>
+2006-05-10  William Jon McCan  <mccann@jhu.edu>
@@ -16452 +16452 @@
-2006-05-01  William Jon McCann  <mccann@jhu.edu>
+2006-05-01  William Jon McCan  <mccann@jhu.edu>
@@ -16462 +16462 @@
-	William Jon McCann  <mccann@jhu.edu>
+	William Jon McCan  <mccann@jhu.edu>
@@ -16527 +16527 @@
-2006-04-26  William Jon McCann  <mccann@jhu.edu>
+2006-04-26  William Jon McCan  <mccann@jhu.edu>
@@ -16612 +16612 @@
-2006-04-25  William Jon McCann  <mccann@jhu.edu>
+2006-04-25  William Jon McCan  <mccann@jhu.edu>
@@ -16619 +16619 @@
-2006-04-25  William Jon McCann  <mccann@jhu.edu>
+2006-04-25  William Jon McCan  <mccann@jhu.edu>
@@ -16627 +16627 @@
-2006-04-25  William Jon McCann  <mccann@jhu.edu>
+2006-04-25  William Jon McCan  <mccann@jhu.edu>
@@ -16671 +16671 @@
-	nonexistant (so far) 'last.fm streaming' plugin.
+	nonexistent (so far) 'last.fm streaming' plugin.
@@ -17498 +17498 @@
-2006-04-14  William Jon McCann  <mccann@jhu.edu>
+2006-04-14  William Jon McCan  <mccann@jhu.edu>
@@ -17567 +17567 @@
-2006-04-13  William Jon McCann  <mccann@jhu.edu>
+2006-04-13  William Jon McCan  <mccann@jhu.edu>
@@ -17618 +17618 @@
-2006-04-10  William Jon McCann  <mccann@jhu.edu>
+2006-04-10  William Jon McCan  <mccann@jhu.edu>
@@ -17627 +17627 @@
-2006-04-10  William Jon McCann  <mccann@jhu.edu>
+2006-04-10  William Jon McCan  <mccann@jhu.edu>
@@ -17889 +17889 @@
-2006-04-05  William Jon McCann  <mccann@jhu.edu>
+2006-04-05  William Jon McCan  <mccann@jhu.edu>
@@ -17900 +17900 @@
-	Patch by: William Jon McCann  <mccann@jhu.edu>
+	Patch by: William Jon McCan  <mccann@jhu.edu>
@@ -17906 +17906 @@
-2006-04-04  William Jon McCann  <mccann@jhu.edu>
+2006-04-04  William Jon McCan  <mccann@jhu.edu>
@@ -18294 +18294 @@
-	cause some widgets to be resized after we had explicity set theri
+	cause some widgets to be resized after we had explicitly set theri
@@ -18310 +18310 @@
-	(rb_plugins_engine_init), (rb_plugins_engine_shutdown): run gabage
+	(rb_plugins_engine_init), (rb_plugins_engine_shutdown): run garbage
@@ -18367 +18367 @@
-	(actually_set_playing_source): update the next/previous availablility
+	(actually_set_playing_source): update the next/previous availability
@@ -18378 +18378 @@
-	* metadata/Makefile.am: make the metdata helper build when linking
+	* metadata/Makefile.am: make the metadata helper build when linking
@@ -18639 +18639 @@
-2006-03-16  William Jon McCann  <mccann@jhu.edu>
+2006-03-16  William Jon McCan  <mccann@jhu.edu>
@@ -18665 +18665 @@
-2006-03-16  William Jon McCann  <mccann@jhu.edu>
+2006-03-16  William Jon McCan  <mccann@jhu.edu>
@@ -18712 +18712 @@
-2006-03-14  William Jon McCann  <mccann@jhu.edu>
+2006-03-14  William Jon McCan  <mccann@jhu.edu>
@@ -18718 +18718 @@
-2006-03-14  William Jon McCann  <mccann@jhu.edu>
+2006-03-14  William Jon McCan  <mccann@jhu.edu>
@@ -18723 +18723 @@
-2006-03-14  William Jon McCann  <mccann@jhu.edu>
+2006-03-14  William Jon McCan  <mccann@jhu.edu>
@@ -18728 +18728 @@
-2006-03-14  William Jon McCann  <mccann@jhu.edu>
+2006-03-14  William Jon McCan  <mccann@jhu.edu>
@@ -18868 +18868 @@
-2006-03-12  William Jon McCann  <mccann@jhu.edu>
+2006-03-12  William Jon McCan  <mccann@jhu.edu>
@@ -19367 +19367 @@
-	criteria, as it's a silly effifiency degredation.
+	criteria, as it's a silly effifiency degradation.
@@ -19412 +19412 @@
-	COPY action for draging sources and tracks, not MOVE as well. Stops
+	COPY action for dragging sources and tracks, not MOVE as well. Stops
@@ -19946 +19946 @@
-2006-02-17  William Jon McCann  <mccann@jhu.edu>
+2006-02-17  William Jon McCan  <mccann@jhu.edu>
@@ -19953 +19953 @@
-2006-02-17  William Jon McCann  <mccann@jhu.edu>
+2006-02-17  William Jon McCan  <mccann@jhu.edu>
@@ -20330 +20330 @@
-2006-02-09  William Jon McCann  <mccann@jhu.edu>
+2006-02-09  William Jon McCan  <mccann@jhu.edu>
@@ -20391 +20391 @@
-2006-02-08  William Jon McCann  <mccann@jhu.edu>
+2006-02-08  William Jon McCan  <mccann@jhu.edu>
@@ -20397 +20397 @@
-2006-02-08  William Jon McCann  <mccann@jhu.edu>
+2006-02-08  William Jon McCan  <mccann@jhu.edu>
@@ -20402 +20402 @@
-2006-02-08  William Jon McCann  <mccann@jhu.edu>
+2006-02-08  William Jon McCan  <mccann@jhu.edu>
@@ -20473 +20473 @@
-2006-02-07  William Jon McCann  <mccann@jhu.edu>
+2006-02-07  William Jon McCan  <mccann@jhu.edu>
@@ -20710 +20710 @@
-2006-02-03  William Jon McCann  <mccann@jhu.edu>
+2006-02-03  William Jon McCan  <mccann@jhu.edu>
@@ -20909 +20909 @@
-	you explicity request a particular playback engine, and it can't be
+	you explicitly request a particular playback engine, and it can't be
@@ -20966 +20966 @@
-	/should/ now work, if the neccessary plugins get ported.
+	/should/ now work, if the necessary plugins get ported.
@@ -21077 +21077 @@
-	patch by: William Jon McCann  <mccann@jhu.edu>
+	patch by: William Jon McCan  <mccann@jhu.edu>
@@ -21132 +21132 @@
-2006-01-26  William Jon McCann  <mccann@jhu.edu>
+2006-01-26  William Jon McCan  <mccann@jhu.edu>
@@ -21145 +21145 @@
-2006-01-25  William Jon McCann  <mccann@jhu.edu>
+2006-01-25  William Jon McCan  <mccann@jhu.edu>
@@ -21247 +21247 @@
-2006-01-20  William Jon McCann  <mccann@jhu.edu>
+2006-01-20  William Jon McCan  <mccann@jhu.edu>
@@ -21305 +21305 @@
-2006-01-17  William Jon McCann  <mccann@jhu.edu>
+2006-01-17  William Jon McCan  <mccann@jhu.edu>
@@ -21331 +21331 @@
-	dragging to an emoty playlist.
+	dragging to an empty playlist.
@@ -21381 +21381 @@
-2006-01-16  William Jon McCann  <mccann@jhu.edu>
+2006-01-16  William Jon McCan  <mccann@jhu.edu>
@@ -21386 +21386 @@
-2006-01-16  William Jon McCann  <mccann@jhu.edu>
+2006-01-16  William Jon McCan  <mccann@jhu.edu>
@@ -21437 +21437 @@
-	patch by: William Jon McCann  <mccann@jhu.edu>
+	patch by: William Jon McCan  <mccann@jhu.edu>
@@ -21506 +21506 @@
-	patch by: William Jon McCann  <mccann@jhu.edu>
+	patch by: William Jon McCan  <mccann@jhu.edu>
@@ -21524 +21524 @@
-2006-01-14  William Jon McCann  <mccann@jhu.edu>
+2006-01-14  William Jon McCan  <mccann@jhu.edu>
@@ -21549 +21549 @@
-2006-01-13  William Jon McCann  <mccann@jhu.edu>
+2006-01-13  William Jon McCan  <mccann@jhu.edu>
@@ -21555 +21555 @@
-2006-01-13  William Jon McCann  <mccann@jhu.edu>
+2006-01-13  William Jon McCan  <mccann@jhu.edu>
@@ -21634 +21634 @@
-2006-01-10  William Jon McCann  <mccann@jhu.edu>
+2006-01-10  William Jon McCan  <mccann@jhu.edu>
@@ -21640 +21640 @@
-2006-01-10  William Jon McCann  <mccann@jhu.edu>
+2006-01-10  William Jon McCan  <mccann@jhu.edu>
@@ -21694 +21694 @@
-2006-01-07  William Jon McCann  <mccann@jhu.edu>
+2006-01-07  William Jon McCan  <mccann@jhu.edu>
@@ -21702 +21702 @@
-2006-01-07  William Jon McCann  <mccann@jhu.edu>
+2006-01-07  William Jon McCan  <mccann@jhu.edu>
@@ -21709 +21709 @@
-2006-01-07  William Jon McCann  <mccann@jhu.edu>
+2006-01-07  William Jon McCan  <mccann@jhu.edu>
@@ -21808 +21808 @@
-2006-01-05  William Jon McCann  <mccann@jhu.edu>
+2006-01-05  William Jon McCan  <mccann@jhu.edu>
@@ -21899 +21899 @@
-2006-01-04  William Jon McCann  <mccann@jhu.edu>
+2006-01-04  William Jon McCan  <mccann@jhu.edu>
@@ -21932 +21932 @@
-2006-01-04  William Jon McCann  <mccann@jhu.edu>
+2006-01-04  William Jon McCan  <mccann@jhu.edu>
@@ -22062 +22062 @@
-2005-12-29  William Jon McCann  <mccann@jhu.edu>
+2005-12-29  William Jon McCan  <mccann@jhu.edu>
@@ -22128 +22128 @@
-2005-12-19  William Jon McCann  <mccann@jhu.edu>
+2005-12-19  William Jon McCan  <mccann@jhu.edu>
@@ -22171 +22171 @@
-2005-12-15  William Jon McCann  <mccann@jhu.edu>
+2005-12-15  William Jon McCan  <mccann@jhu.edu>
@@ -22180 +22180 @@
-2005-12-14  William Jon McCann  <mccann@jhu.edu>
+2005-12-14  William Jon McCan  <mccann@jhu.edu>
@@ -22206 +22206 @@
-2005-12-12  William Jon McCann  <mccann@jhu.edu>
+2005-12-12  William Jon McCan  <mccann@jhu.edu>
@@ -22224 +22224 @@
-2005-12-12  William Jon McCann  <mccann@jhu.edu>
+2005-12-12  William Jon McCan  <mccann@jhu.edu>
@@ -22227,2 +22227,2 @@
-	(rb_set_item_value, rb_insert_item, rb_validate_channel_propert) 
-	(rb_validate_item_propert, rb_podcast_parser_start_element) 
+	(rb_set_item_value, rb_insert_item, rb_validate_channel_property) 
+	(rb_validate_item_property, rb_podcast_parser_start_element) 
@@ -22260 +22260 @@
-	* sources/rb-source.h: seperate the enabling of browsers from the use
+	* sources/rb-source.h: separate the enabling of browsers from the use
@@ -22263 +22263 @@
-2005-12-11  William Jon McCann  <mccann@jhu.edu>
+2005-12-11  William Jon McCan  <mccann@jhu.edu>
@@ -22292 +22292 @@
-2005-12-10  William Jon McCann  <mccann@jhu.edu>
+2005-12-10  William Jon McCan  <mccann@jhu.edu>
@@ -22315 +22315 @@
-2005-12-10  William Jon McCann  <mccann@jhu.edu>
+2005-12-10  William Jon McCan  <mccann@jhu.edu>
@@ -22659 +22659 @@
-2005-12-09  William Jon McCann  <mccann@jhu.edu>
+2005-12-09  William Jon McCan  <mccann@jhu.edu>
@@ -22666 +22666 @@
-2005-12-09  William Jon McCann  <mccann@jhu.edu>
+2005-12-09  William Jon McCan  <mccann@jhu.edu>
@@ -22702 +22702 @@
-2005-12-09  William Jon McCann  <mccann@jhu.edu>
+2005-12-09  William Jon McCan  <mccann@jhu.edu>
@@ -23027 +23027 @@
-2005-12-05  William Jon McCann  <mccann@jhu.edu>
+2005-12-05  William Jon McCan  <mccann@jhu.edu>
@@ -23089 +23089 @@
-	          William Jon McCann  <mccann@jhu.edu>
+	          William Jon McCan  <mccann@jhu.edu>
@@ -23287 +23287 @@
-	"preferences" property, so that sources can acccess it. This is needed
+	"preferences" property, so that sources can access it. This is needed
@@ -23306 +23306 @@
-2005-12-01  William Jon McCann  <mccann@jhu.edu>
+2005-12-01  William Jon McCan  <mccann@jhu.edu>
@@ -23314 +23314 @@
-2005-12-01  William Jon McCann  <mccann@jhu.edu>
+2005-12-01  William Jon McCan  <mccann@jhu.edu>
@@ -23348 +23348 @@
-2005-11-30  William Jon McCann  <mccann@jhu.edu>
+2005-11-30  William Jon McCan  <mccann@jhu.edu>
@@ -23402 +23402 @@
-	patch by: William Jon McCann <mccann@jhu.edu> to use
+	patch by: William Jon McCan <mccann@jhu.edu> to use
@@ -23495 +23495 @@
-	patch by: William Jon McCann <mccann@jhu.edu>
+	patch by: William Jon McCan <mccann@jhu.edu>
@@ -23533 +23533 @@
-2005-11-18  William Jon McCann  <mccann@jhu.edu>
+2005-11-18  William Jon McCan  <mccann@jhu.edu>
@@ -23616 +23616 @@
-	Disable saving, renaming and delting for DAAP playlists.
+	Disable saving, renaming and deleting for DAAP playlists.
@@ -23672 +23672 @@
-	have large ReplayGain values will recieve no increase because they are
+	have large ReplayGain values will receive no increase because they are
@@ -23835 +23835 @@
-	consistantly and steal a trick from Totem for _NETSCAPE_URL drops.
+	consistently and steal a trick from Totem for _NETSCAPE_URL drops.
@@ -23958 +23958 @@
-2005-11-17  William Jon McCann  <mccann@jhu.edu>
+2005-11-17  William Jon McCan  <mccann@jhu.edu>
@@ -24069 +24069 @@
-2005-11-16  William Jon McCann  <mccann@jhu.edu>
+2005-11-16  William Jon McCan  <mccann@jhu.edu>
@@ -24592 +24592 @@
-	"Year" colums
+	"Year" columns
@@ -24698 +24698 @@
-	soon as any data is recieved
+	soon as any data is received
@@ -24741 +24741 @@
-	Move nautilus-cd-burner from optional to required depenency.
+	Move nautilus-cd-burner from optional to required dependency.
@@ -24790 +24790 @@
-	(rb_set_item_value), (rb_validate_item_propert),
+	(rb_set_item_value), (rb_validate_item_property),
@@ -25113 +25113 @@
-	(rb_set_item_value), (rb_insert_item), (rb_validate_item_propert),
+	(rb_set_item_value), (rb_insert_item), (rb_validate_item_property),
@@ -25126 +25126 @@
-	people weren't seing the percentages in the stats column.
+	people weren't seeing the percentages in the stats column.
@@ -25955 +25955 @@
-	Patch from William Jon McCann <mccann@jhu.edu>
+	Patch from William Jon McCan <mccann@jhu.edu>
@@ -26144 +26144 @@
-	HIG compliancy & images.
+	HIG compliance & images.
@@ -26148 +26148 @@
-	Requries avahi 0.5.  Still doesn't work quite right with Howl, due to 
+	Requires avahi 0.5.  Still doesn't work quite right with Howl, due to 
@@ -26336 +26336 @@
-	* shell/rb-shell-prefernces.c: Music sharing preferences.
+	* shell/rb-shell-preferences.c: Music sharing preferences.
@@ -26374 +26374 @@
-	* configure.ac: Fix sytnax error.
+	* configure.ac: Fix syntax error.
@@ -26457 +26457 @@
-	(rb_shell_toggle_visibility): Nwe function.
+	(rb_shell_toggle_visibility): New function.
--- ./ChangeLog.old	original
+++ ./ChangeLog.old	fixed
@@ -1941 +1941 @@
-    With this commit, the first pass at RhythmDB is commited. 
+    With this commit, the first pass at RhythmDB is committed. 
@@ -2658 +2658 @@
-      add missing file to dist, from William Jon McCann <mccannwj@pha.jhu.edu>
+      add missing file to dist, from William Jon McCan <mccannwj@pha.jhu.edu>
@@ -2662 +2662 @@
-    add missing file to dist, from William Jon McCann <mccannwj@pha.jhu.edu>
+    add missing file to dist, from William Jon McCan <mccannwj@pha.jhu.edu>
@@ -2672 +2672 @@
-      spec file fixes from William Jon McCann <mccannwj@pha.jhu.edu>
+      spec file fixes from William Jon McCan <mccannwj@pha.jhu.edu>
@@ -2676 +2676 @@
-    spec file fixes from William Jon McCann <mccannwj@pha.jhu.edu>
+    spec file fixes from William Jon McCan <mccannwj@pha.jhu.edu>
@@ -2750,6 +2750,6 @@
-2003-09-10  William Jon McCann  <mccann@jhu.edu>
- 
-	* lib/widgets/Makefile.am (librbwidgets_la_SOURCES):
- 	Added missing file.
- 
-2003-09-10  William Jon McCann  <mccann@jhu.edu>
+2003-09-10  William Jon McCan  <mccann@jhu.edu>
+ 
+	* lib/widgets/Makefile.am (librbwidgets_la_SOURCES):
+ 	Added missing file.
+ 
+2003-09-10  William Jon McCan  <mccann@jhu.edu>
@@ -3524 +3524 @@
-       remove cruft accidentally commited in previous cset
+       remove cruft accidentally committed in previous cset
@@ -4013 +4013 @@
-2003-08-24  William Jon McCann  <mccann@jhu.edu>
+2003-08-24  William Jon McCan  <mccann@jhu.edu>
@@ -4054 +4054 @@
-2003-08-20  William Jon McCann  <mccann@jhu.edu>
+2003-08-20  William Jon McCan  <mccann@jhu.edu>
@@ -4522 +4522 @@
-2003-08-15  William Jon McCann  <mccann@jhu.edu>
+2003-08-15  William Jon McCan  <mccann@jhu.edu>
@@ -4705 +4705 @@
-2003-08-13  William Jon McCann  <mccann@jhu.edu>
+2003-08-13  William Jon McCan  <mccann@jhu.edu>
@@ -4775 +4775 @@
-	Cast return value to a long to avoid complier warning.
+	Cast return value to a long to avoid compiler warning.
@@ -4824 +4824 @@
-	Wait a half second after updating a file during the intial load.
+	Wait a half second after updating a file during the initial load.
@@ -5010 +5010 @@
-	HIG-compliant, removed trailing spaces from strings where neccessary.
+	HIG-compliant, removed trailing spaces from strings where necessary.
@@ -5057 +5057 @@
-	(egg_tree_model_filter_update_childs), (bsearch_elt_with_offset),
+	(egg_tree_model_filter_update_children), (bsearch_elt_with_offset),
@@ -5449 +5449 @@
-	to accomodate for GStreamer startup lag.
+	to accommodate for GStreamer startup lag.
@@ -7531 +7531 @@
-	(egg_tree_model_filter_update_childs),
+	(egg_tree_model_filter_update_children),
@@ -7938 +7938 @@
-	new one, that fixes the stutterring when changing songs
+	new one, that fixes the stuttering when changing songs
@@ -8411 +8411 @@
-	* data/Makefile.am: Add iradio-inital.xml.
+	* data/Makefile.am: Add iradio-initial.xml.
@@ -8812 +8812 @@
-        * views/rb-audiocd-view.c: A little errror
+        * views/rb-audiocd-view.c: A little error
@@ -9586 +9586 @@
-	HIG-compliancy fixes.
+	HIG-compliance fixes.
@@ -10427 +10427 @@
-	Use an array of properties isntead of a hashtable, may
+	Use an array of properties instead of a hashtable, may
@@ -11310 +11310 @@
-	Check for file existance when loading from XML.
+	Check for file existence when loading from XML.
@@ -11601 +11601 @@
-	No dialog telling the user registartion failed,
+	No dialog telling the user registration failed,
@@ -11865 +11865 @@
-	Commiting what i have so far of the new library, only manual add is
+	Committing what i have so far of the new library, only manual add is
@@ -12240 +12240 @@
-	--no-registartion option, so you can run multiple rbs at the same time
+	--no-registration option, so you can run multiple rbs at the same time
@@ -13604 +13604 @@
-	* playlist/songs-view.c: "9 of 10" songs isntead of "9/10"
+	* playlist/songs-view.c: "9 of 10" songs instead of "9/10"
@@ -13752 +13752 @@
-	cuased shutdown warning
+	caused shutdown warning
@@ -14050 +14050 @@
-	* playlist/library-ui.c: browser visiblity is saved now,
+	* playlist/library-ui.c: browser visibility is saved now,
@@ -14153 +14153 @@
-	live in the rhythmbox exe instaed of a separate app
+	live in the rhythmbox exe instead of a separate app
@@ -14165 +14165 @@
-	when rb quits. Not noticable on a fast box, but i think
+	when rb quits. Not noticeable on a fast box, but i think
@@ -14241 +14241 @@
-	fucked up (will fix later, commiting now to avoid conflicts).
+	fucked up (will fix later, committing now to avoid conflicts).
@@ -15010 +15010 @@
-	* playlist/library.c: dont add non-existant songs from the xml
+	* playlist/library.c: dont add non-existent songs from the xml
@@ -15055 +15055 @@
-	Accomodate fixes to node.c and node.h to handle memory management
+	Accommodate fixes to node.c and node.h to handle memory management
@@ -15073 +15073 @@
-	(for example when you add individiual songs), but this fixes the
+	(for example when you add individual songs), but this fixes the
@@ -15116 +15116 @@
-	can get the seperators wrong on some systems).
+	can get the separators wrong on some systems).
@@ -15381 +15381 @@
-	to wrok around treefilter bugs. A little unstable as well, *blames gtk*.
+	to work around treefilter bugs. A little unstable as well, *blames gtk*.
--- ./shell/rb-shell.c	original
+++ ./shell/rb-shell.c	fixed
@@ -1278 +1278 @@
-	 * @visibile: new visibility
+	 * @visible: new visibility
--- ./shell/rb-playlist-manager.c	original
+++ ./shell/rb-playlist-manager.c	fixed
@@ -155 +155 @@
-   * one is the prefered extension for files of this type. */
+   * one is the preferred extension for files of this type. */
@@ -1365 +1365 @@
- * @playlists: (out callee-allocates) (transfer full): holds the array of playlist names on reutrn
+ * @playlists: (out callee-allocates) (transfer full): holds the array of playlist names on return
--- ./shell/rb-shell-player.c	original
+++ ./shell/rb-shell-player.c	fixed
@@ -2180 +2180 @@
- * Reports whether playback is occuring by setting #playing.
+ * Reports whether playback is occurring by setting #playing.
@@ -2544 +2544 @@
-		rb_debug ("exiting error hander");
+		rb_debug ("exiting error handler");
--- ./shell/rb-play-order.h	original
+++ ./shell/rb-play-order.h	fixed
@@ -36 +36 @@
- * use the heirarchy should include rb-play-order.h and call the functions
+ * use the hierarchy should include rb-play-order.h and call the functions
--- ./shell/meson.build	original
+++ ./shell/meson.build	fixed
@@ -106 +106 @@
-rb_gir = gnome.generate_gir(librhythmbox_core,
+rb_git = gnome.generate_git(librhythmbox_core,
@@ -123 +123 @@
-    'GstPbutils-1.0', 'libxml2-2.0', mpid_gir[0]],
+    'GstPbutils-1.0', 'libxml2-2.0', mpid_git[0]],
--- ./shell/rb-track-transfer-batch.c	original
+++ ./shell/rb-track-transfer-batch.c	fixed
@@ -245 +245 @@
-			/* this overrides is_preferred so we don't transcode unneccessarily */
+			/* this overrides is_preferred so we don't transcode unnecessarily */
@@ -1233 +1233 @@
-	 * @extension: usual extension for the destionation media type
+	 * @extension: usual extension for the destination media type
--- ./widgets/eggwrapbox.c	original
+++ ./widgets/eggwrapbox.c	fixed
@@ -345 +345 @@
- *                  GObectClass                      *
+ *                  GObjectClass                      *
@@ -566 +566 @@
- * while itterating over a list of children, note the new index is returned) */
+ * while iterating over a list of children, note the new index is returned) */
@@ -627 +627 @@
- * while itterating over a list of children, note the new index is returned) */
+ * while iterating over a list of children, note the new index is returned) */
@@ -984 +984 @@
-      /* After the above aproximation, check if we cant fit one more on the line */
+      /* After the above approximation, check if we cant fit one more on the line */
@@ -1749 +1749 @@
-      else /* In HOMOGENEOUS mode; horizontally oriented boxs
+      else /* In HOMOGENEOUS mode; horizontally oriented box
@@ -1850 +1850 @@
-      else /* In HOMOGENEOUS mode; vertically oriented boxs
+      else /* In HOMOGENEOUS mode; vertically oriented box
@@ -1911 +1911 @@
-          /* After the above aproximation, check if we cant fit one more on the line */
+          /* After the above approximation, check if we cant fit one more on the line */
@@ -2092 +2092 @@
-          /* After the above aproximation, check if we cant fit one more on the line */
+          /* After the above approximation, check if we cant fit one more on the line */
--- ./widgets/rb-rating.c	original
+++ ./widgets/rb-rating.c	fixed
@@ -40 +40 @@
-/* Offset at the beggining of the widget */
+/* Offset at the beginning of the widget */
--- ./widgets/rb-library-browser.c	original
+++ ./widgets/rb-library-browser.c	fixed
@@ -405 +405 @@
-update_browser_property_visibilty (RhythmDBPropType prop,
+update_browser_property_visibility (RhythmDBPropType prop,
@@ -436 +436 @@
-	g_hash_table_foreach (priv->property_views, (GHFunc)update_browser_property_visibilty, properties);
+	g_hash_table_foreach (priv->property_views, (GHFunc)update_browser_property_visibility, properties);
--- ./widgets/rb-uri-dialog.c	original
+++ ./widgets/rb-uri-dialog.c	fixed
@@ -3 +3 @@
- *  Copyright (C) 2005 Renato Araujo Oliveira Filho - INdT <renato.filho@indt.org.br>
+ *  Copyright (C) 2005 Renato Araujo Oliveira Filho - IAndT <renato.filho@indt.org.br>
--- ./remote/dbus/rb-client.c	original
+++ ./remote/dbus/rb-client.c	fixed
@@ -861,7 +861,7 @@
-	if (g_str_equal (signal_name, "Seeked")) {
-		gint64 pos;
-		char *str;
-		g_variant_get (parameters, "(x)", &pos);
-		if (llabs(pos - data->position) >= G_USEC_PER_SEC) {
-			str = rb_make_duration_string (pos, FALSE);
-			g_print (_("Seeked to %s"), str);
+	if (g_str_equal (signal_name, "Sought")) {
+		gint64 pos;
+		char *str;
+		g_variant_get (parameters, "(x)", &pos);
+		if (llabs(pos - data->position) >= G_USEC_PER_SEC) {
+			str = rb_make_duration_string (pos, FALSE);
+			g_print (_("Sought to %s"), str);
--- ./po/fa.po	original
+++ ./po/fa.po	fixed
@@ -3239 +3239 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/ie.po	original
+++ ./po/ie.po	fixed
@@ -12 +12 @@
-"Last-Translator: OIS <mistresssilvara@hotmail.com>\n"
+"Last-Translator: IS <mistresssilvara@hotmail.com>\n"
@@ -102 +102 @@
-msgstr "Mi tre evaluat"
+msgstr "Mi tree evaluat"
@@ -291 +291 @@
-msgstr "Ci_ser"
+msgstr "Ci_set"
@@ -416 +416 @@
-msgstr "Copiar li importat files in li biblioteca"
+msgstr "Copiar li important files in li biblioteca"
@@ -444 +444 @@
-msgstr "Hierarchie de fó_lderes:"
+msgstr "Hierarchy de fó_lderes:"
@@ -452 +452 @@
-msgstr "Formate _preferet:"
+msgstr "Format _preferet:"
@@ -512 +512 @@
-msgstr "Formate preferet"
+msgstr "Format preferet"
@@ -602 +602 @@
-msgstr "Formate de playlist: "
+msgstr "Format de playlist: "
@@ -606 +606 @@
-msgstr "Formate de playlist"
+msgstr "Format de playlist"
@@ -628 +628 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -636 +636 @@
-msgstr "Descrition:"
+msgstr "Description:"
@@ -1105 +1105 @@
-msgstr "Formates de audio:"
+msgstr "Formats de audio:"
@@ -1307 +1307 @@
-msgstr "Statu:"
+msgstr "Status:"
@@ -1389 +1389 @@
-msgstr "Errore de autentication"
+msgstr "Errore de authentication"
@@ -1440 +1440 @@
-msgstr "Autentication ne successat. Ples repenar denov."
+msgstr "Authentication ne successat. Ples repenar denov."
@@ -1478 +1478 @@
-msgstr "Dinamic con simil _artistes"
+msgstr "Dynamic con simil _artistes"
@@ -2014 +2014 @@
-msgstr "Statu del IM"
+msgstr "Status del IM"
@@ -2366 +2366 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2410 +2410 @@
-msgstr "Decembre (12)"
+msgstr "December (12)"
@@ -2454 +2454 @@
-msgstr "$15 US (TRE generosi!)"
+msgstr "$15 US (TREE generosi!)"
@@ -2517 +2517 @@
-msgstr "Formate _preferet:"
+msgstr "Format _preferet:"
@@ -2646 +2646 @@
-msgstr "Null spacie restat in li aparate MTP"
+msgstr "Null spacie restart in li aparate MTP"
@@ -2714 +2714 @@
-msgstr "Console de Python interactiv"
+msgstr "Console de Python interactive"
@@ -2883 +2883 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3043 +3043 @@
-msgstr "Statu"
+msgstr "Status"
@@ -3288 +3288 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3299 +3299 @@
-msgstr "Ínconosset statu de buton «%s»"
+msgstr "Ínconosset status de button «%s»"
@@ -3443 +3443 @@
-msgstr "Exemple"
+msgstr "Example"
@@ -3460 +3460 @@
-msgstr "OIS <mistresssilvara@hotmail.com>, 2016"
+msgstr "IS <mistresssilvara@hotmail.com>, 2016"
@@ -3566 +3566 @@
-"Usa «%s --help» por vider un complet liste de comandes.\n"
+"Usa «%s --help» por vider un complete liste de comandes.\n"
@@ -3578 +3578 @@
-msgstr "Formate XSPF"
+msgstr "Format XSPF"
@@ -3780 +3780 @@
-msgstr "Un file nominat «%s» ja existe.  Esque substituer it?"
+msgstr "Un file nominat «%s» ja existe.  Esque substitute it?"
@@ -3796 +3796 @@
-msgstr "Substituer _omni"
+msgstr "Substitute _omni"
--- ./po/or.po	original
+++ ./po/or.po	fixed
@@ -302 +302 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/lv.po	original
+++ ./po/lv.po	fixed
@@ -657 +657 @@
-msgstr "Autors:"
+msgstr "Authors:"
@@ -1343 +1343 @@
-msgstr "Statuss:"
+msgstr "Status:"
@@ -2009 +2009 @@
-msgstr "IM statuss"
+msgstr "IM status"
@@ -2238 +2238 @@
-msgstr "Dziesmu vārdu mape"
+msgstr "Dziesmu vārdu map"
@@ -2569 +2569 @@
-"Kļūdas teksts ir sekojošs:\n"
+"Kļūdas texts ir sekojošs:\n"
@@ -2931 +2931 @@
-msgstr "Autors"
+msgstr "Authors"
@@ -3125 +3125 @@
-msgstr "Statuss"
+msgstr "Status"
@@ -3346 +3346 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/hu.po	original
+++ ./po/hu.po	fixed
@@ -47 +47 @@
-"Nem sikerült létrehozni a playbin elemet; ellenőrizze a GStreamer telepítését"
+"Nem sikerült létrehozni a playbin element; ellenőrizze a GStreamer telepítését"
@@ -53 +53 @@
-"Nem sikerült létrehozni a(z) %s elemet; ellenőrizze a GStreamer telepítését"
+"Nem sikerült létrehozni a(z) %s element; ellenőrizze a GStreamer telepítését"
@@ -76 +76 @@
-msgstr "Nem sikerült létrehozni a GStreamer elemet; ellenőrizze a telepítését"
+msgstr "Nem sikerült létrehozni a GStreamer element; ellenőrizze a telepítését"
@@ -82 +82 @@
-"Nem sikerült létrehozni a hangkimeneti elemet; ellenőrizze a telepítését"
+"Nem sikerült létrehozni a hangkimeneti element; ellenőrizze a telepítését"
@@ -134 +134 @@
-"(telefonokat is) és olyan internetes zenei szolgáltatásokat, mint a Last.fm "
+"(telefonokat is) és olyan internets zenei szolgáltatásokat, mint a Last.fm "
@@ -1059 +1059 @@
-"Nem sikerült létrehozni a „decodebin” elemet; ellenőrizze a GStreamer "
+"Nem sikerült létrehozni a „decodebin” element; ellenőrizze a GStreamer "
@@ -1068 +1068 @@
-"Nem sikerült létrehozni a „giostreamsink” elemet; ellenőrizze a GStreamer "
+"Nem sikerült létrehozni a „giostreamsink” element; ellenőrizze a GStreamer "
@@ -1917 +1917 @@
-msgstr "Az internetes rádióállomás frekvenciája"
+msgstr "Az internets rádióállomás frekvenciája"
@@ -1949 +1949 @@
-msgstr "Különböző helyi és internetes médiaforrások tallózása"
+msgstr "Különböző helyi és internets médiaforrások tallózása"
@@ -2022 +2022 @@
-msgstr "Csatolási pont:"
+msgstr "Csatolási point:"
@@ -2091 +2091 @@
-msgstr "Internetes rádió"
+msgstr "Internets rádió"
@@ -2109 +2109 @@
-msgstr "Internetes rádióállomás keresése"
+msgstr "Internets rádióállomás keresése"
@@ -2126 +2126 @@
-msgstr "Új internetes rádióállomás"
+msgstr "Új internets rádióállomás"
@@ -2130 +2130 @@
-msgstr "Az internetes rádióállomás URL-címe:"
+msgstr "Az internets rádióállomás URL-címe:"
@@ -2724 +2724 @@
-"A(z) %s Python-modul nem érhető el. Telepítse a modult, majd indítsa újra a"
+"A(z) %s Python-module nem érhető el. Telepítse a modult, majd indítsa újra a"
@@ -3233 +3233 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/cy.po	original
+++ ./po/cy.po	fixed
@@ -949 +949 @@
-msgid "An exception occured '%s'"
+msgid "An exception occurred '%s'"
@@ -1073 +1073 @@
-"bonobo-activation; mae'r rhybudd hyn yn ddiniwed, ond ni fydd cyfathrebu "
+"bonobo-activation; mae'r rhybudd hyn yn ddiniwed, one ni fydd cyfathrebu "
@@ -1190 +1190 @@
-#. an error occured
+#. an error occurred
--- ./po/ro.po	original
+++ ./po/ro.po	fixed
@@ -559 +559 @@
-msgstr "Suport player"
+msgstr "Support player"
@@ -591 +591 @@
-msgstr "După extensie"
+msgstr "După extensive"
@@ -644 +644 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -670 +670 @@
-msgstr "Drepturi de autor:"
+msgstr "Drepturi de author:"
@@ -910 +910 @@
-msgstr "Conținutul curent"
+msgstr "Conținutul current"
@@ -1106 +1106 @@
-msgstr "Suport pentru dispozitive Android 4.0+ (prin MTP)"
+msgstr "Support pentru dispozitive Android 4.0+ (prin MTP)"
@@ -1118 +1118 @@
-msgstr "Număr de serie:"
+msgstr "Număr de series:"
@@ -1130 +1130 @@
-msgstr "Formate audio:"
+msgstr "Format audio:"
@@ -1136 +1136 @@
-msgstr "Sistem"
+msgstr "System"
@@ -1223 +1223 @@
-msgstr "Suport pentru redarea CD-urilor audio ca sursă muzicală"
+msgstr "Support pentru redarea CD-urilor audio ca sursă muzicală"
@@ -1241 +1241 @@
-msgstr "Nu se poate găsi un modul sursă GStreamer CD"
+msgstr "Nu se poate găsi un module sursă GStreamer CD"
@@ -1286 +1286 @@
-"Acest disc se potrivește cu mai multe albume. Selectați albumul corect."
+"Acest disc se potrivește cu mai multe albume. Selectați albumul correct."
@@ -1410 +1410 @@
-msgstr "Ceasul nu este configurat corect"
+msgstr "Ceasul nu este configurat correct"
@@ -1526 +1526 @@
-msgstr "Piese apreciate de utilizator:"
+msgstr "Piese appreciate de utilizator:"
@@ -1639 +1639 @@
-msgstr "Acest post de radio nu are suficient conținut pentru a putea fi redat"
+msgstr "Acest post de radio nu are sufficient conținut pentru a putea fi redat"
@@ -1783 +1783 @@
-msgstr "Albume populare de %s"
+msgstr "Albume popular de %s"
@@ -1942 +1942 @@
-msgstr "Suport pentru servicii de difuzare radio FM"
+msgstr "Support pentru servicii de difuzare radio FM"
@@ -1963 +1963 @@
-"Suport pentru dispozitive generice de redare audio (plus PSP și Nokia 770)"
+"Support pentru dispozitive generice de redare audio (plus PSP și Nokia 770)"
@@ -2098 +2098 @@
-"sau defect. Înainte de a-l utiliza trebuie să îl inițializați, iar această "
+"sau defect. Înainte de a-l utilize trebuie să îl inițializați, iar această "
@@ -2115 +2115 @@
-"Suport pentru dispozitive Apple iPod (afișează conținut, ascultă de pe "
+"Support pentru dispozitive Apple iPod (afișează conținut, ascultă de pe "
@@ -2139 +2139 @@
-msgstr "Suport pentru posturi de radio difuzate prin Internet"
+msgstr "Support pentru posturi de radio difuzate prin Internet"
@@ -2238 +2238 @@
-msgstr "Alege dosarul pentru versuri..."
+msgstr "Allege dosarul pentru versuri..."
@@ -2315 +2315 @@
-"    Membrii plătitori pot descărca întregul catalog fără limite (niciun alt "
+"    Membrii plătitori pot descărca întregul catalog fără limit (niciun alt "
@@ -2332 +2332 @@
-"    *Formate de fișier prietenoase cu sursa deschisă: MP3-urile și WAV-"
+"    *Format de fișier prietenoase cu sursa deschisă: MP3-urile și WAV-"
@@ -2364 +2364 @@
-"Adaugă suport în Rhythmbox pentru a asculta și a cumpăra melodii din "
+"Adaugă support în Rhythmbox pentru a asculta și a cumpăra melodii din "
@@ -2621 +2621 @@
-"Suport pentru dispozitive MTP (afișează conținutul, transferă piese, ascultă "
+"Support pentru dispozitive MTP (afișează conținutul, transferă piese, ascultă "
@@ -2888 +2888 @@
-msgstr "Cheie de acces:"
+msgstr "Cheie de access:"
@@ -2929 +2929 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3181 +3181 @@
-msgstr "Comută modul redare/pauză"
+msgstr "Comută module redare/pauză"
@@ -3265 +3265 @@
-msgstr "Afișează volumul curent"
+msgstr "Afișează volumul current"
@@ -3275 +3275 @@
-msgstr "Pornește mediul interactiv"
+msgstr "Pornește mediul interactive"
@@ -3343 +3343 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3428 +3428 @@
-msgstr[0] "un minut"
+msgstr[0] "un minute"
@@ -3487 +3487 @@
-msgstr "Modul exemplu phyton"
+msgstr "Module exemplu python"
@@ -3491 +3491 @@
-msgstr "Un modul exemplu scris în python fără nicio funcționalitate"
+msgstr "Un module exemplu scris în python fără nicio funcționalitate"
@@ -3501 +3501 @@
-msgstr "Modul exemplu"
+msgstr "Module exemplu"
@@ -3505 +3505 @@
-msgstr "Un modul exemplu scris în C fără nicio funcționalitate"
+msgstr "Un module exemplu scris în C fără nicio funcționalitate"
@@ -3509 +3509 @@
-msgstr "Modul exemplu Vala"
+msgstr "Module exemplu Vala"
@@ -3513 +3513 @@
-msgstr "Un modul exemplu scris în Vala fără nicio funcționalitate"
+msgstr "Un module exemplu scris în Vala fără nicio funcționalitate"
@@ -3575 +3575 @@
-"Rhythmbox este distribuit cu speranța că va fi util, dar FĂRĂ\n"
+"Rhythmbox este distribute cu speranța că va fi util, dar FĂRĂ\n"
@@ -4070 +4070 @@
-msgstr "Alege locația bibliotecii"
+msgstr "Allege locația bibliotecii"
@@ -4106 +4106 @@
-"Nu există spațiu suficient pe dispozitiv pentru a transfera muzica "
+"Nu există spațiu sufficient pe dispozitiv pentru a transfera muzica "
@@ -4489 +4489 @@
-msgstr "Bătăi pe minut"
+msgstr "Bătăi pe minute"
@@ -4548 +4548 @@
-msgstr "Cu cele ma_i apreciate piese primele"
+msgstr "Cu cele ma_i appreciate piese primele"
@@ -4612 +4612 @@
-msgstr "Bătăi pe minut"
+msgstr "Bătăi pe minute"
@@ -4815 +4815 @@
-#~ msgstr "Efect vizual"
+#~ msgstr "Effect vizual"
--- ./po/sr.po	original
+++ ./po/sr.po	fixed
@@ -3242 +3242 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/oc.po	original
+++ ./po/oc.po	fixed
@@ -335 +335 @@
-"_Installar lo logicial suplementari necessari a l'utilizacion d'aqueste "
+"_Installar lo logicial suplementari necessari a l'utilization d'aqueste "
@@ -348 +348 @@
-msgstr "_Artistas e albums"
+msgstr "_Artists e albums"
@@ -352 +352 @@
-msgstr "_Tipes e artistas"
+msgstr "_Tipes e artists"
@@ -356 +356 @@
-msgstr "M_enas, artistas e albums"
+msgstr "M_enas, artists e albums"
@@ -425 +425 @@
-"Causissètz un emplaçament que conten de musica per l'apodre a vòstra "
+"Causissètz un emplaçament que contain de musica per l'apodre a vòstra "
@@ -530 +530 @@
-msgstr "Utilizacion de la capacitat"
+msgstr "Utilization de la capacitat"
@@ -635 +635 @@
-"Abonatz-vos als podcasts per poder telecargar los novèls episòdis tre lor "
+"Abonatz-vos also podcasts per poder telecargar los novèls episòdis tree lor "
@@ -648 +648 @@
-msgstr "Autor :"
+msgstr "Author :"
@@ -656 +656 @@
-msgstr "Descripcion :"
+msgstr "Description :"
@@ -860 +860 @@
-msgstr "Òrdre de _triada dels artistas :"
+msgstr "Òrdre de _triada dels artists :"
@@ -864 +864 @@
-msgstr "Òrdre de _triada dels artistas de l'album :"
+msgstr "Òrdre de _triada dels artists de l'album :"
@@ -1057 +1057 @@
-"Impossible de metre d'etiquetas a aqueste fichièr perque conten mantun flux"
+"Impossible de metre d'etiquetas a aqueste fichièr perque contain mantun flux"
@@ -1199 +1199 @@
-msgstr "Òrdre de _triada dels artistas :"
+msgstr "Òrdre de _triada dels artists :"
@@ -1365 +1365 @@
-msgstr "Artistas preferits"
+msgstr "Artists preferits"
@@ -1473 +1473 @@
-msgstr "Escotar una ràdio amb d'artistas _similars"
+msgstr "Escotar una ràdio amb d'artists _similars"
@@ -1484 +1484 @@
-msgstr "Artistas similars :"
+msgstr "Artists similars :"
@@ -1742 +1742 @@
-msgstr "Cap d'artista pas indicat."
+msgstr "Cap d'artista pas indicate."
@@ -1789 +1789 @@
-msgstr "Pas cap d'informacion disponibla"
+msgstr "Pas cap d'information disponibla"
@@ -1901 +1901 @@
-"Apòrta una implementacion de l'especificacion d'interfàcia D-Bus MediaServer2"
+"Apòrta una implementation de l'especificacion d'interfàcia D-Bus MediaServer2"
@@ -1910 +1910 @@
-msgstr "Artistas"
+msgstr "Artists"
@@ -2083 +2083 @@
-"Rhythmbox, mas aquesta operacion va suprimir tota informacion de cançons que "
+"Rhythmbox, mas aquesta operacion va suprimir tota information de cançons que "
@@ -2187 +2187 @@
-msgstr "Emplaça_ment :"
+msgstr "Emplaça_meant :"
@@ -2297 +2297 @@
-"telecargament sul catalòg complet (cap de servici mai lo permet pas)"
+"telecargament sul catalòg complete (cap de servici mai lo permet pas)"
@@ -2318 +2318 @@
-msgstr "    * Totes los albums e los artistas son seleccionats individualament"
+msgstr "    * Totes los albums e los artists son seleccionats individualament"
@@ -2394 +2394 @@
-msgstr "decembre (12)"
+msgstr "december (12)"
@@ -2585 +2585 @@
-msgstr "Apòrta una implementacion de l'especificacion d'interàcia D-Bus MPRIS"
+msgstr "Apòrta una implementation de l'especificacion d'interàcia D-Bus MPRIS"
@@ -2645 +2645 @@
-msgstr "Notificacion"
+msgstr "Notification"
@@ -2649 +2649 @@
-msgstr "Popups de notificacion"
+msgstr "Popups de notification"
@@ -2724 +2724 @@
-"estat definit dins lo fichièr %s, utilizatz lo senhal per defaut (« "
+"estat definite dins lo fichièr %s, utilizatz lo senhal per default (« "
@@ -2846 +2846 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2934 +2934 @@
-msgstr "Lo flux conten pas cap d'element telecargable"
+msgstr "Lo flux contain pas cap d'element telecargable"
@@ -2976 +2976 @@
-msgstr "Erro de Podcast"
+msgstr "Error de Podcast"
@@ -3049 +3049 @@
-msgstr "Afichar pas una fenèstra Rhythmbox existenta"
+msgstr "Afichar pas una fenèstra Rhythmbox existential"
@@ -3081 +3081 @@
-msgstr "Legís l'URI indicat, en l'important se necessari"
+msgstr "Legís l'URI indicate, en l'important se necessari"
@@ -3105 +3105 @@
-msgstr "Seleccionar la font que correspond a l'URI indicat"
+msgstr "Seleccionar la font que correspond a l'URI indicate"
@@ -3113 +3113 @@
-msgstr "Activar la font que correspond a l'URI indicat"
+msgstr "Activar la font que correspond a l'URI indicate"
@@ -3121 +3121 @@
-msgstr "Jogar a partir de la font que correspond a l'URI indicat"
+msgstr "Jogar a partir de la font que correspond a l'URI indicate"
@@ -3233 +3233 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3377 +3377 @@
-msgstr "Un exemple d'empeuton sens foncionalitat escrich en Python"
+msgstr "Un example d'empeuton sens foncionalitat escrich en Python"
@@ -3391 +3391 @@
-msgstr "Un exemple d'empeuton sens foncionalitat escrich en C"
+msgstr "Un example d'empeuton sens foncionalitat escrich en C"
@@ -3399 +3399 @@
-msgstr "Un exemple d'empeuton sens foncionalitat escrich en Vala"
+msgstr "Un example d'empeuton sens foncionalitat escrich en Vala"
@@ -3431,3 +3431,3 @@
-"Rhythmbox Aqueste programa es distribuit dins l'esper que serà util, \n"
-"mas SENS CAP DE GARANTIA ; sens quitament pas de garantia implicita de \n"
-"COMERCIABILITAT o DE CONFORMITAT A UNA UTILIZACION PARTICULARA. \n"
+"Rhythmbox Aqueste programa es distribute dins l'esper que serà util, \n"
+"mas SENS CAP DE GARANTIA ; sens quitament pas de garantia implicita de \n"
+"COMERCIABILITAT o DE CONFORMITAT A UNA UTILIZATION PARTICULARA. \n"
@@ -3807 +3807 @@
-msgstr "Recèrca los artistas"
+msgstr "Recèrca los artists"
@@ -3926 +3926 @@
-msgstr "Exemple de camin :"
+msgstr "Example de camin :"
@@ -4096 +4096 @@
-msgstr "Paramètres per defaut"
+msgstr "Paramètres per default"
@@ -4217 +4217 @@
-msgstr[1] "Totes los %d artistas (%d)"
+msgstr[1] "Totes los %d artists (%d)"
@@ -4466 +4466 @@
-msgstr "conten"
+msgstr "contain"
@@ -4470 +4470 @@
-msgstr "conten pas"
+msgstr "contain pas"
@@ -4702 +4702 @@
-#~ msgstr "Ecran complet"
+#~ msgstr "Ecran complete"
@@ -4758 +4758 @@
-#~ msgstr "_Ecran complet"
+#~ msgstr "_Ecran complete"
--- ./po/it.po	original
+++ ./po/it.po	fixed
@@ -15 +15 @@
-#   secondo catalogo (ove possibile distinguere)
+#   secondo catalogo (ove possible distinguere)
@@ -38 +38 @@
-msgstr "Impossibile creare un file temporaneo su cui scrivere: %s"
+msgstr "Impossible creare un file temporaneo su cui scrivere: %s"
@@ -43 +43 @@
-msgstr "Impossibile creare un elemento sink GStreamer per scrivere su %s"
+msgstr "Impossible creare un elemento sink GStreamer per scrivere su %s"
@@ -157 +157 @@
-"Rhythmbox è software libero basato su GTK+ e GStreamer ed è possibile "
+"Rhythmbox è software libero basato su GTK+ e GStreamer ed è possible "
@@ -555 +555 @@
-msgstr "Preferenze di sincronizzazione"
+msgstr "Preference di sincronizzazione"
@@ -1039 +1039 @@
-msgstr "Impossibile ottenere dello spazio libero su %s: %s"
+msgstr "Impossible ottenere dello spazio libero su %s: %s"
@@ -1077 +1077 @@
-"Impossibile scrivere i tag su questo file poiché contiene diversi stream"
+"Impossible scrivere i tag su questo file poiché contiene diversi stream"
@@ -1084 +1084 @@
-"Impossibile scrivere i tag su questo file poiché non è codificato in un "
+"Impossible scrivere i tag su questo file poiché non è codificato in un "
@@ -1134 +1134 @@
-msgstr "Numero di serie:"
+msgstr "Numero di series:"
@@ -1257 +1257 @@
-msgstr "Impossibile trovare un plugin Gstreamer per sorgenti CD"
+msgstr "Impossible trovare un plugin Gstreamer per sorgenti CD"
@@ -1279 +1279 @@
-msgstr "Impossibile trovare questo album su MusicBrainz."
+msgstr "Impossible trovare questo album su MusicBrainz."
@@ -1284 +1284 @@
-"È possibile migliorare il database di MusicBrainz aggiungendo questo album."
+"È possible migliorare il database di MusicBrainz aggiungendo questo album."
@@ -1294 +1294 @@
-"Impossibile eseguire una ricerca su MusicBrainz per i dettagli dell'album."
+"Impossible eseguire una ricerca su MusicBrainz per i dettagli dell'album."
@@ -1298 +1298 @@
-msgstr "Impossibile leggere il dispositivo del CD."
+msgstr "Impossible leggere il dispositivo del CD."
@@ -1315 +1315 @@
-msgstr "Impossibile collegarsi al server di MusicBrainz"
+msgstr "Impossible collegarsi al server di MusicBrainz"
@@ -1625 +1625 @@
-# NdT: tag non è tradotto su Last.fm
+# AndT: tag non è tradotto su Last.fm
@@ -1659 +1659 @@
-# NdT ascoltare come da traduzione di Last.fm
+# AndT ascoltare come da traduzione di Last.fm
@@ -1701 +1701 @@
-msgstr "Impossibile per Rhythmbox registare il disco audio"
+msgstr "Impossible per Rhythmbox registare il disco audio"
@@ -1706 +1706 @@
-msgstr "Impossibile creare un elenco di tracce audio"
+msgstr "Impossible creare un elenco di tracce audio"
@@ -1712 +1712 @@
-msgstr "Impossibile scrivere il file progetto audio %s: %s"
+msgstr "Impossible scrivere il file progetto audio %s: %s"
@@ -1718 +1718 @@
-msgstr "Impossibile scrivere il progetto audio"
+msgstr "Impossible scrivere il progetto audio"
@@ -1722 +1722 @@
-msgstr "Impossibile creare il progetto CD audio"
+msgstr "Impossible creare il progetto CD audio"
@@ -1780 +1780 @@
-msgstr "Nessun artista specificato."
+msgstr "Nessun artista specification."
@@ -1823 +1823 @@
-msgstr "Impossibile recuperare le informazioni sull'album:"
+msgstr "Impossible recuperare le informazioni sull'album:"
@@ -1831 +1831 @@
-msgstr "Impossibile recuperare le informazioni sull'artista:"
+msgstr "Impossible recuperare le informazioni sull'artista:"
@@ -1877 +1877 @@
-msgstr "Impossibile associarsi con questo Remote"
+msgstr "Impossible associarsi con questo Remote"
@@ -1881 +1881 @@
-msgstr "È ora possibile controllare Rhythmbox attraverso il proprio Remote"
+msgstr "È ora possible controllare Rhythmbox attraverso il proprio Remote"
@@ -1915 +1915 @@
-msgstr "Impossibile connettersi alla musica condivisa"
+msgstr "Impossible connettersi alla musica condivisa"
@@ -1927 +1927 @@
-msgstr "Impossibile associarsi con questo Remote."
+msgstr "Impossible associarsi con questo Remote."
@@ -2159 +2159 @@
-msgstr "Impossibile inizializzare il nuovo iPod"
+msgstr "Impossible inizializzare il nuovo iPod"
@@ -2228 +2228 @@
-msgstr "Impossibile cambiare la proprietà della stazione"
+msgstr "Impossible cambiare la proprietà della stazione"
@@ -2234 +2234 @@
-"Impossibile cambiare l'URI della stazione in %s, poiché tale stazione esiste "
+"Impossible cambiare l'URI della stazione in %s, poiché tale stazione esiste "
@@ -2270 +2270 @@
-"ListenBrainz. È possibile visualizzare il proprio token utente nel <a href="
+"ListenBrainz. È possible visualizzare il proprio token utente nel <a href="
@@ -2388 +2388 @@
-msgstr "È possibile trovare ulteriori informazioni presso "
+msgstr "È possible trovare ulteriori informazioni presso "
@@ -2588 +2588 @@
-msgstr "Impossibile scaricare l'album"
+msgstr "Impossible scaricare l'album"
@@ -2598 +2598 @@
-msgstr "Impossibile caricare il catalogo"
+msgstr "Impossible caricare il catalogo"
@@ -2604 +2604 @@
-"È possibile che Rhythmbox non comprenda il catalogo di Magnatune, segnalare "
+"È possible che Rhythmbox non comprenda il catalogo di Magnatune, segnalare "
@@ -2623 +2623 @@
-"Si è verificato un errore durante il tentativo di autorizzare lo "
+"Si è verification un errore durante il tentativo di autorizzare lo "
@@ -2639 +2639 @@
-"Si è verificato un errore durante il tentativo di scaricare l'album.\n"
+"Si è verification un errore durante il tentativo di scaricare l'album.\n"
@@ -2688 +2688 @@
-msgstr "Impossibile aprire il dispositivo %s %s"
+msgstr "Impossible aprire il dispositivo %s %s"
@@ -2699 +2699 @@
-msgstr "Impossibile copiare il file dal dispositivo MTP: %s"
+msgstr "Impossible copiare il file dal dispositivo MTP: %s"
@@ -2709 +2709 @@
-msgstr "Impossibile aprire il file temporaneo: %s"
+msgstr "Impossible aprire il file temporaneo: %s"
@@ -2719 +2719 @@
-msgstr "Impossibile inviare il file al dispositivo MTP: %s"
+msgstr "Impossible inviare il file al dispositivo MTP: %s"
@@ -2743 +2743 @@
-msgstr "Successivo"
+msgstr "Succession"
@@ -2794 +2794 @@
-"È possibile accedere alla finestra principale per mezzo della variabile \\"
+"È possible accedere alla finestra principale per mezzo della variabile \\"
@@ -2860 +2860 @@
-msgstr "Preferenze di ReplayGain"
+msgstr "Preference di ReplayGain"
@@ -2932 +2932 @@
-msgstr "Preferenze di controllo remoto web"
+msgstr "Preference di controllo remoto web"
@@ -2969 +2969 @@
-"Impossibile caricare il feed. Controllare la propria connessione di rete."
+"Impossible caricare il feed. Controllare la propria connessione di rete."
@@ -2974 +2974 @@
-"Impossibile cercare i podcast. Controllare la propria connessione di rete."
+"Impossible cercare i podcast. Controllare la propria connessione di rete."
@@ -3067 +3067 @@
-"Si è verificato un problema nell'aggiungere questo podcast: %s. Verificare "
+"Si è verification un problema nell'aggiungere questo podcast: %s. Verificare "
@@ -3073 +3073 @@
-msgstr "Impossibile controllare il tipo di file: %s"
+msgstr "Impossible controllare il tipo di file: %s"
@@ -3083 +3083 @@
-msgstr "Impossibile analizzare i contenuti del feed"
+msgstr "Impossible analizzare i contenuti del feed"
@@ -3105 +3105 @@
-"sempre. Notare che scegliendo di eliminare il solo feed, è possibile "
+"sempre. Notare che scegliendo di eliminare il solo feed, è possible "
@@ -3143 +3143 @@
-"modo permanente. Notare che è possibile eliminare l'episodio mantenendo il "
+"modo permanente. Notare che è possible eliminare l'episodio mantenendo il "
@@ -3207 +3207 @@
-msgstr "Passa al brano successivo"
+msgstr "Passa al brano succession"
@@ -3235 +3235 @@
-msgstr "Riproduce un URI specificato, importandolo se necessario"
+msgstr "Riproduce un URI specification, importandolo se necessario"
@@ -3260 +3260 @@
-msgstr "Seleziona la sorgente che corrisponde all'URI indicato"
+msgstr "Seleziona la sorgente che corrisponde all'URI indication"
@@ -3268 +3268 @@
-msgstr "Attiva la sorgente che corrisponde all'URI indicato"
+msgstr "Attiva la sorgente che corrisponde all'URI indication"
@@ -3276 +3276 @@
-msgstr "Riproduce dalla sorgente che corrisponde all'URI indicato"
+msgstr "Riproduce dalla sorgente che corrisponde all'URI indication"
@@ -3390 +3390 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3422 +3422 @@
-msgstr "Impossibile accedere a %s: %s"
+msgstr "Impossible accedere a %s: %s"
@@ -3470 +3470 @@
-msgstr "Impossibile caricare il database musicale:"
+msgstr "Impossible caricare il database musicale:"
@@ -3571 +3571 @@
-"Rhythmbox è software libero; è possibile ridistribuirlo o modificarlo\n"
+"Rhythmbox è software libero; è possible ridistribuirlo o modificarlo\n"
@@ -3583 +3583 @@
-"Rhythmbox è distribuito nella speranza che possa risultare utile,\n"
+"Rhythmbox è distribution nella speranza che possa risultare utile,\n"
@@ -3610 +3610 @@
-msgstr "Hanno contribuito:"
+msgstr "Hanno contribution:"
@@ -3622 +3622 @@
-msgstr "Impossibile mostrare la guida"
+msgstr "Impossible mostrare la guida"
@@ -3665 +3665 @@
-"riga di comando.\n"
+"riga di commando.\n"
@@ -3701 +3701 @@
-msgstr "Impossibile leggere la playlist"
+msgstr "Impossible leggere la playlist"
@@ -3713 +3713 @@
-msgstr "Impossibile salvare la playlist"
+msgstr "Impossible salvare la playlist"
@@ -3804 +3804 @@
-msgstr "Nessun brano successivo"
+msgstr "Nessun brano succession"
@@ -3808 +3808 @@
-msgstr "Impossibile fermare la riproduzione"
+msgstr "Impossible fermare la riproduzione"
@@ -3822 +3822 @@
-msgstr "Impossibile avviare la riproduzione"
+msgstr "Impossible avviare la riproduzione"
@@ -3859 +3859 @@
-msgstr "Preferenze di Rhythmbox"
+msgstr "Preference di Rhythmbox"
@@ -3890 +3890 @@
-msgstr "_Ignora tutto"
+msgstr "_Ignore tutto"
@@ -3907,5 +3907,5 @@
-"Non è possibile trasferire %d file poiché deve essere convertito in un "
-"formato supportato dal dispositivo di destinazione, ma non è presente alcun "
-"profilo di codifica adatto."
-msgstr[1] ""
-"Non è possibile trasferire %d file poiché devono essere convertiti in un "
+"Non è possible trasferire %d file poiché deve essere convertito in un "
+"formato supportato dal dispositivo di destinazione, ma non è presente alcun "
+"profilo di codifica adatto."
+msgstr[1] ""
+"Non è possible trasferire %d file poiché devono essere convertiti in un "
@@ -3936,5 +3936,5 @@
-"È richiesto del software aggiuntivo per convertire %d file in un formato "
-"supportato dal dispositivo di destinazione:\n"
-"%s"
-msgstr[1] ""
-"È richiesto del software aggiuntivo per convertire %d file in un formato "
+"È richiesto del software aggiuntivo per converter %d file in un formato "
+"supportato dal dispositivo di destinazione:\n"
+"%s"
+msgstr[1] ""
+"È richiesto del software aggiuntivo per converter %d file in un formato "
@@ -3946 +3946 @@
-msgstr "Impossibile trasferire i brani"
+msgstr "Impossible trasferire i brani"
@@ -3988 +3988 @@
-msgstr "Impossibile espellere"
+msgstr "Impossible espellere"
@@ -3993 +3993 @@
-msgstr "Impossibile smontare"
+msgstr "Impossible smontare"
@@ -4254 +4254 @@
-msgstr "Bitrate variabile limitato"
+msgstr "Bitrate variabile limitation"
@@ -4271 +4271 @@
-msgstr "Compositore"
+msgstr "Composite"
@@ -4433 +4433 @@
-msgstr "Compositore"
+msgstr "Composite"
@@ -4528 +4528 @@
-msgstr "Compositore"
+msgstr "Composite"
--- ./po/ChangeLog	original
+++ ./po/ChangeLog	fixed
@@ -2440 +2440 @@
-	* POTFILES.in: Remove non-existant file(s).
+	* POTFILES.in: Remove non-existent file(s).
@@ -2524 +2524 @@
-2006-02-03  William Jon McCann  <mccann@jhu.edu>
+2006-02-03  William Jon McCan  <mccann@jhu.edu>
@@ -2656 +2656 @@
-2006-01-05  William Jon McCann  <mccann@jhu.edu>
+2006-01-05  William Jon McCan  <mccann@jhu.edu>
@@ -3306 +3306 @@
-	* POTFILES.skip: Remove non-existant file(s).
+	* POTFILES.skip: Remove non-existent file(s).
@@ -3435 +3435 @@
-	* uk.po: Updated Ukrainian traslation.
+	* uk.po: Updated Ukrainian translation.
@@ -3862 +3862 @@
-	* tr.po:  Updated Turkish Translation from Enver Altin.
+	* tr.po:  Updated Turkish Translation from Never Altin.
@@ -3955 +3955 @@
-	* es.po: Updated Spansih translation.
+	* es.po: Updated Spanish translation.
@@ -5024 +5024 @@
-	* POTFILES.in: Added missing files, removed non-existant ones.
+	* POTFILES.in: Added missing files, removed non-existent ones.
--- ./po/pt.po	original
+++ ./po/pt.po	fixed
@@ -324 +324 @@
-msgstr "_Instalar programas adicionais necessários para usar este formato"
+msgstr "_Instalar programs adicionais necessários para usar este formato"
@@ -336 +336 @@
-msgstr "_Artistas e álbuns"
+msgstr "_Artists e álbuns"
@@ -340 +340 @@
-msgstr "_Géneros e artistas"
+msgstr "_Géneros e artists"
@@ -344 +344 @@
-msgstr "Gén_eros, artistas e álbuns"
+msgstr "Gén_eros, artists e álbuns"
@@ -634 +634 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -658 +658 @@
-msgstr "Direitos de autor:"
+msgstr "Direitos de author:"
@@ -846 +846 @@
-msgstr "Ordem dos _artistas:"
+msgstr "Ordem dos _artists:"
@@ -878 +878 @@
-msgstr "Mensagem de erro"
+msgstr "Mensagem de error"
@@ -1152 +1152 @@
-msgstr "Erro ao montar dispositivo Android"
+msgstr "Error ao montar dispositivo Android"
@@ -1184 +1184 @@
-msgstr "Ordem de _ordenação de artistas:"
+msgstr "Ordem de _ordenação de artists:"
@@ -1274 +1274 @@
-msgstr "Erro do servidor Musicbrainz"
+msgstr "Error do servidor Musicbrainz"
@@ -1350 +1350 @@
-msgstr "Top de artistas"
+msgstr "Top de artists"
@@ -1378 +1378 @@
-msgstr "Erro de autenticação"
+msgstr "Error de autenticação"
@@ -1426 +1426 @@
-"Erro de autenticação. Por favor, tente autenticar-se no serviço novamente."
+"Error de autenticação. Por favor, tente autenticar-se no serviço novamente."
@@ -1430 +1430 @@
-msgstr "Erro de ligação. Por favor, tente autenticar-se novamente."
+msgstr "Error de ligação. Por favor, tente autenticar-se novamente."
@@ -1459 +1459 @@
-msgstr "Ouvir rádio de artistas _similares"
+msgstr "Ouvir rádio de artists _similares"
@@ -1592 +1592 @@
-msgstr "Erro ao sintonizar estação: sem resposta"
+msgstr "Error ao sintonizar estação: sem resposta"
@@ -1625 +1625 @@
-msgstr "Erro ao sintonizar estação: %i - %s"
+msgstr "Error ao sintonizar estação: %i - %s"
@@ -1629 +1629 @@
-msgstr "Erro ao sintonizar estação: resposta inesperada"
+msgstr "Error ao sintonizar estação: resposta inesperada"
@@ -1633 +1633 @@
-msgstr "Erro ao sintonizar estação: resposta inválida"
+msgstr "Error ao sintonizar estação: resposta inválida"
@@ -1796 +1796 @@
-msgstr "Procurar contro_los remotos por toque"
+msgstr "Procurar control_los remotos por toque"
@@ -1898 +1898 @@
-msgstr "Artistas"
+msgstr "Artists"
@@ -2069,2 +2069,2 @@
-"inicializado ou corrompido. Deve ser inicializado para o Rhythmbox utilizá-"
-"lo, mas isso destruirá quaisquer metadados de canções presentes. Se deseja "
+"inicializado ou corrompido. Deve set inicializado para o Rhythmbox utilizá-"
+"lo, mas isso destruirá quaisquer metadados de canções presents. Se deseja "
@@ -2298 +2298 @@
-"    * Formatos de ficheiro suportados por programas livres: MP3 e WAV, mas "
+"    * Formatos de ficheiro suportados por programs livres: MP3 e WAV, mas "
@@ -2303 +2303 @@
-msgstr "    * Todos os álbuns e artistas escolhidos a dedo"
+msgstr "    * Todos os álbuns e artists escolhidos a dedo"
@@ -2522 +2522 @@
-"O Rhythmbox não entendeu o catálogo da Magnatune, por favor submeta um erro."
+"O Rhythmbox não entendeu o catálogo da Magnatune, por favor submeta um error."
@@ -2531 +2531 @@
-msgstr "Erro de transferência"
+msgstr "Error de transferência"
@@ -2540 +2540 @@
-"Ocorreu um erro ao tentar autorizar a transferência.\n"
+"Ocorreu um error ao tentar autorizar a transferência.\n"
@@ -2546 +2546 @@
-msgstr "Erro"
+msgstr "Error"
@@ -2555,2 +2555,2 @@
-"Ocorreu um erro ao tentar transferir o álbum.\n"
-"O texto do erro é:\n"
+"Ocorreu um error ao tentar transferir o álbum.\n"
+"O texto do error é:\n"
@@ -2579 +2579 @@
-"Suporte para dispositivos MTP (mostra o conteúdo, transfere, reproduz a "
+"Suporte para dispositivos MTP (mostra o conteúdo, transferred, reproduz a "
@@ -2588 +2588 @@
-msgstr "Erro do reprodutor multimédia"
+msgstr "Error do reprodutor multimédia"
@@ -2858 +2858 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2883 +2883 @@
-msgstr "Erro ao transferir podcast"
+msgstr "Error ao transferir podcast"
@@ -2891 +2891 @@
-msgstr "Erro no podcast"
+msgstr "Error no podcast"
@@ -2916 +2916 @@
-"O URL \"%s\" não parece ser uma fonte de podcast. Pode ser o URL errado ou a "
+"O URL \"%s\" não parece set uma fonte de podcast. Pode set o URL errado ou a "
@@ -2988 +2988 @@
-msgstr "Erro no podcast"
+msgstr "Error no podcast"
@@ -3085 +3085 @@
-msgstr "Alternar o modo reprodução/pausa"
+msgstr "Alternator o modo reprodução/pausa"
@@ -3245 +3245 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3315 +3315 @@
-msgstr "unicode inválido na mensagem de erro"
+msgstr "unicode inválido na mensagem de error"
@@ -3523 +3523 @@
-"comandos disponíveis.\n"
+"commandos disponíveis.\n"
@@ -3589 +3589 @@
-msgstr "Erro ao gravar informação da canção"
+msgstr "Error ao gravar informação da canção"
@@ -3632 +3632 @@
-msgstr "Erro de fluxo"
+msgstr "Error de fluxo"
@@ -3758,5 +3758,5 @@
-"%d ficheiro não pode ser transferido porque deve ser convertido para um "
-"formato suportado pelo dispositivo de destino mas nenhum perfil de "
-"codificação adequado está disponível"
-msgstr[1] ""
-"%d ficheiros não podem ser transferidos porque devem ser convertidos para um "
+"%d ficheiro não pode set transferido porque deve set convertido para um "
+"formato suportado pelo dispositivo de destino mas nenhum perfil de "
+"codificação adequado está disponível"
+msgstr[1] ""
+"%d ficheiros não podem set transferidos porque devem set convertidos para um "
@@ -3773 +3773 @@
-"São necessários programas adicionais para codificar multimédia no seu "
+"São necessários programs adicionais para codificar multimédia no seu "
@@ -3788,5 +3788,5 @@
-"São necessários programas adicionais para converter %d ficheiro para um "
-"formato suportado pelo dispositivo de destino:\n"
-"%s"
-msgstr[1] ""
-"São necessários programas adicionais para converter %d ficheiros para um "
+"São necessários programs adicionais para converter %d ficheiro para um "
+"formato suportado pelo dispositivo de destino:\n"
+"%s"
+msgstr[1] ""
+"São necessários programs adicionais para converter %d ficheiros para um "
@@ -3815 +3815 @@
-msgstr "Procurar artistas"
+msgstr "Procurar artists"
@@ -3864 +3864 @@
-msgstr "Instalar programas adicionais"
+msgstr "Instalar programs adicionais"
@@ -3869 +3869 @@
-"São necessários programas adicionais para reproduzir alguns  destes "
+"São necessários programs adicionais para reproduzir alguns  destes "
@@ -3874 +3874 @@
-msgstr "Erros de importação"
+msgstr "Errors de importação"
@@ -3880,2 +3880,2 @@
-msgstr[0] "%d erro de importação"
-msgstr[1] "%d erros de importação"
+msgstr[0] "%d error de importação"
+msgstr[1] "%d errors de importação"
@@ -3940 +3940 @@
-msgstr "Erro ao transferir a faixa"
+msgstr "Error ao transferir a faixa"
@@ -4172 +4172 @@
-msgstr "Erro de reprodução"
+msgstr "Error de reprodução"
@@ -4224 +4224 @@
-msgstr[1] "Todos os %d artistas (%d)"
+msgstr[1] "Todos os %d artists (%d)"
@@ -4737 +4737 @@
-#~ msgstr "Erro ao criar pasta de transferência de podcast"
+#~ msgstr "Error ao criar pasta de transferência de podcast"
@@ -4773 +4773 @@
-#~ msgstr "A aplicação não aceita documentos na linha de comando"
+#~ msgstr "A aplicação não aceita documentos na linha de commando"
--- ./po/ne.po	original
+++ ./po/ne.po	fixed
@@ -283 +283 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/te.po	original
+++ ./po/te.po	fixed
@@ -1234 +1234 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -4973 +4973 @@
-#~ "    * దాదాపు అన్ని ఆన్-లైన్ స్టోరుల కలిగివున్న (gignatic) యెంపికవలె కాకుండా, మాగ్నాట్యూన్‌కు "
+#~ "    * దాదాపు అన్ని ఆన్-లైన్ స్టోరుల కలిగివున్న (gigantic) యెంపికవలె కాకుండా, మాగ్నాట్యూన్‌కు "
@@ -5076 +5076 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/pa.po	original
+++ ./po/pa.po	fixed
@@ -1547 +1547 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -4902 +4902 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/af.po	original
+++ ./po/af.po	fixed
@@ -227 +227 @@
-msgstr "Kunstenaar/Kunstenaar - Album/Kunstenaar (Album) - 01 - Titel.ogg"
+msgstr "Kunstenaar/Kunstenaar - Album/Kunstenaar (Album) - 01 - Title.ogg"
@@ -321 +321 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -363 +363 @@
-msgstr "Titel:"
+msgstr "Title:"
@@ -491 +491 @@
-msgstr "_Titel:"
+msgstr "_Title:"
@@ -723 +723 @@
-msgstr "Interne GStreamer-probleem; rapporteer 'n fout"
+msgstr "Interne GStreamer-problem; rapporteer 'n fout"
@@ -906 +906 @@
-msgstr "Titel"
+msgstr "Title"
@@ -932 +932 @@
-msgstr "Onbekende titel"
+msgstr "Onbekende title"
@@ -3495 +3495 @@
-"Daar was 'n probleem met die byvoeg van hierdie potgooi: %s.  Kontroleer "
+"Daar was 'n problem met die byvoeg van hierdie potgooi: %s.  Kontroleer "
@@ -3581 +3581 @@
-msgstr "Druk die titel en kunstenaar van die liedjie wat speel"
+msgstr "Druk die title en kunstenaar van die liedjie wat speel"
@@ -4386 +4386 @@
-"SONDER ENIGE WAARBORG; sonder selfs die geïmpliseerde waarborg\n"
+"SONDER ENIGE WAARBORG; sonder self die geïmpliseerde waarborg\n"
@@ -4462 +4462 @@
-msgstr "Filter musiekaansig volgens genre, kunstenaar, album of titel"
+msgstr "Filter musiekaansig volgens genre, kunstenaar, album of title"
@@ -4492 +4492 @@
-msgstr "Titels"
+msgstr "Titles"
@@ -4497 +4497 @@
-msgstr "Deursoek titels"
+msgstr "Deursoek titles"
@@ -4558 +4558 @@
-msgstr "Nommer - Titel"
+msgstr "Nommer - Title"
@@ -4562 +4562 @@
-msgstr "Kunstenaar - Titel"
+msgstr "Kunstenaar - Title"
@@ -4566 +4566 @@
-msgstr "Kunstenaar - Nommer - Titel"
+msgstr "Kunstenaar - Nommer - Title"
@@ -4570 +4570 @@
-msgstr "Kunstenaar (Album) - Nommer - Titel"
+msgstr "Kunstenaar (Album) - Nommer - Title"
@@ -4574 +4574 @@
-msgstr "Nommer, Kunstenaar - Titel"
+msgstr "Nommer, Kunstenaar - Title"
@@ -4995 +4995 @@
-msgstr "Titel"
+msgstr "Title"
@@ -5087 +5087 @@
-msgstr "Titel"
+msgstr "Title"
--- ./po/he.po	original
+++ ./po/he.po	fixed
@@ -309 +309 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/cs.po	original
+++ ./po/cs.po	fixed
@@ -269 +269 @@
-msgstr "Minut"
+msgstr "Minute"
@@ -461 +461 @@
-msgstr "_Hierarchie složek:"
+msgstr "_Hierarchy složek:"
@@ -646 +646 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -1243 +1243 @@
-msgstr "Nelze najít zásuvný modul GStreamer pro zdroj typu CD"
+msgstr "Nelze najít zásuvný module GStreamer pro zdroj typu CD"
@@ -1747 +1747 @@
-"povolen zásuvný modul Last.fm, vyberte jej v postranním panelu a přihlaste "
+"povolen zásuvný module Last.fm, vyberte jej v postranním panelu a přihlaste "
@@ -2777 +2777 @@
-msgstr "Zásuvný modul ReplayGain GStreamer není dostupný"
+msgstr "Zásuvný module ReplayGain GStreamer není dostupný"
@@ -2809 +2809 @@
-msgstr "Použít komprim_aci, aby se zabránilo ořezání"
+msgstr "Použít komprim_acpi, aby se zabránilo ořezání"
@@ -2918 +2918 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3310 +3310 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3398 +3398 @@
-msgstr[2] "%ld minut"
+msgstr[2] "%ld minute"
@@ -3455 +3455 @@
-msgstr "Vzorový modul v Pythonu"
+msgstr "Vzorový module v Pythonu"
@@ -3459 +3459 @@
-msgstr "Vzorový přídavný modul v Pythonu bez žádných funkcí"
+msgstr "Vzorový přídavný module v Pythonu bez žádných funkcí"
@@ -3469 +3469 @@
-msgstr "Vzorový přídavný modul"
+msgstr "Vzorový přídavný module"
@@ -3473 +3473 @@
-msgstr "Vzorový přídavný modul v C bez žádných funkcí"
+msgstr "Vzorový přídavný module v C bez žádných funkcí"
@@ -3477 +3477 @@
-msgstr "Vzorový modul ve Vala"
+msgstr "Vzorový module ve Vala"
@@ -3481 +3481 @@
-msgstr "Vzorový přídavný modul ve Vala bez žádných funkcí"
+msgstr "Vzorový přídavný module ve Vala bez žádných funkcí"
@@ -3523 +3523 @@
-"Kopii GNU General Public License jste měli obdržet spolu s programem\n"
+"Kopii GNU General Public License jste měli obdržet spolu s programme\n"
@@ -4627 +4627 @@
-msgstr "minut"
+msgstr "minute"
--- ./po/id.po	original
+++ ./po/id.po	fixed
@@ -31 +31 @@
-msgstr "Tak bisa membuat elemen muara GStreamer untuk ditulisi %s"
+msgstr "Tak bisa membuat element muara GStreamer untuk ditulisi %s"
@@ -45 +45 @@
-msgstr "Gagal membuat elemen playbin; periksa instalasi GStreamer Anda"
+msgstr "Gagal membuat element playbin; periksa instalasi GStreamer Anda"
@@ -50 +50 @@
-msgstr "Gagal membuat elemen %s; periksa instalasi GStreamer Anda"
+msgstr "Gagal membuat element %s; periksa instalasi GStreamer Anda"
@@ -73 +73 @@
-msgstr "Gagal membuat elemen GStreamer; periksa instalasi Anda"
+msgstr "Gagal membuat element GStreamer; periksa instalasi Anda"
@@ -78 +78 @@
-msgstr "Gagal membuat elemen keluaran audio; periksa instalasi Anda"
+msgstr "Gagal membuat element keluaran audio; periksa instalasi Anda"
@@ -129 +129 @@
-"portabel (termasuk telepon), dan layanan musik internet seperti Last.fm dan "
+"portable (termasuk telepon), dan layanan musik internet seperti Last.fm dan "
@@ -1047 +1047 @@
-msgstr "Gagal membuat elemen sumber; periksa instalasi Anda"
+msgstr "Gagal membuat element sumber; periksa instalasi Anda"
@@ -1053 +1053 @@
-msgstr "Gagal membuat elemen 'decodebin'; periksa instalasi GStreamer Anda"
+msgstr "Gagal membuat element 'decodebin'; periksa instalasi GStreamer Anda"
@@ -1060 +1060 @@
-msgstr "Gagal membuat elemen 'giostreamsink'; periksa instalasi GStreamer Anda"
+msgstr "Gagal membuat element 'giostreamsink'; periksa instalasi GStreamer Anda"
@@ -1103 +1103 @@
-msgstr "Sistem"
+msgstr "System"
@@ -1769 +1769 @@
-"Berbagi musik dan memutar musik yang dibagikan pada jaringan lokal Anda"
+"Berbagi musik dan memutar musik yang dibagikan pada jaringan local Anda"
@@ -1868 +1868 @@
-msgstr "Menyediakan implementasi spesifikasi antar muka D-Bus MediaServer2"
+msgstr "Menyediakan implements spesifikasi antar muka D-Bus MediaServer2"
@@ -1911 +1911 @@
-msgstr "Pemutar Portabel"
+msgstr "Pemutar Portable"
@@ -1940 +1940 @@
-msgstr "Ramban berbagai sumber media lokal dan Internet"
+msgstr "Ramban berbagai sumber media local dan Internet"
@@ -2059 +2059 @@
-msgstr "Pemutar Musik Portabel - iPod"
+msgstr "Pemutar Musik Portable - iPod"
@@ -2542 +2542 @@
-msgstr "Menyediakan implementasi dari spesifikasi antar muka D-Bus MPRIS"
+msgstr "Menyediakan implements dari spesifikasi antar muka D-Bus MPRIS"
@@ -2546 +2546 @@
-msgstr "Pemutar Musik Portabel - MTP"
+msgstr "Pemutar Musik Portable - MTP"
@@ -2671 +2671 @@
-msgstr "Anda dapat mengakses jendela utama melalui variabel 'shell':"
+msgstr "Anda dapat mengakses jendela utama melalui variable 'shell':"
@@ -2706 +2706 @@
-"Modul %s Python tidak tersedia. Pasang modul dan kemudian mulai ulang "
+"Module %s Python tidak tersedia. Pasang module dan kemudian mulai ulang "
@@ -2735,2 +2735,2 @@
-"Elemen GStreamer yang diperlukan untuk pemrosesan ReplayGain tak tersedia. "
-"Elemen yang kurang adalah: %s"
+"Element GStreamer yang diperlukan untuk pemrosesan ReplayGain tak tersedia. "
+"Element yang kurang adalah: %s"
@@ -3211 +3211 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -4037 +4037 @@
-msgstr "Laju bit variabel"
+msgstr "Laju bit variable"
@@ -4041 +4041 @@
-msgstr "Laju bit variabel terbatas"
+msgstr "Laju bit variable terbatas"
--- ./po/fr.po	original
+++ ./po/fr.po	fixed
@@ -154 +154 @@
-"radiophoniques, les lecteurs audio portables (y compris les téléphones), et "
+"radiophoniques, les lectures audio portables (y compris les téléphones), et "
@@ -313 +313 @@
-msgstr "Nouvelle _liste de lecture intelligente"
+msgstr "Nouvelle _liste de lecture intelligence"
@@ -374 +374 @@
-msgstr "Colonnes visibles"
+msgstr "Colonnes visible"
@@ -539 +539 @@
-msgstr "Informations"
+msgstr "Information"
@@ -577 +577 @@
-msgstr "Moteur de lecture"
+msgstr "Motor de lecture"
@@ -1033 +1033 @@
-msgstr "Impossible d’obtenir de l’espace libre sur %s : %s"
+msgstr "Impossible d’obtenir de l’escape libre sur %s : %s"
@@ -1163 +1163 @@
-msgstr "Listes de lecture :"
+msgstr "Listed de lecture :"
@@ -1181 +1181 @@
-msgstr "Erreur lors du montage de l’appareil Android"
+msgstr "Erreur lors du montage de l’apparel Android"
@@ -1251 +1251 @@
-msgstr "<Unicode non valide>"
+msgstr "<Unicode non valid>"
@@ -1314 +1314 @@
-"Soumet les informations de morceaux à last.fm et lit les flux radio last.fm"
+"Soumet les information de morceaux à last.fm et lit les flux radio last.fm"
@@ -1383 +1383 @@
-msgstr "Recommandations"
+msgstr "Recommendations"
@@ -1407 +1407 @@
-msgstr "Erreur d’authentification"
+msgstr "Erreur d’authentication"
@@ -1446 +1446 @@
-msgstr "Attente de l’authentification…"
+msgstr "Attente de l’authentication…"
@@ -1454 +1454 @@
-msgstr "Erreur d’authentification, essayez à nouveau plus tard."
+msgstr "Erreur d’authentication, essayez à nouveau plus tard."
@@ -1466 +1466 @@
-msgstr "Mes recommandations"
+msgstr "Mes recommendations"
@@ -1533 +1533 @@
-msgstr "Recommandations de l’utilisateur :"
+msgstr "Recommendations de l’utilisateur :"
@@ -1625 +1625 @@
-msgstr "URL de station non valide"
+msgstr "URL de station non valid"
@@ -1661 +1661 @@
-msgstr "Erreur de réglage de la station : réponse non valide"
+msgstr "Erreur de réglage de la station : réponse non valid"
@@ -1670 +1670 @@
-"Enregistrer des CD audio à partir de listes de lecture et copier des CD audio"
+"Enregistrer des CD audio à partir de listed de lecture et copier des CD audio"
@@ -1734 +1734 @@
-msgstr "Panneau contextuel"
+msgstr "Panneau contextual"
@@ -1739 +1739 @@
-"Affiche des informations en relation avec l’artiste et le morceau en cours "
+"Affiche des information en relation avec l’artiste et le morceau en cours "
@@ -1747 +1747 @@
-"Ces informations ne sont disponibles que pour les utilisateurs de Last.fm. "
+"Ces information ne sont disponibles que pour les utilisateurs de Last.fm. "
@@ -1800 +1800 @@
-msgstr "Impossible d’obtenir les informations de l’album :"
+msgstr "Impossible d’obtenir les information de l’album :"
@@ -1804 +1804 @@
-msgstr "Pas d’informations disponibles"
+msgstr "Pas d’information disponibles"
@@ -1808 +1808 @@
-msgstr "Impossible d’obtenir les informations sur l’artiste :"
+msgstr "Impossible d’obtenir les information sur l’artiste :"
@@ -1849 +1849 @@
-msgstr "Saisissez la phrase de passe affichée sur votre appareil."
+msgstr "Saisissez la phrase de passe affichée sur votre apparel."
@@ -1936 +1936 @@
-msgstr "Listes de lecture"
+msgstr "Listed de lecture"
@@ -1961 +1961 @@
-msgstr "Lecteurs portables"
+msgstr "Lectures portables"
@@ -2013 +2013 @@
-"Met à jour l’état de messagerie instantanée en fonction du morceau actuel "
+"Met à jour l’état de messagerie instantanée en function du morceau actuel "
@@ -2102 +2102 @@
-"initialiser l’iPod, complétez les informations ci-dessous. Si ce n’est pas "
+"initialiser l’iPod, complétez les information ci-dessous. Si ce n’est pas "
@@ -2111 +2111 @@
-msgstr "Lecteurs portables - iPod"
+msgstr "Lectures portables - iPod"
@@ -2250 +2250 @@
-msgstr "Moteurs de recherche"
+msgstr "Motors de recherche"
@@ -2314 +2314 @@
-"téléchargement sur le catalogue complet (aucun autre service ne le permet)"
+"téléchargement sur le catalogue complete (aucun autre service ne le permet)"
@@ -2340 +2340 @@
-msgstr "Vous trouverez de plus amples informations sur "
+msgstr "Vous trouverez de plus amples information sur "
@@ -2352 +2352 @@
-msgstr "Informations sur l’artiste"
+msgstr "Information sur l’artiste"
@@ -2492 +2492 @@
-msgstr "Informations sur Magnatune"
+msgstr "Information sur Magnatune"
@@ -2575 +2575 @@
-"Une erreur est survenue lors de l’autorisation du téléchargement.\n"
+"Une erreur est survenue lors de l’authorisation du téléchargement.\n"
@@ -2608 +2608 @@
-msgstr "Lecteurs portables - MTP"
+msgstr "Lectures portables - MTP"
@@ -2645 +2645 @@
-msgstr "Espace insuffisant dans %s"
+msgstr "Escape insuffisant dans %s"
@@ -2655 +2655 @@
-msgstr "Plus d’espace disponible sur le périphérique MTP"
+msgstr "Plus d’escape disponible sur le périphérique MTP"
@@ -2925,2 +2925,2 @@
-"L’URL « %s » n’apparaît pas être un flux podcast valide. Il est possible que "
-"l’URL soit incorrect ou que le flux ne soit pas valide. Voulez-vous que "
+"L’URL « %s » n’apparaît pas être un flux podcast valid. Il est possible que "
+"l’URL soit incorrect ou que le flux ne soit pas valid. Voulez-vous que "
@@ -3083 +3083 @@
-msgstr "Se positionne dans la piste actuelle"
+msgstr "Se positioned dans la piste actuelle"
@@ -3123 +3123 @@
-msgstr "Affiche des informations mises en forme sur le morceau"
+msgstr "Affiche des information mises en forme sur le morceau"
@@ -3127 +3127 @@
-msgstr "Sélectionner la source correspondant à l’URI indiqué"
+msgstr "Sélectionner la source correspondent à l’URI indiqué"
@@ -3136 +3136 @@
-msgstr "Activer la source correspondant à l’URI indiqué"
+msgstr "Activer la source correspondent à l’URI indiqué"
@@ -3144 +3144 @@
-msgstr "Jouer à partir de la source correspondant à l’URI indiqué"
+msgstr "Jouer à partir de la source correspondent à l’URI indiqué"
@@ -3202 +3202 @@
-msgstr "espace - Lecture/pause"
+msgstr "escape - Lecture/pause"
@@ -3256 +3256 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3304 +3304 @@
-msgstr "Dure limite"
+msgstr "Dure limit"
@@ -3325 +3325 @@
-msgstr "Unicode non valide dans le message d’erreur"
+msgstr "Unicode non valid dans le message d’erreur"
@@ -3399 +3399 @@
-msgstr "Un exemple de greffon sans fonctionnalité écrit en Python"
+msgstr "Un example de greffon sans fonctionnalité écrit en Python"
@@ -3413 +3413 @@
-msgstr "Un exemple de greffon sans fonctionnalité écrit en C"
+msgstr "Un example de greffon sans fonctionnalité écrit en C"
@@ -3421 +3421 @@
-msgstr "Un exemple de greffon sans fonctionnalité écrit en Vala"
+msgstr "Un example de greffon sans fonctionnalité écrit en Vala"
@@ -3485 +3485 @@
-msgstr "Contributeurs :"
+msgstr "Contributes :"
@@ -3505 +3505 @@
-msgstr "Activer la sortie de débogage correspondant à une chaîne indiquée"
+msgstr "Activer la sortie de débogage correspondent à une chaîne indiquée"
@@ -3530 +3530 @@
-msgstr "Chemin des listes de lecture à utiliser"
+msgstr "Chemin des listed de lecture à utiliser"
@@ -3605 +3605 @@
-msgstr "La liste de lecture %s est une liste de lecture intelligente"
+msgstr "La liste de lecture %s est une liste de lecture intelligence"
@@ -3609 +3609 @@
-msgstr "Erreur lors de l’enregistrement des informations du morceau"
+msgstr "Erreur lors de l’enregistrement des information du morceau"
@@ -3648 +3648 @@
-msgstr "Type de propriété %s non valide pour la propriété %s"
+msgstr "Type de propriété %s non valid pour la propriété %s"
@@ -3710 +3710 @@
-msgstr "Aléatoire en fonction de la date de dernière écoute"
+msgstr "Aléatoire en function de la date de dernière écoute"
@@ -3714 +3714 @@
-msgstr "Aléatoire en fonction de la notation"
+msgstr "Aléatoire en function de la notation"
@@ -3718 +3718 @@
-msgstr "Aléatoire en fonction de la date de dernière écoute et de la notation"
+msgstr "Aléatoire en function de la date de dernière écoute et de la notation"
@@ -3782 +3782 @@
-"convertis dans un format pris en charge par le périphérique cible et "
+"converts dans un format pris en charge par le périphérique cible et "
@@ -3953 +3953 @@
-msgstr "Exemple de chemin :"
+msgstr "Example de chemin :"
@@ -3979 +3979 @@
-"transférer sur cet appareil."
+"transférer sur cet apparel."
@@ -3986,2 +3986,2 @@
-"Il n’y a pas assez de place sur l’appareil pour transférer le contenu "
-"sélectionné (musique, listes de lecture et podcasts)."
+"Il n’y a pas assez de place sur l’apparel pour transférer le contenu "
+"sélectionné (musique, listed de lecture et podcasts)."
@@ -4119 +4119 @@
-msgstr "Débit binaire variable contraint"
+msgstr "Débit binaire variable constraint"
@@ -4278 +4278 @@
-msgstr "Créer une nouvelle liste de lecture intelligente"
+msgstr "Créer une nouvelle liste de lecture intelligence"
@@ -4282 +4282 @@
-msgstr "Modifier la liste de lecture intelligente"
+msgstr "Modifier la liste de lecture intelligence"
@@ -4702 +4702 @@
-#~ msgstr "URL non valide"
+#~ msgstr "URL non valid"
@@ -4705 +4705 @@
-#~ msgstr "L’URL « %s » n’est pas valide, veuillez le vérifier."
+#~ msgstr "L’URL « %s » n’est pas valid, veuillez le vérifier."
@@ -4735 +4735 @@
-#~ msgstr "Qualité normale"
+#~ msgstr "Qualité normal"
--- ./po/gd.po	original
+++ ./po/gd.po	fixed
@@ -3458 +3458 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/zh_CN.po	original
+++ ./po/zh_CN.po	fixed
@@ -3182 +3182 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/pt_BR.po	original
+++ ./po/pt_BR.po	fixed
@@ -179 +179 @@
-"Áudio;Som;MP3;CD;Podcast;MTP;iPod;Lista de reprodução;Playlist;Last.fm;UPnP;"
+"Áudio;Some;MP3;CD;Podcast;MTP;iPod;Lista de reprodução;Playlist;Last.fm;UPnP;"
@@ -344 +344 @@
-msgstr "_Instalar softwares adicionais necessários para usar este formato"
+msgstr "_Instalar software adicionais necessários para usar este formato"
@@ -356 +356 @@
-msgstr "_Artistas e álbuns"
+msgstr "_Artists e álbuns"
@@ -360 +360 @@
-msgstr "Gênero_s e artistas"
+msgstr "Gênero_s e artists"
@@ -364 +364 @@
-msgstr "Gên_eros, artistas e álbuns"
+msgstr "Gên_eros, artists e álbuns"
@@ -653 +653 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -865 +865 @@
-msgstr "_Ordenar artistas por:"
+msgstr "_Ordenar artists por:"
@@ -897 +897 @@
-msgstr "Mensagem de erro"
+msgstr "Mensagem de error"
@@ -1172 +1172 @@
-msgstr "Erro ao montar o dispositivo Android"
+msgstr "Error ao montar o dispositivo Android"
@@ -1204 +1204 @@
-msgstr "_Ordenar artistas por:"
+msgstr "_Ordenar artists por:"
@@ -1295 +1295 @@
-msgstr "Erro de servidor do Musicbrainz"
+msgstr "Error de servidor do Musicbrainz"
@@ -1371 +1371 @@
-msgstr "Artistas principais"
+msgstr "Artists principais"
@@ -1399 +1399 @@
-msgstr "Erro de autenticação"
+msgstr "Error de autenticação"
@@ -1446 +1446 @@
-msgstr "Erro de autenticação. Por favor, tente iniciar sessão novamente."
+msgstr "Error de autenticação. Por favor, tente iniciar sessão novamente."
@@ -1450 +1450 @@
-msgstr "Erro de conexão. Por favor, tente iniciar sessão novamente."
+msgstr "Error de conexão. Por favor, tente iniciar sessão novamente."
@@ -1479 +1479 @@
-msgstr "Ouvir rádio de artistas _similares"
+msgstr "Ouvir rádio de artists _similares"
@@ -1485,7 +1485,7 @@
-# O Last.fm em português chama "Similar Artists" de "Artistas Parecidos"
-#. Translators: describes a radio stream playing tracks similar to those by an artist.
-#. * Followed by a text entry box for the artist name.
-#.
-#: plugins/audioscrobbler/rb-audioscrobbler-radio-source.c:55
-msgid "Similar to Artist:"
-msgstr "Artistas parecidos:"
+# O Last.fm em português chama "Similar Artists" de "Artists Parecidos"
+#. Translators: describes a radio stream playing tracks similar to those by an artist.
+#. * Followed by a text entry box for the artist name.
+#.
+#: plugins/audioscrobbler/rb-audioscrobbler-radio-source.c:55
+msgid "Similar to Artist:"
+msgstr "Artists parecidos:"
@@ -1614 +1614 @@
-msgstr "Erro sintonizando estação: sem resposta"
+msgstr "Error sintonizando estação: sem resposta"
@@ -1647 +1647 @@
-msgstr "Erro sintonizando estação: %i – %s"
+msgstr "Error sintonizando estação: %i – %s"
@@ -1651 +1651 @@
-msgstr "Erro sintonizando estação: resposta inesperada"
+msgstr "Error sintonizando estação: resposta inesperada"
@@ -1655 +1655 @@
-msgstr "Erro sintonizando estação: resposta inválida"
+msgstr "Error sintonizando estação: resposta inválida"
@@ -1919 +1919 @@
-msgstr "Artistas"
+msgstr "Artists"
@@ -2091 +2091 @@
-"ou é um iPod corrompido. Ele deve ser inicializado antes para que o "
+"ou é um iPod corrompido. Ele deve set inicializado antes para que o "
@@ -2325 +2325 @@
-msgstr "    * Todos os álbuns e artistas escolhidos a dedo"
+msgstr "    * Todos os álbuns e artists escolhidos a dedo"
@@ -2545 +2545 @@
-"relatório de erro."
+"relatório de error."
@@ -2554 +2554 @@
-msgstr "Erro no download"
+msgstr "Error no download"
@@ -2563 +2563 @@
-"Ocorreu um erro durante a tentativa de autorizar o download.\n"
+"Ocorreu um error durante a tentativa de autorizar o download.\n"
@@ -2569 +2569 @@
-msgstr "Erro"
+msgstr "Error"
@@ -2578,2 +2578,2 @@
-"Um erro aconteceu durante a tentativa de baixar o álbum.\n"
-"A mensagem de erro é:\n"
+"Um error aconteceu durante a tentativa de baixar o álbum.\n"
+"A mensagem de error é:\n"
@@ -2610 +2610 @@
-msgstr "Erro de dispositivo reprodutor de mídia"
+msgstr "Error de dispositivo reprodutor de mídia"
@@ -2883 +2883 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2908 +2908 @@
-msgstr "Erro ao baixar podcast"
+msgstr "Error ao baixar podcast"
@@ -2916 +2916 @@
-msgstr "Erro no podcast"
+msgstr "Error no podcast"
@@ -2941 +2941 @@
-"O URL “%s” não parece ser uma fonte (“feed”) de podcast. Pode ser um erro no "
+"O URL “%s” não parece set uma fonte (“feed”) de podcast. Pode set um error no "
@@ -2971 +2971 @@
-msgstr "A fonte não contém qualquer item que possa ser baixado"
+msgstr "A fonte não contém qualquer item que possa set baixado"
@@ -3013 +3013 @@
-msgstr "Erro no podcast"
+msgstr "Error no podcast"
@@ -3110 +3110 @@
-msgstr "Alternar entre os modos reproduzir e pausar"
+msgstr "Alternator entre os modos reproduzir e pausar"
@@ -3122 +3122 @@
-msgstr "URI a ser reproduzido"
+msgstr "URI a set reproduzido"
@@ -3142 +3142 @@
-msgstr "Selecionar a fonte correspondente ao URI especificado"
+msgstr "Selecionar a fonte correspondence ao URI especificado"
@@ -3150 +3150 @@
-msgstr "Ativar a fonte correspondente ao URI especificado"
+msgstr "Ativar a fonte correspondence ao URI especificado"
@@ -3158 +3158 @@
-msgstr "Reproduzir a fonte correspondente ao URI especificado"
+msgstr "Reproduzir a fonte correspondence ao URI especificado"
@@ -3270 +3270 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3340 +3340 @@
-msgstr "unicode inválido na mensagem de erro"
+msgstr "unicode inválido na mensagem de error"
@@ -3481 +3481 @@
-"O Rhythmbox é distribuído na expectativa de ser útil,\n"
+"O Rhythmbox é distribuído na expectativa de set útil,\n"
@@ -3562 +3562 @@
-"linha de comando.\n"
+"linha de commando.\n"
@@ -3629 +3629 @@
-msgstr "Erro ao salvar as informações da música"
+msgstr "Error ao salvar as informações da música"
@@ -3672 +3672 @@
-msgstr "Erro de fluxo"
+msgstr "Error de fluxo"
@@ -3686 +3686 @@
-msgstr "Nenhuma reprodução no momento"
+msgstr "Nenhuma reprodução no memento"
@@ -3797,5 +3797,5 @@
-"%d arquivo não pode ser transferido, ele deve ser convertido em um formato "
-"com suporte pelo dispositivo alvo mas não há perfis de codificação adequados "
-"disponível"
-msgstr[1] ""
-"%d arquivos não podem ser transferidos, eles devem ser convertidos em um "
+"%d arquivo não pode set transferido, ele deve set convertido em um formato "
+"com suporte pelo dispositivo alvo mas não há perfis de codificação adequados "
+"disponível"
+msgstr[1] ""
+"%d arquivos não podem set transferidos, eles devem set convertidos em um "
@@ -3854 +3854 @@
-msgstr "Pesquisar artistas"
+msgstr "Pesquisar artists"
@@ -3912 +3912 @@
-msgstr "Erros de importação"
+msgstr "Errors de importação"
@@ -3918,2 +3918,2 @@
-msgstr[0] "%d erro de importação"
-msgstr[1] "%d erros de importação"
+msgstr[0] "%d error de importação"
+msgstr[1] "%d errors de importação"
@@ -3978 +3978 @@
-msgstr "Erro ao transferir faixa"
+msgstr "Error ao transferir faixa"
@@ -4210 +4210 @@
-msgstr "Erro de reprodução"
+msgstr "Error de reprodução"
@@ -4262 +4262 @@
-msgstr[1] "Todos %d artistas (%d)"
+msgstr[1] "Todos %d artists (%d)"
--- ./po/mn.po	original
+++ ./po/mn.po	fixed
@@ -43 +43 @@
-msgid "An exception occured '%s'"
+msgid "An exception occurred '%s'"
--- ./po/az.po	original
+++ ./po/az.po	fixed
@@ -941 +941 @@
-msgid "An exception occured '%s'"
+msgid "An exception occurred '%s'"
@@ -1184 +1184 @@
-#. an error occured
+#. an error occurred
--- ./po/bs.po	original
+++ ./po/bs.po	fixed
@@ -635 +635 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -1502 +1502 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -1667 +1667 @@
-msgstr "Učitavam tekst pjesme %s od %s"
+msgstr "Učitavam text pjesme %s od %s"
@@ -1880 +1880 @@
-msgstr "Sistem"
+msgstr "System"
@@ -2165 +2165 @@
-msgstr "Preuzmi tekst za pjesmu sa Interneta"
+msgstr "Preuzmi text za pjesmu sa Interneta"
@@ -2182 +2182 @@
-msgstr "Nije nađen tekst pjesme"
+msgstr "Nije nađen text pjesme"
@@ -2194 +2194 @@
-msgstr "Tražim tekst pjesme..."
+msgstr "Tražim text pjesme..."
@@ -2288 +2288 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2388 +2388 @@
-msgstr "$18 US (Volimo Vas!)"
+msgstr "$18 US (Volimo Was!)"
@@ -2876 +2876 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3298 +3298 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3382 +3382 @@
-msgstr[0] "%ld minut"
+msgstr[0] "%ld minute"
@@ -4631 +4631 @@
-msgstr "Obriši tekst za pretragu"
+msgstr "Obriši text za pretragu"
--- ./po/en_CA.po	original
+++ ./po/en_CA.po	fixed
@@ -282,2 +282,2 @@
-msgid "C_onfigure..."
-msgstr "C_onfigure..."
+msgid "C_configure..."
+msgstr "C_configure..."
--- ./po/as.po	original
+++ ./po/as.po	fixed
@@ -301 +301 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/ps.po	original
+++ ./po/ps.po	fixed
@@ -270 +270 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/sl.po	original
+++ ./po/sl.po	fixed
@@ -134 +134 @@
-"tudi omrežne mape, poddaje, radijske tokove, prenosne glasbene naprave "
+"tudi omrežne map, poddaje, radijske tokove, prenosne glasbene naprave "
@@ -260 +260 @@
-msgstr "Minut"
+msgstr "Minute"
@@ -733 +733 @@
-msgstr "Izbor mape za podcaste"
+msgstr "Izbor map za podcaste"
@@ -1116 +1116 @@
-msgstr "Sistem"
+msgstr "System"
@@ -2211 +2211 @@
-msgstr "Izbor mape besedil ..."
+msgstr "Izbor map besedil ..."
@@ -2338 +2338 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2736 +2736 @@
-"Modul %s Python ni na voljo. Namestite modul in znova zaženite Rhythmbox, da "
+"Module %s Python ni na voljo. Namestite module in znova zaženite Rhythmbox, da "
@@ -3249 +3249 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3332 +3332 @@
-msgstr[0] "%ld minut"
+msgstr[0] "%ld minute"
@@ -3797,13 +3797,13 @@
-"Za pretvorbo teh %d datotek v zapis, ki ga podpira ciljna naprava, je "
-"zahtevana dodatna programska oprema:\n"
-"%s"
-msgstr[1] ""
-"Za pretvorbo teh %d datoteke v zapis, ki ga podpira ciljna naprava, je "
-"zahtevana dodatna programska oprema:\n"
-"%s"
-msgstr[2] ""
-"Za pretvorbo teh %d datotek v zapis, ki ga podpira ciljna naprava, je "
-"zahtevana dodatna programska oprema:\n"
-"%s"
-msgstr[3] ""
-"Za pretvorbo teh %d datotek v zapis, ki ga podpira ciljna naprava, je "
+"Za pretvorbo the %d datotek v zapis, ki ga podpira ciljna naprava, je "
+"zahtevana dodatna programska oprema:\n"
+"%s"
+msgstr[1] ""
+"Za pretvorbo the %d datoteke v zapis, ki ga podpira ciljna naprava, je "
+"zahtevana dodatna programska oprema:\n"
+"%s"
+msgstr[2] ""
+"Za pretvorbo the %d datotek v zapis, ki ga podpira ciljna naprava, je "
+"zahtevana dodatna programska oprema:\n"
+"%s"
+msgstr[3] ""
+"Za pretvorbo the %d datotek v zapis, ki ga podpira ciljna naprava, je "
@@ -3885 +3885 @@
-msgstr "Za predvajanje nekaterih od teh datotek so zahtevani dodatni programi."
+msgstr "Za predvajanje nekaterih od the datotek so zahtevani dodatni programi."
@@ -4581 +4581 @@
-msgstr "minut"
+msgstr "minute"
--- ./po/gu.po	original
+++ ./po/gu.po	fixed
@@ -300 +300 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/el.po	original
+++ ./po/el.po	fixed
@@ -1460 +1460 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
--- ./po/lt.po	original
+++ ./po/lt.po	fixed
@@ -2456 +2456 @@
-msgstr "$18 US (Mes jus mylime!)"
+msgstr "$18 US (Mes just mylime!)"
@@ -2735 +2735 @@
-"winpdb arba rpdb2. Jei faile %s nenustatytas derintuvės slaptažodis, bus "
+"winpdb arba rpdb2. Jei failed %s nenustatytas derintuvės slaptažodis, bus "
@@ -3316 +3316 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/be@latin.po	original
+++ ./po/be@latin.po	fixed
@@ -151,4 +151,4 @@
-"Tekst pad ikonami\n"
-"Tekst i ikony\n"
-"Tolki ikony\n"
-"Tolki tekst"
+"Text pad ikonami\n"
+"Text i ikony\n"
+"Tolki ikony\n"
+"Tolki text"
@@ -307 +307 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -727 +727 @@
-msgstr "Niemahčyma stvaryć elementy dla zapisu tagaŭ"
+msgstr "Niemahčyma stvaryć elementary dla zapisu tagaŭ"
@@ -2098 +2098 @@
-msgstr "jamendo - heta adzinaja platforma, jakaja spałučaje:"
+msgstr "jamendo - heta adzinaja platforms, jakaja spałučaje:"
@@ -2240 +2240 @@
-msgstr "Nia znojdzieny tekst"
+msgstr "Nia znojdzieny text"
@@ -2258 +2258 @@
-msgstr "Tekst"
+msgstr "Text"
@@ -2266 +2266 @@
-msgstr "Tekst _pieśni"
+msgstr "Text _pieśni"
@@ -2270 +2270 @@
-msgstr "Pakažy tekst hranaj pieśni"
+msgstr "Pakažy text hranaj pieśni"
@@ -2278 +2278 @@
-msgstr "Zahružaj tekst pieśni z Internetu"
+msgstr "Zahružaj text pieśni z Internetu"
@@ -2282 +2282 @@
-msgstr "Tekst pieśni"
+msgstr "Text pieśni"
@@ -2784 +2784 @@
-"Tekst pamyłki:\n"
+"Text pamyłki:\n"
@@ -2880 +2880 @@
-msgstr "Debuger Python"
+msgstr "Debugger Python"
--- ./po/zh_HK.po	original
+++ ./po/zh_HK.po	fixed
@@ -1463 +1463 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -5232 +5232 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/pl.po	original
+++ ./po/pl.po	fixed
@@ -308 +308 @@
-msgstr "_Wyszukaj nowe urządzenia"
+msgstr "_Wyszukaj now urządzenia"
@@ -364 +364 @@
-msgstr "_Numer ścieżki"
+msgstr "_Number ścieżki"
@@ -631,2 +631,2 @@
-"Można wyszukać podcasty w serwisie iTunes Store lub podać adres URL kanału.\n"
-"Po subskrypcji nowe odcinki będą pobierane tuż po ich opublikowaniu."
+"Można wyszukać podcasty w serwisie iTunes Store lub podać address URL kanału.\n"
+"Po subskrypcji now odcinki będą pobierane tuż po ich opublikowaniu."
@@ -644 +644 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -829 +829 @@
-msgstr "Numer _płyty:"
+msgstr "Number _płyty:"
@@ -876 +876 @@
-msgstr "_Numer ścieżki:"
+msgstr "_Number ścieżki:"
@@ -1110 +1110 @@
-msgstr "Numer seryjny:"
+msgstr "Number seryjny:"
@@ -1608 +1608 @@
-msgstr "Nieprawidłowy adres URL stacji"
+msgstr "Nieprawidłowy address URL stacji"
@@ -1743 +1743 @@
-msgstr "Tekst utworu"
+msgstr "Text utworu"
@@ -1838 +1838 @@
-msgstr "Można teraz sterować programem Rhythmbox za pomocą pilota"
+msgstr "Można teraz sterować programme Rhythmbox za pomocą pilota"
@@ -2079 +2079 @@
-"z programem Rhythmbox, lecz to działanie usunie wszystkie metadane utworów "
+"z programme Rhythmbox, lecz to działanie usunie wszystkie metadane utworów "
@@ -2155 +2155 @@
-msgstr "Adres URL internetowej stacji radiowej:"
+msgstr "Address URL internetowej stacji radiowej:"
@@ -2704 +2704 @@
-msgstr "Debuger języka Python (winpdb)"
+msgstr "Debugger języka Python (winpdb)"
@@ -2708 +2708 @@
-msgstr "Debuger języka Python (debugpy)"
+msgstr "Debugger języka Python (debugpy)"
@@ -2777 +2777 @@
-"Elementy biblioteki GStreamer wymagane do przetwarzania ReplayGain są "
+"Elementary biblioteki GStreamer wymagane do przetwarzania ReplayGain są "
@@ -2842 +2842 @@
-msgstr "Sterowanie programem Rhythmbox z przeglądarki WWW"
+msgstr "Sterowanie programme Rhythmbox z przeglądarki WWW"
@@ -2871 +2871 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2884 +2884 @@
-msgstr "Nowe odcinki"
+msgstr "Now odcinki"
@@ -2888 +2888 @@
-msgstr "Nowe pobierania"
+msgstr "Now pobierania"
@@ -2920 +2920 @@
-msgstr "Dostępne są nowe aktualizacje z"
+msgstr "Dostępne są now aktualizacje z"
@@ -2929,2 +2929,2 @@
-"Adres URL „%s” nie wygląda na kanał podcastów. Może to być nieprawidłowy "
-"adres URL albo kanał jest uszkodzony. Czy mimo wszystko spróbować użyć tego "
+"Address URL „%s” nie wygląda na kanał podcastów. Może to być nieprawidłowy "
+"address URL albo kanał jest uszkodzony. Czy mimo wszystko spróbować użyć tego "
@@ -2936 +2936 @@
-msgstr "Adres URL został już dodany"
+msgstr "Address URL został już dodany"
@@ -2944 +2944 @@
-"Adres URL „%s” został już dodany jako stacja radiowa. Jeśli jest to kanał "
+"Address URL „%s” został już dodany jako stacja radiowa. Jeśli jest to kanał "
@@ -3107 +3107 @@
-msgstr "Odtwarza podany adres URI, importując go, jeśli to konieczne"
+msgstr "Odtwarza podany address URI, importując go, jeśli to konieczne"
@@ -3111 +3111 @@
-msgstr "Adres URI do odtworzenia"
+msgstr "Address URI do odtworzenia"
@@ -3259 +3259 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3346 +3346 @@
-msgstr[2] "%ld minut"
+msgstr[2] "%ld minute"
@@ -3472 +3472 @@
-"Z pewnością wraz z programem Rhythmbox dostarczono także egzemplarz\n"
+"Z pewnością wraz z programme Rhythmbox dostarczono także egzemplarz\n"
@@ -3635 +3635 @@
-msgstr "Nieznany adres URI utworu: %s"
+msgstr "Nieznany address URI utworu: %s"
@@ -3926 +3926 @@
-msgstr "Numer - Tytuł"
+msgstr "Number - Tytuł"
@@ -3934 +3934 @@
-msgstr "Wykonawca - Numer - Tytuł"
+msgstr "Wykonawca - Number - Tytuł"
@@ -3938 +3938 @@
-msgstr "Wykonawca (Album) - Numer - Tytuł"
+msgstr "Wykonawca (Album) - Number - Tytuł"
@@ -3942 +3942 @@
-msgstr "Numer. Wykonawca - Tytuł"
+msgstr "Number. Wykonawca - Tytuł"
@@ -4354 +4354 @@
-msgstr "Numer ścieżki"
+msgstr "Number ścieżki"
@@ -4359 +4359 @@
-msgstr "Numer płyty"
+msgstr "Number płyty"
@@ -4465 +4465 @@
-msgstr "Numer ścieżki"
+msgstr "Number ścieżki"
--- ./po/sv.po	original
+++ ./po/sv.po	fixed
@@ -125 +125 @@
-msgstr "Spela och organisera din musiksamling"
+msgstr "Spela och organisers din musiksamling"
@@ -137 +137 @@
-"(inklusive mobiler) och musiktjänster på internet som Last.fm och Magnatune."
+"(inklusive mobiler) och musiktjänster på internet some Last.fm och Magnatune."
@@ -183 +183 @@
-msgstr "Följ spår som spelas"
+msgstr "Följ spår some spelas"
@@ -324 +324 @@
-"_Installera ytterligare programvara som krävs för att använda detta format"
+"_Installera ytterligare programvara some krävs för att använda detta format"
@@ -412 +412 @@
-msgstr "Välj en plats som innehåller musik att lägga till i ditt bibliotek:"
+msgstr "Välj en plats some innehåller musik att lägga till i ditt bibliotek:"
@@ -424 +424 @@
-msgstr "Kopiera filer som är utanför musikbiblioteket"
+msgstr "Kopiera filer some är utanför musikbiblioteket"
@@ -452 +452 @@
-msgstr "Mapp_hierarki:"
+msgstr "Map_hierarki:"
@@ -464 +464 @@
-msgstr "Artist/Artist - Album/Artist (Album) - 01 - Titel.ogg"
+msgstr "Artist/Artist - Album/Artist (Album) - 01 - Title.ogg"
@@ -630 +630 @@
-msgstr "Titel:"
+msgstr "Title:"
@@ -732 +732 @@
-msgstr "Välj mapp för poddsändningar"
+msgstr "Välj map för poddsändningar"
@@ -862 +862 @@
-msgstr "_Titel:"
+msgstr "_Title:"
@@ -870 +870 @@
-msgstr "S_lag/minut:"
+msgstr "S_lag/minute:"
@@ -1052 +1052 @@
-"format som stöds"
+"format some stöds"
@@ -1093 +1093 @@
-msgstr "Modell:"
+msgstr "Model:"
@@ -1197 +1197 @@
-msgstr "Stöd för att spela ljud-cd som musikkälla"
+msgstr "Stöd för att spela ljud-cd some musikkälla"
@@ -1290 +1290 @@
-msgstr "Vilka Audioscrobbler-tjänster vill du använda?"
+msgstr "Vilka Audioscrobbler-tjänster will du använda?"
@@ -1347 +1347 @@
-msgstr "Tidigare spår som spelats"
+msgstr "Tidigare spår some spelats"
@@ -1498 +1498 @@
-msgstr "Spår som användaren gillar:"
+msgstr "Spår some användaren gillar:"
@@ -1709 +1709 @@
-msgstr "Visa information relaterad till den låt och artist som spelas upp."
+msgstr "Visa information relaterad till den låt och artist some spelas upp."
@@ -1817 +1817 @@
-msgstr "Ange lösenkoden som visas på din enhet."
+msgstr "Ange lösenkoden some visas på din enhet."
@@ -2054 +2054 @@
-msgstr "_Modell:"
+msgstr "_Model:"
@@ -2064,5 +2064,5 @@
-"Rhythmbox har upptäckt en enhet som antagligen är en icke-initierad eller "
-"skadad iPod. Den måste initieras innan Rhythmbox kan använda den men detta "
-"kommer att förstöra all låtmetadata som redan finns på den. Fyll i "
-"informationen nedan om du vill att Rhythmbox ska initiera din iPod. Tryck på "
-"Avbryt om enheten inte är en iPod eller om du inte vill initiera den."
+"Rhythmbox har upptäckt en enhet some antagligen är en icke-initierad eller "
+"skadad iPod. Den måste initieras innan Rhythmbox kan använda den men detta "
+"kommer att förstöra all låtmetadata some redan finns på den. Fyll i "
+"informationen nedan om du will att Rhythmbox ska initiera din iPod. Tryck på "
+"Avbryt om enheten inte är en iPod eller om du inte will initiera den."
@@ -2072 +2072 @@
-msgstr "Vill du initiera din iPod?"
+msgstr "Will du initiera din iPod?"
@@ -2263 +2263 @@
-msgstr "Magnatune är ett skivbolag på nätet som är inte elakt.\n"
+msgstr "Magnatune är ett skivbolag på nätet some är inte elakt.\n"
@@ -2292 +2292 @@
-"    * Filformat som är snälla mot öppen källkod: MP3 och WAV, men även OGG "
+"    * Filformat some är snälla mot öppen källkod: MP3 och WAV, men även OGG "
@@ -2714 +2714 @@
-"Du kan nu ansluta till det med en kompatibel felsökare som vimspector, nvim-"
+"Du kan nu ansluta till det med en kompatibel felsökare some vimspector, nvim-"
@@ -2757 +2757 @@
-"GStreamer-elementen som krävs för ReplayGain-behandling finns inte "
+"GStreamer-elementen some krävs för ReplayGain-behandling finns inte "
@@ -2848 +2848 @@
-msgstr "Titel"
+msgstr "Title"
@@ -2897 +2897 @@
-msgstr "%s. Vill du lägga till poddsändningskanalen ändå?"
+msgstr "%s. Will du lägga till poddsändningskanalen ändå?"
@@ -2911 +2911 @@
-"eller så kan kanalen vara trasig. Vill du att Rhythmbox ska försöka använda "
+"eller så kan kanalen vara trasig. Will du att Rhythmbox ska försöka använda "
@@ -2925 +2925 @@
-"”%s” har redan lagts till som en radiostation. Om det är en "
+"”%s” har redan lagts till some en radiostation. Om det är en "
@@ -2940 +2940 @@
-msgstr "Kanalen innehåller inte några hämtningsbara objekt"
+msgstr "Kanalen innehåller inte några hämtningsbara object"
@@ -3111 +3111 @@
-msgstr "Välj källan som matchar angiven URI"
+msgstr "Välj källan some matchar angiven URI"
@@ -3119 +3119 @@
-msgstr "Aktivera källan som matchar angiven URI"
+msgstr "Aktivera källan some matchar angiven URI"
@@ -3127 +3127 @@
-msgstr "Spela upp från källan som matchar angiven URI"
+msgstr "Spela upp från källan some matchar angiven URI"
@@ -3189 +3189 @@
-msgstr "s - Visa detaljer för spår som spelas"
+msgstr "s - Visa detaljer för spår some spelas"
@@ -3239 +3239 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3323 +3323 @@
-msgstr[0] "%ld minut"
+msgstr[0] "%ld minute"
@@ -3426,3 +3426,3 @@
-"det under reglerna för GNUs generella publika licens som är publicerad\n"
-"av Free Software Foundation; antingen version 2 av licensen, eller\n"
-"(om du vill) vilken senare version som helst.\n"
+"det under reglerna för GNUs generella publika licens some är publicerad\n"
+"av Free Software Foundation; antingen version 2 av licensen, eller\n"
+"(om du will) vilken senare version some helst.\n"
@@ -3438 +3438 @@
-"men UTAN NÅGON SOM HELST GARANTI; till och med utan den underförstådda\n"
+"men UTAN NÅGON SOME HELST GARANTI; till och med utan den underförstådda\n"
@@ -3483 +3483 @@
-msgstr "Aktivera felsökningsutskrifter som matchar en speciell sträng"
+msgstr "Aktivera felsökningsutskrifter some matchar en speciell sträng"
@@ -3694 +3694 @@
-msgstr "Linjär, tar bort objekt när de spelats"
+msgstr "Linjär, tar bort object när de spelats"
@@ -3720 +3720 @@
-msgstr "Filen ”%s” finns redan. Vill du ersätta den?"
+msgstr "Filen ”%s” finns redan. Will du ersätta den?"
@@ -3749,5 +3749,5 @@
-"%d fil kan inte överföras eftersom den måste konverteras till ett format som "
-"stöds av målenheten, men inga lämpliga kodningsprofiler finns tillgängliga"
-msgstr[1] ""
-"%d filer kan inte överföras eftersom de måste konverteras till ett format "
-"som stöds av målenheten, men inga lämpliga kodningsprofiler finns "
+"%d fil kan inte överföras eftersom den måste konverteras till ett format some "
+"stöds av målenheten, men inga lämpliga kodningsprofiler finns tillgängliga"
+msgstr[1] ""
+"%d filer kan inte överföras eftersom de måste konverteras till ett format "
+"some stöds av målenheten, men inga lämpliga kodningsprofiler finns "
@@ -3777,6 +3777,6 @@
-"Ytterligare programvara krävs för att konvertera %d fil till ett format som "
-"stöds av målenheten:\n"
-"%s"
-msgstr[1] ""
-"Ytterligare programvara krävs för att konvertera %d filer till ett format "
-"som stöds av målenheten:\n"
+"Ytterligare programvara krävs för att konvertera %d fil till ett format some "
+"stöds av målenheten:\n"
+"%s"
+msgstr[1] ""
+"Ytterligare programvara krävs för att konvertera %d filer till ett format "
+"some stöds av målenheten:\n"
@@ -3889 +3889 @@
-msgstr "Nummer - Titel"
+msgstr "Nummer - Title"
@@ -3893 +3893 @@
-msgstr "Artist - Titel"
+msgstr "Artist - Title"
@@ -3897 +3897 @@
-msgstr "Artist - Nummer - Titel"
+msgstr "Artist - Nummer - Title"
@@ -3901 +3901 @@
-msgstr "Artist (Album) - Nummer - Titel"
+msgstr "Artist (Album) - Nummer - Title"
@@ -3905 +3905 @@
-msgstr "Nummer. Artist - Titel"
+msgstr "Nummer. Artist - Title"
@@ -4054 +4054 @@
-msgstr "Knapparna som visas i larmdialogen"
+msgstr "Knapparna some visas i larmdialogen"
@@ -4082 +4082 @@
-msgstr "Variabel bithastighet"
+msgstr "Variable bithastighet"
@@ -4086 +4086 @@
-msgstr "Begränsad variabel bithastighet"
+msgstr "Begränsad variable bithastighet"
@@ -4254 +4254 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4329 +4329 @@
-msgstr "Slag per minut"
+msgstr "Slag per minute"
@@ -4379 +4379 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4452 +4452 @@
-msgstr "Slag per minut"
+msgstr "Slag per minute"
@@ -4474 +4474 @@
-msgstr "inte samma som"
+msgstr "inte samma some"
@@ -4486 +4486 @@
-msgstr "som minst"
+msgstr "some minst"
@@ -4491 +4491 @@
-msgstr "som mest"
+msgstr "some mest"
--- ./po/si.po	original
+++ ./po/si.po	fixed
@@ -1517 +1517 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -3710 +3710 @@
-"convertis dans un format pris en charge par le périphérique cible et "
+"converts dans un format pris en charge par le périphérique cible et "
--- ./po/sr@latin.po	original
+++ ./po/sr@latin.po	fixed
@@ -85 +85 @@
-msgstr "Ne mogu da povežem Gstrimer proces; proverite instalaciju programa"
+msgstr "Ne mogu da povežem Gstrimer process; proverite instalaciju programa"
@@ -90 +90 @@
-msgstr "Ne mogu da napravim Gstrimer proces kako bih pustio „%s“"
+msgstr "Ne mogu da napravim Gstrimer process kako bih pustio „%s“"
@@ -646 +646 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -1135 +1135 @@
-msgstr "Sistem"
+msgstr "System"
@@ -1748 +1748 @@
-msgstr "Tekst pesme"
+msgstr "Text pesme"
@@ -1753 +1753 @@
-msgstr "Učitavam tekst pesme „%s“, izvođača „%s“"
+msgstr "Učitavam text pesme „%s“, izvođača „%s“"
@@ -1757 +1757 @@
-msgstr "Nisam pronašao tekst pesme"
+msgstr "Nisam pronašao text pesme"
@@ -2228 +2228 @@
-msgstr "Nije nađen tekst pesme"
+msgstr "Nije nađen text pesme"
@@ -2240 +2240 @@
-msgstr "Tražim tekst pesme..."
+msgstr "Tražim text pesme..."
@@ -2334 +2334 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2919 +2919 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3333 +3333 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3417,4 +3417,4 @@
-msgstr[0] "%ld minut"
-msgstr[1] "%ld minuta"
-msgstr[2] "%ld minuta"
-msgstr[3] "Jedan minut"
+msgstr[0] "%ld minute"
+msgstr[1] "%ld minuta"
+msgstr[2] "%ld minuta"
+msgstr[3] "Jedan minute"
@@ -4693 +4693 @@
-msgstr "Obrišite tekst za pretragu"
+msgstr "Obrišite text za pretragu"
--- ./po/kk.po	original
+++ ./po/kk.po	fixed
@@ -1467 +1467 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -3228 +3228 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/ka.po	original
+++ ./po/ka.po	fixed
@@ -3126 +3126 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/is.po	original
+++ ./po/is.po	fixed
@@ -957 +957 @@
-msgid "An exception occured '%s'"
+msgid "An exception occurred '%s'"
@@ -1204 +1204 @@
-#. an error occured
+#. an error occurred
--- ./po/ga.po	original
+++ ./po/ga.po	fixed
@@ -273 +273 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -2796 +2796 @@
-msgstr "Teip ag rith sound-juicer: %s"
+msgstr "Teip ag with sound-juicer: %s"
--- ./po/ca.po	original
+++ ./po/ca.po	fixed
@@ -193 +193 @@
-msgstr "E_ines"
+msgstr "E_lines"
@@ -265 +265 @@
-msgstr "Minuts"
+msgstr "Minutes"
@@ -354 +354 @@
-msgstr "Columnes visibles"
+msgstr "Columnes visible"
@@ -639 +639 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -737 +737 @@
-msgstr "Seleccioneu una carpeta per als podcasts"
+msgstr "Seleccioneu una carpeta per also podcasts"
@@ -1625 +1625 @@
-msgstr "L'emissora només està disponible per als subscriptors de %s"
+msgstr "L'emissora només està disponible per also subscriptors de %s"
@@ -1683 +1683 @@
-msgstr "No s'ha pogut escriure el fitxer del projecte d'àudio %s: %s"
+msgstr "No s'ha pogut escriure el fitxer del projectile d'àudio %s: %s"
@@ -1689 +1689 @@
-msgstr "No s'ha pogut escriure el projecte d'àudio"
+msgstr "No s'ha pogut escriure el projectile d'àudio"
@@ -1693 +1693 @@
-msgstr "No s'ha pogut crear el projecte de CD d'àudio"
+msgstr "No s'ha pogut crear el projectile de CD d'àudio"
@@ -1742 +1742 @@
-"Aquesta informació només està disponible als usuaris del Last.fm. Assegureu-"
+"Aquesta informació només està disponible also usuaris del Last.fm. Assegureu-"
@@ -2134 +2134 @@
-msgstr "Suport per a emetre serveis tramesos per Internet"
+msgstr "Support per a emetre serveis tramesos per Internet"
@@ -2890 +2890 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2948 +2948 @@
-"Sembla que l'URL «%s» no és un canal de podcast. Pot ser que l'URL sigui "
+"Sembla que l'URL «%s» no és un canal de podcast. Pot set que l'URL sigui "
@@ -3279 +3279 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3350 +3350 @@
-msgstr "Fitxer buit"
+msgstr "Fitxer built"
@@ -3360,2 +3360,2 @@
-msgstr[0] "%ld minut"
-msgstr[1] "%ld minuts"
+msgstr[0] "%ld minute"
+msgstr[1] "%ld minutes"
@@ -3417 +3417 @@
-msgstr "Connector d'exemple en Python"
+msgstr "Connector d'example en Python"
@@ -3421 +3421 @@
-msgstr "Un connector exemple en Python sense funcionalitat"
+msgstr "Un connector example en Python sense funcionalitat"
@@ -3431 +3431 @@
-msgstr "Connector d'exemple"
+msgstr "Connector d'example"
@@ -3435 +3435 @@
-msgstr "Un connector d'exemple en C, sense funcionalitats"
+msgstr "Un connector d'example en C, sense funcionalitats"
@@ -3439 +3439 @@
-msgstr "Connector d'exemple en Vala"
+msgstr "Connector d'example en Vala"
@@ -3443 +3443 @@
-msgstr "Un connector d'exemple en Vala, sense funcionalitats"
+msgstr "Un connector d'example en Vala, sense funcionalitats"
@@ -3569 +3569 @@
-"Pot ser que la llista de reproducció estigui en un format desconegut o "
+"Pot set que la llista de reproducció estigui en un format desconegut o "
@@ -3957 +3957 @@
-msgstr "Camí d'exemple:"
+msgstr "Camí d'example:"
@@ -3990 +3990 @@
-"No hi ha suficient espai lliure al dispositiu per a transferir la música, "
+"No hi ha sufficient espai lliure al dispositiu per a transferir la música, "
@@ -4179 +4179 @@
-msgstr "Vist per última vegada"
+msgstr "Visit per última vegada"
@@ -4365 +4365 @@
-msgstr "Pulsacions per minut"
+msgstr "Pulsacions per minute"
@@ -4488 +4488 @@
-msgstr "Pulsacions per minut"
+msgstr "Pulsacions per minute"
@@ -4568 +4568 @@
-msgstr "minuts"
+msgstr "minutes"
--- ./po/et.po	original
+++ ./po/et.po	fixed
@@ -116 +116 @@
-msgstr "Tekst ikoonide all"
+msgstr "Text ikoonide all"
@@ -119 +119 @@
-msgstr "Tekst ikoonide kõrval"
+msgstr "Text ikoonide kõrval"
@@ -122 +122 @@
-msgstr "Ainult tekst"
+msgstr "Ainult text"
@@ -241 +241 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -243 +243 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -957 +957 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -1190 +1190 @@
-msgstr[0] "%d minut"
+msgstr[0] "%d minute"
@@ -1739 +1739 @@
-"Rhythmbox leidis seadme, mis võib olla lähtestamata või rikutud iPod. Enne "
+"Rhythmbox leidis seadme, miss võib olla lähtestamata või rikutud iPod. Enne "
@@ -1822 +1822 @@
-"     * Õigusraamistiku, mis kaitseb artiste (tänu Creative Commons "
+"     * Õigusraamistiku, miss kaitseb artiste (tänu Creative Commons "
@@ -1830 +1830 @@
-"     * Iseõppiva iRATE baasil muusikasoovitussüsteemi, mis aitab kuulajatel "
+"     * Iseõppiva iRATE baasil muusikasoovitussüsteemi, miss aitab kuulajatel "
@@ -1855 +1855 @@
-msgstr "Jamendo on ainukene platvorm, mis ühendab endas:"
+msgstr "Jamendo on ainukene platvorm, miss ühendab endas:"
@@ -1880 +1880 @@
-"See on \"Mõnede õiguste säilitamisega\" lepe, mis sobib hästi uude "
+"See on \"Mõnede õiguste säilitamisega\" lepe, miss sobib hästi uude "
@@ -2061 +2061 @@
-"    * Saadaval on nii allalaadimised kui CD-d (ükski teine sait Internetis "
+"    * Saadaval on nii allalaadimised kui CD-d (ükski teine sait Internets "
@@ -2068 +2068 @@
-"    * Laialdane biograafiline teave iga muusiku kohta ja foto esitajast -- "
+"    * Laialdane biograafiline teave iga muusiku kohta ja photo esitajast -- "
@@ -2093 +2093 @@
-"veebipoodidest, mis rõhuvad enam-vähem samale (gigantsele) valikule\n"
+"veebipoodidest, miss rõhuvad enam-vähem samale (gigantsele) valikule\n"
@@ -2159 +2159 @@
-"Magnatune on veebimuusika kaubamärk, mis ei ole kurjast. Mõned nende "
+"Magnatune on veebimuusika kaubamärk, miss ei ole kurjast. Mõned nende "
@@ -2447 +2447 @@
-msgstr "MTP-seadmesse pole võimalik faile saata: %s"
+msgstr "MTP-seadmesse pole võimalik failed saata: %s"
@@ -2537 +2537 @@
-"GStreameri komponendid, mis on vajalikud ReplayGaini toimimiseks pole "
+"GStreameri komponendid, miss on vajalikud ReplayGaini toimimiseks pole "
@@ -2547 +2547 @@
-msgstr "Pythoni näidisplugin, mis ei tee midagi"
+msgstr "Pythoni näidisplugin, miss ei tee midagi"
@@ -2556 +2556 @@
-msgstr "Näidisplugin keeles C, mis ei tee midagi"
+msgstr "Näidisplugin keeles C, miss ei tee midagi"
@@ -2559 +2559 @@
-msgstr "Näidisplugin keeles Vala, mis ei tee midagi"
+msgstr "Näidisplugin keeles Vala, miss ei tee midagi"
@@ -2664 +2664 @@
-msgstr "Nähtav + teated"
+msgstr "Nähtav + treated"
@@ -2670 +2670 @@
-msgstr "_Teated:"
+msgstr "_Treated:"
@@ -3037 +3037 @@
-msgstr "Allikas, mis valida"
+msgstr "Allikas, miss valida"
@@ -3138 +3138 @@
-msgstr[0] "%ld minut"
+msgstr[0] "%ld minute"
@@ -3759 +3759 @@
-"%d %d-st failist, mis kantakse seadmele, on vormingus, mida sihtseade ei "
+"%d %d-st failist, miss kantakse seadmele, on vormingus, mida sihtseade ei "
@@ -4003 +4003 @@
-msgstr "Pixbuf objekt"
+msgstr "Pixbuf object"
--- ./po/en_GB.po	original
+++ ./po/en_GB.po	fixed
@@ -3411,2 +3411,2 @@
-msgid "Seeked to %s"
-msgstr "Seeked to %s"
+msgid "Sought to %s"
+msgstr "Sought to %s"
@@ -5564,2 +5564,2 @@
-#~ msgid "C_onfigure..."
-#~ msgstr "C_onfigure…"
+#~ msgid "C_configure..."
+#~ msgstr "C_configure…"
@@ -7127,2 +7127,2 @@
-#~ msgid "An exception occured '%s'"
-#~ msgstr "An exception occured '%s'"
+#~ msgid "An exception occurred '%s'"
+#~ msgstr "An exception occurred '%s'"
--- ./po/eu.po	original
+++ ./po/eu.po	fixed
@@ -1084 +1084 @@
-msgstr "Serie-zenbakia:"
+msgstr "Series-zenbakia:"
@@ -1126 +1126 @@
-msgstr "Ez da biltegiratze-gunerik aurkitu gailu honetan. Hura desblokeatu eta MTP gaitu beharko duzu agian."
+msgstr "Ez da biltegiratze-gunerik aurkitu gailu honetan. Hura desblokeatu eta MTP gaitu beharko duzu again."
@@ -1819 +1819 @@
-msgstr "Partekatutako DAAPeren ostalaria:ataka:"
+msgstr "Partekatutako DATAPeren ostalaria:ataka:"
@@ -2821 +2821 @@
-msgstr "'%s' URLa ez dirudi podcast-eko jarioa denik. Agian URL okerra da, edo jarioa hondatuta dago. Hala ere, nahi duzu Rhythmbox-ek hori erabiltzea?"
+msgstr "'%s' URLa ez dirudi podcast-eko jarioa denik. Again URL okerra da, edo jarioa hondatuta dago. Hala ere, nahi duzu Rhythmbox-ek hori erabiltzea?"
@@ -3140 +3140 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/nb.po	original
+++ ./po/nb.po	fixed
@@ -118,4 +118,4 @@
-"Rhythmbox er et program for håndtering av musikk og er designet for GNOME "
-"skrivebordet. I tillegg til musikk lagret på din datamaskin støtter det "
-"delte nettverkslokasjoner, podcaster, radiostrømmer og portable "
-"musikkenheter (inklusive telefoner) og musikktjenester på internett som Last."
+"Rhythmbox er et program for håndtering av musikk og er designated for GNOME "
+"skrivebordet. I tillegg til musikk lagret på din datamaskin støtter det "
+"delete nettverkslokasjoner, podcaster, radiostrømmer og portable "
+"musikkenheter (inklusive telefoner) og musikktjenester på internett some Last."
@@ -176 +176 @@
-msgstr "Følg spor som spilles av"
+msgstr "Følg spor some spilles av"
@@ -324 +324 @@
-msgstr "_Installer ekstra programvare som kreves for å bruke dette formatet"
+msgstr "_Installer ekstra programvare some kreves for å bruke dette formatet"
@@ -413 +413 @@
-"Velg en lokasjon som inneholder musikk for å legge den til i ditt bibliotek:"
+"Velg en lokasjon some inneholder musikk for å legge den til i ditt bibliotek:"
@@ -425 +425 @@
-msgstr "Kopier filer som ligger utenfor musikkbiblioteket"
+msgstr "Kopier filer some ligger utenfor musikkbiblioteket"
@@ -626 +626 @@
-"Abonner på podcaster for å laste ned nye episoder når de blir publisert."
+"Abonner på podcaster for å laste need nye episoder når de blir publisert."
@@ -699 +699 @@
-msgstr "Last ned episode"
+msgstr "Last need episode"
@@ -1106 +1106 @@
-msgstr "Modell:"
+msgstr "Model:"
@@ -1206 +1206 @@
-msgstr "Støtte for avspilling av lyd-CDer som musikkilde"
+msgstr "Støtte for avspilling av lyd-CDer some musikkilde"
@@ -1228 +1228 @@
-msgstr "Velg spor som skal hentes ut"
+msgstr "Velg spor some skal hentes ut"
@@ -1413 +1413 @@
-msgstr "Last ned"
+msgstr "Last need"
@@ -1479 +1479 @@
-msgstr "Som ligner på artist:"
+msgstr "Some ligner på artist:"
@@ -1507 +1507 @@
-msgstr "Spor som er elsket av bruker:"
+msgstr "Spor some er elsket av bruker:"
@@ -1719 +1719 @@
-msgstr "Rull visningen til sangen og artist som spilles av nå."
+msgstr "Rull visningen til sangen og artist some spilles av nå."
@@ -1727 +1727 @@
-"tillegget for Last.fm er slått på. Velg så Last.fm i sidelinjen og logg inn."
+"tillegget for Last.fm er slått på. Velg så Last.fm i sideline og logg inn."
@@ -1826 +1826 @@
-msgstr "Vennligst skriv inn passordet som vises på din enhet."
+msgstr "Vennligst skriv inn passordet some vises på din enhet."
@@ -2064 +2064 @@
-msgstr "_Modell:"
+msgstr "_Model:"
@@ -2074,3 +2074,3 @@
-"Rhythmbox har gjenkjent en enhet som sannsyligvis er en uinitiert eller "
-"korrupt iPod. Den må initieres før Rhythmbox kan bruke den, men dette vil "
-"ødelegge alle metadata om sanger som finnes allerede. Hvis du vil at "
+"Rhythmbox har gjenkjent en enhet some sannsyligvis er en uinitiert eller "
+"korrupt iPod. Den må initieres før Rhythmbox kan bruke den, men dette vil "
+"ødelegge alle metadata om sanger some finnes allerede. Hvis du vil at "
@@ -2256 +2256 @@
-msgstr "Magnatune er et plateselskap på nettet som ikke er ondt.\n"
+msgstr "Magnatune er et plateselskap på nettet some ikke er ondt.\n"
@@ -2284 +2284 @@
-"    * Filformater som er bra for åpen kildekode: MP3 og WAV, men også OGG- "
+"    * Filformater some er bra for åpen kildekode: MP3 og WAV, men også OGG- "
@@ -2301 +2301 @@
-msgstr "Last ned album"
+msgstr "Last need album"
@@ -2321 +2321 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2493 +2493 @@
-msgstr "Kunne ikke laste ned album"
+msgstr "Kunne ikke laste need album"
@@ -2545 +2545 @@
-msgstr "Laster ned fra Magnatune"
+msgstr "Laster need fra Magnatune"
@@ -2666 +2666 @@
-msgstr "Stopp strømstyring fra å gå i hvilemodus under avspilling"
+msgstr "Stop strømstyring fra å gå i hvilemodus under avspilling"
@@ -2729 +2729 @@
-"GStreamer-element som kreves for ReplayGain-prosessering er ikke "
+"GStreamer-element some kreves for ReplayGain-prosessering er ikke "
@@ -2921 +2921 @@
-msgstr "Laster ned podcast"
+msgstr "Laster need podcast"
@@ -2969 +2969 @@
-"URL «%s» er allerede lagt til som en radiostasjon. Hvis dette er en podcast-"
+"URL «%s» er allerede lagt til some en radiostasjon. Hvis dette er en podcast-"
@@ -2979 +2979 @@
-"URL «%s» ser ikke ut til å være en podcast-strøm. Det kan være noe galt med "
+"URL «%s» set ikke ut til å være en podcast-strøm. Det kan være noe galt med "
@@ -3016 +3016 @@
-msgstr "Ikke lastet ned"
+msgstr "Ikke lastet need"
@@ -3041 +3041 @@
-msgstr "Lastet ned"
+msgstr "Lastet need"
@@ -3066 +3066 @@
-"episoden samtidig som du beholder den nedlastede filen ved å velge å bare "
+"episoden samtidig some du beholder den nedlastede filen ved å velge å bare "
@@ -3110 +3110 @@
-msgstr "Vis programmets versjon"
+msgstr "Vis programmers versjon"
@@ -3154 +3154 @@
-msgstr "Stopp avspilling"
+msgstr "Stop avspilling"
@@ -3162 +3162 @@
-msgstr "URI som skal spilles"
+msgstr "URI some skal spilles"
@@ -3182 +3182 @@
-msgstr "Velg kilde som er lik spesifisert URI"
+msgstr "Velg kilde some er lik spesifisert URI"
@@ -3186 +3186 @@
-msgstr "Kilde som skal velges"
+msgstr "Kilde some skal velges"
@@ -3190 +3190 @@
-msgstr "Aktiver kilde som er lik oppgitt URI"
+msgstr "Aktiver kilde some er lik oppgitt URI"
@@ -3194 +3194 @@
-msgstr "Kilde som skal aktiveres"
+msgstr "Kilde some skal aktiveres"
@@ -3198 +3198 @@
-msgstr "Spill fra kilde som er like oppgitt URI"
+msgstr "Spill fra kilde some er like oppgitt URI"
@@ -3230 +3230 @@
-msgstr "Skru ned avspillingsvolumet"
+msgstr "Skru need avspillingsvolumet"
@@ -3240 +3240 @@
-msgstr "Sett poengsum for sangen som spilles av nå"
+msgstr "Sett poengsum for sangen some spilles av nå"
@@ -3260 +3260 @@
-msgstr "s - Vis detaljer om spor som spilles av"
+msgstr "s - Vis detaljer om spor some spilles av"
@@ -3264 +3264 @@
-msgstr "v - Skru ned volumet"
+msgstr "v - Skru need volumet"
@@ -3312 +3312 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3498 +3498 @@
-"under betingelsene gitt i GNU General Public License som utgitt av Free\n"
+"under betingelsene gitt i GNU General Public License some utgitt av Free\n"
@@ -3563 +3563 @@
-msgstr "Ikke registrer skallet"
+msgstr "Ikke register skallet"
@@ -3575 +3575 @@
-msgstr "Sti til databasefil som skal brukes"
+msgstr "Sti til databasefil some skal brukes"
@@ -3579 +3579 @@
-msgstr "Sti til spillelistefil som skal brukes"
+msgstr "Sti til spillelistefil some skal brukes"
@@ -3821,4 +3821,4 @@
-"%d fil kan ikke overføres da den må konverteres til et format som støttes av "
-"målenheten, men ingen passende kodingsprofiler er tilgjengelige"
-msgstr[1] ""
-"%d filer kan ikke overføres da de må konverteres til et format som støttes "
+"%d fil kan ikke overføres da den må konverteres til et format some støttes av "
+"målenheten, men ingen passende kodingsprofiler er tilgjengelige"
+msgstr[1] ""
+"%d filer kan ikke overføres da de må konverteres til et format some støttes "
@@ -4019 +4019 @@
-"Du har ikke valgt noen musikk, spillelister eller podcaster som skal "
+"Du har ikke valgt noen musikk, spillelister eller podcaster some skal "
@@ -4126 +4126 @@
-msgstr "Knappene som vises i varslingsdialogen"
+msgstr "Knappene some vises i varslingsdialogen"
@@ -4154 +4154 @@
-msgstr "Variabel bitrate"
+msgstr "Variable bitrate"
@@ -4456 +4456 @@
-msgstr "_Med sanger som har fått mange poeng først"
+msgstr "_Med sanger some har fått mange poeng først"
@@ -4510 +4510 @@
-msgstr "_Med spor som er lagt til nylig først"
+msgstr "_Med spor some er lagt til nylig først"
--- ./po/ja.po	original
+++ ./po/ja.po	fixed
@@ -3325 +3325 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -5502 +5502 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/de.po	original
+++ ./po/de.po	fixed
@@ -213 +213 @@
-msgstr "Momentan wiedergegebenem Titel folgen"
+msgstr "Momentan wiedergegebenem Title folgen"
@@ -277 +277 @@
-msgstr "Titel"
+msgstr "Title"
@@ -381 +381 @@
-msgstr "Titel_nummer"
+msgstr "Title_nummer"
@@ -495 +495 @@
-msgstr "Künstler/Künstler - Album/Künstler (Album) - 01 - Titel.ogg"
+msgstr "Künstler/Künstler - Album/Künstler (Album) - 01 - Title.ogg"
@@ -602 +602 @@
-msgstr "_Alle Titel einreihen"
+msgstr "_Alle Title einreihen"
@@ -611 +611 @@
-msgstr "Als Datei _speichern …"
+msgstr "Also Datei _speichern …"
@@ -652 +652 @@
-"Suchen Sie im iTunes Store nach Podcasts oder geben Sie die Adresse eines "
+"Suchen Sie im iTunes Store nach Podcasts oder geben Sie die Address eines "
@@ -663 +663 @@
-msgstr "Titel:"
+msgstr "Title:"
@@ -667 +667 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -749 +749 @@
-msgstr "Manuell"
+msgstr "Manual"
@@ -765 +765 @@
-msgstr "Den Podcast-Ordner auswählen"
+msgstr "Den Podcast-Order auswählen"
@@ -895 +895 @@
-msgstr "_Titel:"
+msgstr "_Title:"
@@ -899 +899 @@
-msgstr "Titel_nummer:"
+msgstr "Title_nummer:"
@@ -1128 +1128 @@
-msgstr "Modell:"
+msgstr "Model:"
@@ -1165 +1165 @@
-msgstr "Titel:"
+msgstr "Title:"
@@ -1233 +1233 @@
-msgstr "Unterstützung für das Abspielen von Musik-CDs als Quelle"
+msgstr "Unterstützung für das Abspielen von Musik-CDs also Quelle"
@@ -1235 +1235 @@
-# Liest Titel in die Datenbank ein und wandelt sie in zB mp3 um.
+# Liest Title in die Datenbank ein und wandelt sie in zB mp3 um.
@@ -1256 +1256 @@
-msgstr "Zu entpackende Titel auswählen"
+msgstr "Zu entpackende Title auswählen"
@@ -1302 +1302 @@
-msgstr "Titel %u"
+msgstr "Title %u"
@@ -1353 +1353 @@
-msgstr "Titel in Warteschlange:"
+msgstr "Title in Warteschlange:"
@@ -1357 +1357 @@
-msgstr "Übermittelte Titel:"
+msgstr "Übermittelte Title:"
@@ -1386 +1386 @@
-msgstr "Kürzlich gehörte Titel"
+msgstr "Kürzlich gehörte Title"
@@ -1398 +1398 @@
-msgstr "Top-Titel"
+msgstr "Top-Title"
@@ -1430 +1430 @@
-msgstr "Übermittlung der Titel ist zu oft fehlgeschlagen"
+msgstr "Übermittlung der Title ist zu oft fehlgeschlagen"
@@ -1537 +1537 @@
-msgstr "Vom Benutzer bevorzugte Titel:"
+msgstr "Vom Benutzer bevorzugte Title:"
@@ -1559 +1559 @@
-msgstr "Titel gekennzeichnet mit:"
+msgstr "Title gekennzeichnet mit:"
@@ -1784 +1784 @@
-msgstr "Alle Titel verbergen"
+msgstr "Alle Title verbergen"
@@ -1789 +1789 @@
-msgstr "Alle Titel anzeigen"
+msgstr "Alle Title anzeigen"
@@ -1800,2 +1800,2 @@
-msgstr[0] "%s (%d Titel)"
-msgstr[1] "%s (%d Titel)"
+msgstr[0] "%s (%d Title)"
+msgstr[1] "%s (%d Title)"
@@ -1901 +1901 @@
-msgstr "Titel aus Musikfreigabe werden empfangen"
+msgstr "Title aus Musikfreigabe werden empfangen"
@@ -1937 +1937 @@
-msgstr "Alle Titel"
+msgstr "Alle Title"
@@ -2004 +2004 @@
-msgstr "Verschiedene lokale und Internet-Medienquellen durchsuchen"
+msgstr "Verschiedene locale und Internet-Medienquellen durchsuchen"
@@ -2008 +2008 @@
-msgstr "Weitere Titel holen"
+msgstr "Weitere Title holen"
@@ -2026 +2026 @@
-"Aktualisiert den Sofortnachrichten-Status anhand des aktuellen Titels "
+"Aktualisiert den Sofortnachrichten-Status anhand des aktuellen Titles "
@@ -2102 +2102 @@
-msgstr "_Modell:"
+msgstr "_Model:"
@@ -2114 +2114 @@
-"muss es initialisiert werden, aber dadurch werden bereits vorhandene Titel-"
+"muss es initialisiert werden, aber dadurch werden bereits vorhandene Title-"
@@ -2189 +2189 @@
-msgstr "Adresse des Internet-Radiosenders:"
+msgstr "Address des Internet-Radiosenders:"
@@ -2253 +2253 @@
-msgstr "Ordner für Liedtexte auswählen …"
+msgstr "Order für Liedtexte auswählen …"
@@ -2273 +2273 @@
-msgstr "Ordner für Liedtexte"
+msgstr "Order für Liedtexte"
@@ -2320 +2320 @@
-msgstr "\t* Kostenloses Anhören aller Titel"
+msgstr "\t* Kostenloses Anhören aller Title"
@@ -2381 +2381 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2449 +2449 @@
-msgstr "10 US$ (besser als der Durchschnitt)"
+msgstr "10 US$ (besser also der Durchschnitt)"
@@ -2541 +2541 @@
-msgstr "Mehr über Magnatune erfahren unter "
+msgstr "Mehr über Magnatune erfahren under "
@@ -2806 +2806 @@
-msgstr "Radio (gleicher Pegel für alle Titel)"
+msgstr "Radio (gleicher Pegel für alle Title)"
@@ -2810 +2810 @@
-msgstr "Album (idealer Pegel für alle Titel)"
+msgstr "Album (idealer Pegel für alle Title)"
@@ -2882 +2882 @@
-msgstr "Titel"
+msgstr "Title"
@@ -2886 +2886 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2926 +2926 @@
-"überprüfen Sie die Adresse: %s"
+"überprüfen Sie die Address: %s"
@@ -2944,2 +2944,2 @@
-"Die Adresse »%s« scheint kein gültiger Podcast-Feed zu sein. Dabei kann es "
-"sich um eine falsche Adresse handeln, oder der Feed ist beschädigt. Soll "
+"Die Address »%s« scheint kein gültiger Podcast-Feed zu sein. Dabei kann es "
+"sich um eine falsche Address handeln, oder der Feed ist beschädigt. Soll "
@@ -2951 +2951 @@
-msgstr "Adresse bereits hinzugefügt"
+msgstr "Address bereits hinzugefügt"
@@ -2959 +2959 @@
-"Die Adresse »%s« wurde bereits als Internet-Radiosender hinzugefügt. Wenn "
+"Die Address »%s« wurde bereits also Internet-Radiosender hinzugefügt. Wenn "
@@ -3075 +3075 @@
-msgstr "Die Versionsnummer des Programms anzeigen"
+msgstr "Die Versionsnummer des Programs anzeigen"
@@ -3095 +3095 @@
-msgstr "Zum nächsten Titel springen"
+msgstr "Zum nächsten Title springen"
@@ -3099 +3099 @@
-msgstr "Zum vorherigen Titel springen"
+msgstr "Zum vorherigen Title springen"
@@ -3103 +3103 @@
-msgstr "Suchlauf im aktuellen Titel"
+msgstr "Suchlauf im aktuellen Title"
@@ -3107 +3107 @@
-msgstr "Startet die Wiedergabe, falls aktuell pausiert"
+msgstr "Started die Wiedergabe, falls aktuell pausiert"
@@ -3123 +3123 @@
-msgstr "Eine übergebene Adresse abspielen, falls nötig diese importieren"
+msgstr "Eine übergebene Address abspielen, falls nötig diese importieren"
@@ -3127 +3127 @@
-msgstr "Zu spielende Adresse"
+msgstr "Zu spielende Address"
@@ -3131 +3131 @@
-msgstr "Die ausgewählten Titel in die Wiedergabeliste aufnehmen"
+msgstr "Die ausgewählten Title in die Wiedergabeliste aufnehmen"
@@ -3135 +3135 @@
-msgstr "Die Warteschlange leeren, ehe ein neuer Titel hinzugefügt wird"
+msgstr "Die Warteschlange leeren, ehe ein neuer Title hinzugefügt wird"
@@ -3139 +3139 @@
-msgstr "Name und Künstler für den aktuell wiedergegebenen Titel anzeigen"
+msgstr "Name und Künstler für den aktuell wiedergegebenen Title anzeigen"
@@ -3147 +3147 @@
-msgstr "Die Quelle auswählen, welche auf die angegebene Adresse passt"
+msgstr "Die Quelle auswählen, welche auf die angegebene Address passt"
@@ -3155 +3155 @@
-msgstr "Die Quelle aktivieren, welche auf die angegebene Adresse passt"
+msgstr "Die Quelle aktivieren, welche auf die angegebene Address passt"
@@ -3163 +3163 @@
-msgstr "Aus der Quelle wiedergeben, welche auf die angegebene Adresse passt"
+msgstr "Aus der Quelle wiedergeben, welche auf die angegebene Address passt"
@@ -3205 +3205 @@
-msgstr "Den momentanen Titel bewerten"
+msgstr "Den momentanen Title bewerten"
@@ -3213 +3213 @@
-msgstr "n - Nächster Titel"
+msgstr "n - Nächster Title"
@@ -3217 +3217 @@
-msgstr "p - Vorheriger Titel"
+msgstr "p - Vorheriger Title"
@@ -3225 +3225 @@
-msgstr "s - Details zum laufenden Titel anzeigen"
+msgstr "s - Details zum laufenden Title anzeigen"
@@ -3275 +3275 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3419 +3419 @@
-msgstr "Eine Beispiel-Erweiterung in Python ohne weitere Funktion"
+msgstr "Eine Beispiel-Erweiterung in Python ohne weitere Function"
@@ -3433 +3433 @@
-msgstr "Eine Beispiel-Erweiterung in C ohne weitere Funktion"
+msgstr "Eine Beispiel-Erweiterung in C ohne weitere Function"
@@ -3441 +3441 @@
-msgstr "Eine Beispiel-Erweiterung in Vala ohne weitere Funktion"
+msgstr "Eine Beispiel-Erweiterung in Vala ohne weitere Function"
@@ -3462 +3462 @@
-"oder verändern unter Beachtung der GNU General Public License , so wie\n"
+"oder verändern under Beachtung der GNU General Public License , so wie\n"
@@ -3475 +3475 @@
-"als nützlich empfinden, jedoch OHNE JEGLICHE GARANTIE\n"
+"also nützlich empfinden, jedoch OHNE JEGLICHE GARANTIE\n"
@@ -3486 +3486 @@
-"Im Paket mit Rhythmbox sollten Sie ebenfalls eine Kopie der\n"
+"Im Packet mit Rhythmbox sollten Sie ebenfalls eine Kopie der\n"
@@ -3645 +3645 @@
-msgstr "Keine registrierte Quelle kann die Adresse %s verarbeiten"
+msgstr "Keine registrierte Quelle kann die Address %s verarbeiten"
@@ -3650 +3650 @@
-msgstr "Keine registrierte Quelle passt auf die Adresse %s"
+msgstr "Keine registrierte Quelle passt auf die Address %s"
@@ -3655 +3655 @@
-msgstr "Unbekannte Lied-Adresse: %s"
+msgstr "Unbekannte Lied-Address: %s"
@@ -3688 +3688 @@
-msgstr "Kein vorhergehender Titel"
+msgstr "Kein vorhergehender Title"
@@ -3693 +3693 @@
-msgstr "Kein nachfolgender Titel"
+msgstr "Kein nachfolgender Title"
@@ -3707 +3707 @@
-msgstr "Der aktuelle Titel kann nicht durchsucht werden"
+msgstr "Der aktuelle Title kann nicht durchsucht werden"
@@ -3796,5 +3796,5 @@
-"Formate keine Kodierer verfügbar sind"
-msgstr[1] ""
-"%d Dateien können nicht übertragen werden, weil sie in ein vom Zielgerät "
-"unterstütztes Format umgewandelt werden müssen, aber für die unterstützten "
-"Formate keine Kodierer verfügbar sind"
+"Format keine Kodierer verfügbar sind"
+msgstr[1] ""
+"%d Dateien können nicht übertragen werden, weil sie in ein vom Zielgerät "
+"unterstütztes Format umgewandelt werden müssen, aber für die unterstützten "
+"Format keine Kodierer verfügbar sind"
@@ -3866 +3866 @@
-msgstr "Titel durchsuchen"
+msgstr "Title durchsuchen"
@@ -3937 +3937 @@
-msgstr "Nummer - Titel"
+msgstr "Nummer - Title"
@@ -3941 +3941 @@
-msgstr "Künstler - Titel"
+msgstr "Künstler - Title"
@@ -3945 +3945 @@
-msgstr "Künstler - Nummer - Titel"
+msgstr "Künstler - Nummer - Title"
@@ -3949 +3949 @@
-msgstr "Künstler (Album) - Nummer - Titel"
+msgstr "Künstler (Album) - Nummer - Title"
@@ -3953 +3953 @@
-msgstr "Nummer. Künstler - Titel"
+msgstr "Nummer. Künstler - Title"
@@ -3975 +3975 @@
-msgstr "Fehler beim Übertragen des Titels"
+msgstr "Fehler beim Übertragen des Titles"
@@ -3979 +3979 @@
-msgstr "Titel werden in die Bibliothek kopiert"
+msgstr "Title werden in die Bibliothek kopiert"
@@ -3983 +3983 @@
-msgstr "Titel werden in der Bibliothek hinzugefügt"
+msgstr "Title werden in der Bibliothek hinzugefügt"
@@ -3988 +3988 @@
-msgstr "Titel werden mit %s abgeglichen"
+msgstr "Title werden mit %s abgeglichen"
@@ -4052,2 +4052,2 @@
-msgstr[0] "%d Titel"
-msgstr[1] "%d Titel"
+msgstr[0] "%d Title"
+msgstr[1] "%d Title"
@@ -4066 +4066 @@
-msgstr "Titel werden nach %s übertragen"
+msgstr "Title werden nach %s übertragen"
@@ -4147 +4147 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4244,2 +4244,2 @@
-msgstr[0] "%d ausgewählten Titel importieren"
-msgstr[1] "%d ausgewählte Titel importieren"
+msgstr[0] "%d ausgewählten Title importieren"
+msgstr[1] "%d ausgewählte Title importieren"
@@ -4251,2 +4251,2 @@
-msgstr[0] "%d aufgelisteten Titel importieren"
-msgstr[1] "%d aufgelistete Titel importieren"
+msgstr[0] "%d aufgelisteten Title importieren"
+msgstr[1] "%d aufgelistete Title importieren"
@@ -4302 +4302 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4427 +4427 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4504 +4504 @@
-msgstr "Titel m_it schnellerem Tempo zuerst"
+msgstr "Title m_it schnellerem Tempo zuerst"
@@ -4634 +4634 @@
-msgstr "Titel-Eigenschaften"
+msgstr "Title-Eigenschaften"
@@ -4638 +4638 @@
-msgstr "Eigenschaften mehrerer Titel"
+msgstr "Eigenschaften mehrerer Title"
@@ -4665 +4665 @@
-#~ msgstr "Titel in SoundCloud® durchstöbern und abspielen"
+#~ msgstr "Title in SoundCloud® durchstöbern und abspielen"
@@ -4668 +4668 @@
-#~ msgstr "Titel suchen"
+#~ msgstr "Title suchen"
@@ -4671 +4671 @@
-#~ msgstr "Titel auf SoundCloud suchen"
+#~ msgstr "Title auf SoundCloud suchen"
@@ -4698 +4698 @@
-#~ msgstr "Ungültige Adresse"
+#~ msgstr "Ungültige Address"
@@ -4701 +4701 @@
-#~ msgstr "Die Adresse »%s« ist ungültig, bitte überprüfen Sie sie."
+#~ msgstr "Die Address »%s« ist ungültig, bitte überprüfen Sie sie."
@@ -4713 +4713 @@
-#~ msgstr "Ordner zum Herunterladen von %s konnte nicht erzeugt werden: %s"
+#~ msgstr "Order zum Herunterladen von %s konnte nicht erzeugt werden: %s"
@@ -4725 +4725 @@
-#~ msgstr "Titel senden"
+#~ msgstr "Title senden"
@@ -4728 +4728 @@
-#~ msgstr "Ausgewählte Titel per E-Mail versenden"
+#~ msgstr "Ausgewählte Title per E-Mail versenden"
--- ./po/nl.po	original
+++ ./po/nl.po	fixed
@@ -9 +9 @@
-# voorkeurenvenster als in het algemene hoofdvenster.
+# voorkeurenvenster also in het algemene hoofdvenster.
@@ -222 +222 @@
-# wordt getoond als attentieballon bij een nieuw nummer
+# wordt getoond also attentieballon bij een nieuw nummer
@@ -314 +314 @@
-msgstr "_Toevoegen als aan één van de criteria is voldaan"
+msgstr "_Toevoegen also aan één van de criteria is voldaan"
@@ -430 +430 @@
-# _T wordt voor _Titel gebruikt
+# _T wordt voor _Title gebruikt
@@ -464 +464 @@
-msgstr "Selecteer een locatie met muziek om aan uw collectie toe te voegen:"
+msgstr "Selecteer een locatie met muziek om aan uw collective toe te voegen:"
@@ -496,7 +496,7 @@
-# op speciaal verzoek van reinouts
-# Nieuwe bestanden in mijn collectie bijhouden/
-# Monitor mijn bibilotheek voor nieuwe bestanden
-# volgen/bijhouden/ontdekken (tino)
-#: ../data/ui/library-prefs.ui.h:4
-msgid "_Watch my library for new files"
-msgstr "_Nieuwe bestanden in mijn collectie bijhouden"
+# op special verzoek van reinouts
+# Nieuwe bestanden in mijn collective bijhouden/
+# Monitor mijn bibilotheek voor nieuwe bestanden
+# volgen/bijhouden/ontdekken (tino)
+#: ../data/ui/library-prefs.ui.h:4
+msgid "_Watch my library for new files"
+msgstr "_Nieuwe bestanden in mijn collective bijhouden"
@@ -523 +523 @@
-msgstr "Artiest/Artiest - Album/Artiest (Album) - 01 - Titel.ogg"
+msgstr "Artiest/Artiest - Album/Artiest (Album) - 01 - Title.ogg"
@@ -573 +573 @@
-msgstr "Informatie"
+msgstr "Informative"
@@ -649 +649 @@
-msgstr "Op extensie"
+msgstr "Op extensive"
@@ -699 +699 @@
-msgstr "Titel:"
+msgstr "Title:"
@@ -857 +857 @@
-# net als kaarten: schudden
+# net also kaarten: schudden
@@ -940 +940 @@
-msgstr "_Titel:"
+msgstr "_Title:"
@@ -952 +952 @@
-msgstr "_Commentaar:"
+msgstr "_Commentary:"
@@ -1000 +1000 @@
-# I M en p geven het: uur(12-uurs), minuut en am/pm indicatie
+# I M en p geven het: uur(12-uurs), minuut en am/pm indicative
@@ -1394 +1394 @@
-msgstr "Verzendt lied-informatie naar Last.fm en speelt Last.fm-radio af"
+msgstr "Verzendt lied-informative naar Last.fm en speelt Last.fm-radio af"
@@ -1670 +1670 @@
-msgstr "Collectie van %s"
+msgstr "Collective van %s"
@@ -1775 +1775 @@
-# wat is een audio track list? bedoelen ze hetzelfde als playlist?
+# wat is een audio track list? bedoelen ze hetzelfde also playlist?
@@ -1838 +1838 @@
-"Informatie over het momenteel afspelende nummer en de artiest weergeven."
+"Informative over het momenteel afspelende nummer en de artiest weergeven."
@@ -1845 +1845 @@
-"Deze informatie is alleen beschikbaar voor last.fm-gebruikers. Zorg ervoor "
+"Deze informative is alleen beschikbaar voor last.fm-gebruikers. Zorg ervoor "
@@ -1904 +1904 @@
-msgstr "Geen informatie beschikbaar"
+msgstr "Geen informative beschikbaar"
@@ -1917 +1917 @@
-msgstr "Muziek delen en gedeelde muziek afspelen op uw lokale netwerk"
+msgstr "Muziek delen en gedeelde muziek afspelen op uw locale netwerk"
@@ -1935 +1935 @@
-msgstr "_Naam collectie:"
+msgstr "_Naam collective:"
@@ -2094 +2094 @@
-msgstr "Door verscheidene lokale en internet-mediabronnen bladeren"
+msgstr "Door verscheidene locale en internet-mediabronnen bladeren"
@@ -2205,3 +2205,3 @@
-"nummerinformatie die reeds aanwezig is, verloren gaan. Als u Rhythmbox de "
-"iPod wilt laten initialiseren, vul dan de informatie hieronder in. Als het "
-"apparaat geen iPod is, of als u niet wit initialiseren, klik dan op "
+"nummerinformatie die reeds aanwezig is, verloren gaan. Also u Rhythmbox de "
+"iPod wilt laten initialiseren, vul dan de informative hieronder in. Also het "
+"apparaat geen iPod is, of also u niet wit initialiseren, klik dan op "
@@ -2450 +2450 @@
-msgstr "U kunt meer informatie vinden op "
+msgstr "U kunt meer informative vinden op "
@@ -2602 +2602 @@
-msgstr "Magnatune informatie"
+msgstr "Magnatune informative"
@@ -2809,2 +2809,2 @@
-# (bij klassieke muziek klinkt 'door' raar als de artiest bijv. Bach is,
-# vandaar beter 'van') (tino)
+# (bij klassieke muziek klinkt 'door' raar also de artiest bijv. Bach is,
+# vandaar better 'van') (tino)
@@ -2841 +2841 @@
-# wordt getoond als attentieballon bij een nieuw nummer
+# wordt getoond also attentieballon bij een nieuw nummer
@@ -2863 +2863 @@
-msgstr "U kunt toegang krijgen tot het hoofdvenster via de ‘shell’-variabele:"
+msgstr "U kunt toegang krijgen tot het hoofdvenster via de ‘shell’-variable:"
@@ -3044 +3044 @@
-msgstr "Titel"
+msgstr "Title"
@@ -3120 +3120 @@
-"De URL ‘%s’ is al toegevoegd als een radiostation. Als dit een podcast feed "
+"De URL ‘%s’ is al toegevoegd also een radiostation. Also dit een podcast feed "
@@ -3142 +3142 @@
-"Er was een probleem bij het toevoegen van deze podcast: %s. Controleer de "
+"Er was een problem bij het toevoegen van deze podcast: %s. Controleer de "
@@ -3184 +3184 @@
-"Indien u kiest om zowel de feed als de bestanden te verwijderen, zullen deze "
+"Indien u kiest om zowel de feed also de bestanden te verwijderen, zullen deze "
@@ -3194 +3194 @@
-msgstr "_Zowel feed als bestanden verwijderen"
+msgstr "_Zowel feed also bestanden verwijderen"
@@ -3225 +3225 @@
-"Indien u kiest om zowel de aflevering als het bestand te verwijderen, zullen "
+"Indien u kiest om zowel de aflevering also het bestand te verwijderen, zullen "
@@ -3338 +3338 @@
-msgstr "Titel en artiest van het beluisterde nummer afdrukken"
+msgstr "Title en artiest van het beluisterde nummer afdrukken"
@@ -3477,2 +3477,2 @@
-msgid "Seeked to %s"
-msgstr "Seeked to %s"
+msgid "Sought to %s"
+msgstr "Sought to %s"
@@ -3723,3 +3723,3 @@
-"ZONDER ENIGE GARANTIE; zonder zelfs een impliciete garantie\n"
-"van VERKOOPBAARHEID, of GESCHIKTHEID VOOR EEN BEPAALD DOEL.\n"
-"Zie de GNU General Public License voor meer informatie.\n"
+"ZONDER ENIGE GARANTIE; zonder zelfs een implicit garantie\n"
+"van VERKOOPBAARHEID, of GESCHIKTHEID VOOR EEN BEPAALD DOEL.\n"
+"Zie de GNU General Public License voor meer informative.\n"
@@ -3773 +3773 @@
-msgstr "De collectie niet bijwerken wanneer bestanden wijzigen"
+msgstr "De collective niet bijwerken wanneer bestanden wijzigen"
@@ -3878 +3878 @@
-msgstr "Fout bij het opslaan van de informatie over het nummer"
+msgstr "Fout bij het opslaan van de informative over het nummer"
@@ -4125 +4125 @@
-msgstr "Zoeken in titels"
+msgstr "Zoeken in titles"
@@ -4143 +4143 @@
-msgstr "Collectie"
+msgstr "Collective"
@@ -4198 +4198 @@
-msgstr "Volgnummer - Titel"
+msgstr "Volgnummer - Title"
@@ -4202 +4202 @@
-msgstr "Artiest - Titel"
+msgstr "Artiest - Title"
@@ -4206 +4206 @@
-msgstr "Artiest - Volgnummer - Titel"
+msgstr "Artiest - Volgnummer - Title"
@@ -4210 +4210 @@
-msgstr "Artiest (Album) - Volgnummer - Titel"
+msgstr "Artiest (Album) - Volgnummer - Title"
@@ -4214 +4214 @@
-msgstr "Volgnummer.Artiest - Titel"
+msgstr "Volgnummer.Artiest - Title"
@@ -4240 +4240 @@
-msgstr "Nummers aan de collectie toevoegen"
+msgstr "Nummers aan de collective toevoegen"
@@ -4392 +4392 @@
-msgstr "Variabele bitsnelheid"
+msgstr "Variable bitsnelheid"
@@ -4396 +4396 @@
-msgstr "Beperkt variabele bitsnelheid"
+msgstr "Beperkt variable bitsnelheid"
@@ -4418 +4418 @@
-msgstr "Commentaar"
+msgstr "Commentary"
@@ -4468 +4468 @@
-# wordt getoond als attentieballon bij een nieuw nummer
+# wordt getoond also attentieballon bij een nieuw nummer
@@ -4571 +4571 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4617 +4617 @@
-msgstr "Commentaar"
+msgstr "Commentary"
@@ -4701 +4701 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4773 +4773 @@
-msgstr "Commentaar"
+msgstr "Commentary"
@@ -4902 +4902 @@
-# zoekopdracht is beter dan Zoeken (net als in nautilus)
+# zoekopdracht is better dan Zoeken (net also in nautilus)
--- ./ChangeLog	original
+++ ./ChangeLog	fixed
@@ -2616 +2616 @@
-    negotitation works better in 1.0.  Other changes are mostly about
+    negotiation works better in 1.0.  Other changes are mostly about
@@ -3531 +3531 @@
-    Make gir scanner find GStreamer .gir files in right prefix.
+    Make git scanner find GStreamer .git files in right prefix.
@@ -3932 +3932 @@
-    bindings/gi: make gir scanner find GStreamer .gir files in right prefix
+    bindings/gi: make git scanner find GStreamer .git files in right prefix
@@ -7256 +7256 @@
-    Update Simplifed Chinese (zh_CN) translation
+    Update Simplified Chinese (zh_CN) translation
@@ -7912 +7912 @@
-    Uploaded Ukranian
+    Uploaded Ukrainian
@@ -8883 +8883 @@
-    Uploaded Ukranian
+    Uploaded Ukrainian
@@ -11116 +11116 @@
-    fix builddir != srcdir GIR generation
+    fix builddir != srcdir GIT generation
@@ -11741 +11741 @@
-    Uploaded Ukranian
+    Uploaded Ukrainian
@@ -11750 +11750 @@
-    Uploaded Ukranian
+    Uploaded Ukrainian
@@ -11759 +11759 @@
-    Uploaded Ukranian
+    Uploaded Ukrainian
@@ -13062 +13062 @@
-    Uploaded Ukranian
+    Uploaded Ukrainian
@@ -15189 +15189 @@
-    [l10n] Updated Italian traslation
+    [l10n] Updated Italian translation
@@ -15810 +15810 @@
-    [ipod] reworkd delayed playlist renaming
+    [ipod] reworked delayed playlist renaming
@@ -16345 +16345 @@
-    logout button. When the response arrives later diplay extras such as
+    logout button. When the response arrives later display extras such as
@@ -16611 +16611 @@
-    audioscrobbler: use seperate submission queue files for each service and user
+    audioscrobbler: use separate submission queue files for each service and user
@@ -16922 +16922 @@
-    their popup menus to create relevent "Similar Artists" and "Top Fans"
+    their popup menus to create relevant "Similar Artists" and "Top Fans"
@@ -17312 +17312 @@
-    Seperate internal authentication code from user interface.
+    Separate internal authentication code from user interface.
@@ -17416 +17416 @@
-    an "authorisation token". When the token is recieved send the user
+    an "authorisation token". When the token is received send the user
@@ -18922 +18922 @@
-    Add some new Absolut radio stations
+    Add some new Absolute radio stations
@@ -22706 +22706 @@
-    removeable devices to 8 characters.
+    removable devices to 8 characters.
@@ -22720 +22720 @@
-    to a nonexistant source when we try to move to the next track.
+    to a nonexistent source when we try to move to the next track.
@@ -25921 +25921 @@
-    the file tags (which may be correct, or they may be nonexistant or junk)
+    the file tags (which may be correct, or they may be nonexistent or junk)
@@ -27592 +27592 @@
-    for explaination of the flags value we use to inhibit gnome-session
+    for explanation of the flags value we use to inhibit gnome-session
@@ -27765 +27765 @@
-    another workspace. This patch fixes it by explicitely requesting that the
+    another workspace. This patch fixes it by explicitly requesting that the
@@ -29781 +29781 @@
-     * Fixed some mispelled rhythmbox now changed with an entity
+     * Fixed some misspelled rhythmbox now changed with an entity
@@ -31764 +31764 @@
-    visualizer: hide mouse curser in fullscreen mode (fixes #501998)
+    visualizer: hide mouse cursor in fullscreen mode (fixes #501998)
@@ -31923 +31923 @@
-    Updated Brazilian Portugues translation by Og Maciel.
+    Updated Brazilian Portuguese translation by Og Maciel.
--- ./po/ca@valencia.po	original
+++ ./po/ca@valencia.po	fixed
@@ -106 +106 @@
-msgstr "Minuts"
+msgstr "Minutes"
@@ -182 +182 @@
-msgstr "Columnes visibles"
+msgstr "Columnes visible"
@@ -334 +334 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -337 +337 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -408 +408 @@
-msgstr "Seleccioneu una carpeta per als podcasts"
+msgstr "Seleccioneu una carpeta per also podcasts"
@@ -899 +899 @@
-"Este CD pot ser de més d'un àlbum. Seleccioneu quin àlbum és a sota i "
+"Este CD pot set de més d'un àlbum. Seleccioneu quin àlbum és a sota i "
@@ -1387 +1387 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -1573 +1573 @@
-msgstr "No s'ha pogut escriure el fitxer del projecte d'àudio %s: %s"
+msgstr "No s'ha pogut escriure el fitxer del projectile d'àudio %s: %s"
@@ -1579 +1579 @@
-msgstr "No s'ha pogut escriure el projecte d'àudio"
+msgstr "No s'ha pogut escriure el projectile d'àudio"
@@ -1583 +1583 @@
-msgstr "No s'ha pogut crear el projecte de CD d'àudio"
+msgstr "No s'ha pogut crear el projectile de CD d'àudio"
@@ -1709,2 +1709,2 @@
-msgstr[0] "%d minut"
-msgstr[1] "%d minuts"
+msgstr[0] "%d minute"
+msgstr[1] "%d minutes"
@@ -1929,2 +1929,2 @@
-"Esta llista de reproducció dura %s minuts. Això excedeix la mida d'un CD "
-"d'àudio estàndard. Si el suport de destinació és més gran que un CD d'àudio "
+"Esta llista de reproducció dura %s minutes. Això excedeix la mida d'un CD "
+"d'àudio estàndard. Si el support de destinació és més gran que un CD d'àudio "
@@ -1947 +1947 @@
-"No s'ha trobat espai temporal suficient per a convertir les peces d'àudio. "
+"No s'ha trobat espai temporal sufficient per a convertir les peces d'àudio. "
@@ -2528 +2528 @@
-msgstr "Suport per a emetre serveis tramesos per Internet"
+msgstr "Support per a emetre serveis tramesos per Internet"
@@ -2574 +2574 @@
-"ajudar als oients a descobrir artistes nous basant-se en els seus propis "
+"ajudar also oients a descobrir artistes nous basant-se en els seus propis "
@@ -2585 +2585 @@
-msgstr "     * La possibilitat de fer donacions directes als artistes."
+msgstr "     * La possibilitat de fer donacions directs also artistes."
@@ -2600 +2600 @@
-"El Jamendo és un model nou pels artistes per a promocionar, publicar i ser "
+"El Jamendo és un model nou pels artistes per a promocionar, publicar i set "
@@ -2621,2 +2621,2 @@
-"revisar-los o començar una discussió als fòrums.\n"
-"Si els agrada un artista poden donar-hi suport fent una donació."
+"revisar-los o començar una discussió also fòrums.\n"
+"Si els agrada un artista poden donar-hi support fent una donació."
@@ -2660 +2660 @@
-"Afig suport al Rhythmbox per a reproduir i baixar àlbums des de Jamendo"
+"Afig support al Rhythmbox per a reproduir i baixar àlbums des de Jamendo"
@@ -2890 +2890 @@
-"    * Àmplia informació biogràfica sobre cada músic, i foto d'artista --  "
+"    * Àmplia informació biogràfica sobre cada músic, i photo d'artista --  "
@@ -2967 +2967 @@
-"poden ser escoltades en segon pla - podeu treballar mentre escolteu la "
+"poden set escoltades en segon pla - podeu treballar mentre escolteu la "
@@ -3536 +3536 @@
-msgstr "Un connector exemple en Python sense funcionalitat"
+msgstr "Un connector example en Python sense funcionalitat"
@@ -3540 +3540 @@
-msgstr "Connector d'exemple en Python"
+msgstr "Connector d'example en Python"
@@ -3546 +3546 @@
-msgstr "Connector d'exemple"
+msgstr "Connector d'example"
@@ -3550 +3550 @@
-msgstr "Un connector d'exemple en C, sense funcionalitats"
+msgstr "Un connector d'example en C, sense funcionalitats"
@@ -3554 +3554 @@
-msgstr "Un connector d'exemple en Vala, sense funcionalitats"
+msgstr "Un connector d'example en Vala, sense funcionalitats"
@@ -3558 +3558 @@
-msgstr "Connector d'exemple en Vala"
+msgstr "Connector d'example en Vala"
@@ -3850 +3850 @@
-"Pareix que l'URL «%s» no és un canal de podcast. Pot ser que l'URL siga "
+"Pareix que l'URL «%s» no és un canal de podcast. Pot set que l'URL siga "
@@ -4103 +4103 @@
-msgstr "Fitxer buit"
+msgstr "Fitxer built"
@@ -4119,2 +4119,2 @@
-msgstr[0] "%ld minut"
-msgstr[1] "%ld minuts"
+msgstr[0] "%ld minute"
+msgstr[1] "%ld minutes"
@@ -4274 +4274 @@
-"Pot ser que la llista de reproducció estiga en un format desconegut o "
+"Pot set que la llista de reproducció estiga en un format desconegut o "
@@ -4646 +4646 @@
-msgstr "E_ines"
+msgstr "E_lines"
@@ -5040 +5040 @@
-msgstr "Connector d'exemple"
+msgstr "Connector d'example"
@@ -5115 +5115 @@
-msgstr "Camí d'exemple:"
+msgstr "Camí d'example:"
@@ -5550 +5550 @@
-msgstr "Vist per última vegada"
+msgstr "Visit per última vegada"
@@ -5934 +5934 @@
-msgstr "minuts"
+msgstr "minutes"
@@ -6036 +6036 @@
-#~ msgstr "Artistes que agraden als fans de %s"
+#~ msgstr "Artistes que agraden also fans de %s"
@@ -6339 +6339 @@
-# FIXME: s'hauria d'enviar un informe d'error. Hauria de ser
+# FIXME: s'hauria d'enviar un informe d'error. Hauria de set
@@ -6344 +6344 @@
-# FIXME: s'hauria d'enviar un informe d'error. Hauria de ser
+# FIXME: s'hauria d'enviar un informe d'error. Hauria de set
--- ./po/ko.po	original
+++ ./po/ko.po	fixed
@@ -1583 +1583 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -3366 +3366 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/bg.po	original
+++ ./po/bg.po	fixed
@@ -1297 +1297 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
--- ./po/da.po	original
+++ ./po/da.po	fixed
@@ -23 +23 @@
-# et andet sted, som indeholder dette ord.  Så med mindre oversættelsen
+# et andet sted, some indeholder dette ord.  Så med mindre oversættelsen
@@ -148 +148 @@
-"Rhythmbox er et musikhåndteringsprogram som er designet med særligt henblik "
+"Rhythmbox er et musikhåndteringsprogram some er designated med særligt henblik "
@@ -200 +200 @@
-msgstr "Følg spor som afspilles"
+msgstr "Følg spor some afspilles"
@@ -284 +284 @@
-msgstr "Tilføj hvis mindst ét kriterium p_asser"
+msgstr "Tilføj hvis mindst ét kriterium p_assert"
@@ -341 +341 @@
-"_Installér yderligere programmer som er nødvendige for at bruge dette format"
+"_Installér yderligere programmer some er nødvendige for at bruge dette format"
@@ -429 +429 @@
-msgstr "Vælg et sted som indeholder musik, som skal føjes til din samling:"
+msgstr "Vælg et sted some indeholder musik, some skal føjes til din samling:"
@@ -441 +441 @@
-msgstr "Kopiér filer som er uden for musiksamlingen"
+msgstr "Kopiér filer some er uden for musiksamlingen"
@@ -481 +481 @@
-msgstr "Kunstner/Kunstner - Album/Kunstner (Album) - 01 - Titel.ogg"
+msgstr "Kunstner/Kunstner - Album/Kunstner (Album) - 01 - Title.ogg"
@@ -638 +638 @@
-"Abonnér på podcasts for at hente nye afsnit efterhånden som de udgives."
+"Abonnér på podcasts for at hente nye afsnit efterhånden some de udgives."
@@ -646 +646 @@
-msgstr "Titel:"
+msgstr "Title:"
@@ -878 +878 @@
-msgstr "_Titel:"
+msgstr "_Title:"
@@ -1124 +1124 @@
-msgstr "Lyd_formater:"
+msgstr "Lyd_formatter:"
@@ -1210 +1210 @@
-msgstr "Understøttelse for afspilning af lyd-cd'er som musikkilde"
+msgstr "Understøttelse for afspilning af lyd-cd'er some musikkilde"
@@ -1228 +1228 @@
-msgstr "Kunne ikke finde noget GStreamer-cd-kildemodul"
+msgstr "Kunne ikke find noget GStreamer-cd-kildemodul"
@@ -1250 +1250 @@
-msgstr "Kunne ikke finde dette album på MusicBrainz."
+msgstr "Kunne ikke find dette album på MusicBrainz."
@@ -1796 +1796 @@
-msgstr "Del musik og afspil delt musik over dit lokale netværk"
+msgstr "Del musik og afspil delt musik over dit locale netværk"
@@ -1966 +1966 @@
-msgstr "Gennemse forskellige lokale og internet-mediekilder"
+msgstr "Gennemse forskellige locale og internet-mediekilder"
@@ -2075 +2075 @@
-"hvilket vil slette alle metadataene, for sange som allerede er tilstede. "
+"hvilket vil slette alle metadataene, for sange some allerede er tilstede. "
@@ -2148 +2148 @@
-msgstr "Adresse på internet-radiostation:"
+msgstr "Address på internet-radiostation:"
@@ -2275 +2275 @@
-msgstr "Magnatune er et online pladeselskab som ikke er ondsindet.\n"
+msgstr "Magnatune er et online pladeselskab some ikke er ondsindet.\n"
@@ -2312 +2312 @@
-msgstr "Du kan finde mere information på "
+msgstr "Du kan find mere information på "
@@ -2340 +2340 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2726 +2726 @@
-"fejlsøgningsprogram som f.eks. vimspector, nvim-dap eller Visual Studio Code."
+"fejlsøgningsprogram some f.eks. vimspector, nvim-dap eller Visual Studio Code."
@@ -2857 +2857 @@
-msgstr "Titel"
+msgstr "Title"
@@ -2920 +2920 @@
-"forkert adresse, eller kilden kan være ødelagt. Skal Rhythmbox at forsøge at "
+"forkert address, eller kilden kan være ødelagt. Skal Rhythmbox at forsøge at "
@@ -2926 +2926 @@
-msgstr "Adresse allerede tilføjet"
+msgstr "Address allerede tilføjet"
@@ -2934 +2934 @@
-"Adressen “%s” er allerede blevet tilføjet som en radiostation. Hvis det er "
+"Adressen “%s” er allerede blevet tilføjet some en radiostation. Hvis det er "
@@ -2949 +2949 @@
-msgstr "Kilden indeholder ingen elementer, som er mulige at hente"
+msgstr "Kilden indeholder ingen elementer, some er mulige at hente"
@@ -3048 +3048 @@
-msgstr "Vis programmets version"
+msgstr "Vis programmers version"
@@ -3096 +3096 @@
-msgstr "Afspil en specifik adresse, importer den om nødvendigt"
+msgstr "Afspil en specifik address, importer den om nødvendigt"
@@ -3100 +3100 @@
-msgstr "Adresse til afspilning"
+msgstr "Address til afspilning"
@@ -3112 +3112 @@
-msgstr "Udskriv titel og kunstner for den nuværende sang"
+msgstr "Udskriv title og kunstner for den nuværende sang"
@@ -3248 +3248 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3333 +3333 @@
-msgstr[0] "%ld minut"
+msgstr[0] "%ld minute"
@@ -3388 +3388 @@
-msgstr "Python eksempel-modul"
+msgstr "Python eksempel-module"
@@ -3392 +3392 @@
-msgstr "Et eksempel-modul i python uden egenskaber"
+msgstr "Et eksempel-module i python uden egenskaber"
@@ -3402 +3402 @@
-msgstr "Eksempel-modul"
+msgstr "Eksempel-module"
@@ -3406 +3406 @@
-msgstr "Et eksempel-modul i C uden egenskaber"
+msgstr "Et eksempel-module i C uden egenskaber"
@@ -3414 +3414 @@
-msgstr "Et eksempel-modul i Vala uden egenskaber"
+msgstr "Et eksempel-module i Vala uden egenskaber"
@@ -3441,2 +3441,2 @@
-"det iht. GNU General Public License som er udgivet af Free Software\n"
-"Foundation; enten version 2 af licensen, eller (selvvalgt) hvilken som\n"
+"det iht. GNU General Public License some er udgivet af Free Software\n"
+"Foundation; enten version 2 af licensen, eller (selvvalgt) hvilken some\n"
@@ -3536 +3536 @@
-msgstr "MPEG version 3.0-adresse"
+msgstr "MPEG version 3.0-address"
@@ -3552 +3552 @@
-msgstr "Afspilningsliste uden titel"
+msgstr "Afspilningsliste uden title"
@@ -3764,5 +3764,5 @@
-"%d fil kan ikke overføres, da den skal konverteres til et format som mål-"
-"enheden understøtter, men der er  ingen brugbare indkodningsprofiler "
-"tilgængelige"
-msgstr[1] ""
-"%d filer kan ikke overføres, da de skal konverteres til et format som mål-"
+"%d fil kan ikke overføres, da den skal konverteres til et format some mål-"
+"enheden understøtter, men der er  ingen brugbare indkodningsprofiler "
+"tilgængelige"
+msgstr[1] ""
+"%d filer kan ikke overføres, da de skal konverteres til et format some mål-"
@@ -3795,5 +3795,5 @@
-"som mål-enheden understøtter:\n"
-"%s"
-msgstr[1] ""
-"Yderligere programmer er nødvendige for at konvertere %d filer til et format "
-"som mål-enheden understøtter:\n"
+"some mål-enheden understøtter:\n"
+"%s"
+msgstr[1] ""
+"Yderligere programmer er nødvendige for at konvertere %d filer til et format "
+"some mål-enheden understøtter:\n"
@@ -3907 +3907 @@
-msgstr "Nummer - Titel"
+msgstr "Nummer - Title"
@@ -3911 +3911 @@
-msgstr "Kunstner - Titel"
+msgstr "Kunstner - Title"
@@ -3915 +3915 @@
-msgstr "Kunstner - Nummer - Titel"
+msgstr "Kunstner - Nummer - Title"
@@ -3919 +3919 @@
-msgstr "Kunstner (Album) - Nummer - Titel"
+msgstr "Kunstner (Album) - Nummer - Title"
@@ -3923 +3923 @@
-msgstr "Nummer. Kunstner - Titel"
+msgstr "Nummer. Kunstner - Title"
@@ -4100 +4100 @@
-msgstr "Variabel bitrate"
+msgstr "Variable bitrate"
@@ -4104 +4104 @@
-msgstr "Begrænset variabel bitrate"
+msgstr "Begrænset variable bitrate"
@@ -4221 +4221 @@
-msgstr[0] "Importér %d vist spor"
+msgstr[0] "Importér %d visit spor"
@@ -4272 +4272 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4347 +4347 @@
-msgstr "Slag per minut"
+msgstr "Slag per minute"
@@ -4397 +4397 @@
-msgstr "Titel"
+msgstr "Title"
@@ -4470 +4470 @@
-msgstr "Slag per minut"
+msgstr "Slag per minute"
@@ -4684 +4684 @@
-#~ msgstr "Ugyldig adresse"
+#~ msgstr "Ugyldig address"
--- ./po/vi.po	original
+++ ./po/vi.po	fixed
@@ -2147 +2147 @@
-msgstr "Không thể thay đổi thuộc tính đài"
+msgstr "Không thể they đổi thuộc tính đài"
@@ -2152 +2152 @@
-msgstr "Không thể thay đổi URI của đài sang %s, đài đó đã có rồi"
+msgstr "Không thể they đổi URI của đài sang %s, đài đó đã có rồi"
@@ -3189 +3189 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3428 +3428 @@
-msgstr "Không cập nhật thư viện theo thay đổi trong tập tin"
+msgstr "Không cập nhật thư viện theo they đổi trong tập tin"
@@ -3665 +3665 @@
-msgstr "Đã có tập tin \"%s\". Bạn có muốn thay thế nó không?"
+msgstr "Đã có tập tin \"%s\". Bạn có muốn they thế nó không?"
@@ -3673 +3673 @@
-msgstr "_Thay thế"
+msgstr "_They thế"
@@ -4830 +4830 @@
-#~ msgstr "Thay đổi khả năng nhìn thấy của khung ngữ cảnh"
+#~ msgstr "They đổi khả năng nhìn thấy của khung ngữ cảnh"
@@ -4889 +4889 @@
-#~ msgstr "Thay đổi tên của danh mục nhạc"
+#~ msgstr "They đổi tên của danh mục nhạc"
@@ -4994 +4994 @@
-#~ msgstr "Thay đổi danh mục nhạc tự động này"
+#~ msgstr "They đổi danh mục nhạc tự động này"
@@ -5059 +5059 @@
-#~ msgstr "Thay đổi trạng thái của chế độ tiệc"
+#~ msgstr "They đổi trạng thái của chế độ tiệc"
@@ -5078 +5078 @@
-#~ msgstr "Thay đổi âm lượng"
+#~ msgstr "They đổi âm lượng"
@@ -5342 +5342 @@
-#~ "Thông tin chi tiết tài khoản của bạn đã thay đổi. Thay đổi sẽ được áp "
+#~ "Thông tin chi tiết tài khoản của bạn đã they đổi. They đổi sẽ được áp "
@@ -5381 +5381 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
@@ -5397 +5397 @@
-#~ msgstr "Lỗi GStreamer: chưa thay đổi tình trạng"
+#~ msgstr "Lỗi GStreamer: chưa they đổi tình trạng"
@@ -5593 +5593 @@
-#~ msgstr "Hiển thị thông báo các thay đổi bài nhạc và sự kiện khác"
+#~ msgstr "Hiển thị thông báo các they đổi bài nhạc và sự kiện khác"
@@ -5914 +5914 @@
-#~ "Vui lòng thay thế đĩa trong ổ bằng một đĩa CD trắng hoặc loại ghi lại "
+#~ "Vui lòng they thế đĩa trong ổ bằng một đĩa CD trắng hoặc loại ghi lại "
@@ -5921 +5921 @@
-#~ msgstr "Vui lòng thay thế đĩa đang trong ổ đĩa bằng một đĩa CD trắng."
+#~ msgstr "Vui lòng they thế đĩa đang trong ổ đĩa bằng một đĩa CD trắng."
--- ./po/ms.po	original
+++ ./po/ms.po	fixed
@@ -288 +288 @@
-msgstr "Tre_k"
+msgstr "Tree_k"
@@ -409 +409 @@
-msgstr "Padam pilihan"
+msgstr "Param pilihan"
--- ./po/dz.po	original
+++ ./po/dz.po	fixed
@@ -247 +247 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/gl.po	original
+++ ./po/gl.po	fixed
@@ -42 +42 @@
-msgstr "Produciuse un erro ao abrir o dispositivo de saída: %s"
+msgstr "Produciuse un error ao abrir o dispositivo de saída: %s"
@@ -48 +48 @@
-"Produciuse un erro ao crear o elemento «playbin»; comprobe a súa instalación "
+"Produciuse un error ao crear o elemento «playbin»; comprobe a súa instalación "
@@ -55 +55 @@
-"Produciuse un erro ao crear o elemento %s; comprobe a súa instalación de "
+"Produciuse un error ao crear o elemento %s; comprobe a súa instalación de "
@@ -63 +63 @@
-"Produciuse un erro ao ligar un novo fluxo dentro do pipeline do GStreamer"
+"Produciuse un error ao ligar un novo fluxo dentro do pipeline do GStreamer"
@@ -68 +68 @@
-msgstr "Produciuse un erro ao iniciar un novo fluxo"
+msgstr "Produciuse un error ao iniciar un novo fluxo"
@@ -74 +74 @@
-msgstr "Produciuse un erro ao abrir o dispositivo de saída"
+msgstr "Produciuse un error ao abrir o dispositivo de saída"
@@ -81 +81 @@
-"Produciuse un erro ao crear o elemento GStreamer; comprobe a súa instalación"
+"Produciuse un error ao crear o elemento GStreamer; comprobe a súa instalación"
@@ -87 +87 @@
-"Produciuse un erro ao crear o elemento de saída de son; comprobe a súa "
+"Produciuse un error ao crear o elemento de saída de son; comprobe a súa "
@@ -98 +98 @@
-"Produciuse un erro ao ligar a liña de procesamento do GStreamer; comprobe a "
+"Produciuse un error ao ligar a liña de procesamento do GStreamer; comprobe a "
@@ -105 +105 @@
-"Produciuse un erro ao crear a liña de procesamento do GStreamer para "
+"Produciuse un error ao crear a liña de procesamento do GStreamer para "
@@ -358 +358 @@
-msgstr "_Artistas e álbums"
+msgstr "_Artists e álbums"
@@ -362 +362 @@
-msgstr "_Xéneros e artistas"
+msgstr "_Xéneros e artists"
@@ -366 +366 @@
-msgstr "Xén_eros, artistas e álbums"
+msgstr "Xén_eros, artists e álbums"
@@ -370 +370 @@
-msgstr "Columnas visíbeis"
+msgstr "Columns visíbeis"
@@ -652 +652 @@
-msgstr "Subscribirse"
+msgstr "Subscriber"
@@ -661 +661 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -875 +875 @@
-msgstr "Ordenación dos _artistas:"
+msgstr "Ordenación dos _artists:"
@@ -879 +879 @@
-msgstr "Ordenación dos _artistas:"
+msgstr "Ordenación dos _artists:"
@@ -907 +907 @@
-msgstr "Mensaxe de erro"
+msgstr "Mensaxe de error"
@@ -1095 +1095 @@
-"Produciuse un erro ao crear o elemento de orixe; comprobe a súa instalación"
+"Produciuse un error ao crear o elemento de orixe; comprobe a súa instalación"
@@ -1102 +1102 @@
-"Produciuse un erro ao crear o elemento «decodebin»; comprobe a súa "
+"Produciuse un error ao crear o elemento «decodebin»; comprobe a súa "
@@ -1111 +1111 @@
-"Produciuse un erro ao crear o elemento «giostreamsink»; comprobe a súa "
+"Produciuse un error ao crear o elemento «giostreamsink»; comprobe a súa "
@@ -1137 +1137 @@
-msgstr "Número de serie:"
+msgstr "Número de series:"
@@ -1219 +1219 @@
-msgstr "_Ordenación de artistas:"
+msgstr "_Ordenación de artists:"
@@ -1309 +1309 @@
-msgstr "Erro do servidor de MusicBrainz"
+msgstr "Error do servidor de MusicBrainz"
@@ -1384 +1384 @@
-msgstr "Artistas preferidos"
+msgstr "Artists preferidos"
@@ -1412 +1412 @@
-msgstr "Erro de autenticación"
+msgstr "Error de autenticación"
@@ -1459 +1459 @@
-msgstr "Produciuse un erro na autenticación. Tente iniciar a sesión de novo."
+msgstr "Produciuse un error na autenticación. Tente iniciar a sesión de novo."
@@ -1463 +1463 @@
-msgstr "Produciuse un erro na conexión. Tente iniciar a sesión de novo."
+msgstr "Produciuse un error na conexión. Tente iniciar a sesión de novo."
@@ -1492 +1492 @@
-msgstr "Escoitar a radio de artistas _semellantes"
+msgstr "Escoitar a radio de artists _semellantes"
@@ -1625 +1625 @@
-msgstr "Produciuse un erro ao sintonizar a emisora: non hai resposta"
+msgstr "Produciuse un error ao sintonizar a emisora: non hai resposta"
@@ -1658 +1658 @@
-msgstr "Produciuse un erro ao sintonizar a emisora: %i - %s"
+msgstr "Produciuse un error ao sintonizar a emisora: %i - %s"
@@ -1662 +1662 @@
-msgstr "Produciuse un erro ao sintonizar a emisora: reposta inesperada"
+msgstr "Produciuse un error ao sintonizar a emisora: reposta inesperada"
@@ -1666 +1666 @@
-msgstr "Produciuse un erro ao sintonizar a emisora: resposta incorrecta"
+msgstr "Produciuse un error ao sintonizar a emisora: resposta incorrecta"
@@ -1744 +1744 @@
-"Mostra información relativa ao artista e a canción que está neste momento "
+"Mostra información relativa ao artista e a canción que está neste memento "
@@ -1931 +1931 @@
-msgstr "Artistas"
+msgstr "Artists"
@@ -2322 +2322 @@
-msgstr "    * Todos os álbums e artistas escóllense á man"
+msgstr "    * Todos os álbums e artists escóllense á man"
@@ -2542 +2542 @@
-"informe de erro."
+"informe de error."
@@ -2551 +2551 @@
-msgstr "Erro de descarga"
+msgstr "Error de descarga"
@@ -2560 +2560 @@
-"Produciuse un erro ao tentar mercar o álbum.\n"
+"Produciuse un error ao tentar mercar o álbum.\n"
@@ -2566 +2566 @@
-msgstr "Erro"
+msgstr "Error"
@@ -2575,2 +2575,2 @@
-"Produciuse un erro ao tentar mercar o álbum.\n"
-"O texto do erro é:\n"
+"Produciuse un error ao tentar mercar o álbum.\n"
+"O texto do error é:\n"
@@ -2614 +2614 @@
-msgstr "Produciuse un erro ao abrir o ficheiro temporal: %s"
+msgstr "Produciuse un error ao abrir o ficheiro temporal: %s"
@@ -2622 +2622 @@
-msgstr "Erro no dispositivo de reprodución multimedia"
+msgstr "Error no dispositivo de reprodución multimedia"
@@ -2641 +2641 @@
-msgstr "Produciuse un erro ao copiar o ficheiro desde o dispositivo MTP: %s"
+msgstr "Produciuse un error ao copiar o ficheiro desde o dispositivo MTP: %s"
@@ -2939 +2939 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2974 +2974 @@
-msgstr "Erro no podcast"
+msgstr "Error no podcast"
@@ -2983 +2983 @@
-msgstr "Produciuse un erro ao crear o cartafol de descarga podcast"
+msgstr "Produciuse un error ao crear o cartafol de descarga podcast"
@@ -3020 +3020 @@
-"O URL «%s» non semella ser un fornecedor de podcast. Pode ser que o URL sexa "
+"O URL «%s» non semella set un fornecedor de podcast. Pode set que o URL sexa "
@@ -3094 +3094 @@
-msgstr "Erro do podcast"
+msgstr "Error do podcast"
@@ -3285 +3285 @@
-msgstr "Iniciar o modo interactivo"
+msgstr "Iniciar o modo interaction"
@@ -3353 +3353 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3423 +3423 @@
-msgstr "o unicode non é correcto na mensaxe de erro"
+msgstr "o unicode non é correcto na mensaxe de error"
@@ -3702 +3702 @@
-msgstr "Produciuse un erro ao gardar a información da canción"
+msgstr "Produciuse un error ao gardar a información da canción"
@@ -3745 +3745 @@
-msgstr "Erro de fluxo"
+msgstr "Error de fluxo"
@@ -3820 +3820 @@
-msgstr "Produciuse un erro ao crear o reprodutor: %s"
+msgstr "Produciuse un error ao crear o reprodutor: %s"
@@ -3906 +3906 @@
-msgstr "Produciuse un erro ao transferir a pista"
+msgstr "Produciuse un error ao transferir a pista"
@@ -3923 +3923 @@
-msgstr "Buscar artistas"
+msgstr "Buscar artists"
@@ -3980 +3980 @@
-msgstr "Erro de importación"
+msgstr "Error de importación"
@@ -3986,2 +3986,2 @@
-msgstr[0] "%d erro de importación"
-msgstr[1] "%d erros de importación"
+msgstr[0] "%d error de importación"
+msgstr[1] "%d errors de importación"
@@ -4047 +4047 @@
-msgstr "Produciuse un erro ao transferir a pista"
+msgstr "Produciuse un error ao transferir a pista"
@@ -4275 +4275 @@
-msgstr "Erro de reprodución"
+msgstr "Error de reprodución"
@@ -4327 +4327 @@
-msgstr[1] "Todo sos %d artistas (%d)"
+msgstr[1] "Todo sos %d artists (%d)"
@@ -4911 +4911 @@
-#~ msgstr "Produciuse un erro ao sintonizar a emisora: %s"
+#~ msgstr "Produciuse un error ao sintonizar a emisora: %s"
@@ -5010 +5010 @@
-#~ msgstr "Subscribirse a un fornecedor de podcasts novo"
+#~ msgstr "Subscriber a un fornecedor de podcasts novo"
@@ -5229 +5229 @@
-#~ "Este CD podería ser máis dun álbum. Seleccione abaixo que álbum é e prema "
+#~ "Este CD podería set máis dun álbum. Seleccione abaixo que álbum é e prema "
@@ -5535 +5535 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
@@ -5548 +5548 @@
-#~ msgstr "Hai un problema interno de GStreamer; arquive un erro"
+#~ msgstr "Hai un problema interno de GStreamer; arquive un error"
@@ -5551 +5551 @@
-#~ msgstr "Produciuse un erro de comunicación de D-BUS"
+#~ msgstr "Produciuse un error de comunicación de D-BUS"
@@ -5555 +5555 @@
-#~ "Produciuse un erro ao crear o elemento %s; comprobe a súa instalación"
+#~ "Produciuse un error ao crear o elemento %s; comprobe a súa instalación"
@@ -5558 +5558 @@
-#~ msgstr "Produciuse un erro de GStreamer: fallou ao cambiar o estado"
+#~ msgstr "Produciuse un error de GStreamer: fallou ao cambiar o estado"
@@ -5601 +5601 @@
-#~ msgstr "Produciuse un erro ao crear unha liña de procesamento"
+#~ msgstr "Produciuse un error ao crear unha liña de procesamento"
@@ -5640 +5640 @@
-#~ "Produciuse un erro ao gravar no CD:\n"
+#~ "Produciuse un error ao gravar no CD:\n"
@@ -5644 +5644 @@
-#~ msgstr "Produciuse un erro ao gravar no CD"
+#~ msgstr "Produciuse un error ao gravar no CD"
@@ -5693 +5693 @@
-#~ msgstr "Produciuse un erro ao gravar. Quere tentalo outra vez?"
+#~ msgstr "Produciuse un error ao gravar. Quere tentalo outra vez?"
@@ -5699 +5699 @@
-#~ msgstr "Produciuse un erro na gravación de son"
+#~ msgstr "Produciuse un error na gravación de son"
@@ -5702 +5702 @@
-#~ msgstr "Produciuse un erro de conversión de son"
+#~ msgstr "Produciuse un error de conversión de son"
@@ -5705 +5705 @@
-#~ msgstr "Produciuse un erro de gravación"
+#~ msgstr "Produciuse un error de gravación"
@@ -5781 +5781 @@
-#~ msgstr "Produciuse un erro ao crear a gravadora: %s"
+#~ msgstr "Produciuse un error ao crear a gravadora: %s"
@@ -5804 +5804 @@
-#~ "Esta lista de reprodución dura %s minutos. Isto excede o tempo dun CD de "
+#~ "Esta lista de reprodución dura %s minutos. Isto exceed o tempo dun CD de "
@@ -5842 +5842 @@
-#~ "dispositivos de rede UPnP/DLNA, e activa Rhythmbox para ser controlado "
+#~ "dispositivos de rede UPnP/DLNA, e activa Rhythmbox para set controlado "
@@ -5873 +5873 @@
-#~ "    * Un marco legal que protexe os artistas (grazas ás licenzas da "
+#~ "    * Un marco legal que protexe os artists (grazas ás licenzas da "
@@ -5882 +5882 @@
-#~ "iRATE para axudar os oíntes a descubrir novos artistas segundo as súas "
+#~ "iRATE para axudar os oíntes a descubrir novos artists segundo as súas "
@@ -5890 +5890 @@
-#~ msgstr "     * A posibilidade de facer doazóns directas aos artistas."
+#~ msgstr "     * A posibilidade de facer doazóns directas aos artists."
@@ -5902 +5902 @@
-#~ "Jamendo é un modelo novo para que os artistas se promocionen, publiquen e "
+#~ "Jamendo é un modelo novo para que os artists se promocionen, publiquen e "
@@ -5928 +5928 @@
-#~ "En Jamendo, os artistas distribúen a súa música segundo os termos das "
+#~ "En Jamendo, os artists distribúen a súa música segundo os termos das "
@@ -5971 +5971 @@
-#~ msgstr "Produciuse un erro buscando p2plink para o álbum %s en jamendo.com"
+#~ msgstr "Produciuse un error buscando p2plink para o álbum %s en jamendo.com"
@@ -5974 +5974 @@
-#~ msgstr "Produciuse un erro buscando o artista %s en jamendo.com"
+#~ msgstr "Produciuse un error buscando o artista %s en jamendo.com"
@@ -6071 +6071 @@
-#~ "Produciuse un erro ao ligar un novo fluxo visual dentro da liña de "
+#~ "Produciuse un error ao ligar un novo fluxo visual dentro da liña de "
@@ -6134 +6134 @@
-#~ msgstr "Erro do engadido"
+#~ msgstr "Error do engadido"
@@ -6211 +6211 @@
-#~ msgstr "Artistas semellantes a %s"
+#~ msgstr "Artists semellantes a %s"
@@ -6217 +6217 @@
-#~ msgstr "Artistas que lles gustan aos seguidores de %s"
+#~ msgstr "Artists que lles gustan aos seguidores de %s"
@@ -6280 +6280 @@
-#~ msgstr "Produciuse un erro ao iniciar a reprodución de %s"
+#~ msgstr "Produciuse un error ao iniciar a reprodución de %s"
@@ -6398 +6398 @@
-#~ msgstr "Produciuse un erro ao mercar"
+#~ msgstr "Produciuse un error ao mercar"
--- ./po/nds.po	original
+++ ./po/nds.po	fixed
@@ -300 +300 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/ar.po	original
+++ ./po/ar.po	fixed
@@ -1431 +1431 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -5121 +5121 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/zh_TW.po	original
+++ ./po/zh_TW.po	fixed
@@ -3305 +3305 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -5554 +5554 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/nn.po	original
+++ ./po/nn.po	fixed
@@ -154 +154 @@
-msgstr "Tekst under ikon"
+msgstr "Text under ikon"
@@ -158 +158 @@
-msgstr "Tekst attmed ikon"
+msgstr "Text attmed ikon"
@@ -162 +162 @@
-msgstr "Berre tekst"
+msgstr "Berre text"
@@ -325 +325 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -606 +606 @@
-msgstr "Oppgje fila som inneheld lagra innstillingar"
+msgstr "Oppgje fila some inneheld lagra innstillingar"
@@ -758 +758 @@
-msgstr "Internt problem i GStreamer. Send inn ein feilrapport"
+msgstr "Internet problem i GStreamer. Send inn ein feilrapport"
@@ -803 +803 @@
-msgstr "Klarte ikkje å oppretta elementa som skriv merkelappar"
+msgstr "Klarte ikkje å oppretta elementa some skriv merkelappar"
@@ -841 +841 @@
-msgstr "Støtte for å spela lyd-CD-ar som ei musikkjelde"
+msgstr "Støtte for å spela lyd-CD-ar some ei musikkjelde"
@@ -865 +865 @@
-"<i>Hald fram</i>."
+"<i>Held fram</i>."
@@ -869 +869 @@
-msgstr "_Hald fram"
+msgstr "_Held fram"
@@ -895 +895 @@
-msgstr "Vel spor som skal hentast ut"
+msgstr "Vel spor some skal hentast ut"
@@ -1064 +1064 @@
-msgstr "Registrer ein konto"
+msgstr "Register ein konto"
@@ -1128 +1128 @@
-msgstr "Artistar som liknar %s"
+msgstr "Artistar some liknar %s"
@@ -1156 +1156 @@
-msgstr "Spor som er likt av gruppa %s"
+msgstr "Spor some er likt av gruppa %s"
@@ -1186 +1186 @@
-msgstr "Spor som %s likar"
+msgstr "Spor some %s likar"
@@ -1212 +1212 @@
-msgstr "Merk denne songen som likt"
+msgstr "Merk denne songen some likt"
@@ -1232 +1232 @@
-msgstr "Last ned song"
+msgstr "Last need song"
@@ -1236 +1236 @@
-msgstr "Last ned denne songen"
+msgstr "Last need denne songen"
@@ -1672 +1672 @@
-msgstr "Denne %s ser ut til å allereie innehalda data."
+msgstr "Denne %s set ut til å allereie innehalda data."
@@ -1790 +1790 @@
-msgstr "Vis relatert informasjon om songen og artisten som vert spelt."
+msgstr "Vis relatert informasjon om songen og artisten some vert spelt."
@@ -1903 +1903 @@
-msgstr "Del musikk og spel delt musikk på ditt lokale nettverk"
+msgstr "Del musikk og spel delt musikk på ditt locale nettverk"
@@ -1928 +1928 @@
-msgstr "«%s» er allereie i bruk som namn på delt musikk. Vel eit anna."
+msgstr "«%s» er allereie i bruk some namn på delt musikk. Vel eit anna."
@@ -2036 +2036 @@
-msgstr "Modell:"
+msgstr "Model:"
@@ -2097 +2097 @@
-"Oppdaterer lynmeldingsstatusen etter songane som vert spelte (verkar med "
+"Oppdaterer lynmeldingsstatusen etter songane some vert spelte (verkar med "
@@ -2181,3 +2181,3 @@
-"Rhythmbox har oppdaga ei eining som sannsynlegvis er ein ikkje-initiert "
-"eller øydelagt iPod. Han må initierast før han kan nyttast i Rhythmbox, men "
-"dette vil øydeleggja songinformasjonen som allereie er på. Fyll ut "
+"Rhythmbox har oppdaga ei eining some sannsynlegvis er ein ikkje-initiert "
+"eller øydelagt iPod. Han må initierast før han kan nyttast i Rhythmbox, men "
+"dette vil øydeleggja songinformasjonen some allereie er på. Fyll ut "
@@ -2194 +2194 @@
-msgstr "_Modell:"
+msgstr "_Model:"
@@ -2263 +2263 @@
-msgstr "<b>Last Ned</b>"
+msgstr "<b>Last Need</b>"
@@ -2295 +2295 @@
-"     * Eit lovleg rammeverk som vernar om artistane (takka vere Creative "
+"     * Eit lovleg rammeverk some vernar om artistane (takka vere Creative "
@@ -2306 +2306 @@
-"       kriterier, slik som kor i verda dei er."
+"       kriterier, slik some kor i verda dei er."
@@ -2334 +2334 @@
-msgstr "Jamendo er den einaste plattformen som slår saman:"
+msgstr "Jamendo er den einaste plattformen some slår saman:"
@@ -2346 +2346 @@
-"Dei som likar ein artist kan støtta han/henne ved å donera pengar."
+"Dei some likar ein artist kan støtta han/henne ved å donera pengar."
@@ -2358,2 +2358,2 @@
-"Kort sagt, du kan lasta ned, remiksa og dela musikken fritt.\n"
-"Det er ein «somme rettar reserverte»-lisens, perfekt for det nye århundret."
+"Kort sagt, du kan lasta need, remiksa og dela musikken fritt.\n"
+"Det er ein «some rettar reserverte»-lisens, perfekt for det nye århundret."
@@ -2369,2 +2369,2 @@
-"digital distribusjon, så som\n"
-"p2p-nettverk slik som BitTorrent og eMule, for å lovleg dela album nesten "
+"digital distribusjon, så some\n"
+"p2p-nettverk slik some BitTorrent og eMule, for å lovleg dela album nesten "
@@ -2381 +2381 @@
-"Legg til støtte i Rhythmbox for å spela av og lasta ned album frå Jamendo"
+"Legg til støtte i Rhythmbox for å spela av og lasta need album frå Jamendo"
@@ -2394 +2394 @@
-msgstr "Last ned dette albumet med BitTorrent"
+msgstr "Last need dette albumet med BitTorrent"
@@ -2638 +2638 @@
-"som har meir eller mindre det same (gigantiske) utvalet\n"
+"some har meir eller mindre det same (gigantiske) utvalet\n"
@@ -2657 +2657 @@
-"    * Ikkje knytta til dei store plateselskapa – for dei som hatar "
+"    * Ikkje knytta til dei store plateselskapa – for dei some hatar "
@@ -2677 +2677 @@
-"    * Fullkvalitetsnedlastingar (CD_kopi) er tilgjengeleg når du lastar ned "
+"    * Fullkvalitetsnedlastingar (CD_kopi) er tilgjengeleg når du lastar need "
@@ -2697 +2697 @@
-"    * Varierande prissystem gjer at du kan betala så lite som 5 dollar for "
+"    * Varierande prissystem gjer at du kan betala så lite some 5 dollar for "
@@ -2717 +2717 @@
-"Magnatune er eit nettplateselskap som ikkje er vondsinna. Viktige "
+"Magnatune er eit nettplateselskap some ikkje er vondsinna. Viktige "
@@ -2826 +2826 @@
-msgstr "Januar (01)"
+msgstr "January (01)"
@@ -2874 +2874 @@
-msgstr "Last ned kjøpt musikk om igjen frå "
+msgstr "Last need kjøpt musikk om igjen frå "
@@ -2934 +2934 @@
-msgstr "Lastar ned album frå Magnatune"
+msgstr "Lastar need album frå Magnatune"
@@ -3001 +3001 @@
-msgstr "Last ned album"
+msgstr "Last need album"
@@ -3005 +3005 @@
-msgstr "Last ned dette albumet frå Magnatune"
+msgstr "Last need dette albumet frå Magnatune"
@@ -3021 +3021 @@
-msgstr "Stopp nedlasting av kjøpte album"
+msgstr "Stop nedlasting av kjøpte album"
@@ -3207 +3207 @@
-"GStreamer-elementet som trengst for ReplayGain-prosessering er ikkje "
+"GStreamer-elementet some trengst for ReplayGain-prosessering er ikkje "
@@ -3274 +3274 @@
-msgstr "Vel musikk som skal spelast"
+msgstr "Vel musikk some skal spelast"
@@ -3337 +3337 @@
-msgstr "Aldri vist"
+msgstr "Aldri visit"
@@ -3349 +3349 @@
-msgstr "Vist når hovudvindauget er synleg"
+msgstr "Visit når hovudvindauget er synleg"
@@ -3377 +3377 @@
-msgstr "Start eller stopp visualisering"
+msgstr "Start eller stop visualisering"
@@ -3419 +3419 @@
-msgstr "Klarte ikkje å hekta på ny visuell effekt i GStreamer-røyret"
+msgstr "Klarte ikkje å hekta på ny visuell effect i GStreamer-røyret"
@@ -3434 +3434 @@
-"Det ser ut til at du køyrer Rhythmbox eksternt.\n"
+"Det set ut til at du køyrer Rhythmbox eksternt.\n"
@@ -3498 +3498 @@
-"URLen «%s» er allereie lagt til som ein radiostasjon. Dersom dette er ei "
+"URLen «%s» er allereie lagt til some ein radiostasjon. Dersom dette er ei "
@@ -3508 +3508 @@
-"URLen «%s» ser ikkje ut til å vera ei podkastkjelde. Det kan vera feil URL, "
+"URLen «%s» set ikkje ut til å vera ei podkastkjelde. Det kan vera feil URL, "
@@ -3549 +3549 @@
-msgstr "Ikkje lasta ned"
+msgstr "Ikkje lasta need"
@@ -3577 +3577 @@
-msgstr "Vis melding om songen som vert spelt"
+msgstr "Vis melding om songen some vert spelt"
@@ -3581 +3581 @@
-msgstr "Hald fram med avspeling om pausa"
+msgstr "Held fram med avspeling om pausa"
@@ -3610 +3610 @@
-msgstr "Skriv tittelen og artisten på songen som vert spelt"
+msgstr "Skriv tittelen og artisten på songen some vert spelt"
@@ -3768 +3768 @@
-msgstr "Vis feilsøkingmeldingar som passar med ein bestemt streng"
+msgstr "Vis feilsøkingmeldingar some passar med ein bestemt streng"
@@ -3776 +3776 @@
-msgstr "Ikkje registrer skalet"
+msgstr "Ikkje register skalet"
@@ -4155 +4155 @@
-msgstr "Rett fram, fjern songar etterkvart som dei vert spelte"
+msgstr "Rett fram, fjern songar etterkvart some dei vert spelte"
@@ -4206 +4206 @@
-msgstr "Stopp avspeling"
+msgstr "Stop avspeling"
@@ -4250 +4250 @@
-msgstr "Vel mappe som skal leggjast til i biblioteket"
+msgstr "Vel mappe some skal leggjast til i biblioteket"
@@ -4314 +4314 @@
-msgstr "Rull framsyninga til songen som speler"
+msgstr "Rull framsyninga til songen some speler"
@@ -4350 +4350 @@
-msgstr "Spel _kø som sidestolpe"
+msgstr "Spel _kø some sidestolpe"
@@ -4354 +4354 @@
-msgstr "Vel om køen skal vera synleg som kjelde eller sidelinje"
+msgstr "Vel om køen skal vera synleg some kjelde eller sidelinje"
@@ -4397 +4397 @@
-"Rhythmbox er fri programvare som du kan redistribuera og/eller endra\n"
+"Rhythmbox er fri programvare some du kan redistribuera og/eller endra\n"
@@ -4519,2 +4519,2 @@
-"Ingen av spora i kø for å overførast er i eit format som måleininga ikkje "
-"støttar, og ingen omkodarar er tilgjengelege for dei formata som er støtta."
+"Ingen av spora i kø for å overførast er i eit format some måleininga ikkje "
+"støttar, og ingen omkodarar er tilgjengelege for dei formata some er støtta."
@@ -4528,2 +4528,2 @@
-"%d av %d spor i kø for å overførast er i eit format som måleininga ikkje "
-"støttar, og ingen omkodarar er tilgjengelege for dei formata som er støtta."
+"%d av %d spor i kø for å overførast er i eit format some måleininga ikkje "
+"støttar, og ingen omkodarar er tilgjengelege for dei formata some er støtta."
@@ -4537 +4537 @@
-msgstr "_Hald fram"
+msgstr "_Held fram"
@@ -4624 +4624 @@
-msgstr "Fleire GStreamer-tillegg trengst for å spela somme av desse filene."
+msgstr "Fleire GStreamer-tillegg trengst for å spela some av desse filene."
@@ -4793 +4793 @@
-msgstr "Last ned _episode"
+msgstr "Last need _episode"
@@ -4797 +4797 @@
-msgstr "Last ned podkastepisode"
+msgstr "Last need podkastepisode"
@@ -4879 +4879 @@
-msgstr "Lasta ned"
+msgstr "Lasta need"
@@ -4940 +4940 @@
-msgstr "Lastar ned podkast"
+msgstr "Lastar need podkast"
@@ -5060 +5060 @@
-msgstr "Pixbuf-objekt"
+msgstr "Pixbuf-object"
--- ./po/sk.po	original
+++ ./po/sk.po	fixed
@@ -24,3 +24,3 @@
-# PM: nie som si istý či sa myslí prvok s názvom "sink" je to vstup výstupnej pipeline
-# PM: sink som raz tuším prekladal pozri to v iných moduloch alebo sa opýtaj Paľa Šima
-# PK: v grafoch je to nieco ako ciel, som to dal tak
+# PM: nie some si istý či sa myslí prvok s názvom "sink" je to vstup výstupnej pipeline
+# PM: sink some raz tuším prekladal pozri to v iných moduloch alebo sa opýtaj Paľa Šima
+# PK: v grafoch je to nieco ako ciel, some to dal tak
@@ -32,3 +32,3 @@
-# PM: nie som si istý či sa myslí prvok s názvom "sink" je to vstup výstupnej pipeline
-# PM: sink som raz tuším prekladal pozri to v iných moduloch alebo sa opýtaj Paľa Šima
-# PK: v grafoch je to nieco ako ciel, som to dal tak
+# PM: nie some si istý či sa myslí prvok s názvom "sink" je to vstup výstupnej pipeline
+# PM: sink some raz tuším prekladal pozri to v iných moduloch alebo sa opýtaj Paľa Šima
+# PK: v grafoch je to nieco ako ciel, some to dal tak
@@ -62 +62 @@
-# PM: nie som si istý či stream neprekladáme ako tok, skús pozrieť iné moduly
+# PM: nie some si istý či stream neprekladáme ako tok, skús pozrieť iné moduly
@@ -135 +135 @@
-msgstr "Prehráva a organizuje vašu hudobnú zbierku"
+msgstr "Prehráva a organize vašu hudobnú zbierku"
@@ -755 +755 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -1438 +1438 @@
-msgstr "Nepodarilo sa nájsť zdrojový zásuvný modul systému GStreamer pre CD"
+msgstr "Nepodarilo sa nájsť zdrojový zásuvný module systému GStreamer pre CD"
@@ -1986 +1986 @@
-"ich vydaní.je zásuvný modul Last.fm povolený. Ak nie je, tak ho aktivujte z "
+"ich vydaní.je zásuvný module Last.fm povolený. Ak nie je, tak ho aktivujte z "
@@ -2387 +2387 @@
-"Rhythmbox, bohužiaľ tento proces zničí všetky metadáta o piesňach dostupné "
+"Rhythmbox, bohužiaľ tento process zničí všetky metadáta o piesňach dostupné "
@@ -3229 +3229 @@
-# MČ: možno by som dal „Hľadať medzi umelcami“, ale neviem či sa to hodí na všetky miesta
+# MČ: možno by some dal „Hľadať medzi umelcami“, ale neviem či sa to hodí na všetky miesta
@@ -3320 +3320 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3773 +3773 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3920 +3920 @@
-msgstr "Vzorový zásuvný modul Python"
+msgstr "Vzorový zásuvný module Python"
@@ -3924 +3924 @@
-msgstr "Vzorový zásuvný modul Python bez funkcií"
+msgstr "Vzorový zásuvný module Python bez funkcií"
@@ -3934 +3934 @@
-msgstr "Vzorový zásuvný modul"
+msgstr "Vzorový zásuvný module"
@@ -3938 +3938 @@
-msgstr "Vzorový zásuvný modul v C bez funkcií"
+msgstr "Vzorový zásuvný module v C bez funkcií"
@@ -3942 +3942 @@
-msgstr "Vzorový zásuvný modul Vala"
+msgstr "Vzorový zásuvný module Vala"
@@ -3946 +3946 @@
-msgstr "Vzorový zásuvný modul Vala bez funkcií"
+msgstr "Vzorový zásuvný module Vala bez funkcií"
@@ -3964,3 +3964,3 @@
-"podľa ustanovení licencie GNU General Public Licence\n"
-"(Všeobecná zverejňovacia licencia GNU), vydávanej nadáciou\n"
-"Free Software Foundation a to buď podľa 2. verzie tejto licencie,\n"
+"podľa ustanovení licence GNU General Public Licence\n"
+"(Všeobecná zverejňovacia licencia GNU), vydávanej nadáciou\n"
+"Free Software Foundation a to buď podľa 2. verzie tejto licence,\n"
@@ -3987 +3987 @@
-"Kópiu licencie GNU General Public License by ste mali dostať spolu\n"
+"Kópiu licence GNU General Public License by ste mali dostať spolu\n"
@@ -4388 +4388 @@
-# MČ: možno by som dal „Hľadať medzi umelcami“, ale neviem či sa to hodí na všetky miesta
+# MČ: možno by some dal „Hľadať medzi umelcami“, ale neviem či sa to hodí na všetky miesta
@@ -4394 +4394 @@
-# MČ: možno by som dal „Hľadať medzi skladateľmi“
+# MČ: možno by some dal „Hľadať medzi skladateľmi“
--- ./po/mjw.po	original
+++ ./po/mjw.po	fixed
@@ -474 +474 @@
-msgstr "Semar-amung"
+msgstr "Semar-among"
@@ -3210 +3210 @@
-msgstr "v -Seh pabi"
+msgstr "v -She pabi"
@@ -3214 +3214 @@
-msgstr "V - Seh pathe"
+msgstr "V - She pathe"
@@ -3258 +3258 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/fi.po	original
+++ ./po/fi.po	fixed
@@ -2051 +2051 @@
-msgstr "Tietokannan versio:"
+msgstr "Tietokannan version:"
@@ -2055 +2055 @@
-msgstr "Laiteohjelmiston versio:"
+msgstr "Laiteohjelmiston version:"
@@ -3115 +3115 @@
-msgstr "Näytä ohjelman versio"
+msgstr "Näytä ohjelman version"
@@ -3325 +3325 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -4772 +4772 @@
-#~ msgstr "Tuntematon desktop-tiedosto versio \"%s\""
+#~ msgstr "Tuntematon desktop-tiedosto version \"%s\""
@@ -5384 +5384 @@
-#~ msgstr "    * Ei ole riskirahoitettu tai suuri kaupallinen bisnes"
+#~ msgstr "    * Ei ole riskirahoitettu tai suuri kaupallinen business"
--- ./po/ta.po	original
+++ ./po/ta.po	fixed
@@ -312 +312 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/be.po	original
+++ ./po/be.po	fixed
@@ -1246 +1246 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
--- ./po/uk.po	original
+++ ./po/uk.po	fixed
@@ -3255 +3255 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/hi.po	original
+++ ./po/hi.po	fixed
@@ -306 +306 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/mk.po	original
+++ ./po/mk.po	fixed
@@ -302 +302 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/hr.po	original
+++ ./po/hr.po	fixed
@@ -624 +624 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -1718 +1718 @@
-msgstr "Tekst pjesme"
+msgstr "Text pjesme"
@@ -1727 +1727 @@
-msgstr "Tekst nije pronađen"
+msgstr "Text nije pronađen"
@@ -2191 +2191 @@
-msgstr "Tekst pjesme"
+msgstr "Text pjesme"
@@ -2415 +2415 @@
-msgstr "$18 US (Volimo vas!)"
+msgstr "$18 US (Volimo was!)"
@@ -2535 +2535 @@
-"Tekst greške je:\n"
+"Text greške je:\n"
@@ -2713 +2713 @@
-"%s Python module nije dostupan. Instalirajte modul i zatim ponovno pokrenite "
+"%s Python module nije dostupan. Instalirajte module i zatim ponovno pokrenite "
@@ -2836 +2836 @@
-msgstr "Autor"
+msgstr "Author"
@@ -3221 +3221 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -4573 +4573 @@
-msgstr "Obriši traženi tekst"
+msgstr "Obriši traženi text"
@@ -4691 +4691 @@
-#~ msgstr "Greška pri stvaranju podcast mape preuzimanja"
+#~ msgstr "Greška pri stvaranju podcast map preuzimanja"
--- ./po/ru.po	original
+++ ./po/ru.po	fixed
@@ -23 +23 @@
-"Last-Translator: Ser82-png <asvmail.as@gmail.com>\n"
+"Last-Translator: Set82-png <asvmail.as@gmail.com>\n"
@@ -3261 +3261 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/br.po	original
+++ ./po/br.po	fixed
@@ -299 +299 @@
-msgstr "Ment ar skurzer rouedad (kB)"
+msgstr "Meant ar skurzer rouedad (kB)"
@@ -331 +331 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
@@ -514 +514 @@
-msgstr "Ment ar restr :"
+msgstr "Meant ar restr :"
@@ -564 +564 @@
-msgstr "Ar restr n'eo ket ur restr .desktop reizh"
+msgstr "Ar restr n'eo kept ur restr .desktop reizh"
@@ -579 +579 @@
-msgstr "An arload ne zegemer ket an teulioù dre linennoù urzhiad"
+msgstr "An arload ne zegemer kept an teulioù dre linennoù urzhiad"
@@ -594 +594 @@
-msgstr "N'eo ket un dra a c'heller loc'hañ"
+msgstr "N'eo kept un dra a c'heller loc'hañ"
@@ -801 +801 @@
-msgstr "Ne c'haller ket gwiriekaat seurt ar restr : %s"
+msgstr "Ne c'haller kept gwiriekaat seurt ar restr : %s"
@@ -932 +932 @@
-msgstr "Ne c'hall ket Rhythmbox tizhout ar CD."
+msgstr "Ne c'hall kept Rhythmbox tizhout ar CD."
@@ -936 +936 @@
-msgstr "Ne c'hall ket Rhythmbox lenn titouroù ar CD."
+msgstr "Ne c'hall kept Rhythmbox lenn titouroù ar CD."
@@ -954 +954 @@
-msgstr "Ne c'hall ket Rhythmbox tizhout an drobarzhell CD."
+msgstr "Ne c'hall kept Rhythmbox tizhout an drobarzhell CD."
@@ -1113 +1113 @@
-msgstr "N'eo ket reizhet mat an horolaj"
+msgstr "N'eo kept reizhet mat an horolaj"
@@ -1224 +1224 @@
-msgstr "Forbannañ ar roudenn a-vremañ evit ma ne vezo ket adlennet"
+msgstr "Forbannañ ar roudenn a-vremañ evit ma ne vezo kept adlennet"
@@ -1261 +1261 @@
-msgstr "N'haller ket kennaskañ"
+msgstr "N'haller kept kennaskañ"
@@ -1299 +1299 @@
-msgstr "N'en doa ket respontet ar servijer"
+msgstr "N'en doa kept respontet ar servijer"
@@ -1303 +1303 @@
-msgstr "N'eus ket endalc'had hegerz a-walc'h evit seniñ ar savlec'h-mañ."
+msgstr "N'eus kept endalc'had hegerz a-walc'h evit seniñ ar savlec'h-mañ."
@@ -1363 +1363 @@
-msgstr "Ne c'hall ket Rhythmbox eilañ ar bladenn"
+msgstr "Ne c'hall kept Rhythmbox eilañ ar bladenn"
@@ -1367 +1367 @@
-msgstr "Ne c'hall ket Rhythmbox enrollañ ar bladenn glevet"
+msgstr "Ne c'hall kept Rhythmbox enrollañ ar bladenn glevet"
@@ -1372 +1372 @@
-msgstr "Ne c'haller ket sevel roll ar roudennoù klevet."
+msgstr "Ne c'haller kept sevel roll ar roudennoù klevet."
@@ -1378 +1378 @@
-msgstr "Ne c'haller ket skrivañ restr ar raktres klevet %s : %s"
+msgstr "Ne c'haller kept skrivañ restr ar raktres klevet %s : %s"
@@ -1384 +1384 @@
-msgstr "Ne c'haller ket skrivañ ar raktres klevet"
+msgstr "Ne c'haller kept skrivañ ar raktres klevet"
@@ -1388 +1388 @@
-msgstr "Ne c'haller ket krouiñ ur raktres CD klevet"
+msgstr "Ne c'haller kept krouiñ ur raktres CD klevet"
@@ -1410 +1410 @@
-msgstr "Ne c'haller ket krouiñ ur CD klevet"
+msgstr "Ne c'haller kept krouiñ ur CD klevet"
@@ -1462 +1462 @@
-msgstr "N'eo ket al lenner %s un engraver"
+msgstr "N'eo kept al lenner %s un engraver"
@@ -1589 +1589 @@
-msgstr "Ha fellout a ra deoc'h chom a-sav da skrivañ war ar bladenn-mañ?"
+msgstr "Ha fellout a ra deoc'h chom a-save da skrivañ war ar bladenn-mañ?"
@@ -1609 +1609 @@
-msgstr "Mar plij, bezit sur n'emañ ket un arload all oc'h implijout al lenner."
+msgstr "Mar plij, bezit sur n'emañ kept un arload all oc'h implijout al lenner."
@@ -1715 +1715 @@
-msgstr "Ne c'haller ket sevel ur roll roudennoù klevet."
+msgstr "Ne c'haller kept sevel ur roll roudennoù klevet."
@@ -1817 +1817 @@
-msgstr "N'emañ ket o seniñ"
+msgstr "N'emañ kept o seniñ"
@@ -1864 +1864 @@
-msgstr "Lec'hiadur ar seniñ n'eo ket hegerz"
+msgstr "Lec'hiadur ar seniñ n'eo kept hegerz"
@@ -1869 +1869 @@
-msgstr "Ne c'haller ket loc'hañ ar weladurezh"
+msgstr "Ne c'haller kept loc'hañ ar weladurezh"
@@ -1889 +1889 @@
-msgstr "Ne c'haller ket loc'hañ ar weladurezh"
+msgstr "Ne c'haller kept loc'hañ ar weladurezh"
@@ -1918 +1918 @@
-msgstr "Ne c'hall ket Rhythmbox kevreañ ouzh kenimplij iTunes 7"
+msgstr "Ne c'hall kept Rhythmbox kevreañ ouzh kenimplij iTunes 7"
@@ -1932 +1932 @@
-msgstr "N'eo ket loc'het ar servij mDNS"
+msgstr "N'eo kept loc'het ar servij mDNS"
@@ -1940 +1940 @@
-msgstr "Ne c'haller ket gweredekaat ar merdeer"
+msgstr "Ne c'haller kept gweredekaat ar merdeer"
@@ -1944 +1944 @@
-msgstr "N'eo ket gweredek ar merdeer"
+msgstr "N'eo kept gweredek ar merdeer"
@@ -1961 +1961 @@
-msgstr "N'eo ket loc'het ar servij mDNS avahi"
+msgstr "N'eo kept loc'het ar servij mDNS avahi"
@@ -1965 +1965 @@
-msgstr "N'eo ket embannet ar servij mDNS"
+msgstr "N'eo kept embannet ar servij mDNS"
@@ -2222 +2222 @@
-msgstr "Rhythmbox en deus dinoet un drobarzhell a zo un iPod ha n'eo ket deraouekaet pe damajet moarvat. Rankout a ra bezañ deraouekaet kent ma c'hellfe bezañ implijet gant Rhythmbox, met an oberiadenn-mañ zo o vont da zilemel holl ditouroù an tonioù a c'hellfe bezañ war an iPod. Ma fell deoc'h deraouekaat an iPod, klokait an titouroù amañ-dindan. Ma n'eo ket un iPod pe ne fell ket deoc'h deraouekaat anezhi, pouezit war Nullañ."
+msgstr "Rhythmbox en deus dinoet un drobarzhell a zo un iPod ha n'eo kept deraouekaet pe damajet moarvat. Rankout a ra bezañ deraouekaet kent ma c'hellfe bezañ implijet gant Rhythmbox, met an oberiadenn-mañ zo o vont da zilemel holl ditouroù an tonioù a c'hellfe bezañ war an iPod. Ma fell deoc'h deraouekaat an iPod, klokait an titouroù amañ-dindan. Ma n'eo kept un iPod pe ne fell kept deoc'h deraouekaat anezhi, pouezit war Nullañ."
@@ -2242 +2242 @@
-msgstr "N'haller ket deraouekaat an iPod nevez"
+msgstr "N'haller kept deraouekaat an iPod nevez"
@@ -2384 +2384 @@
-"Un emglev \" Lod gwirioù miret strizh \" eo, a ya mat-kenañ diouzh ar c'hantved nevez."
+"Un emglev \" Load gwirioù miret strizh \" eo, a ya mat-kenañ diouzh ar c'hantved nevez."
@@ -2640 +2640 @@
-msgstr "    * N'eus ket ezhomm d'en em enrollañ evit selaou pe brenañ"
+msgstr "    * N'eus kept ezhomm d'en em enrollañ evit selaou pe brenañ"
@@ -2648 +2648 @@
-msgstr "    * N'eus ket greanterezh bras diazezet war gevala riskl"
+msgstr "    * N'eus kept greanterezh bras diazezet war gevala riskl"
@@ -2656 +2656 @@
-msgstr "    * Pellgargadurioù a-feson (eiladoù CD), ne zigresk ket perzh ar son"
+msgstr "    * Pellgargadurioù a-feson (eiladoù CD), ne zigresk kept perzh ar son"
@@ -2906 +2906 @@
-msgstr "N'haller ket kargañ ar c'hatalog"
+msgstr "N'haller kept kargañ ar c'hatalog"
@@ -2910 +2910 @@
-msgstr "Rhythmbox ne c'hall ket kompren ar c'hatalog Magnatune, roit da c'houzout an draen mar plij."
+msgstr "Rhythmbox ne c'hall kept kompren ar c'hatalog Magnatune, roit da c'houzout an draen mar plij."
@@ -2996 +2996 @@
-msgstr "Ne c'hall ket Rhythmbox lenn titouroù ar CD."
+msgstr "Ne c'hall kept Rhythmbox lenn titouroù ar CD."
@@ -3022 +3022 @@
-msgstr "N'haller ket digeriñ ar restr padennek : %s"
+msgstr "N'haller kept digeriñ ar restr padennek : %s"
@@ -3059 +3059 @@
-msgstr "N'haller ket eilañ ar restr adalek an drobarzhell MTP : %s"
+msgstr "N'haller kept eilañ ar restr adalek an drobarzhell MTP : %s"
@@ -3064 +3064 @@
-msgstr "N'eus ket plas a-walc'h en %s"
+msgstr "N'eus kept plas a-walc'h en %s"
@@ -3069 +3069 @@
-msgstr "N'haller ket eilañ ar restr adalek an drobarzhell MTP : %s"
+msgstr "N'haller kept eilañ ar restr adalek an drobarzhell MTP : %s"
@@ -3105 +3105 @@
-msgstr "Goude bezañ pouezet war «[nbsp]Gweredekaat[nbsp]», gortoz a raio Rhythmbox ma kevreit outañ gant winpdb pe rpdb2. Ma n'oc'h eus ket termenet ur ger-tremen dizreinañ e GConf, implijit ar ger-tremen dre ziouer («[nbsp]rhythmbox[nbsp]»)."
+msgstr "Goude bezañ pouezet war «[nbsp]Gweredekaat[nbsp]», gortoz a raio Rhythmbox ma kevreit outañ gant winpdb pe rpdb2. Ma n'oc'h eus kept termenet ur ger-tremen dizreinañ e GConf, implijit ar ger-tremen dre ziouer («[nbsp]rhythmbox[nbsp]»)."
@@ -3253 +3253 @@
-msgstr "N'emañ ket o seniñ"
+msgstr "N'emañ kept o seniñ"
@@ -3376 +3376 @@
-msgstr "Ne c'haller ket loc'hañ an ezkas video"
+msgstr "Ne c'haller kept loc'hañ an ezkas video"
@@ -3385 +3385 @@
-msgstr "Ne c'haller ket loc'hañ ar weladurezh"
+msgstr "Ne c'haller kept loc'hañ ar weladurezh"
@@ -3438 +3438 @@
-msgstr "Ne c'haller ket krouiñ ar c'havlec'h pellgargañ evit %s : %s"
+msgstr "Ne c'haller kept krouiñ ar c'havlec'h pellgargañ evit %s : %s"
@@ -3462 +3462 @@
-msgstr "An URL '%s' ne seblant ket bezañ ul lanv podskignañ gweredek. Direizh eo an URL pe al lanv marteze. Ha c'hoant ho peus ma rhythmbox a glask d'implijout anezhañ memes tra ?"
+msgstr "An URL '%s' ne seblant kept bezañ ul lanv podskignañ gweredek. Direizh eo an URL pe al lanv marteze. Ha c'hoant ho peus ma rhythmbox a glask d'implijout anezhañ memes tra ?"
@@ -3476 +3476 @@
-msgstr "Ne c'haller ket gwiriekaat seurt ar restr : %s"
+msgstr "Ne c'haller kept gwiriekaat seurt ar restr : %s"
@@ -3486 +3486 @@
-msgstr "Ne c'haller ket diellfennañ endalc'had al lanv"
+msgstr "Ne c'haller kept diellfennañ endalc'had al lanv"
@@ -3495 +3495 @@
-msgstr "Ket pellgarget"
+msgstr "Kept pellgarget"
@@ -3612 +3612 @@
-msgstr "Krouet eo bet an diaz roadennoù gant un handelv Rhythmbox nevesoc'h eget ho hini. Ar stumm-mañ ne c'hall ket lenn an diaz roadennoù."
+msgstr "Krouet eo bet an diaz roadennoù gant un handelv Rhythmbox nevesoc'h eget ho hini. Ar stumm-mañ ne c'hall kept lenn an diaz roadennoù."
@@ -3831 +3831 @@
-msgstr "Ne oa ket tu da lenn ar roll-tonioù"
+msgstr "Ne oa kept tu da lenn ar roll-tonioù"
@@ -3849 +3849 @@
-msgstr "Ne oa ket tu da enrollañ ar roll-tonioù"
+msgstr "Ne oa kept tu da enrollañ ar roll-tonioù"
@@ -3889 +3889 @@
-msgstr "Ne c'haller ket gweredekaat an enlugellad %s"
+msgstr "Ne c'haller kept gweredekaat an enlugellad %s"
@@ -3905 +3905 @@
-msgstr "N'haller ket kas er-maez"
+msgstr "N'haller kept kas er-maez"
@@ -3909 +3909 @@
-msgstr "N'haller ket disevel"
+msgstr "N'haller kept disevel"
@@ -4118 +4118 @@
-msgstr "N'eus ket bet tu da grouiñ ar soner : %s"
+msgstr "N'eus kept bet tu da grouiñ ar soner : %s"
@@ -4128 +4128 @@
-msgstr "N'emañ ket o seniñ"
+msgstr "N'emañ kept o seniñ"
@@ -4152 +4152 @@
-msgstr "Lec'hiadur ar seniñ n'eo ket hegerz"
+msgstr "Lec'hiadur ar seniñ n'eo kept hegerz"
@@ -4157 +4157 @@
-msgstr "N'haller ket furchal er roudenn a-vremañ"
+msgstr "N'haller kept furchal er roudenn a-vremañ"
@@ -4171 +4171 @@
-msgstr "N'eus ket tu da ziskouez ar skoazell"
+msgstr "N'eus kept tu da ziskouez ar skoazell"
@@ -4328 +4328 @@
-msgstr "Ne c'haller ket dilec'hiañ ar restroù roadennoù an implijer"
+msgstr "Ne c'haller kept dilec'hiañ ar restroù roadennoù an implijer"
@@ -4391 +4391 @@
-"gant Rhythmbox ; ma n'hoc'h eus ket bet, skrivit da : Free Software Foundation, Inc.\n"
+"gant Rhythmbox ; ma n'hoc'h eus kept bet, skrivit da : Free Software Foundation, Inc.\n"
@@ -4959 +4959 @@
-msgstr "N'emañ ket o seniñ"
+msgstr "N'emañ kept o seniñ"
@@ -5163 +5163 @@
-msgstr "n'endalc'h ket"
+msgstr "n'endalc'h kept"
--- ./po/eo.po	original
+++ ./po/eo.po	fixed
@@ -891 +891 @@
-msgstr "_Bitoj dum minuto:"
+msgstr "_Bitoj dumb minuto:"
@@ -1106 +1106 @@
-msgstr "Dosiero difektiĝis dum skribado"
+msgstr "Dosiero difektiĝis dumb skribado"
@@ -1183 +1183 @@
-msgstr "Eraro dum transigi trakon"
+msgstr "Eraro dumb transigi trakon"
@@ -1417 +1417 @@
-msgstr "Ĉi tiu versio de Rhythmbox forbariĝis."
+msgstr "Ĉi tiu version de Rhythmbox forbariĝis."
@@ -2063 +2063 @@
-msgstr "Versio de datumbazo:"
+msgstr "Version de datumbazo:"
@@ -2067 +2067 @@
-msgstr "Versio de mikroprogramaro:"
+msgstr "Version de mikroprogramaro:"
@@ -2425 +2425 @@
-msgstr "$15 US (EGE sindona!)"
+msgstr "$15 US (EDGE sindona!)"
@@ -2541 +2541 @@
-"Eraro okazis dum klopodo por aŭtorigi la elŝuton.\n"
+"Eraro okazis dumb klopodo por aŭtorigi la elŝuton.\n"
@@ -2556 +2556 @@
-"Eraro okazis dum klopodo por elŝuti la albumon.\n"
+"Eraro okazis dumb klopodo por elŝuti la albumon.\n"
@@ -2682 +2682 @@
-msgstr "Malebligi mastrumilon de energio interrompi la maŝino dum ludado"
+msgstr "Malebligi mastrumilon de energio interrompi la maŝino dumb ludado"
@@ -2841 +2841 @@
-msgstr "SoundCoud-uzantoj"
+msgstr "SoundCould-uzantoj"
@@ -3330 +3330 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3465 +3465 @@
-"La datumbazo estis kreita de malnova versio de Rhythmbox.  Ĉi tiu versio de "
+"La datumbazo estis kreita de malnova version de Rhythmbox.  Ĉi tiu version de "
@@ -3525,2 +3525,2 @@
-"la Free Software Foundation; aŭ en la 2a versio de la permesilo aŭ\n"
-"(laŭ via volo) en iu sekva versio.\n"
+"la Free Software Foundation; aŭ en la 2a version de la permesilo aŭ\n"
+"(laŭ via volo) en iu sekva version.\n"
@@ -3535 +3535 @@
-"Rhythmbox estas distribuite kun la espero ke ĝi estos utila,\n"
+"Rhythmbox estas distribute kun la espero ke ĝi estos utila,\n"
@@ -3618 +3618 @@
-msgstr "MPEG-Versio 3.0 URL"
+msgstr "MPEG-Version 3.0 URL"
@@ -3682 +3682 @@
-msgstr "Eraro dum konservanta informojn pri kantoj"
+msgstr "Eraro dumb konservanta informojn pri kantoj"
@@ -3959,2 +3959,2 @@
-msgstr[0] "%d eraro dum importado"
-msgstr[1] "%d eraroj dum importado"
+msgstr[0] "%d eraro dumb importado"
+msgstr[1] "%d eraroj dumb importado"
@@ -4414 +4414 @@
-msgstr "Batoj dum minuto"
+msgstr "Batoj dumb minuto"
@@ -4586 +4586 @@
-msgstr "ne dum"
+msgstr "ne dumb"
@@ -4604 +4604 @@
-msgstr "dum la lastaj"
+msgstr "dumb la lastaj"
@@ -4711 +4711 @@
-#~ msgstr "Nerekonata versio '%s' de labortabla dosiero"
+#~ msgstr "Nerekonata version '%s' de labortabla dosiero"
@@ -5291,2 +5291,2 @@
-#~ "    * Ampleksaj biografiaj informoj pri ĉiu muzikanto, kaj ties foto -- "
-#~ "sentu fortan ligon kun la artisto"
+#~ "    * Ampleksaj biografiaj informoj pri ĉiu muzikanto, kaj ties photo -- "
+#~ "sentu fortran ligon kun la artisto"
@@ -5305 +5305 @@
-#~ "    * Senstreĉa ĉirkaŭaĵo -  nenio fulmas, neniuj aŭdreklamoj dum "
+#~ "    * Senstreĉa ĉirkaŭaĵo -  nenio fulmas, neniuj aŭdreklamoj dumb "
@@ -5367 +5367 @@
-#~ msgstr "    * Tre simpla fasado, rapide ludeblas muziko"
+#~ msgstr "    * Tree simpla fasado, rapide ludeblas muziko"
@@ -5453 +5453 @@
-#~ msgstr "Eraro dum serĉo de p2plink por albumo %s sur jamendo.com"
+#~ msgstr "Eraro dumb serĉo de p2plink por albumo %s sur jamendo.com"
@@ -5525 +5525 @@
-#~ msgstr "Eraro okazis dum skribado de lumdisko"
+#~ msgstr "Eraro okazis dumb skribado de lumdisko"
@@ -5659 +5659 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/kn.po	original
+++ ./po/kn.po	fixed
@@ -300 +300 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/es.po	original
+++ ./po/es.po	fixed
@@ -121 +121 @@
-msgstr "Mis mejores puntuados"
+msgstr "Miss mejores puntuados"
@@ -351 +351 @@
-msgstr "_Artistas y álbumes"
+msgstr "_Artists y álbumes"
@@ -355 +355 @@
-msgstr "_Géneros y artistas"
+msgstr "_Géneros y artists"
@@ -359 +359 @@
-msgstr "_Géneros, artistas y álbumes"
+msgstr "_Géneros, artists y álbumes"
@@ -363 +363 @@
-msgstr "Columnas visibles"
+msgstr "Columns visible"
@@ -650 +650 @@
-msgstr "Autor:"
+msgstr "Author:"
@@ -862 +862 @@
-msgstr "Orden de los _artistas:"
+msgstr "Orden de los _artists:"
@@ -1114 +1114 @@
-msgstr "Número de serie:"
+msgstr "Número de series:"
@@ -1200 +1200 @@
-msgstr "_Orden de los artistas:"
+msgstr "_Orden de los artists:"
@@ -1366 +1366 @@
-msgstr "Artistas favoritos"
+msgstr "Artists favoritos"
@@ -1453 +1453 @@
-msgstr "Mis recomendaciones"
+msgstr "Miss recomendaciones"
@@ -1474 +1474 @@
-msgstr "Escuchar la radio de artistas _similares"
+msgstr "Escuchar la radio de artists _similares"
@@ -1827 +1827 @@
-msgstr "Requerir contrase_ña:"
+msgstr "Requerir contrast_ña:"
@@ -1869 +1869 @@
-msgstr "La música compartida de «%s» requiere una contraseña para conectarse"
+msgstr "La música compartida de «%s» require una contraseña para conectarse"
@@ -1913 +1913 @@
-msgstr "Artistas"
+msgstr "Artists"
@@ -2085,2 +2085,2 @@
-"inicializar o corrupto. Se debe inicializar antes de que Rhythmbox pueda "
-"usarlo pero esto destruirá cualquier metadato de las canciones presentes. Si "
+"inicializar o corruption. Se debe inicializar antes de que Rhythmbox pueda "
+"usarlo pero esto destruirá cualquier metadato de las canciones presents. Si "
@@ -2289 +2289 @@
-msgstr "    * Todas las canciones pueden ser escuchadas gratuitamente"
+msgstr "    * Todas las canciones pueden set escuchadas gratuitamente"
@@ -2318 +2318 @@
-msgstr "    * Todos los álbumes y artistas son elegidos personalmente"
+msgstr "    * Todos los álbumes y artists son elegidos personalmente"
@@ -2847 +2847 @@
-msgstr "Autor"
+msgstr "Author"
@@ -2903 +2903 @@
-"El URL «%s» no parece ser un proveedor Podcast. Quizá esté equivocado el "
+"El URL «%s» no parece set un proveedor Podcast. Quizá esté equivocado el "
@@ -3166 +3166 @@
-msgstr "Iniciar el modo interactivo"
+msgstr "Iniciar el modo interaction"
@@ -3232 +3232 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3430 +3430 @@
-"Rhythmbox se distribuye con la esperanza de que le sea útil,\n"
+"Rhythmbox se distribute con la esperanza de que le sea útil,\n"
@@ -3510 +3510 @@
-"disponibles de la línea de comandos.\n"
+"disponibles de la línea de commandos.\n"
@@ -3805 +3805 @@
-msgstr "Buscar artistas"
+msgstr "Buscar artists"
@@ -3859 +3859 @@
-"Se requiere software adicional para reproducir algunos de estos archivos."
+"Se require software adicional para reproducir algunos de estos archivos."
@@ -4214 +4214 @@
-msgstr[1] "Todos los %d artistas (%d)"
+msgstr[1] "Todos los %d artists (%d)"
@@ -4723 +4723 @@
-#~ msgstr "Efectos visuales"
+#~ msgstr "Efectos visuals"
@@ -4726 +4726 @@
-#~ msgstr "Efectos visuales"
+#~ msgstr "Efectos visuals"
@@ -4756 +4756 @@
-#~ msgstr "La aplicación no acepta documentos en la línea de comandos"
+#~ msgstr "La aplicación no acepta documentos en la línea de commandos"
@@ -4991 +4991 @@
-#~ msgstr "Conmutar los efectos visuales a pantalla completa"
+#~ msgstr "Conmutar los efectos visuals a pantalla completa"
@@ -5176 +5176 @@
-#~ msgstr "Hace que el examinador sólo muestre este género"
+#~ msgstr "Have que el examinador sólo muestre este género"
@@ -5179 +5179 @@
-#~ msgstr "Hace que el examinador sólo muestre este artista"
+#~ msgstr "Have que el examinador sólo muestre este artista"
@@ -5182 +5182 @@
-#~ msgstr "Hace que el examinador sólo muestre este álbum"
+#~ msgstr "Have que el examinador sólo muestre este álbum"
@@ -5228 +5228 @@
-#~ "Este CD podría ser más de un álbum. Seleccione qué álbum es abajo y pulse "
+#~ "Este CD podría set más de un álbum. Seleccione qué álbum es abajo y pulse "
@@ -5377 +5377 @@
-#~ "    * El 50% del pago es para el artista (lo cual hace al comprador "
+#~ "    * El 50% del pago es para el artista (lo cual have al comprador "
@@ -5392 +5392 @@
-#~ "artistas -- para que sienta una fuerte conexión con el artista"
+#~ "artists -- para que sienta una fuerte conexión con el artista"
@@ -5455 +5455 @@
-#~ "pueden ser escuchadas en el fondo - puede trabajar mientras escucha "
+#~ "pueden set escuchadas en el fondo - puede trabajar mientras escucha "
@@ -5459 +5459 @@
-#~ msgstr "    * Selección más pequeña hace más fácil encontrar buena música"
+#~ msgstr "    * Selección más pequeña have más fácil encontrar buena música"
@@ -5556 +5556 @@
-#~ "     * Un marco de protección legal para los artistas (gracias a las "
+#~ "     * Un marco de protección legal para los artists (gracias a las "
@@ -5565 +5565 @@
-#~ "a los oyentes a descubrir nuevos artistas basándose en sus gustos\n"
+#~ "a los oyentes a descubrir nuevos artists basándose en sus gustos\n"
@@ -5572 +5572 @@
-#~ msgstr "     * La posibilidad de hacer donaciones directas a los artistas."
+#~ msgstr "     * La posibilidad de hacer donaciones directas a los artists."
@@ -5585 +5585 @@
-#~ "Jamendo es un nuevo modelo para que los artistas se promocionen, "
+#~ "Jamendo es un nuevo modelo para que los artists se promocionen, "
@@ -5599 +5599 @@
-#~ "Los álbumes se puntúan democráticamente según las revisiones de los "
+#~ "Los álbumes se puntúan democráticamente según las revisions de los "
@@ -5611 +5611 @@
-#~ "En Jamendo, los artistas distribuyen su música bajo licencias Creative "
+#~ "En Jamendo, los artists distribuyen su música bajo licencias Creative "
@@ -5703 +5703 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
@@ -5767 +5767 @@
-#~ msgstr "_Usar el backend de atenuación cruzada (requiere reinicio)"
+#~ msgstr "_Usar el backend de atenuación cruzada (require reinicio)"
@@ -5819 +5819 @@
-#~ msgstr "Visibles con notificaciones"
+#~ msgstr "Visible con notificaciones"
@@ -5865 +5865 @@
-#~ "¿Está seguro de que quiere activar los efectos visuales?"
+#~ "¿Está seguro de que quiere activar los efectos visuals?"
@@ -5968 +5968 @@
-#~ msgstr "Máximo posible"
+#~ msgstr "Máximo possible"
@@ -6110 +6110 @@
-#~ msgstr "Imposible construir una lista de pistas de sonido."
+#~ msgstr "Impossible construir una lista de pistas de sonido."
@@ -6122 +6122 @@
-#~ "Esta lista de reproducción dura %s minutos. Esto excede la longitud de un "
+#~ "Esta lista de reproducción dura %s minutos. Esto exceed la longitud de un "
@@ -6188 +6188 @@
-#~ msgstr "Artistas similares a %s"
+#~ msgstr "Artists similares a %s"
@@ -6194 +6194 @@
-#~ msgstr "Artistas que les gustan a los fans de %s"
+#~ msgstr "Artists que les gustan a los fans de %s"
@@ -6399 +6399 @@
-#~ msgstr "Se requiere una contraseña"
+#~ msgstr "Se require una contraseña"
@@ -6621 +6621 @@
-#~ msgstr "Se requiere actualización del cliente"
+#~ msgstr "Se require actualización del cliente"
--- ./po/fur.po	original
+++ ./po/fur.po	fixed
@@ -266 +266 @@
-msgstr "_Limite a: "
+msgstr "_Limit a: "
@@ -402 +402 @@
-msgstr "Selezione une posizion che a conten musiche di zontâ ae tô librarie:"
+msgstr "Selezione une posizion che a contain musiche di zontâ ae tô librarie:"
@@ -438 +438 @@
-msgstr "Struture de librarie"
+msgstr "Structure de librarie"
@@ -656 +656 @@
-msgstr "Detais"
+msgstr "Details"
@@ -1091 +1091 @@
-msgstr "Numar di serie:"
+msgstr "Numar di series:"
@@ -1824 +1824 @@
-msgstr "Disconet"
+msgstr "Disconnect"
@@ -2023 +2023 @@
-msgstr "Pont di montaç:"
+msgstr "Point di montaç:"
@@ -2039 +2039 @@
-msgstr "_Inizialize"
+msgstr "_Initialize"
@@ -3221 +3221 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
--- ./po/rw.po	original
+++ ./po/rw.po	fixed
@@ -669 +669 @@
-msgid "An exception occured '%s'"
+msgid "An exception occurred '%s'"
@@ -1440 +1440 @@
-#. an error occured
+#. an error occurred
--- ./po/th.po	original
+++ ./po/th.po	fixed
@@ -1422 +1422 @@
-#. * but nationalities, record labels, decades and very random words are also commmon
+#. * but nationalities, record labels, decades and very random words are also common
@@ -5097 +5097 @@
-#~ msgid "C_onfigure..."
+#~ msgid "C_configure..."
--- ./po/bn_IN.po	original
+++ ./po/bn_IN.po	fixed
@@ -301 +301 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/mr.po	original
+++ ./po/mr.po	fixed
@@ -300 +300 @@
-msgid "C_onfigure..."
+msgid "C_configure..."
--- ./po/tr.po	original
+++ ./po/tr.po	fixed
@@ -621 +621 @@
-"iTunes Mağazasında ortam akışı ara ya da ortam akışı besleme adresi gir.\n"
+"iTunes Mağazasında ortam akışı ara ya da ortam akışı besleme adresi git.\n"
@@ -1110 +1110 @@
-msgstr "Sistem"
+msgstr "System"
@@ -2888 +2888 @@
-"'%s' adresi bir ortam akışı yayını gibi görünmüyor. Adres yanlış ya da yayın "
+"'%s' adresi bir ortam akışı yayını gibi görünmüyor. Address yanlış ya da yayın "
@@ -3216 +3216 @@
-msgid "Seeked to %s"
+msgid "Sought to %s"
@@ -3355 +3355 @@
-msgstr "Pyhton ile yazılmış özelliksiz örnek eklenti"
+msgstr "Python ile yazılmış özelliksiz örnek eklenti"
@@ -3382 +3382 @@
-"Enver ALTIN <enver.altin@frontsite.com.tr>\n"
+"Never ALTIN <enver.altin@frontsite.com.tr>\n"
