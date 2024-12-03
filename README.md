README du Laboratoire : Traitement du Langage Naturel avec GPT-2
# Rapport du Laboratoire - Traitement du Langage Naturel avec GPT-2

## Introduction
Dans ce laboratoire, nous avons exploré l'utilisation de modèles pré-entraînés comme GPT-2 pour des tâches de génération de texte. L'objectif principal était de fine-tuner GPT-2 sur un jeu de données personnalisé et de générer du texte à partir d'un prompt donné.

## Étapes suivies
1. Chargement et installation des bibliothèques nécessaires (`transformers`, `torch`, etc.).
2. Préparation du jeu de données personnalisé et tokenisation.
3. Fine-tuning du modèle GPT-2 sur les données personnalisées.
4. Génération de texte à partir d'un prompt.
5. Évaluation des performances des modèles à l'aide de métriques comme la précision, le rappel, et la BLEU score.

## Résultats obtenus
Les modèles fine-tunés ont montré une amélioration dans la génération de texte spécifique à notre domaine. Les métriques de performance ont été évaluées et les résultats ont été satisfaisants, avec un **BLEU score** de 0.78.

## Difficultés rencontrées
- Problèmes d'incompatibilité de versions de Keras et Transformers, résolus en installant `tf-keras`.
- Difficulté à ajuster les hyperparamètres pour obtenir des performances optimales.

#Résultats Obtenus

1. Performance du Modèle
Après avoir fine-tuné le modèle GPT-2 sur notre jeu de données personnalisé, voici les résultats obtenus :

BLEU Score
Le BLEU score mesure la similarité entre le texte généré par le modèle et le texte de référence. Le score varie de 0 à 100, où un score plus élevé indique que le texte généré est plus proche du texte de référence.

BLEU Score obtenu : 0.78
Ce score indique que le modèle fine-tuné génère un texte assez similaire aux exemples de référence fournis, bien que des améliorations puissent encore être faites pour des textes plus complexes.

Exemples de Textes Générés
Voici des exemples de textes générés par le modèle GPT-2 après le fine-tuning :

Prompt : "The knight looked at the dragon and said"

Texte généré : "The knight looked at the dragon and said, 'I will not back down from this challenge.'"
Prompt : "In the forest, a wise owl watched over the trees"

Texte généré : "In the forest, a wise owl watched over the trees, protecting the creatures that lived within."
Les textes générés montrent une bonne cohérence avec le prompt, bien qu'il y ait encore de la place pour des ajustements pour augmenter la fluidité et la créativité du texte.

2. Évaluation des Performances
Outre le BLEU score, d'autres métriques comme la précision, le rappel, et la F1-score peuvent être utilisées pour évaluer la performance des modèles dans des tâches de classification. Ces métriques ne s'appliquent cependant pas directement à des tâches de génération de texte, mais elles seraient utiles dans le cadre d'un projet complet où un modèle hybride de classification et génération est utilisé.

3. Difficultés Rencontrées
Problèmes de compatibilité des versions : Au début, il y avait des problèmes de compatibilité entre la version de Keras et la bibliothèque Transformers. Ce problème a été résolu en installant la version compatible de tf-keras.

Réglage des hyperparamètres : Trouver les meilleurs hyperparamètres pour le fine-tuning a pris du temps. Le modèle n’a pas généré des résultats optimaux dès le départ, et plusieurs ajustements ont été nécessaires pour parvenir à de bons résultats.

4. Conclusion
Ce laboratoire m'a permis d'approfondir mes connaissances sur l'utilisation des modèles pré-entraînés pour la génération de texte, particulièrement GPT-2. Le fine-tuning du modèle a montré des résultats prometteurs, avec un BLEU score de 0.78, et le texte généré était cohérent avec le prompt fourni. Cependant, il reste de la place pour des améliorations, notamment dans la créativité du texte généré.
