[← Back to contents](../README.md)

# 14. Account and information security

Lens: money and personal information. Someone logged into your account takes money first. They'll also use your account to scam the people in your contacts. Your identity is effectively taken too.

### 1. Turn on two-factor verification for email, payment and social accounts - phone push confirmation first, SMS codes second
<!-- tags: money=0 time=low will=no benefit=big lens=money -->
- Cost: Free. Set once per account - two or three minutes each.
- TL;DR: Two-factor verification means confirming it's really you a second time beyond the password at login. The phone-popup-tap-confirm method blocks over 90% of phishing account theft. The old way - answering "where did you last log in" or "what's your backup email" - stops only about 10%.
- Benefit: Google studied 350,000 real account-theft attempts (account hijacking). One class verifies by device - a phone popup you tap to confirm, or a plugged-in security key. It blocked "over 94% of phishing-based hijacking attempts and 100% of automated hijacking attempts" - phishing meaning tricking you into entering your password on a fake site, automated meaning machines bulk-trying leaked passwords. The other class verifies by questions - where you last logged in, your backup email. It "blocked as little as 10% of phishing hijacking and 73% of automated hijacking"
- Evidence: A
- Sources: Doerfler P, Thomas K, Marincenko M, et al. (2019). Evaluating Login Challenges as a Defense Against Account Takeover. The World Wide Web Conference (WWW '19). <https://doi.org/10.1145/3308558.3313481>
- Notes: The same study found these checks sometimes lock out the owner: 52% of real users failed to get in on the first try, though 97% eventually did. Enable it on email first - most other accounts can be reset through email.

### 2. The email password stands alone - repeated on no other site
<!-- tags: money=0 time=low will=some benefit=big lens=money -->
- Cost: Free. With a password manager, you don't memorize anything. The hard part is breaking the one-password-everywhere habit.
- TL;DR: Passwords stolen from other sites get tried directly on your email. Once someone is in your email, every account recoverable through it goes down together. So the email password stands alone - used nowhere else.
- Benefit: Trying leaked account-password pairs one by one is credential stuffing - the cheapest attack there is. Passwords leaked elsewhere get tried directly on your email. Once someone is in, every account using it for password recovery goes down together
- Evidence: C
- Sources: Author's experience; no direct literature
- Notes: Can't memorize: use the browser's built-in password manager - far better than one password everywhere. Don't store passwords in WeChat Favorites or a notes app.

### 3. Set a lock-screen password on the phone and a PIN on the SIM card
<!-- tags: money=0 time=low will=no benefit=big lens=money -->
- Cost: Free. Set each once.
- TL;DR: The SIM is the small card in the phone - SMS codes arrive through it. If the phone is lost, the finder pulls the card, plugs it into another phone to receive your codes, and resets your accounts one by one. A PIN on the card means a new phone demands the code at boot - that road is cut.
- Benefit: After a phone is lost, the finder's fastest road is plugging the SIM into another phone and receiving your SMS codes. Codes in hand, they reset your accounts one by one. A PIN on the SIM demands the code at boot on any other phone - that road is cut directly
- Evidence: C
- Sources: Author's experience; no direct literature
- Notes: The PIN is set under "SIM lock" in phone settings. Factory defaults are usually 1234 or 0000. Three wrong entries and only the carrier's PUK code unlocks it - so write the code down on paper first.

### 4. Phone lost: do it in this order - freeze the SIM, lock the phone remotely, change passwords, report to police, freeze bank cards
<!-- tags: money=0 time=low will=no benefit=big lens=money -->
- Cost: Free. The whole sequence takes ten-plus minutes.
- TL;DR: Order matters more than speed. Step one, freeze the SIM - the verification-code lifeline is cut. Then lock the phone remotely, change email and payment passwords from a computer, report to police and get the receipt, and freeze bank cards as needed. Without your phone, borrowing someone's to call the carrier's service line freezes the SIM too.
- Benefit: Order matters more than speed. First, freeze the SIM - cutting the verification-code lifeline. Second, lock the phone remotely and wipe its contents. Third, change email and payment passwords from a computer. Fourth, report to police and get the receipt. Last, freeze bank cards as needed
- Evidence: C
- Sources: Author's experience; no direct literature. Replacing an ID card: chapter 7; loans taken out in your name: the credit-report entry in chapter 8
- Notes: Save the three carriers' service numbers in advance: China Mobile 10086, China Unicom 10010, China Telecom 10000. Also note which city your number was registered in - customer service will ask. Someone else's phone works for the freeze call just the same.

### 5. Card fraudulently charged: freeze first, report second, then demand the bank pay - proving "you made the charge yourself" is the bank's job
<!-- tags: money=0 time=low will=some benefit=big lens=money -->
- Cost: Free. On noticing anything off on the card, freeze it at once. Keep the police-report record, the freeze record and the bank's transaction notifications. With the card still on you, do a small nearby balance check or transaction - a record proving the real card was in your hand when it happened. The hard part is not arguing with customer service first - freeze first.
- TL;DR: With a fraudulently charged card, you don't prove "it wasn't me". The reverse: the bank must produce evidence the charge was yours - failing that, it pays you. The precondition is freezing as soon as you notice. Dragging without freezing, the further losses are yours.
- Benefit: The SPC's rule splits "who produces evidence". Claiming cloned-card or online fraud, you produce evidence first - cloned-card fraud meaning the card was copied and charged. Usable proof includes effective legal documents, where the real card was during the transaction, and where the transaction happened; also account statements, transaction notifications, police reports and freeze records. **In reverse, the issuing bank or non-bank payment institution (third-party payment) claiming the cardholder made or authorized the charge must produce the evidence**. After you notify the bank, if it fails to verify in time, or fails to provide and keep transaction slips and surveillance footage so the evidence becomes unavailable, the bank bears the consequence of having no evidence. Once found: a debit-card (savings-card) holder may demand the issuing bank pay the stolen deposit with interest and compensate losses. A credit-card holder may demand return of the charged overdraft principal, interest and penalty, plus losses - and a bank counterclaiming repayment of that overdraft gets no court support. You may also demand the bank promptly remove the corresponding bad credit record (nationwide, effective May 25, 2021)
- Evidence: A
- Sources: Supreme People's Court (2021). Provisions on several issues in hearing bank-card civil disputes (Articles 4, 5, 7, 14, 15). <https://www.court.gov.cn/fabu/xiangqing/304771.html>
- Notes: Two situations are your own liability. First, failing to keep the card, password or verification codes safe - your own fault ("failure of safekeeping duty with fault") - bearing as much as the fault. So: the password told to no one, codes forwarded to no one (entry 1: phone-push confirmation first). Second, not freezing in time and letting losses grow - the excess is yours. So step one is always freezing, not arguing with customer service. Third-party payment institutions follow the same rules - one whose materials concretely promise "compensation first" can be held to paying first. Money you were scammed into transferring yourself is another road - entry 2 of chapter 8 (call 110 or 96110 at once to stop payment).

### 6. Every so often, review your accounts' logged-in devices and authorized apps - clear what you no longer use
<!-- tags: money=0 time=low will=some benefit=mid lens=money -->
- Cost: Free. Minutes each time. The hard part: nobody reminds you - remembering is on you.
- TL;DR: "Logged-in devices" are the phones and computers that can currently use your account. Account thieves often lie low a while before acting. An unknown device appearing in the list, or long-unused software still connected: log everything out, then change the password.
- Benefit: Account theft often isn't acted on at once - the other side lies low first. The logged-in-devices list records the phones and computers that can currently use the account. The authorized-apps list records third-party software you allowed to sign in with it. Unknown devices and long-unused third-party software are the easiest traces to spot
- Evidence: C
- Sources: Author's experience; no direct literature
- Notes: WeChat, Alipay, email, Apple and Android accounts all have this entry point. An unrecognized device: tap log out everywhere, then change the password.

### 7. Don't tap "agree to all" to use an app: for information a service doesn't need, refusing it can't cost you the service
<!-- tags: money=0 time=low will=some benefit=mid lens=freedom -->
- Cost: Free. The hard part is not tapping "agree to all".
- TL;DR: Where information isn't necessary to provide the service, refusing to give it can't get you refused. And what's collected is limited to what's actually used. A map needing your location is necessary; a flashlight wanting your contacts isn't.
- Benefit: The law writes two things. First, a product or service may not be refused on the ground that you didn't consent, or withdrew consent - unless processing that information is necessary to provide it. Second, collection is limited to the minimum scope for the purpose - only what's used
- Evidence: A
- Sources: NPC Standing Committee (2021). Personal Information Protection Law. NPC website. <http://www.npc.gov.cn/npc/c2/c30834/202108/t20210820_313088.html>: Article 6 "personal information shall be collected within the minimum scope for the processing purpose - no excessive collection"; Article 16 "a personal-information processor may not refuse products or services on the ground that the individual does not consent to, or withdraws consent to, processing - except where processing is necessary to provide the product or service"; Article 15 "where processing is based on consent, the individual may withdraw it; the processor shall provide a convenient way to withdraw"
- Notes: The test is one sentence: is this information necessary for this service. A map needing location is; a flashlight wanting contacts isn't. After installing an app, go to the phone's app-permissions page and switch off what isn't necessary. When it's genuinely needed, choose "allow this time only".

### 8. You have the right to view, copy, correct and delete your personal information - refused, you can sue
<!-- tags: money=0 time=low will=some benefit=mid lens=freedom -->
- Cost: Free. Only if the other side stalls do you need to complain or sue - a real lawsuit is months at minimum with your own lawyer fees, so complaining first pays better. The hard part is pressing repeatedly while they stall.
- TL;DR: You may demand a company let you view, copy, correct and delete your information. When the service stops, the retention period ends, or you withdraw consent, the company should delete on its own. Refusing you, it must give a reason; not acting, you can sue it in court directly. Closing the account and deleting the information are two things - deletion must be separately requested after closure.
- Benefit: Several situations require a company to delete proactively: the service stopped, the agreed retention period expired, you withdrew consent, the original collection purpose is achieved, and so on. It didn't delete - you may demand it. Refusing your exercise of these rights, it must give a reason. You may sue in court directly
- Evidence: A
- Sources: NPC Standing Committee (2021). Personal Information Protection Law. NPC website. <http://www.npc.gov.cn/npc/c2/c30834/202108/t20210820_313088.html>: Article 45 "individuals may access and copy their personal information from the processor... on request, the processor shall provide it promptly"; Article 46, the right to correct and supplement; Article 47 lists five proactive-deletion situations including "(1) the processing purpose is achieved, unachievable, or no longer necessary", "(2) the processor stops the product or service, or the retention period expires", "(3) the individual withdraws consent" - "where the processor hasn't deleted, the individual may request deletion"; Article 50 "the processor shall set up convenient mechanisms for accepting and handling rights requests; refusing one, it shall give a reason", "the individual may sue in a people's court under law"
- Notes: Closing the account and deleting personal information are two things - deletion must be separately requested after closure. Before switching phones or selling the old one: log out of every account on it, unbind them, then factory-reset. What the law gives is deletion after the fact - it can't pull back what has already leaked.

### 9. Face scanning isn't something you must accept: where another method exists, face can't be the only option - refuse it and they must give you an alternative
<!-- tags: money=0 time=low will=some benefit=mid lens=money -->
- Cost: Free. Asked to scan your face, ask "is there another way to verify". They say no - demand one. The hard part is asking out loud, face to face.
- TL;DR: Wherever another method accomplishes the same thing, face scanning can't be the only option. Refusing it, they must offer card-swiping, a password, an ID card or the like - and "then we can't serve you" may not be used to force you. Hotel rooms, public baths, changing rooms and restrooms: no one may install face-recognition equipment there.
- Benefit: The security measures for face-recognition technology write: "where another non-face-recognition method achieves the same purpose or equivalent business requirement, face recognition may not be the only verification method. Where an individual declines identity verification through facial information, another reasonable and convenient method shall be provided". Also: "no organization or individual may mislead, defraud or coerce an individual into accepting face-recognition identity verification on grounds like handling business or improving service quality". Processing facial information by consent takes "separate consent given voluntarily and explicitly on the basis of full information" - asked about this one thing alone, your own separate nod. You may withdraw consent, and the processor must offer a convenient way. Facial information of under-14s requires parental or guardian consent. Face-recognition equipment in public places "shall be necessary for maintaining public security" and carry prominent notices. Inside private spaces in public places - hotel rooms, public baths, public changing rooms, public restrooms - no organization or individual may install it. Facial information is stored inside the recognition device and not transmitted over the internet - except where laws or administrative regulations provide otherwise, or separate consent was obtained (nationwide, effective June 1, 2025)
- Evidence: A
- Sources: CAC and Ministry of Public Security (2025). Security measures for face-recognition technology application (Order No. 19, Articles 10, 12, 13; effective June 1, 2025). <https://www.cac.gov.cn/2025-03/21/c_1744174262156096.htm>
- Notes: The most common demands come from residential-compound gates, rental platforms, gyms and hotels wanting your face enrolled. When the other side says "the system only supports face", read the measures' wording back: "where another non-face-recognition method achieves the same purpose or equivalent business requirement, face recognition may not be the only verification method". Then demand card-swiping, a password, an ID card or the like. Still refused: report it to the local cyberspace authority. Where the state separately regulates face-based identity verification - some financial and government-service scenarios - those rules apply. The biggest difference between a face and a password: a leaked face can't be changed, so it deserves more caution than a password. An entity storing facial information of over 100,000 people must file with the province-level-or-above cyberspace authority within 30 working days - asking about that filing is one way to judge whether the other side is legitimate. The rights to view, correct and delete your personal information: entry 8.
