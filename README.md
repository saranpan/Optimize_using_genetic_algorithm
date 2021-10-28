# Optimize_using_genetic_algorithm
Numerical way to optimize 


<fieldset>
Problem :

Data: We import from *data.world* which contain the nutrient for each food

**constraint** :<br> 1) the sum of the sugar from all of 8 foods is not higher than 25g
           <br> 2) Cannot contain the duplicated food
          
**onjective function** : Maximizing the fiber (g)
<br><br>
**Fitness function** : the threshold update everytime with min(fiber) + 0.8(max(fiber)-min(fiber))

Since we don't know the optimal solution, so I decided to stop iterate more gene pool when the max fiber stay for 100 iterations
</fieldset>
