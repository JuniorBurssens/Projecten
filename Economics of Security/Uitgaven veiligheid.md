---
title: "Uitgaven veiligheid"
author: "Junior Burssens"
date: "20-03-2015"
output: pdf_document
csl: apa.csl
bibliography: Economics of Security.bib
---

# Inleiding en probleemstelling

**Gedeelte Stijn**

# Literatuur

Een recent overzicht van de determinanten van uitgaven aan politie in de V.S. wordt gegeven door Zhao et al. [-@zhao_budgetary_2010]. Hierbij wordt een onderscheid gemaakt tussen drie types van voorspellers: de bestuurscultuur, socio-economische factoren en een incrementele aanpak. We hanteren dezelfde structuur in dit literatuuroverzicht, aangevuld met een set geografische variabelen.

Politie-uitgaven kunnen op twee manieren geoperationaliseerd worden. Zhao et al. [-@zhao_budgetary_2010] gebruiken het jaarlijks procentueel aandeel uitgaven voor politie in de totale gemeente-uitgaven als afhankelijke variabele in een panel schatting. Deller et al. [-@deller_model_2006] tonen aan dat wanneer het totale budget van een gemeente wijzigt er verschillen in de onderlinge verhoudingen van de uitgaven optreden en dat de budgetten voor politie en brandweer vrij constant blijven. Men roept dus het risico wijzigingen in het totale budget te interpreteren als wijzigingen in de uitgaven aan politie. Andere auteurs maken gebruik van de per capita uitgaven voor politie [@guillamon_electoral_2013,@ruddell_determinants_], wat makkelijker interpreteerbare resultaten genereert.

De variabelen die de bestuurscultuur vertegenwoordigen waren in het onderzoek van Zhao et al. [-@zhao_budgetary_2010] de slechtste voorspellers. Sharp [-@sharp_back_2014] pleit voor de inclusie van meer politieke variabelen in het onderzoek naar lokale politie. Een dichotome variabele met betrekking tot het aantal deelnemers in de coalitie werd reeds gebruikt in een panel GMM schatting naar de invloed van verkiezingen op uitgaven voor lokale politie in 322 Spaanse gemeenten gedurende de periode 2001-2008 [@guillamon_electoral_2013]. De resultaten onderschrijven de veronderstelling dat kleine coalities meer uitgeven aan politie. In de context van de Vlaamse politiezones is het de politieraad en het politiecollege die beslissen over het budgettair en financieel beheer van de zone^[MO PLP 53 van 3 december 2014 betreffende de onderrichtingen voor het opstellen van de politiebegroting voor 2015 ten behoeve van de politiezones, *B.S.*, 24 december 2014]. De coalitiecontext speelt hier onder vorm van de één- of meergemeentezones, waarbij er al dan niet een compromis tussen de betrokken gemeenten moet gezocht worden.

De incrementele aanpak, geoperationaliseerd door de veranderingen in de proportie aan uitgaven voor de brandweer, verklaarde de meeste variatie [@zhao_budgetary_2010]. De verandering in het aandeel aan politie-uitgaven hangt duidelijk zeer sterk samen te hangen met andere onmisbare publieke diensten. Ook andere auteurs [@kelejian_suggested_1993;@guillamon_electoral_2013] wijzen op de inertie van uitgaven voor politie. Zowel vanuit de historiek aan eigen uitgaven, als van de uitgaven in het verleden door naburige gemeenten. Wanneer men dit soort vertraagde variabelen opneemt in een regressie met cross-sectionele gegevens, ontstaan er methodologische problemen rond autocorrelatie van de storingstermen, waardoor de resultaten van het onderzoek onbetrouwbaar worden [@gujarati_basic_2004, pp. 441-505]. Bovendien biedt deze aanpak weinig inzicht in de structurele elementen die de uitgaven voor politie bepalen, vermits deze weinig tot niet wijzigen over de jaren.

De diversiteit aan socio-economische variabelen resulteert in een even uiteenlopende verklaringskracht naargelang welke variabele in overweging wordt genomen. Zhao et al. [-@zhao_budgetary_2010] konden niet aantonen dat de met 1 jaar vertraagde criminaliteitsgraad een invloed had op de uitgaven voor politie. Opvallend is wel dat in deze modellen een maat voor de aanwezigheid van 'minderheden' (zwarten, hispanics) significant verband houdt met de uitgaven. In een cross-nationale studie naar geweld en druggebruik bij jongeren in een multi-etnische setting signaleren Benschop et al. [@benschop_different_2006] de problemen met het overnemen van de Amerikaanse definitie van etniciteit en de gevolgen van die definitie voor het verband met de onderzochte criminaliteitsvariabelen. 
Daarom nemen de modellen in voorliggend onderzoek criminaliteitsindicatoren op, maar gerichter opgesplitst naar de drie beschikbare fenomenen, diefstal en afpersing en misdrijven tegen de lichamelijke integriteit, alsook de algemene cijfers voor de gemeente. 

