# KTH-ID2209-Course-Project

## **Project Overview**  
This project is developed as part of the **Distributed Artificial Intelligence and Intelligent Agents** course at **KTH Royal Institute of Technology**. The main objective is to simulate the behavior and interactions of different types of agents in various environments. The project also includes a **BDI (Belief-Desire-Intention) agent** implementation to enhance the decision-making capability of the agents.

## **Agent Interactions**  
Each agent type was programmed with specific actions and reactions, influenced by attributes such as sociability, generosity, and tolerance. The interactions were designed to reflect realistic social behaviors. 
| Place   | Guest1      | Guest2      | Action                                 | Reaction                                           |
| ------- | ----------- | ----------- | -------------------------------------- | -------------------------------------------------- |
| Bar     | Party       | Introverted | Invites for a drink                    | Accepts the invitation with appreciation.          |
| Bar     | Observer    | Meat Eater  | Asks, "What brings you here?"          | Responds, "The food here."                         |
| Bar     | Vegan       | Introverted | Invites for small talk                 | Accepts the invitation with appreciation.          |
| Bar     | Meat Eater  | Vegan       | Invites for steak                      | Politely declines, mentioning dietary preferences. |
| Bar     | Party       | Observer    | Invites to dance                       | Accepts the invitation enthusiastically.           |
| Concert | Party       | Vegan       | Asks, "Do you like the music?"         | Responds positively, expressing enjoyment.         |
| Concert | Introverted | Observer    | Asks, "What do you think of the band?" | Responds positively, expressing approval.          |
| Concert | Observer    | Introverted | Comments, "You must be enjoying it."   | Agrees, expressing enjoyment.                      |
| Concert | Vegan       | Meat Eater  | Comments, "The salad is amazing!"      | Acknowledges but mentions not having salad.        |
| Concert | Meat Eater  | Party       | Invites for burgers                    | Accepts the invitation with appreciation.          |

## **Installation & Execution**  
1. Install **GAMA platform** from [GAMA Official Website](https://gama-platform.org/).  
2. Clone this repository:  
   ```sh
   git clone https://github.com/yourusername/DAIIA-Project.git
   cd DAIIA-Project
