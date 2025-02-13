# API Dokumentáció

## Végpontok

### /predict
- **Módszer**: POST
- **Leírás**: Szöveg szentimentjének előrejelzése.
- **Input**:
  - `text`: A szöveg, amelynek szentimentjét szeretnénk előrejelezni.
- **Output**:
  - `sentiment`: Az előrejelzett szentiment (posititve, negative, neutral).

## Training Set és LLM Promptok Verziózása
A training set és az LLM promptok verziózásához a Git verziókezelő rendszert használjuk. Minden módosítás külön branch-en történik, és a végleges változatok a master branch-be kerülnek.

## Forráskódok és Modellek Tárolása
A forráskódok és a modellek a GitHub tárhelyen vannak tárolva. A modell súlyai szintén elérhetők a Google Drive-on és az AWS S3 tárhelyén.

## Modell Monitorozása és KPI-k
A modell monitorozása a TensorBoard segítségével történik. Az alábbi KPI-kat figyeljük:
- **Loss**: Az edzési és validációs veszteség.
- **Accuracy**: Az edzési és validációs pontosság.
- **F1-Score**: Az osztályozási teljesítmény mérésére.
- **Confusion Matrix**: A valódi és előrejelzett címkék összehasonlítása.
