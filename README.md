### About Me, Davada Beni Zaita

<p align="justify">  
I am a passionate engineer and innovator dedicated to pushing the boundaries of technology and shaping the future. With a steadfast commitment to excellence and a curiosity that fuels continuous learning, I thrive at the intersection of engineering and innovation. Harnessing cutting-edge advancements and state-of-the-art solutions, I strive to develop impactful technologies that solve real-world problems and elevate industries. My journey is driven by a relentless pursuit of innovation, a meticulous attention to detail, and an unwavering belief that technology can transform lives. As a forward-thinker in the realm of engineering, I embrace emerging trends such as artificial intelligence, automation, and sustainable design, integrating them into my projects with precision and creativity. My goal is to contribute to a smarter, more sustainable future through engineering excellence and innovative thinking.I believe that true progress stems from collaboration, curiosity, and a passion for discovery. With each challenge I face, I see an opportunity to pioneer new solutions and set new standards of excellence in technology and engineering.
</p>

![Image](https://github.com/user-attachments/assets/9085094a-282e-4f9d-b04b-ec01b8924d42)

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

---
### "Think about math, don't know how to do calculations, go study"
---
### Recommendation:

• Solve algebra questions, convert to pseudocodigo, and then implemented in ANSI C89/90.

---
### Reference Books: 

• "Algebra: Form and Function";

• "Fundamentals of Neural Networks: Architectures, Algorithms and Applications".

• "C Programming Language, 2nd Edition";

---

### 1. Neural Network Principles and Applications

• Summation;

• Calculating Activation;

• Activation Functions;

• Bias Neurons.

Seeing how this simple neural network is calculated will form the foundation for understanding training, and other more complex features of neural networks.

### 1.1 Understanding the Summation Operator

### • Summation Operator reduced to pseudocode 

<p align="justify">
In this section, we will take a quick look at the summation operator. The summation operator, represented by the capital Greek letter sigma can be seen in Equation Below. The above equation is a summation. If you are unfamiliar with sigma notation, it is essentially the same thing as a programming for loop.
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

### 1.2. Calculating a Neural Network

<p align="justify">
We will begin by looking at how a neural network calculates its output. You should already know the structure of a neural network from the book’s introduction. Consider a neural network such as the one in below:
</p>

<img width="1141" height="439" alt="Image" src="https://github.com/user-attachments/assets/9221248e-ee25-4c78-8eb6-a2e3c9547cc0" />

<p align="justify">
This neural network has one output neuron. As a result, it will have one output value. To calculate the value of this output neuron (O1), we must calculate the activation for each of the inputs into O1. The inputs that feed into O1 are H1, H2 and B2. The activation for B2 is simply 1.0, because it is a bias neuron. However, H1 and H2 must be calculated independently. To calculate H1 and H2, the activations of I1, I2 and B1 must be considered. Though H1 and H2 share the same inputs, they will not calculate to the same activation. This is because they have different weights. The weights are represented by lines in the above diagram.
</p>

<p align="justify">
First we must look at how one activation calculation is done. This same activation calculation can then be applied to the other activation calculations. We will examine how H1 is calculated. Figure below shows only the inputs to H1.
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
    i[1] = /* first input value to the neural network */;
    i[2] = /* second input value to the neural network */;
    i[3] = 1.0; /* bias input B1, typically set to 1 */

    /* Initialize weights */
    double w[4]; /* Using 1-based indexing for clarity, ignoring w[0] */
    w[1] = /* weight from I1 to H1 */;
    w[2] = /* weight from I2 to H1 */;
    w[3] = /* weight from B1 to H1 */;

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
    double w[3] = { /* initialize with your weights */ };
    double i[3] = { /* initialize with your input values */ };
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
 */
double A(double x) {
    /* You can modify this function as needed */
    if (x > 0.0)
        return 1.0;
    else
        return 0.0;
}

```
