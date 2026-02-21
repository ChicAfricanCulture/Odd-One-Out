# African Foodways: Spot the Odd One Out

An interactive visual recognition game that trains the eye to distinguish authentic African pantry staples from common look-alikes or Western substitutes. Four images appear; three are variations of one dish or ingredient, one is the impostor. Click to reveal, then select the odd one out. Correct choices unlock short, accurate explanations of texture, preparation, and cultural role.

Part of the **African Foodways Project** — field notes, recipes, and documentation at https://chicafricanculture.github.io/african-foodways-data/.

## Purpose

Many people see a white mound and think "mashed potatoes" or a rice dish and assume "fried rice." This game drills the differences that matter in actual kitchens: swallow vs. chew, pounded vs. whipped, stewed vs. wok-tossed, fermented vs. fresh. It is not a trivia quiz—it is visual pattern recognition for people who cook, eat, or document African foodways.

Rounds progress from obvious (texture/shape) to subtle (plating variations, regional markers). Players finish knowing why fufu balls are seamless and glossy while mashed potatoes show peaks and butter pools, or why jollof rice glistens uniformly red while fried rice shows distinct grains and flecks.

## Features

- 12 progressive rounds (expandable)
- 2×2 grid with reveal-on-click mechanics
- Instant feedback: shake on wrong choice, explanation + proverb on correct
- Score tracking and completion badge
- Mobile-responsive (tiles scale, layout stacks on small screens)
- Dark theme consistent with African Pantry Mahjong
- Vanilla HTML/CSS/JS — no frameworks, fast load

## How to Play

1. Open in browser.
2. Click tiles to reveal images.
3. Select the odd one out (the impostor).
4. Correct → explanation + score increase → next round.
5. Wrong → shake + hint → try again.
6. Finish 12 rounds → archive master status.

## Rounds Overview

Each round uses 3 authentic variants + 1 common substitute/impostor.

1. Fufu variations vs. mashed potatoes (pounded swallow staple vs. whipped side)
2. Jollof rice vs. fried rice (stewed tomato sheen vs. wok-tossed dry grains)
3. Pounded yam vs. Irish champ (smooth yellow-white vs. green-flecked buttery mash)
4. Garri soak vs. instant oats (lumpy cassava vs. smooth grain porridge)
5. Ugali vs. polenta (firm white cornmeal vs. looser yellow grit)
6. Kenkey vs. tamales (fermented corn dough wrap vs. masa filling)
7. Banku vs. couscous (sour fermented dough vs. steamed grain)
8. Amala vs. chapati dough (dark yam powder ball vs. wheat flatbread base)
9. Eba vs. boiled pasta (garri swallow vs. wheat bite)
10. Tuwo shinkafa vs. risotto (Hausa rice mush vs. creamy Arborio)
11. Sadza vs. Southern grits (firm Zimbabwean maize vs. loose US hominy)
12. Injera vs. crepe (Ethiopian teff ferment bubbles vs. thin pancake)

## Tech Stack

- Pure HTML5, CSS3, JavaScript
- Images in `/images/` folder (PNG/JPG, 160×160+ recommended)
- MIT License

## Setup (Local / Development)

1. Clone repo
2. Place images in `/images/` (match filenames in `rounds` array)
3. Open `index.html` in browser
4. Edit `rounds` array in `<script>` to add/reorder rounds or change explanations

## Cultural & Editorial Notes

- Explanations are short, factual, kitchen-grounded — no romanticizing or generic descriptors.
- Focus is West/Central/East African staples with clear visual/tactile distinctions.
- Game teaches without lecturing: players learn by seeing, not reading essays.
- Extend by adding rounds (e.g., pounded plantain vs. gnocchi, ewedu vs. creamed spinach).

## Contributing

Pull requests welcome for:
- Bug fixes (mobile scaling, click accuracy)
- New rounds (authentic images + impostor + accurate one-sentence explanation)
- Additional proverbs tied to food context
- Image cropping/optimization suggestions

All contributions should respect lived practice and avoid tourist or colonial framing.

## License

MIT — see [LICENSE](LICENSE) file.

Maintained by Chic African Culture for The African Gourmet Foodways Archive.
