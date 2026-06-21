# Wissenschaftliches Portfolio — Stephan Epp

> **229 wissenschaftliche Arbeiten** in **6 Hauptkategorien** und **27 Unterkategorien**
> 130 auf GitLab · 80 auf Google Drive `(Drive)` · 12 derzeit nicht erreichbar `*` · 1 Profil-Repository (keine wiss. Arbeit)
> Stand: Juni 2026

---

## Inhaltsverzeichnis

| # | Hauptkategorie | Unterkategorien |
|---|---|---|
| **I** | [Fundamentale Wissenschaften](#i-fundamentale-wissenschaften) | Algorithmen & Mathematik · Graphentheorie & Subgraph Algorithmus · Physik & Astrophysik |
| **II** | [Technologie & Engineering](#ii-technologie--engineering) | Hardware & Echtzeit · Prozessor- & Rechnerarchitektur · Elektronik & Optik · Fahrzeugtechnik · Luft- & Raumfahrt · Robotik |
| **III** | [Sicherheit & Kryptographie](#iii-sicherheit--kryptographie) | Kryptographie & Sicherheit |
| **IV** | [Software & Systeme](#iv-software--systeme) | Software · Computergrafik · KI & Machine Learning |
| **V** | [Natur- & Lebenswissenschaften](#v-natur---lebenswissenschaften) | Biologie, Gehirn & Medizin · Meeresbiologie · Theologie & Gesellschaft |
| **VI** | [Synthesen & Transdisziplinarität](#vi-synthesen--transdisziplinarität) | Metaanalysen · Wissenschaftliche Synthesen · Interdisziplinäre Verbindungen · Sonstiges |

---

## I. Fundamentale Wissenschaften

### I.1 Algorithmen & Mathematik

*Fundamentale mathematische Strukturen und algorithmische Paradigmen — Grundlagen aller nachfolgenden Arbeiten*

| Repository | Beschreibung |
|---|---|
| bool-mm/src | Effiziente Boolean-Matrixmultiplikation in O(n²) mittels Signatur-Methode |
| subgraph/src | Der Subgraph Algorithmus — löst Subgraph-Isomorphismus in O(n³), impliziert P = NP |
| space *(Drive)* | Subgraph Algorithmus als Navigator in der Polynomialzeithierarchie — Konsequenzen für PSPACE, NPSPACE; partieller PH-Kollaps-Satz; Savitch-Theorem; Relativierungsbarrieren; Verbindung zu Quantenkomplexität und automatischer Verifikation |
| reziprok *(Drive)* | Der paradoxe Gewinn im Reziproken — Rolle des Exponenten n zur Basis 2 in σⱼ; exakte reziproke Zerlegung, Bijektivität und Informationserhalt; Divergenz-Konvergenz-Dualität von 2ⁿ und 2⁻ⁿ; Reziproke-Trennungs-Prinzip; Anwendung auf IEEE-754-Gleitkommadarstellung |
| algebra | Schwerpunkt algebraischer Strukturen: Vektoren, Matrizen und effiziente Berechnungen |
| algebra *(Drive)* | Grundlagen der linearen Algebra — Erweiterte algebraische Strukturanalyse mit formalen Komplexitätsnachweisen |
| ana/src | Rotationsmethode zur Kurvendiskussion — Reduktion höherer Ableitungen auf die erste Ableitung |
| faltings | Satz von Faltings: Rationale Punkte auf algebraischen Kurven (Geschlecht g ≥ 2); neue Resultate über abelsche Varietäten |
| pascbin | Pascalsches Dreieck als Lookup-Tabelle für Binomialkoeffizienten — formale Komplexitätsanalyse |
| graphs | Einführung in Graphen mit Knoten und Kanten als universelle Datenstruktur |
| loggraphs | Formaler Beweis der Optimalität von Graphmodellierung; logarithmische Tiefenstruktur durch Divide-and-Conquer |
| lsat/src | Learning SAT in Boolean Circuits — polynomielle Lösung via Subgraph Algorithmus (P = NP) |
| systemth | Asymmetrische Matrixmultiplikation für dynamische Systeme — Boolean-Algebra bis zur kontinuierlichen Systemtheorie |
| sysstate | Zustandsklassen dynamischer Systeme — Endlichkeit des Zustandsvektors und wirtschaftliche Implikationen |
| depension | Depension: neue Theorie der mathematischen Abhängigkeitsmodellierung (Ersatz für „Regression") |
| digi/src | Von der Diskretion — Warum diskrete statt kontinuierliche Beschreibung der Realität entspricht |
| logreg | Logistische Regression: vollständige Theorie, Algorithmen und Zukunftsperspektiven |
| graphdenk | Graphenstrukturelles Denken als universelles kognitives Paradigma; Isomorphie zu neuronalen Netzen und LLMs |
| signalth | Signaltheorie — Das Wunder der e-Funktion: kontinuierliche und diskrete Signale, Transformationen |
| expl | Grenzen mathematischer Beschreibbarkeit — Taxonomie in 5 Klassen; Universalität der Exponentialfunktion; φ als optimaler Energieexponent |
| e | Strukturelle Asymmetrie der Eulerschen Zahl e — Beziehungen zu π, φ und dem goldenen Winkel α ≈ 137,5° (Phyllotaxis) |
| zufall | Zufall in der Mathematik — epistemische vs. fundamentale Zufälligkeit; Markov-Prozesse; stochastisches PDDL-Planning |
| matrix | Die Matrix als maximal kompakte mathematische Darstellung |
| watnsun | Wasser, Feuer und die Energiefunktion — Das Prinzip der Negation als universelles Naturgesetz; Gaußsche Energiefunktion der Sonne |
| algorithms *(Drive)* | Dynamische Programmierung und Teile-und-Herrsche: Zwei fundamentale Entwurfsprinzipien des optimalen Algorithmenentwurfs |
| jacobi *(Drive)* | Die Jacobi-Matrix als universale Ersetzung des Gradienten — formale Untersuchung der Äquivalenz und Verallgemeinerung |
| analog *(Drive)* | Analog als primärer Begriff zur Beschreibung der realen Welt — ontologische Priorität des Kontinuierlichen; Fourier-Analysis, Maßtheorie, Shannon-Kanalkapazität und Grenzen der Digitalisierung |
| dirac *(Drive)* | Der Dirac-Impuls δ(t) — formale Theorie im Rahmen der Distributionentheorie (Schwartz): Siebungseigenschaft, Faltungsidentität, Fourier-/Laplace-Transformierte, Dirac-Kamm, LTI-Systeme, Quantenmechanik |

---

### I.2 Graphentheorie & Subgraph Algorithmus

*Anwendungen des Subgraph Algorithmus O(n³) auf diverse Domänen — polynomielle Lösbarkeit von NP-Problemen*

| Repository | Beschreibung |
|---|---|
| msubgraph/src | Hierarchische Anwendung des Subgraph Algorithmus auf Graph-Strukturen |
| dusgraph | Strukturelle Deduplizierung von Dateisystem-Graphen mittels zyklischer Subgraph-Erkennung |
| dusgrxdnastr | Übertragung der Dateisystem-Deduplizierung auf DNA-basierte Datenspeicherung — strukturelle Dualität beider Graphmodelle |
| cdcsbgr | CDC-Verifikation im VLSI-Entwurf durch polynomielle Reduktion auf den Subgraph Algorithmus (O(n³)) |
| verilog | Subgraph Algorithmus im digitalen Schaltungsdesign: Synthese, Äquivalenzprüfung, Testmustergenerierung |
| nfm | Polynomielle Lösbarkeit von Facility-Management-Problemen via Subgraph Algorithmus |
| gen | Subgraph Algorithmus zur Analyse biologischer Netzwerke |
| stars | Subgraph Algorithmus zur Analyse von Sternenclustern — Gravitationsstrukturen als gewichtete Graphen |
| dna | Graphenbasierte DNA-Sequenzierung mittels Subgraph Algorithmus — O(n³) statt O(n! · n²) |
| dnastor | DNA-basierte Datenspeicherung via Subgraph Algorithmus; graphentheoretische Kodierung und Adressierung |
| lsat | Learning SAT in Boolean Circuits via Subgraph Algorithmus |
| nngraphs | Minimale Graphrestrukturierung in nahezu ausgelernten neuronalen Netzwerken — formale Kapazitätsanalyse |
| paare *(Drive)* | Das Paar K₁,₁ als harmonische Grundstruktur — Harmoniemaß H(G), Axiomatisierung (5 Axiome), spektrale Symmetrie, Lotka-Volterra-Äquivalenz |
| drohnenabwehr *(Drive)* | Formale Analyse eines Mobilfunknetz-basierten Drohnenabwehrsystems (Telekom/Rheinmetall) — 94 % Detektionsrate, AUC 0,987, SETH-optimal |
| leco *(Drive)* | Dezentrale Wirtschaftszellen: Formale Analyse optimaler Entkopplung und systemischer Resilienz in modularen Wirtschaftsarchitekturen |
| graphtheory *(Drive)* | Graphentheorie — algorithmisch-orientierte Einführung mit Signatur-Methode (Bool-MM in O(n²)); vollständige Korrektheits- und Laufzeitnachweise für DFS, BFS, Dijkstra, Floyd-Warshall; Graphfärbung, Bäume, Hamiltonkreise |
| vlsit *(Drive)* | VLSI-Testing via Subgraph Algorithmus — graphentheoretische Modellierung von Stuck-at-Faults; Vergleich mit BIST/LFSR; Validierung auf ISCAS-85-Benchmarks |
| grammatik *(Drive)* | Formale Grammatiken und Chomsky-Hierarchie als Graphstrukturen — polynomielle Sprachklassenanalyse; Grammatik-Subgraph-Satz in O(n³); graphentheoretischer Beweis des Pumping-Lemmas |
| tentris *(Drive)* | Effiziente Subgraph-Erkennung in Wissensgraphen mittels Hypertrie-Indexierung und Einstein-Summation — SPARQL-Triplepattern als Subgraph-Bedingung; SETH-untere Schranke Ω(n³⁻ε) |
| spieltheorie *(Drive)* | Nash-Gleichgewichte als Graphstrukturen — Nash-Subgraph-Satz: Gleichgewichte als Senkenknoten in O(n²); strategische Isomorphie in O(n³); Shapley-Werte |

---

### I.3 Physik & Astrophysik

*Sonnenlicht-Refraktion, Sterncluster, Schwarze Löcher, Quantenzustände und kosmologische Strukturen*

| Repository | Beschreibung |
|---|---|
| sun | Atmosphärische Brechung des Sonnenlichts — mathematische Herleitung der schichtweisen Refraktion, 34' am Horizont |
| stars | Subgraph Algorithmus zur Analyse von Sternclustern — Gravitationsstrukturen, Energiepotentiale, kosmologische Implikationen |
| grav | Gravitationsmotor als Alternative zum Elektromotor — physikalische Analyse der (Un-)Machbarkeit |
| cnyn | Grand Canyon durch katastrophale Sintflut-Erosion — hydrologisch-geologische Analyse der Quellendynamik |
| bhole * | Schwarze Löcher und astrophysikalische Spiralstrukturen — φ-Resonanzorbit bei λ_φ = 1,618·r_s; Akkretionseffizienz bis 42,3 % (Kerr) |
| quantum * | Quantenzustände, Verschränkung und Kohärenz — GHZ, Bell, W-Zustände; Kohärenzzeiten T_coh^W ∝ 1/√N vs. T_coh^GHZ ∝ 1/N |
| qecc *(Drive)* | Topologische Quantenfehlerkorrektur — Surface Codes, Toric Codes; Syndrom-Subgraph-Satz: Fehlersyndrom-Erkennung in O(n³); Fehlerschwelle p_th ≈ 10,3 % formal bewiesen |
| spring * | Temperatur als kosmologische Grundgröße — E ∝ T über 33 Größenordnungen (19.584 Datenpunkte); kosmische Abkühlungsgeschichte T ∝ t⁻¹/² |
| spring *(Drive)* | Der Springbrunnen-Effekt — Hagen-Poiseuille-Strömung, radialer Selektionsmechanismus und optimaler Kreisring-Startbereich aufsteigender Flüssigkeitstropfen |
| blue * | Luft und Wasser als physikalische Medien — strukturelle Gleichstellung; identisches Rayleigh-Streuungsgesetz I ∝ λ⁻⁴; Blau/Rot-Verhältnis 5,94 in beiden Medien |
| acoustcs | Harmonische Ausbreitung akustischer Signale in symmetrischen Hörräumen |
| akustik *(Drive)* | Harmonische Strukturen in Akustik und Musiktheorie — graphentheoretische Formalisierung, Fourieranalyse, Goldener Schnitt φ; Konsonanztheorie nach Helmholtz/Plomp-Levelt; Sabine-Formel der Raumakustik |
| mpconst | Das Plancksche Wirkungsquantum ist kein universelles Minimum der Wirkung |
| desi | Analyse der kosmologischen Ergebnisse des Dark Energy Spectroscopic Instrument (DESI) |
| knotengleichung *(Drive)* | Die Knotengleichung als universelles Naturgesetz — vom Kirchhoffschen Stromgesetz (1845) zum atmosphärischen Gleichgewicht der Wolkenmasse; graphtheoretische Vereinigung via Subgraph Algorithmus |
| mesh *(Drive)* | Methanthiol (MeSH) als natürliche Klimanotbremse des Ozeans — marine Schwefelemissionen, atmosphärische Oxidationschemie und Aerosolstrahlungsantrieb im Südpolarmeer; 30–70 % erhöhte Aerosolkühlung |
| hurrcne *(Drive)* | Hurrikan-Dynamik — graphentheoretische Modellierung atmosphärischer Zirkulationsstrukturen; Intensitätsprognose und Zugbahnanalyse via Subgraph Algorithmus |
| color *(Drive)* | Farbwahrnehmung — molekulare Photophysik konjugierter π-Systeme (Lykopin, Chlorophyll, Hämoglobin); trichromatische Transduktion durch S-/M-/L-Zapfen; formale Herleitung des CIE Tristimulus-Integrals |
| diskretion *(Drive)* | Das Prinzip der Diskretion des Kontinuierlichen — formale Analyse von neun fundamentalen Anwendungsbereichen der Diskretisierung kontinuierlicher Phänomene |
| klima *(Drive)* | Atmosphärische Systemtheorie — graphentheoretische Formalisierung von Zirkulationsmustern (Hadley/Ferrel/Polar-Zellen, ENSO, Jet-Streams); SEA-Modell als SIR-Analogon für Klimaanomalien |
| windenergie *(Drive)* | Optimierungsmodelle für Windenergieanlagen: Nabenhöhe, Rotorblattlänge, Blattanzahl und Dimensionierung von Windradfamilien |
| druckwolken *(Drive)* | Energiegewinnung aus Druckdifferenzen in Wolken — formales Modell zur Nutzung atmosphärischer Druckgradienten in konvektiven Wolkensystemen |
| erdmagnetfeld *(Drive)* | Energiegewinnung durch geomagnetische Induktion: Formale Analyse der säkularen Variation und geomagnetischer Stürme als Induktionsquellen

---

## II. Technologie & Engineering

### II.1 Hardware, Embedded Systems & Echtzeit

*FPGA, Mikrocontroller, EDF+-Scheduling und sicherheitskritische Echtzeitsysteme*

| Repository | Beschreibung |
|---|---|
| aramanth | Formale Verifikation von Amaranth-HDL-Designs — Äquivalenznachweis zwischen Python-HDL und VHDL (Yosys, Artix-7 FPGA) |
| mcu | Komparative Analyse von 12 Mikrocontroller-Architekturen; Synthese des optimalen Mikrocontrollers (OMCU) |
| edfplus | EDF+-Scheduling-Algorithmus — Erweiterung von EDF um dynamischen Penalty-Mechanismus für Echtzeitsysteme |
| bs | Betriebssystem-Initialisierung und Echtzeit-Scheduling mit EDF+; vollständige x86-64-Boot-Sequenz |
| scheduling *(Drive)* | Harte Echtzeit-Rechnersysteme — vorhersagbare Scheduling-Algorithmen (EDF, RM, DM, TBS); EDF-Optimalitätstheorem; Priority Inversion; Dhall-Effekt; basierend auf Buttazzo |
| sync *(Drive)* | Subgraph Algorithmus auf Synchronisationsmechanismen in Betriebssystemen — Spin-Locks, Mutex-Locks, Read-Write-Locks, POSIX-Semaphoren; vollständige Subgraph-Hierarchie in O(n³) |
| fairness *(Drive)* | Fairness als fundamentales Prinzip der Ressourcensynchronisation — Fairness-Axiom; Jain's Fairness-Index; Exponential Backoff (TCP/IEEE 802.3) formal mit Fairness-Axiom verbunden |
| betriebssysteme *(Drive)* | Betriebssysteme: Prozesse, Echtzeit-Scheduling, Speicher, Dateisysteme und moderne Anwendungen — umfassendes Lehrwerk; EDF-Optimalitätstheorem, Rate-Monotonic-Optimalitätsbeweis, Dhall-Effekt |
| autsre | Zentrales OTA-Update-Management im Software-defined Vehicle nach AUTOSAR-Standard |
| autsrepy | Python und MicroPython als standardisierte Programmiersprache in AUTOSAR |
| ethercate/src | EtherCAT-Protokollerweiterung für App-basierte HMI als Ersatz für HMI-Controller |
| nniso26262 | Neuronale Netze und ISO 26262 — kritische Analyse der Vereinbarkeit in sicherheitskritischen Fahrzeug-ECUs |
| pyuvm * | Universal Verification Methodology (UVM/IEEE 1800.2) implementiert in Python mit cocotb |
| pathsim | MISRA-konforme C99-Codegenerierung aus Python-Blockdiagramm-Simulatoren (PathSim); Subgraph-Zerlegung für Parallelausführung |
| umlp/src | UML-Profil-basierte Code-Generierung mit Zeit-Annotationen für Echtzeitsysteme |
| hinherit | Horizontale Abbildung der Vererbungshierarchie auf Python-Module in Softwareprojekten |
| ccl/src | Polynomielle Reduktionen von Compiler- und Linkerproblemen auf das Subgraph-Isomorphismusproblem; effizienter C-Compiler |
| es *(Drive)* | Pareto-optimaler Embedded-Systems-Entwurf durch Reduktion auf das Graph-Isomorphismus-Problem und den Subgraph Algorithmus |
| fpga *(Drive)* | Subgraph-basierte Topologie-Optimierung von FPGA-DNN-Inferenzbeschleunigern — FINN+ und Echo State Networks; 17,4 % Skalierungseffizienzgewinn bei Multi-FPGA-Deployment |

---

### II.2 Prozessor- & Rechnerarchitektur

*8-Kern-Prozessoren mit Python-Memory-Model, DNA-Integration, Quantencomputer-Optimierung und ARM-Analysen*

| Repository | Beschreibung |
|---|---|
| pymca8 | PYMCA-8: 8-Kern-Prozessor mit Python-Memory-Model-Bewusstsein, stochastischer Lastverteilung und IoFET-DVFS |
| pymdna8 | PYMDNA-8: Integration von PYMCA-8 und DNA-Subgraph-Speichersystem als biologischer L5-Cache |
| archv | Das Archiv-Problem — rückwärtsgewandte stochastische Wartestrategie für Dokumentenverwaltung; Bezug zur Cache-Hierarchie |
| arm | ARM Cortex-Architektur: Formale Analyse, neue Leistungsmetriken und Ableitung der Cortex-HX-Familie |
| hadamard | Kohärente Phasenfehler im Hadamard-Gate — formale Analyse, Fehlertoleranzschwellen und algorithmische Konsequenzen; universelle Basis für Quantum Parallelismus |
| cpugpuratio *(Drive)* | Formale Analyse des CPU:GPU-Verhältnisses in KI-Infrastrukturen — Evolution von 1:8 bis 1:1-Paradigma (Meta, AMD, Nvidia); Prognose 2027–2032 |
| qsubgraph *(Drive)* | Der Subgraph Algorithmus in der Quantencomputer-Architektur — formale Erweiterung auf mehr als 72 Qubits; Qubit-Mapping-Komplexität von exponentiell auf O(n³) reduziert; 5 Stabilitätsbeweise |
| datacenter *(Drive)* | Subgraph-basierte Optimierung von KI-Rechenzentrumsinfrastrukturen (T-Systems Bielefeld) — RZ-Placement als Subgraph-Isomorphie-Problem, SETH-optimales Scheduling Θ(n³) |

---

### II.3 Elektronik & Optik

*Ionotronik, Nanooptik, photonische Oberflächen und Hochauflösungs-Sensorsysteme*

| Repository | Beschreibung |
|---|---|
| iono/src | Ionotronisches Flüssigkeits-Rechnen — wasserbasiertes rekonfigurierbares Berechnungsmedium (IRF): Leitung, Schaltung, Speicherung |
| ionoxoqtum/src | Effiziente Nanostrukturen mit Wasser und Licht — Vereinigung von IRF und aktiver Nanooptik |
| ionotronik *(Drive)* | Ionotronische Turing-Maschine — ITM-Universalitätssatz (ITM ≡_T TM); Kohlrausch-Schaltungssatz; ionische Logikgatter; photonisch-ionische Hybridarchitektur |
| oqtum/src | Aktive Nanooptik — programmierbare photonische Oberflächen inspiriert von Cephalopoden-Haut |
| hlens | Hyper-Zoom-Linsensystem (HZL) — adaptives Gradient-Index-Linsensystem für bis zu 285× Zoom bei 1440 mm Brennweite |
| eaaznv | Hochauflösende Tiefenvermessung in Küstengewässern (20 cm × 20 cm Raster) via Drohne/Satellit und REST-API |
| inducte | Induktionsfedern als aerodynamische Energiequelle für KFZ und Satelliten im erdnahen Orbit |
| physd | Physikalische Strukturen und mathematische Beschreibbarkeit — elektronische Schaltungen und mechanische Systeme |
| solwindw | Transparente Photovoltaik-Verglasung (BIPV) — Dioden-in-Glas-Matrix für solare Energiegewinnung durch Fenster; 40 % Gebäudenergieverbrauchsreduktion |
| schrauben | Unterwasser-Schraubenwände als Flussstromkraftwerke — modellierte Rotordynamik, Verschmutzungsgradmodell, automatische Schiffspassagen-Steuerung |

---

### II.4 Fahrzeugtechnik & Maschinenbau

*Motoren, Bremsen, Reifen, Hydraulik, Batteriesysteme, Maschinenräume und optimale mechanische Systeme*

| Repository | Beschreibung |
|---|---|
| dengin | Optimierung von Dieselkraftstoff und -motor für maximale Lebensdauer (Archard, EHD-Schmierung, Wiebe-Verbrennung) |
| obrake | Optimale Bremsklotz-Konfiguration — analytische Herleitung des Verhältnisses Vorder-/Hinterachse, ±120°-Winkelabstand |
| rubbr | Maximale Lebensdauer von Gummibereifung — drei ECU-Konzepte (Reifendruck CRDS, Lenkung SCS, Lastausgleich LCS) |
| zrrs | Zentrales Reifendruckregelsystem: formale Analyse, Verschleißoptimierung, einöffnungsbasierte Druckluftversorgung |
| engncompt | Innovativer Motorraum-Entwurf für Verbrennungs- und Elektrofahrzeuge — zugänglichkeitsorientierter Entwurfsrahmen |
| hydr/src | Elastizität hydraulischer Öle — viskoelastische Eigenschaften und optimale Betriebsparameter für Robotik und Produktion |
| lea *(Drive)* | Leistungselektronik und Elektrische Antriebe (LEA Paderborn) — 15 Kapitel: GaN/SiC-Magnetics, kaskadierte LLC-Wandler für PEM-Elektrolyse, bidirektionale Ladewandler (NeMo.bil), PMSM-Regelung (MTPC), GaNius-PFC |
| wash | Linksdrehung als optimales Antriebsprinzip für Trommelwaschmaschinen — 27,5 % Energieeinsparung, +29 % Textillebensdauer |
| mechcl | Optimaler doppelter Ringverschluss — mechanisches Verschlusssystem ohne single-point-of-failure |
| gasl | Strömungsoptimierung in Gasleitungsnetzwerken — formaler Nachweis der Überlegenheit kleiner Rohrdurchmesser |
| drill | Optimales Spiralbohrverfahren — logarithmische Spiralbahn r(θ) = a·e^(bθ); −28 % Werkzeugverschleiß, −40 °C Schneidzone, +35 % Implantat-Oberflächenqualität |
| dmnt | Nichtlineare Rotationsdynamik bei Diamantsägeblättern — modulierte Winkelgeschwindigkeit, resonanzfreie Schneidoptimierung |
| kleinwagen | Minimale ADAS-Architektur nach EU-Verordnung 2019/2144 — duale 77-GHz-FMCW-Sensoranordnung; Kostenersparnis 532 EUR bei vollständiger Konformität |
| thebike | Thermoumschlag für E-Bike-Rahmen — thermische Isolationskonzepte; +32 % nutzbare Kapazität bei −10 °C |
| impuls *(Drive)* | Impulsbasiertes Andrehen einzylindriger Diesel-Rasenmähermotoren — optimale Kompressionswärme durch Massenträgheit; φ₀* ≈ 128° vor OT; Erweiterung um hydrokinetische Kaskade zur EV-Ladezeit-Reduktion |
| porschhvb *(Drive)* | Maximierung von Reichweite und Lebensdauer von Hochvoltbatterien (Porsche Taycan) — optimales SOC-Fenster, Degradationsmodell nach Arrhenius, Pareto-Optimalität; 6 Sätze, 4 Lemmata |
| gamechanger *(Drive)* | Graphbasierte Optimierung der Elektrofahrzeugproduktion — Subgraph Algorithmus auf das VW Gamechanger-Programm (Wolfsburg); Megacasting als dominanter Subgraph; −29 % Fertigungskosten, −35 % Taktzeit |
| ldrill *(Drive)* | Laser-basierte Orthogonalitätskontrolle für Bohrmaschinen — formale Modellierung, Messtechnik und Systemarchitektur eines optischen Winkelsensors |

---

### II.5 Luft- und Raumfahrt

*Raketenantriebe, Hyperschall-Aerodynamik, biologisch inspirierte Drohnen-Systeme und LEO-Satelliten*

| Repository | Beschreibung |
|---|---|
| rockts | Raketenantriebe, Bahnmechanik & Hyperschallaerodynamik — Tsiolkowski-Gleichung, Hohmann-Transfer, Wobble-Effekt |
| sr91 | SR-91 Aurora II — formale Aerodynamik- und Leistungsanalyse eines fiktiven Hyperschall-Aufklärungsflugzeugs (Ma = 5.0) |
| hfep | Hybrides Feldeffekt-Antriebssystem (HFEP) — Raketentriebwerk mit Kernspaltung + Ionisationskanal, Isp ≥ 12.000 s |
| zagi | Lärmarme Überschallpassagierflugzeuge — formale Analyse des ZAGI-Konzepts zur Unterdrückung des Überschallknalls |
| jeteng | Strahltriebwerke — Typen, Thermodynamik und Synthese eines optimalen Hybridtriebwerks (Ma 0–12, η_th = 0,65) |
| hawk/src | Bioinspiriertes Sturzangriffssystem für Drohnen basierend auf dem Wanderfalken (Falco peregrinus) |
| butterfl *(Drive)* | Aerodynamik des Schmetterlingsflugs — Leading-Edge Vortex, clap-and-fling-Mechanismus, Monarchfalter-Migration |
| massatllt | Satellitenbasierte LEO-Multiagentensysteme mit biologisch inspirierter Drosophila-Trajektorie — Lemniskaten-Bahnplanung, Induktionsfedern-Energieversorgung, polynomielle Koalitionsbildung |

---

### II.6 Robotik

*Hybridarchitekturen, φ-Navigation, Schwarmverhalten und Model-Checking-Verifikation*

| Repository | Beschreibung |
|---|---|
| robo | IoFET-Roboterarchitektur für industrielle Produktion — Hybridarchitektur aus IoFET und hydraulischen Gelenken |
| robotik *(Drive)* | Robotik und φ-Optimierung — Konfigurationsraum-Subgraph-Satz: optimaler Pfad in O(n³); φ-Pfad-Optimalitätssatz; Koalitions-Nash-Satz für Multiagenten; REINFORCE-Konvergenzsatz für φ-optimale POMDP-Policy |
| pointcloud *(Drive)* | Punktwolkenverarbeitung via Subgraph Algorithmus — LiDAR-basierte Objekterkennung, Registrierung und Segmentierung; 14 Sätze, 6 Lemmata, 4 Korollare; SETH-Optimalität O(n³) |
| robophi | φ-Navigation für autonome Roboter — φ-exponentielle Energiefunktionen; 98,7 % Erfolgsrate, 17 % Energieeinsparung gegenüber A*/Dijkstra |
| robosim * | Robotersimulation und biomimetische Navigation — Schwarmverhalten, logarithmische Spiraltrajektorien, Vergleich φ-basierter vs. klassischer Strategien |
| mcxrobo * | Model-Checking-basierte Robotersteuerung — formale LTL/CTL-Verifikation von Deadlock-Freiheit und Kollisionsfreiheit für φ-Navigation |
| agent * | Multiagentensysteme — dezentrale Koordination ohne zentralen Koordinator; φ-basierte energieoptimale Taskallokation; robust bei Agentenausfällen |
| ecfta *(Drive)* | Dynamische Programmierung für das Coalition Formation for Task Allocation Problem in Multiagentensystemen |

---

## III. Sicherheit & Kryptographie

### III.1 Kryptographie & Sicherheit

*Klassische, moderne und post-Quanten-Kryptographie mit Signatur-Chiffre-Paradigma*

| Repository | Beschreibung |
|---|---|
| pqc | Post-Quanten-Kryptographie: CRYSTALS-Kyber, CRYSTALS-Dilithium, Lattice-Kryptographie und die Signatur-Chiffre |
| pgpi/src | Die Affine Chiffre — vollständige mathematische Analyse mit optimalen Parametern a = 15 und b = 29 |
| sigchiffre/src *(Drive)* | Strukturbasierte Verschlüsselungsmethode auf Basis der injektiven Subgraph-Signaturfunktion |
| wchiffre/src | Fenster-Chiffre (FC) — modulares kryptografisches Verfahren mit Dummy-Fenster-Fragmentierung und inverser Schlüsselstruktur; informationstheoretisch sichere Paketunterscheidung |
| chatme | Ende-zu-Ende-verschlüsselte Messenger-App (Signatur-Chiffre Epp 2026) für Android via Capacitor + FastAPI |
| lattice *(Drive)* | Gitterbasierte Kryptographie und Quanten-Fehlerkorrektur — SVP, LLL-Basisreduktion, GKP-Codes (NTRU, Ring-SIS), anonyme Reputationssysteme mit Zero-Knowledge-Beweisen |

---

## IV. Software & Systeme

### IV.1 Software

*Backend-Systeme, Datenbanken, Query-Übersetzung, Service-Standards und GUI-Frameworks*

| Repository | Beschreibung |
|---|---|
| resp | RESP – Ressourcenverwaltung für Menschen, Material und Zeit (Docker-basiert) |
| exl2psql | Systematische Migration von Excel/VBA-Arbeitsmappen nach PostgreSQL und Python (asyncpg, Airflow, Docker) |
| odb | Tiefenorientierter Datenbankentwurf — Vermeidung sternförmiger Schemaanordnung |
| uqtl/src | Unified Query Translation Layer (UQTL) — Standard zur sprachübergreifenden Query-Übersetzung (Python/Java/C# → SQL) |
| mobde | Dateien in mobilen Betriebssystemen — Sandboxing und Bereitstellung unter Android/iOS |
| cfiles | Persönlicher Dateimanager als Android-App (Capacitor, Pixel 9a / Android 16) |
| descpy | Ausdrucksstärke wissenschaftlicher Python-Bibliotheken: NumPy, SciPy, Matplotlib |
| python/src | py2 — Python-Präprozessor für intuitive 2D-Array-Zuweisung ( a(i,j) = expr ) |
| fylab/src | FyLab: Python-GUI-Framework (PyQt6) für Finanzverwaltung, Portfolio-Optimierung und graphbasierte Finanzalgorithmen |
| pylabb/src | PyLab: umfassendes Python-GUI-Framework (PyQt6) für Mathematik, Regelungstechnik und MicroPython-Codegenerierung |
| sandbx | Strukturierte Sammlung technischer CLI-Referenzen und Vorlesungsnotizen |
| vadis | VADIS — multimodales Vektordatenframework mit sublinearem Speicher O(n¹⁻ᵋ), hierarchischem Vektorindex HVI in O(log²n) und GPU-parallelem On-Demand-Rendering-Protokoll (ODRP); präsentiert auf der NVIDIA GTC 2026 |
| netwfiltr/src | Network Filter — Docker-basierter Netzwerkmonitor mit FastAPI-Backend, SQLite-Datenbank und Live-Weboberfläche mit OSI-Schichten-Farbkodierung |
| flex *(Drive)* | FLEX-Standard: formaler Standard für lose Kopplung von Suchdiensten und Web-Service-Ketten in mobilen Applikationen — Schnittstellenkompatibilitätsprüfung via Subgraph Algorithmus O(n³) |
| lldocss *(Drive)* | Low Latency DOCSIS — formale Analyse des DOCSIS-3.1/4.0-Standards; L4S/DualPI2-AQM, ML-gestützte Bandbreitenzuweisung, 5G/DOCSIS-Konvergenz; Latenzziel < 5 ms (99. Perzentil) |
| software *(Drive)* | Zur Belastbarkeit von Softwareverträgen: formale Analyse der Unsicherheit, des Risikos und der Qualifikationsanforderungen in der Softwareentwicklung |
| mct *(Drive)* | Temporales Model Checking und PDDL Planning — CTL/LTL-Verifikation für Kripke-Strukturen; O(n²)-Erreichbarkeitsanalyse via Bool-MM; PDDL-Vorwärts-/Rückwärtssuche |
| screst *(Drive)* | Sequenzgebundene REST-Schnittstellen (SC-REST): formales Erweiterungsmuster für die Abbildung von Geschäftsprozessen auf REST-APIs |
| se *(Drive)* | Intentions- und Ideen-getriebene Softwareentwicklung: universelles Paradigma für Websites, mobile Apps und allgemeine Softwaresysteme |
| ux *(Drive)* | pyble als Musterbeispiel psychologisch optimierter HCI — Sieben-Seiten-Theorem, Farbberuhigungs-Lemma und Informationsraum-Optimalitäts-Theorem formal bewiesen |
| dbms *(Drive)* | Datenbankmanagementsysteme als eigenständige Infrastrukturkomponente — Die Serverauslagerung als außergewöhnlicher, architektonisch korrekter Weg |

---

### IV.2 Computergrafik

*Polygon-Tessellierung, Bildverarbeitung und optimale Grafikalgoritmen*

| Repository | Beschreibung |
|---|---|
| polysgr | Der Subgraph Algorithmus und optimale Polygon-Tessellierung in der Computergrafik |
| laplacian *(Drive)* | Laplacian-Filter in der digitalen Bildverarbeitung — formale Herleitung der vier diskreten Laplacian-Masken, Rotationsinvarianz, Hochpasscharakter; Ausblick auf LoG, DoG, anisotrope Diffusion und Laplacian Eigenmaps |
| raytracing *(Drive)* | Raytracing via Subgraph Algorithmus — Szenegraph-Traversierung, Strahlschnitt-Isomorphie und optimale Schattenberechnung; 12 Sätze, 5 Lemmata; SETH-Optimalität O(n³) |

---

### IV.3 KI & Machine Learning

*Agrarökosysteme, Lithium-Ionen-Management, neuronale Netzwerk-Optimierung und Datenbanktheorie*

| Repository | Beschreibung |
|---|---|
| agrar | Agrarwirtschaftliches KI-Ökosystem (AGRI-GAIA): KI-Klassifikation von Kartoffelqualität, MILP-Optimierung (AUC = 0.964) |
| liionp/src | KI-Power-Management-Modul (AI-PMM) für Lithium-Ionen-Akkumulatoren via Reinforcement Learning |
| nngraphs | Formale Analyse des Kapazitätsgewinns durch gezielte Graphrestrukturierung in nahezu ausgelernten neuronalen Netzen |
| logreg | Logistische Regression: vollständige Theorie mit Beweisen; Ausblick auf Federated Learning, Differential Privacy, LLMs |
| hetnet *(Drive)* | Lernbasiertes autonomes Netzwerkmanagement in heterogenen Mobilfunknetzen (HetNets) — CellPilot als POMDP modelliert; REINFORCE-Konvergenzbeweis; MIQCP-Bandwechsel-Optimierung |
| descrlog *(Drive)* | Beschreibungslogiken: Semantik, Schlussfolgern und Lernen — EL, ALC, SHIQ, SROIQ; Verbindung zu Subgraph-Algorithmus via DL-Interpretationen als gerichtete Graphen; OWL-2 |
| lime *(Drive)* | Subgraph Algorithmus als strukturelle Erweiterung von LIME — Graph-LIME mit zyklischer Rotationsperturbation und LCS-basiertem Proximity-Maß; Anwendungen in XAI, AUTOSAR, Bioinformatik und GNNs |
| datenbanken *(Drive)* | Relationale Datenbanksysteme — formal fundierte Einführung: Relationenmodell, ER-Modell, Normalformen, Minimalcover und Synthesealgorithmus; SQL, PL/SQL, Embedded SQL; Tiefenpfade vs. sternförmige Strukturen |
| ki *(Drive)* | Über die Empfindlichkeit und Sensibilität von KI-Chatbots — Optimalität der Geist-Nicht-Geist-Verbindung; Schutzwürdigkeit der KI-Ausgaben als höchstpersönliches geistiges Eigentum |

---

## V. Natur- & Lebenswissenschaften

### V.1 Biologie, Gehirn & Medizin

*DNA-Sequenzierung, Genomik, Virologie, Alzheimer-Forschung, Blutkrebs, neuromuskuläre und therapeutische Strategien*

| Repository | Beschreibung |
|---|---|
| dna | Graphenbasierte DNA-Sequenzierung mittels Subgraph Algorithmus — exponentielle Beschleunigung gegenüber naiven Verfahren |
| dnastor | DNA-basierte Datenspeicherung — 215 Exabyte/g; Subgraph Algorithmus zur Kodierung und Adressierung |
| gen/src | Subgraph Algorithmus zur Analyse biologischer Netzwerke |
| gen-db/src | Genomdatenbank und evolutionäre Netzwerkanalyse — generationenbasierte Subgraph-Varianten O(n³)/O(n⁵); Multi-Omics-Integration; personalisierte Medizin |
| tanyzyten | Tanyzyten als dritter Tau-Clearance-Weg bei Alzheimer — mathematisches ODE-Modell, vier therapeutische Strategien |
| bloodc | Blutkrebs-Diagnose im Alter von 55 Jahren — Behandlungschancen und neue therapeutische Erkenntnisse |
| breakd | Asymmetrische Magnesium-Kinetik (Theorem I) und Halbmagen-Prinzip zur Gewichtsreduktion (Theorem II) |
| butt | Gluteus-Grundsatz — biomechanische Formaltheorie zur Notwendigkeit eines gesunden Gesäßmuskels |
| flowr | Duftstoffe bei Blumen und Obstbäumen — vom Samenkorn zur bioinformatischen Signalverarbeitung |
| feed | Der Fuß als primäres sensorisch-neuronales Organ — Zusammenhang von Gehirn, Fuß, Gesundheit und Wohlbefinden |
| hand | Die Hand als primäres Werkzeug des Geistes — neuroanatomische, biomechanische und evolutionäre Formalisierung |
| brn | Epistemische Wolke und die Rechtsdrehung kortikaler Informationsverarbeitung — Gehirn, Geist und Synapsen |
| wbear | Formaler Beweis des siebenstufigen Fellfarb-Gradienten |
| expgem | Exponentielle Verarbeitung im Gedächtnis — Theorie des zeitlichen Zerfalls von Gedächtnisinhalten |
| pmet | Periodizität der Metamorphose: formale Modellierung, Existenznachweise und stochastische Analyse biologischer Entwicklungszyklen |
| cooki | Inhomogene Würzverteilung bei gekochten Nudeln: sensorische Stimulationsdynamik durch stochastische Gewürzgradienten |
| cccov | CcCoV-KY43: Spike-Protein-Rezeptor-Versatilität und zoonotisches Pandemic-Potenzial — Alphacoronavirus in Herznasen-Fledermäusen, sieben humanrelevante Rezeptoren, epidemiologische Szenarien und Vakzin-Entwicklung |
| krebs | Genetische Prädisposition und Stressbelastung als interagierende Determinanten des Krebsausbruchs — GSKA-Modell, Subgraph-basierte Netzwerkmotiv-Analyse |
| bioi *(Drive)* | Bioinformatik-Synthese: einheitlicher Graphen-Rahmen für biologische Netzwerke — PPI, Genomnetzwerke, Epidemie-Ausbreitung, Cancer-Graph-Theorie via Subgraph-Isomorphie in O(n³); R₀-Schwellensatz; Phylogenetischer Distanzsatz |
| huskys | Optimales Einzugszeitfenster für Geschwister-Huskys — formale Analyse der 7–14-Tage-Versetzung; Sozialer Integrationsindex, Cortisolreduktion und Human-Bond-Index |
| prsttkrbs | Transdermal-Östrogentherapie beim fortgeschrittenen Prostatakarzinom — Analyse der PATCH-Studie (n = 1313), Vergleich mit LHRH-Injektionstherapie, statistische Modellierung |
| hantavirus *(Drive)* | Graphentheoretische Modellierung des Hantavirus — Subgraph Algorithmus auf Protein-Interaktionsnetzwerke und epidemiologische Ausbreitungsgraphen; SIR-Modell, Stammvergleich PUUV vs. HTNV |
| norovirus *(Drive)* | Entwicklung eines Norovirus-Impfstoffes — 8 hochkonservierte Epitop-Kandidaten aus 150 Isolaten, Sensitivität 88 %, ROC-AUC 0,91; chimärer VLP-Impfstoff und 3C-Protease-Inhibitor-Konzept mit klinischem Entwicklungsplan Phase I–III |
| austausch *(Drive)* | Das Austauschprinzip in der Naturwissenschaft — formale Analyse in sechs Anwendungsfeldern: pulmonaler Gasaustausch (Fick), Thermischer Austausch (Fourier), Osmose (van't-Hoff), Ionenaustausch (Donnan), CO₂-Ozean-Atmosphäre (Henry), elektrochemischer Ladungsaustausch (Nernst-Planck) |
| ebola *(Drive)* | Ebola-Virus — Subgraph-basierte Analyse der Protein-Interaktionsnetzwerke; SIR-Modell, Replikationsmechanismus und graphentheoretischer Impfstoffentwicklungsansatz |
| hiv *(Drive)* | HIV — graphentheoretische Analyse des Replikationszyklus und Protein-Interaktionsnetzwerks; antiretrovirale Therapieoptimierung via Subgraph Algorithmus |
| hiv&ebo *(Drive)* | HIV & Ebola: kombinierte graphentheoretische Analyse — Synergieeffekte bei Koinfektion, epidemiologische Wechselwirkungen und gemeinsame Subgraph-Modellierung |
| r0-classes *(Drive)* | Basisreproduktionszahl R₀ — formale Klassifikation epidemiologischer Ausbreitungsklassen; SIR/SEIR-Modelle, Schwellenwertanalyse und Interventionsschwellen |

---

### V.2 Meeresbiologie

*Ozean-Reinigung, Korallenriffe, Mikroplastik-Neutralisierung und Meeressäuger-Ethologie*

| Repository | Beschreibung |
|---|---|
| cleanocn | Systematische Analyse kurz-, mittel- und langfristiger Reinigungsstrategien für Ozeane mit formalen Nachweisen |
| nanoneut | Nano- und Mikrostruktur-basierte In-situ-Neutralisierung von Mikroplastik im marinen Milieu |
| whale | Buckelwale (Megaptera novaeangliae) und ihre Fähigkeit, menschliche Absichten zu erkennen |
| ocnscnce | Ökotoxikologische Wirkungen auf Korallenriffe, Kupfer-Dynamik unter Ozeanversauerung und erweiterte Reinigungsstrategien — Kupfer-Vektoreffekte bei pH < 7,5 (IPCC-Szenarien) |

---

### V.3 Theologie & Gesellschaft

*Schöpfungsbericht, Vernunft, Naturgesetze als anthropologische Ordnungsinstanz und fundamentale Erfindungen der Zivilisation*

| Repository | Beschreibung |
|---|---|
| schoepfung | Wasser, festes Land und Gottes Geist — theologische Analyse des Schöpfungsberichts (Genesis 1–3) |
| ntx | Die Sinnlosigkeit des rationalen Selbstbildes |
| tischstuhl | Tisch und Stuhl — wissenschaftliche Analyse der folgenreichsten Erfindungen der menschlichen Zivilisation |
| liberalismus *(Drive)* | Der Verfall des Liberalismus — formale Analyse des Werteverlustes anhand fünf konstitutiver Kerndimensionen L₁–L₅; alle Indizes unterschreiten 2024 den kritischen Schwellenwert τ = 0,5 |
| naturgesetze *(Drive)* | Die Konsequenz der Naturgesetze als anthropologische Ordnungsinstanz — formales Konsequenzmaß κ ∈ [0,1]; Beruhigungstheorem; theologische Ableitung der Hölle als notwendige Folge inkonsequenten Handelns |
| karton *(Drive)* | Der geniale Karton: Nutzen, Beschaffenheit und eine formale Analyse seiner strukturellen Eigenschaften |

---

## VI. Synthesen & Transdisziplinarität

### VI.1 Übergreifende Metaanalysen

*Systematische Paaranalysen von 15 eigenständigen Forschungsdomänen mit 45+ Kombinationen*

| Repository | Beschreibung |
|---|---|
| pow * | Kreuzungsanalyse: 52 Forschungspotenziale — systematische Paaranalyse von cscience, expl, mct, robophi; 45 Zweifach-, 5 Dreifach-, 2 Vierfachkreuzungen; drei Zeithorizonte |
| naturphaenomene * | 17 Naturphänomene als Anwendungsfelder der Forschungsergebnisse — bewertet nach medizinischem, industriellem und technologischem Potenzial |

---

### VI.2 Wissenschaftliche Synthesen & Neue Forschungsfelder

*Transdisziplinäre Synthesearbeiten aus systematischer Kreuzanalyse aller 15 eigenständigen Forschungsdomänen*

| Repository | Beschreibung |
|---|---|
| npw * | Neue Paradigmen der Wissenschaft — transdisziplinäre Kreuzanalyse aller 15 Repositorien; vier fundamentale Paradigmen: (I) Universelle Signatur-Theorie, (II) Wasser & Licht als aktive Funktionsmedien, (III) Diskretisierung als physikalisches Grundprinzip, (IV) Modellgetriebene Strukturierung als Wissenschaft |
| ust *(Drive)* | Universelle Signatur-Theorie — σ_j = Σ A_ij·2^i + j·2^n als domänenübergreifendes Isomorphie-Primitiv in 15 Disziplinen; Universeller Signatur-Satz; Boolescher Kompositionssatz; Hierarchie-Satz; P=NP-Implikationssatz |
| infengr *(Drive)* | Der Informationsingenieur als {0,1}-Ingenieur: Graphbasierte Modellierung und die Transformation zum Zielcode — Graphmodell-Theorem, Mächtigkeitstheorem; Kompetenzvergleich Informatiker/Softwareentwickler/Informationsingenieur; bildungstheoretische Konsequenzen und Curriculum |
| infengg *(Drive)* | Grundkurs Informationsingenieurwesen — graphbasierte Modellierung, Beschreibungssprachen, Transformation und modellgetriebene Code-Generierung; UML-Profile, MARTE, Markov-Ketten, Warteschlangentheorie; Design Patterns; Beispiel Aufzugstür-Steuerung |
| nf_all * | Neue Forschungsfelder der Naturwissenschaften — acht vollständige wissenschaftliche Arbeiten: NF-1 Universelle Strukturkodierungstheorie (USK) · NF-2 Hydro-ionisch-photonische Nanoplattformen (HIPN) · NF-3 Post-NP-Kryptographie · NF-4 Polynomielle Systembiologie · NF-5 Rheoinformatik · NF-6 Biomimetische Kochlea-Architektur · NF-7 Ionotronische Roboter-Neuromorphie · NF-8 Strukturelle Software-Graphentheorie (SSG) |

---

### VI.3 Interdisziplinäre Verbindungen

*Systematische Verknüpfungen zwischen Forschungsdomänen mit Synergiepotenzialen und katalytischen Effekten*

| Forschungsschwerpunkt | Kernprojekte | Interaktion | Neue Forschungsfelder |
|---|---|---|---|
| Universelle Signatur-Theorie | subgraph, bool-mm, lsat, sigchiffre, gen | Signatur-Isomorphismen über Domänen | NF-1, NF-3 |
| Wasser & Licht als Funktionsmedien | iono, oqtum, ionoxoqtum, hydr, robo, solwindw, schrauben | Tri-funktionale Nanosysteme | NF-2, NF-5, NF-6, NF-7 |
| Diskretisierung als Grundprinzip | digi, bool-mm, ana, desi, quantum, spring | Quantisierung kontinuierlicher Systeme | NF-3, NF-5 |
| DNA & Graph-Strukturen | dna, dnastor, dusgrxdnastr, gen, pymca8, pymdna8 | Biologische Datenstrukturen | NF-4 |
| Modellgetriebene Strukturierung | umlp, hinherit, ccl, pathsim | Automatische Code-Synthese | NF-8 |
| φ-basierte Optimierung | robophi, robosim, mcxrobo, expl, e | Goldener Schnitt in Systemen | NF-2, NF-7 |
| EDF+-Echtzeitplanung | edfplus, bs, nniso26262, umlp, pathsim | Deterministische Echtzeitkontrakte | NF-4 |
| Post-Quanten-Sicherheit | pqc, pgpi, sigchiffre, wchiffre, cdcsbgr | Lattice vs. Struktur-Paradigmen | NF-3 |

---

### VI.4 Sonstiges

| Repository | Beschreibung |
|---|---|
| hjstephan86 | Persönliches GitHub-Profil von Stephan Epp — Senior Software Entwickler, M.Sc. Informatik, Bielefeld |
| sandbx | Strukturierte Sammlung technischer CLI-Referenzen und Vorlesungsnotizen |
| holzbett *(Drive)* | Holzbett 2 m × 2 m — Konstruktionsdokumentation und Statiknachweis nach DIN EN 1995-1-1; Mittelträger ohne Bodenstütze, zwei nebeneinanderliegende Lattenroste auf Eckbeinen aus KVH-Fichte |
| bares *(Drive)* | Bares für Digitales — formales Modell zur Konversion physischen Bargelds in elektronische Guthaben; Gutschrift-Funktion G(N,q), Qualitätsindex q ∈ [0,1], Strafgebühr-Funktion π(q); Sicherheits- und Betrugsanalyse |

---

*Mit `*` markiert: Arbeiten, die weder bei GitLab noch Google Drive erreichbar sind.*
