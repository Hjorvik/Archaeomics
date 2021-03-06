Building some intuition with the Wright-Fisher model
===============

# Thinking forwards in time

Go to:
https://phytools.shinyapps.io/drift-selection/

This is a Wright-Fisher simulator. The plotted line represents the frequency of one allele as the populations evolves over time. For this tutorial, we will only simulate neutral alleles, so we won't modify the fitnesses of the 3 genotypes. Set the starting frequency of the allele at 50%. Set the population size to 20 and the number of generations to 400. Now generate 10 simulations. How many simulations result in the allele being either fixed (100% frequency) or extinct (0% frequency) by the time the simulation ends? Try increasing the population size to 500, but keep the same number of generations as before. How many simulations result in fixation or extinction now? How many simulations have the allele still segregating in the population? Why do you think this is so?

# Thinking backwards in time

Go to:
https://phytools.shinyapps.io/coalescent-plot/

This is also a Wright-Fisher simulator, but in this case, we can actually observe each individual in each generation, who they're descended from and who their offspring are.

Set the number of generations to 10 and the number of individuals per generation to 5. Now, look at the present-day generation (the bottom-most row). Randomly pick any two individuals (ask your partner to give you two numbers between 1 and 5). Take a blank piece of paper. Now check: Have the two randomly-picked individuals coalesced (found a common ancestor) by the time you reach 10 generations into the past (the top-most row)? If so, write down a tick mark on your blank paper. If not, write down a cross. Repeat this exercise 9 more times, each time generating a new simulation by clicking on the button "new plot". How many tick marks and crosses do you have at the end?

Now set the number of individuals per generation to 50. Keep the number of generations at 10. Generate 10 simulations and repeat the exercise we just performed. This time, you will have to ask your partner to give you two numbers between 1 and 50. How many tick marks and how many crosses do you have? What does this tell you about the coalescent rate? Does this rate increase or decrease with increasing population size? Why do you think this is so?
