# 🦓 Zebra Crossing: an easy-to-use digital safety checklist

## 👋🏽 Start here!

### 🤔 Read this guide if you:

- Use the internet daily—for work, social media, financial transactions, and anything else.
- Want to secure your digital safety and privacy proactively but aren’t in immediate danger. (If you are, reach out to an expert for a one-on-one consultation.)
- Feel comfortable with technology. For example, you’re confident going into your computer’s or smartphone’s settings section.

### 🗺 Where this guide is from

The advice here draws from our experiences living and working in the United States, Canada, and Hong Kong.

Much of what we write applies in other places, but [please let us know](mailto:contact@narwhalacademy.org) if you see any gaps in our coverage.

### 🌱 How to use this guide

- **Recommendations are sorted by increasing levels of difficulty.**
Start from Level 1 and work your way up!
- **At a minimum, we recommend following Level 1 and Level 2.**
They will protect you from the most widely-used (yet simple) attacks. Going through them won’t take more than 1–2 hours.
- **Level 3 is a bit more involved and requires dedicated time and money.**
It may not be 100% necessary, but if you’re worried at all and can afford to, we recommend going through that list, too. Depending on the amount of digital housekeeping you have to do, it may take anywhere from 1–4 hours.
- **The scenarios shared after Level 3 are for higher-stakes situations.**
Scan them to see if any of them apply to you. (Because the stakes are higher, they assume you’ve done everything in Levels 1–3.)
- This guide is a living document—please feel free to submit a pull request or fork your version of this guide [on GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🗣 Read this guide in other languages

- [繁體中文 (Traditional Chinese)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-繁體中文.md)
- [Deutsch (German)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Deutsch.md)
- [日本語](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-日本語.md) (Japanese, a work-in-progress)
- [Italiano](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Italiano.md) (Italian, a work-in-progress)

### ☕️ Support this guide

- [Buy us a virtual coffee](https://ko-fi.com/narwhalacademy)

### 🕒 Last updated

- 4 December 2021

---

## 🧐 Definitions, Background, and Theory

### 🎯 Threat modeling

**Threat modeling** is a process that allows us to identify potential threats to safeguard against them.

When putting together your threat model, ask yourself the following questions:

- **“What kind of danger am I in?”** E.g., credit card hack, corporate espionage, online harassment/doxxing.
- **“What kind of assets am I protecting?”** E.g., confidential documents, private photos.

We’re all in a little bit of danger—otherwise, we wouldn’t bother putting a password on our computer or phone.

Still, it’s necessary to think about what’s at stake before dismissing concerns or becoming paranoid.

### 🔗 Weakest link

Remember, the **weakest link** is all that matters! For example, if an account’s password recovery links to your email, hackers only need to access your email to get to your account.

### 🔡 Encryption levels

**Encryption** is the process of converting information to prevent unauthorized access. You’ll want to be aware of three types of **encryption levels:**

1. **No encryption:** Any third-party who intercepts the data can read it as-is.
2. **Regular encryption:** Data is encrypted so that third parties cannot read them. But the platform (Google or Facebook, for example) still has access and may hand the data over if required by the courts or government agencies.
3. **End-to-end encryption:** Only the original sender and receiver can read the data. This means not even the platform has access. So if courts or other government agencies call, the service provider can’t hand over the messages because they don’t have them either.

### 🧩 Metadata

**Metadata** is data about your data. For example, the metadata for a phone call might be the number you called and for how long (but not the call’s contents).

With enough metadata, hackers can piece together a relatively reliable picture of who you are, who you know, and where you’re going.

It's worth noting that legal protections around metadata tend to be weak.

---

## 💦 Level 1 Recommendations

### ✅ Things to do now

#### Strengthen passwords

- Create passwords with more than 10 characters. It’s okay to string together non-related words (for example, `plant-truck-nose-frame-lace`—but don’t use this one since it’s public! 😅)
- Double-check the security questions for your most critical online services (email, banking, social, etc.) and make sure that they’re not easy to answer by friends or anyone looking you up on Google or other search engines.
- Use a different password for every service because password leaks often happen. To make this easy, use a password manager ([Wirecutter](https://www.nytimes.com/wirecutter/reviews/best-password-managers/) recommends 💰 [1Password](https://1password.com/) or [BitWarden](https://bitwarden.com/).) to generate, autofill, and store them. For now, make sure to use a unique password for your critical online services (email, banking, social, cloud storage, etc.).
- Use a non-common/obvious unlock code for your phone with at least 9 digits.

#### Double-lock important accounts

Use two-factor authentication (also known as 2FA and two-step verification) to add a second layer of protection on top of a typed password.

Usually, this takes the form of a short code sent to your phone via a specialized authenticator app or text message (SMS).

Authenticator apps are far more secure than SMS, so use one if available. ([Wirecutter](https://www.nytimes.com/wirecutter/reviews/best-two-factor-authentication-app/) recommends [Authy](https://authy.com/)).

Now that you know what 2FA is, where should you use it? Turn on 2FA for your:

- **Email service.** See instructions for [Gmail](https://support.google.com/accounts/answer/185839?hl=en), [Protonmail](https://protonmail.com/support/knowledge-base/two-factor-authentication/), or find instructions for your email provider [here](https://twofactorauth.org/#email).
- **Frequently used social media accounts.** See instructions for [Twitter](https://help.twitter.com/en/managing-your-account/two-factor-authentication), [Facebook](https://www.facebook.com/help/148233965247823/), [Instagram](https://help.instagram.com/566810106808145), and [other services](https://2fa.directory/#social).
- **Any other online accounts where losing access would be catastrophic.** Look up instructions on [Two Factor Auth](https://2fa.directory/).

Finally, turn on cloud-backup for your authenticator app in case you ever lose your phone. See instructions for [Authy](https://authy.com/features/backup/).

#### Email

- If using a webmail service, check that you're logging into it using an `https://` URL. If there isn't one available, find a new email provider.
- After turning on 2FA, find out if your email service supports **backup codes.** Backup codes are single-use codes in case you lose your phone). [See Gmail instructions](https://support.google.com/accounts/answer/1187538?hl=en).

#### Encrypt your devices

- **Encrypt your computer hard drive:**
  - Mac: [See Apple’s instructions](https://support.apple.com/en-us/HT204837).
  - Windows: [See Microsoft’s instructions](https://support.microsoft.com/en-us/windows/device-encryption-in-windows-10-ad5dcf4b-dbe0-2331-228f-7925c2a3012d) (use BitLocker if it’s available).
- **Encrypt your phone storage:**
  - iOS: Automatically encrypts.
  - Android: Recent versions automatically encrypt. Double-check by going to `Settings → Security → Encryption`.
- **Secure your backups too!**
  - Encrypt your backup hard drives:
    - Mac: If you use Time Machine, [see Apple‘s instructions here](https://support.apple.com/en-ca/guide/mac-help/mh21241/mac).
    - Windows: [See instructions here](https://techjury.net/blog/how-to-encrypt-your-hard-drive/).

**💡 Remember:** encryption is only fully effective when the device is off!

#### Other

- **Setup up a pin code for your mobile phone SIM card:**
  - [See iPhone instructions](https://support.apple.com/en-hk/HT201529).
  - [See Android instructions](https://www.maketecheasier.com/change-sim-pin-android/).
  - If necessary, search your phone provider’s website to find out what their default password is (it varies from carrier to carrier).
- **Turn on the firewall on your computer:**
  - *Mac:* `System Preferences → Security & Privacy → Firewall`.
  - *Windows:* `Control Panel → System and Security → Windows Firewall`.
- **Turn off remote access on your computer:**
  - *Mac:* `System Preferences → Sharing → Remote Login, Remote Management`.
  - *Windows:* `Control Panel → System and Security → System: Allow remote access → Don’t Allow Remote connections to this computer`.
- **Set up basic anti-virus software on your computer:**
  - *Mac:* None required. ([Read Wirecutter’s explanation](https://www.nytimes.com/wirecutter/blog/best-antivirus/.))
  - *Windows:* Make sure Microsoft Defender Antivirus is on ([see Microsoft’s instructions here](https://support.microsoft.com/en-us/windows/stay-protected-with-windows-security-2ae0363d-0ada-c064-8b56-6a39afb6a963)) and [turn on the extra `ransomware protection` feature](https://lifehacker.com/why-you-should-use-windows-defenders-ransomware-prevent-1837311176).
- **Turn off app-specific passwords that bypass two-factor authentication** (e.g. [instructions for Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)).
- **Turn off automatically add(ed) invitations on [Google Calendar settings](https://calendar.google.com/calendar/r/settings)** ([here's why](https://www.forbes.com/sites/daveywinder/2019/06/11/new-security-warning-issued-for-googles-1-5-billion-gmail-and-calendar-users/#3605ff0565e5)).
- **Turn on Login Alerts on Facebook** ([instructions here](https://www.facebook.com/settings?tab=security)).
- **Disable macros within Microsoft Office** ([instructions here](https://support.office.com/en-us/article/enable-or-disable-macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6)).
- **Don’t allow USB accessories to control a locked device:**
  - *iOS:* Turn off `Settings → Face ID & Passcode → Allow Access When Locked: USB Accessories`.
  - *Android:* Off by default, only available if `Developer Options` settings are turned on.

### 💪🏽 Habits to cultivate

#### Email

- **Be on the lookout for phishing scams.** Always double-check:
  - The `From` email address.
  - The domain that outbound links go to.
- **Don’t open unnecessary email attachments.** Where possible, open or preview them first in an online document reader. Ask colleagues to use a filesharing service (Dropbox, Google Drive, Tresorit, SpiderOak), which tends to be harder to hack.
- **Upload suspicious attachments to [VirusTotal](http://www.virustotal.com) for a check-up.** (Keep in mind files submitted to VirusTotal are available to security researchers, so don’t submit sensitive information).

#### Update all the things

- When you get a notification on your devices to update the operating system, do it as soon as you can.
- Turn on auto-update for your apps if the feature is available. If asked to update your app, do so as soon as possible.
- Check occasionally for firmware updates for your router and other internet-connected devices.

#### Other

- Wipe your devices properly before donating or giving them away. If you’ve encrypted your phones and computers (as suggested earlier), a standard factory reset will do the job for almost all use cases. If you want an extra layer of security for your computer hard drives, see [Wired’s guide on this topic](https://www.wired.co.uk/article/securely-wipe-android-iphone-hard-disk).
- Don’t charge your phone at public charging stations/ports, as they may steal your data. Consider charging your portable battery instead.

---

**👍 Great job! You’ve covered the basics.**  
**👍 Treat yourself to a cup of tea and a stretch.**  
**👍 Ready for Level 2?**

---

## 💦💦 Level 2 recommendations

### ✅ Things to do now

#### Enhance your privacy
##### On social media

- Review the privacy settings on social networks you frequent: who can see your content, who can comment on it, and who can see your location.
  - Limit Facebook tracking by turning off “Off-Facebook Activity” (follow [these Electronic Frontier Foundation instructions](https://www.eff.org/deeplinks/2020/01/how-change-your-facebook-activity-settings)).

##### On messaging apps

- Review the privacy settings on messaging apps you usually use: read receipts, time stamps for “last seen,” and whether your phone number and profile picture are public.
- Review what data these big tech companies have on you and clear out anything you don’t need: [Google - My Activity](https://myactivity.google.com), [Alexa Privacy Settings](https://www.amazon.com/b/?node=19149164011), [Microsoft account: Privacy](https://account.microsoft.com/privacy).
- Review the privacy settings on messaging apps you normally use: read receipts, time stamps for "last seen," and whether your phone number/profile picture are public.
- Review what data these big tech companies have on you and clear out anything you don’t need:
  - [Google - My Activity](https://myactivity.google.com)
  - [Alexa Privacy Settings](https://www.amazon.com/b/?node=19149164011)
  - [Microsoft account: Privacy](https://account.microsoft.com/privacy).

##### On browsers

- Install [Firefox](https://www.mozilla.org/en-US/firefox/) and set it as the default web browser on your computer.
- Install these protective web browsers add-ons on your computer (and make sure they're on even during private/incognito mode):
  - An ad blocker (e.g. [uBlock Origin](https://ublockorigin.com/)).
  - A tracker blocker ([Privacy Badger](https://www.eff.org/privacybadger)).
  - [HTTPS Everywhere](https://www.eff.org/https-everywhere).

##### On your phone

- Review which apps on your smartphone have access to your location data. Turn off access if the app doesn’t need it, and minimize the number of apps that track your location all the time.
  - **iOS:** `Settings → Privacy → Location Services`.
  - **Android:** `Settings → Location → App access to location`.
- On Android, turn off passive Wi-Fi and Bluetooth scanning:
  - `Settings → Location → Wi-Fi and Bluetooth scanning`
- On your smartphone, delete any third-party keyboards you might have installed as they often share what you type with the software maker.
  - On iOS and Android, these are installed apps, so it may take some time to find and delete them. If you need to use a third-party keyboard, make sure that it is an open-source project where others have verified that it does not share your data with third parties.

##### On your internet-connected physical devices

- If you use smart speakers, turn off its recording function:
  - Google Home: go to [Activity Controls](https://myaccount.google.com/activitycontrols/audio) and uncheck `Include audio recordings`.
  - Amazon Alexa: [Follow these instructions](https://www.digitaltrends.com/home/how-to-stop-amazon-from-listening-to-your-alexa-recordings/).
- If you own an Amazon Ring or Echo, turn off its feature that shares your internet with strangers:
  - In the Alexa app: `Settings → Account Settings → Amazon Sidewalk`

#### Set up your home wifi router

- Login to the administration and settings dashboard (check your router's instructions, though it's usually accessible by going to `http://192.168.0.1` on your web browser).
- If the password to log into this dashboard is simple (for example, `123456789`), then update it.
- Look through what devices are connected to the network right now (click around until you find the `access control`) and make sure you know what every device on the list is.
- Make sure the following options are turned off (look for them under `advanced settings` or `gateway functions`):
  - UPnP (universal plug and play)
  - WPS (wi-fi protected setup)
  - Remote management

#### Other

- Set up tracking apps for your devices so you can remotely find and wipe your devices by logging into a website if you ever lose them:
  - **iOS & Mac:** [Instructions for setting up Find My](https://support.apple.com/en-us/HT210400).
  - **Android:** [Instructions for setting up Find My Device](https://support.google.com/android/answer/6160491?hl=en).
  - **Windows:** [Instructions for setting up Find My Device](https://support.microsoft.com/en-us/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316).
- Review the `Third-Party Apps` or `Connected Apps` on your primary email/social media accounts. These are services that might have access to your Facebook data and even permission to make posts automatically there. ([Here are the instructions for checking for them on Facebook and Gmail](https://www.online-tech-tips.com/computer-tips/check-google-facebook-connected-apps/).)
- Review the extensions/add-ons/plug-ins installed on your computer web browser—delete any that you haven’t used in a while or don’t remember installing.


### 💪🏾 Habits to cultivate

#### Enhance your privacy

- Post very little, if any, personal information online—mainly information that others can use to identify/track/scam you (addresses, phone numbers, birthday, etc.).
- Remember almost everything you say online is logged somewhere and that even if your setup is secure, your recipient’s setup may not be.
  - If you enjoy leaving local business reviews on Google Maps, Yelp, etc., set up a new account under a pen name. This is especially important for Google Maps, where they show the profile picture and full name you use on Gmail.
- If you own domains, use WHOIS privacy services and stick with them (they’re worth the money, and some providers will add WHOIS service for free). But note that with WHOIS lookup/history tools, if you’ve ever put in your actual address, it’s challenging to remove from the logs.

#### Watch what you say in online groups

Don’t say anything you’d regret on in a “private” Slack group, Facebook page, WhatsApp group chat, or Telegram channel because:

- Any member can leak everyone’s data.
- Administrators usually have access to everything within the group, including private, direct messages between two people, and sometimes even deleted messages.
- Even if you’re not using your real name or photo, what you say can often be traced back to your phone number or email linked to your account.
  - To prevent this in Telegram, go into `Settings → Privacy and Security → Phone Number`, and then set:
    - `Who can see my phone number` to `Nobody`.
    - `Who can find me by my number` to `My Contacts`.

#### Other

- When you download new mobile apps, double-check to make sure it’s the right one — there are a lot of fake apps that try to trick people by using a slightly modified name or icon of an existing, popular app.
- Regularly check the apps installed on your phone and delete the ones you’re not using anymore.
- If you ever need to send someone a password, split it in half and send each half using two different channels (e.g., email + voice call).
- Put a sticker (or webcam cover) over your laptop’s front-facing camera.
- Don’t use Google/Twitter/Facebook to sign up/login to other services—each service should have its own account.

---

**🎉 Congratulations! You're now reasonably secure!**  
**🎉 (Which is more than most) :)**  
**🎉 Take the rest of the day off, and...**  
**🎉 Come back tomorrow (or another day) for Level 3!**

---

## 💦💦💦 Level 3 recommendations

### ✅ To do

#### Lock up sensitive files

- Identify files you don't want others to access (e.g., private photos, passport documents).
- Use [Cryptomator](https://cryptomator.org/) or [Veracrypt](https://www.veracrypt.fr/en/Home.html) to create an encrypted, password-protected vault for them.
- Set them up on both your computer and your phone.
- Move your files into these secure vaults. Make sure they're not still hanging around on an old folder or your phone.

#### Upgrade your gear 💰


- Use a paid VPN service when on public networks (e.g., cafe wifi) and even at home if you don't want your service provider to know where you're going.
  - Free VPN services are inadequate because operators don't have enough incentive to protect you/your data.
  - [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/) both recommend [Mullvad](https://mullvad.net) and [IVPN](https://www.ivpn.net/)
- Buy a privacy screen for your laptop and phone. It prevents onlookers from seeing your screen—see [this 3M example](https://www.3m.com/3M/en_US/company-us/all-3m-products/~/All-3M-Products/Privacy-Screen-Protectors/Privacy-Products/Black-Privacy/).
- Buy a harder-to-hack mobile phone — an iPhone or an Android phone that implements a "pure" Google version of Android.

#### Revisit old passwords

- Store all of your online service passwords in a password manager. (If you have the right browser add-on/plugin installed, it will capture all the relevant details during a login process.)
- Using your password manager's analysis feature, see which accounts/services have weak passwords and update the ones that might have any personal information about you or that you would hate to lose.

#### Use end-to-end encrypted apps

##### Mobile messaging apps

- [Signal](https://signal.org/) (sign up with phone number)
- [Wire (Personal)](https://wire.com/en/products/personal-secure-messenger/) (sign up with email)
- Consider letting messages expire after 1 week.
  - Signal: `Go to Settings → Privacy → Disappearing Messages → Default Timer for New Chats`.
  - Wire: No app-wide setting exists. You have to set it up for each conversation by tapping/clicking the timer icon ⏱.

##### One-on-one or small group voice/video calls

- Continue using [Signal](https://signal.org/), [Wire](https://wire.com/en/products/personal-secure-messenger/)


##### Large group video calls

- Privacy is hard to maintain with many people, particularly as large group calls often become quasi-public events.
- If you have a particular need for privacy, see Freedom of the Press' chart: [Which video conferencing tool is right for the job?](https://freedom.press/training/blog/videoconferencing-tools/)
##### Online file sharing/backup
- [Tresorit](https://tresorit.com/), [Spideroak One](https://spideroak.com/one/).
- Remember, files on Google Drive and iCloud are not end-to-end encrypted.

---

**😲 Wow, you completed all three levels!**  
**😲 Well done! Now quickly look below**  
**😲 to see if any apply to you.**  

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
  - US travel: See [BoingBoing's note](http://boingboing.net/2017/02/12/how-to-cross-a-us-or-other-b.html) about filing for attorney privileges at the US border.

---

### 😭 Somebody took my phone/computer!

- Wipe or lock your phone remotely:
  - iOS, Mac: Instructions for using [Find My](https://support.apple.com/en-us/HT210515#erasedevice). 
  - Android: Instruction for [Find My Device](https://support.google.com/accounts/answer/6160491?hl=en).
  - Windows: Instructions for [Find My Device](https://support.microsoft.com/en-us/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316)
- Log out of all important accounts from another device.
- If this happened at an international border: Ask for a seizure receipt (available in some jurisdictions, e.g. [Canada](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf))
- Get a new SIM card.
- If you get your device back, reset it back to its factory settings and restore from your last backup.

---

### 👾 I think my computer has been hacked?

- Download an application that help you analyze the data streams going in and out of your devices. Try:
	- [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) for Mac.
	- [Charles Proxy](https://www.charlesproxy.com/) for Windows,Mac, Linux.
	- [Glasswire](https://www.glasswire.com/) for Windows/Android.
	- [Guardian Firewall](https://guardianapp.com) for iOS.
- Run Activity Monitor on Mac or Process Explorer on Windows to look at what processes/applications are running. Google any suspicious names.
- Login to important online accounts to see if there have been any suspicious logins – see [this Motherboard guide for details](https://motherboard.vice.com/en_us/article/bjeznz/how-do-you-know-when-youve-been-hacked-gmail-facebook).
- Setup a spare Android phone using [Haven](https://guardianproject.github.io/haven/) as a room monitor to detect unwanted intrusions.

---

### 🍆 Sexting & consensual image sharing

- See [The Motherboard Guide to Sexting Securely](https://motherboard.vice.com/en_us/article/mb3nd4/how-to-sext-securely-safely-what-apps-to-use-sexting).

---

### ✊🏾 Attending a protest

#### In case of emergency

- Draft a message to a trusted friend (not at protest) or legal hotline. Be ready to hit send if you are arrested/there is an emergency.
- Write the phone number of the trusted friend/hotline on your arm with permanent marker as a backup.
- Bring a spare battery for your phone.
- If you use your fingerprint or face to unlock your phone, turn it off for now. In some jurisdictions, [officers can compel you to provide your fingerprint but not your passcode](http://www.theatlantic.com/technology/archive/2016/05/iphone-fingerprint-search-warrant/480861/).
- Immediately power off your phone if you think you'll be arrested (disk encryption works better if it's off).
- Consider using a burner phone ([instructions for the US](https://theintercept.com/2020/06/15/protest-tech-safety-burner-phone/)) with a burner SIM card.

#### Store less share less

- Keep as little sensitive personal information on your phone as possible. Delete any photos, chat logs and notes that can be used against you.
- Use a messaging app that lets you create disappearing messages (e.g. [Signal](https://signal.org/)). Turn on the timer when discussing the protest.
- Don't take any photos or videos where people's faces are clearly visible. Taking a photo of people's backs is okay. (The one exception is if you're filming a video of a conflict or arrest where documentation is key.)
- Wear a face mask so you are not easily caught on camera.
- When sharing photos/videos, blur the faces of any protesters using these apps/features:
  - Phone:
    - [Signal's blur tool](https://signal.org/blog/blur-tools/) for photos.
  - Computer:
    - Everest Pipkin's [Image Scrubber](https://everestpipkin.github.io/image-scrubber/) for photos.
    - Youtube's [blur faces tool](https://youtube-eng.googleblog.com/2017/08/blur-select-faces-with-updated-blur.html) for videos.
- If need be, erase the location metadata on any photos/videos before posting using [these apps](https://www.maketecheasier.com/best-apps-remove-exif-data-from-images/).

#### Minimize location tracking

- Turn off location history:
  - iOS: `Settings → Privacy → Location Services → System Services → Significant Locations`.
  - Android: `Settings → Privacy → Advanced → Google Location History →  Activity Controls: Location History.
  - Google Maps: `Settings → Maps history → Web & App Activity`.
- Delete past location history:
  - iOS: `Settings → Privacy → Location Services → System Services → Significant Locations → Clear History`.
  - [Android](https://support.google.com/accounts/answer/3118687?hl=en#delete)
  - [Google Maps](https://support.google.com/maps/answer/3137804?hl=en)
- Consider turning off all location services temporarily:
  - iPhone: `Settings → Privacy → Location Services → Location Services: Off`.
  - Android: `Settings → Location → Use location: Off`.

#### Other

- Double check your messaging apps' privacy settings.
- Turn off message previews in your notifications:
  - iOS: `Settings → Notifications → Show Previews: When Unlocked`.
  - Android: `Settings → Apps & notifications → Notifications → Notifications on lock screen → Sensitive notifications: Off`.
- Remember to make voice calls through end-to-end encrypted apps like [Signal](https://signal.org/).

---

### 📰 I'm a journalist working on a sensitive topic

Below are some basics that all journalists should consider. If you're working on/in a particularly sensitive story/region (e.g. a whisteblower story), you and your team should get an tailored training session from an expert.

#### Be prepared

- To remotely wipe the contents of your devices. See scenario above titled `Somebody took my phone/computer!`
- To be on the receiving end of an email phishing campaign (as journalist emails are usually more public than others).

#### Protect your sources

- Use email as little as possible as [even end-to-end encrypted email leaves a trail of metadata](https://freedom.press/training/blog/how-reporters-emails-get-got-case-studies-legal-request-hacking/).
- To exchange messages, use an end-to-end encrypted messaging app that doesn't store metadata like [Signal](https://www.signal.org/). (Don't use Twitter DMs!)
- For voice/video calls, also use an end-to-end encrypted app like [Signal](https://www.signal.org/) or [Wire](https://wire.com/en/products/personal-secure-messenger/).
- Use the security features in Signal and Whatsapp – see Martin Shelton's articles on [Locking Down Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) and [Upgrading WhatsApp security](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3).
- For document transfers, have your organization set up [SecureDrop](https://securedrop.org/). Failing that, encourage people to use [OnionShare](https://onionshare.org/).
- Blur faces from photos and videos. See the `Store less share less` section in the `Attending a protest` scenario above.
- See Ted Han and Quinn Norton's [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/).
- See Martin Shelton's [Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/).

#### Protect yourself

- Use a secondary phone number on Signal to talk to your sources, and to create a public tip line. Follow Yael Grauer's guide on [How To Use Signal Without Giving Out Your Phone Number Using a Chromebook and an Old Phone](https://blog.yaelwrites.com/how-to-use-signal-without-giving-out-your-phone-number-using-a-chromebook-and-an-old-phone/).
- If you're traveling, review the `Crossing an international border` scenario above.
- If you're covering a protest, review the `Attending a protest` scenario above and decide which parts apply to you (if you have special journalist rights/protections where you're working).
- Use a VPN if you're browsing the internet at the office (website administrators can usually see that you're coming from, say, the New York Times network).

#### Protect your data

- Make sure you're using an email/storage provider that's not owned/linked to an organization that you're reporting on.
- Be aware that [courts can compel Google to hand over all of your data](https://medium.com/@tinfoilpress/newsrooms-lets-talk-about-g-suite-1672a36eb235).
- Move all of your work onto end-to-end encrypted platforms. (E.g. [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) for email, [CryptPad](cryptpad.fr/) for docs/spreadsheets.
- Store sensitive data in a password-protected cloud or external storage device as much as possible. See the `Lock up sensitive files` section above.
- Remember to permanently erase sensitive files from your computer: use [Eraser for Windows](https://eraser.heidi.ie/) and [File Shredder for Mac](https://apps.apple.com/us/app/fileshredder/id418094085?mt=12).

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
- Alternately, reach out to online communities you're an active member of and ask for help. See PEN America's article on [Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/deploying-supportive-cyber-communities/).
- If no one is available right now, Heartmob has a list of [supportive organizations](https://iheartmob.org/resources/supportive_organizations), some of which have 24/7 hotlines.

#### Search for public information about yourself (dox yourself)

Ask your trusted friend to:

- Search for your name, nicknames, usernames, and address on Google, Bing and any other popular search engines. Try adding `filetype:pdf` to your search query to catch any CVs or documents you might have missed.
- Run an image search on your most-used profile pictures on the same search engines as well.
- Search for your name, nicknames and usernames on any social media platforms you regular use, as well as any social media platforms that are popular where you are.

For more information, see Access Now Digital Security Helpline's [Self-Doxing Guide](https://guides.accessnow.org/self-doxing.html).

#### Monitor updates & collect receipts

- Monitor your name/username using these services: [Talkwalker](https://www.talkwalker.com/alerts), [Google Alerts](https://www.google.com/alerts) and/or [Mention](https://mention.com) 💰.
- Monitor and archive webpages that mention you using [ChangeTower](https://changetower.com/).
- Start logging (date, time, description, screenshot, URL) incidents in whatever program/app that's easiest for you. If there's a lot of phone-only content, use the [Hunchly](https://hunch.ly/) mobile app.
- If future legal action is likely, pay [Page Vault](https://www.page-vault.com) to capture a snapshot of a website and ask a lawyer to file an [evidence preservation request](https://onlinesos.org/blog/evidence-preservation-i-e-litigation-hold-request) with the relevant online platform. 

#### Delete online information about you

- See scenario below titled: `Remove information about you off of the internet`.

#### Ignore/reply/report/block your harassers

- Together with your trusted friend and the log of receipts, decide on your course of action (these aren't mutually exclusive):
  - **Ignore:** Sometimes harassers will become bored and walk away if they don't get attention.
  - **De-escalate:** In some contexts, you can defuse the situation with some calm words before it gets worse.
  - **Report:** Report the harasser to the relevant online platform to have their account frozen or deleted. If it makes sense, you may also report the incident to your local law enforcement.
  - **Mute on social media:** This allows you to have peace of mind, and not have your harasser's updates suddenly pop up on social media. (You might still want to proactively check what they're saying though.)
  - **Block on social media:** Sends a strong signal to your harasser. They won't be able to see your posts or message you. They will however see clearly that you blocked them and might interpret it as a sign of escalation.
  - **Go public:** Sometimes shaming a harasser publicly or rallying people to your support will make them go away. This has a high risk of escalating the situation and drawing more attention to it though.
- If you decide to report:
  - If you file a report with a social media company, ask at least 10 friends to do it as well. If it makes sense, have 1-2 people file a copyright infringement claim. Relevant links for [Facebook](https://www.facebook.com/help/www/181495968648557), [Instagram](https://help.instagram.com/192435014247952), [Twitter](https://help.twitter.com/en/forms/safety-and-sensitive-content), [Snapchat](https://support.snapchat.com/en-US/a/report-abuse-in-app).
  - If there is harassment material on a website, you can file a report with the website's webhosting service and domain registrar. You might be able to find out who these companies are by performing a [WHOIS lookup](https://lookup.icann.org/) on the website domain.
  - If you contact law enforcement:
    - Beware that not all officers are used to dealing with online harassment threats.
    - If you believe you might become a target of swatting (where people prank call the cops on you), let them know. Send them an article about swatting in case it's a new idea to them.

#### Social media platform tools and features

**Facebook** has a few features to control your interactions, but ultimately relies on you setting limits on who can see and comment on your posts and profile:

- [`Ignore Messages`](https://www.facebook.com/help/messenger-app/1245152242249842) within Facebook Messenger to move the current and future messages to the `Message Requests` section
- [`Privacy Checkup`](https://www.facebook.com/privacy/checkup) within Facebook includes a section on `Who can see what you share` that walks you the visibiity of your profile and posts.

**Instagram** has a set of nuanced features within its mobile app to filter and fine tune social interactions on its platform:

- [`Restrict`](https://help.instagram.com/2638385956221960/) an account, which means the other person can't see when you're online, whether you've read their messages, and hides their comments.
- [`Hide`](https://help.instagram.com/1177797265575168/) your stories from a specific account.
- [`Hidden Words`](https://help.instagram.com/700284123459336) filters out messages and comments with words that Instagram deems offensive. You can also set up a custom words list.
- [`Limit`](https://help.instagram.com/4106887762741654) comments and messages from accounts that aren't following you or from recent followers.

**Twitter** works with some pretty handy third-party tools and has a few features of its own:

- Filter unwanted mentions and replies, and/or archive them to process later with the help of a friend using [Block Party](https://www.blockpartyapp.com/).
- Block previously-identified offenders using [Block Together](https://theblockbot.com/) — ask around in your communities for shared block lists.
- Block troll bots using [Bot Sentinel](https://botsentinel.com).
- Reduce dogpiling by blocking all followers of a certain profile using [Red Block](https://github.com/gaeulbyul/RedBlock).
- See what lists you've been added to by going to `Profile → Lists → ··· → Lists` you're on. If you see a suspicious list or list owner, tap the three dots on the top right to report the list and leave the list by blocking the creator.
- Control who can reply to your tweets by tapping `Everyone can reply` and restricting it to `People you follow` or `Only people you mention`.

#### Notify other parties

- Tell your close contacts, family and employer about what is going on. Get ahead of the situation by making talking points together so that they know how to respond if internet strangers or the press contacts them. 
- If the situation escalates, find and notify someone in your community nearby with crisis experience for protection and support.

### Be extra kind to yourself

- Don't worry if you're not able to keep up with your regular work day routine.
- Call in friends to help share a meal, take a break or watch your cats for a few days.
- Remember to eat and shower regularly.
- Go for a walk. Do some sort of exercise, no matter how small.
- If possible, prepare a box of comforts beforehand. Include things that you like to see, touch, taste, and listen to.
- If the incident is traumatizing, it helps to use a nickname to refer to what's happening or what's happened.

#### Bonus tips for journalists and researchers

- Make yourself a harder target. Consider making all of your social media accounts private (or temporarily deleting them) for 48 hours surrounding a major, new release.
- Remember you did nothing wrong. Some ignorant employers or colleagues may not be supportive and even start seeing you as a liability. They are wrong.
- Don't make more noise about yourself. Don't livetweet your situation, don't quit your job suddenly, and don't talk to media outlets who will twist your words. If need be, prepare a formal written statement or reply with the help of people who have experience dealing with the media.
- But if the noise won't stop, flood the airwaves with positive stories about yourself. Ask people within your professional community to write positive articles or social media post about you and your work.
- Read [Lyz Lenz's conversation with Talia Lavin](https://lyz.substack.com/p/when-the-mob-comes) about their experiences.

#### For more information

- See Kat Fukui's [Guide for handling online harassment](https://www.tinykat.cafe/guide-for-handling-online-harassment).
- See OnlineSOS' [Action Center](https://onlinesos.org/action-center/category:identify).
- See PEN America's [Online Harassment Field Manual](https://onlineharassmentfieldmanual.pen.org/).
- See Feminist Frequency's [Speak Up & Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/).
- See TrollBusters' [What to Do? Where to Go? Infographic](https://yoursosteam.wordpress.com/what-to-do-infographic/).

---

### 👀 Remove information about you off of the internet

If you're about to become a public figure or are experiencing harassment, consider some of the suggestions below.

#### Clean up your social media presences

You might not need to delete your entire account, but consider deleting (or making private) posts that are old and/or reveal too much about where you live, where you go, and who you're with.

##### Facebook

- See what your public profile looks and remove/restrict things as you see fit.
  - On desktop, go to your profile and click the 👁 button next to the right of the Edit Profile button.
  - On mobile, go to your proflie, tap the three dots on the right of Add Story and tap View As.
- Make it so only friends can see your past posts.
  - On desktop, go to `Settings → Privacy → Limit Past Posts`.
  - On mobile, go to `Settings & Privacy → Settings → Privacy Settings → Limit who can see past posts`.
- To bulk delete past posts, [see this article in PC Magazine](https://www.pcmag.com/how-to/how-to-quickly-delete-old-facebook-posts).

##### Whatsapp

- Swipe to delete individual conversations.
- Delete chat content but keep the chat groups: `Settings → Chats →  Clear All Chats`.
- Delete all chats including the chat groups: `Settings → Chats → Delete All Chats`.
- Turn off chat backups on WhatsApp (`Settings → Chats → Chat backup`) and delete your previous backups (instructions for [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).

##### Instagram

- Look through your profile and manually delete posts (tap the three dots above upper-right corner of a photo).
- If need be, bulk delete using [third-party tools](https://upleap.com/blog/how-to-delete-an-instagram-post/).

##### Twitter

- Use a third-party service to filter for tweets you want to save, and bulk delete the rest. We recommend [Semiphemeral](https://semiphemeral.com) (free + open source, but beta), [TweetDelete](https://tweetdelete.net/) (free + paid 💰 options), or [Twitter Archive Eraser](https://martani.github.io/Twitter-Archive-Eraser/) (free + paid 💰 options).
- Alternately, manually locate and delete individual posts using [Twitter's Advanced search](https://twitter.com/search-advanced). 

##### Reddit and other forums

- There's often no easy solution. Sometimes you have to delete your entire account, or in the case of Reddit, you have to [use third-party scripts](https://social.techjunkie.com/how-to-delete-all-reddit-posts/) because deleting your account still leaves your posts up.

##### LinkedIn

- Modify the [visibility settings](https://www.linkedin.com/psettings/data-visibility) of your profile.

#### Delete your social media accounts... temporarily

Many social media companies let you restore your full account after deleting it if you restore after a specific period of time. This can be useful if you want to just hide for a while and wait for an event to pass.

- **Facebook** has [instructions](https://www.facebook.com/help/224562897555674) for temporarily deactivating your account, or for deleting it (which can be reversed within a 30-day period)
- **Instagram** has [instructions](https://help.instagram.com/370452623149242/) for temporarily disabling your account, but deleting it seems to be permanent.
- **Twitter** has [instructions](https://help.twitter.com/en/managing-your-account/how-to-deactivate-twitter-account) for deactivating your account, and if you don't restore it (login) after 30 days it is permanently deleted.
- **Snapchat** has [instructions](https://support.snapchat.com/en-US/a/delete-my-account1) for deleting your account, and if you don't reactivate it (login) after 30 days it is permanently deleted.

#### Remove your information from other people's accounts or websites

- [Ask Google](https://support.google.com/websearch/troubleshooter/3111061?hl=en) and [Bing](https://www.microsoft.com/en-ca/concern/bing) to remove search results pointing to pages with your personal information on them.
- Remove any local business reviews you have might left on Google Maps, Yelp, etc. that might point to your home or frequently visited places.
- Follow the Cyber Civil Rights Initiative's [guide to get policy-violating posts/media removed from social networks](https://www.cybercivilrights.org/online-removal).
- If you're willing to pay 💰, [Yael Grauer](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List#paid-options) recommends using [DeleteMe](https://joindeleteme.com/) and [Kanary](https://www.thekanary.com/) to remove your information from English-language public and paywalled sites.
- If you want to do it yourself, check out Yael Grauer's [Big Ass Data Broker Opt-Out List](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List). (To be 100% thorough, use this on top of paid services.)
- Remember that information removal requests takes time to process and often require repeated attempts.

### Removing articles and press about you online

- Think of this as risk reduction, not total elimination, as it will be impossible to have everything removed.
- Contact the editor or your previous contact. Explain your situation honestly and hope for a sympathetic editor/writer.
- If you think the editor/writer will not respond well, then it may be better to not reach out in case it draws more attention to your situation.
- For older articles, it may help to remind them that the article is still easily accessible on search engines.
- As a general rule — the larger the publication, the harder it is to persuade them.

#### Obscure your personal information

- See scenario below titled: `I don't want to give out my real phone number for online dating/networking/organizing`.
- Get a PO box at a post office or use [Traveling Mailbox](https://travelingmailbox.com/) (USA only) to hide your home address.
- Delete old accounts to eliminate traces of personal information on the Internet. Use [JustDeleteMe](https://justdeleteme.xyz/) to accelerate this process.

---

### 💔 I think my partner is spying on me through my phone (stalkerware)

#### If you're not sure and things between you and your partner aren't that bad yet:

- Keep a hidden, pen-and-paper log of suspicious incidents.
- Make sure your partner is not getting information from previously shared accounts (e.g. calendars) or because you left the [location share on within Google Maps](https://support.google.com/maps/answer/7326816?co=GENIE.Platform%3DAndroid&hl=en).
- Review and redo the items in Levels 1-3 of this guide. Reset your passwords, check your privacy/data sharing permissions, and look up any apps you don't recognize on your computer and phone.
- Keep an eye out for other signs. E.g. your phone battery doesn't last very long, your laptop internet connection is slow, you get emails/prompts about someone else logging into an account, or your partner suddenly borrowed your phone for a long time the other day.
- **Don't delete suspicious apps immediately** — you may need to keep them as evidence. Plus, deletion may also cause the situation with your partner to escalate.

#### If you're pretty sure they're spying on you and you're scared:

- Seek help. You should not go through this alone:
  - Find a public or friend's computer/phone to contact the organizations in [this global resource list compiled by the Coalition Against Stalkerware](https://stopstalkerware.org/get-help/resources/). Some of them can even help you collect evidence and remove stalkerware safely.
  - Reach out to a trusted friend (through a public device/line) and ask them to hold space for your situation and be your sounding board on analyzing how bad the situation is.
- Keep digital and printed records of relevant texts, emails, calls, etc. See the NNEDV's [guide on documenting/saving evidence](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence).
- When you no longer need evidence anymore, remove the suspicous apps/stalkerware yourself either by performing a full factory reset on your computer/phone. (Buying a brand new device is even safer of course.) Remember to reinstall apps and import data manually, lest you restore a backup with stalkerware in it.

#### For more information

- See Consumer Reports' [Shut Stalkers Out of Your Tech](https://www.consumerreports.org/digital-security/shut-stalkers-out-of-your-tech/)
- See Wirecutter's [Protect Your Devices Against Domestic Abusers](https://thewirecutter.com/blog/domestic-abusers-can-control-your-devices-heres-how-to-fight-back/)
- If you're an iOS user, see [Apple's checklist](https://support.apple.com/en-us/HT212021) and download the document at the bottom called `Device and Data Access when Personal Safety is At Risk`.

---

### 👤 I don't want to give out my personal information for online dating/networking/organizing

For messaging apps that use phone numbers as the primary identifier/username (e.g. Signal, WhatsApp, Telegram), get a secondary number from:

- 💰 [Hushed](https://hushed.com) (US, Canada, UK numbers),  [Burner](https://www.burnerapp.com/) (US, Canada numbers) or [Skype](https://secure.skype.com/en/skype-number) (lots of countries)
- 🆓 [TextNow](https://www.textnow.com/) (ad-supported US/Canada number)  [Google Voice](https://voice.google.com/about) (free number only available in the US)
- 💰 A local phone company: get a prepaid or cheap SIM card plan

For sites and services that use email as the primary identifier/username, either get a new email account or get an email alias that forwards to your main account from:

- 🆓 [SimpleLogin](https://simplelogin.io) (based in EU) 
- 🆓 [AnonAddy](https://anonaddy.com) (based in UK/EU)

To mask what you've bought from your bank, get a virtual credit card from [Privacy](https://privacy.com/) (US-only, feature only available for Pro accounts 💰).

Keep in mind:

- If you lose/unsubscribe to your secondary phone number, other people can buy it and impersonate you.
- Courts can still compel companies to hand over your information in most cases. 

#### For true anonymity – create an untraceable online persona under a pseudonymn

- If you're a public figure, consider working under a persistent pseudonymn or collective identity – this [Tactical Tech manual](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online) has more details on why.
- To operate online under a truly safe pseudonymn, follow this guide on [creating untraceable online accounts and protecting your real identity](https://medium.com/@geminiimatt/creating-an-online-persona-deb4cd8c7f46).

---

### 🤐 Traveling to a place with weak data protection laws or internet censorship

- Be aware that the phone companies there might share your location data and personal info with others without permission.
- Setup a VPN beforehand so you can a) access services uninterrupted, and b) to minimize the amount of data collected about you. Avoid VPNs that are free or have opaque ownership. [Wirecutter](https://thewirecutter.com/reviews/best-vpn-service/) and [Freedom of the Press](https://freedom.press/training/choosing-a-vpn/) both recommend 💰 [Mullvad](https://mullvad.net) and 💰 [IVPN](https://www.ivpn.net/).
- Consider traveling with a burner phone while leaving your laptop at home. This will be especially useful if you need to install new/untested software for work that might violate data privacy policies.
- Re-evaluate which online services are safe to use:
  - If available, see how often your favorite service hands over its data by looking up their transparency reports:
    - [Google Transparency Report: Request for user information](https://transparencyreport.google.com/user-data/overview)
    - [Facebook Transparency Report: Government Requests for User Data](https://transparency.facebook.com/)
    - [Twitter Transparency Center: Information Requests](https://transparency.twitter.com/en/reports/information-requests.html)
    - [Apple Transparency Report](https://www.apple.com/legal/transparency/)
  - Look up where the service's headquarters are and think about how that affects its privacy policies.

---

### 😣 I need help now, my systems are under attack!

If you work as part of a civil society group, contact:

- Access Now's [Digital Security Helpline](https://www.accessnow.org/help/).
- Front Line Defender's [Emergency Contact](https://www.frontlinedefenders.org/emergency-contact).
- SMEX's [Digital Safety Helpdesk](https://smex.org/helpdesk/) for people in Lebanon and other Arabic-speaking countries.
- [Vita Activa](https://vita-activa.org/) for Spanish speakers.
- If you have a bit more time, apply for a Digital Defenders Partnership [Incident Emergency Grant](https://www.digitaldefenders.org/funding/incident-emergency-funding/).

Or try these regional hotlines:

- Jordan: [JOSA Emergency Response](https://er.jordanopensource.org/)

If you are being harassed online, contact:

- The [Games and Online Harassment Hotline](https://gameshotline.org/), a US-based, text message-based, confidential emotional support hotline for members of the gaming community.
- The Digital Rights Foundation's Pakistan-based [Cyber Harassment Hotline](https://digitalrightsfoundation.pk/contact/).

Alternately, hotlines that don't focus on digital safety may still be able to help:

- The Coalition Against Stalkerware links to hotlines and organizations in 13 countries on [their resources page](https://stopstalkerware.org/resources/).
- The [Cyber Civil Rights Initiative has a crisis helpline](https://www.cybercivilrights.org/contact-us/) for victims of nonconsensual pornography or other forms of online abuse.
- Freemuse offers [assistance to artists](https://freemuse.org/artist-assistance/) at risk of threats, attacks, imprisonments, or exile.

If someone else has taken control of your accounts:

- See Consumer Reports Security Planners' [list of instructions on regaining access](https://securityplanner.consumerreports.org/tool/regain-control-of-hacked-accounts).

If you've been a victim of an online scam, fraud or ransomware:

- See Microsoft's [list of government fraud and scam reporting websites](https://support.microsoft.com/en-us/windows/protect-your-pc-from-ransomware-08ed68a7-939f-726c-7e84-a72ba92c01c3) (scroll down to "What to do if you already paid").

---

## 💦❓ Other recommendations

This section is a catch-all for difficult or esoteric practices that do not fall under any of our scenarios above and might not lead to an immediate payoff for the casual user.

#### Emails

- Sign up for a [Protonmail](https://protonmail.com/) or [Tutanota](https://tutanota.com/) end-to-end encrypted email account.
- Use PGP to secure your emails.

#### File storage & sharing

- Use encrypted external USB/hard drives from companies like [Apricorn](https://www.apricorn.com/).
- If you want to send a file anonymously, use a special sharing service like [Tresorit Send](https://send.tresorit.com/) or [OnionShare](https://onionshare.org/).
- Instead of Google Docs or Microsoft Office, use [CryptPad](https://cryptpad.fr) or [Standard Notes](https://standardnotes.org/) (both are open-source and end-to-end encrypted).

#### Messaging apps

- WhatsApp additional settings:
  - To be 100% end-to-end encrypted, turn off chat backups on WhatsApp (`Settings → Chats → Chat backup`) and delete your previous backups (instructions for [iOS](https://www.wikihow.com/Delete-Backups-on-WhatsApp-on-iPhone-or-iPad), [Android](https://faq.whatsapp.com/en/android/30030306)).
  - Turn on security notifications on WhatsApp (`Settings → Account → Security`).
  - Set up a pin number (`Settings → Account → Two-Step Verification`) and email address (`Account → Two-step verification → tap Add Email Address`) to prevent your account from being moved without your permission.
- Telegram:
  - Use only the `Secret Chat` function for secure chats (note that this means your messages will not show up in your desktop or web app)
  - Only allow your contacts to add / find your account
  - Turn on self-destruct timers for your Secret Chat.
- Apple Messages:
  - Auto-delete messages after a year: `Settings → Messages → Keep Messages → 1 Year.
- Check these two lists of secure messaging apps ([Secure Messaging Apps Comparison](https://www.securemessagingapps.com/) and [IntelTechnique's Messaging](https://inteltechniques.com/messaging.html)) to learn more about security considerations beyond end-to-end encryption and what trade-offs you may be OK with.

#### Hosting/running a website

- Read [this EDRi guide on ethical website development and maintenance](https://edri.org/ethical-web-dev/). Pay special attention to its privacy recommendations.
- Protect your website (from DDOS attacks and other things) by using:
  - [Deflect](https://deflect.ca/) (has [free plan](https://deflect.ca/nonprofit)) for non-profits).
  - [Cloudflare](https://www.cloudflare.com/) (has [free plan](https://www.cloudflare.com/galileo/) for arts, human rights, civil society, journalism, or democracy organizations).
  - [Project Shield](https://projectshield.withgoogle.com) from Google: only available for news, human rights and election monitoring sites. 
  - [Wordfence](https://wordpress.org/plugins/wordfence/), [Sucuri Security](https://wordpress.org/plugins/sucuri-scanner/) and [iThemes Security](https://wordpress.org/plugins/better-wp-security/) plug-ins for Wordpress.
- Consider switching to a more privacy-oriented hosting service like [Greenhost](https://greenhost.net/) or one of these recommendations from [Gecko & Fly](https://www.geckoandfly.com/32144/anonymous-offshore-web-hosting/) and [PrivacyTools](https://www.privacytools.io/providers/hosting/).
- Set up a [security.txt](https://securitytxt.org/) so that researchers have a place to disclose security vulnerabilities.

#### Other

- Sign up to be notified by [Have I Been Pwned](https://haveibeenpwned.com/) when an account tied to your email is compromised.
- Buy a [YubiKey](https://www.yubico.com/products/) USB key to use for two-factor authentication. If you work in free speech/press/internet, you may qualify for a free [Yubico for Free Speech](https://www.yubico.com/about/about-us/free-speech-program/).
- Keep less information/data/photos on your devices – you can't lose what you don't have.
- Turn suspicious PDFs into safe ones using [Dangerzone](https://dangerzone.rocks/).
- Access Facebook with more anonymity and/or bypass internet filtering by using [its onion service](https://en.wikipedia.org/wiki/Facebookcorewwwi.onion). 
- If you (or your organization) is really wedded to Google Suite/Workspace, consider [Google's Advance Protection program](https://www.wired.com/story/google-advanced-protection/).
- Put your smart cards/passports/phones in a Faraday bag that blocks signals from going in and out. (See [Micah Lee's guide on them](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
- Use [One Time](https://onetimesecret.com/) to send a password-protected, self-destructing message.
- For iOS users: Download [iVerify](https://www.iverify.io/individuals) to scan your device.
- For Android users: Download apps using [F-Droid](https://f-droid.org), an open-source, security-focused app store.
- Use a more secure operating system on desktop ([Tails](https://tails.boum.org/), [Qubes OS](https://www.qubes-os.org/)) and mobile ([CalyxOS](https://calyxos.org/), [GrapheneOS](https://grapheneos.org/)). 
- Start using more secure devices: [PINE64](https://www.pine64.org/), [Purism](https://puri.sm/). 
- For US residents: Freeze your credit to prevent bad actors from accessing or mis-using your personal information. See IntelTechniques' [Credit Freeze Guide](https://inteltechniques.com/data/workbook.pdf) for details.

---

**🏆 Oh my, you made it this far.  
🏆 You are a true champ!**

---

## 🧠 Other resources

We consulted many sources and drew upon our own experiences in creating this resource. If you're not finding quite what you want here, we recommend checking out these other resources: 

- [Consumer Reports' Security Planner](https://securityplanner.consumerreports.org/)
- [The Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/)

---

## 📝 License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 👋🏾 Special thanks

Special thanks to the [CryptoHarlem](https://twitter.com/cryptoharlem) community, to the students at the School of Journalism and Communication at the Chinese University of Hong Kong, and to [our GitHub contributors](https://github.com/narwhalacademy/zebra-crossing/graphs/contributors).
