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
### Recommendation, solve algebra questions, convert to pseudocodigo, and then implemented in ANSI C89/90.
---
### Reference Books: 

• "Algebra: Form and Function";

• "Fundamentals of Neural Networks: Architectures, Algorithms and Applications".

• "C Programming Language, 2nd Edition";

---

### Neural Network Principles and Applications

• Summation;

• Calculating Activation;

• Activation Functions;

• Bias Neurons.

Seeing how this simple neural network is calculated will form the foundation for understanding training, and other more complex features of neural networks.

### 1. Understanding the Summation Operator

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

### • ANSI C89/90 Multiparadigms

```c
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

