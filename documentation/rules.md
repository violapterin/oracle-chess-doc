
# Oracle Chess Rules
_idea created Aug. 21, 2019_
first draft Aug. 22, 2019

1. The _Oracle Chess_ is a novel chess-variant, a deterministic board game for two players based on Chess.
Apart from substantial similarity to the canonical Chess, in the game we introduce several features:
First, rather than solid pieces, there are bodies and souls which may separate;
second, we allow rebirth of men on certain circumstances;
third, in place of Queen, there is the new piece &mdash; Priestess, and its different induced forms, as follows.

	- Core definitions, in this document, are numbered to let them stand out, while explanatory commentary are interspersed, like now, and marked with a bullet point.

1. In playing the game, two players, called _White_ and _Black_, tokens of their own color on a _chessboard_.
They move alternately, starting with White.

1. There are two kinds of tokens, _bodies_ and _souls_, each of several kinds.
Bodies are marked with white or black, but souls are not.
A kind of soul may either _match_ or _mismatch_ a kind of body.
A particular instance of soul may _bear_ a particular instance of body, so that they are _united_.

1. A compound of one body and one or more matching souls is called a _man_, and the body is said to be _living_.
A compound of one body and one or more mismatching souls is called a _mistaken body_.
To be clear, a body without a soul is not said to be a man, and we also call it a _dead body_.

	- I promise the whole idea is really easy, but I am sorry that we have to introduce a few terminologies to be more precise.

1. There are the following kinds of bodies: _Lord_, _Priestess_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ body.
There are the following kinds of souls: _Lord_, _Chariot_, _Elephant_, _Horse_, and _Soldier_ soul (without Priestess's).

1. A Lord, Chariot, Elephant, Horse, and Soldier body (except for Priestess) each matches the kind soul called by the same name, and the name also refers to the resulting man.
Thus, a Lord body matches a Lord soul, and the compound is called simply a Lord, likewise Chariot, Elephant, Horse, and Soldier are called as thus.

1. The _chessboard_ is of square shape, spanned along two _directions_, for 8 _units_.
Thus it is made up of 64 discrete _squares_ on it, which are numbered from _a_ to _h_ in the horizontal direction, and from _1_ to _8_ in the vertical direction.
Each _squares_ may be _empty_, or may accommodate exactly one body, one mismatched body, or one man.

	- That is, we use just the traditional chessboard, numbered as usual.

	- All men but Priestesses are placed on its analogous starting square in Chess, and Priestesses takes up the Queen square.

1. In the beginning of the game, the White (respectively, the Black) has Lords placed on _e1_ (_e8_), Priestess body on _d1_ (_d8_), Elephants on _c1_ and _f1_ (_c8_ and _f8_), Horses on _b1_ and _g1_ (_b8_ and _g8_), and Chariots on _a1_ and _h1_ (_a8_ and _h8_).
The White (the Black) has Soldiers placed on _a2_, _b2_, ..., _h2_ (_a7_, _b7_, ..., _h7_).
To be clear, all bodies but the Priestesses' are living, and the Priestesses are dead.

1. A _follower_ is either a Priestess, a Chariot, a Elephant, a Horse, or a Soldier.
A _warrior_ is either a Chariot, a Elephant, or a Horse.

1. A Priestess body matches warrior souls, and may bear with one, two, or three of them, which need not be of distinct kind.

	- Thus, a Priestess-body may bear, for example, a Chariot soul and a Elephant soul, or all of Chariot soul, Elephant soul, and Horse soul, or even two Horse souls, among 20 cases.
  But usually we expect it to bear distinct souls, which make up 8 cases.

1. A man may move from one square to another square on the chessboard, when the final square is empty, in the manner completely dictated by its soul.
When a men move, the body and the soul stay united.

	- Each kind of soul moves differently, which we now examine.

1. A Lord moves for either zero or one unit in either direction.

	- The Lord moves exactly like the King in Chess.

1. A Chariot moves for several units in one of the directions, provided that none of the squares which lies on the line that passes through both initial and final squares, is occupied.

	- The Chariot moves exactly like the Rook in Chess.
  Recall that it can be blocked.

1. A Elephant moves for several units in one of the directions, and the same number of units in the other direction, provided that none of the squares which lies on the line that passes through both initial and final squares, is occupied.

	- The Elephant moves exactly like the Bishop in Chess.
  Recall that it can be blocked.

1. A Horse moves for two units in one of the directions, and one unit in the other direction.

	- The Horse moves exactly like the Knight in Chess.
  Recall that it cannot be blocked.

1. The soul of a man may also move, alone, from one square to another square on the chessboard, the same way it does together with the matching body, when on the final square lies a dead body.
Afterwards the soul is considered to unite with that dead body, leaving behind the original body.

1. A dead body cannot move to any square.
Likewise, a mistaken body cannot move to any square, neither by itself, nor together with the mismatching soul it now bears, either.

	- It is helpful to think the soul drives the body when they match, while soul is able to move alone on top of bodies.

1. A men or a body may be captured.

1. When a body is captured, it goes to the _earth_, and it switches its color from white to black, or from black to white.
When a soul is captured, it goes to the _underworld_.
The number of bodies on the chessboard and in the earth is conservative, throughout the game.
And so does the number of souls on the chessboard and in the underworld.