Het onderzoek van Zhao et al. [-@zhao_budgetary_2010] vindt een significante invloed van de proportie mannen in een gemeente, maar stelt dat deze variabele vooral het aantal jongeren wil vatten. In de literatuur met betrekking tot de verklaring van lokale uitgaven is de demografische samenstelling qua leeftijd een belangrijk element, vermits overheidsdiensten worden afgestemd op leeftijdscategorieën [@borge_partial_2014]. Het aandeel ouderen en jongeren in de bevolking werd reeds gebruikt in een Amerikaans cross-sectioneel onderzoek naar het effect van etnische fragmentatie op de per capita politie-uitgaven in 2000 [@ajilore_ethnic_2011].^[Het onderzoek past 2SLS toe, vanwege endogeniteit tussen criminaliteit en politie-uitgaven, maar wij vertragen criminaliteit met 1 jaar dus het probleem stelt zich hier niet.]
De uitgaven van een gemeente worden uiteraard ook beïnvloed door hun inkomsten. Voor de Vlaamse gemeenten vinden die hun oorsprong voornamelijk in de opcentiemen bij de inkomstenbelasting en de onroerende voorheffing. Variabelen met betrekking tot deze belastingen kunnen daarom ook gerelateerd worden aan de uitgaven voor politie. Het inkomensniveau van de bevolking geeft wisselende resultaten in de literatuur. Zo vinden Zhao et al. [-@zhao_budgetary_2010] geen significant verband, terwijl de indicator voor inkomen bij Guillamón et al. [-@guillamon_electoral_2013] net een heel sterk effect genereerde.
De economische indicatoren werkloosheid en inkomen waren niet significant, maar het aandeel huiseigenaars was dat wel [@zhao_budgetary_2010]. Deze laatste vormt een indicator voor fiscale stabiliteit via de onroerend goed belasting, terwijl de twee eersten betrekking hebben op de potentiële inkomsten uit de inkomensbelasting.
In hun jaarlijkse analyse van de politie- en OCMW-financiën groepeert Belfius [@dessoy_sociaaleconomische_2007] de Vlaamse gemeenten in 16 sociaaleconomische clusters die een vergelijkbaarheid van de financiële gegevens van de gemeenten vergemakkelijkt. Deze typologie wordt opgenomen in het model onder vorm van dummy-variabelen, met als referentie de landelijke gemeenten. Internationaal zijn er slechts enkele studies [@kelejian_suggested_1993;@rincke_commuting_2010] die ruimtelijke effecten expliciet modelleren in het onderzoek. Dit zou ons hier evenwel te ver leiden, zeker gezien de complexiteit met betrekking tot de correcte implementatie [@rincke_commuting_2010]. Niettemin worden deze effecten zoveel mogelijk ondervangen met een aantal dichotome variabelen die de nabijheid van grenzen aangeven, alsook met een indicator die aangeeft met hoeveel gemeenten men in de politiezone zit.

# Methodologie

## Model

WERKINGSUITGPERCAPITA2013 = c + SEVAR + GEOVAR + CRIMVAR

AANDEEL UPZINTOTUIT2013 = c + SEVAR + GEOVAR + CRIMVAR

De modellen bevatten steeds alle Socio-economische variabelen (SEVAR) en Geografische kenmerken (GEOVAR). Voor elke criminaliteitsvariabele (CRIMVAR) werd een aparte schatting uitgevoerd.

## Variabelen

### Afhankelijke variabelen

WERKINGSUITGPERCAPITA2013
:    De werkingsuitgaven per capita van de gemeente voor politie in 2013

AANDEEL UPZINTOTUIT2013
:    Het aandeel van de uitgaven politiezone in het totaal van de uitgaven van 2013 voor de gemeente

### Socio-economische variabelen (SEVAR)

NBICAP10
:    Netto belastbaar inkomen per capita voor 2010

unempl11
:    Werkloosheidsgraad (werklozen/actieve bevolking) in 2011

DSALDOCAP1112  
:    Verandering in het saldo (overschot of tekort) van de gemeente-uitgaven van 2011 naar 2012

min20j13
:    Het aantal -20-jarigen in 2013

plus64j13
:    Het aantal +64-jarigen in 2013

voetbal
:    De gemeente heeft een ploeg in het eersteklassevoetbal

### Geografische kenmerken (GEOVAR)

grensnl
:    De gemeente grenst aan Nederland

grensfr
:    De gemeente grenst aan Frankrijk

taalgr
:    De gemeente ligt aan de taalgrens

DCENTRG
:    De gemeente is een centrumgemeente

DAGGLOMG
:    De gemeente is een agglomeratiegemeente (volgens de Belfius indeling)

DECONACTG
:    Gemeenten met concentratie van economische activiteit

DTOERISTG
:    De gemeente is een toeristisch aantrekkelijke gemeente

DWOONG
:    De gemeente is een woongemeente

AGEMPERZONE
:    Het aantal gemeenten in de politiezone

### Criminaliteitsvariabelen (CRIMVAR)^[waarom 3 jaar vertraagd? Verwachten we een onrechtstreeks effect via bvb. migratie? Is 1 jaar vertraging getest?]

EIGM2010
:    De eigendomscriminaliteit in 2010 voor de gemeente

DAM2010
:    De diefstallen en afpersingen in 2010 voor de gemeente

LINTM2010
:    De misdrijven tegen de lichamelijke integriteit in 2010 voor de gemeente

som2010
:    Alle bovenstaande misdrijven samen in 2010 voor de gemeente

\newpage

# Bibliografie