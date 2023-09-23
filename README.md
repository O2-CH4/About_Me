<img width="300" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/47f6d405-a35a-451c-a13f-015b6396a075">







## 1) Overview & Interests 

- Canadian AI Graduate Student

- Previously a Graduate Research Intern at [CERVO Brain Research Center](https://cervo.ulaval.ca/en) in [Ethier’s Lab](https://scholar.google.ca/citations?user=9CzYcbAAAAAJ&hl=en) called the Neural Interface and Motor Plasticity Laboratory. There, I was completing my first Masters in Artificial Intelligence (Laval University) with a focus on Deep Learning techniques for Brain-Computer Interfaces (BCIs).

- I am currently pursuing my second Masters in Artificial Intelligence at UdeM / Mila, with a focus this time on more theoretical aspects of future AI architectures and learning paradigms. Although I am attracted to many problems, some of them can be synthesized via the quest of how to create multi-tasks agents with a grounded understanding of the world which leverage prior knowledge to learn with low-sample complexity.

- I can describe myself as a student with wide interests that is driven to understand complex problems and create utility for others. I mostly enjoy applying new tools from AI/Statistics to challenges in Sciences & Engineering.






 

## 2) Repository for Diverse Projects/Files


#### • [Kinematics Decoding from Rodent’s Primary Motor Cortex](LINK REPORT) 

- **Context**: Graduate Research Internship at CERVO
- **Overview**: Across this internship, I was responsible for developing an end-to-end pipeline for decoding kinematics variables using Deep Recurrent Neural Networks from raw intra-cortical neural recordings. Due to my previous experience in Brain-Computer Interface projects, I was mainly leading a small group of students (undergrads, masters, PhD) in order to design & develop various tools necessary for building datasets that could be used for training motor neural decoding models. Tools included: Experiment Design, Signal Processing, 3D markerless pose estimation, data pre-processing pipelines and decoders training pipelines. 
- **Future Avenues**: Although only single session models were trained, I established that it would be interesting if time allowed to explore in details the generalization capabilities of the trained decoders on different time scale, different tasks, and different rat subjects. Indeed, techniques such as large foundational neural decoders for motor control that could generalize across those settings could represent a paradigm shift from current methods when it comes to Brain-Computer Interfaces. An other interesting avenue could have been to explore various decoding/encoding learning architectures that could handle the larger amount of data that will be produced by the higher channel counts technologies of tomorrow while still displaying strong generalization. I think this will be an important aspect for accurately predicting more complex informations (higher doF motor decoding), which will be necessary for future prosthetics control.



<img width="200" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/376c9ef5-61f9-4d0b-9e92-92d2f083ca74"> <img width="200" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/78f6c685-f18c-4e86-9e71-f4cd8df0f00e"> <img width="200" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/251ad1ff-1bd8-4a97-96dc-00903fe9838d">







#### • [Avoiding Collapses in Non-Contrastive SSL Methods](https://github.com/O2-CH4/DL_Theoretical_SSL) 

- **Context**: Theoretical Principles for Deep Learning (Graduate Course) (UdeM/Mila)
- **Overview**: Non-Contrastive Self-Supervised Learning is considered as a potential training paradigm for acquiring large sets of prior knowledge from unlabeled multi-modal data. This could allow future AI agents to acquire a grounded understanding of their environnement and System-2 reasoning capabilities. To that end, I decided to investigate some properties of recent non-contrastive methods, more specifically how are they maximizing the information content of their representations in order to avoid different types of collapses.
- **Details**: Recent self-supervised learning methods for image representation are either classified as contrastive or non-contrastive. Contrastive methods operate by simultaneously minimizing the distance between two augmented views of the same data point (positive pairs) and maximizing views from different data points (negative pairs). While those techniques achieve state of the art results for image classification with few labeled samples, their use of negative pairs is making them limited in many aspects as their scaling potential is limited by the ability of finding suitable contrastive samples for training. Recently, many Non-Contrastive methods have shown competitive results without using any negative pairs, which raises the question of how those methods avoid any type of collapsing solutions to their loss function? Driven by those recent advances, the goal of this project report was to study in detail how and why some recent non-contrastive methods avoid any type of collapses via some specific architectural changes and regularization to their loss functions. In other words, how those methods can avoid trivial solutions that output constant solutions while keeping a high information content in their representations.




#### • [Graduate Quantum Computing Course -- Various Work](https://github.com/O2-CH4/Quantum_Computing_Files) 

- Took this course for pure personal interest (not counting in any degree) 
- **Result**: Submitted problems worth 35% of the session (29/35) 
- **Bonus**: I added the 2 presentations I gave in front of the class & Mr. Brassard. One is on Quantum-Enabled Secure Communications in Space and the other one is on Quantum Speedups for Deep Neural Networks Training (or more specifically for Non-Convex Optimization). 





#### • Museum Tour USA (Phase 2 -- Summer 2023)

- Drove 20 000 km in 2 weeks (again) to visit 20-30 aerospace/energy/science museums across almost all the USA.
- The goal was to visit the museums and cities I missed for various reasons during phase 1
- Some pictures: 


<img width="160" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/3753e311-84ca-4f62-8d40-ccc3956e8170"> <img width="160" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/00f426f9-646c-4b08-870b-c4b0dc62a073"> <img width="160" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/f7c290ed-1462-434f-a419-8e1780147e7b"> <img width="160" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/8d7dee69-97a4-427a-b254-8db9723467b2"> <img width="160" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/89ff379b-304f-47a4-95e4-2f89efd6e2b9">

<img width="300" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/d7c67376-85be-4516-b5db-6ed6ca6f0ef5"> <img width="300" alt="image" src="https://github.com/O2-CH4/About_Me/assets/118633117/00bfbe96-c308-48ee-8936-97ea4f335a6f">

 






#### • [Neural Decoding -- Spikes-Force Mapping](https://github.com/O2-CH4/Neural_Decoding_Force) 

- **Overview**: Neural Decoders were trained in order to assess the possibility of decoding the applied force on a knob sensor from the neural activity recorded from a rat primary motor cortex (M1). The activity was recorded from a Microwire Array with 32 channels. Several decoder architectures were tested in order to test the impact of different approach/design/parameters. 

- **Details**: This project can be seen as an extension of the initial Neural Decoding Project made with the assistance of Dr. Éthier's laboratory at the CERVO research center. In addition of the free-behaving behavioral data, rats were trained to apply a specific force on a knob, where a sensor recorded the applied force continuously during the recording in tandem with the Primary Motor Cortex (M1) activity. With the raw data, the project consisted of building pipelines for data pre-processing, dataset generation, and decoder training based on various architectures of deep neural networks. (Pipelines for data pre-processing, dataset generation, and models training can possibly be shared if necessary)




#### • [Deep Generative Models -- Cheat Sheet V1](https://github.com/O2-CH4/Deep_Generative_Models_Cheatsheet) 

- Took some weeks off to understand the fundamentals differences between some key Deep Generative Models 
- Those type of models are responsible for recent innovation in text, images, and video generation, which I find very useful.
- Produced a raw document and a condensed cheat sheet V1 (I will add further information/models this 2023 summer)



#### • [Inductor Magnetic Energy Estimation Based on a MLP Surrogate Model](https://github.com/O2-CH4/FEA_VS_Surrogates_Inductor_Design) 

- **Context**: ML Graduate Course
- **Overview**: Investigate the possibility of using ML/DL methods as fast & accurate surrogate approaches for approximating the exact mapping made by FEA methods on an Electro-Magnetic model for evaluating design parameters of an Inductor. 
- **Details**: Many complex engineering designs requires weeks of computations in order to assess the quality of a certain project design. Those computations often solve Partial Differential Equations (PDEs) in a precise manner via methods similar to Finite-Element-Analysis (FEA). In a simple example, extensive Computational Fluid Dynamics (CFD) calculations are necessary to quantify the effectiveness of a plane design (Ex: Evaluating lift, drag, etc.). Therefore, approximating via statistical models the mapping made by the PDEs between some design parameters and the effectiveness metrics of a design could accelerate by many orders of magnitude the design cycles of many engineering project as design evaluation could take seconds instead of weeks. This was the subject of our research project, where we tested the performance of multiple ML models for approximating the Magnetic Energy parameter of an inductor design based on design features like its multi-dimensional topology. 
- **Data**: The database of 100’000 samples has been provided by one of our team member from Switzerland (professor and researcher), and thus the data is proprietary (only to be used in this project) and owned by iCoSys (Institute of Complex Systems in Fribourg, University of Applied Science of Western Switzerland).





#### • [Neural Decoding from Rodent's Primary Motor Cortex](https://github.com/O2-CH4/Neural_Decoding_Behaviours) 

- **Context**: Bioinstrumentation & Biomedical Microsystems Graduate Course Project 
- **Overview**: Project which first involved the design and implementation of a Vision-System for collecting behavioral / kinematics data of free-behaving rats in order to subsequently process the raw data and train various Neural Decoders using the firing activity simultaneously recorded from the Primary Motor Cortex (M1). This was done in collaboration with Dr. Éthier's laboratory at CERVO, which I am grateful to for accepting of helping me realize this complex project. And as this was a graduate Electrical Engineering course, the signal processing involved and the hardware necessary for high-density microelectrode arrays recording was also analyzed in detail for this research project. Recurrent Deep Neural Network were used for the Neural decoding models. (Pipelines for data pre-processing, dataset generation, and models training can possibly be shared if necessary)



#### • [Graduate RL Course -- Various Work](https://github.com/O2-CH4/RL_Files)  
- **Work 1**: Theoretical Questions + Code Implementations of various Multi-Armed Bandits Strategies 
- **Work 2**: Theoretical Questions + Code Implementations of Deep-RL Strategies (Sarsa (λ) & DQN) 
- **Project**: Trade-offs between Model-Free and Model-Based Reinforcement Learning Methods
  - Subject chosen for strong alignment with interest of designing architectures for Multi-Task Continual Learning Agents.
  - Understanding and implementing MuZero was the key point of this project.



#### • [Graduate NLP Course -- Various Work](https://github.com/O2-CH4/NLP_Files)   
- **Work 1**: N-Gram Language Models, Text Classification using various Statistical Methods. 
- **Work 2**: MLP/Word Embeddings for Question Classification, LSTM for Neural Language Modeling & Sentence Completion 
- **Work 3**: Sequence Labeling with a fine-tuned Transformer Model (Task: Postal Address Analysis) 



#### • Museum Tour USA (Phase 1 -- Summer 2022) 

- Drove 20 000 km in 2 weeks to visit 20-30 aerospace/energy/science museums across almost all the USA.
- Some pictures: 

<img width="236" alt="image" src="https://user-images.githubusercontent.com/118633117/218298193-e0782f72-b39e-4b84-9d67-014c55f8c8c0.png"> <img width="230" alt="image" src="https://user-images.githubusercontent.com/118633117/218298196-3de65f07-f024-4fbb-94b4-6abe072311bb.png"> <img width="230" alt="image" src="https://user-images.githubusercontent.com/118633117/218298204-1738cc55-1f8c-420d-832e-851b80028d71.png"> <img width="229" alt="image" src="https://user-images.githubusercontent.com/118633117/218298209-c0d5967c-4fb0-49fb-84eb-8d2a99c458a8.png">








#### • [Stochastic Simulation and Design of Intelligent Systems](https://github.com/O2-CH4/Design_Simulation_Intelligent_Systems) 

- **Context**: Graduate course "Design & Simulation of Intelligent Systems for the 4.0 Industry"
- Two interesting projects:

**a) Monte-Carlo Simulations for Optimal Scenario Assessment (Robotic Automation of Port Activities)**
 - **Question**: Which robotic automation investment is the most optimal to do given some statistical distributions of the maritime traffic.
 - We simulated each possible scenario according to some assumed distributions (Inverse Transform Method)

