---
title: CAD tiedoston konvertointi
date: 2017-11-26 00:00:00 +0000
keywords:
- cad
- converter
- autocad
categories: [sovellukset]
tags: [cad, dwg, zamzar, convertcadfiles, cloudconvert, draftsight]
banner: "img/banners/banner-how-to-convert-cad-files.png"

---
# DWG:n konvertointi PDF-dokumentiksi

Suunnittelijat käyttävät yleensä työkaluja, kuten AutoCAD:ä, jotka tuottavat .DWG tiedostoja. Erityisesti eri suunnittelijoiden välillä suunnitelmien siirtäminen DWG muodossa vähentää merkittäväsi työvaiheita ja säilyttää mitat kohdallaan. Koska kaikki meistä eivät kuitenkaan ole arkkitehtejä eivätkä omista, tai halua opetella käyttämään sovellusta jolla käsitellä näitä tiedostoja, on välillä helpompi muuntaa .DWG tiedostot toiseen muotoon kuten PDF tai PNG tiedostoksi.

Internetistä löytyy useita toki useita sovelluksia joilla konvertoida .DWG tiedostoja joista toiset toimivat paremmin kuin toiset. Koska ajatus on nyt tehdä asiat helposti, katsotaan vain palveluita joita voi käyttää pelkällä selaimella - asentamatta mitään omalle koneelle.

## Testitiedosto

Testikuvaksi on tässä otettu AutoDesk:n [esimerkki kirjastosta](https://knowledge.autodesk.com/support/autocad/downloads/caas/downloads/content/autocad-sample-files.html) kuva [Architectural - Annotation, Scaling and Multileaders](http://download.autodesk.com/us/samplefiles/acad/architectural_-_annotation_scaling_and_multileaders.dwg). Tiedoston alkuperäinen koko on `189KB. 

### Yksityiskohta alkuperäisestä

CAD ohjelmalla (DraftSight) katsottuna yksityiskohta portaista näyttää seuraavalta. Yksi kriteeri konversion onnistumiselle on se että suunnitelmaa voidaan tarkastella läheltä ilman että yksityiskohdat tai tekstit sumentuvat.

{{< figure src="/img/cad_original_selection.png">}}

## Convertcadfiles.com

[![convertcadfiles.com](https://res.cloudinary.com/rakentaminentekniikka/image/upload/c_scale,w_600/v1511678740/convertcadfiles-com_macbookgrey_front_tyrwme.png)](https://www.convertcadfiles.com/)

Sivusto oli valitettavasti työn alla joten täytyy palata siihen myöhemmin.

---

## ZAMZAR

[![zamzar.com](http://res.cloudinary.com/rakentaminentekniikka/image/upload/c_scale,w_600/v1511679202/zamzar-com_macbookgrey_front_kwp9ll.jpg)](https://www.zamzar.com/)

*ZAMZAR* pyytää sähköpostiosoitteen jonne lähettää linkin jolla konvertoidu tiedosto voidaan ladata. Käyttökokemus on sekava, linkkejä on useita ennen kun tiedostoon pääsee käsiksi. Lopulta PDF tipahti omalle koneelle. Konvertoidun tiedoston koko oli `1.3MB` mikä ei lupaa hyvää. PDF lukija lataa kuvaa hitaasti ja vaiheittain. Sen sijaan että ZAMZAR olisi konvertoinut CAD tiedoston polut vastaaviksi PDF:ssä, on ZAMZAR muuttanut CAD tiedoston kuvaksi ja käärinyt sen PDF:n sisään. Lopputulosta ei voi enään zoomata ilman että kuvanlaatu ja yksityiskohdat kärsivät. Alkuperäinen yksityiskohta näyttää nyt tältä:

### ZAMZAR lopputulos
{{< figure src="/img/zamzar_detail.png">}}

---

## Cloudconvert

[![cloudconvert.com](/img/cloudconvert_site_macbook.png)](https://www.couldconvert.com/)

*Cloudconvert*:n käyttöliittymä on selkeä ja ammattimainen. DWG tiedostojen lisäksi Cloudconvert muuntaa yhden jos toisenkin formaatin haluttuun muotoon.

DWG tiedosto raahataan sivulle jonka jälkeen pitää huomata painaa sivun alareunasta löytyvää punaista "Start Conversion" painiketta. Kun konvertointi on valmis, lopputuloksen voi ladata suoraan koneelle mikä on todella näppärää sähköpostilinkkien sijaan. 

Konvertoitu tiedosto oli pieni, kooltaa `253KB`, eli vain hieman alkuperäistä suurempi. PDF ohjelma avaa tiedoston nopeasti eikä kuvanlaatu kärsi zoomatessa joten Cloudconvert on säilyttänyt alkuperäisen informaation polkumuodossa.

### Cloudconvert yksityiskohta
{{< figure src="/img/cloudconvert_detail.png">}}

Mutta kun katsotaan alkuperäistä dokumenttia kokonaisuudessaan ja Cloudconvert:n PDF versiota, niissä on melko paljon eroa.

{{< figure src="/img/cad_original_full.png" caption="Alkuperäinen">}}
{{< figure src="/img/cad_cloudconvert_full.png" caption="Cloudconvert">}}

Cloudconvert siis sekoitti hieman alkuperäisen DWG tiedoston asemointia ja kadotti metatietoja.


## Lopputulos

Vielä toistaiseksi en ole löytynyt palvelua joka pystyisi konvertoimaan DWG tiedoston PDF:ksi tehden sen yhtä hyvin kuin CAD ohjelmat mutta haku jatkuu. Cloudconvert on toistaiseksi testatuista kuitenkin paras vaihtoehto.




