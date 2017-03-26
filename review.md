# Review of AlphaGo

## Summary
The win of Google Deep Mind's Go algorithm, AlphaGo (REF), against Fan Hui, a 2. dan professional player, has been a major breakthrough in artificial intelligence (AI).  
After Deep Blue beat Kasparov in chess in 1996-97 (REF), the win of AlphaGo put AI back into the general publics mind. 
Go was considered very challenging given the complex nature of the game.

The huge search space of Go [][1], combined with the non tractability of a general value function, lead to to the interest of Go in the AI community was before not thought to be feasible, the reason lies in the huge state space of this game. Given the huge size of possible moves XYZ, makes any option for complete exploration of the game tree not tractable. 

What has been done before
Unlike to chess or checkers, minimax and alpha beta pruning have proven to be unsuccessful in Go (REF, Russell?). 
Monte carlo tree search in contrast to minimax has shown to be successful in playing go, here, the value function and the optimal policy is estimated using a huge amount
of monte carlo plays. 

Why is alpha go different
Unlike, eralier methods AlphaGo does not rely on compilicated rollout strategies for the monte carlo search tree, but uses a neural network to estimate its value function.  

Deep convolutional neural networks have been used to represent the spatial position of the game. 

Supervised learning reinforcement learning of policy networks

Training of value networks

Monte carlo tree search combining these networks
 
AlphaGo consists of a sophisticated AI pipeline, combining multiple strategies from artificial intelligence and machine learning.

## Result

Alpha Go outperforms leading go programs, Value network alone really good

The game outperformed not only the leading AI's in Go but also beat the ASJDF champion. 

The general performance of AlphaGo further examplified in games against in XYZ 2016, when it won 4 out of 5 games against.

## References
[1]: http://tromp.github.io/go/legal.html, retrieved on 03/08/2017