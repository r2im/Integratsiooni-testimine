Integratsiooni-testimine
========================

TEOORIA (20 minutit)

__Tarkvara arendamine__ on väga üldistatult öeldes üks suur tõlkimise protsess, kus kliendi nõudeid sammhaaval süstematiseerides saab valmis arvuti protsessorile ettenähtud tegevustik. Koskmudeli (waterfall) järgi on testimine üks etapp tarkvara arenduses, aga ühe rohkem liigutakse selle poole, et testimine on arendusest võimalikult eraldiseisev tegevus. Samaväärselt nagu testitakse koodikirjutamist, tuleb ka testida analüüsi, arhitektuuri, disaini ja paigaldamist.

__Tarkvara testimine__ on informatsiooni kogumine testitava rakenduse kvaliteedi kohta huvitatud osapoolte (stakeholders) jaoks [Wikipedia]. Testimise juures on väga tähtis, mida testitakse, kuidas testitakse ja kelle jaoks tulemused tähtsad on (näited). Sama asja on võimalik mitmeti testida ja välja tuua erinevaid mõõdikuid. Testimise põhieesmärk on leida vigu - test on edukas, kui see avastas vea tarkvaras.

Tüüpiline arusaam testimisest on, et tuleb avastada võimalikult palju programmeerija tehtud vigu. Tarkvara arenduse alguspäevadel testimine ainult nii käiski. Paljudes ettevõtetes on tõenäoliselt siiani tarkvara arendus ülesehitatud nii, et testijad testivad puhtalt programmeerijate tööd. Uusi meetodeid ja tehnoloogiaid tuleb pidevalt peale (viimasel ajal küll vähem), aga erinevatel põhjustel hinnatakse nö vanakooli testimist kõige paremaks (kõik hinnangud on autori sisetunde järgi). Peamine põhjus on, et kliendile ei ole piisavalt hästi osatud selgeks teha edevamate testimistehnoloogiate vajadust - klient ei saa aru, mille eest ta maksab. Näiteks ühiktestide kirjutamine teeb rakenduse arendamise alguses vähemalt 2 korda kallimaks.

Üha enam hinnatakse testimise vajalikkust ja investeeritakse sellese üha rohkem. “Moodsas” ettevõttes käib tarkvara testimine paralleelselt tarkvara arendusega. Uue rakenduse või rakenduse osa arendamist alustavad tarkvara analüütik ja testimise analüütik koos. Esimese roll on klassikaline, teise roll on tarkvara analüüsi põhjal testplaani koostamine ja mingil määral ka nõuete analüüsi testimine.

__Testplaan on eeskiri__, mille järgi viiakse läbi rakenduse testimine. Eelkõige kirjeldab testplaan ära, mida, millal, kuidas ja kui palju testida. Viimast momenti on kõige keerulisem hinnata, aga see määrab kõige rohkem, kui kalliks läheb rakenduse arenduse mingi etapp. Testides liiga vähe, on suurem tõenäosus, et lõppkasutaja leiab vea. Testides liiga palju, kulutab liialt arenduse ressurssi.


__Integratsiooni testimine__ tähendab eraldiseisvate süsteemi komponentide suhtlemise testimist. Veebirakendust puhul räägitakse integratsiooni testimisest kui viisist, et kindlaks teha, kas Model-, View- ja Controllerkomponendid teevad koos seda, mida neilt eeldatakse. Seda pilti natuke kaugemalt vaadates testitakse, kas mingi HTTP päring annab soovitud HTTP vastuse.

PRAKTIKA JA ARUTELU (60 minutit)

* Ruby 1.9.3, Rails 3.2, MiniTest, Capybara
  * Mis on MiniTest?
  * Mis on Capybara?
  * Mis on alternatiivid?
* Nullist näidisrakenduse alustamine ja seadistamine
* Lihtsa rakenduse arendamine
* Rakenduse peal võimalikult erinevate stsenaariumite testimine

