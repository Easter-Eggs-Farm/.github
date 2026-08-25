# Easter Eggs Farm

Deux poulaillers dans l'Yonne, tenus par deux développeurs.

Sigrid a treize poules, deux chèvres et deux coqs ; Anthony en a six et rien
d'autre. Nous vendons les œufs aux voisins. Le reste de la semaine, nous
écrivons du code — ce qui explique pourquoi la ferme se présente comme un
dépôt, avec des fichiers, un diff et un tableau de tickets.

## Ce qu'on trouve ici

| Dépôt                                                    | Ce que c'est                                                                      |
| -------------------------------------------------------- | --------------------------------------------------------------------------------- |
| [`qr-code`](https://github.com/Easter-Eggs-Farm/qr-code) | Le QR code collé sur les boîtes : il mène au site et au moyen de paiement.        |
| `egg-manager`                                            | Le site et la gestion : ponte, stock, poules, réservations. Privé pour l'instant. |

## Nous ouvrir une issue

**[→ Ouvrir une issue](https://github.com/Easter-Eggs-Farm/.github/issues/new)**

Tout arrive au même endroit, quel que soit le sujet, et nous trions ensuite.
Vous n'avez pas à deviner quel dépôt est concerné : c'est notre travail, pas le
vôtre.

Écrivez en français ou en anglais, comme vous voulez. Ce qui aide vraiment :

- **Ce que vous faisiez** quand ça s'est passé.
- **Ce que vous attendiez**, et ce qui est arrivé à la place.
- **Sur quoi** : téléphone ou ordinateur, et quel navigateur si vous le savez.
- **Une capture d'écran**, si l'écran montre quelque chose.

Rien de tout ça n'est obligatoire. Une issue qui dit seulement « le bouton de
réservation ne fait rien sur mon téléphone » est une bonne issue — nous
poserons les questions qui manquent.

Pour une question sur les œufs plutôt que sur le site — une commande, une date
de vente, une poule en particulier — le site a un bouton de contact, et c'est la
bonne porte.

## Comment on travaille

Rien d'original, mais tenu :

- **Chaque décision de structure est écrite** avant d'être prise, dans un ADR
  qui nomme l'hypothèse qui la rendrait fausse et le signal qui le prouverait.
  Une décision qu'on ne peut pas réfuter est une décision dont on n'apprend
  rien.
- **La CI décide, pas nous.** Tests, couverture, types, lint, format des
  messages de commit, accessibilité : si une porte est rouge, ça ne part pas.
  Un seuil qu'on peut contourner à la main n'est pas un seuil.
- **L'accessibilité est une porte, pas une intention.** Les contrastes sont
  mesurés à chaque exécution, les pages balayées par axe. Le site vise WCAG AAA,
  avec une seule exception assumée et documentée là où viser AAA rendait le
  texte plus difficile à lire, pas moins.
- **Le code et les commentaires sont en anglais ; ce qu'un visiteur lit est
  bilingue.** Deux publics, deux langues, aucune traduction automatique.
- **On ne met jamais en ligne ce qu'on n'a pas vérifié.** Pas de photo de poule
  qui n'existe pas, pas de chiffre inventé, pas de témoignage écrit par nous.
  Ce qui manque est signalé comme manquant.

---

<details>
<summary><b>In English</b></summary>

# Easter Eggs Farm

Two henhouses in the Yonne, kept by two developers.

Sigrid has thirteen hens, two goats and two roosters; Anthony has six hens and
nothing else. We sell the eggs to our neighbours. The rest of the week we write
code — which is why the farm introduces itself as a repository, with files, a
diff and a ticket board.

## What is here

| Repository                                               | What it is                                                                               |
| -------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| [`qr-code`](https://github.com/Easter-Eggs-Farm/qr-code) | The QR code on the boxes: it leads to the site and to the way to pay.                    |
| `egg-manager`                                            | The site and the management screens: laying, stock, hens, reservations. Private for now. |

## Opening an issue

**[→ Open an issue](https://github.com/Easter-Eggs-Farm/.github/issues/new)**

Everything lands in one place whatever it is about, and we sort it afterwards.
You do not have to work out which repository is concerned: that is our job, not
yours.

Write in French or English, as you prefer. What genuinely helps:

- **What you were doing** when it happened.
- **What you expected**, and what happened instead.
- **On what**: phone or computer, and which browser if you know.
- **A screenshot**, if the screen shows anything.

None of that is required. An issue saying only "the reserve button does nothing
on my phone" is a good issue — we will ask for whatever is missing.

For a question about the eggs rather than the site — an order, a sale date, one
particular hen — the site has a contact button, and that is the right door.

## How we work

Nothing original, but kept to:

- **Every structural decision is written down** before it is taken, in an ADR
  that names the assumption which would make it wrong and the signal that would
  prove it. A decision you cannot disprove is one you learn nothing from.
- **CI decides, not us.** Tests, coverage, types, lint, commit message format,
  accessibility: if a gate is red, it does not ship. A threshold you can step
  around by hand is not a threshold.
- **Accessibility is a gate, not an intention.** Contrast ratios are measured on
  every run and the pages swept with axe. The site holds WCAG AAA, with one
  documented exception where reaching AAA made the text harder to read rather
  than easier.
- **Code and comments are in English; what a visitor reads is bilingual.** Two
  audiences, two languages, no machine translation.
- **We never publish what we have not checked.** No photograph of a hen that
  does not exist, no invented figure, no testimonial written by us. What is
  missing is marked as missing.

</details>
