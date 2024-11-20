  Schéma électronique

    +---------------------+              +----------------------------+
    |     Microphone      |              |      Haut-parleur          |
    |  (Module MAX9814)   |              | (Connecté à DFPlayer Mini) |
    +---------------------+              +----------------------------+
               |                                      |
               |                                      |
               v                                      v
       +----------------+                  +---------------------+
       |   Arduino/RPi  |------------------|    Module Audio     |
       |   (Traitement) |                  |  (DFPlayer Mini)    |
       +----------------+                  +---------------------+
               |                                      |
               |                                      |
               v                                      v
       +----------------+                 +--------------------------+
       |  Traitement du |                 |   Sortie Audio (Jack)    |
       |  Signal Audio  |                 |   (pour le haut-parleur) |
       +----------------+                 +--------------------------+
