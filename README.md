# TLDR Guide To Personal Digital Security

---

## Why another guide?

- Because personal digital security is important.
- Because there was a dearth of guides/resources that filled the gap between really simple and really complex.
- Because most of the guides tackling more complex setups don't take usability into account (poor usability → human error → security fail).

## About this guide

- This is draft one! I am very sleepy.
- This guide is a living document – please feel free to submit a pull request and/or fork your own version of this guide.
- This guide is mostly focused on personal digital security but will also cover aspects of protecting your privacy as they often go hand in hand.

---

## Theory

### Threat Modeling

- What kind of danger are you in? E.g. corporate espionage, police/state intervention, online harrassment/doxing, nosy neighbors.
- What kind of assets are you protecting? E.g. confidential documents, politically sensitive information, private photos.
- We're all in a little bit of danger (otherwise we wouldn't bother putting a password on our computers and phones) but it's important to think about what's at stake before dismissing concerns or becoming paranoid :)
- For more info, read [the EFF's introduction to threat modeling](https://ssd.eff.org/en/module/introduction-threat-modeling).

### Weakest Link

- Remember the weakest link is all that matters! E.g. if password recovery is linked to email, then hackers only need to get access to your email.
- For more info, read [the EFF's guide to seven steps to digital security](https://ssd.eff.org/en/module/seven-steps-digital-security).

---

## Science (coming soon)

- Encryption
- Metadata

---

## Level 1 💦

### Things To Do Now

#### Email

- If you're on a webmail service, check that you're logging into it using an `https://` URL. And if there isn't one, find a new email provider.
- Turn on two-factor authentication for your email service (e.g. [Gmail instructions](https://support.google.com/accounts/answer/185839?hl=en)). 
- Where available, use an authenticator app rather than SMS for two-factor authentication (e.g. [Google Authenticator instructions](https://support.google.com/accounts/answer/1066447?hl=en)).

#### Good passwords

- Any password less than 10 characters is bad, but it's also okay-to-string-together-non-sequitur-words.
- Double check the security questions for your key online services (email, bank, Facebook, etc.) and make sure that they're not easy to answer by friends/looking you up on google.
- Use a different password for every service, because password leaks happen all the time. To make this easy, use a password manager – [Lifehacker reviews them here](https://lifehacker.com/5529133/five-best-password-managers). They also help generate more secure passwords.
- Use a non-common/obvious unlock code for your phone. Pro tip: if you insist on using thumbprint unlock, immediately power off your phone if you're ever arrested.

#### Encrypt your devices

- Encrypt your phone: [Android](http://www.networkworld.com/article/2689371/opensource-subnet/how-to-encrypt-an-android-device-in-5-steps.html), [iOS](https://ssd.eff.org/en/module/how-encrypt-your-iphone
).
- Encrypt your laptop/desktop hard drive: [Windows](https://uit.stanford.edu/service/encryption/wholedisk/bitlocker), [Windows if no BitLocker](https://veracrypt.codeplex.com/), [Mac OSX](https://support.apple.com/en-us/HT204837).
- Secure your backups too! Encrypt your backup hard drives and/or make sure your online backup storage solution supports end-to-end encryption.
- N.B. Remember encryption is only fully effective when the device is off!

#### Other

- Turn off app-specific passwords that bypass two-factor authentication (e.g. [instructions for Gmail](https://www.lifewire.com/revoke-an-application-password-for-gmail-1171889)).
- [Turn on Login Alerts on Facebook](https://www.facebook.com/settings?tab=security).
- Lock your mobile phone SIM card: go to your phone provider's website to create a strong passphrase/PIN.
- Always update the operating system on your computer and mobile to the latest version.

### Habits to Cultivate

#### Email

- Be on the lookout for phishing scams: where possible double check the From email address and the domains that outbound links go to.
- Don't open unnecessary email attachments. Where possible, open/preview them first in an online document reader, or have colleagues use a filesharing server or service (Google Drive, SpiderOak, Dropbox), which tend to be a little harder to hack into.
- You can upload a suspicious attachment to [VirusTotal](http://www.virustotal.com) for a check-up (but keep in mind files submitted to VirusTotal are available to security researchers so don’t submit sensitive information)

#### Other

- Regularly change important passwords (e.g. email, computer login, password manager master)
- Wipe your devices properly before donating/giving away: [phone](http://lifehacker.com/5808280/what-should-i-do-with-my-phone-before-i-sell-it), [computer](http://lifehacker.com/5835369/how-do-i-securely-wipe-a-computer-before-donating-it-to-charity)

### Scenario: 💩 my phone/computer was stolen!

- Follow the Freedom of Press Foundation's guide: [What To Do If Your Phone Is Seized By The Police](https://freedom.press/training/mobile-security-for-activists-and-journalists/)
- Wipe your phone remotely: see PC Magazine's [How to Remotely Disable Your Lost or Stolen Phone](www.pcmag.com/article2/0,2817,2352755,00.asp)

### Scenario: I think my computer has been hacked 😱

- Download an application that will notify you when data is being sent out from your computer. E.g. [Little Snitch for Mac](https://www.obdev.at/products/littlesnitch/index.html)
- Run Activity Monitor on Mac or Process Explorer on Windows to look at what processes/applications are running. Google any suspicious names.

---

👍 Good job! You've covered the basics. What about trying out the next level?

---

## Level 2 💦💦

### Things To Do Now    

- Review the privacy settings on social networks you frequent: who can see your content, who can comment on it, and who can see your location.
- Review what's connected to your main email/social media accounts (e.g. what kinds of services have access to Facebook, and what data can they access and/or can they post on your behalf)
- Update the apps on your phone and computer to the newest versions. [Flexera PSI](http://learn.flexerasoftware.com/SVM-EVAL-Personal-Software-Inspector) helps with that on a Windows PC.
- Set up your devices with third-party applications (e.g. [Lookout Security](https://www.lookout.com/), [Prey](https://www.preyproject.com) so you can remotely track, wipe, and encrypt your devices from a website in the future.
- Setup end-to-end encryption for computer-based instant messaging: EFF guide for [Mac](https://ssd.eff.org/en/module/how-use-otr-mac), [Windows](https://ssd.eff.org/en/module/how-use-otr-windows), [Linux](https://ssd.eff.org/en/module/how-use-otr-linux)

### Habits To Cultivate

- Post less personal information online – especially information that can be used to identify/track/scam you (addresses, phone numbers, birthday, etc.). Remember almost everything you say online is logged somewhere and that even if your setup is secure, your recipient's setup may not be.
- Use a paid VPN service when on public networks (e.g. cafe wifi). See [the EFF on Choosing the VPN That's Right for You](https://ssd.eff.org/en/module/choosing-vpn-thats-right-you). Free VPN services are bad because operators don't have enough incentive to protect you/your data.
- Start using [Signal](https://whispersystems.org/), an end-to-end encrypted mobile messaging app that's generally agreed to be safe/secure/robust. (Beyond Signal, there is little consensus on what's secure and people tend to get very emotional about their choice of mobile messaging apps.)
- Start making end-to-end encrypted voice calls (available on Signal, WhatsApp, Jitsi, Silent Phone, Zphone, etc.).
- If you ever need to send someone a password, send it through multiple networks/channels (including a voice call). 
- Buy more secure mobile phones ($$$): either an iPhone or an Android phone that implements a "pure" Google version of Android (at the least you should be able to goto Settings → Security and see options for encryption and SIM card lock).
- If you own domains, use WHOIS privacy services and stick with it (they're worth the money). But note that with WHOIS lookup/history tools, if you've ever put in your real address, it's very difficult to remove from the logs.

### Scenario: Online harassment & doxing

- See [Crash Override: So You've Been Doxed](http://www.crashoverridenetwork.com/soyouvebeendoxed.html).
- See [Crash Override: Preventing Doxing](http://www.crashoverridenetwork.com/preventingdoxing.html).
- Use [Traveling Mailbox](https://travelingmailbox.com/) to obscure your postal address.
- Use [Burner](http://www.burnerapp.com/) to set up burner phone numbers for calling/texting.

### Scenario: Attending a protest

- Draft a message to a trusted friend who is elsewhere. Be ready to hit send if you are arrested/there is an emergency.

---

🎉 Congratulations! You're now reasonably secure, which is more than most :)

---

## Level 5 💦💦💦💦💦 (under construction)

- YubiKey USB for two-factor authentication
- Email PGP
- Diceware passwords
- Tor
- DuckDuckGo
- Tails
- Self-hosted Wordpress: Cloudflare + iThemes Security 
- If protest: leave your phone at home or use burner phone
- Delete old accounts

---

Oh my you made it this far! Are you a 🤖?

---

## Sources

These are the main sources that I drew from, all of which were tremendously helpful and are good guides in their own right:

- [Digital Security Low Hanging Fruit](https://www.johnscottrailton.com/jsrs-digital-security-low-hanging-fruit/) by John Scott-Railton
- [Computer Security Tools and Concepts for Lawyers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2831739) by Kendra Albert
- [Crash Override's Resource Center](http://www.crashoverridenetwork.com/resources.html)
- [The Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/)
- [How to encrypt your entire life in less than an hour](https://medium.freecodecamp.com/tor-signal-and-beyond-a-law-abiding-citizens-guide-to-privacy-1a593f2104c3#.z1estrrkj) by Quincy Larson

Let me know by filing an issue if there are any other guides that you found useful that you think I should include.

---

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
