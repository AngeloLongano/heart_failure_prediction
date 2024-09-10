# Heart Failure Prediction

Le malattie cardiovascolari (CVD) sono la prima causa di morte a livello globale, con circa 17,9 milioni di vite all'anno, pari al 31% di tutti i decessi nel mondo. Quattro decessi su 5 per CVD sono dovuti ad attacchi di cuore e ictus, e un terzo di questi decessi avviene prematuramente in persone di età inferiore ai 70 anni. L'insufficienza cardiaca è un evento comune causato da CVD e questo set di dati contiene 11 caratteristiche che possono essere utilizzate per prevedere una possibile malattia cardiaca.

Le persone affette da malattie cardiovascolari o ad alto rischio cardiovascolare (per la presenza di uno o più fattori di rischio come ipertensione, diabete, iperlipidemia o malattie già conclamate) hanno bisogno di una ßdiagnosi e di una gestione precoci, per le quali un modello di apprendimento automatico può essere di grande aiuto.

## Attributi del dataset

- Age: età del paziente [anni]
- Sex: sesso del paziente 
    - M: Maschio
    - F: Femmina
- ChestPainType: tipo di dolore toracico 
    - TA: Angina* Tipica
    - ATA: Angina Atipica
    - NAP: Dolore Non Anginoso
    - ASY: Asintomatico
- RestingBP: pressione sanguigna a riposo [mm Hg]
- Cholesterol: colesterolo sierico [mg/dl]
- FastingBS: glicemia a digiuno 
    - 1: se FastingBS > 120 mg/dl
    - 0: altrimenti
- RestingECG: risultati dell'elettrocardiogramma a riposo 
    - Normal: Normale
    - ST: presenza di anomalia dell'onda ST-T (inversioni dell'onda T e/o elevazione o depressione del segmento ST di > 0,05 mV)
    - LVH: mostra probabile o definita ipertrofia ventricolare sinistra secondo i criteri di Estes
- MaxHR: frequenza cardiaca massima raggiunta [valore numerico tra 60 e 202]
- ExerciseAngina: angina* indotta da esercizio 
    - Y: Sì
    - N: No
- Oldpeak: oldpeak = ST [valore numerico misurato in depressione]
- ST_Slope: inclinazione del segmento ST durante l'esercizio 
    - Up: inclinato verso l'alto
    - Flat: piatto
    - Down: inclinato verso il basso
- HeartDisease: classe di uscita 
    - 1: malattia cardiaca
    - 0: Normale

_*Il termine Angina Pectoris deriva dai termini latini Angina=dolore e Pectoris=petto. Si tratta, in effetti, di una sindrome caratterizzata da dolore in regione retrosternale, talvolta irradiato al lato ulnare del braccio sinistro e alle spalle. [wiki](https://www.my-personaltrainer.it/cardiopatia-ischemica/angina.html)_

## Sorgente del dataset
Questo set di dati è stato creato combinando diversi set di dati già disponibili in modo indipendente ma non combinati prima. In questo set di dati, 5 set di dati sul cuore sono combinati su 11 caratteristiche comuni, il che lo rende il più grande set di dati sulle malattie cardiache finora disponibile per scopi di ricerca. I cinque set di dati utilizzati per la sua cura sono:

Cleveland: 303 osservazioni
Ungheria: 294 osservazioni
Svizzera: 123 osservazioni
Long Beach VA: 200 osservazioni
Set di dati Stalog (Heart): 270 osservazioni
Totale: 1190 osservazioni
Duplicati: 272 osservazioni

Set di dati finale: __918 osservazioni__

# Citation
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.