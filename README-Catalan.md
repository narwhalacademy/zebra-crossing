# 🦓 Pas de zebra: una llista de comprovació de seguretat digital fàcil d'utilitzar

## 🎯 Comença aquí!

### 🤔 Llegeix aquesta guia si tu

-   Utilitzes internet diàriament — per a la feina, les xarxes socials i les transaccions financeres.
-   Vols garantir proactivament la teva seguretat i privadesa digitals, però no et trobes en perill imminent. (Si és el teu cas, contacta amb algú de la teva comunitat per a una consulta individual.)
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
-   **El nivell 3 t'ajudarà a afinar la teva privadesa en línia** i**a** reduir dràsticament la quantitat d'informació personal que comparteixes gratuïtament. Aquesta secció també trigarà d'1 a 2 hores.
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

-   **"Quin tipus de perill corro?"** Per exemple, robatoris de dades de targetes de crèdit, espionatge corporatiu o assetjament/revelació d'informació personal en línia (doxing).
-   **"Quin tipus d'actius protegeixo?"** Per exemple: documents confidencials, fotos privades o missatges personals.

Recorda, però, que el teu model d'amenaça pot canviar, ja sigui gradualment amb el temps o de manera abrupta, per exemple, quan de sobte s'aprova una nova llei.

### 🔗 L'enllaç més feble

**El punt més feble** és on la teva seguretat digital és més vulnerable. Per exemple, si la funció "he oblidat la contrasenya" d'un compte t'envia un enllaç al correu electrònic, els atacants només han d'accedir al teu correu electrònic per accedir al compte.

### 🔡 Nivells de xifratge

**El xifratge** és el procés de desordenar o codificar informació per fer-la il·legible per a tercers i evitar l'accés no autoritzat. Sovint, la gent classifica **el xifratge** en aquests tres tipus:

1.  **Sense xifratge:** qualsevol tercer pot interceptar les dades i llegir-les tal qual. Sovint s'anomena "text pla".
2.  **Xifratge estàndard:** Les dades es xifren de manera que tercers que les intercepten no les poden llegir, però la plataforma que s'utilitza per enviar les dades (p. ex., Facebook Messenger) les pot desxifrar i llegir-les. La plataforma pot lliurar les dades desxifrades als tribunals si se li ordena.
3.  **Xifratge d'extem a extrem:** només l'emissor i el receptor originals poden llegir les dades. La plataforma que s'utilitza per enviar les dades només té la versió xifrada i il·legible. Així que, si els tribunals ordenen a la plataforma que lliuri les dades, no hi ha res d'útil per lliurar.

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

El primer pany sol ser la contrasenya del vostre compte. El segon pany adopta una forma diferent i/o arriba per un canal diferent, la majoria de vegades com un codi enviat al vostre telèfon mitjançant una aplicació o un missatge de text (SMS). Aquest pany addicional s'anomena habitualment _autenticació de dos factors_ (abreujada com _2FA_ de l'anglès 2 Factor Authentication) o _verificació de dos passos_.

