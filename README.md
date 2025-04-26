# AI Lab

This repository contains weekly assignments, projects, and practice work related to Reinforcement Learning (RL) and related AI topics.  
We use **Gymnasium** (the updated version of OpenAI Gym), classic control environments, and other simulation environments for experiments.

# Folder Structure

-  **Week 1**: Solving classic environments like **CartPole** and **MountainCar** using simple policies and initial environment exploration.

-  **Week 2**: Implementing graph-based search algorithms (like BFS/DFS) in actor databases — finding degrees of separation between actors.

-  **Week 3**: Building a **Tic Tac Toe** agent and introducing basic Minimax algorithm concepts.

-  **Week 4**: Solving combinatorial optimization problems like **N-Queens**, **Traveling Salesman Problem** (TSP) using random hill climbing methods.

-  **Week 5**: Introduction to **Multi-Armed Bandits** — exploring exploration vs exploitation dilemmas.

-  **Week 8**: Working with **FrozenLake** environment — value iteration and policy iteration methods.

-  **Week 9**: Solving **Cliff Walking** problem — learning basic **SARSA** and **Q-Learning** algorithms.

-  **Week 10**: Advanced exploration of **Cliff Walking** with updated learning strategies and hyperparameter tuning.

-  **Week 11**: Solving the **Taxi-v3** environment — implementing Q-Learning with full training and evaluation cycles.

# Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/adwaiy2912/AI-Lab.git
   cd AI-Lab
   ```

2. **Create and Activate a Virtual Environment (Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scriptsctivate
   ```

3. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is missing, install manually:

   ```bash
   pip install jupyter numpy pandas matplotlib seaborn scikit-learn gymnasium
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

# Notes

-  Gymnasium environments require some basic setup. If needed, install extras:
   ```bash
   pip install gymnasium[box2d]  # for environments like LunarLander
   pip install gymnasium[toy_text]  # for simple environments like FrozenLake, Taxi
   ```
-  Python files like `degrees.py` and `util.py` are helper modules for search and graph problems.
-  CSV datasets are included where needed for projects (e.g., Movie actor database, Ad Click datasets).
