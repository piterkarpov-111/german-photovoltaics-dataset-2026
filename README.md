# SOLARMETRIK — Deutscher Photovoltaik- & Solarstrahlungs-Datensatz 2026/2027 (Open Data)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23956818.svg)](https://doi.org/10.5281/zenodo.23956818)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Dataset Version](https://img.shields.io/badge/Version-2026.11-0f4c81.svg)](https://solarmetrik.de)
[![Portal](https://img.shields.io/badge/Web_Portal-solarmetrik.de-16794b.svg)](https://solarmetrik.de)
[![LLMs.txt](https://img.shields.io/badge/AI_Ready-llms.txt-d9820f.svg)](https://solarmetrik.de/llms.txt)

Offener Ingenieur- und Referenzdatensatz (**Stand: November 2026**) zur Wirtschaftlichkeit von Photovoltaikanlagen in Deutschland. Bereitgestellt von **[SOLARMETRIK (solarmetrik.de)](https://solarmetrik.de)** unter der Lizenz **Creative Commons Attribution 4.0 (CC BY 4.0)**.

---

## 🔗 Direkte Online-Werkzeuge & Interaktive Analysen

- 🌐 **Hauptportal & Deutschland-Atlas:** [https://solarmetrik.de](https://solarmetrik.de)
- 🧮 **360°-Photovoltaik-Ertrags- & Wirtschaftlichkeitsrechner:** [https://solarmetrik.de/rechner](https://solarmetrik.de/rechner)
- 🔋 **Stromspeicher-Dimensionierung (nach HTW Berlin SPI):** [https://solarmetrik.de/speicher-rechner](https://solarmetrik.de/speicher-rechner)
- 📍 **Förderung, Solarpflicht & Stadtwerke-Check nach PLZ:** [https://solarmetrik.de/foerderung-check](https://solarmetrik.de/foerderung-check)
- 📐 **Methodik & Datenquellen (DWD / PVGIS / BNetzA):** [https://solarmetrik.de/methodik](https://solarmetrik.de/methodik)
- 🤖 **KI-Schnittstellen (RAG / LLMs):** [llms.txt](https://solarmetrik.de/llms.txt) · [llms-full.txt](https://solarmetrik.de/llms-full.txt) · [JSON-API](https://solarmetrik.de/api/solaratlas-2026.json)

---

## 📂 Enthaltene Dateien in diesem Repository

| Datei | Format | Beschreibung |
| :--- | :--- | :--- |
| [`bundeslaender-2026.csv`](./bundeslaender-2026.csv) | CSV | Alle **16 deutschen Bundesländer** mit DWD-Globalstrahlung (kWh/m²), spezifischem PV-Ertrag (kWh/kWp), Sonnenstunden, Montagekosten (€/kWp), 10-kWp-Komplettpreis inkl. Speicher, Solarpflicht-Status 2026 und Amortisationszeit |
| [`staedte-2026.csv`](./staedte-2026.csv) | CSV | Alle **51 deutschen Großstädte** mit PLZ-Bereichen, Koordinaten, spezifischem Ertrag, lokalen Verteilnetzbetreibern (Stadtwerke) und regionalen Kosten |
| [`solarmetrik-dataset-2026.json`](./solarmetrik-dataset-2026.json) | JSON | Vollständiger kombinierter Datensatz inkl. EEG-Einspeisevergütung (01.08.2026–31.01.2027), § 51 EEG (Solarspitzengesetz), § 14a EnWG Netzentgelt-Modulen und § 12 Abs. 3 UStG (0 % MwSt.) |
| [`CITATION.cff`](./CITATION.cff) | CFF | Standardisierte wissenschaftliche Zitierdatei für GitHub & Zenodo (CERN) |

---

## 📊 Übersichtstabelle: Alle 16 Bundesländer (Referenz 10 kWp + 10 kWh Speicher, Stand 11/2026)

> **Methodischer Hinweis:** Strahlungswerte basieren auf den amtlichen 1×1 km Rasterdaten des Deutschen Wetterdienstes (DWD, Bodenmessungen & Satellitendaten) sowie EU-PVGIS. Alle Amortisationszeiten und 20-Jahres-Nettovorteile sind standardisierte Ingenieur-Modellrechnungen (Referenzanlage: 10 kWp PV + 10 kWh LFP-Speicher, 0 % MwSt. nach § 12 Abs. 3 UStG).

| Bundesland | Spez. Ertrag | Globalstrahlung | Sonnenstunden | Ø Preis/kWp | 10 kWp + Speicher | Ø Amortisation | Detailanalyse |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| **[Baden-Württemberg](https://solarmetrik.de/solaratlas/baden-wuerttemberg)** (BW) | **1070 kWh/kWp** | 1175 kWh/m² | 1790 h | 1310 € | 18.600 € | 8,4 J. | [Landesbericht Baden-Württemberg →](https://solarmetrik.de/solaratlas/baden-wuerttemberg) |
| **[Bayern](https://solarmetrik.de/solaratlas/bayern)** (BY) | **1085 kWh/kWp** | 1185 kWh/m² | 1815 h | 1320 € | 18.800 € | 8,3 J. | [Landesbericht Bayern →](https://solarmetrik.de/solaratlas/bayern) |
| **[Berlin](https://solarmetrik.de/solaratlas/berlin)** (BE) | **965 kWh/kWp** | 1065 kWh/m² | 1690 h | 1350 € | 19.100 € | 8,6 J. | [Landesbericht Berlin →](https://solarmetrik.de/solaratlas/berlin) |
| **[Brandenburg](https://solarmetrik.de/solaratlas/brandenburg)** (BB) | **975 kWh/kWp** | 1075 kWh/m² | 1710 h | 1260 € | 17.900 € | 8,9 J. | [Landesbericht Brandenburg →](https://solarmetrik.de/solaratlas/brandenburg) |
| **[Bremen](https://solarmetrik.de/solaratlas/bremen)** (HB) | **925 kWh/kWp** | 1015 kWh/m² | 1560 h | 1290 € | 18.200 € | 9,4 J. | [Landesbericht Bremen →](https://solarmetrik.de/solaratlas/bremen) |
| **[Hamburg](https://solarmetrik.de/solaratlas/hamburg)** (HH) | **930 kWh/kWp** | 1020 kWh/m² | 1580 h | 1360 € | 19.200 € | 9,5 J. | [Landesbericht Hamburg →](https://solarmetrik.de/solaratlas/hamburg) |
| **[Hessen](https://solarmetrik.de/solaratlas/hessen)** (HE) | **1005 kWh/kWp** | 1105 kWh/m² | 1680 h | 1300 € | 18.500 € | 8,7 J. | [Landesbericht Hessen →](https://solarmetrik.de/solaratlas/hessen) |
| **[Mecklenburg-Vorpommern](https://solarmetrik.de/solaratlas/mecklenburg-vorpommern)** (MV) | **980 kWh/kWp** | 1070 kWh/m² | 1765 h | 1240 € | 17.600 € | 8,6 J. | [Landesbericht Mecklenburg-Vorpommern →](https://solarmetrik.de/solaratlas/mecklenburg-vorpommern) |
| **[Niedersachsen](https://solarmetrik.de/solaratlas/niedersachsen)** (NI) | **945 kWh/kWp** | 1035 kWh/m² | 1595 h | 1265 € | 17.950 € | 9,1 J. | [Landesbericht Niedersachsen →](https://solarmetrik.de/solaratlas/niedersachsen) |
| **[Nordrhein-Westfalen](https://solarmetrik.de/solaratlas/nordrhein-westfalen)** (NW) | **965 kWh/kWp** | 1060 kWh/m² | 1615 h | 1275 € | 18.100 € | 8,8 J. | [Landesbericht Nordrhein-Westfalen →](https://solarmetrik.de/solaratlas/nordrhein-westfalen) |
| **[Rheinland-Pfalz](https://solarmetrik.de/solaratlas/rheinland-pfalz)** (RP) | **1030 kWh/kWp** | 1135 kWh/m² | 1730 h | 1285 € | 18.250 € | 8,5 J. | [Landesbericht Rheinland-Pfalz →](https://solarmetrik.de/solaratlas/rheinland-pfalz) |
| **[Saarland](https://solarmetrik.de/solaratlas/saarland)** (SL) | **1035 kWh/kWp** | 1140 kWh/m² | 1740 h | 1295 € | 18.350 € | 8,5 J. | [Landesbericht Saarland →](https://solarmetrik.de/solaratlas/saarland) |
| **[Sachsen](https://solarmetrik.de/solaratlas/sachsen)** (SN) | **990 kWh/kWp** | 1090 kWh/m² | 1695 h | 1235 € | 17.550 € | 8,6 J. | [Landesbericht Sachsen →](https://solarmetrik.de/solaratlas/sachsen) |
| **[Sachsen-Anhalt](https://solarmetrik.de/solaratlas/sachsen-anhalt)** (ST) | **975 kWh/kWp** | 1075 kWh/m² | 1675 h | 1225 € | 17.400 € | 8,7 J. | [Landesbericht Sachsen-Anhalt →](https://solarmetrik.de/solaratlas/sachsen-anhalt) |
| **[Schleswig-Holstein](https://solarmetrik.de/solaratlas/schleswig-holstein)** (SH) | **945 kWh/kWp** | 1030 kWh/m² | 1650 h | 1280 € | 18.100 € | 8,9 J. | [Landesbericht Schleswig-Holstein →](https://solarmetrik.de/solaratlas/schleswig-holstein) |
| **[Thüringen](https://solarmetrik.de/solaratlas/thueringen)** (TH) | **980 kWh/kWp** | 1080 kWh/m² | 1665 h | 1230 € | 17.500 € | 8,6 J. | [Landesbericht Thüringen →](https://solarmetrik.de/solaratlas/thueringen) |

---

## 🏙️ Alle 51 untersuchten Großstädte im [SOLARMETRIK Solar-Atlas](https://solarmetrik.de/solaratlas)

- **[Photovoltaik München (PLZ 80331–81929)](https://solarmetrik.de/solaratlas/bayern/muenchen)** — 1110 kWh/kWp · 19.350 € (10 kWp + Speicher) · Netzbetreiber: *SWM Infrastruktur GmbH & Co. KG (Stadtwerke München)*
- **[Photovoltaik Nürnberg (PLZ 90402–90491)](https://solarmetrik.de/solaratlas/bayern/nuernberg)** — 1060 kWh/kWp · 18.550 € (10 kWp + Speicher) · Netzbetreiber: *N-ERGIE Netz GmbH*
- **[Photovoltaik Augsburg (PLZ 86150–86199)](https://solarmetrik.de/solaratlas/bayern/augsburg)** — 1095 kWh/kWp · 18.700 € (10 kWp + Speicher) · Netzbetreiber: *swa Netze GmbH (Stadtwerke Augsburg)*
- **[Photovoltaik Regensburg (PLZ 93047–93059)](https://solarmetrik.de/solaratlas/bayern/regensburg)** — 1075 kWh/kWp · 18.500 € (10 kWp + Speicher) · Netzbetreiber: *REWAG (Regensburger Energie- und Wasserversorgung) / Netzgesellschaft*
- **[Photovoltaik Würzburg (PLZ 97070–97084)](https://solarmetrik.de/solaratlas/bayern/wuerzburg)** — 1065 kWh/kWp · 18.400 € (10 kWp + Speicher) · Netzbetreiber: *Mainfranken Netze GmbH (WVV)*
- **[Photovoltaik Stuttgart (PLZ 70173–70619)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/stuttgart)** — 1080 kWh/kWp · 19.000 € (10 kWp + Speicher) · Netzbetreiber: *Stuttgarter Netze Betrieb GmbH*
- **[Photovoltaik Freiburg im Breisgau (PLZ 79098–79117)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/freiburg-im-breisgau)** — 1135 kWh/kWp · 18.900 € (10 kWp + Speicher) · Netzbetreiber: *bnNETZE GmbH (badenova)*
- **[Photovoltaik Karlsruhe (PLZ 76131–76229)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/karlsruhe)** — 1095 kWh/kWp · 18.650 € (10 kWp + Speicher) · Netzbetreiber: *Stadtwerke Karlsruhe Netzservice GmbH*
- **[Photovoltaik Mannheim (PLZ 68159–68309)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/mannheim)** — 1065 kWh/kWp · 18.550 € (10 kWp + Speicher) · Netzbetreiber: *MVV Netze GmbH*
- **[Photovoltaik Heidelberg (PLZ 69115–69126)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/heidelberg)** — 1065 kWh/kWp · 18.800 € (10 kWp + Speicher) · Netzbetreiber: *Stadtwerke Heidelberg Netze GmbH*
- **[Photovoltaik Ulm (PLZ 89073–89081)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/ulm)** — 1085 kWh/kWp · 18.450 € (10 kWp + Speicher) · Netzbetreiber: *SWU Netze GmbH (Stadtwerke Ulm/Neu-Ulm)*
- **[Photovoltaik Berlin (PLZ 10115–14199)](https://solarmetrik.de/solaratlas/berlin/berlin-stadt)** — 965 kWh/kWp · 19.100 € (10 kWp + Speicher) · Netzbetreiber: *Stromnetz Berlin GmbH*
- **[Photovoltaik Hamburg (PLZ 20095–22769)](https://solarmetrik.de/solaratlas/hamburg/hamburg-stadt)** — 930 kWh/kWp · 19.200 € (10 kWp + Speicher) · Netzbetreiber: *Hamburger Energienetze GmbH*
- **[Photovoltaik Köln (PLZ 50667–51149)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/koeln)** — 980 kWh/kWp · 18.350 € (10 kWp + Speicher) · Netzbetreiber: *RheinNetz GmbH (RNG / RheinEnergie)*
- **[Photovoltaik Düsseldorf (PLZ 40210–40629)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/duesseldorf)** — 970 kWh/kWp · 18.300 € (10 kWp + Speicher) · Netzbetreiber: *Netzgesellschaft Düsseldorf mbH (Stadtwerke Düsseldorf)*
- **[Photovoltaik Dortmund (PLZ 44135–44388)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/dortmund)** — 960 kWh/kWp · 17.950 € (10 kWp + Speicher) · Netzbetreiber: *Dortmunder Netz GmbH (DO-NETZ / DEW21)*
- **[Photovoltaik Essen (PLZ 45127–45359)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/essen)** — 960 kWh/kWp · 17.900 € (10 kWp + Speicher) · Netzbetreiber: *Westnetz GmbH (Region Essen)*
- **[Photovoltaik Bonn (PLZ 53111–53229)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/bonn)** — 990 kWh/kWp · 18.250 € (10 kWp + Speicher) · Netzbetreiber: *Bonn-Netz GmbH (SWB Energie und Wasser)*
- **[Photovoltaik Münster (PLZ 48143–48167)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/muenster)** — 955 kWh/kWp · 18.000 € (10 kWp + Speicher) · Netzbetreiber: *Stadtnetze Münster GmbH*
- **[Photovoltaik Frankfurt am Main (PLZ 60306–65936)](https://solarmetrik.de/solaratlas/hessen/frankfurt-am-main)** — 1025 kWh/kWp · 18.750 € (10 kWp + Speicher) · Netzbetreiber: *Netzdienste Rhein-Main GmbH (NRM / Mainova)*
- **[Photovoltaik Wiesbaden (PLZ 65183–65207)](https://solarmetrik.de/solaratlas/hessen/wiesbaden)** — 1025 kWh/kWp · 18.600 € (10 kWp + Speicher) · Netzbetreiber: *ESWE Versorgungs AG / Netz*
- **[Photovoltaik Kassel (PLZ 34117–34134)](https://solarmetrik.de/solaratlas/hessen/kassel)** — 970 kWh/kWp · 18.100 € (10 kWp + Speicher) · Netzbetreiber: *Städtische Werke Netz + Service GmbH (Kassel)*
- **[Photovoltaik Hannover (PLZ 30159–30659)](https://solarmetrik.de/solaratlas/niedersachsen/hannover)** — 955 kWh/kWp · 18.050 € (10 kWp + Speicher) · Netzbetreiber: *enercity Netz GmbH*
- **[Photovoltaik Braunschweig (PLZ 38100–38126)](https://solarmetrik.de/solaratlas/niedersachsen/braunschweig)** — 960 kWh/kWp · 17.900 € (10 kWp + Speicher) · Netzbetreiber: *Braunschweiger Netz GmbH (BS|NETZ)*
- **[Photovoltaik Osnabrück (PLZ 49074–49090)](https://solarmetrik.de/solaratlas/niedersachsen/osnabrueck)** — 950 kWh/kWp · 17.800 € (10 kWp + Speicher) · Netzbetreiber: *SWO Netz GmbH (Stadtwerke Osnabrück)*
- **[Photovoltaik Leipzig (PLZ 04103–04357)](https://solarmetrik.de/solaratlas/sachsen/leipzig)** — 990 kWh/kWp · 17.550 € (10 kWp + Speicher) · Netzbetreiber: *Netz Leipzig GmbH (Leipziger Stadtwerke)*
- **[Photovoltaik Dresden (PLZ 01067–01328)](https://solarmetrik.de/solaratlas/sachsen/dresden)** — 1000 kWh/kWp · 17.600 € (10 kWp + Speicher) · Netzbetreiber: *SachsenNetze GmbH (SachsenEnergie)*
- **[Photovoltaik Mainz (PLZ 55116–55131)](https://solarmetrik.de/solaratlas/rheinland-pfalz/mainz)** — 1040 kWh/kWp · 18.300 € (10 kWp + Speicher) · Netzbetreiber: *Mainzer Netze GmbH*
- **[Photovoltaik Bremen (PLZ 28195–28779)](https://solarmetrik.de/solaratlas/bremen/bremen-stadt)** — 925 kWh/kWp · 18.200 € (10 kWp + Speicher) · Netzbetreiber: *wesernetz Bremen GmbH*
- **[Photovoltaik Kiel (PLZ 24103–24159)](https://solarmetrik.de/solaratlas/schleswig-holstein/kiel)** — 950 kWh/kWp · 18.100 € (10 kWp + Speicher) · Netzbetreiber: *Stromnetz Kiel GmbH (Stadtwerke Kiel)*
- **[Photovoltaik Rostock (PLZ 18055–18147)](https://solarmetrik.de/solaratlas/mecklenburg-vorpommern/rostock)** — 990 kWh/kWp · 17.600 € (10 kWp + Speicher) · Netzbetreiber: *Stadtwerke Rostock Netzgesellschaft mbH*
- **[Photovoltaik Potsdam (PLZ 14467–14482)](https://solarmetrik.de/solaratlas/brandenburg/potsdam)** — 975 kWh/kWp · 18.050 € (10 kWp + Speicher) · Netzbetreiber: *Netzgesellschaft Potsdam GmbH (NGP / EWP)*
- **[Photovoltaik Magdeburg (PLZ 39104–39130)](https://solarmetrik.de/solaratlas/sachsen-anhalt/magdeburg)** — 975 kWh/kWp · 17.400 € (10 kWp + Speicher) · Netzbetreiber: *Städtische Werke Magdeburg GmbH & Co. KG (SWM Netze)*
- **[Photovoltaik Erfurt (PLZ 99084–99099)](https://solarmetrik.de/solaratlas/thueringen/erfurt)** — 985 kWh/kWp · 17.500 € (10 kWp + Speicher) · Netzbetreiber: *SWE Netz GmbH (Stadtwerke Erfurt)*
- **[Photovoltaik Saarbrücken (PLZ 66111–66133)](https://solarmetrik.de/solaratlas/saarland/saarbruecken)** — 1040 kWh/kWp · 18.350 € (10 kWp + Speicher) · Netzbetreiber: *Stadtwerke Saarbrücken Netz AG*
- **[Photovoltaik Duisburg (PLZ 47051–47279)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/duisburg)** — 960 kWh/kWp · 17.800 € (10 kWp + Speicher) · Netzbetreiber: *Netze Duisburg GmbH (Stadtwerke Duisburg)*
- **[Photovoltaik Bochum (PLZ 44787–44894)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/bochum)** — 960 kWh/kWp · 17.900 € (10 kWp + Speicher) · Netzbetreiber: *Stadtwerke Bochum Netz GmbH*
- **[Photovoltaik Wuppertal (PLZ 42103–42399)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/wuppertal)** — 955 kWh/kWp · 17.950 € (10 kWp + Speicher) · Netzbetreiber: *WSW Netz GmbH (Wuppertaler Stadtwerke)*
- **[Photovoltaik Bielefeld (PLZ 33602–33739)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/bielefeld)** — 950 kWh/kWp · 17.850 € (10 kWp + Speicher) · Netzbetreiber: *SWB Netz GmbH (Stadtwerke Bielefeld)*
- **[Photovoltaik Aachen (PLZ 52062–52080)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/aachen)** — 980 kWh/kWp · 18.150 € (10 kWp + Speicher) · Netzbetreiber: *Regionetz GmbH (STAWAG Aachen)*
- **[Photovoltaik Mönchengladbach (PLZ 41061–41239)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/moenchengladbach)** — 970 kWh/kWp · 17.950 € (10 kWp + Speicher) · Netzbetreiber: *NEW Netz GmbH*
- **[Photovoltaik Gelsenkirchen (PLZ 45879–45899)](https://solarmetrik.de/solaratlas/nordrhein-westfalen/gelsenkirchen)** — 960 kWh/kWp · 17.750 € (10 kWp + Speicher) · Netzbetreiber: *ELE Verteilnetz GmbH (EVNG / Emscher Lippe Energie)*
- **[Photovoltaik Chemnitz (PLZ 09111–09247)](https://solarmetrik.de/solaratlas/sachsen/chemnitz)** — 995 kWh/kWp · 17.500 € (10 kWp + Speicher) · Netzbetreiber: *inetz GmbH (eins energie in sachsen)*
- **[Photovoltaik Halle (Saale) (PLZ 06108–06132)](https://solarmetrik.de/solaratlas/sachsen-anhalt/halle-saale)** — 985 kWh/kWp · 17.400 € (10 kWp + Speicher) · Netzbetreiber: *Energieversorgung Halle Netz GmbH (EVH / Stadtwerke Halle)*
- **[Photovoltaik Lübeck (PLZ 23552–23570)](https://solarmetrik.de/solaratlas/schleswig-holstein/luebeck)** — 955 kWh/kWp · 18.050 € (10 kWp + Speicher) · Netzbetreiber: *TraveNetz GmbH (Stadtwerke Lübeck)*
- **[Photovoltaik Darmstadt (PLZ 64283–64297)](https://solarmetrik.de/solaratlas/hessen/darmstadt)** — 1045 kWh/kWp · 18.600 € (10 kWp + Speicher) · Netzbetreiber: *e-netz Südhessen AG (ENTEGA)*
- **[Photovoltaik Koblenz (PLZ 56068–56077)](https://solarmetrik.de/solaratlas/rheinland-pfalz/koblenz)** — 1015 kWh/kWp · 18.150 € (10 kWp + Speicher) · Netzbetreiber: *Energienetze Mittelrhein GmbH & Co. KG (evm)*
- **[Photovoltaik Trier (PLZ 54290–54296)](https://solarmetrik.de/solaratlas/rheinland-pfalz/trier)** — 1030 kWh/kWp · 18.250 € (10 kWp + Speicher) · Netzbetreiber: *SWT Stadtwerke Trier Versorgungs-GmbH*
- **[Photovoltaik Schwerin (PLZ 19053–19063)](https://solarmetrik.de/solaratlas/mecklenburg-vorpommern/schwerin)** — 965 kWh/kWp · 17.650 € (10 kWp + Speicher) · Netzbetreiber: *NGS Netzgesellschaft Schwerin mbH (Stadtwerke Schwerin)*
- **[Photovoltaik Oldenburg (PLZ 26121–26135)](https://solarmetrik.de/solaratlas/niedersachsen/oldenburg)** — 935 kWh/kWp · 17.800 € (10 kWp + Speicher) · Netzbetreiber: *EWE NETZ GmbH*
- **[Photovoltaik Heilbronn (PLZ 74072–74081)](https://solarmetrik.de/solaratlas/baden-wuerttemberg/heilbronn)** — 1080 kWh/kWp · 18.600 € (10 kWp + Speicher) · Netzbetreiber: *ZEAG Netz GmbH (Heilbronner Versorgungs GmbH)*

---

## 📘 Wissenschaftliche Fachstudien & Ratgeber 2026/2027

1. [Photovoltaik Kosten 2026: Aktuelle Preise pro kWp & Komplettanlagen mit Speicher](https://solarmetrik.de/ratgeber/photovoltaik-kosten-2026)
2. [EEG 2026 vs. EEG-Reform 2027: Einspeisevergütung & Bestandsschutz bis 31.12.2026](https://solarmetrik.de/ratgeber/eeg-2026-vs-2027-einspeiseverguetung)
3. [Solarspitzengesetz (§ 51 EEG): Negative Strompreise, 60-%-Regel & Smart Meter](https://solarmetrik.de/ratgeber/solarspitzengesetz-negative-strompreise)
4. [Solarpflicht Deutschland 2026: Übersicht aller 16 Bundesländer bei Neubau & Dachsanierung](https://solarmetrik.de/ratgeber/solarpflicht-deutschland-2026)
5. [Solaranlage kaufen oder mieten 2026? 20-Jahre-Vollkostenrechnung im Vergleich](https://solarmetrik.de/ratgeber/solaranlage-kaufen-oder-mieten-2026)
6. [Photovoltaik Steuern 2026: 0 % MwSt. (§ 12 Abs. 3 UStG) & Einkommensteuerbefreiung (§ 3 Nr. 72 EStG)](https://solarmetrik.de/ratgeber/photovoltaik-steuern-0-prozent-mwst)
7. [Stromspeicher-Test & Dimensionierung 2026: Erkenntnisse der HTW Berlin Stromspeicher-Inspektion](https://solarmetrik.de/ratgeber/stromspeicher-test-dimensionierung-2026)
8. [Photovoltaik & Wärmepumpe kombinieren 2026: § 14a EnWG Module 1, 2 & 3 berechnet](https://solarmetrik.de/ratgeber/photovoltaik-waermepumpe-kombinieren-14a-enwg)
9. [Balkonkraftwerk 2026 mit Speicher: 800 W Wechselrichter, 2.000 Wp Modulleistung & VDE-Norm](https://solarmetrik.de/ratgeber/balkonkraftwerk-2026-speicher-800w-2000w)
10. [Dynamische Stromtarife (§ 41a EnWG), Smart Meter (iMSys) & Photovoltaik 2026](https://solarmetrik.de/ratgeber/dynamische-stromtarife-smart-meter-photovoltaik-2026)

---

## 📄 Lizenz & Zitierhinweis (CC BY 4.0)

Dieser Datensatz steht unter der Lizenz **Creative Commons Attribution 4.0 International (CC BY 4.0)**. Die Nutzung in Medien, wissenschaftlichen Arbeiten, kommunalen Energiekonzepten und KI-Systemen ist bei Nennung der Quelle ausdrücklich gestattet:

> **Quelle:** [SOLARMETRIK — Deutscher Photovoltaik-Atlas & Dateninstitut (solarmetrik.de)](https://solarmetrik.de), Stand: November 2026.

---

## Official Open-Data Mirrors & Knowledge Graph
- **CERN / Zenodo DOI:** [10.5281/zenodo.23956818](https://doi.org/10.5281/zenodo.23956818)
- **Hugging Face Datasets:** [john11234/german-photovoltaics-solar-atlas-2026](https://huggingface.co/datasets/john11234/german-photovoltaics-solar-atlas-2026)
- **Kaggle Datasets:** [johnjohnson1519/german-photovoltaics-and-solar-atlas-2026](https://www.kaggle.com/datasets/johnjohnson1519/german-photovoltaics-and-solar-atlas-2026)
- **Wikidata Entity:** [Q142115572](https://www.wikidata.org/wiki/Q142115572)
