---
stub: true
tags:
  - hit sounds
  - hitsounds
---

# Hitsound

*Voir aussi : [Ajouter des hitsounds personnalisés](/wiki/Guides/Using_custom_hitsounds)*.

Les **hitsounds** sont les sons qu'osu! joue en réponse aux frappes de l'utilisateur lorsqu'il interagit avec les [hit objects](/wiki/Hit_object). Les hitsounds sont généralement utilisés pour donner un retour auditif au joueur afin de l'aider à évaluer sa [précision](/wiki/Gameplay/Accuracy) par rapport à la beatmap.

Les hitsounds sont composés d'un échantillon par défaut appelé "hit normal", lui même composé d'un ensemble de whistle, de finish et de clap. Les trois échantillons `Normal`, `Soft`, et `Drum` changent tous le style de chaque hitsound.

Les mappers peuvent remplacer tous les échantillons sonores par défaut par des échantillons personnalisés en utilisant le dossier d'une [beatmap](/wiki/Beatmap). Le [skin](/wiki/Skinning) d'un joueur peut également remplacer les hitsounds par défaut sur toutes les beatmaps. Vous trouverez des détails sur les échantillons des hitsounds dans l'article [hitsound skinning](/wiki/Skinning/Sounds#hitsounds).

Les [spinners](/wiki/Hit_object/Spinner) et les [sliders](/wiki/Hit_object/Slider) ont des hitsounds supplémentaires : `spinner`, `bonus spinner`, `slider slide` et `slider tick`.

## Hitsound actif

Un hitsound est considéré comme *actif* si il se situe sur une partie cliquable d'un hit object, par exemple un hit circle ou un slider head. Ils aident le joueur à juger si ils ont appuyé trop tôt ou trop tard en jouant un son clair et impactant au moment du clic. Si il est cliqué au bon moment, le son devrait correspondre à un battement de la musique.

## Hitsound passif

Si un hitsound est situé sur une partie non cliquable d'un objet, pas exemple un slider repeat ou la fin d'un spinner, il est considéré comme *passif*. Ces hitsounds vont toujours se jouer au même moment du moment que le joueur est en train d'intéragir avec le hit object, contrairement aux hitsounds actifs. Les hitsounds passifs n'ont pas besoin d'avoir un réel impact ou d'être audible, mais ils utilisent souvent les même sons que les hitsounds actifs quand il sont au même moment qu'un battement distinct de la musique, pour aider le joueur à garder le rythme.

## Keysound

Un keysound est un échantillon de hitsound qui est extrêmement similaire à la musique, ou directement tiré de celle-ci, et qui est utilisé pour reproduire la hauteur des notes de la musique. Cette méthode de hitsounding fournit généralement un faible retour au joueur, mais peut rendre le jeu de certains beatmaps plus intéressant et faire ressortir certaines sections d'une map lorsqu'elle est bien appliquée.

## Dans osu!taiko

Contrairement aux autres [modes de jeu](/wiki/Game_mode), les hitsounds du mode [osu!taiko](/wiki/Game_mode/osu!taiko) affectent directement la jouabilité de leurs beatmaps. Les Kats se distinguent des Dons à l'aide de whistle et de claps, et les grandes notes se distinguent des notes normales à l'aide de finishers.

Les échantillons par défaut de osu!taiko sont uniques au mode, et les mappeurs ne les remplacent généralement pas.
