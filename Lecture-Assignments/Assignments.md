16061116
#### 问题1
> 在一个游戏中，主办方在三个门中任选一个，在门后放了一个奖品，另外两个门之后是空的。选手要在三个门中选择一个抽奖。 当选手选择了一个门，未曾打开门之前，主办方打开了另外两个门中没有奖品的那个门，并向选手说， 他可以改变他的选择，即转为选择剩下一个没有打开的门。 请问，如果选手此时改变选择， 他会提高或降低获奖的可能性么？提高多少？请给出你的分析。
* #### 解答
    设选手第一次选择了有奖品的门为事件A，选手改变选择为事件B，选手获奖为事件C，C可表示为A<span style="TEXT-DECORATION: overline">B</span>+<span style="TEXT-DECORATION: overline">A</span>B
    
    则P(C) = P(A<span style="TEXT-DECORATION: overline">B</span>+<span style="TEXT-DECORATION: overline">A</span>B) = P(A<span style="TEXT-DECORATION: overline">B</span>)+P(<span style="TEXT-DECORATION: overline">A</span>B)

    由于事件A与B相互独立

    则P(C) = P(A)P(<span style="TEXT-DECORATION: overline">B</span>)+P(<span style="TEXT-DECORATION: overline">A</span>)P(B) = P(A)[1-P(B)]+[1-P(A)]P(B) = P(A) + P(B) - 2[P(A)P(B)]

    带入P(A) = 1/3
    
    得P(C) = 1/3 + 1/3 * P(B)

    所以当P(B) = 1时，P(C)取最大值2/3，即选手改变选择能使获奖概率从原先的1/3提高到2/3

#### 问题2
> 如何看待 “中文房间” 问题，中文房间有智能么？它有什么样水平的智能？如何才能让它具有人类水平的智能？
* #### 解答
    1. 