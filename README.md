# Trade-Smart: Reinforcement Learning (RL) Agent for Stock Markets
Re-inforcement Learning Agent that can help you automate decisions around:
1. When & at what Price to Buy a given Stock
2. When & What Price to Sell
3. What Quantity to Buy/Sell

A customized Re-inforcement Learning(RL) environment is part of the package to simluate real-world stock market. RL agent acts as a trader to learn securities price-action behavior. After sufficient training, it recognised patterns to make profitable trades.

![Trade-Smart: Reinforcement Learning (RL) Agent for Stock Markets](https://github.com/mohneesh-saxena/Trade-Smart/img.jpeg)

In the given setup, following steps were taken:
1. Stock Market Environment was created (ENV)
2. Apple Price Action was induced into the environment for 1st Learning Setup. (APPLE_ENV)
3. Additional features are added to the environment to provide additional intelligence to the Agent (APPLE_ENV)
4. Training of RL agent was performed on a randomized 5 year data set (1000 trading days). Let us say this agent is APPLE_RL_AGENT
5. APPLE_RL_AGENT generated profitable trades on a randomized 200 trading day test data (Randomized) (on an avg. 23-73% returns)  
6. Next step was to create another environment with Google Data set (GOOGLE_ENV)
7. APPLE_RL_AGENT was tested on GOOGLE_ENV on a randomized 200 trading day test data. (on an avg. 7-23% returns)

Option of transfer learning is also possible. Provisions are made in the code (main_file). You can make APPLE_RL_AGENT further learn on GOOGLE_ENV to optimize/generalize it policy parameters. 

Feel free to tweek the source code.