**b) Simulation and Optimization of Wood Drying through Deep Reinforcement Learning**

- **Overview**: Research Project in partnership with a wood drying company active in North America 
- **Goal**: Assess the potential of Deep-Reinforcement-Learning combined with a detailed simulator (Digital Twin) for industrial optimization.
- **Details**: The complex simulation environment was created using Open AI Gym & Simpy in order to reproduce part of the operation processes. Then, a Deep-RL agent was trained to allocate efficiently some resources that are part of the industrial process operations. I directed the team towards choosing Deep-RL & Simulation-Learning as I really think this represents the future of robotics via sim-to-real transfer for efficiently training and optimizing robotic controllers/industrial processes. (Ex: Open AI -- Rubik Cube Solving, Nvidia-ETH Zurich -- Learning to Walk in Minutes Using Massively Parallel Deep-RL). PPO + Reward Engineering Technique "Heuristic-Guided Reinforcement Learning" were used.



#### • [3D Perception for Autonomous Vehicles — Various Work](LINK) 

- **Overview**: Various homeworks and assignments performed in the context of a graduate course on 3D sensing for AVs.
- **Topics**: ROS, 2D/3D Geometry & Transformations, Point Cloud Registration & Mapping, Lidars, …






#### • [Information Theory -- Various Work](https://github.com/O2-CH4/Information_Theory_Files)

