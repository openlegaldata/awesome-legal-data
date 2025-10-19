# Awesome Legal Data

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A curated list of resources dedicated to legal data. 
The collection contains data sets, corpora, benchmarks, tools and other links related to the legal domain — grouped by region/country. 
Most resources are openly available. 

**Legend:** *(Open)* = publicly accessible (may require free key); *(Commercial)* = paid/subscription; *(API)* = offers programmatic access/bulk data.


## Global & Multi‑Jurisdictional

- [WorldLII](http://www.worldlii.org/) — Federated gateway to free legal information worldwide (legislation, case law, treaties) across national LIIs. *(Open)*
- [vLex](https://www.vlex.com/) — Global legal research platform covering 100+ jurisdictions; case law, legislation, journals, and analytics. *(Commercial)*
- [Westlaw](https://legal.thomsonreuters.com/en/westlaw) — Thomson Reuters’ flagship global legal research service (cases, statutes, citators, secondary sources). *(Commercial)*
- [LexisNexis / Lexis+](https://www.lexisnexis.com/) — Global legal content (case law, statutes, Practical Guidance, news). *(Commercial)*
- [HeinOnline](https://home.heinonline.org/) — Extensive law journal & historical legislative archives; treaties; session laws. *(Commercial)*
- [WIPO Lex](https://www.wipo.int/wipolex/) — Global database of IP laws/treaties and **WIPO Lex-Judgments** for selected IP case law. *(Open)*
- [SSRN (Legal Scholarship Network)](https://www.ssrn.com/) — Open repository of legal scholarship/preprints. *(Open)*
- [OpenAlex](https://openalex.org/) — Scholarly metadata/abstracts (including law journals) with an **API**; useful for legal literature mining. *(Open, API)*
- [Pile-of-Law](https://pile-of-law.github.io/) — 256GB open corpus of English legal/administrative text (opinions, regulations, contracts) for legal NLP. *(Open)*
- [MultiLegalPile](https://huggingface.co/datasets/joelito/legal-pile) — Multilingual/multijurisdiction legal text corpus for LLM training (24 languages). *(Open)*
- [LexGLUE](https://github.com/coastalcph/lex_glue) — Benchmark suite for legal language understanding (multi-task classification across legal domains). *(Open)*
- [LEDGAR](https://nlp.jhu.edu/ledgar/) — Contract clause classification dataset (common clause types from EDGAR filings). *(Open)*
- [ContractNLI](https://github.com/nyu-mll/contract-nli) — Natural-language inference dataset for contracts (entailment/contradiction/neutral). *(Open)*
- [CUAD](https://www.atticusprojectai.org/cuad) — Contract Understanding Atticus Dataset with expert-annotated clauses across 13 categories. *(Open)*
- [Massive Legal Embedding Benchmark (MLEB)](https://isaacus.com/mleb) - A multidomain open-source benchmark for legal information retrieval. *(Open)*

## Europe & European Union

- [EUR-Lex](https://eur-lex.europa.eu/) — Official EU law (treaties, directives, regulations, decisions, OJ). Bulk downloads and **API**. *(Open, API)* [[HF](https://huggingface.co/datasets/joelniklaus/eurlex_resources)]
- [CURIA (CJEU)](https://curia.europa.eu/) — Court of Justice & General Court case law (judgments, opinions, orders). *(Open)*
- [HUDOC (ECHR)](https://hudoc.echr.coe.int/) — European Court of Human Rights judgments, decisions, and summaries. *(Open)*
- [N-Lex](https://n-lex.europa.eu/) — One-stop portal into each EU Member State’s national legislation databases. *(Open)*
- [JRC-Acquis](https://ec.europa.eu/jrc/en/language-technologies/jrc-acquis) — Multilingual parallel corpus of EU law (Acquis Communautaire) for MT/NLP. *(Open)*
- [MultiEURLEX](https://github.com/nlpaueb/multi_eurlex) — ~65k EU legal acts in 23 languages annotated with EuroVoc; for multilabel classification/zero-shot. *(Open)*
- [OP (Publications Office) Data Portal](https://data.europa.eu/en) — EU Open Data incl. cellar, EuroVoc, and legal metadata via **APIs**. *(Open, API)*
- [EU Open Data Portal — Cellar](https://op.europa.eu/en/web/about-us/our-data) — Linked Data repository for EU legal documents (RDF/SPARQL). *(Open, API)*
- [MultiEURLEX - A multi-lingual and multi-label legal document classification dataset for zero-shot cross-lingual transfer](https://arxiv.org/abs/2109.00904)
- [Mining Legal Arguments in Court Decisions - Data and software (European Court of Human Rights (ECHR))](https://github.com/trusthlt/mining-legal-arguments)

*(Tip: The EU **N‑Lex** portal links to the official law databases of all EU/EEA countries.)*


### United Kingdom

- [legislation.gov.uk](https://www.legislation.gov.uk/) — Official consolidated UK legislation (Acts, SIs, devolved). **API** & bulk XML. *(Open, API)*
- [Find Case Law (The National Archives)](https://caselaw.nationalarchives.gov.uk/) — Free database of court & tribunal judgments (England & Wales). *(Open)*
- [BAILII](https://www.bailii.org/) — British & Irish Legal Information Institute (UK/IE case law & legislation). *(Open)*
- [ICLR](https://www.iclr.co.uk/) — Official Law Reports and case analysis. *(Commercial)*
- [Westlaw UK](https://legal.thomsonreuters.com/en/uk-and-ireland/westlaw-uk) — UK cases, legislation, journals, and analytics. *(Commercial)*
- [Lexis+ UK](https://www.lexisnexis.co.uk/legal/lexisplus-uk) — UK case law, legislation, commentary (Halsbury’s). *(Commercial)*


### Germany

- [Gesetze im Internet](https://www.gesetze-im-internet.de/) — Official federal statutes & regulations (BMJ). *(Open)*
- [Rechtsprechung im Internet](https://www.rechtsprechung-im-internet.de/) — Official portal indexing German federal high-court decisions. *(Open)*
- [NeuRIS (Neues Rechtsinformationssystem)](https://digitalservice.bund.de/projekte/neues-rechtsinformationssystem) *(API)*
- [OpenJur](https://openjur.de/) — Community open case-law database (DE & EU decisions). *(Open)*
- [Open Legal Data (DE)](https://openlegaldata.io/) — Open platform & **API** for German legal documents/case law. *(Open, API)*  [(HF)](https://huggingface.co/openlegaldata)
- [juris](https://www.juris.de/) — Comprehensive German legal database (cases, laws, journals). *(Commercial)*
- [A Dataset of German Legal Documents for Named Entity Recognition (Lynx Project)](https://github.com/elenanereiss/Legal-Entity-Recognition)
- [GerDaLIR: A German Dataset for Legal Information Retrieval](https://github.com/lavis-nlp/GerDaLIR) [(Paper)](https://aclanthology.org/2021.nllp-1.13.pdf)
- [gesp: Download all available German court decisions straight from the command line](https://github.com/niklaswais/gesp)
- [German Legal Sentences (GLS): Semantic sentence matching and citation recommendation](https://huggingface.co/datasets/lavis-nlp/german_legal_sentences)
- [dejure: German laws and court decisions including citations (no API)](https://dejure.org/)


### France

- [Légifrance](https://www.legifrance.gouv.fr/) — Official French legislation (codes, laws) and selected jurisprudence. *(Open)*
- [Judilibre (Cour de cassation)](https://www.courdecassation.fr/), [Judilibre API](https://www.courdecassation.fr/toutes-les-actualites/2021/10/01/judilibre-les-decisions-judiciaires-en-open-data) — Open data/API for Court of Cassation decisions. *(Open, API)*
- [Doctrine.fr](https://www.doctrine.fr/) — Aggregated French case law with analytics. *(Commercial)*
- [Dalloz](https://www.dalloz.fr/) — Codes, jurisprudence, and commentary (Encyclopédie Dalloz). *(Commercial)*


### Italy

- [Normattiva](https://www.normattiva.it/) — Official consolidated Italian legislation (1861-present). *(Open)*
- [Italgiure (Corte di Cassazione)](https://www.italgiure.giustizia.it/) — Supreme Court case law database/portal. *(Mixed/Institutional)*
- [De Jure (Giuffrè Francis Lefebvre)](https://dejure.giuffre.it/) — Case law, legislation, commentary. *(Commercial)*
- [Pluris (Wolters Kluwer)](https://pluris.wolterskluwer.it/) — Comprehensive Italian legal research platform. *(Commercial)*


### Spain

- [BOE](https://www.boe.es/) — Spain’s Official State Gazette; laws & regulations + **Open Data**. *(Open, some API)* • Open data: <https://www.boe.es/datosabiertos/>
- [CENDOJ](https://www.poderjudicial.es/cgpj/en/Services/CENDOJ/) — Judicial Documentation Center (Supreme Court & higher courts’ jurisprudence). *(Open)*
- [Westlaw Spain](https://www.thomsonreuters.es/es/soluciones-juridicas/westlaw) — Case law, legislation, commentary. *(Commercial)*
- [La Ley (Wolters Kluwer)](https://laley.wolterskluwer.es/) — Spanish legal research platform. *(Commercial)*


### Netherlands

- [wetten.nl](https://wetten.overheid.nl/) — Official consolidated Dutch legislation (XML/HTML). *(Open)*
- [Rechtspraak (Uitspraken)](https://uitspraken.rechtspraak.nl/) — Official case law portal (search judgments). *(Open)*
- [Kluwer Navigator](https://www.navigator.nl/) — Dutch commercial legal research. *(Commercial)*


### Finland

- [Finlex](https://www.finlex.fi/) — Finnish legislation, case law, government bills; machine-readable access. *(Open)*


### Poland

- [ISAP (Sejm)](https://isap.sejm.gov.pl/) — Internet System of Legal Acts (Polish legislation). *(Open)*
- [Legalis / LEX (Wolters Kluwer)](https://www.wolterskluwer.com/pl-pl/solutions/lex) — Commercial Polish legal databases. *(Commercial)*
- [mojeprawo.io](https://mojeprawo.io/)


### Switzerland

- [Fedlex](https://www.fedlex.admin.ch/) — Official Swiss federal law portal (RDF/Linked Data available). *(Open)*
- [Swiss Federal Supreme Court (BGer/BGerentscheid)](https://www.bger.ch/) — Search engine for decisions. *(Open)*
- [Entscheidsuche](https://entscheidsuche.ch/) — Meta-search across Swiss case law sources. *(Open)*
- [Swisslex](https://www.swisslex.ch/) — Commercial Swiss legal research. *(Commercial)*
- [Swiss-Judgment-Prediction: A Multilingual Legal Judgment Prediction Benchmark](https://arxiv.org/abs/2110.00806)


### Austria

- [RIS](https://www.ris.bka.gv.at/) — Federal Legal Information System (legislation, case law). *(Open)*


### Czech

- [Czech Court Decisions Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-3052) [(Paper)](https://arxiv.org/pdf/1910.09513.pdf)


### Norway

- [rettspraksis.no](https://rettspraksis.no/wiki/Forside)

---

### Turkey
- [https://acikveri.yagiz.dev/] - Open Legal Turkey

## North America

### United States

- [GovInfo](https://www.govinfo.gov/) — U.S. Government Publishing Office—authenticated federal documents (USC, CFR, Federal Register) + [bulk data/APIs](https://www.govinfo.gov/). *(Open, API)*
- [U.S. Code (XML)](https://uscode.house.gov/download/download.shtml) — Bulk downloads of the United States Code in XML. *(Open)*
- [eCFR](https://www.ecfr.gov/) — Up-to-date Code of Federal Regulations; [API](https://www.ecfr.gov/) via Federal Register. *(Open, API)*
- [Federal Register](https://www.federalregister.gov/) — Daily federal rules/notices; full [API](https://www.federalregister.gov/). *(Open, API)*
- [case.law (Caselaw Access Project)](https://case.law/) — ~6.7M U.S. opinions (1658–2018); bulk & [API](https://case.law/). *(Open, API)*
- [CourtListener](https://www.courtlistener.com/) — Millions of opinions + dockets via RECAP; robust [API](https://www.courtlistener.com/)/bulk. *(Open, API)*
- [Free Law Project](https://free.law).
- [PACER](https://pacer.uscourts.gov/) — Federal court dockets & filings (fees apply). *(Commercial/Gov)*
- [Oyez](https://www.oyez.org/) — SCOTUS audio, transcripts, and case summaries (education-oriented). *(Open)*
- [Supreme Court Database (SCDB)](http://scdb.wustl.edu/) — Coded metadata for every SCOTUS decision (1791–). *(Open)*
- [CaseHOLD (AI2)](https://huggingface.co/datasets/allenai/casehold) — Multiple-choice QA over U.S. holdings (legal reasoning benchmark). *(Open)*
- [EDGAR](https://www.sec.gov/edgar) — SEC corporate filings (contracts, 10-Ks), bulk + [API](https://www.sec.gov/edgar). *(Open, API)*
- [Bloomberg Law](https://www.bloomberglaw.com/) — Dockets, analytics, secondary sources. *(Commercial)*
- [Fastcase](https://www.fastcase.com/) — Case law & statutes with citator; often via bar membership. *(Commercial)*
- [Westlaw / Lexis+](https://legal.thomsonreuters.com/) • [Lexis+](https://www.lexisnexis.com/) — Comprehensive U.S. primary/secondary law & citators (KeyCite/Shepard’s). *(Commercial)*
- [H2O Open Case Book](https://opencasebook.org/)


### Canada

- [CanLII](https://www.canlii.org/) — Pan-Canadian case law & legislation; [API](https://www.canlii.org/) for developers (key required). *(Open, API)*
- [Justice Laws (Canada)](https://laws-lois.justice.gc.ca/) — Official consolidated federal statutes & regulations. *(Open)*
- [Supreme Court of Canada Judgments](https://scc-csc.lexum.com/) — Full-text decisions (LexUM). *(Open)*
- [WestlawNext Canada](https://www.thomsonreuters.ca/en/westlaw.html) / [Lexis Advance Quicklaw](https://www.lexisnexis.ca/en) — Commercial Canadian legal research. *(Commercial)*
- [A2AJ] (https://a2aj.ca/) - Open Legal Canadian Database

### Mexico

- [DOF (Diario Oficial de la Federación)](https://www.dof.gob.mx/) — Official Gazette of the Federation (laws/decrees, searchable). *(Open)*
- [SCJN — Sistema de Jurisprudencia (IUS)](https://www2.scjn.gob.mx/ius/) — Supreme Court of Justice jurisprudence search. *(Open)*
- [PJF (Federal Judiciary)](https://www.gob.mx/cjf) — Case law/jurisprudence and statistics portals. *(Open)*

---

## Asia

### India

- [India Code](https://www.indiacode.nic.in/) — Central repository of Central/State Acts and subordinate legislation. *(Open)*
- [Supreme Court of India — Judgments](https://main.sci.gov.in/judgments) — Official search/portal for SC judgments. *(Open)*
- [eCourts Services / NJDG](https://ecourts.gov.in/) • [NJDG](https://njdg.ecourts.gov.in/) — Case status & national judicial data grid (stats/open data). *(Open)*
- [Indian Kanoon](https://indiankanoon.org/) — Aggregated judgments (SC/HC/tribunals) + statutes; full-text search. *(Open)*
- [SCC Online](https://www.scconline.com/) — Leading commercial database (EBC): SC/HC/tribunals + commentary. *(Commercial)*
- [Manupatra](https://www.manupatrafast.com/) — Comprehensive commercial Indian legal research. *(Commercial)*
- [OpenNyAI Datasets](https://opennyai.org/datasets) — Indian legal NLP datasets (judgment summarization, QA, translation). *(Open)*
- [ILDC (Indian Legal Documents Corpus)](https://github.com/Legal-NLP-EkStep/ILDC) — Public datasets for Indian judgment analysis/summarization (various releases). *(Open)*


### China

- [National Laws & Regulations Database (国家法律法规数据库)](https://flk.npc.gov.cn/) — Official centralized repository of PRC laws/regulations. *(Open)*
- [China Judgments Online (裁判文书网 / Wenshu)](https://wenshu.court.gov.cn/) — Supreme People’s Court open repository of court judgments. *(Open)*
- [PKULaw (北大法宝)](https://www.pkulaw.com/) • [LawInfoChina](https://www.lawinfochina.com/) — Comprehensive Chinese legal database; English via LawInfoChina. *(Commercial)*
- [OpenLaw (开放法学)](https://openlaw.cn/) — Open legal case platform & analytics (coverage varies). *(Open/Mixed)*
- [CAIL2018](https://github.com/china-ai-law-challenge/CAIL2018) — Large-scale Chinese legal judgment datasets (charges, articles, term prediction). *(Open)*
- [LeCaRD](https://github.com/PKU-ICST-LeCaRD/LeCaRD) — Chinese Legal Case Retrieval Dataset for precedent search benchmarks. *(Open)*
- [JEC-QA](https://github.com/china-ai-law-challenge/JEC-QA) — Judicial Examination Challenge QA dataset (multi-choice legal questions). *(Open)*


### Japan

- [e-Gov Law Search (e-Gov法令検索)](https://elaws.e-gov.go.jp/) — Official portal for Japanese laws/regulations; [API](https://elaws.e-gov.go.jp/) (XML). *(Open, API)*
- [Japanese Law Translation](https://www.japaneselawtranslation.go.jp/) — MOJ database of unofficial English translations of key laws. *(Open)*
- [Supreme Court of Japan — Judgments](https://www.courts.go.jp/app/hanrei_en/) — Search Supreme Court decisions (some English summaries). *(Open)*
- [WIPO Lex-Judgments (Japan IP)](https://wipolex.wipo.int/en/judgments) — Selected Japanese IP judgments in English. *(Open)*
- [COLIEE](https://sites.ualberta.ca/~rabelo/COLIEE2023/) — Legal Information Extraction & Entailment shared task (JP Civil Code QA, case retrieval). *(Open)*
- [Westlaw Japan](https://go.westlawjapan.com/) / [LexisNexis Japan](https://www.lexisnexis.jp/) — Commercial JP legal research suites. *(Commercial)*
- [Competition on Legal Information Extraction/Entailment (COLIEE 2020)](https://sites.ualberta.ca/~rabelo/COLIEE2020/)

## South Korea
- [https://open.law.go.kr/LSO/openApi/guideList.do] - Open Legal Data

### Russia
- [https://github.com/irlcode/RusLawOD] - Open Legal Data
- [IPBD.ru] - Open Legal Data
---

## Brazil

- [LexML Brasil](https://www.lexml.gov.br/) — Federated search over Brazilian legislation & legal docs; open standards. *(Open)*
- [Diário Oficial da União (DOU)](https://www.in.gov.br/) — Federal Official Gazette (laws, decrees). *(Open)*
- [STF — Supremo Tribunal Federal](https://portal.stf.jus.br/jurisprudencia/) — Supreme Court decisions/jurisprudence portal. *(Open)*
- [STJ — Superior Tribunal de Justiça](https://scon.stj.jus.br/SCON/) — Decisions search (SCON). *(Open)*
- [CNJ — Dados Abertos](https://www.cnj.jus.br/sistemas/dadosabertos/) — National Council of Justice open judicial data & indicators. *(Open)*
- [Jusbrasil](https://www.jusbrasil.com.br/) — Massive legal search (cases, legislation, gazettes) + community; premium features. *(Open/Commercial)*
- [vLex Brasil](https://br.vlex.com/) — Commercial platform for Brazilian law with analytics. *(Commercial)*


## Australia

- [Australasian Legal Information Institute](http://www.austlii.edu.au/)
- [Open Australian Legal Corpus: The First Multijurisdictional Open Corpus of Australian Legislative and Judicial Documents](https://huggingface.co/datasets/umarbutler/open-australian-legal-corpus)


---

## Other datasets

- [LexGLUE: A Benchmark Dataset for Legal Language Understanding in English](https://github.com/coastalcph/lex-glue)
- [PileOfLaw](https://github.com/Breakend/PileOfLaw)

## Tools

- [Blackstone - A spaCy pipeline and model for NLP on unstructured legal text.](https://github.com/ICLRandD/Blackstone)
- [Pseudo-anonymization of French legal cases](https://github.com/ELS-RD/anonymisation)
- [Scripts to crawl English legal corpora](https://github.com/iliaschalkidis/LegalCrawler)
- [LEGAL-BERT: The Muppets straight out of Law School](https://arxiv.org/abs/2010.02559)
- [Law-OMNI-BERT-Project](https://github.com/Lukas-Justen/Law-OMNI-BERT-Project)

## Other links

- [Liquid-Legal-Institute/Legal-Text-Analytics](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics)
- [Natural Legal Language Processing Workshop](https://nllpw.org/)

## Contribute

Have a dataset or platform to add (or found a broken link)? Open a PR or file an issue in your repo.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
