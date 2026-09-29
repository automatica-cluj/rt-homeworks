# SSATR – Teme de laborator

Teme pentru disciplina **Structuri Software pentru Aplicații de Timp Real (SSATR)**, program de master.

Fiecare temă se află într-un subfolder separat și conține enunțul (`README.md`) și, opțional, exemple și un proiect de start.

## Teme

| Nr. | Temă | Tehnologii |
|-----|------|------------|
| 01  | [Aplicație IoT cu taskuri periodice, sporadice și aperiodice](tema-01-iot-mqtt/) | Java, MQTT, diagrame UML |

## Tehnologii folosite

- **Java** – programare concurentă, fire de execuție, planificare, sincronizare
- **Arduino / ESP32** – sisteme embedded, FreeRTOS, senzori și actuatori
- **Linux cu kernel RT** (`PREEMPT_RT`) – latență, priorități, politici de planificare
- **Servicii de mesagerie** – RabbitMQ, Kafka, MQTT etc.
- **Diagrame** – UML (secvență, stări, activitate, componente), rețele Petri, diagrame de timp

## Structura unei teme

```
tema-NN-nume-scurt/
├── README.md     # enunțul temei (obligatoriu)
├── exemple/      # cod sau diagrame demonstrative (opțional)
└── start/        # proiect de pornire pentru studenți (opțional)
```

## Cum se lucrează

1. Faceți un fork (sau clonați) acest repository.
2. Citiți enunțul din `README.md` al temei.
3. Dacă tema are un folder `start/`, porniți de la acesta.
4. Predați soluția conform instrucțiunilor din enunțul temei.
