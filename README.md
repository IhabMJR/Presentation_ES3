# Doppelgänger

## Synoptique

- **Éléments d'Entrée**: Captures user interaction and environmental input (presence, motion, and sound).
- **Processeurs & Logiciels**: Processes input data with TouchDesigner, FaceAPI for facial detection, and Max/MSP for audio.
- **Éléments de Sortie**: Outputs display visuals on LED screens and plays sound, enhancing the immersive ambiance of the installation.

```mermaid
graph TD;

    %% Components
    subgraph Equipement
        PC[PC avec GPU dédié]
        Cam[Caméra]
        SP1[Haut-parleur 1]
        SP2[Haut-parleur 2]
        SP3[Haut-parleur 3]
        SP4[Haut-parleur 4]
        LED1[Écran LED 1]
        LED2[Écran LED 2]
        Wifi[(Wi-Fi)]
    end

    %% Connections
    Cam -->|USB| PC
    PC -->|HDMI| LED1
    PC -->|HDMI| LED2
    PC -->|Jack/Audio Cable| SP1
    PC -->|Jack/Audio Cable| SP2
    PC -->|Jack/Audio Cable| SP3
    PC -->|Jack/Audio Cable| SP4
    Wifi --> PC

    %% Labels for clarity
    note right of Cam: Connexion vidéo et capture
    note right of LED1: Affichage principal
    note right of SP1: Audio surround
    note right of Wifi: Connexion internet
```

## Plantation

## Simulation

## Scénarimage

## Devis Technique