-   **Activa l'autenticació de dos factors als comptes importants que** acabes d'identificar. Per trobar instruccions sobre com fer-ho:
    -   Fes una cerca a Internet de " `autenticació de dos factors` " i el nom del compte
    -   Cerqueu el proveïdor del compte a [2fa.directory](https://2fa.directory)
-   **Utilitza una aplicació d'autenticació si n'hi ha una disponible.** Són més segures que utilitzar missatges SMS per rebre el codi de 2FA.
    -   Aplicacions recomanades:
        -   [2FAS](https://2fas.com) (si només utilitzes un dispositiu per obtenir els codis d'autenticació)
        -   [Ente Auth](https://ente.io/auth/) (si vols que els codis es sincronitzin en diversos dispositius)
    -   La majoria de comptes bancaris t'obligaran a fer servir la seva pròpia aplicació, així que no et preocupis si no pots fer servir una de les aplicacions anteriors per a això.
-   **Activa la còpia de seguretat al núvol per a la teva aplicació d'autenticació** per si mai perds el telèfon.
    -   Instruccions per a:
        -   2FAS: Ves a `Configuració → Còpia de seguretat 2FAS`
        -   Ente Auth: Crea un compte a l'aplicació

### 🔁 Activa les actualitzacions automàtiques del programari

La majoria de dispositius nous avui dia tenen les actualitzacions automàtiques activades per defecte, però val la pena comprovar-ho:

-   **Comproveu la configuració d'actualitzacions del sistema operatiu del vostre dispositiu:**
    -   En telèfons i tauletes:
        -  **iOS:** `Configuració → General → Actualització de programari → Actualitzacions automàtiques`
        -  **Android:** `Configuració → Sistema → Actualització del sistema`
    -   En ordinadors:
        -  **macOS:** `Configuració del sistema… → General → Actualització de programari → Actualitzacions automàtiques`
        -  **Windows 11:** `Inici → Configuració → Actualització de Windows → Opcions avançades`
        -  **Windows 10:** `Configuració → Actualització i seguretat → Actualització de Windows → Opcions avançades`
        -  **macOS:** Preferències del sistema… → General → Actualització de programari → Actualitza
        -  **GNU/Linux (segons la distribució):**
	        - **Ubuntu / Debian (i derivades):** Obre l'aplicació _Programari i actualitzacions_ (Software & Updates) → ves a la pestanya _Actualitzacions_. Allà pots configurar que es descarreguin i s'instal·lin automàticament les actualitzacions de seguretat. Des del terminal, pots actualitzar manualment amb: `sudo apt update && sudo apt upgrade`.
            - **Fedora / Red Hat:** Obre la botiga de _Programari de GNOME_ (GNOME Software) → fes clic al menú d'opcions (tres ratlles) → _Configuració d'actualitzacions_ i activa les actualitzacions automàtiques. Des del terminal, pots actualitzar manualment amb: `sudo dnf upgrade`.
            - **Arch Linux (i derivades com Manjaro):** En ser distribucions de llançament continu (_rolling release_), s'han d'actualitzar manualment molt sovint des del terminal executant: `sudo pacman -Syu`. També es poden fer servir assistents gràfics com _Pamac_ o _Octopi_ per rebre notificacions d'actualitzacions pendents.
-   **Comproveu la configuració d'actualitzacions de la botiga d'aplicacions principal del vostre dispositiu:**
    -  **iOS:** `Configuració → App Store → Descàrregues automàtiques: Actualitzacions d'aplicacions`
    -  Android: Obre `la Play Store`, després ves a `Configuració → Actualitzar automàticament les aplicacions`
    -  **macOS:** Obre `l'App Store` i després ves a `Configuració → Actualitzacions automàtiques`
    -  **Windows 10/11:** Obriu la `Microsoft Store`, després aneu a `Perfil → Configuració → Actualitzacions d'aplicacions`.
    -  **GNU/Linux (GNOME Software / KDE Discover):** Si utilitzes una botiga d'aplicacions gràfica integrada, obre-la i entra a la seva _Configuració_ (o Preferències). Assegura't d'activar les actualitzacions automàtiques, ja que això també mantindrà al dia els paquets en formats universals com **Flatpak** i **Snap**.
-   **Assegura't que el sistema operatiu del teu dispositiu encara pugui rebre actualitzacions:**
    -   Si han passat més de tres anys des que vas comprar el telèfon o l'ordinador, val la pena comprovar que encara reps actualitzacions.
        -  **Per a telèfons:** cerqueu [el vostre dispositiu a endoflife.date](https://endoflife.date/tags/device) i assegureu-vos que encara aparegui com a «compatible».
        -  **Per a macOS:** Esbrina quin sistema operatiu estàs utilitzant. Fes clic al logotip d'Apple a la cantonada superior esquerra i, a continuació, `a «Sobre aquest Mac`». Després, assegura't que a [aquesta pàgina d'endoflife.date](https://endoflife.date/macos) encara indiqui «Estat del servei: Sí».
        -  **Per a Windows:** Descobreix quin sistema operatiu estàs utilitzant. `Inici → Configuració → Sistema → Sobre.` A continuació, assegura't que encara rep suport de seguretat a [aquesta pàgina d'endoflife.date](https://endoflife.date/windows).
        -  **Per a GNU/Linux:**
	        - Primer, esbrina quina distribució i versió exacta utilitzes. Pots fer-ho anant a _Configuració → Sobre el sistema_ o obrint un terminal i escrivint: `cat /etc/os-release`.
            - Busca la teva distribució a [endoflife.date](https://endoflife.date "null") (per exemple, cerca _Ubuntu_, _Fedora_ o _Debian_).
            - Recorda que les versions **LTS (Long Term Support)** d'Ubuntu o Debian reben suport de seguretat durant 5 anys o més, mentre que les versions no-LTS d'Ubuntu o les de Fedora tenen un cicle de vida molt més curt (entre 9 i 13 mesos). Assegura't que la teva versió encara està en el període actiu de suport.
    -   Si ja no rep actualitzacions:
        -   Assegura't que has actualitzat a l'últim sistema operatiu que funciona al teu dispositiu. De vegades, una actualització es paralitza per falta d'espai al disc. (Hauràs rebut avisos sobre això si has seguit els passos anteriors.) O, en el cas de Windows, pot ser que hagis de comprar la nova edició.
        - **En el cas de GNU/Linux:** Si utilitzes una versió que ha arribat al final del seu cicle de vida (EOL de l'anglès End Of Life), només has de fer un canvi de versió (_upgrade_) des del propi gestor d'actualitzacions del sistema o del terminal. En gairebé totes les distribucions de Linux, el pas a una versió superior amb suport de seguretat és completament gratuït i fàcil de fer sense haver d'adquirir cap llicència.
        -   **Comenceu a investigar quin dispositiu voleu adquirir.** Si el maquinari ja no és compatible amb sistemes operatius moderns i segurs, de moment, seguiu la resta d'aquesta llista de comprovació per actualitzar tot el programari que falti i comenceu a planificar la substitució del dispositiu per un de més segur.

---

_👍 Excel·lent! Aquests passos senzills realment et mantindran segur la major part del temps. Pensa que és com tenir una bona i sòlida porta de seguretat a la porta d'entrada. No és infal·lible, però mantindrà casa teva segura la major part del temps. Continua per assegurar els petits detalls que més endavant es podrien convertir en vulnerabilitats._

---

## 🏃🏻‍♂️ Nivell 2: Assegureu tots els petits detalls

### 🧠 Utilitza contrasenyes difícils de endevinar per als comptes importants

Els atacants solen accedir al vostre compte si la vostra contrasenya és:

1.  Massa curta.
2.  Massa fàcil d'endevinar.
3.  Ja s'ha filtrat com a part d'una violació de dades/incident pirata i fas servir la mateixa contrasenya en diferents llocs.

Per tant, és crucial utilitzar una contrasenya diferent per a cada compte i assegurar-vos que siguin molt llargues i molt difícils de endevinar. Per ajudar a crear i emmagatzemar aquestes contrasenyes llargues, podeu:

1.  Utilitza aplicacions de gestor de contrasenyes.
2.  Inventa la teva pròpia fórmula que sigui un joc de paraules amb el servei al qual t'hi connectes.
3.  Escriu-les amb bolígraf i paper.

El que funciona millor és diferent per a tothom, i no cal que facis servir una única opció: pots combinar-les com vulguis. Per a una explicació més detallada i completa de les tres opcions, consulta l'article de Michael Horowitz [«The world's BEST password advice](https://michaelhorowitz.com/BestPasswordAdvice.php) ».

De moment, **centra't a assegurar-te que els comptes importants que vas identificar al Nivell 1 tinguin contrasenyes llargues, úniques i difícils de endevinar**. A continuació, tens una guia pas a pas de les tres opcions:

##### Opció 1: instal·lar un gestor de contrasenyes (recomanat)

Aquesta és una opció popular per a les persones que se senten còmodes amb finestres emergents addicionals. Una aplicació gestor de contrasenyes ajuda a generar contrasenyes llargues, les emmagatzema i les omple gairebé automàticament quan inicies la sessió en un lloc web.

-   **Gestors de contrasenyes recomanats:**
    -   [1Password](https://1password.com/) 💰
    -   [Bitwarden](https://bitwarden.com/)
-   **No recomanem els gestors de contrasenyes que vénen amb el sistema operatiu o el navegador web** perquè no funcionen fora del seu ecosistema (p. ex., Apple Passwords no funcionarà en un telèfon Android).
-   **Instal·la l'aplicació del gestor de contrasenyes** tant al telèfon com a l'ordinador.
-   **Instal·la l'extensió del gestor de contrasenyes** al navegador web del teu ordinador.
-   **Creeu només contrasenyes de més de 12 caràcters.** Recomanem utilitzar l'opció del gestor de contrasenyes que combina paraules aleatòries i sense relació entre si (p. ex., `planta-camió-nas-estructura-puntes`) perquè sigui fàcil escriure-les en aquells casos poc habituals en què l'emplenament automàtic no funciona.
-   **La propera vegada que hagis de teclejar la contrasenya d'un altre compte, crea-hi una entrada.** D'aquesta manera, aniràs afegint gradualment qualsevol compte que facis servir sovint al gestor de contrasenyes. Si ho fas a l'ordinador, l'extensió/add-on del navegador del gestor de contrasenyes capturarà les dades automàticament després que les teclegis.
-   **Fixa't que l'aplicació vincula la informació d'inici de sessió a l'URL. (adreça web)** Per tant, si ets en un lloc web i el gestor de contrasenyes no té cap entrada per a ell, vigila especialment que no sigui un lloc web de suplantació d'identitat (phishing).
-   **Transferiu tots els vostres comptes més endavant.** Introduir tots els vostres comptes al gestor de contrasenyes trigarà una estona, i és una tasca que és millor deixar per a un altre dia. (Hem col·locat aquesta tasca que porta temps al nostre `Nivell 3`.)
-   **No utilitzis el gestor de contrasenyes com a aplicació d'autenticació de dos factors.** És millor no posar tots els ous en una mateixa cistella.

##### Opció 2: utilitzar una fórmula

Aquesta opció la fan servir habitualment les persones amb una bona memòria i les que prefereixen tenir menys aplicacions per gestionar i menys finestres emergents per tocar als seus dispositius.

Aquí teniu un exemple d'una fórmula senzilla de [la llista de comprovació de Computació Defensiva](https://defensivecomputingchecklist.com/indexold.php#passwoyds):

> …un aficionat al beisbol podria començar cada contrasenya amb «BaseballRules!». Aleshores, si «jungle» fos la seva contrasenya per a Amazon.com, la contrasenya real seria «BaseballRules!jungle». I l'únic que hauries de recordar seria que la teva contrasenya d'Amazon és «jungle». Bastant fàcil. Amazon. Jungle. I la feble contrasenya "book" per a Barnes and Noble es converteix en una bona contrasenya ("BaseballRules!book") quan s'aplica la fórmula.

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

### 📱 Assegura els teus dispositius

#### Assegura el telèfon

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
    -   Android: `Configuració → Seguretat i privadesa → Altres configuracions: Més seguretat i privadesa → Seguretat: Protecció contra robatori`
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
    -   **GNU/Linux (segons la distribució):**
	    - **Ubuntu / Debian (i derivades):** Obre el terminal i executa `sudo ufw enable` (o utilitza l'eina gràfica `gufw`).  
		- **Fedora / Red Hat:** Obre el terminal i executa `sudo systemctl enable --now firewalld`.
	    - **Arch Linux (i derivades com EndeavourOS o Manjaro):** Activa el tallafocs de la teva elecció (p. ex., `sudo systemctl enable --now ufw` o `firewalld`).
-   **Desactiva l'accés remot del teu ordinador:**
    -   macOS: `Preferències del sistema → Compartició → Inici de sessió remot, Gestió remota`.
    -   Windows 10/11: `Configuració → Sistema → Escriptori remot → Escriptori remot: Desactivat`.
    -   **GNU/Linux (totes les distribucions):** Assegura't que el servei SSH està desactivat executant al terminal `sudo systemctl stop sshd` i `sudo systemctl disable sshd` (o desactiva la "Compartició de pantalla" / "Escriptori remot" des de l'apartat de Configuració del teu entorn d'escriptori, com GNOME o KDE).
-   **Configura un programari antivirus bàsic al teu ordinador:**
    -   macOS: No cal res.
    -   Windows 10/11: `Inici → Configuració → Actualització i seguretat → Seguretat de Windows → Protecció contra virus i amenaces`
	-  **GNU/Linux (totes les distribucions):** Per defecte no sol ser necessari un antivirus actiu, però per a escanejos puntuals pots instal·lar **ClamAV** (i la seva interfície gràfica `clamtk`) des del gestor de programari de la teva distribució. Es recomana sobretot si comparteixes fitxers sovint amb sistemes Windows.
-   **Si utilitzeu Microsoft Office: desactiveu els macros.** Els macros són fragments petits de codi que automatitzen accions que poden ser explotades per atacants. Tot i això, de vegades poden ser útils, per això recomanem l'opció `Desactiva tots els macros amb notificació`, que us permet executar manualment macros de fonts de confiança.
    -   Instruccions per a:
        -   [macOS](https://support.microsoft.com/en-us/office/enable-or-disable-macros-in-office-for-mac-c2494c99-a637-4ce6-9b82-e02cbb85cb96)
        -   [Windows](https://support.microsoft.com/en-us/office/macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6), que pot requerir [configuracions especials per a l'Excel](https://support.microsoft.com/en-us/office/change-macro-security-settings-in-excel-a97c09d2-c082-46b8-b19f-e8621e8fe373)

#### Seguritzeu el router Wi-Fi de casa

-   **Inicieu la sessió al tauler d'administració i configuració.** Normalment s'hi pot accedir anant a `http://192.168.0.1` al vostre navegador web. Si no, consulteu les instruccions que van amb el vostre router.
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
        - [macOS](https://support.apple.com/en-us/HT204837).
        - [Microsoft Windows](https://support.microsoft.com/en-us/windows/device-encryption-in-windows-10-ad5dcf4b-dbe0-2331-228f-7925c2a3012d) (utilitzeu [BitLocker](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) si està disponible).
        -  **GNU/Linux (totes les distribucions):** S'ha de seleccionar l'opció de xifratge de disc (**LUKS**) durant el procés d'instal·lació del sistema operatiu (marcant la casella "Xifra el disc" o "Encrypt system"). Post-instal·lació és un procés complex.
-   **Xifra l'emmagatzematge del telèfon.**
    -   iOS: Xifra automàticament.
    -   Android: Gairebé sempre xifra automàticament. Verifica-ho anant a `Configuració → Seguretat → Xifratge`.
-   **Xifra els teus discs durs de còpia de seguretat.**
    -   Instruccions per a:
        - [macOS (si utilitzeu Time Machine)](https://support.apple.com/en-ca/guide/mac-help/mh21241/mac)
        - [Microsoft Windows](https://web.archive.org/web/20250123165604/https://techjury.net/blog/how-to-encrypt-your-hard-drive/)
        - **GNU/Linux (totes les distribucions):** Pots fer servir l'eina gràfica de Discs (Gnome Disks) per formatar la unitat externa triant l'opció **"Ext4 protegit amb contrasenya (LUKS)"**, o utilitzar programari multiplataforma com **[VeraCrypt](https://veracrypt.io/en/Home.html)**.

### 🗓️ Atura les invitacions malicioses al calendari

Evita que les invitacions de calendari de persones que no coneixes apareguin automàticament al teu calendari; aquestes invitacions es poden utilitzar per enviar enllaços maliciosos.

-   [Configuració de](https://calendar.google.com/calendar/r/settings) Google Calendar `→ Configuració d'esdeveniments → Afegeix les invitacions al meu calendari: Quan responc a la invitació per correu electrònic`
-   Outlook: `Fitxer → Opcions → Calendari → Acceptació o rebuig automàtics → Acceptar/Rebre automàticament i Suprimir les reunions cancel·lades`
-   iCloud: A iOS: Ves a `Configuració → [El teu nom] → iCloud → Dades emmagatzemades a iCloud: Veure-ho tot → Calendari iCloud → Enviar i rebre → Rebre` i selecciona `Correu electrònic` per a cada compte.
---
_👍👍 Enhorabona! T'has endinsat sense por a la configuració —fent clic, tocant i lliscant— per tancar les llacunes de seguretat dels teus comptes i dispositius. Ara la següent secció tracta sobre aprendre i revisar els teus hàbits i reflexos pel que fa a la seguretat digital, així que serà principalment de lectura i reflexió (en lloc de tocar/fer clic als teus dispositius). No obstant això, encara recomanem que facis una pausa ara mateix perquè et mereixes de debò el que et queda de dia lliure._

---
## 💪🏽 Intermedi: Revisió d'hàbits i reflexos

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
        -   macOS Mail: Passa el cursor del ratolí per sobre d'un enllaç i espera uns segons que aparegui un missatge emergent.
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
-   **Actualitzacions del microprogramari *(firmware)*:** Comproveu ocasionalment si hi ha actualitzacions del microprogramari per al vostre *router* i altres dispositius connectats a Internet.

### 🙅🏾 No ho facis a casa (ni enlloc)

-   **No carreguis el telèfon en estacions o ports de càrrega públics.** Suposen un risc perquè els atacants podrien robar-te les dades. En lloc d'això, utilitza una bateria externa o porta el teu propi adaptador per connectar-lo directament a la presa de corrent.
-   **No connectis a l'ordinador memòries USB o unitats d'emmagatzematge que no coneguis.** Poden contenir programari maliciós.
-   **No introduïu contrasenyes en navegadors integrats a l'aplicació.** Quan una aplicació mòbil us permet navegar per una pàgina web sense obrir el navegador web (és a dir, un navegador integrat a l'aplicació), l'aplicació pot registrar els llocs web que visiteu i el que hi escriviu. Per tant, no hi escriviu res de sensible.
-   **No utilitzis Google/X/Twitter/Facebook per registrar-te o iniciar sessió en altres serveis,** ja que això proporciona a aquestes plataformes dades innecessàries sobre tu. Cada servei hauria de tenir el seu propi compte.

### 🏊🏼‍♀️ Altres hàbits saludables

-   **Reinicia el telèfon i l'ordinador un cop per setmana apagant-los i tornant-los a engegar** per netejar la memòria temporal (RAM) i perquè funcionin més fluidament.
-   **Quan descarregues una nova aplicació mòbil, comprova-ho dues vegades per confirmar que és la correcta.** Moltes aplicacions falses enganyen la gent fent servir un nom o una icona lleugerament modificats d'una aplicació existent i popular.
-   **Revisa regularment les aplicacions instal·lades al teu telèfon.** Elimina les que ja no fas servir.
-   **Esborra adequadament els teus dispositius abans de donar-los o regalar-los.** Si has xifrat els teus telèfons i ordinadors (com s'ha suggerit abans), un restabliment de fàbrica estàndard funcionarà en la majoria de casos.
    -   Si voleu una capa de seguretat addicional per a les unitats de disc del vostre ordinador, consulteu [la guia de Wired sobre aquest tema](https://www.wired.co.uk/article/securely-wipe-android-iphone-hard-disk).
-   **Has de enviar una contrasenya a algú? Separa-la per la meitat i envia-la per dos canals diferents.** Per exemple, envia la meitat de la contrasenya per correu electrònic i l'altra meitat per trucada de veu.

### 🆘 Informeu-vos sobre la funció SOS d'emergència del vostre telèfon

-   iOS: `Configuració → SOS d'emergència`
-   Android: `Configuració → Seguretat i emergència → SOS d'emergència`

---

_🥳 La seguretat digital té tant a veure amb les coses que fas cada dia com amb la configuració dels teus dispositius i aplicacions. No dubteu a tornar més endavant per revisar aquests hàbits i reflexos; no esperem que ningú se'ls aprengui de memòria a la primera lectura. Ara, la nostra següent secció tracta sobre com millorar la vostra privadesa digital, i és un tema dens perquè, a cada cantonada, hi ha alguna empresa que intenta recollir i vendre les nostres dades al millor postor. Esperem que estigueu a punt per recuperar (una part del) control de les vostres dades!_

---

## 🧗🏿‍♀️ Nivell 3: Millora la teva privadesa digital

### ⚙️ Ajusta amb precisió la configuració de la teva privadesa

#### A les xarxes socials i a les aplicacions de missatgeria
-   **Revisa la configuració de privadesa de les xarxes socials i les aplicacions de missatgeria que fas servir sovint.** Comprova qui pot veure el teu contingut, quina informació teva es fa pública i què comparteixes amb aplicacions de tercers o anunciants.
-   **Sempre que sigui possible, desactiva els rebuts de lectura a les aplicacions de missatgeria.** Al principi pot semblar incòmode, però a la llarga tindràs més privadesa i llibertat quan la gent _no_ sàpiga si has llegit els seus missatges o no.
-   Aquí teniu enllaços i instruccions per a les plataformes/aplicacions més utilitzades:
    -   **Plataformes/aplicacions amb configuració de privadesa disponible a través d'un navegador d'escriptori:**
        -   Facebook: [Revisió de la privadesa](https://www.facebook.com/privacy/checkup/)
        -   Google: [Revisió de la privadesa](https://myaccount.google.com/intro/privacycheckup)
        -   YouTube: [Confidencialitat de la compte](https://www.youtube.com/account_privacy)
        -   X/Twitter: [Privadesa i seguretat](https://twitter.com/settings/privacy_and_safety)
        -   Reddit: [Seguretat i privadesa](https://www.reddit.com/settings/privacy)
        -   Bluesky: [Privadesa i seguretat](https://bsky.app/settings/privacy-and-security)
    -   **Plataformes/aplicacions amb configuració de privadesa només disponible completament a través de la seva aplicació mòbil:**
        -   Instagram: `Configuració → Privadesa`
        -   WhatsApp: `Configuració → Compte → Privadesa
        -   Snapchat: `Configuració → Controls de privadesa`
        -   TikTok: `Perfil → Configuració i privadesa → privadesa`
        -   Telegram: `Configuració → Privadesa i seguretat`
        -   Signal: `Configuració → Privadesa`
-   **Limita com Facebook et fa un seguiment en altres llocs web** eliminant i desconnectant [l'activitat fora de Facebook](https://www.facebook.com/off_facebook_activity).

#### En comptes de correu electrònic i de xarxes socials
-   **Revisa `les aplicacions de tercers` o `les aplicacions connectades` vinculades a les principals plataformes de xarxes socials/correu electrònic.** Aquestes aplicacions de tercers/connectades tenen accés a les teves dades i podrien estar-les venent. Instruccions per a:
    -   [Google](https://support.google.com/accounts/answer/3466521?hl=en)
    -   [Facebook](https://www.facebook.com/help/211829542181913)
    -   [Instagram](https://www.facebook.com/help/instagram/1144624522593085)
    -   [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps)

#### Als comptes de correu electrònic
-   **Evita que les imatges es carreguin automàticament als teus correus electrònics**, perquè les empreses les utilitzen com una manera de fer-te un seguiment.
    -   Gmail: A l'ordinador, feu clic a Configuració `⚙️ → Totes les configuracions → General: Imatges: Demanar abans de mostrar imatges externes`. Per als remitent de correus electrònics de confiança, sempre podeu fer clic `a Sempre mostra imatges d'un` correu electrònic seu. Per revertir aquesta decisió, heu de fer clic al petit triangle orientat cap avall `que hi ha` al costat `de "de"` a la part superior del correu electrònic.
    -   Proton Mail: No cal, ja que tenen una funció que carrega les imatges als seus propis servidors abans d'enviar-t'les. [Més informació aquí](https://proton.me/support/protonmail-images).
    -   Tuta Mail: La càrrega d'imatges està desactivada per defecte, però podeu activar la càrrega automàtica d'un remitent a la vegada. Al missatge de descàrrec de responsabilitat `de càrrega automàtica d'imatges` que apareix a sota de la informació del remitent, feu clic `a Sempre confiar en el remitent` (al mòbil, primer feu clic `a Més`). Per revertir aquesta decisió, feu clic/toc a les tres punxes a la cantonada superior dreta i després feu clic/toc `a Bloqueja el contingut extern`.
#### Al teu telèfon
-   **Revisa quines aplicacions del teu telèfon intel·ligent tenen accés a les teves dades de localització.** Desactiva l'accés per a les aplicacions que no el necessiten i minimitza el nombre d'aplicacions que rastregen la teva ubicació.
    -   iOS: `Configuració → Privadesa i seguretat → Serveis de localització`
    -   Android: `Configuració → Ubicació → Permisos de ubicació de les aplicacions`
-   **Desactiva el teu identificador publicitari únic** perquè els anunciants no et puguin localitzar tan fàcilment:
    -   iOS: `Configuració → Privadesa i seguretat → Rastreig → Permetre que les aplicacions sol·licitin fer un seguiment: Desactivat`
    -   iOS: `Configuració → Privadesa i seguretat → Publicitat d'Apple → Anuncis personalitzats: Desactivat`
    -   Android: `Configuració → Seguretat i privadesa → Privadesa → Anuncis → Esborra l'identificador d'anuncis`
-   A iOS, desactiva la configuració que permet a les aplicacions fer un seguiment de la teva activitat en altres aplicacions i llocs web:
    -   `Configuració → Privadesa i seguretat → Rastrejament → Permetre que les aplicacions sol·licitin rastrejar: Desactivat`
-   **A Android, desactiva l'escaneig passiu de Wi-Fi i Bluetooth.**
    -   `Configuració → Ubicació → Serveis de ubicació → Escaneig de Wi-Fi`
    -   `Configuració → Ubicació → Serveis de ubicació → Escaneig de Bluetooth`
-   **Elimina qualsevol aplicació que no reconeguis o que no hagis utilitzat des de fa molt de temps.** Sempre les pots tornar a descarregar si cal, tot i que hi ha algunes aplicacions que vénen amb el sistema operatiu i que no es poden eliminar.
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

-   **Si us preocupa la privadesa, no utilitzeu Amazon Echo (altaveus) ni Ring (sistema de seguretat domèstic).** Tots dos tenen un historial de violacions de la privadesa. Si ja en teniu, aquí teniu algunes mesures de mitigació:
    -   Amazon Echo: Desactiva les comandes de veu prement el botó físic que sembla un cercle amb una línia travessada. Altrament, tot el que diguis s'enviarà als seus sistemes en el núvol per a l'anàlisi.
    -   Amazon Echo i Ring: Desactiva la funció "Amazon Sidewalk" que comparteix la teva connexió a Internet amb desconeguts seguint [aquestes instruccions](https://allaboutcookies.org/opt-out-amazon-sidewalk).
-   **Considereu desactivar els comandaments per veu als vostres altaveus intel·ligents.** Els comandaments per veu poden ser una comoditat, però només funcionen perquè s'envien fragments d'àudio als servidors del fabricant del dispositiu per processar el que heu dit.
-   **Si les ordres de veu són importants per a tu, aquí tens algunes maneres de tenir certa privadesa amb elles:**
    -   **Google Nest:** aneu a [Controls d'activitat](https://myaccount.google.com/activitycontrols/audio) de Google Home i desmarqueu `Inclou enregistraments d'àudio`.
    -   **Apple HomePod:** al telèfon vinculat a l'altaveu, aneu a: `aplicació Home → [icona de l'HomePod] → Configuració de l'accessori → Anàlisi i millora` i desactiveu totes les opcions.
    -   **Sonos:** Consulteu [les suggerències de la Fundació Mozilla](https://www.mozillafoundation.org/en/privacynotincluded/sonos-smart-speakers/).
-   **Per a les televisors intel·ligents, assegura't desactivar la funcionalitat de seguiment de dades del fabricant,** també coneguda com a reconeixement automàtic de contingut (ACR).
    -   Instruccions de: [Consumer Reports](https://www.consumerreports.org/privacy/how-to-turn-off-smart-tv-snooping-features-a4840102036/)

### 🕸️ Actualitza el navegador web del teu telèfon i del teu ordinador

-   **Canvia el navegador si fas servir Chrome o Edge,** tots dos tenen un historial pèssim pel que fa a la protecció de la teva privadesa.
    -   Per a iOS: utilitzeu Safari.
    -   Per a macOS: instal·la [el Firefox](https://www.firefox.com) o fes servir el Safari.
    -   Per a Android/Windows: instal·la [el Firefox](https://www.firefox.com).
-   **Revisa la configuració de privadesa del teu navegador web**
    -   Al teu mòbil:
        -   Safari d'iOS: `[iOS] Configuració → Aplicacions → Safari → Privadesa i seguretat`. Assegura't que els opcions `«Evita el seguiment entre llocs` », `«Amaga l'adreça IP»` i `«Advertiment de llocs web fraudulents»` estiguin activades.
        -   Firefox per a Android: `[Firefox] Configuració → Privadesa i seguretat`, activa `el mode només HTTPS` i `la protecció reforçada contra el seguiment`.
    -   Al teu ordinador:
        -   Safari de macOS: `Preferències → Privadesa`, marqueu les caselles de `Seguiment de llocs web` i `Amaga l'adreça IP`
        -   Firefox per a macOS/Windows: `Preferències → Privadesa i seguretat`, activa `la Protecció de seguiment millorada` (qualsevol opció), `No em segueixis` i `el Mode només HTTPS` (desplaça't fins a la part inferior).
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
-   **En lloc d'obrir una `finestra privada/incògnita nova` al vostre navegador habitual, feu servir un navegador separat amb més privadesa** quan vulgueu un seguiment mínim. És possible que aquests navegadors no funcionin tan bé per a l'ús diari, però és perquè tenen proteccions addicionals. A més, quan hi ha dues aplicacions separades, és menys probable que barregeu les finestres privades i les no privades.
    -   Per a macOS, Windows i GNU/Linux: [Mullvad Browser](https://mullvad.net/en/browser)
    -   Per a iOS i Android: [Firefox Focus](https://www.firefox.com/browsers/mobile/focus/)

### 📊 Revisa quines dades tenen sobre tu aquestes grans plataformes tecnològiques

Suprimeix tot allò que no necessitis, si hi ha opcions per fer-ho:
-   **Google:** [La meva activitat](https://myactivity.google.com)
-   **Facebook:** [La teva informació de Facebook](https://www.facebook.com/settings?tab=your_facebook_information)
-   **Amazon:** [Configuració de privadesa d'Alexa](https://www.amazon.com/b/?node=19149164011)
-   **Microsoft:** [Privadesa del compte](https://account.microsoft.com/privacy)

### 💪🏽 Revisió d'hàbits i reflexos (edició de privadesa digital)

#### La regla d'or
**Publica menys informació personal en línia.** Això inclou informació que es pot utilitzar per identificar-te, rastrejar-te o estafar-te (adreces, números de telèfon, data de naixement, etc.), així com fotos de casa teva i del teu veïnat.

#### Compte amb el que dius als grups en línia
**No diguis res del que et puguis penedir en un grup «privat»** a Slack, Discord, Facebook, xat de grup de WhatsApp, canal de Telegram o qualsevol fòrum en línia «privat». Vet aquí per què:
1.  **Qualsevol persona del grup pot filtrar les dades.**
2.  **Els administradors solen tenir accés a tot el que hi ha dins del grup,** incloses les missatges eliminades i les missatges directes privades entre dues persones.
3.  **El que dius es pot rastrejar fins al número de telèfon o l'adreça de correu electrònic del teu compte.** Fins i tot si no fas servir el teu nom o la teva foto reals.
    -   Per evitar-ho a Telegram, aneu a `Configuració → Privadesa i seguretat → Número de telèfon` i, a continuació, configureu:
        -   `Qui pot veure el meu número de telèfon` a `Ningú`.
        -   `Qui em pot trobar pel meu número` a `Els meus contactes`.

#### Sàpiga quan el seu nom apareix públicament com a simpatitzant o donant
**Comprova sempre si el teu nom apareix públicament en línia per subscripcions, micromecenatges, peticions i donacions.** Això és especialment rellevant si tens un nom únic.

Algunes plataformes que faciliten aquestes coses sovint tenen configuracions de privadesa, així que el millor és crear-hi un compte per tenir un cert control sobre el que es mostra públicament. Alguns exemples de configuracions de privadesa importants però sovint passades per alt:
-   **Patreon:** `Configuració → Comptes → Privadesa`: Desactiva tant `el Perfil públic complet` com `el Perfil de comunitat`.
-   **Indiegogo:** Al menú, ves a `Les meves campanyes`. Si vols amagar un projecte del teu perfil públic:
    -   A sota `Campanyes que he finançat`, selecciona `Accions: Amaga la contribució`.
    -   Aleshores la pàgina es refresca, però el projecte simplement s'ha desplaçat a `Campanyes que segueixo`. Allà, seleccioneu `Accions: Deixa de seguir`.Patreon: Configuració → Comptes → Privadesa: Desactiva tant el Perfil públic complet com el Perfil
-   **GoFundMe:** Al menú, aneu a `El vostre impacte`. A continuació, aneu a qualsevol campanya que hàgiu donat suport. Allà, a sota `Les vostres donacions`, podeu canviar si el vostre nom apareix públicament.

#### Altres recomanacions
-   **Crea un compte separat amb un pseudònim per deixar ressenyes de negocis locals** (a Google Maps, Yelp, etc.) si n'escrius moltes. Altrament, les ressenyes es mostraran amb el teu nom real i podrien revelar la teva ubicació.
-   **Si teniu un domini web, assegureu-vos que la privadesa WHOIS/de domini estigui activada.** Molts registradors de dominis i proveïdors d'allotjament web ofereixen aquesta funció gratuïtament i la tenen activada per defecte.

---

_👍👍👍 Uf! Dona't un cop a l'esquena, perquè navegar per tot això no ha estat gens fàcil. Però esperem que ara sentis que tens molt més control de les dades que envies al món. Les nostres recomanacions no són de cap manera exhaustives, però haurien de proporcionar-vos un nivell de privadesa raonable sense haver de sacrificar la comoditat i la diversió de la tecnologia. De nou, us recomanem que feu un bon descans abans de passar a la següent secció, on presentem els nostres consells i eines preferits per ser més segurs i privats en línia._

---

## 🤾🏻‍♀️ Nivell 4: Consells i eines per fer més coses

### 🔐 Afegeix un pany addicional als fitxers sensibles

-   **Identifica els fitxers als quals no vols que altres hi accedeixin.** Això pot incloure fotos privades, escanejats del passaport i documents financers.
-   **Per als fitxers del vostre ordinador, creeu una caixa forta xifrada (volta) i protegida per contrasenya per als vostres fitxers:**
    -   Eina recomanada: [Cryptomator](https://cryptomator.org/).
    -   Està bé tant emmagatzemar la vostre caixa forta al núvol o al vostre ordinador. Decidiu segons com vulgueu fer còpies de seguretat de la caixa forta.
    -   Mou els teus fitxers a aquesta caixa forta segura. Assegura't d'esborrar les còpies originals un cop hagin estat traslladades a la caixa forta.
-   **Per als documents del telèfon, hi ha diverses opcions:**
    -   Crea un caixa forta similar amb una aplicació com [Cryptomator](https://cryptomator.org/)(💰 per a mòbils).
    -   Si tens un pla de pagament per a un gestor de contrasenyes, les aplicacions també et permeten desar fitxers en una secció anomenada `documents` o `adjunts`. 💰
    -   L'aplicació Files d'iOS té una funció `de bloqueig de PDF` per a fitxers individuals.
    -   Android Files de Google et permet crear una `carpeta segura` [seguint aquestes instruccions](https://support.google.com/files/answer/9935264).
-   **Per a les fotos i vídeos del telèfon, utilitzeu les funcions de les aplicacions de fotos predeterminades:**
    -   Fotos d'iOS: obriu la foto i toqueu el botó `…` a la part superior dreta. Toqueu `Amaga`. Això posarà la foto en una carpeta `Amagada` a l'aplicació Fotos (a sota `d'Utilitats`) que només es pot desblocar amb FaceID o un codi d'accés.
    -   Android Google Photos: [Segueix aquestes instruccions](https://support.google.com/photos/answer/10694388?co=GENIE.Platform%3DAndroid&oco=1) i llegeix amb atenció la secció sobre còpies de seguretat automàtiques.
    -   Galeria d'Android: L'aplicació de galeria bàsica no admet fotos ocultes, així que descarregueu una aplicació de galeria alternativa com [Fossify Gallery](https://github.com/FossifyOrg/Gallery) i activeu la protecció amb contrasenya per als elements ocults a la configuració.

### 💰 Millora el teu equipament

-   **Compra una pantalla de privadesa per al teu portàtil i telèfon.** Aquestes làmines adhesives eviten que els curiosos vegin el que hi ha a la pantalla. Exemples per a:
    -   Portàtils: [Filtres de privadesa 3M](https://www.3m.com/3M/en_US/p/c/office-supplies/workstation-accessories/screen-filters-protectors/laptop-filters/)
    -   iPhone: [Spigen EZ FIT GLAS.tR Privacy](https://www.spigen.com/collections/iphone-13-pro/products/iphone-13-pro-screen-protector-ez-fit-glas-tr-privacy)
-   **Col·loca un adhesiu (o una coberta per a la webcam) sobre la càmera frontal del teu portàtil.**
    -   Si compres una tapa per a la càmera web d'un portàtil, assegura't que tingui menys de 0,1 mm de gruix perquè no afecti el tancament del portàtil.
-   **No utilitzis els dispositius que et proporciona la teva empresa per a assumptes personals.** Tingues dispositius separats per a la teva vida laboral i personal o, si és massa complicat tenir-ne diversos, utilitza el teu dispositiu personal per a tot. Els dispositius configurats pels llocs de treball sovint tenen sistemes de monitorització que es poden fer servir malament durant les disputes.
-   **Compra un telèfon mòbil que sempre rebi les últimes actualitzacions de programari** i, en el cas d'Android, que no instal·li aplicacions ni complements de sistema innecessaris.
    -   **Primera opció: Fairphone.** Aquests dispositius destaquen pel seu compromís de suport a molt llarg termini (fins a 8-10 anys d'actualitzacions de seguretat segons el model) i utilitzen un Android net sense aplicacions innecessàries. A més, estan dissenyats perquè **l'usuari els pugui reparar fàcilment** a casa (pots comprar peces de recanvi oficials com pantalles o bateries a la seva [botiga de recanvis](https://www.google.com/search?q=https://shop.fairphone.com/es/spare-parts)) i permeten instal·lar sistemes operatius alternatius centrats en la privadesa.
    -    Segona opció: Apple iPhone. Apple té un historial de donar suport als dispositius durant molt de temps.
    -   Tercera opció: Google Pixel. Els telèfons Pixel reben les actualitzacions d'Android directament de Google i venen amb una instal·lació d'Android més o menys «pura».
    -   Per a altres telèfons Android:
        -   Investiga per trobar un telèfon que a) no afegeixi massa programari innecessari a la seva instal·lació d'Android, b) apliqui ràpidament els pegats de seguretat que publica el projecte Android de Google i c) garanteixi actualitzacions de programari per al seu maquinari durant molt de temps.
        -   Evita els telèfons Android més barats de grans empreses com Samsung, Xiaomi o OPPO: tenen un historial d'afegir aplicacions innecessàries i intrusius. Per exemple, [la plataforma d'aplicacions](https://www.techfinitive.com/explainers/what-is-app-cloud-delete/) de Samsung [que instal·la aplicacions sense permís i recull dades sobre tu sense consentiment](https://www.techfinitive.com/explainers/what-is-app-cloud-delete/).
-   **Utilitza un servei de VPN de pagament** tant quan sigueu en una xarxa pública (p. ex., un cafè) com quan siguis a casa (per reduir les dades que compartiu amb la vostra companyia de telefonia/internet).
    -   Evita els serveis de VPN gratuïts perquè sovint recuperen la inversió venent les teves dades.
    -   VPN recomanades: [Mullvad](https://mullvad.net), [IVPN💰](https://www.ivpn.net/)
    -   _Tingues en compte que, tot i que el  iCloud Private Relay és similar a una VPN, només s'aplica al trànsit a través del navegador web Safari._

### 🔡 Utilitza aplicacions amb xifrat de principi a fi

#### Per a missatgeria i trucades segures

-   **Utilitza aplicacions amb protocols de xifratge de principi a fi de codi obert i temporitzadors de missatges efímers fàcils d'utilitzar.**
    -   Aplicacions recomanades:
        -   [Signal](https://signal.org/): Registra't amb un número de telèfon.
        -   [Wire](https://wire.com/): Registra't amb una adreça de correu electrònic.
    -   Configura els missatges perquè desapareguin. Tria un interval que et sigui còmode.
        -   **Signal:** Ves a `Configuració → Privadesa → Missatges que desapareixen → Temporitzador per defecte per a xats nous`.
        -   **Wire:** No hi ha cap configuració a nivell d'aplicació. L'has de configurar per a cada conversa tocant/fent clic a la icona del temporitzador ⏱.
    -   Aquestes aplicacions també xifren les trucades de vídeo i veu de punta a punta, així que continueu utilitzant-les sempre que sigui possible.
-   **El xifratge de principi a fi per a trucades de vídeo/veu amb més de 5 persones potser no val la pena.** Hi ha diverses raons:
    -   És difícil mantenir la privadesa en trucades de grup grans, ja que sovint es converteixen en esdeveniments quasi públics a causa del gran nombre de participants.
    -   El suport per a trucades de vídeo/veu xifrades de principi a fi per a grups més grans és limitat, i la majoria de plataformes encara recullen les metadades de la vostra trucada fins i tot quan el xifratge de principi a fi està activat.

#### Per a compartir fitxers en línia i fer còpies de seguretat

-   **Desa i comparteix fitxers al núvol utilitzant el xifrat de principi a fi.**
    -   Aplicacions recomanades: [Tresorit](https://tresorit.com/), [Proton Drive](https://proton.me/drive) 💰
    -   Per a iCloud: activa la Protecció de dades avançada. [Consulta les instruccions d'Apple](https://support.apple.com/en-us/HT212520).
    -   _Recorda: els fitxers emmagatzemats a Dropbox i Google Drive no estan xifrats de principi a fi._
-   **Fes còpia de seguretat dels teus fitxers en línia amb una plataforma amb xifratge de principi a fi.**
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

#### Utilitzeu les funcions de seguretat i privadesa específiques de l'aplicació

##### Signal []

-   **Configura un nom d'usuari** perquè la gent et trobi amb aquest nom en lloc del teu número de telèfon. Per crear un nom d'usuari:
    -   `Configuració →` \[Toca la icona del teu perfil o el teu nom\] `→ @ Nom d'usuari`
-   **Amaga el teu número de telèfon.**
    -   Ves a `Configuració → Privadesa → Número de telèfon` i estableix ambdós a `Ningú`.
-   **Activa la capa addicional de protecció amb codi PIN** i evita que altres iniciïn la sessió amb el teu número de telèfon.
    -   `Configuració → Compte → Bloqueig de registre: Activat`
    -   `Configuració → Compte → Bloqueig de registre: Activat`
-   **Amaga els teus missatges del canviador d'aplicacions del telèfon** (perquè els teus missatges no es mostrin accidentalment a altres aplicacions) activant `la seguretat de la pantalla`:
    
    -   `Configuració → Privadesa → Amaga la pantalla a Canviador d'aplicacions` [ALERT This is not valid]
-   **Amaga els teus missatges de la funció Recall de Microsoft Windows.**
    
    -   L'aplicació de sobretaula de Signal les amaga per defecte, però comprova-ho doblement anant a `Configuració → Privadesa → Seguretat de la pantalla`.
-   **Evita que els missatges apareguin a les finestres de notificació.**
    
    -   `Configuració → Notificacions → Contingut de les notificacions: Mostra → Sense nom ni contingut`

##### Telegram

-   **Activa la verificació de dos passos** per evitar que algú mogui el teu compte sense el teu permís.
    -   `Configuració → Privadesa i seguretat → Verificació en dos passos`
-   **Amaga el teu número de telèfon:**
    -   `Configuració → Privadesa i seguretat → Número de telèfon`, i després estableix `Qui pot veure el meu número de telèfon` a `Ningú`.
-   **Comença les converses amb `Inicia un xat secret` perquè estiguin xifrades de principi a fi.** Totes les altres converses i grups no**ho** estan. _Malauradament, això significa que els teus missatges no apareixeran a l'aplicació d'escriptori o web._ Aquesta opció està disponible fent clic al menú dels tres punt del perfil de la persona amb qui vols mantenir la conversa.

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

### 🙃 Assegureu la resta dels vostres comptes

Has creat contrasenyes úniques per als comptes importants al `Nivell 2`, però hauries de planificar un dia per ocupar-te de la resta dels teus comptes en línia. No és una tasca urgent, per això l'hem posat tan avall a la llista, però requerirà força temps i esforç. Pots fer-ho ara o marcar-ho com a tasca pendent per més endavant.

-   **Fes una llista de tots els comptes actius i dels comptes que continguin la teva informació privada.** No et preocupis per trobar tots els comptes, sempre els podràs gestionar més endavant.
-   **Si ja no utilitzes un compte, considera iniciar-hi la sessió per desactivar-lo o suprimir-lo.** Potser alguns comptes tenen un valor sentimental, però la majoria no.
-   **Per als comptes que vulgueu conservar, assegureu-vos que cadascun utilitzi una contrasenya única i difícil d'endevinar.** Reviseu les nostres recomanacions `de nivell 2` sobre com crear bones contrasenyes si cal.
    -   Si utilitzeu un gestor de contrasenyes, ara és el moment de transferir-hi tot:
        -   La manera més ràpida d'introduir les dades és iniciar la sessió i desconnectar-te de cada compte al teu ordinador, i deixar que l'extensió/add-on del navegador del gestor de contrasenyes capturi les dades automàticament.
        -   En alguns casos, el gestor de contrasenyes pot advertir-te que la contrasenya que tens és feble. Si és així, dedica un minut més al lloc web del compte per canviar-la per una nova contrasenya.
        -   Quan hagis acabat, utilitza la funció de monitoratge del teu gestor de contrasenyes per comprovar les contrasenyes emmagatzemades i veure si són massa curtes, si s'han reutilitzat o si ja s'han filtrat com a part d'una filtració de dades. A 1Password, aquesta funció s'anomena `Watchtower`, i a Bitwarden s'anomena `Vault Health Report`.Considera utilitzar un sobrenom o només el teu nom de pila (si el teu nom de pila és comú on vius).

---

_👍👍👍👍 Uau, ho has aconseguit. Has completat els quatre nivells! Has bloquejat totes les coses (grans i petites), has augmentat dràsticament la teva privadesa digital i has aconseguit eines i consells súper segurs. Has fet tot el que creiem que és útil per a tothom. Regala't alguna cosa bonica com a recompensa, sens dubte._

_A partir d'ara, oferim recomanacions per a casos especials (escenaris) i, a continuació, una petita secció de bonificació per a usuaris tècnics. Si cap dels escenaris no s'aplica a tu ara mateix, ja ho tens tot a punt. Recorda que els escenaris seran aquí si mai els necessites!_

---

## 🤹🏻 Escenaris

---

### 👤 Amagar la teva identitat per a cites en línia, esdeveniments o organització

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

_Nota: Si perds o et dones de baixa el número de telèfon secundari, altres persones el poden comprar i suplantar la teva identitat._

#### Obtén un àlies de correu electrònic

Per a llocs i serveis que utilitzen el correu electrònic com a identificador principal/nom d'usuari, crea un compte de correu electrònic nou 🆓 o un àlies de correu electrònic que reenviï al teu compte principal des de:

-   [SimpleLogin::](https://simplelogin.io) Amb seu a Suïssa (com a part del grup Proton Mail/VPN)
-   [addy.io](https://addy.io): Amb seu al Regne Unit i a la UE

#### Comprar coses en línia de manera anònima

-   **Registra't per obtenir una targeta de crèdit virtual centrada en la privadesa 💰** de [Privacy](https://privacy.com/) (només disponible als EUA). Ajuda a) a ocultar la teva identitat al venedor i b) a ocultar al banc què has comprat.
-   **Compra una targeta de crèdit prepagament en una botiga de conveniència local.** Però tingues cura, aquestes targetes no sempre funcionen per a compres en línia, depenent d'on et trobis.
-   **Obtén una targeta de crèdit virtual per a proves gratuïtes** a [Do Not Pay](https://donotpay.com/learn/virtual-credit-cards/) per a aquells casos en què vulguis registrar-te en un període de servei gratuït però no vulguis facilitar la informació real de la teva targeta de crèdit.
-   **Demana que et paguin amb targetes regal**, que es poden utilitzar a les botigues sense rastreig.

#### Crea un àlies en línia no rastrejable

Fins i tot amb tots els serveis de tercers esmentats anteriorment, els tribunals encara poden obligar les empreses a lliurar informació sobre tu. Per tant, si realment et trobes en una situació d'alt risc, potser hauràs de fer tot el que s'ha dit i més. Per a un exemple d'això, consulta [la RECEPTA DE PRIVADESA](https://geminiimatt.medium.com/creating-an-online-persona-deb4cd8c7f46) de Matt Mitchell [: Crear una personalitat en línia](https://geminiimatt.medium.com/creating-an-online-persona-deb4cd8c7f46).