- Devoir 1-4
- Submitted problems worth 40% of the session for the graduate course on Information Theory 
- Winter 2022 semester






#### • [Neural Combinatorial Solver Project (WTA Deep-RL)](https://github.com/O2-CH4/Neural_Combinatorial_Solver) 

- **Context**: Combinatorial Optimization Graduate course 
- **Overview**: Me and two other students realized a project relating the trade-offs made when using end-to-end neural solvers instead of traditional solving methods for combinatorial optimization problems. 
- **Details**: Neural Solvers approximate/learn an end-to-end policy that take a problem instance as input and output directly a solution to our problem that ideally optimize a desired objective function(s) and respect a set of constraints.  Problems can be Permutation or Assignment-based. In our work, we focused on comparing the results of a Graph Attention Neural Network architecture and a traditional solver on a specific assignment problem: The Weapon-Target Assignment (WTA). This defense-related problem seeks to assign interceptor (or missiles) from different weapon systems to targets in order to minimize the total expected destructive value of those incoming targets. We used reinforcement learning to parametrize our neural solver in order to learn an optimal policy, where the reward was the negative of the total expected destructive value of all targets after an assignment. If Supervised learning was used, we could say that the optimal policy was approximated. Solutions were generated autoregressively by our model at inference time. 



#### • [Critical Temperature Prediction for Superconducting Materials](https://github.com/O2-CH4/Superconductors_ML) 

