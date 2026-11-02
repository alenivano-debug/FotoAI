# FotoAI — Android početni projekt

Profesionalno tamno sučelje za AI uređivanje fotografija, izrađeno u Kotlinu i Jetpack Composeu.

## Trenutno uključeno
- Android aplikacijski projekt
- Odabir fotografije iz galerije
- Početni zaslon s alatima: AI mišići, uređivanje lica, promjena pozadine, uklanjanje objekata, HD kvaliteta i AI generiranje
- Informativni dijalozi za još nepovezanu AI obradu

## Važno
Ovo je početni prototip, a ne gotov AI editor. Gumbi alata zasad prikazuju objašnjenje; stvarna obrada fotografija još nije implementirana. Za nju treba odabrati AI modele/API-je i povezati siguran serverski dio. Ne stavljati privatne API ključeve u Android aplikaciju.

"Besplatno" može značiti besplatno korištenje uz ograničenja, lokalni model na uređaju ili vlastiti server; ne može se unaprijed jamčiti neograničena besplatna AI obrada.

## Kako otvoriti
1. Instaliraj Android Studio na računalo.
2. Odaberi **Open** i otvori mapu `FotoAI_Android`.
3. Pričekaj Gradle Sync.
4. Spoji Android mobitel s uključenim USB debuggingom ili pokreni emulator.
5. Klikni **Run**.

Za izradu APK-a: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.


## Izrada APK-a samo preko mobitela (GitHub Actions)
1. Prijavi se ili otvori besplatan račun na GitHubu.
2. U pregledniku otvori GitHub i napravi novi, prazan repository naziva `FotoAI`.
3. Uploadaj sadržaj ove mape u repository (uključujući skrivenu mapu `.github`).
4. Otvori karticu **Actions**, odaberi **Build FotoAI APK** i pokreni **Run workflow** ako se ne pokrene automatski.
5. Kada je postupak završen, otvori uspješan run, preuzmi artifact `FotoAI-debug-apk` i raspakiraj ga.
6. Instaliraj `app-debug.apk`. Android može tražiti dopuštenje za instalaciju iz preglednika ili aplikacije za datoteke.

Ovo je debug APK za osobno testiranje, nije objavljena Play Store verzija.
