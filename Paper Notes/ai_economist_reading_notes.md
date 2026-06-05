### Notes on the Paper --> The AI Economist: Optimal Economic Policy Design via Two-Level Deep Reinforcement Learning

#### Abstract:
AI and RL are not yet widely adopted in fields like economic policy design, mechanism design, or economics in general.

The limitations of current economic methods are,
-	Lack of counterfactual data (“what if” a particular event happened differently)
-	Simplistic behavioral methods (not quite taking into account human emotions, cognitive biases, or social pressures that can cause a deviation in decision-making succinctly)
-	Limited opportunities to experiment with policies and evaluate behavioral responses (in other words – lack of simulations mimicking the actual world)

The authors of the paper show that ML can be used to simulate economic scenarios, which is a strong policy and mechanism design framework for overcoming current limitations.

The AI Economist is broadly,
-	A two-level deep RL framework
-	It trains a) agents & b) a social planner – both of which who co-adapt
-	Provides an easy to manage solution to the highly unstable and novel two-level RL challenge

Simply put – we learn rational agent behaviors that adapt to learned planner policies, and planners who adapt to rational agent behaviors.

The authors demonstrate the efficacy of their solution through solving the problem of optimal taxation. There are two scenarios for that,
1)	Simple one-step economies: the AI Economist recovers the optimal tax policy of economic theory
2)	Complex and dynamic economies: the AI Economist significantly improves both utilitarian social welfare, and the trade-off between equality and productivity over baselines

The AI Economist solves the optimal taxation problem despite emergent tax-gaming strategies. It also accounts for agent interactions and behavioral change more accurately than economic theory

The authors conclude that this work demonstrates that two-level deep RL can be used for understanding, and complementing the theory of economic design.

Overall, this is a new computational learning-based approach to understanding economic policy. 
