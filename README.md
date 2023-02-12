<img width="120" alt="image" src="https://user-images.githubusercontent.com/118633117/218296532-2dda1a5a-ac8d-4827-903f-67f653cf60ee.png">



## 1) Overview: 


- Canadian AI Graduate Student 
- I see myself as a student with interdisciplinary interests that is driven to understand complex problems and create utility for others.
- Winter 2023: Currently following 2 courses in Montreal, which are Quantum Computing and Theoretical Principles of Deep Learning. 






## 2) Interests:

- Applying emerging tools from AI/Statistics to problems in Science & Engineering. 




## 3) Repository for Diverse Projects/Files:



#### • [Neural Decoding -- Spikes-Force Mapping](link:___) 

- **Overview**: Neural Decoders were trained in order to assess the possibility of decoding the applied force on a knob sensor from the neural activity recorded from a rat primary motor cortex (M1). The activity was recorded from a Microwire Array with 32 channels. Several decoder architectures were tested in order to test the impact of different approach/design/parameters. 

- **Details**: This project can be seen as an extension of the initial Neural Decoding Project made with the assistance of Dr. Éthier's laboratory at the CERVO research center. In addition of the free-behaving behavioral data, rats were trained to apply a specific force on a knob, where a sensor recorded the applied force continuously during the recording in tandem with the Primary Motor Cortex (M1) activity. With the raw data, the project consisted of building pipelines for data pre-processing, dataset generation, and decoder training based on various architectures of deep neural networks.




#### • [Deep Generative Models -- Cheat Sheet V1](link:____) 

- Took some weeks off to understand the fundamentals differences between some key Deep Generative Models 
- Those type of models are responsible for recent innovation in text, images, and video generation, which I find very useful.
- Produced a raw document and a condensed cheat sheet V1 
- I will add further information and models this 2023 summer.



#### • [Inductor Magnetic Energy Estimation Based on a MLP Surrogate Model](link:____) 

- **Context**: ML Graduate Course
- **Overview**: Investigate the possibility of using ML/DL methods as fast & accurate surrogate approaches for approximating the exact mapping made by FEA methods on an Electro-Magnetic model for evaluating design parameters of an Inductor. 
- **Details**: Many complex engineering designs requires weeks of computations in order to assess the quality of a certain project design. Those computations often solve Partial Differential Equations (PDEs) in a precise manner via methods similar to Finite-Element-Analysis (FEA). In a simple example, extensive Computational Fluid Dynamics (CFD) calculations are necessary to quantify the effectiveness of a plane design (Ex: Evaluating lift, drag, etc.). Therefore, approximating via statistical models the mapping made by the PDEs between some design parameters and the effectiveness metrics of a design could accelerate by many orders of magnitude the design cycles of many engineering project as design evaluation could take seconds instead of weeks. This was the subject of our research project, where we tested the performance of multiple ML models for approximating the Magnetic Energy parameter of an inductor design based on design features like its multi-dimensional topology.





#### • [Neural Decoding from Rodent's Primary Motor Cortex](link:_____) 

- **Context**: Bioinstrumentation & Biomedical Microsystems Graduate Course Project 
- **Overview**: Project which first involved the design and implementation of a Vision-System for collecting behavioral / kinematics data of free-behaving rats in order to subsequently process the raw data and train various Neural Decoders using the firing activity simultaneously recorded from the Primary Motor Cortex (M1). This was done in collaboration with Dr. Éthier's laboratory at CERVO, which I am grateful to for accepting of helping me realize this complex project. And as this was a graduate Electrical Engineering course, the signal processing involved and the hardware necessary for high-density microelectrode arrays recording was also analyzed in detail for this research project. Recurrent Deep Neural Network were used for the Neural decoding models. 



#### • [Graduate RL Course -- Various Work](link:_____)  
- Work 1: Theoretical Questions + Code Implementations of various Multi-Armed Bandits Strategies 
- Work 2: Theoretical Questions + Code Implementations of Deep-RL Strategies (Sarsa (λ) & DQN) 

- **Project**: Trade-offs between Model-Free and Model-Based Reinforcement Learning Methods
  - Subject chosen for strong alignment with interest of designing architectures for Multi-Task Continual Learning Agents.



#### • [Graduate NLP Course -- Various Work](link:_____)   
- Work 1: N-Gram Language Models, Text Classification using various Statistical Methods. 
- Work 2: MLP/Word Embeddings for Question Classification, LSTM for Neural Language Modeling used for proverb competition 
- Work 3: Sequence Labeling with a fine-tuned Transformer Model (Task: Postal Address Analysis) 



#### • Museum Tour USA 

- Drove 20 000 km in 2 weeks to visit 20-30 aerospace/energy/science museums across almost all the USA.
- Some pictures: 

