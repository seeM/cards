# cards

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Install

``` sh
pip install cards
```

## How to use

``` python
from cards.deck import Deck
```

Create a [`Deck`](https://seeM.github.io/cards/deck.html#deck) of
standard playing cards:

``` python
deck = Deck()
deck
```

    A♣️ 2♣️ 3♣️ 4♣️ 5♣️ 6♣️ 7♣️ 8♣️ 9♣️ 10♣️ J♣️ Q♣️ K♣️ A♦️ 2♦️ 3♦️ 4♦️ 5♦️ 6♦️ 7♦️ 8♦️ 9♦️ 10♦️ J♦️ Q♦️ K♦️ A❤️ 2❤️ 3❤️ 4❤️ 5❤️ 6❤️ 7❤️ 8❤️ 9❤️ 10❤️ J❤️ Q❤️ K❤️ A♠️ 2♠️ 3♠️ 4♠️ 5♠️ 6♠️ 7♠️ 8♠️ 9♠️ 10♠️ J♠️ Q♠️ K♠️

Decks work like ordinary Python lists. Draw a
[`Card`](https://seeM.github.io/cards/card.html#card) from the deck with
`deck.pop`:

``` python
card = deck.pop()
card
```

    K♠️
