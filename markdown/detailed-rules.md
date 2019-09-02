# Detailed Rules

This document is written rather formally and painstakingly for sake of rigor, and is intend to be a reference only.
Readers may want to read [Concise Rules](/markdown/concise-rules.md) first, if they have not done so.

1. The _Oracle Chess_ is a deterministic board game for two players, who are associated respectively with two colors, _White_ and _Black_.

   - Core definitions, in this document, are numbered to let them stand out, while explanatory commentary are interspersed, like now, and marked with a bullet point.

1. In playing the game, two players move _tokens_ on a _board_, take them away from it, or take them back onto it.
One moves tokens that at the moment pertain to their own color only, as prescribed below.
They move alternately, starting with White.
A _move_ (sometimes called a _tempo_) is also considered a discrete time index.
Two moves makes up a _round_.

1. There are two kinds of tokens, _bodies_ and _souls_, both of _classes_ of either of them.
A body is associated with either White or Black, but a soul is not.
All bodies of the same class and color is identical.
Likewise, all souls of the same class are identical.

1. A class of soul may either _match_ or _mismatch_ a class of body.
An instance of body can be united with an instance of soul, so that the body _hosts_ the soul, and the soul _possesses_ the body.

1. A _being_ consisting of a body and possibly one or more souls it hosts.
A being having one or more souls that all match is a _figure_ (or _man_), in which case the body is _living_.
A being having one or more souls that all match is a _ill-suited body_.
A body without a soul is not a figure, and we also call it an _lifeless body_.

