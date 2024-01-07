# Reinforcement_Learning_Taxi_Driver
The Reinforcement Learning (RL) approach using Q-learning algorithms to train an agent that can autonomously navigate the Taxi environment, demonstrating improved decision-making and task efficiency over time. The effectiveness of the learned policy is assessed through training and testing outcomes. Below are short summarizes from the outcomes of using RL in the Taxi driver application:

<b>Initialization and Validation</b>
   + Outcome: Samples a random action considering an action mask, applies the action to transition to the next state, and provides visual and console outputs for validation purposes.
   + Observation: Verify that the environment is set up correctly and that the random action sampling and state transitions are functioning as expected.

![image](https://github.com/bachthyaglx/Reinforcement_Learning_Taxi_Driver/assets/62774638/4f842dc6-e954-439e-a90e-cf9690061f08)

<b>Testing a random agent</b>
   + Outcome: Simulates the Taxi task with a random agent, where the agent takes random actions without considering any learned policy.
   + Observation: The Taxi takes random actions without any learned policy, exhibits unpredictable and often inefficient behavior in the Taxi-v3 environment

![image](https://github.com/bachthyaglx/Reinforcement_Learning_Taxi_Driver/assets/62774638/1560f4b4-e3c3-445b-bcfa-11de6196e203)

<b>Training the agent</b>
   + Outcome: The final trained policy is evaluated based on the number of epochs and failed drop-offs.
   + Observation: The goal is to achieve a policy that minimizes the number of epochs and failed drop-offs, indicating efficient navigation and successful task completion.

![image](https://github.com/bachthyaglx/Reinforcement_Learning_Taxi_Driver/assets/62774638/b664b604-79a0-4ca3-b8f3-b7c84fbd9c3c)
![image](https://github.com/bachthyaglx/Reinforcement_Learning_Taxi_Driver/assets/62774638/5c9d3a63-37ab-4b5a-b719-42c053ac09f1)

<b>Testing the policy</b>
   + Outcome: The script tests the performance of the agent after training using the Q-learning algorithm.
   + Observation: Evaluates the trained policy's performance, and the observations and visualizations provide insights into how well the agent applies its learned knowledge to complete the task after the training phase.

![image](https://github.com/bachthyaglx/Reinforcement_Learning_Taxi_Driver/assets/62774638/581de439-37b1-4479-b3f9-fd917d670174)

![image](https://github.com/bachthyaglx/Reinforcement_Learning_Taxi_Driver/assets/62774638/2ebea46d-b8ef-489b-8d52-8179f7b44c56)

# Python environment instructions

### Installation:
c:
cd C:\(...)\Lec1_ Reinforcement Learning

### Windows:
python -m venv .venv
.venv\Scripts\activate.bat

### Linux, MacOS:
.venv/Scripts/activate
pip install -r requirements.txt

### Launch:
c:
cd (...)\Lec1_ Reinforcement Learning

### Windows:
.venv\Scripts\activate.bat
Linux, MacOS:
.venv/Scripts/activate

### Spyder
jupyter notebook
