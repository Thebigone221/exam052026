
# Examen DevOps CI/CD Mouhamadou Gueye

Problèmes rencontrés

- Pipeline main : tous les champs étaient TO_BE_REPLACE

- Dockerfile : EXPOSE 81 au lieu de 80, index.html manquant

- Trivy : version 0.30.0 inexistante, image-ref incorrecte

- Login Docker Hub : commande manuelle échouait, secrets mal lus

Corrections appliquées

- Remplacement des TO_BE_REPLACE par les vraies variables

- Correction du Dockerfile (EXPOSE 80 + ajout index.html)

- Utilisation de docker/login-action@v3 pour le login

- Trivy : version master + image-ref correcte

Lien du dépôt

https://github.com/Thebigone221/exam052026

