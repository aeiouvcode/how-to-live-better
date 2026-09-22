# Licenses for running a platform: cross-reference table and the server-choice decision table

This long-form piece belongs to chapter 26 of the README. It holds only three tables and a few of the easiest-to-get-wrong explanations. The entry text and sources are in the chapter itself. How to register a company and file its taxes is in chapter 12 (starting and running a business). The red lines for employed technicians are in chapter 11 (programmers and tech workers).

## 1. First figure out which kind of business yours is

One site often touches several business categories at once. However many it touches, that's how many licenses you need - picking one and filing it doesn't finish the job.

| What you're doing | Business category | What's needed | Main basis |
|---|---|---|---|
| An information site, personal blog or company homepage that takes no money | Non-commercial internet information service | ICP filing. Not a license - a check-in with the authority before opening the site | Article 4, Measures for the administration of internet information services |
| Paid memberships, value-added services, paid content | Commercial internet information service | Value-added telecom business operating license (information services). It polices the fact that you charge users | Same, Articles 3, 4, 7 |
| Matching buyers and sellers, handling transactions and orders | Online data processing and transaction processing | Value-added telecom business operating license (B21). It polices your processing transactions for buyers and sellers | Telecom business classification catalogue (2015 edition), B21 |
| Livestreams with hosts on camera, game streaming | Online performance | Online culture operating license, scope covering online performance. Without it, no hosts on camera on your site | Article 4, Measures for the administration of online performance business activities |
| Making your own video programs, aggregating programs from elsewhere, or letting users upload video | Internet audiovisual program service | License for disseminating audiovisual programs on the information network. It polices video programs playing on the site | Articles 7, 8, Provisions on the administration of internet audiovisual program services |
| Selling goods inside livestreams | Online livestream marketing | The licenses from the rows above as applicable; plus verifying merchants and keeping records | Article 8, Measures for the administration of online livestream marketing (trial) |
| News and current-affairs content | Internet news information service | Internet news information service license. Without it, no news on the site | Article 5, Provisions on the administration of internet livestream services |
| Selling hosting and bandwidth from your own server room | Internet data-center business, internet access-service business | Value-added telecom business operating licenses (B11, B14). They police selling server rooms and bandwidth to others | Telecom business classification catalogue (2015 edition), B11, B14 |

Which livestream maps to which license is said most plainly in the 2021 guiding opinion from seven departments: "a livestream platform conducting commercial online performance activities must hold an Online Culture Operating License and complete an ICP filing; a livestream platform conducting online audiovisual program services must hold a License for Disseminating Audiovisual Programs on the Information Network (or complete registration in the national online audiovisual platform information registration system) and complete an ICP filing; a livestream platform conducting internet news information services must hold an Internet News Information Service License."

In plain words, three kinds. Hosts performing: the Online Culture Operating License. Online audiovisual programs: the License for Disseminating Audiovisual Programs on the Information Network, or registration in the national online audiovisual platform information registration system. News: the Internet News Information Service License. The first two also both need the ICP filing.

### Three easy points to get wrong

**An individual cannot get the value-added telecom license.** The first application condition reads "the operator is a lawfully established company." Meaning you need a company first. An individual applying with an ID card gets turned down. Operating within one province only: registered capital of at least 1 million yuan. Across provinces: at least 10 million yuan. After materials go in, the authority's review period is 60 days. The license, once issued, is valid 5 years. To run a paid business, set the company up first - how is in chapter 12 (starting and running a business).

**The audiovisual-program license is basically out of reach for private companies.** The application conditions read "possessing legal-person status, being a wholly state-owned or state-controlled unit." Meaning this license goes only to state-funded or state-controlled units. So the long-video and self-produced-program routes are closed to individual founders. For livestreaming, take the online culture operating license line.

**No official document states outright that "e-commerce platforms must get EDI."** EDI is the B21 license in the table above, formally called online data processing and transaction processing. The industry ministry's service guide says only "apply for the telecom business operating license corresponding to your business definition." The ministry has also twice answered separately: ride-hailing platforms need only a website filing, and rights-type and bulk-commodity trading platforms likewise need only a website filing. So this book quotes only B21's definition verbatim. Whether your specific business needs it is left to you and the local communications administration to judge. Before starting, call the local communications administration once and ask.

## 2. The platform's own daily obligations

