## Detected Typos Diff
```diff
--- ./tests/scenarios/pokemon/getAllPokemonSpecies.test.ts	original
+++ ./tests/scenarios/pokemon/getAllPokemonSpecies.test.ts	fixed
@@ -1344 +1344 @@
-      { key: 'watchog', species: 'watchog' },
+      { key: 'watchdog', species: 'watchdog' },
--- ./CHANGELOG.md	original
+++ ./CHANGELOG.md	fixed
@@ -526 +526 @@
-  aliasses have drastically changed so this should be considered a breaking change.
+  aliases have drastically changed so this should be considered a breaking change.
@@ -589 +589 @@
-- **abilities:** fixed coaching description ([f480ded](https://github.com/favware/graphql-pokemon/commit/f480ded2cbf02e3da925003ae729bcf5cde0cb30))
+- **abilities:** fixed coaching description ([f480dead](https://github.com/favware/graphql-pokemon/commit/f480ded2cbf02e3da925003ae729bcf5cde0cb30))
@@ -762 +762 @@
-- update smogon tierlists ([#89](https://github.com/favware/graphql-pokemon/issues/89)) ([313ded3](https://github.com/favware/graphql-pokemon/commit/313ded3054919f4ef2ebb81282c17f9e11a7364e))
+- update smogon tierlists ([#89](https://github.com/favware/graphql-pokemon/issues/89)) ([313dead3](https://github.com/favware/graphql-pokemon/commit/313ded3054919f4ef2ebb81282c17f9e11a7364e))
--- ./graphql/enums.graphql	original
+++ ./graphql/enums.graphql	fixed
@@ -1008,2074 +1008,2074 @@
-  watchog
-  lillipup
-  herdier
-  stoutland
-  purrloin
-  liepard
-  pansage
-  simisage
-  pansear
-  simisear
-  panpour
-  simipour
-  munna
-  musharna
-  pidove
-  tranquill
-  unfezant
-  blitzle
-  zebstrika
-  roggenrola
-  boldore
-  gigalith
-  woobat
-  swoobat
-  drilbur
-  excadrill
-  audino
-  audinomega
-  timburr
-  gurdurr
-  conkeldurr
-  tympole
-  palpitoad
-  seismitoad
-  throh
-  sawk
-  sewaddle
-  swadloon
-  leavanny
-  venipede
-  whirlipede
-  scolipede
-  cottonee
-  whimsicott
-  petilil
-  lilligant
-  lilliganthisui
-  basculin
-  basculinbluestriped
-  basculinwhitestriped
-  sandile
-  krokorok
-  krookodile
-  darumaka
-  darumakagalar
-  darmanitan
-  darmanitangalar
-  darmanitanzen
-  darmanitangalarzen
-  maractus
-  dwebble
-  crustle
-  scraggy
-  scrafty
-  sigilyph
-  yamask
-  yamaskgalar
-  cofagrigus
-  tirtouga
-  carracosta
-  archen
-  archeops
-  trubbish
-  garbodor
-  garbodorgmax
-  zorua
-  zoruahisui
-  zoroark
-  zoroarkhisui
-  minccino
-  cinccino
-  gothita
-  gothorita
-  gothitelle
-  solosis
-  duosion
-  reuniclus
-  ducklett
-  swanna
-  vanillite
-  vanillish
-  vanilluxe
-  deerling
-  sawsbuck
-  emolga
-  karrablast
-  escavalier
-  foongus
-  amoonguss
-  frillish
-  frillishfemale
-  jellicent
-  jellicentfemale
-  alomomola
-  joltik
-  galvantula
-  ferroseed
-  ferrothorn
-  klink
-  klang
-  klinklang
-  tynamo
-  eelektrik
-  eelektross
-  elgyem
-  beheeyem
-  litwick
-  lampent
-  chandelure
-  axew
-  fraxure
-  haxorus
-  cubchoo
-  beartic
-  cryogonal
-  shelmet
-  accelgor
-  stunfisk
-  stunfiskgalar
-  mienfoo
-  mienshao
-  druddigon
-  golett
-  golurk
-  pawniard
-  bisharp
-  bouffalant
-  rufflet
-  braviary
-  braviaryhisui
-  vullaby
-  mandibuzz
-  heatmor
-  durant
-  deino
-  zweilous
-  hydreigon
-  larvesta
-  volcarona
-  cobalion
-  terrakion
-  virizion
-  tornadus
-  tornadustherian
-  thundurus
-  thundurustherian
-  reshiram
-  zekrom
-  landorus
-  landorustherian
-  kyurem
-  kyuremblack
-  kyuremwhite
-  keldeo
-  keldeoresolute
-  meloetta
-  meloettapirouette
-  genesect
-  genesectdouse
-  genesectshock
-  genesectburn
-  genesectchill
-  chespin
-  quilladin
-  chesnaught
-  fennekin
-  braixen
-  delphox
-  froakie
-  frogadier
-  greninja
-  greninjaash
-  bunnelby
-  diggersby
-  fletchling
-  fletchinder
-  talonflame
-  scatterbug
-  spewpa
-  vivillon
-  vivillonfancy
-  vivillonpokeball
-  litleo
-  pyroar
-  flabebe
-  floette
-  floetteeternal
-  florges
-  skiddo
-  gogoat
-  pancham
-  pangoro
-  furfrou
-  espurr
-  meowstic
-  meowsticf
-  honedge
-  doublade
-  aegislash
-  aegislashblade
-  spritzee
-  aromatisse
-  swirlix
-  slurpuff
-  inkay
-  malamar
-  binacle
-  barbaracle
-  skrelp
-  dragalge
-  clauncher
-  clawitzer
-  helioptile
-  heliolisk
-  tyrunt
-  tyrantrum
-  amaura
-  aurorus
-  sylveon
-  hawlucha
-  dedenne
-  carbink
-  goomy
-  sliggoo
-  sliggoohisui
-  goodra
-  goodrahisui
-  klefki
-  phantump
-  trevenant
-  pumpkaboo
-  pumpkaboosmall
-  pumpkaboolarge
-  pumpkaboosuper
-  gourgeist
-  gourgeistsmall
-  gourgeistlarge
-  gourgeistsuper
-  bergmite
-  avalugg
-  avalugghisui
-  noibat
-  noivern
-  xerneas
-  xerneasneutral
-  yveltal
-  zygarde
-  zygarde10
-  zygardecomplete
-  diancie
-  dianciemega
-  hoopa
-  hoopaunbound
-  volcanion
-  rowlet
-  dartrix
-  decidueye
-  decidueyehisui
-  litten
-  torracat
-  incineroar
-  popplio
-  brionne
-  primarina
-  pikipek
-  trumbeak
-  toucannon
-  yungoos
-  gumshoos
-  gumshoostotem
-  grubbin
-  charjabug
-  vikavolt
-  vikavolttotem
-  crabrawler
-  crabominable
-  oricorio
-  oricoriopompom
-  oricoriopau
-  oricoriosensu
-  cutiefly
-  ribombee
-  ribombeetotem
-  rockruff
-  lycanroc
-  lycanrocmidnight
-  lycanrocdusk
-  wishiwashi
-  wishiwashischool
-  mareanie
-  toxapex
-  mudbray
-  mudsdale
-  dewpider
-  araquanid
-  araquanidtotem
-  fomantis
-  lurantis
-  lurantistotem
-  morelull
-  shiinotic
-  salandit
-  salazzle
-  salazzletotem
-  stufful
-  bewear
-  bounsweet
-  steenee
-  tsareena
-  comfey
-  oranguru
-  passimian
-  wimpod
-  golisopod
-  sandygast
-  palossand
-  pyukumuku
-  typenull
-  silvally
-  silvallybug
-  silvallydark
-  silvallydragon
-  silvallyelectric
-  silvallyfairy
-  silvallyfighting
-  silvallyfire
-  silvallyflying
-  silvallyghost
-  silvallygrass
-  silvallyground
-  silvallyice
-  silvallypoison
-  silvallypsychic
-  silvallyrock
-  silvallysteel
-  silvallywater
-  minior
-  miniormeteor
-  komala
-  turtonator
-  togedemaru
-  togedemarutotem
-  mimikyu
-  mimikyubusted
-  mimikyutotem
-  mimikyubustedtotem
-  bruxish
-  drampa
-  dhelmise
-  jangmoo
-  hakamoo
-  kommoo
-  kommoototem
-  tapukoko
-  tapulele
-  tapubulu
-  tapufini
-  cosmog
-  cosmoem
-  solgaleo
-  lunala
-  nihilego
-  buzzwole
-  pheromosa
-  xurkitree
-  celesteela
-  kartana
-  guzzlord
-  necrozma
-  necrozmaduskmane
-  necrozmadawnwings
-  necrozmaultra
-  magearna
-  magearnaoriginal
-  marshadow
-  poipole
-  naganadel
-  stakataka
-  blacephalon
-  zeraora
-  meltan
-  melmetal
-  melmetalgmax
-  grookey
-  thwackey
-  rillaboom
-  rillaboomgmax
-  scorbunny
-  raboot
-  cinderace
-  cinderacegmax
-  sobble
-  drizzile
-  inteleon
-  inteleongmax
-  skwovet
-  greedent
-  rookidee
-  corvisquire
-  corviknight
-  corviknightgmax
-  blipbug
-  dottler
-  orbeetle
-  orbeetlegmax
-  nickit
-  thievul
-  gossifleur
-  eldegoss
-  wooloo
-  dubwool
-  chewtle
-  drednaw
-  drednawgmax
-  yamper
-  boltund
-  rolycoly
-  carkol
-  coalossal
-  coalossalgmax
-  applin
-  flapple
-  flapplegmax
-  appletun
-  appletungmax
-  silicobra
-  sandaconda
-  sandacondagmax
-  cramorant
-  cramorantgulping
-  cramorantgorging
-  arrokuda
-  barraskewda
-  toxel
-  toxtricity
-  toxtricitylowkey
-  toxtricitygmax
-  toxtricitylowkeygmax
-  sizzlipede
-  centiskorch
-  centiskorchgmax
-  clobbopus
-  grapploct
-  sinistea
-  sinisteaantique
-  polteageist
-  polteageistantique
-  hatenna
-  hattrem
-  hatterene
-  hatterenegmax
-  impidimp
-  morgrem
-  grimmsnarl
-  grimmsnarlgmax
-  obstagoon
-  perrserker
-  cursola
-  sirfetchd
-  mrrime
-  runerigus
-  milcery
-  alcremie
-  alcremiegmax
-  falinks
-  pincurchin
-  snom
-  frosmoth
-  stonjourner
-  eiscue
-  eiscuenoice
-  indeedee
-  indeedeef
-  morpeko
-  morpekohangry
-  cufant
-  copperajah
-  copperajahgmax
-  dracozolt
-  arctozolt
-  dracovish
-  arctovish
-  duraludon
-  duraludongmax
-  dreepy
-  drakloak
-  dragapult
-  zacian
-  zaciancrowned
-  zamazenta
-  zamazentacrowned
-  eternatus
-  eternatuseternamax
-  kubfu
-  urshifu
-  urshifurapidstrike
-  urshifugmax
-  urshifurapidstrikegmax
-  zarude
-  zarudedada
-  regieleki
-  regidrago
-  glastrier
-  spectrier
-  calyrex
-  calyrexice
-  calyrexshadow
-  wyrdeer
-  kleavor
-  ursaluna
-  basculegion
-  basculegionf
-  sneasler
-  overqwil
-  enamorus
-  enamorustherian
-  pokestarsmeargle
-  pokestarufo
-  pokestarufo2
-  pokestarbrycenman
-  pokestarmt
-  pokestarmt2
-  pokestartransport
-  pokestargiant
-  pokestarhumanoid
-  pokestarmonster
-  pokestarf00
-  pokestarf002
-  pokestarspirit
-  pokestarblackdoor
-  pokestarwhitedoor
-  pokestarblackbelt
-  pokestarufopropu2
-}
-
-"The supported items"
-enum ItemsEnum {
-  abomasite
-  absolite
-  absorbbulb
-  adamantorb
-  adrenalineorb
-  aerodactylite
-  aggronite
-  aguavberry
-  airballoon
-  alakazite
-  aloraichiumz
-  altarianite
-  ampharosite
-  apicotberry
-  armorfossil
-  aspearberry
-  assaultvest
-  audinite
-  babiriberry
-  banettite
-  beastball
-  beedrillite
-  belueberry
-  berry
-  berryjuice
-  berrysweet
-  berserkgene
-  bigroot
-  bindingband
-  bitterberry
-  blackbelt
-  blackglasses
-  blacksludge
-  blastoisinite
-  blazikenite
-  blueorb
-  blukberry
-  blunderpolicy
-  bottlecap
-  brightpowder
-  buggem
-  bugmemory
-  buginiumz
-  burndrive
-  burntberry
-  cameruptite
-  cellbattery
-  charcoal
-  charizarditex
-  charizarditey
-  chartiberry
-  cheriberry
-  cherishball
-  chestoberry
-  chilanberry
-  chilldrive
-  chippedpot
-  choiceband
-  choicescarf
-  choicespecs
-  chopleberry
-  clawfossil
-  cloversweet
-  cobaberry
-  colburberry
-  cornnberry
-  coverfossil
-  crucibellite
-  crackedpot
-  custapberry
-  damprock
-  darkgem
-  darkmemory
-  darkiniumz
-  dawnstone
-  decidiumz
-  deepseascale
-  deepseatooth
-  destinyknot
-  diancite
-  diveball
-  domefossil
-  dousedrive
-  dracoplate
-  dragonfang
-  dragongem
-  dragonmemory
-  dragonscale
-  dragoniumz
-  dreadplate
-  dreamball
-  dubiousdisc
-  durinberry
-  duskball
-  duskstone
-  earthplate
-  eeviumz
-  ejectbutton
-  ejectpack
-  electirizer
-  electricgem
-  electricmemory
-  electricseed
-  electriumz
-  energypowder
-  enigmaberry
-  eviolite
-  expertbelt
-  fairiumz
-  fairygem
-  fairymemory
-  fastball
-  fightinggem
-  fightingmemory
-  fightiniumz
-  figyberry
-  firegem
-  firememory
-  firestone
-  firiumz
-  fistplate
-  flameorb
-  flameplate
-  floatstone
-  flowersweet
-  flyinggem
-  flyingmemory
-  flyiniumz
-  focusband
-  focussash
-  fossilizedbird
-  fossilizeddino
-  fossilizeddrake
-  fossilizedfish
-  friendball
-  fullincense
-  fullrestore
-  galaricacuff
-  galaricawreath
-  galladite
-  ganlonberry
-  garchompite
-  gardevoirite
-  gengarite
-  ghostgem
-  ghostmemory
-  ghostiumz
-  glalitite
-  goldberry
-  goldbottlecap
-  grassgem
-  grassmemory
-  grassiumz
-  grassyseed
-  greatball
-  grepaberry
-  gripclaw
-  griseousorb
-  groundgem
-  groundmemory
-  groundiumz
-  gyaradosite
-  habanberry
-  hardstone
-  healball
-  heatrock
-  heavyball
-  heavydutyboots
-  helixfossil
-  heracronite
-  hondewberry
-  houndoominite
-  hyperpotion
-  iapapaberry
-  iceberry
-  icegem
-  icememory
-  icestone
-  icicleplate
-  iciumz
-  icyrock
-  inciniumz
-  insectplate
-  ironball
-  ironplate
-  jabocaberry
-  jawfossil
-  kangaskhanite
-  kasibberry
-  kebiaberry
-  keeberry
-  kelpsyberry
-  kingsrock
-  kommoniumz
-  laggingtail
-  lansatberry
-  latiasite
-  latiosite
-  laxincense
-  leafstone
-  leek
-  leftovers
-  leppaberry
-  levelball
-  liechiberry
-  lifeorb
-  lightball
-  lightclay
-  lopunnite
-  loveball
-  lovesweet
-  lucarionite
-  luckypunch
-  lumberry
-  luminousmoss
-  lunaliumz
-  lureball
-  lustrousorb
-  luxuryball
-  lycaniumz
-  machobrace
-  magmarizer
-  magnet
-  magoberry
-  magostberry
-  mail
-  manectite
-  marangaberry
-  marshadiumz
-  masterball
-  mawilite
-  maxpotion
-  meadowplate
-  medichamite
-  mentalherb
-  metagrossite
-  metalcoat
-  metalpowder
-  metronome
-  mewniumz
-  mewtwonitex
-  mewtwonitey
-  micleberry
-  mimikiumz
-  mindplate
-  mintberry
-  miracleberry
-  miracleseed
-  mistyseed
-  moonball
-  moonstone
-  muscleband
-  mysteryberry
-  mysticwater
-  nanabberry
-  nestball
-  netball
-  nevermeltice
-  nomelberry
-  normalgem
-  normaliumz
-  occaberry
-  oddincense
-  oldamber
-  oranberry
-  ovalstone
-  przcureberry
-  psncureberry
-  pamtreberry
-  parkball
-  passhoberry
-  payapaberry
-  pechaberry
-  persimberry
-  petayaberry
-  pidgeotite
-  pikaniumz
-  pikashuniumz
-  pinapberry
-  pinkbow
-  pinsirite
-  pixieplate
-  plumefossil
-  poisonbarb
-  poisongem
-  poisonmemory
-  poisoniumz
-  pokeball
-  polkadotbow
-  pomegberry
-  poweranklet
-  powerband
-  potion
-  powerbelt
-  powerbracer
-  powerherb
-  powerlens
-  powerweight
-  premierball
-  primariumz
-  prismscale
-  protectivepads
-  protector
-  psychicgem
-  psychicmemory
-  psychicseed
-  psychiumz
-  qualotberry
-  quickball
-  quickclaw
-  quickpowder
-  rabutaberry
-  rarebone
-  rawstberry
-  razorclaw
-  razorfang
-  razzberry
-  reapercloth
-  redcard
-  redorb
-  repeatball
-  ribbonsweet
-  rindoberry
-  ringtarget
-  rockgem
-  rockincense
-  rockmemory
-  rockiumz
-  roseincense
-  rockyhelmet
-  roomservice
-  rootfossil
-  roseliberry
-  rowapberry
-  rustedshield
-  rustedsword
-  sablenite
-  sachet
-  safariball
-  safetygoggles
-  sailfossil
-  salacberry
-  salamencite
-  sceptilite
-  scizorite
-  scopelens
-  seaincense
-  sharpbeak
-  sharpedonite
-  shedshell
-  shellbell
-  shinystone
-  shockdrive
-  shucaberry
-  silkscarf
-  silverpowder
-  sitrusberry
-  skullfossil
-  skyplate
-  slowbronite
-  smoothrock
-  snorliumz
-  snowball
-  softsand
-  solganiumz
-  souldew
-  spelltag
-  spelonberry
-  splashplate
-  spookyplate
-  sportball
-  starfberry
-  steelgem
-  steelmemory
-  steeliumz
-  starsweet
-  steelixite
-  stick
-  stickybarb
-  stoneplate
-  strawberrysweet
-  sunstone
-  superpotion
-  swampertite
-  sweetapple
-  tamatoberry
-  tangaberry
-  tapuniumz
-  tartapple
-  terrainextender
-  thickclub
-  throatspray
-  thunderstone
-  timerball
-  toxicorb
-  toxicplate
-  twistedspoon
-  tyranitarite
-  ultraball
-  ultranecroziumz
-  upgrade
-  utilityumbrella
-  venusaurite
-  vilevial
-  wacanberry
-  watergem
-  watermemory
-  waterstone
-  wateriumz
-  watmelberry
-  waveincense
-  weaknesspolicy
-  wepearberry
-  whippeddream
-  whiteherb
-  widelens
-  wikiberry
-  wiseglasses
-  yacheberry
-  zapplate
-  zoomlens
-  acrobike
-  adventureguide
-  apricornbox
-  aquasuit
-  auroraticket
-  autograph
-  azureflute
-  bandautograph
-  basementkey
-  berrypots
-  berrypouch
-  bicycle
-  bikevoucher
-  bluecard
-  bluepetal
-  campinggear
-  cardkey
-  catchingcharm
-  clearbell
-  coincase
-  colressmchn
-  contestcostume
-  contestpass
-  coupon1
-  coupon2
-  coupon3
-  dnasplicers
-  darkstone
-  devongoods
-  devonparts
-  devonscope
-  devonscubagear
-  dowsingmchn
-  dowsingmachine
-  dragonskull
-  droppeditem
-  dynamaxband
-  eggcard
-  elevatorkey
-  endorsement
-  enigmastone
-  enigmaticcard
-  eonflute
-  eonticket
-  escaperope
-  expshare
-  explorerkit
-  famechecker
-  fashioncase
-  fishingrod
-  foragebag
-  gbsounds
-  gsball
-  galactickey
-  gogoggles
-  godstone
-  goldteeth
-  goodrod
-  gracidea
-  gram1
-  gram2
-  gram3
-  greenpetal
-  grubbyhanky
-  hitechearbuds
-  holocaster
-  honorofkalos
-  ilimasnormaliumz
-  intriguingstone
-  itemfinder
-  jadeorb
-  journal
-  keystone
-  keytoroom1
-  keytoroom2
-  keytoroom4
-  keytoroom6
-  leftpokeball
-  legendplate
-  lenscase
-  letter
-  libertypass
-  liftkey
-  lightstone
-  lockcapsule
-  lookerticket
-  lootsack
-  lostitem
-  lunarwing
-  machbike
-  machinepart
-  magmaemblem
-  magmastone
-  magmasuit
-  makeupbag
-  medalbox
-  megabracelet
-  megaring
-  membercard
-  meteorite
-  meteoriteshard
-  moonflute
-  mysteryegg
-  mysticticket
-  nlunarizer
-  nsolarizer
-  oaksletter
-  oaksparcel
-  oldcharm
-  oldletter
-  oldrod
-  oldseamap
-  orangepetal
-  ovalcharm
-  pairoftickets
-  palpad
-  parcel
-  pass
-  permit
-  photoalbum
-  pinkpetal
-  plasmacard
-  poffincase
-  pointcard
-  pokeradar
-  pokeblockkit
-  pokeblockcase
-  pokeflute
-  pokemonboxlink
-  powderjar
-  powerplantpass
-  prisonbottle
-  profsletter
-  professorsmask
-  propcase
-  purplepetal
-  ragecandybar
-  rainbowflower
-  rainbowpass
-  rainbowwing
-  redchain
-  redpetal
-  redscale
-  revealglass
-  ridepager
-  rm1key
-  rm2key
-  rm4key
-  rm6key
-  rollerskates
-  rotombike
-  rotomcatalog
-  ruby
-  rulebook
-  ssticket
-  sapphire
-  scanner
-  sealbag
-  sealcase
-  secretkey
-  secretpotion
-  shinycharm
-  silphscope
-  silverwing
-  slowpoketail
-  soniasbook
-  sootsack
-  sparklingstone
-  sprayduck
-  sprinklotad
-  squirtbottle
-  storagekey
-  suitekey
-  sunflute
-  superrod
-  surgebadge
-  tmcase
-  tmvpass
-  tea
-  teachytv
-  tidalbell
-  townmap
-  traveltrunk
-  tripass
-  unownreport
-  vsrecorder
-  vsseeker
-  wailmerpail
-  wishingstar
-  workskey
-  xtransceiver
-  yellowpetal
-  zpowering
-  zring
-  zygardecube
-}
-
-"The supported moves"
-enum MovesEnum {
-  tenmillionvoltthunderbolt
-  absorb
-  accelerock
-  acid
-  acidarmor
-  aciddownpour
-  acidspray
-  acrobatics
-  acupressure
-  aerialace
-  aeroblast
-  afteryou
-  agility
-  aircutter
-  airslash
-  alloutpummeling
-  allyswitch
-  amnesia
-  anchorshot
-  ancientpower
-  appleacid
-  aquajet
-  aquaring
-  aquatail
-  armthrust
-  aromatherapy
-  aromaticmist
-  assist
-  assurance
-  astralbarrage
-  astonish
-  attackorder
-  attract
-  aurasphere
-  aurawheel
-  aurorabeam
-  auroraveil
-  autotomize
-  avalanche
-  babydolleyes
-  baddybad
-  banefulbunker
-  barbbarrage
-  barrage
-  barrier
-  batonpass
-  beakblast
-  beatup
-  belch
-  behemothbash
-  behemothblade
-  bellydrum
-  bestow
-  bide
-  bind
-  bite
-  bittermalice
-  blackholeeclipse
-  blastburn
-  blazekick
-  bleakwindstorm
-  blizzard
-  block
-  bloomdoom
-  blueflare
-  bodypress
-  bodyslam
-  boltbeak
-  boltstrike
-  boneclub
-  bonerush
-  bonemerang
-  boomburst
-  bounce
-  bouncybubble
-  bravebird
-  branchpoke
-  breakingswipe
-  breakneckblitz
-  brickbreak
-  brine
-  brutalswing
-  bubble
-  bubblebeam
-  bugbite
-  bugbuzz
-  bulkup
-  bulldoze
-  bulletpunch
-  bulletseed
-  burningjealousy
-  burnup
-  buzzybuzz
-  calmmind
-  camouflage
-  captivate
-  catastropika
-  ceaselessedge
-  celebrate
-  charge
-  chargebeam
-  charm
-  chatter
-  chipaway
-  chloroblast
-  circlethrow
-  clamp
-  clangingscales
-  clangoroussoul
-  clangoroussoulblaze
-  clearsmog
-  closecombat
-  coaching
-  coil
-  cometpunch
-  confide
-  confuseray
-  confusion
-  constrict
-  continentalcrush
-  conversion
-  conversion2
-  copycat
-  coreenforcer
-  corkscrewcrash
-  corrosivegas
-  cosmicpower
-  cottonguard
-  cottonspore
-  counter
-  courtchange
-  covet
-  crabhammer
-  craftyshield
-  crosschop
-  crosspoison
-  crunch
-  crushclaw
-  crushgrip
-  curse
-  cut
-  darkpulse
-  darkvoid
-  darkestlariat
-  dazzlinggleam
-  decorate
-  defendorder
-  defensecurl
-  defog
-  destinybond
-  detect
-  devastatingdrake
-  diamondstorm
-  dig
-  direclaw
-  disable
-  disarmingvoice
-  discharge
-  dive
-  dizzypunch
-  doomdesire
-  doublehit
-  doubleironbash
-  doublekick
-  doubleslap
-  doubleteam
-  doubleedge
-  dracometeor
-  dragonascent
-  dragonbreath
-  dragonclaw
-  dragondance
-  dragondarts
-  dragonenergy
-  dragonhammer
-  dragonpulse
-  dragonrage
-  dragonrush
-  dragontail
-  drainpunch
-  drainingkiss
-  dreameater
-  drillpeck
-  drillrun
-  drumbeating
-  dualchop
-  dynamicpunch
-  dualwingbeat
-  dynamaxcannon
-  earthpower
-  earthquake
-  echoedvoice
-  eerieimpulse
-  eeriespell
-  eggbomb
-  electricterrain
-  electrify
-  electroball
-  electroweb
-  embargo
-  ember
-  encore
-  endeavor
-  endure
-  energyball
-  entrainment
-  eruption
-  esperwing
-  eternabeam
-  expandingforce
-  explosion
-  extrasensory
-  extremeevoboost
-  extremespeed
-  facade
-  fairylock
-  fairywind
-  fakeout
-  faketears
-  falsesurrender
-  falseswipe
-  featherdance
-  feint
-  feintattack
-  fellstinger
-  fierydance
-  fierywrath
-  finalgambit
-  fireblast
-  firefang
-  firelash
-  firepledge
-  firepunch
-  firespin
-  firstimpression
-  fishiousrend
-  fissure
-  flail
-  flameburst
-  flamecharge
-  flamewheel
-  flamethrower
-  flareblitz
-  flash
-  flashcannon
-  flatter
-  fleurcannon
-  fling
-  flipturn
-  floatyfall
-  floralhealing
-  flowershield
-  fly
-  flyingpress
-  focusblast
-  focusenergy
-  focuspunch
-  followme
-  forcepalm
-  foresight
-  forestscurse
-  foulplay
-  freezeshock
-  freezedry
-  freezingglare
-  freezyfrost
-  frenzyplant
-  frostbreath
-  frustration
-  furyattack
-  furycutter
-  furyswipes
-  fusionbolt
-  fusionflare
-  futuresight
-  gastroacid
-  geargrind
-  gearup
-  genesissupernova
-  geomancy
-  gigadrain
-  gigaimpact
-  gigavolthavoc
-  glaciallance
-  glaciate
-  glare
-  glitzyglow
-  gmaxbefuddle
-  gmaxcannonade
-  gmaxcentiferno
-  gmaxchistrike
-  gmaxcuddle
-  gmaxdepletion
-  gmaxdrumsolo
-  gmaxfinale
-  gmaxtartness
-  gmaxvinelash
-  gmaxvolcalith
-  gmaxvoltcrash
-  gmaxwildfire
-  gmaxwindrage
-  gmaxfireball
-  gmaxfoamburst
-  gmaxgoldrush
-  gmaxgravitas
-  gmaxhydrosnipe
-  gmaxmalodor
-  gmaxmeltdown
-  gmaxstonesurge
-  gmaxstunshock
-  gmaxsweetness
-  gmaxterror
-  gmaxoneblow
-  gmaxrapidflow
-  gmaxreplenish
-  gmaxresonance
-  gmaxsandblast
-  gmaxsmite
-  gmaxsnooze
-  gmaxsteelsurge
-  grassknot
-  grasspledge
-  grasswhistle
-  grassyglide
-  grassyterrain
-  gravapple
-  gravity
-  growl
-  growth
-  grudge
-  guardsplit
-  guardswap
-  guardianofalola
-  guillotine
-  gunkshot
-  gust
-  gyroball
-  hail
-  hammerarm
-  happyhour
-  harden
-  haze
-  headcharge
-  headsmash
-  headbutt
-  headlongrush
-  healbell
-  healblock
-  healorder
-  healpulse
-  healingwish
-  heartstamp
-  heartswap
-  heatcrash
-  heatwave
-  heavyslam
-  helpinghand
-  hex
-  hiddenpower
-  hiddenpowerbug
-  hiddenpowerdark
-  hiddenpowerdragon
-  hiddenpowerelectric
-  hiddenpowerfighting
-  hiddenpowerfire
-  hiddenpowerflying
-  hiddenpowerghost
-  hiddenpowergrass
-  hiddenpowerground
-  hiddenpowerice
-  hiddenpowerpoison
-  hiddenpowerpsychic
-  hiddenpowerrock
-  hiddenpowersteel
-  hiddenpowerwater
-  highhorsepower
-  highjumpkick
-  holdback
-  holdhands
-  honeclaws
-  hornattack
-  horndrill
-  hornleech
-  howl
-  hurricane
-  hydrocannon
-  hydropump
-  hydrovortex
-  hyperbeam
-  hyperfang
-  hypervoice
-  hyperspacefury
-  hyperspacehole
-  hypnosis
-  iceball
-  icebeam
-  iceburn
-  icefang
-  icehammer
-  icepunch
-  iceshard
-  iciclecrash
-  iciclespear
-  icywind
-  imprison
-  incinerate
-  infernalparade
-  inferno
-  infernooverdrive
-  infestation
-  ingrain
-  instruct
-  iondeluge
-  irondefense
-  ironhead
-  irontail
-  jawlock
-  judgment
-  jumpkick
-  junglehealing
-  karatechop
-  kinesis
-  kingsshield
-  knockoff
-  landswrath
-  laserfocus
-  lashout
-  lastresort
-  lavaplume
-  leafblade
-  leafstorm
-  leaftornado
-  leafage
-  leechlife
-  leechseed
-  leer
-  letssnuggleforever
-  lick
-  lightscreen
-  lightthatburnsthesky
-  lifedew
-  lightofruin
-  liquidation
-  lockon
-  lovelykiss
-  lowkick
-  lowsweep
-  luckychant
-  lunarblessing
-  lunardance
-  lunge
-  lusterpurge
-  machpunch
-  magiccoat
-  magicpowder
-  magicroom
-  magicalleaf
-  magikarpsrevenge
-  magmastorm
-  magnetbomb
-  magnetrise
-  magneticflux
-  magnitude
-  maliciousmoonsault
-  matblock
-  mefirst
-  maxairstream
-  maxdarkness
-  maxflare
-  maxflutterby
-  maxgeyser
-  maxguard
-  meanlook
-  maxhailstorm
-  maxknuckle
-  maxlightning
-  maxmindstorm
-  maxooze
-  maxovergrowth
-  maxphantasm
-  maxquake
-  maxrockfall
-  maxstarfall
-  maxsteelspike
-  maxstrike
-  maxwyrmwind
-  meditate
-  megadrain
-  megakick
-  megapunch
-  megahorn
-  memento
-  menacingmoonrazemaelstrom
-  metalburst
-  metalclaw
-  metalsound
-  meteorassault
-  meteorbeam
-  meteormash
-  metronome
-  milkdrink
-  mimic
-  mindblown
-  mindreader
-  minimize
-  miracleeye
-  mirrorcoat
-  mirrormove
-  mirrorshot
-  mist
-  mistball
-  mistyexplosion
-  mistyterrain
-  moonblast
-  moongeistbeam
-  moonlight
-  morningsun
-  mountaingale
-  mudbomb
-  mudshot
-  mudsport
-  mudslap
-  muddywater
-  multiattack
-  mysticalfire
-  mysticalpower
-  nastyplot
-  naturalgift
-  naturepower
-  naturesmadness
-  needlearm
-  neverendingnightmare
-  nightdaze
-  nightshade
-  nightslash
-  nightmare
-  nobleroar
-  noretreat
-  nuzzle
-  oblivionwing
-  obstruct
-  oceanicoperetta
-  octazooka
-  octolock
-  odorsleuth
-  ominouswind
-  originpulse
-  outrage
-  overdrive
-  overheat
-  painsplit
-  paleowave
-  paraboliccharge
-  partingshot
-  payday
-  payback
-  peck
-  perishsong
-  petalblizzard
-  petaldance
-  phantomforce
-  photongeyser
-  pikapapow
-  pinmissile
-  plasmafists
-  playnice
-  playrough
-  pluck
-  poisonfang
-  poisongas
-  poisonjab
-  poisonpowder
-  poisonsting
-  poisontail
-  pollenpuff
-  poltergeist
-  pound
-  powder
-  powdersnow
-  powergem
-  powershift
-  powersplit
-  powerswap
-  powertrick
-  powertrip
-  powerwhip
-  poweruppunch
-  precipiceblades
-  present
-  prismaticlaser
-  protect
-  psybeam
-  psychup
-  psychic
-  psychicfangs
-  psychicterrain
-  psychoboost
-  psychocut
-  psychoshift
-  psyshieldbash
-  psyshock
-  psystrike
-  psywave
-  pulverizingpancake
-  punishment
-  purify
-  pursuit
-  pyroball
-  quash
-  quickattack
-  quickguard
-  quiverdance
-  rage
-  ragepowder
-  ragingfury
-  raindance
-  rapidspin
-  razorleaf
-  razorshell
-  razorwind
-  recover
-  recycle
-  reflect
-  reflecttype
-  refresh
-  relicsong
-  rest
-  retaliate
-  return
-  revelationdance
-  revenge
-  reversal
-  risingvoltage
-  roar
-  roaroftime
-  rockblast
-  rockclimb
-  rockpolish
-  rockslide
-  rocksmash
-  rockthrow
-  rocktomb
-  rockwrecker
-  roleplay
-  rollingkick
-  rollout
-  roost
-  rototiller
-  round
-  sacredfire
-  sacredsword
-  safeguard
-  sandattack
-  sandtomb
-  sandsearstorm
-  sandstorm
-  sappyseed
-  savagespinout
-  scald
-  scaleshot
-  scaryface
-  scorchingsands
-  scratch
-  screech
-  searingshot
-  searingsunrazesmash
-  secretpower
-  secretsword
-  seedbomb
-  seedflare
-  seismictoss
-  selfdestruct
-  shadowball
-  shadowbone
-  shadowclaw
-  shadowforce
-  shadowpunch
-  shadowsneak
-  shadowstrike
-  sharpen
-  shatteredpsyche
-  sheercold
-  shellsidearm
-  shellsmash
-  shelltrap
-  shelter
-  shiftgear
-  shockwave
-  shoreup
-  signalbeam
-  silverwind
-  simplebeam
-  sing
-  sinisterarrowraid
-  sizzlyslide
-  sketch
-  skillswap
-  skittersmack
-  skullbash
-  skyattack
-  skydrop
-  skyuppercut
-  slackoff
-  slam
-  slash
-  sleeppowder
-  sleeptalk
-  sludge
-  sludgebomb
-  sludgewave
-  smackdown
-  smartstrike
-  smellingsalts
-  smog
-  smokescreen
-  snaptrap
-  snarl
-  snatch
-  snipeshot
-  snore
-  soak
-  softboiled
-  solarbeam
-  solarblade
-  sonicboom
-  soulstealing7starstrike
-  spacialrend
-  spark
-  sparklingaria
-  sparklyswirl
-  spectralthief
-  speedswap
-  spiderweb
-  spikecannon
-  spikes
-  spikyshield
-  spiritbreak
-  spiritshackle
-  spitup
-  spite
-  splash
-  splinteredstormshards
-  splishysplash
-  spore
-  spotlight
-  springtidestorm
-  stealthrock
-  steameruption
-  steamroller
-  steelbeam
-  steelroller
-  steelwing
-  stickyweb
-  stockpile
-  stokedsparksurfer
-  stomp
-  stompingtantrum
-  stoneaxe
-  stoneedge
-  storedpower
-  stormthrow
-  strangesteam
-  strength
-  strengthsap
-  stringshot
-  struggle
-  strugglebug
-  stuffcheeks
-  stunspore
-  submission
-  substitute
-  subzeroslammer
-  suckerpunch
-  sunnyday
-  sunsteelstrike
-  superfang
-  superpower
-  supersonic
-  supersonicskystrike
-  surf
-  surgingstrikes
-  swagger
-  swallow
-  sweetkiss
-  sweetscent
-  swift
-  switcheroo
-  swordsdance
-  synchronoise
-  synthesis
-  tackle
-  tailglow
-  tailslap
-  tailwhip
-  tailwind
-  takedown
-  takeheart
-  tarshot
-  taunt
-  tearfullook
-  teatime
-  technoblast
-  tectonicrage
-  teeterdance
-  telekinesis
-  teleport
-  terrainpulse
-  thief
-  thousandarrows
-  thousandwaves
-  thrash
-  throatchop
-  thunder
-  thundercage
-  thunderfang
-  thunderouskick
-  thunderpunch
-  thundershock
-  thunderwave
-  thunderbolt
-  tickle
-  topsyturvy
-  torment
-  toxic
-  toxicspikes
-  toxicthread
-  transform
-  triattack
-  trick
-  trickroom
-  trickortreat
-  triplearrows
-  tripleaxel
-  triplekick
-  tropkick
-  trumpcard
-  twineedle
-  twinkletackle
-  twister
-  uturn
-  uproar
-  vcreate
-  vacuumwave
-  veeveevolley
-  venomdrench
-  venoshock
-  victorydance
-  vinewhip
-  visegrip
-  vitalthrow
-  voltswitch
-  volttackle
-  wakeupslap
-  watergun
-  waterpledge
-  waterpulse
-  watershuriken
-  watersport
-  waterspout
-  waterfall
-  wavecrash
-  weatherball
-  whirlpool
-  whirlwind
-  wickedblow
-  wideguard
-  wildboltstorm
-  wildcharge
-  willowisp
-  wingattack
-  wish
-  withdraw
-  wonderroom
-  woodhammer
-  workup
-  worryseed
-  wrap
-  wringout
-  xscissor
-  yawn
-  zapcannon
-  zenheadbutt
-  zingzap
-  zippyzap
-}
-
-"The types in Pokémon"
-enum TypesEnum {
-  bug
-  dark
-  dragon
-  electric
-  fairy
-  fighting
-  fire
-  flying
-  ghost
-  grass
-  ground
-  ice
-  normal
-  poison
-  psychic
-  rock
-  steel
-  water
-}
+  watchdog
+  lillipup
+  herdier
+  stoutland
+  purrloin
+  liepard
+  pansage
+  simisage
+  pansear
+  simisear
+  panpour
+  simipour
+  munna
+  musharna
+  pidove
+  tranquill
+  unfezant
+  blitzle
+  zebstrika
+  roggenrola
+  boldore
+  gigalith
+  woobat
+  swoobat
+  drilbur
+  excadrill
+  audino
+  audinomega
+  timburr
+  gurdurr
+  conkeldurr
+  tympole
+  palpitoad
+  seismitoad
+  throh
+  sawk
+  sewaddle
+  swadloon
+  leavanny
+  venipede
+  whirlipede
+  scolipede
+  cottonee
+  whimsicott
+  petilil
+  lilligant
+  lilliganthisui
+  basculin
+  basculinbluestriped
+  basculinwhitestriped
+  sandile
+  krokorok
+  krookodile
+  darumaka
+  darumakagalar
+  darmanitan
+  darmanitangalar
+  darmanitanzen
+  darmanitangalarzen
+  maractus
+  dwebble
+  crustle
+  scraggy
+  scrafty
+  sigilyph
+  yamask
+  yamaskgalar
+  cofagrigus
+  tirtouga
+  carracosta
+  archen
+  archeops
+  trubbish
+  garbodor
+  garbodorgmax
+  zorua
+  zoruahisui
+  zoroark
+  zoroarkhisui
+  minccino
+  cinccino
+  gothita
+  gothorita
+  gothitelle
+  solosis
+  duosion
+  reuniclus
+  ducklett
+  swanna
+  vanillite
+  vanillish
+  vanilluxe
+  deerling
+  sawsbuck
+  emolga
+  karrablast
+  escavalier
+  foongus
+  amoonguss
+  frillish
+  frillishfemale
+  jellicent
+  jellicentfemale
+  alomomola
+  joltik
+  galvantula
+  ferroseed
+  ferrothorn
+  klink
+  klang
+  klinklang
+  tynamo
+  eelektrik
+  eelektross
+  elgyem
+  beheeyem
+  litwick
+  lampent
+  chandelure
+  axew
+  fraxure
+  haxorus
+  cubchoo
+  beartic
+  cryogonal
+  shelmet
+  accelgor
+  stunfisk
+  stunfiskgalar
+  mienfoo
+  mienshao
+  druddigon
+  golett
+  golurk
+  pawniard
+  bisharp
+  bouffalant
+  rufflet
+  braviary
+  braviaryhisui
+  vullaby
+  mandibuzz
+  heatmor
+  durant
+  deino
+  zweilous
+  hydreigon
+  larvesta
+  volcarona
+  cobalion
+  terrakion
+  virizion
+  tornadus
+  tornadustherian
+  thundurus
+  thundurustherian
+  reshiram
+  zekrom
+  landorus
+  landorustherian
+  kyurem
+  kyuremblack
+  kyuremwhite
+  keldeo
+  keldeoresolute
+  meloetta
+  meloettapirouette
+  genesect
+  genesectdouse
+  genesectshock
+  genesectburn
+  genesectchill
+  chespin
+  quilladin
+  chesnaught
+  fennekin
+  braixen
+  delphox
+  froakie
+  frogadier
+  greninja
+  greninjaash
+  bunnelby
+  diggersby
+  fletchling
+  fletchinder
+  talonflame
+  scatterbug
+  spewpa
+  vivillon
+  vivillonfancy
+  vivillonpokeball
+  litleo
+  pyroar
+  flabebe
+  floette
+  floetteeternal
+  florges
+  skiddo
+  gogoat
+  pancham
+  pangoro
+  furfrou
+  espurr
+  meowstic
+  meowsticf
+  honedge
+  doublade
+  aegislash
+  aegislashblade
+  spritzee
+  aromatisse
+  swirlix
+  slurpuff
+  inkay
+  malamar
+  binacle
+  barbaracle
+  skrelp
+  dragalge
+  clauncher
+  clawitzer
+  helioptile
+  heliolisk
+  tyrunt
+  tyrantrum
+  amaura
+  aurorus
+  sylveon
+  hawlucha
+  dedenne
+  carbink
+  goomy
+  sliggoo
+  sliggoohisui
+  goodra
+  goodrahisui
+  klefki
+  phantump
+  trevenant
+  pumpkaboo
+  pumpkaboosmall
+  pumpkaboolarge
+  pumpkaboosuper
+  gourgeist
+  gourgeistsmall
+  gourgeistlarge
+  gourgeistsuper
+  bergmite
+  avalugg
+  avalugghisui
+  noibat
+  noivern
+  xerneas
+  xerneasneutral
+  yveltal
+  zygarde
+  zygarde10
+  zygardecomplete
+  diancie
+  dianciemega
+  hoopa
+  hoopaunbound
+  volcanion
+  rowlet
+  dartrix
+  decidueye
+  decidueyehisui
+  litten
+  torracat
+  incineroar
+  popplio
+  brionne
+  primarina
+  pikipek
+  trumbeak
+  toucannon
+  yungoos
+  gumshoos
+  gumshoostotem
+  grubbin
+  charjabug
+  vikavolt
+  vikavolttotem
+  crabrawler
+  crabominable
+  oricorio
+  oricoriopompom
+  oricoriopau
+  oricoriosensu
+  cutiefly
+  ribombee
+  ribombeetotem
+  rockruff
+  lycanroc
+  lycanrocmidnight
+  lycanrocdusk
+  wishiwashi
+  wishiwashischool
+  mareanie
+  toxapex
+  mudbray
+  mudsdale
+  dewpider
+  araquanid
+  araquanidtotem
+  fomantis
+  lurantis
+  lurantistotem
+  morelull
+  shiinotic
+  salandit
+  salazzle
+  salazzletotem
+  stufful
+  bewear
+  bounsweet
+  steenee
+  tsareena
+  comfey
+  oranguru
+  passimian
+  wimpod
+  golisopod
+  sandygast
+  palossand
+  pyukumuku
+  typenull
+  silvally
+  silvallybug
+  silvallydark
+  silvallydragon
+  silvallyelectric
+  silvallyfairy
+  silvallyfighting
+  silvallyfire
+  silvallyflying
+  silvallyghost
+  silvallygrass
+  silvallyground
+  silvallyice
+  silvallypoison
+  silvallypsychic
+  silvallyrock
+  silvallysteel
+  silvallywater
+  minior
+  miniormeteor
+  komala
+  turtonator
+  togedemaru
+  togedemarutotem
+  mimikyu
+  mimikyubusted
+  mimikyutotem
+  mimikyubustedtotem
+  bruxish
+  drampa
+  dhelmise
+  jangmoo
+  hakamoo
+  kommoo
+  kommoototem
+  tapukoko
+  tapulele
+  tapubulu
+  tapufini
+  cosmog
+  cosmoem
+  solgaleo
+  lunala
+  nihilego
+  buzzwole
+  pheromosa
+  xurkitree
+  celesteela
+  kartana
+  guzzlord
+  necrozma
+  necrozmaduskmane
+  necrozmadawnwings
+  necrozmaultra
+  magearna
+  magearnaoriginal
+  marshadow
+  poipole
+  naganadel
+  stakataka
+  blacephalon
+  zeraora
+  meltan
+  melmetal
+  melmetalgmax
+  grookey
+  thwackey
+  rillaboom
+  rillaboomgmax
+  scorbunny
+  raboot
+  cinderace
+  cinderacegmax
+  sobble
+  drizzile
+  inteleon
+  inteleongmax
+  skwovet
+  greedent
+  rookidee
+  corvisquire
+  corviknight
+  corviknightgmax
+  blipbug
+  dottler
+  orbeetle
+  orbeetlegmax
+  nickit
+  thievul
+  gossifleur
+  eldegoss
+  wooloo
+  dubwool
+  chewtle
+  drednaw
+  drednawgmax
+  yamper
+  boltund
+  rolycoly
+  carkol
+  coalossal
+  coalossalgmax
+  applin
+  flapple
+  flapplegmax
+  appletun
+  appletungmax
+  silicobra
+  sandaconda
+  sandacondagmax
+  cramorant
+  cramorantgulping
+  cramorantgorging
+  arrokuda
+  barraskewda
+  toxel
+  toxtricity
+  toxtricitylowkey
+  toxtricitygmax
+  toxtricitylowkeygmax
+  sizzlipede
+  centiskorch
+  centiskorchgmax
+  clobbopus
+  grapploct
+  sinistea
+  sinisteaantique
+  polteageist
+  polteageistantique
+  hatenna
+  hattrem
+  hatterene
+  hatterenegmax
+  impidimp
+  morgrem
+  grimmsnarl
+  grimmsnarlgmax
+  obstagoon
+  perrserker
+  cursola
+  sirfetchd
+  mrrime
+  runerigus
+  milcery
+  alcremie
+  alcremiegmax
+  falinks
+  pincurchin
+  snom
+  frosmoth
+  stonjourner
+  eiscue
+  eiscuenoice
+  indeedee
+  indeedeef
+  morpeko
+  morpekohangry
+  cufant
+  copperajah
+  copperajahgmax
+  dracozolt
+  arctozolt
+  dracovish
+  arctovish
+  duraludon
+  duraludongmax
+  dreepy
+  drakloak
+  dragapult
+  zacian
+  zaciancrowned
+  zamazenta
+  zamazentacrowned
+  eternatus
+  eternatuseternamax
+  kubfu
+  urshifu
+  urshifurapidstrike
+  urshifugmax
+  urshifurapidstrikegmax
+  zarude
+  zarudedada
+  regieleki
+  regidrago
+  glastrier
+  spectrier
+  calyrex
+  calyrexice
+  calyrexshadow
+  wyrdeer
+  kleavor
+  ursaluna
+  basculegion
+  basculegionf
+  sneasler
+  overqwil
+  enamorus
+  enamorustherian
+  pokestarsmeargle
+  pokestarufo
+  pokestarufo2
+  pokestarbrycenman
+  pokestarmt
+  pokestarmt2
+  pokestartransport
+  pokestargiant
+  pokestarhumanoid
+  pokestarmonster
+  pokestarf00
+  pokestarf002
+  pokestarspirit
+  pokestarblackdoor
+  pokestarwhitedoor
+  pokestarblackbelt
+  pokestarufopropu2
+}
+
+"The supported items"
+enum ItemsEnum {
+  abomasite
+  absolite
+  absorbbulb
+  adamantorb
+  adrenalineorb
+  aerodactylite
+  aggronite
+  aguavberry
+  airballoon
+  alakazite
+  aloraichiumz
+  altarianite
+  ampharosite
+  apicotberry
+  armorfossil
+  aspearberry
+  assaultvest
+  audinite
+  babiriberry
+  banettite
+  beastball
+  beedrillite
+  belueberry
+  berry
+  berryjuice
+  berrysweet
+  berserkgene
+  bigroot
+  bindingband
+  bitterberry
+  blackbelt
+  blackglasses
+  blacksludge
+  blastoisinite
+  blazikenite
+  blueorb
+  blukberry
+  blunderpolicy
+  bottlecap
+  brightpowder
+  buggem
+  bugmemory
+  buginiumz
+  burndrive
+  burntberry
+  cameruptite
+  cellbattery
+  charcoal
+  charizarditex
+  charizarditey
+  chartiberry
+  cheriberry
+  cherishball
+  chestoberry
+  chilanberry
+  chilldrive
+  chippedpot
+  choiceband
+  choicescarf
+  choicespecs
+  chopleberry
+  clawfossil
+  cloversweet
+  cobaberry
+  colburberry
+  cornnberry
+  coverfossil
+  crucibellite
+  crackedpot
+  custapberry
+  damprock
+  darkgem
+  darkmemory
+  darkiniumz
+  dawnstone
+  decidiumz
+  deepseascale
+  deepseatooth
+  destinyknot
+  diancite
+  diveball
+  domefossil
+  dousedrive
+  dracoplate
+  dragonfang
+  dragongem
+  dragonmemory
+  dragonscale
+  dragoniumz
+  dreadplate
+  dreamball
+  dubiousdisc
+  durinberry
+  duskball
+  duskstone
+  earthplate
+  eeviumz
+  ejectbutton
+  ejectpack
+  electirizer
+  electricgem
+  electricmemory
+  electricseed
+  electriumz
+  energypowder
+  enigmaberry
+  eviolite
+  expertbelt
+  fairiumz
+  fairygem
+  fairymemory
+  fastball
+  fightinggem
+  fightingmemory
+  fightiniumz
+  figyberry
+  firegem
+  firememory
+  firestone
+  firiumz
+  fistplate
+  flameorb
+  flameplate
+  floatstone
+  flowersweet
+  flyinggem
+  flyingmemory
+  flyiniumz
+  focusband
+  focussash
+  fossilizedbird
+  fossilizeddino
+  fossilizeddrake
+  fossilizedfish
+  friendball
+  fullincense
+  fullrestore
+  galaricacuff
+  galaricawreath
+  galladite
+  ganlonberry
+  garchompite
+  gardevoirite
+  gengarite
+  ghostgem
+  ghostmemory
+  ghostiumz
+  glalitite
+  goldberry
+  goldbottlecap
+  grassgem
+  grassmemory
+  grassiumz
+  grassyseed
+  greatball
+  grepaberry
+  gripclaw
+  griseousorb
+  groundgem
+  groundmemory
+  groundiumz
+  gyaradosite
+  habanberry
+  hardstone
+  healball
+  heatrock
+  heavyball
+  heavydutyboots
+  helixfossil
+  heracronite
+  hondewberry
+  houndoominite
+  hyperpotion
+  iapapaberry
+  iceberry
+  icegem
+  icememory
+  icestone
+  icicleplate
+  iciumz
+  icyrock
+  inciniumz
+  insectplate
+  ironball
+  ironplate
+  jabocaberry
+  jawfossil
+  kangaskhanite
+  kasibberry
+  kebiaberry
+  keeberry
+  kelpsyberry
+  kingsrock
+  kommoniumz
+  laggingtail
+  lansatberry
+  latiasite
+  latiosite
+  laxincense
+  leafstone
+  leek
+  leftovers
+  leppaberry
+  levelball
+  liechiberry
+  lifeorb
+  lightball
+  lightclay
+  lopunnite
+  loveball
+  lovesweet
+  lucarionite
+  luckypunch
+  lumberry
+  luminousmoss
+  lunaliumz
+  lureball
+  lustrousorb
+  luxuryball
+  lycaniumz
+  machobrace
+  magmarizer
+  magnet
+  magoberry
+  magostberry
+  mail
+  manectite
+  marangaberry
+  marshadiumz
+  masterball
+  mawilite
+  maxpotion
+  meadowplate
+  medichamite
+  mentalherb
+  metagrossite
+  metalcoat
+  metalpowder
+  metronome
+  mewniumz
+  mewtwonitex
+  mewtwonitey
+  micleberry
+  mimikiumz
+  mindplate
+  mintberry
+  miracleberry
+  miracleseed
+  mistyseed
+  moonball
+  moonstone
+  muscleband
+  mysteryberry
+  mysticwater
+  nanabberry
+  nestball
+  netball
+  nevermeltice
+  nomelberry
+  normalgem
+  normaliumz
+  occaberry
+  oddincense
+  oldamber
+  oranberry
+  ovalstone
+  przcureberry
+  psncureberry
+  pamtreberry
+  parkball
+  passhoberry
+  payapaberry
+  pechaberry
+  persimberry
+  petayaberry
+  pidgeotite
+  pikaniumz
+  pikashuniumz
+  pinapberry
+  pinkbow
+  pinsirite
+  pixieplate
+  plumefossil
+  poisonbarb
+  poisongem
+  poisonmemory
+  poisoniumz
+  pokeball
+  polkadotbow
+  pomegberry
+  poweranklet
+  powerband
+  potion
+  powerbelt
+  powerbracer
+  powerherb
+  powerlens
+  powerweight
+  premierball
+  primariumz
+  prismscale
+  protectivepads
+  protector
+  psychicgem
+  psychicmemory
+  psychicseed
+  psychiumz
+  qualotberry
+  quickball
+  quickclaw
+  quickpowder
+  rabutaberry
+  rarebone
+  rawstberry
+  razorclaw
+  razorfang
+  razzberry
+  reapercloth
+  redcard
+  redorb
+  repeatball
+  ribbonsweet
+  rindoberry
+  ringtarget
+  rockgem
+  rockincense
+  rockmemory
+  rockiumz
+  roseincense
+  rockyhelmet
+  roomservice
+  rootfossil
+  roseliberry
+  rowapberry
+  rustedshield
+  rustedsword
+  sablenite
+  sachet
+  safariball
+  safetygoggles
+  sailfossil
+  salacberry
+  salamencite
+  sceptilite
+  scizorite
+  scopelens
+  seaincense
+  sharpbeak
+  sharpedonite
+  shedshell
+  shellbell
+  shinystone
+  shockdrive
+  shucaberry
+  silkscarf
+  silverpowder
+  sitrusberry
+  skullfossil
+  skyplate
+  slowbronite
+  smoothrock
+  snorliumz
+  snowball
+  softsand
+  solganiumz
+  souldew
+  spelltag
+  spelonberry
+  splashplate
+  spookyplate
+  sportball
+  starfberry
+  steelgem
+  steelmemory
+  steeliumz
+  starsweet
+  steelixite
+  stick
+  stickybarb
+  stoneplate
+  strawberrysweet
+  sunstone
+  superpotion
+  swampertite
+  sweetapple
+  tamatoberry
+  tangaberry
+  tapuniumz
+  tartapple
+  terrainextender
+  thickclub
+  throatspray
+  thunderstone
+  timerball
+  toxicorb
+  toxicplate
+  twistedspoon
+  tyranitarite
+  ultraball
+  ultranecroziumz
+  upgrade
+  utilityumbrella
+  venusaurite
+  vilevial
+  wacanberry
+  watergem
+  watermemory
+  waterstone
+  wateriumz
+  watmelberry
+  waveincense
+  weaknesspolicy
+  wepearberry
+  whippeddream
+  whiteherb
+  widelens
+  wikiberry
+  wiseglasses
+  yacheberry
+  zapplate
+  zoomlens
+  acrobike
+  adventureguide
+  apricornbox
+  aquasuit
+  auroraticket
+  autograph
+  azureflute
+  bandautograph
+  basementkey
+  berrypots
+  berrypouch
+  bicycle
+  bikevoucher
+  bluecard
+  bluepetal
+  campinggear
+  cardkey
+  catchingcharm
+  clearbell
+  coincase
+  colressmchn
+  contestcostume
+  contestpass
+  coupon1
+  coupon2
+  coupon3
+  dnasplicers
+  darkstone
+  devongoods
+  devonparts
+  devonscope
+  devonscubagear
+  dowsingmchn
+  dowsingmachine
+  dragonskull
+  droppeditem
+  dynamaxband
+  eggcard
+  elevatorkey
+  endorsement
+  enigmastone
+  enigmaticcard
+  eonflute
+  eonticket
+  escaperope
+  expshare
+  explorerkit
+  famechecker
+  fashioncase
+  fishingrod
+  foragebag
+  gbsounds
+  gsball
+  galactickey
+  gogoggles
+  godstone
+  goldteeth
+  goodrod
+  gracidea
+  gram1
+  gram2
+  gram3
+  greenpetal
+  grubbyhanky
+  hitechearbuds
+  holocaster
+  honorofkalos
+  ilimasnormaliumz
+  intriguingstone
+  itemfinder
+  jadeorb
+  journal
+  keystone
+  keytoroom1
+  keytoroom2
+  keytoroom4
+  keytoroom6
+  leftpokeball
+  legendplate
+  lenscase
+  letter
+  libertypass
+  liftkey
+  lightstone
+  lockcapsule
+  lookerticket
+  lootsack
+  lostitem
+  lunarwing
+  machbike
+  machinepart
+  magmaemblem
+  magmastone
+  magmasuit
+  makeupbag
+  medalbox
+  megabracelet
+  megaring
+  membercard
+  meteorite
+  meteoriteshard
+  moonflute
+  mysteryegg
+  mysticticket
+  nlunarizer
+  nsolarizer
+  oaksletter
+  oaksparcel
+  oldcharm
+  oldletter
+  oldrod
+  oldseamap
+  orangepetal
+  ovalcharm
+  pairoftickets
+  palpad
+  parcel
+  pass
+  permit
+  photoalbum
+  pinkpetal
+  plasmacard
+  poffincase
+  pointcard
+  pokeradar
+  pokeblockkit
+  pokeblockcase
+  pokeflute
+  pokemonboxlink
+  powderjar
+  powerplantpass
+  prisonbottle
+  profsletter
+  professorsmask
+  propcase
+  purplepetal
+  ragecandybar
+  rainbowflower
+  rainbowpass
+  rainbowwing
+  redchain
+  redpetal
+  redscale
+  revealglass
+  ridepager
+  rm1key
+  rm2key
+  rm4key
+  rm6key
+  rollerskates
+  rotombike
+  rotomcatalog
+  ruby
+  rulebook
+  ssticket
+  sapphire
+  scanner
+  sealbag
+  sealcase
+  secretkey
+  secretpotion
+  shinycharm
+  silphscope
+  silverwing
+  slowpoketail
+  soniasbook
+  sootsack
+  sparklingstone
+  sprayduck
+  sprinklotad
+  squirtbottle
+  storagekey
+  suitekey
+  sunflute
+  superrod
+  surgebadge
+  tmcase
+  tmvpass
+  tea
+  teachytv
+  tidalbell
+  townmap
+  traveltrunk
+  tripass
+  unownreport
+  vsrecorder
+  vsseeker
+  wailmerpail
+  wishingstar
+  workskey
+  xtransceiver
+  yellowpetal
+  zpowering
+  zring
+  zygardecube
+}
+
+"The supported moves"
+enum MovesEnum {
+  tenmillionvoltthunderbolt
+  absorb
+  accelerock
+  acid
+  acidarmor
+  aciddownpour
+  acidspray
+  acrobatics
+  acupressure
+  aerialace
+  aeroblast
+  afteryou
+  agility
+  aircutter
+  airslash
+  alloutpummeling
+  allyswitch
+  amnesia
+  anchorshot
+  ancientpower
+  appleacid
+  aquajet
+  aquaring
+  aquatail
+  armthrust
+  aromatherapy
+  aromaticmist
+  assist
+  assurance
+  astralbarrage
+  astonish
+  attackorder
+  attract
+  aurasphere
+  aurawheel
+  aurorabeam
+  auroraveil
+  autotomize
+  avalanche
+  babydolleyes
+  baddybad
+  banefulbunker
+  barbbarrage
+  barrage
+  barrier
+  batonpass
+  beakblast
+  beatup
+  belch
+  behemothbash
+  behemothblade
+  bellydrum
+  bestow
+  bide
+  bind
+  bite
+  bittermalice
+  blackholeeclipse
+  blastburn
+  blazekick
+  bleakwindstorm
+  blizzard
+  block
+  bloomdoom
+  blueflare
+  bodypress
+  bodyslam
+  boltbeak
+  boltstrike
+  boneclub
+  bonerush
+  bonemerang
+  boomburst
+  bounce
+  bouncybubble
+  bravebird
+  branchpoke
+  breakingswipe
+  breakneckblitz
+  brickbreak
+  brine
+  brutalswing
+  bubble
+  bubblebeam
+  bugbite
+  bugbuzz
+  bulkup
+  bulldoze
+  bulletpunch
+  bulletseed
+  burningjealousy
+  burnup
+  buzzybuzz
+  calmmind
+  camouflage
+  captivate
+  catastropika
+  ceaselessedge
+  celebrate
+  charge
+  chargebeam
+  charm
+  chatter
+  chipaway
+  chloroblast
+  circlethrow
+  clamp
+  clangingscales
+  clangoroussoul
+  clangoroussoulblaze
+  clearsmog
+  closecombat
+  coaching
+  coil
+  cometpunch
+  confide
+  confuseray
+  confusion
+  constrict
+  continentalcrush
+  conversion
+  conversion2
+  copycat
+  coreenforcer
+  corkscrewcrash
+  corrosivegas
+  cosmicpower
+  cottonguard
+  cottonspore
+  counter
+  courtchange
+  covet
+  crabhammer
+  craftyshield
+  crosschop
+  crosspoison
+  crunch
+  crushclaw
+  crushgrip
+  curse
+  cut
+  darkpulse
+  darkvoid
+  darkestlariat
+  dazzlinggleam
+  decorate
+  defendorder
+  defensecurl
+  defog
+  destinybond
+  detect
+  devastatingdrake
+  diamondstorm
+  dig
+  direclaw
+  disable
+  disarmingvoice
+  discharge
+  dive
+  dizzypunch
+  doomdesire
+  doublehit
+  doubleironbash
+  doublekick
+  doubleslap
+  doubleteam
+  doubleedge
+  dracometeor
+  dragonascent
+  dragonbreath
+  dragonclaw
+  dragondance
+  dragondarts
+  dragonenergy
+  dragonhammer
+  dragonpulse
+  dragonrage
+  dragonrush
+  dragontail
+  drainpunch
+  drainingkiss
+  dreameater
+  drillpeck
+  drillrun
+  drumbeating
+  dualchop
+  dynamicpunch
+  dualwingbeat
+  dynamaxcannon
+  earthpower
+  earthquake
+  echoedvoice
+  eerieimpulse
+  eeriespell
+  eggbomb
+  electricterrain
+  electrify
+  electroball
+  electroweb
+  embargo
+  ember
+  encore
+  endeavor
+  endure
+  energyball
+  entrainment
+  eruption
+  esperwing
+  eternabeam
+  expandingforce
+  explosion
+  extrasensory
+  extremeevoboost
+  extremespeed
+  facade
+  fairylock
+  fairywind
+  fakeout
+  faketears
+  falsesurrender
+  falseswipe
+  featherdance
+  feint
+  feintattack
+  fellstinger
+  fierydance
+  fierywrath
+  finalgambit
+  fireblast
+  firefang
+  firelash
+  firepledge
+  firepunch
+  firespin
+  firstimpression
+  fishiousrend
+  fissure
+  flail
+  flameburst
+  flamecharge
+  flamewheel
+  flamethrower
+  flareblitz
+  flash
+  flashcannon
+  flatter
+  fleurcannon
+  fling
+  flipturn
+  floatyfall
+  floralhealing
+  flowershield
+  fly
+  flyingpress
+  focusblast
+  focusenergy
+  focuspunch
+  followme
+  forcepalm
+  foresight
+  forestscurse
+  foulplay
+  freezeshock
+  freezedry
+  freezingglare
+  freezyfrost
+  frenzyplant
+  frostbreath
+  frustration
+  furyattack
+  furycutter
+  furyswipes
+  fusionbolt
+  fusionflare
+  futuresight
+  gastroacid
+  geargrind
+  gearup
+  genesissupernova
+  geomancy
+  gigadrain
+  gigaimpact
+  gigavolthavoc
+  glaciallance
+  glaciate
+  glare
+  glitzyglow
+  gmaxbefuddle
+  gmaxcannonade
+  gmaxcentiferno
+  gmaxchistrike
+  gmaxcuddle
+  gmaxdepletion
+  gmaxdrumsolo
+  gmaxfinale
+  gmaxtartness
+  gmaxvinelash
+  gmaxvolcalith
+  gmaxvoltcrash
+  gmaxwildfire
+  gmaxwindrage
+  gmaxfireball
+  gmaxfoamburst
+  gmaxgoldrush
+  gmaxgravitas
+  gmaxhydrosnipe
+  gmaxmalodor
+  gmaxmeltdown
+  gmaxstonesurge
+  gmaxstunshock
+  gmaxsweetness
+  gmaxterror
+  gmaxoneblow
+  gmaxrapidflow
+  gmaxreplenish
+  gmaxresonance
+  gmaxsandblast
+  gmaxsmite
+  gmaxsnooze
+  gmaxsteelsurge
+  grassknot
+  grasspledge
+  grasswhistle
+  grassyglide
+  grassyterrain
+  gravapple
+  gravity
+  growl
+  growth
+  grudge
+  guardsplit
+  guardswap
+  guardianofalola
+  guillotine
+  gunkshot
+  gust
+  gyroball
+  hail
+  hammerarm
+  happyhour
+  harden
+  haze
+  headcharge
+  headsmash
+  headbutt
+  headlongrush
+  healbell
+  healblock
+  healorder
+  healpulse
+  healingwish
+  heartstamp
+  heartswap
+  heatcrash
+  heatwave
+  heavyslam
+  helpinghand
+  hex
+  hiddenpower
+  hiddenpowerbug
+  hiddenpowerdark
+  hiddenpowerdragon
+  hiddenpowerelectric
+  hiddenpowerfighting
+  hiddenpowerfire
+  hiddenpowerflying
+  hiddenpowerghost
+  hiddenpowergrass
+  hiddenpowerground
+  hiddenpowerice
+  hiddenpowerpoison
+  hiddenpowerpsychic
+  hiddenpowerrock
+  hiddenpowersteel
+  hiddenpowerwater
+  highhorsepower
+  highjumpkick
+  holdback
+  holdhands
+  honeclaws
+  hornattack
+  horndrill
+  hornleech
+  howl
+  hurricane
+  hydrocannon
+  hydropump
+  hydrovortex
+  hyperbeam
+  hyperfang
+  hypervoice
+  hyperspacefury
+  hyperspacehole
+  hypnosis
+  iceball
+  icebeam
+  iceburn
+  icefang
+  icehammer
+  icepunch
+  iceshard
+  iciclecrash
+  iciclespear
+  icywind
+  imprison
+  incinerate
+  infernalparade
+  inferno
+  infernooverdrive
+  infestation
+  ingrain
+  instruct
+  iondeluge
+  irondefense
+  ironhead
+  irontail
+  jawlock
+  judgment
+  jumpkick
+  junglehealing
+  karatechop
+  kinesis
+  kingsshield
+  knockoff
+  landswrath
+  laserfocus
+  lashout
+  lastresort
+  lavaplume
+  leafblade
+  leafstorm
+  leaftornado
+  leafage
+  leechlife
+  leechseed
+  leer
+  letssnuggleforever
+  lick
+  lightscreen
+  lightthatburnsthesky
+  lifedew
+  lightofruin
+  liquidation
+  lockon
+  lovelykiss
+  lowkick
+  lowsweep
+  luckychant
+  lunarblessing
+  lunardance
+  lunge
+  lusterpurge
+  machpunch
+  magiccoat
+  magicpowder
+  magicroom
+  magicalleaf
+  magikarpsrevenge
+  magmastorm
+  magnetbomb
+  magnetrise
+  magneticflux
+  magnitude
+  maliciousmoonsault
+  matblock
+  mefirst
+  maxairstream
+  maxdarkness
+  maxflare
+  maxflutterby
+  maxgeyser
+  maxguard
+  meanlook
+  maxhailstorm
+  maxknuckle
+  maxlightning
+  maxmindstorm
+  maxooze
+  maxovergrowth
+  maxphantasm
+  maxquake
+  maxrockfall
+  maxstarfall
+  maxsteelspike
+  maxstrike
+  maxwyrmwind
+  meditate
+  megadrain
+  megakick
+  megapunch
+  megahorn
+  memento
+  menacingmoonrazemaelstrom
+  metalburst
+  metalclaw
+  metalsound
+  meteorassault
+  meteorbeam
+  meteormash
+  metronome
+  milkdrink
+  mimic
+  mindblown
+  mindreader
+  minimize
+  miracleeye
+  mirrorcoat
+  mirrormove
+  mirrorshot
+  mist
+  mistball
+  mistyexplosion
+  mistyterrain
+  moonblast
+  moongeistbeam
+  moonlight
+  morningsun
+  mountaingale
+  mudbomb
+  mudshot
+  mudsport
+  mudslap
+  muddywater
+  multiattack
+  mysticalfire
+  mysticalpower
+  nastyplot
+  naturalgift
+  naturepower
+  naturesmadness
+  needlearm
+  neverendingnightmare
+  nightdaze
+  nightshade
+  nightslash
+  nightmare
+  nobleroar
+  noretreat
+  nuzzle
+  oblivionwing
+  obstruct
+  oceanicoperetta
+  octazooka
+  octolock
+  odorsleuth
+  ominouswind
+  originpulse
+  outrage
+  overdrive
+  overheat
+  painsplit
+  paleowave
+  paraboliccharge
+  partingshot
+  payday
+  payback
+  peck
+  perishsong
+  petalblizzard
+  petaldance
+  phantomforce
+  photongeyser
+  pikapapow
+  pinmissile
+  plasmafists
+  playnice
+  playrough
+  pluck
+  poisonfang
+  poisongas
+  poisonjab
+  poisonpowder
+  poisonsting
+  poisontail
+  pollenpuff
+  poltergeist
+  pound
+  powder
+  powdersnow
+  powergem
+  powershift
+  powersplit
+  powerswap
+  powertrick
+  powertrip
+  powerwhip
+  poweruppunch
+  precipiceblades
+  present
+  prismaticlaser
+  protect
+  psybeam
+  psychup
+  psychic
+  psychicfangs
+  psychicterrain
+  psychoboost
+  psychocut
+  psychoshift
+  psyshieldbash
+  psyshock
+  psystrike
+  psywave
+  pulverizingpancake
+  punishment
+  purify
+  pursuit
+  pyroball
+  quash
+  quickattack
+  quickguard
+  quiverdance
+  rage
+  ragepowder
+  ragingfury
+  raindance
+  rapidspin
+  razorleaf
+  razorshell
+  razorwind
+  recover
+  recycle
+  reflect
+  reflecttype
+  refresh
+  relicsong
+  rest
+  retaliate
+  return
+  revelationdance
+  revenge
+  reversal
+  risingvoltage
+  roar
+  roaroftime
+  rockblast
+  rockclimb
+  rockpolish
+  rockslide
+  rocksmash
+  rockthrow
+  rocktomb
+  rockwrecker
+  roleplay
+  rollingkick
+  rollout
+  roost
+  rototiller
+  round
+  sacredfire
+  sacredsword
+  safeguard
+  sandattack
+  sandtomb
+  sandsearstorm
+  sandstorm
+  sappyseed
+  savagespinout
+  scald
+  scaleshot
+  scaryface
+  scorchingsands
+  scratch
+  screech
+  searingshot
+  searingsunrazesmash
+  secretpower
+  secretsword
+  seedbomb
+  seedflare
+  seismictoss
+  selfdestruct
+  shadowball
+  shadowbone
+  shadowclaw
+  shadowforce
+  shadowpunch
+  shadowsneak
+  shadowstrike
+  sharpen
+  shatteredpsyche
+  sheercold
+  shellsidearm
+  shellsmash
+  shelltrap
+  shelter
+  shiftgear
+  shockwave
+  shoreup
+  signalbeam
+  silverwind
+  simplebeam
+  sing
+  sinisterarrowraid
+  sizzlyslide
+  sketch
+  skillswap
+  skittersmack
+  skullbash
+  skyattack
+  skydrop
+  skyuppercut
+  slackoff
+  slam
+  slash
+  sleeppowder
+  sleeptalk
+  sludge
+  sludgebomb
+  sludgewave
+  smackdown
+  smartstrike
+  smellingsalts
+  smog
+  smokescreen
+  snaptrap
+  snarl
+  snatch
+  snipeshot
+  snore
+  soak
+  softboiled
+  solarbeam
+  solarblade
+  sonicboom
+  soulstealing7starstrike
+  spacialrend
+  spark
+  sparklingaria
+  sparklyswirl
+  spectralthief
+  speedswap
+  spiderweb
+  spikecannon
+  spikes
+  spikyshield
+  spiritbreak
+  spiritshackle
+  spitup
+  spite
+  splash
+  splinteredstormshards
+  splishysplash
+  spore
+  spotlight
+  springtidestorm
+  stealthrock
+  steameruption
+  steamroller
+  steelbeam
+  steelroller
+  steelwing
+  stickyweb
+  stockpile
+  stokedsparksurfer
+  stomp
+  stompingtantrum
+  stoneaxe
+  stoneedge
+  storedpower
+  stormthrow
+  strangesteam
+  strength
+  strengthsap
+  stringshot
+  struggle
+  strugglebug
+  stuffcheeks
+  stunspore
+  submission
+  substitute
+  subzeroslammer
+  suckerpunch
+  sunnyday
+  sunsteelstrike
+  superfang
+  superpower
+  supersonic
+  supersonicskystrike
+  surf
+  surgingstrikes
+  swagger
+  swallow
+  sweetkiss
+  sweetscent
+  swift
+  switcheroo
+  swordsdance
+  synchronoise
+  synthesis
+  tackle
+  tailglow
+  tailslap
+  tailwhip
+  tailwind
+  takedown
+  takeheart
+  tarshot
+  taunt
+  tearfullook
+  teatime
+  technoblast
+  tectonicrage
+  teeterdance
+  telekinesis
+  teleport
+  terrainpulse
+  thief
+  thousandarrows
+  thousandwaves
+  thrash
+  throatchop
+  thunder
+  thundercage
+  thunderfang
+  thunderouskick
+  thunderpunch
+  thundershock
+  thunderwave
+  thunderbolt
+  tickle
+  topsyturvy
+  torment
+  toxic
+  toxicspikes
+  toxicthread
+  transform
+  triattack
+  trick
+  trickroom
+  trickortreat
+  triplearrows
+  tripleaxel
+  triplekick
+  tropkick
+  trumpcard
+  twineedle
+  twinkletackle
+  twister
+  uturn
+  uproar
+  vcreate
+  vacuumwave
+  veeveevolley
+  venomdrench
+  venoshock
+  victorydance
+  vinewhip
+  visegrip
+  vitalthrow
+  voltswitch
+  volttackle
+  wakeupslap
+  watergun
+  waterpledge
+  waterpulse
+  watershuriken
+  watersport
+  waterspout
+  waterfall
+  wavecrash
+  weatherball
+  whirlpool
+  whirlwind
+  wickedblow
+  wideguard
+  wildboltstorm
+  wildcharge
+  willowisp
+  wingattack
+  wish
+  withdraw
+  wonderroom
+  woodhammer
+  workup
+  worryseed
+  wrap
+  wringout
+  xscissor
+  yawn
+  zapcannon
+  zenheadbutt
+  zingzap
+  zippyzap
+}
+
+"The types in Pokémon"
+enum TypesEnum {
+  bug
+  dark
+  dragon
+  electric
+  fairy
+  fighting
+  fire
+  flying
+  ghost
+  grass
+  ground
+  ice
+  normal
+  poison
+  psychic
+  rock
+  steel
+  water
+}
--- ./src/lib/assets/learnsets.ts	original
+++ ./src/lib/assets/learnsets.ts	fixed
@@ -47576 +47576 @@
-    'watchog',
+    'watchdog',
--- ./src/lib/assets/pokedex-data/gen2.ts	original
+++ ./src/lib/assets/pokedex-data/gen2.ts	fixed
@@ -2024 +2024 @@
-      aliases: ['mantain']
+      aliases: ['maintain']
--- ./src/lib/assets/pokedex-data/pokestar.ts	original
+++ ./src/lib/assets/pokedex-data/pokestar.ts	fixed
@@ -166 +166 @@
-      aliases: ['pokestarpropt1', 'pokestartransportprop', 'propt1', 'transport', 'transportprop']
+      aliases: ['pokestarpropt1', 'pokestartransportprop', 'prompt1', 'transport', 'transportprop']
--- ./src/lib/assets/moves.ts	original
+++ ./src/lib/assets/moves.ts	fixed
@@ -8217 +8217 @@
-        "Tthe Pokémon cuts some of its HP to recover another Pokémon's HP. It can be learned by Miltank, Skiddo and Gogoat by leveling up.",
+        "The Pokémon cuts some of its HP to recover another Pokémon's HP. It can be learned by Miltank, Skiddo and Gogoat by leveling up.",
@@ -9290 +9290 @@
-      aliases: ['playaround']
+      aliases: ['playground']
--- ./src/lib/assets/formats.json	original
+++ ./src/lib/assets/formats.json	fixed
@@ -667,599 +667,599 @@
-  "watchog": "Past",
-  "lillipup": "LC",
-  "herdier": "NFE",
-  "stoutland": "(PU)",
-  "purrloin": "LC",
-  "liepard": "(PU)",
-  "pansage": "Past",
-  "simisage": "Past",
-  "pansear": "Past",
-  "simisear": "Past",
-  "panpour": "Past",
-  "simipour": "Past",
-  "munna": "LC",
-  "musharna": "(PU)",
-  "pidove": "LC",
-  "tranquill": "NFE",
-  "unfezant": "(PU)",
-  "blitzle": "Past",
-  "zebstrika": "Past",
-  "roggenrola": "LC",
-  "boldore": "NFE",
-  "gigalith": "PU",
-  "woobat": "NFE",
-  "swoobat": "(PU)",
-  "drilbur": "LC",
-  "excadrill": "UU",
-  "audino": "PU",
-  "audinomega": "Past",
-  "timburr": "LC",
-  "gurdurr": "NFE",
-  "conkeldurr": "UU",
-  "tympole": "LC",
-  "palpitoad": "NFE",
-  "seismitoad": "RU",
-  "throh": "(PU)",
-  "sawk": "(PU)",
-  "sewaddle": "Past",
-  "swadloon": "Past",
-  "leavanny": "Past",
-  "venipede": "LC",
-  "whirlipede": "NFE",
-  "scolipede": "RUBL",
-  "cottonee": "LC",
-  "whimsicott": "PU",
-  "petilil": "LC",
-  "lilligant": "(PU)",
-  "lilliganthisui": "Future",
-  "basculin": "(PU)",
-  "basculinbluestriped": "(PU)",
-  "basculinwhitestriped": "Future",
-  "sandile": "LC",
-  "krokorok": "NFE",
-  "krookodile": "UU",
-  "darumaka": "LC",
-  "darumakagalar": "LC",
-  "darmanitan": "UU",
-  "darmanitangalar": "Uber",
-  "darmanitangalarzen": "Refer to base form / unknown",
-  "maractus": "(PU)",
-  "dwebble": "LC",
-  "crustle": "(PU)",
-  "scraggy": "NFE",
-  "scrafty": "PU",
-  "sigilyph": "NUBL",
-  "yamask": "LC",
-  "yamaskgalar": "LC",
-  "cofagrigus": "(PU)",
-  "runerigus": "(PU)",
-  "tirtouga": "LC",
-  "carracosta": "(PU)",
-  "archen": "LC",
-  "archeops": "PU",
-  "trubbish": "LC",
-  "garbodor": "PU",
-  "garbodorgmax": "Gigantamax",
-  "zorua": "LC",
-  "zoruahisui": "Future",
-  "zoroark": "PUBL",
-  "zoroarkhisui": "Future",
-  "minccino": "LC",
-  "cinccino": "PU",
-  "gothita": "NFE",
-  "gothorita": "NFE",
-  "gothitelle": "(PU)",
-  "solosis": "LC",
-  "duosion": "NFE",
-  "reuniclus": "RU",
-  "ducklett": "Past",
-  "swanna": "Past",
-  "vanillite": "LC",
-  "vanillish": "NFE",
-  "vanilluxe": "PUBL",
-  "deerling": "Past",
-  "sawsbuck": "Past",
-  "emolga": "(PU)",
-  "karrablast": "LC",
-  "escavalier": "NU",
-  "foongus": "LC",
-  "amoonguss": "UU",
-  "frillish": "LC",
-  "jellicent": "PU",
-  "alomomola": "Past",
-  "joltik": "LC",
-  "galvantula": "PU",
-  "ferroseed": "PU",
-  "ferrothorn": "OU",
-  "klink": "LC",
-  "klang": "NFE",
-  "klinklang": "(PU)",
-  "tynamo": "Past",
-  "eelektrik": "Past",
-  "eelektross": "Past",
-  "elgyem": "LC",
-  "beheeyem": "(PU)",
-  "litwick": "LC",
-  "lampent": "NFE",
-  "chandelure": "RU",
-  "axew": "LC",
-  "fraxure": "NFE",
-  "haxorus": "RUBL",
-  "cubchoo": "LC",
-  "beartic": "(PU)",
-  "cryogonal": "(PU)",
-  "shelmet": "LC",
-  "accelgor": "(PU)",
-  "stunfisk": "(PU)",
-  "stunfiskgalar": "(PU)",
-  "mienfoo": "LC",
-  "mienshao": "UUBL",
-  "druddigon": "PU",
-  "golett": "LC",
-  "golurk": "NU",
-  "pawniard": "LC",
-  "bisharp": "OU",
-  "bouffalant": "(PU)",
-  "rufflet": "NFE",
-  "braviary": "NU",
-  "braviaryhisui": "Future",
-  "vullaby": "NFE",
-  "mandibuzz": "UU",
-  "heatmor": "(PU)",
-  "durant": "RUBL",
-  "deino": "LC",
-  "zweilous": "NFE",
-  "hydreigon": "UU",
-  "larvesta": "LC",
-  "volcarona": "OU",
-  "cobalion": "UU",
-  "terrakion": "UUBL",
-  "virizion": "PUBL",
-  "tornadus": "NUBL",
-  "tornadustherian": "OU",
-  "thundurus": "UUBL",
-  "thundurustherian": "UU",
-  "reshiram": "Uber",
-  "zekrom": "Uber",
-  "landorus": "Uber",
-  "landorustherian": "OU",
-  "kyurem": "Uber",
-  "kyuremblack": "Uber",
-  "kyuremwhite": "Uber",
-  "keldeo": "UU",
-  "keldeoresolute": "Refer to base form / unknown",
-  "meloetta": "Past",
-  "meloettapirouette": "Past",
-  "genesect": "Uber",
-  "genesectdouse": "Refer to base form / unknown",
-  "chespin": "Past",
-  "quilladin": "Past",
-  "chesnaught": "Past",
-  "fennekin": "Past",
-  "braixen": "Past",
-  "delphox": "Past",
-  "froakie": "Past",
-  "frogadier": "Past",
-  "greninja": "Past",
-  "greninjaash": "Past",
-  "bunnelby": "LC",
-  "diggersby": "RUBL",
-  "fletchling": "LC",
-  "fletchinder": "NFE",
-  "talonflame": "NU",
-  "scatterbug": "Past",
-  "spewpa": "Past",
-  "vivillon": "Past",
-  "vivillonfancy": "Past",
-  "vivillonpokeball": "Past",
-  "litleo": "Past",
-  "pyroar": "Past",
-  "flabebe": "Past",
-  "floette": "Past",
-  "floetteeternal": "Past",
-  "florges": "Past",
-  "skiddo": "Past",
-  "gogoat": "Past",
-  "pancham": "LC",
-  "pangoro": "NUBL",
-  "furfrou": "Past",
-  "espurr": "LC",
-  "meowstic": "(PU)",
-  "meowsticf": "(PU)",
-  "honedge": "LC",
-  "doublade": "PU",
-  "aegislash": "UUBL",
-  "aegislashblade": "Refer to base form / unknown",
-  "spritzee": "LC",
-  "aromatisse": "PU",
-  "swirlix": "NFE",
-  "slurpuff": "NUBL",
-  "inkay": "LC",
-  "malamar": "(PU)",
-  "binacle": "LC",
-  "barbaracle": "NUBL",
-  "skrelp": "LC",
-  "dragalge": "NUBL",
-  "clauncher": "LC",
-  "clawitzer": "PUBL",
-  "helioptile": "LC",
-  "heliolisk": "NU",
-  "tyrunt": "LC",
-  "tyrantrum": "NU",
-  "amaura": "LC",
-  "aurorus": "(PU)",
-  "hawlucha": "UUBL",
-  "dedenne": "(PU)",
-  "carbink": "(PU)",
-  "goomy": "LC",
-  "sliggoo": "NFE",
-  "sliggoohisui": "Future",
-  "goodra": "NUBL",
-  "goodrahisui": "Future",
-  "klefki": "RU",
-  "phantump": "LC",
-  "trevenant": "(PU)",
-  "pumpkaboo": "LC",
-  "pumpkaboosmall": "LC",
-  "pumpkaboolarge": "LC",
-  "pumpkaboosuper": "LC",
-  "gourgeist": "(PU)",
-  "gourgeistsmall": "(PU)",
-  "gourgeistlarge": "(PU)",
-  "gourgeistsuper": "(PU)",
-  "bergmite": "LC",
-  "avalugg": "(PU)",
-  "avalugghisui": "Future",
-  "noibat": "LC",
-  "noivern": "RU",
-  "xerneas": "Uber",
-  "xerneasneutral": "Custom",
-  "yveltal": "Uber",
-  "zygarde": "Uber",
-  "zygarde10": "UU",
-  "zygardecomplete": "Uber",
-  "diancie": "NU",
-  "dianciemega": "Past",
-  "hoopa": "Past",
-  "hoopaunbound": "Past",
-  "volcanion": "OU",
-  "rowlet": "LC",
-  "dartrix": "NFE",
-  "decidueye": "NU",
-  "decidueyehisui": "Future",
-  "litten": "LC",
-  "torracat": "NFE",
-  "incineroar": "RU",
-  "popplio": "LC",
-  "brionne": "NFE",
-  "primarina": "UU",
-  "pikipek": "Past",
-  "trumbeak": "Past",
-  "toucannon": "Past",
-  "yungoos": "Past",
-  "gumshoos": "Past",
-  "gumshoostotem": "Past",
-  "grubbin": "LC",
-  "charjabug": "NFE",
-  "vikavolt": "(PU)",
-  "vikavolttotem": "Past",
-  "crabrawler": "Past",
-  "crabominable": "Past",
-  "oricorio": "Past",
-  "oricoriopompom": "Past",
-  "oricoriopau": "Past",
-  "oricoriosensu": "Past",
-  "cutiefly": "NFE",
-  "ribombee": "PU",
-  "ribombeetotem": "Past",
-  "rockruff": "LC",
-  "rockruffdusk": "LC",
-  "lycanroc": "PU",
-  "lycanrocmidnight": "(PU)",
-  "lycanrocdusk": "UU",
-  "wishiwashi": "PU",
-  "wishiwashischool": "Refer to base form / unknown",
-  "mareanie": "LC",
-  "toxapex": "OU",
-  "mudbray": "LC",
-  "mudsdale": "NU",
-  "dewpider": "LC",
-  "araquanid": "PUBL",
-  "araquanidtotem": "Past",
-  "fomantis": "LC",
-  "lurantis": "(PU)",
-  "lurantistotem": "Past",
-  "morelull": "LC",
-  "shiinotic": "(PU)",
-  "salandit": "LC",
-  "salazzle": "NU",
-  "salazzletotem": "Past",
-  "stufful": "LC",
-  "bewear": "NUBL",
-  "bounsweet": "LC",
-  "steenee": "NFE",
-  "tsareena": "NU",
-  "comfey": "PU",
-  "oranguru": "(PU)",
-  "passimian": "NU",
-  "wimpod": "LC",
-  "golisopod": "RU",
-  "sandygast": "LC",
-  "palossand": "(PU)",
-  "pyukumuku": "(PU)",
-  "typenull": "NFE",
-  "silvally": "(PU)",
-  "silvallybug": "(PU)",
-  "silvallydark": "(PU)",
-  "silvallydragon": "(PU)",
-  "silvallyelectric": "(PU)",
-  "silvallyfairy": "PU",
-  "silvallyfighting": "(PU)",
-  "silvallyfire": "(PU)",
-  "silvallyflying": "(PU)",
-  "silvallyghost": "PU",
-  "silvallygrass": "(PU)",
-  "silvallyground": "NU",
-  "silvallyice": "(PU)",
-  "silvallypoison": "(PU)",
-  "silvallypsychic": "(PU)",
-  "silvallyrock": "(PU)",
-  "silvallysteel": "PU",
-  "silvallywater": "(PU)",
-  "minior": "Past",
-  "miniormeteor": "Past",
-  "komala": "Past",
-  "turtonator": "(PU)",
-  "togedemaru": "PU",
-  "togedemarutotem": "Past",
-  "mimikyu": "RU",
-  "mimikyutotem": "Past",
-  "mimikyubustedtotem": "Past",
-  "bruxish": "Past",
-  "drampa": "PUBL",
-  "dhelmise": "NU",
-  "jangmoo": "LC",
-  "hakamoo": "NFE",
-  "kommoo": "UUBL",
-  "kommoototem": "Past",
-  "tapukoko": "OU",
-  "tapulele": "OU",
-  "tapubulu": "UU",
-  "tapufini": "OU",
-  "cosmog": "LC",
-  "cosmoem": "NFE",
-  "solgaleo": "Uber",
-  "lunala": "Uber",
-  "nihilego": "UU",
-  "buzzwole": "OU",
-  "pheromosa": "Uber",
-  "xurkitree": "RU",
-  "celesteela": "UU",
-  "kartana": "OU",
-  "guzzlord": "PUBL",
-  "necrozma": "RUBL",
-  "necrozmaduskmane": "Uber",
-  "necrozmadawnwings": "Uber",
-  "necrozmaultra": "Past",
-  "magearna": "Uber",
-  "magearnaoriginal": "Refer to base form / unknown",
-  "marshadow": "Uber",
-  "poipole": "NFE",
-  "naganadel": "Uber",
-  "stakataka": "NU",
-  "blacephalon": "OU",
-  "zeraora": "OU",
-  "meltan": "(PU)",
-  "melmetal": "OU",
-  "melmetalgmax": "Gigantamax",
-  "grookey": "LC",
-  "thwackey": "NFE",
-  "rillaboom": "OU",
-  "rillaboomgmax": "Gigantamax",
-  "scorbunny": "LC",
-  "raboot": "NFE",
-  "cinderace": "Uber",
-  "cinderacegmax": "Gigantamax",
-  "sobble": "LC",
-  "drizzile": "NFE",
-  "inteleon": "PUBL",
-  "inteleongmax": "Gigantamax",
-  "skwovet": "LC",
-  "greedent": "(PU)",
-  "rookidee": "LC",
-  "corvisquire": "NFE",
-  "corviknight": "OU",
-  "corviknightgmax": "Gigantamax",
-  "blipbug": "LC",
-  "dottler": "NFE",
-  "orbeetle": "(PU)",
-  "orbeetlegmax": "Gigantamax",
-  "nickit": "LC",
-  "thievul": "(PU)",
-  "gossifleur": "LC",
-  "eldegoss": "PU",
-  "wooloo": "LC",
-  "dubwool": "(PU)",
-  "chewtle": "LC",
-  "drednaw": "(PU)",
-  "drednawgmax": "Gigantamax",
-  "yamper": "LC",
-  "boltund": "(PU)",
-  "rolycoly": "LC",
-  "carkol": "NFE",
-  "coalossal": "(PU)",
-  "coalossalgmax": "Gigantamax",
-  "applin": "LC",
-  "flapple": "(PU)",
-  "flapplegmax": "Gigantamax",
-  "appletun": "(PU)",
-  "appletungmax": "Gigantamax",
-  "silicobra": "LC",
-  "sandaconda": "PU",
-  "sandacondagmax": "Gigantamax",
-  "cramorant": "(PU)",
-  "arrokuda": "LC",
-  "barraskewda": "OU",
-  "toxel": "LC",
-  "toxtricity": "RU",
-  "toxtricitylowkey": "RU",
-  "toxtricitygmax": "Gigantamax",
-  "toxtricitylowkeygmax": "Gigantamax",
-  "sizzlipede": "LC",
-  "centiskorch": "(PU)",
-  "centiskorchgmax": "Gigantamax",
-  "clobbopus": "LC",
-  "grapploct": "(PU)",
-  "sinistea": "LC",
-  "sinisteaantique": "LC",
-  "polteageist": "RU",
-  "hatenna": "LC",
-  "hattrem": "NFE",
-  "hatterene": "UU",
-  "hatterenegmax": "Gigantamax",
-  "impidimp": "LC",
-  "morgrem": "NFE",
-  "grimmsnarl": "NU",
-  "grimmsnarlgmax": "Gigantamax",
-  "milcery": "LC",
-  "alcremie": "(PU)",
-  "alcremiegmax": "Gigantamax",
-  "falinks": "(PU)",
-  "pincurchin": "(PU)",
-  "snom": "LC",
-  "frosmoth": "PU",
-  "stonjourner": "(PU)",
-  "eiscue": "(PU)",
-  "indeedee": "NUBL",
-  "indeedeef": "NU",
-  "morpeko": "(PU)",
-  "cufant": "LC",
-  "copperajah": "NU",
-  "copperajahgmax": "Gigantamax",
-  "dracozolt": "UUBL",
-  "arctozolt": "UUBL",
-  "dracovish": "Uber",
-  "arctovish": "(PU)",
-  "duraludon": "PUBL",
-  "duraludongmax": "Gigantamax",
-  "dreepy": "LC",
-  "drakloak": "NFE",
-  "dragapult": "OU",
-  "zacian": "AG",
-  "zaciancrowned": "AG",
-  "zamazenta": "Uber",
-  "zamazentacrowned": "Uber",
-  "eternatus": "Uber",
-  "eternatuseternamax": "Unobtainable",
-  "kubfu": "NFE",
-  "urshifu": "Uber",
-  "urshifurapidstrike": "OU",
-  "urshifugmax": "Gigantamax",
-  "urshifurapidstrikegmax": "Gigantamax",
-  "zarude": "UU",
-  "zarudedada": "Refer to base form / unknown",
-  "regieleki": "UU",
-  "regidrago": "NUBL",
-  "glastrier": "(PU)",
-  "spectrier": "Uber",
-  "calyrex": "(PU)",
-  "calyrexice": "Uber",
-  "calyrexshadow": "Uber",
-  "wyrdeer": "Future",
-  "kleavor": "Future",
-  "ursaluna": "Future",
-  "basculegion": "Future",
-  "basculegionf": "Future",
-  "sneasler": "Future",
-  "overqwil": "Future",
-  "enamorus": "Future",
-  "enamorustherian": "Future",
-  "missingno": "Custom",
-  "syclar": "CAP",
-  "syclant": "CAP",
-  "revenankh": "CAP",
-  "embirch": "CAP",
-  "flarelm": "CAP",
-  "pyroak": "CAP",
-  "breezi": "CAP",
-  "fidgit": "CAP",
-  "rebble": "CAP",
-  "tactite": "CAP",
-  "stratagem": "CAP",
-  "privatyke": "CAP",
-  "arghonaut": "CAP",
-  "nohface": "CAP",
-  "kitsunoh": "CAP",
-  "monohm": "CAP",
-  "duohm": "CAP",
-  "cyclohm": "CAP",
-  "dorsoil": "CAP",
-  "colossoil": "CAP",
-  "protowatt": "CAP",
-  "krilowatt": "CAP",
-  "voodoll": "CAP",
-  "voodoom": "CAP",
-  "scratchet": "CAP",
-  "tomohawk": "CAP",
-  "necturine": "CAP",
-  "necturna": "CAP",
-  "mollux": "CAP",
-  "cupra": "CAP",
-  "argalis": "CAP",
-  "aurumoth": "CAP",
-  "brattler": "CAP",
-  "malaconda": "CAP",
-  "cawdet": "CAP",
-  "cawmodore": "CAP",
-  "volkritter": "CAP",
-  "volkraken": "CAP",
-  "snugglow": "CAP",
-  "plasmanta": "CAP",
-  "floatoy": "CAP",
-  "caimanoe": "CAP",
-  "naviathan": "CAP",
-  "crucibelle": "CAP",
-  "crucibellemega": "CAP",
-  "pluffle": "CAP",
-  "kerfluffle": "CAP",
-  "pajantom": "CAP",
-  "mumbao": "CAP",
-  "jumbao": "CAP",
-  "fawnifer": "CAP",
-  "electrelk": "CAP",
-  "caribolt": "CAP",
-  "smogecko": "CAP",
-  "smoguana": "CAP",
-  "smokomodo": "CAP",
-  "swirlpool": "CAP",
-  "coribalis": "CAP",
-  "snaelstrom": "CAP",
-  "justyke": "CAP",
-  "equilibra": "CAP",
-  "solotl": "CAP",
-  "astrolotl": "CAP",
-  "miasmite": "CAP",
-  "miasmaw": "CAP",
-  "chromera": "CAP",
-  "venomicon": "CAP",
-  "venomiconepilogue": "CAP",
-  "saharaja": "CAP",
-  "pokestarsmeargle": "Custom",
-  "pokestarufo": "Custom",
-  "pokestarufo2": "Custom",
-  "pokestarbrycenman": "Custom",
-  "pokestarmt": "Custom",
-  "pokestarmt2": "Custom",
-  "pokestartransport": "Custom",
-  "pokestargiant": "Custom",
-  "pokestargiant2": "Custom",
-  "pokestarhumanoid": "Custom",
-  "pokestarmonster": "Custom",
-  "pokestarf00": "Custom",
-  "pokestarf002": "Custom",
-  "pokestarspirit": "Custom",
-  "pokestarblackdoor": "Custom",
-  "pokestarwhitedoor": "Custom",
-  "pokestarblackbelt": "Custom",
-  "pokestargiantpropo2": "Custom",
-  "pokestarufopropu2": "Custom"
-}
+  "watchdog": "Past",
+  "lillipup": "LC",
+  "herdier": "NFE",
+  "stoutland": "(PU)",
+  "purrloin": "LC",
+  "liepard": "(PU)",
+  "pansage": "Past",
+  "simisage": "Past",
+  "pansear": "Past",
+  "simisear": "Past",
+  "panpour": "Past",
+  "simipour": "Past",
+  "munna": "LC",
+  "musharna": "(PU)",
+  "pidove": "LC",
+  "tranquill": "NFE",
+  "unfezant": "(PU)",
+  "blitzle": "Past",
+  "zebstrika": "Past",
+  "roggenrola": "LC",
+  "boldore": "NFE",
+  "gigalith": "PU",
+  "woobat": "NFE",
+  "swoobat": "(PU)",
+  "drilbur": "LC",
+  "excadrill": "UU",
+  "audino": "PU",
+  "audinomega": "Past",
+  "timburr": "LC",
+  "gurdurr": "NFE",
+  "conkeldurr": "UU",
+  "tympole": "LC",
+  "palpitoad": "NFE",
+  "seismitoad": "RU",
+  "throh": "(PU)",
+  "sawk": "(PU)",
+  "sewaddle": "Past",
+  "swadloon": "Past",
+  "leavanny": "Past",
+  "venipede": "LC",
+  "whirlipede": "NFE",
+  "scolipede": "RUBL",
+  "cottonee": "LC",
+  "whimsicott": "PU",
+  "petilil": "LC",
+  "lilligant": "(PU)",
+  "lilliganthisui": "Future",
+  "basculin": "(PU)",
+  "basculinbluestriped": "(PU)",
+  "basculinwhitestriped": "Future",
+  "sandile": "LC",
+  "krokorok": "NFE",
+  "krookodile": "UU",
+  "darumaka": "LC",
+  "darumakagalar": "LC",
+  "darmanitan": "UU",
+  "darmanitangalar": "Uber",
+  "darmanitangalarzen": "Refer to base form / unknown",
+  "maractus": "(PU)",
+  "dwebble": "LC",
+  "crustle": "(PU)",
+  "scraggy": "NFE",
+  "scrafty": "PU",
+  "sigilyph": "NUBL",
+  "yamask": "LC",
+  "yamaskgalar": "LC",
+  "cofagrigus": "(PU)",
+  "runerigus": "(PU)",
+  "tirtouga": "LC",
+  "carracosta": "(PU)",
+  "archen": "LC",
+  "archeops": "PU",
+  "trubbish": "LC",
+  "garbodor": "PU",
+  "garbodorgmax": "Gigantamax",
+  "zorua": "LC",
+  "zoruahisui": "Future",
+  "zoroark": "PUBL",
+  "zoroarkhisui": "Future",
+  "minccino": "LC",
+  "cinccino": "PU",
+  "gothita": "NFE",
+  "gothorita": "NFE",
+  "gothitelle": "(PU)",
+  "solosis": "LC",
+  "duosion": "NFE",
+  "reuniclus": "RU",
+  "ducklett": "Past",
+  "swanna": "Past",
+  "vanillite": "LC",
+  "vanillish": "NFE",
+  "vanilluxe": "PUBL",
+  "deerling": "Past",
+  "sawsbuck": "Past",
+  "emolga": "(PU)",
+  "karrablast": "LC",
+  "escavalier": "NU",
+  "foongus": "LC",
+  "amoonguss": "UU",
+  "frillish": "LC",
+  "jellicent": "PU",
+  "alomomola": "Past",
+  "joltik": "LC",
+  "galvantula": "PU",
+  "ferroseed": "PU",
+  "ferrothorn": "OU",
+  "klink": "LC",
+  "klang": "NFE",
+  "klinklang": "(PU)",
+  "tynamo": "Past",
+  "eelektrik": "Past",
+  "eelektross": "Past",
+  "elgyem": "LC",
+  "beheeyem": "(PU)",
+  "litwick": "LC",
+  "lampent": "NFE",
+  "chandelure": "RU",
+  "axew": "LC",
+  "fraxure": "NFE",
+  "haxorus": "RUBL",
+  "cubchoo": "LC",
+  "beartic": "(PU)",
+  "cryogonal": "(PU)",
+  "shelmet": "LC",
+  "accelgor": "(PU)",
+  "stunfisk": "(PU)",
+  "stunfiskgalar": "(PU)",
+  "mienfoo": "LC",
+  "mienshao": "UUBL",
+  "druddigon": "PU",
+  "golett": "LC",
+  "golurk": "NU",
+  "pawniard": "LC",
+  "bisharp": "OU",
+  "bouffalant": "(PU)",
+  "rufflet": "NFE",
+  "braviary": "NU",
+  "braviaryhisui": "Future",
+  "vullaby": "NFE",
+  "mandibuzz": "UU",
+  "heatmor": "(PU)",
+  "durant": "RUBL",
+  "deino": "LC",
+  "zweilous": "NFE",
+  "hydreigon": "UU",
+  "larvesta": "LC",
+  "volcarona": "OU",
+  "cobalion": "UU",
+  "terrakion": "UUBL",
+  "virizion": "PUBL",
+  "tornadus": "NUBL",
+  "tornadustherian": "OU",
+  "thundurus": "UUBL",
+  "thundurustherian": "UU",
+  "reshiram": "Uber",
+  "zekrom": "Uber",
+  "landorus": "Uber",
+  "landorustherian": "OU",
+  "kyurem": "Uber",
+  "kyuremblack": "Uber",
+  "kyuremwhite": "Uber",
+  "keldeo": "UU",
+  "keldeoresolute": "Refer to base form / unknown",
+  "meloetta": "Past",
+  "meloettapirouette": "Past",
+  "genesect": "Uber",
+  "genesectdouse": "Refer to base form / unknown",
+  "chespin": "Past",
+  "quilladin": "Past",
+  "chesnaught": "Past",
+  "fennekin": "Past",
+  "braixen": "Past",
+  "delphox": "Past",
+  "froakie": "Past",
+  "frogadier": "Past",
+  "greninja": "Past",
+  "greninjaash": "Past",
+  "bunnelby": "LC",
+  "diggersby": "RUBL",
+  "fletchling": "LC",
+  "fletchinder": "NFE",
+  "talonflame": "NU",
+  "scatterbug": "Past",
+  "spewpa": "Past",
+  "vivillon": "Past",
+  "vivillonfancy": "Past",
+  "vivillonpokeball": "Past",
+  "litleo": "Past",
+  "pyroar": "Past",
+  "flabebe": "Past",
+  "floette": "Past",
+  "floetteeternal": "Past",
+  "florges": "Past",
+  "skiddo": "Past",
+  "gogoat": "Past",
+  "pancham": "LC",
+  "pangoro": "NUBL",
+  "furfrou": "Past",
+  "espurr": "LC",
+  "meowstic": "(PU)",
+  "meowsticf": "(PU)",
+  "honedge": "LC",
+  "doublade": "PU",
+  "aegislash": "UUBL",
+  "aegislashblade": "Refer to base form / unknown",
+  "spritzee": "LC",
+  "aromatisse": "PU",
+  "swirlix": "NFE",
+  "slurpuff": "NUBL",
+  "inkay": "LC",
+  "malamar": "(PU)",
+  "binacle": "LC",
+  "barbaracle": "NUBL",
+  "skrelp": "LC",
+  "dragalge": "NUBL",
+  "clauncher": "LC",
+  "clawitzer": "PUBL",
+  "helioptile": "LC",
+  "heliolisk": "NU",
+  "tyrunt": "LC",
+  "tyrantrum": "NU",
+  "amaura": "LC",
+  "aurorus": "(PU)",
+  "hawlucha": "UUBL",
+  "dedenne": "(PU)",
+  "carbink": "(PU)",
+  "goomy": "LC",
+  "sliggoo": "NFE",
+  "sliggoohisui": "Future",
+  "goodra": "NUBL",
+  "goodrahisui": "Future",
+  "klefki": "RU",
+  "phantump": "LC",
+  "trevenant": "(PU)",
+  "pumpkaboo": "LC",
+  "pumpkaboosmall": "LC",
+  "pumpkaboolarge": "LC",
+  "pumpkaboosuper": "LC",
+  "gourgeist": "(PU)",
+  "gourgeistsmall": "(PU)",
+  "gourgeistlarge": "(PU)",
+  "gourgeistsuper": "(PU)",
+  "bergmite": "LC",
+  "avalugg": "(PU)",
+  "avalugghisui": "Future",
+  "noibat": "LC",
+  "noivern": "RU",
+  "xerneas": "Uber",
+  "xerneasneutral": "Custom",
+  "yveltal": "Uber",
+  "zygarde": "Uber",
+  "zygarde10": "UU",
+  "zygardecomplete": "Uber",
+  "diancie": "NU",
+  "dianciemega": "Past",
+  "hoopa": "Past",
+  "hoopaunbound": "Past",
+  "volcanion": "OU",
+  "rowlet": "LC",
+  "dartrix": "NFE",
+  "decidueye": "NU",
+  "decidueyehisui": "Future",
+  "litten": "LC",
+  "torracat": "NFE",
+  "incineroar": "RU",
+  "popplio": "LC",
+  "brionne": "NFE",
+  "primarina": "UU",
+  "pikipek": "Past",
+  "trumbeak": "Past",
+  "toucannon": "Past",
+  "yungoos": "Past",
+  "gumshoos": "Past",
+  "gumshoostotem": "Past",
+  "grubbin": "LC",
+  "charjabug": "NFE",
+  "vikavolt": "(PU)",
+  "vikavolttotem": "Past",
+  "crabrawler": "Past",
+  "crabominable": "Past",
+  "oricorio": "Past",
+  "oricoriopompom": "Past",
+  "oricoriopau": "Past",
+  "oricoriosensu": "Past",
+  "cutiefly": "NFE",
+  "ribombee": "PU",
+  "ribombeetotem": "Past",
+  "rockruff": "LC",
+  "rockruffdusk": "LC",
+  "lycanroc": "PU",
+  "lycanrocmidnight": "(PU)",
+  "lycanrocdusk": "UU",
+  "wishiwashi": "PU",
+  "wishiwashischool": "Refer to base form / unknown",
+  "mareanie": "LC",
+  "toxapex": "OU",
+  "mudbray": "LC",
+  "mudsdale": "NU",
+  "dewpider": "LC",
+  "araquanid": "PUBL",
+  "araquanidtotem": "Past",
+  "fomantis": "LC",
+  "lurantis": "(PU)",
+  "lurantistotem": "Past",
+  "morelull": "LC",
+  "shiinotic": "(PU)",
+  "salandit": "LC",
+  "salazzle": "NU",
+  "salazzletotem": "Past",
+  "stufful": "LC",
+  "bewear": "NUBL",
+  "bounsweet": "LC",
+  "steenee": "NFE",
+  "tsareena": "NU",
+  "comfey": "PU",
+  "oranguru": "(PU)",
+  "passimian": "NU",
+  "wimpod": "LC",
+  "golisopod": "RU",
+  "sandygast": "LC",
+  "palossand": "(PU)",
+  "pyukumuku": "(PU)",
+  "typenull": "NFE",
+  "silvally": "(PU)",
+  "silvallybug": "(PU)",
+  "silvallydark": "(PU)",
+  "silvallydragon": "(PU)",
+  "silvallyelectric": "(PU)",
+  "silvallyfairy": "PU",
+  "silvallyfighting": "(PU)",
+  "silvallyfire": "(PU)",
+  "silvallyflying": "(PU)",
+  "silvallyghost": "PU",
+  "silvallygrass": "(PU)",
+  "silvallyground": "NU",
+  "silvallyice": "(PU)",
+  "silvallypoison": "(PU)",
+  "silvallypsychic": "(PU)",
+  "silvallyrock": "(PU)",
+  "silvallysteel": "PU",
+  "silvallywater": "(PU)",
+  "minior": "Past",
+  "miniormeteor": "Past",
+  "komala": "Past",
+  "turtonator": "(PU)",
+  "togedemaru": "PU",
+  "togedemarutotem": "Past",
+  "mimikyu": "RU",
+  "mimikyutotem": "Past",
+  "mimikyubustedtotem": "Past",
+  "bruxish": "Past",
+  "drampa": "PUBL",
+  "dhelmise": "NU",
+  "jangmoo": "LC",
+  "hakamoo": "NFE",
+  "kommoo": "UUBL",
+  "kommoototem": "Past",
+  "tapukoko": "OU",
+  "tapulele": "OU",
+  "tapubulu": "UU",
+  "tapufini": "OU",
+  "cosmog": "LC",
+  "cosmoem": "NFE",
+  "solgaleo": "Uber",
+  "lunala": "Uber",
+  "nihilego": "UU",
+  "buzzwole": "OU",
+  "pheromosa": "Uber",
+  "xurkitree": "RU",
+  "celesteela": "UU",
+  "kartana": "OU",
+  "guzzlord": "PUBL",
+  "necrozma": "RUBL",
+  "necrozmaduskmane": "Uber",
+  "necrozmadawnwings": "Uber",
+  "necrozmaultra": "Past",
+  "magearna": "Uber",
+  "magearnaoriginal": "Refer to base form / unknown",
+  "marshadow": "Uber",
+  "poipole": "NFE",
+  "naganadel": "Uber",
+  "stakataka": "NU",
+  "blacephalon": "OU",
+  "zeraora": "OU",
+  "meltan": "(PU)",
+  "melmetal": "OU",
+  "melmetalgmax": "Gigantamax",
+  "grookey": "LC",
+  "thwackey": "NFE",
+  "rillaboom": "OU",
+  "rillaboomgmax": "Gigantamax",
+  "scorbunny": "LC",
+  "raboot": "NFE",
+  "cinderace": "Uber",
+  "cinderacegmax": "Gigantamax",
+  "sobble": "LC",
+  "drizzile": "NFE",
+  "inteleon": "PUBL",
+  "inteleongmax": "Gigantamax",
+  "skwovet": "LC",
+  "greedent": "(PU)",
+  "rookidee": "LC",
+  "corvisquire": "NFE",
+  "corviknight": "OU",
+  "corviknightgmax": "Gigantamax",
+  "blipbug": "LC",
+  "dottler": "NFE",
+  "orbeetle": "(PU)",
+  "orbeetlegmax": "Gigantamax",
+  "nickit": "LC",
+  "thievul": "(PU)",
+  "gossifleur": "LC",
+  "eldegoss": "PU",
+  "wooloo": "LC",
+  "dubwool": "(PU)",
+  "chewtle": "LC",
+  "drednaw": "(PU)",
+  "drednawgmax": "Gigantamax",
+  "yamper": "LC",
+  "boltund": "(PU)",
+  "rolycoly": "LC",
+  "carkol": "NFE",
+  "coalossal": "(PU)",
+  "coalossalgmax": "Gigantamax",
+  "applin": "LC",
+  "flapple": "(PU)",
+  "flapplegmax": "Gigantamax",
+  "appletun": "(PU)",
+  "appletungmax": "Gigantamax",
+  "silicobra": "LC",
+  "sandaconda": "PU",
+  "sandacondagmax": "Gigantamax",
+  "cramorant": "(PU)",
+  "arrokuda": "LC",
+  "barraskewda": "OU",
+  "toxel": "LC",
+  "toxtricity": "RU",
+  "toxtricitylowkey": "RU",
+  "toxtricitygmax": "Gigantamax",
+  "toxtricitylowkeygmax": "Gigantamax",
+  "sizzlipede": "LC",
+  "centiskorch": "(PU)",
+  "centiskorchgmax": "Gigantamax",
+  "clobbopus": "LC",
+  "grapploct": "(PU)",
+  "sinistea": "LC",
+  "sinisteaantique": "LC",
+  "polteageist": "RU",
+  "hatenna": "LC",
+  "hattrem": "NFE",
+  "hatterene": "UU",
+  "hatterenegmax": "Gigantamax",
+  "impidimp": "LC",
+  "morgrem": "NFE",
+  "grimmsnarl": "NU",
+  "grimmsnarlgmax": "Gigantamax",
+  "milcery": "LC",
+  "alcremie": "(PU)",
+  "alcremiegmax": "Gigantamax",
+  "falinks": "(PU)",
+  "pincurchin": "(PU)",
+  "snom": "LC",
+  "frosmoth": "PU",
+  "stonjourner": "(PU)",
+  "eiscue": "(PU)",
+  "indeedee": "NUBL",
+  "indeedeef": "NU",
+  "morpeko": "(PU)",
+  "cufant": "LC",
+  "copperajah": "NU",
+  "copperajahgmax": "Gigantamax",
+  "dracozolt": "UUBL",
+  "arctozolt": "UUBL",
+  "dracovish": "Uber",
+  "arctovish": "(PU)",
+  "duraludon": "PUBL",
+  "duraludongmax": "Gigantamax",
+  "dreepy": "LC",
+  "drakloak": "NFE",
+  "dragapult": "OU",
+  "zacian": "AG",
+  "zaciancrowned": "AG",
+  "zamazenta": "Uber",
+  "zamazentacrowned": "Uber",
+  "eternatus": "Uber",
+  "eternatuseternamax": "Unobtainable",
+  "kubfu": "NFE",
+  "urshifu": "Uber",
+  "urshifurapidstrike": "OU",
+  "urshifugmax": "Gigantamax",
+  "urshifurapidstrikegmax": "Gigantamax",
+  "zarude": "UU",
+  "zarudedada": "Refer to base form / unknown",
+  "regieleki": "UU",
+  "regidrago": "NUBL",
+  "glastrier": "(PU)",
+  "spectrier": "Uber",
+  "calyrex": "(PU)",
+  "calyrexice": "Uber",
+  "calyrexshadow": "Uber",
+  "wyrdeer": "Future",
+  "kleavor": "Future",
+  "ursaluna": "Future",
+  "basculegion": "Future",
+  "basculegionf": "Future",
+  "sneasler": "Future",
+  "overqwil": "Future",
+  "enamorus": "Future",
+  "enamorustherian": "Future",
+  "missingno": "Custom",
+  "syclar": "CAP",
+  "syclant": "CAP",
+  "revenankh": "CAP",
+  "embirch": "CAP",
+  "flarelm": "CAP",
+  "pyroak": "CAP",
+  "breezi": "CAP",
+  "fidgit": "CAP",
+  "rebble": "CAP",
+  "tactite": "CAP",
+  "stratagem": "CAP",
+  "privatyke": "CAP",
+  "arghonaut": "CAP",
+  "nohface": "CAP",
+  "kitsunoh": "CAP",
+  "monohm": "CAP",
+  "duohm": "CAP",
+  "cyclohm": "CAP",
+  "dorsoil": "CAP",
+  "colossoil": "CAP",
+  "protowatt": "CAP",
+  "krilowatt": "CAP",
+  "voodoll": "CAP",
+  "voodoom": "CAP",
+  "scratchet": "CAP",
+  "tomohawk": "CAP",
+  "necturine": "CAP",
+  "necturna": "CAP",
+  "mollux": "CAP",
+  "cupra": "CAP",
+  "argalis": "CAP",
+  "aurumoth": "CAP",
+  "brattler": "CAP",
+  "malaconda": "CAP",
+  "cawdet": "CAP",
+  "cawmodore": "CAP",
+  "volkritter": "CAP",
+  "volkraken": "CAP",
+  "snugglow": "CAP",
+  "plasmanta": "CAP",
+  "floatoy": "CAP",
+  "caimanoe": "CAP",
+  "naviathan": "CAP",
+  "crucibelle": "CAP",
+  "crucibellemega": "CAP",
+  "pluffle": "CAP",
+  "kerfluffle": "CAP",
+  "pajantom": "CAP",
+  "mumbao": "CAP",
+  "jumbao": "CAP",
+  "fawnifer": "CAP",
+  "electrelk": "CAP",
+  "caribolt": "CAP",
+  "smogecko": "CAP",
+  "smoguana": "CAP",
+  "smokomodo": "CAP",
+  "swirlpool": "CAP",
+  "coribalis": "CAP",
+  "snaelstrom": "CAP",
+  "justyke": "CAP",
+  "equilibra": "CAP",
+  "solotl": "CAP",
+  "astrolotl": "CAP",
+  "miasmite": "CAP",
+  "miasmaw": "CAP",
+  "chromera": "CAP",
+  "venomicon": "CAP",
+  "venomiconepilogue": "CAP",
+  "saharaja": "CAP",
+  "pokestarsmeargle": "Custom",
+  "pokestarufo": "Custom",
+  "pokestarufo2": "Custom",
+  "pokestarbrycenman": "Custom",
+  "pokestarmt": "Custom",
+  "pokestarmt2": "Custom",
+  "pokestartransport": "Custom",
+  "pokestargiant": "Custom",
+  "pokestargiant2": "Custom",
+  "pokestarhumanoid": "Custom",
+  "pokestarmonster": "Custom",
+  "pokestarf00": "Custom",
+  "pokestarf002": "Custom",
+  "pokestarspirit": "Custom",
+  "pokestarblackdoor": "Custom",
+  "pokestarwhitedoor": "Custom",
+  "pokestarblackbelt": "Custom",
+  "pokestargiantpropo2": "Custom",
+  "pokestarufopropu2": "Custom"
+}
--- ./src/lib/utils/util.ts	original
+++ ./src/lib/utils/util.ts	fixed
@@ -10 +10 @@
-/** Converts a string to lower-hypen-case */
+/** Converts a string to lower-hyphen-case */
--- ./README.md	original
+++ ./README.md	fixed
@@ -40 +40 @@
-data. Unlike contemporary APIs this API focusses on speed, accuracy and data
+data. Unlike contemporary APIs this API focuses on speed, accuracy and data
--- ./src/lib/assets/pokedex-data/gen5.ts	original
+++ ./src/lib/assets/pokedex-data/gen5.ts	fixed
@@ -275 +275 @@
-      evos: ['watchog'],
+      evos: ['watchdog'],
@@ -289 +289 @@
-    'watchog',
+    'watchdog',
@@ -305 +305 @@
-      species: 'watchog',
+      species: 'watchdog',
