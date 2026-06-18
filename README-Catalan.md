# 🦓 Pas zebra: una llista de comprovació de seguretat digital fàcil d'utilitzar

## 🎯 Comença aquí!

### 🤔 Llegeix aquesta guia si tu

-   Utilitzes internet diàriament — per a la feina, les xarxes socials i les transaccions financeres.
-   Vols garantir proactivament la teva seguretat i privacitat digitals, però no et trobes en perill imminent. (Si és el teu cas, contacta amb algú de la teva comunitat per a una consulta individual.)
-   Et sents còmode amb la tecnologia — confies en la teva capacitat per canviar la configuració de l'ordinador o del telèfon intel·ligent.

### 🗺 D'on prové aquesta guia

-   Aquesta guia es basa en la nostra experiència ajudant particulars i grups a millorar les seves pràctiques de seguretat digital, i en les nostres vivències vivint i treballant al Canadà, els EUA, Alemanya i Hong Kong.
-   Sempre que ha estat possible, hem triat aplicacions i eines accessibles i fàcils d'utilitzar en lloc d'altres que, tot i ser tècnicament sofisticades, són difícils d'utilitzar. La nostra decisió es basa en l'observació que les persones es tornen més maldestres en situacions d'estrès, per la qual cosa és important mantenir els procediments tan senzills com sigui possible.

### 🌱 Com utilitzar aquesta guia

