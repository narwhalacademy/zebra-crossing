# TLDR Guide to Digital Security

### 🤔 Who this guide is for

- You use the internet on a day-to-day basis – for work, social media, financial transactions, etc.
- You feel you could be doing more to ensure your digital safety and privacy, but you're also not in immediate danger. (If you are, seek out an expert for a 1:1 consult.)
- You're comfortable with technology. For example, you're comfortable going into the settings section of your computer/smartphone.

### 🌱 How this guide works

- Recommendations have been sorted in ascending levels of difficulty. Start from level one and work your way up!
- *I recommend doing everything in levels one, two and three.* I did, and I'm only a mildly technically-competent person.
- The scenario-based recommedations assume that you've done everything in levels 1-3.
- This guide is a living document – please feel free to submit a pull request or fork your own version of this guide on GitHub.

### 🕒 Last updated

- 6 October 2019

---

## 🧐 Theory & science

### 🎯 Threat modeling

- What kind of danger are you in? E.g. corporate espionage, police/state intervention, online harassment/doxxing.
- What kind of assets are you protecting? E.g. confidential documents, private photos.
- We're all in a little bit of danger (otherwise we wouldn't bother putting a password on our computer or phone) but it's important to think about what's at stake before dismissing concerns or becoming paranoid.
- For more info, read [the EFF's introduction to threat modeling](https://ssd.eff.org/en/module/introduction-threat-modeling).

### 🔗 Weakest link

- Remember the weakest link is all that matters! E.g. if password recovery is linked to email, then hackers only need to get access to your email.

### 🔡 Encryption levels

1. Not encrypted: Any third party who intercepts the data can read it as-is.
2. Regular encryption: Data is encrypted so that third parties cannot read them. But the platform (e.g. Google or Facebook) still has access, and may hand the data over to law enforcement if they are required to do so by the courts/the government.
3. End-to-end encryption: the data can only be read by the original sender and receiver. This means not even the platform has access. So if law enforcement calls, the service provider can't hand over the messages because they don't have them either.

### 🧩 Metadata

- Data about your data – e.g. what number you called, and for how long (but not the contents of the call). With enough metadata, hackers can piece together a pretty good picture of who you are, who you know, where you're going, etc. Plus legal protections around metadata are generally weaker.

---

## 💦 Level 1 recommendations

### ✅ Things to do now

#### Email

- If you're on a webmail service, check that you're logging into it using an `https://` URL. And if there isn't one, find a new email provider.
- Turn on two-factor authentication for your email service (e.g. instructions for [Gmail](https://support.google.com/accounts/answer/185839?hl=en), [Protonmail](https://protonmail.com/support/knowledge-base/two-factor-authentication/)) **if** they support an authenticator app (SMS is no longer considered safe) (e.g. [Authy](https://authy.com/), [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en)).
- After turning on two-factor authentication, see if your email service supports backup codes (a single-use code in case you lose your phone). [See Gmail instructions](https://support.google.com/accounts/answer/1187538?hl=en).

#### Good passwords

- Any password less than 10 characters is bad, but it's also okay-to-string-together-non-sequitur-words.
- Double check the security questions for your key online services (email, bank, Facebook, etc.) and make sure that they're not easy to answer by friends/looking you up on Google.
- Start using a different password for every service, because password leaks happen all the time. To make this easy, use a password manager ([Lifehacker reviews them here](https://lifehacker.com/5529133/five-best-password-managers)) to store/autofill/generate them. For now, make sure you use a unique password for essential services (email, social media, banking, cloud storage).
- Use a non-common/obvious unlock code for your phone.
- On iPhone, turn off USB Accessories in Settings > Face ID & Passcode > Allow Access When Locked.

#### Encrypt your devices

- Encrypt your phone storage: [Android](http://www.networkworld.com/article/2689371/opensource-subnet/how-to-encrypt-an-android-device-in-5-steps.html), [iOS](https://ssd.eff.org/en/module/how-encrypt-your-iphone) (many phones now encrypt by default but it's worth double checking).
- Encrypt your laptop/desktop hard drive: [Windows](https://uit.stanford.edu/service/encryption/wholedisk/bitlocker), [Windows if no BitLocker](https://veracrypt.codeplex.com/), [Mac OSX](https://support.apple.com/en-us/HT204837).
- Secure your backups too! Encrypt your backup hard drives and/or make sure your online backup storage solution supports end-to-end encryption.
- N.B. Remember encryption is only fully effective when the device is off!

#### Other

- Setup up a pin code for your mobile phone SIM card: [iPhone](https://support.apple.com/en-hk/HT201529), [Android](https://www.digitalcitizen.life/how-change-or-remove-sim-pin-android-2-steps). Search your phone provider's website to find out what their default password is (it varies from carrier to carrier).
- Turn off app-specific passwords that bypass two-factor authentication (e.g. [instructions for Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)).
- Turn off automatically add invitations on [Google Calendar settings](https://calendar.google.com/calendar/r/settings) ([here's why](https://www.forbes.com/sites/daveywinder/2019/06/11/new-security-warning-issued-for-googles-1-5-billion-gmail-and-calendar-users/#3605ff0565e5)).
- [Turn on Login Alerts on Facebook](https://www.facebook.com/settings?tab=security).
- [Disable macros within Microsoft Office](https://support.office.com/en-us/article/enable-or-disable-macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6).

### 💪🏽 Habits to cultivate

#### Email

- Be on the lookout for phishing scams: where possible double check the _From_ email address and the domains that outbound links go to.
- Don't open unnecessary email attachments. Where possible, open/preview them first in an online document reader, or have colleagues use a filesharing server or service (Dropbox, Google Drive, SpiderOak, Tresorit), which tend to be a little harder to hack into.
- You can upload a suspicious attachment to [VirusTotal](http://www.virustotal.com) for a check-up (but keep in mind files submitted to VirusTotal are available to security researchers so don’t submit sensitive information).

#### Update all the things

- When you get a notification to update your operating system (on your mobile or computer), do it right away.
- Same for apps (mobile + computer).
- Check occasionally for firmware updates for your router (and other Internet-connected devices).

#### Other

- Change important passwords (e.g. email, computer login, password manager master) every year or two.
- Wipe your devices properly before donating/giving away: [phone](http://lifehacker.com/5808280/what-should-i-do-with-my-phone-before-i-sell-it), [computer](http://lifehacker.com/5835369/how-do-i-securely-wipe-a-computer-before-donating-it-to-charity).
- Don't charge your phone at public charging stations/ports – they may steal your data. Consider charging your portable battery instead.

---

**👍 Great job! You've covered the basics.  
👍 What about trying out the next level?**  

---

## 💦💦 Level 2 recommendations

### ✅ Things to do now

#### Enhance your privacy

- Review the privacy settings on social networks you frequent: who can see your content, who can comment on it, and who can see your location.
- Install these protective web browsers add-ons (and make sure they're on even during private/incognito mode):
  - An ad blocker (e.g. [uBlock Origin](https://github.com/gorhill/uBlock/), [Ghostery](https://www.ghostery.com/)).
  - A tracker blocker ([Privacy Badger](https://www.eff.org/privacybadger)).
  - [HTTPS Everywhere](https://www.eff.org/https-everywhere).
- If you use smart speakers, turn off its recording function: instructions for [Google Home](https://myaccount.google.com/activitycontrols/audio) and for [Amazon Alexa](https://twitter.com/geminiimatt/status/1125611726773334017).

#### Other

- Set up your devices with third-party applications (e.g. [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/) so you can remotely track, wipe, and encrypt your devices from a website in the future.
- Review what's connected to your main email/social media accounts (e.g. what kinds of services have access to Facebook, and what data can they access and/or can they post on your behalf).
- Review the extensions/add-ons/plug-ins that have been installed within your computer web browser – delete any that you haven't used in a while or don't remember installing.
- Download and run [Stethoscope](https://ragtag.org/stethoscope) for your computer, which make sure your basic security settings (encryption, firewall, screen locks, etc.) are covered.

### 💪🏾 Habits to cultivate

#### Enhance your privacy

- Post less personal information online – especially information that can be used to identify/track/scam you (addresses, phone numbers, birthday, etc.). Remember almost everything you say online is logged somewhere and that even if your setup is secure, your recipient's setup may not be.
- Buy a privacy screen (prevents onlookers from seeing your screen, see [this 3M example](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/All-3M-Products/Privacy-Screen-Protectors/Privacy-Products/Black-Privacy/)) for your laptop and/or phone.
- If you own domains, use WHOIS privacy services and stick with it (they're worth the money). But note that with WHOIS lookup/history tools, if you've ever put in your real address, it's very difficult to remove from the logs.

#### Other

- Use a paid VPN service when on public networks (e.g. cafe wifi) – free VPN services are bad because operators don't have enough incentive to protect you/your data. See recommendations from [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/).
- Check what apps you have installed on your phone once in a while, and delete the ones you're not using anymore.
- If you ever need to send someone a password, split it in half and send via two different channels (e.g. email + voice call).
- Put a sticker (or webcam cover) over your laptop's front-facing camera.
- Don't use Google/Twitter/Facebook to sign up/login to other services – each service should have its own account.

---

**🎉 Congratulations! You're now reasonably  
🎉 secure, which is more than most :)**

---

## 💦💦💦 Level 3 recommendations

### ✅ To do

#### Lock up sensitive files

- Identify files that you don't want others to access (e.g. private photos, passport documents).
- Use [Cryptomator](https://cryptomator.org/) or [Veracrypt](https://www.veracrypt.fr/en/Home.html) to create an encrypted, password-protected vault for them.
- Set them up on both your desktop/laptop and your phone.
- Move your files into these secure vaults. Make sure they're not still hanging around on an old folder or on your phone.

#### Revisit old passwords

- Store all of your online service passwords in a password manager. (If you have the right browser add-on/plugin installed, it will capture all the relevant details during a login process.)

- Using your password manager's analysis feature, see which accounts/services have weak passwords and update the ones that might have any personal information about you or that you would really hate to lose.

### 💪🏾 Habits to cultivate

- Start using [Signal](https://whispersystems.org/), an end-to-end encrypted mobile messaging app that's generally agreed to be safe/secure/robust. (Beyond Signal, there is little consensus on what's secure and people tend to get very emotional about their choice of mobile messaging apps.)
- When making voice or video calls, use an end-to-end encrypted app (e.g. Signal, Jitsi, Wire).
- Buy a harder-to-hack mobile phone ($$$). Typically, this is an iPhone or Android phone that implements a "pure" Google version of Android.

---

**😲 Wow, you even finished the difficult  
😲 digital housekeeping tasks. Well done!**

---

## 💦❗️ Scenario-based recommendations

### 🛫 Crossing an international border

- If you're entering a country with a track record of seizing travelers' data **and** you're carrying highly sensitive information – see [Wired's guide](https://www.wired.com/2017/02/guide-getting-past-customs-digital-privacy-intact/) and [BoingBoing's addendum](http://boingboing.net/2017/02/12/how-to-cross-a-us-or-other-b.html) about making data unavailable, setting up burner accounts, and filing for attorney privileges at the border.
- Put your phone into airplane mode so that it's offline – in some jurisdictions officers (e.g. [Canada](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf)) aren't allowed to search through remote content.
- Don't put any stickers on your laptop or phone that could be mistaken as a hacking and/or political organization – it might get you stopped at the border one day.

---

### 😭 Somebody took my phone/computer!

- Wipe your phone remotely: see instructions for [Android](https://support.google.com/accounts/answer/6160491?hl=en), [iOS](https://support.apple.com/kb/PH2701?locale=en_US).
- Log out of all important accounts from another device.
- If this happened at an international border: Ask for a seizure receipt (available in some jurisdictions, e.g. [Canada](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf))
- Get a new SIM card.
- If you get it back, reset your phone/computer back to its factory settings. Then run some anti-virus and anti-spyware programs just in case.

---

### 👾 I think my computer has been hacked!

- Download an application that will notify you when data is being sent out from your computer. E.g. [Little Snitch for Mac](https://www.obdev.at/products/littlesnitch/index.html).
- Run Activity Monitor on Mac or Process Explorer on Windows to look at what processes/applications are running. Google any suspicious names.
- Login to important online accounts to see if there have been any suspicious logins – see [this Motherboard guide for details](https://motherboard.vice.com/en_us/article/bjeznz/how-do-you-know-when-youve-been-hacked-gmail-facebook).

---

### 🍆 Sexting & non-consensual image sharing

- See [The Motherboard Guide to Sexting Securely](https://motherboard.vice.com/en_us/article/mb3nd4/how-to-sext-securely-safely-what-apps-to-use-sexting).

---

### ✊🏾 Attending a protest

#### In case of emergency

- Draft a message to a trusted friend (not at protest) or legal hotline. Be ready to hit send if you are arrested/there is an emergency.
- Bring a spare battery for your phone.
- If you use thumbprint (or facial recognition) unlock, immediately power off your phone if you're ever arrested. In some jurisdictions, [officers can compel you to provide your fingerprint but not your passcode](http://www.theatlantic.com/technology/archive/2016/05/iphone-fingerprint-search-warrant/480861/). Better yet, turn off fingerprint or face ID before going to a protest.
- If you're attending a high-risk protest: leave your phone at home or use burner phone.

#### Store less share less

- Keep as little sensitive personal information or incriminating information as possible – you never know whose hands it might end up in.
- Turn on disappearing messages if your messaging app supports it:
  - Within a chat in Signal: Tap here for settings > Disappearing Messages
  - Within a chat in Wire: Tap the timer icon on the bottom right.
- Turn off location history:
  - iPhone: Settings > Privacy > Location Services > System Services > Significant Locations
  - Android: Settings > Google > Google Account > Data & personalization > Location History > Manage setting > Your account & all your devices > turn off Use Location History
  - Google Maps: Settings > Maps history > Web & App Activity
- If you need to share photos, erase the associated metadata first using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).
- Delete past location history:
  - iPhone: Settings > Privacy > Location Services > System Services > Significant Locations > Clear History
  - [Android](https://support.google.com/accounts/answer/3118687?hl=en#delete)
  - [Google Maps](https://support.google.com/maps/answer/3137804?hl=en)

#### Other

- Double check your messaging apps privacy settings.
- Turn off message previews in your notifications:
  - iOS: Settings > Notifications > Show Previews: When Unlocked
  - Android: Settings > Apps & notifications > Notifications > On lock screen: Hide sensitive content
- Remember to make voice calls through end-to-end encrypted apps like Signal or Whatsapp.
- More info from the EFF about protesting [in the US](https://ssd.eff.org/en/module/attending-protests-united-states) and [internationally](https://ssd.eff.org/en/module/attending-protests-international).

---

### 🕵🏼‍♂️ Online harassment & doxxing

Harassment and doxxing can get very specific and complicated based on the attacker, your position, the overall cultural context, etc. While we have some general suggestions below, we implore you to think about whether your situation has escalated sufficiently and whether it's time to find professional, one-on-one help.

#### Recruit a trusted friend

- Do not force yourself into a corner by going at this alone!
  
  - Baseline: Ask a trusted friend to hold space for your situation and be your sounding board on analyzing how bad the threat is.
  
  - Preferred: Ask a trusted friend to help you investigate, record, report and block harassers – see Take Back The Tech's [Hey Friend!](https://www.takebackthetech.net/know-more/heyfriend) guide for more details about this. In some cases, it may be healthier to hand over your phone/social media/accounts over to them so that you're not constantly triggered.

- Alternately, reach out to online communities you're an active member of and ask for help. See PEN America's article on [Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/cyber-safety/deploying-your-supportive-cyber-communities/).

- If no one is available right now, Heartmob has a list of [supportive organizations](https://iheartmob.org/resources/supportive_organizations), some of which have 24/7 hotlines.

#### Monitor updates & collect receipts

- Set up a [Talkwalker](https://www.talkwalker.com/alerts) and/or [Google Alerts](https://www.google.com/alerts) for your name/nickname.

- Start logging (date, time, description, screenshot) incidents in whatever program/app that's easiest for you.

#### Remove your personal information from the internet

- Pay [PrivacyDuck](https://www.privacyduck.com/) to scrub your information online. If you are an activist you can contact [Equity Labs](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c) for a discounted rate.

- Pay [Reputation.com](https://www.reputation.com/) to remove your information from paid sites and monitor them to make sure it stays removed.

- Alternately, both [PrivacyDuck](https://www.privacyduck.com/resources/) and [Motherboard](https://motherboard.vice.com/en_us/article/ne9b3z/how-to-get-off-data-broker-and-people-search-sites-pipl-spokeo) have free online resources to help you remove your information yourself.

#### Obscure your personal information

- Use [Burner](http://www.burnerapp.com/) to set up burner phone numbers for calling/texting.

- Use [Traveling Mailbox](https://travelingmailbox.com/) to obscure your postal address.

- Delete old accounts to eliminate traces of personal information on the Internet. Use [Justdelete.me](http://Justdelete.me) to accelerate this process.

- Review your social media accounts and delete any posts that reveal too much about where you live/where you go/who you're with.

- For Twitter users:
  
  - Ask around in your communities for shared [block lists](https://help.twitter.com/en/using-twitter/advanced-twitter-block-options) of known offenders.
  
  - Use [Semiphemeral](https://micahflee.com/2019/06/semiphemeral-automatically-delete-your-old-tweets-except-for-the-ones-you-want-to-keep/) to delete most of your unwanted posts on Twitter. (Requires use of the command line.)

#### Ignore/reply/report/block your harassers

- Together with your support person/friend and the log of receipts, decide on your course of action (these aren't mutually exclusive):
  
  - Ignore: Sometimes harassers will walk away if they don't get attention.
  
  - De-escalate: In some contexts, you can defuse the situation with some calm words before it gets worse.
  
  - Report: Report the harasser to the relevant online platform and/or your local law enforcement.
  
  - Mute on social media: Allows for peace of mind.
  
  - Block on social media: Maximizes peace of mind as the harasser won't be able to see your posts. But they will notice and see it as a sign of escalation.
  
  - Go public: Can be dangerous, but sometimes shaming them publicly or rallying people to your support will make them go away.

#### For more information

- See Feminist Frequency's [Speak Up & Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/).

- See TrollBusters' [What to Do? Where to Go? Infographic](https://yoursosteam.wordpress.com/what-to-do-infographic/).

- See Equity Labs' [Anti-Doxing Guide for Activists Facing Attacks from the Alt-Right](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c).

- See HeartMob/Hollaback's [Technical Safety Guide](https://iheartmob.org/resources/tech).

- See Crash Override (RIP)'s [So You've Been Doxed](http://www.crashoverridenetwork.com/soyouvebeendoxed.html) and [Preventing Doxing](http://www.crashoverridenetwork.com/preventingdoxing.html).

---

### 👤 Creating an untraceable online persona under a pseudonymn

- If you're a public figure, artist or activist, consider working under a persistent pseudonymn or collective identity – this [Tactical Tech manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online) has more details on why.

- To operate online under a truly safe pseudonymn, follow this guide on [creating untraceable online accounts and protecting your real identity](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46).

---

## 💦❓ Other recommendations

This section is a catch-all for difficult or esoteric practices that do not fall under any of our scenarios above and might not have any immediate payoff for the casual user.

#### Emails

- Sign up for a [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) end-to-end encrypted email account.
- Approach PGP emails at your own risk ([recently disclosed security vulnerabilities](https://www.eff.org/deeplinks/2018/05/not-so-pretty-what-you-need-know-about-e-fail-and-pgp-flaw-0) means that it's no longer bulletproof).

#### Access

- Buy a [YubiKey](http://www.amazon.com/Yubico-Y-072-YubiKey-NEO/dp/B00LX8KZZ8/ref=sr_1_1?ie=UTF8&qid=1421839152&sr=8-1&keywords=yubikey+NEO) USB key to use for two-factor authentication.
- Use an alphanumeric passcode to unlock your phone.
- [Generating Diceware passwords](http://world.std.com/~reinhold/diceware.html).

#### File storage & sharing

- Use an end-to-end encrypted cloud storage service (not Dropbox): [Tresorit](https://tresorit.com/), [SpiderOak](https://spideroak.com/).
- Use encrypted external USB/hard drives from companies like [Apricorn](https://www.apricorn.com/).
- If you want to send a file anonymously, use a special sharing service like [OnionShare](https://onionshare.org/).
- Instead of Google Docs or Microsoft Office, use [CryptPad](https://cryptpad.fr) (open-source, end-to-end encrypted).

#### Messaging apps

- WhatsApp additional settings:
  
  - To be 100% end-to-end encrypted, turn off chat backups on WhatsApp (Settings > Chats > Chat backup) and delete your previous backups (instructions for [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).
  
  - Turn on security notifications on WhatsApp (Settings > Account > Security).
  
  - Set up a pin number to prevent your account from being moved without your permission (Settings > Account > Two-Step Verification).

- If you're a journalist who uses Signal regularly, step up your safety practices try following Martin Sheldon's [Locking Down Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) guide (or [similarly for WhatsApp](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3) if you use that a lot).

#### Other

- Keep less information/data/photos on your devices – you can't lose what you don't have!
- Don't use smart TVs or smart speakers.
- Search the web anonymously with [DuckDuckGo](http://duckduckgo.com/).
- Fortify your self-hosted Wordpress website with [Cloudflare](https://www.cloudflare.com) + [iThemes Security](https://wordpress.org/plugins/better-wp-security/).
- Set up a fenced off, secure OS: [Tails](https://ssd.eff.org/en/module/keeping-your-data-safe).
- For Android users: Download apps using [F-Droid](https://f-droid.org), an open-source, security-focused app store.
- For US residents: Freeze your credit to prevent hackers from accessing sensitive data. See Security Checklist's [Freeze Your Credit](https://securitycheckli.st/) section for details.

---

**🏆 Oh my, you made it this far.  
🏆 You are a true champ!**

---

## 🧠 Sources

These are the main sources that I drew from, all of which were tremendously helpful and are good guides in their own right:

- [Digital Security Low Hanging Fruit](https://www.johnscottrailton.com/jsrs-digital-security-low-hanging-fruit/) by John Scott-Railton
- [Computer Security Tools and Concepts for Lawyers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2831739) by Kendra Albert
- [Crash Override's Resource Center](http://www.crashoverridenetwork.com/resources.html)
- [The Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/)
- [How to encrypt your entire life in less than an hour](https://medium.freecodecamp.com/tor-signal-and-beyond-a-law-abiding-citizens-guide-to-privacy-1a593f2104c3#.z1estrrkj) by Quincy Larson
- [Anti-Doxing Guide for Activists Facing Attacks from the Alt-Right](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c) by Equity Labs
- [The Motherboard Guide to Not Getting Hacked](https://motherboard.vice.com/en_us/article/d3devm/motherboard-guide-to-not-getting-hacked-online-safety-guide)
- [A Guide to Digital Safety](https://cryptpad.fr/pad/#/2/pad/view/J38ub5rvVRaN5uNfbYJIuo4Ov8MAobKEC9Om-QCddDg/)
- [Matt Mitchell's Twitter stream](https://twitter.com/geminiimatt/)

Let me know by filing an issue if there are any other guides that you found useful that you think I should include.

---

## 📝 License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
