<b>"Doppelgänger"</b> est une installation interactive qui a la forme d'un miroir qui déforme le reflet de l'utilisateur, projettant des distortions sonores et visuelles, symbolisant l’exploitation de la vie privée par des groupes qui cherchent à abuser nos données personnelles.

# Devis Technique

## Fournis par l'artiste

- PC/laptop Windows qui contient les logiciels (TouchDesigner, Max)
- Camera webcam 1080p

## Fournis par le diffuseur

### Vidéo

- Écran ~40"
- Écran ~12"
- 2 Cables HDMI

### Audio

- Interface audio avec 4 sorties
- 4 haut-parleurs aux alentours de l'utilisateur
- 4 cables XLR

# Synoptique

```mermaid
graph TD;

    %% Components
        PC[PC]
        AudioInterface[Interface audio avec 4 sorties]
        Cam[Caméra]
        SP1[Haut-parleur 1]
        SP2[Haut-parleur 2]
        SP3[Haut-parleur 3]
        SP4[Haut-parleur 4]
        LED1[Écran LED 1]
        LED2[Écran LED 2]
        Routeur[Routeur]

    %% Connections
    Cam -->|USB| PC
    PC -->|USB| AudioInterface
    PC -->|HDMI| LED1
    PC -->|HDMI| LED2
    AudioInterface -->|Cable audio| SP1
    AudioInterface -->|Cable audio| SP2
    AudioInterface -->|Cable audio| SP3
    AudioInterface -->|Cable audio| SP4
    Routeur -->|UTP| PC
```

# Plantation

<img src="assets/Frame 6.png"/>

# Simulation

<img src="assets/simulation_2.png"/>
<img src="assets/simulation.png"/>

# Scénarimage

<img src="assets/Frame 1.png"/>
<img src="assets/Frame 2.png"/>
<img src="assets/Frame 3.png"/>
<img src="assets/Frame 4.png"/>
<img src="assets/Frame 5.png"/>
