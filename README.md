# Avec les explicits locks
## Lorsqu'un philosophe souhaite prendre un bâtonnet, il appelle la méthode tryTake() avec un délai d'attente.
## Si le bâtonnet est déjà occupé, le philosophe attend jusqu'à ce qu'il soit libéré ou que le délai d'attente soit dépassé.
## Lorsqu'un philosophe a fini d'utiliser un bâtonnet, il appelle la méthode release() pour le libérer.
## La classe utilise un ReentrantLock pour synchroniser l'accès aux bâtonnets entre les philosophes.