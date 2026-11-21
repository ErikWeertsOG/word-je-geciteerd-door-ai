# Word je geciteerd door AI?

Een Claude-skill die meet of ChatGPT, Perplexity en Google jouw organisatie noemen bij de vragen die je kopers stellen. En als dat niet zo is: waarom niet.

## Het probleem

Je kopers googelen minder en vragen meer. "Welke partijen doen dit in Nederland?" gaat steeds vaker naar een AI-assistent. Die geeft geen tien blauwe links maar drie namen.

Sta jij daartussen? De meeste marketeers weten het niet. Ze hebben het één keer geprobeerd met één vraag, zagen hun naam niet en schrokken. Of ze zagen hem wel en waren gerustgesteld. Geen van beide is een meting.

## Wat deze skill doet

1. **Vragenset.** Claude maakt met jou twaalf vragen die jouw kopers echt stellen. In tien daarvan staat je naam niet.
2. **Antwoorden.** Je stelt de vragen aan minimaal twee assistenten en plakt de antwoorden terug. Heeft Claude een browser, dan doet hij het zelf.
3. **Matrix.** Per vraag: word je genoemd, word je gelinkt, wie wordt er wel genoemd en op welke bronnen leunt het antwoord.
4. **Waarom niet.** Per gat één reden: geen pagina, verkeerde vorm, niemand anders noemt je, of verouderd.
5. **Acties.** Maximaal vijf, met de makkelijkste bovenaan.

Het kost je een uur tot anderhalf uur, vooral door het plakken.

## Wat je eruit haalt

Het interessantste is meestal niet of je genoemd wordt. Het is de lijst met bronnen. Je ziet op welke vijf websites de assistenten leunen in jouw categorie. Vaak zijn dat een vakblad, een vergelijkingssite en twee concurrenten met een goede uitlegpagina. Dan weet je waar je moet zijn.

## Wat het niet is

Ik wil hier eerlijk over zijn, want er wordt veel onzin over verkocht.

- **Het is geen ranking.** AI-antwoorden wisselen per keer. Je krijgt een momentopname.
- **Het is geen garantie.** Niemand weet precies hoe deze systemen kiezen. De acties zijn redelijke stappen, meer niet.
- **Het is geen trucendoos.** Geen verborgen tekst en geen pagina's die alleen voor AI geschreven zijn. Wat een koper niet helpt, werkt hier ook niet lang.

De waarde zit in het herhalen. Draai dezelfde twaalf vragen elk kwartaal, dan zie je of er iets verschuift.

## Installeren

Je hebt geen technische kennis nodig.

**In Claude (web, desktop of app)**
1. Download deze repo als zip via de groene knop **Code → Download ZIP**.
2. Upload de zip bij Skills in je Claude-instellingen.
3. Zeg tegen Claude: "Worden wij genoemd door AI?" en de skill neemt het over.

**In Claude Code**
Zet de map in `~/.claude/skills/`.

## Tips

- Gebruik een tijdelijke chat of log uit voordat je de vragen stelt. Anders kleurt je eigen geschiedenis het antwoord.
- Stel elke vraag in een nieuw gesprek.
- Plak het hele antwoord terug, met de bronnen. Daar zit de helft van de waarde.
- Bewaar je vragenset. Zonder dezelfde vragen kun je de volgende keer niets vergelijken.

## Meedoen

Heb je een vraagtype dat ontbreekt, of een reden die niet in de vier past? Open een issue. Dit vak is een jaar oud en niemand heeft het al uitgevonden.

---

Gemaakt door [Erik Weerts](https://github.com/ErikWeertsOG). Elke tekst doorloopt de [zes checks](https://github.com/ErikWeertsOG/stop-ai-slop-nl) van Stop AI Slop.
