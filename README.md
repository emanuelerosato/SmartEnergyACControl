# Smart Energy AC Control

Questo repository contiene un flusso Node-RED progettato per integrarsi con Home Assistant e automatizzare il controllo del condizionatore d'aria utilizzando l'energia prodotta da pannelli solari. Il sistema mira a massimizzare l'uso dell'energia rinnovabile mantenendo il comfort domestico.

## Caratteristiche

- **Automazione Basata su Energia Solare**: Utilizza l'energia in eccesso dai pannelli solari per alimentare il condizionatore.
- **Logica di Isteresi**: Evita cicli di accensione/spegnimento frequenti per prolungare la vita del condizionatore.
- **Notifiche via Telegram**: Ricevi aggiornamenti in tempo reale sull'attività del condizionatore.

## Pre-requisiti

- Skill Alexa con connettività ai dispositivi HVAC.
- Alexa Media Player installato in Home Assistant.
- Nodo Node-RED installato in Home Assistant.
- Configurazione del bot Telegram per le notifiche.

## Installazione

1. Clona il repository in locale.
2. Importa il flusso in Node-RED.
3. Configura i nodi con le tue specifiche impostazioni di Home Assistant e Telegram.

## Configurazione

Assicurati di aggiornare i seguenti parametri:

- `entity_id` dei tuoi sensori di produzione solare e consumo energetico.
- `api_key` e `chat_id` per il bot Telegram.

## Uso

Una volta configurato, il flusso eseguirà automaticamente il controllo del tuo condizionatore basandosi sulla produzione energetica e sulle condizioni preimpostate.

## Contribuire

Se desideri contribuire a questo progetto, per favore:

1. Forka il repository.
2. Crea un nuovo branch per le tue modifiche.
3. Invia una pull request con una descrizione dettagliata delle modifiche.

## Licenza

Questo progetto è rilasciato sotto la licenza [MIT](LICENSE).

## Contatti

Per supporto e domande, apri un'issue in questo repository.
