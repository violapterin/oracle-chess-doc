# Detailed Rules

This document is written rather formally and painstakingly for sake of rigor, and is intend to be a reference only.
Readers may want to read [Concise Rules](/markdown/concise-rules.md) first, if they have not done so.

1. The _Oracle Chess_ is a deterministic board game for two players.
They are associated respectively with two colors, _White_ and _Black_.

   - Core definitions, in this document, are numbered to let them stand out, while explanatory commentary are interspersed, like now, and marked with a bullet point.

1. In playing the game, two players move _tokens_ on a _board_, take them away from it, or take them back onto it.
They move, alternately, tokens pertaining to their own color, starting with White.
A move is also called a _tempo_, a discrete time index.
Two tempi is called a _round_.

1. There are two kinds of tokens, _bodies_ and _souls_, both of _classes_ of either of them.
A body is associated with either White or Black, but a soul is not.
All bodies of the same class and color is identical.
Likewise, all souls of the same class are identical.

1. A class of soul may either _match_ or _mismatch_ a class of body.
A particular instance of soul may _host_ a particular instance of body, so that they are united.

1. A compound of one body and one or more matching souls is called a _man_, and the body of a figure is said to be _living_.
A compound of one body and one or more mismatching souls is called a _ill-suited body_.
A body without a soul is not said to be a figure, and we also call it an _lifeless body_.

   - I promise the whole idea is really easy, but I am sorry that we have to introduce a few terminologies to be more precise.

