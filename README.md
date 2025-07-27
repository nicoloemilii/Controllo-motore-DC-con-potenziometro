# Controllo Motore DC con Potenziometro

## 🔧 Descrizione del progetto
Questo progetto ha lo scopo di controllare la velocità di un motore DC utilizzando un potenziometro e un PLC Siemens S7-1200. Il controllo della velocità avviene tramite un segnale PWM (Pulse Width Modulation) generato dal PLC, che agisce su un transistor Darlington BDX53BG per regolare l'alimentazione del motore.

## 🧠 Principio di funzionamento
- Il potenziometro invia un valore analogico al PLC.
- Il PLC campiona il valore, lo converte e genera un segnale PWM proporzionale.
- Il segnale PWM comanda il transistor BDX53BG che regola la velocità del motore.
- Un pulsante tattile PCB consente di accendere e spegnere il motore.

## ⚙️ Componenti utilizzati
- PLC Siemens S7-1200 (6ES7215-1AG40-0XB0)  
- Alimentatore Siemens 6EP1332-1SH71  
- Motore DC JGB37-520 (12V, 45 RPM)  
- Regolatore di tensione LM7812  
- Transistor Darlington BDX53BG  
- Diodi LED (2 verdi, 2 rossi)  
- Diodo 1N4007  
- Potenziometro 10kΩ  
- Resistori vari (1kΩ, 3.3kΩ)  
- Condensatori (0.33µF, 0.1µF)  
- Pulsanti PCB  
- Breadboard  
- Morsetti da quadro elettrico a vite

## 🖥️ Software utilizzato
- **TIA Portal**: per la programmazione del PLC in linguaggio Ladder (LD)

## 🧩 Schema elettrico e diagrammi
Sono allegati nella documentazione originale della relazione (vedi immagini o PDF).

## 🔄 Possibili estensioni
Un aggiornamento del progetto prevede l’introduzione di un **encoder rotativo**, che consentirà di rilevare in tempo reale la velocità del motore, completando così il ciclo di controllo con feedback.

## 👨‍💻 Autore

Nicolò Emilii

---

