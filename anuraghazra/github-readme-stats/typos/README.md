## Detected Typos Diff
```diff
--- ./tests/renderWakatimeCard.test.js	original
+++ ./tests/renderWakatimeCard.test.js	fixed
@@ -58 +58 @@
-  it('should show "no coding activitiy this week" message when there hasn not been activity', () => {
+  it('should show "no coding activity this week" message when there hasn not been activity', () => {
--- ./src/translations.js	original
+++ ./src/translations.js	fixed
@@ -179 +179 @@
-      it: "Ha contribuito a",
+      it: "Ha contribution a",
@@ -226 +226 @@
-    my: "Templat",
+    my: "Template",
--- ./src/common/utils.js	original
+++ ./src/common/utils.js	fixed
@@ -395 +395 @@
- * @template T Langauge object.
+ * @template T Language object.
--- ./docs/readme_tr.md	original
+++ ./docs/readme_tr.md	fixed
@@ -368 +368 @@
-GitHub API saatte sadece 5.000 isteğe izin verdiği için `https://github-readme-stats.vercel.app/api` adresindeki API'm bu limite muhtemelen takılmış olabilir. Eğer projeyi kendi Vercel sunucunuzda yayınlarsanız, böyle bir sorun yaşamayabilirsiniz. Deploy butonuna tıkla ve deploy başlasın!
+GitHub API saatte sadece 5.000 isteğe izin verdiği için `https://github-readme-stats.vercel.app/api` adresindeki API'm bu limit muhtemelen takılmış olabilir. Eğer projeyi kendi Vercel sunucunuzda yayınlarsanız, böyle bir sorun yaşamayabilirsiniz. Deploy butonuna tıkla ve deploy başlasın!
--- ./docs/readme_fr.md	original
+++ ./docs/readme_fr.md	fixed
@@ -113 +113 @@
-Avec les thèmes intégrés, vous pouvez personnaliser l'apparence de la carte sans faire de [personnalisation manuelle](#customization).
+Avec les thèmes intégrés, vous pouvez personnaliser l'appearance de la carte sans faire de [personnalisation manuelle](#customization).
@@ -131 +131 @@
-Vous pouvez personnaliser l'apparence de votre `Carte des stats` ou `Carte de dépôt` comme vous le souhaitez avec les paramètres d'URL.
+Vous pouvez personnaliser l'appearance de votre `Carte des stats` ou `Carte de dépôt` comme vous le souhaitez avec les paramètres d'URL.
@@ -133 +133 @@
-#### Options principales:
+#### Options principles:
@@ -142 +142 @@
-- `locale` - définir la langue de la carte _(par exemple. cn, de, es, etc.)_
+- `locale` - définir la langue de la carte _(par example. cn, de, es, etc.)_
@@ -156 +156 @@
--   `hide` - Masquer [les éléments spécifiés](#cacher-les-statistiques-individuelles) dans les statistiques _(Comma seperated values)_
+-   `hide` - Masquer [les éléments spécifiés](#cacher-les-statistiques-individuelles) dans les statistiques _(Comma separated values)_
@@ -170 +170 @@
--   `hide` - Masquer les langages spécifiés sur la carte _(Comma seperated values)_
+-   `hide` - Masquer les langages spécifiés sur la carte _(Comma separated values)_
@@ -223 +223 @@
-Vous pouvez utiliser le paramètre `?hide=language1,language2` pour masquer les langages individuels.
+Vous pouvez utiliser le paramètre `?hide=language1,language2` pour masquer les langages individuals.
@@ -291 +291 @@
-En général, vous ne pourrez pas mettre les images côte à côte. Pour ce faire, vous pouvez utiliser cette approche :
+En général, vous ne pourrez pas mettre les images côte à côte. Pour ce faire, vous pouvez utiliser cette approach :
@@ -308 +308 @@
-NOTE: Depuis [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) nous devrions être en mesure de traiter plus de 5 000 demandes et ne pas avoir de problèmes de temps d'arrêt :D
+NOTE: Depuis [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) nous devrions être en measure de traiter plus de 5 000 demands et ne pas avoir de problèmes de temps d'arrêt :D
@@ -327 +327 @@
-1. Choisissez root et gardez tout tel quel, ajoutez simplement votre variable d'environnement nommée PAT_1 (comme indiqué), qui contiendra un jeton d'accès personnel (PAT), que vous pouvez facilement créer [ici](https://github.com/settings/tokens/new) (laissez tout tel quel, nommez le simplement quelque chose, cela peut être tout ce que vous voulez)
+1. Choisissez root et gardez tout tel quel, ajoutez simplement votre variable d'environment nommée PAT_1 (comme indiqué), qui contiendra un jeton d'accès personnel (PAT), que vous pouvez facilement créer [ici](https://github.com/settings/tokens/new) (laissez tout tel quel, nommez le simplement quelque chose, cela peut être tout ce que vous voulez)
--- ./docs/readme_es.md	original
+++ ./docs/readme_es.md	fixed
@@ -67 +67 @@
-- [Tarjeta de Lenguajes Principales](#tarjeta-de-lenguajes-principales)
+- [Tarjeta de Lenguajes Principles](#tarjeta-de-lenguajes-principles)
@@ -119 +119 @@
-Utiliza el parámetro `?theme=THEME_NAME`, de esta manera:
+Utilize el parámetro `?theme=THEME_NAME`, de esta manera:
@@ -158 +158 @@
-#### Opciones exclusivas de la Tarjeta de Estadísticas:
+#### Opciones exclusives de la Tarjeta de Estadísticas:
@@ -170 +170 @@
-#### Opciones exclusivas de la Tarjeta de Repo:
+#### Opciones exclusives de la Tarjeta de Repo:
@@ -174 +174 @@
-#### Opciones exclusivas de la Tarjeta de Lenguajes:
+#### Opciones exclusives de la Tarjeta de Lenguajes:
@@ -188 +188 @@
-#### Opciones exclusivas de la Tarjeta de Wakatime:
+#### Opciones exclusives de la Tarjeta de Wakatime:
@@ -220 +220 @@
-Utiliza la variable [show_owner](#customización) para incluir el nombre de usuario del propietario del repositorio.
+Utilize la variable [show_owner](#customización) para incluir el nombre de usuario del propietario del repositorio.
@@ -224 +224 @@
-# Tarjeta de Lenguajes Principales
+# Tarjeta de Lenguajes Principles
@@ -226 +226 @@
-La tarjeta de lenguajes principales muestra los lenguajes principales del usuario de GitHub que se han utilizado principalmente.
+La tarjeta de lenguajes principles muestra los lenguajes principles del usuario de GitHub que se han utilizado principalmente.
@@ -228 +228 @@
-_NOTA: los lenguajes principales no indican mi nivel de habilidad o algo así, es una métrica de GitHub de los lenguajes que tengo más código en GitHub. Es una nueva característica de github-readme-stats_
+_NOTA: los lenguajes principles no indican mi nivel de habilidad o algo así, es una métrica de GitHub de los lenguajes que tengo más código en GitHub. Es una nueva característica de github-readme-stats_
@@ -367 +367 @@
-Desde que la API de GitHub permite solo 5k peticiones por hora, es posible que mi `https://github-readme-stats.vercel.app/api` pueda llegar al límite. Si lo alojas en tu propio servidor de Vercel, no tendrás que preocuparte de nada. ¡Clickea en el botón "Deploy" para comenzar!
+Desde que la API de GitHub permite solo 5k peticiones por hora, es possible que mi `https://github-readme-stats.vercel.app/api` pueda llegar al límite. Si lo alojas en tu propio servidor de Vercel, no tendrás que preocuparte de nada. ¡Clickea en el botón "Deploy" para comenzar!
@@ -388 +388 @@
-9. Selecciona "root" y matén todo como está, simplemente añade tu variable de entorno llamada PAT_1 (como se muestra), la cual contendrá un token de acceso personal (PAT), el cual puedes crear fácilmente [aquí](https://github.com/settings/tokens/new) (mantén todo como está, simplemente asígnale un nombre, puede ser cualquiera que desees)
+9. Selecciona "root" y matén todo como está, simplemente añade tu variable de entorno llamada PAT_1 (como se muestra), la cual contendrá un token de acceso personal (PAT), el cual puedes crear fácilmente [aquí](https://github.com/settings/tokens/new) (mantén todo como está, simplemente asígnale un nombre, puede set cualquiera que desees)
@@ -396 +396 @@
-Casi todos mis proyectos son de código abierto e intento responder a todos los usuarios que necesiten ayuda con alguno de estos proyectos. Obviamente, esto toma tiempo. Puedes usar este servicio gratis.
+Casi todos miss proyectos son de código abierto e intento responder a todos los usuarios que necesiten ayuda con alguno de estos proyectos. Obviamente, esto toma tiempo. Puedes usar este servicio gratis.
--- ./docs/readme_nl.md	original
+++ ./docs/readme_nl.md	fixed
@@ -99 +99 @@
-_Notitie: Als je dit project zelf deployt, zullen de privé contributies standaard toegevoegt worden aan je totaal, omdat anders je hoeveelheid privé contributies moet delen._
+_Notitie: Also je dit project zelf deployt, zullen de privé contributies standaard toegevoegt worden aan je totaal, omdat anders je hoeveelheid privé contributies moet delen._
@@ -131 +131 @@
-Je kan een preview van alle [beschikbare thema\'s](../themes/README.md) bekijken, of zie het [thema configuratie bestand](../themes/index.js) en **je kan aan nieuwe thema\'s bijdragen** als je dat leuk lijkt :D
+Je kan een preview van alle [beschikbare thema\'s](../themes/README.md) bekijken, of zie het [thema configuratie bestand](../themes/index.js) en **je kan aan nieuwe thema\'s bijdragen** also je dat leuk lijkt :D
@@ -139,2 +139,2 @@
-- `title_color` - De kleur van de titel van de kaart _(hex kleur)_
-- `text_color` - Tekst kleur _(hex kleur)_
+- `title_color` - De kleur van de title van de kaart _(hex kleur)_
+- `text_color` - Text kleur _(hex kleur)_
@@ -156 +156 @@
-> Notities i.v.b.m. cache: Repo kaarten hebben een standaard cache van 4 uur (14400 seconden) als de fork hoeveelheid en de star hoeveelheid minder is dan 1k, anders is het 2 uur (7200 seconden). Daarnaast ligt de cache vast aan een minimum van 2 uur en een maximum van 24 uur.
+> Notities i.v.b.m. cache: Repo kaarten hebben een standaard cache van 4 uur (14400 seconden) also de fork hoeveelheid en de star hoeveelheid minder is dan 1k, anders is het 2 uur (7200 seconden). Daarnaast ligt de cache vast aan een minimum van 2 uur en een maximum van 24 uur.
@@ -167 +167 @@
-- `custom_title` - Stel een aangepaste titel voor je kaart in
+- `custom_title` - Stel een aangepaste title voor je kaart in
@@ -181 +181 @@
-- `custom_title` - Stelt een eigen titel voor de kaart in
+- `custom_title` - Stelt een eigen title voor de kaart in
@@ -191,3 +191,3 @@
-- `line_height` - Verandert de lijn hoogte tussen tekst _(nummer)_
-- `hide_progress` - Verbergt de progressiebalk en het percentage _(boolean)_
-- `custom_title` - Stelt een eigen titel voor de kaart in
+- `line_height` - Verandert de lijn hoogte tussen text _(nummer)_
+- `hide_progress` - Verbergt de progressiebalk en het percentage _(boolean)_
+- `custom_title` - Stelt een eigen title voor de kaart in
@@ -218 +218 @@
-Gebruikt [show_owner](#customization) variabele om de repo\'s eigenaar toe te voegen
+Gebruikt [show_owner](#customization) variable om de repo\'s eigenaar toe te voegen
@@ -362 +362 @@
-Sinds de GitHub API alleen maar 5k verzoeken per uur toestaat, zou mijn `https://github-readme-stats.vercel.app/api` mogelijk de rate limiet behalen. Als je het op je eigen Vercel server host, dan hoef je je nergens zorgen om te maken. Klik op de deploy knop om te beginnen!
+Sinds de GitHub API alleen maar 5k verzoeken per uur toestaat, zou mijn `https://github-readme-stats.vercel.app/api` mogelijk de rate limiet behalen. Also je het op je eigen Vercel server host, dan hoef je je nergens zorgen om te maken. Klik op de deploy knop om te beginnen!
@@ -393 +393 @@
-Hoe dan ook, als je dit project gebruikt en er blij mee bent, of mij wilt aanmoedigen om dingen te blijven maken, zijn er een paar manieren om dit te doen; -
+Hoe dan ook, also je dit project gebruikt en er blij mee bent, of mij wilt aanmoedigen om dingen te blijven maken, zijn er een paar manieren om dit te doen; -
--- ./docs/readme_cn.md	original
+++ ./docs/readme_cn.md	fixed
@@ -170 +170 @@
-- `hide` - 从卡片中隐藏指定语言 _(Comma seperated values)_
+- `hide` - 从卡片中隐藏指定语言 _(Comma separated values)_
--- ./docs/readme_pt-BR.md	original
+++ ./docs/readme_pt-BR.md	fixed
@@ -32 +32 @@
-    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Reportar erros</a>
+    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Reportar errors</a>
@@ -149 +149 @@
-#### Opções exclusivas do cartão de estatísticas:
+#### Opções exclusives do cartão de estatísticas:
@@ -151 +151 @@
-- `hide` - Oculta itens específicos das estatísticas _(Valores separados por vírgulas)_
+- `hide` - Oculta items específicos das estatísticas _(Valores separados por vírgulas)_
@@ -159 +159 @@
-#### Opções exclusivas do cartão de repositórios:
+#### Opções exclusives do cartão de repositórios:
@@ -163 +163 @@
-#### Opções exclusivas do cartão de linguagens:
+#### Opções exclusives do cartão de linguagens:
@@ -171 +171 @@
-> Nomes de linguagens devem ser uma sequência escapada de URI, como específicado em [Codificação por cento](https://pt.wikipedia.org/wiki/Codificação_por_cento)
+> Nomes de linguagens devem set uma sequência escapada de URI, como específicado em [Codificação por cento](https://pt.wikipedia.org/wiki/Codificação_por_cento)
@@ -313 +313 @@
-Como a API do GitHub permite apenas 5 mil solicitações por hora, é possível que minha `https://github-readme-stats.vercel.app/api` atinja a cota limite. Se hospedar em seu próprio servidor Vercel, não precisará se preocupar com nada. Clique no botão de implantação para começar!
+Como a API do GitHub permite apenas 5 mil solicitações por hora, é possível que minha `https://github-readme-stats.vercel.app/api` atinja a cota limit. Se hospedar em seu próprio servidor Vercel, não precisará se preocupar com nada. Clique no botão de implantação para começar!
@@ -334 +334 @@
-1. Selecione a raiz e mantenha tudo como está, basta adicionar sua variável de ambiente chamada PAT_1 (que será exibida), que conterá um token de acesso pessoal (PAT), que você pode criar facilmente [aqui](https://github.com/settings/tokens/new) (deixe tudo como está, apenas dê um nome, que pode ser o que você quiser)
+1. Selecione a raiz e mantenha tudo como está, basta adicionar sua variável de ambiente chamada PAT_1 (que será exibida), que conterá um token de acesso pessoal (PAT), que você pode criar facilmente [aqui](https://github.com/settings/tokens/new) (deixe tudo como está, apenas dê um nome, que pode set o que você quiser)
--- ./docs/readme_de.md	original
+++ ./docs/readme_de.md	fixed
@@ -35 +35 @@
-    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Funktion wünschen</a>
+    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Function wünschen</a>
@@ -73 +73 @@
-Kopiere folgendes in deine Readme um die Statistiken zu benutzen.
+Kopiere folgendes in define Readme um die Statistiken zu benutzen.
@@ -128 +128 @@
-- `bg_color` - Hintergrundfarbe _(hex color)_ **oder** ein Farbverlauf in der Form von _winkel,start,ende_
+- `bg_color` - Hintergrundfarbe _(hex color)_ **oder** ein Farbverlauf in der Form von _winkel,start,end_
@@ -142 +142 @@
-> Hinweis bzgl. des Caches: Wenn die Anzahl der Forks und Stars geringer als 1 Tsd. ist, haben die Repo-Cards eine Standard-Cachezeit von 30 Minuten (1800 Sekunden), ansonsten beträgt diese 2 Stunden (7200 Sekunden). Außerdem ist der Cache auf ein Minimum von 30 Minuten und ein Maximum von 24 Stunden begrenzt.
+> Hinweis bzgl. des Caches: Wenn die Anzahl der Forks und Stars geringer also 1 Tsd. ist, haben die Repo-Cards eine Standard-Cachezeit von 30 Minuten (1800 Sekunden), ansonsten beträgt diese 2 Stunden (7200 Sekunden). Außerdem ist der Cache auf ein Minimum von 30 Minuten und ein Maximum von 24 Stunden begrenzt.
@@ -163 +163 @@
-- `card_width` - Lege die Breite der Karte manuell fest _(Zahl)_
+- `card_width` - Lege die Breite der Karte manual fest _(Zahl)_
@@ -174,5 +174,5 @@
-- `custom_title` - Legt einen benutzerdefinierten Titel fest
-- `layout` - Wechselt zwischen zwei verschiedenen Layouts: `default` & `compact`
-- `langs_count` - Begrenzt die Anzahl der angezeigten Sprachen auf der Karte
-- `api_domain` - Legt eine benutzerdefinierte API Domain fest, z.B. für [Hakatime](https://github.com/mujx/hakatime) oder [Wakapi](https://github.com/muety/wakapi)
-- `range` – Fragt eine andere Zeitspanne an, als jene, welche standardmäßig in Wakatime hinterlegt ist. Zum Beispiel `last_7_days`. Siehe [WakaTime API Dokumentation](https://wakatime.com/developers#stats).
+- `custom_title` - Legt einen benutzerdefinierten Title fest
+- `layout` - Wechselt zwischen zwei verschiedenen Layouts: `default` & `compact`
+- `langs_count` - Begrenzt die Anzahl der angezeigten Sprachen auf der Karte
+- `api_domain` - Legt eine benutzerdefinierte API Domain fest, z.B. für [Hakatime](https://github.com/mujx/hakatime) oder [Wakapi](https://github.com/muety/wakapi)
+- `range` – Fragt eine andere Zeitspanne an, also jene, welche standardmäßig in Wakatime hinterlegt ist. Zum Beispiel `last_7_days`. Siehe [WakaTime API Dokumentation](https://wakatime.com/developers#stats).
@@ -184 +184 @@
-GitHub Extra-Pins ermöglicht es mit Hilfe einer Readme auf deinem Profil mehr als 6 Repositories anzuzeigen.
+GitHub Extra-Pins ermöglicht es mit Hilfe einer Readme auf deinem Profil mehr also 6 Repositories anzuzeigen.
@@ -190 +190 @@
-Füge diesen Code in deine Readme-Datei ein und passe die Links an.
+Füge diesen Code in define Readme-Datei ein und passe die Links an.
@@ -216 +216 @@
-Füge diesen Code in deine Readme-Datei ein und passe die Links an.
+Füge diesen Code in define Readme-Datei ein und passe die Links an.
@@ -331 +331 @@
-Hinweis: Seit [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) sollte es möglich sein, mehr als 5 Tsd Aufrufe pro Stunde ohne Downtimes zu verkraften :D
+Hinweis: Seit [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) sollte es möglich sein, mehr also 5 Tsd Aufrufe pro Stunde ohne Downtimes zu verkraften :D
@@ -346,7 +346,7 @@
-1. Klick `Import Project`
-   ![](https://files.catbox.moe/qckos0.png)
-1. Klick `Import Git Repository`
-   ![](https://files.catbox.moe/pqub9q.png)
-1. Wähle root und füge eine Umgebungsvariable namens PAT_1 (siehe Abbildung) die als Wert deinen persönlichen Access Token (PAT) hat hinzu, den du einfach [hier](https://github.com/settings/tokens/new) erzeugen kannst (lasse alles wie es ist, vergebe einen beliebigen Namen)
-   ![](https://files.catbox.moe/0ez4g7.png)
-1. Klicke auf `Deploy`, und das wars. Besuche deine Domains um die API zu benutzen!
+1. Click `Import Project`
+   ![](https://files.catbox.moe/qckos0.png)
+1. Click `Import Git Repository`
+   ![](https://files.catbox.moe/pqub9q.png)
+1. Wähle root und füge eine Umgebungsvariable namens PAT_1 (siehe Abbildung) die also Wert deinen persönlichen Access Token (PAT) hat hinzu, den du einfach [hier](https://github.com/settings/tokens/new) erzeugen kannst (lasse alles wie es ist, vergebe einen beliebigen Namen)
+   ![](https://files.catbox.moe/0ez4g7.png)
+1. Klicke auf `Deploy`, und das wars. Besuche define Domains um die API zu benutzen!
@@ -357 +357 @@
-Ich versuche alles was ich kann als Open-Source zur Verfügung zu stellen, als auch jedem der Hilfe bei der Benutzung dieses Projektes braucht zu antworten. Natürlich beansprucht sowas Zeit und du kannst diesen Dienst kostenlos benutzen.
+Ich versuche alles was ich kann also Open-Source zur Verfügung zu stellen, also auch jedem der Hilfe bei der Benutzung dieses Projektes braucht zu antworten. Natürlich beansprucht sowas Zeit und du kannst diesen Dienst kostenlos benutzen.
--- ./themes/README.md	original
+++ ./themes/README.md	fixed
@@ -26 +26 @@
-| `algolia` ![algolia][algolia] | `great-gatsby` ![great-gatsby][great-gatsby] | `darcula` ![darcula][darcula] |
+| `algolia` ![algolia][algolia] | `great-gatsby` ![great-gatsby][great-gatsby] | `dracula` ![dracula][dracula] |
@@ -54 +54 @@
-| `algolia` ![algolia][algolia_repo] | `great-gatsby` ![great-gatsby][great-gatsby_repo] | `darcula` ![darcula][darcula_repo] |
+| `algolia` ![algolia][algolia_repo] | `great-gatsby` ![great-gatsby][great-gatsby_repo] | `dracula` ![dracula][dracula_repo] |
@@ -94 +94 @@
-[darcula]: https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&hide=contribs,prs&cache_seconds=86400&theme=darcula
+[dracula]: https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&hide=contribs,prs&cache_seconds=86400&theme=darcula
@@ -157 +157 @@
-[darcula_repo]: https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&cache_seconds=86400&theme=darcula
+[dracula_repo]: https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&cache_seconds=86400&theme=darcula
--- ./themes/index.js	original
+++ ./themes/index.js	fixed
@@ -147 +147 @@
-  darcula: {
+  dracula: {
--- ./api/pin.js	original
+++ ./api/pin.js	fixed
@@ -49 +49 @@
-      if star count & fork count is over 1k then we are kFormating the text
+      if star count & fork count is over 1k then we are kFormatting the text
--- ./docs/readme_it.md	original
+++ ./docs/readme_it.md	fixed
@@ -95 +95 @@
-_Nota: se hai deciso di fare il deploy del progetto, i contributi privati verranno inclusi in automatico._
+_Nota: se hai deciso di fare il deploy del progetto, i contributi privati verranno inclusi in automation._
@@ -113 +113 @@
-Esistono alcuni temi predefiniti coi quali è possibile personalizzare l'aspetto delle card. In alternativa, è possibile effettuare una [personalizzazione manuale](#personalizzazione).
+Esistono alcuni temi predefiniti coi quali è possible personalizzare l'aspetto delle card. In alternativa, è possible effettuare una [personalizzazione manuale](#personalizzazione).
@@ -154 +154 @@
-#### Opzioni valide solo per le card delle statistiche:
+#### Opzioni valid solo per le card delle statistiche:
@@ -164 +164 @@
-#### Opzioni valide solo per le Repo Card:
+#### Opzioni valid solo per le Repo Card:
@@ -168 +168 @@
-#### Opzioni valide solo per le card dei linguaggi:
+#### Opzioni valid solo per le card dei linguaggi:
@@ -176 +176 @@
-> Per i nomi dei linguaggi, assicurati di effettuare l'encoding giusto nell'uri, come specificato in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
+> Per i nomi dei linguaggi, assicurati di effettuare l'encoding giusto nell'uri, come specification in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
@@ -207 +207 @@
-_NOTA: questa card non indica il livello di abilità, ma piuttosto quanto codice hai scritto in un determinato linguaggio_
+_NOTA: questa card non indica il livello di abilità, ma piuttosto quanto codice hai scritto in un determination linguaggio_