1. There are the following classes of bodies: _Lord_, _Priestess_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ body.
There are the following classes of souls: _Lord_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ soul (without Priestess's).

1. A Lord, Chariot, Elephant, Horse, and Soldier body (except for Priestess) each matches the corresponding class of soul.
A figure is also called by the class of its body.
Thus, a Lord body matches a Lord soul, and the compound is called simply a Lord, likewise Chariot, Elephant, Horse, and Soldier are called as thus.

1. The _board_ is of square shape, spanned along two _directions_, extending for 8 _units_ from left to right, and from back to front.
Thus it is made up of 64 discrete _squares_ on it, which are numbered from _a_ to _h_ in the horizontal direction, and from _1_ to _8_ in the vertical direction.
Each _squares_ may either be _empty_, or may accommodate one body and one soul it possibly hosts.

   - That is, we use just the chessboard, and squares are numbered as usual.

1. In the beginning of the game, the White (respectively, the Black) has a Lord placed on _e1_ (_e8_), an lifeless Priestess on _d1_ (_d8_), two Elephants on _c1_ and _f1_ (_c8_ and _f8_), two Horses on _b1_ and _g1_ (_b8_ and _g8_), and two Chariots on _a1_ and _h1_ (_a8_ and _h8_).
The White (the Black) has eight Soldiers placed on _a2_, _b2_, ..., _h2_ (_a7_, _b7_, ..., _h7_).
Except for the lifeless Priestesses, all bodies are living.

   - All figures but Priestesses are placed on its analogous starting square in Chess, and Priestesses takes up the Queen square.

1. A _follower_ body (or soul) it is either a Priestess, a Chariot, an Elephant, a Horse, or a Soldier body (or soul).
A _warrior_ body (or soul) is either a Chariot, a Elephant, or a Horse body (or soul).

1. A Priestess body matches any warrior soul, and may host one, two, or three of them, which need not be of distinct class.

   - Thus, a Priestess-body may host, for example, a Chariot soul and a Elephant soul, or all of Chariot soul, Elephant soul, and Horse soul, or even two Horse souls, among 20 cases.
  But usually we expect it to host distinct souls, which make up 8 cases.

1. When a token or tokens _move_, it or they _go_ or _capture_, which we now examine.

1. A soul may _go_ alone from one body which hosts it to another lifeless body, where the new body must be of the same color with the old body.
A figure may also _go_ from a square to another empty square.
Such moves are legal when the initial square (that the old body lies on) and the final square (that the new body lies on) satisfy certain relation completely dictated by the class of the moving soul.
The action takes a tempo.

1. A Lord soul (and so a Lord) goes for either zero or one unit in either direction.

   - They move exactly like the King in Chess.
   There is no equivalent of castling in Oracle Chess.

1. A Chariot soul (and so a Chariot) goes for several units in one of the directions, provided that none of the squares which lies on the line that passes through both initial and final squares, is occupied.

   - They move exactly like the Rook in Chess.
  Recall that they can be blocked.

1. A Elephant soul (and so a Elephant) goes for several units in one of the directions, and the same number of units in the other direction, provided that none of the squares which lies on the line that passes through both initial and final squares, is occupied.

   - They move exactly like the Bishop in Chess.
  Recall that they can be blocked.

1. A Horse soul (and so a Horse) goes for two units in one of the directions, and one unit in the other direction.

   - They move exactly like the Knight in Chess.
  Recall that they cannot be blocked.

1. A Soldier soul (and so a Soldier) goes for two units in one of the directions, and one unit in the other direction.

   - They move exactly like the Pawn in Chess when they move.
   They cannot go for two squares the first time they move.

1. A lifeless body cannot go to another square, nor can a ill-suited body go.

   - It is helpful to think the soul drives the hosting body to go when they match, while the soul is able to go over bodies by itself.

1. A figure may also move to a square already occupied (by another figure, another ill-suited body, another lifeless body), where the occupying body must be of the opposite color with the figure.
When this happens, the occupying body and the soul it possibly hosts, leave the board.
We say the figure _captures_ the occupying body.
The action takes a tempo.

1. A Lord, a Priestess, a Chariot, an Elephant, and a Horse (except for a Soldier) capture the same way they go.
Namely, the initial square and the final square satisfy the same relation as they are when it is allowed to go.
When a Soldier capture, it moves horizontally for one unit, and forwards for one unit.

   - These are just same as Chess.

1. When a body leaves the board, it shall stay in the _earth_, and it switches its color from white to black, or from black to white.
When a soul leaves the board, it shall stay in the _underworld_.

1. When a Lord goes to an empty square, a lifeless body taken from the earth may be _fetched_ on the square the Lord formerly occupied, so that the fetched body returns to the board.
The fetched body may be any currently in the earth, except for the Priestess's.
Moreover, it must be of the same color as the Lord, and 
The action takes a tempo.
Other than the Lord, no friendly figure may fetch a body.

1. When a Priestess is able to host another soul, it may _summon_ a soul taken from the underworld, and host it, so that the summoned soul returns to the board.
The action takes a tempo.
Other than the Priestess, no friendly figure may summon a soul.

1. We remark that the total number of bodies present at the board and those absent from the board (thus in the earth), is conservative throughout the game.
In a similar fashion, the total number of souls present at the board and those absent from the board (thus in the underworld), is conservative throughout the game.

1. A figure consisting of a fetched body and a summoned soul is said to be _reborn_.
We see that rebirth is possible for any follower, except for the Priestess, and 

1. When a Soldier is already in the furthest rank from the start position (i.e., any square from _a8_ to _h8_ for White, and that from _a1_ to _h1_ for Black), and either or both Priestess body is absent from the board, it may be _promoted_ to a lifeless Priestess.
The body and soul of the Soldier shall stay in the earth and the underworld, respectively, as usual.

   - According to the above, it takes a tempo to move from the second-to-last rank to the last rank, and it takes another tempo (if it is not captured in that round).
   And promotion is not possible when both Priestesses are living.
   Notice that the soldier may remain in the last rank for indefinite time before it promotes (maybe in order to wait for either Priestess to get captured).

1. In each _position_, each body is of definite color and either lies on a certain square or stays in the earth, and each soul is either being hosted by a body or stays in the underworld.

   - A record of position is not only the situation on the board, but also the count of absent bodies and souls in the earth and underworld, as well as the color of absent bodies.

1. A friendly figure _attacks_ a living body, ill-suited body, or lifeless body, the figure is about to capture the latter in the next round, if it were to make another move on the present position.
A player _checks_ the opponent, the enemy lord soul is attackd by a friendly follower of the checking player.

1. Either one of the players _wins_ the game, so that the other _loses_, or the game ends in a _draw_.

1. A player wins the game if the enemy Lord soul is given a check, and no subsequent move of the opponent can stop the Lord soul from being checked.
In this case, the opponent is said to be _checkmated_.

   - Here I do not rule out the possibility that a Lord body is captured, but the Lord soul has not been so.

1. A player also wins if the opponent _resigns_.
If clock is used, a player may _lose on time_.

1. When either player has no legal move to make, the game is also drawn.
When it happens, it is called a _stalemate_.

   - It would seem exceedingly unlikely to happen under Oracle Chess, though.

1. The game results in a draw when a _threefold repetition_ happens, that is, a position has occurs for three times throughout the game.
   - It can be hard to keep track, though, and this is true also in Chess.
   I suggest that, when people play Oracle Chess on computer, that computer warn what move results in a threefold repetition.

1. And the game results in a draw if there are 32 consecutive _quiet_ rounds, which means that: no figure has ever captured, no soldier has ever moved, no Priestess has ever summoned a soul, and no Lord has ever fetched a body.
   - I suggest 32 instead of 50, not only because it is prettier, but because the nature of Oracle Chess seems to be more fierce.
If there are some theoretical win which requires more than 32 rounds, allow me to punish the side with slight advantage for not having gain one big enough.

1. When the 256 round ends, the game ends as a draw.
   - FIDE does not limit the absolute number of round in a Chess game.
   But, by the same reasoning, if Oracle Chess is more fierce, here when the game lasts for more than 256 rounds, I believe both sides must have been playing pretty contrively, and were not competitive.
   So that if there were indeed some theoretical game that one side can win by perfect play for more than 256 rounds, the side with advantage chose too quiet a line and only deserve a draw.

1. A draw is also valid if two players mutually agree so.

   - As for the forced draw equivalents in Oracle Chess, I do not think, as a formal rule, it is necessary to discuss it, since, techically, players may just continue until either 256-round limit is reached, or the 32-quiet-round is claimable.
