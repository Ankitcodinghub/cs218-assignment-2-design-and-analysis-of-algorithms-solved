# cs218-assignment-2-design-and-analysis-of-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [CS218 Assignment 2-Design and analysis of algorithms Solved](https://www.ankitcodinghub.com/product/cs218-design-and-analysis-of-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110115&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS218 Assignment 2-Design and analysis of algorithms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
A game on graphs: Consider a two player game played on a complete directed graph with weights on its edges {wi,j : 1 ≤ i 6= j ≤ n}. The game starts with a token being present on the vertex v1. The two players alternately make a move in the game. A player, when it is their turn, moves the token from its current vertex i to a different vertex j and gets a reward of wi,j. The total number of moves for allowed for each player is pre-determined, say m. Whichever player has the higher total reward at the end wins. In case the two players have equal total rewards, player 2 is declared as winner.

For example, consider the following game on a graph with 4 vertices. The edge weights are given by the following table.

v1 v2 v3 v4

v1 – 10 5 3

v2 9 – 7 12

v3 2 8 – 6

v4 5 13 4 –

Suppose the number of allowed moves is m = 2 for each player. Consider the following play of the game:

• player 1 : v1 → v3. Gets a reward of 5 points.

• player 2 : v3 → v4. Gets a reward of 6 points.

• player 1 : v4 → v1. Gets a reward of 5 points.

• player 2 : v1 → v2. Gets a reward of 10 points.

The total reward for player 1 is 10 and for player 2 it is 16. Hence player 2 wins.

In fact, in this particular game, player 2 has a strategy to win irrespective of how player 1 plays. We demonstrate this in Figure 1.

Figure 1: An example of a game, where irrespective of how Player 1 plays, Player 2 can find a way to have a higher total reward at the end.

1

Observe that in any given game, either player 1 or player 2 will have a winning strategy. To see this formally, suppose m = 2. Then player 2 has a winning strategy if

∀vi ∃vj ∀vk ∃v`, w1,i + wj,k ≤ wi,j + wk,`.

If player 2 does not have a winning strategy, then we get the negation of the above statement, which is equivalent to

∃vi ∀vj ∃vk ∀v`, w1,i + wj,k &gt; wi,j + wk,`.

This is nothing but saying that player 1 has a winning strategy.

For any given game, the task is to compute which player has a winning strategy.

Instructions

Input contains n(n − 1) + 2 lines.

Line 1: n (the number of vertices in the graph)

Line 2: m (the number of allowed moves for each player)

Line 3: w1,2

Line 4: w1,3

…

Line n + 1: w1,n Line n + 2: w2,1

Line n + 3: w2,3

…

Line (n(n − 1) + 2): wn,n−1 Output :

1 or 2 (which player has a winning strategy)

• Programming Language: C++. We will compile your code with g++. Make sure that it works.

• Submission: put your code in a file named XXX.cpp where XXX is your roll number. Also, write a short explanation (a paragraph) of what your algorithm does, put this in XXX.pdf. The two files should be uploaded on Moodle (do not zip/compress).

• Given files: In the GraphGame folder, you will find: (i) helper.cpp (a c++ code showing expected input/output, feel free to use) (ii) Few sample input and output files, (iii) an executable file, which can be used to get the correct output on any input.

• Running time: we will test your code on some similar size instances as given in the sample input file. If your program runs in time polynomial in n and m, that should be good enough. An exponential running time like (n − 1)m will be too slow to pass the inputs.

• Grading: The test cases will be of varying sizes (will keep n ≤ 50 and m ≤ 100). Since the output is simply 1 or 2, one can try to generate the answer randomly and hope to be correct on half of the inputs. To catch this, we will run on each input multiple times and expect the same answer.

2