1. There are the following classes of bodies: _Lord_, _Priestess_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ body.
There are the following classes of souls: _Lord_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ soul (without Priestess's).

1. A Lord, Chariot, Elephant, Horse, and Soldier body (except for Priestess) each matches (and may only match) the class of soul of same name, and can host exactly one soul, and the resulting figure is also named after the class.
Thus, a Lord body matches a Lord soul, and the being is called simply a Lord, likewise Chariot, Elephant, Horse, and Soldier are called as thus.

1. The _board_ is of square shape, spanned along two _directions_, extending for 8 unit distance _horizontally_ and _vertically_.
Thus it is made up of 64 discrete _squares_ on it, which are numbered from _a_ to _h_ in the horizontal direction, and from _1_ to _8_ in the vertical direction.
Each squares may either be _empty_, or may be _occupied_ by one being.

   - That is, we use just the chessboard, and squares are numbered as usual.

1. In the beginning of the game, the White (respectively, the Black) has a Lord placed on _e1_ (_e8_), an lifeless Priestess on _d1_ (_d8_), two Elephants on _c1_ and _f1_ (_c8_ and _f8_), two Horses on _b1_ and _g1_ (_b8_ and _g8_), and two Chariots on _a1_ and _h1_ (_a8_ and _h8_).
The White (the Black) has eight Soldiers placed on _a2_, _b2_, ..., _h2_ (_a7_, _b7_, ..., _h7_).
Except for the lifeless Priestesses, all bodies are living.

   - All figures but Priestesses are placed on its analogous starting square in Chess, while Priestesses takes up the Queen square.

1. A Priestess body matches a Chariot, Elephant, or Horse soul, and can host up to three of them, which need not be distinct.

   - Thus, a Priestess-body may host, for example, a Chariot soul and a Elephant soul, or all of Chariot soul, Elephant soul, and Horse soul, or even two Horse souls, among 20 cases.
   But usually we expect it to host distinct souls, which make up 8 cases.
 
 1. A Priestess that hosts a Chariot soul is also called a _induced_ Chariot, and same is said to Elephants and Horses.
A Priestess that hosts exactly Chariot and Elephant souls is a _Queen_;
that hosts exactly Chariot and Horse souls is a _Amazon_;
that hosts exactly Horse and Elephant souls is a _Witch_.
that hosts all of Chariot, Elephant, and Horse souls is a _Goddess_.

   - These are usually called fairy pieces, and I did not follow established terms.
   My Amazon is usually called a Empress, Chancellor, Marshal, or Elephant;
   My Witch, called a Princess, Archbishop, Cardinal, or Hawk;
   My Goddess, called an Amazon.

1. When tokens _move_, they _go to_ somewhere or _take on_ something, which we now examine.

1. A soul may _go_ alone from one body which hosts it to another body not fully possessed, 
A figure may also _go_ from a square to another empty square.
Such moves are legal when the initial square (that the old body lies on) and the final square (that the new body lies on) satisfy certain relation completely dictated by the class of the moving soul.
The action takes one move.
   
   - It is helpful to think the soul drives the hosting body to go when they match, while the soul is able to go over bodies by itself.


1. A Lord soul moves for either zero or one unit in either direction.

   - They move exactly like the King in Chess.
   There is no equivalent of castling in Oracle Chess.

1. A Chariot soul moves for several units in one of the directions, provided that none of the squares which lies on the line that passes through both initial and final squares, accomodates a soul.

   - They move exactly like the Rook in Chess.
  Recall that they can be blocked.

1. A Elephant soul moves for several units in one of the directions, and the same number of units in the other direction, provided that none of the squares which lies on the line that passes through both initial and final squares, accomodates a soul.

   - They move exactly like the Bishop in Chess.
  Recall that they can be blocked.

1. A Horse soul moves for two units in one of the directions, and one unit in the other direction.

   - They move exactly like the Knight in Chess.
  Recall that they cannot be blocked.

1. A Soldier soul goes for one unit forwards, but takes for one unit in one of the directions, and one unit in the other direction.

   - They move exactly like the Pawn in Chess.

1. To move, a body must be living.

   - Lifeless body and ill-suited body may not move.

1. When figures move, they move the same way apt to the possessing soul, but they are blocked by body on the blocking square, rather than soul.

   - So it is possible that a Chariot is blocked by a lifeless body right in the line of sight, but the Chariot soul may move, and so on.

1. A figure may also move to a square already occupied (by another figure, another ill-suited body, another lifeless body), where the occupying body must be of the opposite color with the figure.
When this happens, the occupying body and the soul it possibly hosts, leave the board.
We say the figure _takes on_ the occupying body.
The action takes one move.

   - We note that the possibility is not ruled out that a figure takes on another friendly body, that a soul goes to another enemy body, or that a soul takes on another friendly soul.

1. A Lord, a Priestess, a Chariot, an Elephant, and a Horse (except for a Soldier) take the same way they go.
Namely, the initial square and the final square satisfy the same relation as they are when it is allowed to go.
When a Soldier take, it moves horizontally for one unit, and forwards for one unit.

   - These are just same as Chess.

1. When a body leaves the board, it shall stay in the _earth_, and it switches its color from white to black, or from black to white.
When a soul leaves the board, it shall stay in the _underworld_.

1. When a Lord moves, a lifeless body taken from the earth may be _fetched_ on the square the Lord formerly occupied, so that the fetched body returns to the board.
The fetched body may be any currently in the earth, except for the Priestess bodies, and must be of the same color as the Lord.
The action takes one move.
Other than the Lord, no friendly figure may fetch a body.

1. In a similar fashion, when a Priestess grants a soul, it may _summon_ any soul currently in the underworld, and host it, so that the summoned soul returns to the board.
The action takes one move.
Other than the Priestess, no friendly figure may summon a soul.

1. We remark that the total number of bodies, present on the board or absent from the board (thus in the earth), is conservative throughout the game.
Similarly, the total number of souls present at the board and those absent from the board (thus in the underworld), is conservative throughout the game.

   - So a being of a fetched body and possibly a summoned soul is effectively reborn.
   Rebirth is not possible for a Priestess or a Lord.

1. When a Soldier is already in the furthest rank from the start position (i.e., any square from _a8_ to _h8_ for White, and that from _a1_ to _h1_ for Black), and either or both Priestess body is absent from the board, it may be _promoted_ to a lifeless Priestess.
The body of the Soldier move to the earth, and the soul to the underworld, as usual.

   - According to the above, it takes one move to move from the second-to-last rank to the last rank, and it takes another move (if it is not taken in that round).
   And promotion is not possible when both Priestesses are living.
   Notice that the soldier may remain in the last rank for indefinite time before it promotes (maybe in order to wait for either Priestess to get taken).

1. In each _position_, each body is of definite color and either lies on a certain square or stays in the earth, and each soul is either being hosted by a body or stays in the underworld.

   - A record of position is not only the situation on the board, but also the count of absent bodies and souls in the earth and underworld, as well as the color of absent bodies.

1. A friendly figure _attacks_ a figure, ill-suited body, or lifeless body, the figure is about to take on the latter in the next round, if it were to make another move on the present position.
A player _checks_ the opponent, the enemy lord soul is attackd by a friendly follower of the checking player.

1. Either one of the players _wins_ the game, so that the other _loses_, or the game ends in a _draw_.

1. A player wins the game if the enemy Lord soul is given a check, and no subsequent move of the opponent can stop the Lord soul from being checked.
In this case, the opponent is _checkmated_.

   - Here I do not rule out the possibility that a Lord body is taken, but the Lord soul has not been so.

1. A player also wins if the opponent _resigns_.
If clock is used, a player may _lose on time_.

1. When either player has no legal move to make, the game is also drawn.
The position is called a _stalemate_.

   - It would seem exceedingly unlikely to happen under Oracle Chess, though.

1. The game results in a mandatory draw when a _threefold repetition_ happens, that is, a position has repeated three times sequentially in three rounds.

   - This is stricter than FIDE Chess Rules, where threefold repetition does not have to be sequential, and the draw is not mandatory.

1.  The game ends as a draw, when the 256-th round is completed.
And the game results in a draw too, if there are 32 consecutive _quiet_ rounds, which means that: no figure has ever taken any being, and no soul has taken any soul, and no soldier has ever moved, and no Priestess has ever summoned a soul, and no Lord has ever fetched a body.

   - FIDE does not limit the absolute number of round in a Chess game.
   But in Oracle Chess, when the game lasts for more than 256 rounds, I believe both sides must have been playing pretty contrively, and were not competitive.
   And if there is indeed some theoretical position that one side can win by perfect play only for more than 32 rounds, I consider the side with advantage is not playing actively enough before the position is reached.

1. A draw is also valid if two players mutually agree so.

   - The so called force draw (analogous to something like king plus knight versus long king in Chess) need not be defined additionally.
   Indeed, techically, players may just continue until either 256-round limit is reached, or the 32-quiet-round is claimable.
