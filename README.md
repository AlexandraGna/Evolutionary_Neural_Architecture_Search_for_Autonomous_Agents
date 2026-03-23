# Evolutionary_Neural_Architecture_Search_for_Autonomous_Agents

Evolutionary Neural Architecture Search (ENAS) is an automated optimization technique that
can outperform human network designs while satisfying resource and performance constraints.
These automated network designs have gained popularity due to the increasing demand for reliable
and efficient neural network architectures in autonomous driving. This thesis introduces
novel strategies to improve upon state-of-the-art ENAS optimization methods for deep reinforcement
learning (DRL) agents in autonomous driving scenarios. Adjustments to fitness functions
were designed to prioritize rewards while balancing computational efficiency. A population initialization
strategy, which used a combination of random and well-performing designs, led to
better convergence rates in the early optimization phases. Transfer learning (TL) accelerated
learning in later generations by transferring learnt policies from earlier generations. This approach
reduced the training effort and achieved higher rewards, with findings highlighting the
stability of this method. However, the results also indicated the need for further refinement
of the TL method to maximize knowledge transfer in subsequent generations. Furthermore, a
credit assignment technique was developed to enhance already high-performing architectures.
The credit values of this technique were used to adjust the mutation probabilities of the operation
types within the architectures. These credit values were constantly updated based on
the results of the population evaluation at the end of each generation. The findings of these
strategies contribute positively to ENAS for DRL in autonomous driving, advancing the field
towards better-performing networks suitable for real-world scenarios.
