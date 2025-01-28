# 🦓 Zebra Crossing: an easy-to-use digital safety checklist

## 🎯 Start here!

### 🤔 Read this guide if you

- Use the internet daily — for work, social media, and financial transactions.
- Want to secure your digital safety and privacy proactively but aren’t in immediate danger. (If you are, reach out to someone in your community for a one-on-one consultation.)
- Feel comfortable with technology — you feel confident about changing the settings on your computer or smartphone.

### 🗺 Where this guide is from

- This guide draws from our work helping individuals and groups upgrade their digital safety practices, and from our experiences living and working in Canada, the US, Germany and Hong Kong.
- Wherever possible, we chose apps and tools that are accessible and easy to use over ones that are technically sophisticated but difficult to use. Our decision is based on our observation that people become clumsier in stressful situations, so it is important to keep procedures as simple as possible.

### 🌱 How to use this guide

- **Start from Level 1 and work your way up!** Recommendations are sorted by increasing levels of difficulty.
- **Level 1 is the quick essentials section.** You should be able to work through it within 1 hour, and chances are, you're already familiar with many of the recommendations in there — but it never hurts to double check.
- **Level 2 digs deeper into your device/app settings and will help you fine tune your privacy online.** This section will take 1-2 hours, depending on how many accounts and devices you frequently use.
- **At a minimum, do everything in Levels 1 and 2.** It'll protect you from the most widely-used attacks while drastically decreasing the amount of personal information you're giving out for free.
- **Level 3 ties up loose ends in your digital safety practice**, but it does requires more time and money to complete. Depending on the amount of digital housekeeping required, this part may take anywhere from 1-4 hours.
- **The scenarios shared after Level 3 are for higher-stakes situations.** Scan them to see if any of them apply to you. (Because the stakes are higher, they assume you’ve done everything in Levels 1–3.)
- **This guide is a living document.** Please feel free to submit a pull request or fork your version of this guide [on GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🗣 Read this guide in other languages

- [繁體中文 (Traditional Chinese)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-繁體中文.md)
- [Deutsch (German)](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Deutsch.md)
- [日本語](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-日本語.md) (Japanese, a work-in-progress)
- [Türkçe](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-T%C3%BCrk%C3%A7e.md) (Turkish, a work-in-progress)
- [Italiano](https://github.com/narwhalacademy/zebra-crossing/blob/main/README-Italiano.md) (Italian, a work-in-progress)
- Looking to contribute another language? [Send us a message](mailto:contact@narwhalacademy.org) to collaborate.

### ☕️ Support this guide

- [Buy us a virtual coffee](https://ko-fi.com/narwhalacademy)
- Share this guide with your friends and community!
- [Send your feedback](mailto:contact@narwhalacademy.org) or [contribute to the guide on GitHub](https://github.com/narwhalacademy/zebra-crossing).

### 🕒 Last updated

- 28 January 2025

---

## 🧐 Useful terms to learn

### 🎯 Threat modeling

**Threat modeling** is a process that allows us to identify potential threats to safeguard against them. To build your threat model, ask yourself the following:

- **“What kind of danger am I in?”** E.g. credit card hacks, corporate espionage, or online harassment/doxxing.
- **“What kind of assets am I protecting?”** E.g. confidential documents, private photos, or personal messages.

Remember though, your threat model can change — either gradually over time or abruptly, say, when a new law is suddenly passed.

### 🔗 Weakest link

The **weakest link** is where your digital safety is most vulnerable. For example, if an account’s forgot password function sends a link to your email, attackers only need to access your email to gain access to the account.

### 🔡 Encryption levels

**Encryption** is the process of scrambling or encoding information to make it unreadable to passers-by and prevent unauthorized access. People often categorize **encryption** into these three types:

1. **No encryption:** Any third party can intercept the data and read it as-is. Often called "plaintext."
2. **Standard encryption:** Data is encrypted so that intercepting third parties cannot read it, but the platform being used to send the data (e.g. Facebook Messenger) can unscramble and read it. The platform may hand the unscrambled data to courts if ordered to do so.
3. **End-to-end encryption:** Only the original sender and receiver can read the data. The platform being used to send the data only has the scrambled, unreadable version. So if courts order the platform to hand over the data, there's nothing useful to hand over.

### 🧩 Metadata

**Metadata** is the contextual information surrounding your data. For example, the metadata for a phone call includes the number you called and the length of your call (but not the call’s contents). With enough metadata, attackers can piece together a relatively reliable picture of who you are, who you know, and where you’re going.

*Unfortunately, legal protections around metadata tend to be weak or nonexistent.*

---

## 🚶🏽‍♀️ Level 1

### ✅ Things to do

#### Identify important accounts

- Imagine that an attacker gains access to all of your online accounts. Which of these accounts would be really painful to lose? List them out and write them down.
- Typically this list includes accounts used for email, online banking, social media, and maybe one or two related to work.
- The list should be short, and have less than 10 items.

#### Double-lock important accounts

The first lock is usually your account password. The second lock takes on a different form and/or comes via a different channel — most often as a code sent to your phone via an app or text message (SMS). This additional lock is usually called *two-factor authentication* (abbreviated as *2FA*) or *two-step verification*.

- **Turn on two-factor authentication for the important accounts** you just identified. To find instructions on how to do so:
  - Run an internet search for `two-factor authentication` and the account name
  - Look up the account provider on [2fa.directory](https://2fa.directory)
- **Use an authenticator app if one is available.** They're more secure than using SMS to receive your 2FA code.
  - Recommended apps:
    - [2FAS](https://2fas.com) (if you only use one device to get authentication codes)
    - [Ente Auth](https://ente.io/auth/) (if you want the codes to sync across multiple devices)
- **Turn on cloud-backup for your authenticator app** in case you ever lose your phone.
  - Instructions for:
    - 2FAS: Go to `Settings → 2FAS Backup`
    - Ente Auth: Create an account in the app

#### Double-check backup security questions on important accounts

- **Make sure the answers to these questions are not easy to find out using public information about you.** Security questions often get used to verify your identity during login or password resets, so they play a crucial role.

#### Secure your email

- **Check the address bar for https://** If you’re using a webmail service, check that you're logging into it using an `https://` URL. If there isn't one available, find a new email provider.
- **Find out if your email service supports backup codes.** Once you turn on 2FA, your email provider may provide single-use backup codes you can use if you lose your phone.
  - Instructions for:
    - [Gmail](https://support.google.com/accounts/answer/1187538?hl=en)
    - [Proton Mail](https://proton.me/support/set-account-recovery-methods#how-to-enable-a-recovery-phrase)
    - [Tuta Mail](https://tuta.com/support#recovery)
    - [iCloud](https://support.apple.com/en-us/HT208072)

#### Secure your phone

- **Use a non-common/obvious unlock code for your phone with at least 10 digits.** We recommend using a long string of numbers as it's easier to tap, but using both letters and numbers works too. Swipe patterns are not recommended, however, as they are too easy replicated by onlookers.
  - To change it:
    - iOS: `Settings → Face ID & Passcode → Change Passcode`
    - Android: `Settings → Security → Screen lock`
- **Set up a pin code for your mobile phone SIM card:**
  - Instructions for:
    - [iPhone](https://support.apple.com/en-us/118228)
    - [Android](https://www.androidpolice.com/enable-sim-lock-android-phone-protection/).
  - If it asks you for a SIM pin code and you don't remember setting one, then the phone company might have set one by default. Go to your phone provider’s website to find out what it is.
- **Don’t allow USB accessories to control a locked device:**
  - iOS: Turn off `Settings → Face ID & Passcode → Allow Access When Locked: USB Accessories`.
  - Android: Setting is off by default and is only available if `Developer Options` are turned on.
- **For iOS devices, make sure `Stolen Device Protection` is turned on:**
  - `Settings → Face ID & Passcode → Stolen Device Protection`

#### Secure your computer

- **Turn on your computer’s firewall:**
  - macOS: `System Preferences → Security & Privacy → Firewall`.
  - Windows 10/11: `Start  → Settings → Update & Security → Windows Security → Firewall & network protection → Microsoft Defender Firewall: On`
- **Turn off your computer’s remote access:**
  - macOS: `System Preferences → Sharing → Remote Login, Remote Management`.
  - Windows 10/11: `Settings → System → Remote Desktop → Remote desktop: Off`.
- **Set up basic anti-virus software on your computer:**
  - macOS: None required.
  - Windows 10/11:  `Start  → Settings → Update & Security → Windows Security → Virus & threat protection`

#### Turn on automatic software updates

Most new devices these days have automatic updates turned on by default, but it’s worth double checking:

- **Check the update settings on your device operating system:**
  - On phones and tablets:
    - iOS: `Settings → General → Software Update → Automatic Updates`
    - Android: `Settings → System → System update`
  - On computers:
    - macOS: `System Settings… → General → Software Update → Automatic Updates`
    - Windows 11: `Start  → Settings  → Windows Update → Advanced options`
    - Windows 10: `Settings → Update & Security → Windows Update → Advanced options`
- **Check the update settings on your device’s main app store:**
  - iOS: `Settings → App Store → Automatic Downloads: App Updates`
  - Android: Open `Play Store`, then go to `Settings → Auto-update apps`
  - macOS: Open `App Store`, then go to `Settings → Automatic Updates`
  - Windows 10/11: Open the `Microsoft Store`, then go to `Profile → Settings → App updates`.

#### Other considerations

- **Turn off app-specific passwords that bypass two-factor authentication (where possible)**.
  - Instructions for:
    - [Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)
    - [iCloud](https://support.apple.com/en-us/HT204397)
- **Turn off automatically added calendar invitations,** which can be used to send malicious links.
  - Google Calendar [Settings](https://calendar.google.com/calendar/r/settings) `→ Event Settings → Add invitations to my calendar: When I respond to the invitation in email`
  - Outlook: `File → Options → Calendar → Automatic accept or decline → Auto Accept/Decline: Automatically Accept Meeting Requests and Remove Canceled Meetings`
  - iCloud: On iOS: Go to `Settings → [Your name] → iCloud → Saved to iCloud: See All → iCloud Calendar → Send & Receive → Receiving` and select `Email` for each account. 
- **Disable macros in Microsoft Office.** Macros are small bits of code that automate actions which can be exploited by attackers. They can still be useful sometimes, which is why we recommend the `Disable all macros with notification`, which allows you to manually allow macros from trusted sources to run.
  - Instructions for:
    - [macOS](https://support.microsoft.com/en-us/office/enable-or-disable-macros-in-office-for-mac-c2494c99-a637-4ce6-9b82-e02cbb85cb96)
    - [Windows](https://support.microsoft.com/en-us/office/macros-in-office-files-12b036fd-d140-4e74-b45e-16fed1a7e5c6), which may require [special settings for Excel](https://support.microsoft.com/en-us/office/change-macro-security-settings-in-excel-a97c09d2-c082-46b8-b19f-e8621e8fe373)

### 💪🏽 Habits to grow

#### Watch out for phishing scams

A phishing scam is an email or text message where an attacker is trying to trick you into giving your password or other login details. To defend yourself:

- **Trust your instincts.** If you feel like something is off — whether it's the way the text is written, the way the graphics look, or an unusual, first-time request from a service provider — it probably is.
- **Check who it's from.** Look over the sender's name and phone number or email address. If it's an email, be sure to closely read the bit after the `@` symbol.
- **But remember sender details can be faked.** It happens rarely, but it is technically possible to put on a fake sender name, email or phone number. So checking the sender details is a not 100% foolproof process.
- **Think twice before clicking a link.** When in doubt, carefully examine the domain in the link. To look at it without opening the link:
  - On mobile:
    - iOS: Tap and hold on a link. A mini preview of the destination will appear. On the top right of this mini-window, tap `Hide preview`. From then on, iOS will show the full URL whenever you tap and hold on a link.
    - Android: Tap and hold on a link.
  - On desktop:
    - Firefox, Chrome, Edge: When your mouse cursor hovers over a link or button, the full URL will show up on the bottom left.
    - macOS Safari: To turn on the above feature, go to `View → Show Status Bar`
    - macOS Mail: Hover your mouse cursor over a link and wait for a few seconds for a pop-up to appear.
- **After clicking links, scan the URL address bar in your web browser.**
  - Is there a red warning icon or 'Not Secure' label? This means the website is running unencrypted on `http` (rather than `https`).
  - Is the domain spelled incorrectly?
- **So if there’s any lingering doubt, don’t click the link.** In almost all cases, you don’t actually need to click the link. If the message is linked to a transaction or account, you can always go to the original website to look up the details.

#### Beware of file attachments

- **Don’t download/open unnecessary attachments.**
  - When in doubt, reply to the original sender to ask what it is.
  - On email, preview attachments within the app or website. On Gmail and Proton Mail, simply clicking the attachment brings up its preview, which runs in a safe environment inside the mail program.
  - Ask the sender to use a filesharing service (Dropbox, Google Drive, Tresorit), which also have their own online preview system.
- **Upload suspicious attachments to [VirusTotal](http://www.virustotal.com)** to have them analyze it. *Keep in mind files submitted to VirusTotal may be shared with multiple security researchers, so don’t submit sensitive information.*

#### Say yes to updates

- **Device operating systems:** If you get a notification on your devices to update the operating system, do it as soon as possible.
- **Apps:** If you see notifications about available updates, follow through and update the app.
- **Firmware updates:** Check occasionally for firmware updates for your router and other internet-connected devices.

#### Other considerations

- **Don’t enter passwords into in-app browsers.** When a mobile app lets you browse a webpage without opening your web browser (i.e. an in-app browser), the app can record what websites you visit and what you type in them. So don’t type anything sensitive in there.
- **Don’t plug in USB sticks/drives that you don’t know into your computer.** It might have malicious software on it.
- **Wipe your devices properly before donating or giving them away.** If you’ve encrypted your phones and computers (as suggested earlier), a standard factory reset will work for most use cases.
  - If you want an extra layer of security for your computer hard drives, see [Wired’s guide on this topic](https://www.wired.co.uk/article/securely-wipe-android-iphone-hard-disk).
- **Don’t charge your phone at public charging stations/ports.** They present a risk because attackers might steal your data. Instead, use a portable battery or bring our own adapter to plug directly into the power outlet.

---

**👍 Great job! You've secured**  
**👍 some important quick wins**  
**👍 for your online safety & privacy.**  
**👍 Please, do treat yourself to**  
**👍 a cup of tea and a stretch.**  
**👍**  
**👍 Now, ready for Level 2?**

---

## 🏃🏻‍♂️ Level 2

### ✅ Things to do

#### Use hard-to-guess passwords for important accounts

Attackers commonly gain access to your account is if your password is:

1. Too short.
2. Too easy to guess.
3. It’s already been leaked as a part of a data breach/hacking incident and you’re use the same password in different places.

So it is crucial to use a different password for every account, and make sure that those passwords are very long and very hard to guess. To help come up with and store these long passwords, you can:

1. Use apps calls password managers.
2. Invent your own formula that’s a wordplay on the service you’re logging into.
3. Write them down with pen and paper.

What works best is different for everyone, and you don’t have to stick to just one  option — feel free to mix and match. For a longer walkthrough and explainer on the three options, see Michael Horowitz’s [The world's BEST password advice](https://michaelhorowitz.com/BestPasswordAdvice.php) article.

For now, **focus on making sure the important accounts you identified in Level 1 have long, unique, hard-to-guess passwords** . Here is a walkthrough of the three options:

##### Option 1: Install a password manager (recommended)

This is a popular option for people who are comfortable navigating extra settings and dialog boxes. A password manager app helps generate long passwords, stores them, and fills them in almost automatically when you log into a website.

- **Recommended password managers:**
  - [1Password](https://1password.com/) 💰
  - [BitWarden](https://bitwarden.com/)
- **We do not recommend password managers that come with your operating system or web browser** because they do not work outside of their ecosystem (e.g. Apple Passwords won’t work on an Android phone).
- **Install the password manager app** on both your phone and computer.
- **Install the password manager browser extension** on your desktop web browser.
- **Only create passwords with more than 12 characters.** We recommend using the option in the password manager that strings together random, unrelated words (e.g. `plant-truck-nose-frame-lace`) so that it's easy to type in those rare instances when the autofill isn't working.
- **Next time you have to type in your password for another account, create an entry for it.** This way, you will gradually add any frequently used accounts into the password manager. If you do this on the computer, the password manager's browser extension/add-on will capture the details automatically after you type them in.
- **Transfer all of your accounts later.** Entering all of your accounts into the password manager will take a while, and is a task best saved for another day. (We've placed this time-consuming task in our `Level 3`.)
- **Don't use your password manager as a two-factor authentication app.** It's better to not put all your eggs in one basket.

##### Option 2: Use a formula

This option is commonly used by people who have strong memorization skills and people who prefer having less apps to manage and dialog boxes to tap on their devices.

Here’s an example of a simple formula from [A Defensive Computing Checklist](https://defensivecomputingchecklist.com/indexold.php#passwoyds):

> …a baseball fan might start every password with "BaseballRules!" Then, if "jungle" was their password for Amazon.com, the actual password is "BaseballRules!jungle" And, all you would have to remember would be that your Amazon password is "jungle". Pretty easy. Amazon. Jungle. And, the miserable password "book" for Barnes and Noble, becomes a good password ("BaseballRules!book") when run through the formula.

Add some extra punctuation marks, dashes and numbers to make the password a little longer and more irregular, and you have a pretty solid password formula.

##### Option 3: Use pen and paper

This option usually supplements the other two options, and is useful for people who rarely ever lose (physical) things. Writing on paper is especially useful if you use a formula and want to note down some hints about the formulas you’ve used.

In fact, password manager apps encourage people to print a sheet of paper with an account recovery code, and then write their master password on it. Here are the instructions for:

- 1Password: [Get to know your Emergency Kit](https://support.1password.com/emergency-kit/)
- BitWarden: [Recovery Codes](https://bitwarden.com/help/two-step-recovery-code/#get-your-recovery-code) (add your master password after printing)

Try to have a backup copy of these papers in a second location.

#### Encrypt your devices

*Remember, encryption is only fully effective when the device is off!*

- **Encrypt your computer hard drive.**
  - Instructions for:
    - [macOS](https://support.apple.com/en-us/HT204837).
    - [Microsoft Windows](https://support.microsoft.com/en-us/windows/device-encryption-in-windows-10-ad5dcf4b-dbe0-2331-228f-7925c2a3012d) (use [BitLocker](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) if it’s available).
- **Encrypt your phone storage.**
  - iOS: Automatically encrypts.
  - Android: Almost always automatically encrypts. Double-check by going to `Settings → Security → Encryption`.
- **Encrypt your backup hard drives.**
  - Instructions for:
    - [macOS (if you use Time Machine)](https://support.apple.com/en-ca/guide/mac-help/mh21241/mac)
    - [Microsoft Windows](https://techjury.net/blog/how-to-encrypt-your-hard-drive/)

#### Make sure your home wifi router is set up right

- **Log into the administration and settings dashboard.** It’s usually accessible by going to `http://192.168.0.1` in your web browser. Otherwise, check your instructions that came with your router.
- **Update the dashboard login if the password is simple.**
- **Review the devices currently connect to your network.** You may have to explore until you find the `access control`. Make sure you know what every device on the list is.
- **Turn off the following options if you see them.** (Look for them under `advanced settings` or `gateway functions`):
  - UPnP (Universal Plug and Play)
  - WPS (Wi-Fi Protected Setup)
  - Remote Management
- **Check for any software updates.** Look for sections labeled `maintenance`, `firmware` or `system update`. Don’t worry if you don’t see it — that means it’s either up-to-date or automatic updates are hard set to on.

##### Track your devices in case you lose them

- **Set up tracking** or `Find My`, which will allow you to remotely find and wipe your devices by logging into a website if you ever lose them.
- Instructions for:
  - [iOS & macOS](https://support.apple.com/en-us/HT210400)
  - [Android](https://support.google.com/android/answer/6160491?hl=en)
  - [Windows](https://support.microsoft.com/en-us/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316)

#### Enhance your privacy

##### On social media & messaging apps

- **Review the privacy settings on social media platforms and messaging apps you frequently use.** Check who can see your content, what information about you is being made public, and what you are sharing with third-party apps/advertisers.
- **Wherever possible, turn off read receipts for messaging apps.** It may seem inconvenient at first, but in the long run you will have more privacy and freedom when people *don't* know if you've read their messages or not. 
- Here are links to and instructions for the most commonly-used platforms/apps:
  - **Platforms/apps with privacy settings available through a desktop browser:**
    - Facebook: [Privacy checkup](https://www.facebook.com/privacy/checkup/)
    - Google: [Privacy checkup](https://myaccount.google.com/intro/privacycheckup)
    - Youtube: [Account privacy](https://www.youtube.com/account_privacy)
    - X/Twitter: [Privacy and safety](https://twitter.com/settings/privacy_and_safety)
    - Reddit: [Safety & privacy](https://www.reddit.com/settings/privacy)
  - **Platforms/apps with privacy settings only fully available through their mobile app:**
    - Instagram: `Settings → Privacy`
    - WhatsApp: `Settings → Account → Privacy`
    - Snapchat: `Settings → Privacy controls`
    - TikTok: `Profile → Settings and privacy → Privacy`
    - Telegram: `Settings → Privacy and Security`
- **Limit how Facebook tracks you on other websites** by clearing and disconnecting [Off-Facebook activity](https://www.facebook.com/off_facebook_activity).

##### On email & social media accounts

- **Review `Third-Party Apps` or `Connected Apps` linked to major social media/email platforms.** These third-party/connected apps have access to your data, and they might be selling it.
- Instructions for:
  - [Google](https://support.google.com/accounts/answer/3466521?hl=en)
  - [Facebook](https://www.facebook.com/help/211829542181913)
  - [Instagram](https://www.facebook.com/help/instagram/1144624522593085)
  - [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps)

##### On your phone

- **Review which apps on your smartphone have access to your location data.** Turn off access for the apps that don’t need it, and minimize the number of apps tracking your location.
  - iOS: `Settings → Privacy & Security → Location Services`
  - Android: `Settings → Location → App location permissions`
- **Turn off your unique advertising ID number** so that advertisers can't pinpoint you as easily:
  - iOS: `Settings → Privacy & Security → Tracking → Allow Apps to Request to Track: Off`
  - iOS: `Settings → Privacy & Security → Apple Advertising → Personalized Ads: Off`
  - Android: `Settings → Security & Privacy → Privacy → Ads → Delete advertising ID`
- **On Android, turn off passive Wi-Fi and Bluetooth scanning.**
  - `Settings → Location → Location services → Wi-Fi scanning`
  - `Settings → Location → Location services → Bluetooth scanning`
- **Delete any apps that you don’t recognize or haven’t used in a long time.** You can always re-download any of them if need be, though there will be a few apps that come with the operating system that cannot be deleted.
  - **Make sure to look for hidden apps as well.** Instructions for:
    - iOS: On the home screen, keep swiping left until you get to the `App Library` screen. Scroll to the bottom to the `Hidden` group. Tap to open and unlock using Face ID or passcode.
    - Android: See all apps including hidden ones in `Settings → Apps → See all apps`
- **Delete third-party keyboards on your phone.** They often share what you type with the software maker.
  - These keyboards are installed as apps on iOS and Android, so take the time to scan through all of your installed apps to find and delete them.
  - If you need to use a third-party keyboard, make sure it’s an open-source project that others have verified and does not share your data with third parties.

##### On your computer

- **Disable ad tracking for computers running Windows.** Instructions for:
  - [Windows 10](https://privacyinternational.org/guide-step/4344/opt-out-targeted-ads-windows)
  - [Windows 11](https://www.pcmag.com/how-to/how-to-remove-annoying-ads-from-windows-11)

##### On your mobile/computer web browsers

- **Review your web browser's privacy settings**
  - On your mobile:
    - iOS Safari: `[iOS] Settings → Apps → Safari → Privacy & Security`. Make sure `Prevent Cross-Site Tracking` , `Hide IP Address` and `Fraudulent Website Warning` are on. 
    - Android Chrome: `[Chrome] Settings → Privacy and security`, turn on `Safe Browsing` (either option), `Always use secure connections`, `Do Not Track`
    - Android Firefox: `[Firefox] Settings → Privacy and security`, turn on `HTTPS-Only Mode`, `Enhanced Tracking Protection`
  - On your computer:
    - macOS Safari: `Preferences → Privacy`, tick the checkboxes for `Website tracking` and `Hide IP address`
    - macOS/Windows Chrome: `Preferences → Privacy and security → Cookies and other site data`, turn on `Block third-party cookies`, `Do not track`
    - macOS/Windows Firefox: `Preferences → Privacy & Security`, turn on `Enhanced Tracking Protection` (any option), `Do Not Track` and `HTTPS-Only Mode` (scroll to the bottom)
- **Install these web browser extensions/add-ons** if your browser supports it. Make sure they’re on even during private/incognito mode. The following extensions/add-ons are available for Firefox (macOS, Windows, Android) and Chrome (macOS, Windows):
  - [uBlock Origin](https://ublockorigin.com/), which blocks invasive ads.
  - [Privacy Badger](https://privacybadger.org/), which blocks trackers.
  - [Decentraleyes](https://decentraleyes.org/), which decrease tracking on commonly-used resource files.
- **Review your other web browser extensions/add-ons.** Delete any that you haven’t used in a while or don’t remember installing.

##### On other internet-connected devices

- **If you use smart speakers, turn off their recording function.**
  - **Google Home:** go to [Activity Controls](https://myaccount.google.com/activitycontrols/audio) and uncheck `Include audio recordings`.
  - **Amazon Alexa:** [Follow these instructions](https://www.digitaltrends.com/home/how-to-stop-amazon-from-listening-to-your-alexa-recordings/).
- **For an Amazon Ring or Echo, turn off the feature that shares your internet with strangers.**
  - **In the Alexa app:** `Settings → Account Settings → Amazon Sidewalk`
- **For smart TVs, make sure to turn off the manufacturer's data tracking functionality,** also known as automatic content recognition (ACR).
  - Instructions from: [Consumer Reports](https://www.consumerreports.org/privacy/how-to-turn-off-smart-tv-snooping-features-a4840102036/) 

##### Other considerations

- **Review what data these platforms have on you.** Delete out anything you don't need, if there are options to do so.
  - **Google:** [My Activity](https://myactivity.google.com)
  - **Facebook:** [Your Facebook information](https://www.facebook.com/settings?tab=your_facebook_information)
  - **Amazon:** [Alexa Privacy Settings](https://www.amazon.com/b/?node=19149164011)
  - **Microsoft:** [Account Privacy](https://account.microsoft.com/privacy)

### 💪🏽 Habits to grow

#### Enhance your privacy

- **Post less personal information online.** This includes information that can be used to identify/track/scam you (addresses, phone numbers, birthday, etc.).
- **Set up a separate account under a pen name to leave local business reviews** (on Google Maps, Yelp, etc.) if you write many of them. Otherwise, reviews will be shown under your real name and possibly give away your home location.
- **When registering domains, make sure WHOIS/domain privacy is turned on.** Many domain name registrars and webhosts offer this feature for free. *Note: There are unofficial WHOIS lookup/history tools out there that make it hard to remove your information from the history log once you’ve entered it at an earlier point in time.*

#### Watch what you say in online groups

**Don’t say anything you’d regret on in a “private” group** on Slack, Discord, Facebook, WhatsApp group chat, Telegram channel, or any “private” online forum. Here’s why:

1. **Anyone in the group can leak the data.**
2. **Administrators usually have access to everything within the group,** including deleted messages and private direct messages between two people.
3. **What you say can be traced back to your account's phone number or email.** Even if you're not using your real name or photo.
   - To prevent this in Telegram, go into `Settings → Privacy and Security → Phone Number`, and then set:
     - `Who can see my phone number` to `Nobody`.
     - `Who can find me by my number` to `My Contacts`.

#### Know when your name publicly appears as a supporter or donor

**Always check whether your name appears publicly online for subscriptions, crowdfunds, petitions and donations.** This is especially relevant if you have a unique name.

Some platforms that facilitate these things often have privacy settings, so it’s best to create an account with them to gain some control over what appears publicly. Some examples of important but often overlooked privacy settings:

- **Patreon:** `Settings → Accounts → Privacy`: Turn off both `Full public profile` and `Community profile`.
- **Indiegogo:** In the menu, go to `My Campaigns`. If you want to hide a project from your public profile:
  - Under `Campaigns I've Funded`,  select `Actions: Hide contribution`.
  - Then the page refreshes, but the project has simply moved down to `Campaigns I’m Following`. There, select `Actions: Unfollow`. 
- **GoFundMe:** In the menu, go to `Your impact`. Then go to any campaign you’ve supported. There, under `Your donations`, you can change whether your name appears publicly.

#### Other considerations

- **Restart your phone and computer once a week by turning it off and then back on** to clean up its temporary memory (RAM) and so it runs smoother.
- **When downloading a new mobile app, double-check to confirm it’s the right one.** Many fake apps trick people by using a slightly modified name or icon of an existing, popular app.
- **Regularly check the installed apps on your phone.** Delete the ones you’re no longer using.
- **Need to send someone a password? Split it in half and send it via two different channels.** For example, send half of the password through email and the other half via a voice call.
- **Don’t use Google/X/Twitter/Facebook to sign up or log into other services,** which gives these platforms unnecessary data about you. Each service should have its account.

---

**🎉 Congratulations! You dove**  
**🎉 fearlessly into your settings,**  
**🎉 clicking, tapping, swiping,**  
**🎉 which makes you a very, very**  
**🎉 above average human being.**  
**🎉 Now, you deserve a day off.**  
**🎉**  
**🎉 When you come back,**    
**🎉 be prepared to join**  
**🎉 the upper ranks of safety**  
**🎉 as you enter Level 3.**

---

## 🧗🏿‍♀️ Level 3

### ✅ Things to do

#### Put an extra lock on sensitive files

- **Identify files you don’t want others to access.** This may include private photos, passport scans, and financial documents.
- **For files on your computer, create an encrypted, password-protected vault for your files:**
  - Recommended tool: [Cryptomator](https://cryptomator.org/).
  - Storing your vault on the cloud or on your computer are both fine. Decide based on how you’d like to backup the vault.
  - Move your files into this secure vault. Make sure to delete the original copies after they’ve been moved into the vault.
- **For documents on your phone, there are several options:**
  - Create a similar vault using an app like [Cryptomator](https://cryptomator.org/)(💰 for mobile).
  - If you’re on a paid plan for a password manager, the apps also let you store files in a section called `documents` or `attachments`. 💰
  - iOS Files app has a  `Lock PDF` feature for individual files.
  - Android Files by Google allows you to create a `Safe Folder` by [following these instructions](https://support.google.com/files/answer/9935264).
- **For photos and videos on your phone, use the features in your default photos apps:**
  - iOS Photos: Open the photo and tap the `…`  button on the top right. Tap `Hide`. This will put the photo in a `Hidden` folder in the Photos app (under `Utilites`) that can only be unlocked with FaceID or a passcode.
  - Android Google Photos: [Follow these instructions](https://support.google.com/photos/answer/10694388?co=GENIE.Platform%3DAndroid&oco=1) and read the section about automatic backups carefully.
  - Android Gallery: The basic Gallery app doesn’t support hidden photos, so download an alternative gallery app like [Fossify Gallery](https://github.com/FossifyOrg/Gallery) and turn on password protection for hidden items in the settings.
#### Upgrade your gear 💰

- **Buy a privacy screen for your laptop and phone.** These stick-on sheets prevent onlookers from seeing what's on your screen. Examples for:
  - Laptops: [3M Privacy Filters](https://www.3m.com/3M/en_US/p/c/office-supplies/workstation-accessories/screen-filters-protectors/laptop-filters/)
  - iPhone: [Spigen EZ FIT GLAS.tR Privacy](https://www.spigen.com/collections/iphone-13-pro/products/iphone-13-pro-screen-protector-ez-fit-glas-tr-privacy)
- **Place a sticker (or webcam cover) over your laptop’s front-facing camera.**
  - If you buy a webcam cover for a laptop, make sure it is less than 0.1mm thick so that it doesn't affect how the laptop closes.
- **Don't use devices your workplace gives you for personal things.** Either have separate devices for your work and personal lives, or, if it's too troublesome to have multiple devices, use your personal device for everything. Devices set up by workplaces often have monitoring systems that can be misused during disputes.
- **Buy a mobile phone that always gets the latest software updates.** Recommended phones:
  - Apple iPhone
  - Google Pixel Android
- **Use a paid VPN service** both when you're on a public network (e.g. café) and when you're at home (to decrease data shared with your internet/phone company).
  - Avoid free VPN services because free services often make their money back by selling your data.
  - Recommended VPNs: [Mullvad](https://mullvad.net), [IVPN](https://www.ivpn.net/)💰
  - *Note that though the iCloud Private Relay is similar to a VPN, it only applies to traffic through the Safari web browser.*

#### Disable 2G connectivity on your phone (Android only)

2G cellular network technology is outdated and has security vulunerabilities that allow fraudsters to send fake text messages. To disable it on Android:

- `Settings → Network and Internet → SIMs → [Your carrier name] → Allow 2G: Off`
- If that option doesn’t appear, open the Phone app and enter `*#*#4636#*#*`. A `Testing` screen will pop up. Select `Phone information` and then change the `Set Preferred Network Type` to the same as the current selection minus `GSM`. To see what each acronymn stands for, see Wikipedia’s [Comparison of wireless standards page](https://en.wikipedia.org/wiki/Comparison_of_mobile_phone_standards#Comparison_of_wireless_Internet_standards). 

#### Use end-to-end encrypted apps

##### For secure messaging & calls

- **Use apps with open source end-to-end encryption protocols and easy-to-use disappearing message timers.**
  - Recommended apps:
    - [Signal](https://signal.org/): Sign up with a phone number.
    - [Wire](https://wire.com/): Sign up with an email address.
  - Set messages to disappear. Pick an interval that’s comfortable for you.
    - **Signal:** Go to `Settings → Privacy →  Disappearing Messages → Default Timer for New Chats`.
    - **Wire:** No app-wide setting exists. You have to set it up for each conversation by tapping/clicking the timer icon ⏱.
  - These apps also end-to-end encrypt video and voice calls, so continue using them wherever possible.
- **End-to-end encryption for video/voice calls with more than 5 people may not be worth it.** There are several reasons:
  - Privacy is hard to maintain in large group calls as they often become quasi-public events due to the large number of participants.
  - Support for end-to-end encrypted video/voice calls for larger groups is limited, and most platforms still collect the metadata around your call even when end-to-end encryption is switched on.

##### For online file-sharing and backup

- **Store and share files on the cloud using end-to-end encryption.**
  - Recommended apps: [Tresorit](https://tresorit.com/), [Proton Drive](https://proton.me/drive) 💰
  - For iCloud: Turn on Advanced Data Protection. [See Apple’s instructions](https://support.apple.com/en-us/HT212520).
  - *Remember: files stored on Dropbox and Google Drive are not end-to-end encrypted.*
- **Backup your files online using an end-to-end encrypted platform.**
  - Recommended app: [Arq](https://www.arqbackup.com/)  💰

#### Further secure your messaging apps

##### Be aware of what other people can see in a group chat

Messaging apps use either your phone number or a username as the unique identifier (which other people use to add you on the platform). As such, **your phone number or username is then visible to anyone you're in a group chat with**, along with the name and photo in your profile.

Here's a breakdown of what unique identifiers is visible to others in a group chat on popular messaging apps:

- **Signal:** phone number by default if you’re the recipient’s address book already, no unique identifier if not (but you can set up a username and stop sharing your phone number altogether)
- **Wire:** username (no one else can see the email or phone number you used to register your account)
- **Telegram:** phone number by default (but you can set up a username and stop sharing your phone number)
- **WhatsApp:** phone number

If you don't want to give out your personal phone number, consider getting a virtual phone number from one of the providers listed in our scenario for `Masking your identity for online dating, events, or organizing`.

##### Use app-specific safety & privacy features

###### Signal

- **Set up a username** so people can find you with it rather than your phone number. To create a username:
  - `Settings →` [Tap your profile icon or name] `→ @ Username`
- **Hide your phone number.**
  - Go to `Settings → Privacy → Phone Number`, and set both to `Nobody`.
- **Turn on the extra layer of pin code protection** and prevent others from logging in with your phone number.
  - `Settings → Account → Signal PIN`
  - `Settings → Account → Registration Lock: On`

###### Telegram

- **Turn on two-step verification**  to prevent someone from moving your account without your permission.
  - `Settings → Privacy and Security → Two-Step Verification`
- **Hide your phone number:**
  - `Settings → Privacy and Security → Phone Number`, and then set `Who can see my phone number` to `Nobody`.
- **Start conversations by using `New Secret Chat` so that they are end-to-end encrypted.** All other conversations and groups are not. *Unfortunately, that this means your messages will not show up in your desktop or web app.*

###### WhatsApp

- **Turn on security notifications on WhatsApp** to get a notification when a person you're talking to switches to a new device.
  - `Settings → Account → Security → Show Security Notifications on This Phone: On`
- **Turn on two-step verification** to prevent someone from moving your account without your permission:
  - `Settings → Account → Two-Step Verification: Enable`
- **If you backup chats, make sure they are end-to-end encrypted,** or turn backup off altogether.
  - `Settings → Chats → Chat Backup → End-to-end Encrypted Backup`
  - For iOS users who use `iCloud Backup` (not end-to-end encrypted) to backup their entire phone, make sure WhatsApp is not included as part of the process. This `iCloud Backup` should not be confused with WhatsApp's interal backup feature that also uses iCloud. 
    - `[iOS] Settings →` Your name `→ iCloud → Manage Storage → Backups →` device `→ WhatsApp: Off`
- **Stop automatically downloading any and all photos and videos your receive:**
  - `Settings → Chats → Save to Camera Roll: Off`

#### Learn about your phone’s Emergency SOS feature

- iOS: `Settings → Emergency SOS`
- Android: `Settings → Safety & emergency → Emergency SOS`

#### Secure the rest of your passwords

You made unique passwords for important accounts in `Level 2`, now it’s time to deal with the rest of your online accounts.

- **Make a list of any active accounts and any accounts with your private information.** Don’t worry about finding every last account, you can always deal with them later.
- **If you no longer use the account, consider logging in to deactivate/delete it.** A few accounts might have sentimental value, but most won’t.
- **For the accounts you want to keep, make sure each of them uses a unique, hard-to-guess password.** Review our `Level 2` recommendations about making good passwords if need be.
  - If you are using a password manager, now is the time to transfer everything onto there:
    - The fastest way to enter the details is to logout and login to each account on your computer, and let the password manager's browser extension/add-on capture the details automatically.
    - In some cases, the password manager may warn you that the password you have is weak. If so, spend that extra minute on the account website to change to a new password.
    - When you’re all done, use your password manager’s monitoring feature to double check stored passwords to see if it's too short, has been reused, or has already been leaked as part of a data breach. In 1Password, this feature is called `Watchtower`, and in Bitwarden it’s called `Vault Health Report`.

---

**😲 Wow, you really did it.**  
**😲 You finished all 3 levels!**  
**😲 You deserve a reward —**  
**😲 a cookie, perhaps,**  
**😲 but not the tracking type.**  
**😲**  
**😲 Rest for the rest of the week**  
**😲 and when you're well rested,**  
**😲 come back and check out**  
**😲 the scenarios below.**

---

## 🤹🏻 Scenarios

---

### 👤 Masking your identity for online dating, events, or organizing

#### Don't use your full name

- **Consider using a nickname** or only your first name (if your first name is common where you live). This is especially important if your full name is very unique, which makes it very easy to search for online.
- **Consider using a persistent pseudonym or collective identity,** especially if you’re a public figure. For more information on how and why, see:
  - Tactical Tech: [Zen and the art of making tech work for you](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Creating_and_managing_identities_online)

#### Get a secondary phone number

For messaging apps using phone numbers as the primary identifier (e.g. Signal, WhatsApp, Telegram), get a secondary number from:

- **Paid online services 💰** (more reliable)
  - [Hushed:](https://hushed.com): Offers US, Canada, and UK numbers
  - [Burner:](https://www.burnerapp.com/): Offers US and Canada numbers
- **Free online services 🆓**
  - [TextNow:](https://www.textnow.com/): Offers ad-supported US and Canada numbers
  - [Google Voice:](https://voice.google.com/about): Offers a free US number, but is only available in the US
- **Your local phone companies 💰**
  - Get a prepaid or cheap SIM card plan

*Note: If you lose/unsubscribe to your secondary phone number, other people can buy it and impersonate you.*

#### Get an email alias

For sites and services that use email as the primary identifier/username, get a new 🆓 email account or an email alias that forwards to your main account from:

- [SimpleLogin:](https://simplelogin.io): Based in Switzerland (as part of the Proton Mail/VPN group)
- [addy.io](https://addy.io): Based in the UK and EU

#### Buy things online anonymously

- **Sign up for a privacy-focused virtual credit card 💰** from [Privacy](https://privacy.com/) (only available in the US). It helps a) mask who you are to the seller, and b) mask what you've bought from the bank.
- **Buy a prepaid credit card at a local convenience store.** But be careful, these cards don’t always work for online shopping depending on where you are.
- **Get a virtual credit card for free trials** at [Do Not Pay](https://donotpay.com/learn/virtual-credit-cards/) for those cases where you want to sign up for a free service period but not give out your real credit card information.
- **Ask to be paid in gift cards**, which can be used in stores without tracking.

#### Create an untraceable online alias

Even with all the third-party services above, courts can still compel companies to hand over information about you. So if you are really in a high-risk situation, you may need to do all of the above and more. For one example of this, see Matt Mitchell's [PRIVACY RECIPE: Creating an online persona](https://geminiimatt.medium.com/creating-an-online-persona-deb4cd8c7f46).

---

### ✊🏾 Attending a protest

When it comes to attending a protest, there are many, many considerations depending on where you are and who you are. In this guide, we are only going to make general recommendations related to technology.

#### Things to do before you go

##### Keep communications private

- **Use an end-to-end encrypted messaging app and make sure disappearing messages is turned on.** See the encrypted messaging app part of `Level 3` above.
- **Double-check the privacy settings in your messaging apps.**
- **Turn off message previews in your notifications.**
  - **iOS:** `Settings → Notifications → Show Previews: When Unlocked`.
  - **Android:** `Settings → Apps & notifications → Notifications → Notifications on lock screen → Sensitive notifications: Off`.
- **Restart your phone by turning it off and then back on** to clean up its temporary memory (RAM) and so it runs smoother.

##### Minimize location tracking on your phone

- **Turn off location history:**
  - iOS: `Settings → Privacy & Security → Location Services → System Services → Significant Locations`.
  - Android: `Settings → Security and privacy → More privacy settings → Activity controls →  Location History.`
  - Google Maps: Tap your profile picture `→ Settings → Maps history → Saving to Web & App Activity → Turn off: Turn off and delete activity`.
- **Delete past location history:**
  - iOS: `Settings → Privacy → Location Services → System Services → Significant Locations → Clear History`.
  - Android: `Settings → Security and privacy → More privacy settings → Activity controls →  Location History.`
- **Consider turning off all location services temporarily:**
  - iPhone: `Settings → Privacy → Location Services → Location Services: Off`.
  - Android: `Settings → Location → Use location: Off`.

##### Disable 2G on your phone to decrease tracking

**Your location can be tracked by third parties through your phone’s SIM card connection.** Tracking is done using devices (often called IMSI catchers) that simulate mobile-phone towers, which log both your SIM card’s unique identity number and rough location. To preserve your privacy completely, you’d have to turn off your phone or set up a burner phone. To limit the amount of tracking, disable 2G on your phone:

- Android: `Settings → Network and Internet → SIMs → [Your carrier name] → Allow 2G: Off`.
- Android alternative: If that option doesn’t appear, open the Phone app and enter `*#*#4636#*#*`. A `Testing` screen will pop up. Select `Phone information` and then change the `Set Preferred Network Type` to the same as the current selection minus `GSM`. To see what each acronymn stands for, see Wikipedia’s [Comparison of mobile phone standards page](https://en.wikipedia.org/wiki/Comparison_of_mobile_phone_standards). 
- On iOS: Turn on Lockdown Mode by going to `Settings → Privacy & Security → Lockdown Mode: On`. This launches a range of restrictive safety precautions (including disabling 2G) that you’ll probably want to turn it off after you return home safetly.

##### Other considerations

- **Draft a message to a trusted friend or legal hotline beforehand.** Prepare to hit send if arrested at the protest or if there’s an emergency.
- **As a backup, write down the phone number of the trusted friend/hotline on your arm** with a permanent marker.
- **Charge your phone fully and bring a spare battery.**
- **Clean out any sensitive personal information on your phone.** Delete any photos, chat logs, and notes that can be used against you.
- **If you use your fingerprint or face to unlock your phone, turn it off before the protest.** In some jurisdictions, officers can compel you to provide your fingerprint but not your passcode.
- **Dress up to *not* stand out.** Wear plain clothes that don't attract attention, cover up visible tattoos, and put on a face mask. Make it harder to be easily identified from a photo and by facial recognition technology.

##### Get a burner phone only if you really need it

- **A burner phone is a single-use, disposable phone and SIM card that you buy with cash.** Ideally, it makes you anonymous to the phone company and online services, and not reveal information about you if someone takes or steals your phone.
- **Burner phones require extra time and money to set up.** For example, see [Micah Lee's guide](https://theintercept.com/2020/06/15/protest-tech-safety-burner-phone/) on setting one up in the US.
- **Decide what you want to use a burner phone for, and what that use might reveal about you.** Every action you perform with your phone creates a clue about who you are. E.g. if you activate it at home, it will give away your home address.
- **Do you need a burner phone and SIM card *or* do you just need a burner virtual phone number?** For the latter, see the scenario above: `Masking your identity for online dating, events, or organizing`.

#### Remember when you're out

- **Power off your phone if there's risk of an imminent arrest or phone seizure.** Encryption works best when devices are off.

##### Respect privacy when taking photos and videos

- **Try not to take photos or videos where people’s faces are visible.** Taking a photo of people’s backs is okay. *The one exception is if you’re filming a video of a conflict where documentation is critical.*
- **If there are faces captured in a photo/video, make sure to blur them before sharing them online.**
  - Recommended tools:
    - Phone: [Signal’s photo blur tool](https://signal.org/blog/blur-tools)
    - Computer: Everest Pipkin’s [Image Scrubber](https://everestpipkin.github.io/image-scrubber/)
    - Computer: YouTube’s [blur faces tool](https://support.google.com/youtube/answer/9057652?hl=en)
- **For further anonymity, erase the location metadata before sharing a photo/video.**
  - Recommended tools:
    - Computer: Everest Pipkin’s [Image Scrubber](https://everestpipkin.github.io/image-scrubber/)
    - iPhone: Take a screenshot of the photo and share the screenshot
    - Android: [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)

##### Help others with their emergency medical information

- **If someone has fainted from heatstroke, check to see if they carry their emergency medical information with them.** This information might be:
  - On a medical identification tag, wrist bracelet, neck chain or wallet card. There is usually a name and phone number on it, and sometimes even a QR code.
  - On their phone:
    - iPhone: Open the lock screen, tap `Emergency` in the bottom left corner, and then `Medical ID` on the bottom left corner.
    - Android: Open the lock screen, tap `Emergency` at the bottom.

---

### 🫶🏾 Organizing a mutual aid group

Mutual aid groups often include people with different backgrounds, so it’s very likely that at least one person in the group won’t be up-to-date on their digital safety practices. So the chances of an accidental data leak are much higher. Luckily, there are things you can do to minimize the damage done if that happens.

- **Obscure your identity in the group**:
  - Consider using a nickname or only your first name (if your first name is very common where you live).
  - Don’t use a photo of yourself as your profile picture. Use a photo of an animal, cartoon character, etc.
- **Split up who has access to your group’s private data** (e.g. community contact details and shared passwords). Not everyone needs access to everything. Here are some ways to split up who can access what:
  - **Create different access level groups**. Access can be based on how long someone has been in the group, how good they are with technology, or which projects they are working on.
  - **Fragment a document into pieces.** Make it so that different people have access to different parts of the document.
  - **Assign one or two people as the documents/data managers.** But make sure that these people are well-versed in digital safety practices and stay home during risky public gatherings.
- **Don’t use email to communicate, only use it to sign up for accounts.** Emails create metadata trails and tend to sit in people’s accounts for too long. 
- **If you and your group plan on gathering publicly and in-person**, consider the recommendations in the scenario `Attending a protest`.
- **If your work includes being visible to the public** (you help people in public spaces or appear on video interviews), consider taking your photo and full name off of your employer or school websites. This is to prevent people who disagree with your group from harassing your employer or school.

#### Picking a chat app for closed, private groups

Sometimes you will have to compromise on using the most technically secure app to using one that people are already familiar with. The one baseline requirement that’s worth fighting for is to **use an app with support for disappearing messages** (and to make sure it’s turned on). 

We recommend:

- **[Signal](https://www.signal.org/)**:
  - ✅ End-to-end encrypted group chats.
  - ❌ Cannot delete a group chat.
  - ✅ People in the chat can only see your phone number if it’s already in their phone’s address book by default, and you can even turn that off:
    - Go to `Settings → Privacy → Phone Number`, and set both to `Nobody`.
  - ✅ Supports audio & video group calls
  - Turn on disappearing messages:
    - In the chat, tap the group name at the top of the screen and then selecting `Disappearing Messages`.
- **[Wire](https://app.wire.com/auth/#/)**:
  - ✅ End-to-end encrypted group chats.
  - ✅ Only shows your username to other people in the chat.
  - ✅ Can delete a group chat.
  - ❌ Requires paid plan for audio & video group calls.
  - Turn on disappearing messages:
    - In the chat, tap the timer icon ⏱ at the bottom of the screen.

We don’t currently recommend Telegram, but it remains a popular choice for group chats. So we’ve included notes below on how to use it more safely:

- **[Telegram](https://telegram.org/)**:
  - ❌ No end-to-end encrypted group chats.
  - ❌ Hard-to-find settings to hide phone number.
  - ❌ Hard to turn on disappearing messages.
  - To hide your phone number:
    - Go to `Settings → Privacy and Security → Phone Number`, and then set:
      - `Who can see my phone number` to `Nobody`.
      - `Who can find me by my number` to `My Contacts`.
  - Turn on disappearing messages by: 
    - In the chat, tap the group name at the top of the screen, then tap the three dots at the top right of the screen, then tap `Auto-Delete`. 

We do not recommend using WhatsApp at all. While its group chats are end-to-end encrypted, there are many downsides:

- ❌ Your contacts list is sent to Meta/Facebook.
- ❌ All chat metadata is sent to Meta/Facebook.
- ❌ Everyone in the chat can see your phone number.
- ❌ By default, it automatically downloads all shared images and videos.
- ❌ By default, its chat backups aren’t end-to-end encrypted.

##### Picking an app to broadcast updates

Groups often use social media platforms (e.g. Instagram, X/Twitter) to post updates about their work. One popular alternative is to use [Telegram](https://telegram.org/)’s Channels to broadcast messages one-way to a large audience (with no comments or replies). The advantages of Telegram Channels:

- You can create a publicly searchable or private invite-only channel.
- Followers/readers subscribe to your channel and receive all of the updates (compared to traditional social media where you have to compete for attention and reach).

##### Picking an app for big-group public outreach

When your group grows, it may make sense to set up a more public online space to work with new members. Groups often migrate to platforms like [Slack](https://slack.com/), [Mattermost](https://mattermost.com/) and [Discord](https://discord.com/), which allow for multiple chatrooms within the same space. However, because these platforms are designed for corporate workplaces or public gaming communities, their privacy features are very limited. So we recommend using these platforms only for public outreach or for quasi-public messaging.

##### Picking an app for group video calls

Video call apps are tricky because not many of them support end-to-end encryption, and even those that do often collect your metadata. Having said that here is what we recommend:

- **For small groups of ten or less, use [Signal](https://www.signal.org/)**. Its calls are end-to-end encrypted and it doesn’t collect any metadata. Unfortunately, it doesn’t work well with slower internet connections and only allows a maximum of 40 people on a call.
- **For larger groups:**
  - If you have a technical group member who is skilled at system administration, set up your own [BigBlueButton](https://bigbluebutton.org/) or [Jitsi](https://jitsi.org/) server. Encryption matters less when you control the data (i.e. you can delete it after each call).
  - Otherwise, fall back on big tech platforms [Zoom](https://zoom.us/) or [Google Meet](https://meet.google.com/). (Zoom might seem like a safer bet because of its [end-to-end encryption feature](https://support.zoom.us/hc/en-us/articles/360048660871-End-to-end-E2E-encryption-for-meetings), but it also has a [poor track record of security issues](https://www.tomsguide.com/news/zoom-security-privacy-woes).) Remember though, both platforms collect your metadata and the host has to have a registered account.

##### How to pick collaboration apps/platforms

There are two paths groups take when it comes to picking collaboration apps/platforms:

1. Use Google’s apps because they’re more accessible.
2. Use open-source alternatives because they have better privacy features.

Here’s the rundown on both of these paths.

###### 1. Using Google Workspace more safely

Google Workplace (Docs, Sheets, Drive, etc.) is a popular choice for collaborative work because its apps are powerful, easy-to-use and work well on mobile devices. But they also carry serious privacy limitations:

1. Anyone who opens a document or file can see the creator’s profile picture, name and email address tied to their Google account.
2. The activity log on documents also shows the details of who has made edits.
3. None of your data is end-to-end encrypted.

To mitigate these pitfalls:

- Create a view-only webpage of your Google document or spreadsheet by going to `File → Share → Publish to web`. It’s hosted for free by Google, and doesn’t show who is creator is. (Unfortunately, this feature is available on the computer and not on mobile devices.)
- Obscure your identity:
  - Create a separate Google account under a fake name to create documents and upload files.
  - Edit your own Google account profile to use a nick name or only your first same. Unfortunately, this changes how your name is displayed on all Google apps (including Gmail). 
  - Open a private/incognito window when editing other people’s documents.

###### 2. Using open-source alternatives

Our recommended apps/platforms with notes about their accessibility limitations:

- **[Riseup Pad:](https://pad.riseup.net/)** A browser-based text editor that doesn’t require any accounts. But this anonymity comes with limitations: anyone with the link can edit/delete the pad, pads will auto-delete after 60 days of inactivity and have a maximum lifespan of one year (so remember to backup).
- **[Cryptpad:](https://cryptpad.fr/)** A browser-based platform that has apps for end-to-end encrypted text editing, spreadsheets and slides. The only downside is that people may experience loading problems on mobile devices.
- **[Tresorit Send](https://send.tresorit.com/)**  is a website that allows you to upload end-to-end encrypted files (up to 5 GB) and share them with a link. No account registration needed, but there’s also no way to update the files in the link. 
- **[CryptDrive](https://cryptpad.fr/drive/)** and **[Proton Drive](https://proton.me/drive)** are both Google Drive alternatives that are a bit more private. They allow you to store files and folders online, share them with a link and update them afterwards. Unlike Google Drive, sharing a link won’t show your username or email, but both platforms do require you to have an account, which means the files are ultimately still traceable to you on the server side. Free plans come with 1 GB and 5 GB of storage respectively.

--- 

### 🩸 Accessing reproductive health services privately

Getting the care you need can be a controversial and fraught endeavor in many parts of the world. Here are some recommendations that may apply if you live in one of those places.

#### Researching information

- **Look up health information without being tracked using [Tor Browser](https://www.torproject.org/download/).** It doesn’t work well for websites requiring login, but you shouldn’t be logging in anyway to prevent tracking. There is no official iOS app because it leaks a bit of data, so use the computer version if you’re an iPhone user.
- **If you need to login to an account, be aware there will be a data trail and work to minimize it:**
  - **Hide what websites your visit from your internet provider by using a VPN**.
    - Recommended 💰 VPNs: [Mullvad](https://mullvad.net),  [IVPN](https://www.ivpn.net/) 
    - Recommended free VPN: [Proton VPN](https://protonvpn.com/free-vpn) (free for one device)
  - **Minimize what websites can see by opening up a private/incognito window on your web browser**. This also makes sure your browsing history isn't saved to your device. Alternately, use a different browser in private mode only for health research to further compartmentalize data.
- **Think twice before sharing information,** and when you do, use an end-to-end encrypted messaging app with disappearing messages on. (Avoid email.)

#### Discussing information with friends
 
- **Use end-to-end encrypted messaging apps** recommended in the `Level 3: Use end-to-end encrypted apps` section, and remember to turn on disappearing messages.
- Do not use email or other messaging apps that create a data trail.

#### Tracking your period

- **Use an app that stores your data locally or use pen and paper.**
  - Recommended apps: [Euki](https://eukiapp.com/), [drip](https://dripapp.org/)
  - iOS: If you use iCloud Backup, turn it off for this app: 
    - `Settings → `Your name` → iCloud → Manage Storage → Backups → `Your device` → Euki: Off`

#### Interacting with a clinic

- **Consider using a nickname.**
- **Use a secondary phone number.** Either buy a SIM card with cash or get a virtual number (run by a company in a place that favors reproductive rights).
  - For our list of virtual number services, see the scenario above: `Masking your identity for online dating, events, or organizing`.
- **Use an end-to-end encrypted email address.** Consider setting up a new one just for this purpose.
  - Recommended services: [Proton Mail](https://protonmail.com/), [Tuta Mail](https://tutanota.com/)
- **Hide your transactions** by paying with:
  - Cash
  - A prepaid credit card you bought with cash
  - A privacy-focused virtual credit card from [Privacy](https://privacy.com/) (only available in the US).

#### Traveling to a clinic
 
- If you are physically going to a clinic and think it will be a risky situation, **follow the recommendations in the above scenario: `Attending a protest`.** 
- Do not bring your phone with you to the clinic. At the least, leave the phone at home or at the hotel during this last part of the journey.

#### Further advice for people in the US

-  Kendra Albert, Maggie Delano, and Emma Weil's [Okay, Fine, Let’s Talk About Period Tracking: The Detailed Explainer](https://medium.com/@maggied/okay-fine-lets-talk-about-period-tracking-the-detailed-explainer-2f45112eebb4)

---

### 🛫 Crossing an international border

- **Turn off your devices.**
  - Storage/hard drives are only encrypted when off, *not* when they’re just in sleep mode.
  - This will also ensure that your mobile devices can only be unlocked using a pin code, which is protected by freedom of speech laws in some jurisdictions.
- **Backup before you depart and keep a copy at home** in case your devices are lost in transit.
- **Store less information on your devices.** They can’t take what you don’t have if your devices are seized.
  - **1Password users can use the app’s [Travel Mode](https://support.1password.com/travel-mode/)** to remove certain passwords from the device during a trip.
- **Be mindful of what stickers you put on your devices.** A border agent could mistake them for something suspicious.
- **Decide beforehand what you will do if you are asked to unlock your devices.** Searches sometimes happen as a routine part of border crossing.
- **Attach a tracking tile/tag to bags** you’re worried about.
- **Notify your people about your flight number and arrival time.** Regularly check in with one of them at points in your journey (e.g. “They just finished scanning my bags!”). Have them contact a lawyer/relevant organization if you do not show up.
- **If the process becomes uncomfortable, consider going back home for now.**  Sometimes you get unlucky and going through with it is not worth the stress. Tell them you are withdrawing your application, no longer want to enter the country, and want to go home.

#### For extreme situations

*Note: Some of these practices might raise suspicions and backfire.*

- **Create an alternate universe version of yourself... digitally.** Create photo albums, email addresses, and social media accounts full of vanilla content.
- **“Forget” half of your password.** Password lock your device/account so that only a trusted friend has the second half of the password.
- **Log out of all important accounts.** Or leave your devices at home.
- **Consult a lawyer beforehand.** Keep a printed copy of their contact information with you, so you can contact them easily.

---

### 🤐 Traveling to a place with weak data privacy laws or internet censorship

- **Be aware that phone companies might share your location and personal info** with others without your permission.
- **Setup a VPN beforehand to:**
  - Access services uninterrupted.
  - Minimize the amount of data collected about you.
  - Recommended apps: [Mullvad](https://mullvad.net/), [IVPN](https://www.ivpn.net/) 💰
- **Download these offline apps in case there are connectivity issues:**
  - **An offline messaging app** to send text messages to people nearby if the internet goes down by using Bluetooth.
    - Recommended: [Bridgefy](https://bridgefy.me/) — *but you need to open the app with an internet connection to setup your account!*
  - **An offline maps app**
    - Recommended: [Organic Maps](https://organicmaps.app/)
- **Consider traveling with a burner phone while leaving your laptop at home.** This will be especially useful if you need to install new/untested software for work that might violate data privacy policies.
- **Re-evaluate which online platforms are safe to use.**  
  - See how often a platform hands over its data by looking up their transparency reports.
    - [Google Transparency Report: Request for user information](https://transparencyreport.google.com/user-data/overview)
    - [Facebook Transparency Report: Government Requests for User Data](https://transparency.facebook.com/)
    - [X/Twitter Transparency Center: Information Requests](https://transparency.twitter.com/en/reports/information-requests.html)
    - [Apple Transparency Report](https://www.apple.com/legal/transparency/)
  - Look up the location of the platform's global headquarters and see where the nearest local/regional office is. Location affects a platform's relationship with the authorities and its privacy policy.

---

### ‍💻 Hosting a public event online

- **Don’t say anything you wouldn’t say in public.** Encourage your attendees to do the same. Most commercial platforms have access to your audio/video data and mine your metadata to create consumer profiles.
- **Limit the amount of control an audience member has.**  
  - For example, for most Zoom events, it's not necessary for everyone to have screensharing access.
- **Don't make the meeting link too public.** Either set a meeting password or set up an RSVP system so that you don’t have to give out the meeting link and password publicly.
- **Create a user/content moderation plan.**
  - If you have co-hosts or moderators, make sure they are set up in the online system as administrators/editors/moderators.
  - Familiarize yourselves with what filtering/muting/blocking powers you have as a host/moderator.
  - Create an emergency plan of action around what you would do if a malicious troll enters your event.

---

### 🥴 Online harassment & doxxing

Harassment and doxxing tend to be very specific situations, which vary drastically depending on who you are, what you do, who the attacker is, etc.

While we have some general recommendations below, we suggest seeking additional information from someone in your community and from an online resource/guide that hews closer to your exact situation.

#### Build support systems

##### Recruit a trusted friend

Do not force yourself into a corner by going at this alone!

- **Baseline:** Ask a trusted friend to hold space for you and your situation. They can be your sounding board while helping you analyze how grave the threat is.
- **Preferred:** Ask a trusted friend to accompany you as you investigate, record, report and block harassers.
- **For serious situations:** Hand your phone/accounts over to a trusted friend and ask them to summarize incoming messages and updates. Decreasing your exposure will decrease your stress.
- **Bonus:** Have the trusted friend start a group chat with you, them, and 2-3 additional people explicitly for your situation. This way, support work is distributed among multiple people.

We recommend either going through the recommendations below with your trusted friend or handing the recommendations over to them.

##### Notify people who might be impacted

Another way to be less alone is to reach out to people who:

1. Are close to you and will want to know because they care about you (friends and family).
2. Might be second-hand impacted by the situation (colleagues, people in your professional or personal networks).

These people won’t necessarily be your “trusted friend,” but they might be able to help with other things on the side. 

If the situation escalates:

- Get ahead of any future trouble by making talking points together so that they know how to respond if internet strangers or the press contacts them.
- Find and notify someone in your community nearby with crisis experience for protection and support. 

##### Connect with communities

- **Reach out to online (and offline) communities you’re an active member of and ask for help.** See PEN America’s article on article on [Deploying Your Supportive Cyber Communities](https://onlineharassmentfieldmanual.pen.org/deploying-supportive-cyber-communities/).
- **Share your story** on [Right To Be’s storytelling platform](https://stories.righttobe.org/), where their “community can help you document or report abuse on social media platforms, as well as send you messages of support.”

#### Research and monitor the situation

##### Search for public information about yourself (dox yourself)

- **Search for your name, nicknames, usernames, and address on Google, Bing, and other popular search engines.** Try adding `filetype:pdf` to your search query to catch any CVs or documents you might have missed.
- **Run an image search on your most-used profile pictures on the same search engines.**
- **Search for your name, nicknames, and usernames on any social media platforms you regularly use.** Check social media platforms that are popular where you’re located, too.
- **Want to do a more thorough search?** See Access Now Digital Security Helpline’s [Self-Doxing Guide](https://guides.accessnow.org/self-doxing.html).

##### Monitor updates and collect evidence

- **Monitor your name and username.** Add them as search keywords in the following tools:
  - [Talkwalker](https://www.talkwalker.com/alerts)
  - [Google Alerts](https://www.google.com/alerts)
  - [Mention](https://mention.com) 💰
- **Monitor and archive webpages that mention you**. Recommended tools:
  - [ChangeTower](https://changetower.com/) or [Visualping](https://visualping.io/)
- **Log (date, time, description, screenshot, URL) incidents in whatever program/app is most accessible for you.** If there’s a lot of phone screenshots, use the [Hunchly Mobile](https://hunch.ly/mobile) app to organize and annotate them.
- **If future legal action is likely, pay [Page Vault](https://www.page-vault.com) to capture a snapshot of a website.** Ask a lawyer to file an [evidence preservation request](https://onlinesos.org/blog/evidence-preservation-i-e-litigation-hold-request) with the relevant online platform.

#### Decide on a course of action

##### Ways to deal with your harasser(s)

The following choices are not mutually exclusive, and the best choice may change over time as the situation evolves:

- **Ignore:** Sometimes, harassers will become bored and walk away if they don’t get attention.
- **De-escalate:** In some contexts, you can defuse the situation with some calm words before it worsens.
- **Mute on social media:** This lets you have peace of mind and not have your harasser’s updates suddenly pop up on social media. (You might still want to check what they’re saying proactively.)
- **Block on social media:** Sends a strong signal to your harasser. They won’t be able to see your posts or message you. They will, however, notice that you blocked them and might interpret it as a sign of escalation.
- **Go public:** Sometimes, shaming a harasser publicly or rallying people to your support will make them disappear. However, this has a high risk of escalating the situation and drawing more attention to it.
- **Report:** Report the harasser to the relevant online platform to have their account frozen or deleted. You may also report the incident to your local law enforcement if it makes sense.
- **Lawyer up:** If the harassment is clearly crossing legal boundaries in your jurisdiction, getting the help of a lawyer, might help, but make sure you have the time and money to do so.

See PEN America's [Guidelines for Safely Practicing Counterspeech](https://onlineharassmentfieldmanual.pen.org/guidelines-for-safely-practicing-counterspeech/) for extra tips on how to talk back effectively.

##### Managing unwanted phone calls

Sometimes you don’t want to block an unwanted caller just yet. Sometimes a harasser uses fake/temporary numbers to call you. Here are some ways to manage unwanted calls:

- **Silence or mute calls from a specific number:**
  - Android: Find the contact either in the Phone or Contacts app and tap on the name. Under `Contact settings`, go to `Contact ringtone → [Currently set sound] → None`. You can also send any calls directly to voicemail by tapping `Send to voicemail`  under the same contact settings.
  - iOS: Create a new `Focus Mode` by following [these Tom’s Guide instructions](https://www.tomsguide.com/how-to/how-to-silence-a-specific-contact-on-your-iphone).
- **Silence calls from all unknown numbers:**
  - iOS: `Settings → Apps → Phone → Silence Unknown Callers`
- **Block calls from all unknown numbers:**
  - Android: 
- **Reveal the number when a caller is hiding behind a `No Caller ID` setting** by using an app like [TrapCall](https://www.trapcall.com/).

##### If you decide to report

- **If harassment is happening on a social media platform**: File a report with a social media company and ask at least 10 friends to do the same. Have 1–2 people file a copyright infringement claim if it makes sense.
  - **Review the relevant reporting links for the following services:**
    - [Facebook](https://www.facebook.com/help/www/181495968648557)
    - [Instagram](https://help.instagram.com/192435014247952)
    - [X/Twitter](https://help.twitter.com/en/forms/safety-and-sensitive-content)
    - [Snapchat](https://support.snapchat.com/en-US/a/report-abuse-in-app)
- **If there’s harassment material on a website:** File a report with the website’s web hosting service and domain registrar. You might be able to find out who these companies are by performing a [WHOIS lookup](https://lookup.icann.org/) on the website domain.
- **If you contact law enforcement:**
  - Beware that not all officers are used to dealing with online harassment threats.
  - If you believe you might become a target of swatting (where people prank call the cops on you), let them know ahead of time. Send them an article about swatting if it’s a new idea to them.

##### Delete online information about you

In most cases, you will be safer if you review and remove some of the public information that's out there online about. See the scenario below titled: `Remove information about you off of the internet`.

#### Bonus: helpful social media platform tools and features

##### Facebook

Facebook has a few features to control your interactions, but ultimately relies on you setting limits on who can see and comment on your posts and profile.

- **[Ignore Messages](https://www.facebook.com/help/messenger-app/1245152242249842)** within Facebook Messenger to move the current and future messages to the `Message Requests` section
- **[Privacy Checkup](https://www.facebook.com/privacy/checkup)** within Facebook includes a section on `Who can see what you share` that walks you the visibiity of your profile and posts.

##### Instagram

Instagram has a set of nuanced features within its mobile app to filter and fine-tune social interactions on its platform.

- **[Restrict](https://help.instagram.com/2638385956221960/)** an account, which means the other person can’t see when you’re online, whether you’ve read their messages, and hides their comments.
- **[Hide](https://help.instagram.com/1177797265575168/)** your stories from a specific account.
- **[Hidden Words](https://help.instagram.com/700284123459336)** filters out messages and comments with words that Instagram deems offensive. You can also set up a custom words list.
- **[Limit](https://help.instagram.com/4106887762741654)** comments and messages from recent followers and accounts that aren’t following you.

##### Bluesky

Bluesky lets anyone create their own manual or algorithmic label/mute/block list, and allows users to limit who gets to comment on/share their posts. 

- **There are two types of labels: badges and warnings.** Badges are short, informative text labels that appear above a post or at the bottom of a profile. Warnings cover up the content with a warning about what it is, and forces you to click through to see the original post.
- **Labeler accounts** can be run by community members. By you subscribing to an account, you will then have access to the labels run by it. For each of the labels (e.g. `slur`), you get to choose whether you want the labeled post to be hidden, to have a badge next to it, to be warned about it, or to turn the label off for now. Here is a [sample list of labeler accounts](https://www.bluesky-labelers.io/).
- **Moderation lists** of users can be created by both user and labeler accounts in  `Settings → Moderation → Moderation lists`. When you subscribe to one, you can choose to mute or block all users on the list.
- **Post interaction settings:** Decide whether others can quote post, and only allow replies from mentioned users, followed users or nobody at all. When writing a post, tap  `Anybody can interact` to see the settings.

Important caveat: It’s currently possible to retrieve a list of everyone you block using the Bluesky API.

##### Mastodon

Mastodon has basic features to limit post visibility and searchability, and adjust how public your proflie is. On top of that, it has unique features because it’s run on a network of federated/decentralized servers (each user has to join a home server that supposedly aligns with their values).

- **Post visibility settings:** Each post can be set to `Public`, `Unlisted/Quiet Public`  (hidden from search and explore), `Follows only`.
- **Profile privacy settings:** In the `Settings → Public Profile → Privacy and reach` section of the website, you can adjust whether your posts and profile show up in recommendation or search pages, whether you want to manually screen every new follower, and whether you want your follows/followers to be browsable.
- **Federated/decentralized features:** Users can block all users from another server. Your server’s administrators can also issue a server-wide block to another server (as a user they are automatically blocked for you).


##### X/Twitter

X no longer supports third-party tools that combat harassment, and the platform’s moderation efforts have gotten lax. If the controls below don’t work, consider setting your profile to private and disengaging until the platform is stable again.

- **See what lists you’ve been added to by going to `Profile → Lists → ··· → Lists` you’re on.** If you see a suspicious list or list owner, tap the three dots on the top right to report the list and leave the list by blocking the creator.
- **Control who can reply to your tweets** by tapping `Everyone can reply` and restricting it to `People you follow` or `Only people you mention`.

##### TikTok

TikTok’s efforts mostly center around protecting people from harmful comments.

- **[Add comment filters](https://support.tiktok.com/en/using-tiktok/messaging-and-notifications/comments#3)** by entering manual keywords, by using TikTok’s own spam/offensive content filter, or by requiring manual approval on all of them.
- **[Add moderators to your livestream](https://support.tiktok.com/en/live-gifts-wallet/tiktok-live/moderating-on-tiktok-live)** to help manage comments and block unwanted viewers.
- **[Remove followers](https://support.tiktok.com/en/using-tiktok/followers-and-following/removing-followers)** from your account; former followers will not be notified.

##### Discord

Discord is centered around separate communities/servers, which affects the way blocking works.

- **When you block someone:**
  - They are unable to direct message you, call you, or tag you in a post.
  - Their messages to you disappear. 
  - Messages that they write on shared channels are hidden. *But* messages that you write on shared channels are still visible to them.
  - They appear `offline` to you at all times, but they can still see your online/offline status.
- **[Privacy settings](https://support.discord.com/hc/en-us/articles/217916488-Blocking-Privacy-Settings-)** allow you to adjust whether community/server members can direct message you, and who's allowed to send you friend requests.

##### Choosing between muting or blocking an account

- **Some platforms tell the other person you've blocked them, while others hide the action completely.** Read this [Consumer Reports guide](https://www.consumerreports.org/digital-security/can-people-tell-when-blocked-texting-social-messaging-apps-a9942470743/) for details on what blocking looks like to the other party.

#### Show yourself some kindness

- **Don’t worry if you’re not able to keep up with your regular workday routine.**
- **Call in friends to help share a meal, take a break, or watch your pet(s)** for a few days.
- **Do your best to eat and shower regularly.**
- **Engage in movement, no matter how small.** That could be a walk or even stretching. Pick something you enjoy, and that eases your mind.
- **Prepare a box of comforts beforehand.** Include things you like to see, touch, taste, and listen to.
- **If the incident is traumatizing, refer to it using a nickname.**
- **Remember, it is not your fault.** Online harassment is never justified and is ignited for the most random reasons.

#### Bonus tips to deal with intimate image & deepfake abuse

- **Look up your local laws** around “revenge pornography”, “nonconsensual sharing of intimate images,” and “digital sex crimes.” Know that in many places, it is a criminal act.
- **Upload a garbled “hash” of an abusive photo/video on [StopNCII.org](https://stopncii.org/) to have them removed from major platforms** like Facebook, TikTok, and Reddit.
- **Find where your face is being misused online using [Alecto AI](https://alectoai.com)** (beta). The service will also help with content removal.
- **Connect with others and share your story** on the [My Image My Choice Storyplace](https://myimagemychoice.storyplace.com/).
- **Connect with a local service** from eSafety’s [global support list](https://www.esafety.gov.au/key-topics/image-based-abuse/getting-help-outside-australia), Chayn’s [global directory](https://www.chayn.co/global-directory), or the Coalition Against Stalkerware’s [direct support resources](https://stopstalkerware.org/resources/).
- **Take Bloom’s course on [Image-based abuse and rebuilding ourselves](https://bloom.chayn.co/courses/image-based-abuse-and-rebuilding-ourselves)**.
  
#### Bonus tips for journalists and researchers

- **Make yourself a more challenging target.** Consider making your social media accounts private (or temporarily deleting them) for 48 hours surrounding a major, new release.
- **Don’t make more noise about yourself.** Don’t livetweet your situation, don’t quit your job suddenly, and don’t talk to media outlets who will twist your words.
  - If necessary, prepare a formal written statement or reply with the help of people who have experience dealing with the media.
- **If the noise doesn’t stop, flood the airwaves with positive stories about yourself.** Ask people within your professional community to write positive articles or social media posts about you and your work.
- **Remember, you did nothing wrong.** Ignorant employers or colleagues may not be supportive and start seeing you as a liability — they’re wrong.
- **Read [Lyz Lenz’s conversation with Talia Lavin](https://lyz.substack.com/p/when-the-mob-comes)** about their experiences.
- **Send these resources to your newsroom:**
  - Media Manipulation Casebook: [Tips for Newsrooms to Support Journalists Targeted by Online Harassment](https://mediamanipulation.org/research/tips-newsrooms-support-journalists-targeted-online-harassment/)
  - Ontheline Newsrooms: [Measures for Newsrooms and Journalists to Address Online Harassment](https://newsrooms-ontheline.ipi.media/).

#### Check out these additional resources

- PEN America: [Online Harassment Field Manual](https://onlineharassmentfieldmanual.pen.org/)
- Games and Online Harassment Hotline: [Digital Safety Guide](https://gameshotline.org/online-free-safety-guide/)

---

### 👀 Remove information about you off of the internet

If you’re about to become a public figure or are experiencing harassment, consider the suggestions below.

#### Clean up your social media presences

You might not need to delete your entire account, but consider deleting (or making private) old posts or posts that reveal too much about where you live, where you go, and who you’re with.

##### Facebook

- **See what your public profile looks like, and remove/restrict things as you see fit.**
  - Desktop: go to your profile and click the 👁 button next to the right of the `Edit Profile` button.
  - Mobile: go to your profile, tap the three dots on the right of `Add Story` and tap `View As`.
- **Make it so only friends can see your past posts.**
  - Desktop: Go to `Settings → Privacy → Limit Past Posts`.
  - Mobile: Go to `Settings & Privacy → Settings → Privacy Settings → Limit who can see past posts`.
- **Consider bulk deleting past posts.** To delete multiple posts at once:
  - `Settings and privacy → Activity log → Your Posts` and then select to `Archive` or `Trash`

##### WhatsApp

- Swipe to delete individual conversations.
- Delete chat content but keep the chat groups:
  - `Settings → Chats → Clear All Chats`.
- Delete all chats, including the chat groups:
  - `Settings → Chats → Delete All Chats`.
- Turn off chat backups on WhatsApp:
  - `Settings → Chats → Chat backup`.
- Delete your previous backups. Instructions for:
  - [iOS](https://faq.whatsapp.com/iphone/chats/how-to-turn-off-icloud-backup/)
  - [Android](https://faq.whatsapp.com/android/how-to-delete-backups/)

##### Instagram

- Look through your profile and manually delete posts. Tap the three dots in the upper-right corner of a photo.
- If you need to bulk-delete posts:
  - `Your activity → Photos and videos → Posts`, `Reels` or `Videos → Select` and then choose either `Archive` or `Delete`

##### X/Twitter

- Manually locate and delete individual posts using [its advanced search](https://twitter.com/search-advanced).
- Delete in bulk by using [Cyd](https://cyd.social/) , [TweetDelete](https://tweetdelete.net/) or [Tweet Deleter](https://tweetdeleter.com/) 💰.

##### Mastodon

- Login to your server through their website, and explore the options in `Preferences → Automated post deletion`.

##### LinkedIn

- Modify your profile’s [visibility settings](https://www.linkedin.com/psettings/data-visibility). Make sure to limit `Who can see or download your email address`, and `Who can see your connections`.

##### Reddit and other forums

- There’s often no easy solution. Sometimes you have to delete your entire account.
- In the case of Reddit, you have to [use third-party scripts](https://social.techjunkie.com/how-to-delete-all-reddit-posts/) because deleting your account still leaves your posts up.

#### Delete your social media accounts...temporarily

Many social media companies let you restore your deleted account after a specific period. This can be useful if you want to hide for a while and wait for an event to pass.

- **Facebook** [Read instructions](https://www.facebook.com/help/224562897555674) to deactivate or delete your account temporarily. You have 30 days after deactivation to reverse it.
- **Instagram** [Read instructions](https://help.instagram.com/370452623149242/) to disable your account temporarily, but deleting it seems permanent.
- **X/Twitter** [Read instructions](https://help.twitter.com/en/managing-your-account/how-to-deactivate-twitter-account) to deactivate your account. It will be permanently deleted if you don’t log in after 30 days.
- **Snapchat** [Read instructions](https://support.snapchat.com/en-US/a/delete-my-account1) to delete your account. It will be permanently deleted if you don’t log in after 30 days.

#### Remove your information from other people’s accounts or websites

*Remember: Information removal requests takes time to process and often require repeated attempts.*

- Ask [Google](https://support.google.com/websearch/troubleshooter/3111061?hl=en) and [Bing](https://www.microsoft.com/en-ca/concern/bing) and Bing to remove search results pointing to pages with your personal information on them.
- Remove any local business reviews you’ve left on Google Maps, Yelp, etc. They might point to your home or frequently visited places.
- Follow the Cyber Civil Rights Initiative’s [guide to get policy-violating posts/media removed from social networks](https://www.cybercivilrights.org/online-removal).
- If you want to do it yourself, check out Yael Grauer’s [BADBOOL](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List). (To be 100% thorough, use this on top of paid services.)
- If you’re willing to pay 💰, [BADBOOL](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List?tab=readme-ov-file#additional-options-paid-and-free) recommends using [EasyOptOuts](https://easyoptouts.com/) to remove your information from English-language public and paywalled sites.
- If you live in the US, [Consumer Reports’ Permission Slip app](https://www.permissionslipcr.com/) (iOS only) helps automate removal requests to 40+ US companies.

#### Remove articles and press about you online

*Note: The larger the publication, the harder it is to persuade them.*

- **Think of this as risk reduction, not total elimination.** It will be impossible to have everything removed.
- **Contact the editor or your previous contact.** Explain your situation honestly and hope for a sympathetic editor/writer.
  - If you think the editor/writer will not respond well, it may be better not to reach out—doing so may draw more attention to your situation.
- **For older articles,** it may help to remind them that the article is still easily accessible on search engines.
- **Enlist the help of a lawyer.** Sometimes, the threat of legal action will persuade an unwilling editor. 

#### Obscure your personal information

- **See the scenario:** `Masking your identity for online dating, events, or organizing`.
- **Get a P.O. box** at a post office or use [Earth Class Mail](https://www.earthclassmail.com/) (U.S. only) to hide your home address.
  - If you live in the US, you might qualify for your home state’s [Address Confidentiality Program](https://en.wikipedia.org/wiki/Address_confidentiality_program) if you are a victim of abuse or a healthcare worker. Rules vary state by state.
- **Delete old accounts to eliminate traces of personal information on the internet.** Use the [JustDeleteMe](https://justdeleteme.xyz/) directory to accelerate this process.

---

### 💔 Dealing with stalkerware/spyware

When someone close to you (usually a romantic partner) spies on you using a hidden app on your mobile device, that person is using *stalkerware*.

#### If you’re not sure and things haven’t escalated between you and your partner

- **Keep a hidden, pen-and-paper log of suspicious incidents.**
- **Restart your phone every day** while this is going on. Sometimes this forces spyware apps to stop working.
- **Make sure your partner is not getting information from previously shared accounts.** Did you share your calendar with them? Do you have any joint online accounts?
- **Log in to your important accounts and look for any suspicious logged in sessions.** Instructions for:
  - [Gmail](https://support.google.com/mail/answer/45938?#zippy=%2Cconcurrent-session-information)
  - [Facebook](https://www.facebook.com/help/211990645501187)
  - [Instagram](https://help.instagram.com/2761108904184084)
  - [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps#sessions)
  - [Microsoft](https://support.microsoft.com/en-us/account-billing/check-the-recent-sign-in-activity-for-your-microsoft-account-5b3cfb8e-70b3-2bd6-9a56-a50177863357)
- **Check to see if you set up location share on an app.** Instructions for:
  - [Google Maps](https://support.google.com/maps/answer/7326816)
  - macOS: [Find My](https://support.apple.com/en-ca/HT210514)
- **If you’re an iPhone user, run Safety Check** to review what you’ve shared and with who:
  - `Settings → Privacy & Security → Safety Check`
- **Scan for high-level spyware on your phone with [iVerify](https://iverify.io/products/basic).** The app’s basic tier costs only $1 and allows you do submit a forensic scan once a month.
- **Don’t delete suspicious apps immediately.** You may need to keep them as evidence. Plus, deletion may also cause the situation with your partner to escalate.
- **Review and redo the items in `Levels 1–3` of this guide.** Make sure to:
  - Reset your passwords for important accounts.
  - Check your privacy settings.
  - Look up any apps you don’t recognize on your computer and phone.
  - Make sure to look for hidden apps as well. Instructions for:
    - iOS: On the home screen, keep swiping left until you get to the `App Library` screen. Scroll to the bottom to the `Hidden` group. Tap to open and unlock using Face ID or passcode.
    - Android: See all apps including hidden ones in `Settings → Apps → See all apps`
- **Keep an eye out for other signs.** Examples include:
  - Your phone battery suddenly drains much faster than before.
  - Your computer internet connection is slower than usual.
  - You get emails/prompts about someone else logging into an account.
  - Your partner suddenly asks to borrow your phone.
- **Check to see if someone is using a tracking tile/tag to follow you.** Luckily, the two most popular tracking tile/tags have anti-stalking features.
  - Instructions for scanning:
    - Apple Airtags: [iOS](https://support.apple.com/HT212227), [Android](https://support.apple.com/HT212227#trackerdetect)
    - [Tiles](https://tileteam.zendesk.com/hc/articles/4415488529943)
  - Additional tool: AirGuard for [iOS](https://apps.apple.com/us/app/airguard-tracking-protection/id1659427454) and [Android](https://github.com/seemoo-lab/AirGuard)

#### If you’re pretty sure they’re spying on you and you’re scared

*Don’t go through this alone — seek help:*

- **Reach out to a trusted friend (through a public phone/line).** Ask them to hold space for you and your situation. They can be your sounding board while helping you analyze how grave the threat is.
- **Connect with one of the many organizations who specialize in stalkerware and domestic abuse (through a public/friend's phone/line).** Some of them help you collect evidence and remove stalkerware safely.
  -  See the Coalition Against Stalkerware's [global list of direct support organizations](https://stopstalkerware.org/resources/).
- **Keep digital and printed records of relevant texts, emails, calls, etc.**
	- See NNEDV's [guide on documenting/saving evidence](https://www.womenslaw.org/about-abuse/abuse-using-technology/evidence-issues-cases-involving-technology/digital-evidence).
- **When you no longer need evidence, remove the suspicious apps/stalkerware yourself by performing a factory reset on your computer/phone.** Buying a brand new device is even safer, of course.
  - **Remember to reinstall apps and import data manually,** lest you restore a backup with stalkerware in it.

#### Additional resources

- Consumer Reports: [Shut Stalkers Out of Your Tech](https://www.consumerreports.org/digital-security/shut-stalkers-out-of-your-tech/)
- Wirecutter: [Protect Your Devices Against Domestic Abusers](https://thewirecutter.com/blog/domestic-abusers-can-control-your-devices-heres-how-to-fight-back/)
- Apple iOS: [Personal Safety User Guide: Keep yourself safe and your data private](https://support.apple.com/en-ca/guide/personal-safety/welcome/web)

---

### 📰 Researching and writing about sensitive topics

Below are some general recommendations that all journalists and researchers should consider, especially for those working with (human) sources. If you have access to experts and training sessions through your workplace or professional communities, we highly recommend you taking advantage of that.

#### Be prepared

- **To remotely wipe the contents of your devices.** See scenario below titled: `Somebody took my phone/computer!`
- **To be on the receiving end of an email phishing campaign** (as journalist emails are usually more public than others).

#### Protect your sources

- **Use email as little as possible.** Even end-to-end encrypted email [leaves a trail of metadata](https://freedom.press/training/blog/how-reporters-emails-get-got-case-studies-legal-request-hacking/).
- **Use an end-to-end encrypted messaging app that doesn’t store metadata to exchange messages.** Don’t use X/Twitter DMs!
- **For voice/video calls, use an end-to-end encrypted app as well.**
- **Use the security features in Signal and WhatsApp.** See Martin Shelton’s articles on [Locking Down Signal](https://medium.com/@mshelton/locking-down-signal-d71678f653d3) and [Upgrading WhatsApp security](https://medium.com/@mshelton/upgrading-whatsapp-security-386c8ce496d3).
- **To make anonymous tips easier, have your organization set up a [Hush Line](https://hushline.app/)**.
- **For document transfers, have your organization set up [SecureDrop](https://securedrop.org/).** Failing that, encourage people to use [OnionShare](https://onionshare.org/).
- **Blur faces from photos and videos.** Read the relevants recommendations in the scenario titled `Attending a protest`.
- **See Ted Han and Quinn Norton’s [Protecting Your Sources When Releasing Sensitive Documents](https://source.opennews.org/articles/how-protect-your-sources-when-releasing-sensitive-/).**
- **See Martin Shelton’s [Opening Secure Channels for Confidential Tips](https://source.opennews.org/articles/opening-secure-channels-confidential-tips/).**

#### Protect yourself

- **Use a secondary phone number on messaging apps to talk to your sources.**
- **Create a public tip line using your secondary phone number.** Follow Yael Grauer’s guide: [How To Use Signal Without Giving Out Your Phone Number Using a Chromebook and an Old Phone](https://blog.yaelwrites.com/how-to-use-signal-without-giving-out-your-phone-number-using-a-chromebook-and-an-old-phone/).
- **If you're traveling,** review the scenario titled `Crossing an international border`.
- **If you’re covering a protest,** review the scenario titled `Attending a protest` and decide which parts apply to you (if you have special journalist rights/protections where you’re working).
- **If you're doing research on social media,** do so under a separate account that uses an alias (not your real name). Set up this account using a disposable email address. (Not all newsrooms/employers allow this, but push the allowed boundaries as much as possible.)
- **Hide where you’re coming from to websites you visit.** Use a VPN or [Tor Browser](https://www.torproject.org/), especially if you’re browsing the internet at home or at the office. You don’t want website administrators to see that you’re visiting from the *New York Times* office network, for example.

#### Protect your data

*Note: [Courts can compel companies like Google to hand over all of your data](https://medium.com/@tinfoilpress/newsrooms-lets-talk-about-g-suite-1672a36eb235).*

- **Use an email and storage provider not owned by an organization you’re reporting on.**
- **Move all of your work onto end-to-end encrypted platforms.** 
  - Recommended email platforms: [Proton Mail](https://protonmail.com/), [Tuta Mail](https://tutanota.com/)
  - Recommended document/spreadsheet platform: [CryptPad](cryptpad.fr/)
  - Recommended cloud storage platforms:  [Tresorit](https://tresorit.com/), [Proton Drive](https://proton.me/drive) 
- **Store sensitive data in a password-protected cloud or external storage device as much as possible.** Read the relevant recommendations in our `Level 3` section above.
- **Permanently erase sensitive files from your computer.** Recommended apps:
  - macOS: [CleanMyMac X](https://macpaw.com/cleanmymac) (its file shredder feature is included in the free trial)
  - Windows: [Eraser for Windows](https://sourceforge.net/projects/eraser/)

---

### 😭 Missing or lost device

- **Look for, lock or wipe your device remotely.** Instructions for:
  - iOS and macOS: [Find My](https://support.apple.com/HT210515).
  - Android: [Find My Device](https://support.google.com/accounts/answer/6160491).
  - Windows: [Find My Device](https://support.microsoft.com/account-billing/find-and-lock-a-lost-windows-device-890bf25e-b8ba-d3fe-8253-e98a12f26316)
- **Remove access to all important accounts on the lost device** by logging into them from another device, and then logging out all other active sessions.
  - Instructions for:
    - [Gmail](https://support.google.com/mail/answer/45938?#zippy=%2Cconcurrent-session-information)
    - [Facebook](https://www.facebook.com/help/211990645501187)
    - [Instagram](https://help.instagram.com/2761108904184084)
    - [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps#sessions)
    - [Microsoft](https://support.microsoft.com/en-us/account-billing/check-the-recent-sign-in-activity-for-your-microsoft-account-5b3cfb8e-70b3-2bd6-9a56-a50177863357)
- **Remove access to your authenticator app on the lost device** (if you use an app that supports multiple devices).
  - Instructions for:
    - Ente Auth: `Settings → Security → View active sessions`, and then tap on one to terminate it.
    - [Authy](https://help.twilio.com/articles/19753662574363)
- **Remove access to your password manager on the lost device** in the same way.
  - Instructions for:
    - 1Password: Tap/click your profile icon/name, then `Manage Accounts → Accounts → [Your account name] → Trusted Devices and Browsers`, and choose `Deauthorize` on the lost device 
    - Bitwarden: `Settings → My accounts → Deauthorize sessions`
- **Change the password on important accounts** (banking, email, social media) if you think someone else might misuse them.
- **To prevent misuse, get a new SIM card and cancel your old one.** Make sure to do this only after you've tried calling your phone to reach whoever has picked it up.
- **If you get your device back, reset it** back to its factory settings and restore it from your last backup.
- **If the authorities seize your device at an international border crossing, ask for a seizure receipt** (available in some jurisdictions, such as [Canada](https://bccla.org/wp-content/uploads/2018/10/Electronic-Devices-Privacy-Handbook-BCCLA_2.0.pdf)).

---

### 👾 Figuring out if your device has been hacked

- **Log in to your important accounts and look for any suspicious logged in sessions.** Instructions for:
  - [Gmail](https://support.google.com/mail/answer/45938?#zippy=%2Cconcurrent-session-information)
  - [Facebook](https://www.facebook.com/help/211990645501187)
  - [Instagram](https://help.instagram.com/2761108904184084)
  - [X/Twitter](https://help.twitter.com/en/managing-your-account/connect-or-revoke-access-to-third-party-apps#sessions)
  - [Microsoft](https://support.microsoft.com/en-us/account-billing/check-the-recent-sign-in-activity-for-your-microsoft-account-5b3cfb8e-70b3-2bd6-9a56-a50177863357)
- **Use the device's built-in tools to look for irregular patterns.**
  - On your computer, look for any processes that are using a lot of your CPU, or have names that you don't recognize (look them up to be sure). Use these tools:
    - macOS: Activity Monitor
    - Windows: Process Explorer to look at what processes/applications are running. Google any suspicious names.
  - On your phone, look for apps that are using an abnormally large amount of battery or data. Use these tools:
    - iOS: `Settings → Battery → Battery usage by app`
    - iOS: `Settings → Cellular → Cellular data` 
    - Android: `Settings → Battery → Battery usage`
    - Android: `Settings → Network and interent → SIMs → App data usage`
    - Android: `Settings → Network and interent → Internet → Non-operator data usage` 
  - If you are on an iPhone:
    - See if you can go to `Settings → General → Profiles`, and if it’s available, look for anything you don’t recognize.
    - In Safari, enter the URL `videos://`. This should ask you to open the TV app if it’s working. Cancel that, and then type in a new URL `cydia://`. It should say “Safari cannot open the page because the address is invalid.”

- **Download third-party apps that analyze network connections and detect malware on your devices:**
  - [Charles Proxy](https://www.charlesproxy.com/) for Windows, macOS, Linux
  - [Glasswire](https://www.glasswire.com/) for Windows, Android
  - [Little Snitch](https://www.obdev.at/index.html) for macOS
  - [Objective-See’s tools](https://objective-see.org/index.html) for macOS
  - [iVerify](https://iverify.io/products/basic) for iOS, Android
- **Set up a spare phone as a room monitor** to detect unwanted physical intrusion. Example apps:
  - [Alfred](https://alfred.camera/) for iOS & Android 
  - [Haven](https://guardianproject.info/apps/org.havenapp.main/) for Android
- **Put your phone or tablet in “lockdown mode” (iOS only)**  to block most of the incoming messages and connections while you figure things out:
  - [Read Apple Support’s article about it.](https://support.apple.com/en-us/HT212650)
  - `Settings → Privacy & Security → Lockdown Mode → Turn On Lockdown Mode` 

---

### 😣 Seeking help in an emergency

#### Helplines and helpdesks

These typically fall into several categories:

1. For residents of a country or jurisdiction: Run an internet search for local internet associations and NGOs.
2. For victims of gender-based violence: See Chayn’s [global directory](https://www.chayn.co/global-directory), the Coalition Against Stalkerware’s [direct support resources](https://stopstalkerware.org/resources/), and eSafety’s [global support list](https://www.esafety.gov.au/key-topics/image-based-abuse/getting-help-outside-australia).
3. For members of civil society: See Amnesty International Security Lab’s [list of digital resilience and security helplines and helpdesks](https://securitylab.amnesty.org/digital-resources/).

#### If someone else has taken control of your accounts

- See Consumer Reports Security Planners’ [list of instructions on regaining access](https://securityplanner.consumerreports.org/tool/regain-control-of-hacked-accounts).

#### If you’ve been a victim of an online scam, fraud or ransomware

- See Microsoft’s [list of government fraud and scam reporting websites](https://support.microsoft.com/en-us/windows/protect-your-pc-from-ransomware-08ed68a7-939f-726c-7e84-a72ba92c01c3) (scroll down to "What to do if you already paid").

#### If you need to safely send information to journalists

- [Drop a News Tip](https://docs.google.com/spreadsheets/d/e/2PACX-1vSRFKbJUtFQ55uB5NSaIgxUwQM8qRGMwLyybDWhqmqbCba_zaeDo5L7i3yJv8vb_Q_VqRvIwOcRKDeJ/pubhtml) has a list of 50+ news organizations from all over the world that let you submit information through SecureDrop and/or an end-to-end encrypted messaging app.

---

## 🎁 Bonus

This section contains additional tools and tips that we encountered during our research. Many of the recommendations below are popular with members of the cybersecurity community, but we found them to be a little too hard to use/follow, or too specific for a small group of people.

### Tools & tips for maximum safety

- **Write and take notes on end-to-end encrypted apps.** Instead of Google Docs or Microsoft Office, use [CryptPad](https://cryptpad.fr) or [Standard Notes](https://standardnotes.org/). Both are open-source and free to use.
- **Share files anonymously** with [Tresorit Send](https://send.tresorit.com/) or [OnionShare](https://onionshare.org/).
- **Turn suspicious PDFs into safe ones** using [Dangerzone](https://dangerzone.rocks).
- **Edit your `Protected View` settings (Windows only)** if you open a lot of files in [Microsoft Office](https://support.microsoft.com/en-us/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653) and [Adobe Acrobat](https://helpx.adobe.com/acrobat/using/protected-view-feature-pdfs-windows.html).
- **Try a new end-to-end encrypted messaging app.** It’s always good to have more than one installed in case it has a server outage. See Mark Williams’ [Secure Messaging Apps Comparison](https://www.securemessagingapps.com/) for some options.
- **Send end-to-end encrypted emails** using [Proton Mail](https://protonmail.com/) or [Tuta Mail](https://tutanota.com/).
- **Find an end-to-end encrypted video calling service** using [Freedom of the Press' guide](https://freedom.press/training/blog/videoconferencing-tools/).
- **Send a self-destructing, password-protected message** using [One Time](https://onetimesecret.com/).
- **Sign up to be notified by [Have I Been Pwned](https://haveibeenpwned.com/)** when an account tied to your email is compromised.
- **Scan for any Bluetooth devices near you** (including AirTags) with [nRF Connect](https://www.nordicsemi.com/Products/Development-tools/nrf-connect-for-mobile).
- **Increase the protective barriers around your accounts:**
  - [Google’s Advanced Protection program](https://landing.google.com/advancedprotection/): mandates passkeys or security keys, is extra careful about downloads, and limits “Sign in with Google” for Google accounts/apps/devices. 
  - [Apple iCloud’s Advanced Data Protection](https://support.apple.com/guide/security/sec973254c5f/web): turns on end-to-end encryption for some iCloud apps but not Mail/Contacts/Calendar.
  - [Proton Sentinel](https://proton.me/support/proton-sentinel) 💰: creates more detailed “security events” logs, and offers better human support around security for Proton services/apps.
- **US residents: freeze your credit** to prevent bad actors from accessing or mis-using your personal information. See IntelTechniques’ [Credit Freeze Guide](https://inteltechniques.com/freeze.html) for details.

### Tools & tips that cost money

- **Buy a USB [YubiKey](https://www.yubico.com/products/) for two-factor authentication.** If you work in free speech/press/internet, you may qualify for a free [Yubico for Free Speech](https://www.yubico.com/about/about-us/free-speech-program/).
- **Use [1Password’s Travel Mode](https://support.1password.com/travel-mode/)** to create a set of passwords you don’t take with you on the road.
- **Put your smart cards/passports/phones in a Faraday bag that blocks signals from going in and out.** (See [Micah Lee’s guide on them](https://micahflee.com/2015/11/some-thoughts-on-faraday-bags-and-operational-security/).)
- **Buy a microphone blocker** from [Mic-Lock](https://mic-lock.com/) to plug into your phone to mute its microphone.
- **Get a security-focused router** from [pcWRT](https://www.pcwrt.com/) or [Peplink](https://www.peplink.com/).
- **Buy a hardware-encrypted external USB or hard drive** from companies like [Apricorn](https://www.apricorn.com/).

### Tools & tips with steep learning curves

- **Use a specialized DNS service to access the internet** like [Quad9](https://www.quad9.net/).
- **Use a decentralized, private messaging app powered by the Tor network**. Check out [Ricohet Refresh](https://www.ricochetrefresh.net/).
- **Access Facebook with more anonymity and bypass internet filtering by using [its onion service](https://en.wikipedia.org/wiki/Facebookcorewwwi.onion).**
- **Use a more secure operating system for your computer.**  Options include:
  - [Tails](https://tails.boum.org/)
  - [Qubes OS](https://www.qubes-os.org/)
- **Harden your Android phone** to be more secure and private:
  - **Use [F-Droid](https://f-droid.org)**: an open source, security-focused app store.
  - **Replace the operating system** your phone came with:
    - If you have a Google phone, install [GrapheneOS](https://grapheneos.org/) or [CalyxOS](https://calyxos.org/).
    - If you don’t have a Google phone, install a vanilla “stock” version of Android directly from Google and without all the extras your phone manufacturer added. (Instructions vary depending on what phone you have, so you will have to do some research.)
- **Start using super secure devices.** Options include:   
  - [PINE64](https://www.pine64.org/)
  - [Purism](https://puri.sm/).

### Tools & tips for hosting/running a website

- **Read [this EDRi guide on ethical website development and maintenance](https://edri.org/ethical-web-dev/).** Pay special attention to its privacy recommendations.
- **Protect your website from DDOS attacks and other threats by using**
  - **[Deflect](https://deflect.ca/).** There’s a [free plan]([https://deflect.ca/nonprofit](https://deflect.ca/nonprofit)) for non-profits.
  - **[Cloudflare](https://www.cloudflare.com/).** There’s a [free plan](https://www.cloudflare.com/galileo/) for arts, human rights, civil society, journalism, or democracy organizations.
  - **[Project Shield](https://projectshield.withgoogle.com) from Google.** Only available for news, human rights and election monitoring sites.
- **If using WordPress, consider using the following plugins**
  - **[Wordfence](https://wordpress.org/plugins/wordfence/)**
  - **[Sucuri Security](https://wordpress.org/plugins/sucuri-scanner/)**
  - If your hosting service doesn't offer backups, use [VaultPress](https://jetpack.com/upgrade/backup/) or [BackupBuddy](https://ithemes.com/backupbuddy/).
  - Alternatively, use [Simply Static](https://simplystatic.com/) to turn your public-facing Wordpress site into a static site.
- **Use a privacy-oriented analytics service** like [Matomo](https://matomo.org/) or [Koko Analytics](https://www.kokoanalytics.com/).
- **Consider switching to a more privacy-oriented hosting service** like [Greenhost](https://greenhost.net/) or [Maadix](https://maadix.net/en/) .
- **Set up a [security.txt](https://securitytxt.org/) file** so that researchers have a place to disclose security vulnerabilities.
- **Set up a robots.txt file** using [this ai.robots.txt list](https://github.com/ai-robots-txt/ai.robots.txt) to prevent AI companies from crawling and scraping your data.

---

**🏆 Oh my, you have arrived.**  
**🏆 This is the end.**  
**🏆 Thank you for reading.**  
**🏆 Thank you for being thorough.**  
**🏆 You are a true champ.**

---

## 🧠 Other resources

We consulted many sources and drew upon our experiences in creating this guide. If you’re not finding quite what you want here, we recommend checking out the following resources:

- Consumer Reports: [Security Planner](https://securityplanner.consumerreports.org/)
- Electronic Frontier Foundation: [Surveillance Self-Defense](https://ssd.eff.org/)
- Michael Horowitz: [A Defensive Computing Checklist](https://defensivecomputingchecklist.com/)

---

## 📝 License ##

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## 👋🏾 Special thanks ##

Special thanks to [our GitHub contributors](https://github.com/narwhalacademy/zebra-crossing/graphs/contributors) and community members who wrote in with edits, suggestions and translations.