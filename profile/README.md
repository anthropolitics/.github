# anthropolitics

On chiffre ce que chaque programme politique change pour des ménages français types, et on le montre en vidéos courtes.

On informe et on chiffre. On ne dit jamais pour qui voter.

## Ce qu'on fait

- **Un moteur open source**, [simulator](https://github.com/anthropolitics/simulator), qui calcule ménage par ménage l'effet des mesures de chaque programme : impôts, cotisations, prestations.
- **Des vidéos pédagogiques** d'environ une minute, tirées des résultats du moteur. Chaque vidéo renvoie au scénario publié : n'importe qui peut vérifier ou relancer le chiffre.

## Nos principes

- **Tout est sourcé.** Chaque paramètre cite sa source : loi, INSEE ou littérature économique.
- **Les incertitudes sont visibles.** Les effets mécaniques (consensus fort) et les effets de comportement ou macro (consensus faible) sont séparés ; les seconds sont donnés en fourchettes.
- **La traduction des programmes est publique.** Chaque mesure devient des paramètres documentés, contestables par issue, y compris par les partis.
- **Aucune consigne de vote.** Nos contenus montrent des effets, jamais un « bon » choix.
- **Diffusion 100 % organique.** Aucune publicité payante.
- **Relecture avant publication**, y compris juridique (droit électoral, RGPD).

## Méthode en bref

1. **Personas** : des ménages types calés sur les statistiques publiques de l'INSEE.
2. **Mesures** : chaque mesure d'un programme est traduite en paramètres publics et sourcés.
3. **Calcul** : la législation est appliquée via OpenFisca-France ; les effets macro n'apparaissent qu'en fourchettes, et seulement quand ils changent la conclusion.
4. **Résultats** : versionnés et reproductibles, publiés dans le dépôt du moteur.

## Participer

- Une erreur, une mesure mal traduite ? Ouvrez une issue sur [simulator](https://github.com/anthropolitics/simulator/issues) avec votre source.
- Envie de contribuer au moteur, aux données ou à la relecture ? Voir la section « Contribuer » du [README du moteur](https://github.com/anthropolitics/simulator#contribuer).