- **Context**: Graduate ML Course 
- **Overview**: Project article on a data-driven approach for critical temperature (Tc) prediction of superconducting materials. 
- **Details**: Deep Neural Network models were used as surrogate models to learn the mapping between the features of known superconducting materials and their respective critical temperature (Tc) observed in laboratory.  A dataset of 21 263 superconductors was used with 82 attributes per superconductor, including characteristics of the materials such as the number of elements that compose them, their average atomic weights and the entropy of their atomic masses.



#### • [Theory behind ML Models + Code Implementations](https://github.com/O2-CH4/ML_Notebook) 

- Took 1 month of my summer 2021 to create an 80 pages documents on all the main Machine Learning Models (Theory + Code)
- The content was extracted from 20 books and multiple papers/blogs (Used Jupiter Notebooks and Python)
- Eventually served many friends looking to prepare themselves for the graduate ML course
- Also did a similar small document on the topic of Mathematical Modeling in order to introduce myself to some Julia implementations




### 4) Education 

- College Stanislas
- Grad-skipped one year
- Rochebelle High School International Program (IB)
- B.A Multidisciplinary (Laval University)
- M.S Computer Science (Laval University / CERVO) (2022-2023)
    * Focus: Deep Learning for Motor BCI Decoding 
- M.S Computer Science (UdeM/Mila) (2023-2024)
    * Focus: Theoretical Artificial Intelligence 

      - All graduate courses completed (to date): 
            - Information Theory
            - Combinatorial Optimization
            - Design & Simulation of Intelligent Systems for the 4.0 Industry
            - 3D Perception for Autonomous Vehicules
            - Reinforcement Learning
            - Natural Language Processing
            - Machine learning
            - Bioinstrumentation & Biomedical Microsystems
            - Quantum Computing (UdeM)
            - Theoretical Principles of Deep Learning (UdeM/Mila)
        
            - Reinforcement Learning and Optimal Control (On-Going)
            - Software Quality Assurance (On-Going)
            - Representation Learning (On-Going)

          
