# Sýn og Afmörkun 

## Númer teymis og höfundar
Hópur 7. Dagur Ingi Viðar, Stefán Steinar Guðlaugsson.

## Heiti kerfis
Nemendakerfi fyrir námsmat


## Efnisyfirlit 
- [Breytingasaga](#revision-history)
- [1. Viðskiptakröfur](#1-business-requirements)
    - [1.1 Bakgrunnur](#11-background)
    - [1.2 Viðskiptatækifæri](#12-business-opportunity)
    - [1.3 Viðskiptamarkmið](#13-business-objectives)
    - [1.4 Árangursmælikvarðar ](#14-success-metrics)
    - [1.5 Sýn](#15-vision-statement)
    - [1.6 Viðskiptaáhætta](#16-business-risks)
    - [1.7 Viðskiptaforsendur og háðleiki](#17-business-assumptions-and-dependencies)
- [2. Umfang og takmarkanir](#2-scope-and-limitations)
    - [2.1 Helstu fídusar](#21-major-features)
    - [2.2 Umfang fyrstu útgáfu](#22-scope-of-initial-and-subsequent-releases)
    - [2.3 Takmarkanir og útilokanir](#23-limitations-and-exclusions)
- [3. Samhengi viðskipta](#3-business-context)
    - [3.1 Prófílar hagsmunaaðila](#31-stakeholder-profiles)
    - [3.2 Forgangsröðun verkefnis](#32-project-priorities)
    - [3.3 Innleiðingarsjónarmið](#33-deployment-considerations)

---
> Hver kafli á að vera um það bil hálf síða að lengd.
> 
## 1. Viðskiptakröfur
### 1.1 Bakgrunnur


### 1.2 Viðskiptatækifæri


### 1.3 Viðskiptamarkmið
BO-1: Hækka meðalánægju notenda af kerfinu um 20%

- Scale: 1-5 ánægjukvarði (t.d. úr notendakönnun)
- Meter: Meðaltal úr notendakönnun _eftir_ útgáfu
- Past (Baseline): 3.5
- Goal: 4.2
- Stretch: 4.5

BO-2: Fækka fjölda síða sem nemandi þarf til að halda utan um einkunnir niður í tvær fyrir alla áfanga

- Scale: Fjöldi síða sem notandi þarf til að sjá allar einkunnir (Canvas, Gradescope o.fl.)
- Meter: Notendaprófanir og flæðigreining í Canvas
- Past (Baseline): meðaltal tvær eða fleiri
- Goal: 2 síður
- Stretch: 1 síða (aðal námskeiðs síða)

BO-3: Auka virkni á aðal námskeiðssíðu um 5% innan við sex mánuði eftir útgáfu

- Scale: Hlutfall virkra notenda yfir ákveðið tímabil
- Meter: Notendagögn úr vefgreiningu
- Past (Baseline): 80%
- Goal: 84%
- Stretch: 87%

BO-4: Minnka stress nemenda hvað óvissu í námsframvindu varðar um 15%

- Scale: 1-10 kvarði (t.d. úr sjálfsmati frá spurningakönnun)
- Meter: Meðaltal stiga í spurningu s.s. "Hversu vel heldurðu að þú vitir hvernig námsframvinda þín gengur þessa önn?"
- Past (Baseline): 6.0 / 10 (f. meðalstress)
- Goal: 5.1 / 10
- Stretch: 4.5 / 10

### 1.4 Árangurs mælikvarðar


### 1.5 Framtíðarsýn
Námsárangurskerfið er upplýsingamiðlunarkerfi fyrir nemendur og prófessora sem mun gefa þeima einfaldan aðgang og skýra framsetningu á skólagögnum. 

Fyrir nemendur mun kerfið sýna einkunnir á gagnlegum formum: meðaleinkunn, staðalfrávik, hæsta og lægsta einkunn, algildi á einkunn varðandi lokaeinkunn ásamt gröfum fyrir einkunnir yfir önnina skipt eftir flokkum. Kerfið mun einnig veita nemendum spár fyrir verkefnaeinkunn og reiknar út frá henni og öðrum einkunum sem áfangi kann að bjóða upp á (s.s. próf) hver lokaeinkunn mun vera fyrir mismunandi lokaprófseinkunnir. Kerfið heldur einnig utan um mætingu á einum stað og veitir sjálfkrafa viðvörun ef nemandi er í hættu á að tapa próftökurétt. Þetta mun auðvelda þeim um að halda utan um námið, skipuleggja sig og vita nákvæmlega hvað þeir þurfa að gera til að ná tilteknum áföngum. Einnig munu færri nemendur vera í hættu á að missa próftökurétt þegar þeir fá betri stað til að halda utan um hann.

Prófessorar munu hafa aðgang að sömu gögnum og nemendur nema þá sérstaklega fyrir fjöldann. Gögn um einkunnir, gröf og spár munu gagna kennara vel til að fylgjast með hvernig áfanginn gengur í heild svo hann geti gripið inn snemma ef betur getur gengið. Utanhald um mætingu getur síðan hjálpað ef kennara finnst nauðsynlegt að minna nemendur á mætingu varðandi próftökurétt eða breyta dæmatímum við lok annar svo fleiri geti mætt. Einnig getur hann þá borið saman fyrrverandi ár til að sjá hvernig mismunandi kennsluhættir hafa áhrif á frammistöðu nemenda.

Þetta er ólíkt núverandi kerfi sem heldur utan um einkunnir nemenda á mörgum mismunandi forritum, s.s. Canvas, Gradescope o.fl. Einnig sér núverandi kerfi ekki um mætingu nemenda (svo hún sé sýnileg þeim) nema prófessor velji það sérstaklega. Engin gröf eru heldur að finna, né meðaleinkunnir eða fleir nánari gögn um einkunnir. Engar spár eru til staðar heldur. Okkar kerfi er byggt til að breyta þessu.

### 1.6 Viðskiptaáhætta


### 1.7 Viðskiptaforsendur og háðleiki


---

## 2. Umfang  og takmarkanir 
### 2.1 Helstu fídusar


### 2.2 Umfang fyrstu útgáfu
*(Skrifaðu þennan kafla )*

[Describe the intended major features that will be included in the initial release of the product. 
Consider the benefits the product is intended to bring to the various customer communities, and generally describe the 
product features and quality characteristics that will enable it to provide those benefits. Avoid the temptation to 
include every possible feature that any potential customer category might conceivably want some day.
Focus on those features and product characteristics  that will provide the most value, at the most acceptable development cost, to the broadest community]

Fyrsta útgáfa *Nemendakerfis fyrir námsmat* (útgáfa 1.0) leggur áherslu á einfalt, stöðugt og notendavænt kerfi sem tryggir áreiðanleika og gagnsæi í námsmati. Markmið fyrstu útgáfu er að veita bæði nemendum og kennurum kjarna af gagnlegum virkni áður en flóknari eiginleikar eru þróaðir.

**Innan umfangs (In Scope):**
- **Innskráning og auðkenning:** Notendur skrá sig inn með skólareikningi og fá öruggan aðgang að eigin gögnum.  
- **Verkefnaskil:** Nemendur geta hlaðið upp verkefnum (t.d. PDF, DOCX) og fengið staðfestingu á móttöku.  
- **Einkunnaskráning:** Kennarar geta fært inn einkunnir og skrifað endurgjöf sem tengist hverju verkefni.  
- **Yfirlit yfir námsframvindu:** Nemendur geta séð yfirlit yfir einkunnir, vægi og meðaltöl í einu viðmóti.  
- **Yfirlit kennara:** Kennarar fá yfirsýn yfir verkefnaskil, hópaframvindu og meðaltöl.  
- **Öryggi og gagnavarsla:** Kerfið tryggir trúnað og rétt aðgangsheimild notenda.  

**Utan umfangs (Out of Scope):**
- Sjálfvirk einkunnagjöf eða prófakerfi.  
- Samþætting við ytri kerfi (Inna, Canvas, Moodle o.fl.).  
- Ítarleg tölfræðigreining eða gervigreindargreining á árangri.  
- Sjálfvirkar áminningar eða tölvupóstsendingar.  
- Sérsniðnar námsáætlanir eða viðbótarviðmót.  

**Áherslur og forgangsröðun:**
- **Drifkraftur:** Gagnsæi og einfaldleiki í notkun.  
- **Takmörkun:** Fjárhagsrammi og sex mánaða þróunartími.  
- **Frjálsleiki:** Fjöldi og útfærsla viðbótarfídusa getur þróast í seinni útgáfum.  

Markmiðið með útgáfu 1.0 er að afhenda *Minimum Viable Product (MVP)* sem eykur skilvirkni, dregur úr villum í einkunnaskráningu og byggir traustan grunn fyrir áframhaldandi þróun.


### 2.3 Takmarkanir og útilokanir


---

## 3. Samhengi viðskipta
### 3.1 Prófílar forgangs hagsmunaaðila 
*(Skrifaðu þennan kafla )*

[ Stakeholders are individuals, groups, or organizations that are actively involved in a project, are affected by its outcome, or can influence its outcome. The stakeholder profiles identify the customers for this product and other stakeholders, and states their major interests in the product. Characterize business-level customers, target market segments, and different user classes, to reduce the likelihood of unexpected requirements surfacing later that cannot be accommodated because of schedule or scope constraints. For each stakeholder category, the profile includes the major value or benefits they will receive from the product, their likely attitudes toward the product, major features and characteristics of interest, and any known constraints that must be accommodated. Examples of stakeholder value include:

- improved productivity
- reduced rework 
- cost savings	
- streamlined business processes	
- automation of previously manual tasks	
- ability to perform entirely new tasks or functions	
- conformance to current standards or regulations	
- improved usability or reduced frustration level compared to current applications
]
Setjið gjarnan upp í töflu sbr námsefnið

#### Hagsmunaaðili: Nemendur

| Þáttur | Lýsing |
|--------|--------|
| **Major Value (Helsti ávinningur)** | Fá betri yfirsýn yfir námsframvindu sína, sjá vægi verkefna og fá endurgjöf kennara á einum stað. |
| **Attitudes (Viðhorf)** | Almennt jákvæðir gagnvart nýjum lausnum ef þær eru einfaldar og aðgengilegar. Þeir missa þó traust fljótt ef kerfið er hægvirkt eða flókið. |
| **Major Interests (Helstu áherslur)** | Einfalt viðmót, skjót endurgjöf, sýn á meðaltöl og vægi einkunna, aðgengi á síma og tölvu. |
| **Constraints (Takmarkanir)** | Takmarkaður tími og tæknifærni. Kerfið þarf að vera á íslensku, virka á snjalltækjum og vera auðvelt í notkun. |

**Samantekt:**  
Nemendur eru helsti notendahópur og lykilhagsmunaaðili í þróun kerfisins.  
Kerfið þarf að mæta væntingum þeirra um áreiðanleika, einfaldleika og gagnsæi í námsmati.  
Ánægja þessa hóps hefur bein áhrif á árangur viðskiptamarkmiða verkefnisins og mótar framtíðarþróun kerfisins.



### 3.2 Forgangsröðun verkefnis 


### 3.3 Innleiðingarsjónarmið 


## Breytingasaga
<!--
Í stað þess að halda utan um alla commit-sögu er aðeins skráð formleg útgáfa (milestones) með Git tags (merkjum).  
Hver lína í töflunni samsvarar tag (merki) sem hefur verið sett í Git repositoryið.
> 🔖 Revision History er viðhaldið með **Git tags**.  
> Þegar ný útgáfa (t.d. drög eða baseline) er tilbúin, búið til tag í Git (`git tag -a vX.Y -m "message" && git push origin vX.Y`)  
> sem bætir einni línu við í töfluna hér að neðan.
-->
> 🔖 Taflan hér á eftir er búin til með því að keyra shell skrána `updatevisionhistory.sh` í bash terminal
> 
>  `chmod +x updatevisionhistory.sh`
> 
>  `./updatevisionhistory.sh`
> 
>  Ef þú vilt skoða töfluna fyrst til að sjá hvernig hún kemur út geturðu gert eftirfarandi beint úr skelinni 
> `git log -n 5 --pretty=format:"| %an | %ad | %s | %h |" --date=short -n 10 -- VISIONSCOPE.md`


<!-- GIT_HISTORY_START -->
| Author | Date       | Message | Commit |
|--------|------------|---------|--------|
| Ebba Þóra Hvannberg | 2025-09-08 | fyrsta útgáfa og Revision history gert sjálfvirkt | 5b39409 |

<!-- GIT_HISTORY_END -->

> Skoða allt: `git log -- "VISIONSCOPE.md" `
