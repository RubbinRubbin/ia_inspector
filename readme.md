# Rilevamento del Grado di Ruggine nel Metallo con YOLO11

![Esempio di rilevamento ruggine](https://img.shields.io/badge/Rilevamento-Ruggine-orange) ![YOLO11](https://img.shields.io/badge/Model-YOLO11-blue) ![Stato](https://img.shields.io/badge/Status-Operativo-green)

## 📋 Descrizione

Questo progetto implementa un sistema di visione artificiale basato su YOLO11 per rilevare e classificare il grado di corrosione (ruggine) su superfici metalliche. Il modello è in grado di identificare diverse categorie di ruggine e fornire informazioni sulla severità della corrosione, utili per la manutenzione predittiva e il controllo qualità industriale.

## 🎯 Obiettivi

- Rilevare la presenza di ruggine in immagini di superfici metalliche
- Classificare il grado di corrosione in diverse categorie di severità
- Fornire un'analisi statistica sulla distribuzione dei gradi di ruggine
- Offrire uno strumento pratico per ispezioni automatizzate

## 🛠️ Tecnologie utilizzate

- **Framework**: PyTorch, Ultralytics YOLO11
- **Linguaggio**: Python 3.x
- **Dataset**: Ottenuto tramite Roboflow
- **Ambiente**: Google Colab con supporto GPU

## 🔍 Funzionalità

- **Training personalizzato**: Addestramento del modello YOLO11 su dataset specifici di immagini di superficie metalliche
- **Rilevamento accurato**: Identificazione precisa delle aree con ruggine nelle immagini
- **Classificazione**: Categorizzazione della ruggine in base al livello di gravità
- **Visualizzazione avanzata**: Rappresentazione grafica dei risultati con statistiche

## 🚀 Come iniziare

### Prerequisiti

- Account Google (per Google Colab)
- Account Roboflow (per accesso al dataset)
- API key di Roboflow

### Esecuzione

1. Aprire il notebook `ia_inspector.ipynb` in Google Colab
2. Seguire le istruzioni nel notebook per:
   - Installare le dipendenze necessarie
   - Configurare l'accesso a Roboflow
   - Scaricare il dataset
   - Addestrare il modello
   - Eseguire il rilevamento su nuove immagini

## 📊 Risultati

Il modello è in grado di rilevare e classificare la ruggine con elevata precisione. I risultati includono:

- Bounding box con indicazione del grado di ruggine
- Confidenza della predizione per ogni rilevamento
- Statistiche sulla distribuzione dei livelli di ruggine
- Mappe di calore per visualizzare le aree maggiormente affette da corrosione

## 📁 Struttura del progetto

- `ia_inspector.ipynb`: Notebook principale con il codice completo
- `README.md`: Questo file descrittivo

## 📚 Riferimenti

- [Documentazione Ultralytics YOLO11](https://docs.ultralytics.com/)
- [Roboflow Universe](https://universe.roboflow.com/)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)

## 📄 Licenza

Questo progetto è distribuito con licenza MIT.

## 👥 Contribuire

Contributi, segnalazioni di bug e richieste di funzionalità sono benvenuti! Sentiti libero di aprire una issue o inviare una pull request.

---

Sviluppato con ❤️ per la preservazione delle strutture metalliche e la prevenzione dei danni da corrosione.