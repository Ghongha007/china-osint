# Research notes (checked 2026-11-19, from a non-Chinese IP, via curl)

## (a) Moved or died

- **China Labour Bulletin closed** (announced 12 June 2025). clb.org.hk now serves an unrelated "China Labour Bulletin Board" news and jobs site, and maps.clb.org.hk (the Strike Map) does not respond. Dropped. Copies of some CLB reports are kept by China Unofficial Archives (listed).
- **Weiboscope** (weiboscope.jmsc.hku.hk) did not respond twice; only 2012 data is on HKU's data hub. Dropped.
- **No response, dropped:** chinavitae.com, cgc.law.stanford.edu (Stanford Guiding Cases Project), ldzl.people.com.cn (People's Daily leaders database), utjd.org ("Requirements Not Met" error). Hamilton 2.0 dashboard (GMF) returned a 522 timeout.
- **Uyghur Tribunal** (uyghurtribunal.com) returned a WordPress database error; dropped for now, recheck later.
- **Moves:** strategictranslation.org to chinaopensourceobservatory.org; chinadialogue.net to dialogue.earth; BIS Entity List page to bis.gov (old bis.doc.gov path lands on the home page; the list itself is now at the EAR Supplement 4 page); CNKI to oversea.cnki.net from abroad; Xiaohongshu to rednote.com; HK Gazette to egazette.gld.gov.hk; HK Land Registry to www1.iris.gov.hk; CNIPA trademark search to /trademark-query; Jamestown China Brief to /publications/cb/; Global Fishing Watch map to /platform/map; NBS National Data to a new interface.
- NFRA replaced the CBIRC in 2023; old cbirc.gov.cn penalty links may break. data.ess.tsinghua.edu.cn says it has moved to data-starcloud.pcl.ac.cn (not listed).

## (b) Unsure

- **Military Procurement Network (plap.mil.cn):** resolves in DNS but did not respond. Older reports give plap.cn; the .mil.cn address is from prior knowledge and Chinese tender documents that name the 军队采购网, not from an official page we could open.
- **Section 1260H list:** we link the Federal Register notice (June 2026). The PDF on media.defense.gov and the war.gov release blocked our checker. The June 2026 update listed 188 entities; WuXi AppTec was removed on 10 Nov 2026 (Federal Register 2026-22840), leaving 187.
- **MOFCOM Unreliable Entity List:** there is no single consolidated list page we could find; the entry points to the announcements page.
- **CaseOpen** (caseopen.org, a CJO snapshot 2013 to 2024) blocked our checker with a bot check; we could not confirm who runs it.
- **Bot checks (Cloudflare, Vercel, Akamai):** ASPI Xinjiang Data Project, ASPI trackers, Shahit, Xinjiang Police Files, OHCHR, Espacenet, AEI tracker (dropped later for length), CASI, FCC and SEC blocked scripts. These are marked unreachable to be consistent with the India list, but normally load in a browser.
- **Mainland .gov.cn and commercial sites** returning 403/412/418/521 or timing out are marked unreachable; their URLs are from official references and prior knowledge. Some (CCDI, BSE, Tianyancha) served captchas or JavaScript challenges rather than blocking outright.
- "access" values are from prior knowledge plus page loads, not from running each search. Qichacha/Tianyancha free tiers change often.
- China Judgements Online loads, but registration needs a mainland phone number; since 2021 millions of rulings were removed and uploads fell sharply. In late 2023 the SPC announced an internal judgment database for court staff only.
- About 90 more checked candidates were cut to keep the list at 170 (for example Caixin, SCMP, Sixth Tone, Variflight, CelesTrak, NDRC, MIIT, CPPCC, OONI, GFWatch, Tibet Watch, HRW). They can be added back if wanted.

## (c) Prior art on GitHub

| Repo | Last push | Size |
|---|---|---|
| [paulpogoda/OSINT-Tools-China](https://github.com/paulpogoda/OSINT-Tools-China) | 2026-10-19 | 41 stars, ~53 links |
| [ArgeliusLabs/chinese_osint_search_dorks](https://github.com/ArgeliusLabs/chinese_osint_search_dorks) | 2026-06-21 | 121 stars; a search-technique guide (Baidu queries, pivots), not a link list |
| [isgmena/china-osint](https://github.com/isgmena/china-osint) | 2021-11-02 | 3 stars, stale; mostly news outlet lists |
| [SOsintOps/Wukong](https://github.com/SOsintOps/Wukong) | 2026-11-03 | 4 stars; installer for a China-focused OSINT workstation, not a source list |

Many other GitHub hits for "China OSINT" are phone-number, username or customer-vetting tools, which our rules exclude.

## Access from outside China

Many mainland government and commercial sites block or throttle foreign IP addresses, demand a mainland phone number to register, or serve captchas. A browser works more often than a script. Results are better during Beijing office hours. Some sites (CNKI, Wanfang) limit overseas users to abstracts.

## Legal and safety cautions for people in China

Searching, downloading or sharing material on Xinjiang, Tibet, protests or leaked documents can expose people inside China to police attention; logins tied to phone numbers are traceable. Scraping company registries and court sites has led to prosecutions of data firms under rules on illegal acquisition of data and personal information. The Data Security Law, Counter-espionage Law (revised 2023) and state secrets rules are broadly drafted and have been used against due-diligence firms and researchers. Do not ask sources in China to look things up for you without weighing the risk to them.

## Deliberately excluded

People-search services, phone and ID-number lookups (including the many ip138-style sites), vehicle and household-registration lookups, social-media de-anonymisation tools, and leaked or breached databases (for example the 2022 Shanghai police database, the 2020 Shanghai CCP member list, and ICIJ's China Cables material). The one exception is the Xinjiang Police Files, a documented research release; its entry is marked as leaked material.
