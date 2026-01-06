# Azure DevOps Backlog (Export)

_Generated from `Documentatie - Epics.csv` on 2026-01-06._

## Table of Contents

- [Epic 4550: Epic: Uniforme Documentatie en Geautomatiseerde Publicatieworkflow](#epic-4550-epic-uniforme-documentatie-en-geautomatiseerde-publicatieworkflow)
  - [Feature 4575: Feature 1. Analyse & Ontwerp Documentatiestandaard](#feature-4575-feature-1-analyse-and-ontwerp-documentatiestandaard)
    - [User Story 4578: US1.1 Als documentatiearchitect wil ik inzicht in bestaande documentatievormen, zodat we een goed fundament kunnen ontwerpen.](#user-story-4578-us11-als-documentatiearchitect-wil-ik-inzicht-in-bestaande-documentatievormen-zodat-we-een-goed-fundament-kunnen-ontwerpen)
      - [Task 4604: Task 1.1.1 — Inventariseer bestaande documentatiestructuren per repository](#task-4604-task-111-inventariseer-bestaande-documentatiestructuren-per-repository)
      - [Task 4605: Task 1.1.2 — Analyseer huidige publicatieprocessen](#task-4605-task-112-analyseer-huidige-publicatieprocessen)
      - [Task 4606: Task 1.1.3 — Maak een overzicht van gebruikte templates en praktijken](#task-4606-task-113-maak-een-overzicht-van-gebruikte-templates-en-praktijken)
      - [Task 4607: Task 1.1.4 — Identificeer inconsistenties en knelpunten](#task-4607-task-114-identificeer-inconsistenties-en-knelpunten)
      - [Task 4608: Task 1.1.5 — Compileer inventarisatierapport voor stakeholders](#task-4608-task-115-compileer-inventarisatierapport-voor-stakeholders)
    - [User Story 4579: US1.2 Als documentatiegebruiker wil ik dat documenttypes en doelgroepen helder zijn, zodat ik weet waar welke informatie hoort.](#user-story-4579-us12-als-documentatiegebruiker-wil-ik-dat-documenttypes-en-doelgroepen-helder-zijn-zodat-ik-weet-waar-welke-informatie-hoort)
      - [Task 4609: Task 1.2.1 — Bepaal verplichte en optionele documenttypes](#task-4609-task-121-bepaal-verplichte-en-optionele-documenttypes)
      - [Task 4610: Task 1.2.2 — Definieer doelgroepen per documenttype](#task-4610-task-122-definieer-doelgroepen-per-documenttype)
      - [Task 4611: Task 1.2.3 — Maak matrix documenttype → doelgroep → locatie](#task-4611-task-123-maak-matrix-documenttype-doelgroep-locatie)
      - [Task 4612: Task 1.2.4 — Beschrijf minimale inhoud per documenttype](#task-4612-task-124-beschrijf-minimale-inhoud-per-documenttype)
      - [Task 4613: Task 1.2.5 — Leg richtlijnen vast voor toegankelijkheid en taalgebruik](#task-4613-task-125-leg-richtlijnen-vast-voor-toegankelijkheid-en-taalgebruik)
    - [User Story 4580: US1.3 Als platformteam wil ik eigenaarschap per documenttype gedefinieerd hebben, zodat onderhoud gewaarborgd is.](#user-story-4580-us13-als-platformteam-wil-ik-eigenaarschap-per-documenttype-gedefinieerd-hebben-zodat-onderhoud-gewaarborgd-is)
      - [Task 4614: Task 1.3.1 — Identificeer rollen per documenttype](#task-4614-task-131-identificeer-rollen-per-documenttype)
      - [Task 4615: Task 1.3.2 — Maak een RACI-model (Responsible/Accountable/Consulted/Informed)](#task-4615-task-132-maak-een-raci-model-responsibleaccountableconsultedinformed)
      - [Task 4616: Task 1.3.3 — Leg document lifecycle regels vast](#task-4616-task-133-leg-document-lifecycle-regels-vast)
      - [Task 4617: Task 1.3.4 — Valideer eigenaarschap met teams](#task-4617-task-134-valideer-eigenaarschap-met-teams)
      - [Task 4618: Task 1.3.5 — Documenteer governance in de blauwdruk](#task-4618-task-135-documenteer-governance-in-de-blauwdruk)
    - [User Story 4581: US1.4 Als documentatiearchitect wil ik weten waar AI waarde kan toevoegen, zodat we AI bewust en effectief inzetten.](#user-story-4581-us14-als-documentatiearchitect-wil-ik-weten-waar-ai-waarde-kan-toevoegen-zodat-we-ai-bewust-en-effectief-inzetten)
      - [Task 4619: Task 1.4.1 — Analyseer AI-mogelijkheden in VS Code Copilot, Visual Studio Copilot en M365 Copilot](#task-4619-task-141-analyseer-ai-mogelijkheden-in-vs-code-copilot-visual-studio-copilot-en-m365-copilot)
      - [Task 4620: Task 1.4.2 — Inventariseer taken waar AI het meeste waarde levert](#task-4620-task-142-inventariseer-taken-waar-ai-het-meeste-waarde-levert)
      - [Task 4621: Task 1.4.3 — Definieer AI‑kwaliteitscriteria](#task-4621-task-143-definieer-aikwaliteitscriteria)
      - [Task 4622: Task 1.4.4 — Ontwikkel een AI-inzetmatrix](#task-4622-task-144-ontwikkel-een-ai-inzetmatrix)
      - [Task 4623: Task 1.4.5 — Schrijf een set standaard prompts](#task-4623-task-145-schrijf-een-set-standaard-prompts)
      - [Task 4624: Task 1.4.6 — Schrijf PoC‑beschrijving voor AI in CI/CD](#task-4624-task-146-schrijf-pocbeschrijving-voor-ai-in-cicd)
  - [Feature 4576: Feature 2. Uniforme /docs Structuur & Richtlijnen](#feature-4576-feature-2-uniforme-docs-structuur-and-richtlijnen)
    - [User Story 4582: US2.1 Als ontwikkelaar wil ik een uniforme /docs structuur, zodat alle projecten hetzelfde format gebruiken.](#user-story-4582-us21-als-ontwikkelaar-wil-ik-een-uniforme-docs-structuur-zodat-alle-projecten-hetzelfde-format-gebruiken)
      - [Task 4625: Task 2.1.1 — Ontwerp top‑niveaumappen van de /docs‑structuur](#task-4625-task-211-ontwerp-topniveaumappen-van-de-docsstructuur)
      - [Task 4626: Task 2.1.2 — Definieer verplichte bestanden per map](#task-4626-task-212-definieer-verplichte-bestanden-per-map)
      - [Task 4627: Task 2.1.3 — Schrijf richtlijnen voor bestandsopbouw (hoofdstukken / secties)](#task-4627-task-213-schrijf-richtlijnen-voor-bestandsopbouw-hoofdstukken-secties)
      - [Task 4628: Task 2.1.4 — Definieer naamgevingsconventies](#task-4628-task-214-definieer-naamgevingsconventies)
      - [Task 4629: Task 2.1.5 — Maak navigatierichtlijnen (TOC, index.md, cross-links)](#task-4629-task-215-maak-navigatierichtlijnen-toc-indexmd-cross-links)
      - [Task 4630: Task 2.1.6 — Bouw een referentie-implementatie](#task-4630-task-216-bouw-een-referentie-implementatie)
      - [Task 4631: Task 2.1.7 — Valideer structuur bij 2 pilotteams](#task-4631-task-217-valideer-structuur-bij-2-pilotteams)
    - [User Story 4583: US2.2 Als team wil ik richtlijnen voor versiebeheer, zodat documentatie consistent wordt beheerd.](#user-story-4583-us22-als-team-wil-ik-richtlijnen-voor-versiebeheer-zodat-documentatie-consistent-wordt-beheerd)
      - [Task 4632: Task 2.2.1 — Bepaal versiebeheerstrategie voor documentatie](#task-4632-task-221-bepaal-versiebeheerstrategie-voor-documentatie)
      - [Task 4633: Task 2.2.2 — Definieer structuur voor releases in /docs/release](#task-4633-task-222-definieer-structuur-voor-releases-in-docsrelease)
      - [Task 4634: Task 2.2.3 — Maak changelog‑conventies](#task-4634-task-223-maak-changelogconventies)
      - [Task 4635: Task 2.2.4 — Richtlijnen: wanneer moet documentatie worden bijgewerkt?](#task-4635-task-224-richtlijnen-wanneer-moet-documentatie-worden-bijgewerkt)
      - [Task 4636: Task 2.2.5 — Documenteer richtlijnen in een centrale plek](#task-4636-task-225-documenteer-richtlijnen-in-een-centrale-plek)
      - [Task 4637: Task 2.2.6 — Stem versiebeheer af met DevOps releaseprocessen](#task-4637-task-226-stem-versiebeheer-af-met-devops-releaseprocessen)
      - [Task 4638: Task 2.2.7 — Validatie met stakeholders](#task-4638-task-227-validatie-met-stakeholders)
    - [User Story 4584: US2.3 Als ontwikkelaar wil ik AI die mij helpt ontbrekende onderdelen te detecteren, zodat documentatie volledig blijft.](#user-story-4584-us23-als-ontwikkelaar-wil-ik-ai-die-mij-helpt-ontbrekende-onderdelen-te-detecteren-zodat-documentatie-volledig-blijft)
      - [Task 4639: Task 2.3.1 (AI) — Maak Copilot-prompts voor structuurcontrole](#task-4639-task-231-ai-maak-copilot-prompts-voor-structuurcontrole)
      - [Task 4640: Task 2.3.2 (AI) — Ontwikkel checklist voor AI‑review](#task-4640-task-232-ai-ontwikkel-checklist-voor-aireview)
      - [Task 4641: Task 2.3.3 (AI) — Bouw voorbeeld AI-reviewrapport](#task-4641-task-233-ai-bouw-voorbeeld-ai-reviewrapport)
      - [Task 4642: Task 2.3.4 (AI) — Prompts ontwikkelen voor metadata-suggesties](#task-4642-task-234-ai-prompts-ontwikkelen-voor-metadata-suggesties)
      - [Task 4643: Task 2.3.5 (AI) — Automatiseer (optioneel) metadata-check](#task-4643-task-235-ai-automatiseer-optioneel-metadata-check)
      - [Task 4644: Task 2.3.6 — Richtlijnen voor gebruik AI in /docs structuren](#task-4644-task-236-richtlijnen-voor-gebruik-ai-in-docs-structuren)
      - [Task 4645: Task 2.3.7 — Documenteer AI-gebruik in standaard documentatieblauwdruk](#task-4645-task-237-documenteer-ai-gebruik-in-standaard-documentatieblauwdruk)
  - [Feature 4577: Feature 3. Standaard Templates voor API‑documentatie, Architectuur, Changelog en README](#feature-4577-feature-3-standaard-templates-voor-apidocumentatie-architectuur-changelog-en-readme)
    - [User Story 4585: US3.1 Als ontwikkelaar wil ik een standaard API‑documentatiesjabloon, zodat API‑informatie altijd consistent en begrijpelijk is voor interne en externe gebruikers](#user-story-4585-us31-als-ontwikkelaar-wil-ik-een-standaard-apidocumentatiesjabloon-zodat-apiinformatie-altijd-consistent-en-begrijpelijk-is-voor-interne-en-externe-gebruikers)
      - [Task 4646: Task 3.1.1 — Analyseer bestaande API‑documentatie binnen de organisatie](#task-4646-task-311-analyseer-bestaande-apidocumentatie-binnen-de-organisatie)
      - [Task 4647: Task 3.1.2 — Definieer verplichte secties](#task-4647-task-312-definieer-verplichte-secties)
      - [Task 4648: Task 3.1.3 — Stem af met architecten en API‑owners](#task-4648-task-313-stem-af-met-architecten-en-apiowners)
      - [Task 4649: Task 3.1.4 — Maak eerste versie van API-template (Markdown + OpenAPI-stijl)](#task-4649-task-314-maak-eerste-versie-van-api-template-markdown-openapi-stijl)
      - [Task 4650: Task 3.1.5 — Bouw voorbeeld-API-documentatie](#task-4650-task-315-bouw-voorbeeld-api-documentatie)
      - [Task 4651: Task 3.1.6 — Laat 2 pilotteams testen](#task-4651-task-316-laat-2-pilotteams-testen)
      - [Task 4652: Task 3.1.7 — Verwerk feedback en finaliseer template](#task-4652-task-317-verwerk-feedback-en-finaliseer-template)
      - [Task 4653: Task 3.1.8 (AI) — Genereer templatevarianten via Copilot](#task-4653-task-318-ai-genereer-templatevarianten-via-copilot)
      - [Task 4654: Task 3.1.9 (AI) — AI‑review voor volledigheid en consistentie](#task-4654-task-319-ai-aireview-voor-volledigheid-en-consistentie)
    - [User Story 4586: US3.2 Als architect wil ik een vaste template voor architectuurdocumentatie, zodat ontwerp, context, diagrammen en technische beslissingen uniform worden beschreven](#user-story-4586-us32-als-architect-wil-ik-een-vaste-template-voor-architectuurdocumentatie-zodat-ontwerp-context-diagrammen-en-technische-beslissingen-uniform-worden-beschreven)
      - [Task 4655: Task 3.2.1 — Verzamel bestaande architectuurdocumenten](#task-4655-task-321-verzamel-bestaande-architectuurdocumenten)
      - [Task 4656: Task 3.2.2 — Definieer vaste secties](#task-4656-task-322-definieer-vaste-secties)
      - [Task 4657: Task 3.2.3 — Stem af met architectengroep](#task-4657-task-323-stem-af-met-architectengroep)
      - [Task 4658: Task 3.2.4 — Maak template + diagramplaatsen (mermaid, plantUML of handgetekend)](#task-4658-task-324-maak-template-diagramplaatsen-mermaid-plantuml-of-handgetekend)
      - [Task 4659: Task 3.2.5 — Bouw voorbeeldarchitectuurdocument](#task-4659-task-325-bouw-voorbeeldarchitectuurdocument)
      - [Task 4660: Task 3.2.6 — Pilot met 1–2 projecten](#task-4660-task-326-pilot-met-12-projecten)
      - [Task 4661: Task 3.2.7 — Verwerk feedback + finaliseer](#task-4661-task-327-verwerk-feedback-finaliseer)
      - [Task 4662: Task 3.2.8 (AI) — AI-suggesties voor structuur en terminologie](#task-4662-task-328-ai-ai-suggesties-voor-structuur-en-terminologie)
      - [Task 4663: Task 3.2.9 (AI) — AI‑generatie van voorbeeld diagram-beschrijvingen](#task-4663-task-329-ai-aigeneratie-van-voorbeeld-diagram-beschrijvingen)
    - [User Story 4587: US3.3 Als release manager wil ik een template voor changelogs en release notes, zodat wijzigingen per project georganiseerd en transparant worden vastgelegd.](#user-story-4587-us33-als-release-manager-wil-ik-een-template-voor-changelogs-en-release-notes-zodat-wijzigingen-per-project-georganiseerd-en-transparant-worden-vastgelegd)
      - [Task 4664: Task 3.3.1 — Analyseer huidige changelogs en release-processen](#task-4664-task-331-analyseer-huidige-changelogs-en-release-processen)
      - [Task 4665: Task 3.3.2 — Definieer standaardformat](#task-4665-task-332-definieer-standaardformat)
      - [Task 4666: Task 3.3.3 — Maak template voor changelog.md & releases](#task-4666-task-333-maak-template-voor-changelogmd-and-releases)
      - [Task 4667: Task 3.3.4 — Integreer met versiebeheer-richtlijnen (Feature 2)](#task-4667-task-334-integreer-met-versiebeheer-richtlijnen-feature-2)
      - [Task 4668: Task 3.3.5 — Bouw voorbeeld-changelog voor demo](#task-4668-task-335-bouw-voorbeeld-changelog-voor-demo)
      - [Task 4669: Task 3.3.6 — Validatie door release managers](#task-4669-task-336-validatie-door-release-managers)
      - [Task 4670: Task 3.3.7 — Finaliseer template](#task-4670-task-337-finaliseer-template)
      - [Task 4671: Task 3.3.8 (AI) — Copilot-generatie van voorbeeldchangelogs](#task-4671-task-338-ai-copilot-generatie-van-voorbeeldchangelogs)
      - [Task 4672: Task 3.3.9 (AI) — Ontwikkel prompts voor automatische changelog‑samenvatting](#task-4672-task-339-ai-ontwikkel-prompts-voor-automatische-changelogsamenvatting)
    - [User Story 4588: US3.4 Als ontwikkelaar wil ik een gestandaardiseerde README.md, zodat elk project dezelfde basisinformatie heeft en nieuwe gebruikers snel kunnen starten.](#user-story-4588-us34-als-ontwikkelaar-wil-ik-een-gestandaardiseerde-readmemd-zodat-elk-project-dezelfde-basisinformatie-heeft-en-nieuwe-gebruikers-snel-kunnen-starten)
      - [Task 4673: Task 3.4.1 — Analyseer huidige README’s](#task-4673-task-341-analyseer-huidige-readmes)
      - [Task 4674: Task 3.4.2 — Definieer verplichte secties](#task-4674-task-342-definieer-verplichte-secties)
      - [Task 4675: Task 3.4.3 — Maak template README.md](#task-4675-task-343-maak-template-readmemd)
      - [Task 4676: Task 3.4.4 — Bouw voorbeeld README](#task-4676-task-344-bouw-voorbeeld-readme)
      - [Task 4677: Task 3.4.5 — Validatie met 2 teams](#task-4677-task-345-validatie-met-2-teams)
      - [Task 4678: Task 3.4.6 — Finaliseer template](#task-4678-task-346-finaliseer-template)
      - [Task 4679: Task 3.4.7 (AI) — Copilot herschrijft voor helderheid en consistentie](#task-4679-task-347-ai-copilot-herschrijft-voor-helderheid-en-consistentie)
      - [Task 4680: Task 3.4.8 (AI) — Maak generieke voorbeeldtekst via M365 Copilot](#task-4680-task-348-ai-maak-generieke-voorbeeldtekst-via-m365-copilot)
    - [User Story 4589: US3.5 Als team wil ik AI‑ondersteuning voor het genereren en verbeteren van templates en voorbeeldinhoud, zodat documentatie sneller en consistenter kan worden gemaakt.](#user-story-4589-us35-als-team-wil-ik-aiondersteuning-voor-het-genereren-en-verbeteren-van-templates-en-voorbeeldinhoud-zodat-documentatie-sneller-en-consistenter-kan-worden-gemaakt)
      - [Task 4681: Task 3.5.1 — Maak AI‑promptbibliotheek voor templategeneratie](#task-4681-task-351-maak-aipromptbibliotheek-voor-templategeneratie)
      - [Task 4682: Task 3.5.2 — Definieer AI‑kwaliteitscriteria voor templates](#task-4682-task-352-definieer-aikwaliteitscriteria-voor-templates)
      - [Task 4683: ask 3.5.3 — Genereer voorbeeldcontent voor elk template via AI](#task-4683-ask-353-genereer-voorbeeldcontent-voor-elk-template-via-ai)
      - [Task 4684: Task 3.5.4 — Ontwikkel AI‑checklist voor template validatie](#task-4684-task-354-ontwikkel-aichecklist-voor-template-validatie)
      - [Task 4685: Task 3.5.5 — Documenteer hoe teams AI moeten gebruiken bij templates](#task-4685-task-355-documenteer-hoe-teams-ai-moeten-gebruiken-bij-templates)
  - [Feature 4590: Feature 4. Geautomatiseerde validatie, publicatie en release notes voor documentatie (CI/CD)](#feature-4590-feature-4-geautomatiseerde-validatie-publicatie-en-release-notes-voor-documentatie-cicd)
    - [User Story 4591: Us4.1 Als ontwikkelaar wil ik dat documentatie automatisch wordt gepubliceerd na een merge of release, zodat informatie altijd actueel en centraal beschikbaar is.](#user-story-4591-us41-als-ontwikkelaar-wil-ik-dat-documentatie-automatisch-wordt-gepubliceerd-na-een-merge-of-release-zodat-informatie-altijd-actueel-en-centraal-beschikbaar-is)
      - [Task 4686: Task 4.1.1 — Ontwerp publicatiestroom (triggers & stappen)](#task-4686-task-411-ontwerp-publicatiestroom-triggers-and-stappen)
      - [Task 4687: Task 4.1.2 — Bouw Azure DevOps pipeline template voor documentatiepublicatie](#task-4687-task-412-bouw-azure-devops-pipeline-template-voor-documentatiepublicatie)
      - [Task 4688: Task 4.1.3 — Implementeer publicatie naar Azure DevOps Wiki](#task-4688-task-413-implementeer-publicatie-naar-azure-devops-wiki)
      - [Task 4689: Task 4.1.4 — Implementeer publicatie naar alternatieve platforms](#task-4689-task-414-implementeer-publicatie-naar-alternatieve-platforms)
      - [Task 4690: Task 4.1.5 — Configuratiehandleiding per repository](#task-4690-task-415-configuratiehandleiding-per-repository)
      - [Task 4691: Task 4.1.6 — Referentie‑implementatie + pilot](#task-4691-task-416-referentieimplementatie-pilot)
    - [User Story 4592: US4.2 Als release manager wil ik dat release notes automatisch worden gegenereerd en gepubliceerd, zodat wijzigingen duidelijk en consistent worden vastgelegd.](#user-story-4592-us42-als-release-manager-wil-ik-dat-release-notes-automatisch-worden-gegenereerd-en-gepubliceerd-zodat-wijzigingen-duidelijk-en-consistent-worden-vastgelegd)
      - [Task 4692: Task 4.2.1 — Specificeer release note format (Aligned met Feature 3 & 2)](#task-4692-task-421-specificeer-release-note-format-aligned-met-feature-3-and-2)
      - [Task 4693: Task 4.2.2 — Bouw script om diffs te verzamelen (commits/PR’s/tags)](#task-4693-task-422-bouw-script-om-diffs-te-verzamelen-commitsprstags)
      - [Task 4694: Task 4.2.3 — Genereer release notes en voeg toe aan repo](#task-4694-task-423-genereer-release-notes-en-voeg-toe-aan-repo)
      - [Task 4695: Task 4.2.4 — Publiceer release notes automatisch naar platform(en)](#task-4695-task-424-publiceer-release-notes-automatisch-naar-platformen)
      - [Task 4696: Task 4.2.5 — Notificatie (Teams/Email) met samenvatting & link](#task-4696-task-425-notificatie-teamsemail-met-samenvatting-and-link)
      - [Task 4697: Task 4.2.6 — Pilot + validatie](#task-4697-task-426-pilot-validatie)
      - [Task 4698: Task 4.2.7 (AI) — AI‑samenvatting genereren van diffs](#task-4698-task-427-ai-aisamenvatting-genereren-van-diffs)
      - [Task 4699: Task 4.2.8 (AI) — Validatie op volledigheid](#task-4699-task-428-ai-validatie-op-volledigheid)
    - [User Story 4593: US4.3 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt beoordeeld op volledigheid, structuur en leesbaarheid.](#user-story-4593-us43-als-team-wil-ik-aireviews-in-de-pipeline-zodat-documentatie-automatisch-wordt-beoordeeld-op-volledigheid-structuur-en-leesbaarheid)
      - [Task 4700: Task 4.3.1 — Definieer AI‑reviewcriteria](#task-4700-task-431-definieer-aireviewcriteria)
      - [Task 4701: Task 4.3.2 — Bouw pipeline‑step die docs naar AI stuurt (Azure OpenAI)](#task-4701-task-432-bouw-pipelinestep-die-docs-naar-ai-stuurt-azure-openai)
      - [Task 4702: Task 4.3.3 — Markeer failures/waarschuwingen](#task-4702-task-433-markeer-failureswaarschuwingen)
      - [Task 4703: Task 4.3.4 — Log en archiveer reviewrapporten](#task-4703-task-434-log-en-archiveer-reviewrapporten)
      - [Task 4704: Task 4.3.5 — Handleiding voor teams: hoe AI‑review te interpreteren](#task-4704-task-435-handleiding-voor-teams-hoe-aireview-te-interpreteren)
    - [User Story 4594: US4.4 Als ontwikkelaar wil ik dat AI aangeeft welke documentatie mogelijk moet worden bijgewerkt na code‑wijzigingen, zodat docs up‑to‑date blijven.](#user-story-4594-us44-als-ontwikkelaar-wil-ik-dat-ai-aangeeft-welke-documentatie-mogelijk-moet-worden-bijgewerkt-na-codewijzigingen-zodat-docs-uptodate-blijven)
      - [Task 4705: Task 4.4.1 — Bepaal mapping code → docs (impactregels)](#task-4705-task-441-bepaal-mapping-code-docs-impactregels)
      - [Task 4706: Task 4.4.2 — Pipeline‑step: verzamel diffs per PR/merge](#task-4706-task-442-pipelinestep-verzamel-diffs-per-prmerge)
      - [Task 4707: Task 4.4.3 — AI‑analyse: welke docs zijn potentieel impacted?](#task-4707-task-443-aianalyse-welke-docs-zijn-potentieel-impacted)
      - [Task 4708: Task 4.4.4 — Maak een “outdated warning” comment op PR](#task-4708-task-444-maak-een-outdated-warning-comment-op-pr)
      - [Task 4709: Task 4.4.5 — Monitor & fine‑tune regels](#task-4709-task-445-monitor-and-finetune-regels)
  - [Feature 4595: Feature 5. Adoptie & Migratie van Bestaande Repositories naar de Nieuwe Documentatiestandaard](#feature-4595-feature-5-adoptie-and-migratie-van-bestaande-repositories-naar-de-nieuwe-documentatiestandaard)
    - [User Story 4596: US5.1 Als platformteam wil ik inzicht in welke aanpassingen nodig zijn voor bestaande repositories, zodat we een correcte migratieplanning kunnen maken.](#user-story-4596-us51-als-platformteam-wil-ik-inzicht-in-welke-aanpassingen-nodig-zijn-voor-bestaande-repositories-zodat-we-een-correcte-migratieplanning-kunnen-maken)
      - [Task 4711: Task 5.1.1 — Inventariseer alle repositories binnen scope](#task-4711-task-511-inventariseer-alle-repositories-binnen-scope)
      - [Task 4712: Task 5.1.2 — Analyseer huidige documentatiestructuur per repository](#task-4712-task-512-analyseer-huidige-documentatiestructuur-per-repository)
      - [Task 4713: Task 5.1.3 — Breng ontbrekende of afwijkende documentatie in kaart](#task-4713-task-513-breng-ontbrekende-of-afwijkende-documentatie-in-kaart)
      - [Task 4714: Task 5.1.4 — Controleer CI/CD‑impact](#task-4714-task-514-controleer-cicdimpact)
      - [Task 4715: Task 5.1.5 — Maak impactrapport per repository](#task-4715-task-515-maak-impactrapport-per-repository)
      - [Task 4716: Task 5.1.6 — Bespreek resultaten met stakeholders](#task-4716-task-516-bespreek-resultaten-met-stakeholders)
      - [Task 4717: Task 5.1.7 (AI) — AI‑analyse: consistentie oude vs. nieuwe structuur](#task-4717-task-517-ai-aianalyse-consistentie-oude-vs-nieuwe-structuur)
      - [Task 4718: Task 5.1.8 (AI) — AI‑detectie: ontbrekende documentatietypes](#task-4718-task-518-ai-aidetectie-ontbrekende-documentatietypes)
    - [User Story 4597: US5.2 Als ontwikkelteam wil ik een duidelijk migratieplan, zodat ik weet welke stappen nodig zijn om de nieuwe documentatiestandaard te gebruiken.](#user-story-4597-us52-als-ontwikkelteam-wil-ik-een-duidelijk-migratieplan-zodat-ik-weet-welke-stappen-nodig-zijn-om-de-nieuwe-documentatiestandaard-te-gebruiken)
      - [Task 4719: Task 5.2.1 — Definieer stappenplan voor migratie](#task-4719-task-521-definieer-stappenplan-voor-migratie)
      - [Task 4720: Task 5.2.2 — Maak adoptiestrategie (per team/per project)](#task-4720-task-522-maak-adoptiestrategie-per-teamper-project)
      - [Task 4721: Task 5.2.3 — Maak migratiechecklist voor developers](#task-4721-task-523-maak-migratiechecklist-voor-developers)
      - [Task 4722: Task 5.2.4 — Schrijf migratiehandleiding (Markdown)](#task-4722-task-524-schrijf-migratiehandleiding-markdown)
      - [Task 4723: Task 5.2.5 — Publiceer handleiding in centrale docs‑repo](#task-4723-task-525-publiceer-handleiding-in-centrale-docsrepo)
      - [Task 4724: Task 5.2.6 (AI) — Genereer migratieadviezen per repository via Copilot](#task-4724-task-526-ai-genereer-migratieadviezen-per-repository-via-copilot)
      - [Task 4725: Task 5.2.7 (AI) — Verbeter migratiehandleiding met M365 Copilot](#task-4725-task-527-ai-verbeter-migratiehandleiding-met-m365-copilot)
      - [Task 4726: Task 5.2.8 (AI) — Ontwikkel prompts voor AI‑ondersteunde migratie (“Rewrite this legacy doc using the new template”)](#task-4726-task-528-ai-ontwikkel-prompts-voor-aiondersteunde-migratie-rewrite-this-legacy-doc-using-the-new-template)
    - [User Story 4598: US5.3 Als platformteam wil ik de nieuwe standaard testen op een pilot repository, zodat we zeker weten dat de aanpak werkt voordat we dit breder uitrollen.](#user-story-4598-us53-als-platformteam-wil-ik-de-nieuwe-standaard-testen-op-een-pilot-repository-zodat-we-zeker-weten-dat-de-aanpak-werkt-voordat-we-dit-breder-uitrollen)
      - [Task 4727: Task 5.3.1 — Selecteer 1–2 pilot repositories](#task-4727-task-531-selecteer-12-pilot-repositories)
      - [Task 4728: Task 5.3.2 — Pas /docs‑structuur toe op pilot](#task-4728-task-532-pas-docsstructuur-toe-op-pilot)
      - [Task 4729: Task 5.3.3 — Migreer legacy documentatie naar nieuwe templates](#task-4729-task-533-migreer-legacy-documentatie-naar-nieuwe-templates)
      - [Task 4730: Task 5.3.4 — Implementeer CI/CD publicatieflow (Feature 4)](#task-4730-task-534-implementeer-cicd-publicatieflow-feature-4)
      - [Task 4731: Task 5.3.5 — Test volledige pipeline: validate → AI review → publish](#task-4731-task-535-test-volledige-pipeline-validate-ai-review-publish)
      - [Task 4732: Task 5.3.6 — Verzamel feedback van pilot teams](#task-4732-task-536-verzamel-feedback-van-pilot-teams)
      - [Task 4733: Task 5.3.7 — Verwerk bevindingen en verbeter standaarden](#task-4733-task-537-verwerk-bevindingen-en-verbeter-standaarden)
      - [Task 4734: Task 5.3.8 (AI) — Laat AI documentatie reviewen op structuur & volledigheid](#task-4734-task-538-ai-laat-ai-documentatie-reviewen-op-structuur-and-volledigheid)
      - [Task 4735: Task 5.3.9 (AI) — AI‑led rewrite: herschrijf legacy documentation in nieuwe template](#task-4735-task-539-ai-ailed-rewrite-herschrijf-legacy-documentation-in-nieuwe-template)
    - [User Story 4710: US5.4 Als platformteam wil ik AI gebruiken om inconsistenties te detecteren en migratievoorstellen te genereren, zodat migratie sneller en nauwkeuriger wordt.](#user-story-4710-us54-als-platformteam-wil-ik-ai-gebruiken-om-inconsistenties-te-detecteren-en-migratievoorstellen-te-genereren-zodat-migratie-sneller-en-nauwkeuriger-wordt)
      - [Task 4736: Task 5.4.1 — Koppel AI aan documentatie‑diffs](#task-4736-task-541-koppel-ai-aan-documentatiediffs)
      - [Task 4737: Task 5.4.2 — Laat AI inconsistenties detecteren](#task-4737-task-542-laat-ai-inconsistenties-detecteren)
      - [Task 4738: Task 5.4.3 — Genereer migratievoorstellen per document](#task-4738-task-543-genereer-migratievoorstellen-per-document)
      - [Task 4739: Task 5.4.4 — Laat AI highlighten welke documenten outdated zijn](#task-4739-task-544-laat-ai-highlighten-welke-documenten-outdated-zijn)
      - [Task 4740: Task 5.4.5 — Bouw voorbeeld migratieadviesrapport](#task-4740-task-545-bouw-voorbeeld-migratieadviesrapport)
      - [Task 4741: Task 5.4.6 (AI) — Proof of concept: “AI Migratie Review” pipeline‑step (Azure OpenAI)](#task-4741-task-546-ai-proof-of-concept-ai-migratie-review-pipelinestep-azure-openai)
      - [Task 4742: Task 5.4.7 (AI) — Copilot vergelijkingsprompt (“Compare legacy doc with new template”) (Azure OpenAI)](#task-4742-task-547-ai-copilot-vergelijkingsprompt-compare-legacy-doc-with-new-template-azure-openai)
  - [Feature 4599: Feature 6. AI‑Ondersteuning voor Schrijven, Verbeteren en Valideren van Documentatie](#feature-4599-feature-6-aiondersteuning-voor-schrijven-verbeteren-en-valideren-van-documentatie)
    - [User Story 4600: US6.1 Als ontwikkelaar wil ik AI‑ondersteuning in mijn IDE, zodat ik sneller documentatie kan schrijven, docstrings/XML‑docs kan genereren en secties kan aanvullen.](#user-story-4600-us61-als-ontwikkelaar-wil-ik-aiondersteuning-in-mijn-ide-zodat-ik-sneller-documentatie-kan-schrijven-docstringsxmldocs-kan-genereren-en-secties-kan-aanvullen)
      - [Task 4743: Task 6.1.1 — Inventariseer AI‑use‑cases in IDE (docstrings, README‑secties, inline uitleg, voorbeeldcode uitleg).](#task-4743-task-611-inventariseer-aiusecases-in-ide-docstrings-readmesecties-inline-uitleg-voorbeeldcode-uitleg)
      - [Task 4744: Task 6.1.2 — Configureer Copilot agents (VS Code & Visual Studio Insider) voor documentatie‑prompts.](#task-4744-task-612-configureer-copilot-agents-vs-code-and-visual-studio-insider-voor-documentatieprompts)
      - [Task 4745: Task 6.1.3 — Maak prompts voor docstrings/XML‑docs (samenvatten van methoden, parameters, exceptions).](#task-4745-task-613-maak-prompts-voor-docstringsxmldocs-samenvatten-van-methoden-parameters-exceptions)
      - [Task 4746: Task 6.1.4 — Voorbeeldworkflow: “van code naar docstring naar /docs‑sectie”.](#task-4746-task-614-voorbeeldworkflow-van-code-naar-docstring-naar-docssectie)
      - [Task 4747: Task 6.1.5 — Demo en handleiding voor developers.](#task-4747-task-615-demo-en-handleiding-voor-developers)
    - [User Story 4601: US6.2 Als documentatieschrijver wil ik M365 Copilot gebruiken om teksten te herschrijven en te verbeteren, zodat documentatie consistent, leesbaar en volgens richtlijnen is.](#user-story-4601-us62-als-documentatieschrijver-wil-ik-m365-copilot-gebruiken-om-teksten-te-herschrijven-en-te-verbeteren-zodat-documentatie-consistent-leesbaar-en-volgens-richtlijnen-is)
      - [Task 4748: Task 6.2.1 — Definieer kwaliteitscriteria (toon, stijl, consistentie, terminologie, toegankelijkheid).](#task-4748-task-621-definieer-kwaliteitscriteria-toon-stijl-consistentie-terminologie-toegankelijkheid)
      - [Task 4749: Task 6.2.2 — M365 Copilot prompts voor herschrijven/vereenvoudigen/structureren.](#task-4749-task-622-m365-copilot-prompts-voor-herschrijvenvereenvoudigenstructureren)
      - [Task 4750: Task 6.2.3 — Voorbeeldcases: herschrijf een architectuursectie; verbeter changelog; harmoniseer README.](#task-4750-task-623-voorbeeldcases-herschrijf-een-architectuursectie-verbeter-changelog-harmoniseer-readme)
      - [Task 4751: Task 6.2.4 — Reviewproces: menselijke goedkeuring blijft nodig (governance).](#task-4751-task-624-reviewproces-menselijke-goedkeuring-blijft-nodig-governance)
      - [Task 4752: Task 6.2.5 — Publiceer “Copilot schrijf‑ en stijlrichtlijnen](#task-4752-task-625-publiceer-copilot-schrijf-en-stijlrichtlijnen)
    - [User Story 4602: US6.3 Als architect wil ik dat AI complexe configuratie‑ en architectuurbestanden samenvat in begrijpelijke documentatie, zodat kennis snel overdraagbaar is.](#user-story-4602-us63-als-architect-wil-ik-dat-ai-complexe-configuratie-en-architectuurbestanden-samenvat-in-begrijpelijke-documentatie-zodat-kennis-snel-overdraagbaar-is)
      - [Task 4753: Task 6.3.1 — Identificeer bronbestanden (IaC, pipelines, configs, manifests).](#task-4753-task-631-identificeer-bronbestanden-iac-pipelines-configs-manifests)
      - [Task 4754: Task 6.3.2 — Ontwikkel prompts: “Vat deze configuratie samen voor /docs/architecture/”.](#task-4754-task-632-ontwikkel-prompts-vat-deze-configuratie-samen-voor-docsarchitecture)
      - [Task 4755: Task 6.3.3 — Plaats samenvattingen in juiste template‑secties (Feature 3).](#task-4755-task-633-plaats-samenvattingen-in-juiste-templatesecties-feature-3)
      - [Task 4756: Task 6.3.4 — Validatie door architecten (correctheid en jargon).](#task-4756-task-634-validatie-door-architecten-correctheid-en-jargon)
      - [Task 4757: Task 6.3.5 — Library met voorbeeldsamenvattingen in centrale repo.](#task-4757-task-635-library-met-voorbeeldsamenvattingen-in-centrale-repo)
    - [User Story 4603: Us6.4 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt gecontroleerd op structuur, volledigheid en metadata.](#user-story-4603-us64-als-team-wil-ik-aireviews-in-de-pipeline-zodat-documentatie-automatisch-wordt-gecontroleerd-op-structuur-volledigheid-en-metadata)
      - [Task 4758: Task 6.4.1 — Definieer AI‑reviewchecklist (structuur, front‑matter, links, volledigheid, taal).](#task-4758-task-641-definieer-aireviewchecklist-structuur-frontmatter-links-volledigheid-taal)
      - [Task 4759: Task 6.4.2 — Pipeline step die docs aan Azure OpenAI aanbiedt + ontvangt reviewrapport.](#task-4759-task-642-pipeline-step-die-docs-aan-azure-openai-aanbiedt-ontvangt-reviewrapport)
      - [Task 4760: Task 6.4.3 — Quality gates: waarschuwing vs. blokkade (configurabel per repo).](#task-4760-task-643-quality-gates-waarschuwing-vs-blokkade-configurabel-per-repo)
      - [Task 4761: Task 6.4.4 — Logging/archivering van reviewrapporten (traceability).](#task-4761-task-644-loggingarchivering-van-reviewrapporten-traceability)
      - [Task 4762: Task 6.4.5 — Handleiding voor teams: hoe reviewresultaten te interpreteren en verwerken.](#task-4762-task-645-handleiding-voor-teams-hoe-reviewresultaten-te-interpreteren-en-verwerken)
    - [User Story 4763: US6.5 Als ontwikkelaar wil ik dat AI documentatie markeert als mogelijk verouderd bij code‑wijzigingen, zodat we tijdig updates doen.](#user-story-4763-us65-als-ontwikkelaar-wil-ik-dat-ai-documentatie-markeert-als-mogelijk-verouderd-bij-codewijzigingen-zodat-we-tijdig-updates-doen)
      - [Task 4765: Task 6.5.1 — Mappingregels code → docs (controllers ↔ /docs/api, infra ↔ /docs/architecture).](#task-4765-task-651-mappingregels-code-docs-controllers-docsapi-infra-docsarchitecture)
      - [Task 4766: Task 6.5.2 — Pipeline step: verzamel diffs en vorm context voor AI.](#task-4766-task-652-pipeline-step-verzamel-diffs-en-vorm-context-voor-ai)
      - [Task 4767: Task 6.5.3 — AI‑analyse: lijst van mogelijk impacted docs + confidence.](#task-4767-task-653-aianalyse-lijst-van-mogelijk-impacted-docs-confidence)
      - [Task 4768: Task 6.5.4 — PR‑comment met waarschuwingen en advies (owners taggen).](#task-4768-task-654-prcomment-met-waarschuwingen-en-advies-owners-taggen)
      - [Task 4769: Task 6.5.5 — Fine‑tuning van impactregels op basis van feedback.](#task-4769-task-655-finetuning-van-impactregels-op-basis-van-feedback)
    - [User Story 4764: US6.6 Als platformteam wil ik een centrale promptbibliotheek en richtlijnen, zodat AI consistent, veilig en effectief wordt ingezet.](#user-story-4764-us66-als-platformteam-wil-ik-een-centrale-promptbibliotheek-en-richtlijnen-zodat-ai-consistent-veilig-en-effectief-wordt-ingezet)
      - [Task 4770: Task 6.6.1 — Promptbibliotheek opzetten (IDE + M365 Copilot + pipeline).](#task-4770-task-661-promptbibliotheek-opzetten-ide-m365-copilot-pipeline)
      - [Task 4771: Task 6.6.2 — Categorieën: schrijven, herschrijven, structureren, metadata, samenvatting, validatie.](#task-4771-task-662-categorien-schrijven-herschrijven-structureren-metadata-samenvatting-validatie)
      - [Task 4772: Task 6.6.3 — Voorbeeldprompts per documenttype (API, architectuur, changelog, README).](#task-4772-task-663-voorbeeldprompts-per-documenttype-api-architectuur-changelog-readme)
      - [Task 4773: Task 6.6.4 — Publiceer richtlijnen (do’s & don’ts, privacy, governance, RACI‑koppeling).](#task-4773-task-664-publiceer-richtlijnen-dos-and-donts-privacy-governance-racikoppeling)
      - [Task 4774: Task 6.6.5 — Training/demo voor teams (best practices).](#task-4774-task-665-trainingdemo-voor-teams-best-practices)

---

<a id="epic-4550-epic-uniforme-documentatie-en-geautomatiseerde-publicatieworkflow"></a>
## Epic 4550: Epic: Uniforme Documentatie en Geautomatiseerde Publicatieworkflow

- **State:** New
- **Work item ID:** 4550

**Description**

<div><div style="font-family:'Segoe UI';"> </div><div><p style="font-family:&quot;Segoe UI&quot;;"> </p> </div><div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Om de kwaliteit, vindbaarheid en consistentie van technische documentatie te verbeteren, willen we een centrale, uniforme documentatiestructuur introduceren, inclusief standaardtemplates en een geautomatiseerd publicatieproces. Dit stelt alle ontwikkelaars en documentatiegebruikers in staat om altijd te werken met actuele en betrouwbare informatie over API’s, architectuur, wijzigingen en releases. </p><p>Daarnaast zetten we AI‑ondersteuning in via M365 Copilot, de VS Code Copilot agent en de Visual Studio Insider Copilot agent om documentatie te genereren, te verbeteren, op kwaliteit te beoordelen en mogelijke veroudering vroegtijdig te signaleren. Hierdoor versnellen we het schrijven en onderhouden van documentatie en verhogen we de consistentie tussen teams. </p><hr><h3><strong>Business Value</strong> </h3><ul><li>Consistente en professionele documentatie </li><li>Minder handmatig onderhoud voor ontwikkelaars en documentatieschrijvers </li><li>Snellere onboarding van nieuwe teamleden én externe partners </li><li>Hogere ontwikkelsnelheid door snelle vindbaarheid van actuele informatie </li><li>Minder risico op verouderde, incomplete of dubbele documentatie </li><li>Verbeterde gebruikerservaring voor interne en externe eindgebruikers door duidelijke, betrouwbare en toegankelijke documentatie </li><li>Eindgebruikers kunnen sneller antwoorden vinden zonder afhankelijk te zijn van ontwikkelaars of support </li><li>Gebruikers beschikken altijd over actuele informatie, wat de adoptie en het correct gebruik van API’s en systemen verbetert </li> </ul> </div><br> </div>

<a id="feature-4575-feature-1-analyse-and-ontwerp-documentatiestandaard"></a>
### Feature 4575: Feature 1. Analyse & Ontwerp Documentatiestandaard

- **State:** New
- **Work item ID:** 4575

**Description**

<div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Deze feature richt zich op het <strong>in kaart brengen</strong>, <strong>definiëren</strong> en <strong>ontwerpen</strong> van een organisatiebrede documentatiestandaard. We inventariseren bestaande documentatiestructuren, leggen documenttypes en doelgroepen vast, definiëren eigenaarschap, en ontwerpen de <strong>doelarchitectuur</strong> voor documentatie (standaard <code>/docs</code>-structuur, templates, versiebeheer, en publicatieprincipes). </p><p>Daarnaast bepalen we <strong>waar en hoe AI</strong> (M365 Copilot, VS Code Copilot Agent, Visual Studio Insider Copilot en Azure OpenAI) wordt ingezet binnen de documentatie‑lifecycle—bij het genereren, verbeteren, valideren en actueel houden van documentatie. </p><p><strong>Resultaat van deze feature:</strong> een <strong>goedgekeurde blauwdruk</strong> (principes, structuur, templatescope, eigenaarschap, AI‑gebruikspatronen) die de basis vormt voor implementatie in volgende features. </p><h3><strong>Business Value</strong> </h3><ul><li>Een <strong>heldere en gedragen standaard</strong> voorkomt wildgroei en versnippering. </li><li><strong>Snellere implementatie</strong> in latere features dankzij duidelijke kaders en scope. </li><li><strong>Duidelijke eigenaarschap</strong> voorkomt verouderde documentatie en onduidelijkheden. </li><li><strong>Consistente gebruikerservaring</strong> voor interne en externe eindgebruikers. </li><li><strong>AI‑bewuste inrichting</strong> verhoogt kwaliteit en snelheid, zonder afhankelijk te zijn van ad‑hoc inzet. </li> </ul> </div><div style="font-family:'Segoe UI';"><h2>✅ <strong>Acceptance Criteria</strong> </h2><h3><strong>Functioneel</strong> </h3><input type=checkbox disabled=""> Een <strong>inventarisatierapport</strong> van huidige documentatiestructuren, tooling en publicatievormen per repository is opgesteld en gedeeld.<br><input type=checkbox disabled=""> <strong>Documenttypes</strong> (API, architectuur, changelog/release notes, README, ADR’s, handleidingen) en <strong>doelgroepen</strong> (intern/extern) zijn gedefinieerd en gedocumenteerd.<br><input type=checkbox disabled=""> <strong>Eigenaarschap per documenttype</strong> (roles: API owner, architect, release manager, tech writer) is vastgelegd en geaccepteerd door stakeholders.<br><input type=checkbox disabled=""> Een <strong>target documentatie‑architectuur</strong> is ontworpen: principes, <code>/docs</code> basismodel, versiebeheer‑richtlijnen, metadata/tags, en publicatiekanalen (DevOps Wiki en/of andere repos/portals).<br><input type=checkbox disabled=""> <strong>AI‑gebruikspatronen</strong> zijn beschreven: waar Copilot/AI wordt ingezet (templategeneratie, kwaliteitsreview, release notes, outdated detection) en hoe (IDE vs. pipeline).<br><input type=checkbox disabled=""> De <strong>blauwdruk</strong> (design document) is <strong>goedgekeurd</strong> door het platformteam en ten minste 2 vertegenwoordigers van ontwikkelteams.<br><h3><strong>Niet‑functioneel</strong> </h3><input type=checkbox disabled=""> De standaard volgt <strong>Microsoft‑conventies</strong> (Markdown, OpenAPI) en interne schrijf- en toegankelijkheidsrichtlijnen.<br><input type=checkbox disabled=""> De standaard is <strong>platform‑agnostisch</strong>: toepasbaar voor Azure DevOps Wiki <strong>en/of</strong> andere documentatieplatformen.<br><input type=checkbox disabled=""> De blauwdruk is <strong>versiebeheerbaar</strong> (opgenomen in centrale repo) en <strong>herhaalbaar</strong> toepasbaar voor alle projecten.<br><input type=checkbox disabled=""> AI‑inzet wordt <strong>privacy‑bewust</strong> en binnen het <strong>Microsoft‑ecosysteem</strong> beschreven (M365 Copilot, Azure OpenAI, IDE‑agents).<br><h3><strong>AI‑specifiek</strong> </h3><input type=checkbox disabled=""> Een <strong>AI‑inzetmatrix</strong> definieert per documenttype en fase welke AI‑agent wordt gebruikt (VS Code Copilot, Visual Studio Insider Copilot, M365 Copilot, Azure OpenAI).<br><input type=checkbox disabled=""> <strong>AI‑kwaliteitscriteria</strong> zijn vastgelegd (structuur, toon, volledigheid, consistentie, metadata).<br><input type=checkbox disabled=""> Voorbeeld <strong>prompts</strong> voor Copilot zijn opgesteld (templategeneratie, herschrijven, samenvatten, ontbrekende secties, tag/metadata).<br><input type=checkbox disabled=""> Een <strong>proof‑of‑concept</strong> beschrijft hoe een pipeline AI kan aanroepen voor documentatie‑review (zonder directe implementatie in deze feature). </div><br><br>

<a id="user-story-4578-us11-als-documentatiearchitect-wil-ik-inzicht-in-bestaande-documentatievormen-zodat-we-een-goed-fundament-kunnen-ontwerpen"></a>
#### User Story 4578: US1.1 Als documentatiearchitect wil ik inzicht in bestaande documentatievormen, zodat we een goed fundament kunnen ontwerpen.

- **State:** New
- **Work item ID:** 4578

<a id="task-4604-task-111-inventariseer-bestaande-documentatiestructuren-per-repository"></a>
##### Task 4604: Task 1.1.1 — Inventariseer bestaande documentatiestructuren per repository

- **State:** New
- **Work item ID:** 4604

**Description**

<div><div style="font-family:'Segoe UI';">Breng mappen, bestanden, publicatiekanalen en documentatievormen in kaart. </div><br> </div>

<a id="task-4605-task-112-analyseer-huidige-publicatieprocessen"></a>
##### Task 4605: Task 1.1.2 — Analyseer huidige publicatieprocessen

- **State:** New
- **Work item ID:** 4605

**Description**

<div><div style="font-family:'Segoe UI';">Welke teams publiceren handmatig? Welke automatisch? Naar welke platforms? </div><br> </div>

<a id="task-4606-task-113-maak-een-overzicht-van-gebruikte-templates-en-praktijken"></a>
##### Task 4606: Task 1.1.3 — Maak een overzicht van gebruikte templates en praktijken

- **State:** New
- **Work item ID:** 4606

**Description**

<div><div style="font-family:'Segoe UI';">README’s, API‑docs, architectuurdocs, release notes, ADR’s, etc. </div><br> </div>

<a id="task-4607-task-114-identificeer-inconsistenties-en-knelpunten"></a>
##### Task 4607: Task 1.1.4 — Identificeer inconsistenties en knelpunten

- **State:** New
- **Work item ID:** 4607

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld: ontbrekende structuur, verouderde info, dubbele documentatie. </div><br> </div>

<a id="task-4608-task-115-compileer-inventarisatierapport-voor-stakeholders"></a>
##### Task 4608: Task 1.1.5 — Compileer inventarisatierapport voor stakeholders

- **State:** New
- **Work item ID:** 4608

**Description**

<div><div style="font-family:'Segoe UI';">Geeft basis voor ontwerp van de nieuwe standaard. </div><br> </div>

<a id="user-story-4579-us12-als-documentatiegebruiker-wil-ik-dat-documenttypes-en-doelgroepen-helder-zijn-zodat-ik-weet-waar-welke-informatie-hoort"></a>
#### User Story 4579: US1.2 Als documentatiegebruiker wil ik dat documenttypes en doelgroepen helder zijn, zodat ik weet waar welke informatie hoort.

- **State:** New
- **Work item ID:** 4579

<a id="task-4609-task-121-bepaal-verplichte-en-optionele-documenttypes"></a>
##### Task 4609: Task 1.2.1 — Bepaal verplichte en optionele documenttypes

- **State:** New
- **Work item ID:** 4609

**Description**

<div><div style="font-family:'Segoe UI';">API docs, architectuur, changelogs, handleidingen, configuratie, security, etc. </div><br> </div>

<a id="task-4610-task-122-definieer-doelgroepen-per-documenttype"></a>
##### Task 4610: Task 1.2.2 — Definieer doelgroepen per documenttype

- **State:** New
- **Work item ID:** 4610

**Description**

<div><div style="font-family:'Segoe UI';">Intern (devs, beheer, architecten), extern (partners, eindgebruikers). </div><br> </div>

<a id="task-4611-task-123-maak-matrix-documenttype-doelgroep-locatie"></a>
##### Task 4611: Task 1.2.3 — Maak matrix documenttype → doelgroep → locatie

- **State:** New
- **Work item ID:** 4611

**Description**

<div><div style="font-family:'Segoe UI';"><p>Bijvoorbeeld: </p><ul><li>API_docs → extern/intern → DevOps Wiki of API Portal </li><li>Architectuur → intern → <code>/docs/architecture</code> </li> </ul> </div><br> </div>

<a id="task-4612-task-124-beschrijf-minimale-inhoud-per-documenttype"></a>
##### Task 4612: Task 1.2.4 — Beschrijf minimale inhoud per documenttype

- **State:** New
- **Work item ID:** 4612

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld voor API-doc: endpoints, parameters, voorbeelden, errors. </div><br> </div>

<a id="task-4613-task-125-leg-richtlijnen-vast-voor-toegankelijkheid-en-taalgebruik"></a>
##### Task 4613: Task 1.2.5 — Leg richtlijnen vast voor toegankelijkheid en taalgebruik

- **State:** New
- **Work item ID:** 4613

**Description**

<div><div style="font-family:'Segoe UI';">Consistentie in schrijfstijl, toon, structuur. </div><br> </div>

<a id="user-story-4580-us13-als-platformteam-wil-ik-eigenaarschap-per-documenttype-gedefinieerd-hebben-zodat-onderhoud-gewaarborgd-is"></a>
#### User Story 4580: US1.3 Als platformteam wil ik eigenaarschap per documenttype gedefinieerd hebben, zodat onderhoud gewaarborgd is.

- **State:** New
- **Work item ID:** 4580

<a id="task-4614-task-131-identificeer-rollen-per-documenttype"></a>
##### Task 4614: Task 1.3.1 — Identificeer rollen per documenttype

- **State:** New
- **Work item ID:** 4614

**Description**

<div><div style="font-family:'Segoe UI';">API-owner, architect, release manager, developer, product owner. </div><br> </div>

<a id="task-4615-task-132-maak-een-raci-model-responsibleaccountableconsultedinformed"></a>
##### Task 4615: Task 1.3.2 — Maak een RACI-model (Responsible/Accountable/Consulted/Informed)

- **State:** New
- **Work item ID:** 4615

**Description**

<div style="font-family:'Segoe UI';">Per document: wie maakt? wie reviewt? wie keurt goed? wie onderhoudt? </div><div style="font-family:'Segoe UI';"><br> </div><div style="font-family:'Segoe UI';"><div style="font-family:'Segoe UI';"><p>Een <strong>RACI‑model</strong> is een eenvoudige maar krachtige methode om <strong>eigenaarschap en verantwoordelijkheden</strong> te verdelen.<br><br> </p><ul><li><strong>Wie maakt de documentatie?</strong> </li><li><strong>Wie is eindverantwoordelijk?</strong> </li><li><strong>Wie moet geraadpleegd worden?</strong> </li><li><strong>Wie moet geïnformeerd worden?</strong> </li> </ul> </div><div style="font-family:'Segoe UI';"><p><strong>RACI</strong> staat voor: </p><div><table><thead><tr><th style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);">Letter</th><th style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);">Betekenis</th><th style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);">Wat het betekent in praktijk</th></tr></thead><tbody><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>R – Responsible</strong></th><td style="border:1px solid rgb(230, 230, 230);">Uitvoerder </td><td style="border:1px solid rgb(230, 230, 230);">Degene die het werk DOET (maakt, schrijft, wijzigt) </td></tr><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>A – Accountable</strong></th><td style="border:1px solid rgb(230, 230, 230);">Eindverantwoordelijke </td><td style="border:1px solid rgb(230, 230, 230);">Degene die beslist en eindgoedkeuring geeft </td></tr><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>C – Consulted</strong></th><td style="border:1px solid rgb(230, 230, 230);">Te raadplegen </td><td style="border:1px solid rgb(230, 230, 230);">Mensen die input moeten geven of feedback hebben </td></tr><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>I – Informed</strong></th><td style="border:1px solid rgb(230, 230, 230);">Te informeren </td><td style="border:1px solid rgb(230, 230, 230);">Mensen die op de hoogte moeten worden gehouden </td></tr></tbody></table> </div><p>Kort samengevat: </p><ul><li><strong>R</strong> = <em>Doer</em> </li><li><strong>A</strong> = <em>Owner</em> </li><li><strong>C</strong> = <em>Advisor</em> </li><li><strong>I</strong> = <em>Geïnformeerde</em> </li> </ul> </div><br> </div><br>

<a id="task-4616-task-133-leg-document-lifecycle-regels-vast"></a>
##### Task 4616: Task 1.3.3 — Leg document lifecycle regels vast

- **State:** New
- **Work item ID:** 4616

**Description**

<div><div style="font-family:'Segoe UI';">Reviewmomenten, update bij wijzigingen, archivering. </div><br> </div>

<a id="task-4617-task-134-valideer-eigenaarschap-met-teams"></a>
##### Task 4617: Task 1.3.4 — Valideer eigenaarschap met teams

- **State:** New
- **Work item ID:** 4617

**Description**

<div><div style="font-family:'Segoe UI';">Stakeholders akkoord? </div><br> </div>

<a id="task-4618-task-135-documenteer-governance-in-de-blauwdruk"></a>
##### Task 4618: Task 1.3.5 — Documenteer governance in de blauwdruk

- **State:** New
- **Work item ID:** 4618

**Description**

<div><div style="font-family:'Segoe UI';">Wordt onderdeel van de standaarden. </div><br> </div>

<a id="user-story-4581-us14-als-documentatiearchitect-wil-ik-weten-waar-ai-waarde-kan-toevoegen-zodat-we-ai-bewust-en-effectief-inzetten"></a>
#### User Story 4581: US1.4 Als documentatiearchitect wil ik weten waar AI waarde kan toevoegen, zodat we AI bewust en effectief inzetten.

- **State:** New
- **Work item ID:** 4581

**Acceptance Criteria**

<div><div style="font-family:'Segoe UI';">&#128204; Een inventarisatie van huidige documentatie<br>
&#128204; Een definitie van documenttypes en doelgroepen<br>
&#128204; Governance en eigenaarschap per documenttype<br>
&#128204; Een AI‑strategie en inzetmatrix<br>
&#128204; Een <strong>complete blauwdruk</strong> voor Feature 2–6 </div><br> </div>

<a id="task-4619-task-141-analyseer-ai-mogelijkheden-in-vs-code-copilot-visual-studio-copilot-en-m365-copilot"></a>
##### Task 4619: Task 1.4.1 — Analyseer AI-mogelijkheden in VS Code Copilot, Visual Studio Copilot en M365 Copilot

- **State:** New
- **Work item ID:** 4619

**Description**

<div><div style="font-family:'Segoe UI';">Welke functies helpen bij documentatie, samenvattingen, validatie? </div><br> </div>

<a id="task-4620-task-142-inventariseer-taken-waar-ai-het-meeste-waarde-levert"></a>
##### Task 4620: Task 1.4.2 — Inventariseer taken waar AI het meeste waarde levert

- **State:** New
- **Work item ID:** 4620

**Description**

<div><div style="font-family:'Segoe UI';"><p>Voorbeelden: </p><ul><li>templategeneratie </li><li>tekstverbeteringen </li><li>samenvattingen </li><li>metadata/tags </li><li>detectie verouderde documentatie </li> </ul> </div><br> </div>

<a id="task-4621-task-143-definieer-aikwaliteitscriteria"></a>
##### Task 4621: Task 1.4.3 — Definieer AI‑kwaliteitscriteria

- **State:** New
- **Work item ID:** 4621

**Description**

<div><div style="font-family:'Segoe UI';">Consistentie, taal, volledigheid, structuur. </div><br> </div>

<a id="task-4622-task-144-ontwikkel-een-ai-inzetmatrix"></a>
##### Task 4622: Task 1.4.4 — Ontwikkel een AI-inzetmatrix

- **State:** New
- **Work item ID:** 4622

**Description**

<div><div style="font-family:'Segoe UI';"><p>Welke AI‑agent gebruiken we waarvoor? </p><ul><li>VS Code → inline suggestions </li><li>Visual Studio → docstrings/XML docs </li><li>M365 Copilot → templateverbeteringen </li><li>Azure OpenAI → pipeline validatie </li> </ul> </div><br> </div>

<a id="task-4623-task-145-schrijf-een-set-standaard-prompts"></a>
##### Task 4623: Task 1.4.5 — Schrijf een set standaard prompts

- **State:** New
- **Work item ID:** 4623

**Description**

<div><div style="font-family:'Segoe UI';">Voor templates, samenvatting, herschrijven, validatie. </div><br> </div>

<a id="task-4624-task-146-schrijf-pocbeschrijving-voor-ai-in-cicd"></a>
##### Task 4624: Task 1.4.6 — Schrijf PoC‑beschrijving voor AI in CI/CD

- **State:** New
- **Work item ID:** 4624

**Description**

<div><div style="font-family:'Segoe UI';">Hoe AI in een pipeline aangeroepen kan worden (nog niet implementeren). </div><br> </div>

<a id="feature-4576-feature-2-uniforme-docs-structuur-and-richtlijnen"></a>
### Feature 4576: Feature 2. Uniforme /docs Structuur & Richtlijnen

- **State:** New
- **Work item ID:** 4576

**Description**

<div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Deze feature realiseert een <strong>standaard en herbruikbare</strong> <code>/docs</code>‑mapstructuur voor alle projecten, inclusief <strong>naamgevingsconventies</strong>, <strong>metadata/tags</strong>, <strong>link‑conventies</strong>, en <strong>richtlijnen voor versiebeheer</strong> (semver, release map, changelog).<br>
Doel is dat elke repository dezelfde basisstructuur hanteert, waardoor documentatie <strong>consistent, vindbaar en onderhoudbaar</strong> wordt. </p><p>De standaard is <strong>platform‑agnostisch</strong>: toepasbaar voor <strong>Azure DevOps Wiki</strong>, <strong>SharePoint</strong>, <strong>Markdown‑portals</strong> of <strong>centrale docs‑repositories</strong>.<br>
AI‑ondersteuning (M365 Copilot, VS Code Copilot agent, Visual Studio Insider Copilot) wordt gebruikt om <strong>ontbrekende secties te signaleren</strong>, <strong>metadata voor te stellen</strong> en <strong>structuurconformiteit</strong> te reviewen. </p><p><strong>Resultaat:</strong> Een <strong>goedgekeurde standaard <code>/docs</code>‑structuur</strong> + <strong>richtlijnen voor versiebeheer</strong> die door alle teams kan worden toegepast. </p><h3><strong>Business Value</strong> </h3><ul><li><strong>Consistentie</strong> in documentatiestructuur over alle projecten → makkelijker zoeken &amp; navigeren. </li><li><strong>Snellere onboarding</strong>: teams herkennen direct waar docs staan en wat verplicht is. </li><li><strong>Onderhoudbaarheid</strong>: standaard indeling en versiebeheer verminderen fouten en veroudering. </li><li><strong>Platform‑flexibiliteit</strong>: bruikbaar op elk documentatieplatform, nu en in de toekomst. </li><li><strong>Kwaliteitsborging</strong>: AI helpt bij het bewaken van structuur, volledigheid en metadata. </li> </ul><h2>✅ Acceptance Criteria </h2><h3><strong>Functioneel</strong> </h3><ul><li><input type=checkbox disabled=""> Er is een <strong>standaard <code>/docs</code>‑structuur</strong> vastgesteld (top‑niveaumappen en verplichte bestanden). </li><li><input type=checkbox disabled=""> <strong>Naamgevingsconventies</strong> en <strong>best practices</strong> (bijv. <code>api/</code>, <code>architecture/</code>, <code>releases/</code>, <code>adr/</code>, <code>guides/</code>, <code>index.md</code>) zijn gedocumenteerd. </li><li><input type=checkbox disabled=""> <strong>Metadata‑richtlijnen</strong> zijn beschikbaar (front‑matter/tags, owners, last‑updated, version). </li><li><input type=checkbox disabled=""> <strong>Link‑conventies</strong> en <strong>navigatie‑richtlijnen</strong> zijn beschreven (relatieve paden, indexpagina’s, TOC). </li><li><input type=checkbox disabled=""> <strong>Versiebeheer‑richtlijnen</strong> voor documentatie zijn gedefinieerd (semver, release folders, changelog). </li><li><input type=checkbox disabled=""> Een <strong>referentie‑implementatie</strong> (voorbeeldrepo of sample in centrale repo) is opgeleverd. </li><li><input type=checkbox disabled=""> Minimaal <strong>2 pilotteams</strong> hebben de structuur gevalideerd en feedback is verwerkt. </li> </ul><h3><strong>Niet‑functioneel</strong> </h3><input type=checkbox disabled=""> Standaard volgt <strong>Microsoft‑conventies</strong> (Markdown/OpenAPI) en interne toegankelijkheidsrichtlijnen.<br><input type=checkbox disabled=""> Structuur is <strong>platform‑agnostisch</strong> en niet afhankelijk van één publicatieplatform.<br><input type=checkbox disabled=""> Richtlijnen zijn <strong>versiebeheerbaar</strong> en centraal gepubliceerd (docs‑as‑code).<br><input type=checkbox disabled=""> Adoptie is <strong>herhaalbaar</strong>: één script of handleiding om structuur toe te passen in nieuwe/bestaande repos.<br><h3><strong>AI‑specifiek</strong> </h3><input type=checkbox disabled=""> AI‑prompts beschikbaar om <strong>ontbrekende secties</strong> te detecteren en <strong>metadata/tags</strong> te suggereren.<br><input type=checkbox disabled=""> Een <strong>AI‑review checklist</strong> (voor IDE agents of pipeline) controleert structuurconformiteit.<br><input type=checkbox disabled=""> Copilot kan <strong>indexpagina’s</strong> en <strong>TOC’s</strong> genereren op basis van bestaande bestanden. </div><br><br>

<a id="user-story-4582-us21-als-ontwikkelaar-wil-ik-een-uniforme-docs-structuur-zodat-alle-projecten-hetzelfde-format-gebruiken"></a>
#### User Story 4582: US2.1 Als ontwikkelaar wil ik een uniforme /docs structuur, zodat alle projecten hetzelfde format gebruiken.

- **State:** New
- **Work item ID:** 4582

**Description**

<div><div style="font-family:'Segoe UI';"><div style="font-family:'Segoe UI';"><b>Wat het oplevert</b> </div><br> </div><div style="font-family:'Segoe UI';">Standaard <code>/docs</code> structuur + navigatie </div><br> </div>

<a id="task-4625-task-211-ontwerp-topniveaumappen-van-de-docsstructuur"></a>
##### Task 4625: Task 2.1.1 — Ontwerp top‑niveaumappen van de /docs‑structuur

- **State:** New
- **Work item ID:** 4625

<a id="task-4626-task-212-definieer-verplichte-bestanden-per-map"></a>
##### Task 4626: Task 2.1.2 — Definieer verplichte bestanden per map

- **State:** New
- **Work item ID:** 4626

**Description**

<div><div style="font-family:'Segoe UI';">Voorbeeld:
<ul><li><code>/api/overview.md</code> </li><li><code>/architecture/solution-overview.md</code> </li><li><code>/releases/changelog.md</code> </li> </ul> </div><br> </div>

<a id="task-4627-task-213-schrijf-richtlijnen-voor-bestandsopbouw-hoofdstukken-secties"></a>
##### Task 4627: Task 2.1.3 — Schrijf richtlijnen voor bestandsopbouw (hoofdstukken / secties)

- **State:** New
- **Work item ID:** 4627

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld: Introductie, Doelgroep, Inhoud, Voorbeelden, Links. </div><br> </div>

<a id="task-4628-task-214-definieer-naamgevingsconventies"></a>
##### Task 4628: Task 2.1.4 — Definieer naamgevingsconventies

- **State:** New
- **Work item ID:** 4628

**Description**

<div><div style="font-family:'Segoe UI';">Bijv.: lowercase, <code>kebab-case.md</code>, datumformat (<code>YYYY-MM-DD</code>) voor ADR’s. </div><br> </div>

<a id="task-4629-task-215-maak-navigatierichtlijnen-toc-indexmd-cross-links"></a>
##### Task 4629: Task 2.1.5 — Maak navigatierichtlijnen (TOC, index.md, cross-links)

- **State:** New
- **Work item ID:** 4629

**Description**

<div><div style="font-family:'Segoe UI';">Relatieve links, index per map, navigatiestructuur. </div><br> </div>

<a id="task-4630-task-216-bouw-een-referentie-implementatie"></a>
##### Task 4630: Task 2.1.6 — Bouw een referentie-implementatie

- **State:** New
- **Work item ID:** 4630

**Description**

<div><div style="font-family:'Segoe UI';">Een voorbeeld <code>/docs</code> map in een sample repository. </div><br> </div>

<a id="task-4631-task-217-valideer-structuur-bij-2-pilotteams"></a>
##### Task 4631: Task 2.1.7 — Valideer structuur bij 2 pilotteams

- **State:** New
- **Work item ID:** 4631

**Description**

<div><div style="font-family:'Segoe UI';">Feedback verzamelen en verwerken. </div><br> </div>

<a id="user-story-4583-us22-als-team-wil-ik-richtlijnen-voor-versiebeheer-zodat-documentatie-consistent-wordt-beheerd"></a>
#### User Story 4583: US2.2 Als team wil ik richtlijnen voor versiebeheer, zodat documentatie consistent wordt beheerd.

- **State:** New
- **Work item ID:** 4583

**Description**

<div><div style="box-sizing:border-box;font-family:&quot;Segoe UI&quot;;"><div style="box-sizing:border-box;"><b style="box-sizing:border-box;">Wat het oplevert</b> </div><br style="box-sizing:border-box;"> </div><div style="box-sizing:border-box;font-family:&quot;Segoe UI&quot;;"><div style="font-family:'Segoe UI';">Richtlijnen voor documentatie-versiebeheer </div> </div><br> </div>

<a id="task-4632-task-221-bepaal-versiebeheerstrategie-voor-documentatie"></a>
##### Task 4632: Task 2.2.1 — Bepaal versiebeheerstrategie voor documentatie

- **State:** New
- **Work item ID:** 4632

<a id="task-4633-task-222-definieer-structuur-voor-releases-in-docsrelease"></a>
##### Task 4633: Task 2.2.2 — Definieer structuur voor releases in /docs/release

- **State:** New
- **Work item ID:** 4633

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld: </div><div style="font-family:'Segoe UI';">&nbsp;
<pre><code>/docs/releases/1.0.0.md
/docs/releases/1.1.0.md</code></pre> </div><br> </div>

<a id="task-4634-task-223-maak-changelogconventies"></a>
##### Task 4634: Task 2.2.3 — Maak changelog‑conventies

- **State:** New
- **Work item ID:** 4634

**Description**

<div style="font-family:'Segoe UI';"><ul><li>Breaking changes </li><li>Added </li><li>Changed </li><li>Fixed </li><li>Deprecated </li> </ul> </div><br>

<a id="task-4635-task-224-richtlijnen-wanneer-moet-documentatie-worden-bijgewerkt"></a>
##### Task 4635: Task 2.2.4 — Richtlijnen: wanneer moet documentatie worden bijgewerkt?

- **State:** New
- **Work item ID:** 4635

**Description**

<div><div style="font-family:'Segoe UI';">Bij merge, feature done, breaking change, API-wijziging. </div><br> </div>

<a id="task-4636-task-225-documenteer-richtlijnen-in-een-centrale-plek"></a>
##### Task 4636: Task 2.2.5 — Documenteer richtlijnen in een centrale plek

- **State:** New
- **Work item ID:** 4636

**Description**

<div><div style="font-family:'Segoe UI';">/docs/guides/versioning-guidelines.md </div><br> </div>

<a id="task-4637-task-226-stem-versiebeheer-af-met-devops-releaseprocessen"></a>
##### Task 4637: Task 2.2.6 — Stem versiebeheer af met DevOps releaseprocessen

- **State:** New
- **Work item ID:** 4637

**Description**

<div><div style="font-family:'Segoe UI';">Release pipelines ↔ documentatie directories. </div><br> </div>

<a id="task-4638-task-227-validatie-met-stakeholders"></a>
##### Task 4638: Task 2.2.7 — Validatie met stakeholders

- **State:** New
- **Work item ID:** 4638

**Description**

<div><div style="font-family:'Segoe UI';">PO, architecten, developers akkoord. </div><br> </div>

<a id="user-story-4584-us23-als-ontwikkelaar-wil-ik-ai-die-mij-helpt-ontbrekende-onderdelen-te-detecteren-zodat-documentatie-volledig-blijft"></a>
#### User Story 4584: US2.3 Als ontwikkelaar wil ik AI die mij helpt ontbrekende onderdelen te detecteren, zodat documentatie volledig blijft.

- **State:** New
- **Work item ID:** 4584

**Description**

<div><b style="box-sizing:border-box;font-family:&quot;Segoe UI&quot;;">Wat het oplevert</b><br><br> </div><div><div style="font-family:'Segoe UI';">AI die helpt structuur &amp; metadata te bewaken </div><br> </div>

<a id="task-4639-task-231-ai-maak-copilot-prompts-voor-structuurcontrole"></a>
##### Task 4639: Task 2.3.1 (AI) — Maak Copilot-prompts voor structuurcontrole

- **State:** New
- **Work item ID:** 4639

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld:
<ul><li>“Controleer of alle verplichte secties aanwezig zijn.” </li><li>“Welke onderdelen ontbreken op basis van het template?” </li> </ul> </div><br> </div>

<a id="task-4640-task-232-ai-ontwikkel-checklist-voor-aireview"></a>
##### Task 4640: Task 2.3.2 (AI) — Ontwikkel checklist voor AI‑review

- **State:** New
- **Work item ID:** 4640

**Description**

<div><div style="font-family:'Segoe UI';"><ul><li>Is metadata aanwezig? </li><li>Zijn verplichte bestanden aanwezig? </li><li>Structuur klopt met standaard? </li> </ul> </div><br> </div>

<a id="task-4641-task-233-ai-bouw-voorbeeld-ai-reviewrapport"></a>
##### Task 4641: Task 2.3.3 (AI) — Bouw voorbeeld AI-reviewrapport

- **State:** New
- **Work item ID:** 4641

**Description**

<div><div style="font-family:'Segoe UI';">Laat Copilot een voorbeeld genereren van een review-output. </div><br> </div>

<a id="task-4642-task-234-ai-prompts-ontwikkelen-voor-metadata-suggesties"></a>
##### Task 4642: Task 2.3.4 (AI) — Prompts ontwikkelen voor metadata-suggesties

- **State:** New
- **Work item ID:** 4642

**Description**

<div><div style="font-family:'Segoe UI';">Copilot genereert automatisch:
<ul><li>title </li><li>description </li><li>tags </li><li>lastUpdated </li><li>owner </li> </ul> </div><br> </div>

<a id="task-4643-task-235-ai-automatiseer-optioneel-metadata-check"></a>
##### Task 4643: Task 2.3.5 (AI) — Automatiseer (optioneel) metadata-check

- **State:** New
- **Work item ID:** 4643

**Description**

<div><div style="font-family:'Segoe UI';">Kijken of verplichte front-matter aanwezig is. </div><br> </div>

<a id="task-4644-task-236-richtlijnen-voor-gebruik-ai-in-docs-structuren"></a>
##### Task 4644: Task 2.3.6 — Richtlijnen voor gebruik AI in /docs structuren

- **State:** New
- **Work item ID:** 4644

**Description**

<div><div style="font-family:'Segoe UI';">Wanneer developers AI gebruiken en wanneer handmatig. </div><br> </div>

<a id="task-4645-task-237-documenteer-ai-gebruik-in-standaard-documentatieblauwdruk"></a>
##### Task 4645: Task 2.3.7 — Documenteer AI-gebruik in standaard documentatieblauwdruk

- **State:** New
- **Work item ID:** 4645

**Description**

<div><div style="font-family:'Segoe UI';">Hoe gebruik je Copilot bij structuurvalidatie? </div><br> </div>

<a id="feature-4577-feature-3-standaard-templates-voor-apidocumentatie-architectuur-changelog-en-readme"></a>
### Feature 4577: Feature 3. Standaard Templates voor API‑documentatie, Architectuur, Changelog en README

- **State:** New
- **Work item ID:** 4577

**Description**

<div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Deze feature levert een <strong>set uniforme templates</strong> op voor alle projectdocumentatie, waaronder API‑documentatie, architectuurdocumentatie, changelogs/release notes en README.md‑bestanden. Deze templates zorgen voor een consistente kwaliteit, een voorspelbare structuur en professionele communicatie naar interne en externe gebruikers. </p><p>De templates volgen <strong>Microsoft‑conventies</strong> (Markdown, OpenAPI‑stijl, architectuurcategorieën) en zijn <strong>platform‑agnostisch</strong>, zodat ze toepasbaar zijn in Azure DevOps Wiki, SharePoint of elk ander documentatieplatform. </p><p>AI‑ondersteuning (VS Code Copilot Agent, Visual Studio Copilot Agent en M365 Copilot) wordt gebruikt om <strong>templatevarianten te genereren</strong>, <strong>secties te verbeteren</strong>, <strong>voorbeeldcontent te maken</strong>, en <strong>kwaliteit te bewaken</strong>. </p><p>Het resultaat is een set <strong>herbruikbare en goedgekeurde templates</strong> die door elk team gebruikt kunnen worden bij nieuwe en bestaande projecten. </p><h3><strong>Business Value</strong> </h3><ul><li><strong>Consistente documentatie</strong> over alle projecten en teams </li><li><strong>Minder inspanning</strong> voor ontwikkelaars door herbruikbare sjablonen </li><li><strong>Minder fouten en ontbrekende informatie</strong> dankzij duidelijke structuur </li><li><strong>Snellere onboarding</strong> doordat documentatie voorspelbaar en herkenbaar is </li><li><strong>Betere gebruikerservaring</strong> voor interne en externe eindgebruikers </li><li><strong>AI‑geoptimaliseerde templates</strong> verhogen kwaliteit en verkleinen de werkdruk </li> </ul><h3><strong>Acceptance Criteria</strong> </h3><h4><strong>Functioneel</strong> </h4><input type=checkbox disabled=""> Er zijn 4 templates gemaakt: <strong>API</strong>, <strong>Architectuur</strong>, <strong>Changelog/Release Notes</strong>, <strong>README.md</strong><br><input type=checkbox disabled=""> Templates bevatten verplichte secties, richtlijnen en voorbeelden<br><input type=checkbox disabled=""> Templates volgen interne richtlijnen + Microsoft Docs‑conventies<br><input type=checkbox disabled=""> Een voorbeeldimplementatie per template is beschikbaar<br><input type=checkbox disabled=""> Templates zijn getest door 2–3 pilotteams<br><input type=checkbox disabled=""> Alle templates bevinden zich in een centrale repository (/docs/templates/)<br><h4><strong>Niet‑functioneel</strong> </h4><input type=checkbox disabled=""> Templates zijn platform‑agnostisch<br><input type=checkbox disabled=""> Templates zijn begrijpelijk, toegankelijk en consistent in stijl<br><input type=checkbox disabled=""> Templates zijn bruikbaar voor M365 Copilot en IDE‑Copilot agents (goed promptable)<br><input type=checkbox disabled=""> Templates zijn versieerbaar en onderhoudbaar<br><h4><strong>AI‑specifiek</strong> </h4><input type=checkbox disabled=""> AI‑prompts zijn ontwikkeld voor templategeneratie en validatie<br><input type=checkbox disabled=""> AI genereert voorbeeldcontent voor elke template<br><input type=checkbox disabled=""> AI kan ontbrekende secties detecteren tijdens schrijven<br><input type=checkbox disabled=""> M365 Copilot kan templates herschrijven voor leesbaarheid<br><input type=checkbox disabled=""> Copilot agents kunnen automatische suggesties geven (secties, voorbeelden, metadata) </div><br><br>

<a id="user-story-4585-us31-als-ontwikkelaar-wil-ik-een-standaard-apidocumentatiesjabloon-zodat-apiinformatie-altijd-consistent-en-begrijpelijk-is-voor-interne-en-externe-gebruikers"></a>
#### User Story 4585: US3.1 Als ontwikkelaar wil ik een standaard API‑documentatiesjabloon, zodat API‑informatie altijd consistent en begrijpelijk is voor interne en externe gebruikers

- **State:** New
- **Work item ID:** 4585

<a id="task-4646-task-311-analyseer-bestaande-apidocumentatie-binnen-de-organisatie"></a>
##### Task 4646: Task 3.1.1 — Analyseer bestaande API‑documentatie binnen de organisatie

- **State:** New
- **Work item ID:** 4646

<a id="task-4647-task-312-definieer-verplichte-secties"></a>
##### Task 4647: Task 3.1.2 — Definieer verplichte secties

- **State:** New
- **Work item ID:** 4647

**Description**

<div><div style="font-family:'Segoe UI';">Voorbeelden:
<ul><li>Overview </li><li>Authentication </li><li>Endpoints </li><li>Parameters </li><li>Examples </li><li>Error handling </li> </ul> </div><br> </div>

<a id="task-4648-task-313-stem-af-met-architecten-en-apiowners"></a>
##### Task 4648: Task 3.1.3 — Stem af met architecten en API‑owners

- **State:** New
- **Work item ID:** 4648

<a id="task-4649-task-314-maak-eerste-versie-van-api-template-markdown-openapi-stijl"></a>
##### Task 4649: Task 3.1.4 — Maak eerste versie van API-template (Markdown + OpenAPI-stijl)

- **State:** New
- **Work item ID:** 4649

<a id="task-4650-task-315-bouw-voorbeeld-api-documentatie"></a>
##### Task 4650: Task 3.1.5 — Bouw voorbeeld-API-documentatie

- **State:** New
- **Work item ID:** 4650

<a id="task-4651-task-316-laat-2-pilotteams-testen"></a>
##### Task 4651: Task 3.1.6 — Laat 2 pilotteams testen

- **State:** New
- **Work item ID:** 4651

<a id="task-4652-task-317-verwerk-feedback-en-finaliseer-template"></a>
##### Task 4652: Task 3.1.7 — Verwerk feedback en finaliseer template

- **State:** New
- **Work item ID:** 4652

<a id="task-4653-task-318-ai-genereer-templatevarianten-via-copilot"></a>
##### Task 4653: Task 3.1.8 (AI) — Genereer templatevarianten via Copilot

- **State:** New
- **Work item ID:** 4653

<a id="task-4654-task-319-ai-aireview-voor-volledigheid-en-consistentie"></a>
##### Task 4654: Task 3.1.9 (AI) — AI‑review voor volledigheid en consistentie

- **State:** New
- **Work item ID:** 4654

<a id="user-story-4586-us32-als-architect-wil-ik-een-vaste-template-voor-architectuurdocumentatie-zodat-ontwerp-context-diagrammen-en-technische-beslissingen-uniform-worden-beschreven"></a>
#### User Story 4586: US3.2 Als architect wil ik een vaste template voor architectuurdocumentatie, zodat ontwerp, context, diagrammen en technische beslissingen uniform worden beschreven

- **State:** New
- **Work item ID:** 4586

<a id="task-4655-task-321-verzamel-bestaande-architectuurdocumenten"></a>
##### Task 4655: Task 3.2.1 — Verzamel bestaande architectuurdocumenten

- **State:** New
- **Work item ID:** 4655

<a id="task-4656-task-322-definieer-vaste-secties"></a>
##### Task 4656: Task 3.2.2 — Definieer vaste secties

- **State:** New
- **Work item ID:** 4656

**Description**

<div><div style="font-family:'Segoe UI';">ijvoorbeeld:
<ul><li>Context </li><li>Solution overview </li><li>Componenten </li><li>Integraties </li><li>Security </li><li>Deployment </li> </ul> </div><br> </div>

<a id="task-4657-task-323-stem-af-met-architectengroep"></a>
##### Task 4657: Task 3.2.3 — Stem af met architectengroep

- **State:** New
- **Work item ID:** 4657

<a id="task-4658-task-324-maak-template-diagramplaatsen-mermaid-plantuml-of-handgetekend"></a>
##### Task 4658: Task 3.2.4 — Maak template + diagramplaatsen (mermaid, plantUML of handgetekend)

- **State:** New
- **Work item ID:** 4658

<a id="task-4659-task-325-bouw-voorbeeldarchitectuurdocument"></a>
##### Task 4659: Task 3.2.5 — Bouw voorbeeldarchitectuurdocument

- **State:** New
- **Work item ID:** 4659

<a id="task-4660-task-326-pilot-met-12-projecten"></a>
##### Task 4660: Task 3.2.6 — Pilot met 1–2 projecten

- **State:** New
- **Work item ID:** 4660

<a id="task-4661-task-327-verwerk-feedback-finaliseer"></a>
##### Task 4661: Task 3.2.7 — Verwerk feedback + finaliseer

- **State:** New
- **Work item ID:** 4661

<a id="task-4662-task-328-ai-ai-suggesties-voor-structuur-en-terminologie"></a>
##### Task 4662: Task 3.2.8 (AI) — AI-suggesties voor structuur en terminologie

- **State:** New
- **Work item ID:** 4662

<a id="task-4663-task-329-ai-aigeneratie-van-voorbeeld-diagram-beschrijvingen"></a>
##### Task 4663: Task 3.2.9 (AI) — AI‑generatie van voorbeeld diagram-beschrijvingen

- **State:** New
- **Work item ID:** 4663

<a id="user-story-4587-us33-als-release-manager-wil-ik-een-template-voor-changelogs-en-release-notes-zodat-wijzigingen-per-project-georganiseerd-en-transparant-worden-vastgelegd"></a>
#### User Story 4587: US3.3 Als release manager wil ik een template voor changelogs en release notes, zodat wijzigingen per project georganiseerd en transparant worden vastgelegd.

- **State:** New
- **Work item ID:** 4587

<a id="task-4664-task-331-analyseer-huidige-changelogs-en-release-processen"></a>
##### Task 4664: Task 3.3.1 — Analyseer huidige changelogs en release-processen

- **State:** New
- **Work item ID:** 4664

<a id="task-4665-task-332-definieer-standaardformat"></a>
##### Task 4665: Task 3.3.2 — Definieer standaardformat

- **State:** New
- **Work item ID:** 4665

**Description**

<div><div style="font-family:'Segoe UI';"><ul><li>Added </li><li>Changed </li><li>Fixed </li><li>Deprecated </li><li>Removed </li> </ul> </div><br> </div>

<a id="task-4666-task-333-maak-template-voor-changelogmd-and-releases"></a>
##### Task 4666: Task 3.3.3 — Maak template voor changelog.md & releases

- **State:** New
- **Work item ID:** 4666

<a id="task-4667-task-334-integreer-met-versiebeheer-richtlijnen-feature-2"></a>
##### Task 4667: Task 3.3.4 — Integreer met versiebeheer-richtlijnen (Feature 2)

- **State:** New
- **Work item ID:** 4667

<a id="task-4668-task-335-bouw-voorbeeld-changelog-voor-demo"></a>
##### Task 4668: Task 3.3.5 — Bouw voorbeeld-changelog voor demo

- **State:** New
- **Work item ID:** 4668

<a id="task-4669-task-336-validatie-door-release-managers"></a>
##### Task 4669: Task 3.3.6 — Validatie door release managers

- **State:** New
- **Work item ID:** 4669

<a id="task-4670-task-337-finaliseer-template"></a>
##### Task 4670: Task 3.3.7 — Finaliseer template

- **State:** New
- **Work item ID:** 4670

<a id="task-4671-task-338-ai-copilot-generatie-van-voorbeeldchangelogs"></a>
##### Task 4671: Task 3.3.8 (AI) — Copilot-generatie van voorbeeldchangelogs

- **State:** New
- **Work item ID:** 4671

<a id="task-4672-task-339-ai-ontwikkel-prompts-voor-automatische-changelogsamenvatting"></a>
##### Task 4672: Task 3.3.9 (AI) — Ontwikkel prompts voor automatische changelog‑samenvatting

- **State:** New
- **Work item ID:** 4672

<a id="user-story-4588-us34-als-ontwikkelaar-wil-ik-een-gestandaardiseerde-readmemd-zodat-elk-project-dezelfde-basisinformatie-heeft-en-nieuwe-gebruikers-snel-kunnen-starten"></a>
#### User Story 4588: US3.4 Als ontwikkelaar wil ik een gestandaardiseerde README.md, zodat elk project dezelfde basisinformatie heeft en nieuwe gebruikers snel kunnen starten.

- **State:** New
- **Work item ID:** 4588

<a id="task-4673-task-341-analyseer-huidige-readmes"></a>
##### Task 4673: Task 3.4.1 — Analyseer huidige README’s

- **State:** New
- **Work item ID:** 4673

<a id="task-4674-task-342-definieer-verplichte-secties"></a>
##### Task 4674: Task 3.4.2 — Definieer verplichte secties

- **State:** New
- **Work item ID:** 4674

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld:
<ul><li>Project summary </li><li>Features </li><li>Installatie </li><li>Usage </li><li>Contributing </li><li>Contact </li> </ul> </div><br> </div>

<a id="task-4675-task-343-maak-template-readmemd"></a>
##### Task 4675: Task 3.4.3 — Maak template README.md

- **State:** New
- **Work item ID:** 4675

<a id="task-4676-task-344-bouw-voorbeeld-readme"></a>
##### Task 4676: Task 3.4.4 — Bouw voorbeeld README

- **State:** New
- **Work item ID:** 4676

<a id="task-4677-task-345-validatie-met-2-teams"></a>
##### Task 4677: Task 3.4.5 — Validatie met 2 teams

- **State:** New
- **Work item ID:** 4677

<a id="task-4678-task-346-finaliseer-template"></a>
##### Task 4678: Task 3.4.6 — Finaliseer template

- **State:** New
- **Work item ID:** 4678

<a id="task-4679-task-347-ai-copilot-herschrijft-voor-helderheid-en-consistentie"></a>
##### Task 4679: Task 3.4.7 (AI) — Copilot herschrijft voor helderheid en consistentie

- **State:** New
- **Work item ID:** 4679

<a id="task-4680-task-348-ai-maak-generieke-voorbeeldtekst-via-m365-copilot"></a>
##### Task 4680: Task 3.4.8 (AI) — Maak generieke voorbeeldtekst via M365 Copilot

- **State:** New
- **Work item ID:** 4680

<a id="user-story-4589-us35-als-team-wil-ik-aiondersteuning-voor-het-genereren-en-verbeteren-van-templates-en-voorbeeldinhoud-zodat-documentatie-sneller-en-consistenter-kan-worden-gemaakt"></a>
#### User Story 4589: US3.5 Als team wil ik AI‑ondersteuning voor het genereren en verbeteren van templates en voorbeeldinhoud, zodat documentatie sneller en consistenter kan worden gemaakt.

- **State:** New
- **Work item ID:** 4589

<a id="task-4681-task-351-maak-aipromptbibliotheek-voor-templategeneratie"></a>
##### Task 4681: Task 3.5.1 — Maak AI‑promptbibliotheek voor templategeneratie

- **State:** New
- **Work item ID:** 4681

<a id="task-4682-task-352-definieer-aikwaliteitscriteria-voor-templates"></a>
##### Task 4682: Task 3.5.2 — Definieer AI‑kwaliteitscriteria voor templates

- **State:** New
- **Work item ID:** 4682

<a id="task-4683-ask-353-genereer-voorbeeldcontent-voor-elk-template-via-ai"></a>
##### Task 4683: ask 3.5.3 — Genereer voorbeeldcontent voor elk template via AI

- **State:** New
- **Work item ID:** 4683

<a id="task-4684-task-354-ontwikkel-aichecklist-voor-template-validatie"></a>
##### Task 4684: Task 3.5.4 — Ontwikkel AI‑checklist voor template validatie

- **State:** New
- **Work item ID:** 4684

<a id="task-4685-task-355-documenteer-hoe-teams-ai-moeten-gebruiken-bij-templates"></a>
##### Task 4685: Task 3.5.5 — Documenteer hoe teams AI moeten gebruiken bij templates

- **State:** New
- **Work item ID:** 4685

<a id="feature-4590-feature-4-geautomatiseerde-validatie-publicatie-en-release-notes-voor-documentatie-cicd"></a>
### Feature 4590: Feature 4. Geautomatiseerde validatie, publicatie en release notes voor documentatie (CI/CD)

- **State:** New
- **Work item ID:** 4590

**Description**

<div style="font-family:'Segoe UI';"><div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Deze feature realiseert een <strong>volledig geautomatiseerde documentatieworkflow</strong> in Azure DevOps: </p><ul><li><strong>Validatie</strong> van documentatie (structuur, verplichte secties, broken links, metadata) </li><li><strong>Publicatie</strong> naar <strong>Azure DevOps Wiki</strong> <strong>en/of</strong> andere gekozen documentatieplatformen (SharePoint, centrale docs‑portal, Markdown‑site) </li><li><strong>Automatische generatie van release notes</strong> op basis van commits/PR’s, gegroepeerd per type wijziging </li><li><strong>AI‑ondersteuning</strong> binnen de pipeline (Azure OpenAI) voor kwaliteitsreview, samenvattingen en detectie van mogelijk verouderde documentatie o.b.v. code‑diffs </li> </ul><p><strong>Resultaat:</strong> één standaard <strong>CI/CD‑publicatieflow</strong> die door alle repositories herbruikbaar is, met <strong>AI‑verrijkte</strong> kwaliteit en release notes. </p><h3><strong>Business Value</strong> </h3><ul><li><strong>Minder handwerk</strong>: publicatie, validatie en release notes gaan automatisch </li><li><strong>Constante kwaliteit</strong>: fouten en ontbrekende onderdelen worden automatisch gedetecteerd </li><li><strong>Snellere releases</strong>: documentatie is direct synchroon met code </li><li><strong>Betere gebruikerservaring</strong>: actuele docs en heldere release notes </li><li><strong>AI‑ondersteuning</strong>: menselijke review blijft, maar met slimme hulp voor snelheid en consistentie </li> </ul><h3>✅ <strong>Acceptance Criteria</strong> </h3><h4><strong>Functioneel</strong> </h4><input type=checkbox disabled=""> Een <strong>standaard Azure DevOps pipeline</strong> is beschikbaar voor documentatie: validatie → publicatie → notificatie<br><input type=checkbox disabled=""> Documentatie wordt <strong>automatisch gepubliceerd</strong> bij merge naar <code>main</code> of bij release tag<br><input type=checkbox disabled=""> <strong>Release notes</strong> worden automatisch gegenereerd en toegevoegd aan <code>README.md</code> of <code>/docs/releases/</code><br><input type=checkbox disabled=""> Validatie omvat: <strong>structuur</strong>, <strong>verplichte secties</strong>, <strong>broken links</strong>, <strong>metadata/front‑matter</strong><br><input type=checkbox disabled=""> Pipeline ondersteunt <strong>Azure DevOps Wiki</strong> en <strong>andere documentatieplatformen</strong> (configurabel)<br><input type=checkbox disabled=""> Er is een <strong>referentie‑implementatie</strong> + handleiding hoe teams deze pipeline adopteren<br><h4><strong>Niet‑functioneel</strong> </h4><input type=checkbox disabled=""> Pipeline draait binnen <strong>&lt; 2 minuten extra</strong> runtime t.o.v. huidige CI/CD<br><input type=checkbox disabled=""> Scripts zijn <strong>herbruikbaar</strong> en <strong>versiebeheerbaar</strong> (centrale repo)<br><input type=checkbox disabled=""> Oplossing werkt voor <strong>nieuwe en bestaande repositories</strong><br><input type=checkbox disabled=""> <strong>Beveiliging en privacy</strong> zijn geborgd (geen data buiten Microsoft‑ecosysteem)<br><h4><strong>AI‑specifiek</strong> </h4><input type=checkbox disabled=""> AI (Azure OpenAI) kan <strong>release note‑samenvattingen</strong> genereren op basis van commit/PR‑diffs<br><input type=checkbox disabled=""> AI kan documentatie <strong>kwaliteitsreviewen</strong> (structuur, ontbrekende secties, leesbaarheid)<br><input type=checkbox disabled=""> AI kan op basis van <strong>code‑differences</strong> documentatie bestempelen als “mogelijk verouderd”<br><input type=checkbox disabled=""> AI‑output is <strong>suggestief</strong> en <strong>reviewbaar</strong> (menselijke goedkeuring blijft vereist) </div> </div><br><br>

<a id="user-story-4591-us41-als-ontwikkelaar-wil-ik-dat-documentatie-automatisch-wordt-gepubliceerd-na-een-merge-of-release-zodat-informatie-altijd-actueel-en-centraal-beschikbaar-is"></a>
#### User Story 4591: Us4.1 Als ontwikkelaar wil ik dat documentatie automatisch wordt gepubliceerd na een merge of release, zodat informatie altijd actueel en centraal beschikbaar is.

- **State:** New
- **Work item ID:** 4591

<a id="task-4686-task-411-ontwerp-publicatiestroom-triggers-and-stappen"></a>
##### Task 4686: Task 4.1.1 — Ontwerp publicatiestroom (triggers & stappen)

- **State:** New
- **Work item ID:** 4686

**Description**

<div><div style="font-family:'Segoe UI';">Trigger: merge naar <code>main</code>, release tag; Stappen: validate → publish → notify. </div><br> </div>

<a id="task-4687-task-412-bouw-azure-devops-pipeline-template-voor-documentatiepublicatie"></a>
##### Task 4687: Task 4.1.2 — Bouw Azure DevOps pipeline template voor documentatiepublicatie

- **State:** New
- **Work item ID:** 4687

**Description**

<div><div style="font-family:'Segoe UI';">BICEP/YAML met herbruikbare stages/jobs/steps. </div><br> </div>

<a id="task-4688-task-413-implementeer-publicatie-naar-azure-devops-wiki"></a>
##### Task 4688: Task 4.1.3 — Implementeer publicatie naar Azure DevOps Wiki

- **State:** New
- **Work item ID:** 4688

**Description**

<div><div style="font-family:'Segoe UI';">Script/REST API of <code>wiki</code>‑repo sync. </div><br> </div>

<a id="task-4689-task-414-implementeer-publicatie-naar-alternatieve-platforms"></a>
##### Task 4689: Task 4.1.4 — Implementeer publicatie naar alternatieve platforms

- **State:** New
- **Work item ID:** 4689

**Description**

<div><div style="font-family:'Segoe UI';">(SharePoint, docs‑portal, Markdown site) via afzonderlijke tasks (configurabel). </div><br> </div>

<a id="task-4690-task-415-configuratiehandleiding-per-repository"></a>
##### Task 4690: Task 4.1.5 — Configuratiehandleiding per repository

- **State:** New
- **Work item ID:** 4690

**Description**

<div><div style="font-family:'Segoe UI';">Hoe teams pipeline en publicatiedoelen instellen. </div><br> </div>

<a id="task-4691-task-416-referentieimplementatie-pilot"></a>
##### Task 4691: Task 4.1.6 — Referentie‑implementatie + pilot

- **State:** New
- **Work item ID:** 4691

**Description**

<div><div style="font-family:'Segoe UI';">Test in 1–2 projecten, verwerk feedback. </div><br> </div>

<a id="user-story-4592-us42-als-release-manager-wil-ik-dat-release-notes-automatisch-worden-gegenereerd-en-gepubliceerd-zodat-wijzigingen-duidelijk-en-consistent-worden-vastgelegd"></a>
#### User Story 4592: US4.2 Als release manager wil ik dat release notes automatisch worden gegenereerd en gepubliceerd, zodat wijzigingen duidelijk en consistent worden vastgelegd.

- **State:** New
- **Work item ID:** 4592

<a id="task-4692-task-421-specificeer-release-note-format-aligned-met-feature-3-and-2"></a>
##### Task 4692: Task 4.2.1 — Specificeer release note format (Aligned met Feature 3 & 2)

- **State:** New
- **Work item ID:** 4692

**Description**

<div><div style="font-family:'Segoe UI';">Secties: Added/Changed/Fixed/Deprecated/Removed, links naar PR’s. </div><br> </div>

<a id="task-4693-task-422-bouw-script-om-diffs-te-verzamelen-commitsprstags"></a>
##### Task 4693: Task 4.2.2 — Bouw script om diffs te verzamelen (commits/PR’s/tags)

- **State:** New
- **Work item ID:** 4693

**Description**

<div><div style="font-family:'Segoe UI';">Output: raw changes per type. </div><br> </div>

<a id="task-4694-task-423-genereer-release-notes-en-voeg-toe-aan-repo"></a>
##### Task 4694: Task 4.2.3 — Genereer release notes en voeg toe aan repo

- **State:** New
- **Work item ID:** 4694

**Description**

<div><div style="font-family:'Segoe UI';">Update <code>README.md</code> (kort) + plaats volledige notes in <code>/docs/releases/</code>. </div><br> </div>

<a id="task-4695-task-424-publiceer-release-notes-automatisch-naar-platformen"></a>
##### Task 4695: Task 4.2.4 — Publiceer release notes automatisch naar platform(en)

- **State:** New
- **Work item ID:** 4695

**Description**

<div><div style="font-family:'Segoe UI';">Als onderdeel van dezelfde pipeline. </div><br> </div>

<a id="task-4696-task-425-notificatie-teamsemail-met-samenvatting-and-link"></a>
##### Task 4696: Task 4.2.5 — Notificatie (Teams/Email) met samenvatting & link

- **State:** New
- **Work item ID:** 4696

**Description**

<div><div style="font-family:'Segoe UI';">Optioneel, via service hook. </div><br> </div>

<a id="task-4697-task-426-pilot-validatie"></a>
##### Task 4697: Task 4.2.6 — Pilot + validatie

- **State:** New
- **Work item ID:** 4697

**Description**

<div><div style="font-family:'Segoe UI';">Check consistentie, leesbaarheid, bruikbaarheid. </div><br> </div>

<a id="task-4698-task-427-ai-aisamenvatting-genereren-van-diffs"></a>
##### Task 4698: Task 4.2.7 (AI) — AI‑samenvatting genereren van diffs

- **State:** New
- **Work item ID:** 4698

**Description**

<div><div style="font-family:'Segoe UI';">Gebruik Azure OpenAI om menselijke tekst te genereren voor release notes. </div><br> </div>

<a id="task-4699-task-428-ai-validatie-op-volledigheid"></a>
##### Task 4699: Task 4.2.8 (AI) — Validatie op volledigheid

- **State:** New
- **Work item ID:** 4699

**Description**

<div><div style="font-family:'Segoe UI';">AI checkt of belangrijke wijzigingen zijn meegenomen. </div><br> </div>

<a id="user-story-4593-us43-als-team-wil-ik-aireviews-in-de-pipeline-zodat-documentatie-automatisch-wordt-beoordeeld-op-volledigheid-structuur-en-leesbaarheid"></a>
#### User Story 4593: US4.3 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt beoordeeld op volledigheid, structuur en leesbaarheid.

- **State:** New
- **Work item ID:** 4593

<a id="task-4700-task-431-definieer-aireviewcriteria"></a>
##### Task 4700: Task 4.3.1 — Definieer AI‑reviewcriteria

- **State:** New
- **Work item ID:** 4700

**Description**

<div><div style="font-family:'Segoe UI';">Structuur, verplichte secties, front‑matter, leesbaarheid, consistentie. </div><br> </div>

<a id="task-4701-task-432-bouw-pipelinestep-die-docs-naar-ai-stuurt-azure-openai"></a>
##### Task 4701: Task 4.3.2 — Bouw pipeline‑step die docs naar AI stuurt (Azure OpenAI)

- **State:** New
- **Work item ID:** 4701

**Description**

<div><div style="font-family:'Segoe UI';">Input: inhoud + checklist; Output: reviewrapport met aanbevelingen. </div><br> </div>

<a id="task-4702-task-433-markeer-failureswaarschuwingen"></a>
##### Task 4702: Task 4.3.3 — Markeer failures/waarschuwingen

- **State:** New
- **Work item ID:** 4702

**Description**

<div><div style="font-family:'Segoe UI';">“Quality gate” die pipeline kan laten falen of waarschuwing geeft. </div><br> </div>

<a id="task-4703-task-434-log-en-archiveer-reviewrapporten"></a>
##### Task 4703: Task 4.3.4 — Log en archiveer reviewrapporten

- **State:** New
- **Work item ID:** 4703

**Description**

<div><div style="font-family:'Segoe UI';">Transparantie en traceability. </div><br> </div>

<a id="task-4704-task-435-handleiding-voor-teams-hoe-aireview-te-interpreteren"></a>
##### Task 4704: Task 4.3.5 — Handleiding voor teams: hoe AI‑review te interpreteren

- **State:** New
- **Work item ID:** 4704

**Description**

<div><div style="font-family:'Segoe UI';">Wat is blocking vs. advisory? </div><br> </div>

<a id="user-story-4594-us44-als-ontwikkelaar-wil-ik-dat-ai-aangeeft-welke-documentatie-mogelijk-moet-worden-bijgewerkt-na-codewijzigingen-zodat-docs-uptodate-blijven"></a>
#### User Story 4594: US4.4 Als ontwikkelaar wil ik dat AI aangeeft welke documentatie mogelijk moet worden bijgewerkt na code‑wijzigingen, zodat docs up‑to‑date blijven.

- **State:** New
- **Work item ID:** 4594

<a id="task-4705-task-441-bepaal-mapping-code-docs-impactregels"></a>
##### Task 4705: Task 4.4.1 — Bepaal mapping code → docs (impactregels)

- **State:** New
- **Work item ID:** 4705

**Description**

<div><div style="font-family:'Segoe UI';">Voorbeelden: wijziging in API‑controllers → <code>/docs/api/*</code>; infra/pipeline → <code>/docs/architecture/*</code>. </div><br> </div>

<a id="task-4706-task-442-pipelinestep-verzamel-diffs-per-prmerge"></a>
##### Task 4706: Task 4.4.2 — Pipeline‑step: verzamel diffs per PR/merge

- **State:** New
- **Work item ID:** 4706

**Description**

<div><div style="font-family:'Segoe UI';">Bestandspaden, typen wijzigingen. </div><br> </div>

<a id="task-4707-task-443-aianalyse-welke-docs-zijn-potentieel-impacted"></a>
##### Task 4707: Task 4.4.3 — AI‑analyse: welke docs zijn potentieel impacted?

- **State:** New
- **Work item ID:** 4707

**Description**

<div><div style="font-family:'Segoe UI';">Output: lijst met te controleren/te updaten documenten. </div><br> </div>

<a id="task-4708-task-444-maak-een-outdated-warning-comment-op-pr"></a>
##### Task 4708: Task 4.4.4 — Maak een “outdated warning” comment op PR

- **State:** New
- **Work item ID:** 4708

**Description**

<div><div style="font-family:'Segoe UI';">Automatische opmerking/tag voor owners. </div><br> </div>

<a id="task-4709-task-445-monitor-and-finetune-regels"></a>
##### Task 4709: Task 4.4.5 — Monitor & fine‑tune regels

- **State:** New
- **Work item ID:** 4709

**Description**

<div><div style="font-family:'Segoe UI';">Verhoog precisie en verlaag ruis. </div><br> </div>

<a id="feature-4595-feature-5-adoptie-and-migratie-van-bestaande-repositories-naar-de-nieuwe-documentatiestandaard"></a>
### Feature 4595: Feature 5. Adoptie & Migratie van Bestaande Repositories naar de Nieuwe Documentatiestandaard

- **State:** New
- **Work item ID:** 4595

**Description**

<div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Deze feature richt zich op de <strong>uitrol</strong>, <strong>adoptie</strong> en <strong>migratie</strong> van de nieuwe documentatiestandaard — inclusief <code>/docs</code>‑structuur, templates, versiebeheer‑richtlijnen en CI/CD‑publicatieprocessen — naar <strong>bestaande repositories</strong> binnen de organisatie. </p><p>We brengen de impact per project in kaart, bepalen migratiestappen en tooling, en begeleiden teams in de adoptie. Daarnaast zetten we AI‑ondersteuning in (M365 Copilot, VS Code Copilot Agent, Visual Studio Copilot Agent en Azure OpenAI) om <strong>inconsistenties te detecteren</strong>, <strong>documenten te vergelijken</strong>, en <strong>migratievoorstellen</strong> te genereren. </p><p>Het resultaat van deze feature is dat de nieuwe documentatie‑architectuur <strong>uniform</strong>, <strong>breed gedragen</strong> en <strong>operationeel</strong> is in bestaande codebases. </p><h3><strong>Business Value</strong> </h3><ul><li><strong>Snelle adoptie</strong> van documentatiestandaarden over alle projecten </li><li><strong>Lagere migratie‑kosten</strong> door AI‑ondersteuning en geautomatiseerde checks </li><li><strong>Minder inconsistenties</strong> tussen oude en nieuwe documentatie </li><li><strong>Hogere documentatiekwaliteit</strong> door uniforme templates en structuur </li><li><strong>Teams worden ontzorgd</strong>, waardoor migratie geen blokkerende factor wordt </li><li><strong>Platform‑agnostisch</strong>, dus bruikbaar ongeacht documentatieplatform </li> </ul><h3><strong>Acceptance Criteria</strong> </h3><h4><strong>Functioneel</strong> </h4><input type=checkbox disabled=""> Een <strong>impactanalyse</strong> per repository is uitgevoerd<br><input type=checkbox disabled=""> Een <strong>migratieplan</strong> met duidelijke stappen is opgesteld<br><input type=checkbox disabled=""> Minstens één repository is succesvol als <strong>pilot</strong> gemigreerd<br><input type=checkbox disabled=""> De nieuwe <code>/docs</code>‑structuur, templates en CI/CD‑flow zijn toegepast op de pilot<br><input type=checkbox disabled=""> Migratiehandleiding (stappenplan) is gepubliceerd<br><input type=checkbox disabled=""> Tijdens migratie wordt gecontroleerd op <strong>inconsistenties</strong> en <strong>verouderde documentatie</strong><br><h4><strong>Niet‑functioneel</strong> </h4><input type=checkbox disabled=""> Migratieproces is <strong>herhaalbaar</strong> en bruikbaar voor alle teams<br><input type=checkbox disabled=""> Migratie introduceert <strong>geen breaking changes</strong> voor lopende projecten<br><input type=checkbox disabled=""> Teams worden ondersteund met <strong>heldere instructies</strong> en voorbeelden<br><input type=checkbox disabled=""> AI‑analyses blijven <strong>privacyvriendelijk binnen het Microsoft‑ecosysteem</strong> </div><div style="font-family:'Segoe UI';"><strong><br></strong> </div><div style="font-family:'Segoe UI';"><strong>AI‑specifiek</strong><strong><br></strong><input type=checkbox disabled=""> AI kan verschillen detecteren tussen oude en nieuwe documentatie per repository<br><input type=checkbox disabled=""> AI kan voorstellen genereren voor het migreren van documenten<br><input type=checkbox disabled=""> AI kan inconsistenties signaleren (verouderde secties, dubbele inhoud, verkeerde structuur)<br><input type=checkbox disabled=""> Copilot kan helpen bij herschrijven van legacy‑documentatie<br><input type=checkbox disabled=""> Azure OpenAI kan in CI/CD een <strong>migratie‑review</strong> genereren </div><br><br>

<a id="user-story-4596-us51-als-platformteam-wil-ik-inzicht-in-welke-aanpassingen-nodig-zijn-voor-bestaande-repositories-zodat-we-een-correcte-migratieplanning-kunnen-maken"></a>
#### User Story 4596: US5.1 Als platformteam wil ik inzicht in welke aanpassingen nodig zijn voor bestaande repositories, zodat we een correcte migratieplanning kunnen maken.

- **State:** New
- **Work item ID:** 4596

<a id="task-4711-task-511-inventariseer-alle-repositories-binnen-scope"></a>
##### Task 4711: Task 5.1.1 — Inventariseer alle repositories binnen scope

- **State:** New
- **Work item ID:** 4711

<a id="task-4712-task-512-analyseer-huidige-documentatiestructuur-per-repository"></a>
##### Task 4712: Task 5.1.2 — Analyseer huidige documentatiestructuur per repository

- **State:** New
- **Work item ID:** 4712

<a id="task-4713-task-513-breng-ontbrekende-of-afwijkende-documentatie-in-kaart"></a>
##### Task 4713: Task 5.1.3 — Breng ontbrekende of afwijkende documentatie in kaart

- **State:** New
- **Work item ID:** 4713

<a id="task-4714-task-514-controleer-cicdimpact"></a>
##### Task 4714: Task 5.1.4 — Controleer CI/CD‑impact

- **State:** New
- **Work item ID:** 4714

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld: breekt publicatie? Zijn er conflicts met bestaande flows? </div><br> </div>

<a id="task-4715-task-515-maak-impactrapport-per-repository"></a>
##### Task 4715: Task 5.1.5 — Maak impactrapport per repository

- **State:** New
- **Work item ID:** 4715

**Description**

<div><div style="font-family:'Segoe UI';">Met prioriteit (low/medium/high effort). </div><br> </div>

<a id="task-4716-task-516-bespreek-resultaten-met-stakeholders"></a>
##### Task 4716: Task 5.1.6 — Bespreek resultaten met stakeholders

- **State:** New
- **Work item ID:** 4716

<a id="task-4717-task-517-ai-aianalyse-consistentie-oude-vs-nieuwe-structuur"></a>
##### Task 4717: Task 5.1.7 (AI) — AI‑analyse: consistentie oude vs. nieuwe structuur

- **State:** New
- **Work item ID:** 4717

<a id="task-4718-task-518-ai-aidetectie-ontbrekende-documentatietypes"></a>
##### Task 4718: Task 5.1.8 (AI) — AI‑detectie: ontbrekende documentatietypes

- **State:** New
- **Work item ID:** 4718

<a id="user-story-4597-us52-als-ontwikkelteam-wil-ik-een-duidelijk-migratieplan-zodat-ik-weet-welke-stappen-nodig-zijn-om-de-nieuwe-documentatiestandaard-te-gebruiken"></a>
#### User Story 4597: US5.2 Als ontwikkelteam wil ik een duidelijk migratieplan, zodat ik weet welke stappen nodig zijn om de nieuwe documentatiestandaard te gebruiken.

- **State:** New
- **Work item ID:** 4597

<a id="task-4719-task-521-definieer-stappenplan-voor-migratie"></a>
##### Task 4719: Task 5.2.1 — Definieer stappenplan voor migratie

- **State:** New
- **Work item ID:** 4719

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld:
<ol><li>Aanmaken <code>/docs</code> </li><li>Verplaatsen documenten </li><li>Template‑mapping </li><li>Metadata toevoegen </li><li>Pipeline configureren </li> </ol> </div><br> </div>

<a id="task-4720-task-522-maak-adoptiestrategie-per-teamper-project"></a>
##### Task 4720: Task 5.2.2 — Maak adoptiestrategie (per team/per project)

- **State:** New
- **Work item ID:** 4720

<a id="task-4721-task-523-maak-migratiechecklist-voor-developers"></a>
##### Task 4721: Task 5.2.3 — Maak migratiechecklist voor developers

- **State:** New
- **Work item ID:** 4721

<a id="task-4722-task-524-schrijf-migratiehandleiding-markdown"></a>
##### Task 4722: Task 5.2.4 — Schrijf migratiehandleiding (Markdown)

- **State:** New
- **Work item ID:** 4722

<a id="task-4723-task-525-publiceer-handleiding-in-centrale-docsrepo"></a>
##### Task 4723: Task 5.2.5 — Publiceer handleiding in centrale docs‑repo

- **State:** New
- **Work item ID:** 4723

<a id="task-4724-task-526-ai-genereer-migratieadviezen-per-repository-via-copilot"></a>
##### Task 4724: Task 5.2.6 (AI) — Genereer migratieadviezen per repository via Copilot

- **State:** New
- **Work item ID:** 4724

<a id="task-4725-task-527-ai-verbeter-migratiehandleiding-met-m365-copilot"></a>
##### Task 4725: Task 5.2.7 (AI) — Verbeter migratiehandleiding met M365 Copilot

- **State:** New
- **Work item ID:** 4725

<a id="task-4726-task-528-ai-ontwikkel-prompts-voor-aiondersteunde-migratie-rewrite-this-legacy-doc-using-the-new-template"></a>
##### Task 4726: Task 5.2.8 (AI) — Ontwikkel prompts voor AI‑ondersteunde migratie (“Rewrite this legacy doc using the new template”)

- **State:** New
- **Work item ID:** 4726

<a id="user-story-4598-us53-als-platformteam-wil-ik-de-nieuwe-standaard-testen-op-een-pilot-repository-zodat-we-zeker-weten-dat-de-aanpak-werkt-voordat-we-dit-breder-uitrollen"></a>
#### User Story 4598: US5.3 Als platformteam wil ik de nieuwe standaard testen op een pilot repository, zodat we zeker weten dat de aanpak werkt voordat we dit breder uitrollen.

- **State:** New
- **Work item ID:** 4598

<a id="task-4727-task-531-selecteer-12-pilot-repositories"></a>
##### Task 4727: Task 5.3.1 — Selecteer 1–2 pilot repositories

- **State:** New
- **Work item ID:** 4727

<a id="task-4728-task-532-pas-docsstructuur-toe-op-pilot"></a>
##### Task 4728: Task 5.3.2 — Pas /docs‑structuur toe op pilot

- **State:** New
- **Work item ID:** 4728

<a id="task-4729-task-533-migreer-legacy-documentatie-naar-nieuwe-templates"></a>
##### Task 4729: Task 5.3.3 — Migreer legacy documentatie naar nieuwe templates

- **State:** New
- **Work item ID:** 4729

<a id="task-4730-task-534-implementeer-cicd-publicatieflow-feature-4"></a>
##### Task 4730: Task 5.3.4 — Implementeer CI/CD publicatieflow (Feature 4)

- **State:** New
- **Work item ID:** 4730

<a id="task-4731-task-535-test-volledige-pipeline-validate-ai-review-publish"></a>
##### Task 4731: Task 5.3.5 — Test volledige pipeline: validate → AI review → publish

- **State:** New
- **Work item ID:** 4731

<a id="task-4732-task-536-verzamel-feedback-van-pilot-teams"></a>
##### Task 4732: Task 5.3.6 — Verzamel feedback van pilot teams

- **State:** New
- **Work item ID:** 4732

<a id="task-4733-task-537-verwerk-bevindingen-en-verbeter-standaarden"></a>
##### Task 4733: Task 5.3.7 — Verwerk bevindingen en verbeter standaarden

- **State:** New
- **Work item ID:** 4733

<a id="task-4734-task-538-ai-laat-ai-documentatie-reviewen-op-structuur-and-volledigheid"></a>
##### Task 4734: Task 5.3.8 (AI) — Laat AI documentatie reviewen op structuur & volledigheid

- **State:** New
- **Work item ID:** 4734

<a id="task-4735-task-539-ai-ailed-rewrite-herschrijf-legacy-documentation-in-nieuwe-template"></a>
##### Task 4735: Task 5.3.9 (AI) — AI‑led rewrite: herschrijf legacy documentation in nieuwe template

- **State:** New
- **Work item ID:** 4735

<a id="user-story-4710-us54-als-platformteam-wil-ik-ai-gebruiken-om-inconsistenties-te-detecteren-en-migratievoorstellen-te-genereren-zodat-migratie-sneller-en-nauwkeuriger-wordt"></a>
#### User Story 4710: US5.4 Als platformteam wil ik AI gebruiken om inconsistenties te detecteren en migratievoorstellen te genereren, zodat migratie sneller en nauwkeuriger wordt.

- **State:** New
- **Work item ID:** 4710

<a id="task-4736-task-541-koppel-ai-aan-documentatiediffs"></a>
##### Task 4736: Task 5.4.1 — Koppel AI aan documentatie‑diffs

- **State:** New
- **Work item ID:** 4736

<a id="task-4737-task-542-laat-ai-inconsistenties-detecteren"></a>
##### Task 4737: Task 5.4.2 — Laat AI inconsistenties detecteren

- **State:** New
- **Work item ID:** 4737

**Description**

<div><div style="font-family:'Segoe UI';">Bijvoorbeeld: dubbele tekst, verkeerde structuur, ontbrekende metadata. </div><br> </div>

<a id="task-4738-task-543-genereer-migratievoorstellen-per-document"></a>
##### Task 4738: Task 5.4.3 — Genereer migratievoorstellen per document

- **State:** New
- **Work item ID:** 4738

<a id="task-4739-task-544-laat-ai-highlighten-welke-documenten-outdated-zijn"></a>
##### Task 4739: Task 5.4.4 — Laat AI highlighten welke documenten outdated zijn

- **State:** New
- **Work item ID:** 4739

<a id="task-4740-task-545-bouw-voorbeeld-migratieadviesrapport"></a>
##### Task 4740: Task 5.4.5 — Bouw voorbeeld migratieadviesrapport

- **State:** New
- **Work item ID:** 4740

<a id="task-4741-task-546-ai-proof-of-concept-ai-migratie-review-pipelinestep-azure-openai"></a>
##### Task 4741: Task 5.4.6 (AI) — Proof of concept: “AI Migratie Review” pipeline‑step (Azure OpenAI)

- **State:** New
- **Work item ID:** 4741

<a id="task-4742-task-547-ai-copilot-vergelijkingsprompt-compare-legacy-doc-with-new-template-azure-openai"></a>
##### Task 4742: Task 5.4.7 (AI) — Copilot vergelijkingsprompt (“Compare legacy doc with new template”) (Azure OpenAI)

- **State:** New
- **Work item ID:** 4742

<a id="feature-4599-feature-6-aiondersteuning-voor-schrijven-verbeteren-en-valideren-van-documentatie"></a>
### Feature 4599: Feature 6. AI‑Ondersteuning voor Schrijven, Verbeteren en Valideren van Documentatie

- **State:** New
- **Work item ID:** 4599

**Description**

<div style="font-family:'Segoe UI';"><div style="font-family:'Segoe UI';"><h3><strong>Beschrijving</strong> </h3><p>Deze feature richt zich op het <strong>operationeel inzetten van AI</strong> in de documentatielifecycle: tijdens het <strong>schrijven in de IDE</strong> (VS Code Copilot agent, Visual Studio Insider Copilot), bij het <strong>bewerken en verbeteren van tekst</strong> (M365 Copilot), en in <strong>CI/CD‑pijplijnen</strong> (Azure OpenAI) voor <strong>kwaliteitsreview</strong>, <strong>samenvattingen</strong> en <strong>detectie van verouderde documentatie</strong> op basis van <strong>code‑diffs</strong>. </p><p>We leveren: </p><ul><li><strong>Promptbibliotheek</strong> voor developers en schrijvers (IDE + M365 Copilot). </li><li><strong>AI‑review checklist</strong> voor kwaliteit (structuur, toon, metadata, volledigheid). </li><li><strong>Pipeline‑steps</strong> die AI aanroepen voor review en release notes samenvatting. </li><li><strong>Richtlijnen</strong> voor veilig en effectief gebruik van AI (privacy, governance, “AI ondersteunt, vervangt niet”). </li> </ul><p><strong>Resultaat:</strong> Teams kunnen <strong>structureel, veilig en effectief</strong> AI inzetten om documentatie <strong>sneller</strong>, <strong>consistenter</strong> en <strong>kwalitatiever</strong> te maken en te houden. </p><br><h3><strong>Business Value</strong> </h3><ul><li><strong>Hogere snelheid</strong> bij het schrijven en updaten van documentatie. </li><li><strong>Constante kwaliteit</strong> door AI‑gestuurde controles en suggesties. </li><li><strong>Minder handwerk</strong> voor release notes en samenvattingen. </li><li><strong>Snellere probleemdetectie</strong> (ontbrekende secties, inconsistenties, verouderde content). </li><li><strong>Betere gebruikerservaring</strong> door duidelijke, actuele en consistente documentatie. </li><li><strong>Herhaalbaar &amp; schaalbaar</strong> door standaard prompts, checklists en pipeline‑integraties. </li> </ul><h3>✅ <strong>Acceptance Criteria</strong> </h3><h4><strong>Functioneel</strong> </h4><input type=checkbox disabled=""> <strong>Promptbibliotheek</strong> is beschikbaar voor IDE‑agents (VS Code/Visual Studio) en M365 Copilot (templates, herschrijven, samenvatten, metadata).<br><input type=checkbox disabled=""> <strong>AI‑review checklist</strong> is opgesteld (structuur/volledigheid, front‑matter/metadata, leesbaarheid/consistentie, broken links).<br><input type=checkbox disabled=""> <strong>Pipeline‑integraties</strong> zijn beschreven en als <strong>referentie‑implementatie</strong> beschikbaar (Azure OpenAI hooks).<br><input type=checkbox disabled=""> <strong>Richtlijnen</strong> voor AI‑gebruik (do’s &amp; don’ts, privacy, governance, RACI‑koppeling) zijn gepubliceerd.<br><input type=checkbox disabled=""> <strong>Voorbeeldcases</strong> (demo’s) tonen AI‑gebruik in IDE en pipeline.<br><h4><strong>Niet‑functioneel</strong> </h4><input type=checkbox disabled=""> AI‑oplossingen draaien binnen het <strong>Microsoft‑ecosysteem</strong> en zijn <strong>privacy‑bewust</strong>.<br><input type=checkbox disabled=""> AI‑output is <strong>reviewbaar</strong> en <strong>niet bindend</strong> (menselijke goedkeuring vereist).<br><input type=checkbox disabled=""> Integraties zijn <strong>herhaalbaar</strong> en <strong>versiebeheerbaar</strong> (centrale repo).<br><input type=checkbox disabled=""> De invoering veroorzaakt <strong>geen vertraging</strong> die groter is dan 2 minuten per pipeline run.<br><h4><strong>AI‑specifiek</strong> </h4><input type=checkbox disabled=""> <strong>Copilot‑prompts</strong> dekken schrijven, herschrijven, structureren, metadata en samenvatten.<br><input type=checkbox disabled=""> <strong>Azure OpenAI</strong> kan documentatie <strong>reviewen</strong> en <strong>release notes</strong> samenvatten vanuit commit/PR‑diffs.<br><input type=checkbox disabled=""> <strong>Detectie van mogelijk verouderde documentatie</strong> op basis van code‑wijzigingen is beschreven en gedemonstreerd.<br><input type=checkbox disabled=""> <strong>Quality gates</strong> kunnen waarschuwingen/blokkades geven op basis van AI‑review (configurabel). </div> </div><br>

<a id="user-story-4600-us61-als-ontwikkelaar-wil-ik-aiondersteuning-in-mijn-ide-zodat-ik-sneller-documentatie-kan-schrijven-docstringsxmldocs-kan-genereren-en-secties-kan-aanvullen"></a>
#### User Story 4600: US6.1 Als ontwikkelaar wil ik AI‑ondersteuning in mijn IDE, zodat ik sneller documentatie kan schrijven, docstrings/XML‑docs kan genereren en secties kan aanvullen.

- **State:** New
- **Work item ID:** 4600

<a id="task-4743-task-611-inventariseer-aiusecases-in-ide-docstrings-readmesecties-inline-uitleg-voorbeeldcode-uitleg"></a>
##### Task 4743: Task 6.1.1 — Inventariseer AI‑use‑cases in IDE (docstrings, README‑secties, inline uitleg, voorbeeldcode uitleg).

- **State:** New
- **Work item ID:** 4743

<a id="task-4744-task-612-configureer-copilot-agents-vs-code-and-visual-studio-insider-voor-documentatieprompts"></a>
##### Task 4744: Task 6.1.2 — Configureer Copilot agents (VS Code & Visual Studio Insider) voor documentatie‑prompts.

- **State:** New
- **Work item ID:** 4744

<a id="task-4745-task-613-maak-prompts-voor-docstringsxmldocs-samenvatten-van-methoden-parameters-exceptions"></a>
##### Task 4745: Task 6.1.3 — Maak prompts voor docstrings/XML‑docs (samenvatten van methoden, parameters, exceptions).

- **State:** New
- **Work item ID:** 4745

<a id="task-4746-task-614-voorbeeldworkflow-van-code-naar-docstring-naar-docssectie"></a>
##### Task 4746: Task 6.1.4 — Voorbeeldworkflow: “van code naar docstring naar /docs‑sectie”.

- **State:** New
- **Work item ID:** 4746

<a id="task-4747-task-615-demo-en-handleiding-voor-developers"></a>
##### Task 4747: Task 6.1.5 — Demo en handleiding voor developers.

- **State:** New
- **Work item ID:** 4747

<a id="user-story-4601-us62-als-documentatieschrijver-wil-ik-m365-copilot-gebruiken-om-teksten-te-herschrijven-en-te-verbeteren-zodat-documentatie-consistent-leesbaar-en-volgens-richtlijnen-is"></a>
#### User Story 4601: US6.2 Als documentatieschrijver wil ik M365 Copilot gebruiken om teksten te herschrijven en te verbeteren, zodat documentatie consistent, leesbaar en volgens richtlijnen is.

- **State:** New
- **Work item ID:** 4601

<a id="task-4748-task-621-definieer-kwaliteitscriteria-toon-stijl-consistentie-terminologie-toegankelijkheid"></a>
##### Task 4748: Task 6.2.1 — Definieer kwaliteitscriteria (toon, stijl, consistentie, terminologie, toegankelijkheid).

- **State:** New
- **Work item ID:** 4748

<a id="task-4749-task-622-m365-copilot-prompts-voor-herschrijvenvereenvoudigenstructureren"></a>
##### Task 4749: Task 6.2.2 — M365 Copilot prompts voor herschrijven/vereenvoudigen/structureren.

- **State:** New
- **Work item ID:** 4749

<a id="task-4750-task-623-voorbeeldcases-herschrijf-een-architectuursectie-verbeter-changelog-harmoniseer-readme"></a>
##### Task 4750: Task 6.2.3 — Voorbeeldcases: herschrijf een architectuursectie; verbeter changelog; harmoniseer README.

- **State:** New
- **Work item ID:** 4750

<a id="task-4751-task-624-reviewproces-menselijke-goedkeuring-blijft-nodig-governance"></a>
##### Task 4751: Task 6.2.4 — Reviewproces: menselijke goedkeuring blijft nodig (governance).

- **State:** New
- **Work item ID:** 4751

<a id="task-4752-task-625-publiceer-copilot-schrijf-en-stijlrichtlijnen"></a>
##### Task 4752: Task 6.2.5 — Publiceer “Copilot schrijf‑ en stijlrichtlijnen

- **State:** New
- **Work item ID:** 4752

<a id="user-story-4602-us63-als-architect-wil-ik-dat-ai-complexe-configuratie-en-architectuurbestanden-samenvat-in-begrijpelijke-documentatie-zodat-kennis-snel-overdraagbaar-is"></a>
#### User Story 4602: US6.3 Als architect wil ik dat AI complexe configuratie‑ en architectuurbestanden samenvat in begrijpelijke documentatie, zodat kennis snel overdraagbaar is.

- **State:** New
- **Work item ID:** 4602

<a id="task-4753-task-631-identificeer-bronbestanden-iac-pipelines-configs-manifests"></a>
##### Task 4753: Task 6.3.1 — Identificeer bronbestanden (IaC, pipelines, configs, manifests).

- **State:** New
- **Work item ID:** 4753

<a id="task-4754-task-632-ontwikkel-prompts-vat-deze-configuratie-samen-voor-docsarchitecture"></a>
##### Task 4754: Task 6.3.2 — Ontwikkel prompts: “Vat deze configuratie samen voor /docs/architecture/”.

- **State:** New
- **Work item ID:** 4754

<a id="task-4755-task-633-plaats-samenvattingen-in-juiste-templatesecties-feature-3"></a>
##### Task 4755: Task 6.3.3 — Plaats samenvattingen in juiste template‑secties (Feature 3).

- **State:** New
- **Work item ID:** 4755

<a id="task-4756-task-634-validatie-door-architecten-correctheid-en-jargon"></a>
##### Task 4756: Task 6.3.4 — Validatie door architecten (correctheid en jargon).

- **State:** New
- **Work item ID:** 4756

<a id="task-4757-task-635-library-met-voorbeeldsamenvattingen-in-centrale-repo"></a>
##### Task 4757: Task 6.3.5 — Library met voorbeeldsamenvattingen in centrale repo.

- **State:** New
- **Work item ID:** 4757

<a id="user-story-4603-us64-als-team-wil-ik-aireviews-in-de-pipeline-zodat-documentatie-automatisch-wordt-gecontroleerd-op-structuur-volledigheid-en-metadata"></a>
#### User Story 4603: Us6.4 Als team wil ik AI‑reviews in de pipeline, zodat documentatie automatisch wordt gecontroleerd op structuur, volledigheid en metadata.

- **State:** New
- **Work item ID:** 4603

<a id="task-4758-task-641-definieer-aireviewchecklist-structuur-frontmatter-links-volledigheid-taal"></a>
##### Task 4758: Task 6.4.1 — Definieer AI‑reviewchecklist (structuur, front‑matter, links, volledigheid, taal).

- **State:** New
- **Work item ID:** 4758

<a id="task-4759-task-642-pipeline-step-die-docs-aan-azure-openai-aanbiedt-ontvangt-reviewrapport"></a>
##### Task 4759: Task 6.4.2 — Pipeline step die docs aan Azure OpenAI aanbiedt + ontvangt reviewrapport.

- **State:** New
- **Work item ID:** 4759

<a id="task-4760-task-643-quality-gates-waarschuwing-vs-blokkade-configurabel-per-repo"></a>
##### Task 4760: Task 6.4.3 — Quality gates: waarschuwing vs. blokkade (configurabel per repo).

- **State:** New
- **Work item ID:** 4760

<a id="task-4761-task-644-loggingarchivering-van-reviewrapporten-traceability"></a>
##### Task 4761: Task 6.4.4 — Logging/archivering van reviewrapporten (traceability).

- **State:** New
- **Work item ID:** 4761

<a id="task-4762-task-645-handleiding-voor-teams-hoe-reviewresultaten-te-interpreteren-en-verwerken"></a>
##### Task 4762: Task 6.4.5 — Handleiding voor teams: hoe reviewresultaten te interpreteren en verwerken.

- **State:** New
- **Work item ID:** 4762

<a id="user-story-4763-us65-als-ontwikkelaar-wil-ik-dat-ai-documentatie-markeert-als-mogelijk-verouderd-bij-codewijzigingen-zodat-we-tijdig-updates-doen"></a>
#### User Story 4763: US6.5 Als ontwikkelaar wil ik dat AI documentatie markeert als mogelijk verouderd bij code‑wijzigingen, zodat we tijdig updates doen.

- **State:** New
- **Work item ID:** 4763

<a id="task-4765-task-651-mappingregels-code-docs-controllers-docsapi-infra-docsarchitecture"></a>
##### Task 4765: Task 6.5.1 — Mappingregels code → docs (controllers ↔ /docs/api, infra ↔ /docs/architecture).

- **State:** New
- **Work item ID:** 4765

<a id="task-4766-task-652-pipeline-step-verzamel-diffs-en-vorm-context-voor-ai"></a>
##### Task 4766: Task 6.5.2 — Pipeline step: verzamel diffs en vorm context voor AI.

- **State:** New
- **Work item ID:** 4766

<a id="task-4767-task-653-aianalyse-lijst-van-mogelijk-impacted-docs-confidence"></a>
##### Task 4767: Task 6.5.3 — AI‑analyse: lijst van mogelijk impacted docs + confidence.

- **State:** New
- **Work item ID:** 4767

<a id="task-4768-task-654-prcomment-met-waarschuwingen-en-advies-owners-taggen"></a>
##### Task 4768: Task 6.5.4 — PR‑comment met waarschuwingen en advies (owners taggen).

- **State:** New
- **Work item ID:** 4768

<a id="task-4769-task-655-finetuning-van-impactregels-op-basis-van-feedback"></a>
##### Task 4769: Task 6.5.5 — Fine‑tuning van impactregels op basis van feedback.

- **State:** New
- **Work item ID:** 4769

<a id="user-story-4764-us66-als-platformteam-wil-ik-een-centrale-promptbibliotheek-en-richtlijnen-zodat-ai-consistent-veilig-en-effectief-wordt-ingezet"></a>
#### User Story 4764: US6.6 Als platformteam wil ik een centrale promptbibliotheek en richtlijnen, zodat AI consistent, veilig en effectief wordt ingezet.

- **State:** New
- **Work item ID:** 4764

<a id="task-4770-task-661-promptbibliotheek-opzetten-ide-m365-copilot-pipeline"></a>
##### Task 4770: Task 6.6.1 — Promptbibliotheek opzetten (IDE + M365 Copilot + pipeline).

- **State:** New
- **Work item ID:** 4770

<a id="task-4771-task-662-categorien-schrijven-herschrijven-structureren-metadata-samenvatting-validatie"></a>
##### Task 4771: Task 6.6.2 — Categorieën: schrijven, herschrijven, structureren, metadata, samenvatting, validatie.

- **State:** New
- **Work item ID:** 4771

<a id="task-4772-task-663-voorbeeldprompts-per-documenttype-api-architectuur-changelog-readme"></a>
##### Task 4772: Task 6.6.3 — Voorbeeldprompts per documenttype (API, architectuur, changelog, README).

- **State:** New
- **Work item ID:** 4772

<a id="task-4773-task-664-publiceer-richtlijnen-dos-and-donts-privacy-governance-racikoppeling"></a>
##### Task 4773: Task 6.6.4 — Publiceer richtlijnen (do’s & don’ts, privacy, governance, RACI‑koppeling).

- **State:** New
- **Work item ID:** 4773

**Description**

<div><div style="font-family:'Segoe UI';"><h3><strong>RACI-Koppeling</strong> </h3><h3><strong>API‑documentatie (voorbeeld)</strong> </h3><div><table><thead><tr><th style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);">Rol</th><th style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);">Betekenis</th><th style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);">Verantwoordelijkheid</th></tr></thead><tbody><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>R – Responsible</strong></th><td style="border:1px solid rgb(230, 230, 230);">Uitvoerder </td><td style="border:1px solid rgb(230, 230, 230);">API‑developer / technical writer gebruikt Copilot om documentatie te schrijven </td></tr><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>A – Accountable</strong></th><td style="border:1px solid rgb(230, 230, 230);">Eindverantwoordelijk </td><td style="border:1px solid rgb(230, 230, 230);">Product Owner of API‑owner keurt definitieve docs goed </td></tr><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>C – Consulted</strong></th><td style="border:1px solid rgb(230, 230, 230);">Adviserend </td><td style="border:1px solid rgb(230, 230, 230);">Architect (voor design), QA (voor edge cases) </td></tr><tr><th scope=row style="border:1px solid rgb(230, 230, 230);background-color:rgb(245, 245, 245);"><strong>I – Informed</strong></th><td style="border:1px solid rgb(230, 230, 230);">Op de hoogte </td><td style="border:1px solid rgb(230, 230, 230);">DevOps team / support teams </td></tr></tbody></table> </div> </div><br> </div>

<a id="task-4774-task-665-trainingdemo-voor-teams-best-practices"></a>
##### Task 4774: Task 6.6.5 — Training/demo voor teams (best practices).

- **State:** New
- **Work item ID:** 4774
