Résumé des apprentissages de ce laboratoire:

Dans ce laboratoire, nous avons appris comment créer une application web simple avec Flask et avec un distributeur de charge. Pendant les manipulations, on connecte les deux membres sur le même serveur et les deux membres communiquent entre eux. On démontre aussi la capacité de NGINX de faire de la répartition de charge.

Réponses aux questions posées:

Étape 5: La page Web affiche le message : "Hello, World! From MS: 172.16.14.38"
Étape 6: Après avoir arrêté l'application python et avoir testé avec la même adresse, le site n'est plus accessible.
Étape 16: On peut remarquer que la machine B se connecte sur notre serveur de la machine A et nous envoie le message “Hello, World! From MS:172.16.14.43” avec son adresse IP. Et quand on rafraîchit plusieurs fois, on remarque que le message passe à celui de la machine A. Les deux machines “s’envoient la balle”.
Étape 17: a. Non.
          b. Oui, même si les applications sont fermés, c'est toujours disponible. Ceci est possible à cause de notre distributeur de charge NGINX.
