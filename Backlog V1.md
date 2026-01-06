# Project Backlog — Epic: Uniforme Documentatie en Geautomatiseerde Publicatieworkflow

_Exportdatum: 06-01-2026_

## Inhoudsopgave
- [Epic](#epic)
- [Feature — Feature 1. Analyse & Ontwerp Documentatiestandaard](#feature-feature-1-analyse-ontwerp-documentatiestandaard)
  - [User Story — US1.1 Als documentatiearchitect wil ik inzicht in bestaande documentatievormen, zodat we een goed fundament kunnen ontwerpen.](#user-story-us1-1-als-documentatiearchitect-wil-ik-inzicht-in-bestaande-documentatievormen-zodat-we-een-goed-fundament-kunnen-ontwerpen)
  - [User Story — US1.2 Als documentatiegebruiker wil ik dat documenttypes en doelgroepen helder zijn, zodat ik weet waar welke informatie hoort.](#user-story-us1-2-als-documentatiegebruiker-wil-ik-dat-documenttypes-en-doelgroepen-helder-zijn-zodat-ik-weet-waar-welke-informatie-hoort)
  - [User Story — US1.3 Als platformteam wil ik eigenaarschap per documenttype gedefinieerd hebben, zodat onderhoud gewaarborgd is.](#user-story-us1-3-als-platformteam-wil-ik-eigenaarschap-per-documenttype-gedefinieerd-hebben-zodat-onderhoud-gewaarborgd-is)
  - [User Story — US1.4 Als documentatiearchitect wil ik weten waar AI waarde kan toevoegen, zodat we AI bewust en effectief inzetten.](#user-story-us1-4-als-documentatiearchitect-wil-ik-weten-waar-ai-waarde-kan-toevoegen-zodat-we-ai-bewust-en-effectief-inzetten)
- [Feature — Feature 2. Uniforme /docs Structuur & Richtlijnen](#feature-feature-2-uniforme-docs-structuur-richtlijnen)
  - [User Story — US2.1 Als ontwikkelaar wil ik een uniforme /docs structuur, zodat alle projecten hetzelfde format gebruiken.](#user-story-us2-1-als-ontwikkelaar-wil-ik-een-uniforme-docs-structuur-zodat-alle-projecten-hetzelfde-format-gebruiken)
  - [User Story — US2.2 Als team wil ik richtlijnen voor versiebeheer, zodat documentatie consistent wordt beheerd.](#user-story-us2-2-als-team-wil-ik-richtlijnen-voor-versiebeheer-zodat-documentatie-consistent-wordt-beheerd)
  - [User Story — US2.3 Als ontwikkelaar wil ik AI die mij helpt ontbrekende onderdelen te detecteren, zodat documentatie volledig blijft.](#user-story-us2-3-als-ontwikkelaar-wil-ik-ai-die-mij-helpt-ontbrekende-onderdelen-te-detecteren-zodat-documentatie-volledig-blijft)
- [Feature — Feature 3. Standaard Templates voor API‑documentatie, Architectuur, Changelog en README](#feature-feature-3-standaard-templates-voor-api-documentatie-architectuur-changelog-en-readme)
  - [User Story — US3.1 Als ontwikkelaar wil ik een standaard API‑documentatiesjabloon, zodat API‑informatie altijd consistent en begrijpelijk is voor interne en externe gebruikers](#user-story-us3-1-als-ontwikkelaar-wil-ik-een-standaard-api-documentatiesjabloon-zodat-api-informatie-altijd-consistent-en-begrijpelijk-is-voor-interne-en-externe-gebruikers)
  - [User Story — US3.2 Als architect wil ik een vaste template voor architectuurdocumentatie, zodat ontwerp, context, diagrammen en technische beslissingen uniform worden beschreven](#user-story-us3-2-als-architect-wil-ik-een-vaste-template-voor-architectuurdocumentatie-zodat-ontwerp-context-diagrammen-en-technische-beslissingen-uniform-worden-beschreven)
  - [User Story — US3.3 Als release manager wil ik een template voor changelogs en release notes, zodat wijzigingen per project georganiseerd en transparant worden vastgelegd.](#user-story-us3-3-als-release-manager-wil-ik-een-template-voor-changelogs-en-release-notes-zodat-wijzigingen-per-project-georganiseerd-en-transparant-worden-vastgelegd)
  - [User Story — US3.4 Als ontwikkelaar wil ik een gestandaardiseerde README.md, zodat elk project dezelfde basisinformatie heeft en nieuwe gebruikers snel kunnen starten.](#user-story-us3-4-als-ontwikkelaar-wil-ik-een-gestandaardiseerde-readme-md-zodat-elk-project-dezelfde-basisinformatie-heeft-en-nieuwe-gebruikers-snel-kunnen-starten)
  - [User Story — US3.5 Als team wil ik AI‑ondersteuning voor het genereren en verbeteren van templates en voorbeeldinhoud, zodat documentatie sneller en consistenter kan worden gemaakt.](#user-story-us3-5-als-team-wil-ik-ai-ondersteuning-voor-het-genereren-en-verbeteren-van-templates-en-voorbeeldinhoud-zodat-documentatie-sneller-en-consistenter-kan-worden-gemaakt)
- [Feature — Feature 4. Geautomatiseerde validatie, publicatie en release notes voor documentatie (CI/CD)](#feature-feature-4-geautomatiseerde-validatie-publicatie-en-release-notes-voor-documentatie-ci-cd)
  - [User Story — Us4.1 Als ontwikkelaar wil ik dat documentatie automatisch wordt gepubliceerd na een merge of release, zodat informatie altijd actueel en centraal beschikbaar is.](#user-story-us4-1-als-ontwikkelaar-wil-ik-dat-documentatie-automatisch-wordt-gepubliceerd-na-een-merge-of-release-zodat-informatie-altijd-actueel-en-centraal-beschikbaar-is)
  - [User Story — US4.2 Als release manager wil ik dat release notes automatisch worden gegenereerd en gepubliceerd, zodat wijzigingen duidelijk en consistent worden vastgelegd.](#user-story-us4-2-als-release-manager-wil-ik-dat-release-notes-automatisch-worden-gegenereerd-en-gepubliceerd-zodat-wijzigingen-duidelijk-en-consistent-worden-vastgelegd)
  - [User Story — US4.3 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt beoordeeld op volledigheid, structuur en leesbaarheid.](#user-story-us4-3-als-team-wil-ik-ai-reviews-in-de-pipeline-zodat-documentatie-automatisch-wordt-beoordeeld-op-volledigheid-structuur-en-leesbaarheid)
  - [User Story — US4.4 Als ontwikkelaar wil ik dat AI aangeeft welke documentatie mogelijk moet worden bijgewerkt na code‑wijzigingen, zodat docs up‑to‑date blijven.](#user-story-us4-4-als-ontwikkelaar-wil-ik-dat-ai-aangeeft-welke-documentatie-mogelijk-moet-worden-bijgewerkt-na-code-wijzigingen-zodat-docs-up-to-date-blijven)
- [Feature — Feature 5. Adoptie & Migratie van Bestaande Repositories naar de Nieuwe Documentatiestandaard](#feature-feature-5-adoptie-migratie-van-bestaande-repositories-naar-de-nieuwe-documentatiestandaard)
  - [User Story — US5.1 Als platformteam wil ik inzicht in welke aanpassingen nodig zijn voor bestaande repositories, zodat we een correcte migratieplanning kunnen maken.](#user-story-us5-1-als-platformteam-wil-ik-inzicht-in-welke-aanpassingen-nodig-zijn-voor-bestaande-repositories-zodat-we-een-correcte-migratieplanning-kunnen-maken)
  - [User Story — US5.2 Als ontwikkelteam wil ik een duidelijk migratieplan, zodat ik weet welke stappen nodig zijn om de nieuwe documentatiestandaard te gebruiken.](#user-story-us5-2-als-ontwikkelteam-wil-ik-een-duidelijk-migratieplan-zodat-ik-weet-welke-stappen-nodig-zijn-om-de-nieuwe-documentatiestandaard-te-gebruiken)
  - [User Story — US5.3 Als platformteam wil ik de nieuwe standaard testen op een pilot repository, zodat we zeker weten dat de aanpak werkt voordat we dit breder uitrollen.](#user-story-us5-3-als-platformteam-wil-ik-de-nieuwe-standaard-testen-op-een-pilot-repository-zodat-we-zeker-weten-dat-de-aanpak-werkt-voordat-we-dit-breder-uitrollen)
  - [User Story — US5.4 Als platformteam wil ik AI gebruiken om inconsistenties te detecteren en migratievoorstellen te genereren, zodat migratie sneller en nauwkeuriger wordt.](#user-story-us5-4-als-platformteam-wil-ik-ai-gebruiken-om-inconsistenties-te-detecteren-en-migratievoorstellen-te-genereren-zodat-migratie-sneller-en-nauwkeuriger-wordt)
- [Feature — Feature 6. AI‑Ondersteuning voor Schrijven, Verbeteren en Valideren van Documentatie](#feature-feature-6-ai-ondersteuning-voor-schrijven-verbeteren-en-valideren-van-documentatie)
  - [User Story — US6.1 Als ontwikkelaar wil ik AI‑ondersteuning in mijn IDE, zodat ik sneller documentatie kan schrijven, docstrings/XML‑docs kan genereren en secties kan aanvullen.](#user-story-us6-1-als-ontwikkelaar-wil-ik-ai-ondersteuning-in-mijn-ide-zodat-ik-sneller-documentatie-kan-schrijven-docstrings-xml-docs-kan-genereren-en-secties-kan-aanvullen)
  - [User Story — US6.2 Als documentatieschrijver wil ik M365 Copilot gebruiken om teksten te herschrijven en te verbeteren, zodat documentatie consistent, leesbaar en volgens richtlijnen is.](#user-story-us6-2-als-documentatieschrijver-wil-ik-m365-copilot-gebruiken-om-teksten-te-herschrijven-en-te-verbeteren-zodat-documentatie-consistent-leesbaar-en-volgens-richtlijnen-is)
  - [User Story — US6.3 Als architect wil ik dat AI complexe configuratie‑ en architectuurbestanden samenvat in begrijpelijke documentatie, zodat kennis snel overdraagbaar is.](#user-story-us6-3-als-architect-wil-ik-dat-ai-complexe-configuratie-en-architectuurbestanden-samenvat-in-begrijpelijke-documentatie-zodat-kennis-snel-overdraagbaar-is)
  - [User Story — Us6.4 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt gecontroleerd op structuur, volledigheid en metadata.](#user-story-us6-4-als-team-wil-ik-ai-reviews-in-de-pipeline-zodat-documentatie-automatisch-wordt-gecontroleerd-op-structuur-volledigheid-en-metadata)
  - [User Story — US6.5 Als ontwikkelaar wil ik dat AI documentatie markeert als mogelijk verouderd bij code‑wijzigingen, zodat we tijdig updates doen.](#user-story-us6-5-als-ontwikkelaar-wil-ik-dat-ai-documentatie-markeert-als-mogelijk-verouderd-bij-code-wijzigingen-zodat-we-tijdig-updates-doen)
  - [User Story — US6.6 Als platformteam wil ik een centrale promptbibliotheek en richtlijnen, zodat AI consistent, veilig en effectief wordt ingezet.](#user-story-us6-6-als-platformteam-wil-ik-een-centrale-promptbibliotheek-en-richtlijnen-zodat-ai-consistent-veilig-en-effectief-wordt-ingezet)

---

## Epic

**Titel:** Epic: Uniforme Documentatie en Geautomatiseerde Publicatieworkflow — _New_

Beschrijving
Om de kwaliteit, vindbaarheid en consistentie van technische documentatie te verbeteren, willen we een centrale, uniforme documentatiestructuur introduceren, inclusief standaardtemplates en een geautomatiseerd publicatieproces. Dit stelt alle ontwikkelaars en documentatiegebruikers in staat om altijd te werken met actuele en betrouwbare informatie over API’s, architectuur, wijzigingen en releases.
Daarnaast zetten we AI‑ondersteuning in via M365 Copilot, de VS Code Copilot agent en de Visual Studio Insider Copilot agent om documentatie te genereren, te verbeteren, op kwaliteit te beoordelen en mogelijke veroudering vroegtijdig te signaleren. Hierdoor versnellen we het schrijven en onderhouden van documentatie en verhogen we de consistentie tussen teams.
Business Value
Consistente en professionele documentatie
Minder handmatig onderhoud voor ontwikkelaars en documentatieschrijvers
Snellere onboarding van nieuwe teamleden én externe partners
Hogere ontwikkelsnelheid door snelle vindbaarheid van actuele informatie
Minder risico op verouderde, incomplete of dubbele documentatie
Verbeterde gebruikerservaring voor interne en externe eindgebruikers door duidelijke, betrouwbare en toegankelijke documentatie
Eindgebruikers kunnen sneller antwoorden vinden zonder afhankelijk te zijn van ontwikkelaars of support
Gebruikers beschikken altijd over actuele informatie, wat de adoptie en het correct gebruik van API’s en systemen verbetert

---

### Feature — Feature 1. Analyse & Ontwerp Documentatiestandaard — _New_

Beschrijving
Deze feature richt zich op het in kaart brengen, definiëren en ontwerpen van een organisatiebrede documentatiestandaard. We inventariseren bestaande documentatiestructuren, leggen documenttypes en doelgroepen vast, definiëren eigenaarschap, en ontwerpen de doelarchitectuur voor documentatie (standaard /docs-structuur, templates, versiebeheer, en publicatieprincipes).
Daarnaast bepalen we waar en hoe AI (M365 Copilot, VS Code Copilot Agent, Visual Studio Insider Copilot en Azure OpenAI) wordt ingezet binnen de documentatie‑lifecycle—bij het genereren, verbeteren, valideren en actueel houden van documentatie.
Resultaat van deze feature: een goedgekeurde blauwdruk (principes, structuur, templatescope, eigenaarschap, AI‑gebruikspatronen) die de basis vormt voor implementatie in volgende features.
Business Value
Een heldere en gedragen standaard voorkomt wildgroei en versnippering.
Snellere implementatie in latere features dankzij duidelijke kaders en scope.
Duidelijke eigenaarschap voorkomt verouderde documentatie en onduidelijkheden.
Consistente gebruikerservaring voor interne en externe eindgebruikers.
AI‑bewuste inrichting verhoogt kwaliteit en snelheid, zonder afhankelijk te zijn van ad‑hoc inzet.
✅ Acceptance Criteria
Functioneel
 Een inventarisatierapport van huidige documentatiestructuren, tooling en publicatievormen per repository is opgesteld en gedeeld.
 Documenttypes (API, architectuur, changelog/release notes, README, ADR’s, handleidingen) en doelgroepen (intern/extern) zijn gedefinieerd en gedocumenteerd.
 Eigenaarschap per documenttype (roles: API owner, architect, release manager, tech writer) is vastgelegd en geaccepteerd door stakeholders.
 Een target documentatie‑architectuur is ontworpen: principes, /docs basismodel, versiebeheer‑richtlijnen, metadata/tags, en publicatiekanalen (DevOps Wiki en/of andere repos/portals).
 AI‑gebruikspatronen zijn beschreven: waar Copilot/AI wordt ingezet (templategeneratie, kwaliteitsreview, release notes, outdated detection) en hoe (IDE vs. pipeline).
 De blauwdruk (design document) is goedgekeurd door het platformteam en ten minste 2 vertegenwoordigers van ontwikkelteams.
Niet‑functioneel
 De standaard volgt Microsoft‑conventies (Markdown, OpenAPI) en interne schrijf- en toegankelijkheidsrichtlijnen.
 De standaard is platform‑agnostisch: toepasbaar voor Azure DevOps Wiki en/of andere documentatieplatformen.
 De blauwdruk is versiebeheerbaar (opgenomen in centrale repo) en herhaalbaar toepasbaar voor alle projecten.
 AI‑inzet wordt privacy‑bewust en binnen het Microsoft‑ecosysteem beschreven (M365 Copilot, Azure OpenAI, IDE‑agents).
AI‑specifiek
 Een AI‑inzetmatrix definieert per documenttype en fase welke AI‑agent wordt gebruikt (VS Code Copilot, Visual Studio Insider Copilot, M365 Copilot, Azure OpenAI).
 AI‑kwaliteitscriteria zijn vastgelegd (structuur, toon, volledigheid, consistentie, metadata).
 Voorbeeld prompts voor Copilot zijn opgesteld (templategeneratie, herschrijven, samenvatten, ontbrekende secties, tag/metadata).
 Een proof‑of‑concept beschrijft hoe een pipeline AI kan aanroepen voor documentatie‑review (zonder directe implementatie in deze feature).

**User Stories**

#### User Story — US1.1 Als documentatiearchitect wil ik inzicht in bestaande documentatievormen, zodat we een goed fundament kunnen ontwerpen.

**Taken**
- [ ] Inventariseer bestaande documentatiestructuren per repository
- [ ] Analyseer huidige publicatieprocessen
- [ ] Maak een overzicht van gebruikte templates en praktijken
- [ ] Identificeer inconsistenties en knelpunten
- [ ] Compileer inventarisatierapport voor stakeholders

#### User Story — US1.2 Als documentatiegebruiker wil ik dat documenttypes en doelgroepen helder zijn, zodat ik weet waar welke informatie hoort.

**Taken**
- [ ] Bepaal verplichte en optionele documenttypes
- [ ] Definieer doelgroepen per documenttype
- [ ] Maak matrix documenttype → doelgroep → locatie
- [ ] Beschrijf minimale inhoud per documenttype
- [ ] Leg richtlijnen vast voor toegankelijkheid en taalgebruik

#### User Story — US1.3 Als platformteam wil ik eigenaarschap per documenttype gedefinieerd hebben, zodat onderhoud gewaarborgd is.

**Taken**
- [ ] Identificeer rollen per documenttype
- [ ] Maak een RACI-model (Responsible/Accountable/Consulted/Informed)
- [ ] Leg document lifecycle regels vast
- [ ] Valideer eigenaarschap met teams
- [ ] Documenteer governance in de blauwdruk

#### User Story — US1.4 Als documentatiearchitect wil ik weten waar AI waarde kan toevoegen, zodat we AI bewust en effectief inzetten.

**Taken**
- [ ] Analyseer AI-mogelijkheden in VS Code Copilot, Visual Studio Copilot en M365 Copilot
- [ ] Inventariseer taken waar AI het meeste waarde levert
- [ ] Definieer AI‑kwaliteitscriteria
- [ ] Ontwikkel een AI-inzetmatrix
- [ ] Schrijf een set standaard prompts
- [ ] Schrijf PoC‑beschrijving voor AI in CI/CD

---

### Feature — Feature 2. Uniforme /docs Structuur & Richtlijnen — _New_

Beschrijving
Deze feature realiseert een standaard en herbruikbare /docs‑mapstructuur voor alle projecten, inclusief naamgevingsconventies, metadata/tags, link‑conventies, en richtlijnen voor versiebeheer (semver, release map, changelog).
Doel is dat elke repository dezelfde basisstructuur hanteert, waardoor documentatie consistent, vindbaar en onderhoudbaar wordt.
De standaard is platform‑agnostisch: toepasbaar voor Azure DevOps Wiki, SharePoint, Markdown‑portals of centrale docs‑repositories.
AI‑ondersteuning (M365 Copilot, VS Code Copilot agent, Visual Studio Insider Copilot) wordt gebruikt om ontbrekende secties te signaleren, metadata voor te stellen en structuurconformiteit te reviewen.
Resultaat: Een goedgekeurde standaard /docs‑structuur + richtlijnen voor versiebeheer die door alle teams kan worden toegepast.
Business Value
Consistentie in documentatiestructuur over alle projecten → makkelijker zoeken & navigeren.
Snellere onboarding: teams herkennen direct waar docs staan en wat verplicht is.
Onderhoudbaarheid: standaard indeling en versiebeheer verminderen fouten en veroudering.
Platform‑flexibiliteit: bruikbaar op elk documentatieplatform, nu en in de toekomst.
Kwaliteitsborging: AI helpt bij het bewaken van structuur, volledigheid en metadata.
✅ Acceptance Criteria
Functioneel
 Er is een standaard /docs‑structuur vastgesteld (top‑niveaumappen en verplichte bestanden).
 Naamgevingsconventies en best practices (bijv. api/, architecture/, releases/, adr/, guides/, index.md) zijn gedocumenteerd.
 Metadata‑richtlijnen zijn beschikbaar (front‑matter/tags, owners, last‑updated, version).
 Link‑conventies en navigatie‑richtlijnen zijn beschreven (relatieve paden, indexpagina’s, TOC).
 Versiebeheer‑richtlijnen voor documentatie zijn gedefinieerd (semver, release folders, changelog).
 Een referentie‑implementatie (voorbeeldrepo of sample in centrale repo) is opgeleverd.
 Minimaal 2 pilotteams hebben de structuur gevalideerd en feedback is verwerkt.
Niet‑functioneel
 Standaard volgt Microsoft‑conventies (Markdown/OpenAPI) en interne toegankelijkheidsrichtlijnen.
 Structuur is platform‑agnostisch en niet afhankelijk van één publicatieplatform.
 Richtlijnen zijn versiebeheerbaar en centraal gepubliceerd (docs‑as‑code).
 Adoptie is herhaalbaar: één script of handleiding om structuur toe te passen in nieuwe/bestaande repos.
AI‑specifiek
 AI‑prompts beschikbaar om ontbrekende secties te detecteren en metadata/tags te suggereren.
 Een AI‑review checklist (voor IDE agents of pipeline) controleert structuurconformiteit.
 Copilot kan indexpagina’s en TOC’s genereren op basis van bestaande bestanden.

**User Stories**

#### User Story — US2.1 Als ontwikkelaar wil ik een uniforme /docs structuur, zodat alle projecten hetzelfde format gebruiken.

Wat het oplevert
Standaard /docs structuur + navigatie

**Taken**
- [ ] Ontwerp top‑niveaumappen van de /docs‑structuur
- [ ] Definieer verplichte bestanden per map
- [ ] Schrijf richtlijnen voor bestandsopbouw (hoofdstukken / secties)
- [ ] Definieer naamgevingsconventies
- [ ] Maak navigatierichtlijnen (TOC, index.md, cross-links)
- [ ] Bouw een referentie-implementatie
- [ ] Valideer structuur bij 2 pilotteams

#### User Story — US2.2 Als team wil ik richtlijnen voor versiebeheer, zodat documentatie consistent wordt beheerd.

Wat het oplevert
Richtlijnen voor documentatie-versiebeheer

**Taken**
- [ ] Bepaal versiebeheerstrategie voor documentatie
- [ ] Definieer structuur voor releases in /docs/release
- [ ] Maak changelog‑conventies
- [ ] Richtlijnen: wanneer moet documentatie worden bijgewerkt?
- [ ] Documenteer richtlijnen in een centrale plek
- [ ] Stem versiebeheer af met DevOps releaseprocessen
- [ ] Validatie met stakeholders

#### User Story — US2.3 Als ontwikkelaar wil ik AI die mij helpt ontbrekende onderdelen te detecteren, zodat documentatie volledig blijft.

Wat het oplevert
AI die helpt structuur & metadata te bewaken

**Taken**
- [ ] Task 2.3.1 (AI) — Maak Copilot-prompts voor structuurcontrole
- [ ] Task 2.3.2 (AI) — Ontwikkel checklist voor AI‑review
- [ ] Task 2.3.3 (AI) — Bouw voorbeeld AI-reviewrapport
- [ ] Task 2.3.4 (AI) — Prompts ontwikkelen voor metadata-suggesties
- [ ] Task 2.3.5 (AI) — Automatiseer (optioneel) metadata-check
- [ ] Richtlijnen voor gebruik AI in /docs structuren
- [ ] Documenteer AI-gebruik in standaard documentatieblauwdruk

---

### Feature — Feature 3. Standaard Templates voor API‑documentatie, Architectuur, Changelog en README — _New_

Beschrijving
Deze feature levert een set uniforme templates op voor alle projectdocumentatie, waaronder API‑documentatie, architectuurdocumentatie, changelogs/release notes en README.md‑bestanden. Deze templates zorgen voor een consistente kwaliteit, een voorspelbare structuur en professionele communicatie naar interne en externe gebruikers.
De templates volgen Microsoft‑conventies (Markdown, OpenAPI‑stijl, architectuurcategorieën) en zijn platform‑agnostisch, zodat ze toepasbaar zijn in Azure DevOps Wiki, SharePoint of elk ander documentatieplatform.
AI‑ondersteuning (VS Code Copilot Agent, Visual Studio Copilot Agent en M365 Copilot) wordt gebruikt om templatevarianten te genereren, secties te verbeteren, voorbeeldcontent te maken, en kwaliteit te bewaken.
Het resultaat is een set herbruikbare en goedgekeurde templates die door elk team gebruikt kunnen worden bij nieuwe en bestaande projecten.
Business Value
Consistente documentatie over alle projecten en teams
Minder inspanning voor ontwikkelaars door herbruikbare sjablonen
Minder fouten en ontbrekende informatie dankzij duidelijke structuur
Snellere onboarding doordat documentatie voorspelbaar en herkenbaar is
Betere gebruikerservaring voor interne en externe eindgebruikers
AI‑geoptimaliseerde templates verhogen kwaliteit en verkleinen de werkdruk
Acceptance Criteria
Functioneel
 Er zijn 4 templates gemaakt: API, Architectuur, Changelog/Release Notes, README.md
 Templates bevatten verplichte secties, richtlijnen en voorbeelden
 Templates volgen interne richtlijnen + Microsoft Docs‑conventies
 Een voorbeeldimplementatie per template is beschikbaar
 Templates zijn getest door 2–3 pilotteams
 Alle templates bevinden zich in een centrale repository (/docs/templates/)
Niet‑functioneel
 Templates zijn platform‑agnostisch
 Templates zijn begrijpelijk, toegankelijk en consistent in stijl
 Templates zijn bruikbaar voor M365 Copilot en IDE‑Copilot agents (goed promptable)
 Templates zijn versieerbaar en onderhoudbaar
AI‑specifiek
 AI‑prompts zijn ontwikkeld voor templategeneratie en validatie
 AI genereert voorbeeldcontent voor elke template
 AI kan ontbrekende secties detecteren tijdens schrijven
 M365 Copilot kan templates herschrijven voor leesbaarheid
 Copilot agents kunnen automatische suggesties geven (secties, voorbeelden, metadata)

**User Stories**

#### User Story — US3.1 Als ontwikkelaar wil ik een standaard API‑documentatiesjabloon, zodat API‑informatie altijd consistent en begrijpelijk is voor interne en externe gebruikers

**Taken**
- [ ] Analyseer bestaande API‑documentatie binnen de organisatie
- [ ] Definieer verplichte secties
- [ ] Stem af met architecten en API‑owners
- [ ] Maak eerste versie van API-template (Markdown + OpenAPI-stijl)
- [ ] Bouw voorbeeld-API-documentatie
- [ ] Laat 2 pilotteams testen
- [ ] Verwerk feedback en finaliseer template
- [ ] Task 3.1.8 (AI) — Genereer templatevarianten via Copilot
- [ ] Task 3.1.9 (AI) — AI‑review voor volledigheid en consistentie

#### User Story — US3.2 Als architect wil ik een vaste template voor architectuurdocumentatie, zodat ontwerp, context, diagrammen en technische beslissingen uniform worden beschreven

**Taken**
- [ ] Verzamel bestaande architectuurdocumenten
- [ ] Definieer vaste secties
- [ ] Stem af met architectengroep
- [ ] Maak template + diagramplaatsen (mermaid, plantUML of handgetekend)
- [ ] Bouw voorbeeldarchitectuurdocument
- [ ] Pilot met 1–2 projecten
- [ ] Verwerk feedback + finaliseer
- [ ] Task 3.2.8 (AI) — AI-suggesties voor structuur en terminologie
- [ ] Task 3.2.9 (AI) — AI‑generatie van voorbeeld diagram-beschrijvingen

#### User Story — US3.3 Als release manager wil ik een template voor changelogs en release notes, zodat wijzigingen per project georganiseerd en transparant worden vastgelegd.

**Taken**
- [ ] Analyseer huidige changelogs en release-processen
- [ ] Definieer standaardformat
- [ ] Maak template voor changelog.md & releases
- [ ] Integreer met versiebeheer-richtlijnen (Feature 2)
- [ ] Bouw voorbeeld-changelog voor demo
- [ ] Validatie door release managers
- [ ] Finaliseer template
- [ ] Task 3.3.8 (AI) — Copilot-generatie van voorbeeldchangelogs
- [ ] Task 3.3.9 (AI) — Ontwikkel prompts voor automatische changelog‑samenvatting

#### User Story — US3.4 Als ontwikkelaar wil ik een gestandaardiseerde README.md, zodat elk project dezelfde basisinformatie heeft en nieuwe gebruikers snel kunnen starten.

**Taken**
- [ ] Analyseer huidige README’s
- [ ] Definieer verplichte secties
- [ ] Maak template README.md
- [ ] Bouw voorbeeld README
- [ ] Validatie met 2 teams
- [ ] Finaliseer template
- [ ] Task 3.4.7 (AI) — Copilot herschrijft voor helderheid en consistentie
- [ ] Task 3.4.8 (AI) — Maak generieke voorbeeldtekst via M365 Copilot

#### User Story — US3.5 Als team wil ik AI‑ondersteuning voor het genereren en verbeteren van templates en voorbeeldinhoud, zodat documentatie sneller en consistenter kan worden gemaakt.

**Taken**
- [ ] Maak AI‑promptbibliotheek voor templategeneratie
- [ ] Definieer AI‑kwaliteitscriteria voor templates
- [ ] Ontwikkel AI‑checklist voor template validatie
- [ ] Documenteer hoe teams AI moeten gebruiken bij templates

---

### Feature — Feature 4. Geautomatiseerde validatie, publicatie en release notes voor documentatie (CI/CD) — _New_

Beschrijving
Deze feature realiseert een volledig geautomatiseerde documentatieworkflow in Azure DevOps:
Validatie van documentatie (structuur, verplichte secties, broken links, metadata)
Publicatie naar Azure DevOps Wiki en/of andere gekozen documentatieplatformen (SharePoint, centrale docs‑portal, Markdown‑site)
Automatische generatie van release notes op basis van commits/PR’s, gegroepeerd per type wijziging
AI‑ondersteuning binnen de pipeline (Azure OpenAI) voor kwaliteitsreview, samenvattingen en detectie van mogelijk verouderde documentatie o.b.v. code‑diffs
Resultaat: één standaard CI/CD‑publicatieflow die door alle repositories herbruikbaar is, met AI‑verrijkte kwaliteit en release notes.
Business Value
Minder handwerk: publicatie, validatie en release notes gaan automatisch
Constante kwaliteit: fouten en ontbrekende onderdelen worden automatisch gedetecteerd
Snellere releases: documentatie is direct synchroon met code
Betere gebruikerservaring: actuele docs en heldere release notes
AI‑ondersteuning: menselijke review blijft, maar met slimme hulp voor snelheid en consistentie
✅ Acceptance Criteria
Functioneel
 Een standaard Azure DevOps pipeline is beschikbaar voor documentatie: validatie → publicatie → notificatie
 Documentatie wordt automatisch gepubliceerd bij merge naar main of bij release tag
 Release notes worden automatisch gegenereerd en toegevoegd aan README.md of /docs/releases/
 Validatie omvat: structuur, verplichte secties, broken links, metadata/front‑matter
 Pipeline ondersteunt Azure DevOps Wiki en andere documentatieplatformen (configurabel)
 Er is een referentie‑implementatie + handleiding hoe teams deze pipeline adopteren
Niet‑functioneel
 Pipeline draait binnen < 2 minuten extra runtime t.o.v. huidige CI/CD
 Scripts zijn herbruikbaar en versiebeheerbaar (centrale repo)
 Oplossing werkt voor nieuwe en bestaande repositories
 Beveiliging en privacy zijn geborgd (geen data buiten Microsoft‑ecosysteem)
AI‑specifiek
 AI (Azure OpenAI) kan release note‑samenvattingen genereren op basis van commit/PR‑diffs
 AI kan documentatie kwaliteitsreviewen (structuur, ontbrekende secties, leesbaarheid)
 AI kan op basis van code‑differences documentatie bestempelen als “mogelijk verouderd”
 AI‑output is suggestief en reviewbaar (menselijke goedkeuring blijft vereist)

**User Stories**

#### User Story — Us4.1 Als ontwikkelaar wil ik dat documentatie automatisch wordt gepubliceerd na een merge of release, zodat informatie altijd actueel en centraal beschikbaar is.

**Taken**
- [ ] Ontwerp publicatiestroom (triggers & stappen)
- [ ] Bouw Azure DevOps pipeline template voor documentatiepublicatie
- [ ] Implementeer publicatie naar Azure DevOps Wiki
- [ ] Implementeer publicatie naar alternatieve platforms
- [ ] Configuratiehandleiding per repository
- [ ] Referentie‑implementatie + pilot

#### User Story — US4.2 Als release manager wil ik dat release notes automatisch worden gegenereerd en gepubliceerd, zodat wijzigingen duidelijk en consistent worden vastgelegd.

**Taken**
- [ ] Specificeer release note format (Aligned met Feature 3 & 2)
- [ ] Bouw script om diffs te verzamelen (commits/PR’s/tags)
- [ ] Genereer release notes en voeg toe aan repo
- [ ] Publiceer release notes automatisch naar platform(en)
- [ ] Notificatie (Teams/Email) met samenvatting & link
- [ ] Pilot + validatie
- [ ] Task 4.2.7 (AI) — AI‑samenvatting genereren van diffs
- [ ] Task 4.2.8 (AI) — Validatie op volledigheid

#### User Story — US4.3 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt beoordeeld op volledigheid, structuur en leesbaarheid.

**Taken**
- [ ] Definieer AI‑reviewcriteria
- [ ] Bouw pipeline‑step die docs naar AI stuurt (Azure OpenAI)
- [ ] Markeer failures/waarschuwingen
- [ ] Log en archiveer reviewrapporten
- [ ] Handleiding voor teams: hoe AI‑review te interpreteren

#### User Story — US4.4 Als ontwikkelaar wil ik dat AI aangeeft welke documentatie mogelijk moet worden bijgewerkt na code‑wijzigingen, zodat docs up‑to‑date blijven.

**Taken**
- [ ] Bepaal mapping code → docs (impactregels)
- [ ] Pipeline‑step: verzamel diffs per PR/merge
- [ ] AI‑analyse: welke docs zijn potentieel impacted?
- [ ] Maak een “outdated warning” comment op PR
- [ ] Monitor & fine‑tune regels

---

### Feature — Feature 5. Adoptie & Migratie van Bestaande Repositories naar de Nieuwe Documentatiestandaard — _New_

Beschrijving
Deze feature richt zich op de uitrol, adoptie en migratie van de nieuwe documentatiestandaard — inclusief /docs‑structuur, templates, versiebeheer‑richtlijnen en CI/CD‑publicatieprocessen — naar bestaande repositories binnen de organisatie.
We brengen de impact per project in kaart, bepalen migratiestappen en tooling, en begeleiden teams in de adoptie. Daarnaast zetten we AI‑ondersteuning in (M365 Copilot, VS Code Copilot Agent, Visual Studio Copilot Agent en Azure OpenAI) om inconsistenties te detecteren, documenten te vergelijken, en migratievoorstellen te genereren.
Het resultaat van deze feature is dat de nieuwe documentatie‑architectuur uniform, breed gedragen en operationeel is in bestaande codebases.
Business Value
Snelle adoptie van documentatiestandaarden over alle projecten
Lagere migratie‑kosten door AI‑ondersteuning en geautomatiseerde checks
Minder inconsistenties tussen oude en nieuwe documentatie
Hogere documentatiekwaliteit door uniforme templates en structuur
Teams worden ontzorgd, waardoor migratie geen blokkerende factor wordt
Platform‑agnostisch, dus bruikbaar ongeacht documentatieplatform
Acceptance Criteria
Functioneel
 Een impactanalyse per repository is uitgevoerd
 Een migratieplan met duidelijke stappen is opgesteld
 Minstens één repository is succesvol als pilot gemigreerd
 De nieuwe /docs‑structuur, templates en CI/CD‑flow zijn toegepast op de pilot
 Migratiehandleiding (stappenplan) is gepubliceerd
 Tijdens migratie wordt gecontroleerd op inconsistenties en verouderde documentatie
Niet‑functioneel
 Migratieproces is herhaalbaar en bruikbaar voor alle teams
 Migratie introduceert geen breaking changes voor lopende projecten
 Teams worden ondersteund met heldere instructies en voorbeelden
 AI‑analyses blijven privacyvriendelijk binnen het Microsoft‑ecosysteem
AI‑specifiek
 AI kan verschillen detecteren tussen oude en nieuwe documentatie per repository
 AI kan voorstellen genereren voor het migreren van documenten
 AI kan inconsistenties signaleren (verouderde secties, dubbele inhoud, verkeerde structuur)
 Copilot kan helpen bij herschrijven van legacy‑documentatie
 Azure OpenAI kan in CI/CD een migratie‑review genereren

**User Stories**

#### User Story — US5.1 Als platformteam wil ik inzicht in welke aanpassingen nodig zijn voor bestaande repositories, zodat we een correcte migratieplanning kunnen maken.

**Taken**
- [ ] Inventariseer alle repositories binnen scope
- [ ] Analyseer huidige documentatiestructuur per repository
- [ ] Breng ontbrekende of afwijkende documentatie in kaart
- [ ] Controleer CI/CD‑impact
- [ ] Maak impactrapport per repository
- [ ] Bespreek resultaten met stakeholders
- [ ] Task 5.1.7 (AI) — AI‑analyse: consistentie oude vs. nieuwe structuur
- [ ] Task 5.1.8 (AI) — AI‑detectie: ontbrekende documentatietypes

#### User Story — US5.2 Als ontwikkelteam wil ik een duidelijk migratieplan, zodat ik weet welke stappen nodig zijn om de nieuwe documentatiestandaard te gebruiken.

**Taken**
- [ ] Definieer stappenplan voor migratie
- [ ] Maak adoptiestrategie (per team/per project)
- [ ] Maak migratiechecklist voor developers
- [ ] Schrijf migratiehandleiding (Markdown)
- [ ] Publiceer handleiding in centrale docs‑repo
- [ ] Task 5.2.6 (AI) — Genereer migratieadviezen per repository via Copilot
- [ ] Task 5.2.7 (AI) — Verbeter migratiehandleiding met M365 Copilot
- [ ] Task 5.2.8 (AI) — Ontwikkel prompts voor AI‑ondersteunde migratie (“Rewrite this legacy doc using the new template”)

#### User Story — US5.3 Als platformteam wil ik de nieuwe standaard testen op een pilot repository, zodat we zeker weten dat de aanpak werkt voordat we dit breder uitrollen.

**Taken**
- [ ] Selecteer 1–2 pilot repositories
- [ ] Pas /docs‑structuur toe op pilot
- [ ] Migreer legacy documentatie naar nieuwe templates
- [ ] Implementeer CI/CD publicatieflow (Feature 4)
- [ ] Test volledige pipeline: validate → AI review → publish
- [ ] Verzamel feedback van pilot teams
- [ ] Verwerk bevindingen en verbeter standaarden
- [ ] Task 5.3.8 (AI) — Laat AI documentatie reviewen op structuur & volledigheid
- [ ] Task 5.3.9 (AI) — AI‑led rewrite: herschrijf legacy documentation in nieuwe template

#### User Story — US5.4 Als platformteam wil ik AI gebruiken om inconsistenties te detecteren en migratievoorstellen te genereren, zodat migratie sneller en nauwkeuriger wordt.

**Taken**
- [ ] Koppel AI aan documentatie‑diffs
- [ ] Laat AI inconsistenties detecteren
- [ ] Genereer migratievoorstellen per document
- [ ] Laat AI highlighten welke documenten outdated zijn
- [ ] Bouw voorbeeld migratieadviesrapport
- [ ] Task 5.4.6 (AI) — Proof of concept: “AI Migratie Review” pipeline‑step (Azure OpenAI)
- [ ] Task 5.4.7 (AI) — Copilot vergelijkingsprompt (“Compare legacy doc with new template”) (Azure OpenAI)

---

### Feature — Feature 6. AI‑Ondersteuning voor Schrijven, Verbeteren en Valideren van Documentatie — _New_

Beschrijving
Deze feature richt zich op het operationeel inzetten van AI in de documentatielifecycle: tijdens het schrijven in de IDE (VS Code Copilot agent, Visual Studio Insider Copilot), bij het bewerken en verbeteren van tekst (M365 Copilot), en in CI/CD‑pijplijnen (Azure OpenAI) voor kwaliteitsreview, samenvattingen en detectie van verouderde documentatie op basis van code‑diffs.
We leveren:
Promptbibliotheek voor developers en schrijvers (IDE + M365 Copilot).
AI‑review checklist voor kwaliteit (structuur, toon, metadata, volledigheid).
Pipeline‑steps die AI aanroepen voor review en release notes samenvatting.
Richtlijnen voor veilig en effectief gebruik van AI (privacy, governance, “AI ondersteunt, vervangt niet”).
Resultaat: Teams kunnen structureel, veilig en effectief AI inzetten om documentatie sneller, consistenter en kwalitatiever te maken en te houden.
Business Value
Hogere snelheid bij het schrijven en updaten van documentatie.
Constante kwaliteit door AI‑gestuurde controles en suggesties.
Minder handwerk voor release notes en samenvattingen.
Snellere probleemdetectie (ontbrekende secties, inconsistenties, verouderde content).
Betere gebruikerservaring door duidelijke, actuele en consistente documentatie.
Herhaalbaar & schaalbaar door standaard prompts, checklists en pipeline‑integraties.
✅ Acceptance Criteria
Functioneel
 Promptbibliotheek is beschikbaar voor IDE‑agents (VS Code/Visual Studio) en M365 Copilot (templates, herschrijven, samenvatten, metadata).
 AI‑review checklist is opgesteld (structuur/volledigheid, front‑matter/metadata, leesbaarheid/consistentie, broken links).
 Pipeline‑integraties zijn beschreven en als referentie‑implementatie beschikbaar (Azure OpenAI hooks).
 Richtlijnen voor AI‑gebruik (do’s & don’ts, privacy, governance, RACI‑koppeling) zijn gepubliceerd.
 Voorbeeldcases (demo’s) tonen AI‑gebruik in IDE en pipeline.
Niet‑functioneel
 AI‑oplossingen draaien binnen het Microsoft‑ecosysteem en zijn privacy‑bewust.
 AI‑output is reviewbaar en niet bindend (menselijke goedkeuring vereist).
 Integraties zijn herhaalbaar en versiebeheerbaar (centrale repo).
 De invoering veroorzaakt geen vertraging die groter is dan 2 minuten per pipeline run.
AI‑specifiek
 Copilot‑prompts dekken schrijven, herschrijven, structureren, metadata en samenvatten.
 Azure OpenAI kan documentatie reviewen en release notes samenvatten vanuit commit/PR‑diffs.
 Detectie van mogelijk verouderde documentatie op basis van code‑wijzigingen is beschreven en gedemonstreerd.
 Quality gates kunnen waarschuwingen/blokkades geven op basis van AI‑review (configurabel).

**User Stories**

#### User Story — US6.1 Als ontwikkelaar wil ik AI‑ondersteuning in mijn IDE, zodat ik sneller documentatie kan schrijven, docstrings/XML‑docs kan genereren en secties kan aanvullen.

**Taken**
- [ ] Inventariseer AI‑use‑cases in IDE (docstrings, README‑secties, inline uitleg, voorbeeldcode uitleg).
- [ ] Configureer Copilot agents (VS Code & Visual Studio Insider) voor documentatie‑prompts.
- [ ] Maak prompts voor docstrings/XML‑docs (samenvatten van methoden, parameters, exceptions).
- [ ] Voorbeeldworkflow: “van code naar docstring naar /docs‑sectie”.
- [ ] Demo en handleiding voor developers.

#### User Story — US6.2 Als documentatieschrijver wil ik M365 Copilot gebruiken om teksten te herschrijven en te verbeteren, zodat documentatie consistent, leesbaar en volgens richtlijnen is.

**Taken**
- [ ] Definieer kwaliteitscriteria (toon, stijl, consistentie, terminologie, toegankelijkheid).
- [ ] M365 Copilot prompts voor herschrijven/vereenvoudigen/structureren.
- [ ] Voorbeeldcases: herschrijf een architectuursectie; verbeter changelog; harmoniseer README.
- [ ] Reviewproces: menselijke goedkeuring blijft nodig (governance).
- [ ] Publiceer “Copilot schrijf‑ en stijlrichtlijnen

#### User Story — US6.3 Als architect wil ik dat AI complexe configuratie‑ en architectuurbestanden samenvat in begrijpelijke documentatie, zodat kennis snel overdraagbaar is.

**Taken**
- [ ] Identificeer bronbestanden (IaC, pipelines, configs, manifests).
- [ ] Ontwikkel prompts: “Vat deze configuratie samen voor /docs/architecture/”.
- [ ] Plaats samenvattingen in juiste template‑secties (Feature 3).
- [ ] Validatie door architecten (correctheid en jargon).
- [ ] Library met voorbeeldsamenvattingen in centrale repo.

#### User Story — Us6.4 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt gecontroleerd op structuur, volledigheid en metadata.

**Taken**
- [ ] Definieer AI‑reviewchecklist (structuur, front‑matter, links, volledigheid, taal).
- [ ] Pipeline step die docs aan Azure OpenAI aanbiedt + ontvangt reviewrapport.
- [ ] Quality gates: waarschuwing vs. blokkade (configurabel per repo).
- [ ] Logging/archivering van reviewrapporten (traceability).
- [ ] Handleiding voor teams: hoe reviewresultaten te interpreteren en verwerken.

#### User Story — US6.5 Als ontwikkelaar wil ik dat AI documentatie markeert als mogelijk verouderd bij code‑wijzigingen, zodat we tijdig updates doen.

**Taken**
- [ ] Mappingregels code → docs (controllers ↔ /docs/api, infra ↔ /docs/architecture).
- [ ] Pipeline step: verzamel diffs en vorm context voor AI.
- [ ] AI‑analyse: lijst van mogelijk impacted docs + confidence.
- [ ] PR‑comment met waarschuwingen en advies (owners taggen).
- [ ] Fine‑tuning van impactregels op basis van feedback.

#### User Story — US6.6 Als platformteam wil ik een centrale promptbibliotheek en richtlijnen, zodat AI consistent, veilig en effectief wordt ingezet.

**Taken**
- [ ] Promptbibliotheek opzetten (IDE + M365 Copilot + pipeline).
- [ ] Categorieën: schrijven, herschrijven, structureren, metadata, samenvatting, validatie.
- [ ] Voorbeeldprompts per documenttype (API, architectuur, changelog, README).
- [ ] Publiceer richtlijnen (do’s & don’ts, privacy, governance, RACI‑koppeling).
- [ ] Training/demo voor teams (best practices).

---