-   **Comença pel Nivell 1 i puja de nivell!** Les recomanacions estan ordenades per nivells de dificultat creixent.
-   **El nivell 1 és la secció de nocions bàsiques ràpides.** La hauríeu de poder completar en mitja hora i és probable que ja estigueu familiaritzats amb moltes de les recomanacions que hi ha — però mai no està de més comprovar-ho.
-   **El nivell 2 aprofundeix més en la configuració del dispositiu/aplicació.** Aquesta secció trigarà d'1 a 2 hores, en funció de quants comptes i dispositius utilitzis habitualment.
-   **Com a mínim, fes tot el dels nivells 1 i 2.** Això et protegirà dels atacs més habituals.
-   **Entre el nivell 2 i el 3 hi ha una pausa de lectura** sobre com desenvolupar millors hàbits i reflexos de seguretat digital.
-   **El nivell 3 t'ajudarà a afinar la teva privacitat en línia** i**a** reduir dràsticament la quantitat d'informació personal que comparteixes gratuïtament. Aquesta secció també trigarà d'1 a 2 hores.
-   **El nivell 4 potencia la teva pràctica de seguretat digital amb les últimes eines i consells.** Algunes parts poden requerir que surtis de la teva zona de confort i d'altres que gastis diners en coses. La major part només hauria de trigar mitja hora a completar-se.
-   **Els escenaris que es comparteixen després del Nivell 4 són per a situacions de més risc.** Repassa'ls per veure si se t'hi aplica algun. (Com que el risc és més alt, es dona per fet que has fet tot el que s'explica als Nivells 1–4.)
-   **Aquesta guia és un document viu.** No dubteu a enviar una sol·licitud d'extracció (pull request) o a fer una bifurcació de la vostra versió de la guia [a GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🗣 Llegeix aquesta guia en altres idiomes
- [English (Anglès)](https://zebracrossing.narwhalacademy.org/index-Deutsch.php)
- [Alemany (alemany)](https://zebracrossing.narwhalacademy.org/index-Deutsch.php)
-   [عربية (Arabic)
* [繁體中文 (Traditional Chinese)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-繁體中文.md)
-  [日本語 (Japonès)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-日本語.md) (Japonès, en procés de revisió)
-  [Türkçe](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-T%C3%BCrk%C3%A7e.md) (Turc, en elaboració)
-  [Italiano](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Italiano.md) (italià, en preparació)
-  Vols contribuir amb una altra llengua? [Envia'ns un missatge](mailto:contact@narwhalacademy.org) per col·laborar.

### ☕️ Dona suport a aquesta guia
-   [Compra'ns un cafè virtual](https://ko-fi.com/narwhalacademy)
-   Comparteix aquesta guia amb els teus amics i la teva comunitat!
-   [Envia els teus comentaris](mailto:contact@narwhalacademy.org) o [col·labora amb la guia a GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🕒 Darrera actualització
-   27 de gener de 2026
---
## 🧐 Termes útils per aprendre

### 🎯 Modelatge de amenaces

**El modelatge de amenaces** és un procés que ens permet identificar amenaces potencials per protegir-nos-en. Per crear el vostre model de amenaces, feu-vos les preguntes següents:

-   **«Quin tipus de perill corro?»** Per exemple, robatoris de dades de targetes de crèdit, espionatge corporatiu o assetjament/doxxing en línia.
-   **"Quin tipus d'actius protegeixo?"** Per exemple: documents confidencials, fotos privades o missatges personals.

Recorda, però, que el teu model d'amenaça pot canviar, ja sigui gradualment amb el temps o de manera abrupta, per exemple, quan de sobte s'aprova una nova llei.

### 🔗 Enllaç més feble

**El punt més feble** és on la teva seguretat digital és més vulnerable. Per exemple, si la funció "he oblidat la contrasenya" d'un compte t'envia un enllaç al correu electrònic, els atacants només han d'accedir al teu correu electrònic per accedir al compte.

### 🔡 Nivells de xifratge

**El xifratge** és el procés de desordenar o codificar informació per fer-la il·legible per a tercers i evitar l'accés no autoritzat. Sovint, la gent classifica **el xifratge** en aquests tres tipus:

1.  **Sense xifratge:** qualsevol tercer pot interceptar les dades i llegir-les tal qual. Sovint s'anomena "text pla".
2.  **Xifratge estàndard:** Les dades es xifren de manera que tercers que les intercepten no les poden llegir, però la plataforma que s'utilitza per enviar les dades (p. ex., Facebook Messenger) les pot descifrar i llegir-les. La plataforma pot lliurar les dades descifrades als tribunals si se li ordena.
3.  **Xifratge de fi a fi:** només l'emissor i el receptor originals poden llegir les dades. La plataforma que s'utilitza per enviar les dades només té la versió xifrada i il·legible. Així que, si els tribunals ordenen a la plataforma que lliuri les dades, no hi ha res d'útil per lliurar.

### 🧩 Metadades

**Les metadades** són la informació contextual que envolta les teves dades. Per exemple, les metadades d'una trucada telefònica inclouen el número al qual vas trucar i la durada de la trucada (però no el contingut de la conversa). Amb prou metadades, els atacants poden muntar una imatge relativament fiable de qui ets, a qui coneixes i on vas.

_Malauradament, les proteccions legals al voltant de les metadades solen ser febles o inexistents._

---

## 🚶🏽‍♀️ Nivell 1: Seguretat essencial en deu minuts

### 🔍 Identifica comptes importants

-   Imagina que un atacant aconsegueix accedir a tots els teus comptes en línia. Quins d'aquests comptes serien realment dolorosos de perdre? Fes-ne una llista i escriu-la.
-   Normalment, aquesta llista inclou comptes utilitzats per al correu electrònic, la banca en línia, les xarxes socials i potser un o dos relacionats amb la feina.
-   La llista hauria de ser curta i tenir menys de 10 elements.

### 🔒 Doble bloqueig per als comptes importants

El primer pany sol ser la contrasenya del vostre compte. El segon pany adopta una forma diferent i/o arriba per un canal diferent, la majoria de vegades com un codi enviat al vostre telèfon mitjançant una aplicació o un missatge de text (SMS). Aquest pany addicional s'anomena habitualment _autenticació de dos factors_ (abreujada com _2FA_) o _verificació de dos passos_.

-   **Activa l'autenticació de dos factors als comptes importants que** acabes d'identificar. Per trobar instruccions sobre com fer-ho:
    -   Fes una cerca a Internet de " `autenticació de dos factors` " i el nom del compte
    -   Cerqueu el proveïdor del compte a [2fa.directory](https://2fa.directory)
-   **Utilitza una aplicació d'autenticació si n'hi ha una disponible.** Són més segures que utilitzar SMS per rebre el codi de 2FA.
    -   Aplicacions recomanades:
        -   [2FAS](https://2fas.com) (si només utilitzes un dispositiu per obtenir els codis d'autenticació)
        -   [Ente Auth](https://ente.io/auth/) (si vols que els codis es sincronicin en diversos dispositius)
    -   La majoria de comptes bancaris t'obligaran a fer servir la seva pròpia aplicació, així que no et preocupis si no pots fer servir una de les aplicacions anteriors per a això.
-   **Activa la còpia de seguretat al núvol per a la teva aplicació d'autenticació** per si mai perds el telèfon.
    -   Instruccions per a:
        -   2FAS: Ves a `Configuració → Còpia de seguretat 2FAS`
        -   Ente Auth: Crea un compte a l'aplicació

### 🔁 Activa les actualitzacions automàtiques del programari

La majoria de dispositius nous avui dia tenen les actualitzacions automàtiques activades per defecte, però val la pena comprovar-ho:

-   **Comproveu la configuració d'actualitzacions del sistema operatiu del vostre dispositiu:**
    -   En telèfons i tauletes:
        -   iOS: `Configuració → General → Actualització de programari → Actualitzacions automàtiques`
        -   Android: `Configuració → Sistema → Actualització del sistema`
    -   En ordinadors:
        -   macOS: `Configuració del sistema… → General → Actualització de programari → Actualitzacions automàtiques`
        -   Windows 11: `Inici → Configuració → Actualització de Windows → Opcions avançades`
        -   Windows 10: `Configuració → Actualització i seguretat → Actualització de Windows → Opcions avançades`En ordinadors:macOS: Preferències del sistema… → General → Actualització de programari → Actualitzac
-   **Comproveu la configuració d'actualitzacions de la botiga d'aplicacions principal del vostre dispositiu:**
    -   iOS: `Configuració → App Store → Descàrregues automàtiques: Actualitzacions d'aplicacions`
    -   Android: Obre `la Play Store`, després ves a `Configuració → Actualitzar automàticament les aplicacions`
    -   macOS: Obre `l'App Store` i després ves a `Configuració → Actualitzacions automàtiques`
    -   Windows 10/11: Obriu la `Microsoft Store`, després aneu a `Perfil → Configuració → Actualitzacions d'aplicacions`.
-   **Assegura't que el sistema operatiu del teu dispositiu encara pugui rebre actualitzacions:**
    -   Si han passat més de tres anys des que vas comprar el telèfon o l'ordinador, val la pena comprovar que encara reps actualitzacions.
        -   Per a telèfons: cerqueu [el vostre dispositiu a endoflife.date](https://endoflife.date/tags/device) i assegureu-vos que encara aparegui com a «compatible».
        -   Per a macOS: Esbrina quin sistema operatiu estàs utilitzant. Fes clic al logotip d'Apple a la cantonada superior esquerra i, a continuació, `a «Sobre aquest Mac`». Després, assegura't que a [aquesta pàgina d'endoflife.date](https://endoflife.date/macos) encara indiqui «Estat del servei: Sí».
        -   Per a Windows: Descobreix quin sistema operatiu estàs utilitzant. `Inici → Configuració → Sistema → Sobre.` A continuació, assegura't que encara rep suport de seguretat a [aquesta pàgina d'endoflife.date](https://endoflife.date/windows).
    -   Si ja no rep actualitzacions:
        -   Assegura't que has actualitzat a l'últim sistema operatiu que funciona al teu dispositiu. De vegades, una actualització es paralitza per falta d'espai al disc. (Hauràs rebut avisos sobre això si has seguit els passos anteriors.) O, en el cas de Windows, pot ser que hagis de comprar la nova edició.
        -   Comenceu a investigar quin dispositiu voleu adquirir. De moment, però, seguiu la resta d'aquesta llista de comprovació per actualitzar tot el que falti.

---

_👍 Excel·lent! Aquests passos senzills realment et mantindran segur la major part del temps. Pensa que és com tenir una bona i sòlida porta de seguretat a la porta d'entrada. No és infal·lible, però mantindrà casa teva segura la major part del temps. Continua per assegurar els petits detalls que més endavant es podrien convertir en vulnerabilitats._

---

## 🏃🏻‍♂️ Nivell 2: Seguritzeu tots els petits detalls

### 🧠 Utilitza contrasenyes difícils de endevinar per als comptes importants

Els atacants solen accedir al vostre compte si la vostra contrasenya és:

1.  Massa curt.
2.  Massa fàcil de endevinar.
3.  Ja s'ha filtrat com a part d'una violació de dades/incident de pirateig i fas servir la mateixa contrasenya en diferents llocs.

Per tant, és crucial utilitzar una contrasenya diferent per a cada compte i assegurar-vos que siguin molt llargues i molt difícils de endevinar. Per ajudar a crear i emmagatzemar aquestes contrasenyes llargues, podeu:

1.  Utilitza aplicacions de gestor de contrasenyes.
2.  Inventa la teva pròpia fórmula que sigui un joc de paraules amb el servei al qual t'hi connectes.
3.  Escriu-les amb bolígraf i paper.

El que funciona millor és diferent per a tothom, i no cal que t'adheris a una sola opció: pots combinar-les com vulguis. Per a una explicació més detallada i completa de les tres opcions, consulta l'article de Michael Horowitz [«The world's BEST password advice](https://michaelhorowitz.com/BestPasswordAdvice.php) ».

De moment, **centra't a assegurar-te que els comptes importants que vas identificar al Nivell 1 tinguin contrasenyes llargues, úniques i difícils de endevinar**. A continuació, tens una guia pas a pas de les tres opcions:

##### Opció 1: instal·lar un gestor de contrasenyes (recomanat)

Aquesta és una opció popular per a les persones que se senten còmodes navegant per paràmetres i finestres emergents addicionals. Una aplicació gestor de contrasenyes ajuda a generar contrasenyes llargues, les emmagatzema i les omple gairebé automàticament quan inicies la sessió en un lloc web.

-   **Gestors de contrasenyes recomanats:**
    -   [1Password](https://1password.com/) 💰
    -   [Bitwarden](https://bitwarden.com/)
-   **No recomanem els gestors de contrasenyes que vénen amb el sistema operatiu o el navegador web** perquè no funcionen fora del seu ecosistema (p. ex., Apple Passwords no funcionarà en un telèfon Android).
-   **Instal·la l'aplicació del gestor de contrasenyes** tant al telèfon com a l'ordinador.
-   **Instal·la l'extensió del gestor de contrasenyes** al navegador web del teu ordinador.
-   **Creeu només contrasenyes de més de 12 caràcters.** Recomanem utilitzar l'opció del gestor de contrasenyes que combina paraules aleatòries i sense relació entre si (p. ex., `planta-camió-nas-estructura-puntes`) perquè sigui fàcil escriure-les en aquells casos poc habituals en què l'emplenament automàtic no funciona.
-   **La propera vegada que hagis de teclejar la contrasenya d'un altre compte, crea-hi una entrada.** D'aquesta manera, aniràs afegint gradualment qualsevol compte que facis servir sovint al gestor de contrasenyes. Si ho fas a l'ordinador, l'extensió/add-on del navegador del gestor de contrasenyes capturarà les dades automàticament després que les teclegis.
-   **Fixa't que l'aplicació vincula la informació d'inici de sessió a l'URL.** Per tant, si ets en un lloc web i el gestor de contrasenyes no té cap entrada per a ell, vigila especialment que no sigui un lloc web de suplantació d'identitat (phishing).
-   **Transferiu tots els vostres comptes més endavant.** Introduir tots els vostres comptes al gestor de contrasenyes trigarà una estona, i és una tasca que és millor deixar per a un altre dia. (Hem col·locat aquesta tasca que porta temps al nostre `Nivell 3`.)
-   **No utilitzis el gestor de contrasenyes com a aplicació d'autenticació de dos factors.** És millor no posar tots els ous en una mateixa cistella.

##### Opció 2: utilitzar una fórmula

Aquesta opció la fan servir habitualment les persones amb una bona memòria i les que prefereixen tenir menys aplicacions per gestionar i menys finestres emergents per tocar als seus dispositius.

Aquí teniu un exemple d'una fórmula senzilla de [la llista de comprovació de Computació Defensiva](https://defensivecomputingchecklist.com/indexold.php#passwoyds):

> …un aficionat al beisbol podria començar cada contrasenya amb «BaseballRules!». Aleshores, si «jungle» fos la seva contrasenya per a Amazon.com, la contrasenya real seria «BaseballRules!jungle». I l'únic que hauries de recordar seria que la teva contrasenya d'Amazon és «jungle». Bastant fàcil. Amazon. Jungle. I la miserable contrasenya "book" per a Barnes and Noble es converteix en una bona contrasenya ("BaseballRules!book") quan s'aplica la fórmula.

Afegiu alguns signes de puntuació, guions i números per fer la contrasenya una mica més llarga i irregular, i tindreu una fórmula de contrasenya força sòlida.

##### Opció 3: Fer servir bolígraf i paper

Aquesta opció sol complementar les altres dues i és útil per a les persones que gairebé mai no perden objectes (físics). Escriure en paper és especialment útil si utilitzeu una fórmula i voleu apuntar algunes pistes sobre les fórmules que heu utilitzat.

De fet, les aplicacions de gestió de contrasenyes animen la gent a imprimir un full de paper amb un codi de recuperació de compte i a escriure-hi la seva contrasenya mestra. Aquí teniu les instruccions per a:

-   1Password: [Coneix el teu Kit d'Emergència](https://support.1password.com/emergency-kit/)
-   BitWarden: [Còdigos de recuperació](https://bitwarden.com/help/two-step-recovery-code/#get-your-recovery-code) (afegeix la teva contrasenya mestra després d'imprimir)

Intenta tenir una còpia de seguretat d'aquests documents en un segon lloc.

### 🧑‍🔬 Configura codis de recuperació per als teus comptes importants

Aquests codis són contrasenyes d'un sol ús i molt llargues que et permeten iniciar la sessió al teu compte si perds els dispositius. És possible que se t'hagi demanat que creessis un codi de recuperació quan vas configurar l'autenticació de dos factors. Són útils per tenir-los en cas d'emergència. Les maneres segures d'emmagatzemar-los inclouen:

-   Imprimir una còpia en paper i guardar-la en un lloc privat
-   Copiar i enganxar en un fitxer que després es guarda en una carpeta protegida amb contrasenya al vostre ordinador (si no sabeu com fer-ho, us ensenyarem el nostre mètode preferit al Nivell 4)
-   Si utilitzeu un gestor de contrasenyes, podeu desar-hi com a nota

Esbrina si el teu compte admet codis de recuperació fent una cerca a Internet de "codis de recuperació" juntament amb el nom del teu compte. Instruccions per a:

-   [Google (incloent-hi Gmail)](https://support.google.com/accounts/answer/1187538?hl=en)
-   [Instagram](https://www.facebook.com/help/1006568999411025/)
-   [Facebook](https://www.facebook.com/help/148104135383285/)
-   [Apple (inclòs iCloud)](https://support.apple.com/en-us/109345)
-   [Proton Mail](https://proton.me/support/set-account-recovery-methods#how-to-enable-a-recovery-phrase)
-   [Tuta Mail](https://tuta.com/support#recovery)

### 📱 Segureu els vostres dispositius

#### Segureu el telèfon

-   **Utilitza un codi de bloqueig no comú ni obvi per al teu telèfon amb almenys 10 dígits.** Recomanem utilitzar una sèrie llarga de números, ja que és més fàcil de teclejar, però també funciona utilitzar tant lletres com números. No obstant això, no es recomana el patró de lliscada, ja que és massa fàcil de replicar per a les persones que t'observen.
    -   Per canviar-lo:
        -   iOS: `Configuració → Face ID i codi d'accés → Canvia el codi d'accés`
        -   Android: `Configuració → Seguretat → Bloqueig de pantalla`
-   **Configureu un codi PIN per a la targeta SIM del telèfon mòbil:**
    -   Instruccions per a:
        -   [iPhone](https://support.apple.com/en-us/118228)
        -   [Android](https://www.androidpolice.com/enable-sim-lock-android-phone-protection/).
    -   Si et demana un codi PIN de la SIM i no recordes haver-ne configurat cap, pot ser que l'operador hagi establert-ne un per defecte. Ves al lloc web del teu operador de telefonia mòbil per esbrinar quin és.
-   **No permetis que accessoris USB controlin un dispositiu bloquejat:**
    -   iOS: Desactiva `Configuració → Face ID i codi d'accés → Permet l'accés quan està bloquejat: Accessoris USB`.
    -   Android: la configuració està desactivada per defecte i només està disponible si `les Opcions de desenvolupador` estan activades.
-   **Activa les funcions antirrobatori del teu telèfon:**
    -   iOS: `Configuració Face ID i codi d'accés → Protecció contra robatori de dispositiu`
    -   Android: `Configuració → Seguretat i privacitat → Altres configuracions: Més seguretat i privacitat → Seguretat: Protecció contra robatori`
-   **Activa el seguiment dels teus dispositius per si els perds,** la qual cosa et permet localitzar-los i esborrar-los de forma remota iniciant sessió en un lloc web si els perds.
    -   Instruccions per a:
        -   [iOS i macOS](https://support.apple.com/en-us/HT210400) (Trobar el meu)
        -   [Android](https://support.google.com/android/answer/6160491?hl=en) (Find Hub)
        -   [Windows](https://support.microsoft.com/en-us/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316) (Trobar el meu dispositiu)
-   **Desactiva la connectivitat 2G al teu telèfon (només Android)**. La tecnologia de xarxa mòbil 2G està obsoleta i té vulnerabilitats de seguretat que permeten als estafadors enviar missatges de text falsos. Per desactivar-la a Android:
    
    -   `Configuració → Xarxa i Internet → Tarjetes SIM → [Nom del teu operador] → Permet 2G: Desactivat`
    -   Si aquesta opció no apareix, obriu l'aplicació Telèfon i introduïu `*#*#4636#*#*.` Apareixerà una pantalla `de proves`. Seleccioneu `Informació del telèfon` i després canvieu el `camp Tipus de xarxa preferit` al mateix que la selecció actual, però sense `GSM`. Per veure què significa cada acrònim, consulteu [la pàgina](https://en.wikipedia.org/wiki/Comparison_of_mobile_phone_standards#Comparison_of_wireless_Internet_standards) de la Viquipèdia [«Comparació dels estàndards sense fil](https://en.wikipedia.org/wiki/Comparison_of_mobile_phone_standards#Comparison_of_wireless_Internet_standards)».
-   **Per als dispositius Android, assegura't que Google Play Protect estigui activat** si fas servir la Google Play Store:
    
    -   A l'aplicació Google Play: icona de perfil `→ Play Protect → Configuració → Analitza les aplicacions amb Play Protect`

#### Protegiu l'ordinador

-   **Activa el tallafocs del teu ordinador:**
    -   macOS: `Preferències del sistema → Seguretat i privadesa → Tallafocs`.
    -   Windows 10/11: `Inici → Configuració → Actualització i seguretat → Seguretat de Windows → Tallafocs i protecció de xarxa → Tallafocs de Microsoft Defender: Activat`
-   **Desactiva l'accés remot del teu ordinador:**
    -   macOS: `Preferències del sistema → Compartició → Inici de sessió remot, Gestió remota`.
    -   Windows 10/11: `Configuració → Sistema → Escriptori remot → Escriptori remot: Desactivat`.
-   **Configura un programari antivirus bàsic al teu ordinador:**
    -   macOS: No cal res.
    -   Windows 10/11: `Inici → Configuració → Actualització i seguretat → Seguretat de Windows → Protecció contra virus i amenaces`
-   **Si utilitzeu Microsoft Office: desactiveu els macros.** Els macros són fragments petits de codi que automatitzen accions que poden ser explotades per atacants. Tot i això, de vegades poden ser útils, per això recomanem l'opció `Desactiva tots els macros amb notificació`, que us permet executar manualment macros de fonts de confiança.
    -   Instruccions per a:
        -   [macOS](https://support.microsoft.com/en-us/office/enable-or-disable-macros-in-office-for-mac-c2494c99-a637-4ce6-9b82-e02cbb85cb96)
        -   [Windows](https://support.microsoft.com/en-us/office/macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6), que pot requerir [configuracions especials per a l'Excel](https://support.microsoft.com/en-us/office/change-macro-security-settings-in-excel-a97c09d2-c082-46b8-b19f-e8621e8fe373)

#### Seguritzeu el router Wi-Fi de casa

-   **Inicieu la sessió al tauler d'administració i configuració.** Normalment s'hi pot accedir anant a `http://192.168.0.1` al vostre navegador web. Si no, consulteu les instruccions que van amb el vostre encaminador.
-   **Actualitzeu la informació d'inici de sessió del panell de control si la contrasenya és senzilla.**
-   **Revisa els dispositius que estan connectats actualment a la teva xarxa.** Potser hauràs d'explorar fins que trobis el `control d'accés`. Assegura't de saber què és cada dispositiu de la llista.
-   **Desactiva les opcions següents si les veus.** (Busca-les a `la configuració avançada` o a `les funcions de passarel·la`):
    -   UPnP (Universal Plug and Play)
    -   WPS (Wi-Fi Protected Setup)
    -   Gestió remota
-   **Comproveu si hi ha actualitzacions de programari.** Cerqueu les seccions etiquetades com a `manteniment`, `firmware` o `actualització del sistema`. No us preocupeu si no la veieu: això vol dir que està actualitzat o que les actualitzacions automàtiques estan activades per defecte.

### 🔑 Xifra les dades dels teus dispositius

_Recorda, el xifratge només és totalment eficaç quan el dispositiu està apagat!_

-   **Xifra el disc dur del teu ordinador.**
    -   Instruccions per a:
        -   [macOS](https://support.apple.com/en-us/HT204837).
        -   [Microsoft Windows](https://support.microsoft.com/en-us/windows/device-encryption-in-windows-10-ad5dcf4b-dbe0-2331-228f-7925c2a3012d) (utilitzeu [BitLocker](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) si està disponible).
-   **Xifra l'emmagatzematge del telèfon.**
    -   iOS: Xifra automàticament.
    -   Android: Gairebé sempre xifra automàticament. Verifica-ho anant a `Configuració → Seguretat → Xifratge`.
-   **Xifra els teus discs durs de còpia de seguretat.**
    -   Instruccions per a:
        -   [macOS (si utilitzeu Time Machine)](https://support.apple.com/en-ca/guide/mac-help/mh21241/mac)
        -   [Microsoft Windows](https://web.archive.org/web/20250123165604/https://techjury.net/blog/how-to-encrypt-your-hard-drive/)

### 🗓️ Atura les invitacions malicioses al calendari

Evita que les invitacions de calendari de persones que no coneixes apareguin automàticament al teu calendari; aquestes invitacions es poden utilitzar per enviar enllaços maliciosos.

-   [Configuració de](https://calendar.google.com/calendar/r/settings) Google Calendar `→ Configuració d'esdeveniments → Afegeix les invitacions al meu calendari: Quan responc a la invitació per correu electrònic`
-   Outlook: `Fitxer → Opcions → Calendari → Acceptació o rebuig automàtics → Acceptar/Rebre automàticament i Suprimir les reunions cancel·lades`
-   iCloud: A iOS: Ves a `Configuració → [El teu nom] → iCloud → Dades emmagatzemades a iCloud: Veure-ho tot → Calendari iCloud → Enviar i rebre → Rebre` i selecciona `Correu electrònic` per a cada compte.

---

_👍👍 Enhorabona! T'has endinsat sense por a la configuració —fent clic, tocant i lliscant— per tancar les llacunes de seguretat dels teus comptes i dispositius. Ara la següent secció tracta sobre aprendre i revisar els teus hàbits i reflexos pel que fa a la seguretat digital, així que serà principalment de lectura i reflexió (en lloc de tocar/fer clic als teus dispositius). No obstant això, encara recomanem que facis una pausa ara mateix perquè et mereixes de debò el que et queda de dia lliure._

---

## 💪🏽 Intermissió: Revisió d'hàbits i reflexos

### 🎣 Vigileu amb els intents de suplantació d'identitat (phishing)

Un frau de phishing és un correu electrònic o un missatge de text en què un atacant intenta enganyar-te perquè li donis la teva contrasenya o altres dades d'inici de sessió. Per defensar-te:

-   **Confia en la teva intuïció.** Si sents que alguna cosa no va bé —ja sigui per la manera com està escrit el text, l'aspecte dels gràfics o una sol·licitud inusual per primera vegada d'un proveïdor de serveis—, probablement ho sigui.
-   **Verifiqueu qui ho envia.** Reviseu el nom de l'emissor, el número de telèfon o l'adreça de correu electrònic. Si és un correu electrònic, assegureu-vos de llegir atentament la part que ve després del símbol `@`.
-   **Però recorda que les dades de l'emissor es poden falsificar.** Passa rarament, però tècnicament és possible posar un nom, una adreça de correu electrònic o un número de telèfon fals. Per tant, comprovar les dades de l'emissor no és un procés 100 % fiable.
-   **Pensa-t'ho dues vegades abans de fer clic en un enllaç.** Quan tinguis dubtes, examina atentament el domini de l'enllaç. Per veure'l sense obrir l'enllaç:
    -   En dispositius mòbils:
        -   iOS: Premeu i manteniu premut un enllaç. Apareixerà una miniatura de la destinació. A la part superior dreta d'aquesta finestra emergent, premeu `Oculta la previsualització`. A partir d'aleshores, l'iOS mostrarà l'URL complet cada vegada que premeu i manteniu premut un enllaç.
        -   Android: Mantingueu premut un enllaç.
    -   En ordinador:
        -   Firefox, Chrome, Edge: Quan el cursor del ratolí es posa sobre un enllaç o botó, l'URL complet apareixerà a la part inferior esquerra.
        -   macOS Safari: Per activar aquesta funció, aneu a `Visualització → Mostra la barra d'estat`
        -   macOS Mail: Passa el cursor del ratolí per sobre d'un enllaç i espera uns segons que aparegui un missatge emergent.Per tant, si teniu cap dubte, no feu clic a l'enllaç. En gairebé tots els casos, de fet no cal que f
-   **Després de fer clic en enllaços, escaneja la barra d'adreces URL del teu navegador web.**
    -   Hi ha una icona d'advertiment vermella o una etiqueta de 'No segur'? Això significa que el lloc web s'està executant sense xifrar en `http` (en lloc `d'https`).
    -   L'adreça de domini està mal escrita?
-   **Així que si teniu cap dubte, no feu clic a l'enllaç.** En gairebé tots els casos, de fet no cal que feu clic a l'enllaç. Si el missatge està vinculat a una transacció o un compte, sempre podeu anar al lloc web original per consultar-ne els detalls.

### 🗄️ Vigileu amb els fitxers adjunts

-   **No descarregueu ni obriu adjunts innecessaris.**
    -   En cas de dubte, respon a l'enviament original per preguntar què és.
    -   Al correu electrònic, previsualitza els fitxers adjunts dins de l'aplicació o el lloc web. A Gmail i Proton Mail, simplement fent clic a l'adjunt es mostra la seva previsualització, que s'executa en un entorn segur dins del programa de correu.
    -   Demana al remitent que utilitzi un servei d'intercanvi de fitxers (Dropbox, Google Drive, Tresorit), que també tenen el seu propi sistema de previsualització en línia.
-   **Pugeu els fitxers adjunts sospitosos a [VirusTotal](http://www.virustotal.com)** perquè els analitzin. _Tingueu en compte que els fitxers enviats a VirusTotal es poden compartir amb diversos investigadors de seguretat, així que no envieu informació sensible._

### 🫡 Digues sí a les actualitzacions

-   **Sistemes operatius dels dispositius:** si rebeu una notificació als vostres dispositius per actualitzar el sistema operatiu, feu-ho com més aviat millor.
-   **Aplicacions:** si veus notificacions sobre actualitzacions disponibles, fes-les i actualitza l'aplicació.
-   **Actualitzacions del firmware:** Comproveu ocasionalment si hi ha actualitzacions del firmware per al vostre encaminador i altres dispositius connectats a Internet.

### 🙅🏾 No ho facis a casa (ni enlloc)

-   **No carreguis el telèfon en estacions o ports de càrrega públics.** Suposen un risc perquè els atacants podrien robar-te les dades. En lloc d'això, utilitza una bateria externa o porta el teu propi adaptador per connectar-lo directament a la presa de corrent.
-   **No connectis a l'ordinador memòries USB o unitats d'emmagatzematge que no coneguis.** Poden contenir programari maliciós.
-   **No introduïu contrasenyes en navegadors integrats a l'aplicació.** Quan una aplicació mòbil us permet navegar per una pàgina web sense obrir el navegador web (és a dir, un navegador integrat a l'aplicació), l'aplicació pot registrar els llocs web que visiteu i el que hi escriviu. Per tant, no hi escriviu res de sensible.
-   **No utilitzis Google/X/Twitter/Facebook per registrar-te o iniciar sessió en altres serveis,** ja que això proporciona a aquestes plataformes dades innecessàries sobre tu. Cada servei hauria de tenir el seu propi compte.

### 🏊🏼‍♀️ Altres hàbits saludables

-   **Reinicia el telèfon i l'ordinador un cop per setmana apagant-los i tornant-los a engegar** per netejar la memòria temporal (RAM) i perquè funcionin més fluidament.
-   **Quan descarregues una nova aplicació mòbil, comprova-ho dues vegades per confirmar que és la correcta.** Moltes aplicacions falses enganyen la gent fent servir un nom o una icona lleugerament modificats d'una aplicació existent i popular.
-   **Revisa regularment les aplicacions instal·lades al teu telèfon.** Elimina les que ja no fas servir.
-   **Eixa adequadament els teus dispositius abans de donar-los o regalar-los.** Si has xifrat els teus telèfons i ordinadors (com s'ha suggerit abans), un restabliment de fàbrica estàndard funcionarà en la majoria de casos.
    -   Si voleu una capa de seguretat addicional per a les unitats de disc del vostre ordinador, consulteu [la guia de Wired sobre aquest tema](https://www.wired.co.uk/article/securely-wipe-android-iphone-hard-disk).
-   **Has de enviar una contrasenya a algú? Separa-la per la meitat i envia-la per dos canals diferents.** Per exemple, envia la meitat de la contrasenya per correu electrònic i l'altra meitat per trucada de veu.

### 🆘 Informeu-vos sobre la funció SOS d'emergència del vostre telèfon

-   iOS: `Configuració → SOS d'emergència`
-   Android: `Configuració → Seguretat i emergència → SOS d'emergència`

---

_🥳 La seguretat digital té tant a veure amb les coses que fas cada dia com amb la configuració dels teus dispositius i aplicacions. No dubteu a tornar més endavant per revisar aquests hàbits i reflexos; no esperem que ningú se'ls aprengui de memòria a la primera lectura. Ara, la nostra següent secció tracta sobre com millorar la vostra privacitat digital, i és un tema dens perquè, a cada cantonada, hi ha alguna empresa que intenta recollir i vendre les nostres dades al millor postor. Esperem que estigueu a punt per recuperar (una part del) control de les vostres dades!_

---

## 🧗🏿‍♀️ Nivell 3: Millora la teva privacitat digital

### ⚙️ Ajusta amb precisió la configuració de la teva privacitat

#### A les xarxes socials i a les aplicacions de missatgeria

-   **Revisa la configuració de privacitat de les xarxes socials i les aplicacions de missatgeria que fas servir sovint.** Comprova qui pot veure el teu contingut, quina informació teva es fa pública i què comparteixes amb aplicacions de tercers o anunciants.
-   **Sempre que sigui possible, desactiva els rebuts de lectura a les aplicacions de missatgeria.** Al principi pot semblar incòmode, però a la llarga tindràs més privacitat i llibertat quan la gent _no_ sàpiga si has llegit els seus missatges o no.
-   Aquí teniu enllaços i instruccions per a les plataformes/aplicacions més utilitzades:
    -   **Plataformes/aplicacions amb configuració de privacitat disponible a través d'un navegador d'escriptori:**
        -   Facebook: [Revisió de la privacitat](https://www.facebook.com/privacy/checkup/)
        -   Google: [Revisió de la privacitat](https://myaccount.google.com/intro/privacycheckup)
        -   YouTube: [Confidencialitat de la compte](https://www.youtube.com/account_privacy)
        -   X/Twitter: [Privacitat i seguretat](https://twitter.com/settings/privacy_and_safety)
        -   Reddit: [Seguretat i privacitat](https://www.reddit.com/settings/privacy)
    -   **Plataformes/aplicacions amb configuració de privacitat només disponible completament a través de la seva aplicació mòbil:**
        -   Instagram: `Configuració → Privadesa`
        -   WhatsApp: `Configuració → Compte → Privacitat`
        -   Snapchat: `Configuració → Controls de privacitat`
        -   TikTok: `Perfil → Configuració i privacitat → Privacitat`
        -   Telegram: `Configuració → Privacitat i seguretat`
-   **Limita com Facebook et fa un seguiment en altres llocs web** eliminant i desconnectant [l'activitat fora de Facebook](https://www.facebook.com/off_facebook_activity).

#### En comptes de correu electrònic i de xarxes socials

-   **Revisa `les aplicacions de tercers` o `les aplicacions connectades` vinculades a les principals plataformes de xarxes socials/correu electrònic.** Aquestes aplicacions de tercers/connectades tenen accés a les teves dades i podrien estar-les venent. Instruccions per a:
    -   [Google](https://support.google.com/accounts/answer/3466521?hl=en)
    -   [Facebook](https://www.facebook.com/help/211829542181913)
    -   [Instagram](https://www.facebook.com/help/instagram/1144624522593085)
    -   [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps)

#### En comptes de correu electrònic

-   **Evita que les imatges es carreguin automàticament als teus correus electrònics**, perquè les empreses les utilitzen com una manera de fer-te un seguiment.
    -   Gmail: A l'ordinador, feu clic a Configuració `⚙️ → Totes les configuracions → General: Imatges: Demanar abans de mostrar imatges externes`. Per als remitent de correus electrònics de confiança, sempre podeu fer clic `a Sempre mostra imatges d'un` correu electrònic seu. Per revertir aquesta decisió, heu de fer clic al petit triangle orientat cap avall `que hi ha` al costat `de "de"` a la part superior del correu electrònic.
    -   Proton Mail: No cal, ja que tenen una funció que carrega les imatges als seus propis servidors abans d'enviar-t'les. [Més informació aquí](https://proton.me/support/protonmail-images).
    -   Tuta Mail: La càrrega d'imatges està desactivada per defecte, però podeu activar la càrrega automàtica d'un remitent a la vegada. Al missatge de descàrrec de responsabilitat `de càrrega automàtica d'imatges` que apareix a sota de la informació del remitent, feu clic `a Sempre confiar en el remitent` (al mòbil, primer feu clic `a Més`). Per revertir aquesta decisió, feu clic/toc a les tres punxes a la cantonada superior dreta i després feu clic/toc `a Bloqueja el contingut extern`.

#### Al teu telèfon

-   **Revisa quines aplicacions del teu telèfon intel·ligent tenen accés a les teves dades de localització.** Desactiva l'accés per a les aplicacions que no el necessiten i minimitza el nombre d'aplicacions que rastregen la teva ubicació.
    -   iOS: `Configuració → Privacitat i seguretat → Serveis de localització`
    -   Android: `Configuració → Ubicació → Permisos de ubicació de les aplicacions`
-   **Desactiva el teu identificador publicitari únic** perquè els anunciants no et puguin localitzar tan fàcilment:
    -   iOS: `Configuració → Privacitat i seguretat → Rastreig → Permetre que les aplicacions sol·licitin fer un seguiment: Desactivat`
    -   iOS: `Configuració → Privacitat i seguretat → Publicitat d'Apple → Anuncis personalitzats: Desactivat`
    -   Android: `Configuració → Seguretat i privacitat → Privacitat → Anuncis → Esborra l'identificador d'anuncis`Suprimeix qualsevol aplicació que no reconeixis o que no hagis utilitzat en molt de temps. Sempre le
-   **A iOS, desactiva la configuració que permet a les aplicacions fer un seguiment de la teva activitat en altres aplicacions i llocs web:**
    
    -   `Configuració → Privadesa i seguretat → Rastrejament → Permetre que les aplicacions sol·licitin rastrejar: Desactivat`
-   **A Android, desactiva l'escaneig passiu de Wi-Fi i Bluetooth.**
    
    -   `Configuració → Ubicació → Serveis de ubicació → Escaneig de Wi-Fi`
    -   `Configuració → Ubicació → Serveis de ubicació → Escaneig de Bluetooth`
-   **Elimina qualsevol aplicació que no reconeixis o que no hagis utilitzat des de fa molt de temps.** Sempre les pots tornar a descarregar si cal, tot i que hi ha algunes aplicacions que vénen amb el sistema operatiu i que no es poden eliminar.
    -   **Assegura't de buscar també aplicacions ocultes.** Instruccions per a:
        -   iOS: A la pantalla d'inici, continua lliscant cap a l'esquerra fins que arribis a la pantalla `de la Biblioteca d'aplicacions`. Desplaça't fins a la part inferior, al grup `Ocultat`. Toca per obrir-lo i desbloqueja'l amb Face ID o codi d'accés.
        -   Android: Vegeu totes les aplicacions, incloses les ocultes, a `Configuració → Aplicacions → Veure totes les aplicacions`
-   **Elimina els teclats de tercers del teu telèfon.** Sovint comparteixen el que escrius amb el fabricant del programari.
    -   Aquests teclats s'instal·len com a aplicacions a iOS i Android, així que dedica temps a revisar totes les aplicacions instal·lades per trobar-los i eliminar-los.
    -   Si necessites utilitzar un teclat de tercers, assegura't que sigui un projecte de codi obert que altres hagin verificat i que no comparteixi les teves dades amb tercers.

#### Al teu ordinador

-   **Desactiva el seguiment publicitari als ordinadors amb Windows.** Instruccions per a:
    -   [Windows 10](https://privacyinternational.org/guide-step/4344/opt-out-targeted-ads-windows)
    -   [Windows 11](https://www.pcmag.com/how-to/how-to-remove-annoying-ads-from-windows-11)

#### En altres dispositius connectats a Internet

-   **Si us preocupa la privacitat, no utilitzeu Amazon Echo (altaveus) ni Ring (sistema de seguretat domèstic).** Tots dos tenen un historial de violacions de la privacitat. Si ja en teniu, aquí teniu algunes mesures de mitigació:
    -   Amazon Echo: Desactiva les comandes de veu prement el botó físic que sembla un cercle amb una línia travessada. Altrament, tot el que diguis s'enviarà als seus sistemes en el núvol per a l'anàlisi.
    -   Amazon Echo i Ring: Desactiva la funció "Amazon Sidewalk" que comparteix la teva connexió a Internet amb desconeguts seguint [aquestes instruccions](https://allaboutcookies.org/opt-out-amazon-sidewalk).
-   **Considereu desactivar els comandaments per veu als vostres altaveus intel·ligents.** Els comandaments per veu poden ser una comoditat, però només funcionen perquè s'envien fragments d'àudio als servidors del fabricant del dispositiu per processar el que heu dit.
-   **Si les ordres de veu són importants per a tu, aquí tens algunes maneres de tenir certa privacitat amb elles:**
    -   **Google Nest:** aneu a [Controls d'activitat](https://myaccount.google.com/activitycontrols/audio) de Google Home i desmarqueu `Inclou enregistraments d'àudio`.
    -   **Apple HomePod:** al telèfon vinculat a l'altaveu, aneu a: `aplicació Home → [icona de l'HomePod] → Configuració de l'accessori → Anàlisi i millora` i desactiveu totes les opcions.
    -   **Sonos:** Consulteu [les suggerències de la Fundació Mozilla](https://www.mozillafoundation.org/en/privacynotincluded/sonos-smart-speakers/).
-   **Per a les televisors intel·ligents, assegura't d'inactivar la funcionalitat de seguiment de dades del fabricant,** també coneguda com a reconeixement automàtic de contingut (ACR).
    -   Instruccions de: [Consumer Reports](https://www.consumerreports.org/privacy/how-to-turn-off-smart-tv-snooping-features-a4840102036/)

### 🕸️ Actualitza el navegador web del teu telèfon i del teu ordinador

-   **Canvia el navegador si fas servir Chrome o Edge,** tots dos tenen un historial pèssim pel que fa a la protecció de la teva privacitat.
    
    -   Per a iOS: utilitzeu Safari.
    -   Per a macOS: instal·la [el Firefox](https://www.firefox.com) o fes servir el Safari.
    -   Per a Android/Windows: instal·la [el Firefox](https://www.firefox.com).
-   **Revisa la configuració de privacitat del teu navegador web**
    
    -   Al teu mòbil:
        -   Safari d'iOS: `[iOS] Configuració → Aplicacions → Safari → Privacitat i seguretat`. Assegura't que els opcions `«Evita el seguiment entre llocs` », `«Amaga l'adreça IP»` i `«Advertiment de llocs web fraudulents»` estiguin activades.
        -   Firefox per a Android: `[Firefox] Configuració → Privacitat i seguretat`, activa `el mode només HTTPS` i `la protecció reforçada contra el seguiment`.
    -   Al teu ordinador:
        -   Safari de macOS: `Preferències → Privadesa`, marqueu les caselles de `Seguiment de llocs web` i `Amaga l'adreça IP`
        -   Firefox per a macOS/Windows: `Preferències → Privadesa i seguretat`, activa `la Protecció de seguiment millorada` (qualsevol opció), `No em segueixis` i `el Mode només HTTPS` (desplaça't fins a la part inferior).Per a macOS/Windows: Mullvad Browser
-   **Instal·leu aquestes extensions/components addicionals per al navegador web** per bloquejar anuncis intrusius i seguidors si el vostre navegador els admet. Assegureu-vos que estiguin actives fins i tot en mode privat/incògnit.
    -   [uBlock Origin](https://ublockorigin.com/)
    -   [uBlock Origin Lite](https://github.com/uBlockOrigin/uBOL-home) (si el teu navegador no és compatible amb uBlock Origin)
    -   [Privacy Badger](https://privacybadger.org/)
-   **Revisa les altres extensions/add-ons del teu navegador web.**
    
    -   Comproveu quins permisos/accés té cadascun d'ells:
        
        -   Safari d'iOS: `[iOS] Ajustaments → Aplicacions → Safari → General: Extensions`, després toca l'extensió per veure'n els detalls.
        -   Firefox per a Android: `[Firefox] Configuració → Avançat: Extensions`, després toca l'extensió i, a continuació, toca `Permisos`.
        -   Safari de macOS: barra de menú superior: `Safari → Configuració... → Extensions`
        -   macOS Firefox: Barra de menú superior: `Eines → Extensions i temes`, després feu clic a cada extensió per veure'n més detalls i, a continuació, feu clic a la pestanya `Permissions i dades`.
        -   Firefox per a Windows: `→ Extensions i temes`, després fes clic a cada extensió per veure'n més detalls i, a continuació, fes clic a la pestanya `Permisos i dades`.
    -   Els únics que haurien de poder llegir les dades de la teva pàgina web són:
        
        -   Les nostres recomanacions anteriors (uBlock Origin/uBlock Origin Lite, Privacy Badger)
        -   La teva extensió de gestor de contrasenyes (si fas servir un gestor de contrasenyes al teu ordinador)
        -   Extensions/add-ons fets per la mateixa empresa que el navegador (p. ex. el Facebook Container de Firefox)
    -   Desactiva o elimina qualsevol altra extensió/add-on que tingui accés de lectura.
        
-   **En lloc d'obrir una `finestra privada/incògnita nova` al vostre navegador habitual, feu servir un navegador separat amb més privacitat** quan vulgueu un seguiment mínim. És possible que aquests navegadors no funcionin tan bé per a l'ús diari, però és perquè tenen proteccions addicionals. A més, quan hi ha dues aplicacions separades, és menys probable que barregeu les finestres privades i les no privades.
    
    -   Per a macOS/Windows: [Mullvad Browser](https://mullvad.net/en/browser)
    -   Per a iOS/Android: [Firefox Focus](https://www.firefox.com/browsers/mobile/focus/)

### 📊 Revisa quines dades tenen sobre tu aquestes grans plataformes tecnològiques

Suprimeix tot allò que no necessitis, si hi ha opcions per fer-ho:

-   **Google:** [La meva activitat](https://myactivity.google.com)
-   **Facebook:** [La teva informació de Facebook](https://www.facebook.com/settings?tab=your_facebook_information)
-   **Amazon:** [Configuració de privacitat d'Alexa](https://www.amazon.com/b/?node=19149164011)
-   **Microsoft:** [Privacitat del compte](https://account.microsoft.com/privacy)

### 💪🏽 Revisió d'hàbits i reflexos (edició de privacitat digital)

#### La regla d'or

**Publica menys informació personal en línia.** Això inclou informació que es pot utilitzar per identificar-te, rastrejar-te o estafar-te (adreces, números de telèfon, data de naixement, etc.), així com fotos de casa teva i del teu veïnat.

#### Compte amb el que dius als grups en línia

**No diguis res del que et puguis penedir en un grup «privat»** a Slack, Discord, Facebook, xat de grup de WhatsApp, canal de Telegram o qualsevol fòrum en línia «privat». Vet aquí per què:

1.  **Qualsevol persona del grup pot filtrar les dades.**
2.  **Els administradors solen tenir accés a tot el que hi ha dins del grup,** incloses les missatges eliminades i les missatges directes privades entre dues persones.
3.  **El que dius es pot rastrejar fins al número de telèfon o l'adreça de correu electrònic del teu compte.** Fins i tot si no fas servir el teu nom o la teva foto reals.
    -   Per evitar-ho a Telegram, aneu a `Configuració → Privacitat i seguretat → Número de telèfon` i, a continuació, configureu:
        -   `Qui pot veure el meu número de telèfon` a `Ningú`.
        -   `Qui em pot trobar pel meu número` a `Els meus contactes`.

#### Sàpiga quan el seu nom apareix públicament com a simpatitzant o donant

**Comprova sempre si el teu nom apareix públicament en línia per subscripcions, micromecenatges, peticions i donacions.** Això és especialment rellevant si tens un nom únic.

Algunes plataformes que faciliten aquestes coses sovint tenen configuracions de privacitat, així que el millor és crear-hi un compte per tenir un cert control sobre el que es mostra públicament. Alguns exemples de configuracions de privacitat importants però sovint passades per alt:

-   **Patreon:** `Configuració → Comptes → Privacitat`: Desactiva tant `el Perfil públic complet` com `el Perfil de comunitat`.
-   **Indiegogo:** Al menú, ves a `Les meves campanyes`. Si vols amagar un projecte del teu perfil públic:
    -   A sota `Campanyes que he finançat`, selecciona `Accions: Amaga la contribució`.
    -   Aleshores la pàgina es refresca, però el projecte simplement s'ha desplaçat a `Campanyes que segueixo`. Allà, seleccioneu `Accions: Deixa de seguir`.Patreon: Configuració → Comptes → Privacitat: Desactiva tant el Perfil públic complet com el Perfil
-   **GoFundMe:** Al menú, aneu a `El vostre impacte`. A continuació, aneu a qualsevol campanya que hàgiu donat suport. Allà, a sota `Les vostres donacions`, podeu canviar si el vostre nom apareix públicament.

#### Altres recomanacions

-   **Crea un compte separat amb un pseudònim per deixar ressenyes de negocis locals** (a Google Maps, Yelp, etc.) si n'escrius moltes. Altrament, les ressenyes es mostraran amb el teu nom real i podrien revelar la teva ubicació.
-   **Si teniu un domini web, assegureu-vos que la privacitat WHOIS/de domini estigui activada.** Molts registradors de dominis i proveïdors d'allotjament web ofereixen aquesta funció gratuïtament i la tenen activada per defecte.

---

_👍👍👍 Uf! Dona't un cop de pal, perquè navegar per tot això no ha estat gens fàcil. Però esperem que ara et sentis molt més en control de les dades que envies al món. Les nostres recomanacions no són de cap manera exhaustives, però haurien de proporcionar-vos un nivell de privacitat raonable sense haver de sacrificar la comoditat i la diversió de la tecnologia. De nou, us recomanem que feu un bon descans abans de passar a la següent secció, on presentem els nostres consells i eines preferits per ser més segurs i privats en línia._

---

## 🤾🏻‍♀️ Nivell 4: Consells i eines per fer més coses

### 🔐 Afegeix un pany addicional als fitxers sensibles

-   **Identifica els fitxers als quals no vols que altres hi accedeixin.** Això pot incloure fotos privades, escanejats del passaport i documents financers.
-   **Per als fitxers del vostre ordinador, creeu una caixa forta xifrada i protegida per contrasenya per als vostres fitxers:**
    -   Eina recomanada: [Cryptomator](https://cryptomator.org/).
    -   Demanar el vostre cofre al núvol o al vostre ordinador està bé. Decidiu segons com vulgueu fer còpies de seguretat del cofre.
    -   Mou els teus fitxers a aquesta caixa forta segura. Assegura't d'esborrar les còpies originals un cop hagin estat traslladades a la caixa forta.
-   **Per als documents del telèfon, hi ha diverses opcions:**
    -   Crea un cofre similar amb una aplicació com [Cryptomator](https://cryptomator.org/)(💰 per a mòbils).
    -   Si tens un pla de pagament per a un gestor de contrasenyes, les aplicacions també et permeten desar fitxers en una secció anomenada `documents` o `adjunts`. 💰
    -   L'aplicació Files d'iOS té una funció `de bloqueig de PDF` per a fitxers individuals.
    -   Android Files by Google et permet crear una `carpeta segura` [seguint aquestes instruccions](https://support.google.com/files/answer/9935264).
-   **Per a les fotos i vídeos del telèfon, utilitzeu les funcions de les aplicacions de fotos predeterminades:**
    -   Fotos d'iOS: obriu la foto i toqueu el botó `…` a la part superior dreta. Toqueu `Amaga`. Això posarà la foto en una carpeta `Amagada` a l'aplicació Fotos (a sota `d'Utilitats`) que només es pot desblocar amb FaceID o un codi d'accés.
    -   Android Google Photos: [Segueix aquestes instruccions](https://support.google.com/photos/answer/10694388?co=GENIE.Platform%3DAndroid&oco=1) i llegeix amb atenció la secció sobre còpies de seguretat automàtiques.
    -   Galeria d'Android: L'aplicació de galeria bàsica no admet fotos ocultes, així que descarregueu una aplicació de galeria alternativa com [Fossify Gallery](https://github.com/FossifyOrg/Gallery) i activeu la protecció amb contrasenya per als elements ocults a la configuració.

### 💰 Millora el teu equipament

-   **Compra una pantalla de privacitat per al teu portàtil i telèfon.** Aquestes làmines adheribles eviten que els curiosos vegin el que hi ha a la pantalla. Exemples per a:
    -   Portàtils: [Filtres de privacitat 3M](https://www.3m.com/3M/en_US/p/c/office-supplies/workstation-accessories/screen-filters-protectors/laptop-filters/)
    -   iPhone: [Spigen EZ FIT GLAS.tR Privacy](https://www.spigen.com/collections/iphone-13-pro/products/iphone-13-pro-screen-protector-ez-fit-glas-tr-privacy)
-   **Col·loca un adhesiu (o una coberta per a la webcam) sobre la càmera frontal del teu portàtil.**
    -   Si compres una tapa per a la càmera web d'un portàtil, assegura't que tingui menys de 0,1 mm de gruix perquè no afecti el tancament del portàtil.
-   **No utilitzis els dispositius que et proporciona la teva empresa per a assumptes personals.** Tens dispositius separats per a la teva vida laboral i personal o, si és massa complicat tenir-ne diversos, utilitza el teu dispositiu personal per a tot. Els dispositius que proporcionen les empreses sovint tenen sistemes de monitoratge que es poden malutilitzar durant les disputes.
-   **Compra un telèfon mòbil que sempre rebi les últimes actualitzacions de programari** i, en el cas d'Android, que no instal·li aplicacions ni complements de sistema innecessaris.
    -   Primera opció: Apple iPhone. Apple té un historial de donar suport als dispositius durant molt de temps.
    -   Segona opció: Google Pixel. Els telèfons Pixel reben les actualitzacions d'Android directament de Google i venen amb una instal·lació d'Android més o menys «pura».
    -   Per a altres telèfons Android:
        -   Investiga per trobar un telèfon que a) no afegeixi massa programari innecessari a la seva instal·lació d'Android, b) apliqui ràpidament els pegats de seguretat que publica el projecte Android de Google i c) garanteixi actualitzacions de programari per al seu maquinari durant molt de temps.
        -   Eviteu els telèfons Android més barats de grans empreses com Samsung, Xiaomi o OPPO: tenen un historial d'afegir aplicacions innecessàries i intrusius. Per exemple, [la plataforma d'aplicacions](https://www.techfinitive.com/explainers/what-is-app-cloud-delete/) de Samsung [que instal·la aplicacions sense permís i recull dades sobre vosaltres sense consentiment](https://www.techfinitive.com/explainers/what-is-app-cloud-delete/).
-   **Utilitzeu un servei de VPN de pagament** tant quan sigueu en una xarxa pública (p. ex., un cafè) com quan sigueu a casa (per reduir les dades que compartiu amb la vostra companyia de telefonia/internet).
    -   Evita els serveis de VPN gratuïts perquè sovint recuperen la inversió venent les teves dades.
    -   VPN recomanades: [Mullvad](https://mullvad.net), [IVPN💰](https://www.ivpn.net/)
    -   _Tingueu en compte que, tot i que el relleu privat d'iCloud és similar a una VPN, només s'aplica al trànsit a través del navegador web Safari._

### 🔡 Utilitza aplicacions amb xifrat de fi a fi

#### Per a missatgeria i trucades segures

-   **Utilitza aplicacions amb protocols de xifratge de fi a fi de codi obert i temporitzadors de missatges efímers fàcils d'utilitzar.**
    -   Aplicacions recomanades:
        -   [Signal](https://signal.org/): Registra't amb un número de telèfon.
        -   [Wire](https://wire.com/): Registra't amb una adreça de correu electrònic.
    -   Configura els missatges perquè desapareguin. Tria un interval que et sigui còmode.
        -   **Signal:** Ves a `Configuració → Privacitat → Missatges que desapareixen → Temporitzador per defecte per a xats nous`.
        -   **Wire:** No hi ha cap configuració a nivell d'aplicació. L'has de configurar per a cada conversa tocant/fent clic a la icona del temporitzador ⏱.
    -   Aquestes aplicacions també xifren les trucades de vídeo i veu de punta a punta, així que continueu utilitzant-les sempre que sigui possible.
-   **El xifratge de fi a fi per a trucades de vídeo/veu amb més de 5 persones potser no val la pena.** Hi ha diverses raons:
    -   És difícil mantenir la privacitat en trucades de grup grans, ja que sovint es converteixen en esdeveniments quasi públics a causa del gran nombre de participants.
    -   El suport per a trucades de vídeo/veu xifrades de cap a cap per a grups més grans és limitat, i la majoria de plataformes encara recullen les metadades de la vostra trucada fins i tot quan el xifratge de cap a cap està activat.

#### Per a compartir fitxers en línia i fer còpies de seguretat

-   **Desa i comparteix fitxers al núvol utilitzant el xifrat de fi a fi.**
    -   Aplicacions recomanades: [Tresorit](https://tresorit.com/), [Proton Drive](https://proton.me/drive) 💰
    -   Per a iCloud: activa la Protecció de dades avançada. [Consulta les instruccions d'Apple](https://support.apple.com/en-us/HT212520).
    -   _Recorda: els fitxers emmagatzemats a Dropbox i Google Drive no estan xifrats de cap a cap._
-   **Fes còpia de seguretat dels teus fitxers en línia amb una plataforma amb xifratge de fi a fi.**
    -   Aplicació recomanada: [Arq](https://www.arqbackup.com/) 💰

### 😷 Segmenteu encara més les vostres aplicacions de missatgeria

#### Tingues en compte què poden veure els altres en una conversa de grup

Les aplicacions de missatgeria utilitzen el teu número de telèfon o un nom d'usuari com a identificador únic (que la resta de persones utilitza per afegir-te a la plataforma). Per tant, **el teu número de telèfon o nom d'usuari és visible per a tothom amb qui estàs en un xat de grup**, juntament amb el nom i la foto del teu perfil.

A continuació, es detalla quins identificadors únics són visibles per als altres en una conversa de grup a les aplicacions de missatgeria populars:

-   **Signal:** número de telèfon per defecte si ja formes part de la llibreta d'adreces del destinatari, cap identificador únic si no (però pots crear un nom d'usuari i deixar de compartir el teu número de telèfon per complet)
-   **Wire:** nom d'usuari (ningú més pot veure l'adreça de correu electrònic o el número de telèfon que vas fer servir per registrar el teu compte)
-   **Telegram:** número de telèfon per defecte (però pots configurar un nom d'usuari i deixar de compartir el teu número de telèfon)
-   **WhatsApp:** número de telèfon

Si no vols donar el teu número de telèfon personal, considera obtenir un número de telèfon virtual d'un dels proveïdors que esmentem en el nostre article sobre `com ocultar la teva identitat per a cites en línia, esdeveniments o organitzar activitats`.

#### Utilitzeu les funcions de seguretat i privacitat específiques de l'aplicació

##### Signal

-   **Configura un nom d'usuari** perquè la gent et trobi amb aquest nom en lloc del teu número de telèfon. Per crear un nom d'usuari:
    -   `Configuració →` \[Toca la icona del teu perfil o el teu nom\] `→ @ Nom d'usuari`
-   **Amaga el teu número de telèfon.**
    -   Ves a `Configuració → Privacitat → Número de telèfon` i estableix ambdós a `Ningú`.
-   **Activa la capa addicional de protecció amb codi PIN** i evita que altres iniciïn la sessió amb el teu número de telèfon.
    -   `Configuració → Compte → Bloqueig de registre: Activat`
    -   `Configuració → Compte → Bloqueig de registre: Activat`
-   **Amaga els teus missatges del canviador d'aplicacions del telèfon** (perquè els teus missatges no es mostrin accidentalment a altres aplicacions) activant `la seguretat de la pantalla`:
    
    -   `Configuració → Privacitat → Amaga la pantalla a Canviador d'aplicacions`
-   **Amaga els teus missatges de la funció Recall de Microsoft Windows.**
    
    -   L'aplicació de sobretaula de Signal les amaga per defecte, però comprova-ho doblement anant a `Configuració → Privacitat → Seguretat de la pantalla`.
-   **Evita que els missatges apareguin a les finestres de notificació.**
    
    -   `Configuració → Notificacions → Contingut de les notificacions: Mostra → Sense nom ni contingut`

##### Telegram

-   **Activa la verificació de dos passos** per evitar que algú mogui el teu compte sense el teu permís.
    -   `Configuració → Privadesa i seguretat → Verificació en dos passos`
-   **Amaga el teu número de telèfon:**
    -   `Configuració → Privacitat i seguretat → Número de telèfon`, i després estableix `Qui pot veure el meu número de telèfon` a `Ningú`.
-   **Comença les converses amb `la nova xerrada secreta` perquè estiguin xifrades de fi a fi.** Totes les altres converses i grups no**ho** estan. _Malauradament, això significa que els teus missatges no apareixeran a l'aplicació d'escriptori o web._

##### WhatsApp

-   **Activa les notificacions de seguretat a WhatsApp** per rebre una notificació quan una persona amb qui parles canvia a un dispositiu nou.
    -   `Configuració → Compte → Seguretat → Mostra notificacions de seguretat en aquest telèfon: Activat`
-   **Activa la verificació en dos passos** per evitar que algú mogui el teu compte sense el teu permís:
    -   `Configuració → Compte → Verificació de dos passos: Activa`
-   **Si fas còpies de seguretat dels xats, assegura't que estiguin xifrats de fi a fi** o desactiva'ls del tot.
    -   `Configuració → Xats → Còpia de seguretat de xats → Còpia de seguretat amb xifratge de fi a fi`
    -   Per als usuaris d'iOS que fan servir `la còpia de seguretat d'iCloud` (que no està xifrada de fi a fi) per a fer una còpia de seguretat de tot el telèfon, assegureu-vos que el WhatsApp no estigui inclòs en el procés. No s'ha de confondre aquesta `còpia de seguretat d'iCloud` amb la funció de còpia de seguretat interna del WhatsApp, que també utilitza iCloud.
        -   `[iOS] Configuració →` El teu nom `→ iCloud → Gestiona l'emmagatzematge → Còpies de seguretat →` Dispositiu `→ WhatsApp: Desactivat`
-   **Atura la descàrrega automàtica de totes les fotos i vídeos que reps:**
    -   `Configuració → Xats → Desa a la carpeta de fotos: Desactivat`

### 🙃 Segureu la resta dels vostres comptes

Has creat contrasenyes úniques per als comptes importants al `Nivell 2`, però hauries de planificar un dia per ocupar-te de la resta dels teus comptes en línia. No és una tasca urgent, per això l'hem posat tan avall a la llista, però requerirà força temps i esforç. Pots fer-ho ara o marcar-ho com a tasca pendent per més endavant.

-   **Fes una llista de tots els comptes actius i dels comptes que continguin la teva informació privada.** No et preocupis per trobar tots els comptes, sempre els podràs gestionar més endavant.
-   **Si ja no utilitzes un compte, considera iniciar-hi la sessió per desactivar-lo o suprimir-lo.** Potser alguns comptes tenen un valor sentimental, però la majoria no.
-   **Per als comptes que vulgueu conservar, assegureu-vos que cadascun utilitzi una contrasenya única i difícil d'endevinar.** Reviseu les nostres recomanacions `de nivell 2` sobre com crear bones contrasenyes si cal.
    -   Si utilitzeu un gestor de contrasenyes, ara és el moment de transferir-hi tot:
        -   La manera més ràpida d'introduir les dades és iniciar la sessió i desconnectar-te de cada compte al teu ordinador, i deixar que l'extensió/add-on del navegador del gestor de contrasenyes capturi les dades automàticament.
        -   En alguns casos, el gestor de contrasenyes pot advertir-te que la contrasenya que tens és feble. Si és així, dedica un minut més al lloc web del compte per canviar-la per una nova contrasenya.
        -   Quan hagis acabat, utilitza la funció de monitoratge del teu gestor de contrasenyes per comprovar les contrasenyes emmagatzemades i veure si són massa curtes, si s'han reutilitzat o si ja s'han filtrat com a part d'una filtració de dades. A 1Password, aquesta funció s'anomena `Watchtower`, i a Bitwarden s'anomena `Vault Health Report`.Considera utilitzar un sobrenom o només el teu nom de pila (si el teu nom de pila és comú on vius).

---

_👍👍👍👍 Uau, ho has aconseguit. Has completat els quatre nivells! Has assegurat-ho tot (grans i petits), has augmentat dràsticament la teva privacitat digital i has aconseguit eines i consells supersegurs. Has fet tot el que creiem que és útil per a tothom. Regala't alguna cosa bonica com a recompensa, sens dubte._

_A partir d'ara, oferim recomanacions per a casos especials (escenaris) i, a continuació, una petita secció de bonificació per a usuaris tècnics. Si cap dels escenaris no s'aplica a tu ara mateix, ja ho tens tot a punt. Recorda que els escenaris seran aquí si mai els necessites!_

---

## 🤹🏻 Escenaris

---

### 👤 Amagar la teva identitat per a cites en línia, esdeveniments o organitzar

#### No utilitzis el teu nom complet

-   **Considera utilitzar un sobrenom** o només el teu nom de pila (si el teu nom de pila és comú on vius). Això és especialment important si el teu nom complet és molt singular, la qual cosa fa que sigui molt fàcil cercar-lo en línia.
-   **Considereu utilitzar un pseudònim persistent o una identitat col·lectiva,** especialment si sou una figura pública. Per a més informació sobre com i per què, vegeu:
    -   Tactical Tech: [Zen i l'art de fer que la tecnologia treballi per a tu](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online)

#### Obtén un número de telèfon secundari

Per a les aplicacions de missatgeria que utilitzen el número de telèfon com a identificador principal (p. ex., Signal, WhatsApp, Telegram), obtingueu un número secundari a:

-   **Serveis en línia de pagament 💰** (més fiables)
    -   [Hushed::](https://hushed.com) Ofereix números dels EUA, del Canadà i del Regne Unit
    -   [Burner::](https://www.burnerapp.com/) Ofereix números dels EUA i del Canadà
-   **Serveis en línia gratuïts 🆓**
    -   [TextNow::](https://www.textnow.com/) Ofereix números dels EUA i del Canadà amb publicitat
    -   [Google Voice::](https://voice.google.com/about) Ofereix un número gratuït dels EUA, però només està disponible als EUA
-   **Les vostres companyies telefòniques locals 💰**
    -   Obteniu un pla de targeta SIM prepagament o econòmic

_Nota: si perds el teu número de telèfon secundari o t'hi desuscribes, altres persones el poden comprar i fer-se passar per tu._

#### Obtén un alias de correu electrònic

Per a llocs i serveis que utilitzen el correu electrònic com a identificador principal/nom d'usuari, crea un compte de correu electrònic nou 🆓 o un alias de correu electrònic que reenviï al teu compte principal des de:

-   [SimpleLogin::](https://simplelogin.io) Amb seu a Suïssa (com a part del grup Proton Mail/VPN)
-   [addy.io](https://addy.io): Amb seu al Regne Unit i a la UE

#### Comprar coses en línia de manera anònima

-   **Registra't per obtenir una targeta de crèdit virtual centrada en la privacitat 💰** de [Privacy](https://privacy.com/) (només disponible als EUA). Ajuda a) a ocultar la teva identitat al venedor i b) a ocultar al banc què has comprat.
-   **Compra una targeta de crèdit prepagament en una botiga de conveniència local.** Però tingues cura, aquestes targetes no sempre funcionen per a compres en línia, depenent d'on et trobis.
-   **Obtén una targeta de crèdit virtual per a proves gratuïtes** a [Do Not Pay](https://donotpay.com/learn/virtual-credit-cards/) per a aquells casos en què vulguis registrar-te en un període de servei gratuït però no vulguis facilitar la informació real de la teva targeta de crèdit.
-   **Demana que et paguin amb targetes regal**, que es poden utilitzar a les botigues sense rastreig.

#### Crea un àlies en línia no rastrejable

Fins i tot amb tots els serveis de tercers esmentats anteriorment, els tribunals encara poden obligar les empreses a lliurar informació sobre tu. Per tant, si realment et trobes en una situació d'alt risc, potser hauràs de fer tot el que s'ha dit i més. Per a un exemple d'això, consulta [la RECEPTA DE PRIVACITAT](https://geminiimatt.medium.com/creating-an-online-persona-deb4cd8c7f46) de Matt Mitchell [: Crear una personalitat en línia](https://geminiimatt.medium.com/creating-an-online-persona-deb4cd8c7f46).

---

### 🗃️ Fer còpies de seguretat de les teves dades

En cas que els teus dispositius es perdin o siguin piratejats, és bo tenir una còpia de seguretat recent de les dades que hi ha emmagatzemades.

#### Fer còpia de seguretat del telèfon/tauleta

##### Dispositius iOS

Les nostres recomanacions per fer còpies de seguretat de manera remota i local:

-   Fes còpia de seguretat a iCloud: un procés automatitzat que només funciona si tens/et subscrius a iCloud+ 💰.
-   Fes una còpia de seguretat al teu ordinador: un procés manual (connectes el dispositiu a l'ordinador amb un cable) que és gratuït sempre que tinguis espai al disc dur.

Consulteu [les instruccions](https://support.apple.com/en-ca/guide/iphone/iph3ecf67d29/ios) d'Apple [per fer-ho de les dues maneres](https://support.apple.com/en-ca/guide/iphone/iph3ecf67d29/ios).

-   Si utilitzeu iCloud, activeu la protecció de dades avançada (que inclou el xifratge de fi a fi) després seguint [aquestes instruccions](https://support.apple.com/en-us/108756).
-   Si fas una còpia de seguretat a l'ordinador, recorda marcar `«Xifra la còpia de seguretat local` » per establir una contrasenya durant el procés.

##### Dispositius Android

Els telèfons Android només es poden fer còpia de seguretat al núvol:

-   Còpia de seguretat a Google One: un procés automatitzat que només funciona si tens/t'has subscrit a Google One 💰. A diferència de l'iCloud d'Apple, però, no hi ha suport per al xifratge de fi a fi. Consulteu [les instruccions de Google](https://support.google.com/android/answer/2819582).

Tot i que podeu transferir fitxers seleccionats si connecteu el telèfon Android a l'ordinador amb un cable, no hi ha manera de fer còpia de seguretat de tot el contingut del telèfon.

#### Còpia de seguretat de l'ordinador en un disc dur extern

##### macOS

La recomanació predeterminada d'Apple és utilitzar la seva aplicació Time Machine, que farà una còpia de seguretat automàtica de tot el contingut del vostre ordinador en un disc dur extern. [Seguiu les seves instruccions](https://support.apple.com/104984) i recordeu activar `Cifrar còpies de seguretat`.

##### Windows

Windows té una funció anomenada Historial de fitxers, que fa còpies de seguretat automàtiques del contingut del vostre ordinador en un disc dur extern. [Seguiu les seves instruccions per configurar-lo](https://support.microsoft.com/windows/backup-and-restore-with-file-history-7bf065bf-f1ea-0a78-c1cf-7dcf51cc8bfc). No hi ha cap opció per xifrar la còpia de seguretat, de manera que heu d'afegir el xifratge manualment al disc extern utilitzant BitLocker [seguint aquestes instruccions](https://support.microsoft.com/en-us/windows/bitlocker-drive-encryption-76b92ac9-1040-48d6-9f5f-d14b3c5fa178). Malauradament, algunes versions Home de Windows no inclouen BitLocker, i les solucions alternatives per utilitzar Veracrypt amb l'Historial de fitxers són bastant complicades ([vegeu aquest exemple de conjunt d'instruccions](https://usercomp.com/news/1480091/veracrypt-drive-for-win-11-file-history)).

#### Fer còpies de seguretat de l'ordinador al núvol

Tot i que les còpies de seguretat en discs durs externs generalment són més barates i fàcils de mantenir, potser voldreu complementar-les amb un servei al núvol 💰:

-   Si voleu fer còpia de seguretat de tot el contingut del vostre ordinador, us recomanem [Arq](https://www.arqbackup.com/), [Blackblaze](https://www.backblaze.com/) o [IDrive](https://www.idrive.com). (Assegureu-vos d'activar el xifratge de fi a fi, que Blackblaze i IDrive anomenen `'private encryption key` '.)
-   Si només vols fer còpia de seguretat de carpetes i fitxers específics, et recomanem [Tresorit](https://tresorit.com/) o [Proton Drive](https://proton.me/drive).

---

### ✊🏾 Assistir a una protesta

Pel que fa a assistir a una protesta, hi ha moltes i moltes consideracions depenent d'on siguis i de qui siguis. En aquesta guia, només farem recomanacions generals relacionades amb la tecnologia.

#### Coses a fer abans d'anar-hi

##### Mantingueu les comunicacions privades

-   **Utilitza una aplicació de missatgeria amb xifrat de fi a fi i assegura't que els missatges efímers estiguin activats.** Consulta la secció sobre aplicacions de missatgeria xifrades del `Nivell 4` anterior.
-   **Revisa de nou la configuració de privacitat de les teves aplicacions de missatgeria.**
-   **Desactiva les previsualitzacions de missatges a les notificacions.**
    -   **iOS:** `Configuració → Notificacions → Mostra previsualitzacions: Quan el dispositiu està desblocat`.
    -   **Android:** `Configuració → Aplicacions i notificacions → Notificacions → Notificacions a la pantalla de bloqueig → Notificacions sensibles: Desactivat`.
-   **Reinicia el telèfon apagant-lo i tornant-lo a engegar** per netejar la memòria temporal (RAM) i perquè funcioni més fluidament.

##### Minimitzar el seguiment de la ubicació al telèfon

-   **Desactiva l'historial de localització:**
    -   iOS: `Configuració → Privacitat i seguretat → Serveis de localització → Serveis del sistema → Ubicacions importants`.
    -   Android: `Configuració → Seguretat i privacitat → Més configuracions de privacitat → Controls d'activitat → Historial de ubicacions.`
    -   Google Maps: toca la teva foto de perfil `→ Configuració → Historial de mapes → Desar a l'activitat web i de l'aplicació → Desactiva: desactiva i elimina l'activitat`.
-   **Suprimeix l'historial de localitzacions anterior:**
    -   iOS: `Configuració → Privadesa → Serveis de localització → Serveis del sistema → Ubicacions rellevants → Esborra l'historial`.
    -   Android: `Configuració → Seguretat i privacitat → Més configuracions de privacitat → Controls d'activitat → Historial de ubicacions.`
-   **Considera desactivar temporalment tots els serveis de localització:**
    -   iPhone: `Configuració → Privacitat → Serveis de localització → Serveis de localització: Desactivat`.
    -   Android: `Configuració → Ubicació → Utilitzar ubicació: Desactivat`.

##### Desactiva el 2G al telèfon per reduir el seguiment

**La teva ubicació pot ser rastrejada per tercers a través de la connexió de la targeta SIM del teu telèfon.** El seguiment es fa mitjançant dispositius (anomenats sovint captadors d'IMSI) que simulen torres de telefonia mòbil, les quals registren tant el número d'identificació únic de la teva targeta SIM com la teva ubicació aproximada. Per protegir completament la teva privacitat, hauries d'apagar el telèfon o configurar un telèfon de descàrrega. Per limitar el seguiment, desactiva el 2G al teu telèfon:

-   Android: `Configuració → Xarxa i Internet → Tarjetes SIM → [Nom del teu operador] → Permet 2G: Desactivat`.
-   Alternativa per a Android: si aquesta opció no apareix, obriu l'aplicació Telèfon i introduïu `*#*#4636#*#*.` Apareixerà una pantalla `de proves`. Seleccioneu `Informació del telèfon` i després canvieu el `tipus de xarxa preferit` al mateix que la selecció actual, però sense `GSM`. Per veure què significa cada acrònim, consulteu [la pàgina Comparació dels estàndards de telèfon mòbil](https://en.wikipedia.org/wiki/Comparison_of_mobile_phone_standards) de la Viquipèdia.
-   A iOS: activa el mode de confinament anant a `Configuració → Privacitat i seguretat → Mode de confinament: Activat`. Això posa en marxa una sèrie de precaucions de seguretat restrictives (incloent-hi la desactivació del 2G) que probablement voldràs desactivar un cop tornis a casa amb seguretat.

##### Neteja les dades del teu telèfon

-   **Suprimeix tota la informació personal sensible del teu telèfon.** Elimina qualsevol foto, registre de xats i anotacions que es puguin utilitzar en contra teva.
-   **Desa menys informació als teus dispositius.** No poden agafar allò que no tens (si et confisquen els dispositius).
    -   Vegeu l'escenari: `neteja de primavera de missatges i dades antics`.
    -   Elimina l'accés a les dades eliminant algunes aplicacions i iniciant la sessió en alguns comptes mentre siguis fora. Recorda reiniciar el telèfon després per esborrar-les també de la memòria del dispositiu. Si t'ajuda, escriu en un paper què has eliminat i de quines sessions has sortit i deixa'l a casa, per poder-hi tornar més tard.Redacteu un missatge per a un amic de confiança o una línia d'assistència jurídica abans de temps. P

##### Altres consideracions

-   **Redacteu per endavant un missatge per a un amic de confiança o una línia d'assistència jurídica.** Prepareu-vos per enviar-lo si us detenen a la protesta o si hi ha una emergència.
-   **Com a mesura de seguretat, escriu el número de telèfon de l'amic de confiança o de la línia directa al braç** amb un retolador permanent.
-   **Carrega completament el telèfon i porta una bateria de recanvi.**
-   **Si utilitzes la teva empremta dactilar o la teva cara per desbloquejar el telèfon, desactiva-ho abans de la protesta.** En algunes jurisdiccions, els agents poden obligar-te a facilitar la teva empremta dactilar, però no el teu codi d'accés.
-   **Vesteix-te per _no_ cridar l'atenció.** Porta roba discreta que no cridi l'atenció, cobreix-te els tatuatges visibles i posa't una mascareta. Fes que sigui més difícil ser identificat fàcilment a partir d'una foto.
-   **Considera portar una mascareta integral** per evitar la tecnologia de reconeixement facial, ja que de vegades aquesta pot identificar algú amb una mascareta quirúrgica (nas i boca).

##### Per a gairebé totes les situacions, no recomanem els telèfons d'un sol ús

Un telèfon d'un sol ús és un telèfon i una targeta SIM d'un sol ús que compres amb diners en efectiu. Idealment, et fa anònim davant de la companyia telefònica i els serveis en línia, i no revela informació sobre tu si algú et pren o et roba el telèfon. Però:

-   Els telèfons de un sol ús requereixen temps i diners addicionals per configurar-los. Has de procurar el telèfon i la targeta SIM, i després crear i configurar comptes nous per a tot.
-   Cada acció que realitzes amb el telèfon crea una pista sobre qui ets. Si l'actives a casa, revelarà la teva adreça. Si li envies un missatge a un amic, podria revelar la teva identitat.
-   Ser enxampat amb un telèfon d'un sol ús desperta sospites sobre tu.

En la majoria dels casos, fer que la teva identitat sigui menys pública és suficient i, de fet `,` assolible. Vegeu l'escenari anterior: `enmascarar la teva identitat per a cites en línia, esdeveniments o organització`.

##### Recomanem precaució a l'hora d'aconseguir un telèfon "secundari"

Un telèfon secundari és un telèfon que emmagatzema menys informació personal: està desconnectat de les xarxes socials i dels comptes de correu electrònic, no té fotos de la família i no està vinculat a xats de grup amb els teus amics. Com un telèfon d'un sol ús, si algú et roba el telèfon, la teva informació privada no quedarà exposada. A diferència d'un telèfon d'un sol ús, aquest segon telèfon no és un dispositiu d'ús únic: l'utilitzes de tant en tant juntament amb el teu primer telèfon.

Us aconsellem precaució perquè:

-   Tenir un segon telèfon implica haver de mantenir-lo, actualitzar-lo i pagar-lo.
-   Un segon telèfon només és útil si deixes el primer a casa, de manera que no podràs assistir a cap esdeveniment espontani si ja ets fora amb el primer telèfon.

Per a la majoria de la gent, recomanem dedicar la vostra energia a netejar i protegir el vostre telèfon únic. Només considereu un segon telèfon si teniu el temps i els recursos addicionals per dedicar-hi.

#### Recorda quan siguis fora

-   **Apaga el telèfon si existeix risc d'una detenció imminent o de la confiscació del telèfon.** El xifratge funciona millor quan els dispositius estan apagats.

##### Respecta la privacitat quan facis fotos i vídeos

-   **Intenta no fer fotos o vídeos on es vegin les cares de la gent.** Fer una foto de les esquenes de la gent està bé. _L'única excepció és si estàs gravant un vídeo d'un conflicte on la documentació és crucial._
-   **Si en una foto o vídeo apareixen cares, assegura't de difuminar-les abans de compartir-les en línia.**
    -   Eines recomanades:
        -   Telèfon: [eina de difuminatge de fotos de Signal](https://signal.org/blog/blur-tools)
        -   Ordinador: [Image Scrubber](https://everestpipkin.github.io/image-scrubber/) d'Everest Pipkin
        -   Ordinador: [eina de difuminatge de cares](https://support.google.com/youtube/answer/9057652?hl=en) de YouTube
-   **Per a més anonimat, esborra les metadades de la ubicació abans de compartir una foto/vídeo.**
    -   Eines recomanades:
        -   Ordinador: [Image Scrubber](https://everestpipkin.github.io/image-scrubber/) d'Everest Pipkin
        -   iPhone: Fes una captura de pantalla de la foto i comparteix la captura de pantalla
        -   Android: [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)Eines recomanades:Ordinador: Everest Pipkin's Image ScrubberiPhone: Fes una captura de pantalla de l

##### Ajuda els altres amb la seva informació mèdica d'emergència

-   **Si algú ha perdut el coneixement per un cop de calor, comproveu si porta amb si la seva informació mèdica d'emergència.** Aquesta informació podria ser:
    -   En una placa d'identificació mèdica, una polsera, una cadena de coll o una targeta de la cartera. Normalment hi ha un nom i un número de telèfon, i de vegades fins i tot un codi QR.
    -   Al seu telèfon:
        -   iPhone: Obre la pantalla de bloqueig, toca `Emergència` a la cantonada inferior esquerra i, a continuació, `Identificació mèdica` a la cantonada inferior esquerra.
        -   Android: Obriu la pantalla de bloqueig, toqueu `Emergència` a la part inferior.

---

### 🫶🏾 Organitzar un grup d'ajuda mútua

Els grups d'ajuda mútua sovint inclouen persones de diferents orígens, de manera que és molt probable que almenys una persona del grup no estigui al dia en les pràctiques de seguretat digital. Per tant, les possibilitats d'una filtració accidental de dades són molt més altes. Per sort, hi ha coses que podeu fer per minimitzar els danys si això passa.

-   **Amaga la teva identitat al grup**:
    -   Considera utilitzar un sobrenom o només el teu nom de pila (si el teu nom de pila és molt comú on vius).
    -   No utilitzis una foto teva com a imatge de perfil. Fes servir una foto d'un animal, d'un personatge de dibuixos animats, etc.
-   **Separeu qui té accés a les dades privades del vostre grup** (p. ex., les dades de contacte de la comunitat i les contrasenyes compartides). No tothom necessita accedir a tot. A continuació, us presentem algunes maneres de separar qui pot accedir a què:
    -   **Crea grups amb diferents nivells d'accés**. L'accés es pot basar en el temps que fa que algú és al grup, la seva destresa amb la tecnologia o els projectes en què treballa.
    -   **Fragmenteu un document en trossos.** Feu que persones diferents tinguin accés a parts diferents del document.
    -   **Nomena una o dues persones com a gestores dels documents/dades.** Però assegura't que aquestes persones coneguin bé les pràctiques de seguretat digital i que es quedin a casa durant les reunions públiques de risc.
-   **No utilitzeu el correu electrònic per comunicar-vos, només utilitzeu-lo per registrar-vos en comptes.** Els correus electrònics generen rastres de metadades i tendeixen a romandre als comptes de la gent durant massa temps.
-   **Si tu i el teu grup teniu previst reunir-vos en públic i en persona**, considereu les recomanacions de l'escenari `«Assistir a una protesta`».
-   **Si la vostra feina implica ser visibles al públic** (ajudeu gent en espais públics o apareixeu en entrevistes en vídeo), considereu la possibilitat de retirar la vostra foto i el vostre nom complet dels llocs web del vostre ocupador o centre d'estudis. Això és per evitar que persones que no estiguin d'acord amb el vostre grup assetgin el vostre ocupador o centre d'estudis.

#### Tria d'una aplicació de xat per a grups tancats i privats

De vegades haureu de fer concessions i utilitzar una aplicació que la gent ja conegui en lloc de la més segura tècnicament. L'únic requisit bàsic que val la pena defensar és **utilitzar una aplicació amb missatges efímers** (i assegurar-se **que** estiguin activats).

Recomanem:

-   **[Senyal](https://www.signal.org/)**:
    -   ✅ Xats de grup amb xifrat de fi a fi.
    -   ❌ No es pot esborrar una conversa de grup.
    -   ✅ Les persones del xat només poden veure el teu número de telèfon si ja el tenen a la seva agenda de contactes per defecte, i fins i tot pots desactivar-ho:
        -   Ves a `Configuració → Privacitat → Número de telèfon` i configura ambdues opcions a `«Ningú`».
    -   ✅ Admet trucades de grup d'àudio i vídeo
    -   Activa els missatges efímers:
        -   Al xat, toca el nom del grup a la part superior de la pantalla i després selecciona `Missatges que desapareixen`.
    -   Si has creat el grup, revisa la configuració `de Permisos` per decidir si vols que `Tots els membres` o `Només els administradors` puguin afegir nous membres.
-   **[Fils](https://app.wire.com/auth/#/)**:
    -   ✅ Xats de grup xifrats de fi a fi.
    -   ✅ Només mostra el teu nom d'usuari a les altres persones del xat.
    -   ✅ Pot esborrar una conversa de grup.
    -   ❌ Requereix un pla de pagament per a trucades de grup d'àudio i vídeo.
    -   Activa els missatges que desapareixen:
        -   Al xat, toca la icona del temporitzador ⏱ a la part inferior de la pantalla.

Actualment no recomanem Telegram, però continua sent una opció popular per a xats de grup. Per això, a continuació hem inclòs notes sobre com utilitzar-lo de manera més segura:

-   **[Telegram](https://telegram.org/)**:
    -   ❌ No hi ha xats de grup amb xifrat de fi a fi.
    -   ❌ Configuració difícil de trobar per amagar el número de telèfon.
    -   ❌ Difícil d'activar els missatges efímers.
    -   Per amagar el teu número de telèfon:
        -   Ves a `Configuració → Privacitat i seguretat → Número de telèfon` i, a continuació, configura:
            -   `Qui pot veure el meu número de telèfon` a `Ningú`.
            -   `Qui em pot trobar pel meu número` a `Els meus contactes`.Activa els missatges efímers:
    -   Activa els missatges efímers fent:
        -   Al xat, toca el nom del grup a la part superior de la pantalla, després toca els tres punts a la part superior dreta de la pantalla i, a continuació, toca `Suprimeix automàticament`.

No recomanem gens utilitzar WhatsApp. Tot i que les seves converses de grup estan xifrades de fi a fi, té molts inconvenients:

-   ❌ La teva llista de contactes s'envia a Meta/Facebook.
-   ❌ Tots els metadades de la conversa s'envien a Meta/Facebook.
-   ❌ Tothom al xat pot veure el teu número de telèfon.
-   ❌ Per defecte, descarrega automàticament totes les imatges i vídeos compartits.
-   ❌ Per defecte, les còpies de seguretat de les converses no estan xifrades de fi a fi.

##### Triar una aplicació per difondre actualitzacions

Els grups sovint utilitzen plataformes de xarxes socials (p. ex., Instagram, X/Twitter) per publicar actualitzacions sobre la seva feina. Una alternativa popular és utilitzar els canals [de Telegram](https://telegram.org/)per emetre missatges en un sol sentit a un públic ampli (sense comentaris ni respostes). Els avantatges dels canals de Telegram:

-   Podeu crear un canal públic, cercable o privat només per invitació.
-   Els seguidors/lectors s'aboquen al teu canal i reben totes les actualitzacions (en comparació amb les xarxes socials tradicionals, on has de competir per l'atenció i l'abast).

Si només transmeteu actualitzacions a 1000 persones o menys, les noves funcions [de Signal](https://www.signal.org/) poden fer-ho possible tot mantenint la màxima privacitat per a ambdues parts:

-   Toca la imatge de perfil del grup i el nom a la part superior per accedir a la configuració. Desplaça't cap avall fins a `Permisos` i toca-hi. A continuació, a `Envia missatges`, configura-ho a `Només administradors`.
-   Opcional: Configura un `enllaç de grup` públic a la mateixa pantalla de configuració del xat de grup per afegir membres més ràpidament. Pensa si els nous membres necessiten la configuració `«Aprovació de l'administrador` ». A més, considera desactivar l'enllaç d'accés públic després d'un breu període de temps.

##### Tria d'una aplicació per a la difusió pública de grans grups

Quan el vostre grup creixi, pot ser que tingui sentit crear un espai en línia més públic per treballar amb nous membres. Els grups sovint migren a plataformes com [Slack](https://slack.com/), [Mattermost](https://mattermost.com/) i [Discord](https://discord.com/), que permeten tenir diverses sales de xat dins del mateix espai. No obstant això, com que aquestes plataformes estan dissenyades per a entorns corporatius o comunitats de jocs públiques, les seves funcions de privacitat són molt limitades. Per tant, recomanem utilitzar aquestes plataformes només per a l'abast públic o per a missatgeria quasi pública.

##### Elecció d'una aplicació per a videotrucades en grup

Les aplicacions de videotrucades són complicades perquè poques d'elles admeten el xifratge de fi a fi, i fins i tot les que ho fan sovint recullen les vostres metadades. Dit això, aquí teniu el que recomanem:

-   **Per a grups petits de deu persones o menys, utilitzeu [Signal](https://www.signal.org/)**. Les seves trucades estan xifrades de fi a fi i no recull cap metadada. Malauradament, no funciona bé amb connexions a internet lentes i només permet un màxim de 40 persones en una trucada.
-   **Per a grups més grans:**
    -   Si teniu un membre del grup tècnic amb habilitats en administració de sistemes, configureu el vostre propi servidor [BigBlueButton](https://bigbluebutton.org/) o [Jitsi](https://jitsi.org/). El xifratge importa menys quan controleu les dades (és a dir, les podeu esborrar després de cada trucada).
    -   En cas contrari, recorre a les grans plataformes tecnològiques [Zoom](https://zoom.us/) o [Google Meet](https://meet.google.com/). (Zoom pot semblar una aposta més segura a causa de [la](https://support.zoom.us/hc/en-us/articles/360048660871-End-to-end-E2E-encryption-for-meetings) seva [funció de xifratge de fi a fi](https://support.zoom.us/hc/en-us/articles/360048660871-End-to-end-E2E-encryption-for-meetings), però també té un [mal historial de problemes de seguretat](https://www.tomsguide.com/news/zoom-security-privacy-woes).) Recorda, però, que ambdues plataformes recullen les teves metadades i que l'amfitrió ha de tenir un compte registrat.

##### Com triar aplicacions/plataformes de col·laboració

Hi ha dues vies que segueixen els grups a l'hora d'escollir aplicacions/plataformes de col·laboració:

1.  Utilitzeu les aplicacions de Google perquè són més accessibles.
2.  Utilitzeu alternatives de codi obert perquè tenen millors funcions de privacitat.

A continuació, fem un resum d'ambdues opcions.

###### 1\. Fer servir Google Workspace de manera més segura

Google Workspace (Docs, Sheets, Drive, etc.) és una opció popular per al treball col·laboratiu perquè les seves aplicacions són potents, fàcils d'utilitzar i funcionen bé en dispositius mòbils. Però també tenen limitacions greus de privacitat:

1.  Qualsevol persona que obri un document o fitxer pot veure la foto de perfil, el nom i l'adreça de correu electrònic del creador, vinculats al seu compte de Google.
2.  El registre d'activitat dels documents també mostra els detalls de qui ha fet edicions.
3.  Cap de les teves dades no està xifrada de fi a fi.

Per mitigar aquests inconvenients:

-   Crea una pàgina web de només visualització del teu document o full de càlcul de Google anant a `Fitxer → Compartir → Publicar a la web`. Està allotjada gratuïtament per Google i no mostra qui n'és el creador. (Malauradament, aquesta funció està disponible a l'ordinador i no en dispositius mòbils.)
-   Amaga la teva identitat:
    -   Crea un compte de Google separat amb un nom fals per crear documents i pujar fitxers.
    -   Edita el teu perfil de compte de Google per utilitzar un sobrenom o només el teu nom de pila. Malauradament, això canvia la manera com es mostra el teu nom a totes les aplicacions de Google (inclòs Gmail).
    -   Obre una finestra privada/incògnita quan editis documents d'altres persones.

###### 2\. Utilitzar alternatives de codi obert

Les aplicacions/plataformes que recomanem, amb notes sobre les seves limitacions d'accessibilitat:

-   **[Riseup Pad:](https://pad.riseup.net/)** Un editor de text basat en navegador que no requereix cap compte. Però aquest anonimat té limitacions: qualsevol persona amb l'enllaç pot editar/suprimir el bloc de notes, els blocs de notes es suprimeixen automàticament després de 60 dies d'inactivitat i tenen una vida útil màxima d'un any (així que recordeu fer còpies de seguretat).
-   **[Cryptpad:](https://cryptpad.fr/)** Una plataforma basada en navegador que té aplicacions per a l'edició de text, fulls de càlcul i presentacions amb xifrat de fi a fi. L'únic inconvenient és que les persones poden tenir problemes de càrrega en dispositius mòbils.
-   **[CryptDrive](https://cryptpad.fr/drive/)** i **[Proton Drive](https://proton.me/drive)** són alternatives a Google Drive una mica més privades. Permeten desar fitxers i carpetes en línia, compartir-los amb un enllaç i actualitzar-los després. A diferència de Google Drive, compartir un enllaç no mostrarà el vostre nom d'usuari ni el vostre correu electrònic, però ambdues plataformes requereixen tenir un compte, la qual cosa significa que els fitxers finalment encara són rastrejables fins a vós des del costat del servidor. Els plans gratuïts inclouen 1 GB i 5 GB d'emmagatzematge, respectivament.

---

### 🩸 Accedir de manera privada als serveis de salut reproductiva

Obtenir l'atenció que necessites pot ser una tasca controvertida i complicada en moltes parts del món. Aquí tens algunes recomanacions que poden ser d'aplicació si vius en un d'aquests llocs.

#### Investigació d'informació

-   **Cerqueu informació de salut sense ser rastrejats amb [el Tor Browser](https://www.torproject.org/download/).** No funciona bé per a llocs web que requereixen inici de sessió, però de totes maneres no hauríeu d'iniciar sessió per evitar el seguiment. No hi ha cap aplicació oficial per a iOS perquè fuita una mica de dades, així que feu servir la versió d'escriptori si sou usuaris d'iPhone.
-   **Si heu d'iniciar sessió en un compte, tingueu en compte que es deixarà un rastre de dades i procureu minimitzar-lo:**
    -   **Amaga quins llocs web visites al teu proveïdor d'internet utilitzant una VPN**.
        -   VPN recomanades 💰: [Mullvad](https://mullvad.net), [IVPN](https://www.ivpn.net/)
        -   VPN gratuïta recomanada: [Proton VPN](https://protonvpn.com/free-vpn) (gratuïta per a un dispositiu)
    -   **Minimitza el que poden veure els llocs web obrint una finestra privada/incògnita al navegador**. Això també garanteix que l'historial de navegació no es desi al dispositiu. Alternativament, fes servir un navegador diferent en mode privat només per a la recerca de salut per a compartimentar més les dades.
-   **Pensa-t'ho dues vegades abans de compartir informació** i**,** quan ho facis, utilitza una aplicació de missatgeria amb xifrat de fi a fi i amb missatges efímers activats. (Evita el correu electrònic.)

#### Comparteix informació amb amics

-   **Utilitza aplicacions de missatgeria amb xifrat de fi a fi** recomanades a la secció `Nivell 4: Utilitza aplicacions amb xifrat de fi a fi`, i recorda activar els missatges efímers.
-   No utilitzeu el correu electrònic ni altres aplicacions de missatgeria que deixen un rastre de dades.

#### Fer un seguiment del teu cicle menstrual

-   **Utilitza una aplicació que emmagatzemi les teves dades localment o utilitza bolígraf i paper.**
    -   Aplicacions recomanades: [Euki](https://eukiapp.com/), [drip](https://dripapp.org/)
    -   iOS: si utilitzeu la còpia de seguretat d'iCloud, desactiveu-la per a aquesta aplicació:
        -   `Ajustaments → El teu``nom → iCloud → Gestiona l'emmagatzematge → Còpies de seguretat → El teu``dispositiu → Euki: Desactivat`Minimitza el que els llocs web poden veure obrint una finestra privada/incògnita al navegador web. A

#### Interactuar amb una clínica

-   **Considera utilitzar un sobrenom.**
-   **Utilitza un número de telèfon secundari.** Ja sigui comprar una targeta SIM amb efectiu o obtenir un número virtual (gestionat per una empresa en un lloc que afavoreixi els drets reproductius).
    -   Per a la nostra llista de serveis de números virtuals, consulteu l'escenari anterior: `Enmascarar la identitat per a cites en línia, esdeveniments o organització`.
-   **Utilitza una adreça de correu electrònic amb xifrat de fi a fi.** Considera la possibilitat de crear-ne una de nova només per a aquest propòsit.
    -   Serveis recomanats: [Proton Mail](https://protonmail.com/), [Tuta Mail](https://tutanota.com/)
-   **Amaga les teves transaccions** pagant amb:
    -   Efectiu
    -   Una targeta de crèdit de prepagament que vas comprar amb efectiu
    -   Una targeta de crèdit virtual centrada en la privacitat de [Privacy](https://privacy.com/) (només disponible als EUA).

#### Desplaçar-se a una clínica

-   Si vas físicament a una clínica i penses que serà una situació arriscada, **segueix les recomanacions de l'escenari anterior: `Assistir a una protesta`.**
-   No portis el telèfon a la clínica. Com a mínim, deixa el telèfon a casa o a l'hotel durant aquesta última part del trajecte.

#### Més consells per a les persones dels EUA

-   [Okay, Fine, Let's Talk About Period Tracking: The Detailed Explainer](https://medium.com/@maggied/okay-fine-lets-talk-about-period-tracking-the-detailed-explainer-2f45112eebb4), de Kendra Albert, Maggie Delano i Emma Weil

---

### 🛫 Creuar una frontera internacional

-   **Fes còpia de seguretat abans de marxar i guarda'n una còpia a casa** per si els teus dispositius es perden durant el trajecte.
-   **Desa menys informació als teus dispositius.** No poden agafar el que no tens (si et confisquen els dispositius).
    -   Vegeu l'escenari: `neteja de primavera de missatges i dades antics`.
    -   Els usuaris de 1Password poden utilitzar el [mode de viatge](https://support.1password.com/travel-mode/) de l'aplicació per eliminar certes contrasenyes del dispositiu durant un viatge.
    -   Elimineu l'accés a les dades esborrant algunes aplicacions i iniciant la sessió a altres comptes mentre esteu de viatge. Recordeu reiniciar el telèfon després per esborrar-les també de la memòria del dispositiu. Si us ajuda, anoteu en un paper el que heu esborrat i dels comptes on heu iniciat la sessió i deixeu-lo a casa, per poder-hi tornar més tard.
    -   Alternativament, si això és massa feixuc però tens els diners, compra un telèfon addicional i fes-lo servir com a telèfon de viatge. Aleshores, sense importar-hi res del telèfon actual, configura'l afegint aplicacions i comptes d'un en un a mesura que els necessitis. D'aquesta manera, seràs plenament conscient del que tens al telèfon. Però assegura't de començar aquest procés almenys un mes abans del viatge i de fer servir el telèfon com a principal durant aquella setmana, per no viatjar amb un dispositiu sospitosament buit.
-   **Revisa els teus perfils públics a les xarxes socials**, ja que alguns llocs els poden revisar.
    
    -   Arxiveu o suprimiu les publicacions antigues que es puguin malinterpretar.
    -   Reentrena l'algorisme de les teves xarxes socials un mes o dos abans.
-   **Porta només els dispositius que necessitis.**
    
    -   Viatges per feina? Només porta els teus dispositius de treball i deixa els personals a casa.
    -   Realment necessites portar el portàtil? Avui dia pots fer la majoria de coses amb un telèfon o una tauleta.
-   **Para atenció a les pegatines que poses als teus dispositius.** Un agent fronterer podria interpretar-les malament.
-   **Decideix per endavant què faràs si et demanen que desbloquegis els teus dispositius.** De vegades, els controls formen part de la rutina del pas fronterer.
-   **Considereu apagar els vostres dispositius durant el pas.**
    -   L'emmagatzematge/les unitats de disc només es xifren quan estan apagats, _no_ quan només estan en mode d'hibernació.
    -   Això també garantirà que els teus dispositius mòbils només es puguin desbloquejar amb un codi PIN, que està protegit per les lleis de llibertat d'expressió en algunes jurisdiccions.
-   **Si mantens el dispositiu encès, reinicia'l i després posa'l en mode avió.**
    
    -   Reiniciar esborra la memòria temporal o a curt termini del telèfon (memòria cau).
    -   El mode avió evita que arxius i missatges aleatoris es descarreguin automàticament.
-   **Adjunta una fitxa de seguiment/etiqueta a les bosses** que et preocupen.
    
-   **Informa els teus familiars o amics del número de vol i l'hora d'arribada.** Posa't en contacte amb un d'ells regularment en diferents moments del viatge (per exemple: «Acaben d'escanejar les meves maletes!»). Demana'ls que contactin amb un advocat o una organització pertinent si no apareixes.
-   **Si el procés es torna incòmode, planteja't tornar a casa de moment.** De vegades tens mala sort i no val la pena passar per tot plegat per l'estrès que suposa. Digues-los que retires la teva sol·licitud, que ja no vols entrar al país i que vols tornar a casa.

#### Per a situacions extremes

_Nota: Algunes d'aquestes pràctiques poden despertar sospites i tenir efectes contraproduents._

-   **"Oblida't" de la meitat de la teva contrasenya.** Bloqueja el dispositiu/compte amb contrasenya de manera que només un amic de confiança tingui la segona meitat de la contrasenya.
-   **Tanca la sessió de tots els comptes importants.** O deixa tots els teus dispositius a casa.
-   **Consulta un advocat abans.** Porta una còpia impresa de la seva informació de contacte amb tu, per poder-lo contactar fàcilment.

---

### 🤐 Viatjar a un lloc amb lleis de privacitat de dades febles o censura d'internet

-   **Tingueu en compte que les companyies de telefonia mòbil poden compartir la vostra ubicació i informació personal** amb tercers sense el vostre permís.
-   **Configura una VPN prèviament per:**
    -   Accés als serveis sense interrupcions.
    -   Minimitzar la quantitat de dades recollides sobre tu.
    -   Aplicacions recomanades: [Mullvad](https://mullvad.net/), [IVPN](https://www.ivpn.net/) 💰
-   **Descarrega aquestes aplicacions fora de línia per si hi ha problemes de connexió:**
    -   **Una aplicació de missatgeria fora de línia** per enviar missatges de text a persones properes si es perd la connexió a Internet mitjançant Bluetooth.
        -   Recomanat: [Bridgefy](https://bridgefy.me/) — _però cal obrir l'aplicació amb una connexió a internet per configurar el compte!_
    -   **Una aplicació de mapes sense connexió**
        -   Recomanat: [Organic Maps](https://organicmaps.app/)
-   **Reavaluïeu quines plataformes en línia són segures per utilitzar.**
    -   Vegeu amb quina freqüència una plataforma lliura les seves dades consultant els seus informes de transparència.
        -   [Informe de transparència de Google: Sol·licitud d'informació d'usuari](https://transparencyreport.google.com/user-data/overview)
        -   [Informe de transparència de Facebook: Sol·licituds de dades d'usuari per part del govern](https://transparency.facebook.com/)
        -   [Centre de transparència d'X/Twitter: Sol·licituds d'informació](https://transparency.twitter.com/en/reports/information-requests.html)
        -   [Informe de transparència d'Apple](https://www.apple.com/legal/transparency/)
    -   Cerqueu la ubicació de la seu central de la plataforma i vegeu on és l'oficina local o regional més propera. La ubicació afecta la relació de la plataforma amb les autoritats i la seva política de privacitat.

---

### ‍💻 Organitzar un esdeveniment públic en línia

-   **No diguis res que no diries en públic.** Anima els teus assistents a fer el mateix. La majoria de les plataformes comercials tenen accés a les teves dades d'àudio/vídeo i extreuen els teus metadades per crear perfils de consum.
-   **Limita el grau de control que té un membre del públic.**
    -   Per exemple, en la majoria d'esdeveniments de Zoom, no és necessari que tothom tingui accés a la compartició de pantalla.
-   **No facis que l'enllaç de la reunió sigui massa públic.** Tant pots establir una contrasenya per a la reunió com configurar un sistema de confirmació d'assistència (RSVP) perquè no hagis de compartir l'enllaç i la contrasenya de la reunió públicament.
-   **Crea un pla de moderació d'usuaris i de contingut.**
    -   Si teniu copresentadors o moderadors, assegureu-vos que estiguin configurats al sistema en línia com a administradors/editors/moderadors.
    -   Familiaritzeu-vos amb els poders de filtratge, silenciament i bloqueig que teniu com a amfitrions/moderadors.
    -   Creeu un pla d'acció d'emergència sobre què faríeu si un trol maliciós entrés al vostre esdeveniment.

---

### 🥴 Assetjament en línia i difusió de dades personals

L'assetjament i el doxxing solen ser situacions molt específiques, que varien dràsticament segons qui siguis, què facis, qui sigui l'atacant, etc.

Tot i que a continuació teniu algunes recomanacions generals, us suggerim que busqueu informació addicional a algú de la vostra comunitat i en un recurs o guia en línia que s'ajusti més a la vostra situació exacta.

#### Construeix sistemes de suport

##### Recluta un amic de confiança

No t'acorralis intentant-ho tot sol!

-   **Línia de base:** Demana a un amic de confiança que et doni suport i espai per a tu i la teva situació. Pot fer de contrapunt mentre t'ajuda a analitzar la gravetat de l'amenaça.
-   **El més recomanable:** demana a un amic de confiança que t'acompanyi mentre investigues, graves, informes i bloqueges els assetjadors.
-   **Per a situacions greus:** entrega el teu telèfon/cuentes a un amic de confiança i demana-li que et resumi els missatges i les actualitzacions entrants. Reduir la teva exposició reduirà l'estrès.
-   **Extra:** Demana a l'amic de confiança que iniciï una conversa de grup amb tu, ell o ella i 2-3 persones addicionals explícitament per a la teva situació. D'aquesta manera, la feina de suport es reparteix entre diverses persones.

Recomanem revisar les recomanacions següents amb el teu amic de confiança o passar-li aquestes recomanacions.

##### Notifica les persones que se'n puguin veure afectades

Una altra manera de sentir-se menys sol és contactar amb persones que:

1.  Estaran a prop teu i voldran saber perquè els importes (amics i familiars).
2.  Podrien veure's afectats indirectament per la situació (companys de feina, persones de les teves xarxes professionals o personals).

Aquestes persones no seran necessàriament el teu "amic de confiança", però podrien ajudar-te amb altres coses paral·lelament.

Si la situació s'agreuja:

-   Previneu futurs problemes preparant conjuntament punts de conversa perquè sàpiguen com respondre si desconeguts d'internet o la premsa els contacten.
-   Troba i notifica algú de la teva comunitat proper amb experiència en crisis per a protecció i suport.

##### Connecta amb comunitats

-   **Contacta amb les comunitats en línia (i fora de línia) de les quals siguis membre actiu i demana ajuda.** Consulta l'article de PEN America sobre com [desplegar les teves comunitats cibernètiques de suport](https://onlineharassmentfieldmanual.pen.org/deploying-supportive-cyber-communities/).
-   **Comparteix la teva història** a la [plataforma de relats de Right To Be](https://stories.righttobe.org/), on la seva comunitat et pot ajudar a documentar o denunciar abusos a les xarxes socials, així com a enviar-te missatges de suport.

#### Investiga i supervisa la situació

##### Cerqueu informació pública sobre vosaltres mateixos (autocomproveu la vostra informació)

-   **Cerqueu el vostre nom, els vostres àlies, noms d'usuari i adreça a Google, Bing i altres motors de cerca populars.** Proveu d'afegir `filetype:pdf` a la vostra consulta de cerca per trobar qualsevol currículum o document que hàgiu pogut passar per alt.
-   **Fes una cerca d'imatges de les teves fotos de perfil més utilitzades als mateixos motors de cerca.**
-   **Cerqueu el vostre nom, els vostres àlies i els vostres noms d'usuari a qualsevol xarxa social que utilitzeu habitualment.** Comproveu també les xarxes socials populars al vostre lloc.
-   **Vols fer una cerca més exhaustiva?** Consulta [la Guia de Doxing](https://guides.accessnow.org/self-doxing.html) per a particulars de l'Access Now Digital Security Helpline.

##### Monitoritza les actualitzacions i recull proves

-   **Supervisa el teu nom i el teu nom d'usuari.** Afegeix-los com a paraules clau de cerca a les eines següents:
    -   [Talkwalker](https://www.talkwalker.com/alerts)
    -   [Google Alerts](https://www.google.com/alerts)
    -   [Mention](https://mention.com) 💰
-   **Monitoritza i arxiva les pàgines web que et mencionen**. Eines recomanades:
    -   [ChangeTower](https://changetower.com/) o [Visualping](https://visualping.io/)
-   **Registra (data, hora, descripció, captura de pantalla, URL) els incidents en el programa o aplicació que et sigui més accessible.** Si hi ha moltes captures de pantalla del telèfon, utilitza l'aplicació [Hunchly Mobile](https://hunch.ly/mobile) per organitzar-les i anotar-les.
-   **Si és probable que es prenguin mesures legals futures, paga [a Page Vault](https://www.page-vault.com) perquè faci una captura de pantalla d'un lloc web.** Demana a un advocat que presenti una [sol·licitud de preservació de proves](https://onlinesos.org/blog/evidence-preservation-i-e-litigation-hold-request) a la plataforma en línia corresponent.

#### Decideix un pla d'acció

##### Maneres d'afrontar el/els teu/teus assetjador/assetjadors

Les opcions següents no són mútuament excloents, i la millor opció pot canviar amb el temps a mesura que la situació evoluciona:

-   **Ignora:** De vegades, els assetjadors s'avorreixen i se'n van si no reben atenció.
-   **Desescalar:** En alguns contextos, podeu desactivar la situació amb algunes paraules calmades abans que empitjori.
-   **Silenciar a les xarxes socials:** Això et permet estar tranquil·la i no veure de sobte les actualitzacions del teu assetjador a les xarxes socials. (Tot i això, potser voldràs comprovar proactivament què diu.)
-   **Bloqueig a les xarxes socials:** Envia un senyal clar al teu assetjador. No podrà veure les teves publicacions ni enviar-te missatges. No obstant això, s'adonarà que l'has bloquejat i podria interpretar-ho com un senyal d'escalada.
-   **Fer-ho públic:** De vegades, avergonyir públicament l'assetjador o aconseguir suport de la gent fa que desaparegui. No obstant això, això comporta un alt risc d'agreujar la situació i cridar-hi més l'atenció.
-   **Denúncia:** Denúncia l'assetjador a la plataforma en línia corresponent perquè bloquegin o eliminin el seu compte. També pots denunciar l'incident a les autoritats policials locals si té sentit.
-   **Busca un advocat:** si l'assetjament supera clarament els límits legals a la teva jurisdicció, pot ser que et serveixi d'ajuda, però assegura't de tenir el temps i els diners necessaris per fer-ho.

Consulta [les directrius](https://onlineharassmentfieldmanual.pen.org/guidelines-for-safely-practicing-counterspeech/) de PEN America [per practicar el contraparler de manera segura](https://onlineharassmentfieldmanual.pen.org/guidelines-for-safely-practicing-counterspeech/) per obtenir consells addicionals sobre com respondre eficaçment.

##### Gestió de trucades no desitjades

De vegades no vols bloquejar un número no desitjat encara. De vegades un assetjador utilitza números falsos o temporals per trucar-te. Aquí tens algunes maneres de gestionar les trucades no desitjades:

-   **Silenciar o desactivar les trucades d'un número específic:**
    -   Android: Troba el contacte a l'aplicació Telèfon o Contactes i toca el nom. A `la secció Configuració del contacte`, ves a `Sonoritat del contacte → [So actualment configurat] → Sense`. També pots enviar totes les trucades directament a la bústia de veu tocant `Envia a la bústia de veu` a la mateixa configuració del contacte.
    -   iOS: Creeu un nou `mode de concentració` seguint [aquestes instruccions de Tom's Guide](https://www.tomsguide.com/how-to/how-to-silence-a-specific-contact-on-your-iphone).
-   **Silenciar trucades de tots els números desconeguts:**
    -   iOS: `Configuració → Aplicacions → Telèfon → Silenciar trucades de números desconeguts`
-   **Bloqueja les trucades de tots els números desconeguts:**
    -   Android:
-   **Revela el número quan un interlocutor s'amaga darrere de la configuració `de número ocult`** fent servir una aplicació com [TrapCall](https://www.trapcall.com/).

##### Si decideixes denunciar

-   **Si l'assetjament està tenint lloc en una plataforma de xarxes socials**: presenteu una denúncia a l'empresa de la xarxa social i demaneu a almenys 10 amics que facin el mateix. Feu que 1 o 2 persones presentin una reclamació per infracció de drets d'autor si té sentit.
    -   **Revisa els enllaços de denúncia pertinents per als serveis següents:**
        -   [Facebook](https://www.facebook.com/help/www/181495968648557)
        -   [Instagram](https://help.instagram.com/192435014247952)
        -   [X/Twitter](https://help.twitter.com/en/forms/safety-and-sensitive-content)
        -   [Snapchat](https://support.snapchat.com/en-US/a/report-abuse-in-app)
-   **Si hi ha material d'assetjament en un lloc web:** presenteu una denúncia al servei d'allotjament web i al registrador de dominis del lloc web. És possible que pugueu esbrinar quines són aquestes empreses fent una [consulta WHOIS](https://lookup.icann.org/) sobre el domini del lloc web.
-   **Si contactes amb les forces de l'ordre:**
    -   Tingueu en compte que no tots els agents estan acostumats a tractar amenaces d'assetjament en línia.
    -   Si creus que podries ser objecte de 'swatting' (quan algú fa una trucada de broma a la policia per tu), fes-los-ho saber amb antelació. Envia'ls un article sobre el 'swatting' si és un concepte nou per a ells.

##### Suprimeix la informació sobre tu en línia

En la majoria dels casos, estaràs més segur si revises i elimines part de la informació pública que hi ha sobre tu a internet. Vegeu l'escenari següent titulat: `Eliminar informació sobre tu d'internet`.

#### Extra: eines i funcions útils de les xarxes socials

##### Facebook

Facebook té algunes funcions per controlar les teves interaccions, però, en última instància, depèn de tu establir límits sobre qui pot veure i comentar les teves publicacions i el teu perfil.

-   **[Ignora missatges](https://www.facebook.com/help/messenger-app/1245152242249842)** dins de Facebook Messenger per moure els missatges actuals i futurs a la secció `de Sol·licituds de missatges`
-   **[Revisió de la privacitat](https://www.facebook.com/privacy/checkup)** dins de Facebook inclou una secció sobre `Qui pot veure el que comparteixes` que t'orienta sobre la visibilitat del teu perfil i les teves publicacions.

##### Instagram

Instagram té un conjunt de funcions matisades dins de la seva aplicació mòbil per filtrar i ajustar les interaccions socials a la seva plataforma.

-   **[Restricció](https://help.instagram.com/2638385956221960/)** un compte, la qual cosa significa que l'altra persona no pot veure quan ets en línia, si has llegit els seus missatges i amaga els seus comentaris.
-   **[Amagar](https://help.instagram.com/1177797265575168/)** les teves històries d'un compte específic.
-   **[Paraules ocultes](https://help.instagram.com/700284123459336)** Filtra missatges i comentaris amb paraules que Instagram considera ofensives. També pots configurar una llista de paraules personalitzada.
-   **[Limita](https://help.instagram.com/4106887762741654)** comentaris i missatges de seguidors recents i de comptes que no et segueixen.

##### Bluesky

Bluesky permet a qualsevol crear la seva pròpia llista manual o algorítmica de marcadors, silenciaments i bloquejos, i permet als usuaris limitar qui pot comentar o compartir les seves publicacions.

-   **Hi ha dos tipus d'etiquetes: insígnies i advertiments.** Les insígnies són etiquetes de text breus i informatives que apareixen a sobre d'una publicació o a la part inferior d'un perfil. Els advertiments cobreixen el contingut amb un avís sobre què és i t'obliga a fer-hi clic per veure la publicació original.
-   **Els comptes etiquetadors** poden ser gestionats per membres de la comunitat. En subscriure't a un compte, tindràs accés a les etiquetes que gestiona. Per a cada etiqueta (p. ex., `insulta`), pots triar si vols que la publicació etiquetada quedi oculta, que tingui una insígnia al costat, que se t'avisi o desactivar l'etiqueta de moment. Aquí tens una [llista de mostra de comptes etiquetadors](https://www.bluesky-labelers.io/).
-   Els comptes d'usuari i els comptes etiquetadors poden crear**llistes de moderació** a `Configuració → Moderació → Llistes de moderació`. Quan et subscrius a una llista, pots triar si vols silenciar o bloquejar tots els usuaris de la llista.
-   **Configuració de la interacció amb la publicació:** Decidiu si els altres poden citar la publicació i només permetre respostes d'usuaris esmentats, usuaris seguits o de ningú. Quan escriviu una publicació, toqueu a `«Qualsevol pot interactuar»` per veure la configuració.

Avís important: Actualment és possible obtenir una llista de totes les persones que bloquegeu mitjançant l'API de Bluesky.

##### Mastodon

Mastodon té funcions bàsiques per limitar la visibilitat i la cercabilitat de les publicacions, i per ajustar com de públic és el teu perfil. A més, té funcions úniques perquè funciona en una xarxa de servidors federats/descentralitzats (cada usuari ha d'unir-se a un servidor d'origen que, suposadament, s'alinea amb els seus valors).

-   **Configuració de la visibilitat de les publicacions:** Cada publicació es pot configurar com a `Pública`, `No indexada/Pública silenciosa` (amagada a les cerques i a Explora) o `Només per a seguidors`.
-   **Configuració de la privacitat del perfil:** A la secció `Configuració → Perfil públic → Privacitat i abast` del lloc web, podeu ajustar si les vostres publicacions i el vostre perfil apareixen a les pàgines de recomanacions o de cerca, si voleu revisar manualment cada nou seguidor i si voleu que els usuaris que seguiu i els que us segueixen siguin consultables.
-   **Funcionalitats federades/descentralitzades:** Els usuaris poden bloquejar tots els usuaris d'un altre servidor. Els administradors del vostre servidor també poden aplicar un bloqueig a tot el servidor per a un altre servidor (com a usuari, se us bloqueja automàticament).

##### X/Twitter

X ja no admet eines de tercers que combaten l'assetjament, i els esforços de moderació de la plataforma s'han relaxat. Si els controls següents no funcionen, considera configurar el teu perfil com a privat i desconnectar-te fins que la plataforma torni a ser estable.

-   **Vegeu a quines llistes us han afegit anant a `Perfil → Llistes → ··· → Llistes` on sou.** Si veieu una llista o un propietari de llista sospitós, toqueu els tres punts de la part superior dreta per denunciar la llista i deixar-la bloquejant-ne el creador.
-   **Controla qui pot respondre als teus tuits** tocant `'Tothom pot respondre` ' i restringint-ho a `'La gent que segueixes` ' o `'Només les persones que mencionis`'.

##### TikTok

Els esforços de TikTok se centren principalment a protegir les persones dels comentaris nocius.

-   **[Afegeix filtres de comentaris](https://support.tiktok.com/en/using-tiktok/messaging-and-notifications/comments#3)** introduint paraules clau manualment, utilitzant el filtre de contingut spam/ofensiu de TikTok o exigint aprovació manual per a tots.
-   **[Afegeix moderadors a la teva retransmissió en directe](https://support.tiktok.com/en/live-gifts-wallet/tiktok-live/moderating-on-tiktok-live)** per ajudar a gestionar comentaris i bloquejar espectadors no desitjats.
-   **[Eliminar seguidors](https://support.tiktok.com/en/using-tiktok/followers-and-following/removing-followers)** del teu compte; els antics seguidors no rebran cap notificació.

##### Discord

Discord està centrat en comunitats/servidors separats, la qual cosa afecta la manera com funciona el bloqueig.

-   **Quan bloqueges algú:**
    -   No et poden enviar missatges directes, trucar-te ni etiquetar-te en una publicació.
    -   Els seus missatges per a tu desapareixen.
    -   Els missatges que escriuen als canals compartits estan ocults. _Però_ els missatges que escrius als canals compartits continuen sent visibles per a ells.
    -   Per a tu, sempre apareixen `com a fora de línia`, però encara poden veure el teu estat en línia/fora de línia.
-   **[Configuració de privacitat](https://support.discord.com/hc/en-us/articles/217916488-Blocking-Privacy-Settings-)** et permet ajustar si els membres de la comunitat/del servidor et poden enviar missatges directes, i qui pot enviar-te sol·licituds d'amistat.

##### Triar entre silenciar o bloquejar un compte

-   **Algunes plataformes informen l'altra persona que l'has bloquejada, mentre que d'altres amaguen l'acció completament.** Llegeix aquesta [guia de Consumer Reports](https://www.consumerreports.org/digital-security/can-people-tell-when-blocked-texting-social-messaging-apps-a9942470743/) per a més detalls sobre com es veu el bloqueig per a l'altra part.

#### Mostra't afecte a tu mateix

-   **No et preocupis si no pots seguir la teva rutina laboral habitual.**
-   **Demana ajuda als amics perquè comparteixin un àpat, facin una pausa o s'encarreguin de les teves mascotes** durant uns dies.
-   **Fes tot el possible per menjar i dutxar-te regularment.**
-   **Fes exercici, per petit que sigui.** Pot ser una passejada o fins i tot estiraments. Tria alguna cosa que t'agradi i que et calmi la ment.
-   **Prepara per endavant una caixa de consol.** Inclou-hi coses que t'agradi veure, tocar, tastar i escoltar.
-   **Si l'incident és traumàtic, refereix-t'hi amb un sobrenom.**
-   **Recorda que no és culpa teva.** L'assetjament en línia mai no està justificat i s'encén per les raons més aleatòries.

#### Consells addicionals per fer front a l'abús d'imatges íntimes i deepfakes

-   **Consulta la legislació local** sobre**la** «porno venjativa», el «compartiment no consentit d'imatges íntimes» i els «delictes sexuals digitals». Sàpigues que en molts llocs és un acte delictiu.
-   **Pugeu un "hash" alterat d'una foto/vídeo abusiva a [StopNCII.org](https://stopncii.org/) per fer-los eliminar de les principals plataformes** com Facebook, TikTok i Reddit.
-   **Troba on s'està fent un ús indegut de la teva cara en línia amb [Alecto AI](https://alectoai.com)** (beta). El servei també t'ajudarà amb l'eliminació de contingut.
-   **Connecta amb altres persones i comparteix la teva història** a [My Image My Choice Storyplace](https://myimagemychoice.storyplace.com/).
-   **Connecta amb un servei local** de [la llista de suport global](https://www.esafety.gov.au/key-topics/image-based-abuse/getting-help-outside-australia) d'eSafety, [del directori global](https://www.chayn.co/global-directory) de Chayn o [dels recursos de suport directe](https://stopstalkerware.org/resources/) de la Coalició contra el Stalkerware.
-   **Fes el curs de Bloom sobre [l'abús basat en imatges i la reconstrucció de nosaltres mateixos](https://bloom.chayn.co/courses/image-based-abuse-and-rebuilding-ourselves)**.

#### Consells addicionals per a periodistes i investigadors

-   **Fes-te un objectiu més difícil.** Considera fer privats els teus comptes de xarxes socials (o eliminar-los temporalment) durant les 48 hores abans i després d'una gran publicació nova.
-   **No facis més soroll sobre tu mateix.** No facis 'livetweets' de la teva situació, no deixis la feina de sobte i no parlis amb mitjans de comunicació que tergiversaran les teves paraules.
    -   Si cal, prepara una declaració escrita formal o una resposta amb l'ajuda de persones que tinguin experiència tractant amb els mitjans de comunicació.
-   **Si el soroll no para, omple els mitjans de comunicació amb històries positives sobre tu.** Demana a persones de la teva comunitat professional que escriguin articles o publicacions a les xarxes socials positives sobre tu i la teva feina.
-   **Recorda, no has fet res malament.** És possible que els empresaris o companys ignorants no et donin suport i comencin a veure't com un problema — s'equivoquen.
-   **Llegeix [la conversa de Lyz Lenz amb Talia Lavin](https://lyz.substack.com/p/when-the-mob-comes)** sobre les seves experiències.
-   **Envia aquests recursos a la teva redacció:**
    -   Casebook de manipulació mediàtica: [Consells per a redaccions per donar suport als periodistes objecte d'assetjament en línia](https://mediamanipulation.org/research/tips-newsrooms-support-journalists-targeted-online-harassment/)
    -   Ontheline Newsrooms: [Mesures per a redaccions i periodistes per abordar l'assetjament en línia](https://newsrooms-ontheline.ipi.media/).

#### Consulta aquests recursos addicionals

-   PEN America: [Manual de camp sobre assetjament en línia](https://onlineharassmentfieldmanual.pen.org/)
-   Línia directa de jocs i assetjament en línia: [Guia de seguretat digital](https://gameshotline.org/online-free-safety-guide/)

---

### 👀 Elimina informació sobre tu d'internet

Si estàs a punt de convertir-te en una figura pública o estàs patint assetjament, considera les suggerències següents.

#### Netegeu la vostra presència a les xarxes socials

Potser no cal que elimines tot el teu compte, però considera esborrar (o fer privades) les publicacions antigues o les que revelen massa informació sobre on vius, on vas i amb qui ets.

##### Facebook

-   **Vegeu quin aspecte té el vostre perfil públic i suprimiu o limiteu allò que considereu oportú.**
    -   Escriptori: ves al teu perfil i fes clic al botó 👁 situat a la dreta del botó `Edita el perfil`.
    -   Mòbil: ves al teu perfil, toca els tres punts a la dreta de " `Afegeix una història` " i toca " `Veure com a`".
-   **Fes que només els amics puguin veure les teves publicacions anteriors.**
    -   Ordinador: Ves a `Configuració → Privacitat → Limita les publicacions anteriors`.
    -   Mòbil: Ves a `Configuració i privacitat → Configuració → Configuració de privacitat → Limita qui pot veure les publicacions anteriors`.
-   **Considera esborrar en massa les publicacions anteriors.** Per esborrar diverses publicacions d'una sola vegada:
    -   `Configuració i privacitat → Diari d'activitat → Les teves publicacions` i després selecciona `Arxivar` o `Mostrar a la brossa`

##### Instagram

-   Repassa el teu perfil i elimina manualment les publicacions. Toca els tres punts a la cantonada superior dreta d'una foto o vídeo.
-   Si necessites suprimir publicacions en massa:
    -   Des de l'aplicació mòbil, ves a `Configuració i activitat → La teva activitat → Fotos i vídeos → Publicacions`, `Reels` o `vídeos → Selecciona` i després tria `Arxivar` o `Suprimir.`
-   Per descarregar el teu arxiu abans d'esborrar res:
    
    -   Des de l'aplicació mòbil, aneu a `Configuració i activitat → Centre de comptes → La teva informació i permisos → Descarrega la teva informació`.
-   Considera desactivar la funció d'arxiu automàtic de les històries. Tingues en compte, però, que ja no podràs accedir a les històries anteriors després de 24 hores.
    
    -   Des de l'aplicació mòbil, aneu a `Configuració i activitat → Arxiu i descàrrega → La teva aplicació i els teus mitjans → Desa la història a l'arxiu`.

##### X/Twitter

-   Localitza i elimina manualment publicacions individuals utilitzant [la seva cerca avançada](https://twitter.com/search-advanced).
-   Suprimeix-les a l'engròs fent servir [Cyd](https://cyd.social/), [TweetDelete](https://tweetdelete.net/) o [Tweet Deleter](https://tweetdeleter.com/) 💰.

##### Mastodon

-   Inicia la sessió al teu servidor a través del seu lloc web i explora les opcions a `Preferències → Supressió automàtica de publicacions`.

##### LinkedIn

-   Modifiqueu [la configuració de visibilitat](https://www.linkedin.com/psettings/data-visibility) del vostre perfil. Assegureu-vos de limitar `qui pot veure o descarregar la vostra adreça de correu electrònic` i `qui pot veure les vostres connexions`.

##### Reddit i altres fòrums

-   Sovint no hi ha una solució fàcil. De vegades has d'esborrar tot el teu compte.
-   En el cas de Reddit, has de [fer servir scripts de tercers](https://social.techjunkie.com/how-to-delete-all-reddit-posts/) perquè eliminar el compte encara deixa les teves publicacions en línia.

#### Suprimeix els teus comptes de xarxes socials... temporalment

Moltes empreses de xarxes socials et permeten restaurar el teu compte eliminat després d'un període determinat. Això pot ser útil si vols amagar-te una estona i esperar que passi un esdeveniment.

-   **Facebook**: [llegeix les instruccions](https://www.facebook.com/help/224562897555674) per desactivar o suprimir temporalment el teu compte. Tens 30 dies després de la desactivació per revertir-ho.
-   **Instagram** [Llegeix les instruccions](https://help.instagram.com/370452623149242/) per desactivar temporalment el teu compte, però l'eliminació sembla permanent.
-   **X/Twitter** [Llegeix les instruccions](https://help.twitter.com/en/managing-your-account/how-to-deactivate-twitter-account) per desactivar el teu compte. S'eliminarà permanentment si no inicies la sessió durant 30 dies.
-   **Snapchat** [Llegeix les instruccions](https://support.snapchat.com/en-US/a/delete-my-account1) per esborrar el teu compte. S'esborrarà permanentment si no inicies la sessió durant 30 dies.

#### Elimina la teva informació dels comptes o llocs web d'altres persones

_Recorda: les sol·licituds d'eliminació d'informació triguen a processar-se i sovint requereixen intents repetits._

-   Utilitza l'eina " [Resultats sobre tu" de Google](https://myactivity.google.com/results-about-you) per cercar llocs web que llisten el teu nom, número de telèfon, adreça de domicili i/o adreça de correu electrònic junts, i sol·licita que s'eliminin dels resultats de cerca de Google.
-   Demana [a Google](https://support.google.com/websearch/troubleshooter/3111061?hl=en) i [Bing](https://www.microsoft.com/en-ca/concern/bing) que eliminin els resultats de cerca que apunten a pàgines amb la teva informació personal.
-   [Demana a Google Maps](https://support.google.com/maps/answer/15439776) que difuminés la imatge de Street View de casa teva.
-   Elimina qualsevol ressenya de negocis locals que hagis deixat a Google Maps, Yelp, etc. Podrien assenyalar la teva llar o llocs que visites sovint.
-   Segueix la [guia](https://www.cybercivilrights.org/online-removal) de la Cyber Civil Rights Initiative [per eliminar de les xarxes socials les publicacions o continguts que incompleixen les polítiques](https://www.cybercivilrights.org/online-removal).
-   Si ho voleu fer vosaltres mateixos, consulteu [BADBOOL](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List) de Yael Grauer. (Per ser del tot exhaustius, utilitzeu-ho a més dels serveis de pagament amb [el gràfic "Fill in the Gaps](https://docs.google.com/spreadsheets/d/115L6LpQg_UX638IyUfdwGhRS7dIU3lKwz6fjAcDtE-0/)" de Yael.)
-   Si esteu disposats a pagar 💰, [BADBOOL](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List?tab=readme-ov-file#additional-options-paid-and-free) recomana utilitzar [EasyOptOuts](https://easyoptouts.com/) per eliminar la vostra informació de llocs públics i de pagament en anglès.
-   Si vius als EUA, [l'aplicació Permission Slip de Consumer Reports](https://www.permissionslipcr.com/) (només per a iOS) ajuda a automatitzar les sol·licituds de supressió a més de 40 empreses nord-americanes.

#### Elimina articles i publicacions de premsa sobre tu en línia

_Nota: Com més gran sigui la publicació, més difícil serà convèncer-la._

-   **Considera-ho una reducció de riscos, no una eliminació total.** Serà impossible eliminar-ho tot.
-   **Contacta amb l'editor o amb el teu contacte anterior.** Explica la teva situació amb honestedat i espera que l'editor o l'escriptor sigui comprensiu.
    -   Si creus que l'editor o l'escriptor no respondrà bé, potser és millor no contactar-lo; fer-ho podria cridar més l'atenció sobre la teva situació.
-   **Per als articles més antics,** pot ajudar recordar-los que l'article encara és fàcilment accessible als motors de cerca.
-   **Recorre a l'ajuda d'un advocat.** De vegades, l'amenaça d'una acció legal convèncerà un editor reticent.

#### Emborroreu la vostra informació personal

-   **Vegeu l'escenari:** `enmascarar la vostra identitat per a cites en línia, esdeveniments o organització`.
-   **Obtén una bústia de correu** a una oficina de correus o utilitza [Earth Class Mail](https://www.earthclassmail.com/) (només als EUA) per amagar la teva adreça particular.
    -   Si vius als EUA, podries optar al [Programa de Confidencialitat d'Adreça](https://en.wikipedia.org/wiki/Address_confidentiality_program) del teu estat si ets víctima d'abusos o treballador sanitari. Les normes varien d'un estat a l'altre.
-   **Suprimeix els comptes antics per eliminar les empremtes d'informació personal d'internet.** Fes servir el directori [JustDeleteMe](https://justdeleteme.xyz/) per accelerar aquest procés.

---

### 🧹 Neteja de primavera de missatges i dades antics

Quan et roben el dispositiu o l'hackejen, el lladre també obté accés a totes les dades que hi ha a dins. Per tant, sempre és bo guardar tan poques dades com puguis als teus dispositius, especialment al telèfon mòbil. Recomanem fer una neteja de primavera als teus dispositius un cop l'any i/o abans de fer viatges llargs.

#### Correu electrònic

##### Gmail

-   Segueix [aquestes instruccions](https://support.google.com/accounts/answer/3024190) per utilitzar Google Takeout per descarregar les teves dades (inclosos els correus electrònics).
    -   Per descarregar només els correus electrònics d'un període de temps específic, per exemple, del 2015 al 2020, crea una etiqueta amb aquest interval de dates [seguint aquestes instruccions](https://support.cloudhq.net/how-to-create-a-gmail-label-with-email-messages-in-certain-date-range/) i, a continuació, selecciona aquesta etiqueta a Google Takeout.
-   Seguiu [aquestes instruccions](https://zapier.com/blog/how-to-mass-delete-emails-gmail/#date) per esborrar correus electrònics antics filtrant per un interval de dates i, a continuació, eliminant tot el que hi hagi dins d'aquest període de temps. (Alternativament, si n'heu creat una etiqueta, només cal que seleccioneu tot el que hi ha sota aquesta etiqueta.)

#### Aplicacions de missatgeria

##### WhatsApp

-   Hi ha diverses opcions per esborrar o buidar xats:
    -   Desplaça per eliminar converses individuals.
    -   Suprimeix el contingut de les xerrades però conserva els grups de xerrada:
        -   `Configuració → Xats → Esborra tots els xats`.
    -   Suprimeix tots els xats, inclosos els grups de xat:
        -   `Configuració → Xats → Suprimeix tots els xats`.Considera desactivar les còpies de seguretat de xat a WhatsApp:
-   Considera desactivar les còpies de seguretat dels xats a WhatsApp:
    -   `Configuració → Xats → Còpia de seguretat dels xats`.
-   Si vols esborrar les teves còpies de seguretat anteriors, aquí tens les instruccions per a:
    -   [iOS](https://faq.whatsapp.com/iphone/chats/how-to-turn-off-icloud-backup/)
    -   [Android](https://faq.whatsapp.com/android/how-to-delete-backups/)

##### Missatges d'Apple/iMessage

-   Descarrega els teus missatges abans d'esborrar-los amb l'eina de tercers [imessage-exporter](https://github.com/ReagentX/imessage-exporter/). És gratuïta, però has d'utilitzar la línia d'ordres (l'aplicació Terminal). Si no estàs familiaritzat amb el Terminal però igualment vols provar-ho, [aquest article té un bon tutorial del procés](https://www.cultofmac.com/how-to/back-up-messages).
-   Considera activar l'eliminació automàtica després que hagi passat un cert període de temps. A iOS, ves a `Configuració → Aplicacions → Missatges → Retén missatges`. Configura que els missatges es retinguin només durant 30 dies o 1 any.

##### Signal

-   Si el temporitzador de missatges que desapareixen no és suficient, pots esborrar els xats un per un o esborrar-ho tot.
    -   Per esborrar-ho tot, ves a `Configuració → Xats → Esborra l'historial de xat`.

##### Instagram

-   Abans d'esborrar res, descarrega les teves publicacions i històries seguint [aquestes instruccions per exportar la teva informació d'Instagram](https://help.instagram.com/181231772500920).
-   L'única manera d'esborrar en massa les històries anteriors [és desactivar la funció d'arxiu automàtic](https://www.facebook.com/help/1935507879999791/). Desactiva-la durant un dia per esborrar les històries anteriors i considera mantenir-la desactivada també després.
-   Per esborrar més ràpidament les converses de missatges directes d'Instagram, canvia el teu compte de personal a empresarial. A continuació, a la finestra de xat, toca `...` i després `Selecciona xats` per seleccionar diversos xats alhora.

#### Fotos i vídeos

Recomanem descarregar les fotos i vídeos del telèfon al Mac i després esborrar-los del dispositiu. No recomanem utilitzar serveis al núvol com ara iCloud Photos o Google Photos perquè els teus mitjans són accessibles des del dispositiu per sempre.

##### Des d'un telèfon iPhone o Android a un ordinador Mac

-   Connecta el telèfon al teu ordinador amb un cable USB i utilitza l'aplicació Image Capture ([instruccions detallades aquí](https://blinksandbuttons.net/how-to-download-pictures-from-camera-to-mac/)).
-   Per esborrar fotos en massa, selecciona-les i elimina-les a l'aplicació Image Capture.

#### Historial del navegador web

Si creus que el teu historial de navegació revela informació privada sobre tu, considera esborrar-lo i començar de zero.

##### Al teu ordinador

-   macOS Firefox: `Preferències → Privadesa i seguretat: Galetes i dades del lloc → Historial de navegació i descàrregues`

##### Al telèfon:

-   Safari d'iOS: `Configuració → Aplicacions → Safari: Historial i dades del lloc web → Esborra l'historial i les dades del lloc web`

#### Altres

-   **Google Drive:** Assegura't de comprovar dues vegades el que hi ha a la secció `«Compartit amb mi»`, ja que Google Drive afegirà a aquesta llista qualsevol document compartit en què hagis fet clic.

---

### 💔 Com tractar el stalkerware/spyware

Quan algú proper a tu (normalment una parella sentimental) t'espia amb una aplicació oculta al teu dispositiu mòbil, aquesta persona està utilitzant _stalkerware_.

#### Si no n'estàs segur i les coses no han empitjorat entre tu i la teva parella

-   **Mantingueu un registre ocult d'incidents sospitosos amb bolígraf i paper.**
-   **Reinicia el telèfon cada dia** mentre això passi. De vegades, això obliga les aplicacions espia a deixar de funcionar.
-   **Assegura't que la teva parella no estigui obtenint informació de comptes compartits anteriorment.** Li vas compartir el teu calendari? Teniu cap compte en línia conjunt?
-   **Inicieu la sessió als vostres comptes importants i cerqueu qualsevol sessió iniciada sospitosa.** Instruccions per a:
    -   [Gmail](https://support.google.com/mail/answer/45938?#zippy=%2Cconcurrent-session-information)
    -   [Facebook](https://www.facebook.com/help/211990645501187)
    -   [Instagram](https://help.instagram.com/2761108904184084)
    -   [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps#sessions)
    -   [Microsoft](https://support.microsoft.com/en-us/account-billing/check-the-recent-sign-in-activity-for-your-microsoft-account-5b3cfb8e-70b3-2bd6-9a56-a50177863357)
-   **Comproveu si heu configurat l'ús compartit de la ubicació en una aplicació.** Instruccions per a:
    -   [Google Maps](https://support.google.com/maps/answer/7326816)
    -   macOS: [Troba el meu](https://support.apple.com/en-ca/HT210514)
-   **Si utilitzeu un iPhone, executeu la comprovació de seguretat** per revisar què heu compartit i amb qui:
    -   `Configuració → Privadesa i seguretat → Comprovació de seguretat`
-   **Analitza el teu telèfon en busca de programari espia d'alt nivell amb [iVerify](https://iverify.io/products/basic).** La versió bàsica de l'aplicació costa només 1 $ i et permet fer una anàlisi forense una vegada al mes.
-   **No elimineu les aplicacions sospitoses immediatament.** Potser les necessiteu com a prova. A més, eliminar-les també podria fer que la situació amb la vostra parella s'agreugés.
-   **Revisa i torna a fer els passos dels `nivells 1–4` d'aquesta guia.** Assegura't de:
    -   Restablix les contrasenyes dels comptes importants.
    -   Comprova la configuració de la teva privacitat.
    -   Cerqueu qualsevol aplicació que no reconegueu al vostre ordinador i telèfon.
    -   Assegura't de buscar també aplicacions ocultes. Instruccions per a:
        -   iOS: A la pantalla d'inici, continua lliscant cap a l'esquerra fins que arribis a la pantalla `de la Biblioteca d'aplicacions`. Desplaça't fins a la part inferior, al grup `Ocultat`. Toca per obrir-lo i desbloqueja'l amb Face ID o codi d'accés.
        -   Android: Vegeu totes les aplicacions, incloses les ocultes, a `Configuració → Aplicacions → Veure totes les aplicacions`
-   **Estigues atent a altres senyals.** Exemples inclouen:
    -   La bateria del telèfon es descarrega de sobte molt més ràpidament que abans.
    -   La connexió a Internet del teu ordinador és més lenta del que és habitual.
    -   Rebs correus electrònics o notificacions que indiquen que algú altre ha iniciat la sessió en un compte.
    -   La teva parella et demana de sobte que li deixis el telèfon.
-   **Comprova si algú està utilitzant una fitxa/etiqueta de seguiment per seguir-te.** Per sort, les dues fitxes/etiquetes de seguiment més populars tenen funcions antiassetjament.
    -   Instruccions per escanejar:
        -   Apple Airtags: [iOS](https://support.apple.com/HT212227), [Android](https://support.apple.com/HT212227#trackerdetect)
        -   [Tiles](https://tileteam.zendesk.com/hc/articles/4415488529943)
    -   Eina addicional: AirGuard per [a iOS](https://apps.apple.com/us/app/airguard-tracking-protection/id1659427454) i [Android](https://github.com/seemoo-lab/AirGuard)

#### Si estàs bastant segur que t'estan espiant i tens por

_No ho passis sol: busca ajuda:_

-   **Contacta amb un amic de confiança (a través d'un telèfon o línia pública).** Demana-li que et doni suport i espai per a tu i la teva situació. Pot ser el teu confesor mentre t'ajuda a analitzar la gravetat de l'amenaça.
-   **Contacta amb una de les moltes organitzacions especialitzades en stalkerware i violència domèstica (a través d'un telèfon o línia pública o d'un amic).** Algunes t'ajuden a recopilar proves i a eliminar el stalkerware de manera segura.
    -   Consulta la [llista global d'organitzacions de suport directe](https://stopstalkerware.org/resources/) de la Coalició contra l'Stalkerware.
-   **Conserva registres digitals i impresos dels textos, correus electrònics, trucades, etc., rellevants.**
    -   Consulta [la guia](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence) de NNEDV [sobre com documentar i desar proves](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence).
-   **Quan ja no necessitis proves, elimina les aplicacions sospitoses/stalkerware tu mateix fent un restabliment de fàbrica al teu ordinador/telèfon.** Comprar un dispositiu nou de trinca és, per descomptat, encara més segur.
    -   **Recorda reinstal·lar les aplicacions i importar les dades manualment,** per evitar restaurar una còpia de seguretat que contingui el stalkerware.

#### Recursos addicionals

-   Consumer Reports: [Mantingueu els assetjadors fora de la vostra tecnologia](https://www.consumerreports.org/digital-security/shut-stalkers-out-of-your-tech/)
-   Wirecutter: [Protegix els teus dispositius contra els maltractadors domèstics](https://thewirecutter.com/blog/domestic-abusers-can-control-your-devices-heres-how-to-fight-back/)
-   Apple iOS: [Guia d'usuari de seguretat personal: Mantingueu-vos segur i mantingueu les vostres dades privades](https://support.apple.com/en-ca/guide/personal-safety/welcome/web)

---

### 📰 Investigar i escriure sobre temes sensibles

A continuació, es presenten algunes recomanacions generals que tots els periodistes i investigadors haurien de considerar, especialment aquells que treballen amb fonts (humanes). Si teniu accés a experts i sessions de formació a través de la vostra empresa o comunitats professionals, us recomanem encaridament que en feu ús.

#### Estigues preparat

-   **Per esborrar de manera remota el contingut dels teus dispositius.** Vegeu l'escenari següent titulat: `Algú m'ha agafat el telèfon/ordinador!`
-   **Per ser destinatari d'una campanya de pesca electrònica** (ja que els correus electrònics dels periodistes solen ser més públics que els d'altres).

#### Protegiu les vostres fonts

-   **Utilitza el correu electrònic el mínim possible.** Fins i tot el correu electrònic xifrat de fi a fi [deixa un rastre de metadades](https://freedom.press/training/blog/how-reporters-emails-get-got-case-studies-legal-request-hacking/).
-   **Utilitza una aplicació de missatgeria amb xifrat de fi a fi que no emmagatzemi metadades per intercanviar missatges.** No facis servir els missatges directes d'X/Twitter!
-   **Per a trucades de veu/vídeo, utilitza també una aplicació amb xifrat de fi a fi.**
-   **Utilitza les funcions de seguretat de Signal i WhatsApp.** Consulta els articles de Martin Shelton sobre [com protegir Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) i [com millorar la seguretat de WhatsApp](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3).
-   **Per facilitar les denúncies anònimes, feu que la vostra organització configuri una [Hush Line](https://hushline.app/)**.
-   **Per a les transferències de documents, feu que la vostra organització configuri [SecureDrop](https://securedrop.org/).** Si no, animeu la gent a fer servir [OnionShare](https://onionshare.org/).
-   **Desfoca els rostres de les fotos i vídeos.** Llegeix les recomanacions pertinents a l'escenari titulat `«Assistència a una protesta`».
-   **Consulteu [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/) de Ted Han i Quinn Norton.**
-   **Consulteu l'article de Martin Shelton [«Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/)».**

#### Protegiu-vos

-   **Utilitza un número de telèfon secundari a les aplicacions de missatgeria per parlar amb les teves fonts.**
-   **Crea una línia de consells pública amb el teu número de telèfon secundari.** Segueix la guia de Yael Grauer: [Com utilitzar Signal sense donar el teu número de telèfon amb un Chromebook i un telèfon antic](https://blog.yaelwrites.com/how-to-use-signal-without-giving-out-your-phone-number-using-a-chromebook-and-an-old-phone/).
-   **Si viatges,** revisa l'escenari titulat `«Creuar una frontera internacional`».
-   **Si cobreixes una protesta,** revisa l'escenari titulat `«Assistència a una protesta»` i decideix quines parts s'apliquen a tu (si tens drets o proteccions especials de periodista on treballes).
-   **Si esteu investigant a les xarxes socials,** feu-ho des d'un compte separat que utilitzi un àlies (no el vostre nom real). Configureu aquest compte amb una adreça de correu electrònic d'un sol ús. (No totes les redaccions/empreses ho permeten, però estireu les fronteres permeses tant com pugueu.)
-   **Amaga d'on et connectes als llocs web que visites.** Fes servir una VPN o [el navegador Tor](https://www.torproject.org/), especialment si naveguessis per internet a casa o a l'oficina. No vols que els administradors dels llocs web vegin que hi accedeixes des de la xarxa de l'oficina _del New York Times_, per exemple.

#### Protegiu les vostres dades

_Nota: [Els tribunals poden obligar empreses com Google a lliurar totes les teves dades](https://medium.com/@tinfoilpress/newsrooms-lets-talk-about-g-suite-1672a36eb235)._

-   **Utilitza un proveïdor de correu electrònic i d'emmagatzematge que no sigui propietat d'una organització sobre la qual informis.**
-   **Mou tota la teva feina a plataformes amb xifratge de fi a fi.**
    -   Plataformes de correu electrònic recomanades: [Proton Mail](https://protonmail.com/), [Tuta Mail](https://tutanota.com/)
    -   Plataforma de documents/full de càlcul recomanada: [CryptPad](cryptpad.fr/)
    -   Plataformes de núvol recomanades: [Tresorit](https://tresorit.com/), [Proton Drive](https://proton.me/drive)
-   **Desa les dades sensibles en un núvol protegit per contrasenya o en un dispositiu d'emmagatzematge extern sempre que sigui possible.** Llegeix les recomanacions pertinents a la nostra secció `de Nivell 4` anterior.
-   **Suprimeix de manera permanent els fitxers sensibles del teu ordinador.** Aplicacions recomanades:
    -   macOS: [CleanMyMac X](https://macpaw.com/cleanmymac) (la seva funció de trituració de fitxers està inclosa en la versió de prova gratuïta)
    -   Windows: [Eraser for Windows](https://sourceforge.net/projects/eraser/)

---

### 😭 Dispositiu perdut o robat

-   **Cerqueu, bloquegeu o esborreu el dispositiu de forma remota.** Instruccions per a:
    -   iOS i macOS: [Find My](https://support.apple.com/HT210515)
    -   Android: [Find Hub](https://support.google.com/accounts/answer/6160491)
    -   Windows: [Troba el meu dispositiu](https://support.microsoft.com/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316)
-   **Elimineu l'accés a tots els comptes importants del dispositiu perdut** iniciant la sessió des d'un altre dispositiu i, a continuació, tancant totes les altres sessions actives.
    -   Instruccions per a:
        -   [Gmail](https://support.google.com/mail/answer/45938?#zippy=%2Cconcurrent-session-information)
        -   [Facebook](https://www.facebook.com/help/211990645501187)
        -   [Instagram](https://help.instagram.com/2761108904184084)
        -   [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps#sessions)
        -   [Microsoft](https://support.microsoft.com/en-us/account-billing/check-the-recent-sign-in-activity-for-your-microsoft-account-5b3cfb8e-70b3-2bd6-9a56-a50177863357)
-   **Suprimeix l'accés a la teva aplicació d'autenticació al dispositiu perdut** (si fas servir una aplicació que admet diversos dispositius).
    -   Instruccions per a:
        -   Ente Auth: `Configuració → Seguretat → Veure sessions actives`, i després toca'n una per finalitzar-la.
        -   [Authy](https://help.twilio.com/articles/19753662574363)
-   **Elimina l'accés al teu gestor de contrasenyes al dispositiu perdut** de la mateixa manera.
    -   Instruccions per a:
        -   1Password: Toca/fes clic a la icona/nom del teu perfil, després `Gestiona comptes → Comptes → [Nom del teu compte] → Dispositius i navegadors de confiança`, i tria `Desautoritza` al dispositiu perdut
        -   Bitwarden: `Configuració → Els meus comptes → Desautoritzar sessions`
-   **Canvia la contrasenya dels comptes importants** (bancaris, de correu electrònic, de xarxes socials) si penses que algú la podria fer servir malament.
-   **Per evitar-ne un mal ús, aconsegueix una nova targeta SIM i cancel·la l'antiga.** Assegura't de fer-ho només després d'haver intentat trucar al teu telèfon per contactar amb qui l'hagi recollit.
-   **Si recuperes el dispositiu, restableix-lo** a la configuració de fàbrica i restaura'l des de la darrera còpia de seguretat.
-   **Si les autoritats us confisquen el dispositiu en un punt de passada fronterera internacional, demaneu un rebut de confiscació** (disponible en algunes jurisdiccions, com ara [el Canadà](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf)).

---

### 👾 Com comprovar si el teu dispositiu ha estat piratejat

-   **Inicieu la sessió als vostres comptes importants i cerqueu qualsevol sessió iniciada sospitosa.** Instruccions per a:
    -   [Gmail](https://support.google.com/mail/answer/45938?#zippy=%2Cconcurrent-session-information)
    -   [Facebook](https://www.facebook.com/help/211990645501187)
    -   [Instagram](https://help.instagram.com/2761108904184084)
    -   [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps#sessions)
    -   [Microsoft](https://support.microsoft.com/en-us/account-billing/check-the-recent-sign-in-activity-for-your-microsoft-account-5b3cfb8e-70b3-2bd6-9a56-a50177863357)
-   **Utilitza les eines integrades del dispositiu per buscar patrons irregulars.**
    
    -   Al teu ordinador, busca qualsevol procés que estigui consumint molta CPU o que tingui noms que no reconeixis (busca'ls per assegurar-te). Fes servir aquestes eines:
        -   macOS: Monitor d'activitat
        -   Windows: Process Explorer per veure quins processos/aplicacions s'estan executant. Cerqueu qualsevol nom sospitós a Google.
    -   Al telèfon, cerqueu aplicacions que consumeixin una quantitat de bateria o dades anormalment gran. Feu servir aquestes eines:
        -   iOS: `Configuració → Bateria → Ús de la bateria per aplicació`
        -   iOS: `Configuració → Dades mòbils → Dades mòbils`
        -   Android: `Configuració → Bateria → Ús de bateria`
        -   Android: `Configuració → Xarxa i Internet → Targetes SIM → Ús de dades d'aplicacions`
        -   Android: `Configuració → Xarxa i Internet → Internet → Ús de dades no d'operador`Si utilitzeu un iPhone:
    -   Si utilitzeu un iPhone:
        -   Comprova si pots anar a `Configuració → General → Perfils` i, si està disponible, busca qualsevol cosa que no reconeguis.
        -   Al Safari, introdueix l'URL `videos://`. Si funciona, et demanarà que obris l'aplicació de TV. Cancela-ho i, a continuació, escriu una nova URL: `cydia://`. Hauria de dir: «El Safari no pot obrir la pàgina perquè l'adreça és invàlida».
-   **Descarregueu aplicacions de tercers que analitzen les connexions de xarxa i detecten programari maliciós als vostres dispositius:**
    
    -   [Charles Proxy](https://www.charlesproxy.com/) per a Windows, macOS i Linux
    -   [Glasswire](https://www.glasswire.com/) per a Windows, Android
    -   [Little Snitch](https://www.obdev.at/index.html) per a macOS
    -   [Eines d'Objective-See](https://objective-see.org/index.html) per a macOS
    -   [iVerify](https://iverify.io/products/basic) per a iOS, Android
-   **Configurar un telèfon de recanvi com a monitor d'habitació** per detectar intrusions físiques no desitjades. Exemples d'aplicacions:
    -   [Alfred](https://alfred.camera/) per a iOS i Android
    -   [Haven](https://guardianproject.info/apps/org.havenapp.main/) per a Android
-   **Posa el telèfon o la tauleta en «mode de bloqueig» (només per a iOS)** per bloquejar la majoria de missatges i connexions entrants mentre ho resols:
    -   [Llegeix l'article d'Apple Support sobre això.](https://support.apple.com/en-us/HT212650)
    -   `Configuració → Privadesa i seguretat → Mode de bloqueig → Activa el mode de bloqueig`

---

### 😣 Demanar ajuda en una emergència

#### Línies d'ajuda i serveis d'assistència

Aquestes solen encaixar en diverses categories:

1.  Per a residents d'un país o jurisdicció: Feu una cerca a Internet d'associacions i ONG locals.
2.  Per a les víctimes de violència de gènere: consulteu [el directori global](https://www.chayn.co/global-directory) de Chayn, [els recursos de suport directe](https://stopstalkerware.org/resources/) de la Coalició contra el stalkerware i [la llista de suport global](https://www.esafety.gov.au/key-topics/image-based-abuse/getting-help-outside-australia) d'eSafety.
3.  Per als membres de la societat civil: Consulteu [la llista de línies d'ajuda i punts d'assistència per a la resiliència i la seguretat digital](https://securitylab.amnesty.org/digital-resources/) de l'Amnesty International Security Lab.

#### Si algú altre ha pres el control dels teus comptes

-   Consulteu [la llista d'instruccions per recuperar l'accés](https://securityplanner.consumerreports.org/tool/regain-control-of-hacked-accounts) del Security Planners de Consumer Reports.

#### Si has estat víctima d'una estafa en línia, d'un frau o d'un ransomware

-   Consulteu [la llista](https://support.microsoft.com/en-us/windows/protect-your-pc-from-ransomware-08ed68a7-939f-726c-7e84-a72ba92c01c3) de Microsoft [de llocs web per denunciar fraus i estafes governamentals](https://support.microsoft.com/en-us/windows/protect-your-pc-from-ransomware-08ed68a7-939f-726c-7e84-a72ba92c01c3) (desplaceu-vos fins a «Què fer si ja heu pagat»).

#### Si necessiteu enviar informació de manera segura als periodistes

-   [Drop a News Tip](https://docs.google.com/spreadsheets/d/e/2PACX-1vSRFKbJUtFQ55uB5NSaIgxUwQM8qRGMwLyybDWhqmqbCba_zaeDo5L7i3yJv8vb_Q_VqRvIwOcRKDeJ/pubhtml) té una llista de més de 50 organitzacions de notícies d'arreu del món que et permeten enviar informació a través de SecureDrop i/o una aplicació de missatgeria amb xifrat de fi a fi.

---

## 🎁 Eines i consells addicionals per a persones tècniques

Aquesta secció conté eines i consells addicionals que vam trobar durant la nostra recerca. Moltes de les recomanacions següents són populars entre els membres de la comunitat de la ciberseguretat, però les vam trobar una mica massa difícils d'utilitzar/seguir, o massa específiques per a un grup reduït de persones.

### Eines i consells per a la màxima seguretat

-   **Escriu i pren notes en aplicacions amb xifrat de fi a fi.** En lloc de Google Docs o Microsoft Office, utilitza [CryptPad](https://cryptpad.fr) o [Standard Notes](https://standardnotes.org/). Totes dues són de codi obert i gratuïtes.
-   **Comparteix fitxers de manera anònima** amb [OnionShare](https://onionshare.org/).
-   **Obtén una adreça de correu electrònic semipública temporal d'un sol ús** de [Maildrop](https://maildrop.cc/).
-   **Converteix els PDF sospitosos en segurs** amb [Dangerzone](https://dangerzone.rocks).
-   **Edita la configuració de la teva `Vista protegida` (només per a Windows)** si obres molts fitxers a [Microsoft Office](https://support.microsoft.com/en-us/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653) i [Adobe Acrobat](https://helpx.adobe.com/acrobat/using/protected-view-feature-pdfs-windows.html).
-   **Proveu una nova aplicació de missatgeria xifrada de punta a punta.** Sempre és bo tenir-ne més d'una instal·lada per si hi ha una avaria del servidor. Consulteu [la comparativa d'aplicacions de missatgeria segura](https://www.securemessagingapps.com/) de Mark Williams per a veure algunes opcions.
-   **Envia correus electrònics xifrats de fi a fi** amb [Proton Mail](https://protonmail.com/) o [Tuta Mail](https://tutanota.com/).
-   **Troba un servei de videotrucada amb xifrat de fi a fi** fent servir [la guia de Freedom of the Press](https://freedom.press/training/blog/videoconferencing-tools/).
-   **Envia un missatge autodestructible protegit amb contrasenya** utilitzant [One Time](https://onetimesecret.com/).
-   **Subscriviu-vos per rebre notificacions de [Have I Been Pwned](https://haveibeenpwned.com/)** quan un compte vinculat al vostre correu electrònic es vegi compromès.
-   **Escaneja els dispositius Bluetooth propers** (incloses les AirTags) amb [nRF Connect](https://www.nordicsemi.com/Products/Development-tools/nrf-connect-for-mobile).
-   **Augmenteu les barreres de protecció dels vostres comptes:**
    -   [Programa de Protecció Avançada de Google](https://landing.google.com/advancedprotection/): exigeix passis de connexió o claus de seguretat, és especialment curós amb les descàrregues i limita l'opció «Inicia la sessió amb Google» per a comptes, aplicacions i dispositius de Google.
    -   [Protecció de dades avançada d'Apple iCloud](https://support.apple.com/guide/security/sec973254c5f/web): activa el xifratge de fi a fi per a algunes aplicacions d'iCloud, però no per al Correu, els Contactes ni el Calendari.
    -   [Proton Sentinel](https://proton.me/support/proton-sentinel) 💰: crea registres d'«esdeveniments de seguretat» més detallats i ofereix un millor suport humà en matèria de seguretat per als serveis/aplicacions de Proton.
-   **Residents dels EUA: congeleu el vostre crèdit** per evitar que actors malintencionats accedeixin a la vostra informació personal o la facin servir malament. Només heu de reactivar-lo quan necessiteu fer-lo servir. Consulteu [la Guia de congelació de crèdit](https://inteltechniques.com/freeze.html) d'IntelTechniques per a més detalls.

### Eines i consells que costen diners

-   **Compra una [YubiKey](https://www.yubico.com/products/) USB per a l'autenticació de dos factors.** Si treballes en llibertat d'expressió, premsa o internet, potser et pots qualificar per a rebre una [Yubico](https://www.yubico.com/about/about-us/free-speech-program/) gratuïta [per a la llibertat d'expressió](https://www.yubico.com/about/about-us/free-speech-program/).
-   **Utilitza [el mode de viatge de 1Password](https://support.1password.com/travel-mode/)** per crear un conjunt de contrasenyes que no et portis amb tu quan viatges.
-   **Guardeu les targetes intel·ligents, els passaports i els telèfons en una bossa de Faraday que impedeixi que els senyals entrin i surtin.** (Consulteu [la guia de Micah Lee sobre aquest tema](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
-   **Compra un bloquejador de micròfon** de [Mic-Lock](https://mic-lock.com/) per endollar al telèfon i silenciar-ne el micròfon.
-   **Aconsegueix un encaminador centrat en la seguretat** de [pcWRT](https://www.pcwrt.com/) o [Peplink](https://www.peplink.com/).
-   **Compra un disc dur extern o una unitat USB amb xifratge de maquinari** de companyies com [Apricorn](https://www.apricorn.com/).

### Eines i consells amb corbes d'aprenentatge pronunciades

-   **Utilitza un servei DNS especialitzat per accedir a Internet**, com ara [Quad9](https://www.quad9.net/).
-   **Utilitza una aplicació de missatgeria descentralitzada i privada impulsada per la xarxa Tor**. Fes una ullada a [Ricochet Refresh](https://www.ricochetrefresh.net/).
-   **Accedeix a Facebook amb més anonimat i evita el filtratge d'Internet utilitzant [el seu servei onion](https://en.wikipedia.org/wiki/Facebookcorewwwi.onion).**
-   **Utilitza un sistema operatiu més segur per al teu ordinador.** Les opcions inclouen:
    -   [Tails](https://tails.boum.org/)
    -   [Qubes OS](https://www.qubes-os.org/)
-   **Reforça el teu telèfon Android** perquè sigui més segur i privat:
    -   **Utilitza [F-Droid](https://f-droid.org)**: una botiga d'aplicacions de codi obert i centrada en la seguretat.
    -   **Substitueix el sistema operatiu** amb què venia el teu telèfon:
        -   Si tens un telèfon de Google, instal·la [GrapheneOS](https://grapheneos.org/) o [CalyxOS](https://calyxos.org/).
        -   Si no tens un telèfon de Google, instal·la una versió "stock" de Android directament de Google i sense tots els extres que ha afegit el fabricant del teu telèfon. (Les instruccions varien segons el telèfon que tinguis, així que hauràs de fer una mica de recerca.)
-   **Comença a utilitzar dispositius supersegurs.** Les opcions inclouen:
    -   [PINE64](https://www.pine64.org/)
    -   [Purism](https://puri.sm/)

### Eines i consells per allotjar/gestionar un lloc web

-   **Llegiu [aquesta guia d'EDRi sobre el desenvolupament i manteniment ètics de llocs web](https://edri.org/ethical-web-dev/).** Pareu especial atenció a les seves recomanacions de privacitat.
-   **Protegiu el vostre lloc web d'atacs DDoS i altres amenaces utilitzant**
    -   **[Deflect](https://deflect.ca/).** Hi ha un [pla gratuït]([https://deflect.ca/nonprofit](https://deflect.ca/nonprofit) per a organitzacions sense ànim de lucre.
    -   **[Cloudflare](https://www.cloudflare.com/).** Hi ha un [pla gratuït](https://www.cloudflare.com/galileo/) per a organitzacions d'arts, drets humans, societat civil, periodisme o democràcia.
    -   **[Project Shield](https://projectshield.withgoogle.com) de Google.** Només disponible per a llocs de notícies, de drets humans i de seguiment electoral.
-   **Si utilitzeu WordPress, considereu utilitzar els següents complements**
    -   **[Wordfence](https://wordpress.org/plugins/wordfence/)**
    -   **[Sucuri Security](https://wordpress.org/plugins/sucuri-scanner/)**
    -   Si el vostre servei d'allotjament no ofereix còpies de seguretat, utilitzeu [VaultPress](https://jetpack.com/upgrade/backup/) o [BackupBuddy](https://ithemes.com/backupbuddy/).
    -   Alternativament, utilitzeu [Simply Static](https://simplystatic.com/) per convertir el vostre lloc de WordPress públic en un lloc estàtic.
-   **Utilitza un servei d'analítica orientat a la privacitat** com [Matomo](https://matomo.org/) o [Koko Analytics](https://www.kokoanalytics.com/).
-   **Considereu canviar a un servei d'allotjament més orientat a la privacitat** com ara [Greenhost](https://greenhost.net/), [Maadix](https://maadix.net/en/) o [1984](https://1984.hosting/).
-   **Crea un fitxer [security.txt](https://securitytxt.org/)** perquè els investigadors tinguin un lloc on revelar vulnerabilitats de seguretat.
-   **Creeu un fitxer robots.txt** utilitzant [aquesta llista ai.robots.txt](https://github.com/ai-robots-txt/ai.robots.txt) per evitar que les empreses d'IA rastrejin i rasquin les vostres dades.

---

_🏆 Ostres, has arribat al final. Això és el final. Gràcies per llegir. Gràcies per la teva meticulositat. Ets un veritable campió._

---

## 📝 Apèndix

### 🧠 Altres recursos

Hem consultat moltes fonts i ens hem basat en les nostres experiències per crear aquesta guia. Si no trobeu exactament el que voleu aquí, us recomanem consultar els recursos següents:

-   Consumer Reports: [Pla de seguretat](https://securityplanner.consumerreports.org/)
-   Electronic Frontier Foundation: [Autodefensa contra la vigilància](https://ssd.eff.org/)
-   Michael Horowitz: [Llista de comprovació de computació defensiva](https://defensivecomputingchecklist.com/)

### 📝 Llicència

Aquesta obra està sota una [llicència Creative Commons Reconeixement-NoComercial-CompartirIgual 4.0 Internacional](http://creativecommons.org/licenses/by-nc-sa/4.0/).

### 👋🏾 Agraïments especials

Un agraïment especial als [nostres col·laboradors de GitHub](https://github.com/narwhalacademy/zebra-crossing/graphs/contributors) i als membres de la comunitat que ens van enviar esmenes, suggeriments i traduccions.