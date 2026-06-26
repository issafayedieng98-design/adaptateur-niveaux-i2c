# Adaptateur de Niveaux Logiques I2C — 3,3 V ↔ 5 V

Carte PCB sur mesure conçue sous **KiCad 8** permettant la conversion bidirectionnelle d'un bus I2C entre deux niveaux de tension (**3,3 V ↔ 5 V**), au format breadboard.

## Objectif

Permettre la communication entre un microcontrôleur 3,3 V (STM32, ESP32, RP2040…) et des périphériques I2C alimentés en 5 V (afficheurs LCD, capteurs, etc.) sans risque de destruction des entrées.

## Caractéristiques

- Conversion bidirectionnelle I2C sur les lignes **SDA et SCL**
- Compatible **3,3 V ↔ 5 V**
- Format adapté à une utilisation sur **breadboard**
- Conception schématique et routage PCB complets sous KiCad 8
- PCB 2 couches

## Stack technique

![KiCad](https://img.shields.io/badge/KiCad_8-314CB0?style=flat&logo=kicad&logoColor=white)
![PCB](https://img.shields.io/badge/PCB-2_couches-green?style=flat)
![I2C](https://img.shields.io/badge/Protocole-I2C-blue?style=flat)
![Tension](https://img.shields.io/badge/Niveaux-3,3V_↔_5V-orange?style=flat)

## Fichiers du projet

| Fichier | Description |
|---|---|
| `adaptateur-niveaux-i2c.kicad_pro` | Fichier projet KiCad |
| `adaptateur-niveaux-i2c.kicad_sch` | Schéma électronique |
| `adaptateur-niveaux-i2c.kicad_pcb` | Routage PCB |
| `adaptateur-niveaux-i2c.kicad_sym` | Bibliothèque de symboles personnalisée |

## Auteur

**Issa FAYE** — Ingénieur Électronique & Systèmes Embarqués  
[Portfolio](https://issa-faye-portfolio.netlify.app)
