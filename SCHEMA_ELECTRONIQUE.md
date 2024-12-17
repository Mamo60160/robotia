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
       |  Traitement du |                 |   Sortie Audio (bt)      |
       |  Signal Audio  |                 |   (pour le haut-parleur) |
       +----------------+                 +--------------------------+
