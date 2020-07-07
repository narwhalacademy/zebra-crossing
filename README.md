# 🦓 Zebra Crossing: an easy-to-use digital safety checklist

### 🤔 Who this guide is for

- You use the internet on a day-to-day basis – for work, social media, financial transactions, etc.
- You feel you could be doing more to ensure your digital safety and privacy, but you're not in immediate danger. (If you are, seek out an expert for a one-on-one consult.)
- You're comfortable with technology. For example, you're comfortable going into the settings section of your computer/smartphone.

### 🌱 How to use this guide

- Recommendations have been sorted in ascending levels of difficulty. Start from level one and work your way up!
- *Everyone should follow the recommendations in levels one and two.* They will protect you from the widely-used (yet simple) attacks. Going through them shouldn't take more than 1-2 hours.
- Level three is a bit more involved in terms of time and money and may not be 100% necessary. But if you're worried at all and can afford to, we recommend going through that list too. Depending on the amount of digital housekeeping you have to do, it may take anywhere from an hour to an afternoon.
- The scenarios listed after are for higher-stakes situations — scan them to see if any of them apply to you. (Because the stakes are higher, they assume that you've done everything in levels 1-3.)
- This guide is a living document – please feel free to submit a pull request or fork your own version of this guide on GitHub.

### 🗣 This guide in other languages

- [繁體中文 (Traditional Chinese)](README-繁體中文.md)
- [日本語](README-日本語.md) (Japanese, a work-in-progress)
- [Italiano](README-Italiano.md) (Italian, a work-in-progress)

### 🕒 Last updated

- 7 July 2020

---

## 🧐 Theory & science

### 🎯 Threat modeling

- What kind of danger are you in? E.g. credit card hack, corporate espionage, online harassment/doxxing.
- What kind of assets are you protecting? E.g. confidential documents, private photos.
- We're all in a little bit of danger (otherwise we wouldn't bother putting a password on our computer or phone) but it's important to think about what's at stake before dismissing concerns or becoming paranoid.

### 🔗 Weakest link

- Remember the weakest link is all that matters! E.g. if password recovery is linked to email, then hackers only need to get access to your email.

### 🔡 Encryption levels

1. Not encrypted: Any third party who intercepts the data can read it as-is.
2. Regular encryption: Data is encrypted so that third parties cannot read them. But the platform (e.g. Google or Facebook) still has access, and may hand the data over to law enforcement if they are required to do so by the courts.
3. End-to-end encryption: the data can only be read by the original sender and receiver. This means not even the platform has access. So if the courts call, the service provider can't hand over the messages because they don't have them either.

### 🧩 Metadata

- Data about your data – e.g. what number you called, and for how long (but not the contents of the call). With enough metadata, hackers can piece together a pretty good picture of who you are, who you know, where you're going, etc. Plus legal protections around metadata are generally weaker.

---

## 💦 Level 1 recommendations

### ✅ Things to do now

#### Email

