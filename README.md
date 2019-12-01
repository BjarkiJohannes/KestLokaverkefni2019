# KEST1VL Lokaverkefni H19
Verkefnið gildir *20%* af lokaeinkunn

Vinnið saman í tveggja manna hópum. Haldið utan um verkefnið á [github](https://github.com).

Búið til lokaða geymslu (*e. private repository*) sem í eiga að vera eftirfarandi skjöl (snyrtilega upp sett með markdown þar sem það á við):
-   README.md, kynning á verkefninu, rökstuðningurinn og leiðbeiningarnar sem talað er um neðar á síðunni.
-   skipanir.sh, þær skipanir sem þið notuðuð til að leysa verkefnið.
-   Dagbækur (.md skrár), ein fyrir hvorn nemanda. Hér haldið þið utan um hvað þið gerðuð í verkefninu.

Skilið svo hlekknum á geymsluna ykkar inn á Innu og bjóðið kennaranum ykkar aðgang (*e. collaberator*) að geymslunni.

---
# Jólaskór ehf.
Fyrirtækið *Jólaskór* hefur beðið ykkur um að setja upp lítið linux tölvukerfi fyrir sig. Fyrirtækið er mjög gamalt og sérhæfði sig á árum áður í þjófnaði og eignaspjöllum en í dag sérhæfir það sig í setja góðgæti og leikföng í skó ásamt því að starfsmennirnir koma fram á hinum ýmsu skemmtunum.

Í dag er 12 starfsmenn á launaskrá fyrirtækisins en fjölgar fljótlega um 2.

## Starfsmannalisti og deildaskipting
Nafn | Hópar/Deildir | Notendanafn | Lykilorð
--- | --- | --- | --- 
Grýla | allir, gjafadeild, leikdeild, songdeild | gryla | pass.123
Stekkjastaur | allir, gjafadeild | staur | pass.123
Giljagaur | allir, gjafadeild | gaur | pass.123
Stúfur | allir, gjafadeild | stufur | pass.123
Þvörusleikir | allir, gjafadeild | thvari | pass.123
Pottaskefill | allir, gjafadeild | skefill | pass.123
Askasleikir | allir, gjafadeild | askur | pass.123
Hurðaskellir | allir, gjafadeild | skellir | pass.123
Skyrgámur | allir, leikdeild | gamur | pass.123
Bjúgnakrækir | allir, leikdeild | bjugi | pass.123
Gluggagægir | allir, leikdeild | gluggi | pass.123
Gáttaþefur | allir, songdeild | gatti | pass.123
Ketkrókur | allir, songdeild | krokur | pass.123
Kertasníkur | allir, songdeild | kerti | pass.123

### Val á stýrikerfi
Það fyrsta sem þarf að gera er að velja hvaða linux þið ætlið að velja. Kynnið ykkur þessi hér fyrir neðan og veljið svo eitt til að setja upp (rökstyðjið val ykkar (ca. 200 orð)).
- Ubuntu, https://ubuntu.com
  - Kubuntu, https://kubuntu.org
  - Lubuntu, https://lubuntu.net
  - Ubuntu MATE https://ubuntu-mate.org
- elementary os, https://elementary.io
- Mint, https://www.linuxmint.com til í ýmsum útgáfum

### Rökstuðningur Linux

Þetta eru helstu ástæður afhverju við völdum Ubuntu:

fyrsta ástæðan afhverju við völdum Ubuntu er vegna þess að það er stýrikerfið sem við kunnum mest á af öllum vegna þess að það er fyrsta stýrikefrið sem við þurftum að kunna nota og þersvegna er best að halda sér við hluti sem maður kannast við. Önnur ástæða afhverju Ubuntu er þægilegt er venga þess að Ubuntu er mjög user-freidnly sem þýðir að þótt þú kunnir ekki neitt að forrita eða á tölvur muntu samt geta notað og skilið Ubunutu vel. Ubunutu er frítt og allar nýjar útgáfur sem munu koma út á Ubunutu mun halda áfram að vera frítt sem er alltaf gott og Ubunutu er líka mikið betur varin heldur en til dæmis windows frá vírusum og slíku. Ubunutu er með mjög mikið af stillingum til að breyta öllu eins og þér hentar og Ubunutu virkar á flestum vélum sama hversu góðir íhlutir eru í tölvuni þinni, eina sem Ubunutu krefst er að þú sért með minnstalægi 512MB RAM og 5Gb á disknum þínum sem er mikið minna en önnur stýrikerfi þurfa. Í Ubunutu eru líka fullt af núðegar uppsettum öppum og ef þú villt fleiri geturu líka fundið fullt af fríum öppum og software-i sem þú getur fengið með því að smella bara á install og þá ert þú kominn með það inná vélina þína. Forritarar elska líka Ubuntu því það er open source sem þýðir að þeir geta breytt og forritað Stýrikerfið eins og þeim hentar sem er mjög hentugt því ekki mörg stýrikerfi eru open source eins og Ubuntu, tökum til dæmis Windows sem dæmi. Windows er closed source software sem þýðir að það er ekki leyft fólki að breyta til og forrita eins og þeim hentar. Þetta eru helstu ástæður afhverju við völdum að nota Ubunutu yfir öðrum stýrikerfum


Setjið svo stýrikerfið upp á VirtualBox (hjá báðum hópmeðlimum). Uppfærið stýrikerfið og setjið upp viðeigandi forrit t.d. þróunarumhverfi fyrir Python. Sejið upp viðeigandi þema (e. desktop theme) fyrir fyrirtækið, sjá t.d. [hér](https://itsfoss.com/christmas-linux-wallpaper/).

### Hópar
Búið til hópana *allir*, *gjafadeild*, *leikdeild* og *songdeild*.

### Möppur og réttindi
Búið til möppuna **jolagogn** á skráarkerfis rótina (/) og svo möppurnar **Sameign**, **Gjafadeild**, **Leikdeild** og **Songdeild** í **jolagogn**. Stillið réttindin á möppunum þannig að allir notendur hafi les og skrifréttindi ásamt keyrsluréttindum á **Sameign** möppuna, þeir sem eru í *gjafadeild* hópnum hafi les og skrifréttindi ásamt keyrsluréttindum á **Gjafadeild** möppuna og svo sambærilegt fyrir **Leikdeild** og **Songdeild**. Tryggið að aðrir en þeir sem eru í réttum hópum hafi ekki aðgang að möppunum. Tryggið einnig að notendur geti eingöngu eytt sínum skrám úr ofantöldum möppum.

### Notendur
Búið til notendurna og setjið notendurna í rétta hópa. Tryggið að þegar notendurnir eru búnir til að fullt nafn sé skráð á þá, þeir fái bash skelina, heimasvæði sé búið til fyrir þá og að í heimasvæði hvers notenda séu möppurnar **Vinna** og **Leikir** auk vísunar (e. link) á möppurnar sem eru í **jolagogn** möppunni. Tryggið að notendur þurfi að breyta um lykilorð þegar þeir skrá sig inn í fyrsta skipti.

### Annað
Askasleikir og Hurðaskellir hefja ekki störf alveg strax, tryggið því að ekki sé hægt að skrá sig inn sem þeir með því að læsa/loka þeirra aðgangi.

Grýla þarf að geta notað `sudo` skipunina, aðrir notendur mega ekki nota sudo skipunina.

Skrifið leiðbeiningar fyrir Grýlu þar sem þið útskýrið hvernig á að búa til notendur og setja í rétta hópa ásamt því að útskýra hvernig hún getur virkjað aðganga þeirra starfsmanna sem hefja ekki störf strax.

### Leiðbeiningar Fyrir Grýlu

Hæ grýla! hérna eru leiðbeiningarnar sem þú baðst um til að stofna notendur og hópana.

Til að búa til user þarftu að skrifa commandið: adduser (og svo nafn á notenda). Til þess að adda useri í group þarftu að skrifa: usermod -a -G (og svo nafn á hópinum) (og svo nafn á notenda). Til þess að virkja notenda þarftu að skrifa: usermod -U -e (nafn notenda).
