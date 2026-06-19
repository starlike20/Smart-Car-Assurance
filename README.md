# 🚗 Smart Car Assurance

Boîte noire IoT embarquée pour les compagnies d'assurance automobile.

## C'est quoi ?

Un système installé dans un véhicule qui enregistre les données de conduite en temps réel et les transmet à l'assureur via internet.

## Le problème résolu

Les assureurs fixent leurs tarifs sans connaître le comportement réel du conducteur. Smart Car collecte les vraies données — vitesse, freinage, localisation — pour un scoring personnalisé et juste.

## Comment ça marche

```
Véhicule → Capteurs → Raspberry Pi → Internet → Dashboard assureur
```

## Matériel utilisé

- Raspberry Pi 4 — cerveau du système
- ESP32 (x3) — collecte des données via Thread, LoRa et WiFi
- Capteurs — GPS, accéléromètre, température, son
- Caméra PiCam — enregistrement vidéo

## Technologies

- **Communication** : MQTT, LoRa, Thread, HTTPS
- **Backend** : Python, Flask, Node-Red, MongoDB
- **Infrastructure** : Docker, Ubuntu 22.04
- **Alertes** : SMS via Twilio, email

## Avancement

| Phase | Description | Statut |
|---|---|---|
| P1 | Thread + infrastructure de base | 🔄 En cours |
| P2 | LoRa + MQTT sécurisé + capteurs | ⏳ À venir |
| P3 | Dashboards + API + Docker | ⏳ À venir |
| P4 | Documentation + démo finale | ⏳ À venir |

## Auteure

**Stanela Djoukouo Fogang**
Master MASI4 — HEPL Liège, Belgique
🔍 En recherche de stage IoT / Réseaux / Cloud
