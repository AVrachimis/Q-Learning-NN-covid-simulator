# Double Q-Learning with Function Approximation using NN - Covid Simulator

## Abstract

>The report investigates the implementation of AI policies and their repercussions in a COVID-19 simulated environment. Three agents have been designed, implemented and tested against one another. Random, Deterministic and Q-Learning Agent with Function Approximation and Neural Networks are among the approaches examined. Despite the different types of environments, Q Learning proved to be the more effective and robust agent. Furthermore, an extension of the Q-Learning agent has been proposed, enhancing the model's generalization, and finally, the use of established policies has been mirrored in real-world contexts.
-------

## Motivations
>Countries all across the world are dealing with an uncommon challenge as a result of the ongoing COVID-19 outbreak. To ameliorate and eventually overcome this predicament, each government must take restrictive measures on its own. Because of the uncertainties surrounding COVID-19, governments frequently take incorrect actions, irritating residents and aggravating the pandemic's situation. Using the ViRL simulated COVID-19 environment, three distinct policies will be studied utilizing a number of various methodologies such as Reinforcement Learning, aiming to mitigate the risk of the COVID-19 pandemic.
-----

## ViRL Environment
>The environment utilized in the coursework is [ViRL](https://git.dcs.gla.ac.uk/SebastianStein/virl). It is a Reinforcement Learning environment that has been used to simulate the ongoing COVID-19 pandemic. We can control the virus transmission, based on the restrictive measures taken or otherwise actions. Each weekly action taken has a varied impact on the overall number of simultaneously infected and hospitalized persons, the infection rate and the economic opportunity cost, all of which are then combined into a single negative value termed reward. An optimal action on a current state is translated into a maximum weekly reward. The main objective of the environment is to replicate a 52 weeks pandemic with the highest possible total reward. As a result, the actions implemented each week must have the least impact based on the current situation/state. Original Author: Sebastian Stein
-----

[Colab Link](https://colab.research.google.com/drive/1QM57-LO1g81qR27ERZbO_O_2-ULot8WJ?usp=sharing)
