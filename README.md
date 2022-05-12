# 🦓 Zebra Crossing: an easy-to-use digital safety checklist #

## 🎯 Start here!

### 🤔 Read this guide if you: ###

- Use the internet daily—for work, social media, financial transactions, and anything else.
- Want to secure your digital safety and privacy proactively but aren’t in immediate danger. (If you are, reach out to an expert for a one-on-one consultation.)
- Feel comfortable with technology. For example, you’re confident going into your computer’s or smartphone’s settings section.

### 🗺 Where this guide is from ###

The advice here draws from our experiences living and working in the United States, Canada, and Hong Kong.

Much of what we write applies in other places, but [please let us know](mailto:contact@narwhalacademy.org) if you see any gaps in our coverage.

### 🌱 How to use this guide ###

- **Recommendations are sorted by increasing levels of difficulty.** Start from Level 1 and work your way up!
- **At a minimum, we recommend following [💦 Level 1](#level-1) and [💦 💦  Level 2](#level-2).** They will protect you from the most widely-used (yet simple) attacks. Going through them won’t take more than 1–2 hours, but take breaks as needed.
- **Level 3 is a more involved and requires dedicated time and money.** It may not be 100% necessary, but if you’re worried and have the resources, we recommend going through that list, too. Depending on the amount of digital housekeeping you have to do, it may take anywhere from 1–4 hours.
- **The scenarios shared after Level 3 are for higher-stakes situations.** Scan them to see if any of them apply to you. (Because the stakes are higher, they assume you’ve done everything in Levels 1–3.)
- **This guide is a living document.** Please feel free to submit a pull request or fork your version of this guide [on GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🗣 Read this guide in other languages ###

- [繁體中文 (Traditional Chinese)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-繁體中文.md)
- [Deutsch (German)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Deutsch.md)
- [日本語](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-日本語.md) (Japanese, a work-in-progress)
- [Italiano](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Italiano.md) (Italian, a work-in-progress)
- Looking to contribute another language? [Send us a message](mailto:contact@narwhalacademy.org) to collaborate.

### ☕️ Support this guide ###

- [Buy us a virtual coffee](https://ko-fi.com/narwhalacademy)
- Share this guide with your friends and community!
- [Send your feedback](mailto:contact@narwhalacademy.org) or [contribute to the guide on GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🕒 Last updated ###

- 23 March 2022

---

## Table of contents ##

Use the table of contents below to navigate to the section of the guide you need.

- [🧐 Definitions, Background, and Theory](#definitions)
- [💦 Level 1 recommendations](#level-1)
- [💦💦 Level 2 recommendations](#level-2)
- [💦💦💦 Level 3 recommendations](#level-3)
- [💦❗️ Scenario-based recommendations](#scenario)
- [💦❓ Other recommendations](#other)
- [🧠 Other resources](#resources)
- [📝 License](#license)
- [👋🏾 Special thanks](#thanks)

---

## <a id="definitions"></a> 🧐 Useful terms to learn ##

### 🎯 Threat modeling ###

**Threat modeling** is a process that allows us to identify potential threats to safeguard against them.

When putting together your threat model, ask yourself the following:

- **“What kind of danger am I in?”** Examples may include credit card hacks, corporate espionage, or online harassment/doxxing.
- **“What kind of assets am I protecting?”** Examples may include confidential documents, private photos, or personal messages.

From setting a computer password to locking the doors of our home, it may be second nature to take action to guard our safety.

For situations you’re not as familiar with, consider what’s at stake before dismissing concerns or becoming paranoid.

### 🔗 Weakest link ###

The **weakest link** is where your digital safety is most vulnerable.

For example, if an account’s password recovery links to your email, hackers only need to access your email to get the account.

### 🔡 Encryption levels ###

**Encryption** is the process of converting information to prevent unauthorized access. There are three types of **encryption levels:**

1. **No encryption:** Any third party can intercept the data and read it as-is.
2. **Standard encryption:** Data is encrypted so that third parties cannot read them, but the platform (Google or Facebook, for example) still has access. The platform may hand the data over to courts or government agencies if ordered to do so.
3. **End-to-end encryption:** Only the original sender and receiver can read the data, and not even the platform has access. If courts or other government agencies call, the service provider can’t hand over the messages because they don’t have them.

### 🧩 Metadata ###

**Metadata** is a collection of details about your data. For example, the metadata for a phone call might be the number you called and for how long (but not the call’s contents).

With enough metadata, hackers can piece together a relatively reliable picture of who you are, who you know, and where you’re going.

> 📍 **Note:** Legal protections around metadata tend to be weak or nonexistent.

---

## <a id="level-1"></a> 💦 Level 1 Recommendations ##

### ✅ Do these now ###

- 🔲 [Strengthen passwords](#l1-passwords)
- 🔲 [Double-lock important accounts](#l1-lock)
- 🔲 [Secure your email](#l1-email)
- 🔲 [Encrypt your devices](#l1-encrypt)
- 🔲 [Other considerations](#l1-other)

#### <a id="l1-passwords"></a> Strengthen passwords ####

- **Create passwords with more than 10 characters.** It’s okay to string together non-related words (for example, `plant-truck-nose-frame-lace`—but don’t use this one since it’s public! 😅)
- **Double-check the security questions for your most critical online services.** These services may include email, banking, social media, etc. Make sure the security questions aren’t easy to answer by friends or anyone looking you up on Google or other search engines.
- **Use a different password for every service.** It may be convenient to remember the same password, but that leaves you vulnerable to password leaks. To make this easy, use a password manager ([Wirecutter](https://www.nytimes.com/wirecutter/reviews/best-password-managers/) recommends 💰 [1Password](https://1password.com/) or [BitWarden](https://bitwarden.com/).) to generate, autofill, and store them.
  - **At the very least,** make sure to use a unique password for your critical online services (email, banking, social, cloud storage, etc.).
- **Use a non-common/obvious unlock code for your phone with at least 9 digits.**

#### <a id="l1-lock"></a> Double-lock important accounts ####

- **Set up two-factor authentication.** Also known as 2FA and two-step verification, this adds a second layer of protection on top of a typed password.
  - **2FA usually takes the form of a short code** sent to your phone via a specialized authenticator app or text message (SMS).
- **Use an authenticator app if available.** They're more secure than using SMS to receive your 2FA code. ([Wirecutter](https://www.nytimes.com/wirecutter/reviews/best-two-factor-authentication-app/) recommends [Authy](https://authy.com/)).
- **Turn on cloud-backup for your authenticator app in case you ever lose your phone.** See instructions for [Authy](https://authy.com/features/backup/).

##### We recommend turning on 2FA for your: #####

- **Email service.** See instructions for [Gmail](https://support.google.com/accounts/answer/185839?hl=en), [Protonmail](https://protonmail.com/support/knowledge-base/two-factor-authentication/), or find instructions for your email provider [here](https://twofactorauth.org/#email).
- **Frequently used social media accounts.** See instructions for [Twitter](https://help.twitter.com/en/managing-your-account/two-factor-authentication), [Facebook](https://www.facebook.com/help/148233965247823/), [Instagram](https://help.instagram.com/566810106808145), and [other services](https://2fa.directory/#social).
- **Other online accounts where losing access would be catastrophic.** Look up instructions on [2FA Directory](https://2fa.directory/).

#### <a id="l1-email"></a> Secure your email ####

- **Check the address bar for https://** If you’re using a webmail service, check that you're logging into it using an `https://` URL. If there isn't one available, find a new email provider.
- **Find out if your email service supports backup codes.** Once you turn on 2FA, your email provider may provide single-use backup codes you can use if you lose your phone. [See Gmail instructions](https://support.google.com/accounts/answer/1187538?hl=en).

#### <a id="l1-encrypt"></a> Encrypt your devices ####

> 💡 **Remember:** Encryption is only fully effective when the device is off!

- **Encrypt your computer hard drive:**
  - **Mac:** [See Apple’s instructions](https://support.apple.com/en-us/HT204837).
  - **Windows:** [See Microsoft’s instructions](https://support.microsoft.com/en-us/windows/device-encryption-in-windows-10-ad5dcf4b-dbe0-2331-228f-7925c2a3012d) (use [BitLocker](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) if it’s available).
- **Encrypt your phone storage:**
  - **iOS:** Automatically encrypts.
  - **Android:** Recent versions automatically encrypt. Double-check by going to `Settings → Security → Encryption`.
- **Encrypt your backup hard drives:**
  - **Mac:** If you use Time Machine, [see Apple’s instructions](https://support.apple.com/en-ca/guide/mac-help/mh21241/mac).
  - **Windows:** [See instructions](https://techjury.net/blog/how-to-encrypt-your-hard-drive/).

#### <a id="l1-other"></a> Other considerations ####

- **Set up a pin code for your mobile phone SIM card:**
  - **iPhone:** [See Apple’s instructions](https://support.apple.com/en-hk/HT201529).
  - **Android:** [See Android instructions](https://www.maketecheasier.com/change-sim-pin-android/).
  - **Cell Provider:** Search your phone provider’s website to find out the default SIM password, as this varies from carrier to carrier.
- **Turn on your computer’s firewall:**
  - **Mac:** `System Preferences → Security & Privacy → Firewall`.
  - **Windows:** `Control Panel → System and Security → Windows Firewall`.
- **Turn off your computer’s remote access:**
  - **Mac:** `System Preferences → Sharing → Remote Login, Remote Management`.
  - **Windows:** `Control Panel → System and Security → System: Allow remote access → Don’t Allow Remote connections to this computer`.
- **Set up basic anti-virus software on your computer:**
  - **Mac:** None required; [read Wirecutter’s explanation](https://www.nytimes.com/wirecutter/blog/best-antivirus/).
  - **Windows:** Turn on Microsoft Defender Antivirus. ([See Microsoft’s instructions](https://support.microsoft.com/en-us/windows/stay-protected-with-windows-security-2ae0363d-0ada-c064-8b56-6a39afb6a963)) and [turn on the extra `ransomware protection` feature](https://lifehacker.com/why-you-should-use-windows-defenders-ransomware-prevent-1837311176).
- **Turn off app-specific passwords that bypass two-factor authentication**. [Instructions for Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889).
- **Turn off automatically added invitations in [Google Calendar](https://calendar.google.com/calendar/r/settings)**. [Read this Forbes article to learn why](https://www.forbes.com/sites/daveywinder/2019/06/11/new-security-warning-issued-for-googles-1-5-billion-gmail-and-calendar-users/#3605ff0565e5).
- **Turn on Login Alerts on Facebook**. [Instructions here](https://www.facebook.com/settings?tab=security).
- **Disable macros within Microsoft Office**. [Instructions here](https://support.office.com/en-us/article/enable-or-disable-macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6).
- **Don’t allow USB accessories to control a locked device:**
  - **iOS:** Turn off `Settings → Face ID & Passcode → Allow Access When Locked: USB Accessories`.
  - **Android:** Off by default, only available if `Developer Options` settings are turned on.

### 💪🏽 Develop new habits ###

#### Mind your email ####

- **Watch out for phishing scams.** Always double-check:
  - The `From` email address.
  - The domain that outbound links go to.
- **Don’t open unnecessary email attachments.** Where possible, open or preview them first in an online document reader. Ask colleagues to use a filesharing service (Dropbox, Google Drive, Tresorit, SpiderOak), which tends to be harder to hack.
- **Upload suspicious attachments to [VirusTotal](http://www.virustotal.com) for a check-up.**
  
   > 📍 **Note:** Keep in mind files submitted to VirusTotal are available to security researchers, so don’t submit sensitive information.

#### Check for updates ####

- **Device operating systems:** When you get a notification on your devices to update the operating system, do it as soon as possible.
- **Automatic updates:** Turn on auto-update for your apps if the feature is available. If asked to update an app, do so as soon as possible.
- **Firmware updates:** Check occasionally for firmware updates for your router and other internet-connected devices.

#### Remain vigilant ####

- **Wipe your devices properly before donating or giving them away.** If you’ve encrypted your phones and computers (as suggested earlier), a standard factory reset will work for most use cases.
  - If you want an extra layer of security for your computer hard drives, see [Wired’s guide on this topic](https://www.wired.co.uk/article/securely-wipe-android-iphone-hard-disk).
- **Don’t charge your phone at public charging stations/ports.** They present a risk because hackers might steal your data. Consider using a portable battery to charge your phone instead.

---

**👍 Great job! You’ve covered the basics.**  
**👍 Treat yourself to a cup of tea and a stretch.**  
**👍 Ready for Level 2?**

---

## <a id="level-2"></a> 💦💦 Level 2 recommendations ##

### ✅ Do these now ###

- 🔲 [Strengthen passwords](#l2-privacy)
- 🔲 [Double-lock important accounts](#l2-wifi)
- 🔲 [Secure your email](#l2-other)
- 🔲 [Encrypt your devices](#l2-encrypt)
- 🔲 [Other considerations](#l2-other)

#### <a id="l2-privacy"></a> Enhance your privacy ####

##### On social media #####

- **Review the privacy settings on social networks you frequent.** Check who can see your content, who can comment on it, and who can see your location.
- **Limit Facebook tracking by turning off Off-Facebook Activity.** Follow [these EFF’s instructions](https://www.eff.org/deeplinks/2020/01/how-change-your-facebook-activity-settings).

##### On your phone #####

- **Review which apps on your smartphone have access to your location data.** Turn off access for the apps that don’t need it, and minimize the number of apps tracking your location.
  - **iOS:** `Settings → Privacy → Location Services`
  - **Android:** `Settings → Location → App access to location`
- **On Android, turn off passive Wi-Fi and Bluetooth scanning.**
  - `Settings → Location → Wi-Fi and Bluetooth scanning`
- **Delete third-party keyboards on your phone.** They often share what you type with the software maker.
  - These keyboards are installed as apps on iOS and Android, so take the time to find and delete them.
  - If you need to use a third-party keyboard, make sure it’s an open-source project that others have verified and does not share your data with third parties.

##### In messaging apps #####

- **Review the privacy settings on messaging apps you usually use.** This includes read receipts, time stamps for “last seen,” and whether your phone number and profile picture are public.

##### While browsing the web #####

- **Install [Firefox](https://www.mozilla.org/en-US/firefox/).** Set it as your computer’s default web browser.
- **Install the following protective web browser add-ons.** Make sure they’re on even during private/incognito mode.
  - An ad blocker (such as [uBlock Origin](https://ublockorigin.com/)).
  - A tracker blocker ([Privacy Badger](https://www.eff.org/privacybadger)).
  - [HTTPS Everywhere](https://www.eff.org/https-everywhere).

##### For internet-connected devices #####

- **If you use smart speakers, turn off their recording function.**
  - **Google Home:** go to [Activity Controls](https://myaccount.google.com/activitycontrols/audio) and uncheck `Include audio recordings`.
  - **Amazon Alexa:** [Follow these instructions](https://www.digitaltrends.com/home/how-to-stop-amazon-from-listening-to-your-alexa-recordings/).
- **For an Amazon Ring or Echo, turn off the feature that shares your internet with strangers.**
  - **In the Alexa app:** `Settings → Account Settings → Amazon Sidewalk`

##### In general #####

- **Review what data these big tech companies have on you.** Clear out anything you don't need.
  - **Google:** [My Activity](https://myactivity.google.com)
  - **Amazon:** [Alexa Privacy Settings](https://www.amazon.com/b/?node=19149164011)
  - **Microsoft:** [Account Privacy](https://account.microsoft.com/privacy)

#### <a id="l2-wifi"></a> Set up your home wifi router ####

- **Log into the administration and settings dashboard.** It’s usually accessible by going to `http://192.168.0.1` in your web browser. Otherwise, check your router’s instructions.
- **Update the dashboard login if the password is simple.**
- **Review the devices currently connect to your network.** You may have to explore until you find the `access control`. Make sure you know what every device on the list is.
- **Turn off the following options if you see them.** (Look for them under `advanced settings` or `gateway functions`):
  - UPnP (Universal Plug and Play)
  - WPS (Wi-Fi Protected Setup)
  - Remote Management

####  <a id="l2-other"></a> Other Considerations ####

##### For internet-connected devices #####

- **Set up tracking across your devices.** Tracking will allow you to remotely find and wipe your devices by logging into a website if you ever lose them.
  - **iOS & Mac:** [Instructions for setting up Find My](https://support.apple.com/en-us/HT210400).
  - **Android:** [Instructions for setting up Find My Device](https://support.google.com/android/answer/6160491?hl=en).
  - **Windows:** [Instructions for setting up Find My Device](https://support.microsoft.com/en-us/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316).

##### In your social media and email accounts #####

- **Review the `Third-Party Apps` or `Connected Apps` on your main accounts.** These services might have access to your Facebook data and even permission to make posts automatically there. [Read these instructions for checking for them on Facebook and Gmail](https://www.online-tech-tips.com/computer-tips/check-google-facebook-connected-apps/).

##### For your web browser #####

- **Review your web browser’s extensions, add-ons, and plug-ins.** Delete any that you haven’t used in a while or don’t remember installing.

### 💪🏽 Develop new habits ###

#### Enhance your privacy ####

- **Post less personal information online.** This includes information that can be used to identify/track/scam you (addresses, phone numbers, birthday, etc.).  

  > 💡 **Remember:** almost everything you say online is logged somewhere and that even if your setup is secure, your recipient's setup may not be.

- **Set up a separate account to leave local business reviews.** If you enjoy leaving local business reviews on sites like Google Maps, Yelp, set up a new account under a pen name.
  - This is especially important for Google Maps, where they show the profile picture and full name you use on Gmail.
- **Use WHOIS privacy services for your domains and stick with them.** They’re worth the money, and some domain hosts provide WHOIS privacy at no additional cost.

  > 📍 **Note:** With WHOIS lookup/history tools, it’s challenging to remove your actual address from the logs once you’ve entered it.

#### Watch what you say in online groups ####

**Don’t say anything you’d regret on in a “private” group** on Slack, Discord, Facebook, WhatsApp group chat, Telegram channel, or any “private” online forum.

Here’s why:

1. **Any member can leak all of the data.**
2. **Administrators usually have access to everything within the group,** including deleted messages and private direct messages between two people.
3. **What you say can be traced back to your account's phone number or email.** Even if you're not using your real name or photo.
   - To prevent this in Telegram, go into `Settings → Privacy and Security → Phone Number`, and then set:
     - `Who can see my phone number` to `Nobody`.
     - `Who can find me by my number` to `My Contacts`.

#### Other ####

- **When downloading a new mobile app, double-check to confirm it’s the right one.** Many fake apps trick people by using a slightly modified name or icon of an existing, popular app.
- **Regularly check the installed apps on your phone.** Delete the ones you’re no longer using.
- **Need to send someone a password? Split it in half and send it via two different channels.** For example, send half of the password through email and the other half via a voice call.
- **Place a sticker (or webcam cover) over your laptop’s front-facing camera.**
- **Don’t use Google/Twitter/Facebook to sign up or log into other services.** Each service should have its account.

---

**🎉 Congratulations!  
🎉 You’re now reasonably secure!  
🎉 (Which is more than most people) :)  
🎉 Take the rest of the day off, and  
🎉 come back when you’re ready for Level 3.**

---

## <a id="level-3"></a> 💦💦💦 Level 3 recommendations ##

### ✅ Do these when you can ###

- 🔲 [Lock up sensitive files](#l3-files)
- 🔲 [Upgrade your gear 💰](#l3-gear)
- 🔲 [Revisit old passwords](#l3-passwords)
- 🔲 [Use end-to-end encrypted apps](#l3-apps)

#### <a id="l3-files"></a> Lock up sensitive files ####

- **Identify files you don’t want others to access.** That may include private photos, passport documents, and more.
- **Create an encrypted, password-protected vault for your files.** We recommend [Cryptomator](https://cryptomator.org/) or [Veracrypt](https://www.veracrypt.fr/en/Home.html).
- **Set up this vault on your computer *and* your phone.**
- **Move your files into the secure vault.** Make sure copies aren’t hanging around in an old folder or on your phone.

#### <a id="l3-gear"></a> Upgrade your gear 💰 ####

- **Use a paid VPN service when on public networks.** For example, while using a café’s free Wi-Fi.
- **Use a paid VPN service at home if you don’t want your service provider to know what you’re doing.**

  > 📍 **Note:** Free VPN services are inadequate because operators don’t have enough incentive to protect you and your data.
  >
  > [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/) both recommend [Mullvad](https://mullvad.net) and [IVPN](https://www.ivpn.net/).

- **Buy a privacy screen for your laptop and phone.** These screens prevent onlookers from seeing your screen—see [this 3M example](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/All-3M-Products/Privacy-Screen-Protectors/Privacy-Products/Black-Privacy/).
- **Buy a harder-to-hack mobile phone.** Consider an iPhone or an Android phone that implements a “pure” Google version of Android.

#### <a id="l3-passwords"></a> Revisit old passwords ####

- **Store all online service passwords in a password manager.** If you have the right browser add-on/plugin installed, it will capture all the relevant details during the login or sign-up process.
- **Use your password manager’s analysis feature.** You’ll see which accounts/services have weak passwords. Update the passwords of those that might have any personal information about you or that you would hate to lose.

#### <a id="l3-apps"></a> Use end-to-end encrypted apps ####

##### For secure messaging #####

- **Sign up and use a secure mobile messaging app.**
  - [Signal](https://signal.org/): Sign up with a phone number.
  - [Wire (Personal)](https://wire.com/en/products/personal-secure-messenger/): Sign up with an email address.
- **Consider letting messages expire after 1 week.**
  - **Signal:** Go to `Settings → Privacy →  Disappearing Messages → Default Timer for New Chats`.
  - **Wire:** No app-wide setting exists. You have to set it up for each conversation by tapping/clicking the timer icon ⏱.

##### For one-on-one or small group voice/video calls #####

- **Continue using [Signal](https://signal.org/), or [Wire](https://wire.com/en/products/personal-secure-messenger/).**

  > 📍 **Note:** Privacy is hard to maintain in large group calls as they often become quasi-public events.
  >
  > If you need privacy, see the Freedom of the Press chart, [Which video conferencing tool is right for the job?](https://freedom.press/training/blog/videoconferencing-tools/)

##### For online file-sharing and backup #####

- **Secure options include**:
  - [Tresorit](https://tresorit.com/) 💰
  - [Spideroak One](https://spideroak.com/one/) 💰

  > 💡 **Remember:** files on Google Drive and iCloud are not end-to-end encrypted).

---

**😲 Wow, you completed all three levels!**  
**😲 Well done! Now quickly look below**  
**😲 to see if any apply to you.**  

---

## <a id="scenarios"></a> 💦❗️ Scenario-based recommendations ##

- [✊🏾 Attending a protest](#scenario-protest)
- [🛫 Crossing an international border](#scenario-border)
- [👩🏿‍💻 Hosting a public event on a video calling platform (e.g. Zoom)](#scenario-event)
- [🕵🏼‍♂️ Online harassment & doxxing](#scenario-doxxing)
- [👀 Remove information about you off of the internet](#scenario-removal)
- [🍆 Sexting & non-consensual image sharing](#scenario-sexting)
- [🤐 Traveling to a place with weak data protection laws or internet censorship](#scenario-travel)
- [📰 “I’m a journalist working on a sensitive topic”](#scenario-journalist)
- [👤 “I don't want to give out my personal information for *x*”](#scenario-personal)
- [👾 “I think my computer has been hacked?”](#scenario-hack)
- [💔 “I think my partner is spying on me through my phone (stalkerware)”](#scenario-stalking)
- [😣 “I need help now, my systems are under attack!”](#scenario-help-now)
- [😭 “Somebody took my phone/computer!”](#scenario-lost-device)

---

### <a id="scenario-protest"></a> ✊🏾 Attending a protest ###

#### Create an emergency back-up plan ####

- **Draft a message to a trusted friend before or legal hotline.** Prepare to hit send if arrested at the protest or if there’s an emergency.
- **Write down the phone number of the trusted friend/hotline on your arm with a permanent marker.**
- **Bring a spare battery or mobile charger for your phone.**
- **If you use your fingerprint or face to unlock your phone, turn it off before the protest.** In some jurisdictions, [officers can compel you to provide your fingerprint but not your passcode](http://www.theatlantic.com/technology/archive/2016/05/iphone-fingerprint-search-warrant/480861/).
- **Power off your phone if you believe you’ll be arrested.** Encryption works better when devices are off.
- **Consider using a burner phone with a burner SIM card.** [See the Intercept’s instructions for this in the U.S.](https://theintercept.com/2020/06/15/protest-tech-safety-burner-phone/).

#### Store less, share less ####

- **Keep very little sensitive personal information on your phone.** Delete any photos, chat logs, and notes that can be used against you.
- **Use a messaging app that lets you create disappearing messages (e.g., [Signal](https://signal.org/)).** Turn on the timer when discussing the protest.
- **Don’t take photos or videos where people’s faces are visible.** Taking a photo of people’s backs is okay.

  > 📍 **Note:** The one exception is if you’re filming a video of a conflict or arrest where documentation is critical.

- Wear a face mask so you’re not easily caught or identified on camera.
- When sharing photos/videos, blur the faces of any protesters.
  - **Phone:** [Signal’s blur tool](https://signal.org/blog/blur-tools/) for photos.
  - **Computer:**
    - Everest Pipkin’s [Image Scrubber](https://everestpipkin.github.io/image-scrubber/) for photos.
    - YouTube’s [blur faces tool](https://youtube-eng.googleblog.com/2017/08/blur-select-faces-with-updated-blur.html) for videos.

  > 📍 **Note:** If need be, erase the location metadata on any photos/videos before posting using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).

#### Minimize location tracking #####

- **Turn off location history**
  - **iOS:** `Settings → Privacy → Location Services → System Services → Significant Locations`.
  - **Android:** `Settings → Privacy → Advanced → Google Location History →  Activity Controls: Location History.`
  - **Google Maps:** `Settings → Maps history → Web & App Activity`.
- **Delete past location history**
  - **iOS:** `Settings → Privacy → Location Services → System Services → Significant Locations → Clear History`.
  - **Android:** [See instructions](https://support.google.com/accounts/answer/3118687?hl=en#delete).
  - **Google Maps:** [See instructions](https://support.google.com/maps/answer/3137804?hl=en).
- **Consider turning off all location services temporarily**
  - **iPhone:** `Settings → Privacy → Location Services → Location Services: Off`.
  - **Android:** `Settings → Location → Use location: Off`.

#### Other ####

- **Double-check the privacy settings in your messaging apps.**
- **Turn off message previews in your notifications.**
  - **iOS:** `Settings → Notifications → Show Previews: When Unlocked`.
  - **Android:** `Settings → Apps & notifications → Notifications → Notifications on lock screen → Sensitive notifications: Off`.
- **Make voice calls through end-to-end encrypted apps like [Signal](https://signal.org/).**

---

### <a id="scenario-border"></a> 🛫 Crossing an international border ###

- **Turn off your devices.**
  - Storage/hard drives are only encrypted when off, **not** when they’re just in sleep mode.
  - This will also ensure that your mobile devices require a pin when turned on, which is protected by freedom of speech laws in some jurisdictions.
- **Store less information on your devices.** They can’t take what you don’t have if your devices are seized.
- **Be mindful of what stickers you put on your devices.** A border agent could mistake them for something suspicious.
- **Notify your people about your flight number and arrival time.** Regularly check in with one of them at points in your journey. Have them contact a lawyer/relevant organization if you do not show up.

#### For extreme situations ####

> 📍 **Note:** Some of these practices might raise suspicions and backfire.

- **Set up alternate photo albums, email addresses, and social media accounts full of harmless content.**
- **“Forget” half of your password.** Password lock your device/account so that only a trusted friend has the second half of the password.
- **Log out of all important accounts.** Or leave your devices at home.
- **For U.S. travel, consider filing for attorney privileges.** See [BoingBoing’s note](http://boingboing.net/2017/02/12/how-to-cross-a-us-or-other-b.html) about filing for attorney privileges at the U.S. border.

---

### <a id="scenario-event"></a> 👩🏿‍💻 Hosting a public event on a video calling platform (Zoom, Google Meet, etc.) ###

- **Set a meeting password.** The password will prevent random people from wandering in via a meeting ID generator. Consider setting up an RSVP system so that you don’t have to give out the meeting link and password publicly.
- **Familiarize yourself with the platform’s settings.** Minimize the amount of control (such as screen-sharing) that non-hosts have. Check these  [settings on Zoom](https://blog.zoom.us/wordpress/2020/03/20/keep-uninvited-guests-out-of-your-zoom-event/).
- **Create a plan of action for what you would do if a malicious troll gains access to your call.**
- **Don’t say anything you wouldn’t say in public.** Encourage your attendees to do the same. Most commercial platforms access your audio/video data and mine your metadata to create consumer profiles.

---

### <a id="scenario-doxxing"></a> 🕵🏼‍♂️ Online harassment & doxxing ###

Harassment and doxxing can get very specific and complicated based on the attacker, what you do, the overall cultural context, etc.

While we have some general suggestions below, we implore you to consider whether your situation has escalated to the point you need to seek professional, one-on-one help.

#### Build and use your support systems ####

##### Connect with a trusted friend #####

Do not force yourself into a corner by going at this alone!

- **Baseline:** Ask a trusted friend to hold space for you and your situation. They can be your sounding board while helping you analyze how grave the threat is.
- **Preferred:** Ask a trusted friend to help you investigate, record, report and block harassers. Check out Take Back The Tech’s [Hey Friend!](https://www.takebackthetech.net/know-more/heyfriend) guide for more details.

  > 📍 **Note:** In some cases, it may be healthier to hand your phone/social media/accounts over to your trusted friend to experience moments of mental relief.

##### Connect with communities #####

- **Reach out to online communities you’re an active member of and ask for help.** See PEN America’s article on article on [Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/deploying-supportive-cyber-communities/).
- **If no one is available right now, Heartmob has a list of [supportive organizations](https://iheartmob.org/resources/supportive_organizations)**, many of which have 24/7 hotlines.

#### Search for public information about yourself (dox yourself) ####

**Reach out to your trusted friend—they can help you do the following:**

- **Search for your name, nicknames, usernames, and address on Google, Bing, and other popular search engines.** Try adding `filetype:pdf` to your search query to catch any CVs or documents you might have missed.
- **Run an image search on your most-used profile pictures on the same search engines.**
- **Search for your name, nicknames, and usernames on any social media platforms you regularly use.** Check social media platforms that are popular where you’re located, too.
- **Need additional support?** For more information, see Access Now Digital Security Helpline’s [Self-Doxing Guide](https://guides.accessnow.org/self-doxing.html).

#### Monitor updates & collect evidence ####

- **Monitor your name/username.**
  - **[Talkwalker](https://www.talkwalker.com/alerts)**
  - **[Google Alerts](https://www.google.com/alerts)**
  - **[Mention](https://mention.com)** 💰
- **Monitor and archive webpages that mention you using [ChangeTower](https://changetower.com/).**
- **Log (date, time, description, screenshot, URL) incidents in whatever program/app is most accessible for you.** If there’s a lot of phone-only content, use the [Hunchly](https://hunch.ly/) mobile app.
- **If future legal action is likely, pay [Page Vault](https://www.page-vault.com) to capture a snapshot of a website.** Ask a lawyer to file an [evidence preservation request](https://onlinesos.org/blog/evidence-preservation-i-e-litigation-hold-request) with the relevant online platform.

#### Delete online information about you ####

- **Read the scenario scenario:** [👀 Remove information about you off of the internet](#scenario-removal)

#### Ignore/reply to/report/block your harassers ####

Together with your trusted friend and the log of receipts, decide on your course of action (these aren’t mutually exclusive).

- **Ignore:** Sometimes, harassers will become bored and walk away if they don’t get attention.
- **De-escalate:** In some contexts, you can defuse the situation with some calm words before it worsens.
- **Mute on social media:** This lets you have peace of mind and not have your harasser’s updates suddenly pop up on social media. (You might still want to check what they’re saying proactively.)
- **Block on social media:** Sends a strong signal to your harasser. They won’t be able to see your posts or message you. They will, however, notice that you blocked them and might interpret it as a sign of escalation.
- **Go public:** Sometimes, shaming a harasser publicly or rallying people to your support will make them disappear. However, this has a high risk of escalating the situation and drawing more attention to it.
- **Report:** Report the harasser to the relevant online platform to have their account frozen or deleted. You may also report the incident to your local law enforcement if it makes sense.

  - **If you decide to report:**
    - **File a report with a social media company and ask at least 10 friends to do the same.** Have 1–2 people file a copyright infringement claim if it makes sense.
      - **Review the relevant reporting links for the following services:**
        - [Facebook](https://www.facebook.com/help/www/181495968648557)
        - [Instagram](https://help.instagram.com/192435014247952)
        - [Twitter](https://help.twitter.com/en/forms/safety-and-sensitive-content)
        - [Snapchat](https://support.snapchat.com/en-US/a/report-abuse-in-app)
    - **If there’s harassment material on a website, you file a report with the website’s web hosting service and domain registrar.** You might be able to find out who these companies are by performing a [WHOIS lookup](https://lookup.icann.org/) on the website domain.
  - **If you contact law enforcement:**
    - Beware that not all officers are used to dealing with online harassment threats.
    - If you believe you might become a target of swatting (where people prank call the cops on you), let them know. Send them an article about swatting if it’s a new idea to them.

#### Specific social media platform tools and features ####

##### Facebook #####

Facebook has a few features to control your interactions, but ultimately relies on you setting limits on who can see and comment on your posts and profile.

- **[Ignore Messages](https://www.facebook.com/help/messenger-app/1245152242249842)** within Facebook Messenger to move the current and future messages to the `Message Requests` section
- **[Privacy Checkup](https://www.facebook.com/privacy/checkup)** within Facebook includes a section on `Who can see what you share` that walks you the visibiity of your profile and posts.

##### Instagram #####

Instagram has a set of nuanced features within its mobile app to filter and fine-tune social interactions on its platform.

- **[Restrict](https://help.instagram.com/2638385956221960/)** an account, which means the other person can’t see when you’re online, whether you’ve read their messages, and hides their comments.
- **[Hide](https://help.instagram.com/1177797265575168/)** your stories from a specific account.
- **[Hidden Words](https://help.instagram.com/700284123459336)** filters out messages and comments with words that Instagram deems offensive. You can also set up a custom words list.
- **[Limit](https://help.instagram.com/4106887762741654)** comments and messages from recent followers and accounts that aren’t following you.

##### Twitter #####

Twitter works with some pretty handy third-party tools and has a few features of its own.

- **Filter unwanted mentions and replies** and/or archive them to process later with the help of a friend using [Block Party](https://www.blockpartyapp.com/).
- **Block previously-identified offenders using [Block Together](https://theblockbot.com/).** Ask around in your communities for shared block lists.
- **Block troll bots using [Bot Sentinel](https://botsentinel.com).**
- **Use [Red Block](https://github.com/gaeulbyul/RedBlock) to reduce dogpiling.** Red Block blocks all followers of a specific profile.
- **See what lists you’ve been added to by going to `Profile → Lists → ··· → Lists` you’re on.** If you see a suspicious list or list owner, tap the three dots on the top right to report the list and leave the list by blocking the creator.
- **Control who can reply to your tweets** by tapping `Everyone can reply` and restricting it to `People you follow` or `Only people you mention`.

#### Notify other parties ####

- **Tell your close contacts, family, and employer what’s going on.** Get ahead of the situation by making talking points together so that they know how to respond if internet strangers or the press contacts them.
- **If the situation escalates,** find and notify someone in your community nearby with crisis experience for protection and support.

#### Show yourself some kindness ####

- **Don’t worry if you’re not able to keep up with your regular workday routine.**
- **Call in friends to help share a meal, take a break, or watch your pet(s) (if you have any) for a few days.**
- **Do your best to eat and shower regularly.**
- **Engage in movement, no matter how small.** That could be a walk or even stretching. Pick something you enjoy, and that eases your mind.
- **Prepare a box of comforts beforehand.** Include things you like to see, touch, taste, and listen to.
- **If the incident is traumatizing, refer to it using a nickname.**

#### Bonus tips for journalists and researchers ####

- **Make yourself a more challenging target.** Consider making your social media accounts private (or temporarily deleting them) for 48 hours surrounding a major, new release.
- **Remember, you did nothing wrong.** Ignorant employers or colleagues may not be supportive and start seeing you as a liability—they’re wrong.
- **Don’t make more noise about yourself.** Don’t livetweet your situation, don’t quit your job suddenly, and don’t talk to media outlets who will twist your words.
  - If necessary, prepare a formal written statement or reply with the help of people who have experience dealing with the media.
- **If the noise doesn’t stop, flood the airwaves with positive stories about yourself.** Ask people within your professional community to write positive articles or social media posts about you and your work.
- **Read [Lyz Lenz’s conversation with Talia Lavin](https://lyz.substack.com/p/when-the-mob-comes) about their experiences.**

#### Check out these additional resources ####

- Kat Fukui’s [Guide for handling online harassment](https://www.tinykat.cafe/guide-for-handling-online-harassment)
- OnlineSOS’ [Action Center](https://onlinesos.org/action-center/category:identify)
- PEN America’s [Online Harassment Field Manual](https://onlineharassmentfieldmanual.pen.org/)
- Feminist Frequency’s [Speak Up & Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/)
- TrollBusters’ [What to Do? Where to Go? Infographic](https://yoursosteam.wordpress.com/what-to-do-infographic/)

---


### <a id="scenario-removal"></a> 👀 Remove information about you off of the internet ###

If you’re about to become a public figure or are experiencing harassment, consider some suggestions below.

#### Clean up your social media presences ####

You might not need to delete your entire account, but consider deleting (or making private) old posts or posts that reveal too much about where you live, where you go, and who you’re with.

##### Facebook #####

- **See what your public profile looks like, and remove/restrict things as you see fit.**
  - **Desktop:** go to your profile and click the 👁 button next to the right of the `Edit Profile` button.
  - **Mobile:** go to your profile, tap the three dots on the right of `Add Story` and tap `View As`.
- **Make it so only friends can see your past posts.**
  - **Desktop:** Go to `Settings → Privacy → Limit Past Posts`.
  - **Mobile:** Go to `Settings & Privacy → Settings → Privacy Settings → Limit who can see past posts`.
- **Consider bulk deleting past posts.** [See this article in PC Magazine](https://www.pcmag.com/how-to/how-to-quickly-delete-old-facebook-posts).

##### WhatsApp #####

- Swipe to delete individual conversations.
- Delete chat content but keep the chat groups: `Settings → Chats → Clear All Chats`.
- Delete all chats, including the chat groups: `Settings → Chats → Delete All Chats`.
- Turn off chat backups on WhatsApp: `Settings → Chats → Chat backup` and delete your previous backups.
  - **[iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad)**
  - **[Android](https://faq.whatsapp.com/en/android/30030306)**

##### Instagram #####

- **Look through your profile and manually delete posts.** Tap the three dots in the upper-right corner of a photo.
- **If you need to, bulk-delete posts using [third-party tools](https://upleap.com/blog/how-to-delete-an-instagram-post/).**

##### Twitter #####

- **Use a third-party service to filter for tweets you want to save and bulk-delete the rest.** We recommend:
  - [Semiphemeral](https://semiphemeral.com) (free + open source, but beta)
  - [TweetDelete](https://tweetdelete.net/) (free + paid 💰 options)
  - [Twitter Archive Eraser](https://martani.github.io/Twitter-Archive-Eraser/) (free + paid 💰 options)
- **Alternately, manually locate and delete individual posts using [Twitter’s Advanced search](https://twitter.com/search-advanced).**

##### LinkedIn #####

- **Modify your profile’s [visibility settings](https://www.linkedin.com/psettings/data-visibility).**

##### Reddit and other forums #####

- There’s often no easy solution. Sometimes you have to delete your entire account.
- **In the case of Reddit, you have to [use third-party scripts](https://social.techjunkie.com/how-to-delete-all-reddit-posts/)** because deleting your account still leaves your posts up.

#### Delete your social media accounts...temporarily #####

Many social media companies let you restore your deleted account after a specific period. This can be useful if you want to hide for a while and wait for an event to pass.

- **Facebook** [Read the instructions](https://www.facebook.com/help/224562897555674) to deactivate or delete your account temporarily. You have 30 days after deactivation to reverse it.
- **Instagram** [Read the instructions](https://help.instagram.com/370452623149242/) to disable your account temporarily, but deleting it seems permanent.
- **Twitter** [Read the instructions](https://help.twitter.com/en/managing-your-account/how-to-deactivate-twitter-account) to deactivate your account. It will be permanently deleted if you don’t log in after 30 days.
- **Snapchat** [Read the instructions](https://support.snapchat.com/en-US/a/delete-my-account1) to delete your account. It will be permanently deleted if you don’t log in after 30 days.

#### Remove your information from other people’s accounts or websites ####

> 💡 **Remember:** Information removal requests takes time to process and often require repeated attempts.

- Ask [Google](https://support.google.com/websearch/troubleshooter/3111061?hl=en) and [Bing](https://www.microsoft.com/en-ca/concern/bing) and Bing to remove search results pointing to pages with your personal information on them.
- **Remove any local business reviews you’ve left on Google Maps, Yelp, etc.** They might point to your home or frequently visited places.
- **Follow the Cyber Civil Rights Initiative’s [guide to get policy-violating posts/media removed from social networks](https://www.cybercivilrights.org/online-removal).**
- **If you’re willing to pay 💰,** [Yael Grauer](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List#paid-options) recommends using [DeleteMe](https://joindeleteme.com/) and [Kanary](https://www.thekanary.com/) to remove your information from English-language public and paywalled sites.
- **If you want to do it yourself,** check out Yael Grauer’s [Big Ass Data Broker Opt-Out List](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List). (To be 100% thorough, use this on top of paid services.)

#### Remove articles and press about you online ####

> 📍 **Note:** The larger the publication, the harder it is to persuade them.

- **Think of this as risk reduction, not total elimination.** It will be impossible to have everything removed.
- **Contact the editor or your previous contact.** Explain your situation honestly and hope for a sympathetic editor/writer.
  - **If you think the editor/writer will not respond well,** it may be better not to reach out—doing so may draw more attention to your situation.
- **For older articles,** it may help to remind them that the article is still easily accessible on search engines.

#### Obscure your personal information ####

- **See the scenario:** [👤 “I don't want to give out my personal information for x”](#scenario-personal).
- **Get a P.O. box at a post office or use [Traveling Mailbox](https://travelingmailbox.com/) (U.S. only) to hide your home address.**
- **Delete old accounts to eliminate traces of personal information on the internet.** Use the [JustDeleteMe](https://justdeleteme.xyz/) directory to accelerate this process.

---

### <a id="scenario-sexting"></a> 🍆 Sexting & non-consensual image sharing ###

- See [The Motherboard Guide to Sexting Securely](https://motherboard.vice.com/en_us/article/mb3nd4/how-to-sext-securely-safely-what-apps-to-use-sexting).

---

### <a id="scenario-travel"></a> 🤐 Traveling to a place with weak data protection laws or internet censorship ###

- **Be aware that phone companies might share your location and personal info with others without your permission.**
- **Setup a VPN beforehand to:**
  - Access services uninterrupted
  - Minimize the amount of data collected about you.
- **Avoid VPNs that are free or have opaque ownership.** [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/) both recommend 💰 [Mullvad](https://mullvad.net) and 💰 [IVPN](https://www.ivpn.net/).
- **Consider traveling with a burner phone while leaving your laptop at home.** This will be especially useful if you need to install new/untested software for work that might violate data privacy policies.
- **Re-evaluate which online services are safe to use.** See how often your favorite service hands over its data by looking up their transparency reports:
  - [Google Transparency Report: Request for user information](https://transparencyreport.google.com/user-data/overview)
  - [Facebook Transparency Report: Government Requests for User Data](https://transparency.facebook.com/)
  - [Twitter Transparency Center: Information Requests](https://transparency.twitter.com/en/reports/information-requests.html)
  - [Apple Transparency Report](https://www.apple.com/legal/transparency/)

  > 📍 **Note:** Look up the location of the service’s headquarters and think about how that impacts its privacy policies.

---

### <a id="scenario-journalist"></a> 📰 “I’m a journalist working on a sensitive topic” ###

Below are the basics all journalists should consider. If you’re working on a sensitive story or in a susceptible region (e.g., a whistleblower story), you and your team should get a tailored training session from an expert.

#### Be prepared ####

- **To remotely wipe the contents of your devices.** See scenario above titled [😭 “Somebody took my phone/computer!”](#scenario-lost-device).
- **To be on the receiving end of an email phishing campaign (as journalist emails are usually more public than others).**

#### Protect your sources ####

- **Use email as little as possible.** Even end-to-end encrypted email [leaves a trail of metadata](https://freedom.press/training/blog/how-reporters-emails-get-got-case-studies-legal-request-hacking/).
- **Use an end-to-end encrypted messaging app that doesn’t store metadata like [Signal](https://www.signal.org/) to exchange messages.** Don’t use Twitter DMs!
- **For voice/video calls, use an end-to-end encrypted app like [Signal](https://www.signal.org/) or [Wire](https://wire.com/en/products/personal-secure-messenger/).**
- **Use the security features in Signal and WhatsApp.** See Martin Shelton’s articles on [Locking Down Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) and [Upgrading WhatsApp security](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3).
- **For document transfers, have your organization set up [SecureDrop](https://securedrop.org/).** Failing that, encourage people to use [OnionShare](https://onionshare.org/).
- **Blur faces from photos and videos.** Read the `Store less, share less` section in the [✊🏾 Attending a protest](#scenario-protest) scenario.
- **See Ted Han and Quinn Norton’s [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/).**
- **See Martin Shelton’s [Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/).**

#### Protect yourself ####

- **Use a secondary phone number on Signal to talk to your sources.**
- **Create a public tip line using your secondary phone number.** Follow Yael Grauer’s guide: [How To Use Signal Without Giving Out Your Phone Number Using a Chromebook and an Old Phone](https://blog.yaelwrites.com/how-to-use-signal-without-giving-out-your-phone-number-using-a-chromebook-and-an-old-phone/).
- **Review the [🛫 Crossing an international border](#scenario-border) scenario if you’re traveling.**
- **If you’re covering a protest,** review the [✊🏾 Attending a protest](#scenario-protest) scenario and decide which parts apply to you (if you have special journalist rights/protections where you’re working).
- **Use a VPN if you’re browsing the internet at the office.** For example, website administrators can see that you’re visiting from the *New York Times* network.

#### Protect your data ####

> 📍 **Note:** [Courts can compel companies like Google to hand over all of your data](https://medium.com/@tinfoilpress/newsrooms-lets-talk-about-g-suite-1672a36eb235).

- **Use an email and storage provider not owned by an organization you’re reporting on.**
- **Move all of your work onto end-to-end encrypted platforms.** Use [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) for email and [CryptPad](cryptpad.fr/) for docs/spreadsheets.
- **Store sensitive data in a password-protected cloud or external storage device as much as possible.** Read the `Lock up sensitive files` section in [💦💦💦 Level 3 recommendations](#level-3).
- **Permanently erase sensitive files from your computer.**
  - **Mac:** [File Shredder for Mac](https://apps.apple.com/us/app/fileshredder/id418094085?mt=12)
  - **Windows:** [Eraser for Windows](https://eraser.heidi.ie/)

#### For more information ####

- **In an unconventional region, jurisdiction, or situation?** See Grégoire Pouget of Nothing2Hide’s [Digital Security for Journalists Requires an Adaptable Toolkit](https://gijn.org/2019/07/16/digital-security-for-journalists-requires-an-adaptable-toolkit/) guide.
- **Running a newsroom?** See Ontheline Newsrooms’ see [Measures for Newsrooms and Journalists to Address Online Harassment](https://newsrooms-ontheline.ipi.media/).

---

### <a id="scenario-personal"></a> 👤 “I don't want to give out my personal information for *x*” ###

#### Messaging apps ####

For messaging apps using phone numbers as the primary identifier or username (e.g., Signal, WhatsApp, Telegram), get a secondary number from:

- **💰 [Hushed:](https://hushed.com)** Best for U.S., Canada, and U.K. numbers
- **[Burner:](https://www.burnerapp.com/)** Best for U.S. and Canada numbers
- **[Skype:](https://secure.skype.com/en/skype-number)** Supports numbers from multiple countries
- **🆓 [TextNow:](https://www.textnow.com/)** Ad-supported U.S. and Canada numbers
- **[Google Voice:](https://voice.google.com/about)** Free number only available in the U.S.
- **💰 A local phone company:** Get a prepaid or cheap SIM card plan

> 📍 **Note:**
>
> - If you lose/unsubscribe to your secondary phone number, other people can buy it and impersonate you.
> - Courts can still compel companies to hand over your information in most cases.

#### Sites and services ####

For sites and services that use email as the primary identifier/username, get a new email account or an email alias that forwards to your main account from:

- 🆓 **[SimpleLogin:](https://simplelogin.io)** Based in E.U.
- 🆓 **[AnonAddy:](https://anonaddy.com)** Based in U.K./E.U.

#### Banking and Finances ####

**Mask what you’ve bought from your bank using a virtual credit card from [Privacy](https://privacy.com/).** U.S.-only and the feature is only available for Pro accounts 💰.

#### Create an untraceable online alias for true anonymity ####

- **If you’re a public figure, consider working under a persistent pseudonym or collective identity.** The [Tactical Tech manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online) has more details on why.
- **Learn to operate safely online under a pseudonym.** Follow this guide on [creating untraceable online accounts and protecting your real identity](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46).

---

### <a id="scenario-hack"></a> 👾 “I think my computer has been hacked?” ###

- **Download an application that helps you analyze the data streams going in and out of your devices.**
  - **Mac:**
    - [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html)
    - [Charles Proxy](https://www.charlesproxy.com/)
  - **Windows:**
    - [Glasswire](https://www.glasswire.com/)
    - [Charles Proxy](https://www.charlesproxy.com/)
  - **Linux:**
    - [Charles Proxy](https://www.charlesproxy.com/)
  - **iOS:**
    - [Guardian Firewall](https://guardianapp.com)
  - **Android:**
    - [Glasswire](https://www.glasswire.com/)
- **Run Activity Monitor on Mac or Process Explorer on Windows** to look at what processes/applications are running. Google any suspicious names.
- **Log in to critical online accounts and check for any suspicious logins.** See [this Motherboard guide for details](https://motherboard.vice.com/en_us/article/bjeznz/how-do-you-know-when-youve-been-hacked-gmail-facebook).
- **Set up a spare Android phone using [Haven](https://guardianproject.github.io/haven/) as a room monitor to detect unwanted intrusions.**

---

### <a id="scenario-stalking"></a> 💔 “I think my partner is spying on me through my phone (stalkerware)” ###

#### If you’re not sure and things haven’t escalated between you and your partner ####

- **Keep a hidden, pen-and-paper log of suspicious incidents.**
- **Make sure your partner is not getting information from previously shared accounts.** This includes calendars, too.
- **Turn off [location share on within Google Maps](https://support.google.com/maps/answer/7326816?co=GENIE.Platform%3DAndroid&hl=en).**
- **Review and redo the items in Levels 1–3 of this guide.** Reset your passwords, check your privacy/data sharing permissions, and look up any apps you don’t recognize on your computer and phone.
- **Keep an eye out for other signs.** Examples may include your phone battery doesn’t last very long, your laptop internet connection is slow, you get emails/prompts about someone else logging into an account, or your partner suddenly borrowed your phone for a long time the other day.
- **Don’t delete suspicious apps immediately.** You may need to keep them as evidence. Plus, deletion may also cause the situation with your partner to escalate.

#### If you’re pretty sure they’re spying on you and you’re scared ####

Don’t go through this alone—seek help.

- **Find a public or friend’s computer/phone to contact the organizations in [this global resource list compiled by the Coalition Against Stalkerware](https://stopstalkerware.org/get-help/resources/).** Some of them can even help you collect evidence and remove stalkerware safely.
- **Reach out to a trusted friend (through a public device/line).** Ask them to hold space for you and your situation. They can be your sounding board while helping you analyze how grave the threat is.
- **Keep digital and printed records of relevant texts, emails, calls, etc.** See the NNEDV’s [guide on documenting/saving evidence](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence).
- **When you no longer need evidence, remove the suspicious apps/stalkerware yourself by performing a factory reset on your computer/phone.** Buying a brand new device is even safer, of course.
  - **Remember to reinstall apps and import data manually,** lest you restore a backup with stalkerware in it.

#### Additional resources ####

- **Consumer Reports’** [Shut Stalkers Out of Your Tech](https://www.consumerreports.org/digital-security/shut-stalkers-out-of-your-tech/)
- **Wirecutter’s** [Protect Your Devices Against Domestic Abusers](https://thewirecutter.com/blog/domestic-abusers-can-control-your-devices-heres-how-to-fight-back/)
- **Are you an iOS user?** See [Apple’s checklist](https://support.apple.com/en-us/HT212021) and download the document at the bottom called `Device and Data Access when Personal Safety is At Risk`.

---

### <a id="scenario-attack"></a> 😣 “I need help now, my systems are under attack!” ###

#### If you work as part of a civil society group ####

- Access Now’s [Digital Security Helpline](https://www.accessnow.org/help/)
- Front Line Defender’s [Emergency Contact](https://www.frontlinedefenders.org/emergency-contact)
- SMEX’s [Digital Safety Helpdesk](https://smex.org/helpdesk/) for people in Lebanon and other Arabic-speaking countries
- [Vita Activa](https://vita-activa.org/) for Spanish speakers.
- If you have a bit more time, apply for a Digital Defenders Partnership [Incident Emergency Grant](https://www.digitaldefenders.org/funding/incident-emergency-funding/)

**Or try these regional hotlines:**

- **Jordan:** [JOSA Emergency Response](https://er.jordanopensource.org/)

#### If you are being harassed online ####

- The [Games and Online Harassment Hotline](https://gameshotline.org/), a US-based, text message-based, confidential emotional support hotline for members of the gaming community.
- The Digital Rights Foundation’s Pakistan-based [Cyber Harassment Hotline](https://digitalrightsfoundation.pk/contact/).

**Alternately, hotlines that don’t focus on digital safety may still be able to help**

- The Coalition Against Stalkerware links to hotlines and organizations in 13 countries on [their resources page](https://stopstalkerware.org/resources/).
- The [Cyber Civil Rights Initiative has a crisis helpline](https://www.cybercivilrights.org/contact-us/) for victims of nonconsensual pornography or other forms of online abuse.
- Freemuse offers [assistance to artists](https://freemuse.org/artist-assistance/) at risk of threats, attacks, imprisonments, or exile.

#### If someone else has taken control of your accounts ####

- See Consumer Reports Security Planners’ [list of instructions on regaining access](https://securityplanner.consumerreports.org/tool/regain-control-of-hacked-accounts).

#### If you’ve been a victim of an online scam, fraud or ransomware ####

- See Microsoft’s [list of government fraud and scam reporting websites](https://support.microsoft.com/en-us/windows/protect-your-pc-from-ransomware-08ed68a7-939f-726c-7e84-a72ba92c01c3) (scroll down to "What to do if you already paid").

---

### <a id="scenario-lost-device"></a> 😭 “Somebody took my phone/computer!” ###

- **Wipe or lock your phone remotely**
  - **iOS and Mac:** Instructions for using [Find My](https://support.apple.com/en-us/HT210515#erasedevice).
  - **Android:** Instruction for [Find My Device](https://support.google.com/accounts/answer/6160491?hl=en).
  - **Windows:** Instructions for [Find My Device](https://support.microsoft.com/en-us/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316)
- **Log out of all important accounts from another device.**
- **If this happened at an international border:** Ask for a seizure receipt (available in some jurisdictions, such as [Canada](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf))
- **Get a new SIM card.**
- **If you get your device back, reset it back to its factory settings and restore it from your last backup.**

---

## <a id="other"></a> 💦❓ Other recommendations ##

This section is a catch-all for complex or esoteric practices that don’t fall under any of our scenarios above and might not lead to an immediate payoff for the casual user.

### Emails ###

- **Sign up for an end-to-end encrypted email account.** Check out [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/).
- **Use PGP to secure your emails.**

### File storage & sharing ###

- **Use an encrypted external USB or hard drive** from companies like [Apricorn](https://www.apricorn.com/).
- **Use a special sharing service** like [Tresorit Send](https://send.tresorit.com/) or [OnionShare](https://onionshare.org/) to send files anonymously.
- **Instead of Google Docs or Microsoft Office, use [CryptPad](https://cryptpad.fr) or [Standard Notes](https://standardnotes.org/).** Both are open-source and end-to-end encrypted).

### Messaging apps ###

#### WhatsApp additional settings ####

- **Turn off chat backups on WhatsApp.**
  - `Settings → Chats → Chat backup`
  - **iOS:** [Delete your previous backups on iPhone](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad)
  - **Android:** [Delete your previous backups on Android](https://faq.whatsapp.com/en/android/30030306)).
- **Turn on security notifications on WhatsApp** `Settings → Account → Security`
- **Set up a PIN** (`Settings → Account → Two-Step Verification`) **and email address** (`Account → Two-step verification → tap Add Email Address`) to prevent your account from being moved without your permission.

#### Telegram ####

- **Only use the `Secret Chat` function for secure conversations.** Note that this means your messages will not show up in your desktop or web app.
- **Only allow your contacts to add / find your account.**
- **Turn on self-destruct timers for your Secret Chat.**

#### Apple Messages ####
- Auto-delete messages after a year: `Settings → Messages → Keep Messages → 1 Year.
- Check these two lists of secure messaging apps ([Secure Messaging Apps Comparison](https://www.securemessagingapps.com/) and [IntelTechnique’s Messaging](https://inteltechniques.com/messaging.html)) to learn more about security considerations beyond end-to-end encryption and what trade-offs you may be OK with.

### Hosting/running a website ###

- **Read [this EDRi guide on ethical website development and maintenance](https://edri.org/ethical-web-dev/).** Pay special attention to its privacy recommendations.
- **Protect your website from DDOS attacks and other threats by using**
  - **[Deflect](https://deflect.ca/).** There’s a [free plan]([https://deflect.ca/nonprofit](https://deflect.ca/nonprofit)) for non-profits.
  - **[Cloudflare](https://www.cloudflare.com/).** There’s a [free plan](https://www.cloudflare.com/galileo/) for arts, human rights, civil society, journalism, or democracy organizations.
  - **[Project Shield](https://projectshield.withgoogle.com) from Google.** Only available for news, human rights and election monitoring sites.
- **If using WordPress, consider using the following plugins**
  - **[Wordfence](https://wordpress.org/plugins/wordfence/)**
  - **[Sucuri Security](https://wordpress.org/plugins/sucuri-scanner/)**
  - **[iThemes Security](https://wordpress.org/plugins/better-wp-security/)**
- **Consider switching to a more privacy-oriented hosting service** like [Greenhost](https://greenhost.net/) or one of these recommendations from [Gecko & Fly](https://www.geckoandfly.com/32144/anonymous-offshore-web-hosting/) and [PrivacyTools](https://www.privacytools.io/providers/hosting/).
- **Set up a [security.txt](https://securitytxt.org/) file** so that researchers have a place to disclose security vulnerabilities.

### Other ###

- **Sign up to be notified by [Have I Been Pwned](https://haveibeenpwned.com/)** when an account tied to your email is compromised.
- **Buy a USB [YubiKey](https://www.yubico.com/products/) for two-factor authentication.** If you work in free speech/press/internet, you may qualify for a free [Yubico for Free Speech](https://www.yubico.com/about/about-us/free-speech-program/).
- **Keep less information/data/photos on your devices—you can’t lose what you don’t have.**
- **Turn suspicious PDFs into safe ones using [Dangerzone](https://dangerzone.rocks/).**
- **Access Facebook with more anonymity and bypass internet filtering by using [its onion service](https://en.wikipedia.org/wiki/Facebookcorewwwi.onion).**
- **If you are (or your organization is) wedded to Google Suite/Workspace, consider [Google’s Advanced Protection program](https://www.wired.com/story/google-advanced-protection/).**
- **Put your smart cards/passports/phones in a Faraday bag that blocks signals from going in and out.** (See [Micah Lee’s guide on them](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
- **Use [One Time](https://onetimesecret.com/) to send a password-protected, self-destructing message.**
- **For iOS users:** Download [iVerify](https://www.iverify.io/individuals) to scan your device.
- **For Android users:** Download apps using [F-Droid](https://f-droid.org), an open-source, security-focused app store.
- **Use a more secure operating system on desktop.**  Options include ([Tails](https://tails.boum.org/), [Qubes OS](https://www.qubes-os.org/)) and mobile ([CalyxOS](https://calyxos.org/), [GrapheneOS](https://grapheneos.org/)).
- **Start using more secure devices.** Options include [PINE64](https://www.pine64.org/), [Purism](https://puri.sm/).
- **For US residents:** Freeze your credit to prevent bad actors from accessing or mis-using your personal information. See IntelTechniques’ [Credit Freeze Guide](https://inteltechniques.com/data/workbook.pdf) for details.

---

**🏆 Oh my, you made it this far.  
🏆 You are a true champ!**

---

## <a id="resources"></a> 🧠 Other resources ##

We consulted many sources and drew upon our experiences in creating this resource.

If you’re not finding quite what you want here, we recommend checking out the following resources:

- [Consumer Reports’ Security Planner](https://securityplanner.consumerreports.org/)
- [The Electronic Frontier Foundation’s Surveillance Self-Defense](https://ssd.eff.org/)

---

## <a id="license"></a> 📝 License ##

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## <a id="thanks"></a> 👋🏾 Special thanks ##

Special thanks to the [CryptoHarlem](https://twitter.com/cryptoharlem) community, the students at the School of Journalism and Communication at the Chinese University of Hong Kong, and [our GitHub contributors](https://github.com/narwhalacademy/zebra-crossing/graphs/contributors).
