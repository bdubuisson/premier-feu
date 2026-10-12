# Le Premier Feu

Un petit jeu de civilisation préhistorique dans le navigateur, entre Populous et Tamagotchi.

En 40 000 av. J.-C., quatre chasseurs-cueilleurs allument leur feu devant leurs grottes. Ils vivent seuls : ils chassent, cueillent, peignent les parois, ont des enfants, vieillissent et meurent. Vous les guidez avec vos pouvoirs (feu, pluie, foudre, arc-en-ciel, fleurs, tornade, tourbillon, inondation, bénédiction, gibier) et en choisissant leurs savoirs, jusqu'à l'oppidum gaulois puis la Gaule romaine, et la fin de l'Empire en 476.

**Jouer :** https://bdubuisson.github.io/premier-feu/ (ordinateur, tablette ou téléphone, sans installation)

## Ce qu'on y trouve

- **Un village vivant.** Chaque villageois a un nom, un caractère, un rêve et un journal. Il naît, apprend un métier souvent hérité de ses parents, devient chef ou druide, et sa date de mort est inscrite dans la chronique.
- **Des âges et des savoirs historiques.** Le jeu va du Paléolithique supérieur à l'Antiquité gallo-romaine. Chaque savoir est daté et illustré : art pariétal, agriculture, menhirs, bronze, druides, oppidum, voie romaine, fanum, thermes, théâtre, castrum…
- **Des statistiques.** Pyramide des âges, courbe de population, espérance de vie, causes de décès et métiers.
- **Le climat de la dernière glaciation.** On y trouve la steppe à mammouths, la neige et la banquise d'hiver, les icebergs des événements de Heinrich, puis le réchauffement de l'Holocène. Quatre saisons rythment l'année.
- **La faune.** Les mammouths et les rhinocéros laineux disparaissent avec le réchauffement. On croise aussi des aurochs et des cerfs, et sur la côte la baleine grise de l'Atlantique, le grand pingouin, des phoques, des dauphins et l'esturgeon. Dans le ciel passent les migrations.
- **Le village se transforme.** Les grottes deviennent bergeries, réserves ou sépultures quand arrivent les maisons. Les sentiers se creusent là où l'on passe. Viennent ensuite la palissade, puis le rempart, et des pillards qu'il faut repousser.

La partie est sauvegardée automatiquement dans le navigateur.

## Technique

Le jeu tient dans un seul fichier, `index.html`, en HTML, CSS et JavaScript, sans étape de compilation. La 3D utilise [three.js](https://threejs.org/), chargée depuis cdnjs. La musique et les sons sont générés en direct avec Web Audio, et les illustrations sont des dessins SVG produits par le code.

Pour le lancer en local, servez le dossier avec n'importe quel serveur web, par exemple `python -m http.server 8080`, puis ouvrez http://localhost:8080.
