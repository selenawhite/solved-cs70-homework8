Download Link: https://assignmentchef.com/product/solved-cs70-homework8
<br>
<h1>1          Counting, Counting, and More Counting</h1>

The only way to learn counting is to practice, practice, practice, so here is your chance to do so. For this problem, you do not need to show work that justifies your answers. We encourage you to leave your answer as an expression (rather than trying to evaluate it to get a specific number).

<ul>

 <li>How many ways are there to arrange <em>n </em>1s and <em>k </em>0s into a sequence?</li>

 <li>A bridge hand is obtained by selecting 13 cards from a standard 52-card deck. The order of the cards in a bridge hand is irrelevant.</li>

</ul>

How many different 13-card bridge hands are there? How many different 13-card bridge hands are there that contain no aces? How many different 13-card bridge hands are there that contain all four aces? How many different 13-card bridge hands are there that contain exactly 6 spades?

<ul>

 <li>Two identical decks of 52 cards are mixed together, yielding a stack of 104 cards. How many different ways are there to order this stack of 104 cards?</li>

 <li>How many 99-bit strings are there that contain more ones than zeros?</li>

 <li>An anagram of FLORIDA is any re-ordering of the letters of FLORIDA, i.e., any string made up of the letters F, L, O, R, I, D, and A, in any order. The anagram does not have to be an English word.</li>

</ul>

How many different anagrams of FLORIDA are there? How many different anagrams of ALASKA are there? How many different anagrams of ALABAMA are there? How many different anagrams of MONTANA are there?

<ul>

 <li>How many different anagrams of ABCDEF are there if: (1) C is the left neighbor of E; (2) C is on the left of E (and not necessarily E’s neighbor)</li>

 <li>We have 9 balls, numbered 1 through 9, and 27 bins. How many different ways are there to distribute these 9 balls among the 27 bins? Assume the bins are distinguishable (e.g., numbered 1 through 27).</li>

 <li>We throw 9 identical balls into 7 bins. How many different ways are there to distribute these 9 balls among the 7 bins such that no bin is empty? Assume the bins are distinguishable (e.g., numbered 1 through 7).</li>

 <li>How many different ways are there to throw 9 identical balls into 27 bins? Assume the bins are distinguishable (e.g., numbered 1 through 27).</li>

 <li>There are exactly 20 students currently enrolled in a class. How many different ways are there to pair up the 20 students, so that each student is paired with one other student?</li>

 <li>How many solutions does <em>x</em><sub>0 </sub>+<em>x</em><sub>1 </sub>+···+<em>x<sub>k </sub></em>= <em>n </em>have, if each <em>x </em>must be a non-negative integer? (l) How many solutions does <em>x</em><sub>0 </sub>+<em>x</em><sub>1 </sub>= <em>n </em>have, if each <em>x </em>must be a <em>strictly positive </em>integer?</li>

</ul>

(m) How many solutions does <em>x</em><sub>0 </sub>+<em>x</em><sub>1 </sub>+···+<em>x<sub>k </sub></em>= <em>n </em>have, if each <em>x </em>must be a <em>strictly positive </em>integer?

<h1>2          Binomial Beads</h1>

<ul>

 <li>Alistair is making school spirit keychains, which consist of a sequence of <em>n </em>beads on a string. He has blue beads and gold beads. How many unique keychains can he make with exactly <em>k </em>≤ <em>n </em>blue beads?</li>

 <li>Alistair decides to sell his keychains! He decides on the following pricing scheme:

  <ul>

   <li>Blue beads have a value of <em>x</em></li>

   <li>Gold beads have a value of <em>y</em></li>

   <li>The price of a keychain is the product of the values of all of its beads.</li>

  </ul></li>

</ul>

What is the price of a keychain with exactly <em>k </em>≤ <em>n </em>blue beads?

<ul>

 <li>Alistair decides to make exactly one of every possible unique keychain. If he sells every keychain he creates, how much revenue will he make? Use parts (a) and (b), and leave your answer in summation form.</li>

 <li>Draw a connection between part (c) and the binomial theorem.</li>

</ul>

(<em>x</em>+<em>y</em>)<em>n </em>= <em>x</em><em>ky</em><em>n</em>−<em>k</em>

<em>Hint: How do you calculate the product (x + y)(x + y)?</em>

<h1>3          Minesweeper</h1>

Minesweeper is a game that takes place on a grid of squares. When you click a square, it disappears to reveal either an integer ∈ [1<em>,</em>8], a mine, or a blank space. If it reveals a mine, you instantly lose. If it reveals a number, that number refers to the number of mines adjacent to that square (including diagonally adjacent). If it reveals a blank space, there were 0 mines adjacent to it.

You are playing on a 8×8 board with 10 mines randomly distributed across the board. In your first move, you click a square near the center of the board.

<ul>

 <li>What is the probability that the square reveals…

  <ol>

   <li>a mine?</li>

   <li>a blank space?</li>

  </ol></li>

</ul>

<ul>

 <li>the number <em>k</em>?</li>

</ul>

<ul>

 <li>The first square you picked revealed the number <em>k</em>. For your next move, you want to minimize the probability of picking a mine. Should you pick a square adjacent to your first pick, or a different square? Your answer should depend on the value of <em>k</em>.</li>

 <li>Your first move resulted in the number 1. You pick the square to the right for your next move.</li>

</ul>

What is the probability that this square reveals the number 4?

<h1>4          Playing Strategically</h1>

Bob, Eve and Carol bought new slingshots. Bob is not very accurate hitting his target with probability 1<em>/</em>3. Eve is better, hitting her target with probability 2<em>/</em>3. Carol never misses. They decide to play the following game: They take turns shooting each other. For the game to be fair, Bob starts first, then Eve and finally Carol. Any player who gets shot has to leave the game. The last person standing wins the game. What is Bob’s best course of action regarding his first shot?

<ul>

 <li>Compute the probability of the event <em>E</em><sub>1 </sub>that Bob wins in a duel against Eve alone, assuming he shoots first.</li>

 <li>Compute the probability of the event <em>E</em><sub>2 </sub>that Bob wins in a duel against Eve alone, assuming he shoots second.</li>

 <li>Compute the probability of the same events for a duel of Bob against Carol.</li>

 <li>Assuming that both Eve and Carol play rationally, conclude that Bob’s best course of action is to shoot into the air (i.e., intentionally miss)! (Hint: What happens if Bob misses? What if he doesn’t?)</li>

</ul>

<h1>5          Weathermen</h1>

Tom is a weatherman in New York. On days when it snows, Tom correctly predicts the snow 70% of the time. When it doesn’t snow, he correctly predicts no snow 95% of the time. In New York, it snows on 10% of all days.

<ul>

 <li>If Tom says that it is going to snow, what is the probability it will actually snow?</li>

 <li>What is Tom’s overall accuracy?</li>

 <li>Tom’s friend Jerry is a weatherman in Alaska. Jerry claims that she is a better weatherman than Tom even though her overall accuracy is lower. After looking at their records, you determine that Jerry is indeed better than Tom at predicting snow on snowy days and sun on sunny days. How is this possible?</li>

</ul>

<em>Hint: what is the weather like in Alaska?</em>