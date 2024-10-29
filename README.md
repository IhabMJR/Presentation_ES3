# Doppelgänger

## Synoptique

- **Éléments d'Entrée**: Captures user interaction and environmental input (presence, motion, and sound).
- **Processeurs & Logiciels**: Processes input data with TouchDesigner, FaceAPI for facial detection, and Max/MSP for audio.
- **Éléments de Sortie**: Outputs display visuals on LED screens and plays sound, enhancing the immersive ambiance of the installation.

```mermaid
graph TD;

    %% Sections for Organization
    subgraph A[Éléments d'Entrée]
        A1[Capteur de présence - Caméra]
        A2[Capteur de mouvement - Kinect]
        A3[Microphone pour capture sonore]
    end

    subgraph B[Processeurs & Logiciels]
        B1[PC avec GPU dédié]
        B2[Logiciel interactif - TouchDesigner]
        B3[Algorithme de détection de visage - FaceAPI]
        B4[Module de traitement audio - Max/MSP]
    end

    subgraph C[Éléments de Sortie]
        C1[Écran LED pour affichage]
        C2[Haut-parleurs pour ambiance sonore]
    end

    %% Flow Connections
    A1 --> B3
    A2 --> B3
    A3 --> B4
    
    B1 --> B2
    B2 --> C1
    B4 --> C2
```

## Plantation

## Simulation

## Scénarimage

## Devis Technique
