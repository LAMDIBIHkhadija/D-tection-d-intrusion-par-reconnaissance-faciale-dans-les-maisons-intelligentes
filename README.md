# Projet de Détection d'intrusion par reconnaissance faciale dans les maisons intelligentes


## **Objectifs du projet**

---

### 1. **Reconnaissance faciale et alerte par email**

**Objectif principal** : Développer un système de reconnaissance faciale permettant de capturer des images, les comparer avec une base de données, détecter des changements (présence de nouvelles personnes) et envoyer des alertes par email si nécessaire.

- **Étapes** :
  1. Capture d'images à intervalles réguliers.
  2. Traitement des images pour détecter des changements (utilisation d'algorithmes de comparaison d'images).
  3. Reconnaissance faciale sur les nouvelles images.
  4. Envoi d'une alerte par email si une nouvelle personne est détectée.

---

### 2. **Capture d'images avec caméra OV7670 via Arduino**

**Objectif principal** : Utiliser une caméra OV7670 pour capturer des images en résolution QVGA (320x240) et les transmettre à un script Python via une communication UART.

- **Étapes** :
  1. Initialisation de la caméra OV7670 sur Arduino.
  2. Capture des images en résolution QVGA.
  3. Transmission des images via UART à un script Python.

---

### 3. **Communication entre Arduino et Python pour la reconnaissance faciale**

**Objectif principal** : Assurer une communication fluide entre le module Arduino qui capture les images et le script Python qui traite ces images pour effectuer la reconnaissance faciale.

- **Étapes** :
  1. Établir une communication via le port série (UART) entre l'Arduino et Python.
  2. Lire les données d'image envoyées par Arduino.
  3. Traiter et reconstruire l'image à partir des octets reçus pour effectuer la reconnaissance faciale.

---

## **Auteur**

- [Lamdibih Khadija](https://github.com/LAMDIBIHkhadija)

---