The license only permits you to open. Below is what must be done every day after opening. The fines for failing them are written in chapter 26's entries.

| Obligation | Hard number | Source |
|---|---|---|
| Verify and register merchants selling on your platform | Re-verify and update at least every six months | Article 24, Measures for the supervision of online transactions |
| Report merchants' identity information upward | Every January and July, to the market regulator | Same, Article 25 |
| Report tax-related information upward | Within one month after each quarter ends, to the tax authority | Article 4, Provisions on tax-related information reporting by internet platform enterprises |
| Keep transaction information | No less than three years from the transaction's completion | Article 31, E-Commerce Law |
| Keep livestream content and logs | Sixty days | Article 16, Provisions on the administration of internet livestream services |
| Keep online-performance video | No less than sixty days | Article 13, Measures for the administration of online performance business activities |
| Keep network logs | No less than six months | Article 23, item 3, Cybersecurity Law |
| Handle infringement notices | Forward the merchant's statement to the complainant; fifteen days after forwarding with no follow-up, restore | Article 43, E-Commerce Law |
| Provide a complaint and report channel | In a prominent place, easy to click | Article 16, Provisions on the ecological governance of online information content |

Retention periods come in four clocks, each running its own. Transaction information: three years. Livestream content: sixty days. Network logs: six months. Platform merchants' identity information: three years from the day the merchant leaves the platform. Design your storage plan to the longest one, not the shortest.

## 3. Choosing a server: picking among the three tiers

Answer the questions below first, then compare prices.

| Question | If the answer is | Then |
|---|---|---|
| Can you live with the site down for a day | Yes | The cheapest VPS - virtual server - is enough |
| Any user registration, transactions or uploads | Yes | Use a mainstream cloud vendor's cloud host. Pick one that can snapshot the whole machine anytime and scale up temporarily |
| Anyone dedicated to managing the server | No | Stay away from colocating a whole machine in a data center |
| Is bandwidth or hardware the biggest cost | Yes, and someone manages it | Only now consider colocating a whole machine in a data center |

**Small providers aren't unusable - check their credentials before using one.** Colocating machines in a data center and providing internet access to others are themselves licensed activities - value-added telecom businesses. The check: open the industry ministry's telecom business market management system at tsm.miit.gov.cn and search the company's full registered name. No license found: rule it out directly. The kind that's half the price usually carries three risks. One, the machines are oversold. Two, the owner disappears. Three, the upstream gets blocked. When one of the three really happens and the provider is licensed, you can still complain to the communications administration. Unlicensed, you don't even know who to appeal to.

**Domestic or overseas.** A server in China means doing the filing; access providers may not connect unfiled sites. Going overseas does skirt the filing. But your users are in China, and the money you collect is in China. Not one of the platform obligations written in entries 5 to 10 of chapter 26 goes away. Overseas also adds a data-export layer. Sending Chinese users' personal information to a machine abroad is exactly what "export" means. Export requires meeting one of the four conditions listed in Article 38 of the Personal Information Protection Law, plus the person's separate consent - "separate" meaning it can't be bundled into a catch-all agreement clicked through together. How many people are involved is counted "cumulatively from January 1 of the current year." Under 100,000 people: none of the three routes below is needed. 100,000 to 1,000,000: either sign the standard contract or get certified. Over 1,000,000: declare a security assessment.

**Backups.** Keep backups in at least two places - and don't put both in the same provider's same region. This one has no regulatory basis; it's pure experience.

## 4. The boundary of this material

- Every provision mentioned above: the sources field of chapter 26 in this book's README is authoritative - document numbers, article numbers and links are there.
- These rules change fast. This chapter's content was verified in September 2026. Before actually citing anything, open the original page once more yourself. Two places especially deserve your own look. One, the Cybersecurity Law - article numbers were adjusted from January 1, 2026. Two, the minor rules for livestream tipping - switched to age tiers in April 2026.
- A few places couldn't get the original text; each is written out in the [verification records](https://github.com/eternity4719/HowToLiveBetter/tree/main/docs/%E6%A0%B8%E5%AE%9E%E8%AE%B0%E5%BD%95) (in Chinese). One is whether e-commerce platforms truly must get EDI and whether any official text says so. The other is the judicial interpretation that treats unlicensed online-culture or audiovisual operation directly as the crime of illegal business operation.
