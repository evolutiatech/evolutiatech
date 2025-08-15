<!--
**evolutiatech/evolutiatech** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### About Me, Davada Beni Zaita

<p align="justify">  
I am a passionate engineer and innovator dedicated to pushing the boundaries of technology and shaping the future. With a steadfast commitment to excellence and a curiosity that fuels continuous learning, I thrive at the intersection of engineering and innovation. Harnessing cutting-edge advancements and state-of-the-art solutions, I strive to develop impactful technologies that solve real-world problems and elevate industries. My journey is driven by a relentless pursuit of innovation, a meticulous attention to detail, and an unwavering belief that technology can transform lives. As a forward-thinker in the realm of engineering, I embrace emerging trends such as artificial intelligence, automation, and sustainable design, integrating them into my projects with precision and creativity. My goal is to contribute to a smarter, more sustainable future through engineering excellence and innovative thinking.I believe that true progress stems from collaboration, curiosity, and a passion for discovery. With each challenge I face, I see an opportunity to pioneer new solutions and set new standards of excellence in technology and engineering.
</p>

![Image](https://github.com/user-attachments/assets/9085094a-282e-4f9d-b04b-ec01b8924d42)

---
<p align="justify">
Devarim 14: 4 - 10 "Howbeit there shall be no needy among you--for HaShem will surely bless thee in the land which HaShem thy G-d giveth thee for an inheritance to possess it-- if only thou diligently hearken unto the voice of HaShem thy G-d, to observe to do all this commandment which I command thee this day. For HaShem thy G-d will bless thee, as He promised thee; and thou shalt lend unto many nations, but thou shalt not borrow; and thou shalt rule over many nations, but they shall not rule over thee. If there be among you a needy man, one of thy brethren, within any of thy gates, in thy land which HaShem thy G-d giveth thee, thou shalt not harden thy heart, nor shut thy hand from thy needy brother; but thou shalt surely open thy hand unto him, and shalt surely lend him sufficient for his need in that which he wanteth. Beware that there be not a base thought in thy heart, saying: 'The seventh year, the year of release, is at hand'; and thine eye be evil against thy needy brother, and thou give him nought; and he cry unto HaShem against thee, and it be sin in thee. Thou shalt surely give him, and thy heart shall not be grieved when thou givest unto him; because that for this thing HaShem thy G-d will bless thee in all thy work, and in all that thou puttest thy hand unto. "
</p>

---

### • To do money for open colletive projects

https://opencollective.com/

https://github.com/opencollective

---

### • AI Personal Development

---

• For AI Help: https://www.deepseek.com 

• For AI Private GPT4ALL - TEST LAB: https://www.nomic.ai/gpt4all

• For Trained AI - TEST LAB: https://huggingface.co

    - https://huggingface.co/models
    
    - https://huggingface.co/datasets
    
    - https://huggingface.co/spaces 
---  

<p align="justify">


### Cyberspace - jammer and fire laser attack

<img width="732" height="413" alt="Image" src="https://github.com/user-attachments/assets/96112dd9-34f4-4249-8089-a5db7fc91945" />

</p>

<p align="justify">

---

### Air Defense System - NASAMS

---

![Image](https://github.com/user-attachments/assets/090f3d13-cdb4-49b9-b218-d59d3e1c2e6a)

---
#### Built Nationally Military Engineers with an indefinite period until is a "RETIRED".

---

### NASAMS (National Advanced Surface-to-Air Missile System) 

A comprehensive covering additional details about NASAMS, including technical specifications, operational scenarios, development considerations, and how to approach modeling or learning more about the system.

---

### **Detailed Technical Specifications**

|             Aspect           |                                                            Details                                                        |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| **System Type**              | Medium-range surface-to-air missile defense system                                                                        |
| **Primary Missiles**         | AIM-120 AMRAAM (adapted for surface launch)                                                                               |
| **Range**                    | Up to approximately 25 km (varies depending on missile variant and target)                                                |
| **Engagement Altitude**      | Up to 15-20 km                                                                                                            |
| **Reaction Time**            | Less than 10 seconds from target detection to missile launch                                                              |
| **Mobility**                 | Road-mobile, typically mounted on standard military trucks or trailers                                                    |
| **Radar**                    | AN/MPQ-64 Sentinel or equivalent, capable of target detection at long ranges                                              |
| **Command & Control**        | Centralized Fire Distribution Center (FDC) with real-time data processing                                                 |
| **Networked Architecture**   | Can be integrated with other sensors and command systems such as NATO’s Integrated Air and Missile Defense (IAMD) network |

---

### **Operational Scenarios**

- **Point Defense:** Protect critical infrastructure like airports, military bases, power plants, and government facilities.
- **Area Defense:** Cover a broader area by deploying multiple NASAMS units working together.
- **Layered Defense Integration:** Combine with long-range systems like the Patriot or S-400 to create multi-tiered defense architectures.
- **Threat Types Addressed:**
  - Aircraft and fighter jets
  - Drones and UAVs
  - Cruise missiles
  - Short-range ballistic missiles (with upgrades)

---

### **Development and Deployment Considerations**

- **Integration with Existing Systems:** Ensuring compatibility with national and NATO command networks.
- **Upgradability:** Modular hardware and software for future missile types and sensor upgrades.
- **Training and Simulation:** Development of realistic training environments for operators using simulation tools.
- **Maintenance & Logistics:** Establishing supply chains for missiles, spare parts, and system maintenance.
- **Legal & Strategic:** Compliance with international treaties and strategic stability considerations.

---

</p>

<p align="justify">
  
#### Developing a **computational model** of NASAMS, especially with a focus on **AI integration** and implementing it in **ANSI C89/90**, is a substantial project. Below is an extended, structured guide that covers **system architecture**, **core components**, **AI integration considerations**, and **sample code snippets** to help you get started.

---

### **Developing a NASAMS with AI in ANSI C89/90**

## 1. **System Architecture Overview**

### Core Components:
- **Sensor Module (Radar)**
- **Target Detection & Tracking**
- **Fire Control & Engagement Logic**
- **Missile Guidance & Control**
- **AI Module (for decision-making, target prioritization, adaptive tactics)**
- **Simulation Environment (for scenario testing)**

### Data Flow:
1. Radar detects potential targets → provides raw data.
2. Target tracking algorithms smooth and predict target trajectories.
3. AI module evaluates threats, prioritizes targets.
4. Fire control computes intercept points, guidance commands.
5. Missile guidance adjusts trajectory toward predicted intercept point.
6. Feedback loop continues during missile flight.

---

## 2. **Designing in ANSI C89/90**

### Key Constraints:
- No dynamic memory allocation (`malloc()`) if you prefer portability.
- Use fixed-size arrays.
- Avoid complex data structures unless necessary.
- Use function pointers for flexibility.
- Implement simple AI as rule-based or heuristic decision logic.

---

## 3. **Incorporating AI and Advanced Decision-Making**

- Use **rules-based AI** for target prioritization, e.g., threat level, proximity, velocity.
- For more advanced AI, consider implementing:
  - **Fuzzy logic** for decision thresholds.
  - **Neural networks** (though complex in ANSI C89/90; may require rewriting external libraries).
  - **Genetic algorithms** for adaptive tactics.

---

## 4. **Extending and Refining**

- Add **sensor models** with detection probabilities and false alarms.
- Implement **communication delays**.
- Model **interception effects** with missile warheads.
- Use **visualization tools** (console ASCII graphics or external tools) for simulation output.

---

# **Summary**

Building a **NASAMS simulation with AI features** in **ANSI C89/90** involves:

- Designing fixed data structures for system components.
- Implementing detection, tracking, and guidance algorithms.
- Incorporating simple or rule-based AI for threat prioritization.
- Developing a modular main loop simulating the dynamic interactions.
- Extending with more sophisticated AI modules or data-driven decision systems as needed.

---

**Note:** Due to the constraints of ANSI C89/90, advanced AI (like neural networks) is challenging to implement directly; often, heuristic or rule-based systems are more feasible. For complex AI, consider interfacing rewriting external libraries or languages, or precomputing decision rules.

---

### **Modeling and Simulation of NASAMS**

If you're interested in developing a **computational or simulation model** for NASAMS, here are some steps and considerations:

#### 1. **Understanding System Architecture**
- Break down the system into subsystems: radars, command centers, launchers, missiles.
- Model interactions: detection, tracking, target assignment, missile guidance.

#### 2. **Choosing Simulation Tools**
- ANSI C89/90 rewriting libraries NumPy, SciPy, and others visualization tools.
- MATLAB/Simulink for dynamic system modeling.
- Specialized simulation environments like Modelica or defense-specific software.

#### 3. **Simulating Key Components**
- **Radar Detection:** Signal processing, target detection algorithms.
- **Target Tracking:** Kalman filters or particle filters for target state estimation.
- **Missile Guidance:** Guidance laws such as proportional navigation, control system dynamics.
- **Interception Logic:** Engagement zones, reaction times, and decision-making algorithms.

#### 4. **Validation and Testing**
- Use real-world data or published performance metrics.
- Run scenarios with varying threat parameters, sensor ranges, and system configurations.

---

### **Further Reading and Resources**

- **Official System Manuals & Technical Reports:**
  - Contact defense manufacturers or government agencies for detailed technical documentation.
- **Defense and Military Publications:**
  - Journals like *Jane’s International Defence Review* or *Defense Technology Review*.
- **Academic Papers:**
  - Research on missile guidance, radar tracking, and integrated air defense systems.
- **Standards & Protocols:**
  - NATO standards on missile defense interoperability and communication.

---

### **Summary**
NASAMS is a sophisticated, adaptable, and proven medium-range air defense system, integral to modern layered defense architectures. Its design emphasizes modularity, network integration, and rapid response, making it suitable for protecting critical assets against evolving aerial threats.

---

</p>

<p align="justify"> 

Developing a computational model of the NASAMS (National Advanced Surface-to-Air Missile System) is a complex task that involves understanding missile defense systems, control systems, radar technology, missile guidance, and simulation techniques. To support your research and development process, here are some highly recommended books that cover relevant topics:

### Recommended Books for Developing a Computational Model of NASAMS

#### 1. **Missile Guidance and Control Systems**
- **"Missile Guidance and Control System" by George M. Siouris**
  - Comprehensive coverage of missile guidance principles, control systems, and algorithms. Essential for understanding how to simulate missile trajectories and guidance logic.

#### 2. **Radar Systems and Signal Processing**
- **"Radar Signal Processing" by Carl Schurn**
  - Offers insights into radar detection, tracking, and signal processing techniques, crucial for modeling the radar component of NASAMS.

- **"Fundamentals of Radar Signal Processing" by Mark A. Richards**
  - Provides a solid foundation in radar signal processing and target tracking algorithms.

#### 3. **Simulation and Modeling Techniques**
- **"Modeling and Simulation of Dynamic Systems" by Robert L. Miller and William J. Long**
  - Guides on creating dynamic system models and simulations, applicable to missile defense systems.

- **"System Simulation: The Art and Science of Modeling Dynamic Systems" by Robert E. Shannon**
  - Focuses on simulation methodologies for complex systems.

#### 4. **Control Systems Engineering**
- **"Modern Control Engineering" by Katsuhiko Ogata**
  - Fundamental concepts in control system design and analysis, useful for modeling missile guidance and interceptor control.

- **"Feedback Control of Dynamic Systems" by Gene F. Franklin, J. David Powell, Abbas Emami-Naeini**
  - Detailed treatment of feedback control principles applicable to missile trajectory control.

#### 5. **Aerospace and Missile Dynamics**
- **"Introduction to Flight" by John D. Anderson**
  - Basic principles of aerodynamics and missile flight dynamics.

- **"Rocket Propulsion Elements" by George P. Sutton and Oscar Biblarz**
  - Insights into missile propulsion, which can inform propulsion modeling.

#### 6. **Military and Defense Systems**
- **"Introduction to Military Systems" by David A. Shlapak and Barry B. Watts**
  - Contextual understanding of military missile systems, including NASAMS.

---

### Additional Resources
- **Research Articles & Technical Papers**
  - Look for white papers, technical reports, and journal articles on missile defense modeling, radar tracking algorithms, and missile guidance systems.

- **Standards and Protocols**
  - Review MIL-STD and NATO standards related to missile systems and defense simulations.

---

### Final note:
Building a computational model of NASAMS is a multidisciplinary effort. Combining these resources with domain expertise and simulation tools (like MATLAB/Simulink, ANSI C89/90, or specialized defense modeling software) will give you a solid foundation.

</p>

---
#### "Think about math, don't know how to do calculations, go study"
---

#### Solution to hypothetical calculation problems

---

**STEPS - Clarification and Explanation (mathematical, physical and chemical problem)**

• 0. Hypothetical problem;

• 1. Mathematical, physical and chemical model and pseudocode;

• 2. Computational model and implementation.

---

<p align="justify">

##### Hypothetical Problem Statement: 
---

Here's a clearer, rephrased version of your hypothetical problem, along with its formal mathematical model and pseudocode.

 • Service schedule for military personnel

Suppose we need to create a weekly service schedule for military personnel. Each week, personnel are assigned to different shifts labeled as:

    • Black Schedule: Weekday shifts (Monday to Friday)
    • Red Schedule: Weekend and holiday shifts (Saturday, Sunday, and official holidays)

The goal is to assign personnel to these shifts over a planning period, ensuring fairness, respecting availability, and complying with operational constraints.

---
#### Computational problem - Trivial Algorithm
---

• Implement the Pseudoalgorithm in ANSI C89/90 Multiparadigm taking into BIG O complexity.

I'll help you translate this high-level pseudo-algorithm into a complete ANSI C89/90 program that demonstrates the core scheduling logic with explanations. Due to the constraints of C89/90 and the scope, this example will be simplified and focus on core concepts—initialization, iterative improvement, and assignment considering availability and fairness.

Overview of the Approach:

    Data Structures:
        Use arrays to store personnel info, availability, and assignments.
        Each iteration attempts to assign personnel to shifts, respecting availability and striving for workload balance.

    Algorithm Steps:
        Initialize all assignments to unassigned.
        Loop until convergence or max iterations:
            For each week and day:
                Assign personnel based on availability.
                Ensure only one person per shift.
            Calculate workload balance.
            Optionally, reassign to improve fairness.
        Output the final schedule.
---
#### Computational problem - Complex Algorithm
---

• Clarification and Improved Explanation:

After implementing the basic, straightforward version of the scheduling algorithm, the next step is to enhance it into a more sophisticated, intelligent system. This advanced version should incorporate principles of an expert system, enabling it to manage the scheduling process more effectively and adaptively.

What does this mean?

    From Trivial to Intelligent:
    The initial implementation performs simple greedy assignments based on availability and workload fairness. It doesn't consider complex constraints, preferences, or dynamic conditions.

    Expert System Approach:
    An expert system uses a knowledge base of rules, facts, and heuristics to emulate decision-making by a human expert. It can reason about multiple factors, handle uncertainty, and adapt its behavior based on evolving data.

    Goal of the Enhancement:
    To develop a knowledge-driven, rule-based scheduling system that can:
        Analyze personnel skills, preferences, and constraints.
        Consider service demand patterns.
        Balance workloads more intelligently.
        Handle special conditions (holidays, emergencies).
        Improve decision quality beyond simple heuristics.

How to Implement an Expert System for Scheduling in C (Conceptual Overview):

    Knowledge Base:
        Store rules and facts about personnel skills, availability, preferences, and constraints.
        For example:
            "Personnel P with skill S can only work on shifts requiring skill S."
            "Personnel should not exceed maximum weekly shifts."
            "Prefer personnel with fewer assigned shifts to balance workload."

    Inference Engine:
        Apply rules to make decisions:
            Which personnel to assign to each shift.
            How to resolve conflicts (e.g., multiple personnel equally qualified).
            When to prioritize certain personnel or shift types.

    Fact Updating:
        After each assignment, update the knowledge base with new facts:
            Updated workloads.
            Personnel availability changes.
            Shift requirements.

    Decision-Making Process:
        Use rule-based reasoning:
            For each shift, evaluate personnel based on rules.
            Select the best candidate(s) considering all constraints and rules.
            Assign accordingly.

    Learning and Adaptation (Optional):
        Incorporate feedback mechanisms to refine rules based on past scheduling outcomes.
        Adjust priorities dynamically.

</p>

<p align="justify">

---
#### Recommendation:
---

• Solve algebra questions, convert to pseudocodigo, and then implemented in ANSI C89/90 Multiparadigms Programming.

---

#### Reference Books: 

• "Algebra: Form and Function";

• "Fundamentals of Neural Networks: Architectures, Algorithms and Applications";

• "C Programming Language, 2nd Edition".

---

### Neural Network Principles and Applications

#### 0. Introduction 

Neural networks are fundamental to modern AI, enabling machines to perform tasks that require perception, reasoning, and learning. Continuous advancements in architectures and training methods are expanding their applications across diverse industries.

Here's an overview of Neural Network Principles and Applications:

#### Principles of Neural Networks

1. **Neurons and Architecture**
   - Neural networks consist of interconnected nodes called neurons or units organized in layers: input layer, hidden layers, and output layer.
   - Each connection has an associated weight that adjusts as learning progresses.

2. **Activation Functions**
   - Neurons process inputs through weighted sums, which are then transformed by an activation function (e.g., sigmoid, ReLU, tanh).
   - Activation functions introduce non-linearity, enabling the network to model complex patterns.

3. **Learning Process**
   - Neural networks learn through a process called training, where the model adjusts weights to minimize the difference between predicted and actual outputs.
   - This is typically done via algorithms like backpropagation combined with gradient descent.

4. **Backpropagation**
   - An algorithm that propagates the error backward through the network, updating weights to improve accuracy.
   - It ensures the network learns from mistakes iteratively.

5. **Generalization**
   - The goal is for the neural network to perform well on unseen data, not just the training set.
   - Techniques like regularization, dropout, and cross-validation help improve generalization.

---

#### Applications of Neural Networks

1. **Image and Video Recognition**
   - Convolutional Neural Networks (CNNs) excel in image classification, object detection, facial recognition, and video analysis.

2. **Natural Language Processing (NLP)**
   - Recurrent Neural Networks (RNNs), Transformers, and other architectures power language translation, sentiment analysis, chatbots, and voice assistants.

3. **Speech Recognition**
   - Neural networks convert spoken language into text, enabling virtual assistants and transcription services.

4. **Healthcare**
   - Used for medical image analysis, disease diagnosis, drug discovery, and personalized treatment plans.

5. **Autonomous Vehicles**
   - Neural networks process sensor data for object detection, path planning, and decision-making in self-driving cars.

6. **Financial Services**
   - Fraud detection, algorithmic trading, credit scoring, and risk management leverage neural network models.

7. **Gaming and Entertainment**
   - Neural networks enhance game AI, generate realistic graphics, and personalize content recommendations.

---

</p>

<p align="justify">

### 1. Neural Network Activation

Neural networks are a subset of machine learning models inspired by the structure and functioning of the human brain. They are designed to recognize patterns, learn from data, and make decisions or predictions. Neural networks have revolutionized many fields due to their ability to handle complex, high-dimensional data.

• Summation;

• Calculating Activation;

• Activation Functions;

• Bias Neurons.

---

#### 1.1 Understanding the Summation Operator

Seeing how this simple neural network is calculated will form the foundation for understanding training, and other more complex features of neural networks.
   
In this section, we will take a quick look at the summation operator. The summation operator, represented by the capital Greek letter sigma can be seen in Equation "Summation" Below.

<img width="1096" height="112" alt="Image" src="https://github.com/user-attachments/assets/67e2b33d-8838-45ac-b664-2b503b660fbb" />

The above equation is a summation. If you are unfamiliar with sigma notation, it is essentially the same thing as a programming for loop. Figure "Summation Operator to Code" below shows Equation "Summation" above reduced to pseudocode. 

</p>

<img width="1145" height="355" alt="Image" src="https://github.com/user-attachments/assets/5b713cdf-c3d1-4920-bd87-da7b78542d06" />

```c

pseudocode

Initialize sum to 0
For i from 1 to 10 do
    sum = sum + (2 * i)
End For
Return sum
```
<p align="justify">  
As you can see, the summation operator is very similar to a for loop. The information just below the sigma symbol species the stating value and the indexing variable. The information above the sigma species the limit of the loop. The information to the right of sigma specifies the value that is being summed.
</p>

```c

ANSI C89/90 Multiparadigms

#include <stdio.h>

/* Function to compute the sum based on the pseudocode */
int compute_sum();

int main() {
    int result;

    result = compute_sum();
    printf("The sum is: %d\n", result);

    return 0;
}

/* Implementation of the sum calculation */
int compute_sum() {
    int i;
    int sum = 0; /* Initialize sum to 0 */

    for (i = 1; i <= 10; i++) {
        sum = sum + (2 * i); /* sum = sum + (2 * i) */
    }

    return sum; /* Return the computed sum */
}

```
---

#### 1.2. Calculating a Neural Network

<p align="justify">
We will begin by looking at how a neural network calculates its output. You should already know the structure of a neural network from the book’s introduction. Consider a neural network such as the one in figure "A Simple Neural Network" below:
</p>

<img width="1141" height="439" alt="Image" src="https://github.com/user-attachments/assets/9221248e-ee25-4c78-8eb6-a2e3c9547cc0" />

<p align="justify">
This neural network has one output neuron. As a result, it will have one output value. To calculate the value of this output neuron (O1), we must calculate the activation for each of the inputs into O1. The inputs that feed into O1 are H1, H2 and B2. The activation for B2 is simply 1.0, because it is a bias neuron. However, H1 and H2 must be calculated independently. To calculate H1 and H2, the activations of I1, I2 and B1 must be considered. Though H1 and H2 share the same inputs, they will not calculate to the same activation. This is because they have different weights. The weights are represented by lines in the above diagram.
</p>

<p align="justify">
First we must look at how one activation calculation is done. This same activation calculation can then be applied to the other activation calculations. We will examine how H1 is calculated. Figure "Calculating H1 Activation" below shows only the inputs to H1.
</p>

<img width="1148" height="330" alt="Image" src="https://github.com/user-attachments/assets/b443d725-0297-4338-803d-34030824507e" />

<p align="justify">
We will now see how to calculate H1. This relatively simple equation is shown in equation in figure below.
</p>

<img width="1086" height="123" alt="Image" src="https://github.com/user-attachments/assets/10e72bff-bab2-4a52-a752-5853aa83d419" />

<p align="justify">
To understand Equation Above, we first examine the variables that go into it. For the above equation we have three input values, given by the variable i. The three input values are input values of I1, I2 and B1. I1 and I2 are simply the input values that the neural network was provided to compute the output. B1 is always 1, because it is the bias neuron.
</p>

<p align="justify">
There are also three weight values considered w1, w2 and w3. These are the weighted connections between H1 and the previous layer. Therefore, the variables to this equation are:
</p>

```c

pseudocode

/* Define number of connections */
n = 3

/* Initialize input values */
i[1] = first input value to the neural network 
i[2] = second input value to the neural network
i[3] = 1 bias input B1

/* Initialize weights */
w[1] = weight from I1 to H1
w[2] = weight from I2 to H1
w[3] = weight from B1 to H1 

/* Initialize sum */
sum = 0

/* Perform the summation (sigma) */
for c = 1 to n do
    sum = sum + (w[c] * i[c])
end for

/* Apply the activation function */
sum = A(sum)
```

```c

ANSI C89/90 Multiparadigms

#include <stdio.h>

/* Prototype for the activation function A */
double A(double x);

int main() {
    int n = 3; /* number of connections */

    /* Initialize input values */
    double i[4]; /* Using 1-based indexing for clarity, ignoring i[0] */
    i[1] = first input value to the neural network;
    i[2] = second input value to the neural network;
    i[3] = 1.0; /* bias input B1, typically set to 1 */

    /* Initialize weights */
    double w[4]; /* Using 1-based indexing for clarity, ignoring w[0] */
    w[1] = weight from I1 to H1;
    w[2] = weight from I2 to H1;
    w[3] = weight from B1 to H1;

    double sum = 0.0;
    int c;

    /* Perform the summation (sigma) */
    for (c = 1; c <= n; c++) {
        sum = sum + (w[c] * i[c]);
    }

    /* Apply the activation function */
    sum = A(sum);

    /* Output the result */
    printf("Output after activation: %f\n", sum);

    return 0;
}

/* Example activation function: threshold at 0 */
double A(double x) {
    if (x > 0.0)
        return 1.0;
    else
        return 0.0;
}
```

<p align="justify">
Though the bias neuron is not really part of the input array, a one is always placed into the input array for the bias neuron. Treating the bias as a forward-only neuron makes the calculation much easier. To understand equation in figure above we will consider it as pseudocode.
</p>

```c

pseudocode

/* Declare arrays for weights and input values */
double w[3]   /* the weights */
double i[3]   /* the input values */

/* Initialize sum to zero */
double sum = 0

/* Perform the summation (sigma) */
for c = 0 to 2 do
    sum = sum + (w[c] * i[c])
end for

/* Apply the activation function */
sum = A(sum)

```
<p align="justify">
Here we sum up each of the inputs times its respective weight. Finally this sum is passed to an activation function. Activation functions are a very important concept in neural network programming. In the next section we will examine activation functions.
</p>

```c

ANSI C89/90 Multiparadigms

#include <stdio.h>

/* Prototype for the activation function A */
double A(double x);

int main() {
    /* Declare weight and input arrays */
    double w[3] = { initialize with your weights };
    double i[3] = { initialize with your input values };
    double sum = 0.0;
    int c;

    /* Perform the summation (sigma) */
    for (c = 0; c <= 2; c++) {
        sum = sum + (w[c] * i[c]);
    }

    /* Apply the activation function */
    sum = A(sum);

    /* Output the result */
    printf("Result after activation: %f\n", sum);

    return 0;
}

/* 
 * Implementation of the activation function A
 * For example, a simple threshold function
 *
 */
double A(double x) {
    /* You can modify this function as needed */
    if (x > 0.0)
        return 1.0;
    else
        return 0.0;
}

```
#### 1.3. Activation Functions

<p align="justify">

Activation functions are used very commonly in neural networks. Activation functions serve several important functions for a neural network. The primary reason to use an activation function is to introduce non-linearity to the neural network. Without this non-linearity a neural network could do little to learn non-linear functions. The output that we expect neural networks to learn is rarely linear.

The two most common activation functions are the sigmoid and hyperbolic tangent activation function. The hyperbolic tangent activation function is the more common of these two, as has a number range from -1 to 1, compared to the sigmoid function which is only from 0 to 1.

<img width="1096" height="112" alt="Image" src="https://github.com/user-attachments/assets/22ea498f-bf14-4fc2-ba41-d157446eab12" />

The hyperbolic tangent function is actually a trigonometric function. However, our use for it has nothing to do with trigonomy. This function was chosen for the shape of its graph. You can see a graph of the hyperbolic tangent function in figure "The Hyperbolic Tangent Function" below.

<img width="1092" height="448" alt="Image" src="https://github.com/user-attachments/assets/6ed91577-0fdc-4c7b-8154-83152bd77e13" />

</p>

---

### Restoration of Hebrew, Rebuilding the David Dynasty And Days of Days: 

---

<p align="justify">
   
**JPS Bible**
---
   • Amos - Chapter 9: 11
   
   **On that day, I will raise up the fallen Tabernacle of David, and I will close up their breaches, and I will raise up its ruins, and build it up as in the days of yore.**

   • Isaiah - Chapter 43: 11-14

   **None but me,  GOD; Beside Me, none can grant triumph. I alone foretold the triumph And I brought it to pass; I announced it, And no strange god was among you. So you are My witnesses—declares GOD—And I am God. Ever since day was, I am the One; None can deliver from My hand. When I act, who can reverse it? Thus said  GOD, Your Redeemer, the Holy One of Israel: For your sake I send to Babylon; I will bring down all [her] bars, And the Chaldeans shall raise their voice in lamentation.**
   
   • Isaiah - Chapter 46: 9-13
   
   **Bear in mind what happened of old; For I am God, and there is none else, I am divine, and there is none like Me. I foretell the end from the beginning,
And from the start, things that had not occurred. I say: My plan shall be fulfilled; I will do all I have purposed. I summoned that swooping bird from the East; From a distant land, the man for My purpose. I have spoken, so I will bring it to pass; I have designed it, so I will complete it. Listen to Me, you stubborn of heart, Who are far from victory: I am bringing My victory close; It shall not be far, And My triumph shall not be delayed. I will grant triumph in Zion To Israel, in whom I glory.**

   • Malachi - Chapter 3: 22-24
   
   **Keep in remembrance the teaching of Moses, My servant-the laws and ordinances which I commanded him in Horeb for all Israel. Lo, I will send you Elijah the prophet before the coming of the great and awesome day of the Lord, that he may turn the heart of the fathers back through the children, and the heart of the children back through their fathers-lest I come and smite the earth with utter destruction.**
   
</p>

---
#### The Science of In-Fighting By Wong Shun Leung
---

![Image](https://github.com/user-attachments/assets/c4a13e22-4622-4b61-9842-5db827512937)

https://youtu.be/YnzXjJC477E

---

#### The Art of High-impact Kicking By Hwang Jang Lee

---


![Image](https://github.com/user-attachments/assets/4a18052c-8184-47a8-8cdb-00bb2caa0dae)

---

• 0. The Art of High-Impact Kicking ( 1 / 5 )

https://youtu.be/NGu86RX3eqg

• 1. The Art of High-Impact Kicking ( 2 / 5 )

https://youtu.be/-29odVJ57nY

• 2. The Art of High-Impact Kicking ( 3 / 5 )

https://youtu.be/XE0UVcWd6HU

• 3. The Art of High-Impact Kicking ( 4 / 5 )

https://youtu.be/CoNJY8mv57k

• 4. The Art of High-Impact Kicking ( 4 / 5 )

https://youtu.be/CxyFv_-Z5S0
