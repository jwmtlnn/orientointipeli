# Orientointipeli
Tekoälyavusteisesti toteutettu selaimessa toimiva, yhden HTML-tiedoston opetussimulaattori takymetrin orientoinnista vapaalle asemapisteelle (suorakulmaiset tasokoordinaatit, ortometrinen korkeus ja gooni-kulmayksikkö).
## Työvaiheet ja ominaisuudet
- Tasaus & Sää: Kojeen tasaus kolmella jalkaruuvilla sekä sääkorjauksen (ppm) määritys.
- Liitospisteet: Tunnettujen kiintopisteiden syöttö tai tuonti maastokortilta.
- Asemapiste: Vapaan asemapisteen tunnuksen (ASP) ja kojekorkeuden ($i$) asetus.
- Mittaus: Karkea tähtäin, optinen mittauskaukoputki, Autolock (ATR), prismallinen (IR) ja pintamittaus (DR) sekä vapaaehtoinen mittaus kahdessa kojeasennossa (I- ja II-asento).
- Tulokset: Pienimmän neliösumman tasoituslaskenta, asemapisteen koordinaatit, kiertymä ($t_0$) sekä pisteittäisten jäännösvirheiden analyysi.
## Muutosloki
- v0.6 (2026-11-20): Sovelluksen nimeksi Orientointipeli, Tietoja-ikkuna, kaksivaiheinen kojeasennon vaihdon animaatio, jalustan painumisen ja kompensaattorin toiminnan palaute, kartoitussauvat ilman tukijalkoja sekä karkeasuuntauksen ja Autolockin hienosäätö.
- v0.5: Täysi offline-yhteensopivuus, vapaaehtoinen mittaus kahdessa kojeasennossa (I+II), portaittainen virhediagnoosi, jalustan painuminen talviharjoituksessa, $360^\circ$-prisman vakio (-11,3 mm) sekä 1,5 mgon tähtäysraja.
- v0.4: Käsitteistön yhtenäistäminen Pasi Laurilan (2012) oppikirjaan, heijastintarran ja heijastimettoman tarran erottelu sekä Autolockin epäkeskinen lukittuminen heijastintarraan.v0.3: Välitön tallennus (F2) jo mitatulle etäisyydelle, pyöröprisman vakio -30,0 mm ja tarratähyksen vakio 0,0 mm.
- v0.2: Kojeen kolmiruuvinen tasaus, ASP-tunnukset, tuntemattomat pisteet (?) kartalla ennen mittausta/laskentaa, karkea tähtäin ja kaukoputki, kartoitussauvat, Autolock (ATR) valelukitusvaaralla sekä 2 sekunnin etäisyysmittausviive äänimerkein.
- v0.1: Ensimmäinen prototyyppi: 5-vaiheinen orientointiprosessi, kaukoputkinäkymä, yleiskartta, fysikaalinen virhemalli ja kolme harjoitusskenaariota.
