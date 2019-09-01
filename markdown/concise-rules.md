# Concise Rules

The _Oracle Chess_ is a novel chess-variant.
It bears substantial similarity to the canonical Chess, so in this document we focus on the new features only.

This document is intended to be short, and does not settle many plausible cases.
For further clarification and discussion I have also written a [Detailed Rules](/markdown/detailed-rules.md).
The reader may skip the Detailed Rules upon first reading.

There are mainly three new features in Oracle Chess: bodies and souls, the Priestess, and rebirth, as follows.

To start, in place of solid pieces, players move two kinds of token, called _bodies_ and _souls_, which may be united or be separated.
Bodies and souls come in several classes, roughly corresponding to the traditional King, Rook, Bishop, Knight, and Pawn, but for clarity, we use different names for them: _Lord_, _Chariot_, _Elephant_, _Horse_, and _Soldier_, respectively.
When a body matches the soul it hosts, the body is said to be living.
A _being_ refers to any composite that may lie on a square: a dead body, a mismatched (_ill-suited_) body, a living body (or a _figure_).
When there is no confusion, a living Chariot is called simply a Chariot, and so on.

The way a body and (or) a soul move is determined only by the class of that soul.
Only a living body can move, and when it does, it moves together with its soul.
However, a soul may move alone to another friendly body, as long as the new body has room to host it.

A body is associated with either White or Black, but a soul is neutral.
A player may move any friendly being, that is, any friendly body and possibly the soul it hosts.

In addition, abandoning of the traditional queen, we introduce a new class of body, the _Priestess_.
A Priestess matches Chariot, Elephant, or Horse souls, and can host up to three souls, which need not be distinct.
Accordingly, it may move the way any of its soul allows.
In the beginning of game, a dead Priestess lies on the traditional queen square (_d1_ or _d8_).

Thus, while a traditional move is either going to an empty square, or capturing an enemy piece, here there are three possible actions.
A living body may go to an empty square, grant a soul to a friendly body, or capture an enemy body, as long as the relation between the initial square and final square corresponds to the soul class. 
Note that a Soldier go to, or grant soul to, an empty square in front of it, but captures on the immediate diagonal square.

When a being is captured, the body goes to the earth, which is represented by a tray next to the board, and is owned by the capturing opponent.
Simply put, bodies swap color when captured, joining the enemy force, in imitation to Shogi rules.
Similarly, when captured, a soul goes to the underworld, represented by another tray.
Since they are not distinguished by color, the tray is shared by two players.

We come naturally to our last topic, the rebirth of beings.
The rebirth has to be realized in two stages.
Firstly, the Lord goes or captures, and on the previous square, now emptied, the player may place a dead body of friendly color.
This takes one move only, and only Lords can do this.
Secondly, a Priestess grants a soul to the new dead body, effectively resurrecting it.

Moreover, a Priestess may fetch a soul (and only it can) when it grants a soul to another body, thus making use of available souls in the underworld.
This way, both the bodies in the earth, and the souls in the underworld, are conservative.

A Soldier can promote to a dead Priestess only, when it is on the last (and furthest) rank.
We require that the promotion take one move, and that it be done only when either Priestess has been captured (so a Priestess body is in the earth).
But the soldier may stay on the promotion square indefinitely to wait to promote.

The goal of the game is to capture the emeny Lord soul.
The concept of check and checkmate generalize naturally, so obviously such capture would not really happen.
Note that we open the possibility that a Lord body has been captured, but the soul is still hosted by another body.

There is no counterpart of casling, and the Soldier may move one square in the beginning.