# Chainmail Economics

Chainmail Economics pictures an economy built from individuals instead of institutions, where people are links in a chainmail of interlocking rings. It starts from one question: how can a community reduce its dependence on outside companies and governments?

The model is simple enough to teach in one lesson, and it comes with a classroom game.

## What's here

| File | What it is |
| --- | --- |
| `chainmail-economics.md` | The model and the rules of the game. Start here to understand it. |
| `index.html` | The facilitator's landing page. Start here to run a session. |
| `chainmail-game.html` | The game board, run by a facilitator on one large screen. |
| `chainmail-card.html` | The participant's card, made for a phone. |

The three HTML files are standalone. They load nothing from outside and need no build step.

## The model in brief

- Each person is one link, with five attributes: energy, food, land, money, and skills (E, F, L, M, S).
- Each link bonds with up to four others, as in the four-in-one weave of real chainmail. There are no hubs.
- A link's levels are advice. The decision to bond belongs to the holders of the links involved.
- Value is counted in sats. There is no debt, and gifting is an economic act.
- A heat map shows what each link offers and how much that offer is wanted where it sits.

## Running the game

1. Open `index.html`. It links to the game and shows a QR code for the card.
2. Open the game on the classroom computer and switch the browser to full screen. The game itself needs no internet connection.
3. Each participant scans the code to open the card, chooses a username (an anonymous one is fine), and sets five levels from 0 to 9.
4. The participant shows, says, or sends their five-digit number to the facilitator, who enters it.
5. The first link goes to the centre of the board. Each later link asks for a place, and its neighbours accept or deny.

The facilitator also has tools for later rounds: breaking a bond, accepting a pair that refused earlier, a shock that removes a link at random, undo, and saving to a file.

## Sharing the card

The landing page and the card need to be opened from a web address for the QR code and the card's WhatsApp button to work.GitHub Pages is enabled for this repository, the landing page is at:

 [`https://blankworker1.github.io/chainmail-economics/`]

The landing page builds the QR code for the card. If the facilitator enters their WhatsApp number there, the code and link change so that each card arrives as a direct message. The link then takes this form:

`chainmail-card.html?to=447700900123`

The number is part of the link, so participants can see it.

## Status

The model is a theoretical visualisation of self-coordinated behaviour. The game is a first version. It has been tested by simulated play and has not yet been run with a real class.

Planned next:

- A version that runs offline from a Raspberry Pi hotspot, with cards sent straight to the game.
- The extension of the model to community and regional scale.

## Credits

`index.html` embeds the QR Code Generator for JavaScript by Kazuhiko Arase, used under the MIT licence.

## Licence

No licence has been chosen yet.
