+++
title = "Exécution de commandes à l’aide du Shell Bash"
weight = 21
+++

Le Shell Bash (*Bourne Again SHell*) est l'un des interpréteurs de commandes les plus populaires sous Linux. Il permet aux utilisateurs d'exécuter des commandes, de manipuler des fichiers, de gérer des processus et d'automatiser des tâches à l'aide de scripts. Cette leçon se concentre sur l'exécution de commandes simples à l'aide du shell Bash.

## Commandes simples

1. **date**
   - **Description** : Affiche ou définit la date et l'heure du système.
   - **Utilisation** :
     ```bash
     date
     ```
   - **Exemple** :
     ```bash
     Mon Dec  3 11:45:00 EST 2024
     ```

2. **passwd**
   - **Description** : Change le mot de passe de l'utilisateur.
   - **Utilisation** :
     ```bash
     passwd
     ```
   - **Exemple** :
     - L'utilisateur est invité à entrer son mot de passe actuel, puis le nouveau mot de passe.

3. **cat**
   - **Description** : Affiche le contenu d'un fichier ou concatène plusieurs fichiers.
   - **Utilisation** :
     ```bash
     cat nom_du_fichier
     ```
   - **Exemple** :
     ```bash
     cat fichier.txt
     ```
   - **Sortie** :
     ```plaintext
     Contenu du fichier.txt
     ```

4. **less**
   - **Description** : Affiche le contenu d'un fichier page par page.
   - **Utilisation** :
     ```bash
     less nom_du_fichier
     ```
   - **Exemple** :
     ```bash
     less fichier.txt
     ```
   - **Navigation** :
     - `Espace` : Page suivante
     - `b` : Page précédente
     - `q` : Quitter

5. **head**
   - **Description** : Affiche les premières lignes d'un fichier.
   - **Utilisation** :
     ```bash
     head nom_du_fichier
     ```
   - **Options Courantes** :
     - `head -n 10 nom_du_fichier` : Affiche les 10 premières lignes (par défaut).
   - **Exemple** :
     ```bash
     head fichier.txt
     ```

6. **tail**
   - **Description** : Affiche les dernières lignes d'un fichier.
   - **Utilisation** :
     ```bash
     tail nom_du_fichier
     ```
   - **Options Courantes** :
     - `tail -n 10 nom_du_fichier` : Affiche les 10 dernières lignes (par défaut).
     - `tail -f nom_du_fichier` : Affiche les nouvelles lignes ajoutées en temps réel.
   - **Exemple** :
     ```bash
     tail fichier.txt
     ```

7. **; (point-virgule)**
   - **Description** : Permet d'exécuter plusieurs commandes sur une seule ligne.
   - **Utilisation** :
     ```bash
     commande1 ; commande2
     ```
   - **Exemple** :
     ```bash
     date ; whoami
     ```
   - **Sortie** :
     ```plaintext
     Mon Dec  3 11:45:00 EST 2024
     utilisateur
     ```

Ces commandes simples sont essentielles pour naviguer et gérer efficacement un système Linux à l'aide du shell Bash. La maîtrise de ces commandes vous permettra d'effectuer des tâches courantes de manière plus efficace et de mieux comprendre le fonctionnement de votre système.