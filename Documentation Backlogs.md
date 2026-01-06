
# Uniforme Documentatie & Geautomatiseerde Publicatie — Blauwdruk en Backlog

## Inhoudsopgave
- [Epic](#epic)
- [Feature 1 — Analyse & Ontwerp](#feature-1--analyse--ontwerp-documentatiestandaard)
- [Feature 2 — Uniforme `/docs` Structuur & Richtlijnen](#feature-2--uniforme-docs-structuur--richtlijnen)
- [Feature 3 — Templates (API, Architectuur, Changelog, README)](#feature-3--templates-voor-api-architectuur-changelog--readme)
- [Feature 4 — Automatisering Publicatie & Release Notes (CI/CD)](#feature-4--automatisering-van-publicatie--release-notes-cicd)
- [Feature 5 — Adoptie & Migratie Bestaande Repositories](#feature-5--adoptie--migratie-bestaande-repositories)
- [Feature 6 — AI-Ondersteunde Documentatieontwikkeling](#feature-6--ai-ondersteunde-documentatieontwikkeling)

---

## Epic
**Titel**  
Uniforme Documentatie en Geautomatiseerde Publicatieworkflow

**Beschrijving**  
Om de kwaliteit, vindbaarheid en consistentie van technische documentatie te verbeteren, introduceren we een centrale, uniforme documentatiestructuur, standaardtemplates en een geautomatiseerd publicatieproces. Dit stelt ontwikkelaars en documentatiegebruikers in staat om altijd te werken met actuele, betrouwbare informatie over API’s, architectuur, wijzigingen en releases.  
We zetten AI-ondersteuning in via M365 Copilot, VS Code Copilot agent en Visual Studio Insider Copilot agent om documentatie te genereren, verbeteren, beoordelen en veroudering vroegtijdig te signaleren.

**Business Value**
- Consistente en professionele documentatie  
- Minder handmatig onderhoud voor ontwikkelaars en documentatieschrijvers  
- Snellere onboarding van nieuwe teamleden én externe partners  
- Hogere ontwikkelsnelheid door snelle vindbaarheid van actuele informatie  
- Minder risico op verouderde, incomplete of dubbele documentatie  
- Verbeterde gebruikerservaring voor interne en externe eindgebruikers  
- Eindgebruikers vinden sneller antwoorden zonder afhankelijk te zijn van support  
- Betere adoptie en correct gebruik van API’s en systemen

---

## Feature 1 — Analyse & Ontwerp Documentatiestandaard

**Beschrijving**  
Inventariseer huidige documentatiestructuren, definieer documenttypes en doelgroepen, leg eigenaarschap vast, ontwerp target documentatie-architectuur en bepaal AI-inzet. Resultaat: een goedgekeurde blauwdruk die basis vormt voor implementatie.

**Business Value**
- Helder fundament voorkomt wildgroei  
- Snellere implementatie dankzij duidelijke kaders  
- Eigenaarschap voorkomt veroudering  
- Consistente gebruikerservaring  
- Bewuste, effectieve inzet van AI

**Acceptance Criteria**
- Functioneel: inventarisatierapport; documenttypes+doelgroepen; eigenaarschap (RACI); target-architectuur; AI-gebruikspatronen; blauwdruk goedgekeurd door stakeholders.  
- Niet-functioneel: volgt MS-conventies (Markdown/OpenAPI); platform-agnostisch; versiebeheerbaar; AI inzet privacybewust in Microsoft-ecosysteem.  
- AI-specifiek: AI-inzetmatrix; kwaliteitseisen; voorbeeldprompts; PoC voor pipeline-AI-review.

**User Stories & Taken**
- **US1.1 — Inzicht in bestaande documentatievormen**  
  - Task 1.1.1 Inventariseer structuren per repo  
  - Task 1.1.2 Analyseer publicatieprocessen  
  - Task 1.1.3 Overzicht gebruikte templates/praktijken  
  - Task 1.1.4 Identificeer inconsistenties/knelpunten  
  - Task 1.1.5 Compileer inventarisatierapport
- **US1.2 — Documenttypes & doelgroepen definiëren**  
  - Task 1.2.1 Bepaal verplichte/optionele documenttypes  
  - Task 1.2.2 Definieer doelgroepen per type  
  - Task 1.2.3 Matrix type→doelgroep→locatie  
  - Task 1.2.4 Minimale inhoud per type  
  - Task 1.2.5 Richtlijnen toegankelijkheid/taal
- **US1.3 — Eigenaarschap per documenttype (RACI)**  
  - Task 1.3.1 Rollen per type identificeren  
  - Task 1.3.2 RACI-matrix opstellen  
  - Task 1.3.3 Lifecycle-regels vastleggen  
  - Task 1.3.4 Validatie met teams  
  - Task 1.3.5 Governance documenteren
- **US1.4 (AI) — Waar voegt AI waarde toe**  
  - Task 1.4.1 Analyseer AI-mogelijkheden (IDE/M365/pipeline)  
  - Task 1.4.2 Identificeer waardevolle AI-taken  
  - Task 1.4.3 Definieer AI-kwaliteitscriteria  
  - Task 1.4.4 AI-inzetmatrix opstellen  
  - Task 1.4.5 Standaard prompts schrijven  
  - Task 1.4.6 PoC-beschrijving AI in CI/CD

---

## Feature 2 — Uniforme `/docs` Structuur & Richtlijnen

**Beschrijving**  
Ontwerp een standaard, herbruikbare `/docs`-mapstructuur incl. naamgeving, metadata/tags, link/navigatie, versiebeheer (semver/changelog). Platform-agnostisch. AI helpt bij detectie van ontbrekende secties, metadata-voorstellen en structuurreview.

**Business Value**
- Consistentie en vindbaarheid  
- Snellere onboarding  
- Onderhoudbaarheid  
- Platform-flexibiliteit  
- Kwaliteitsborging met AI

**Acceptance Criteria**
- Functioneel: standaard `/docs`-structuur; naamgeving; metadata; link/navigatie; versiebeheer; referentie-implementatie; pilotfeedback verwerkt.  
- Niet-functioneel: MS-conventies; platform-agnostisch; versiebeheerbaar; herhaalbaar toepasbaar.  
- AI-specifiek: prompts voor ontbrekende secties/metadata; AI-review checklist; AI kan index/TOC genereren.

**User Stories & Taken**
- **US2.1 — Uniforme `/docs`-structuur**  
  - Task 2.1.1 Ontwerp top-niveaumappen  
  - Task 2.1.2 Verplichte bestanden per map  
  - Task 2.1.3 Richtlijnen voor bestandsopbouw  
  - Task 2.1.4 Naamgevingsconventies  
  - Task 2.1.5 Navigatierichtlijnen  
  - Task 2.1.6 Referentie-implementatie  
  - Task 2.1.7 Validatie bij pilotteams
- **US2.2 — Versiebeheer-richtlijnen**  
  - Task 2.2.1 Versiestrategie (SemVer/tags)  
  - Task 2.2.2 Release-structuur in `/docs/releases`  
  - Task 2.2.3 Changelog-conventies  
  - Task 2.2.4 Wanneer documentatie bijwerken  
  - Task 2.2.5 Publiceer richtlijnen  
  - Task 2.2.6 Afstemmen met DevOps releases  
  - Task 2.2.7 Validatie stakeholders
- **US2.3 — AI-validatie & metadata**  
  - Task 2.3.1 Prompts voor structuurcontrole  
  - Task 2.3.2 AI-review checklist  
  - Task 2.3.3 Voorbeeld AI-reviewrapport  
  - Task 2.3.4 Prompts voor metadata-suggesties  
  - Task 2.3.5 (Optioneel) Automatische front-matter-check  
  - Task 2.3.6 Richtlijnen AI-gebruik in `/docs`  
  - Task 2.3.7 Documenteer AI-gebruik

---

## Feature 3 — Templates voor API, Architectuur, Changelog & README

**Beschrijving**  
Lever uniforme templates voor API-documentatie, architectuur, changelog/release notes en README.md. Volgen Microsoft-conventies en zijn platform-agnostisch. AI helpt bij het genereren van varianten, verbeteren van secties en voorbeeldcontent.

**Business Value**
- Consistente documentatie  
- Minder inspanning door herbruikbare sjablonen  
- Minder fouten en ontbrekende info  
- Snellere onboarding  
- Betere gebruikerservaring  
- AI-geoptimaliseerde templates

**Acceptance Criteria**
- Functioneel: 4 templates (API/Architectuur/Changelog/README); verplichte secties+richtlijnen+voorbeelden; voorbeeldimplementaties; pilot getest; templates centraal beschikbaar.  
- Niet-functioneel: platform-agnostisch; toegankelijk; consistent; versieerbaar.  
- AI-specifiek: prompts voor templategeneratie/validatie; AI genereert voorbeeldcontent; detectie ontbrekende secties; M365 herschrijft; Copilot geeft suggesties.

**User Stories & Taken**
- **US3.1 — API-template**  
  - Task 3.1.1 Analyse bestaande API-docs  
  - Task 3.1.2 Verplichte secties definiëren  
  - Task 3.1.3 Afstemmen met architecten/API-owners  
  - Task 3.1.4 Eerste versie (Markdown + OpenAPI-stijl)  
  - Task 3.1.5 Voorbeeld-API-doc maken  
  - Task 3.1.6 Pilotteams testen  
  - Task 3.1.7 Feedback verwerken  
  - Task 3.1.8 (AI) Templatevarianten via Copilot  
  - Task 3.1.9 (AI) AI-review op volledigheid/consistentie
- **US3.2 — Architectuurtemplate**  
  - Task 3.2.1 Verzamel bestaande architectuurdocs  
  - Task 3.2.2 Secties definiëren (Context/Solution/Componenten/Integraties/Security/Deployment)  
  - Task 3.2.3 Afstemmen met architectengroep  
  - Task 3.2.4 Template + diagramplaatsen (mermaid/plantUML/afbeeldingen)  
  - Task 3.2.5 Voorbeeldarchitectuurdocument  
  - Task 3.2.6 Pilot  
  - Task 3.2.7 Finaliseren  
  - Task 3.2.8 (AI) Suggesties voor structuur/terminologie  
  - Task 3.2.9 (AI) Voorbeeld diagram-beschrijvingen
- **US3.3 — Changelog & Release Notes template**  
  - Task 3.3.1 Analyse huidige changelogs  
  - Task 3.3.2 Standaardformat (Added/Changed/Fixed/Deprecated/Removed)  
  - Task 3.3.3 Templates `changelog.md` & releases  
  - Task 3.3.4 Link met versiebeheer (Feature 2)  
  - Task 3.3.5 Voorbeeldchangelog  
  - Task 3.3.6 Validatie release managers  
  - Task 3.3.7 Finaliseren  
  - Task 3.3.8 (AI) Voorbeeldchangelogs genereren  
  - Task 3.3.9 (AI) Prompts voor automatische samenvatting
- **US3.4 — README.md template**  
  - Task 3.4.1 Analyse huidige READMEs  
  - Task 3.4.2 Verplichte secties (Summary/Features/Install/Usage/Contributing/Contact)  
  - Task 3.4.3 Template README  
  - Task 3.4.4 Voorbeeld README  
  - Task 3.4.5 Validatie  
  - Task 3.4.6 Finaliseren  
  - Task 3.4.7 (AI) Herschrijven voor helderheid/consistentie  
  - Task 3.4.8 (AI) Generieke voorbeeldtekst
- **US3.5 — AI-ondersteunde templates & voorbeeldcontent**  
  - Task 3.5.1 Promptbibliotheek voor templategeneratie  
  - Task 3.5.2 AI-kwaliteitscriteria voor templates  
  - Task 3.5.3 Voorbeeldcontent per template via AI  
  - Task 3.5.4 AI-checklist voor template-validatie  
  - Task 3.5.5 Richtlijnen: AI-gebruik bij templates

---

## Feature 4 — Automatisering van Publicatie & Release Notes (CI/CD)

**Beschrijving**  
Implementeer een standaard Azure DevOps pipeline voor documentatie: validatie → publicatie → notificatie, plus automatische release notes generatie. Ondersteunt Azure DevOps Wiki en/of andere platforms. AI (Azure OpenAI) helpt bij review, samenvattingen en detectie van verouderde documentatie.

**Business Value**
- Minder handwerk  
- Constante kwaliteit  
- Snellere releases  
- Betere gebruikerservaring  
- AI-ondersteuning

**Acceptance Criteria**
- Functioneel: standaard pipeline; automatische publicatie bij merge/release; automatische release notes; validatiestappen; multi-platform; referentie-implementatie + handleiding.  
- Niet-functioneel: <2 min extra runtime; herbruikbare scripts; werkt voor nieuwe/bestaande repos; security/privacy geborgd.  
- AI-specifiek: AI-samenvatting van diffs; AI-kwaliteitsreview; AI-outdated-detectie; AI-output is suggestief en reviewbaar.

**User Stories & Taken**
- **US4.1 — Automatische publicatie**  
  - Task 4.1.1 Ontwerp publicatiestroom  
  - Task 4.1.2 Bouw pipeline template (YAML)  
  - Task 4.1.3 Publicatie naar DevOps Wiki  
  - Task 4.1.4 Publicatie naar alternatieve platforms (configurabel)  
  - Task 4.1.5 Configuratiehandleiding per repo  
  - Task 4.1.6 Referentie-implementatie + pilot
- **US4.2 — Automatische release notes**  
  - Task 4.2.1 Release note format specificeren  
  - Task 4.2.2 Script: diffs verzamelen  
  - Task 4.2.3 Release notes genereren + toevoegen aan repo  
  - Task 4.2.4 Publiceren naar platform(en)  
  - Task 4.2.5 Notificatie (Teams/Email)  
  - Task 4.2.6 Pilot + validatie  
  - Task 4.2.7 (AI) Samenvatting van diffs  
  - Task 4.2.8 (AI) Validatie op volledigheid
- **US4.3 (AI) — AI-kwaliteitsreview in pipeline**  
  - Task 4.3.1 Reviewcriteria  
  - Task 4.3.2 Pipeline-step AI-call  
  - Task 4.3.3 Quality gates  
  - Task 4.3.4 Logging/archivering  
  - Task 4.3.5 Handleiding reviewresultaten
- **US4.4 (AI) — Outdated-detectie o.b.v. code-diffs**  
  - Task 4.4.1 Mapping code→docs  
  - Task 4.4.2 Diffs verzamelen  
  - Task 4.4.3 AI-analyse impacted docs  
  - Task 4.4.4 PR-comment waarschuwingen  
  - Task 4.4.5 Fine-tuning regels

---

## Feature 5 — Adoptie & Migratie Bestaande Repositories

**Beschrijving**  
Rol de nieuwe documentatiestandaard uit naar bestaande repositories. Voer impactanalyse, definieer migratieplan, doe pilotmigratie, lever handleidingen en zet AI in voor inconsistentie-detectie en migratieadvies.

**Business Value**
- Snelle adoptie  
- Lagere migratiekosten  
- Minder inconsistenties  
- Hogere kwaliteit  
- Teams ontzorgd  
- Platform-agnostisch

**Acceptance Criteria**
- Functioneel: impactanalyse per repo; migratieplan; pilot succesvol; `/docs`+templates+pipeline toegepast; handleiding gepubliceerd; check op inconsistenties/veroudering.  
- Niet-functioneel: herhaalbaar; geen breaking changes; heldere instructies; privacyvriendelijke AI.  
- AI-specifiek: verschillen detecteren; migratievoorstellen; inconsistenties signaleren; Copilot herschrijft; Azure OpenAI migratie-review.

**User Stories & Taken**
- **US5.1 — Impactanalyse**  
  - Task 5.1.1 Repos binnen scope inventariseren  
  - Task 5.1.2 Huidige documentatie per repo analyseren  
  - Task 5.1.3 Ontbrekende/afwijkende docs in kaart  
  - Task 5.1.4 CI/CD-impact controleren  
  - Task 5.1.5 Impactrapport per repo  
  - Task 5.1.6 Resultaten bespreken  
  - Task 5.1.7 (AI) Consistentie-analyse oud vs. nieuw  
  - Task 5.1.8 (AI) Detectie ontbrekende types
- **US5.2 — Migratieplan & adoptiestrategie**  
  - Task 5.2.1 Stappenplan migratie  
  - Task 5.2.2 Adoptiestrategie per team/project  
  - Task 5.2.3 Migratiechecklist developers  
  - Task 5.2.4 Handleiding (Markdown)  
  - Task 5.2.5 Publicatie handleiding  
  - Task 5.2.6 (AI) Migratieadviezen per repo  
  - Task 5.2.7 (AI) Handleiding verbeteren met M365 Copilot  
  - Task 5.2.8 (AI) Prompts voor AI-ondersteunde migratie
- **US5.3 — Pilotmigratie uitvoeren**  
  - Task 5.3.1 Pilotrepos selecteren  
  - Task 5.3.2 `/docs` toepassen  
  - Task 5.3.3 Legacy docs migreren naar templates  
  - Task 5.3.4 CI/CD publicatieflow implementeren  
  - Task 5.3.5 Pipeline testen (validate→AI→publish)  
  - Task 5.3.6 Feedback verzamelen  
  - Task 5.3.7 Verbeteringen verwerken  
  - Task 5.3.8 (AI) Review structuur & volledigheid  
  - Task 5.3.9 (AI) AI-herschrijven legacy docs
- **US5.4 — AI-inconsistentieanalyse & migratieadvies**  
  - Task 5.4.1 AI koppelen aan doc-diffs  
  - Task 5.4.2 Inconsistenties detecteren  
  - Task 5.4.3 Migratievoorstellen per doc  
  - Task 5.4.4 Outdated docs highlighten  
  - Task 5.4.5 Voorbeeld migratieadviesrapport  
  - Task 5.4.6 (AI) PoC “AI Migratie Review”  
  - Task 5.4.7 (AI) Copilot vergelijkingsprompt

---

## Feature 6 — AI-Ondersteunde Documentatieontwikkeling

**Beschrijving**  
Operationeel inzetten van AI in IDE (VS Code/Visual Studio Copilot), M365 Copilot voor herschrijven/kwaliteit, en Azure OpenAI in CI/CD voor review, samenvattingen en outdated-detectie. Lever promptbibliotheek, checklists, pipeline-steps en richtlijnen.

**Business Value**
- Hogere snelheid  
- Constante kwaliteit  
- Minder handwerk  
- Snellere detectie van problemen  
- Betere gebruikerservaring  
- Herhaalbaar & schaalbaar

**Acceptance Criteria**
- Functioneel: promptbibliotheek (IDE/M365); AI-review checklist; referentie-pipeline integraties; richtlijnen voor AI-gebruik; voorbeeldcases/demos.  
- Niet-functioneel: Microsoft-ecosysteem & privacy; AI-output reviewbaar; versiebeheerbaar; ≤2 min extra pipeline tijd.  
- AI-specifiek: prompts voor schrijven/herschrijven/structuur/metadata/samenvatting; Azure OpenAI review & release notes; detectie veroudering; quality gates.

**User Stories & Taken**
- **US6.1 — AI schrijven in IDE**  
  - Task 6.1.1 Use-cases in IDE inventariseren  
  - Task 6.1.2 Copilot agents configureren  
  - Task 6.1.3 Prompts voor docstrings/XML-docs  
  - Task 6.1.4 Voorbeeldworkflow code→docstring→`/docs`  
  - Task 6.1.5 Demo & handleiding
- **US6.2 — AI herschrijven & kwaliteitsverbetering (M365)**  
  - Task 6.2.1 Kwaliteitscriteria definiëren  
  - Task 6.2.2 M365 Copilot prompts (herschrijven/structuur)  
  - Task 6.2.3 Voorbeeldcases  
  - Task 6.2.4 Reviewproces (menselijke goedkeuring)  
  - Task 6.2.5 Schrijf- & stijlrichtlijnen publiceren
- **US6.3 — AI samenvattingen van architectuur/configs**  
  - Task 6.3.1 Bronbestanden identificeren  
  - Task 6.3.2 Prompts voor samenvattingen  
  - Task 6.3.3 Plaatsing in templates  
  - Task 6.3.4 Validatie door architecten  
  - Task 6.3.5 Bibliotheek voorbeeldsamenvattingen
- **US6.4 — AI kwaliteitsreview in CI/CD**  
  - Task 6.4.1 Reviewchecklist  
  - Task 6.4.2 Pipeline-step AI-call  
  - Task 6.4.3 Quality gates (waarschuwing/blokkade)  
  - Task 6.4.4 Logging/archivering  
  - Task 6.4.5 Handleiding voor teams
- **US6.5 — AI detectie verouderde documentatie (diffs)**  
  - Task 6.5.1 Mappingregels code→docs  
  - Task 6.5.2 Diffs verzamelen  
  - Task 6.5.3 AI-analyse impacted docs  
  - Task 6.5.4 PR-comment waarschuwingen  
  - Task 6.5.5 Fine-tuning
- **US6.6 — Promptbibliotheek & richtlijnen**  
  - Task 6.6.1 Promptbibliotheek opzetten  
  - Task 6.6.2 Categorieën (schrijven/herschrijven/structuur/metadata/samenvatting/validatie)  
  - Task 6.6.3 Voorbeeldprompts per documenttype  
  - Task 6.6.4 Richtlijnen (privacy/governance/RACI-koppeling)  
  - Task 6.6.5 Training/demo voor teams
