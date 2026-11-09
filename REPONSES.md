# Réponses — Évaluation POO : héritage, polymorphisme, transtypage

- Matricule :
- Nom et prénom :
- N (deux derniers chiffres du matricule) :

> Rédigez vos justifications **avec vos propres mots**. Elles serviront de base à l'échange oral.

## Exercice 1 — A. Affichage prédit

Écrivez ci-dessous, entre les deux lignes de trois accents graves, **une ligne par ligne affichée**, dans l'ordre.
Ne modifiez pas les lignes de trois accents graves.

```text
A vehicule
f null 0
e moto 110
moto2
moto
c3
c2
b vehicule
a vehicule
f null 0
e moto 110
true false
true
a vehicule
b vehicule
3

```

## Exercice 1 — A. Justifications

1. Ligne qui commence par « F » :c'est moto demarrer qui tourne mais il se termine avant l'nitialisationdes champs de moto
2. Ligne « C3 » :comparer v est declaré vahicule, a l'exécution il redefinie cette méthone et ce pour cela il retourn c3
3. Ligne « C2 » :ici on dois type moto, donc le compilateur choisit comparer moto elle va pas redefinir cette version, elle hérite de vehicule,donc elle retourn c2
4. Ligne qui commence par « D- » :c'est le type déclaré de v donc vehicule, qui decide méme si léobjet est une moto
5. Pourquoi des lignes « A », « F », « E » apparaissent avant « true false » :system.out.println(equals(v)+)pour afficher la ligne et seulement aprés il affiche true false true parce que o et v c'est le méme objet

## Exercice 1 — B. Transtypage

Colonne « Compile ? » : `oui` ou `non`. Colonne « Exécution » : `OK`, `exception` (en précisant laquelle), ou `-` si le code ne compile pas.

| n° | Compile ? | Exécution | Justification |
|----|-----------|-----------|---------------|
| 1  |    oui       |  ok         |  une moto est un vehicule             |
| 2  |non           |           |c"c'est un vehicule rt il ne c"est pas que ce tu ne moto               |
| 3  |           |           |               |
| 4  |           |           |               |
| 5  |           |           |               |
| 6  |           |           |               |
| 7  |           |           |               |
| 8  |           |           |               |
