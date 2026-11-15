# ❄️ Šiaurės serverio įsilaužimas

Kalėdų viktorina visai klasei kibernetinio įsilaužimo stiliumi.

**Žaisti:** https://jokubas098.github.io/Siaures-serverio-isilauzimas/

1. Mokytojas spaudžia **„Sukurti žaidimą“** ir projektoriuje parodo 5 skaitmenų kodą.
2. Mokiniai atsidaro tą patį adresą, spaudžia **„Prisijungti“** ir įveda kodą, vardą, avatarą bei slaptažodį.
3. Atsakai teisingai → atidarai serverio dėžę → renki ❄ SniegoCoin arba įsilauži į draugą, atspėjęs jo slaptažodį.

⚠ Mokytojo langas yra žaidimo serveris: neuždarykite jo, kol vyksta žaidimas.

## 👩‍🏫 Mokytojų paskyros (Firebase)

Mokytojai prisijungia su Google arba el. paštu ir gali kurti savo klausimų rinkinius (taip pat įklijuoti iš Excel), juos bendrinti su kolegomis ir žaisti su klase.

- Nustatymai: `index.html` faile `FIREBASE_CONFIG`.
- Saugumo taisyklės: `firestore.rules` (įklijuokite Firebase → Firestore → Rules).
- Mokytojų sąrašas – kolekcija `mokytojai` (dokumento ID = el. paštas mažosiomis raidėmis, laukas `admin: true` administratoriui).
- Kol `FIREBASE_CONFIG` neįrašytas, žaidimas veikia be prisijungimo su įmontuotais Kalėdų klausimais.
