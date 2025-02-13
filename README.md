# MLOps-project-hw

## 🎯 Célkitűzés
Ez a projekt egy **szentimentanalízis modellt** valósít meg, amely képes különböző szövegek érzelmi töltetének azonosítására (pozitív, negatív, semleges).

## 🛠 Implementáció
A projekt **Python** és a **Transformers** könyvtár segítségével készült. A modell egy **BERT-alapú előre betanított modell** finomhangolásával jött létre. Az adatok a **Kaggle Reddit sentiment analysis datasetből** származnak.

## 📂 Fájlok
- `model_training.ipynb` – A modell betanításának lépései.
- `main.py` – Az API implementációja.
- `config.json` – A modell konfigurációs fájlja.
- `model.safetensors` – A betanított modell súlyai.
- `training_args.bin` – A betanítási paraméterek.

## 📡 API Dokumentáció
Az API végpontjai és azok használata az **`API_documentation.md`** fájlban található.



