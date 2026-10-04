# Chainmail Economics

Chainmail Economics pictures an economy built from individuals instead of institutions, where people are links in a chainmail of interlocking rings. It starts from one question: how can a community reduce its dependence on outside companies and governments?

The model is simple enough to teach in one lesson, and it comes with a classroom game.

## What's here

| File | What it is |
| --- | --- |
| `chainmail-economics.md` | The model and the rules of the game. Start here. |
| `chainmail-game.html` | The game board, run by a facilitator on one large screen. |
| `chainmail-card.html` | The participant's card, made for a phone. |

Both HTML files are standalone. They have no dependencies and need no build step.

## The model in brief

- Each person is one link, with five attributes: energy, food, land, money, and skills (E, F, L, M, S).
- Each link bonds with up to four others, as in the four-in-one weave of real chainmail. There are no hubs.
- A link's levels are advice. The decision to bond belongs to the holders of the links involved.
- Value is counted in sats. There is no debt, and gifting is an economic act.
- A heat map shows what each link offers and how much that offer is wanted where it sits.

## Running the game

1. Open `chainmail-game.html` in a browser on the classroom computer and switch the browser to full screen. No internet connection is needed.
2. Each participant opens `chainmail-card.html`, chooses a username (an anonymous one is fine), and sets five levels from 0 to 9.
3. The participant shows, says, or sends their five-digit number to the facilitator, who enters it.
4. The first link goes to the centre of the board. Each later link asks for a place, and its neighbours accept or deny.

The facilitator also has tools for later rounds: breaking a bond, accepting a pair that refused earlier, a shock that removes a link at random, undo, and saving to a file.

## Sharing the card

The card needs to be opened from a web address for its WhatsApp button to work. If GitHub Pages is enabled for this repository, the card is available at:

`https://blankworker1.github.io/chainmail-economics/chainmail-card.html`

Adding the facilitator's number to the link sends each card as a direct message:

`chainmail-card.html?to=447700900123`

## Status

The model is a theoretical visualisation of self-coordinated behaviour. The game is a first version. It has been tested by simulated play and has not yet been run with a real class.

Planned next:

- A version that runs offline from a Raspberry Pi hotspot, with cards sent straight to the game.
- The extension of the model to community and regional scale.

## Licence

No licence has been chosen yet.
