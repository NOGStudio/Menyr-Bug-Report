---
name: Bug report
about: Create a report to help us improve
title: "[BUG] "
labels: bug
assignees: ''

---

name: Rapport de bug Menyr
about: Utilisez ce modèle pour signaler un bug dans Menyr.

title: "[BUG] Titre du problème"
labels: bug

body:
- type: textarea
  id: description
  attributes:
    label: Description
    placeholder: Décrivez le problème de manière claire et concise.
  validations:
    required: true

- type: input
  id: version
  attributes:
    label: Version
    description: Quelle est la version de Menyr que vous utilisez ?
    placeholder: 1.0.0

- type: input
  id: os
  attributes:
    label: Système d'exploitation
    description: Quel est votre système d'exploitation ?
    placeholder: Windows 10

- type: textarea
  id: steps-to-reproduce
  attributes:
    label: Étapes pour reproduire
    description: Décrivez les étapes pour reproduire le problème.
    placeholder: 1. Ouvrez Menyr. 2. Cliquez sur X. 3. Le problème se produit.

- type: textarea
  id: expected-behavior
  attributes:
    label: Comportement attendu
    description: Décrivez ce que vous attendiez de Menyr.
    placeholder: Le menu déroulant devrait s'ouvrir.

- type: textarea
  id: actual-behavior
  attributes:
    label: Comportement observé
    description: Décrivez ce que vous avez observé à la place.
    placeholder: Le menu déroulant ne s'ouvre pas.

- type: input
  id: screenshots
  attributes:
    label: Captures d'écran
    description: Si vous le pouvez, ajoutez des captures d'écran pour illustrer le problème.
    placeholder: https://i.imgur.com/abc123.png

- type: textarea
  id: additional-info
  attributes:
    label: Informations supplémentaires
    description: Ajoutez ici toutes les informations supplémentaires que vous pensez être pertinentes.

submit: Envoyer le rapport de bug
