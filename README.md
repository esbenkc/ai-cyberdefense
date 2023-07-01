# AI Cyberdefense

🔥 A repository for collecting cyberdefense thoughts, books, and documents about AI cyberdefense

## Resources

### General cybersecurity

- [list] [Goodreads list of books](https://www.goodreads.com/review/list/72754976?shelf=cybersecurity&sort=avg_rating#)
  - [book] [Silence on the Wire](https://cloudflare-ipfs.com/ipfs/bafykbzaced7qlzap77wrfegoup2djxbeafqeeasp47sgx563hmxhdnn4usfzg?filename=Michal%20Zalewski%20-%20Silence%20on%20the%20Wire_%20A%20Field%20Guide%20to%20Passive%20Reconnaissance%20and%20Indirect%20Attacks-No%20Starch%20Press%20%282005%29.pdf): It is supposedly one of the better introductions to "how the internet works"
- [post] [Overview in Danish](<https://www.bdo.dk/da-dk/services/advisory/cybersikkerhed?utm_source=bing&utm_medium=cpc&utm_campaign=Service%20-%20Cybersikkerhed%20(Dansk)&utm_term=Cyber%20Security&utm_content=Cyber%20Security>)
- [report] [MIT Cybersecurity review of 20 countries](https://www.technologyreview.com/2022/11/15/1063189/the-cyber-defense-index-2022-23/)
- [website] [Live cyber threat map](https://threatmap.checkpoint.com/)
- [whitepaper] [Checkpoint's guide for adopting a threat prevention approach to cybersecurity](https://pages.checkpoint.com/preventing-unknown-zero-day-attacks-whitepaper.html)
- [report] [IBM's estimates for costs of data breaches](https://www.ibm.com/reports/data-breach)
- [article] [Building a vulnerability benchmark](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/iet-ifs.2018.5647)
- [guidelines] [NIST Framework for Improving Critical Infrastructure Cybersecurity](https://www.baltimorecityschools.org/sites/default/files/inline-files/NIST.CSWP_.04162018.pdf)
- [article] [Social cybersecurity: an emerging science](https://link.springer.com/article/10.1007/s10588-020-09322-9)
- [textbook] [Cybersecurity for Industry 4.0](https://link.springer.com/book/10.1007/978-3-319-50660-9)

### AI cybersafety

- [article] [Review: machine learning techniques applied to cybersecurity](https://link.springer.com/article/10.1007/s13042-018-00906-1)
- [article] [Cybersecurity data science: an overview from machine learning perspective](https://link.springer.com/article/10.1186/s40537-020-00318-5)
- [article] [Machine learning approaches to IoT security: A systematic literature review](https://www.sciencedirect.com/science/article/pii/S2542660521000093)
- [sequence] [AI infosec: first strikes, zero-day markets, hardware supply chains, adoption barriers](https://www.lesswrong.com/posts/kvk2ZorXui4YB4zvc/ai-infosec-first-strikes-zero-day-markets-hardware-supply)
- [post] [AI Safety in a World of Vulnerable Machine Learning Systems](https://www.lesswrong.com/posts/ncsxcf8CkDveXBCrA/ai-safety-in-a-world-of-vulnerable-machine-learning-systems-1)

## Conferences and events

| Name                                                                 | When?          | Description           | Location  |
| -------------------------------------------------------------------- | -------------- | --------------------- | --------- |
| [44CON](https://44con.com/2023/03/20/44con-2023-early-bird-tickets/) | 13-15 Sep 2023 |                       | London    |
| [CCCamp](https://events.ccc.de/camp/2023/infos/)                     | 15-19 Aug 2023 | A hacker camp         | Berlin    |
| [SEC-T](https://www.sec-t.org/)                                      | 12-15 Sep 2023 | Conf. w/ talks & Q&As | Stockholm |

## Products

- [Palantir AIP](https://www.palantir.com/platforms/aip/)
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)
-

## AI organization commitments

- [Anthropic Trust](https://trust.anthropic.com/)
- [OpenAI Trust](https://trust.openai.com/)

## Notes

### Overview of attacks and defenses

| Attack                              | Defense                                                               | Defense description                                                                       |
| ----------------------------------- | --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Malware attacks: Malicious software | Antivirus, antimalware (AMW) software, firewalls                      | AMW: Signature-based (known malware) and behaviour-based detection (suspicious activity). |
| Phishing attacks                    | User education, email filtering, network traffic flagging             |                                                                                           |
| Denial-of-service attacks           | Network capacity, CDN, intrusion detection & prevention system (IDPS) | IDPS monitors network traffic and warns or blocks                                         |

## Project ideas

- Malware detection: AI has the potential to provide much more accurate and faster detection of malicious activity than traditional signature-based detection. To design this kind of system, you would need to first create a data set of network traffic. This data set would need to include both malicious and benign traffic so that the AI could learn to distinguish between the two. | Network traffic dataset
