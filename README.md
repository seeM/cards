# Cards

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This is based on Chapter 18 of Allen B. Downey’s *Think Python* which he
has generously made available
[here](https://www.greenteapress.com/thinkpython/html/book019.html).

## Install

``` sh
pip install cards
```

## How to use

``` python
from cards.deck import Deck
```

Create a [`Deck`](https://seeM.github.io/cards/deck.html#deck), which is
sorted by default:

``` python
deck = Deck()
deck
```

    A♣️ 2♣️ 3♣️ 4♣️ 5♣️ 6♣️ 7♣️ 8♣️ 9♣️ 10♣️ J♣️ Q♣️ K♣️ A♦️ 2♦️ 3♦️ 4♦️ 5♦️ 6♦️ 7♦️ 8♦️ 9♦️ 10♦️ J♦️ Q♦️ K♦️ A❤️ 2❤️ 3❤️ 4❤️ 5❤️ 6❤️ 7❤️ 8❤️ 9❤️ 10❤️ J❤️ Q❤️ K❤️ A♠️ 2♠️ 3♠️ 4♠️ 5♠️ 6♠️ 7♠️ 8♠️ 9♠️ 10♠️ J♠️ Q♠️ K♠️

However, you can shuffle the deck:

``` python
import random
```

``` python
random.seed(42)
```

``` python
deck.shuffle()
deck
```

    10♣️ J♦️ K♦️ 4♣️ 9♦️ K❤️ 4♦️ A♠️ 7♦️ Q♣️ 8♠️ Q♦️ 8❤️ 4❤️ 6❤️ 5♠️ 5♣️ 3❤️ J♣️ A❤️ J❤️ A♣️ 6♠️ 6♦️ 4♠️ Q♠️ 10❤️ 10♠️ 5❤️ 8♦️ 10♦️ K♣️ K♠️ 7❤️ 7♠️ A♦️ 3♠️ J♠️ 3♣️ 2❤️ Q❤️ 6♣️ 9❤️ 7♣️ 9♣️ 2♦️ 3♦️ 5♦️ 9♠️ 2♣️ 8♣️ 2♠️

Each element of the deck is a
[`Card`](https://seeM.github.io/cards/card.html#card):

``` python
card = deck[0]
card
```

    10♣️
