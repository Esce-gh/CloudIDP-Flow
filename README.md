# CloudIDP Flow ☁️📄

Chmurowa platforma automatyzacji procesów biznesowych (BPM) zintegrowana z modułem Inteligentnego Przetwarzania Dokumentów (IDP). 

Projekt umożliwia analitykom biznesowym (w podejściu low-code/no-code) modelowanie procesów, które automatycznie klasyfikują i ekstrahują dane z nieustrukturyzowanych dokumentów (faktury, skany, maile) przy użyciu modeli (V)LLM, a następnie przekazują je do zewnętrznych systemów ERP/CRM.

## 🛠 Technologie
* **Middleware / BPM:** n8n / Camunda (środowisko modelowania)
* **AI / Ekstrakcja danych:** Modele (V)LLM (OCR, NLP, ML)
* **Infrastruktura:** Środowisko chmurowe (np. AWS/Azure)
* **Integracje:** Python / Node.js (customowe komponenty)

## 📂 Struktura repozytorium
* `/src` - kody źródłowe własnych węzłów (custom nodes) i skryptów integracyjnych API.
* `/workflows` - wyeksportowane modele procesów biznesowych (pliki BPMN lub JSON).
* `/docs` - skrócona dokumentacja techniczna i instrukcje wdrożeniowe.
* `/tests` - skrypty do ewaluacji jakości modelu (V)LLM i testów integracyjnych.

## 🚀 Szybki start
1. Sklonuj repozytorium:
   ```bash
   git clone [https://gitlab.domain.com/cloudidp-flow.git](https://gitlab.domain.com/cloudidp-flow.git)