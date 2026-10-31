# Camicia card game

**Difficulty:** hard · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Stacks, queues, linked lists](../stacks-lists/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/EX-4?utm_source=github&utm_medium=tasks-repo)**

Simulate a two-player card game similar to Camicia. You get the decks of players A and B as lists of cards from the top of the deck to the bottom. A card is a string `"2"`–`"10"` (number card) or `"J"`, `"Q"`, `"K"`, `"A"` (payment card).

Rules. Players take turns putting the top card of their deck on a shared pile; A starts the first round. A number card simply passes the turn to the other player. A payment card makes the opponent pay a penalty: `J` is 1 card, `Q` is 2, `K` is 3, `A` is 4. The opponent puts cards on the pile one by one; if one of them is a payment card, they stop paying, and the other player now pays a penalty for the new card. When a penalty is paid in full, the player who put the last payment card takes the whole pile and puts it at the bottom of their deck (keeping the pile order: the bottom card of the pile goes first). That player starts the next round. If a player has no card to put (while paying a penalty or on their own turn), the other player takes the pile. Each time the pile is taken is a trick. If after a trick one player holds all the cards, the game ends.

The game enters a loop as soon as the decks (after a trick) equal decks seen earlier, when number cards are not told apart (all number cards count as the same; decks are compared with the card order, and the starting decks count as seen). Then the game stops.

Return a string of three words separated by spaces: the status (`finished` or `loop`), the total number of cards put on the pile during the whole game, and the number of tricks. For example `"finished 13 1"`.

Example: `["2", "A", "7", "8", "Q", "10"]`, `["3", "4", "5", "6", "K", "9", "J"]` → `"finished 13 1"`; `["J", "2", "3"]`, `["4", "J", "5"]` → `"loop 8 3"`.

---

Source: [Exercism, camicia](https://github.com/exercism/problem-specifications/tree/650bebeb39ad40439175288042aece982b0a90a9/exercises/camicia) · © Exercism · [MIT](https://github.com/exercism/problem-specifications/blob/650bebeb39ad40439175288042aece982b0a90a9/LICENSE) · statement rewritten
