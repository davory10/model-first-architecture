# Model-First Enterprise Systems Architecture

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21534285.svg)](https://doi.org/10.5281/zenodo.21534285)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language: HR & EN](https://img.shields.io/badge/Language-Croatian%20%7C%20English-green.svg)](#)

> **Rethinking enterprise information systems in the era of Artificial Intelligence.**  
> *Preispitivanje poslovnih informacijskih sustava u eri umjetne inteligencije.*

---

## 📄 Overview / O radu

**Author / Autor:** Davor Veljača  
**Publication Date / Datum objave:** July 2026 / Srpanj 2026.  
**DOI:** [10.5281/zenodo.21534285](https://doi.org/10.5281/zenodo.21534285)  
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### English Summary

The **Model-First Enterprise Systems Architecture** presents a strategic framework for designing, developing, and governing business applications in the age of generative AI. 

Traditional enterprise software scatters business logic across user interfaces, backend API layers, relational tables, and integration glue. As organizations attempt to integrate AI, they face a double threat:
1. **Unbounded AI Execution:** Allowing AI models direct write access to databases or ad-hoc SQL execution introduces hallucination risks, non-deterministic operations, and compliance failures.
2. **Exploding Technical Debt:** Using AI simply to write more application code leads to unmaintainable codebase fragmentation.

#### Key Architectural Pillars
* **Managed Business Model (Single Source of Truth):** Business logic, validation rules, permissions, and workflow boundaries are declared inside a centralized, versioned, machine-readable model.
* **Database as the Deterministic Anchor:** Data integrity, transaction boundaries, strict constraints, and security policies remain anchored in the database engine.
* **AI as the Adaptive Interpreter:** The AI acts purely as an interpreter of user intent and model semantics—translating conversational inputs into authorized, deterministic model operations without raw data access.
* **Generative UI + Fixed Design System:** Dynamic interface assembly tailored to user tasks, bound strictly within predefined visual and UX components.
* **Audit Replay:** Full reconstruction of business decisions linking user identity, AI intent, model version, and database commit state into an immutable audit chain.
* **Infrastructure & Economic Awareness:** Aligning software architecture with compute constraints, energy efficiency demands, and regulatory mandates (e.g., EU Cloud & AI Development Act).

---

### Hrvatski Sažetak

**Model-First Arhitektura Poslovnih Sustava** donosi strateški i arhitektonski okvir za razvoj i upravljanje poslovnim informacijskim sustavima u eri umjetne inteligencije.

Klasični poslovni softver raspoređuje poslovnu logiku kroz korisnička sučelja, backend servise, baze podataka i integracijski kod. Pokušaji masovnog uvođenja AI-ja u takve sustave često dovode do dvaju velikih problema:
1. **Probabilistički kaos:** Prepustite li AI-ju izravno pisanje SQL upita ili neposredno izvođenje transakcija, sustav izlažete riziku halucinacija i narušavanju integriteta podataka.
2. **Povećanje tehničkog duga:** Korištenje AI-ja samo za generiranje još više linija koda ubrzava stvaranje "špageti koda" i otežava održavanje.

#### Temeljni Stupovi Arhitekture
* **Upravljani poslovni model:** Poslovna pravila, ovlasti i workflow definiranirani su na jednom mjestu kroz upravljani, verzionirani i strojno interpretabilni model.
* **Baza podataka kao determinističko sidro:** Transakcijski integritet, sigurnost i pravila izvršavaju se strogo u bazi podataka.
* **AI kao interpretator namjere:** AI služi isključivo kao prilagodljivi prevoditelj ljudske namjere i vodič kroz model—bez neposrednog, slobodnog pristupa produkcijskim podacima.
* **Generativno sučelje uz fiksni dizajnerski sustav:** Dinamičko slaganje radnih prostora prilagođenih zadatku, obuzdano strogim UX/UI okvirom radi vizualne konzistentnosti.
* **Audit Replay:** Potpuna rekonstrukcija poslovnih odluka povezivanjem identiteta, AI namjere, verzije modela i DB dokaza u nepromjenjivi lanac revizije.
* **DEPRO studija slučaja:** Praktičan prikaz primjene načela u realnom poslovnom domenskom okruženju.

---

## 📚 Document Files / Datoteke Dokumenta

The full papers are available in both Croatian and English in this repository and on Zenodo:

| File | Language | Description |
| :--- | :--- | :--- |
| `Model-First_Arhitektura_Poslovnih_Sustava_Davor_Veljaca_HR_FINAL.pdf` | 🇭🇷 Croatian | Službeni izvorni dokument (v1.0) |
| `Model-First_Enterprise_Systems_Architecture_Davor_Veljaca_EN_FINAL.pdf` | 🇬🇧 English | Official translated full paper (v1.0) |

---

## 📖 Citation / Citiranje

If you reference or build upon this architecture in your research, consulting, or software projects, please cite it as follows:

### APA Format
```text
Veljača, D. (2026). Model-First Enterprise Systems Architecture: Rethinking Enterprise Systems in the Era of Artificial Intelligence. Zenodo. https://doi.org/10.5281/zenodo.21534285
```

### BibTeX
```bibtex
@techreport{veljaca2026modelfirst,
  author       = {Davor Velja{{c}}a},
  title        = {{Model-First Enterprise Systems Architecture: Rethinking Enterprise Systems in the Era of Artificial Intelligence}},
  year         = {2026},
  month        = jul,
  institution  = {Zenodo},
  doi          = {10.5281/zenodo.21534285},
  url          = {https://doi.org/10.5281/zenodo.21534285}
}
```

---

## ⚖️ License / Licenca

This work is licensed under a **[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

**You are free to:**
* **Share** — copy and redistribute the material in any medium or format.
* **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

**Under the following terms:**
* **Attribution** — You must give appropriate credit (mention author **Davor Veljača**, document title, and provide the DOI link: `https://doi.org/10.5281/zenodo.21534285`).

---

© 2026 **Davor Veljača**. All rights reserved.