- If you're on a webmail service, check that you're logging into it using an `https://` URL. And if there isn't one, find a new email provider.
- Turn on two-factor authentication for your email service (e.g. instructions for [Gmail](https://support.google.com/accounts/answer/185839?hl=en), [Protonmail](https://protonmail.com/support/knowledge-base/two-factor-authentication/)) through an authenticator app (e.g. [Authy](https://authy.com/), [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en)). Do no rely on SMS text messages as they are no longer considered safe.
- After turning on two-factor authentication, see if your email service supports backup codes (a single-use code in case you lose your phone). [See Gmail instructions](https://support.google.com/accounts/answer/1187538?hl=en).

#### Good passwords

- Any password less than 10 characters is bad, but it's also okay-to-string-together-non-sequitur-words.
- Double check the security questions for your key online services (email, bank, Facebook, etc.) and make sure that they're not easy to answer by friends/looking you up on Google.
- Start using a different password for every service, because password leaks happen all the time. To make this easy, use a password manager ([Lifehacker reviews them here](https://lifehacker.com/5529133/five-best-password-managers)) to store/autofill/generate them. For now, make sure you use a unique password for essential services (email, social media, banking, cloud storage).
- Use a non-common/obvious unlock code for your phone with at least 8 digits.
- On iPhone, turn off USB Accessories in Settings → Face ID & Passcode → Allow Access When Locked.

#### Encrypt your devices

- Encrypt your phone storage: [Android](http://www.networkworld.com/article/2689371/opensource-subnet/how-to-encrypt-an-android-device-in-5-steps.html), [iOS](https://ssd.eff.org/en/module/how-encrypt-your-iphone) (many phones now encrypt by default but it's worth double checking).
- Encrypt your laptop/desktop hard drive: [Windows](https://uit.stanford.edu/service/encryption/wholedisk/bitlocker), [Windows if no BitLocker](https://veracrypt.codeplex.com/), [Mac OSX](https://support.apple.com/en-us/HT204837).
- Secure your backups too! Encrypt your backup hard drives and/or make sure your online backup storage solution offers end-to-end encryption (which neither iCloud or Google Drive support).
- N.B. Remember encryption is only fully effective when the device is off!

#### Other

- Setup up a pin code for your mobile phone SIM card: [iPhone](https://support.apple.com/en-hk/HT201529), [Android](https://www.digitalcitizen.life/how-change-or-remove-sim-pin-android-2-steps). Search your phone provider's website to find out what their default password is (it varies from carrier to carrier).
- Turn off app-specific passwords that bypass two-factor authentication (e.g. [instructions for Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)).
- Turn off automatically add(ed) invitations on [Google Calendar settings](https://calendar.google.com/calendar/r/settings) ([here's why](https://www.forbes.com/sites/daveywinder/2019/06/11/new-security-warning-issued-for-googles-1-5-billion-gmail-and-calendar-users/#3605ff0565e5)).
- [Turn on Login Alerts on Facebook](https://www.facebook.com/settings?tab=security).
- [Disable macros within Microsoft Office](https://support.office.com/en-us/article/enable-or-disable-macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6).The **School** of **Journalism** and Communication

### 💪🏽 Habits to cultivate

#### Email

- Be on the lookout for phishing scams: where possible double check the _From_ email address and the domains that outbound links go to.
- Don't open unnecessary email attachments. Where possible, open/preview them first in an online document reader, or have colleagues use a filesharing server or service (Dropbox, Google Drive, SpiderOak, Tresorit), which tend to be a little harder to hack into.
- You can upload a suspicious attachment to [VirusTotal](http://www.virustotal.com) for a check-up (but keep in mind files submitted to VirusTotal are available to security researchers so don’t submit sensitive information).

#### Update all the things

- When you get a notification to update your operating system (on your mobile or computer), do it as soon as you can.
- Same for apps (mobile + computer).
- Check occasionally for firmware updates for your router (and other Internet-connected devices).

#### Other

- Change important passwords (e.g. email, computer login, password manager master) every year or two.
- Wipe your devices properly before donating/giving away: [phone](http://lifehacker.com/5808280/what-should-i-do-with-my-phone-before-i-sell-it), [computer](http://lifehacker.com/5835369/how-do-i-securely-wipe-a-computer-before-donating-it-to-charity).
- Don't charge your phone at public charging stations/ports – they may steal your data. Consider charging your portable battery instead.

---

**👍 Great job! You've covered the basics. 
👍 Treat yourself to a cup of tea and a stretch.  
👍 Now, ready for the next level?**

---

## 💦💦 Level 2 recommendations

### ✅ Things to do now

#### Enhance your privacy

- Review the privacy settings on social networks you frequent: who can see your content, who can comment on it, and who can see your location.
  - Limit Facebook tracking by turning off Off-Facebook Activity (follow [these EFF's instructions](https://www.eff.org/deeplinks/2020/01/how-change-your-facebook-activity-settings)).
- Review the privacy settings on messaging apps you normally use: read receipts, time stamps for "last seen," and whether your phone number/profile picture are public.
- Install these protective web browsers add-ons on your laptop/desktop computer (and make sure they're on even during private/incognito mode):
  - An ad blocker (e.g. [uBlock Origin](https://github.com/gorhill/uBlock/), [Ghostery](https://www.ghostery.com/)).
  - A tracker blocker ([Privacy Badger](https://www.eff.org/privacybadger)).
  - [HTTPS Everywhere](https://www.eff.org/https-everywhere).
- Review which apps on your smartphone have access to your location data. Turn off access if the app doesn't need it, and minimize the number of apps that track your location all the time.
  - iOS: Settings → Privacy → Location Services
  - Android: Settings → Apps & notifications → App permissions
- If you use smart speakers, turn off its recording function: instructions for [Google Home](https://myaccount.google.com/activitycontrols/audio) and for [Amazon Alexa](https://twitter.com/geminiimatt/status/1125611726773334017).

#### Other

- Set up your devices with third-party applications (e.g. [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/) so you can remotely track, wipe, and encrypt your devices from a website in the future.
- Review the "Third-Party Apps" or "Connected Apps" on your main email/social media accounts. These are services that might have access to, say, your Facebook data and even permission to make posts automatically there. ([Here are the instructions for checking for them on Facebook and Gmail](https://www.online-tech-tips.com/computer-tips/check-google-facebook-connected-apps/).)
- Review the extensions/add-ons/plug-ins that have been installed within your computer web browser – delete any that you haven't used in a while or don't remember installing.
- Download and run [Stethoscope](https://ragtag.org/stethoscope) for your computer, which make sure your basic security settings (encryption, firewall, screen locks, etc.) are covered.

### 💪🏾 Habits to cultivate

#### Enhance your privacy

- Post less personal information online – especially information that can be used to identify/track/scam you (addresses, phone numbers, birthday, etc.). Remember almost everything you say online is logged somewhere and that even if your setup is secure, your recipient's setup may not be.
- If you own domains, use WHOIS privacy services and stick with it (they're worth the money). But note that with WHOIS lookup/history tools, if you've ever put in your real address, it's very difficult to remove from the logs.

#### Watch what you say in online groups

Don't say anything you'd regret on in a "private" Slack group, Facebook page, WhatsApp group chat or Telegram channel because:

- Any one member can leak all of the data.
- Administrators usually have access to everything within the group, including that private direct message between two people, and sometimes even deleted messages.
- Even if you're not using your real name or photo, what you say can often be traced back to your phone number or email (that is linked to the account).
  - To prevent this in Telegram, go into Settings → Privacy and Security → Phone Number, and then set:
    - `Who can see my phone number` to `Nobody` 
    - `Who can find me by my number` to `My Contacts` 

#### Other

- When you download new mobile apps, double check to make sure it's the right one — there are a lot of fake apps that try to trick people by using a slightly modified name or icon of an existing, popular app.
- Check what apps you have installed on your phone once in a while, and delete the ones you're not using anymore.
- If you ever need to send someone a password, split it in half and send via two different channels (e.g. email + voice call).
- Put a sticker (or webcam cover) over your laptop's front-facing camera.
- Don't use Google/Twitter/Facebook to sign up/login to other services – each service should have its own account.

---

**🎉 Congratulations! You're now reasonably  
🎉 secure, which is more than most :)  
🎉 Take the rest of the day off, and  
🎉 come back tomorrow for Level 3.**

---

## 💦💦💦 Level 3 recommendations

### ✅ To do

#### Lock up sensitive files

- Identify files that you don't want others to access (e.g. private photos, passport documents).
- Use [Cryptomator](https://cryptomator.org/) or [Veracrypt](https://www.veracrypt.fr/en/Home.html) to create an encrypted, password-protected vault for them.
- Set them up on both your desktop/laptop and your phone.
- Move your files into these secure vaults. Make sure they're not still hanging around on an old folder or on your phone.

#### Upgrade your gear

- Use a paid VPN service when on public networks (e.g. cafe wifi) and even at home if you don't want your service provider to know where you're going. Free VPN services are bad because operators don't have enough incentive to protect you/your data. See recommendations from [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/).
- Buy a privacy screen (prevents onlookers from seeing your screen, see [this 3M example](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/All-3M-Products/Privacy-Screen-Protectors/Privacy-Products/Black-Privacy/)) for your laptop and phone.

#### Revisit old passwords

- Store all of your online service passwords in a password manager. (If you have the right browser add-on/plugin installed, it will capture all the relevant details during a login process.)
- Using your password manager's analysis feature, see which accounts/services have weak passwords and update the ones that might have any personal information about you or that you would really hate to lose.

### 💪🏾 Habits to cultivate

- Start using [Signal](https://signal.org/), an end-to-end encrypted mobile messaging app that's generally agreed to be safe/secure/robust. (Beyond Signal, there is little consensus on what's secure and people tend to get very emotional about their choice of mobile messaging apps.)
- When making voice or video calls, use an end-to-end encrypted app (e.g. Signal, Jitsi, Wire).
- Buy a harder-to-hack mobile phone ($$$). Typically, this is an iPhone or Android phone that implements a "pure" Google version of Android.

---

**😲 Wow, you completed all three levels!  
😲 Well done! Now quickly look below  
😲 to see if any apply to you.**

---

## 💦❗️ Scenario-based recommendations

### 👩🏿‍💻 Hosting a public event on a video calling platform (e.g. Zoom)

- Set a password to enter the meeting to prevent random people from wandering in via a meeting ID generator. Consider setting up an RSVP system so that you don't have to give out the meeting link and password publicly.
- Familiarize yourself with the platform's settings and minimize the amount of control (e.g. screen sharing) that non-hosts have. (E.g. [settings on Zoom](https://blog.zoom.us/wordpress/2020/03/20/keep-uninvited-guests-out-of-your-zoom-event/))
- Create a plan of action for what you would do if a malicious troll gains access to your call.
- Don't say what you wouldn't say in a public forum. Encourage your attendees to do the same. Most commercial platforms have access to your audio/video data and are mining your metadata to create consumer profiles.

---

### 🛫 Crossing an international border

- Turn off your devices because:
  - Storage/hard drives are only encrypted when they're off, **not** when they're just in sleep mode
  - This will also ensure that your mobile devices require a pin when they are turned on, which is protected by freedom of speech laws in some jurisdictions.
- Store less information on your devices – in case they're seized, what you don't have they can't take.
- Be mindful of what stickers you put on your devices – a border agent could mistake them for something suspicious.
- Notify your people about your flight number and arrival time. Check in with one of them at regular points in your journey. Have them contact a lawyer/relevant organization if you do not show up.
- For extreme situations (some of these practices might raise suspicions and backfire):
  - Set up alternate photo albums, email addresses and social media accounts full of harmless content.
  - "Forget" half of your password: Password lock your device/account so that only a trusted friend has the second half of the password.
  - Log out of all important accounts (or simply leave your devices at home).
- For more information, see Wired's [Guide to Getting Past Customs With Your Digital Privacy Intact](https://www.wired.com/2017/02/guide-getting-past-customs-digital-privacy-intact/) and [BoingBoing's addendum](http://boingboing.net/2017/02/12/how-to-cross-a-us-or-other-b.html) about filing for attorney privileges at the US border.

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
- Setup a spare smartphone using [Haven](https://guardianproject.github.io/haven/) as a room monitor to detect unwanted intrusions.

---

### 🍆 Sexting & non-consensual image sharing

- See [The Motherboard Guide to Sexting Securely](https://motherboard.vice.com/en_us/article/mb3nd4/how-to-sext-securely-safely-what-apps-to-use-sexting).

---

### ✊🏾 Attending a protest

#### In case of emergency

- Draft a message to a trusted friend (not at protest) or legal hotline. Be ready to hit send if you are arrested/there is an emergency.
- Write the phone number of the trusted friend/hotline on your arm with permanent marker as a backup.
- Bring a spare battery for your phone.
- If you use your fingerprint or face to unlock your phone, turn it off for now. In some places, [officers can compel you to provide your fingerprint but not your passcode](http://www.theatlantic.com/technology/archive/2016/05/iphone-fingerprint-search-warrant/480861/).
- Immediately power off your phone if you think you'll be arrested (disk encryption works better if it's off).
- Consider using a burner phone with a burner SIM card.

#### Store less share less

- Keep as little sensitive personal information on your phone as possible. Delete any photos, chat logs and notes that can be used against you.
- Use a messaging app that lets you create disappearing messages (e.g. [Signal](https://signal.org/)). Turn on the timer when discussing the protest.
- Don't take any photos or videos where people's faces are clearly visible. Taking a photo of people's backs is okay. (The one exception is if you're filming a video of a conflict or arrest where documentation is key.)
- Wear a face mask so you are not easily caught on camera.
- When sharing photos/videos:
  - Blur the faces of any protesters. (Use Everest Pipkin's [Image Scrubber](https://everestpipkin.github.io/image-scrubber/) or [Signal's blur tool](https://signal.org/blog/blur-tools/) for photos, and Youtube's [blur faces tool](https://youtube-eng.googleblog.com/2017/08/blur-select-faces-with-updated-blur.html) for videos.)
  - If need be, erase the location metadata using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).

#### Minimize location tracking

- Turn off location history:
  - iPhone: Settings → Privacy → Location Services → System Services → Significant Locations
  - Android: Settings → Google → Google Account → Data & personalization → Location History → Manage setting → Your account & all your devices → Use Location History Off
  - Google Maps: Settings → Maps history → Web & App Activity
- Delete past location history:
  - iPhone: Settings → Privacy → Location Services → System Services → Significant Locations → Clear History
  - [Android](https://support.google.com/accounts/answer/3118687?hl=en#delete)
  - [Google Maps](https://support.google.com/maps/answer/3137804?hl=en)
- Consider turning off all location services temporarily:
  - iPhone: Settings → Privacy → Location Services → Location Services Off
  - Android: Security & location → Location → Use location Off

#### Other

- Double check your messaging apps' privacy settings.
- Turn off message previews in your notifications:
  - iOS: Settings → Notifications → Show Previews: When Unlocked
  - Android: Settings → Apps & notifications → Notifications → On lock screen: Hide sensitive content
- Remember to make voice calls through end-to-end encrypted apps like [Signal](https://signal.org/).

---

### 📰 I'm a journalist working on a sensitive topic

Below are some basics that all journalists should consider. If you're working on/in a particularly sensitive story/region (e.g. a whisteblower story), you and your team should get an tailored training session from an expert.

#### Be prepared

- To remotely wipe the contents of your devices using a tracking app (e.g. [Find My](https://www.apple.com/icloud/find-my/) on iOS, [Find My Device](https://support.google.com/accounts/answer/6160491?hl=en) on Android, [Prey](https://www.preyproject.com), [Lookout Security](https://www.lookout.com/)).
- To be on the receiving end of an email phishing campaign (as journalist emails are usually more public than others).

#### Protect yourself

- If you're traveling, review the `Crossing an international border` scenario above.
- If you're covering a protest, review the `Attending a protest` scenario above and decide which parts apply to you (if you have special journalist rights/protections where you're working).
- Use a VPN if you're browsing the internet at the office (website administrators can usually see that you're coming from, say, the New York Times network)

#### Protect your sources

- Use email less, as [even end-to-end encrypted email leaves a trail of metadata](https://freedom.press/training/blog/how-reporters-emails-get-got-case-studies-legal-request-hacking/).
- To exchange messages, use an end-to-end encrypted messaging app that doesn't store metadata like [Signal](https://www.signal.org/). (Don't use Twitter DMs!)
- Use [Signal](https://www.signal.org/) or [Jitsi](https://jitsi.org/) for end-to-end encrypted voice and video calls.
- Use the security features in Signal and Whatsapp – see Martin Shelton's articles on [Locking Down Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) and [Upgrading WhatsApp security](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3).
- Have your organization set up [SecureDrop](https://securedrop.org/). Failing that, encourage people to use [OnionShare](https://onionshare.org/) or [Firefox Send](https://send.firefox.com/).
- Blur faces from photos and videos (e.g. Android [ObscuraCam](https://guardianproject.info/apps/obscuracam/), Youtube [instructions](https://technology.witness.org/2016/02/how-to-use-youtubes-new-blurring-feature-to-protect-identities/)).
- Erase media metadata using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).
- See Ted Han and Quinn Norton's [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/).
- See Martin Shelton's [Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/).

#### Protect your data

- Make sure you're using an email/storage provider that's not owned/linked to an organization that you're reporting on.
- Be aware that [courts can compel Google to hand over all of your data](https://medium.com/@tinfoilpress/newsrooms-lets-talk-about-g-suite-1672a36eb235).
- Move all of your work onto end-to-end encrypted platforms. (E.g. [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) for email, store documents in a [Tresorit](https://tresorit.com/) or [SpiderOak](https://spideroak.com/) cloud.) 
- Store sensitive data in a password-protected cloud or external storage device as much as possible. See the `Lock up sensitive files` section above.
- Remember to permanently erase sensitive files from your laptop/desktop: use [Eraser for Windows](https://eraser.heidi.ie/) and [File Shredder for Mac](https://apps.apple.com/us/app/fileshredder/id418094085?mt=12).

#### For more information

- If you're in an unconventional region, jurisdiction or situation, see Grégoire Pouget of Nothing2Hide's [Digital Security for Journalists Requires an Adaptable Toolkit](https://gijn.org/2019/07/16/digital-security-for-journalists-requires-an-adaptable-toolkit/) guide.
- If you're running a newsroom, see Ontheline Newsrooms' see [Measures for Newsrooms and Journalists to Address Online Harassment](https://newsrooms-ontheline.ipi.media/).

---

### 🕵🏼‍♂️ Online harassment & doxxing

Harassment and doxxing can get very specific and complicated based on the attacker, your position, the overall cultural context, etc. While we have some general suggestions below, we implore you to think about whether your situation has escalated sufficiently and whether it's time to find professional, one-on-one help.

#### Recruit a trusted friend

- Do not force yourself into a corner by going at this alone!
  - Baseline: Ask a trusted friend to hold space for your situation and be your sounding board on analyzing how bad the threat is.
  - Preferred: Ask a trusted friend to help you investigate, record, report and block harassers — see Take Back The Tech's [Hey Friend!](https://www.takebackthetech.net/know-more/heyfriend) guide for more details about this. In some cases, it may be healthier to hand over your phone/social media/accounts over to them so that you're not constantly triggered.
- Alternately, reach out to online communities you're an active member of and ask for help. See PEN America's article on [Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/cyber-safety/deploying-your-supportive-cyber-communities/).
- If no one is available right now, Heartmob has a list of [supportive organizations](https://iheartmob.org/resources/supportive_organizations), some of which have 24/7 hotlines.

#### Monitor updates & collect receipts

- Run keyword searches for your name, nickname, and address to see what's out there. Also run an image search on your most-used profile pictures.
- Set up a [Talkwalker](https://www.talkwalker.com/alerts) and/or [Google Alerts](https://www.google.com/alerts) for your name and nickname.
- Start logging (date, time, description, screenshot) incidents in whatever program/app that's easiest for you.

#### Remove information about you off of the internet

- Follow the instructions in the section/scenario that follows this one.

#### Ignore/reply/report/block your harassers

- Together with your support person/friend and the log of receipts, decide on your course of action (these aren't mutually exclusive):
  - Ignore: Sometimes harassers will walk away if they don't get attention.
  - De-escalate: In some contexts, you can defuse the situation with some calm words before it gets worse.
  - Report: Report the harasser to the relevant online platform and/or your local law enforcement.
  - Mute on social media: Allows for peace of mind.
  - Block on social media: Maximizes peace of mind as the harasser won't be able to see your posts. But they will notice and see it as a sign of escalation.
  - Go public: Can be dangerous, but sometimes shaming them publicly or rallying people to your support will make them go away.
- For Twitter users:
  - Ask around in your communities for shared [block lists](https://help.twitter.com/en/using-twitter/advanced-twitter-block-options) of known offenders.   
  - Block troll bots using [Bot Sentinel](https://botsentinel.com).
  - Reduce dogpiling by blocking all followers of a certain profile using [Twitter Block Chain](%5Bhttps://github.com/satsukitv/twitter-block-chain%5D(https://github.com/satsukitv/twitter-block-chain).
  - See what lists you've been added to by going to Profile → Lists → ··· → Lists you're on. If you see a suspicious list or list owner, tap the three dots on the top right to report the list and leave the list by blocking the creator.

#### For more information

- See Feminist Frequency's [Speak Up & Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/).
- See TrollBusters' [What to Do? Where to Go? Infographic](https://yoursosteam.wordpress.com/what-to-do-infographic/).
- See Equity Labs' [Anti-Doxing Guide](https://medium.com/@EqualityLabs/anti-doxing-guide-for-activists-facing-attacks-from-the-alt-right-ec6c290f543c).
- See HeartMob/Hollaback's [Technical Safety Guide](https://iheartmob.org/resources/tech).
- See Crash Override (RIP)'s [So You've Been Doxed](http://www.crashoverridenetwork.com/soyouvebeendoxed.html) and [Preventing Doxing](http://www.crashoverridenetwork.com/preventingdoxing.html).

---

### 👀 Remove information about you off of the internet

If you're about to become a public figure or are experiencing harassment, consider some of the suggestions below.

#### Clean up your social media presences

You might not need to delete your entire account, but consider deleting (or making private) posts that are old and/or reveal too much about where you live, where you go, and who you're with.

- Facebook:
  - See what your public profile looks and remove/restrict things as you see fit.
    - On desktop, go to your profile and click the 👁button next to the right of the Edit Profile button.
    - On mobile, go to your proflie, tap the three dots on the right of Add Story and tap View As.
  - Make it so only friends can see your past posts.
    - On desktop, go to Settings → Privacy → Limit Past Posts.
    - On mobile, go to Settings & Privacy → Settings → Privacy Settings → Limit who can see past posts.
  - To bulk delete past posts, [see this article in PC Magazine](https://www.pcmag.com/how-to/how-to-quickly-delete-old-facebook-posts).
- Whatsapp:
  - Swipe to delete individual conversations.
  - Delete chat content but keep the chat groups: Settings → Chats →  Clear All Chats.
  - Delete all chats including the chat groups: Settings → Chats → Delete All Chats.
  - Turn off chat backups on WhatsApp (Settings → Chats → Chat backup) and delete your previous backups (instructions for [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).
- Instagram:
  - Look through your profile and manually delete posts (tap the three dots above upper-right corner of a photo).
  - If need be, bulk delete using [third-party tools](https://upleap.com/blog/how-to-delete-an-instagram-post/).
- Twitter:
  - Use a third-party service to filter for tweets you want to save, and bulk delete the rest. We recommend [Semiphemeral](https://semiphemeral.com) (free + open source, but beta), [TweetDelete](https://tweetdelete.net/) (free + paid options), or [Twitter Archive Eraser](https://martani.github.io/Twitter-Archive-Eraser/) (free + paid options)
- Reddit and other forums:
  - There's often no easy solution. Sometimes you have to delete your entire account, or in the case of Reddit, you have to [use third-party scripts](https://social.techjunkie.com/how-to-delete-all-reddit-posts/) because deleting your account still leaves your posts up.

#### Remove your information from other people's websites

- Pay [PrivacyDuck](https://www.privacyduck.com/) or [Reputation Defender](https://www.reputationdefender.com/) to remove your information from English-language public and paywalled sites. See if you qualify for one of their [PrivacyDuck's discount programs](https://www.privacyduck.com/discount-programs/).
- If you want to do it yourself, check out [PrivacyDuck's guides](https://www.privacyduck.com/resources/) and Yael Grauer's [Big Ass Data Broker Opt-Out List](https://docs.google.com/document/d/1ElB7VXmr5JEkFaLJpO7YLGrAuasedmq-rZC-8TUMxTM/). (To be 100% thorough, use the latter on top of paid services.)

#### Obscure your personal information

- Use [Burner](http://www.burnerapp.com/) or [Hushed](https://hushed.com) to set up burner phone numbers for calling/texting.
- Get a PO box at a post office or use [Traveling Mailbox](https://travelingmailbox.com/) (USA only) to hide your home address.
- Delete old accounts to eliminate traces of personal information on the Internet. Use [JustDeleteMe](https://justdeleteme.xyz/) to accelerate this process.

---

### 💔 I think my partner is spying on me through my phone (stalkerware)

#### If you're not sure and things between you and your partner aren't that bad yet:

- Keep a hidden, pen-and-paper log of suspicious incidents.
- Make sure your partner is not getting information from previously shared accounts or because you left the [location share on within Google Maps](https://support.google.com/maps/answer/7326816?co=GENIE.Platform%3DAndroid&hl=en).
- Review and redo the items in Levels 1-3 of this guide. Reset your passwords, check your privacy/data sharing permissions, and look up any apps you don't recognize on your computer and phone.
- Keep an eye out for other signs. E.g. your phone battery doesnt' last very long anymore, or your laptop internet connection is slow. Review the Coalition Against Stalkerware's [full of list of indicators](https://stopstalkerware.org/get-help/).
- **Don't delete suspicious apps immediately** — you may need to keep them as evidence. Plus, deletion may also cause the situation with your partner to escalate.

#### If you're pretty sure they're spying on you and you're scared:

- Seek help. You should not go through this alone:
  - Find a public or friend's computer/phone to contact the organizations in [this global resource list compiled by the Coalition Against Stalkerware](https://stopstalkerware.org/get-help/resources/). Some of them can even help you collect evidence and remove stalkerware safely.
  - Reach out to a trusted friend (through a public device/line) and ask them to hold space for your situation and be your sounding board on analyzing how bad the situation is.
- Keep digital and printed records of relevant texts, emails, calls, etc. See the NNEDV's [guide on documenting/saving evidence](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence).
- When you no longer need evidence anymore, remove the suspicous apps/stalkerware yourself either by deleting them one by one, or by performing a full factory reset on your computer/phone. (Buying brand new device is even safer of course.) Remember to reinstall apps and import data manually, lest you restore a backup with stalkerware in it.

#### For more information

- See Wirecutter's [Protect Your Devices Against Domestic Abusers](https://thewirecutter.com/blog/domestic-abusers-can-control-your-devices-heres-how-to-fight-back/)
- See Coalition Against Stalkerware's [Safety Toolkit](https://stopstalkerware.org/get-help/)

---

### 👤 I don't want to give out my real phone number for online dating/networking/organizing

For messaging apps that use phone numbers as the primary identifier/username (e.g. Signal, WhatsApp, Telegram), get a secondary number from:

- [Twilio](https://www.twilio.com) (1 USD/month, but complicated setup – see the Twilio section [here](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46) and [this guide](https://source.opennews.org/articles/shields-using-signal-without-your-phone-number/))
- [Google Voice](https://voice.google.com/about) (free but only available in the US)
- [Burner](https://www.burnerapp.com/) or [Hushed](https://hushed.com) (5 and 4 USD/month respectively + other prepaid plans for short-term use, US/Canada numbers)
- A phone company: get a prepaid or cheap SIM card plan (rates vary)

For sites and services that use email as the primary identifier/username, get a separate, new email address.

Keep in mind:

- If you lose/unsubscribe to your secondary phone number, other people can buy it and impersonate you.
- Courts can still compel companies to hand over your information in most cases. 

#### For true anonymity – create an untraceable online persona under a pseudonymn

- If you're a public figure, consider working under a persistent pseudonymn or collective identity – this [Tactical Tech manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online) has more details on why.
- To operate online under a truly safe pseudonymn, follow this guide on [creating untraceable online accounts and protecting your real identity](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46).

---

### 🤐 Traveling to a place with weak data protection laws or internet censorship

- Be aware that the phone companies there might share your location data and personal info with others without permission.
- Setup a VPN beforehand so you can a) access services uninterrupted, and b) to minimize the amount of data collected about you. Avoid VPNs that are free or have opaque ownership. See recommendations from [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/).
- Consider traveling with a burner phone while leaving your laptop at home. This will be especially useful if you need to install new/untested software for work that might violate data privacy policies.
- Re-evaluate which online services are safe to use:
  - If available, see how often your favorite service hands over its data by looking up their transparency reports:
    - [Google Transparency Report: Request for user information](https://transparencyreport.google.com/user-data/overview)
    - [Facebook Transparency Report: Government Requests for User Data](https://transparency.facebook.com/)
    - [Apple Transparency Report](https://www.apple.com/legal/transparency/)
  - Look up where the service's headquarters are and think about how that affects its privacy policies.

---

### 😣 I need help now, my systems are under attack!

If you work as part of a civil society group, you can contact:

- Access Now's [Digital Security Helpline](https://www.accessnow.org/help/)
- Front Line Defender's [Emergency Contact](https://www.frontlinedefenders.org/emergency-contact)

If you have a bit more time, you can also apply for a Digital Defenders Partnership [Incident Emergency Grant](https://www.digitaldefenders.org/sections/about-us/emergency-grants/).

---

## 💦❓ Other recommendations

This section is a catch-all for difficult or esoteric practices that do not fall under any of our scenarios above and might not lead to an immediate payoff for the casual user.

#### Emails

- Sign up for a [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) end-to-end encrypted email account.
- Use PGP to secure your emails.

#### File storage & sharing

- Use an end-to-end encrypted cloud storage service (not Dropbox): [Tresorit](https://tresorit.com/), [SpiderOak](https://spideroak.com/).
- Use encrypted external USB/hard drives from companies like [Apricorn](https://www.apricorn.com/).
- If you want to send a file anonymously, use a special sharing service like [OnionShare](https://onionshare.org/).
- Instead of Google Docs or Microsoft Office, use [CryptPad](https://cryptpad.fr) (open-source, end-to-end encrypted).

#### Messaging apps

- WhatsApp additional settings:
  
  - To be 100% end-to-end encrypted, turn off chat backups on WhatsApp (Settings → Chats → Chat backup) and delete your previous backups (instructions for [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).
  - Turn on security notifications on WhatsApp (Settings → Account → Security).
  - Set up a pin number to prevent your account from being moved without your permission (Settings → Account → Two-Step Verification).

#### Hosting/running a website

- Read [this EDRi guide on ethical website development and maintenance](https://edri.org/ethical-web-dev/). Pay special attention to its privacy recommendations.
- Protect your website (from DDOS attacks and other things) by using:
  - [Deflect](https://deflect.ca/) (has [free plan]([https://deflect.ca/nonprofit](https://deflect.ca/nonprofit)) for non-profits).
  - [Cloudflare](https://www.cloudflare.com/) (has [free plan]([https://www.cloudflare.com/galileo/](https://www.cloudflare.com/galileo/) for arts, human rights, civil society, journalism, or democracy organizations).
  - [Project Shield](https://projectshield.withgoogle.com) from Google: only available for news, human rights and election monitoring sites. 
  - [iThemes Security plug-in](https://wordpress.org/plugins/better-wp-security/) for Wordpress.
- Consider switching to a more privacy-oriented hosting service like [Greenhost](https://greenhost.net/) or one of these recommendations from [Gecko & Fly](https://www.geckoandfly.com/32144/anonymous-offshore-web-hosting/) and [PrivacyTools](https://www.privacytools.io/providers/hosting/).
  - Set up a [security.txt](https://securitytxt.org/) so that researchers have a place to disclose security vulnerabilities.

#### Other

- Buy a [YubiKey](http://www.amazon.com/Yubico-Y-072-YubiKey-NEO/dp/B00LX8KZZ8/ref=sr_1_1?ie=UTF8&qid=1421839152&sr=8-1&keywords=yubikey+NEO) USB key to use for two-factor authentication.
- Keep less information/data/photos on your devices – you can't lose what you don't have.
- Don't use smart TVs or smart speakers.
- Search the web anonymously with [DuckDuckGo](http://duckduckgo.com/).
- Access Facebook with more anonymity and/or bypass internet filtering by using [its onion service](https://en.wikipedia.org/wiki/Facebookcorewwwi.onion). 
- If you (or your organization) is really wedded to the Google Suite, consider [Google's Advance Protection program](https://www.wired.com/story/google-advanced-protection/).
- Put your smart cards/passports/phones in a Faraday bag that blocks signals from going in and out. (See [Micah Lee's guide on them](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
- Use a more secure operating system: [Tails](https://ssd.eff.org/en/module/keeping-your-data-safe) (works off of a USB stick) or [Qubes OS](https://www.qubes-os.org/).
- For Android users: Download apps using [F-Droid](https://f-droid.org), an open-source, security-focused app store.
- For US residents: Freeze your credit to prevent bad actors from accessing or mis-using your personal information. See IntelTechniques' [Credit Freeze Guide](https://inteltechniques.com/data/workbook.pdf) for details.

---

**🏆 Oh my, you made it this far.  
🏆 You are a true champ!**

---

## 🧠 Sources

We consulted many sources and drew upon our own experiences in creating this resource. If you're not finding quite what you want here, we recommend checking out these other resources: 

- [The Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/)
- [Citizen Lab's Security Planner](https://securityplanner.org)

---

## 📝 License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 👋🏾 Special thanks

Special thanks to the students at the School of Journalism and Communication at the Chinese University of Hong Kong, and to [our GitHub contributors](https://github.com/narwhalacademy/zebra-crossing/graphs/contributors).
