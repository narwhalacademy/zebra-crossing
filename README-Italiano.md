# TLDR Note per la Sicurezza Online

### 🤔 Per chi e' questa guida?

- Usi internet ogni giorno – per lavoro, social media, banca online, ecc.
- Hai l'impressione che potresti fare di piu' per garantire la tua sicurezza e privacy, ma non sei esposto a nessun pericolo immediato. (Se pensi di esserlo, consulta un esperto che possa analizzare la tua situazione specifica.)
- Sei a tuo agio con la technologia, anche se non ti consideri un utente avanzato. Per esempio, sai come accedere alle impostazioni del tuo computer/telefonino.

### 🌱 Come usare questa guida

- Le varie raccomandazioni sono ordinate per livello crescente di difficolta'. Inizia dal livello 1, prima di procedere con i livelli successivi!
- *Raccomando di applicare tutte le raccomandazioni dei livelli 1, 2 e 3.* Non serve essere un esperto... io l'ho fatto, e la mia competenza tecnica e' nella media.
- Dopodiche', leggi gli scenari e vedi se ti ritrovi in una o piu' delle situazioni descritte. (Il presupposto e' che tu applicato tutte le raccomandazioni dei livelli da 1 a 3.)
- Apprezziamo suggerimenti e contributi - usa le funzioni 'pull request' o 'fork' di github per suggerire modifiche, ecc. 

### 🗣 Questa guida in altre lingue

- [Inglese](README.md)
- [繁體中文 (Traditional Chinese)](README-繁體中文.md)

### 🕒 Data di ultima modifica

- 9 Febbraio 2020

---

## 🧐 Teoria & pratica

### 🎯 Threat modeling

Per capire che misure di protezione adottare, devi prima capire a che rischi sei esposto:

- A quali rischi sei esposto? per esempio: spionaggio industriale, sorveglianza da parte di polizia/servizi di sicurezza, molestie online/doxxing.
- Che tipo di informazioni vuoi proteggere? E.g. documenti confidenziali, foto personali.
- Siamo tutti a rischio quando usiamo strumenti digitali (altrimenti non ci sarebbe bisogno di password sui nostri pc o telefonini) ma e' importante capire esattamente quali sono i rischi e le possibili conseguenze, cosi da adottare una risposta commisurata al rischio (non sottovalutare il rischio, ma nemmeno sopravvalutarlo) 
- Per ulteriori informazioni, leggi [come creare il tuo piano di difesa online](https://ssd.eff.org/en/module/introduction-threat-modeling) sul sito della  Electronic Frontier Foundation (in Inglese).

### 🔗 L'anello debole

- Ricorda che una catena è forte solo quanto il suo anello più debole! Per esempio, se hai scelto l'opzione di reimpostare la password via email, un hacker che riesca ad avere accesso alla tua email, avra' accesso anche al resto dei tuoi servizi online.

### 🔡 Livelli di crittografia

1. Dati non criptati: Chunque intercetti le tue comunicazioni, puo' leggerle.
2. Livello di criptazione normale: I tuoi dati sono crittografati, chiunque intercetti le tue comunicazioni, non puo' leggerle. Ma la piattaforma usata per comunicare (per esempio Google or Facebook) puo' accedere ai tuoi dati in chiaro, e potrebbe consegnarli alle autorita' in caso venga chiesto loro di farlo, per esempio da un ordine del tribunale.
3. Crittografia end-to-end: le comunicazioni possono essere lette solo dal mittente e dal destinatario. Questo significa che nemmeno la piattaforma usata per comunicare ha accesso al contenuto della comunicazione. Quindi anche in caso di un ordine del tribunale, la piattaforma puo' solo fornire il contenuto crittografato delle comunicazioni, non in chiaro.

### 🧩 Metadati

- I metadati sono dati che descrivono le tue comunicazioni – per esempio che numero hai chiamato, e la durata della telefonata (ma non il contenuto della telefonata stessa). I metadati sono importanti perche' permettono di costruire un profilo abbastanza accurato della tua identita', i tuoi contatti, i tuoi spostamenti... In generale, le varie leggi a protezione della privacy forniscono una minore protezione per i metadati.

---

## 💦 Livello 1

### ✅ Cose da fare immediatamente

#### Email

- Se usi un servizio di posta elettronica via web, assicurati di usare un URl che inizia per `https://`. Se il tuo fornitore non ha questa opzione, cambia fornitore.
- Abilita l'autenticazione a due fattori (two-factor authentication) per la tua casella di posta elettronica (e.g. istruzioni per [Gmail](https://support.google.com/accounts/answer/185839?hl=it), [Protonmail](https://protonmail.com/support/knowledge-base/two-factor-authentication/) - in Inglese) **se** il tuo fornitore supporta antenticazione via app (codici via SMS non sono piu' considerati sicuri al giorno d'oggi) (e.g. [Authy](https://authy.com/), [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=it)).
- Dopo aver abilitato l'autenticazione a due fattori, controlla se il tuo servizio di posta elettronica supporta codici di ripristino (un codice da usare in caso tu perda il tuo telefono). [Istruzioni per Gmail](https://support.google.com/accounts/answer/1187538?hl=it).

#### Passwords

- Scegli password 'lunghe' (=non meno di dieci caratteri); un'ottima tecnica per creare password sicure e' concatenare-parole-a-caso-per-formare-lunghe-frasi-senza-senso.
- Rivedi le 'domande di sicurezza' per i tuo servizi online (email, banca online, Facebook, ecc.) e scegline una che non sia facile da rispondere e.g. che nemmeno i tuoi amici conoscano, che non si possa trovare online googlando il tuo nome/sul tuo account facebook.
- Usa una password diversa per ciascun sito web/servizio online, perche' incidenti di sicurezza succedono ogni giorno, e non si sa mai qual'e il prossimo sito ad essere compromesso. Usa un password manager ([qui i piu' comuni](https://lifehacker.com/5529133/five-best-password-managers)) per memorizzare/usare/creare password sicure. Se non vuoi installare un password manager adesso, almeno cambia _subito_ le password dei tuoi servizi essenziali (email, social media,banca online, cloud storage) e usa una password unica per ciascun sito.
- Usa un codice di sblocco per il tuo smartphone che non sia ovvio (e.g. no 0000, 1111, ecc...).
- Se usi un iPhone, disattiva Accessori USB in Impostazioni > Face ID & Passcode > Allow Access When Locked.
- Se usi un Android, [disabilita Smart Lock](https://support.google.com/android/answer/9075927?hl=it)

#### Abilita Crittografia per i tuoi dispositivi

- verifica che la memoria del telegono sia crittografata: [Android](http://www.networkworld.com/article/2689371/opensource-subnet/how-to-encrypt-an-android-device-in-5-steps.html) (in Inglese), [iOS](https://ssd.eff.org/en/module/how-encrypt-your-iphone) (in Inglese) (questa e' l'impostazione di default in molti telefoni nuovi, ma val la pena controllare).
- fai lo stesso per il disco del tuo pc (portatile o fisso): [Windows](https://uit.stanford.edu/service/encryption/wholedisk/bitlocker) (in Inglese), [Windows se non hai BitLocker](https://veracrypt.codeplex.com/) (in Inglese), [Mac OSX](https://support.apple.com/it-it/HT204837).
- Crittografa anche le copie di backup! Abilita crittografia per il disco esterno (e.g. USB) che usi per le copie di sicurezza, e se usi il cloud, controlla che il tuo provider supporti crittografia end-to-end.
- N.B. Ricorda che la crittografia protegge i tuoi dati solo quando il computer e' spento!

#### Altro

- Configura il codice PIN per la carta SIM del tuo telefonino: [iPhone](https://support.apple.com/it-it/HT201529), [Android](https://www.digitalcitizen.life/how-change-or-remove-sim-pin-android-2-steps) (in Inglese). Cerca nel sito del tuo operatore mobile per indicazioni sulla password di default (e' diversa da operatore a operatore).
- Disabilita app che non usano l'autenticazione a due fattori (e.g. [instructions for Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889) - in Inglese).
- Disabilita l'opzione di aggiungere inviti automaticamente al tuo calendario su [Impostazioni di Google Calendar](https://calendar.google.com/calendar/r/settings) ([perche'? leggi qui](https://www.forbes.com/sites/daveywinder/2019/06/11/new-security-warning-issued-for-googles-1-5-billion-gmail-and-calendar-users/#3605ff0565e5)).
- [Abilita Avvisi di login su Facebook](https://www.facebook.com/settings?tab=security).
- [Disabilita macro in Microsoft Office](https://support.office.com/en-us/article/enable-or-disable-macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6).

### 💪🏽 Buone abitudini da coltivare

#### Email

- Stai allerta e assicurati che ogni email che ricevi non sia una _phishing_ email: quando possibile, controlla l'indirizzo del mittente, e tutti i nomi di dominio dei link (senza cliccarli pero'! :) ).
- Non aprire gli allegati senza essere _certi_ della provenienza. Quando possibile, visualizza anteprima usando un servizio online, o chiedi di spedirli usando un server di condivisione o un servizio online (Dropbox, Google Drive, SpiderOak, Tresorit), che sono tipicamente piu' sicuri.
- Se non sei sicuro della provenienza di un allegato, puoi mandarlo (senza aprirlo!) a [VirusTotal](http://www.virustotal.com) per un controllo (NOTA: i file mandati a VirusTotal sono messi a disposizione di ricercatori nel campo della sicurezza IT, dunque non mandare documenti personali e/o confidenziali).

#### Installa gli aggiornamenti!

- Quando ricevi una notifica (genuina!) che chiede di aggiornare il sistema operativo (sul pc o smartphone), fallo immediatamente.
- Lo stesso per apps (telefonino + computer).
- Controlla di tanto in tanto sul sito del produttore, se ci sono aggiornamenti del firmware per router (e altri dispositivi connessi a internet e.g. IPcam, smart TV, ecc).

#### Altro

- Cambia le tue password importanti (e.g. email, computer login, password manager master) ogni uno-due anni.
- Resetta i tuoi dispositivi alle impostazioni di fabbrica prima di rivenderli/donarli: [smartphone](http://lifehacker.com/5808280/what-should-i-do-with-my-phone-before-i-sell-it) (in Inglese), [computer](http://lifehacker.com/5835369/how-do-i-securely-wipe-a-computer-before-donating-it-to-charity) (in Inglese).
- Evita di ricaricare il tuo telefonino ai punti di ricarica e.g. nei centri comemrciali – potrebbero essere configurati per copiare i tuoi dati. Ricarica invece la tua batteria portatile.

---

**👍 Ottimo lavoro! Hai preso le precauzioni di base.  
👍 Vuoi dare un'occhiata al livello piu' avanzato?**  

---

## 💦💦 Livello 2

### ✅ Cose da fare immediatamente

#### Ottimizza la tua privacy

- Review the privacy settings on social networks you frequent: who can see your content, who can comment on it, and who can see your location.
- Install these protective web browsers add-ons (and make sure they're on even during private/incognito mode):
  - An ad blocker (e.g. [uBlock Origin](https://github.com/gorhill/uBlock/), [Ghostery](https://www.ghostery.com/)).
  - A tracker blocker ([Privacy Badger](https://www.eff.org/privacybadger)).
  - [HTTPS Everywhere](https://www.eff.org/https-everywhere).
- If you use smart speakers, turn off its recording function: instructions for [Google Home](https://myaccount.google.com/activitycontrols/audio) and for [Amazon Alexa](https://twitter.com/geminiimatt/status/1125611726773334017).

#### Altro

- Set up your devices with third-party applications (e.g. [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/) so you can remotely track, wipe, and encrypt your devices from a website in the future.
- Review what's connected to your main email/social media accounts (e.g. what kinds of services have access to Facebook, and what data can they access and/or can they post on your behalf).
- Review the extensions/add-ons/plug-ins that have been installed within your computer web browser – delete any that you haven't used in a while or don't remember installing.
- Download and run [Stethoscope](https://ragtag.org/stethoscope) for your computer, which make sure your basic security settings (encryption, firewall, screen locks, etc.) are covered.

### 💪🏾 Buone abitudini da coltivare

#### Ottimizza la tua privacy

- Post less personal information online – especially information that can be used to identify/track/scam you (addresses, phone numbers, birthday, etc.). Remember almost everything you say online is logged somewhere and that even if your setup is secure, your recipient's setup may not be.
- Buy a privacy screen (prevents onlookers from seeing your screen, see [this 3M example](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/All-3M-Products/Privacy-Screen-Protectors/Privacy-Products/Black-Privacy/)) for your laptop and/or phone.
- If you own domains, use WHOIS privacy services and stick with it (they're worth the money). But note that with WHOIS lookup/history tools, if you've ever put in your real address, it's very difficult to remove from the logs.

#### Altro

- Use a paid VPN service when on public networks (e.g. cafe wifi) – free VPN services are bad because operators don't have enough incentive to protect you/your data. See recommendations from [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/).
- Check what apps you have installed on your phone once in a while, and delete the ones you're not using anymore.
- If you ever need to send someone a password, split it in half and send via two different channels (e.g. email + voice call).
- Put a sticker (or webcam cover) over your laptop's front-facing camera.
- Don't use Google/Twitter/Facebook to sign up/login to other services – each service should have its own account.

---

**🎉 Congratulazioni! Hai preso ragionevoli precauzioni 
🎉 per la tua sicurezza online :)**

---

## 💦💦💦 Livello 3

### ✅ Da fare

#### Proteggi documenti confidenziali

- Identify files that you don't want others to access (e.g. private photos, passport documents).
- Use [Cryptomator](https://cryptomator.org/) or [Veracrypt](https://www.veracrypt.fr/en/Home.html) to create an encrypted, password-protected vault for them.
- Set them up on both your desktop/laptop and your phone.
- Move your files into these secure vaults. Make sure they're not still hanging around on an old folder or on your phone.

#### Cambia le vecchie password

- Store all of your online service passwords in a password manager. (If you have the right browser add-on/plugin installed, it will capture all the relevant details during a login process.)

- Using your password manager's analysis feature, see which accounts/services have weak passwords and update the ones that might have any personal information about you or that you would really hate to lose.

### 💪🏾 Buone abitudini da coltivare

- Start using [Signal](https://whispersystems.org/), an end-to-end encrypted mobile messaging app that's generally agreed to be safe/secure/robust. (Beyond Signal, there is little consensus on what's secure and people tend to get very emotional about their choice of mobile messaging apps.)
- When making voice or video calls, use an end-to-end encrypted app (e.g. Signal, Jitsi, Wire).
- Buy a harder-to-hack mobile phone ($$$). Typically, this is an iPhone or Android phone that implements a "pure" Google version of Android.

---

**😲 Wow, hai completato anche il livello piu' avanzato.  
😲 Congratulazioni!**

---

## 💦❗️ Raccomandazioni per scenari specifici

### 🛫 Attraversare un confine internazionale

- Turn off your devices because:
  - Storage/hard drives are only encrypted when they're off, **not** when they're just in sleep mode
  - This will also ensure that your mobile devices require a pin when they are turned on, which is protected by freedom of speech laws in some jurisdictions.
- Store less information on your devices – in case they're seized, what you don't have they can't take.
- Be mindful of what stickers you put on your devices – a border agent could mistake them for something suspicious.
- Notify your people about your flight number and arrival time. Have them contact a lawyer/relevant organization if you do not show up.
- For high risk situations (some of these practices might raise suspicions and backfire):
  - Set up alternate photo albums, email addresses and social media accounts full of harmless content.
  - "Forget" half of your password: Password lock your device/account so that only a trusted friend has the second half of the password.
  - Log out of all important accounts (or simply leave your devices at home).
- For more information, see Wired's [Guide to Getting Past Customs With Your Digital Privacy Intact](https://www.wired.com/2017/02/guide-getting-past-customs-digital-privacy-intact/) and [BoingBoing's addendum](http://boingboing.net/2017/02/12/how-to-cross-a-us-or-other-b.html) about filing for attorney privileges at the US border.

---

### 😭 Qualcuno mi ha rubato il telefono/computer portatile!

- Wipe your phone remotely: see instructions for [Android](https://support.google.com/accounts/answer/6160491?hl=en), [iOS](https://support.apple.com/kb/PH2701?locale=en_US).
- Log out of all important accounts from another device.
- If this happened at an international border: Ask for a seizure receipt (available in some jurisdictions, e.g. [Canada](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf))
- Get a new SIM card.
- If you get it back, reset your phone/computer back to its factory settings. Then run some anti-virus and anti-spyware programs just in case.

---

### 👾 Ho il sospetto che il mio computer sia stato hackerato!

- Download an application that will notify you when data is being sent out from your computer. E.g. [Little Snitch for Mac](https://www.obdev.at/products/littlesnitch/index.html).
- Run Activity Monitor on Mac or Process Explorer on Windows to look at what processes/applications are running. Google any suspicious names.
- Login to important online accounts to see if there have been any suspicious logins – see [this Motherboard guide for details](https://motherboard.vice.com/en_us/article/bjeznz/how-do-you-know-when-youve-been-hacked-gmail-facebook).
- Setup a spare smartphone using [Haven](https://guardianproject.github.io/haven/) as a room monitor to detect unwanted intrusions.

---

### 🍆 Sexting & condivisione di immagini non-consensuale

- See [The Motherboard Guide to Sexting Securely](https://motherboard.vice.com/en_us/article/mb3nd4/how-to-sext-securely-safely-what-apps-to-use-sexting).

---

### ✊🏾 Partecipare a una manifestazione

#### In caso di emergenza

- Draft a message to a trusted friend (not at protest) or legal hotline. Be ready to hit send if you are arrested/there is an emergency.
- Bring a spare battery for your phone.
- If you use thumbprint (or facial recognition) unlock, immediately power off your phone if you're ever arrested. In some jurisdictions, [officers can compel you to provide your fingerprint but not your passcode](http://www.theatlantic.com/technology/archive/2016/05/iphone-fingerprint-search-warrant/480861/). Better yet, turn off fingerprint or face ID before going to a protest.
- If you're attending a high-risk protest: leave your phone at home or use burner phone.

#### Salva il meno possibile, condividi il meno possibile

- Keep as little sensitive personal information or incriminating information as possible – you never know whose hands it might end up in.
- Turn on disappearing messages if your messaging app supports it.
- If you need to share photos, erase the associated metadata first using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).
- Turn off location history:
  - iPhone: Settings > Privacy > Location Services > System Services > Significant Locations
  - Android: Settings > Google > Google Account > Data & personalization > Location History > Manage setting > Your account & all your devices > turn off Use Location History
  - Google Maps: Settings > Maps history > Web & App Activity
- Delete past location history:
  - iPhone: Settings > Privacy > Location Services > System Services > Significant Locations > Clear History
  - [Android](https://support.google.com/accounts/answer/3118687?hl=en#delete)
  - [Google Maps](https://support.google.com/maps/answer/3137804?hl=en)

#### Altro

- Double check your messaging apps privacy settings.
- Turn off message previews in your notifications:
  - iOS: Settings > Notifications > Show Previews: When Unlocked
  - Android: Settings > Apps & notifications > Notifications > On lock screen: Hide sensitive content
- Remember to make voice calls through end-to-end encrypted apps like Signal or Whatsapp.
- More info from the EFF about protesting [in the US](https://ssd.eff.org/en/module/attending-protests-united-states) and [internationally](https://ssd.eff.org/en/module/attending-protests-international).

---

### 📰 Sono un giornalista e sto lavorando a un articolo delicato/potenzialmente pericoloso

Below are some basics that all journalists should consider. If you're working on/in a particularly sensitive story/region (e.g. a whisteblower story in the US or China), you and your team should get an tailored training session from an expert.

#### Sii preparato!

- To remotely wipe the contents of your devices using a tracking app (e.g. [Find My](https://www.apple.com/icloud/find-my/) on iOS, [Find My Device](https://support.google.com/accounts/answer/6160491?hl=en) on Android, [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/)).

- To be on the receiving end of an email phishing campaign (as journalist emails are usually more public than others).

#### Proteggi te stesso

- If you're traveling, review the `Crossing an international border` scenario above.

- If you're covering a protest, review the `Attending a protest` scenario above and decide which parts apply to you (if you have special journalist rights/protections where you're working).

- Use a VPN if you're browsing the internet at the office (website administrators can usually see that you're coming from, say, the New York Times network)

#### Proteggi le tue fonti

- Use [Signal](https://www.signal.org/) or [Jitsi](https://jitsi.org/) for end-to-end encrypted voice and video calls.

- Turn on disappearing messages if your messaging app supports it. (Failing that, remember to regularly clear chat logs/histories.)

- Have your organization set up [SecureDrop](https://securedrop.org/). Failing that, encourage people to use [OnionShare](https://onionshare.org/) or [Firefox Send](https://send.firefox.com/).

- Blur faces from photos and videos (e.g. Android [ObscuraCam](https://guardianproject.info/apps/obscuracam/), Youtube [instructions](https://technology.witness.org/2016/02/how-to-use-youtubes-new-blurring-feature-to-protect-identities/)).

- Erase media metadata using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).

- See Ted Han and Quinn Norton's [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/).

- See Martin Shelton's [Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/).

#### Proteggi i tuoi dati

- Make sure you're using an email/storage provider that's not owned/linked to a state or organization that you're reporting on.

- Better yet, move all of your work onto end-to-end encrypted platforms. (E.g. [Protonmail]([https://protonmail.com/](https://protonmail.com/) or [Tutanota](https://tutanota.com/) for email, store documents in a [Tresorit](https://tresorit.com/) or [SpiderOak](https://spideroak.com/) cloud.) Be aware that [courts can compel Google to hand over all of your data](https://medium.com/@tinfoilpress/newsrooms-lets-talk-about-g-suite-1672a36eb235).

- Store sensitive data in a password-protected cloud or external storage device as much as possible. See the `Lock up sensitive files` section above.

- Remember to permanently erase sensitive files from your laptop/desktop: use [Eraser for Windows](https://eraser.heidi.ie/) and [File Shredder for Mac](https://apps.apple.com/us/app/fileshredder/id418094085?mt=12).

#### Ulteriori informazioni

- If you're in an unconventional region, jurisdiction or situation, see Grégoire Pouget of Nothing2Hide's [Digital Security for Journalists Requires an Adaptable Toolkit](https://gijn.org/2019/07/16/digital-security-for-journalists-requires-an-adaptable-toolkit/) guide.

- If you're running a newsroom, see Ontheline Newsrooms' see [Measures for Newsrooms and Journalists to Address Online Harassment](https://newsrooms-ontheline.ipi.media/).

---

### 🕵🏼‍♂️ Molestie online & doxxing

Harassment and doxxing can get very specific and complicated based on the attacker, your position, the overall cultural context, etc. While we have some general suggestions below, we implore you to think about whether your situation has escalated sufficiently and whether it's time to find professional, one-on-one help.

#### Chiedi l'aiuto di un amico fidato

- Do not force yourself into a corner by going at this alone!
  
  - Baseline: Ask a trusted friend to hold space for your situation and be your sounding board on analyzing how bad the threat is.
  
  - Preferred: Ask a trusted friend to help you investigate, record, report and block harassers – see Take Back The Tech's [Hey Friend!](https://www.takebackthetech.net/know-more/heyfriend) guide for more details about this. In some cases, it may be healthier to hand over your phone/social media/accounts over to them so that you're not constantly triggered.

- Alternately, reach out to online communities you're an active member of and ask for help. See PEN America's article on [Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/cyber-safety/deploying-your-supportive-cyber-communities/).

- If no one is available right now, Heartmob has a list of [supportive organizations](https://iheartmob.org/resources/supportive_organizations), some of which have 24/7 hotlines.

#### Monitora i tuoi mention online, tieni un diario 

- Set up a [Talkwalker](https://www.talkwalker.com/alerts) and/or [Google Alerts](https://www.google.com/alerts) for your name/nickname.

- Start logging (date, time, description, screenshot) incidents in whatever program/app that's easiest for you.

#### Cancella le tue informazioni personali da internet

- Pay [PrivacyDuck](https://www.privacyduck.com/) to scrub your information online. If you are an activist you can contact [Equity Labs](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c) for a discounted rate.

- Pay [Reputation.com](https://www.reputation.com/) to remove your information from paid sites and monitor them to make sure it stays removed.

- Alternately, both [PrivacyDuck](https://www.privacyduck.com/resources/) and [Motherboard](https://motherboard.vice.com/en_us/article/ne9b3z/how-to-get-off-data-broker-and-people-search-sites-pipl-spokeo) have free online resources to help you remove your information yourself.

#### Cancella le tue informazioni personali da internet - even more

- Use [Burner](http://www.burnerapp.com/) to set up burner phone numbers for calling/texting.

- Use [Traveling Mailbox](https://travelingmailbox.com/) to obscure your postal address.

- Delete old accounts to eliminate traces of personal information on the Internet. Use [Justdelete.me](http://Justdelete.me) to accelerate this process.

- Review your social media accounts and delete any posts that reveal too much about where you live/where you go/who you're with.

- For Twitter users:
  
  - Ask around in your communities for shared [block lists](https://help.twitter.com/en/using-twitter/advanced-twitter-block-options) of known offenders.
  
  - Use [Semiphemeral](https://micahflee.com/2019/06/semiphemeral-automatically-delete-your-old-tweets-except-for-the-ones-you-want-to-keep/) to delete most of your unwanted posts on Twitter. (Requires use of the command line.)

#### Ignora/segnala/blocca i tuoi molestatori

- Together with your support person/friend and the log of receipts, decide on your course of action (these aren't mutually exclusive):
  
  - Ignore: Sometimes harassers will walk away if they don't get attention.
  
  - De-escalate: In some contexts, you can defuse the situation with some calm words before it gets worse.
  
  - Report: Report the harasser to the relevant online platform and/or your local law enforcement.
  
  - Mute on social media: Allows for peace of mind.
  
  - Block on social media: Maximizes peace of mind as the harasser won't be able to see your posts. But they will notice and see it as a sign of escalation.
  
  - Go public: Can be dangerous, but sometimes shaming them publicly or rallying people to your support will make them go away.

#### Ulteriori informazioni

- See Feminist Frequency's [Speak Up & Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/).

- See TrollBusters' [What to Do? Where to Go? Infographic](https://yoursosteam.wordpress.com/what-to-do-infographic/).

- See Equity Labs' [Anti-Doxing Guide for Activists Facing Attacks from the Alt-Right](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c).

- See HeartMob/Hollaback's [Technical Safety Guide](https://iheartmob.org/resources/tech).

- See Crash Override (RIP)'s [So You've Been Doxed](http://www.crashoverridenetwork.com/soyouvebeendoxed.html) and [Preventing Doxing](http://www.crashoverridenetwork.com/preventingdoxing.html).

---

### 👤 Non voglio usare il mio vero numero di telefono per online dating/networking

For messaging apps that use phone numbers as the primary identifier/username (e.g. Signal, WhatsApp), get a secondary number from:

- [Twilio](https://www.burnerapp.com/) (1 USD/month, but complicated setup – see the Twilio section [here](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46) and [this guide](https://source.opennews.org/articles/shields-using-signal-without-your-phone-number/))

- [Burner](https://www.burnerapp.com/) (5 USD/month, but also has prepaid plans for short-term use)

- [Google Voice](https://voice.google.com/about) (free but only available in the US)

- A phone company: get a prepaid or cheap SIM card plan (rates vary)

But keep in mind:

- If you lose/unsubscribe to your secondary phone number, other people can buy it and impersonate you.

- Most companies will still hand over your information to the authorities if the latter files the right paperwork. 

#### Per completa anonimita' – come creare un profilo online sotto pseudonimo

- If you're a public figure, artist or activist, consider working under a persistent pseudonymn or collective identity – this [Tactical Tech manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online) has more details on why.

- To operate online under a truly safe pseudonymn, follow this guide on [creating untraceable online accounts and protecting your real identity](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46).

---

## 💦❓ Altre raccomandazioni

This section is a catch-all for difficult or esoteric practices that do not fall under any of our scenarios above and might not have any immediate payoff for the casual user.

#### Email

- Sign up for a [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) end-to-end encrypted email account.
- Approach PGP emails at your own risk ([recently disclosed security vulnerabilities](https://www.eff.org/deeplinks/2018/05/not-so-pretty-what-you-need-know-about-e-fail-and-pgp-flaw-0) means that it's no longer bulletproof).

#### Accesso

- Buy a [YubiKey](http://www.amazon.com/Yubico-Y-072-YubiKey-NEO/dp/B00LX8KZZ8/ref=sr_1_1?ie=UTF8&qid=1421839152&sr=8-1&keywords=yubikey+NEO) USB key to use for two-factor authentication.
- Use an alphanumeric passcode to unlock your phone.
- [Generating Diceware passwords](http://world.std.com/~reinhold/diceware.html).

#### File storage & condivisione

- Use an end-to-end encrypted cloud storage service (not Dropbox): [Tresorit](https://tresorit.com/), [SpiderOak](https://spideroak.com/).
- Use encrypted external USB/hard drives from companies like [Apricorn](https://www.apricorn.com/).
- If you want to send a file anonymously, use a special sharing service like [OnionShare](https://onionshare.org/).
- Instead of Google Docs or Microsoft Office, use [CryptPad](https://cryptpad.fr) (open-source, end-to-end encrypted).

#### App di messaggistica

- WhatsApp additional settings:
  
  - To be 100% end-to-end encrypted, turn off chat backups on WhatsApp (Settings > Chats > Chat backup) and delete your previous backups (instructions for [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).
  
  - Turn on security notifications on WhatsApp (Settings > Account > Security).
  
  - Set up a pin number to prevent your account from being moved without your permission (Settings > Account > Two-Step Verification).

- If you're a journalist who uses Signal regularly, step up your safety practices try following Martin Sheldon's [Locking Down Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) guide (or [similarly for WhatsApp](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3) if you use that a lot).

#### Altro

- Keep less information/data/photos on your devices – you can't lose what you don't have!
- Don't use smart TVs or smart speakers.
- Search the web anonymously with [DuckDuckGo](http://duckduckgo.com/).
- If you (or your organization) is really wedded to the Google Suite, consider [Google's Advance Protection program](https://www.wired.com/story/google-advanced-protection/).
- Put your smart cards/passports/phones in a Faraday bag that blocks signals from going in and out. (See [Micah Lee's guide on them](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
- Fortify your self-hosted Wordpress website with [Cloudflare](https://www.cloudflare.com) + [iThemes Security](https://wordpress.org/plugins/better-wp-security/).
- Use a more secure operating system: [Tails](https://ssd.eff.org/en/module/keeping-your-data-safe) (works off of a USB stick) or [Qubes OS](https://www.qubes-os.org/).
- For Android users: Download apps using [F-Droid](https://f-droid.org), an open-source, security-focused app store.
- For US residents: Freeze your credit to prevent hackers from accessing sensitive data. See Security Checklist's [Freeze Your Credit](https://securitycheckli.st/) section for details.

---

**🏆 Oh, sei arrivato fino in fondo!  
🏆 Congratulazioni!**

---

## 🧠 Links

We consulted many sources and drew upon our own experiences in creating this resource. ([See our full list of sources.](SourcesConsulted.md)) If you're not finding quite what you want here, we recommend checking out these other resources: 

- [The Motherboard Guide to Not Getting Hacked](https://motherboard.vice.com/en_us/article/d3devm/motherboard-guide-to-not-getting-hacked-online-safety-guide)
- [The Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/)
- [Holistic digital security training curriculum for women human rights defenders](https://cyber-women.com/en/)
- [Matt Mitchell's Twitter stream](https://twitter.com/geminiimatt/)
- [Rory Peck Trust's Digital Security guide for freelance journalists](https://rorypecktrust.org/freelance-resources/digital-security/)

For a curated selection, check out Martin Shelton's [Current Digital Security Resources](https://medium.com/@mshelton/current-digital-security-resources-5c88ba40ce5c) guide.

---

## 📝 Licenza

Quest'opera è distribuita con [Licenza Creative Commons Attribuzione - Non commerciale - Condividi allo stesso modo 4.0 Internazionale](http://creativecommons.org/licenses/by-nc-sa/4.0/).