<img width="236" alt="image" src="https://user-images.githubusercontent.com/118633117/218298193-e0782f72-b39e-4b84-9d67-014c55f8c8c0.png"> <img width="230" alt="image" src="https://user-images.githubusercontent.com/118633117/218298196-3de65f07-f024-4fbb-94b4-6abe072311bb.png"> <img width="230" alt="image" src="https://user-images.githubusercontent.com/118633117/218298204-1738cc55-1f8c-420d-832e-851b80028d71.png"> <img width="229" alt="image" src="https://user-images.githubusercontent.com/118633117/218298209-c0d5967c-4fb0-49fb-84eb-8d2a99c458a8.png">








#### • [Stochastic Simulation and Design of Intelligent Systems](link:____) 

- Context: Graduate course "Design & Simulation of Intelligent Systems for the 4.0 Industry"
- Two interesting projects:

**A) Monte-Carlo Simulations for Optimal Scenario Assessment (Robotic Automation of Port Activities)**
 - Question: Which robotic automation investment is the most optimal to do given some statistical distributions of the maritime traffic.
 - We simulated each possible scenario according to some assumed distributions (Inverse Transform Method)

**B) Simulation and Optimization of Wood Drying through Deep Reinforcement Learning**

- **Overview**: Research Project in partnership with a wood drying company active in North America 
- **Goal**: Assess the potential of Deep-Reinforcement-Learning combined with a detailed simulator (Digital Twin) for industrial optimization.
- **Details**: The complex simulation environment was created using Open AI Gym & Simpy in order to reproduce part of the operation processes. Then, a Deep-RL agent was trained to allocate efficiently some resources that are part of the industrial process operations. I directed the team towards choosing Deep-RL & Simulation-Learning as I really think this represents the future of robotics via sim-to-real transfer for efficiently training and optimizing robotic controllers/industrial processes. (Ex: Open AI -- Rubik Cube Solving, Nvidia-ETH Zurich -- Learning to Walk in Minutes Using Massively Parallel Deep-RL). PPO + Reward Engineering Technique "Heuristic-Guided Reinforcement Learning" were used.







#### • [Information Theory (diverse files)](link:___)

- Devoir 1
- Devoir 2
- Devoir 3
- Devoir 4

- Submitted problems worth 40% of the session for the graduate course on Information Theory 
- Winter 2022 semester






#### • [Neural Combinatorial Solver Project (WTA Deep-RL)](link:____) 

- **Context**: Combinatorial Optimization Graduate course 
- **Overview**: Me and two other students realized a project relating the trade-offs made when using end-to-end neural solvers instead of traditional solving methods for combinatorial optimization problems. 
- **Details**: Neural Solvers approximate/learn an end-to-end policy that take a problem instance as input and output directly a solution to our problem that ideally optimize a desired objective function(s) and respect a set of constraints.  Problems can be Permutation or Assignment-based. In our work, we focused on comparing the results of a Graph Attention Neural Network architecture and a traditional solver on a specific assignment problem: The Weapon-Target Assignment (WTA). This defense-related problem seeks to assign interceptor (or missiles) from different weapon systems to targets in order to minimize the total expected destructive value of those incoming targets. We used reinforcement learning to parametrize our neural solver in order to learn an optimal policy, where the reward was the negative of the total expected destructive value of all targets after an assignment. If Supervised learning was used, we could say that the optimal policy was approximated. Solutions were generated autoregressively by our model at inference time. 



#### • [Critical Temperature Prediction for Superconducting Materials](link:____) 

- **Context**: Graduate ML Course 
- **Overview**: Project article on a data-driven approach for critical temperature (Tc) prediction of superconducting materials. 
- **Details**: Deep Neural Network models were used as surrogate models to learn the mapping between the features of known superconducting materials and their respective critical temperature (Tc) observed in laboratory.  A dataset of 21 263 superconductors was used with 82 attributes per superconductor, including characteristics of the materials such as the number of elements that compose them, their average atomic weights and the entropy of their atomic masses.



#### • [Theory behind ML Models + Code Implementations](link:____) 

- Took 1 month of my summer 2021 to create an 80 pages documents on all the main Machine Learning Models (Theory + Code)
- The content was extracted from 20 books and multiple papers/blogs (Used Jupiter Notebooks and Python)
- Eventually served many friends looking to prepare themselves for the graduate ML course
- Also did a similar small document on the topic of Mathematical Modeling in order to introduce myself to some Julia implementations




### 4) Education 

- College Stanislas
- **Grad-skipped one year**
- Rochebelle High School International Program (IB)
- B.A Multidisciplinary (Laval University)
- M.S Artificial Intelligence (Transfering to UdeM)
      - 7 graduate courses already completed at Ulaval (GPA: 3.57/4.33)
            - Information Theory
            - Design & Simulation of Intelligent Systems for the 4.0 Industry
            - 3D Perception for Autonomous Vehicules
            - Reinforcement Learning
            - Natural Language Processing
            - Machine learning
            - Bioinstrumentation & Biomedical Microsystems
      - 2 currently following at UdeM (GPA: _ )
            - Theoretical Principles of Deep Learning
            - Quantum Computing
