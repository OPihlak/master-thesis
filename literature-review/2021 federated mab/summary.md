It presents a new framework paralleling the federated learning (FL) framework,
specifically designed for multi-armed bandit problems. It addresses applications like cognitive radio and recommender
systems, embodying features similar to FL. The paper introduces a general FMAB framework and delves into two specific
federated bandit models. It tackles the approximate model where local models are considered heterogeneous and random
realizations of a global model, introducing client sampling uncertainty. The Federated Double UCB (Fed2-UCB) algorithm
is proposed to handle uncertainties from both arm and client sampling, emphasizing the importance of gradually
integrating new clients to achieve optimal regret while considering communication costs. Additionally, an exact model
where the global bandit model precisely averages the local models is examined, showing that optimal regret can be
independent of client numbers with appropriate update timing. Theoretical insights and real-world dataset experiments
validate the framework's efficacy, providing a nuanced understanding of federated multi-armed bandit problems.