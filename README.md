# cs4210-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CS4210 Assignment #4 Solved](https://www.ankitcodinghub.com/product/cs-4210-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110127&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4210  Assignment #4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Note 1: Your submission header must have the format as shown in the above-enclosed rounded rectangle.

Note 4: All submitted materials must be legible. Figures/diagrams must have good quality. Note 5: Please use and check the Blackboard discussion for further instructions, questions, answers, and hints.

1.&nbsp; Consider the combinatorial optimization problem known as the “0-1 Knapsack problem”, where we need to fill a knapsack with objects of different weights and values. The goal is to fill the Knapsack with the highest possible value, not exceeding its maximum capacity (weight supported) and carrying only one type of each object inside. Below is the list of available objects, with their respective weights and values.

Maximum weight capacity (C) = 15 kg.

Object Tablet Laptop Projector

Weight (w) 5 kg 8 kg 10 kg

Value (v) $ 570,00 $ 710,00 $ 640,00

Apply generational Genetic Algorithms (𝑟 = 1) to solve this optimization problem strictly following the planning below.

• Representation: binary, identifying whether the object should be included or not, with the 1st, 2nd, and 3rd positions of the chromosomes referring to the Tablet, Laptop, and Projector respectively.

• Initial population (Chromosomes) : (C1=000, C2=001, C3=010, C4=100). Population size should remain the same (4 individuals) over time.

• Fitness function: ∑𝑛𝑖=1 𝑣𝑖𝑥𝑖, with n being the number of objects in the knapsack and 𝑥𝑖 being the number of instances of object 𝑖 to include in the knapsack (1, if the object is included and 0, otherwise).

• Constraint: ∑𝑛𝑖=1 𝑤𝑖𝑥𝑖 ≤ 𝐶.

• Penalty criterion: If the maximum capacity of the knapsack (C) is exceeded, discard the obtained chromosome (offspring) and replicate the best among the two of its parents.

• Selection method: roulette wheel (simulation)

• Crossover strategy: single-point crossover with mask 110 in the 1st generation, single-point crossover with mask 100 in the 2nd generation. Use the following chromosomes to perform crossover (simulating the process of spinning the roulette wheel) according to the relative fitness (sectors of a roulette wheel), generating two offspring for each crossover:

• (2nd and 3rd) and (2nd and 1st) in the 1st generation

• (1st and 1st) and (1º and 2nd) in the 2nd generation

• Mutation: on the 3rd bit of the first chromosome 101 generated for the 3rd generation.

• Termination criteria: stop in the 3ª generation. Return the best chromosome found until then.

Summary of the optimization function:

𝑛

max ∑ 𝑣𝑖𝑥𝑖

𝑖=1

subject to 𝑤𝑖𝑥𝑖 ≤ 𝐶 𝑎𝑛𝑑 𝑥𝑖 ∈ {0,1} Solution format:

1st generation (C1, C2, C3, C4):

Fitness(C1) = ? Pr(C1) = ?

Fitness(C2) = ? and weigh ? Pr(C2) = ?

Fitness(C3) = ? and weight ? Pr(C3) = ? Fitness(C4) = ? and weight ? Pr(C4) = ?

Suppose C2 and C4 and C2 and C3 are selected for crossover:

C2 = 00|1 → C5 = ? C2 = 00|1 → C7 = ?

C4 = 10|0 → C6 = ? C3 = 01|0 → C8 = ? Apply mutation now on C5, C6, C7, C8 if specified.

2nd generation (?, ?, ?, ?)

…

3rd generation (?, ?, ?, ?)

…

2. [20 points] Consider the dataset below.

Outlook Temperature PlayTennis

Sunny Hot No

Overcast Cool Yes

Overcast Hot Yes

Rain Cool No

Overcast Mild Yes

We will apply steady state Genetic Algorithms (𝑟 = 0.5) to solve this classification problem, by using a similar approach of the Find-S algorithm. If the instance matches the rule pre-condition of the chromosome, you predict according to its post-condition, otherwise you predict the opposite class (there must be a prediction for each instance then). Follow the planning below to build your solution.

• Representation: single if-then rule by using bit strings (binary encoding).

o Outlook &lt;Sunny, Overcast, Rain&gt;

o Temperature &lt;Hot, Mild, Cool &gt;

o Examples:

o Outlook = Overcast → 010 o Outlook = Overcast ˅ Rain → 011 o Outlook = Sunny ˅ Overcast ˅ Rain → 111

o Outlook = (Overcast ˅ Rain) ˄ (Temperature = Hot) → 011100 o Outlook = Sunny ˄ Temperature = Hot then PlayTennis = yes → 1001001

• Initial population (Chromosomes) : (C1=1001001, C2=0100101, C3=1011000, C4=1101100). Population size should remain the same (4 individuals) over time.

• Fitness function: accuracy • Penalty criterion: no penalty.

• Selection method: The best two chromosomes are carried over to the next generation. The other two are generated by using the roulette wheel (simulation). In case of a tie, the newest chromosomes should have a higher rank.

• Crossover strategy: single-point crossover with mask 1110000 in the 1st generation, two-point crossover with mask 0001100 in the 2nd generation. Use the following chromosomes to perform crossover (simulating the process of spinning the roulette wheel) according to the relative fitness (sectors of a roulette wheel), generating two offspring for each crossover: o (1st and 3rd) in the 1st generation o (1st and 2nd) in the 2nd generation

• Mutation: on the 6th bit of the chromosome 1011000 generated for the 3rd generation.

• Termination criteria: accuracy = 1.0. Return the corresponding chromosome.

Solution format:

1st generation (C1, C2, C3, C4):

Fitness(C1) = ? Pr(C1) = ?

Fitness(C2) = ? Pr(C2) = ?

Fitness(C3) = ? Pr(C3) = ? Fitness(C4) = ? Pr(C4) = ?

Suppose C1 and are C2 are selected for crossover:

C1 = 100|1001 → C5 = ?

C2 = 010|0101 → C6 = ? Apply mutation now on C5, C6 if specified.

2nd generation (?, ?, ?, ?)

…

3rd generation (?, ?, ?, ?)

…

𝑥1 𝑥2 𝑥1 𝐴𝑁𝐷 𝑥2

0 0 0

0 1 0

1 0 0

1 1 1

3. [20 points] Train the perceptron network below to solve the logical AND problem correctly classifying the dataset instances. Use the parameters: learning rate ɳ=0.4, initial weights = 1, and activation function = heaviside.

Solution format: Include the solution table (as illustrated in the lecture) with all variables and values calculated for each iteration. Hint: you can use an Excel spreadsheet to solve this problem and add your solution table here.

4. [20 points] Train the perceptron network below to solve the logical NOT problem correctly classifying the dataset instances. Use the parameters: learning rate ɳ=0.1, initial weights = 0, and activation function = heaviside.

𝑥1 𝑁𝑂𝑇 𝑥1

0 1

1 0

𝑥 1 Datset

Solution format: Include the solution table (as illustrated in the lecture) with all variables and values calculated for each iteration. Hint: you can use an Excel spreadsheet to solve this problem and add your solution table here.

5. [20 points] Complete the Python program (perceptron.py) that will read the file optdigits.tra to build a Perceptron classifier. You will simulate a grid search, trying to find which combination of two Perceptron hyperparameters (eta0, random_state) leads you to the best prediction performance. To test the accuracy of those distinct models, you will also use the file optdigits.tes. You should update and print the accuracy, together with the hyperparameters, when it is getting higher, printing at the end the highest accuracy and corresponding hyperparameters.
